"# Cross-Platform-App-Installation" 

# Windows User 

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
choco install -y nodejs-lts openjdk11
```

### Install Andriod Studio 
  - Set sdk
  - set jre
  - set Android Virtual Device
