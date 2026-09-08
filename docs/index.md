# app-legal-docs — module map

Shared repo for privacy policy / terms of service documents across this account's
apps. One folder per app, each containing `PRIVACY.md` and `TERMS.md` (some apps also
have `SUPPORT.md` or `GUIDE.md`). Managed by
the `eula` skill (`/eula` in Claude Code) — see that skill for the workflow to create
or update these docs.

## Apps covered

| Folder | App |
|---|---|
| `archiveduplicatescanner/` | Archive Duplicate Scanner |
| `bibliofuse/` | BiblioFuse (has `GUIDE.md`/`SUPPORT.md` in addition to privacy/terms) |
| `bibliofusegreptagread/` | BiblioFuse Grep Tag Reader (iOS/macOS + Windows) |
| `contentcue/` | ContentCue |
| `packetplanner/` | PacketPlanner (iOS, Android and Windows share one privacy/terms pair) |
| `paperclerk/` | PaperClerk |
| `smartdecrypt PDF ZIP/` | SmartDecrypt PDF ZIP CBZ (also has screenshots + its own `README.md`) |
| `stealerfirstaid/` | Hacked Account First Aid for Apple platforms |
| `hackaccountfirstaid/` | Hacked Account First Aid for Windows |

## Two ways this repo is consumed
1. **GitHub Pages** (rendered HTML) — per `SETUP_GUIDE.txt`: enabled with "Deploy from
   branch: main (folder: /root)". GitHub Pages auto-renders `.md` files as HTML, so
   e.g. `https://MLT-solutions.github.io/app-legal-docs/bibliofuse/PRIVACY` is a clean,
   directly-linkable URL — this is what goes into App Store Connect's privacy-policy
   URL field and each app's in-app Settings link.
2. **Raw fetch at runtime** — some apps' own privacy/terms screens fetch the raw
   markdown directly from `raw.githubusercontent.com` and render it in-app (e.g.
   `Bibliofuse-home`'s `AppPrivacy.jsx` — see that project's
   `docs/features/privacy-pages.md`), so the legal text has one source of truth
   consumed live rather than copy-pasted into each surface.

## Adding a new app
Create `<app-folder>/PRIVACY.md` and `TERMS.md` following the existing folders'
format; if another surface (a marketing site's privacy page, an in-app screen) needs
to reference it, point that surface at the raw GitHub URL for this file rather than
duplicating the text — see the `eula` skill for the guided flow that wires this up
end-to-end (docs here + app source code links + store listing + ASC privacy URL).
