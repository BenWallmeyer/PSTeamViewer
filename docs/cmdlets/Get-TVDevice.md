---
external help file: PSTeamViewer-help.xml
Module Name: PSTeamViewer
online version: 
schema: 2.0.0
---

# Get-TVDevice

## SYNOPSIS
Get devices.

## SYNTAX

```
Get-TVDevice [[-Token] <String>] [[-OnlineState] <String>] [[-GroupID] <String>] [[-RemoteControlID] <String>]
```

## DESCRIPTION
Fetches devices from the TeamViewer API.

## EXAMPLES

### Example 1
```
PS C:\> Get-TVDevice
```

{{ Add example description here }}

## PARAMETERS

### -GroupID
{{Fill GroupID Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnlineState
{{Fill OnlineState Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: 
Accepted values: Online, Offline

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RemoteControlID
{{Fill RemoteControlID Description}}

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

### -Token
{{Fill Token Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

### None

## OUTPUTS

### TVDevice[]

## NOTES

## RELATED LINKS
