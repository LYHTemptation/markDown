# Markdown

## 특징

> 텍스트 기반의 가벼운 마크업 언어이다.
>
> 다양한 서식과 구조를 지원하며 문서에 즉각적으로 반영이 가능하다.
>
> 단순 텍스트 문법으로 내용을 작성하며 다양한 환경에서 변환하여 보여진다.

## 활용 예

* **README.me**

  * Github등 사이트에서 READ.md인것을 보여준다.

  * 오픈소스의 공식 문서를 작성하거나 개인 프로젝트의 프로젝트 소개서로 활용

  * 모든 페이지에 README.md를 넣어 문서를 바로 볼 수 있도록 활용

    ![](C:\Users\admin\Desktop\multiCamfolder\readme.jpg )

* **기술 블로그**

  * 다양한 기술블로그에서 정적사이트 생성
  * Jekyll, Gatsby, Hugo, Hexo 등을 통해 작성된 마크다운을 HTML, CSS, JS 파일 등으로 변환
  * Github pages 기능을 통해 호스팅 (외부 공개)
  * ![](C:\Users\admin\Desktop\multiCamfolder\기술블로그.png)

* **기타**

  * 개발 환경 뿐 아니라 일반 SW에서도 사용

  * Jupyter notebook에는 별도의 마크다운 셀이 있어 데이터 분석 등을 하는 과정에서 프로젝트 내용과 분석 결과를 정리함

  * Notion과 같은 메모/노트 필기 SW에서도 기본 문법으로 마크다운을 채택

    <img src="C:\Users\admin\Desktop\multiCamfolder\notion.png" style="zoom:20%;" />

    

## 문법

**Heading** - 문서의 제목이나 소제목으로 사용

 * #의 개수에 따라 대응되는 수준이 있으며 h1 ~ h6까지 표현 가능
 * 문서의 구조를 위해 작성되며 글자 크기를 조절하기 위해 사용되어서는 안됨

**List** - 나열

* list는 순서가 있는 리스트(ol)와 순서가 없는 리스트(ul)로 구성
* Tab과 shift + Tab으로 하위 목록을 자유롭게 구성
* 1.을 입력후 사용(ol)
* -, *, + 중 사용 가능(ul)

**Fenced Code Block** - 코드 블록

* 코드 블록은 backtick 기호 3개를 활용하여 작성(`)

* 코드 블록은 특정 언어를 명시하면 Syntax Highlighting 적용 가능

* java

  * ```java
    /* 주석 */
    // 주석
    public class HelloWorld{
        public static void main(String args[]){
     		System.out.println("hello world");   
        }
    }
    ```

* python

  * ```python
    # 주석
    // 주석 x
    print('hello world!')
    ```

**Inline Code Block**

* 코드 블록은 backtick 기호 1개를 인라인에 활용하여 작성

**Link**

* [](url)을 통해 링크를 작성 가능
* 특정 파일들 포함하여 연결 가능
* [https://github.com/LYHTemptation](url)

**이미지**

* ![]()을 통해 이미지를 사용 가능
* 특정 파일들 포함하여 연결 가능
* 드라그앤드랍 활용 가능

**Blockquotes(인용문)**

* '>'을 통해 인용문을 작성

**Table**

* 상단 메뉴 > 본문 > 표 > 표 삽입

**text강조**

* 굵게(bold), 기울임(ltalic)을 통해 특정 글자들을 강조
* **,__(굵게)
* *,_(기울임)

**수평선**

* 3개 이상의 ***,---,___ 사용

