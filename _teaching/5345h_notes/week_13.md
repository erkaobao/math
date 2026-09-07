---
layout: archive
title: "MATH 5345H --- Week 13: Paracompactness; complete metric spaces"
permalink: /teaching/5345h_notes/week_13
author_profile: false
render_with_liquid: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

{% raw %}
<div class="ltx_page_main">
<div class="ltx_page_content">
<article class="ltx_document">
<section id="S1" class="ltx_section">
<h2 class="ltx_title ltx_font_bold ltx_title_section" style="font-size:144%;color:#1A3873;">1  Complete Metric Spaces and Function Spaces</h2>

<section id="S1.SS1" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.1  (§43) Complete metric spaces</h3>

<div id="S1.SS1.p1" class="ltx_para ltx_noindent">
<ul id="S1.I1" class="ltx_itemize">
<li id="S1.I1.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I1.i1.p1.m1" class="ltx_Math" alttext="(x_{n})" display="inline"><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mi>n</mi></msub><mo stretchy="false">)</mo></mrow></math> in <math id="S1.I1.i1.p1.m2" class="ltx_Math" alttext="(X,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> is <em class="ltx_emph ltx_font_italic">Cauchy</em> if <math id="S1.I1.i1.p1.m3" class="ltx_Math" alttext="\forall\varepsilon&gt;0\ \exists N" display="inline"><mrow><mrow><mo rspace="0.167em">∀</mo><mi>ε</mi></mrow><mo>&gt;</mo><mrow><mn>0</mn><mo lspace="0.667em">⁢</mo><mrow><mo rspace="0.167em">∃</mo><mi>N</mi></mrow></mrow></mrow></math>:
<math id="S1.I1.i1.p1.m4" class="ltx_Math" alttext="d(x_{m},x_{n})&lt;\varepsilon" display="inline"><mrow><mrow><mi>d</mi><mo>⁢</mo><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mi>m</mi></msub><mo>,</mo><msub><mi>x</mi><mi>n</mi></msub><mo stretchy="false">)</mo></mrow></mrow><mo>&lt;</mo><mi>ε</mi></mrow></math> for all <math id="S1.I1.i1.p1.m5" class="ltx_Math" alttext="m,n\geq N" display="inline"><mrow><mrow><mi>m</mi><mo>,</mo><mi>n</mi></mrow><mo>≥</mo><mi>N</mi></mrow></math>.
<math id="S1.I1.i1.p1.m6" class="ltx_Math" alttext="(X,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> is <em class="ltx_emph ltx_font_italic">complete</em> if every Cauchy sequence converges.</p>
</div>
</li>
<li id="S1.I1.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i2.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Rmk.</span> Every convergent sequence is Cauchy. The converse is the content of completeness.</p>
</div>
</li>
<li id="S1.I1.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Lem.</span> It suffices that every Cauchy sequence has a <em class="ltx_emph ltx_font_italic">convergent subsequence</em>.</p>
</div>
<div id="S1.I1.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Cauchy <math id="S1.I1.i3.p2.m1" class="ltx_Math" alttext="+" display="inline"><mo mathcolor="#3D3D3D">+</mo></math> a subsequential limit <math id="S1.I1.i3.p2.m2" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> the whole sequence converges to it.</span></span></p>
</div>
</li>
<li id="S1.I1.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> Every compact metric space is complete.</p>
</div>
<div id="S1.I1.i4.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> Sequential compactness supplies the subsequence.</span></span></p>
</div>
</li>
<li id="S1.I1.i5" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I1.i5.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I1.i5.p1.m1" class="ltx_Math" alttext="\mathbb{R}^{n}" display="inline"><msup><mi>ℝ</mi><mi>n</mi></msup></math> is complete (in any norm-induced metric).</p>
</div>
</li>
</ul>
</div>
</section>
<section id="S1.SS2" class="ltx_subsection">
<h3 class="ltx_title ltx_font_bold ltx_title_subsection" style="font-size:120%;color:#1A3873;">1.2  (§45) Compactness in metric spaces</h3>

<div id="S1.SS2.p1" class="ltx_para ltx_noindent">
<ul id="S1.I2" class="ltx_itemize">
<li id="S1.I2.i1" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i1.p1" class="ltx_para">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Def.</span> <math id="S1.I2.i1.p1.m1" class="ltx_Math" alttext="(X,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> is <em class="ltx_emph ltx_font_italic">totally bounded</em> if for every <math id="S1.I2.i1.p1.m2" class="ltx_Math" alttext="\varepsilon&gt;0" display="inline"><mrow><mi>ε</mi><mo>&gt;</mo><mn>0</mn></mrow></math> finitely many
<math id="S1.I2.i1.p1.m3" class="ltx_Math" alttext="\varepsilon" display="inline"><mi>ε</mi></math>-balls cover <math id="S1.I2.i1.p1.m4" class="ltx_Math" alttext="X" display="inline"><mi>X</mi></math>.</p>
</div>
</li>
<li id="S1.I2.i2" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i2.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Prop.</span> Compact <math id="S1.I2.i2.p1.m1" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo stretchy="false">⇒</mo></math> totally bounded.</p>
</div>
<div id="S1.I2.i2.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> The <math id="S1.I2.i2.p2.m1" class="ltx_Math" alttext="\varepsilon" display="inline"><mi mathcolor="#3D3D3D">ε</mi></math>-balls form an open cover.</span></span></p>
</div>
</li>
<li id="S1.I2.i3" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i3.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><math id="S1.I2.i3.p1.m1" class="ltx_Math" alttext="\bigstar" display="inline"><mi mathvariant="normal">★</mi></math> <span class="ltx_text ltx_font_bold">Thm.</span> <math id="S1.I2.i3.p1.m2" class="ltx_Math" alttext="(X,d)" display="inline"><mrow><mo stretchy="false">(</mo><mi>X</mi><mo>,</mo><mi>d</mi><mo stretchy="false">)</mo></mrow></math> is compact <math id="S1.I2.i3.p1.m3" class="ltx_Math" alttext="\Leftrightarrow" display="inline"><mo stretchy="false">⇔</mo></math> complete and totally bounded.</p>
</div>
<div id="S1.I2.i3.p2" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold ltx_font_italic" style="font-size:90%;color:#3D3D3D;">Proof.<span class="ltx_text ltx_font_medium ltx_font_upright"> <math id="S1.I2.i3.p2.m1" class="ltx_Math" alttext="\Leftarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇐</mo></math>: build a Cauchy subsequence. Cover by finitely many balls of radius <math id="S1.I2.i3.p2.m2" class="ltx_Math" alttext="1" display="inline"><mn mathcolor="#3D3D3D">1</mn></math>;
one, <math id="S1.I2.i3.p2.m3" class="ltx_Math" alttext="B_{1}" display="inline"><msub><mi mathcolor="#3D3D3D">B</mi><mn mathcolor="#3D3D3D">1</mn></msub></math>, contains <math id="S1.I2.i3.p2.m4" class="ltx_Math" alttext="x_{n}" display="inline"><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">n</mi></msub></math> for <math id="S1.I2.i3.p2.m5" class="ltx_Math" alttext="n" display="inline"><mi mathcolor="#3D3D3D">n</mi></math> in an infinite set <math id="S1.I2.i3.p2.m6" class="ltx_Math" alttext="J_{1}" display="inline"><msub><mi mathcolor="#3D3D3D">J</mi><mn mathcolor="#3D3D3D">1</mn></msub></math>. Inductively pick <math id="S1.I2.i3.p2.m7" class="ltx_Math" alttext="B_{k+1}" display="inline"><msub><mi mathcolor="#3D3D3D">B</mi><mrow><mi mathcolor="#3D3D3D">k</mi><mo mathcolor="#3D3D3D">+</mo><mn mathcolor="#3D3D3D">1</mn></mrow></msub></math> of
radius <math id="S1.I2.i3.p2.m8" class="ltx_Math" alttext="1/(k+1)" display="inline"><mrow><mn mathcolor="#3D3D3D">1</mn><mo mathcolor="#3D3D3D">/</mo><mrow><mo mathcolor="#3D3D3D" stretchy="false">(</mo><mrow><mi mathcolor="#3D3D3D">k</mi><mo mathcolor="#3D3D3D">+</mo><mn mathcolor="#3D3D3D">1</mn></mrow><mo mathcolor="#3D3D3D" stretchy="false">)</mo></mrow></mrow></math> containing <math id="S1.I2.i3.p2.m9" class="ltx_Math" alttext="x_{n}" display="inline"><msub><mi mathcolor="#3D3D3D">x</mi><mi mathcolor="#3D3D3D">n</mi></msub></math> for infinitely many <math id="S1.I2.i3.p2.m10" class="ltx_Math" alttext="n\in J_{k}" display="inline"><mrow><mi mathcolor="#3D3D3D">n</mi><mo mathcolor="#3D3D3D">∈</mo><msub><mi mathcolor="#3D3D3D">J</mi><mi mathcolor="#3D3D3D">k</mi></msub></mrow></math>, giving
<math id="S1.I2.i3.p2.m11" class="ltx_Math" alttext="J_{1}\supset J_{2}\supset\cdots" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">J</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">⊃</mo><msub><mi mathcolor="#3D3D3D">J</mi><mn mathcolor="#3D3D3D">2</mn></msub><mo mathcolor="#3D3D3D">⊃</mo><mi mathcolor="#3D3D3D" mathvariant="normal">⋯</mi></mrow></math>. Choose <math id="S1.I2.i3.p2.m12" class="ltx_Math" alttext="n_{1}&lt;n_{2}&lt;\cdots" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">n</mi><mn mathcolor="#3D3D3D">1</mn></msub><mo mathcolor="#3D3D3D">&lt;</mo><msub><mi mathcolor="#3D3D3D">n</mi><mn mathcolor="#3D3D3D">2</mn></msub><mo mathcolor="#3D3D3D">&lt;</mo><mi mathcolor="#3D3D3D" mathvariant="normal">⋯</mi></mrow></math> with <math id="S1.I2.i3.p2.m13" class="ltx_Math" alttext="n_{k}\in J_{k}" display="inline"><mrow><msub><mi mathcolor="#3D3D3D">n</mi><mi mathcolor="#3D3D3D">k</mi></msub><mo mathcolor="#3D3D3D">∈</mo><msub><mi mathcolor="#3D3D3D">J</mi><mi mathcolor="#3D3D3D">k</mi></msub></mrow></math>;
then <math id="S1.I2.i3.p2.m14" class="ltx_Math" alttext="x_{n_{i}},x_{n_{j}}\in B_{k}" display="inline"><mrow><mrow><msub><mi mathcolor="#3D3D3D">x</mi><msub><mi mathcolor="#3D3D3D">n</mi><mi mathcolor="#3D3D3D">i</mi></msub></msub><mo mathcolor="#3D3D3D">,</mo><msub><mi mathcolor="#3D3D3D">x</mi><msub><mi mathcolor="#3D3D3D">n</mi><mi mathcolor="#3D3D3D">j</mi></msub></msub></mrow><mo mathcolor="#3D3D3D">∈</mo><msub><mi mathcolor="#3D3D3D">B</mi><mi mathcolor="#3D3D3D">k</mi></msub></mrow></math> for <math id="S1.I2.i3.p2.m15" class="ltx_Math" alttext="i,j\geq k" display="inline"><mrow><mrow><mi mathcolor="#3D3D3D">i</mi><mo mathcolor="#3D3D3D">,</mo><mi mathcolor="#3D3D3D">j</mi></mrow><mo mathcolor="#3D3D3D">≥</mo><mi mathcolor="#3D3D3D">k</mi></mrow></math>, so the subsequence is Cauchy.
Complete <math id="S1.I2.i3.p2.m16" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> convergent <math id="S1.I2.i3.p2.m17" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> sequentially compact <math id="S1.I2.i3.p2.m18" class="ltx_Math" alttext="\Rightarrow" display="inline"><mo mathcolor="#3D3D3D" stretchy="false">⇒</mo></math> compact (§28).</span></span></p>
</div>
</li>
<li id="S1.I2.i4" class="ltx_item" style="list-style-type:none;">
<span class="ltx_tag ltx_tag_item">•</span> 
<div id="S1.I2.i4.p1" class="ltx_para ltx_noindent">
<p class="ltx_p"><span class="ltx_text ltx_font_bold">Caution.</span> Total boundedness alone is not enough — and boundedness alone is far weaker
than total boundedness in general metric spaces.</p>
</div>
</li>
</ul>
</div>
</section>
</section>
</article>
</div>
<footer class="ltx_page_footer">
<div class="ltx_page_logo">Generated  on Mon Sep  7 18:48:00 2026 by <a href="http://dlmf.nist.gov/LaTeXML/" class="ltx_LaTeXML_logo"><span style="letter-spacing:-0.2em; margin-right:0.1em;">L<span class="ltx_font_smallcaps" style="position:relative; bottom:2.2pt;">a</span>T<span class="ltx_font_smallcaps" style="font-size:120%;position:relative; bottom:-0.2ex;">e</span></span><span style="font-size:90%; position:relative; bottom:-0.2ex;">XML</span><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEwAACxMBAJqcGAAAAAd0SU1FB9wKExQZLWTEaOUAAAAddEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIFRoZSBHSU1Q72QlbgAAAdpJREFUKM9tkL+L2nAARz9fPZNCKFapUn8kyI0e4iRHSR1Kb8ng0lJw6FYHFwv2LwhOpcWxTjeUunYqOmqd6hEoRDhtDWdA8ApRYsSUCDHNt5ul13vz4w0vWCgUnnEc975arX6ORqN3VqtVZbfbTQC4uEHANM3jSqXymFI6yWazP2KxWAXAL9zCUa1Wy2tXVxheKA9YNoR8Pt+aTqe4FVVVvz05O6MBhqUIBGk8Hn8HAOVy+T+XLJfLS4ZhTiRJgqIoVBRFIoric47jPnmeB1mW/9rr9ZpSSn3Lsmir1fJZlqWlUonKsvwWwD8ymc/nXwVBeLjf7xEKhdBut9Hr9WgmkyGEkJwsy5eHG5vN5g0AKIoCAEgkEkin0wQAfN9/cXPdheu6P33fBwB4ngcAcByHJpPJl+fn54mD3Gg0NrquXxeLRQAAwzAYj8cwTZPwPH9/sVg8PXweDAauqqr2cDjEer1GJBLBZDJBs9mE4zjwfZ85lAGg2+06hmGgXq+j3+/DsixYlgVN03a9Xu8jgCNCyIegIAgx13Vfd7vdu+FweG8YRkjXdWy329+dTgeSJD3ieZ7RNO0VAXAPwDEAO5VKndi2fWrb9jWl9Esul6PZbDY9Go1OZ7PZ9z/lyuD3OozU2wAAAABJRU5ErkJggg==" alt="Mascot Sammy"></a>
</div></footer>
</div>
{% endraw %}
