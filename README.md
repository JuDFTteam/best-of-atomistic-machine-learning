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
    <strong>🏆&nbsp; A ranked list of awesome atomistic machine learning (AML) projects. Updated regularly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-460-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/JuDFTteam/best-of-atomistic-machine-learning/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/JuDFTteam/best-of-atomistic-machine-learning?color=green&label=updated"></a>
    <a href="https://doi.org/10.5281/zenodo.10430261"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.10430261.svg" alt="DOI"></a>
</p>

This curated list contains 460 awesome open-source projects with a total of 220K stars grouped into 23 categories. All projects are ranked by a [project-quality score](https://github.com/best-of-lists/best-of-generator#project-quality-score), which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/issues/new/choose), submit a [pull request](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/pulls), or directly edit the [projects.yaml](https://github.com/JuDFTteam/best-of-atomistic-machine-learning/edit/main/projects.yaml).

The current focus of this list is more on simulation data rather than experimental data, and more on materials rather than drug design. Nevertheless, contributions from other fields are warmly welcome!

<strong>How to cite.</strong> See the button "Cite this repository" on the right side-bar.

> 🧙‍♂️  Discover other [best-of lists](https://best-of.org) or [create your own](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

## Contents

- [Active learning](#active-learning) _9 projects_
- [Community resources](#community-resources) _39 projects_
- [Datasets](#datasets) _53 projects_
- [Data Structures](#data-structures) _4 projects_
- [Density functional theory (ML-DFT)](#density-functional-theory-ml-dft) _30 projects_
- [Educational Resources](#educational-resources) _26 projects_
- [Explainable Artificial intelligence (XAI)](#explainable-artificial-intelligence-xai) _2 projects_
- [Electronic structure methods (ML-ESM)](#electronic-structure-methods-ml-esm) _4 projects_
- [General Tools](#general-tools) _24 projects_
- [Generative Models](#generative-models) _16 projects_
- [Interatomic Potentials (ML-IAP)](#interatomic-potentials-ml-iap) _73 projects_
- [Language Models](#language-models) _22 projects_
- [Materials Discovery](#materials-discovery) _13 projects_
- [Mathematical tools](#mathematical-tools) _12 projects_
- [Molecular Dynamics](#molecular-dynamics) _14 projects_
- [Probabilistic ML](#probabilistic-ml) _1 projects_
- [Reinforcement Learning](#reinforcement-learning) _2 projects_
- [Representation Engineering](#representation-engineering) _26 projects_
- [Representation Learning](#representation-learning) _54 projects_
- [Universal Potentials](#universal-potentials) _18 projects_
- [Unsupervised Learning](#unsupervised-learning) _10 projects_
- [Visualization](#visualization) _6 projects_
- [Wavefunction methods (ML-WFT)](#wavefunction-methods-ml-wft) _5 projects_
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

<details><summary><b><a href="https://github.com/deepmodeling/dpgen">DP-GEN</a></b> (🥇18 ·  ⭐ 380) - The deep potential generator to generate a deep-learning based model of interatomic potential energy and force field. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>workflows</code></summary>

- [GitHub](https://github.com/deepmodeling/dpgen) (👨‍💻 76 · 🔀 190 · 📦 8):

	```
	git clone https://github.com/deepmodeling/dpgen
	```
- [PyPi](https://pypi.org/project/dpgen) (📥 810 / month · 📦 2 · ⏱️ 12.05.2026):
	```
	pip install dpgen
	```
- [Conda](https://anaconda.org/deepmodeling/dpgen) (📥 320 · ⏱️ 25.03.2025):
	```
	conda install -c deepmodeling dpgen
	```
</details>
<details><summary><b><a href="https://bgolearn.netlify.app">Bgolearn</a></b> (🥈13 ·  ⭐ 140) - [NPJ Com. Mat.] Offical implement of Bgolearn. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <code>probabilistic</code></summary>

- [GitHub](https://github.com/Bin-Cao/Bgolearn) (👨‍💻 4 · 🔀 19):

	```
	git clone https://github.com/Bin-Cao/Bgolearn
	```
- [PyPi](https://pypi.org/project/Bgolearn) (📥 510 / month · ⏱️ 09.07.2026):
	```
	pip install Bgolearn
	```
</details>
<details><summary><b><a href="https://github.com/zincware/IPSuite">IPSuite</a></b> (🥈13 ·  ⭐ 24) - A Python toolkit for FAIR development and deployment of machine-learned interatomic potentials. <code><a href="http://bit.ly/2M0xmjV">EPL-2.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>workflows</code> <a href="https://en.wikipedia.org/wiki/High-throughput_computing"><code>HTC</code></a> <a href="https://www.go-fair.org/fair-principles/"><code>FAIR</code></a></summary>

- [GitHub](https://github.com/zincware/IPSuite) (👨‍💻 9 · 🔀 13 · 📦 14):

	```
	git clone https://github.com/zincware/IPSuite
	```
- [PyPi](https://pypi.org/project/ipsuite) (📥 190 / month · 📦 5 · ⏱️ 20.11.2025):
	```
	pip install ipsuite
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/flare">FLARE</a></b> (🥈12 ·  ⭐ 340 · 💤) - An open-source Python package for creating fast and accurate interatomic potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C++</code> <code>ML-IAP</code></summary>

- [GitHub](https://github.com/mir-group/flare) (👨‍💻 44 · 🔀 78 · 📦 12):

	```
	git clone https://github.com/mir-group/flare
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/dpgen2">DP-GEN2</a></b> (🥉9 ·  ⭐ 40) - 2nd generation of the Deep Potential GENerator. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>workflows</code></summary>

- [GitHub](https://github.com/deepmodeling/dpgen2) (👨‍💻 19 · 🔀 36 · 📦 6):

	```
	git clone https://github.com/deepmodeling/dpgen2
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/mir-group/flare_pp">flare++</a></b> (🥉10 ·  ⭐ 37 · 💀) - A many-body extension of the FLARE code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>C++</code> <code>ML-IAP</code>
- <b><a href="https://github.com/ulissigroup/finetuna">Finetuna</a></b> (🥉7 ·  ⭐ 55 · 💀) - Active Learning for Machine Learning Potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nec-research/alebrew">ALEBREW</a></b> (🥉5 ·  ⭐ 21 · 💀) - Official repository for the paper Uncertainty-biased molecular dynamics for learning uniformly accurate interatomic.. <code><a href="https://github.com/nec-research/alebrew/blob/main/LICENSE.txt">Custom</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://github.com/ACEsuit/ACEHAL">ACEHAL</a></b> (🥉4 ·  ⭐ 14 · 💀) - Hyperactive Learning (HAL) Python interface for building Atomic Cluster Expansion potentials. <code>Unlicensed</code> <code>Julia</code>
</details>
<br>

## Community resources

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that collect atomistic ML resources or foster communication within community._

🔗&nbsp;<b><a href="https://acesupport.zulipchat.com">ACE / GRACE support</a></b>  - Support forum for the Atomic Cluster Expansion (ACE) and extensions.

🔗&nbsp;<b><a href="https://www.air4.science/map">AI for Science Map</a></b>  - Interactive mindmap of the AI4Science research field, including atomistic machine learning, including papers,..

🔗&nbsp;<b><a href="https://wiki.fysik.dtu.dk/ase/ecosystem.html">ASE ecosystem</a></b>  - This is a list of software packages related to ASE or using ASE. <code>md, ml-iap</code>

🔗&nbsp;<b><a href="https://cortner.github.io/ACEweb/">Atomic Cluster Expansion</a></b>  - Atomic Cluster Expansion (ACE) community homepage.

🔗&nbsp;<b><a href="https://crystallm.com">CrystaLLM</a></b>  - Generate a crystal structure from a composition. <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>

🔗&nbsp;<b><a href="https://gap-ml.org/">GAP-ML.org community homepage</a></b>   <code>ML-IAP</code>

🔗&nbsp;<b><a href="https://matsci.org/">matsci.org</a></b>  - A community forum for the discussion of anything materials science, with a focus on computational materials science..

🔗&nbsp;<b><a href="https://mattermodeling.stackexchange.com/questions/tagged/machine-learning">Matter Modeling Stack Exchange - Machine Learning</a></b>  - Forum StackExchange, site Matter Modeling, ML-tagged questions.

<details><summary><b><a href="https://github.com/janosh/matbench-discovery">MatBench Discovery</a></b> (🥇17 ·  ⭐ 210) - An evaluation framework for machine learning models simulating high-throughput materials discovery. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code> <code>benchmarking</code> <code>model-repository</code></summary>

- [GitHub](https://github.com/janosh/matbench-discovery) (👨‍💻 35 · 🔀 54 · 📦 8):

	```
	git clone https://github.com/janosh/matbench-discovery
	```
- [PyPi](https://pypi.org/project/matbench-discovery) (📥 3.9K / month · 📦 2 · ⏱️ 11.09.2024):
	```
	pip install matbench-discovery
	```
</details>
<details><summary><b><a href="https://ml-peg.stfc.ac.uk/">ML-PEG</a></b> (🥇14 ·  ⭐ 49) - ML Performance and Extrapolation Guide. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>benchmarking</code> <a href="https://en.wikipedia.org/wiki/Visualization"><code>viz</code></a> <code>datasets</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a> <code>long-range</code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a></summary>

- [GitHub](https://github.com/ddmms/ml-peg) (👨‍💻 25 · 🔀 47):

	```
	git clone https://github.com/ddmms/ml-peg
	```
- [PyPi](https://pypi.org/project/ml-peg) (📥 280 / month · ⏱️ 06.07.2026):
	```
	pip install ml-peg
	```
</details>
<details><summary><b><a href="https://thegardens.ai/">Garden</a></b> (🥇13 ·  ⭐ 41) - FAIR AI/ML Model Publishing Framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>model-repository</code></summary>

- [GitHub](https://github.com/Garden-AI/garden) (👨‍💻 14 · 🔀 4 · 📦 6):

	```
	git clone https://github.com/Garden-AI/garden
	```
- [PyPi](https://pypi.org/project/garden-ai) (📥 660 / month · ⏱️ 18.03.2026):
	```
	pip install garden-ai
	```
</details>
<details><summary><b><a href="https://github.com/openml/OpenML">OpenML</a></b> (🥈10 ·  ⭐ 710 · 💤) - Open Machine Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>datasets</code></summary>

- [GitHub](https://github.com/openml/OpenML) (👨‍💻 35 · 🔀 96):

	```
	git clone https://github.com/openml/OpenML
	```
</details>
<details><summary><b><a href="https://huggingface.co/GT4SD">GT4SD - Generative Toolkit for Scientific Discovery</a></b> (🥈9 ·  ⭐ 380 · 💤) - Gradio apps of generative models in GT4SD. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <code>model-repository</code></summary>

- [GitHub](https://github.com/GT4SD/gt4sd-core) (👨‍💻 20 · 🔀 81):

	```
	git clone https://github.com/GT4SD/gt4sd-core
	```
</details>
<details><summary><b><a href="https://github.com/blaiszik/awesome-matchem-datasets">Awesome Materials & Chemistry Datasets</a></b> (🥈9 ·  ⭐ 270 · 💤) - A curated list of the most useful datasets in materials science and chemistry for training machine learning and AI.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code> <a href="https://en.wikipedia.org/wiki/Experimental_physics"><code>experimental-data</code></a> <code>literature-data</code> <a href="https://en.wikipedia.org/wiki/Proprietary_software"><code>proprietary</code></a></summary>

- [GitHub](https://github.com/blaiszik/awesome-matchem-datasets) (👨‍💻 9 · 🔀 34):

	```
	git clone https://github.com/blaiszik/awesome-matchem-datasets
	```
</details>
<details><summary><b><a href="https://github.com/neurreps/awesome-neural-geometry">Awesome Neural Geometry</a></b> (🥉7 ·  ⭐ 1.1K) - A curated collection of resources and research related to the geometry of representations in the brain, deep networks,.. <code>Unlicensed</code> <code>educational</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/neurreps/awesome-neural-geometry) (👨‍💻 16 · 🔀 72):

	```
	git clone https://github.com/neurreps/awesome-neural-geometry
	```
</details>
<details><summary>Show 24 hidden projects...</summary>

- <b><a href="https://github.com/materialsproject/matbench">MatBench</a></b> (🥇16 ·  ⭐ 160 · 💀) - Matbench: Benchmarks for materials science property prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code> <code>benchmarking</code> <code>model-repository</code>
- <b><a href="https://github.com/ml-tooling/best-of-ml-python">Best-of Machine Learning with Python</a></b> (🥇13 ·  ⭐ 16K · 💀) - A ranked list of awesome machine learning Python libraries. Updated weekly. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code> <code>general-ml</code> <code>Python</code>
- <b><a href="https://github.com/naganandy/graph-based-deep-learning-literature">Graph-based Deep Learning Literature</a></b> (🥈11 ·  ⭐ 4.7K · 💀) - links to conference publications in graph-based deep learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>general-ml</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://next-gen.materialsproject.org/materials/gnome">GNoME Explorer</a></b> (🥈9 ·  ⭐ 800 · 💀) - Graph Networks for Materials Exploration Database. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>datasets</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a>
- <b><a href="https://github.com/divelab/AIRS/blob/main/Overview/resources.md">AI for Science Resources</a></b> (🥈9 ·  ⭐ 470 · 💀) - List of resources for AI4Science research, including learning resources. <code><a href="https://tldrlegal.com/search?q=GPL-3.0%20license">GPL-3.0 license</a></code>
- <b><a href="https://github.com/yuzhimanhua/Awesome-Scientific-Language-Models">Awesome-Scientific-Language-Models</a></b> (🥈9 ·  ⭐ 400 · 💀) - A Comprehensive Survey of Scientific Large Language Models and Their Applications in Scientific Discovery. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a> <code>general-ml</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Multimodal_learning"><code>multimodal</code></a>
- <b><a href="https://molformer.res.ibm.com/">MoLFormers UI</a></b> (🥈9 ·  ⭐ 210 · 💀) - A family of foundation models trained on chemicals. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>
- <b><a href="https://github.com/ncfrey/resources">A Highly Opinionated List of Open-Source Materials Informatics Resources</a></b> (🥉7 ·  ⭐ 61 · 💀) - A Highly Opinionated List of Open Source Materials Informatics Resources. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/yuanqidu/awesome-graph-generation">Awesome-Graph-Generation</a></b> (🥉6 ·  ⭐ 260 · 💀) - A curated list of up-to-date graph generation papers and resources. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/sherrylixuecheng/AI_for_Science_paper_collection">AI for Science paper collection</a></b> (🥉6 ·  ⭐ 24 · 💀) - List the AI for Science papers accepted by top conferences. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/AlexDuvalinho/geometric-gnns">Geometric-GNNs</a></b> (🥉5 ·  ⭐ 44 · 💀) - List of Geometric GNNs for 3D atomic systems. <code>Unlicensed</code> <code>datasets</code> <code>educational</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/blaiszik/ml_publication_charts">Charting ML Publications in Science</a></b> (🥉5 ·  ⭐ 43 · 💀) - Literature analysis of ML applications in materials science, chemistry, physics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>literature-data</code> <code>general-ml</code>
- <b><a href="https://github.com/Eipgen/Neural-Network-Models-for-Chemistry">Neural-Network-Models-for-Chemistry</a></b> (🥉5 ·  ⭐ 37 · 💀) - A collection of Nerual Network Models for chemistry. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://bohrium.dp.tech/competitions/8821838186">LAM Crystal Philately competition 2024</a></b> (🥉5 ·  ⭐ 22 · 💀) - OpenLAM Challenge crystal structure prediction https://arxiv.org/abs/2501.16358. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <code>single-paper</code> <code>datasets</code> <code>structure-prediction</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <code>ML-IAP</code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a>
- <b><a href="https://github.com/kdmsit/Awesome-Crystal-GNNs">Awesome-Crystal-GNNs</a></b> (🥉5 ·  ⭐ 13 · 💀) - This repository contains a collection of resources and papers on GNN Models on Crystal Solid State Materials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tilde-lab/awesome-materials-informatics">Awesome Materials Informatics</a></b> (🥉5 ·  ⭐ 11 · 💀) - Curated list of current known efforts in materials informatics. <code><a href="https://github.com/tilde-lab/awesome-materials-informatics#license">Custom</a></code>
- <b><a href="https://github.com/smsharma/awesome-neural-sbi">Awesome Neural SBI</a></b> (🥉5 ·  ⭐ 4 · 💀) - Community-sourced list of papers and resources on neural simulation-based inference. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a>
- <b><a href="https://optimade.science">optimade.science</a></b> (🥉5 · 💀) - A sky-scanner OPTIMADE browser-only GUI. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code>
- <b><a href="https://github.com/deepmodeling/deepmodeling-projects">DeepModeling Projects</a></b> (🥉4 ·  ⭐ 8 · 💤) - DeepModeling projects. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code>
- <b><a href="https://github.com/sedaoturak/data-resources-for-materials-science">The Collection of Database and Dataset Resources in Materials Science</a></b> (🥉3 ·  ⭐ 34 · 💀) - A list of databases, datasets and books/handbooks where you can find materials properties for machine learning.. <code>Unlicensed</code> <code>datasets</code>
- <b><a href="MADICES/MADICES.github.io/blob/main/docs/awesome_interoperability.md">MADICES Awesome Interoperability</a></b> (🥉3) - Linked data interoperability resources of the Machine-actionable data interoperability for the chemical sciences.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code>
- <b><a href="https://github.com/topics/materials-informatics">GitHub topic materials-informatics</a></b> (🥉1) - GitHub topic materials-informatics. <code>Unlicensed</code>
- <b><a href="https://ma.issp.u-tokyo.ac.jp/en/">MateriApps</a></b> (🥉1) - A Portal Site of Materials Science Simulation. <code>Unlicensed</code>
- <b><a href="https://thismaterialdoesnotexist.com/">Does this material exist?</a></b> (🥉1) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>for-fun</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a>
</details>
<br>

## Datasets

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Datasets, databases and trained models for atomistic ML._

🔗&nbsp;<b><a href="https://alexandria.icams.rub.de/">Alexandria Materials Database</a></b>  - A database of millions of theoretical crystal structures (3D, 2D and 1D) discovered by machine learning accelerated..

🔗&nbsp;<b><a href="https://www.catalysis-hub.org/">Catalysis Hub</a></b>  - A web-platform for sharing data and software for computational catalysis research!.

🔗&nbsp;<b><a href="https://citrination.com/">Citrination Datasets</a></b>  - AI-Powered Materials Data Platform. Open Citrination has been decommissioned.

🔗&nbsp;<b><a href="https://crystals.ai/">crystals.ai</a></b>  - Curated datasets for reproducible AI in materials science.

🔗&nbsp;<b><a href="https://huggingface.co/DeepChem">DeepChem Models</a></b>  - DeepChem models on HuggingFace. <code>model-repository</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a>

🔗&nbsp;<b><a href="https://figshare.com/articles/dataset/Graphs_of_Materials_Project_20190401/8097992">Graphs of Materials Project 20190401</a></b>  - The dataset used to train the MEGNet interatomic potential. <code>ML-IAP</code>

🔗&nbsp;<b><a href="https://doi.org/10.6084/m9.figshare.19658538">HME21 Dataset</a></b>  - High-temperature multi-element 2021 dataset for the PreFerred Potential (PFP).. <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a>

🔗&nbsp;<b><a href="https://pages.nist.gov/jarvis_leaderboard/">JARVIS-Leaderboard</a></b> ( ⭐ 72 · 💤)  - A large scale benchmark of materials design methods: https://www.nature.com/articles/s41524-024-01259-w. <code>model-repository</code> <code>benchmarking</code> <code>community-resource</code> <code>educational</code>

🔗&nbsp;<b><a href="https://materialsproject.org/ml/charge_densities">Materials Project - Charge Densities</a></b>  - Materials Project has started offering charge density information available for download via their public API.

🔗&nbsp;<b><a href="https://figshare.com/articles/dataset/Materials_Project_Trjectory_MPtrj_Dataset/23713842">Materials Project Trajectory (MPtrj) Dataset</a></b>  - The dataset used to train the CHGNet universal potential. <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a>

🔗&nbsp;<b><a href="https://matterverse.ai/">matterverse.ai</a></b>  - Database of yet-to-be-sythesized materials predicted using state-of-the-art machine learning algorithms.

🔗&nbsp;<b><a href="https://figshare.com/articles/dataset/MPF_2021_2_8/19470599">MPF.2021.2.8</a></b>  - The dataset used to train the M3GNet universal potential. <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a>

🔗&nbsp;<b><a href="https://materials.nrel.gov/">NRELMatDB</a></b>  - Computational materials database with the specific focus on materials for renewable energy applications including, but..

🔗&nbsp;<b><a href="https://data.dtu.dk/articles/dataset/QM9_Charge_Densities_and_Energies_Calculated_with_VASP/16794500">QM9 Charge Densities and Energies</a></b>  - QM9 molecules calculated with VASP using Atomic Simulation Environment. <code>ML-DFT</code>

🔗&nbsp;<b><a href="https://doi.org/10.6084/m9.figshare.25993060.v1">QM40 Dataset</a></b>  - A More Realistic QM Dataset for Machine Learning in Molecular Science https://doi.org/10.1038/s41597-024-04206-y. <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>

🔗&nbsp;<b><a href="CC-BY-3.0">QMugs dataset</a></b>  - Quantum Mechanical Properties of Drug-like Molecules https://doi.org/10.1038/s41597-022-01390-7. <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>

🔗&nbsp;<b><a href="http://quantum-machine.org/datasets/">Quantum-Machine.org Datasets</a></b>  - Collection of datasets, including QM7, QM9, etc. MD, DFT. Small organic molecules, mostly.

🔗&nbsp;<b><a href="http://sgdml.org/#datasets">sGDML Datasets</a></b>  - MD17, MD22, DFT datasets.

🔗&nbsp;<b><a href="https://moleculenet.org/">MoleculeNet</a></b>  - A Benchmark for Molecular Machine Learning. <code>benchmarking</code>

🔗&nbsp;<b><a href="https://zinc15.docking.org/">ZINC15</a></b>  - A free database of commercially-available compounds for virtual screening. ZINC contains over 230 million purchasable.. <code>graph</code> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a>

🔗&nbsp;<b><a href="https://zinc.docking.org/">ZINC20</a></b>  - A free database of commercially-available compounds for virtual screening. ZINC contains over 230 million purchasable.. <code>graph</code> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a>

<details><summary><b><a href="https://opencatalystproject.org/">FAIR Chemistry datasets</a></b> (🥇22 ·  ⭐ 2.1K) - Datasets OC20, OC22, etc. Formerly known as Open Catalyst Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a></summary>

- [GitHub]() (👨‍💻 69 · 🔀 480):

	```
	git clone https://github.com/FAIR-Chem/fairchem
	```
- [PyPi](https://pypi.org/project/fairchem-core) (📥 74K / month · 📦 48 · ⏱️ 08.06.2026):
	```
	pip install fairchem-core
	```
</details>
<details><summary><b><a href="https://huggingface.co/datasets/fairchem/OMAT24">Meta Open Materials 2024 (OMat24) Dataset</a></b> (🥇21 ·  ⭐ 2.1K) - Contains over 100 million Density Functional Theory calculations focused on structural and compositional diversity. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code></summary>

- [GitHub]() (👨‍💻 69 · 🔀 480):

	```
	git clone https://github.com/FAIR-Chem/fairchem
	```
- [PyPi](https://pypi.org/project/fairchem-core) (📥 74K / month · 📦 48 · ⏱️ 08.06.2026):
	```
	pip install fairchem-core
	```
</details>
<details><summary><b><a href="https://github.com/materialsproject/MPContribs">MPContribs</a></b> (🥇19 ·  ⭐ 39) - Platform for materials scientists to contribute and disseminate their materials data through Materials Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/materialsproject/MPContribs) (👨‍💻 32 · 🔀 27 · 📦 60):

	```
	git clone https://github.com/materialsproject/MPContribs
	```
- [PyPi](https://pypi.org/project/mpcontribs-client) (📥 9.1K / month · 📦 7 · ⏱️ 09.02.2026):
	```
	pip install mpcontribs-client
	```
</details>
<details><summary><b><a href="https://github.com/Materials-Consortia/optimade-python-tools">OPTIMADE Python tools</a></b> (🥇18 ·  ⭐ 90) - Tools for implementing and consuming OPTIMADE APIs in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Materials-Consortia/optimade-python-tools) (👨‍💻 37 · 🔀 53):

	```
	git clone https://github.com/Materials-Consortia/optimade-python-tools
	```
- [PyPi](https://pypi.org/project/optimade) (📥 23K / month · 📦 4 · ⏱️ 21.06.2026):
	```
	pip install optimade
	```
- [Conda](https://anaconda.org/conda-forge/optimade) (📥 190K · ⏱️ 21.06.2026):
	```
	conda install -c conda-forge optimade
	```
</details>
<details><summary><b><a href="https://github.com/jla-gardner/load-atoms">load-atoms</a></b> (🥈13 ·  ⭐ 48 · 💤) - download and manipulate atomistic datasets. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>data-structures</code></summary>

- [GitHub](https://github.com/jla-gardner/load-atoms) (👨‍💻 5 · 🔀 5 · 📦 8):

	```
	git clone https://github.com/jla-gardner/load-atoms
	```
- [PyPi](https://pypi.org/project/load-atoms) (📥 1K / month · 📦 3 · ⏱️ 25.11.2025):
	```
	pip install load-atoms
	```
</details>
<details><summary><b><a href="https://matpes.ai/">MatPES</a></b> (🥈11 ·  ⭐ 40 · 💤) - A foundational potential energy dataset for materials. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <code>ML-IAP</code></summary>

- [GitHub](https://github.com/materialsvirtuallab/matpes) (👨‍💻 3 · 🔀 4):

	```
	git clone https://github.com/materialsvirtuallab/matpes
	```
- [PyPi](https://pypi.org/project/matpes) (📥 230 / month · ⏱️ 10.03.2025):
	```
	pip install matpes
	```
</details>
<details><summary><b><a href="https://github.com/AIRI-Institute/nablaDFT">nablaDFT</a></b> (🥈9 ·  ⭐ 230) - nablaDFT: Large-Scale Conformational Energy and Hamiltonian Prediction benchmark and dataset. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-DFT</code> <code>ML-WFT</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <code>ML-IAP</code> <code>benchmarking</code></summary>

- [GitHub](https://github.com/AIRI-Institute/nablaDFT) (👨‍💻 9 · 🔀 25):

	```
	git clone https://github.com/AIRI-Institute/nablaDFT
	```
</details>
<details><summary><b><a href="https://www.materialsdatafacility.org">Materials Data Facility (MDF)</a></b> (🥉6 ·  ⭐ 10) - A simple way to publish, discover, and access materials datasets. Publication of very large datasets supported (e.g.,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/materials-data-facility/connect_client) (👨‍💻 7 · 🔀 1):

	```
	git clone https://github.com/materials-data-facility/connect_client
	```
</details>
<details><summary><b><a href="https://github.com/Ramprasad-Group/polyVERSE">polyVERSE</a></b> (🥉5 ·  ⭐ 31 · 🐣) - polyVERSE is a comprehensive repository of informatics-ready datasets curated by the Ramprasad Group. <code><a href="https://github.com/Ramprasad-Group/polyVERSE?tab=License-1-ov-file">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Soft_matter"><code>soft-matter</code></a></summary>

- [GitHub](https://github.com/Ramprasad-Group/polyVERSE) (👨‍💻 10 · 🔀 6):

	```
	git clone https://github.com/Ramprasad-Group/polyVERSE
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/AIS-Square">AIS Square</a></b> (🥉5 ·  ⭐ 15 · 💤) - A collaborative and open-source platform for sharing AI for Science datasets, models, and workflows. Home of the.. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>community-resource</code> <code>model-repository</code></summary>

- [GitHub](https://github.com/deepmodeling/AIS-Square) (👨‍💻 8 · 🔀 8):

	```
	git clone https://github.com/deepmodeling/AIS-Square
	```
</details>
<details><summary><b><a href="https://github.com/aimat-lab/visual_graph_datasets">Visual Graph Datasets</a></b> (🥉5 ·  ⭐ 5 · 💤) - Datasets for the training of graph neural networks (GNNs) and subsequent visualization of attributional explanations.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Explainable_artificial_intelligence"><code>XAI</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/aimat-lab/visual_graph_datasets) (👨‍💻 2 · 🔀 3):

	```
	git clone https://github.com/aimat-lab/visual_graph_datasets
	```
</details>
<details><summary>Show 21 hidden projects...</summary>

- <b><a href="https://github.com/drorlab/atom3d">ATOM3D</a></b> (🥈17 ·  ⭐ 290 · 💀) - ATOM3D: tasks on molecules in three dimensions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a> <code>benchmarking</code>
- <b><a href="https://www.openqdc.io/">OpenQDC</a></b> (🥈11 ·  ⭐ 28 · 💀) - Repository of Quantum Datasets Publicly Available. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code>
- <b><a href="https://github.com/divelab/AIRS/tree/main/OpenDFT/QHBench/QH9">QH9</a></b> (🥈9 ·  ⭐ 470 · 💀) - A Quantum Hamiltonian Prediction Benchmark. <code><a href="https://tldrlegal.com/search?q=CC-BY-NC-SA-4.0">CC-BY-NC-SA-4.0</a></code> <code>ML-DFT</code>
- <b><a href="https://github.com/mpds-io/mpds-api">MPDS API</a></b> (🥈9 ·  ⭐ 24 · 💀) - Tutorials, notebooks, issue tracker, and website on the MPDS API: the data retrieval interface for the Materials.. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code> <a href="https://en.wikipedia.org/wiki/Phase_transition"><code>phase-transition</code></a>
- <b><a href="https://github.com/NRC-Mila/OBELiX">OBELiX</a></b> (🥈9 ·  ⭐ 19 · 💀) - A Curated Dataset of Crystal Structures and Experimentally Measured Ionic Conductivities for Lithium Solid-State.. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code> <a href="https://en.wikipedia.org/wiki/Experimental_physics"><code>experimental-data</code></a> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://github.com/Materials-Consortia/OPTIMADE">Open Databases Integration for Materials Design (OPTIMADE)</a></b> (🥈8 ·  ⭐ 86 · 💀) - Specification of a common REST API for access to materials databases. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code>
- <b><a href="https://github.com/openmm/spice-dataset">SPICE</a></b> (🥉7 ·  ⭐ 190 · 💀) - A collection of QM data for training potential functions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://github.com/deepchem/moleculenet">MoleculeNet Leaderboard</a></b> (🥉7 ·  ⭐ 79 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/isayev/ANI1_dataset">ANI-1 Dataset</a></b> (🥉7 ·  ⭐ 65 · 💀) - A data set of 20 million calculated off-equilibrium conformations for organic molecules. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://openkim.org/">OpenKIM</a></b> (🥉7 ·  ⭐ 24 · 💀) - The Open Knowledgebase of Interatomic Models (OpenKIM) aims to be an online resource for standardized testing, long-.. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <code>model-repository</code> <a href="https://en.wikipedia.org/wiki/Knowledge_base"><code>knowledge-base</code></a> <code>pretrained</code>
- <b><a href="https://github.com/learningmatter-mit/geom">GEOM</a></b> (🥉6 ·  ⭐ 240 · 💀) - GEOM: Energy-annotated molecular conformations. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>
- <b><a href="https://github.com/aiqm/ANI1x_datasets">ANI-1x Datasets</a></b> (🥉6 ·  ⭐ 63 · 💀) - The ANI-1ccx and ANI-1x data sets, coupled-cluster and density functional theory properties for organic molecules. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Jesperkemist/perovskitedatabase">The Perovskite Database Project</a></b> (🥉5 ·  ⭐ 42 · 💀) - Perovskite Database Project aims at making all perovskite device data, both past and future, available in a form.. <code>Unlicensed</code> <code>community-resource</code>
- <b><a href="https://github.com/aimat-lab/3DSC">3DSC Database</a></b> (🥉5 ·  ⭐ 24 · 💀) - Repo for the paper publishing the superconductor database with 3D crystal structures. <code><a href="https://github.com/aimat-lab/3DSC/blob/main/LICENSE.md">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Superconductivity"><code>superconductors</code></a> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a>
- <b><a href="https://github.com/mathsphy/paper-data-redundancy">paper-data-redundancy</a></b> (🥉5 ·  ⭐ 7 · 💀) - Repo for the paper Exploiting redundancy in large materials datasets for efficient machine learning with less data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>small-data</code> <code>single-paper</code>
- <b><a href="https://github.com/drcassar/SciGlass">SciGlass</a></b> (🥉5 ·  ⭐ 6 · 💀) - The database contains a vast set of data on the properties of glass materials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/isayev/COMP6">COMP6 Benchmark dataset</a></b> (🥉4 ·  ⭐ 3 · 💀) - COMP6 Benchmark dataset for ML potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/HSE-LAMBDA/ai4material_design/blob/main/docs/DATA.md">2DMD dataset</a></b> (🥉4 ·  ⭐ 2 · 💀) - Code for Kazeev, N., Al-Maeeni, A.R., Romanov, I. et al. Sparse representation for machine learning the properties of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Crystallographic_defect"><code>material-defect</code></a>
- <b><a href="https://www.optimade.org/providers-dashboard/">OPTIMADE providers dashboard</a></b> (🥉3 ·  ⭐ 2 · 💀) - A dashboard of known providers. <code>Unlicensed</code>
- <b><a href="https://gitlab.com/brucefan1983/nep-data">nep-data</a></b> (🥉2 ·  ⭐ 20 · 💀) - Data related to the NEP machine-learned potential of GPUMD. <code>Unlicensed</code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://github.com/ulissigroup/tmqm_wB97MV">tmQM_wB97MV Dataset</a></b> (🥉2 ·  ⭐ 8 · 💀) - Code for Applying Large Graph Neural Networks to Predict Transition Metal Complex Energies Using the tmQM_wB97MV.. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
</details>
<br>

## Data Structures

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on providing data structures used in atomistic machine learning._

<details><summary><b><a href="https://github.com/deepmodeling/dpdata">dpdata</a></b> (🥇23 ·  ⭐ 250) - A Python package for manipulating atomistic data of software in computational science. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/deepmodeling/dpdata) (👨‍💻 72 · 🔀 160 · 📦 160):

	```
	git clone https://github.com/deepmodeling/dpdata
	```
- [PyPi](https://pypi.org/project/dpdata) (📥 120K / month · 📦 44 · ⏱️ 07.05.2026):
	```
	pip install dpdata
	```
- [Conda](https://anaconda.org/deepmodeling/dpdata) (📥 480 · ⏱️ 25.03.2025):
	```
	conda install -c deepmodeling dpdata
	```
</details>
<details><summary><b><a href="https://github.com/metatensor/metatensor">Metatensor</a></b> (🥈17 ·  ⭐ 100) - Self-describing sparse tensor data format for atomistic machine learning and beyond. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>Rust</code> <code>C-lang</code> <code>C++</code> <code>Python</code></summary>

- [GitHub](https://github.com/metatensor/metatensor) (👨‍💻 36 · 🔀 28 · 📦 16):

	```
	git clone https://github.com/metatensor/metatensor
	```
- [PyPi](https://pypi.org/project/metatensor) (📥 1.2K / month · ⏱️ 26.01.2024):
	```
	pip install metatensor
	```
</details>
<details><summary><b><a href="https://github.com/materialsproject/pyrho">mp-pyrho</a></b> (🥉14 ·  ⭐ 42 · 💤) - Tools for re-griding volumetric quantum chemistry data for machine-learning purposes. <code><a href="https://github.com/materialsproject/pyrho">Custom</a></code> <code>ML-DFT</code></summary>

- [GitHub](https://github.com/materialsproject/pyrho) (👨‍💻 10 · 🔀 10 · 📦 36):

	```
	git clone https://github.com/materialsproject/pyrho
	```
- [PyPi](https://pypi.org/project/mp-pyrho) (📥 41K / month · 📦 5 · ⏱️ 13.10.2025):
	```
	pip install mp-pyrho
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/dlpack">dlpack</a></b> (🥉12 ·  ⭐ 1.2K) - common in-memory tensor structure. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/dmlc/dlpack) (👨‍💻 35 · 🔀 160):

	```
	git clone https://github.com/dmlc/dlpack
	```
</details>
<br>

## Density functional theory (ML-DFT)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of DFT, such as density functional approximations (ML-DFA), the charge density, density of states, the Hamiltonian, etc._

🔗&nbsp;<b><a href="https://rodare.hzdr.de/record/2720">IKS-PIML</a></b>  - Code and generated data for the paper Inverting the Kohn-Sham equations with physics-informed machine learning.. <a href="https://en.wikipedia.org/wiki/Neural_operators"><code>neural-operator</code></a> <a href="https://en.wikipedia.org/wiki/Physics-informed_neural_networks"><code>pinn</code></a> <code>datasets</code> <code>single-paper</code>

🔗&nbsp;<b><a href="https://zenodo.org/records/10616893">M-OFDFT</a></b>  - Overcoming the Barrier of Orbital-Free Density Functional Theory in Molecular Systems Using Deep Learning.. <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <code>single-paper</code>

<details><summary><b><a href="https://github.com/google-research/google-research/tree/master/jax_dft">JAX-DFT</a></b> (🥇18 ·  ⭐ 38K) - This library provides basic building blocks that can construct DFT calculations as a differentiable program. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-research/google-research) (👨‍💻 880 · 🔀 8.4K):

	```
	git clone https://github.com/google-research/google-research
	```
</details>
<details><summary><b><a href="https://github.com/mala-project/mala">MALA</a></b> (🥇9 ·  ⭐ 98) - Materials Learning Algorithms. A framework for machine learning materials properties from first-principles data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mala-project/mala) (👨‍💻 47 · 🔀 27 · 📦 2):

	```
	git clone https://github.com/mala-project/mala
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/CiderPress">CiderPress</a></b> (🥈8 ·  ⭐ 13 · 💤) - A high-performance software package for training and evaluating machine-learned XC functionals using the CIDER.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Category:Density_functional_theory"><code>ml-functional</code></a> <code>C-lang</code></summary>

- [GitHub](https://github.com/mir-group/CiderPress) (👨‍💻 2 · 🔀 2):

	```
	git clone https://github.com/mir-group/CiderPress
	```
- [PyPi](https://pypi.org/project/ciderpress) (📥 190 / month · ⏱️ 13.03.2025):
	```
	pip install ciderpress
	```
</details>
<details><summary><b><a href="https://github.com/lcmd-epfl/Q-stack">Q-stack</a></b> (🥈6 ·  ⭐ 18) - Stack of codes for dedicated pre- and post-processing tasks for Quantum Machine Learning (QML). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Excited_state"><code>excited-states</code></a> <code>general-tool</code></summary>

- [GitHub](https://github.com/lcmd-epfl/Q-stack) (👨‍💻 8 · 🔀 7):

	```
	git clone https://github.com/lcmd-epfl/Q-stack
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEhamiltonians.jl">ACEhamiltonians</a></b> (🥈6 ·  ⭐ 17 · 💤) - Provides tools for constructing, fitting, and predicting self-consistent Hamiltonian and overlap matrices in solid-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACEhamiltonians.jl) (👨‍💻 5 · 🔀 7):

	```
	git clone https://github.com/ACEsuit/ACEhamiltonians.jl
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/dftio">dftio</a></b> (🥉5 ·  ⭐ 13 · 💤) - dftio is to assist machine learning communities to transcript DFT output into a format that is easy to read or used by.. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>data-structures</code> <code>workflows</code></summary>

- [GitHub](https://github.com/deepmodeling/dftio) (👨‍💻 5 · 🔀 8):

	```
	git clone https://github.com/deepmodeling/dftio
	```
</details>
<details><summary>Show 22 hidden projects...</summary>

- <b><a href="https://github.com/google-deepmind/deepmind-research/tree/master/density_functional_approximation_dm21">DM21</a></b> (🥇14 ·  ⭐ 13K · 💀) - This package provides a PySCF interface to the DM21 (DeepMind 21) family of exchange-correlation functionals described.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/divelab/AIRS/tree/main/OpenDFT/QHNet">QHNet</a></b> (🥇9 ·  ⭐ 470 · 💀) - Artificial Intelligence Research for Science (AIRS). <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/mzjb/DeepH-pack">DeepH-pack</a></b> (🥈8 ·  ⭐ 200 · 💀) - Deep neural networks for density functional theory Hamiltonian. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>Julia</code>
- <b><a href="https://github.com/deepmodeling/deepks-kit">DeePKS-kit</a></b> (🥈7 ·  ⭐ 120 · 💀) - a package for developing machine learning-based chemically accurate energy and density functional models. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Category:Density_functional_theory"><code>ml-functional</code></a>
- <b><a href="https://github.com/XanaduAI/GradDFT">Grad DFT</a></b> (🥈7 ·  ⭐ 75 · 💀) - GradDFT is a JAX-based library enabling the differentiable design and experimentation of exchange-correlation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/AIforGreatGood/charge3net">ChargE3Net</a></b> (🥈7 ·  ⭐ 75 · 💀) - [npj Comp. Mat.] Higher-order equivariant neural networks for charge density prediction in materials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/peterbjorgensen/DeepDFT">DeepDFT</a></b> (🥈6 ·  ⭐ 87 · 💀) - Official implementation of DeepDFT model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/QuantumLab-ZY/HamGNN">HamGNN</a></b> (🥈6 ·  ⭐ 50 · 💀) - An E(3) equivariant Graph Neural Network for predicting electronic Hamiltonian matrix. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <code>magnetism</code> <code>C-lang</code>
- <b><a href="https://github.com/MihailBogojeski/ml-dft">ML-DFT</a></b> (🥈6 ·  ⭐ 27 · 💀) - A package for density functional approximation using machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mzjb/xDeepH">xDeepH</a></b> (🥉5 ·  ⭐ 32 · 💀) - Extended DeepH (xDeepH) method for magnetic materials. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>magnetism</code> <code>Julia</code>
- <b><a href="https://github.com/biklooost/PROPhet">PROPhet</a></b> (🥉5 ·  ⭐ 16 · 💀) - PROPhet is a code to integrate machine learning techniques with first-principles quantum chemistry approaches. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>single-paper</code> <code>C++</code>
- <b><a href="https://github.com/ulissigroup/charge-density-models">charge-density-models</a></b> (🥉5 ·  ⭐ 13 · 💀) - Tools to build charge density models using [fairchem](https://github.com/FAIR-Chem/fairchem). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/semodi/neuralxc">NeuralXC</a></b> (🥉5 ·  ⭐ 12 · 💀) - Implementation of a machine learned density functional. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Xiaoxun-Gong/DeepH-E3">DeepH-E3</a></b> (🥉4 ·  ⭐ 9 · 💀) - General framework for E(3)-equivariant neural network representation of density functional theory Hamiltonian. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>magnetism</code>
- <b><a href="https://github.com/pedersor/ksr_dft">KSR-DFT</a></b> (🥉4 ·  ⭐ 3 · 💀) - Kohn-Sham regularizer for machine-learned DFT functionals. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mala-project/malada">MALADA</a></b> (🥉4 ·  ⭐ 1 · 💀) - MALA Data Acquisition: Helpful tools to build data for MALA. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/foxjas/CSNN">CSNN</a></b> (🥉4 ·  ⭐ 1 · 💀) - Primary codebase of CSNN - Concentric Spherical Neural Network for 3D Representation Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://gitlab.com/jmargraf/gprep">gprep</a></b> (🥉4 · 💀) - Fitting DFTB repulsive potentials with GPR. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/emotionor/APET">APET</a></b> (🥉3 · 💀) - Atomic Positional Embedding-based Transformer. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Density_of_states"><code>density-of-states</code></a> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>
- <b><a href="https://github.com/brunocuevas/a3md">A3MD</a></b> (🥉2 ·  ⭐ 8 · 💀) - MPNN-like + Analytic Density Model = Accurate electron densities. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <code>single-paper</code>
- <b><a href="https://github.com/siddarthachar/deepcdp">DeepCDP</a></b> (🥉2 ·  ⭐ 6 · 💀) - DeepCDP: Deep learning Charge Density Prediction. <code>Unlicensed</code>
- <b><a href="https://gitlab.com/jmargraf/kdf">kdft</a></b> (🥉1 ·  ⭐ 1 · 💀) - The Kernel Density Functional (KDF) code allows generating ML based DFT functionals. <code>Unlicensed</code>
</details>
<br>

## Educational Resources

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tutorials, guides, cookbooks, recipes, etc._

🔗&nbsp;<b><a href="https://ai4science101.github.io/">AI for Science 101</a></b>   <code>community-resource</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>

🔗&nbsp;<b><a href="https://sites.utu.fi/al4ms2023/media-and-tutorials/">AL4MS 2023 workshop tutorials</a></b>   <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a>

🔗&nbsp;<b><a href="https://www.elsevier.com/books-and-journals/book-companion/9780323900492">Quantum Chemistry in the Age of Machine Learning</a></b>  - Book, 2022.

<details><summary><b><a href="https://github.com/schwallergroup/ai4chem_course">AI4Chemistry course</a></b> (🥇9 ·  ⭐ 270) - EPFL AI for chemistry course, Spring 2023. https://schwallergroup.github.io/ai4chem_course. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>chemistry</code></summary>

- [GitHub](https://github.com/schwallergroup/ai4chem_course) (👨‍💻 10 · 🔀 63):

	```
	git clone https://github.com/schwallergroup/ai4chem_course
	```
</details>
<details><summary><b><a href="https://dmol.pub/">Deep Learning for Molecules and Materials Book</a></b> (🥇8 ·  ⭐ 690) - Deep learning for molecules and materials book. <code><a href="https://github.com/whitead/dmol-book/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/whitead/dmol-book) (👨‍💻 19 · 🔀 130):

	```
	git clone https://github.com/whitead/dmol-book
	```
</details>
<details><summary><b><a href="https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks">jarvis-tools-notebooks</a></b> (🥈7 ·  ⭐ 93 · 💤) - This repository is no longer maintained. For the latest updates and continued development, please visit:.. <code><a href="https://tldrlegal.com/search?q=NIST">NIST</a></code></summary>

- [GitHub](https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks) (👨‍💻 6 · 🔀 40):

	```
	git clone https://github.com/JARVIS-Materials-Design/jarvis-tools-notebooks
	```
</details>
<details><summary>Show 20 hidden projects...</summary>

- <b><a href="https://github.com/deepchem/DeepLearningLifeSciences">DeepLearningLifeSciences</a></b> (🥇10 ·  ⭐ 320 · 💀) - Example code from the book Deep Learning for the Life Sciences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/argonne-lcf/ai-science-training-series">Introduction to AI-driven Science on Supercomputers: A Student Training Series</a></b> (🥇8 ·  ⭐ 240 · 💤) -  <code>Unlicensed</code> <code>general-ml</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a>
- <b><a href="https://github.com/ceriottm/iam-notebooks">iam-notebooks</a></b> (🥈7 ·  ⭐ 26 · 💀) - Jupyter notebooks for the lectures of the Introduction to Atomistic Modeling. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/aronwalsh/MLforMaterials">MLforMaterials</a></b> (🥈6 ·  ⭐ 56 · 💀) - Online resource for a practical course in machine learning for materials research at Imperial College London.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>community-resource</code> <code>general-ml</code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a>
- <b><a href="https://github.com/ilyes319/mace-tutorials">MACE-tutorials</a></b> (🥈6 ·  ⭐ 50 · 💀) - Another set of tutorials for the MACE interatomic potential by one of the authors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://github.com/CompPhysVienna/MLSummerSchoolVienna2022">Machine Learning for Materials Hard and Soft</a></b> (🥈6 ·  ⭐ 39 · 💀) - ESI-DCAFM-TACO-VDSP Summer School on Machine Learning for Materials Hard and Soft. <code>Unlicensed</code>
- <b><a href="https://github.com/rdkit/rdkit-tutorials">RDKit Tutorials</a></b> (🥈6 ·  ⭐ 21 · 💀) - Tutorials to learn how to work with the RDKit. <code><a href="https://github.com/rdkit/rdkit-tutorials/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/anthony-wang/BestPractices">BestPractices</a></b> (🥈6 ·  ⭐ 19 · 💀) - Things that you should (and should not) do in your Materials Informatics research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Materials-Consortia/optimade-tutorial-exercises">OPTIMADE Tutorial Exercises</a></b> (🥈6 ·  ⭐ 15 · 💀) - Tutorial exercises for the OPTIMADE API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code>
- <b><a href="https://github.com/deepmodeling/AI4Science101">AI4Science101</a></b> (🥉5 ·  ⭐ 99 · 💀) - AI for Science. <code>Unlicensed</code>
- <b><a href="https://github.com/WardLT/applied-ai-for-materials">Applied AI for Materials</a></b> (🥉5 ·  ⭐ 59 · 💀) - Course materials for Applied AI for Materials Science and Engineering. <code>Unlicensed</code>
- <b><a href="https://github.com/deepmodeling/tutorials">DeepModeling Tutorials</a></b> (🥉5 ·  ⭐ 15 · 💀) - Tutorials for DeepModeling projects. <code>Unlicensed</code>
- <b><a href="https://github.com/chaitjo/geometric-gnn-dojo/blob/main/geometric_gnn_101.ipynb">Geometric GNN Dojo</a></b> (🥉5 ·  ⭐ 14 · 💀) - New to geometric GNNs: try our practical notebook, prepared for MPhil students at the University of Cambridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/Teoroo-CMC/DoE_Course_Material">Data Handling, DoE and Statistical Analysis for Material Chemists</a></b> (🥉5 ·  ⭐ 4 · 💀) - Notebooks for workshops of DoE course, hosted by the Computational Materials Chemistry group at Uppsala University. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/BingqingCheng/ML-in-chemistry-101">ML-in-chemistry-101</a></b> (🥉4 ·  ⭐ 51 · 💀) - The course materials for Machine Learning in Chemistry 101. <code>Unlicensed</code>
- <b><a href="https://github.com/gabor1/chemrev-gpr">chemrev-gpr</a></b> (🥉4 ·  ⭐ 12 · 💀) - Notebooks accompanying the paper on GPR in materials and molecules in Chemical Reviews 2020. <code>Unlicensed</code>
- <b><a href="https://github.com/ulissigroup/ml_catalysis_tutorials">ML for catalysis tutorials</a></b> (🥉4 ·  ⭐ 9 · 💀) - A jupyter book repo for tutorial on how to use OCP ML models for catalysis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Teoroo-CMC/PiNN_lab">PiNN Lab</a></b> (🥉4 ·  ⭐ 3 · 💀) - Material for running a lab session on atomic neural networks. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/mala-project/mala_tutorial">MALA Tutorial</a></b> (🥉1 ·  ⭐ 2 · 💀) - A full MALA hands-on tutorial. <code>Unlicensed</code>
- <b><a href="https://matsciedu.github.io/DSM-CORE">DSM-CORE</a></b> -  <code>Unlicensed</code>
</details>
<br>

## Explainable Artificial intelligence (XAI)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on explainability and model interpretability in atomistic ML._

<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/ur-whitelab/exmol">exmol</a></b> (🥇16 ·  ⭐ 330 · 💀) - Explainer for black box models that predict molecule properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aimat-lab/graph_attention_student">MEGAN: Multi Explanation Graph Attention Student</a></b> (🥉4 ·  ⭐ 12 · 🐣) - Minimal implementation of graph attention student model architecture. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
</details>
<br>

## Electronic structure methods (ML-ESM)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of electronic structure methods, which do not fit into either of the categories ML-WFT or ML-DFT._

<details><summary><b><a href="https://github.com/deepmodeling/DeePTB">DeePTB</a></b> (🥇14 ·  ⭐ 120) - DeePTB: A deep learning package for tight-binding Hamiltonian with ab initio accuracy. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>ML-DFT</code></summary>

- [GitHub](https://github.com/deepmodeling/DeePTB) (👨‍💻 15 · 🔀 33 · 📦 4):

	```
	git clone https://github.com/deepmodeling/DeePTB
	```
- [PyPi](https://pypi.org/project/dptb) (📥 540 / month · 📦 2 · ⏱️ 20.06.2026):
	```
	pip install dptb
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/masashitsubaki/QuantumDeepField_molecule">QDF for molecule</a></b> (🥈6 ·  ⭐ 68 · 💀) - Quantum deep field: data-driven wave function, electron density generation, and energy prediction and extrapolation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="http://qmlearn.rutgers.edu/">QMLearn</a></b> (🥉5 ·  ⭐ 12 · 💀) - Quantum Machine Learning by learning one-body reduced density matrices in the AO basis... <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/jmargraf/qpac">q-pac</a></b> (🥉5 ·  ⭐ 6 · 💀) - Kernel charge equilibration method. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a>
</details>
<br>

## General Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General tools for atomistic machine learning._

<details><summary><b><a href="https://github.com/rdkit/rdkit">RDKit</a></b> (🥇29 ·  ⭐ 3.5K) -  <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>C++</code> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a></summary>

- [GitHub](https://github.com/rdkit/rdkit) (👨‍💻 280 · 🔀 1K · 📦 3):

	```
	git clone https://github.com/rdkit/rdkit
	```
- [PyPi](https://pypi.org/project/rdkit) (📥 8.4M / month · 📦 1.9K · ⏱️ 16.07.2026):
	```
	pip install rdkit
	```
- [Conda](https://anaconda.org/rdkit/rdkit) (📥 2.6M · ⏱️ 25.03.2025):
	```
	conda install -c rdkit rdkit
	```
</details>
<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥇25 ·  ⭐ 6.9K) - Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry, Materials Science and Biology. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 260 · 🔀 2.3K · 📦 670):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 44K / month · 📦 32 · ⏱️ 20.07.2026):
	```
	pip install deepchem
	```
- [Conda](https://anaconda.org/conda-forge/deepchem) (📥 120K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge deepchem
	```
- [Docker Hub](https://hub.docker.com/r/deepchemio/deepchem) (📥 11K · ⭐ 5 · ⏱️ 15.07.2025):
	```
	docker pull deepchemio/deepchem
	```
</details>
<details><summary><b><a href="https://github.com/hackingmaterials/matminer">Matminer</a></b> (🥇22 ·  ⭐ 580) - Data mining for materials science. <code><a href="https://github.com/hackingmaterials/matminer/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/hackingmaterials/matminer) (👨‍💻 58 · 🔀 210 · 📦 490):

	```
	git clone https://github.com/hackingmaterials/matminer
	```
- [PyPi](https://pypi.org/project/matminer) (📥 65K / month · 📦 89 · ⏱️ 14.04.2026):
	```
	pip install matminer
	```
- [Conda](https://anaconda.org/conda-forge/matminer) (📥 120K · ⏱️ 14.04.2026):
	```
	conda install -c conda-forge matminer
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/jarvis">JARVIS-Tools</a></b> (🥈19 ·  ⭐ 370) - About JARVIS-Tools: an open-source software package for data-driven atomistic materials design. Publications:.. <code><a href="https://github.com/usnistgov/jarvis/blob/master/LICENSE.rst">Custom</a></code></summary>

- [GitHub](https://github.com/usnistgov/jarvis) (👨‍💻 16 · 🔀 140):

	```
	git clone https://github.com/usnistgov/jarvis
	```
- [PyPi](https://pypi.org/project/jarvis-tools) (📥 30K / month · 📦 44 · ⏱️ 18.06.2026):
	```
	pip install jarvis-tools
	```
- [Conda](https://anaconda.org/conda-forge/jarvis-tools) (📥 140K · ⏱️ 06.04.2026):
	```
	conda install -c conda-forge jarvis-tools
	```
</details>
<details><summary><b><a href="https://github.com/libAtoms/QUIP">QUIP</a></b> (🥈17 ·  ⭐ 390) - libAtoms/QUIP molecular dynamics framework: https://libatoms.github.io. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <code>Fortran</code></summary>

- [GitHub](https://github.com/libAtoms/QUIP) (👨‍💻 87 · 🔀 130 · 📦 46):

	```
	git clone https://github.com/libAtoms/QUIP
	```
- [PyPi](https://pypi.org/project/quippy-ase) (📥 1.4K / month · 📦 9 · ⏱️ 30.04.2026):
	```
	pip install quippy-ase
	```
- [Docker Hub](https://hub.docker.com/r/libatomsquip/quip) (📥 11K · ⭐ 4 · ⏱️ 24.04.2023):
	```
	docker pull libatomsquip/quip
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/maml">MAML</a></b> (🥈16 ·  ⭐ 430 · 💤) - Python for Materials Machine Learning, Materials Descriptors, Machine Learning Force Fields, Deep Learning, etc. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/materialsvirtuallab/maml) (👨‍💻 39 · 🔀 89 · 📦 17):

	```
	git clone https://github.com/materialsvirtuallab/maml
	```
- [PyPi](https://pypi.org/project/maml) (📥 870 / month · 📦 3 · ⏱️ 02.04.2025):
	```
	pip install maml
	```
</details>
<details><summary><b><a href="https://github.com/dralgroup/mlatom">MLatom</a></b> (🥈15 ·  ⭐ 51) - AI-enhanced computational chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>ML-DFT</code> <code>ML-ESM</code> <a href="https://en.wikipedia.org/wiki/Transfer_learning"><code>transfer-learning</code></a> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <a href="https://en.wikipedia.org/wiki/Spectroscopy"><code>spectroscopy</code></a> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a></summary>

- [GitHub](https://github.com/dralgroup/mlatom) (👨‍💻 6 · 🔀 10):

	```
	git clone https://github.com/dralgroup/mlatom
	```
- [PyPi](https://pypi.org/project/mlatom) (📥 1.5K / month · 📦 3 · ⏱️ 15.07.2026):
	```
	pip install mlatom
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/scikit-matter">Scikit-Matter</a></b> (🥈14 ·  ⭐ 91) - A collection of scikit-learn compatible utilities that implement methods born out of the materials science and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>scikit-learn</code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/scikit-matter) (👨‍💻 19 · 🔀 25):

	```
	git clone https://github.com/scikit-learn-contrib/scikit-matter
	```
- [PyPi](https://pypi.org/project/skmatter) (📥 5.5K / month · 📦 7 · ⏱️ 06.01.2026):
	```
	pip install skmatter
	```
- [Conda](https://anaconda.org/conda-forge/skmatter) (📥 8.1K · ⏱️ 08.01.2026):
	```
	conda install -c conda-forge skmatter
	```
</details>
<details><summary><b><a href="https://github.com/uw-cmg/MAST-ML">MAST-ML</a></b> (🥉8 ·  ⭐ 130 · 💤) - MAterials Simulation Toolkit for Machine Learning (MAST-ML). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/uw-cmg/MAST-ML) (👨‍💻 19 · 🔀 61):

	```
	git clone https://github.com/uw-cmg/MAST-ML
	```
</details>
<details><summary>Show 15 hidden projects...</summary>

- <b><a href="https://github.com/datamol-io/molfeat">Molfeat</a></b> (🥈18 ·  ⭐ 220 · 💀) - molfeat - the hub for all your molecular featurizers. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a> <code>pretrained</code>
- <b><a href="https://github.com/pycroscopy/atomai">AtomAI</a></b> (🥈16 ·  ⭐ 210 · 💀) - Deep and Machine Learning for Microscopy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Computer_vision"><code>computer-vision</code></a> <a href="https://en.wikipedia.org/wiki/Unsupervised_learning"><code>USL</code></a> <a href="https://en.wikipedia.org/wiki/Experimental_physics"><code>experimental-data</code></a>
- <b><a href="https://github.com/qmlcode/qml">QML</a></b> (🥉13 ·  ⭐ 200 · 💀) - QML: Quantum Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/hackingmaterials/automatminer">Automatminer</a></b> (🥉13 ·  ⭐ 73 · 💀) - An automatic engine for predicting materials properties. <code><a href="https://github.com/hackingmaterials/automatminer/blob/main/LICENSE">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Automated_machine_learning"><code>autoML</code></a>
- <b><a href="https://github.com/yoshida-lab/XenonPy">XenonPy</a></b> (🥉12 ·  ⭐ 130 · 💀) - XenonPy is a Python Software for Materials Informatics. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/divelab/AIRS">Artificial Intelligence for Science (AIRS)</a></b> (🥉9 ·  ⭐ 470 · 💀) - Artificial Intelligence Research for Science (AIRS). <code><a href="https://tldrlegal.com/search?q=GPL-3.0%20license">GPL-3.0 license</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>ML-DFT</code> <code>ML-WFT</code> <a href="https://en.wikipedia.org/wiki/Biomolecule"><code>biomolecules</code></a>
- <b><a href="https://github.com/Mariewelt/OpenChem">OpenChem</a></b> (🥉8 ·  ⭐ 410 · 💀) - OpenChem: Deep Learning toolkit for Computational Chemistry and Drug Design Research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepchem/jaxchem">JAXChem</a></b> (🥉7 ·  ⭐ 74 · 💀) - JAXChem is a JAX-based deep learning library for complex and versatile chemical modeling. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ulissigroup/amptorch">AMPtorch</a></b> (🥉7 ·  ⭐ 60 · 💀) - AMPtorch: Atomistic Machine Learning Package (AMP) - PyTorch. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/deepchem/torchchem">torchchem</a></b> (🥉7 ·  ⭐ 34 · 💀) - An experimental repo for experimenting with PyTorch models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lab-cosmo/equisolve">Equisolve</a></b> (🥉6 ·  ⭐ 4 · 💀) - A ML toolkit package utilizing the metatensor data format to build models for the prediction of equivariant properties.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>ML-IAP</code>
- <b><a href="https://github.com/ulissigroup/uncertainty_benchmarking">uncertainty_benchmarking</a></b> (🥉5 ·  ⭐ 42 · 💀) - Various code/notebooks to benchmark different ways we could estimate uncertainty in ML predictions. <code>Unlicensed</code> <code>benchmarking</code> <code>probabilistic</code>
- <b><a href="https://github.com/ACEsuit/ACEatoms.jl">ACEatoms</a></b> (🥉3 ·  ⭐ 2 · 💀) - Generic code for modelling atomic properties using ACE. <code><a href="https://github.com/ACEsuit/ACEatoms.jl/blob/main/ASL.md">Custom</a></code> <code>Julia</code>
- <b><a href="https://bitbucket.org/wolverton/magpie/">Magpie</a></b> (🥉3) - Materials Agnostic Platform for Informatics and Exploration (Magpie). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Java</code>
- <b><a href="https://github.com/hgheiberger/quantum-structure-ml">quantum-structure-ml</a></b> (🥉2 ·  ⭐ 2 · 💀) - Multi-class classification model for predicting the magnetic order of magnetic structures and a binary classification.. <code>Unlicensed</code> <code>magnetism</code> <code>benchmarking</code>
</details>
<br>

## Generative Models

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement generative models for atomistic ML._

<details><summary><b><a href="https://github.com/GT4SD/gt4sd-core">GT4SD</a></b> (🥇13 ·  ⭐ 380 · 💤) - GT4SD, an open-source library to accelerate hypothesis generation in the scientific discovery process. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/GT4SD/gt4sd-core) (👨‍💻 20 · 🔀 81):

	```
	git clone https://github.com/GT4SD/gt4sd-core
	```
- [PyPi](https://pypi.org/project/gt4sd) (📥 1.1K / month · ⏱️ 19.02.2025):
	```
	pip install gt4sd
	```
</details>
<details><summary><b><a href="https://github.com/xiaohang007/SLICES">SLICES and MatterGPT</a></b> (🥈11 ·  ⭐ 65 · 💤) - SLICES: An Invertible, Invariant, and String-based Crystal Representation [2023, Nature Communications] MatterGPT. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <a href="https://en.wikipedia.org/wiki/Language_model"><code>language-models</code></a> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <code>structure-prediction</code></summary>

- [GitHub](https://github.com/xiaohang007/SLICES) (👨‍💻 2 · 🔀 41 · 📦 7):

	```
	git clone https://github.com/xiaohang007/SLICES
	```
- [PyPi](https://pypi.org/project/slices) (📥 140 / month · 📦 1 · ⏱️ 14.10.2025):
	```
	pip install slices
	```
- [Docker Hub](https://hub.docker.com/r/xiaohang07/slices) (📥 900 · ⭐ 1 · ⏱️ 14.10.2025):
	```
	docker pull xiaohang07/slices
	```
</details>
<details><summary><b><a href="https://github.com/RokasEl/simgen">SiMGen</a></b> (🥈10 ·  ⭐ 29 · 💤) - Zero Shot Molecular Generation via Similarity Kernels. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Visualization"><code>viz</code></a></summary>

- [GitHub](https://github.com/RokasEl/simgen) (👨‍💻 4 · 🔀 5 · 📦 2):

	```
	git clone https://github.com/RokasEl/simgen
	```
- [PyPi](https://pypi.org/project/simgen) (📥 51 / month · ⏱️ 13.12.2024):
	```
	pip install simgen
	```
</details>
<details><summary>Show 13 hidden projects...</summary>

- <b><a href="https://github.com/whitead/synspace">synspace</a></b> (🥇15 ·  ⭐ 39 · 💀) - Synthesis generative model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/microsoft/molecule-generation">MoLeR</a></b> (🥇13 ·  ⭐ 310 · 💀) - Implementation of MoLeR: a generative model of molecular graphs which supports scaffold-constrained generation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/hspark1212/MOFTransformer">PMTransformer</a></b> (🥈11 ·  ⭐ 76 · 💀) - Universal Transfer Learning in Porous Materials, including MOFs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transfer_learning"><code>transfer-learning</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>
- <b><a href="https://github.com/ehoogeboom/e3_diffusion_for_molecules">EDM</a></b> (🥈8 ·  ⭐ 440 · 💀) - E(3) Equivariant Diffusion Model for Molecule Generation in 3D. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/G-SchNet">G-SchNet</a></b> (🥉7 ·  ⭐ 130 · 💀) - G-SchNet - a generative model for 3d molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/schnetpack-gschnet">SchNetPack G-SchNet</a></b> (🥉7 ·  ⭐ 41 · 💀) - G-SchNet extension for SchNetPack. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aksub99/molecular-vae">molecular-vae</a></b> (🥉7 ·  ⭐ 22 · 💀) - Pytorch implementation of the paper Automatic Chemical Design Using a Data-Driven Continuous Representation of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <code>single-paper</code>
- <b><a href="https://github.com/atomistic-machine-learning/cG-SchNet">cG-SchNet</a></b> (🥉6 ·  ⭐ 47 · 💀) - cG-SchNet - a conditional generative neural network for 3d molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/terraytherapeutics/COATI">COATI</a></b> (🥉6 ·  ⭐ 32 · 💀) - COATI: multi-modal contrastive pre-training for representing and traversing chemical space. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Multimodal_learning"><code>multimodal</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/tsudalab/rxngenerator">rxngenerator</a></b> (🥉5 ·  ⭐ 12 · 💀) - A generative model for molecular generation via multi-step chemical reactions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tsudalab/bVAE-IM">bVAE-IM</a></b> (🥉5 ·  ⭐ 11 · 💀) - Implementation of Chemical Design with GPU-based Ising Machine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Quantum_machine_learning"><code>QML</code></a> <code>single-paper</code>
- <b><a href="https://github.com/LigandPro/Matcha">Matcha</a></b> (🥉4 ·  ⭐ 16 · 🐣) - Implementation of Matcha: Multi-Stage Riemannian Flow Matching for Accurate and Physically Valid Molecular Docking. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <code>benchmarking</code>
- <b><a href="https://github.com/tsudalab/MolSLEPA">MolSLEPA</a></b> (🥉4 ·  ⭐ 5 · 💀) - Interpretable Fragment-based Molecule Design with Self-learning Entropic Population Annealing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Explainable_artificial_intelligence"><code>XAI</code></a>
</details>
<br>

## Interatomic Potentials (ML-IAP)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Machine learning interatomic potentials (aka ML-IAP, MLIAP, MLIP, MLP) and force fields (ML-FF) for molecular dynamics._

<details><summary><b><a href="https://opencatalystproject.org/">fairchem</a></b> (🥇22 ·  ⭐ 2.1K) - FAIR Chemistrys library of machine learning methods for chemistry. Formerly known as Open Catalyst Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a></summary>

- [GitHub]() (👨‍💻 69 · 🔀 480):

	```
	git clone https://github.com/FAIR-Chem/fairchem
	```
- [PyPi](https://pypi.org/project/fairchem-core) (📥 74K / month · 📦 48 · ⏱️ 08.06.2026):
	```
	pip install fairchem-core
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/deepmd-kit">DeePMD-kit</a></b> (🥇22 ·  ⭐ 2K) - A deep learning package for many-body potential energy representation and molecular dynamics. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>workflows</code> <code>C++</code></summary>

- [GitHub](https://github.com/deepmodeling/deepmd-kit) (👨‍💻 88 · 🔀 620 · 📦 57):

	```
	git clone https://github.com/deepmodeling/deepmd-kit
	```
- [PyPi](https://pypi.org/project/deepmd-kit) (📥 19K / month · 📦 21 · ⏱️ 06.06.2026):
	```
	pip install deepmd-kit
	```
- [Conda](https://anaconda.org/deepmodeling/deepmd-kit) (📥 4.1K · ⏱️ 25.03.2025):
	```
	conda install -c deepmodeling deepmd-kit
	```
- [Docker Hub](https://hub.docker.com/r/deepmodeling/deepmd-kit) (📥 6.2K · ⭐ 1 · ⏱️ 07.06.2026):
	```
	docker pull deepmodeling/deepmd-kit
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/nequip">NequIP</a></b> (🥇22 ·  ⭐ 940) - NequIP is a code for building E(3)-equivariant interatomic potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mir-group/nequip) (👨‍💻 45 · 🔀 210 · 📦 53):

	```
	git clone https://github.com/mir-group/nequip
	```
- [PyPi](https://pypi.org/project/nequip) (📥 9.3K / month · 📦 25 · ⏱️ 16.07.2026):
	```
	pip install nequip
	```
- [Conda](https://anaconda.org/conda-forge/nequip) (📥 28K · ⏱️ 16.07.2026):
	```
	conda install -c conda-forge nequip
	```
</details>
<details><summary><b><a href="https://github.com/aiqm/torchani">TorchANI</a></b> (🥇21 ·  ⭐ 550) - TorchANI 2.0 is an open-source library that supports training, development, and research of ANI-style neural network.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aiqm/torchani) (👨‍💻 23 · 🔀 140 · 📦 78):

	```
	git clone https://github.com/aiqm/torchani
	```
- [PyPi](https://pypi.org/project/torchani) (📥 8.1K / month · 📦 24 · ⏱️ 20.07.2026):
	```
	pip install torchani
	```
- [Conda](https://anaconda.org/conda-forge/torchani) (📥 1.4M · ⏱️ 23.07.2026):
	```
	conda install -c conda-forge torchani
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/matcalc">MatCalc</a></b> (🥇18 ·  ⭐ 120) - A python library for calculating materials properties from the PES. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>workflows</code> <code>benchmarking</code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <code>pretrained</code> <code>model-repository</code></summary>

- [GitHub](https://github.com/materialsvirtuallab/matcalc) (👨‍💻 23 · 🔀 27 · 📦 26):

	```
	git clone https://github.com/materialsvirtuallab/matcalc
	```
- [PyPi](https://pypi.org/project/matcalc) (📥 1.9K / month · 📦 14 · ⏱️ 28.05.2026):
	```
	pip install matcalc
	```
</details>
<details><summary><b><a href="https://github.com/stfc/janus-core">janus-core</a></b> (🥇16 ·  ⭐ 49) - Tools for machine learnt interatomic potentials. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>benchmarking</code> <code>workflows</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a></summary>

- [GitHub](https://github.com/stfc/janus-core) (👨‍💻 11 · 🔀 18 · 📦 16):

	```
	git clone https://github.com/stfc/janus-core
	```
- [PyPi](https://pypi.org/project/janus-core) (📥 4.1K / month · 📦 7 · ⏱️ 18.07.2026):
	```
	pip install janus-core
	```
</details>
<details><summary><b><a href="https://github.com/metatensor/metatrain">Metatrain</a></b> (🥇15 ·  ⭐ 74) - Train, fine-tune, and manipulate machine learning models for atomistic systems. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>workflows</code> <code>benchmarking</code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/metatensor/metatrain) (👨‍💻 37 · 🔀 37 · 📦 16):

	```
	git clone https://github.com/metatensor/metatrain
	```
- [PyPi](https://pypi.org/project/metatrain) (📦 6 · ⏱️ 01.07.2026):
	```
	pip install metatrain
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace">MACE</a></b> (🥈14 ·  ⭐ 1.2K) - MACE - Fast and accurate machine learning interatomic potentials with higher order equivariant message passing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace) (👨‍💻 72 · 🔀 420):

	```
	git clone https://github.com/ACEsuit/mace
	```
</details>
<details><summary><b><a href="https://github.com/torchmd/torchmd-net">TorchMD-NET</a></b> (🥈14 ·  ⭐ 470) - Training neural network potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <code>pretrained</code></summary>

- [GitHub](https://github.com/torchmd/torchmd-net) (👨‍💻 20 · 🔀 97):

	```
	git clone https://github.com/torchmd/torchmd-net
	```
- [Conda](https://anaconda.org/conda-forge/torchmd-net) (📥 920K · ⏱️ 18.03.2026):
	```
	conda install -c conda-forge torchmd-net
	```
</details>
<details><summary><b><a href="https://github.com/basf/mlipx">MLIPX - Machine-Learned Interatomic Potential eXploration</a></b> (🥈14 ·  ⭐ 96 · 💤) - Machine-Learned Interatomic Potential eXploration (mlipx) is designed at BASF for evaluating machine-learned.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code> <a href="https://en.wikipedia.org/wiki/Visualization"><code>viz</code></a> <code>workflows</code></summary>

- [GitHub](https://github.com/basf/mlipx) (👨‍💻 5 · 🔀 7 · 📦 7):

	```
	git clone https://github.com/basf/mlipx
	```
- [PyPi](https://pypi.org/project/mlipx) (📥 2.3K / month · 📦 4 · ⏱️ 09.06.2025):
	```
	pip install mlipx
	```
</details>
<details><summary><b><a href="https://github.com/openmm/NNPOps">NNPOps</a></b> (🥈13 ·  ⭐ 93) - High-performance operations for neural network potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>C++</code></summary>

- [GitHub](https://github.com/openmm/NNPOps) (👨‍💻 11 · 🔀 18):

	```
	git clone https://github.com/openmm/NNPOps
	```
- [Conda](https://anaconda.org/conda-forge/nnpops) (📥 760K · ⏱️ 17.06.2026):
	```
	conda install -c conda-forge nnpops
	```
</details>
<details><summary><b><a href="https://github.com/apax-hub/apax">apax</a></b> (🥈13 ·  ⭐ 36) - A flexible and performant framework for training machine learning potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/apax-hub/apax) (👨‍💻 11 · 🔀 7 · 📦 7):

	```
	git clone https://github.com/apax-hub/apax
	```
- [PyPi](https://pypi.org/project/apax) (📥 230 / month · 📦 2 · ⏱️ 18.03.2026):
	```
	pip install apax
	```
</details>
<details><summary><b><a href="https://gitlab.com/materials-modeling/calorine">calorine</a></b> (🥈13 ·  ⭐ 13) - A Python package for constructing and sampling neuroevolution potential models. https://doi.org/10.21105/joss.06264. <code><a href="https://gitlab.com/materials-modeling/calorine/-/blob/master/LICENSE">Custom</a></code></summary>

- [PyPi](https://pypi.org/project/calorine) (📥 2K / month · 📦 10 · ⏱️ 06.07.2026):
	```
	pip install calorine
	```
- [GitLab](https://gitlab.com/materials-modeling/calorine) (🔀 6 · 📋 130 - 8% open · ⏱️ 06.07.2026):

	```
	git clone https://gitlab.com/materials-modeling/calorine
	```
</details>
<details><summary><b><a href="https://github.com/jla-gardner/graph-pes">Graph-PES</a></b> (🥈12 ·  ⭐ 120) - Potential Energy Surfaces on Graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>pretrained</code></summary>

- [GitHub]() (👨‍💻 8 · 🔀 12 · 📦 3):

	```
	git clone https://github.com/jla-gardner/graph-pes
	```
- [PyPi](https://pypi.org/project/graph-pes) (📥 1.7K / month · 📦 2 · ⏱️ 20.02.2026):
	```
	pip install graph-pes
	```
</details>
<details><summary><b><a href="https://github.com/uf3/uf3">Ultra-Fast Force Fields (UF3)</a></b> (🥈12 ·  ⭐ 71) - UF3: a python library for generating ultra-fast interatomic potentials. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uf3/uf3) (👨‍💻 10 · 🔀 28 · 📦 2):

	```
	git clone https://github.com/uf3/uf3
	```
- [PyPi](https://pypi.org/project/uf3) (📥 170 / month · ⏱️ 27.10.2023):
	```
	pip install uf3
	```
</details>
<details><summary><b><a href="https://github.com/autoatml/autoplex">Autoplex</a></b> (🥈12 ·  ⭐ 39) - Code for automated fitting of machine learned interatomic potentials. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>benchmarking</code> <code>workflows</code></summary>

- [GitHub](https://github.com/autoatml/autoplex) (👨‍💻 15 · 🔀 5 · 📦 2):

	```
	git clone https://github.com/autoatml/autoplex
	```
- [PyPi](https://pypi.org/project/autoplex) (📥 200 / month · ⏱️ 14.05.2026):
	```
	pip install autoplex
	```
</details>
<details><summary><b><a href="https://github.com/stfc/aiida-mlip">aiida-mlip</a></b> (🥈11 ·  ⭐ 16 · 💤) - machine learning interatomic potentials aiida plugin. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>workflows</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a></summary>

- [GitHub](https://github.com/stfc/aiida-mlip) (👨‍💻 8 · 🔀 10 · 📦 3):

	```
	git clone https://github.com/stfc/aiida-mlip
	```
- [PyPi](https://pypi.org/project/aiida-mlip) (📥 340 / month · ⏱️ 17.11.2025):
	```
	pip install aiida-mlip
	```
</details>
<details><summary><b><a href="https://github.com/mir-group/allegro">Allegro</a></b> (🥈10 ·  ⭐ 480) - Allegro is a code for building highly scalable E(3)-equivariant interatomic potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mir-group/allegro) (👨‍💻 10 · 🔀 74 · 📦 2):

	```
	git clone https://github.com/mir-group/allegro
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/NeuralForceField">Neural Force Field</a></b> (🥈10 ·  ⭐ 280 · 💤) - Neural Network Force Field based on PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code></summary>

- [GitHub](https://github.com/learningmatter-mit/NeuralForceField) (👨‍💻 45 · 🔀 61):

	```
	git clone https://github.com/learningmatter-mit/NeuralForceField
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/CCS">CCS_fit</a></b> (🥈9 ·  ⭐ 10 · 💤) - Curvature Constrained Splines. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/CCS) (👨‍💻 8 · 🔀 11):

	```
	git clone https://github.com/Teoroo-CMC/CCS
	```
- [PyPi](https://pypi.org/project/ccs_fit) (📥 260 / month · ⏱️ 16.02.2024):
	```
	pip install ccs_fit
	```
</details>
<details><summary><b><a href="https://github.com/Teoroo-CMC/PiNN">PiNN</a></b> (🥈8 ·  ⭐ 120) - A Python library for building atomic neural networks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Teoroo-CMC/PiNN) (👨‍💻 8 · 🔀 36):

	```
	git clone https://github.com/Teoroo-CMC/PiNN
	```
- [Docker Hub](https://hub.docker.com/r/teoroo/pinn) (📥 820 · ⏱️ 26.03.2026):
	```
	docker pull teoroo/pinn
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/deepmd-gnn">DeepMD-GNN</a></b> (🥈8 ·  ⭐ 55) - DeePMD-kit plugin for various graph neural network models. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <code>C++</code></summary>

- [GitHub](https://github.com/deepmodeling/deepmd-gnn) (👨‍💻 10 · 🔀 9):

	```
	git clone https://github.com/deepmodeling/deepmd-gnn
	```
</details>
<details><summary><b><a href="https://github.com/libAtoms/workflow">wfl</a></b> (🥈8 ·  ⭐ 43 · 💤) - Workflow is a Python toolkit for building interatomic potential creation and atomistic simulation workflows. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code> <code>workflows</code> <a href="https://en.wikipedia.org/wiki/High-throughput_computing"><code>HTC</code></a></summary>

- [GitHub](https://github.com/libAtoms/workflow) (👨‍💻 21 · 🔀 20 · 📦 6):

	```
	git clone https://github.com/libAtoms/workflow
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace-jax">MACE-Jax</a></b> (🥉7 ·  ⭐ 80 · 💤) - Equivariant machine learning interatomic potentials in JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ACEsuit/mace-jax) (👨‍💻 6 · 🔀 17):

	```
	git clone https://github.com/ACEsuit/mace-jax
	```
</details>
<details><summary><b><a href="https://libatoms.github.io/">GAP</a></b> (🥉6 ·  ⭐ 44 · 💤) - Gaussian Approximation Potential (GAP). <code><a href="https://github.com/libAtoms/GAP/blob/main/LICENSE.md">Custom</a></code></summary>

- [GitHub](https://github.com/libAtoms/GAP) (👨‍💻 13 · 🔀 20):

	```
	git clone https://github.com/libAtoms/GAP
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/ACEfit.jl">ACEfit</a></b> (🥉6 ·  ⭐ 7 · 💤) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/ACEfit.jl) (👨‍💻 10 · 🔀 9):

	```
	git clone https://github.com/ACEsuit/ACEfit.jl
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/matml">MatML</a></b> (🥉5 ·  ⭐ 8 · 💤) - Full MatML Docker image, including MatGL, MatCalc, MatPES and LAMMPS with ML-GNNP and ML-SNAP. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <code>pretrained</code></summary>

- [GitHub](https://github.com/materialsvirtuallab/matml) (👨‍💻 2):

	```
	git clone https://github.com/materialsvirtuallab/matml
	```
- [Docker Hub](https://hub.docker.com/r/materialsvirtuallab/matml) (📥 720 · ⭐ 2 · ⏱️ 08.04.2025):
	```
	docker pull materialsvirtuallab/matml
	```
</details>
<details><summary>Show 46 hidden projects...</summary>

- <b><a href="https://github.com/materialsvirtuallab/megnet">MEGNet</a></b> (🥇18 ·  ⭐ 540 · 💀) - Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://en.wikipedia.org/wiki/Multifidelity_simulation"><code>multifidelity</code></a>
- <b><a href="https://github.com/stefanch/sGDML">sGDML</a></b> (🥈14 ·  ⭐ 140 · 💀) - sGDML - Reference implementation of the Symmetric Gradient Domain Machine Learning model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/openkim/kliff">KLIFF</a></b> (🥈13 ·  ⭐ 35 · 💀) - KIM-based Learning-Integrated Fitting Framework for interatomic potentials. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <code>probabilistic</code> <code>workflows</code>
- <b><a href="https://github.com/MaterSim/PyXtal_FF">PyXtalFF</a></b> (🥈11 ·  ⭐ 85 · 💀) - Machine Learning Interatomic Potential Predictions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/SchNet">SchNet</a></b> (🥈9 ·  ⭐ 210 · 💀) - SchNet - a deep learning architecture for quantum chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/isayev/ASE_ANI">ANI-1</a></b> (🥈9 ·  ⭐ 150 · 💀) - ANI-1 neural net potential with python interface (ASE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://cortner.github.io/ACEweb/software/">Pacemaker</a></b> (🥈9 ·  ⭐ 100 · 💀) - Python package for fitting atomic cluster expansion (ACE) potentials. <code><a href="https://github.com/ICAMS/python-ace/blob/master/LICENSE.md">Custom</a></code>
- <b><a href="https://github.com/atomicarchitects/equiformer_v2">EquiformerV2</a></b> (🥈8 ·  ⭐ 300 · 💀) - [ICLR 2024] EquiformerV2: Improved Equivariant Transformer for Scaling to Higher-Degree Representations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/jparkhill/TensorMol">TensorMol</a></b> (🥈8 ·  ⭐ 250 · 💀) - Tensorflow + Molecules = TensorMol. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>single-paper</code>
- <b><a href="https://github.com/CompPhysVienna/n2p2">n2p2</a></b> (🥈8 ·  ⭐ 240 · 💀) - n2p2 - A Neural Network Potential Package. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>C++</code>
- <b><a href="https://github.com/TUM-DAML/gemnet_pytorch">GemNet</a></b> (🥈8 ·  ⭐ 210 · 💀) - GemNet model in PyTorch, as proposed in GemNet: Universal Directional Graph Neural Networks for Molecules (NeurIPS.. <code><a href="https://github.com/TUM-DAML/gemnet_pytorch/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/aiqm/aimnet">AIMNet</a></b> (🥈8 ·  ⭐ 100 · 💀) - Atoms In Molecules Neural Network Potential. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/aimat-lab/NNsForMD">NNsforMD</a></b> (🥈8 ·  ⭐ 11 · 💀) - Neural network class for molecular dynamics to predict potential energy, forces and non-adiabatic couplings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/HSE-LAMBDA/MEGNetSparse">MEGNetSparse</a></b> (🥈8 ·  ⭐ 1 · 💀) - A library imlementing a graph neural network with sparse representation from Code for Kazeev, N., Al-Maeeni, A.R.,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Crystallographic_defect"><code>material-defect</code></a>
- <b><a href="https://github.com/gasteigerjo/dimenet">DimeNet</a></b> (🥉7 ·  ⭐ 280 · 💀) - DimeNet and DimeNet++ models, as proposed in Directional Message Passing for Molecular Graphs (ICLR 2020) and Fast and.. <code><a href="https://github.com/gasteigerjo/dimenet/blob/master/LICENSE.md">Custom</a></code>
- <b><a href="https://github.com/TinkerTools/tinker-hp">tinker-hp</a></b> (🥉7 ·  ⭐ 98 · 💀) - Tinker-HP: High-Performance Massively Parallel Evolution of Tinker on CPUs & GPUs. <code><a href="https://github.com/TinkerTools/tinker-hp/blob/master/license-Tinker.pdf">Custom</a></code>
- <b><a href="https://github.com/MMunibas/PhysNet">PhysNet</a></b> (🥉7 ·  ⭐ 93 · 💀) - Code for training PhysNet models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a>
- <b><a href="https://github.com/thorben-frank/mlff">So3krates (MLFF)</a></b> (🥉7 ·  ⭐ 80 · 💀) - Build neural networks for machine learning force fields with JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/MDIL-SNU/SIMPLE-NN">SIMPLE-NN</a></b> (🥉7 ·  ⭐ 48 · 💀) - SIMPLE-NN(SNU Interatomic Machine-learning PotentiaL packagE version Neural Network). <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/learningmatter-mit/Atomistic-Adversarial-Attacks">Atomistic Adversarial Attacks</a></b> (🥉7 ·  ⭐ 40 · 💀) - Code for performing adversarial attacks on atomistic systems using NN potentials. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code>
- <b><a href="https://github.com/materialsvirtuallab/snap">SNAP</a></b> (🥉7 ·  ⭐ 36 · 💀) - Repository for spectral neighbor analysis potential (SNAP) model development. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ACEsuit/ACE.jl">ACE.jl</a></b> (🥉6 ·  ⭐ 66 · 💀) - Parameterisation of Equivariant Properties of Particle Systems. <code><a href="https://github.com/ACEsuit/ACE.jl/blob/main/license/mit.md">Custom</a></code> <code>Julia</code>
- <b><a href="https://github.com/MDIL-SNU/SIMPLE-NN_v2">SIMPLE-NN v2</a></b> (🥉6 ·  ⭐ 43 · 💀) - SIMPLE-NN is an open package that constructs Behler-Parrinello-type neural-network interatomic potentials from ab.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/lanl/alf">ALF</a></b> (🥉6 ·  ⭐ 36 · 💀) - A framework for performing active learning for training machine-learned interatomic potentials. <code><a href="https://github.com/lanl/ALF/blob/main/LICENSE">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a>
- <b><a href="https://gitlab.com/ashapeev/mlip-3">MLIP-3</a></b> (🥉6 ·  ⭐ 27 · 💀) - MLIP-3: Active learning on atomic environments with Moment Tensor Potentials (MTP). <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code>C++</code>
- <b><a href="https://github.com/sirmarcel/glp">glp</a></b> (🥉6 ·  ⭐ 26 · 💀) - tools for graph-based machine-learning potentials in jax. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://acesuit.github.io/">ACE1.jl</a></b> (🥉6 ·  ⭐ 22 · 💀) - Atomic Cluster Expansion for Modelling Invariant Atomic Properties. <code><a href="https://github.com/ACEsuit/ACE1.jl/blob/main/ASL.md">Custom</a></code> <code>Julia</code>
- <b><a href="https://github.com/bigd4/PyNEP">PyNEP</a></b> (🥉6 ·  ⭐ 14 · 💀) - A python interface of the machine learning potential NEP used in GPUMD. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/PANNAdevs/panna">PANNA</a></b> (🥉6 ·  ⭐ 11 · 💀) - A package to train and validate all-to-all connected network models for BP[1] and modified-BP[2] type local atomic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/MMunibas/Asparagus">Asparagus</a></b> (🥉6 ·  ⭐ 9 · 💀) - Program Package for Sampling, Training and Applying ML-based Potential models https://doi.org/10.48550/arXiv.2407.15175. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>workflows</code> <code>sampling</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://cortner.github.io/ACEweb/software/">TensorPotential</a></b> (🥉5 ·  ⭐ 13 · 💀) - Tensorpotential is a TensorFlow based tool for development, fitting ML interatomic potentials from electronic.. <code><a href="https://github.com/ICAMS/TensorPotential/blob/main/LICENSE.md">Custom</a></code>
- <b><a href="https://github.com/mcaroba/turbogap">TurboGAP</a></b> (🥉5 ·  ⭐ 12 · 💀) - The TurboGAP code. <code><a href="https://github.com/mcaroba/turbogap/blob/master/LICENSE.md">Custom</a></code> <code>Fortran</code>
- <b><a href="https://gitlab.com/zaverkin_v/gmnn">GN-MM</a></b> (🥉5 ·  ⭐ 12 · 💀) - The Gaussian Moment Neural Network (GM-NN) package developed for large-scale atomistic simulations employing atomistic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <code>magnetism</code>
- <b><a href="https://github.com/RowleyGroup/MLXDM">MLXDM</a></b> (🥉5 ·  ⭐ 5 · 💀) - A Neural Network Potential with Rigorous Treatment of Long-Range Dispersion https://doi.org/10.1039/D2DD00150K. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>long-range</code>
- <b><a href="https://github.com/Luthaf/alchemical-learning">Alchemical learning</a></b> (🥉5 ·  ⭐ 3 · 💀) - Code for the Modeling high-entropy transition metal alloys with alchemical compression article. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <a href="https://www.google.com/search?q=defects+and+disorder+in+materials"><code>Defects & Disorder</code></a>
- <b><a href="https://github.com/ibayashi-hikaru/allegro-legato">Allegro-Legato</a></b> (🥉4 ·  ⭐ 20 · 💀) - An extension of Allegro with enhanced robustness and time-to-failure. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://github.com/libAtoms/testing-framework">testing-framework</a></b> (🥉4 ·  ⭐ 11 · 💀) - The purpose of this repository is to aid the testing of a large number of interatomic potentials for a variety of.. <code>Unlicensed</code> <code>benchmarking</code>
- <b><a href="https://github.com/AaltoRSE/PeriodicPotentials">PeriodicPotentials</a></b> (🥉4 · 💀) - A Periodic table app that displays potentials based on the selected elements. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>community-resource</code> <a href="https://en.wikipedia.org/wiki/Visualization"><code>viz</code></a> <code>JavaScript</code>
- <b><a href="https://github.com/mariogeiger/nequip-jax">NequIP-JAX</a></b> (🥉3 ·  ⭐ 18 · 💀) - JAX implementation of the NequIP interatomic potential. <code>Unlicensed</code>
- <b><a href="https://github.com/lmj1029123/SingleNN">SingleNN</a></b> (🥉3 ·  ⭐ 6 · 💀) - An efficient package for training and executing neural-network interatomic potentials. <code>Unlicensed</code> <code>C++</code>
- <b><a href="https://github.com/jla-gardner/nnp-pre-training">nnp-pre-training</a></b> (🥉3 ·  ⭐ 6 · 💀) - Synthetic pre-training for neural-network interatomic potentials. <code>Unlicensed</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://github.com/ACEsuit/ACEworkflows">ACE Workflows</a></b> (🥉3 · 💀) - Workflow Examples for ACE Models. <code>Unlicensed</code> <code>Julia</code> <code>workflows</code>
- <b><a href="https://gitlab.com/flame-code/PyFLAME">PyFLAME</a></b> (🥉3 · 💀) - An automated approach for developing neural network interatomic potentials with FLAME.. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <code>structure-prediction</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <code>Fortran</code>
- <b><a href="https://github.com/cesmix-mit/mlp">mlp</a></b> (🥉2 ·  ⭐ 1 · 💀) - Proper orthogonal descriptors for efficient and accurate interatomic potentials... <code>Unlicensed</code> <code>Julia</code>
- <b><a href="https://www.uni-goettingen.de/de/560580.html">RuNNer</a></b> (🥉2) - The RuNNer Neural Network Energy Representation is a Fortran-based framework for the construction of Behler-.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>Fortran</code>
- <b><a href="https://github.com/ACEsuit/ACE1pack.jl">ACE1Pack.jl</a></b> (🥉1) - Provides convenience functionality for the usage of ACE1.jl, ACEfit.jl, JuLIP.jl for fitting interatomic potentials.. <code>Unlicensed</code> <code>Julia</code>
</details>
<br>

## Language Models

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that use (large) language models (LMs, LLMs) or natural language procesing (NLP) techniques for atomistic ML._

🔗&nbsp;<b><a href="https://huggingface.co/spaces/jablonkagroup/MaCBench-Leaderboard">MaCBench Leaderboard</a></b>  - Leaderboard for multimodal language models for chemistry & materials research. <code>community-resource</code> <code>benchmarking</code> <code>datasets</code>

<details><summary><b><a href="https://futurehouse.gitbook.io/futurehouse-cookbook">paper-qa</a></b> (🥇17 ·  ⭐ 8.3K) - LLM Chain for answering questions from docs. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Large_language_model#Agency"><code>ai-agent</code></a></summary>

- [GitHub]() (🔀 840):

	```
	git clone https://github.com/whitead/paper-qa
	```
- [PyPi](https://pypi.org/project/paper-qa) (📥 51K / month · 📦 24 · ⏱️ 18.03.2026):
	```
	pip install paper-qa
	```
</details>
<details><summary><b><a href="https://github.com/OpenBioML/chemnlp">OpenBioML ChemNLP</a></b> (🥈13 ·  ⭐ 180) - ChemNLP project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>datasets</code></summary>

- [GitHub](https://github.com/OpenBioML/chemnlp) (👨‍💻 29 · 🔀 46):

	```
	git clone https://github.com/OpenBioML/chemnlp
	```
- [PyPi](https://pypi.org/project/chemnlp) (📦 1 · ⏱️ 07.08.2023):
	```
	pip install chemnlp
	```
</details>
<details><summary><b><a href="https://github.com/vertaix/LLM-Prop">LLM-Prop</a></b> (🥉7 ·  ⭐ 58) - A repository for the LLM-Prop implementation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vertaix/LLM-Prop) (👨‍💻 7 · 🔀 11):

	```
	git clone https://github.com/vertaix/LLM-Prop
	```
</details>
<details><summary>Show 18 hidden projects...</summary>

- <b><a href="https://github.com/mcs07/ChemDataExtractor">ChemDataExtractor</a></b> (🥇16 ·  ⭐ 250 · 💀) - Automatically extract chemical information from scientific documents. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>literature-data</code>
- <b><a href="https://github.com/ur-whitelab/chemcrow-public">ChemCrow</a></b> (🥇15 ·  ⭐ 670 · 💀) - Open source package for the accurate solution of reasoning-intensive chemical tasks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Large_language_model#Agency"><code>ai-agent</code></a>
- <b><a href="https://github.com/kjappelbaum/gptchem">gptchem</a></b> (🥈13 ·  ⭐ 170 · 💀) - Use GPT-3 to solve chemistry problems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/usnistgov/atomgpt">AtomGPT</a></b> (🥈11 ·  ⭐ 50 · 💀) - AtomGPT & DiffractGPT : Generative Pretrained Transformer Models for Forward and Inverse Materials Design.. <code><a href="https://github.com/usnistgov/atomgpt/blob/main/LICENSE.rst">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>
- <b><a href="https://github.com/usnistgov/chemnlp">NIST ChemNLP</a></b> (🥈11 ·  ⭐ 28 · 💀) - ChemNLP: A Natural Language Processing based Library for Materials Chemistry Text Data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>literature-data</code>
- <b><a href="https://github.com/materialsintelligence/mat2vec">mat2vec</a></b> (🥈10 ·  ⭐ 630 · 💀) - Supplementary Materials for Tshitoyan et al. Unsupervised word embeddings capture latent knowledge from materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/whitead/nlcc">nlcc</a></b> (🥈10 ·  ⭐ 38 · 💀) - Natural language computational chemistry command line interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/IBM/molformer">MoLFormer</a></b> (🥈9 ·  ⭐ 210 · 💀) - Repository for MolFormer. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>
- <b><a href="https://github.com/Yeonghun1675/ChatMOF">ChatMOF</a></b> (🥈9 ·  ⭐ 11 · 💀) - Predict and Inverse design for metal-organic framework with large-language models (llms). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a>
- <b><a href="https://pypi.org/project/chembench/">ChemBench</a></b> (🥉8 · 💀) - Benchmark chemistry performance of LLMs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code> <a href="https://en.wikipedia.org/wiki/Multimodal_learning"><code>multimodal</code></a>
- <b><a href="https://github.com/microsoft/molskill">MolSkill</a></b> (🥉7 ·  ⭐ 24 · 💀) - Learning chemical intuition from humans in the loop. Supporting code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Recommender_system"><code>recommender</code></a>
- <b><a href="https://github.com/facebookresearch/crystal-text-llm">crystal-text-llm</a></b> (🥉6 ·  ⭐ 65 · 💀) - Large language models to generate stable crystals. <code><a href="https://tldrlegal.com/search?q=CC-BY-NC-4.0">CC-BY-NC-4.0</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a>
- <b><a href="https://github.com/chiang-yuan/llamp">LLaMP</a></b> (🥉6 ·  ⭐ 41 · 💀) - A web app and Python API for multi-modal RAG framework to ground LLMs on high-fidelity materials informatics. An.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://en.wikipedia.org/wiki/Multimodal_learning"><code>multimodal</code></a> <a href="https://en.wikipedia.org/wiki/Retrieval-augmented_generation"><code>RAG</code></a> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <code>pretrained</code> <code>JavaScript</code> <code>Python</code>
- <b><a href="https://github.com/CFN-softbio/SciBot">SciBot</a></b> (🥉5 ·  ⭐ 28 · 💀) - SciBot is a simple demo of building a domain-specific chatbot for science. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Large_language_model#Agency"><code>ai-agent</code></a>
- <b><a href="https://github.com/lamalab-org/chemlift">chemlift</a></b> (🥉5 ·  ⭐ 14 · 💀) - Language-interfaced fine-tuning for chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lamm-mit/Cephalo">Cephalo</a></b> (🥉5 ·  ⭐ 8 · 💀) - Multimodal Vision-Language Models for Bio-Inspired Materials Analysis and Design. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <a href="https://en.wikipedia.org/wiki/Multimodal_learning"><code>multimodal</code></a> <code>pretrained</code>
- <b><a href="https://github.com/OSU-NLP-Group/LLM4Chem">LLM4Chem</a></b> (🥉4 ·  ⭐ 4 · 💀) - Advancing Large Language Models for Chemistry with a Large-Scale, Comprehensive, High-Quality Instruction Tuning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <code>datasets</code>
- <b><a href="https://github.com/hoon-ock/CatBERTa">CatBERTa</a></b> (🥉2 ·  ⭐ 3 · 💀) - Large Language Model for Catalyst Property Prediction. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a>
</details>
<br>

## Materials Discovery

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement materials discovery methods using atomistic ML._

<details><summary><b><a href="https://github.com/WMD-group/SMACT">SMACT</a></b> (🥇20 ·  ⭐ 130) - Python package to aid materials design and informatics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/High-throughput_computing"><code>HTC</code></a> <code>structure-prediction</code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a></summary>

- [GitHub](https://github.com/WMD-group/SMACT) (👨‍💻 51 · 🔀 29 · 📦 78):

	```
	git clone https://github.com/WMD-group/SMACT
	```
- [PyPi](https://pypi.org/project/smact) (📥 13K / month · 📦 14 · ⏱️ 03.03.2026):
	```
	pip install smact
	```
- [Conda](https://anaconda.org/conda-forge/smact) (📥 12K · ⏱️ 15.07.2026):
	```
	conda install -c conda-forge smact
	```
</details>
<details><summary><b><a href="https://github.com/LopezGroup-ICIQ/care">CARE</a></b> (🥇13 ·  ⭐ 87) - Automated creation and manipulation of chemical reaction networks (CRNs) in heterogeneous catalysis, powered by state-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <code>ML-IAP</code> <code>Julia</code></summary>

- [GitHub](https://github.com/LopezGroup-ICIQ/care) (👨‍💻 5 · 🔀 14):

	```
	git clone https://github.com/LopezGroup-ICIQ/care
	```
- [PyPi](https://pypi.org/project/care-crn) (📥 410 / month · ⏱️ 06.07.2026):
	```
	pip install care-crn
	```
</details>
<details><summary><b><a href="https://gitlab.com/cest-group/boss">BOSS</a></b> (🥈12 ·  ⭐ 27) - Bayesian Optimization Structure Search (BOSS). <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>probabilistic</code></summary>

- [PyPi](https://pypi.org/project/aalto-boss) (📥 390 / month · ⏱️ 31.05.2026):
	```
	pip install aalto-boss
	```
- [GitLab](https://gitlab.com/cest-group/boss) (🔀 15 · 📋 40 - 15% open · ⏱️ 31.05.2026):

	```
	git clone https://gitlab.com/cest-group/boss
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/mattergen">MatterGen</a></b> (🥈11 ·  ⭐ 1.7K) - Official implementation of MatterGen -- a generative model for inorganic materials design across the periodic table.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>structure-prediction</code> <code>pretrained</code></summary>

- [GitHub](https://github.com/microsoft/mattergen) (👨‍💻 14 · 🔀 310):

	```
	git clone https://github.com/microsoft/mattergen
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/materials_discovery">Materials Discovery: GNoME</a></b> (🥈9 ·  ⭐ 800 · 💀) - Graph Networks for Materials Science (GNoME) and dataset of 381,000 novel stable materials. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <code>datasets</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Proprietary_software"><code>proprietary</code></a></summary>

- [GitHub](https://github.com/google-deepmind/materials_discovery) (👨‍💻 3 · 🔀 130):

	```
	git clone https://github.com/google-deepmind/materials_discovery
	```
</details>
<details><summary><b><a href="https://agox.gitlab.io/agox/">AGOX</a></b> (🥈9 ·  ⭐ 18) - AGOX is a package for global optimization of atomic system using e.g. the energy calculated from density functional.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a></summary>

- [PyPi](https://pypi.org/project/agox) (📥 160 / month · 📦 3 · ⏱️ 04.02.2026):
	```
	pip install agox
	```
- [GitLab](https://gitlab.com/agox/agox) (🔀 8 · 📋 29 - 31% open · ⏱️ 04.02.2026):

	```
	git clone https://gitlab.com/agox/agox
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/CompRhys/aviary">aviary</a></b> (🥉7 ·  ⭐ 38 · 💀) - The Wren sits on its Roost in the Aviary. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://gitlab.com/bigd4/magus">MAGUS</a></b> (🥉5 ·  ⭐ 120 · 💀) - Machine learning And Graph theory assisted Universal structure Searcher. <code>Unlicensed</code> <code>structure-prediction</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a>
- <b><a href="https://github.com/takahashi-akira-36m/ml_atomate">ML-atomate</a></b> (🥉4 ·  ⭐ 5 · 💀) - Machine learning-assisted Atomate code for autonomous computational materials screening. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <code>workflows</code>
- <b><a href="https://github.com/ulissigroup/CAMD">Computational Autonomy for Materials Discovery (CAMD)</a></b> (🥉4 ·  ⭐ 1 · 💀) - Agent-based sequential learning software for materials discovery. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/aced-differentiate/closed-loop-acceleration-benchmarks">closed-loop-acceleration-benchmarks</a></b> (🥉4 · 💀) - Data and scripts in support of the publication By how much can closed-loop frameworks accelerate computational.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <code>single-paper</code>
- <b><a href="https://github.com/minoru938/cspml">CSPML (crystal structure prediction with machine learning-based element substitution)</a></b> (🥉3 ·  ⭐ 17 · 💀) - Original implementation of CSPML. <code>Unlicensed</code> <code>structure-prediction</code>
- <b><a href="https://github.com/MDIL-SNU/SPINNER">SPINNER</a></b> (🥉3 ·  ⭐ 14 · 💀) - SPINNER (Structure Prediction of Inorganic crystals using Neural Network potentials with Evolutionary and Random.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>C++</code> <code>structure-prediction</code>
</details>
<br>

## Mathematical tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that implement mathematical objects used in atomistic machine learning._

<details><summary><b><a href="https://github.com/NVIDIA/cuEquivariance">cuEquivariance</a></b> (🥇19 ·  ⭐ 370) - cuEquivariance is a math library that is a collective of low-level primitives and tensor ops to accelerate widely-used.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/NVIDIA/cuEquivariance) (👨‍💻 13 · 🔀 27):

	```
	git clone https://github.com/NVIDIA/cuEquivariance
	```
- [PyPi](https://pypi.org/project/cuequivariance) (📥 180K / month · 📦 12 · ⏱️ 22.04.2026):
	```
	pip install cuequivariance
	```
- [Conda](https://anaconda.org/conda-forge/cuequivariance) (📥 26K · ⏱️ 23.04.2026):
	```
	conda install -c conda-forge cuequivariance
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/kfac-jax">KFAC-JAX</a></b> (🥇18 ·  ⭐ 310) - Second Order Optimization and Curvature Estimation with K-FAC in JAX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-deepmind/kfac-jax) (👨‍💻 21 · 🔀 29 · 📦 16):

	```
	git clone https://github.com/google-deepmind/kfac-jax
	```
- [PyPi](https://pypi.org/project/kfac-jax) (📥 3.5K / month · 📦 2 · ⏱️ 25.02.2026):
	```
	pip install kfac-jax
	```
</details>
<details><summary><b><a href="https://github.com/PASSIONLab/OpenEquivariance">OpenEquivariance</a></b> (🥇18 ·  ⭐ 150) - OpenEquivariance: a fast, open-source GPU JIT kernel generator for the Clebsch-Gordon Tensor Product. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/PASSIONLab/OpenEquivariance) (👨‍💻 6 · 🔀 10 · 📦 8):

	```
	git clone https://github.com/PASSIONLab/OpenEquivariance
	```
- [PyPi](https://pypi.org/project/openequivariance) (📥 26K / month · 📦 4 · ⏱️ 14.06.2026):
	```
	pip install openequivariance
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/sphericart">SpheriCart</a></b> (🥈16 ·  ⭐ 100) - Multi-language library for the calculation of spherical harmonics in Cartesian coordinates. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lab-cosmo/sphericart) (👨‍💻 15 · 🔀 17 · 📦 11):

	```
	git clone https://github.com/lab-cosmo/sphericart
	```
- [PyPi](https://pypi.org/project/sphericart) (📥 8K / month · 📦 2 · ⏱️ 09.07.2026):
	```
	pip install sphericart
	```
</details>
<details><summary><b><a href="https://github.com/ziatdinovmax/gpax">gpax</a></b> (🥈14 ·  ⭐ 220 · 💤) - Gaussian Processes for Experimental Sciences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>probabilistic</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a></summary>

- [GitHub](https://github.com/ziatdinovmax/gpax) (👨‍💻 6 · 🔀 29 · 📦 6):

	```
	git clone https://github.com/ziatdinovmax/gpax
	```
- [PyPi](https://pypi.org/project/gpax) (📥 390 / month · ⏱️ 04.07.2025):
	```
	pip install gpax
	```
</details>
<details><summary><b><a href="https://github.com/risi-kondor/GElib">GElib</a></b> (🥉7 ·  ⭐ 25 · 💤) - C++/CUDA library for SO(3) equivariant operations. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/risi-kondor/GElib) (👨‍💻 6 · 🔀 3):

	```
	git clone https://github.com/risi-kondor/GElib
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/Polynomials4ML.jl">Polynomials4ML.jl</a></b> (🥉6 ·  ⭐ 13 · 💤) - Polynomials for ML: fast evaluation, batching, differentiation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code></summary>

- [GitHub](https://github.com/ACEsuit/Polynomials4ML.jl) (👨‍💻 12 · 🔀 6):

	```
	git clone https://github.com/ACEsuit/Polynomials4ML.jl
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/lie-nn/lie-nn">lie-nn</a></b> (🥉6 ·  ⭐ 38 · 💀) - Tools for building equivariant polynomials on reductive Lie groups. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://github.com/aced-differentiate/EquivariantOperators.jl">EquivariantOperators.jl</a></b> (🥉5 ·  ⭐ 18 · 💀) - This package is deprecated. Functionalities are migrating to Porcupine.jl. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>Julia</code>
- <b><a href="https://github.com/lab-cosmo/toolbox">COSMO Toolbox</a></b> (🥉4 ·  ⭐ 6 · 💀) - Assorted libraries and utilities for atomistic simulation analysis. <code>Unlicensed</code> <code>C++</code>
- <b><a href="https://github.com/lab-cosmo/torch_spex">torch_spex</a></b> (🥉3 ·  ⭐ 2 · 💀) - Spherical expansions in PyTorch. <code>Unlicensed</code>
- <b><a href="https://github.com/lab-cosmo/wigner_kernels">Wigner Kernels</a></b> (🥉2 ·  ⭐ 1 · 💀) - Collection of programs to benchmark Wigner kernels. <code>Unlicensed</code> <code>benchmarking</code>
</details>
<br>

## Molecular Dynamics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that simplify the integration of molecular dynamics and atomistic machine learning._

<details><summary><b><a href="https://github.com/jax-md/jax-md">JAX-MD</a></b> (🥇23 ·  ⭐ 1.4K) - Differentiable, Hardware Accelerated, Molecular Dynamics. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jax-md/jax-md) (👨‍💻 51 · 🔀 240 · 📦 94):

	```
	git clone https://github.com/jax-md/jax-md
	```
- [PyPi](https://pypi.org/project/jax-md) (📥 31K / month · 📦 25 · ⏱️ 10.06.2026):
	```
	pip install jax-md
	```
</details>
<details><summary><b><a href="https://github.com/luigibonati/mlcolvar">mlcolvar</a></b> (🥇15 ·  ⭐ 130) - A unified framework for machine learning collective variables for enhanced sampling simulations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>sampling</code></summary>

- [GitHub](https://github.com/luigibonati/mlcolvar) (👨‍💻 15 · 🔀 35 · 📦 13):

	```
	git clone https://github.com/luigibonati/mlcolvar
	```
- [PyPi](https://pypi.org/project/mlcolvar) (📥 840 / month · 📦 4 · ⏱️ 03.02.2026):
	```
	pip install mlcolvar
	```
</details>
<details><summary><b><a href="https://github.com/openmm/openmm-torch">openmm-torch</a></b> (🥈14 ·  ⭐ 220) - OpenMM plugin to define forces with neural networks. <code><a href="https://github.com/openmm/openmm-torch#license">Custom</a></code> <code>ML-IAP</code> <code>C++</code></summary>

- [GitHub](https://github.com/openmm/openmm-torch) (👨‍💻 9 · 🔀 28):

	```
	git clone https://github.com/openmm/openmm-torch
	```
- [Conda](https://anaconda.org/conda-forge/openmm-torch) (📥 1.3M · ⏱️ 17.06.2026):
	```
	conda install -c conda-forge openmm-torch
	```
</details>
<details><summary><b><a href="https://github.com/openmm/openmm-ml">OpenMM-ML</a></b> (🥈14 ·  ⭐ 170) - High level API for using machine learning models in OpenMM simulations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code></summary>

- [GitHub](https://github.com/openmm/openmm-ml) (👨‍💻 11 · 🔀 47 · 📦 2):

	```
	git clone https://github.com/openmm/openmm-ml
	```
- [Conda](https://anaconda.org/conda-forge/openmm-ml) (📥 55K · ⏱️ 08.06.2026):
	```
	conda install -c conda-forge openmm-ml
	```
</details>
<details><summary><b><a href="https://pypi.org/project/torch-sim-atomistic/">TorchSim</a></b> (🥈13 · 📉) - A pytorch toolkit for calculating material properties using MLIPs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/High-throughput_computing"><code>HTC</code></a> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <code>ML-IAP</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a></summary>

- [GitHub]() (👨‍💻 37):

	```
	git clone https://github.com/Radical-AI/torch-sim
	```
- [PyPi](https://pypi.org/project/torch-sim-atomistic) (📥 23K / month · 📦 19 · ⏱️ 24.04.2026):
	```
	pip install torch-sim-atomistic
	```
</details>
<details><summary><b><a href="https://github.com/FitSNAP/FitSNAP">FitSNAP</a></b> (🥈12 ·  ⭐ 180 · 💤) - Software for generating machine-learning interatomic potentials for LAMMPS. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code></summary>

- [GitHub](https://github.com/FitSNAP/FitSNAP) (👨‍💻 24 · 🔀 65):

	```
	git clone https://github.com/FitSNAP/FitSNAP
	```
- [Conda](https://anaconda.org/conda-forge/fitsnap3) (📥 18K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge fitsnap3
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/DMFF">DMFF</a></b> (🥉8 ·  ⭐ 180 · 💤) - DMFF (Differentiable Molecular Force Field) is a Jax-based python package that provides a full differentiable.. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>C++</code></summary>

- [GitHub](https://github.com/deepmodeling/DMFF) (👨‍💻 17 · 🔀 47):

	```
	git clone https://github.com/deepmodeling/DMFF
	```
</details>
<details><summary><b><a href="https://github.com/ICAMS/lammps-user-pace">PACE</a></b> (🥉6 ·  ⭐ 31 · 💤) - The LAMMPS ML-IAP `pair_style pace`, aka Atomic Cluster Expansion (ACE), aka ML-PACE,.. <code><a href="https://github.com/ICAMS/lammps-user-pace/blob/main/LICENSE">Custom</a></code></summary>

- [GitHub](https://github.com/ICAMS/lammps-user-pace) (👨‍💻 8 · 🔀 15):

	```
	git clone https://github.com/ICAMS/lammps-user-pace
	```
</details>
<details><summary><b><a href="https://github.com/chiang-yuan/muse">MUSE</a></b> (🥉5 ·  ⭐ 7 · 🐣) - A python package for fast building amorphous solids and liquid mixtures from @materialsproject computed structures and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://www.google.com/search?q=defects+and+disorder+in+materials"><code>Defects & Disorder</code></a></summary>

- [GitHub](https://github.com/chiang-yuan/muse) (👨‍💻 2 · 📦 1):

	```
	git clone https://github.com/chiang-yuan/muse
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/brucefan1983/GPUMD">GPUMD</a></b> (🥉9 ·  ⭐ 450 · 💀) - GPUMD is a highly efficient general-purpose molecular dynamic (MD) package and enables machine-learned potentials.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>ML-IAP</code> <code>C++</code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a>
- <b><a href="https://github.com/molmod/psiflow">Psiflow</a></b> (🥉7 ·  ⭐ 68 · 💀) - Interatomic potential development library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <code>sampling</code>
- <b><a href="https://github.com/mir-group/pair_nequip">pair_nequip</a></b> (🥉7 ·  ⭐ 44 · 💀) - LAMMPS pair style for NequIP. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a>
- <b><a href="https://gitlab.com/ivannovikov/interface-lammps-mlip-3">interface-lammps-mlip-3</a></b> (🥉3 ·  ⭐ 5 · 💀) - An interface between LAMMPS and MLIP (version 3). <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code>
- <b><a href="https://github.com/initqp/somd">SOMD</a></b> (🥉3 · 💀) - SOMD is an ab-initio molecular dynamics (AIMD) package designed for the SIESTA DFT code. <code><a href="http://bit.ly/3pwmjO5">AGPL-3.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a>
</details>
<br>

## Probabilistic ML

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on probabilistic, Bayesian, Gaussian process and adversarial methods for atomistic ML, for optimization, uncertainty quantification (UQ), etc._

<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/janosh/thermo">thermo</a></b> (🥇5 ·  ⭐ 10 · 💀) - Data-driven risk-conscious thermoelectric materials discovery. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Experimental_physics"><code>experimental-data</code></a> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
</details>
<br>

## Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on reinforcement learning for atomistic ML._

<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/isayev/ReLeaSE">ReLeaSE</a></b> (🥇9 ·  ⭐ 210 · 💀) - Deep Reinforcement Learning for de-novo Drug Design. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>
- <b><a href="https://github.com/ulissigroup/catgym">CatGym</a></b> (🥉4 ·  ⭐ 12 · 💀) - Surface segregation using Deep Reinforcement Learning. <code><a href="https://tldrlegal.com/search?q=GPL">GPL</a></code>
</details>
<br>

## Representation Engineering

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that offer implementations of representations aka descriptors, fingerprints of atomistic systems, and models built with them, aka feature engineering._

<details><summary><b><a href="https://github.com/SINGROUP/dscribe">DScribe</a></b> (🥇19 ·  ⭐ 450 · 💤) - DScribe is a python package for creating machine learning descriptors for atomistic systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SINGROUP/dscribe) (👨‍💻 18 · 🔀 96 · 📦 300):

	```
	git clone https://github.com/SINGROUP/dscribe
	```
- [PyPi](https://pypi.org/project/dscribe) (📥 52K / month · 📦 63 · ⏱️ 27.09.2025):
	```
	pip install dscribe
	```
- [Conda](https://anaconda.org/conda-forge/dscribe) (📥 310K · ⏱️ 10.12.2025):
	```
	conda install -c conda-forge dscribe
	```
</details>
<details><summary><b><a href="https://github.com/cdk/cdk">cdk</a></b> (🥇16 ·  ⭐ 580) - The Chemistry Development Kit. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <code>Java</code></summary>

- [GitHub](https://github.com/cdk/cdk) (👨‍💻 170 · 🔀 180):

	```
	git clone https://github.com/cdk/cdk
	```
- [Maven](https://search.maven.org/artifact/org.openscience.cdk/cdk-bundle) (📦 18 · ⏱️ 03.03.2026):
	```
	<dependency>
		<groupId>org.openscience.cdk</groupId>
		<artifactId>cdk-bundle</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/PhasesResearchLab/pySIPFENN">pySIPFENN</a></b> (🥈12 ·  ⭐ 24) - Python python toolset for Structure-Informed Property and Feature Engineering with Neural Networks. It offers unique.. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Crystallographic_defect"><code>material-defect</code></a> <a href="https://www.google.com/search?q=defects+and+disorder+in+materials"><code>Defects & Disorder</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Transfer_learning"><code>transfer-learning</code></a></summary>

- [GitHub](https://github.com/PhasesResearchLab/pySIPFENN) (👨‍💻 5 · 🔀 6 · 📦 7):

	```
	git clone https://github.com/PhasesResearchLab/pySIPFENN
	```
- [PyPi](https://pypi.org/project/pysipfenn) (📥 380 / month · ⏱️ 18.07.2026):
	```
	pip install pysipfenn
	```
- [Conda](https://anaconda.org/conda-forge/pysipfenn) (📥 25K · ⏱️ 19.07.2026):
	```
	conda install -c conda-forge pysipfenn
	```
</details>
<details><summary><b><a href="https://pypi.org/project/ElementEmbeddings/">ElementEmbeddings</a></b> (🥈12) - Element Embeddings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Explainable_artificial_intelligence"><code>XAI</code></a> <a href="https://en.wikipedia.org/wiki/Unsupervised_learning"><code>USL</code></a> <a href="https://en.wikipedia.org/wiki/Visualization"><code>viz</code></a></summary>

- [GitHub]() (👨‍💻 9 · 📦 6):

	```
	git clone https://github.com/WMD-group/ElementEmbeddings
	```
- [PyPi](https://pypi.org/project/ElementEmbeddings) (📥 1.3K / month · 📦 2 · ⏱️ 14.07.2026):
	```
	pip install ElementEmbeddings
	```
- [Conda](https://anaconda.org/conda-forge/elementembeddings) (📥 4.4K · ⏱️ 15.07.2026):
	```
	conda install -c conda-forge elementembeddings
	```
</details>
<details><summary><b><a href="https://github.com/metatensor/featomic">Featomic</a></b> (🥈11 ·  ⭐ 82) - Computing representations for atomistic machine learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>Rust</code> <code>C++</code></summary>

- [GitHub](https://github.com/metatensor/featomic) (👨‍💻 21 · 🔀 18):

	```
	git clone https://github.com/metatensor/featomic
	```
</details>
<details><summary><b><a href="https://github.com/drcassar/glasspy">GlassPy</a></b> (🥈11 ·  ⭐ 37) - Python module for scientists working with glass materials. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code></summary>

- [GitHub](https://github.com/drcassar/glasspy) (👨‍💻 2 · 🔀 8 · 📦 7):

	```
	git clone https://github.com/drcassar/glasspy
	```
- [PyPi](https://pypi.org/project/glasspy) (📥 490 / month · ⏱️ 13.03.2026):
	```
	pip install glasspy
	```
</details>
<details><summary><b><a href="https://github.com/libAtoms/soap_turbo">soap_turbo</a></b> (🥉5 ·  ⭐ 7 · 💤) - soap_turbo comprises a series of libraries to be used in combination with QUIP/GAP and TurboGAP. <code><a href="https://github.com/libAtoms/soap_turbo/blob/master/LICENSE.md">Custom</a></code> <code>Fortran</code></summary>

- [GitHub](https://github.com/libAtoms/soap_turbo) (👨‍💻 4 · 🔀 8):

	```
	git clone https://github.com/libAtoms/soap_turbo
	```
</details>
<details><summary>Show 19 hidden projects...</summary>

- <b><a href="https://github.com/hachmannlab/chemml">ChemML</a></b> (🥇15 ·  ⭐ 160 · 💀) - ChemML is a machine learning and informatics program suite for the chemical and materials sciences. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <a href="https://en.wikipedia.org/wiki/Cheminformatics"><code>cheminformatics</code></a> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <code>workflows</code>
- <b><a href="https://github.com/SUNCAT-Center/CatLearn">CatLearn</a></b> (🥈13 ·  ⭐ 92 · 💀) -  <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Surface_science"><code>surface-science</code></a>
- <b><a href="https://github.com/ppdebreuck/modnet">MODNet</a></b> (🥈10 ·  ⭐ 90 · 💀) - MODNet: a framework for machine learning materials properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <code>small-data</code> <a href="https://en.wikipedia.org/wiki/Transfer_learning"><code>transfer-learning</code></a>
- <b><a href="https://github.com/sirmarcel/cmlkit">cmlkit</a></b> (🥈10 ·  ⭐ 33 · 💀) - tools for machine learning in condensed matter physics and quantum chemistry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/WMD-group/PDynA">PDynA</a></b> (🥈9 ·  ⭐ 28 · 💀) - Python package to analyse the structural dynamics of perovskites. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a>
- <b><a href="https://github.com/capoe/benchml">BenchML</a></b> (🥈9 ·  ⭐ 9 · 💀) - ML benchmarking and pipeling framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>benchmarking</code>
- <b><a href="https://github.com/lantunes/skipatom">SkipAtom</a></b> (🥈9 ·  ⭐ 7 · 💀) - Distributed representations of atoms, inspired by the Skip-gram model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kaaiian/CBFV">CBFV</a></b> (🥈9 ·  ⭐ 3 · 💀) - Tool to quickly create a composition-based feature vector. <code>Unlicensed</code>
- <b><a href="https://github.com/rouyang2017/SISSO">SISSO</a></b> (🥉8 ·  ⭐ 120 · 💀) - A data-driven method combining symbolic regression and compressed sensing toward accurate & interpretable models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>Fortran</code>
- <b><a href="https://github.com/lab-cosmo/librascal">Librascal</a></b> (🥉8 ·  ⭐ 77 · 💀) - A scalable and versatile library to generate representations for atomic-scale learning. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">LGPL-2.1</a></code>
- <b><a href="https://gitlab.com/sissopp_developers/sissopp">SISSO++</a></b> (🥉7 ·  ⭐ 6 · 💀) - C++ Implementation of SISSO with python bindings. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>C++</code>
- <b><a href="https://bitbucket.org/andrewpeterson/amp/">AMP</a></b> (🥉7 · 💀) - Amp is an open-source package designed to easily bring machine-learning to atomistic calculations. <code>Unlicensed</code>
- <b><a href="https://github.com/NU-CUCIS/ElemNet">ElemNet</a></b> (🥉6 ·  ⭐ 98 · 💀) - Deep Learning the Chemistry of Materials From Only Elemental Composition for Enhancing Materials Property Prediction. <code>Unlicensed</code> <code>single-paper</code>
- <b><a href="https://github.com/muhrin/milad">milad</a></b> (🥉5 ·  ⭐ 29 · 💀) - Moment Invariants Local Atomic Descriptor. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a>
- <b><a href="https://github.com/lab-cosmo/nice">NICE</a></b> (🥉5 ·  ⭐ 12 · 💀) - NICE (N-body Iteratively Contracted Equivariants) is a set of tools designed for the calculation of invariant and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dilkins/TENSOAP">SA-GPR</a></b> (🥉5 ·  ⭐ 12 · 💀) - Public repository for symmetry-adapted Gaussian Process Regression (SA-GPR). <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>C-lang</code>
- <b><a href="https://github.com/capoe/soapxx">SOAPxx</a></b> (🥉5 ·  ⭐ 7 · 💀) - A SOAP implementation. <code><a href="http://bit.ly/2KucAZR">GPL-2.0</a></code> <code>C++</code>
- <b><a href="https://github.com/ceriottm/lode">pyLODE</a></b> (🥉5 ·  ⭐ 3 · 💀) - Pythonic implementation of LOng Distance Equivariants. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a>
- <b><a href="https://github.com/mm-tud/automl-materials">automl-materials</a></b> (🥉3 ·  ⭐ 2 · 💀) - AutoML for Regression Tasks on Small Tabular Data in Materials Design. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Automated_machine_learning"><code>autoML</code></a> <code>benchmarking</code> <code>single-paper</code>
</details>
<br>

## Representation Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General models that learn a representations aka embeddings of atomistic systems, such as message-passing neural networks (MPNN)._

<details><summary><b><a href="https://github.com/dmlc/dgl">Deep Graph Library (DGL)</a></b> (🥇28 ·  ⭐ 14K · 💤) - Python package built to ease deep learning on graph, on top of existing DL frameworks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 300 · 🔀 3K · 📦 4.3K):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 150K / month · 📦 150 · ⏱️ 13.05.2024):
	```
	pip install dgl
	```
- [Conda](https://anaconda.org/dglteam/dgl) (📥 490K · ⏱️ 25.03.2025):
	```
	conda install -c dglteam dgl
	```
</details>
<details><summary><b><a href="https://github.com/e3nn/e3nn">e3nn</a></b> (🥇25 ·  ⭐ 1.2K) - A modular framework for neural networks with Euclidean symmetry. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/e3nn/e3nn) (👨‍💻 38 · 🔀 180 · 📦 670):

	```
	git clone https://github.com/e3nn/e3nn
	```
- [PyPi](https://pypi.org/project/e3nn) (📥 490K / month · 📦 74 · ⏱️ 13.02.2026):
	```
	pip install e3nn
	```
- [Conda](https://anaconda.org/conda-forge/e3nn) (📥 77K · ⏱️ 29.04.2026):
	```
	conda install -c conda-forge e3nn
	```
</details>
<details><summary><b><a href="https://github.com/pyg-team/pytorch_geometric/tree/master/torch_geometric/nn/models">PyG Models</a></b> (🥇22 ·  ⭐ 24K · 📉) - Representation learning models implemented in PyTorch Geometric. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>general-ml</code></summary>

- [GitHub](https://github.com/pyg-team/pytorch_geometric) (👨‍💻 570 · 🔀 4K · 📦 11K):

	```
	git clone https://github.com/pyg-team/pytorch_geometric
	```
</details>
<details><summary><b><a href="https://github.com/materialsvirtuallab/matgl">MatGL (Materials Graph Library)</a></b> (🥇21 ·  ⭐ 420) - Graph deep learning library for materials. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>ML-IAP</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Multifidelity_simulation"><code>multifidelity</code></a></summary>

- [GitHub](https://github.com/materialsvirtuallab/matgl) (👨‍💻 27 · 🔀 87 · 📦 95):

	```
	git clone https://github.com/materialsvirtuallab/matgl
	```
- [PyPi](https://pypi.org/project/matgl) (📥 21K / month · 📦 35 · ⏱️ 02.07.2026):
	```
	pip install matgl
	```
- [Docker Hub](https://hub.docker.com/r/materialsvirtuallab/matgl) (📥 430 · ⭐ 1 · ⏱️ 26.04.2026):
	```
	docker pull materialsvirtuallab/matgl
	```
</details>
<details><summary><b><a href="https://github.com/atomistic-machine-learning/schnetpack">SchNetPack</a></b> (🥇19 ·  ⭐ 890 · 💤) - SchNetPack - Deep Neural Networks for Atomistic Systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/atomistic-machine-learning/schnetpack) (👨‍💻 43 · 🔀 250 · 📦 110):

	```
	git clone https://github.com/atomistic-machine-learning/schnetpack
	```
- [PyPi](https://pypi.org/project/schnetpack) (📥 4.1K / month · 📦 4 · ⏱️ 19.12.2025):
	```
	pip install schnetpack
	```
</details>
<details><summary><b><a href="https://github.com/e3nn/e3nn-jax">e3nn-jax</a></b> (🥇19 ·  ⭐ 230) - jax library for E3 Equivariant Neural Networks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/e3nn/e3nn-jax) (👨‍💻 8 · 🔀 19 · 📦 95):

	```
	git clone https://github.com/e3nn/e3nn-jax
	```
- [PyPi](https://pypi.org/project/e3nn-jax) (📥 62K / month · 📦 35 · ⏱️ 01.04.2026):
	```
	pip install e3nn-jax
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/alignn">ALIGNN</a></b> (🥈17 ·  ⭐ 310) - Atomistic Line Graph Neural Network https://scholar.google.com/citations?user=9Q-tNnwAAAAJ.. <code><a href="https://github.com/usnistgov/alignn/blob/main/LICENSE.rst">Custom</a></code></summary>

- [GitHub](https://github.com/usnistgov/alignn) (👨‍💻 8 · 🔀 110):

	```
	git clone https://github.com/usnistgov/alignn
	```
- [PyPi](https://pypi.org/project/alignn) (📥 6.1K / month · 📦 14 · ⏱️ 24.05.2026):
	```
	pip install alignn
	```
</details>
<details><summary><b><a href="https://github.com/lanl/hippynn">hippynn</a></b> (🥈9 ·  ⭐ 85 · 💤) - python library for atomistic machine learning. <code><a href="https://github.com/lanl/hippynn/blob/main/LICENSE.txt">Custom</a></code> <code>workflows</code></summary>

- [GitHub](https://github.com/lanl/hippynn) (👨‍💻 21 · 🔀 30 · 📦 4):

	```
	git clone https://github.com/lanl/hippynn
	```
</details>
<details><summary><b><a href="https://github.com/learningmatter-mit/uvvisml">UVVisML</a></b> (🥉6 ·  ⭐ 33 · 💤) - Predict optical properties of molecules with machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Optical_properties"><code>optical-properties</code></a> <code>single-paper</code> <code>probabilistic</code></summary>

- [GitHub](https://github.com/learningmatter-mit/uvvisml) (👨‍💻 1 · 🔀 9):

	```
	git clone https://github.com/learningmatter-mit/uvvisml
	```
</details>
<details><summary><b><a href="https://github.com/omron-sinicx/crystalframer">Crystalframer</a></b> (🥉5 ·  ⭐ 15 · 💤) - The official code respository for Rethinking the role of frames for SE(3)-invariant crystal structure modeling (ICLR.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <code>single-paper</code></summary>

- [GitHub](https://github.com/omron-sinicx/crystalframer) (👨‍💻 3 · 🔀 3):

	```
	git clone https://github.com/omron-sinicx/crystalframer
	```
</details>
<details><summary>Show 44 hidden projects...</summary>

- <b><a href="https://github.com/awslabs/dgl-lifesci">dgl-lifesci</a></b> (🥇21 ·  ⭐ 790 · 💀) - Python package for graph neural networks in chemistry and biology. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/divelab/DIG">DIG: Dive into Graphs</a></b> (🥈16 ·  ⭐ 1.8K · 💀) - A library for graph deep learning research. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code>
- <b><a href="https://github.com/QUVA-Lab/escnn">escnn</a></b> (🥈14 ·  ⭐ 320 · 💀) - Equivariant Steerable CNNs Library for Pytorch https://quva-lab.github.io/escnn/. <code><a href="https://github.com/QUVA-Lab/escnn/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/aimat-lab/gcnn_keras">kgcnn</a></b> (🥈14 ·  ⭐ 120 · 💀) - Graph convolutions in Keras with TensorFlow, PyTorch or Jax. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/NVIDIA/DeepLearningExamples#graph-neural-networks">NVIDIA Deep Learning Examples for Tensor Cores</a></b> (🥈13 ·  ⭐ 15K · 💀) - State-of-the-Art Deep Learning scripts organized by models - easy to train and deploy with reproducible accuracy and.. <code><a href="https://github.com/NVIDIA/DeepLearningExamples/blob/master/DGLPyTorch/DrugDiscovery/SE3Transformer/LICENSE">Custom</a></code> <code>educational</code> <a href="https://en.wikipedia.org/wiki/Drug_design#Computer-aided_drug_design"><code>drug-discovery</code></a>
- <b><a href="https://github.com/sparks-baird/CrabNet">Compositionally-Restricted Attention-Based Network (CrabNet)</a></b> (🥈12 ·  ⭐ 10 · 💀) - Predict materials properties using only the composition information!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/graphdeeplearning/benchmarking-gnns">benchmarking-gnns</a></b> (🥈11 ·  ⭐ 2.6K · 💀) - Repository for benchmarking graph neural networks (JMLR 2023). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code> <code>benchmarking</code>
- <b><a href="https://github.com/microsoft/Graphormer">Graphormer</a></b> (🥈11 ·  ⭐ 2.3K · 💀) - Graphormer is a general-purpose deep learning backbone for molecular modeling. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <code>pretrained</code>
- <b><a href="https://github.com/deepmodeling/Uni-Mol">Uni-Mol</a></b> (🥈10 ·  ⭐ 1K · 💀) - Official Repository for the Uni-Mol Series Methods. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code>
- <b><a href="https://github.com/sparks-baird/xtal2png">xtal2png</a></b> (🥈10 ·  ⭐ 39 · 💀) - Encode/decode a crystal structure to/from a grayscale PNG image for direct use with image-based machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Computer_vision"><code>computer-vision</code></a>
- <b><a href="https://github.com/idocx/Atom2Vec">Atom2Vec</a></b> (🥈10 ·  ⭐ 27 · 💀) - Atom2Vec: a simple way to describe atoms for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/snap-stanford/pretrain-gnns">pretrained-gnns</a></b> (🥈9 ·  ⭐ 1.1K · 💀) - Strategies for Pre-training Graph Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code>
- <b><a href="https://github.com/gasteigerjo/gdc">GDC</a></b> (🥈9 ·  ⭐ 260 · 💀) - Graph Diffusion Convolution, as proposed in Diffusion Improves Graph Learning (NeurIPS 2019). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a>
- <b><a href="https://github.com/txie-93/cgcnn">Crystal Graph Convolutional Neural Networks (CGCNN)</a></b> (🥈9 ·  ⭐ 190 · 💀) - Crystal graph convolutional neural networks for predicting material properties. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/FabianFuchsML/se3-transformer-public">SE(3)-Transformers</a></b> (🥈8 ·  ⭐ 490 · 💀) - code for the SE3 Transformers paper: https://arxiv.org/abs/2006.10503. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>
- <b><a href="https://github.com/atomicarchitects/equiformer">Equiformer</a></b> (🥈8 ·  ⭐ 260 · 💀) - [ICLR 2023 Spotlight] Equiformer: Equivariant Graph Attention Transformer for 3D Atomistic Graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>
- <b><a href="https://github.com/masashitsubaki/molecularGNN_smiles">molecularGNN_smiles</a></b> (🥈8 ·  ⭐ 170 · 💀) - The code of a graph neural network (GNN) for molecules, which is based on learning representations of r-radius.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/tensorfieldnetworks/tensorfieldnetworks">tensorfieldnetworks</a></b> (🥈8 ·  ⭐ 150 · 💀) - Rotation- and translation-equivariant neural networks for 3D point clouds. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/llnl/graphite">graphite</a></b> (🥈8 ·  ⭐ 37 · 💀) - A repository for implementing graph network models based on atomic structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ORNL/HydraGNN">HydraGNN</a></b> (🥈8 ·  ⭐ 29 · 💀) - Distributed PyTorch implementation of multi-headed graph convolutional neural networks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://pypi.org/project/faenet/">FAENet</a></b> (🥈8 · 💀) - Frame Averaging Equivariant GNN for materials modeling. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/chao1224/Geom3D">Geom3D</a></b> (🥉7 ·  ⭐ 110 · 💀) - Geom3D: Geometric Modeling on 3D Structures, NeurIPS 2023. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code> <code>single-paper</code>
- <b><a href="https://github.com/atomistic-machine-learning/dtnn">DTNN</a></b> (🥉7 ·  ⭐ 76 · 💀) - Deep Tensor Neural Network. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/usccolumbia/deeperGATGNN">DeeperGATGNN</a></b> (🥉7 ·  ⭐ 62 · 💀) - Scalable graph neural networks for materials property prediction. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/NREL/nfp">Neural fingerprint (nfp)</a></b> (🥉7 ·  ⭐ 60 · 💀) - Keras layers for end-to-end learning with rdkit and pymatgen. <code><a href="https://github.com/NREL/nfp/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/superlouis/GATGNN">GATGNN: Global Attention Graph Neural Network</a></b> (🥉7 ·  ⭐ 55 · 💀) - Pytorch Repository for our work: Graph convolutional neural networks with global attention for improved materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Open-Catalyst-Project/AdsorbML">AdsorbML</a></b> (🥉7 ·  ⭐ 42 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Surface_science"><code>surface-science</code></a> <code>single-paper</code>
- <b><a href="https://github.com/pfnet-research/charge_transfer_nnp">charge_transfer_nnp</a></b> (🥉7 ·  ⭐ 35 · 💀) - Graph neural network potential with charge transfer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a>
- <b><a href="https://github.com/IntelLabs/matsciml">matsciml</a></b> (🥉6 ·  ⭐ 130 · 💀) - Open MatSci ML Toolkit is a framework for prototyping and scaling out deep learning models for materials discovery.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>workflows</code> <code>benchmarking</code>
- <b><a href="https://github.com/ACEsuit/mace-layer">MACE-Layer</a></b> (🥉6 ·  ⭐ 45 · 💀) - Higher order equivariant graph neural networks for 3D point clouds. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/learningmatter-mit/GLAMOUR">GLAMOUR</a></b> (🥉6 ·  ⭐ 23 · 💀) - Graph Learning over Macromolecule Representations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>single-paper</code>
- <b><a href="https://github.com/Hongyu-yu/T-e3nn">T-e3nn</a></b> (🥉6 ·  ⭐ 11 · 💀) - Time-reversal Euclidean neural networks based on e3nn. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>magnetism</code>
- <b><a href="https://github.com/risilab/cormorant">Cormorant</a></b> (🥉5 ·  ⭐ 60 · 💀) - Codebase for Cormorant Neural Networks. <code><a href="https://github.com/risilab/cormorant/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/risilab/Autobahn">Autobahn</a></b> (🥉5 ·  ⭐ 30 · 💀) - Repository for Autobahn: Automorphism Based Graph Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/omron-sinicx/crystalformer">Crystalformer</a></b> (🥉5 ·  ⭐ 27 · 💀) - The official code respository for Crystalformer: Infinitely Connected Attention for Periodic Structure Encoding (ICLR.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a> <code>single-paper</code>
- <b><a href="https://github.com/atomistic-machine-learning/field_schnet">FieldSchNet</a></b> (🥉5 ·  ⭐ 16 · 💀) - Deep neural network for molecules in external fields. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sirmarcel/gkx">gkx: Green-Kubo Method in JAX</a></b> (🥉5 ·  ⭐ 8 · 💀) - Green-Kubo + JAX + MLPs = Anharmonic Thermal Conductivities Done Fast. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://github.com/gasteigerjo/gtn">Graph Transport Network</a></b> (🥉4 ·  ⭐ 16 · 💀) - Graph transport network (GTN), as proposed in Scalable Optimal Transport in High Dimensions for Graph Distances,.. <code><a href="https://github.com/gasteigerjo/gtn/blob/main/LICENSE.md">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
- <b><a href="https://github.com/aimat-lab/ML4pXRDs">ML4pXRDs</a></b> (🥉4 ·  ⭐ 3 · 💀) - Contains code to train neural networks based on simulated powder XRDs from synthetic crystals. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/X-ray_crystallography"><code>XRD</code></a> <code>single-paper</code>
- <b><a href="https://github.com/HSE-LAMBDA/ai4material_design">ai4material_design</a></b> (🥉4 ·  ⭐ 2 · 💀) - Code for Kazeev, N., Al-Maeeni, A.R., Romanov, I. et al. Sparse representation for machine learning the properties of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Crystallographic_defect"><code>material-defect</code></a>
- <b><a href="https://github.com/M3RG-IITD/MDBENCHGNN">EGraFFBench</a></b> (🥉3 ·  ⭐ 12 · 💀) -  <code>Unlicensed</code> <code>single-paper</code> <code>benchmarking</code> <code>ML-IAP</code>
- <b><a href="https://github.com/learningmatter-mit/atom_by_atom">atom_by_atom</a></b> (🥉3 ·  ⭐ 10 · 💀) - Atom-by-atom design of metal oxide catalysts for the oxygen evolution reaction with Machine Learning. <code>Unlicensed</code> <a href="https://en.wikipedia.org/wiki/Surface_science"><code>surface-science</code></a> <code>single-paper</code>
- <b><a href="https://github.com/risilab/SphericalNet">SphericalNet</a></b> (🥉3 ·  ⭐ 3 · 💀) - Implementation of Clebsch-Gordan Networks (CGnet: https://arxiv.org/pdf/1806.09231.pdf) by GElib & cnine libraries in.. <code>Unlicensed</code>
- <b><a href="https://zenodo.org/record/7967079">Point Edge Transformer</a></b> (🥉2) - Smooth, exact rotational symmetrization for deep learning on point clouds. <code><a href="https://tldrlegal.com/search?q=CC-BY-4.0">CC-BY-4.0</a></code>
</details>
<br>

## Universal Potentials

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Machine-learned interatomic potentials (ML-IAP) that have been trained on large, chemically and structural diverse datasets. For materials, this means e.g. datasets that include a majority of the periodic table._

🔗&nbsp;<b><a href="https://doi.org/10.24433/CO.0749085.v1">TeaNet</a></b>  - Universal neural network interatomic potential inspired by iterative electronic relaxations.. <code>ML-IAP</code>

🔗&nbsp;<b><a href="https://www.nature.com/articles/s41467-022-30687-9#code-availability">PreFerred Potential (PFP)</a></b>  - Universal neural network potential for material discovery https://doi.org/10.1038/s41467-022-30687-9. <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Proprietary_software"><code>proprietary</code></a>

<details><summary><b><a href="https://github.com/deepmodeling/deepmd-kit">DPA-2</a></b> (🥇23 ·  ⭐ 2K) - A large atomic model as a multi-task learner https://arxiv.org/abs/2312.15492. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>ML-IAP</code> <code>pretrained</code> <code>workflows</code> <code>datasets</code></summary>

- [GitHub](https://github.com/deepmodeling/deepmd-kit) (👨‍💻 88 · 🔀 620 · 📦 57):

	```
	git clone https://github.com/deepmodeling/deepmd-kit
	```
- [PyPi](https://pypi.org/project/deepmd-kit) (📥 19K / month · 📦 21 · ⏱️ 06.06.2026):
	```
	pip install deepmd-kit
	```
- [Conda](https://anaconda.org/conda-forge/deepmd-kit) (📥 3M · ⏱️ 07.06.2026):
	```
	conda install -c conda-forge deepmd-kit
	```
- [Docker Hub](https://hub.docker.com/r/deepmodeling/deepmd-kit) (📥 6.2K · ⭐ 1 · ⏱️ 07.06.2026):
	```
	docker pull deepmodeling/deepmd-kit
	```
</details>
<details><summary><b><a href="https://github.com/deepmodeling/deepmd-kit">DeePMD-DPA3</a></b> (🥇23 ·  ⭐ 2K) - Successor of DPA-2. <code><a href="http://bit.ly/37RvQcA">LGPL-3.0</a></code> <code>ML-IAP</code> <code>pretrained</code> <code>workflows</code> <code>datasets</code></summary>

- [GitHub](https://github.com/deepmodeling/deepmd-kit) (👨‍💻 88 · 🔀 620 · 📦 57):

	```
	git clone https://github.com/deepmodeling/deepmd-kit
	```
- [PyPi](https://pypi.org/project/deepmd-kit) (📥 19K / month · 📦 21 · ⏱️ 06.06.2026):
	```
	pip install deepmd-kit
	```
- [Conda](https://anaconda.org/conda-forge/deepmd-kit) (📥 3M · ⏱️ 07.06.2026):
	```
	conda install -c conda-forge deepmd-kit
	```
- [Docker Hub](https://hub.docker.com/r/deepmodeling/deepmd-kit) (📥 6.2K · ⭐ 1 · ⏱️ 07.06.2026):
	```
	docker pull deepmodeling/deepmd-kit
	```
</details>
<details><summary><b><a href="https://github.com/ACEsuit/mace-foundations">MACE-FOUNDATION models</a></b> (🥇23 ·  ⭐ 1.2K) - MACE foundation models (MP, OMAT, Matpes). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a></summary>

- [GitHub](https://github.com/ACEsuit/mace-foundations) (👨‍💻 5 · 🔀 420):

	```
	git clone https://github.com/ACEsuit/mace-foundations
	```
- [PyPi](https://pypi.org/project/mace-torch) (📥 100K / month · 📦 110 · ⏱️ 10.05.2026):
	```
	pip install mace-torch
	```
</details>
<details><summary><b><a href="https://github.com/FAIR-Chem/fairchem/tree/main/src/fairchem/core/models/equiformer_v2">FAIRChem EquiformerV2 models</a></b> (🥈22 ·  ⭐ 2.1K) - FAIRChem implementation of Equiformer V2 (eqV2) models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a></summary>

- [GitHub]() (👨‍💻 69 · 🔀 480):

	```
	git clone https://github.com/FAIR-Chem/fairchem
	```
- [PyPi](https://pypi.org/project/fairchem-core) (📥 74K / month · 📦 48 · ⏱️ 08.06.2026):
	```
	pip install fairchem-core
	```
</details>
<details><summary><b><a href="https://github.com/janosh/matbench-discovery/tree/main/models/eSEN">FAIRChem eSEN models</a></b> (🥈22 ·  ⭐ 2.1K) - FAIRChem implementation of Smooth Energy Network (eSEN) models arXiv:2502.12147. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <a href="https://www.google.com/search?q=universal+interatomic+potential"><code>UIP</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Catalysis"><code>catalysis</code></a></summary>

- [GitHub]() (👨‍💻 69 · 🔀 480):

	```
	git clone https://github.com/FAIR-Chem/fairchem
	```
- [PyPi](https://pypi.org/project/fairchem-core) (📥 74K / month · 📦 48 · ⏱️ 08.06.2026):
	```
	pip install fairchem-core
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/mattersim">MatterSim</a></b> (🥈20 ·  ⭐ 560) - MatterSim: A deep learning atomistic model across elements, temperatures and pressures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Active_learning_(machine_learning)"><code>active-learning</code></a> <a href="https://en.wikipedia.org/wiki/Multimodal_learning"><code>multimodal</code></a> <a href="https://en.wikipedia.org/wiki/Phase_transition"><code>phase-transition</code></a> <code>pretrained</code></summary>

- [GitHub](https://github.com/microsoft/mattersim) (👨‍💻 23 · 🔀 85):

	```
	git clone https://github.com/microsoft/mattersim
	```
- [PyPi](https://pypi.org/project/mattersim) (📥 48K / month · 📦 29 · ⏱️ 28.05.2026):
	```
	pip install mattersim
	```
</details>
<details><summary><b><a href="https://github.com/orbital-materials/orb-models">Orb Models</a></b> (🥈19 ·  ⭐ 580) - ORB forcefield models from Orbital Materials. <code><a href="https://github.com/orbital-materials/orb-models/blob/main/LICENSE">Custom</a></code> <code>ML-IAP</code> <code>pretrained</code></summary>

- [GitHub](https://github.com/orbital-materials/orb-models) (👨‍💻 16 · 🔀 85 · 📦 38):

	```
	git clone https://github.com/orbital-materials/orb-models
	```
- [PyPi](https://pypi.org/project/orb-models) (📥 14K / month · 📦 38 · ⏱️ 26.05.2026):
	```
	pip install orb-models
	```
</details>
<details><summary><b><a href="https://github.com/MDIL-SNU/SevenNet">SevenNet</a></b> (🥈19 ·  ⭐ 250) - SevenNet - a graph neural network interatomic potential package supporting efficient multi-GPU parallel molecular.. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>pretrained</code></summary>

- [GitHub](https://github.com/MDIL-SNU/SevenNet) (👨‍💻 22 · 🔀 55):

	```
	git clone https://github.com/MDIL-SNU/SevenNet
	```
- [PyPi](https://pypi.org/project/sevenn) (📥 15K / month · 📦 28 · ⏱️ 19.06.2026):
	```
	pip install sevenn
	```
</details>
<details><summary><b><a href="https://github.com/CederGroupHub/chgnet">CHGNet</a></b> (🥉18 ·  ⭐ 360 · 💤) - Pretrained universal neural network potential for charge-informed atomistic modeling https://chgnet.lbl.gov. <code><a href="https://github.com/CederGroupHub/chgnet/blob/main/LICENSE">Custom</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Electrostatics"><code>electrostatics</code></a> <code>magnetism</code> <code>structure-relaxation</code></summary>

- [GitHub](https://github.com/CederGroupHub/chgnet) (👨‍💻 13 · 🔀 93 · 📦 74):

	```
	git clone https://github.com/CederGroupHub/chgnet
	```
- [PyPi](https://pypi.org/project/chgnet) (📥 160K / month · 📦 33 · ⏱️ 22.09.2025):
	```
	pip install chgnet
	```
</details>
<details><summary><b><a href="https://lab-cosmo.github.io/upet/latest">PET-MAD</a></b> (🥉14 ·  ⭐ 220 · 💤) - A universal interatomic potential for advanced materials modeling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>ML-IAP</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a></summary>

- [GitHub]() (👨‍💻 17 · 🔀 22 · 📦 8):

	```
	git clone https://github.com/lab-cosmo/pet-mad
	```
- [PyPi](https://pypi.org/project/pet-mad) (📥 700 / month · 📦 9 · ⏱️ 12.12.2025):
	```
	pip install pet-mad
	```
- [Conda](https://anaconda.org/conda-forge/pet-mad):
	```
	conda install -c conda-forge pet-mad
	```
</details>
<details><summary><b><a href="https://github.com/ICAMS/grace-tensorpotential">GRACE</a></b> (🥉9 ·  ⭐ 96) - GRACE models and gracemaker (as implemented in TensorPotential package). <code><a href="https://github.com/ICAMS/grace-tensorpotential/blob/master/LICENSE.md">Custom</a></code> <code>ML-IAP</code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a></summary>

- [GitHub](https://github.com/ICAMS/grace-tensorpotential) (👨‍💻 5 · 🔀 16 · 📦 14):

	```
	git clone https://github.com/ICAMS/grace-tensorpotential
	```
</details>
<details><summary><b><a href="https://huggingface.co/spaces/atomind/mlip-arena">MLIP Arena Leaderboard</a></b> (🥉7 ·  ⭐ 94) - [NeurIPS 25 Spotlight] Fair and transparent benchmark of machine learning interatomic potentials (MLIPs), beyond basic.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>ML-IAP</code> <code>benchmarking</code></summary>

- [GitHub](https://github.com/atomind-ai/mlip-arena) (👨‍💻 3 · 🔀 8 · 📦 2):

	```
	git clone https://github.com/atomind-ai/mlip-arena
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/materialsvirtuallab/m3gnet">M3GNet</a></b> (🥉15 ·  ⭐ 300 · 💀) - Materials graph network with 3-body interactions featuring a DFT surrogate crystal relaxer and a state-of-the-art.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>ML-IAP</code> <code>pretrained</code>
- <b><a href="https://github.com/janosh/ffonons">ffonons</a></b> (🥉6 ·  ⭐ 15 · 💀) - Phonons from ML force fields. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>benchmarking</code> <a href="https://en.wikipedia.org/wiki/Density_of_states"><code>density-of-states</code></a>
- <b><a href="https://github.com/facebookresearch/JMP">Joint Multidomain Pre-Training (JMP)</a></b> (🥉5 ·  ⭐ 33 · 💀) - Code for From Molecules to Materials Pre-training Large Generalizable Models for Atomic Property Prediction. <code><a href="https://tldrlegal.com/search?q=CC-BY-NC-4.0">CC-BY-NC-4.0</a></code> <code>pretrained</code> <code>ML-IAP</code> <code>general-tool</code>
- <b><a href="https://github.com/usnistgov/chipsff">CHIPS-FF</a></b> (🥉4 ·  ⭐ 8 · 💤) - Evaluation of universal machine learning force-fields https://doi.org/10.1021/acsmaterialslett.5c00093. <code><a href="https://github.com/usnistgov/chipsff/blob/main/LICENSE.rst">Custom</a></code> <code>benchmarking</code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>structure-optimization</code></a> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Transport_phenomena"><code>transport-phenomena</code></a>
</details>
<br>

## Unsupervised Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on unsupervised, semi- or self-supervised learning for atomistic ML, such as dimensionality reduction, clustering, contrastive learning, etc._

<details><summary><b><a href="https://github.com/sissa-data-science/DADApy">DADApy</a></b> (🥇16 ·  ⭐ 140) - Distance-based Analysis of DAta-manifolds in python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sissa-data-science/DADApy) (👨‍💻 23 · 🔀 23):

	```
	git clone https://github.com/sissa-data-science/DADApy
	```
- [PyPi](https://pypi.org/project/dadapy) (📥 680 / month · 📦 3 · ⏱️ 01.05.2026):
	```
	pip install dadapy
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/sparks-baird/mat_discover">mat_discover</a></b> (🥈11 ·  ⭐ 46 · 💀) - A materials discovery algorithm geared towards exploring high-performance candidates in new chemical spaces. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <a href="https://en.wikipedia.org/wiki/High-throughput_computing"><code>HTC</code></a>
- <b><a href="https://github.com/ncfrey/pumml">pumml</a></b> (🥈10 ·  ⭐ 23 · 💀) - Positive and Unlabeled Materials Machine Learning (pumml) is a code that uses semi-supervised machine learning to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://www.psik2022.net/program/symposia#h.p_hM6hJbQD9dex"><code>materials-discovery</code></a>
- <b><a href="https://github.com/BingqingCheng/ASAP">ASAP</a></b> (🥈8 ·  ⭐ 63 · 💀) - ASAP is a package that can quickly analyze and visualize datasets of crystal or molecular structures. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lab-cosmo/sketchmap">Sketchmap</a></b> (🥉6 ·  ⭐ 43 · 💀) - Suite of programs to perform non-linear dimensionality reduction -- sketch-map in particular. <code><a href="http://bit.ly/2M0xdwT">GPL-3.0</a></code> <code>C++</code>
- <b><a href="https://github.com/jiaor17/3D-EMGP">3D-EMGP</a></b> (🥉6 ·  ⭐ 31 · 💀) - [AAAI 2023] The implementation for the paper Energy-Motivated Equivariant Pretraining for 3D Molecular Graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>pretrained</code> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a> <code>single-paper</code>
- <b><a href="https://github.com/mathsphy/paper-ml-robustness-material-property">paper-ml-robustness-material-property</a></b> (🥉5 ·  ⭐ 4 · 💀) - A critical examination of robustness and generalizability of machine learning prediction of materials properties. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>datasets</code> <code>single-paper</code>
- <b><a href="https://github.com/learningmatter-mit/Coarse-Graining-Auto-encoders">Coarse-Graining-Auto-encoders</a></b> (🥉2 ·  ⭐ 4 · 💀) - Implementation of coarse-graining Autoencoders. <code>Unlicensed</code> <code>single-paper</code>
- <b><a href="https://github.com/Minoru938/KmdPlus">KmdPlus</a></b> (🥉2 ·  ⭐ 3 · 💀) - This module contains a class for treating kernel mean descriptor (KMD), and a function for generating descriptors with.. <code>Unlicensed</code>
- <b><a href="https://gitlab.mpcdf.mpg.de/klai/decaf">Descriptor Embedding and Clustering for Atomisitic-environment Framework (DECAF)</a></b> ( ⭐ 2) - Provides a workflow to obtain clustering of local environments in dataset of structures. <code>Unlicensed</code>
</details>
<br>

## Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects that focus on visualization (viz.) for atomistic ML._

<details><summary><b><a href="https://github.com/materialsproject/crystaltoolkit">Crystal Toolkit</a></b> (🥇21 ·  ⭐ 190) - Crystal Toolkit is a framework for building web apps for materials science and is currently powering the new Materials.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/materialsproject/crystaltoolkit) (👨‍💻 39 · 🔀 66 · 📦 43):

	```
	git clone https://github.com/materialsproject/crystaltoolkit
	```
- [PyPi](https://pypi.org/project/crystal-toolkit) (📥 9.8K / month · 📦 13 · ⏱️ 21.07.2026):
	```
	pip install crystal-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/janosh/pymatviz">pymatviz</a></b> (🥈20 ·  ⭐ 320) - A toolkit for visualizations in materials informatics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>general-tool</code> <code>probabilistic</code></summary>

- [GitHub](https://github.com/janosh/pymatviz) (👨‍💻 14 · 🔀 40 · 📦 36):

	```
	git clone https://github.com/janosh/pymatviz
	```
- [PyPi](https://pypi.org/project/pymatviz) (📥 15K / month · 📦 10 · ⏱️ 07.06.2026):
	```
	pip install pymatviz
	```
</details>
<details><summary><b><a href="https://github.com/lab-cosmo/chemiscope">Chemiscope</a></b> (🥈16 ·  ⭐ 180) - An interactive structure/property explorer for materials and molecules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code>JavaScript</code></summary>

- [GitHub](https://github.com/lab-cosmo/chemiscope) (👨‍💻 27 · 🔀 43 · 📦 6):

	```
	git clone https://github.com/lab-cosmo/chemiscope
	```
- [npm](https://www.npmjs.com/package/chemiscope) (📥 220 / month · 📦 3 · ⏱️ 15.03.2023):
	```
	npm install chemiscope
	```
</details>
<details><summary><b><a href="https://github.com/zincware/ZnDraw">ZnDraw</a></b> (🥉14 ·  ⭐ 49) - A powerful tool for visualizing, modifying, and analysing atomistic systems. <code><a href="http://bit.ly/2M0xmjV">EPL-2.0</a></code> <a href="https://en.wikipedia.org/wiki/Molecular_dynamics"><code>MD</code></a> <a href="https://en.wikipedia.org/wiki/Generative_model"><code>generative</code></a> <code>JavaScript</code></summary>

- [GitHub](https://github.com/zincware/ZnDraw) (👨‍💻 16 · 🔀 5 · 📦 16):

	```
	git clone https://github.com/zincware/ZnDraw
	```
- [PyPi](https://pypi.org/project/zndraw) (📥 3K / month · 📦 5 · ⏱️ 01.04.2026):
	```
	pip install zndraw
	```
</details>
<details><summary><b><a href="https://github.com/usnistgov/atomvision">Atomvision</a></b> (🥉9 ·  ⭐ 34 · 💤) - Deep learning framework for atomistic image data. <code><a href="https://github.com/usnistgov/atomvision/blob/master/LICENSE.md">Custom</a></code> <a href="https://en.wikipedia.org/wiki/Computer_vision"><code>computer-vision</code></a> <a href="https://en.wikipedia.org/wiki/Experimental_physics"><code>experimental-data</code></a> <a href="https://en.wikipedia.org/wiki/Feature_learning"><code>rep-learn</code></a></summary>

- [GitHub](https://github.com/usnistgov/atomvision) (👨‍💻 4 · 🔀 17 · 📦 4):

	```
	git clone https://github.com/usnistgov/atomvision
	```
- [PyPi](https://pypi.org/project/atomvision) (⏱️ 08.05.2023):
	```
	pip install atomvision
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://janosh.github.io/matterviz">Elementari</a></b> (🥉11 ·  ⭐ 350 · 💀) - Interactive visualizations for materials science: periodic tables, 3D structures, MD trajectories, heatmaps, scatter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>JavaScript</code>
</details>
<br>

## Wavefunction methods (ML-WFT)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Projects and models that focus on quantities of wavefunction theory methods, such as Monte Carlo techniques like deep learning variational Monte Carlo (DL-VMC), quantum chemistry methods, etc._

<details><summary><b><a href="https://github.com/deepqmc/deepqmc">DeepQMC</a></b> (🥇16 ·  ⭐ 420) - Deep learning quantum Monte Carlo for electrons in real space. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/deepqmc/deepqmc) (👨‍💻 15 · 🔀 62 · 📦 3):

	```
	git clone https://github.com/deepqmc/deepqmc
	```
- [PyPi](https://pypi.org/project/deepqmc) (📥 340 / month · ⏱️ 20.07.2026):
	```
	pip install deepqmc
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/google-deepmind/ferminet">FermiNet</a></b> (🥈10 ·  ⭐ 690 · 💀) - An implementation of the Fermionic Neural Network for ab-initio electronic structure calculations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <a href="https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)"><code>transformer</code></a>
- <b><a href="https://github.com/mdsunivie/deeperwin">DeepErwin</a></b> (🥈9 ·  ⭐ 67 · 💀) - DeepErwin is a python 3.8+ package that implements and optimizes JAX 2.x wave function models for numerical solutions.. <code><a href="https://github.com/mdsunivie/deeperwin/blob/master/LICENSE">Custom</a></code>
- <b><a href="https://github.com/atomistic-machine-learning/SchNOrb">SchNOrb</a></b> (🥉6 ·  ⭐ 57 · 💀) - Unifying machine learning and quantum chemistry with a deep neural network for molecular wavefunctions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ACEsuit/ACEpsi.jl">ACEpsi.jl</a></b> (🥉5 ·  ⭐ 3 · 💤) - ACE wave function parameterizations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <a href="https://en.wikipedia.org/wiki/Feature_engineering"><code>rep-eng</code></a> <code>Julia</code>
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
