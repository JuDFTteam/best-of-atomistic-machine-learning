<!-- markdownlint-disable -->
<h1 align="center">
    <!-- ⚛️🧬❄️/💎,  🤖🧠🦾✨, ▶️⏩➡️↔️🔄🔁♻️-->    
    Best of Atomistic Machine Learning ⚛️🧬💎
    <br>
</h1>

<p align="center">
    <!-- Note: For image preview, use path relative to source file, config/header.md. For production, use path relative to README.md. -->
    <!-- Either only Atom + NN, or NN + Atom, DNA, Crystal, standing for materials & molecules -->
    <!-- <img src="config/images/emoji-neural-network-like-atom_atom.svg" width="40"> -->
    <!-- <img src="config/images/emoji-neural-network-like-atom_nn-purple.svg" width="40"> -->
    <!-- <img src="./images/emoji-dna.svg" width="40"> -->
    <!-- <img src="./images/emoji-gem-stone.svg" width="40"> -->
</p>    

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome atomistic machine learning (AML) projects. Updated quarterly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-290-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/JuDFTteam/best-of-atomistic-machine-learning?color=green&label=updated"></a>
</p>

This curated list contains 290 awesome open-source projects with a total of 120K stars grouped into 23 categories. All projects are ranked by a [project-quality score](https://github.com/best-of-lists/best-of-generator#project-quality-score), which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/issues/new/choose), submit a [pull request](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/pulls), or directly edit the [projects.yaml](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/edit/main/projects.yaml).

The current focus of this list is more on simulation data rather than experimental data, and more on materials rather than drug design. Nevertheless, contributions from other fields are warmly welcome!

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Active learning](#active-learning) _4 projects_
- [Biomolecules](#biomolecules) _2 projects_
- [Community resources](#community-resources) _15 projects_
- [Datasets](#datasets) _24 projects_
- [Data Structures](#data-structures) _3 projects_
- [Density functional theory (ML-DFT)](#density-functional-theory-ml-dft) _19 projects_
- [Educational Resources](#educational-resources) _18 projects_
- [Explainable Artificial intelligence (XAI)](#explainable-artificial-intelligence-xai) _4 projects_
- [Electronic structure methods (ML-ESM)](#electronic-structure-methods-ml-esm) _2 projects_
- [General Tools](#general-tools) _22 projects_
- [Generative Models](#generative-models) _10 projects_
- [Interatomic Potentials (ML-IAP)](#interatomic-potentials-ml-iap) _51 projects_
- [Language Models](#language-models) _6 projects_
- [Materials Discovery](#materials-discovery) _8 projects_
- [Mathematical tools](#mathematical-tools) _9 projects_
- [Molecular Dynamics](#molecular-dynamics) _6 projects_
- [Probabilistic ML](#probabilistic-ml) _0 projects_
- [Reinforcement Learning](#reinforcement-learning) _2 projects_
- [Representation Engineering](#representation-engineering) _22 projects_
- [Representation Learning](#representation-learning) _52 projects_
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

<br>

## Active learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on enabling active learning, iterative learning schemes for atomistic ML._

<details><summary><b><a href="https://github.com/mir-group/flare">FLARE</a></b> (🥇19 ·  ⭐ 250) - An open-source Python package for creating fast and accurate interatomic potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C++</code> <code>ML-IAP</code></summary>

- [GitHub](https://github.com/mir-group/flare) (👨‍💻 36 · 🔀 56 · 📥 1 · 📦 10 · 📋 190 - 12% open · ⏱️ 26.05.2023):

	```
	git clone https://github.com/mir-group/flare
	```
</details>
<details><summary><b><a href="https://github.com/ulissigroup/finetuna">Finetuna</a></b> (🥈10 ·  ⭐ 33) - Active Learning for Machine Learning Potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ulissigroup/finetuna) (👨‍💻 11 · 🔀 7 · 📋 19 - 21% open · ⏱️ 03.10.2023):

	```
	git clone https://github.com/ulissigroup/finetuna
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEHAL">ACEHAL</a></b> (🥉6 ·  ⭐ 7) - Hyperactive Learning (HAL) Python interface for building Atomic Cluster Expansion potentials. <code>Unlicensed</code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACEHAL) (👨‍💻 3 · 🔀 2 · 📋 10 - 40% open · ⏱️ 21.09.2023):

	```
	git clone https://github.com/ACEsuit/ACEHAL
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/mir-group/flare_pp">flare++</a></b> (🥈10 ·  ⭐ 34 · 💀) - A many-body extension of the FLARE code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C++</code> <code>ML-IAP</code>
</details>
<br>

## Biomolecules

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on biomolecules, protein structure, protein folding, etc. using atomistic ML._

<details><summary><b><a href="https://github.com/google-deepmind/alphafold">AlphaFold</a></b> (🥇21 ·  ⭐ 11K · 📉) - Open source code for AlphaFold. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-deepmind/alphafold) (👨‍💻 19 · 🔀 1.9K · 📦 6 · 📋 740 - 23% open · ⏱️ 10.08.2023):

	```
	git clone https://github.com/deepmind/alphafold
	```
</details>
<details><summary><b><a href="https://github.com/dptech-corp/Uni-Fold">Uni-Fold</a></b> (🥉15 ·  ⭐ 300) - An open-source platform for developing protein models beyond AlphaFold. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dptech-corp/Uni-Fold) (👨‍💻 7 · 🔀 52 · 📥 2.4K · 📋 61 - 21% open · ⏱️ 18.09.2023):

	```
	git clone https://github.com/dptech-corp/Uni-Fold
	```
</details>
<br>

## Community resources

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that collect atomistic ML resources or foster communication within community._

🔗&nbsp;<b><a href="https://www.air4.science/map">AI for Science Map</a></b>  - Interactive mindmap of the AI4Science research field, including atomistic machine learning, including papers,..

🔗&nbsp;<b><a href="https://cortner.github.io/ACEweb/">Atomic Cluster Expansion</a></b>  - Atomic Cluster Expansion (ACE) community homepage.

🔗&nbsp;<b><a href="https://crystallm.com">CrystaLLM</a></b>  - Generate a crystal structure from a composition. <a href="https://en.wikipedia.org/wiki/Language_model"><code>LM</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>pre-trained</code>

🔗&nbsp;<b><a href="https://matsci.org/">matsci.org</a></b>  - A community forum for the discussion of anything materials science, with a focus on computational materials science..

🔗&nbsp;<b><a href="https://mattermodeling.stackexchange.com/questions/tagged/machine-learning">Matter Modeling Stack Exchange - Machine Learning</a></b>  - Forum StackExchange, site Matter Modeling, ML-tagged questions.

<details><summary><b><a href="https://github.com/ml-tooling/best-of-ml-python">Best-of Machine Learning with Python</a></b> (🥇23 ·  ⭐ 15K · 📈) - A ranked list of awesome machine learning Python libraries. Updated weekly. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code> <code>general-ml</code> <code>Python</code></summary>

- [GitHub](https://github.com/ml-tooling/best-of-ml-python) (👨‍💻 44 · 🔀 2.1K · 📋 48 - 31% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/ml-tooling/best-of-ml-python
	```
</details>
<details><summary><b><a href="https://github.com/naganandy/graph-based-deep-learning-literature">Graph-based Deep Learning Literature</a></b> (🥈18 ·  ⭐ 4.4K) - links to conference publications in graph-based deep learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>general-ml</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/naganandy/graph-based-deep-learning-literature) (👨‍💻 12 · 🔀 710 · ⏱️ 13.10.2023):

	```
	git clone https://github.com/naganandy/graph-based-deep-learning-literature
	```
</details>
<details><summary><b><a href="https://github.com/materialsproject/matbench">MatBench</a></b> (🥈17 ·  ⭐ 84) - Matbench: Benchmarks for materials science property prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code> <code>benchmarking</code></summary>

- [GitHub](https://github.com/materialsproject/matbench) (👨‍💻 23 · 🔀 31 · 📦 11 · 📋 57 - 54% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/materialsproject/matbench
	```
- [PyPi](https://pypi.org/project/matbench) (📥 120 / month):
	```
	pip install matbench
	```
</details>
<details><summary><b><a href="https://github.com/janosh/matbench-discovery">MatBench Discovery</a></b> (🥉15 ·  ⭐ 37) - An evaluation framework for machine learning models simulating high-throughput materials discovery. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code> <code>benchmarking</code></summary>

- [GitHub](https://github.com/janosh/matbench-discovery) (👨‍💻 5 · 🔀 5 · 📋 24 - 20% open · ⏱️ 17.10.2023):

	```
	git clone https://github.com/janosh/matbench-discovery
	```
- [PyPi](https://pypi.org/project/matbench-discovery) (📥 35 / month):
	```
	pip install matbench-discovery
	```
</details>
<details><summary><b><a href="https://github.com/divelab/AIRS/blob/main/Overview/resources.md">AI for Science Resources</a></b> (🥉12 ·  ⭐ 260 · 📉) - List of resources for AI4Science research, including learning resources. <code><a href="https://tldrlegal.com/search?q=GPL-3.0%20license">GPL-3.0 license</a></code></summary>

- [GitHub](https://github.com/divelab/AIRS) (👨‍💻 23 · 🔀 33 · ⏱️ 10.10.2023):

	```
	git clone https://github.com/divelab/AIRS
	```
</details>
<details><summary><b><a href="https://github.com/tilde-lab/awesome-materials-informatics">Awesome Materials Informatics</a></b> (🥉10 ·  ⭐ 310) - Curated list of known efforts in materials informatics = modern materials science. <code><a href="https://github.com/tilde-lab/awesome-materials-informatics#license">Custom</a></code></summary>

- [GitHub](https://github.com/tilde-lab/awesome-materials-informatics) (👨‍💻 18 · 🔀 74 · ⏱️ 21.08.2023):

	```
	git clone https://github.com/tilde-lab/awesome-materials-informatics
	```
</details>
<details><summary><b><a href="https://github.com/sedaoturak/data-resources-for-materials-science">The Collection of Database and Dataset Resources in Materials Science</a></b> (🥉7 ·  ⭐ 170) - A list of databases, datasets and books/handbooks where you can find materials properties for machine learning.. <code>Unlicensed</code> <code>datasets</code></summary>

- [GitHub](https://github.com/sedaoturak/data-resources-for-materials-science) (👨‍💻 2 · 🔀 26 · ⏱️ 28.09.2023):

	```
	git clone https://github.com/sedaoturak/data-resources-for-materials-science
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/ncfrey/resources">A Highly Opinionated List of Open-Source Materials Informatics Resources</a></b> (🥉7 ·  ⭐ 95 · 💀) - A Highly Opinionated List of Open Source Materials Informatics Resources. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/topics/materials-informatics">GitHub topic materials-informatics</a></b> -  <code>Unlicensed</code>
- <b><a href="https://ma.issp.u-tokyo.ac.jp/en/">MateriApps</a></b> -  <code>Unlicensed</code>
</details>
<br>

## Datasets

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Datasets, databases and trained models for atomistic ML._

🔗&nbsp;<b><a href="https://www.catalysis-hub.org/">Catalysis Hub</a></b>  - A web-platform for sharing data and software for computational catalysis research!.

🔗&nbsp;<b><a href="https://citrination.com/">Citrination Datasets</a></b>  - AI-Powered Materials Data Platform. Open Citrination has been decommissioned.

🔗&nbsp;<b><a href="https://crystals.ai/">crystals.ai</a></b>  - Curated datasets for reproducible AI in materials science.

🔗&nbsp;<b><a href="https://huggingface.co/DeepChem">DeepChem Models</a></b>  - DeepChem models on HuggingFace. <code>pre-trained</code> <a href="https://en.wikipedia.org/wiki/Language_model"><code>LM</code></a>

🔗&nbsp;<b><a href="https://pages.nist.gov/jarvis_leaderboard/">JARVIS-Leaderboard</a></b> ( ⭐ 41)  - This project provides benchmark-performances for materials science applications including Artificial Intelligence.. <code>benchmarking</code>

🔗&nbsp;<b><a href="https://materialsproject.org/ml/charge_densities">Materials Project - Charge Densities</a></b>  - Materials Project has started offering charge density information available for download via their public API.

🔗&nbsp;<b><a href="https://matterverse.ai/">matterverse.ai</a></b>  - Database of yet-to-be-sythesized materials predicted using state-of-the-art machine learning algorithms.

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">Quantum-Machine.org Datasets</a></b>  - Collection of datasets, including QM7, QM9, etc. MD, DFT. Small organic molecules, mostly.

🔗&nbsp;<b><a href="http://sgdml.org/#datasets">sGDML Datasets</a></b>  - MD17, MD22, DFT datasets.

<details><summary><b><a href="https://github.com/materialsproject/MPContribs">MPContribs</a></b> (🥇23 ·  ⭐ 32) - Platform for materials scientists to contribute and disseminate their materials data through Materials Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/materialsproject/MPContribs) (👨‍💻 25 · 🔀 19 · 📦 23 · 📋 98 - 20% open · ⏱️ 18.10.2023):

	```
	git clone https://github.com/materialsproject/MPContribs
	```
- [PyPi](https://pypi.org/project/mpcontribs-client) (📥 4K / month):
	```
	pip install mpcontribs-client
	```
</details>
<details><summary><b><a href="https://github.com/Open-Catalyst-Project/ocp/blob/main/DATASET.md">Open Catalyst datasets</a></b> (🥇18 ·  ⭐ 480) - The datasets of the Open Catalyst project, OC20, OC22. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code></summary>

- [GitHub](https://github.com/Open-Catalyst-Project/ocp) (👨‍💻 32 · 🔀 170 · 📋 140 - 7% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/Open-Catalyst-Project/ocp
	```
</details>
<details><summary><b><a href="https://github.com/Materials-Consortia/OPTIMADE">Open Databases Integration for Materials Design (OPTIMADE)</a></b> (🥈15 ·  ⭐ 62) - Specification of a common REST API for access to materials databases. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code></summary>

- [GitHub](https://github.com/Materials-Consortia/OPTIMADE) (👨‍💻 19 · 🔀 35 · 📋 220 - 33% open · ⏱️ 22.06.2023):

	```
	git clone https://github.com/Materials-Consortia/OPTIMADE
	```
</details>
<details><summary><b><a href="https://github.com/openmm/spice-dataset">SPICE</a></b> (🥈13 ·  ⭐ 95) - A collection of QM data for training potential functions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a></summary>

- [GitHub](https://github.com/openmm/spice-dataset) (🔀 5 · 📥 220 · 📋 47 - 25% open · ⏱️ 17.10.2023):

	```
	git clone https://github.com/openmm/spice-dataset
	```
</details>
<details><summary><b><a href="https://github.com/drcassar/SciGlass">SciGlass</a></b> (🥉6 ·  ⭐ 6) - The database contains a vast set of data on the properties of glass materials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/drcassar/SciGlass) (👨‍💻 2 · 🔀 3 · 📥 1 · ⏱️ 27.08.2023):

	```
	git clone https://github.com/drcassar/SciGlass
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://openkim.org/">OpenKIM</a></b> (🥈11 ·  ⭐ 29 · 💀) - The Open Knowledgebase of Interatomic Models (OpenKIM) aims to be an online resource for standardized testing, long-.. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <a href="https://en.wikipedia.org/wiki/Knowledge_base"><code>knowledge-base</code></a> <code>pre-trained</code>
- <b><a href="https://github.com/HSE-LAMBDA/ai4material_design/blob/main/docs/DATA.md">2DMD dataset</a></b> (🥈9 ·  ⭐ 1) - Code for Kazeev, N., Al-Maeeni, A.R., Romanov, I. et al. Sparse representation for machine learning the properties of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Crystallographic_defect"><code>material-defect</code></a>
- <b><a href="https://github.com/isayev/ANI1_dataset">ANI-1 Dataset</a></b> (🥉8 ·  ⭐ 90 · 💀) - A data set of 20 million calculated off-equilibrium conformations for organic molecules. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepchem/moleculenet">MoleculeNet Leaderboard</a></b> (🥉8 ·  ⭐ 73 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/aiqm/ANI1x_datasets">ANI-1x Datasets</a></b> (🥉6 ·  ⭐ 45 · 💀) - The ANI-1ccx and ANI-1x data sets, coupled-cluster and density functional theory properties for organic molecules. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/isayev/COMP6">COMP6 Benchmark dataset</a></b> (🥉6 ·  ⭐ 36 · 💀) - COMP6 Benchmark dataset for ML potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/learningmatter-mit/geom">GEOM</a></b> (🥉5 ·  ⭐ 140 · 💀) - GEOM: Energy-annotated molecular conformations. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>
- <b><a href="https://github.com/BingqingCheng/linear-regression-benchmarks">linear-regression-benchmarks</a></b> (🥉5 ·  ⭐ 1 · 💀) - Data sets used for linear regression benchmarks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code> <code>single-paper</code>
- <b><a href="https://github.com/aimat-lab/3DSC">3DSC Database</a></b> (🥉4 ·  ⭐ 7) - Repo for the paper publishing the superconductor database with 3D crystal structures. <code><a href="https://github.com/aimat-lab/3DSC/blob/main/LICENSE.md">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Superconductivity"><code>superconductors</code></a> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a>
- <b><a href="https://github.com/aimat-lab/visual_graph_datasets">Visual Graph Datasets</a></b> (🥉4 ·  ⭐ 1 · 🐣) - Datasets for the training of graph neural networks (GNNs) and subsequent visualization of attributional explanations.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Data Structures

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on providing data structures used in atomistic machine learning._

<details><summary><b><a href="https://github.com/deepmodeling/dpdata">dpdata</a></b> (🥇22 ·  ⭐ 140) - Manipulating multiple atomic simulation data formats, including DeePMD-kit, VASP, LAMMPS, ABACUS, etc. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/dpdata) (👨‍💻 51 · 🔀 100 · 📦 100 · 📋 74 - 21% open · ⏱️ 08.09.2023):

	```
	git clone https://github.com/deepmodeling/dpdata
	```
- [PyPi](https://pypi.org/project/dpdata) (📥 6.7K / month):
	```
	pip install dpdata
	```
- [Conda](https://anaconda.org/deepmodeling/dpdata) (📥 140 · ⏱️ 27.09.2023):
	```
	conda install -c deepmodeling dpdata
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/metatensor">Metatensor</a></b> (🥉18 ·  ⭐ 25 · 📈) - Self-describing sparse tensor data format for atomistic machine learning and beyond. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/metatensor) (👨‍💻 17 · 🔀 12 · 📥 610 · 📦 4 · 📋 110 - 33% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/lab-cosmo/metatensor
	```
</details>
<details><summary><b><a href="https://github.com/materialsproject/pyrho">mp-pyrho</a></b> (🥉14 ·  ⭐ 28 · 💤) - Tools for re-griding volumetric quantum chemistry data for machine-learning purposes. <code><a href="https://github.com/materialsproject/pyrho">Custom</a></code> <code>ML-DFT</code></summary>

- [GitHub](https://github.com/materialsproject/pyrho) (👨‍💻 8 · 🔀 6 · 📦 18 · 📋 4 - 25% open · ⏱️ 21.03.2023):

	```
	git clone https://github.com/materialsproject/pyrho
	```
- [PyPi](https://pypi.org/project/mp-pyrho) (📥 71 / month):
	```
	pip install mp-pyrho
	```
</details>
<br>

## Density functional theory (ML-DFT)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of DFT, such as density functional approximations (ML-DFA), the charge density, density of states, the Hamiltonian, etc._

<details><summary><b><a href="https://github.com/deepmind/deepmind-research/tree/master/density_functional_approximation_dm21">DM21</a></b> (🥇20 ·  ⭐ 12K) - This package provides a PySCF interface to the DM21 (DeepMind 21) family of exchange-correlation functionals described.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-deepmind/deepmind-research) (👨‍💻 92 · 🔀 2.4K · 📋 290 - 54% open · ⏱️ 02.06.2023):

	```
	git clone https://github.com/deepmind/deepmind-research
	```
</details>
<details><summary><b><a href="https://github.com/mala-project/mala">MALA</a></b> (🥇18 ·  ⭐ 53) - Materials Learning Algorithms. A framework for machine learning materials properties from first-principles data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mala-project/mala) (👨‍💻 41 · 🔀 20 · 📋 240 - 11% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/mala-project/mala
	```
</details>
<details><summary><b><a href="https://github.com/mzjb/DeepH-pack">DeepH-pack</a></b> (🥈13 ·  ⭐ 140) - Deep neural networks for density functional theory Hamiltonian. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/mzjb/DeepH-pack) (👨‍💻 6 · 🔀 27 · 📋 36 - 13% open · ⏱️ 11.07.2023):

	```
	git clone https://github.com/mzjb/DeepH-pack
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/deepks-kit">DeePKS-kit</a></b> (🥈10 ·  ⭐ 94) - a package for developing machine learning-based chemically accurate energy and density functional models. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/deepks-kit) (👨‍💻 6 · 🔀 30 · 📋 10 - 10% open · ⏱️ 01.04.2023):

	```
	git clone https://github.com/deepmodeling/deepks-kit
	```
</details>
<details><summary><b><a href="https://github.com/andreagrisafi/SALTED">SALTED</a></b> (🥈8 ·  ⭐ 13) - Symmetry-Adapted Learning of Three-dimensional Electron Densities. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/andreagrisafi/SALTED) (👨‍💻 12 · 🔀 2 · 📋 2 - 50% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/andreagrisafi/SALTED
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEhamiltonians.jl">ACEhamiltonians</a></b> (🥈7 ·  ⭐ 8) - Provides tools for constructing, fitting, and predicting self-consistent Hamiltonian and overlap matrices in solid-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACEhamiltonians.jl) (👨‍💻 4 · 🔀 3 · 📋 4 - 25% open · ⏱️ 12.04.2023):

	```
	git clone https://github.com/ACEsuit/ACEhamiltonians.jl
	```
</details>
<details><summary><b><a href="https://github.com/peterbjorgensen/DeepDFT">DeepDFT</a></b> (🥉6 ·  ⭐ 38 · 💤) - Official implementation of DeepDFT model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/peterbjorgensen/DeepDFT) (👨‍💻 2 · 🔀 7 · ⏱️ 28.02.2023):

	```
	git clone https://github.com/peterbjorgensen/DeepDFT
	```
</details>
<details><summary><b><a href="https://github.com/Xiaoxun-Gong/DeepH-E3">DeepH-E3</a></b> (🥉6 ·  ⭐ 31) - General framework for E(3)-equivariant neural network representation of density functional theory Hamiltonian. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>magnetism</code></summary>

- [GitHub](https://github.com/Xiaoxun-Gong/DeepH-E3) (👨‍💻 2 · 🔀 8 · 📋 8 - 25% open · ⏱️ 04.04.2023):

	```
	git clone https://github.com/Xiaoxun-Gong/DeepH-E3
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/semodi/neuralxc">NeuralXC</a></b> (🥈10 ·  ⭐ 28 · 💀) - Implementation of a machine learned density functional. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/biklooost/PROPhet">PROPhet</a></b> (🥈9 ·  ⭐ 60 · 💀) - PROPhet is a code to integrate machine learning techniques with first-principles quantum chemistry approaches. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>single-paper</code> <code>C++</code>
- <b><a href="https://github.com/semodi/libnxc">Libnxc</a></b> (🥈7 ·  ⭐ 14 · 💀) - A library for using machine-learned exchange-correlation functionals for density-functional theory. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code>C++</code> <code>Fortran</code>
- <b><a href="https://github.com/ulissigroup/charge-density-models">charge-density-models</a></b> (🥉4 ·  ⭐ 4) - Tools to build charge density models using ocpmodels. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/jmargraf/gprep">gprep</a></b> (🥉4 · 💀) - Fitting DFTB repulsive potentials with GPR. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/MihailBogojeski/ml-dft">ML-DFT</a></b> (🥉3 ·  ⭐ 18 · 💀) - A package for density functional approximation using machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/foxjas/CSNN">CSNN</a></b> (🥉3 ·  ⭐ 1 · 💤) - Primary codebase of CSNN - Concentric Spherical Neural Network for 3D Representation Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mala-project/malada">MALADA</a></b> (🥉3) - MALA Data Acquisition: Helpful tools to build data for MALA. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mzjb/xDeepH">xDeepH</a></b> (🥉2 ·  ⭐ 19) - Extended DeepH (xDeepH) method for magnetic materials. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>magnetism</code> <code>Julia</code>
- <b><a href="https://github.com/siddarthachar/deepcdp">DeepCDP</a></b> (🥉2 ·  ⭐ 2) - DeepCDP: Deep learning Charge Density Prediction. <code>Unlicensed</code>
- <b><a href="https://gitlab.com/jmargraf/kdf">kdft</a></b> (🥉1 ·  ⭐ 2 · 💀) - The Kernel Density Functional (KDF) code allows generating ML based DFT functionals. <code>Unlicensed</code>
</details>
<br>

## Educational Resources

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tutorials, guides, cookbooks, recipes, etc._

🔗&nbsp;<b><a href="https://www.elsevier.com/books-and-journals/book-companion/9780323900492">Quantum Chemistry in the Age of Machine Learning</a></b>  - Book, 2022.

<details><summary><b><a href="https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks">jarvis-tools-notebooks</a></b> (🥇12 ·  ⭐ 40) - A Google-Colab Notebook Collection for Materials Design: https://jarvis.nist.gov/. <code><a href="https://tldrlegal.com/search?q=NIST">NIST</a></code></summary>

- [GitHub](https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks) (👨‍💻 5 · 🔀 21 · ⏱️ 16.10.2023):

	```
	git clone https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks
	```
</details>
<details><summary><b><a href="https://dmol.pub/">Deep Learning for Molecules and Materials Book</a></b> (🥇11 ·  ⭐ 540) - Deep learning for molecules and materials book. <code><a href="https://github.com/whitead/dmol-book/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/whitead/dmol-book) (👨‍💻 19 · 🔀 100 · 📋 160 - 17% open · ⏱️ 02.07.2023):

	```
	git clone https://github.com/whitead/dmol-book
	```
</details>
<details><summary><b><a href="https://github.com/rdkit/rdkit-tutorials">RDKit Tutorials</a></b> (🥈8 ·  ⭐ 210 · 💤) - Tutorials to learn how to work with the RDKit. <code><a href="https://github.com/rdkit/rdkit-tutorials/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/rdkit/rdkit-tutorials) (👨‍💻 5 · 🔀 67 · 📋 4 - 75% open · ⏱️ 19.03.2023):

	```
	git clone https://github.com/rdkit/rdkit-tutorials
	```
</details>
<details><summary><b><a href="https://github.com/ceriottm/iam-notebooks">iam-notebooks</a></b> (🥈8 ·  ⭐ 19) - Jupyter notebooks for the lectures of the Introduction to Atomistic Modeling. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ceriottm/iam-notebooks) (👨‍💻 6 · 🔀 4 · ⏱️ 07.08.2023):

	```
	git clone https://github.com/ceriottm/iam-notebooks
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/DoE_Course_Material">Data Handling, DoE and Statistical Analysis for Material Chemists</a></b> (🥉5 · 🐣) - Notebooks for workshops of DoE course, hosted by the Computational Materials Chemistry group at Uppsala University. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/DoE_Course_Material) (👨‍💻 3 · 🔀 13 · ⏱️ 26.06.2023):

	```
	git clone https://github.com/Teoroo-CMC/DoE_Course_Material
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/deepchem/DeepLearningLifeSciences">DeepLearningLifeSciences</a></b> (🥇11 ·  ⭐ 310 · 💀) - Example code from the book Deep Learning for the Life Sciences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aimat-lab/MAChINE">MAChINE</a></b> (🥈10 ·  ⭐ 1 · 🐣) - Client-Server Web App to introduce usage of ML in materials science to beginners. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/anthony-wang/BestPractices">BestPractices</a></b> (🥈6 ·  ⭐ 140 · 💀) - Things that you should (and should not) do in your Materials Informatics research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/WardLT/applied-ai-for-materials">Applied AI for Materials</a></b> (🥈6 ·  ⭐ 48 · 💀) - Course materials for Applied AI for Materials Science and Engineering. <code>Unlicensed</code>
- <b><a href="https://github.com/lab-cosmo/software-cookbook">COSMO Software Cookbook</a></b> (🥈6 ·  ⭐ 3 · 🐣) - The COSMO cookbook contains recipes for atomic-scale modelling for materials and molecules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/deepmodeling/AI4Science101">AI4Science101</a></b> (🥉5 ·  ⭐ 73 · 💀) - AI for Science. <code>Unlicensed</code>
- <b><a href="https://github.com/CompPhysVienna/MLSummerSchoolVienna2022">Machine Learning for Materials Hard and Soft</a></b> (🥉5 ·  ⭐ 32 · 💀) - ESI-DCAFM-TACO-VDSP Summer School on Machine Learning for Materials Hard and Soft. <code>Unlicensed</code>
- <b><a href="https://github.com/BingqingCheng/ML-in-chemistry-101">ML-in-chemistry-101</a></b> (🥉4 ·  ⭐ 56 · 💀) - The course materials for Machine Learning in Chemistry 101. <code>Unlicensed</code>
- <b><a href="https://github.com/gabor1/chemrev-gpr">chemrev-gpr</a></b> (🥉4 ·  ⭐ 6 · 💀) - Notebooks accompanying the paper on GPR in materials and molecules in Chemical Reviews 2020. <code>Unlicensed</code>
- <b><a href="https://github.com/bfocassio/MLDensity_tutorial">MLDensity_tutorial</a></b> (🥉2 ·  ⭐ 6 · 💤) - Tutorial files to work with ML for the charge density in molecules and solids. <code>Unlicensed</code>
- <b><a href="https://github.com/mala-project/mala_tutorial">MALA Tutorial</a></b> (🥉2 ·  ⭐ 2 · 💤) - A full MALA hands-on tutorial. <code>Unlicensed</code>
- <b><a href="https://github.com/Teoroo-CMC/PiNN_lab">PiNN Lab</a></b> (🥉1 ·  ⭐ 2) -  <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
</details>
<br>

## Explainable Artificial intelligence (XAI)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on explainability and model interpretability in atomistic ML._

<details><summary><b><a href="https://github.com/ur-whitelab/exmol">exmol</a></b> (🥇20 ·  ⭐ 260) - Explainer for black box models that predict molecule properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ur-whitelab/exmol) (👨‍💻 7 · 🔀 40 · 📦 12 · 📋 67 - 14% open · ⏱️ 19.06.2023):

	```
	git clone https://github.com/ur-whitelab/exmol
	```
- [PyPi](https://pypi.org/project/exmol) (📥 560 / month):
	```
	pip install exmol
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/aimat-lab/graph_attention_student">MEGAN: Multi Explanation Graph Attention Student</a></b> (🥈6 ·  ⭐ 2) - Minimal implementation of graph attention student model architecture. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aimat-lab/graph_attention_student">MEGAN</a></b> (🥈6 ·  ⭐ 2) - Minimal implementation of graph attention student model architecture. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Explainable_artificial_intelligence"><code>XAI</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/CitrineInformatics-ERD-public/linear-vs-blackbox">Linear vs blackbox</a></b> (🥉3 ·  ⭐ 1 · 💤) - Code and data related to the publication: Interpretable models for extrapolation in scientific machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Explainable_artificial_intelligence"><code>XAI</code></a> <code>single-paper</code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a>
</details>
<br>

## Electronic structure methods (ML-ESM)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of electronic structure methods, which do not fit into either of the categories ML-WFT or ML-DFT._

<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/masashitsubaki/QuantumDeepField_molecule">QDF for molecule</a></b> (🥇9 ·  ⭐ 170 · 💀) - Quantum deep field: data-driven wave function, electron density generation, and energy prediction and extrapolation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/muhrin/e3psi">e3psi</a></b> (🥉3 ·  ⭐ 2) - Equivariant machine learning library for learning from electronic structures. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code>
</details>
<br>

## General Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General tools for atomistic machine learning._

<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥇36 ·  ⭐ 4.7K) - Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry, Materials Science and Biology. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 230 · 🔀 1.5K · 📦 270 · 📋 1.6K - 25% open · ⏱️ 17.10.2023):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 16K / month):
	```
	pip install deepchem
	```
- [Conda](https://anaconda.org/conda-forge/deepchem) (📥 100K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge deepchem
	```
- [Docker Hub](https://hub.docker.com/r/deepchemio/deepchem) (📥 7K · ⭐ 4 · ⏱️ 11.03.2022):
	```
	docker pull deepchemio/deepchem
	```
</details>
<details><summary><b><a href="https://github.com/rdkit/rdkit">RDKit</a></b> (🥇30 ·  ⭐ 2.2K) -  <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/rdkit/rdkit) (👨‍💻 200 · 🔀 770 · 📥 1.4K · 📦 2 · 📋 2.9K - 29% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/rdkit/rdkit
	```
- [PyPi](https://pypi.org/project/rdkit) (📥 230K / month):
	```
	pip install rdkit
	```
- [Conda](https://anaconda.org/rdkit/rdkit) (📥 2.5M · ⏱️ 16.06.2023):
	```
	conda install -c rdkit rdkit
	```
</details>
<details><summary><b><a href="https://github.com/hackingmaterials/matminer">Matminer</a></b> (🥇28 ·  ⭐ 420) - Data mining for materials science. <code><a href="https://github.com/hackingmaterials/matminer/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/hackingmaterials/matminer) (👨‍💻 49 · 🔀 170 · 📦 230 · 📋 210 - 12% open · ⏱️ 11.09.2023):

	```
	git clone https://github.com/hackingmaterials/matminer
	```
- [PyPi](https://pypi.org/project/matminer) (📥 17K / month):
	```
	pip install matminer
	```
- [Conda](https://anaconda.org/conda-forge/matminer) (📥 51K · ⏱️ 27.06.2023):
	```
	conda install -c conda-forge matminer
	```
</details>
<details><summary><b><a href="https://github.com/libAtoms/QUIP">QUIP</a></b> (🥈24 ·  ⭐ 300 · 📉) - libAtoms/QUIP molecular dynamics framework: https://libatoms.github.io. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code></summary>

- [GitHub](https://github.com/libAtoms/QUIP) (👨‍💻 80 · 🔀 120 · 📥 350 · 📦 24 · 📋 430 - 20% open · ⏱️ 29.08.2023):

	```
	git clone https://github.com/libAtoms/QUIP
	```
- [PyPi](https://pypi.org/project/quippy-ase) (📥 2.3K / month):
	```
	pip install quippy-ase
	```
- [Docker Hub](https://hub.docker.com/r/libatomsquip/quip) (📥 9.9K · ⭐ 4 · ⏱️ 24.04.2023):
	```
	docker pull libatomsquip/quip
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/maml">MAML</a></b> (🥈23 ·  ⭐ 280) - Python for Materials Machine Learning, Materials Descriptors, Machine Learning Force Fields, Deep Learning, etc. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/maml) (👨‍💻 29 · 🔀 57 · 📦 4 · 📋 64 - 6% open · ⏱️ 13.10.2023):

	```
	git clone https://github.com/materialsvirtuallab/maml
	```
- [PyPi](https://pypi.org/project/maml) (📥 130 / month):
	```
	pip install maml
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/jarvis">JARVIS-Tools</a></b> (🥈22 ·  ⭐ 250) - JARVIS-Tools: an open-source software package for data-driven atomistic materials design. Publications:.. <code><a href="https://github.com/usnistgov/jarvis/blob/master/LICENSE.rst">Custom</a></code></summary>

- [GitHub](https://github.com/usnistgov/jarvis) (👨‍💻 15 · 🔀 110 · 📦 64 · 📋 82 - 47% open · ⏱️ 22.09.2023):

	```
	git clone https://github.com/usnistgov/jarvis
	```
- [PyPi](https://pypi.org/project/jarvis-tools) (📥 1.9K / month):
	```
	pip install jarvis-tools
	```
- [Conda](https://anaconda.org/conda-forge/jarvis-tools) (📥 57K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jarvis-tools
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/scikit-matter">Scikit-Matter</a></b> (🥈19 ·  ⭐ 61) - A collection of scikit-learn compatible utilities that implement methods born out of the materials science and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>scikit-learn</code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/scikit-matter) (👨‍💻 13 · 🔀 15 · 📦 6 · 📋 68 - 17% open · ⏱️ 22.09.2023):

	```
	git clone https://github.com/scikit-learn-contrib/scikit-matter
	```
- [PyPi](https://pypi.org/project/skmatter) (📥 1.1K / month):
	```
	pip install skmatter
	```
- [Conda](https://anaconda.org/conda-forge/skmatter) (📥 580 · ⏱️ 24.08.2023):
	```
	conda install -c conda-forge skmatter
	```
</details>
<details><summary><b><a href="https://github.com/uw-cmg/MAST-ML">MAST-ML</a></b> (🥈17 ·  ⭐ 87) - MAterials Simulation Toolkit for Machine Learning (MAST-ML). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/uw-cmg/MAST-ML) (👨‍💻 19 · 🔀 51 · 📥 82 · 📦 6 · 📋 210 - 10% open · ⏱️ 28.07.2023):

	```
	git clone https://github.com/uw-cmg/MAST-ML
	```
</details>
<details><summary><b><a href="https://github.com/yoshida-lab/XenonPy">XenonPy</a></b> (🥈16 ·  ⭐ 110) - XenonPy is a Python Software for Materials Informatics. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yoshida-lab/XenonPy) (👨‍💻 10 · 🔀 56 · 📥 1.2K · 📋 82 - 19% open · ⏱️ 21.05.2023):

	```
	git clone https://github.com/yoshida-lab/XenonPy
	```
- [PyPi](https://pypi.org/project/xenonpy) (📥 220 / month):
	```
	pip install xenonpy
	```
</details>
<details><summary><b><a href="https://github.com/divelab/AIRS">Artificial Intelligence for Science (AIRS)</a></b> (🥉12 ·  ⭐ 260) - Artificial Intelligence for Science (AIRS). <code><a href="https://tldrlegal.com/search?q=GPL-3.0%20license">GPL-3.0 license</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>ML-DFT</code> <code>ML-WFT</code> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a></summary>

- [GitHub](https://github.com/divelab/AIRS) (👨‍💻 23 · 🔀 33 · ⏱️ 10.10.2023):

	```
	git clone https://github.com/divelab/AIRS
	```
</details>
<details><summary><b><a href="https://github.com/ulissigroup/amptorch">AMPtorch</a></b> (🥉12 ·  ⭐ 56) - AMPtorch: Atomistic Machine Learning Package (AMP) - PyTorch. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/ulissigroup/amptorch) (👨‍💻 14 · 🔀 31 · 📋 31 - 16% open · ⏱️ 16.07.2023):

	```
	git clone https://github.com/ulissigroup/amptorch
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/qmlcode/qml">QML</a></b> (🥉15 ·  ⭐ 190 · 💀) - QML: Quantum Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/hackingmaterials/automatminer">Automatminer</a></b> (🥉14 ·  ⭐ 130 · 💀) - An automatic engine for predicting materials properties. <code><a href="https://github.com/hackingmaterials/automatminer/blob/main/LICENSE">Custom</a></code>
- <b><a href="https://github.com/Mariewelt/OpenChem">OpenChem</a></b> (🥉10 ·  ⭐ 620 · 💀) - OpenChem: Deep Learning toolkit for Computational Chemistry and Drug Design Research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lab-cosmo/equisolve">Equisolve</a></b> (🥉8 ·  ⭐ 4) - A package tasked with taking equistore objects and computing machine learning models using them. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>ML-IAP</code>
- <b><a href="https://github.com/deepchem/jaxchem">JAXChem</a></b> (🥉7 ·  ⭐ 75 · 💀) - JAXChem is a JAX-based deep learning library for complex and versatile chemical modeling. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ulissigroup/uncertainty_benchmarking">uncertainty_benchmarking</a></b> (🥉7 ·  ⭐ 34 · 💀) - Various code/notebooks to benchmark different ways we could estimate uncertainty in ML predictions. <code>Unlicensed</code> <code>benchmarking</code> <code>probabilistic</code>
- <b><a href="https://github.com/deepchem/torchchem">torchchem</a></b> (🥉7 ·  ⭐ 34 · 💀) - An experimental repo for experimenting with PyTorch models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ACEsuit/ACEatoms.jl">ACEatoms</a></b> (🥉4 ·  ⭐ 2 · 💤) - Generic code for modelling atomic properties using ACE. <code><a href="https://github.com/ACEsuit/ACEatoms.jl/blob/main/ASL.md">Custom</a></code> <code>Julia</code>
- <b><a href="https://bitbucket.org/wolverton/magpie/">Magpie</a></b> (🥉3) - Materials Agnostic Platform for Informatics and Exploration (Magpie). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Java</code>
- <b><a href="http://mlatom.com/">MLatom</a></b> (🥉3) - Machine learning for atomistic simulations. <code><a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">Custom</a></code>
- <b><a href="https://github.com/hgheiberger/quantum-structure-ml">quantum-structure-ml</a></b> (🥉2 ·  ⭐ 1 · 💤) - Multi-class classification model for predicting the magnetic order of magnetic structures and a binary classification.. <code>Unlicensed</code> <code>magnetism</code> <code>benchmarking</code>
</details>
<br>

## Generative Models

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement generative models for atomistic ML._

<details><summary><b><a href="https://github.com/GT4SD/gt4sd-core">GT4SD</a></b> (🥇18 ·  ⭐ 270) - GT4SD, an open-source library to accelerate hypothesis generation in the scientific discovery process. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pre-trained</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/GT4SD/gt4sd-core) (👨‍💻 19 · 🔀 55 · 📋 93 - 2% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/GT4SD/gt4sd-core
	```
- [PyPi](https://pypi.org/project/gt4sd) (📥 500 / month):
	```
	pip install gt4sd
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/molecule-generation">MoLeR</a></b> (🥈16 ·  ⭐ 210) - Implementation of MoLeR: a generative model of molecular graphs which supports scaffold-constrained generation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/molecule-generation) (👨‍💻 5 · 🔀 33 · 📋 31 - 22% open · ⏱️ 09.08.2023):

	```
	git clone https://github.com/microsoft/molecule-generation
	```
- [PyPi](https://pypi.org/project/molecule-generation) (📥 240 / month):
	```
	pip install molecule-generation
	```
</details>
<details><summary><b><a href="https://github.com/whitead/synspace">synspace</a></b> (🥈11 ·  ⭐ 30) - Synthesis generative model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/whitead/synspace) (👨‍💻 2 · 🔀 3 · 📦 5 · 📋 3 - 66% open · ⏱️ 15.04.2023):

	```
	git clone https://github.com/whitead/synspace
	```
- [PyPi](https://pypi.org/project/synspace) (📥 480 / month):
	```
	pip install synspace
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/schnetpack-gschnet">SchNetPack G-SchNet</a></b> (🥈10 ·  ⭐ 28) - G-SchNet extension for SchNetPack. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/schnetpack-gschnet) (👨‍💻 3 · 🔀 6 · ⏱️ 01.06.2023):

	```
	git clone https://github.com/atomistic-machine-learning/schnetpack-gschnet
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/G-SchNet">G-SchNet</a></b> (🥉8 ·  ⭐ 120 · 💤) - G-SchNet - a generative model for 3d molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/G-SchNet) (👨‍💻 2 · 🔀 23 · ⏱️ 24.03.2023):

	```
	git clone https://github.com/atomistic-machine-learning/G-SchNet
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/cG-SchNet">cG-SchNet</a></b> (🥉8 ·  ⭐ 43 · 💤) - cG-SchNet - a conditional generative neural network for 3d molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/cG-SchNet) (🔀 13 · ⏱️ 24.03.2023):

	```
	git clone https://github.com/atomistic-machine-learning/cG-SchNet
	```
</details>
<details><summary><b><a href="https://github.com/tsudalab/bVAE-IM">bVAE-IM</a></b> (🥉7 ·  ⭐ 8) - Implementation of Chemical Design with GPU-based Ising Machine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Quantum_machine_learning"><code>QML</code></a> <code>single-paper</code></summary>

- [GitHub](https://github.com/tsudalab/bVAE-IM) (🔀 2 · ⏱️ 11.07.2023):

	```
	git clone https://github.com/tsudalab/bVAE-IM
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/ehoogeboom/e3_diffusion_for_molecules">EDM</a></b> (🥉9 ·  ⭐ 310 · 💀) - E(3) Equivariant Diffusion Model for Molecule Generation in 3D. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tsudalab/rxngenerator">rxngenerator</a></b> (🥉5 ·  ⭐ 12 · 💀) - A generative model for molecular generation via multi-step chemical reactions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tsudalab/MolSLEPA">MolSLEPA</a></b> (🥉5 ·  ⭐ 4 · 🐣) - Interpretable Fragment-based Molecule Design with Self-learning Entropic Population Annealing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Explainable_artificial_intelligence"><code>XAI</code></a>
</details>
<br>

## Interatomic Potentials (ML-IAP)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Machine learning interatomic potentials (aka ML-IAP, MLIAP, MLIP, MLP) and force fields (ML-FF) for molecular dynamics._

<details><summary><b><a href="https://github.com/deepmodeling/deepmd-kit">DeePMD-kit</a></b> (🥇28 ·  ⭐ 1.2K) - A deep learning package for many-body potential energy representation and molecular dynamics. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/deepmodeling/deepmd-kit) (👨‍💻 62 · 🔀 430 · 📥 27K · 📦 11 · 📋 460 - 5% open · ⏱️ 13.10.2023):

	```
	git clone https://github.com/deepmodeling/deepmd-kit
	```
- [PyPi](https://pypi.org/project/deepmd-kit) (📥 1.4K / month):
	```
	pip install deepmd-kit
	```
- [Conda](https://anaconda.org/deepmodeling/deepmd-kit) (📥 1.4K · ⏱️ 13.10.2023):
	```
	conda install -c deepmodeling deepmd-kit
	```
- [Docker Hub](https://hub.docker.com/r/deepmodeling/deepmd-kit) (📥 2K · ⭐ 1 · ⏱️ 15.10.2023):
	```
	docker pull deepmodeling/deepmd-kit
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/megnet">MEGNet</a></b> (🥇21 ·  ⭐ 460) - Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/megnet) (👨‍💻 13 · 🔀 140 · 📦 71 · 📋 74 - 22% open · ⏱️ 27.04.2023):

	```
	git clone https://github.com/materialsvirtuallab/megnet
	```
- [PyPi](https://pypi.org/project/megnet) (📥 260 / month):
	```
	pip install megnet
	```
</details>
<details><summary><b><a href="https://github.com/aiqm/torchani">TorchANI</a></b> (🥇21 ·  ⭐ 400 · 💤) - Accurate Neural Network Potential on PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aiqm/torchani) (👨‍💻 16 · 🔀 110 · 📦 26 · 📋 160 - 12% open · ⏱️ 21.03.2023):

	```
	git clone https://github.com/aiqm/torchani
	```
- [PyPi](https://pypi.org/project/torchani) (📥 1.9K / month):
	```
	pip install torchani
	```
- [Conda](https://anaconda.org/conda-forge/torchani) (📥 220K · ⏱️ 25.06.2023):
	```
	conda install -c conda-forge torchani
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/dpgen">DP-GEN</a></b> (🥇21 ·  ⭐ 240 · 💤) - The deep potential generator to generate a deep-learning based model of interatomic potential energy and force field. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>workflows</code></summary>

- [GitHub](https://github.com/deepmodeling/dpgen) (👨‍💻 59 · 🔀 160 · 📥 1.5K · 📦 4 · 📋 250 - 13% open · ⏱️ 21.03.2023):

	```
	git clone https://github.com/deepmodeling/dpgen
	```
- [PyPi](https://pypi.org/project/dpgen) (📥 290 / month):
	```
	pip install dpgen
	```
- [Conda](https://anaconda.org/deepmodeling/dpgen) (📥 190 · ⏱️ 16.06.2023):
	```
	conda install -c deepmodeling dpgen
	```
</details>
<details><summary><b><a href="https://github.com/CederGroupHub/chgnet">CHGNet</a></b> (🥇21 ·  ⭐ 120 · 📈) - Pretrained universal neural network potential for charge-informed atomistic modeling https://chgnet.lbl.gov. <code><a href="https://github.com/CederGroupHub/chgnet/blob/main/LICENSE">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>pre-trained</code> <code>electrostatics</code> <code>magnetism</code> <code>structure-relaxation</code></summary>

- [GitHub](https://github.com/CederGroupHub/chgnet) (👨‍💻 7 · 🔀 23 · 📦 9 · 📋 22 - 4% open · ⏱️ 14.10.2023):

	```
	git clone https://github.com/CederGroupHub/chgnet
	```
- [PyPi](https://pypi.org/project/chgnet) (📥 8.2K / month):
	```
	pip install chgnet
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/nequip">NequIP</a></b> (🥇20 ·  ⭐ 450 · 💤) - NequIP is a code for building E(3)-equivariant interatomic potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mir-group/nequip) (👨‍💻 8 · 🔀 99 · 📦 15 · 📋 61 - 19% open · ⏱️ 26.03.2023):

	```
	git clone https://github.com/mir-group/nequip
	```
- [PyPi](https://pypi.org/project/nequip) (📥 490 / month):
	```
	pip install nequip
	```
- [Conda](https://anaconda.org/conda-forge/nequip) (📥 3.5K · ⏱️ 18.06.2023):
	```
	conda install -c conda-forge nequip
	```
</details>
<details><summary><b><a href="https://github.com/Open-Catalyst-Project/ocp/blob/main/MODELS.md">Pre-trained OCP models</a></b> (🥈19 ·  ⭐ 480) - Pre-trained models released as part of the Open Catalyst Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pre-trained</code></summary>

- [GitHub](https://github.com/Open-Catalyst-Project/ocp) (👨‍💻 32 · 🔀 170 · 📋 140 - 7% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/Open-Catalyst-Project/ocp
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/m3gnet">M3GNet</a></b> (🥈17 ·  ⭐ 180) - Materials graph network with 3-body interactions featuring a DFT surrogate crystal relaxer and a state-of-the-art.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/m3gnet) (👨‍💻 14 · 🔀 51 · 📦 18 · 📋 35 - 42% open · ⏱️ 06.06.2023):

	```
	git clone https://github.com/materialsvirtuallab/m3gnet
	```
- [PyPi](https://pypi.org/project/m3gnet) (📥 420 / month):
	```
	pip install m3gnet
	```
</details>
<details><summary><b><a href="https://github.com/stefanch/sGDML">sGDML</a></b> (🥈16 ·  ⭐ 130) - sGDML - Reference implementation of the Symmetric Gradient Domain Machine Learning model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/stefanch/sGDML) (👨‍💻 8 · 🔀 34 · 📦 8 · 📋 16 - 31% open · ⏱️ 31.08.2023):

	```
	git clone https://github.com/stefanch/sGDML
	```
- [PyPi](https://pypi.org/project/sgdml) (📥 130 / month):
	```
	pip install sgdml
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace">MACE</a></b> (🥈14 ·  ⭐ 200) - MACE - Fast and accurate machine learning interatomic potentials with higher order equivariant message passing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace) (👨‍💻 12 · 🔀 69 · 📋 82 - 30% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/ACEsuit/mace
	```
</details>
<details><summary><b><a href="https://github.com/MaterSim/PyXtal_FF">PyXtalFF</a></b> (🥈14 ·  ⭐ 74) - Machine Learning Interatomic Potential Predictions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MaterSim/PyXtal_FF) (👨‍💻 8 · 🔀 19 · 📋 60 - 15% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/MaterSim/PyXtal_FF
	```
- [PyPi](https://pypi.org/project/pyxtal_ff) (📥 32 / month):
	```
	pip install pyxtal_ff
	```
</details>
<details><summary><b><a href="https://github.com/openmm/NNPOps">NNPOps</a></b> (🥈14 ·  ⭐ 67) - High-performance operations for neural network potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>C++</code></summary>

- [GitHub](https://github.com/openmm/NNPOps) (👨‍💻 7 · 🔀 16 · 📋 53 - 37% open · ⏱️ 25.07.2023):

	```
	git clone https://github.com/openmm/NNPOps
	```
- [Conda](https://anaconda.org/conda-forge/nnpops) (📥 69K · ⏱️ 14.10.2023):
	```
	conda install -c conda-forge nnpops
	```
</details>
<details><summary><b><a href="https://github.com/uf3/uf3">Ultra-Fast Force Fields (UF3)</a></b> (🥈14 ·  ⭐ 43) - UF3: a python library for generating ultra-fast interatomic potentials. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uf3/uf3) (👨‍💻 8 · 🔀 16 · 📋 32 - 40% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/uf3/uf3
	```
- [PyPi](https://pypi.org/project/uf3) (📥 10 / month):
	```
	pip install uf3
	```
</details>
<details><summary><b><a href="https://github.com/openkim/kliff">KLIFF</a></b> (🥈14 ·  ⭐ 27) - KIM-based Learning-Integrated Fitting Framework (KLIFF). <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <code>probabilistic</code> <code>workflows</code></summary>

- [GitHub](https://github.com/openkim/kliff) (👨‍💻 10 · 🔀 17 · 📋 33 - 51% open · ⏱️ 28.08.2023):

	```
	git clone https://github.com/openkim/kliff
	```
- [PyPi](https://pypi.org/project/kliff) (📥 63 / month):
	```
	pip install kliff
	```
- [Conda](https://anaconda.org/conda-forge/kliff) (📥 64K · ⏱️ 07.10.2023):
	```
	conda install -c conda-forge kliff
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/CCS">CCS_fit</a></b> (🥈13 ·  ⭐ 5) - Curvature Constrained Splines. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/CCS) (👨‍💻 8 · 🔀 9 · 📥 380 · 📋 14 - 57% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/Teoroo-CMC/CCS
	```
- [PyPi](https://pypi.org/project/ccs_fit) (📥 300 / month):
	```
	pip install ccs_fit
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/DMFF">DMFF</a></b> (🥈12 ·  ⭐ 110 · 💤) - DMFF (Differentiable Molecular Force Field) is a Jax-based python package that provides a full differentiable.. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/DMFF) (👨‍💻 7 · 🔀 29 · 📋 19 - 63% open · ⏱️ 14.02.2023):

	```
	git clone https://github.com/deepmodeling/DMFF
	```
</details>
<details><summary><b><a href="https://cortner.github.io/ACEweb/software/">Pacemaker</a></b> (🥈12 ·  ⭐ 47) - Python package for fitting atomic cluster expansion (ACE) potentials. <code><a href="https://github.com/ICAMS/python-ace/blob/master/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/ICAMS/python-ace) (👨‍💻 5 · 🔀 12 · 📋 37 - 27% open · ⏱️ 29.09.2023):

	```
	git clone https://github.com/ICAMS/python-ace
	```
- [PyPi](https://pypi.org/project/python-ace) (📥 4 / month):
	```
	pip install python-ace
	```
</details>
<details><summary><b><a href="https://github.com/thorben-frank/mlff">So3krates (MLFF)</a></b> (🥈12 ·  ⭐ 38) - Build neural networks for machine learning force fields with JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thorben-frank/mlff) (👨‍💻 3 · 🔀 6 · 📋 7 - 42% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/thorben-frank/mlff
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/PiNN">PiNN</a></b> (🥉11 ·  ⭐ 98) - A Python library for building atomic neural networks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/PiNN) (👨‍💻 2 · 🔀 26 · 📋 6 - 16% open · ⏱️ 28.09.2023):

	```
	git clone https://github.com/Teoroo-CMC/PiNN
	```
- [Docker Hub](https://hub.docker.com/r/teoroo/pinn) (📥 220 · ⏱️ 19.10.2023):
	```
	docker pull teoroo/pinn
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEfit.jl">ACEfit</a></b> (🥉11 ·  ⭐ 5) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACEfit.jl) (👨‍💻 6 · 🔀 3 · 📋 54 - 40% open · ⏱️ 18.08.2023):

	```
	git clone https://github.com/ACEsuit/ACEfit.jl
	```
</details>
<details><summary><b><a href="https://github.com/gasteigerjo/dimenet">DimeNet</a></b> (🥉10 ·  ⭐ 250) - DimeNet and DimeNet++ models, as proposed in Directional Message Passing for Molecular Graphs (ICLR 2020) and Fast and.. <code><a href="https://github.com/gasteigerjo/dimenet/blob/master/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/gasteigerjo/dimenet) (👨‍💻 2 · 🔀 53 · 📦 1 · 📋 30 - 3% open · ⏱️ 03.10.2023):

	```
	git clone https://github.com/gasteigerjo/dimenet
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/allegro">Allegro</a></b> (🥉9 ·  ⭐ 240) - Allegro is an open-source code for building highly scalable and accurate equivariant deep learning interatomic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mir-group/allegro) (👨‍💻 2 · 🔀 34 · 📋 20 - 35% open · ⏱️ 08.05.2023):

	```
	git clone https://github.com/mir-group/allegro
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/NeuralForceField">Neural Force Field</a></b> (🥉9 ·  ⭐ 190) - Neural Network Force Field based on PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pre-trained</code></summary>

- [GitHub](https://github.com/learningmatter-mit/NeuralForceField) (👨‍💻 10 · 🔀 41 · ⏱️ 25.07.2023):

	```
	git clone https://github.com/learningmatter-mit/NeuralForceField
	```
</details>
<details><summary><b><a href="https://github.com/TUM-DAML/gemnet_pytorch">GemNet</a></b> (🥉9 ·  ⭐ 150) - GemNet model in PyTorch, as proposed in GemNet: Universal Directional Graph Neural Networks for Molecules (NeurIPS.. <code><a href="https://github.com/TUM-DAML/gemnet_pytorch/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/TUM-DAML/gemnet_pytorch) (👨‍💻 5 · 🔀 25 · ⏱️ 26.04.2023):

	```
	git clone https://github.com/TUM-DAML/gemnet_pytorch
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACE.jl">ACE.jl</a></b> (🥉9 ·  ⭐ 62) - Parameterisation of Equivariant Properties of Particle Systems. <code><a href="https://github.com/ACEsuit/ACE.jl/blob/main/license/mit.md">Custom</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACE.jl) (👨‍💻 12 · 🔀 14 · 📋 81 - 28% open · ⏱️ 09.06.2023):

	```
	git clone https://github.com/ACEsuit/ACE.jl
	```
</details>
<details><summary><b><a href="https://acesuit.github.io/">ACE1.jl</a></b> (🥉9 ·  ⭐ 19) - Atomic Cluster Expansion for Modelling Invariant Atomic Properties. <code><a href="https://github.com/ACEsuit/ACE1.jl/blob/main/ASL.md">Custom</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACE1.jl) (👨‍💻 7 · 🔀 4 · 📋 45 - 46% open · ⏱️ 19.09.2023):

	```
	git clone https://github.com/ACEsuit/ACE1.jl
	```
</details>
<details><summary><b><a href="https://github.com/libAtoms/workflow">wfl</a></b> (🥉9 ·  ⭐ 15) - Workflow is a Python toolkit for building interatomic potential creation and atomistic simulation workflows. <code>Unlicensed</code> <code>workflows</code> <a href="https://en.wikipedia.org/wiki/High-throughput_computing"><code>HTC</code></a></summary>

- [GitHub](https://github.com/libAtoms/workflow) (👨‍💻 13 · 🔀 13 · 📋 130 - 46% open · ⏱️ 18.10.2023):

	```
	git clone https://github.com/libAtoms/workflow
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/NNsForMD">NNsforMD</a></b> (🥉9 ·  ⭐ 10 · 💤) - Neural network class for molecular dynamics to predict potential energy, forces and non-adiabatic couplings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aimat-lab/NNsForMD) (👨‍💻 2 · 🔀 3 · ⏱️ 10.11.2022):

	```
	git clone https://github.com/aimat-lab/NNsForMD
	```
- [PyPi](https://pypi.org/project/pyNNsMD) (📥 11 / month):
	```
	pip install pyNNsMD
	```
</details>
<details><summary><b><a href="https://libatoms.github.io/">GAP</a></b> (🥉8 ·  ⭐ 32) - Gaussian Approximation Potential (GAP). <code><a href="https://github.com/libAtoms/GAP/blob/main/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/libAtoms/GAP) (👨‍💻 12 · 🔀 20 · ⏱️ 15.10.2023):

	```
	git clone https://github.com/libAtoms/GAP
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/Atomistic-Adversarial-Attacks">Atomistic Adversarial Attacks</a></b> (🥉8 ·  ⭐ 24 · 💤) - Code for performing adversarial attacks on atomistic systems using NN potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code></summary>

- [GitHub](https://github.com/learningmatter-mit/Atomistic-Adversarial-Attacks) (👨‍💻 6 · 🔀 6 · ⏱️ 03.10.2022):

	```
	git clone https://github.com/learningmatter-mit/Atomistic-Adversarial-Attacks
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACE1pack.jl">ACE1Pack.jl</a></b> (🥉8 · 🐣) - Provides convenience functionality for the usage of ACE1.jl, ACEfit.jl, JuLIP.jl for fitting interatomic potentials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACE1pack.jl) (👨‍💻 11 · ⏱️ 21.08.2023):

	```
	git clone https://github.com/ACEsuit/ACE1pack.jl
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace-jax">MACE-Jax</a></b> (🥉6 ·  ⭐ 35) - Equivariant machine learning interatomic potentials in JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace-jax) (👨‍💻 2 · 🔀 1 · ⏱️ 04.10.2023):

	```
	git clone https://github.com/ACEsuit/mace-jax
	```
</details>
<details><summary><b><a href="https://github.com/lanl/ALF">ALF</a></b> (🥉6 ·  ⭐ 20) - A framework for performing active learning for training machine-learned interatomic potentials. <code><a href="https://github.com/lanl/ALF/blob/main/LICENSE">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a></summary>

- [GitHub](https://github.com/lanl/ALF) (👨‍💻 5 · 🔀 7 · ⏱️ 04.08.2023):

	```
	git clone https://github.com/lanl/alf
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEworkflows">ACE Workflows</a></b> (🥉6 · 🐣) - Workflow Examples for ACE Models. <code>Unlicensed</code> <code>Julia</code> <code>workflows</code></summary>

- [GitHub](https://github.com/ACEsuit/ACEworkflows) (👨‍💻 5 · 🔀 1 · ⏱️ 12.10.2023):

	```
	git clone https://github.com/ACEsuit/ACEworkflows
	```
</details>
<details><summary><b><a href="https://gitlab.com/ashapeev/mlip-3">MLIP-3</a></b> (🥉5 ·  ⭐ 15 · 🐣) - MLIP-3: Active learning on atomic environments with Moment Tensor Potentials (MTP). <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code>C++</code></summary>

- [GitLab](https://gitlab.com/ashapeev/mlip-3) (🔀 3 · 📋 18 - 77% open · ⏱️ 24.04.2023):

	```
	git clone https://gitlab.com/ashapeev/mlip-3
	```
</details>
<details><summary>Show 16 hidden projects...</summary>

- <b><a href="https://github.com/CompPhysVienna/n2p2">n2p2</a></b> (🥈13 ·  ⭐ 190 · 💀) - n2p2 - A Neural Network Potential Package. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>C++</code>
- <b><a href="https://github.com/jparkhill/TensorMol">TensorMol</a></b> (🥈12 ·  ⭐ 260 · 💀) - Tensorflow + Molecules = TensorMol. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>single-paper</code>
- <b><a href="https://github.com/isayev/ASE_ANI">ANI-1</a></b> (🥈12 ·  ⭐ 210 · 💀) - ANI-1 neural net potential with python interface (ASE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/MDIL-SNU/SIMPLE-NN">SIMPLE-NN</a></b> (🥉11 ·  ⭐ 43 · 💀) - SIMPLE-NN(SNU Interatomic Machine-learning PotentiaL packagE version Neural Network). <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/SchNet">SchNet</a></b> (🥉9 ·  ⭐ 180 · 💀) - SchNet - a deep learning architecture for quantum chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/materialsvirtuallab/snap">SNAP</a></b> (🥉8 ·  ⭐ 32 · 💀) - Repository for spectral neighbor analysis potential (SNAP) model development. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/MDIL-SNU/SIMPLE-NN_v2">SIMPLE-NN v2</a></b> (🥉8 ·  ⭐ 28) -  <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/MMunibas/PhysNet">PhysNet</a></b> (🥉7 ·  ⭐ 80 · 💀) - Code for training PhysNet models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>electrostatics</code>
- <b><a href="https://github.com/aiqm/aimnet">AIMNet</a></b> (🥉7 ·  ⭐ 77 · 💀) - Atoms In Molecules Neural Network Potential. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/libAtoms/testing-framework">testing-framework</a></b> (🥉6 ·  ⭐ 11 · 💀) - The purpose of this repository is to aid the testing of a large number of interatomic potentials for a variety of.. <code>Unlicensed</code> <code>benchmarking</code>
- <b><a href="https://gitlab.com/PANNAdevs/panna">PANNA</a></b> (🥉6 ·  ⭐ 7 · 💀) - A package to train and validate all-to-all connected network models for BP[1] and modified-BP[2] type local atomic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/Luthaf/alchemical-learning">Alchemical learning</a></b> (🥉5 ·  ⭐ 2) - Code for the Modeling high-entropy transition metal alloys with alchemical compression article. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/sirmarcel/glp">glp</a></b> (🥉4 ·  ⭐ 12) - tools for graph-based machine-learning potentials in jax. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://cortner.github.io/ACEweb/software/">TensorPotential</a></b> (🥉4 ·  ⭐ 5) - Tensorpotential is a TensorFlow based tool for development, fitting ML interatomic potentials from electronic.. <code><a href="https://github.com/ICAMS/TensorPotential/blob/main/LICENSE.md">Custom</a></code>
- <b><a href="https://github.com/lmj1029123/SingleNN">SingleNN</a></b> (🥉2 ·  ⭐ 7 · 💀) - An efficient package for training and executing neural-network interatomic potentials. <code>Unlicensed</code> <code>C++</code>
- <b><a href="https://www.uni-goettingen.de/de/560580.html">RuNNer</a></b> (🥉2) - The RuNNer Neural Network Energy Representation is a Fortran-based framework for the construction of Behler-.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>Fortran</code>
</details>
<br>

## Language Models

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that use (large) language models (LMs, LLMs) or natural language procesing (NLP) techniques for atomistic ML._

<details><summary><b><a href="https://github.com/whitead/paper-qa">paper-qa</a></b> (🥇25 ·  ⭐ 3.1K) - LLM Chain for answering questions from documents with citations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/whitead/paper-qa) (👨‍💻 12 · 🔀 280 · 📦 34 · 📋 100 - 39% open · ⏱️ 19.09.2023):

	```
	git clone https://github.com/whitead/paper-qa
	```
- [PyPi](https://pypi.org/project/paper-qa) (📥 3.4K / month):
	```
	pip install paper-qa
	```
</details>
<details><summary><b><a href="https://github.com/kjappelbaum/gptchem">gptchem</a></b> (🥈13 ·  ⭐ 160) - Use GPT-3 to solve chemistry problems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kjappelbaum/gptchem) (👨‍💻 2 · 🔀 30 · 📋 17 - 88% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/kjappelbaum/gptchem
	```
- [PyPi](https://pypi.org/project/gptchem) (📥 310 / month):
	```
	pip install gptchem
	```
</details>
<details><summary><b><a href="https://github.com/materialsintelligence/mat2vec">mat2vec</a></b> (🥈12 ·  ⭐ 600) - Supplementary Materials for Tshitoyan et al. Unsupervised word embeddings capture latent knowledge from materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/materialsintelligence/mat2vec) (👨‍💻 5 · 🔀 170 · 📋 23 - 26% open · ⏱️ 06.05.2023):

	```
	git clone https://github.com/materialsintelligence/mat2vec
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/molskill">MolSkill</a></b> (🥉11 ·  ⭐ 81) - Learning chemical intuition from humans in the loop. Supporting code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Recommender_system"><code>recommender</code></a></summary>

- [GitHub](https://github.com/microsoft/molskill) (👨‍💻 4 · 🔀 5 · 📋 5 - 40% open · ⏱️ 13.06.2023):

	```
	git clone https://github.com/microsoft/molskill
	```
- [Conda](https://anaconda.org/msr-ai4science/molskill) (📥 120 · ⏱️ 18.06.2023):
	```
	conda install -c msr-ai4science molskill
	```
</details>
<details><summary><b><a href="https://github.com/whitead/nlcc">nlcc</a></b> (🥉10 ·  ⭐ 41 · 💤) - Natural language computational chemistry command line interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code></summary>

- [GitHub](https://github.com/whitead/nlcc) (👨‍💻 3 · 🔀 6 · ⏱️ 04.02.2023):

	```
	git clone https://github.com/whitead/nlcc
	```
- [PyPi](https://pypi.org/project/nlcc) (📥 10 / month):
	```
	pip install nlcc
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/StefanoSanvitoGroup/BERT-PSIE-TC">BERT-PSIE-TC</a></b> (🥉4 ·  ⭐ 2) - A dataset of Curie temperatures automatically extracted from scientific literature with the use of the BERT-PSIE.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>magnetism</code>
</details>
<br>

## Materials Discovery

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement materials discovery methods using atomistic ML._

<details><summary><b><a href="https://github.com/CompRhys/aviary">aviary</a></b> (🥇13 ·  ⭐ 29) - The Wren sits on its Roost in the Aviary. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CompRhys/aviary) (👨‍💻 7 · 🔀 7 · 📋 26 - 15% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/CompRhys/aviary
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://gitlab.com/cest-group/boss">BOSS</a></b> (🥈7 ·  ⭐ 18 · 💀) - Bayesian Optimization Structure Search (BOSS). <code>Unlicensed</code> <code>probabilistic</code>
- <b><a href="https://gitlab.com/agox/agox">AGOX</a></b> (🥈6 ·  ⭐ 10 · 💀) - AGOX is a package for global optimization of atomic system using e.g. the energy calculated from density functional.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a>
- <b><a href="https://github.com/ulissigroup/CAMD">Computational Autonomy for Materials Discovery (CAMD)</a></b> (🥈6 ·  ⭐ 1 · 💤) - Agent-based sequential learning software for materials discovery. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/aced-differentiate/closed-loop-acceleration-benchmarks">closed-loop-acceleration-benchmarks</a></b> (🥉4) - Data and scripts in support of the publication By how much can closed-loop frameworks accelerate computational.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <code>single-paper</code>
- <b><a href="https://github.com/Minoru938/CSPML">CSPML (crystal structure prediction with machine learning-based element substitution)</a></b> (🥉3 ·  ⭐ 12 · 💀) - Original implementation of CSPML. <code>Unlicensed</code> <code>structure-prediction</code>
- <b><a href="https://github.com/MDIL-SNU/SPINNER">SPINNER</a></b> (🥉3 ·  ⭐ 9 · 💀) - SPINNER (Structure Prediction of Inorganic crystals using Neural Network potentials with Evolutionary and Random.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>C++</code> <code>structure-prediction</code>
- <b><a href="https://github.com/CitrineInformatics-ERD-public/sl_discovery">sl_discovery</a></b> (🥉3 ·  ⭐ 5 · 💤) - Data processing and models related to Quantifying the performance of machine learning models in materials discovery. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <code>single-paper</code>
</details>
<br>

## Mathematical tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement mathematical objects used in atomistic machine learning._

<details><summary><b><a href="https://github.com/google-deepmind/kfac-jax">KFAC-JAX</a></b> (🥇18 ·  ⭐ 160) - Second Order Optimization and Curvature Estimation with K-FAC in JAX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-deepmind/kfac-jax) (👨‍💻 11 · 🔀 13 · 📦 8 · 📋 9 - 11% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/deepmind/kfac-jax
	```
- [PyPi](https://pypi.org/project/kfac-jax) (📥 780 / month):
	```
	pip install kfac-jax
	```
</details>
<details><summary><b><a href="https://github.com/ziatdinovmax/gpax">gpax</a></b> (🥈16 ·  ⭐ 140) - Gaussian Processes for Experimental Sciences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a></summary>

- [GitHub](https://github.com/ziatdinovmax/gpax) (👨‍💻 2 · 🔀 16 · 📋 17 - 35% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/ziatdinovmax/gpax
	```
- [PyPi](https://pypi.org/project/gpax) (📥 200 / month):
	```
	pip install gpax
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/Polynomials4ML.jl">Polynomials4ML.jl</a></b> (🥈15 ·  ⭐ 11) - Polynomials for ML: fast evaluation, batching, differentiation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/Polynomials4ML.jl) (👨‍💻 8 · 🔀 4 · 📋 43 - 37% open · ⏱️ 08.10.2023):

	```
	git clone https://github.com/ACEsuit/Polynomials4ML.jl
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/sphericart">SpheriCart</a></b> (🥈12 ·  ⭐ 42) - Multi-language library for the calculation of spherical harmonics in Cartesian coordinates. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/sphericart) (👨‍💻 7 · 🔀 3 · 📥 1 · 📦 1 · 📋 14 - 50% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/lab-cosmo/sphericart
	```
- [PyPi](https://pypi.org/project/sphericart) (📥 120 / month):
	```
	pip install sphericart
	```
</details>
<details><summary><b><a href="https://github.com/risi-kondor/GElib">GElib</a></b> (🥉7 ·  ⭐ 16) - C++/CUDA library for SO(3) equivariant operations. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/risi-kondor/GElib) (👨‍💻 3 · 🔀 2 · 📋 5 - 80% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/risi-kondor/GElib
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/toolbox">COSMO Toolbox</a></b> (🥉6 ·  ⭐ 6) - Assorted libraries and utilities for atomistic simulation analysis. <code>Unlicensed</code> <code>C++</code></summary>

- [GitHub](https://github.com/lab-cosmo/toolbox) (👨‍💻 9 · 🔀 5 · ⏱️ 23.06.2023):

	```
	git clone https://github.com/lab-cosmo/toolbox
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/aced-differentiate/EquivariantOperators.jl">EquivariantOperators.jl</a></b> (🥉6 ·  ⭐ 17) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code>
- <b><a href="https://github.com/risi-kondor/cnine">cnine</a></b> (🥉4 ·  ⭐ 2) - Cnine tensor library. <code>Unlicensed</code> <code>C++</code>
- <b><a href="https://github.com/lab-cosmo/wigner_kernels">Wigner Kernels</a></b> (🥉2 ·  ⭐ 1) - Collection of programs to benchmark Wigner kernels. <code>Unlicensed</code> <code>benchmarking</code>
</details>
<br>

## Molecular Dynamics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that simplify the integration of molecular dynamics and atomistic machine learning._

<details><summary><b><a href="https://github.com/jax-md/jax-md">JAX-MD</a></b> (🥇23 ·  ⭐ 1K) - Differentiable, Hardware Accelerated, Molecular Dynamics. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jax-md/jax-md) (👨‍💻 28 · 🔀 160 · 📦 35 · 📋 140 - 45% open · ⏱️ 29.08.2023):

	```
	git clone https://github.com/jax-md/jax-md
	```
- [PyPi](https://pypi.org/project/jax-md) (📥 1.2K / month):
	```
	pip install jax-md
	```
</details>
<details><summary><b><a href="https://github.com/FitSNAP/FitSNAP">FitSNAP</a></b> (🥈19 ·  ⭐ 120) - Software for generating SNAP machine-learning interatomic potentials. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code></summary>

- [GitHub](https://github.com/FitSNAP/FitSNAP) (👨‍💻 24 · 🔀 44 · 📥 7 · 📋 63 - 12% open · ⏱️ 18.10.2023):

	```
	git clone https://github.com/FitSNAP/FitSNAP
	```
- [Conda](https://anaconda.org/conda-forge/fitsnap3) (📥 4.8K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge fitsnap3
	```
</details>
<details><summary><b><a href="https://github.com/openmm/openmm-torch">openmm-torch</a></b> (🥈15 ·  ⭐ 130) - OpenMM plugin to define forces with neural networks. <code><a href="https://github.com/openmm/openmm-torch#license">Custom</a></code> <code>ML-IAP</code> <code>C++</code></summary>

- [GitHub](https://github.com/openmm/openmm-torch) (👨‍💻 7 · 🔀 24 · 📋 70 - 22% open · ⏱️ 03.10.2023):

	```
	git clone https://github.com/openmm/openmm-torch
	```
- [Conda](https://anaconda.org/conda-forge/openmm-torch) (📥 220K · ⏱️ 10.10.2023):
	```
	conda install -c conda-forge openmm-torch
	```
</details>
<details><summary><b><a href="https://github.com/openmm/openmm-ml">OpenMM-ML</a></b> (🥉11 ·  ⭐ 53) - High level API for using machine learning models in OpenMM simulations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code></summary>

- [GitHub](https://github.com/openmm/openmm-ml) (👨‍💻 2 · 🔀 15 · 📋 40 - 52% open · ⏱️ 21.08.2023):

	```
	git clone https://github.com/openmm/openmm-ml
	```
- [Conda](https://anaconda.org/conda-forge/openmm-ml) (📥 2.2K · ⏱️ 21.08.2023):
	```
	conda install -c conda-forge openmm-ml
	```
</details>
<details><summary><b><a href="https://github.com/ICAMS/lammps-user-pace">PACE</a></b> (🥉10 ·  ⭐ 21) - The LAMMPS ML-IAP `pair_style pace`, aka Atomic Cluster Expansion (ACE), aka ML-PACE,.. <code><a href="https://github.com/ICAMS/lammps-user-pace/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/ICAMS/lammps-user-pace) (👨‍💻 6 · 🔀 10 · 📋 6 - 16% open · ⏱️ 13.10.2023):

	```
	git clone https://github.com/ICAMS/lammps-user-pace
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://gitlab.com/ivannovikov/interface-lammps-mlip-3">interface-lammps-mlip-3</a></b> (🥉4 ·  ⭐ 5 · 🐣) - An interface between LAMMPS and MLIP (version 3). <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code>
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

- <b><a href="https://github.com/isayev/ReLeaSE">ReLeaSE</a></b> (🥇11 ·  ⭐ 310 · 💀) - Deep Reinforcement Learning for de-novo Drug Design. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>
- <b><a href="https://github.com/ulissigroup/catgym">CatGym</a></b> (🥉6 ·  ⭐ 10 · 💀) - Surface segregation using Deep Reinforcement Learning. <code><a href="https://tldrlegal.com/search?q=GPL">GPL</a></code>
</details>
<br>

## Representation Engineering

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that offer implementations of representations aka descriptors, fingerprints of atomistic systems, and models built with them, aka feature engineering._

<details><summary><b><a href="https://github.com/cdk/cdk">cdk</a></b> (🥇25 ·  ⭐ 440) - The Chemistry Development Kit. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <code>Java</code></summary>

- [GitHub](https://github.com/cdk/cdk) (👨‍💻 160 · 🔀 150 · 📥 16K · 📦 18 · 📋 260 - 8% open · ⏱️ 17.10.2023):

	```
	git clone https://github.com/cdk/cdk
	```
- [Maven](https://search.maven.org/artifact/org.openscience.cdk/cdk-bundle):
	```
	<dependency>
		<groupId>org.openscience.cdk</groupId>
		<artifactId>cdk-bundle</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/SINGROUP/dscribe">DScribe</a></b> (🥇22 ·  ⭐ 350 · 📉) - DScribe is a python package for creating machine learning descriptors for atomistic systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SINGROUP/dscribe) (👨‍💻 18 · 🔀 79 · 📦 150 · 📋 85 - 9% open · ⏱️ 05.09.2023):

	```
	git clone https://github.com/SINGROUP/dscribe
	```
- [PyPi](https://pypi.org/project/dscribe) (📥 26K / month):
	```
	pip install dscribe
	```
- [Conda](https://anaconda.org/conda-forge/dscribe) (📥 79K · ⏱️ 06.09.2023):
	```
	conda install -c conda-forge dscribe
	```
</details>
<details><summary><b><a href="https://github.com/SUNCAT-Center/CatLearn">CatLearn</a></b> (🥇15 ·  ⭐ 94 · 💤) -  <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Surface_science"><code>surface-science</code></a></summary>

- [GitHub](https://github.com/SUNCAT-Center/CatLearn) (👨‍💻 22 · 🔀 51 · 📦 4 · 📋 26 - 38% open · ⏱️ 07.02.2023):

	```
	git clone https://github.com/SUNCAT-Center/CatLearn
	```
- [PyPi](https://pypi.org/project/catlearn) (📥 100 / month):
	```
	pip install catlearn
	```
</details>
<details><summary><b><a href="https://github.com/ppdebreuck/modnet">MODNet</a></b> (🥇15 ·  ⭐ 59 · 📉) - MODNet: a framework for machine learning materials properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pre-trained</code> <code>small-data</code> <a href="https://en.wikipedia.org/wiki/Transfer_learning"><code>transfer-learning</code></a></summary>

- [GitHub](https://github.com/ppdebreuck/modnet) (👨‍💻 7 · 🔀 26 · 📦 4 · 📋 35 - 37% open · ⏱️ 29.07.2023):

	```
	git clone https://github.com/ppdebreuck/modnet
	```
</details>
<details><summary><b><a href="https://github.com/rouyang2017/SISSO">SISSO</a></b> (🥈14 ·  ⭐ 180) - A data-driven method combining symbolic regression and compressed sensing for accurate & interpretable models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>Fortran</code></summary>

- [GitHub](https://github.com/rouyang2017/SISSO) (👨‍💻 3 · 🔀 62 · 📋 52 - 3% open · ⏱️ 12.09.2023):

	```
	git clone https://github.com/rouyang2017/SISSO
	```
</details>
<details><summary><b><a href="https://github.com/drcassar/glasspy">GlassPy</a></b> (🥈14 ·  ⭐ 16) - Python module for scientists working with glass materials. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/drcassar/glasspy) (🔀 6 · 📦 2 · 📋 4 - 25% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/drcassar/glasspy
	```
- [PyPi](https://pypi.org/project/glasspy) (📥 200 / month):
	```
	pip install glasspy
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/librascal">Librascal</a></b> (🥈13 ·  ⭐ 71) - A scalable and versatile library to generate representations for atomic-scale learning. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/librascal) (👨‍💻 29 · 🔀 18 · 📋 230 - 43% open · ⏱️ 06.06.2023):

	```
	git clone https://github.com/lab-cosmo/librascal
	```
</details>
<details><summary><b><a href="https://github.com/Luthaf/rascaline">Rascaline</a></b> (🥈13 ·  ⭐ 23) - Computing representations for atomistic machine learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>Rust</code> <code>C++</code></summary>

- [GitHub](https://github.com/Luthaf/rascaline) (👨‍💻 12 · 🔀 12 · 📋 41 - 48% open · ⏱️ 18.10.2023):

	```
	git clone https://github.com/Luthaf/rascaline
	```
</details>
<details><summary><b><a href="https://github.com/capoe/benchml">BenchML</a></b> (🥉7 ·  ⭐ 13) - ML benchmarking and pipeling framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>benchmarking</code></summary>

- [GitHub](https://github.com/capoe/benchml) (👨‍💻 9 · 🔀 2 · 📋 13 - 23% open · ⏱️ 24.05.2023):

	```
	git clone https://github.com/capoe/benchml
	```
- [PyPi](https://pypi.org/project/benchml) (📥 20 / month):
	```
	pip install benchml
	```
</details>
<details><summary><b><a href="https://github.com/muhrin/milad">milad</a></b> (🥉6 ·  ⭐ 27 · 💤) - Moment Invariants Local Atomic Descriptor. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a></summary>

- [GitHub](https://github.com/muhrin/milad) (🔀 1 · 📦 1 · ⏱️ 03.12.2022):

	```
	git clone https://github.com/muhrin/milad
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/nice">NICE</a></b> (🥉6 ·  ⭐ 11) - NICE (N-body Iteratively Contracted Equivariants) is a set of tools designed for the calculation of invariant and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/nice) (👨‍💻 4 · 🔀 2 · 📋 3 - 66% open · ⏱️ 01.05.2023):

	```
	git clone https://github.com/lab-cosmo/nice
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/sirmarcel/cmlkit">cmlkit</a></b> (🥈10 ·  ⭐ 31 · 💀) - tools for machine learning in condensed matter physics and quantum chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/lantunes/skipatom">SkipAtom</a></b> (🥉7 ·  ⭐ 22 · 💀) - Distributed representations of atoms, inspired by the Skip-gram model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Kaaiian/CBFV">CBFV</a></b> (🥉7 ·  ⭐ 15 · 💀) - Tool to quickly create a composition-based feature vector. <code>Unlicensed</code>
- <b><a href="https://github.com/dilkins/TENSOAP">SA-GPR</a></b> (🥉6 ·  ⭐ 14 · 💀) - Public repository for symmetry-adapted Gaussian Process Regression (SA-GPR). <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>C-lang</code>
- <b><a href="https://github.com/zhuligs/fplib">fplib</a></b> (🥉6 ·  ⭐ 7 · 💀) - a fingerprint library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C-lang</code> <code>single-paper</code>
- <b><a href="https://github.com/capoe/soapxx">SOAPxx</a></b> (🥉6 ·  ⭐ 7 · 💀) - A SOAP implementation. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code> <code>C++</code>
- <b><a href="https://github.com/ceriottm/lode">pyLODE</a></b> (🥉6 ·  ⭐ 2) - Pythonic implementation of LOng Distance Equivariants. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>electrostatics</code>
- <b><a href="https://gitlab.com/sissopp_developers/sissopp">SISSO++</a></b> (🥉4 ·  ⭐ 2 · 💀) - C++ Implementation of SISSO with python bindings. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>C++</code>
- <b><a href="https://github.com/dppant/magnetism-prediction">magnetism-prediction</a></b> (🥉4 ·  ⭐ 1) - DFT-aided Machine Learning Search for Magnetism in Fe-based Bimetallic Chalcogenides. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>magnetism</code> <code>single-paper</code>
- <b><a href="https://github.com/msg-byu/ML-for-CurieTemp-Predictions">ML-for-CurieTemp-Predictions</a></b> (🥉3 · 🐣) - Machine Learning Predictions of High-Curie-Temperature Materials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code> <code>magnetism</code>
- <b><a href="https://bitbucket.org/andrewpeterson/amp/">AMP</a></b> (🥉2) - Amp is an open-source package designed to easily bring machine-learning to atomistic calculations. <code>Unlicensed</code>
</details>
<br>

## Representation Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General models that learn a representations aka embeddings of atomistic systems, such as message-passing neural networks (MPNN)._

<details><summary><b><a href="https://github.com/dmlc/dgl">Deep Graph Library (DGL)</a></b> (🥇38 ·  ⭐ 12K) - Python package built to ease deep learning on graph, on top of existing DL frameworks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 280 · 🔀 2.8K · 📦 160 · 📋 2.4K - 13% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 62K / month):
	```
	pip install dgl
	```
- [Conda](https://anaconda.org/dglteam/dgl) (📥 290K · ⏱️ 14.09.2023):
	```
	conda install -c dglteam dgl
	```
</details>
<details><summary><b><a href="https://github.com/pyg-team/pytorch_geometric/tree/master/torch_geometric/nn/models">PyG Models</a></b> (🥇30 ·  ⭐ 19K) - Representation learning models implemented in PyTorch Geometric. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>general-ml</code></summary>

- [GitHub](https://github.com/pyg-team/pytorch_geometric) (👨‍💻 450 · 🔀 3.3K · 📋 3.2K - 23% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/pyg-team/pytorch_geometric
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/schnetpack">SchNetPack</a></b> (🥇27 ·  ⭐ 650) - SchNetPack - Deep Neural Networks for Atomistic Systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/schnetpack) (👨‍💻 31 · 🔀 180 · 📦 59 · 📋 210 - 1% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/atomistic-machine-learning/schnetpack
	```
- [PyPi](https://pypi.org/project/schnetpack) (📥 600 / month):
	```
	pip install schnetpack
	```
</details>
<details><summary><b><a href="https://github.com/e3nn/e3nn">e3nn</a></b> (🥇25 ·  ⭐ 760) - A modular framework for neural networks with Euclidean symmetry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/e3nn/e3nn) (👨‍💻 29 · 🔀 110 · 📦 120 · 📋 150 - 10% open · ⏱️ 02.09.2023):

	```
	git clone https://github.com/e3nn/e3nn
	```
- [PyPi](https://pypi.org/project/e3nn) (📥 110K / month):
	```
	pip install e3nn
	```
- [Conda](https://anaconda.org/conda-forge/e3nn) (📥 9.8K · ⏱️ 18.06.2023):
	```
	conda install -c conda-forge e3nn
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/dgl-lifesci">dgl-lifesci</a></b> (🥇22 ·  ⭐ 620 · 📈) - Python package for graph neural networks in chemistry and biology. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/awslabs/dgl-lifesci) (👨‍💻 22 · 🔀 130 · 📦 130 · 📋 80 - 30% open · ⏱️ 16.04.2023):

	```
	git clone https://github.com/awslabs/dgl-lifesci
	```
- [PyPi](https://pypi.org/project/dgllife) (📥 7.9K / month):
	```
	pip install dgllife
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/gcnn_keras">kgcnn</a></b> (🥇22 ·  ⭐ 88) - Graph convolutions in Keras with TensorFlow, PyTorch or Jax. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aimat-lab/gcnn_keras) (👨‍💻 7 · 🔀 24 · 📦 15 · 📋 78 - 7% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/aimat-lab/gcnn_keras
	```
- [PyPi](https://pypi.org/project/kgcnn) (📥 100 / month):
	```
	pip install kgcnn
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/DeepLearningExamples#graph-neural-networks">NVIDIA Deep Learning Examples for Tensor Cores</a></b> (🥈21 ·  ⭐ 12K) - State-of-the-Art Deep Learning scripts organized by models - easy to train and deploy with reproducible accuracy and.. <code><a href="https://github.com/NVIDIA/DeepLearningExamples/blob/master/DGLPyTorch/DrugDiscovery/SE3Transformer/LICENSE">Custom</a></code> <code>educational</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a></summary>

- [GitHub](https://github.com/NVIDIA/DeepLearningExamples) (👨‍💻 120 · 🔀 2.8K · 📋 790 - 29% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/NVIDIA/DeepLearningExamples
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/matgl">MatGL (Materials Graph Library)</a></b> (🥈21 ·  ⭐ 120) - Graph deep learning library for materials. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/matgl) (👨‍💻 12 · 🔀 28 · 📦 13 · 📋 40 - 7% open · ⏱️ 19.10.2023):

	```
	git clone https://github.com/materialsvirtuallab/matgl
	```
- [PyPi](https://pypi.org/project/m3gnet) (📥 420 / month):
	```
	pip install m3gnet
	```
</details>
<details><summary><b><a href="https://github.com/Open-Catalyst-Project/ocp">ocp</a></b> (🥈19 ·  ⭐ 480) - ocp is the Open Catalyst Projects library of state-of-the-art machine learning algorithms for catalysis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Open-Catalyst-Project/ocp) (👨‍💻 32 · 🔀 170 · 📋 140 - 7% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/Open-Catalyst-Project/ocp
	```
</details>
<details><summary><b><a href="https://github.com/e3nn/e3nn-jax">e3nn-jax</a></b> (🥈19 ·  ⭐ 120) - jax library for E3 Equivariant Neural Networks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/e3nn/e3nn-jax) (👨‍💻 5 · 🔀 13 · 📦 19 · 📋 10 - 10% open · ⏱️ 17.10.2023):

	```
	git clone https://github.com/e3nn/e3nn-jax
	```
- [PyPi](https://pypi.org/project/e3nn-jax) (📥 1.9K / month):
	```
	pip install e3nn-jax
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/alignn">ALIGNN</a></b> (🥈18 ·  ⭐ 150) - Atomistic Line Graph Neural Network. <code><a href="https://github.com/usnistgov/alignn/blob/main/LICENSE.rst">Custom</a></code></summary>

- [GitHub](https://github.com/usnistgov/alignn) (👨‍💻 7 · 🔀 63 · 📦 7 · 📋 46 - 50% open · ⏱️ 11.08.2023):

	```
	git clone https://github.com/usnistgov/alignn
	```
- [PyPi](https://pypi.org/project/alignn) (📥 610 / month):
	```
	pip install alignn
	```
</details>
<details><summary><b><a href="https://github.com/dptech-corp/Uni-Mol">Uni-Mol</a></b> (🥈17 ·  ⭐ 430) - Official Repository for the Uni-Mol Series Methods. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pre-trained</code></summary>

- [GitHub](https://github.com/dptech-corp/Uni-Mol) (👨‍💻 12 · 🔀 79 · 📥 6.4K · 📋 100 - 28% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/dptech-corp/Uni-Mol
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/matsciml">matsciml</a></b> (🥈17 ·  ⭐ 74) - Open MatSci ML Toolkit is a single framework for prototyping and scaling out deep learning models for materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>workflows</code> <code>benchmarking</code></summary>

- [GitHub](https://github.com/IntelLabs/matsciml) (👨‍💻 8 · 🔀 10 · 📋 10 - 50% open · ⏱️ 18.10.2023):

	```
	git clone https://github.com/IntelLabs/matsciml
	```
</details>
<details><summary><b><a href="https://github.com/QUVA-Lab/escnn">escnn</a></b> (🥈15 ·  ⭐ 240) - Equivariant Steerable CNNs Library for Pytorch https://quva-lab.github.io/escnn/. <code><a href="https://github.com/QUVA-Lab/escnn/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/QUVA-Lab/escnn) (👨‍💻 10 · 🔀 33 · 📋 55 - 34% open · ⏱️ 17.10.2023):

	```
	git clone https://github.com/QUVA-Lab/escnn
	```
- [PyPi](https://pypi.org/project/escnn) (📥 470 / month):
	```
	pip install escnn
	```
</details>
<details><summary><b><a href="https://github.com/sparks-baird/CrabNet">Compositionally-Restricted Attention-Based Network (CrabNet)</a></b> (🥈12 ·  ⭐ 11) - Predict materials properties using only the composition information!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sparks-baird/CrabNet) (👨‍💻 5 · 🔀 3 · 📦 11 · 📋 17 - 88% open · ⏱️ 19.06.2023):

	```
	git clone https://github.com/sparks-baird/CrabNet
	```
- [PyPi](https://pypi.org/project/crabnet) (📥 140 / month):
	```
	pip install crabnet
	```
</details>
<details><summary><b><a href="https://github.com/gasteigerjo/gdc">GDC</a></b> (🥈10 ·  ⭐ 220) - Graph Diffusion Convolution, as proposed in Diffusion Improves Graph Learning (NeurIPS 2019). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a></summary>

- [GitHub](https://github.com/gasteigerjo/gdc) (👨‍💻 3 · 🔀 38 · 📦 1 · ⏱️ 26.04.2023):

	```
	git clone https://github.com/gasteigerjo/gdc
	```
</details>
<details><summary><b><a href="https://github.com/LLNL/graphite">graphite</a></b> (🥈10 ·  ⭐ 25) - A repository for implementing graph network models based on atomic structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/LLNL/graphite) (👨‍💻 2 · 🔀 6 · 📦 6 · ⏱️ 04.10.2023):

	```
	git clone https://github.com/llnl/graphite
	```
</details>
<details><summary><b><a href="https://github.com/superlouis/GATGNN">GATGNN: Global Attention Graph Neural Network</a></b> (🥈9 ·  ⭐ 61 · 💤) - Pytorch Repository for our work: Graph convolutional neural networks with global attention for improved materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/superlouis/GATGNN) (👨‍💻 3 · 🔀 18 · 📋 6 - 50% open · ⏱️ 03.10.2022):

	```
	git clone https://github.com/superlouis/GATGNN
	```
</details>
<details><summary><b><a href="https://github.com/usccolumbia/deeperGATGNN">DeeperGATGNN</a></b> (🥉8 ·  ⭐ 32) - Scalable graph neural networks for materials property prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/usccolumbia/deeperGATGNN) (👨‍💻 3 · 🔀 7 · ⏱️ 19.04.2023):

	```
	git clone https://github.com/usccolumbia/deeperGATGNN
	```
</details>
<details><summary><b><a href="https://github.com/hyllios/CGAT">CGAT</a></b> (🥉8 ·  ⭐ 16 · 💤) - Crystal graph attention neural networks for materials prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hyllios/CGAT) (👨‍💻 4 · 🔀 7 · ⏱️ 10.01.2023):

	```
	git clone https://github.com/hyllios/CGAT
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/uvvisml">UVVisML</a></b> (🥉8 ·  ⭐ 14) - Predict optical properties of molecules with machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Optical_properties"><code>optical-properties</code></a> <code>single-paper</code> <code>probabilistic</code></summary>

- [GitHub](https://github.com/learningmatter-mit/uvvisml) (🔀 4 · ⏱️ 26.05.2023):

	```
	git clone https://github.com/learningmatter-mit/uvvisml
	```
</details>
<details><summary><b><a href="https://github.com/atomicarchitects/equiformer">Equiformer</a></b> (🥉7 ·  ⭐ 130) - [ICLR23 Spotlight] Equiformer: Equivariant Graph Attention Transformer for 3D Atomistic Graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomicarchitects/equiformer) (👨‍💻 2 · 🔀 25 · 📋 12 - 41% open · ⏱️ 21.06.2023):

	```
	git clone https://github.com/atomicarchitects/equiformer
	```
</details>
<details><summary><b><a href="https://github.com/lanl/hippynn">hippynn</a></b> (🥉7 ·  ⭐ 48) - python library for atomistic machine learning. <code><a href="https://github.com/lanl/hippynn/blob/main/LICENSE.txt">Custom</a></code> <code>workflows</code></summary>

- [GitHub](https://github.com/lanl/hippynn) (👨‍💻 11 · 🔀 18 · 📋 6 - 83% open · ⏱️ 17.10.2023):

	```
	git clone https://github.com/lanl/hippynn
	```
</details>
<details><summary><b><a href="https://github.com/Open-Catalyst-Project/AdsorbML">AdsorbML</a></b> (🥉7 ·  ⭐ 22) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Surface_science"><code>surface-science</code></a> <code>single-paper</code></summary>

- [GitHub](https://github.com/Open-Catalyst-Project/AdsorbML) (👨‍💻 5 · 🔀 5 · ⏱️ 31.07.2023):

	```
	git clone https://github.com/Open-Catalyst-Project/AdsorbML
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/ML4pXRDs">ML4pXRDs</a></b> (🥉7) - Contains code to train neural networks based on simulated powder XRDs from synthetic crystals. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/X-ray_crystallography"><code>XRD</code></a> <code>single-paper</code></summary>

- [GitHub](https://github.com/aimat-lab/ML4pXRDs) (📥 2 · ⏱️ 14.07.2023):

	```
	git clone https://github.com/aimat-lab/ML4pXRDs
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace-layer">MACE-Layer</a></b> (🥉6 ·  ⭐ 26) - Higher order equivariant graph neural networks for 3D point clouds. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace-layer) (👨‍💻 2 · 🔀 4 · ⏱️ 06.06.2023):

	```
	git clone https://github.com/ACEsuit/mace-layer
	```
</details>
<details><summary><b><a href="https://github.com/emilemathieu/escnn_jax">escnn_jax</a></b> (🥉6 ·  ⭐ 22 · 🐣) - Equivariant Steerable CNNs Library for Pytorch https://quva-lab.github.io/escnn/. <code><a href="https://github.com/emilemathieu/escnn_jax/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/emilemathieu/escnn_jax) (👨‍💻 8 · 🔀 2 · ⏱️ 28.06.2023):

	```
	git clone https://github.com/emilemathieu/escnn_jax
	```
- [PyPi](https://pypi.org/project/escnn_jax):
	```
	pip install escnn_jax
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/GLAMOUR">GLAMOUR</a></b> (🥉6 ·  ⭐ 18 · 💤) - Graph Learning over Macromolecule Representations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code></summary>

- [GitHub](https://github.com/learningmatter-mit/GLAMOUR) (🔀 6 · ⏱️ 31.12.2022):

	```
	git clone https://github.com/learningmatter-mit/GLAMOUR
	```
</details>
<details><summary><b><a href="https://github.com/lantunes/CraTENet">CraTENet</a></b> (🥉5 ·  ⭐ 6) - An attention-based deep neural network for thermoelectric transport properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a></summary>

- [GitHub](https://github.com/lantunes/CraTENet) (🔀 1 · ⏱️ 05.04.2023):

	```
	git clone https://github.com/lantunes/CraTENet
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/per-site_painn">Per-site PAiNN</a></b> (🥉5 · 🐣) - Fork of PaiNN for PerovskiteOrderingGCNNs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code> <code>pre-trained</code> <code>single-paper</code></summary>

- [GitHub](https://github.com/learningmatter-mit/per-site_painn) (👨‍💻 10 · ⏱️ 05.06.2023):

	```
	git clone https://github.com/learningmatter-mit/per-site_painn
	```
</details>
<details><summary>Show 22 hidden projects...</summary>

- <b><a href="https://github.com/graphdeeplearning/benchmarking-gnns">benchmarking-gnns</a></b> (🥈14 ·  ⭐ 2.3K · 💀) - Repository for benchmarking graph neural networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code> <code>benchmarking</code>
- <b><a href="https://github.com/txie-93/cgcnn">Crystal Graph Convolutional Neural Networks (CGCNN)</a></b> (🥈12 ·  ⭐ 510 · 💀) - Crystal graph convolutional neural networks for predicting material properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/NREL/nfp">Neural fingerprint (nfp)</a></b> (🥈12 ·  ⭐ 54 · 💀) - Keras layers for end-to-end learning with rdkit and pymatgen. <code><a href="https://github.com/NREL/nfp/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/FabianFuchsML/se3-transformer-public">SE(3)-Transformers</a></b> (🥈9 ·  ⭐ 410 · 💀) - code for the SE3 Transformers paper: https://arxiv.org/abs/2006.10503. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/masashitsubaki/molecularGNN_smiles">molecularGNN_smiles</a></b> (🥈9 ·  ⭐ 250 · 💀) - The code of a graph neural network (GNN) for molecules, which is based on learning representations of r-radius.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/HSE-LAMBDA/ai4material_design">ai4material_design</a></b> (🥈9 ·  ⭐ 1) - Code for Kazeev, N., Al-Maeeni, A.R., Romanov, I. et al. Sparse representation for machine learning the properties of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>pre-trained</code> <a href="https://en.wikipedia.org/wiki/Crystallographic_defect"><code>material-defect</code></a>
- <b><a href="https://github.com/atomistic-machine-learning/dtnn">DTNN</a></b> (🥉7 ·  ⭐ 77 · 💀) - Deep Tensor Neural Network. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/risilab/cormorant">Cormorant</a></b> (🥉7 ·  ⭐ 54 · 💀) - Codebase for Cormorant Neural Networks. <code><a href="https://github.com/risilab/cormorant/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/pfnet-research/charge_transfer_nnp">charge_transfer_nnp</a></b> (🥉6 ·  ⭐ 23 · 💀) - Graph neural network potential with charge transfer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>electrostatics</code>
- <b><a href="https://github.com/tensorfieldnetworks/tensorfieldnetworks">tensorfieldnetworks</a></b> (🥉5 ·  ⭐ 140 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/risilab/Autobahn">Autobahn</a></b> (🥉5 ·  ⭐ 28 · 💀) - Repository for Autobahn: Automorphism Based Graph Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/andy90/SCFNN">SCFNN</a></b> (🥉5 ·  ⭐ 14 · 💀) - Self-consistent determination of long-range electrostatics in neural network potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C++</code> <code>electrostatics</code> <code>single-paper</code>
- <b><a href="https://github.com/atomistic-machine-learning/field_schnet">FieldSchNet</a></b> (🥉5 ·  ⭐ 9 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/atomicarchitects/equiformer_v2">EquiformerV2</a></b> (🥉4 ·  ⭐ 84 · 🐣) - [arXiv23] EquiformerV2: Improved Equivariant Transformer for Scaling to Higher-Degree Representations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gasteigerjo/gtn">Graph Transport Network</a></b> (🥉4 ·  ⭐ 15) - Graph transport network (GTN), as proposed in Scalable Optimal Transport in High Dimensions for Graph Distances,.. <code><a href="https://github.com/gasteigerjo/gtn/blob/main/LICENSE.md">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://github.com/learningmatter-mit/per-site_cgcnn">Per-Site CGCNN</a></b> (🥉4 ·  ⭐ 1 · 🐣) - Crystal graph convolutional neural networks for predicting material properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pre-trained</code> <code>single-paper</code>
- <b><a href="https://github.com/idocx/Atom2Vec">Atom2Vec</a></b> (🥉3 ·  ⭐ 25 · 💀) - Atom2Vec: a simple way to describe atoms for machine learning. <code>Unlicensed</code>
- <b><a href="https://github.com/jeherr/element-encoder">Element encoder</a></b> (🥉3 ·  ⭐ 5 · 💀) - Autoencoder neural network to compress properties of atomic species into a vector representation. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>single-paper</code>
- <b><a href="https://github.com/learningmatter-mit/atom_by_atom">atom_by_atom</a></b> (🥉3 ·  ⭐ 2 · 🐣) - Atom-by-atom design of metal oxide catalysts for the oxygen evolution reaction with Machine Learning. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Surface_science"><code>surface-science</code></a> <code>single-paper</code>
- <b><a href="https://github.com/sirmarcel/gkx">gkx: Green-Kubo Method in JAX</a></b> (🥉2 ·  ⭐ 2 · 🐣) - Green-Kubo + JAX + MLPs = Anharmonic Thermal Conductivities Done Fast. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://zenodo.org/record/7967079">Point Edge Transformer</a></b> (🥉2) - Smooth, exact rotational symmetrization for deep learning on point clouds. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code>
- <b><a href="https://github.com/risilab/SphericalNet">SphericalNet</a></b> (🥉1 ·  ⭐ 3 · 💀) - Implementation of Clebsch-Gordan Networks (CGnet: https://arxiv.org/pdf/1806.09231.pdf) by GElib & cnine libraries in.. <code>Unlicensed</code>
</details>
<br>

## Unsupervised Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on unsupervised learning (USL) for atomistic ML, such as dimensionality reduction, clustering and visualization._

<details><summary><b><a href="https://github.com/sissa-data-science/DADApy">DADApy</a></b> (🥇15 ·  ⭐ 74) - Distance-based Analysis of DAta-manifolds in python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sissa-data-science/DADApy) (👨‍💻 15 · 🔀 9 · 📦 2 · 📋 26 - 42% open · ⏱️ 14.09.2023):

	```
	git clone https://github.com/sissa-data-science/DADApy
	```
- [PyPi](https://pypi.org/project/dadapy) (📥 61 / month):
	```
	pip install dadapy
	```
</details>
<details><summary><b><a href="https://github.com/BingqingCheng/ASAP">ASAP</a></b> (🥈13 ·  ⭐ 120) - ASAP is a package that can quickly analyze and visualize datasets of crystal or molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/BingqingCheng/ASAP) (👨‍💻 6 · 🔀 25 · 📦 4 · 📋 24 - 25% open · ⏱️ 30.08.2023):

	```
	git clone https://github.com/BingqingCheng/ASAP
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/sketchmap">Sketchmap</a></b> (🥉8 ·  ⭐ 39) - Suite of programs to perform non-linear dimensionality reduction -- sketch-map in particular. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/lab-cosmo/sketchmap) (👨‍💻 8 · 🔀 10 · 📋 8 - 37% open · ⏱️ 24.05.2023):

	```
	git clone https://github.com/lab-cosmo/sketchmap
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/learningmatter-mit/Coarse-Graining-Auto-encoders">Coarse-Graining-Auto-encoders</a></b> (🥉3 ·  ⭐ 20 · 💀) -  <code>Unlicensed</code> <code>single-paper</code>
- <b><a href="https://github.com/Minoru938/KmdPlus">KmdPlus</a></b> (🥉2 ·  ⭐ 1) - This module contains a class for treating kernel mean descriptor (KMD), and a function for generating descriptors with.. <code>Unlicensed</code>
- <b><a href="https://gitlab.mpcdf.mpg.de/klai/decaf">Descriptor Embedding and Clustering for Atomisitic-environment Framework (DECAF)</a></b> ( ⭐ 2) - Provides a workflow to obtain clustering of local environments in dataset of structures. <code>Unlicensed</code>
</details>
<br>

## Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on visualization (viz.) for atomistic ML._

<details><summary><b><a href="https://github.com/lab-cosmo/chemiscope">Chemiscope</a></b> (🥇17 ·  ⭐ 89) - An interactive structure/property explorer for materials and molecules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>JavaScript</code></summary>

- [GitHub](https://github.com/lab-cosmo/chemiscope) (👨‍💻 17 · 🔀 27 · 📥 140 · 📦 5 · 📋 110 - 35% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/lab-cosmo/chemiscope
	```
- [npm](https://www.npmjs.com/package/chemiscope) (📥 130 / month):
	```
	npm install chemiscope
	```
</details>
<br>

## Wavefunction methods (ML-WFT)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of wavefunction theory methods, such as Monte Carlo techniques like deep learning variational Monte Carlo (DL-VMC), quantum chemistry methods, etc._

<details><summary><b><a href="https://github.com/deepqmc/deepqmc">DeepQMC</a></b> (🥇22 ·  ⭐ 300) - Deep learning quantum Monte Carlo for electrons in real space. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deepqmc/deepqmc) (👨‍💻 13 · 🔀 56 · 📦 1 · 📋 38 - 7% open · ⏱️ 16.10.2023):

	```
	git clone https://github.com/deepqmc/deepqmc
	```
- [PyPi](https://pypi.org/project/deepqmc) (📥 180 / month):
	```
	pip install deepqmc
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/ferminet">FermiNet</a></b> (🥈14 ·  ⭐ 580) - An implementation of the Fermionic Neural Network for ab-initio electronic structure calculations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-deepmind/ferminet) (👨‍💻 18 · 🔀 100 · ⏱️ 14.08.2023):

	```
	git clone https://github.com/deepmind/ferminet
	```
</details>
<details><summary><b><a href="https://github.com/mdsunivie/deeperwin">DeepErwin</a></b> (🥉8 ·  ⭐ 35) - DeepErwin is a python 3.8+ package that implements and optimizes JAX 2.x wave function models for numerical solutions.. <code><a href="https://github.com/mdsunivie/deeperwin/blob/master/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/mdsunivie/deeperwin) (👨‍💻 6 · 🔀 5 · ⏱️ 16.10.2023):

	```
	git clone https://github.com/mdsunivie/deeperwin
	```
- [PyPi](https://pypi.org/project/deeperwin) (📥 19 / month):
	```
	pip install deeperwin
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/atomistic-machine-learning/SchNOrb">SchNOrb</a></b> (🥉5 ·  ⭐ 54 · 💀) - Unifying machine learning and quantum chemistry with a deep neural network for molecular wavefunctions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary>Show 1 hidden projects...</summary>


</details>

---

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
