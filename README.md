# DX Zaza — official updates

This repository only hosts the official DX Zaza update files (installers and update bundles),
read automatically by DX Zaza when it checks for a new version. No source code.

- `latest.json` — newest version, release notes, download address and SHA-256 of each file
- `latest.json.sig` — Ed25519 signature of `latest.json`, checked by every DX Zaza before it
  trusts anything here; updates not signed with the DX Zaza key are refused
- `files/<version>/` — the installers / bundles of each version
