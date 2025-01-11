# XeroLinux Welcome

This is a welcome app for the XeroLinux Distro. It features:

- Running the Calamares installer
- Showing XeroLinux Social Links
- Updating the system (post-install)
- Launch the XeroLinux Toolkit (post-install)

This program is still on beta stages and it is semi complete and ready to use.

## Build the package on Arch machines

- Install dpendencies:
```shell
sudo pacman -S --noconfirm git rustup
```

- Initialize Rust:
```shell
rustup default nightly
```

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

### Update Rust

It's a good idea to update Cargo DB once a week. Since it's not only a package but a database as well, you will have to update it manually. To do so do this in terminal:

- To update Cargo DB
```shell
rustup update
```

### Credits

This tool was created by the [**ParchLinux**](https://parchlinux.com/en) team. I take absolutely no credit for that. They just allowed me to modify and use it for my own needs. That's the beauty of **FOSS**. You can find original source-code >> [**Here**](https://git.parchlinux.com/applications/parch-welcome/-/tree/main?ref_type=heads).
