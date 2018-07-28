# Changelog

All noteworthy changes to this project will be documented in this file.

The format is based on [Keep a Changelog][changelog-1].

Versioning semi-adheres to [Semantic Versioning][changelog-2], accordingly:
*Ubuntu-Minor.Box-Major.Box-Minor*.

A new Ubuntu release will bump the first digit (we're currently at Ubuntu
18.**04**). A new version of this Vagrant box will bump either or both of the
last two digits.

Box updates do not add additional software unless strictly necessary for bug
fixes and system stability. Box updates are most likely new
Guest Additions/VMware Tools, a new Linux kernel, upgraded software packages and
so on. On that note, the *Box-Major* part of the version string is unlikely to
change.

[changelog-1]: http://keepachangelog.com/en/1.0.0/
[changelog-2]: http://semver.org/spec/v2.0.0.html

## [Unreleased][unreleased-1]

- Nothing, yet.

[unreleased-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v10.0.0...HEAD

## [10.0.0][100-1] - 2018-07-28

### Software

- Ubuntu version: `18.10 (development branch)`
- Budgie version: `10.4`
- Linux Kernel: `4.15.0-29-generic`
- VirtualBox Guest Additions: `5.2.16r123759`
- VMware Tools: `10.2.5.8049 (build-8068393)`
- Built with Packer: `1.2.6` ([special edition][100-2])
- ..on host: `Windows Pro 10.0.17134 Build 17134`

[100-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v4.0.2...v10.0.0
[100-2]: https://github.com/hashicorp/packer/issues/6524#issuecomment-407127912

## [4.0.2][402-1] - 2018-04-15

### Added

- This changelog.

### Software

- Ubuntu version: `18.04 (development branch)`
- Budgie version: `10.4`
- Linux Kernel: `4.15.0-15-generic`
- VirtualBox Guest Additions: `5.2.8r121009`
- VMware Tools: `10.2.0.7047 (build-7259539)`
- Built with Packer: `1.2.2`
- ..on host: `Windows Pro 10.0.16299 Build 16299`

[402-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v4.0.1...v4.0.2

## [4.0.1][401-1] - 2018-03-22

### Improved

- [issue martinanderssondotcom/box-ubuntu-budgie-17-x64#3][401-2]

### Software

- Ubuntu version: `18.04 (development branch)`
- Budgie version: `10.4`
- Linux Kernel: `4.15.0-12-generic`
- VirtualBox Guest Additions: `5.2.8r121009`
- VMware Tools: `10.2.0.7047 (build-7259539)`
- Built with Packer: `1.2.1`
- ..on host: `Windows Pro 10.0.16299 Build 16299`

[401-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v4.0.0...v4.0.1
[401-2]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-17-x64/issues/3

## 4.0.0 - 2018-03-22

Initial release.

### Software

- Ubuntu version: `18.04 (development branch)`
- Budgie version: `10.4`
- Linux Kernel: `4.15.0-12-generic`
- VirtualBox Guest Additions: `5.2.8r121009`
- VMware Tools: `10.2.0.7047 (build-7259539)`
- Built with Packer: `1.2.1`
- ..on host: `Windows Pro 10.0.16299 Build 16299`