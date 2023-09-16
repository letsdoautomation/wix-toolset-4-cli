# WiX toolset 4 CLI
### Downloads and documentation
<b>Download links:</b> <br />
* [FileZilla](https://filezilla-project.org/download.php?platform=win64)

<b>Generate package guid</b>
```powershell
[guid]::NewGuid().guid
```

<b>WiX build MSI package command</b>
```powershell
wix build "FileZilla.wxs"
```