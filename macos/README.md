# Mesh Town for macOS

Builds of [Mesh Town](https://github.com/mesh-town/meshtown) for macOS: `MeshTown-macos-arm64.zip` for Apple silicon
and `MeshTown-macos-x86_64.zip` for Intel. The files without a version are the latest version (0.3.96 at the last
publication); the four latest versions of each are also kept under their version numbers.

## Install

1. Unpack the zip and move `MeshTown.app` to Applications.
2. The app is signed ad hoc and not notarized, and a zip downloaded in a browser carries the quarantine mark, so
   Gatekeeper blocks the first launch. Either open **System Settings → Privacy & Security → "Open Anyway"**, or remove
   the mark from a terminal: `xattr -dr com.apple.quarantine /Applications/MeshTown.app`.

Check the download against `SHA256SUMS` (`shasum -a 256 -c SHA256SUMS --ignore-missing`) before running it.

## Versions

| File | Link |
|---|---|
| `MeshTown-macos-arm64.zip` (latest) | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-arm64.zip |
| `MeshTown-macos-arm64-0.3.96.zip` | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-arm64-0.3.96.zip |
| `MeshTown-macos-arm64-0.3.33.zip` | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-arm64-0.3.33.zip |
| `MeshTown-macos-arm64-0.3.30.zip` | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-arm64-0.3.30.zip |
| `MeshTown-macos-arm64-0.3.29.zip` | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-arm64-0.3.29.zip |
| `MeshTown-macos-x86_64.zip` (latest) | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-x86_64.zip |
| `MeshTown-macos-x86_64-0.3.96.zip` | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-x86_64-0.3.96.zip |
| `MeshTown-macos-x86_64-0.3.33.zip` | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-x86_64-0.3.33.zip |
| `MeshTown-macos-x86_64-0.3.30.zip` | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-x86_64-0.3.30.zip |
| `MeshTown-macos-x86_64-0.3.29.zip` | https://github.com/mesh-town/meshtown-dist/raw/main/macos/MeshTown-macos-x86_64-0.3.29.zip |
