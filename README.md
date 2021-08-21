# frontend

## 참고링크

https://www.w3schools.com/

https://codesandbox.io/

## HTML

### INTRODUCTION

https://www.w3schools.com/html/html_intro.asp

> 웹 페이지 구조 표시
> 웹 페이지 콘텐츠 표시
>
> - 텍스트 컨텐츠
> - 멀티미디어 컨텐츠 :이미지 ,비디오, 오디오

### HTML Element

https://www.w3schools.com/html/html_elements.asp

`(backtick)

```
<tagname>Contents</tagname>

*시작태그만 있는 경우 :Empty Element
```

> 포함관계(nested)

```
<html>
  <body>
    <h1>Heading</1>
  </body>
</html>
```

> html-body-h1 관계
>
> html : body와 관계--부모요소/h1과 관계--조상요소
>
> body : h1과 관계 부모요소/html과 관계--자식요소
>
> h1 : body와의 관계-자식요소/html과 관계 --자손요소

### html Atributes

### html hedings

https://www.w3schools.com/html/html_headings.asp

h1-h6: 제목태그(H-heading)

### html Paragraph

https://www.w3schools.com/html/html_paragraphs.asp

### html Link

https://www.w3schools.com/html/html_links.asp

a : anchor

> URL(Uniform Resource Locator) : 파일식별자(위치표시), 가장 넓은 의미의 인터넷 주소
> 인터넷 주소
>
> - IP(Internet Protocol) : 숫자로 구성되 주소(192.168.0.1)
> - Domain Name : WWW.naver.com / DNS(Domain Name Server)
> - blog.naver.com/blog/12345 => URL

### html file 경로

https://www.w3schools.com/html/html_filepaths.asp

절대 vs 상대

- 경로 위치 표시 방식
- 경로 표시 기준의 변경 여부
- EX) 대한민국 서울특별시 서초구 ~동 대호빌딩 803호
- 출발지 위치에 상관없이 항상 찾아갈 수 있도록 표시
- EX)도메인주소 /상세경로=>https://www.naver.com/blog/image.jpg
-
- ex) 강남역 12번 출구에서 3분 대호빌딩
- 출발지 위치를 기준으로 표시
- ex)상세경로=> /blog/image.jpg|| image.jpg

###html list
https://www.w3schools.com/html/html_lists.asp

> 중첩목록 (nested list)

###html table
https://www.w3schools.com/html/html_tables.asp

###html Block & inLine
https://www.w3schools.com/html/html_blocks.asp

포함관계
블럭요소에는 다른 블럭요소, 인라인요소

###html id & class
https://www.w3schools.com/html/html_id.asp
https://www.w3schools.com/html/html_classes.asp

> id attribute
>
> 하나의 이름만 지정할수 있다.

class attribute
한문서내에서 여러번 중복사용할수 있습니다.
Class는
