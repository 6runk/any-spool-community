# AnySpool

**Program your Elegoo filament spools — free, instant, no account needed.**

→ **[anyspool.de](https://www.anyspool.de)**

---

## What is this?

Elegoo's Neptune and other CANVAS-compatible printers read NFC tags on filament spools to auto-configure print settings. AnySpool lets you program blank NTAG213 stickers with the correct Elegoo payload — so any filament you own works like a genuine Elegoo spool.

- Works with any 1.75mm filament, any brand
- Generates the correct NFC data for Elegoo CANVAS
- Android: write directly from your browser via Web NFC
- iOS: copy hex commands for NFC Tools app
- No account, no tracking, no cookies — runs entirely in your browser
- Free forever

---

## Supported printers

Any Elegoo printer that reads NFC filament tags, including:

- Neptune 4 Pro / Max / Plus
- Neptune 4 X
- Other CANVAS-compatible models

---

## Roadmap

You can follow what's planned, in progress, and shipped on the [project board](../../projects).

Have a feature request or found a bug? [Open an issue](../../issues/new/choose) — takes 30 seconds.

---

## Requesting a filament

Don't see your filament brand or color in the catalog?

[Open a filament request issue](../../issues/new?template=filament_request.md) and include:
- Brand and material (e.g. Bambu Lab PLA Basic)
- Color name and hex code if you know it
- A link to the product page

Popular requests get prioritized. If a brand has a public product API or filament database, that helps a lot.

---

## FAQ

**Does this work with Bambu / Creality / other brands?**
Right now the catalog focuses on Elegoo filaments and the NFC payload format is Elegoo-specific. Support for other printer ecosystems is on the roadmap.

**Will this void my warranty?**
No. You're programming a sticker, not modifying the printer.

**How accurate are the NFC payloads?**
The payload format is reverse-engineered from genuine Elegoo spools. It works reliably for material type, color, and print temperature. If you notice incorrect behavior on your printer, please open an issue with your printer model and the filament you used.

**Is the source code available?**
Not currently. This repo is for community feedback and tracking only.

---

## Links

- [Live site](https://www.anyspool.de)
- [Report a bug](../../issues/new?labels=bug)
- [Request a feature](../../issues/new?labels=feature-request)
- [Request a filament](../../issues/new?labels=filament-request)

---

*AnySpool is an independent project and is not affiliated with Elegoo.*
