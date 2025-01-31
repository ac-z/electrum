# electrum &nbsp; [![bluebuild build badge](https://github.com/ac-z/electrum/actions/workflows/build.yml/badge.svg)](https://github.com/ac-z/electrum/actions/workflows/build.yml)

Custom Fedora Kinoite image for my own use. Mainly for additional packages/configs.

## Verification

These images are signed with [Sigstore](https://www.sigstore.dev/)'s [cosign](https://github.com/sigstore/cosign). You can verify the signature by downloading the `cosign.pub` file from this repo and running the following command:

```bash
cosign verify --key cosign.pub ghcr.io/ac-z/electrum
```
