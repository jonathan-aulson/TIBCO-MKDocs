---
interface_name: moviecatalogsearch.module.SortSingleMovie
process_file: C:/Users/JonathanAulson/Documents/Projects/Concentra-Tibco-Context/out/tmp/archives/MovieAPI_UnitTesting_a94ab19c4120/MovieCatalogSearch.module/Processes/moviecatalogsearch/module/SortSingleMovie.bwp
source_hash: e1035c7ee04b8700afc596ba2f8ab310d20e4ff494662b5b6637b492bee921f3
extracted_at: '2025-09-12T22:59:38.992468+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.796
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.082
  evidence_strength: 1.0
  inferred_fraction: 0.25
detected_format: process_xml
start_activity: logLevel
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 1
---

## moviecatalogsearch.module.SortSingleMovie — One-line summary
This process implements a REST service "moviecatalogsearch.module.SortSingleMovie" at Unknown / that performs domain logic returns a structured response.

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
- REST: Unknown //0/@process/@activity/@activity/@activities.4 (evidence: element)

## Interdependency Map
- Related family processes: moviecatalogsearch.module.GetRatings, moviecatalogsearch.module.Process, moviecatalogsearch.module.SearchMovies, moviecatalogsearch.module.SortMovies, moviecatalogsearch.module.SortMovieSingle

## Extrapolations (educated guesses)
- (Hypothesis 0.50) Family likely implements Search → Get → Sort pipeline for the same domain.
  - Rationale: Peer names include verbs 'Search', 'Get', 'Sort' within same family.
_These are clearly marked as hypotheses; treat as directional until reviewed._

## Technical appendix
The process **moviecatalogsearch.module.SortSingleMovie** consists of 49 activities connected by transitions.

### Activities
- ProcessInstanceId (xs:string)
- ErrorReport (tns:ErrorReport)
- FullClass (xs:string)
- apikey (xsd:string)
- MsgCode (xs:string)
- ProcessContext (tns:ProcessContext)
- message (xs:string)
- Msg (xs:string)
- Data (tns:anydata)
- ProcessStack (xs:string)
- JobId (xs:string)
- Class (xs:string)
- ActivityException (tns:ActivityExceptionType)
- StackTrace (xs:string)
- ActivityErrorData (tns:ActivityErrorDataType)
- CorrelationValue (xs:string)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- FaultDetail (tns:FaultDetail)
- CustomJobId (xs:string)
- msgCode (xs:string)
- EngineName (xs:string)
- ActivityTimedOutException (tns:ActivityTimedOutExceptionType)
- ApplicationName (xs:string)
- TrackingInfo (xs:string)
- OptionalErrorReport (tns:OptionalErrorReport)
- logLevel (xs:string)
- ActivityName (xs:string)
- loggerName (xs:string)
- ActivityInput (tns:LogParametersType)
- RestReference (bpws:partnerLink)
- _processContext (bpws:variable)
- Start (bpws:variable)
- End-input (bpws:variable)
- get-input (bpws:variable)
- get (bpws:variable)
- _error_get (bpws:variable)
- _error (bpws:variable)
- Log-input (bpws:variable)
- Mapper-input (bpws:variable)
- Mapper (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- StartToget (bpws:link)
- getToEnd (bpws:link)
- LogToMapper (bpws:link)
- MapperToEnd (bpws:link)
- End (tibex:activityExtension)
- config (properties)
- Log (tibex:activityExtension)

## Related Documents
- [moviecatalogsearch.module.GetRatings](moviecatalogsearch.module.GetRatings.md)
- [moviecatalogsearch.module.Process](moviecatalogsearch.module.Process.md)
- [moviecatalogsearch.module.SearchMovies](moviecatalogsearch.module.SearchMovies.md)
- [moviecatalogsearch.module.SortMovieSingle](moviecatalogsearch.module.SortMovieSingle.md)
- [moviecatalogsearch.module.SortMovies](moviecatalogsearch.module.SortMovies.md)
