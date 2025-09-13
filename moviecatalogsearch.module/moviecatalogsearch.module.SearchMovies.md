---
interface_name: moviecatalogsearch.module.SearchMovies
process_file: C:/Users/JonathanAulson/Documents/Projects/Concentra-Tibco-Context/out/tmp/archives/MovieAPI_UnitTesting_a94ab19c4120/MovieCatalogSearch.module/Processes/moviecatalogsearch/module/SearchMovies.bwp
source_hash: ab94db2f593ccdf95f70ef6df4715be98335003ac94ad25e938fe5787c7e89fa
extracted_at: '2025-09-12T22:59:38.919568+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.798
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.109
  evidence_strength: 1.0
  inferred_fraction: 0.25
detected_format: process_xml
start_activity: logLevel
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 1
---

## moviecatalogsearch.module.SearchMovies — One-line summary
This process implements a REST service "moviecatalogsearch.module.SearchMovies" at Unknown /T1563811039923Converted/JsonSchema that performs domain logic returns a structured response.

## What it does (specific steps)
- Receives a REST request (endpoint: /T1563811039923Converted/JsonSchema, method: Unknown).

## Why this matters (business view)
- Enables downstream systems to obtain a specific, structured result.
- Provides traceability via explicit logging and error handling paths.

## Interfaces exposed
- REST: Unknown /T1563811039923Converted/JsonSchema (evidence: {http://schemas.xmlsoap.org/wsdl/}import)
- REST: Unknown /movies (evidence: {http://schemas.xmlsoap.org/wsdl/}portType)
- REST: GET Unknown (evidence: {http://schemas.xmlsoap.org/wsdl/}operation)
- REST: Unknown {http://www.example.org/MovieCatalogMaster}OMDBSearchElement (evidence: {http://www.tibco.com/bpel/2007/extensions}ProcessInterface)
- REST: Unknown //0/@process/@activity/@activity/@activities.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.1 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.2 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.3 (evidence: element)

## Interdependency Map
- Related family processes: moviecatalogsearch.module.GetRatings, moviecatalogsearch.module.Process, moviecatalogsearch.module.SortMovies, moviecatalogsearch.module.SearchMovies, moviecatalogsearch.module.SortMovieSingle, moviecatalogsearch.module.SortSingleMovie

## Extrapolations (educated guesses)
- (Hypothesis 0.50) Family likely implements Search → Get → Sort pipeline for the same domain.
  - Rationale: Peer names include verbs 'Search', 'Get', 'Sort' within same family.
_These are clearly marked as hypotheses; treat as directional until reviewed._

## Technical appendix
The process **moviecatalogsearch.module.SearchMovies** consists of 46 activities connected by transitions.

### Activities
- MsgCode (xs:string)
- StackTrace (xs:string)
- Data (tns:anydata)
- ProcessStack (xs:string)
- CorrelationValue (xs:string)
- FaultDetail (tns:FaultDetail)
- ActivityErrorData (tns:ActivityErrorDataType)
- EngineName (xs:string)
- Class (xs:string)
- ProcessInstanceId (xs:string)
- ProcessContext (tns:ProcessContext)
- ApplicationName (xs:string)
- ActivityTimedOutException (tns:ActivityTimedOutExceptionType)
- ActivityInput (tns:LogParametersType)
- FullClass (xs:string)
- loggerName (xs:string)
- Msg (xs:string)
- message (xs:string)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- ActivityName (xs:string)
- JobId (xs:string)
- msgCode (xs:string)
- logLevel (xs:string)
- ErrorReport (tns:ErrorReport)
- CustomJobId (xs:string)
- TrackingInfo (xs:string)
- ActivityException (tns:ActivityExceptionType)
- OptionalErrorReport (tns:OptionalErrorReport)
- movies (bpws:partnerLink)
- RestReference (scaext:binding)
- _processContext (bpws:variable)
- End-input (bpws:variable)
- get-input (bpws:variable)
- get (bpws:variable)
- _error_get (bpws:variable)
- _error (bpws:variable)
- Start (bpws:variable)
- Log-input (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- StartToget (bpws:link)
- getToEnd (bpws:link)
- LogToEnd (bpws:link)
- End (tibex:activityExtension)
- config (properties)
- Log (tibex:activityExtension)

## Related Documents
- [moviecatalogsearch.module.GetRatings](moviecatalogsearch.module.GetRatings.md)
- [moviecatalogsearch.module.Process](moviecatalogsearch.module.Process.md)
- [moviecatalogsearch.module.SearchMovies](moviecatalogsearch.module.SearchMovies.md)
- [moviecatalogsearch.module.SortMovieSingle](moviecatalogsearch.module.SortMovieSingle.md)
- [moviecatalogsearch.module.SortMovies](moviecatalogsearch.module.SortMovies.md)
- [moviecatalogsearch.module.SortSingleMovie](moviecatalogsearch.module.SortSingleMovie.md)
