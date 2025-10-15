# Recompressed builds of VSCodium and VSCode

This repository contains a GitHub Actions workflow that fetches the latest upstream release of **VSCodium** and **VSCode**, unpacks it, and recompresses it into a 7z archive with maximum compression.

## Where to get the files

The recompressed builds are published under the [**GitHub Releases**](https://github.com/ddrezip/vscodium-vscode/releases) page of this repository.

> **Note:** If you are viewing this project on a mirror, such as Gitlab or Framagit, no release assets are attached there.  
> Please use the GitHub mirror to download the 7z files.

## Upstream

Original releases are published by the upstream projects:

- [VSCodium](https://github.com/VSCodium/vscodium/releases)
- [Visual Studio Code](https://code.visualstudio.com/Download)

This repository does not modify the software itself, it only repackages existing upstream binaries.

## Contributing

I focus my repacks on the versions I use, because I don’t really expect this to be used by many.
But if you want a particular build that I don’t currently repack, feel free to send a pull request (or to just open an issue, if you must).
