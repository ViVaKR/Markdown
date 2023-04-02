# 마크다운 이야기

<!-- 사용처 -->
## 사용처

1. Readme Files (Github, etc)  
2. Forum & Blog Posts
3. Static Site Generators

## 포맷의 종류

1. 제목 (Headings)
2. 코드블럭 (Blocks of Code)
3. 목록 (Lists)
4. 이미지 (Images)
5. 강조 (Emphasis)
6. 인용구 (Blockquotes)
7. 링크 (Links)
8. 수평선 (Horizontal Rules)

---

## 제목 : `숫자 기호와 제목이름 사이에 공백 추가`

> # 제목 1 (`#`)
> ## 제목 2 (`##`)
> ### 제목 3 (`###`)
> #### 제목 4 (`####`)
> ##### 제목 5 (`#####`)
> ###### 제목 6 (`######`)

---

## 공백넣기

+ `nbsp` &nbsp; Add 1 spaces.
+ `ensp` &ensp; Add 2 spaces.
+ `emsp` &emsp; Add 4 spaces. (Tab key)

---

## 줄바꿈
> 일반문장 그대로 타이핑후 끝에서 줄바꿈은 &emsp; `공백 + 공백`

## 단락
> 또는 단락 사이에 공백을 넣음

---

## 링크 (Link) : `[링크명](URL)`

> 이것은 하이퍼링크 - [헬로우월드 바로가기](https://vivabm.com "ViVaBM WebSite") 

---
## 강조 (Emphaszing): 

일반 문장  
*기울어진 문장 (1)* : `*문장*`  
_기울어진 문장 (2)_ : `_문장_`   
**굵은 문장 (1)** : `**문장**`  
__굵은 문장 (2)__  `__...__`  
___굵고 기울어진 문장 만들기 (1)___ `___문장___`  
***굵고 기울어진 문장 만들기 (2)*** `***문장***`  
~~취소선 만들기~~ `~~문장~~`  
수평선   `---`  

## 리스트 (List) : `-, +, * 아이템, 1. 번호 아이템`

### UL

- 아이템 1
- 아이템2
  - 서브 아이템 1
  - 서브 아이템 2
- 아이템 3

### OL

1. 번호 아이템 1
2. 번호 아이템 2
   1. 서브 번호 아이템 1
   2. 서브 번호 아이템 2
3. 번호 아이템 3  

---
## 인용구 (Blockquotes) : `> 좋은 글...., >> 연관된 중첩문`
> 하루에 3시간 걸으면 7년 후에 지구를 한바퀴 돌 수 있다 - 사무엘 존슨   
>
> 다음 문장
>
>> 중첩된 문장 
>> - 중첩 내부에 서브 문장
---
## 코드블럭 (Code Block) :  ` ``` ` _Code Blocks_ ` ``` `

` ```html `
```html
<head>
    <title>Hello, World</title>
</head>
```
` ``` `   

` ```javascript `
```javascript
function someFunc() {
    alert('Hello World');
}
```
` ``` `
#### bash
```bash
    npm install
    npm start
```

#### Python
```python
    def add(num1, num2):
        return num1 + num2

```
### C#
```csharp
    public class Program 
    {
        public static void Main() 
        {
            Console.WriteLine("Hello, World");
        }
    }
```

> 문장안에 __*Inline Code Block*__ 넣기
>  
> \`싱글 백틱으로 Code 를 양쪽으로 감쌈\`
> 
>> this is an \` `<div>` \`  
>> `<p> This is a inline block by p tag <p/>` 
---
## 탈출문자, Escape Caracter : `\`
> 탈출 시키기 => \*여보세요\*  
---

## Table : `|` 으로 칸 만들기
`|title 1 | title 2 |`   
`| ---  | --- |`   
`| 내용 1 | 내용 2 |`  

|Name|Email|
|---|---|
|ViV|viv@gamil.com|
|Hello|hello@gmail.com|
---
## Task List : `[ ]`
* [X] Task 1
* [ ] Task 2
* [ ] Task 3
---

## HTML : 일반 Html Tag 를 그대로 사용

`<img src="./Images/avata.png" width="200" alt="아바타" />`  
<img src="./Images/avata.png" width="200" alt="아바타" />  

## 이미지 (Image): `[![이미지명](이미지 경로)](Click Go To URL)`

[![아바타](./Images/key-gen.ico)](https://vivabm.com)
---
