# Learning 3D Shape Completion under Weak Supervision

This repository contains paper and code corresponding to:

D. Stutz, A. Geiger. **Learning 3D Shape Completion under Weak Supervision.** International Journal of Computer Vision (2018). [[ArXiv](http://arxiv.org/abs/1805.07290) | [Springer Link](https://link.springer.com/article/10.1007/s11263-018-1126-y)]

Please cite as:

    @article{Stutz2018ARXIV,
        author    = {David Stutz and Andreas Geiger},
        title     = {Learning 3D Shape Completion under Weak Supervision},
        journal   = {International Journal of Computer Vision},
        year      = {2018},
    }

This work is based on our earlier CVPR'18 paper

D. Stutz, A. Geiger. **Learning 3D Shape Completion from Laser Scan Data with Weak Supervision.** IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018.

Also check the [project page](http://davidstutz.de/projects/improved-shape-completion/)
and the repository for our CVPR publication:
[davidstutz/cvpr2018-shape-completion](https://github.com/davidstutz/cvpr2018-shape-completion)

Here, you can find:

* `paper/`: the LaTeX source of the paper, as available on ArXiv.
* `code/`:
    * [davidstutz/aml-improved-shape-completion](https://github.com/davidstutz/aml-improved-shape-completion),
      Torch and C++ implementation of the proposed approach and baselines as well
      as the created benchmarks.
    * [davidstutz/mesh-evaluation](https://github.com/davidstutz/mesh-evaluation),
      C++ implementation of mesh-to-mesh / mesh-to-point distance
      used for evaluation.
    * [davidstutz/bpy-visualization-utils](https://github.com/davidstutz/bpy-visualization-utils),
      Python and Blender (`bpy`) utilities for visualization as shown below.
    * [davidstutz/mesh-fusion](https://github.com/davidstutz/mesh-fusion),
      Python implementation of TSDF fusion used to obtain watertight and simplified
      meshes for our benchmarks.
    * [davidstutz/mesh-voxelization](https://github.com/davidstutz/mesh-voxelization),
      C++ implementation of mesh voxelization for computing occupancy grids
      and signed distance functions from watertight meshes.

![AML.](screenshot.png?raw=true "AML.")
