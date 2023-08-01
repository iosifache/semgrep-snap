<p align="center">
    <a href="https://semgrep.dev">
        <img src="https://raw.githubusercontent.com/returntocorp/semgrep/develop/images/semgrep-logo-light.svg" height="100" alt="Semgrep logo"/>
    </a>
</p>
<h2 align="center">Code scanning at ludicrous speed, all in a snap</h2>
<p align="center" float="left">
    <img src="https://snapcraft.io/semgrep/badge.svg" width="150" height="17" alt="Snapcraft's Version"/>
    &nbsp; &nbsp;
    <img src="https://img.shields.io/pypi/v/semgrep?label=Semgrep%20on%20PyPi&color=1c8223" height="17" alt="PyPI's Version">
    &nbsp; &nbsp;
    <img src="https://img.shields.io/github/actions/workflow/status/iosifache/semgrep-snap/main.yml?label=Build%20Status&color=1c8223" height="17" alt="GitHub Build Workflow Status">
</p>

# Description

Semgrep is an open source static code analysis tool that may be used to identify vulnerabilities in your own codebase or third-party dependencies. The goal of this repository is to package Semgrep as a **(community) snap that can be effortlessly installed across a variety of Linux distributions**.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/semgrep)

> Notice: If you want to view the officially recommended method of installing the OSS engine, refer to the [Semgrep documentation](https://semgrep.dev/docs/getting-started/#installing-and-running-semgrep-locally).

# Local Build

1. Clone this repository: `git clone https://github.com/iosifache/semgrep-snap`
2. Move into the cloned repository: `cd semgrep-snap`
3. Install Snapcraft: `sudo snap install snapcraft --classic`
4. Build the snap: `snapcraft --verbose`
5. Install the snap: `snap install --dangerous ./semgrep_*.snap`
6. Test the snap by running the `semgrep` command: `semgrep`
