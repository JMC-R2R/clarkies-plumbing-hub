# Clarkies Plumbing: suburb emergency plumbing page (layout "ck-location")

Source pages (built by the delivery team, live 11/11/2026, Elementor on Hello theme):
- https://clarkiesplumbing.com.au/service-area/emergency-plumber-williamtown/
- https://clarkiesplumbing.com.au/service-area/emergency-plumber-medowie/

Both pages use the same template. Only the slots below change between them. Everything else is identical, word for word.

Files: `skeleton.html` (fill the `{{...}}` slots), `page_css.css`, `page_header.html`, `page_footer.html`, `sample.html` (Cameron Park example).

## Rules for every page
- Australian English, no em or en dashes, no Oxford comma, plain and practical tone, "we" voice (the business speaks), no hype.
- Exactly one `<h1>`. Keep every class name and the section order exactly as in the skeleton. No inline `style` attributes.
- SUBURB = the page suburb (Cameron Park, Wallsend or Stockton). Name it in the H1, the hero lead, the local H3, the services H3 and paragraph, the "What To Do" sentence and at least one FAQ.
- Headings show in Title Case on the site (CSS capitalises every word), so write them in Title Case.
- Only use facts listed under "Facts the site states". Do not add years, review counts, response times, prices, suburb landmarks the client has not mentioned, or guarantees.
- Reword everything for each suburb. The two live pages share no sentences in the variable slots, so do not copy Williamtown or Medowie wording or the sample's wording.

## Section by section

| # | Section | Slot or fixed | Guidance (measured on the live pages) |
|---|---|---|---|
| 1 | Hero (`pg-hero ck-hero`) | H1, lead, 1 photo | H1: 6 to 8 words, "emergency plumbing" plus SUBURB, e.g. "Trusted Emergency Plumbing Services in Medowie", "Emergency Plumbing Repairs Available Across Williamtown". Lead: one sentence, 20 to 21 words live (18 to 24 ok), names SUBURB and the urgent faults. Buttons fixed: "Get a Free Quote" (contact page) and "Call 0411 289 923". Photo: real Clarkies job photo, landscape, shown 400px tall. |
| 2 | Trust boxes (`ck-trust`) | Fixed | Six boxes, copy verbatim. |
| 3 | Local intro (`ck-intro`) | Photo, H3, 2 paragraphs | Photo on the left (a second, different job photo). H3: 7 to 8 words, who we help in SUBURB ("Dependable Local Plumbers for Williamtown Property Owners"). P1: 33 to 37 words live (up to 50 ok): the properties we help in SUBURB and the faults we fix. P2: 47 to 49 words live (45 to 55): how we work (assess, explain, prevent further damage) and must include the phrases "emergency plumbing repair" or "emergency plumber" plus "same-day plumbing services". Button fixed: "Schedule a Free Consultation". |
| 4 | Services (`ck-svc`) | H3, 1 paragraph, 21 card lines | Eyebrow "Our Plumbing Services" fixed. H3: 7 to 8 words with SUBURB. Paragraph: one sentence, 18 to 19 words. Then 21 service cards: title and "Learn more" link are fixed (real service URLs), only the one-line description changes. Each card line starts with "We" and is exactly 10 words (every card on both live pages is exactly 10 words). Write a fresh line for every card on every page. |
| 5 | What To Do Before Your Plumber Arrives (`ck-prep`) | Fixed except SUBURB | Copy verbatim. Only `{{SUBURB}}` changes (see "Issues on the live pages"). |
| 6 | Testimonials (`ck-reviews`) | Fixed | Live site shows a Trustindex Google review slider. The mockup shows three of those reviews verbatim. Never edit or invent reviews. |
| 7 | FAQ (`ck-faq`) | 5 questions | Exactly 5 `<details><summary>Question?</summary><p>Answer</p></details>`. Question 6 to 10 words. Answer 20 to 27 words, practical, first word often "Yes." for yes/no questions. Mix: one "do you cover SUBURB", one safety or what-to-do question, one fault question (blocked drain, leaking hot water, overflowing toilet), one commercial or timing question, one cost or same-day question. On cost, never give a price: say it depends on the timing, fault, access and materials (Williamtown wording). On same-day, say it "may be available depending on the work required and our schedule" (Medowie wording). |
| 8 | Contact (`ck-contact`) | Fixed | Copy verbatim, including licence numbers, ABN, buttons and ute photo. |

Total words on the finished page (body only): about 880 to 960, of which about 520 to 600 are slot copy.

## Fixed copy (do not change)
Trust boxes, every card title and link, the What To Do block, the three reviews, "Read More Reviews", the FAQ eyebrow and H2, the whole Contact block, the header and footer.

## Facts the site states (only these may be reused)
On both source pages (Williamtown and Medowie URLs above) unless noted:
- Phone: "0411 289 923" (buttons "Call 0411 289 923", contact list), header button "+61 411 289 923", tel link `tel:+61411289923`.
- Email: "clarkiesplumbing@gmail.com" (header, contact block, footer).
- "NSW Licence 153563C" and "Licence: 457869C" (contact block).
- "ABN: 55 680 327 502" (contact block).
- "10+ Years Plumbing Services", "24/7 Emergency Plumbing Newcastle", "Fully Licensed & Experienced", "Upfront Pricing – No Hidden Costs" (live uses an en dash, the mockup uses a comma), "Quality Workmanship That Lasts", "Newcastle Plumbing Experts" (trust boxes).
- "24 hours / 7 days" and "Plumbing service to Newcastle, NSW Australia and surrounds." (contact block).
- "24/7 Plumbing Service" and "Stockton - Newcastle - NSW" (header top bar).
- Footer: "Clarkies Plumbing is a family owned, local business, based in Stockton, NSW. We provide 24 hour 7 days a week plumbing service to Newcastle and surrounds." and "With a commitment to excellence and customer satisfaction, we pride ourselves in skilfully addressing your plumbing needs."
- Address: "38 Dunbar Street, Stockton, NSW 2295" (footer).
- Footer "Area We Serve": Mayfield, Merewether, Hamilton, Kotara, New Lambton, Charlestown, Newcastle, Medowie, Waratah, Fern Bay, Stockton. Cameron Park and Wallsend are not on this list.
- Medowie page: "We provide 24-hour emergency plumbing support across Medowie". Williamtown FAQ: after-hours cost "depends on the timing, fault, access, materials and work required".
- Contact block: "transparent pricing, rapid arrival times, and quality Aussie workmanship".
- Google reviews (Trustindex widget) mention emergency call outs, a short-notice emergency blockage, fair pricing and a tidy finish. Do not quote review counts or star averages; none are shown on the page.

Stockton page: Stockton is the business's home base (footer and address). You may say the business is based in Stockton. Do not claim faster arrival times because of it.

## Internal links
- Card links (fixed, in the skeleton) go to the 21 service pages.
- Buttons: `https://clarkiesplumbing.com.au/contact-us/` and `tel:+61411289923`.
- Do not add other in-text links. The live pages have none.
- New page URL pattern: `/service-area/emergency-plumber-<suburb>/` (e.g. `/service-area/emergency-plumber-cameron-park/`).
- SEO title pattern (for the page settings, not the body): "Emergency Plumbing in SUBURB | Clarkies Plumbing" or "Local Emergency Plumbers in SUBURB | Clarkies Plumbing". Meta description, about 150 characters: "Need an emergency plumber in SUBURB? We repair blocked drains, leaking pipes, toilets and hot water faults for homes and businesses. Contact us today."

## Images
Two photos per page (hero and intro), both real Clarkies job photos, not stock. Use a different pair on each page. The live pages use `wp-content/uploads/2026/09/IMG_0167-1-scaled.jpg`, `IMG_0821-2-scaled.jpg`, `IMG_7873-scaled.jpg` and `2026/06/gas-fitting.jpg`. The sample reuses two of these only for the QA preview. Alt text describes what is in the photo.

## Issues on the live pages (do not copy)
- Both live pages say "while our **Mayfield** plumber is booking it to your location" in the What To Do block. That is a template leftover. The skeleton uses SUBURB.
- Live spells "minimize". The skeleton uses "minimise".
- The live Medowie and Williamtown headings put the local intro heading in an `<h3>` and "Our Plumbing Services" in an `<h2>`. The skeleton mirrors that so the page builds the same in Elementor.

## Avoid
Em and en dashes, Oxford commas, US spelling, invented stats or response times, prices, "best" or "#1" claims, suburb trivia, repeating the same card lines across pages, extra sections, extra links.
