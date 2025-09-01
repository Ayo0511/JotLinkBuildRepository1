##  How to Install JotLink

1. Download `JotLink.msix` from the latest release.

2. Double-click the `.msix` file to begin installation.

>  If you see a trust warning, enable sideloading:
> Go to **Settings > Privacy & Security > For Developers**
> Turn on **“Install apps from any source”**

---

###  Advanced: If Installation Fails

If double-clicking the `.msix` file doesn’t work:

1. **Right-click** `Add-AppDevPackage.ps1`  
2. Select **“Run with PowerShell”**

This script will:
- Install the included certificate (`JotLink.cer`)
- Register the app package
- Prompt you through any trust or permission steps

>  You may need to allow script execution:
> Open PowerShell as Administrator and run:
> `Set-ExecutionPolicy RemoteSigned`
