# peydi-legal

Public legal pages for [Peydi](https://github.com/aaronmusa/peydi-ios), a payday budget tracker for iPhone.

Kept in its own repo so the copy can be corrected without shipping an app release.

| Page | URL |
|---|---|
| Landing | `/` |
| Privacy Policy | `/privacy/` |
| Support | `/support/` |
| Terms of Use | Apple's Standard EULA (linked out, not hosted here) |

## Deploying

GitHub Pages, deploying from `main` at the repo root. Push to `main` and Pages republishes.

## Rules

- The privacy policy must keep matching `App/PrivacyInfo.xcprivacy` in the app repo and the App Store Connect nutrition labels. If one changes, change all three.
- Anything the app starts writing to iCloud, including the shared household zone, is a policy edit as well as a code change.
- Bump the effective date in `privacy/index.html` whenever the policy text changes materially.
