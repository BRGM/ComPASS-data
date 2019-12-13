Test cases from:
Xing, F., Masson, R., & Lopez, S. (2017).
Parallel numerical modeling of hybrid-dimensional compositional
non-isothermal Darcy flows in fractured porous media.
Journal of Computational Physics.
https://doi.org/10.1016/j.jcp.2017.05.043

.. code-block:: latex

    @article{Xing2017,
    abstract = {This paper introduces a new discrete fracture model accounting for non-isothermal compositional multiphase Darcy flows and complex networks of fractures with intersecting, immersed and non-immersed fractures. The so called hybrid-dimensional model using a 2D model in the fractures coupled with a 3D model in the matrix is first derived rigorously starting from the equi-dimensional matrix fracture model. Then, it is discretized using a fully implicit time integration combined with the Vertex Approximate Gradient (VAG) finite volume scheme which is adapted to polyhedral meshes and anisotropic heterogeneous media. The fully coupled systems are assembled and solved in parallel using the Single Program Multiple Data (SPMD) paradigm with one layer of ghost cells. This strategy allows for a local assembly of the discrete systems. An efficient preconditioner is implemented to solve the linear systems at each time step and each Newton type iteration of the simulation. The numerical efficiency of our approach is assessed on different meshes, fracture networks, and physical settings in terms of parallel scalability, nonlinear convergence and linear convergence.},
    archivePrefix = {arXiv},
    arxivId = {1612.07501},
    author = {Xing, F. and Masson, R. and Lopez, S.},
    doi = {10.1016/j.jcp.2017.05.043},
    eprint = {1612.07501},
    issn = {10902716},
    journal = {Journal of Computational Physics},
    keywords = {Discrete fracture model,Non-isothermal compositional multiphase hybrid-dimensional Darcy flow model,Parallel algorithm,Polyhedral meshes,Preconditioner,Vertex Approximate Gradient scheme},
    title = {{Parallel numerical modeling of hybrid-dimensional compositional non-isothermal Darcy flows in fractured porous media}},
    year = {2017}
    }
