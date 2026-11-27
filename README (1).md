<p align="center"><img src="assets/logo/lockup.svg" alt="TheRider" width="360"></p>

<p align="center"><b>One rider. Every venue.</b><br>
A free, open-source rider builder for bands, tour managers, promoters and venues.<br>
By <a href="https://github.com/XDDSHK">EDDSHK_PROJECTS</a>.</p>

---

TheRider lets you build your technical rider once, from stage plot to lighting plot, and send it to any venue in their own language and units. For tours and festivals it plans every changeover, down to which mic or DI can stay on stage.

No account. No paywall. Everything is saved in your own browser.

![TheRider home](docs/screenshots/home.png)

![Rider editor](docs/screenshots/rider-editor.png)

## What it does

**For bands**
- Pick what your show uses (risers, lighting, video, effects, wireless, power…). Everything else stays out of the menu and the rider
- Stage plot with risers (size, height, rolling risers), layers, colours and snap to grid
- Riser plan: drum, keys and band risers, dancer platforms, catwalks and steps with top, skirt, steps, rails, wheels and locks, plus the decks and legs to build them
- Input list with ★ must-haves, 48V, stands and "fill from stage plot"
- Monitor mixes plus a mix matrix
- Wireless (RF) list with clash warnings
- Lighting plot with standard plot symbols, groups (blinders, spots, LED), truss trim heights
- Lighting floor setup: lights on the floor, on stands or towers, with height and aim; quick starts for floor movers, uplighters, stands and towers
- Backdrops, kabuki drops, scrims and banners
- Video: LED walls, projectors, screens and TVs
- Special effects & pyro: CO2, flames, cold sparks, confetti, pyro, low fog, with cues and a safety section
- Top, front, side and 3D views with real shapes (drums, cymbals, amps, trusses, LED walls), including your backdrop artwork, LED walls with panels and content, and light beams
- Drum kit builder: kicks, double pedal, 0–4 rack toms, 0–3 floor toms, snares, cymbals, sample pads
- Lighting per song: a colour palette and lighting wish for every song, and a sheet for the house LD
- DMX patch list with modes and auto-patch
- Backline, schedule and hospitality (incl. bar, drink tickets, dietary needs)
- Power plan: drops on the stage plot, watts and amps per drop, overload warnings
- Setlists, printed big for the stage in your band's fonts
- Tape labels (desk, cables, monitor mixes) and a stagebox patch sheet
- Venue check: your rider against a venue's gear list, with what to bring
- Your own house style: band logo, colours, 60+ fonts by style or your own font file, heading options
- QR code on the PDF that links to your latest rider
- Several riders and versions (e.g. full show and acoustic), undo/redo, copy/paste
- Metric and imperial: type in one, print in the other

**For tour managers and festivals**
- Day sheets per show: travel, address with map link, times, parking, wifi, contacts, hotel. PDF or copy for WhatsApp
- Changeover timer with beeps, pace and a big clock
- Cases & gear: weights, volume, van fit, flight limits, ATA carnet / customs list
- Put riders in a running order, with tour dates
- "What to build": everything the stage needs for the whole day
- Changeovers: what to strike, set, move, and what stays, with match channels so mics and DIs keep their lines
- Shared backline detection
- Show-day mode for the stage crew
- Advancing checklist per tour date or per act
- Add a band to the running order straight from a share link
- One event rider PDF with every act's rider after it

**Output and sharing**
- What changed since the last version you sent, optionally shown at the top of the rider
- Signal flow: analog or digital split, Dante/MADI/AES50 and more, gain master and gain tracking, master/slave and clock, talkback and tie lines between FOH and monitors, recording and broadcast splits
- Monitor wishes per musician
- Black & white print version, front/side/3D views
- Effects, video and backdrop plots with their own top, front and 3D views: flames, CO2, sparks, confetti and low fog fire in 3D, with keep-clear rings
- Festivals: timetable over every stage with changeover checks, festival spec checked against every act with one hire list, wings plan, artist logistics, stage manager sheet per act
- Tours: tour book (PDF or phone page), routing with drive times and days off, venue fit (your stage plot on every venue's stage), advancing tracker per date, money and settlement, crew calls and rooming lists
- Cable list: XLR lengths from the stageboxes to every input, mic stands, power extensions and strips, measured from the stage plot
- Rigging: weight per truss and per motor point, truss types, ground support, warnings for motor and venue limits
- PA plan: main hangs, subs (L/R, arc, cardioid, flown), front fills, out fills, delays and FOH, with coverage from above, from the side and in 3D
- Exports: desk channel names (CSV), lighting patch (CSV) and MVR for grandMA3, Vectorworks and Capture
- Everything to scale: real sizes in cm, a scale bar on every plot, and the PDF prints plots at a fixed scale (1:50, 1:100…) on A4
- Fixture library: search 653 fixtures (from the Open Fixture Library, MIT) and add them with all their DMX modes, real size, power and weight
- Your own fixtures with name, maker, plot symbol and DMX modes; lighting console with software version, show file and network (grandMA3/2, ChamSys, Avolites, ETC, Hog and more); FOH and monitor desks with versions (DiGiCo, Yamaha, Allen & Heath, Midas, Avid, SSL and more)
- Hospitality: dressing rooms with a furniture plot (tables, chairs, sofas, mirrors, rails, fridge, shower), diets and the 14 EU allergens per person, meals or buy-out, and a drinks rider
- Security & barriers: Dutch-type crowd barrier, gates, crowd fences and guards, with the pit drawn in 2D, front/side views and 3D
- Three example bands (Neon Harbor, Velvet Static, Kettle & Crow) and one festival day to explore, plus six templates: club band, metal with pyro, pop show, synth duo, hip-hop + live drums, acoustic
- Edit together with bandmates (Claude version)
- PDF, web page, CSV and JSON backup
- Share a rider with one link (WhatsApp, email); whoever opens it gets a copy
- Riders in many languages, plus an email to the venue in their language (see below)

![3D view](docs/screenshots/3d-view.png)

![Effects plot in 3D](docs/screenshots/effects-3d.png)

![Example bands](docs/screenshots/example-bands.png)

![Barrier and pit security in 3D](docs/screenshots/security-3d.png)

![Signal flow](docs/screenshots/signal-flow.png)

![Dressing room plot](docs/screenshots/dressing-room.png)

![Rigging](docs/screenshots/rigging.png)

![PA plan](docs/screenshots/pa-plan.png)

![Festival timetable](docs/screenshots/festival-timetable.png)

![Venue fit](docs/screenshots/venue-fit.png)

![Changeovers](docs/screenshots/changeovers.png)

## Install on your phone

TheRider is a web app you can install. Open it in Safari or Chrome and choose *⚙ → Install on this device* (or *Share → Add to Home Screen* on iPhone). After that it works offline. When you upload a new `index.html`, change `VERSION` at the top of `sw.js` so phones pick up the update.

## Run it

It is one HTML file with no build step.

- **Locally:** download the repo and open `index.html` in a browser.
- **GitHub Pages:** in your repo go to *Settings → Pages*, pick *Deploy from a branch*, branch `main`, folder `/ (root)`, and save. After a minute it is live at `https://<your-name>.github.io/<repo-name>/`.
- **Netlify / Vercel / any static host:** upload the folder as it is.

## Features that need Claude

A few features use the Claude runtime and only work when TheRider runs as a Claude artifact:

- translating a rider (and the app itself) into another language
- importing an old rider from text or photos
- writing the email to the venue
- the shared venue database
- saving across devices
- 6-letter share codes (share links work everywhere)

On GitHub Pages or locally, these buttons show a short message instead, and everything else works as normal. Riders in English, with metric or imperial, work everywhere. Riders are saved in the browser (`localStorage`), so use *⋯ More → Back up (.json)* to keep a copy or move to another computer.

## Built with

- Plain HTML, CSS and JavaScript in a single file
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) for PDF export (loaded from cdnjs)
- QR Code encoder by Kazuhiko Arase (MIT), bundled in `index.html`
- Google Fonts

## Repo layout

```
index.html          the whole app
manifest.webmanifest, sw.js, icon-*.png, apple-touch-icon.png
                    make it installable and work offline
assets/logo/        TheRider logo (mark, mono mark, lockup)
design/tokens.json  colours, type and spacing of the house style
docs/screenshots/   images for this README
```

## Contributing

Ideas, bug reports and pull requests are welcome. Open an issue and tell us what you are touring with.

## License

[MIT](LICENSE) © 2026 Eddie Schievink (EDDSHK)


Fixture data from the [Open Fixture Library](https://open-fixture-library.org) (MIT). See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

The MVR export follows the open MVR specification (https://github.com/mvrdevelopment/spec).
