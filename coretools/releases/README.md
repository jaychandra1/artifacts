# CoreTools releases

Latest: **v1.2.5** — 2026-10-15

## Download the latest

These links never change; they always serve the newest version.

| File | Size | SHA-256 |
| --- | --- | --- |
| [CoreTools-Windows-Setup.exe](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-Windows-Setup.exe) | 4.4 MB | `846e60ad4b5f210dd04526317094fae64e41a95a61034787109db7eca5521fbd` |
| [CoreTools-macOS.dmg](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-macOS.dmg) | 11.3 MB | `568b074fad25b69a9b05012b126e71315d0a391bdd0b82825f70d5d077874d6f` |
| [CoreTools-Linux.AppImage](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-Linux.AppImage) | 80.6 MB | `db0903131f3883efb56a8acb5beb8aafa0538ecb3e9ca7b2017df45b635fceb0` |
| [CoreTools-sbom.cdx.json](https://github.com/jaychandra1/artifacts/releases/download/coretools-latest/CoreTools-sbom.cdx.json) | 843 KB | `ba604788ade42683f327fb18799a7e9632e001eea60ec06d90cae2d3904ac6a2` |

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
| [v1.2.5](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.5) | 2026-10-15 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.5/SHA256SUMS.txt.sigstore.json) |
| [v1.2.4](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.4) | 2026-10-15 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.4/SHA256SUMS.txt.sigstore.json) |
| [v1.2.3](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.3) | 2026-10-15 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.3/SHA256SUMS.txt.sigstore.json) |
| [v1.2.1](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.1) | 2026-10-14 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.1/SHA256SUMS.txt.sigstore.json) |
| [v1.2.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.2.0) | 2026-10-13 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-Linux.AppImage) · [SBOM](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/CoreTools-sbom.cdx.json) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/SHA256SUMS.txt) · [signature](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.2.0/SHA256SUMS.txt.sigstore.json) |
| [v1.1.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.1.0) | 2026-10-13 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/CoreTools-Linux.AppImage) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.1.0/SHA256SUMS.txt) |
| [v1.0.1](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.0.1) | 2026-10-12 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/CoreTools-Linux.AppImage) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.1/SHA256SUMS.txt) |
| [v1.0.0](https://github.com/jaychandra1/artifacts/releases/tag/coretools-v1.0.0) | 2026-10-12 | [Windows](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/CoreTools-Windows-Setup.exe) · [macOS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/CoreTools-macOS.dmg) · [Linux](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/CoreTools-Linux.AppImage) · [SHA256SUMS](https://github.com/jaychandra1/artifacts/releases/download/coretools-v1.0.0/SHA256SUMS.txt) |

_Generated by the release workflow — do not edit by hand._
