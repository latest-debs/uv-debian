# uv for Debian

[uv](https://github.com/astral-sh/uv) — an extremely fast Python package and
project manager, written in Rust — packaged for Debian as part of
[latest-debs](https://github.com/latest-debs).

## Install

Via the latest-debs apt repository:

```sh
sudo extrepo enable latest-debs
sudo apt update
sudo apt install uv
```

Or download a `.deb` from the [Releases](https://github.com/latest-debs/uv-debian/releases) page:

```sh
sudo dpkg -i uv_*.deb
```

## Supported distributions & architectures

- Debian Bookworm (12), Trixie (13), Forky (14/testing), Sid (unstable)
- amd64, arm64, armel, armhf, ppc64el, s390x, riscv64

## Building

Run the [Build uv for Debian](../../actions) workflow on GitHub with the
desired upstream version. Packaging is driven by
[debian-multiarch-builder](https://github.com/ranjithrajv/debian-multiarch-builder).

## Disclaimer

Unofficial packaging only. For issues with uv itself, see
[astral-sh/uv](https://github.com/astral-sh/uv).
