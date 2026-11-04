# Brand Studio decisions — UNBOUND

This is the working record of agreed brand decisions, implemented features, and research evidence. Persona descriptions and expected audience responses are **hypotheses**, not validated customer findings. `LEARNING.md` records student explanations, AI assistance, and reflections.

## Current stage

- **Completed feature:** `BRAND-001` — UNBOUND branded storefront, live style guide, and modernist/postmodernist hero comparison.
- **Repository:** https://github.com/njd54/is117-brand-studio
- **BRAND-001 delivery:** `feature/brand-001-unbound` was pushed and pull request **#2** was merged into `main` (confirmed by the GitHub screenshot shared November 4, 2026).
- **Verification:** `npm run check` passed, including **10 Playwright tests**. Student manually reported: “Everything looks correct on mobile and I was able to navigate using only my keyboard.”
- **Current assignment:** IS117-007 — T-shirt Research, due **November 10, 2026, 8:30 a.m. Eastern**.
- **Next action:** Add dated competitor screenshots to the repository, confirm exact product URLs, discuss one observation with a classmate November 5, and record feedback, response, and a revision or justified decision to keep the design.

## Product boundary

UNBOUND is a concept for the same plain white T-shirt throughout its two design previews. The site includes a size selector and temporary demo bag; there are no real orders, payments, accounts, or persistent cart data. The **$28** displayed price is fictional demo data, not a market-validated price. Do not claim unverified materials, fit, sustainability, shipping, customer reviews, sales, or product scarcity.

## Audience hypotheses

| Question                     | Primary audience hypothesis                                                 | Secondary audience hypothesis                                     |
| ---------------------------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Person and situation         | College student aged 18–24 assembling everyday campus outfits               | Urban creative aged 22–30 dressing for work and social activities |
| Goal                         | Feel confident and express individuality with accessible streetwear styling | Express creativity and adapt basics to several settings           |
| Concern                      | Whether a simple white T-shirt can fit their personal streetwear aesthetic  | Whether the understated shirt can work with different outfits     |
| Site should help them decide | Whether UNBOUND suits their style and which size to choose                  | Whether the shirt complements their existing wardrobe             |
| Evidence status              | Hypothesis; no customer interviews or purchase data                         | Hypothesis; no customer interviews or purchase data               |

## Early brand brief

| Decision         | Agreement                                                                                                           |
| ---------------- | ------------------------------------------------------------------------------------------------------------------- |
| Brand name       | **UNBOUND** (creative concept; trademark availability not checked)                                                  |
| Promise          | A versatile everyday essential that lets your personal style stand out.                                             |
| Archetype        | **Rebel** — independent and expressive                                                                              |
| Voice            | Bold, direct, authentic                                                                                             |
| Tagline          | **WEAR YOUR OWN WAY.**                                                                                              |
| Predicted effect | College streetwear enthusiasts may associate UNBOUND with confidence and individuality; not validated by customers. |

## Visual decision

Both coded hero previews use the **same white T-shirt**, headline, supporting copy, and action. Only the visual presentation changes.

| Element               | Decision and rationale                                                                                                                                       |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Shared content        | `WEAR YOUR OWN WAY.` / `One essential. Endless ways to express yourself.` / `SHOP THE TEE`; both use `assets/white-shirt.svg`.                               |
| Modernist preview     | Restrained typography, ordered composition, and clear hierarchy. Intended benefit: quick product evaluation. Risk: less distinctive for the target audience. |
| Postmodernist preview | Oversized typography, layering, asymmetry, strong contrast, and red accents. Intended benefit: energy and individuality. Risk: visual overload.              |
| Selected approach     | **Postmodernist**, because the student views youth as a period of self-expression and discovering identity. Preserve clear navigation and shopping controls. |
| Logo                  | `public/assets/unbound-logo.svg`, UNBOUND wordmark with red diagonal slash.                                                                                  |
| Palette               | Ink `#111111`; off-white `#F4F1E9`; signal red `#E6392E`; concrete gray `#8D9094`; darker interactive red `#C92C23` where needed for contrast.               |
| Implementation        | `public/styles.css` supplies shared tokens; `public/styleguide.js` reads them; `public/studio.html` shows the two treatments and research annotations.       |

### Design research references and application

These are design precedents, **not endorsements of UNBOUND**. The connections below are the student's design interpretations.

**Modernist reference 1 — Herbert Bayer, Bauhaus graphic design.** Museum of Modern Art: https://www.moma.org/collection/works/5101

- Principle: functional typography and purposeful visual hierarchy.
- UNBOUND application: restrained type and clearly separated product information in the modernist preview.
- Intended effect: easy scanning; risk: conventional appearance.

**Modernist reference 2 — Swiss International Typographic Style (1950–1970).** Swiss National Library: https://www.nb.admin.ch/en/the-international-style-1950-1970

- Principle: structured grids, legibility, and controlled organization.
- UNBOUND application: balanced spacing, consistent hierarchy, and straightforward action link.
- Intended effect: clarity; risk: limited expression of the Rebel archetype.

**Postmodernist reference 1 — Paula Scher, _The Diva is Dismissed_ (1994).** Museum of Modern Art: https://www.moma.org/collection/works/8837

- Principle: expressive type, contrasting scale, and unconventional composition.
- UNBOUND application: oversized headline and assertive hierarchy.
- Intended effect: personality and confidence; risk: crowding product information.

**Postmodernist reference 2 — April Greiman, _Your Turn, My Turn_ (1983).** Cooper Hewitt, Smithsonian Design Museum: https://www.cooperhewitt.org/2017/08/30/26363/

- Principle: experimental, layered composition.
- UNBOUND application: asymmetry and unexpected visual emphasis.
- Intended effect: encourage individual style; risk: legibility if overused.

**Conclusion:** Use postmodernist expression to communicate brand personality, but modernist clarity for product facts, navigation, size controls, and bag feedback.

## Ethical persuasion in UNBOUND

| Principle                      | Implemented feature                                                                                                                               | Benefit and boundary                                                                      |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| **Reciprocity**                | `ONE TEE. THREE WAYS.` offers free ideas: Campus casual, Layered streetwear, Clean contrast. Copy states `FREE STYLE NOTES / NO PURCHASE NEEDED`. | Visitors get useful styling ideas without needing to buy. No unsupported product claims.  |
| **Commitment and consistency** | `WHAT'S YOUR STYLE?` offers optional Minimal, Layered, Bold, and Mixed choices.                                                                   | Visitors can express a preference without an account, purchase, or persistent commitment. |

The ordinary product-size selector is **not** counted as the separate commitment-and-consistency feature.

## BRAND-001 — completion and evidence

- [x] Choose audience hypotheses, Rebel brand character, and postmodernist direction.
- [x] Implement two coded hero previews with identical product and copy.
- [x] Document modernist and postmodernist sources and tradeoffs.
- [x] Create original UNBOUND SVG wordmark and coherent storefront/style guide.
- [x] Preserve size selection and demo bag.
- [x] Implement two ethical persuasion features.
- [x] Pass automated format, lint, unit, browser, and accessibility checks.
- [x] Manually check mobile layout and keyboard-only navigation.
- [x] Push feature branch and merge pull request #2 into `main`.

**Automated evidence:** On November 4, 2026, the final `npm run check` screenshot showed **10 passed**. This supports only the tested behaviors; it does not prove customer preference or complete accessibility.

**Manual evidence:** Student statement: “Everything looks correct on mobile and I was able to navigate using only my keyboard.”

**Accessibility corrections:** Earlier Studio tests identified insufficient contrast on the ribbon label, UNBOUND stamp, and postmodernist link. Text/background colors were adjusted. A duplicate CSS selector and hex-color lint issue were corrected; the final check passed.

---

# IS117-007 — T-shirt competitive research

**Research date:** November 4, 2026  
**Assignment due:** November 10, 2026, 8:30 a.m. Eastern  
**Research question:** How do three clothing websites communicate the value of a T-shirt, support product selection, and encourage purchase, and what should UNBOUND adopt or avoid?

**Method:** Inspect each product page and add **one size-medium shirt** to the bag/cart where possible; document visible controls, messaging, and cart feedback without checking out, entering personal details, or purchasing. Compare the sites' **design and buying experience**, not equivalent products: the selected garments differ in category, fit, design, and price. Screenshots were supplied during the research conversation; copies still need to be committed to the repository for durable evidence. Prices and promotions are **point-in-time observations**, not current-price guarantees.

## Competitor 1 — UNIQLO

**Source:** https://www.uniqlo.com/us/en/products/E424873-000/00?colorDisplayCode=00&sizeDisplayCode=003  
**Observed product:** Women's Crew Neck T-Shirt, white. The first screenshot had **S** selected; the subsequent cart observation recorded one item, but the cart modal did not visibly confirm its size.

**Observed on product page:** $19.90 price; sizes XXS–XXL; white and other color swatches; size guide; **4.7 rating with 999+ reviews**; quantity controls; Add to Cart; store-availability and shipping information. Large product photography and black-on-white typography organize the page.

**Observed after adding to cart:** “Added to cart”; **1 item**, **$19.90 subtotal before tax**; message stating **$79.10** remaining to qualify for free standard shipping; “Frequently Bought Together” product recommendations; View Cart and Continue Shopping actions. No completed checkout was observed.

**Interpretation:** Predominantly **modernist** shopping interface emphasizing practical information and clarity. **Everyperson** is a plausible archetype hypothesis because of its accessible everyday positioning, not an official brand classification. The displayed reviews provide **social proof**. Recommendations and the shipping threshold may encourage additional purchases; neither proves actual customer behavior.

**What UNBOUND could use:** Visible price, size guidance, and unambiguous cart feedback. Avoid adding unnecessary pressure to spend more simply to meet a shipping threshold.

**Evidence to commit:** `research/screenshots/uniqlo-product-2026-11-04.png` and `research/screenshots/uniqlo-cart-2026-11-04.png` (proposed filenames; add actual screenshots and update paths if different).

## Competitor 2 — Represent

**Source:** Represent website, https://representclo.com/ . **Exact MH Paint product URL still needs to be copied from the browser**; do not substitute the previously suggested Owners Club product link.

**Observed product:** **MH Paint Short Sleeve T-Shirt**, Antique Slate, **$145**, distressed/paint-effect styling. Size choices XS–XXL; **S** appeared unavailable. The cart confirmed **M**, quantity 1. Page showed size chart, fit help, wishlist, estimated delivery, free shipping over **$175**, Prestige Points, and installment-payment information.

**Observed cart:** Slide-out cart showed **$145 subtotal**, **$10 estimated delivery**, and **$155 displayed total**. It offered “Others Also Bought” recommendations and a Secure Checkout button. Final tax, payment, and order completion were not tested.

**Interpretation:** The **interface** uses restrained, modernist-like black-and-white organization, while the **garment styling** is expressive and unconventional. **Rebel with possible Ruler elements** is an archetype hypothesis, based on visual distinctiveness and premium positioning. “Others Also Bought” suggests **social proof**, but the screenshot does not verify the recommendation data. Rewards and installments are sales mechanisms, not automatically distinct Cialdini principles.

**What UNBOUND could use:** Expressive brand identity paired with straightforward size selection and clear cart totals. Avoid unsupported exclusivity or premium-quality claims.

**Comparison limitation:** This distressed $145 shirt is **not** equivalent to UNIQLO's basic white crewneck or UNBOUND's fictional $28 white T-shirt.

**Evidence to commit:** `research/screenshots/represent-product-2026-11-04.png` and `research/screenshots/represent-cart-2026-11-04.png` (proposed paths).

## Competitor 3 — H&M

**Source:** https://www2.hm.com/en_us/ . **Exact Loose-Fit Interlock product URL still needs to be copied from the browser**; the earlier suggested Regular Fit product link is not evidence for this screenshot.

**Observed product:** **Loose-Fit Interlock T-Shirt**, cream, men's, **$15.00 sale price** from **$19.99** (25% off). Color swatches, sizes XS–XXL, size guide, shipping selection, and free pickup option were visible. The page showed a red **“FLASH SALE: 25% OFF UNTIL MIDNIGHT”** banner and a countdown timer. The screenshot indicated pickup availability at Westfield Garden State Plaza; availability may change.

**Observed add-to-bag confirmation:** Product, cream color, **size M**, **quantity 1**, and **$15.00** price. Shipping charges, taxes, final total, and checkout were not shown.

**Interpretation:** A structured product interface with high-contrast promotional styling. **Everyperson** is a plausible accessible-fashion archetype hypothesis. The deadline and countdown are evidence of **time-based scarcity messaging**; the screenshot does **not** independently verify the offer's enforcement or prove it changed purchasing behavior.

**What UNBOUND could use:** Clear size/availability feedback and convenient shopping choices, without making countdown urgency the main brand message.

**Evidence to commit:** `research/screenshots/hm-product-2026-11-04.png` and `research/screenshots/hm-bag-2026-11-04.png` (proposed paths).

### Competitor screenshot evidence

Research date: November 4, 2026.

The following screenshots document the product pages and add-to-cart interactions observed during the competitive research. No purchases were completed.

| Competitor | Product page screenshot                                  | Cart / bag screenshot                                     |
| ---------- | -------------------------------------------------------- | --------------------------------------------------------- |
| UNIQLO     | [View product page](docs/research/uniqlo-product.png)    | [View cart confirmation](docs/research/uniqlo-cart.png)   |
| Represent  | [View product page](docs/research/represent-product.png) | [View shopping cart](docs/research/represent-cart.png)    |
| H&M        | [View product page](docs/research/hm-product.png)        | [View add-to-bag confirmation](docs/research/hm-cart.png) |

#### Screenshot observations

**UNIQLO:** The product page shows a $19.90 Crew Neck T-Shirt, clear sizing options, customer ratings, and an Add to Cart button. The cart confirmation displays the subtotal, a free-shipping threshold, and related product recommendations.

**Represent:** The product page shows a $145 MH Paint Short Sleeve T-Shirt in Antique Slate. The cart displays one medium shirt, a $145 subtotal, $10 estimated delivery, and a $155 displayed total.

**H&M:** The product page shows a cream Loose-Fit Interlock T-Shirt discounted to $15.00 from $19.99. The add-to-bag confirmation shows one medium shirt. The page also displays a time-limited sale and countdown.

#### Research limitations

These screenshots document the product selection and initial cart interactions only. Full checkout, payment, and order completion were not tested. The selected shirts differ in style and positioning, so their prices are not directly comparable as identical products.

## Side-by-side findings

| Dimension              | UNIQLO                                      | Represent                                         | H&M                                      |
| ---------------------- | ------------------------------------------- | ------------------------------------------------- | ---------------------------------------- |
| Observed garment       | White women's crewneck                      | Distressed Antique Slate tee                      | Cream men's loose-fit tee                |
| Observed price         | $19.90                                      | $145.00                                           | $15.00 promotional ($19.99 original)     |
| Positioning hypothesis | Practical everyday basics                   | Premium expressive streetwear                     | Accessible trend-focused fashion         |
| Archetype hypothesis   | Everyperson                                 | Rebel / Ruler                                     | Everyperson                              |
| Visual treatment       | Restrained, organized                       | Restrained interface; expressive garment          | Organized interface; urgent sale styling |
| Persuasion evidence    | Review stars; related products              | “Others Also Bought”; rewards                     | Time-limited sale/countdown              |
| Bag/cart evidence      | 1 item; $19.90 subtotal; shipping threshold | $145 subtotal; $10 estimated delivery; $155 total | 1 medium shirt; $15 item confirmation    |
| UNBOUND lesson         | Clear sizing and cart information           | Distinctive identity without confusing controls   | Clear selection; avoid pressure tactics  |

**Cross-site conclusion:** All three sites provide product-selection controls, but their value messages differ. UNBOUND can distinguish itself through expressive styling inspiration while retaining understandable controls. The comparison does **not** establish what real customers prefer; further feedback is required.

## Two positioning alternatives

### Alternative A — Affordable everyday essentials

- **Person:** Budget-conscious college commuter.
- **Situation:** Needs an easy-to-style shirt for classes and everyday activities.
- **Need:** Simple choices, clear price, and confidence in sizing.
- **Positioning statement (hypothesis):** “One essential. Clear choices. Everyday versatility.”
- **Archetype fit:** Everyperson.
- **Supporting observation:** UNIQLO and H&M make sizing and pricing prominent.
- **Tradeoff:** Clear and practical, but may not differentiate UNBOUND from mainstream basics brands.

### Alternative B — Creative college streetwear

- **Person:** College streetwear enthusiast exploring personal identity.
- **Situation:** Styling a simple white T-shirt for campus, friends, and social activities.
- **Need:** Inspiration to express individuality without requiring an expensive statement garment.
- **Positioning statement (hypothesis):** “One essential. Endless ways to express yourself.”
- **Archetype fit:** Rebel.
- **Supporting observation:** Represent illustrates expressive streetwear positioning; UNIQLO and H&M illustrate the value of practical product controls.
- **Tradeoff:** More distinctive, but expressive visuals must not obscure the shirt, price, or sizing.

## Two short persona hypotheses

**Persona 1 — Jordan, 20, college commuter (Alternative A).** Jordan wants an affordable white tee that is easy to choose and style before class. Their main concern is making a practical purchase without confusing sizing or surprise costs. They would benefit from clear product facts and straightforward cart feedback. **Assumption:** This is a fictional persona, not an interviewed customer.

**Persona 2 — Alex, 21, creative college student (Alternative B).** Alex likes streetwear and wants to turn a plain white tee into outfits that feel personal. Their concern is whether a basic item can express individuality. They would benefit from styling ideas and expressive but readable branding. **Assumption:** This is a fictional persona, not an interviewed customer.

## Chosen audience and rationale

**Choose Alternative B — Creative college streetwear**, with **college streetwear enthusiasts aged 18–24** as the primary audience. This fits the already implemented UNBOUND Rebel archetype, postmodernist presentation, tagline **“WEAR YOUR OWN WAY,”** and free styling suggestions. Borrow the functional clarity of mainstream shopping interfaces rather than copying their positioning or using unverified scarcity claims.

**Why this is still a hypothesis:** The competitor screenshots show how brands present products; they do not prove that students prefer UNBOUND's concept, that the fictional $28 price is acceptable, or that the styling content increases conversion. The November 5 class discussion is an opportunity to challenge the assumption.

## Honest persuasion decision

- **Keep:** Free styling ideas (**reciprocity**) and optional style-direction choices (**commitment and consistency**).
- **Use carefully:** Clear size guidance, cart confirmation, and accurate price displays.
- **Avoid without evidence:** Fake reviews, unsupported limited-stock claims, invented shipping promises, or countdowns implying deadlines that are not real.
- **Disclosure:** UNBOUND's bag and price are a **demo**, not a live retail checkout.

## November 5 peer-feedback record — pending actual class activity

**Research observation to present:** Represent pairs an expressive garment with a minimal shopping interface; UNBOUND could do the same with postmodernist branding and simple product controls.

**Question for classmate:** “Does UNBOUND's expressive visual style help you understand its intended audience, or does it distract from the basic white T-shirt and size selection?”

- **Classmate's question or feedback:** Pending — record actual words or clearly labeled paraphrase after class.
- **My response:** Pending — write the student's actual explanation.
- **Decision (revise or keep, with reason):** Pending.
- **Change made and retest, if applicable:** Pending. If keeping the design, explain why and what was checked.
- **GitHub feedback issue URL:** Pending — create/update an issue in this repository after discussion.
- **Team partner:** Pending — record only after pairing in class.

## Submission checklist — IS117-007

- [x] Examine three relevant clothing websites and capture product/cart or bag screenshots.
- [x] Record screenshot-based observations, interpretations, and UNBOUND implications.
- [x] Compare two positioning alternatives and two persona hypotheses.
- [x] Choose and justify a primary audience, labeling assumptions.
- [x] Explain brand archetypes, modernism/postmodernism, and ethical persuasion.
- [ ] Add all six actual screenshots to the repository and update the evidence paths above.
- [ ] Record exact product-page URLs for the Represent and H&M products shown.
- [ ] Collect real peer feedback on November 5 and record a response and revision or justified keep decision in a GitHub issue.
- [ ] Recheck affected work after any changes and record the result.
- [ ] Commit and push the updated `SPEC.md` and evidence to GitHub.
- [ ] Submit in Canvas: research-record link, repository/site links, feedback issue link, and a brief change/open-question note.

**Assignment reminder:** Research submission is due **November 10, 2026, at 8:30 a.m. Eastern**. The separate portfolio/career research assignment is not part of this `SPEC.md` section.
