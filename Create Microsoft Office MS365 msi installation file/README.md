# WiX toolset 4 CLI: Create Microsoft Office MS365 MSI installation file

<b>Downloads</b>

* [Office Deployment Tool](https://www.microsoft.com/en-us/download/details.aspx?id=49117)

<b>Documentation:</b>

* [Overview of the Office Deployment Tool](https://learn.microsoft.com/en-us/deployoffice/overview-office-deployment-tool)
* [Configuration options for the Office Deployment Tool](https://learn.microsoft.com/en-us/deployoffice/office-deployment-tool-configuration-options)
* [List of Product IDs that are supported by the Office Deployment Tool for Click-to-Run](https://learn.microsoft.com/en-us/microsoft-365/troubleshoot/installation/product-ids-supported-office-deployment-click-to-run)

<b>Objectives:</b>

* Create .MSI installation file for Microsoft 365 Office installation

<b>Generate package guid:</b>

```powershell
[guid]::NewGuid().guid
```

<b>Create .MSI package:</b>

```powershell
wix build m365-wix.wxs
```

### Related videos

<b>WiX Toolset 4 CLI:</b>

[Windows Tools: Download and install .NET 7 SDK and WiXtoolset 4 CLI tool](https://youtu.be/ukrIlmadTjw) <br />
[Group Policy: Packaging EXE into MSI for Group Policy software deployment using WiX toolset CLI](https://youtu.be/pZ42XS2Ucsg) <br />
