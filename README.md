# Awesome RTL Security Repair

A companion repository for our review on automated RTL security defect repair:

**Large Language Models for RTL Security Defect Repair: Localization, Patch Generation, and Trustworthy Validation**

## Overview

This repository accompanies our review of automated RTL security defect repair at the intersection of hardware security, electronic design automation (EDA), and large language models (LLMs).

The review is organized around four closely connected stages:

1. **RTL Security Defect Localization**  
   Identifying repair-relevant defect locations, root causes, and security semantics in RTL designs.

2. **LLM-Driven RTL Repair**  
   Generating and refining RTL patches using LLMs, retrieval-augmented generation, agentic workflows, and neural-symbolic techniques.

3. **Trustworthy Validation**  
   Evaluating repaired RTL through compilation, simulation, regression testing, security-property checking, formal verification, and equivalence checking.

4. **Validation-Guided Re-repair**  
   Using structured validation-failure evidence to guide subsequent repair attempts and support closed-loop automated RTL security repair.

## Literature Scope

The current review analyzes four thematic evidence pools:

- **16** existing surveys
- **37** studies related to RTL security defect localization
- **60** studies related to RTL repair
- **43** studies related to trustworthy RTL validation

These thematic collections may overlap and therefore should not be interpreted as the number of unique publications in the final review corpus.

## Research Perspective

The central perspective of this review is to connect:

**Localization → Repair → Trustworthy Validation → Feedback → Re-repair**

rather than treating defect localization, patch generation, and verification as isolated research tasks.

Particular attention is given to:

- repair-oriented semantic localization;
- security-aware RTL patch generation;
- verifier- and tool-guided LLM repair;
- functional and security preservation;
- formal and equivalence evidence;
- verifier and oracle qualification;
- structured failure feedback for iterative re-repair.

## Repository Status

This repository is maintained alongside the preparation of the review manuscript. Additional literature information, taxonomy tables, and supplementary materials may be added as the review is updated.

## Citation

Citation information will be added after publication of the review.

## Contact

For questions or suggestions regarding this repository, please open an issue on GitHub.
