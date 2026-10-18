# Simplified Chinese UI screenshots

Captured on 2026-10-18 from the actual Dashboard application, built locally at commit `ad540c5815732e7ceb3884f0a50690362de1d7ac` (the merged Simplified Chinese refresh in PR #337).

- Locale: `zh-CN`; theme: light; viewport: 1440 × 1000 CSS pixels, scale 1.
- Routes: `/dashboard/setup`, `/dashboard/providers`, `/dashboard/quota`, `/dashboard/settings`.
- The application used a local Next.js production build with `SKIP_AUTH=1`. No application components or translations were changed for the screenshots.
- A local read-only fixture proxy supplied API responses. The `demo` user, `example.com` accounts, masked key placeholders, quotas, update versions and service status are illustrative data, not live credentials or production measurements. No real provider or production server was contacted.
- The setup screenshot shows the initial, unconfigured wizard; the other screenshots illustrate a configured demo environment.
- Browser translation-extension controls were excluded from the capture. Application text was not translated by a browser extension or edited into the images.
- Product names and technical identifiers are preserved. Some hardcoded or upstream-supplied text remains English because it bypasses the locale catalog.

These images document the Chinese UI appearance, not end-to-end verification of OAuth, billing, updates, or production connectivity. The English README's original screenshots and the shared architecture/project-structure diagrams are unchanged.
