<p align="center">
    <img src="https://raw.githubusercontent.com/returntocorp/semgrep/develop/images/semgrep-logo-light.svg" height="100" alt="Semgrep logo"/>
</p>
<h2 align="center">Code scanning at ludicrous speed, all in a snap</h2>
<p align="center" float="left">
    <img src="https://snapcraft.io/semgrep/badge.svg" width="150" alt="Snapcraft's Version"/>
    &nbsp; &nbsp;
    <img alt="PyPI's Version" src="https://img.shields.io/pypi/v/semgrep?label=Semgrep%20on%20PyPi&color=blue">
</p>

# Description

Semgrep is an open source static code analysis tool that may be used to identify vulnerabilities in your own codebase or third-party dependencies. The goal of this repository is to package Semgrep as a snap that can be effortlessly distributed across a variety of Linux distributions.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/semgrep)

# Local Build

1. Clone this repository: `git clone https://github.com/iosifache/semgrep-snap`
2. Move into the cloned repository: `cd semgrep-snap`
3. Install Snapcraft: `sudo snap install snapcraft --classic`
4. Build the snap: `snapcraft --verbose`
5. Install the snap: `snap install --dangerous ./semgrep_*.snap`
6. Test the snap by running the `semgrep` command: `semgrep`
