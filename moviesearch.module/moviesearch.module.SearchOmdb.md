---
interface_name: moviesearch.module.SearchOmdb
process_file: C:/Users/JonathanAulson/Documents/Projects/Concentra-Tibco-Context/out/tmp/archives/MovieSearchFinal_b47807ce3849/MovieSearch.module/Processes/moviesearch/module/SearchOmdb.bwp
source_hash: f40776772a6faa9e9a03eb14bcb22a25a4988624eaa2f7c316f5ce92f261c58d
extracted_at: '2025-09-12T22:59:39.111528+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.811
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.105
  evidence_strength: 1.0
  inferred_fraction: 0.0
detected_format: process_xml
start_activity: RestReference
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 0
---

## moviesearch.module.SearchOmdb — One-line summary
This process implements a REST service "moviesearch.module.SearchOmdb" at Unknown / that performs domain logic returns a structured response.

## What it does (specific steps)
- Receives a REST request (endpoint: /, method: Unknown).

## Why this matters (business view)
- Enables downstream systems to obtain a specific, structured result.
- Provides traceability via explicit logging and error handling paths.

## Interfaces exposed
- REST: Unknown / (evidence: {http://schemas.xmlsoap.org/wsdl/}portType)
- REST: GET Unknown (evidence: {http://schemas.xmlsoap.org/wsdl/}operation)
- REST: Unknown {http://tns.tibco.com/bw/json/1563800063700}OMDBSearchElement (evidence: {http://www.tibco.com/bpel/2007/extensions}ProcessInterface)
- REST: Unknown //0/@process/@activity/@activity/@activities.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.1 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.2 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity (evidence: element)
- REST: Unknown //0/@process/@activity (evidence: element)

## Interdependency Map
- Related family processes: moviesearch.module.Process

## Technical appendix
The process **moviesearch.module.SearchOmdb** consists of 38 activities connected by transitions.

### Activities
- ProcessInstanceId (xs:string)
- ErrorReport (tns:ErrorReport)
- ProcessContext (tns:ProcessContext)
- ActivityName (xs:string)
- ApplicationName (xs:string)
- JobId (xs:string)
- Msg (xs:string)
- ProcessStack (xs:string)
- CustomJobId (xs:string)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- FullClass (xs:string)
- StackTrace (xs:string)
- Data (tns:anydata)
- MsgCode (xs:string)
- CorrelationValue (xs:string)
- TrackingInfo (xs:string)
- Class (xs:string)
- OptionalErrorReport (tns:OptionalErrorReport)
- ActivityTimedOutException (tns:ActivityTimedOutExceptionType)
- ActivityErrorData (tns:ActivityErrorDataType)
- FaultDetail (tns:FaultDetail)
- ActivityException (tns:ActivityExceptionType)
- EngineName (xs:string)
- Www-omdbapi-com (bpws:partnerLink)
- RestReference (scaext:binding)
- _processContext (bpws:variable)
- get-input (bpws:variable)
- get (bpws:variable)
- _error_get (bpws:variable)
- _error (bpws:variable)
- Start (bpws:variable)
- End-input (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- StartToget (bpws:link)
- getToEnd (bpws:link)
- End (tibex:activityExtension)
- config (properties)

## Related Documents
- [moviesearch.module.Process](moviesearch.module.Process.md)
