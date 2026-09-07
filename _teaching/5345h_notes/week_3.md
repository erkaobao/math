---
layout: archive
title: "MATH 5345H — Week 3: Topological Spaces and Bases"
permalink: /teaching/5345h_notes/week_3
author_profile: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<p><em>Topic: Topological spaces and standard examples (§12); bases, subbases, and comparison of topologies (§13)</em></p>


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


<h2>Topological Spaces and Continuous Functions</h2><h3>(\S12) Topological spaces</h3><ul class="notes-list"><li><span class="key-star">★</span>&nbsp;<span class="label-dfn">Def.</span>&nbsp; A <em>topology</em> on a set $X$ is a collection $\cT$ of subsets with
  <ol class="notes-enum"><li>$\emptyset\in\cT$ and $X\in\cT$;
  </li><li>$\{U_\alpha\}_{\alpha\in J}\subset\cT\ \imp\ \bigcup_{\alpha\in J}U_\alpha\in\cT$
         (<em>arbitrary</em> unions)
  </li><li>$U_1,\dots,U_n\in\cT\ \imp\ U_1\cap\cdots\cap U_n\in\cT$
         (<em>finite</em> intersections)
  </li></ol>
  $(X,\cT)$ is a <em>topological space</em>; the $U\in\cT$ are the <em>open</em> sets.
<div class="note"><strong><em>Note.</em></strong>&ensp;For (3) it is enough to check $n=2$; induct. The asymmetry between (2) and (3) is the whole
subject — infinite intersections of open sets need not be open: $\bigcap_n(-1/n,1/n)=\{0\}$.</div>
</li><li><span class="label-dfn">Def.</span>&nbsp; <em>Discrete</em> $\Tdisc=\Pow(X)$ (every subset open).  
      <em>Trivial</em> $\Ttriv=\{\emptyset,X\}$.
</li><li><span class="label-exa">Ex.</span>&nbsp; $X=\{a,b\}$: exactly four topologies —
      $\Ttriv$, \; $\cT_a=\{\emptyset,\{a\},X\}$, \; $\cT_b=\{\emptyset,\{b\},X\}$, \; $\Tdisc$.
      The middle two are the <em>Sierpiński</em> topologies.
<div class="note"><strong><em>Note.</em></strong>&ensp;In $(X,\cT_a)$: $a$ is separated from $b$, but every open set containing $b$ contains $a$.
So $a$ is “arbitrarily close” to $b$ without $b$ being close to $a$. No metric does this.</div>
</li><li><span class="label-exa">Ex.</span>&nbsp; $X=\{a,b,c\}$: there are $29$ topologies. Nine of them, the rest obtained by
      permuting $a,b,c$:
  <ul class="notes-sub"><li>$\{\emptyset,X\}$
  </li><li>$\{\emptyset,\{a\},X\}$
  </li><li>$\{\emptyset,\{a,b\},X\}$
  </li><li>$\{\emptyset,\{a\},\{a,b\},X\}$
  </li><li>$\{\emptyset,\{a,b\},\{c\},X\}$
  </li><li>$\{\emptyset,\{a\},\{b\},\{a,b\},X\}$
  </li><li>$\{\emptyset,\{a\},\{a,b\},\{a,c\},X\}$
  </li><li>$\{\emptyset,\{a\},\{c\},\{a,b\},\{a,c\},X\}$
  </li><li>$\Pow(X)$, the discrete topology (8 elements)
  </li></ul>
</li><li><span class="label-exa">Ex.</span>&nbsp; <em>Not</em> topologies on $\{a,b,c\}$:
      $\{\{a\},\{c\},\{a,b\},\{a,c\}\}$ (misses $\emptyset,X$);
      $\{\emptyset,\{a\},\{b\},X\}$ (no union);
      $\{\emptyset,\{a,b\},\{a,c\},X\}$ (no intersection).
</li><li><span class="label-dfn">Def.</span>&nbsp; $\cT$ is <em>coarser</em> than $\cT’$ ($\cT’$ <em>finer</em>) if $\cT\subset\cT’$.
      Always $\Ttriv\subset\cT\subset\Tdisc$.
<div class="note"><strong><em>Note.</em></strong>&ensp;A partial order, not a total one: neither Sierpiński topology refines the other.</div>
</li><li><span class="label-dfn">Def.</span>&nbsp; <em>Cofinite</em> topology: $\Tcof=\{U\subset X\mid X-U\text{ finite}\}\cup\{\emptyset\}$.
      It is a topology.
<div class="proof"><strong><em>Proof.</em></strong>&ensp;(2): if some $U_\beta\neq\emptyset$ then $X-\bigcup U_\alpha\subset X-U_\beta$ is finite.
(3): De Morgan turns $X-\bigcap U_i$ into a finite union of finite sets.</div>
</li><li><span class="label-rmk">Rmk.</span>&nbsp; $X$ finite $\imp\Tcof=\Tdisc$;\; $X$ infinite $\imp\Tcof\subsetneq\Tdisc$
      (singletons are not cofinite).
      On $\NN$: $\Ttriv\subsetneq\Tcof\subsetneq\Tdisc$.
</li><li><span class="label-dfn">Def.</span>&nbsp; A <em>metric</em> on $X$ is $d\colon X\times X\to\RR$ with
  <ol class="notes-enum"><li>$d(x,y)\ge0$, with $d(x,y)=0\iff x=y$;
  </li><li>$d(x,y)=d(y,x)$;
  </li><li>$d(x,z)\le d(x,y)+d(y,z)$.
  </li></ol>
  $\varepsilon$-ball: $B_d(x,\varepsilon)=\{y\mid d(x,y)<\varepsilon\}$.
</li><li><span class="key-star">★</span>&nbsp;<span class="label-dfn">Def.</span>&nbsp; <em>Metric topology</em> $\cT_d$:
      $U$ open $\iff$ for each $x\in U$ there is $\varepsilon>0$ with $B_d(x,\varepsilon)\subset U$.
      This is a topology.
<div class="proof"><strong><em>Proof.</em></strong>&ensp;(3) is where finiteness enters: take $\varepsilon=\min\{\varepsilon_1,\dots,\varepsilon_n\}>0$.
An infinite family would give $\inf=0$.</div>
</li></ul><h3>(\S13) Basis for a topology</h3><ul class="notes-list"><li><span class="key-star">★</span>&nbsp;<span class="label-dfn">Def.</span>&nbsp; $\cB$, a collection of subsets of $X$, is a <em>basis</em> if
  <ol class="notes-enum"><li>each $x\in X$ lies in some $B\in\cB$;
  </li><li>$x\in B_1\cap B_2$ $\imp$ there is $B_3\in\cB$ with $x\in B_3\subset B_1\cap B_2$.
  </li></ol>
</li><li><span class="label-dfn">Def.</span>&nbsp; Topology <em>generated</em> by $\cB$:
      \(U\in\cT\iff\forall x\in U\ \exists B\in\cB:\ x\in B\subset U.\)
      This is a topology.
</li><li><span class="label-exa">Ex.</span>&nbsp; Open discs in $\RR^2$;\; open rectangles $(a,b)\times(c,d)$;\;
      singletons $\{x\}$ (generating $\Tdisc$).
<div class="proof"><strong><em>Proof.</em></strong>&ensp;For rectangles, $B_1\cap B_2$ is again a basis element or empty — condition (2) is free.
For discs it needs the triangle inequality.</div>
</li><li><span class="label-lem">Lem.</span>&nbsp; Let $\cB$ be a basis for $\cT$. Then (1) each $B\in\cB$ is open;
      (2) every open $U$ is a union of basis elements: $U=\bigcup_{x\in U}B_x$.
<div class="note"><strong><em>Note.</em></strong>&ensp;The gluing trick — assemble local choices $B_x$ into one global object. It recurs
throughout the course; name it now.</div>
</li><li><span class="key-star">★</span>&nbsp;<span class="label-lem">Lem.</span>&nbsp; <strong>(Recognition criterion.)</strong> Let $\cC$ be a collection of open sets in
      $(X,\cT)$ such that for every open $U$ and every $x\in U$ there is $C\in\cC$ with
      $x\in C\subset U$. Then $\cC$ is a basis for $\cT$.
<div class="note"><strong><em>Note.</em></strong>&ensp;The workhorse for identifying bases. Use it for products, subspaces, metric subspaces.</div>
</li><li><span class="key-star">★</span>&nbsp;<span class="label-lem">Lem.</span>&nbsp; <strong>(Comparison.)</strong> $\cB,\cB’$ bases for $\cT,\cT’$. TFAE:
  <ol class="notes-enum"><li>$\cT\subset\cT’$;
  </li><li>for each $B\in\cB$ and $x\in B$ there is $B’\in\cB’$ with $x\in B’\subset B$.
  </li></ol>
</li><li><span class="label-warn">Caution.</span>&nbsp; $\cT\subset\cT’$ does <em>not</em> require $\cB\subset\cB’$ — only that
      $\cB’$ has <em>smaller</em> sets near each point.
</li><li><span class="label-cor">Cor.</span>&nbsp; $\cB$ and $\cB’$ generate the <em>same</em> topology $\iff$ both conditions hold:
      for each $x\in B\in\cB$ there is $B’\in\cB’$ with $x\in B’\subset B$,
      <em>and</em> for each $x\in B’\in\cB’$ there is $B\in\cB$ with $x\in B\subset B’$.
</li><li><span class="label-exa">Ex.</span>&nbsp; Discs and rectangles generate the same topology on $\RR^2$, namely the metric
      topology.
</li><li><span class="label-dfn">Def.</span>&nbsp; Standard topology on $\RR$: basis $\{(a,b)\mid a<b\}$; equals $\cT_d$ for $d(x,y)=|y-x|$.
</li><li><span class="label-dfn">Def.</span>&nbsp; <em>Lower limit</em> topology $\cT_\ell$ on $\RR$: basis $\{[a,b)\mid a<b\}$;
      write $\RR_\ell$.
</li><li><span class="label-lem">Lem.</span>&nbsp; $\cT_d\subsetneq\cT_\ell$.
<div class="proof"><strong><em>Proof.</em></strong>&ensp;$\subset$: given $x\in(a,b)$ take $[x,b)$. Strict: no $(c,d)$ sits inside $[a,b)$ around
$x=a$, since $(c+a)/2$ escapes.</div>
</li><li><span class="label-dfn">Def.</span>&nbsp; A <em>subbasis</em> $\cS$ is a collection of subsets with $\bigcup_{S\in\cS}S=X$.
      Its associated basis is
      $\cB=\{S_1\cap\cdots\cap S_n\mid S_i\in\cS,\ n\ge1\}$;
      the topology generated by $\cS$ is the one generated by $\cB$. Always $\cS\subset\cB\subset\cT$.
<div class="proof"><strong><em>Proof.</em></strong>&ensp;$\cB$ satisfies the basis axioms: (2) holds because $B_1\cap B_2$ is again a finite
intersection of subbasis elements. The bound $n\ge1$ avoids the empty intersection.</div>
</li></ul>
