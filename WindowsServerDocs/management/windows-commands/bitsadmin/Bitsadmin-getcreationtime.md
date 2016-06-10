---
title: Bitsadmin getcreationtime
ms.custom: na
ms.prod: windows-server-2012
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: be409cb5-ce72-41d9-aafa-edd4e230fd14
---
# Bitsadmin getcreationtime
Retrieves the creation time for the specified job.

## Syntax

```
bitsadmin /GetCreationTime <Job>
```

## Parameters

|Parameter|Description|
|-------------|---------------|
|Job|The job's display name or GUID|

## <a name="BKMK_examples"></a>Examples
The following example retrieves the creation time for the job named *myDownloadJob*.

```
C:\>bitsadmin /GetCreationTime myDownloadJob
```

## Additional references
[Command-Line Syntax Key](../Command-Line-Syntax-Key.md)

