# usefulthings

```
iwr -useb christitus.com/win | iex  ------------->powershell
```

# Chromium Visual Studio Gereksinimleri için Yükleme Kodu
```
start " " "%~dp0vs_installer" modify --installPath "C:\Program Files\Microsoft Visual Studio\2022\Community" --add Microsoft.VisualStudio.Workload.NativeDesktop Microsoft.VisualStudio.Component.VC.ATLMFC Microsoft.VisualStudio.Component.VC.Tools.ARM64 Microsoft.VisualStudio.Component.VC.MFC.ARM64
```

```
mkdir C:\src\chromium && cd C:\src\chromium
```

```
git init
```
#116 yazan kısımlara güncel build numaralarını yaz
<br>Buradan bulabilirsin : https://chromium.woolyss.com/ 
```
git fetch https://chromium.googlesource.com/chromium/src.git +refs/tags/116.0.5845.180:chromium_116.0.5845.180 --depth 1
```
