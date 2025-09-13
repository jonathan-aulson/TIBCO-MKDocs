---
interface_name: moviesearch.module.Process
process_file: C:/Users/JonathanAulson/Documents/Projects/Concentra-Tibco-Context/out/tmp/archives/MovieSearchFinal_b47807ce3849/MovieSearch.module/Processes/moviesearch/module/Process.bwp
source_hash: 32f34a8792a3c364b861c977c9af421351911939428b2037fbd4504c23ff6102
extracted_at: '2025-09-12T22:59:39.048297+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.808
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.081
  evidence_strength: 1.0
  inferred_fraction: 0.0
detected_format: process_xml
start_activity: OnMessageEnd
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 0
---

## moviesearch.module.Process — One-line summary
This process implements a REST service "moviesearch.module.Process" at Unknown /movies that performs domain logic returns a structured response.

## What it does (specific steps)
- Receives a REST request (endpoint: /movies, method: Unknown).

## Why this matters (business view)
- Enables downstream systems to obtain a specific, structured result.
- Provides traceability via explicit logging and error handling paths.

## Interfaces exposed
- REST: Unknown /movies (evidence: {http://schemas.xmlsoap.org/wsdl/}portType)
- REST: GET Unknown (evidence: {http://schemas.xmlsoap.org/wsdl/}operation)
- REST: Unknown //0/@process (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.2 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.3 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity (evidence: element)

## Interdependency Map
- Related family processes: moviesearch.module.SearchOmdb

## Technical appendix
The process **moviesearch.module.Process** consists of 37 activities connected by transitions.

### Activities
- FullClass (xs:string)
- Data (tns:anydata)
- MsgCode (xs:string)
- OptionalErrorReport (tns:OptionalErrorReport)
- StackTrace (xs:string)
- EngineName (xs:string)
- ActivityException (tns:ActivityExceptionType)
- ProcessStack (xs:string)
- ErrorReport (tns:ErrorReport)
- ProcessInstanceId (xs:string)
- Class (xs:string)
- FaultDetail (tns:FaultDetail)
- TrackingInfo (xs:string)
- ProcessContext (tns:ProcessContext)
- ApplicationName (xs:string)
- CorrelationValue (xs:string)
- Msg (xs:string)
- CustomJobId (xs:string)
- JobId (xs:string)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- ActivityName (xs:string)
- ActivityTimedOutException (tns:ActivityTimedOutExceptionType)
- movies (bpws:partnerLink)
- _processContext (bpws:variable)
- get (bpws:variable)
- getOut-input (bpws:variable)
- SearchOmdb-input (bpws:variable)
- SearchOmdb (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- pick (bpws:pick)
- scope1 (bpws:scope)
- flow1 (bpws:flow)
- SearchOmdbTogetOut (bpws:link)
- OnMessageStart (bpws:empty)
- OnMessageEnd (bpws:empty)
- getOut (bpws:reply)

## Related Documents
- [moviesearch.module.SearchOmdb](moviesearch.module.SearchOmdb.md)
