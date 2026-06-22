# vc-di-anoncreds

**AnonCreds Data Integrity Cryptosuites** — a [ReSpec](https://respec.org/) specification
defining how AnonCreds CL proofs are expressed as W3C `DataIntegrityProof` documents
(`cryptosuite`: `anoncreds-2023`).

## Status

Editor's draft. Data model is aligned with
[anoncreds-rs](https://github.com/hyperledger/anoncreds-rs) W3C support.

## View the spec

1. Clone this repository.
2. Open [`index.html`](index.html) in a browser (ReSpec loads from W3C CDN).

Or use a local static server:

```bash
npx --yes serve .
# open http://localhost:3000
```

## Examples

- [`examples/sample_credential.json`](examples/sample_credential.json) — issued credential with tag-1 `proofValue`
- [`examples/sample_presentation.json`](examples/sample_presentation.json) — VP with tag-2 embedded cred proofs and tag-3 aggregated proof

## Related specifications

- [AnonCreds Specification](https://anoncreds.github.io/anoncreds-spec/) — CL cryptography
- [VC Data Integrity](https://www.w3.org/TR/vc-data-integrity/) — `DataIntegrityProof` framework
- [vc-di-bbs](https://www.w3.org/TR/vc-di-bbs/) — structural reference for DI cryptosuite specs

## Publishing

Enable GitHub Pages on this repository to publish at:

`https://opsecid.github.io/vc-di-anoncreds/`

Set `edDraftURI` in `index.html` to match.

## Contributing

Pull requests welcome. Do **not** fork [ReSpec](https://github.com/speced/respec); this
repo only references it via script tag.
