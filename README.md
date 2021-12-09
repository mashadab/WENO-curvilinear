# WENO-curvilinear
This repository encloses Mathematica codes used in the paper [1] on Fifth order finite volume Weighted essentially non-oscillatory scheme in orthogonally-curvilinear coordinates.

The two Mathematica codes are as follows:
1. Weight derivation: For uniform grids in cartesian, cylindrical, and spherical coordinates
2. Modified von-Neumann stability analysis (as performed in [2])

<p align="center">
<img src="./Cover_photos/Cover1.jpeg" height="370">
  <img src="./Cover_photos/Cover2.jpeg" height="370">
</p>
Figure : Schematic showing gravity-driven infiltration in a soil with porosity $ \phi $ decay with depth. The colors blue, brown, white refer to water, soil and gas respectively. A fully saturated region $ \Omega(t) $ develops within an otherwise unsaturated domain. The saturated-unsaturated region boundary $ \partial \Omega (t) $ has a boundary condition of water-gas pressure equivalence. The saturated region expands with time as the boundary $ \partial \Omega (t) $ moves in outward direction.

Please cite paper [1], if using/extending the codes/work.

References:
1. Shadab, M.A., Balsara, D., Shyy, W. and Xu, K., 2019. Fifth order finite volume WENO in general orthogonally-curvilinear coordinates. Computers & Fluids (article in press). Link: https://doi.org/10.1016/j.compfluid.2019.06.031
2. Liu, H. and Jiao, X., 2016. WLS-ENO: Weighted-least-squares based essentially non-oscillatory schemes for finite volume methods on unstructured meshes. Journal of Computational Physics, 314, pp.749-773. Link: https://www.sciencedirect.com/science/article/pii/S0021999116001911 
