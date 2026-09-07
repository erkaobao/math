---
layout: archive
title: "MATH 5345H --- Week 6: Metric topologies, metrizability, and sequences"
permalink: /teaching/5345h_notes/week_6
author_profile: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S0.SS1" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.1  (§20) The metric topology</h2>

<div id="S0.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S0.I1" class="ltx_itemize">
<li id="S0.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i1.p1.m1" class="ltx_Math" alttext="(X,\mathcal{T})" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo stretchy="false">)</mo></mrow></math> is <em class="ltx_emph ltx_font_italic">metrizable</em> if <math id="S0.I1.i1.p1.m2" class="ltx_Math" alttext="\mathcal{T}=\mathcal{T}_{d}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>=</mo><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>d</mi></msub></mrow></math> for some metric <math id="S0.I1.i1.p1.m3" class="ltx_Math" alttext="d" display="inline"><mi>d</mi></math>.</p>
</div>
</li>
<li id="S0.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i2.p1.m1" class="ltx_Math" alttext="(X,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> <em class="ltx_emph ltx_font_italic">bounded</em> if <math id="S0.I1.i2.p1.m2" class="ltx_Math" alttext="d\leq M" display="inline"><mrow><mi>d</mi><mo>≤</mo><mi>M</mi></mrow></math> throughout;
<math id="S0.I1.i2.p1.m3" class="ltx_Math" alttext="\operatorname{diam}(X)=\sup\{d(x,y)\}" display="inline"><mrow><mrow><mi>diam</mi><mo>⁡</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo stretchy="false">)</mo></mrow></mrow><mo rspace="0.1389em">=</mo><mrow><mo lspace="0.1389em" rspace="0em">sup</mo><mrow><mo stretchy="false">{</mo><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">}</mo></mrow></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i3.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i3.p1.m2" class="ltx_Math" alttext="\bar{d}(x,y)=\min\{d(x,y),1\}" display="inline"><mrow><mrow><mover accent="true"><mi>d</mi><mo>¯</mo></mover><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>min</mi><mo>⁡</mo><mrow><mo stretchy="false">{</mo><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>,</mo><mn>1</mn><mo stretchy="false">}</mo></mrow></mrow></mrow></math> is a bounded metric inducing the <em class="ltx_emph ltx_font_italic">same</em>
topology as <math id="S0.I1.i3.p1.m3" class="ltx_Math" alttext="d" display="inline"><mi>d</mi></math>.</p>
</div>
<div id="S0.I1.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Triangle inequality by cases. Same topology because <math id="S0.I1.i3.p2.m1" class="ltx_Math" alttext="\varepsilon" display="inline"><mi mathcolor="#3D3D3D">ε</mi></math>-balls with <math id="S0.I1.i3.p2.m2" class="ltx_Math" alttext="\varepsilon&lt;1" display="inline"><mrow><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D">&lt;</mo><mn mathcolor="#3D3D3D">1</mn></mrow></math>
already form a basis, and there <math id="S0.I1.i3.p2.m3" class="ltx_Math" alttext="d" display="inline"><mi mathcolor="#3D3D3D">d</mi></math> and <math id="S0.I1.i3.p2.m4" class="ltx_Math" alttext="\bar{d}" display="inline"><mover accent="true"><mi mathcolor="#3D3D3D">d</mi><mo mathcolor="#3D3D3D">¯</mo></mover></math> agree. Moral: boundedness is metric data,
not topological data.</span></span></p>
</div>
</li>
<li id="S0.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> On <math id="S0.I1.i4.p1.m1" class="ltx_Math" alttext="\mathbb{R}^{n}" display="inline"><msup><mi>ℝ</mi><mi>n</mi></msup></math>:  <math id="S0.I1.i4.p1.m2" class="ltx_Math" alttext="\|x\|=\sqrt{x_{1}^{2}+\cdots+x_{n}^{2}}" display="inline"><mrow><mrow><mo stretchy="false">‖</mo><mi>x</mi><mo stretchy="false">‖</mo></mrow><mo>=</mo><msqrt><mrow><msubsup><mi>x</mi><mn>1</mn><mn>2</mn></msubsup><mo>+</mo><mi mathvariant="normal">⋯</mi><mo>+</mo><msubsup><mi>x</mi><mi>n</mi><mn>2</mn></msubsup></mrow></msqrt></mrow></math>, <math id="S0.I1.i4.p1.m3" class="ltx_Math" alttext="d(x,y)=\|y-x\|" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">‖</mo><mrow><mi>y</mi><mo>−</mo><mi>x</mi></mrow><mo stretchy="false">‖</mo></mrow></mrow></math> (Euclidean);
<math id="S0.I1.i4.p1.m4" class="ltx_Math" alttext="\|x\|_{\infty}=\max_{i}|x_{i}|" display="inline"><mrow><msub><mrow><mo stretchy="false">‖</mo><mi>x</mi><mo stretchy="false">‖</mo></mrow><mi mathvariant="normal">∞</mi></msub><mo>=</mo><mrow><msub><mi>max</mi><mi>i</mi></msub><mo>⁡</mo><mrow><mo stretchy="false">|</mo><msub><mi>x</mi><mi>i</mi></msub><mo stretchy="false">|</mo></mrow></mrow></mrow></math>, <math id="S0.I1.i4.p1.m5" class="ltx_Math" alttext="\rho(x,y)=\|y-x\|_{\infty}" display="inline"><mrow><mrow><mi>ρ</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><msub><mrow><mo stretchy="false">‖</mo><mrow><mi>y</mi><mo>−</mo><mi>x</mi></mrow><mo stretchy="false">‖</mo></mrow><mi mathvariant="normal">∞</mi></msub></mrow></math> (square metric).</p>
</div>
</li>
<li id="S0.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i5.p1.m1" class="ltx_Math" alttext="d" display="inline"><mi>d</mi></math> and <math id="S0.I1.i5.p1.m2" class="ltx_Math" alttext="\rho" display="inline"><mi>ρ</mi></math> induce the same topology on <math id="S0.I1.i5.p1.m3" class="ltx_Math" alttext="\mathbb{R}^{n}" display="inline"><msup><mi>ℝ</mi><mi>n</mi></msup></math>.</p>
</div>
</li>
<li id="S0.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i6.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i6.p1.m1" class="ltx_Math" alttext="\mathbb{R}^{J}=\{x\colon J\to\mathbb{R}\}" display="inline"><mrow><msup><mi>ℝ</mi><mi>J</mi></msup><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>x</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>J</mi><mo stretchy="false">→</mo><mi>ℝ</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>;  <math id="S0.I1.i6.p1.m2" class="ltx_Math" alttext="\mathbb{R}^{\omega}" display="inline"><msup><mi>ℝ</mi><mi>ω</mi></msup></math> for <math id="S0.I1.i6.p1.m3" class="ltx_Math" alttext="J=\mathbb{N}" display="inline"><mrow><mi>J</mi><mo>=</mo><mi>ℕ</mi></mrow></math>.</p>
</div>
<div id="S0.I1.i6.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Neither <math id="S0.I1.i6.p2.m1" class="ltx_Math" alttext="\|x\|" display="inline"><mrow><mo mathcolor="#737373" stretchy="false">‖</mo><mi mathcolor="#737373">x</mi><mo mathcolor="#737373" stretchy="false">‖</mo></mrow></math> nor <math id="S0.I1.i6.p2.m2" class="ltx_Math" alttext="\|x\|_{\infty}" display="inline"><msub><mrow><mo mathcolor="#737373" stretchy="false">‖</mo><mi mathcolor="#737373">x</mi><mo mathcolor="#737373" stretchy="false">‖</mo></mrow><mi mathcolor="#737373" mathvariant="normal">∞</mi></msub></math> is defined for all of <math id="S0.I1.i6.p2.m3" class="ltx_Math" alttext="\mathbb{R}^{\omega}" display="inline"><msup><mi mathcolor="#737373">ℝ</mi><mi mathcolor="#737373">ω</mi></msup></math> — hence the need to
truncate with <math id="S0.I1.i6.p2.m4" class="ltx_Math" alttext="\bar{d}" display="inline"><mover accent="true"><mi mathcolor="#737373">d</mi><mo mathcolor="#737373">¯</mo></mover></math>.</span></span></span></p>
</div>
</li>
<li id="S0.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">Uniform metric</em> on <math id="S0.I1.i7.p1.m1" class="ltx_Math" alttext="X^{J}" display="inline"><msup><mi>X</mi><mi>J</mi></msup></math>, <math id="S0.I1.i7.p1.m2" class="ltx_Math" alttext="(X,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> metric:
<math id="S0.I1.i7.p1.m3" class="ltx_Math" alttext="\bar{\rho}(x,y)=\sup\{\bar{d}(x_{\alpha},y_{\alpha})\mid\alpha\in J\}." display="inline"><mrow><mrow><mrow><mover accent="true"><mi>ρ</mi><mo>¯</mo></mover><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo rspace="0.1389em">=</mo><mrow><mo lspace="0.1389em" rspace="0em">sup</mo><mrow><mo stretchy="false">{</mo><mrow><mover accent="true"><mi>d</mi><mo>¯</mo></mover><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mi>α</mi></msub><mo>,</mo><msub><mi>y</mi><mi>α</mi></msub><mo stretchy="false">)</mo></mrow></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></mrow><mo lspace="0em">.</mo></mrow></math>
The induced topology is the <em class="ltx_emph ltx_font_italic">uniform topology</em>.</p>
</div>
</li>
<li id="S0.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i8.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> On <math id="S0.I1.i8.p1.m1" class="ltx_Math" alttext="\mathbb{R}^{J}" display="inline"><msup><mi>ℝ</mi><mi>J</mi></msup></math>: uniform topology is finer than the product topology
(strictly, for <math id="S0.I1.i8.p1.m2" class="ltx_Math" alttext="J" display="inline"><mi>J</mi></math> infinite).</p>
</div>
<div id="S0.I1.i8.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Given a basis box <math id="S0.I1.i8.p2.m1" class="ltx_Math" alttext="B" display="inline"><mi mathcolor="#3D3D3D">B</mi></math> constrained at <math id="S0.I1.i8.p2.m2" class="ltx_Math" alttext="\alpha_{1},\dots,\alpha_{n}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">α</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D" mathvariant="normal">…</mi><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">α</mi><mi mathcolor="#3D3D3D">n</mi></msub></mrow></math>, take
<math id="S0.I1.i8.p2.m3" class="ltx_Math" alttext="\varepsilon=\min_{i}\varepsilon_{i}" display="inline"><mrow><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D">=</mo><mrow><msub><mi mathcolor="#3D3D3D">min</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo lspace="0.167em">⁡</mo><msub><mi mathcolor="#3D3D3D">ε</mi><mi mathcolor="#3D3D3D">i</mi></msub></mrow></mrow></math>; then <math id="S0.I1.i8.p2.m4" class="ltx_Math" alttext="B_{\bar{\rho}}(x,\varepsilon)\subset B" display="inline"><mrow><mrow><msub><mi mathcolor="#3D3D3D">B</mi><mover accent="true"><mi mathcolor="#3D3D3D">ρ</mi><mo mathcolor="#3D3D3D">¯</mo></mover></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">⊂</mo><mi mathcolor="#3D3D3D">B</mi></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i9.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i9.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> The product topology on <math id="S0.I1.i9.p1.m2" class="ltx_Math" alttext="\mathbb{R}^{\omega}" display="inline"><msup><mi>ℝ</mi><mi>ω</mi></msup></math> <em class="ltx_emph ltx_font_italic">is</em> metrizable:
<math id="S0.I1.i9.p1.m3" class="ltx_Math" alttext="D(x,y)=\sup\bigl{\{}\bar{d}(x_{n},y_{n})/n\;\bigm{|}\;n\in\mathbb{N}\bigr{\}}" display="inline"><mrow><mrow><mi>D</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo rspace="0.1389em">=</mo><mrow><mo lspace="0.1389em" rspace="0em">sup</mo><mrow><mo maxsize="120%" minsize="120%">{</mo><mrow><mrow><mover accent="true"><mi>d</mi><mo>¯</mo></mover><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mi>n</mi></msub><mo>,</mo><msub><mi>y</mi><mi>n</mi></msub><mo stretchy="false">)</mo></mrow></mrow><mo>/</mo><mi>n</mi></mrow><mo mathsize="120%">|</mo><mrow><mi>n</mi><mo>∈</mo><mi>ℕ</mi></mrow><mo maxsize="120%" minsize="120%">}</mo></mrow></mrow></mrow></math>
induces it.</p>
</div>
<div id="S0.I1.i9.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">The <math id="S0.I1.i9.p2.m1" class="ltx_Math" alttext="1/n" display="inline"><mrow><mn mathcolor="#737373">1</mn><mo mathcolor="#737373">/</mo><mi mathcolor="#737373">n</mi></mrow></math> damping makes all but finitely many coordinates irrelevant at scale
<math id="S0.I1.i9.p2.m2" class="ltx_Math" alttext="\varepsilon" display="inline"><mi mathcolor="#737373">ε</mi></math> — exactly matching “<math id="S0.I1.i9.p2.m3" class="ltx_Math" alttext="U_{n}\neq\mathbb{R}" display="inline"><mrow><msub><mi mathcolor="#737373">U</mi><mi mathcolor="#737373">n</mi></msub><mo mathcolor="#737373">≠</mo><mi mathcolor="#737373">ℝ</mi></mrow></math> for finitely many <math id="S0.I1.i9.p2.m4" class="ltx_Math" alttext="n" display="inline"><mi mathcolor="#737373">n</mi></math>”.</span></span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S0.SS2" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.2  (§21) The metric topology, continued</h2>

<div id="S0.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S0.I2" class="ltx_itemize">
<li id="S0.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I2.i1.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> has a <em class="ltx_emph ltx_font_italic">countable basis at <math id="S0.I2.i1.p1.m2" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math></em> if there are neighborhoods
<math id="S0.I2.i1.p1.m3" class="ltx_Math" alttext="\{B_{n}\}_{n=1}^{\infty}" display="inline"><msubsup><mrow><mo stretchy="false">{</mo><msub><mi>B</mi><mi>n</mi></msub><mo stretchy="false">}</mo></mrow><mrow><mi>n</mi><mo>=</mo><mn>1</mn></mrow><mi mathvariant="normal">∞</mi></msubsup></math> of <math id="S0.I2.i1.p1.m4" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> such that every neighborhood of <math id="S0.I2.i1.p1.m5" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> contains some <math id="S0.I2.i1.p1.m6" class="ltx_Math" alttext="B_{n}" display="inline"><msub><mi>B</mi><mi>n</mi></msub></math>.
<math id="S0.I2.i1.p1.m7" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">first-countable</em> if this holds at every point.
May assume <math id="S0.I2.i1.p1.m8" class="ltx_Math" alttext="B_{1}\supset B_{2}\supset\cdots" display="inline"><mrow><msub><mi>B</mi><mn>1</mn></msub><mo>⊃</mo><msub><mi>B</mi><mn>2</mn></msub><mo>⊃</mo><mi mathvariant="normal">⋯</mi></mrow></math> (replace <math id="S0.I2.i1.p1.m9" class="ltx_Math" alttext="B_{n}" display="inline"><msub><mi>B</mi><mi>n</mi></msub></math> by <math id="S0.I2.i1.p1.m10" class="ltx_Math" alttext="B_{1}\cap\cdots\cap B_{n}" display="inline"><mrow><msub><mi>B</mi><mn>1</mn></msub><mo>∩</mo><mi mathvariant="normal">⋯</mi><mo>∩</mo><msub><mi>B</mi><mi>n</mi></msub></mrow></math>).</p>
</div>
</li>
<li id="S0.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Every metric space is first-countable  — take <math id="S0.I2.i2.p1.m1" class="ltx_Math" alttext="B_{d}(x,1/n)" display="inline"><mrow><msub><mi>B</mi><mi>d</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mrow><mn>1</mn><mo>/</mo><mi>n</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i3.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <span class="ltx_text ltx_font_bold">(Sequence lemma.)</span> If some sequence in <math id="S0.I2.i3.p1.m2" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> converges to <math id="S0.I2.i3.p1.m3" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math>, then
<math id="S0.I2.i3.p1.m4" class="ltx_Math" alttext="x\in\bar{A}" display="inline"><mrow><mi>x</mi><mo>∈</mo><mover accent="true"><mi>A</mi><mo>¯</mo></mover></mrow></math>. If <math id="S0.I2.i3.p1.m5" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is metrizable, the converse holds.</p>
</div>
<div id="S0.I2.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Converse: pick <math id="S0.I2.i3.p2.m1" class="ltx_Math" alttext="x_{n}\in A\cap B_{d}(x,1/n)" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D">∈</mo><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">∩</mo><mrow><msub><mi mathcolor="#3D3D3D">B</mi><mi mathcolor="#3D3D3D">d</mi></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mrow><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">/</mo><mi mathcolor="#3D3D3D">n</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i4.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I2.i4.p1.m2" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> continuous <math id="S0.I2.i4.p1.m3" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> (<math id="S0.I2.i4.p1.m4" class="ltx_Math" alttext="x_{n}\to x" display="inline"><mrow><msub><mi>x</mi><mi>n</mi></msub><mo stretchy="false">→</mo><mi>x</mi></mrow></math> gives <math id="S0.I2.i4.p1.m5" class="ltx_Math" alttext="f(x_{n})\to f(x)" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mi>n</mi></msub><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">→</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>).
If <math id="S0.I2.i4.p1.m6" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is metrizable, the converse holds.</p>
</div>
<div id="S0.I2.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Converse: show <math id="S0.I2.i4.p2.m1" class="ltx_Math" alttext="f(\bar{A})\subset\overline{f(A)}" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mover accent="true"><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">¯</mo></mover><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">⊂</mo><mover accent="true"><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">¯</mo></mover></mrow></math> using the sequence lemma.</span></span></p>
</div>
</li>
<li id="S0.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I2.i5.p1.m2" class="ltx_Math" alttext="\mathbb{R}^{J}" display="inline"><msup><mi>ℝ</mi><mi>J</mi></msup></math> with <math id="S0.I2.i5.p1.m3" class="ltx_Math" alttext="J" display="inline"><mi>J</mi></math> uncountable is <em class="ltx_emph ltx_font_italic">not</em> metrizable.</p>
</div>
<div id="S0.I2.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Let <math id="S0.I2.i5.p2.m1" class="ltx_Math" alttext="A=\{x\mid x_{\alpha}\neq 1\text{ for finitely many }\alpha\}" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">x</mi><mo fence="true" lspace="0em" mathcolor="#3D3D3D" rspace="0em">∣</mo><mrow><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">α</mi></msub><mo mathcolor="#3D3D3D">≠</mo><mrow><mn mathcolor="#3D3D3D">1</mn><mo>⁢</mo><mtext mathcolor="#3D3D3D"> for finitely many </mtext><mo>⁢</mo><mi mathcolor="#3D3D3D">α</mi></mrow></mrow><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></math> and <math id="S0.I2.i5.p2.m2" class="ltx_Math" alttext="x=0" display="inline"><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">=</mo><mn mathcolor="#3D3D3D">0</mn></mrow></math>.
Then <math id="S0.I2.i5.p2.m3" class="ltx_Math" alttext="0\in\bar{A}" display="inline"><mrow><mn mathcolor="#3D3D3D">0</mn><mo mathcolor="#3D3D3D">∈</mo><mover accent="true"><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">¯</mo></mover></mrow></math>, but no sequence in <math id="S0.I2.i5.p2.m4" class="ltx_Math" alttext="A" display="inline"><mi mathcolor="#3D3D3D">A</mi></math> converges to <math id="S0.I2.i5.p2.m5" class="ltx_Math" alttext="0" display="inline"><mn mathcolor="#3D3D3D">0</mn></math>: the union of countably many finite
“support” sets misses some <math id="S0.I2.i5.p2.m6" class="ltx_Math" alttext="\beta\in J" display="inline"><mrow><mi mathcolor="#3D3D3D">β</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">J</mi></mrow></math>, and <math id="S0.I2.i5.p2.m7" class="ltx_Math" alttext="\pi_{\beta}^{-1}(-\tfrac{1}{2},\tfrac{1}{2})" display="inline"><mrow><msubsup><mi mathcolor="#3D3D3D">π</mi><mi mathcolor="#3D3D3D">β</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msubsup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mo mathcolor="#3D3D3D">−</mo><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mn mathcolor="#3D3D3D">2</mn></mfrac></mrow><mo mathcolor="#3D3D3D">,</mo><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mn mathcolor="#3D3D3D">2</mn></mfrac><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> separates.
So the sequence lemma fails.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:59:10 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
