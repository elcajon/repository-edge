# Home Assistant Community Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)


## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

In general, there is no need to install this repository on your
Home Assistant instance. It is activated and added by Home Assistant
by default.

However, if the repository is missing on your setup, adding this add-ons
repository to your Home Assistant instance is pretty easy. In the
Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/elcajon/repository-edge
```

## Add-ons provided by this repository

### &#10003; [Docker in Docker][addon-dind]

![Latest Version][dind-version-shield]
![Supports armhf Architecture][dind-armhf-shield]
![Supports armv7 Architecture][dind-armv7-shield]
![Supports aarch64 Architecture][dind-aarch64-shield]
![Supports amd64 Architecture][dind-amd64-shield]
![Supports i386 Architecture][dind-i386-shield]

Docker in Docker Imge

[:books: Docker in Docker add-on documentation][addon-doc-dind]

### &#10003; [Factorio Server Manager][addon-fsm]

![Latest Version][fsm-version-shield]
![Supports armhf Architecture][fsm-armhf-shield]
![Supports armv7 Architecture][fsm-armv7-shield]
![Supports aarch64 Architecture][fsm-aarch64-shield]
![Supports amd64 Architecture][fsm-amd64-shield]
![Supports i386 Architecture][fsm-i386-shield]

Factorio Server Manager

[:books: Factorio Server Manager add-on documentation][addon-doc-fsm]

### &#10003; [Simplelogin App][addon-simplelogin]

![Latest Version][simplelogin-version-shield]
![Supports armhf Architecture][simplelogin-armhf-shield]
![Supports armv7 Architecture][simplelogin-armv7-shield]
![Supports aarch64 Architecture][simplelogin-aarch64-shield]
![Supports amd64 Architecture][simplelogin-amd64-shield]
![Supports i386 Architecture][simplelogin-i386-shield]

Simple-Login App

[:books: Simplelogin App add-on documentation][addon-doc-simplelogin]

### &#10003; [Visual Studio Code][addon-vscode]

![Latest Version][vscode-version-shield]
![Supports armhf Architecture][vscode-armhf-shield]
![Supports armv7 Architecture][vscode-armv7-shield]
![Supports aarch64 Architecture][vscode-aarch64-shield]
![Supports amd64 Architecture][vscode-amd64-shield]
![Supports i386 Architecture][vscode-i386-shield]

Fully featured VSCode experience, to edit your HA config in the browser, including auto-completion!

[:books: Visual Studio Code add-on documentation][addon-doc-vscode]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

- [Open an issue for the add-on: Docker in Docker][dind-issue]
- [Open an issue for the add-on: Factorio Server Manager][fsm-issue]
- [Open an issue for the add-on: Simplelogin App][simplelogin-issue]
- [Open an issue for the add-on: Visual Studio Code][vscode-issue]

For a general repository issue or add-on ideas [open an issue here][issue]





## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-dind]: https://github.com/elcajon/addon-dind/tree/bc9ef57
[addon-doc-dind]: https://github.com/elcajon/addon-dind/blob/bc9ef57/README.md
[dind-issue]: https://github.com/elcajon/addon-dind/issues
[dind-version-shield]: https://img.shields.io/badge/version-bc9ef57-blue.svg
[dind-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[dind-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[dind-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[dind-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[dind-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-fsm]: https://github.com/elcajon/addon-fsm/tree/v1.0.3
[addon-doc-fsm]: https://github.com/elcajon/addon-fsm/blob/v1.0.3/README.md
[fsm-issue]: https://github.com/elcajon/addon-fsm/issues
[fsm-version-shield]: https://img.shields.io/badge/version-v1.0.3-blue.svg
[fsm-aarch64-shield]: https://img.shields.io/badge/aarch64-no-red.svg
[fsm-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[fsm-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[fsm-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[fsm-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-simplelogin]: https://github.com/elcajon/addon-simplelogin/tree/4ea14f9
[addon-doc-simplelogin]: https://github.com/elcajon/addon-simplelogin/blob/4ea14f9/README.md
[simplelogin-issue]: https://github.com/elcajon/addon-simplelogin/issues
[simplelogin-version-shield]: https://img.shields.io/badge/version-4ea14f9-blue.svg
[simplelogin-aarch64-shield]: https://img.shields.io/badge/aarch64-no-red.svg
[simplelogin-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[simplelogin-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[simplelogin-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[simplelogin-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-vscode]: https://github.com/elcajon/addon-vscode/tree/v1.0.6
[addon-doc-vscode]: https://github.com/elcajon/addon-vscode/blob/v1.0.6/README.md
[vscode-issue]: https://github.com/elcajon/addon-vscode/issues
[vscode-version-shield]: https://img.shields.io/badge/version-v1.0.6-blue.svg
[vscode-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[vscode-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[vscode-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[vscode-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[vscode-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[awesome-shield]: https://img.shields.io/badge/awesome%3F-yes-brightgreen.svg
[awesome]: https://awesome-ha.com
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[gitlabci-shield]: https://gitlab.com/elcajon/repository-edge/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/elcajon/repository-edge/pipelines
[issue]: https://github.com/elcajon/repository-edge/issues
[license-shield]: https://img.shields.io/github/license/elcajon/repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2021.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html