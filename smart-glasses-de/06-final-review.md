# Project Review: Camera-Free Prescription Smart Glasses for Germany (working name: "Our Glasses")

*Reviewer: Reviewer Agent. Date: 20 Nov 2026. Inputs reviewed: `01-research.md`, `02-strategy.md`, `03-copywriting.md`, `04-prototype/index.html`, `05-qa-report.md`.*

---

## Executive Summary

The team researched the German smart-glasses market and found three things. Meta dominates it. Germans are unusually sensitive about camera glasses (§ 8 TDDDG debate, HateAid complaint, EDPB statement, 76-82% privacy concern in Bitkom data). The display segment is still fragmented. From this, the team chose a sharp position: **camera-free prescription smart glasses that show live subtitles and translation, sold through opticians, with on-device or EU-hosted AI**. The first target is glasses wearers who are hard of hearing. The slogan "Understand everyone. Film no one." expresses the strategy well, and the landing-page prototype reproduces the copy word for word. Each step follows from the one before it, and that is the work's main strength.

I don't think this is ready for investment yet. Two questions could change the business case, and no stage has answered them:

1. **Is a microphone-based "always listening" product actually a privacy win with bystanders and under the law?** This covers § 201 StGB and GDPR.
2. **Does marketing to people with hearing loss turn the glasses themselves into a medical device under MDR?**

Two more facts are unverified. We don't know whether Even Realities and Rokid already offer German subtitles and translation, and that is the battleground the strategy picked. We also don't know the size of the target segment.

**Verdict:** this is a strong, internally consistent concept package and a good internal demo. It is not yet a validated go-to-market plan.

---

## Stage Overview

| Stage | Output | Status | Reviewer note |
|---|---|---|---|
| 01 Research | `01-research.md`: market trends, 10 competitors, B2C/B2B segments, regulatory map (TDDDG, GDPR/EDPB, AI Act, RED/CRA, MDR), opportunities, risks, sources | Complete, with data gaps | Broad and well sourced. Estimates are labelled honestly. Gaps: no German market size, no check of competitors' subtitle/translation features, no hearing-loss market data, and the +449% display figure is not in the data table |
| 02 Strategy | `02-strategy.md`: positioning, 2 priority segments, 4 differentiation pillars, competitor angles, pricing guidance, phased GTM (0-3), risks | Complete, with open gaps flagged | Clear and evidence-linked. Marks "information insufficient" honestly. Rests on two unverified assumptions (Even's "limited AI", segment size) and misses the MDR question for the device itself |
| 03 Copywriting | `03-copywriting.md`: slogan (EN/DE), hero, 4 selling points, CTAs, 8-point pitch deck, review notes | Complete, needs legal and copy revision | Faithful to the strategy and disciplined about unproven claims. Some absolute wording ("Nothing... is stored", "We publish...") runs ahead of the facts. The website never names hearing loss |
| 04 Prototype | `04-prototype/index.html`: single-page responsive landing page | Complete as an internal demo | Clean semantic HTML, copy reproduced exactly, clearly marked as a demo. English only, dead CTA links, placeholder brand name |
| 05 QA | `05-qa-report.md`: 0 red, 8 yellow, full pass list | Complete, but limited in scope | Good technical and copy-match check. Caught the storage-wording conflict. Checked only the strategy-to-page chain, so it missed the regulatory and positioning issues listed below |

---

## Strengths

1. **Each stage builds on the one before.** Each document says what it is based on, and the logic holds from research to strategy to copy to page. The privacy findings (§ 8 TDDDG, EDPB, Bitkom 76%/82%) lead directly to the "no camera" choice. That choice leads to the slogan, and the slogan is the first thing on the page. I found nothing in the page that contradicts the strategy.
2. **The position is sharp and defensible.** The team turned Germany's main market barrier, distrust of camera glasses, into the product's main selling point. They also avoided Meta's strongest ground (capture, lifestyle, sport). The "What we are not" list and the table of segments not targeted first show real strategic discipline.
3. **The team is honest about what it doesn't know.** Research labels estimates and lists data gaps. Strategy writes "information insufficient" instead of inventing numbers. Copy deliberately leaves out price, accuracy, language counts, reimbursement and listening-indicator claims, and explains why in its review notes. That is unusually careful work for a pipeline of this kind.
4. **The channel logic fits the context.** The pitch to opticians fits their situation well: Fielmann, Apollo and Mister Spex are named in the HateAid complaint, and Fielmann and Apollo received the Big Brother Award. They have a concrete reason to want a lower-risk smart-glasses category. Softening the pitch from "without legal exposure" to "without the camera controversy" was a correct legal judgement.
5. **The compliance groundwork is thorough.** Phase 0 lists RED/EN 18031, CRA, GPSR, ElektroG/LUCID, DPIA, Data Act and AI Act limits. It's a practical pre-launch checklist.
6. **The prototype and QA are solid.** The HTML is semantic, responsive and accessible by default, with the prototype clearly marked. QA checked the copy word for word and caught the one real copy inconsistency ("stored" vs "stored by default"). QA also flagged hero contrast, which matters for an older target audience.

---

## Weaknesses

### A. Cross-stage consistency problems

1. **The website never addresses the main target segment directly.** The strategy says Priority 1 is glasses wearers who are hard of hearing, and the pitch deck mentions "hearing loss". The website copy, however, never says "hearing", "hard of hearing" or "hearing loss". It speaks to everyone who wants to "follow every conversation". That may be deliberate (to avoid stigma, or to avoid a medical-device claim; see B2), but no stage documents this choice. QA's statement that the page "puts Priority 1 (hard of hearing) first" is too generous: the scenarios fit, but the segment is not named.
2. **"Your family can relax around you" may not hold for a listening device.** The strategy openly says a microphone product is still exposed to § 201 StGB and needs a visible listening indicator. The copy makes bystander-comfort claims ("can relax around you", "without making anyone around you uncomfortable") but leaves the indicator out. The research shows that 62% would not let smart-glasses wearers into their homes. Nobody has tested whether that rejection is about cameras specifically or about smart glasses in general. The slogan "Film no one" invites the obvious reply from Digitalcourage or HateAid: "but it listens to everyone".
3. **The storage claim conflicts within the copy.** The hero says "Nothing the people around you say is stored". The selling point and strategy say "not stored by default". QA flagged this correctly. It needs one agreed wording, approved by legal.
4. **Statements that don't exist yet are written as fact.** "We publish a privacy whitepaper and a summary of our DPIA" is written in the present tense. Both are Phase 0 deliverables that haven't been produced.
5. **The page is in English for a German-first product.** The page says "Built for German conversations" and "Made for German", but the whole page, including the demo subtitle, is in English. Only the slogan exists in German. This is acceptable for internal review, but it undercuts the core selling point in any external demo.
6. **The pitch deck overstates the research.** Pitch point 2 says "Germans do not want [camera glasses]". The research shows 43% would wear smart glasses and 15% already have. The honest framing is "the market is split, and bystander acceptance is the limit". Pitch point 1 leads with "two thirds of adults wear glasses", which is unverified, and then pairs it with "many of them struggle", which is not quantified anywhere.

### B. Gaps that run through every stage

1. **Even Realities and Rokid were never checked against our core features.** The strategy's head-to-head plan against Even G2 rests on the research's note of "limited AI features". Nobody checked whether Even G2 or Rokid already offer live subtitles or translation in German. Rokid is noted for 89-language translation. If competitors already ship these features, our differentiation shrinks to "German quality + EU hosting + optician focus", and the strategy's own risk #2 has already happened.
2. **The MDR question for the device itself was missed.** Research and strategy treat MDR only for prescription lenses (class I). If the product is marketed to compensate for hearing loss, its software and the device could fall under MDR as a medical device, because a device intended to compensate for a disability falls within the MDR definition. That would mean a separate conformity route, cost and timeline. It could also be the route to health-insurance reimbursement, which the strategy calls its top research priority. This choice affects claims, price, channel and timeline, and no stage raised it.
3. **Substitute products are missing from the competitive analysis.** For hard-of-hearing users, the real alternatives are hearing aids sold through acousticians and free phone captioning apps, not only other smart glasses. Neither appears in the research or strategy, so we can't yet show why a user would pay up to about EUR 699 on top of what they already use.
4. **Some key evidence lacks a source or a check.** The "+449% display AI glasses H1 2026" figure is central to the strategy's choice of display. It appears only in research section 4.3 and is not in the sourced data table. Smaller inconsistencies: Meta's share is given as 69-82% in one place and 70-80% in another, and the Bitkom 76% is described in two slightly different ways ("filmed by them" vs "filmed unnoticed").
5. **The technology architecture isn't defined.** "Processed on the device or in the EU" and "no data transfers to the US or China" are firm promises. Nobody has decided where speech recognition and translation run, or which provider supplies them. If a US-owned hyperscaler or LLM provider is used, even with EU hosting, the "no US transfers" claim needs legal review.
6. **The business numbers are missing.** There is no segment size, no bill of materials, no optician margin, no price, no numeric KPIs and no budget or timeline for Phase 0. The strategy says so openly, but it means the plan cannot yet be checked for financial viability.

### C. QA scope

QA did a good job on what it checked (HTML, matching the copy, consistency with the strategy). But it checked only stages 02-04. It did not check claims against the research or the law, so items A1, A2, A6 and all of section B were outside its scope. Future QA passes should include a claims and compliance check.

---

## Recommended Next Steps (in priority order)

1. **Legal gate, before any external use (blocking).**
   - Get a legal opinion on § 201 StGB and GDPR for live transcription and translation without storage, including whether a listening indicator is needed and how it must work.
   - Get an MDR intended-purpose assessment: can we name hearing loss in marketing without the device becoming a medical device? Or should we choose that route deliberately to pursue reimbursement?
   - Check whether the "no transfers to the US or China" claim holds for the planned processing providers.
2. **Check the competitive gap.** Run a hands-on feature audit of Even Realities G2, Rokid Glasses and Meta Ray-Ban Display for German live subtitles and translation (quality, latency, on-device vs cloud). Add hearing aids and phone captioning apps to the competitor set. If competitors already match us, adjust the differentiation before spending more on branding.
3. **Size and validate the Priority 1 segment.**
   - Find the number of glasses wearers with hearing loss in Germany.
   - Check the health-insurance reimbursement route (linked to the MDR decision in step 1).
   - Run 10-15 interviews each with hard-of-hearing glasses wearers, opticians with audiology services, and bystanders. Ask the bystanders whether a listening, camera-free device is accepted in homes, workplaces and pharmacies.
4. **Decide the architecture and pricing basis.** Choose on-device vs EU-cloud speech recognition and translation and the provider. Draft a bill of materials and get optician margin expectations, so the "at or below EUR 699" target can be tested.
5. **Revise the copy based on steps 1-3.**
   - Settle one storage wording.
   - Change "We publish..." to future tense until the documents exist.
   - Decide explicitly whether to name hearing loss on the website.
   - Add the listening-indicator message once legal confirms it.
   - Tone down pitch point 2 to match the research ("the market is split").
   - Write a full German version.
   - Choose a product name.
6. **Update the prototype.**
   - Build a German page (`lang="de"`) with a German demo subtitle and an optional translation line.
   - Fix the two `href="#"` CTAs (link to placeholder pages or mark them "Coming soon").
   - Use full opacity for hero text to meet WCAG AA contrast.
   - Add a meta description and an aria-label on the subtitle demo.
   - Get copywriter approval for the two headings the developer added.
7. **Fix research housekeeping.** Source or remove the +449% figure, align the Meta market-share numbers and the Bitkom wording, and buy GfK/NIQ or Statista data for German market volume.
8. **Widen the QA scope.** Add a claims and compliance check (every factual or legal claim traced back to the research or to a legal opinion) to the QA checklist for future cycles.
