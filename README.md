# windows-new-pc
Scripts to quickly get going on a new Windows install

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
choco install -y 
    GoogleChrome 7zip `
    python nodejs rust git github-desktop gh vscode notepadplusplus ` 
    vnc-viewer tightvnc `
choco install drawio
