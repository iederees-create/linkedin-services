# Cloud-Browser Handover — Restaurant Digital Menu Kit LinkedIn Upload

**For: ChatGPT cloud-browser session. Do not perform this from Claude Code — this file is the handover package.**

## ⚠️ Known gap before you start
The portfolio project page and blog post (which the launch post is meant to link to) **have not been built yet** as of this handover. Do not invent a URL. Options:
1. **Wait** until Iederees confirms the project page is live, then use that URL.
2. If publishing now, link to the **Etsy draft is not public** (drafts aren't visible to buyers) — do not link to it. In that case, publish the launch post **without a live project link**, or ask Iederees for a substitute URL before publishing.

## Repository and asset links
- LinkedIn services repo folder: `linkedin-services/restaurant-digital-menu-kit/` (commit SHA and remote URL provided separately after push — see final report)
- Post copy: `posts/01-launch.md` (ready), `posts/02-practical-example.md` and `posts/03-evergreen-overview.md` (drafts — leave unpublished)
- Images: `assets/screenshot-tv.png` (primary), `assets/screenshot-mobile.png`, `assets/screenshot-editor.png`, `assets/screenshot-print.png`
- **Not yet produced:** dedicated LinkedIn cover image, PDF carousel, demo video — see `upload-manifest.json` for exact status. Do not claim these exist.

## Field mapping
| LinkedIn field | Source |
|---|---|
| Post text | `posts/01-launch.md` (strip the "Status:" line before pasting) |
| Post image | `assets/screenshot-tv.png` |
| Image alt text | See the alt-text line at the bottom of `01-launch.md` |
| Services category | See `service-category-mapping.md` — **verify live options, this is a suggestion only** |
| Service description | `service-description.txt` |
| Featured item title | "Restaurant Digital Menu & Promotion Kit" |
| Featured item URL | **BLOCKED — see gap above** |

## Instructions for the browser agent
1. Verify you are on Iederees Francis's **developer/NextGenWebs** LinkedIn profile — not any trading-related profile.
2. Let the human handle login, CAPTCHA and 2FA entirely. Do not attempt to bypass or automate these.
3. Check existing Services, posts and Featured items for anything already covering this offer — do not create a duplicate.
4. Add this service offer through the available Services controls, preserving all existing services already listed. Adapt to whatever categories/description fields LinkedIn's live interface actually offers.
5. Publish **one** launch post (`posts/01-launch.md`) with `assets/screenshot-tv.png` — **only if a real project/demo URL is available to link**; otherwise hold and report back rather than posting without a working link.
6. Add the published post (or the project URL, once available) to Featured.
7. Leave `posts/02-practical-example.md` and `posts/03-evergreen-overview.md` unpublished.
8. After acting, update `publication-status.json` in this folder with the real outcome (URLs, timestamps, what was/wasn't done).
9. Report any LinkedIn feature that doesn't support something in this handover (e.g., no package/pricing tables) — do not claim it was completed if it wasn't possible.
