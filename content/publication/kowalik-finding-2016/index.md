+++
title = "On finding rainbow and colorful paths"
date = 2016-05-01
authors = ["Łukasz Kowalik", "Juho Lauri"]
publication_types = ["2"]
abstract = "In the Colorful Path problem we are given a graph $G=(V,E)$ and an arbitrary vertex coloring function $c: V to [k]$. The goal is to find a colorful path, i.e., a path on k vertices, that visits each color. This problem has been introduced in the classical work of Alon et al. (1995) [1], and the authors proposed a dynamic programming algorithm that runs in time $2textasciicircumk ntextasciicircumO(1)$ and uses $O(2textasciicircumk)$ space. Since then the only progress obtained is reducing the space size to a polynomial at the cost of using randomization. In this work we show that a progress in time complexity is unlikely: if Colorful Path can be solved in time $(2-varepsilon)textasciicircumk ntextasciicircumO(1)$, then Set Cover admits a $(2-varepsilon')textasciicircumn (nm)textasciicircumO(1)$-time algorithm. The same applies to other versions of the problem: when edges are colored instead of vertices, or we ask for a walk instead of a path, or when the requested path/walk has specified endpoints.  We study also a second, very related problem. In Rainbowst-Connectivity, we are given a k-edge-colored graph and two vertices s and t. The goal is to decide whether there is a rainbow path between s and t, that is, a path on which no color repeats. In its vertex variant (Rainbow Vertexst-Connectivity) the input graph is k-vertex-colored, and a rainbow path is defined analogously. Uchizawa et al. (2011) [14] show that both variants can be solved in $2textasciicircumk ntextasciicircumO(1)$ time and exponential space. We show that the space size can be reduced to a polynomial, while keeping the same running time. In contrast to the polynomial space algorithm for Colorful Path, our algorithm for finding rainbow paths is deterministic."
featured = false
publication = "*Theoretical Computer Science*"
url_pdf = "https://linkinghub.elsevier.com/retrieve/pii/S030439751600219X"
doi = "10.1016/j.tcs.2016.03.017"
+++

