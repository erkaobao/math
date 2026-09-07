---
layout: archive
title: "MATH 5345H --- Week 3: Topological spaces and standard examples"
permalink: /teaching/5345h_notes/week_3
author_profile: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S1" class="ltx_section">
<h2 class="ltx_title ltx_font_bold ltx_title_section" style="font-size:144%;color:#1A3873;">1  Topological Spaces and Continuous Functions</h2>

<section id="S1.SS1" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.1  (§12) Topological spaces</h3>

<div id="S1.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S1.I1" class="ltx_itemize">
<li id="S1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i1.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">topology</em> on a set <math id="S1.I1.i1.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is a collection <math id="S1.I1.i1.p1.m3" class="ltx_Math" alttext="\mathcal{T}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒯</mi></math> of subsets with</p>
<ol id="S1.I1.i1.I1" class="ltx_enumerate">
<li id="S1.I1.i1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(1)</span> 
<div id="S1.I1.i1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i1.I1.i1.p1.m1" class="ltx_Math" alttext="\emptyset\in\mathcal{T}" display="inline"><mrow><mi mathvariant="normal">∅</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi></mrow></math> and <math id="S1.I1.i1.I1.i1.p1.m2" class="ltx_Math" alttext="X\in\mathcal{T}" display="inline"><mrow><mi>X</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi></mrow></math>;</p>
</div>
</li>
<li id="S1.I1.i1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(2)</span> 
<div id="S1.I1.i1.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i1.I1.i2.p1.m1" class="ltx_Math" alttext="\{U_{\alpha}\}_{\alpha\in J}\subset\mathcal{T}\ \Rightarrow\ \bigcup_{\alpha%
\in J}U_{\alpha}\in\mathcal{T}" display="inline"><mrow><msub><mrow><mo stretchy="false">{</mo><msub><mi>U</mi><mi>α</mi></msub><mo stretchy="false">}</mo></mrow><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></msub><mo>⊂</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo lspace="0.778em" rspace="0.611em" stretchy="false">⇒</mo><mrow><msub><mo>⋃</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></msub><msub><mi>U</mi><mi>α</mi></msub></mrow><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi></mrow></math>
 (<em class="ltx_emph ltx_font_italic">arbitrary</em> unions)</p>
</div>
</li>
<li id="S1.I1.i1.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(3)</span> 
<div id="S1.I1.i1.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i1.I1.i3.p1.m1" class="ltx_Math" alttext="U_{1},\dots,U_{n}\in\mathcal{T}\ \Rightarrow\ U_{1}\cap\cdots\cap U_{n}\in%
\mathcal{T}" display="inline"><mrow><mrow><msub><mi>U</mi><mn>1</mn></msub><mo>,</mo><mi mathvariant="normal">…</mi><mo>,</mo><msub><mi>U</mi><mi>n</mi></msub></mrow><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo lspace="0.778em" rspace="0.778em" stretchy="false">⇒</mo><mrow><msub><mi>U</mi><mn>1</mn></msub><mo>∩</mo><mi mathvariant="normal">⋯</mi><mo>∩</mo><msub><mi>U</mi><mi>n</mi></msub></mrow><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi></mrow></math>
 (<em class="ltx_emph ltx_font_italic">finite</em> intersections)</p>
</div>
</li>
</ol>
<p class="ltx_p"><math id="S1.I1.i1.p1.m4" class="ltx_Math" alttext="(X,\mathcal{T})" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo stretchy="false">)</mo></mrow></math> is a <em class="ltx_emph ltx_font_italic">topological space</em>; the <math id="S1.I1.i1.p1.m5" class="ltx_Math" alttext="U\in\mathcal{T}" display="inline"><mrow><mi>U</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi></mrow></math> are the <em class="ltx_emph ltx_font_italic">open</em> sets.</p>
</div>
<div id="S1.I1.i1.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">For (3) it is enough to check <math id="S1.I1.i1.p2.m1" class="ltx_Math" alttext="n=2" display="inline"><mrow><mi mathcolor="#737373">n</mi><mo mathcolor="#737373">=</mo><mn mathcolor="#737373">2</mn></mrow></math>; induct. The asymmetry between (2) and (3) is the whole
subject — infinite intersections of open sets need not be open: <math id="S1.I1.i1.p2.m2" class="ltx_Math" alttext="\bigcap_{n}(-1/n,1/n)=\{0\}" display="inline"><mrow><mrow><msub><mo mathcolor="#737373">⋂</mo><mi mathcolor="#737373">n</mi></msub><mrow><mo lspace="0em" mathcolor="#737373" stretchy="false">(</mo><mrow><mo mathcolor="#737373">−</mo><mrow><mn mathcolor="#737373">1</mn><mo mathcolor="#737373">/</mo><mi mathcolor="#737373">n</mi></mrow></mrow><mo mathcolor="#737373">,</mo><mrow><mn mathcolor="#737373">1</mn><mo mathcolor="#737373">/</mo><mi mathcolor="#737373">n</mi></mrow><mo mathcolor="#737373" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#737373">=</mo><mrow><mo mathcolor="#737373" stretchy="false">{</mo><mn mathcolor="#737373">0</mn><mo mathcolor="#737373" stretchy="false">}</mo></mrow></mrow></math>.</span></span></span></p>
</div>
</li>
<li id="S1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">Discrete</em> <math id="S1.I1.i2.p1.m1" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{disc}}=\mathcal{P}(X)" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>disc</mi></msub><mo>=</mo><mrow><mi class="ltx_font_mathcaligraphic">𝒫</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> (every subset open). <em class="ltx_emph ltx_font_italic">Trivial</em> <math id="S1.I1.i2.p1.m2" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{triv}}=\{\emptyset,X\}" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>triv</mi></msub><mo>=</mo><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I1.i3.p1.m1" class="ltx_Math" alttext="X=\{a,b\}" display="inline"><mrow><mi>X</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow></mrow></math>: exactly four topologies —
<math id="S1.I1.i3.p1.m2" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{triv}}" display="inline"><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>triv</mi></msub></math>,   <math id="S1.I1.i3.p1.m3" class="ltx_Math" alttext="\mathcal{T}_{a}=\{\emptyset,\{a\},X\}" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>a</mi></msub><mo>=</mo><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></mrow></math>,   <math id="S1.I1.i3.p1.m4" class="ltx_Math" alttext="\mathcal{T}_{b}=\{\emptyset,\{b\},X\}" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>b</mi></msub><mo>=</mo><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></mrow></math>,   <math id="S1.I1.i3.p1.m5" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{disc}}" display="inline"><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>disc</mi></msub></math>.
The middle two are the <em class="ltx_emph ltx_font_italic">Sierpiński</em> topologies.</p>
</div>
<div id="S1.I1.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">In <math id="S1.I1.i3.p2.m1" class="ltx_Math" alttext="(X,\mathcal{T}_{a})" display="inline"><mrow><mo mathcolor="#737373" stretchy="false">(</mo><mi mathcolor="#737373">X</mi><mo mathcolor="#737373">,</mo><msub><mi class="ltx_font_mathcaligraphic" mathcolor="#737373">𝒯</mi><mi mathcolor="#737373">a</mi></msub><mo mathcolor="#737373" stretchy="false">)</mo></mrow></math>: <math id="S1.I1.i3.p2.m2" class="ltx_Math" alttext="a" display="inline"><mi mathcolor="#737373">a</mi></math> is separated from <math id="S1.I1.i3.p2.m3" class="ltx_Math" alttext="b" display="inline"><mi mathcolor="#737373">b</mi></math>, but every open set containing <math id="S1.I1.i3.p2.m4" class="ltx_Math" alttext="b" display="inline"><mi mathcolor="#737373">b</mi></math> contains <math id="S1.I1.i3.p2.m5" class="ltx_Math" alttext="a" display="inline"><mi mathcolor="#737373">a</mi></math>.
So <math id="S1.I1.i3.p2.m6" class="ltx_Math" alttext="a" display="inline"><mi mathcolor="#737373">a</mi></math> is “arbitrarily close” to <math id="S1.I1.i3.p2.m7" class="ltx_Math" alttext="b" display="inline"><mi mathcolor="#737373">b</mi></math> without <math id="S1.I1.i3.p2.m8" class="ltx_Math" alttext="b" display="inline"><mi mathcolor="#737373">b</mi></math> being close to <math id="S1.I1.i3.p2.m9" class="ltx_Math" alttext="a" display="inline"><mi mathcolor="#737373">a</mi></math>. No metric does this.</span></span></span></p>
</div>
</li>
<li id="S1.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I1.i4.p1.m1" class="ltx_Math" alttext="X=\{a,b,c\}" display="inline"><mrow><mi>X</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo>,</mo><mi>c</mi><mo stretchy="false">}</mo></mrow></mrow></math>: there are <math id="S1.I1.i4.p1.m2" class="ltx_Math" alttext="29" display="inline"><mn>29</mn></math> topologies. Nine of them, the rest obtained by
permuting <math id="S1.I1.i4.p1.m3" class="ltx_Math" alttext="a,b,c" display="inline"><mrow><mi>a</mi><mo>,</mo><mi>b</mi><mo>,</mo><mi>c</mi></mrow></math>:</p>
<ul id="S1.I1.i4.I1" class="ltx_itemize">
<li id="S1.I1.i4.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I1.i4.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i4.I1.i1.p1.m1" class="ltx_Math" alttext="\{\emptyset,X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math></p>
</div>
</li>
<li id="S1.I1.i4.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I1.i4.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i4.I1.i2.p1.m1" class="ltx_Math" alttext="\{\emptyset,\{a\},X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math></p>
</div>
</li>
<li id="S1.I1.i4.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I1.i4.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i4.I1.i3.p1.m1" class="ltx_Math" alttext="\{\emptyset,\{a,b\},X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math></p>
</div>
</li>
<li id="S1.I1.i4.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I1.i4.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i4.I1.i4.p1.m1" class="ltx_Math" alttext="\{\emptyset,\{a\},\{a,b\},X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math></p>
</div>
</li>
<li id="S1.I1.i4.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I1.i4.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i4.I1.i5.p1.m1" class="ltx_Math" alttext="\{\emptyset,\{a,b\},\{c\},X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>c</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math></p>
</div>
</li>
<li id="S1.I1.i4.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I1.i4.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i4.I1.i6.p1.m1" class="ltx_Math" alttext="\{\emptyset,\{a\},\{b\},\{a,b\},X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math></p>
</div>
</li>
<li id="S1.I1.i4.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I1.i4.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i4.I1.i7.p1.m1" class="ltx_Math" alttext="\{\emptyset,\{a\},\{a,b\},\{a,c\},X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>c</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math></p>
</div>
</li>
<li id="S1.I1.i4.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I1.i4.I1.i8.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i4.I1.i8.p1.m1" class="ltx_Math" alttext="\{\emptyset,\{a\},\{c\},\{a,b\},\{a,c\},X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>c</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>c</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math></p>
</div>
</li>
<li id="S1.I1.i4.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">–</span> 
<div id="S1.I1.i4.I1.i9.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i4.I1.i9.p1.m1" class="ltx_Math" alttext="\mathcal{P}(X)" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">𝒫</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo stretchy="false">)</mo></mrow></mrow></math>, the discrete topology (8 elements)</p>
</div>
</li>
</ul>
</div>
</li>
<li id="S1.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <em class="ltx_emph ltx_font_italic">Not</em> topologies on <math id="S1.I1.i5.p1.m1" class="ltx_Math" alttext="\{a,b,c\}" display="inline"><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo>,</mo><mi>c</mi><mo stretchy="false">}</mo></mrow></math>:
<math id="S1.I1.i5.p1.m2" class="ltx_Math" alttext="\{\{a\},\{c\},\{a,b\},\{a,c\}\}" display="inline"><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>c</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>c</mi><mo stretchy="false">}</mo></mrow><mo stretchy="false">}</mo></mrow></math> (misses <math id="S1.I1.i5.p1.m3" class="ltx_Math" alttext="\emptyset,X" display="inline"><mrow><mi mathvariant="normal">∅</mi><mo>,</mo><mi>X</mi></mrow></math>);
<math id="S1.I1.i5.p1.m4" class="ltx_Math" alttext="\{\emptyset,\{a\},\{b\},X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math> (no union);
<math id="S1.I1.i5.p1.m5" class="ltx_Math" alttext="\{\emptyset,\{a,b\},\{a,c\},X\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>c</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>X</mi><mo stretchy="false">}</mo></mrow></math> (no intersection).</p>
</div>
</li>
<li id="S1.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i6.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I1.i6.p1.m1" class="ltx_Math" alttext="\mathcal{T}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒯</mi></math> is <em class="ltx_emph ltx_font_italic">coarser</em> than <math id="S1.I1.i6.p1.m2" class="ltx_Math" alttext="\mathcal{T}^{\prime}" display="inline"><msup><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>′</mo></msup></math> (<math id="S1.I1.i6.p1.m3" class="ltx_Math" alttext="\mathcal{T}^{\prime}" display="inline"><msup><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>′</mo></msup></math> <em class="ltx_emph ltx_font_italic">finer</em>) if <math id="S1.I1.i6.p1.m4" class="ltx_Math" alttext="\mathcal{T}\subset\mathcal{T}^{\prime}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>⊂</mo><msup><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>′</mo></msup></mrow></math>.
Always <math id="S1.I1.i6.p1.m5" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{triv}}\subset\mathcal{T}\subset\mathcal{T}_{\mathrm{disc}}" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>triv</mi></msub><mo>⊂</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>⊂</mo><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>disc</mi></msub></mrow></math>.</p>
</div>
<div id="S1.I1.i6.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">A partial order, not a total one: neither Sierpiński topology refines the other.</span></span></span></p>
</div>
</li>
<li id="S1.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i7.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">Cofinite</em> topology: <math id="S1.I1.i7.p1.m1" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{cof}}=\{U\subset X\mid X-U\text{ finite}\}\cup\{\emptyset\}" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>cof</mi></msub><mo>=</mo><mrow><mrow><mo stretchy="false">{</mo><mrow><mi>U</mi><mo>⊂</mo><mi>X</mi></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>X</mi><mo>−</mo><mrow><mi>U</mi><mo>⁢</mo><mtext> finite</mtext></mrow></mrow><mo stretchy="false">}</mo></mrow><mo>∪</mo><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo stretchy="false">}</mo></mrow></mrow></mrow></math>.
It is a topology.</p>
</div>
<div id="S1.I1.i7.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> (2): if some <math id="S1.I1.i7.p2.m1" class="ltx_Math" alttext="U_{\beta}\neq\emptyset" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">β</mi></msub><mo mathcolor="#3D3D3D">≠</mo><mi mathcolor="#3D3D3D" mathvariant="normal">∅</mi></mrow></math> then <math id="S1.I1.i7.p2.m2" class="ltx_Math" alttext="X-\bigcup U_{\alpha}\subset X-U_{\beta}" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D" rspace="0.055em">−</mo><mrow><mo mathcolor="#3D3D3D">⋃</mo><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">α</mi></msub></mrow></mrow><mo mathcolor="#3D3D3D">⊂</mo><mrow><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D">−</mo><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">β</mi></msub></mrow></mrow></math> is finite.
(3): De Morgan turns <math id="S1.I1.i7.p2.m3" class="ltx_Math" alttext="X-\bigcap U_{i}" display="inline"><mrow><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D" rspace="0.055em">−</mo><mrow><mo mathcolor="#3D3D3D">⋂</mo><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">i</mi></msub></mrow></mrow></math> into a finite union of finite sets.</span></span></p>
</div>
</li>
<li id="S1.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> <math id="S1.I1.i8.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> finite <math id="S1.I1.i8.p1.m2" class="ltx_Math" alttext="\Rightarrow\mathcal{T}_{\mathrm{cof}}=\mathcal{T}_{\mathrm{disc}}" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>cof</mi></msub><mo>=</mo><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>disc</mi></msub></mrow></math>;  <math id="S1.I1.i8.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> infinite <math id="S1.I1.i8.p1.m4" class="ltx_Math" alttext="\Rightarrow\mathcal{T}_{\mathrm{cof}}\subsetneq\mathcal{T}_{\mathrm{disc}}" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>cof</mi></msub><mo>⊊</mo><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>disc</mi></msub></mrow></math>
(singletons are not cofinite).
On <math id="S1.I1.i8.p1.m5" class="ltx_Math" alttext="\mathbb{N}" display="inline"><mi>ℕ</mi></math>: <math id="S1.I1.i8.p1.m6" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{triv}}\subsetneq\mathcal{T}_{\mathrm{cof}}\subsetneq%
\mathcal{T}_{\mathrm{disc}}" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>triv</mi></msub><mo>⊊</mo><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>cof</mi></msub><mo>⊊</mo><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>disc</mi></msub></mrow></math>.</p>
</div>
</li>
<li id="S1.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">metric</em> on <math id="S1.I1.i9.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <math id="S1.I1.i9.p1.m2" class="ltx_Math" alttext="d\colon X\times X\to\mathbb{R}" display="inline"><mrow><mi>d</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>X</mi></mrow><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></mrow></math> with</p>
<ol id="S1.I1.i9.I1" class="ltx_enumerate">
<li id="S1.I1.i9.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(1)</span> 
<div id="S1.I1.i9.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i9.I1.i1.p1.m1" class="ltx_Math" alttext="d(x,y)\geq 0" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>≥</mo><mn>0</mn></mrow></math>, with <math id="S1.I1.i9.I1.i1.p1.m2" class="ltx_Math" alttext="d(x,y)=0\Leftrightarrow x=y" display="inline"><mrow><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mn>0</mn></mrow><mo stretchy="false">⇔</mo><mrow><mi>x</mi><mo>=</mo><mi>y</mi></mrow></mrow></math>;</p>
</div>
</li>
<li id="S1.I1.i9.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(2)</span> 
<div id="S1.I1.i9.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i9.I1.i2.p1.m1" class="ltx_Math" alttext="d(x,y)=d(y,x)" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo>,</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>;</p>
</div>
</li>
<li id="S1.I1.i9.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(3)</span> 
<div id="S1.I1.i9.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i9.I1.i3.p1.m1" class="ltx_Math" alttext="d(x,z)\leq d(x,y)+d(y,z)" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>z</mi><mo stretchy="false">)</mo></mrow></mrow><mo>≤</mo><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>+</mo><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo>,</mo><mi>z</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>.</p>
</div>
</li>
</ol>
<p class="ltx_p"><math id="S1.I1.i9.p1.m3" class="ltx_Math" alttext="\varepsilon" display="inline"><mi>ε</mi></math>-ball: <math id="S1.I1.i9.p1.m4" class="ltx_Math" alttext="B_{d}(x,\varepsilon)=\{y\mid d(x,y)&lt;\varepsilon\}" display="inline"><mrow><mrow><msub><mi>B</mi><mi>d</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>ε</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>y</mi><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mi>ε</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i10.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i10.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">Metric topology</em> <math id="S1.I1.i10.p1.m2" class="ltx_Math" alttext="\mathcal{T}_{d}" display="inline"><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>d</mi></msub></math>:
<math id="S1.I1.i10.p1.m3" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math> open <math id="S1.I1.i10.p1.m4" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> for each <math id="S1.I1.i10.p1.m5" class="ltx_Math" alttext="x\in U" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>U</mi></mrow></math> there is <math id="S1.I1.i10.p1.m6" class="ltx_Math" alttext="\varepsilon&gt;0" display="inline"><mrow><mi>ε</mi><mo>&gt;</mo><mn>0</mn></mrow></math> with <math id="S1.I1.i10.p1.m7" class="ltx_Math" alttext="B_{d}(x,\varepsilon)\subset U" display="inline"><mrow><mrow><msub><mi>B</mi><mi>d</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>ε</mi><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mi>U</mi></mrow></math>.
This is a topology.</p>
</div>
<div id="S1.I1.i10.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> (3) is where finiteness enters: take <math id="S1.I1.i10.p2.m1" class="ltx_Math" alttext="\varepsilon=\min\{\varepsilon_{1},\dots,\varepsilon_{n}\}&gt;0" display="inline"><mrow><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">min</mi><mo>⁡</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><msub><mi mathcolor="#3D3D3D">ε</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D" mathvariant="normal">…</mi><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">ε</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow><mo mathcolor="#3D3D3D">&gt;</mo><mn mathcolor="#3D3D3D">0</mn></mrow></math>.
An infinite family would give <math id="S1.I1.i10.p2.m2" class="ltx_Math" alttext="\inf=0" display="inline"><mrow><mo mathcolor="#3D3D3D" rspace="0.1389em">inf</mo><mo lspace="0.1389em" mathcolor="#3D3D3D">=</mo><mn mathcolor="#3D3D3D">0</mn></mrow></math>.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS2" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.2  (§13) Basis for a topology</h3>

<div id="S1.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S1.I2" class="ltx_itemize">
<li id="S1.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I2.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I2.i1.p1.m2" class="ltx_Math" alttext="\mathcal{B}" display="inline"><mi class="ltx_font_mathcaligraphic">ℬ</mi></math>, a collection of subsets of <math id="S1.I2.i1.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>, is a <em class="ltx_emph ltx_font_italic">basis</em> if</p>
<ol id="S1.I2.i1.I1" class="ltx_enumerate">
<li id="S1.I2.i1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(1)</span> 
<div id="S1.I2.i1.I1.i1.p1" class="ltx_para">
<p class="ltx_p">each <math id="S1.I2.i1.I1.i1.p1.m1" class="ltx_Math" alttext="x\in X" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>X</mi></mrow></math> lies in some <math id="S1.I2.i1.I1.i1.p1.m2" class="ltx_Math" alttext="B\in\mathcal{B}" display="inline"><mrow><mi>B</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi></mrow></math>;</p>
</div>
</li>
<li id="S1.I2.i1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(2)</span> 
<div id="S1.I2.i1.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i1.I1.i2.p1.m1" class="ltx_Math" alttext="x\in B_{1}\cap B_{2}" display="inline"><mrow><mi>x</mi><mo>∈</mo><mrow><msub><mi>B</mi><mn>1</mn></msub><mo>∩</mo><msub><mi>B</mi><mn>2</mn></msub></mrow></mrow></math> <math id="S1.I2.i1.I1.i2.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> there is <math id="S1.I2.i1.I1.i2.p1.m3" class="ltx_Math" alttext="B_{3}\in\mathcal{B}" display="inline"><mrow><msub><mi>B</mi><mn>3</mn></msub><mo>∈</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi></mrow></math> with <math id="S1.I2.i1.I1.i2.p1.m4" class="ltx_Math" alttext="x\in B_{3}\subset B_{1}\cap B_{2}" display="inline"><mrow><mi>x</mi><mo>∈</mo><msub><mi>B</mi><mn>3</mn></msub><mo>⊂</mo><mrow><msub><mi>B</mi><mn>1</mn></msub><mo>∩</mo><msub><mi>B</mi><mn>2</mn></msub></mrow></mrow></math>.</p>
</div>
</li>
</ol>
</div>
</li>
<li id="S1.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> Topology <em class="ltx_emph ltx_font_italic">generated</em> by <math id="S1.I2.i2.p1.m1" class="ltx_Math" alttext="\mathcal{B}" display="inline"><mi class="ltx_font_mathcaligraphic">ℬ</mi></math>:
<math id="S1.I2.i2.p1.m2" class="ltx_Math" alttext="U\in\mathcal{T}\Leftrightarrow\forall x\in U\ \exists B\in\mathcal{B}:\ x\in B%
\subset U." display="inline"><mrow><mrow><mrow><mi>U</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi></mrow><mo stretchy="false">⇔</mo><mrow><mrow><mo rspace="0.167em">∀</mo><mi>x</mi></mrow><mo>∈</mo><mrow><mi>U</mi><mo lspace="0.667em">⁢</mo><mrow><mo rspace="0.167em">∃</mo><mi>B</mi></mrow></mrow><mo>∈</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi></mrow><mo lspace="0.278em" rspace="0.778em">:</mo><mrow><mi>x</mi><mo>∈</mo><mi>B</mi><mo>⊂</mo><mi>U</mi></mrow></mrow><mo lspace="0em">.</mo></mrow></math>
This is a topology.</p>
</div>
</li>
<li id="S1.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Open discs in <math id="S1.I2.i3.p1.m1" class="ltx_Math" alttext="\mathbb{R}^{2}" display="inline"><msup><mi>ℝ</mi><mn>2</mn></msup></math>;  open rectangles <math id="S1.I2.i3.p1.m2" class="ltx_Math" alttext="(a,b)\times(c,d)" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo rspace="0.055em" stretchy="false">)</mo></mrow><mo rspace="0.222em">×</mo><mrow><mo stretchy="false">(</mo><mi>c</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></mrow></math>; 
singletons <math id="S1.I2.i3.p1.m3" class="ltx_Math" alttext="\{x\}" display="inline"><mrow><mo stretchy="false">{</mo><mi>x</mi><mo stretchy="false">}</mo></mrow></math> (generating <math id="S1.I2.i3.p1.m4" class="ltx_Math" alttext="\mathcal{T}_{\mathrm{disc}}" display="inline"><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>disc</mi></msub></math>).</p>
</div>
<div id="S1.I2.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> For rectangles, <math id="S1.I2.i3.p2.m1" class="ltx_Math" alttext="B_{1}\cap B_{2}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">B</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">∩</mo><msub><mi mathcolor="#3D3D3D">B</mi><mn mathcolor="#3D3D3D">2</mn></msub></mrow></math> is again a basis element or empty — condition (2) is free.
For discs it needs the triangle inequality.</span></span></p>
</div>
</li>
<li id="S1.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Let <math id="S1.I2.i4.p1.m1" class="ltx_Math" alttext="\mathcal{B}" display="inline"><mi class="ltx_font_mathcaligraphic">ℬ</mi></math> be a basis for <math id="S1.I2.i4.p1.m2" class="ltx_Math" alttext="\mathcal{T}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒯</mi></math>. Then (1) each <math id="S1.I2.i4.p1.m3" class="ltx_Math" alttext="B\in\mathcal{B}" display="inline"><mrow><mi>B</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi></mrow></math> is open;
(2) every open <math id="S1.I2.i4.p1.m4" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math> is a union of basis elements: <math id="S1.I2.i4.p1.m5" class="ltx_Math" alttext="U=\bigcup_{x\in U}B_{x}" display="inline"><mrow><mi>U</mi><mo rspace="0.111em">=</mo><mrow><msub><mo>⋃</mo><mrow><mi>x</mi><mo>∈</mo><mi>U</mi></mrow></msub><msub><mi>B</mi><mi>x</mi></msub></mrow></mrow></math>.</p>
</div>
<div id="S1.I2.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">The gluing trick — assemble local choices <math id="S1.I2.i4.p2.m1" class="ltx_Math" alttext="B_{x}" display="inline"><msub><mi mathcolor="#737373">B</mi><mi mathcolor="#737373">x</mi></msub></math> into one global object. It recurs
throughout the course; name it now.</span></span></span></p>
</div>
</li>
<li id="S1.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <span class="ltx_text ltx_font_bold">(Recognition criterion.)</span> Let <math id="S1.I2.i5.p1.m2" class="ltx_Math" alttext="\mathcal{C}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒞</mi></math> be a collection of open sets in
<math id="S1.I2.i5.p1.m3" class="ltx_Math" alttext="(X,\mathcal{T})" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo stretchy="false">)</mo></mrow></math> such that for every open <math id="S1.I2.i5.p1.m4" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math> and every <math id="S1.I2.i5.p1.m5" class="ltx_Math" alttext="x\in U" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>U</mi></mrow></math> there is <math id="S1.I2.i5.p1.m6" class="ltx_Math" alttext="C\in\mathcal{C}" display="inline"><mrow><mi>C</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒞</mi></mrow></math> with
<math id="S1.I2.i5.p1.m7" class="ltx_Math" alttext="x\in C\subset U" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>C</mi><mo>⊂</mo><mi>U</mi></mrow></math>. Then <math id="S1.I2.i5.p1.m8" class="ltx_Math" alttext="\mathcal{C}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒞</mi></math> is a basis for <math id="S1.I2.i5.p1.m9" class="ltx_Math" alttext="\mathcal{T}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒯</mi></math>.</p>
</div>
<div id="S1.I2.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <span class="ltx_text ltx_font_italic">The workhorse for identifying bases. Use it for products, subspaces, metric subspaces.</span></span></span></p>
</div>
</li>
<li id="S1.I2.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i6.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I2.i6.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <span class="ltx_text ltx_font_bold">(Comparison.)</span> <math id="S1.I2.i6.p1.m2" class="ltx_Math" alttext="\mathcal{B},\mathcal{B}^{\prime}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>,</mo><msup><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>′</mo></msup></mrow></math> bases for <math id="S1.I2.i6.p1.m3" class="ltx_Math" alttext="\mathcal{T},\mathcal{T}^{\prime}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>,</mo><msup><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>′</mo></msup></mrow></math>. TFAE:</p>
<ol id="S1.I2.i6.I1" class="ltx_enumerate">
<li id="S1.I2.i6.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(1)</span> 
<div id="S1.I2.i6.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I2.i6.I1.i1.p1.m1" class="ltx_Math" alttext="\mathcal{T}\subset\mathcal{T}^{\prime}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>⊂</mo><msup><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>′</mo></msup></mrow></math>;</p>
</div>
</li>
<li id="S1.I2.i6.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(2)</span> 
<div id="S1.I2.i6.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p">for each <math id="S1.I2.i6.I1.i2.p1.m1" class="ltx_Math" alttext="B\in\mathcal{B}" display="inline"><mrow><mi>B</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi></mrow></math> and <math id="S1.I2.i6.I1.i2.p1.m2" class="ltx_Math" alttext="x\in B" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>B</mi></mrow></math> there is <math id="S1.I2.i6.I1.i2.p1.m3" class="ltx_Math" alttext="B^{\prime}\in\mathcal{B}^{\prime}" display="inline"><mrow><msup><mi>B</mi><mo>′</mo></msup><mo>∈</mo><msup><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>′</mo></msup></mrow></math> with <math id="S1.I2.i6.I1.i2.p1.m4" class="ltx_Math" alttext="x\in B^{\prime}\subset B" display="inline"><mrow><mi>x</mi><mo>∈</mo><msup><mi>B</mi><mo>′</mo></msup><mo>⊂</mo><mi>B</mi></mrow></math>.</p>
</div>
</li>
</ol>
</div>
</li>
<li id="S1.I2.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> <math id="S1.I2.i7.p1.m1" class="ltx_Math" alttext="\mathcal{T}\subset\mathcal{T}^{\prime}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>⊂</mo><msup><mi class="ltx_font_mathcaligraphic">𝒯</mi><mo>′</mo></msup></mrow></math> does <em class="ltx_emph ltx_font_italic">not</em> require <math id="S1.I2.i7.p1.m2" class="ltx_Math" alttext="\mathcal{B}\subset\mathcal{B}^{\prime}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>⊂</mo><msup><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>′</mo></msup></mrow></math> — only that
<math id="S1.I2.i7.p1.m3" class="ltx_Math" alttext="\mathcal{B}^{\prime}" display="inline"><msup><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>′</mo></msup></math> has <em class="ltx_emph ltx_font_italic">smaller</em> sets near each point.</p>
</div>
</li>
<li id="S1.I2.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> <math id="S1.I2.i8.p1.m1" class="ltx_Math" alttext="\mathcal{B}" display="inline"><mi class="ltx_font_mathcaligraphic">ℬ</mi></math> and <math id="S1.I2.i8.p1.m2" class="ltx_Math" alttext="\mathcal{B}^{\prime}" display="inline"><msup><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>′</mo></msup></math> generate the <em class="ltx_emph ltx_font_italic">same</em> topology <math id="S1.I2.i8.p1.m3" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> both conditions hold:
for each <math id="S1.I2.i8.p1.m4" class="ltx_Math" alttext="x\in B\in\mathcal{B}" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>B</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi></mrow></math> there is <math id="S1.I2.i8.p1.m5" class="ltx_Math" alttext="B^{\prime}\in\mathcal{B}^{\prime}" display="inline"><mrow><msup><mi>B</mi><mo>′</mo></msup><mo>∈</mo><msup><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>′</mo></msup></mrow></math> with <math id="S1.I2.i8.p1.m6" class="ltx_Math" alttext="x\in B^{\prime}\subset B" display="inline"><mrow><mi>x</mi><mo>∈</mo><msup><mi>B</mi><mo>′</mo></msup><mo>⊂</mo><mi>B</mi></mrow></math>,
<em class="ltx_emph ltx_font_italic">and</em> for each <math id="S1.I2.i8.p1.m7" class="ltx_Math" alttext="x\in B^{\prime}\in\mathcal{B}^{\prime}" display="inline"><mrow><mi>x</mi><mo>∈</mo><msup><mi>B</mi><mo>′</mo></msup><mo>∈</mo><msup><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>′</mo></msup></mrow></math> there is <math id="S1.I2.i8.p1.m8" class="ltx_Math" alttext="B\in\mathcal{B}" display="inline"><mrow><mi>B</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi></mrow></math> with <math id="S1.I2.i8.p1.m9" class="ltx_Math" alttext="x\in B\subset B^{\prime}" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>B</mi><mo>⊂</mo><msup><mi>B</mi><mo>′</mo></msup></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Discs and rectangles generate the same topology on <math id="S1.I2.i9.p1.m1" class="ltx_Math" alttext="\mathbb{R}^{2}" display="inline"><msup><mi>ℝ</mi><mn>2</mn></msup></math>, namely the metric
topology.</p>
</div>
</li>
<li id="S1.I2.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> Standard topology on <math id="S1.I2.i10.p1.m1" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>: basis <math id="S1.I2.i10.p1.m2" class="ltx_Math" alttext="\{(a,b)\mid a&lt;b\}" display="inline"><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>a</mi><mo>&lt;</mo><mi>b</mi></mrow><mo stretchy="false">}</mo></mrow></math>; equals <math id="S1.I2.i10.p1.m3" class="ltx_Math" alttext="\mathcal{T}_{d}" display="inline"><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>d</mi></msub></math> for <math id="S1.I2.i10.p1.m4" class="ltx_Math" alttext="d(x,y)=|y-x|" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">|</mo><mrow><mi>y</mi><mo>−</mo><mi>x</mi></mrow><mo stretchy="false">|</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i11.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">Lower limit</em> topology <math id="S1.I2.i11.p1.m1" class="ltx_Math" alttext="\mathcal{T}_{\ell}" display="inline"><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi mathvariant="normal">ℓ</mi></msub></math> on <math id="S1.I2.i11.p1.m2" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>: basis <math id="S1.I2.i11.p1.m3" class="ltx_Math" alttext="\{[a,b)\mid a&lt;b\}" display="inline"><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>a</mi><mo>&lt;</mo><mi>b</mi></mrow><mo stretchy="false">}</mo></mrow></math>;
write <math id="S1.I2.i11.p1.m4" class="ltx_Math" alttext="\mathbb{R}_{\ell}" display="inline"><msub><mi>ℝ</mi><mi mathvariant="normal">ℓ</mi></msub></math>.</p>
</div>
</li>
<li id="S1.I2.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i12.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I2.i12.p1.m1" class="ltx_Math" alttext="\mathcal{T}_{d}\subsetneq\mathcal{T}_{\ell}" display="inline"><mrow><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi>d</mi></msub><mo>⊊</mo><msub><mi class="ltx_font_mathcaligraphic">𝒯</mi><mi mathvariant="normal">ℓ</mi></msub></mrow></math>.</p>
</div>
<div id="S1.I2.i12.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I2.i12.p2.m1" class="ltx_Math" alttext="\subset" display="inline"><mo mathcolor="#3D3D3D">⊂</mo></math>: given <math id="S1.I2.i12.p2.m2" class="ltx_Math" alttext="x\in(a,b)" display="inline"><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">∈</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> take <math id="S1.I2.i12.p2.m3" class="ltx_Math" alttext="[x,b)" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></math>. Strict: no <math id="S1.I2.i12.p2.m4" class="ltx_Math" alttext="(c,d)" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">d</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></math> sits inside <math id="S1.I2.i12.p2.m5" class="ltx_Math" alttext="[a,b)" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></math> around
<math id="S1.I2.i12.p2.m6" class="ltx_Math" alttext="x=a" display="inline"><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">=</mo><mi mathcolor="#3D3D3D">a</mi></mrow></math>, since <math id="S1.I2.i12.p2.m7" class="ltx_Math" alttext="(c+a)/2" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D">+</mo><mi mathcolor="#3D3D3D">a</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D">/</mo><mn mathcolor="#3D3D3D">2</mn></mrow></math> escapes.</span></span></p>
</div>
</li>
<li id="S1.I2.i13" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i13.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">subbasis</em> <math id="S1.I2.i13.p1.m1" class="ltx_Math" alttext="\mathcal{S}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒮</mi></math> is a collection of subsets with <math id="S1.I2.i13.p1.m2" class="ltx_Math" alttext="\bigcup_{S\in\mathcal{S}}S=X" display="inline"><mrow><mrow><msub><mo>⋃</mo><mrow><mi>S</mi><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒮</mi></mrow></msub><mi>S</mi></mrow><mo>=</mo><mi>X</mi></mrow></math>.
Its associated basis is
<math id="S1.I2.i13.p1.m3" class="ltx_Math" alttext="\mathcal{B}=\{S_{1}\cap\cdots\cap S_{n}\mid S_{i}\in\mathcal{S},\ n\geq 1\}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><msub><mi>S</mi><mn>1</mn></msub><mo>∩</mo><mi mathvariant="normal">⋯</mi><mo>∩</mo><msub><mi>S</mi><mi>n</mi></msub></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mrow><msub><mi>S</mi><mi>i</mi></msub><mo>∈</mo><mi class="ltx_font_mathcaligraphic">𝒮</mi></mrow><mo rspace="0.667em">,</mo><mrow><mi>n</mi><mo>≥</mo><mn>1</mn></mrow></mrow><mo stretchy="false">}</mo></mrow></mrow></math>;
the topology generated by <math id="S1.I2.i13.p1.m4" class="ltx_Math" alttext="\mathcal{S}" display="inline"><mi class="ltx_font_mathcaligraphic">𝒮</mi></math> is the one generated by <math id="S1.I2.i13.p1.m5" class="ltx_Math" alttext="\mathcal{B}" display="inline"><mi class="ltx_font_mathcaligraphic">ℬ</mi></math>. Always <math id="S1.I2.i13.p1.m6" class="ltx_Math" alttext="\mathcal{S}\subset\mathcal{B}\subset\mathcal{T}" display="inline"><mrow><mi class="ltx_font_mathcaligraphic">𝒮</mi><mo>⊂</mo><mi class="ltx_font_mathcaligraphic">ℬ</mi><mo>⊂</mo><mi class="ltx_font_mathcaligraphic">𝒯</mi></mrow></math>.</p>
</div>
<div id="S1.I2.i13.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I2.i13.p2.m1" class="ltx_Math" alttext="\mathcal{B}" display="inline"><mi class="ltx_font_mathcaligraphic" mathcolor="#3D3D3D">ℬ</mi></math> satisfies the basis axioms: (2) holds because <math id="S1.I2.i13.p2.m2" class="ltx_Math" alttext="B_{1}\cap B_{2}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">B</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">∩</mo><msub><mi mathcolor="#3D3D3D">B</mi><mn mathcolor="#3D3D3D">2</mn></msub></mrow></math> is again a finite
intersection of subbasis elements. The bound <math id="S1.I2.i13.p2.m3" class="ltx_Math" alttext="n\geq 1" display="inline"><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">≥</mo><mn mathcolor="#3D3D3D">1</mn></mrow></math> avoids the empty intersection.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:58:58 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
