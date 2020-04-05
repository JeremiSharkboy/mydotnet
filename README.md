# For learning purposes only

This repository is only for educational purposes

Canonical repo https://gitlab.com/dotnetstudygroup/mydotnet
git@gitlab.com:dotnetstudygroup/mydotnet.git

```powershell
PowerShell 7.0.0
Copyright (c) Microsoft Corporation. All rights reserved.

https://aka.ms/powershell
Type 'help' to get help.

PS C:\Users\hadak\Documents\source\mydotnet> dotnet --info
.NET Core SDK (reflecting any global.json):
 Version:   5.0.100-preview.2.20176.6
 Commit:    d752c3e07b

Runtime Environment:
 OS Name:     Windows
 OS Version:  10.0.18363
 OS Platform: Windows
 RID:         win10-x64
 Base Path:   C:\Program Files\dotnet\sdk\5.0.100-preview.2.20176.6\

Host (useful for support):
  Version: 5.0.0-preview.2.20160.6
  Commit:  d12f79a4d1

.NET Core SDKs installed:
  5.0.100-preview.2.20176.6 [C:\Program Files\dotnet\sdk]

.NET Core runtimes installed:
  Microsoft.AspNetCore.App 5.0.0-preview.2.20167.3 [C:\Program Files\dotnet\shared\Microsoft.AspNetCore.App]
  Microsoft.NETCore.App 5.0.0-preview.2.20160.6 [C:\Program Files\dotnet\shared\Microsoft.NETCore.App]
  Microsoft.WindowsDesktop.App 5.0.0-preview.2.20160.6 [C:\Program Files\dotnet\shared\Microsoft.WindowsDesktop.App]

To install additional .NET Core runtimes or SDKs:
  https://aka.ms/dotnet-download
PS C:\Users\hadak\Documents\source\mydotnet> 
```

```bash
[kushal@ideapadflex-kushal ~]$ cd ~/src/
[kushal@ideapadflex-kushal src]$ git clone git@github.com:kusl/mydotnet.git
Cloning into 'mydotnet'...
remote: Enumerating objects: 93, done.
remote: Counting objects: 100% (93/93), done.
remote: Compressing objects: 100% (49/49), done.
remote: Total 93 (delta 37), reused 86 (delta 30), pack-reused 0
Receiving objects: 100% (93/93), 18.50 KiB | 3.08 MiB/s, done.
Resolving deltas: 100% (37/37), done.
[kushal@ideapadflex-kushal src]$ cd mydotnet/
[kushal@ideapadflex-kushal mydotnet]$ dotnet build
Microsoft (R) Build Engine version 16.5.0+d4cbfca49 for .NET Core
Copyright (C) Microsoft Corporation. All rights reserved.

/usr/share/dotnet/sdk/3.1.201/Sdks/Microsoft.NET.Sdk/targets/Microsoft.NET.TargetFrameworkInference.targets(127,5): error NETSDK1045: The current .NET SDK does not support targeting .NET Core 5.0.  Either target .NET Core 3.1 or lower, or use a version of the .NET SDK that supports .NET Core 5.0. [/home/kushal/src/mydotnet/MyConsole/MyConsole.csproj]
/usr/share/dotnet/sdk/3.1.201/Sdks/Microsoft.NET.Sdk/targets/Microsoft.NET.TargetFrameworkInference.targets(127,5): error NETSDK1045: The current .NET SDK does not support targeting .NET Core 5.0.  Either target .NET Core 3.1 or lower, or use a version of the .NET SDK that supports .NET Core 5.0. [/home/kushal/src/mydotnet/MyXunitTests/MyXunitTests.csproj]

Build FAILED.

/usr/share/dotnet/sdk/3.1.201/Sdks/Microsoft.NET.Sdk/targets/Microsoft.NET.TargetFrameworkInference.targets(127,5): error NETSDK1045: The current .NET SDK does not support targeting .NET Core 5.0.  Either target .NET Core 3.1 or lower, or use a version of the .NET SDK that supports .NET Core 5.0. [/home/kushal/src/mydotnet/MyConsole/MyConsole.csproj]
/usr/share/dotnet/sdk/3.1.201/Sdks/Microsoft.NET.Sdk/targets/Microsoft.NET.TargetFrameworkInference.targets(127,5): error NETSDK1045: The current .NET SDK does not support targeting .NET Core 5.0.  Either target .NET Core 3.1 or lower, or use a version of the .NET SDK that supports .NET Core 5.0. [/home/kushal/src/mydotnet/MyXunitTests/MyXunitTests.csproj]
    0 Warning(s)
    2 Error(s)

Time Elapsed 00:00:01.59
[kushal@ideapadflex-kushal mydotnet]$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
[kushal@ideapadflex-kushal mydotnet]$ code -r
[kushal@ideapadflex-kushal mydotnet]$ code -r .
[kushal@ideapadflex-kushal mydotnet]$ dotnet --info
.NET Core SDK (reflecting any global.json):
 Version:   3.1.201
 Commit:    b1768b4ae7

Runtime Environment:
 OS Name:     fedora
 OS Version:  31
 OS Platform: Linux
 RID:         fedora.31-x64
 Base Path:   /usr/share/dotnet/sdk/3.1.201/

Host (useful for support):
  Version: 3.1.3
  Commit:  4a9f85e9f8

.NET Core SDKs installed:
  3.1.201 [/usr/share/dotnet/sdk]

.NET Core runtimes installed:
  Microsoft.AspNetCore.App 3.1.3 [/usr/share/dotnet/shared/Microsoft.AspNetCore.App]
  Microsoft.NETCore.App 3.1.3 [/usr/share/dotnet/shared/Microsoft.NETCore.App]

To install additional .NET Core runtimes or SDKs:
  https://aka.ms/dotnet-download
[kushal@ideapadflex-kushal mydotnet]$ 

```