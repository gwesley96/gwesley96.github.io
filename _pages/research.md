---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
---

{% include base_path %}

<style>
  .page__content ul {
    margin-top: 0.4rem;
    padding-left: 1.25rem;
  }
  .page__content li {
    margin-bottom: 0.6rem;
    line-height: 1.55;
  }
  .page__content .abstract-toggle {
    display: inline;
    white-space: nowrap;
    cursor: pointer;
    font-weight: 600;
    color: inherit;
    margin-left: 0.25rem;
  }
  .page__content .abstract-body {
    display: block;
    margin: 0.35rem 0 0 1.25rem;
    padding: 0.2rem 0 0 0.75rem;
    border-left: 2px solid rgba(0, 0, 0, 0.15);
    line-height: 1.5;
    text-indent: 0;
    list-style: none;
  }
</style>

<script>
function toggleAbstract(el) {
  const body = el.nextElementSibling;
  const expanded = el.getAttribute('aria-expanded') === 'true';
  el.setAttribute('aria-expanded', String(!expanded));
  body.hidden = expanded;
  el.textContent = expanded ? '▸ Abstract' : '▾ Abstract';
}
</script>

<h2 id="preprints">Preprints</h2>

<ul>
  <li>Greyson Wesley. Unitary TQFTs, unitary disk-like \(n\)-categories, and higher Hilbert spaces. 2026. <a href="https://arxiv.org/abs/2609.19713">arXiv:2609.19713</a> <span class="abstract-toggle" aria-expanded="false" onclick="toggleAbstract(this)">▸ Abstract</span>
    <span class="abstract-body" hidden>We introduce the notion of a unitary disk-like $n$-category, which is a disk-like $n$-category equipped with a reflection structure and a sphere trace inducing positive-definite pairings. Since a finite unitary disk-like $n$-category is defined to be the local field data of a fully extended $(n + 1)\text{D}$ unitary TQFT, we propose a complete finite unitary disk-like $n$-category as the definition of a finite $(n + 1)$-Hilbert space for all $n$. For $n = 1$ and $n = 2$ we verify this proposal, proving that complete finite unitary disk-like 1- and 2-categories are isometrically equivalent to finite 2- and 3-Hilbert spaces respectively, and that these equivalences are functorial. For $n = 1$ we recover a unitary refinement of Schommer-Pries’ classification of oriented $(1 + 1)\text{D}$ TQFTs in terms of $\mathrm{H}^*$-Morita equivalence classes of $\mathrm{H}^*$-algebras, and for $n = 2$ we categorify this to classify oriented $(2 + 1)\text{D}$ unitary TQFTs by $\mathrm{H}^*$-Morita equivalence classes of $\mathrm{H}^*$-multifusion categories. Along the way, we investigate fully incomplete 3-Hilbert spaces, prove a strictification result for pivotal dagger 2-categories, and define functors and higher transformations between disk-like $n$-categories.</span></li>

  <li>Giovanni Ferrer, Brett Hungar, David Penneys, and Greyson Wesley. Orthonormal bases for higher Hilbert spaces. 2026. <a href="http://arxiv.org/abs/2608.11358">arXiv:2608.11358</a> <span class="abstract-toggle" aria-expanded="false" onclick="toggleAbstract(this)">▸ Abstract</span>
    <span class="abstract-body" hidden>In our previous article <a href="https://arxiv.org/abs/2410.05120">arXiv:2410.05120</a>, we introduced the notion of a finite dimensional 3-Hilbert space, categorifying Baez’s 2-Hilbert spaces. In this article, by further categorifying Baez’s higher linear algebra, we provide useful tools for working with 3-Hilbert spaces, including generalized scalar multiplication, orthonormal bases, and unitary adjoints for operators. We use these tools to endow the $\mathrm{C}^*$-3-category of 3-Hilbert spaces with a self-enrichment. We prove a Unitary Yoneda Lemma/Riesz Representation Theorem for 3-Hilbert spaces: the Yoneda embedding is an isometric equivalence. Finally, we define a unitary version of the Deligne product on 3-Hilbert spaces and prove that it satisfies an isometric version of the folding trick.</span></li>
</ul>

<h2 id="undergraduate-work">Undergraduate work</h2>

<ul>
  <li>C. Johnson, X. Lin, X. Liu, G. Wesley, and S. Zhou. The inverse characteristic polynomial problem for graphs over finite fields. 2023. In <em>Recent Research in Polynomials</em>, edited by F. Ozger, chap. 6. <span class="abstract-toggle" aria-expanded="false" onclick="toggleAbstract(this)">▸ Abstract</span>
    <span class="abstract-body" hidden>Let $\mathbb{F}$ be a finite field, and let $G$ be a graph on $n$ vertices. We study the possible characteristic polynomials that may be realized by matrices $A$ over a finite field such that the graph of $A$ is $G$. We focus mainly on the case $G$ is a tree $T$, not only because trees are computationally simpler, but also because the theory of eigenvalue multiplicities is much better understood for trees than it is for general graphs. We demonstrate the applications to this problem by branch duplication and the recently developed geometric Parter–Wiener, etc. theory. We end with a list of several conjectures which should pave the way for future study.</span></li>

  <li>Greyson Wesley. Counting monic polynomials without prescribed factors over $\mathbb{F}_q$. 2022. Short note. <span class="abstract-toggle" aria-expanded="false" onclick="toggleAbstract(this)">▸ Abstract</span>
    <span class="abstract-body" hidden>In this short note we use the symbolic method to provide a brief proof for the ordinary generating function of the combinatorial class of monic polynomials over $\mathbb{F}_q$ not divisible by anything from a given set of monic irreducibles.</span></li>

  <li>C. R. Johnson, G. Tsoukalas, G. Wesley, and Z. Zhao. $k$-NIM trees: a characterization and enumeration. 2022. <a href="https://arxiv.org/abs/2208.05450">arXiv:2208.05450</a> <span class="abstract-toggle" aria-expanded="false" onclick="toggleAbstract(this)">▸ Abstract</span>
    <span class="abstract-body" hidden>Among those real symmetric matrices whose graph is a given tree $T$, the maximum multiplicity $M(T)$ that can be attained by an eigenvalue is known to be the path cover number of $T$. We say that a tree is $k$-NIM if, whenever an eigenvalue attains a multiplicity of $k-1$ less than the maximum multiplicity, all other multiplicities are 1. 1-NIM trees are known as NIM trees, and a characterization for NIM trees is already known. Here we provide a graph-theoretic characterization for $k$-NIM trees for each $k \geq 1$, as well as count them. It follows from the characterization that $k$-NIM trees exist on $n$ vertices only when $k=1,2,3$. In case $k=3$, the only 3-NIM trees are simple stars.</span></li>

  <li>David Galvin, Greyson Wesley, and Bailee Zacovic. Enumerating threshold graphs and some related graph classes. <em>J. Integer Sequences</em> 25 (2022), Article 22.2.7. <a href="https://cs.uwaterloo.ca/journals/JIS/VOL25/Galvin/galvin2.html">Journal Article</a> <span class="abstract-toggle" aria-expanded="false" onclick="toggleAbstract(this)">▸ Abstract</span> <span class="abstract-body" hidden>We give combinatorial proofs of some enumeration formulas involving labelled threshold, quasi-threshold, loop-threshold and quasi-loop-threshold graphs. In each case we count by number of vertices and number of components. For threshold graphs, we also count by number of dominating vertices, and for loop-threshold graphs we also count by number of looped dominating vertices. We also obtain an analog of the Frobenius formula (connecting Eulerian numbers and Stirling numbers of the second kind) in the context of labelled threshold graphs.</span></li>
</ul>
