---
layout: post
title: Tibco Tracing!
---

properties in designer.tra

ALL TRACING:
Trace.Task.*=true
Trace.Startup=true
Trace.JC.*=true
Trace.Engine=true
Trace.Debug.*=true
bw.engine.showInput=true
bw.engine.showOutput=true

SOAP TRACING:
java.property.com.tibco.plugin.soap.trace.inbound=true
java.property.com.tibco.plugin.soap.trace.outbound=true
java.property.com.tibco.plugin.soap.trace.filename=c:/temp/soap.txt
java.property.com.tibco.plugin.soap.trace.pretty=true

DISABLE SOAP VALIDATION:
For "by passing" the parsing , Plaes add :
java.property.com.tibco.plugin.soap.SOAPSendReceiveActivity.NoOutputValidation=true
java.property.com.tibco.plugin.soap.SOAPSendReceiveActivity.NoInputValidation=true


