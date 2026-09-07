---
layout: archive
title: "MATH 5345H --- Week 9: Compact subsets of Euclidean space; Heine-Borel"
permalink: /teaching/5345h_notes/week_9
author_profile: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S0.SS1" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.1  (§27) Compact subspaces of the real line</h2>

<div id="S0.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S0.I1" class="ltx_itemize">
<li id="S0.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i1.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> Every closed interval <math id="S0.I1.i1.p1.m2" class="ltx_Math" alttext="[a,b]\subset\mathbb{R}" display="inline"><mrow><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">]</mo></mrow><mo>⊂</mo><mi>ℝ</mi></mrow></math> is compact.</p>
</div>
<div id="S0.I1.i1.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Let <math id="S0.I1.i1.p2.m1" class="ltx_Math" alttext="S=\{x\in[a,b]\mid[a,x]\text{ has a finite subcover}\}" display="inline"><mrow><mi mathcolor="#3D3D3D">S</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">∈</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow></mrow><mo fence="true" lspace="0em" mathcolor="#3D3D3D" rspace="0em">∣</mo><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow><mo>⁢</mo><mtext mathcolor="#3D3D3D"> has a finite subcover</mtext></mrow><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></math>, <math id="S0.I1.i1.p2.m2" class="ltx_Math" alttext="c=\sup S" display="inline"><mrow><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D" rspace="0.1389em">=</mo><mrow><mo lspace="0.1389em" mathcolor="#3D3D3D" rspace="0.167em">sup</mo><mi mathcolor="#3D3D3D">S</mi></mrow></mrow></math>.
Show <math id="S0.I1.i1.p2.m3" class="ltx_Math" alttext="c\in S" display="inline"><mrow><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">S</mi></mrow></math> (an open <math id="S0.I1.i1.p2.m4" class="ltx_Math" alttext="U_{\beta}\ni c" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">β</mi></msub><mo mathcolor="#3D3D3D">∋</mo><mi mathcolor="#3D3D3D">c</mi></mrow></math> reaches back past some <math id="S0.I1.i1.p2.m5" class="ltx_Math" alttext="x\in S" display="inline"><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">S</mi></mrow></math>), then <math id="S0.I1.i1.p2.m6" class="ltx_Math" alttext="c=b" display="inline"><mrow><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D">=</mo><mi mathcolor="#3D3D3D">b</mi></mrow></math>
(otherwise <math id="S0.I1.i1.p2.m7" class="ltx_Math" alttext="U_{\beta}" display="inline"><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">β</mi></msub></math> reaches past <math id="S0.I1.i1.p2.m8" class="ltx_Math" alttext="c" display="inline"><mi mathcolor="#3D3D3D">c</mi></math>). Least upper bound property again.</span></span></p>
</div>
</li>
<li id="S0.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i2.p1.m2" class="ltx_Math" alttext="Y\subset\mathbb{R}^{n}" display="inline"><mrow><mi>Y</mi><mo>⊂</mo><msup><mi>ℝ</mi><mi>n</mi></msup></mrow></math> is compact <math id="S0.I1.i2.p1.m3" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> <math id="S0.I1.i2.p1.m4" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> is closed and bounded.</p>
</div>
<div id="S0.I1.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I1.i2.p2.m1" class="ltx_Math" alttext="\Leftarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇐</mo></math>: <math id="S0.I1.i2.p2.m2" class="ltx_Math" alttext="Y" display="inline"><mi mathcolor="#3D3D3D">Y</mi></math> is closed inside some <math id="S0.I1.i2.p2.m3" class="ltx_Math" alttext="\prod[a_{i},b_{i}]" display="inline"><mrow><mo mathcolor="#3D3D3D" rspace="0em">∏</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><msub><mi mathcolor="#3D3D3D">a</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">b</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow></mrow></math>.
<math id="S0.I1.i2.p2.m4" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math>: cover by the cubes <math id="S0.I1.i2.p2.m5" class="ltx_Math" alttext="(-M,M)^{n}" display="inline"><msup><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">M</mi></mrow><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">M</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mi mathcolor="#3D3D3D">n</mi></msup></math>; and <math id="S0.I1.i2.p2.m6" class="ltx_Math" alttext="\mathbb{R}^{n}" display="inline"><msup><mi mathcolor="#3D3D3D">ℝ</mi><mi mathcolor="#3D3D3D">n</mi></msup></math> Hausdorff gives closed.</span></span></p>
</div>
</li>
<li id="S0.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i3.p1.m1" class="ltx_Math" alttext="(a,b)" display="inline"><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></math>, <math id="S0.I1.i3.p1.m2" class="ltx_Math" alttext="[a,b)" display="inline"><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></math>, <math id="S0.I1.i3.p1.m3" class="ltx_Math" alttext="(a,b]" display="inline"><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">]</mo></mrow></math> are not closed in <math id="S0.I1.i3.p1.m4" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>, hence not compact.</p>
</div>
</li>
<li id="S0.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i4.p1.m1" class="ltx_Math" alttext="f\colon[0,1]\to S^{1}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow><mo stretchy="false">→</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></mrow></math> is a quotient map (<math id="S0.I1.i4.p1.m2" class="ltx_Math" alttext="[0,1]" display="inline"><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></math> compact, <math id="S0.I1.i4.p1.m3" class="ltx_Math" alttext="S^{1}" display="inline"><msup><mi>S</mi><mn>1</mn></msup></math> Hausdorff);
likewise <math id="S0.I1.i4.p1.m4" class="ltx_Math" alttext="f\times f\colon[0,1]^{2}\to T^{2}" display="inline"><mrow><mrow><mi>f</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>f</mi></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msup><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow><mn>2</mn></msup><mo stretchy="false">→</mo><msup><mi>T</mi><mn>2</mn></msup></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Extreme value theorem.)</span> <math id="S0.I1.i5.p1.m2" class="ltx_Math" alttext="f\colon X\to\mathbb{R}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></mrow></math> continuous, <math id="S0.I1.i5.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> compact
<math id="S0.I1.i5.p1.m4" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> there are <math id="S0.I1.i5.p1.m5" class="ltx_Math" alttext="c,d\in X" display="inline"><mrow><mrow><mi>c</mi><mo>,</mo><mi>d</mi></mrow><mo>∈</mo><mi>X</mi></mrow></math> with <math id="S0.I1.i5.p1.m6" class="ltx_Math" alttext="f(c)\leq f(x)\leq f(d)" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>c</mi><mo stretchy="false">)</mo></mrow></mrow><mo>≤</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>≤</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> for all <math id="S0.I1.i5.p1.m7" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math>.</p>
</div>
<div id="S0.I1.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I1.i5.p2.m1" class="ltx_Math" alttext="f(X)" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> compact <math id="S0.I1.i5.p2.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> closed and bounded <math id="S0.I1.i5.p2.m3" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> contains its inf and sup.</span></span></p>
</div>
</li>
<li id="S0.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i6.p1.m1" class="ltx_Math" alttext="d(x,A)=\inf\{d(x,a)\mid a\in A\}" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo rspace="0.1389em">=</mo><mrow><mo lspace="0.1389em" rspace="0em">inf</mo><mrow><mo stretchy="false">{</mo><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>a</mi><mo stretchy="false">)</mo></mrow></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>a</mi><mo>∈</mo><mi>A</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></mrow></math>; <math id="S0.I1.i6.p1.m2" class="ltx_Math" alttext="\operatorname{diam}(A)=\sup\{d(a,b)\mid a,b\in A\}" display="inline"><mrow><mrow><mi>diam</mi><mo>⁡</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo rspace="0.1389em">=</mo><mrow><mo lspace="0.1389em" rspace="0em">sup</mo><mrow><mo stretchy="false">{</mo><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mrow><mi>a</mi><mo>,</mo><mi>b</mi></mrow><mo>∈</mo><mi>A</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I1.i7.p1.m1" class="ltx_Math" alttext="x\mapsto d(x,A)" display="inline"><mrow><mi>x</mi><mo stretchy="false">↦</mo><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> is continuous; indeed <math id="S0.I1.i7.p1.m2" class="ltx_Math" alttext="|d(x,A)-d(y,A)|\leq d(x,y)" display="inline"><mrow><mrow><mo stretchy="false">|</mo><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow><mo>−</mo><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo>,</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow></mrow><mo stretchy="false">|</mo></mrow><mo>≤</mo><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i8.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i8.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <span class="ltx_text ltx_font_bold">(Lebesgue number lemma.)</span> <math id="S0.I1.i8.p1.m2" class="ltx_Math" alttext="\mathcal{A}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒜</mi></math> an open cover of a compact metric space
<math id="S0.I1.i8.p1.m3" class="ltx_Math" alttext="(X,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> <math id="S0.I1.i8.p1.m4" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> there is <math id="S0.I1.i8.p1.m5" class="ltx_Math" alttext="\delta&gt;0" display="inline"><mrow><mi>δ</mi><mo>&gt;</mo><mn>0</mn></mrow></math> such that every <math id="S0.I1.i8.p1.m6" class="ltx_Math" alttext="B\subset X" display="inline"><mrow><mi>B</mi><mo>⊂</mo><mi>X</mi></mrow></math> with
<math id="S0.I1.i8.p1.m7" class="ltx_Math" alttext="\operatorname{diam}(B)&lt;\delta" display="inline"><mrow><mrow><mi>diam</mi><mo>⁡</mo><mrow><mo stretchy="false">(</mo><mi>B</mi><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mi>δ</mi></mrow></math> lies in a single element of <math id="S0.I1.i8.p1.m8" class="ltx_Math" alttext="\mathcal{A}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒜</mi></math>.</p>
</div>
<div id="S0.I1.i8.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Take a finite subcover <math id="S0.I1.i8.p2.m1" class="ltx_Math" alttext="U_{1},\dots,U_{n}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">U</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D" mathvariant="normal">…</mi><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">n</mi></msub></mrow></math>, put <math id="S0.I1.i8.p2.m2" class="ltx_Math" alttext="C_{i}=X-U_{i}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">C</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D">−</mo><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">i</mi></msub></mrow></mrow></math> and
<math id="S0.I1.i8.p2.m3" class="ltx_Math" alttext="f(x)=\frac{1}{n}\sum_{i}d(x,C_{i})" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mi mathcolor="#3D3D3D">n</mi></mfrac><mo>⁢</mo><mrow><msub><mo mathcolor="#3D3D3D">∑</mo><mi mathcolor="#3D3D3D">i</mi></msub><mrow><mi mathcolor="#3D3D3D">d</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">C</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></mrow></mrow></math>. Then <math id="S0.I1.i8.p2.m4" class="ltx_Math" alttext="f&gt;0" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">&gt;</mo><mn mathcolor="#3D3D3D">0</mn></mrow></math>; let <math id="S0.I1.i8.p2.m5" class="ltx_Math" alttext="\delta=\min f&gt;0" display="inline"><mrow><mi mathcolor="#3D3D3D">δ</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">min</mi><mo lspace="0.167em">⁡</mo><mi mathcolor="#3D3D3D">f</mi></mrow><mo mathcolor="#3D3D3D">&gt;</mo><mn mathcolor="#3D3D3D">0</mn></mrow></math> by the extreme value theorem.</span></span></p>
</div>
</li>
<li id="S0.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i9.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is <em class="ltx_emph ltx_font_italic">uniformly continuous</em> if <math id="S0.I1.i9.p1.m2" class="ltx_Math" alttext="\forall\varepsilon&gt;0\ \exists\delta&gt;0" display="inline"><mrow><mrow><mo rspace="0.167em">∀</mo><mi>ε</mi></mrow><mo>&gt;</mo><mrow><mn>0</mn><mo lspace="0.667em">⁢</mo><mrow><mo rspace="0.167em">∃</mo><mi>δ</mi></mrow></mrow><mo>&gt;</mo><mn>0</mn></mrow></math>:
<math id="S0.I1.i9.p1.m3" class="ltx_Math" alttext="d_{X}(x,x^{\prime})&lt;\delta\Rightarrow d_{Y}(f(x),f(x^{\prime}))&lt;\varepsilon" display="inline"><mrow><mrow><msub><mi>d</mi><mi>X</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><msup><mi>x</mi><mo>′</mo></msup><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mi>δ</mi><mo stretchy="false">⇒</mo><mrow><msub><mi>d</mi><mi>Y</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>,</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msup><mi>x</mi><mo>′</mo></msup><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mi>ε</mi></mrow></math> — one <math id="S0.I1.i9.p1.m4" class="ltx_Math" alttext="\delta" display="inline"><mi>δ</mi></math> for all points.</p>
</div>
</li>
<li id="S0.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i10.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i10.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i10.p1.m2" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> continuous, <math id="S0.I1.i10.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> compact metric <math id="S0.I1.i10.p1.m4" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> <math id="S0.I1.i10.p1.m5" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is uniformly continuous.</p>
</div>
<div id="S0.I1.i10.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Take a Lebesgue number for <math id="S0.I1.i10.p2.m1" class="ltx_Math" alttext="\{f^{-1}(B(y,\varepsilon/2))\}_{y\in Y}" display="inline"><msub><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">B</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">y</mi><mo mathcolor="#3D3D3D">,</mo><mrow><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D">/</mo><mn mathcolor="#3D3D3D">2</mn></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow><mrow><mi mathcolor="#3D3D3D">y</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">Y</mi></mrow></msub></math>.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S0.SS2" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.2  (§28) Limit point compactness</h2>

<div id="S0.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S0.I2" class="ltx_itemize">
<li id="S0.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I2.i1.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">limit point compact</em> if every infinite subset has a limit point.</p>
</div>
</li>
<li id="S0.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> Compact <math id="S0.I2.i2.p1.m1" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> limit point compact.</p>
</div>
<div id="S0.I2.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> If <math id="S0.I2.i2.p2.m1" class="ltx_Math" alttext="A" display="inline"><mi mathcolor="#3D3D3D">A</mi></math> has no limit point, <math id="S0.I2.i2.p2.m2" class="ltx_Math" alttext="A" display="inline"><mi mathcolor="#3D3D3D">A</mi></math> is closed and each <math id="S0.I2.i2.p2.m3" class="ltx_Math" alttext="p\in A" display="inline"><mrow><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">A</mi></mrow></math> has <math id="S0.I2.i2.p2.m4" class="ltx_Math" alttext="U_{p}" display="inline"><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">p</mi></msub></math> with
<math id="S0.I2.i2.p2.m5" class="ltx_Math" alttext="A\cap U_{p}=\{p\}" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">∩</mo><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">p</mi></msub></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></math>. Cover by <math id="S0.I2.i2.p2.m6" class="ltx_Math" alttext="X-A" display="inline"><mrow><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">A</mi></mrow></math> and the <math id="S0.I2.i2.p2.m7" class="ltx_Math" alttext="U_{p}" display="inline"><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">p</mi></msub></math>; finiteness forces <math id="S0.I2.i2.p2.m8" class="ltx_Math" alttext="A" display="inline"><mi mathcolor="#3D3D3D">A</mi></math> finite.</span></span></p>
</div>
</li>
<li id="S0.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">subsequence</em> <math id="S0.I2.i3.p1.m1" class="ltx_Math" alttext="x_{n_{1}},x_{n_{2}},\dots" display="inline"><mrow><msub><mi>x</mi><msub><mi>n</mi><mn>1</mn></msub></msub><mo>,</mo><msub><mi>x</mi><msub><mi>n</mi><mn>2</mn></msub></msub><mo>,</mo><mi mathvariant="normal">…</mi></mrow></math> with <math id="S0.I2.i3.p1.m2" class="ltx_Math" alttext="n_{1}&lt;n_{2}&lt;\cdots" display="inline"><mrow><msub><mi>n</mi><mn>1</mn></msub><mo>&lt;</mo><msub><mi>n</mi><mn>2</mn></msub><mo>&lt;</mo><mi mathvariant="normal">⋯</mi></mrow></math>.
<math id="S0.I2.i3.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">sequentially compact</em> if every sequence has a convergent subsequence.</p>
</div>
</li>
<li id="S0.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i4.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> For <em class="ltx_emph ltx_font_italic">metrizable</em> <math id="S0.I2.i4.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>, TFAE:
(1) compact; (2) limit point compact; (3) sequentially compact.</p>
</div>
<div id="S0.I2.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I2.i4.p2.m1" class="ltx_Math" alttext="(1)\Rightarrow(2)" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">2</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> above.
<math id="S0.I2.i4.p2.m2" class="ltx_Math" alttext="(2)\Rightarrow(3)" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">2</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">3</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math>: if <math id="S0.I2.i4.p2.m3" class="ltx_Math" alttext="A=\{x_{n}\}" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></math> is finite use a constant subsequence; else take a limit point <math id="S0.I2.i4.p2.m4" class="ltx_Math" alttext="p" display="inline"><mi mathcolor="#3D3D3D">p</mi></math>
and pick <math id="S0.I2.i4.p2.m5" class="ltx_Math" alttext="x_{n_{k}}\in A\cap B(p,1/k)" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">x</mi><msub><mi mathcolor="#3D3D3D">n</mi><mi mathcolor="#3D3D3D">k</mi></msub></msub><mo mathcolor="#3D3D3D">∈</mo><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">∩</mo><mrow><mi mathcolor="#3D3D3D">B</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D">,</mo><mrow><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">/</mo><mi mathcolor="#3D3D3D">k</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></mrow></math> inductively.
<math id="S0.I2.i4.p2.m6" class="ltx_Math" alttext="(3)\Rightarrow(1)" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">3</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> needs two lemmas below.</span></span></p>
</div>
</li>
<li id="S0.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I2.i5.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> sequentially compact metric <math id="S0.I2.i5.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> the Lebesgue number lemma holds for <math id="S0.I2.i5.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>.</p>
</div>
<div id="S0.I2.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Else get <math id="S0.I2.i5.p2.m1" class="ltx_Math" alttext="C_{n}" display="inline"><msub><mi mathcolor="#3D3D3D">C</mi><mi mathcolor="#3D3D3D">n</mi></msub></math> of diameter <math id="S0.I2.i5.p2.m2" class="ltx_Math" alttext="&lt;1/n" display="inline"><mrow><mi></mi><mo mathcolor="#3D3D3D">&lt;</mo><mrow><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">/</mo><mi mathcolor="#3D3D3D">n</mi></mrow></mrow></math> in no element of <math id="S0.I2.i5.p2.m3" class="ltx_Math" alttext="\mathcal{A}" display="inline"><mi class="ltx_font_mathcaligraphic" mathcolor="#3D3D3D">𝒜</mi></math>; a convergent subsequence
<math id="S0.I2.i5.p2.m4" class="ltx_Math" alttext="x_{n_{k}}\to p" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">x</mi><msub><mi mathcolor="#3D3D3D">n</mi><mi mathcolor="#3D3D3D">k</mi></msub></msub><mo mathcolor="#3D3D3D" stretchy="false">→</mo><mi mathcolor="#3D3D3D">p</mi></mrow></math> traps <math id="S0.I2.i5.p2.m5" class="ltx_Math" alttext="C_{n_{k}}" display="inline"><msub><mi mathcolor="#3D3D3D">C</mi><msub><mi mathcolor="#3D3D3D">n</mi><mi mathcolor="#3D3D3D">k</mi></msub></msub></math> inside a ball around <math id="S0.I2.i5.p2.m6" class="ltx_Math" alttext="p" display="inline"><mi mathcolor="#3D3D3D">p</mi></math> — contradiction.</span></span></p>
</div>
</li>
<li id="S0.I2.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i6.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I2.i6.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> sequentially compact metric <math id="S0.I2.i6.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> <math id="S0.I2.i6.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">totally bounded</em>
(finitely many <math id="S0.I2.i6.p1.m4" class="ltx_Math" alttext="\varepsilon" display="inline"><mi>ε</mi></math>-balls cover <math id="S0.I2.i6.p1.m5" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>, each <math id="S0.I2.i6.p1.m6" class="ltx_Math" alttext="\varepsilon&gt;0" display="inline"><mrow><mi>ε</mi><mo>&gt;</mo><mn>0</mn></mrow></math>).</p>
</div>
<div id="S0.I2.i6.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Else build <math id="S0.I2.i6.p2.m1" class="ltx_Math" alttext="x_{n}" display="inline"><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">n</mi></msub></math> with mutual distances <math id="S0.I2.i6.p2.m2" class="ltx_Math" alttext="\geq\varepsilon" display="inline"><mrow><mi></mi><mo mathcolor="#3D3D3D">≥</mo><mi mathcolor="#3D3D3D">ε</mi></mrow></math>; no convergent subsequence.</span></span></p>
</div>
</li>
<li id="S0.I2.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i7.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Then <math id="S0.I2.i7.p1.m1" class="ltx_Math" alttext="(3)\Rightarrow(1)" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mn>3</mn><mo stretchy="false">)</mo></mrow><mo stretchy="false">⇒</mo><mrow><mo stretchy="false">(</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></mrow></math>: given <math id="S0.I2.i7.p1.m2" class="ltx_Math" alttext="\mathcal{A}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒜</mi></math> with Lebesgue number <math id="S0.I2.i7.p1.m3" class="ltx_Math" alttext="\delta" display="inline"><mi>δ</mi></math>, cover by
<math id="S0.I2.i7.p1.m4" class="ltx_Math" alttext="\varepsilon" display="inline"><mi>ε</mi></math>-balls with <math id="S0.I2.i7.p1.m5" class="ltx_Math" alttext="\varepsilon=\delta/3" display="inline"><mrow><mi>ε</mi><mo>=</mo><mrow><mi>δ</mi><mo>/</mo><mn>3</mn></mrow></mrow></math>; each has diameter <math id="S0.I2.i7.p1.m6" class="ltx_Math" alttext="&lt;\delta" display="inline"><mrow><mi></mi><mo>&lt;</mo><mi>δ</mi></mrow></math>, so each sits
in one element of <math id="S0.I2.i7.p1.m7" class="ltx_Math" alttext="\mathcal{A}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒜</mi></math>.</p>
</div>
</li>
</ul>
</div>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:59:22 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
