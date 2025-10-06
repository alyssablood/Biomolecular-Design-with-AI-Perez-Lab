# Perez-Lab-Intro-Tutorials
This repo contains all the information needed to get started in Dr. Perez's lab, including sections on AutoDock, Chimera, VMD, BindCraft, AMBER, RFDiffusion, ProteinMPNN, AlphaFold2 and AlphaFold3.


**Visualization**

Chimera: Best for generating final graphics for presentations, models alpha helix versus beta pleats.

VMD: Best for modeling multiple docking poses and animating mechamisms. Many options for color/shape of models.

**Docking Poses (not mechanism)**

AMBER: Uses physics-based (p-chem) methods to apply force fields (vector equations) to molecules in order to predict folding, docking, and general behavior. Good for very specific results, binding energy and other outputs are considered reliable.

AutoDock: Predicts how ligand and protein interact, and what binding conformation would occur. P-chem methods are NOT used, therefore specific numbers are considered unreliable. Good for preliminary testing to get shape and quantity of docked poses.

**Protein Design**

BindCraft: Good for desiging a new binder custom fit to a target protein. It is generally very accurate, but follows strict garbage in garbage out policy. Input protein must be high accuracy, and runs take a relatively long time. link iGEM

ProteinMPNN: Optimizes amino acid sequences for most stable protein backbones. Good for designing new target proteins.

RFDiffusion: Generates new protein backbones using diffusion models. Adds in noise to allow for flexibility in structure. Results MUST be checked carefully. It is very easy to add too much noise and generate garbage outputs.

**Protein Folding**

AlphaFold2:

AlphaFold3:


To do:
- flow chart showing how to decide which software to use
- folders for each software w/ explanations and instructions
- remember: dont just explain how to use it, explain the big picture and how it works
