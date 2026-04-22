# Milica Portfolio Guide

This file tracks the current state of the website, content decisions, asset locations, and working rules for future updates.

## Purpose

- Keep the website consistent while we continue editing it
- Track which sections are already customized
- Track where assets belong
- Make future edits faster and cleaner

## Main Project Folder

- Website root:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO`

## Main Files We Edit Most

- HTML:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/index.html`
- Main CSS:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/css/style.css`
- Main JS:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/js/custom.js`

## Current Visual Direction

- Overall style:
  clean, feminine, premium, soft, polished portfolio presentation
- Main mood:
  white/light base with refined soft gradients and elegant rounded shapes
- Accent colors currently used:
  warm gold, soft pink, muted blue-gray
- Video section direction:
  premium glassy overlays, subtle gradients, clean grid layout
- Shape language:
  rounded cards, pill-style title badges, soft layered shadows
- Page loader:
  custom circular progress loader with site-color gradient ring, moving percentage, and no letter/monogram mark in the center; do not use the old generic GIF loader
- Avoid:
  raw template placeholders, visible ugly file names, overly harsh dark UI, cluttered layouts

## Personalized Identity

- Name:
  Milica Milosavljevic
- Main title:
  Creative Project Manager
- Hero summary:
  Leading creative projects from concept to final delivery while ensuring clarity, structure, and high-quality execution.
- Hero skills:
  Project Coordination, Client Communication, Timeline Management, Process Improvement, Workflow Optimization, Creative Production, Problem Solving, Attention to Detail
- Hero skills layout:
  soft 4-by-2 grid on desktop; subdued enough that the title and intro remain primary
- About intro:
  A little about how I work

## Sidebar / Navigation

Current role:

- fixed left sidebar with profile image, section navigation icons, and social links
- sidebar should feel premium, clean, and visually lighter than the main page content
- sidebar must not show its own scroll option; page scroll should remain the only visible scroll behavior

Profile image:

- current approved profile image:
  `assets/ja /CVnaocare.png`
- use only this one profile image in the sidebar
- do not rotate/swap between `CVpic.png` and `CVnaocare.png`
- the old non-glasses sidebar profile image should not be re-added unless the user explicitly asks
- profile frame should be elegant and subtle:
  thin soft gradient ring, light glow, soft shadow
- avoid overly strong/crooked/conic rings that make the frame look strange or too busy
- profile image may have a small hover interaction:
  gentle lift/scale and slightly stronger glow
- hover interaction should stay smooth and premium, not jumpy or distracting

Navigation items:

- sidebar currently keeps only these functional icon links:
  1. About Me
  2. Portfolio / Selected Work / My Projects
  3. Contact
- the Experience sidebar icon/link is intentionally hidden and should stay removed from visible navigation
- About Me should link to the section headed:
  `About Me / A Little About How I Work`
- Portfolio should link to:
  `Selected Work / My Projects`
- Contact should link to:
  `Contact me / Let’s create something cool together.`

Sidebar icon assets:

- use the exact PNG files provided by the user from:
  `assets/ikonice`
- do not redraw, reinterpret, recolor, flip, crop, or replace these icons with Font Awesome/SVG versions
- About icon must use:
  `assets/ikonice/Screenshot_2026-04-21_at_02.17.53-removebg-preview.png`
- Portfolio icon must use:
  `assets/ikonice/Screenshot_2026-04-21_at_02.10.11-removebg-preview.png`
- Contact icon must use:
  `assets/ikonice/Screenshot_2026-04-21_at_02.10.22-removebg-preview.png`
- use the transparent `removebg-preview` icon files, not the older white-background screenshots
- About icon should show the full illustration as provided, centered inside the card
- do not force the About icon to look like it is emerging from the bottom if that crops or ruins the image
- icon cards should be smaller than the profile image so the profile remains the main visual focus
- current intended icon card size is small/premium, around the low-70px range
- icon cards can have soft shadows, subtle gradient border, and gentle hover lift
- avoid making icon cards as visually heavy or large as the profile avatar
- navigation icon cards are intentionally smaller now, around high-50px card size

Sidebar contact block:

- the old `Follow Us` label and generic social icon list should not be used
- sidebar contact area should be labeled `Let’s connect!`
- it should show only two contact actions:
  - Gmail, linking to `mailto:milosavljevicmilica2001@gmail.com`
  - LinkedIn, linking to `https://www.linkedin.com/in/milica-milosavljevic`
- this block should visually differ from the three main navigation icons above it
- contact links should feel like a compact premium dock, not section-navigation icons
- Gmail and LinkedIn should be round icon buttons inside one small shared pill/dock
- do not show the Gmail/LinkedIn text labels in the sidebar dock unless the user asks; the icons should carry the action
- keep this dock in the empty middle space below the three navigation icons
- never overlap the `Let’s connect!` dock with the Contact navigation icon above it
- the dock may have a subtle glassy backing plate, fine accent line, and soft glow so the section feels intentionally designed

## About Section

- Hero/about image replaced with Milica portrait
- Signature removed from the about section
- About text customized from CV
- About text now appears as one concise paragraph describing creative project management, IS/technology background, coordination, workflow ownership, and creative delivery
- About section includes a `Tools I use` panel with two groups:
  - Creative production: Figma, Canva, Photoshop, Illustrator, Premiere Pro
  - Project flow: Asana, Trello, Notion, Slack, Office
- `Creative production` should appear as the first row/group
- `Project flow` should appear as the second row/group
- tools panel should stay lightweight: no heavy nested card frame and no individual boxed cards around every icon
- tool icons should be a little larger and read like a clean software stack
- tool labels should stay lighter/subtle so icons remain the focus
- Photoshop uses clean transparent asset `assets/ikonice/photoshop-clean.png`, not the old checker-background JPG
- `Tools I use` heading should have a designed accent, not plain text only
- about location detail `Based in Belgrade` sits under the portrait/image area using the site location icon
- hero portrait also includes the same `Based in Belgrade` location detail under the image
- hero and about location details should read like floating glass badges with soft shadow, overlapping the bottom of the cutout so the person appears to emerge from the badge
- hero image currently uses transparent cutout `assets/ja /CVslikabezpozadine.png`, displayed without a gradient/photo background; use shadow/depth instead
- about portrait currently uses transparent cutout `assets/ja /pokazbezpozadine.png`, also without a gradient/photo background
- both cutouts should have a visible soft shadow/aura behind the person for depth
- about pointing image is intentionally shifted lower so the pointing gesture aligns with the text area
- cutout images should animate once when they enter view with a noticeable downward settle; hover movement should be visible but subtle and intentional, not a continuous floating loop
- `Hire Me` removed
- CV actions should include both `Open CV` and `Download CV`
- current expected CV path is `assets/Milica-Milosavljevic-CV.pdf`
- Hero section already visually redesigned to look more premium than the original template
- About section should remain clean and editorial, not busy or over-decorated

## Education Section

Education items currently used:

1. Master’s Degree in Information Systems Engineering
2. Bachelor’s Degree in Information Systems and Technology
3. Cambridge English Certificate in ESOL

Dates currently set:

- Master:
  2024-2025
- Bachelor:
  2020-2024
- Education timeline labels were widened so long faculty text fits correctly
- Non-education placeholder content was removed from this section

## Experience Section

Current real experience entries:

1. Creative Project Coordinator
   Moseable Studio
   2025-Present

2. Service Desk Specialist
   NCR Atleos
   2025-Present

3. Client Operations & Process Associate
   Addiko bank
   2024-2025

4. IT Teacher
   KiberOne Programming School
   2023-2025

Color direction currently used:

- Moseable Studio:
  soft orange-pink family
- NCR Atleos:
  dark green family
- Addiko bank:
  red family
- KiberOne Programming School:
  bright yellow family, based on the user-provided yellow reference

Layout direction currently used:

- experience entries are stacked vertically
- position title is black and in one line
- company name sits below and uses accent color
- year blocks are color-matched to the company accent

## What I Do Section

Current section title:

- Small heading:
  Let's take a look
- Main heading:
  What I Do

Current cards:

1. Project Coordination
2. Graphic Design
3. Creative Production
4. Video Editing
5. Workflow Organization
6. Task Coordination
7. Running Social Media Accounts
8. Teaching
9. Web Design & Development

Current image source folder:

- `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/images`

Current illustration files used there:

- `download.png`
- `download-1.png`
- `download-2.png`
- `download-3.png`
- `download-4.png`
- `download-5.png`
- `download-6.png`
- `download-7.png`
- `download-8.png`

Current icon sizing choice:

- service illustrations intentionally enlarged for stronger visual presence
- current display target is large and expressive, not tiny icon-sized

Current card topics:

- this section should stay practical and skill-based, not vague or generic
- card copy is already approved and should be preserved unless user changes it
- all `What I Do` cards should stay equal height and visually aligned in the grid

## Projects Section

Current section heading:

- Small heading:
  Selected Work
- Main heading:
  My Projects
- Intro text:
  A few selected projects - the rest didn’t fit on one page. :)
- Intro text is intentionally bold
- Section should feel curated, not exhaustive
- Project cards should feel like premium case-study previews, not a generic gallery

### Current project cards

1. Brand Guidelines & Visual Standards - Moseable Studio
2. Client Content Production
3. PaceUp - Mobile App Design System
4. Chari AI - Contest-Winning Product Promo Video

Cards removed or merged into broader structure:

- Newsletter Design is no longer a standalone top-level project card
- Online Banner Design is no longer a standalone top-level project card
- Social Media Posts is no longer a standalone top-level project card
- these now live under `Client Content Production`

Template sections removed from the page:

- the full `Testimonial / words from clients` section is removed
- testimonial/sidebar links are removed from `index.html` and `blog.html`
- the full `My Blog / Recent News` template section is removed
- the old template sponsor/responsor strip is removed
- do not reintroduce these placeholder sections unless the user explicitly asks for them

### Moseable Project

Current setup:

- Linked PDF presentation is used as the main showcase
- PDF path:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/projects/moseable-brand-guidelines/Moseable-Brand-Guidelines-2026.pdf`
- Generated preview image path:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/projects/moseable-brand-guidelines/Moseable-Brand-Guidelines-2026.pdf.png`
- Card title currently displayed as:
  `Brand Guidelines & Visual Standards - Moseable Studio`
- The old `Brand Systems` label was removed
- This project card uses a blue-gray premium badge style for the title
- The title badge should feel integrated with the card, wide enough for clean wrapping, and visually elegant
- The PDF preview is the main visible showcase asset for this project
- Button text currently used:
  `Open Brand Guidelines Presentation`

### Client Content Production

This card is intentionally structured as:

- main title:
  Client Content Production
- sub-sections:
  1. Short-form Video Editing
  2. Newsletter Design
  3. Online Banner Design
  4. Social Media Posts
- Main title should visually match the premium badge treatment of the Moseable title
- The user explicitly wants this card to stay simple:
  one main title + four clear sub-headings + space for portfolio materials under each
- Avoid overcomplicating this card or turning it into a broken masonry-style layout
- Keep this project organized, modular, and easy to keep expanding

### Short-form Video Editing

Current helper line:

- Take a look at just a few of them... there’s more where that came from!

Current videos are loaded from:

- `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/videos`

Currently connected videos:

1. `WhatsApp Video 2026-04-17 at 18.45.47.mp4`
2. `CudniReelFINAL!mp4.mp4`
3. `BioStile - Magnezijum - Aktivni & Sport - Angle 4 - bundle Q10.mp4`
4. `BioStile - Collagen - Beauty Prevention - Angle 1 - sjajna koza - samo kolagen.mp4`
5. `BioStile - Magnezijum - Aktivni & Sport - Angle 2 - bundle Q10.mp4`
6. `BioStile - Magnezijum - Stres i Posao - Angle 1 - nervoza - bundle q10.mp4`
7. `UGCVIDEO.mp4`
8. `hook7TeloZglobovi5PAKET.mp4`

Current style direction for that video block:

- premium video grid
- 4 columns on desktop
- cleaner 2-row style layout when enough videos are shown
- no visible raw file names or long technical labels in the UI
- overlay hides while video is playing
- grid preview videos may use cropped cover framing, but fullscreen playback must use `object-fit: contain` so the full video image is visible
- play control should be:
  very transparent, glossy, glass-like, and shaped between a rectangle and a rounded square
- user prefers the play button to be much more transparent than before
- video block should avoid looking monochrome and lifeless; subtle gradients and tasteful accents are welcome

### Experience section

- keep the line under `My Experience`:
  `Just a few highlights - part of the journey, still building the rest!`
- it should remain bold and centered under the main heading

### Newsletter Design / Online Banner Design / Social Media Posts

These remain inside `Client Content Production` and should be treated as expandable portfolio sub-sections.

For each of them:

- keep a clear heading
- keep a short description
- keep a tidy placeholder/showcase area ready for real uploads
- design should stay cleaner than the video section unless the user asks otherwise

### Newsletter Design

Current state:

- uses the same premium section-heading treatment as `Short-form Video Editing`
- currently populated with 3 real newsletter examples
- current image order:
  1. `3.png`
  2. `news2.png`
  3. `4.png`
- newsletter previews should stay compact and teaser-like, not full-height on-page
- use cropped premium preview cards instead of exposing the entire long newsletter inside the layout
- interaction should favor `click to open` full newsletter view inside the page
- newsletter cards open a custom full-image viewer with an `X` close button, Escape-to-close behavior, backdrop click close, and simple zoom controls
- newsletter viewer should start in fit-to-screen mode so the full newsletter is visible first, then allow zooming in manually
- do not send newsletter cards to a raw browser image view unless the user explicitly asks again
- do not use generic lightbox/gallery behavior for newsletter cards unless it preserves the approved close and zoom controls
- visible UI should feel curated and stylish, not like raw image thumbnails
- avoid designs that force excessive scrolling just to get past newsletter examples

### Online Banner Design

Current state:

- uses the same premium section-heading treatment as `Newsletter Design`
- includes bold helper line:
  `Just a few of them - and yes, they speak different languages!`
- banners should not be visible directly on the page
- use large premium `reveal` buttons/cards that open the actual banner asset on click
- button/card colors can vary, but should stay within the site palette and feel polished
- current intro text:
  `Designed banner sets tailored to different campaigns, ensuring strong visual consistency and clear messaging.`
- second intro line:
  `Hero, square, desktop, mobile...different shapes, same goal - to catch attention and make the message land.`
- current cards use blurred real banner previews in the top reveal area
- CTA text currently used:
  `Click to reveal`
- do not show `Banner 01/02/...` labels
- current asset order:
  1. `2_Valentines Day - GOOGLE.pdf`
  2. `3_LIVER PROTECT - HERO.pdf`
  3. `5_MALOPRODAJA - STAMPA.pdf`
  4. `2_KOLAGEN  - HERO.pdf`
  5. `5_DESKTOP PP - HERO BANER - BMT Q10.pdf`
  6. `9_MOBILE & DESKTOP - HP & PP - SQUARE BANER - Q10 BUNDLES - 1000x1000.pdf`
  7. `10_DESKTOP PP - HERO BANER - Q10 BUNDLE.pdf`
  8. existing banner previews continue below in the current 3x3 layout
- current layout:
  3 rows with 3 cards each
- preview image folder:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/banner-previews`
- last button wording:
  `Reveal Hero Banner (last one, I promise)`

### Social Media Posts

Current state:

- section title uses the same premium pill-style title treatment as `Newsletter Design`
- current sub-sections:
  1. `Carousel Posts`
  2. `Product Bundle Posts`
- `Carousel Posts` description:
  `Turning ideas into swipeable slides that feel easy to follow and actually keep people engaged.`
- bold helper line under it:
  `A small selection - there’s a lot more where these came from.`
- `Product Bundle Posts` description:
  `Making product combos look good, feel clear, and easy to say yes to.`
- `Carousel Posts` should stay full-width
- `Product Bundle Posts` should remain below the carousel area

### Carousel Posts

Current state:

- carousel section uses folder / fascicle cards, not banner-style or newsletter-style cards
- cards should feel like folders with stacked visible papers inside
- folder colors should use light beige variations, not pink/lilac
- do not wrap individual carousel folders in visible white card frames;
  the folder itself should be the visual object
- `Open Carousel` should sit lower and more transparent, not cover the preview too much
- carousel PDFs should open with `#zoom=50` so the browser PDF viewer starts around 50% instead of 100%
- current asset folder:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/carousels`
- preview folder:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/carousel-previews`
- current approved order:
  1. `One Form Is Not Enough`
  2. `It’s Not Just Melatonin`
  3. `Signals We Ignore` -> `17_SRPSKI - 20.03. - Q10 - Mali signali koje ignorišemo.pdf`
  4. `Magnesium Placebo`
  5. `Body Priority List`
  6. `Collagen Price Trap`
  7. `Q10 After 40`
  8. `Collagen in Food`

### Product Bundle Posts

Current state:

- section now uses Instagram-post-inspired product cards on shelf-like rows
- cards should not look like generic flat ecommerce cards
- keep:
  red filled heart icon,
  comment/share icons,
  cleaner Instagram-like frame,
  shelf background behind rows
- current layout:
  2 rows, 4 items per row
- cards were recently slightly reduced in overall size to occupy less space
- last bundle title must stay:
  `Urovit Tea Bundle`
- current preview folder:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/bundle-previews`
- current source PDFs:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/bundles`

### Client logos

- do not place client logos inside individual project sections
- instead, show them as a premium moving marquee in these places:
  - below `My Education` and above the yellow progress section
  - below `My Experience` and above `Let's take a look / What I Do`
  - below `What I Do` and before `Selected Work / My Projects`
  - below `My Projects` and above `Contact me`
- current marquee uses original logo files from:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/logoi`
- current marquee includes:
  - `moseablelogo.jpeg`
  - `Biostile_-_Logo_2.webp`
  - `chariailogo1.png`
  - `paceuplogo.png`
  - `checksafezonelogo.svg`
  - `narrlit-logo-green.png`
- preferred treatment:
  a narrow, elegant horizontal strip with gentle motion
- each strip should have a small centered label just above it:
  `Worked with:`
- the `Worked with` label should stay centered above the strip, never aligned left
- each logo strip should use a shared inner container so the `Worked with` label is centered relative to the full section width, not the start of the logo row
- each logo strip should use one shared full-width parent group with:
  - `display: flex`
  - `flex-direction: column`
  - `align-items: center`
  so the heading sits on top and the logo row sits directly below it, both centered together
- the `Worked with:` label should be an auto-width centered element inside that parent group, not a left-starting full-width text block
- all logo strips should be wide enough that all 6 logos are visible at once on desktop
- logo strips should keep their moving marquee/slide behavior
- `Worked with:` should remain immediately above each moving strip, centered, italic, and underlined
- for the strip above `My Projects`, place it lower inside the section above and keep the space below it tighter than before, while still preserving a clear separation from `Selected Work / My Projects`
- treat `Worked with:` like a centered section title:
  same font family and dark text tone as other section labels,
  slightly italic,
  underlined with a thin line,
  and horizontally centered over the full width of the logo section
- avoid boxed logo cards; logos should feel freer and more integrated into the line
- keep the logos larger than before, but the overall strip slimmer and more discreet
- no visible horizontal line should run through the logos
- `narrlit-logo-green.png` can be slightly larger than the other logos for better balance
- do not redraw, restyle, or replace the actual logo artwork; use original files as-is
- the strip before `My Projects` should sit closer to the section and transition into it with a soft premium gradient, so it feels intentionally separated instead of leaving a large empty gap
- the strip below `What I Do` belongs visually to that section and should sit directly under the last three cards
- the strip below `What I Do` should also live in the same parent section/container as those cards, not as a standalone block outside the section
- `Selected Work / My Projects` should begin below that strip as a clearly separate section with its own breathing room
- the strip below `My Projects` replaced the old template sponsor/responsor strip and should keep the same approved `Worked with:` treatment as the other strips
- logo strips must not create horizontal page scrolling; the page should scroll only vertically
- current final approved `Worked with:` styling:
  centered,
  underlined,
  color `#556d91`,
  `font-size: 16px`
- in some sections this styling is enforced inline in `index.html` because earlier CSS clashes caused inconsistent rendering

### Progress strip

- keep the yellow percent section visually the same, but more compact than before
- reduce its vertical space so it requires less scrolling
- smaller circle size and tighter spacing are preferred over changing the concept

### PaceUp Project

Current role in site:

- still a standalone top-level project card
- should remain design-system focused
- now populated with real Light Mode and Dark Mode app screens
- title uses the same premium main-title treatment as the other approved top-level project cards
- description currently used:
  `Designed and structured the complete mobile app design system in Figma, including design tokens, variables, typography, reusable components, user flows, and visual guidelines.`
- bold helper line currently used:
  `Take a swipe and see how it all comes to life.`
- current layout:
  title and copy on top,
  two equal mockup blocks directly below,
  `Based on Google’s Material Design - Light Mode` and `Custom UI & Design System - Dark Mode` side by side on desktop
- in each PaceUp mode badge, the design-system/context phrase should sit horizontally to the left of the `Light Mode` / `Dark Mode` label, with both parts similarly visible and close in size
- both mockups should keep:
  swipe left/right,
  scroll only for longer screens,
  hidden left arrow on first slide,
  hidden right arrow on last slide,
  counter and pagination,
  `Swipe` and `Scroll` helper prompts
- standard-height screens should fit inside the mockup without scrolling
- only taller screens should scroll
- Light mode assets:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/PaceUplightmode`
- Dark mode assets:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/PaceUpdarkmode`
- dark mode card should remain dark, but slightly softer and less harsh than pure high-contrast black
- current Light mode active set removes:
  `7 - Material Design system-11 - PaceUp.png`
- current Dark mode active set removes:
  `8 - PaceUp.png`
- current Dark mode order must follow this approved visible folder order:
  `01, 02, 03, 4, 5, 6, 7, 9, 10, 011, 0011, 12, 13`
- current Light / Dark counters should display `/13`

### Chari AI Project

Current role in site:

- still a standalone top-level project card
- positioned as an award-winning promo video case
- now populated with the real video:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/videos/ChariAIFinal.mp4`
- current visual phone mockup asset:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/realistic-vector-phone-mockup-2026-02-24-01-11-37-utc/phonemockup.jpg`
- `instareel.avif` is now only a visual reference for icon/detail placement, not the actual on-page frame
- title uses the same premium main-title badge style as the other top-level project cards
- current description:
  `Created a fast paced short-form promo video for the Chari AI platform, highlighting its key features through clear, engaging visual storytelling.`
- bold helper line:
  `1st place winner, so take a look and see it for yourself.`
- final approved presentation:
  show the real `ChariAIFinal.mp4` inside a single front-facing phone mockup built into the page,
  so it feels like an Instagram Reel playing live on-screen
- video should use normal built-in player controls with sound enabled,
  so it can be manually played/paused like a regular video player
- keep a visible centered play button over the video before first play;
  it should disappear while the video is playing and reappear when paused
- keep a reel-like overlay structure on top of the video:
  profile row,
  right-side action icons,
  bottom caption/audio text
- do not show the large source image with both front and back phones on the page
- remove extra helper labels and explanatory chrome around the video block
- keep the presentation visually clean and centered on the page
- keep the Chari card slightly tinted in the site palette instead of pure white,
  and keep the overall text/video layout compact so there is less empty space
- keep the Chari title badge in its original upper-left position;
  only tighten the paragraph layout and phone sizing, without pushing the title lower
- below the main Chari description, use a styled project-info block instead of plain extra text:
  `Concept / Focus / Platform`
  with more visual treatment than the main paragraphs
- final Chari title line break should be:
  `Chari AI - Contest Winning`
  `Product Promo Video`
- the old small `Award-Winning Video` pill/tag above the Chari project was removed
- do not add that pill/tag back; the award/winning context is already handled by the project title and helper copy
- directly below Chari and above the final logo strip, keep a playful self-built-site callout:
  `And here’s the fun part →`
  `Also designed and built the experience you’re in right now!`
  `From idea to final build, this one’s mine too.`
- the self-built-site callout should use `assets/images/SAJTDIZAJN-cutout.png` as the transparent visual, with no rectangular image frame, noticeable shadow/glow, and hover movement
- keep this section more compact than a full project card, so it feels like a sharp final wink before the logo strip

## Contact Section

Current role:

- final CTA section for direct contact
- no message form
- no map
- no old template footer contact cards
- no fake location, phone numbers, or placeholder email addresses

Current headings/text:

- small heading:
  `Contact me`
- main heading:
  `Let’s create something cool together.`
- paragraph:
  `I’m always open to new projects, collaborations, or just a quick chat. If you like what you saw, let’s talk!`
- panel label:
  `My information`
- helper line:
  `Pick your favorite door. Both are open.`

Current contact details:

- Email:
  `milosavljevicmilica2001@gmail.com`
- LinkedIn:
  `https://www.linkedin.com/in/milica-milosavljevic`

Current interaction rules:

- email address is visible and should stay prominent
- email icon/square is clickable and opens `mailto:`
- email card has two separate action buttons:
  - `Copy email`
  - `Send email`
- `Copy email` copies `milosavljevicmilica2001@gmail.com` and briefly changes to `Copied`
- `Send email` opens `mailto:milosavljevicmilica2001@gmail.com`
- LinkedIn card is entirely clickable and opens the LinkedIn profile in a new tab
- LinkedIn card includes a centered `Visit profile` button for clear action language
- avoid nested clickable links inside the LinkedIn card; the whole card is the link and `Visit profile` is a styled span/button-like element

Current contact visual direction:

- premium glassy contact panel
- two contact cards inside the panel
- soft white/glass cards over a subtle stationery background
- no overlapping buttons/text
- email text must not be covered by buttons
- on desktop, email should stay on one line whenever possible
- on very small mobile screens, email may wrap only if required to prevent overflow

Current contact background image:

- `assets/images/mock-up-of-many-empty-multicolored-office-stickers-2026-03-17-03-33-19-utc.jpg`
- used as the full-width background of the Contact section
- current treatment:
  - `background-size: 100% auto` on desktop
  - full width, not centered with white side gutters
  - subtle brightness/saturation adjustment
  - light blur
  - soft white overlay for readability
- previous tested image:
  `assets/images/colorful-paperclips-scattered-around-yellow-sticky-2026-01-09-13-49-57-utc.jpg`
- the current selected image is the multicolored office stickers image unless the user asks to switch back

## Footer

Current footer content:

- main line:
  `Just me, my laptop, and too many ideas`
- CTA:
  `Let’s work together →`
- CTA opens:
  `mailto:milosavljevicmilica2001@gmail.com`
- location:
  `Based in`
  `Belgrade`
- contact links:
  - `Email`
  - `LinkedIn`
- copyright:
  `© 2026 Milica. Designed & developed with intention.`

Footer design direction:

- should feel like a polished final sign-off, not a template footer
- colored footer section with a clear footer-like presence; current test direction is pastel warm rose/coral/gold with a soft cyan accent
- compact premium sign-off with a soft glassy inner layer, but no separate frames around location/contact groups
- Belgrade/location should be very visible
- location uses `assets/images/locationicon.png` with no frame around the icon
- email and LinkedIn should include small premium inline SVG icons
- CTA should be prominent and warm, using the gold accent
- keep footer concise; do not add fake phone, fake address, or generic template links

## Asset Organization

### Images

- General image folder:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/images`

### Videos

- General video folder:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/videos`

Current known real video assets already in use:

- short-form video editing videos listed above

Important rule:

- keep real videos in `assets/videos` unless there is a strong reason to move them into a narrower project folder
- visible labels on the site should be curated, not literal filenames

### Project Assets

- Project asset base folder:
  `/Users/milica/Desktop/cv sajt/Main Files/html/bootstrap5/color_version-MYPORTFOLIO/assets/projects`

Current project folders:

- `moseable-brand-guidelines`
- `client-content-production`
- `newsletter-design`
- `online-banner-design`
- `social-media-posts`
- `paceup-design-system`
- `chari-ai-promo-video`

Guide rule for future assets:

- PDF presentations and static case-study files should go into the matching `assets/projects/...` folder
- general videos can stay in `assets/videos`
- images for broad site sections can stay in `assets/images`
- if a subsection gets many files, create a subsection folder and document it here

## Working Rules For Future Updates

When editing this site in future turns:

- Always check this `guide.md` first
- Keep content aligned with Milica’s real CV and portfolio work
- Prefer elegant, premium, clean presentation over template-looking blocks
- Avoid placeholder text once a real section is defined
- Avoid long raw file names in visible UI unless explicitly wanted
- Keep asset paths organized by section/project
- Update this file every time a meaningful new change is made
- Preserve approved sections that are already “good”
- If a new design breaks nearby cards or layout, fix that before continuing
- Prefer fewer, stronger design moves over many noisy decorative ones
- For portfolio media:
  the media itself should be the focus, not oversized labels or unnecessary UI chrome
- For title badges:
  keep them elegant, wide enough for text, and visually integrated with the card
- For overlays:
  user prefers subtle, glossy, semi-transparent styling rather than bold solid buttons

## Git / Workflow Notes

- A local git repo is already initialized in `/Users/milica/Desktop/cv sajt`
- We have been making local commits as we go
- GitHub push is still pending because browser/token auth was postponed earlier
- Continue making logical local commits after meaningful chunks of work
- This `guide.md` should be updated whenever a new approved design/content decision becomes part of the site standard

## Maintenance Rule

Every time we do one of these:

- new section redesign
- new real content added
- new images/videos/PDFs linked
- structure changes
- style direction changes

this file should be updated so it stays accurate.
