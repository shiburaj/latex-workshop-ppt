# Introduction to LaTex PPT
Basic introduction to LaTex and Sample Project Reports. [Click Here](https://github.com/shiburaj/latex-workshop-ppt/releases/download/v1/Final.pdf) to Download PPT

## Softwares for Latex
- [**Overleaf**](https://www.overleaf.com/)
- [**TexStudio**](https://www.texstudio.org/)

## Steps to Install TexStudio in RCOE Lab Computers
1. Goto Start menu and Run **PowerShell** as **Administrator**
2. Install **Chocolatey** using following command
```ps
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
3. Add local chocolatey server
```ps
choco source add -n nexus-choco -s http://nexus.rcoe.co.in/repository/choco/ --priority=1
```
4. Install **TexStudio** using chocolatey
```ps
choco install -y miktex texstudio
```

## Report Templates
- [**Synopsis Report Template**](https://github.com/shiburaj/latex-synopsis-report)
- [**Project Report Template**](https://github.com/shiburaj/latex-project-report)
