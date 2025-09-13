---
interface_name: creditapp.module.MainProcess
process_file: bw-samples-master/bw-samples-master/TN2018/Apps/CreditAppService/CreditApp.module/Processes/creditapp/module/MainProcess.bwp
source_hash: d5b80129c59cde695c4a6cb6b6254cb469a9313e0c77a5ccbc4906d1bc3e3b5b
extracted_at: '2025-09-12T22:59:38.208323+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.81
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.1
  evidence_strength: 1.0
  inferred_fraction: 0.0
detected_format: process_xml
start_activity: OnMessageEnd
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 0
---

## creditapp.module.MainProcess — One-line summary
This process implements a REST service "creditapp.module.MainProcess" at Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema that performs domain logic returns a structured response.

## What it does (specific steps)
- Receives a REST request (endpoint: /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema, method: Unknown).

## Why this matters (business view)
- Enables downstream systems to obtain a specific, structured result.
- Provides traceability via explicit logging and error handling paths.

## Interfaces exposed
- REST: Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema (evidence: {http://schemas.xmlsoap.org/wsdl/}import)
- REST: Unknown /creditdetails (evidence: {http://schemas.xmlsoap.org/wsdl/}portType)
- REST: POST Unknown (evidence: {http://schemas.xmlsoap.org/wsdl/}operation)
- REST: Unknown //0/@process (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.2 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0/@messages.0/@activity/@activity/@activities.3 (evidence: element)

## Interdependency Map
- Related family processes: creditapp.module.EquifaxScore, creditapp.module.ExperianScore

## Technical appendix
The process **creditapp.module.MainProcess** consists of 40 activities connected by transitions.

### Activities
- CorrelationValue (xs:string)
- ProcessStack (xs:string)
- EngineName (xs:string)
- CustomJobId (xs:string)
- Msg (xs:string)
- Data (tns:anydata)
- OptionalErrorReport (tns:OptionalErrorReport)
- FullClass (xs:string)
- ActivityException (tns:ActivityExceptionType)
- ActivityName (xs:string)
- ProcessInstanceId (xs:string)
- ProcessContext (tns:ProcessContext)
- StackTrace (xs:string)
- FaultDetail (tns:FaultDetail)
- ActivityTimedOutException (tns:ActivityTimedOutExceptionType)
- Class (xs:string)
- MsgCode (xs:string)
- TrackingInfo (xs:string)
- ErrorReport (tns:ErrorReport)
- ApplicationName (xs:string)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- JobId (xs:string)
- creditdetails (bpws:partnerLink)
- _processContext (bpws:variable)
- post (bpws:variable)
- postOut-input (bpws:variable)
- EquifaxScore-input (bpws:variable)
- EquifaxScore (bpws:variable)
- ExperianScore-input (bpws:variable)
- ExperianScore (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- pick (bpws:pick)
- scope1 (bpws:scope)
- flow1 (bpws:flow)
- FICOScoreTopostOut (bpws:link)
- ExperianScoreTopostOut (bpws:link)
- OnMessageStart (bpws:empty)
- OnMessageEnd (bpws:empty)
- postOut (bpws:reply)

## Related Documents
- [creditapp.module.EquifaxScore](creditapp.module.EquifaxScore.md)
- [creditapp.module.ExperianScore](creditapp.module.ExperianScore.md)
