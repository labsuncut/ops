# Working in ops

This repo tracks every website we build for local businesses. Read [playbook.md](playbook.md) first; it is the source of truth for the process and prices.

## When someone gives you a business name

1. Look up public info: Google Business listing, website, Instagram, Facebook, Yelp. Collect name, address, phone, hours, what they sell, brand colours, and up to three real review quotes with the reviewer's first name.
2. Open or update an issue using the New site form fields, with a "Missing" list of what you couldn't find. Label it `stage: intake`.
3. Link every source you used in the issue.

## When asked to build

1. The site repo is `site-<business-slug>` (lowercase, hyphens, include the town if the name is common).
2. Follow `CLAUDE.md` in `labsuncut/site-template` for the build itself.
3. Post the preview link and screenshots on the issue, tick the checklist box, and change the label to `stage: review`.

## Always

- Update the issue's stage label when a stage changes.
- Draft pitches from `templates/pitch-message.md`; never send them.
- Never invent facts about a business.
