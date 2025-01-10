# XeroLinux Welcome

This is a welcome app for the XeroLinux Ditro. It features:

- Showing XeroLinux Social Links
- Running the Calamares installer
- Updating XeroLinux repositories

This program is still on beta stages and it is semi complete and ready to use.

## Build the package on Arch machines

- For building this package run:
```shell
cd build/
makepkg -f
```

### Install the package
- For installing this pacakge run:
```shell
cd build/
sudo pacman -U ./xero-welcome*
```
