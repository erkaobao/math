---
layout: archive
title: "MATH 5345H --- Week 11: Normal spaces and the Urysohn lemma"
permalink: /teaching/5345h_notes/week_11
author_profile: false
render_with_liquid: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S0.SS1" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.1  (§33) The Urysohn lemma</h2>

<div id="S0.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S0.I1" class="ltx_itemize">
<li id="S0.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Urysohn’s lemma.)</span> <math id="S0.I1.i1.p1.m2" class="ltx_Math" alttext="A,B" display="inline"><mrow><mi>A</mi><mo>,</mo><mi>B</mi></mrow></math> disjoint closed subsets of a normal space <math id="S0.I1.i1.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>
<math id="S0.I1.i1.p1.m4" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> there is a map <math id="S0.I1.i1.p1.m5" class="ltx_Math" alttext="f\colon X\to[0,1]" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></mrow></mrow></math> with <math id="S0.I1.i1.p1.m6" class="ltx_Math" alttext="f\equiv 0" display="inline"><mrow><mi>f</mi><mo>≡</mo><mn>0</mn></mrow></math> on <math id="S0.I1.i1.p1.m7" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> and <math id="S0.I1.i1.p1.m8" class="ltx_Math" alttext="f\equiv 1" display="inline"><mrow><mi>f</mi><mo>≡</mo><mn>1</mn></mrow></math> on <math id="S0.I1.i1.p1.m9" class="ltx_Math" alttext="B" display="inline"><mi>B</mi></math>.</p>
</div>
</li>
<li id="S0.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Proof, on the board in four moves.</span></p>
<ol id="S0.I1.i2.I1" class="ltx_enumerate">
<li id="S0.I1.i2.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(1)</span> 
<div id="S0.I1.i2.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Dyadic rationals</em> <math id="S0.I1.i2.I1.i1.p1.m1" class="ltx_Math" alttext="r=a/2^{n}" display="inline"><mrow><mi>r</mi><mo>=</mo><mrow><mi>a</mi><mo>/</mo><msup><mn>2</mn><mi>n</mi></msup></mrow></mrow></math> are dense in <math id="S0.I1.i2.I1.i1.p1.m2" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>.</p>
</div>
</li>
<li id="S0.I1.i2.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(2)</span> 
<div id="S0.I1.i2.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Build a nested family.</em> <math id="S0.I1.i2.I1.i2.p1.m1" class="ltx_Math" alttext="U_{1}=X-B" display="inline"><mrow><msub><mi>U</mi><mn>1</mn></msub><mo>=</mo><mrow><mi>X</mi><mo>−</mo><mi>B</mi></mrow></mrow></math>; normality gives <math id="S0.I1.i2.I1.i2.p1.m2" class="ltx_Math" alttext="U_{0}" display="inline"><msub><mi>U</mi><mn>0</mn></msub></math> with
<math id="S0.I1.i2.I1.i2.p1.m3" class="ltx_Math" alttext="A\subset U_{0}\subset\bar{U}_{0}\subset U_{1}" display="inline"><mrow><mi>A</mi><mo>⊂</mo><msub><mi>U</mi><mn>0</mn></msub><mo>⊂</mo><msub><mover accent="true"><mi>U</mi><mo>¯</mo></mover><mn>0</mn></msub><mo>⊂</mo><msub><mi>U</mi><mn>1</mn></msub></mrow></math>, then <math id="S0.I1.i2.I1.i2.p1.m4" class="ltx_Math" alttext="U_{1/2}" display="inline"><msub><mi>U</mi><mrow><mn>1</mn><mo>/</mo><mn>2</mn></mrow></msub></math> between them.
Inductively insert <math id="S0.I1.i2.I1.i2.p1.m5" class="ltx_Math" alttext="U_{(2b+1)/2^{n}}" display="inline"><msub><mi>U</mi><mrow><mrow><mo stretchy="false">(</mo><mrow><mrow><mn>2</mn><mo>⁢</mo><mi>b</mi></mrow><mo>+</mo><mn>1</mn></mrow><mo stretchy="false">)</mo></mrow><mo>/</mo><msup><mn>2</mn><mi>n</mi></msup></mrow></msub></math> between <math id="S0.I1.i2.I1.i2.p1.m6" class="ltx_Math" alttext="U_{2b/2^{n}}" display="inline"><msub><mi>U</mi><mrow><mrow><mn>2</mn><mo>⁢</mo><mi>b</mi></mrow><mo>/</mo><msup><mn>2</mn><mi>n</mi></msup></mrow></msub></math> and <math id="S0.I1.i2.I1.i2.p1.m7" class="ltx_Math" alttext="U_{(2b+2)/2^{n}}" display="inline"><msub><mi>U</mi><mrow><mrow><mo stretchy="false">(</mo><mrow><mrow><mn>2</mn><mo>⁢</mo><mi>b</mi></mrow><mo>+</mo><mn>2</mn></mrow><mo stretchy="false">)</mo></mrow><mo>/</mo><msup><mn>2</mn><mi>n</mi></msup></mrow></msub></math>.
Result: <math id="S0.I1.i2.I1.i2.p1.m8" class="ltx_Math" alttext="\bar{U}_{p}\subset U_{q}" display="inline"><mrow><msub><mover accent="true"><mi>U</mi><mo>¯</mo></mover><mi>p</mi></msub><mo>⊂</mo><msub><mi>U</mi><mi>q</mi></msub></mrow></math> whenever <math id="S0.I1.i2.I1.i2.p1.m9" class="ltx_Math" alttext="p&lt;q" display="inline"><mrow><mi>p</mi><mo>&lt;</mo><mi>q</mi></mrow></math>.
Extend by <math id="S0.I1.i2.I1.i2.p1.m10" class="ltx_Math" alttext="U_{r}=\emptyset" display="inline"><mrow><msub><mi>U</mi><mi>r</mi></msub><mo>=</mo><mi mathvariant="normal">∅</mi></mrow></math> for <math id="S0.I1.i2.I1.i2.p1.m11" class="ltx_Math" alttext="r&lt;0" display="inline"><mrow><mi>r</mi><mo>&lt;</mo><mn>0</mn></mrow></math> and <math id="S0.I1.i2.I1.i2.p1.m12" class="ltx_Math" alttext="U_{r}=X" display="inline"><mrow><msub><mi>U</mi><mi>r</mi></msub><mo>=</mo><mi>X</mi></mrow></math> for <math id="S0.I1.i2.I1.i2.p1.m13" class="ltx_Math" alttext="r&gt;1" display="inline"><mrow><mi>r</mi><mo>&gt;</mo><mn>1</mn></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i2.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(3)</span> 
<div id="S0.I1.i2.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Define</em> <math id="S0.I1.i2.I1.i3.p1.m1" class="ltx_Math" alttext="D(x)=\{r\text{ dyadic}\mid x\in U_{r}\}" display="inline"><mrow><mrow><mi>D</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mi>r</mi><mo>⁢</mo><mtext> dyadic</mtext></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>x</mi><mo>∈</mo><msub><mi>U</mi><mi>r</mi></msub></mrow><mo stretchy="false">}</mo></mrow></mrow></math> and
<math id="S0.I1.i2.I1.i3.p1.m2" class="ltx_Math" alttext="f(x)=\inf D(x)\in[0,1]." display="inline"><mrow><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo rspace="0.1389em">=</mo><mrow><mo lspace="0.1389em" rspace="0.167em">inf</mo><mrow><mi>D</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow><mo>∈</mo><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></mrow><mo lspace="0em">.</mo></mrow></math></p>
</div>
</li>
<li id="S0.I1.i2.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(4)</span> 
<div id="S0.I1.i2.I1.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Three claims.</em>
(a) <math id="S0.I1.i2.I1.i4.p1.m1" class="ltx_Math" alttext="x\in\bar{U}_{r}\Rightarrow f(x)\leq r" display="inline"><mrow><mi>x</mi><mo>∈</mo><msub><mover accent="true"><mi>U</mi><mo>¯</mo></mover><mi>r</mi></msub><mo stretchy="false">⇒</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>≤</mo><mi>r</mi></mrow></math>; 
(b) <math id="S0.I1.i2.I1.i4.p1.m2" class="ltx_Math" alttext="x\notin U_{r}\Rightarrow f(x)\geq r" display="inline"><mrow><mi>x</mi><mo>∉</mo><msub><mi>U</mi><mi>r</mi></msub><mo stretchy="false">⇒</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>≥</mo><mi>r</mi></mrow></math>; 
(c) <math id="S0.I1.i2.I1.i4.p1.m3" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is continuous.</p>
</div>
</li>
</ol>
</div>
<div id="S0.I1.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> For (c): given <math id="S0.I1.i2.p2.m1" class="ltx_Math" alttext="(c,d)\ni f(x)" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">d</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D">∋</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>, pick dyadic <math id="S0.I1.i2.p2.m2" class="ltx_Math" alttext="c&lt;p&lt;f(x)&lt;q&lt;d" display="inline"><mrow><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D">&lt;</mo><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D">&lt;</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">&lt;</mo><mi mathcolor="#3D3D3D">q</mi><mo mathcolor="#3D3D3D">&lt;</mo><mi mathcolor="#3D3D3D">d</mi></mrow></math>; then
<math id="S0.I1.i2.p2.m3" class="ltx_Math" alttext="U=U_{q}-\bar{U}_{p}" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">=</mo><mrow><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">q</mi></msub><mo mathcolor="#3D3D3D">−</mo><msub><mover accent="true"><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">¯</mo></mover><mi mathcolor="#3D3D3D">p</mi></msub></mrow></mrow></math> is a neighborhood of <math id="S0.I1.i2.p2.m4" class="ltx_Math" alttext="x" display="inline"><mi mathcolor="#3D3D3D">x</mi></math> with <math id="S0.I1.i2.p2.m5" class="ltx_Math" alttext="f(U)\subset(c,d)" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">⊂</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">d</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i3.p1.m1" class="ltx_Math" alttext="A,B" display="inline"><mrow><mi>A</mi><mo>,</mo><mi>B</mi></mrow></math> are <em class="ltx_emph ltx_font_italic">separated by a continuous function</em> if some <math id="S0.I1.i3.p1.m2" class="ltx_Math" alttext="f\colon X\to\mathbb{R}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></mrow></math>
is <math id="S0.I1.i3.p1.m3" class="ltx_Math" alttext="0" display="inline"><mn>0</mn></math> on <math id="S0.I1.i3.p1.m4" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> and <math id="S0.I1.i3.p1.m5" class="ltx_Math" alttext="1" display="inline"><mn>1</mn></math> on <math id="S0.I1.i3.p1.m6" class="ltx_Math" alttext="B" display="inline"><mi>B</mi></math>. (Forces <math id="S0.I1.i3.p1.m7" class="ltx_Math" alttext="A\cap B=\emptyset" display="inline"><mrow><mrow><mi>A</mi><mo>∩</mo><mi>B</mi></mrow><mo>=</mo><mi mathvariant="normal">∅</mi></mrow></math>.)</p>
</div>
</li>
<li id="S0.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i4.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">completely regular</em> (<math id="S0.I1.i4.p1.m2" class="ltx_Math" alttext="T_{3\frac{1}{2}}" display="inline"><msub><mi>T</mi><mrow><mn>3</mn><mo lspace="0.222em" rspace="0.222em">⁤</mo><mfrac><mn>1</mn><mn>2</mn></mfrac></mrow></msub></math>) if points are closed and each
point and disjoint closed set are separated by a continuous function.</p>
</div>
</li>
<li id="S0.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Normal <math id="S0.I1.i5.p1.m1" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> completely regular <math id="S0.I1.i5.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> regular.</p>
</div>
<div id="S0.I1.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> First: Urysohn with <math id="S0.I1.i5.p2.m1" class="ltx_Math" alttext="A=\{x\}" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></math>.
Second: <math id="S0.I1.i5.p2.m2" class="ltx_Math" alttext="U=f^{-1}[0,\tfrac{1}{2})" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mn mathcolor="#3D3D3D">0</mn><mo mathcolor="#3D3D3D">,</mo><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mn mathcolor="#3D3D3D">2</mn></mfrac><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>, <math id="S0.I1.i5.p2.m3" class="ltx_Math" alttext="V=f^{-1}(\tfrac{1}{2},1]" display="inline"><mrow><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mn mathcolor="#3D3D3D">2</mn></mfrac><mo mathcolor="#3D3D3D">,</mo><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i6.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> Subspaces and products of completely regular spaces are completely regular.
<span class="ltx_text ltx_font_bold">Caution.</span> The same is <em class="ltx_emph ltx_font_italic">not</em> true for normality.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S0.SS2" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.2  (§34) The Urysohn metrization theorem</h2>

<div id="S0.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S0.I2" class="ltx_itemize">
<li id="S0.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> Every second-countable regular space is metrizable.</p>
</div>
</li>
<li id="S0.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Proof: embed <math id="S0.I2.i2.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> into <math id="S0.I2.i2.p1.m2" class="ltx_Math" alttext="\mathbb{R}^{\omega}" display="inline"><msup><mi>ℝ</mi><mi>ω</mi></msup></math> (product topology, which is metrizable).</span></p>
<ol id="S0.I2.i2.I1" class="ltx_enumerate">
<li id="S0.I2.i2.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(1)</span> 
<div id="S0.I2.i2.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Claim 1: a countable separating family.</em> There are maps <math id="S0.I2.i2.I1.i1.p1.m1" class="ltx_Math" alttext="f_{k}\colon X\to[0,1]" display="inline"><mrow><msub><mi>f</mi><mi>k</mi></msub><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></mrow></mrow></math>
such that for every <math id="S0.I2.i2.I1.i1.p1.m2" class="ltx_Math" alttext="p\in U" display="inline"><mrow><mi>p</mi><mo>∈</mo><mi>U</mi></mrow></math> open, some <math id="S0.I2.i2.I1.i1.p1.m3" class="ltx_Math" alttext="f_{k}" display="inline"><msub><mi>f</mi><mi>k</mi></msub></math> has <math id="S0.I2.i2.I1.i1.p1.m4" class="ltx_Math" alttext="f_{k}(p)=1" display="inline"><mrow><mrow><msub><mi>f</mi><mi>k</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>p</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mn>1</mn></mrow></math> and <math id="S0.I2.i2.I1.i1.p1.m5" class="ltx_Math" alttext="f_{k}(X-U)\subset\{0\}" display="inline"><mrow><mrow><msub><mi>f</mi><mi>k</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>X</mi><mo>−</mo><mi>U</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i2.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(2)</span> 
<div id="S0.I2.i2.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Construction.</em> <math id="S0.I2.i2.I1.i2.p1.m1" class="ltx_Math" alttext="\{B_{n}\}" display="inline"><mrow><mo stretchy="false">{</mo><msub><mi>B</mi><mi>n</mi></msub><mo stretchy="false">}</mo></mrow></math> a countable basis. For each pair <math id="S0.I2.i2.I1.i2.p1.m2" class="ltx_Math" alttext="(m,n)" display="inline"><mrow><mo stretchy="false">(</mo><mi>m</mi><mo>,</mo><mi>n</mi><mo stretchy="false">)</mo></mrow></math> with
<math id="S0.I2.i2.I1.i2.p1.m3" class="ltx_Math" alttext="\bar{B}_{m}\subset B_{n}" display="inline"><mrow><msub><mover accent="true"><mi>B</mi><mo>¯</mo></mover><mi>m</mi></msub><mo>⊂</mo><msub><mi>B</mi><mi>n</mi></msub></mrow></math>, use Urysohn (X is normal by Thm 32.1) to get <math id="S0.I2.i2.I1.i2.p1.m4" class="ltx_Math" alttext="g_{m,n}" display="inline"><msub><mi>g</mi><mrow><mi>m</mi><mo>,</mo><mi>n</mi></mrow></msub></math>
with <math id="S0.I2.i2.I1.i2.p1.m5" class="ltx_Math" alttext="g_{m,n}(\bar{B}_{m})=\{1\}" display="inline"><mrow><mrow><msub><mi>g</mi><mrow><mi>m</mi><mo>,</mo><mi>n</mi></mrow></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mover accent="true"><mi>B</mi><mo>¯</mo></mover><mi>m</mi></msub><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo stretchy="false">}</mo></mrow></mrow></math>, <math id="S0.I2.i2.I1.i2.p1.m6" class="ltx_Math" alttext="g_{m,n}(X-B_{n})=\{0\}" display="inline"><mrow><mrow><msub><mi>g</mi><mrow><mi>m</mi><mo>,</mo><mi>n</mi></mrow></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>X</mi><mo>−</mo><msub><mi>B</mi><mi>n</mi></msub></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></math>. Reindex as <math id="S0.I2.i2.I1.i2.p1.m7" class="ltx_Math" alttext="\{f_{k}\}" display="inline"><mrow><mo stretchy="false">{</mo><msub><mi>f</mi><mi>k</mi></msub><mo stretchy="false">}</mo></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i2.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(3)</span> 
<div id="S0.I2.i2.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Claim 2:</em> <math id="S0.I2.i2.I1.i3.p1.m1" class="ltx_Math" alttext="F(x)=(f_{1}(x),f_{2}(x),\dots)" display="inline"><mrow><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><msub><mi>f</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>,</mo><mrow><msub><mi>f</mi><mn>2</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>,</mo><mi mathvariant="normal">…</mi><mo stretchy="false">)</mo></mrow></mrow></math> is an embedding <math id="S0.I2.i2.I1.i3.p1.m2" class="ltx_Math" alttext="X\to\mathbb{R}^{\omega}" display="inline"><mrow><mi>X</mi><mo stretchy="false">→</mo><msup><mi>ℝ</mi><mi>ω</mi></msup></mrow></math>.
Continuous (components are); injective (separate <math id="S0.I2.i2.I1.i3.p1.m3" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> from <math id="S0.I2.i2.I1.i3.p1.m4" class="ltx_Math" alttext="y" display="inline"><mi>y</mi></math> using <math id="S0.I2.i2.I1.i3.p1.m5" class="ltx_Math" alttext="U=X-\{y\}" display="inline"><mrow><mi>U</mi><mo>=</mo><mrow><mi>X</mi><mo>−</mo><mrow><mo stretchy="false">{</mo><mi>y</mi><mo stretchy="false">}</mo></mrow></mrow></mrow></math>).</p>
</div>
</li>
<li id="S0.I2.i2.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(4)</span> 
<div id="S0.I2.i2.I1.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Claim 3: <math id="S0.I2.i2.I1.i4.p1.m1" class="ltx_Math" alttext="F" display="inline"><mi>F</mi></math> is open onto its image <math id="S0.I2.i2.I1.i4.p1.m2" class="ltx_Math" alttext="Z" display="inline"><mi>Z</mi></math>.</em> Given <math id="S0.I2.i2.I1.i4.p1.m3" class="ltx_Math" alttext="q=F(p)\in F(U)" display="inline"><mrow><mi>q</mi><mo>=</mo><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>p</mi><mo stretchy="false">)</mo></mrow></mrow><mo>∈</mo><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>, choose <math id="S0.I2.i2.I1.i4.p1.m4" class="ltx_Math" alttext="k" display="inline"><mi>k</mi></math> with
<math id="S0.I2.i2.I1.i4.p1.m5" class="ltx_Math" alttext="f_{k}(p)=1" display="inline"><mrow><mrow><msub><mi>f</mi><mi>k</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>p</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mn>1</mn></mrow></math>, <math id="S0.I2.i2.I1.i4.p1.m6" class="ltx_Math" alttext="f_{k}(X-U)=\{0\}" display="inline"><mrow><mrow><msub><mi>f</mi><mi>k</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>X</mi><mo>−</mo><mi>U</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></math>, and set <math id="S0.I2.i2.I1.i4.p1.m7" class="ltx_Math" alttext="W=Z\cap\pi_{k}^{-1}(0,\infty)" display="inline"><mrow><mi>W</mi><mo>=</mo><mrow><mi>Z</mi><mo>∩</mo><mrow><msubsup><mi>π</mi><mi>k</mi><mrow><mo>−</mo><mn>1</mn></mrow></msubsup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mi mathvariant="normal">∞</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>.
Then <math id="S0.I2.i2.I1.i4.p1.m8" class="ltx_Math" alttext="q\in W\subset F(U)" display="inline"><mrow><mi>q</mi><mo>∈</mo><mi>W</mi><mo>⊂</mo><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.</p>
</div>
</li>
</ol>
</div>
<div id="S0.I2.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Regularity is used exactly once — to produce <math id="S0.I2.i2.p2.m1" class="ltx_Math" alttext="p\in B_{m}\subset\bar{B}_{m}\subset B_{n}" display="inline"><mrow><mi mathcolor="#737373">p</mi><mo mathcolor="#737373">∈</mo><msub><mi mathcolor="#737373">B</mi><mi mathcolor="#737373">m</mi></msub><mo mathcolor="#737373">⊂</mo><msub><mover accent="true"><mi mathcolor="#737373">B</mi><mo mathcolor="#737373">¯</mo></mover><mi mathcolor="#737373">m</mi></msub><mo mathcolor="#737373">⊂</mo><msub><mi mathcolor="#737373">B</mi><mi mathcolor="#737373">n</mi></msub></mrow></math>,
which is what makes the pair <math id="S0.I2.i2.p2.m2" class="ltx_Math" alttext="(m,n)" display="inline"><mrow><mo mathcolor="#737373" stretchy="false">(</mo><mi mathcolor="#737373">m</mi><mo mathcolor="#737373">,</mo><mi mathcolor="#737373">n</mi><mo mathcolor="#737373" stretchy="false">)</mo></mrow></math> available.</span></span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S0.SS3" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.3  (§35–§36) Tietze extension; manifolds</h2>

<div id="S0.SS3.p1" class="ltx_para ltx_noindent">
<ul id="S0.I3" class="ltx_itemize">
<li id="S0.I3.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I3.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Tietze.)</span> <math id="S0.I3.i1.p1.m2" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> closed in a normal <math id="S0.I3.i1.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>. Every map <math id="S0.I3.i1.p1.m4" class="ltx_Math" alttext="A\to[0,1]" display="inline"><mrow><mi>A</mi><mo stretchy="false">→</mo><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></mrow></math>
(resp. <math id="S0.I3.i1.p1.m5" class="ltx_Math" alttext="A\to\mathbb{R}" display="inline"><mrow><mi>A</mi><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></math>) extends to a map <math id="S0.I3.i1.p1.m6" class="ltx_Math" alttext="X\to[0,1]" display="inline"><mrow><mi>X</mi><mo stretchy="false">→</mo><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></mrow></math> (resp. <math id="S0.I3.i1.p1.m7" class="ltx_Math" alttext="X\to\mathbb{R}" display="inline"><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></math>). <span class="ltx_text" style="font-size:80%;color:#737373;">[Mk §35]</span></p>
</div>
</li>
<li id="S0.I3.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I3.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> An <em class="ltx_emph ltx_font_italic"><math id="S0.I3.i2.p1.m2" class="ltx_Math" alttext="m" display="inline"><mi>m</mi></math>-manifold</em> is a second-countable Hausdorff space in which every point
has a neighborhood homeomorphic to an open subset of <math id="S0.I3.i2.p1.m3" class="ltx_Math" alttext="\mathbb{R}^{m}" display="inline"><msup><mi>ℝ</mi><mi>m</mi></msup></math>
(equivalently, to <math id="S0.I3.i2.p1.m4" class="ltx_Math" alttext="\mathbb{R}^{m}" display="inline"><msup><mi>ℝ</mi><mi>m</mi></msup></math> itself).</p>
</div>
</li>
<li id="S0.I3.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> <math id="S0.I3.i3.p1.m1" class="ltx_Math" alttext="m=0" display="inline"><mrow><mi>m</mi><mo>=</mo><mn>0</mn></mrow></math>: discrete countable set. <math id="S0.I3.i3.p1.m2" class="ltx_Math" alttext="m=1" display="inline"><mrow><mi>m</mi><mo>=</mo><mn>1</mn></mrow></math>: <em class="ltx_emph ltx_font_italic">curve</em>. <math id="S0.I3.i3.p1.m3" class="ltx_Math" alttext="m=2" display="inline"><mrow><mi>m</mi><mo>=</mo><mn>2</mn></mrow></math>: <em class="ltx_emph ltx_font_italic">surface</em>.</p>
</div>
</li>
<li id="S0.I3.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> A compact <math id="S0.I3.i4.p1.m1" class="ltx_Math" alttext="m" display="inline"><mi>m</mi></math>-manifold embeds in <math id="S0.I3.i4.p1.m2" class="ltx_Math" alttext="\mathbb{R}^{n}" display="inline"><msup><mi>ℝ</mi><mi>n</mi></msup></math> for some <math id="S0.I3.i4.p1.m3" class="ltx_Math" alttext="n" display="inline"><mi>n</mi></math>. <span class="ltx_text" style="font-size:80%;color:#737373;">[Mk §36]</span></p>
</div>
</li>
</ul>
</div>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:59:29 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
