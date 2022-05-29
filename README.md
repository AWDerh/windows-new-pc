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
choco feature enable -n allowGlobalConfirmation
choco install -y GoogleChrome 7zip google-backup-and-sync discord
choco install -y python nodejs rust git github-desktop gh vscode notepadplusplus mobaxterm
choco install -y vnc-viewer tightvnc
choco install -y obs-studio openoffice
choco install -y drawio
choco install -y qbittorrent

git config --global user.email "abdul.derh@gmail.com"
git config --global user.name "Abdul Derh"
```

## Python configuration

```
python -m pip install pipenv pandas numpy matplotlib requests
```
