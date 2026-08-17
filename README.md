# DIU OS manifesto

Epistemic charter and prior-art record for DIU OS — **Scientific Compute Infrastructure**, not EdTech and not a DeSci protocol.

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

## Living text

Read [`MANIFESTO.md`](MANIFESTO.md) (updated 12 Jul 2026). That file is the current charter.

## Prior-art snapshot (do not treat as product spec)

Release **v1.0.0** (28 Dec 2025) — PDF / DOCX / OpenTimestamps proof. Historical IP declaration only. It describes an earlier stack (CDC, MCP tutoring, NFT certificates) that is **not** what ships on [diu-os.com](https://diu-os.com).

| File | Role |
|------|------|
| `MANIFESTO.md` | Current charter |
| `DIU_OS_Manifesto_PUBLIC_v1.pdf` | Dec 2025 snapshot (also on GitHub Releases) |
| `DIU_OS_Manifesto_PUBLIC_v1.pdf.ots` | OpenTimestamps proof for that PDF |
| `LICENSE` | Apache-2.0 |

### Verify the December snapshot

```bash
pip install opentimestamps-client --break-system-packages
ots verify DIU_OS_Manifesto_PUBLIC_v1.pdf.ots
```

## What this org publishes

- This manifesto (Apache-2.0)
- [diu-contracts](https://github.com/diu-os/diu-contracts) — Stylus contracts on Arbitrum **Sepolia** (MIT)

Platform source is not in `github.com/diu-os`. Product: [diu-os.com](https://diu-os.com). Contact: contact@diu-os.org
