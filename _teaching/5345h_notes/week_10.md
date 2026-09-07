---
layout: archive
title: "MATH 5345H --- Week 10: Local compactness and the one-point compactification"
permalink: /teaching/5345h_notes/week_10
author_profile: false
render_with_liquid: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S0.SS1" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.1  (§29) Local compactness</h3>

<div id="S0.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S0.I1" class="ltx_itemize">
<li id="S0.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i1.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">locally compact at <math id="S0.I1.i1.p1.m3" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math></em> if there is a compact <math id="S0.I1.i1.p1.m4" class="ltx_Math" alttext="C" display="inline"><mi>C</mi></math> containing a
neighborhood <math id="S0.I1.i1.p1.m5" class="ltx_Math" alttext="V" display="inline"><mi>V</mi></math> of <math id="S0.I1.i1.p1.m6" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math>:   <math id="S0.I1.i1.p1.m7" class="ltx_Math" alttext="x\in V\subset C\subset X" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>V</mi><mo>⊂</mo><mi>C</mi><mo>⊂</mo><mi>X</mi></mrow></math>. Locally compact: at every point.</p>
</div>
</li>
<li id="S0.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Compact <math id="S0.I1.i2.p1.m1" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> locally compact. <math id="S0.I1.i2.p1.m2" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math> is locally compact (<math id="S0.I1.i2.p1.m3" class="ltx_Math" alttext="V=(x-1,x+1)\subset C=[x-1,x+1]" display="inline"><mrow><mi>V</mi><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><mi>x</mi><mo>−</mo><mn>1</mn></mrow><mo>,</mo><mrow><mi>x</mi><mo>+</mo><mn>1</mn></mrow><mo stretchy="false">)</mo></mrow><mo>⊂</mo><mi>C</mi><mo>=</mo><mrow><mo stretchy="false">[</mo><mrow><mi>x</mi><mo>−</mo><mn>1</mn></mrow><mo>,</mo><mrow><mi>x</mi><mo>+</mo><mn>1</mn></mrow><mo stretchy="false">]</mo></mrow></mrow></math>); so is <math id="S0.I1.i2.p1.m4" class="ltx_Math" alttext="\mathbb{R}^{n}" display="inline"><msup><mi>ℝ</mi><mi>n</mi></msup></math>, using products of intervals.</p>
</div>
</li>
<li id="S0.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i3.p1.m1" class="ltx_Math" alttext="\mathbb{Q}" display="inline"><mi>ℚ</mi></math> is <em class="ltx_emph ltx_font_italic">not</em> locally compact. Nor is <math id="S0.I1.i3.p1.m2" class="ltx_Math" alttext="\mathbb{R}^{\omega}" display="inline"><msup><mi>ℝ</mi><mi>ω</mi></msup></math>: a basis neighborhood of <math id="S0.I1.i3.p1.m3" class="ltx_Math" alttext="0" display="inline"><mn>0</mn></math>
has non-compact closure.</p>
</div>
</li>
<li id="S0.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i4.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <span class="ltx_text ltx_font_bold">(One-point compactification.)</span> <math id="S0.I1.i4.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> locally compact Hausdorff,
<math id="S0.I1.i4.p1.m3" class="ltx_Math" alttext="Y=X\cup\{\infty\}" display="inline"><mrow><mi>Y</mi><mo>=</mo><mrow><mi>X</mi><mo>∪</mo><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∞</mi><mo stretchy="false">}</mo></mrow></mrow></mrow></math> with <math id="S0.I1.i4.p1.m4" class="ltx_Math" alttext="\mathcal{T}_{\infty}" display="inline"><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi mathvariant="normal">∞</mi></msub></math> consisting of
(1) the open <math id="S0.I1.i4.p1.m5" class="ltx_Math" alttext="U\subset X" display="inline"><mrow><mi>U</mi><mo>⊂</mo><mi>X</mi></mrow></math>, and
(2) the sets <math id="S0.I1.i4.p1.m6" class="ltx_Math" alttext="Y-C" display="inline"><mrow><mi>Y</mi><mo>−</mo><mi>C</mi></mrow></math> for <math id="S0.I1.i4.p1.m7" class="ltx_Math" alttext="C\subset X" display="inline"><mrow><mi>C</mi><mo>⊂</mo><mi>X</mi></mrow></math> compact.</p>
</div>
</li>
<li id="S0.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i5.p1.m2" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> is compact Hausdorff, <math id="S0.I1.i5.p1.m3" class="ltx_Math" alttext="X\subset Y" display="inline"><mrow><mi>X</mi><mo>⊂</mo><mi>Y</mi></mrow></math> is a subspace, and <math id="S0.I1.i5.p1.m4" class="ltx_Math" alttext="Y-X" display="inline"><mrow><mi>Y</mi><mo>−</mo><mi>X</mi></mrow></math> is one point.</p>
</div>
<div id="S0.I1.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Topology: three cases each for <math id="S0.I1.i5.p2.m1" class="ltx_Math" alttext="\cap" display="inline"><mo mathcolor="#3D3D3D">∩</mo></math> and <math id="S0.I1.i5.p2.m2" class="ltx_Math" alttext="\cup" display="inline"><mo mathcolor="#3D3D3D">∪</mo></math>; needs <math id="S0.I1.i5.p2.m3" class="ltx_Math" alttext="C_{1}\cup C_{2}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">C</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">∪</mo><msub><mi mathcolor="#3D3D3D">C</mi><mn mathcolor="#3D3D3D">2</mn></msub></mrow></math> compact, <math id="S0.I1.i5.p2.m4" class="ltx_Math" alttext="X-C" display="inline"><mrow><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">C</mi></mrow></math> open
(Hausdorff), and <math id="S0.I1.i5.p2.m5" class="ltx_Math" alttext="\bigcap C_{\beta}" display="inline"><mrow><mo mathcolor="#3D3D3D">⋂</mo><msub><mi mathcolor="#3D3D3D">C</mi><mi mathcolor="#3D3D3D">β</mi></msub></mrow></math>, <math id="S0.I1.i5.p2.m6" class="ltx_Math" alttext="C-U" display="inline"><mrow><mi mathcolor="#3D3D3D">C</mi><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">U</mi></mrow></math> compact (closed in a compact set).
Compact: any cover has some <math id="S0.I1.i5.p2.m7" class="ltx_Math" alttext="V=Y-C" display="inline"><mrow><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">Y</mi><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">C</mi></mrow></mrow></math> containing <math id="S0.I1.i5.p2.m8" class="ltx_Math" alttext="\infty" display="inline"><mi mathcolor="#3D3D3D" mathvariant="normal">∞</mi></math>; cover the compact <math id="S0.I1.i5.p2.m9" class="ltx_Math" alttext="C" display="inline"><mi mathcolor="#3D3D3D">C</mi></math> by finitely many
others. Hausdorff at <math id="S0.I1.i5.p2.m10" class="ltx_Math" alttext="\infty" display="inline"><mi mathcolor="#3D3D3D" mathvariant="normal">∞</mi></math>: use local compactness at <math id="S0.I1.i5.p2.m11" class="ltx_Math" alttext="x" display="inline"><mi mathcolor="#3D3D3D">x</mi></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Prop.</span> <span class="ltx_text ltx_font_bold">(Converse.)</span> If <math id="S0.I1.i6.p1.m1" class="ltx_Math" alttext="X\subset Y" display="inline"><mrow><mi>X</mi><mo>⊂</mo><mi>Y</mi></mrow></math> with <math id="S0.I1.i6.p1.m2" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> compact Hausdorff and <math id="S0.I1.i6.p1.m3" class="ltx_Math" alttext="Y-X" display="inline"><mrow><mi>Y</mi><mo>−</mo><mi>X</mi></mrow></math> a single
point, then <math id="S0.I1.i6.p1.m4" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is locally compact Hausdorff.</p>
</div>
</li>
<li id="S0.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Prop.</span> <span class="ltx_text ltx_font_bold">(Uniqueness.)</span> Any two such <math id="S0.I1.i7.p1.m1" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> are homeomorphic rel <math id="S0.I1.i7.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> —
hence <em class="ltx_emph ltx_font_italic">the</em> one-point compactification.</p>
</div>
</li>
<li id="S0.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i8.p1.m1" class="ltx_Math" alttext="(0,1)^{+}\cong S^{1}" display="inline"><mrow><msup><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow><mo>+</mo></msup><mo>≅</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></math>, hence <math id="S0.I1.i8.p1.m2" class="ltx_Math" alttext="\mathbb{R}^{+}\cong S^{1}" display="inline"><mrow><msup><mi>ℝ</mi><mo>+</mo></msup><mo>≅</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></math>.
  <math id="S0.I1.i8.p1.m3" class="ltx_Math" alttext="B(0,1)^{+}\cong S^{n}" display="inline"><mrow><mrow><mi>B</mi><mo>⁢</mo><msup><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow><mo>+</mo></msup></mrow><mo>≅</mo><msup><mi>S</mi><mi>n</mi></msup></mrow></math>, hence <math id="S0.I1.i8.p1.m4" class="ltx_Math" alttext="(\mathbb{R}^{n})^{+}\cong S^{n}" display="inline"><mrow><msup><mrow><mo stretchy="false">(</mo><msup><mi>ℝ</mi><mi>n</mi></msup><mo stretchy="false">)</mo></mrow><mo>+</mo></msup><mo>≅</mo><msup><mi>S</mi><mi>n</mi></msup></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> <math id="S0.I1.i9.p1.m1" class="ltx_Math" alttext="[0,1]" display="inline"><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></math> is a <em class="ltx_emph ltx_font_italic">different</em> compactification of <math id="S0.I1.i9.p1.m2" class="ltx_Math" alttext="(0,1)" display="inline"><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></math> — it adds two points.
Likewise <math id="S0.I1.i9.p1.m3" class="ltx_Math" alttext="\bar{B}(0,1)" display="inline"><mrow><mover accent="true"><mi>B</mi><mo>¯</mo></mover><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></mrow></math> adds <math id="S0.I1.i9.p1.m4" class="ltx_Math" alttext="S^{n-1}" display="inline"><msup><mi>S</mi><mrow><mi>n</mi><mo>−</mo><mn>1</mn></mrow></msup></math>.</p>
</div>
</li>
<li id="S0.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i10.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i10.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i10.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> Hausdorff. Then <math id="S0.I1.i10.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is locally compact <math id="S0.I1.i10.p1.m4" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> for each <math id="S0.I1.i10.p1.m5" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> and each
neighborhood <math id="S0.I1.i10.p1.m6" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math> of <math id="S0.I1.i10.p1.m7" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> there is a neighborhood <math id="S0.I1.i10.p1.m8" class="ltx_Math" alttext="V" display="inline"><mi>V</mi></math> with
<math id="S0.I1.i10.p1.m9" class="ltx_Math" alttext="x\in V\subset\bar{V}\subset U" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>V</mi><mo>⊂</mo><mover accent="true"><mi>V</mi><mo>¯</mo></mover><mo>⊂</mo><mi>U</mi></mrow></math> and <math id="S0.I1.i10.p1.m10" class="ltx_Math" alttext="\bar{V}" display="inline"><mover accent="true"><mi>V</mi><mo>¯</mo></mover></math> compact.</p>
</div>
<div id="S0.I1.i10.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I1.i10.p2.m1" class="ltx_Math" alttext="\Leftarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇐</mo></math> take <math id="S0.I1.i10.p2.m2" class="ltx_Math" alttext="U=X" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">=</mo><mi mathcolor="#3D3D3D">X</mi></mrow></math>. <math id="S0.I1.i10.p2.m3" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> work inside <math id="S0.I1.i10.p2.m4" class="ltx_Math" alttext="Y=X\cup\{\infty\}" display="inline"><mrow><mi mathcolor="#3D3D3D">Y</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D">∪</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D" mathvariant="normal">∞</mi><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></mrow></math>: separate <math id="S0.I1.i10.p2.m5" class="ltx_Math" alttext="x" display="inline"><mi mathcolor="#3D3D3D">x</mi></math> from the
compact <math id="S0.I1.i10.p2.m6" class="ltx_Math" alttext="K=Y-U" display="inline"><mrow><mi mathcolor="#3D3D3D">K</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">Y</mi><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">U</mi></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i11.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> Open and closed subspaces of a locally compact Hausdorff space are locally compact.</p>
</div>
</li>
<li id="S0.I1.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i12.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> <math id="S0.I1.i12.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is homeomorphic to an open subspace of a compact Hausdorff space
<math id="S0.I1.i12.p1.m2" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> <math id="S0.I1.i12.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is locally compact Hausdorff.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1" class="ltx_section">
<h2 class="ltx_title ltx_font_bold ltx_title_section" style="font-size:144%;color:#1A3873;">1  Countability and Separation Axioms</h2>

<div id="S1.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Goal of the chapter.</span> Urysohn metrization: one countability axiom (second countable)
plus one separation axiom (regular) yield enough maps <math id="S1.p1.m1" class="ltx_Math" alttext="X\to\mathbb{R}" display="inline"><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></math> to embed <math id="S1.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> in a metric space.</p>
</div>
<section id="S1.SS1" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.1  (§30) The countability axioms</h3>

<div id="S1.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S1.I1" class="ltx_itemize">
<li id="S1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> <span class="ltx_text" style="font-size:80%;color:#737373;">[Mk §7]</span> Recall: subsets, finite or countable unions, and finite products of
countable sets are countable. <math id="S1.I1.i1.p1.m1" class="ltx_Math" alttext="\mathbb{Q}" display="inline"><mi>ℚ</mi></math> is countable; <math id="S1.I1.i1.p1.m2" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math> is not.</p>
</div>
</li>
<li id="S1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">First-countable</em>: a countable neighborhood basis at each point.
<em class="ltx_emph ltx_font_italic">Second-countable</em>: a countable basis for the topology.</p>
</div>
</li>
<li id="S1.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Second-countable <math id="S1.I1.i3.p1.m1" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> first-countable</p>
</div>
<div id="S1.I1.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> take <math id="S1.I1.i3.p2.m1" class="ltx_Math" alttext="\mathcal{B}_{x}=\{U\in\mathcal{B}\mid x\in U\}" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic" mathcolor="#3D3D3D">ℬ</mi><mi mathcolor="#3D3D3D">x</mi></msub><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">∈</mo><mi class="ltx_font_mathcaligraphic" mathcolor="#3D3D3D">ℬ</mi></mrow><mo fence="true" lspace="0em" mathcolor="#3D3D3D" rspace="0em">∣</mo><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">U</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></math>.</span></span></p>
</div>
<div id="S1.I1.i3.p3" class="ltx_para">
<p class="ltx_p">Every metric space is first-countable.</p>
</div>
</li>
<li id="S1.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Second-countable: <math id="S1.I1.i4.p1.m1" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math> (intervals <math id="S1.I1.i4.p1.m2" class="ltx_Math" alttext="(a,b)" display="inline"><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></math>, <math id="S1.I1.i4.p1.m3" class="ltx_Math" alttext="a,b\in\mathbb{Q}" display="inline"><mrow><mrow><mi>a</mi><mo>,</mo><mi>b</mi></mrow><mo>∈</mo><mi>ℚ</mi></mrow></math>);
<math id="S1.I1.i4.p1.m4" class="ltx_Math" alttext="\mathbb{R}^{n}" display="inline"><msup><mi>ℝ</mi><mi>n</mi></msup></math> (rational boxes);
even <math id="S1.I1.i4.p1.m5" class="ltx_Math" alttext="\mathbb{R}^{\omega}" display="inline"><msup><mi>ℝ</mi><mi>ω</mi></msup></math> (rational boxes, <math id="S1.I1.i4.p1.m6" class="ltx_Math" alttext="U_{n}=\mathbb{R}" display="inline"><mrow><msub><mi>U</mi><mi>n</mi></msub><mo>=</mo><mi>ℝ</mi></mrow></math> for all but finitely many <math id="S1.I1.i4.p1.m7" class="ltx_Math" alttext="n" display="inline"><mi>n</mi></math>).</p>
</div>
</li>
<li id="S1.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> Not every metric space is second-countable: <math id="S1.I1.i5.p1.m1" class="ltx_Math" alttext="\mathbb{R}^{\omega}" display="inline"><msup><mi>ℝ</mi><mi>ω</mi></msup></math> in the uniform topology.</p>
</div>
</li>
<li id="S1.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> Subspaces, and countable products, of first- (resp. second-) countable spaces are
first- (resp. second-) countable.</p>
</div>
</li>
<li id="S1.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I1.i7.p1.m1" class="ltx_Math" alttext="A\subset X" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>X</mi></mrow></math> is <em class="ltx_emph ltx_font_italic">dense</em> if <math id="S1.I1.i7.p1.m2" class="ltx_Math" alttext="\bar{A}=X" display="inline"><mrow><mover accent="true"><mi>A</mi><mo>¯</mo></mover><mo>=</mo><mi>X</mi></mrow></math>, i.e. every nonempty open set meets <math id="S1.I1.i7.p1.m3" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math>.
<span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I1.i7.p1.m4" class="ltx_Math" alttext="\mathbb{Q}" display="inline"><mi>ℚ</mi></math> dense in <math id="S1.I1.i7.p1.m5" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>.</p>
</div>
</li>
<li id="S1.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i8.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i8.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I1.i8.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> second-countable <math id="S1.I1.i8.p1.m3" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math>
(1) every open cover has a <em class="ltx_emph ltx_font_italic">countable</em> subcover (<em class="ltx_emph ltx_font_italic">Lindelöf</em>);
(2) <math id="S1.I1.i8.p1.m4" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> has a countable dense subset (<em class="ltx_emph ltx_font_italic">separable</em>).</p>
</div>
<div id="S1.I1.i8.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Fix a countable basis <math id="S1.I1.i8.p2.m1" class="ltx_Math" alttext="\{B_{n}\}" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><msub><mi mathcolor="#3D3D3D">B</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></math>. (1) For each <math id="S1.I1.i8.p2.m2" class="ltx_Math" alttext="n" display="inline"><mi mathcolor="#3D3D3D">n</mi></math> pick <math id="S1.I1.i8.p2.m3" class="ltx_Math" alttext="A_{n}\in\mathcal{A}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">A</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D">∈</mo><mi class="ltx_font_mathcaligraphic" mathcolor="#3D3D3D">𝒜</mi></mrow></math> with <math id="S1.I1.i8.p2.m4" class="ltx_Math" alttext="B_{n}\subset A_{n}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">B</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D">⊂</mo><msub><mi mathcolor="#3D3D3D">A</mi><mi mathcolor="#3D3D3D">n</mi></msub></mrow></math>
when possible. (2) Pick <math id="S1.I1.i8.p2.m5" class="ltx_Math" alttext="x_{n}\in B_{n}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D">∈</mo><msub><mi mathcolor="#3D3D3D">B</mi><mi mathcolor="#3D3D3D">n</mi></msub></mrow></math> for each nonempty <math id="S1.I1.i8.p2.m6" class="ltx_Math" alttext="B_{n}" display="inline"><msub><mi mathcolor="#3D3D3D">B</mi><mi mathcolor="#3D3D3D">n</mi></msub></math>.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS2" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.2  (§31–§32) The separation axioms; normal spaces <span class="ltx_text" style="font-size:67%;color:#737373;">[Mk §31–32]</span>
</h3>

<div id="S1.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S1.I2" class="ltx_itemize">
<li id="S1.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> Assume one-point sets are closed (<math id="S1.I2.i1.p1.m1" class="ltx_Math" alttext="T_{1}" display="inline"><msub><mi>T</mi><mn>1</mn></msub></math>). Then:</p>
<ul id="S1.I2.i1.I1" class="ltx_itemize">
<li id="S1.I2.i1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I2.i1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I2.i1.I1.i1.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">regular</em> if a point and a disjoint closed set can be separated by
disjoint open sets;</p>
</div>
</li>
<li id="S1.I2.i1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I2.i1.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i1.I1.i2.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">normal</em> if two disjoint closed sets can be so separated.</p>
</div>
</li>
</ul>
<p class="ltx_p">Normal <math id="S1.I2.i1.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> regular <math id="S1.I2.i1.p1.m3" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> Hausdorff.</p>
</div>
</li>
<li id="S1.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text" style="font-size:80%;color:#737373;">[Mk Thm 32.1]</span> A regular space with a countable basis is normal.
(This is the input to Urysohn metrization.)</p>
</div>
</li>
<li id="S1.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Full treatment, examples and counterexamples: work through Munkres §31–32.</p>
</div>
</li>
</ul>
</div>
</section>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:59:25 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
