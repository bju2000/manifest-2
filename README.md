# Maru OS Manifest

## Getting Started

To get started with Android/Maru OS, you'll need to get familiar with
[Repo](https://source.android.com/source/using-repo.html) and [Version Control
with Git](https://source.android.com/source/version-control.html).

To initialize your local repository using the Maru OS trees, use a command like this:

    repo init -u https://github.com/pintaf/manifest -b maru-0.7 --no-clone-bundle --depth=1

Then to sync up:

    repo sync --jobs=8 --fetch-submodules --current-branch --no-clone-bundle


## Contributing

See the [main Maru OS repository](https://github.com/maruos/maruos) for more
info.

## Licensing

[Apache 2.0](LICENSE)
