# Proton Mail Desktop App
![GitHub Release](https://img.shields.io/github/v/release/ArchitektApx/protonmail-desktop?label=%F0%9F%93%A6%20GitHub%20Release)
![📦 Architecture: x64 ](https://img.shields.io/badge/📦_Architecture-x64-blue?style=flat-square)
![📦 Architecture: aarch64](https://img.shields.io/badge/📦_Architecture-aarch64-blue?style=flat-square)

Automatically updated spec files and `x64/aarch64/arm64` build workflows for the Proton Mail Desktop App

## Releases

All Proton Mail Desktop releases are built using the [ProtonMail WebClients Monorepo](https://github.com/ProtonMail/WebClients) and provide [DEB/RPM/Zip Packages](https://github.com/ArchitektApx/protonmail-desktop/releases/tag/1.6.0) for installation.

## Fedora COPR

[![⚡️ Powered By: Copr](https://img.shields.io/badge/⚡️_Powered_by-COPR-blue?style=flat-square)](https://copr.fedorainfracloud.org/)
[![Latest Version](https://img.shields.io/badge/dynamic/json?color=blue&label=Version&query=builds.latest.source_package.version&url=https%3A%2F%2Fcopr.fedorainfracloud.org%2Fapi_3%2Fpackage%3Fownername%3Darchitektapx%26projectname%3Dprotonmail-desktop%26packagename%3Dprotonmail-desktop%26with_latest_build%3DTrue&style=flat-square&logoColor=blue)](https://copr.fedorainfracloud.org/coprs/architektapx/protonmail-desktop/package/protonmail-desktop/)
[![Copr build status](https://copr.fedorainfracloud.org/coprs/architektapx/protonmail-desktop/package/protonmail-desktop/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/architektapx/protonmail-desktop/package/protonmail-desktop/)

### Installation Instructions
1. Enable `architektapx/protonmail-desktop` [Copr](https://copr.fedorainfracloud.org/coprs/architektapx/protonmail-desktop/) repository according to your package manager.

```Shell
# If you are using dnf... (you need to have 'dnf-plugins-core' installed)
sudo dnf copr enable architektapx/protonmail-desktop

# If you are using yum... (you need to have 'yum-plugins-copr' installed)
sudo yum copr enable architektapx/protonmail-desktop

# specify chroot if you have troubles on fedora 41 due to case sensitivity
sudo dnf copr enable architektapx/protonmail-desktop fedora-41-aarch64
# or
sudo dnf copr enable architektapx/protonmail-desktop fedora-41-x86_64
```

2. (Optional) Update your package list.

```Shell
sudo dnf check-update
```

3. Execute the following command to install the package.

```Shell
sudo dnf install protonmail-desktop
```

4. Launch the application from the Application Menu or execute following command in terminal.

```Shell
proton-mail
```