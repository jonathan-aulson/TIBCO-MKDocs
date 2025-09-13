---
{}
---

# Family creditapp.module — domain view
<!-- CONFIDENCE_INLINE -->
> **Confidence Score:** 0.81 — *(see scoring table at bottom for details)*


## Members
- creditapp.module.EquifaxScore
- creditapp.module.ExperianScore
- creditapp.module.MainProcess

## Exposed Endpoints (detected)
- creditapp.module.EquifaxScore: POST Unknown
- creditapp.module.EquifaxScore: Unknown /
- creditapp.module.EquifaxScore: Unknown //0/@process
- creditapp.module.EquifaxScore: Unknown //0/@process/@activity/@activity/@activities.0
- creditapp.module.EquifaxScore: Unknown //0/@process/@partnerLinks/@children.0
- creditapp.module.EquifaxScore: Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc
- creditapp.module.EquifaxScore: Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema
- creditapp.module.EquifaxScore: Unknown {/y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema}SuccessSchema
- creditapp.module.ExperianScore: GET Unknown
- creditapp.module.ExperianScore: POST Unknown
- creditapp.module.ExperianScore: Unknown /
- creditapp.module.ExperianScore: Unknown //0/@process/@activity/@activity/@activities.0
- creditapp.module.ExperianScore: Unknown //0/@process/@activity/@activity/@activities.1
- creditapp.module.ExperianScore: Unknown //0/@process/@activity/@activity/@activities.2
- creditapp.module.ExperianScore: Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema
- creditapp.module.ExperianScore: Unknown {http://tns.tibco.com/bw/json/1535671685533}ExperianResponseSchemaElement
- creditapp.module.MainProcess: POST Unknown
- creditapp.module.MainProcess: Unknown //0/@process
- creditapp.module.MainProcess: Unknown //0/@process/@activity/@activity/@activities.0
- creditapp.module.MainProcess: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.0
- creditapp.module.MainProcess: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.2
- creditapp.module.MainProcess: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.3
- creditapp.module.MainProcess: Unknown /creditdetails
- creditapp.module.MainProcess: Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema

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
| creditapp.module.EquifaxScore.md | 0.81 | 0.50 | 0.00 | 1.00 | 0.13 | 1.00 | 0.00 |
| creditapp.module.ExperianScore.md | 0.81 | 0.50 | 0.00 | 1.00 | 0.07 | 1.00 | 0.00 |
| creditapp.module.MainProcess.md | 0.81 | 0.50 | 0.00 | 1.00 | 0.10 | 1.00 | 0.00 |

**Overall score (this document set):** 0.81

<!-- CONFIDENCE_ROLLUP_END -->
