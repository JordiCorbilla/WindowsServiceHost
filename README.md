# WindowsServiceHost
Host .NET 5 in a Windows Service

### Create the service

```bash
C:\>sc create HostedService binpath=C:\WindowsServiceHostTemplate\bin\Debug\net5.0\WindowsServiceHostTemplate.exe
[SC] CreateService SUCCESS

C:\WINDOWS\system32>sc start HostedService
```
