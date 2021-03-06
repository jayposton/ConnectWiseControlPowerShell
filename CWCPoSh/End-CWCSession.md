# End-CWCSession
## SYNOPSIS
Will end a given session.
## SYNTAX
```powershell
End-CWCSession [-Server] <Object> [-GUID] <Guid[]> [-User] <Object> [-Password] <Object> [-Type] <Object> [<CommonParameters>]
```
## DESCRIPTION
Will end a given access or support session.
## PARAMETERS
### -Server &lt;Object&gt;
The address to your Control server. Example 'https://control.labtechconsulting.com' or 'http://control.secure.me:8040'
```
Required                    true
Position                    1
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -GUID &lt;Guid[]&gt;
The GUID identifier for the session you wish to end.
```
Required                    true
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -User &lt;Object&gt;
User to authenticate against the Control server.
```
Required                    true
Position                    3
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Password &lt;Object&gt;
Password to authenticate against the Control server.
```
Required                    true
Position                    4
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -Type &lt;Object&gt;
The type of session Support/Access
```
Required                    true
Position                    5
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>End-CWCAccessSession -Server $Server -GUID $GUID -User $User -Password $Password

Will remove the given access session
```

## NOTES
Version:        1.0

Author:         Chris Taylor

Creation Date:  10/10/2018

Purpose/Change: Initial script development 
