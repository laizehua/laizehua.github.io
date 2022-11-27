---
title: "Simpler Grassmannian optimization"
collection: publications
permalink: /publications/2020-09-28-simpler-Grassmannian/
excerpt: 'A simpler model for optimization on Grassmannian manifolds. A follow-up paper deals with the flag manifolds.'
date: 2020-09-28
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2009.13502.pdf'
citation: 'Lai, Zehua, Lek-Heng Lim, and Ke Ye. &quot;Simpler Grassmannian optimization.&quot; arXiv preprint arXiv:2009.13502 (2020).'
---
Abstract:

There are two widely used models for the Grassmannian $\text{Gr}(k,n)$, as the set of equivalence classes of orthogonal matrices $\text{O}(n)/\bigl(\text{O}(k) \times \text{O}(n-k)\bigr)$, and as the set of trace-$k$ projection matrices $\{P \in \mathbb{R}^{n \times n} : P^\top = P = P^2,\; \text{tr}(P) = k\}$. The former, standard in manifold optimization, has the downside of relying on equivalence classes but working with orthogonal matrices is generally good numerical practice. The latter, widely adopted in coding theory and probability, uses actual matrices (as opposed to equivalence classes) but working with projection matrices is numerically unstable. We present an alternative that has both advantages and suffers from neither of the disadvantages; by representing $k$-dimensional subspaces as symmetric orthogonal matrices of trace $2k-n$, we obtain
$$
\text{Gr}(k,n) \cong \{Q \in \text{O}(n) : Q^\top = Q, \; \text{tr}(Q) = 2k -n\}.
$$
As with the other two models, we show that differential geometric objects and operations --- tangent vector, metric, normal vector, exponential map, geodesic, parallel transport, gradient, Hessian, etc --- have closed-form analytic expressions that are computable with standard numerical linear algebra. In the proposed model, these expressions are considerably simpler, a result of representing $\text{Gr}(k,n)$ as a linear section of a compact matrix Lie group $\text{O}(n)$, and can be computed with at most one \textsc{qr} decomposition and one exponential of a special skew-symmetric matrix that takes only $O\bigl(nk(n-k)\bigr)$ time. In particular, we completely avoid eigen- and singular value decompositions in our steepest descent, conjugate gradient, quasi-Newton, and Newton methods for the Grassmannian. Another important feature of these algorithms, particularly evident in steepest descent and Newton method, is that they exhibit clear signs of numerical stability; various measures of errors consistently reduce to the order of machine precision throughout extensive numerical experiments.
