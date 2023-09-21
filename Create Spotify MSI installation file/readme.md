# WiX toolset 4 CLI
### <b>Downloads and documentation</b>
Download links:
* [Spotify](https://www.spotify.com/de-en/download/windows/)
* [Spotify Offline Installer](https://download.scdn.co/SpotifyFullSetup.exe)

Actions performed by MSI file:
* Software installation file placed in C:\ProgramData\\_packages\GUID
* Active Setup registry key created

Software installation flow using Active Setup and RunOnce:

```mermaid
flowchart TD
    a["User signs-in to the computer"] --> b["Active Setup creates RunOnce registry entry"]
    b --> c[Users Desktop loads]
    c --> d["RunOnce will start software installation"]
```

Silent switches:
```powershell
/Silent
```

Generate package guid:
```powershell
[guid]::NewGuid().guid
```

WiX build MSI package command:
```powershell
wix build .\Spotify.wxs
```

### <b>WiX Toolset 4 CLI</b>
[Windows Tools: Download and install .NET 7 SDK and WiXtoolset 4 CLI tool](https://youtu.be/ukrIlmadTjw) <br />
[Group Policy: Packaging EXE into MSI for Group Policy software deployment using WiX toolset CLI](https://youtu.be/pZ42XS2Ucsg) <br />

### <b>Windows registry</b>
[Windows Registry: Run and RunOnce](https://youtu.be/zgFzCq5uEPw) <br />
[Windows Registry: Active Setup](https://youtu.be/HrVJ7wdvfmo) <br />

### <b>PSEXEC</b>
[Windows tools: Using PSEXEC for software deployment testing](https://youtu.be/9ywdTna_TLc) <br />
