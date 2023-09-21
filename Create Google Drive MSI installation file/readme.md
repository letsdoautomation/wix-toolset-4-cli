# WiX toolset 4 CLI
### Downloads and documentation
<b>Download links:</b> <br />
* [Google Drive](https://support.google.com/a/answer/7491144?hl=en#zippy=%2Cwindows)

How it works:
* We are installing MSI file
* MSI file is installing software

<b>Silent switches:</b>
```powershell
--silent --skip_launch_new --gsuite_shortcuts=false
```

<b>Generate package guid</b>
```powershell
[guid]::NewGuid().guid
```

<b>WiX build MSI package command</b>
```powershell
wix build "googledrive.wxs"
```

### WiX Toolset 4 CLI
[Windows Tools: Download and install .NET 7 SDK and WiXtoolset 4 CLI tool](https://youtu.be/ukrIlmadTjw) <br />
[Group Policy: Packaging EXE into MSI for Group Policy software deployment using WiX toolset CLI](https://youtu.be/pZ42XS2Ucsg) <br />

### PSEXEC
[Windows tools: Using PSEXEC for software deployment testing](https://youtu.be/9ywdTna_TLc) <br />