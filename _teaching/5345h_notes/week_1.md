---
layout: archive
title: "MATH 5345H ---
 Week 1: Sets, functions, relations, and the standard number systems"
permalink: /teaching/5345h_notes/week_1
author_profile: false
render_with_liquid: false
---
{% raw %}
<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="Sx1" class="ltx_section">
<h2 class="ltx_title ltx_font_bold ltx_title_section" style="font-size:144%;color:#1A3873;">Introduction</h2>

<div id="Sx1.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_rule" style="width:433.6pt;height:0.7pt;background:black;display:inline-block;"> </span></p>
</div>
<div id="Sx1.p2" class="ltx_para ltx_noindent">
<ul id="Sx1.I1" class="ltx_itemize">
<li id="Sx1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">What topology is.</span> From Greek <em class="ltx_emph ltx_font_italic">topos</em> (place) and <em class="ltx_emph ltx_font_italic">logos</em>
(discourse, reason): the study of continuous functions, also called <em class="ltx_emph ltx_font_italic">maps</em>.</p>
</div>
</li>
<li id="Sx1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">The problem.</span> To make sense of “<math id="Sx1.I1.i2.p1.m1" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> is continuous” we need extra
data: continuity says that if <math id="Sx1.I1.i2.p1.m2" class="ltx_Math" alttext="x,y\in X" display="inline"><mrow><mrow><mi>x</mi><mo>,</mo><mi>y</mi></mrow><mo>∈</mo><mi>X</mi></mrow></math> are <em class="ltx_emph ltx_font_italic">close</em>, then <math id="Sx1.I1.i2.p1.m3" class="ltx_Math" alttext="f(x),f(y)" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>,</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> are close.
So <math id="Sx1.I1.i2.p1.m4" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> and <math id="Sx1.I1.i2.p1.m5" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> each need a notion of closeness.</p>
</div>
</li>
<li id="Sx1.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">First answer: metrics.</span> Assign a distance <math id="Sx1.I1.i3.p1.m1" class="ltx_Math" alttext="d(x,y)" display="inline"><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow></math>; call <math id="Sx1.I1.i3.p1.m2" class="ltx_Math" alttext="x,y" display="inline"><mrow><mi>x</mi><mo>,</mo><mi>y</mi></mrow></math> close when
<math id="Sx1.I1.i3.p1.m3" class="ltx_Math" alttext="d(x,y)" display="inline"><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow></math> is small. This gives a <em class="ltx_emph ltx_font_italic">metric space</em> <math id="Sx1.I1.i3.p1.m4" class="ltx_Math" alttext="(X,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math>.</p>
</div>
<div id="Sx1.I1.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">A bare set carries no information about two elements beyond whether they are equal.
A metric gives it a shape — which is why we then say <em class="ltx_emph ltx_font_upright">space</em> rather than set, and
<em class="ltx_emph ltx_font_upright">point</em> rather than element.</span></span></span></p>
</div>
</li>
<li id="Sx1.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Why that is not enough.</span> Metric spaces are special. <em class="ltx_emph ltx_font_italic">Pointwise convergence</em>
of real functions (<math id="Sx1.I1.i4.p1.m1" class="ltx_Math" alttext="f_{n}\to g" display="inline"><mrow><msub><mi>f</mi><mi>n</mi></msub><mo stretchy="false">→</mo><mi>g</mi></mrow></math> iff <math id="Sx1.I1.i4.p1.m2" class="ltx_Math" alttext="f_{n}(t)\to g(t)" display="inline"><mrow><mrow><msub><mi>f</mi><mi>n</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">→</mo><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> for each <math id="Sx1.I1.i4.p1.m3" class="ltx_Math" alttext="t" display="inline"><mi>t</mi></math>) is a useful notion of
closeness, but no metric on the set of real functions expresses it.</p>
</div>
</li>
<li id="Sx1.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><math id="Sx1.I1.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Second answer: open sets.</span> Instead of distances between points, specify which
subsets <math id="Sx1.I1.i5.p1.m2" class="ltx_Math" alttext="U\subset X" display="inline"><mrow><mi>U</mi><mo>⊂</mo><mi>X</mi></mrow></math> are <em class="ltx_emph ltx_font_italic">open</em>. Read this as:</p>
<ul id="Sx1.I1.i5.I1" class="ltx_itemize">
<li id="Sx1.I1.i5.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="Sx1.I1.i5.I1.i1.p1" class="ltx_para ltx_noindent">
<p class="ltx_p">if <math id="Sx1.I1.i5.I1.i1.p1.m1" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> lies in <math id="Sx1.I1.i5.I1.i1.p1.m2" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math> and <math id="Sx1.I1.i5.I1.i1.p1.m3" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math> is open, then every <math id="Sx1.I1.i5.I1.i1.p1.m4" class="ltx_Math" alttext="y" display="inline"><mi>y</mi></math> sufficiently close to <math id="Sx1.I1.i5.I1.i1.p1.m5" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> also
lies in <math id="Sx1.I1.i5.I1.i1.p1.m6" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math>.</p>
</div>
</li>
</ul>
<p class="ltx_p">The collection of all open subsets is the <em class="ltx_emph ltx_font_italic">topology</em> <math id="Sx1.I1.i5.p1.m3" class="ltx_Math" alttext="\mathcal{T}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒯</mi></math> on <math id="Sx1.I1.i5.p1.m4" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>.</p>
</div>
</li>
<li id="Sx1.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Consequence for the course.</span> This approach handles not just elements and
functions but subsets and collections of subsets — hence we begin with a summary of
set theory.</p>
</div>
</li>
<li id="Sx1.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><math id="Sx1.I1.i7.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">The payoff.</span> For topological spaces the definition of continuity is simply:</p>
<ul id="Sx1.I1.i7.I1" class="ltx_itemize">
<li id="Sx1.I1.i7.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="Sx1.I1.i7.I1.i1.p1" class="ltx_para ltx_noindent">
<p class="ltx_p">for each open <math id="Sx1.I1.i7.I1.i1.p1.m1" class="ltx_Math" alttext="V\subset Y" display="inline"><mrow><mi>V</mi><mo>⊂</mo><mi>Y</mi></mrow></math>, the preimage <math id="Sx1.I1.i7.I1.i1.p1.m2" class="ltx_Math" alttext="f^{-1}(V)" display="inline"><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>V</mi><mo stretchy="false">)</mo></mrow></mrow></math> is open in <math id="Sx1.I1.i7.I1.i1.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>.</p>
</div>
</li>
</ul>
<p class="ltx_p">Compare the <math id="Sx1.I1.i7.p1.m2" class="ltx_Math" alttext="(\varepsilon,\delta)" display="inline"><mrow><mo stretchy="false">(</mo><mi>ε</mi><mo>,</mo><mi>δ</mi><mo stretchy="false">)</mo></mrow></math> definition for metric spaces: for each <math id="Sx1.I1.i7.p1.m3" class="ltx_Math" alttext="x\in X" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>X</mi></mrow></math> and each
<math id="Sx1.I1.i7.p1.m4" class="ltx_Math" alttext="\varepsilon&gt;0" display="inline"><mrow><mi>ε</mi><mo>&gt;</mo><mn>0</mn></mrow></math> there is <math id="Sx1.I1.i7.p1.m5" class="ltx_Math" alttext="\delta&gt;0" display="inline"><mrow><mi>δ</mi><mo>&gt;</mo><mn>0</mn></mrow></math> such that <math id="Sx1.I1.i7.p1.m6" class="ltx_Math" alttext="d(x,y)&lt;\delta" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mi>δ</mi></mrow></math> implies
<math id="Sx1.I1.i7.p1.m7" class="ltx_Math" alttext="d(f(x),f(y))&lt;\varepsilon" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>,</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mi>ε</mi></mrow></math>.</p>
</div>
</li>
<li id="Sx1.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i8.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">On the abstraction.</span> The definition of a topological space looks harder than the
subsequent definition of a continuous map. Same pattern as linear algebra: “<math id="Sx1.I1.i8.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is
linear if <math id="Sx1.I1.i8.p1.m2" class="ltx_Math" alttext="f(\lambda x+\mu y)=\lambda f(x)+\mu f(y)" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mrow><mi>λ</mi><mo>⁢</mo><mi>x</mi></mrow><mo>+</mo><mrow><mi>μ</mi><mo>⁢</mo><mi>y</mi></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mi>λ</mi><mo>⁢</mo><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>+</mo><mrow><mi>μ</mi><mo>⁢</mo><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>” is simple, but presupposes the
abstract definition of a real vector space, which in turn presupposes the nine-odd field
axioms for <math id="Sx1.I1.i8.p1.m3" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>.</p>
</div>
<div id="Sx1.I1.i8.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Moral: axiomatisations of the most fundamental objects are general enough to be hard to
grasp at once. It is the <em class="ltx_emph ltx_font_upright">relations</em> between them — continuous maps, linear
transformations — that are concrete. Say this early; it defuses a lot of anxiety.</span></span></span></p>
</div>
</li>
<li id="Sx1.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Programme.</span> After spaces and maps we study the properties such spaces may have:</p>
<ul id="Sx1.I1.i9.I1" class="ltx_itemize">
<li id="Sx1.I1.i9.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="Sx1.I1.i9.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">connected</em> — not a disjoint union of subspaces;</p>
</div>
</li>
<li id="Sx1.I1.i9.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="Sx1.I1.i9.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">compact</em> — not too many open subsets globally;</p>
</div>
</li>
<li id="Sx1.I1.i9.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="Sx1.I1.i9.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Hausdorff</em> — enough open subsets locally.</p>
</div>
</li>
</ul>
<p class="ltx_p">Then the consequences: general forms of the intermediate value theorem, existence of maximal
values, uniqueness of limits, and more.</p>
</div>
</li>
<li id="Sx1.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I1.i10.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> These notes follow J. R. Munkres, <em class="ltx_emph ltx_font_italic">Topology</em>; the <math id="Sx1.I1.i10.p1.m1" class="ltx_Math" alttext="\S" display="inline"><mi mathvariant="normal">§</mi></math>-signs refer to
sections of that book. Course MAT3500/4500, University of Oslo.</p>
</div>
</li>
</ul>
</div>
<div id="Sx1.p3" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Where this leads (worth 5 minutes at the first lecture).</span></p>
</div>
<div id="Sx1.p4" class="ltx_para ltx_noindent">
<ul id="Sx1.I2" class="ltx_itemize">
<li id="Sx1.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Classification of surfaces.</span> Two facts determine a connected compact
<math id="Sx1.I2.i1.p1.m1" class="ltx_Math" alttext="2" display="inline"><mn>2</mn></math>-manifold up to topological equivalence: whether it can be oriented, and how many
handles it has. The number of handles is the <em class="ltx_emph ltx_font_italic">genus</em> <math id="Sx1.I2.i1.p1.m2" class="ltx_Math" alttext="g" display="inline"><mi>g</mi></math>:
sphere <math id="Sx1.I2.i1.p1.m3" class="ltx_Math" alttext="g=0" display="inline"><mrow><mi>g</mi><mo>=</mo><mn>0</mn></mrow></math>, torus <math id="Sx1.I2.i1.p1.m4" class="ltx_Math" alttext="g=1" display="inline"><mrow><mi>g</mi><mo>=</mo><mn>1</mn></mrow></math>, two-handled surface <math id="Sx1.I2.i1.p1.m5" class="ltx_Math" alttext="g=2" display="inline"><mrow><mi>g</mi><mo>=</mo><mn>2</mn></mrow></math>.</p>
</div>
</li>
<li id="Sx1.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Gauss–Bonnet</span> — local geometry against global topology. For a surface <math id="Sx1.I2.i2.p1.m1" class="ltx_Math" alttext="F" display="inline"><mi>F</mi></math> with
a Riemannian metric,</p>
<table id="Sx1.Ex1" class="ltx_equation ltx_eqn_table">

<tbody><tr class="ltx_equation ltx_eqn_row ltx_align_baseline">
<td class="ltx_eqn_cell ltx_eqn_center_padleft"></td>
<td class="ltx_eqn_cell ltx_align_center"><math id="Sx1.Ex1.m1" class="ltx_Math" alttext="\int_{F}K\,dA\;=\;2\pi\cdot\chi,\qquad\chi=2-2g." display="block"><mrow><mrow><mrow><mrow><msub><mo>∫</mo><mi>F</mi></msub><mrow><mi>K</mi><mo lspace="0.170em">⁢</mo><mrow><mo rspace="0em">𝑑</mo><mi>A</mi></mrow></mrow></mrow><mo lspace="0.558em">=</mo><mrow><mrow><mn> 2</mn><mo>⁢</mo><mi>π</mi></mrow><mo lspace="0.222em" rspace="0.222em">⋅</mo><mi>χ</mi></mrow></mrow><mo rspace="2.167em">,</mo><mrow><mi>χ</mi><mo>=</mo><mrow><mn>2</mn><mo>−</mo><mrow><mn>2</mn><mo>⁢</mo><mi>g</mi></mrow></mrow></mrow></mrow><mo lspace="0em">.</mo></mrow></math></td>
<td class="ltx_eqn_cell ltx_eqn_center_padright"></td>
</tr></tbody>
</table>
<p class="ltx_p">Check on the sphere of radius <math id="Sx1.I2.i2.p1.m2" class="ltx_Math" alttext="r" display="inline"><mi>r</mi></math>: curvature <math id="Sx1.I2.i2.p1.m3" class="ltx_Math" alttext="1/r^{2}" display="inline"><mrow><mn>1</mn><mo>/</mo><msup><mi>r</mi><mn>2</mn></msup></mrow></math> everywhere, area <math id="Sx1.I2.i2.p1.m4" class="ltx_Math" alttext="4\pi r^{2}" display="inline"><mrow><mn>4</mn><mo>⁢</mo><mi>π</mi><mo>⁢</mo><msup><mi>r</mi><mn>2</mn></msup></mrow></math>, product
<math id="Sx1.I2.i2.p1.m5" class="ltx_Math" alttext="4\pi=2\pi\cdot 2" display="inline"><mrow><mrow><mn>4</mn><mo>⁢</mo><mi>π</mi></mrow><mo>=</mo><mrow><mrow><mn>2</mn><mo>⁢</mo><mi>π</mi></mrow><mo lspace="0.222em" rspace="0.222em">⋅</mo><mn>2</mn></mrow></mrow></math>, and indeed <math id="Sx1.I2.i2.p1.m6" class="ltx_Math" alttext="\chi(S^{2})=2" display="inline"><mrow><mrow><mi>χ</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msup><mi>S</mi><mn>2</mn></msup><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mn>2</mn></mrow></math>. <span class="ltx_text" style="font-size:80%;color:#737373;">[Mk course MAT4510]</span></p>
</div>
</li>
<li id="Sx1.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="Sx1.I2.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Topology and rational points.</span> For curves over <math id="Sx1.I2.i3.p1.m1" class="ltx_Math" alttext="\mathbb{C}" display="inline"><mi>ℂ</mi></math>:
<math id="Sx1.I2.i3.p1.m2" class="ltx_Math" alttext="x^{2}+y^{2}=1" display="inline"><mrow><mrow><msup><mi>x</mi><mn>2</mn></msup><mo>+</mo><msup><mi>y</mi><mn>2</mn></msup></mrow><mo>=</mo><mn>1</mn></mrow></math> is a sphere and has infinitely many rational solutions;
<math id="Sx1.I2.i3.p1.m3" class="ltx_Math" alttext="x^{5}+y^{2}=1" display="inline"><mrow><mrow><msup><mi>x</mi><mn>5</mn></msup><mo>+</mo><msup><mi>y</mi><mn>2</mn></msup></mrow><mo>=</mo><mn>1</mn></mrow></math> has genus <math id="Sx1.I2.i3.p1.m4" class="ltx_Math" alttext="2" display="inline"><mn>2</mn></math> and only finitely many.
Conjectured by Mordell, proved by Faltings (1983): a rationally defined algebraic curve
of genus <math id="Sx1.I2.i3.p1.m5" class="ltx_Math" alttext="&gt;1" display="inline"><mrow><mi></mi><mo>&gt;</mo><mn>1</mn></mrow></math> has only finitely many rational points.</p>
</div>
<div id="Sx1.I2.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">A topological condition forcing an arithmetic conclusion. Good advertisement for the
subject. <span class="ltx_text" style="font-size:89%;">[Mk courses in algebraic geometry]</span></span></span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1" class="ltx_section">
<h2 class="ltx_title ltx_font_bold ltx_title_section" style="font-size:144%;color:#1A3873;">1  Set Theory and Logic</h2>

<section id="S1.SS1" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.1  (§1) Fundamental concepts</h3>

<div id="S1.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S1.I1" class="ltx_itemize">
<li id="S1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> <math id="S1.I1.i1.p1.m1" class="ltx_Math" alttext="x\in A" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>A</mi></mrow></math>, <math id="S1.I1.i1.p1.m2" class="ltx_Math" alttext="x\notin A" display="inline"><mrow><mi>x</mi><mo>∉</mo><mi>A</mi></mrow></math>. <math id="S1.I1.i1.p1.m3" class="ltx_Math" alttext="D=\{0,1,\dots,9\}" display="inline"><mrow><mi>D</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><mn>9</mn><mo stretchy="false">}</mo></mrow></mrow></math>,  <math id="S1.I1.i1.p1.m4" class="ltx_Math" alttext="P=\{n\in\mathbb{N}\mid n\text{ prime}\}" display="inline"><mrow><mi>P</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mi>n</mi><mo>∈</mo><mi>ℕ</mi></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>n</mi><mo>⁢</mo><mtext> prime</mtext></mrow><mo stretchy="false">}</mo></mrow></mrow></math>,  <math id="S1.I1.i1.p1.m5" class="ltx_Math" alttext="S=\{n^{2}\mid n\in\mathbb{N}\}" display="inline"><mrow><mi>S</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><msup><mi>n</mi><mn>2</mn></msup><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>n</mi><mo>∈</mo><mi>ℕ</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> <math id="S1.I1.i2.p1.m1" class="ltx_Math" alttext="x\neq\{x\}" display="inline"><mrow><mi>x</mi><mo>≠</mo><mrow><mo stretchy="false">{</mo><mi>x</mi><mo stretchy="false">}</mo></mrow></mrow></math>. <math id="S1.I1.i2.p1.m2" class="ltx_Math" alttext="\emptyset=\{\,\}" display="inline"><mrow><mi mathvariant="normal">∅</mi><mo>=</mo><mrow><mo rspace="0.170em" stretchy="false">{</mo><mo stretchy="false">}</mo></mrow></mrow></math> has no elements.</p>
</div>
</li>
<li id="S1.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I1.i3.p1.m1" class="ltx_Math" alttext="A\subset B" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>B</mi></mrow></math> iff <math id="S1.I1.i3.p1.m2" class="ltx_Math" alttext="(x\in A)\Rightarrow(x\in B)" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>x</mi><mo>∈</mo><mi>A</mi></mrow><mo stretchy="false">)</mo></mrow><mo stretchy="false">⇒</mo><mrow><mo stretchy="false">(</mo><mrow><mi>x</mi><mo>∈</mo><mi>B</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></math>. <math id="S1.I1.i3.p1.m3" class="ltx_Math" alttext="A=B" display="inline"><mrow><mi>A</mi><mo>=</mo><mi>B</mi></mrow></math> iff <math id="S1.I1.i3.p1.m4" class="ltx_Math" alttext="A\subset B" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>B</mi></mrow></math> and <math id="S1.I1.i3.p1.m5" class="ltx_Math" alttext="B\subset A" display="inline"><mrow><mi>B</mi><mo>⊂</mo><mi>A</mi></mrow></math>. <math id="S1.I1.i3.p1.m6" class="ltx_Math" alttext="A\subsetneq B" display="inline"><mrow><mi>A</mi><mo>⊊</mo><mi>B</mi></mrow></math>: proper.</p>
</div>
</li>
<li id="S1.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I1.i4.p1.m1" class="ltx_Math" alttext="A\cap B=\{x\mid x\in A\text{ and }x\in B\}" display="inline"><mrow><mrow><mi>A</mi><mo>∩</mo><mi>B</mi></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>x</mi><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>x</mi><mo>∈</mo><mrow><mi>A</mi><mo>⁢</mo><mtext> and </mtext><mo>⁢</mo><mi>x</mi></mrow><mo>∈</mo><mi>B</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>, <math id="S1.I1.i4.p1.m2" class="ltx_Math" alttext="A\cup B=\{x\mid x\in A\text{ or }x\in B\}" display="inline"><mrow><mrow><mi>A</mi><mo>∪</mo><mi>B</mi></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>x</mi><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>x</mi><mo>∈</mo><mrow><mi>A</mi><mo>⁢</mo><mtext> or </mtext><mo>⁢</mo><mi>x</mi></mrow><mo>∈</mo><mi>B</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math> (inclusive or).</p>
</div>
</li>
<li id="S1.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Distributive laws.</span>
<math id="S1.I1.i5.p1.m1" class="ltx_Math" alttext="A\cap(B\cup C)=(A\cap B)\cup(A\cap C)" display="inline"><mrow><mrow><mi>A</mi><mo>∩</mo><mrow><mo stretchy="false">(</mo><mrow><mi>B</mi><mo>∪</mo><mi>C</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>A</mi><mo>∩</mo><mi>B</mi></mrow><mo stretchy="false">)</mo></mrow><mo>∪</mo><mrow><mo stretchy="false">(</mo><mrow><mi>A</mi><mo>∩</mo><mi>C</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>, <math id="S1.I1.i5.p1.m2" class="ltx_Math" alttext="A\cup(B\cap C)=(A\cup B)\cap(A\cup C)" display="inline"><mrow><mrow><mi>A</mi><mo>∪</mo><mrow><mo stretchy="false">(</mo><mrow><mi>B</mi><mo>∩</mo><mi>C</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>A</mi><mo>∪</mo><mi>B</mi></mrow><mo stretchy="false">)</mo></mrow><mo>∩</mo><mrow><mo stretchy="false">(</mo><mrow><mi>A</mi><mo>∪</mo><mi>C</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I1.i6.p1.m1" class="ltx_Math" alttext="A-B=\{x\in A\mid x\notin B\}" display="inline"><mrow><mrow><mi>A</mi><mo>−</mo><mi>B</mi></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mi>x</mi><mo>∈</mo><mi>A</mi></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>x</mi><mo>∉</mo><mi>B</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math> — the complement of <math id="S1.I1.i6.p1.m2" class="ltx_Math" alttext="B" display="inline"><mi>B</mi></math> in <math id="S1.I1.i6.p1.m3" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math>.</p>
</div>
</li>
<li id="S1.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i7.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i7.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">De Morgan.</span>
<math id="S1.I1.i7.p1.m2" class="ltx_Math" alttext="A-(B\cup C)=(A-B)\cap(A-C)" display="inline"><mrow><mrow><mi>A</mi><mo>−</mo><mrow><mo stretchy="false">(</mo><mrow><mi>B</mi><mo>∪</mo><mi>C</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>A</mi><mo>−</mo><mi>B</mi></mrow><mo stretchy="false">)</mo></mrow><mo>∩</mo><mrow><mo stretchy="false">(</mo><mrow><mi>A</mi><mo>−</mo><mi>C</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>, <math id="S1.I1.i7.p1.m3" class="ltx_Math" alttext="A-(B\cap C)=(A-B)\cup(A-C)" display="inline"><mrow><mrow><mi>A</mi><mo>−</mo><mrow><mo stretchy="false">(</mo><mrow><mi>B</mi><mo>∩</mo><mi>C</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>A</mi><mo>−</mo><mi>B</mi></mrow><mo stretchy="false">)</mo></mrow><mo>∪</mo><mrow><mo stretchy="false">(</mo><mrow><mi>A</mi><mo>−</mo><mi>C</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.</p>
</div>
<div id="S1.I1.i7.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Used constantly later: it is what converts the union/intersection axioms for open sets
into the intersection/union statements for closed sets.</span></span></span></p>
</div>
</li>
<li id="S1.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> Informal listings such as <math id="S1.I1.i8.p1.m1" class="ltx_Math" alttext="P=\{2,3,5,\dots\}" display="inline"><mrow><mi>P</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mn>2</mn><mo>,</mo><mn>3</mn><mo>,</mo><mn>5</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo stretchy="false">}</mo></mrow></mrow></math> and <math id="S1.I1.i8.p1.m2" class="ltx_Math" alttext="S=\{1,4,9,\dots\}" display="inline"><mrow><mi>S</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mn>1</mn><mo>,</mo><mn>4</mn><mo>,</mo><mn>9</mn><mo>,</mo><mi mathvariant="normal">…</mi><mo stretchy="false">}</mo></mrow></mrow></math> are used when
the pattern is clear from context.</p>
</div>
</li>
<li id="S1.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> A set whose elements are sets is called a <em class="ltx_emph ltx_font_italic">collection</em> (or family),
written <math id="S1.I1.i9.p1.m1" class="ltx_Math" alttext="\mathcal{A},\mathcal{B},\dots" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">𝒜</mi><mo>,</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>,</mo><mi mathvariant="normal">…</mi></mrow></math>
For a given <math id="S1.I1.i9.p1.m2" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math>, the <em class="ltx_emph ltx_font_italic">power set</em> is <math id="S1.I1.i9.p1.m3" class="ltx_Math" alttext="\mathcal{P}(A)=\{B\mid B\subset A\}" display="inline"><mrow><mrow><mi class="ltx_font_mathcaligraphic">𝒫</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>B</mi><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>B</mi><mo>⊂</mo><mi>A</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>.
E.g. <math id="S1.I1.i9.p1.m4" class="ltx_Math" alttext="\mathcal{P}(\{a,b\})=\{\emptyset,\{a\},\{b\},\{a,b\}\}" display="inline"><mrow><mrow><mi class="ltx_font_mathcaligraphic">𝒫</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">}</mo></mrow></mrow></math>, with four elements.</p>
</div>
</li>
<li id="S1.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i10.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <span class="ltx_text ltx_font_bold">(Students and courses — a collection to keep in mind.)</span>
<math id="S1.I1.i10.p1.m1" class="ltx_math_unparsed" alttext="S=\{s\mid s" display="inline"><mrow><mi>S</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>s</mi><mo lspace="0em" rspace="0.167em">∣</mo><mi>s</mi></mrow></mrow></math> a student<math id="S1.I1.i10.p1.m2" class="ltx_Math" alttext="\}" display="inline"><mo stretchy="false">}</mo></math>, <math id="S1.I1.i10.p1.m3" class="ltx_math_unparsed" alttext="C=\{c\mid c" display="inline"><mrow><mi>C</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>c</mi><mo lspace="0em" rspace="0.167em">∣</mo><mi>c</mi></mrow></mrow></math> a course<math id="S1.I1.i10.p1.m4" class="ltx_Math" alttext="\}" display="inline"><mo stretchy="false">}</mo></math>,
<math id="S1.I1.i10.p1.m5" class="ltx_math_unparsed" alttext="E_{c}=\{s\in S\mid s" display="inline"><mrow><msub><mi>E</mi><mi>c</mi></msub><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>s</mi><mo>∈</mo><mi>S</mi><mo lspace="0em" rspace="0.167em">∣</mo><mi>s</mi></mrow></mrow></math> enrolled in <math id="S1.I1.i10.p1.m6" class="ltx_math_unparsed" alttext="c\}" display="inline"><mrow><mi>c</mi><mo stretchy="false">}</mo></mrow></math>, and <math id="S1.I1.i10.p1.m7" class="ltx_Math" alttext="\mathscr{E}=\{E_{c}\mid c\in C\}" display="inline"><mrow><mi class="ltx_font_mathscript">ℰ</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><msub><mi>E</mi><mi>c</mi></msub><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>c</mi><mo>∈</mo><mi>C</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>.
Elements of <math id="S1.I1.i10.p1.m8" class="ltx_Math" alttext="\mathscr{E}" display="inline"><mi class="ltx_font_mathscript">ℰ</mi></math> are sets of students.</p>
</div>
<div id="S1.I1.i10.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Note <math id="S1.I1.i10.p2.m1" class="ltx_Math" alttext="E_{c}=E_{d}" display="inline"><mrow><msub><mi mathcolor="#737373">E</mi><mi mathcolor="#737373">c</mi></msub><mo mathcolor="#737373">=</mo><msub><mi mathcolor="#737373">E</mi><mi mathcolor="#737373">d</mi></msub></mrow></math> can happen for <math id="S1.I1.i10.p2.m2" class="ltx_Math" alttext="c\neq d" display="inline"><mrow><mi mathcolor="#737373">c</mi><mo mathcolor="#737373">≠</mo><mi mathcolor="#737373">d</mi></mrow></math> (both empty). Worth pointing out before indexed
families in §5, where exactly this failure of injectivity is allowed.</span></span></span></p>
</div>
</li>
<li id="S1.I1.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i11.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> For a collection <math id="S1.I1.i11.p1.m1" class="ltx_Math" alttext="\mathcal{A}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒜</mi></math>:
<math id="S1.I1.i11.p1.m2" class="ltx_Math" alttext="\bigcap_{A\in\mathcal{A}}A=\{x\mid x\in A\ \forall A\in\mathcal{A}\}" display="inline"><mrow><mrow><msub><mo>⋂</mo><mrow><mi>A</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒜</mi></mrow></msub><mi>A</mi></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>x</mi><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>x</mi><mo>∈</mo><mrow><mi>A</mi><mo lspace="0.667em">⁢</mo><mrow><mo rspace="0.167em">∀</mo><mi>A</mi></mrow></mrow><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒜</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>, <math id="S1.I1.i11.p1.m3" class="ltx_Math" alttext="\bigcup_{A\in\mathcal{A}}A=\{x\mid x\in A\text{ for some }A\in\mathcal{A}\}" display="inline"><mrow><mrow><msub><mo>⋃</mo><mrow><mi>A</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒜</mi></mrow></msub><mi>A</mi></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>x</mi><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>x</mi><mo>∈</mo><mrow><mi>A</mi><mo>⁢</mo><mtext> for some </mtext><mo>⁢</mo><mi>A</mi></mrow><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒜</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I1.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i12.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> <math id="S1.I1.i12.p1.m1" class="ltx_Math" alttext="\bigcup_{A\in\emptyset}A=\emptyset" display="inline"><mrow><mrow><msub><mo>⋃</mo><mrow><mi>A</mi><mo>∈</mo><mi mathvariant="normal">∅</mi></mrow></msub><mi>A</mi></mrow><mo>=</mo><mi mathvariant="normal">∅</mi></mrow></math>, but <math id="S1.I1.i12.p1.m2" class="ltx_Math" alttext="\bigcap_{A\in\emptyset}A" display="inline"><mrow><msub><mo>⋂</mo><mrow><mi>A</mi><mo>∈</mo><mi mathvariant="normal">∅</mi></mrow></msub><mi>A</mi></mrow></math> needs an
ambient universal set <math id="S1.I1.i12.p1.m3" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math>; then it is <math id="S1.I1.i12.p1.m4" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math>.</p>
</div>
</li>
<li id="S1.I1.i13" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i13.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> With that collection: <math id="S1.I1.i13.p1.m1" class="ltx_Math" alttext="\bigcap_{E_{c}\in\mathscr{E}}E_{c}" display="inline"><mrow><msub><mo>⋂</mo><mrow><msub><mi>E</mi><mi>c</mi></msub><mo>∈</mo><mi class="ltx_font_mathscript">ℰ</mi></mrow></msub><msub><mi>E</mi><mi>c</mi></msub></mrow></math> = students enrolled in
<em class="ltx_emph ltx_font_italic">every</em> course (probably empty); <math id="S1.I1.i13.p1.m2" class="ltx_Math" alttext="\bigcup_{E_{c}\in\mathscr{E}}E_{c}" display="inline"><mrow><msub><mo>⋃</mo><mrow><msub><mi>E</mi><mi>c</mi></msub><mo>∈</mo><mi class="ltx_font_mathscript">ℰ</mi></mrow></msub><msub><mi>E</mi><mi>c</mi></msub></mrow></math> = the active
students; <math id="S1.I1.i13.p1.m3" class="ltx_Math" alttext="S-\bigcup E_{c}" display="inline"><mrow><mi>S</mi><mo rspace="0.055em">−</mo><mrow><mo>⋃</mo><msub><mi>E</mi><mi>c</mi></msub></mrow></mrow></math> = the inactive ones.</p>
</div>
</li>
<li id="S1.I1.i14" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i14.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I1.i14.p1.m1" class="ltx_Math" alttext="A\times B=\{(x,y)\mid x\in A,\ y\in B\}" display="inline"><mrow><mrow><mi>A</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>B</mi></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mrow><mi>x</mi><mo>∈</mo><mi>A</mi></mrow><mo rspace="0.667em">,</mo><mrow><mi>y</mi><mo>∈</mo><mi>B</mi></mrow></mrow><mo stretchy="false">}</mo></mrow></mrow></math>; <math id="S1.I1.i14.p1.m2" class="ltx_Math" alttext="(x,y)=(x^{\prime},y^{\prime})" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><msup><mi>x</mi><mo>′</mo></msup><mo>,</mo><msup><mi>y</mi><mo>′</mo></msup><mo stretchy="false">)</mo></mrow></mrow></math> iff <math id="S1.I1.i14.p1.m3" class="ltx_Math" alttext="x=x^{\prime}" display="inline"><mrow><mi>x</mi><mo>=</mo><msup><mi>x</mi><mo>′</mo></msup></mrow></math> and <math id="S1.I1.i14.p1.m4" class="ltx_Math" alttext="y=y^{\prime}" display="inline"><mrow><mi>y</mi><mo>=</mo><msup><mi>y</mi><mo>′</mo></msup></mrow></math>.
Distinguish the ordered pair <math id="S1.I1.i14.p1.m5" class="ltx_Math" alttext="(x,y)" display="inline"><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></math> from the set <math id="S1.I1.i14.p1.m6" class="ltx_Math" alttext="\{x,y\}" display="inline"><mrow><mo stretchy="false">{</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">}</mo></mrow></math>.
(If wanted: define <math id="S1.I1.i14.p1.m7" class="ltx_Math" alttext="(x,y)=\{\{x\},\{x,y\}\}" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">{</mo><mi>x</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">}</mo></mrow></mrow></math>.)</p>
</div>
<div id="S1.I1.i14.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I1.i14.p2.m1" class="ltx_Math" alttext="\mathbb{R}^{2}=\mathbb{R}\times\mathbb{R}" display="inline"><mrow><msup><mi mathcolor="#737373">ℝ</mi><mn mathcolor="#737373">2</mn></msup><mo mathcolor="#737373">=</mo><mrow><mi mathcolor="#737373">ℝ</mi><mo lspace="0.222em" mathcolor="#737373" rspace="0.222em">×</mo><mi mathcolor="#737373">ℝ</mi></mrow></mrow></math><span class="ltx_text ltx_font_italic"> read as horizontal and vertical coordinates is Descartes’ analytic
geometry, as against Euclid’s synthetic approach.</span></span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS2" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.2  (§2) Functions</h3>

<div id="S1.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S1.I2" class="ltx_itemize">
<li id="S1.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I2.i1.p1.m1" class="ltx_Math" alttext="f\colon A\to B" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>A</mi><mo stretchy="false">→</mo><mi>B</mi></mrow></mrow></math>: to each <math id="S1.I2.i1.p1.m2" class="ltx_Math" alttext="x\in A" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>A</mi></mrow></math> a unique <math id="S1.I2.i1.p1.m3" class="ltx_Math" alttext="f(x)\in B" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>∈</mo><mi>B</mi></mrow></math>.
<math id="S1.I2.i1.p1.m4" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> = domain, <math id="S1.I2.i1.p1.m5" class="ltx_Math" alttext="B" display="inline"><mi>B</mi></math> = range (codomain).</p>
</div>
</li>
<li id="S1.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> The rule may be given by a procedure, e.g. for <math id="S1.I2.i2.p1.m1" class="ltx_Math" alttext="x\in\mathbb{N}" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>ℕ</mi></mrow></math></p>
<table id="S1.Ex2" class="ltx_equation ltx_eqn_table">

<tbody><tr class="ltx_equation ltx_eqn_row ltx_align_baseline">
<td class="ltx_eqn_cell ltx_eqn_center_padleft"></td>
<td class="ltx_eqn_cell ltx_align_center"><math id="S1.Ex2.m1" class="ltx_Math" alttext="f(x)=\begin{cases}3x+1&amp;x\text{ odd}\\
x/2&amp;x\text{ even,}\end{cases}" display="block"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo>{</mo><mtable columnspacing="5pt" displaystyle="true" rowspacing="0pt"><mtr><mtd class="ltx_align_left" columnalign="left"><mrow><mrow><mn>3</mn><mo>⁢</mo><mi>x</mi></mrow><mo>+</mo><mn>1</mn></mrow></mtd><mtd class="ltx_align_left" columnalign="left"><mrow><mi>x</mi><mo>⁢</mo><mtext> odd</mtext></mrow></mtd></mtr><mtr><mtd class="ltx_align_left" columnalign="left"><mrow><mi>x</mi><mo>/</mo><mn>2</mn></mrow></mtd><mtd class="ltx_align_left" columnalign="left"><mrow><mi>x</mi><mo>⁢</mo><mtext> even,</mtext></mrow></mtd></mtr></mtable></mrow></mrow></math></td>
<td class="ltx_eqn_cell ltx_eqn_center_padright"></td>
</tr></tbody>
</table>
<p class="ltx_p">but no such assumption is made in general.</p>
</div>
</li>
<li id="S1.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> Graph <math id="S1.I2.i3.p1.m1" class="ltx_Math" alttext="\Gamma_{f}=\{(x,f(x))\}\subset A\times B" display="inline"><mrow><msub><mi mathvariant="normal">Γ</mi><mi>f</mi></msub><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow><mo stretchy="false">}</mo></mrow><mo>⊂</mo><mrow><mi>A</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>B</mi></mrow></mrow></math>.
Characterised by: for each <math id="S1.I2.i3.p1.m2" class="ltx_Math" alttext="x\in A" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>A</mi></mrow></math> exactly one <math id="S1.I2.i3.p1.m3" class="ltx_Math" alttext="y" display="inline"><mi>y</mi></math> with <math id="S1.I2.i3.p1.m4" class="ltx_Math" alttext="(x,y)\in\Gamma" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow><mo>∈</mo><mi mathvariant="normal">Γ</mi></mrow></math>.</p>
</div>
<div id="S1.I2.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">So a function may be <em class="ltx_emph ltx_font_upright">defined</em> as a triple <math id="S1.I2.i3.p2.m1" class="ltx_Math" alttext="(A,B,\Gamma)" display="inline"><mrow><mo mathcolor="#737373" stretchy="false">(</mo><mi mathcolor="#737373">A</mi><mo mathcolor="#737373">,</mo><mi mathcolor="#737373">B</mi><mo mathcolor="#737373">,</mo><mi mathcolor="#737373" mathvariant="normal">Γ</mi><mo mathcolor="#737373" stretchy="false">)</mo></mrow></math> — domain and codomain are
part of the data, not just the rule.</span></span></span></p>
</div>
</li>
<li id="S1.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> Image <math id="S1.I2.i4.p1.m1" class="ltx_Math" alttext="f(A)=\{f(x)\mid x\in A\}\subset B" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>x</mi><mo>∈</mo><mi>A</mi></mrow><mo stretchy="false">}</mo></mrow><mo>⊂</mo><mi>B</mi></mrow></math>. Restriction <math id="S1.I2.i4.p1.m2" class="ltx_Math" alttext="f|S\colon S\to B" display="inline"><mrow><mrow><mi>f</mi><mo fence="false">|</mo><mi>S</mi></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>S</mi><mo stretchy="false">→</mo><mi>B</mi></mrow></mrow></math>. Corestriction <math id="S1.I2.i4.p1.m3" class="ltx_Math" alttext="A\to T" display="inline"><mrow><mi>A</mi><mo stretchy="false">→</mo><mi>T</mi></mrow></math>, defined only when <math id="S1.I2.i4.p1.m4" class="ltx_Math" alttext="f(A)\subset T" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mi>T</mi></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">injective</em>: <math id="S1.I2.i5.p1.m1" class="ltx_Math" alttext="f(x)=f(y)\Rightarrow x=y" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">⇒</mo><mi>x</mi><mo>=</mo><mi>y</mi></mrow></math>. <em class="ltx_emph ltx_font_italic">surjective</em>: <math id="S1.I2.i5.p1.m2" class="ltx_Math" alttext="f(A)=B" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mi>B</mi></mrow></math>. <em class="ltx_emph ltx_font_italic">bijective</em>: both; then <math id="S1.I2.i5.p1.m3" class="ltx_Math" alttext="f^{-1}\colon B\to A" display="inline"><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>B</mi><mo stretchy="false">→</mo><mi>A</mi></mrow></mrow></math> exists, with
<math id="S1.I2.i5.p1.m4" class="ltx_Math" alttext="f^{-1}(y)=x" display="inline"><mrow><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mi>x</mi></mrow></math> exactly when <math id="S1.I2.i5.p1.m5" class="ltx_Math" alttext="y=f(x)" display="inline"><mrow><mi>y</mi><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> <math id="S1.I2.i6.p1.m1" class="ltx_Math" alttext="\Gamma_{f^{-1}}=\{(y,x)\in B\times A\mid(x,y)\in\Gamma_{f}\}" display="inline"><mrow><msub><mi mathvariant="normal">Γ</mi><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup></msub><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mrow><mo stretchy="false">(</mo><mi>y</mi><mo>,</mo><mi>x</mi><mo stretchy="false">)</mo></mrow><mo>∈</mo><mrow><mi>B</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>A</mi></mrow></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow><mo>∈</mo><msub><mi mathvariant="normal">Γ</mi><mi>f</mi></msub></mrow><mo stretchy="false">}</mo></mrow></mrow></math>: the graph of <math id="S1.I2.i6.p1.m2" class="ltx_Math" alttext="f^{-1}" display="inline"><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup></math>
is the graph of <math id="S1.I2.i6.p1.m3" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> with the two factors interchanged.</p>
</div>
</li>
<li id="S1.I2.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> If <math id="S1.I2.i7.p1.m1" class="ltx_Math" alttext="f|S" display="inline"><mrow><mi>f</mi><mo fence="false">|</mo><mi>S</mi></mrow></math> is injective and <math id="S1.I2.i7.p1.m2" class="ltx_Math" alttext="T=f(S)" display="inline"><mrow><mi>T</mi><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>, the resulting <math id="S1.I2.i7.p1.m3" class="ltx_Math" alttext="g\colon S\to T" display="inline"><mrow><mi>g</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>S</mi><mo stretchy="false">→</mo><mi>T</mi></mrow></mrow></math> is a bijection
with an inverse <math id="S1.I2.i7.p1.m4" class="ltx_Math" alttext="g^{-1}\colon T\to S" display="inline"><mrow><msup><mi>g</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>T</mi><mo stretchy="false">→</mo><mi>S</mi></mrow></mrow></math>, even when <math id="S1.I2.i7.p1.m5" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> itself is not invertible.</p>
</div>
</li>
<li id="S1.I2.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I2.i8.p1.m1" class="ltx_Math" alttext="(g\circ f)(x)=g(f(x))" display="inline"><mrow><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>g</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>f</mi></mrow><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>. Unital, associative, <em class="ltx_emph ltx_font_italic">not</em> commutative.
<math id="S1.I2.i8.p1.m2" class="ltx_Math" alttext="(g\circ f)^{-1}=f^{-1}\circ g^{-1}" display="inline"><mrow><msup><mrow><mo stretchy="false">(</mo><mrow><mi>g</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>f</mi></mrow><mo stretchy="false">)</mo></mrow><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>=</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo lspace="0.222em" rspace="0.222em">∘</mo><msup><mi>g</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">Inclusion</em> <math id="S1.I2.i9.p1.m1" class="ltx_Math" alttext="i\colon S\to A" display="inline"><mrow><mi>i</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>S</mi><mo stretchy="false">→</mo><mi>A</mi></mrow></mrow></math>, <math id="S1.I2.i9.p1.m2" class="ltx_Math" alttext="i(x)=x" display="inline"><mrow><mrow><mi>i</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mi>x</mi></mrow></math> for <math id="S1.I2.i9.p1.m3" class="ltx_Math" alttext="x\in S" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>S</mi></mrow></math>. Not the identity unless
<math id="S1.I2.i9.p1.m4" class="ltx_Math" alttext="S=A" display="inline"><mrow><mi>S</mi><mo>=</mo><mi>A</mi></mrow></math>. Then <math id="S1.I2.i9.p1.m5" class="ltx_Math" alttext="f\circ i=f|S" display="inline"><mrow><mrow><mi>f</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>i</mi></mrow><mo>=</mo><mrow><mi>f</mi><mo fence="false">|</mo><mi>S</mi></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Dually, for <math id="S1.I2.i10.p1.m1" class="ltx_Math" alttext="T\subset B" display="inline"><mrow><mi>T</mi><mo>⊂</mo><mi>B</mi></mrow></math> with <math id="S1.I2.i10.p1.m2" class="ltx_Math" alttext="f(A)\subset T" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mi>T</mi></mrow></math> and <math id="S1.I2.i10.p1.m3" class="ltx_Math" alttext="j\colon T\to B" display="inline"><mrow><mi>j</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>T</mi><mo stretchy="false">→</mo><mi>B</mi></mrow></mrow></math> the inclusion,
the corestriction <math id="S1.I2.i10.p1.m4" class="ltx_Math" alttext="g\colon A\to T" display="inline"><mrow><mi>g</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>A</mi><mo stretchy="false">→</mo><mi>T</mi></mrow></mrow></math> is characterised by <math id="S1.I2.i10.p1.m5" class="ltx_Math" alttext="j\circ g=f" display="inline"><mrow><mrow><mi>j</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>g</mi></mrow><mo>=</mo><mi>f</mi></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i11.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> Induced maps on power sets:
<math id="S1.I2.i11.p1.m1" class="ltx_Math" alttext="f\colon\mathcal{P}(A)\to\mathcal{P}(B)" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi class="ltx_font_mathcaligraphic">𝒫</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">→</mo><mrow><mi class="ltx_font_mathcaligraphic">𝒫</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>B</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>, <math id="S1.I2.i11.p1.m2" class="ltx_Math" alttext="f^{-1}\colon\mathcal{P}(B)\to\mathcal{P}(A)" display="inline"><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi class="ltx_font_mathcaligraphic">𝒫</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>B</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">→</mo><mrow><mi class="ltx_font_mathcaligraphic">𝒫</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>.</p>
</div>
<div id="S1.I2.i11.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">Same symbol, different domain — flag the abuse of notation once and move on.</span></span></span></p>
</div>
</li>
</ul>
</div>
<div id="S1.SS2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Images vs. preimages</span> — the asymmetry to put on the board:</p>
</div>
<div id="S1.SS2.p3" class="ltx_para ltx_noindent">
<ul id="S1.I3" class="ltx_itemize">
<li id="S1.I3.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Images</span> (only partly well behaved). For <math id="S1.I3.i1.p1.m1" class="ltx_Math" alttext="S,T\subset A" display="inline"><mrow><mrow><mi>S</mi><mo>,</mo><mi>T</mi></mrow><mo>⊂</mo><mi>A</mi></mrow></math>:</p>
<ul id="S1.I3.i1.I1" class="ltx_itemize">
<li id="S1.I3.i1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I3.i1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i1.I1.i1.p1.m1" class="ltx_Math" alttext="S\subset T\Rightarrow f(S)\subset f(T)" display="inline"><mrow><mi>S</mi><mo>⊂</mo><mi>T</mi><mo stretchy="false">⇒</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>T</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math></p>
</div>
</li>
<li id="S1.I3.i1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I3.i1.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i1.I1.i2.p1.m1" class="ltx_Math" alttext="f(S\cup T)=f(S)\cup f(T)" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>S</mi><mo>∪</mo><mi>T</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow><mo>∪</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>T</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math></p>
</div>
</li>
<li id="S1.I3.i1.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I3.i1.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i1.I1.i3.p1.m1" class="ltx_Math" alttext="f(S\cap T)\subset f(S)\cap f(T)" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>S</mi><mo>∩</mo><mi>T</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow><mo>∩</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>T</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>  — equality if <math id="S1.I3.i1.I1.i3.p1.m2" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> injective</p>
</div>
</li>
<li id="S1.I3.i1.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I3.i1.I1.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I3.i1.I1.i4.p1.m1" class="ltx_Math" alttext="f(T)-f(S)\subset f(T-S)" display="inline"><mrow><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>T</mi><mo stretchy="false">)</mo></mrow></mrow><mo>−</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow></mrow><mo>⊂</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>T</mi><mo>−</mo><mi>S</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>  — equality if <math id="S1.I3.i1.I1.i4.p1.m2" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> injective</p>
</div>
</li>
</ul>
</div>
</li>
<li id="S1.I3.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Preimages</span> (all four are equalities). For <math id="S1.I3.i2.p1.m2" class="ltx_Math" alttext="S,T\subset B" display="inline"><mrow><mrow><mi>S</mi><mo>,</mo><mi>T</mi></mrow><mo>⊂</mo><mi>B</mi></mrow></math>:</p>
<ul id="S1.I3.i2.I1" class="ltx_itemize">
<li id="S1.I3.i2.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I3.i2.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i2.I1.i1.p1.m1" class="ltx_Math" alttext="S\subset T\Rightarrow f^{-1}(S)\subset f^{-1}(T)" display="inline"><mrow><mi>S</mi><mo>⊂</mo><mi>T</mi><mo stretchy="false">⇒</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>T</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math></p>
</div>
</li>
<li id="S1.I3.i2.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I3.i2.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i2.I1.i2.p1.m1" class="ltx_Math" alttext="f^{-1}(S\cup T)=f^{-1}(S)\cup f^{-1}(T)" display="inline"><mrow><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>S</mi><mo>∪</mo><mi>T</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow><mo>∪</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>T</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math></p>
</div>
</li>
<li id="S1.I3.i2.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I3.i2.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i2.I1.i3.p1.m1" class="ltx_Math" alttext="f^{-1}(S\cap T)=f^{-1}(S)\cap f^{-1}(T)" display="inline"><mrow><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>S</mi><mo>∩</mo><mi>T</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow><mo>∩</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>T</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math></p>
</div>
</li>
<li id="S1.I3.i2.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I3.i2.I1.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I3.i2.I1.i4.p1.m1" class="ltx_Math" alttext="f^{-1}(S-T)=f^{-1}(S)-f^{-1}(T)" display="inline"><mrow><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>S</mi><mo>−</mo><mi>T</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow><mo>−</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>T</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math></p>
</div>
</li>
</ul>
</div>
</li>
<li id="S1.I3.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Round trips.</span> <math id="S1.I3.i3.p1.m1" class="ltx_Math" alttext="S\subset f^{-1}(f(S))" display="inline"><mrow><mi>S</mi><mo>⊂</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>S</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math> and <math id="S1.I3.i3.p1.m2" class="ltx_Math" alttext="f(f^{-1}(T))\subset T" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>T</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mi>T</mi></mrow></math>.</p>
</div>
<div id="S1.I3.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">This table is the whole reason continuity will be defined by preimages, not images.
Point forward to it now; refer back in §18.</span></span></span></p>
</div>
</li>
</ul>
</div>
</section>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:58:50 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>


{% endraw %}
