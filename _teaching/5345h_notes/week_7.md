---
layout: archive
title: "MATH 5345H --- Week 7: The quotient topology and identification spaces"
permalink: /teaching/5345h_notes/week_7
author_profile: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S0.SS1" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">0.1  (§22) The quotient topology</h3>

<div id="S0.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S0.I1" class="ltx_itemize">
<li id="S0.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Injections gave us subspaces and embeddings. Surjections will give quotients —
the dual construction, with <em class="ltx_emph ltx_font_italic">finest</em> in place of coarsest.</p>
</div>
</li>
<li id="S0.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> An <em class="ltx_emph ltx_font_italic">equivalence relation</em> <math id="S0.I1.i2.p1.m1" class="ltx_Math" alttext="\sim" display="inline"><mo>∼</mo></math> on <math id="S0.I1.i2.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>: reflexive, symmetric, transitive.
Classes <math id="S0.I1.i2.p1.m3" class="ltx_Math" alttext="[x]=\{y\mid x\sim y\}" display="inline"><mrow><mrow><mo stretchy="false">[</mo><mi>x</mi><mo stretchy="false">]</mo></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>y</mi><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mi>x</mi><mo>∼</mo><mi>y</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></math>; they are nonempty, cover <math id="S0.I1.i2.p1.m4" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>, are mutually disjoint.
<math id="S0.I1.i2.p1.m5" class="ltx_math_unparsed" alttext="X/\!\!\sim\;=\{[x]\}" display="inline"><mrow><mi>X</mi><mpadded width="0.170em"><mo>/</mo></mpadded><mo rspace="0em">∼</mo><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">[</mo><mi>x</mi><mo stretchy="false">]</mo></mrow><mo stretchy="false">}</mo></mrow></mrow></math>, canonical surjection <math id="S0.I1.i2.p1.m6" class="ltx_Math" alttext="\pi(x)=[x]" display="inline"><mrow><mrow><mi>π</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">[</mo><mi>x</mi><mo stretchy="false">]</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Any surjection <math id="S0.I1.i3.p1.m1" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> arises this way: set <math id="S0.I1.i3.p1.m2" class="ltx_Math" alttext="x\sim y\Leftrightarrow f(x)=f(y)" display="inline"><mrow><mrow><mi>x</mi><mo>∼</mo><mi>y</mi></mrow><mo stretchy="false">⇔</mo><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>;
then <math id="S0.I1.i3.p1.m3" class="ltx_Math" alttext="h([x])=f(x)" display="inline"><mrow><mrow><mi>h</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mo stretchy="false">[</mo><mi>x</mi><mo stretchy="false">]</mo></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> is a bijection <math id="S0.I1.i3.p1.m4" class="ltx_math_unparsed" alttext="X/\!\!\sim\;\to Y" display="inline"><mrow><mi>X</mi><mpadded width="0.170em"><mo>/</mo></mpadded><mo rspace="0em">∼</mo><mo stretchy="false">→</mo><mi>Y</mi></mrow></math> with <math id="S0.I1.i3.p1.m5" class="ltx_Math" alttext="f=h\circ\pi" display="inline"><mrow><mi>f</mi><mo>=</mo><mrow><mi>h</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>π</mi></mrow></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i4.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <em class="ltx_emph ltx_font_italic">Quotient topology</em> on <math id="S0.I1.i4.p1.m2" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> from a surjection <math id="S0.I1.i4.p1.m3" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math>:
<math id="S0.I1.i4.p1.m4" class="ltx_Math" alttext="U\subset Y\text{ open}\Leftrightarrow f^{-1}(U)\text{ open in }X." display="inline"><mrow><mrow><mrow><mi>U</mi><mo>⊂</mo><mrow><mi>Y</mi><mo>⁢</mo><mtext> open</mtext></mrow></mrow><mo stretchy="false">⇔</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>U</mi><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mtext> open in </mtext><mo>⁢</mo><mi>X</mi></mrow></mrow><mo lspace="0em">.</mo></mrow></math>
A surjection carrying this topology is a <em class="ltx_emph ltx_font_italic">quotient map</em>.</p>
</div>
<div id="S0.I1.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> It is a topology because <math id="S0.I1.i4.p2.m1" class="ltx_Math" alttext="f^{-1}" display="inline"><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup></math> commutes with <math id="S0.I1.i4.p2.m2" class="ltx_Math" alttext="\cup" display="inline"><mo mathcolor="#3D3D3D">∪</mo></math> and <math id="S0.I1.i4.p2.m3" class="ltx_Math" alttext="\cap" display="inline"><mo mathcolor="#3D3D3D">∩</mo></math>. Quotient maps are
continuous by construction.</span></span></p>
</div>
</li>
<li id="S0.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> The quotient topology is the <em class="ltx_emph ltx_font_italic">finest</em> topology on <math id="S0.I1.i5.p1.m1" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> making <math id="S0.I1.i5.p1.m2" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> continuous.</p>
</div>
</li>
<li id="S0.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I1.i6.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> surjective is a quotient map <math id="S0.I1.i6.p1.m2" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> (<math id="S0.I1.i6.p1.m3" class="ltx_Math" alttext="A\subset Y" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>Y</mi></mrow></math> closed <math id="S0.I1.i6.p1.m4" class="ltx_Math" alttext="\Leftrightarrow f^{-1}(A)" display="inline"><mrow><mi></mi><mo stretchy="false">⇔</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> closed).</p>
</div>
</li>
<li id="S0.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> A bijective quotient map is a homeomorphism, and conversely.</p>
</div>
</li>
<li id="S0.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S0.I1.i8.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is an <em class="ltx_emph ltx_font_italic">open map</em> if <math id="S0.I1.i8.p1.m2" class="ltx_Math" alttext="f(U)" display="inline"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow></math> is open for all open <math id="S0.I1.i8.p1.m3" class="ltx_Math" alttext="U" display="inline"><mi>U</mi></math>;
a <em class="ltx_emph ltx_font_italic">closed map</em> if <math id="S0.I1.i8.p1.m4" class="ltx_Math" alttext="f(A)" display="inline"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo stretchy="false">)</mo></mrow></mrow></math> is closed for all closed <math id="S0.I1.i8.p1.m5" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math>.</p>
</div>
</li>
<li id="S0.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S0.I1.i9.p1.m1" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> open <math id="S0.I1.i9.p1.m2" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> <math id="S0.I1.i9.p1.m3" class="ltx_Math" alttext="f(B)" display="inline"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>B</mi><mo stretchy="false">)</mo></mrow></mrow></math> open for every basis element <math id="S0.I1.i9.p1.m4" class="ltx_Math" alttext="B" display="inline"><mi>B</mi></math>.</p>
</div>
</li>
<li id="S0.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i10.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S0.I1.i10.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> A surjective open map is a quotient map. So is a surjective closed map.</p>
</div>
<div id="S0.I1.i10.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S0.I1.i10.p2.m1" class="ltx_Math" alttext="U=f(f^{-1}(U))" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math> by surjectivity; then apply openness (resp. closedness).</span></span></p>
</div>
</li>
<li id="S0.I1.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i11.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i11.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i11.p1.m2" class="ltx_Math" alttext="f\colon[0,1]\to S^{1}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow><mo stretchy="false">→</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></mrow></math>, <math id="S0.I1.i11.p1.m3" class="ltx_Math" alttext="f(t)=(\cos 2\pi t,\sin 2\pi t)" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mrow><mn>2</mn><mo>⁢</mo><mi>π</mi><mo>⁢</mo><mi>t</mi></mrow></mrow><mo>,</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mrow><mn>2</mn><mo>⁢</mo><mi>π</mi><mo>⁢</mo><mi>t</mi></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></math>: continuous, surjective,
closed (compactness), hence a quotient map. <em class="ltx_emph ltx_font_italic">Not</em> open.
With <math id="S0.I1.i11.p1.m4" class="ltx_Math" alttext="0\sim 1" display="inline"><mrow><mn>0</mn><mo>∼</mo><mn>1</mn></mrow></math>: <math id="S0.I1.i11.p1.m5" class="ltx_math_unparsed" alttext="[0,1]/\!\!\sim\;\cong S^{1}" display="inline"><mrow><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow><mpadded width="0.170em"><mo>/</mo></mpadded><mo rspace="0em">∼</mo><mo>≅</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i12.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i12.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> Torus. <math id="S0.I1.i12.p1.m2" class="ltx_Math" alttext="g=f\times f\colon[0,1]^{2}\to S^{1}\times S^{1}" display="inline"><mrow><mrow><mi>g</mi><mo>=</mo><mrow><mi>f</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>f</mi></mrow></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msup><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow><mn>2</mn></msup><mo stretchy="false">→</mo><mrow><msup><mi>S</mi><mn>1</mn></msup><mo lspace="0.222em" rspace="0.222em">×</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></mrow></mrow></math> is a quotient map;
identify <math id="S0.I1.i12.p1.m3" class="ltx_Math" alttext="(s,0)\sim(s,1)" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mi>s</mi><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow><mo>∼</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></mrow></math> and <math id="S0.I1.i12.p1.m4" class="ltx_Math" alttext="(0,t)\sim(1,t)" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow><mo>∼</mo><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow></math>. Classes: the four corners; the paired
edge points; the interior singletons. So <math id="S0.I1.i12.p1.m5" class="ltx_math_unparsed" alttext="T^{2}\cong[0,1]^{2}/\!\!\sim" display="inline"><mrow><msup><mi>T</mi><mn>2</mn></msup><mo>≅</mo><msup><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow><mn>2</mn></msup><mpadded width="0.170em"><mo>/</mo></mpadded><mo>∼</mo></mrow></math>.</p>
</div>
</li>
<li id="S0.I1.i13" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i13.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i13.p1.m1" class="ltx_Math" alttext="\mathbb{R}\to\{n,z,p\}" display="inline"><mrow><mi>ℝ</mi><mo stretchy="false">→</mo><mrow><mo stretchy="false">{</mo><mi>n</mi><mo>,</mo><mi>z</mi><mo>,</mo><mi>p</mi><mo stretchy="false">}</mo></mrow></mrow></math> by sign. Quotient topology
<math id="S0.I1.i13.p1.m2" class="ltx_Math" alttext="\{\emptyset,\{n\},\{p\},\{n,p\},Y\}" display="inline"><mrow><mo stretchy="false">{</mo><mi mathvariant="normal">∅</mi><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>n</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>p</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mrow><mo stretchy="false">{</mo><mi>n</mi><mo>,</mo><mi>p</mi><mo stretchy="false">}</mo></mrow><mo>,</mo><mi>Y</mi><mo stretchy="false">}</mo></mrow></math>: not Hausdorff; <math id="S0.I1.i13.p1.m3" class="ltx_Math" alttext="z" display="inline"><mi>z</mi></math> is the only closed point.</p>
</div>
</li>
<li id="S0.I1.i14" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i14.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S0.I1.i14.p1.m1" class="ltx_Math" alttext="\pi_{1}\colon\mathbb{R}^{2}\to\mathbb{R}" display="inline"><mrow><msub><mi>π</mi><mn>1</mn></msub><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msup><mi>ℝ</mi><mn>2</mn></msup><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></mrow></math> is open (hence a quotient map) but <em class="ltx_emph ltx_font_italic">not</em> closed:
the hyperbola <math id="S0.I1.i14.p1.m2" class="ltx_Math" alttext="C=\{xy=1\}" display="inline"><mrow><mi>C</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mrow><mi>x</mi><mo>⁢</mo><mi>y</mi></mrow><mo>=</mo><mn>1</mn></mrow><mo stretchy="false">}</mo></mrow></mrow></math> is closed, <math id="S0.I1.i14.p1.m3" class="ltx_Math" alttext="\pi_{1}(C)=\mathbb{R}-\{0\}" display="inline"><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>C</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>ℝ</mi><mo>−</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></mrow></math> is not.</p>
</div>
</li>
<li id="S0.I1.i15" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i15.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> <span class="ltx_text ltx_font_bold">Ex.</span> Restricting a quotient map can destroy the property.
With <math id="S0.I1.i15.p1.m1" class="ltx_Math" alttext="A=C\cup\{(0,0)\}" display="inline"><mrow><mi>A</mi><mo>=</mo><mrow><mi>C</mi><mo>∪</mo><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow><mo stretchy="false">}</mo></mrow></mrow></mrow></math>, the map <math id="S0.I1.i15.p1.m2" class="ltx_Math" alttext="\pi_{1}|A\colon A\to\mathbb{R}" display="inline"><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo fence="false">|</mo><mi>A</mi></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>A</mi><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></mrow></math> is a continuous surjection but
<em class="ltx_emph ltx_font_italic">not</em> a quotient map: <math id="S0.I1.i15.p1.m3" class="ltx_Math" alttext="\{0\}" display="inline"><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></math> is not open in <math id="S0.I1.i15.p1.m4" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>, yet its preimage <math id="S0.I1.i15.p1.m5" class="ltx_Math" alttext="\{(0,0)\}" display="inline"><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow><mo stretchy="false">}</mo></mrow></math>
is open in <math id="S0.I1.i15.p1.m6" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math>.</p>
</div>
</li>
<li id="S0.I1.i16" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i16.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <math id="S0.I1.i16.p1.m1" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> a quotient map, <math id="S0.I1.i16.p1.m2" class="ltx_Math" alttext="B\subset Y" display="inline"><mrow><mi>B</mi><mo>⊂</mo><mi>Y</mi></mrow></math>, <math id="S0.I1.i16.p1.m3" class="ltx_Math" alttext="A=f^{-1}(B)" display="inline"><mrow><mi>A</mi><mo>=</mo><mrow><msup><mi>f</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>B</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> <em class="ltx_emph ltx_font_italic">saturated</em>,
<math id="S0.I1.i16.p1.m4" class="ltx_Math" alttext="g=f|A\colon A\to B" display="inline"><mrow><mrow><mi>g</mi><mo>=</mo><mrow><mi>f</mi><mo fence="false">|</mo><mi>A</mi></mrow></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>A</mi><mo stretchy="false">→</mo><mi>B</mi></mrow></mrow></math>. Then <math id="S0.I1.i16.p1.m5" class="ltx_Math" alttext="g" display="inline"><mi>g</mi></math> is a quotient map if either
(1) <math id="S0.I1.i16.p1.m6" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> is open, or <math id="S0.I1.i16.p1.m7" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> is closed; or (2) <math id="S0.I1.i16.p1.m8" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> is an open map, or a closed map.</p>
</div>
<div id="S0.I1.i16.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Two identities do the work: <math id="S0.I1.i16.p2.m1" class="ltx_Math" alttext="g^{-1}(V)=f^{-1}(V)" display="inline"><mrow><mrow><msup><mi mathcolor="#3D3D3D">g</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math> for <math id="S0.I1.i16.p2.m2" class="ltx_Math" alttext="V\subset B" display="inline"><mrow><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">⊂</mo><mi mathcolor="#3D3D3D">B</mi></mrow></math>, and
<math id="S0.I1.i16.p2.m3" class="ltx_Math" alttext="g(A\cap U)=B\cap f(U)" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">g</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">∩</mo><mi mathcolor="#3D3D3D">U</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">B</mi><mo mathcolor="#3D3D3D">∩</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>. Both use <math id="S0.I1.i16.p2.m4" class="ltx_Math" alttext="A=f^{-1}(B)" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">B</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S0.I1.i17" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i17.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Composites of quotient maps are quotient maps.
<span class="ltx_text ltx_font_bold">Caution.</span> Products of quotient maps need <em class="ltx_emph ltx_font_italic">not</em> be; some local compactness hypothesis
is required. Quotients of Hausdorff spaces need not be Hausdorff.</p>
</div>
</li>
<li id="S0.I1.i18" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i18.p1" class="ltx_para">
<p class="ltx_p"><math id="S0.I1.i18.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Universal property.)</span> <math id="S0.I1.i18.p1.m2" class="ltx_Math" alttext="f\colon X\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> a quotient map,
<math id="S0.I1.i18.p1.m3" class="ltx_Math" alttext="h\colon X\to Z" display="inline"><mrow><mi>h</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Z</mi></mrow></mrow></math> constant on the fibres of <math id="S0.I1.i18.p1.m4" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math>. Then <math id="S0.I1.i18.p1.m5" class="ltx_Math" alttext="h" display="inline"><mi>h</mi></math> factors uniquely as <math id="S0.I1.i18.p1.m6" class="ltx_Math" alttext="h=g\circ f" display="inline"><mrow><mi>h</mi><mo>=</mo><mrow><mi>g</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>f</mi></mrow></mrow></math>;
moreover <math id="S0.I1.i18.p1.m7" class="ltx_Math" alttext="g" display="inline"><mi>g</mi></math> is continuous <math id="S0.I1.i18.p1.m8" class="ltx_Math" alttext="\Leftrightarrow h" display="inline"><mrow><mi></mi><mo stretchy="false">⇔</mo><mi>h</mi></mrow></math> is, and <math id="S0.I1.i18.p1.m9" class="ltx_Math" alttext="g" display="inline"><mi>g</mi></math> is a quotient map <math id="S0.I1.i18.p1.m10" class="ltx_Math" alttext="\Leftrightarrow h" display="inline"><mrow><mi></mi><mo stretchy="false">⇔</mo><mi>h</mi></mrow></math> is.</p>
</div>
</li>
<li id="S0.I1.i19" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S0.I1.i19.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> <math id="S0.I1.i19.p1.m1" class="ltx_Math" alttext="h\colon X\to Z" display="inline"><mrow><mi>h</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Z</mi></mrow></mrow></math> a continuous surjection, <math id="S0.I1.i19.p1.m2" class="ltx_Math" alttext="x\sim y\Leftrightarrow h(x)=h(y)" display="inline"><mrow><mrow><mi>x</mi><mo>∼</mo><mi>y</mi></mrow><mo stretchy="false">⇔</mo><mrow><mrow><mi>h</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>h</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>.
Then <math id="S0.I1.i19.p1.m3" class="ltx_Math" alttext="h" display="inline"><mi>h</mi></math> induces a continuous bijection <math id="S0.I1.i19.p1.m4" class="ltx_math_unparsed" alttext="g\colon X/\!\!\sim\;\to Z" display="inline"><mrow><mi>g</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mi>X</mi><mpadded width="0.170em"><mo>/</mo></mpadded><mo rspace="0em">∼</mo><mo stretchy="false">→</mo><mi>Z</mi></mrow></math>;
<math id="S0.I1.i19.p1.m5" class="ltx_Math" alttext="g" display="inline"><mi>g</mi></math> is a homeomorphism <math id="S0.I1.i19.p1.m6" class="ltx_Math" alttext="\Leftrightarrow h" display="inline"><mrow><mi></mi><mo stretchy="false">⇔</mo><mi>h</mi></mrow></math> is a quotient map;
and if <math id="S0.I1.i19.p1.m7" class="ltx_Math" alttext="Z" display="inline"><mi>Z</mi></math> is Hausdorff so is <math id="S0.I1.i19.p1.m8" class="ltx_math_unparsed" alttext="X/\!\!\sim" display="inline"><mrow><mi>X</mi><mpadded width="0.170em"><mo>/</mo></mpadded><mo>∼</mo></mrow></math>.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1" class="ltx_section">
<h2 class="ltx_title ltx_font_bold ltx_title_section" style="font-size:144%;color:#1A3873;">1  Connectedness and Compactness</h2>

<section id="S1.SS1" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.1  (§23) Connected spaces</h3>

<div id="S1.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S1.I1" class="ltx_itemize">
<li id="S1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> For disjoint spaces <math id="S1.I1.i1.p1.m1" class="ltx_Math" alttext="C,D" display="inline"><mrow><mi>C</mi><mo>,</mo><mi>D</mi></mrow></math>: the <em class="ltx_emph ltx_font_italic">disjoint union</em> <math id="S1.I1.i1.p1.m2" class="ltx_Math" alttext="C\sqcup D" display="inline"><mrow><mi>C</mi><mo>⊔</mo><mi>D</mi></mrow></math> carries the
topology consisting of those <math id="S1.I1.i1.p1.m3" class="ltx_Math" alttext="W" display="inline"><mi>W</mi></math> with <math id="S1.I1.i1.p1.m4" class="ltx_Math" alttext="C\cap W" display="inline"><mrow><mi>C</mi><mo>∩</mo><mi>W</mi></mrow></math> open in <math id="S1.I1.i1.p1.m5" class="ltx_Math" alttext="C" display="inline"><mi>C</mi></math> and <math id="S1.I1.i1.p1.m6" class="ltx_Math" alttext="D\cap W" display="inline"><mrow><mi>D</mi><mo>∩</mo><mi>W</mi></mrow></math> open in <math id="S1.I1.i1.p1.m7" class="ltx_Math" alttext="D" display="inline"><mi>D</mi></math>;
the finest making both inclusions continuous.</p>
</div>
</li>
<li id="S1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> <math id="S1.I1.i2.p1.m1" class="ltx_Math" alttext="C\sqcup D" display="inline"><mrow><mi>C</mi><mo>⊔</mo><mi>D</mi></mrow></math> is also called the <em class="ltx_emph ltx_font_italic">sum</em>, or <em class="ltx_emph ltx_font_italic">coproduct</em>, of <math id="S1.I1.i2.p1.m2" class="ltx_Math" alttext="C" display="inline"><mi>C</mi></math> and <math id="S1.I1.i2.p1.m3" class="ltx_Math" alttext="D" display="inline"><mi>D</mi></math>;
it has a universal property dual to that of the product <math id="S1.I1.i2.p1.m4" class="ltx_Math" alttext="C\times D" display="inline"><mrow><mi>C</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>D</mi></mrow></math>.
Every <math id="S1.I1.i2.p1.m5" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is trivially <math id="S1.I1.i2.p1.m6" class="ltx_Math" alttext="C\sqcup D" display="inline"><mrow><mi>C</mi><mo>⊔</mo><mi>D</mi></mrow></math> with <math id="S1.I1.i2.p1.m7" class="ltx_Math" alttext="C=\emptyset" display="inline"><mrow><mi>C</mi><mo>=</mo><mi mathvariant="normal">∅</mi></mrow></math> or <math id="S1.I1.i2.p1.m8" class="ltx_Math" alttext="D=\emptyset" display="inline"><mrow><mi>D</mi><mo>=</mo><mi mathvariant="normal">∅</mi></mrow></math>;
if <math id="S1.I1.i2.p1.m9" class="ltx_Math" alttext="X\cong C\sqcup D" display="inline"><mrow><mi>X</mi><mo>≅</mo><mrow><mi>C</mi><mo>⊔</mo><mi>D</mi></mrow></mrow></math> non-trivially, <math id="S1.I1.i2.p1.m10" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">disconnected</em>.</p>
</div>
</li>
<li id="S1.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i3.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">separation</em> of <math id="S1.I1.i3.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>: a pair <math id="S1.I1.i3.p1.m3" class="ltx_Math" alttext="U,V" display="inline"><mrow><mi>U</mi><mo>,</mo><mi>V</mi></mrow></math> of disjoint nonempty open sets with
<math id="S1.I1.i3.p1.m4" class="ltx_Math" alttext="U\cup V=X" display="inline"><mrow><mrow><mi>U</mi><mo>∪</mo><mi>V</mi></mrow><mo>=</mo><mi>X</mi></mrow></math>. <math id="S1.I1.i3.p1.m5" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">connected</em> if no separation exists.</p>
</div>
</li>
<li id="S1.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Being connected is a topological property. The empty space needs care: some authors
declare <math id="S1.I1.i4.p1.m1" class="ltx_Math" alttext="\emptyset" display="inline"><mi mathvariant="normal">∅</mi></math> not connected, much as <math id="S1.I1.i4.p1.m2" class="ltx_Math" alttext="1" display="inline"><mn>1</mn></math> has no proper factors yet is not counted
as a prime.</p>
</div>
</li>
<li id="S1.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I1.i5.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is connected <math id="S1.I1.i5.p1.m3" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> the only clopen subsets are <math id="S1.I1.i5.p1.m4" class="ltx_Math" alttext="\emptyset" display="inline"><mi mathvariant="normal">∅</mi></math> and <math id="S1.I1.i5.p1.m5" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>.</p>
</div>
<div id="S1.I1.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> In a separation <math id="S1.I1.i5.p2.m1" class="ltx_Math" alttext="V=X-U" display="inline"><mrow><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">U</mi></mrow></mrow></math>, so “<math id="S1.I1.i5.p2.m2" class="ltx_Math" alttext="U,V" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">V</mi></mrow></math> both open” <math id="S1.I1.i5.p2.m3" class="ltx_Math" alttext="=" display="inline"><mo mathcolor="#3D3D3D">=</mo></math> “<math id="S1.I1.i5.p2.m4" class="ltx_Math" alttext="U" display="inline"><mi mathcolor="#3D3D3D">U</mi></math> clopen”, and “both nonempty”
<math id="S1.I1.i5.p2.m5" class="ltx_Math" alttext="=" display="inline"><mo mathcolor="#3D3D3D">=</mo></math> “<math id="S1.I1.i5.p2.m6" class="ltx_Math" alttext="U\neq\emptyset,X" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">≠</mo><mrow><mi mathcolor="#3D3D3D" mathvariant="normal">∅</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">X</mi></mrow></mrow></math>”. Cleanest working form of the definition.</span></span></p>
</div>
</li>
<li id="S1.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I1.i6.p1.m1" class="ltx_Math" alttext="U,V" display="inline"><mrow><mi>U</mi><mo>,</mo><mi>V</mi></mrow></math> a separation <math id="S1.I1.i6.p1.m2" class="ltx_Math" alttext="\Rightarrow X\cong U\sqcup V" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mi>X</mi><mo>≅</mo><mrow><mi>U</mi><mo>⊔</mo><mi>V</mi></mrow></mrow></math>; conversely <math id="S1.I1.i6.p1.m3" class="ltx_Math" alttext="X=C\sqcup D" display="inline"><mrow><mi>X</mi><mo>=</mo><mrow><mi>C</mi><mo>⊔</mo><mi>D</mi></mrow></mrow></math> with both
nonempty gives a separation.</p>
</div>
</li>
<li id="S1.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Equivalent formulation: a separation is a pair of disjoint nonempty sets
<math id="S1.I1.i7.p1.m1" class="ltx_Math" alttext="A,B" display="inline"><mrow><mi>A</mi><mo>,</mo><mi>B</mi></mrow></math> with <math id="S1.I1.i7.p1.m2" class="ltx_Math" alttext="A\cup B=X" display="inline"><mrow><mrow><mi>A</mi><mo>∪</mo><mi>B</mi></mrow><mo>=</mo><mi>X</mi></mrow></math>, neither containing a limit point of the other
(<math id="S1.I1.i7.p1.m3" class="ltx_Math" alttext="\bar{A}\cap B=\emptyset=A\cap\bar{B}" display="inline"><mrow><mrow><mover accent="true"><mi>A</mi><mo>¯</mo></mover><mo>∩</mo><mi>B</mi></mrow><mo>=</mo><mi mathvariant="normal">∅</mi><mo>=</mo><mrow><mi>A</mi><mo>∩</mo><mover accent="true"><mi>B</mi><mo>¯</mo></mover></mrow></mrow></math>).</p>
</div>
</li>
<li id="S1.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> One-point spaces are connected.
Sierpiński <math id="S1.I1.i8.p1.m1" class="ltx_Math" alttext="\{a,b\}" display="inline"><mrow><mo stretchy="false">{</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">}</mo></mrow></math> is connected (<math id="S1.I1.i8.p1.m2" class="ltx_Math" alttext="\{a\}" display="inline"><mrow><mo stretchy="false">{</mo><mi>a</mi><mo stretchy="false">}</mo></mrow></math> open not closed, <math id="S1.I1.i8.p1.m3" class="ltx_Math" alttext="\{b\}" display="inline"><mrow><mo stretchy="false">{</mo><mi>b</mi><mo stretchy="false">}</mo></mrow></math> closed not open).
<math id="S1.I1.i8.p1.m4" class="ltx_Math" alttext="[-1,0)\cup(0,1]" display="inline"><mrow><mrow><mo stretchy="false">[</mo><mrow><mo>−</mo><mn>1</mn></mrow><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow><mo>∪</mo><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></mrow></math> is disconnected.</p>
</div>
</li>
<li id="S1.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Coming in §24: <math id="S1.I1.i9.p1.m1" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math> is connected, as is every interval
<math id="S1.I1.i9.p1.m2" class="ltx_Math" alttext="[a,b]" display="inline"><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">]</mo></mrow></math>, <math id="S1.I1.i9.p1.m3" class="ltx_Math" alttext="[a,b)" display="inline"><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></math>, <math id="S1.I1.i9.p1.m4" class="ltx_Math" alttext="(a,b]" display="inline"><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">]</mo></mrow></math>, <math id="S1.I1.i9.p1.m5" class="ltx_Math" alttext="(a,b)" display="inline"><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></math> for <math id="S1.I1.i9.p1.m6" class="ltx_Math" alttext="-\infty\leq a\leq b\leq\infty" display="inline"><mrow><mrow><mo>−</mo><mi mathvariant="normal">∞</mi></mrow><mo>≤</mo><mi>a</mi><mo>≤</mo><mi>b</mi><mo>≤</mo><mi mathvariant="normal">∞</mi></mrow></math>.</p>
</div>
</li>
<li id="S1.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Every <math id="S1.I1.i10.p1.m1" class="ltx_Math" alttext="X\subset\mathbb{Q}" display="inline"><mrow><mi>X</mi><mo>⊂</mo><mi>ℚ</mi></mrow></math> with <math id="S1.I1.i10.p1.m2" class="ltx_Math" alttext="\geq 2" display="inline"><mrow><mi></mi><mo>≥</mo><mn>2</mn></mrow></math> points is disconnected:
pick irrational <math id="S1.I1.i10.p1.m3" class="ltx_Math" alttext="a" display="inline"><mi>a</mi></math> between <math id="S1.I1.i10.p1.m4" class="ltx_Math" alttext="p&lt;q" display="inline"><mrow><mi>p</mi><mo>&lt;</mo><mi>q</mi></mrow></math> in <math id="S1.I1.i10.p1.m5" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> and cut at <math id="S1.I1.i10.p1.m6" class="ltx_Math" alttext="a" display="inline"><mi>a</mi></math>.</p>
</div>
</li>
<li id="S1.I1.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i11.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i11.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I1.i11.p1.m2" class="ltx_Math" alttext="U,V" display="inline"><mrow><mi>U</mi><mo>,</mo><mi>V</mi></mrow></math> a separation of <math id="S1.I1.i11.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>, <math id="S1.I1.i11.p1.m4" class="ltx_Math" alttext="A\subset X" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>X</mi></mrow></math> connected <math id="S1.I1.i11.p1.m5" class="ltx_Math" alttext="\Rightarrow A\subset U" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mi>A</mi><mo>⊂</mo><mi>U</mi></mrow></math> or <math id="S1.I1.i11.p1.m6" class="ltx_Math" alttext="A\subset V" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>V</mi></mrow></math>.</p>
</div>
<div id="S1.I1.i11.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I1.i11.p2.m1" class="ltx_Math" alttext="A\cap U" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">∩</mo><mi mathcolor="#3D3D3D">U</mi></mrow></math> is clopen in <math id="S1.I1.i11.p2.m2" class="ltx_Math" alttext="A" display="inline"><mi mathcolor="#3D3D3D">A</mi></math>. The single most-used lemma of the section.</span></span></p>
</div>
</li>
<li id="S1.I1.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i12.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i12.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> A union of connected subspaces with a point in common is connected.</p>
</div>
</li>
<li id="S1.I1.i13" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i13.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i13.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I1.i13.p1.m2" class="ltx_Math" alttext="A\subset B\subset\bar{A}" display="inline"><mrow><mi>A</mi><mo>⊂</mo><mi>B</mi><mo>⊂</mo><mover accent="true"><mi>A</mi><mo>¯</mo></mover></mrow></math>, <math id="S1.I1.i13.p1.m3" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> connected <math id="S1.I1.i13.p1.m4" class="ltx_Math" alttext="\Rightarrow B" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mi>B</mi></mrow></math> connected.
(Adding limit points cannot disconnect.)</p>
</div>
</li>
<li id="S1.I1.i14" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i14.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i14.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> The continuous image of a connected space is connected.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS2" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.2  (§24) Connected subspaces of the real line</h3>

<div id="S1.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S1.I2" class="ltx_itemize">
<li id="S1.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I2.i1.p1.m1" class="ltx_Math" alttext="C\subset\mathbb{R}" display="inline"><mrow><mi>C</mi><mo>⊂</mo><mi>ℝ</mi></mrow></math> is <em class="ltx_emph ltx_font_italic">convex</em> if <math id="S1.I2.i1.p1.m2" class="ltx_Math" alttext="a&lt;b" display="inline"><mrow><mi>a</mi><mo>&lt;</mo><mi>b</mi></mrow></math> in <math id="S1.I2.i1.p1.m3" class="ltx_Math" alttext="C" display="inline"><mi>C</mi></math> <math id="S1.I2.i1.p1.m4" class="ltx_Math" alttext="\Rightarrow[a,b]\subset C" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">]</mo></mrow><mo>⊂</mo><mi>C</mi></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> The convex subsets of <math id="S1.I2.i2.p1.m1" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>: <math id="S1.I2.i2.p1.m2" class="ltx_Math" alttext="\emptyset" display="inline"><mi mathvariant="normal">∅</mi></math>; the intervals <math id="S1.I2.i2.p1.m3" class="ltx_Math" alttext="(a,b),[a,b),(a,b],[a,b]" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow><mo>,</mo><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">)</mo></mrow><mo>,</mo><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">]</mo></mrow><mo>,</mo><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">]</mo></mrow></mrow></math>;
the rays; and <math id="S1.I2.i2.p1.m4" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math>.</p>
</div>
</li>
<li id="S1.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i3.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> Every convex <math id="S1.I2.i3.p1.m2" class="ltx_Math" alttext="C\subset\mathbb{R}" display="inline"><mrow><mi>C</mi><mo>⊂</mo><mi>ℝ</mi></mrow></math> is connected. In particular <math id="S1.I2.i3.p1.m3" class="ltx_Math" alttext="\mathbb{R}" display="inline"><mi>ℝ</mi></math> is connected.</p>
</div>
<div id="S1.I2.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Reduce to <math id="S1.I2.i3.p2.m1" class="ltx_Math" alttext="[a,b]" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow></math>. Given <math id="S1.I2.i3.p2.m2" class="ltx_Math" alttext="[a,b]=U\sqcup V" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">⊔</mo><mi mathcolor="#3D3D3D">V</mi></mrow></mrow></math> with <math id="S1.I2.i3.p2.m3" class="ltx_Math" alttext="a\in U,b\in V" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">U</mi></mrow><mo mathcolor="#3D3D3D">,</mo><mrow><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">V</mi></mrow></mrow></math>, let <math id="S1.I2.i3.p2.m4" class="ltx_Math" alttext="c=\sup U" display="inline"><mrow><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D" rspace="0.1389em">=</mo><mrow><mo lspace="0.1389em" mathcolor="#3D3D3D" rspace="0.167em">sup</mo><mi mathcolor="#3D3D3D">U</mi></mrow></mrow></math>.
Then <math id="S1.I2.i3.p2.m5" class="ltx_Math" alttext="c\in\bar{U}=U" display="inline"><mrow><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D">∈</mo><mover accent="true"><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">¯</mo></mover><mo mathcolor="#3D3D3D">=</mo><mi mathcolor="#3D3D3D">U</mi></mrow></math>, so <math id="S1.I2.i3.p2.m6" class="ltx_Math" alttext="c\neq b" display="inline"><mrow><mi mathcolor="#3D3D3D">c</mi><mo mathcolor="#3D3D3D">≠</mo><mi mathcolor="#3D3D3D">b</mi></mrow></math>; but <math id="S1.I2.i3.p2.m7" class="ltx_Math" alttext="U" display="inline"><mi mathcolor="#3D3D3D">U</mi></math> open gives points <math id="S1.I2.i3.p2.m8" class="ltx_Math" alttext="&gt;c" display="inline"><mrow><mi></mi><mo mathcolor="#3D3D3D">&gt;</mo><mi mathcolor="#3D3D3D">c</mi></mrow></math> in <math id="S1.I2.i3.p2.m9" class="ltx_Math" alttext="U" display="inline"><mi mathcolor="#3D3D3D">U</mi></math> —
contradicting the supremum. Least upper bound property is doing all the work.</span></span></p>
</div>
</li>
<li id="S1.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i4.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Intermediate value theorem.)</span> <math id="S1.I2.i4.p1.m2" class="ltx_Math" alttext="f\colon X\to\mathbb{R}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>ℝ</mi></mrow></mrow></math> continuous,
<math id="S1.I2.i4.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> connected, <math id="S1.I2.i4.p1.m4" class="ltx_Math" alttext="r" display="inline"><mi>r</mi></math> between <math id="S1.I2.i4.p1.m5" class="ltx_Math" alttext="f(a)" display="inline"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>a</mi><mo stretchy="false">)</mo></mrow></mrow></math> and <math id="S1.I2.i4.p1.m6" class="ltx_Math" alttext="f(b)" display="inline"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></mrow></math> <math id="S1.I2.i4.p1.m7" class="ltx_Math" alttext="\Rightarrow\exists c" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mrow><mo rspace="0.167em">∃</mo><mi>c</mi></mrow></mrow></math> with <math id="S1.I2.i4.p1.m8" class="ltx_Math" alttext="f(c)=r" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>c</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mi>r</mi></mrow></math>.</p>
</div>
<div id="S1.I2.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Otherwise <math id="S1.I2.i4.p2.m1" class="ltx_Math" alttext="f^{-1}(-\infty,r)" display="inline"><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D" mathvariant="normal">∞</mi></mrow><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">r</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> and <math id="S1.I2.i4.p2.m2" class="ltx_Math" alttext="f^{-1}(r,\infty)" display="inline"><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">r</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D" mathvariant="normal">∞</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> separate <math id="S1.I2.i4.p2.m3" class="ltx_Math" alttext="X" display="inline"><mi mathcolor="#3D3D3D">X</mi></math>.</span></span></p>
</div>
</li>
<li id="S1.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">path</em> from <math id="S1.I2.i5.p1.m1" class="ltx_Math" alttext="x" display="inline"><mi>x</mi></math> to <math id="S1.I2.i5.p1.m2" class="ltx_Math" alttext="y" display="inline"><mi>y</mi></math>: a map <math id="S1.I2.i5.p1.m3" class="ltx_Math" alttext="f\colon[a,b]\to X" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mo stretchy="false">[</mo><mi>a</mi><mo>,</mo><mi>b</mi><mo stretchy="false">]</mo></mrow><mo stretchy="false">→</mo><mi>X</mi></mrow></mrow></math>, <math id="S1.I2.i5.p1.m4" class="ltx_Math" alttext="f(a)=x" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>a</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mi>x</mi></mrow></math>, <math id="S1.I2.i5.p1.m5" class="ltx_Math" alttext="f(b)=y" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>b</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mi>y</mi></mrow></math>.
<math id="S1.I2.i5.p1.m6" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">path connected</em> if any two points are joined by a path.</p>
</div>
</li>
<li id="S1.I2.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i6.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i6.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> Path connected <math id="S1.I2.i6.p1.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> connected.</p>
</div>
<div id="S1.I2.i6.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> A separation of <math id="S1.I2.i6.p2.m1" class="ltx_Math" alttext="X" display="inline"><mi mathcolor="#3D3D3D">X</mi></math> would pull back to a separation of <math id="S1.I2.i6.p2.m2" class="ltx_Math" alttext="[a,b]" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow></math>.</span></span></p>
</div>
</li>
<li id="S1.I2.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> The continuous image of a path connected space is path connected.</p>
</div>
</li>
<li id="S1.I2.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I2.i8.p1.m1" class="ltx_Math" alttext="C" display="inline"><mi>C</mi></math> in a real vector space is <em class="ltx_emph ltx_font_italic">convex</em> if <math id="S1.I2.i8.p1.m2" class="ltx_Math" alttext="(1-t)x+ty\in C" display="inline"><mrow><mrow><mrow><mrow><mo stretchy="false">(</mo><mrow><mn>1</mn><mo>−</mo><mi>t</mi></mrow><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mi>x</mi></mrow><mo>+</mo><mrow><mi>t</mi><mo>⁢</mo><mi>y</mi></mrow></mrow><mo>∈</mo><mi>C</mi></mrow></math> for
<math id="S1.I2.i8.p1.m3" class="ltx_Math" alttext="x,y\in C" display="inline"><mrow><mrow><mi>x</mi><mo>,</mo><mi>y</mi></mrow><mo>∈</mo><mi>C</mi></mrow></math>, <math id="S1.I2.i8.p1.m4" class="ltx_Math" alttext="t\in[0,1]" display="inline"><mrow><mi>t</mi><mo>∈</mo><mrow><mo stretchy="false">[</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Convex subsets of <math id="S1.I2.i9.p1.m1" class="ltx_Math" alttext="\mathbb{R}^{n}" display="inline"><msup><mi>ℝ</mi><mi>n</mi></msup></math> are path connected — e.g. the unit ball
<math id="S1.I2.i9.p1.m2" class="ltx_Math" alttext="B^{n}=\{\|x\|\leq 1\}" display="inline"><mrow><msup><mi>B</mi><mi>n</mi></msup><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mrow><mo stretchy="false">‖</mo><mi>x</mi><mo stretchy="false">‖</mo></mrow><mo>≤</mo><mn>1</mn></mrow><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I2.i10.p1.m1" class="ltx_Math" alttext="\mathbb{R}^{n}-\{0\}" display="inline"><mrow><msup><mi>ℝ</mi><mi>n</mi></msup><mo>−</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></math> is path connected for <math id="S1.I2.i10.p1.m2" class="ltx_Math" alttext="n\geq 2" display="inline"><mrow><mi>n</mi><mo>≥</mo><mn>2</mn></mrow></math> (not for <math id="S1.I2.i10.p1.m3" class="ltx_Math" alttext="n=1" display="inline"><mrow><mi>n</mi><mo>=</mo><mn>1</mn></mrow></math>).
Hence <math id="S1.I2.i10.p1.m4" class="ltx_Math" alttext="S^{n-1}=\{\|x\|=1\}" display="inline"><mrow><msup><mi>S</mi><mrow><mi>n</mi><mo>−</mo><mn>1</mn></mrow></msup><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mrow><mo stretchy="false">‖</mo><mi>x</mi><mo stretchy="false">‖</mo></mrow><mo>=</mo><mn>1</mn></mrow><mo stretchy="false">}</mo></mrow></mrow></math> is path connected for <math id="S1.I2.i10.p1.m5" class="ltx_Math" alttext="n\geq 2" display="inline"><mrow><mi>n</mi><mo>≥</mo><mn>2</mn></mrow></math>, being the image of
<math id="S1.I2.i10.p1.m6" class="ltx_Math" alttext="x\mapsto x/\|x\|" display="inline"><mrow><mi>x</mi><mo stretchy="false">↦</mo><mrow><mi>x</mi><mo>/</mo><mrow><mo stretchy="false">‖</mo><mi>x</mi><mo stretchy="false">‖</mo></mrow></mrow></mrow></math>. (<math id="S1.I2.i10.p1.m7" class="ltx_Math" alttext="S^{0}=\{\pm 1\}" display="inline"><mrow><msup><mi>S</mi><mn>0</mn></msup><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mo>±</mo><mn>1</mn></mrow><mo stretchy="false">}</mo></mrow></mrow></math> is not.)</p>
</div>
</li>
<li id="S1.I2.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i11.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i11.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> <span class="ltx_text ltx_font_bold">Topologist’s sine curve.</span>
<math id="S1.I2.i11.p1.m2" class="ltx_Math" alttext="S=\{(x,\sin(1/x))\mid 0&lt;x\leq 1\}" display="inline"><mrow><mi>S</mi><mo>=</mo><mrow><mo stretchy="false">{</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mrow><mi>sin</mi><mo>⁡</mo><mrow><mo stretchy="false">(</mo><mrow><mn>1</mn><mo>/</mo><mi>x</mi></mrow><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">)</mo></mrow><mo fence="true" lspace="0em" rspace="0em">∣</mo><mrow><mn>0</mn><mo>&lt;</mo><mi>x</mi><mo>≤</mo><mn>1</mn></mrow><mo stretchy="false">}</mo></mrow></mrow></math>,   <math id="S1.I2.i11.p1.m3" class="ltx_Math" alttext="\bar{S}=S\cup V" display="inline"><mrow><mover accent="true"><mi>S</mi><mo>¯</mo></mover><mo>=</mo><mrow><mi>S</mi><mo>∪</mo><mi>V</mi></mrow></mrow></math> with <math id="S1.I2.i11.p1.m4" class="ltx_Math" alttext="V=\{0\}\times[-1,1]" display="inline"><mrow><mi>V</mi><mo>=</mo><mrow><mrow><mo stretchy="false">{</mo><mn>0</mn><mo rspace="0.055em" stretchy="false">}</mo></mrow><mo rspace="0.222em">×</mo><mrow><mo stretchy="false">[</mo><mrow><mo>−</mo><mn>1</mn></mrow><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></mrow></mrow></math>.
<math id="S1.I2.i11.p1.m5" class="ltx_Math" alttext="S" display="inline"><mi>S</mi></math> is connected (continuous image of <math id="S1.I2.i11.p1.m6" class="ltx_Math" alttext="(0,1]" display="inline"><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo stretchy="false">]</mo></mrow></math>), hence so is <math id="S1.I2.i11.p1.m7" class="ltx_Math" alttext="\bar{S}" display="inline"><mover accent="true"><mi>S</mi><mo>¯</mo></mover></math>.
But <math id="S1.I2.i11.p1.m8" class="ltx_Math" alttext="\bar{S}" display="inline"><mover accent="true"><mi>S</mi><mo>¯</mo></mover></math> is <em class="ltx_emph ltx_font_italic">not</em> path connected.</p>
</div>
<div id="S1.I2.i11.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> A path from <math id="S1.I2.i11.p2.m1" class="ltx_Math" alttext="V" display="inline"><mi mathcolor="#3D3D3D">V</mi></math> into <math id="S1.I2.i11.p2.m2" class="ltx_Math" alttext="S" display="inline"><mi mathcolor="#3D3D3D">S</mi></math>: reparametrise so <math id="S1.I2.i11.p2.m3" class="ltx_Math" alttext="f(0)\in V" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">0</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">V</mi></mrow></math>, <math id="S1.I2.i11.p2.m4" class="ltx_Math" alttext="f(t)\in S" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">t</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">S</mi></mrow></math> for <math id="S1.I2.i11.p2.m5" class="ltx_Math" alttext="t&gt;0" display="inline"><mrow><mi mathcolor="#3D3D3D">t</mi><mo mathcolor="#3D3D3D">&gt;</mo><mn mathcolor="#3D3D3D">0</mn></mrow></math>.
Write <math id="S1.I2.i11.p2.m6" class="ltx_Math" alttext="f=(x,y)" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">y</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math>. Construct <math id="S1.I2.i11.p2.m7" class="ltx_Math" alttext="t_{n}\to 0" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">t</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">→</mo><mn mathcolor="#3D3D3D">0</mn></mrow></math> with <math id="S1.I2.i11.p2.m8" class="ltx_Math" alttext="y(t_{n})=(-1)^{n}" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">y</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">t</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><msup><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mi mathcolor="#3D3D3D">n</mi></msup></mrow></math> via the IVT applied to <math id="S1.I2.i11.p2.m9" class="ltx_Math" alttext="x" display="inline"><mi mathcolor="#3D3D3D">x</mi></math>.
Then <math id="S1.I2.i11.p2.m10" class="ltx_Math" alttext="y(t_{n})" display="inline"><mrow><mi mathcolor="#3D3D3D">y</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">t</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> does not converge — contradicting continuity.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:59:15 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
