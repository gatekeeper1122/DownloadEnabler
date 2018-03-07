Download Enabler
================================================================================

The official PS Vita&trade; webbrowser is only able to downloaded media files. 
This plugin removes that limitation and allows you to download any files from the webbrowser to `ux0:download`.
Content that do not have a `Content-Length` entity-header field are not supported.

### Changelog v4
- Added support for 3.65 retail and 3.67 retail.
- Added support for 3.60 PDEL and 3.60 PTEL.

### Changelog v3
- Improved code and now files with don't overwrite existing files anymore, but are saved as `filename (X).ext`.

### Changelog v2
- Fixed bug in Sony webbrowser where a `HEAD` request was made instead of a `GET` request. This also fixed the `Cannot download using this system` bug.
- Changed download folder to `ux0:download`.

### Installation
Copy `download_enabler.suprx` to `ux0:tai` and write the path to `*main` as follows

```text
*main
ux0:tai/download_enabler.suprx
```

Reboot your device and enjoy your improved webbrowser.