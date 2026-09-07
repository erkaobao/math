---
layout: archive
title: "MATH 5345H — Week 2: Cartesian Products, Indexed Families, and Finite Sets"
permalink: /teaching/5345h_notes/week_2
author_profile: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<p><em>Topic: Cartesian products; finite, countable, and uncountable sets (§§5–7); infinite sets, the axiom of choice, and well-ordered sets (§§9–10)</em></p>


<script type="text/x-mathjax-config">
MathJax.Hub.Config({
  TeX: {
    Macros: {
      RR: "\\mathbb{R}",
      NN: "\\mathbb{N}",
      ZZ: "\\mathbb{Z}",
      QQ: "\\mathbb{Q}",
      CX: "\\mathbb{C}",
      Zh: "\\widehat{\\mathbb{Z}}",
      cT: "\\mathcal{T}",
      cB: "\\mathcal{B}",
      cS: "\\mathcal{S}",
      cA: "\\mathcal{A}",
      cC: "\\mathcal{C}",
      cD: "\\mathcal{D}",
      cU: "\\mathcal{U}",
      Pow: "\\mathcal{P}",
      Map: "\\mathscr{C}",
      sm: "\\smallsetminus",
      Cl: ["\\operatorname{Cl}", 0],
      Int: ["\\operatorname{Int}", 0],
      diam: ["\\operatorname{diam}", 0],
      id: ["\\operatorname{id}", 0],
      To: "\\longrightarrow",
      imp: "\\Rightarrow",
      Tdisc: "\\mathcal{T}_{\\mathrm{disc}}",
      Ttriv: "\\mathcal{T}_{\\mathrm{triv}}",
      Tcof: "\\mathcal{T}_{\\mathrm{cof}}"
    }
  }
});
</script>


<style>
.notes-list { list-style: disc; margin: 0.8em 0 0.8em 1.6em; padding: 0; }
.notes-list > li { margin: 0.55em 0; }
.notes-sub  { list-style: none; margin: 0.5em 0 0.5em 1.4em; padding: 0; }
.notes-sub  > li::before { content: "– "; }
.notes-sub  > li { margin: 0.3em 0; }
.notes-enum { list-style: decimal; margin: 0.5em 0 0.5em 1.8em; padding: 0; }
.notes-enum > li { margin: 0.3em 0; }
.proof { margin: 0.6em 0 0.8em 2em; color: #333; font-size: 0.92em; }
.note  { margin: 0.6em 0 0.8em 2em; color: #555; font-style: italic; font-size: 0.92em; }
.label-dfn, .label-thm, .label-lem, .label-prp, .label-cor,
.label-exa, .label-rmk, .label-ntn { font-weight: bold; }
.label-warn { font-weight: bold; color: #c00; }
.key-star   { color: #b06000; font-weight: bold; }
.munkres-ref { font-size: 0.82em; color: #777; }
</style>


<h3>(\S5) Cartesian products</h3><ul class="notes-list"><li><span class="label-dfn">Def.</span>&nbsp; <em>Indexing function</em> for $\cA$: a surjection $f\colon J\to\cA$;
      write $A_\alpha=f(\alpha)$, family $\{A_\alpha\}_{\alpha\in J}$.
      Not assumed injective: $A_\alpha=A_\beta$ is allowed for $\alpha\neq\beta$.
</li><li><span class="label-ntn">Notation.</span>&nbsp; $\bigcap_{\alpha\in J}A_\alpha$, $\bigcup_{\alpha\in J}A_\alpha$;
      finite case $A_1\cap\cdots\cap A_n$.
</li><li><span class="label-dfn">Def.</span>&nbsp; $n$-tuple $=$ function $x\colon\{1,\dots,n\}\to X$, written $(x_1,\dots,x_n)$;
      \(\prod_{i=1}^{n}A_i\); \; $X^n$.
</li><li><span class="label-dfn">Def.</span>&nbsp; sequence $=$ function $x\colon\NN\to X$, written $(x_i)_{i=1}^{\infty}$
      (also called an <em>$\omega$-tuple</em>);
      \;$\prod_{i=1}^{\infty}A_i=A_1\times A_2\times\cdots$;\; $X^\omega$.
</li><li><span class="key-star">★</span>&nbsp;<span class="label-dfn">Def.</span>&nbsp; General product. $J$-tuple $=$ function $x\colon J\to X$, $x_\alpha=x(\alpha)$.
  \[
    \prod_{\alpha\in J}A_\alpha
      =\Bigl\{\,x\colon J\to\bigcup_{\alpha\in J}A_\alpha \ \Bigm|\ x(\alpha)\in A_\alpha\ \forall\alpha\,\Bigr\},
    \qquad X^J=\prod_{\alpha\in J}X .
  \]
<div class="note"><strong><em>Note.</em></strong>&ensp;Stress: a point of an infinite product is a <em>function</em>. Everything about product
topologies later reads more easily from this description.</div>
</li></ul><h3>(\S6) Finite sets</h3><ul class="notes-list"><li><span class="label-dfn">Def.</span>&nbsp; Section of $\NN$: $\{1,2,\dots,n\}$; for $n=0$ this is $\emptyset$.
</li><li><span class="label-lem">Lem.</span>&nbsp; $\{1,\dots,m\}\hookrightarrow\{1,\dots,n\}$ injective $\imp m\le n$.
<div class="proof"><strong><em>Proof.</em></strong>&ensp;Induction on $n$: delete $f(m)=k$, use a bijection $\{1,\dots,n\}-\{k\}\to\{1,\dots,n-1\}$.</div>
</li><li><span class="label-cor">Cor.</span>&nbsp; Hence there is <em>no</em> injective $\{1,\dots,m\}\to\{1,\dots,n\}$ when $m>n$.
      (Pigeonhole.)
</li><li><span class="label-prp">Prop.</span>&nbsp; A bijection $\{1,\dots,m\}\to\{1,\dots,n\}$ forces $m=n$.
      <div class="proof"><strong><em>Proof.</em></strong>&ensp;Apply the lemma to $f$ and to $f^{-1}$.</div>
</li><li><span class="label-cor">Cor.</span>&nbsp; Hence there is <em>no</em> bijection $\{1,\dots,m\}\to\{1,\dots,n\}$ when $m\neq n$.
</li><li><span class="label-dfn">Def.</span>&nbsp; $A$ is <em>finite of cardinality $n$</em> if there is a bijection $A\to\{1,\dots,n\}$.
      Cardinality is well defined.
      <span class="label-exa">Ex.</span>&nbsp; $\emptyset$ has cardinality $0$; singletons have cardinality $1$.
</li><li><span class="label-lem">Lem.</span>&nbsp; $A\subset\{1,\dots,n\}$ is finite, of cardinality $\le n$;
      if $A\subsetneq\{1,\dots,n\}$ the cardinality is $<n$.
</li><li><span class="key-star">★</span>&nbsp;<span class="label-thm">Thm.</span>&nbsp; A finite set admits no bijection with a proper subset of itself.
</li><li><span class="label-cor">Cor.</span>&nbsp; $\NN$ is not finite: $f(x)=x+1$ is a bijection of $\NN$ with the proper subset
      $\NN-\{1\}$.
</li><li><span class="label-cor">Cor.</span>&nbsp; Any subset $B$ of a finite set $A$ is finite; if $B\subsetneq A$ then
      $\mathrm{card}(B)<\mathrm{card}(A)$.
</li><li><span class="label-prp">Prop.</span>&nbsp; TFAE: (1) $A$ finite; (2) some $\{1,\dots,n\}\twoheadrightarrow A$;
      (3) some $A\hookrightarrow\{1,\dots,n\}$.
<div class="proof"><strong><em>Proof.</em></strong>&ensp;$(2)\imp(3)$: send $x$ to $\min g^{-1}(x)$.</div>
</li><li><span class="label-prp">Prop.</span>&nbsp; Finite unions and finite products of finite sets are finite.
</li></ul>
