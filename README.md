# Windows Service Host
Hosting a .NET 5 WebAPI on a Windows Service

### Create the service

```bash
C:\>sc create HostedService binpath=C:\WindowsServiceHostTemplate\bin\Debug\net5.0\WindowsServiceHostTemplate.exe
[SC] CreateService SUCCESS

C:\WINDOWS\system32>sc start HostedService
```

### Navigate to the API

Navigate here -> <http://localhost:5050/weatherforecast> and you'll see the data
