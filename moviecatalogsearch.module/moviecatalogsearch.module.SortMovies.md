---
interface_name: moviecatalogsearch.module.SortMovies
process_file: C:/Users/JonathanAulson/Documents/Projects/Concentra-Tibco-Context/out/tmp/archives/MovieAPI_UnitTesting_a94ab19c4120/MovieCatalogSearch.module/Processes/moviecatalogsearch/module/SortMovies.bwp
source_hash: 9ccd1b3e39748b3cf6e9f1f61e03707defdeef779ed6bdd603e1c97d72875e98
extracted_at: '2025-09-12T22:59:38.956583+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.793
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.058
  evidence_strength: 1.0
  inferred_fraction: 0.25
detected_format: process_xml
start_activity: StartToIterate
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 1
---

## moviecatalogsearch.module.SortMovies — One-line summary
This process implements a REST service "moviecatalogsearch.module.SortMovies" at Unknown / that performs domain logic returns a structured response.

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
- REST: Unknown //0/@process/@activity/@activity/@activities.2/@activity/@activities.1/@activity/@activity/@activities.2 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.2/@activity/@activities.1/@activity/@activity/@activities.3 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.2/@activity/@activities.1/@activity/@activity/@activities.4 (evidence: element)

## Interdependency Map
- Related family processes: moviecatalogsearch.module.GetRatings, moviecatalogsearch.module.Process, moviecatalogsearch.module.SearchMovies, moviecatalogsearch.module.SortMovies, moviecatalogsearch.module.SortMovieSingle, moviecatalogsearch.module.SortSingleMovie

## Extrapolations (educated guesses)
- (Hypothesis 0.50) Family likely implements Search → Get → Sort pipeline for the same domain.
  - Rationale: Peer names include verbs 'Search', 'Get', 'Sort' within same family.
_These are clearly marked as hypotheses; treat as directional until reviewed._

## Technical appendix
The process **moviecatalogsearch.module.SortMovies** consists of 69 activities connected by transitions.

### Activities
- Msg (xs:string)
- ProcessStack (xs:string)
- ProcessContext (tns:ProcessContext)
- Class (xs:string)
- StackTrace (xs:string)
- ActivityName (xs:string)
- OptionalErrorReport (tns:OptionalErrorReport)
- FaultDetail (tns:FaultDetail)
- MsgCode (xs:string)
- Data (tns:anydata)
- ProcessInstanceId (xs:string)
- JobId (xs:string)
- TrackingInfo (xs:string)
- FullClass (xs:string)
- message (xs:string)
- ActivityTimedOutException (tns:ActivityTimedOutExceptionType)
- msgCode (xs:string)
- AccumulatedOutput (tns:AccumulatedOutputType)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- ErrorReport (tns:ErrorReport)
- loggerName (xs:string)
- ActivityInput (tns:LogParametersType)
- ActivityException (tns:ActivityExceptionType)
- ApplicationName (xs:string)
- apiKey (xsd:string)
- logLevel (xs:string)
- CorrelationValue (xs:string)
- EngineName (xs:string)
- CustomJobId (xs:string)
- ActivityErrorData (tns:ActivityErrorDataType)
- Www-omdbapi-com (bpws:partnerLink)
- RestReference (scaext:binding)
- _processContext (bpws:variable)
- Start (bpws:variable)
- End-input (bpws:variable)
- Mapper-input (bpws:variable)
- Mapper (bpws:variable)
- InvokeOmdb-input (bpws:variable)
- InvokeOmdb (bpws:variable)
- _error_InvokeOmdb (bpws:variable)
- _error (bpws:variable)
- Log-input (bpws:variable)
- Log1-input (bpws:variable)
- Accumulate (bpws:variable)
- Log2-input (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- StartToIterate (bpws:link)
- IterateToEnd (bpws:link)
- LogToEnd (bpws:link)
- End (tibex:activityExtension)
- config (properties)
- Iterate (bpws:scope)
- sequence (bpws:sequence)
- GroupInit (bpws:assign)
- iterate (bpws:forEach)
- variableList (tibex:DesignExpression)
- innerScope (bpws:scope)
- currentElement (bpws:variable)
- flow1 (bpws:flow)
- MapperToGroupEnd (bpws:link)
- GroupStartToget (bpws:link)
- getToMapper (bpws:link)
- Log1ToMapper (bpws:link)
- Log2ToInvokeOmdb (bpws:link)
- GroupStart (bpws:assign)
- Log1 (tibex:activityExtension)
- Log2 (tibex:activityExtension)
- Log (tibex:activityExtension)

## Related Documents
- [moviecatalogsearch.module.GetRatings](moviecatalogsearch.module.GetRatings.md)
- [moviecatalogsearch.module.Process](moviecatalogsearch.module.Process.md)
- [moviecatalogsearch.module.SearchMovies](moviecatalogsearch.module.SearchMovies.md)
- [moviecatalogsearch.module.SortMovieSingle](moviecatalogsearch.module.SortMovieSingle.md)
- [moviecatalogsearch.module.SortMovies](moviecatalogsearch.module.SortMovies.md)
- [moviecatalogsearch.module.SortSingleMovie](moviecatalogsearch.module.SortSingleMovie.md)
