# Orbit Hop — site

The public landing page and privacy policy for the Orbit Hop Android game,
served with GitHub Pages.

This repository is public only because GitHub Pages needs it to be. It holds
documents and one image — no game code, and no ad unit IDs. The game itself
lives in a separate private repository.

- `index.html` — landing page
- `privacy.html` — privacy policy, linked from the Play listing
- `icon.png` — the app icon, 512×512
- `site.css`, `assets/` — local fonts and concept artwork for the landing page

The landing follows the original Orbit Hop design prototype, with copy corrected
for the Android app: 100 ranks, 100 moons, five daily missions, 20 languages,
offline core gameplay, banners from launch six, and opt-in rewarded ads from
the first launch. The current build uses test ads. The public Play download
link will be added after release. Concept artwork is labelled as illustration.

The source of the landing is maintained in the private app repository at
`Design/orbit_hop_1/code.html` and `site.css`; `node tools/build-site.mjs`
exports only the landing and its listed public assets. It preserves the policy.

**When the app changes what it collects or who it sends data to, update
`privacy.html` before that version ships.** The policy is a statement of fact
about a specific build; Play's Data Safety form has to agree with it.
