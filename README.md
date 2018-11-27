In _[2010][E.Kokiopoulou,et al] Trace optimization and eigenproblems in dimension reduction methods_, 
it is indicated that a lot of popular algorithms of manifold learning methods (linear or nonlinear) including 
(1) PCA (Principal Component Analysis)
(2) MDS (Multidimensional Scaling)
(3) Isomap (Isometric Map)
(4) LLE (Locally Linear Embedding)
(5) Eigen (Laplacian Eigenmap)
can be expressed as optimization problem of the form
objective function = tr(**)
subject to orthogonal constraints.

This repository contains julia codes that implements this observation and the manifold learning methods mentioned above. 

