# Coding Scheme Dossiers

This directory contains a communication-ready dossier for each distinct coding scheme identified in the systematic review workflow, plus a compiled PDF for direct sharing.

## Inventory

1. `scheme_1`
   - Topic: Stage 1 screening and eligibility decision scheme
   - Files: `scheme_1/scheme_1.tex`, `scheme_1/scheme_1.pdf`
   - Main source paths:
     - `src/protocol/decision_rules/screening_rules.md`
     - `src/bps_review/screening/rules.py`
     - `src/review_stages/03_screening/README.md`

2. `scheme_2`
   - Topic: Stage 2 abstract-level structured coding scheme
   - Files: `scheme_2/scheme_2.tex`, `scheme_2/scheme_2.pdf`
   - Main source paths:
     - `src/protocol/codebooks/stage2_codebook.md`
     - `src/review_stages/04_extraction/codebooks/stage2_codebook.csv`
     - `src/bps_review/extraction/stage2.py`
     - `src/bps_review/extraction/llm_stage2.py`
     - `src/review_stages/04_extraction/outputs/stage2_abstract_coding.csv`

3. `scheme_3`
   - Topic: Stage 3 full-text deep coding scheme
   - Files: `scheme_3/scheme_3.tex`, `scheme_3/scheme_3.pdf`
   - Main source paths:
     - `src/protocol/codebooks/stage3_codebook.md`
     - `src/review_stages/04_extraction/codebooks/stage3_codebook.csv`
     - `src/bps_review/extraction/stage3_prep.py`
     - `src/review_stages/04_extraction/forms/stage3_fulltext_coding_template.csv`

4. `scheme_4`
   - Topic: Stage 3 retrieval and manual relevance triage scheme
   - Files: `scheme_4/scheme_4.tex`, `scheme_4/scheme_4.pdf`
   - Main source paths:
     - `src/bps_review/extraction/stage3_prep.py`
     - `src/review_stages/04_extraction/forms/stage3_manual_relevance_checklist.csv`
     - `src/review_stages/04_extraction/outputs/stage3_candidate_manifest.csv`

5. `scheme_5`
   - Topic: Psychological concept clustering and framework mapping scheme
   - Files: `scheme_5/scheme_5.tex`, `scheme_5/scheme_5.pdf`
   - Main source paths:
     - `src/bps_review/extraction/coding.py`
     - `src/protocol/codebooks/stage2_codebook.md`
     - `src/protocol/codebooks/stage3_codebook.md`
     - `src/data/interim/extraction/llm_concept_clusters.json`

6. `scheme_6`
   - Topic: BPS ontology and semantic loading benchmark scheme
   - Files: `scheme_6/scheme_6.tex`, `scheme_6/scheme_6.pdf`
   - Main source paths:
     - `src/bps_review/reporting/semantic_loading.py`
     - `src/vector_db/semantic_loading/ontology/ontology_terms.json`
     - `src/vector_db/semantic_loading/analysis/domain_loading_summary.csv`

## Notes

- The dossiers prioritize the operational implementation used by the pipeline.
- Where protocol prose, codebooks, and generated outputs diverge, the dossiers state that explicitly.
- The underlying outputs and source files referenced above remain in their original project paths so reviewers can inspect the raw materials directly.
