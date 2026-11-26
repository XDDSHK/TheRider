# TheRider

One rider. Every venue.
A free, open-source rider builder for bands, tour managers, promoters and venues.
By EDDSHK_PROJECTS.

TheRider lets you build your technical rider once, from stage plot to lighting plot, and send it to any venue in their own language and units. For tours and festivals it plans every changeover, down to which mic or DI can stay on stage.

No account. No paywall. Everything is saved in your own browser.

Rider editor

What it does
For bands

Stage plot with risers (size, height, rolling risers), layers, colours and snap to grid
Input list with ★ must-haves, 48V, stands and "fill from stage plot"
Monitor mixes plus a mix matrix
Wireless (RF) list with clash warnings
Lighting plot with standard plot symbols, groups (blinders, spots, LED), truss trim heights
DMX patch list with modes and auto-patch
Backline, schedule and hospitality
Your own house style: band logo, colours and fonts on the rider
Several riders and versions (e.g. full show and acoustic), undo/redo, copy/paste
Metric and imperial: type in one, print in the other
For tour managers and festivals

Put riders in a running order, with tour dates
"What to build": everything the stage needs for the whole day
Changeovers: what to strike, set, move, and what stays, with match channels so mics and DIs keep their lines
Shared backline detection
Show-day mode for the stage crew
One event rider PDF with every act's rider after it
Output

PDF, web page, CSV and JSON backup
Riders in many languages, plus an email to the venue in their language (see below)
Changeovers

Run it
It is one HTML file with no build step.

Locally: download the repo and open index.html in a browser.
GitHub Pages: in your repo go to Settings → Pages, pick Deploy from a branch, branch main, folder / (root), and save. After a minute it is live at https://<your-name>.github.io/<repo-name>/.
Netlify / Vercel / any static host: upload the folder as it is.
Features that need Claude
A few features use the Claude runtime and only work when TheRider runs as a Claude artifact:

translating a rider (and the app itself) into another language
importing an old rider from text or photos
writing the email to the venue
the shared venue database
saving across devices
On GitHub Pages or locally, these buttons show a short message instead, and everything else works as normal. Riders in English, with metric or imperial, work everywhere. Riders are saved in the browser (localStorage), so use ⋯ More → Back up (.json) to keep a copy or move to another computer.

Built with
Plain HTML, CSS and JavaScript in a single file
html2pdf.js for PDF export (loaded from cdnjs)
Google Fonts
Repo layout
index.html          the whole app
assets/logo/        TheRider logo (mark, mono mark, lockup)
design/tokens.json  colours, type and spacing of the house style
docs/screenshots/   images for this README
Contributing
Ideas, bug reports and pull requests are welcome. Open an issue and tell us what you are touring with.

License
MIT © 2026 Eddie Schievink (EDDSHK)
