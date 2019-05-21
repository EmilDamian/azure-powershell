---
external help file: Az.WebSite-help.xml
Module Name: Az.WebSite
online version: https://docs.microsoft.com/en-us/powershell/module/az.website/get-azwebappvnetconnectionslot
schema: 2.0.0
---

# Get-AzWebAppVnetConnectionSlot

## SYNOPSIS
Gets a virtual network the app (or deployment slot) is connected to by name.

## SYNTAX

### List (Default)
```
Get-AzWebAppVnetConnectionSlot -Name <String> -ResourceGroupName <String> -Slot <String>
 -SubscriptionId <String[]> [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### Get
```
Get-AzWebAppVnetConnectionSlot -Name <String> -ResourceGroupName <String> -Slot <String>
 -SubscriptionId <String[]> -VnetName <String> [-DefaultProfile <PSObject>] [<CommonParameters>]
```

### GetViaIdentity
```
Get-AzWebAppVnetConnectionSlot -InputObject <IWebSiteIdentity> [-DefaultProfile <PSObject>]
 [<CommonParameters>]
```

## DESCRIPTION
Gets a virtual network the app (or deployment slot) is connected to by name.

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: System.Management.Automation.PSObject
Parameter Sets: (All)
Aliases: AzureRMContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.WebSite.Models.IWebSiteIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Name
Name of the app.

```yaml
Type: System.String
Parameter Sets: List, Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
Name of the resource group to which the resource belongs.

```yaml
Type: System.String
Parameter Sets: List, Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Slot
Name of the deployment slot.
If a slot is not specified, the API will get virtual network connections for the production slot.

```yaml
Type: System.String
Parameter Sets: List, Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubscriptionId
Your Azure subscription ID.
This is a GUID-formatted string (e.g.
00000000-0000-0000-0000-000000000000).

```yaml
Type: System.String[]
Parameter Sets: List, Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VnetName
Name of the virtual network.

```yaml
Type: System.String
Parameter Sets: Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.WebSite.Models.Api20180201.IVnetInfo
## NOTES

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/az.website/get-azwebappvnetconnectionslot](https://docs.microsoft.com/en-us/powershell/module/az.website/get-azwebappvnetconnectionslot)
