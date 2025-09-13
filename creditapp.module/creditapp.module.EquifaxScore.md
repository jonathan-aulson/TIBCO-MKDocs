---
interface_name: creditapp.module.EquifaxScore
process_file: bw-samples-master/bw-samples-master/TN2018/Apps/CreditAppService/CreditApp.module/Processes/creditapp/module/EquifaxScore.bwp
source_hash: 95e2452744f4cda24ad462b4bd24ee5d66a3e42c3a28f2a62b6fce1b073f4f7a
extracted_at: '2025-09-12T22:59:38.160096+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.813
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.128
  evidence_strength: 1.0
  inferred_fraction: 0.0
detected_format: process_xml
start_activity: StartTopost
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 0
---

## creditapp.module.EquifaxScore — One-line summary
This process implements a REST service "creditapp.module.EquifaxScore" at Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema that performs domain logic returns a structured response.

## What it does (specific steps)
- Receives a REST request (endpoint: /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema, method: Unknown).

## Why this matters (business view)
- Enables downstream systems to obtain a specific, structured result.
- Provides traceability via explicit logging and error handling paths.

## Interfaces exposed
- REST: Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema (evidence: {http://schemas.xmlsoap.org/wsdl/}import)
- REST: Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc (evidence: {http://schemas.xmlsoap.org/wsdl/}portType)
- REST: POST Unknown (evidence: {http://schemas.xmlsoap.org/wsdl/}operation)
- REST: Unknown / (evidence: {http://schemas.xmlsoap.org/wsdl/}portType)
- REST: Unknown {/y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema}SuccessSchema (evidence: {http://www.tibco.com/bpel/2007/extensions}ProcessInterface)
- REST: Unknown //0/@process (evidence: element)
- REST: Unknown //0/@process/@partnerLinks/@children.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0 (evidence: element)

## Interdependency Map
- Related family processes: creditapp.module.ExperianScore, creditapp.module.MainProcess

## Technical appendix
The process **creditapp.module.EquifaxScore** consists of 39 activities connected by transitions.

### Activities
- StackTrace (xs:string)
- Class (xs:string)
- JobId (xs:string)
- ApplicationName (xs:string)
- Msg (xs:string)
- EngineName (xs:string)
- ProcessInstanceId (xs:string)
- CustomJobId (xs:string)
- TrackingInfo (xs:string)
- OptionalErrorReport (tns:OptionalErrorReport)
- Data (tns:anydata)
- ErrorReport (tns:ErrorReport)
- FaultDetail (tns:FaultDetail)
- FullClass (xs:string)
- ProcessContext (tns:ProcessContext)
- MsgCode (xs:string)
- CorrelationValue (xs:string)
- ActivityException (tns:ActivityExceptionType)
- ProcessStack (xs:string)
- ActivityTimedOutException (tns:ActivityTimedOutExceptionType)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- ActivityErrorData (tns:ActivityErrorDataType)
- client-404-RecordNotFound (xsd:string)
- ActivityName (xs:string)
- creditscore1 (bpws:partnerLink)
- RestReference (scaext:binding)
- _processContext (bpws:variable)
- Start (bpws:variable)
- End-input (bpws:variable)
- post-input (bpws:variable)
- post (bpws:variable)
- _error_post (bpws:variable)
- _error (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- StartTopost (bpws:link)
- postToEnd (bpws:link)
- End (tibex:activityExtension)
- config (properties)

## Related Documents
- [creditapp.module.ExperianScore](creditapp.module.ExperianScore.md)
- [creditapp.module.MainProcess](creditapp.module.MainProcess.md)
