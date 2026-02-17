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
- [Industry Partnerships & Consortia](#industry-partnerships--consortia)
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
- [A Perspective on Protein Structure Prediction Using Quantum Computers](https://pubs.acs.org/doi/full/10.1021/acs.jctc.4c00067) - IBM Quantum perspective on selecting protein structure problems amenable to quantum advantage, with proof-of-concept on Zika Virus NS3 Helicase. (J. Chem. Theory Comput., 2024)
- [Quantum biological convergence: quantum computing accelerates KRAS inhibitor design](https://www.nature.com/articles/s41392-025-02239-2) - Commentary on the KRAS breakthrough highlighting QCBMs for navigating chemical space. (Signal Transduction and Targeted Therapy, 2025)
- [Quantum Machine Learning in Drug Discovery: Applications in Academia and Pharmaceutical Industries](https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00678) - Review of QNNs on gate-based quantum computers for property prediction and molecular generation. (Chemical Reviews, 2025)
- [Quantum Computing in Drug Discovery: Techniques, Challenges, and Emerging Opportunities](https://pubmed.ncbi.nlm.nih.gov/40873222/) - Overview of quantum techniques, current challenges, and emerging opportunities in pharmaceutical applications. (Current Drug Discovery Technologies, 2025)
- [Quantum intelligence in drug discovery: Advancing insights with quantum machine learning](https://www.sciencedirect.com/science/article/abs/pii/S135964462500176X) - Review of QML applications including property prediction, docking simulations, and de novo design. (Drug Discovery Today, 2025)
- [Prioritizing quantum computing use cases in the drug discovery and development pipeline](https://www.sciencedirect.com/science/article/pii/S1359644625000364) - Industry perspective on prioritizing QC applications across the drug development pipeline. (Drug Discovery Today, 2025)

### Industry Perspectives

- [BCG Survey](https://www.bcg.com/publications/2023/quantum-computing-will-transform-pharma) - 8 of top 10 biopharma companies piloting quantum projects. (BCG, 2023)
- [McKinsey: The quantum revolution in pharma](https://www.mckinsey.com/industries/life-sciences/our-insights/the-quantum-revolution-in-pharma-faster-smarter-and-more-precise) - Strategic overview of quantum opportunities in life sciences. (McKinsey, 2025)

## Quantum Chemistry & Molecular Simulation

Quantum approaches for accurate molecular energy calculations, excited-state simulation, and hybrid workflows.

### Electronic Structure & Accuracy

- [High-Quality Protein Force Fields with Noisy Quantum Processors](https://arxiv.org/abs/1907.07128) - Resource estimates and workflow for improving biomolecular force fields via quantum chemistry. (arXiv, 2019)
- [Quantum chemical simulations of excited states](https://arxiv.org/abs/2109.02110) - Methods for computing excited electronic states relevant to photopharmacology. (arXiv, 2021)
- [Reliably assessing the electronic structure of cytochrome P450 on today's classical computers and tomorrow's quantum computers](https://arxiv.org/abs/2202.01244) - Boehringer Ingelheim, Google, and QSimulate CYP450 benchmark introducing BLISS+THC for quantum resource reduction. (npj Quantum Information, 2022)
- [Drug design on quantum computers](https://www.nature.com/articles/s41567-024-02411-5) - Comprehensive study on quantum methods for drug-relevant molecular simulations. (Nature Physics, 2024)
- [Shortcut to chemically accurate quantum computing via density-based basis-set correction](https://www.nature.com/articles/s41467-024-46566-4) - Qubit Pharmaceuticals and Sorbonne University method reducing qubit requirements for molecular simulation. (Nature Communications, 2024)
- [Faster Quantum Chemistry Simulations on a Quantum Computer with Improved Tensor Factorization and Active Volume Compilation](https://arxiv.org/abs/2501.06165) - PsiQuantum and Boehringer Ingelheim report 234x speedup for CYP450 and 278x for FeMoco using Active Volume compilation. (PRX Quantum, 2025)
- [Challenges and Advances in the Simulation of Targeted Covalent Inhibitors Using Quantum Computing](https://pubs.acs.org/doi/10.1021/acs.jpclett.5c01680) - Review of QM/MM scoring functions, warhead reactivity, and quantum computing opportunities for covalent drugs. (J. Phys. Chem. Lett., 2025)

### Free Energy, Solvation & Hybrid Pipelines

- [Solvent configuration prediction using quantum computing](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.6.043020) - PASQAL collaboration on protein hydration analysis using neutral-atom quantum computers. (Phys. Rev. Research, 2024)
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
- [Quantum Approximate Optimization Algorithms for Molecular Docking](https://arxiv.org/abs/2503.04239) - Pfizer-led research mapping docking to maximum vertex weight clique, solved with QAOA and DC-QAOA. (arXiv, 2025)
- [Quantum algorithm for protein-ligand docking sites identification](https://link.springer.com/article/10.1007/s10822-025-00620-5) - Grover-based algorithm for binding site identification, validated on IBM quantum hardware. (J. Comput. Aided Mol. Des., 2025)

### Annealing & Screening Workflows

- [Molecular unfolding formulation with enhanced quantum annealing](https://arxiv.org/abs/2403.00507) - D-Wave implementation for molecular unfolding in geometric docking, showing 42.5% mean speedup over classical GeoDock. (arXiv, 2024)
- [Quantum Algorithm for Structure-Based Virtual Drug Screening Using Classical Force Fields](https://arxiv.org/abs/2505.07876) - Uses qubits to evaluate many ligand configurations in superposition while computing binding energies from classical force-field terms. (arXiv, 2025)

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
- [QuPepFold: A Python package for hybrid quantum-classical protein folding simulations](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0342012) - Modular package targeting intrinsically disordered regions on Qiskit Aer, Amazon Braket, and IonQ Aria-1. (PLOS ONE, 2025)
- [Capturing Protein Free Energy Landscape using Efficient Quantum Encoding](https://arxiv.org/abs/2510.15316) - FCC lattice encoding with Miyazawa-Jernigan potential, validated on IBM 133-qubit hardware. (arXiv, 2025)
- [Quantum-Enabled Protein Folding of Disordered Regions in Ubiquitin C](https://ieeexplore.ieee.org/document/11130538/) - Error-mitigated VQE for Ubiquitin C terminal region folding. (IEEE, 2025)

## Peptide & Antibody Design

Quantum methods specifically targeting biologics discovery.

- [Quantum computing for protein design](https://arxiv.org/pdf/2105.09690.pdf) - Approaches for computational protein and peptide engineering.
- [Quantum algorithms for antimicrobial peptides](https://arxiv.org/abs/2401.03994) - Includes membrane environmental effects without additional qubits.
- [De Novo Design of Protein-Binding Peptides by Quantum Computing](https://pubs.acs.org/doi/10.1021/acs.jctc.5c00768) - Multiscale framework combining D-Wave quantum annealer with classical atomistic docking for peptide design. (J. Chem. Theory Comput., 2025)

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
- [Quantum-computing-enhanced algorithm unveils potential KRAS inhibitors](https://www.nature.com/articles/s41587-024-02526-3) - First experimentally validated quantum drug discovery study; hybrid QCBM-LSTM screened 1M+ molecules and identified active KRAS binders. (Nature Biotechnology, 2025)
- [Bridging Quantum and Classical Computing in Drug Design: Architecture Principles for Improved Molecule Generation](https://arxiv.org/abs/2506.01177) - Empirical architecture guidelines for hybrid quantum-classical molecular GANs via Bayesian optimization. (arXiv, 2025)
- [QCA-MolGAN: Quantum Circuit Associative Molecular GAN with Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2509.05051) - QCBM-enabled GAN with multi-agent RL to steer QED/LogP/SA objectives for drug-like molecules. (arXiv, 2025)

### Property, Activity, and Interaction Prediction

- [Quantum machine learning algorithms for drug discovery applications](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.1c00166) - Benchmark study using SVM and data reuploading classifier on SARS-CoV-2 and TB datasets. (J. Chem. Inf. Model., 2021)
- [Hybrid Quantum Neural Network for Drug Response Prediction](https://www.mdpi.com/2072-6694/15/10/2705) - Hybrid QNN for predicting drug response from cell line and chemical inputs. (Cancers, 2023)
- [Quantum Machine Learning Predicting ADME-Tox Properties in Drug Discovery](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01079) - QML models for ADMET property prediction, a key drug discovery bottleneck. (J. Chem. Inf. Model., 2023)
- [Robust quantum reservoir computing for molecular property prediction](https://arxiv.org/abs/2412.06758) - Quantum reservoir computing for predicting biological activity from molecular descriptors. (arXiv, 2024)
- [QKDTI: A quantum kernel based machine learning model for drug target interaction prediction](https://www.nature.com/articles/s41598-025-07303-z) - Quantum-kernel SVR approach evaluated on DAVIS and KIBA, validated on BindingDB. (Scientific Reports, 2025)
- [Q2SAR: A Quantum Multiple Kernel Learning Approach for Drug Discovery](https://arxiv.org/abs/2506.14920) - Quantum multiple-kernel learning for QSAR classification (DYRK1A inhibitors). (arXiv, 2025)

## Drug Combination & Optimization

Quantum methods focused on combinatorial treatment strategies and constrained molecular optimization.

- [Q-Drug: A Framework to bring Drug Design into Quantum Space](https://arxiv.org/abs/2308.13171) - Deep learning combined with quantum annealing for molecular optimization. (arXiv, 2023)
- [Towards quantum computing for clinical trial design and optimization](https://arxiv.org/abs/2404.13113) - IBM and Cleveland Clinic perspective on quantum optimization for trial site selection and cohort identification. (Trends in Pharmacological Sciences, 2024)
- [Network-based prediction of drug combinations with quantum annealing](https://arxiv.org/abs/2512.20199) - QUBO formulation using network medicine's complementary exposure principle for combination therapy discovery. (arXiv, 2025)
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
- [QDockBank: A Dataset for Ligand Docking on Protein Fragments Predicted on Utility-Level Quantum Computers](https://arxiv.org/abs/2508.00837) - Protein-fragment structures for docking benchmarks generated via superconducting quantum processors. (arXiv, 2025)

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

## Industry Partnerships & Consortia

Collaborative initiatives advancing quantum drug discovery.

- **IBM Quantum Network** - Includes Cleveland Clinic (Discovery Accelerator), Moderna, and multiple pharma partners.
- **QIDO** - Quantum-Integrated Discovery Orchestrator platform by Mitsui, QSimulate, and Quantinuum for drug and materials discovery; beta tested by Chugai Pharmaceutical (2025).
- [QuEnAIS](https://qunasys.com/news/posts/quenais_e/) - Quantum-AI drug discovery consortium led by QunaSys.
- **QuPharm** - Alliance of pharmaceutical companies developing quantum computing solutions for drug discovery.

### Funding Commitments

- **Novo Holdings** - DKK 1.4 billion (~€188M) commitment to quantum computing in life sciences, with portfolio including Phasecraft and Sparrow Quantum (2024).

### Pharma Companies with Quantum Programs

- **Amgen** - QuEra collaboration for molecular property prediction.
- **AstraZeneca** - SandboxAQ and Riverlane partnerships.
- **Biogen** - 1QBit/Accenture quantum molecular comparison validation.
- **Boehringer Ingelheim** - Collaborations with Google Quantum AI and PsiQuantum (CYP450 simulation); studies including quantum chemistry for metalloenzymes.
- **Johnson & Johnson** - Patent filings and quantum research programs.
- **Merck KGaA** - Multiple initiatives including SEEQC consortium, QC Ware partnership, and QuEra collaboration.
- **Moderna** - IBM collaboration for mRNA medicine design.
- **Pfizer** - Quantum algorithm development for molecular docking and simulation.
- **Roche** - Internal quantum research programs and startup collaborations.
- **Sanofi** - SandboxAQ partnership for molecular simulation and AI-driven biomarker identification in clinical development (2024).

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
