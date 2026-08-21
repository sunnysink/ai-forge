# Build prompt — my link-in-bio site

Paste this into Claude (or Claude Code) to build the page. Swap the bracketed
bits for your real links and brand before you send it, or leave them and let
Claude ask.

---

Build me a link-in-bio page that replaces my Linktree. It is the page my QR code, my Instagram bio, and my emails all point to, so it has to load fast on a phone and it has to look like mine.

Structure it as a small single-page site with three views: Home, About, and Services. Use reusable components and internal client-side routing, so tapping Home, About, or Services displays that view without reloading the page. Keep everything in one self-contained index.html: vanilla JavaScript, no frameworks, no build step. Use hash routing (#home, #about, #services) so the browser back button works and I can link straight to a view.

Home is my link hub, and it has to work on its own because most people never leave it. My name, one line on what I do, my photo, and a button for each place I send people: [BOOKING LINK], [MEMBERSHIP], [FREEBIE OR EMAIL LIST], [INSTAGRAM], [ANY OFFER]. Put the one I most want tapped at the very top, reachable the moment the page loads.

About is my story in a few short paragraphs. [I will paste this.]

Services is my offers, each with a short line and a button to book or buy. [I will paste these.]

The look matters as much as the structure. Do not build a generic Claude artifact, and avoid every recognizable generic Claude pattern: no single centered card floating on a purple or blue gradient, no default system font, no emoji used as bullet points, no "Here is your page" heading, no rounded-corner-everything. Make the design feel custom to my brand. [My brand is the Forge: warm firelight on a dark ground, deep copper and ember and gold, Cormorant Garamond headings, Hanken Grotesk body. OR: use my Forge design system skill.] It should look like I paid a designer.

Hard rules:
- One single self-contained index.html file, named in all lowercase. Everything inline, no separate CSS or JS files.
- Mobile first. Most people open this from a phone. Big tap targets, nothing tiny.
- It has to work when I just open the file. I am not editing code afterward.
- Leave my real links as obvious placeholders like [BOOKING LINK] so I can find and swap them.

Ask me up to 3 questions before you build if anything is unclear. Then build the whole thing in one go.

---

## Why it is shaped this way

- **The anti-generic clause is the whole point.** It is the line that stops the
  page reading as "made by Claude." Keep it in every build prompt.
- **Home is the hub on purpose.** A link-in-bio has one job: get a tap and send
  the person out. The routing and the extra tabs are polish on top of that job,
  never in front of it. Your top button loads reachable, every time.
- **Hash routing over a JS framework** keeps it a single file with no build step,
  so it drops straight onto GitHub Pages and the back button still works.
- **Placeholders in brackets** so swapping your real links is find-and-replace,
  not code surgery.
