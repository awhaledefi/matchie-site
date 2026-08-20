# matchie-site

The public support and legal pages for [Matchie](https://matchie.app) — the
dating app for Iraq. Served by GitHub Pages at
**https://awhaledefi.github.io/matchie-site/**

| Page | Used for |
|---|---|
| `index.html` | App Store **Support URL** and **Marketing URL** |
| `privacy.html` | App Store **Privacy Policy URL**, and linked from onboarding and Settings |
| `terms.html` | Linked from onboarding, Settings, and the App Store description |
| `delete-account.html` | App Store **Account deletion URL** — Apple requires a path that works without installing the app |

Static HTML and one stylesheet. No build step: edit, commit, push.

The app source lives in a separate private repo. When these pages change, check
that `Web` in `Matchie/Models.swift` and the URL table in `APPSTORE.md` still
agree with them.

Contact address on every page: **iamwaelalani@gmail.com**. It is the address
App Store Connect points at for privacy and support, so it has to keep working —
change it here and in App Store Connect together, never one without the other.
