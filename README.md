# Windows New PC Quick Install

Scripts to quickly get going on a new Windows install.

## Disable UAC

😁

## Enable Hibernate and Set it as Default Power Option

Control Panel\Hardware and Sound\Power Options\System Settings
Change What the Power Buttons Do
Enable the Hibernate Option and change the power button

## Download Chocolatey

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Get Key Applications

```
choco install -y `
    GoogleChrome 7zip `
    python nodejs rust git github-desktop gh vscode notepadplusplus mobaxterm `
    vnc-viewer tightvnc
    drawio `


## Questionable Installs
```

choco install -y `
openoffice

```

```
