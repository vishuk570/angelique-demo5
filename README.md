# Angelique — Option 04: Beyond Boundaries

A separate, fully redesigned client-review prototype. Previous options are unchanged.

## What is new

- Desktop identity rail and separate original-logo panel, replacing the horizontal navigation bar.
- Blue Explore control opens a full-screen numbered menu with contextual imagery and direct sector links. Hover/focus updates the menu photograph. Mobile uses a full-screen list without the rail.
- New 1080p bridge-construction video at sunset, 15 seconds, with animated headline, rotating Watch film control, pause and playback progress.
- Horizontal sector gallery, staggered project photography and a selectable EPC journey.
- Rotatable globe using geographic land points, three region selectors and seven source-listed country examples. Drag to rotate; select countries to focus the view.
- Scroll reveals, number counters, image zooms, technical scan animation, global motion pause and reduced-motion support.
- 22 page templates, local search, scripted assistant and demonstration enquiry form.

## Preview and deploy to Vercel

1. Extract the ZIP. The project folder is angelique-option-04.
2. Open public/index.html for a local preview, or upload this project folder's CONTENTS to a new GitHub repository.
3. Import the repository into Vercel as a new project.
4. Framework: Other. Build Command: empty. Output Directory: public. Root Directory: the directory containing vercel.json.
5. Deploy. Review desktop and mobile layouts and interactions before sending the URL to your client.
6. Share /design-review.html for the design rationale and Option 03 / Option 04 comparison. That page has a Print / save as PDF button.

The included vercel.json sets the static output directory. With Node.js installed you can alternatively run `npx vercel@latest --prod` from the project folder and create a new project. Do not link it to another option. Check intended audience access in your deployment's protection settings.

## Files

- public/index.html — new header, navigation overlay, footer and dialogs.
- public/app.js — homepage, inner templates, globe rendering, controls and local interactions.
- public/styles.css — fresh standalone Option 04 design system and responsive layouts.
- public/globe-data.js — land points derived from Natural Earth geography via world-atlas.
- public/media/ — local video, poster, high-resolution images, original AIL logo, map source and credit files.
- public/design-review.html — printable client review document.

No build, runtime dependencies, remote CDN or API credentials are needed.

## Sources and content accuracy

Original AIL website: https://www.angelique-india.com/home . Logo colours are unchanged: AIL deep blue #163C63 and bright blue #0078C7.

New footage: Mixkit item 2088, rail bridge construction, with verified commercial Free License. New bridge and team images: Pexels. Sector photos: Pexels. See media/new-credits.json and media/sector-credits.json for exact source pages, authors and licence notes. These assets illustrate EPC sectors and are not verified AIL projects, sites or employees.

The globe shows selected source-listed examples from Kenya, Mali, Mozambique, India, Bangladesh, Laos and Cambodia. Pins are approximate country centres, not exact office or project coordinates. This is not a complete footprint. Project scope, dates, status and outcomes require approval.

Counters show 1996 as the establishment year, 5 sectors and 3 EPC disciplines. No unsupported scale statistics are used.

## Prototype boundaries

This is a static HTML/CSS/JavaScript prototype, not a Next.js/CMS production build. Noindex and hash routes are intentional for client review. Forms transmit/store nothing. The assistant is scripted. Language controls are previews; English is implemented. Approved content, production SEO, analytics, CMS, secure forms, translation and an AI-backed chatbot remain production tasks after design approval.

## Verification

JavaScript syntax, generated page content, local assets and routes, original logo bytes, globe projection, region/country selection, EPC stage controls, counter progression, media metadata and archive integrity were checked. Source media was visually inspected. Browser-based layout/interaction QA was unavailable in the build environment. Review responsive layouts, navigation focus, video playback, carousel scrolling, globe drag/rotation and forms after deployment.
