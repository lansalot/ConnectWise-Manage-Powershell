# Get-CWMCompanyNoteTypes
## SYNOPSIS
This function will list company note types based on conditions.
## SYNTAX
```powershell
Get-CWMCompanyNoteTypes [[-Condition] <String>] [[-orderBy] <Object>] [[-childconditions] <String>] [[-customfieldconditions] <String>] [[-page] <Int32>] [[-pageSize] <Int32>] [-all] [<CommonParameters>]
```
## PARAMETERS
### -Condition &lt;String&gt;
This is your search condition to return the results you desire.

Example:

(contact/name like "Fred%" and closedFlag = false) and dateEntered > [2015-12-23T05:53:27Z] or summary contains "test" AND  summary != "Some Summary"
```
Required                    false
Position                    1
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -orderBy &lt;Object&gt;
Choose which field to sort the results by
```
Required                    false
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -childconditions &lt;String&gt;
Allows searching arrays on endpoints that list childConditions under parameters
```
Required                    false
Position                    3
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -customfieldconditions &lt;String&gt;
Allows searching custom fields when customFieldConditions is listed in the parameters
```
Required                    false
Position                    4
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -page &lt;Int32&gt;
Used in pagination to cycle through results
```
Required                    false
Position                    5
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -pageSize &lt;Int32&gt;
Number of results returned per page (Defaults to 25)
```
Required                    false
Position                    6
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -all &lt;SwitchParameter&gt;
Return all results
```
Required                    false
Position                    named
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>Get-CWMCompanyNoteTypes -Condition "status/id IN (1,42,43,57)" -all

Will return all company notes that match the condition
```

## NOTES
Author: Chris Taylor

Date: <GET-DATE> 
## LINKS
http://labtechconsulting.com

https://developer.connectwise.com/products/manage/rest?a=Company&e=CompanyNoteTypes&o=GET
