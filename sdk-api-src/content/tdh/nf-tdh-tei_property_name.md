---
UID: NF:tdh.TEI_PROPERTY_NAME
tech.root: ETW
title: TEI_PROPERTY_NAME (tdh.h)
ms.date: 12/05/2022
ms.keywords: TEI_PROPERTY_NAME
targetos: Windows
description: Macro that retrieves the Trace Event Information (TEI) property name.
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: tdh.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.target-type: Windows
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - 
api_location:
 - tdh.h
api_name:
 - TEI_PROPERTY_NAME
f1_keywords:
 - TEI_PROPERTY_NAME
 - tdh/TEI_PROPERTY_NAME
dev_langs:
 - c++
helpviewer_keywords:
 - TEI_PROPERTY_NAME
---

# TEI_PROPERTY_NAME function (tdh.h)

## -description

Macro that retrieves the Trace Event Information (TEI) property name.

## -parameters

### -param EventInfo [in]

A [TRACE_EVENT_INFO structure](ns-tdh-trace_event_info.md) that contains the event information. To get this structure, call the [TdhGetEventInformation function](nf-tdh-tdhgeteventinformation.md).

### -param Property

An [EVENT_PROPERTY_INFO structure](ns-tdh-event_property_info.md) that contains the event property information.

## -returns

The TEI property name, or NULL.

## -remarks

## -see-also
