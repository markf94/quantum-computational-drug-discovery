# Awesome Quantum Drug Discovery

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources, papers, software, and tools at the intersection of quantum computing, quantum-inspired methods, and drug discovery.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*


## Contents

- [Review Papers & Perspectives](#review-papers--perspectives)
- [Quantum Chemistry & Molecular Simulation](#quantum-chemistry--molecular-simulation)
- [Molecular Docking & Virtual Screening](#molecular-docking--virtual-screening)
- [Protein Folding](#protein-folding)
- [Peptide & Antibody Design](#peptide--antibody-design)
- [RNA & Genomics](#rna--genomics)
- [Quantum Machine Learning for Drug Discovery](#quantum-machine-learning-for-drug-discovery)
- [Drug Combination & Optimization](#drug-combination--optimization)
- [Datasets & Benchmarks](#datasets--benchmarks)
- [Software & Tools](#software--tools)
- [Learning Resources](#learning-resources)
- [Quantum Hardware Platforms](#quantum-hardware-platforms)
- [Biochemical Quantum Hardware](#biochemical-quantum-hardware)
- [Companies & Startups](#companies--startups)
- [Contributing](#contributing)
- [License](#license)

## Review Papers & Perspectives

Comprehensive reviews and strategic perspectives on quantum computing applications in drug discovery.

### Foundational Reviews

- [Quantum computing for drug discovery](https://ieeexplore.ieee.org/document/8585034) - Early perspective on quantum computing opportunities in pharma. (IEEE, 2018)
- [Quantum chemistry in the age of quantum computing](https://pubs.acs.org/doi/10.1021/acs.chemrev.8b00803) - Comprehensive review of quantum algorithms for chemistry. (Chemical Reviews, 2019)
- [The prospects of quantum computing in computational molecular biology](https://wires.onlinelibrary.wiley.com/doi/epdf/10.1002/wcms.1481) - Foundational review of quantum computing prospects in molecular biology. (WIREs Comput. Mol. Sci., 2020)

### Recent Reviews & Perspectives

- [Quantum Computing for Molecular Biology](https://chemistry-europe.onlinelibrary.wiley.com/doi/full/10.1002/cbic.202300120) - Road map from ETH Zurich's Quantum for Life Center covering biochemical simulations, structure prediction, and data-driven approaches. (ChemBioChem, 2023)

### Industry Perspectives

- [BCG Survey](https://www.bcg.com/publications/2023/quantum-computing-will-transform-pharma) - 8 of top 10 biopharma companies piloting quantum projects. (BCG, 2023)

## Quantum Chemistry & Molecular Simulation

Quantum approaches for accurate molecular energy calculations, excited-state simulation, and hybrid workflows.

### Electronic Structure & Accuracy

- [High-Quality Protein Force Fields with Noisy Quantum Processors](https://arxiv.org/abs/1907.07128) - Resource estimates and workflow for improving biomolecular force fields via quantum chemistry. (arXiv, 2019)
- [Quantum chemical simulations of excited states](https://arxiv.org/abs/2109.02110) - Methods for computing excited electronic states relevant to photopharmacology. (arXiv, 2021)
- [Reliably assessing the electronic structure of cytochrome P450 on today's classical computers and tomorrow's quantum computers](https://arxiv.org/abs/2202.01244) - Boehringer Ingelheim, Google, and QSimulate CYP450 benchmark introducing BLISS+THC for quantum resource reduction. (npj Quantum Information, 2022)
- [Drug design on quantum computers](https://www.nature.com/articles/s41567-024-02411-5) - Comprehensive study on quantum methods for drug-relevant molecular simulations. (Nature Physics, 2024)

### Free Energy, Solvation & Hybrid Pipelines

- [A hybrid quantum computing pipeline for real world drug discovery](https://www.nature.com/articles/s41598-024-67897-8) - Practical hybrid quantum-classical pipeline for prodrug activation and covalent bond simulations. (Scientific Reports, 2024)

## Molecular Docking & Virtual Screening

Quantum and quantum-inspired approaches for ligand docking, pose prediction, and large-scale screening.

### Core Docking Methods

- [Molecular docking with Gaussian Boson Sampling](https://www.science.org/doi/10.1126/sciadv.aax1950) - Xanadu/ProteinQure collaboration showing photonic quantum devices can predict docking configurations via maximum weighted clique reductions. (Science Advances, 2020)
- [Molecular Docking Using Quantum Mechanical-Based Methods](https://pubmed.ncbi.nlm.nih.gov/32016899/) - Review of QM-based docking for improved accuracy. (Methods Mol. Biol., 2020)
- [Multibody molecular docking on a quantum annealer](https://arxiv.org/abs/2210.11401) - Multibody docking formulation mapped to quantum annealing for biomolecular interaction problems. (arXiv, 2022)
- [Molecular docking via quantum approximate optimization algorithm](https://arxiv.org/abs/2308.04098) - Pharmacophore-based approach using labeled distance graphs. (arXiv, 2024)
- [Quantum molecular docking with quantum-inspired algorithm](https://arxiv.org/abs/2404.08265) - QA-inspired binary encodings and hopscotch simulated bifurcation for rugged docking energy landscapes; compared against AutoDock Vina and DiffDock. (arXiv, 2024; JCTC 2024: [10.1021/acs.jctc.4c00141](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.4c00141))
- [Quantum-Inspired Machine Learning for Molecular Docking](https://arxiv.org/abs/2401.12999) - Quantum-inspired optimization combined with diffusion models for blind docking. (arXiv, 2024)

## Protein Folding

Quantum algorithms and comparative studies for protein and peptide folding.

### Lattice, VQE, and Quantum Walk Methods

- [A quantum alternating operator ansatz with hard and soft constraints for lattice protein folding](https://arxiv.org/abs/1810.13411) - QAOA-style approach splitting optimization into hard and soft constraints. (arXiv, 2018)
- [Coarse-grained lattice protein folding on a quantum annealer](https://arxiv.org/abs/1811.00713) - Improved Ising-type encodings on D-Wave with record lattice folding of Chignolin and Trp-Cage. (arXiv, 2018)
- [Resource-efficient quantum algorithm for protein folding](https://www.nature.com/articles/s41534-021-00368-4) - Introduced CVaR-VQE for tetrahedral-lattice protein folding. (npj Quantum Information, 2021)
- [Quantum walks for protein and peptide folding](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009037) - Quantum-walk-based structure prediction in 3D. (PLOS Comput. Biol., 2021)

### Comparative Studies & New Benchmarks

- [Quantum synergy in peptide folding: CVaR-VQE vs molecular dynamics](https://www.sciencedirect.com/science/article/abs/pii/S0141813024038388) - Comparative study of 50 peptides showing CVaR-VQE outperforming MD for global optimization. (Int. J. Biol. Macromol., 2024)
- [A comparative insight into peptide folding with quantum CVaR-VQE algorithm](https://link.springer.com/article/10.1007/s11128-024-04261-9) - Benchmarks CVaR-VQE against MD and Hidden Markov Models. (Quantum Inf. Process., 2024)

## Peptide & Antibody Design

Quantum methods specifically targeting biologics discovery.

- [Quantum computing for protein design](https://arxiv.org/pdf/2105.09690.pdf) - Approaches for computational protein and peptide engineering.
- [Quantum algorithms for antimicrobial peptides](https://arxiv.org/abs/2401.03994) - Includes membrane environmental effects without additional qubits.

## RNA & Genomics

Quantum computing applications for RNA structure prediction and genomic analysis.

- [Predicting RNA secondary structure using quantum computing](https://www.biorxiv.org/content/10.1101/2021.05.27.446060v1) - RNA folding formulated as combinatorial optimization on quantum hardware. (bioRxiv, 2021)
- [Quantum computing applications in genomics](https://www.mdpi.com/2076-3417/11/6/2696) - Survey of quantum approaches for genomic data analysis. (Applied Sciences, 2021)

## Quantum Machine Learning for Drug Discovery

Applications of QML to molecule generation, molecular property prediction, and drug-target modeling.

### Generative Models & Molecular Design

- [Quantum Generative Models for Small Molecule Drug Discovery](https://arxiv.org/abs/2101.03438) - Qubit-efficient hybrid quantum GAN generator for learning molecular distributions; includes code. (arXiv, 2021)
- [Quantum computing for near-term applications in generative chemistry and drug discovery](https://www.sciencedirect.com/science/article/pii/S1359644623001915) - Review of NISQ-era quantum applications for de novo molecular generation. (Drug Discovery Today, 2023)
- [Exploring the Advantages of Quantum Generative Adversarial Networks in Generative Chemistry](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00562) - Insilico/Zapata/U of T hybrid MolGAN-CQ with quantum discriminator outperforming classical GANs on drug-likeness metrics. (J. Chem. Inf. Model., 2023)
- [Hybrid quantum-classical machine learning for generative chemistry and drug design](https://www.nature.com/articles/s41598-023-32703-4) - Hybrid architectures combining quantum circuits with classical networks for molecule generation and property optimization. (Scientific Reports, 2023)

### Property, Activity, and Interaction Prediction

- [Hybrid Quantum Neural Network for Drug Response Prediction](https://www.mdpi.com/2072-6694/15/10/2705) - Hybrid QNN for predicting drug response from cell line and chemical inputs. (Cancers, 2023)
- [Quantum Machine Learning Predicting ADME-Tox Properties in Drug Discovery](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01079) - QML models for ADMET property prediction, a key drug discovery bottleneck. (J. Chem. Inf. Model., 2023)
- [Robust quantum reservoir computing for molecular property prediction](https://arxiv.org/abs/2412.06758) - Quantum reservoir computing for predicting biological activity from molecular descriptors. (arXiv, 2024)

## Drug Combination & Optimization

Quantum methods focused on combinatorial treatment strategies and constrained molecular optimization.

- [Q-Drug: A Framework to bring Drug Design into Quantum Space](https://arxiv.org/abs/2308.13171) - Deep learning combined with quantum annealing for molecular optimization. (arXiv, 2023)
- [Towards quantum computing for clinical trial design and optimization](https://arxiv.org/abs/2404.13113) - IBM and Cleveland Clinic perspective on quantum optimization for trial site selection and cohort identification. (Trends in Pharmacological Sciences, 2024)
- [Quantum-Aided Drug Design (QuADD)](https://polarisqb.com) - PolarisQB's D-Wave-based platform for constrained molecular optimization.

## Datasets & Benchmarks

### Drug Discovery Datasets (Commonly Used in QML)

- [BindingDB](https://www.bindingdb.org/bind/index.jsp) - Measured binding affinities for protein-ligand interactions; widely used for DTI benchmarks.
- [ChEMBL](https://www.ebi.ac.uk/chembl/) - Open bioactivity database for drug-like molecules and targets.
- [MoleculeNet](https://pubs.acs.org/doi/10.1021/acs.jcim.7b00577) - Benchmark suite of molecular ML datasets commonly used for property prediction. (J. Chem. Inf. Model., 2018)
- [RCSB Protein Data Bank (PDB)](https://www.rcsb.org/) - Structural biology database for protein targets and complexes.
- [Therapeutics Data Commons (TDC)](https://tdcommons.ai/) - ML-ready datasets and benchmarks spanning targets, molecules, and clinical outcomes. (NeurIPS, 2021)
- [ZINC](https://zinc.docking.org/) - Database of commercially available compounds for virtual screening.

### Quantum/Hybrid Benchmarks & Datasets

- [QMugs: Quantum Mechanical Properties of Drug-like Molecules](https://www.nature.com/articles/s41597-022-01870-w) - Large-scale dataset with DFT-calculated properties for drug-like molecules and molecular conformers. (Scientific Data, 2022)
- [A performance characterization of quantum generative models](https://arxiv.org/abs/2301.09363) - Benchmarking QCBM/QGAN variants useful for selecting architectures in molecular generation pipelines. (arXiv, 2023)

## Software & Tools

Frameworks, SDKs, and practical repositories for quantum drug discovery workflows.

### Quantum Chemistry & Simulation

- [InQuanto](https://www.quantinuum.com/products-solutions/inquanto) - Quantinuum's quantum computational chemistry platform for molecular simulation workflows.
- [OpenFermion](https://github.com/quantumlib/OpenFermion) - Google's library for compiling and analyzing quantum algorithms for chemistry.
- [PennyLane](https://pennylane.ai) - Xanadu's cross-platform library for differentiable quantum chemistry.
- [Qiskit Nature](https://github.com/Qiskit/qiskit-nature) - IBM's quantum chemistry module including ground-state, excited-state, and dipole calculations.
- [QURI SDK](https://github.com/QunaSys/quri-sdk) - QunaSys toolkit for gate-based quantum workflows with chemistry and algorithm modules.
- [Tangelo](https://github.com/goodchemistryco/Tangelo) - Quantum chemistry simulation toolkit originally created by Good Chemistry Company, now maintained by SandboxAQ.
- [TenCirChem](https://github.com/tencent-quantum-lab/tencirchem) - Tencent's efficient quantum chemistry simulation package built on TensorCircuit.
- [TEQUILA](https://github.com/tequilahub/tequila) - Open-source framework for rapid development of variational quantum algorithms with chemistry applications (Aspuru-Guzik group).

### SDKs, Frameworks, and Annealing Toolchains

- [Amazon Braket SDK](https://github.com/amazon-braket/amazon-braket-sdk-python) - AWS SDK for quantum computing across multiple hardware backends.
- [Cirq](https://github.com/quantumlib/Cirq) - Google's framework for NISQ circuits.
- [CUDA-Q](https://github.com/NVIDIA/cuda-quantum) - NVIDIA's open-source platform for hybrid quantum-classical application development.
- [D-Wave Ocean SDK](https://github.com/dwavesystems/dwave-ocean-sdk) - Tools for quantum annealing optimization problems.
- [dimod](https://github.com/dwavesystems/dimod) - Shared API for Ising and QUBO models.
- [Qiskit](https://github.com/Qiskit/qiskit) - IBM's comprehensive quantum computing SDK.
- [Qiskit Machine Learning](https://github.com/qiskit-community/qiskit-machine-learning) - Qiskit add-on for quantum kernels, QNNs, and hybrid ML workflows.

### End-to-End Drug Discovery Repositories

- [AWS Quantum Computing Exploration for Drug Discovery](https://github.com/awslabs/quantum-computing-exploration-for-drug-discovery-on-aws) - Notebooks for molecular unfolding (QUBO), RNA folding, protein folding (VQE, Grover), and retrosynthetic planning.
- [Quantum-ML-Drug-discovery](https://github.com/Pratik25priyanshu20/Quantum-ML-Drug-discovery) - Tutorial repository demonstrating QML approaches for drug discovery.
- [QuPepFold](https://github.com/qupepfold/qupepfold) - Python package for CVaR-VQE peptide folding simulations with hardware-agnostic design.

## Learning Resources

Educational materials and hands-on tutorials for getting started quickly.

### Tutorials & Workshops

- [Qiskit Textbook - Quantum Chemistry](https://qiskit.org/textbook/ch-applications/vqe-molecules.html) - VQE for molecular ground states.
- [PennyLane Quantum Chemistry Demos](https://pennylane.ai/qml/demos_quantum-chemistry.html) - Interactive tutorials on quantum chemistry algorithms.
- [AWS Quantum Drug Discovery Workshop](https://awslabs.github.io/quantum-computing-exploration-for-drug-discovery-on-aws/en/workshop/) - Hands-on notebooks covering molecular unfolding, protein folding, and retrosynthetic planning.
- [NVIDIA CUDA-Q: Molecular docking via DC-QAOA](https://nvidia.github.io/cuda-quantum/latest/applications/python/digitized_counterdiabatic_qaoa.html) - Tutorial implementing DC-QAOA docking (based on [arXiv:2308.04098](https://arxiv.org/abs/2308.04098)).
- [MATLAB Protein Folding VQE Example](https://www.mathworks.com/help/matlab/math/ground-state-protein-folding-using-variational-quantum-eigensolver-vqe.html) - Step-by-step VQE implementation for neuropeptide folding.

## Quantum Hardware Platforms

Hardware providers with relevance to molecular simulation and drug discovery workflows.

### Gate-Based Quantum Computers

- [Google Quantum AI](https://quantumai.google/) - Superconducting processors; partner collaborations include Boehringer Ingelheim.
- [IBM Quantum](https://www.ibm.com/quantum) - Superconducting quantum processors; pharma collaborations include Cleveland Clinic (Discovery Accelerator) and Moderna (mRNA design).
- [IonQ](https://ionq.com/) - Trapped-ion quantum computers available via Amazon Braket and Azure Quantum.
- [Quantinuum](https://www.quantinuum.com/) - H-Series trapped-ion systems with high fidelity; Microsoft partnership demonstrated 12 logical qubits for chemistry (2024).
- [Rigetti](https://www.rigetti.com/) - Superconducting quantum processors available via Rigetti QCS and Amazon Braket.

### Photonic Quantum Computers

- [PsiQuantum](https://www.psiquantum.com/) - Photonic quantum computing; pharma collaborations include Boehringer Ingelheim (CYP450 simulation).
- [Xanadu](https://www.xanadu.ai/) - Photonic quantum computing; creators of PennyLane and Strawberry Fields, with applications including Gaussian Boson Sampling.

### Quantum Annealers

- [D-Wave](https://www.dwavequantum.com/) - 5000+ qubit annealing systems used in molecular docking and constrained optimization.

### Neutral-Atom Quantum Computers

- [PASQAL](https://www.pasqal.com/) - Neutral-atom processors; partner collaborations include Qubit Pharmaceuticals.
- [QuEra Computing](https://www.quera.com/) - Neutral-atom systems with collaborations including Merck KGaA and Amgen.

## Biochemical Quantum Hardware

Biomolecular systems as quantum computing platforms.

- [Peptides as Versatile Platforms for Quantum Computing](https://pubs.acs.org/doi/abs/10.1021/acs.jpclett.8b01813) - Lanthanide-binding peptide tags as molecular qubits demonstrating coherent oscillations via pulsed EPR. (J. Phys. Chem. Lett., 2018)

## Companies & Startups

Organizations building products and services at the intersection of quantum computing and drug discovery.

### Quantum-Native Drug Discovery & Platform Companies

- [Algorithmiq](https://algorithmiq.fi/) (Finland) - Aurora platform with IBM partnership, quantum network medicine focus, and Cleveland Clinic cancer drug collaboration.
- [Aqemia](https://www.aqemia.com/) (France) - Quantum-inspired statistical mechanics for affinity prediction.
- [Kuano](https://kuano.ai/) (UK) - Quantum machine learning for molecular discovery.
- [Menten AI](https://www.menten.ai/) (USA/Canada) - Quantum-enhanced peptide and protein design.
- [Phasecraft](https://www.phasecraft.io/) (UK) - Quantum algorithms for drug discovery; Wellcome Leap Q4Bio covalent inhibitor project with University of Nottingham and QuEra.
- [Polaris Quantum Biotech (PolarisQB)](https://polarisqb.com/) (USA) - QuADD platform on D-Wave for lead identification and constrained molecular optimization.
- [ProteinQure](https://www.proteinqure.com/) (Canada) - Peptide drug discovery with long-term quantum R&D focus.
- [QC Ware](https://qcware.com/) (USA) - Promethium quantum chemistry SaaS platform; partnerships include Merck KGaA and NVIDIA Quantum Cloud integration.
- [QSimulate](https://qsimulate.com/) (USA) - Ab initio quantum simulation for drug discovery.
- [Qubit Pharmaceuticals](https://www.qubit-pharmaceuticals.com/) (France/USA) - Atlas platform combining HPC simulation with quantum algorithms; WEF Technology Pioneer 2024.
- [SandboxAQ](https://www.sandboxaq.com/) (USA) - Developer of Tangelo and AQChemSim (formerly QEMIST Cloud); collaborations include AstraZeneca and Sanofi.
- [XtalPi](https://www.xtalpi.com/) (China/USA) - ID4 platform combining quantum mechanics and AI; partnerships include Pfizer.

### Quantum Software Providers with Pharma Engagement

- [1QBit](https://1qbit.com/) (Canada) - Quantum software provider; pharma partnership history includes Biogen (via Accenture).
- [HQS Quantum Simulations](https://quantumsimulations.de/) (Germany) - Quantum chemistry software; three-year partnership with Merck KGaA for drug screening and molecular property prediction.
- [QunaSys](https://qunasys.com/news/posts/quenais_e/) (Japan) - Quantum chemistry software company and lead coordinator of the QuEnAIS quantum-AI drug discovery consortium.

## Contributing

Contributions welcome! Please read our [contribution guidelines](CONTRIBUTING.md) first.

When adding new resources:
- Include publication year and source
- Provide brief description of the quantum method used
- Link to papers, code repositories, or official documentation
- Verify links are accessible

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

---

*Curated by [Mark Fingerhuth](https://markfingerhuth.ai), passionate about the intersection of quantum computing and drug discovery. For the latest in open-source quantum software more broadly, see [Awesome Quantum Software](https://github.com/qosf/awesome-quantum-software).*
