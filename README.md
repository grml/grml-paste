# grml-paste

[![Sponsor](https://img.shields.io/badge/Sponsor-GitHub-purple?logo=github)](https://github.com/sponsors/grml)
[![GitHub release](https://img.shields.io/github/v/release/grml/grml-paste)](https://github.com/grml/grml-paste/releases)
[![Debian package](https://img.shields.io/debian/v/grml-paste/trixie?label=debian)](https://packages.debian.org/trixie/grml-paste)
[![Ubuntu package](https://img.shields.io/ubuntu/v/grml-paste)](https://packages.ubuntu.com/search?keywords=grml-paste)

Paste text into a pastebin service

## Overview

grml-paste is a client for a pastebin service like https://paste.debian.net/.

## Installation

### From Debian repositories

```bash
sudo apt install grml-paste
```

Package information: [grml-paste on packages.debian.org](https://packages.debian.org/trixie/grml-paste)

### From GitHub releases

Download the latest `.deb` package from the [releases page](../../releases) and install:

```bash
sudo apt install ./grml-paste_*.deb
```

## Quick start

1. Install the package (see above)
2. Paste some text:
   ```bash
   echo hi | grml-paste
   ```

## Token

Authentication against the pastebin allows you to circumvent most of the AntiSpam checks and benefit from relaxed limits. To create a token you
need to authenticate on https://paste.debian.net against salsa.debian.org. Afterwards you can use https://paste.debian.net/tokens to create and 
manage your token. grml-paste accepts your token with the --token parameter.

## License

This project is licensed under the GPL v2+.

## Contributing

- **Source code**: https://github.com/grml/grml-paste
- **Issues**: https://github.com/grml/grml-paste/issues
- **Releases**: https://github.com/grml/grml-paste/releases
- **Grml Live Linux**: https://grml.org
