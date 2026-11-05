# AGENTS.md — Rules for Francesca Lee's personal site

Owner: Francesca Lee. Source of truth for content: `Updated FL Resume.pdf` in this folder.
Links: LinkedIn https://www.linkedin.com/in/francesca-lee09/ · GitHub https://github.com/franleee

## Never publish
- Phone number (including the one on the CV), home or street address, and personal email. City-level location (New York, NY) is fine.
- Grades, salary, visa status, date of birth.
- Anything in `private/`: add `private/` to `.gitignore` first, before any other git step.
- Any other email address, unless Francesca explicitly approves it for the page. LinkedIn and GitHub are the default contact paths.
- Anything not in the CV or provided by Francesca. Never invent, round up or embellish metrics, titles, dates, employers or skills.
- Confidential or non-public employer information beyond what the CV already states.
- Tracking scripts, analytics, visitor-data forms or third-party embeds, without approval.
- Never push to GitHub, deploy, or otherwise make the site public without an explicit go-ahead from Francesca.

## Ask first
- Before any `git push`, any change on GitHub, deployment, or publishing the site anywhere.
- Before adding any contact detail (email, phone, other social account) not listed above.
- Before adding content that is not in the CV (new projects, testimonials, photos, bio claims, taglines).
- Before changing the wording of achievements or numbers. Typo and grammar fixes are fine, but report them.
- Before adding external dependencies (fonts, CDNs, libraries). Default is a single self-contained file.
- Before deleting or overwriting files other than ones I created.
- Before a major redesign after Francesca has reviewed a version.

## Content rules
- Keep CV section order: Education → Experience → Additional Information.
- Every fact on the page must trace back to the CV. Keep figures exactly as written.
- Keep the CV's British spelling for CV content ("optimising", "organisational").
- Any supporting copy I write (headline, section labels) must be factual and restate the CV only.

## Style
- Tone: professional and modern. Formal, concise, confident. No casual greetings, slang, jokes or chatty phrasing.
- Colors: Columbia Business School palette — navy and Columbia blue on white/pale backgrounds.
- London flair: a restrained accent in Underground-roundel red and a transit-line motif (stations/line along the experience timeline). Subtle, never kitsch; no clip-art landmarks.
- Navigation: one sticky top bar with a few anchor links; no nested menus. Tiles and native expandable cards (`<details>`) to make sections easy to scan.
- Accessible: semantic HTML, sufficient contrast, keyboard-focusable controls, responsive on mobile, respects reduced-motion.
- Self-contained: plain HTML and CSS only (no JavaScript), system fonts, no build step. Clean and minimal.
- Portfolio: if projects are added, present them as a gallery page that links to each project. Only add projects Francesca provides.

## Reporting
- When finishing a task, say what changed and what was skipped. List every file created or changed, and flag anything omitted or altered from the CV.
