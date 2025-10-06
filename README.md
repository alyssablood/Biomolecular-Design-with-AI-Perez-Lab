# Perez-Lab-Intro-Tutorials
This repo contains all the information needed to get started in Dr. Perez's lab, including sections on AutoDock, Chimera, VMD, BindCraft, AMBER, RFDiffusion, ProteinMPNN, AlphaFold2 and AlphaFold3.

1. [Introduction & Background](https://github.com/alyssablood/Perez-Lab-Intro-Tutorials/blob/main/Chapter%201)

    - AI and structures: from games to molecules
    - The protein folding problem & the CASP competition
2. [Core Technical Foundations](2. Core Technical Foundations)

    - Python/Colab notebooks for running AI pipelines
    - Introduction to HiPerGator for scalable computing
3. Protein Structure Prediction

    - AlphaFold, RoseTTAFold, MSEFold
    - Case studies using the Protein Data Bank
    - Transformer proteins and memorization issues
4. Protein Design

    - Hallucination and move 37
    - RFdiffusion and ProteinMPNN
    - BindCraft and other emerging methods
    - Applications in miniproteins, peptides, and enzyme design
5. Protein Interactions

    - AlphaFold competitive binding assays (AF-CBA)
    - Modeling interactomes and selectivity
6. Protein Dynamics

    - Beyond static folds: ensembles and motion
    - BioEMU and AI for conformational states
7. Applications & Frontiers

    - Drug discovery, synthetic biology, enzyme design
    - Limitations, reproducibility, FAIR practices (Findable, Accessible, Interoperable, 
Reproducible)
8. Community Challenges: unbiased assessment of methods

    - CASP: protein structure prediction
    - CAPRI: protein-protein structure prediction
    - RNA Puzzles: RNA structure prediction
    - BioML Challenge: Bits to binders : designing miniproteins to target cancer cells
    - Align Bio: 2025 PETase Tournament
    - iGEM projects on campus


**Visualization**

Chimera: Best for generating final graphics for presentations, models alpha helix versus beta pleats.

VMD: Best for modeling multiple docking poses and animating mechamisms. Many options for color/shape of models.

**Docking Poses (not mechanism)**

AMBER: Uses physics-based (p-chem) methods to apply force fields (vector equations) to molecules in order to predict folding, docking, and general behavior. Good for very specific results, binding energy and other outputs are considered reliable.

AutoDock: Predicts how ligand and protein interact, and what binding conformation would occur. P-chem methods are NOT used, therefore specific numbers are considered unreliable. Good for preliminary testing to get shape and quantity of docked poses.

**Protein Design**

BindCraft: Good for desiging a new binder custom fit to a target protein. It is generally very accurate, but follows strict garbage in garbage out policy. Input protein must be high accuracy, and runs take a relatively long time. link iGEM

ProteinMPNN: Optimizes amino acid sequences for most stable protein backbones. Good for designing new target proteins.

RFDiffusion: Generates new protein backbones using diffusion models. Adds in noise to allow for flexibility in folding. Results MUST be checked carefully. It is very easy to add too much noise and generate garbage outputs.

**Protein Folding**

AlphaFold2: Extremely popular tool for deriving a 3D structure from an amino acid sequence. Very high accuracy, industry standard. link baker paper

AlphaFold3: Expansion of AlphaFold2 that also analyzes interacions between molecules. Program won 2024 Nobel Prize in Chemistry. link baker paper

To do:
- flow chart showing how to decide which software to use
- folders for each software w/ explanations and instructions
- remember: dont just explain how to use it, explain the big picture and how it works
