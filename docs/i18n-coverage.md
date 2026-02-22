# ZeroClaw i18n Status (Archived)

Last updated: **February 22, 2026**.

## Decision

ZeroClaw no longer maintains the legacy `docs/i18n/*` documentation tree.

- The old `docs/i18n/` directory has been removed.
- Vietnamese docs are now referenced directly under `docs/vi/`.
- Existing localized entry READMEs may remain, but `docs/i18n/*` is no longer a supported docs contract.

## Migration Notes

- Old path pattern: `docs/i18n/vi/...`
- Current path pattern: `docs/vi/...`

If you find stale links to `docs/i18n/*`, replace them with the equivalent `docs/vi/*` paths.
