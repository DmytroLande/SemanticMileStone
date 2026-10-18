
# SMF-MAP — Supplementary Materials

## Semantic Milestones and the SMF-MAP Multi-Agent Framework

**Author:** Dmytro Lande  
**Affiliation:** National Technical University of Ukraine "Igor Sikorsky Kyiv Polytechnic Institute"

**Repository:** https://github.com/DmytroLande/SemanticMileStone

## Overview

This directory contains supplementary research materials associated with the paper *Semantic Milestones and the SMF-MAP Multi-Agent Framework*.

The materials document the construction and analysis of semantic relationship datasets, classification decisions, controlled transformations, and the methodology used in the study.

The purpose of this collection is to support transparency, reproducibility, and further research on semantic milestones and their relationships.

## Supplementary Materials

| ID | Description |
|---|---|
| S1 | Primary corpus of 90 statement pairs covering nine semantic relationship classes |
| S2 | Internal model audit results for the primary corpus |
| S3 | Additional control corpus of 45 statement pairs and classification decisions |
| S4 | Results of 90 controlled semantic modifications |
| S5 | Paraphrase robustness analysis for 45 statement pairs |
| S6 | Rules and procedures for constructing controlled modifications |
| S7 | Disputed classification cases, editorial revisions, and methodological observations |

## Semantic Relationship Taxonomy

SMF-MAP distinguishes nine semantic relationship classes:

1. `CONTRADICTION` — mutually incompatible statements under identical conditions.
2. `COUNTEREXAMPLE` — a specific case refuting a general statement.
3. `EQUIVALENCE` — bidirectional logical entailment.
4. `ENTAILMENT` — unidirectional logical entailment.
5. `CONTEXT_DEPENDENT` — relationships determined by contextual differences.
6. `TRADE_OFF` — competing objectives involving a limited shared resource.
7. `TENSION` — opposing tendencies without a demonstrated necessary resource trade-off.
8. `COMPLEMENT` — compatible statements describing different aspects of a phenomenon.
9. `UNRELATED` — no significant established semantic relationship.

When the available information is insufficient, the framework permits the classification outcome `NEEDS_CONTEXT`.

## Evaluation Metrics

The study considers four metrics:

- **SPR (Semantic Preservation Rate):** proportion of meaning-preserving modifications for which the original classification is retained.
- **SCDR (Semantic Change Detection Rate):** proportion of meaning-changing modifications correctly identified through the expected classification.
- **FSR (False Stability Rate):** proportion of meaning-changing modifications incorrectly treated as preserving the original classification.
- **FIR (False Instability Rate):** proportion of meaning-preserving modifications incorrectly treated as changing the classification.

For the final controlled modification series:

- SPR: **97.8%** (44/45).
- SCDR: **80.0%** (36/45).

These values characterize the reported internal model audit and must not be interpreted as independently established performance metrics of a deployed multi-agent system.

## Methodological Limitations

The reported evaluation was conducted as a sequential, single-session model audit using author-constructed datasets.

The procedure did not constitute:

- Independent execution of all SMF-MAP agents.
- Blind evaluation by external experts.
- A comparison with independently implemented baseline systems.
- Experimental validation of a fully deployed multi-agent architecture.

The datasets and associated records are provided to make the reported procedures inspectable and to facilitate future independent validation.

## SMF-MAP Framework

The English specification of the framework is available here:

[SMF-MAP Framework — English, v1.1](../Framework/SMF_MAP_v1_1.md)

## Research Article

The associated scientific article is available in the repository:

[Semantic Milestones and the SMF-MAP Multi-Agent Framework](../Article/)

## Reproducibility

Researchers may use the supplementary materials to:

- Examine the operational definitions of semantic relationships.
- Review classification decisions and disputed cases.
- Reproduce the controlled modification procedures.
- Evaluate classification robustness using independent models.
- Compare single-model and multi-agent implementations.
- Develop extended benchmark datasets.

Reproduction of the reported results requires documenting model versions, prompts, execution settings, dataset versions, and evaluation procedures.

## Data Availability

The supplementary datasets and methodological materials are publicly available in this repository.

Some original research records are preserved in Ukrainian to maintain consistency with the source materials.

## Funding

This research received no external funding.

## Conflict of Interest

The author declares no known competing financial interests or personal relationships that could have influenced the research.

## Citation

When using these materials, please cite the associated paper:

Lande, D. *Semantic Milestones and the SMF-MAP Multi-Agent Framework*. Preprint.

Bibliographic details and a persistent identifier should be added after publication.

## Contact

**Dmytro Lande**  
Igor Sikorsky Kyiv Polytechnic Institute  
Email: dwlande@gmail.com
