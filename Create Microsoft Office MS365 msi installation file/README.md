# WiX toolset 4 CLI: Create Microsoft Office MS365 msi installation file

<b>Downloads:</b>

 * [7-zip download page](https://www.7-zip.org/download.html)

<b>Objectives:</b>

* Create .MSI installation file for Microsoft Office installation

<b>Generate package guid:</b>

```powershell
[guid]::NewGuid().guid
```

<b>Create .MSI package:</b>

```powershell
wix build m365-wix.wxs
```