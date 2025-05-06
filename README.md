# Conditional_Protein_Generative_Model

This Project focuses on creating a diffusion model that is conditioned on protein attributes for generation.
# Conditional_Protein_Generative_Model

This repository contains the code and resources for a final project exploring the use of conditional diffusion models for protein sequence generation. The goal is to generate protein sequences that are conditioned on specific biochemical properties such as solubility, stability, or binding affinity.

## Project Overview

We aim to integrate a pretrained protein language model (e.g., ESM-2) with a conditional diffusion model. The pipeline embeds protein sequences into a latent space and uses a property vector to guide the diffusion-based sampling process. The generated latent vectors are then decoded back into protein representations such as amino acid sequences or SMILES strings.

## Key Components

- Protein dataset preparation and preprocessing
- Embedding generation using pretrained models
- Conditional latent diffusion model architecture and training
- Decoding from latent space to protein representations
- Evaluation of generated sequences (validity, novelty, property alignment)

## Applications

This work supports controlled protein design for use in drug discovery, biosensors, and synthetic biology.

## References

Key references include PepVAE (Dean et al., 2021), ProteinGAN (Repecka et al., 2021), AMP-Diffusion (Chen et al., 2024), and Guided Discrete Diffusion (Gruver et al., 2023).