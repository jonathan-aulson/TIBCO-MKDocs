---
{}
---

# Family creditcheckservice — domain view
<!-- CONFIDENCE_INLINE -->
> **Confidence Score:** 0.81 — *(see scoring table at bottom for details)*


## Members
- creditcheckservice.LookupDatabase
- creditcheckservice.LookupDatabase
- creditcheckservice.Process
- creditcheckservice.Process

## Exposed Endpoints (detected)
- creditcheckservice.LookupDatabase: Unknown //0/@process/@activity
- creditcheckservice.LookupDatabase: Unknown //0/@process/@activity/@activity
- creditcheckservice.LookupDatabase: Unknown //0/@process/@activity/@activity/@activities.0
- creditcheckservice.LookupDatabase: Unknown //0/@process/@activity/@activity/@activities.1
- creditcheckservice.LookupDatabase: Unknown //0/@process/@activity/@activity/@activities.2
- creditcheckservice.LookupDatabase: Unknown //0/@process/@activity/@activity/@activities.3
- creditcheckservice.LookupDatabase: Unknown //0/@process/@activity/@activity/@activities.4
- creditcheckservice.LookupDatabase: Unknown {/T1535753828744Converted/JsonSchema}Response
- creditcheckservice.Process: GET Unknown
- creditcheckservice.Process: POST Unknown
- creditcheckservice.Process: Unknown /
- creditcheckservice.Process: Unknown //0/@process
- creditcheckservice.Process: Unknown //0/@process/@activity/@activity/@activities.0
- creditcheckservice.Process: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.0
- creditcheckservice.Process: Unknown /T1535753828744Converted/JsonSchema
- creditcheckservice.Process: Unknown /creditscore

_This is an automated domain-level synthesis; verify endpoints and flows where needed._

<!-- CONFIDENCE_ROLLUP_START -->
## Confidence & Evidence Rollup

!!! info "How to read these scores"
    - **parsed** — base signal that the process was parsed at all (typically 0.5 when activities were found).
    - **known_types_coverage** — fraction of activities recognized as known BW types (higher is better; low values mean many unknown/opaque steps).
    - **transition_integrity** — 1.0 if all transitions link valid activities; lower means broken/missing links.
    - **role_coverage** — evidence of key roles detected (interface.receive / invoke.process / data.jdbc / messaging.jms, etc.).
    - **evidence_strength** — proportion of claims backed by concrete evidence (e.g., detected endpoints, JDBC targets).
    - **inferred_fraction** — portion of the explanation based on hypotheses (higher = more guesswork).

    Examples:
    - High **known_types_coverage** (≥ 0.7): process uses well-identified palette activities (HTTP/REST/JDBC/JMS/etc.).
    - Low **transition_integrity** (< 1.0): transitions reference non-existent steps (XML issues or partial parse).
    - Low **evidence_strength** (≈ 0.0): few/no concrete endpoints, datastore names, or invocation targets detected.
    - Higher **inferred_fraction** (≥ 0.5): explanation relies on educated guesses (scant evidence in source).
    - Overall score is the average of component scores, penalized by any low scores.
| Document | Score | parsed | known_types | transition_integrity | role_coverage | evidence_strength | inferred_fraction |
|---|---:|---:|---:|---:|---:|---:|---:|
| creditcheckservice.LookupDatabase.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.03 | 1.00 | 0.00 |
| creditcheckservice.Process.md | 0.81 | 0.50 | 0.00 | 1.00 | 0.07 | 1.00 | 0.00 |
| creditcheckservice.LookupDatabase.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.03 | 1.00 | 0.00 |
| creditcheckservice.Process.md | 0.81 | 0.50 | 0.00 | 1.00 | 0.07 | 1.00 | 0.00 |

**Overall score (this document set):** 0.81

<!-- CONFIDENCE_ROLLUP_END -->
