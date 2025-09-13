---
{}
---

# Family moviecatalogsearch.module — domain view
<!-- CONFIDENCE_INLINE -->
> **Confidence Score:** 0.80 — *(see scoring table at bottom for details)*


## Members
- moviecatalogsearch.module.GetRatings
- moviecatalogsearch.module.GetRatings
- moviecatalogsearch.module.GetRatings
- moviecatalogsearch.module.Process
- moviecatalogsearch.module.Process
- moviecatalogsearch.module.Process
- moviecatalogsearch.module.SearchMovies
- moviecatalogsearch.module.SearchMovies
- moviecatalogsearch.module.SearchMovies
- moviecatalogsearch.module.SortMovieSingle
- moviecatalogsearch.module.SortMovies
- moviecatalogsearch.module.SortMovies
- moviecatalogsearch.module.SortMovies
- moviecatalogsearch.module.SortSingleMovie

## Exposed Endpoints (detected)
- moviecatalogsearch.module.GetRatings: Unknown //0
- moviecatalogsearch.module.GetRatings: Unknown //0/@process
- moviecatalogsearch.module.GetRatings: Unknown //0/@process/@activity
- moviecatalogsearch.module.GetRatings: Unknown //0/@process/@activity/@activity
- moviecatalogsearch.module.GetRatings: Unknown //0/@process/@activity/@activity/@activities.0
- moviecatalogsearch.module.GetRatings: Unknown //0/@process/@activity/@activity/@activities.1
- moviecatalogsearch.module.GetRatings: Unknown //0/@process/@activity/@activity/@links/@children.0
- moviecatalogsearch.module.GetRatings: Unknown //@children.0/@children.3/@children.0/@children.0/@children.0/@children.0/@children.0/@children.0/@children.1
- moviecatalogsearch.module.Process: GET Unknown
- moviecatalogsearch.module.Process: Unknown //0/@process
- moviecatalogsearch.module.Process: Unknown //0/@process/@activity/@activity/@activities.0
- moviecatalogsearch.module.Process: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.0
- moviecatalogsearch.module.Process: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.2
- moviecatalogsearch.module.Process: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.3
- moviecatalogsearch.module.Process: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.4
- moviecatalogsearch.module.Process: Unknown /movies
- moviecatalogsearch.module.SearchMovies: GET Unknown
- moviecatalogsearch.module.SearchMovies: Unknown //0/@process/@activity/@activity/@activities.0
- moviecatalogsearch.module.SearchMovies: Unknown //0/@process/@activity/@activity/@activities.1
- moviecatalogsearch.module.SearchMovies: Unknown //0/@process/@activity/@activity/@activities.2
- moviecatalogsearch.module.SearchMovies: Unknown //0/@process/@activity/@activity/@activities.3
- moviecatalogsearch.module.SearchMovies: Unknown /T1563811039923Converted/JsonSchema
- moviecatalogsearch.module.SearchMovies: Unknown /movies
- moviecatalogsearch.module.SearchMovies: Unknown {http://www.example.org/MovieCatalogMaster}OMDBSearchElement
- moviecatalogsearch.module.SortMovieSingle: GET Unknown
- moviecatalogsearch.module.SortMovieSingle: Unknown /
- moviecatalogsearch.module.SortMovieSingle: Unknown //0/@process/@activity/@activity
- moviecatalogsearch.module.SortMovieSingle: Unknown //0/@process/@activity/@activity/@activities.0
- moviecatalogsearch.module.SortMovieSingle: Unknown //0/@process/@activity/@activity/@activities.1
- moviecatalogsearch.module.SortMovieSingle: Unknown //0/@process/@activity/@activity/@activities.2
- moviecatalogsearch.module.SortMovieSingle: Unknown //0/@process/@activity/@activity/@activities.3
- moviecatalogsearch.module.SortMovieSingle: Unknown {http://www.example.org/MovieCatalogMaster}Movie
- moviecatalogsearch.module.SortMovies: GET Unknown
- moviecatalogsearch.module.SortMovies: Unknown /
- moviecatalogsearch.module.SortMovies: Unknown //0/@process/@activity/@activity/@activities.0
- moviecatalogsearch.module.SortMovies: Unknown //0/@process/@activity/@activity/@activities.1
- moviecatalogsearch.module.SortMovies: Unknown //0/@process/@activity/@activity/@activities.2/@activity/@activities.1/@activity/@activity/@activities.2
- moviecatalogsearch.module.SortMovies: Unknown //0/@process/@activity/@activity/@activities.2/@activity/@activities.1/@activity/@activity/@activities.3
- moviecatalogsearch.module.SortMovies: Unknown //0/@process/@activity/@activity/@activities.2/@activity/@activities.1/@activity/@activity/@activities.4
- moviecatalogsearch.module.SortMovies: Unknown {http://www.example.org/MovieCatalogMaster}Movie
- moviecatalogsearch.module.SortSingleMovie: GET Unknown
- moviecatalogsearch.module.SortSingleMovie: Unknown /
- moviecatalogsearch.module.SortSingleMovie: Unknown //0/@process/@activity/@activity/@activities.0
- moviecatalogsearch.module.SortSingleMovie: Unknown //0/@process/@activity/@activity/@activities.1
- moviecatalogsearch.module.SortSingleMovie: Unknown //0/@process/@activity/@activity/@activities.2
- moviecatalogsearch.module.SortSingleMovie: Unknown //0/@process/@activity/@activity/@activities.3
- moviecatalogsearch.module.SortSingleMovie: Unknown //0/@process/@activity/@activity/@activities.4
- moviecatalogsearch.module.SortSingleMovie: Unknown {http://www.example.org/MovieCatalogMaster}Movie

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
| moviecatalogsearch.module.GetRatings.md | 0.79 | 0.50 | 0.00 | 1.00 | 0.07 | 1.00 | 0.25 |
| moviecatalogsearch.module.Process.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.07 | 1.00 | 0.25 |
| moviecatalogsearch.module.SearchMovies.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.11 | 1.00 | 0.25 |
| moviecatalogsearch.module.SortMovies.md | 0.79 | 0.50 | 0.00 | 1.00 | 0.06 | 1.00 | 0.25 |
| moviecatalogsearch.module.GetRatings.md | 0.79 | 0.50 | 0.00 | 1.00 | 0.07 | 1.00 | 0.25 |
| moviecatalogsearch.module.Process.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.07 | 1.00 | 0.25 |
| moviecatalogsearch.module.SearchMovies.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.11 | 1.00 | 0.25 |
| moviecatalogsearch.module.SortMovies.md | 0.79 | 0.50 | 0.00 | 1.00 | 0.06 | 1.00 | 0.25 |
| moviecatalogsearch.module.SortMovieSingle.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.10 | 1.00 | 0.25 |
| moviecatalogsearch.module.GetRatings.md | 0.79 | 0.50 | 0.00 | 1.00 | 0.07 | 1.00 | 0.25 |
| moviecatalogsearch.module.Process.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.07 | 1.00 | 0.25 |
| moviecatalogsearch.module.SearchMovies.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.11 | 1.00 | 0.25 |
| moviecatalogsearch.module.SortMovies.md | 0.79 | 0.50 | 0.00 | 1.00 | 0.06 | 1.00 | 0.25 |
| moviecatalogsearch.module.SortSingleMovie.md | 0.80 | 0.50 | 0.00 | 1.00 | 0.08 | 1.00 | 0.25 |

**Overall score (this document set):** 0.80

<!-- CONFIDENCE_ROLLUP_END -->
