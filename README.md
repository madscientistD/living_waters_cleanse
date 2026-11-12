# Living Waters Cleanse — website review build

Static review pages for the Living Waters Cleanse website rewrite, prepared by Boise Marketing Mechanic. Each page is a single self-contained HTML file with no build step. Fonts load from Google Fonts.

Page folders match the live site's addresses (for example `/10-day-healing-retreat`), so the final pages can move over without changing any URLs.

| Page | File | Status |
| --- | --- | --- |
| Homepage | `index.html` | Draft for client review |
| 10-day cleanse and healing retreat | `10-day-healing-retreat/index.html` | Draft for client review |
| Colon hydrotherapy | `colon-hydrotherapy/index.html` | Draft for client review |
| What is a colonic? | `colon-hydrotherapy-what-is-it/` | Not started |
| Contact | `contact/` | Not started |
| Webinar: the 4 natural laws of healing | `four-natural-laws-of-healing/` | Not started |

Shared images (logo, logo with tagline, favicon) are in `assets/`.

Every page has `noindex, nofollow` set so search engines skip it while it's a draft. Remove that line before a page goes live.

## Before launch

Homepage:
- [ ] Replace the photo placeholders
- [ ] Paste the GoHighLevel contact form embed into the contact section
- [ ] Point the webinar popup button at the GoHighLevel webinar form
- [ ] Paste the Google Tag Manager snippet (head and body)
- [ ] Add the office email and the social profile links in the footer
- [ ] Add the I-ACT member badge
- [ ] Get a written OK from each client quoted in the testimonials

Colon hydrotherapy page:
- [ ] Fill in the four other first-timer package services
- [ ] Add the 3-session package price and terms
- [ ] Add the monthly membership price and what's included
- [ ] Answer the FAQ items marked for David (prep, what to wear, total visit time, how often)
- [ ] Review the "Your first colonic session" video for health claims before launch
- [ ] Replace the photo placeholders (treatment table, soups and juices or team)
- [ ] Paste the GoHighLevel contact form embed

10-day retreat page:
- [ ] Replace the photo placeholders (treatment room, team, workbook)
- [ ] Add email, hours, social icons and the IACT member badge in the footer
- [ ] Point every "Book My Free Consultation" button at the real booking URL (they currently jump to the How It Works section)
- [ ] Confirm the street address (853 vs. 855 S Curtis Rd) and the guest count per retreat (now 5 per month)
- [ ] Get a written OK from each client quoted in the testimonials
- [ ] Remove past retreat dates each month

## Preview locally

Run `python3 -m http.server` in this folder and visit http://localhost:8000. Links between pages use relative folder paths, so open the pages through the server rather than straight from the file system.
