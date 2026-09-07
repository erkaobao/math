---
layout: archive
title: "MATH 5345H --- Week 14: Pointwise and compact convergence; Baire spaces"
permalink: /teaching/5345h_notes/week_14
author_profile: false
render_with_liquid: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S0.SS1" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.1  (§46) Pointwise and compact convergence</h2>

<div id="S0.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S0.I1" class="ltx_itemize">
<li id="S0.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> <math id="S0.I1.i1.p1.m1" class="ltx_Math" alttext="Y^{X}=\{f\colon X\to Y\}=\prod_{X}Y" display="inline"><mrow><msup><mi>Y</mi><mi>X</mi></msup><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow><mo stretchy="false">}</mo></mrow><mo rspace="0.111em">=</mo><mrow><msub><mo>∏</mo><mi>X</mi></msub><mi>Y</mi></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> For <math id="S0.I1.i2.p1.m1" class="ltx_Math" alttext="x\in X" display="inline"><mrow><mi>x</mi><mo>∈</mo><mi>X</mi></mrow></math>, <math id="S0.I1.i2.p1.m2" class="ltx_Math" alttext="U\subset Y" display="inline"><mrow><mi>U</mi><mo>⊂</mo><mi>Y</mi></mrow></math> open:   <math id="S0.I1.i2.p1.m3" class="ltx_Math" alttext="S(x,U)=\{f\mid f(x)\in U\}=\pi_{x}^{-1}(U)" display="inline"><mrow><mrow><mi>S</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>f</mi><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>∈</mo><mi>U</mi></mrow><mo stretchy="false">}</mo></mrow><mo>=</mo><mrow><msubsup><mi>π</mi><mi>x</mi><mrow><mo>−</mo><mn>1</mn></mrow></msubsup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.
These form a subbasis for the <em class="ltx_emph ltx_font_italic">topology of pointwise convergence</em>
<math id="S0.I1.i2.p1.m4" class="ltx_Math" alttext="=" display="inline"><mo>=</mo></math> the product topology on <math id="S0.I1.i2.p1.m5" class="ltx_Math" alttext="Y^{X}" display="inline"><msup><mi>Y</mi><mi>X</mi></msup></math>.</p>
</div>
</li>
<li id="S0.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I1.i3.p1.m1" class="ltx_Math" alttext="f_{n}\to f" display="inline"><mrow><msub><mi>f</mi><mi>n</mi></msub><mo stretchy="false">→</mo><mi>f</mi></mrow></math> in it <math id="S0.I1.i3.p1.m2" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> <math id="S0.I1.i3.p1.m3" class="ltx_Math" alttext="f_{n}(x)\to f(x)" display="inline"><mrow><mrow><msub><mi>f</mi><mi>n</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">→</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> for every <math id="S0.I1.i3.p1.m4" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math>.</p>
</div>
</li>
<li id="S0.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i4.p1.m1" class="ltx_Math" alttext="(Y,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>Y</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> metric.   <math id="S0.I1.i4.p1.m2" class="ltx_Math" alttext="B(f,\varepsilon)=\{g\mid\sup_{x\in X}d(f(x),g(x))&lt;\varepsilon\}" display="inline"><mrow><mrow><mi>B</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>f</mi><mo>,</mo><mi>ε</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>g</mi><mo fence="true" lspace="0em" rspace="0.0835em">∣</mo><mrow><mrow><msub><mo lspace="0.0835em" rspace="0.167em">sup</mo><mrow><mi>x</mi><mo>∈</mo><mi>X</mi></mrow></msub><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>,</mo><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow><mo>&lt;</mo><mi>ε</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>
is a basis for the <em class="ltx_emph ltx_font_italic">topology of uniform convergence</em>.</p>
</div>
<div id="S0.I1.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Basis axiom: for <math id="S0.I1.i4.p2.m1" class="ltx_Math" alttext="g\in B(f,\varepsilon)" display="inline"><mrow><mi mathcolor="#3D3D3D">g</mi><mo mathcolor="#3D3D3D">∈</mo><mrow><mi mathcolor="#3D3D3D">B</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math> take <math id="S0.I1.i4.p2.m2" class="ltx_Math" alttext="\delta=\varepsilon-\sup_{x}d(f,g)" display="inline"><mrow><mi mathcolor="#3D3D3D">δ</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D">−</mo><mrow><msub><mo lspace="0em" mathcolor="#3D3D3D" rspace="0.167em">sup</mo><mi mathcolor="#3D3D3D">x</mi></msub><mrow><mi mathcolor="#3D3D3D">d</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">g</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></mrow></mrow></math>;
then <math id="S0.I1.i4.p2.m3" class="ltx_Math" alttext="B(g,\delta)\subset B(f,\varepsilon)" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">B</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">g</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">δ</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">⊂</mo><mrow><mi mathcolor="#3D3D3D">B</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I1.i5.p1.m1" class="ltx_Math" alttext="f_{n}\to f" display="inline"><mrow><msub><mi>f</mi><mi>n</mi></msub><mo stretchy="false">→</mo><mi>f</mi></mrow></math> in it <math id="S0.I1.i5.p1.m2" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> <math id="S0.I1.i5.p1.m3" class="ltx_Math" alttext="f_{n}\to f" display="inline"><mrow><msub><mi>f</mi><mi>n</mi></msub><mo stretchy="false">→</mo><mi>f</mi></mrow></math> uniformly.</p>
</div>
</li>
<li id="S0.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i6.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> A uniform limit of continuous functions is continuous.</p>
</div>
</li>
<li id="S0.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> For <math id="S0.I1.i7.p1.m1" class="ltx_Math" alttext="C\subset X" display="inline"><mrow><mi>C</mi><mo>⊂</mo><mi>X</mi></mrow></math> compact:  
<math id="S0.I1.i7.p1.m2" class="ltx_Math" alttext="B_{C}(f,\varepsilon)=\{g\mid\sup_{x\in C}d(f(x),g(x))&lt;\varepsilon\}" display="inline"><mrow><mrow><msub><mi>B</mi><mi>C</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>f</mi><mo>,</mo><mi>ε</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>g</mi><mo fence="true" lspace="0em" rspace="0.0835em">∣</mo><mrow><mrow><msub><mo lspace="0.0835em" rspace="0.167em">sup</mo><mrow><mi>x</mi><mo>∈</mo><mi>C</mi></mrow></msub><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>,</mo><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow><mo>&lt;</mo><mi>ε</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math> is a basis for the
<em class="ltx_emph ltx_font_italic">topology of compact convergence</em> (uniform convergence on compact sets).</p>
</div>
</li>
<li id="S0.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I1.i8.p1.m1" class="ltx_Math" alttext="f_{n}\to f" display="inline"><mrow><msub><mi>f</mi><mi>n</mi></msub><mo stretchy="false">→</mo><mi>f</mi></mrow></math> in it <math id="S0.I1.i8.p1.m2" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> <math id="S0.I1.i8.p1.m3" class="ltx_Math" alttext="f_{n}|C\to f|C" display="inline"><mrow><mrow><msub><mi>f</mi><mi>n</mi></msub><mo fence="false">|</mo><mi>C</mi></mrow><mo stretchy="false">→</mo><mrow><mi>f</mi><mo fence="false">|</mo><mi>C</mi></mrow></mrow></math> uniformly for every compact <math id="S0.I1.i8.p1.m4" class="ltx_Math" alttext="C\subset X" display="inline"><mrow><mi>C</mi><mo>⊂</mo><mi>X</mi></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Ordering: pointwise <math id="S0.I1.i9.p1.m1" class="ltx_Math" alttext="\subset" display="inline"><mo>⊂</mo></math> compact <math id="S0.I1.i9.p1.m2" class="ltx_Math" alttext="\subset" display="inline"><mo>⊂</mo></math> uniform. If <math id="S0.I1.i9.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is compact the last
two agree.</p>
</div>
</li>
<li id="S0.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i10.p1.m1" class="ltx_Math" alttext="f_{n}(x)=\sum_{k=0}^{n}x^{k}/k!\to e^{x}" display="inline"><mrow><mrow><msub><mi>f</mi><mi>n</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo rspace="0.111em">=</mo><mrow><msubsup><mo>∑</mo><mrow><mi>k</mi><mo>=</mo><mn>0</mn></mrow><mi>n</mi></msubsup><mrow><msup><mi>x</mi><mi>k</mi></msup><mo>/</mo><mrow><mi>k</mi><mo>!</mo></mrow></mrow></mrow><mo stretchy="false">→</mo><msup><mi>e</mi><mi>x</mi></msup></mrow></math> on <math id="S0.I1.i10.p1.m2" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>: pointwise and uniformly on compact
sets, but <em class="ltx_emph ltx_font_italic">not</em> uniformly.</p>
</div>
</li>
<li id="S0.I1.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i11.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i11.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">compactly generated</em> if: <math id="S0.I1.i11.p1.m2" class="ltx_Math" alttext="A\subset X" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>X</mi></mrow></math> is open whenever <math id="S0.I1.i11.p1.m3" class="ltx_Math" alttext="A\cap C" display="inline"><mrow><mi>A</mi><mo>∩</mo><mi>C</mi></mrow></math> is
open in <math id="S0.I1.i11.p1.m4" class="ltx_Math" alttext="C" display="inline"><mi>C</mi></math> for every compact <math id="S0.I1.i11.p1.m5" class="ltx_Math" alttext="C\subset X" display="inline"><mrow><mi>C</mi><mo>⊂</mo><mi>X</mi></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i12.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Equivalently, with “closed” in place of “open”.</p>
</div>
</li>
<li id="S0.I1.i13" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i13.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I1.i13.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> compactly generated <math id="S0.I1.i13.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> (<math id="S0.I1.i13.p1.m3" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> continuous <math id="S0.I1.i13.p1.m4" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> every <math id="S0.I1.i13.p1.m5" class="ltx_Math" alttext="f|C" display="inline"><mrow><mi>f</mi><mo fence="false">|</mo><mi>C</mi></mrow></math> is).</p>
</div>
<div id="S0.I1.i13.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I1.i13.p2.m1" class="ltx_Math" alttext="f^{-1}(U)\cap C=(f|C)^{-1}(U)" display="inline"><mrow><mrow><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">∩</mo><mi mathcolor="#3D3D3D">C</mi></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo fence="false" mathcolor="#3D3D3D">|</mo><mi mathcolor="#3D3D3D">C</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i14" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i14.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i14.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i14.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> compactly generated, <math id="S0.I1.i14.p1.m3" class="ltx_Math" alttext="(Y,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>Y</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> metric. If continuous <math id="S0.I1.i14.p1.m4" class="ltx_Math" alttext="f_{n}\to f" display="inline"><mrow><msub><mi>f</mi><mi>n</mi></msub><mo stretchy="false">→</mo><mi>f</mi></mrow></math> uniformly on
compact subspaces, then <math id="S0.I1.i14.p1.m5" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is continuous.</p>
</div>
</li>
<li id="S0.I1.i15" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i15.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Prop.</span> Locally compact spaces, and first-countable (hence metrizable) spaces, are
compactly generated. <span class="ltx_text" style="font-size:80%;color:#737373;">[Mk p. 284]</span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S0.SS2" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.2  Mapping spaces and the compact-open topology</h2>

<div id="S0.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S0.I2" class="ltx_itemize">
<li id="S0.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> <math id="S0.I2.i1.p1.m1" class="ltx_Math" alttext="\mathscr{C}(X,Y)=\{f\colon X\to Y\mid f\text{ continuous}\}\subset Y^{X}" display="inline"><mrow><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>Y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mrow><mi>Y</mi><mo>∣</mo><mrow><mi>f</mi><mo>⁢</mo><mtext> continuous</mtext></mrow></mrow></mrow><mo stretchy="false">}</mo></mrow><mo>⊂</mo><msup><mi>Y</mi><mi>X</mi></msup></mrow></math>.
(Also written <math id="S0.I2.i1.p1.m2" class="ltx_Math" alttext="\mathrm{Map}(X,Y)" display="inline"><mrow><mi>Map</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>Y</mi><mo stretchy="false">)</mo></mrow></mrow></math>.)</p>
</div>
</li>
<li id="S0.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I2.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> For <math id="S0.I2.i2.p1.m2" class="ltx_Math" alttext="C\subset X" display="inline"><mrow><mi>C</mi><mo>⊂</mo><mi>X</mi></mrow></math> compact and <math id="S0.I2.i2.p1.m3" class="ltx_Math" alttext="U\subset Y" display="inline"><mrow><mi>U</mi><mo>⊂</mo><mi>Y</mi></mrow></math> open:
<math id="S0.I2.i2.p1.m4" class="ltx_Math" alttext="S(C,U)=\{f\in\mathscr{C}(X,Y)\mid f(C)\subset U\}." display="inline"><mrow><mrow><mrow><mi>S</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>C</mi><mo>,</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mi>f</mi><mo>∈</mo><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>Y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>C</mi><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><mi>U</mi></mrow><mo stretchy="false">}</mo></mrow></mrow><mo lspace="0em">.</mo></mrow></math>
These form a subbasis for the <em class="ltx_emph ltx_font_italic">compact-open topology</em>.</p>
</div>
</li>
<li id="S0.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Finer than pointwise convergence, since points are compact.</p>
</div>
</li>
<li id="S0.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I2.i4.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I2.i4.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> a space, <math id="S0.I2.i4.p1.m3" class="ltx_Math" alttext="(Y,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>Y</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> metric. On <math id="S0.I2.i4.p1.m4" class="ltx_Math" alttext="\mathscr{C}(X,Y)" display="inline"><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>Y</mi><mo stretchy="false">)</mo></mrow></mrow></math> the compact-open topology equals
the topology of compact convergence.</p>
</div>
<div id="S0.I2.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Two inclusions.
<math id="S0.I2.i4.p2.m1" class="ltx_Math" alttext="(\supset)" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mo lspace="0em" mathcolor="#3D3D3D" rspace="0em">⊃</mo><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></math> Given <math id="S0.I2.i4.p2.m2" class="ltx_Math" alttext="f\in S(C,U)" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">∈</mo><mrow><mi mathcolor="#3D3D3D">S</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">C</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>: <math id="S0.I2.i4.p2.m3" class="ltx_Math" alttext="f(C)" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">C</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> is compact in the open <math id="S0.I2.i4.p2.m4" class="ltx_Math" alttext="U" display="inline"><mi mathcolor="#3D3D3D">U</mi></math>, so
<math id="S0.I2.i4.p2.m5" class="ltx_Math" alttext="B(f(C),\varepsilon)\subset U" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">B</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">C</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">⊂</mo><mi mathcolor="#3D3D3D">U</mi></mrow></math> for some <math id="S0.I2.i4.p2.m6" class="ltx_Math" alttext="\varepsilon&gt;0" display="inline"><mrow><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D">&gt;</mo><mn mathcolor="#3D3D3D">0</mn></mrow></math>; then <math id="S0.I2.i4.p2.m7" class="ltx_Math" alttext="B_{C}(f,\varepsilon)\subset S(C,U)" display="inline"><mrow><mrow><msub><mi mathcolor="#3D3D3D">B</mi><mi mathcolor="#3D3D3D">C</mi></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">⊂</mo><mrow><mi mathcolor="#3D3D3D">S</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">C</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.
<math id="S0.I2.i4.p2.m8" class="ltx_Math" alttext="(\subset)" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mo lspace="0em" mathcolor="#3D3D3D" rspace="0em">⊂</mo><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></math> Given <math id="S0.I2.i4.p2.m9" class="ltx_Math" alttext="B_{C}(f,\varepsilon)" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">B</mi><mi mathcolor="#3D3D3D">C</mi></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math>: cover <math id="S0.I2.i4.p2.m10" class="ltx_Math" alttext="C" display="inline"><mi mathcolor="#3D3D3D">C</mi></math> by finitely many <math id="S0.I2.i4.p2.m11" class="ltx_Math" alttext="V_{x_{i}}" display="inline"><msub><mi mathcolor="#3D3D3D">V</mi><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">i</mi></msub></msub></math> with
<math id="S0.I2.i4.p2.m12" class="ltx_Math" alttext="f(\bar{V}_{x_{i}})" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mover accent="true"><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">¯</mo></mover><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">i</mi></msub></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> of diameter <math id="S0.I2.i4.p2.m13" class="ltx_Math" alttext="&lt;\varepsilon" display="inline"><mrow><mi></mi><mo mathcolor="#3D3D3D">&lt;</mo><mi mathcolor="#3D3D3D">ε</mi></mrow></math>; set <math id="S0.I2.i4.p2.m14" class="ltx_Math" alttext="C_{i}=\bar{V}_{x_{i}}\cap C" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">C</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D">=</mo><mrow><msub><mover accent="true"><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">¯</mo></mover><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">i</mi></msub></msub><mo mathcolor="#3D3D3D">∩</mo><mi mathcolor="#3D3D3D">C</mi></mrow></mrow></math>, <math id="S0.I2.i4.p2.m15" class="ltx_Math" alttext="U_{i}=B(f(x_{i}),\varepsilon/3)" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">B</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">,</mo><mrow><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D">/</mo><mn mathcolor="#3D3D3D">3</mn></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>;
then <math id="S0.I2.i4.p2.m16" class="ltx_Math" alttext="f\in\bigcap_{i}S(C_{i},U_{i})\subset B_{C}(f,\varepsilon)" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D" rspace="0.111em">∈</mo><mrow><msub><mo mathcolor="#3D3D3D">⋂</mo><mi mathcolor="#3D3D3D">i</mi></msub><mrow><mi mathcolor="#3D3D3D">S</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">C</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">U</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow><mo mathcolor="#3D3D3D">⊂</mo><mrow><msub><mi mathcolor="#3D3D3D">B</mi><mi mathcolor="#3D3D3D">C</mi></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">ε</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I2.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> Hence the compact-convergence topology on <math id="S0.I2.i5.p1.m1" class="ltx_Math" alttext="\mathscr{C}(X,Y)" display="inline"><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>Y</mi><mo stretchy="false">)</mo></mrow></mrow></math> depends only on the
<em class="ltx_emph ltx_font_italic">topology</em> of <math id="S0.I2.i5.p1.m2" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math>, not on the chosen metric.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S0.SS3" class="ltx_subsection">
<h2 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.3  Joint continuity and the exponential law</h2>

<div id="S0.SS3.p1" class="ltx_para ltx_noindent">
<ul id="S0.I3" class="ltx_itemize">
<li id="S0.I3.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I3.i1.p1.m1" class="ltx_Math" alttext="F\colon X\times Y\to Z" display="inline"><mrow><mi>F</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>Y</mi></mrow><mo stretchy="false">→</mo><mi>Z</mi></mrow></mrow></math> and <math id="S0.I3.i1.p1.m2" class="ltx_Math" alttext="f\colon X\to Z^{Y}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><msup><mi>Z</mi><mi>Y</mi></msup></mrow></mrow></math> correspond by
<math id="S0.I3.i1.p1.m3" class="ltx_Math" alttext="f(x)(y)=F(x,y)." display="inline"><mrow><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow><mo lspace="0em">.</mo></mrow></math>
Call <math id="S0.I3.i1.p1.m4" class="ltx_Math" alttext="F" display="inline"><mi>F</mi></math> the <em class="ltx_emph ltx_font_italic">left adjoint</em>, <math id="S0.I3.i1.p1.m5" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> the <em class="ltx_emph ltx_font_italic">right adjoint</em>.</p>
</div>
</li>
<li id="S0.I3.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I3.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I3.i2.p1.m2" class="ltx_Math" alttext="F" display="inline"><mi>F</mi></math> continuous <math id="S0.I3.i2.p1.m3" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> <math id="S0.I3.i2.p1.m4" class="ltx_Math" alttext="f\colon X\to\mathscr{C}(Y,Z)" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>Y</mi><mo>,</mo><mi>Z</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math> is continuous
(compact-open topology).</p>
</div>
<div id="S0.I3.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Given <math id="S0.I3.i2.p2.m1" class="ltx_Math" alttext="f(p)\in S(C,U)" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">∈</mo><mrow><mi mathcolor="#3D3D3D">S</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">C</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>, i.e. <math id="S0.I3.i2.p2.m2" class="ltx_Math" alttext="F(\{p\}\times C)\subset U" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">F</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D" rspace="0.055em" stretchy="false">}</mo></mrow><mo mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">C</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">⊂</mo><mi mathcolor="#3D3D3D">U</mi></mrow></math>: apply the <em class="ltx_emph ltx_font_italic">tube lemma</em>
to the open <math id="S0.I3.i2.p2.m3" class="ltx_Math" alttext="F^{-1}(U)\supset\{p\}\times C" display="inline"><mrow><mrow><msup><mi mathcolor="#3D3D3D">F</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">⊃</mo><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D" rspace="0.055em" stretchy="false">}</mo></mrow><mo mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">C</mi></mrow></mrow></math> with <math id="S0.I3.i2.p2.m4" class="ltx_Math" alttext="C" display="inline"><mi mathcolor="#3D3D3D">C</mi></math> compact, getting <math id="S0.I3.i2.p2.m5" class="ltx_Math" alttext="V\ni p" display="inline"><mrow><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">∋</mo><mi mathcolor="#3D3D3D">p</mi></mrow></math> with
<math id="S0.I3.i2.p2.m6" class="ltx_Math" alttext="V\times C\subset F^{-1}(U)" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">V</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">C</mi></mrow><mo mathcolor="#3D3D3D">⊂</mo><mrow><msup><mi mathcolor="#3D3D3D">F</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I3.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I3.i3.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Prop.</span> <math id="S0.I3.i3.p1.m2" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> locally compact Hausdorff <math id="S0.I3.i3.p1.m3" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> the evaluation map
<math id="S0.I3.i3.p1.m4" class="ltx_Math" alttext="e\colon\mathscr{C}(Y,Z)\times Y\to Z,\quad e(g,y)=g(y)" display="inline"><mrow><mi>e</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mrow><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>Y</mi><mo>,</mo><mi>Z</mi><mo rspace="0.055em" stretchy="false">)</mo></mrow></mrow><mo rspace="0.222em">×</mo><mi>Y</mi></mrow><mo stretchy="false">→</mo><mi>Z</mi></mrow><mo rspace="1.167em">,</mo><mrow><mrow><mi>e</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>g</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></mrow></math> is continuous.</p>
</div>
<div id="S0.I3.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Given <math id="S0.I3.i3.p2.m1" class="ltx_Math" alttext="g(p)\in U" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">g</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">U</mi></mrow></math>: local compactness gives <math id="S0.I3.i3.p2.m2" class="ltx_Math" alttext="V\ni p" display="inline"><mrow><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">∋</mo><mi mathcolor="#3D3D3D">p</mi></mrow></math> with <math id="S0.I3.i3.p2.m3" class="ltx_Math" alttext="\bar{V}" display="inline"><mover accent="true"><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">¯</mo></mover></math> compact,
<math id="S0.I3.i3.p2.m4" class="ltx_Math" alttext="\bar{V}\subset g^{-1}(U)" display="inline"><mrow><mover accent="true"><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">¯</mo></mover><mo mathcolor="#3D3D3D">⊂</mo><mrow><msup><mi mathcolor="#3D3D3D">g</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>. Then <math id="S0.I3.i3.p2.m5" class="ltx_Math" alttext="W=S(\bar{V},U)\times V" display="inline"><mrow><mi mathcolor="#3D3D3D">W</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mrow><mi mathcolor="#3D3D3D">S</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mover accent="true"><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">¯</mo></mover><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" rspace="0.055em" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">V</mi></mrow></mrow></math> works.</span></span></p>
</div>
</li>
<li id="S0.I3.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I3.i4.p1.m1" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> locally compact Hausdorff: <math id="S0.I3.i4.p1.m2" class="ltx_Math" alttext="f\colon X\to\mathscr{C}(Y,Z)" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>Y</mi><mo>,</mo><mi>Z</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math> continuous <math id="S0.I3.i4.p1.m3" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math>
<math id="S0.I3.i4.p1.m4" class="ltx_Math" alttext="F\colon X\times Y\to Z" display="inline"><mrow><mi>F</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>Y</mi></mrow><mo stretchy="false">→</mo><mi>Z</mi></mrow></mrow></math> continuous.</p>
</div>
<div id="S0.I3.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I3.i4.p2.m1" class="ltx_Math" alttext="F=e\circ(f\times\operatorname{id})" display="inline"><mrow><mi mathcolor="#3D3D3D">F</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">e</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">∘</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">id</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I3.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i5.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I3.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Cor.</span> <math id="S0.I3.i5.p1.m2" class="ltx_Math" alttext="I=[0,1]" display="inline"><mrow><mi>I</mi><mo>=</mo><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></mrow></math> is compact Hausdorff, hence locally compact Hausdorff. So there are
bijective correspondences between maps</p>
<table id="S0.Ex1" class="ltx_equation ltx_eqn_table">

<tbody><tr class="ltx_equation ltx_eqn_row ltx_align_baseline">
<td class="ltx_eqn_cell ltx_eqn_center_padleft"></td>
<td class="ltx_eqn_cell ltx_align_center"><math id="S0.Ex1.m1" class="ltx_Math" alttext="F\colon X\times I\to Y,\quad f\colon X\to\mathscr{C}(I,Y),\quad G\colon I%
\times X\to Y,\quad g\colon I\to\mathscr{C}(X,Y)" display="block"><mrow><mi>F</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>I</mi></mrow><mo stretchy="false">→</mo><mrow><mi>Y</mi><mo rspace="1.167em">,</mo><mi>f</mi></mrow></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mrow><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>I</mi><mo>,</mo><mi>Y</mi><mo stretchy="false">)</mo></mrow></mrow><mo rspace="1.167em">,</mo><mi>G</mi></mrow></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>I</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>X</mi></mrow><mo stretchy="false">→</mo><mrow><mi>Y</mi><mo rspace="1.167em">,</mo><mi>g</mi></mrow></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>I</mi><mo stretchy="false">→</mo><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>Y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math></td>
<td class="ltx_eqn_cell ltx_eqn_center_padright"></td>
</tr></tbody>
</table>
<p class="ltx_p">(<math id="S0.I3.i5.p1.m3" class="ltx_Math" alttext="g" display="inline"><mi>g</mi></math> requires <math id="S0.I3.i5.p1.m4" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> locally compact Hausdorff), related by
<math id="S0.I3.i5.p1.m5" class="ltx_Math" alttext="F(x,t)=f(x)(t)=G(t,x)=g(t)(x)." display="inline"><mrow><mrow><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>G</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>t</mi><mo>,</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>t</mi><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow><mo lspace="0em">.</mo></mrow></math></p>
</div>
</li>
<li id="S0.I3.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I3.i6.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Each such map is a <em class="ltx_emph ltx_font_italic">homotopy</em> between <math id="S0.I3.i6.p1.m1" class="ltx_Math" alttext="g(0)" display="inline"><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></mrow></math> and <math id="S0.I3.i6.p1.m2" class="ltx_Math" alttext="g(1)" display="inline"><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></mrow></math>. This is the bridge
into Chapter 7: a homotopy is a path in a mapping space.</p>
</div>
</li>
</ul>
</div>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:59:38 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
