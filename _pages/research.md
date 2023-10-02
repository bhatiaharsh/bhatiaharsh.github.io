---
layout: page
title: Research
permalink: /research/
# subtitle: Why you'd want to go on a date with me
---

### Deep Learning

##### >> Scalable build pipeline for Generative AI
At Samsung Research America, I worked on the development of
<a href="https://neonlife.ai" target=_blank>NEONs --- virtual humans</a>, which are
powered by **generative AI** and state-of-the-art **language models**. Here, I led
a sub-team on creating a *scalable*, *automated*, and *reproducible* pipeline for
delivering deployment-ready, GPU-enabled models.

Starting with captured data, this data pipeline entails feature extraction for
**multimodal data** (video, audio, and text), **distributed training** of PyTorch
models, conversion to **TensorRT**, and packaging relevant models for deployment
and delivery. Of special focus was automated versioning and tracking of all input,
output, and intermediate data assets.

##### >> Deep learning and Computer Vision for Cancer Research
At LLNL, As part of the <a href="https://www.energy.gov" target=_blank>DOE</a>-<a href="https://www.cancer.gov" target=_blank>NCI</a> partnership, I worked on developing AI solutions for
facilitating autonomous, multiscale simulations in the context of Cancer research.

Building and utilizing **computer vision** approaches for **multimodal** data
(multichannel images and spatial trajectories), I developed **unsupervised** and
**semi-supervised** techniques to identify similarities between given data samples.
Upon deployment, these approaches are used for **on-demand recommendations**
based on the **real-time analysis** of **streaming data**.

These AI models form the basis of the "novelty sampling" framework that facilitates
the first-of-its-kind multiscale simulations focusing on interactions of RAS-RAF
(certain cancer-inducing proteins) with human cell membranes, and have been deployed
on some of the **largest supercomputers on the planet**.

See news coverage of this ***award-winning work***: <a href="https://www.hpcwire.com/2019/11/04/ai-based-cancer-protein-simulation-is-finalist-for-sc19-best-paper" target=_blank>HPCwire</a>, <a href="https://www.hpcwire.com/off-the-wire/scientists-tap-the-power-of-hpc-in-a-bet-to-understand-cancer-growth" target=_blank>HPCwire</a>, <a href="https://deixismagazine.org/2021/04/targeting-tumors" target=_blank>DEIXIS</a>.

For details, please see
- The <a href="https://doi.org/10.1038/s42256-021-00327-w" target=_blank>Nature Machine Intelligence</a> paper detailing the sampling mechanism that uses a **variational autoencoder**.
- The <a href="https://doi.org/10.1088/2632-2153/ac8523" target=_blank>Machine Learning: Science & Technology</a> paper that describes the **metric learning** approach used for the second generation
of this work.

Also see an opinion article on the topic <a href="https://doi.org/10.1016/j.sbi.2023.102569" target=_blank>The Confluence of Machine Learning and Multiscale Simulations</a>.


##### >> Deep Learning for Plasma Physics
In search of faster solutions to complex scientific problems, data-driven **surrogate
models** are an attractive alternative. <a href="https://doi.org/10.1017/S002237782200085X" target=_blank>This work</a> shows the value of
**variational autoencoders** to capture intricate relationships between the nontrivial
topology of a <a href="https://en.wikipedia.org/wiki/Tokamak" target=_blank>Tokamak reactor</a>
and the various relevant observables, allowing accurate predictions to complement
expensive simulations.


### High-performance Computing

##### >> Large-scale, AI-driven scientific workflows
With increasing reliance on heterogenous architectures in HPC, large monolithic
applications are being replaced by modular simulation codes that are customized
to specific device types. Orchestrating such applications on large supercomputers
requires addressing challenges of scalability, portability, fault-tolerance, and
ease-of-use. In this work, we developed an **arbitrarily-scalable, AI-driven workflow**
for multiscale simulations in computational biology and demonstrated full scaling to
two of the world's largest supercomputers --- *Sierra* and *Summit*,
**utilizing almost 130,000 GPUs simultaneously**.

For details, see
- The <a href="http://dx.doi.org/10.1145/3295500.3356197" target=_blank>introductory paper on MuMMI</a>, which was adjudged the **Best Paper at *Supercomputing 2019*** conference.
- The <a href="http://dx.doi.org/10.1145/3458817.3476210" target=_blank>follow-up MuMMI paper</a> that highlights several new innovations and shows unprecedented scaling.

##### >> Performance profiling of large-scale applications
To ensure judicious use of dollar investment in HPC hardwares and softwares, it is
imperative to profile application codes towards continual improvement in performance.
With my team, I have developed several tools and techniques for visualizing (and sometimes capturing) profiled data to facilitate performance improvements, focusing on **software traces**,
**network interconnects**, **GPU power consumption**, and **CPU--GPU data movements**.

For details, see
- <a href="https://doi.org/10.1109/TVCG.2019.2953746" target=_blank>Visualizing Hierarchical Performance Profiles of Parallel Codes using CallFlow</a>.
- <a href="https://doi.org/10.1109/TVCG.2021.3129414" target=_blank>Scalable Comparative Visualization of Ensembles of Call Graphs</a>.
- <a href="http://dx.doi.org/10.1111/cgf.13442" target=_blank>Interactive Investigation of Traffic Congestion on Fat-Tree Networks Using
  TreeScope</a>.
- <a href="http://dx.doi.org/10.1109/WORKS49585.2019.00009" target=_blank>Comparing GPU Power and Frequency Capping: A Case Study with the MuMMI Workflow</a>.

### Scientific Visualization

##### >> Adaptive data representations
I have developed and contributed to several tools and techniques aimed broadly at
**reducing data footprint, both in-memory and on-disk**. These techniques
combine the two traditional axes of data reduction --- **reducing data precision**
(e.g., compression) and **reducing data resolution** (e.g., spatial hierarchies). See
<a href="https://doi.org/10.1109/TVCG.2018.2864853" target=_blank>TVCG 2018</a>,
<a href="https://doi.org/10.1109/TVCG.2020.3030381" target=_blank>TVCG 2020</a>,
<a href="http://dx.doi.org/10.1109/LDAV53230.2021.00011" target=_blank>LDAV 2021</a>,
<a href="https://doi.org/10.1109/TVCG.2022.3165392" target=_blank>TVCG 2022</a>, and
<a href="https://doi.org/10.1109/TVCG.2023.3260628" target=_blank>TVCG 2023</a> papers.

##### >> Topological analysis of flow fields
I have developed and contributed to several tools and techniques for analyzing and
visualizing vector field data. Flow fields are notoriously difficult to analyze
both at the fundamental level (due to presence of turbulence and dependence on
reference frames) as well as from a computational perspective (sensitive to numerical errors). Broadly, my work focused on
- Developing a new variant of the well-known Helmholtz-Hodge decomposition and
utilizing it for flow analysis with respect to Galilean frames of reference. See
<a href="http://dx.doi.org/10.1109/TVCG.2012.316" target=_blank>TVCG 2013</a>,
<a href="http://dx.doi.org/10.1111/cgf.12358" target=_blank>CGF 2014</a>, and <a href="http://dx.doi.org/10.1109/TVCG.2014.2312012" target=_blank>TVCG 2014</a>,
and <a href="https://doi.org/10.1109/TVCG.2020.2984413" target=_blank>TVCG 2020</a> papers.
- Developing and utilizing techniques for robust detection of singularities in
flow fields. See <a href="http://dx.doi.org/10.1007/978-3-319-04099-8_1" target=_blank>TopoInVis 2013</a>, <a href="http://dx.doi.org/10.1111/cgf.12109" target=_blank>EuroVis 2013</a>, <a href="http://dx.doi.org/10.1109/TVCG.2016.2534538" target=_blank>TVCG 2016</a>, and <a href="http://dx.doi.org/10.1007/978-3-030-43036-8_14" target=_blank>TopoInVis 2020</a> papers.
- Developing a new data structure, "Edge maps", that can replace traditional
approach for trajectory calculation (explicit integration) with mapping from
simplex boundaries in a given domain mesh. See
<a href="http://dx.doi.org/10.1109/PACIFICVIS.2011.5742375" target=_blank>Pacific Vis 2011</a>, <a href="http://dx.doi.org/10.1007/978-3-642-23175-9_10" target=_blank>TopoInVis 2012</a>, <a href="http://dx.doi.org/10.1109/TVCG.2011.265" target=_blank>TVCG 2012</a>, and <a href="http://dx.doi.org/10.1111/j.1467-8659.2012.03087.x" target=_blank>EuroVis 2012</a> papers.


### Scientific Applications

I have developed and contributed to several tools and techniques aimed broadly at
exploring scientific data, focusing on different applications. See the list below.

- Proceedings of National Academy of Sciences (PNAS): <a href="https://doi.org/10.1073/pnas.2113297119" target=_blank>2022</a>.
- Journal of Chemical Theory & Computation: <a href="https://doi.org/10.1021/acs.jctc.2c01018" target=_blank>2022</a>, <a href="https://doi.org/10.1021/acs.jctc.9b00453" target=_blank>2019</a>.
- Biophysics Journal: <a href="https://doi.org/10.1016/j.bpj.2022.06.035" target=_blank>2022</a>, <a href="https://doi.org/10.1016/j.bpj.2017.10.017" target=_blank>2017</a>.
- The Journal of Physical Chemistry: <a href="https://doi.org/10.1021/acs.jpcb.0c03368" target=_blank>2020</a>, <a href="http://dx.doi.org/10.1021/acs.jpcc.7b02006" target=_blank>2017</a>.
- The Journal of Computational Chemistry:
<a href="https://doi.org/10.1002/jcc.25181" target=_blank>2018</a>.
- Computer Graphics Forum:
<a href="http://dx.doi.org/10.1111/cgf.14304" target=_blank>2021</a>.
- IEEE Pacific Visualization Symposium:
<a href="http://dx.doi.org/10.1109/PACIFICVIS.2016.7465259" target=_blank>2016</a>.
