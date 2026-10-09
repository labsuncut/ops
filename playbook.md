# Playbook

We build websites for local businesses with Claude and GitHub, show the owner a working site, and sell it with a monthly care plan. Anyone who follows this page can run it.

## How a site moves

| Stage | What happens | Who |
| --- | --- | --- |
| Lead | Spot a business with no site or a bad one. Open a [New site](../../issues/new/choose) issue, or just post the name in the Claude project | Anyone |
| Intake | Claude looks up public info (Google listing, Instagram, hours, reviews) and adds it to the issue, marking what's missing | Claude, then a person fills gaps |
| Build | Say "build it" in the Claude project. Claude creates `site-<business-slug>` from `site-template` and fills it in | Claude |
| Review | Claude posts the preview link and phone/desktop screenshots. Open it on your own phone. Ask for fixes or approve | Builder |
| Pitch | Claude drafts the message with the link and price. You send it, or show it in person | Seller |
| Sold | Client pays. Collect logo, photos, domain login. Claude swaps in real content and connects the domain | Seller, then Claude |
| Care | Site stays in our GitHub on the monthly plan. Change requests become issues labelled `client edit` | Claude makes the change, a person merges |
| Not now | Owner said no. Keep the demo; try again in a few months | Seller |

Move the issue's label each time the stage changes.

## Roles

One person can hold all three.

- **Admin:** owns the GitHub and Claude login, the payment account and any domains.
- **Builder:** starts builds in the Claude project, checks previews, asks for fixes.
- **Seller:** finds businesses, pitches, closes, collects the client's content.

## Prices (starting point, adjust as we learn)

| Package | Setup | Monthly | Includes |
| --- | --- | --- | --- |
| One-page | $300 | $30 | Home page with services, hours, map, call button |
| Standard | $750 | $50 | Up to 5 pages, contact form, Google Business link |
| Plus | $1,500 | $80 | Standard plus booking or ordering embed, 2 hours of edits a month |

Hosting on GitHub Pages is free. The client pays for their domain (about $10 to $20 a year).

## Rules

- Claude never contacts a business, sends email or takes payment. A person does.
- Never put fake reviews, awards or claims on a client's site.
- Stock or AI images are placeholders until the client sends real photos.
- Client sites are public repos. Nothing private goes in them: no contracts, passwords or payment details.
- Cold email must follow CAN-SPAM: your real name, a real address, and a way to opt out.

## Turning on hosting for a new site repo

In the repo on GitHub: **Settings**, **Pages**, Source "Deploy from a branch", branch `main`, folder `/ (root)`, **Save**. The preview appears at `https://labsuncut.github.io/<repo-name>/` within a couple of minutes.
