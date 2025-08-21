ATSocketsHttpHandler:
===========================
ATSocketsHttpHandler is a backport of SocketsHttpHandler to .NET Standard 2.0.

Features added to ATSocketsHttpHandler:
=============================================
• .NET Standard 2.0 compatibility (.NET Framework 4.7.2 is supported)  
• ConnectCallback property - allows configuration of various socket options (TCP Keepalive, etc.)  

Features missing from ATSocketsHttpHandler:
=============================================
• Windows Authentication (NLTM & Kerberos)  
• Operating System proxy settings detection  

Using ATSocketsHttpHandler:
=================================
HttpClient client = new HttpClient(new ATSocketsHttpHandler())  
 
Releases:
=========
Releases are available via [NuGet.org](https://www.nuget.org/packages/ATSocketsHttpHandler)  

Contact:
========
If you have any question, feel free to contact me.  
Shriram <shri8858@gmail.com>  
