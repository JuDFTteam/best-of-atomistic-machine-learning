<!-- markdownlint-disable -->
<h1 align="center">
    best-of-atomistic-machine-learning
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome atomistic machine learning (AML) projects. Updated monthly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-250-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/JuDFTteam/best-of-atomistic-machine-learning?color=green&label=updated"></a>
</p>

This curated list contains 250 awesome open-source projects with a total of 77K stars grouped into 24 categories. All projects are ranked by a [project-quality score](https://github.com/best-of-lists/best-of-generator#project-quality-score), which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/issues/new/choose), submit a [pull request](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/pulls), or directly edit the [projects.yaml](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/edit/main/projects.yaml).

The current focus of this list is more on simulation data rather than experimental data, and more on materials rather than molecules. Nevertheless, contributions from other fields are warmly welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Active learning](#active-learning) _2 projects_
- [Biomolecules](#biomolecules) _2 projects_
- [Community resources](#community-resources) _1 projects_
- [Datasets](#datasets) _31 projects_
- [Data Structures](#data-structures) _2 projects_
- [Density functional theory (ML-DFT)](#density-functional-theory-ml-dft) _17 projects_
- [Educational Resources](#educational-resources) _19 projects_
- [Explainable Artificial intelligence (XAI)](#explainable-artificial-intelligence-xai) _2 projects_
- [Electronic structure methods (ML-ESM)](#electronic-structure-methods-ml-esm) _3 projects_
- [General Tools](#general-tools) _22 projects_
- [Generative Models](#generative-models) _8 projects_
- [Machine Learning Potentials (MLP)](#machine-learning-potentials-mlp) _47 projects_
- [Materials Discovery](#materials-discovery) _6 projects_
- [Mathematical tools](#mathematical-tools) _9 projects_
- [Molecular Dynamics](#molecular-dynamics) _4 projects_
- [Natural Language Processing](#natural-language-processing) _5 projects_
- [Probabilistic ML](#probabilistic-ml) _0 projects_
- [Reinforcement Learning](#reinforcement-learning) _2 projects_
- [Representation Engineering Models](#representation-engineering-models) _5 projects_
- [Representation Learning Models](#representation-learning-models) _43 projects_
- [Representations](#representations) _12 projects_
- [Unsupervised Learning](#unsupervised-learning) _6 projects_
- [Visualization](#visualization) _1 projects_
- [Wavefunction methods (ML-WFT)](#wavefunction-methods-ml-wft) _4 projects_
- [Others](#others) _1 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/python.ico" style="display:inline;" width="13" height="13">&nbsp; Python-related project, non-exclusive
- <img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13">&nbsp; Julia-related project, non-exclusive
- <img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/rust.ico" style="display:inline;" width="13" height="13">&nbsp; Rust-related project, non-exclusive
- <img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c%2B%2B.ico" style="display:inline;" width="13" height="13">&nbsp; C++ - related project, non-exclusive
- <img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13">&nbsp; C-related project, non-exclusive
- <img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/fortran.ico" style="display:inline;" width="13" height="13">&nbsp; Fortran-related project, non-exclusive
- <img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/073d9ecaf3e28d0f1378e9f660cd4f631bf71fd7/config/images/javascript.ico" style="display:inline;" width="13" height="13">&nbsp; JavaScript-related project, non-exclusive
- <img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/073d9ecaf3e28d0f1378e9f660cd4f631bf71fd7/config/images/java.ico" style="display:inline;" width="13" height="13">&nbsp; Java-related project, non-exclusive

<br>

## Active learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on enabling active learning, iterative learning schemes for atomistic ML._

<details><summary><b><a href="https://github.com/ulissigroup/finetuna">Finetuna</a></b> (🥇10 ·  ⭐ 25) - Active Learning for Machine Learning Potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ulissigroup/finetuna) (👨‍💻 11 · 🔀 6 · 📋 16 - 18% open · ⏱️ 13.02.2023):

	```
	git clone https://github.com/ulissigroup/finetuna
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEHAL">ACEHAL</a></b> (🥉5 ·  ⭐ 7 · 🐣) - Hyperactive Learning (HAL) Python interface for building Atomic Cluster Expansion potentials. <code>Unlicensed</code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ACEsuit/ACEHAL) (👨‍💻 3 · 🔀 2 · 📋 8 - 37% open · ⏱️ 09.05.2023):

	```
	git clone https://github.com/ACEsuit/ACEHAL
	```
</details>
<br>

## Biomolecules

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on biomolecules, protein structure, protein folding, etc. using atomistic ML._

<details><summary><b><a href="https://github.com/deepmind/alphafold">AlphaFold</a></b> (🥇23 ·  ⭐ 10K · 📉) - Open source code for AlphaFold. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepmind/alphafold) (👨‍💻 18 · 🔀 1.8K · 📦 5 · 📋 700 - 20% open · ⏱️ 16.06.2023):

	```
	git clone https://github.com/deepmind/alphafold
	```
</details>
<details><summary><b><a href="https://github.com/dptech-corp/Uni-Fold">Uni-Fold</a></b> (🥉16 ·  ⭐ 260) - An open-source platform for developing protein models beyond AlphaFold. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dptech-corp/Uni-Fold) (👨‍💻 7 · 🔀 44 · 📥 1.7K · 📋 54 - 12% open · ⏱️ 19.06.2023):

	```
	git clone https://github.com/dptech-corp/Uni-Fold
	```
</details>
<br>

## Community resources

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that foster communication within the atomistic ML community._

🔗&nbsp;<b><a href="https://cortner.github.io/ACEweb/">Atomic Cluster Expansion</a></b>  - Atomic Cluster Expansion (ACE) community homepage.

<br>

## Datasets

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Datasets, databases and trained models for atomistic ML._

🔗&nbsp;<b><a href="https://crystals.ai/">crystals.ai</a></b>  - Curated datasets for reproducible AI in materials science.

🔗&nbsp;<b><a href="http://sgdml.org/#datasets">sGDML Datasets</a></b>  

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">QM7</a></b>  - This dataset is a subset of GDB-13 (a database of nearly 1 billion stable and synthetically accessible organic..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">QM7b</a></b>  - This dataset is an extension of the QM7 dataset for multitask learning where 13 additional properties (e.g...

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">QM9</a></b>  - We report computed geometric, energetic, electronic, and thermodynamic properties for 134k stable small organic..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">QM8</a></b>  - Dataset with low-lying singlet-singlet vertical electronic spectra of over 20000 synthetically feasible small organic..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">MD Trajectories of small molecules</a></b>  - The molecular dynamics (MD) datasets in this package range in size from 150k to nearly 1M conformational geometries.

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">MD Trajectories of C7O2H10</a></b>  - This data set consists of molecular dynamics trajectories of 113 randomly selected C7O2H10 isomers calculated at a..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">Datasets including densities</a></b>  - These datasets contain not only molecular geometries and energies but also valence densities.

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">ISO17</a></b>  - MD Trajectories of C7O2H10 with total energies and atomic forces.

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">SN2 reactions</a></b>  - Chemical reactions of methyl halides with halide anions.

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">Solvated protein fragments</a></b>  - Contains structures for all possible amons (hydrogen-saturated covalently bonded fragments) of up to eight heavy atoms..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">Molecules generated with G-SchNet</a></b>  - Molecules generated with the G-SchNet architecture trainined on 50k randomly selected structures from QM9. Both..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">MQMspin database</a></b>  - This data set contains a sample of approx. 5k singlet state and approx. 8k triplet state carbene structures drawn from..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">Molecular Hamiltonians and overlap matrices </a></b>  - Datasets containing structures, energies, forces, Hamiltonians (Fock or Kohn-Sham matrices) and overlap matrices for..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">tmQM Dataset</a></b>  - The transition metal quantum mechanics dataset (tmQM) contains the geometries and properties of a chemical compound..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">Densities dataset</a></b>  - These datasets contain molecular geometries, coupled-cluster energies, DFT energies, and valence electron densities..

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">Molecular response properties in implicit and explicit solvent environments</a></b>  - These datasets contain structures, energies, forces and various response properties (dipole moment, polarizability..

🔗&nbsp;<b><a href="https://pages.nist.gov/jarvis_leaderboard/">JARVIS-Leaderboard</a></b> ( ⭐ 29)  - This project provides benchmark-performances for materials science applications including Artificial Intelligence.. <code>benchmarking</code>

🔗&nbsp;<b><a href="https://www.catalysis-hub.org/">Catalysis Hub</a></b>  - A web-platform for sharing data and software for computational catalysis research!.

🔗&nbsp;<b><a href="https://matterverse.ai/">matterverse.ai</a></b>  - Database of yet-to-be-sythesized materials predicted using state-of-the-art machine learning algorithms.

🔗&nbsp;<b><a href="https://huggingface.co/DeepChem">DeepChem Models</a></b>   <code>pretrained</code> <code>NLP</code>

<details><summary><b><a href="https://github.com/isayev/ANI1_dataset">ANI-1 Dataset</a></b> (🥈8 ·  ⭐ 86 · 💤) - A data set of 20 million calculated off-equilibrium conformations for organic molecules. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/isayev/ANI1_dataset) (👨‍💻 3 · 🔀 18 · 📋 9 - 66% open · ⏱️ 08.08.2022):

	```
	git clone https://github.com/isayev/ANI1_dataset
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/visual_graph_datasets">Visual Graph Datasets</a></b> (🥉5) - Datasets for the training of graph neural networks (GNNs) and subsequent visualization of attributional explanations.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aimat-lab/visual_graph_datasets) (🔀 1 · ⏱️ 12.06.2023):

	```
	git clone https://github.com/aimat-lab/visual_graph_datasets
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://openkim.org/">OpenKIM</a></b> (🥇10 ·  ⭐ 28 · 💀) - The Open Knowledgebase of Interatomic Models (OpenKIM) aims to be an online resource for standardized testing, long-.. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <code>knowledgebase</code> <code>pretrained</code>
- <b><a href="https://github.com/deepchem/moleculenet">MoleculeNet Leaderboard</a></b> (🥈8 ·  ⭐ 70 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/aiqm/ANI1x_datasets">ANI-1x Datasets</a></b> (🥈6 ·  ⭐ 45 · 💀) - The ANI-1ccx and ANI-1x data sets, coupled-cluster and density functional theory properties for organic molecules. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/isayev/COMP6">COMP6 Benchmark dataset</a></b> (🥈6 ·  ⭐ 33 · 💀) - COMP6 Benchmark dataset for ML potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/learningmatter-mit/geom">GEOM</a></b> (🥉5 ·  ⭐ 120 · 💀) - GEOM: Energy-annotated molecular conformations. <code>Unlicensed</code> <code>💊</code>
- <b><a href="https://github.com/BingqingCheng/linear-regression-benchmarks">linear-regression-benchmarks</a></b> (🥉5 ·  ⭐ 1 · 💀) - Data sets used for linear regression benchmarks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code> <code>single-paper</code>
- <b><a href="https://github.com/aimat-lab/3DSC">3DSC Database</a></b> (🥉4 ·  ⭐ 5) - Repo for the paper publishing the superconductor database with 3D crystal structures. <code><a href="https://github.com/aimat-lab/3DSC/blob/main/LICENSE.md">Custom</a></code> <code>🧘</code> <code>materials-discovery</code>
</details>
<br>

## Data Structures

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on providing data structures used in atomistic machine learning._

<details><summary><b><a href="https://github.com/deepmodeling/dpdata">dpdata</a></b> (🥇22 ·  ⭐ 140) - Manipulating multiple atomic simulation data formats, including DeePMD-kit, VASP, LAMMPS, ABACUS, etc. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/dpdata) (👨‍💻 45 · 🔀 94 · 📦 97 · 📋 62 - 29% open · ⏱️ 04.05.2023):

	```
	git clone https://github.com/deepmodeling/dpdata
	```
- [PyPi](https://pypi.org/project/dpdata) (📥 3.2K / month):
	```
	pip install dpdata
	```
- [Conda](https://anaconda.org/deepmodeling/dpdata) (📥 440 · ⏱️ 16.06.2023):
	```
	conda install -c deepmodeling dpdata
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/equistore">Equistore</a></b> (🥉13 ·  ⭐ 23) - Storage format for equivariant atomistic machine learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/equistore) (👨‍💻 16 · 🔀 11 · 📋 89 - 41% open · ⏱️ 28.06.2023):

	```
	git clone https://github.com/lab-cosmo/equistore
	```
</details>
<br>

## Density functional theory (ML-DFT)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of DFT, such as density functional approximations (ML-DFA), the charge density, density of states, the Hamiltonian, etc._

<details><summary><b><a href="https://github.com/deepmind/deepmind-research/tree/master/density_functional_approximation_dm21">DM21</a></b> (🥇21 ·  ⭐ 12K) - This package provides a PySCF interface to the DM21 (DeepMind 21) family of exchange-correlation functionals described.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepmind/deepmind-research) (👨‍💻 92 · 🔀 2.4K · 📋 280 - 52% open · ⏱️ 02.06.2023):

	```
	git clone https://github.com/deepmind/deepmind-research
	```
</details>
<details><summary><b><a href="https://github.com/mala-project/mala">MALA</a></b> (🥇18 ·  ⭐ 35) - Materials Learning Algorithms. A framework for machine learning materials properties from first-principles data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mala-project/mala) (👨‍💻 41 · 🔀 17 · 📋 220 - 9% open · ⏱️ 07.06.2023):

	```
	git clone https://github.com/mala-project/mala
	```
</details>
<details><summary><b><a href="https://github.com/mzjb/DeepH-pack">DeepH-pack</a></b> (🥈14 ·  ⭐ 110) - Deep neural networks for density functional theory Hamiltonian. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mzjb/DeepH-pack) (👨‍💻 6 · 🔀 25 · 📋 33 - 12% open · ⏱️ 19.06.2023):

	```
	git clone https://github.com/mzjb/DeepH-pack
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/deepks-kit">DeePKS-kit</a></b> (🥈9 ·  ⭐ 92) - a package for developing machine learning-based chemically accurate energy and density functional models. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/deepks-kit) (👨‍💻 6 · 🔀 29 · 📋 9 - 11% open · ⏱️ 01.04.2023):

	```
	git clone https://github.com/deepmodeling/deepks-kit
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEhamiltonians.jl">ACEhamiltonians</a></b> (🥈9 ·  ⭐ 6) - Provides tools for constructing, fitting, and predicting self-consistent Hamiltonian and overlap matrices in solid-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ACEsuit/ACEhamiltonians.jl) (👨‍💻 4 · 🔀 3 · 📋 4 - 25% open · ⏱️ 12.04.2023):

	```
	git clone https://github.com/ACEsuit/ACEhamiltonians.jl
	```
</details>
<details><summary><b><a href="https://github.com/andreagrisafi/SALTED">SALTED</a></b> (🥈7 ·  ⭐ 10) - Program for doing symmetry-adapted learning of three-dimensional electron densities. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/andreagrisafi/SALTED) (👨‍💻 6 · 🔀 1 · ⏱️ 29.06.2023):

	```
	git clone https://github.com/andreagrisafi/SALTED
	```
</details>
<details><summary><b><a href="https://github.com/peterbjorgensen/DeepDFT">DeepDFT</a></b> (🥉6 ·  ⭐ 32) - Official implementation of DeepDFT model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/peterbjorgensen/DeepDFT) (👨‍💻 2 · 🔀 6 · ⏱️ 28.02.2023):

	```
	git clone https://github.com/peterbjorgensen/DeepDFT
	```
</details>
<details><summary><b><a href="https://github.com/mala-project/malada">MALADA</a></b> (🥉5) - MALA Data Acquisition: Helpful tools to build data for MALA. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mala-project/malada) (👨‍💻 2 · 🔀 1 · 📋 19 - 89% open · ⏱️ 24.05.2023):

	```
	git clone https://github.com/mala-project/malada
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/semodi/neuralxc">NeuralXC</a></b> (🥈10 ·  ⭐ 28 · 💀) - Implementation of a machine learned density functional. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/semodi/libnxc">Libnxc</a></b> (🥈7 ·  ⭐ 12 · 💀) - A library for using machine-learned exchange-correlation functionals for density-functional theory. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/fortran.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Xiaoxun-Gong/DeepH-E3">DeepH-E3</a></b> (🥉4 ·  ⭐ 22 · 🐣) - General framework for E(3)-equivariant neural network representation of density functional theory Hamiltonian. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>🧲</code>
- <b><a href="https://github.com/ulissigroup/charge-density-models">charge-density-models</a></b> (🥉4 ·  ⭐ 2) - Tools to build charge density models using ocpmodels. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/jmargraf/gprep">gprep</a></b> (🥉4 · 💀) - Fitting DFTB repulsive potentials with GPR. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/foxjas/CSNN">CSNN</a></b> (🥉4 · 💤) - Primary codebase of CSNN - Concentric Spherical Neural Network for 3D Representation Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/MihailBogojeski/ml-dft">ML-DFT</a></b> (🥉3 ·  ⭐ 14 · 💀) - A package for density functional approximation using machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mzjb/xDeepH">xDeepH</a></b> (🥉1 ·  ⭐ 15 · 🐣) - Extended DeepH (xDeepH) method for magnetic materials. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>🧲</code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://gitlab.com/jmargraf/kdf">kdft</a></b> (🥉1 ·  ⭐ 1 · 💀) - The Kernel Density Functional (KDF) code allows generating ML based DFT functionals. <code>Unlicensed</code>
</details>
<br>

## Educational Resources

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tutorials, guides, cookbooks, recipes, etc._

🔗&nbsp;<b><a href="https://www.elsevier.com/books-and-journals/book-companion/9780323900492">Quantum Chemistry in the Age of Machine Learning</a></b>  

<details><summary><b><a href="https://github.com/NVIDIA/DeepLearningExamples">NVIDIA Deep Learning Examples for Tensor Cores</a></b> (🥇22 ·  ⭐ 11K) - State-of-the-Art Deep Learning scripts organized by models - easy to train and deploy with reproducible accuracy and.. <code><a href="https://github.com/NVIDIA/DeepLearningExamples/blob/master/DGLPyTorch/DrugDiscovery/SE3Transformer/LICENSE">Custom</a></code> <code>💊</code></summary>

- [GitHub](https://github.com/NVIDIA/DeepLearningExamples) (👨‍💻 120 · 🔀 2.7K · 📋 750 - 26% open · ⏱️ 29.05.2023):

	```
	git clone https://github.com/NVIDIA/DeepLearningExamples
	```
</details>
<details><summary><b><a href="https://dmol.pub/">Deep Learning for Molecules and Materials Book</a></b> (🥇12 ·  ⭐ 510) - Deep learning for molecules and materials book. <code><a href="https://github.com/whitead/dmol-book/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/whitead/dmol-book) (👨‍💻 17 · 🔀 94 · 📋 150 - 15% open · ⏱️ 25.01.2023):

	```
	git clone https://github.com/whitead/dmol-book
	```
</details>
<details><summary><b><a href="https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks">jarvis-tools-notebooks</a></b> (🥈11 ·  ⭐ 36) - A Google-Colab Notebook Collection for Materials Design: https://jarvis.nist.gov/. <code><a href="https://tldrlegal.com/search?q=NIST">NIST</a></code></summary>

- [GitHub](https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks) (👨‍💻 4 · 🔀 20 · ⏱️ 28.06.2023):

	```
	git clone https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks
	```
</details>
<details><summary><b><a href="https://github.com/ceriottm/iam-notebooks">iam-notebooks</a></b> (🥈10 ·  ⭐ 16) - Jupyter notebooks for the lectures of the Introduction to Atomistic Modeling. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ceriottm/iam-notebooks) (👨‍💻 6 · 🔀 4 · ⏱️ 26.05.2023):

	```
	git clone https://github.com/ceriottm/iam-notebooks
	```
</details>
<details><summary><b><a href="https://github.com/rdkit/rdkit-tutorials">RDKit Tutorials</a></b> (🥈8 ·  ⭐ 190) - Tutorials to learn how to work with the RDKit. <code><a href="https://github.com/rdkit/rdkit-tutorials/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/rdkit/rdkit-tutorials) (👨‍💻 5 · 🔀 63 · 📋 4 - 75% open · ⏱️ 19.03.2023):

	```
	git clone https://github.com/rdkit/rdkit-tutorials
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/DoE_Course_Material">Data Handling, DoE and Statistical Analysis for Material Chemists</a></b> (🥈8 · 🐣) - Notebooks for workshops of DoE course, hosted by the Computational Materials Chemistry group at Uppsala University. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/DoE_Course_Material) (👨‍💻 3 · 🔀 12 · ⏱️ 26.06.2023):

	```
	git clone https://github.com/Teoroo-CMC/DoE_Course_Material
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/AI4Science101">AI4Science101</a></b> (🥉5 ·  ⭐ 63 · 💤) - AI for Science. <code>Unlicensed</code></summary>

- [GitHub](https://github.com/deepmodeling/AI4Science101) (👨‍💻 5 · 🔀 11 · ⏱️ 04.09.2022):

	```
	git clone https://github.com/deepmodeling/AI4Science101
	```
</details>
<details><summary><b><a href="https://github.com/CompPhysVienna/MLSummerSchoolVienna2022">Machine Learning for Materials Hard and Soft</a></b> (🥉5 ·  ⭐ 29 · 💤) - ESI-DCAFM-TACO-VDSP Summer School on Machine Learning for Materials Hard and Soft. <code>Unlicensed</code></summary>

- [GitHub](https://github.com/CompPhysVienna/MLSummerSchoolVienna2022) (👨‍💻 11 · 🔀 16 · ⏱️ 22.07.2022):

	```
	git clone https://github.com/CompPhysVienna/MLSummerSchoolVienna2022
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/deepchem/DeepLearningLifeSciences">DeepLearningLifeSciences</a></b> (🥈11 ·  ⭐ 290 · 💀) - Example code from the book Deep Learning for the Life Sciences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aimat-lab/MAChINE">MAChINE</a></b> (🥉7 ·  ⭐ 1 · 🐣) - Client-Server Web App to introduce usage of ML in materials science to beginners. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/anthony-wang/BestPractices">BestPractices</a></b> (🥉6 ·  ⭐ 130 · 💀) - Things that you should (and should not) do in your Materials Informatics research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/WardLT/applied-ai-for-materials">Applied AI for Materials</a></b> (🥉6 ·  ⭐ 41 · 💀) - Course materials for Applied AI for Materials Science and Engineering. <code>Unlicensed</code>
- <b><a href="https://github.com/lab-cosmo/software-cookbook">COSMO Software Cookbook</a></b> (🥉6 ·  ⭐ 2 · 🐣) - The COSMO cookbook contains recipes for atomic-scale modelling for materials and molecules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/BingqingCheng/ML-in-chemistry-101">ML-in-chemistry-101</a></b> (🥉4 ·  ⭐ 50 · 💀) - The course materials for Machine Learning in Chemistry 101. <code>Unlicensed</code>
- <b><a href="https://github.com/gabor1/chemrev-gpr">chemrev-gpr</a></b> (🥉4 ·  ⭐ 5 · 💀) - Notebooks accompanying the paper on GPR in materials and molecules in Chemical Reviews 2020. <code>Unlicensed</code>
- <b><a href="https://github.com/bfocassio/MLDensity_tutorial">MLDensity_tutorial</a></b> (🥉1 ·  ⭐ 4 · 🐣) - Tutorial files to work with ML for the charge density in molecules and solids. <code>Unlicensed</code>
- <b><a href="https://github.com/Teoroo-CMC/PiNN_lab">PiNN Lab</a></b> (🥉1 ·  ⭐ 2) -  <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/mala-project/mala_tutorial">MALA Tutorial</a></b> (🥉1 ·  ⭐ 1 · 🐣) - A full MALA hands-on tutorial. <code>Unlicensed</code>
</details>
<br>

## Explainable Artificial intelligence (XAI)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on explainability and model interpretability in atomistic ML._

<details><summary><b><a href="https://github.com/ur-whitelab/exmol">exmol</a></b> (🥇19 ·  ⭐ 240) - Explainer for black box models that predict molecule properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ur-whitelab/exmol) (👨‍💻 7 · 🔀 35 · 📦 12 · 📋 66 - 13% open · ⏱️ 19.06.2023):

	```
	git clone https://github.com/ur-whitelab/exmol
	```
- [PyPi](https://pypi.org/project/exmol) (📥 1K / month):
	```
	pip install exmol
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/graph_attention_student">MEGAN: Multi Explanation Graph Attention Student</a></b> (🥉6) - Minimal implementation of graph attention student model architecture. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aimat-lab/graph_attention_student) (🔀 1 · ⏱️ 21.06.2023):

	```
	git clone https://github.com/aimat-lab/graph_attention_student
	```
</details>
<br>

## Electronic structure methods (ML-ESM)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of electronic structure methods, which do not fit into either of the categories ML-WFT or ML-DFT._

<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/masashitsubaki/QuantumDeepField_molecule">QDF for molecule</a></b> (🥇9 ·  ⭐ 160 · 💀) - Quantum deep field: data-driven wave function, electron density generation, and energy prediction and extrapolation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/jmargraf/kqeq">q-pac</a></b> (🥉4 ·  ⭐ 2 · 💀) - Kernel charge equilibration method. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>⚡</code>
- <b><a href="https://github.com/muhrin/e3psi">e3psi</a></b> (🥉3 ·  ⭐ 2) - Equivariant machine learning library for learning from electronic structures. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code>
</details>
<br>

## General Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General tools for atomistic machine learning._

<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥇36 ·  ⭐ 4.4K) - Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry, Materials Science and Biology. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 220 · 🔀 1.4K · 📦 210 · 📋 1.6K - 24% open · ⏱️ 27.06.2023):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 20K / month):
	```
	pip install deepchem
	```
- [Conda](https://anaconda.org/conda-forge/deepchem) (📥 100K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge deepchem
	```
- [Docker Hub](https://hub.docker.com/r/deepchemio/deepchem) (📥 6.9K · ⭐ 4 · ⏱️ 11.03.2022):
	```
	docker pull deepchemio/deepchem
	```
</details>
<details><summary><b><a href="https://github.com/rdkit/rdkit">RDKit</a></b> (🥇30 ·  ⭐ 2.1K) -  <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rdkit/rdkit) (👨‍💻 200 · 🔀 740 · 📥 1.4K · 📋 2.8K - 29% open · ⏱️ 24.06.2023):

	```
	git clone https://github.com/rdkit/rdkit
	```
- [PyPi](https://pypi.org/project/rdkit) (📥 170K / month):
	```
	pip install rdkit
	```
- [Conda](https://anaconda.org/rdkit/rdkit) (📥 2.5M · ⏱️ 16.06.2023):
	```
	conda install -c rdkit rdkit
	```
</details>
<details><summary><b><a href="https://github.com/hackingmaterials/matminer">Matminer</a></b> (🥇29 ·  ⭐ 390) - Data mining for materials science. <code><a href="https://github.com/hackingmaterials/matminer/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/hackingmaterials/matminer) (👨‍💻 48 · 🔀 170 · 📦 210 · 📋 210 - 11% open · ⏱️ 27.06.2023):

	```
	git clone https://github.com/hackingmaterials/matminer
	```
- [PyPi](https://pypi.org/project/matminer) (📥 11K / month):
	```
	pip install matminer
	```
- [Conda](https://anaconda.org/conda-forge/matminer) (📥 43K · ⏱️ 27.06.2023):
	```
	conda install -c conda-forge matminer
	```
</details>
<details><summary><b><a href="https://github.com/libAtoms/QUIP">QUIP</a></b> (🥈27 ·  ⭐ 290) - libAtoms/QUIP molecular dynamics framework: https://libatoms.github.io. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code></summary>

- [GitHub](https://github.com/libAtoms/QUIP) (👨‍💻 79 · 🔀 120 · 📥 330 · 📦 20 · 📋 420 - 20% open · ⏱️ 15.06.2023):

	```
	git clone https://github.com/libAtoms/QUIP
	```
- [PyPi](https://pypi.org/project/quippy-ase) (📥 1.4K / month):
	```
	pip install quippy-ase
	```
- [Docker Hub](https://hub.docker.com/r/libatomsquip/quip) (📥 9.8K · ⭐ 4 · ⏱️ 24.04.2023):
	```
	docker pull libatomsquip/quip
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/maml">MAML</a></b> (🥈21 ·  ⭐ 250) - Python for Materials Machine Learning, Materials Descriptors, Machine Learning Force Fields, Deep Learning, etc. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/maml) (👨‍💻 24 · 🔀 56 · 📦 4 · 📋 60 - 8% open · ⏱️ 23.06.2023):

	```
	git clone https://github.com/materialsvirtuallab/maml
	```
- [PyPi](https://pypi.org/project/maml) (📥 140 / month):
	```
	pip install maml
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/jarvis">JARVIS-Tools</a></b> (🥈21 ·  ⭐ 230) - JARVIS-Tools: an open-source software package for data-driven atomistic materials design. Publications:.. <code><a href="https://github.com/usnistgov/jarvis/blob/master/LICENSE.rst">Custom</a></code></summary>

- [GitHub](https://github.com/usnistgov/jarvis) (👨‍💻 15 · 🔀 100 · 📦 56 · 📋 78 - 46% open · ⏱️ 29.05.2023):

	```
	git clone https://github.com/usnistgov/jarvis
	```
- [PyPi](https://pypi.org/project/jarvis-tools) (📥 4.2K / month):
	```
	pip install jarvis-tools
	```
- [Conda](https://anaconda.org/conda-forge/jarvis-tools) (📥 51K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jarvis-tools
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/flare">FLARE</a></b> (🥈18 ·  ⭐ 220) - An open-source Python package for creating fast and accurate interatomic potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mir-group/flare) (👨‍💻 36 · 🔀 51 · 📥 1 · 📦 9 · 📋 170 - 8% open · ⏱️ 26.05.2023):

	```
	git clone https://github.com/mir-group/flare
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/scikit-matter">Scikit-Matter</a></b> (🥈18 ·  ⭐ 59) -  <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>scikit-learn</code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/scikit-matter) (👨‍💻 11 · 🔀 14 · 📦 5 · 📋 65 - 15% open · ⏱️ 01.06.2023):

	```
	git clone https://github.com/scikit-learn-contrib/scikit-matter
	```
- [PyPi](https://pypi.org/project/skmatter) (📥 400 / month):
	```
	pip install skmatter
	```
- [Conda](https://anaconda.org/conda-forge/skmatter) (📥 280 · ⏱️ 18.06.2023):
	```
	conda install -c conda-forge skmatter
	```
</details>
<details><summary><b><a href="https://github.com/yoshida-lab/XenonPy">XenonPy</a></b> (🥈17 ·  ⭐ 110) - XenonPy is a Python Software for Materials Informatics. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yoshida-lab/XenonPy) (👨‍💻 10 · 🔀 57 · 📥 1.1K · 📋 82 - 19% open · ⏱️ 21.05.2023):

	```
	git clone https://github.com/yoshida-lab/XenonPy
	```
- [PyPi](https://pypi.org/project/xenonpy) (📥 330 / month):
	```
	pip install xenonpy
	```
</details>
<details><summary><b><a href="https://github.com/uw-cmg/MAST-ML">MAST-ML</a></b> (🥈17 ·  ⭐ 82) - MAterials Simulation Toolkit for Machine Learning (MAST-ML). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/uw-cmg/MAST-ML) (👨‍💻 19 · 🔀 49 · 📥 77 · 📦 4 · 📋 210 - 10% open · ⏱️ 01.05.2023):

	```
	git clone https://github.com/uw-cmg/MAST-ML
	```
</details>
<details><summary><b><a href="https://github.com/ulissigroup/amptorch">AMPtorch</a></b> (🥉11 ·  ⭐ 51) - AMPtorch: Atomistic Machine Learning Package (AMP) - PyTorch. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ulissigroup/amptorch) (👨‍💻 14 · 🔀 31 · 📋 29 - 13% open · ⏱️ 18.06.2023):

	```
	git clone https://github.com/ulissigroup/amptorch
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/qmlcode/qml">QML</a></b> (🥉16 ·  ⭐ 180 · 💀) - QML: Quantum Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/hackingmaterials/automatminer">Automatminer</a></b> (🥉14 ·  ⭐ 120 · 💀) - An automatic engine for predicting materials properties. <code><a href="https://github.com/hackingmaterials/automatminer/blob/main/LICENSE">Custom</a></code>
- <b><a href="https://github.com/Mariewelt/OpenChem">OpenChem</a></b> (🥉11 ·  ⭐ 530 · 💀) - OpenChem: Deep Learning toolkit for Computational Chemistry and Drug Design Research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mir-group/flare_pp">flare++</a></b> (🥉10 ·  ⭐ 34 · 💀) - A many-body extension of the FLARE code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code> <code>active-learning</code>
- <b><a href="https://github.com/deepchem/jaxchem">JAXChem</a></b> (🥉7 ·  ⭐ 74 · 💀) - JAXChem is a JAX-based deep learning library for complex and versatile chemical modeling. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ulissigroup/uncertainty_benchmarking">uncertainty_benchmarking</a></b> (🥉7 ·  ⭐ 33 · 💀) - Various code/notebooks to benchmark different ways we could estimate uncertainty in ML predictions. <code>Unlicensed</code> <code>benchmarking</code> <code>probabilistic</code>
- <b><a href="https://github.com/deepchem/torchchem">torchchem</a></b> (🥉7 ·  ⭐ 32 · 💀) - An experimental repo for experimenting with PyTorch models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ACEsuit/ACEatoms.jl">ACEatoms</a></b> (🥉4 ·  ⭐ 2) - Generic code for modelling atomic properties using ACE. <code><a href="https://github.com/ACEsuit/ACEatoms.jl/blob/main/ASL.md">Custom</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://bitbucket.org/wolverton/magpie/">Magpie</a></b> (🥉3) - Materials Agnostic Platform for Informatics and Exploration (Magpie). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/073d9ecaf3e28d0f1378e9f660cd4f631bf71fd7/config/images/java.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="http://mlatom.com/">MLatom</a></b> (🥉3) - Machine learning for atomistic simulations. <code><a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">Custom</a></code>
- <b><a href="https://github.com/hgheiberger/quantum-structure-ml">quantum-structure-ml</a></b> (🥉2 ·  ⭐ 1) - Multi-class classification model for predicting the magnetic order of magnetic structures and a binary classification.. <code>Unlicensed</code> <code>🧲</code> <code>benchmarking</code>
</details>
<br>

## Generative Models

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement generative models for atomistic ML._

<details><summary><b><a href="https://github.com/microsoft/molecule-generation">MoLeR</a></b> (🥇17 ·  ⭐ 190 · 📈) - Implementation of MoLeR: a generative model of molecular graphs which supports scaffold-constrained generation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/molecule-generation) (👨‍💻 5 · 🔀 29 · 📋 29 - 20% open · ⏱️ 16.06.2023):

	```
	git clone https://github.com/microsoft/molecule-generation
	```
- [PyPi](https://pypi.org/project/molecule-generation) (📥 270 / month):
	```
	pip install molecule-generation
	```
</details>
<details><summary><b><a href="https://github.com/whitead/synspace">synspace</a></b> (🥈12 ·  ⭐ 26 · 🐣) - Synthesis generative model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/whitead/synspace) (👨‍💻 2 · 🔀 2 · 📦 4 · 📋 3 - 66% open · ⏱️ 15.04.2023):

	```
	git clone https://github.com/whitead/synspace
	```
- [PyPi](https://pypi.org/project/synspace) (📥 800 / month):
	```
	pip install synspace
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/schnetpack-gschnet">SchNetPack G-SchNet</a></b> (🥈12 ·  ⭐ 18) - G-SchNet extension for SchNetPack. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/schnetpack-gschnet) (👨‍💻 3 · 🔀 3 · ⏱️ 01.06.2023):

	```
	git clone https://github.com/atomistic-machine-learning/schnetpack-gschnet
	```
</details>
<details><summary><b><a href="https://github.com/tsudalab/bVAE-IM">bVAE-IM</a></b> (🥉9 ·  ⭐ 7 · 🐣) - Implementation of Chemical Design with GPU-based Ising Machine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>⚛️</code> <code>single-paper</code></summary>

- [GitHub](https://github.com/tsudalab/bVAE-IM) (🔀 1 · ⏱️ 31.05.2023):

	```
	git clone https://github.com/tsudalab/bVAE-IM
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/G-SchNet">G-SchNet</a></b> (🥉8 ·  ⭐ 110) - G-SchNet - a generative model for 3d molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/G-SchNet) (👨‍💻 2 · 🔀 22 · ⏱️ 24.03.2023):

	```
	git clone https://github.com/atomistic-machine-learning/G-SchNet
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/cG-SchNet">cG-SchNet</a></b> (🥉8 ·  ⭐ 43) - cG-SchNet - a conditional generative neural network for 3d molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/cG-SchNet) (🔀 12 · ⏱️ 24.03.2023):

	```
	git clone https://github.com/atomistic-machine-learning/cG-SchNet
	```
</details>
<details><summary><b><a href="https://github.com/tsudalab/rxngenerator">rxngenerator</a></b> (🥉5 ·  ⭐ 11 · 💤) - A generative model for molecular generation via multi-step chemical reactions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tsudalab/rxngenerator) (🔀 2 · ⏱️ 09.08.2022):

	```
	git clone https://github.com/tsudalab/rxngenerator
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/tsudalab/MolSLEPA">MolSLEPA</a></b> (🥉5 ·  ⭐ 2 · 🐣) - Interpretable Fragment-based Molecule Design with Self-learning Entropic Population Annealing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>XAI</code>
</details>
<br>

## Machine Learning Potentials (MLP)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Machine Learning Potentials (aka MLP, MLIP, MLIAP) and force fields (ML-FF) for molecular dynamics._

🔗&nbsp;<b><a href="https://github.com/Open-Catalyst-Project/ocp/blob/main/MODELS.md">Pretrained OCP models</a></b>  - Pretrained models released as part of the Open Catalyst Project. <code>pretrained</code>

<details><summary><b><a href="https://github.com/deepmodeling/deepmd-kit">DeePMD-kit</a></b> (🥇28 ·  ⭐ 1.2K) - A deep learning package for many-body potential energy representation and molecular dynamics. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmodeling/deepmd-kit) (👨‍💻 57 · 🔀 410 · 📥 23K · 📦 11 · 📋 420 - 10% open · ⏱️ 24.05.2023):

	```
	git clone https://github.com/deepmodeling/deepmd-kit
	```
- [PyPi](https://pypi.org/project/deepmd-kit) (📥 920 / month):
	```
	pip install deepmd-kit
	```
- [Conda](https://anaconda.org/deepmodeling/deepmd-kit) (📥 870 · ⏱️ 16.06.2023):
	```
	conda install -c deepmodeling deepmd-kit
	```
- [Docker Hub](https://hub.docker.com/r/deepmodeling/deepmd-kit) (📥 1.9K · ⭐ 1 · ⏱️ 24.05.2023):
	```
	docker pull deepmodeling/deepmd-kit
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/megnet">MEGNet</a></b> (🥇22 ·  ⭐ 450) - Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/megnet) (👨‍💻 13 · 🔀 140 · 📦 68 · 📋 74 - 22% open · ⏱️ 27.04.2023):

	```
	git clone https://github.com/materialsvirtuallab/megnet
	```
- [PyPi](https://pypi.org/project/megnet) (📥 590 / month):
	```
	pip install megnet
	```
</details>
<details><summary><b><a href="https://github.com/aiqm/torchani">TorchANI</a></b> (🥇22 ·  ⭐ 390) - Accurate Neural Network Potential on PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aiqm/torchani) (👨‍💻 16 · 🔀 110 · 📦 24 · 📋 150 - 10% open · ⏱️ 21.03.2023):

	```
	git clone https://github.com/aiqm/torchani
	```
- [PyPi](https://pypi.org/project/torchani) (📥 2.4K / month):
	```
	pip install torchani
	```
- [Conda](https://anaconda.org/conda-forge/torchani) (📥 190K · ⏱️ 25.06.2023):
	```
	conda install -c conda-forge torchani
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/dpgen">DP-GEN</a></b> (🥇22 ·  ⭐ 220) - The deep potential generator to generate a deep-learning based model of interatomic potential energy and force field. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>workflows</code></summary>

- [GitHub](https://github.com/deepmodeling/dpgen) (👨‍💻 59 · 🔀 150 · 📥 1.4K · 📦 4 · 📋 220 - 15% open · ⏱️ 21.03.2023):

	```
	git clone https://github.com/deepmodeling/dpgen
	```
- [PyPi](https://pypi.org/project/dpgen) (📥 250 / month):
	```
	pip install dpgen
	```
- [Conda](https://anaconda.org/deepmodeling/dpgen) (📥 150 · ⏱️ 16.06.2023):
	```
	conda install -c deepmodeling dpgen
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/nequip">NequIP</a></b> (🥇20 ·  ⭐ 400) - NequIP is a code for building E(3)-equivariant interatomic potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mir-group/nequip) (👨‍💻 8 · 🔀 84 · 📦 12 · 📋 56 - 17% open · ⏱️ 26.03.2023):

	```
	git clone https://github.com/mir-group/nequip
	```
- [PyPi](https://pypi.org/project/nequip) (📥 400 / month):
	```
	pip install nequip
	```
- [Conda](https://anaconda.org/conda-forge/nequip) (📥 3K · ⏱️ 18.06.2023):
	```
	conda install -c conda-forge nequip
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/m3gnet">M3GNet</a></b> (🥈18 ·  ⭐ 160) - Materials graph network with 3-body interactions featuring a DFT surrogate crystal relaxer and a state-of-the-art.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/m3gnet) (👨‍💻 14 · 🔀 46 · 📦 12 · 📋 35 - 42% open · ⏱️ 06.06.2023):

	```
	git clone https://github.com/materialsvirtuallab/m3gnet
	```
- [PyPi](https://pypi.org/project/m3gnet) (📥 580 / month):
	```
	pip install m3gnet
	```
</details>
<details><summary><b><a href="https://github.com/stefanch/sGDML">sGDML</a></b> (🥈16 ·  ⭐ 110) - sGDML - Reference implementation of the Symmetric Gradient Domain Machine Learning model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanch/sGDML) (👨‍💻 7 · 🔀 34 · 📦 8 · 📋 16 - 31% open · ⏱️ 08.06.2023):

	```
	git clone https://github.com/stefanch/sGDML
	```
- [PyPi](https://pypi.org/project/sgdml) (📥 360 / month):
	```
	pip install sgdml
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace">MACE</a></b> (🥈15 ·  ⭐ 160) - MACE - Fast and accurate machine learning interatomic potentials with higher order equivariant message passing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace) (👨‍💻 11 · 🔀 52 · 📋 45 - 31% open · ⏱️ 23.02.2023):

	```
	git clone https://github.com/ACEsuit/mace
	```
</details>
<details><summary><b><a href="https://github.com/MaterSim/PyXtal_FF">PyXtalFF</a></b> (🥈15 ·  ⭐ 69) - Machine Learning Interatomic Potential Predictions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MaterSim/PyXtal_FF) (👨‍💻 8 · 🔀 19 · 📋 60 - 15% open · ⏱️ 09.06.2023):

	```
	git clone https://github.com/MaterSim/PyXtal_FF
	```
- [PyPi](https://pypi.org/project/pyxtal_ff) (📥 220 / month):
	```
	pip install pyxtal_ff
	```
</details>
<details><summary><b><a href="https://github.com/openkim/kliff">KLIFF</a></b> (🥈15 ·  ⭐ 26) - KIM-based Learning-Integrated Fitting Framework (KLIFF). <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <code>probabilistic</code> <code>workflows</code></summary>

- [GitHub](https://github.com/openkim/kliff) (👨‍💻 10 · 🔀 17 · 📋 31 - 48% open · ⏱️ 14.06.2023):

	```
	git clone https://github.com/openkim/kliff
	```
- [PyPi](https://pypi.org/project/kliff) (📥 92 / month):
	```
	pip install kliff
	```
- [Conda](https://anaconda.org/conda-forge/kliff) (📥 60K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge kliff
	```
</details>
<details><summary><b><a href="https://github.com/CompPhysVienna/n2p2">n2p2</a></b> (🥈14 ·  ⭐ 180 · 💤) - n2p2 - A Neural Network Potential Package. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/CompPhysVienna/n2p2) (👨‍💻 9 · 🔀 64 · 📋 140 - 38% open · ⏱️ 05.09.2022):

	```
	git clone https://github.com/CompPhysVienna/n2p2
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/CCS">CCS_fit</a></b> (🥈14 ·  ⭐ 5 · 📉) - Curvature Constrained Splines. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/CCS) (👨‍💻 8 · 🔀 8 · 📥 220 · 📋 13 - 61% open · ⏱️ 16.06.2023):

	```
	git clone https://github.com/Teoroo-CMC/CCS
	```
- [PyPi](https://pypi.org/project/ccs_fit) (📥 1.1K / month):
	```
	pip install ccs_fit
	```
</details>
<details><summary><b><a href="https://github.com/uf3/uf3">Ultra-Fast Force Fields (UF3)</a></b> (🥈13 ·  ⭐ 28 · 💤) - UF3: a python library for generating ultra-fast interatomic potentials. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uf3/uf3) (👨‍💻 3 · 🔀 13 · 📋 23 - 34% open · ⏱️ 03.10.2022):

	```
	git clone https://github.com/uf3/uf3
	```
- [PyPi](https://pypi.org/project/uf3) (📥 29 / month):
	```
	pip install uf3
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/DMFF">DMFF</a></b> (🥈12 ·  ⭐ 100) - DMFF (Differentiable Molecular Force Field) is a Jax-based python package that provides a full differentiable.. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/DMFF) (👨‍💻 7 · 🔀 24 · 📋 13 - 61% open · ⏱️ 14.02.2023):

	```
	git clone https://github.com/deepmodeling/DMFF
	```
</details>
<details><summary><b><a href="https://cortner.github.io/ACEweb/software/">Pacemaker</a></b> (🥈12 ·  ⭐ 39) - Python package for fitting atomic cluster expansion (ACE) potentials. <code><a href="https://github.com/ICAMS/python-ace/blob/master/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/ICAMS/python-ace) (👨‍💻 5 · 🔀 7 · 📋 27 - 22% open · ⏱️ 25.06.2023):

	```
	git clone https://github.com/ICAMS/python-ace
	```
- [PyPi](https://pypi.org/project/python-ace) (📥 3 / month):
	```
	pip install python-ace
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACE1pack.jl">ACE1Pack.jl</a></b> (🥈12 ·  ⭐ 10) - Provides convenience functionality for the usage of ACE1.jl, ACEfit.jl, JuLIP.jl for fitting interatomic potentials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ACEsuit/ACE1pack.jl) (👨‍💻 11 · 🔀 7 · 📋 84 - 50% open · ⏱️ 27.06.2023):

	```
	git clone https://github.com/ACEsuit/ACE1pack.jl
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/NeuralForceField">Neural Force Field</a></b> (🥈10 ·  ⭐ 170) - Neural Network Force Field based on PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code></summary>

- [GitHub](https://github.com/learningmatter-mit/NeuralForceField) (👨‍💻 9 · 🔀 39 · 📋 16 - 6% open · ⏱️ 20.05.2023):

	```
	git clone https://github.com/learningmatter-mit/NeuralForceField
	```
</details>
<details><summary><b><a href="https://github.com/thorben-frank/mlff">So3krates (MLFF)</a></b> (🥈10 ·  ⭐ 32 · 📈) - Build neural networks for machine learning force fields with JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thorben-frank/mlff) (👨‍💻 2 · 🔀 4 · 📋 4 - 25% open · ⏱️ 23.06.2023):

	```
	git clone https://github.com/thorben-frank/mlff
	```
</details>
<details><summary><b><a href="https://libatoms.github.io/">GAP</a></b> (🥈10 ·  ⭐ 30) - Gaussian Approximation Potential (GAP). <code><a href="https://github.com/libAtoms/GAP/blob/main/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/libAtoms/GAP) (👨‍💻 12 · 🔀 20 · ⏱️ 08.06.2023):

	```
	git clone https://github.com/libAtoms/GAP
	```
</details>
<details><summary><b><a href="https://acesuit.github.io/">ACE1.jl</a></b> (🥈10 ·  ⭐ 18) - Atomic Cluster Expansion for Modelling Invariant Atomic Properties. <code><a href="https://github.com/ACEsuit/ACE1.jl/blob/main/ASL.md">Custom</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ACEsuit/ACE1.jl) (👨‍💻 7 · 🔀 4 · 📋 45 - 48% open · ⏱️ 29.06.2023):

	```
	git clone https://github.com/ACEsuit/ACE1.jl
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/NNsForMD">NNsforMD</a></b> (🥈10 ·  ⭐ 9 · 💤) - Neural network class for molecular dynamics to predict potential energy, forces and non-adiabatic couplings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aimat-lab/NNsForMD) (👨‍💻 2 · 🔀 3 · ⏱️ 10.11.2022):

	```
	git clone https://github.com/aimat-lab/NNsForMD
	```
- [PyPi](https://pypi.org/project/pyNNsMD) (📥 32 / month):
	```
	pip install pyNNsMD
	```
</details>
<details><summary><b><a href="https://github.com/gasteigerjo/dimenet">DimeNet</a></b> (🥉9 ·  ⭐ 240) - DimeNet and DimeNet++ models, as proposed in Directional Message Passing for Molecular Graphs (ICLR 2020) and Fast and.. <code><a href="https://github.com/gasteigerjo/dimenet/blob/master/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/gasteigerjo/dimenet) (👨‍💻 2 · 🔀 50 · 📋 30 - 6% open · ⏱️ 26.04.2023):

	```
	git clone https://github.com/gasteigerjo/dimenet
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/allegro">Allegro</a></b> (🥉9 ·  ⭐ 190) - Allegro is an open-source code for building highly scalable and accurate equivariant deep learning interatomic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mir-group/allegro) (👨‍💻 2 · 🔀 26 · 📋 14 - 14% open · ⏱️ 08.05.2023):

	```
	git clone https://github.com/mir-group/allegro
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/PiNN">PiNN</a></b> (🥉9 ·  ⭐ 90) - A Python library for building atomic neural networks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/PiNN) (👨‍💻 2 · 🔀 25 · 📋 6 - 33% open · ⏱️ 23.01.2023):

	```
	git clone https://github.com/Teoroo-CMC/PiNN
	```
- [Docker Hub](https://hub.docker.com/r/teoroo/pinn) (📥 210 · ⏱️ 23.01.2023):
	```
	docker pull teoroo/pinn
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACE.jl">ACE.jl</a></b> (🥉9 ·  ⭐ 58) - Parameterisation of Equivariant Properties of Particle Systems. <code><a href="https://github.com/ACEsuit/ACE.jl/blob/main/license/mit.md">Custom</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ACEsuit/ACE.jl) (👨‍💻 12 · 🔀 14 · 📋 81 - 28% open · ⏱️ 09.06.2023):

	```
	git clone https://github.com/ACEsuit/ACE.jl
	```
</details>
<details><summary><b><a href="https://github.com/TUM-DAML/gemnet_pytorch">GemNet</a></b> (🥉8 ·  ⭐ 140) - GemNet model in PyTorch, as proposed in GemNet: Universal Directional Graph Neural Networks for Molecules (NeurIPS.. <code><a href="https://github.com/TUM-DAML/gemnet_pytorch/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/TUM-DAML/gemnet_pytorch) (👨‍💻 5 · 🔀 23 · ⏱️ 26.04.2023):

	```
	git clone https://github.com/TUM-DAML/gemnet_pytorch
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/Atomistic-Adversarial-Attacks">Atomistic Adversarial Attacks</a></b> (🥉8 ·  ⭐ 24 · 💤) - Code for performing adversarial attacks on atomistic systems using NN potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code></summary>

- [GitHub](https://github.com/learningmatter-mit/Atomistic-Adversarial-Attacks) (👨‍💻 6 · 🔀 6 · ⏱️ 03.10.2022):

	```
	git clone https://github.com/learningmatter-mit/Atomistic-Adversarial-Attacks
	```
</details>
<details><summary><b><a href="https://github.com/lanl/ALF">ALF</a></b> (🥉8 ·  ⭐ 16 · 🐣) - A framework for performing active learning for training machine-learned interatomic potentials. <code><a href="https://github.com/lanl/ALF/blob/main/LICENSE">Custom</a></code> <code>active-learning</code></summary>

- [GitHub](https://github.com/lanl/ALF) (👨‍💻 5 · 🔀 6 · ⏱️ 27.06.2023):

	```
	git clone https://github.com/lanl/alf
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace-jax">MACE-Jax</a></b> (🥉6 ·  ⭐ 30 · 🐣) - Equivariant machine learning interatomic potentials in JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace-jax) (👨‍💻 2 · 🔀 1 · ⏱️ 23.06.2023):

	```
	git clone https://github.com/ACEsuit/mace-jax
	```
</details>
<details><summary><b><a href="https://cortner.github.io/ACEweb/software/">TensorPotential</a></b> (🥉5 ·  ⭐ 5) - Tensorpotential is a TensorFlow based tool for development, fitting ML interatomic potentials from electronic.. <code><a href="https://github.com/ICAMS/TensorPotential/blob/main/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/ICAMS/TensorPotential) (👨‍💻 4 · 🔀 3 · ⏱️ 04.05.2023):

	```
	git clone https://github.com/ICAMS/TensorPotential
	```
</details>
<details><summary>Show 16 hidden projects...</summary>

- <b><a href="https://github.com/isayev/ASE_ANI">ANI-1</a></b> (🥈11 ·  ⭐ 200 · 💀) - ANI-1 neural net potential with python interface (ASE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/MDIL-SNU/SIMPLE-NN">SIMPLE-NN</a></b> (🥈11 ·  ⭐ 41 · 💀) - SIMPLE-NN(SNU Interatomic Machine-learning PotentiaL packagE version Neural Network). <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/ACEsuit/ACEfit.jl">ACEfit</a></b> (🥈10 ·  ⭐ 2 · 📈) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/atomistic-machine-learning/SchNet">SchNet</a></b> (🥉9 ·  ⭐ 170 · 💀) - SchNet - a deep learning architecture for quantum chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/materialsvirtuallab/snap">SNAP</a></b> (🥉8 ·  ⭐ 31 · 💀) - Repository for spectral neighbor analysis potential (SNAP) model development. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/aiqm/aimnet">AIMNet</a></b> (🥉7 ·  ⭐ 74 · 💀) - Atoms In Molecules Neural Network Potential. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/MMunibas/PhysNet">PhysNet</a></b> (🥉7 ·  ⭐ 73 · 💀) - Code for training PhysNet models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>⚡</code>
- <b><a href="https://github.com/MDIL-SNU/SIMPLE-NN_v2">SIMPLE-NN v2</a></b> (🥉7 ·  ⭐ 19) -  <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/libAtoms/testing-framework">testing-framework</a></b> (🥉6 ·  ⭐ 11 · 💀) - The purpose of this repository is to aid the testing of a large number of interatomic potentials for a variety of.. <code>Unlicensed</code> <code>benchmarking</code>
- <b><a href="https://gitlab.com/PANNAdevs/panna">PANNA</a></b> (🥉6 ·  ⭐ 5 · 💀) - A package to train and validate all-to-all connected network models for BP[1] and modified-BP[2] type local atomic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/Luthaf/alchemical-learning">Alchemical learning</a></b> (🥉5 ·  ⭐ 2) - Code for the Modeling high-entropy transition metal alloys with alchemical compression article. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/sirmarcel/glp">glp</a></b> (🥉4 ·  ⭐ 10 · 🐣) - tools for graph-based machine-learning potentials in jax. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/ashapeev/mlip-3">MLIP-3</a></b> (🥉3 ·  ⭐ 8 · 🐣) - MLIP-3: Active learning on atomic environments with Moment Tensor Potentials (MTP). <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ACEsuit/ACEworkflows">ACE Workflows</a></b> (🥉3 · 🐣) - Workflow Examples for ACE Models. <code>Unlicensed</code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code> <code>workflows</code>
- <b><a href="https://github.com/lmj1029123/SingleNN">SingleNN</a></b> (🥉2 ·  ⭐ 5 · 💀) - An efficient package for training and executing neural-network interatomic potentials. <code>Unlicensed</code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://www.uni-goettingen.de/de/560580.html">RuNNer</a></b> (🥉2) - The RuNNer Neural Network Energy Representation is a Fortran-based framework for the construction of Behler-.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/fortran.ico" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Materials Discovery

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement materials discovery methods using atomistic ML._

<details><summary><b><a href="https://github.com/CompRhys/aviary">aviary</a></b> (🥇13 ·  ⭐ 23) - The Wren sits on its Roost in the Aviary. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CompRhys/aviary) (👨‍💻 4 · 🔀 7 · 📋 26 - 15% open · ⏱️ 17.06.2023):

	```
	git clone https://github.com/CompRhys/aviary
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://gitlab.com/cest-group/boss">BOSS</a></b> (🥈6 ·  ⭐ 18 · 💀) - Bayesian Optimization Structure Search (BOSS). <code>Unlicensed</code> <code>probabilistic</code>
- <b><a href="https://github.com/ulissigroup/CAMD">Computational Autonomy for Materials Discovery (CAMD)</a></b> (🥈5 ·  ⭐ 1 · 🐣) - Agent-based sequential learning software for materials discovery. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Minoru938/CSPML">CSPML (crystal structure prediction with machine learning-based element substitution)</a></b> (🥉3 ·  ⭐ 11 · 💤) - Original implementation of CSPML. <code>Unlicensed</code> <code>structure-prediction</code>
- <b><a href="https://gitlab.com/agox/agox">AGOX</a></b> (🥉3 ·  ⭐ 10 · 💀) - AGOX is a package for global optimization of atomic system using e.g. the energy calculated from density functional.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>structure-optimization</code>
- <b><a href="https://github.com/MDIL-SNU/SPINNER">SPINNER</a></b> (🥉3 ·  ⭐ 8 · 💀) - SPINNER (Structure Prediction of Inorganic crystals using Neural Network potentials with Evolutionary and Random.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code> <code>structure-prediction</code>
</details>
<br>

## Mathematical tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement mathematical objects used in atomistic machine learning._

<details><summary><b><a href="https://github.com/deepmind/kfac-jax">KFAC-JAX</a></b> (🥇16 ·  ⭐ 140) - Second Order Optimization and Curvature Estimation with K-FAC in JAX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepmind/kfac-jax) (👨‍💻 11 · 🔀 9 · 📦 6 · 📋 8 - 50% open · ⏱️ 29.06.2023):

	```
	git clone https://github.com/deepmind/kfac-jax
	```
- [PyPi](https://pypi.org/project/kfac-jax) (📥 600 / month):
	```
	pip install kfac-jax
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/sphericart">SpheriCart</a></b> (🥈15 ·  ⭐ 35 · 🐣) - Multi-language library for the calculation of spherical harmonics in Cartesian coordinates. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/sphericart) (👨‍💻 6 · 🔀 3 · 📦 1 · 📋 10 - 60% open · ⏱️ 24.06.2023):

	```
	git clone https://github.com/lab-cosmo/sphericart
	```
- [PyPi](https://pypi.org/project/sphericart) (📥 160 / month):
	```
	pip install sphericart
	```
</details>
<details><summary><b><a href="https://github.com/ziatdinovmax/gpax">gpax</a></b> (🥈14 ·  ⭐ 84) - Structured Gaussian Processes and Deep Kernel Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code> <code>active-learning</code></summary>

- [GitHub](https://github.com/ziatdinovmax/gpax) (🔀 12 · ⏱️ 21.05.2023):

	```
	git clone https://github.com/ziatdinovmax/gpax
	```
- [PyPi](https://pypi.org/project/gpax) (📥 100 / month):
	```
	pip install gpax
	```
</details>
<details><summary><b><a href="https://github.com/risi-kondor/GElib">GElib</a></b> (🥉8 ·  ⭐ 17) - C++/CUDA library for SO(3) equivariant operations. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/risi-kondor/GElib) (👨‍💻 3 · 🔀 2 · 📋 3 - 66% open · ⏱️ 29.06.2023):

	```
	git clone https://github.com/risi-kondor/GElib
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/toolbox">COSMO Toolbox</a></b> (🥉6 ·  ⭐ 6) - Assorted libraries and utilities for atomistic simulation analysis. <code>Unlicensed</code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lab-cosmo/toolbox) (👨‍💻 9 · 🔀 5 · ⏱️ 23.06.2023):

	```
	git clone https://github.com/lab-cosmo/toolbox
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/ACEsuit/Polynomials4ML.jl">Polynomials4ML.jl</a></b> (🥈13 ·  ⭐ 4) - Polynomials for ML: fast evaluation, batching, differentiation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/julia.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lab-cosmo/equisolve">Equisolve</a></b> (🥉8 ·  ⭐ 3) - A package tasked with taking equistore objects and computing machine learning models using them. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/risi-kondor/cnine">cnine</a></b> (🥉5 ·  ⭐ 1) - Cnine tensor library. <code>Unlicensed</code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lab-cosmo/wigner_kernels">Wigner Kernels</a></b> (🥉4 · 🐣) - Collection of programs to benchmark Wigner kernels. <code>Unlicensed</code> <code>benchmarking</code>
</details>
<br>

## Molecular Dynamics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that simplify the integration of molecular dynamics and atomistic machine learning._

<details><summary><b><a href="https://github.com/jax-md/jax-md">JAX-MD</a></b> (🥇22 ·  ⭐ 950) - Differentiable, Hardware Accelerated, Molecular Dynamics. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jax-md/jax-md) (👨‍💻 21 · 🔀 160 · 📦 27 · 📋 120 - 43% open · ⏱️ 25.05.2023):

	```
	git clone https://github.com/jax-md/jax-md
	```
- [PyPi](https://pypi.org/project/jax-md) (📥 1.5K / month):
	```
	pip install jax-md
	```
</details>
<details><summary><b><a href="https://github.com/FitSNAP/FitSNAP">FitSNAP</a></b> (🥈19 ·  ⭐ 110) - Software for generating SNAP machine-learning interatomic potentials. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code></summary>

- [GitHub](https://github.com/FitSNAP/FitSNAP) (👨‍💻 24 · 🔀 41 · 📥 4 · 📋 58 - 13% open · ⏱️ 26.06.2023):

	```
	git clone https://github.com/FitSNAP/FitSNAP
	```
- [Conda](https://anaconda.org/conda-forge/fitsnap3) (📥 3.6K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge fitsnap3
	```
</details>
<details><summary><b><a href="https://github.com/ICAMS/lammps-user-pace">PACE</a></b> (🥉7 ·  ⭐ 19) - The LAMMPS MLP `pair_style pace`, aka Atomic Cluster Expansion (ACE), aka ML-PACE,.. <code><a href="https://github.com/ICAMS/lammps-user-pace/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/ICAMS/lammps-user-pace) (👨‍💻 6 · 🔀 9 · 📋 6 - 16% open · ⏱️ 31.01.2023):

	```
	git clone https://github.com/ICAMS/lammps-user-pace
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://gitlab.com/ivannovikov/interface-lammps-mlip-3">interface-lammps-mlip-3</a></b> (🥉2 ·  ⭐ 2 · 🐣) - An interface between LAMMPS and MLIP (version 3). <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code>
</details>
<br>

## Natural Language Processing

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that use natural language processing (NLP) and large language models (LLM) for atomistic ML._

<details><summary><b><a href="https://github.com/whitead/paper-qa">paper-qa</a></b> (🥇24 ·  ⭐ 2.7K · 🐣) - LLM Chain for answering questions from documents with citations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/whitead/paper-qa) (👨‍💻 10 · 🔀 230 · 📦 13 · 📋 87 - 34% open · ⏱️ 27.06.2023):

	```
	git clone https://github.com/whitead/paper-qa
	```
- [PyPi](https://pypi.org/project/paper-qa) (📥 5.6K / month):
	```
	pip install paper-qa
	```
</details>
<details><summary><b><a href="https://github.com/kjappelbaum/gptchem">gptchem</a></b> (🥈12 ·  ⭐ 150 · 🐣) - Use GPT-3 to solve chemistry problems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kjappelbaum/gptchem) (👨‍💻 2 · 🔀 27 · 📋 5 - 60% open · ⏱️ 22.06.2023):

	```
	git clone https://github.com/kjappelbaum/gptchem
	```
- [PyPi](https://pypi.org/project/gptchem) (📥 52 / month):
	```
	pip install gptchem
	```
</details>
<details><summary><b><a href="https://github.com/whitead/nlcc">nlcc</a></b> (🥈12 ·  ⭐ 41) - Natural language computational chemistry command line interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code></summary>

- [GitHub](https://github.com/whitead/nlcc) (👨‍💻 3 · 🔀 5 · ⏱️ 04.02.2023):

	```
	git clone https://github.com/whitead/nlcc
	```
- [PyPi](https://pypi.org/project/nlcc) (📥 74 / month):
	```
	pip install nlcc
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/molskill">MolSkill</a></b> (🥉11 ·  ⭐ 74 · 🐣) - Learning chemical intuition from humans in the loop. Supporting code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>💊</code> <code>recommender</code></summary>

- [GitHub](https://github.com/microsoft/molskill) (👨‍💻 4 · 🔀 5 · 📋 5 - 40% open · ⏱️ 13.06.2023):

	```
	git clone https://github.com/microsoft/molskill
	```
- [Conda](https://anaconda.org/msr-ai4science/molskill) (📥 77 · ⏱️ 18.06.2023):
	```
	conda install -c msr-ai4science molskill
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/StefanoSanvitoGroup/BERT-PSIE-TC">BERT-PSIE-TC</a></b> (🥉4 ·  ⭐ 2 · 🐣) - A dataset of Curie temperatures automatically extracted from scientific literature with the use of the BERT-PSIE.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>🧲</code>
</details>
<br>

## Probabilistic ML

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on probabilistic, Bayesian, Gaussian process and adversarial methods for atomistic ML, for optimization, uncertainty quantification (UQ), etc._

<br>

## Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on reinforcement learning for atomistic ML._

<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/isayev/ReLeaSE">ReLeaSE</a></b> (🥇11 ·  ⭐ 300 · 💀) - Deep Reinforcement Learning for de-novo Drug Design. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>💊</code>
- <b><a href="https://github.com/ulissigroup/catgym">CatGym</a></b> (🥉6 ·  ⭐ 9 · 💀) - Surface segregation using Deep Reinforcement Learning. <code><a href="https://tldrlegal.com/search?q=GPL">GPL</a></code>
</details>
<br>

## Representation Engineering Models

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General models that use hand-crafted representations, aka feature engineering._

<details><summary><b><a href="https://github.com/SUNCAT-Center/CatLearn">CatLearn</a></b> (🥇16 ·  ⭐ 87) -  <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>🪞</code></summary>

- [GitHub](https://github.com/SUNCAT-Center/CatLearn) (👨‍💻 22 · 🔀 49 · 📦 4 · 📋 25 - 36% open · ⏱️ 07.02.2023):

	```
	git clone https://github.com/SUNCAT-Center/CatLearn
	```
- [PyPi](https://pypi.org/project/catlearn) (📥 190 / month):
	```
	pip install catlearn
	```
</details>
<details><summary><b><a href="https://github.com/capoe/benchml">BenchML</a></b> (🥉10 ·  ⭐ 13) - ML benchmarking and pipeling framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>benchmarking</code></summary>

- [GitHub](https://github.com/capoe/benchml) (👨‍💻 9 · 🔀 2 · 📋 13 - 23% open · ⏱️ 24.05.2023):

	```
	git clone https://github.com/capoe/benchml
	```
- [PyPi](https://pypi.org/project/benchml) (📥 33 / month):
	```
	pip install benchml
	```
</details>
<details><summary><b><a href="https://github.com/dilkins/TENSOAP">SA-GPR</a></b> (🥉7 ·  ⭐ 14 · 💤) - Public repository for symmetry-adapted Gaussian Process Regression (SA-GPR). <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dilkins/TENSOAP) (👨‍💻 5 · 🔀 8 · 📋 7 - 28% open · ⏱️ 29.09.2022):

	```
	git clone https://github.com/dilkins/TENSOAP
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/sirmarcel/cmlkit">cmlkit</a></b> (🥈11 ·  ⭐ 29 · 💀) - tools for machine learning in condensed matter physics and quantum chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/dppant/magnetism-prediction">magnetism-prediction</a></b> (🥉4 ·  ⭐ 1) - DFT-aided Machine Learning Search for Magnetism in Fe-based Bimetallic Chalcogenides. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>🧲</code> <code>single-paper</code>
</details>
<br>

## Representation Learning Models

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General models that learn an embedding, such as message-passing neural networks (MPNN)._

🔗&nbsp;<b><a href="https://github.com/pyg-team/pytorch_geometric/tree/master/torch_geometric/nn/models">PyG Models</a></b>  - Representation learning models implemented in PyTorch Geometric.

<details><summary><b><a href="https://github.com/dmlc/dgl">Deep Graph Library (DGL)</a></b> (🥇37 ·  ⭐ 12K) - Python package built to ease deep learning on graph, on top of existing DL frameworks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 270 · 🔀 2.8K · 📦 110 · 📋 2.3K - 14% open · ⏱️ 29.06.2023):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 76K / month):
	```
	pip install dgl
	```
- [Conda](https://anaconda.org/dglteam/dgl) (📥 260K · ⏱️ 28.06.2023):
	```
	conda install -c dglteam dgl
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/schnetpack">SchNetPack</a></b> (🥇27 ·  ⭐ 600) - SchNetPack - Deep Neural Networks for Atomistic Systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/schnetpack) (👨‍💻 31 · 🔀 170 · 📦 55 · 📋 200 - 1% open · ⏱️ 29.06.2023):

	```
	git clone https://github.com/atomistic-machine-learning/schnetpack
	```
- [PyPi](https://pypi.org/project/schnetpack) (📥 490 / month):
	```
	pip install schnetpack
	```
</details>
<details><summary><b><a href="https://github.com/e3nn/e3nn">e3nn</a></b> (🥇25 ·  ⭐ 690) - A modular framework for neural networks with Euclidean symmetry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/e3nn/e3nn) (👨‍💻 27 · 🔀 100 · 📦 87 · 📋 140 - 10% open · ⏱️ 04.06.2023):

	```
	git clone https://github.com/e3nn/e3nn
	```
- [PyPi](https://pypi.org/project/e3nn) (📥 26K / month):
	```
	pip install e3nn
	```
- [Conda](https://anaconda.org/conda-forge/e3nn) (📥 7.5K · ⏱️ 18.06.2023):
	```
	conda install -c conda-forge e3nn
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/dgl-lifesci">dgl-lifesci</a></b> (🥇23 ·  ⭐ 590) - Python package for graph neural networks in chemistry and biology. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/awslabs/dgl-lifesci) (👨‍💻 22 · 🔀 130 · 📦 92 · 📋 79 - 29% open · ⏱️ 16.04.2023):

	```
	git clone https://github.com/awslabs/dgl-lifesci
	```
- [PyPi](https://pypi.org/project/dgllife) (📥 12K / month):
	```
	pip install dgllife
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/gcnn_keras">kgcnn</a></b> (🥇22 ·  ⭐ 77) - Graph convolution with tf.keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aimat-lab/gcnn_keras) (👨‍💻 7 · 🔀 23 · 📦 14 · 📋 76 - 5% open · ⏱️ 27.06.2023):

	```
	git clone https://github.com/aimat-lab/gcnn_keras
	```
- [PyPi](https://pypi.org/project/kgcnn) (📥 340 / month):
	```
	pip install kgcnn
	```
</details>
<details><summary><b><a href="https://github.com/Open-Catalyst-Project/ocp">ocp</a></b> (🥈19 ·  ⭐ 410) - ocp is the Open Catalyst Projects library of state-of-the-art machine learning algorithms for catalysis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Open-Catalyst-Project/ocp) (👨‍💻 30 · 🔀 160 · 📋 110 - 6% open · ⏱️ 15.06.2023):

	```
	git clone https://github.com/Open-Catalyst-Project/ocp
	```
</details>
<details><summary><b><a href="https://github.com/e3nn/e3nn-jax">e3nn-jax</a></b> (🥈18 ·  ⭐ 110) - jax library for E3 Equivariant Neural Networks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/e3nn/e3nn-jax) (👨‍💻 4 · 🔀 10 · ⏱️ 24.06.2023):

	```
	git clone https://github.com/e3nn/e3nn-jax
	```
- [PyPi](https://pypi.org/project/e3nn-jax) (📥 2.5K / month):
	```
	pip install e3nn-jax
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/matgl">MatGL (Materials Graph Library)</a></b> (🥈18 ·  ⭐ 78) - Graph deep learning library for materials. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/matgl) (👨‍💻 10 · 🔀 14 · 📦 1 · ⏱️ 29.06.2023):

	```
	git clone https://github.com/materialsvirtuallab/matgl
	```
- [PyPi](https://pypi.org/project/m3gnet) (📥 580 / month):
	```
	pip install m3gnet
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/alignn">ALIGNN</a></b> (🥈17 ·  ⭐ 130) - Atomistic Line Graph Neural Network. <code><a href="https://github.com/usnistgov/alignn/blob/main/LICENSE.rst">Custom</a></code></summary>

- [GitHub](https://github.com/usnistgov/alignn) (👨‍💻 6 · 🔀 60 · 📦 4 · 📋 43 - 55% open · ⏱️ 23.06.2023):

	```
	git clone https://github.com/usnistgov/alignn
	```
- [PyPi](https://pypi.org/project/alignn) (📥 970 / month):
	```
	pip install alignn
	```
</details>
<details><summary><b><a href="https://github.com/dptech-corp/Uni-Mol">Uni-Mol</a></b> (🥈14 ·  ⭐ 350 · 📉) - Official Repository for the Uni-Mol Series Methods. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code></summary>

- [GitHub](https://github.com/dptech-corp/Uni-Mol) (👨‍💻 6 · 🔀 57 · 📥 3.5K · 📋 77 - 23% open · ⏱️ 12.06.2023):

	```
	git clone https://github.com/dptech-corp/Uni-Mol
	```
</details>
<details><summary><b><a href="https://github.com/NREL/nfp">Neural fingerprint (nfp)</a></b> (🥈12 ·  ⭐ 53 · 💤) - Keras layers for end-to-end learning with rdkit and pymatgen. <code><a href="https://github.com/NREL/nfp/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/NREL/nfp) (👨‍💻 4 · 🔀 24 · 📦 11 · ⏱️ 14.06.2022):

	```
	git clone https://github.com/NREL/nfp
	```
</details>
<details><summary><b><a href="https://github.com/sparks-baird/CrabNet">Compositionally-Restricted Attention-Based Network (CrabNet)</a></b> (🥈12 ·  ⭐ 10) - Predict materials properties using only the composition information!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sparks-baird/CrabNet) (👨‍💻 5 · 🔀 2 · 📦 10 · 📋 15 - 86% open · ⏱️ 19.06.2023):

	```
	git clone https://github.com/sparks-baird/CrabNet
	```
- [PyPi](https://pypi.org/project/crabnet) (📥 350 / month):
	```
	pip install crabnet
	```
</details>
<details><summary><b><a href="https://github.com/gasteigerjo/gdc">GDC</a></b> (🥈10 ·  ⭐ 210) - Graph Diffusion Convolution, as proposed in Diffusion Improves Graph Learning (NeurIPS 2019). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>generative</code></summary>

- [GitHub](https://github.com/gasteigerjo/gdc) (👨‍💻 3 · 🔀 35 · ⏱️ 26.04.2023):

	```
	git clone https://github.com/gasteigerjo/gdc
	```
</details>
<details><summary><b><a href="https://github.com/superlouis/GATGNN">GATGNN: Global Attention Graph Neural Network</a></b> (🥈9 ·  ⭐ 59 · 💤) - Pytorch Repository for our work: Graph convolutional neural networks with global attention for improved materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/superlouis/GATGNN) (👨‍💻 3 · 🔀 18 · 📋 6 - 50% open · ⏱️ 03.10.2022):

	```
	git clone https://github.com/superlouis/GATGNN
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/matsciml">matsciml</a></b> (🥈9 ·  ⭐ 43) - Open MatSci ML Toolkit is a single framework for prototyping and scaling out deep learning models for materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>workflows</code></summary>

- [GitHub](https://github.com/IntelLabs/matsciml) (👨‍💻 5 · 🔀 5 · 📋 9 - 44% open · ⏱️ 13.03.2023):

	```
	git clone https://github.com/IntelLabs/matsciml
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/ML4pXRDs">ML4pXRDs</a></b> (🥈9 · 🐣) - Contains code to train neural networks based on simulated powder XRDs from synthetic crystals. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>🩻</code> <code>single-paper</code></summary>

- [GitHub](https://github.com/aimat-lab/ML4pXRDs) (🔀 1 · 📥 2 · ⏱️ 14.06.2023):

	```
	git clone https://github.com/aimat-lab/ML4pXRDs
	```
</details>
<details><summary><b><a href="https://github.com/usccolumbia/deeperGATGNN">DeeperGATGNN</a></b> (🥉8 ·  ⭐ 30) - Scalable graph neural networks for materials property prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/usccolumbia/deeperGATGNN) (👨‍💻 3 · 🔀 7 · ⏱️ 19.04.2023):

	```
	git clone https://github.com/usccolumbia/deeperGATGNN
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/uvvisml">UVVisML</a></b> (🥉8 ·  ⭐ 10) - Predict optical properties of molecules with machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>👁️</code> <code>single-paper</code> <code>probabilistic</code></summary>

- [GitHub](https://github.com/learningmatter-mit/uvvisml) (🔀 4 · ⏱️ 26.05.2023):

	```
	git clone https://github.com/learningmatter-mit/uvvisml
	```
</details>
<details><summary><b><a href="https://github.com/lanl/hippynn">hippynn</a></b> (🥉7 ·  ⭐ 39) - python library for atomistic machine learning. <code><a href="https://github.com/lanl/hippynn/blob/main/LICENSE.txt">Custom</a></code> <code>workflows</code></summary>

- [GitHub](https://github.com/lanl/hippynn) (👨‍💻 9 · 🔀 17 · ⏱️ 30.03.2023):

	```
	git clone https://github.com/lanl/hippynn
	```
</details>
<details><summary><b><a href="https://github.com/Open-Catalyst-Project/AdsorbML">AdsorbML</a></b> (🥉7 ·  ⭐ 14) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>🪞</code> <code>single-paper</code></summary>

- [GitHub](https://github.com/Open-Catalyst-Project/AdsorbML) (👨‍💻 4 · 🔀 2 · ⏱️ 16.06.2023):

	```
	git clone https://github.com/Open-Catalyst-Project/AdsorbML
	```
</details>
<details><summary><b><a href="https://github.com/hyllios/CGAT">CGAT</a></b> (🥉7 ·  ⭐ 9) - Crystal graph attention neural networks for materials prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hyllios/CGAT) (👨‍💻 4 · 🔀 7 · ⏱️ 10.01.2023):

	```
	git clone https://github.com/hyllios/CGAT
	```
</details>
<details><summary><b><a href="https://github.com/LLNL/graphite">graphite</a></b> (🥉7 ·  ⭐ 9) - A repository for implementing graph network models based on atomic structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/LLNL/graphite) (🔀 3 · ⏱️ 10.06.2023):

	```
	git clone https://github.com/llnl/graphite
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace-layer">MACE-Layer</a></b> (🥉6 ·  ⭐ 20) - Higher order equivariant graph neural networks for 3D point clouds. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace-layer) (👨‍💻 2 · 🔀 3 · ⏱️ 06.06.2023):

	```
	git clone https://github.com/ACEsuit/mace-layer
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/GLAMOUR">GLAMOUR</a></b> (🥉6 ·  ⭐ 18) - Graph Learning over Macromolecule Representations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code></summary>

- [GitHub](https://github.com/learningmatter-mit/GLAMOUR) (🔀 5 · ⏱️ 31.12.2022):

	```
	git clone https://github.com/learningmatter-mit/GLAMOUR
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/per-site_painn">Per-site PAiNN</a></b> (🥉6) - Fork of PaiNN for PerovskiteOrderingGCNNs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code> <code>pretrained</code> <code>single-paper</code></summary>

- [GitHub](https://github.com/learningmatter-mit/per-site_painn) (👨‍💻 10 · ⏱️ 05.06.2023):

	```
	git clone https://github.com/learningmatter-mit/per-site_painn
	```
</details>
<details><summary><b><a href="https://github.com/atomicarchitects/equiformer">Equiformer</a></b> (🥉5 ·  ⭐ 100 · 🐣) - [ICLR23 Spotlight] Equiformer: Equivariant Graph Attention Transformer for 3D Atomistic Graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomicarchitects/equiformer) (👨‍💻 2 · 🔀 14 · 📋 7 - 42% open · ⏱️ 21.06.2023):

	```
	git clone https://github.com/atomicarchitects/equiformer
	```
</details>
<details><summary>Show 16 hidden projects...</summary>

- <b><a href="https://github.com/graphdeeplearning/benchmarking-gnns">benchmarking-gnns</a></b> (🥈15 ·  ⭐ 2.2K · 💀) - Repository for benchmarking graph neural networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code> <code>benchmarking</code>
- <b><a href="https://github.com/txie-93/cgcnn">Crystal Graph Convolutional Neural Networks (CGCNN)</a></b> (🥈12 ·  ⭐ 480 · 💀) - Crystal graph convolutional neural networks for predicting material properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/FabianFuchsML/se3-transformer-public">SE(3)-Transformers</a></b> (🥈9 ·  ⭐ 390 · 💀) - code for the SE3 Transformers paper: https://arxiv.org/abs/2006.10503. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/masashitsubaki/molecularGNN_smiles">molecularGNN_smiles</a></b> (🥈9 ·  ⭐ 240 · 💀) - The code of a graph neural network (GNN) for molecules, which is based on learning representations of r-radius.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/dtnn">DTNN</a></b> (🥉7 ·  ⭐ 77 · 💀) - Deep Tensor Neural Network. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/risilab/cormorant">Cormorant</a></b> (🥉7 ·  ⭐ 51 · 💀) - Codebase for Cormorant Neural Networks. <code><a href="https://github.com/risilab/cormorant/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/risilab/Autobahn">Autobahn</a></b> (🥉5 ·  ⭐ 26 · 💀) - Repository for Autobahn: Automorphism Based Graph Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pfnet-research/charge_transfer_nnp">charge_transfer_nnp</a></b> (🥉5 ·  ⭐ 20 · 💀) - Graph neural network potential with charge transfer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>⚡</code>
- <b><a href="https://github.com/andy90/SCFNN">SCFNN</a></b> (🥉5 ·  ⭐ 13 · 💀) - Self-consistent determination of long-range electrostatics in neural network potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code> <code>⚡</code> <code>single-paper</code>
- <b><a href="https://github.com/atomistic-machine-learning/field_schnet">FieldSchNet</a></b> (🥉5 ·  ⭐ 9 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/learningmatter-mit/per-site_cgcnn">Per-Site CGCNN</a></b> (🥉5 ·  ⭐ 1 · 🐣) - Crystal graph convolutional neural networks for predicting material properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <code>single-paper</code>
- <b><a href="https://github.com/gasteigerjo/gtn">Graph Transport Network</a></b> (🥉4 ·  ⭐ 14) - Graph transport network (GTN), as proposed in Scalable Optimal Transport in High Dimensions for Graph Distances,.. <code><a href="https://github.com/gasteigerjo/gtn/blob/main/LICENSE.md">Custom</a></code> <code>🔥</code>
- <b><a href="https://github.com/learningmatter-mit/atom_by_atom">atom_by_atom</a></b> (🥉4 ·  ⭐ 1 · 🐣) - Atom-by-atom design of metal oxide catalysts for the oxygen evolution reaction with Machine Learning. <code>Unlicensed</code> <code>🪞</code> <code>single-paper</code>
- <b><a href="https://zenodo.org/record/7967079">Point Edge Transformer</a></b> (🥉2) - Smooth, exact rotational symmetrization for deep learning on point clouds. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code>
- <b><a href="https://github.com/sirmarcel/gkx">gkx: Green-Kubo Method in JAX</a></b> (🥉1 ·  ⭐ 2 · 🐣) - Green-Kubo + JAX + MLPs = Anharmonic Thermal Conductivities Done Fast. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>🔥</code>
- <b><a href="https://github.com/risilab/SphericalNet">SphericalNet</a></b> ( ⭐ 2 · 💤) - Implementation of Clebsch-Gordan Networks (CGnet: https://arxiv.org/pdf/1806.09231.pdf) by GElib & cnine libraries in.. <code>Unlicensed</code>
</details>
<br>

## Representations

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that offer implementations of representations, descriptors, fingerprints of atomistic systems._

<details><summary><b><a href="https://github.com/SINGROUP/dscribe">DScribe</a></b> (🥇25 ·  ⭐ 330) - DScribe is a python package for creating machine learning descriptors for atomistic systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SINGROUP/dscribe) (👨‍💻 18 · 🔀 74 · 📦 140 · 📋 82 - 9% open · ⏱️ 17.05.2023):

	```
	git clone https://github.com/SINGROUP/dscribe
	```
- [PyPi](https://pypi.org/project/dscribe) (📥 13K / month):
	```
	pip install dscribe
	```
- [Conda](https://anaconda.org/conda-forge/dscribe) (📥 73K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge dscribe
	```
</details>
<details><summary><b><a href="https://github.com/rouyang2017/SISSO">SISSO</a></b> (🥇13 ·  ⭐ 170) - A data-driven method combining symbolic regression and compressed sensing for accurate & interpretable models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/fortran.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rouyang2017/SISSO) (👨‍💻 3 · 🔀 58 · 📋 50 - 8% open · ⏱️ 17.06.2023):

	```
	git clone https://github.com/rouyang2017/SISSO
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/librascal">Librascal</a></b> (🥈12 ·  ⭐ 68 · 📉) - A scalable and versatile library to generate representations for atomic-scale learning. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/librascal) (👨‍💻 29 · 🔀 19 · 📋 230 - 43% open · ⏱️ 06.06.2023):

	```
	git clone https://github.com/lab-cosmo/librascal
	```
</details>
<details><summary><b><a href="https://github.com/Luthaf/rascaline">Rascaline</a></b> (🥈10 ·  ⭐ 11) - Computing representations for atomistic machine learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>Rust, C++</code></summary>

- [GitHub](https://github.com/Luthaf/rascaline) (👨‍💻 9 · 🔀 11 · 📋 31 - 54% open · ⏱️ 22.06.2023):

	```
	git clone https://github.com/Luthaf/rascaline
	```
</details>
<details><summary><b><a href="https://github.com/muhrin/milad">milad</a></b> (🥉6 ·  ⭐ 26) - Moment Invariants Local Atomic Descriptor. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>generative</code></summary>

- [GitHub](https://github.com/muhrin/milad) (📦 1 · ⏱️ 03.12.2022):

	```
	git clone https://github.com/muhrin/milad
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/nice">NICE</a></b> (🥉6 ·  ⭐ 10) - NICE (N-body Iteratively Contracted Equivariants) is a set of tools designed for the calculation of invariant and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/nice) (👨‍💻 4 · 🔀 2 · 📋 3 - 66% open · ⏱️ 01.05.2023):

	```
	git clone https://github.com/lab-cosmo/nice
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/Kaaiian/CBFV">CBFV</a></b> (🥈7 ·  ⭐ 11 · 💀) - Tool to quickly create a composition-based feature vector. <code>Unlicensed</code>
- <b><a href="https://github.com/zhuligs/fplib">fplib</a></b> (🥉6 ·  ⭐ 7 · 💀) - a fingerprint library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code> <code>single-paper</code>
- <b><a href="https://github.com/capoe/soapxx">SOAPxx</a></b> (🥉6 ·  ⭐ 7 · 💀) - A SOAP implementation. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ceriottm/lode">pyLODE</a></b> (🥉6 ·  ⭐ 2 · 💤) - Pythonic implementation of LOng Distance Equivariants. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>⚡</code>
- <b><a href="https://gitlab.com/sissopp_developers/sissopp">SISSO++</a></b> (🥉3 ·  ⭐ 1 · 💀) - C++ Implementation of SISSO with python bindings. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/e143de7faaa0dff3bc6a2c9fbaa46d209e56cb5e/config/images/c.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://bitbucket.org/andrewpeterson/amp/">AMP</a></b> (🥉2) - Amp is an open-source package designed to easily bring machine-learning to atomistic calculations. <code>Unlicensed</code>
</details>
<br>

## Unsupervised Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on unsupervised learning for atomistic ML, such as dimensionality reduction, clustering and visualization._

<details><summary><b><a href="https://github.com/sissa-data-science/DADApy">DADApy</a></b> (🥇16 ·  ⭐ 63 · 📉) - Distance-based Analysis of DAta-manifolds in python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sissa-data-science/DADApy) (👨‍💻 15 · 🔀 8 · 📦 2 · 📋 23 - 34% open · ⏱️ 28.06.2023):

	```
	git clone https://github.com/sissa-data-science/DADApy
	```
- [PyPi](https://pypi.org/project/dadapy) (📥 120 / month):
	```
	pip install dadapy
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/sketchmap">Sketchmap</a></b> (🥉8 ·  ⭐ 39) - Suite of programs to perform non-linear dimensionality reduction -- sketch-map in particular. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/sketchmap) (👨‍💻 8 · 🔀 10 · 📋 7 - 42% open · ⏱️ 24.05.2023):

	```
	git clone https://github.com/lab-cosmo/sketchmap
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/BingqingCheng/ASAP">ASAP</a></b> (🥈10 ·  ⭐ 110 · 💀) - ASAP is a package that can quickly analyze and visualize datasets of crystal or molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/learningmatter-mit/Coarse-Graining-Auto-encoders">Coarse-Graining-Auto-encoders</a></b> (🥉3 ·  ⭐ 18 · 💀) -  <code>Unlicensed</code> <code>single-paper</code>
- <b><a href="https://gitlab.mpcdf.mpg.de/klai/decaf">Descriptor Embedding and Clustering for Atomisitic-environment Framework (DECAF)</a></b> ( ⭐ 2) - Provides a workflow to obtain clustering of local environments in dataset of structures. <code>Unlicensed</code>
- <b><a href="https://github.com/Minoru938/KmdPlus">KmdPlus</a></b> ( ⭐ 1 · 🐣) - This module contains a class for treating kernel mean descriptor (KMD), and a function for generating descriptors with.. <code>Unlicensed</code>
</details>
<br>

## Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on visualization for atomistic ML._

<details><summary><b><a href="https://github.com/lab-cosmo/chemiscope">Chemiscope</a></b> (🥇17 ·  ⭐ 86) - An interactive structure/property explorer for materials and molecules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/073d9ecaf3e28d0f1378e9f660cd4f631bf71fd7/config/images/javascript.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lab-cosmo/chemiscope) (👨‍💻 17 · 🔀 26 · 📥 130 · 📦 4 · 📋 100 - 36% open · ⏱️ 24.05.2023):

	```
	git clone https://github.com/lab-cosmo/chemiscope
	```
- [npm](https://www.npmjs.com/package/chemiscope) (📥 10 / month):
	```
	npm install chemiscope
	```
</details>
<br>

## Wavefunction methods (ML-WFT)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of wavefunction electronic structure methods, such as Monte Carlo techniques like deep learning variational Monte Carlo (DL-VMC), MO theory methods, etc._

<details><summary><b><a href="https://github.com/deepqmc/deepqmc">DeepQMC</a></b> (🥇20 ·  ⭐ 280) - Deep learning quantum Monte Carlo for electrons in real space. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deepqmc/deepqmc) (👨‍💻 13 · 🔀 56 · 📦 1 · 📋 34 - 11% open · ⏱️ 28.06.2023):

	```
	git clone https://github.com/deepqmc/deepqmc
	```
- [PyPi](https://pypi.org/project/deepqmc) (📥 68 / month):
	```
	pip install deepqmc
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/ferminet">FermiNet</a></b> (🥈15 ·  ⭐ 560) - An implementation of the Fermionic Neural Network for ab-initio electronic structure calculations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepmind/ferminet) (👨‍💻 17 · 🔀 97 · ⏱️ 31.05.2023):

	```
	git clone https://github.com/deepmind/ferminet
	```
</details>
<details><summary><b><a href="https://github.com/mdsunivie/deeperwin">DeepErwin</a></b> (🥉9 ·  ⭐ 28) - DeepErwin is a python 3.8+ package that implements and optimizes JAX 2.x wave function models for numerical solutions.. <code><a href="https://github.com/mdsunivie/deeperwin/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/mdsunivie/deeperwin) (👨‍💻 6 · 🔀 5 · 📋 5 - 20% open · ⏱️ 23.05.2023):

	```
	git clone https://github.com/mdsunivie/deeperwin
	```
- [PyPi](https://pypi.org/project/deeperwin) (📥 35 / month):
	```
	pip install deeperwin
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/atomistic-machine-learning/SchNOrb">SchNOrb</a></b> (🥉5 ·  ⭐ 49 · 💀) - Unifying machine learning and quantum chemistry with a deep neural network for molecular wavefunctions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary>Show 1 hidden projects...</summary>


</details>

---

## Related Resources

Datasets.

- [**The Collection of Database and Dataset Resources in Materials Science**](https://github.com/sedaoturak/data-resources-for-materials-science).

General machine learning.

- [**Graph-based Deep Learning Literature**](https://github.com/naganandy/graph-based-deep-learning-literature). The repository contains links primarily to conference publications in graph-based deep learning
- [**best-of-ml-python**](https://github.com/ml-tooling/best-of-ml-python): A ranked list of awesome machine learning Python libraries.
- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

Materials informatics.

- [**tilde-lab - Awesome Materials Informatics**](https://github.com/tilde-lab/awesome-materials-informatics).
- [**GitHub Topic > materials-informatics**](https://github.com/topics/materials-informatics)
- [**A Highly Opinionated List of Open-Source Materials Informatics Resources**](https://github.com/ncfrey/resources). Last update 2022.

Quantum physics.

- [**Github Topic > tensor-networks**](https://github.com/topics/tensor-networks)

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
