---
title: "close-worddocument"
excerpt: "Describe purpose of "Close-WordDocument" in 1-2 sentences."
category: "help"
---

# Close-WordDocument
**Module** WordDoc

## SYNOPSIS
Describe purpose of "Close-WordDocument" in 1-2 sentences.

## DESCRIPTION
Add a more complete description of what the function does.

## SYNTAX

```
Close-WordDocument [[-SaveOptions] {wdDoNotSaveChanges | wdPromptToSaveChanges | 
wdSaveChanges}] [[-OriginalFormat] {wdWordDocument | wdOriginalDocumentFormat | 
wdPromptUser}] [[-WordDocument] <Document>] [[-WordInstance] <Application>] 
[<CommonParameters>]
```


## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------


```
PS C:\>Close-WordDocument -WordInstance Value -WordDocument Value
```

Describe what this call does


## PARAMETERS

### SaveOptions



```
Type WdSaveOptions
Parameter Sets: 
Aliases: 
Required: false
Position: 1
Default Value:wdPromptToSaveChanges
Accept pipeline input: false
```
### OriginalFormat

Describe parameter -wdPromptUser.

```
Type WdOriginalFormat
Parameter Sets: 
Aliases: 
Required: false
Position: 2
Default Value:wdPromptUser
Accept pipeline input: false
```
### WordDocument

Describe parameter -WordDocument.

```
Type Document
Parameter Sets: 
Aliases: 
Required: false
Position: 3
Default Value:$Script:WordDocument
Accept pipeline input: false
```
### WordInstance

Describe parameter -WordInstance.

```
Type Application
Parameter Sets: 
Aliases: 
Required: false
Position: 4
Default Value:$Script:WordInstance
Accept pipeline input: false
```
### CommonParameters

This function only supports -verbose

## RELATED LINKS


https://shanehoey.github.io/worddoc/docs/close-worddocument
