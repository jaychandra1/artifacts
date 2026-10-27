# CoreTools releases

Latest: **v1.4.0** — 2026-10-27

## Download the latest

These links never change; they always serve the newest version.

| File | Size | SHA-256 |
| --- | --- | --- |
| [CoreTools-Linux.AppImage](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-Linux.AppImage) | 89.4 MB | `7d9ad04c37c237450e9fe832f9cd6525e3d037c0207cc2c94577185ee4007ebe` |
| [CoreTools-Windows-Setup.exe](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-Windows-Setup.exe) | 12.0 MB | `827f6c44bc165d5883d6a9b9b7c67dbecb35468f294d6b3cf7f4553ad79bbc52` |
| [CoreTools-macOS.dmg](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-macOS.dmg) | 27.3 MB | `209ef437e6e5a60896509a612d116084d15b242d3c4a8d395c504f5b45e2c43a` |
| [CoreTools-sbom.cdx.json](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-sbom.cdx.json) | 863 KB | `06ee518fe4c2afe55ba8f5d7afb26088775e733f0233eb06823feeffe732e5e7` |

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
| [v1.4.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.4.0) | 2026-10-27 | [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.4.0/CoreTools-Linux.AppImage) · [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.4.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.4.0/CoreTools-macOS.dmg) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.4.0/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.4.0/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.4.0/SHA256SUMS.txt.sigstore.json) |
| [v1.3.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.3.0) | 2026-10-27 | [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.3.0/CoreTools-Linux.AppImage) · [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.3.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.3.0/CoreTools-macOS.dmg) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.3.0/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.3.0/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.3.0/SHA256SUMS.txt.sigstore.json) |
| [v1.2.5](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.5) | 2026-10-15 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/SHA256SUMS.txt.sigstore.json) |
| [v1.2.4](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.4) | 2026-10-15 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/SHA256SUMS.txt.sigstore.json) |
| [v1.2.3](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.3) | 2026-10-15 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/SHA256SUMS.txt.sigstore.json) |
| [v1.2.1](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.1) | 2026-10-14 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/SHA256SUMS.txt.sigstore.json) |
| [v1.2.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.0) | 2026-10-13 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/SHA256SUMS.txt.sigstore.json) |
| [v1.1.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.1.0) | 2026-10-13 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/CoreTools-Linux.AppImage) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/SHA256SUMS.txt) |
| [v1.0.1](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.0.1) | 2026-10-12 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/CoreTools-Linux.AppImage) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/SHA256SUMS.txt) |
| [v1.0.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.0.0) | 2026-10-12 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/CoreTools-Linux.AppImage) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/SHA256SUMS.txt) |

_Generated by the release workflow — do not edit by hand._
