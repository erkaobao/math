---
layout: archive
title: "MATH 5345H --- Week 12: The Tychonoff theorem and compactness of products"
permalink: /teaching/5345h_notes/week_12
author_profile: false
render_with_liquid: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S1" class="ltx_section">
<h2 class="ltx_title ltx_font_bold ltx_title_section" style="font-size:144%;color:#1A3873;">1  The Tychonoff Theorem</h2>

<section id="S1.SS1" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.1  (§37) The Tychonoff theorem</h3>

<div id="S1.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S1.I1" class="ltx_itemize">
<li id="S1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><math id="S1.I1.i1.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Tychonoff.)</span> For any <math id="S1.I1.i1.p1.m2" class="ltx_Math" alttext="J" display="inline"><mi>J</mi></math> and any compact spaces <math id="S1.I1.i1.p1.m3" class="ltx_Math" alttext="X_{\alpha}" display="inline"><msub><mi>X</mi><mi>α</mi></msub></math>,
the product <math id="S1.I1.i1.p1.m4" class="ltx_Math" alttext="\prod_{\alpha\in J}X_{\alpha}" display="inline"><mrow><msub><mo>∏</mo><mrow><mi>α</mi><mo>∈</mo><mi>J</mi></mrow></msub><msub><mi>X</mi><mi>α</mi></msub></mrow></math> is compact in the product topology.</p>
</div>
</li>
<li id="S1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Proved above for finite <math id="S1.I1.i2.p1.m1" class="ltx_Math" alttext="J" display="inline"><mi>J</mi></math> (tube lemma). The general case is omitted here;
it needs the axiom of choice. Application below instead.</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS2" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.2  The profinite integers</h3>

<div id="S1.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S1.I2" class="ltx_itemize">
<li id="S1.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Notation.</span> <math id="S1.I2.i1.p1.m1" class="ltx_Math" alttext="a\equiv b\ (\mathrm{mod}\ n)" display="inline"><mrow><mi>a</mi><mo>≡</mo><mrow><mi>b</mi><mo lspace="0.500em">⁢</mo><mrow><mo stretchy="false">(</mo><mrow><mi>mod</mi><mo lspace="0.500em">⁢</mo><mi>n</mi></mrow><mo stretchy="false">)</mo></mrow></mrow></mrow></math> iff <math id="S1.I2.i1.p1.m2" class="ltx_Math" alttext="n\mid b-a" display="inline"><mrow><mi>n</mi><mo>∣</mo><mrow><mi>b</mi><mo>−</mo><mi>a</mi></mrow></mrow></math>; classes <math id="S1.I2.i1.p1.m3" class="ltx_Math" alttext="[a]_{n}=a+n\mathbb{Z}" display="inline"><mrow><msub><mrow><mo stretchy="false">[</mo><mi>a</mi><mo stretchy="false">]</mo></mrow><mi>n</mi></msub><mo>=</mo><mrow><mi>a</mi><mo>+</mo><mrow><mi>n</mi><mo>⁢</mo><mi>ℤ</mi></mrow></mrow></mrow></math>;
ring <math id="S1.I2.i1.p1.m4" class="ltx_Math" alttext="\mathbb{Z}/n" display="inline"><mrow><mi>ℤ</mi><mo>/</mo><mi>n</mi></mrow></math> with <math id="S1.I2.i1.p1.m5" class="ltx_Math" alttext="[a]_{n}+[b]_{n}=[a+b]_{n}" display="inline"><mrow><mrow><msub><mrow><mo stretchy="false">[</mo><mi>a</mi><mo stretchy="false">]</mo></mrow><mi>n</mi></msub><mo>+</mo><msub><mrow><mo stretchy="false">[</mo><mi>b</mi><mo stretchy="false">]</mo></mrow><mi>n</mi></msub></mrow><mo>=</mo><msub><mrow><mo stretchy="false">[</mo><mrow><mi>a</mi><mo>+</mo><mi>b</mi></mrow><mo stretchy="false">]</mo></mrow><mi>n</mi></msub></mrow></math>, <math id="S1.I2.i1.p1.m6" class="ltx_Math" alttext="[a]_{n}\cdot[b]_{n}=[ab]_{n}" display="inline"><mrow><mrow><msub><mrow><mo stretchy="false">[</mo><mi>a</mi><mo stretchy="false">]</mo></mrow><mi>n</mi></msub><mo lspace="0.222em" rspace="0.222em">⋅</mo><msub><mrow><mo stretchy="false">[</mo><mi>b</mi><mo stretchy="false">]</mo></mrow><mi>n</mi></msub></mrow><mo>=</mo><msub><mrow><mo stretchy="false">[</mo><mrow><mi>a</mi><mo>⁢</mo><mi>b</mi></mrow><mo stretchy="false">]</mo></mrow><mi>n</mi></msub></mrow></math>;
surjection <math id="S1.I2.i1.p1.m7" class="ltx_Math" alttext="\varphi_{n}\colon\mathbb{Z}\to\mathbb{Z}/n" display="inline"><mrow><msub><mi>φ</mi><mi>n</mi></msub><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>ℤ</mi><mo stretchy="false">→</mo><mrow><mi>ℤ</mi><mo>/</mo><mi>n</mi></mrow></mrow></mrow></math>.</p>
</div>
</li>
<li id="S1.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> Give each <math id="S1.I2.i2.p1.m1" class="ltx_Math" alttext="\mathbb{Z}/n" display="inline"><mrow><mi>ℤ</mi><mo>/</mo><mi>n</mi></mrow></math> and <math id="S1.I2.i2.p1.m2" class="ltx_Math" alttext="\mathbb{Z}" display="inline"><mi>ℤ</mi></math> the discrete topology. Then
<math id="S1.I2.i2.p1.m3" class="ltx_Math" alttext="\prod_{n=1}^{\infty}\mathbb{Z}/n" display="inline"><mrow><msubsup><mo>∏</mo><mrow><mi>n</mi><mo>=</mo><mn>1</mn></mrow><mi mathvariant="normal">∞</mi></msubsup><mrow><mi>ℤ</mi><mo>/</mo><mi>n</mi></mrow></mrow></math> is compact Hausdorff, and
<math id="S1.I2.i2.p1.m4" class="ltx_Math" alttext="\Phi=(\varphi_{1},\varphi_{2},\dots)\colon\mathbb{Z}\to\prod_{n}\mathbb{Z}/n" display="inline"><mrow><mrow><mi mathvariant="normal">Φ</mi><mo>=</mo><mrow><mo stretchy="false">(</mo><msub><mi>φ</mi><mn>1</mn></msub><mo>,</mo><msub><mi>φ</mi><mn>2</mn></msub><mo>,</mo><mi mathvariant="normal">…</mi><mo rspace="0.278em" stretchy="false">)</mo></mrow></mrow><mo rspace="0.278em">:</mo><mrow><mi>ℤ</mi><mo rspace="0.111em" stretchy="false">→</mo><mrow><msub><mo>∏</mo><mi>n</mi></msub><mrow><mi>ℤ</mi><mo>/</mo><mi>n</mi></mrow></mrow></mrow></mrow></math>
is injective and continuous.</p>
</div>
<div id="S1.I2.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Each <math id="S1.I2.i2.p2.m1" class="ltx_Math" alttext="\mathbb{Z}/n" display="inline"><mrow><mi mathcolor="#3D3D3D">ℤ</mi><mo mathcolor="#3D3D3D">/</mo><mi mathcolor="#3D3D3D">n</mi></mrow></math> is finite, hence compact; Tychonoff. Injective: if <math id="S1.I2.i2.p2.m2" class="ltx_Math" alttext="n\mid b-a" display="inline"><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">∣</mo><mrow><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">a</mi></mrow></mrow></math> for all <math id="S1.I2.i2.p2.m3" class="ltx_Math" alttext="n" display="inline"><mi mathcolor="#3D3D3D">n</mi></math>,
take <math id="S1.I2.i2.p2.m4" class="ltx_Math" alttext="n&gt;|b-a|" display="inline"><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">&gt;</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">|</mo><mrow><mi mathcolor="#3D3D3D">b</mi><mo mathcolor="#3D3D3D">−</mo><mi mathcolor="#3D3D3D">a</mi></mrow><mo mathcolor="#3D3D3D" stretchy="false">|</mo></mrow></mrow></math>.</span></span></p>
</div>
</li>
<li id="S1.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i3.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> For <math id="S1.I2.i3.p1.m1" class="ltx_Math" alttext="d\mid m" display="inline"><mrow><mi>d</mi><mo>∣</mo><mi>m</mi></mrow></math>, reduction <math id="S1.I2.i3.p1.m2" class="ltx_Math" alttext="\rho_{m,d}\colon\mathbb{Z}/m\to\mathbb{Z}/d" display="inline"><mrow><msub><mi>ρ</mi><mrow><mi>m</mi><mo>,</mo><mi>d</mi></mrow></msub><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mrow><mi>ℤ</mi><mo>/</mo><mi>m</mi></mrow><mo stretchy="false">→</mo><mrow><mi>ℤ</mi><mo>/</mo><mi>d</mi></mrow></mrow></mrow></math>, <math id="S1.I2.i3.p1.m3" class="ltx_Math" alttext="[a]_{m}\mapsto[a]_{d}" display="inline"><mrow><msub><mrow><mo stretchy="false">[</mo><mi>a</mi><mo stretchy="false">]</mo></mrow><mi>m</mi></msub><mo stretchy="false">↦</mo><msub><mrow><mo stretchy="false">[</mo><mi>a</mi><mo stretchy="false">]</mo></mrow><mi>d</mi></msub></mrow></math>;
note <math id="S1.I2.i3.p1.m4" class="ltx_Math" alttext="\rho_{m,d}\circ\varphi_{m}=\varphi_{d}" display="inline"><mrow><mrow><msub><mi>ρ</mi><mrow><mi>m</mi><mo>,</mo><mi>d</mi></mrow></msub><mo lspace="0.222em" rspace="0.222em">∘</mo><msub><mi>φ</mi><mi>m</mi></msub></mrow><mo>=</mo><msub><mi>φ</mi><mi>d</mi></msub></mrow></math>. Set</p>
<table id="S1.Ex1" class="ltx_equation ltx_eqn_table">

<tbody><tr class="ltx_equation ltx_eqn_row ltx_align_baseline">
<td class="ltx_eqn_cell ltx_eqn_center_padleft"></td>
<td class="ltx_eqn_cell ltx_align_center"><math id="S1.Ex1.m1" class="ltx_Math" alttext="\widehat{\mathbb{Z}}=\Bigl{\{}(x_{n})_{n}\in\prod_{n=1}^{\infty}\mathbb{Z}/n\ %
\Bigm{|}\ \rho_{m,d}(x_{m})=x_{d}\ \text{ for all }d\mid m\Bigr{\}}," display="block"><mrow><mrow><mover accent="true"><mi>ℤ</mi><mo>^</mo></mover><mo>=</mo><mrow><mo maxsize="160%" minsize="160%">{</mo><mrow><msub><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mi>n</mi></msub><mo stretchy="false">)</mo></mrow><mi>n</mi></msub><mo rspace="0.111em">∈</mo><mrow><munderover><mo movablelimits="false">∏</mo><mrow><mi>n</mi><mo>=</mo><mn>1</mn></mrow><mi mathvariant="normal">∞</mi></munderover><mrow><mi>ℤ</mi><mo>/</mo><mi>n</mi></mrow></mrow></mrow><mo lspace="0.500em" mathsize="160%" rspace="0.500em">|</mo><mrow><mrow><msub><mi>ρ</mi><mrow><mi>m</mi><mo>,</mo><mi>d</mi></mrow></msub><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mi>m</mi></msub><mo stretchy="false">)</mo></mrow></mrow><mo>=</mo><mrow><mrow><msub><mi>x</mi><mi>d</mi></msub><mo>⁢</mo><mtext> for all </mtext><mo>⁢</mo><mi>d</mi></mrow><mo>∣</mo><mi>m</mi></mrow></mrow><mo maxsize="160%" minsize="160%">}</mo></mrow></mrow><mo>,</mo></mrow></math></td>
<td class="ltx_eqn_cell ltx_eqn_center_padright"></td>
</tr></tbody>
</table>
<p class="ltx_p">the ring of <em class="ltx_emph ltx_font_italic">profinite integers</em> (operations termwise; a topological ring).</p>
</div>
</li>
<li id="S1.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i4.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I2.i4.p1.m2" class="ltx_Math" alttext="\widehat{\mathbb{Z}}" display="inline"><mover accent="true"><mi>ℤ</mi><mo>^</mo></mover></math> is a closed subspace of <math id="S1.I2.i4.p1.m3" class="ltx_Math" alttext="\prod_{n}\mathbb{Z}/n" display="inline"><mrow><msub><mo>∏</mo><mi>n</mi></msub><mrow><mi>ℤ</mi><mo>/</mo><mi>n</mi></mrow></mrow></math>, hence compact Hausdorff.</p>
</div>
<div id="S1.I2.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I2.i4.p2.m1" class="ltx_Math" alttext="\widehat{\mathbb{Z}}=\bigcap_{d\mid m}f_{m,d}^{-1}([0]_{d})" display="inline"><mrow><mover accent="true"><mi mathcolor="#3D3D3D">ℤ</mi><mo mathcolor="#3D3D3D">^</mo></mover><mo mathcolor="#3D3D3D" rspace="0.111em">=</mo><mrow><msub><mo mathcolor="#3D3D3D">⋂</mo><mrow><mi mathcolor="#3D3D3D">d</mi><mo mathcolor="#3D3D3D">∣</mo><mi mathcolor="#3D3D3D">m</mi></mrow></msub><mrow><msubsup><mi mathcolor="#3D3D3D">f</mi><mrow><mi mathcolor="#3D3D3D">m</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">d</mi></mrow><mrow><mo mathcolor="#3D3D3D">−</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msubsup><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mn mathcolor="#3D3D3D">0</mn><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow><mi mathcolor="#3D3D3D">d</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></mrow></mrow></math> where
<math id="S1.I2.i4.p2.m2" class="ltx_Math" alttext="f_{m,d}\bigl{(}(x_{n})\bigr{)}=\rho_{m,d}(x_{m})-x_{d}" display="inline"><mrow><mrow><msub><mi mathcolor="#3D3D3D">f</mi><mrow><mi mathcolor="#3D3D3D">m</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">d</mi></mrow></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" maxsize="133%" minsize="133%">(</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow><mo mathcolor="#3D3D3D" maxsize="133%" minsize="133%">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">=</mo><mrow><mrow><msub><mi mathcolor="#3D3D3D">ρ</mi><mrow><mi mathcolor="#3D3D3D">m</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">d</mi></mrow></msub><mo>⁢</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">m</mi></msub><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow><mo mathcolor="#3D3D3D">−</mo><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">d</mi></msub></mrow></mrow></math> is continuous and <math id="S1.I2.i4.p2.m3" class="ltx_Math" alttext="\mathbb{Z}/d" display="inline"><mrow><mi mathcolor="#3D3D3D">ℤ</mi><mo mathcolor="#3D3D3D">/</mo><mi mathcolor="#3D3D3D">d</mi></mrow></math> is discrete.</span></span></p>
</div>
</li>
<li id="S1.I2.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> <math id="S1.I2.i5.p1.m1" class="ltx_Math" alttext="\Phi" display="inline"><mi mathvariant="normal">Φ</mi></math> corestricts to an injective continuous ring map <math id="S1.I2.i5.p1.m2" class="ltx_Math" alttext="\Psi\colon\mathbb{Z}\to\widehat{\mathbb{Z}}" display="inline"><mrow><mi mathvariant="normal">Ψ</mi><mo lspace="0.278em" rspace="0.278em">:</mo><mrow><mi>ℤ</mi><mo stretchy="false">→</mo><mover accent="true"><mi>ℤ</mi><mo>^</mo></mover></mrow></mrow></math>,
with <em class="ltx_emph ltx_font_italic">dense</em> image.</p>
</div>
<div id="S1.I2.i5.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Given <math id="S1.I2.i5.p2.m1" class="ltx_Math" alttext="p\in\widehat{\mathbb{Z}}" display="inline"><mrow><mi mathcolor="#3D3D3D">p</mi><mo mathcolor="#3D3D3D">∈</mo><mover accent="true"><mi mathcolor="#3D3D3D">ℤ</mi><mo mathcolor="#3D3D3D">^</mo></mover></mrow></math> and a basis neighborhood constrained at finitely many <math id="S1.I2.i5.p2.m2" class="ltx_Math" alttext="n" display="inline"><mi mathcolor="#3D3D3D">n</mi></math>, let <math id="S1.I2.i5.p2.m3" class="ltx_Math" alttext="N" display="inline"><mi mathcolor="#3D3D3D">N</mi></math> be a
common multiple of those <math id="S1.I2.i5.p2.m4" class="ltx_Math" alttext="n" display="inline"><mi mathcolor="#3D3D3D">n</mi></math> and choose <math id="S1.I2.i5.p2.m5" class="ltx_Math" alttext="a" display="inline"><mi mathcolor="#3D3D3D">a</mi></math> with <math id="S1.I2.i5.p2.m6" class="ltx_Math" alttext="[a]_{N}=x_{N}" display="inline"><mrow><msub><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow><mi mathcolor="#3D3D3D">N</mi></msub><mo mathcolor="#3D3D3D">=</mo><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">N</mi></msub></mrow></math>; then <math id="S1.I2.i5.p2.m7" class="ltx_Math" alttext="[a]_{n}=x_{n}" display="inline"><mrow><msub><mrow><mo mathcolor="#3D3D3D" stretchy="false">[</mo><mi mathcolor="#3D3D3D">a</mi><mo mathcolor="#3D3D3D" stretchy="false">]</mo></mrow><mi mathcolor="#3D3D3D">n</mi></msub><mo mathcolor="#3D3D3D">=</mo><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">n</mi></msub></mrow></math> for each
constrained <math id="S1.I2.i5.p2.m8" class="ltx_Math" alttext="n" display="inline"><mi mathcolor="#3D3D3D">n</mi></math>.</span></span></p>
</div>
</li>
<li id="S1.I2.i6" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i6.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> The subspace topology on <math id="S1.I2.i6.p1.m1" class="ltx_Math" alttext="\mathbb{Z}" display="inline"><mi>ℤ</mi></math> from <math id="S1.I2.i6.p1.m2" class="ltx_Math" alttext="\widehat{\mathbb{Z}}" display="inline"><mover accent="true"><mi>ℤ</mi><mo>^</mo></mover></math> is the <em class="ltx_emph ltx_font_italic">Fürstenberg topology</em>.
(<math id="S1.I2.i6.p1.m3" class="ltx_Math" alttext="\Psi" display="inline"><mi mathvariant="normal">Ψ</mi></math> is not an embedding of <em class="ltx_emph ltx_font_italic">discrete</em> <math id="S1.I2.i6.p1.m4" class="ltx_Math" alttext="\mathbb{Z}" display="inline"><mi>ℤ</mi></math>.)</p>
</div>
</li>
<li id="S1.I2.i7" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i7.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i7.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <span class="ltx_text ltx_font_bold">(Euclid, ca. 300 BC.)</span> There are infinitely many primes.</p>
</div>
<div id="S1.I2.i7.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Fürstenberg’s 1955 argument. In the Fürstenberg topology every nonempty open set is
infinite, and each <math id="S1.I2.i7.p2.m1" class="ltx_Math" alttext="p\mathbb{Z}" display="inline"><mrow><mi mathcolor="#3D3D3D">p</mi><mo>⁢</mo><mi mathcolor="#3D3D3D">ℤ</mi></mrow></math> is closed. If there were finitely many primes,
<math id="S1.I2.i7.p2.m2" class="ltx_Math" alttext="A=\bigcup_{p}p\mathbb{Z}" display="inline"><mrow><mi mathcolor="#3D3D3D">A</mi><mo mathcolor="#3D3D3D" rspace="0.111em">=</mo><mrow><msub><mo mathcolor="#3D3D3D">⋃</mo><mi mathcolor="#3D3D3D">p</mi></msub><mrow><mi mathcolor="#3D3D3D">p</mi><mo>⁢</mo><mi mathcolor="#3D3D3D">ℤ</mi></mrow></mrow></mrow></math> would be closed, so its complement <math id="S1.I2.i7.p2.m3" class="ltx_Math" alttext="\{\pm 1\}" display="inline"><mrow><mo mathcolor="#3D3D3D" stretchy="false">{</mo><mrow><mo mathcolor="#3D3D3D">±</mo><mn mathcolor="#3D3D3D">1</mn></mrow><mo mathcolor="#3D3D3D" stretchy="false">}</mo></mrow></math> would be open and
finite — contradiction.</span></span></p>
</div>
</li>
</ul>
</div>
</section>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 03:59:32 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
