# WiX toolset 4 CLI
### Downloads and documentation
Download link: [Adobe Acrobat Reader DC](https://get.adobe.com/reader/enterprise/) <br />

### Extract MSI files
```powershell
cmd /c D:\Downloads\AcroRdrDC2300320269_en_US.exe -sfx_o"D:\Downloads\Reader" -sfx_ne
```
### Create administrative installation point
```powershell
cmd /c msiexec /a "D:\Downloads\Reader\AcroRead.msi" TARGETDIR="D:\Downloads\Reader_deployment"
```
### Update administrative installation point
```powershell
cmd /c msiexec /a "D:\Downloads\Reader_deployment\AcroRead.msi" /p "D:\Downloads\Reader\AcroRdrDCUpd2300320269.msp" TARGETDIR="D:\Downloads\Reader_deployment"
```