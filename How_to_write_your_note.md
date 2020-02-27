# Markdown

## Markdown 标题

1. ctr+1~6
2. #+ +test 几个“# ”代表几级标题

## Markdown段落格式

1. **斜体**    ctr+l or 文字左右带一个*    *word*

2. **粗体**    ctr+b or 文字左右带两个*    **word**

3. **粗斜体**    文字左右带三个*    ***word***

4. **分割线**    在一行中输入三个*

   ***

5. **删除线**    alt+shift+5 or 文字左右带两个~~    ~~word~~

6. **下划线 **   ctr+u or 文字左带一个u右边带一个/u     <u>word</u>

7. **清楚格式**    ctr+\

## Markdown列表

1. **无序列表**    每段前 *+ +word 
   - word

2. **有序列表**    每段前 数字+.+ +word

## Markdown区块

每一个 >+ +word 就是一个区块 or ctr+shift+q

> 1
>
> > 2

## Markdown代码

1. **代码片段**    在代码左右带一个*`*     `print()`

2. **代码区块**    ctr+shift+k or 在代码前后行写三个`

```
word
```

## Markdown链接

1. **直接插入链接**       在链接左右加< >

2. **用变量替代网址**    在他处输入链接    [+描述文字+]+[+变量名+]

   在他出 [+变量名+]+:+ +网址

## Markdown图片

1. **插入图片**    ！+[+描述文字+]+(+网址or绝对地址+)

   ![RUNOOB](http://static.runoob.com/images/runoob-logo.png)

2. **用变量替代网址or地址**    在他处输入链接    [+描述文字+]+[+变量名+]

   在他出 [+变量名+]+:+ +网址or地址

## Markdown其他技巧

1. **转义**    为了使得符号不冲突，在每一个特定符号前都用\来表示其符号的属性    \\\*word\\\*
2. **公式**    ctr+shift+m or 两个$$包裹TeX 或LaTeX格式的数学公式
3. **大纲**    ctr+shift+1
4.  **搜索**   ctr+shift+f
5. **显示/隐藏左侧边栏**    ctr+l
6. **专注模式** F8    **打字机模式** F9    **全屏模式**  F11    **源代码模式** ctr+/
7. **放大**    ctr+shift+=    **缩小 **   ctr+shift+-

### 参考

[runoob](https://www.runoob.com/markdown/md-advance.html)



# LaTeX公式

## 字符

### 字符的帽子们

\dot{a}, \ddot{a}, \acute{a}, \grave{a}
$$
\dot{a}, \ddot{a}, \acute{a}, \grave{a}
$$
\check{a}, \breve{a}, \tilde{a}, \bar{a}
$$
\check{a}, \breve{a}, \tilde{a}, \bar{a}
$$
\hat{a}, \widehat{a}, \vec{a}
$$
\hat{a}, \widehat{a}, \vec{a}
$$
\bar{q}, \bar{abc}, \overline{q}, \overline{abc}
$$
\bar{q}, \bar{abc}, \overline{q}, \overline{abc}
$$
\underline{k l m}， \overbrace{1+2+\cdots+100}， \begin{matrix} 5050 \\ \overbrace{ 1+2+\cdots+100 } \end{matrix}
$$
\underline{k l m}， \overbrace{1+2+\cdots+100}， \begin{matrix} 5050 \\ \overbrace{ 1+2+\cdots+100 } \end{matrix}
$$
\underbrace{a+b+\cdots+z}， \begin{matrix} \underbrace{ a+b+\cdots+z } \\ 26 \end{matrix}
$$
\underbrace{a+b+\cdots+z}， \begin{matrix} \underbrace{ a+b+\cdots+z } \\ 26 \end{matrix}
$$

### 下标、上标

a^2， a_2， a^{2+2}， a_{i,j}， x_2^3， {}_1^2\!X_3^4
$$
a^2， a_2， a^{2+2}， a_{i,j}， x_2^3， {}_1^2\!X_3^4
$$

### 希腊字母

输入 `\小写希腊字母英文全称` 和 `\首字母大写希腊字母英文全称` 来分别输入小写和大写希腊字母。

```
\Alpha \Beta \Gamma \Delta \Epsilon \Zeta \Eta \Theta
```

$$
ABΓΔEZHΘ
$$



```
\Iota \Kappa \Lambda \Mu \Nu \Xi \Omicron \Pi
```

$$
IKΛMNOΞΠ
$$



```
\Rho \Sigma \Tau \Upsilon \Phi \Chi \Psi \Omega
```

$$
PΣTΥΦXΨΩ
$$



```
\alpha \beta \gamma \delta \epsilon \zeta \eta \theta
```

$$
αβγδϵζηθ
$$



```
\iota \kappa \lambda \mu \nu \omicron \xi \pi
```

$$
ικλμνoξπ
$$



```
\rho \sigma \tau \upsilon \phi \chi \psi \omega
```

$$
ρστυϕχψω
$$

### 类字母符号

\infty, \aleph, \complement, \backepsilon, \eth, \Finv, \hbar
$$
\infty, \aleph, \complement, \backepsilon, \eth, \Finv, \hbar
$$
\Im, \imath, \jmath, \Bbbk, \ell, \mho, \wp, \Re, \circledS
$$
\Im, \imath, \jmath, \Bbbk, \ell, \mho, \wp, \Re, \circledS
$$

## 函数们

### 指数

\exp_a b = a^b, \exp b = e^b, 10^m
$$
\exp_a b = a^b, \exp b = e^b, 10^m
$$

### 对数

\ln c, \lg d = \log e, \log_{10} f
$$
\ln c, \lg d = \log e, \log_{10} f
$$

### 三角函数

（以此类推）

\sin a, \cos b, \tan c, \cot d, \sec e, \csc f 
$$
\sin a, \cos b, \tan c, \cot d, \sec e, \csc f
$$

## 符号

### 求和、求积

\sum_{k=1}^N k^2，\begin{matrix} \sum_{k=1}^N k^2 \end{matrix}
$$
\sum_{k=1}^N k^2，\begin{matrix} \sum_{k=1}^N k^2 \end{matrix}
$$
\prod_{i=1}^N x_i，\begin{matrix} \prod_{i=1}^N x_i \end{matrix} 
$$
\prod_{i=1}^N x_i，\begin{matrix} \prod_{i=1}^N x_i \end{matrix}
$$

### 积分

本例中 \, 和 {\rm d} 部分可省略，但建议加入，能使式子更美观。{\rm d}可以用\mathrm{d}等价替换。

\int_{-N}^{N} e^x\, {\rm d}x
$$
\int_{-N}^{N} e^x\, {\rm d}x
$$
\iint_{D}^{W} \, \mathrm{d}x\,\mathrm{d}y
$$
\iint_{D}^{W} \, \mathrm{d}x\,\mathrm{d}y
$$

### 分数

通常使用 `\frac {分子} {分母}` 命令产生一个分数，分数可嵌套。
便捷情况可直接输入 `\frac ab` 来快速生成一个 abab 。
如果分式很复杂，亦可使用 `分子 \over 分母` 命令，此时分数仅有一层。

\frac{2}{4}=0.5
$$
\frac{2}{4}=0.5
$$
\cfrac{2}{c + \cfrac{2}{d + \cfrac{2}{4}}} = a
$$
\cfrac{2}{c + \cfrac{2}{d + \cfrac{2}{4}}} = a
$$
在以e为底的指数函数、极限和积分中尽量不要使用 `\frac` 符号：它会使整段函数看起来很怪，而且可能产生歧义。也正是因此它在专业数学排版中几乎从不出现。
横着写这些分式，中间使用斜线间隔 `/` （用斜线代替分数线）。

### 二项式系数

\dbinom{n}{r}=\binom{n}{n-r}=\mathrm{C}_n^r=\mathrm{C}_n^{n-r}
$$
\dbinom{n}{r}=\binom{n}{n-r}=\mathrm{C}_n^r=\mathrm{C}_n^{n-r}
$$

### 符号函数、绝对值

\sgn r, \left\vert s \right\vert
$$
\sgn r, 
\left\vert s \right\vert
$$

### 最大值、最小值

\min(x,y), \max(x,y)
$$
\min(x,y), \max(x,y)
$$


### 界限

\lim u, \liminf v, \limsup w
$$
\lim u, \liminf v, \limsup w
$$

### 极限

\lim_{x \to \infty} \frac{1}{n(n+1)}，\begin{matrix} \lim_{n \to \infty}x_n \end{matrix}
$$
\lim_{x \to \infty} \frac{1}{n(n+1)}，\begin{matrix} \lim_{n \to \infty}x_n \end{matrix}
$$

### 其他

\dim p, \deg q, \det m, \ker\phi
$$
\dim p, \deg q, \det m, \ker\phi
$$

### 投影

\Pr j, \hom l, \lVert z \rVert, \arg z
$$
\Pr j, \hom l, \lVert z \rVert, \arg z
$$

### 微分、导数

dt, \mathrm{d}t, \partial t, \nabla\psi
$$
dt, \mathrm{d}t, \partial t, \nabla\psi
$$
dy/dx, \mathrm{d}y/\mathrm{d}x, \frac{dy}{dx}, \frac{\mathrm{d}y}{\mathrm{d}x}, \frac{\partial^2}{\partial x_1\partial x_2}y
$$
dy/dx, \mathrm{d}y/\mathrm{d}x, \frac{dy}{dx}, \frac{\mathrm{d}y}{\mathrm{d}x}, \frac{\partial^2}{\partial x_1\partial x_2}y
$$
\prime, \backprime, f^\prime, f', f'', f^{(3)}, \dot y, \ddot y
$$
\prime, \backprime, f^\prime, f', f'', f^{(3)}, \dot y, \ddot y
$$

### 根号

\surd, \sqrt{2}, \sqrt[n]{}, \sqrt[3]{\frac{x^3+y^3}{2}}
$$
\surd, \sqrt{2}, \sqrt[n]{}, \sqrt[3]{\frac{x^3+y^3}{2}}
$$

### 运算符

+, -, \pm, \mp, \dotplus
$$
+, -, \pm, \mp, \dotplus
$$
\times, \div, \divideontimes, /, \backslash
$$
\times, \div, \divideontimes, /, \backslash
$$
\cdot, * \ast, \star, \circ, \bullet
$$
\cdot, * \ast, \star, \circ, \bullet
$$
\oplus, \ominus, \otimes, \oslash, \odot
$$
\oplus, \ominus, \otimes, \oslash, \odot
$$

### 关系类符号

=, \ne, \neq, \equiv, \not\equiv
$$
=, \ne, \neq, \equiv, \not\equiv
$$
\doteq,  \overset{\underset{\mathrm{def}}{}}{=}, :=
$$
\doteq,  \overset{\underset{\mathrm{def}}{}}{=}, :=
$$
\sim, \nsim, \simeq, \approx, \propto, \varpropto
$$
\sim, \nsim, \simeq, \approx, \propto, \varpropto
$$
\le, \nleq, \ge, \ngeq, \lessgtr,  \leqslant, \nleqslant,  \geqslant, \ngeqslant,
$$
\le, \nleq, \ge, \ngeq, \lessgtr,  \leqslant, \nleqslant,  \geqslant, \ngeqslant,
$$
\prec, \nprec, \preceq, \npreceq, \precneqq
$$
\prec, \nprec, \preceq, \npreceq, \precneqq
$$
\succ, \nsucc, \succeq, \nsucceq, \succneqq
$$
\succ, \nsucc, \succeq, \nsucceq, \succneqq
$$

### 几何符号

\parallel, \nparallel,\vartriangle, \triangledown
$$
\parallel, \nparallel,\vartriangle, \triangledown
$$
\perp, \angle, \sphericalangle, \measuredangle, 45^\circ
$$
\perp, \angle, \sphericalangle, \measuredangle, 45^\circ
$$

### 逻辑符号

\forall, \exists, \nexists
$$
\forall, \exists, \nexists
$$
\therefore, \because, \And
$$
\therefore, \because, \And
$$
\or，\and
$$
\or，\and
$$
\lnot \neg, \not\operatorname{R}, \bot, \top
$$
\lnot \neg, \not\operatorname{R}, \bot, \top
$$

## 矩阵

语法：

```
Copy\begin{类型}
公式内容
\end{类型}
```

类型可以是：矩阵 `matrix` `pmatrix` `bmatrix` `Bmatrix` `vmatrix` `Vmatrix`、条件表达式 `cases`、多行对齐方程式 `aligned`、数组 `array`。

在公式内容中：在每一行中插入 `&` 来指定需要**对齐**的内容，在每行结尾处使用 `\\` **换行**。



**无框矩阵**

在开头使用 `begin{matrix}`，在结尾使用 `end{matrix}`，在中间插入矩阵元素，每个元素之间插入 `&` ，并在每行结尾处使用 `\\` 。

```
\begin{matrix}
x & y \\
z & v
\end{matrix}
```

$$
\begin{matrix}
x & y \\
z & v
\end{matrix}
$$

**有框矩阵**

在开头将 `matrix` 替换为 `pmatrix` `bmatrix` `Bmatrix` `vmatrix` `Vmatrix` 

```
\begin{vmatrix}
x & y \\
z & v
\end{vmatrix}
```

$$
\begin{vmatrix}
x & y \\
z & v
\end{vmatrix}
$$



使用 `\cdots` ⋯⋯ , `\ddots` ⋱⋱ , `\vdots` ⋮⋮ 来输入**省略符号**。

```
\begin{bmatrix}
0      & \cdots & 0      \\
\vdots & \ddots & \vdots \\
0      & \cdots & 0
\end{bmatrix}
```

$$
\begin{bmatrix}
0      & \cdots & 0      \\
\vdots & \ddots & \vdots \\
0      & \cdots & 0
\end{bmatrix}
$$



```
\begin{Bmatrix}
x & y \\
z & v
\end{Bmatrix}
```

$$
\begin{Bmatrix}
x & y \\
z & v
\end{Bmatrix}
$$

**用数组实现带分割符号的矩阵**

其中 `cc|c` 代表在一个三列矩阵中的第二和第三列之间插入分割线。

```
$$
\left[
    \begin{array}{cc|c}
      1&2&3\\
      4&5&6
    \end{array}
\right]
$$
```

$$
\left[
    \begin{array}{cc|c}
      1&2&3\\
      4&5&6
    \end{array}
\right]
$$

```
\begin{pmatrix}
x & y \\
z & v
\end{pmatrix}
```

$$
\begin{pmatrix}
x & y \\
z & v
\end{pmatrix}
$$

## 方程组



```
\begin{cases}
3x + 5y +  z \\
7x - 2y + 4z \\
-6x + 3y + 2z
\end{cases}
```

$$
\begin{cases}3x + 5y +  z \\7x - 2y + 4z \\-6x + 3y + 2z\end{cases}
$$

### 条件表达式

```
f(n) =
\begin{cases} 
n/2,  & \text{if }n\text{ is even} \\
3n+1, & \text{if }n\text{ is odd}
\end{cases}
```

$$
f(n) =
\begin{cases} 
n/2,  & \text{if }n\text{ is even} \\
3n+1, & \text{if }n\text{ is odd}
\end{cases}
$$

### 多行等式、同余式

人们经常想要一列整齐且居中的方程式序列。使用 `\begin{aligned}…\end{aligned}`。

```
\begin{aligned}
f(x) & = (m+n)^2 \\
     & = m^2+2mn+n^2 \\
\end{aligned}
```

$$
\begin{aligned}
f(x) & = (m+n)^2 \\
     & = m^2+2mn+n^2 \\
\end{aligned}
$$



```
\begin{alignedat}{3}
f(x) & = (m-n)^2 \\
f(x) & = (-m+n)^2 \\
     & = m^2-2mn+n^2 \\
\end{alignedat}
```

$$
\begin{alignedat}{3}
f(x) & = (m-n)^2 \\
f(x) & = (-m+n)^2 \\
     & = m^2-2mn+n^2 \\
\end{alignedat}
$$

## 集合

\{ \}, \O \empty \emptyset, \varnothing
$$
\{ \}, \O \empty \emptyset, \varnothing
$$
\in, \notin \not\in, \ni, \not\ni
$$
\in, \notin \not\in, \ni, \not\ni
$$
\cap, \sqcap, \cup, \sqcup, \setminus，\subset, \supset
$$
\cap, \sqcap, \cup, \sqcup, \setminus，\subset, \supset
$$
\subseteq, \nsubseteq, \subsetneq, \varsubsetneq
$$
\supseteq, \nsupseteq, \supsetneq, \varsupsetneq
$$
\subseteqq, \nsubseteqq, \subsetneqq, \varsubsetneqq
$$
\supseteqq, \nsupseteqq, \supsetneqq, \varsupsetneqq
$$

## 箭头

\Rightarrow, \nRightarrow,\Leftarrow, \nLeftarrow,\Leftrightarrow, \nLeftrightarrow, \rightleftharpoons \leftrightharpoons，\circlearrowleft
$$
\Rightarrow, \nRightarrow,\Leftarrow, \nLeftarrow,\Leftrightarrow, \nLeftrightarrow, \rightleftharpoons \leftrightharpoons，\circlearrowleft
$$

### 参考

<https://www.cnblogs.com/1024th/p/11623258.html>