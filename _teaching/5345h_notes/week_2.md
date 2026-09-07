---
layout: archive
title: "MATH 5345H --- Week 2: Cartesian products; finite, countable, and uncountable sets"
permalink: /teaching/5345h_notes/week_2
author_profile: false
render_with_liquid: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S0.SS1" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.1  (§5) Cartesian products</h2>

<div id="S0.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S0.I1" class="ltx_itemize">
<li id="S0.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">Indexing function</em> for <math id="S0.I1.i1.p1.m1" class="ltx_Math" alttext="\mathcal{A}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒜</mi></math>: a surjection <math id="S0.I1.i1.p1.m2" class="ltx_Math" alttext="f\colon J\to\mathcal{A}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>J</mi><mo stretchy="false">→</mo><mi class="ltx_font_mathcaligraphic">𝒜</mi></mrow></mrow></math>;
write <math id="S0.I1.i1.p1.m3" class="ltx_Math" alttext="A_{\alpha}=f(\alpha)" display="inline"><mrow><msub><mi>A</mi><mi>α</mi></msub><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>α</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>, family <math id="S0.I1.i1.p1.m4" class="ltx_Math" alttext="\{A_{\alpha}\}_{\alpha\in J}" display="inline"><msub><mrow><mo stretchy="false">{</mo><msub><mi>A</mi><mi>α</mi></msub><mo stretchy="false">}</mo></mrow><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></msub></math>.
Not assumed injective: <math id="S0.I1.i1.p1.m5" class="ltx_Math" alttext="A_{\alpha}=A_{\beta}" display="inline"><mrow><msub><mi>A</mi><mi>α</mi></msub><mo>=</mo><msub><mi>A</mi><mi>β</mi></msub></mrow></math> is allowed for <math id="S0.I1.i1.p1.m6" class="ltx_Math" alttext="\alpha\neq\beta" display="inline"><mrow><mi>α</mi><mo>≠</mo><mi>β</mi></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> <math id="S0.I1.i2.p1.m1" class="ltx_Math" alttext="\bigcap_{\alpha\in J}A_{\alpha}" display="inline"><mrow><msub><mo>⋂</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></msub><msub><mi>A</mi><mi>α</mi></msub></mrow></math>, <math id="S0.I1.i2.p1.m2" class="ltx_Math" alttext="\bigcup_{\alpha\in J}A_{\alpha}" display="inline"><mrow><msub><mo>⋃</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></msub><msub><mi>A</mi><mi>α</mi></msub></mrow></math>;
finite case <math id="S0.I1.i2.p1.m3" class="ltx_Math" alttext="A_{1}\cap\cdots\cap A_{n}" display="inline"><mrow><msub><mi>A</mi><mn>1</mn></msub><mo>∩</mo><mi mathvariant="normal">⋯</mi><mo>∩</mo><msub><mi>A</mi><mi>n</mi></msub></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i3.p1.m1" class="ltx_Math" alttext="n" display="inline"><mi>n</mi></math>-tuple <math id="S0.I1.i3.p1.m2" class="ltx_Math" alttext="=" display="inline"><mo>=</mo></math> function <math id="S0.I1.i3.p1.m3" class="ltx_Math" alttext="x\colon\{1,\dots,n\}\to X" display="inline"><mrow><mi>x</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">→</mo><mi>X</mi></mrow></mrow></math>, written <math id="S0.I1.i3.p1.m4" class="ltx_Math" alttext="(x_{1},\dots,x_{n})" display="inline"><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mn>1</mn></msub><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><msub><mi>x</mi><mi>n</mi></msub><mo stretchy="false">)</mo></mrow></math>;
<math id="S0.I1.i3.p1.m5" class="ltx_Math" alttext="\prod_{i=1}^{n}A_{i}" display="inline"><mrow><msubsup><mo>∏</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></msubsup><msub><mi>A</mi><mi>i</mi></msub></mrow></math>;   <math id="S0.I1.i3.p1.m6" class="ltx_Math" alttext="X^{n}" display="inline"><msup><mi>X</mi><mi>n</mi></msup></math>.</p>
</div>
</li>
<li id="S0.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> sequence <math id="S0.I1.i4.p1.m1" class="ltx_Math" alttext="=" display="inline"><mo>=</mo></math> function <math id="S0.I1.i4.p1.m2" class="ltx_Math" alttext="x\colon\mathbb{N}\to X" display="inline"><mrow><mi>x</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>ℕ</mi><mo stretchy="false">→</mo><mi>X</mi></mrow></mrow></math>, written <math id="S0.I1.i4.p1.m3" class="ltx_Math" alttext="(x_{i})_{i=1}^{\infty}" display="inline"><msubsup><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mi>i</mi></msub><mo stretchy="false">)</mo></mrow><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mi mathvariant="normal">∞</mi></msubsup></math>
(also called an <em class="ltx_emph ltx_font_italic"><math id="S0.I1.i4.p1.m4" class="ltx_Math" alttext="\omega" display="inline"><mi>ω</mi></math>-tuple</em>);
 <math id="S0.I1.i4.p1.m5" class="ltx_Math" alttext="\prod_{i=1}^{\infty}A_{i}=A_{1}\times A_{2}\times\cdots" display="inline"><mrow><mrow><msubsup><mo>∏</mo><mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow><mi mathvariant="normal">∞</mi></msubsup><msub><mi>A</mi><mi>i</mi></msub></mrow><mo>=</mo><mrow><msub><mi>A</mi><mn>1</mn></msub><mo lspace="0.222em" rspace="0.222em">×</mo><msub><mi>A</mi><mn>2</mn></msub><mo lspace="0.222em" rspace="0.222em">×</mo><mi mathvariant="normal">⋯</mi></mrow></mrow></math>;  <math id="S0.I1.i4.p1.m6" class="ltx_Math" alttext="X^{\omega}" display="inline"><msup><mi>X</mi><mi>ω</mi></msup></math>.</p>
</div>
</li>
<li id="S0.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> General product. <math id="S0.I1.i5.p1.m2" class="ltx_Math" alttext="J" display="inline"><mi>J</mi></math>-tuple <math id="S0.I1.i5.p1.m3" class="ltx_Math" alttext="=" display="inline"><mo>=</mo></math> function <math id="S0.I1.i5.p1.m4" class="ltx_Math" alttext="x\colon J\to X" display="inline"><mrow><mi>x</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>J</mi><mo stretchy="false">→</mo><mi>X</mi></mrow></mrow></math>, <math id="S0.I1.i5.p1.m5" class="ltx_Math" alttext="x_{\alpha}=x(\alpha)" display="inline"><mrow><msub><mi>x</mi><mi>α</mi></msub><mo>=</mo><mrow><mi>x</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>α</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.</p>
<table id="S0.Ex1" class="ltx_equation ltx_eqn_table">

<tbody><tr class="ltx_equation ltx_eqn_row ltx_align_baseline">
<td class="ltx_eqn_cell ltx_eqn_center_padleft"></td>
<td class="ltx_eqn_cell ltx_align_center"><math id="S0.Ex1.m1" class="ltx_math_unparsed" alttext="\prod_{\alpha\in J}A_{\alpha}=\Bigl{\{}\,x\colon J\to\bigcup_{\alpha\in J}A_{%
\alpha}\ \Bigm{|}\ x(\alpha)\in A_{\alpha}\ \forall\alpha\,\Bigr{\}},\qquad X^%
{J}=\prod_{\alpha\in J}X." display="block"><mrow><munder><mo movablelimits="false">∏</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></munder><msub><mi>A</mi><mi>α</mi></msub><mo>=</mo><mrow><mo maxsize="160%" minsize="160%" rspace="0.170em">{</mo><mi>x</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mi>J</mi><mo rspace="0.111em" stretchy="false">→</mo><munder><mo movablelimits="false">⋃</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></munder><msub><mi>A</mi><mi>α</mi></msub><mo lspace="0em" mathsize="160%" rspace="0.500em">|</mo><mi>x</mi><mrow><mo stretchy="false">(</mo><mi>α</mi><mo stretchy="false">)</mo></mrow><mo>∈</mo><msub><mi>A</mi><mi>α</mi></msub><mo lspace="0.167em" rspace="0.167em">∀</mo><mi>α</mi><mo lspace="0.170em" maxsize="160%" minsize="160%">}</mo></mrow><mo rspace="2.167em">,</mo><msup><mi>X</mi><mi>J</mi></msup><mo rspace="0.111em">=</mo><munder><mo movablelimits="false">∏</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></munder><mi>X</mi><mo lspace="0em">.</mo></mrow></math></td>
<td class="ltx_eqn_cell ltx_eqn_center_padright"></td>
</tr></tbody>
</table>
</div>
<div id="S0.I1.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Stress: a point of an infinite product is a <em class="ltx_emph ltx_font_upright">function</em>. Everything about product
topologies later reads more easily from this description.</span></span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S0.SS2" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.2  (§6) Finite sets</h2>

<div id="S0.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S0.I2" class="ltx_itemize">
<li id="S0.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> Section of <math id="S0.I2.i1.p1.m1" class="ltx_Math" alttext="\mathbb{N}" display="inline"><mi>ℕ</mi></math>: <math id="S0.I2.i1.p1.m2" class="ltx_Math" alttext="\{1,2,\dots,n\}" display="inline"><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mn>2</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow></math>; for <math id="S0.I2.i1.p1.m3" class="ltx_Math" alttext="n=0" display="inline"><mrow><mi>n</mi><mo>=</mo><mn>0</mn></mrow></math> this is <math id="S0.I2.i1.p1.m4" class="ltx_Math" alttext="\emptyset" display="inline"><mi mathvariant="normal">∅</mi></math>.</p>
</div>
</li>
<li id="S0.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I2.i2.p1.m1" class="ltx_Math" alttext="\{1,\dots,m\}\hookrightarrow\{1,\dots,n\}" display="inline"><mrow><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>m</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">↪</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow></mrow></math> injective <math id="S0.I2.i2.p1.m2" class="ltx_Math" alttext="\Rightarrow m\leq n" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mi>m</mi><mo>≤</mo><mi>n</mi></mrow></math>.</p>
</div>
<div id="S0.I2.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Induction on <math id="S0.I2.i2.p2.m1" class="ltx_Math" alttext="n" display="inline"><mi mathcolor="#3D3D3D">n</mi></math>: delete <math id="S0.I2.i2.p2.m2" class="ltx_Math" alttext="f(m)=k" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">m</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mi mathcolor="#3D3D3D">k</mi></mrow></math>, use a bijection <math id="S0.I2.i2.p2.m3" class="ltx_Math" alttext="\{1,\dots,n\}-\{k\}\to\{1,\dots,n-1\}" display="inline"><mrow><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D" mathvariant="normal">…</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow><mo mathcolor="#3D3D3D">−</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">k</mi><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow><mo mathcolor="#3D3D3D" stretchy="false">→</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D" mathvariant="normal">…</mi><mo mathcolor="#3D3D3D">,</mo><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> Hence there is <em class="ltx_emph ltx_font_italic">no</em> injective <math id="S0.I2.i3.p1.m1" class="ltx_Math" alttext="\{1,\dots,m\}\to\{1,\dots,n\}" display="inline"><mrow><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>m</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">→</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow></mrow></math> when <math id="S0.I2.i3.p1.m2" class="ltx_Math" alttext="m&gt;n" display="inline"><mrow><mi>m</mi><mo>&gt;</mo><mi>n</mi></mrow></math>.
(Pigeonhole.)</p>
</div>
</li>
<li id="S0.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Prop.</span> A bijection <math id="S0.I2.i4.p1.m1" class="ltx_Math" alttext="\{1,\dots,m\}\to\{1,\dots,n\}" display="inline"><mrow><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>m</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">→</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow></mrow></math> forces <math id="S0.I2.i4.p1.m2" class="ltx_Math" alttext="m=n" display="inline"><mrow><mi>m</mi><mo>=</mo><mi>n</mi></mrow></math>.</p>
</div>
<div id="S0.I2.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Apply the lemma to <math id="S0.I2.i4.p2.m1" class="ltx_Math" alttext="f" display="inline"><mi mathcolor="#3D3D3D">f</mi></math> and to <math id="S0.I2.i4.p2.m2" class="ltx_Math" alttext="f^{-1}" display="inline"><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup></math>.</span></span></p>
</div>
</li>
<li id="S0.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> Hence there is <em class="ltx_emph ltx_font_italic">no</em> bijection <math id="S0.I2.i5.p1.m1" class="ltx_Math" alttext="\{1,\dots,m\}\to\{1,\dots,n\}" display="inline"><mrow><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>m</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">→</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow></mrow></math> when <math id="S0.I2.i5.p1.m2" class="ltx_Math" alttext="m\neq n" display="inline"><mrow><mi>m</mi><mo>≠</mo><mi>n</mi></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I2.i6.p1.m1" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> is <em class="ltx_emph ltx_font_italic">finite of cardinality <math id="S0.I2.i6.p1.m2" class="ltx_Math" alttext="n" display="inline"><mi>n</mi></math></em> if there is a bijection <math id="S0.I2.i6.p1.m3" class="ltx_Math" alttext="A\to\{1,\dots,n\}" display="inline"><mrow><mi>A</mi><mo stretchy="false">→</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow></mrow></math>.
Cardinality is well defined.
<span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I2.i6.p1.m4" class="ltx_Math" alttext="\emptyset" display="inline"><mi mathvariant="normal">∅</mi></math> has cardinality <math id="S0.I2.i6.p1.m5" class="ltx_Math" alttext="0" display="inline"><mn>0</mn></math>; singletons have cardinality <math id="S0.I2.i6.p1.m6" class="ltx_Math" alttext="1" display="inline"><mn>1</mn></math>.</p>
</div>
</li>
<li id="S0.I2.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I2.i7.p1.m1" class="ltx_Math" alttext="A\subset\{1,\dots,n\}" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow></mrow></math> is finite, of cardinality <math id="S0.I2.i7.p1.m2" class="ltx_Math" alttext="\leq n" display="inline"><mrow><mi></mi><mo>≤</mo><mi>n</mi></mrow></math>;
if <math id="S0.I2.i7.p1.m3" class="ltx_Math" alttext="A\subsetneq\{1,\dots,n\}" display="inline"><mrow><mi>A</mi><mo>⊊</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow></mrow></math> the cardinality is <math id="S0.I2.i7.p1.m4" class="ltx_Math" alttext="&lt;n" display="inline"><mrow><mi></mi><mo>&lt;</mo><mi>n</mi></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i8.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i8.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> A finite set admits no bijection with a proper subset of itself.</p>
</div>
</li>
<li id="S0.I2.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> <math id="S0.I2.i9.p1.m1" class="ltx_Math" alttext="\mathbb{N}" display="inline"><mi>ℕ</mi></math> is not finite: <math id="S0.I2.i9.p1.m2" class="ltx_Math" alttext="f(x)=x+1" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>x</mi><mo>+</mo><mn>1</mn></mrow></mrow></math> is a bijection of <math id="S0.I2.i9.p1.m3" class="ltx_Math" alttext="\mathbb{N}" display="inline"><mi>ℕ</mi></math> with the proper subset
<math id="S0.I2.i9.p1.m4" class="ltx_Math" alttext="\mathbb{N}-\{1\}" display="inline"><mrow><mi>ℕ</mi><mo>−</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> Any subset <math id="S0.I2.i10.p1.m1" class="ltx_Math" alttext="B" display="inline"><mi>B</mi></math> of a finite set <math id="S0.I2.i10.p1.m2" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> is finite; if <math id="S0.I2.i10.p1.m3" class="ltx_Math" alttext="B\subsetneq A" display="inline"><mrow><mi>B</mi><mo>⊊</mo><mi>A</mi></mrow></math> then
<math id="S0.I2.i10.p1.m4" class="ltx_Math" alttext="\mathrm{card}(B)&lt;\mathrm{card}(A)" display="inline"><mrow><mrow><mi>card</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>B</mi><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mrow><mi>card</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i11.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Prop.</span> TFAE: (1) <math id="S0.I2.i11.p1.m1" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> finite; (2) some <math id="S0.I2.i11.p1.m2" class="ltx_Math" alttext="\{1,\dots,n\}\twoheadrightarrow A" display="inline"><mrow><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">↠</mo><mi>A</mi></mrow></math>;
(3) some <math id="S0.I2.i11.p1.m3" class="ltx_Math" alttext="A\hookrightarrow\{1,\dots,n\}" display="inline"><mrow><mi>A</mi><mo stretchy="false">↪</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mi>n</mi><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
<div id="S0.I2.i11.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I2.i11.p2.m1" class="ltx_Math" alttext="(2)\Rightarrow(3)" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">2</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">3</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math>: send <math id="S0.I2.i11.p2.m2" class="ltx_Math" alttext="x" display="inline"><mi mathcolor="#3D3D3D">x</mi></math> to <math id="S0.I2.i11.p2.m3" class="ltx_Math" alttext="\min g^{-1}(x)" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">min</mi><mo lspace="0.167em">⁡</mo><msup><mi mathcolor="#3D3D3D">g</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup></mrow><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I2.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i12.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Prop.</span> Finite unions and finite products of finite sets are finite.</p>
</div>
</li>
</ul>
</div>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:58:53 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
