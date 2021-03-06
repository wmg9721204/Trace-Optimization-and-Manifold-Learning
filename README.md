# Popular Manifold Learning Methods based on Trace Optimization
In the paper <br>
>[2010][E.Kokiopoulou,et al] Trace optimization and eigenproblems in dimension reduction methods <br>
URL: https://onlinelibrary.wiley.com/doi/full/10.1002/nla.743

it is indicated that a lot of popular algorithms of manifold learning methods (linear or nonlinear) including <br>
**(1) PCA (Principal Component Analysis) <br>
(2) MDS (Multidimensional Scaling) <br>
(3) Isomap (Isometric Map) <br>
(4) LLE (Locally Linear Embedding) <br>
(5) Eigen (Laplacian Eigenmap) <br>**
can be expressed as optimization problem of the form <br>
objective function = tr( - ) <br>
subject to orthogonal constraints.

This repository contains a jupyter notebook containing codes that <br>
(1) solve the trace optimization and <br>
(2) implement the manifold learning methods mentioned above. 

For more information, please refer to the details of the paper. 
