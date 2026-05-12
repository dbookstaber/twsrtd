# Licensing posture

This document explains what is licensed how in this repository, and how commercial inquiries are handled.

## What MIT covers

The [MIT License](../LICENSE) at the root of this repository applies to:

- Documentation (`README.md`, files under `docs/`)
- Excel workbook examples under `examples/`
- Screenshots under `screenshots/`
- GitHub-side templates and CI configuration under `.github/`

These materials are free for any purpose subject to the standard MIT terms (preserve the copyright notice; no warranty).

## What MIT does not cover

The TwsRtdServer binary product itself — the registered COM component and its supporting installer — is **not** open source. Source code is not published. Binary distribution is governed by the End-User License Agreement that ships with the installer.

The MIT license on the repository content explicitly does not grant rights to the binary product.

## Commercial inquiries

Three categories of inquiry are welcome via [GitHub Discussions](https://github.com/dbookstaber/twsrtd/discussions) → **Commercial inquiries**:

1. **Source-license** — typically for trading firms / hedge funds that want in-house build and modification rights for proprietary deployment. Negotiated per-engagement.
2. **OEM / white-label redistribution** — for vendors that want to embed TwsRtdServer into another commercial product (advisor-platform Excel front-ends, etc.).
3. **Integration partnership** — joint work with IBKR or third-party platforms.

End-user binary licensing terms (single-user, single-firm, per-seat) will publish alongside the first signed Releases drop.

## Why the split?

The product surface (binary) and the documentation surface (this repository) serve different audiences. Documentation should be freely citable, forkable, and embeddable — the MIT split lets that happen without ambiguity. The binary product is the deliverable that customers actually license; commingling its license with the docs would create the wrong default.
