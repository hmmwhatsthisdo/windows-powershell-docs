---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: brianlic
author: brianlic-msft
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
external help file: microsoft.windows.appbackgroundtask.commands.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.date: 12/20/2016
ms.prod: w10
ms.technology: powershell-windows
ms.topic: reference
online version: 
schema: 2.0.0
title: Disable-AppBackgroundTaskDiagnosticLog
ms.assetid: 68CCA324-C329-44B5-BC42-E2FEE9256C9E
---

# Disable-AppBackgroundTaskDiagnosticLog

## SYNOPSIS
Disables background task logging in Event Viewer.

## SYNTAX

```
Disable-AppBackgroundTaskDiagnosticLog [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
The **Disable-AppBackgroundTaskDiagnosticLog** cmdlet disables background task logging in Event Viewer.
You must have administrator access to disable background task logging.

## EXAMPLES

### Example 1: Disable background task logging
```
PS C:\> Disable-AppBackgroundTaskDiagnosticLog
```

This command turns off background task logging in Event Viewer.

## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Enable-AppBackgroundTaskDiagnosticLog](./Enable-AppBackgroundTaskDiagnosticLog.md)

