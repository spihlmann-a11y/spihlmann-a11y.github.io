# QA Check Report

**Verdict: no 🔴 items. The prototype can go to internal review. Before any external or live use, the two placeholder CTA links and the "Nothing ... is stored" claim (both 🟡 below) need to be fixed.**

**Files checked:**
- Prototype: `04-prototype/index.html`
- Strategy: `02-strategy.md`
- Copy: `03-copywriting.md`

## 🔴 Must fix

None. The HTML is well formed, and all copy from `03-copywriting.md` (slogan, hero, supporting line, the 4 selling points, both CTAs, closing line) is reproduced word for word. Nothing on the page contradicts the strategy.

## 🟡 Recommended fixes

1. **Placeholder links on both CTA buttons (lines 152, 156)**
   - `<a href="#" class="btn btn-primary">Find a partner optician</a>`
   - `<a href="#" class="btn btn-secondary">Read our privacy whitepaper</a>`
   - Both go nowhere. The hero CTA (line 114, `href="#cta"`) only scrolls down to the second "Find a partner optician" button, which also goes nowhere, so the main conversion path is a dead end.
   - Acceptable for a prototype marked "Demo prototype"; becomes 🔴 before any external demo or launch.
   - **Fix:** point them to real or placeholder pages (e.g. `/optician-finder`, `/privacy-whitepaper`), or mark them as disabled ("Coming soon").
   - The copy notes (line 80) say the whitepaper CTA must not go live until the whitepaper and DPIA summary are published (Phase 0 deliverables in the strategy).
2. **The subheadline and card 2 disagree about storage (line 109 vs 130)**
   - The hero says "Nothing the people around you say is stored...", which is absolute.
   - Card 2 and the strategy (pillar 1) say audio "is not stored by default".
   - The § 201 StGB legal opinion is still open in the strategy, so the absolute claim is the riskier wording.
   - This comes from the copy file, not the developer: send it back to copywriter or legal to settle one wording, e.g. "Nothing ... is stored by default or used to train AI".
3. **Card 2 claims "We publish a privacy whitepaper and a summary of our data protection impact assessment" (line 130)**
   - Present tense, but both documents are Phase 0 deliverables that don't exist yet.
   - Fine for an internal demo. For external use, publish them first or reword (e.g. "We will publish...").
4. **Brand placeholder "Our Glasses" (line 99)**: expected, since the copy says the product name isn't defined yet. Track it so it gets replaced before any external use.
5. **The demo subtitle doesn't show the German-first selling point (line 111)**
   - "Shall we order dessert too?" is not in the copy file; the developer added it. It is harmless and fits the "dinner table" scenario.
   - A German line such as „Bestellen wir noch einen Nachtisch?" would show the main selling point better. Optionally add an English translation underneath to show the translation feature.
6. **Page language vs target market (line 2, `lang="en"`)**: an English page is fine for internal review. Real use needs a German version, and the copy only gives a German slogan ("Alle verstehen. Niemanden filmen."). Switch to `lang="de"` when localising.
7. **Text contrast in the hero (lines 34, 46)**
   - `.slogan` and `.supporting` use white text at `opacity: 0.85` and small sizes (0.9rem / 0.95rem) over the gradient.
   - Toward the lighter end of the gradient (#1b7a8c), contrast may fall below WCAG AA (4.5:1).
   - The main audience includes older, hard-of-hearing readers, so use full opacity or a slightly larger font size.
8. **Small additions to consider**
   - No `<meta name="description">`.
   - The `.subtitle-demo` box (line 111) has no label for screen readers, e.g. `aria-label="Example of a live subtitle"`.
   - The headings "Why our glasses" (line 120) and "Ready to try them?" (line 148) were added by the developer, not taken from the copy file. Their tone fits, but copywriter should approve them.

## 🟢 Passed items

- **HTML structure**
  - DOCTYPE, charset and viewport meta tags are present.
  - All tags are closed and properly nested.
  - Uses meaningful structural tags (`header` / `main` / `section` / `article` / `footer`).
  - Headings are in a sensible order: one `h1`, then `h2`, then `h3`.
- **Copy matches word for word**: slogan, headline, subheadline, supporting line, all 4 selling points, both CTA lines and buttons, and the closing line.
- **Consistent with the strategy**
  - Covers all four strategy pillars: no camera, German-first, optician and prescription fit, EU hosting with no transfers to the US or China.
  - Puts Priority 1 (hard of hearing) first, with the dinner-table and pharmacy-counter scenarios, and mentions Priority 2 (translation).
  - Doesn't drift toward a camera or lifestyle product.
- **Follows the copy's restrictions**: no price, accuracy figures, language counts or insurance-reimbursement claims, and no claims about a listening indicator or § 201 StGB.
- **CTAs are clear**: the primary (amber) and secondary (outlined) buttons are clearly different, and the hero CTA scrolls to the CTA section.
- **Mobile layout**
  - `@media (max-width: 600px)` shrinks the h1 and h2 and makes buttons full width.
  - Card and CTA grids use `repeat(auto-fit, minmax(...))` and drop to one column on phones, with no overflow down to a screen width of about 300px.
  - `box-sizing: border-box` is set for all elements, and the header holds only two short items, so there is little risk of the layout breaking.
- **Prototype is clearly marked**: the "Demo prototype" badge (line 100) and the footer disclaimer (line 166) prevent it being mistaken for a live product.
- **Keyboard focus is visible**: the browser's default focus outline is not removed.

## Summary: can it be delivered?

**Yes, as an internal review prototype.** There are no 🔴 issues. Before any external demo or launch:
- Fix the two `href="#"` CTA links (item 1).
- Settle the "not stored" vs "not stored by default" wording with copywriter or legal (item 2).
- Replace the "Our Glasses" placeholder name.
- Hold the whitepaper CTA and the "We publish..." claim until the Phase 0 documents are actually published.
