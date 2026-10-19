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

Hero, four-photo row, welcome from Kevin Young, event summary (What/When/Where/Cost), schedule, travel, kids and teens, free time and excursions, highlights, strategic initiatives, FAQ accordion, Register Today band, footer.

## Still open

1. FundEasy registration URL. Every Register button points to `#` for now.
2. Kevin Young's headshot, quote and bio.
3. Kids' Club, Kids' Squad and teen program: photos, descriptions, and the staff lead names and emails.
4. Excursion photos: Rocky Mountain National Park, downtown Estes Park, horseback riding, Stanley Hotel history tour. Use only free-licensed photos (Unsplash, Pexels, or NPS public domain) and log the credits.
5. Two more highlight stories (Lake Nona High School football is the first). These may become Vimeo embeds.
6. Strategic initiatives summary and download file.
7. Travel details: rental car, shuttle and group transfer.
8. Hosting and domain (cruexecutivegetaway.com was mentioned). Josh Dean owns what can be hosted on Cru domains.

## Facts to keep exact

- June 24 to 27, 2027, at the Historic Stanley Hotel in Estes Park, Colorado.
- Registration is Thursday from 3 to 5 PM. The event closes Sunday at 11 AM. Guests should book return flights after 2 PM, since Denver International (DEN) is about 1.5 hours away.
- Saturday night is the opening night of Rocky Mountain Getaway at YMCA of the Rockies.
- Contact: Linda Stephens, linda.stephens@cru.org
- Footer: "The Executive Getaway is hosted by Cru / Campus Crusade for Christ, Intl." and 100 Lake Hart Dr, #2500, Orlando, FL 32832.
