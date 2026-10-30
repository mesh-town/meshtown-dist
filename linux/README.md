# Mesh Town for Linux

Static (musl) builds of [Mesh Town](https://github.com/mesh-town/meshtown) for x86_64 and aarch64:
`meshtown-linux-<arch>.tar.gz` (with the tray icon) and `meshtown-cli-linux-<arch>.tar.gz` (console only). The files
without a version are the latest version (0.3.225 at the last publication).
Earlier versions are attached to the [releases](https://github.com/mesh-town/meshtown-dist/releases) of this repository.

## Install

Unpack an archive with `tar xzf <file>` and run the program from the folder it creates. Run only one of the two builds
at a time: they share their settings.

Check the download against `SHA256SUMS` (`sha256sum -c SHA256SUMS --ignore-missing`) before running it.

## Debian and Ubuntu

The [`debian/`](debian/README.md) folder is an apt repository with a signed `.deb` package for amd64 and arm64.

## Files

| File | Link |
|---|---|
| `meshtown-cli-linux-aarch64.tar.gz` | https://github.com/mesh-town/meshtown-dist/raw/main/linux/meshtown-cli-linux-aarch64.tar.gz |
| `meshtown-cli-linux-x86_64.tar.gz` | https://github.com/mesh-town/meshtown-dist/raw/main/linux/meshtown-cli-linux-x86_64.tar.gz |
| `meshtown-linux-aarch64.tar.gz` | https://github.com/mesh-town/meshtown-dist/raw/main/linux/meshtown-linux-aarch64.tar.gz |
| `meshtown-linux-x86_64.tar.gz` | https://github.com/mesh-town/meshtown-dist/raw/main/linux/meshtown-linux-x86_64.tar.gz |
