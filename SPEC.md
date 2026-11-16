# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: BRAND-001 kept and merged into main on 2026-11-16.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: [Pull request #2](https://github.com/rajveer-r-sharma/Brand-Studio-Webpage/pull/2) merged after full GitHub checks passed and the learner approved the merge. Scope agreed. Work is on `feature/brand-001` ([issue #1](https://github.com/rajveer-r-sharma/Brand-Studio-Webpage/issues/1)).
- Next small decision: Submit the repository URL in Canvas.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                                        | Secondary audience                                |
| ------------------------------------- | ------------------------------------------------------- | ------------------------------------------------- |
| Person in a concrete situation        | High school or college student dressing for class       | Student pairing the tee with an existing outfit   |
| Goal or meaning they seek             | Look put together in simple, comfortable school clothes | Feel confident in an understated outfit           |
| Concern before choosing               | Would a simple tee look good at school?                 | Would the tee draw more attention than they want? |
| What the page should help them decide | How they might wear the tee on a school day             | Whether the tee blends into their own outfit      |
| Evidence or assumption                | Assumption; not validated                               | Assumption; not validated                         |

## Early brand brief

| Decision                                 | Agreement                                                                                                |
| ---------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Brand name                               | Class Staple                                                                                             |
| One-sentence promise                     | A white tee that goes with what you already wear to class.                                               |
| Primary archetype: the brand's character | Everyperson                                                                                              |
| Three voice traits                       | Relaxed, direct, encouraging                                                                             |
| One example line in this voice           | A white tee that goes with what you already wear to class.                                               |
| Learner's predicted audience effect      | Students may picture navy, black, or other trousers they own and feel more confident wearing the outfit. |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                       |
| ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action                | Your everyday white tee. / A white tee that goes with what you already wear to class. Try it with navy or black trousers. / Choose a size   |
| Modernist preview, reference, and annotations     | [Course catalog](public/explorations/modernist.html), EKCO AC 74 radio                                                                      |
| Postmodernist preview, reference, and annotations | [Campus pinboard](public/explorations/postmodernist.html), Super lamp                                                                       |
| Chosen direction and reason                       | Modernist course catalog. The learner chose its simple layout because it fits a student who wants to look confident without feeling flashy. |
| Original SVG logo                                 | [Approved one-color staple and wordmark](public/assets/class-staple.svg).                                                                   |
| Monochrome and small-size variants                | The same navy SVG appears at 150px and 130px in the [logo preview](public/explorations/logo.html).                                          |
| Logo review at actual use size                    | Learner chose to keep the logo after the size preview was shared.                                                                           |
| Shared palette, typography, spacing, and assets   | Navy ink and warm paper, Arial, responsive grid spacing in catalog.css; shared styles.css and class-staple.svg.                             |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle   | Actual copy or interaction                                                                                     | Visitor benefit / factual support                                                                          |
| ----------- | -------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Reciprocity | Free navy-trouser and black-pant styling tip before any bag action.                                            | Gives a useful outfit idea without enrollment or obligation; learner approved keeping it.                  |
| Consistency | Voluntarily choose a navy or black pairing, then retain that choice as a styling reminder when adding the tee. | Helps a visitor follow through on their own outfit preference; learner values seeing whether they like it. |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                        | Issue / PR                                                                    | Actual checks and observations                                                                                                                          |
| --------- | ------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRAND-001 | public/index.html, public/styleguide.html, public/catalog.css, public/shop.js, public/explorations, SVG logo | [Issue #1](https://github.com/rajveer-r-sharma/Brand-Studio-Webpage/issues/1) | Baseline formatting, lint, and 7 server tests passed. Chromium launch was denied locally. Learner selected M and observed one size M shirt, quantity 1. |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.

## Implementation check — 2026-11-16

The learner preferred the optional pairing preview because students can see whether they like the outfit. Navy and black previews now accompany the original tee. Each bag entry retains the pairing chosen when added. The learner approved keeping the free outfit tip as the second persuasion application.

Storefront and guide share catalog.css, styles.css, and class-staple.svg. Formatting and lint pass, as do seven server tests. Local Chromium launch was blocked. The complete prepared suite subsequently passed on [GitHub Actions](https://github.com/rajveer-r-sharma/Brand-Studio-Webpage/actions/runs/43897476399).

In the available browser, pressing Add to demo bag without a size showed the size error and left the bag empty. Selecting Navy and M then adding produced one size M tee with a navy styling reminder. Switching the preview to Black left that existing reminder intact. At 1000px and 375px, the storefront, guide, and studio had no horizontal overflow. The agent inspected their rendered first views. Learner reports a good first impression from the simplicity, clear shirt description, size choice near the top, and clean border. Learner reports being able to navigate, select what they want, and add the shirt using the keyboard. Visible focus was not specifically described. Learner reports that at narrow/mobile width nothing was cut off or difficult to use and everything fit well.

## Final keep decision

The learner approved merging PR #2 after reviewing the passing checks and the purpose of merging the feature branch into main. [PR #2](https://github.com/rajveer-r-sharma/Brand-Studio-Webpage/pull/2) was verified merged on 2026-11-16 as ecac7a3fb0f46704afdbf14be5f3da98e9cf9bee. Publishing is optional and has not been requested.
