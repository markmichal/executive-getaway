# Executive Getaway 2027 site: handoff

Approved direction: **A, light and airy** (Shawn's preference), chosen from four mockups made in Claude Design (Cowork).

## What's here

- `index.html`: the full one-page site. Opens in a browser as-is, with no build step.
- `img/`: Linda's photos from the Drive folder "EXECUTIVE GETAWAY 2027 IMAGES", resized for the web. Some aren't used on the page yet (stanley-mountains, stanley-keys, student-donuts, students-praying, teens-rockies).
- `ds/cru-cornerstone/`: the Cru Cornerstone design system (tokens.css, components bundle, Sora and Inter fonts, Cru logo, one stock photo). It supplies the `cs-button`, `cs-accordion` and `cs-icon` elements. Package: `@cruglobal/cornerstone-components` 0.6.2. Docs: https://cruglobal.github.io/cornerstone-design-system/

## Design rules

- Headings: Sora ExtraBold (800). Body: Inter.
- Colors: navy #1f1f47 text, Cru yellow #ffd000 accents and buttons, teal #007890 small labels, warm gray #f0efee alternate sections, white background.
- Mobile first. A sticky nav with a Register button that stays visible. Nav links hide under 900px.
- Anything still missing is marked with a purple dashed tag (`.ph` for boxes, `.pht` for inline text). Keep that style until the real content arrives.

## Sections, in order

Hero, four-photo row, welcome from Kevin Young, event summary (What/When/Where/Cost), schedule, travel, kids and teens, free time and excursions, highlights (stories: Peyton, Lake Nona, Angel), FAQ accordion, Register Today band, footer.

## Decisions (team rulings)

- Register buttons (nav, hero, Register Today band) go to FundEasy: https://v4app.fundeasy.com/events/attendance/1427/event (Linda, 2026-11-04).
- Live at https://cruexecutivegetaway.org (GoDaddy DNS to GitHub Pages, 2026-10-28). Still has the `noindex` tag while it's a draft.
- Kevin's quote is Brad's edited version, which Kevin approved. Shown at 20px desktop, 18px phone so it lines up with his photo.
- Kids and teens wording comes from the Campus Ministry Summit site, minus Summit-only logistics. No staff names or emails.
- "Next three years" strategic initiatives box removed (2026-10-28). Two passing mentions remain in Details and the FAQ.
- Travel shows only the drive time from Denver plus an Estes Park photo. No rental car, shuttle or transfer cards.
- "Join us" wording, not "You are invited." Buttons say "Register now."

## Still open

1. Whether to keep "Optional local excursions require a fee" in the Cost box and FAQ.
2. Removing the `noindex` tag when the team is ready for Google to list the site.

## Facts to keep exact

- June 24 to 27, 2027, at the Historic Stanley Hotel in Estes Park, Colorado.
- Registration is Thursday from 3 to 5 PM. The event closes Sunday at 11 AM. Guests should book return flights after 2 PM, since Denver International (DEN) is about 1.5 hours away.
- Saturday night is the opening night of Rocky Mountain Getaway at YMCA of the Rockies.
- Contact: Linda Stephens, linda.stephens@cru.org
- Footer: "The Executive Getaway is hosted by Cru / Campus Crusade for Christ, Intl." and 100 Lake Hart Dr, #2500, Orlando, FL 32832.
