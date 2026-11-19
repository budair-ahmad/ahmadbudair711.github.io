# Platform business plan (edit freely)

## What you edit
- `assets/config.js`: form endpoint, payment links, analytics code. Nothing else is needed to switch the shop and newsletter on.
- `assets/content2.js`: products (LIB), reports (REPORTS), courses (COURSES), service packages (PKG), tools list.
- `assets/content.js`: Insights articles (INS). Add an article by adding one row.

## Switch on a product
1. Create the file (Excel/Word/PDF) and a checkout link at your payment provider.
2. Put the link in `CFG.pay`, for example `pay:{proposal:"https://..."}`.
3. The product button changes from "Notify me" to "Buy" automatically.

## Switch on the newsletter
Create a form or list at a provider (for example Formspree, MailerLite, Buttondown), paste its address into `CFG.formEndpoint`.

## Added later
- Proposal generator: Tools page, id #proposal. Exports a Word-compatible .doc or prints to PDF, English or Arabic.
- Glossary: glossary.html (27 terms, EN/AR). Add a term by adding one article block, or ask for it to be regenerated.
- Insights have static pages in /insights. A new article needs its page generated.
- Free downloads live in assets/downloads and are linked in assets/content2.js (FILES).
