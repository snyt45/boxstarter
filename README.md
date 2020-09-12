# boxstarter
# How to Use
## Install Chocolatey
Launch PowerShell prompt with "Run as Administrator".
```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
## Install Boxstarter
```
choco install -y boxstarter
```

## Launch Boxstarter Setup Script
```
BOXSTARTERSHELL
Install-BoxstarterPackage -PackageName https://github.com/miyamam/boxstarter/raw/master/boxstarter.txt
```

## Check the installation package
```
clist -lo
```
