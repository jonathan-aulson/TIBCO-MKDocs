---
interface_name: creditapp.module.ExperianScore
process_file: bw-samples-master/bw-samples-master/TN2018/Apps/CreditAppService/CreditApp.module/Processes/creditapp/module/ExperianScore.bwp
source_hash: 97addc7d332ce08a7f08eb3602573cc2a6b1013be6d3fa4363d79271e98550b9
extracted_at: '2025-09-12T22:59:38.183289+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.807
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.07
  evidence_strength: 1.0
  inferred_fraction: 0.0
detected_format: process_xml
start_activity: ActivityOutputClass
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 0
---

## creditapp.module.ExperianScore — One-line summary
This process implements a REST service "creditapp.module.ExperianScore" at Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema that performs domain logic returns a structured response.

## What it does (specific steps)
- Receives a REST request (endpoint: /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema, method: Unknown).

## Why this matters (business view)
- Enables downstream systems to obtain a specific, structured result.
- Provides traceability via explicit logging and error handling paths.

## Interfaces exposed
- REST: Unknown /y54cuadtcxtfstqs3rux2gfdaxppoqgc/T1535409245354Converted/JsonSchema (evidence: {http://schemas.xmlsoap.org/wsdl/}import)
- REST: Unknown / (evidence: {http://schemas.xmlsoap.org/wsdl/}portType)
- REST: POST Unknown (evidence: {http://schemas.xmlsoap.org/wsdl/}operation)
- REST: GET Unknown (evidence: {http://schemas.xmlsoap.org/wsdl/}operation)
- REST: Unknown {http://tns.tibco.com/bw/json/1535671685533}ExperianResponseSchemaElement (evidence: {http://www.tibco.com/bpel/2007/extensions}ProcessInterface)
- REST: Unknown //0/@process/@activity/@activity/@activities.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.1 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.2 (evidence: element)

## Interdependency Map
- Related family processes: creditapp.module.EquifaxScore, creditapp.module.MainProcess

## Technical appendix
The process **creditapp.module.ExperianScore** consists of 71 activities connected by transitions.

### Activities
- ActivityName (xs:string)
- mimeHeaders (tns:mimeHeadersType)
- JobId (xs:string)
- ActivityException (tns:ActivityExceptionType)
- Header (tns:Header)
- RequestActivityOutput (tns:RequestActivityOutput)
- Class (xs:string)
- statusLine (tns:StatusLineType)
- Msg (xs:string)
- TrackingInfo (xs:string)
- HttpServerException (tns:HttpServerExceptionType)
- UnsupportedEncodingException (tns:UnsupportedEncodingExceptionType)
- MsgCode (xs:string)
- HttpClientException (tns:HttpClientExceptionType)
- ErrorReport (tns:ErrorReport)
- CorrelationValue (xs:string)
- RequestActivityInput (tns:RequestActivityInput)
- DynamicHeaders (tns:DynamicHeaders)
- JSONParserException (tns:JSONParserExceptionType)
- JSONTransformException (tns:JSONTransformExceptionType)
- httpClientResource (xsd:string)
- EngineName (xs:string)
- mimePart (tns:mimePartType)
- ActivityInputClass (tns:ActivityInputClassType)
- StackTrace (xs:string)
- FullClass (xs:string)
- ActivityTimedOutException (tns:BaseExceptionType)
- ActivityErrorData (tns:ActivityErrorDataType)
- JSONActivityException (tns:JSONActivityException)
- Data (tns:anydata)
- mimeEnvelopeElement (tns:mimeEnvelopeElementType)
- Headers (tns:outputHeadersType)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- ActivityOutputClass (tns:ActivityOutputClassType)
- ValidationException (tns:ValidationExceptionType)
- ProcessContext (tns:ProcessContext)
- headers (tns:HeadersType)
- JSONRestException (tns:JSONRestExceptionType)
- ApplicationName (xs:string)
- ProcessStack (xs:string)
- HttpException (tns:HttpExceptionType)
- CustomJobId (xs:string)
- FaultDetail (tns:FaultDetail)
- parameters (tns:parametersType)
- httpMessage (tns:HttpMessageType)
- HttpCommunicationException (tns:HttpCommunicationExceptionType)
- OptionalErrorReport (tns:OptionalErrorReport)
- JSONRenderException (tns:JSONRenderExceptionType)
- ProcessInstanceId (xs:string)
- HttpResponseException (tns:HttpResponseExceptionType)
- _processContext (bpws:variable)
- _error (bpws:variable)
- Start (bpws:variable)
- End-input (bpws:variable)
- SendHTTPRequest-input (bpws:variable)
- SendHTTPRequest (bpws:variable)
- _error_SendHTTPRequest (bpws:variable)
- RenderJSON-input (bpws:variable)
- RenderJSON (bpws:variable)
- _error_RenderJSON (bpws:variable)
- ParseJSON-input (bpws:variable)
- ParseJSON (bpws:variable)
- _error_ParseJSON (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- StartToSendHTTPRequest (bpws:link)
- SendHTTPRequestToEnd (bpws:link)
- RenderJSONToSendHTTPRequest (bpws:link)
- ParseJSONToEnd (bpws:link)
- End (tibex:activityExtension)
- config (properties)

## Related Documents
- [creditapp.module.EquifaxScore](creditapp.module.EquifaxScore.md)
- [creditapp.module.MainProcess](creditapp.module.MainProcess.md)
