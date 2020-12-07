<h1 align="center">Porridge's Bucket</h1>
<p align="center">
    <a href="https://github.com/porridgepi/scoop-bucket/blob/master/LICENSE"><img src="https://img.shields.io/github/license/porridgepi/scoop-bucket.svg?style=flat-square" alt="License"></a>
    <a href="https://www.microsoft.com/en-us/windows"><img src="https://img.shields.io/badge/Target-Windows%2010-0067B8.svg?style=flat-square" alt="Windows" /></a>
    <a href="https://github.com/porridgepi/scoop-bucket"><img src="https://img.shields.io/github/repo-size/porridgepi/scoop-bucket.svg?style=flat-square" alt="Repo size"></a>
</p>

<p align="center">
        <a href="README.md">English</a> | <a href="README-zh.md">简体中文</a>
</p>

<blockquote>
        Yet Another <a href="https://github.com/lukesampson/scoop">Scoop</a> <a href="https://github.com/lukesampson/scoop/wiki/Buckets">Bucket</a>
</blockquote>



## Scoop Installation

Run the following command from your PowerShell to install scoop to its default location (`C:\Users\<user>\scoop`) and add certain buckets

```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser

iwr -useb get.scoop.sh | iex

scoop install git

scoop bucket add extras
scoop bucket add nirsoft
scoop bucket add nerd-fonts
scoop bucket add nonportable
scoop bucket add games

scoop update
```

## Add this bucket
Run the following command to add this bucket to your Scoop installation
```powershell
scoop bucket add porridge https://github.com/PorridgePi/scoop-bucket
```
## Manifests
### Available manifests for installation
| App name                  | Manifest name | Description |
|-------------------------- | ------------- | ----------- |
| [Legacy YUMI](https://www.pendrivelinux.com/yumi-multiboot-usb-creator/) | `yumi` | Multiboot USB Creator - Legacy BIOS |
| [YUMI UEFI](https://www.pendrivelinux.com/yumi-multiboot-usb-creator/) | `yumi-uefi` | Multiboot USB Creator - UEFI |
| [Dynalist](https://dynalist.io) | `dynalist` | The best outlining app for your best work |
| [Furmark](https://www.geeks3d.com/20200924/furmark-1-22-0-released/) | `furmark` | Furmark v1.22.2.0 which can be installed by innunp |

### Deprecated (Removed)
| App name                  | Manifest name | Description |
|-------------------------- | ------------- | ----------- |