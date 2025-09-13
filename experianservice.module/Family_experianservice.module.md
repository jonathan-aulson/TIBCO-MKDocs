---
{}
---

# Family experianservice.module — domain view
<!-- CONFIDENCE_INLINE -->
> **Confidence Score:** 0.80 — *(see scoring table at bottom for details)*


## Members
- experianservice.module.Process

## Exposed Endpoints (detected)
- experianservice.module.Process: POST Unknown
- experianservice.module.Process: Unknown //0/@process
- experianservice.module.Process: Unknown //0/@process/@activity/@activity/@activities.0
- experianservice.module.Process: Unknown //0/@process/@activity/@activity/@activities.1
- experianservice.module.Process: Unknown //0/@process/@activity/@activity/@activities.2
- experianservice.module.Process: Unknown //0/@process/@activity/@activity/@activities.3
- experianservice.module.Process: Unknown //0/@process/@activity/@activity/@activities.4
- experianservice.module.Process: Unknown /creditscore

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
| experianservice.module.Process.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.03 | 1.00 | 0.00 |

**Overall score (this document set):** 0.80

<!-- CONFIDENCE_ROLLUP_END -->
