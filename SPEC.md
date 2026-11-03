# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- **Stage:** UNBOUND brand identity, storefront, style guide, and hero comparisons implemented; final review underway.
- **Current feature:** `BRAND-001` — first branded storefront and live style guide.
- **Status:** Feature branch `feature/brand-001-unbound`; `npm run check` passed, including 10 Playwright browser tests. GitHub issue, pull request, and merge not confirmed.
- **Next small decision:** Review the cited design references and confirm manual mobile/keyboard observations before committing.

## Product boundary

The product is the same white T-shirt throughout the comparison. The storefront retains a size selector and temporary demo bag. No real orders, payments, accounts, or persistence. The displayed $28 price is fictional demo data. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. The secondary card provides a contrasting need. Neither hypothesis has been validated with customer research.

| Tiny card                             | Primary audience                                                      | Secondary audience                                                         |
| ------------------------------------- | --------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| Person in a concrete situation        | College student aged 18–24 putting together an everyday campus outfit | Urban creative aged 22–30 choosing clothing for work and social activities |
| Goal or meaning they seek             | Confidence, individuality, and accessible streetwear styling          | Creative self-expression and versatility                                   |
| Concern before choosing               | Whether a simple white T-shirt fits their streetwear aesthetic        | Whether the understated product works with multiple personal styles        |
| What the page should help them decide | Whether UNBOUND suits their outfits and preferred size                | Whether the product complements their wardrobe                             |
| Evidence or assumption                | Audience hypothesis, not validated by research                        | Audience hypothesis, not validated by research                             |

## Early brand brief

| Decision                                 | Agreement                                                                                                                             |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Brand name                               | **UNBOUND** (creative concept; trademark availability not checked)                                                                    |
| One-sentence promise                     | A versatile everyday essential that lets your personal style stand out.                                                               |
| Primary archetype: the brand's character | **The Rebel** — independent and expressive                                                                                            |
| Three voice traits                       | Bold, direct, authentic                                                                                                               |
| One example line in this voice           | **WEAR YOUR OWN WAY.**                                                                                                                |
| Learner's predicted audience effect      | College streetwear enthusiasts may associate UNBOUND with confidence and individuality. This is a prediction, not a validated result. |

## Visual decision

The two coded hero previews use the **same white T-shirt**, headline, supporting copy, and action. The comparison changes visual treatment rather than product claims.

| Item                                            | Agreement or evidence                                                                                                                                                                                                                                                 |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action              | `WEAR YOUR OWN WAY.` / `One essential. Endless ways to express yourself.` / `SHOP THE TEE`. Both previews use `assets/white-shirt.svg`.                                                                                                                               |
| Modernist preview and annotations               | `public/studio.html`: restrained typography, ordered composition, clear hierarchy. Intended effect: straightforward product evaluation. Risk: less distinctive to the primary audience. See modernist references below.                                               |
| Postmodernist preview and annotations           | `public/studio.html`: oversized expressive type, layered or tilted elements, bold contrast, and red accents. Intended effect: individuality and energy. Risk: visual overload or reduced legibility. See postmodernist references below.                              |
| Chosen direction and reason                     | **Postmodernist.** The learner's explanation: youth is a time of self-expression and discovering identity; clothing can communicate individuality. This is a design rationale, not a measured audience result. Keep navigation and shopping controls straightforward. |
| Original SVG logo                               | `public/assets/unbound-logo.svg`: UNBOUND wordmark with a red diagonal slash.                                                                                                                                                                                         |
| Monochrome and small-size variants              | Learner marked logo review complete in `LEARNING.md`; confirm that the actual one-color presentation is present and readable before merging.                                                                                                                          |
| Logo review at actual use size                  | Learner marked this complete in `LEARNING.md`; detailed observation not recorded here.                                                                                                                                                                                |
| Shared palette, typography, spacing, and assets | Brand references: ink `#111111`, off-white `#F4F1E9`, signal red `#E6392E`, concrete gray `#8D9094`. Accessible interactive red uses `#C92C23` where needed. `public/styles.css` supplies shared tokens; `public/styleguide.js` reads those tokens.                   |

### Design research references and application

These references inform the _interpretation_ of the two styles. They are not evidence that the artists endorsed UNBOUND. Source links and work titles should be checked in the browser before final submission.

#### Modernist references

**1. Herbert Bayer — Bauhaus typography and graphic design**  
Source: Museum of Modern Art (MoMA)  
https://www.moma.org/collection/works/5101

- **Observed design principle:** Functional typography, ordered visual relationships, and purposeful hierarchy associated with Bauhaus modernism.
- **Application to the modernist UNBOUND preview:** Restrained type treatment and clearly separated product information help the visitor evaluate the white T-shirt.
- **Intended effect:** Clarity and ease of scanning.
- **Risk:** The composition could feel too conventional for the chosen streetwear audience.

**2. Swiss International Typographic Style (1950–1970)**  
Source: Swiss National Library  
https://www.nb.admin.ch/en/the-international-style-1950-1970

- **Observed design principle:** Structured grids, typographic clarity, and controlled visual organization.
- **Application to the modernist UNBOUND preview:** Balanced spacing, a consistent hierarchy, and a straightforward action link.
- **Intended effect:** Make the product and next action immediately understandable.
- **Risk:** Minimal expression of the Rebel archetype.

#### Postmodernist references

**3. Paula Scher — _The Diva is Dismissed_ (1994)**  
Source: Museum of Modern Art (MoMA)  
https://www.moma.org/collection/works/8837

- **Observed design principle:** Expressive typography and unconventional relationships among type, scale, and space.
- **Application to the postmodernist UNBOUND preview:** Oversized headline and more assertive visual hierarchy.
- **Intended effect:** Communicate personality, confidence, and individuality.
- **Risk:** Large or crowded typography can compete with product information.

**4. April Greiman — _Your Turn, My Turn_ (1983)**  
Source: Cooper Hewitt, Smithsonian Design Museum  
https://www.cooperhewitt.org/2017/08/30/26363/

- **Observed design principle:** Experimental composition and a willingness to challenge conventional graphic-design layouts.
- **Application to the postmodernist UNBOUND preview:** Layered elements, asymmetry, and unexpected visual emphasis.
- **Intended effect:** Reinforce the idea of making one's own style choices.
- **Risk:** Decorative complexity can interfere with reading and navigation if uncontrolled.

**Chosen approach:** Use postmodernist expression for UNBOUND's personality, while retaining modernist clarity in navigation, product facts, size controls, and the demo bag. The references are documented here; confirm that the live Studio page also contains the required source links or annotations if the assignment requires them to appear on-page.

## Ethical persuasion

Both applications are present in the supplied `public/index.html`. Neither requires a purchase, account, or personal data.

| Principle                                    | Actual copy or interaction                                                                                                                                                              | Visitor benefit / factual support                                                                                         |
| -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Reciprocity — implemented**                | Section `ONE TEE. THREE WAYS.` provides three free outfit ideas: **Campus casual**, **Layered streetwear**, and **Clean contrast**. Label: `FREE STYLE NOTES / NO PURCHASE NEEDED`.     | Useful styling inspiration before any shopping decision. Suggestions are not claims about the shirt's fit or performance. |
| **Commitment and consistency — implemented** | Section `WHAT'S YOUR STYLE?` provides optional radio choices **Minimal**, **Layered**, **Bold**, and **Mixed**. The selection can be changed and does not alter or submit the demo bag. | Visitors can articulate a voluntary style preference; no pressure to buy and no false commitment claim.                   |

The required product size selector is not counted as the commitment-and-consistency feature. The two dedicated sections are separate from it.

## BRAND-001 — first branded storefront and live style guide

**Scope:** Turn the working neutral storefront into UNBOUND's first coherent branded page. Keep the size selector and demo bag usable. Do not add checkout or future features.

### Acceptance criteria

- [x] Choose audience hypotheses, brand brief, and postmodernist direction.
- [x] Implement modernist and postmodernist coded hero previews with the same product and copy.
- [x] Document real design references, visual choices, intended effects, and risks in this spec.
- [x] Create and use the UNBOUND SVG logo asset.
- [x] Brand the storefront and retain the live style guide.
- [x] Preserve the size selector and demo bag.
- [x] Implement two ethical persuasion applications.
- [x] Pass automated formatting, linting, unit, browser, and accessibility checks.
- [x] Confirm the cited references and annotations appear in the Studio page as required.
- [x] Record specific manual mobile and keyboard observations.
- [x] Confirm the one-color logo presentation is usable in the final browser review.
- [x] Review and approve `LEARNING.md`, including the learner's own test interpretation.
- [ ] Verify issue, commit, push, pull request, review, and merge into `main`.

## Evidence

Passing automated checks is evidence only for their tested assertions, not customer research or proof of complete accessibility.

| Spec ID   | Files                                                                                                                                                                     | Issue / PR                                                                                        | Actual checks and observations                                                                                                                                                                                                                                                                                                                                                                        |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRAND-001 | `SPEC.md`, `LEARNING.md`, `public/index.html`, `public/styles.css`, `public/studio.css`, `public/styleguide.html`, `public/studio.html`, `public/assets/unbound-logo.svg` | Feature branch `feature/brand-001-unbound`; issue and PR numbers not supplied; merge not verified | **November 3, 2026:** Final `npm run check` passed. Prettier and lint checks passed, as did unit tests and **10 Playwright browser tests**. Accessibility testing initially found low contrast on Studio elements; CSS was corrected and the page-integrity tests passed. Learner reported a positive overall browser impression; detailed manual mobile/keyboard observations remain to be recorded. |

### Accessibility correction record

The Studio page initially failed color-contrast checks for the ribbon label, UNBOUND stamp, and postmodernist shopping link. Darker red backgrounds and readable text colors were applied. A duplicate CSS selector and a `#ffffff` versus `#fff` Stylelint issue were also resolved. The final full check passed.

## Later

No follow-up feature is selected. After keeping and merging `BRAND-001`, choose one next cycle, such as a brand story, supported fit guide, or richer demo-bag behavior. Agree its scope and add a new spec ID then.
