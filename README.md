# Awesome Cheminformatics with stars

> Cheminformatics (also known as chemoinformatics, chemioinformatics and chemical informatics) is the use of computer and informational techniques applied to a range of problems in the field of chemistry.— [Wikipedia](https://en.wikipedia.org/wiki/Cheminformatics)

A curated list of awesome Cheminformatics software, resources, and libraries. Mostly command line based, and free or open-source. Please feel free to [contribute](CONTRIBUTING.md) !

## Contents

* [Applications](#applications)
  * [Visualization](#app-visualization)
  * [Command Line Tools](#app-cmd)
  * [Docking](#app-docking)
  * [Virtual Machine](#app-virtual)
* [Libraries](#libraries)
  * [General Purpose](#lib-general)
  * [Visualization](#lib-visualization)
  * [Command Line Tools](#lib-format)
  * [Docking](#lib-dock)
  * [Molecular Descriptors](#lib-des)
  * [Machine Learning](#lib-ml)
  * [Web APIs](#lib-web)
  * [Databases](#lib-db)
  * [Others](#lib-others)
* [Journals](#journals)
* [Resources](#resources)
  * [Courses](#courses)
  * [Blogs](#blogs)
  * [Books](#books)
* [See Also](#see-also)

## Applications

<a id="app-visualization"></a>

### Visualization

* [PyMOL](https://sourceforge.net/projects/pymol/) - Python-enhanced molecular graphics tool.
* [Jmol](http://jmol.sourceforge.net/) - Browser-based HTML5 viewer and stand-alone Java viewer for chemical structures in 3D.
* [VMD](http://www.ks.uiuc.edu/Research/vmd/) - Molecular visualization program for displaying, animating, and analyzing large biomolecular systems using 3-D graphics and built-in scripting.
* [Chimera](https://www.cgl.ucsf.edu/chimera/) - Highly extensible program for interactive molecular visualization and analysis. [Source](https://www.cgl.ucsf.edu/chimera/docs/sourcecode.html) is available.
* [ChimeraX](https://www.cgl.ucsf.edu/chimerax/) - The next-generation molecular visualization program, following UCSF Chimera. Source is available [here](https://www.cgl.ucsf.edu/chimerax/docs/devel/conventions.html).
* [DataWarrior](http://www.openmolecules.org/datawarrior/index.html) - A program for data Visualization and analysis which combines dynamic graphical views and interactive row filtering with chemical intelligence.

<a id="app-cmd"></a>

### Command Line Tools

* [Open Babel](http://openbabel.org/wiki/Main_Page) - Chemical toolbox designed to speak the many languages of chemical data.
* [MayaChemTools](http://www.mayachemtools.org/index.html) - Collection of Perl and Python scripts, modules, and classes that support day-to-day computational discovery needs.
* [Packmol](http://m3g.iqm.unicamp.br/packmol/home.shtml) - Initial configurations for molecular dynamics simulations by packing optimization.
* [BCL::Commons](http://meilerlab.org/index.php/bclcommons/show/b_apps_id/1)

<a id="app-docking"></a>

### Docking

* [AutoDock Vina](http://vina.scripps.edu/) - Molecular docking and virtual screening.
* [smina](https://sourceforge.net/projects/smina/) - Customized [AutoDock Vina](http://vina.scripps.edu/) to better support scoring function development and high-performance energy minimization.

<a id="app-virtual"></a>

### Virtual Machine

* [myChEMBL](http://chembl.blogspot.com/2015/07/mychembl-20-has-landed.html) - A version of ChEMBL built using Open Source software (Ubuntu, PostgreSQL, RDKit)
* [3D e-Chem Virtual Machine](https://github.com/3D-e-Chem/3D-e-Chem-VM) ⭐ 17 | 🐛 5 | 🌐 Shell | 📅 2018-09-27 - Virtual machine with all software and sample data to run 3D-e-Chem Knime workflows

## Libraries

<a id="lib-general"></a>

### General Purpose

* [ChemPy](https://github.com/bjodah/chempy) ⭐ 657 | 🐛 37 | 🌐 Python | 📅 2026-08-18 - A Python package useful for chemistry (mainly physical/inorganic/analytical chemistry)
* [datamol](https://github.com/datamol-org/datamol) ⭐ 545 | 🐛 13 | 🌐 Python | 📅 2026-05-20: - Molecular Manipulation Made Easy. A light wrapper build on top of RDKit.
* [Indigo](https://github.com/epam/Indigo) ⭐ 406 | 🐛 745 | 🌐 C++ | 📅 2026-08-26 - Universal molecular toolkit that can be used for molecular fingerprinting, substructure search, and molecular visualization written in C++ package, with Java, C#, and Python wrappers.
* [MolecularGraph.jl](https://github.com/mojaie/MolecularGraph.jl) ⭐ 227 | 🐛 17 | 🌐 Julia | 📅 2026-06-03 - A graph-based molecule modeling and chemoinformatics analysis toolkit fully implemented in Julia
* [CGRtools](https://github.com/cimm-kzn/CGRtools) ⭐ 52 | 🐛 3 | 🌐 Python | 📅 2022-10-31 - Toolkit for processing molecules, reactions and condensed graphs of reactions. Can be used for chemical standardization, MCS search, tautomers generation with backward compatibility to RDKit and NetworkX.
* [RDKit](http://www.rdkit.org/) - Collection of cheminformatics and machine-learning software written in C++ and Python.
* [CDK (Chemistry Development Kit)](https://sourceforge.net/projects/cdk/) - Algorithms for structural chemo- and bioinformatics, implemented in Java.
* [ChemmineR](https://www.bioconductor.org/packages/release/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html) - Cheminformatics package for analyzing drug-like small molecule data in R.

<a id="lib-format"></a>

### Format Checking

* [pdb-tools](https://github.com/haddocking/pdb-tools) ⭐ 457 | 🐛 4 | 🌐 Python | 📅 2026-06-10 - A swiss army knife for manipulating and editing PDB files.
* [ChEMBL\_Structure\_Pipeline (formerly standardiser)](https://github.com/chembl/ChEMBL_Structure_Pipeline) ⭐ 247 | 🐛 9 | 🌐 Python | 📅 2025-11-24 - Tool designed to provide a simple way of standardising molecules as a prelude to e.g. molecular modelling exercises.
* [MolVS](https://github.com/mcs07/MolVS) ⭐ 188 | 🐛 23 | 🌐 Python | 📅 2020-04-16 - Molecule validation and standardization based on [RDKit](http://www.rdkit.org/).
* [rd\_filters](https://github.com/PatWalters/rd_filters) ⭐ 172 | 🐛 6 | 🌐 Python | 📅 2026-02-17 - A script to run structural alerts using the RDKit and ChEMBL

<a id="lib-visualization"></a>

### Visualization

* [3Dmol.js](https://github.com/3dmol/3Dmol.js) ⭐ 1,007 | 🐛 44 | 🌐 Jupyter Notebook | 📅 2026-08-17 - An object-oriented, webGL based JavaScript library for online molecular visualization.
* [rdeditor](https://github.com/EBjerrum/rdeditor) ⭐ 179 | 🐛 4 | 🌐 Python | 📅 2026-05-03 - Simple RDKit molecule editor GUI using PySide.
* [JChemPaint](https://github.com/JChemPaint/jchempaint) ⭐ 145 | 🐛 115 | 🌐 Java | 📅 2026-04-24 - Chemical 2D structure editor application/applet based on the [Chemistry Development Kit](https://sourceforge.net/projects/cdk/).
* [Kekule.js](http://partridgejiang.github.io/Kekule.js/) - Front-end JavaScript library for providing the ability to represent, draw, edit, compare and search molecule structures on web browsers.
* [nglviewer](http://nglviewer.org/nglview/latest/) - Interactive molecular graphics for Jupyter notebooks.
* [RDKit.js](https://www.npmjs.com/package/@rdkit/rdkit) - Official JavaScript distribution of cheminformatics functionality from the RDKit - a C++ library for cheminformatics.

<a id="lib-des"></a>

### Molecular Descriptors

* [mordred](https://github.com/mordred-descriptor/mordred) ⭐ 479 | 🐛 55 | 🌐 Python | 📅 2024-02-07 - Molecular descriptor calculator based on [RDKit](http://www.rdkit.org/).
* [mol2vec](https://github.com/samoturk/mol2vec) ⚠️ Archived - Vector representations of molecular substructures.
* [DescriptaStorus](https://github.com/bp-kelley/descriptastorus) ⭐ 280 | 🐛 3 | 🌐 Python | 📅 2024-10-26 - Descriptor computation(chemistry) and (optional) storage for machine learning.
* [Align-it](http://silicos-it.be.s3-website-eu-west-1.amazonaws.com/software/align-it/1.0.4/align-it.html#alignit-generating-pharmacophore-points) - Align molecules according their pharmacophores.
* [Rcpi](https://nanx.me/Rcpi/index.html) - R/Bioconductor package to generate various descriptors of proteins, compounds and their interactions.

<a id="lib-ml"></a>

### Machine Learning

* [DeepChem](https://github.com/deepchem/deepchem) ⭐ 6,962 | 🐛 1,165 | 🌐 Python | 📅 2026-08-20 - Deep learning library for Chemistry based on Tensorflow
* [Chemprop](https://github.com/chemprop/chemprop) ⭐ 2,438 | 🐛 13 | 🌐 Python | 📅 2026-08-21 - Directed message passing neural networks for property prediction of molecules and reactions with uncertainty and interpretation.
* [DGL-LifeSci](https://github.com/awslabs/dgl-lifesci) ⭐ 809 | 🐛 32 | 🌐 Python | 📅 2023-11-01 - DGL-LifeSci is a [DGL](https://www.dgl.ai/)-based package for various applications in life science with graph neural network.
* [OpenChem](https://github.com/Mariewelt/OpenChem) ⭐ 753 | 🐛 17 | 🌐 Python | 📅 2023-11-26 - OpenChem is a deep learning toolkit for Computational Chemistry with PyTorch backend.
* [chainer-chemistry](https://github.com/pfnet-research/chainer-chemistry) ⭐ 706 | 🐛 31 | 🌐 Python | 📅 2023-04-20 - A Library for Deep Learning in Biology and Chemistry.
* [ChemML](https://github.com/hachmannlab/chemml) ⭐ 180 | 🐛 3 | 🌐 Python | 📅 2026-08-19 - ChemML is a machine learning and informatics program suite for the analysis, mining, and modeling of chemical and materials data. (based on Tensorflow)
* [Summit](https://github.com/sustainable-processes/summit) ⭐ 151 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2024-09-03 - A python package for optimizing chemical reactions using machine learning (contains 10 algorithms + several benchmarks).
* [chemmodlab](https://github.com/jrash/ChemModLab) ⭐ 17 | 🐛 0 | 🌐 R | 📅 2025-11-20 - A Cheminformatics Modeling Laboratory for Fitting and Assessing Machine Learning Models in R.
* [olorenchemengine](https://github.com/Oloren-AI/olorenchemengine) - Molecular property prediction with unified API for diverse models and respresentations,
  with integrated uncertainty quantification, interpretability, and hyperparameter/architecture tuning.
* [pytorch-geometric](https://pytorch-geometric.readthedocs.io/en/latest/) - A PyTorch library provides implementation of many graph convolution algorithms.

<a id="lib-web"></a>

### Web APIs

* [webchem](https://github.com/ropensci/webchem) ⭐ 186 | 🐛 60 | 🌐 R | 📅 2026-08-21 - Chemical Information from the Web.
* [Beaker](https://github.com/chembl/chembl_beaker) ⚠️ Archived - [RDKit](http://www.rdkit.org/) and [OSRA](https://cactus.nci.nih.gov/osra/) in the [Bottle](http://bottlepy.org/docs/dev/) on [Tornado](http://www.tornadoweb.org/en/stable/).
* [chemminetools](https://github.com/girke-lab/chemminetools) ⭐ 42 | 🐛 54 | 🌐 JavaScript | 📅 2022-12-08 - Open source web framework for small molecule analysis based on Django.
* [PubChemPy](http://pubchempy.readthedocs.io) - Python wrapper for the PubChem PUG REST API.
* [ChemSpiPy](http://chemspipy.readthedocs.org) - Python wrapper for the ChemSpider API.
* [CIRpy](http://cirpy.readthedocs.org/) - Python wrapper for the [NCI Chemical Identifier Resolver (CIR)](https://cactus.nci.nih.gov/chemical/structure).
* [ambit](http://ambit.sourceforge.net/) - offers chemoinformatics functionality via REST web services.

<a id="lib-db"></a>

### Databases

* [razi](https://github.com/rvianello/razi) ⭐ 40 | 🐛 2 | 🌐 Python | 📅 2025-09-11 - Cheminformatic extension for the SQLAlchemy database.
* [Chemical Translation Service](https://bitbucket.org/fiehnlab/fiehnlab-cts/src/master/) - Source code of the [Chemical Translation Service](https://cts.fiehnlab.ucdavis.edu/) web service.

<a id="lib-dock"></a>

### Docking

* [DOCKSTRING](https://github.com/dockstring/dockstring) ⭐ 188 | 🐛 8 | 🌐 Python | 📅 2026-05-24 - Automates and standardizes ligand preparation for AutoDock Vina.
* [Rosetta](https://www.rosettacommons.org/docs/latest/Home) - A comprehensive software suite for modeling macromolecular structures. Used larely for protein-protein docking.

<a id="lib-md"></a>

### Molecular Dynamics

* [MDTraj](https://github.com/mdtraj/mdtraj) ⭐ 729 | 🐛 87 | 🌐 Python | 📅 2026-08-19 - Analysis of molecular dynamics trajectories.
* [ProDy](https://github.com/prody/ProDy) ⭐ 554 | 🐛 35 | 🌐 Python | 📅 2026-08-26 - A Python package for protein dynamics analysis
* [cclib](https://github.com/cclib/cclib) ⭐ 423 | 🐛 189 | 🌐 Python | 📅 2026-08-26 - Parsers and algorithms for computational chemistry logfiles.
* [Gromacs](http://www.gromacs.org/) - Molecular dynamics package mainly designed for simulations of proteins, lipids and nucleic acids.
* [OpenMM](http://openmm.org/) - High performance toolkit for molecular simulation including extensive language bindings for Python, C, C++, and even Fortran.
* [NAMD](https://www.ks.uiuc.edu/Research/namd/) - a parallel molecular dynamics code designed for high-performance simulation of large biomolecular systems.

<a id="lib-others"></a>

### Others

* [Cookiecutter for Computational Molecular Sciences](https://github.com/MolSSI/cookiecutter-cms) ⭐ 461 | 🐛 30 | 🌐 Python | 📅 2025-12-15 - Python-centric Cookiecutter for Molecular Computational Chemistry Packages by [MolSSL](https://molssi.org/)
* [OPSIN](https://github.com/dan2097/opsin) ⭐ 232 | 🐛 110 | 🌐 Java | 📅 2026-08-19 - Open Parser for Systematic IUPAC nomenclature
* [RDchiral](https://github.com/connorcoley/rdchiral) ⭐ 188 | 🐛 22 | 🌐 Jupyter Notebook | 📅 2023-09-18 - Wrapper for RDKit's RunReactants to improve stereochemistry handling
* [Auto-QChem](https://github.com/PrincetonUniversity/auto-qchem) ⭐ 129 | 🐛 5 | 🌐 Python | 📅 2026-01-14 - an automated workflow for the generation and storage of DFT calculations for organic molecules.
* [confgen](https://github.com/Et9797/confgen-webapp) ⭐ 7 | 🐛 0 | 🌐 HTML | 📅 2026-01-06 - Webapp for generating conformers
* [eiR](https://github.com/girke-lab/eiR) ⭐ 4 | 🐛 2 | 🌐 R | 📅 2025-02-11 - Accelerated similarity searching of small molecules
* [Gypsum-DL](https://git.durrantlab.pitt.edu/jdurrant/gypsum_dl) - a program for converting 2D SMILES strings to 3D models.

## Journals

* [Journal of Cheminformatics](https://jcheminf.biomedcentral.com/)
* [Journal of Chemical Information and Modeling (ACS Publications)](https://pubs.acs.org/journal/jcisd8)

## Resources

### Courses

* [TeachOpenCADD](https://github.com/volkamerlab/TeachOpenCADD) ⭐ 1,054 | 🐛 59 | 🌐 Jupyter Notebook | 📅 2026-08-27 - A teaching platform for computer-aided drug design (CADD) using open source packages and data.
* [Python for chemoinformatics](https://github.com/Mishima-syk/py4chemoinformatics) ⭐ 236 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2021-06-26
* [Learncheminformatics.com](http://learncheminformatics.com/) - "Cheminformatics: Navigating the world of chemical data" courese at Indiana University.
* [Cheminformatics OLCC](https://chem.libretexts.org/Courses/Intercollegiate_Courses/Cheminformatics_OLCC_\(2019\)) - Cheminformatics course of the Collaborative Intercollegiate Online Chemistry Course (OLCC) course of University of Arkansas at Little Rock by Robert Belford
* [BigChem](http://bigchem.eu/alllectures) - All lectures of [BigChem](http://bigchem.eu/) (A Horizon 2020 MSC ITN EID project, which provides innovative education in large chemical data analysis.)
* [Molecular modeling course](https://dasher.wustl.edu/chem478/) - by Dr. [Jay Ponder](https://dasher.wustl.edu/), a professor from WashU St.Louis.
* [Simulation in Chemistry and Biochemistry](https://dasher.wustl.edu/chem430/) - by Dr. [Jay Ponder](https://dasher.wustl.edu/), a professor from WashU St.Louis.

### Blogs

* [Open Source Molecular Modeling](https://opensourcemolecularmodeling.github.io/README.html) - Updateable catalog of open source molecular modeling software.
* [PubChem Blog](https://pubchemblog.ncbi.nlm.nih.gov/) - News, updates and tutorials about [PubChem](https://pubchem.ncbi.nlm.nih.gov/).
* [The ChEMBL-og blog](http://chembl.blogspot.tw/) - Stories and news from Computational Chemical Biology Group at [EMBL-EBI](https://www.ebi.ac.uk/).
* [ChEMBL blog](http://chembl.github.io/) - ChEMBL on GitHub.
* [SteinBlog](http://www.steinbeck-molecular.de/steinblog/) - Blog of [Christoph Steinbeck](http://www.steinbeck-molecular.de/steinblog/index.php/about/), who is the head of cheminformatics and metabolism at the EMBL-EBI.
* [Practical Cheminformatics](http://practicalcheminformatics.blogspot.com/) - Blog with in-depth examples of practical application of cheminformatics.
* [So much to do, so little time - Trying to squeeze sense out of chemical data](http://blog.rguha.net/) - Bolg of [Rajarshi Guha](http://blog.rguha.net/?page_id=8), who is a research scientist at NIH Center for Advancing Translational Science.
   \* Some old blogs [1](https://rguha.wordpress.com/) [2](http://www.rguha.net/index.html).
* [Noel O'Blog](http://baoilleach.blogspot.tw/) - Blog of [Noel O'Boyle](https://www.redbrick.dcu.ie/~noel/), who is a Senior Software Engineer at NextMove Software.
* [chem-bla-ics](http://chem-bla-ics.blogspot.tw/) - Blog of [Egon Willighagen](http://egonw.github.io/), who is an assistant professor at Maastricht University.

<!---
* [Asad's Blog](https://chembioinfo.com/) - Bolg of Syed Asad Rahman, who is a research scientist in the [Thornton group](http://www.ebi.ac.uk/research/thornton) at EMBL-EBI.
-->

* [steeveslab-blog](http://asteeves.github.io/) - Some examples using [RDKit](http://www.rdkit.org/).
* [Macs in Chemistry](http://www.macinchem.org/) - Provide a resource for chemists using Apple Macintosh computers.
* [DrugDiscovery.NET](http://www.drugdiscovery.net/) - Blog of [Andreas Bender](http://www.andreasbender.de/), who is a Reader for Molecular Informatics at University of Cambridge.
* [Is life worth living?](https://iwatobipen.wordpress.com/) - Some examples for cheminformatics libraries.
* [Cheminformatics 2.0](https://cheminf20.org/) - Blog of [Alex M. Clark](https://twitter.com/aclarkxyz), a research scientist at Collaborative Drug Discovery.
* [Depth-First](https://depth-first.com/) - Blog of [Richard L. Apodaca](https://depth-first.com/about/), a chemist living in La Jolla, California.
* [Cheminformania](https://www.cheminformania.com) - Blog of [Ph.D, Esben Jannik Bjerrum](https://www.cheminformania.com/about/esben-jannik-bjerrum/), who is a Principle Scientist and a Machine Learning and AI specialists at AstraZeneca.

### Books

* [Computational Approaches in Cheminformatics and Bioinformatics](https://books.google.com/books/about/Computational_Approaches_in_Cheminformat.html?id=bLqV4rYQoYsC) -  Include insights from public (NIH), academic, and industrial sources at the same time.
* [Chemoinformatics for Drug Discovery](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118742785) - Materials about how to use Chemoinformatics strategies to improve drug discovery results.
* [Molecular Descriptors for Chemoinformatics](https://onlinelibrary.wiley.com/doi/book/10.1002/9783527628766) - More than 3300 descriptors and related terms for chemoinformatic analysis of chemical compound properties.

<a id="see-also"></a>

## See Also

* [deeplearning-biology](https://github.com/hussius/deeplearning-biology#chemoinformatics-and-drug-discovery-) ⭐ 2,155 | 🐛 0 | 📅 2026-08-03 - Chemoinformatics and drug discovery section in deeplearning-biology repo.
* [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) ⭐ 1,434 | 🐛 10 | 📅 2025-09-21 - Another list focuses on Python stuff related to Chemistry.
* [awesome-small-molecule-ml](https://github.com/benb111/awesome-small-molecule-ml) ⭐ 242 | 🐛 5 | 📅 2023-11-25 - A list of papers, data sets, and other resources for machine learning for small-molecule drug discovery.
* [awesome-molecular-docking](https://github.com/yangnianzu0515/awesome-molecular-docking) ⭐ 106 | 🐛 2 | 📅 2023-02-23 - A curated list of molecular docking software, datasets, and other closely related resources.
* [MolSSI Molecular Software Database](https://molssi.org/software-search/)
  ＊[Pages created by Tobias Kind, PhD](https://fiehnlab.ucdavis.edu/staff/kind/metabolomics)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
