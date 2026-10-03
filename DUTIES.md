# Duties and Responsibilities for Deep Phenotyping OMIM Rare Disease Agent

## Dual-Control Architecture
Maker:
phenotype-mapper

Checker:
genomic-variant-prioritizer

## Operational Workflow
1. The Maker (phenotype-mapper) analyzes incoming telemetry, context, and requirements.
2. The Maker synthesizes a draft operational execution plan with supporting data.
3. The Checker (genomic-variant-prioritizer) independently verifies all assumptions and constraints.
4. If validation passes, the plan is signed, logged, and committed.
5. All actions are appended to the immutable governance audit trail.
