# CoreTools releases

Latest: **v1.2.1** — 2026-10-14

## Download the latest

These links never change; they always serve the newest version.

| File | Size | SHA-256 |
| --- | --- | --- |
| [CoreTools-Windows-Setup.exe](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-Windows-Setup.exe) | 4.4 MB | `0a2a4b9c5fea4a904eafc09ff05bcd94c3b13870cae108908fc3b7e31e968ac7` |
| [CoreTools-macOS.dmg](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-macOS.dmg) | 11.3 MB | `b8efc0a5b0e515e8f60e09d3e70e7c93551aca1ea678882f05fe856c68eaffae` |
| [CoreTools-Linux.AppImage](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-Linux.AppImage) | 80.6 MB | `ecdd64e5c7910be814c979a46dff7297bbc80d49d5da982ab738c65a4b4e94f7` |
| [CoreTools-sbom.cdx.json](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-sbom.cdx.json) | 842 KB | `5e92649272afa28f48efdc6fa826474a9231e8de1addf3f7fb260dbeadcfe0f5` |

Verify a download against `SHA256SUMS.txt`:

- Windows (PowerShell): `Get-FileHash <file> -Algorithm SHA256`
- macOS / Linux: `shasum -a 256 <file>`

`SHA256SUMS.txt` is signed with [Sigstore](https://www.sigstore.dev/) by the release workflow. Check the signature first ([cosign](https://docs.sigstore.dev/cosign/system_config/installation/)), with `SHA256SUMS.txt.sigstore.json` beside it:

```
cosign verify-blob SHA256SUMS.txt --bundle SHA256SUMS.txt.sigstore.json \
  --certificate-identity-regexp '^https://github\.com/jaychandra1/coretools/\.github/workflows/release\.yml@refs/(tags/v.+|heads/master)$' \
  --certificate-oidc-issuer https://token.actions.githubusercontent.com
```

A file that fails this check did not come from the CoreTools release pipeline — don't install it.

## All versions

| Version | Date | Downloads |
| --- | --- | --- |
| [v1.2.1](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.1) | 2026-10-14 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/SHA256SUMS.txt.sigstore.json) |
| [v1.2.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.0) | 2026-10-13 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/SHA256SUMS.txt.sigstore.json) |
| [v1.1.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.1.0) | 2026-10-13 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/CoreTools-Linux.AppImage) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/SHA256SUMS.txt) |
| [v1.0.1](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.0.1) | 2026-10-12 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/CoreTools-Linux.AppImage) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/SHA256SUMS.txt) |
| [v1.0.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.0.0) | 2026-10-12 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/CoreTools-Linux.AppImage) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/SHA256SUMS.txt) |

_Generated by the release workflow — do not edit by hand._
