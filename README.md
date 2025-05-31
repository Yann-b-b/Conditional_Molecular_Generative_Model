# Conditional_Molecule_Generative_Model

This project focuses on generating small molecules conditioned on target physicochemical properties using a contrastive alignment model with a SELF-BART architecture.

## Conditional_Molecule_Generative_Model

This repository contains the code and resources for a final project exploring the use of contrastive learning to align molecular structures and properties for conditional generation. The goal is to generate chemically valid molecular sequences (SELFIES) that match desired properties such as LogP, molecular weight, and polar surface area.

## Project Overview

We integrate a pretrained molecular sequence model (SELF-BART) with a contrastive property encoder. The model maps both molecules and property vectors to a shared latent space, allowing controlled generation through property-conditioned decoding.

## Key Components

- Molecular dataset preparation and SELFIES conversion
- Embedding generation using pretrained SELF-BART encoder
- Contrastive training between molecule and property vectors
- Conditional decoding using the SELF-BART decoder
- Evaluation of generated molecules (validity, novelty, property alignment)

## Applications

This work supports de novo molecular design for applications in drug discovery and materials science.

## References

Key references include SELFIES (Krenn et al., 2020), DrugDiff (Oestreich et al., 2025), MolGPT (Bagal et al., 2021), and ImageBind (Girdhar et al., 2023).