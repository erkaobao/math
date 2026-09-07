---
layout: archive
title: "MATH 5345H --- Week 15: Homotopy of paths; course review"
permalink: /teaching/5345h_notes/week_15
author_profile: false
render_with_liquid: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

{% raw %}
<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S1" class="ltx_section">
<h2 class="ltx_title ltx_font_bold ltx_title_section" style="font-size:144%;color:#1A3873;">1  The Fundamental Group</h2>

<section id="S1.SS1" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.1  (§51) Homotopy of paths</h3>

<div id="S1.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S1.I1" class="ltx_itemize">
<li id="S1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I1.i1.p1.m2" class="ltx_Math" alttext="f,g\colon X\to Y" display="inline"><mrow><mrow><mi>f</mi><mo>,</mo><mi>g</mi></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> are <em class="ltx_emph ltx_font_italic">homotopic</em>, <math id="S1.I1.i1.p1.m3" class="ltx_Math" alttext="f\simeq g" display="inline"><mrow><mi>f</mi><mo>≃</mo><mi>g</mi></mrow></math>, if there is a map
<math id="S1.I1.i1.p1.m4" class="ltx_Math" alttext="F\colon X\times I\to Y" display="inline"><mrow><mi>F</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>I</mi></mrow><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> with <math id="S1.I1.i1.p1.m5" class="ltx_Math" alttext="F(x,0)=f(x)" display="inline"><mrow><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>, <math id="S1.I1.i1.p1.m6" class="ltx_Math" alttext="F(x,1)=g(x)" display="inline"><mrow><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>. <math id="S1.I1.i1.p1.m7" class="ltx_Math" alttext="F" display="inline"><mi>F</mi></math> is a <em class="ltx_emph ltx_font_italic">homotopy</em>.</p>
</div>
</li>
<li id="S1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> <math id="S1.I1.i2.p1.m1" class="ltx_Math" alttext="f_{t}(x)=F(x,t)" display="inline"><mrow><mrow><msub><mi>f</mi><mi>t</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math>; the rule <math id="S1.I1.i2.p1.m2" class="ltx_Math" alttext="t\mapsto f_{t}" display="inline"><mrow><mi>t</mi><mo stretchy="false">↦</mo><msub><mi>f</mi><mi>t</mi></msub></mrow></math> is a path <math id="S1.I1.i2.p1.m3" class="ltx_Math" alttext="I\to\mathscr{C}(X,Y)" display="inline"><mrow><mi>I</mi><mo stretchy="false">→</mo><mrow><mi class="ltx_font_mathscript">𝒞</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>Y</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></math> from <math id="S1.I1.i2.p1.m4" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> to <math id="S1.I1.i2.p1.m5" class="ltx_Math" alttext="g" display="inline"><mi>g</mi></math>.</p>
</div>
</li>
<li id="S1.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">path</em> in <math id="S1.I1.i3.p1.m1" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math> from <math id="S1.I1.i3.p1.m2" class="ltx_Math" alttext="y_{0}" display="inline"><msub><mi>y</mi><mn>0</mn></msub></math> to <math id="S1.I1.i3.p1.m3" class="ltx_Math" alttext="y_{1}" display="inline"><msub><mi>y</mi><mn>1</mn></msub></math>: a map <math id="S1.I1.i3.p1.m4" class="ltx_Math" alttext="f\colon I\to Y" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>I</mi><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> with
<math id="S1.I1.i3.p1.m5" class="ltx_Math" alttext="f(0)=y_{0}" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><msub><mi>y</mi><mn>0</mn></msub></mrow></math>, <math id="S1.I1.i3.p1.m6" class="ltx_Math" alttext="f(1)=y_{1}" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><msub><mi>y</mi><mn>1</mn></msub></mrow></math>.</p>
</div>
</li>
<li id="S1.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i4.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i4.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> Paths <math id="S1.I1.i4.p1.m2" class="ltx_Math" alttext="f,g" display="inline"><mrow><mi>f</mi><mo>,</mo><mi>g</mi></mrow></math> from <math id="S1.I1.i4.p1.m3" class="ltx_Math" alttext="y_{0}" display="inline"><msub><mi>y</mi><mn>0</mn></msub></math> to <math id="S1.I1.i4.p1.m4" class="ltx_Math" alttext="y_{1}" display="inline"><msub><mi>y</mi><mn>1</mn></msub></math> are <em class="ltx_emph ltx_font_italic">path homotopic</em>, <math id="S1.I1.i4.p1.m5" class="ltx_Math" alttext="f\simeq_{p}g" display="inline"><mrow><mi>f</mi><msub><mo>≃</mo><mi>p</mi></msub><mi>g</mi></mrow></math>,
if there is <math id="S1.I1.i4.p1.m6" class="ltx_Math" alttext="F\colon I\times I\to Y" display="inline"><mrow><mi>F</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>I</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>I</mi></mrow><mo stretchy="false">→</mo><mi>Y</mi></mrow></mrow></math> with
<math id="S1.I1.i4.p1.m7" class="ltx_Math" alttext="F(s,0)=f(s),\ F(s,1)=g(s),\ F(0,t)=y_{0},\ F(1,t)=y_{1}." display="inline"><mrow><mrow><mrow><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo stretchy="false">)</mo></mrow></mrow></mrow><mo rspace="0.667em">,</mo><mrow><mrow><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo>,</mo><mn>1</mn><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo stretchy="false">)</mo></mrow></mrow></mrow><mo rspace="0.667em">,</mo><mrow><mrow><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><msub><mi>y</mi><mn>0</mn></msub></mrow><mo rspace="0.667em">,</mo><mrow><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><msub><mi>y</mi><mn>1</mn></msub></mrow></mrow></mrow></mrow><mo lspace="0em">.</mo></mrow></math>
<span class="ltx_text ltx_font_bold">The endpoints stay fixed throughout.</span></p>
</div>
</li>
<li id="S1.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I1.i5.p1.m1" class="ltx_Math" alttext="\simeq" display="inline"><mo>≃</mo></math> and <math id="S1.I1.i5.p1.m2" class="ltx_Math" alttext="\simeq_{p}" display="inline"><msub><mo>≃</mo><mi>p</mi></msub></math> are equivalence relations.</p>
</div>
<div id="S1.I1.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Reflexive: constant homotopy. Symmetric: <math id="S1.I1.i5.p2.m1" class="ltx_Math" alttext="\bar{F}(x,t)=F(x,1-t)" display="inline"><mrow><mrow><mover accent="true"><mi mathcolor="#3D3D3D">F</mi><mo mathcolor="#3D3D3D">¯</mo></mover><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">t</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">F</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mrow><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">t</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.
Transitive: concatenate,
<math id="S1.I1.i5.p2.m2" class="ltx_Math" alttext="(F\star G)(x,t)=F(x,2t)" display="inline"><mrow><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">F</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">⋆</mo><mi mathcolor="#3D3D3D">G</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">t</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">F</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mrow><mn mathcolor="#3D3D3D">2</mn><mo>⁢</mo><mi mathcolor="#3D3D3D">t</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math> for <math id="S1.I1.i5.p2.m3" class="ltx_Math" alttext="t\leq\tfrac{1}{2}" display="inline"><mrow><mi mathcolor="#3D3D3D">t</mi><mo mathcolor="#3D3D3D">≤</mo><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mn mathcolor="#3D3D3D">2</mn></mfrac></mrow></math>, <math id="S1.I1.i5.p2.m4" class="ltx_Math" alttext="G(x,2t-1)" display="inline"><mrow><mi mathcolor="#3D3D3D">G</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mrow><mrow><mn mathcolor="#3D3D3D">2</mn><mo>⁢</mo><mi mathcolor="#3D3D3D">t</mi></mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> for <math id="S1.I1.i5.p2.m5" class="ltx_Math" alttext="t\geq\tfrac{1}{2}" display="inline"><mrow><mi mathcolor="#3D3D3D">t</mi><mo mathcolor="#3D3D3D">≥</mo><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mn mathcolor="#3D3D3D">2</mn></mfrac></mrow></math>;
continuous by the pasting lemma since <math id="S1.I1.i5.p2.m6" class="ltx_Math" alttext="F(x,1)=g(x)=G(x,0)" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">F</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">g</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mi mathcolor="#3D3D3D">G</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mn mathcolor="#3D3D3D">0</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S1.I1.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> <math id="S1.I1.i6.p1.m1" class="ltx_Math" alttext="[f]" display="inline"><mrow><mo stretchy="false">[</mo><mi>f</mi><mo stretchy="false">]</mo></mrow></math> = homotopy class; for paths, <math id="S1.I1.i6.p1.m2" class="ltx_Math" alttext="[f]" display="inline"><mrow><mo stretchy="false">[</mo><mi>f</mi><mo stretchy="false">]</mo></mrow></math> = <em class="ltx_emph ltx_font_italic">path</em> homotopy class.</p>
</div>
</li>
<li id="S1.I1.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i7.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i7.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> <span class="ltx_text ltx_font_bold">Straight-line homotopy.</span> For <math id="S1.I1.i7.p1.m2" class="ltx_Math" alttext="f,g\colon X\to\mathbb{R}^{2}" display="inline"><mrow><mrow><mi>f</mi><mo>,</mo><mi>g</mi></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><msup><mi>ℝ</mi><mn>2</mn></msup></mrow></mrow></math> (or into any convex
<math id="S1.I1.i7.p1.m3" class="ltx_Math" alttext="Y\subset\mathbb{R}^{n}" display="inline"><mrow><mi>Y</mi><mo>⊂</mo><msup><mi>ℝ</mi><mi>n</mi></msup></mrow></math>):   <math id="S1.I1.i7.p1.m4" class="ltx_Math" alttext="F(x,t)=(1-t)f(x)+tg(x)" display="inline"><mrow><mrow><mi>F</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mrow><mo stretchy="false">(</mo><mrow><mn>1</mn><mo>−</mo><mi>t</mi></mrow><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>+</mo><mrow><mi>t</mi><mo>⁢</mo><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>. So any two maps into a convex set are
homotopic; and if <math id="S1.I1.i7.p1.m5" class="ltx_Math" alttext="f,g" display="inline"><mrow><mi>f</mi><mo>,</mo><mi>g</mi></mrow></math> are paths with the same endpoints, this is a path homotopy.</p>
</div>
</li>
<li id="S1.I1.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i8.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i8.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> In the punctured plane <math id="S1.I1.i8.p1.m2" class="ltx_Math" alttext="Y=\mathbb{R}^{2}-\{0\}" display="inline"><mrow><mi>Y</mi><mo>=</mo><mrow><msup><mi>ℝ</mi><mn>2</mn></msup><mo>−</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></mrow></math>, with
<math id="S1.I1.i8.p1.m3" class="ltx_Math" alttext="f(s)=(\cos\pi s,\sin\pi s)" display="inline"><mrow><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mrow><mi>π</mi><mo>⁢</mo><mi>s</mi></mrow></mrow><mo>,</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mrow><mi>π</mi><mo>⁢</mo><mi>s</mi></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></math>, <math id="S1.I1.i8.p1.m4" class="ltx_Math" alttext="g(s)=(\cos\pi s,2\sin\pi s)" display="inline"><mrow><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mrow><mi>π</mi><mo>⁢</mo><mi>s</mi></mrow></mrow><mo>,</mo><mrow><mn>2</mn><mo lspace="0.167em">⁢</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mrow><mi>π</mi><mo>⁢</mo><mi>s</mi></mrow></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></math>,
<math id="S1.I1.i8.p1.m5" class="ltx_Math" alttext="h(s)=(\cos\pi s,-\sin\pi s)" display="inline"><mrow><mrow><mi>h</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mrow><mi>π</mi><mo>⁢</mo><mi>s</mi></mrow></mrow><mo>,</mo><mrow><mo rspace="0.167em">−</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mrow><mi>π</mi><mo>⁢</mo><mi>s</mi></mrow></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></math>:
<math id="S1.I1.i8.p1.m6" class="ltx_Math" alttext="f\simeq_{p}g" display="inline"><mrow><mi>f</mi><msub><mo>≃</mo><mi>p</mi></msub><mi>g</mi></mrow></math> (the straight-line homotopy stays in <math id="S1.I1.i8.p1.m7" class="ltx_Math" alttext="Y" display="inline"><mi>Y</mi></math>), but the straight-line homotopy
from <math id="S1.I1.i8.p1.m8" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> to <math id="S1.I1.i8.p1.m9" class="ltx_Math" alttext="h" display="inline"><mi>h</mi></math> passes through the origin. In fact <math id="S1.I1.i8.p1.m10" class="ltx_Math" alttext="f\not\simeq_{p}h" display="inline"><mrow><mi>f</mi><msub><mo>≄</mo><mi>p</mi></msub><mi>h</mi></mrow></math> — proved later.</p>
</div>
<div id="S1.I1.i8.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#737373;">Note.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I1.i8.p2.m1" class="ltx_Math" alttext="f" display="inline"><mi mathcolor="#737373">f</mi></math><span class="ltx_text ltx_font_italic"> and <math id="S1.I1.i8.p2.m2" class="ltx_Math" alttext="h" display="inline"><mi mathcolor="#737373">h</mi></math> <em class="ltx_emph ltx_font_upright">are</em> homotopic as maps if endpoints are released. That is why path
homotopy, not homotopy, is the right relation here.</span></span></span></p>
</div>
</li>
<li id="S1.I1.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i9.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i9.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> For <math id="S1.I1.i9.p1.m2" class="ltx_Math" alttext="f" display="inline"><mi>f</mi></math> a path <math id="S1.I1.i9.p1.m3" class="ltx_Math" alttext="x_{0}\to x_{1}" display="inline"><mrow><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">→</mo><msub><mi>x</mi><mn>1</mn></msub></mrow></math> and <math id="S1.I1.i9.p1.m4" class="ltx_Math" alttext="g" display="inline"><mi>g</mi></math> a path <math id="S1.I1.i9.p1.m5" class="ltx_Math" alttext="x_{1}\to x_{2}" display="inline"><mrow><msub><mi>x</mi><mn>1</mn></msub><mo stretchy="false">→</mo><msub><mi>x</mi><mn>2</mn></msub></mrow></math>, the <em class="ltx_emph ltx_font_italic">product</em></p>
<table id="S1.Ex1" class="ltx_equation ltx_eqn_table">

<tbody><tr class="ltx_equation ltx_eqn_row ltx_align_baseline">
<td class="ltx_eqn_cell ltx_eqn_center_padleft"></td>
<td class="ltx_eqn_cell ltx_align_center"><math id="S1.Ex1.m1" class="ltx_Math" alttext="(f*g)(s)=\begin{cases}f(2s)&amp;0\leq s\leq\tfrac{1}{2}\\
g(2s-1)&amp;\tfrac{1}{2}\leq s\leq 1.\end{cases}" display="block"><mrow><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>f</mi><mo lspace="0.222em" rspace="0.222em">∗</mo><mi>g</mi></mrow><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo>{</mo><mtable columnspacing="5pt" displaystyle="true" rowspacing="0pt"><mtr><mtd class="ltx_align_left" columnalign="left"><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mn>2</mn><mo>⁢</mo><mi>s</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></mtd><mtd class="ltx_align_left" columnalign="left"><mrow><mn>0</mn><mo>≤</mo><mi>s</mi><mo>≤</mo><mstyle displaystyle="false"><mfrac><mn>1</mn><mn>2</mn></mfrac></mstyle></mrow></mtd></mtr><mtr><mtd class="ltx_align_left" columnalign="left"><mrow><mi>g</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mrow><mn>2</mn><mo>⁢</mo><mi>s</mi></mrow><mo>−</mo><mn>1</mn></mrow><mo stretchy="false">)</mo></mrow></mrow></mtd><mtd class="ltx_align_left" columnalign="left"><mrow><mrow><mstyle displaystyle="false"><mfrac><mn>1</mn><mn>2</mn></mfrac></mstyle><mo>≤</mo><mi>s</mi><mo>≤</mo><mn>1</mn></mrow><mo lspace="0em">.</mo></mrow></mtd></mtr></mtable></mrow></mrow></math></td>
<td class="ltx_eqn_cell ltx_eqn_center_padright"></td>
</tr></tbody>
</table>
<p class="ltx_p">Continuous by the pasting lemma.</p>
</div>
</li>
<li id="S1.I1.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I1.i10.p1.m1" class="ltx_Math" alttext="f_{0}\simeq_{p}f_{1}" display="inline"><mrow><msub><mi>f</mi><mn>0</mn></msub><msub><mo>≃</mo><mi>p</mi></msub><msub><mi>f</mi><mn>1</mn></msub></mrow></math> and <math id="S1.I1.i10.p1.m2" class="ltx_Math" alttext="g_{0}\simeq_{p}g_{1}" display="inline"><mrow><msub><mi>g</mi><mn>0</mn></msub><msub><mo>≃</mo><mi>p</mi></msub><msub><mi>g</mi><mn>1</mn></msub></mrow></math> <math id="S1.I1.i10.p1.m3" class="ltx_Math" alttext="\Rightarrow f_{0}*g_{0}\simeq_{p}f_{1}*g_{1}" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mrow><msub><mi>f</mi><mn>0</mn></msub><mo lspace="0.222em" rspace="0.222em">∗</mo><msub><mi>g</mi><mn>0</mn></msub></mrow><msub><mo>≃</mo><mi>p</mi></msub><mrow><msub><mi>f</mi><mn>1</mn></msub><mo lspace="0.222em" rspace="0.222em">∗</mo><msub><mi>g</mi><mn>1</mn></msub></mrow></mrow></math>.
Hence <math id="S1.I1.i10.p1.m4" class="ltx_Math" alttext="[f]*[g]=[f*g]" display="inline"><mrow><mrow><mrow><mo stretchy="false">[</mo><mi>f</mi><mo rspace="0.055em" stretchy="false">]</mo></mrow><mo rspace="0.222em">∗</mo><mrow><mo stretchy="false">[</mo><mi>g</mi><mo stretchy="false">]</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">[</mo><mrow><mi>f</mi><mo lspace="0.222em" rspace="0.222em">∗</mo><mi>g</mi></mrow><mo stretchy="false">]</mo></mrow></mrow></math> is well defined.</p>
</div>
</li>
<li id="S1.I1.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i11.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I1.i11.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I1.i11.p1.m2" class="ltx_Math" alttext="*" display="inline"><mo>∗</mo></math> on path homotopy classes satisfies:</p>
<ol id="S1.I1.i11.I1" class="ltx_enumerate">
<li id="S1.I1.i11.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(1)</span> 
<div id="S1.I1.i11.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Associativity</em>: <math id="S1.I1.i11.I1.i1.p1.m1" class="ltx_Math" alttext="([f]*[g])*[h]=[f]*([g]*[h])" display="inline"><mrow><mrow><mrow><mo stretchy="false">(</mo><mrow><mrow><mo stretchy="false">[</mo><mi>f</mi><mo rspace="0.055em" stretchy="false">]</mo></mrow><mo rspace="0.222em">∗</mo><mrow><mo stretchy="false">[</mo><mi>g</mi><mo stretchy="false">]</mo></mrow></mrow><mo rspace="0.055em" stretchy="false">)</mo></mrow><mo rspace="0.222em">∗</mo><mrow><mo stretchy="false">[</mo><mi>h</mi><mo stretchy="false">]</mo></mrow></mrow><mo>=</mo><mrow><mrow><mo stretchy="false">[</mo><mi>f</mi><mo rspace="0.055em" stretchy="false">]</mo></mrow><mo rspace="0.222em">∗</mo><mrow><mo stretchy="false">(</mo><mrow><mrow><mo stretchy="false">[</mo><mi>g</mi><mo rspace="0.055em" stretchy="false">]</mo></mrow><mo rspace="0.222em">∗</mo><mrow><mo stretchy="false">[</mo><mi>h</mi><mo stretchy="false">]</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>;</p>
</div>
</li>
<li id="S1.I1.i11.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(2)</span> 
<div id="S1.I1.i11.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Units</em>: with <math id="S1.I1.i11.I1.i2.p1.m1" class="ltx_Math" alttext="e_{x}(s)\equiv x" display="inline"><mrow><mrow><msub><mi>e</mi><mi>x</mi></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo stretchy="false">)</mo></mrow></mrow><mo>≡</mo><mi>x</mi></mrow></math> the constant path,
<math id="S1.I1.i11.I1.i2.p1.m2" class="ltx_Math" alttext="[e_{x_{0}}]*[f]=[f]=[f]*[e_{x_{1}}]" display="inline"><mrow><mrow><mrow><mo stretchy="false">[</mo><msub><mi>e</mi><msub><mi>x</mi><mn>0</mn></msub></msub><mo rspace="0.055em" stretchy="false">]</mo></mrow><mo rspace="0.222em">∗</mo><mrow><mo stretchy="false">[</mo><mi>f</mi><mo stretchy="false">]</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">[</mo><mi>f</mi><mo stretchy="false">]</mo></mrow><mo>=</mo><mrow><mrow><mo stretchy="false">[</mo><mi>f</mi><mo rspace="0.055em" stretchy="false">]</mo></mrow><mo rspace="0.222em">∗</mo><mrow><mo stretchy="false">[</mo><msub><mi>e</mi><msub><mi>x</mi><mn>1</mn></msub></msub><mo stretchy="false">]</mo></mrow></mrow></mrow></math>;</p>
</div>
</li>
<li id="S1.I1.i11.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">(3)</span> 
<div id="S1.I1.i11.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><em class="ltx_emph ltx_font_italic">Inverses</em>: with <math id="S1.I1.i11.I1.i3.p1.m1" class="ltx_Math" alttext="\bar{f}(s)=f(1-s)" display="inline"><mrow><mrow><mover accent="true"><mi>f</mi><mo>¯</mo></mover><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>s</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>f</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mn>1</mn><mo>−</mo><mi>s</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>,
<math id="S1.I1.i11.I1.i3.p1.m2" class="ltx_Math" alttext="[f]*[\bar{f}]=[e_{x_{0}}]" display="inline"><mrow><mrow><mrow><mo stretchy="false">[</mo><mi>f</mi><mo rspace="0.055em" stretchy="false">]</mo></mrow><mo rspace="0.222em">∗</mo><mrow><mo stretchy="false">[</mo><mover accent="true"><mi>f</mi><mo>¯</mo></mover><mo stretchy="false">]</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">[</mo><msub><mi>e</mi><msub><mi>x</mi><mn>0</mn></msub></msub><mo stretchy="false">]</mo></mrow></mrow></math> and <math id="S1.I1.i11.I1.i3.p1.m3" class="ltx_Math" alttext="[\bar{f}]*[f]=[e_{x_{1}}]" display="inline"><mrow><mrow><mrow><mo stretchy="false">[</mo><mover accent="true"><mi>f</mi><mo>¯</mo></mover><mo rspace="0.055em" stretchy="false">]</mo></mrow><mo rspace="0.222em">∗</mo><mrow><mo stretchy="false">[</mo><mi>f</mi><mo stretchy="false">]</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">[</mo><msub><mi>e</mi><msub><mi>x</mi><mn>1</mn></msub></msub><mo stretchy="false">]</mo></mrow></mrow></math>.</p>
</div>
</li>
</ol>
</div>
<div id="S1.I1.i11.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> All three are reparametrisation homotopies. For (1) let the breakpoints slide:
traverse <math id="S1.I1.i11.p2.m1" class="ltx_Math" alttext="f" display="inline"><mi mathcolor="#3D3D3D">f</mi></math> on <math id="S1.I1.i11.p2.m2" class="ltx_Math" alttext="0\leq s\leq(1+t)/4" display="inline"><mrow><mn mathcolor="#3D3D3D">0</mn><mo mathcolor="#3D3D3D">≤</mo><mi mathcolor="#3D3D3D">s</mi><mo mathcolor="#3D3D3D">≤</mo><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">+</mo><mi mathcolor="#3D3D3D">t</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D">/</mo><mn mathcolor="#3D3D3D">4</mn></mrow></mrow></math>, <math id="S1.I1.i11.p2.m3" class="ltx_Math" alttext="g" display="inline"><mi mathcolor="#3D3D3D">g</mi></math> on <math id="S1.I1.i11.p2.m4" class="ltx_Math" alttext="(1+t)/4\leq s\leq(2+t)/4" display="inline"><mrow><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">+</mo><mi mathcolor="#3D3D3D">t</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D">/</mo><mn mathcolor="#3D3D3D">4</mn></mrow><mo mathcolor="#3D3D3D">≤</mo><mi mathcolor="#3D3D3D">s</mi><mo mathcolor="#3D3D3D">≤</mo><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mn mathcolor="#3D3D3D">2</mn><mo mathcolor="#3D3D3D">+</mo><mi mathcolor="#3D3D3D">t</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D">/</mo><mn mathcolor="#3D3D3D">4</mn></mrow></mrow></math>, <math id="S1.I1.i11.p2.m5" class="ltx_Math" alttext="h" display="inline"><mi mathcolor="#3D3D3D">h</mi></math> thereafter.
Draw the square with the two subdivision patterns and interpolate.</span></span></p>
</div>
</li>
<li id="S1.I1.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i12.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> <math id="S1.I1.i12.p1.m1" class="ltx_Math" alttext="*" display="inline"><mo>∗</mo></math> is <em class="ltx_emph ltx_font_italic">not</em> a group operation on paths — only on path homotopy classes,
and only when endpoints match.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS2" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.2  (§52) The fundamental group</h3>

<div id="S1.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S1.I2" class="ltx_itemize">
<li id="S1.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">loop</em> at <math id="S1.I2.i1.p1.m1" class="ltx_Math" alttext="x_{0}" display="inline"><msub><mi>x</mi><mn>0</mn></msub></math>: a path from <math id="S1.I2.i1.p1.m2" class="ltx_Math" alttext="x_{0}" display="inline"><msub><mi>x</mi><mn>0</mn></msub></math> to <math id="S1.I2.i1.p1.m3" class="ltx_Math" alttext="x_{0}" display="inline"><msub><mi>x</mi><mn>0</mn></msub></math>.</p>
</div>
</li>
<li id="S1.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I2.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I2.i2.p1.m2" class="ltx_Math" alttext="\pi_{1}(X,x_{0})" display="inline"><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow></math> = set of path homotopy classes of loops at <math id="S1.I2.i2.p1.m3" class="ltx_Math" alttext="x_{0}" display="inline"><msub><mi>x</mi><mn>0</mn></msub></math>, with <math id="S1.I2.i2.p1.m4" class="ltx_Math" alttext="*" display="inline"><mo>∗</mo></math>.
By the theorem above it is a <em class="ltx_emph ltx_font_italic">group</em>: unit <math id="S1.I2.i2.p1.m5" class="ltx_Math" alttext="e=[e_{x_{0}}]" display="inline"><mrow><mi>e</mi><mo>=</mo><mrow><mo stretchy="false">[</mo><msub><mi>e</mi><msub><mi>x</mi><mn>0</mn></msub></msub><mo stretchy="false">]</mo></mrow></mrow></math>, inverse <math id="S1.I2.i2.p1.m6" class="ltx_Math" alttext="[f]^{-1}=[\bar{f}]" display="inline"><mrow><msup><mrow><mo stretchy="false">[</mo><mi>f</mi><mo stretchy="false">]</mo></mrow><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>=</mo><mrow><mo stretchy="false">[</mo><mover accent="true"><mi>f</mi><mo>¯</mo></mover><mo stretchy="false">]</mo></mrow></mrow></math>.
The <em class="ltx_emph ltx_font_italic">fundamental group</em> of <math id="S1.I2.i2.p1.m7" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> based at <math id="S1.I2.i2.p1.m8" class="ltx_Math" alttext="x_{0}" display="inline"><msub><mi>x</mi><mn>0</mn></msub></math>.</p>
</div>
</li>
<li id="S1.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I2.i3.p1.m1" class="ltx_Math" alttext="A\subset\mathbb{R}^{n}" display="inline"><mrow><mi>A</mi><mo>⊂</mo><msup><mi>ℝ</mi><mi>n</mi></msup></mrow></math> convex, <math id="S1.I2.i3.p1.m2" class="ltx_Math" alttext="x_{0}\in A" display="inline"><mrow><msub><mi>x</mi><mn>0</mn></msub><mo>∈</mo><mi>A</mi></mrow></math> <math id="S1.I2.i3.p1.m3" class="ltx_Math" alttext="\Rightarrow\pi_{1}(A,x_{0})=\{e\}" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">{</mo><mi>e</mi><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i4.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I2.i4.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <span class="ltx_text ltx_font_bold">(Functoriality.)</span> <math id="S1.I2.i4.p1.m2" class="ltx_Math" alttext="h\colon(X,x_{0})\to(Y,y_{0})" display="inline"><mrow><mi>h</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow><mo stretchy="false">→</mo><mrow><mo stretchy="false">(</mo><mi>Y</mi><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow></mrow></math> a based map. Define</p>
<table id="S1.Ex2" class="ltx_equation ltx_eqn_table">

<tbody><tr class="ltx_equation ltx_eqn_row ltx_align_baseline">
<td class="ltx_eqn_cell ltx_eqn_center_padleft"></td>
<td class="ltx_eqn_cell ltx_align_center"><math id="S1.Ex2.m1" class="ltx_Math" alttext="h_{*}\colon\pi_{1}(X,x_{0})\to\pi_{1}(Y,y_{0}),\qquad h_{*}[f]=[h\circ f]." display="block"><mrow><mrow><msub><mi>h</mi><mo>∗</mo></msub><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">→</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>Y</mi><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow></mrow><mo rspace="2.167em">,</mo><mrow><mrow><msub><mi>h</mi><mo>∗</mo></msub><mo>⁢</mo><mrow><mo stretchy="false">[</mo><mi>f</mi><mo stretchy="false">]</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">[</mo><mrow><mi>h</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>f</mi></mrow><mo stretchy="false">]</mo></mrow></mrow></mrow></mrow><mo lspace="0em">.</mo></mrow></math></td>
<td class="ltx_eqn_cell ltx_eqn_center_padright"></td>
</tr></tbody>
</table>
</div>
</li>
<li id="S1.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i5.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I2.i5.p1.m1" class="ltx_Math" alttext="h_{*}" display="inline"><msub><mi>h</mi><mo>∗</mo></msub></math> is a group homomorphism.</p>
</div>
</li>
<li id="S1.I2.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i6.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I2.i6.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I2.i6.p1.m2" class="ltx_Math" alttext="(k\circ h)_{*}=k_{*}\circ h_{*}" display="inline"><mrow><msub><mrow><mo stretchy="false">(</mo><mrow><mi>k</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>h</mi></mrow><mo stretchy="false">)</mo></mrow><mo>∗</mo></msub><mo>=</mo><mrow><msub><mi>k</mi><mo>∗</mo></msub><mo lspace="0.222em" rspace="0.222em">∘</mo><msub><mi>h</mi><mo>∗</mo></msub></mrow></mrow></math> and <math id="S1.I2.i6.p1.m3" class="ltx_Math" alttext="(\operatorname{id})_{*}=\operatorname{id}" display="inline"><mrow><msub><mrow><mo stretchy="false">(</mo><mi>id</mi><mo stretchy="false">)</mo></mrow><mo>∗</mo></msub><mo>=</mo><mi>id</mi></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i7.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I2.i7.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Cor.</span> <math id="S1.I2.i7.p1.m2" class="ltx_Math" alttext="h" display="inline"><mi>h</mi></math> a homeomorphism <math id="S1.I2.i7.p1.m3" class="ltx_Math" alttext="\Rightarrow h_{*}" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><msub><mi>h</mi><mo>∗</mo></msub></mrow></math> an isomorphism.
So <math id="S1.I2.i7.p1.m4" class="ltx_Math" alttext="\pi_{1}" display="inline"><msub><mi>π</mi><mn>1</mn></msub></math> is a topological invariant of based spaces.</p>
</div>
</li>
<li id="S1.I2.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I2.i8.p1.m1" class="ltx_Math" alttext="\alpha" display="inline"><mi>α</mi></math> a path from <math id="S1.I2.i8.p1.m2" class="ltx_Math" alttext="x_{0}" display="inline"><msub><mi>x</mi><mn>0</mn></msub></math> to <math id="S1.I2.i8.p1.m3" class="ltx_Math" alttext="x_{1}" display="inline"><msub><mi>x</mi><mn>1</mn></msub></math>. Define
<math id="S1.I2.i8.p1.m4" class="ltx_Math" alttext="\hat{\alpha}\colon\pi_{1}(X,x_{0})\to\pi_{1}(X,x_{1}),\qquad\hat{\alpha}[f]=[%
\bar{\alpha}*f*\alpha]." display="inline"><mrow><mrow><mover accent="true"><mi>α</mi><mo>^</mo></mover><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">→</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>1</mn></msub><mo stretchy="false">)</mo></mrow></mrow></mrow><mo rspace="2.167em">,</mo><mrow><mrow><mover accent="true"><mi>α</mi><mo>^</mo></mover><mo>⁢</mo><mrow><mo stretchy="false">[</mo><mi>f</mi><mo stretchy="false">]</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">[</mo><mrow><mover accent="true"><mi>α</mi><mo>¯</mo></mover><mo lspace="0.222em" rspace="0.222em">∗</mo><mi>f</mi><mo lspace="0.222em" rspace="0.222em">∗</mo><mi>α</mi></mrow><mo stretchy="false">]</mo></mrow></mrow></mrow></mrow><mo lspace="0em">.</mo></mrow></math></p>
</div>
</li>
<li id="S1.I2.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i9.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I2.i9.p1.m1" class="ltx_Math" alttext="\hat{\alpha}" display="inline"><mover accent="true"><mi>α</mi><mo>^</mo></mover></math> is an isomorphism; and <math id="S1.I2.i9.p1.m2" class="ltx_Math" alttext="\alpha\simeq_{p}\beta\Rightarrow\hat{\alpha}=\hat{\beta}" display="inline"><mrow><mi>α</mi><msub><mo>≃</mo><mi>p</mi></msub><mi>β</mi><mo stretchy="false">⇒</mo><mover accent="true"><mi>α</mi><mo>^</mo></mover><mo>=</mo><mover accent="true"><mi>β</mi><mo>^</mo></mover></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Cor.</span> <math id="S1.I2.i10.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> path connected <math id="S1.I2.i10.p1.m2" class="ltx_Math" alttext="\Rightarrow\pi_{1}(X,x_{0})\cong\pi_{1}(X,x_{1})" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow><mo>≅</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>1</mn></msub><mo stretchy="false">)</mo></mrow></mrow></mrow></math> for all <math id="S1.I2.i10.p1.m3" class="ltx_Math" alttext="x_{0},x_{1}" display="inline"><mrow><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>x</mi><mn>1</mn></msub></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i11.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> The isomorphism depends on the path: different paths give <em class="ltx_emph ltx_font_italic">conjugate</em>
isomorphisms, which differ when <math id="S1.I2.i11.p1.m1" class="ltx_Math" alttext="\pi_{1}" display="inline"><msub><mi>π</mi><mn>1</mn></msub></math> is non-abelian. So “<math id="S1.I2.i11.p1.m2" class="ltx_Math" alttext="\pi_{1}(X)" display="inline"><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo stretchy="false">)</mo></mrow></mrow></math>” without a base
point is well defined only up to isomorphism.</p>
</div>
</li>
<li id="S1.I2.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i12.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> <math id="S1.I2.i12.p1.m1" class="ltx_Math" alttext="x_{0}\in P\subset X" display="inline"><mrow><msub><mi>x</mi><mn>0</mn></msub><mo>∈</mo><mi>P</mi><mo>⊂</mo><mi>X</mi></mrow></math> with <math id="S1.I2.i12.p1.m2" class="ltx_Math" alttext="P" display="inline"><mi>P</mi></math> the path component <math id="S1.I2.i12.p1.m3" class="ltx_Math" alttext="\Rightarrow\pi_{1}(P,x_{0})\cong\pi_{1}(X,x_{0})" display="inline"><mrow><mi></mi><mo stretchy="false">⇒</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>P</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow><mo>≅</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.
<math id="S1.I2.i12.p1.m4" class="ltx_Math" alttext="\pi_{1}" display="inline"><msub><mi>π</mi><mn>1</mn></msub></math> sees only one path component.</p>
</div>
</li>
<li id="S1.I2.i13" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i13.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I2.i13.p1.m1" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is <em class="ltx_emph ltx_font_italic">simply connected</em> if it is path connected and <math id="S1.I2.i13.p1.m2" class="ltx_Math" alttext="\pi_{1}(X,x_{0})" display="inline"><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow></math> is trivial.
Then any two paths with the same endpoints are path homotopic.</p>
</div>
</li>
<li id="S1.I2.i14" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i14.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i14.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Brouwer.)</span> Every map <math id="S1.I2.i14.p1.m2" class="ltx_Math" alttext="f\colon B^{2}\to B^{2}" display="inline"><mrow><mi>f</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msup><mi>B</mi><mn>2</mn></msup><mo stretchy="false">→</mo><msup><mi>B</mi><mn>2</mn></msup></mrow></mrow></math> has a fixed point. <span class="ltx_text" style="font-size:80%;color:#737373;">[Mk §55]</span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS3" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.3  (§53) Covering spaces</h3>

<div id="S1.SS3.p1" class="ltx_para ltx_noindent">
<ul id="S1.I3" class="ltx_itemize">
<li id="S1.I3.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I3.i1.p1.m2" class="ltx_Math" alttext="p\colon E\to B" display="inline"><mrow><mi>p</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>E</mi><mo stretchy="false">→</mo><mi>B</mi></mrow></mrow></math> a surjective map. An open <math id="S1.I3.i1.p1.m3" class="ltx_Math" alttext="U\subset B" display="inline"><mrow><mi>U</mi><mo>⊂</mo><mi>B</mi></mrow></math> is <em class="ltx_emph ltx_font_italic">evenly covered</em>
if <math id="S1.I3.i1.p1.m4" class="ltx_Math" alttext="p^{-1}(U)=\coprod_{\alpha}V_{\alpha}" display="inline"><mrow><mrow><msup><mi>p</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>U</mi><mo stretchy="false">)</mo></mrow></mrow><mo rspace="0.111em">=</mo><mrow><msub><mo>∐</mo><mi>α</mi></msub><msub><mi>V</mi><mi>α</mi></msub></mrow></mrow></math> with each <math id="S1.I3.i1.p1.m5" class="ltx_Math" alttext="V_{\alpha}\subset E" display="inline"><mrow><msub><mi>V</mi><mi>α</mi></msub><mo>⊂</mo><mi>E</mi></mrow></math> open and each
<math id="S1.I3.i1.p1.m6" class="ltx_Math" alttext="p|V_{\alpha}\colon V_{\alpha}\to U" display="inline"><mrow><mrow><mi>p</mi><mo fence="false">|</mo><msub><mi>V</mi><mi>α</mi></msub></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msub><mi>V</mi><mi>α</mi></msub><mo stretchy="false">→</mo><mi>U</mi></mrow></mrow></math> a homeomorphism. The <math id="S1.I3.i1.p1.m7" class="ltx_Math" alttext="V_{\alpha}" display="inline"><msub><mi>V</mi><mi>α</mi></msub></math> are the <em class="ltx_emph ltx_font_italic">sheets</em>
(slices).</p>
</div>
</li>
<li id="S1.I3.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I3.i2.p1.m2" class="ltx_Math" alttext="p" display="inline"><mi>p</mi></math> is a <em class="ltx_emph ltx_font_italic">covering map</em> (and <math id="S1.I3.i2.p1.m3" class="ltx_Math" alttext="E" display="inline"><mi>E</mi></math> a <em class="ltx_emph ltx_font_italic">covering space</em> of <math id="S1.I3.i2.p1.m4" class="ltx_Math" alttext="B" display="inline"><mi>B</mi></math>) if every
point of <math id="S1.I3.i2.p1.m5" class="ltx_Math" alttext="B" display="inline"><mi>B</mi></math> has an evenly covered neighborhood.</p>
</div>
</li>
<li id="S1.I3.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> Trivial covering: <math id="S1.I3.i3.p1.m1" class="ltx_Math" alttext="F" display="inline"><mi>F</mi></math> discrete, <math id="S1.I3.i3.p1.m2" class="ltx_Math" alttext="p\colon B\times F\to B" display="inline"><mrow><mi>p</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>B</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>F</mi></mrow><mo stretchy="false">→</mo><mi>B</mi></mrow></mrow></math>; sheets <math id="S1.I3.i3.p1.m3" class="ltx_Math" alttext="B\times\{\alpha\}" display="inline"><mrow><mi>B</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mrow><mo stretchy="false">{</mo><mi>α</mi><mo stretchy="false">}</mo></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I3.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Each fibre <math id="S1.I3.i4.p1.m1" class="ltx_Math" alttext="p^{-1}(x)" display="inline"><mrow><msup><mi>p</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow></math> is discrete.</p>
</div>
</li>
<li id="S1.I3.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I3.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> Every covering map is an open surjection, hence a quotient map.</p>
</div>
<div id="S1.I3.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> For <math id="S1.I3.i5.p2.m1" class="ltx_Math" alttext="A\subset E" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">⊂</mo><mi mathcolor="#3D3D3D">E</mi></mrow></math> open and <math id="S1.I3.i5.p2.m2" class="ltx_Math" alttext="x\in p(A)" display="inline"><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">∈</mo><mrow><mi mathcolor="#3D3D3D">p</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>: pick <math id="S1.I3.i5.p2.m3" class="ltx_Math" alttext="y\in A" display="inline"><mrow><mi mathcolor="#3D3D3D">y</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">A</mi></mrow></math> over <math id="S1.I3.i5.p2.m4" class="ltx_Math" alttext="x" display="inline"><mi mathcolor="#3D3D3D">x</mi></math>, let <math id="S1.I3.i5.p2.m5" class="ltx_Math" alttext="V_{\beta}" display="inline"><msub><mi mathcolor="#3D3D3D">V</mi><mi mathcolor="#3D3D3D">β</mi></msub></math> be its sheet;
<math id="S1.I3.i5.p2.m6" class="ltx_Math" alttext="p(A\cap V_{\beta})" display="inline"><mrow><mi mathcolor="#3D3D3D">p</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">∩</mo><msub><mi mathcolor="#3D3D3D">V</mi><mi mathcolor="#3D3D3D">β</mi></msub></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> is open in <math id="S1.I3.i5.p2.m7" class="ltx_Math" alttext="U" display="inline"><mi mathcolor="#3D3D3D">U</mi></math> and contains <math id="S1.I3.i5.p2.m8" class="ltx_Math" alttext="x" display="inline"><mi mathcolor="#3D3D3D">x</mi></math>.</span></span></p>
</div>
</li>
<li id="S1.I3.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i6.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I3.i6.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I3.i6.p1.m2" class="ltx_Math" alttext="p\colon\mathbb{R}\to S^{1}" display="inline"><mrow><mi>p</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>ℝ</mi><mo stretchy="false">→</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></mrow></math>,   <math id="S1.I3.i6.p1.m3" class="ltx_Math" alttext="p(t)=(\cos 2\pi t,\sin 2\pi t)" display="inline"><mrow><mrow><mi>p</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mrow><mn>2</mn><mo>⁢</mo><mi>π</mi><mo>⁢</mo><mi>t</mi></mrow></mrow><mo>,</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mrow><mn>2</mn><mo>⁢</mo><mi>π</mi><mo>⁢</mo><mi>t</mi></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></math>, is a covering map.</p>
</div>
<div id="S1.I3.i6.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> For <math id="S1.I3.i6.p2.m1" class="ltx_Math" alttext="U=\{(x,y)\in S^{1}\mid x&gt;0\}" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">y</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D">∈</mo><msup><mi mathcolor="#3D3D3D">S</mi><mn mathcolor="#3D3D3D">1</mn></msup></mrow><mo fence="true" lspace="0em" mathcolor="#3D3D3D" rspace="0em">∣</mo><mrow><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">&gt;</mo><mn mathcolor="#3D3D3D">0</mn></mrow><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></math>: <math id="S1.I3.i6.p2.m2" class="ltx_Math" alttext="p^{-1}(U)=\coprod_{n\in\mathbb{Z}}(n-\tfrac{1}{4},n+\tfrac{1}{4})" display="inline"><mrow><mrow><msup><mi mathcolor="#3D3D3D">p</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" rspace="0.111em">=</mo><mrow><msub><mo mathcolor="#3D3D3D" rspace="0em">∐</mo><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">∈</mo><mi mathcolor="#3D3D3D">ℤ</mi></mrow></msub><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">−</mo><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mn mathcolor="#3D3D3D">4</mn></mfrac></mrow><mo mathcolor="#3D3D3D">,</mo><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">+</mo><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mn mathcolor="#3D3D3D">4</mn></mfrac></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math>,
with inverse <math id="S1.I3.i6.p2.m3" class="ltx_Math" alttext="(x,y)\mapsto n+\frac{1}{2\pi}\arcsin y" display="inline"><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">x</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">y</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">↦</mo><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">+</mo><mrow><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mrow><mn mathcolor="#3D3D3D">2</mn><mo>⁢</mo><mi mathcolor="#3D3D3D">π</mi></mrow></mfrac><mo lspace="0.167em">⁢</mo><mrow><mi mathcolor="#3D3D3D">arcsin</mi><mo lspace="0.167em">⁡</mo><mi mathcolor="#3D3D3D">y</mi></mrow></mrow></mrow></mrow></math>. Four such <math id="S1.I3.i6.p2.m4" class="ltx_Math" alttext="U" display="inline"><mi mathcolor="#3D3D3D">U</mi></math> cover <math id="S1.I3.i6.p2.m5" class="ltx_Math" alttext="S^{1}" display="inline"><msup><mi mathcolor="#3D3D3D">S</mi><mn mathcolor="#3D3D3D">1</mn></msup></math>.
Each interval <math id="S1.I3.i6.p2.m6" class="ltx_Math" alttext="[n,n+1]" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">,</mo><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">+</mo><mn mathcolor="#3D3D3D">1</mn></mrow><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow></math> wraps once around.</span></span></p>
</div>
</li>
<li id="S1.I3.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i7.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I3.i7.p1.m1" class="ltx_Math" alttext="p" display="inline"><mi>p</mi></math> is a <em class="ltx_emph ltx_font_italic">local homeomorphism</em> if each <math id="S1.I3.i7.p1.m2" class="ltx_Math" alttext="y\in E" display="inline"><mrow><mi>y</mi><mo>∈</mo><mi>E</mi></mrow></math> has a neighborhood <math id="S1.I3.i7.p1.m3" class="ltx_Math" alttext="V" display="inline"><mi>V</mi></math> with
<math id="S1.I3.i7.p1.m4" class="ltx_Math" alttext="p(V)" display="inline"><mrow><mi>p</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>V</mi><mo stretchy="false">)</mo></mrow></mrow></math> open and <math id="S1.I3.i7.p1.m5" class="ltx_Math" alttext="p|V\colon V\to p(V)" display="inline"><mrow><mrow><mi>p</mi><mo fence="false">|</mo><mi>V</mi></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>V</mi><mo stretchy="false">→</mo><mrow><mi>p</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>V</mi><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math> a homeomorphism.</p>
</div>
</li>
<li id="S1.I3.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Covering map <math id="S1.I3.i8.p1.m1" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> local homeomorphism.</p>
</div>
</li>
<li id="S1.I3.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i9.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i9.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Caution.</span> Converse fails: <math id="S1.I3.i9.p1.m2" class="ltx_Math" alttext="q=p|(0,\infty)\colon(0,\infty)\to S^{1}" display="inline"><mrow><mrow><mi>q</mi><mo>=</mo><mrow><mi>p</mi><mo fence="false">|</mo><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mi mathvariant="normal">∞</mi><mo rspace="0.278em" stretchy="false">)</mo></mrow></mrow></mrow><mo rspace="0.278em">:</mo><mrow><mrow><mo stretchy="false">(</mo><mn>0</mn><mo>,</mo><mi mathvariant="normal">∞</mi><mo stretchy="false">)</mo></mrow><mo stretchy="false">→</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></mrow></math> is a local
homeomorphism but not a covering map — no neighborhood of <math id="S1.I3.i9.p1.m3" class="ltx_Math" alttext="(1,0)" display="inline"><mrow><mo stretchy="false">(</mo><mn>1</mn><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></math> is evenly covered.</p>
</div>
</li>
<li id="S1.I3.i10" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i10.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I3.i10.p1.m1" class="ltx_Math" alttext="p_{n}\colon S^{1}\to S^{1}" display="inline"><mrow><msub><mi>p</mi><mi>n</mi></msub><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msup><mi>S</mi><mn>1</mn></msup><mo stretchy="false">→</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></mrow></math>, <math id="S1.I3.i10.p1.m2" class="ltx_Math" alttext="z\mapsto z^{n}" display="inline"><mrow><mi>z</mi><mo stretchy="false">↦</mo><msup><mi>z</mi><mi>n</mi></msup></mrow></math>, i.e. <math id="S1.I3.i10.p1.m3" class="ltx_Math" alttext="(\cos\theta,\sin\theta)\mapsto(\cos n\theta,\sin n\theta)" display="inline"><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mi>θ</mi></mrow><mo>,</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mi>θ</mi></mrow><mo stretchy="false">)</mo></mrow><mo stretchy="false">↦</mo><mrow><mo stretchy="false">(</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mrow><mi>n</mi><mo>⁢</mo><mi>θ</mi></mrow></mrow><mo>,</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mrow><mi>n</mi><mo>⁢</mo><mi>θ</mi></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></math>. A covering map for each <math id="S1.I3.i10.p1.m4" class="ltx_Math" alttext="n" display="inline"><mi>n</mi></math>.
(E.g. <math id="S1.I3.i10.p1.m5" class="ltx_Math" alttext="p_{2}(x,y)=(x^{2}-y^{2},2xy)" display="inline"><mrow><mrow><msub><mi>p</mi><mn>2</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><msup><mi>x</mi><mn>2</mn></msup><mo>−</mo><msup><mi>y</mi><mn>2</mn></msup></mrow><mo>,</mo><mrow><mn>2</mn><mo>⁢</mo><mi>x</mi><mo>⁢</mo><mi>y</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></math>.)</p>
</div>
</li>
<li id="S1.I3.i11" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i11.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Prop.</span> <span class="ltx_text ltx_font_bold">(Restriction.)</span> <math id="S1.I3.i11.p1.m1" class="ltx_Math" alttext="p" display="inline"><mi>p</mi></math> a covering map, <math id="S1.I3.i11.p1.m2" class="ltx_Math" alttext="B_{0}\subset B" display="inline"><mrow><msub><mi>B</mi><mn>0</mn></msub><mo>⊂</mo><mi>B</mi></mrow></math>, <math id="S1.I3.i11.p1.m3" class="ltx_Math" alttext="E_{0}=p^{-1}(B_{0})" display="inline"><mrow><msub><mi>E</mi><mn>0</mn></msub><mo>=</mo><mrow><msup><mi>p</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mi>B</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow></mrow></math>
<math id="S1.I3.i11.p1.m4" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> <math id="S1.I3.i11.p1.m5" class="ltx_Math" alttext="p|E_{0}\colon E_{0}\to B_{0}" display="inline"><mrow><mrow><mi>p</mi><mo fence="false">|</mo><msub><mi>E</mi><mn>0</mn></msub></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msub><mi>E</mi><mn>0</mn></msub><mo stretchy="false">→</mo><msub><mi>B</mi><mn>0</mn></msub></mrow></mrow></math> is a covering map.</p>
</div>
</li>
<li id="S1.I3.i12" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i12.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Prop.</span> <span class="ltx_text ltx_font_bold">(Products.)</span> <math id="S1.I3.i12.p1.m1" class="ltx_Math" alttext="p\times p^{\prime}\colon E\times E^{\prime}\to B\times B^{\prime}" display="inline"><mrow><mrow><mi>p</mi><mo lspace="0.222em" rspace="0.222em">×</mo><msup><mi>p</mi><mo>′</mo></msup></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>E</mi><mo lspace="0.222em" rspace="0.222em">×</mo><msup><mi>E</mi><mo>′</mo></msup></mrow><mo stretchy="false">→</mo><mrow><mi>B</mi><mo lspace="0.222em" rspace="0.222em">×</mo><msup><mi>B</mi><mo>′</mo></msup></mrow></mrow></mrow></math> is a covering map.</p>
</div>
</li>
<li id="S1.I3.i13" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i13.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i13.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I3.i13.p1.m2" class="ltx_Math" alttext="p\times p\colon\mathbb{R}^{2}\to S^{1}\times S^{1}=T^{2}" display="inline"><mrow><mrow><mi>p</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>p</mi></mrow><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><msup><mi>ℝ</mi><mn>2</mn></msup><mo stretchy="false">→</mo><mrow><msup><mi>S</mi><mn>1</mn></msup><mo lspace="0.222em" rspace="0.222em">×</mo><msup><mi>S</mi><mn>1</mn></msup></mrow><mo>=</mo><msup><mi>T</mi><mn>2</mn></msup></mrow></mrow></math> covers the torus;
each unit square <math id="S1.I3.i13.p1.m3" class="ltx_Math" alttext="[n,n+1]\times[m,m+1]" display="inline"><mrow><mrow><mo stretchy="false">[</mo><mi>n</mi><mo>,</mo><mrow><mi>n</mi><mo>+</mo><mn>1</mn></mrow><mo rspace="0.055em" stretchy="false">]</mo></mrow><mo rspace="0.222em">×</mo><mrow><mo stretchy="false">[</mo><mi>m</mi><mo>,</mo><mrow><mi>m</mi><mo>+</mo><mn>1</mn></mrow><mo stretchy="false">]</mo></mrow></mrow></math> wraps once around.</p>
</div>
</li>
<li id="S1.I3.i14" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i14.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I3.i14.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> Figure eight. <math id="S1.I3.i14.p1.m2" class="ltx_Math" alttext="B_{0}=(S^{1}\times\{s_{0}\})\cup(\{s_{0}\}\times S^{1})\subset T^{2}" display="inline"><mrow><msub><mi>B</mi><mn>0</mn></msub><mo>=</mo><mrow><mrow><mo stretchy="false">(</mo><mrow><msup><mi>S</mi><mn>1</mn></msup><mo lspace="0.222em" rspace="0.222em">×</mo><mrow><mo stretchy="false">{</mo><msub><mi>s</mi><mn>0</mn></msub><mo stretchy="false">}</mo></mrow></mrow><mo stretchy="false">)</mo></mrow><mo>∪</mo><mrow><mo stretchy="false">(</mo><mrow><mrow><mo stretchy="false">{</mo><msub><mi>s</mi><mn>0</mn></msub><mo rspace="0.055em" stretchy="false">}</mo></mrow><mo rspace="0.222em">×</mo><msup><mi>S</mi><mn>1</mn></msup></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>⊂</mo><msup><mi>T</mi><mn>2</mn></msup></mrow></math>;
then <math id="S1.I3.i14.p1.m3" class="ltx_Math" alttext="E_{0}=(p\times p)^{-1}(B_{0})=(\mathbb{R}\times\mathbb{Z})\cup(\mathbb{Z}%
\times\mathbb{R})" display="inline"><mrow><msub><mi>E</mi><mn>0</mn></msub><mo>=</mo><mrow><msup><mrow><mo stretchy="false">(</mo><mrow><mi>p</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>p</mi></mrow><mo stretchy="false">)</mo></mrow><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mi>B</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>ℝ</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>ℤ</mi></mrow><mo stretchy="false">)</mo></mrow><mo>∪</mo><mrow><mo stretchy="false">(</mo><mrow><mi>ℤ</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>ℝ</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math>,
the infinite grid, covers <math id="S1.I3.i14.p1.m4" class="ltx_Math" alttext="B_{0}" display="inline"><msub><mi>B</mi><mn>0</mn></msub></math>.</p>
</div>
</li>
<li id="S1.I3.i15" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I3.i15.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I3.i15.p1.m1" class="ltx_Math" alttext="\exp\colon\mathbb{C}\to\mathbb{C}-\{0\}" display="inline"><mrow><mi>exp</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>ℂ</mi><mo stretchy="false">→</mo><mrow><mi>ℂ</mi><mo>−</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></mrow></mrow></math>, in real coordinates
<math id="S1.I3.i15.p1.m2" class="ltx_Math" alttext="p(x,y)=(e^{x}\cos y,e^{x}\sin y)" display="inline"><mrow><mrow><mi>p</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><msup><mi>e</mi><mi>x</mi></msup><mo lspace="0.167em">⁢</mo><mrow><mi>cos</mi><mo lspace="0.167em">⁡</mo><mi>y</mi></mrow></mrow><mo>,</mo><mrow><msup><mi>e</mi><mi>x</mi></msup><mo lspace="0.167em">⁢</mo><mrow><mi>sin</mi><mo lspace="0.167em">⁡</mo><mi>y</mi></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow></math>, is a covering map: it factors through
<math id="S1.I3.i15.p1.m3" class="ltx_Math" alttext="\mathbb{R}\times S^{1}\cong\mathbb{R}^{2}-\{0\}" display="inline"><mrow><mrow><mi>ℝ</mi><mo lspace="0.222em" rspace="0.222em">×</mo><msup><mi>S</mi><mn>1</mn></msup></mrow><mo>≅</mo><mrow><msup><mi>ℝ</mi><mn>2</mn></msup><mo>−</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></mrow></math> as a product of coverings.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS4" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.4  (§54–§55) The fundamental group of the circle <span class="ltx_text" style="font-size:67%;color:#737373;">[Mk §54–55]</span>
</h3>

<div id="S1.SS4.p1" class="ltx_para ltx_noindent">
<ul id="S1.I4" class="ltx_itemize">
<li id="S1.I4.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I4.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I4.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I4.i1.p1.m2" class="ltx_Math" alttext="\pi_{1}(S^{1},s_{0})\cong\mathbb{Z}" display="inline"><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msup><mi>S</mi><mn>1</mn></msup><mo>,</mo><msub><mi>s</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow><mo>≅</mo><mi>ℤ</mi></mrow></math>, generated by the loop that goes once around;
the isomorphism sends a loop to its <em class="ltx_emph ltx_font_italic">winding number</em>, i.e. the endpoint of its lift
along <math id="S1.I4.i1.p1.m3" class="ltx_Math" alttext="p\colon\mathbb{R}\to S^{1}" display="inline"><mrow><mi>p</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>ℝ</mi><mo stretchy="false">→</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I4.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I4.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Machinery needed: path lifting, homotopy lifting, the lifting correspondence.
Work these through from Munkres §54; then §55 gives no-retraction of <math id="S1.I4.i2.p1.m1" class="ltx_Math" alttext="B^{2}" display="inline"><msup><mi>B</mi><mn>2</mn></msup></math> onto <math id="S1.I4.i2.p1.m2" class="ltx_Math" alttext="S^{1}" display="inline"><msup><mi>S</mi><mn>1</mn></msup></math>,
and Brouwer’s theorem.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS5" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.5  (§58) Deformation retracts and homotopy type</h3>

<div id="S1.SS5.p1" class="ltx_para ltx_noindent">
<ul id="S1.I5" class="ltx_itemize">
<li id="S1.I5.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I5.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I5.i1.p1.m1" class="ltx_Math" alttext="j\colon A\to X" display="inline"><mrow><mi>j</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>A</mi><mo stretchy="false">→</mo><mi>X</mi></mrow></mrow></math> an inclusion. A <em class="ltx_emph ltx_font_italic">retraction</em> is a map <math id="S1.I5.i1.p1.m2" class="ltx_Math" alttext="r\colon X\to A" display="inline"><mrow><mi>r</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>X</mi><mo stretchy="false">→</mo><mi>A</mi></mrow></mrow></math> with
<math id="S1.I5.i1.p1.m3" class="ltx_Math" alttext="r\circ j=\operatorname{id}_{A}" display="inline"><mrow><mrow><mi>r</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>j</mi></mrow><mo>=</mo><msub><mi>id</mi><mi>A</mi></msub></mrow></math>.</p>
</div>
</li>
<li id="S1.I5.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I5.i2.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I5.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> A <em class="ltx_emph ltx_font_italic">deformation retraction</em> of <math id="S1.I5.i2.p1.m2" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> onto <math id="S1.I5.i2.p1.m3" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math>: a homotopy
<math id="S1.I5.i2.p1.m4" class="ltx_Math" alttext="H\colon X\times I\to X" display="inline"><mrow><mi>H</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>I</mi></mrow><mo stretchy="false">→</mo><mi>X</mi></mrow></mrow></math> from <math id="S1.I5.i2.p1.m5" class="ltx_Math" alttext="\operatorname{id}_{X}" display="inline"><msub><mi>id</mi><mi>X</mi></msub></math> to <math id="S1.I5.i2.p1.m6" class="ltx_Math" alttext="j\circ r" display="inline"><mrow><mi>j</mi><mo lspace="0.222em" rspace="0.222em">∘</mo><mi>r</mi></mrow></math>, with <math id="S1.I5.i2.p1.m7" class="ltx_Math" alttext="H(a,t)=a" display="inline"><mrow><mrow><mi>H</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>a</mi><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mi>a</mi></mrow></math> for all
<math id="S1.I5.i2.p1.m8" class="ltx_Math" alttext="a\in A" display="inline"><mrow><mi>a</mi><mo>∈</mo><mi>A</mi></mrow></math>, <math id="S1.I5.i2.p1.m9" class="ltx_Math" alttext="t\in I" display="inline"><mrow><mi>t</mi><mo>∈</mo><mi>I</mi></mrow></math>.</p>
</div>
</li>
<li id="S1.I5.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I5.i3.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I5.i3.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I5.i3.p1.m2" class="ltx_Math" alttext="A=S^{n}\subset X=\mathbb{R}^{n+1}-\{0\}" display="inline"><mrow><mi>A</mi><mo>=</mo><msup><mi>S</mi><mi>n</mi></msup><mo>⊂</mo><mi>X</mi><mo>=</mo><mrow><msup><mi>ℝ</mi><mrow><mi>n</mi><mo>+</mo><mn>1</mn></mrow></msup><mo>−</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow></mrow></math>, <math id="S1.I5.i3.p1.m3" class="ltx_Math" alttext="r(x)=x/\|x\|" display="inline"><mrow><mrow><mi>r</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mi>x</mi><mo>/</mo><mrow><mo stretchy="false">‖</mo><mi>x</mi><mo stretchy="false">‖</mo></mrow></mrow></mrow></math>, and
<math id="S1.I5.i3.p1.m4" class="ltx_Math" alttext="H(x,t)=(1-t)x+t\,x/\|x\|." display="inline"><mrow><mrow><mrow><mi>H</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>x</mi><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><mrow><mo stretchy="false">(</mo><mrow><mn>1</mn><mo>−</mo><mi>t</mi></mrow><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mi>x</mi></mrow><mo>+</mo><mrow><mrow><mi>t</mi><mo lspace="0.170em">⁢</mo><mi>x</mi></mrow><mo>/</mo><mrow><mo stretchy="false">‖</mo><mi>x</mi><mo stretchy="false">‖</mo></mrow></mrow></mrow></mrow><mo lspace="0em">.</mo></mrow></math></p>
</div>
</li>
<li id="S1.I5.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I5.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I5.i4.p1.m1" class="ltx_Math" alttext="H" display="inline"><mi>H</mi></math> a homotopy from <math id="S1.I5.i4.p1.m2" class="ltx_Math" alttext="h" display="inline"><mi>h</mi></math> to <math id="S1.I5.i4.p1.m3" class="ltx_Math" alttext="k" display="inline"><mi>k</mi></math> with <math id="S1.I5.i4.p1.m4" class="ltx_Math" alttext="H(x_{0},t)=y_{0}" display="inline"><mrow><mrow><mi>H</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><mi>t</mi><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><msub><mi>y</mi><mn>0</mn></msub></mrow></math> for all <math id="S1.I5.i4.p1.m5" class="ltx_Math" alttext="t" display="inline"><mi>t</mi></math> (a homotopy
<em class="ltx_emph ltx_font_italic">relative to</em> <math id="S1.I5.i4.p1.m6" class="ltx_Math" alttext="x_{0}" display="inline"><msub><mi>x</mi><mn>0</mn></msub></math>) <math id="S1.I5.i4.p1.m7" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> <math id="S1.I5.i4.p1.m8" class="ltx_Math" alttext="h_{*}=k_{*}" display="inline"><mrow><msub><mi>h</mi><mo>∗</mo></msub><mo>=</mo><msub><mi>k</mi><mo>∗</mo></msub></mrow></math> on <math id="S1.I5.i4.p1.m9" class="ltx_Math" alttext="\pi_{1}" display="inline"><msub><mi>π</mi><mn>1</mn></msub></math>.</p>
</div>
<div id="S1.I5.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> For a loop <math id="S1.I5.i4.p2.m1" class="ltx_Math" alttext="f" display="inline"><mi mathcolor="#3D3D3D">f</mi></math> at <math id="S1.I5.i4.p2.m2" class="ltx_Math" alttext="x_{0}" display="inline"><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">0</mn></msub></math>, the composite <math id="S1.I5.i4.p2.m3" class="ltx_Math" alttext="H\circ(f\times\operatorname{id})\colon I\times I\to Y" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">H</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">∘</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">id</mi></mrow><mo mathcolor="#3D3D3D" rspace="0.278em" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" rspace="0.278em">:</mo><mrow><mrow><mi mathcolor="#3D3D3D">I</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">×</mo><mi mathcolor="#3D3D3D">I</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">→</mo><mi mathcolor="#3D3D3D">Y</mi></mrow></mrow></math> is a
path homotopy from <math id="S1.I5.i4.p2.m4" class="ltx_Math" alttext="hf" display="inline"><mrow><mi mathcolor="#3D3D3D">h</mi><mo>⁢</mo><mi mathcolor="#3D3D3D">f</mi></mrow></math> to <math id="S1.I5.i4.p2.m5" class="ltx_Math" alttext="kf" display="inline"><mrow><mi mathcolor="#3D3D3D">k</mi><mo>⁢</mo><mi mathcolor="#3D3D3D">f</mi></mrow></math>.</span></span></p>
</div>
</li>
<li id="S1.I5.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I5.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I5.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I5.i5.p1.m2" class="ltx_Math" alttext="A" display="inline"><mi>A</mi></math> a deformation retract of <math id="S1.I5.i5.p1.m3" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> <math id="S1.I5.i5.p1.m4" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math>
<math id="S1.I5.i5.p1.m5" class="ltx_Math" alttext="j_{*}\colon\pi_{1}(A,a_{0})\xrightarrow{\ \cong\ }\pi_{1}(X,a_{0})." display="inline"><mrow><mrow><msub><mi>j</mi><mo>∗</mo></msub><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>A</mi><mo>,</mo><msub><mi>a</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow><mover accent="true"><mo stretchy="false">→</mo><mo>≅</mo></mover><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>a</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow><mo lspace="0em">.</mo></mrow></math></p>
</div>
<div id="S1.I5.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I5.i5.p2.m1" class="ltx_Math" alttext="rj=\operatorname{id}_{A}" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">r</mi><mo>⁢</mo><mi mathcolor="#3D3D3D">j</mi></mrow><mo mathcolor="#3D3D3D">=</mo><msub><mi mathcolor="#3D3D3D">id</mi><mi mathcolor="#3D3D3D">A</mi></msub></mrow></math> gives <math id="S1.I5.i5.p2.m2" class="ltx_Math" alttext="r_{*}j_{*}=\operatorname{id}" display="inline"><mrow><mrow><msub><mi mathcolor="#3D3D3D">r</mi><mo mathcolor="#3D3D3D">∗</mo></msub><mo>⁢</mo><msub><mi mathcolor="#3D3D3D">j</mi><mo mathcolor="#3D3D3D">∗</mo></msub></mrow><mo mathcolor="#3D3D3D">=</mo><mi mathcolor="#3D3D3D">id</mi></mrow></math>. And <math id="S1.I5.i5.p2.m3" class="ltx_Math" alttext="H" display="inline"><mi mathcolor="#3D3D3D">H</mi></math> is a homotopy rel <math id="S1.I5.i5.p2.m4" class="ltx_Math" alttext="a_{0}" display="inline"><msub><mi mathcolor="#3D3D3D">a</mi><mn mathcolor="#3D3D3D">0</mn></msub></math> from <math id="S1.I5.i5.p2.m5" class="ltx_Math" alttext="\operatorname{id}_{X}" display="inline"><msub><mi mathcolor="#3D3D3D">id</mi><mi mathcolor="#3D3D3D">X</mi></msub></math> to <math id="S1.I5.i5.p2.m6" class="ltx_Math" alttext="jr" display="inline"><mrow><mi mathcolor="#3D3D3D">j</mi><mo>⁢</mo><mi mathcolor="#3D3D3D">r</mi></mrow></math>,
so <math id="S1.I5.i5.p2.m7" class="ltx_Math" alttext="j_{*}r_{*}=\operatorname{id}" display="inline"><mrow><mrow><msub><mi mathcolor="#3D3D3D">j</mi><mo mathcolor="#3D3D3D">∗</mo></msub><mo>⁢</mo><msub><mi mathcolor="#3D3D3D">r</mi><mo mathcolor="#3D3D3D">∗</mo></msub></mrow><mo mathcolor="#3D3D3D">=</mo><mi mathcolor="#3D3D3D">id</mi></mrow></math> by the lemma.</span></span></p>
</div>
</li>
<li id="S1.I5.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I5.i6.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I5.i6.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I5.i6.p1.m2" class="ltx_Math" alttext="\pi_{1}(\mathbb{C}-\{0\})\cong\pi_{1}(S^{1})\cong\mathbb{Z}" display="inline"><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>ℂ</mi><mo>−</mo><mrow><mo stretchy="false">{</mo><mn>0</mn><mo stretchy="false">}</mo></mrow></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>≅</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msup><mi>S</mi><mn>1</mn></msup><mo stretchy="false">)</mo></mrow></mrow><mo>≅</mo><mi>ℤ</mi></mrow></math>, infinite cyclic.</p>
</div>
</li>
<li id="S1.I5.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I5.i7.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I5.i7.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> Doubly punctured plane <math id="S1.I5.i7.p1.m2" class="ltx_Math" alttext="X=\mathbb{C}-\{+i,-i\}" display="inline"><mrow><mi>X</mi><mo>=</mo><mrow><mi>ℂ</mi><mo>−</mo><mrow><mo stretchy="false">{</mo><mrow><mo>+</mo><mi>i</mi></mrow><mo>,</mo><mrow><mo>−</mo><mi>i</mi></mrow><mo stretchy="false">}</mo></mrow></mrow></mrow></math> deformation retracts onto the
<em class="ltx_emph ltx_font_italic">figure eight</em> <math id="S1.I5.i7.p1.m3" class="ltx_Math" alttext="8=(i+S^{1})\cup(-i+S^{1})=S^{1}\vee S^{1}" display="inline"><mrow><mn>8</mn><mo>=</mo><mrow><mrow><mo stretchy="false">(</mo><mrow><mi>i</mi><mo>+</mo><msup><mi>S</mi><mn>1</mn></msup></mrow><mo stretchy="false">)</mo></mrow><mo>∪</mo><mrow><mo stretchy="false">(</mo><mrow><mrow><mo>−</mo><mi>i</mi></mrow><mo>+</mo><msup><mi>S</mi><mn>1</mn></msup></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><msup><mi>S</mi><mn>1</mn></msup><mo>∨</mo><msup><mi>S</mi><mn>1</mn></msup></mrow></mrow></math>, meeting at <math id="S1.I5.i7.p1.m4" class="ltx_Math" alttext="0" display="inline"><mn>0</mn></math>.
So <math id="S1.I5.i7.p1.m5" class="ltx_Math" alttext="\pi_{1}(8,0)\cong\pi_{1}(X,0)" display="inline"><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>8</mn><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></mrow><mo>≅</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I5.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I5.i8.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> With <math id="S1.I5.i8.p1.m1" class="ltx_Math" alttext="x=[f]" display="inline"><mrow><mi>x</mi><mo>=</mo><mrow><mo stretchy="false">[</mo><mi>f</mi><mo stretchy="false">]</mo></mrow></mrow></math>, <math id="S1.I5.i8.p1.m2" class="ltx_Math" alttext="y=[g]" display="inline"><mrow><mi>y</mi><mo>=</mo><mrow><mo stretchy="false">[</mo><mi>g</mi><mo stretchy="false">]</mo></mrow></mrow></math> the classes of the two circle loops:
<math id="S1.I5.i8.p1.m3" class="ltx_Math" alttext="\pi_{1}(8,0)=F_{2}=\langle x,y\rangle" display="inline"><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>8</mn><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><msub><mi>F</mi><mn>2</mn></msub><mo>=</mo><mrow><mo stretchy="false">⟨</mo><mi>x</mi><mo>,</mo><mi>y</mi><mo stretchy="false">⟩</mo></mrow></mrow></math>, the free group on two generators —
every element a word in <math id="S1.I5.i8.p1.m4" class="ltx_Math" alttext="x^{\pm 1},y^{\pm 1}" display="inline"><mrow><msup><mi>x</mi><mrow><mo>±</mo><mn>1</mn></mrow></msup><mo>,</mo><msup><mi>y</mi><mrow><mo>±</mo><mn>1</mn></mrow></msup></mrow></math>, with no relations beyond the group axioms.
We prove less:</p>
</div>
</li>
<li id="S1.I5.i9" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I5.i9.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I5.i9.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Prop.</span> <math id="S1.I5.i9.p1.m2" class="ltx_Math" alttext="\pi_{1}(8,0)" display="inline"><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mn>8</mn><mo>,</mo><mn>0</mn><mo stretchy="false">)</mo></mrow></mrow></math> is <em class="ltx_emph ltx_font_italic">not abelian</em>.</p>
</div>
<div id="S1.I5.i9.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Use the path-connected threefold cover of <math id="S1.I5.i9.p2.m1" class="ltx_Math" alttext="8" display="inline"><mn mathcolor="#3D3D3D">8</mn></math> which is onefold over one circle and
twofold over the other. Starting at the right vertex, the lifts of <math id="S1.I5.i9.p2.m2" class="ltx_Math" alttext="f*g" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">∗</mo><mi mathcolor="#3D3D3D">g</mi></mrow></math> and <math id="S1.I5.i9.p2.m3" class="ltx_Math" alttext="g*f" display="inline"><mrow><mi mathcolor="#3D3D3D">g</mi><mo lspace="0.222em" mathcolor="#3D3D3D" rspace="0.222em">∗</mo><mi mathcolor="#3D3D3D">f</mi></mrow></math> end at
different points, so <math id="S1.I5.i9.p2.m4" class="ltx_Math" alttext="[f]*[g]\neq[g]*[f]" display="inline"><mrow><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D" rspace="0.055em" stretchy="false">]</mo></mrow><mo mathcolor="#3D3D3D" rspace="0.222em">∗</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">g</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow></mrow><mo mathcolor="#3D3D3D">≠</mo><mrow><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">g</mi><mo mathcolor="#3D3D3D" rspace="0.055em" stretchy="false">]</mo></mrow><mo mathcolor="#3D3D3D" rspace="0.222em">∗</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow></mrow></mrow></math>. Draw the covering graph.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS6" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.6  (§59) The fundamental group of <math id="S1.SS6.m1" class="ltx_Math" alttext="S^{n}" display="inline"><msup><mi mathcolor="#1A3873">S</mi><mi mathcolor="#1A3873">n</mi></msup></math>
</h3>

<div id="S1.SS6.p1" class="ltx_para ltx_noindent">
<ul id="S1.I6" class="ltx_itemize">
<li id="S1.I6.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I6.i1.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I6.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I6.i1.p1.m2" class="ltx_Math" alttext="X=U\cup V" display="inline"><mrow><mi>X</mi><mo>=</mo><mrow><mi>U</mi><mo>∪</mo><mi>V</mi></mrow></mrow></math> with <math id="S1.I6.i1.p1.m3" class="ltx_Math" alttext="U,V" display="inline"><mrow><mi>U</mi><mo>,</mo><mi>V</mi></mrow></math> open and simply connected and <math id="S1.I6.i1.p1.m4" class="ltx_Math" alttext="U\cap V" display="inline"><mrow><mi>U</mi><mo>∩</mo><mi>V</mi></mrow></math> path connected
<math id="S1.I6.i1.p1.m5" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> <math id="S1.I6.i1.p1.m6" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math> is simply connected.</p>
</div>
<div id="S1.I6.i1.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Base point <math id="S1.I6.i1.p2.m1" class="ltx_Math" alttext="x_{0}\in U\cap V" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">0</mn></msub><mo mathcolor="#3D3D3D">∈</mo><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">∩</mo><mi mathcolor="#3D3D3D">V</mi></mrow></mrow></math>; loop <math id="S1.I6.i1.p2.m2" class="ltx_Math" alttext="f" display="inline"><mi mathcolor="#3D3D3D">f</mi></math>. The cover <math id="S1.I6.i1.p2.m3" class="ltx_Math" alttext="\{f^{-1}(U),f^{-1}(V)\}" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">,</mo><mrow><msup><mi mathcolor="#3D3D3D">f</mi><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></math> of the compact
metric space <math id="S1.I6.i1.p2.m4" class="ltx_Math" alttext="I" display="inline"><mi mathcolor="#3D3D3D">I</mi></math> has a Lebesgue number, giving <math id="S1.I6.i1.p2.m5" class="ltx_Math" alttext="0=s_{0}&lt;\cdots&lt;s_{n}=1" display="inline"><mrow><mn mathcolor="#3D3D3D">0</mn><mo mathcolor="#3D3D3D">=</mo><msub><mi mathcolor="#3D3D3D">s</mi><mn mathcolor="#3D3D3D">0</mn></msub><mo mathcolor="#3D3D3D">&lt;</mo><mi mathcolor="#3D3D3D" mathvariant="normal">⋯</mi><mo mathcolor="#3D3D3D">&lt;</mo><msub><mi mathcolor="#3D3D3D">s</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D">=</mo><mn mathcolor="#3D3D3D">1</mn></mrow></math> with each
<math id="S1.I6.i1.p2.m6" class="ltx_Math" alttext="f([s_{i-1},s_{i}])" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><msub><mi mathcolor="#3D3D3D">s</mi><mrow><mi mathcolor="#3D3D3D">i</mi><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msub><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">s</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> inside <math id="S1.I6.i1.p2.m7" class="ltx_Math" alttext="U" display="inline"><mi mathcolor="#3D3D3D">U</mi></math> or <math id="S1.I6.i1.p2.m8" class="ltx_Math" alttext="V" display="inline"><mi mathcolor="#3D3D3D">V</mi></math>. Delete any <math id="S1.I6.i1.p2.m9" class="ltx_Math" alttext="s_{i}" display="inline"><msub><mi mathcolor="#3D3D3D">s</mi><mi mathcolor="#3D3D3D">i</mi></msub></math> with <math id="S1.I6.i1.p2.m10" class="ltx_Math" alttext="f(s_{i})\notin U\cap V" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">s</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">∉</mo><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">∩</mo><mi mathcolor="#3D3D3D">V</mi></mrow></mrow></math>;
then all <math id="S1.I6.i1.p2.m11" class="ltx_Math" alttext="f(s_{i})\in U\cap V" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">s</mi><mi mathcolor="#3D3D3D">i</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">∈</mo><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">∩</mo><mi mathcolor="#3D3D3D">V</mi></mrow></mrow></math>. Pick a loop <math id="S1.I6.i1.p2.m12" class="ltx_Math" alttext="g" display="inline"><mi mathcolor="#3D3D3D">g</mi></math> in <math id="S1.I6.i1.p2.m13" class="ltx_Math" alttext="U\cap V" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">∩</mo><mi mathcolor="#3D3D3D">V</mi></mrow></math> agreeing with <math id="S1.I6.i1.p2.m14" class="ltx_Math" alttext="f" display="inline"><mi mathcolor="#3D3D3D">f</mi></math> at each <math id="S1.I6.i1.p2.m15" class="ltx_Math" alttext="s_{i}" display="inline"><msub><mi mathcolor="#3D3D3D">s</mi><mi mathcolor="#3D3D3D">i</mi></msub></math>;
patch the piecewise path homotopies. Finally <math id="S1.I6.i1.p2.m16" class="ltx_Math" alttext="[g]" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">g</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow></math> dies already in <math id="S1.I6.i1.p2.m17" class="ltx_Math" alttext="\pi_{1}(U,x_{0})" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">π</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">0</mn></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S1.I6.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I6.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I6.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I6.i2.p1.m2" class="ltx_Math" alttext="S^{2}" display="inline"><msup><mi>S</mi><mn>2</mn></msup></math> is simply connected.</p>
</div>
<div id="S1.I6.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I6.i2.p2.m1" class="ltx_Math" alttext="U=S^{2}-\{S\}" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mi mathcolor="#3D3D3D">S</mi><mn mathcolor="#3D3D3D">2</mn></msup><mo mathcolor="#3D3D3D">−</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">S</mi><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></mrow></math>, <math id="S1.I6.i2.p2.m2" class="ltx_Math" alttext="V=S^{2}-\{N\}" display="inline"><mrow><mi mathcolor="#3D3D3D">V</mi><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mi mathcolor="#3D3D3D">S</mi><mn mathcolor="#3D3D3D">2</mn></msup><mo mathcolor="#3D3D3D">−</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mi mathcolor="#3D3D3D">N</mi><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></mrow></math>; stereographic projection
<math id="S1.I6.i2.p2.m3" class="ltx_Math" alttext="h(x_{1},x_{2},x_{3})=\frac{1}{1+x_{3}}(x_{1},x_{2})" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">h</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">2</mn></msub><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">3</mn></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mfrac mathcolor="#3D3D3D"><mn mathcolor="#3D3D3D">1</mn><mrow><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">+</mo><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">3</mn></msub></mrow></mfrac><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">x</mi><mn mathcolor="#3D3D3D">2</mn></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></math> gives <math id="S1.I6.i2.p2.m4" class="ltx_Math" alttext="U\cong\mathbb{R}^{2}" display="inline"><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">≅</mo><msup><mi mathcolor="#3D3D3D">ℝ</mi><mn mathcolor="#3D3D3D">2</mn></msup></mrow></math>, likewise <math id="S1.I6.i2.p2.m5" class="ltx_Math" alttext="V" display="inline"><mi mathcolor="#3D3D3D">V</mi></math>;
and <math id="S1.I6.i2.p2.m6" class="ltx_Math" alttext="U\cap V\cong\mathbb{R}^{2}-\{0\}" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">U</mi><mo mathcolor="#3D3D3D">∩</mo><mi mathcolor="#3D3D3D">V</mi></mrow><mo mathcolor="#3D3D3D">≅</mo><mrow><msup><mi mathcolor="#3D3D3D">ℝ</mi><mn mathcolor="#3D3D3D">2</mn></msup><mo mathcolor="#3D3D3D">−</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mn mathcolor="#3D3D3D">0</mn><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></mrow></mrow></math> is path connected.</span></span></p>
</div>
</li>
<li id="S1.I6.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I6.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Same argument: <math id="S1.I6.i3.p1.m1" class="ltx_Math" alttext="S^{n}" display="inline"><msup><mi>S</mi><mi>n</mi></msup></math> is simply connected for all <math id="S1.I6.i3.p1.m2" class="ltx_Math" alttext="n\geq 2" display="inline"><mrow><mi>n</mi><mo>≥</mo><mn>2</mn></mrow></math>.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS7" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.7  (§60) Fundamental groups of some surfaces</h3>

<div id="S1.SS7.p1" class="ltx_para ltx_noindent">
<ul id="S1.I7" class="ltx_itemize">
<li id="S1.I7.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I7.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> Product group <math id="S1.I7.i1.p1.m1" class="ltx_Math" alttext="G\times H" display="inline"><mrow><mi>G</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>H</mi></mrow></math>: <math id="S1.I7.i1.p1.m2" class="ltx_Math" alttext="(g,h)(g^{\prime},h^{\prime})=(gg^{\prime},hh^{\prime})" display="inline"><mrow><mrow><mrow><mo stretchy="false">(</mo><mi>g</mi><mo>,</mo><mi>h</mi><mo stretchy="false">)</mo></mrow><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msup><mi>g</mi><mo>′</mo></msup><mo>,</mo><msup><mi>h</mi><mo>′</mo></msup><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mo stretchy="false">(</mo><mrow><mi>g</mi><mo>⁢</mo><msup><mi>g</mi><mo>′</mo></msup></mrow><mo>,</mo><mrow><mi>h</mi><mo>⁢</mo><msup><mi>h</mi><mo>′</mo></msup></mrow><mo stretchy="false">)</mo></mrow></mrow></math>, unit <math id="S1.I7.i1.p1.m3" class="ltx_Math" alttext="(e,e)" display="inline"><mrow><mo stretchy="false">(</mo><mi>e</mi><mo>,</mo><mi>e</mi><mo stretchy="false">)</mo></mrow></math>,
inverse <math id="S1.I7.i1.p1.m4" class="ltx_Math" alttext="(g^{-1},h^{-1})" display="inline"><mrow><mo stretchy="false">(</mo><msup><mi>g</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>,</mo><msup><mi>h</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo stretchy="false">)</mo></mrow></math>.</p>
</div>
</li>
<li id="S1.I7.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I7.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I7.i2.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> With <math id="S1.I7.i2.p1.m2" class="ltx_Math" alttext="p=\mathrm{pr}_{X}" display="inline"><mrow><mi>p</mi><mo>=</mo><msub><mi>pr</mi><mi>X</mi></msub></mrow></math>, <math id="S1.I7.i2.p1.m3" class="ltx_Math" alttext="q=\mathrm{pr}_{Y}" display="inline"><mrow><mi>q</mi><mo>=</mo><msub><mi>pr</mi><mi>Y</mi></msub></mrow></math>, the map
<math id="S1.I7.i2.p1.m4" class="ltx_Math" alttext="\Phi=(p_{*},q_{*})\colon\pi_{1}(X\times Y,(x_{0},y_{0}))\longrightarrow\pi_{1}%
(X,x_{0})\times\pi_{1}(Y,y_{0})" display="inline"><mrow><mrow><mi mathvariant="normal">Φ</mi><mo>=</mo><mrow><mo stretchy="false">(</mo><msub><mi>p</mi><mo>∗</mo></msub><mo>,</mo><msub><mi>q</mi><mo>∗</mo></msub><mo rspace="0.278em" stretchy="false">)</mo></mrow></mrow><mo rspace="0.278em">:</mo><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>X</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>Y</mi></mrow><mo>,</mo><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mn>0</mn></msub><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow><mo stretchy="false">)</mo></mrow></mrow><mo stretchy="false">⟶</mo><mrow><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><msub><mi>x</mi><mn>0</mn></msub><mo rspace="0.055em" stretchy="false">)</mo></mrow></mrow><mo rspace="0.222em">×</mo><msub><mi>π</mi><mn>1</mn></msub></mrow><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mi>Y</mi><mo>,</mo><msub><mi>y</mi><mn>0</mn></msub><mo stretchy="false">)</mo></mrow></mrow></mrow></mrow></math>
is a group isomorphism.</p>
</div>
<div id="S1.I7.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Surjective: given loops <math id="S1.I7.i2.p2.m1" class="ltx_Math" alttext="f,g" display="inline"><mrow><mi mathcolor="#3D3D3D">f</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">g</mi></mrow></math> set <math id="S1.I7.i2.p2.m2" class="ltx_Math" alttext="h(s)=(f(s),g(s))" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">h</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">s</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">f</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">s</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">,</mo><mrow><mi mathcolor="#3D3D3D">g</mi><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">s</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math>.
Injective: path homotopies <math id="S1.I7.i2.p2.m3" class="ltx_Math" alttext="F,G" display="inline"><mrow><mi mathcolor="#3D3D3D">F</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">G</mi></mrow></math> assemble to <math id="S1.I7.i2.p2.m4" class="ltx_Math" alttext="H=(F,G)" display="inline"><mrow><mi mathcolor="#3D3D3D">H</mi><mo mathcolor="#3D3D3D">=</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">F</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">G</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S1.I7.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I7.i3.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I7.i3.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Ex.</span> <math id="S1.I7.i3.p1.m2" class="ltx_Math" alttext="\pi_{1}(T^{2})=\pi_{1}(S^{1}\times S^{1})\cong\mathbb{Z}\times\mathbb{Z}=%
\mathbb{Z}^{2}," display="inline"><mrow><mrow><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msup><mi>T</mi><mn>2</mn></msup><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><msup><mi>S</mi><mn>1</mn></msup><mo lspace="0.222em" rspace="0.222em">×</mo><msup><mi>S</mi><mn>1</mn></msup></mrow><mo stretchy="false">)</mo></mrow></mrow><mo>≅</mo><mrow><mi>ℤ</mi><mo lspace="0.222em" rspace="0.222em">×</mo><mi>ℤ</mi></mrow><mo>=</mo><msup><mi>ℤ</mi><mn>2</mn></msup></mrow><mo>,</mo></mrow></math>
free abelian on two generators.</p>
</div>
</li>
<li id="S1.I7.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I7.i4.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> The inclusion <math id="S1.I7.i4.p1.m1" class="ltx_Math" alttext="8=S^{1}\vee S^{1}\subset S^{1}\times S^{1}=T^{2}" display="inline"><mrow><mn>8</mn><mo>=</mo><mrow><msup><mi>S</mi><mn>1</mn></msup><mo>∨</mo><msup><mi>S</mi><mn>1</mn></msup></mrow><mo>⊂</mo><mrow><msup><mi>S</mi><mn>1</mn></msup><mo lspace="0.222em" rspace="0.222em">×</mo><msup><mi>S</mi><mn>1</mn></msup></mrow><mo>=</mo><msup><mi>T</mi><mn>2</mn></msup></mrow></math> induces the canonical
surjection <math id="S1.I7.i4.p1.m2" class="ltx_Math" alttext="F_{2}\to\mathbb{Z}^{2}" display="inline"><mrow><msub><mi>F</mi><mn>2</mn></msub><mo stretchy="false">→</mo><msup><mi>ℤ</mi><mn>2</mn></msup></mrow></math> (abelianisation).
The commutator <math id="S1.I7.i4.p1.m3" class="ltx_Math" alttext="xyx^{-1}y^{-1}" display="inline"><mrow><mi>x</mi><mo>⁢</mo><mi>y</mi><mo>⁢</mo><msup><mi>x</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><msup><mi>y</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup></mrow></math> maps to <math id="S1.I7.i4.p1.m4" class="ltx_Math" alttext="0" display="inline"><mn>0</mn></math>: in the square model of <math id="S1.I7.i4.p1.m5" class="ltx_Math" alttext="T^{2}" display="inline"><msup><mi>T</mi><mn>2</mn></msup></math>, the loop
<math id="S1.I7.i4.p1.m6" class="ltx_Math" alttext="f*g*\bar{f}*\bar{g}" display="inline"><mrow><mi>f</mi><mo lspace="0.222em" rspace="0.222em">∗</mo><mi>g</mi><mo lspace="0.222em" rspace="0.222em">∗</mo><mover accent="true"><mi>f</mi><mo>¯</mo></mover><mo lspace="0.222em" rspace="0.222em">∗</mo><mover accent="true"><mi>g</mi><mo>¯</mo></mover></mrow></math> is the boundary of <math id="S1.I7.i4.p1.m7" class="ltx_Math" alttext="I^{2}" display="inline"><msup><mi>I</mi><mn>2</mn></msup></math>, which is nullhomotopic in <math id="S1.I7.i4.p1.m8" class="ltx_Math" alttext="I^{2}" display="inline"><msup><mi>I</mi><mn>2</mn></msup></math>.</p>
</div>
</li>
<li id="S1.I7.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I7.i5.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I7.i5.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Def.</span> <span class="ltx_text ltx_font_bold">Double torus</span> <math id="S1.I7.i5.p1.m2" class="ltx_Math" alttext="T^{2}\#T^{2}" display="inline"><mrow><msup><mi>T</mi><mn>2</mn></msup><mo>⁢</mo><mi mathvariant="normal">#</mi><mo>⁢</mo><msup><mi>T</mi><mn>2</mn></msup></mrow></math>: the quotient of an octagon with boundary word
<math id="S1.I7.i5.p1.m3" class="ltx_Math" alttext="a\,b\,a^{-1}b^{-1}\,c\,d\,c^{-1}d^{-1}." display="inline"><mrow><mrow><mi>a</mi><mo lspace="0.170em">⁢</mo><mi>b</mi><mo lspace="0.170em">⁢</mo><msup><mi>a</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><msup><mi>b</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><mi>c</mi><mo lspace="0.170em">⁢</mo><mi>d</mi><mo lspace="0.170em">⁢</mo><msup><mi>c</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup><mo>⁢</mo><msup><mi>d</mi><mrow><mo>−</mo><mn>1</mn></mrow></msup></mrow><mo lspace="0em">.</mo></mrow></math>
Cutting along the diagonal gives two tori each with a disc removed; regluing along that
circle is the connected sum.</p>
</div>
</li>
<li id="S1.I7.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I7.i6.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I7.i6.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I7.i6.p1.m2" class="ltx_Math" alttext="\pi_{1}(T^{2}\#T^{2})" display="inline"><mrow><msub><mi>π</mi><mn>1</mn></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><mrow><msup><mi>T</mi><mn>2</mn></msup><mo>⁢</mo><mi mathvariant="normal">#</mi><mo>⁢</mo><msup><mi>T</mi><mn>2</mn></msup></mrow><mo stretchy="false">)</mo></mrow></mrow></math> is not abelian.</p>
</div>
<div id="S1.I7.i6.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Let <math id="S1.I7.i6.p2.m1" class="ltx_Math" alttext="A\subset X=T^{2}\#T^{2}" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">⊂</mo><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D">=</mo><mrow><msup><mi mathcolor="#3D3D3D">T</mi><mn mathcolor="#3D3D3D">2</mn></msup><mo>⁢</mo><mi mathcolor="#3D3D3D" mathvariant="normal">#</mi><mo>⁢</mo><msup><mi mathcolor="#3D3D3D">T</mi><mn mathcolor="#3D3D3D">2</mn></msup></mrow></mrow></math> be the edges labelled <math id="S1.I7.i6.p2.m2" class="ltx_Math" alttext="a" display="inline"><mi mathcolor="#3D3D3D">a</mi></math> and <math id="S1.I7.i6.p2.m3" class="ltx_Math" alttext="c" display="inline"><mi mathcolor="#3D3D3D">c</mi></math>; then <math id="S1.I7.i6.p2.m4" class="ltx_Math" alttext="A\cong 8" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D">≅</mo><mn mathcolor="#3D3D3D">8</mn></mrow></math>.
There is a retraction <math id="S1.I7.i6.p2.m5" class="ltx_Math" alttext="r\colon X\to A" display="inline"><mrow><mi mathcolor="#3D3D3D">r</mi><mo lspace="0.278em" mathcolor="#3D3D3D" rspace="0.278em">:</mo><mrow><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D" stretchy="false">→</mo><mi mathcolor="#3D3D3D">A</mi></mrow></mrow></math>: collapse the cutting circle to get <math id="S1.I7.i6.p2.m6" class="ltx_Math" alttext="T^{2}\vee T^{2}" display="inline"><mrow><msup><mi mathcolor="#3D3D3D">T</mi><mn mathcolor="#3D3D3D">2</mn></msup><mo mathcolor="#3D3D3D">∨</mo><msup><mi mathcolor="#3D3D3D">T</mi><mn mathcolor="#3D3D3D">2</mn></msup></mrow></math>,
then retract each torus onto a circle. So <math id="S1.I7.i6.p2.m7" class="ltx_Math" alttext="j_{*}\colon\pi_{1}(8)\to\pi_{1}(X)" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">j</mi><mo mathcolor="#3D3D3D">∗</mo></msub><mo lspace="0.278em" mathcolor="#3D3D3D" rspace="0.278em">:</mo><mrow><mrow><msub><mi mathcolor="#3D3D3D">π</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mn mathcolor="#3D3D3D">8</mn><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D" stretchy="false">→</mo><mrow><msub><mi mathcolor="#3D3D3D">π</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></mrow></math> is injective,
and <math id="S1.I7.i6.p2.m8" class="ltx_Math" alttext="\pi_{1}(X)" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">π</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mi mathcolor="#3D3D3D">X</mi><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> has a non-abelian subgroup.</span></span></p>
</div>
</li>
<li id="S1.I7.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I7.i7.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I7.i7.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I7.i7.p1.m2" class="ltx_Math" alttext="S^{2}" display="inline"><msup><mi>S</mi><mn>2</mn></msup></math>, <math id="S1.I7.i7.p1.m3" class="ltx_Math" alttext="T^{2}" display="inline"><msup><mi>T</mi><mn>2</mn></msup></math> and <math id="S1.I7.i7.p1.m4" class="ltx_Math" alttext="T^{2}\#T^{2}" display="inline"><mrow><msup><mi>T</mi><mn>2</mn></msup><mo>⁢</mo><mi mathvariant="normal">#</mi><mo>⁢</mo><msup><mi>T</mi><mn>2</mn></msup></mrow></math> are pairwise non-homeomorphic.</p>
</div>
<div id="S1.I7.i7.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I7.i7.p2.m1" class="ltx_Math" alttext="\pi_{1}(S^{2})=1" display="inline"><mrow><mrow><msub><mi mathcolor="#3D3D3D">π</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msup><mi mathcolor="#3D3D3D">S</mi><mn mathcolor="#3D3D3D">2</mn></msup><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mn mathcolor="#3D3D3D">1</mn></mrow></math> and <math id="S1.I7.i7.p2.m2" class="ltx_Math" alttext="\pi_{1}(T^{2})=\mathbb{Z}^{2}" display="inline"><mrow><mrow><msub><mi mathcolor="#3D3D3D">π</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msup><mi mathcolor="#3D3D3D">T</mi><mn mathcolor="#3D3D3D">2</mn></msup><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><msup><mi mathcolor="#3D3D3D">ℤ</mi><mn mathcolor="#3D3D3D">2</mn></msup></mrow></math> are abelian and non-isomorphic;
<math id="S1.I7.i7.p2.m3" class="ltx_Math" alttext="\pi_{1}(T^{2}\#T^{2})" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">π</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><msup><mi mathcolor="#3D3D3D">T</mi><mn mathcolor="#3D3D3D">2</mn></msup><mo>⁢</mo><mi mathcolor="#3D3D3D" mathvariant="normal">#</mi><mo>⁢</mo><msup><mi mathcolor="#3D3D3D">T</mi><mn mathcolor="#3D3D3D">2</mn></msup></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> is not abelian. Fundamental groups distinguish all three.</span></span></p>
</div>
</li>
<li id="S1.I7.i8" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I7.i8.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> <span class="ltx_text ltx_font_bold">Closing remark (3-manifolds).</span> A compact 3-manifold splits into finitely many
compact connected ones; a connected one is <em class="ltx_emph ltx_font_italic">irreducible</em> if every embedded <math id="S1.I7.i8.p1.m1" class="ltx_Math" alttext="S^{2}" display="inline"><msup><mi>S</mi><mn>2</mn></msup></math>
bounds an embedded <math id="S1.I7.i8.p1.m2" class="ltx_Math" alttext="B^{3}" display="inline"><msup><mi>B</mi><mn>3</mn></msup></math>, and reducible ones simplify by cutting along such a sphere and
capping off. By Thurston’s geometrization conjecture, proved by Perelman, an irreducible
3-manifold decomposes along canonical tori into geometric pieces (eight model geometries).
Combining the classifications — Waldhausen for Haken manifolds, Seifert for six of the
geometries, Mostow rigidity for the hyperbolic one — the fundamental group turns out to
be a complete invariant for irreducible 3-manifolds, apart from lens spaces.</p>
</div>
</li>
</ul>
</div>
<div id="S1.SS7.p2" class="ltx_para">
<p class="ltx_p ltx_align_center"><span class="ltx_text" style="font-size:90%;color:#737373;">— end of notes —</span></p>
</div>
</section>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 18:48:11 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
{% endraw %}
