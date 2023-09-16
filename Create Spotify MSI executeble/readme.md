# WiX toolset 4 CLI
### Downloads and documentation
<b>Download links:</b> <br /> 
* [Spotify](https://www.spotify.com/de-en/download/windows/) <br />
* [Spotify Offline Installer](https://download.scdn.co/SpotifyFullSetup.exe)

<b>Generate package guid</b>
```powershell
[guid]::NewGuid().guid
```

<b>WiX build MSI package command</b>
```powershell
wix build .\Spotify.wxs
```