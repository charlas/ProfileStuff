# Profile Stuff

# Terminal Icons

Install-Module -Name Terminal-Icons -Repository PSGallery

# Oh-My-Posh

Set-ExecutionPolicy Bypass -Scope Process -Force; Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://ohmyposh.dev/install.ps1'))

# PSReadline

Install-Module -Name PowerShellGet -Force

# PSColors

Install-Module PSColors -Scope CurrentUser -AllowClobber

# PoshGit

PowerShellGet\Install-Module posh-git -Scope CurrentUser -Force

# VSC Extensions

[aslamanver.vsc-export](https://marketplace.visualstudio.com/items?itemName=aslamanver.vsc-export) < use this to do initial sync, then Sync on github to pull config
