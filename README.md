# RedBonOS
RedBonOS gives the option for users to install Arch Linux with ease and get a custom grub look. This will also include the redbon-repo in the installed system.

- Link for redbon-repo: https://gitlab.com/MacCygwin1/redbon-repo

Directory Tree:
```
.
├── airootfs
│   └── usr
│       ├── local
│       │   └── bin
│       │       ├── redbon-install.sh
│       │       └── ...
│       └── share
│           └── wallpapers
│               └── redbon-default.png
├── bootstrap_packages
├── efiboot
├── grub  
├── packages.x86_64
├── pacman.conf
└── profiledef.sh
```

To download the ISO, go to [`Releases`](https://github.com/MacCygwin/RedBonOS/releases).

If u want to build the iso locally:
```
sudo mkarchiso -v .
```
- . being main directory.

