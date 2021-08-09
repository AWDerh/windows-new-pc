# Windows New PC Quick Install

Scripts to quickly get going on a new Windows install.

## Download Chocolatey

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Get Key Applications

```
choco install -y `
    GoogleChrome 7zip google-backup-and-sync `
    python nodejs rust git github-desktop gh vscode notepadplusplus mobaxterm `
    vnc-viewer tightvnc `
    obs-studio openoffice `
    drawio `
```
