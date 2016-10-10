# remagine.github.io
This is Remagine's git Blog

-

# TODO

- [x] Study Markdown
- [ ] Make `index.html`


## Markdown 문법 사용법

```html
<h1>heading 1</h1>
<h2>heading 2</h2>
<h3>heading 3</h3>
<h4>heading 4</h4>
<h5>heading 5</h5>
<h6>heading 6</h6>
```

# Markdown H1
## Markdown H2
### Markdown H3
#### Markdown H4
##### Markdown H5
###### Markdown H6

```html
<!-- 비순차 목록 -->
<!-- ul>li{item$}*3 -->
<ul>
	<li>item1</li>
	<li>item2</li>
	<li>item3</li>
</ul>

<!-- 순차 목록 -->
<!-- ol>li{item$}*3 -->
<ol>
	<li>item1</li>
	<li>item2</li>
	<li>item3</li>
</ol>
```

#### 비순차 목록

- item1
- item2
- item3

#### 순차 목록

1. item1
1. item2
1. item3

### 이미지

```html
<img src="http://pds27.egloos.com/pds/201310/09/99/c0109099_5254e50e70934.jpg" alt="귀염">
```

<!-- ctrl shift p 후 emmet : update Image size를 사용하면 자동으로 이미지 크기 확인 가능  -->
<img src="http://pds27.egloos.com/pds/201310/09/99/c0109099_5254e50e70934.jpg" alt="귀염" width="240" height="150" >

![귀염](Assets/cute_joker.jpg)

### 하이퍼링크

```html
<a href="http://iropke.com">이롭게 에이전시</a>
```

- [지니- 무력감 테스트](http://blog.naver.com/afx1979?Redirect=Log&logNo=220831608445&from=section)
- [PPAP](https://www.youtube.com/watch?v=d9TpRfDdyU0)
- [여우 사진](http://egloos.zum.com/HRDSK/v/1332937)

### 인용 구문

인용절은 보통 들여쓰기를 통해 사용자에게 일반 문장과 구분해준다.<br>
HTML 언어에서는 `<blockquote>`요소를 사용하여 인용절을 구조화한다.

>"Design is All. All is Design."<br>
>"Learn By Doing"<br>
>"근자열 원자래"


### 표

Job Type | Role
--- | ---
Planner | Plan
Designer | Design
Developer | Develop