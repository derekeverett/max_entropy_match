# max_entropy_match



Please see (link forthcoming) for the derivation and description of these methods, and please cite (link forthcoming) if these methods are used in research.

Please see the two jupyter notebooks `Solving_Energy_Bulk.ipynb` and `Solving_Energy_Shear.ipynb` for the numerical methods of constructing the maximum entropy distribution.

The root solvers (just using scipy) are probably still too slow for phenomenology, but with some though and time I believe a full 3 or 4-d root solver could be written in e.g. `c++` that would be fast enough. 

For solving the shear-stress Langrange multipliers, a slow but accurate library called `mpmath` was used to evaluate the triple-series expressions. This is also quite slow, but I'm sure there are faster methods either in python or in e.g. `c++`. 
