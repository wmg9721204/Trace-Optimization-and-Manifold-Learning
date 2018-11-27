In the paper **[2010][E.Kokiopoulou,et al] Trace optimization and eigenproblems in dimension reduction methods**, it is indicated that a lot of popular algorithms of manifold learning methods (linear or nonlinear) including <br>
**(1) PCA (Principal Component Analysis) <br>
(2) MDS (Multidimensional Scaling) <br>
(3) Isomap (Isometric Map) <br>
(4) LLE (Locally Linear Embedding) <br>
(5) Eigen (Laplacian Eigenmap) <br>**
can be expressed as optimization problem of the form <br>
objective function = tr( - ) <br>
subject to orthogonal constraints.

This repository contains julia codes that <br>
(1) solves the trace optimization and <br>
(2) implements the manifold learning methods mentioned above. 

Mathematically, the optimization problem is
`$$
\alpha
$$`

