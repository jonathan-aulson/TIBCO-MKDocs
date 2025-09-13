---
interface_name: moviecatalogsearch.module.SortMovieSingle
process_file: C:/Users/JonathanAulson/Documents/Projects/Concentra-Tibco-Context/out/tmp/archives/MovieAPI_ForUnitTesting_5e3844c9f8a2/MovieCatalogSearch.module/Processes/moviecatalogsearch/module/SortMovieSingle.bwp
source_hash: c74b613858268c8e53feb6c0e1fcc3eea3813a48cf0dd7b21efab565feb4da49
extracted_at: '2025-09-12T22:59:38.752361+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.797
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.098
  evidence_strength: 1.0
  inferred_fraction: 0.25
detected_format: process_xml
start_activity: RestReference
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 1
---

## moviecatalogsearch.module.SortMovieSingle — One-line summary
This process implements a REST service "moviecatalogsearch.module.SortMovieSingle" at Unknown / that performs domain logic returns a structured response.

## What it does (specific steps)
- Receives a REST request (endpoint: /, method: Unknown).

## Why this matters (business view)
- Enables downstream systems to obtain a specific, structured result.
- Provides traceability via explicit logging and error handling paths.

## Interfaces exposed
- REST: Unknown / (evidence: {http://schemas.xmlsoap.org/wsdl/}portType)
- REST: GET Unknown (evidence: {http://schemas.xmlsoap.org/wsdl/}operation)
- REST: Unknown {http://www.example.org/MovieCatalogMaster}Movie (evidence: {http://www.tibco.com/bpel/2007/extensions}ProcessInterface)
- REST: Unknown //0/@process/@activity/@activity/@activities.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.1 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.2 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.3 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity (evidence: element)

## Interdependency Map
- Related family processes: moviecatalogsearch.module.GetRatings, moviecatalogsearch.module.Process, moviecatalogsearch.module.SearchMovies, moviecatalogsearch.module.SortMovies, moviecatalogsearch.module.SortSingleMovie

## Extrapolations (educated guesses)
- (Hypothesis 0.50) Family likely implements Search → Get → Sort pipeline for the same domain.
  - Rationale: Peer names include verbs 'Search', 'Get', 'Sort' within same family.
_These are clearly marked as hypotheses; treat as directional until reviewed._

## Technical appendix
The process **moviecatalogsearch.module.SortMovieSingle** consists of 41 activities connected by transitions.

### Activities
- Msg (xs:string)
- EngineName (xs:string)
- ProcessStack (xs:string)
- apikey (xsd:string)
- Data (tns:anydata)
- ProcessInstanceId (xs:string)
- Class (xs:string)
- ActivityName (xs:string)
- FullClass (xs:string)
- TrackingInfo (xs:string)
- CorrelationValue (xs:string)
- MsgCode (xs:string)
- ActivityTimedOutException (tns:ActivityTimedOutExceptionType)
- ErrorReport (tns:ErrorReport)
- OptionalErrorReport (tns:OptionalErrorReport)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- ActivityErrorData (tns:ActivityErrorDataType)
- StackTrace (xs:string)
- FaultDetail (tns:FaultDetail)
- ProcessContext (tns:ProcessContext)
- JobId (xs:string)
- ApplicationName (xs:string)
- ActivityException (tns:ActivityExceptionType)
- CustomJobId (xs:string)
- RestReference (bpws:partnerLink)
- _processContext (bpws:variable)
- get-input (bpws:variable)
- get (bpws:variable)
- _error_get (bpws:variable)
- _error (bpws:variable)
- End-input (bpws:variable)
- Mapper-input (bpws:variable)
- Mapper (bpws:variable)
- Start (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- StartToget (bpws:link)
- getToEnd (bpws:link)
- MapperToEnd (bpws:link)
- End (tibex:activityExtension)
- config (properties)

## Related Documents
- [moviecatalogsearch.module.GetRatings](moviecatalogsearch.module.GetRatings.md)
- [moviecatalogsearch.module.Process](moviecatalogsearch.module.Process.md)
- [moviecatalogsearch.module.SearchMovies](moviecatalogsearch.module.SearchMovies.md)
- [moviecatalogsearch.module.SortMovies](moviecatalogsearch.module.SortMovies.md)
- [moviecatalogsearch.module.SortSingleMovie](moviecatalogsearch.module.SortSingleMovie.md)
