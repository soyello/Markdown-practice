
# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장 (Paragraph)
나는 행복해질거다.
반드시 사랑받고 싶다. 행복하고 싶다. 평안하고 싶다.

# 줄바꿈 (Line Breaks) - 띄어쓰기 두번 or html의 브레이크 태그
나는 행복해질거다.  
지금도 행복할 수 있다.  
필사적으로 행복하자.<br/>
혼자서도 가치있어지자.

# 강조(Emphasis)
_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~(물결 표시 두개)  
<u>밑줄</u> -> 실제 html에서는 사용 거의 안하고 css에서 적용한다.

# 목록(List)
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

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https;//google.com)

<a href="https://naver.com" title="NAVER로 이동">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동")

# 이미지(image)
![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

이미지 선택시 블로그 주소로 이동

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.   
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문!

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블럭(block) 코드 강조

```html 
<a href="https://google.com">GOOGLE</a>
```

# 표(Table)

position 속성

값 | 의미 | 기본값
:--|:--:|--:
왼쪽 정렬 | 가운데 정렬 | 오른쪽 정렬
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X
