# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks, space 2개, <br/>)
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
무궁화 삼천리 화려 강산</br>
대한사람.

# 강조(Emphasis)  
_이탤릭_  
**두껍게**
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List, OL태그와 비슷, 1만 넣어도, 들여쓰기2번)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록    
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록 
- 순서가 필요하지 않은 목록

# 링크
<a href="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)

<a href="https://google.com" title="NAVER로 이동">NAVER</a>  
[NAVER](https://google.com "NAVER로 이동")

# 이미지 (!추가해야함)
![HEROPY](https://heropy.blog/css/images/logo.png)

# 이미지 클릭시 링크됨
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/css/images/logo.png)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  

> (네이버 국어 사전)
>> 중첩된 인용문
>>> 중중첩된 인용문1
>>> 중중첩된 인용문2
>>> 중중첩된 인용문3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
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
$git commit -m 'Study Markdown'
```

```plaintext
마크다운 연습중입니다.
```

# 표(Table), : 정렬, 

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치상 부모요소 | X
fixed | 뷰포트 | X

# 원시 HTML (Raw HTML), HTML 문법사용
동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://google.com" target="_blank">GOOGLE</a>

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">

# 수평선
---

***

___
