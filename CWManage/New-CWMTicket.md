# New-CWMTicket
## SYNOPSIS
This function will create a new ticket.
## SYNTAX
```powershell
New-CWMTicket [[-id] <Int32>] [-summary] <String> [[-recordType] <Object>] [[-board] <Object>] [[-status] <Object>] [[-project] <Object>] [[-phase] <Object>] [[-wbsCode] <String>] [-company] <Object> [[-site] <Object>] [[-siteName] <String>] [[-addressLine1] <String>] [[-addressLine2] <String>] [[-city] <String>] [[-stateIdentifier] <String>] [[-zip] <String>] [[-country] <Object>] [[-contact] <Object>] [[-contactName] <String>] [[-contactPhoneNumber] <String>] [[-contactPhoneExtension] 

<String>] [[-contactEmailAddress] <String>] [[-type] <Object>] [[-subType] <Object>] [[-item] <Object>] [[-team] <Object>] [[-owner] <Object>] [[-priority] <Object>] [[-serviceLocation] <Object>] [[-source] <Object>] [[-requiredDate] <String>] [[-budgetHours] <Decimal>] [[-opportunity] <Object>] [[-agreement] <Object>] [[-severity] <Int32>] [[-impact] <Int32>] [[-externalXRef] <String>] [[-poNumber] <String>] [[-knowledgeBaseCategoryId] <Int32>] [[-knowledgeBaseSubCategoryId] <Int32>] 

[[-allowAllClientsPortalView] <Boolean>] [[-customerUpdatedFlag] <Boolean>] [[-automaticEmailContactFlag] <Boolean>] [[-automaticEmailResourceFlag] <Boolean>] [[-automaticEmailCcFlag] <Boolean>] [[-automaticEmailCc] <String>] [[-initialDescription] <String>] [[-initialInternalAnalysis] <String>] [[-initialResolution] <String>] [[-contactEmailLookup] <String>] [[-processNotifications] <Boolean>] [[-skipCallback] <Boolean>] [[-closedDate] <String>] [[-closedBy] <String>] [[-closedFlag] 

<Boolean>] [[-dateEntered] <String>] [[-enteredBy] <String>] [[-actualHours] <Decimal>] [[-approved] <Boolean>] [[-subBillingMethod] <Object>] [[-subBillingAmount] <Decimal>] [[-subDateAccepted] <String>] [[-dateResolved] <String>] [[-dateResplan] <String>] [[-dateResponded] <String>] [[-resolveMinutes] <Int32>] [[-resPlanMinutes] <Int32>] [[-respondMinutes] <Int32>] [[-isInSla] <Boolean>] [[-knowledgeBaseLinkId] <Int32>] [[-resources] <String>] [[-parentTicketId] <Int32>] [[-hasChildTicket] 

<Boolean>] [[-knowledgeBaseLinkType] <Object>] [[-billTime] <Object>] [[-billExpenses] <Object>] [[-billProducts] <Object>] [[-predecessorType] <Object>] [[-predecessorId] <Int32>] [[-predecessorClosedFlag] <Boolean>] [[-lagDays] <Int32>] [[-lagNonworkingDaysFlag] <Boolean>] [[-estimatedStartDate] <String>] [[-duration] <Int32>] [[-locationId] <Int32>] [[-businessUnitId] <Int32>] [[-mobileGuid] <Guid>] [[-sla] <Object>] [[-currency] <Object>] [[-_info] <Object>] [[-customFields] <Object>] 

[<CommonParameters>]
```
## PARAMETERS
### -id &lt;Int32&gt;

```
Required                    false
Position                    1
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -summary &lt;String&gt;

```
Required                    true
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -recordType &lt;Object&gt;

```
Required                    false
Position                    3
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -board &lt;Object&gt;

```
Required                    false
Position                    4
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -status &lt;Object&gt;

```
Required                    false
Position                    5
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -project &lt;Object&gt;

```
Required                    false
Position                    6
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -phase &lt;Object&gt;

```
Required                    false
Position                    7
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -wbsCode &lt;String&gt;

```
Required                    false
Position                    8
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -company &lt;Object&gt;

```
Required                    true
Position                    9
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -site &lt;Object&gt;

```
Required                    false
Position                    10
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -siteName &lt;String&gt;

```
Required                    false
Position                    11
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -addressLine1 &lt;String&gt;

```
Required                    false
Position                    12
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -addressLine2 &lt;String&gt;

```
Required                    false
Position                    13
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -city &lt;String&gt;

```
Required                    false
Position                    14
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -stateIdentifier &lt;String&gt;

```
Required                    false
Position                    15
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -zip &lt;String&gt;

```
Required                    false
Position                    16
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -country &lt;Object&gt;

```
Required                    false
Position                    17
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -contact &lt;Object&gt;

```
Required                    false
Position                    18
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -contactName &lt;String&gt;

```
Required                    false
Position                    19
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -contactPhoneNumber &lt;String&gt;

```
Required                    false
Position                    20
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -contactPhoneExtension &lt;String&gt;

```
Required                    false
Position                    21
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -contactEmailAddress &lt;String&gt;

```
Required                    false
Position                    22
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -type &lt;Object&gt;

```
Required                    false
Position                    23
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -subType &lt;Object&gt;

```
Required                    false
Position                    24
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -item &lt;Object&gt;

```
Required                    false
Position                    25
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -team &lt;Object&gt;

```
Required                    false
Position                    26
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -owner &lt;Object&gt;

```
Required                    false
Position                    27
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -priority &lt;Object&gt;

```
Required                    false
Position                    28
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -serviceLocation &lt;Object&gt;

```
Required                    false
Position                    29
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -source &lt;Object&gt;

```
Required                    false
Position                    30
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -requiredDate &lt;String&gt;

```
Required                    false
Position                    31
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -budgetHours &lt;Decimal&gt;

```
Required                    false
Position                    32
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -opportunity &lt;Object&gt;

```
Required                    false
Position                    33
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -agreement &lt;Object&gt;

```
Required                    false
Position                    34
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -severity &lt;Int32&gt;

```
Required                    false
Position                    35
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -impact &lt;Int32&gt;

```
Required                    false
Position                    36
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -externalXRef &lt;String&gt;

```
Required                    false
Position                    37
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -poNumber &lt;String&gt;

```
Required                    false
Position                    38
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -knowledgeBaseCategoryId &lt;Int32&gt;

```
Required                    false
Position                    39
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -knowledgeBaseSubCategoryId &lt;Int32&gt;

```
Required                    false
Position                    40
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -allowAllClientsPortalView &lt;Boolean&gt;

```
Required                    false
Position                    41
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -customerUpdatedFlag &lt;Boolean&gt;

```
Required                    false
Position                    42
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -automaticEmailContactFlag &lt;Boolean&gt;

```
Required                    false
Position                    43
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -automaticEmailResourceFlag &lt;Boolean&gt;

```
Required                    false
Position                    44
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -automaticEmailCcFlag &lt;Boolean&gt;

```
Required                    false
Position                    45
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -automaticEmailCc &lt;String&gt;

```
Required                    false
Position                    46
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -initialDescription &lt;String&gt;

```
Required                    false
Position                    47
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -initialInternalAnalysis &lt;String&gt;

```
Required                    false
Position                    48
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -initialResolution &lt;String&gt;

```
Required                    false
Position                    49
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -contactEmailLookup &lt;String&gt;

```
Required                    false
Position                    50
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -processNotifications &lt;Boolean&gt;

```
Required                    false
Position                    51
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -skipCallback &lt;Boolean&gt;

```
Required                    false
Position                    52
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -closedDate &lt;String&gt;

```
Required                    false
Position                    53
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -closedBy &lt;String&gt;

```
Required                    false
Position                    54
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -closedFlag &lt;Boolean&gt;

```
Required                    false
Position                    55
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -dateEntered &lt;String&gt;

```
Required                    false
Position                    56
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -enteredBy &lt;String&gt;

```
Required                    false
Position                    57
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -actualHours &lt;Decimal&gt;

```
Required                    false
Position                    58
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -approved &lt;Boolean&gt;

```
Required                    false
Position                    59
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -subBillingMethod &lt;Object&gt;

```
Required                    false
Position                    60
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -subBillingAmount &lt;Decimal&gt;

```
Required                    false
Position                    61
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -subDateAccepted &lt;String&gt;

```
Required                    false
Position                    62
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -dateResolved &lt;String&gt;

```
Required                    false
Position                    63
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -dateResplan &lt;String&gt;

```
Required                    false
Position                    64
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -dateResponded &lt;String&gt;

```
Required                    false
Position                    65
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -resolveMinutes &lt;Int32&gt;

```
Required                    false
Position                    66
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -resPlanMinutes &lt;Int32&gt;

```
Required                    false
Position                    67
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -respondMinutes &lt;Int32&gt;

```
Required                    false
Position                    68
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -isInSla &lt;Boolean&gt;

```
Required                    false
Position                    69
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -knowledgeBaseLinkId &lt;Int32&gt;

```
Required                    false
Position                    70
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -resources &lt;String&gt;

```
Required                    false
Position                    71
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -parentTicketId &lt;Int32&gt;

```
Required                    false
Position                    72
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -hasChildTicket &lt;Boolean&gt;

```
Required                    false
Position                    73
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -knowledgeBaseLinkType &lt;Object&gt;

```
Required                    false
Position                    74
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -billTime &lt;Object&gt;

```
Required                    false
Position                    75
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -billExpenses &lt;Object&gt;

```
Required                    false
Position                    76
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -billProducts &lt;Object&gt;

```
Required                    false
Position                    77
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -predecessorType &lt;Object&gt;

```
Required                    false
Position                    78
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -predecessorId &lt;Int32&gt;

```
Required                    false
Position                    79
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -predecessorClosedFlag &lt;Boolean&gt;

```
Required                    false
Position                    80
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -lagDays &lt;Int32&gt;

```
Required                    false
Position                    81
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -lagNonworkingDaysFlag &lt;Boolean&gt;

```
Required                    false
Position                    82
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -estimatedStartDate &lt;String&gt;

```
Required                    false
Position                    83
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -duration &lt;Int32&gt;

```
Required                    false
Position                    84
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -locationId &lt;Int32&gt;

```
Required                    false
Position                    85
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -businessUnitId &lt;Int32&gt;

```
Required                    false
Position                    86
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -mobileGuid &lt;Guid&gt;

```
Required                    false
Position                    87
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -sla &lt;Object&gt;

```
Required                    false
Position                    88
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -currency &lt;Object&gt;

```
Required                    false
Position                    89
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -_info &lt;Object&gt;

```
Required                    false
Position                    90
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -customFields &lt;Object&gt;

```
Required                    false
Position                    91
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>$Ticket = @{

'identifier' = $Product.offerName
    'description' = $Product.offerName
    'subcategory' = @{id = 152}
    'type' = @{id = 47}
    'customerDescription' = $Product.offerName
    'cost' = $Product.unitPrice
    'price' = $Price
    'manufacturerPartNumber' = $Product.offerName
    'manufacturer' = $Manufacturer
    'productClass' = 'Agreement'
    'taxableFlag' = $true
}
New-CWMTicket @Ticket
```

## NOTES
Author: Chris Taylor

Date: 8/22/2018 
## LINKS
http://labtechconsulting.com

https://developer.connectwise.com/manage/rest?a=Service&e=Tickets&o=CREATE
