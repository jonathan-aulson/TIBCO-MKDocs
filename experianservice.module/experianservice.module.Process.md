---
interface_name: experianservice.module.Process
process_file: bw-samples-master/bw-samples-master/TN2018/Apps/ExperianDemoService/ExperianService.module/Processes/experianservice/module/Process.bwp
source_hash: 3c13a308d5c13964103153751d0b17936b57038f8ae145d76240ff50bf5c3bff
extracted_at: '2025-09-12T22:59:38.032042+00:00'
tool_version: bw-orchestrator-1.3.0
explanation_source: llm
documentation_status: auto_generated
review_status: pending
confidence_score: 0.803
confidence_subscores:
  parsed: 0.5
  known_types_coverage: 0.0
  transition_integrity: 1.0
  role_coverage: 0.034
  evidence_strength: 1.0
  inferred_fraction: 0.0
detected_format: process_xml
start_activity: ActivityOutputClass
enrichment_summary:
  business_scaffold: 7
  interdependencies_slice: 5
  extrapolations: 0
---

## experianservice.module.Process — One-line summary
This process implements a REST service "experianservice.module.Process" at Unknown /creditscore that performs domain logic returns a structured response.

## What it does (specific steps)
- Receives a REST request (endpoint: /creditscore, method: Unknown).

## Why this matters (business view)
- Enables downstream systems to obtain a specific, structured result.
- Provides traceability via explicit logging and error handling paths.

## Interfaces exposed
- REST: Unknown /creditscore (evidence: {http://schemas.xmlsoap.org/wsdl/}portType)
- REST: POST Unknown (evidence: {http://schemas.xmlsoap.org/wsdl/}operation)
- REST: Unknown //0/@process (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.0 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.1 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.2 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.3 (evidence: element)
- REST: Unknown //0/@process/@activity/@activity/@activities.4 (evidence: element)

## Technical appendix
The process **experianservice.module.Process** consists of 87 activities connected by transitions.

### Activities
- StackTrace (xs:string)
- Class (xs:string)
- Data (tns:anydata)
- Msg (xs:string)
- JSONTransformException (tns:JSONTransformExceptionType)
- MsgCode (xs:string)
- Context (tns:ContextType)
- ActivityErrorData (tns:ActivityErrorDataType)
- InvalidTimeZoneException (tns2:InvalidTimeZoneExceptionType)
- FullClass (xs:string)
- ProcessInstanceId (xs:string)
- ProcessStarterOutput (tns:HTTPEventSourceOutputType)
- Certificate (tns:CertificateType)
- ActivityException (tns:ActivityExceptionType)
- JSONRestException (tns:JSONRestExceptionType)
- JDBCSQLException (tns2:JDBCSQLExceptionType)
- CustomJobId (xs:string)
- input (tns:WaitForHTTPRequestInputType)
- ProcessContext (tns:ProcessContext)
- ProcessStack (xs:string)
- JobId (xs:string)
- UnsupportedEncodingException (tns:UnsupportedEncodingExceptionType)
- DynamicHeaders (tns:dynamicHeadersType)
- ErrorReport (tns:ErrorReport)
- jdbcProperty (xsd:string)
- JSONActivityException (tns:JSONActivityException)
- Headers (tns:headersType)
- LoginTimedOutException (tns2:LoginTimedOutExceptionType)
- OptionalErrorReport (tns:OptionalErrorReport)
- ActivityOutputClass (tns:ActivityOutputClassType)
- ActivityInputClass (tns:ActivityInputClassType)
- mimePart (tns:mimePartType)
- Header (tns:dynamicHeadersTypeDetails)
- TrackingInfo (xs:string)
- FaultDetail (tns:FaultDetail)
- HttpResponseException (tns:HttpResponseExceptionType)
- SecurityContext (tns:SecurityContextType)
- ResponseActivityInput (tns:ActivityInputType)
- JDBCPluginException (tns2:JDBCPluginExceptionType)
- UsernamePasswordToken (tns:UsernamePasswordTokenType)
- JDBCConnectionNotFoundException (tns2:JDBCConnectionNotFoundExceptionType)
- HttpException (tns:HttpExceptionType)
- X509Certificate (tns:X509CertificateType)
- JSONRenderException (tns:JSONRenderExceptionType)
- CorrelationValue (xs:string)
- ActivityTimedOutException (tns:BaseExceptionType)
- statusLine (tns:StatusLineType)
- InvalidSQLTypeException (tns2:InvalidSQLTypeExceptionType)
- CertificateToken (tns:CertificateTokenType)
- httpMessage (tns:HttpMessageType)
- mimeEnvelopeElement (tns:mimeEnvelopeElementType)
- HttpServerException (tns:HttpServerExceptionType)
- ValidationException (tns:ValidationExceptionType)
- JSONParserException (tns:JSONParserExceptionType)
- HttpClientException (tns:HttpClientExceptionType)
- mimeHeaders (tns:mimeHeadersType)
- httpConnectorResource (xsd:string)
- DuplicateKeyException (tns:DuplicateKeyExceptionType)
- CertificateChain (tns:CertificateChainType)
- DuplicatedFieldNameException (tns2:DuplicatedFieldNameExceptionType)
- ApplicationName (xs:string)
- ActivityName (xs:string)
- HttpCommunicationException (tns:HttpCommunicationExceptionType)
- EngineName (xs:string)
- headers (tns:HeadersType)
- _processContext (bpws:variable)
- HTTPReceiver (bpws:variable)
- SendHTTPResponse-input (bpws:variable)
- _error_SendHTTPResponse (bpws:variable)
- _error (bpws:variable)
- JDBCQuery-input (bpws:variable)
- JDBCQuery (bpws:variable)
- _error_JDBCQuery (bpws:variable)
- ParseJSON-input (bpws:variable)
- ParseJSON (bpws:variable)
- _error_ParseJSON (bpws:variable)
- RenderJSON-input (bpws:variable)
- RenderJSON (bpws:variable)
- _error_RenderJSON (bpws:variable)
- scope (bpws:scope)
- flow (bpws:flow)
- HTTPReceiverToSendHTTPResponse (bpws:link)
- JDBCQueryToSendHTTPResponse (bpws:link)
- ParseJSONToJDBCQuery (bpws:link)
- RenderJSONToSendHTTPResponse (bpws:link)
- config (properties)
- SendHTTPResponse (tibex:activityExtension)
