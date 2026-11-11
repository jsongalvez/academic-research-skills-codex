---
name: literary-mt-experiment-design
description: Use to design or revise Literary MT Research pilots, model comparisons, reader studies, context ablations, consistency tests, and cost measurements; do not execute unapproved experiments.
---

# Literary MT Experiment Design

## Design sequence

1. Read the charter, current state, evaluation protocol, experiment registry, and relevant hardware constraints.
2. State the decision the experiment could change.
3. Define a falsifiable hypothesis and credible alternative explanations.
4. Specify sample, language coverage, genre/features, unit of analysis, context, segmentation, conditions, controls, and exclusions.
5. Define source-fidelity gates before preference scoring. Blind reader preference applies only among outputs that pass the gate.
6. Define consistency checks for names, aliases, pronouns, titles, relationships, terminology, viewpoint, voice, and repeated stylistic choices.
7. Predefine rubric, reviewer qualifications, blinding/randomization, adjudication, missing-data handling, and analysis.
8. Log reproducibility and cost fields.
9. Estimate compute, data, and human-review requirements. Prefer the smallest informative pilot.
10. Record thresholds, limitations, risks, and stop conditions in the existing experiment registry.

## Evaluation layers

- **Fidelity:** omissions, additions, mistranslations, agency/relationship errors, cultural/idiom errors, viewpoint shifts, and other meaning-changing defects.
- **Reader response:** blind preference and qualitative comments among fidelity-acceptable candidates.
- **Literary diagnostics:** voice, register, dialogue, figurative language, rhythm, characterization, and coherence.
- **Long-range consistency:** names, terminology, relationships, voice, and viewpoint across distant passages.
- **Efficiency:** quality-accepted English words per total cost, including inference, review, correction, and operations.

Automatic metrics and LLM judges are diagnostics, not ground truth. Validate any judge against qualified human assessments before relying on it for selection.

## Reproducibility log

Capture provenance/access status; language, genre, passage features, and context; exact model ID/revision; quantization/backend/hardware; prompt, segmentation, decoding, tokens; wall time, peak memory, failures/retries; rubric and evaluator qualifications; blind/randomization method; fidelity and reader judgments; adjudication; human correction time; cost assumptions/calculation.

## Authorization

Experiment design does not authorize execution. Do not download full corpora, run inference, train/fine-tune/RL, consume paid compute, or launch a large batch without explicit user approval. A local dry-run that performs model inference or meaningful compute also requires approval.

## Output

Provide the decision/hypothesis, conditions/controls, sample/language coverage, rubric/analysis, resource estimate, risks/limitations, falsification criteria, and explicit authorization needed before execution.
