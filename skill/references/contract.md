# Contract

## Capability
Check social-media claims for source traceability, corroboration, timestamp quality and unsupported certainty.

## Input root
`findings` with fields: claim, severity, users_affected, confidence.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
