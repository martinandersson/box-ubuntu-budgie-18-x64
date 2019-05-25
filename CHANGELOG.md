# Changelog

All noteworthy changes to this project will be documented in this file.

The format is based on [Keep a Changelog][changelog-1].

Versioning semi-adheres to [Semantic Versioning][changelog-2], accordingly:
*Ubuntu-Minor.Box-Major.Box-Minor*.

A new Ubuntu release will bump the first digit (we're currently at Ubuntu
18.**10**). A new version of this Vagrant box will bump either or both of the
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

[unreleased-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v10.2.1...HEAD

## [10.2.1][1021-1] - 2019-05-25

### Software

- Ubuntu version: `18.10`
- Budgie version: `10.4`
- Linux Kernel: `4.18.0-20-generic`
- VirtualBox Guest Additions: `6.0.8r130520`
- VMware Tools: `10.3.10.10540 (build-12406962)`
- Built with Packer: `1.4.0`
- ..on host: `Windows Pro 10.0.17763 Build 17763`

[1021-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v10.2.0...v10.2.1

## [10.2.0][1020-1] - 2019-03-04

### Software

- Ubuntu version: `18.10`
- Budgie version: `10.4`
- Linux Kernel: `4.18.0-15-generic`
- VirtualBox Guest Additions: `6.0.4r128413`
- VMware Tools: `10.3.2.6765 (build-9925305)`
- Built with Packer: `1.3.5`
- ..on host: `Windows Pro 10.0.17763 Build 17763`

[1020-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v10.1.0...v10.2.0

## [10.1.0][1010-1] - 2018-11-20

### Changed

- VMware's "[Hardware version][1010-2]" from `14` to `16`; this ought to require
  Workstation 15

### Software

- Ubuntu version: `18.10`
- Budgie version: `10.4`
- Linux Kernel: `4.18.0-11-generic`
- VirtualBox Guest Additions: `5.2.22r126460`
- VMware Tools: `10.3.2.6765 (build-9925305)`
- Built with Packer: `1.3.2`
- ..on host: `Windows Pro 10.0.17134 Build 17134`

[1010-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v10.0.1...v10.1.0
[1010-2]: https://kb.vmware.com/s/article/1003746

## [10.0.1][1001-1] - 2018-08-25

### Software

- Ubuntu version: `18.10 (development branch)`
- Budgie version: `10.4`
- Linux Kernel: `4.17.0-7-generic`
- VirtualBox Guest Additions: `5.2.18r124319`
- VMware Tools: `10.2.5.8049 (build-8068393)`
- Built with Packer: `1.2.6` ([special edition][1000-2])
- ..on host: `Windows Pro 10.0.17134 Build 17134`

[1001-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v10.0.0...v10.0.1

## [10.0.0][1000-1] - 2018-07-28

### Software

- Ubuntu version: `18.10 (development branch)`
- Budgie version: `10.4`
- Linux Kernel: `4.15.0-29-generic`
- VirtualBox Guest Additions: `5.2.16r123759`
- VMware Tools: `10.2.5.8049 (build-8068393)`
- Built with Packer: `1.2.6` ([special edition][1000-2])
- ..on host: `Windows Pro 10.0.17134 Build 17134`

[1000-1]: https://github.com/martinanderssondotcom/box-ubuntu-budgie-18-x64/compare/v4.0.2...v10.0.0
[1000-2]: https://github.com/hashicorp/packer/issues/6524#issuecomment-407127912

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