---
layout: glossary
title: Invoke-VSChangeSetExecution
categories: glossary
label1: Category
data1: Documentation
label2: Depth
data2: Deep
---

# Invoke-VSChangeSetExecution

## SYNOPSIS
Executes a Change Set

## SYNTAX

```
Invoke-VSChangeSetExecution [-ChangeSetName] <String> [-StackName] <String> [[-ClientRequestToken] <String>]
 [[-ProfileName] <String>]
```

## DESCRIPTION
Executes a Change Set

## PARAMETERS

### -ChangeSetName
The name or ARN of the change set that you want use to update the specified stack.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StackName
If you specified the name of a change set, specify the stack name or ID (ARN) that is associated with the change set you want to execute.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ClientRequestToken
A unique identifier for this ExecuteChangeSet request.
Specify this token if you plan to retry requests so that AWS CloudFormation knows that you're not attempting to execute a change set to update a stack with the same name.
You might retry ExecuteChangeSet requests to ensure that AWS CloudFormation successfully received them.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProfileName
The name of the configuration profile to deploy the stack with.
Defaults to $env:AWS_PROFILE, if set.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 4
Default value: $env:AWS_PROFILE
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
