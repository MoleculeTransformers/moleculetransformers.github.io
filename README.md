# Molecule Transformers
Molecule Transformers is a collection of recipes for pre-training and fine-tuning molecular transformer language models, including BART, BERT, etc. This project contains the following modules:

### [1. Enumeration-aware Molecular Transformers](https://github.com/MoleculeTransformers/enumeration-aware-molecule-transformers)
Introduces contrastive learning alongside multi-task regression, and masked language modelling as pre-training objectives to inject enumeration knowledge into pre-trained language models.
#### Molecular Domain Adaptation (Contrastive Encoder-based)
##### Architecture
![smole bert drawio](https://user-images.githubusercontent.com/6007894/233776921-41667331-1ab7-413c-92f7-4e6fad512f5c.svg)
##### Contrastive Learning
<img width="1418" alt="Screenshot 2023-04-22 at 11 54 23 AM" src="https://user-images.githubusercontent.com/6007894/233777069-439c18cc-77a2-4ae2-a81e-d7e94c30a6be.png">

#### Canonicalization Encoder-decoder (Denoising Encoder-decoder)
<img width="702" alt="Screenshot 2023-04-22 at 11 43 06 AM" src="https://user-images.githubusercontent.com/6007894/233776512-ab6cdeef-02f1-4076-9b76-b228cbf26456.png">

### [2. Fine-tuning on low-data via Semi-supervised Learning](https://github.com/MoleculeTransformers/moleculenet-bert-ssl)
Replacing fully supervised fine-tuning of molecular language models with semi-supervised learning methods including pseudo-label, and deep co-training to generalize language models in low-data scenarios.

### [3. SMILES Featurizers](https://github.com/MoleculeTransformers/smiles-featurizers)
Allows to get neural fingerprints from pre-trained language models for training downstream ML models.

### [4. RDKit Virtual Screening Benchmarking Platform for Transformers](https://github.com/MoleculeTransformers/rdkit-benchmarking-platform-transformers)
Port of the [RDKit Virtual Screening Platform](https://github.com/rdkit/benchmarking_platform) to work with pre-trained transformer-based language models.

### [5. SMILES Augment](https://github.com/MoleculeTransformers/smiles-augment)
Provides different stochastic and interpolation oriented SMILES augmentation mechanisms to augment SMILES-based training datasets.
