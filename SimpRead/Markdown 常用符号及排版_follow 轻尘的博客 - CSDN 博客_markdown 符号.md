> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [blog.csdn.net](https://blog.csdn.net/u013914471/article/details/82973812)

### Markdown 常用符号及排版

*   [前言](#_1)
*   [符号及公式](#_4)
*   *   [数学符号](#_8)
    *   *   [数学模式重音符](#_9)
        *   [小写希腊字母](#_16)
        *   [大写希腊字母](#_28)
        *   [二元关系符](#_35)
        *   [二元运算符](#_46)
        *   [大尺寸运算符](#_57)
        *   [箭头](#_64)
        *   [其他符号](#_75)
    *   [公式](#_90)
    *   *   [函数](#_91)
        *   [积分、求和](#_98)
        *   [矩阵、方程](#_161)
*   [排版](#_244)
*   *   [表格](#_245)
    *   [图片](#_315)
    *   [页内跳转](#_345)

前言
==

初开博客，练习一下 Markdown 写作，整理些常用的符号、公式、排版技巧等，也算练练手，以备后用，会不定时更新使用过程中学到的新技巧。  
本文基于 [LaTeX 各种命令，符号](https://blog.csdn.net/garfielder007/article/details/51646604)、[常用数学符号的 LaTeX 表示方法](http://mohu.org/info/symbols/symbols.htm)以及 [Markdown 快速入门](https://sspai.com/post/45816)等整理，感谢分享。

符号及公式
=====

Markdown 中书写符号或者公式时，只需在符号或者公式前后同时添加 “$” 或“$$”即可，显示效果不同。如下所示：  
当在符号 \delta 前后各添加两个 "$"，结果为 δ \delta δ  
当在符号 \delta 前后各添加一个 "$"，即 $\delta$，结果为 δ \delta δ

数学符号
----

### 数学模式重音符

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>\bar{a}</td><td>a ˉ \bar{a} aˉ</td><td>\acute{a}</td><td>a ˊ \acute{a} aˊ</td><td>\check{a}</td><td>a ˇ \check{a} aˇ</td><td>\grave{a}</td><td>a ˋ \grave{a} aˋ</td></tr><tr><td>\hat{a}</td><td>a ^ \hat{a} a^</td><td>\tilde{a}</td><td>a ~ \tilde{a} a~</td><td>\dot{a}</td><td>a ˙ \dot{a} a˙</td><td>\ddot{a}</td><td>a ¨ \ddot{a} a¨</td></tr><tr><td>\breve{a}</td><td>a ˘ \breve{a} a˘</td><td>\vec{a}</td><td>a ⃗ \vec{a} a<svg width="0.471em" height="0.714em" style="width:0.471em" viewBox="0 0 471 714" preserveAspectRatio="xMinYMin"><path d="M377 20c0-5.333 1.833-10 5.5-14S391 0 397 0c4.667 0 8.667 1.667 12 5
3.333 2.667 6.667 9 10 19 6.667 24.667 20.333 43.667 41 57 7.333 4.667 11
10.667 11 18 0 6-1 10-3 12s-6.667 5-14 9c-28.667 14.667-53.667 35.667-75 63
-1.333 1.333-3.167 3.5-5.5 6.5s-4 4.833-5 5.5c-1 .667-2.5 1.333-4.5 2s-4.333 1
-7 1c-4.667 0-9.167-1.833-13.5-5.5S337 184 337 178c0-12.667 15.667-32.333 47-59
H213l-171-1c-8.667-6-13-12.333-13-19 0-4.667 4.333-11.333 13-20h359
c-16-25.333-24-45-24-59z"></path></svg></td><td>\widehat{A}</td><td>A ^ \widehat{A} A<svg width="100%" height="0.24em" viewBox="0 0 1062 239" preserveAspectRatio="none"><path d="M529 0h5l519 115c5 1 9 5 9 10 0 1-1 2-1 3l-4 22
c-1 5-5 9-11 9h-2L532 67 19 159h-2c-5 0-9-4-11-9l-5-22c-1-6 2-12 8-13z"></path></svg></td><td>\widetilde{A}</td><td>A ~ \widetilde{A} A<svg width="100%" height="0.26em" viewBox="0 0 600 260" preserveAspectRatio="none"><path d="M200 55.538c-77 0-168 73.953-177 73.953-3 0-7
-2.175-9-5.437L2 97c-1-2-2-4-2-6 0-4 2-7 5-9l20-12C116 12 171 0 207 0c86 0
 114 68 191 68 78 0 168-68 177-68 4 0 7 2 9 5l12 19c1 2.175 2 4.35 2 6.525 0
 4.35-2 7.613-5 9.788l-19 13.05c-92 63.077-116.937 75.308-183 76.128
-68.267.847-113-73.952-191-73.952z"></path></svg></td></tr></tbody></table>

### 小写希腊字母

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>\alpha</td><td>α \alpha α</td><td>\theta</td><td>θ \theta θ</td><td>o</td><td>o o o</td><td>\upsilon</td><td>υ \upsilon υ</td></tr><tr><td>\beta</td><td>β \beta β</td><td>\vartheta</td><td>ϑ \vartheta ϑ</td><td>\pi</td><td>π \pi π</td><td>\phi</td><td>ϕ \phi ϕ</td></tr><tr><td>\gamma</td><td>γ \gamma γ</td><td>\iota</td><td>ι \iota ι</td><td>\varpi</td><td>ϖ \varpi ϖ</td><td>\varphi</td><td>φ \varphi φ</td></tr><tr><td>\delta</td><td>δ \delta δ</td><td>\kappa</td><td>κ \kappa κ</td><td>\rho</td><td>ρ \rho ρ</td><td>\chi</td><td>χ \chi χ</td></tr><tr><td>\epsilon</td><td>ϵ \epsilon ϵ</td><td>\lambda</td><td>λ \lambda λ</td><td>\varrho</td><td>ϱ \varrho ϱ</td><td>\psi</td><td>ψ \psi ψ</td></tr><tr><td>\varepsilon</td><td>ε \varepsilon ε</td><td>\mu</td><td>μ \mu μ</td><td>\sigma</td><td>$\sigma$</td><td>\omega</td><td>ω \omega ω</td></tr><tr><td>\zeta</td><td>ζ \zeta ζ</td><td>\nu</td><td>ν \nu ν</td><td>\varsigma</td><td>ς \varsigma ς</td><td>\eta</td><td>η \eta η</td></tr><tr><td>\xi</td><td>ξ \xi ξ</td><td>\tau</td><td>τ \tau τ</td><td></td><td></td><td></td><td></td></tr></tbody></table>

### 大写希腊字母

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>\Gamma</td><td>Γ \Gamma Γ</td><td>\Lambda</td><td>Λ \Lambda Λ</td><td>\Sigma</td><td>Σ \Sigma Σ</td><td>\Psi</td><td>Ψ \Psi Ψ</td></tr><tr><td>\Delta</td><td>Δ \Delta Δ</td><td>\Xi</td><td>Ξ \Xi Ξ</td><td>\Upsilon</td><td>Υ \Upsilon Υ</td><td>\Omega</td><td>Ω \Omega Ω</td></tr><tr><td>\Theta</td><td>Θ \Theta Θ</td><td>\Pi</td><td>Π \Pi Π</td><td>\Phi</td><td>Φ \Phi Φ</td><td></td><td></td></tr></tbody></table>

### 二元关系符

可以通过在下述命令前加上 \ not 来得到其否定形式，如 "\not >" 即为 ≯ \not > ​>。

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>&lt;</td><td>&lt; &lt; &lt;</td><td>&gt;</td><td>&gt; &gt; &gt;</td><td>=</td><td>= = =</td><td>\leq 或 \ le</td><td>≤ \leq ≤</td></tr><tr><td>\geq 或 \ ge</td><td>≥ \ge ≥</td><td>\equiv</td><td>≡ \equiv ≡</td><td>\ll</td><td>≪ \ll ≪</td><td>\gg</td><td>≫ \gg ≫</td></tr><tr><td>\sim</td><td>∼ \sim ∼</td><td>\simeq</td><td>≃ \simeq ≃</td><td>\subset</td><td>⊂ \subset ⊂</td><td>\supset</td><td>⊃ \supset ⊃</td></tr><tr><td>\approx</td><td>≈ \approx ≈</td><td>\subseteq</td><td>⊆ \subseteq ⊆</td><td>\supseteq</td><td>⊇ \supseteq ⊇</td><td>\cong</td><td>≅ \cong ≅</td></tr><tr><td>\in</td><td>∈ \in ∈</td><td>\ni 或 \ owns</td><td>∋ \ni ∋</td><td>\propto</td><td>∝ \propto ∝</td><td>\mid</td><td>∣ \mid ∣</td></tr><tr><td>\parallel</td><td>∥ \parallel ∥</td><td>:</td><td>: : :</td><td>\notin</td><td>∉ \notin ∈/​</td><td>\neq 或 \ ne</td><td>≠ \ne ​=</td></tr></tbody></table>

### 二元运算符

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>+</td><td>+ + +</td><td>-</td><td>− - −</td><td>\mp</td><td>∓ \mp ∓</td><td>\pm</td><td>± \pm ±</td></tr><tr><td>\triangleleft</td><td>◃ \triangleleft ◃</td><td>\triangleright</td><td>▹ \triangleright ▹</td><td>\cdot</td><td>⋅ \cdot ⋅</td><td>\div</td><td>÷ \div ÷</td></tr><tr><td>\times</td><td>× \times ×</td><td>setminus</td><td>∖ \setminus ∖</td><td>\star</td><td>⋆ \star ⋆</td><td>\ast</td><td>∗ \ast ∗</td></tr><tr><td>\cup</td><td>∪ \cup ∪</td><td>\cap</td><td>∩ \cap ∩</td><td>\circ</td><td>∘ \circ ∘</td><td>\bullet</td><td>∙ \bullet ∙</td></tr><tr><td>\vee 或 \ lor</td><td>∨ \vee ∨</td><td>\wedge 或 land</td><td>∧ \land ∧</td><td>\oplus</td><td>⊕ \oplus ⊕</td><td>\ominus</td><td>⊖ \ominus ⊖</td></tr><tr><td>\odot</td><td>⊙ \odot ⊙</td><td>\oslash</td><td>⊘ \oslash ⊘</td><td>\otimes</td><td>⊗ \otimes ⊗</td><td>\diamond</td><td>⋄ \diamond ⋄</td></tr><tr><td>\bigtriangleup</td><td>△ \bigtriangleup △</td><td>\bigtriangledown</td><td>▽ \bigtriangledown ▽</td><td>\bigcirc</td><td>◯ \bigcirc ◯</td><td></td><td></td></tr></tbody></table>

### 大尺寸运算符

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>\sum</td><td>∑ \sum ∑</td><td>\bigcup</td><td>⋃ \bigcup ⋃</td><td>\bigvee</td><td>⋁ \bigvee ⋁</td><td>\bigolus</td><td>⨁ \bigoplus ⨁</td></tr><tr><td>\prod</td><td>∏ \prod ∏</td><td>\bigcap</td><td>⋂ \bigcap ⋂</td><td>\bigwedge</td><td>⋀ \bigwedge ⋀</td><td>\bigotimes</td><td>⨂ \bigotimes ⨂</td></tr><tr><td>\coprod</td><td>∐ \coprod ∐</td><td>\int</td><td>∈ \in ∈</td><td>\oint</td><td>∮ \oint ∮</td><td>\bigodot</td><td>⨀ \bigodot ⨀</td></tr></tbody></table>

### 箭头

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>\leftarrow 或 \ gets</td><td>← \gets ←</td><td>\longleftarrow</td><td>⟵ \longleftarrow ⟵</td><td>\uparrow</td><td>↑ \uparrow ↑</td><td>\downarrow</td><td>↓ \downarrow ↓</td></tr><tr><td>\rightarrow 或 \ to</td><td>→ \to →</td><td>\longrightarrow</td><td>⟶ \longrightarrow ⟶</td><td>\leftrightarrow</td><td>↔ \leftrightarrow ↔</td><td>updownarrow</td><td>↕ \updownarrow ↕</td></tr><tr><td>\Leftarrow</td><td>⇐ \Leftarrow ⇐</td><td>\Longleftarrow</td><td>⟸ \Longleftarrow ⟸</td><td>\Uparrow</td><td>⇑ \Uparrow ⇑</td><td>\Downarrow</td><td>⇓ \Downarrow ⇓</td></tr><tr><td>\Rightarrow</td><td>⇒ \Rightarrow ⇒</td><td>\Longrightarrow</td><td>⟹ \Longrightarrow ⟹</td><td>\Leftrightarrow</td><td>⇔ \Leftrightarrow ⇔</td><td>\Updownarrow</td><td>⇕ \Updownarrow ⇕</td></tr><tr><td>\nearrow</td><td>↗ \nearrow ↗</td><td>\searrow</td><td>↘ \searrow ↘</td><td>\swarrow</td><td>↙ \swarrow ↙</td><td>\nwarrow</td><td>↖ \nwarrow ↖</td></tr><tr><td>\leftharpoonup</td><td>↼ \leftharpoonup ↼</td><td>\rightharpoonup</td><td>⇀ \rightharpoonup ⇀</td><td>\leftharpoondown</td><td>↽ \leftharpoondown ↽</td><td>\rightharpoondown</td><td>⇁ \rightharpoondown ⇁</td></tr><tr><td>\rightleftharpoons</td><td>⇌ \rightleftharpoons ⇌</td><td>\iff</td><td>   ⟺    \iff ⟺</td><td></td><td></td><td></td><td></td></tr></tbody></table>

### 其他符号

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>\dots</td><td>… \dots …</td><td>\cdots</td><td>⋯ \cdots ⋯</td><td>\vdots</td><td>⋮ \vdots ⋮</td><td>\ddots</td><td>⋱ \ddots ⋱</td></tr><tr><td>\hbar</td><td>ℏ \hbar ℏ</td><td>\imath</td><td>ı \imath ı</td><td>\jmath</td><td>ȷ \jmath ȷ</td><td>\ell</td><td>ℓ \ell ℓ</td></tr><tr><td>\Re</td><td>ℜ \Re ℜ</td><td>\Im</td><td>ℑ \Im ℑ</td><td>aleph</td><td>ℵ \aleph ℵ</td><td>\wp</td><td>℘ \wp ℘</td></tr><tr><td>\forall</td><td>∀ \forall ∀</td><td>\exists</td><td>∃ \exists ∃</td><td>\mho</td><td>℧ \mho ℧</td><td>\partial</td><td>∂ \partial ∂</td></tr><tr><td>’</td><td>′ ' ′</td><td>\prime</td><td>′ \prime ′</td><td>\emptyset</td><td>∅ \emptyset ∅</td><td>\infty</td><td>∞ \infty ∞</td></tr><tr><td>\nabla</td><td>∇ \nabla ∇</td><td>\triangle</td><td>△ \triangle △</td><td>\Box</td><td>□ \Box □</td><td>\Diamond</td><td>◊ \Diamond ◊</td></tr><tr><td>\bot</td><td>⊥ \bot ⊥</td><td>\top</td><td>⊤ \top ⊤</td><td>\angle</td><td>∠ \angle ∠</td><td>\surd</td><td>√ \surd √</td></tr><tr><td>\diamondsuit</td><td>♢ \diamondsuit ♢</td><td>\heartsuit</td><td>♡ \heartsuit ♡</td><td>\clubsuit</td><td>♣ \clubsuit ♣</td><td>\spadesuit</td><td>♠ \spadesuit ♠</td></tr><tr><td>\neg 或 \ lnot</td><td>¬ \lnot ¬</td><td>\flat</td><td>♭ \flat ♭</td><td>\natural</td><td>♮ \natural ♮</td><td>\sharp</td><td>♯ \sharp ♯</td></tr></tbody></table>

暂时整理这些符号，其他需要的用到再查。

公式
--

### 函数

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>\sin\theta</td><td>sin ⁡ θ \sin\theta sinθ</td><td>\cos\theta</td><td>cos ⁡ θ \cos\theta cosθ</td><td>\tan\theta</td><td>tan ⁡ θ \tan\theta tanθ</td><td>\cot\theta</td><td>cot ⁡ θ \cot\theta cotθ</td></tr><tr><td>\arcsin\frac{A}{C}</td><td>arcsin ⁡ A C \arcsin\frac{A}{C} arcsinCA​</td><td>\log X</td><td>log ⁡ X \log X logX</td><td>\sqrt{3}</td><td>3 \sqrt{3} 3 <svg width="400em" height="1.08em" viewBox="0 0 400000 1080" preserveAspectRatio="xMinYMin slice"><path d="M95,702c-2.7,0,-7.17,-2.7,-13.5,-8c-5.8,-5.3,-9.5,
-10,-9.5,-14c0,-2,0.3,-3.3,1,-4c1.3,-2.7,23.83,-20.7,67.5,-54c44.2,-33.3,65.8,
-50.3,66.5,-51c1.3,-1.3,3,-2,5,-2c4.7,0,8.7,3.3,12,10s173,378,173,378c0.7,0,
35.3,-71,104,-213c68.7,-142,137.5,-285,206.5,-429c69,-144,104.5,-217.7,106.5,
-221c5.3,-9.3,12,-14,20,-14H400000v40H845.2724s-225.272,467,-225.272,467
s-235,486,-235,486c-2.7,4.7,-9,7,-19,7c-6,0,-10,-1,-12,-3s-194,-422,-194,-422
s-65,47,-65,47z M834 80H400000v40H845z"></path></svg>​</td><td>\sqrt[n]{3}</td><td>3 n \sqrt[n]{3} n3 <svg width="400em" height="1.08em" viewBox="0 0 400000 1080" preserveAspectRatio="xMinYMin slice"><path d="M95,702c-2.7,0,-7.17,-2.7,-13.5,-8c-5.8,-5.3,-9.5,
-10,-9.5,-14c0,-2,0.3,-3.3,1,-4c1.3,-2.7,23.83,-20.7,67.5,-54c44.2,-33.3,65.8,
-50.3,66.5,-51c1.3,-1.3,3,-2,5,-2c4.7,0,8.7,3.3,12,10s173,378,173,378c0.7,0,
35.3,-71,104,-213c68.7,-142,137.5,-285,206.5,-429c69,-144,104.5,-217.7,106.5,
-221c5.3,-9.3,12,-14,20,-14H400000v40H845.2724s-225.272,467,-225.272,467
s-235,486,-235,486c-2.7,4.7,-9,7,-19,7c-6,0,-10,-1,-12,-3s-194,-422,-194,-422
s-65,47,-65,47z M834 80H400000v40H845z"></path></svg>​</td></tr><tr><td>\lim A</td><td>lim ⁡ A \lim A limA</td><td>\lim_{\imath\to n} x_\imath</td><td>lim ⁡ ı → n x ı \lim_{\imath\to n}x_\imath limı→n​xı​</td><td></td><td></td><td></td><td></td></tr></tbody></table>

### 积分、求和

<table><tbody><tr><th>功能</th><th>语法</th><th>效果</th></tr><tr><td rowspan="2">求和</td><td>\sum_{k=1}^N k^2</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\sum_%7bk=1%7d^N%20k^2"></td></tr><tr><td>\\begin{matrix} \sum_{k=1}^N k^2 \\end{matrix}</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\begin%7bmatrix%7d%20\sum_%7bk=1%7d^N%20k^2%20\end%7bmatrix%7d"></td></tr><tr><td rowspan="2">求积</td><td>\prod_{i=1}^N x_i</td><td><img class="" src="http://latex.codecogs.com/gif.latex?\prod_%7bi=1%7d^N%20x_i"></td></tr><tr><td>\\begin{matrix} \prod_{i=1}^N x_i \\end{matrix}</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\begin%7bmatrix%7d%20\prod_%7bi=1%7d^N%20x_i%20\end%7bmatrix%7d"></td></tr><tr><td rowspan="2">积分</td><td>\int_{-N}^{N} e^x\, dx</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\int_%7b-N%7d^%7bN%7d%20e^x\,%20dx"></td></tr><tr><td>\\begin{matrix} \int_{-N}^{N} e^x\, dx\\end{matrix}</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\begin%7bmatrix%7d%20\int_%7b-N%7d^%7bN%7d%20e^x\,%20dx\end%7bmatrix%7d"></td></tr><tr><td>双重积分</td><td>\iint_{-N}^{N} e^x\, dx</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\iint_%7b-N%7d^%7bN%7d%20e^x\,%20dx"></td></tr><tr><td>三重积分</td><td>\iiint_{-N}^{N} e^x\, dx</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\iiint_%7b-N%7d^%7bN%7d%20e^x\,%20dx"></td></tr><tr><td>闭合的曲线、曲面积分</td><td>\oint_{C} x^3\, dx + 4y^2\, dy</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\oint_%7bC%7d%20x^3\,%20dx%20+%204y^2\，dy"></td></tr></tbody></table>

> 注：在实际使用过程中
> 
> ```
> \\begin{}
> \\end{}
> ```
> 
> 应书写为
> 
> ```
> \begin{}
> \end{}
> ```
> 
> 对 html 不熟悉，实在不知道怎么转义让公式不显示，故将 begin、end 前置双斜杠。后面同理。

### 矩阵、方程

<table><tbody><tr><th>功能</th><th>语法</th><th>效果</th></tr><tr><td rowspan="2">矩阵</td><td>\\begin{bmatrix}<br>x &amp; y \\<br>z &amp; v<br>\\end{bmatrix}</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\begin%7bbmatrix%7d%09x%20&amp;%20y%20\\%20z%20&amp;%20v\end%7bbmatrix%7d"></td></tr><tr><td>\\begin{vmatrix}<br>x &amp; y \\<br>z &amp; v<br>\\end{vmatrix}</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\begin%7bvmatrix%7d%20x%20&amp;%20y%20\\%20z%20&amp;%20v\end%7bvmatrix%7d"></td></tr><tr><td>条件定义</td><td>f(n) =<br>\\begin{cases}<br>n/2, &amp; \mbox{if}n\mbox{ is even} \\<br>3n+1, &amp; \mbox{if}n\mbox{ is odd}<br>\\end{cases}</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20f%28n%29%20=%20\begin%7bcases%7d%20n/2,%20%20&amp;%20\mbox%7bif%20%7dn\mbox%7b%20is%20even%7d%20\\%0a%09%093n+1,%20&amp;%20\mbox%7bif%20%7dn\mbox%7b%20is%20odd%7d%20\end%7bcases%7d"></td></tr><tr><td>方程组</td><td>\\begin{cases}<br>3x + 5y + z = 0\\<br>7x - 2y + 4z = 0 \\<br>-6x + 3y + 2z = 0<br>\\end{cases}</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\begin%7bcases%7d%09%093x%20+%205y%20+%20%20z%20=%200\\%09%097x%20-%202y%20+%204z%20=%200%20\\%09%09-6x%20+%203y%20+%20%09%09%092z%20=%200%09%09\end%7bcases%7d"></td></tr><tr><td rowspan="2">上下括号</td><td>\\begin{matrix} 2 \\ \overbrace{<br>\\begin{bmatrix}<br>x &amp; y \\<br>z &amp; v<br>\\end{bmatrix}<br>}\\end{matrix}</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\begin%7bmatrix%7d%202%20\\%20\overbrace%7b\begin%7bbmatrix%7d%09x%20&amp;%20y%20\\%20z%20&amp;%20v\end%7bbmatrix%7d%7d\end%7bmatrix%7d"></td></tr><tr><td>\\begin{matrix} \underbrace{<br>\\begin{vmatrix}<br>x &amp; y \\<br>z &amp; v<br>\\end{vmatrix}} \\<br>2 \\end{matrix}</td><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\begin%7bmatrix%7d%20\underbrace%7b\begin%7bvmatrix%7d%20x%20&amp;%20y%20\\%20z%20&amp;%20v\end%7bvmatrix%7d%7d%20\\%202\end%7bmatrix%7d"></td></tr></tbody></table>

观察方程等的书写语法可知，只需在固定格式中替换所需功能对应的语法即可。

```
\begin{功能}
...
\end{功能}
```

若想在公式或方程后添加编号，只需添加`\tag{序号}`即可，如：

a x + b y + c = 0 (1.1) ax+by+c=0 \tag{1.1} ax+by+c=0(1.1)  
命令为：

```
$$ax+by+c=0 \tag{1.1}$$
```

排版
==

表格
--

Markdown 可以通过多种方式实现表格  
**Markdown 推荐的标准表格**

```
语法|效果|语法|效果|语法|效果|语法|效果
--|--|--|--|--|--|--|--
\sum|$\sum$|\bigcup|$\bigcup$|\bigvee|$\bigvee$|\bigolus|$\bigoplus$
```

效果为：

<table><thead><tr><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th><th>语法</th><th>效果</th></tr></thead><tbody><tr><td>\sum</td><td>∑ \sum ∑</td><td>\bigcup</td><td>⋃ \bigcup ⋃</td><td>\bigvee</td><td>⋁ \bigvee ⋁</td><td>\bigolus</td><td>⨁ \bigoplus ⨁</td></tr></tbody></table>

默认表格内内容居中对齐，若需居左或居右对齐，操作如下：

```
语法|效果|语法|效果|语法|效果
:--|--:|:--|--:|--|:--:
\sum|$\sum$|\bigcup|$\bigcup$|\bigvee|$\bigvee$
```

<table><thead><tr><th align="left">语法</th><th align="right">效果</th><th align="left">语法</th><th align="right">效果</th><th>语法</th><th align="center">效果</th></tr></thead><tbody><tr><td align="left">\sum</td><td align="right">∑ \sum ∑</td><td align="left">\bigcup</td><td align="right">⋃ \bigcup ⋃</td><td>\bigvee</td><td align="center">⋁ \bigvee ⋁</td></tr></tbody></table>

**HTML 格式的表格**  
由于 Markdown 兼容 html 语法，因此可以用 html 语法生成一些复杂形式的表格。如下面可合并行列的表格：

<table><tbody><tr><th rowspan="3">合并行</th><th>第一列</th><th>第二列</th><th>第三列</th></tr><tr><td colspan="2">合并列</td><td rowspan="2">第三列</td></tr><tr><td><img class="" src="http://latex.codecogs.com/gif.latex?%20\omega"></td><td><img class="" src="http://latex.codecogs.com/gif.latex?%2035*d_2"></td></tr></tbody></table>

插入公示，只需添加

```
<img src="http://latex.codecogs.com/gif.latex? latex公式代码" />
```

html 插入公示参考链接：[轮子的博客](http://www.cnblogs.com/haore147/p/3629895.html)

代码为：

```
<table><tbody>
    <tr>
        <th rowspan=3>合并行</th>
        <th>第一列</th>
        <th>第二列</th>
        <th>第三列</th>
    </tr>
    <tr>
        <td colspan=2>合并列</td>
        <td rowspan=2>第三列</td>
    </tr>
    <tr>
        <td><img src="http://latex.codecogs.com/gif.latex? \omega" /></td>
        <td><img src="http://latex.codecogs.com/gif.latex? 35*d_2" /></td>
    </tr>
</table>
```

图片
--

图片尺寸及位置调整参考：[简书](https://www.jianshu.com/p/5c1805c6f0ff)  
插入图片时，可以直接复制粘贴一张图，图片可以是任意位置的图片，粘贴进来会自动生成地址，不用担心图片挪动位置导致图片不显示。但直接复制粘贴的图片默认是居左显示的，如下图：

![](https://img-blog.csdn.net/20181011191243452?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM5MTQ0NzE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

```
![在这里插入图片描述](https://img-blog.csdn.net/20181011190106378?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM5MTQ0NzE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
```

如果想调整图像大小，只需在代码后面添加尺寸约束 “=200x”（宽 x 高），尺寸可以自定义，在不确定图像比例的情况下可以省略高度信息：

```
![在这里插入图片描述](https://img-blog.csdn.net/20181011191327845?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM5MTQ0NzE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70 =200x)
```

效果如下：  
![](https://img-blog.csdn.net/20181011191327845?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM5MTQ0NzE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

也可以用 html 语法调整：

```
<img src="https://img-blog.csdn.net/20181011191327845?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM5MTQ0NzE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" width="500" hegiht="313" />
```

![](https://img-blog.csdn.net/20181011191327845?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM5MTQ0NzE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

若想让图片居中或者居右显示，则替换 align=center 或 right

```
<div align=center><img src="https://img-blog.csdn.net/20181011191327845?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM5MTQ0NzE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70"/></div>
```

![](https://img-blog.csdn.net/20181011191327845?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTM5MTQ0NzE=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

页内跳转
----

参考内容：[Markdown 页内跳转实现方法](https://www.cnblogs.com/tocy/p/markdown-link-inner-page.html)

页内跳转除了通过 Markdown 默认的目录功能外，还可以通过 HTML 中的设置锚点的方式进行。具体操作如下：  
在需要跳转至的地方设置锚点：

```
<span id="jump"></span>
```

其中，span 是设置锚点的关键词，id 可理解为该锚点的定义，“jump” 即为锚点 id，可以自定义，在需要跳转的位置，链接此 id 即可实现跳转。

在需要点击进行跳转的地方链接锚点 id：

```
[点击跳转](#jump)
```

其中，“[]” 中的内容是你希望点击的对象，“( )” 中是锚点 id。

示例：查看[跳转效果](#%E8%B7%B3%E8%BD%AC)。  
操作步骤如下图所示：  
![](https://img-blog.csdnimg.cn/20181120161826792.png)  
![](https://img-blog.csdnimg.cn/20181120161851792.png)