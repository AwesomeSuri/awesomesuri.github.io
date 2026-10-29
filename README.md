# awesomesuri.github.io
Portfolio page of Akbar Suriaganda

## Self-hosted libraries

`vendor/` contains pinned copies of every third-party asset the site uses, so no visitor data is sent to external CDNs. Keep it that way: the privacy policy (`privacy.html`) states that the site loads nothing from third parties.

| Folder | Package | Version |
|---|---|---|
| `vendor/inter/` | Inter variable font (latin + latin-ext), via `@fontsource-variable/inter` | 5.3.0 |
| `vendor/fontawesome/` | `@fortawesome/fontawesome-free` (core, solid, brands) | 6.7.2 |
| `vendor/aos/` | `aos` | 2.3.1 |
| `vendor/swiper/` | `swiper` (bundle) | 11.2.10 |

To update a library, download the new version from npm (for example `npm pack swiper@11`), copy the same files over the existing ones, and bump the version in this table. Do not switch back to CDN links.
