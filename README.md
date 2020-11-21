<div>
  <img width="190" height="210" align="left" src="https://raw.githubusercontent.com/v2fly/v2fly-github-io/master/docs/.vuepress/public/readme-logo.png" alt="V2Ray"/>
  <br>
  <h1>Project V</h1>
  <p>Project V is a set of network tools that helps you to build your own computer network. It secures your network connections and thus protects your privacy.</p>
</div>

[![GitHub Test Badge](https://github.com/v2fly/v2ray-core/workflows/Test/badge.svg)](https://github.com/v2fly/v2ray-core/actions)
[![codecov.io](https://codecov.io/gh/v2fly/v2ray-core/branch/master/graph/badge.svg?branch=master)](https://codecov.io/gh/v2fly/v2ray-core?branch=master)
[![codebeat](https://goreportcard.com/badge/github.com/v2fly/v2ray-core)](https://goreportcard.com/report/github.com/v2fly/v2ray-core)
[![Downloads](https://img.shields.io/github/downloads/v2fly/v2ray-core/total.svg)](https://github.com/v2fly/v2ray-core/releases/latest)

## Related Links

- [Documentation](https://www.v2fly.org/) and [Newcomer's Instructions](https://www.v2fly.org/guide/start.html)
- Welcome to translate V2Ray via: [Transifex](https://www.transifex.com/v2fly/public/)

## Installation

V2Ray binaries are available in [GitHub Releases](https://github.com/v2fly/v2ray-core/releases), or you can install it by:

- macOS:
  - [Homebrew](https://brew.sh): `brew install v2ray`
- Windows:
  - [Chocolatey](https://chocolatey.org): `choco install v2ray`
  - [Scoop](https://scoop.sh): `scoop install v2ray`
- Linux:
  - [Docker](https://github.com/v2fly/docker): `docker pull v2fly/v2fly-core`
  - [Linuxbrew](https://github.com/Homebrew/linuxbrew-core): `brew install v2ray`
  - [Bash script](https://github.com/v2fly/fhs-install-v2ray)
  - Package managers, including apt (Debian), pacman (Arch Linux), etc

For more details, please visit [Installation guide](https://www.v2fly.org/guide/install.html).

## Packaging Status

> If you are willing to package V2Ray for other distros/platforms, please let us know or seek for help via [GitHub issues](https://github.com/v2fly/v2ray-core/issues).

[![Packaging status](https://repology.org/badge/vertical-allrepos/v2ray.svg)](https://repology.org/project/v2ray/versions)
[![Packaging status](https://repology.org/badge/vertical-allrepos/go:v2ray-core.svg)](https://repology.org/project/go:v2ray-core/versions)
[![Packaging status](https://repology.org/badge/vertical-allrepos/v2ray-core.svg)](https://repology.org/project/v2ray-core/versions)

## License

[The MIT License (MIT)](https://raw.githubusercontent.com/v2fly/v2ray-core/master/LICENSE)

## Credits

This repo relies on the following third-party projects:

- In production:
  - [gorilla/websocket](https://github.com/gorilla/websocket)
  - [lucas-clemente/quic-go](https://github.com/lucas-clemente/quic-go)
  - [pires/go-proxyproto](https://github.com/pires/go-proxyproto)
  - [seiflotfy/cuckoofilter](https://github.com/seiflotfy/cuckoofilter)
  - [google/starlark-go](https://github.com/google/starlark-go)
- For testing only:
  - [miekg/dns](https://github.com/miekg/dns)
  - [h12w/socks](https://github.com/h12w/socks)
