---
layout: page
title: Software
# subtitle: Why you'd want to go on a date with me
---

### MuMMI Framework
MuMMI (Multiscale Machine-Learned Modeling Infrastructure) was developed to create ML-driven, autonomous, multiscale simulation ensembles to study the interactions of RAS proteins and RAS-RAF protein complexes with lipid plasma membranes. This framework was developed as part of the Pilot2 project of the Joint Design of Advanced Computing Solutions for Cancer funded jointly by the <a href="https://www.energy.gov" target=_blank>Department of Energy (DOE)</a> and the <a href="https://www.cancer.gov" target=_blank>National Cancer Institute (NCI)</a>.

I co-led the development of MuMMI, focusing on developing the workflow, AI models, and integration of the various simulation codes.
* Code: <a href="https://github.com/mummi-framework" target=_blank>github</a>.
* Papers:  <a href="http://dx.doi.org/10.1145/3295500.3356197" target=_blank>SC 2019</a> and <a href="http://dx.doi.org/10.1145/3458817.3476210" target=_blank>SC 2021</a>.
* Technologies:
  - Python
  - TensorFlow, Keras, Horovod
  - GPU-enabled MD simulation Tools, CUDA
  - HPC resource managers: Flux
  - Hardware: NVIDIA Tesla GPUs, IBM PowerPC, Sierra and Summit supercomputers

### Adaptive Multilinear Meshes (AMM)
AMM represents a new paradigm datastructure for volumetric data by combining **novel spatial hierarchies** with **mixed-precision representation** to offer new, **lossless data reduction** strategies. AMM is built upon a new "adaptive octree" datastructure that is more flexible than the standard octree, providing reduced branching in the hiearchy, effectively reducing the data footprint. AMM can also automatially identify and reduce the number of bits needed to represent the data, further reducing the in-memory size of the data.

I developed this award-winning technology as part of my research at LLNL.
* Code: <a href="https://github.com/LLNL/AMM" target=_blank>github</a>.
* Paper:  <a href="https://doi.org/10.1109/TVCG.2022.3165392" target=_blank>TVCG 2022</a>.
* Technologies:
  - C++ 17, VTK, Cmake
  - Wavelet transforms, Octrees


### MemSurfer
MemSurfer is an efficient and versatile tool to compute and analyze **membrane surfaces** found in a wide variety of large-scale molecular simulations. MemSurfer works independent of the type of simulation, directly on the **3D point coordinates**, and can handle a variety of membranes as well as atomic simulations. MemSurfer provides many in-built analysis tasks, such as computing the membrane curvature, density and normals of lipids, and area per lipid. More importantly, MemSurfer provides a simple-to-use Python API that may be easily used/extended to perform other types of analysis.
* Code: <a href="https://github.com/LLNL/MemSurfer" target=_blank>github</a>.
* Paper:  <a href="https://doi.org/10.1002/jcc.25181" target=_blank>JCC 2018</a>.
* Technologies:
  - Python, C++, Cmake, VTK, CGAL, boost, eigen
  - Computational topology, Computational geometry, Surface reconstruction


### TopoMS
TopoMS is a computational tool for **topological analysis** of molecular and condensed matter systems, including the computation of atomic volumes and charges through the quantum theory of atoms in molecules (also known as Bader analysis), as well as the complete molecular graph. With roots in techniques from computational topology, and using a **shared-memory parallel approach**, TopoMS provides scalable, numerically robust, and topologically consistent analysis.
* Code: <a href="https://github.com/LLNL/TopoMS" target=_blank>github</a>.
* Paper:  <a href="https://doi.org/10.1002/jcc.25181" target=_blank>JCC 2018</a>.
* Technologies:
  - C++, Qt, Cmake, VTK, CGAL
  - Computational topology


### DynIm
The DynIm framework offers an almost-real-time sampling of data through a dynamic
importance scheme. DynIm uses <a href="https://github.com/facebookresearch/faiss" target=_blank>FAISS</a> as a vector database to store encoded data
and perform approximate nearest neighbor searches.
  * Code: <a href="https://github.com/LLNL/dynim" target=_blank>github</a>.
  * Paper:  <a href="https://doi.org/10.1038/s42256-021-00327-w" target=_blank>Nature Machine Intelligence 2021</a>.
  * Technologies:
    - Python, Numpy, FAISS

### CallFlow
CallFlow is an interactive visual analysis tool for exploring performance profiles of application codes. CallFlow provides a high-level overview of Calling Context Trees (CCTs) together with semantic refinement operations to progressively explore them.
CallFlow also facilitates analysis of ensembles of application runs. The development
of CallFlow was led by my student, SP Kesavan.
* Code: <a href="https://github.com/LLNL/CallFlow" target=_blank>github</a>.
* Papers: <a href="https://doi.org/10.1109/TVCG.2021.3129414" target=_blank>TVCG 2021</a> and <a href="https://doi.org/10.1109/TVCG.2019.2953746" target=_blank>TVCG 2019</a>.
* Technologies:
  - Python, Pandas

### Earlier open-source research codes
* <a href="https://github.com/bhatiaharsh/RobustCriticalPointDetection" target=_blank>Numerically robust critical point detection</a> in vector fields defined on simplicial meshes using the notion of <a href="https://dl.acm.org/doi/pdf/10.1145/77635.77639" target=_blank>*Simulation of Simplicity (SOS)*</a> [C++, Qt].
* <a href="https://github.com/bhatiaharsh/TrajectoryExplorer" target=_blank>Visualization and animation of atom trajectories</a> in simulated systems, with focus on the representation of uncertainty in the data [C++, Qt].
* <a href="https://github.com/bhatiaharsh/JacobiSetComputation" target=_blank>Computation of Jacobi Sets</a> of scalar functions as part of topological analysis and simplification of data [C++].
* <a href="https://github.com/bhatiaharsh/naturalHHD" target=_blank>Computation of the Natural Helmholtz-Hodge decomposition</a> of 2D and 3D vector fields [Python, C++].
