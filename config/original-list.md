Best-of Atomistic Machine Learning
==================================

###### tags: `chapter`, `ml`, `by-wasmer`, `shared`, `from-2020-12`, `evolving`, `awesome-list`

[up <i class="fa fa-arrow-up"></i> Resources](https://iffmd.fz-juelich.de/WxOZ75GTTHu2MNmnw2u5pA#Resources)

## Disclaimer

This is the orginal best-of-atomistic-machine-learning, copied from [original
location](https://iffmd.fz-juelich.de/68Vn-YcuSWCun3bL_rJHXA#) on 2023-06-11. To
keep track of the porting to the `projects.yaml` file, a checkmark "[X]"
indicate the entry has been ported, an empty checkmarks "[ ]" or its absence
indicate the entry has not been portec yet to `projects.yaml`.

## Description

This chapter concerns machine learning in materials science / atomistic machine learning.

For connected resources lists, go up one level.

This list is in the tradition of [best-of lists](https://github.com/best-of-lists/best-of) and [awesome lists](https://www.google.com/search?&q=awesome+list). The plan is to turn it into a proper community-curated awesome list on GitHub.

These notes try to narrow down recources for the huge and rapidly evolving field of using machine learning in materials science down to references which might be actually be relevant or useful for the master thesis [Development of a surrogate machine learning model for the acceleration of density functional calculations with the Korringa-Kohn-Rostoker method](https://www.fz-juelich.de/SharedDocs/Personen/PGI/PGI-1/EN/Wasmer_J.html?nn=1053144). So the emphasis is on
- practical stuff: libraries and workshops, over theory.
- ML for first-principles methods: DFT over MD.
- ML for physicists: condensed matter and magnetic systems over chemistry

For theory and literature references, see [phd-project-wasmer library](https://www.zotero.org/groups/2583661/phd-project-wasmer/library).

## Changelog

Last additions:
- 2022-09-28: Added various packages seen at Psi-k 2022 conference.

Last complete list refresh (update dates and labels):
- Never.

TODO:
- DOING refresh whole list w.r.t. dates. 75 % done 2022-09.
- DOING homogenize list items format. 75 % done 2022-09.
- TODO clean up or separate the tutorials section.
- TODO move to github.
- TODO turn into a best-of list using [this template](https://github.com/best-of-lists/best-of#contribution), or awesome-list using [this template](https://github.com/jthegedus/awesome-list-template).
- TODO automatic badges for github starts, repo activity etc, maybe sorting according to that.

## Table of contents

[TOC]

## Tags

[tags: software-related](https://iffmd.fz-juelich.de/gxsOkPXATd-dR6r48ZFEiQ#Tags)

[tags: atomistic simulation](https://iffmd.fz-juelich.de/0-NbOz2yRqa1mvHD3RtTTQ#Tags)

[tags: general machine learning](https://iffmd.fz-juelich.de/VkNGn9ziRPSbzx45SHTwEQ#Tags)

tags: atomistic machine learning

| tag     | meaning                               | connected  |
| ------- | ------------------------------------- | ---------- |
| #ACE    | atomic cluster expansion              | #SBFV      |
| #AML    | atomistic #ML                         | #ML        |
| #CBFV   | composition-based #FV / #rep          | #FV #rep   |
| #CSP    | crystal structure prediction          |            |
| #MI     | materials informatics                 |            |
| #ML-DFT | ML-enabled #DFT                       | #ML-ESM    |
| #ML-ESM | ML-enabled #ESM                       | #ESM       |
| #MLIP   | machine-learned interatomic potential | #MD #MLP   |
| #MLP    | machine-learned interatomic potential | #MD        |
| #SA-GPR | symmetry-adapted #GPR                 | #GPR #SBFV |
| #SBFV   | structure-based #FV / #rep            | #FV #rep   |

Notes:

- #MD: most mled-potential literature is about learning interatomic potentials for molecular dynamics (size scale too large), or if for electronic structure, then mostly for molecules (non-#per systems). And as such, often only conceptually interesting but not applicable here.
- #MI: materials informatics is more about data analysis for e.g. structure-property prediction. So while ML in materials science, it is also not directly applicable here, but may be conceptually interesting.

## Other collections

Materials informatics.

- [naganandy/graph-based-deep-learning-literature](https://github.com/naganandy/graph-based-deep-learning-literature). Last update 2022.
- [github topic > tensor-networks](https://github.com/topics/tensor-networks)
- [ncfrey - A Highly Opinionated List of Open-Source Materials Informatics Resources](https://github.com/ncfrey/resources#getting-started). Last update 2022.
- [tilde-lab - Awesome Materials Informatics](https://github.com/tilde-lab/awesome-materials-informatics). Last update 2022.
- [sedaoturak - The Collection of Database and Dataset Resources in Materials Science](https://github.com/sedaoturak/data-resources-for-materials-science). Last update 2022.
- [github topic > materials-informatics](https://github.com/topics/materials-informatics)

## Tools

### General Tools

Tools which combine two or more of any of the following categories.

- [X] **ACEsuit**. A collection of (mostly #Julia) packages built around the Atomic Cluster Expansion (#ACE) representation (#SBFV). Homepages: [ACE Web](https://cortner.github.io/ACEweb/) Online platform of the ACE community. [ACEsuit](https://acesuit.github.io/) Homepage of ACEsuit packages, lists *estabished* packages. [ACEsuit@GitHub](https://github.com/orgs/ACEsuit) Lists *all* ACEsuit packages. By [ICAMS](https://github.com/ICAMS) et al. #ACE
  [X] - **ACE.jl**. "Parameterisation of *Equivariant* Properties of Particle Systems". [Code](https://github.com/ACEsuit/ACE.jl), last update 2022. Development version, as of 2022-09: "ACE.jl is currently being rewritten to account for a variety of generalisations and new features, in particular equivariant properties, automatic differentiation, effective parameter management for general nonlinear models." #Julia
  - [X] **ACE1.jl**. "Atomic Cluster Expansion for Modelling *Invariant* Atomic Properties". [Code](https://github.com/ACEsuit/ACE1.jl), last update 2022. Stable version, split off from ACE.jl. [Documentation](https://acesuit.github.io/ACE1pack.jl). #Julia
  - [X] **ACE1pack.jl**. "ACE1pack provides convenience functionality for the usage of ACE1.jl, ACEfit.jl, JuLIP.jl for fitting interatomic potentials using the ACE model." [Code](https://github.com/ACEsuit/ACE1pack.jl), last update 2022. [Documentation](https://acesuit.github.io/ACE1pack.jl). #Julia
- [X] **DeepKS-kit** (KS = Kohn-Sham). A package for developing machine learning-based chemically accurate energy and density functional models. 2021. [Original publication](https://arxiv.org/abs/2012.14615), 2021. [Code](https://github.com/deepmodeling/deepks-kit), last update 2022. Tags: #dep-PyTorch.
- [X] **cmlkit**. Specify, tune, and evaluate machine learning models for computational chemistry and condensed matter physics. [Original publication](https://www.nature.com/articles/s41524-022-00721-x), 2022. [Homepage](https://marcel.science/repbench/). [Code](https://github.com/sirmarcel/cmlkit), last update 2022. [Tutorial](https://analytics-toolkit.nomad-coe.eu/public/user-redirect/notebooks/tutorials/cmlkit.ipynb). Representations: SOAP, ACSF, MBTR. Models: KRR. Features and limitations, as of 2021: Only allows scalar target properties; sparse features not supported; In-built hyperparameter optimization using `hyperopt`; no documentation except docstrings.
- [X] **Scikit-Matter** aka `skmatter` (Previously Scikit-COSMO aka `skcosmo`). A collection of scikit-learn compatible utilities that implement methods developed in the COSMO laboratory. Scikit-learn extensions for atomistic ML. [Code](https://github.com/lab-cosmo/scikit-matter), last update 2022. By [lab-cosmo](https://github.com/lab-cosmo) et al. #SL #USL #PCovR #KPCovR #FSn #SSn
- [X] **COSMO-tools**. Scripts, jupyter nbs, and general helpful stuff from COSMO by COSMO. Also, LaTeX macros for the [Dirac notation for structural representations (#SBFV) introduced by Ceriotti et al](https://doi.org/10.1021/acs.chemrev.1c00021). [Code](https://github.com/lab-cosmo/cosmo-tools), last update 2021.
- [X] [crystals.ai](https://crystals.ai/): Repository by the [materialsvirtuallab](https://materialsvirtuallab.org/) for pre-trained models, model libraries, and training datasets.
- [X] **MAST-ML** (`mastml`). The  Materials  Simulation  Toolkit  for  Machine  Learning. An automated open source toolkit to accelerate data-driven materials research. 2020. [Original publication](https://www.sciencedirect.com/science/article/abs/pii/S0927025620300355), 2020. [Preprint](https://arxiv.org/abs/1910.06291), 2019. [Code](https://github.com/uw-cmg/MAST-ML), last update 2022. [Docs](https://mastmldocs.readthedocs.io).[Notebooks examples/tutorial](https://github.com/uw-cmg/MAST-ML/tree/master/examples). [youtube video](https://www.youtube.com/watch?v=GpT59maueUA).
- [X] **AMP** (`amp-atomistics`). Atomistic Machine-learning Package. ASE calculator for atomistic machine learning, with descriptors and models. [Original publication](https://www.sciencedirect.com/science/article/pii/S0010465516301266?via%3Dihub), 2016. [Homepage](https://amp.readthedocs.io). [Code](https://bitbucket.org/andrewpeterson/amp/), last update 2022.
- [X] **AMPtorch**. PyTorch implementation of the Atomistic Machine-learning Package (AMP) code. [Code](https://github.com/ulissigroup/amptorch), last update 2022. #dep-PyTorch
- [X] **ASAP** (`asaplib`). Automatic Selection And Prediction tools for materials and molecules. Generate global or atomic descriptors, sparsified kernel ridge regression KRR. Generate materials maps (unsupverised learning) from PCA, sparsified kernel PCA, UMAP, t-SNE, DBSCAN. [Original publication](https://pubs.acs.org/doi/full/10.1021/acs.accounts.0c00403), 2020. [Code](https://github.com/BingqingCheng/ASAP), last update 2021. #USL #viz
- [X] **Automatminer**. Tool for automatically creating complete machine learning pipelines for materials science, including automatic featurization with matminer, feature reduction, and an AutoML backend. Put in a materials dataset, get out a machine that predicts materials properties. [Original publication ](https://www.nature.com/articles/s41524-020-00406-3), 2020. [Code](https://github.com/hackingmaterials/automatminer), last update 2022. [Homepage](https://hackingmaterials.lbl.gov/automatminer/).
- [X] **JARVIS-Tools**. An open-source software package and online platform for data-driven atomistic materials design. 2017-2020. [Homepage](https://jarvis.nist.gov/) (services, documentation).  [Code](https://github.com/usnistgov/jarvis), last update 2022. [example notebooks](https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks). By NIST.
- [X] **maml**. MAterials Machine Learning. Python package that aims to provide useful high-level interfaces that make ML for materials science as easy as possible. descriptors, models. [Original publication](https://doi.org/10.1021/acs.jpca.9b08723), 2020. [Code](https://github.com/materialsvirtuallab/maml), last update 2022. [Homepage](http://maml.ai/).
- [X] **SNAP**. "Spectral neighbor analysis potential". Descriptor for PES, derivate of GAP. Implemented in `maml` package. [Archived separate code](https://github.com/materialsvirtuallab/snap), last update 2020.
- [X] **XenonPy**. Comprehensive set of machine learning tools for molecules and materials informatics. [Original publication](https://pubs.acs.org/doi/10.1021/acscentsci.9b00804), 2019. [Code](https://github.com/yoshida-lab/XenonPy), last update 2022. [Homepage](https://xenonpy.readthedocs.io). The prebuilt docker image contains thousands of pretrained models. #dep-PyTorch
  > XenonPy has a rich set of tools for various materials informatics applications. The descriptor generator class can calculate several types of numeric descriptors from compositional, structure. By using XenonPy’s built-in visualization functions, the relationships between descriptors and target properties can be easily shown in a heatmap.

  > Transfer learning is an important tool for the efficient application of machine learning methods to materials informatics. To facilitate the widespread use of transfer learning, we have developed a comprehensive library of pre-trained models, called XenonPy.MDL. This library provides a simple API that allows users to fetch the models via an HTTP request. For the ease of using the pre-trained models, some useful functions are also provided

  Personal notes:

  - inspired by matminer, uses pytorch. [descriptors](https://xenonpy.readthedocs.io/en/stable/features.html): compositional descriptors are based on chemical element property databases (like eg `mendeleev`). structural descriptors only RDF and OFM.
- [X] **MagPie**. "A Materials-Agnostic Platform for Informatics and Exploration". [Code](https://bitbucket.org/wolverton/magpie), last update 2020. [Original publication](https://www.nature.com/articles/npjcompumats201628), 2016. #stale
  - Personal note: can view XenonPy as a continuation of Magpie.
- [X] **QML** aka `qmlcode`. "A Python Toolkit for Quantum Machine Learning". [Homepage](http://www.qmlcode.org). [Code](https://github.com/qmlcode), last update 2018. Resentations: CM, BOB, Spectrum of London and Axillrod-Teller-Muto potential (SLATM), ACSF, FCHL. Kernels: Wasserstein, Laplacian, Gaussian, linear, Sargan, Matern, PCA. Models: KRR. More for chemistry than materials. By lilienfeld-group. #stale

### General Models

Models which cannot be categorized or combine feature engineering and representation learning approaches.

Terminology: "Traditional ML models" require manual / hand-based representations (featurizers, e.g. #SBFV. Neural network models typically (but not always) manual representation, or they learn the representation themselves / perform representation learning. An analogy in image ML is a CNN learning complex image features itself, as opposed to hand-based feature engineering. A neural network model does not necessarily have to be a deep learning model. In fact, many GCN used in early AML were shallow networks (TODO citation needed - search eg 'deep graph convulation networks').

- [X] **TensorPotential**. Tensorpotential is a TensorFlow based tool for development, fitting ML interatomic potentials from electronic structure calculations data and perform computations using these potentials. [Code](https://github.com/ICAMS/TensorPotential), last update 2022. By [ICAMS](https://github.com/ICAMS) et al. #dep-TensorFlow
- [X] **pacemaker**, aka `python-ace`, `pyace`. Pacemaker is a tool for fitting of interatomic potentials in a general nonlinear Atomic Cluster Expansion (ACE) form. [Original publication](https://journals.aps.org/prmaterials/abstract/10.1103/PhysRevMaterials.6.013804) 2022. [Code](https://github.com/ICAMS/python-ace), last update 2022. [Documentation](https://pacemaker.readthedocs.io). By [ICAMS](https://github.com/ICAMS) et al. Also see, in this list: ACEsuit. #ACE #dep-TensorFlow
  - [ACE Web](https://cortner.github.io/ACEweb/). Online platform of the ACE community.
  - ACE & pacemaker tutorial at PyIron workshop 2022. [Repository](https://github.com/pyiron/potentials-workshop-2022) with all links.
  - ACE & pacemaker tutorial at ML4M workshop 2022, using PACEmaker and TensorPotential. See ml4m22 in this list. Direct links: [Tutorial Colab notebook](https://colab.research.google.com/drive/1avJoULLhrGGPQdLdMlb73vkCe41v7sCW). [Tutorial video recording](https://www.youtube.com/watch?v=P5cfUl1lGp0&ab_channel=ICTPCondensedMatterandStatisticalPhysic).

### Representation engineering - General

Terminology synonyms and connected concepts: representation, descriptor, feature vector, fingerprint. Featurizers / fingerprinters create feature vectors from compositional or structural input data, based on a formal representation / decriptor method. These are then used as input to a ML model. This corresponds to hand-based feature engineering.

- [X] [MatMiner](https://github.com/hackingmaterials/matminer). [paper 2018](https://www.sciencedirect.com/science/article/abs/pii/S0927025618303252?via%3Dihub).
  - [table of matminer featurizers](https://hackingmaterials.lbl.gov/matminer/featurizer_summary.html). very extensive.
  - [matminer tutorial: generating descriptors for machine learning](https://workshop.materialsproject.org/lessons/08_ml_matminer/matminer-notes/#part-2-generating-descriptors-for-machine-learning)

### Representation engineering - Compositional Descriptors

#CBFV

- **Overview of some #CBFV libraries**. [Video](https://www.youtube.com/watch?v=JctWNNdI9Jc), 2021. Discusses packages Jarvis, oliynyk, atom2vec, mat2vec, magpie, elemnet.
- [X] **CBFV**. Featurizer for composition-based featurizers. Supports the following #CBFV schemes: jarvis, magpie, mat2vec, oliynyk (default), onehot, random_200. [Code](https://github.com/kaaiian/CBFV), last update 2021. [Video demonstration](https://www.youtube.com/watch?v=JctWNNdI9Jc&t=1521s). #stale

### Representation engineering - Structural Descriptors

#SBFV

- [X] **Equistore**. Storage format for equivariant atomistic machine learning. [Code](https://github.com/lab-cosmo/equistore), last update 2022. [Documentation](https://lab-cosmo.github.io/equistore). [Tutorial](https://github.com/lab-cosmo/equistore-examples). By [lab-cosmo](https://github.com/lab-cosmo) et al.
- [X] **Rascaline**. Rust/Python Atom-centered density correlations (ACDCs) library. [Original publication](https://aip.scitation.org/doi/abs/10.1063/5.0087042). [Code](https://github.com/Luthaf/rascaline), last update 2022. [Documentation](https://luthaf.fr/rascaline). [Tutorial](https://github.com/lab-cosmo/equistore-examples). By [lab-cosmo](https://github.com/lab-cosmo).
- [X] **LibRascal**. C++/Python descriptor library. [Original publication](https://aip.scitation.org/doi/full/10.1063/5.0044689), 2021. [Benchmark dataset](https://github.com/felixmusil/rascal_benchmarks) used in the original publication. [Code](https://github.com/lab-cosmo/librascal), last update 2022. [Documentation](https://lab-cosmo.github.io/librascal). By [lab-cosmo](https://github.com/lab-cosmo) et al.
- [X] **Nice**. Dimensionality reduction while preserving information content tool for structural representations. 2020. [code](https://github.com/cosmo-epfl/nice). [presentation 2018](https://www.osti.gov/servlets/purl/1582188). [presentation 2015](https://www.lammps.org/workshops/Aug15/PDF/talk_Thompson2.pdf). By [lab-cosmo](https://github.com/lab-cosmo) et al.
- [X] **DScribe**. Python package for transforming atomic structures into fixed-size numerical fingerprints. [homepage](https://singroup.github.io/dscribe). [original paper](https://www.sciencedirect.com/science/article/pii/S0010465519303042). [pypi](https://pypi.org/project/dscribe/). [conda](https://anaconda.org/conda-forge/dscribe). [libraries.io](https://libraries.io/conda/dscribe).
  - application, validation and extensions of DScribe to periodic systems: Onat et al. [Sensitivity and Dimensionality of Atomic Environment Representations used for Machine Learning Interatomic Potentials](https://aip.scitation.org/doi/10.1063/5.0016005). June2020.
  - DScribe workshop 2019: [notebooks](https://github.com/fullmetalfelix/ML-CSC-tutorial), [slides](https://docs.google.com/presentation/d/1iGh3xA6eBwEHR-mBcrsoVkPAdaSf8wWDrLr04F6BQ5U/edit#slide=id.p), [report](https://psi-k.net/young-researchers-workshop-on-machine-learning-for-material-science-2019-report/).
- [X] **milad**. "Moment Invariants Local Atomic Descriptor", which is invertible. [Original publication](https://arxiv.org/abs/2104.09319), 2021. [Code](https://github.com/muhrin/milad/), last update 2021. #stale
- [X] ChemEnv: ChemEnv: a fast and robust coordination environment identification tool. 2018, 2020. URLs: [src](https://github.com/materialsproject/pymatgen/tree/master/pymatgen/analysis/chemenv). [reference](https://journals.iucr.org/b/issues/2020/04/00/lo5066/lo5066.pdf). [tutorial notebook](https://jageo.github.io/jekyll/update/2018/03/01/ChemEnv-Tutorial-online.html). Part of `pymatgen`.

### Representation engineering - Structural Models

- [X] **SA-GPR** aka TENSOAP, SOAPFAST. Symmetry-Adapted Gaussian Process Regression (SA-GPR). [Code](https://github.com/dilkins/TENSOAP), last update 2022. By [lab-cosmo](https://github.com/lab-cosmo) et al.
- [X] **SALTED**. Symmetry-Adapted Learning of Three-dimensional Electron Densities. [Original publication](https://pubs.acs.org/doi/10.1021/acs.jctc.1c00576), 2021. [Code](https://github.com/andreagrisafi/SALTED), last update 2022. By [lab-cosmo](https://github.com/lab-cosmo) et al.
- [X] **QUIP and quippy**, aka `quippy-ase`, `gap_fit` etc. Package with a collection of  machine-learning interatomic potentials (#MLP). Includes the Gaussian Approximation Potential (#GAP) and SOAP. [Homepage](https://libatoms.github.io/QUIP). [Code](https://github.com/libAtoms/QUIP), last update 2022. [Code for GAP](https://github.com/libAtoms/GAP), last update 2022. #GP #GAP #MLP #MD
  - Subsequent publications:
    - [Gaussian Approximation Potentials: a brief tutorial introduction](https://arxiv.org/abs/1502.01366), 2020 (v2). A GAP tutorial using QUIP.
    - [Compressing local atomic neighbourhood descriptors](https://doi.org/10.1038/s41524-022-00847-y), 2022. Implemented in `gap_fit`. [Data & tutorial](https://zenodo.org/record/5793852) for compression of the power spectrum representation.
    - [X] **testing-framework**. "testing of a large number of interatomic potentials for a variety of systems (materials or molecules)". [Code](https://github.com/libAtoms/testing-framework), last update 2022.
- [X] q-pac, formerly known as kQEq. "kQEq is a Python implementation of the kernel Charge Equilibration method. This allows training and using physics-based machine-learning models for predicting charge distributions in molecules and materials." [Original publication](https://iopscience.iop.org/article/10.1088/2632-2153/ac568d), 2022. [Code](https://gitlab.com/jmargraf/kqeq), last update 2022.
  - Recorded talks about kQEq: [at ML4M22 workshop](https://www.youtube.com/watch?v=EiDF8X8YzZI), 2022; [at GdR REST Machine Learning Discussion](https://www.youtube.com/watch?v=i0THgDtm3FU) meeting, 2021. Both by first author, JMargraf.
- [X] [CatLearn](https://github.com/SUNCAT-Center/CatLearn): An environment for atomistic machine learning in Python for applications in catalysis. 2020. also contains featurizers. #GP
- [X] **FLARE**. Fast Learning of Atomistic Rare Events (FLARE) is an open-source Python package for creating fast and accurate atomistic potentials. [Original publication](https://www.nature.com/articles/s41524-020-0283-z), 2020. [Code](https://github.com/mir-group/flare), last update 2022. [Documentation](https://mir-group.github.io/flare/). [Tutorial](https://colab.research.google.com/drive/1Q2NCCQWYQdTW9-e35v1W-mBlWTiQ4zfT).  By [mir-group](https://github.com/mir-group). #AIMD #BI #AL #GP
  - [FLARE-tutorials](https://github.com/mir-group/FLARE-Tutorials).
- [X]**flare++**. Many-body extension of FLARE, using ACE, and Gaussian processes for uncertainty estimation / online active learning. [Original publication](https://arxiv.org/abs/2106.01949), 2021. [Code](https://github.com/mir-group/flare_pp), last update 2022. [Tutorial](https://colab.research.google.com/drive/18_pTcWM19AUiksaRyCgg9BCpVyw744xv).
- [X] **BOSS**. Bayesian Optimization Structure Search (BOSS) is an active machine learning technique for accelerated global exploration of energy and property phase space. [Original publication](https://www.nature.com/articles/s41524-019-0175-2) 2019. [Code](https://gitlab.com/cest-group/boss), last update 2022. [Documentation](https://cest-group.gitlab.io/boss/). By [cest-group](https://gitlab.com/cest-group). #GPR
  - Tutorial at ML4M 2022 workshop. See ml4m22 in this list. Direct links: Tutorial notebooks: [ml4m22 Hans-On Tutorials](https://ml4m.xyz/hands-on-tutorials/) > search Milica Todorović. [Tutorial video recording](https://www.youtube.com/watch?v=oeY6Gez9NOQ&ab_channel=ICTPCondensedMatterandStatisticalPhysics).
- [X] **ML-DFT**. "Machine learning for density functional approximations". Atomic structure -> $V_{ext}$ -> electron density -> total energy. Implementation of paper bogojeskiQuantumChemicalAccuracy2020. [Original publication](https://doi.org/10.1038/s41467-020-19093-1), 2020. [Code](https://github.com/MihailBogojeski/ml-dft), last update 2020. #ML-DFA #KRR #stale

### Representation learning

- [X] **MACE**. "Higher Order Equivariant Message Passing Neural Networks for Fast and Accurate Force Fields". #ACE-insipired #MPNN that reportedly improves on NequIP. [Original publication](https://arxiv.org/abs/2206.07697), 2022. [Code](https://github.com/ACEsuit/mace), last update 2022. See also in this list: ACEsuit. By csanyi-group et al. #dep-PyTorch
  - [Twitter thread about the paper](https://mobile.twitter.com/davkovacs10/status/1537440680561156097)
  - [Recorded talk](https://www.youtube.com/watch?v=k-KawPHC0wE) about MACE by IBatatia at [IPAM workshop](http://www.ipam.ucla.edu/programs/workshops/workshop-iv-monte-carlo-and-machine-learning-approaches-in-quantum-mechanics/?tab=schedule), 2022.
- [X] **e3nn**. "E(3) is the Euclidean group in dimension 3. That is the group of rotations, translations and mirror. e3nn is a pytorch library that aims to create E(3) equivariant neural networks." [Homepage](https://e3nn.org/). [Code](https://github.com/e3nn), last update 2022 (PyTorch and JAX implementations). #dep-PyTorch, #dep-JAX
  - [Tutorial](https://github.com/e3nn/e3nn-tutorial-mrs-fall-2021), 2021. "e3nn tutorial for Materials Research Society Fall Meeting 2021".
- [X] **DGL**. "Deep Graph Library". Major, as of 2022, general Python framwork for building GNNs. [Homepage](https://www.dgl.ai/). [Code](https://github.com/dmlc/dgl), last update 2022. #dep-PyTorch #dep-TensorFlow
  - [GitHub Topics > dgl](https://github.com/topics/dgl)
- [X] **dgl-lifesci**. "Python package for graph neural networks in chemistry and biology". [Implements](https://lifesci.dgl.ai/api/model.zoo.html) SchNet, MPNNs etc. Only for molecules (SMILES). [Code](https://github.com/awslabs/dgl-lifesci), last update 2022.
- [X] **benchmarking-gnns**. "Repository for benchmarking graph neural networks". [Original publication](https://arxiv.org/abs/2003.00982), 2022. [Code](https://github.com/graphdeeplearning/benchmarking-gnns), last update 2022.
- [X] **DeepErwin**. DNN-based VMC to predict wavefunction of molecules at accuracy above CCSD(T). Claims it improves over FermiNet, PauliNet via weight-sharing. [Original publication](https://www.nature.com/articles/s43588-022-00228-x), 2022. [Code](https://github.com/mdsunivie/deeperwin), last update 2022. By PGrohs, PMarquetand et al. #dep-JAX
- [X] **Allegro**. A "strictly local E(3)-equivariant machine-learning interatomic potential". Extension of NequIP. [Original publication](https://arxiv.org/abs/2204.05249), 2022. [Code](https://github.com/mir-group/allegro), last update: 2022. By [mir-group](https://github.com/mir-group). #dep-PyTorch
- [X] **NequIP**. "Neural Equivariant Interatomic Potentials (NequIP), an E(3)-equivariant neural network approach for learning interatomic potentials from ab-initio calculations for molecular dynamics simulations". An #MPNN which reportedly outperforms #ACE linear models. [Original publication](https://www.nature.com/articles/s41467-022-29939-5), 2021. [Code](https://github.com/mir-group/nequip), last update: 2022. By [mir-group](https://github.com/mir-group). #dep-PyTorch
- [X] **M3GNet-DGL**. Reimplementation of MEGNet, M3GNet in [DGL](https://www.dgl.ai/). [Code](https://github.com/materialsvirtuallab/m3gnet-dgl), last update 2022. #dep-PyTorch
- [X] **M3GNet**. [Original publication](https://arxiv.org/abs/2202.02450), 2022. "Materials graph network with 3-body interactions featuring a DFT surrogate crystal relaxer and a state-of-the-art property predictor." [Code](https://github.com/materialsvirtuallab/m3gnet), last update 2022. #dep-TensorFlow
  - [Recorded talk about M3GNet](https://www.youtube.com/watch?v=RiAKIaWY_iM) by Ping Ong at CCMS Summer Institute Lecture 2022.
  - [X] [matterverse.ai](https://matterverse.ai/). Materials database of hypothetical materials built with M3GNet by training a 'universal model' for the complete periodic table on the whole MaterialsProject database.
- [X] **MEGNet**. "Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals". [Original publication](https://doi.org/10.1021/acs.chemmater.9b01294), 2019. [Code](https://github.com/materialsvirtuallab/megnet), last update 2022. #dep-TensorFlow
  - [Tutorial](https://bit.ly/mrs-nequip).
- [X] **gcnn_keras** aka `kgcnn`. "Keras Graph Convolution Neural Networks". Implements SchNet and other physics/chemistry GNN, GCN for Keras. [Original publication](https://www.sciencedirect.com/science/article/pii/S266596382100035X), 2021. [Code](https://github.com/aimat-lab/gcnn_keras), last update 2022. #dep-TensorFlow
- [X] **PANNA**. Properties from Artificial Neural Network Architectures (PANNA) is a package to train and validate all-to-all connected network models for BP and modified-BP type local atomic environment descriptors and atomic potentials. [Code](https://gitlab.com/PANNAdevs/panna), last update 2021. #dep-TensorFlow1 #stale
  - Tutorial at ML4M 2022 workshop. See ML4M in this list. Direct links: [Tutorial Colab notebook](https://bit.ly/ML4M22PANNA). [Tutorial video recording](https://www.youtube.com/watch?v=YhQxtrn0e7E&list=PLYc-eBoIpXTLRPmVi6qPgljHu-Fs9_ptc&index=7).
  - [Article about PANNA by MaX CoE](http://www.max-centre.eu/news/generating-neural-network-potentials) 2021.
- [X] **OpenChem**. "Deep Learning toolkit for Computational Chemistry and Drug Design Research". Only for molecules (SMILES, molecular graphs). [Original publication](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00971), 2021. [Code](https://github.com/Mariewelt/OpenChem), last update 2022. #dep-PyTorch #molecules
- [X] [Libnxc](https://github.com/semodi/libnxc/): library for using machine-learned exchange-correlation functionals for density-functional theory. Compatible with [Libxc](https://tddft.org/programs/libxc/) & PySCF. [paper](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.104.L161109#fulltext). 2021. #Autodiff #dep-PyTorch
- [X] [NeuralXC](https://github.com/semodi/neuralxc): Implementation of a machine learned density functional with Libnxc. [paper](https://www.nature.com/articles/s41467-020-17265-7). 2020.
- [X] **MALA**  (Materials Learning Algorithms).  is a data-driven framework to generate surrogate models of density functional theory calculations based on machine learning. [code](https://github.com/mala-project/mala). Uses SNAP descriptors, ANNs to learn LDOS. [paper](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.104.035120). [video presentation](https://www.youtube.com/watch?v=j8kqVd-b9Yo), [discussion](https://www.youtube.com/watch?v=OCdkOvZUvzo). Last update 2022. #dep-PyTorch
- [X] [CrabNet](https://github.com/anthony-wang/CrabNet): Compositionally-Restricted Attention-Based Network. attention-based neural network architecture for the prediction of inorganic materials properties given access to nothing but each materials' chemical composition. Last update 2022. #dep-PyTorch
- [X] [SchNet, sGDML, COMBO](http://quantum-machine.org/software/) (only SchNet useful for solids). #dep-PyTorch
- [Atomic Energy Network (ænet)](http://ann.atomistic.net/): software package [1–3] for the construction and usage of atomic interaction potentials based on artificial neural networks (ANNs). 2016, 2020.
- [X] [SingleNN](https://github.com/KitchinHUB/SingleNN). Modified BPNN by Kitchin group which [replaces](https://www.youtube.com/watch?v=nKwbpaV8dts&t=1m20s) the one-NN-per-species approach of BPNN with single-NN for all species, but with multiple outputs, one per species. Last update 2020. #stale
- [X] [PiNN](https://github.com/Teoroo-CMC/PiNN). a Python library for building atomic neural networks. Last update 2022. #dep-TensorFlow
- [X] [RuNNer](https://www.uni-goettingen.de/de/560580.html). RuNNer represents the first implementation of [HDNNPs](https://github.com/masayoshi-ogura/HDNNP).
- [X] [SIMPLE-NN](https://github.com/MDIL-SNU/SIMPLE-NN) (SNU Interatomic Machine-learning PotentiaL packagE – version Neural Network). 2020.
- [X] [DeepChem](https://github.com/deepchem/deepchem).

### Unsupervised learning

- [X] **DADApy**. Python package for the characterisation of manifolds in high dimensional spaces. [Original publication](https://arxiv.org/abs/2205.03373) 2022. [Code](https://github.com/sissa-data-science/DADApy), last update 2022. [Documentation](https://dadapy.readthedocs.io/). By [sissa-data-science](https://github.com/sissa-data-science).
  - Tutorial at ML4M 2022 workshop: See ML4M22 in this list. Direct links: Tutorial notebooks: [ML4M Hands-On Tutorials](https://ml4m.xyz/hands-on-tutorials/) > search DADAPy. [Tutorial video recording](https://www.youtube.com/watch?v=BqTmHrb-0vs).
- [X] **Chemiscope**. Graphical tool for the interactive exploration of materials and molecular databases, correlating local and global structural descriptors with the physical properties of the different systems. [Homepage](https://chemiscope.org/). [Code](https://github.com/lab-cosmo/chemiscope), last update 2022. By [lab-cosmo](https://github.com/lab-cosmo) et al. #dimred
- [X] [sketchmap](http://interactive.sketchmap.org/#about): Sketch-map is a non-linear dimensionality reduction algorithm that is particularly well suited for examining high-dimensionality data that is routinely produced in atomistic simulations. [interactive visualizer](http://interactive.sketchmap.org). [paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-017-0192-4). [Code](https://github.com/cosmo-epfl/sketchmap), last update 2020. [interactive visualizer code](https://github.com/sandipde/Interactive-Sketchmap-Visualizer), other name: web dashboard. #dimred #stale

### Crystal structure prediction

- [X] **CSPML**. "Crystal structure prediction with machine learning-based element substitution". [Original publication](https://doi.org/10.1016/j.commatsci.2022.111496), 2022. [Code](https://github.com/minoru938/cspml), last update 2022. #dep-TensorFlow

### Unsorted

- [X] 230609:
  - https://github.com/lanl/alf
  - https://github.com/lanl/hippynn
  - https://github.com/aiqm/torchani
- [X] 230601:
  - https://zenodo.org/record/7967079, via https://twitter.com/lab_COSMO/status/1664164774035243009
- [X] 230531:
  - [X] https://github.com/materialsvirtuallab/matgl
    - multi-GPU PyTorch reimplementation of M3GNet ([via](https://www.youtube.com/watch?v=qEE7cP5Fh18))
- [X] 230530:
  - https://github.com/StefanoSanvitoGroup/MLdensity
  - https://github.com/bfocassio/MLDensity_tutorial
- [X] 230526:
  - https://github.com/atomicarchitects/equiformer
  - https://gitlab.skoltech.ru/shapeev/mlip/
  - https://gitlab.com/ashapeev/mlip-3
  - https://gitlab.com/ivannovikov/interface-lammps-mlip-3/
- [X] 230520:
  - https://github.com/ur-whitelab/exmol
  - https://github.com/kjappelbaum/gptchem
  - https://github.com/whitead/nlcc
- [X] 230506:
  - https://github.com/uf3/uf3
  - https://github.com/rouyang2017/SISSO (new repo location)
  - https://github.com/Luthaf/alchemical-learning
- [X] 230414:
  - https://github.com/foxjas/CSNN
  - https://github.com/peterbjorgensen/DeepDFT
- [X] 230413:
  - https://github.com/mzjb/DeepH-pack
- [X] 230411:
  - https://github.com/masashitsubaki/QuantumDeepField_molecule
  - https://github.com/llnl/graphite
  - https://huggingface.co/DeepChem
- [X] 230410:
  - https://www.fhi.mpg.de/1004948/software
- [X] 230404:
  - https://github.com/sirmarcel/gknet-archive
  - https://github.com/sirmarcel/glp
  - https://github.com/thorben-frank/mlff (SO3krates)
  - https://gitlab.mpcdf.mpg.de/klai/decaf
  - https://github.com/FitSNAP/FitSNAP
  - https://github.com/hyllios/CGAT
  - https://github.com/andy90/SCFNN
  - SISSO++
    - https://gitlab.com/sissopp_developers/sissopp
    - https://joss.theoj.org/papers/10.21105/joss.03960
- [X] 230403:
  - https://github.com/IntelLabs/matsciml
  - https://github.com/dppant/magnetism-prediction
  - https://github.com/hgheiberger/quantum-structure-ml
- [X] 230319:
  - https://github.com/zhuligs/fplib
  - https://github.com/pfnet-research/charge_transfer_nnp
  - https://github.com/MMunibas/PhysNet
  - https://github.com/capoe/benchml
    - https://github.com/BingqingCheng/linear-regression-benchmarks
  - https://github.com/capoe/soapxx
  - https://gitlab.com/jmargraf/kdf
    - https://doi.org/10.1038/s41467-020-20471-y
- [X] 230302:
  - http://mlatom.com/
- [X] 230215:
  - https://github.com/openkim/kliff
  - https://github.com/MaterSim/PyXtal_FF
- [X] 230129:
  - [X] add agox https://mldft.com/book/booklet/2/2291/, https://gitlab.com/agox/agox
  - [X] add https://github.com/ziatdinovmax/gpax
- [ ] 230128:
  - [ ] TODO add stuff saved in various places as 'add to best-of-aml' (telegram, link dump, etc.)
  - [X] add [nfp](https://github.com/NREL/nfp), [nfp tutorial](https://github.com/WardLT/applied-ai-for-materials/tree/main/molecular-property-prediction/message-passing-networks),
  - [X] add aimat-lab [3DSC](https://github.com/aimat-lab/3DSC).
- [X] 221003:
  - add SchNet, SchNOrb, DimeNet, DimeNet++, GemNet
    - reimplementation https://github.com/learningmatter-mit/NeuralForceField
  - add DeepMD-kit (see linfeng zhang gscholar), DeepDensity (see Zotero)
  - add `se3-transformer` from MWelling paper "SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks"
  - https://github.com/CompRhys/aviary . Includes Wren (Wyckoff representation network), from ML4M22 workshop, now also on ArXiV. #dep-PyTorch
- [X] 220927:
  - https://github.com/CompPhysVienna/n2p2
  - CrysXPP from Psi-k22 conference notes, also CGCNN and all / at lest some of the other **many** GCN libraries, see Zotero > tags GCN, review.

## Tutorials

### Miscellaneous

- **Tutorial review papers**. Go to Johannes Wasmer's Zotero library [phd-project-wasmer](https://www.zotero.org/groups/2583661/phd-project-wasmer). In the tags window (left lower corner), filter for the tag 'tuorial'.
- **Swiss Equivariant Learning Workshop**. 2022.
  - [SELW Workshop Schedule](https://sites.google.com/mit.edu/swiss-equivariant-learning/schedule). Contains recordings and tutorials notebooks. Subjects: Equivariant models, data storage, tensor products, MPNN, NequIP, PyTorch.
- **Free online book 'Deep Learning for Molecules and Materials'**. 2022. With hands-on GNN model building using TensorFlow and JAX.
  - [https://dmol.pub](https://dmol.pub). Book homepage.
- **ML4M Young Researchers' Workshop on Machine Learning for Materials** aka ml4m22. 2022.
  - [ml4m22 Workshop Homepage](https://ml4m.xyz/). Separate workshop homepage. See 'Hans-On Tutorials' and 'Recorded Talks' for Colab notebooks and video recordings of all tutorial sessions.
  - [ml4m22 Playlist on YouTube](https://www.youtube.com/playlist?list=PLYc-eBoIpXTLRPmVi6qPgljHu-Fs9_ptc). Video recordings of all lectures and tutorial sessions.
  - [ml4m22 Entry @ICTP](https://indico.ictp.it/event/9786). 'Program Overview' contains `.mp4` recordings of all talks.
  - [ml4m22 Entry @CECAM Events](https://www.cecam.org/workshop-details/1150)
- **GdR REST - Discussion meeting on Machine Learning**. 2021.
  - GdR REST = Groupement de Recherche (CNRS research cluster) REncontres de Spectroscopie Theorique.
  - [Homepage](http://gdr-rest.polytechnique.fr/Discussion_Meeting_Machine_Learning) with programme.
  - [YouTube playlist of recorded talks](https://www.youtube.com/playlist?list=PLD59gCifE4d8_tuAjKXFiy75kVcngxTzP).
- **lab-cosmo/kernel-tutorials**. A set of utilities and pedagogic notebooks for the use of linear and kernel methods in atomistic modeling. [Code](https://github.com/lab-cosmo/kernel-tutorials), last update 2021.
- [wholetale.org example tales](https://wholetale.org/). Example tales: Informatics-aided bandgap engineering for solar material. Predicting the Properties of Inorganic Materials with Machine Learning. Whole Tale is basically a JupyterHub with lets you share complete projects including data.
- [Big Data and Machine Learning for Chemistry - EPFL](https://bdmlc2021.epfl.ch/). 2021. Hands-on tutorial [notebooks](https://github.com/lcmd-epfl/BDML4Chem).
- [CMU SciML Webinar Series](https://www.cmu.edu/aced/sciML.html). 2021 ongoing.
- [anthony-wang/BestPractices](https://github.com/anthony-wang/BestPractices): Things that you should (and should not) do in your Materials Informatics research. Last update 2021. By wang, persson, kauwe, sparks etc.  [publication](https://pubs.acs.org/doi/10.1021/acs.chemmater.0c01907).
- [The Hitchhiker's Guide to Condensed Matter and Statistical Physics: Machine Learning for Condensed Matter](http://indico.ictp.it/event/9471/). Lecture series by ICTP. [youtube playlist](https://www.youtube.com/playlist?list=PLYc-eBoIpXTKSVBB2nUH6ezrMbT727Cka). Jan2021.
- [kaai kauwe @github](https://github.com/kaaiian?tab=repositories) ml for matsci repos, like
  - [best practices](https://github.com/kaaiian/BestPractices) hings that you should (and should not) do in your Materials Informatics research. 2020.
  - [youtube](https://www.youtube.com/watch?v=WhBg-mC0ChQ&list=PLS2b5v1ZHxl98iZEZsRRHdocprn3zf6vy&index=27): Machine Learning Materials Properties with Python. 2020.
- colab notebook by [Sherif Abbas](https://scholar.google.com/citations?user=NhT7vZIAAAAJ), undated, no reference: [Machine learning for material science](https://colab.research.google.com/drive/1p6ORktVuni6dhGLB70WM_PLbdPvrDh_N#scrollTo=nN1j9xzP_O6U) (copy in my Drive): Materials Project > Crystals > Structures > Descriptors > Models: RF, Xgboost. Follow-up: [Predicting the bandgap of crystals using simple atom-based descriptors](https://colab.research.google.com/drive/1aUNFlIa-pailaSyCTR_p8gRiPFUljZ9h#scrollTo=u7jAD2ZXYkHT) (copy in Drive): better crystal descriptors.

### FAIR-DI, FAIRmat, NOMAD

- [Nomad Virtual Tutorial Series](https://th.fhi-berlin.mpg.de/meetings/nomad-tutorials/index.php?n=Meeting.Home). Started 2020, ongoing. Topics: Archive, Artificial Intelligence Toolkit, Workflows, Optimade, ...

Online course on Big Data and Artificial Intelligence in Materials Sciences 2020/2021

Main links:
- [Course Homepage](https://www.nomad-coe.eu/course-on-big-data-and-artificial-intelligence)
- [Lecture materials](https://www.nomad-coe.eu/events/course-on-big-data-and-artificial-intelligence/lecture-materials)
- [Artificial Intelligence Toolkit - Workshop](https://nomad-lab.eu/AITutorialsWorkshop)


### MaterialsProject

- [The Materials Project Workshop - Machine Learning with MatMiner](https://workshop.materialsproject.org/lessons/08_ml_matminer/matminer-notes/)
  - [2019 video](https://www.youtube.com/watch?v=1DQg6if8Zb0)
  - [2020 video](https://www.youtube.com/watch?v=AwrIK4rW6mU)

### AFLOWlib

- [aflow-school 2020](http://www.aflowlib.org/aflow-school/) -> search 'machine learning'

### materialsvirtuallab

NANO181/281 - Data Science in Materials Science 2022

- [Lecture materials](https://github.com/materialsvirtuallab/nano281)
- [YouTube playlist](https://www.youtube.com/playlist?list=PLzGGfTpqE6yq8B028qutvAmCysRyjaT1A)

NANO281 Data Science in Materials Science 2020

- [youtube lecture videos](https://www.youtube.com/playlist?list=PLzGGfTpqE6yoct83uKY9xH6U7wOPTIMRQ)
- [github lecture materials](https://github.com/materialsvirtuallab/nano281)

matgenb

- [Materials Virtual Lab - matgenb](http://matgenb.materialsvirtuallab.org/): collection of Jupyter notebooks that demonstrate the utilization of open-source codes for the study of materials science. pymatgen, atomate, custodian, fireworks. [Code](https://github.com/materialsvirtuallab/matgenb), last update 2022.

### nanohub

Introduction to Machine Learning for Materials Science 2020

- [youtube lecture videos](https://www.youtube.com/playlist?list=PLUDGrMBDVGZlmFW1kbmq9NI2cMs2eCRON)
- [nanohub learning module](https://nanohub.org/tools/intromllab)

### IPAM

#### Machine Learning for Physics and the Physics of Learning 2019

- [Machine Learning for Physics and the Physics of Learning Tutorials](http://www.ipam.ucla.edu/programs/workshops/machine-learning-for-physics-and-the-physics-of-learning-tutorials/?tab=schedule)
- [Machine Learning for Physics and the Physics of Learning Seminar series](https://www.ipam.ucla.edu/programs/long-programs/machine-learning-for-physics-and-the-physics-of-learning/?tab=seminar-series)
Workshops:
- [Workshop I: From Passive to Active: Generative and Reinforcement Learning with Physics](http://www.ipam.ucla.edu/programs/workshops/workshop-i-from-passive-to-active-generative-and-reinforcement-learning-with-physics/?tab=schedule)
  - [Coarse graining autoencoders and evolutionary learning of atomistic potentials](http://www.ipam.ucla.edu/abstract/?tid=16099&pcode=MLPWS1)
- [Workshop II: Interpretable Learning in Physical Sciences](http://www.ipam.ucla.edu/programs/workshops/workshop-ii-interpretable-learning-in-physical-sciences/?tab=schedule)
- [Workshop III: Validation and Guarantees in Learning Physical Models: from Patterns to Governing Equations to Laws of Nature](http://www.ipam.ucla.edu/programs/workshops/workshop-iii-validation-and-guarantees-in-learning-physical-models-from-patterns-to-governing-equations-to-laws-of-nature/?tab=schedule)
- [Workshop IV: Using Physical Insights for Machine Learning](http://www.ipam.ucla.edu/programs/workshops/workshop-iv-using-physical-insights-for-machine-learning/?tab=schedule)
  - [Machine learning for atomic and molecular simulations Michele Ceriotti](http://www.ipam.ucla.edu/abstract/?tid=15817&pcode=MLPWS4)
  - [Representation and regression problems for molecular structure and dynamics Gabor Csanyi](http://www.ipam.ucla.edu/abstract/?tid=15837&pcode=MLPWS4)

## Unsorted

- 230506:
  - https://github.com/rhennig/EMA6938 notebooks for course on AML for materials
- 210413: AAAI-MLPS 2020 & 2021 presentations: AAAI 2021 Spring Symposium on Combining Artificial Intelligence and Machine Learning with Physics Sciences:
  - homepages: [aaai-mplps 2021](https://sites.google.com/view/aaai-mlps/), [aaai-mlps 2020](https://sites.google.com/view/aaai-mlps/aaai-mlps-2020/).
  - youtube videos: [aaai-mlps playlists](https://www.youtube.com/channel/UCvb7Il2_YzOJe6cKKw0Dt5g/playlists)
  - interesting presentations:
    - [Learning Potentials of Quantum Systems using Deep Neural Networks](https://www.youtube.com/watch?v=07wzW1YdPm4)
    - [Combining Programmable Potentials and Neural Networks for Materials Problems](https://www.youtube.com/watch?v=yMuAxNvsnuM)
    - [Toward Geometrical Robustness with Hybrid DL and Differential Invariants Theory](https://www.youtube.com/watch?v=8D3EAq5vjvc)
    - [Learning Physics-guided Neural Networks with Competing Physics Loss: Solving Eigenvalue Problems](https://www.youtube.com/watch?v=6yRHvCn0Y04)
    - [Graph-Informed Neural Networks](https://www.youtube.com/watch?v=ywRuK1QlU9Q)
- 210331: links around DScribe:
  - singroup/MatID "python package for identifying and analyzing atomistic systems based on their structure. MatID is designed to help researchers in the automated analysis and labeling of atomistic datasets.". [homepage](https://singroup.github.io/matid/). seems similar to [kovacik's `structure_analyzer.py`](https://github.com/JuDFTteam/aiida-jutools/tree/master/aiida_jutools) (e.g., wyckoff positions)
- 210216: from Materials Informatics JVLMD Team Meeting 16.02.2021 with bluegel, wortmann, kostja, kovacik, chand, hilgers, divanova, wasmer. Links from Kostja:
  - [Hierarchical structures of amorphous solidscharacterized by persistent homology](https://www.pnas.org/content/pnas/113/26/7035.full.pdf) by Nishiura et al. "This article proposes a topological method that extracts hierarchi-cal structures of various amorphous solids.". Kostja: could be used also for crystalline solids!
  - Blatov / ToposPro software for topological analysis for crystal structures. Could be used for descriptors maybe. [Applied Topological Analysis of Crystal Structures with the Program Package ToposPro](https://pubs.acs.org/doi/full/10.1021/cg500498k), Blatov. [ToposPro Software](https://topospro.com/software/topospro/).

- 210202: dl4sci-school.lbl.gov 201001 talk [Qualitative Choices in Representations for Molecules, Materials, and Surfaces](https://dl4sci-school.lbl.gov/zachary-ulissi), [youtube](https://www.youtube.com/watch?v=R4jMffHoHkc), by zachary-ulissi. Current overview of the field of descriptors / representations of materials including #mol #per #surf with literature review.
- 201223: [Nathan Frey](https://github.com/ncfrey):
  - pumml: Positive and Unlabeled Materials Machine Learning (pumml) is a code that uses semi-supervised machine learning to classify materials from only positive and unlabeled examples.
  - pytopomat: Python Topological Materials (pytopomat) is a code for easy, high-throughput analysis of topological materials.
  - pymatgen
  - deepchem
- 201222: after one-on-one ai-seminar with kovacik about his heusler alloys work (see ai-seminar '20sep29 kovacik, '20dec08 hilgers):
  - [aiida-jutools > kovacik's `structure_analyzer.py`](https://github.com/JuDFTteam/aiida-jutools/tree/master/aiida_jutools) (see handwritten notes for usage; update due in '21jan)
  - via mattermost > ai > 20sep15 > kovacik: "to quantify a local environment (or a superposition of several "ideal" local environments), one can use this": [janine george](https://jageo.github.io/) > [ChemEnv : a fast and robust tool to automatically identify coordination environments (notebook example)](https://matgenb.materialsvirtuallab.org/2018/01/01/ChemEnv-How-to-automatically-identify-coordination-environments-in-a-structure.html) (side-note: jageo collab rwth dronskowski, louvain hautier gonzen, pymatgen)
- 201221:
  - scientific software dev guides:
    - [molssi Python Package Best Practices](https://education.molssi.org/python-package-best-practices/)
    - [dutch escience center guide](https://guide.esciencecenter.nl/#/)
    - [e-cam Scientific Software Best Practices](https://e-cam.readthedocs.io/en/latest/best-practices/index.html)
    - [bssw better scientific software](https://bssw.io/)
- 201218:
  - [Physics ∩ ML virtual hub](http://www.physicsmeetsml.org/)
    - [Nov18 2020 Euclidean Neural Networks for Atomic systems](http://physicsmeetsml.org/posts/sem_2020_11_18/)
- 201213:
  - uni of california irvine (kieron burke) Physical Sciences Machine Learning Nexus (seminar/workshop series)
    - https://ps.uci.edu/psml/
    - https://www.youtube.com/channel/UCWZ_0VWbJdoIu7u4pyT3r8A/search?query=psml
      - kr-mueller [ML meets Quantum Physics](https://www.youtube.com/watch?v=KN7mCSMX_9g). post to youtube when done:
        - 4:53 Ingredients to build an ML estimator
        - 10:44 ML for chemical compound space
        - 16:29 Descriptors: Coulomb matrix, etc.
        - 18:31 KRR Kernel Ridge Regression
        - 21:39 Deep Tensor Neural Network, SchNet, etc.
        - 29:49 Explaining Neural Networks
  - kr-mueller [How to represent crystal structures for machine learning: Towards fast prediction of electronic properties](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.89.205118#fulltext) (note: according to [qm-machine.org](http://quantum-machine.org/publications/), kr-mueller's work all on molecules not solids, except for this one)
  - kt-schuett [SchNet – A deep learning architecture for molecules and materials](https://aip.scitation.org/doi/10.1063/1.5019779) (note: see Figure2, Figure6, search 'defect': so capable to represent solids) (note2: SchNet is CNN for materials, with difference that conv filter is continuous not discrete, reference [kr-mueller psml](https://www.youtube.com/watch?v=KN7mCSMX_9g&t=25m35s))
  - [wandb.ai - Visualize & Debug Machine Learning Models](https://wandb.ai/wandb/getting-started/reports/Visualize-Debug-Machine-Learning-Models--VmlldzoyNzY5MDk?utm_source=karoly) - similar service to cometml, free for academics, mainly for DL
  - [Google JAX-MD - Accelerated, Differentiable, Molecular Dynamics](https://github.com/google/jax-md) (via twitter > NeurIPS. yes it's only MD, but it builds on [Google's Python Jax](https://github.com/google/jax), which can autodiff any Python function in HPC fashion (GPU-optimized) automatically! The gradient of the potential is the force field.)
- 2011:
  - [QPhML2020](https://ellisqphml.github.io/qphml2020.html) workshop: lectures by Csanyi, Ceriotti, Noe, Tkatchenko, Lilienfeld
  - [ML4Science](https://www.youtube.com/c/ML4Science/videos) talks by Burke, Curtarolo, Tamblyn, Csanyi
## New stuff
New stuff 2023-06-11 onwards, found while porting best-of-aml list to https://github.com/JuDFTteam/best-of-atomistic-machine-learning/. Stuff that does not fit into the AML category, but rather e.g. atomistic simulation, etc.

- https://github.com/molssi
  - https://github.com/molssi/cookiecutter-cms
- https://github.com/orgs/ulissigroup/repositories
  - The HTC workflow dataset generation stuff is particularly interesting.
  - https://github.com/ulissigroup/wherewulff
  - https://github.com/ulissigroup/vasp-interactive
  - https://github.com/ulissigroup/CatKit
- https://github.com/hackingmaterials
  - https://github.com/hackingmaterials/rocketsled
  - https://github.com/hackingmaterials/materials-coord
  - https://github.com/hackingmaterials/amset
  - https://github.com/hackingmaterials/figrecipes
  - https://github.com/usnistgov/pyMCR
  - https://github.com/usnistgov/atomman
  - https://github.com/hackingmaterials/robocrystallographer
- https://github.com/yoshida-lab
  - https://github.com/yoshida-lab/crystallus
  - https://github.com/yoshida-lab/avalon
- ChemEnv (in list above). This is not an AML tool per se. Instead, also fits
  more into atomistic simulation super-category.
- https://github.com/semodi
  - https://github.com/semodi/raynx
  - https://towardsdatascience.com/supercharge-your-model-performance-with-inductive-bias-48559dba5133
  - https://github.com/semodi/paper-scraper
  - https://github.com/semodi/diffusion_map
- https://github.com/whitead
  - https://github.com/whitead/smilesDrawer
  - https://github.com/whitead/molbloom
  - https://github.com/whitead/skunk
  - https://github.com/whitead/molcloud
- https://github.com/deepmodeling
  - https://github.com/deepmodeling/dflow
  - https://github.com/dptech-corp/Uni-Core
  - https://openmm.org/
  - https://github.com/choderalab/pymbar
  - https://github.com/deepmind/optax
  - https://github.com/mdtraj/mdtraj
  - https://github.com/jax-md/jax-md
- https://github.com/learningmatter-mit/
  - https://github.com/learningmatter-mit/surface-sampling
- https://github.com/TUM-DAML
  - https://github.com/TUM-DAML/seml
- https://github.com/MMunibas/
  - https://github.com/MMunibas/RKHS
- https://github.com/LLNL/
  - https://github.com/LLNL/lbann
  - https://github.com/LLNL/merlin
