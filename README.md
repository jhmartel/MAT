# MAT: Blum's Medial Axis Theorem

This repository contains our preprint concerning an elementary proof of Blum's conjecture that the medial axis transform M(A) of an open bounded subset A of R^n is
 homotopy-isomorphic to the subset $A$. This means $M(A)$ encodes all the topology of $A$, all connectivity relations and loop relations, etc.. Lieutier gave a lengthy proof using vector fields and gradient flows, but as part of our research into singularities we believe we have found a more direct proof. This is included in the MAT.pdf file.
 
 Remark. The key topological lemma, called Lemma 5 in the document requires the max-centre map $x\mapsto m(x)$ be continuous map $m: A\to A$. This is key for continuity of the deformation retract. Our proof of Lemma 5 depends on a variational characterization of the max-centre map. Namely m(x) is the argmax for a maximization program of a convex function on a convex domain. This implies the maximum is attained on the boundary of the domain, and indeed varies continuously with respect to variations in the domain and the objective function.
 
 Thus we obtain a direct geometric homotopy-isomorphism for a bounded open subset onto its medial axis.
