# MAT: Blum's Medial Axis Theorem

This repository contains our preprint concerning an elementary proof of Blum's conjecture that the medial axis transform M(A) of an open bounded subset A of R^n is
homotopy-isomorphic to the subset $A$. This means $M(A)$ encodes all the topology of $A$, all connectivity relations and loop relations, etc.. Lieutier gave a lengthy proof using vector fields and gradient flows, but as part of our research into singularities we believe we have found a more direct proof. This is included in the MAT.pdf file.

In our preprint we look to construct strong deformation retracts of $A$ onto $N(A)$, which is the locus of nondifferentiability of the distance to boundary function. It's well known that $N(A)$ is the closure of $M(A)$ in $A$.
 
Remark. The key topological lemma requires the *continuity* of our max-centre map $x\mapsto m(x)$,  $m: A\to A$. This is key for continuity of the deformation retract. We are *not* satisfied with our proof that $m$ is continuous. Indeed Saul Rodrigues Martin's answer https://mathoverflow.net/questions/413480/is-the-max-centre-map-continuous-for-open-bounded-domains/413527?noredirect=1#comment1060282_413527
proves that $m$ is not necessarily continuous unless we extend replace the medial axis $M(A)$ with the locus of nondifferentiability $N=N(A)$ of the distance-to-boundary.
