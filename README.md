<p align="center">
   <img src="logo.jpg" width="250" alt="Default Repo All Distro Linux Logo" style="background: transparent;">
</p>

# Default Repository Collection for All Major Linux Distributions

📦 A centralized collection of default repository configuration files for many popular Linux distributions.

This project provides the original/default repo configurations that come pre-installed or are commonly used for each distro. Useful if:

- You broke or deleted your repo configuration
- You're reinstalling your system
- You want to manually restore package manager configs
- You're setting up offline or air-gapped systems

## 🐧 Supported Distributions
- Debian
- Ubuntu
- Kali Linux
- Arch Linux
- Manjaro
- Fedora
- RHEL
- CentOS
- OpenSUSE
- Linux Mint
- Parrot OS
- BlackArch
- Alpine Linux
- Garuda Linux
- BackBox Linux
- Gentoo
- Pentoo
- Deepin
- Peppermint OS
- KaOS
- NixOS
- Grml
- Mandriva
- Linux Lite
- Kubuntu
- etc.


## 📁 Folder Structure

Each folder contains the default repository files and a `README.md` explaining how to use it.

```
distro/
├── repository-file
└── README.md
```
## Structure

Each distro has its own folder with its default `.list`, `.repo`, or `mirrorlist` file.

## 📌 Contributions

We welcome PRs with other distro defaults! Please include:

- Distro name and version
- Default repo config file(s)
- Verified source or documentation link if possible
- We welcome contributions! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

## License
```
This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.
```

## ⚠️ Disclaimer

Always double-check the URLs or mirror addresses. Some distros or versions might have specific requirements or keys.

---
Maintained by the community. Contributions are highly appreciated!
