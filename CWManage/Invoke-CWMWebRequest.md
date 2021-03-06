# Invoke-CWMWebRequest
## SYNOPSIS
This function is used to handle all web requests to the ConnectWise Manage API.
## SYNTAX
```powershell
Invoke-CWMWebRequest [[-Arguments] <Object>] [[-MaxRetry] <Int32>] [<CommonParameters>]
```
## DESCRIPTION
This function is used to manage error handling with web requests.
It will also handle retries of failed attempts.
## PARAMETERS
### -Arguments &lt;Object&gt;
A splat object of web request parameters
```
Required                    false
Position                    1
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -MaxRetry &lt;Int32&gt;
The maximum number of retry attempts
```
Required                    false
Position                    2
Default value                5
Accept pipeline input       false
Accept wildcard characters  false
```
## NOTES
Author: Chris Taylor

Date: 10/10/2018 
