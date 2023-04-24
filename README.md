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

## ***수학 기호를 넣는 방법***

# [Ref. LaTex](https://en.wikibooks.org/wiki/LaTeX/Mathematics)

$1 + 1 = 2$

$$1 + 1 = 2$$

$2\times 2 = 4$  

$^1/_2$

---

***소괄호 표기법***  

```
$$(1 + 2)$$
```
$$(1 + 2)$$

---

***중괄호 표기법***  

```
$$\{1 + 2\}$$
```
$$\{1 + 2\}$$

---

***대괄호 표기법***  

```
$$[1 + 2]$$
```
$$[1 + 2]$$

---

***자동괄호 리사이징 표기법***  

```
$$\left(\frac{2}{3}\right)$$
```

---

***수동 괄호 리사이징 (big, Big, bigg, Bigg) 표기법***  

```
$$\Bigg(\bigg(\Big(\big(1\big)\Big)\bigg)\Bigg)$$
```
$$\Bigg(\bigg(\Big(\big(1\big)\Big)\bigg)\Bigg)$$

---

***위 첨자 지수 (Power) 표기법***  

```
$$2^2 = 4$$
```
$$2^2 = 4$$

---

***아래 첨자 (Indices)표기법***  

```
$$a_1, a_2, a_3$$
```
$$a_1, a_2, a_3$$

---

***점 (dot) 수와 수사이 값이 존재함을 생략적 표기법***  

```
$$ 0\dots11$$
```
$$ 0\dots11$$

---

***중앙에 점 (dot) 표기법***  

```
$$1\cdots10$$
```
$$1\cdots10$$

---

***새로방향 점 표기법***  

```
$$\vdots$$
```
$$\vdots$$

---

***대각선 방향 점 표기법***  

```
$$\ddots$$
```
$$\ddots$$

---
***루트 (거듭제곱근) 표기법***  

```
$$\sqrt{2}$$
```
$$\sqrt{2}$$

---

***펙토리얼 (Factorial) 표기법***  

```
$$n! = 1 \times 2 \times 3 \times 4 \ldots n$$
$$n! = \prod_{k=1}^n k$$
```
$$n! = 1 \times 2 \times 3 \times 4 \ldots n$$
$$n! = \prod_{k=1}^n k$$

---

***합집합 표기법***  

```
$$\{a, b, c\} \cup \{d, e\}= \{a, b, c, d, e\}$$
```
$$\{a, b, c\} \cup \{d, e\}= \{a, b, c, d, e\}$$

---

***교집합 표기법***  

```
$$\{a, b, c\} \cap \{a, b, d\} = \{a, b\}$$
```
$$\{a, b, c\} \cap \{a, b, d\} = \{a, b\}$$

---

***수학공식, 수식번호 표기법***  

```
$$X_{1,j} \mathbf{F}X_{2,j} = 0, \tag{1}$$
```
$$X_{1,j} \mathbf{F}X_{2,j} = 0, \tag{1}$$

***삼각함수 (싸인, 코싸인, 탄젠트, 세타) 표기법***  

```
$$90^\circ$$
```

$$90^\circ$$
$$\cos(1\theta) = \cos^2\theta - sin^2\theta \ldots \tan (2\theta)$$

--- 

***파이 (PI) 표기법***  

```
$$\pi, \Pi, \phi$$
```

$$\pi, \Pi, \phi$$

---

***각도 표기법***  

```
$$90^\circ$$
```

$$90^\circ$$

---

***극한 표기법 (limit)***  

```
$$\lim_{x \to \infty} \exp(-x) = 0$$
```
$$\lim_{x \to \infty} \exp(-x) = 0$$

---

***시그마 표기법 (for)***  

```
$$\displaystyle\sum_{i=1}^{10} t_i$$
$$\sum_{i=1}^{10} t_i$$
```

$$\displaystyle\sum_{i=1}^{10} t_i$$
$$\sum_{i=1}^{10} t_i$$

--- 

***미분 표기법 (Differential)***  

```
$$\dv{Q}{t} = \dv{s}{t}$$
```
$$\dv{Q}{t} = \dv{s}{t}$$

---

***적분 (Intergral) 표기법***  

```
$$\int_0^\infty \mathrm{e}^{-x}\, \mathrm{d}x$$
$$\int\limits_a^b$$
```

**$$\int_0^\infty \mathrm{e}^{-x}\, \mathrm{d}x$$

$$\int\limits_a^b$$

---

***행렬 (Matrix) 표기법***

```
$$A_{m,n} = 
\begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m,1} & a_{m,2} \cdots & a_{m,n}
\end{pmatrix}$$
```

$$A_{m,n} = 
\begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m,1} & a_{m,2} \cdots & a_{m,n}
\end{pmatrix}$$

---

***백터, 스칼라 (Vector, Scalar) 표기법***

```
$$\overrightarrow{AB}$$

$$\overline{AB}$$
```
$$\overrightarrow{AB}$$

$$\overline{AB}$$

---

***기본 규칙***
1. 인라인 수식
   1. `$` 또는 `\(`와 `\)` 사이에 수식을 넣습니다. 
   2. 예를 들어, `$y = mx + b$`와 같이 작성할 수 있습니다.

2. 디스플레이 수식: 
   1. `$$` 또는 `\[`와 `\]` 사이에 수식을 넣습니다. 
   2. 예를 들어, `$$y = \frac{1}{2}x^2 + 3x - 5$$`와 같이 작성할 수 있습니다.

3. LaTeX 수식: 
    1. LaTeX 수식을 사용하여 수식을 작성할 수 있습니다. 
    2. 이를 위해서는 `$` 대신 `$$`를 사용하여 디스플레이 수식을 작성해야 합니다. 
    3. 예를 들어, `$$\int_{0}^{1} x^2 dx = \frac{1}{3}$$`와 같이 작성할 수 있습니다.

4. 수학기오
   - `+`, `-`, `*`, `/`: 덧셈, 뺄셈, 곱셈, 나눗셈
   - \div, \times, 
   - `^`: 거듭제곱
   - `_`: 아래 첨자
   - `{}`: 그룹화
   - `\sqrt`: 제곱근
   - `\frac`: 분수 (fraction, 프렉션)
   - `\int`: 적분
   - `\sum`: 시그마 합
   - `\lim`: 극한
   - `\infty`: 무한대
   - `\pi`: 원주율
   - `\theta`: 세타
   - `cos` : 코싸인
   - `sin` : 싸인
   - `tan` : 탄젠트

---
***ETC***

```
$$\alpha, \Alpha, \beta, \Beta, \gamma, \Gamma, \pi, \Pi, \phi, \varphi, \mu, \Phi$$
```
$$\alpha, \Alpha, \beta, \Beta, \gamma, \Gamma, \pi, \Pi, \phi, \varphi, \mu, \Phi$$

---

```
$a \bmod b$
```

$a \bmod b$

---

```
$f(n) = n^5$
```

---

```
$f(n) = n^5$
Hello $^3/_7$ World   
hello$\;$fine
$\rightarrow$
```
$f(n) = n^5$
Hello $^3/_7$ World   
hello$\;$fine  
$\rightarrow$
---

***논문 기호***

| 이름 | 명령어 | 반환 | 이름 | 명령어 | 반환 |
|-|-|-|-|-|-|
| 알파 | `\alpha` | $\alpha$ | 크사이 | `\xi` | $\xi$ |
| 베타 |`\beta` | $\beta$ |	오미크론 | o |$o$|
| 감마 |`\gamma` | $\gamma$ |파이 | \pi |$\pi$|
| 델타 |`\delta` | $\delta$ | 로 | \rho |$\rho$|
| 엡실론 |`\epsilon` | $\epsilon$|시그마|`\sigma`|$\sigma$|
| 제타 |`\zeta` | $\zeta$ |타우 | `\tau` |$\tau$|
| 에타 |`\eta` | $\eta$ | 입실론 | `\upsilon` |$\upsilon$|
| 세타 |`\theta` | $\theta$ |파이 | `\phi` |$\phi$|
| 이오타 |`\iota` | $\iota$ |카이 | `\chi` |$\chi$|
| 카파 |`\kappa` | $\kappa$ |오메가 | `\omega` |$\omega$|
| 람다 |`\lambda` | $\lambda$ | 뉴 | `\nu` | $\nu$|
| 뮤 |`\mu` | $\mu$|-|-|-|-|

---

***관계연산자***

|이름|명령어|반환|이름|명령어|반환|
|-|-|-|-|-|-|
|합동|`\equiv`|$\equiv$|근사|`\approx`|$\approx$|
|비례|`\propto`|$\propto$|같고 근사|`\simeq`|$\simeq$|
|닮음|`\sim`|$\sim$|같지 않음|`\neq`|$\neq$|
|작거나 같음|`\leq`|$\leq$|크거나 같음|`\geq`|$\geq$|
|매우작음|`\ll`|$\ll$|매우 큼|`\gg`|$\gg$|

---

***논리기호***

|이름|명령어|반환|이름|명령어|반환|
|-|-|-|-|-|-|
|wedge|`\wedge`|$\wedge$|vee|`\vee`|$\vee$|
|논리합|`\oplus`|$\oplus$|어떤|`\exists`|$\exists$|
|오른쪽 화살표|`\rightarrow`|$\rightarrow$|왼쪽 화살표|`\leftarrow`|$\leftarrow$|
|왼쪽 큰화살표|`\Leftarrow`|$\Leftarrow$|오른쪽 큰화살표|`\Rightarrow`|$\Rightarrow$|
|양쪽 큰화살표|`\Leftrightarrow`|$\Leftrightarrow$|양쪽 화살표|`\leftrightarrow`|$\leftrightarrow$|
|모든|`\forall`|$\forall$||||
|불릿|`\bullet`|$\bullet$|부정|`\neq`|$\neq$|

---

***집합기호***

|이름|명령어|반환|이름|명령어|반환|
|-|-|-|-|-|-|
|교집합|`\cap`|$\cap$|합집합|`\cup`|$\cup$|
|상위집합|`\supset`|$\supset$|진상위집합|`\supseteq`|$\supseteq$|
|하위집합|`\subset`|$\subset$|진하위집|`\subseteq`|$\subseteq$|
|부분집합아님|`\not\subset`|$\not\subset$|공집합|`\emptyset, \varnothing`|$\emptyset$, $\varnothing$|
|원소|`\in`|$\in$|`원소아님`|`\notin`|$\notin$|

---

***기타***

|이름|명령어|반환|이름|명령어|반환|
|-|-|-|-|-|-|
|hat|`\hat{x}`|$\hat{x}$|widehat|`\widehat{x}`|$\widehat{x}$|
|물결|`\tilde{x}`|$\tilde{x}$|wide물결|`\widetilde{x}`|$\widetilde{x}$|
|bar|`\bar{x}`|$\bar{x}$|overline|`\overline{x}`|$\overline{x}$|
|check|`\check{x}`|$\check{x}$|acute|`\acute{x}`|$\acute{x}$|
|grave|`\grave{x}`|\(\grave{x}\)|dot|`\dot{x}`|$\dot{x}$|
|ddot|`\ddot{x}`|\(\ddot{x}\)|breve|`\breve{x}`|$\breve{x}$|
|vec|`\vec{x}`|$\vec{x}$|델,나블라|`\nabla`|$\nabla$|
|수직|`\perp`|$\perp$|평행|`\parallel`|$\parallel$|
|부분집합아님|`\not\subset`|$\not\subset$|공집합|`emptyset`|$\emptyset$|
|가운데 점|`\cdot`|$\cdot$|…|`\dots`|$\dots$|
|가운데 점들|`\cdots`|$\cdots$|세로점들|`\vdots`|$\vdots$|
|나누기|`\div`|$\div$|물결표|`\sim`|$\sim$|
|플마,마플|`\pm, \mp`|$\pm$, $\mp$|겹물결표|`\approx`| $\approx$ |
|prime|`\prime`|$\prime$|무한대|`\infty`|$\infty$|
|적분|`\int`|$\int$|편미분|`\partial`|$\partial$|
|한칸띄어|`x\,y`|$x\,y$|두칸|`x\;y`|$x \; y$|
|네칸띄어|`x \quad y`|$x \quad y$|여덟칸띄어|`x \qquad y`|$x \qquad y$|

---

