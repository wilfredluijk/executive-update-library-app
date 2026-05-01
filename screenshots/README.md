# Screenshots

The names below are referenced from the AsciiDoc chapter files. Drop new
screenshots here using the listed names.

## App frontend (`03-app-frontend.adoc`)

| File | Page |
|---|---|
| `01-app-signin.png` | Sign-in |
| `02-app-signup.png` | Sign-up |
| `03-app-forgot-password.png` | Forgot password |
| `04-app-home-mobile.png` | Journal home — mobile |
| `05-app-home-desktop.png` | Journal home — desktop |
| `06-app-library-grid.png` | Library list, grid view |
| `07-app-library-list.png` | Library list, list view |
| `08-app-entry-detail.png` | Library entry detail |
| `09-app-add-isbn.png` | Add by ISBN |
| `10-app-add-barcode.png` | Add by barcode |
| `11-app-add-manual.png` | Manual entry |
| `12-app-shelf-upload.png` | Shelf scan, step 1 — choose photos |
| `13-app-shelf-extract.png` | Shelf scan, step 2 — extraction in progress |
| `14-app-shelf-review.png` | Shelf scan, step 3 — per-book review |
| `15-app-imports-list.png` | Bulk imports list |
| `16-app-account-profile.png` | Account — profile / language / email / password |
| `17-app-account-data.png` | Account — bulk imports nav, GDPR export, danger zone |

## Maintenance Portal (`04-admin-frontend.adoc`)

MFA enrolment + verification screens are *not* listed below. MFA is
disabled in the local profile (`shelfie.admin.mfa.required=false`) and the
production posture (mandatory TOTP MFA) is described in prose only. If the
production-posture screens are ever needed, capture them against the
production profile and add `21-admin-mfa-enroll.png` /
`22-admin-mfa-verify.png` in that order — the rest of the sequence is
reserved.

| File | Page |
|---|---|
| `20-admin-signin.png` | Admin sign-in |
| `21-admin-overview.png` | Overview |
| `22-admin-users-list.png` | Users list |
| `23-admin-user-detail.png` | User detail |
| `24-admin-catalog-list.png` | Catalog list |
| `25-admin-book-detail.png` | Book detail (with merge) |
| `26-admin-sources.png` | Sources panel |
| `27-admin-moderation.png` | Moderation queue |
| `28-admin-metrics-overview.png` | Metrics overview |
| `29-admin-analytics.png` | Analytics dashboard |
| `30-admin-llm-metrics.png` | LLM metrics |
| `31-admin-lookup-detail.png` | Lookup detail (replay) |
| `32-admin-audit.png` | Audit log |

Feature-flags screen is intentionally omitted from this update; the
*Sources, moderation, feature flags* section in `04-admin-frontend.adoc`
describes it but no screenshot is attached.

## Naming convention

`<NN>-<surface>-<page>.png` where `<surface>` is `app` or `admin`. The
two-digit prefix matches the order the screenshots appear in the document.
PNG is preferred; SVG works too if a page renders cleanly at vector scale.
