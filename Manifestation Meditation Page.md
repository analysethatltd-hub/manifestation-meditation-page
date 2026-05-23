# Manifestation Meditation Page

## Purpose

Create a single static web page that helps Glenn focus on stillness, identity, desire, and quiet manifestation without presenting itself as a religious application.

The page should feel like a contemplative object, not an app. It now includes a discreet chakra tuning panel because the user explicitly requested audio controls after the original no-controls direction.

## Vault Basis

- `AGENTS.md` requires active work to live in `projects/` and asks Codex to say when a topic is not backed by the vault.
- No direct source note was found in `notes/` for manifestation, meditation, mantra language, Web Audio, or frequency design on 2026-05-18.
- The visual system is therefore a creative implementation guess, with only adjacent taste guidance from `ideas/Synthesia Constraint-Led Video Craft.md`: intentional structure should prevent generic output.

## Experience Direction

- Full-screen, single-page meditation environment.
- No user actions required or displayed.
- Slow sacred-geometry motion, light trails, and breathing rhythm.
- A visible breath-work guide that cycles through inhale, hold, release, and rest without requiring user action.
- Mantra text that cycles quietly without requiring interaction.
- Ambient tone generation using browser Web Audio where allowed by browser autoplay policies.
- User preference as of 2026-05-18: base the vibration/noise layer on 432 Hz and related subharmonics/harmonics. This is treated as an experiential creative direction, not a vault-backed health or spiritual claim.
- Background colour should continue shifting slowly to feel more mentally activating while keeping the page meditative.
- Respect reduced-motion preference with a calmer still state.
- Balance review on 2026-05-18: keep the page centered around one ritual axis. Avoid splitting attention between multiple large circles; use the mantra, intention word, mandala, breath guide, and footer as one vertical composition.
- Sacred geometry refinement on 2026-05-18: favor deliberate Flower-of-Life-style circles, vesica relationships, hexagons, triangles, and Metatron-style connecting lines over loose decorative traces. Keep the breath circle fixed at the exact viewport center so text changes cannot move the focus point.
- Karpathy guardrails rebuild on 2026-05-22: rebuild `index.html` as one explicit-state static page. Keep scope surgical, avoid new dependencies, preserve the no-action meditation objective, and verify with syntax plus browser checks.
- Chakra tuning update on 2026-05-23: user explicitly requested controls, which supersedes the earlier no-controls constraint. Add a small manual control panel for chakra frequency tuning, default to Root, auto-ascend upward through the chakra list, and treat chakra-frequency mappings as experiential creative defaults rather than vault-backed health claims.
- Text cleanup update on 2026-05-23: user clarified that the large rotating mantras should remain the star. Remove distracting small supporting copy such as eyebrow/subline/intent/footer/cue text, while keeping the centered breath guide and chakra controls.
- Living garden update on 2026-05-23: add a playful ambient monk and timestamp-based garden growth layer, with flowers and occasional trees saved locally over time. Keep this layer small, non-interactive, and outside the central breath focus so it enriches long meditation sessions without competing with the mantra.
- Publishing update on 2026-05-23: page is published from `analysethatltd-hub/manifestation-meditation-page` using GitHub Pages from the `main` branch root. Live URL: `https://analysethatltd-hub.github.io/manifestation-meditation-page/`.
- Mobile and bee update on 2026-05-23: minimize the chakra tuning panel by default on mobile, support tap and swipe expand/collapse gestures, replace the monk with a bee that scouts, darts, hovers, pollinates, and leaves growth behind, and start Web Audio from explicit touch/click/key gestures for mobile browser compatibility.
- Three-panel update on 2026-05-23: add collapsed left/right glass panels for gratitude/support and breath timing, add a top-right sound toggle for mobile browser audio startup, add bee startle behavior on touch/click proximity, and create a GitHub README with screenshots. The Green Tea support link remains a configurable placeholder until the user provides a donation URL.
- Mobile audio repair on 2026-05-23: make the top-right sound button the only creator of the Web Audio graph, prevent one mobile tap from double-toggling via pointer/touch/click event chains, and add a tiny Web Audio unlock pulse for stricter iOS/WebView audio startup behavior. This follows browser autoplay policy guidance that Web Audio must be resumed from user interaction.
- Non-religious language update on 2026-05-23: remove explicit God/prayer wording from the public page and README so the project presents as universal manifestation meditation rather than a religious application.
- Iconology update on 2026-05-23: set the opening mantra to `I am aligned.` and bring the preferred mobile-use image language into the app through small non-religious SVG symbols for gratitude/heart, seeds, breath waves, chakra/root, sound, tea, and source links.

## Files

- `index.html`: self-contained page with CSS, canvas motion, text rhythm, and Web Audio tone layers.
