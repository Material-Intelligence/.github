# Material Intelligence

Computational materials design: first-principles calculations, machine-learning interatomic potentials, interpretable descriptors, and LLM-agent workflows.

Founded and led by [Jiahao Xie](https://github.com/xiejiahao).

## Research lines

| Line | What we build |
|---|---|
| **Interpretable descriptors** | Physically constrained symbolic regression (SISSO++) with nested out-of-sample validation |
| **ML potentials for hybrid perovskites** | Fine-tuned interatomic potentials for molecule–perovskite interfaces and structure optimisation |
| **Excited states in metal halides** | Automated computational discovery of self-trapped-exciton emitters in zero-dimensional metal halides |
| **Knowledge engineering** | A literature-grounded knowledge base and ontology for materials design, with LLM-assisted screening |
| **AI for physics** | DerivationLab — an LLM-agent system for step-level physics derivations |

## Open-source releases

| Repository | What it does | Licence |
|---|---|---|
| [elf-anisotropy-sisso](https://github.com/Material-Intelligence/elf-anisotropy-sisso) | Command-line ELF anisotropy descriptor from a VASP `ELFCAR`, plus the SISSO++ candidate-search and nested leave-one-material-out validation workflow for 2D Sn/Pb iodide perovskites | MIT |
| [derivationlab](https://github.com/Material-Intelligence/derivationlab) | DerivationLab: hash-chained records of machine-checked physics derivations — the derivation runtime, service and web UI, plus a stdlib-only offline verifier and viewer with example records | Apache-2.0 |
| [materials-discovery-skills](https://github.com/Material-Intelligence/materials-discovery-skills) | `matdisc`: an agent-drivable workflow for generative structure design, MLIP prescreening and DFT validation of inorganic semiconductors, packaged as seven agent skills (from arXiv:2606.10251) | MIT |
| [perovskite-adsorption-sampler](https://github.com/Material-Intelligence/perovskite-adsorption-sampler) | Adsorbate-placement samplers for Pb–I terminated perovskite surfaces on top of FAIRChem, with a resumable MLP-to-DFT screening workflow and a CPU-only example | MIT |

## Contact

Jiahao Xie · [Google Scholar](https://scholar.google.com/citations?user=kZua6cMAAAAJ) · xiejh.mail@gmail.com
