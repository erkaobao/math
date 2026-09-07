---
layout: archive
title: "MATH 5345H --- Week 8: Components, path components, and local connectedness"
permalink: /teaching/5345h_notes/week_8
author_profile: false
render_with_liquid: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S0.SS1" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.1  (§25) Components and local connectedness</h2>

<div id="S0.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S0.I1" class="ltx_itemize">
<li id="S0.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i1.p1.m1" class="ltx_Math" alttext="x\sim y" display="inline"><mrow><mi>x</mi><mo>∼</mo><mi>y</mi></mrow></math> iff some connected <math id="S0.I1.i1.p1.m2" class="ltx_Math" alttext="C\subset X" display="inline"><mrow><mi>C</mi><mo>⊂</mo><mi>X</mi></mrow></math> contains both. An equivalence relation;
classes are the <em class="ltx_emph ltx_font_italic">components</em> of <math id="S0.I1.i1.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>.</p>
</div>
</li>
<li id="S0.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> Components are connected, disjoint, and cover <math id="S0.I1.i2.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>; every nonempty connected
subset lies in exactly one.</p>
</div>
<div id="S0.I1.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Connectedness of a component <math id="S0.I1.i2.p2.m1" class="ltx_Math" alttext="C" display="inline"><mi mathcolor="#3D3D3D">C</mi></math>: fix <math id="S0.I1.i2.p2.m2" class="ltx_Math" alttext="x_{0}\in C" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">0</mn></msub><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">C</mi></mrow></math>, write <math id="S0.I1.i2.p2.m3" class="ltx_Math" alttext="C=\bigcup_{x\in C}A_{x}" display="inline"><mrow><mi mathcolor="#3D3D3D">C</mi><mo mathcolor="#3D3D3D" rspace="0.111em">=</mo><mrow><msub><mo mathcolor="#3D3D3D">⋃</mo><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">C</mi></mrow></msub><msub><mi mathcolor="#3D3D3D">A</mi><mi mathcolor="#3D3D3D">x</mi></msub></mrow></mrow></math> with each
<math id="S0.I1.i2.p2.m4" class="ltx_Math" alttext="A_{x}" display="inline"><msub><mi mathcolor="#3D3D3D">A</mi><mi mathcolor="#3D3D3D">x</mi></msub></math> connected containing <math id="S0.I1.i2.p2.m5" class="ltx_Math" alttext="x_{0}" display="inline"><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">0</mn></msub></math>; apply the common-point theorem.</span></span></p>
</div>
</li>
<li id="S0.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> A finite product of connected spaces is connected.</p>
</div>
<div id="S0.I1.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> In <math id="S0.I1.i3.p2.m1" class="ltx_Math" alttext="X\times Y" display="inline"><mrow><mi mathcolor="#3D3D3D">X</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">Y</mi></mrow></math>: <math id="S0.I1.i3.p2.m2" class="ltx_Math" alttext="X\times\{y\}" display="inline"><mrow><mi mathcolor="#3D3D3D">X</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">y</mi><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></math> then <math id="S0.I1.i3.p2.m3" class="ltx_Math" alttext="\{x^{\prime}\}\times Y" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><msup><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">′</mo></msup><mo mathcolor="#3D3D3D" rspace="0.055em" stretchy="false">}</mo></mrow><mo mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">Y</mi></mrow></math> links <math id="S0.I1.i3.p2.m4" class="ltx_Math" alttext="(x,y)" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">y</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></math> to <math id="S0.I1.i3.p2.m5" class="ltx_Math" alttext="(x^{\prime},y^{\prime})" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msup><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">′</mo></msup><mo mathcolor="#3D3D3D">,</mo><msup><mi mathcolor="#3D3D3D">y</mi><mo mathcolor="#3D3D3D">′</mo></msup><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></math>.
Then induct.</span></span></p>
</div>
<div id="S0.I1.i3.p3" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> True for arbitrary products too.</p>
</div>
</li>
<li id="S0.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i4.p1.m1" class="ltx_Math" alttext="x\simeq y" display="inline"><mrow><mi>x</mi><mo>≃</mo><mi>y</mi></mrow></math> iff a path joins them; classes are the <em class="ltx_emph ltx_font_italic">path components</em>.
Same statements as for components.</p>
</div>
</li>
<li id="S0.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i5.p1.m1" class="ltx_Math" alttext="\bar{S}" display="inline"><mover accent="true"><mi>S</mi><mo>¯</mo></mover></math> (topologist’s sine curve): <em class="ltx_emph ltx_font_italic">one</em> component, <em class="ltx_emph ltx_font_italic">two</em> path components
<math id="S0.I1.i5.p1.m2" class="ltx_Math" alttext="S" display="inline"><mi>S</mi></math> and <math id="S0.I1.i5.p1.m3" class="ltx_Math" alttext="V" display="inline"><mi>V</mi></math>. Note <math id="S0.I1.i5.p1.m4" class="ltx_Math" alttext="S" display="inline"><mi>S</mi></math> is open but not closed in <math id="S0.I1.i5.p1.m5" class="ltx_Math" alttext="\bar{S}" display="inline"><mover accent="true"><mi>S</mi><mo>¯</mo></mover></math>; <math id="S0.I1.i5.p1.m6" class="ltx_Math" alttext="V" display="inline"><mi>V</mi></math> is closed but not open.</p>
</div>
</li>
<li id="S0.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i6.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">locally connected at <math id="S0.I1.i6.p1.m2" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math></em> if every neighborhood <math id="S0.I1.i6.p1.m3" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math> of <math id="S0.I1.i6.p1.m4" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> contains a
connected neighborhood <math id="S0.I1.i6.p1.m5" class="ltx_Math" alttext="V" display="inline"><mi>V</mi></math> of <math id="S0.I1.i6.p1.m6" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math>: <math id="S0.I1.i6.p1.m7" class="ltx_Math" alttext="x\in V\subset U" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>V</mi><mo>⊂</mo><mi>U</mi></mrow></math>. Likewise
<em class="ltx_emph ltx_font_italic">locally path connected</em>.</p>
</div>
</li>
<li id="S0.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i7.p1.m1" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math> is locally (path) connected.
<math id="S0.I1.i7.p1.m2" class="ltx_Math" alttext="\bar{S}" display="inline"><mover accent="true"><mi>S</mi><mo>¯</mo></mover></math> is not: small neighborhoods of points of <math id="S0.I1.i7.p1.m3" class="ltx_Math" alttext="V" display="inline"><mi>V</mi></math> are disconnected.</p>
</div>
</li>
<li id="S0.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> Connected <math id="S0.I1.i8.p1.m1" class="ltx_Math" alttext="\neq" display="inline"><mo>≠</mo></math> locally connected, in either direction.</p>
</div>
</li>
<li id="S0.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i9.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i9.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> locally connected <math id="S0.I1.i9.p1.m3" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> every component is open.
<math id="S0.I1.i9.p1.m4" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> locally path connected <math id="S0.I1.i9.p1.m5" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> every path component is open.</p>
</div>
</li>
<li id="S0.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i10.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i10.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> Each path component lies in a unique component. If <math id="S0.I1.i10.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is locally path connected,
components <math id="S0.I1.i10.p1.m3" class="ltx_Math" alttext="=" display="inline"><mo>=</mo></math> path components.</p>
</div>
<div id="S0.I1.i10.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I1.i10.p2.m1" class="ltx_Math" alttext="C=P\sqcup U" display="inline"><mrow><mi mathcolor="#3D3D3D">C</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">P</mi><mo mathcolor="#3D3D3D">⊔</mo><mi mathcolor="#3D3D3D">U</mi></mrow></mrow></math> with <math id="S0.I1.i10.p2.m2" class="ltx_Math" alttext="U" display="inline"><mi mathcolor="#3D3D3D">U</mi></math> a union of other path components; all are open,
so <math id="S0.I1.i10.p2.m3" class="ltx_Math" alttext="P" display="inline"><mi mathcolor="#3D3D3D">P</mi></math> is clopen in the connected <math id="S0.I1.i10.p2.m4" class="ltx_Math" alttext="C" display="inline"><mi mathcolor="#3D3D3D">C</mi></math>, forcing <math id="S0.I1.i10.p2.m5" class="ltx_Math" alttext="P=C" display="inline"><mrow><mi mathcolor="#3D3D3D">P</mi><mo mathcolor="#3D3D3D">=</mo><mi mathcolor="#3D3D3D">C</mi></mrow></math>.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S0.SS2" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.2  (§26) Compact spaces</h2>

<div id="S0.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S0.I2" class="ltx_itemize">
<li id="S0.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I2.i1.p1.m1" class="ltx_Math" alttext="\mathcal{A}=\{U_{\alpha}\}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">𝒜</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><msub><mi>U</mi><mi>α</mi></msub><mo stretchy="false">}</mo></mrow></mrow></math> <em class="ltx_emph ltx_font_italic">covers</em> <math id="S0.I2.i1.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> if <math id="S0.I2.i1.p1.m3" class="ltx_Math" alttext="\bigcup U_{\alpha}=X" display="inline"><mrow><mrow><mo>⋃</mo><msub><mi>U</mi><mi>α</mi></msub></mrow><mo>=</mo><mi>X</mi></mrow></math>;
an <em class="ltx_emph ltx_font_italic">open cover</em> if all <math id="S0.I2.i1.p1.m4" class="ltx_Math" alttext="U_{\alpha}" display="inline"><msub><mi>U</mi><mi>α</mi></msub></math> are open.
A <em class="ltx_emph ltx_font_italic">subcover</em> is a subcollection that still covers.</p>
</div>
</li>
<li id="S0.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I2.i2.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">compact</em> if every open cover of <math id="S0.I2.i2.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> has a finite subcover.</p>
</div>
</li>
<li id="S0.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Finite spaces are compact. <math id="S0.I2.i3.p1.m1" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math> is <em class="ltx_emph ltx_font_italic">not</em>: <math id="S0.I2.i3.p1.m2" class="ltx_Math" alttext="\{(n-1,n+1)\}_{n\in\mathbb{N}}" display="inline"><msub><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">(</mo><mrow><mi>n</mi><mo>−</mo><mn>1</mn></mrow><mo>,</mo><mrow><mi>n</mi><mo>+</mo><mn>1</mn></mrow><mo stretchy="false">)</mo></mrow><mo stretchy="false">}</mo></mrow><mrow><mi>n</mi><mo>∈</mo><mi>ℕ</mi></mrow></msub></math>
has no finite subcover. But <math id="S0.I2.i3.p1.m3" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math> with <math id="S0.I2.i3.p1.m4" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{triv}}" display="inline"><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>triv</mi></msub></math> <em class="ltx_emph ltx_font_italic">is</em> compact.</p>
</div>
<div id="S0.I2.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Compactness is a property of the topology, not of the set — worth saying out loud
before students attach it to “bounded”.</span></span></span></p>
</div>
</li>
<li id="S0.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> <span class="ltx_text ltx_font_bold">Story break.</span> Tell the Atiyah–Segal examination anecdote from
S. G. Krantz, <em class="ltx_emph ltx_font_italic">Mathematical Apocrypha</em>: a nervous student, asked for an example of
a compact set, answers “the real line” — and Segal rescues him with
“in what topology?” The joke is exactly the previous two examples.</p>
</div>
</li>
<li id="S0.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I2.i5.p1.m1" class="ltx_Math" alttext="X=\{0\}\cup\{1/n\mid n\in\mathbb{N}\}\subset\mathbb{R}" display="inline"><mrow><mi>X</mi><mo>=</mo><mrow><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow><mo>∪</mo><mrow><mo stretchy="false">{</mo><mrow><mn>1</mn><mo>/</mo><mi>n</mi></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>n</mi><mo>∈</mo><mi>ℕ</mi></mrow><mo stretchy="false">}</mo></mrow></mrow><mo>⊂</mo><mi>ℝ</mi></mrow></math> is compact:
one <math id="S0.I2.i5.p1.m2" class="ltx_Math" alttext="U\ni 0" display="inline"><mrow><mi>U</mi><mo>∋</mo><mn>0</mn></mrow></math> catches all but finitely many <math id="S0.I2.i5.p1.m3" class="ltx_Math" alttext="1/n" display="inline"><mrow><mn>1</mn><mo>/</mo><mi>n</mi></mrow></math>; cover those individually.</p>
</div>
</li>
<li id="S0.I2.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Any <math id="S0.I2.i6.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> with <math id="S0.I2.i6.p1.m2" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{cof}}" display="inline"><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>cof</mi></msub></math> is compact: one nonempty <math id="S0.I2.i6.p1.m3" class="ltx_Math" alttext="U_{\beta}" display="inline"><msub><mi>U</mi><mi>β</mi></msub></math> leaves a finite complement.</p>
</div>
</li>
<li id="S0.I2.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i7.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i7.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I2.i7.p1.m2" class="ltx_Math" alttext="Y\subset X" display="inline"><mrow><mi>Y</mi><mo>⊂</mo><mi>X</mi></mrow></math> is compact <math id="S0.I2.i7.p1.m3" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> every cover of <math id="S0.I2.i7.p1.m4" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> by open subsets <em class="ltx_emph ltx_font_italic">of <math id="S0.I2.i7.p1.m5" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math></em>
has a finite subcollection covering <math id="S0.I2.i7.p1.m6" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math>.</p>
</div>
<div id="S0.I2.i7.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Translate along <math id="S0.I2.i7.p2.m1" class="ltx_Math" alttext="V_{\alpha}=Y\cap U_{\alpha}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">V</mi><mi mathcolor="#3D3D3D">α</mi></msub><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">Y</mi><mo mathcolor="#3D3D3D">∩</mo><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">α</mi></msub></mrow></mrow></math>. Lets you work in <math id="S0.I2.i7.p2.m2" class="ltx_Math" alttext="X" display="inline"><mi mathcolor="#3D3D3D">X</mi></math> and forget the subspace
topology.</span></span></p>
</div>
</li>
<li id="S0.I2.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i8.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i8.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> A closed subspace of a compact space is compact.</p>
</div>
</li>
<li id="S0.I2.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i9.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i9.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> A compact subspace of a Hausdorff space is closed.</p>
</div>
<div id="S0.I2.i9.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Fix <math id="S0.I2.i9.p2.m1" class="ltx_Math" alttext="p\notin K" display="inline"><mrow><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D">∉</mo><mi mathcolor="#3D3D3D">K</mi></mrow></math>. For each <math id="S0.I2.i9.p2.m2" class="ltx_Math" alttext="q\in K" display="inline"><mrow><mi mathcolor="#3D3D3D">q</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">K</mi></mrow></math> separate <math id="S0.I2.i9.p2.m3" class="ltx_Math" alttext="p,q" display="inline"><mrow><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">q</mi></mrow></math> by <math id="S0.I2.i9.p2.m4" class="ltx_Math" alttext="U_{q},V_{q}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">q</mi></msub><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">V</mi><mi mathcolor="#3D3D3D">q</mi></msub></mrow></math>. Finitely many <math id="S0.I2.i9.p2.m5" class="ltx_Math" alttext="V_{q_{i}}" display="inline"><msub><mi mathcolor="#3D3D3D">V</mi><msub><mi mathcolor="#3D3D3D">q</mi><mi mathcolor="#3D3D3D">i</mi></msub></msub></math>
cover <math id="S0.I2.i9.p2.m6" class="ltx_Math" alttext="K" display="inline"><mi mathcolor="#3D3D3D">K</mi></math>; then <math id="S0.I2.i9.p2.m7" class="ltx_Math" alttext="U=\bigcap U_{q_{i}}" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" rspace="0.111em">=</mo><mrow><mo mathcolor="#3D3D3D">⋂</mo><msub><mi mathcolor="#3D3D3D">U</mi><msub><mi mathcolor="#3D3D3D">q</mi><mi mathcolor="#3D3D3D">i</mi></msub></msub></mrow></mrow></math> misses <math id="S0.I2.i9.p2.m8" class="ltx_Math" alttext="K" display="inline"><mi mathcolor="#3D3D3D">K</mi></math>. Compact sets generalise finite sets here.</span></span></p>
</div>
</li>
<li id="S0.I2.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> (Extracted from that proof.) <math id="S0.I2.i10.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> Hausdorff, <math id="S0.I2.i10.p1.m2" class="ltx_Math" alttext="K" display="inline"><mi>K</mi></math> compact, <math id="S0.I2.i10.p1.m3" class="ltx_Math" alttext="p\notin K" display="inline"><mrow><mi>p</mi><mo>∉</mo><mi>K</mi></mrow></math>
<math id="S0.I2.i10.p1.m4" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> there are disjoint open <math id="S0.I2.i10.p1.m5" class="ltx_Math" alttext="U\ni p" display="inline"><mrow><mi>U</mi><mo>∋</mo><mi>p</mi></mrow></math> and <math id="S0.I2.i10.p1.m6" class="ltx_Math" alttext="V\supset K" display="inline"><mrow><mi>V</mi><mo>⊃</mo><mi>K</mi></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i11.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i11.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> The continuous image of a compact space is compact.</p>
</div>
</li>
<li id="S0.I2.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i12.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i12.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I2.i12.p1.m2" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> a map, <math id="S0.I2.i12.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> compact, <math id="S0.I2.i12.p1.m4" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> Hausdorff. Then</p>
<ol id="S0.I2.i12.I1" class="ltx_enumerate">
<li id="S0.I2.i12.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(1)</span> 
<div id="S0.I2.i12.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i12.I1.i1.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is a closed map;</p>
</div>
</li>
<li id="S0.I2.i12.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(2)</span> 
<div id="S0.I2.i12.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i12.I1.i2.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> surjective <math id="S0.I2.i12.I1.i2.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> <math id="S0.I2.i12.I1.i2.p1.m3" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is a quotient map;</p>
</div>
</li>
<li id="S0.I2.i12.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(3)</span> 
<div id="S0.I2.i12.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i12.I1.i3.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> bijective <math id="S0.I2.i12.I1.i3.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> <math id="S0.I2.i12.I1.i3.p1.m3" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is a homeomorphism;</p>
</div>
</li>
<li id="S0.I2.i12.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(4)</span> 
<div id="S0.I2.i12.I1.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i12.I1.i4.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> injective <math id="S0.I2.i12.I1.i4.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> <math id="S0.I2.i12.I1.i4.p1.m3" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is an embedding.</p>
</div>
</li>
</ol>
</div>
<div id="S0.I2.i12.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> All from (1): <math id="S0.I2.i12.p2.m1" class="ltx_Math" alttext="A" display="inline"><mi mathcolor="#3D3D3D">A</mi></math> closed <math id="S0.I2.i12.p2.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> <math id="S0.I2.i12.p2.m3" class="ltx_Math" alttext="A" display="inline"><mi mathcolor="#3D3D3D">A</mi></math> compact <math id="S0.I2.i12.p2.m4" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> <math id="S0.I2.i12.p2.m5" class="ltx_Math" alttext="f(A)" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> compact <math id="S0.I2.i12.p2.m6" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> <math id="S0.I2.i12.p2.m7" class="ltx_Math" alttext="f(A)" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> closed.
This is the standard device for upgrading continuous bijections — contrast <math id="S0.I2.i12.p2.m8" class="ltx_Math" alttext="[0,1)\to S^{1}" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mn mathcolor="#3D3D3D">0</mn><mo mathcolor="#3D3D3D">,</mo><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">→</mo><msup><mi mathcolor="#3D3D3D">S</mi><mn mathcolor="#3D3D3D">1</mn></msup></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I2.i13" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i13.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I2.i13.p1.m1" class="ltx_Math" alttext="\mathbb{R}\to\{0\}" display="inline"><mrow><mi>ℝ</mi><mo stretchy="false">→</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></math>: preimages of compact sets need not be compact.
<span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I2.i13.p1.m2" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is <em class="ltx_emph ltx_font_italic">proper</em> if <math id="S0.I2.i13.p1.m3" class="ltx_Math" alttext="f^{-1}(K)" display="inline"><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>K</mi><mo stretchy="false">)</mo></mrow></mrow></math> is compact for every compact <math id="S0.I2.i13.p1.m4" class="ltx_Math" alttext="K" display="inline"><mi>K</mi></math>.</p>
</div>
</li>
<li id="S0.I2.i14" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i14.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i14.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <span class="ltx_text ltx_font_bold">(Tube lemma.)</span> <math id="S0.I2.i14.p1.m2" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> compact, <math id="S0.I2.i14.p1.m3" class="ltx_Math" alttext="N\subset X\times Y" display="inline"><mrow><mi>N</mi><mo>⊂</mo><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>Y</mi></mrow></mrow></math> open with
<math id="S0.I2.i14.p1.m4" class="ltx_Math" alttext="\{p\}\times Y\subset N" display="inline"><mrow><mrow><mrow><mo stretchy="false">{</mo><mi>p</mi><mo rspace="0.055em" stretchy="false">}</mo></mrow><mo rspace="0.222em">×</mo><mi>Y</mi></mrow><mo>⊂</mo><mi>N</mi></mrow></math> <math id="S0.I2.i14.p1.m5" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> there is a neighborhood <math id="S0.I2.i14.p1.m6" class="ltx_Math" alttext="U\ni p" display="inline"><mrow><mi>U</mi><mo>∋</mo><mi>p</mi></mrow></math> with <math id="S0.I2.i14.p1.m7" class="ltx_Math" alttext="U\times Y\subset N" display="inline"><mrow><mrow><mi>U</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>Y</mi></mrow><mo>⊂</mo><mi>N</mi></mrow></math>.</p>
</div>
<div id="S0.I2.i14.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Cover <math id="S0.I2.i14.p2.m1" class="ltx_Math" alttext="\{p\}\times Y" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D" rspace="0.055em" stretchy="false">}</mo></mrow><mo mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">Y</mi></mrow></math> by basis boxes <math id="S0.I2.i14.p2.m2" class="ltx_Math" alttext="U_{q}\times V_{q}\subset N" display="inline"><mrow><mrow><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">q</mi></msub><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><msub><mi mathcolor="#3D3D3D">V</mi><mi mathcolor="#3D3D3D">q</mi></msub></mrow><mo mathcolor="#3D3D3D">⊂</mo><mi mathcolor="#3D3D3D">N</mi></mrow></math>; finitely many <math id="S0.I2.i14.p2.m3" class="ltx_Math" alttext="V_{q_{i}}" display="inline"><msub><mi mathcolor="#3D3D3D">V</mi><msub><mi mathcolor="#3D3D3D">q</mi><mi mathcolor="#3D3D3D">i</mi></msub></msub></math>
suffice; take <math id="S0.I2.i14.p2.m4" class="ltx_Math" alttext="U=\bigcap U_{q_{i}}" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" rspace="0.111em">=</mo><mrow><mo mathcolor="#3D3D3D">⋂</mo><msub><mi mathcolor="#3D3D3D">U</mi><msub><mi mathcolor="#3D3D3D">q</mi><mi mathcolor="#3D3D3D">i</mi></msub></msub></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I2.i15" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i15.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> Fails without compactness of <math id="S0.I2.i15.p1.m1" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math>: take <math id="S0.I2.i15.p1.m2" class="ltx_Math" alttext="N=\{|xy|&lt;1\}\supset\{0\}\times\mathbb{R}" display="inline"><mrow><mi>N</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mrow><mo stretchy="false">|</mo><mrow><mi>x</mi><mo>⁢</mo><mi>y</mi></mrow><mo stretchy="false">|</mo></mrow><mo>&lt;</mo><mn>1</mn></mrow><mo stretchy="false">}</mo></mrow><mo>⊃</mo><mrow><mrow><mo stretchy="false">{</mo><mn>0</mn><mo rspace="0.055em" stretchy="false">}</mo></mrow><mo rspace="0.222em">×</mo><mi>ℝ</mi></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I2.i16" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i16.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i16.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I2.i16.p1.m2" class="ltx_Math" alttext="X,Y" display="inline"><mrow><mi>X</mi><mo>,</mo><mi>Y</mi></mrow></math> compact <math id="S0.I2.i16.p1.m3" class="ltx_Math" alttext="\Rightarrow X\times Y" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>Y</mi></mrow></mrow></math> compact. <span class="ltx_text ltx_font_bold">Cor.</span> Finite products of compact spaces
are compact.</p>
</div>
<div id="S0.I2.i16.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> For each <math id="S0.I2.i16.p2.m1" class="ltx_Math" alttext="p" display="inline"><mi mathcolor="#3D3D3D">p</mi></math>, finitely many <math id="S0.I2.i16.p2.m2" class="ltx_Math" alttext="W_{\alpha}" display="inline"><msub><mi mathcolor="#3D3D3D">W</mi><mi mathcolor="#3D3D3D">α</mi></msub></math> cover <math id="S0.I2.i16.p2.m3" class="ltx_Math" alttext="\{p\}\times Y" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D" rspace="0.055em" stretchy="false">}</mo></mrow><mo mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">Y</mi></mrow></math>; the tube lemma widens this to
<math id="S0.I2.i16.p2.m4" class="ltx_Math" alttext="U_{p}\times Y" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">p</mi></msub><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">Y</mi></mrow></math>. Then finitely many <math id="S0.I2.i16.p2.m5" class="ltx_Math" alttext="U_{p}" display="inline"><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">p</mi></msub></math> cover <math id="S0.I2.i16.p2.m6" class="ltx_Math" alttext="X" display="inline"><mi mathcolor="#3D3D3D">X</mi></math>. Union of finitely many finite collections.</span></span></p>
</div>
</li>
<li id="S0.I2.i17" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i17.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I2.i17.p1.m1" class="ltx_Math" alttext="\mathcal{C}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒞</mi></math> has the <em class="ltx_emph ltx_font_italic">finite intersection property</em> if every finite subcollection has
nonempty intersection.</p>
</div>
</li>
<li id="S0.I2.i18" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i18.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i18.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I2.i18.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is compact <math id="S0.I2.i18.p1.m3" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> every collection <math id="S0.I2.i18.p1.m4" class="ltx_Math" alttext="\mathcal{C}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒞</mi></math> of closed sets with the finite
intersection property has <math id="S0.I2.i18.p1.m5" class="ltx_Math" alttext="\bigcap_{C\in\mathcal{C}}C\neq\emptyset" display="inline"><mrow><mrow><msub><mo>⋂</mo><mrow><mi>C</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒞</mi></mrow></msub><mi>C</mi></mrow><mo>≠</mo><mi mathvariant="normal">∅</mi></mrow></math>.</p>
</div>
<div id="S0.I2.i18.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Purely the contrapositive of the definition, read through complements. Write the four
successive rephrasings on the board.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:59:19 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
