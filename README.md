# Chi-Guide: Towards Controllable Antibody Design via Torsion Angle Diffusion and Property Guidance

Chi-Guide is a diffusion-based framework for antigen-specific antibody CDR design that incorporates explicit side-chain torsion angle ($\chi$-angle) representation and classifier guidance for controllable generation.

---

## Overview

Existing backbone-level diffusion models for antibody design discard side-chain information during generation, limiting both structural quality and the ability to apply gradient-based property guidance. Chi-Guide addresses this by jointly diffusing backbone geometry and side-chain torsion angles ($\chi_1$–$\chi_4$), providing differentiable atomic coordinates at every denoising step. A lightweight classifier trained on noisy intermediate states steers sampling toward improved binding affinity without modifying the base generative model.

![method](method.png)

---

---

## CDR Design Example

Representative CDR design on the SARS-CoV-2 RBD complex (PDB: 7CHB). Reference structures are shown in red and Chi-Guide designs in cyan for all six CDR loops, with substituted residues highlighted.

![design](c7.5g40.png)

---

## Code Availability

The code and pretrained models will be made publicly available upon acceptance.

---

## License

This project will be released under the MIT License.
