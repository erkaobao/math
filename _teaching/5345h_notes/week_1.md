---
layout: archive
title: "MATH 5345H — Week 1: Sets, Functions, and Foundations"
permalink: /teaching/5345h_notes/week_1
author_profile: false
---

<p><a href="https://erkaobao.github.io/math/teaching/2026_fall_5345h_lecture_notes">&#8592; Back to Lecture Notes</a></p>

<p><em>Topic: Course overview and proof writing; sets, functions, relations, and the standard number systems (§§1–4)</em></p>


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


<h2>Introduction</h2><ul class="notes-list"><li><strong>What topology is.</strong> From Greek <em>topos</em> (place) and <em>logos</em>
      (discourse, reason): the study of continuous functions, also called <em>maps</em>.
</li><li><strong>The problem.</strong> To make sense of “$f\colon X\to Y$ is continuous” we need extra
      data: continuity says that if $x,y\in X$ are <em>close</em>, then $f(x),f(y)$ are close.
      So $X$ and $Y$ each need a notion of closeness.
</li><li><strong>First answer: metrics.</strong> Assign a distance $d(x,y)$; call $x,y$ close when
      $d(x,y)$ is small. This gives a <em>metric space</em> $(X,d)$.
<div class="note"><strong><em>Note.</em></strong>&ensp;A bare set carries no information about two elements beyond whether they are equal.
A metric gives it a shape — which is why we then say <em>space</em> rather than set, and
<em>point</em> rather than element.</div>
</li><li><strong>Why that is not enough.</strong> Metric spaces are special. <em>Pointwise convergence</em>
      of real functions ($f_n\to g$ iff $f_n(t)\to g(t)$ for each $t$) is a useful notion of
      closeness, but no metric on the set of real functions expresses it.
</li><li><span class="key-star">★</span>&nbsp;<strong>Second answer: open sets.</strong> Instead of distances between points, specify which
      subsets $U\subset X$ are <em>open</em>. Read this as:
  <ul class="notes-sub"><li>if $x$ lies in $U$ and $U$ is open, then every $y$ sufficiently close to $x$ also
        lies in $U$.
  </li></ul>
  The collection of all open subsets is the <em>topology</em> $\cT$ on $X$.
</li><li><strong>Consequence for the course.</strong> This approach handles not just elements and
      functions but subsets and collections of subsets — hence we begin with a summary of
      set theory.
</li><li><span class="key-star">★</span>&nbsp;<strong>The payoff.</strong> For topological spaces the definition of continuity is simply:
  <ul class="notes-sub"><li>for each open $V\subset Y$, the preimage $f^{-1}(V)$ is open in $X$.
  </li></ul>
  Compare the $(\varepsilon,\delta)$ definition for metric spaces: for each $x\in X$ and each
  $\varepsilon>0$ there is $\delta>0$ such that $d(x,y)<\delta$ implies
  $d(f(x),f(y))<\varepsilon$.
</li><li><strong>On the abstraction.</strong> The definition of a topological space looks harder than the
      subsequent definition of a continuous map. Same pattern as linear algebra: “$f$ is
      linear if $f(\lambda x+\mu y)=\lambda f(x)+\mu f(y)$” is simple, but presupposes the
      abstract definition of a real vector space, which in turn presupposes the nine-odd field
      axioms for $\RR$.
<div class="note"><strong><em>Note.</em></strong>&ensp;Moral: axiomatisations of the most fundamental objects are general enough to be hard to
grasp at once. It is the <em>relations</em> between them — continuous maps, linear
transformations — that are concrete. Say this early; it defuses a lot of anxiety.</div>
</li><li><strong>Programme.</strong> After spaces and maps we study the properties such spaces may have:
  <ul class="notes-sub"><li><em>connected</em> — not a disjoint union of subspaces;
  </li><li><em>compact</em> — not too many open subsets globally;
  </li><li><em>Hausdorff</em> — enough open subsets locally.
  </li></ul>
  Then the consequences: general forms of the intermediate value theorem, existence of maximal
  values, uniqueness of limits, and more.
</li><li><span class="label-ntn">Notation.</span>&nbsp; These notes follow J. R. Munkres, <em>Topology</em>; the $\S$-signs refer to
      sections of that book. Course MAT3500/4500, University of Oslo.
</li></ul><p><strong>Where this leads (worth 5 minutes at the first lecture).</strong></p><ul class="notes-list"><li><strong>Classification of surfaces.</strong> Two facts determine a connected compact
      $2$-manifold up to topological equivalence: whether it can be oriented, and how many
      handles it has. The number of handles is the <em>genus</em> $g$:
      sphere $g=0$, torus $g=1$, two-handled surface $g=2$.
</li><li><strong>Gauss–Bonnet</strong> — local geometry against global topology. For a surface $F$ with
      a Riemannian metric,
  \[ \int_F K\,dA \;=\; 2\pi\cdot\chi, \qquad \chi=2-2g. \]
  Check on the sphere of radius $r$: curvature $1/r^2$ everywhere, area $4\pi r^2$, product
  $4\pi=2\pi\cdot2$, and indeed $\chi(S^2)=2$. <span class="munkres-ref">[Mk course MAT4510]</span>
</li><li><strong>Topology and rational points.</strong> For curves over $\CX$:
      $x^2+y^2=1$ is a sphere and has infinitely many rational solutions;
      $x^5+y^2=1$ has genus $2$ and only finitely many.
      Conjectured by Mordell, proved by Faltings (1983): a rationally defined algebraic curve
      of genus $>1$ has only finitely many rational points.
<div class="note"><strong><em>Note.</em></strong>&ensp;A topological condition forcing an arithmetic conclusion. Good advertisement for the
subject. <span class="munkres-ref">[Mk courses in algebraic geometry]</span></div>
</li></ul><h2>Set Theory and Logic</h2><h3>(\S1) Fundamental concepts</h3><ul class="notes-list"><li><span class="label-ntn">Notation.</span>&nbsp; $x\in A$, $x\notin A$.  
      $D=\{0,1,\dots,9\}$,\; $P=\{n\in\NN\mid n\text{ prime}\}$,\; $S=\{n^2\mid n\in\NN\}$.
</li><li><span class="label-warn">Caution.</span>&nbsp; $x\neq\{x\}$.   $\emptyset=\{\,\}$ has no elements.
</li><li><span class="label-dfn">Def.</span>&nbsp; $A\subset B$ iff $(x\in A)\imp(x\in B)$.  
      $A=B$ iff $A\subset B$ and $B\subset A$.  
      $A\subsetneq B$: proper.
</li><li><span class="label-dfn">Def.</span>&nbsp; $A\cap B=\{x\mid x\in A\text{ and }x\in B\}$,  
      $A\cup B=\{x\mid x\in A\text{ or }x\in B\}$ (inclusive or).
</li><li><strong>Distributive laws.</strong>
      \(A\cap(B\cup C)=(A\cap B)\cup(A\cap C)\),  
      \(A\cup(B\cap C)=(A\cup B)\cap(A\cup C)\).
</li><li><span class="label-dfn">Def.</span>&nbsp; $A-B=\{x\in A\mid x\notin B\}$ — the complement of $B$ in $A$.
</li><li><span class="key-star">★</span>&nbsp;<strong>De Morgan.</strong>
      \(A-(B\cup C)=(A-B)\cap(A-C)\),  
      \(A-(B\cap C)=(A-B)\cup(A-C)\).
<div class="note"><strong><em>Note.</em></strong>&ensp;Used constantly later: it is what converts the union/intersection axioms for open sets
into the intersection/union statements for closed sets.</div>
</li><li><span class="label-ntn">Notation.</span>&nbsp; Informal listings such as $P=\{2,3,5,\dots\}$ and $S=\{1,4,9,\dots\}$ are used when
      the pattern is clear from context.
</li><li><span class="label-dfn">Def.</span>&nbsp; A set whose elements are sets is called a <em>collection</em> (or family),
      written $\cA,\cB,\dots$
      For a given $A$, the <em>power set</em> is $\Pow(A)=\{B\mid B\subset A\}$.
      E.g. $\Pow(\{a,b\})=\{\emptyset,\{a\},\{b\},\{a,b\}\}$, with four elements.
</li><li><span class="label-exa">Ex.</span>&nbsp; <strong>(Students and courses — a collection to keep in mind.)</strong>
      $S=\{s\mid s$ a student$\}$, $C=\{c\mid c$ a course$\}$,
      $E_c=\{s\in S\mid s$ enrolled in $c\}$, and $\mathscr{E}=\{E_c\mid c\in C\}$.
      Elements of $\mathscr{E}$ are sets of students.
<div class="note"><strong><em>Note.</em></strong>&ensp;Note $E_c=E_d$ can happen for $c\neq d$ (both empty). Worth pointing out before indexed
families in \S5, where exactly this failure of injectivity is allowed.</div>
</li><li><span class="label-dfn">Def.</span>&nbsp; For a collection $\cA$:
      \(\bigcap_{A\in\cA}A=\{x\mid x\in A\ \forall A\in\cA\}\),  
      \(\bigcup_{A\in\cA}A=\{x\mid x\in A\text{ for some }A\in\cA\}\).
</li><li><span class="label-warn">Caution.</span>&nbsp; $\bigcup_{A\in\emptyset}A=\emptyset$, but $\bigcap_{A\in\emptyset}A$ needs an
      ambient universal set $U$; then it is $U$.
</li><li><span class="label-exa">Ex.</span>&nbsp; With that collection: $\bigcap_{E_c\in\mathscr{E}}E_c$ = students enrolled in
      <em>every</em> course (probably empty); $\bigcup_{E_c\in\mathscr{E}}E_c$ = the active
      students; $S-\bigcup E_c$ = the inactive ones.
</li><li><span class="label-dfn">Def.</span>&nbsp; $A\times B=\{(x,y)\mid x\in A,\ y\in B\}$;  
      $(x,y)=(x’,y’)$ iff $x=x’$ and $y=y’$.
      Distinguish the ordered pair $(x,y)$ from the set $\{x,y\}$.
      (If wanted: define $(x,y)=\{\{x\},\{x,y\}\}$.)
<div class="note"><strong><em>Note.</em></strong>&ensp;$\RR^2=\RR\times\RR$ read as horizontal and vertical coordinates is Descartes’ analytic
geometry, as against Euclid’s synthetic approach.</div>
</li></ul><h3>(\S2) Functions</h3><ul class="notes-list"><li><span class="label-dfn">Def.</span>&nbsp; $f\colon A\to B$: to each $x\in A$ a unique $f(x)\in B$.
      $A$ = domain, $B$ = range (codomain).
</li><li><span class="label-exa">Ex.</span>&nbsp; The rule may be given by a procedure, e.g. for $x\in\NN$
      \[ f(x)=\begin{cases}3x+1 & x\text{ odd}\\ x/2 & x\text{ even,}\end{cases} \]
      but no such assumption is made in general.
</li><li><span class="label-dfn">Def.</span>&nbsp; Graph $\Gamma_f=\{(x,f(x))\}\subset A\times B$.
      Characterised by: for each $x\in A$ exactly one $y$ with $(x,y)\in\Gamma$.
<div class="note"><strong><em>Note.</em></strong>&ensp;So a function may be <em>defined</em> as a triple $(A,B,\Gamma)$ — domain and codomain are
part of the data, not just the rule.</div>
</li><li><span class="label-dfn">Def.</span>&nbsp; Image $f(A)=\{f(x)\mid x\in A\}\subset B$.  
      Restriction $f|S\colon S\to B$.  
      Corestriction $A\to T$, defined only when $f(A)\subset T$.
</li><li><span class="label-dfn">Def.</span>&nbsp; <em>injective</em>: $f(x)=f(y)\imp x=y$.  
      <em>surjective</em>: $f(A)=B$.  
      <em>bijective</em>: both; then $f^{-1}\colon B\to A$ exists, with
      $f^{-1}(y)=x$ exactly when $y=f(x)$.
</li><li><span class="label-rmk">Rmk.</span>&nbsp; $\Gamma_{f^{-1}}=\{(y,x)\in B\times A\mid(x,y)\in\Gamma_f\}$: the graph of $f^{-1}$
      is the graph of $f$ with the two factors interchanged.
</li><li><span class="label-rmk">Rmk.</span>&nbsp; If $f|S$ is injective and $T=f(S)$, the resulting $g\colon S\to T$ is a bijection
      with an inverse $g^{-1}\colon T\to S$, even when $f$ itself is not invertible.
</li><li><span class="label-dfn">Def.</span>&nbsp; $(g\circ f)(x)=g(f(x))$. Unital, associative, <em>not</em> commutative.
      $(g\circ f)^{-1}=f^{-1}\circ g^{-1}$.
</li><li><span class="label-dfn">Def.</span>&nbsp; <em>Inclusion</em> $i\colon S\to A$, $i(x)=x$ for $x\in S$. Not the identity unless
      $S=A$. Then $f\circ i=f|S$.
</li><li><span class="label-rmk">Rmk.</span>&nbsp; Dually, for $T\subset B$ with $f(A)\subset T$ and $j\colon T\to B$ the inclusion,
      the corestriction $g\colon A\to T$ is characterised by $j\circ g=f$.
</li><li><span class="label-dfn">Def.</span>&nbsp; Induced maps on power sets:
      \(f\colon\Pow(A)\to\Pow(B)\),   \(f^{-1}\colon\Pow(B)\to\Pow(A)\).
<div class="note"><strong><em>Note.</em></strong>&ensp;Same symbol, different domain — flag the abuse of notation once and move on.</div>
</li></ul><p><strong>Images vs. preimages</strong> — the asymmetry to put on the board:</p><ul class="notes-list"><li><strong>Images</strong> (only partly well behaved). For $S,T\subset A$:
  <ul class="notes-sub"><li>$S\subset T\imp f(S)\subset f(T)$
  </li><li>$f(S\cup T)=f(S)\cup f(T)$
  </li><li>$f(S\cap T)\subset f(S)\cap f(T)$    — equality if $f$ injective
  </li><li>$f(T)-f(S)\subset f(T-S)$    — equality if $f$ injective
  </li></ul>
</li><li><span class="key-star">★</span>&nbsp;<strong>Preimages</strong> (all four are equalities). For $S,T\subset B$:
  <ul class="notes-sub"><li>$S\subset T\imp f^{-1}(S)\subset f^{-1}(T)$
  </li><li>$f^{-1}(S\cup T)=f^{-1}(S)\cup f^{-1}(T)$
  </li><li>$f^{-1}(S\cap T)=f^{-1}(S)\cap f^{-1}(T)$
  </li><li>$f^{-1}(S-T)=f^{-1}(S)-f^{-1}(T)$
  </li></ul>
</li><li><strong>Round trips.</strong> $S\subset f^{-1}(f(S))$ and $f(f^{-1}(T))\subset T$.
<div class="note"><strong><em>Note.</em></strong>&ensp;This table is the whole reason continuity will be defined by preimages, not images.
Point forward to it now; refer back in \S18.</div>
</li></ul>
