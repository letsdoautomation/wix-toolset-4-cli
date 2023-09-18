# WiX toolset 4 CLI
### <b>Downloads and documentation</b>
<b>Download links:</b> <br />
* [Brave](https://github.com/brave/brave-browser) <br />

### <b>Software installation using Active Setup and RunOnce</b>
```mermaid
flowchart TD
    a["User signs-in to the computer"] --> b["Active Setup creates RunOnce registry entry"]
    b --> c[Users Desktop loads]
    c --> d["RunOnce will start software installation"]
```

<b>Generate package guid</b>
```powershell
[guid]::NewGuid().guid
```

<b>WiX build MSI package command</b>
```powershell
wix build .\Brave.wxs
```

### <b>WiX Toolset 4 CLI</b><br />
[Windows Tools: Download and install .NET 7 SDK and WiXtoolset 4 CLI tool](https://youtu.be/ukrIlmadTjw) <br />
[Group Policy: Packaging EXE into MSI for Group Policy software deployment using WiX toolset CLI](https://youtu.be/pZ42XS2Ucsg) <br />

### <b>Windows registry</b><br />
[Windows Registry: Run and RunOnce](https://youtu.be/zgFzCq5uEPw) <br />
[Windows Registry: Active Setup](https://youtu.be/HrVJ7wdvfmo) <br />

### <b>PSEXEC</b><br />
[Windows tools: Using PSEXEC for software deployment testing](https://youtu.be/9ywdTna_TLc) <br />