---
title: How to Modify Client Configuration by Using Windows PowerShell (Windows 10)
description: How to Modify Client Configuration by Using Windows PowerShell
author: MaggiePucciEvans
ms.pagetype: mdop, appcompat, virtualization
ms.mktglfcycl: deploy
ms.sitesec: library
ms.prod: w10
---


# How to Modify Client Configuration by Using Windows PowerShell

**Applies to**
-   Windows 10, version 1607

Use the following procedure to configure the App-V client configuration.

1.  To configure the client settings using Windows PowerShell, use the **Set-AppvClientConfiguration** cmdlet. For more information about installing Windows PowerShell, and a list of cmdlets see, [How to Load the Windows PowerShell Cmdlets for App-V and Get Cmdlet Help](appv-load-the-powershell-cmdlets-and-get-cmdlet-help.md).

2.  To modify the client configuration, open a Windows PowerShell Command prompt and run **Set-AppvClientConfiguration** with any required parameters. For example:

    `$config = Get-AppvClientConfiguration`

    `Set-AppvClientConfiguration $config`

    `Set-AppvClientConfiguration –Name1 MyConfig –Name2 “xyz”`


## Have a suggestion for App-V? 
 
Add or vote on suggestions on the [Application Virtualization feedback site](http://appv.uservoice.com/forums/280448-microsoft-application-virtualization).<br>For App-V issues, use the [App-V TechNet Forum](https://social.technet.microsoft.com/Forums/en-US/home?forum=mdopappv).

## Related topics

[Operations for App-V](appv-operations.md)
