# 제목(Header)

# 제목 1
## 제목 2
### 제목 3

# 문장(paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(line Breaks)
띄어쓰기 2번(줄바꿈)
<br/>

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)
_기호를 사용하용하면 그 사이에 넣으면 바뀐다  
**기호를 사용하면 두껍게
~~기호를 사용하면 취소선  
u를 사용하면 밑줄

_이텔릭_  
**두껍게**  
_**이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)
숫자.을 사용하면 리스트로 바뀐다  
html의 ol 과 같은 것  
를 사용해 목록을 넣을 수 있다

1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록

1. 순서가 필요한 목록
- 순서가 필요한 목록
- 순서가 필요한 목록
- 순서가 필요한 목록 
    - 순서가 필요한 목록
- 순서가 필요한 목록
- 순서가 필요한 목록

# 링크(Links)
[ ]에 링크 ( ) 주소를 입력해서 사용한다

[GOOGLE](https://www.google.co.kr/)  
[NAVER](https://naver.com "NAVER로 이동!")

# 이미지(images)
!를 입력하고 [ ]에 링크 ( ) 주소를 입력해서 사용한다

![HEROPY](https://heropy.blog/css/images/logo.png)

#인용문(BlockQuote)

>남의 말이나 글에서 직접 또는 간접적으로 따온 문장.  
>(네이버 국어 사전)

>인용문을 작성하세요!
>>중첩된 인용문
>>>중첩된 인용문 1
>>>중첩된 인용문 2
>>>중첩된 인용문 3

# 인라인(inline) 코드 강조
`백틱 기호를 사용

CSS에서 `background` 혹은 `background-imge`  혹성으로 요소에 배경 이미지를 삽입할 수 있습니다

# 블록(block) 코드 강조
`백틱기호 3개를 사용해서 코드를 문자로 표현할 수 있다.


```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ git commit -m "Study Markdown"
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리 나라 만세
```

# 표(Table)
각 행을 버티컬바로 표현한다 ( | )

position 속성

값 | 의미 | 기본값
--|--|--|
static | 기준 없음 | O  
relative | 요소 자신 | O  
absolute | 위치 상 부모 요소 | X  
fixed | 뷰포트 | X  

# 원시 HTML(Raw HTML)

동해물과 <u>백두산</u>이 마르고 닳도록</br>
하느님이 보우하사 우리나라 만세

<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>

# 수평선(Horizontal Rule)

---
***
___

동해물과 <u>백두산</u>이 마르고 닳도록</br>
___
하느님이 보우하사 우리나라 만세