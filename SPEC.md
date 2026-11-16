**# Brand Studio decisions — UNBOUND**

This is the working record of agreed brand decisions, implemented features, and research evidence. Persona descriptions and expected audience responses are _\*\*_**\*\*hypotheses\*\***\*\*, not validated customer findings. \`LEARNING.md\` records student explanations, AI assistance, and reflections.



**## Current stage**

\- _\*\*_**\*\*Completed feature:\*\***\*\* \`BRAND-001\` — UNBOUND branded storefront, live style guide, and modernist/postmodernist hero comparison.



\- _\*\*_**\*\*Repository:\*\***\*\* https\://github.com/njd54/is117-brand-studio



\- _\*\*_**\*\*BRAND-001 delivery:\*\***\*\* \`feature/brand-001-unbound\` was pushed and pull request _\*\*_**\*\*#2\*\***\*\* was merged into \`main\` (confirmed by the GitHub screenshot shared November 4, 2026).



\- _\*\*_**\*\*Verification:\*\***\*\* \`npm run check\` passed, including _\*\*_**\*\*10 Playwright tests\*\***\*\*. Student manually reported: “Everything looks correct on mobile and I was able to navigate using only my keyboard.”



\- _\*\*_**\*\*Current assignment:\*\***\*\* IS117-007 — T-shirt Research, due _\*\*_**\*\*November 10, 2026, 8:30 a.m. Eastern\*\***\*\*.



\- _\*\*_**\*\*Next action:\*\***\*\* Add dated competitor screenshots to the repository, confirm exact product URLs, discuss one observation with a classmate November 5, and record feedback, response, and a revision or justified decision to keep the design.



**## Product boundary**

UNBOUND is a concept for the same plain white T-shirt throughout its two design previews. The site includes a size selector and temporary demo bag; there are no real orders, payments, accounts, or persistent cart data. The _\*\*_**\*\*$28\*\***\*\* displayed price is fictional demo data, not a market-validated price. Do not claim unverified materials, fit, sustainability, shipping, customer reviews, sales, or product scarcity.



**## Audience hypotheses**

\| Question                     | Primary audience hypothesis                                                 | Secondary audience hypothesis                                     |



\| ---------------------------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------- |



\| Person and situation         | College student aged 18–24 assembling everyday campus outfits               | Urban creative aged 22–30 dressing for work and social activities |



\| Goal                         | Feel confident and express individuality with accessible streetwear styling | Express creativity and adapt basics to several settings           |



\| Concern                      | Whether a simple white T-shirt can fit their personal streetwear aesthetic  | Whether the understated shirt can work with different outfits     |



\| Site should help them decide | Whether UNBOUND suits their style and which size to choose                  | Whether the shirt complements their existing wardrobe             |



\| Evidence status              | Hypothesis; no customer interviews or purchase data                         | Hypothesis; no customer interviews or purchase data               |



**## Early brand brief**

\| Decision         | Agreement                                                                                                           |



\| ---------------- | ------------------------------------------------------------------------------------------------------------------- |



\| Brand name       | _\*\*_**\*\*UNBOUND\*\***\*\* (creative concept; trademark availability not checked)                                                  |



\| Promise          | A versatile everyday essential that lets your personal style stand out.                                             |



\| Archetype        | _\*\*_**\*\*Rebel\*\***\*\* — independent and expressive                                                                              |



\| Voice            | Bold, direct, authentic                                                                                             |



\| Tagline          | _\*\*_**\*\*WEAR YOUR OWN WAY.\*\***\*\*                                                                                              |



\| Predicted effect | College streetwear enthusiasts may associate UNBOUND with confidence and individuality; not validated by customers. |



**## Visual decision**

Both coded hero previews use the _\*\*_**\*\*same white T-shirt\*\***\*\*, headline, supporting copy, and action. Only the visual presentation changes.



\| Element               | Decision and rationale                                                                                                                                       |



\| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |



\| Shared content        | \`WEAR YOUR OWN WAY.\` / \`One essential. Endless ways to express yourself.\` / \`SHOP THE TEE\`; both use \`assets/white-shirt.svg\`.                               |



\| Modernist preview     | Restrained typography, ordered composition, and clear hierarchy. Intended benefit: quick product evaluation. Risk: less distinctive for the target audience. |



\| Postmodernist preview | Oversized typography, layering, asymmetry, strong contrast, and red accents. Intended benefit: energy and individuality. Risk: visual overload.              |



\| Selected approach     | _\*\*_**\*\*Postmodernist\*\***\*\*, because the student views youth as a period of self-expression and discovering identity. Preserve clear navigation and shopping controls. |



\| Logo                  | \`public/assets/unbound-logo.svg\`, UNBOUND wordmark with red diagonal slash.                                                                                  |



\| Palette               | Ink \`#111111\`; off-white \`#F4F1E9\`; signal red \`#E6392E\`; concrete gray \`#8D9094\`; darker interactive red \`#C92C23\` where needed for contrast.               |



\| Implementation        | \`public/styles.css\` supplies shared tokens; \`public/styleguide.js\` reads them; \`public/studio.html\` shows the two treatments and research annotations.       |



**### Design research references and application**

These are design precedents, _\*\*_**\*\*not endorsements of UNBOUND\*\***\*\*. The connections below are the student's design interpretations.



_\*\*_**\*\*Modernist reference 1 — Herbert Bayer, Bauhaus graphic design.\*\***\*\* Museum of Modern Art: https\://www\.moma.org/collection/works/5101



\- Principle: functional typography and purposeful visual hierarchy.



\- UNBOUND application: restrained type and clearly separated product information in the modernist preview.



\- Intended effect: easy scanning; risk: conventional appearance.



_\*\*_**\*\*Modernist reference 2 — Swiss International Typographic Style (1950–1970).\*\***\*\* Swiss National Library: https\://www\.nb.admin.ch/en/the-international-style-1950-1970



\- Principle: structured grids, legibility, and controlled organization.



\- UNBOUND application: balanced spacing, consistent hierarchy, and straightforward action link.



\- Intended effect: clarity; risk: limited expression of the Rebel archetype.



_\*\*_**\*\*Postmodernist reference 1 — Paula Scher,&#x20;\*\*\_\_The Diva is Dismissed\_\_**\*\*&#x20;(1994).*\*\**\*\* Museum of Modern Art: https\://www\.moma.org/collection/works/8837



\- Principle: expressive type, contrasting scale, and unconventional composition.



\- UNBOUND application: oversized headline and assertive hierarchy.



\- Intended effect: personality and confidence; risk: crowding product information.



_\*\*_**\*\*Postmodernist reference 2 — April Greiman,&#x20;\*\*\_\_Your Turn, My Turn\_\_**\*\*&#x20;(1983).*\*\**\*\* Cooper Hewitt, Smithsonian Design Museum: https\://www\.cooperhewitt.org/2017/08/30/26363/



\- Principle: experimental, layered composition.



\- UNBOUND application: asymmetry and unexpected visual emphasis.



\- Intended effect: encourage individual style; risk: legibility if overused.



_\*\*_**\*\*Conclusion:\*\***\*\* Use postmodernist expression to communicate brand personality, but modernist clarity for product facts, navigation, size controls, and bag feedback.



**## Ethical persuasion in UNBOUND**

\| Principle                      | Implemented feature                                                                                                                               | Benefit and boundary                                                                      |



\| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |



\| _\*\*_**\*\*Reciprocity\*\***\*\*                | \`ONE TEE. THREE WAYS.\` offers free ideas: Campus casual, Layered streetwear, Clean contrast. Copy states \`FREE STYLE NOTES / NO PURCHASE NEEDED\`. | Visitors get useful styling ideas without needing to buy. No unsupported product claims.  |



\| _\*\*_**\*\*Commitment and consistency\*\***\*\* | \`WHAT'S YOUR STYLE?\` offers optional Minimal, Layered, Bold, and Mixed choices.                                                                   | Visitors can express a preference without an account, purchase, or persistent commitment. |



The ordinary product-size selector is _\*\*_**\*\*not\*\***\*\* counted as the separate commitment-and-consistency feature.



**## BRAND-001 — completion and evidence**

\- [x] Choose audience hypotheses, Rebel brand character, and postmodernist direction.



\- [x] Implement two coded hero previews with identical product and copy.



\- [x] Document modernist and postmodernist sources and tradeoffs.



\- [x] Create original UNBOUND SVG wordmark and coherent storefront/style guide.



\- [x] Preserve size selection and demo bag.



\- [x] Implement two ethical persuasion features.



\- [x] Pass automated format, lint, unit, browser, and accessibility checks.



\- [x] Manually check mobile layout and keyboard-only navigation.



\- [x] Push feature branch and merge pull request #2 into \`main\`.



_\*\*_**\*\*Automated evidence:\*\***\*\* On November 4, 2026, the final \`npm run check\` screenshot showed _\*\*_**\*\*10 passed\*\***\*\*. This supports only the tested behaviors; it does not prove customer preference or complete accessibility.



_\*\*_**\*\*Manual evidence:\*\***\*\* Student statement: “Everything looks correct on mobile and I was able to navigate using only my keyboard.”



_\*\*_**\*\*Accessibility corrections:\*\***\*\* Earlier Studio tests identified insufficient contrast on the ribbon label, UNBOUND stamp, and postmodernist link. Text/background colors were adjusted. A duplicate CSS selector and hex-color lint issue were corrected; the final check passed.



**\*\*---\*\***



**# IS117-007 — T-shirt competitive research**

_\*\*_**\*\*Research date:\*\***\*\* November 4, 2026  



_\*\*_**\*\*Assignment due:\*\***\*\* November 10, 2026, 8:30 a.m. Eastern  



_\*\*_**\*\*Research question:\*\***\*\* How do three clothing websites communicate the value of a T-shirt, support product selection, and encourage purchase, and what should UNBOUND adopt or avoid?



_\*\*_**\*\*Method:\*\***\*\* Inspect each product page and add _\*\*_**\*\*one size-medium shirt\*\***\*\* to the bag/cart where possible; document visible controls, messaging, and cart feedback without checking out, entering personal details, or purchasing. Compare the sites' _\*\*_**\*\*design and buying experience\*\*\*\*, not equivalent products: the selected garments differ in category, fit, design, and price. Screenshots were supplied during the research conversation; copies still need to be committed to the repository for durable evidence. Prices and promotions are&#x20;**_\*\*_**\*\***&#x70;oint-in-time observations\*\*\*\*, not current-price guarantees.



**## Competitor 1 — UNIQLO**

_\*\*_**\*\*Source:\*\***\*\* https\://www\.uniqlo.com/us/en/products/E424873-000/00?colorDisplayCode=00&sizeDisplayCode=003  



_\*\*_**\*\*Observed product:\*\***\*\* Women's Crew Neck T-Shirt, white. The first screenshot had _\*\*_**\*\*S\*\***\*\* selected; the subsequent cart observation recorded one item, but the cart modal did not visibly confirm its size.



_\*\*_**\*\*Observed on product page:\*\***\*\* $19.90 price; sizes XXS–XXL; white and other color swatches; size guide; _\*\*_**\*\*4.7 rating with 999+ reviews\*\***\*\*; quantity controls; Add to Cart; store-availability and shipping information. Large product photography and black-on-white typography organize the page.



_\*\*_**\*\*Observed after adding to cart:\*\***\*\* “Added to cart”; _\*\*_**\*\*1 item\*\*\*\*,&#x20;**_\*\*_**\*\***$19.90 subtotal before tax\***\*\*\*; message stating&#x20;**_\*\*_**\*\***$79.10\*\*\*\* remaining to qualify for free standard shipping; “Frequently Bought Together” product recommendations; View Cart and Continue Shopping actions. No completed checkout was observed.



_\*\*_**\*\*Interpretation:\*\***\*\* Predominantly _\*\*_**\*\*modernist\*\***\*\* shopping interface emphasizing practical information and clarity. _\*\*_**\*\*Everyperson\*\***\*\* is a plausible archetype hypothesis because of its accessible everyday positioning, not an official brand classification. The displayed reviews provide _\*\*_**\*\*social proof\*\***\*\*. Recommendations and the shipping threshold may encourage additional purchases; neither proves actual customer behavior.



_\*\*_**\*\*What UNBOUND could use:\*\***\*\* Visible price, size guidance, and unambiguous cart feedback. Avoid adding unnecessary pressure to spend more simply to meet a shipping threshold.



_\*\*_**\*\*Evidence to commit:\*\***\*\* \`research/screenshots/uniqlo-product-2026-11-04.png\` and \`research/screenshots/uniqlo-cart-2026-11-04.png\` (proposed filenames; add actual screenshots and update paths if different).



**## Competitor 2 — Represent**

_\*\*_**\*\*Source:\*\***\*\* Represent website, https\://representclo.com/ . _\*\*_**\*\*Exact MH Paint product URL still needs to be copied from the browser\*\***\*\*; do not substitute the previously suggested Owners Club product link.



_\*\*_**\*\*Observed product:\*\***\*\* _\*\*_**\*\*MH Paint Short Sleeve T-Shirt\*\*\*\*, Antique Slate,&#x20;**_\*\*_**\*\***$145\***\*\*\*, distressed/paint-effect styling. Size choices XS–XXL;&#x20;**_\*\*_**\*\***&#x53;\***\*\*\* appeared unavailable. The cart confirmed&#x20;**_\*\*_**\*\***&#x4D;\***\*\*\*, quantity 1. Page showed size chart, fit help, wishlist, estimated delivery, free shipping over&#x20;**_\*\*_**\*\***$175\*\*\*\*, Prestige Points, and installment-payment information.



_\*\*_**\*\*Observed cart:\*\***\*\* Slide-out cart showed _\*\*_**\*\*$145 subtotal\*\*\*\*,&#x20;**_\*\*_**\*\***$10 estimated delivery\***\*\*\*, and&#x20;**_\*\*_**\*\***$155 displayed total\*\*\*\*. It offered “Others Also Bought” recommendations and a Secure Checkout button. Final tax, payment, and order completion were not tested.



_\*\*_**\*\*Interpretation:\*\***\*\* The _\*\*_**\*\*interface\*\***\*\* uses restrained, modernist-like black-and-white organization, while the _\*\*_**\*\*garment styling\*\***\*\* is expressive and unconventional. _\*\*_**\*\*Rebel with possible Ruler elements\*\***\*\* is an archetype hypothesis, based on visual distinctiveness and premium positioning. “Others Also Bought” suggests _\*\*_**\*\*social proof\*\***\*\*, but the screenshot does not verify the recommendation data. Rewards and installments are sales mechanisms, not automatically distinct Cialdini principles.



_\*\*_**\*\*What UNBOUND could use:\*\***\*\* Expressive brand identity paired with straightforward size selection and clear cart totals. Avoid unsupported exclusivity or premium-quality claims.



_\*\*_**\*\*Comparison limitation:\*\***\*\* This distressed $145 shirt is _\*\*_**\*\*not\*\***\*\* equivalent to UNIQLO's basic white crewneck or UNBOUND's fictional $28 white T-shirt.



_\*\*_**\*\*Evidence to commit:\*\***\*\* \`research/screenshots/represent-product-2026-11-04.png\` and \`research/screenshots/represent-cart-2026-11-04.png\` (proposed paths).



**## Competitor 3 — H&M**

_\*\*_**\*\*Source:\*\***\*\* https\://www2.hm.com/en_us/ . _\*\*_**\*\*Exact Loose-Fit Interlock product URL still needs to be copied from the browser\*\***\*\*; the earlier suggested Regular Fit product link is not evidence for this screenshot.



_\*\*_**\*\*Observed product:\*\***\*\* _\*\*_**\*\*Loose-Fit Interlock T-Shirt\*\*\*\*, cream, men's,&#x20;**_\*\*_**\*\***$15.00 sale price\***\*\*\* from&#x20;**_\*\*_**\*\***$19.99\***\*\*\* (25% off). Color swatches, sizes XS–XXL, size guide, shipping selection, and free pickup option were visible. The page showed a red&#x20;**_\*\*_**\*\***“FLASH SALE: 25% OFF UNTIL MIDNIGHT”*\*\**\*\* banner and a countdown timer. The screenshot indicated pickup availability at Westfield Garden State Plaza; availability may change.



_\*\*_**\*\*Observed add-to-bag confirmation:\*\***\*\* Product, cream color, _\*\*_**\*\*size M\*\*\*\*,&#x20;**_\*\*_**\*\***&#x71;uantity 1\***\*\*\*, and&#x20;**_\*\*_**\*\***$15.00\*\*\*\* price. Shipping charges, taxes, final total, and checkout were not shown.



_\*\*_**\*\*Interpretation:\*\***\*\* A structured product interface with high-contrast promotional styling. _\*\*_**\*\*Everyperson\*\***\*\* is a plausible accessible-fashion archetype hypothesis. The deadline and countdown are evidence of _\*\*_**\*\*time-based scarcity messaging\*\*\*\*; the screenshot does&#x20;**_\*\*_**\*\***&#x6E;ot\*\*\*\* independently verify the offer's enforcement or prove it changed purchasing behavior.



_\*\*_**\*\*What UNBOUND could use:\*\***\*\* Clear size/availability feedback and convenient shopping choices, without making countdown urgency the main brand message.



_\*\*_**\*\*Evidence to commit:\*\***\*\* \`research/screenshots/hm-product-2026-11-04.png\` and \`research/screenshots/hm-bag-2026-11-04.png\` (proposed paths).



**### Competitor screenshot evidence**

Research date: November 4, 2026.



The following screenshots document the product pages and add-to-cart interactions observed during the competitive research. No purchases were completed.



\| Competitor | Product page screenshot                                  | Cart / bag screenshot                                     |



\| ---------- | -------------------------------------------------------- | --------------------------------------------------------- |



\| UNIQLO     | [View product page]\(docs/research/uniqlo-product.png)    | [View cart confirmation]\(docs/research/uniqlo-cart.png)   |



\| Represent  | [View product page]\(docs/research/represent-product.png) | [View shopping cart]\(docs/research/represent-cart.png)    |



\| H&M        | [View product page]\(docs/research/hm-product.png)        | [View add-to-bag confirmation]\(docs/research/hm-cart.png) |



**#### Screenshot observations**

_\*\*_**\*\*UNIQLO:\*\***\*\* The product page shows a $19.90 Crew Neck T-Shirt, clear sizing options, customer ratings, and an Add to Cart button. The cart confirmation displays the subtotal, a free-shipping threshold, and related product recommendations.



_\*\*_**\*\*Represent:\*\***\*\* The product page shows a $145 MH Paint Short Sleeve T-Shirt in Antique Slate. The cart displays one medium shirt, a $145 subtotal, $10 estimated delivery, and a $155 displayed total.



_\*\*_**\*\*H&M:\*\***\*\* The product page shows a cream Loose-Fit Interlock T-Shirt discounted to $15.00 from $19.99. The add-to-bag confirmation shows one medium shirt. The page also displays a time-limited sale and countdown.



**#### Research limitations**

These screenshots document the product selection and initial cart interactions only. Full checkout, payment, and order completion were not tested. The selected shirts differ in style and positioning, so their prices are not directly comparable as identical products.



**## Side-by-side findings**

\| Dimension              | UNIQLO                                      | Represent                                         | H&M                                      |



\| ---------------------- | ------------------------------------------- | ------------------------------------------------- | ---------------------------------------- |



\| Observed garment       | White women's crewneck                      | Distressed Antique Slate tee                      | Cream men's loose-fit tee                |



\| Observed price         | $19.90                                      | $145.00                                           | $15.00 promotional ($19.99 original)     |



\| Positioning hypothesis | Practical everyday basics                   | Premium expressive streetwear                     | Accessible trend-focused fashion         |



\| Archetype hypothesis   | Everyperson                                 | Rebel / Ruler                                     | Everyperson                              |



\| Visual treatment       | Restrained, organized                       | Restrained interface; expressive garment          | Organized interface; urgent sale styling |



\| Persuasion evidence    | Review stars; related products              | “Others Also Bought”; rewards                     | Time-limited sale/countdown              |



\| Bag/cart evidence      | 1 item; $19.90 subtotal; shipping threshold | $145 subtotal; $10 estimated delivery; $155 total | 1 medium shirt; $15 item confirmation    |



\| UNBOUND lesson         | Clear sizing and cart information           | Distinctive identity without confusing controls   | Clear selection; avoid pressure tactics  |



_\*\*_**\*\*Cross-site conclusion:\*\***\*\* All three sites provide product-selection controls, but their value messages differ. UNBOUND can distinguish itself through expressive styling inspiration while retaining understandable controls. The comparison does _\*\*_**\*\*not\*\***\*\* establish what real customers prefer; further feedback is required.



**## Two positioning alternatives**

**### Alternative A — Affordable everyday essentials**

\- _\*\*_**\*\*Person:\*\***\*\* Budget-conscious college commuter.



\- _\*\*_**\*\*Situation:\*\***\*\* Needs an easy-to-style shirt for classes and everyday activities.



\- _\*\*_**\*\*Need:\*\***\*\* Simple choices, clear price, and confidence in sizing.



\- _\*\*_**\*\*Positioning statement (hypothesis):\*\***\*\* “One essential. Clear choices. Everyday versatility.”



\- _\*\*_**\*\*Archetype fit:\*\***\*\* Everyperson.



\- _\*\*_**\*\*Supporting observation:\*\***\*\* UNIQLO and H&M make sizing and pricing prominent.



\- _\*\*_**\*\*Tradeoff:\*\***\*\* Clear and practical, but may not differentiate UNBOUND from mainstream basics brands.



**### Alternative B — Creative college streetwear**

\- _\*\*_**\*\*Person:\*\***\*\* College streetwear enthusiast exploring personal identity.



\- _\*\*_**\*\*Situation:\*\***\*\* Styling a simple white T-shirt for campus, friends, and social activities.



\- _\*\*_**\*\*Need:\*\***\*\* Inspiration to express individuality without requiring an expensive statement garment.



\- _\*\*_**\*\*Positioning statement (hypothesis):\*\***\*\* “One essential. Endless ways to express yourself.”



\- _\*\*_**\*\*Archetype fit:\*\***\*\* Rebel.



\- _\*\*_**\*\*Supporting observation:\*\***\*\* Represent illustrates expressive streetwear positioning; UNIQLO and H&M illustrate the value of practical product controls.



\- _\*\*_**\*\*Tradeoff:\*\***\*\* More distinctive, but expressive visuals must not obscure the shirt, price, or sizing.



**## Two short persona hypotheses**

_\*\*_**\*\*Persona 1 — Jordan, 20, college commuter (Alternative A).\*\***\*\* Jordan wants an affordable white tee that is easy to choose and style before class. Their main concern is making a practical purchase without confusing sizing or surprise costs. They would benefit from clear product facts and straightforward cart feedback. _\*\*_**\*\*Assumption:\*\***\*\* This is a fictional persona, not an interviewed customer.



_\*\*_**\*\*Persona 2 — Alex, 21, creative college student (Alternative B).\*\***\*\* Alex likes streetwear and wants to turn a plain white tee into outfits that feel personal. Their concern is whether a basic item can express individuality. They would benefit from styling ideas and expressive but readable branding. _\*\*_**\*\*Assumption:\*\***\*\* This is a fictional persona, not an interviewed customer.



**## Chosen audience and rationale**

_\*\*_**\*\*Choose Alternative B — Creative college streetwear\*\*\*\*, with&#x20;**_\*\*_**\*\***&#x63;ollege streetwear enthusiasts aged 18–24\***\*\*\* as the primary audience. This fits the already implemented UNBOUND Rebel archetype, postmodernist presentation, tagline&#x20;**_\*\*_**\*\***“WEAR YOUR OWN WAY,”*\*\**\*\* and free styling suggestions. Borrow the functional clarity of mainstream shopping interfaces rather than copying their positioning or using unverified scarcity claims.



_\*\*_**\*\*Why this is still a hypothesis:\*\***\*\* The competitor screenshots show how brands present products; they do not prove that students prefer UNBOUND's concept, that the fictional $28 price is acceptable, or that the styling content increases conversion. The November 5 class discussion is an opportunity to challenge the assumption.



**## Honest persuasion decision**

\- _\*\*_**\*\*Keep:\*\***\*\* Free styling ideas (_\*\*_**\*\*reciprocity\*\*\*\*) and optional style-direction choices (\*\*\*\*commitment and consistency\*\***\*\*).



\- _\*\*_**\*\*Use carefully:\*\***\*\* Clear size guidance, cart confirmation, and accurate price displays.



\- _\*\*_**\*\*Avoid without evidence:\*\***\*\* Fake reviews, unsupported limited-stock claims, invented shipping promises, or countdowns implying deadlines that are not real.



\- _\*\*_**\*\*Disclosure:\*\***\*\* UNBOUND's bag and price are a _\*\*_**\*\*demo\*\***\*\*, not a live retail checkout.



**## November 5 peer-feedback record — pending actual class activity**

_\*\*_**\*\*Research observation to present:\*\***\*\* Represent pairs an expressive garment with a minimal shopping interface; UNBOUND could do the same with postmodernist branding and simple product controls.



_\*\*_**\*\*Question for classmate:\*\***\*\* “Does UNBOUND's expressive visual style help you understand its intended audience, or does it distract from the basic white T-shirt and size selection?”



\- _\*\*_**\*\*Classmate's question or feedback:\*\***\*\* Pending — record actual words or clearly labeled paraphrase after class.



\- _\*\*_**\*\*My response:\*\***\*\* Pending — write the student's actual explanation.



\- _\*\*_**\*\*Decision (revise or keep, with reason):\*\***\*\* Pending.



\- _\*\*_**\*\*Change made and retest, if applicable:\*\***\*\* Pending. If keeping the design, explain why and what was checked.



\- _\*\*_**\*\*GitHub feedback issue URL:\*\***\*\* Pending — create/update an issue in this repository after discussion.



\- _\*\*_**\*\*Team partner:\*\***\*\* Pending — record only after pairing in class.



**## Submission checklist — IS117-007**

\- [x] Examine three relevant clothing websites and capture product/cart or bag screenshots.



\- [x] Record screenshot-based observations, interpretations, and UNBOUND implications.



\- [x] Compare two positioning alternatives and two persona hypotheses.



\- [x] Choose and justify a primary audience, labeling assumptions.



\- [x] Explain brand archetypes, modernism/postmodernism, and ethical persuasion.



\- [ ] Add all six actual screenshots to the repository and update the evidence paths above.



\- [ ] Record exact product-page URLs for the Represent and H&M products shown.



\- [ ] Collect real peer feedback on November 5 and record a response and revision or justified keep decision in a GitHub issue.



\- [ ] Recheck affected work after any changes and record the result.



\- [ ] Commit and push the updated \`SPEC.md\` and evidence to GitHub.



\- [ ] Submit in Canvas: research-record link, repository/site links, feedback issue link, and a brief change/open-question note.



_\*\*_**\*\*Assignment reminder:\*\***\*\* Research submission is due _\*\*_**\*\*November 10, 2026, at 8:30 a.m. Eastern\*\***\*\*. The separate portfolio/career research assignment is not part of this \`SPEC.md\` section.



**---**



**# IS117-007 — Review 2: T-shirt Plan**



**\*\*Plan date:\*\*** November 16, 2026  

**\*\*Due:\*\*** November 17, 2026, 8:30 a.m. Eastern  

**\*\*Status:\*\*** Planning proposal; implementation and new tests not yet verified.  

**\*\*Project:\*\*** UNBOUND — one fictional $28 white T-shirt, aimed at college streetwear enthusiasts ages 18–24.



**## Planning question**



How can UNBOUND let a college streetwear enthusiast explore expressive styling, choose a size, and complete a clearly labeled simulated purchase without sacrificing understandable product information or falsely implying a real transaction?



**## Compare two concise approaches**



\| Dimension | Approach A — Everyday essentials | Approach B — Creative college streetwear (selected) |

\| --- | --- | --- |

\| Audience need | Quick, uncomplicated shopping for a basic tee | Express personal style while confidently choosing a basic tee |

\| Presentation | Minimal layout, restrained typography, direct product facts | Postmodernist hero, Rebel voice, bold red accents, then clear shopping controls |

\| Core interaction | Select size, add to bag, simulated checkout | Browse free style ideas, optionally choose a style direction, select size, add to bag, simulated checkout |

\| Benefit | Lower visual complexity and easy scanning | Better aligns with UNBOUND's existing brand promise and styling concept |

\| Risk | Hard to distinguish from basic-clothing competitors | Visual complexity could obscure price, size, or checkout |

\| Check to perform | Can a reviewer find size, price, and bag action without guidance? | Can a reviewer find the same controls and finish the simulated flow using keyboard only? |



**\*\*Decision:\*\*** Select **\*\*Approach B\*\***, preserving the existing postmodernist design and tagline **\*\*“WEAR YOUR OWN WAY.”\*\*** Borrow Approach A's clear labels, predictable controls, and readable totals. This is a design rationale, not evidence that customers prefer B.



**## Brand and honest persuasion carried forward**



\- **\*\*Brand promise:\*\*** A versatile everyday essential that lets personal style stand out.

\- **\*\*Visual system:\*\*** Ink \`#111111\`, off-white \`#F4F1E9\`, signal red \`#E6392E\`, concrete gray \`#8D9094\`; use the darker red \`#C92C23\` when needed for contrast. Keep expressive typography away from form labels and transaction details.

\- **\*\*Reciprocity:\*\*** Keep **\*\*“ONE TEE. THREE WAYS.”\*\*** and the explicit **\*\*“FREE STYLE NOTES / NO PURCHASE NEEDED”\*\*** message. The tips are useful without a purchase.

\- **\*\*Commitment and consistency:\*\*** Keep optional **\*\*“WHAT'S YOUR STYLE?”\*\*** choices (Minimal, Layered, Bold, Mixed). These are preferences, not a required account or a binding commitment.

\- **\*\*Honesty:\*\*** The $28 price is fictional demo data. State **\*\*“Simulated checkout — no payment or real order”\*\*** before the checkout action and again on confirmation. Do not invent reviews, stock shortages, shipping terms, or limited-time offers.



**## Five user stories and observable acceptance checks**



\| ID | User story | Essential feature | Observable acceptance check (planned) |

\| --- | --- | --- | --- |

\| US-1 | As a college shopper, I want to see the shirt and its price so I can decide whether to explore it. | Product image, product name, visible $28 demo price, demo disclosure | Open the product page at desktop and mobile widths; confirm the same white shirt, $28 price, and demo label are visible without guessing. |

\| US-2 | As a shopper, I want to select a size so I know which variant I am adding. | Accessible size selector and validation | Try adding with no size selected: receive a clear message and no bag entry. Select M, add, and confirm bag shows M. |

\| US-3 | As a style-conscious student, I want free outfit ideas and an optional style choice so I can imagine wearing the shirt my way. | Three free style ideas and optional style-direction buttons | Open all three style ideas without purchasing; choose a style and confirm the selection is visually and programmatically indicated; verify it can be changed. |

\| US-4 | As a shopper, I want a clear bag summary so I can review the selected item and total before proceeding. | Bag item, size, quantity, subtotal, remove/change action | Add one M shirt and confirm quantity 1 and $28 subtotal; increase to 2 and confirm $56; remove item and confirm the bag is empty. |

\| US-5 | As a shopper, I want to finish a simulated checkout so I can understand the ordering flow without paying or submitting a real order. | Demo checkout form, confirmation, SQLite-backed demo order | Select size M and quantity 2 for the fictional $28 shirt; complete the simulated checkout and receive a clearly labeled SIMULATION confirmation with an order ID. Verify that SQLite stores size M, quantity 2, unit price 2800 cents, and subtotal 5600 cents ($56). Stop and restart the application, retrieve the same order by ID, and confirm those values remain unchanged. Invalid input must not create an order. |



**\*\*US-5 peer-review revision (Issue #7):\*\*** For a concrete persistence test, select size M and quantity 2, complete the simulated checkout, capture the demo order ID, and check that SQLite stores the correct values (M, 2, 2800 cents per shirt, 5600 cents subtotal). Stop and restart the application, retrieve the order by ID through the server, and compare the stored values to the confirmation. A browser-only confirmation does not satisfy this check. This is a planned acceptance test, not a test result.

These checks are **\*\*acceptance criteria to execute later\*\***, not completed test results. Existing \`BRAND-001\` tests do not establish that checkout or SQLite persistence works.



**## Essential features and scope**



**\*\*Keep from existing work:\*\*** UNBOUND branding, modernist/postmodernist comparison, size selector, temporary demo bag, style ideas, optional style preference, responsive layout, and accessible navigation.



**\*\*Plan to add:\*\*** consistent bag quantity and subtotal controls, a simulated checkout page/form, server-side validation, SQLite order persistence, a simulated confirmation page, and a documented reopen/restart persistence check.



**\*\*Out of scope:\*\*** real payments, payment-card fields, fulfillment, live inventory, real shipping charges, real customer accounts, and claims of completed orders. The demo must not collect sensitive payment information.



**## Simulated checkout — proposed user flow**



1\. Visitor views the white tee and sees the fictional $28 price.

2\. Visitor selects a size and adds a quantity to the demo bag.

3\. Bag displays size, quantity, unit price, and calculated subtotal. If there is no item, checkout is disabled or clearly blocked.

4\. Visitor selects **\*\*Continue to simulated checkout\*\***. A prominent notice explains that no real payment or shipment occurs.

5\. Visitor enters only minimal **\*\*fictional demo details\*\*** (for example, a display name), confirms the bag summary, and selects **\*\*Place demo order\*\***. No card number or real address is requested.

6\. Server validates the request and saves the demo order plus its item(s) in SQLite using parameterized queries and a transaction.

7\. Confirmation displays a generated demo order ID and **\*\*“Simulation only — no payment was taken and nothing will ship.”\*\***

8\. Restart the local app and retrieve the demo order by ID to confirm that data persisted in the SQLite file.



**\*\*Boundary:\*\*** This is a planned flow. The current temporary browser bag is not evidence of SQLite persistence.



**## SQLite backend — proposed technical plan**



**\*\*Architecture:\*\*** Browser HTML/CSS/JavaScript → local Node.js server/API → SQLite database file. Keep database access on the server; the browser must not write directly to SQLite.



**\*\*Suggested minimal schema:\*\***



\`\`\`sql

CREATE TABLE IF NOT EXISTS demo_orders (

  id INTEGER PRIMARY KEY AUTOINCREMENT,

  display_name TEXT NOT NULL,

  subtotal_cents INTEGER NOT NULL CHECK (subtotal_cents >= 0),

  status TEXT NOT NULL DEFAULT 'SIMULATED',

  created_at TEXT NOT NULL DEFAULT CURRENT_TIMESTAMP

);



CREATE TABLE IF NOT EXISTS demo_order_items (

  id INTEGER PRIMARY KEY AUTOINCREMENT,

  order_id INTEGER NOT NULL REFERENCES demo_orders(id),

  product_code TEXT NOT NULL,

  size TEXT NOT NULL CHECK (size IN ('XS', 'S', 'M', 'L', 'XL', 'XXL')),

  quantity INTEGER NOT NULL CHECK (quantity BETWEEN 1 AND 10),

  unit_price_cents INTEGER NOT NULL CHECK (unit_price_cents >= 0)

);

\`\`\`



**\*\*Suggested endpoints (not implemented yet):\*\*** \`POST /api/demo-orders\` validates and creates an order; \`GET /api/demo-orders/:id\` retrieves a demo order for confirmation and verification. The server should enforce a known product code and **\*\*2800 cents\*\*** per shirt rather than trusting client-submitted prices. Enable SQLite foreign keys, use prepared statements, and insert the order and items atomically.



**\*\*Persistence check:\*\*** Start the app, create a demo order, record its ID, stop the server, start it again, and retrieve that same ID. Confirm its size, quantity, subtotal, and \`SIMULATED\` status. A \`localStorage\` or \`sessionStorage\` bag by itself **\*\*does not\*\*** meet the SQLite requirement.



**\*\*Implementation choice still open:\*\*** Review the instructor's Campus Cotton SQLite starter before deciding whether to adapt it or add a minimal Node.js/SQLite API to the current project. Record any starter-code reuse and modifications in \`LEARNING.md\`.



**## Planned verification checklist**



\- [ ] Verify desktop and mobile layout with the demo disclosure visible.

\- [ ] Test keyboard navigation, focus visibility, field labels, and validation messages.

\- [ ] Test no-size, valid-size, quantity-update, remove-item, and empty-bag behavior.

\- [ ] Confirm $28 × quantity math in both bag and server-calculated order.

\- [ ] Confirm simulated checkout does not ask for payment details.

\- [ ] Confirm invalid requests do not create database rows.

\- [ ] Confirm a successful simulated order is stored in SQLite.

\- [ ] Stop and restart the server; retrieve the same order and verify persistence.

\- [ ] Run the project's available automated checks and record exact commands/results.

\- [ ] Ask a classmate to walk through **\*\*US-5\*\*** and explain how they would verify persistence.



**## Peer review and decision history — Issue #7**

**\*\*Story reviewed:\*\*** US-5 — simulated checkout with SQLite persistence.  
**\*\*Issue:\*\*** https://github.com/njd54/is117-brand-studio/issues/7  
**\*\*Feedback recorded:\*\*** November 16, 2026, in the GitHub issue screenshot. The reviewer comment recommends testing a size selection, simulated checkout confirmation, and persistence of size, quantity, and total after restarting the application.

\| Evidence | Status / link |
\| --- | --- |
\| Reviewer and date | PazuAvalon account posted the comment on November 16, 2026; confirm that the commenter is the actual classmate reviewer for the assignment. |
\| Reviewer question or GitHub issue | [Issue #7](https://github.com/njd54/is117-brand-studio/issues/7): Is the checkout acceptance check specific enough to demonstrate SQLite persistence? |
\| My decision and reason | **Revise.** A specific saved-order test distinguishes real SQLite persistence from a browser-only confirmation and makes US-5 objectively checkable. |
\| Planned change to SPEC.md | US-5 now specifies size M, quantity 2, $28 each, $56 subtotal, a demo order ID, and a restart-and-retrieve comparison. |
\| Linked documentation commit or PR referencing #7 | Pending — link the commit after pushing this revision. |
\| Verification | Documentation review planned: confirm US-5 and the persistence checklist agree. Running the application and inspecting SQLite remain untested. |
\| Reviewer retry/confirmation | Pending — ask the reviewer to check the revised acceptance criteria. |
\| Issue resolution | Leave open until the change is linked, checked, and reviewer follow-up is recorded. |

**\*\*Suggested reviewer recheck:\*\*** Can you now identify the exact data to inspect in SQLite and the steps needed to verify persistence after restarting the app? Record the actual response in Issue #7.

**## Review 2 submission checklist**



\- [x] Compare two approaches and select one with a rationale.

\- [x] Preserve target audience, brand promise, visual choices, and two honest persuasion elements.

\- [x] Define five user stories, essential features, and observable checks.

\- [x] Include simulated checkout and working SQLite backend **\*\*in the plan\*\***.

\- [ ] Commit this updated plan to the existing T-shirt repository.

\- [x] Record the Issue #7 feedback and the decision to revise US-5.
\- [ ] Link the revision commit, verify the updated plan, and obtain reviewer confirmation.

\- [ ] Submit in Canvas: the updated record link, repository URL, current prototype/site URL if available, relevant issue link, and a short change/open-issue note.



**\*\*Repository:\*\*** https\://github.com/njd54/is117-brand-studio  

**\*\*Record:\*\*** https\://github.com/njd54/is117-brand-studio/blob/main/SPEC.md  

**\*\*Prototype:\*\*** Link the actual published site if available; do not invent a URL.  

**\*\*AI assistance:\*\*** ChatGPT helped structure this plan and propose acceptance criteria and a SQLite design. The student must review choices, verify implementation claims, and document real results before submission.
