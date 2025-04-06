# Context-Menu-Windows
[<img src='https://github.com/shovoalways/Context-Menu-Windows/blob/main/img/image.png?raw=true' alt='Ali Hossain'>](https://github.com/shovoalways/)

Win+ R 👉 regedit

Registry Path:
Computer\HKEY_CURRENT_USER\SOFTWARE\CLASSES\CLSID
Keys: {86ca1aa0-34aa-4e8b-a509-50c905bae2a2}
Sub-key: InprocServer32

Default SHOULD BE BLANK😂



Windows Security Issue Problem Fix.
Pwoershell
Get-AppxPackage Microsoft.SecHealthUI -AllUsers | Reset-AppxPackage



Try disabling Fast Startup in Windows. Let me find the instructions.

Edit: In Windows, press Win+R > powercfg.cpl > OK > Choose what the power buttons do > Change settings that are currently unavailable, then uncheck "Turn on fast startup". Save changes and restart (not shutdown) the PC.
