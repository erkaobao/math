---
layout: archive
title: "MATH 5345H --- Week 5: Continuity, homeomorphisms, and the pasting lemma"
permalink: /teaching/5345h_notes/week_5
author_profile: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S0.SS1" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.1  (§18) Continuous functions</h2>

<div id="S0.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S0.I1" class="ltx_itemize">
<li id="S0.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i1.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i1.p1.m2" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> is <em class="ltx_emph ltx_font_italic">continuous</em> if <math id="S0.I1.i1.p1.m3" class="ltx_Math" alttext="f^{-1}(V)" display="inline"><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>V</mi><mo stretchy="false">)</mo></mrow></mrow></math> is open in <math id="S0.I1.i1.p1.m4" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> for every
open <math id="S0.I1.i1.p1.m5" class="ltx_Math" alttext="V\subset Y" display="inline"><mrow><mi>V</mi><mo>⊂</mo><mi>Y</mi></mrow></math>. A continuous function is called a <em class="ltx_emph ltx_font_italic">map</em>.</p>
</div>
<div id="S0.I1.i1.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Refer back to §2: preimages respect <math id="S0.I1.i1.p2.m1" class="ltx_Math" alttext="\cup" display="inline"><mo mathcolor="#737373">∪</mo></math>, <math id="S0.I1.i1.p2.m2" class="ltx_Math" alttext="\cap" display="inline"><mo mathcolor="#737373">∩</mo></math>, <math id="S0.I1.i1.p2.m3" class="ltx_Math" alttext="-" display="inline"><mo mathcolor="#737373">−</mo></math>. Images do not. That is the
entire reason the definition takes this form.</span></span></span></p>
</div>
</li>
<li id="S0.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Composites of maps are maps.</p>
</div>
<div id="S0.I1.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I1.i2.p2.m1" class="ltx_Math" alttext="(g\circ f)^{-1}(W)=f^{-1}(g^{-1}(W))" display="inline"><mrow><mrow><msup><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">g</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">∘</mo><mi mathcolor="#3D3D3D">f</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">W</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><msup><mi mathcolor="#3D3D3D">g</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">W</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i3.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> It is enough to test a basis: <math id="S0.I1.i3.p1.m2" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> continuous <math id="S0.I1.i3.p1.m3" class="ltx_Math" alttext="\Leftrightarrow f^{-1}(B)" display="inline"><mrow><mi></mi><mo stretchy="false">⇔</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>B</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> open for all
<math id="S0.I1.i3.p1.m4" class="ltx_Math" alttext="B\in\mathcal{B}" display="inline"><mrow><mi>B</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi></mrow></math>. And enough to test a subbasis: <math id="S0.I1.i3.p1.m5" class="ltx_Math" alttext="\Leftrightarrow f^{-1}(S)" display="inline"><mrow><mi></mi><mo stretchy="false">⇔</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> open for all <math id="S0.I1.i3.p1.m6" class="ltx_Math" alttext="S\in\mathcal{S}" display="inline"><mrow><mi>S</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒮</mi></mrow></math>.</p>
</div>
<div id="S0.I1.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Because <math id="S0.I1.i3.p2.m1" class="ltx_Math" alttext="f^{-1}" display="inline"><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup></math> commutes with unions (basis) and with finite intersections (subbasis).</span></span></p>
</div>
</li>
<li id="S0.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Metric spaces: continuity <math id="S0.I1.i4.p1.m1" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> for all <math id="S0.I1.i4.p1.m2" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> and <math id="S0.I1.i4.p1.m3" class="ltx_Math" alttext="\varepsilon&gt;0" display="inline"><mrow><mi>ε</mi><mo>&gt;</mo><mn>0</mn></mrow></math> there is <math id="S0.I1.i4.p1.m4" class="ltx_Math" alttext="\delta&gt;0" display="inline"><mrow><mi>δ</mi><mo>&gt;</mo><mn>0</mn></mrow></math> with
<math id="S0.I1.i4.p1.m5" class="ltx_Math" alttext="d(x,y)&lt;\delta\Rightarrow d^{\prime}(f(x),f(y))&lt;\varepsilon" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mi>δ</mi><mo stretchy="false">⇒</mo><mrow><msup><mi>d</mi><mo>′</mo></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>,</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mi>ε</mi></mrow></math>. The <math id="S0.I1.i4.p1.m6" class="ltx_Math" alttext="\varepsilon" display="inline"><mi>ε</mi></math>–<math id="S0.I1.i4.p1.m7" class="ltx_Math" alttext="\delta" display="inline"><mi>δ</mi></math> definition, recovered.</p>
</div>
</li>
<li id="S0.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i5.p1.m2" class="ltx_Math" alttext="\operatorname{id}\colon\mathbb{R}\to\mathbb{R}_{\ell}" display="inline"><mrow><mi>id</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>ℝ</mi><mo stretchy="false">→</mo><msub><mi>ℝ</mi><mi mathvariant="normal">ℓ</mi></msub></mrow></mrow></math> is <em class="ltx_emph ltx_font_italic">not</em> continuous (<math id="S0.I1.i5.p1.m3" class="ltx_Math" alttext="[a,b)" display="inline"><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></math> is not open in <math id="S0.I1.i5.p1.m4" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>);
<math id="S0.I1.i5.p1.m5" class="ltx_Math" alttext="\operatorname{id}\colon\mathbb{R}_{\ell}\to\mathbb{R}" display="inline"><mrow><mi>id</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msub><mi>ℝ</mi><mi mathvariant="normal">ℓ</mi></msub><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></mrow></math> <em class="ltx_emph ltx_font_italic">is</em> continuous.</p>
</div>
</li>
<li id="S0.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i6.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is <em class="ltx_emph ltx_font_italic">continuous at <math id="S0.I1.i6.p1.m2" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math></em> if for each neighborhood <math id="S0.I1.i6.p1.m3" class="ltx_Math" alttext="V" display="inline"><mi>V</mi></math> of <math id="S0.I1.i6.p1.m4" class="ltx_Math" alttext="f(x)" display="inline"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></math> there is a
neighborhood <math id="S0.I1.i6.p1.m5" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math> of <math id="S0.I1.i6.p1.m6" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> with <math id="S0.I1.i6.p1.m7" class="ltx_Math" alttext="f(U)\subset V" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mi>V</mi></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i7.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i7.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> continuous <math id="S0.I1.i7.p1.m2" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> <math id="S0.I1.i7.p1.m3" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> continuous at every <math id="S0.I1.i7.p1.m4" class="ltx_Math" alttext="x\in X" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>X</mi></mrow></math>.</p>
</div>
<div id="S0.I1.i7.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I1.i7.p2.m1" class="ltx_Math" alttext="\Leftarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇐</mo></math> is the gluing trick again: <math id="S0.I1.i7.p2.m2" class="ltx_Math" alttext="f^{-1}(V)=\bigcup_{x\in f^{-1}(V)}U_{x}" display="inline"><mrow><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" rspace="0.111em">=</mo><mrow><msub><mo mathcolor="#3D3D3D">⋃</mo><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">∈</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></msub><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">x</mi></msub></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i8.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i8.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> TFAE:</p>
<ol id="S0.I1.i8.I1" class="ltx_enumerate">
<li id="S0.I1.i8.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(1)</span> 
<div id="S0.I1.i8.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i8.I1.i1.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is continuous;</p>
</div>
</li>
<li id="S0.I1.i8.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(2)</span> 
<div id="S0.I1.i8.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i8.I1.i2.p1.m1" class="ltx_Math" alttext="f(\bar{A})\subset\overline{f(A)}" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mover accent="true"><mi>A</mi><mo>¯</mo></mover><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mover accent="true"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo>¯</mo></mover></mrow></math> for every <math id="S0.I1.i8.I1.i2.p1.m2" class="ltx_Math" alttext="A\subset X" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>X</mi></mrow></math>;</p>
</div>
</li>
<li id="S0.I1.i8.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(3)</span> 
<div id="S0.I1.i8.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i8.I1.i3.p1.m1" class="ltx_Math" alttext="f^{-1}(B)" display="inline"><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>B</mi><mo stretchy="false">)</mo></mrow></mrow></math> is closed for every closed <math id="S0.I1.i8.I1.i3.p1.m2" class="ltx_Math" alttext="B\subset Y" display="inline"><mrow><mi>B</mi><mo>⊂</mo><mi>Y</mi></mrow></math>.</p>
</div>
</li>
</ol>
</div>
<div id="S0.I1.i8.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I1.i8.p2.m1" class="ltx_Math" alttext="(1)\Rightarrow(2)" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">2</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> via the neighborhood criterion for closure;
<math id="S0.I1.i8.p2.m2" class="ltx_Math" alttext="(2)\Rightarrow(3)" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">2</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">3</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> apply to <math id="S0.I1.i8.p2.m3" class="ltx_Math" alttext="A=f^{-1}(B)" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">B</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>;
<math id="S0.I1.i8.p2.m4" class="ltx_Math" alttext="(3)\Rightarrow(1)" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">3</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> complement.</span></span></p>
</div>
</li>
<li id="S0.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i9.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i9.p1.m2" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> is a <em class="ltx_emph ltx_font_italic">homeomorphism</em> if it is bijective and both <math id="S0.I1.i9.p1.m3" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> and
<math id="S0.I1.i9.p1.m4" class="ltx_Math" alttext="f^{-1}" display="inline"><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup></math> are continuous. Then <math id="S0.I1.i9.p1.m5" class="ltx_Math" alttext="X\cong Y" display="inline"><mrow><mi>X</mi><mo>≅</mo><mi>Y</mi></mrow></math>, <em class="ltx_emph ltx_font_italic">topologically equivalent</em>.</p>
</div>
</li>
<li id="S0.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I1.i10.p1.m1" class="ltx_Math" alttext="\cong" display="inline"><mo>≅</mo></math> is an equivalence relation (identity, inverse, composite).</p>
</div>
</li>
<li id="S0.I1.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i11.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> For <math id="S0.I1.i11.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> bijective, TFAE: <math id="S0.I1.i11.p1.m2" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> homeomorphism;
<math id="S0.I1.i11.p1.m3" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math> open in <math id="S0.I1.i11.p1.m4" class="ltx_Math" alttext="X\Leftrightarrow f(U)" display="inline"><mrow><mi>X</mi><mo stretchy="false">⇔</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> open in <math id="S0.I1.i11.p1.m5" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math>;
<math id="S0.I1.i11.p1.m6" class="ltx_Math" alttext="V" display="inline"><mi>V</mi></math> open in <math id="S0.I1.i11.p1.m7" class="ltx_Math" alttext="Y\Leftrightarrow f^{-1}(V)" display="inline"><mrow><mi>Y</mi><mo stretchy="false">⇔</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>V</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> open in <math id="S0.I1.i11.p1.m8" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>.</p>
</div>
<div id="S0.I1.i11.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">So a homeomorphism is a bijection <math id="S0.I1.i11.p2.m1" class="ltx_Math" alttext="\mathcal{T}_{X}\to\mathcal{T}_{Y}" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic" mathcolor="#737373">𝒯</mi><mi mathcolor="#737373">X</mi></msub><mo mathcolor="#737373" stretchy="false">→</mo><msub><mi class="ltx_font_mathcaligraphic" mathcolor="#737373">𝒯</mi><mi mathcolor="#737373">Y</mi></msub></mrow></math> of the topologies, not just of the points.</span></span></span></p>
</div>
</li>
<li id="S0.I1.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i12.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">topological property</em> is one expressible in terms of points and open sets;
such properties are preserved by homeomorphism.
E.g. finiteness, discreteness, Hausdorff, and later compactness and connectedness.</p>
</div>
</li>
<li id="S0.I1.i13" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i13.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i13.p1.m1" class="ltx_Math" alttext="(0,1)\cong(a,b)" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow><mo>≅</mo><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></mrow></math> via <math id="S0.I1.i13.p1.m2" class="ltx_Math" alttext="f(x)=(1-x)a+xb" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mrow><mo stretchy="false">(</mo><mrow><mn>1</mn><mo>−</mo><mi>x</mi></mrow><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mi>a</mi></mrow><mo>+</mo><mrow><mi>x</mi><mo>⁢</mo><mi>b</mi></mrow></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i14" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i14.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i14.p1.m1" class="ltx_Math" alttext="(-1,1)\cong\mathbb{R}" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mrow><mo>−</mo><mn>1</mn></mrow><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow><mo>≅</mo><mi>ℝ</mi></mrow></math> via <math id="S0.I1.i14.p1.m2" class="ltx_Math" alttext="f(x)=x/(1-x^{2})" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>x</mi><mo>/</mo><mrow><mo stretchy="false">(</mo><mrow><mn>1</mn><mo>−</mo><msup><mi>x</mi><mn>2</mn></msup></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>,  
<math id="S0.I1.i14.p1.m3" class="ltx_Math" alttext="f^{-1}(y)=2y/\bigl{(}1+\sqrt{1+4y^{2}}\bigr{)}" display="inline"><mrow><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mn>2</mn><mo>⁢</mo><mi>y</mi></mrow><mo>/</mo><mrow><mo maxsize="120%" minsize="120%">(</mo><mrow><mn>1</mn><mo>+</mo><msqrt><mrow><mn>1</mn><mo>+</mo><mrow><mn>4</mn><mo>⁢</mo><msup><mi>y</mi><mn>2</mn></msup></mrow></mrow></msqrt></mrow><mo maxsize="120%" minsize="120%">)</mo></mrow></mrow></mrow></math>. Hence every open interval <math id="S0.I1.i14.p1.m4" class="ltx_Math" alttext="\cong\mathbb{R}" display="inline"><mrow><mi></mi><mo>≅</mo><mi>ℝ</mi></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i15" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i15.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i15.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Caution.</span> <span class="ltx_text ltx_font_bold">Continuous bijection <math id="S0.I1.i15.p1.m2" class="ltx_Math" alttext="\neq" display="inline"><mo>≠</mo></math> homeomorphism.</span></p>
<ul id="S0.I1.i15.I1" class="ltx_itemize">
<li id="S0.I1.i15.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S0.I1.i15.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i15.I1.i1.p1.m1" class="ltx_Math" alttext="\operatorname{id}\colon\mathbb{R}_{\ell}\to\mathbb{R}" display="inline"><mrow><mi>id</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msub><mi>ℝ</mi><mi mathvariant="normal">ℓ</mi></msub><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i15.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S0.I1.i15.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i15.I1.i2.p1.m1" class="ltx_Math" alttext="f\colon[0,1)\to S^{1}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow><mo stretchy="false">→</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></mrow></math>, <math id="S0.I1.i15.I1.i2.p1.m2" class="ltx_Math" alttext="f(t)=(\cos 2\pi t,\sin 2\pi t)" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mrow><mn>2</mn><mo>⁢</mo><mi>π</mi><mo>⁢</mo><mi>t</mi></mrow></mrow><mo>,</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mrow><mn>2</mn><mo>⁢</mo><mi>π</mi><mo>⁢</mo><mi>t</mi></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></math>. Here <math id="S0.I1.i15.I1.i2.p1.m3" class="ltx_Math" alttext="U=[0,\tfrac{1}{2})" display="inline"><mrow><mi>U</mi><mo>=</mo><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mfrac><mn>1</mn><mn>2</mn></mfrac><mo stretchy="false">)</mo></mrow></mrow></math> is open in
<math id="S0.I1.i15.I1.i2.p1.m4" class="ltx_Math" alttext="[0,1)" display="inline"><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></math> but <math id="S0.I1.i15.I1.i2.p1.m5" class="ltx_Math" alttext="f(U)" display="inline"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow></math> is not open in <math id="S0.I1.i15.I1.i2.p1.m6" class="ltx_Math" alttext="S^{1}" display="inline"><msup><mi>S</mi><mn>1</mn></msup></math>: no neighborhood of <math id="S0.I1.i15.I1.i2.p1.m7" class="ltx_Math" alttext="(1,0)" display="inline"><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></math> lies inside it.</p>
</div>
</li>
</ul>
</div>
</li>
</ul>
</div>
<div id="S0.SS1.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Constructing maps.</span></p>
<ul id="S0.I2" class="ltx_itemize">
<li id="S0.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> The subspace topology on <math id="S0.I2.i1.p1.m1" class="ltx_Math" alttext="A\subset X" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>X</mi></mrow></math> is the <em class="ltx_emph ltx_font_italic">coarsest</em> making the inclusion
<math id="S0.I2.i1.p1.m2" class="ltx_Math" alttext="i\colon A\to X" display="inline"><mrow><mi>i</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>A</mi><mo stretchy="false">→</mo><mi>X</mi></mrow></mrow></math> continuous.</p>
</div>
</li>
<li id="S0.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> Restrictions <math id="S0.I2.i2.p1.m1" class="ltx_Math" alttext="f|A" display="inline"><mrow><mi>f</mi><mo fence="false">|</mo><mi>A</mi></mrow></math> of maps are maps. <span class="ltx_text ltx_font_bold">Lem.</span> Corestrictions <math id="S0.I2.i2.p1.m2" class="ltx_Math" alttext="X\to B" display="inline"><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>B</mi></mrow></math> (with <math id="S0.I2.i2.p1.m3" class="ltx_Math" alttext="f(X)\subset B" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mi>B</mi></mrow></math>) are maps.</p>
</div>
</li>
<li id="S0.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I2.i3.p1.m1" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> is an <em class="ltx_emph ltx_font_italic">embedding</em> if the corestriction <math id="S0.I2.i3.p1.m2" class="ltx_Math" alttext="X\to f(X)" display="inline"><mrow><mi>X</mi><mo stretchy="false">→</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> is a
homeomorphism onto the subspace <math id="S0.I2.i3.p1.m3" class="ltx_Math" alttext="f(X)" display="inline"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo stretchy="false">)</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I2.i4.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is an embedding <math id="S0.I2.i4.p1.m2" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> <math id="S0.I2.i4.p1.m3" class="ltx_Math" alttext="f=j\circ h" display="inline"><mrow><mi>f</mi><mo>=</mo><mrow><mi>j</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>h</mi></mrow></mrow></math> with <math id="S0.I2.i4.p1.m4" class="ltx_Math" alttext="h" display="inline"><mi>h</mi></math> a homeomorphism onto a subspace
and <math id="S0.I2.i4.p1.m5" class="ltx_Math" alttext="j" display="inline"><mi>j</mi></math> the inclusion. Embeddings are injective.</p>
</div>
</li>
<li id="S0.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I2.i5.p1.m1" class="ltx_Math" alttext="[0,1)\to\mathbb{R}^{2}" display="inline"><mrow><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow><mo stretchy="false">→</mo><msup><mi>ℝ</mi><mn>2</mn></msup></mrow></math>, <math id="S0.I2.i5.p1.m2" class="ltx_Math" alttext="t\mapsto(\cos 2\pi t,\sin 2\pi t)" display="inline"><mrow><mi>t</mi><mo stretchy="false">↦</mo><mrow><mo stretchy="false">(</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mrow><mn>2</mn><mo>⁢</mo><mi>π</mi><mo>⁢</mo><mi>t</mi></mrow></mrow><mo>,</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mrow><mn>2</mn><mo>⁢</mo><mi>π</mi><mo>⁢</mo><mi>t</mi></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></math>: injective and continuous,
<em class="ltx_emph ltx_font_italic">not</em> an embedding.</p>
</div>
</li>
<li id="S0.I2.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Maps to a one-point space are continuous; hence constant maps are continuous.</p>
</div>
</li>
<li id="S0.I2.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i7.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i7.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Pasting lemma.)</span></p>
<ul id="S0.I2.i7.I1" class="ltx_itemize">
<li id="S0.I2.i7.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S0.I2.i7.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i7.I1.i1.p1.m1" class="ltx_Math" alttext="X=\bigcup_{\alpha\in J}U_{\alpha}" display="inline"><mrow><mi>X</mi><mo rspace="0.111em">=</mo><mrow><msub><mo>⋃</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></msub><msub><mi>U</mi><mi>α</mi></msub></mrow></mrow></math> with all <math id="S0.I2.i7.I1.i1.p1.m2" class="ltx_Math" alttext="U_{\alpha}" display="inline"><msub><mi>U</mi><mi>α</mi></msub></math> open:
<math id="S0.I2.i7.I1.i1.p1.m3" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> continuous <math id="S0.I2.i7.I1.i1.p1.m4" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> every <math id="S0.I2.i7.I1.i1.p1.m5" class="ltx_Math" alttext="f|U_{\alpha}" display="inline"><mrow><mi>f</mi><mo fence="false">|</mo><msub><mi>U</mi><mi>α</mi></msub></mrow></math> continuous.</p>
</div>
</li>
<li id="S0.I2.i7.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S0.I2.i7.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i7.I1.i2.p1.m1" class="ltx_Math" alttext="X=A_{1}\cup\cdots\cup A_{n}" display="inline"><mrow><mi>X</mi><mo>=</mo><mrow><msub><mi>A</mi><mn>1</mn></msub><mo>∪</mo><mi mathvariant="normal">⋯</mi><mo>∪</mo><msub><mi>A</mi><mi>n</mi></msub></mrow></mrow></math> with all <math id="S0.I2.i7.I1.i2.p1.m2" class="ltx_Math" alttext="A_{i}" display="inline"><msub><mi>A</mi><mi>i</mi></msub></math> closed (<em class="ltx_emph ltx_font_italic">finitely many</em>):
<math id="S0.I2.i7.I1.i2.p1.m3" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> continuous <math id="S0.I2.i7.I1.i2.p1.m4" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> every <math id="S0.I2.i7.I1.i2.p1.m5" class="ltx_Math" alttext="f|A_{i}" display="inline"><mrow><mi>f</mi><mo fence="false">|</mo><msub><mi>A</mi><mi>i</mi></msub></mrow></math> continuous.</p>
</div>
</li>
</ul>
</div>
<div id="S0.I2.i7.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Open case: <math id="S0.I2.i7.p2.m1" class="ltx_Math" alttext="f^{-1}(V)=\bigcup(f|U_{\alpha})^{-1}(V)" display="inline"><mrow><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" rspace="0.111em">=</mo><mrow><mo mathcolor="#3D3D3D" rspace="0em">⋃</mo><mrow><msup><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo fence="false" mathcolor="#3D3D3D">|</mo><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">α</mi></msub></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>, a union of open sets.
Closed case: same with closed sets — and now finiteness is essential.</span></span></p>
</div>
</li>
<li id="S0.I2.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i8.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i8.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Maps into a product.)</span> <math id="S0.I2.i8.p1.m2" class="ltx_Math" alttext="f\colon A\to X\times Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>A</mi><mo stretchy="false">→</mo><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>Y</mi></mrow></mrow></mrow></math> is continuous
<math id="S0.I2.i8.p1.m3" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> both components <math id="S0.I2.i8.p1.m4" class="ltx_Math" alttext="f_{1}=\pi_{1}f" display="inline"><mrow><msub><mi>f</mi><mn>1</mn></msub><mo>=</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mi>f</mi></mrow></mrow></math> and <math id="S0.I2.i8.p1.m5" class="ltx_Math" alttext="f_{2}=\pi_{2}f" display="inline"><mrow><msub><mi>f</mi><mn>2</mn></msub><mo>=</mo><mrow><msub><mi>π</mi><mn>2</mn></msub><mo>⁢</mo><mi>f</mi></mrow></mrow></math> are continuous.</p>
</div>
<div id="S0.I2.i8.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Subbasis criterion: <math id="S0.I2.i8.p2.m1" class="ltx_Math" alttext="f^{-1}(U\times Y)=f_{1}^{-1}(U)" display="inline"><mrow><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">U</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">Y</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><msubsup><mi mathcolor="#3D3D3D">f</mi><mn mathcolor="#3D3D3D">1</mn><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msubsup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>, <math id="S0.I2.i8.p2.m2" class="ltx_Math" alttext="f^{-1}(X\times V)=f_{2}^{-1}(V)" display="inline"><mrow><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">X</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">V</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><msubsup><mi mathcolor="#3D3D3D">f</mi><mn mathcolor="#3D3D3D">2</mn><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msubsup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I2.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i9.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> The product topology is the <em class="ltx_emph ltx_font_italic">coarsest</em> topology making both projections
continuous.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S0.SS2" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.2  (§19) The product topology (general)</h2>

<div id="S0.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S0.I3" class="ltx_itemize">
<li id="S0.I3.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I3.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> On <math id="S0.I3.i1.p1.m2" class="ltx_Math" alttext="\prod_{\alpha\in J}X_{\alpha}" display="inline"><mrow><msub><mo>∏</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></msub><msub><mi>X</mi><mi>α</mi></msub></mrow></math> the <em class="ltx_emph ltx_font_italic">product topology</em> is generated by the
subbasis
<math id="S0.I3.i1.p1.m3" class="ltx_Math" alttext="\mathcal{S}=\{\pi_{\beta}^{-1}(U_{\beta})\mid\beta\in J,\ U_{\beta}\subset X_{%
\beta}\text{ open}\}." display="inline"><mrow><mrow><mi class="ltx_font_mathcaligraphic">𝒮</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><msubsup><mi>π</mi><mi>β</mi><mrow><mo>−</mo><mn>1</mn></mrow></msubsup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mi>U</mi><mi>β</mi></msub><mo stretchy="false">)</mo></mrow></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mrow><mi>β</mi><mo>∈</mo><mi>J</mi></mrow><mo rspace="0.667em">,</mo><mrow><msub><mi>U</mi><mi>β</mi></msub><mo>⊂</mo><mrow><msub><mi>X</mi><mi>β</mi></msub><mo>⁢</mo><mtext> open</mtext></mrow></mrow></mrow><mo stretchy="false">}</mo></mrow></mrow><mo lspace="0em">.</mo></mrow></math></p>
</div>
</li>
<li id="S0.I3.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I3.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> Concretely:</p>
<ul id="S0.I3.i2.I1" class="ltx_itemize">
<li id="S0.I3.i2.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S0.I3.i2.I1.i1.p1" class="ltx_para">
<p class="ltx_p">subbasis elements are <math id="S0.I3.i2.I1.i1.p1.m1" class="ltx_Math" alttext="\prod_{\alpha}U_{\alpha}" display="inline"><mrow><msub><mo>∏</mo><mi>α</mi></msub><msub><mi>U</mi><mi>α</mi></msub></mrow></math> with <math id="S0.I3.i2.I1.i1.p1.m2" class="ltx_Math" alttext="U_{\alpha}\neq X_{\alpha}" display="inline"><mrow><msub><mi>U</mi><mi>α</mi></msub><mo>≠</mo><msub><mi>X</mi><mi>α</mi></msub></mrow></math>
for <em class="ltx_emph ltx_font_italic">at most one</em> <math id="S0.I3.i2.I1.i1.p1.m3" class="ltx_Math" alttext="\alpha" display="inline"><mi>α</mi></math>;</p>
</div>
</li>
<li id="S0.I3.i2.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S0.I3.i2.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p">basis elements are <math id="S0.I3.i2.I1.i2.p1.m1" class="ltx_Math" alttext="\prod_{\alpha}U_{\alpha}" display="inline"><mrow><msub><mo>∏</mo><mi>α</mi></msub><msub><mi>U</mi><mi>α</mi></msub></mrow></math> with <math id="S0.I3.i2.I1.i2.p1.m2" class="ltx_Math" alttext="U_{\alpha}\neq X_{\alpha}" display="inline"><mrow><msub><mi>U</mi><mi>α</mi></msub><mo>≠</mo><msub><mi>X</mi><mi>α</mi></msub></mrow></math>
for <em class="ltx_emph ltx_font_italic">finitely many</em> <math id="S0.I3.i2.I1.i2.p1.m3" class="ltx_Math" alttext="\alpha" display="inline"><mi>α</mi></math>.</p>
</div>
</li>
</ul>
</div>
<div id="S0.I3.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Emphasise “all but finitely many coordinates unrestricted”. This is the point where
students expect the naive definition and get a different one.</span></span></span></p>
</div>
</li>
<li id="S0.I3.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I3.i3.p1.m1" class="ltx_Math" alttext="f\colon A\to\prod X_{\alpha}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>A</mi><mo rspace="0.111em" stretchy="false">→</mo><mrow><mo>∏</mo><msub><mi>X</mi><mi>α</mi></msub></mrow></mrow></mrow></math> continuous <math id="S0.I3.i3.p1.m2" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> every component <math id="S0.I3.i3.p1.m3" class="ltx_Math" alttext="f_{\beta}=\pi_{\beta}f" display="inline"><mrow><msub><mi>f</mi><mi>β</mi></msub><mo>=</mo><mrow><msub><mi>π</mi><mi>β</mi></msub><mo>⁢</mo><mi>f</mi></mrow></mrow></math>
is continuous.</p>
</div>
</li>
<li id="S0.I3.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> The product topology is the coarsest making all <math id="S0.I3.i4.p1.m1" class="ltx_Math" alttext="\pi_{\beta}" display="inline"><msub><mi>π</mi><mi>β</mi></msub></math> continuous.</p>
</div>
</li>
<li id="S0.I3.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I3.i5.p1.m1" class="ltx_Math" alttext="A_{\alpha}\subset X_{\alpha}" display="inline"><mrow><msub><mi>A</mi><mi>α</mi></msub><mo>⊂</mo><msub><mi>X</mi><mi>α</mi></msub></mrow></math> subspaces: on <math id="S0.I3.i5.p1.m2" class="ltx_Math" alttext="\prod A_{\alpha}" display="inline"><mrow><mo>∏</mo><msub><mi>A</mi><mi>α</mi></msub></mrow></math>, product topology
<math id="S0.I3.i5.p1.m3" class="ltx_Math" alttext="=" display="inline"><mo>=</mo></math> subspace topology from <math id="S0.I3.i5.p1.m4" class="ltx_Math" alttext="\prod X_{\alpha}" display="inline"><mrow><mo>∏</mo><msub><mi>X</mi><mi>α</mi></msub></mrow></math>.</p>
</div>
</li>
<li id="S0.I3.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> All <math id="S0.I3.i6.p1.m1" class="ltx_Math" alttext="X_{\alpha}" display="inline"><msub><mi>X</mi><mi>α</mi></msub></math> Hausdorff <math id="S0.I3.i6.p1.m2" class="ltx_Math" alttext="\Rightarrow\prod X_{\alpha}" display="inline"><mrow><mi></mi><mo rspace="0.111em" stretchy="false">⇒</mo><mrow><mo>∏</mo><msub><mi>X</mi><mi>α</mi></msub></mrow></mrow></math> Hausdorff.</p>
</div>
</li>
<li id="S0.I3.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i7.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I3.i7.p1.m1" class="ltx_Math" alttext="\overline{\prod_{\alpha}A_{\alpha}}=\prod_{\alpha}\overline{A_{\alpha}}" display="inline"><mrow><mover accent="true"><mrow><msub><mo>∏</mo><mi>α</mi></msub><msub><mi>A</mi><mi>α</mi></msub></mrow><mo>¯</mo></mover><mo rspace="0.111em">=</mo><mrow><msub><mo>∏</mo><mi>α</mi></msub><mover accent="true"><msub><mi>A</mi><mi>α</mi></msub><mo>¯</mo></mover></mrow></mrow></math>.</p>
</div>
</li>
</ul>
</div>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:59:07 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
