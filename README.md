# MoneyLens Releases

Binary distribution releases (macOS .app bundles, signed update manifests).

- Source code lives in the private repository `yuxx0248/MoneyLens` — it is **not** mirrored here.
- Clients discover updates via the GitHub Releases API; only published (non-draft) releases with a valid Ed25519-signed `update-manifest.json` are eligible.
- Assets are built per release; tags here only anchor release objects and carry no source tree.
