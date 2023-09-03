# ✍️<ReadMe.md 작성하기>

- ReadMe 작성: MarkDown(마크다운) 문법으로 작성
- MarkDown: <br>
  ㄴ 장점) 사용이 쉽고 마크업 언어인 HTML태그에 비해 간단해 문서 작성이편리 <br>
  ㄴ 단점) 마크다운을 지원하는 프로그램 or 사이트에서만 사용 가능 <br>
          (ex. 깃허브, 디스코드, 벨로그, 티스토리 등)

<br>
<br>
<br>

## 1. 헤더(header)
: `<h1>` ~ `<h2>` 까지 제목으로 표현가능
- 텍스트 앞에 `#` 붙임

※ `#`과 텍스트 사이 한칸 띄움
- `#`이 갯수가 클수록 레벨이 낮아짐
- `#`은 1~6까지
- h1: ===, h2: --- 가능

### 1.1. 방법 ①
#### 1.1.1. Edit
```html
# `#`이용 제목1
## `#`이용 제목2
### `#`이용 제목3
#### `#`이용 제목4
##### `#`이용 제목6
```

#### 1.1.1. Preview
# `#`이용 제목1
## `#`이용 제목2
### `#`이용 제목3
#### `#`이용 제목4
##### `#`이용 제목6

### 1.1. 방법 ②
#### 1.1.1. Edit
```html
`#`이용 제목1
===
`#`이용 제목2
---
```

#### 1.1.1. Preview
`#`이용 제목1
===
`#`이용 제목2
==

<br>
<br>
<br>

## 2. 수평선(Horizontal Rules)
- `-`또는 `*`을 3개 이상 작성
※ `-`을 사용할 경우 header로 인식할 수 있으므로, 이 전 라인 비워둬야함

### 2.1. Edit
```html
* * *
******
- - -
------
```

### 2.2. Preview
* * *
******
- - -
------

<br>
<br>
<br>

## 3. 줄바꿈(Line Breaks)
- `<br>` 활용해 줄바꿈 가능
- 엔터로 칸 띄우면 다음행 넘어감. `<br>` 하나의 문장에서 줄바꿈
 
### 3.1. Edit
```html
오늘 하루도 화이팅
입니다 <br>
아자아자 화이팅!
```

### 3.2. Preview
오늘 하루도 화이팅
입니다 <br>
아자아자 화이팅!

<br>
<br>
<br>

## 4. 강조(Emphasis)
- 기울여쓰기(italic): `*` 또는 `_`(언더바) 로 감싼 텍스트
- 두껍게 쓰기(bold): `**` 또는 `__` 로 감싼 텍스트
- 취소선: `~~` 로 감싼 텍스트
※ 기울여쓰기 & 두껍게 쓰기 같이 사용 가능
 
### 4.1. Edit
```html
*hello*
_How was your day?_
**hi**
__Good to see you__
~~happy day~~
***Have a great day!***
```


### 4.2. Preview
*hello* <br>
_How was your day?_ <br>
**hi** <br>
__Good to see you__ <br>
~~happy day~~ <br>
***Have a great day!*** <br>


## 5. 인용(Blockquote)
- `>` 로 시작하는 텍스트
- `>`~`>>>`: 3개까지 가능
※ 인용구 안에 제목, 리트스, 텍스트박스 가능
  
### 5.1. Edit
```html
> 오늘 하루도 화이팅
>> 입니다
>>> 아자아자 화이팅!
```

### 5.2. Preview
> 오늘 하루도 화이팅
>> 입니다
>>> 아자아자 화이팅!



## 6. 인용(Block1
- 
 
### 6.1. Edit
```html
오늘 하루도 화이팅
입니다 <br>
아자아자 화이팅!
```

### 6.2. Preview
오늘 하루도 화이팅
입니다 <br>
아자아자 화이팅!



