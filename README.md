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
