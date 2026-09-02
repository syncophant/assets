# Syncophant Assets

Canonical design sources and product assets for Syncophant.

## Layout

- `design/`: design canvas exports and source files.
- `app/`: Flutter app logos and tray icons.
- `landing/`: landing-page images and fonts.
- `screenshots/`: current product captures. Files are labelled by form factor:
  `desktop-*` is a 2x macOS window capture and `mobile-*` is an iPhone
  device capture.

## Screenshot catalog

| Desktop | Mobile |
| --- | --- |
| `desktop-pairings.png` | `mobile-pairings.png` |
| `desktop-accounts.png` | `mobile-accounts.png` |
| `desktop-activity.png` | `mobile-activity.png` |
| `desktop-settings.png` | `mobile-settings.png` |
| `desktop-pairing-form.png` | `mobile-pairing-form.png` |
| `desktop-pairing-detail.png` | `mobile-setup-code.png` |
| `desktop-filters.png` | |
| `desktop-delete-guard.png` | |

The app and landing repositories vendor the runtime files they need so each
build remains independent.

## License

AGPL-3.0. See [LICENSE](LICENSE).
