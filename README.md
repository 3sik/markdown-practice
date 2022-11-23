# 제목 (Header)
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
꼭 ```#``` 다음에 띄어쓰기 해줘야됨.

# 문장 (Paragraph)
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

줄바꿈 처리가 안 됨.

# 줄바꿈 (Line Breaks)

띄어쓰기 2번 또는 ```<br>```

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산  
대한 사람 대한 으로 길이 보전하세  

# 강조 (Emphasis)

```_이텔릭_``` _이텔릭_ <br>
```**두껍게**``` **두껍게** <br>
```_**이텔릭 + 두껍게 합체**_```  _**이텔릭 + 두껍게 합체**_<br>
```~~취소선~~``` ~~취소선~~ <br>
```<u>밑줄<u>``` <u>밑줄</u> <br>

# 목록 (List)
1. 순서가 필요한 목록
2. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

숫자를 순서대로 입력하지 않아도 알아서 순서가 자동으로 게산되어 출력됨.  
띄어쓰기 4번 하면 서브 항목 가능해짐.  

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

```-``` 를 사용하면 순서가 필요하지 않은 목록 만들기 가능.  
마찬가지로 띄어쓰기 4번 하면 서브 항목 가능

# 링크 (Link)

```<a href="https://google.com">GOOGLE</a>```   

<a href="https://google.com">GOOGLE</a>

```[GOOGLE](https://google.com)```  

[GOOGLE](https://google.com)

```<a href="https://naver.com" title="NAVER로 이동!"> NAVER </a>``` 

<a href="https://naver.com" title="NAVER로 이동!"> NAVER </a>

```[NAVER](https://google.com "NAVER로 이동!")```

[NAVER](https://google.com "NAVER로 이동!")


```<a href="https://naver.com" title="NAVER로 이동!" target="_blank"> NAVER </a>```


<a href="https://naver.com" title="NAVER로 이동!" target="_blank"> NAVER </a>

# 이미지 (Images)
```![대체텍스트](복사한 이미지 주소)```
  
  이미지 출력됨  

```[이미지 코드](링크)```  
이미지 출력되고 누르면 링크로 넘어감.

# 인용문 (BlockQuote)

```>``` 사용.
```
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)
```

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

```
> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중첩된 인용문 1
>>> 중첨된 인용문 2
>>> 중첩된 인용문 3
```
> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1  
>>> 중중첨된 인용문 2  
>>> 중중첩된 인용문 3  

# 인라인 (inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
글자 드래그 후 백팁 기호를 이용하면 됨.


# 블록 (block) 코드 강조

```html
<a href="https://google.com">GOOGLE</a>
```
백팁 3번 뒤에 html 붙여주기.

```javascript
function func() {
    var a = 'AAA';
    return a;
}
```
백팁 3번 뒤에 javascript

```bash
$ git commit -m 'Study Markdown'
```

백팀 3번 뒤에 bash

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```
백팁 3번 뒤에 plaintext

# 표 (Table)

```
position 속성

값 | 의미 | 기본값
--|--|--
static | 기준 없음 | O
relative | 요소 사진 | X
absolute | 위치 상 부모요소 | X
fixed | 뷰포트 | X

```

position 속성

값 | 의미 | 기본값
--|--|--
static | 기준 없음 | O
relative | 요소 사진 | X
absolute | 위치 상 부모요소 | X
fixed | 뷰포트 | X

정렬 바꾸려면
하이픈 기호 앞 뒤로 콜론 기호 추가하면 됨.
기본 왼쪽 정렬.
양쪽으로 하면 가운데 정렬
오른쪽 끝에 입력하면 오른쪽 정렬

```
position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 사진 | X
absolute | 위치 상 부모요소 | X
fixed | 뷰포트 | X

```

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 사진 | X
absolute | 위치 상 부모요소 | X
fixed | 뷰포트 | X

# 원시 HTML (Raw HTML)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

줄바꿈 띄어쓰기 두번 또는 `<br>`태그   
`<u>` 와 `<span style="text-decoration: underline;">` 로 밑줄 

표준이 없기 때문에 동작하지 않는 환경들이 있어서 html 태그을 넣어줄 수 있음.

markdown 문법 안에서 html 문법을 사용하는 것을 원시 HTML.


# 수평선 (Horizontal Rule)

`-` 와 `*` 기호를  여러번 눌러주면 사용 가능
`---`

---

`***`

***