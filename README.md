# Scoop Bucket

My personal bucket for [Scoop](http://scoop.sh), with certain packages not included in the known buckets.

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
## Included packages
* `yumi`
* `yumi-uefi`
