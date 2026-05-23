# Manifestation Meditation Page

A single-page meditation space for prayer, breath work, desire, gratitude, sound, colour, sacred geometry, and one very busy little bee.

[Open the live page](https://analysethatltd-hub.github.io/manifestation-meditation-page/)

![Mobile meditation view](docs/screenshot-mobile.png)

## What It Does

This is a static GitHub Pages site built as a quiet focus object rather than a conventional app. The page keeps the mantra and breath circle at the centre, while the controls collapse into small glassy panels so the screen stays calm.

![Desktop meditation view](docs/screenshot-desktop.png)

## Features

- Rotating manifestation mantras centred around God, identity, desire, surrender, and receiving well.
- A fixed breath-work circle that guides inhale, hold, release, and rest.
- Breath controls on the right panel for adjusting each phase length without changing the default rhythm.
- Chakra frequency controls with manual tuning, volume, and automatic upward progression.
- A top-right sound button so mobile Safari and Chrome receive a clear user gesture before Web Audio starts.
- Living sacred-geometry background with slow colour shifts and chakra-responsive glow.
- A gratitude panel with rotating gratitude seeds, a flower-planting action, a GitHub link, and a themed Green Tea support slot.
- A tiny bee that scouts, darts, pollinates flowers, leaves pollen trails, and gets startled away if you try to tap it.
- Local garden persistence, so flowers and trees gradually build up across sessions.

## Green Tea Support Setup

The Green Tea button is already in the page, but it is intentionally disabled until a donation URL exists.

To activate it:

1. Create a payment/support link with a service such as Ko-fi, Buy Me a Coffee, GitHub Sponsors, Stripe Payment Links, or PayPal.
2. Copy the public donation URL.
3. Put that URL into `GREEN_TEA_URL` near the top of the script in `index.html`.
4. Commit and push to `main`, and GitHub Pages will publish the button.

## Local Preview

This repo is just static HTML, CSS, canvas, and Web Audio. You can run it locally with any small static server:

```powershell
python -m http.server 4178
```

Then open:

```text
http://127.0.0.1:4178/index.html
```

## Notes

The frequency and chakra mappings are creative, experiential defaults rather than medical or spiritual claims. Browsers, especially on mobile, block audio until the visitor taps a control, so the top-right sound button is part of the intended experience.
