# MAT: Blum's Medial Axis Theorem

This repository contains our preprint concerning an elementary proof of Blum's conjecture that the medial axis transform M(A) of an open bounded subset A of R^n is
 homotopy-isomorphic to the subset $A$. This means $M(A)$ encodes all the topology of $A$, all connectivity relations and loop relations, etc.. Lieutier gave a lengthy proof using vector fields and gradient flows, but as part of our research into singularities we believe we have found a more direct proof. This is included in the MAT.pdf file.
 
Remark. The key topological lemma, called Lemma 5 in the document requires the max-centre map $x\mapsto m(x)$ be continuous map $m: A\to A$. This is key for continuity of the deformation retract. We are *not* satisfied with our proof that $m$ is continuous. Indeed Saul Rodrigues Martin's answer https://mathoverflow.net/questions/413480/is-the-max-centre-map-continuous-for-open-bounded-domains/413527?noredirect=1#comment1060282_413527
proves that $m$ is not necessarily continuous. His counterexamples indicate that the open subset $A$ needs satisfy some finiteness properties. For example, the max-radius function $r(x)$ needs be uniformly bounded away from zero ($r>const>0$) on the medial axis. 

Our current strategy is this: Saul Martin's examples are not stable with respect to perturbations of the open set $A$. Thus we require a lemma:

Lemma: If $A$ is open bounded subset, then there exists a perturbation $A*$ of $A$ such that $A, A*$ are naturally homotopic, and the max-centre map of $A*$ is continuous.

Remark. Our proof of Lemma 5 depends on a variational characterization of the max-centre map. Namely m(x) is the argmax for a maximization program of a convex function on a convex domain. This implies the maximum is attained on the boundary of the domain. However there appears circumstances where the boundary maximum does not vary continuously with the data (c.f. the mathoverflow counter example). 

N.B. Without a solid proof of Lemma 5 (continuity of max-centre map), we cannot claim to have a direct geometric proof for arbitrary bounded open sets. 
