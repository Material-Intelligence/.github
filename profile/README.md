# Material Intelligence

Computational materials design that is **auditable, not just fast**: first-principles calculations, machine-learning interatomic potentials, interpretable descriptors, and LLM-agent workflows whose steps are recorded and replayable.

Founded and led by [Jiahao Xie](https://github.com/xiejiahao).

## Research lines

| Line | What we build |
|---|---|
| **Interpretable descriptors** | Physically constrained symbolic regression (SISSO++) with nested out-of-sample validation |
| **ML potentials for hybrid perovskites** | Fine-tuned interatomic potentials for molecule–perovskite interfaces and structure optimisation |
| **Excited states in metal halides** | Automated computational discovery of self-trapped-exciton emitters in zero-dimensional metal halides |
| **Knowledge engineering** | A literature-grounded knowledge base and ontology for materials design, with LLM-assisted screening |
| **Auditable AI for physics** | DerivationLab — an LLM-agent system in which every derivation step is machine-checked and every model call, verdict, and human intervention is recorded, so a full derivation replays exactly |

## Open-source releases

| Repository | What it does | Licence |
|---|---|---|
| [elf-anisotropy-sisso](https://github.com/Material-Intelligence/elf-anisotropy-sisso) | Command-line ELF anisotropy descriptor from a VASP `ELFCAR`, plus the SISSO++ candidate-search and nested leave-one-material-out validation workflow for 2D Sn/Pb iodide perovskites | MIT |

Most repositories here are working research spaces and stay private while the associated manuscripts are in preparation. Public releases are exported as clean, citable snapshots (licence, `CITATION.cff`, runnable example, tests).

## How we work

Every project carries a provenance record, a data dictionary, a status file, and an issue-driven task list, so that a result can be traced back to the inputs and code that produced it.

## Contact

Jiahao Xie · [Google Scholar](https://scholar.google.com/citations?user=kZua6cMAAAAJ) · xiejh.mail@gmail.com
