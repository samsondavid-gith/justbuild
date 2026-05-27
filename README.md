# First Build — Platform Handover

A school-version sibling of Just Build for engineering college students. Same DNA, school-shaped.

## What this is

A static facilitator console mirroring `platform.html`, adapted for Class 8–10 Minifounders doing their First Build. Dark mode, projection-optimised, no backend, no shared state with the college platform.

Hosts at: `justbuild.orangecaterpillar.com/platform-school`

## Files in this folder

- `platform-school.html` — the console (single file, all CSS and JS inline)
- `sessions-school.json` — 12 sessions of content driving the console
- `caterpillar.png`, `butterfly.png` — journey bookend artwork (shared with college version)
- `logo.png`, `favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png`, `apple-touch-icon.png` — Orange Caterpillar brand assets

Drop all of these in the same folder on Render. Done.

## Login

- ID: `firstbuild`
- Password: `minifounder`

Change in `platform-school.html` near the top of the script block (`LOGIN_ID`, `LOGIN_PW`).

## Keyboard shortcuts

- `→` or `Space` — next screen
- `←` — previous screen
- `T` — pause/resume the session timer
- `J` — open jump menu

## What's different from the college platform

Same architecture and visual identity. Differences live in scope and tone, not code:

### Identity
- **Role:** Minifounders (not Solopreneurs)
- **Program:** First Build (not Just Build)
- **Pipeline framing:** First Build → Just Build → next program

### Scope
- **Duration:** Weekend + 3 weeks office hours + Demo Day (vs college's 6 weeks)
- **Audience:** Class 8–10 students (ages 13–15)
- **Artifacts (6, not 8):** Ideation + AI App + Website + Audio + Video + Brochure
- **Dropped:** Chatbot, Make.com agent, LinkedIn founder video
- **Added as artifact:** Ideation sheet (recommend adding this to the college version too)

### Stages (5, renamed)
- Pick → Build → Launch → Polish → Share
- (College: Ideate, Build, Launch, Brand, Automate, Ready to show)

### HMV softening
- Renamed to "the three checks": Real person · Real problem · Demoable
- Treated as mild guidance, not a strict gate
- Reach axis dropped (school students reach is naturally local)

### Sessions (12 total, vs college's 16)
- 0: Kickoff (30 min)
- 1: Pick your idea (90 min)
- 2: Build your AI app (105 min)
- milestone: Lunch check (30 min)
- 3: Deploy and write the website (150 min)
- 4: Launch the website (150 min) — Day 2
- 5: Audio, video, brochure (165 min) — Day 2
- interim-demo: Interim show (60 min)
- 6: What happens next (60 min)
- 7: Week 1 office hours (60 min)
- 8: Week 2 office hours (60 min)
- 9: Week 3 office hours (60 min)
- 10: Demo Day (180 min)
- 11: What you do now (30 min)

### Pre-work
- **None.** Facilitator presents 4–5 sample ideas in the room. Students pick.
- (College: 5-question pre-work narrowing 25–30 ideas to 3)
- No prework.html needed.

### Portfolio URL pattern
`justbuild.orangecaterpillar.com/{school}/{cohort}/{name}`
(College: `justbuild.orangecaterpillar.com/{college}/{cohort}/{name}`)

## Open items

These were locked conceptually but not built:
1. The 4–5 sample ideas the facilitator presents at Session 1. Same across all cohorts. Need writing.
2. The school waitlist / signup page (parallel to the college `index.html`).
3. The school showcase page (parallel to `showcase.html`).
4. Pricing copy on the public-facing page. Discussed: ₹9,999 v1.

## Visual continuity with the college program

- Same colour tokens (`#C17D2A` accent on `#0A0A0A`)
- Same typography (Plus Jakarta Sans serif + Inter sans)
- Same caterpillar-to-butterfly journey wave
- Same projection-first dark mode
- Same login-overlay-into-console pattern
- Same session-by-session screen-pile structure (welcome, housekeeping, journey-map, then per-session set-the-stage / questions / prompts / build / output-capture / end)

The two consoles look like siblings, not strangers. That's intentional.
