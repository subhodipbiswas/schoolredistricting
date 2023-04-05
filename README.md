# Spatial Optimization techniques for School Redistricting

This is the GitHub repository corresponding to the doctoral thesis [Spatial Optimization Techniques for School Redistricting](https://vtechworks.lib.vt.edu/handle/10919/110433). In this thesis, optimization techniques have been developed for solving the school redistricitng problem. The techniques include 
- [clustering algorithm](https://doi.org/10.1609/aaai.v34i09.7058) called GeoKMeans,
- [local-search framework](https://doi.org/10.1145/3347146.3359377) called REGAL,
- [memetic algorithm](https://doi.org/10.1145/3397536.3422265) called SPATIAL,
- [MCMC-based algorithms](http://arxiv.org/abs/2206.03703), and
- exact optimization methods.


The developement of these algorithms happened at different stages and used data for different school years. An attempt is made to consolidate the different algorithms for the most latest school year, i.e., 2020-21. As a result of this ongoing effort, we have presently made the following codes available:

- REGAL and SPATIAL at [SpatialPartitioning](https://github.com/subhodipbiswas/SpatialPartitioning)
- MCMC techniques at [SamplingbasedSchoolRedistricting](https://github.com/subhodipbiswas/SamplingbasedSchoolRedistricting)
- We will release the code for the clustering algorithm and the exact optimization method soon.

We encourage the research community to extend these algorithms to other similar redistricting problems

## Citation
If you use this data/code for your work, please consider citing the following article:
```
@inproceedings{biswas2020incorporating,
  title={Incorporating domain knowledge into Memetic Algorithms for solving Spatial Optimization problems},
  author={Biswas, Subhodip and Chen, Fanglan and Chen, Zhiqian and Lu, Chang-Tien and Ramakrishnan, Naren},
  booktitle={Proceedings of the 28th International Conference on Advances in Geographic Information Systems},
  pages={25--35},
  year={2020}
}

@article{biswas2022memetic,
author = {Biswas, Subhodip and Chen, Fanglan and Chen, Zhiqian and Lu, Chang-Tien and Ramakrishnan, Naren},
title = {Memetic Algorithms for Spatial Partitioning Problems},
year = {2023},
issue_date = {March 2023},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {9},
number = {1},
issn = {2374-0353},
url = {https://doi.org/10.1145/3544779},
doi = {10.1145/3544779},
month = {jan},
articleno = {5},
numpages = {31},
keywords = {redistricting, Metaheuristic, spatial optimization}
}
```
## Note
Should you have queries, please reach out to me at subhodipbiswas@vt.edu
