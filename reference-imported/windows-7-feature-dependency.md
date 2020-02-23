# Windows 7 Feature Dependency Reference

>The contents of this page were copied from the section in [Toolkit reference](https://docs.microsoft.com/en-us/configmgr/mdt/toolkit-reference). The content was modified to have better headers.

>TODO: fix links

 Table 8 lists the Windows 7 features, the parent feature, and any dependent features. You can use this information to determine which features and roles need to be installed to support a specific feature using the [Install Roles and Features](#InstallRolesandFeatures) and [Uninstall Roles and Features](#UninstallRolesandFeatures) task sequence steps.  

#### Table 8. Windows 7 Feature Dependency Reference  

|**Feature**|**Parent Feature**|**Dependent Features**|  
|-|-|-|  
|Windows Media® Center|Media Features|Might affect other Windows features|  
|Windows DVD Maker|Media Features|Might affect other Windows features|  
|Windows Media Player|Media Features|Might affect other Windows features|  
|Windows Search|N/A|Might affect other Windows features|  
|Internet Explorer (amd64)|N/A|Might affect other Windows features|  
|World Wide Web services|Microsoft Internet Information Services (IIS)|- Microsoft Message Queuing (MSMQ) HTTP support<br /><br /> - Windows Communication Foundation (WCF) HTTP activation|  
|IIS 6 WMI compatibility|IIS, Web management tools, IIS 6 management compatibility|IIS 6 scripting tooling|  
|Microsoft .NET extensibility|IIS, World Wide Web services, application development features|- Microsoft ASP.NET<br /><br /> - MSMQ HTTP support<br /><br /> - WCF HTTP activation|  
|Default document|IIS, World Wide Web services, common HTTP features|MSMQ HTTP support|  
|Directory browsing|IIS, World Wide Web services, common HTTP features|MSMQ HTTP support|  
|HTTP redirection|IIS, World Wide Web services, common HTTP features|MSMQ HTTP support|  
|Static content|IIS, World Wide Web services, common HTTP features|- Web-based Distributed Authoring and Versioning (WebDAV) publishing<br /><br /> - MSMQ HTTP support|  
|Custom logging|IIS, World Wide Web services, health and diagnostics|MSMQ HTTP support|  
|HTTP logging|IIS, World Wide Web services, health and diagnostics|MSMQ HTTP support|  
|ODBC logging|IIS, World Wide Web services, health and diagnostics|MSMQ HTTP support|  
|Request Monitor|IIS, World Wide Web services, health and diagnostics|MSMQ HTTP support|  
|Tracing|IIS, World Wide Web services, health and diagnostics|MSMQ HTTP support|  
|Static content compression|IIS, World Wide Web services, performance features|MSMQ HTTP support|  
|Security|IIS, World Wide Web services|- Microsoft .NET extensibility<br /><br /> - MSMQ HTTP support<br /><br /> - WCF HTTP activation|  
|Request Filtering|IIS, World Wide Web services, security|- Microsoft .NET extensibility<br /><br /> - MSMQ HTTP support<br /><br /> - WCF HTTP activation|  
|XPS Viewer|N/A|Might affect other Windows features|  