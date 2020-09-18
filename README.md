# Maru OS Manifest

## Getting Started

To get started with Android/Maru OS, you'll need to get familiar with
[Repo](https://source.android.com/source/using-repo.html) and [Version Control
with Git](https://source.android.com/source/version-control.html).

To initialize your local repository using the Maru OS trees, use a command like this:

    repo init -u https://github.com/bju2000/manifest-maruos -b maru-0.8 --no-clone-bundle -c --depth=1 --no-tags

Then to sync up:

    repo sync -c -j 16 --force-sync --no-tag --no-clone-bundle --optimized-fetch --prune --fetch-submodules --current-branch


## Contributing

See the [main Maru OS repository](https://github.com/maruos/maruos) for more
info.

## Licensing

[Apache 2.0](LICENSE)
