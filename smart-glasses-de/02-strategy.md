# Strategy Positioning Document: Smart Glasses for the German Market

*Based solely on `01-research.md` (research date 20 Nov 2026). Where the research does not support a judgement, this is stated explicitly as "Information insufficient, further research recommended".*

---

## 1. Product Positioning

**Positioning statement**

> For German glasses wearers who struggle to follow conversations because of hearing loss or a language barrier, we are camera-free prescription smart glasses that show live subtitles and translation in their field of view. Unlike Meta's camera glasses, ours cannot film anyone. The AI runs on the device or on EU hosting, and nothing the people around you say is stored or used to train AI.

Short form: **"Smart glasses that help you understand people and never film them."**

**Why this position (evidence from the research)**

| Strategic choice | Supporting fact in the report |
|---|---|
| **No camera** | § 8 TDDDG ban risk is rated "very high impact" for camera products. The HateAid criminal complaint and the ZIT review are ongoing. 76% of Germans reject being filmed unnoticed, and 62% would not let smart-glasses wearers into their homes. Even Realities' camera-free design "largely avoids the § 8 TDDDG debate". |
| **Display with subtitles and translation as the core use case** | Display AI glasses grew +449% in H1 2026. The report names subtitles and translation as "fast-growing" and "less tied to the camera". The display segment is still fragmented (Rokid 41%, Meta 37%, Even 11%), unlike the display-less segment, where Meta has 94%. |
| **Prescription-first** | About two thirds of German adults wear glasses (industry estimate, not verified for 2026). Opticians are becoming the main channel. Corrective lenses are MDR class I, so working with an optician or lens partner is the practical route. |
| **On-device and EU-hosted AI, no bystander data stored or used for training** | These are the EDPB Statement 01/2026 recommendations: data minimisation, on-device processing, no persistent storage by default. Using bystander data for AI training is "particularly difficult" to justify. Cloud transfers to the US or China need a Schrems-II/DPF assessment, and Chinese brands face extra scepticism. |

**What we are not:** We are not a lifestyle camera or POV device, not a sports camera and not a media display. We do not compete with Ray-Ban Meta or Oakley Meta on capturing content.

---

## 2. Target Segments

### Priority 1: Prescription-glasses wearers who are hard of hearing
- **Need:** Live subtitles of conversations in German, in their own prescription frame (report section 3.1: accessibility and prescription segments).
- **Why first:**
  1. The use case does not need a camera, so it fits the privacy-first product completely.
  2. The need is functional rather than a gadget want, so it is less exposed to the hype cool-down that IDC reports.
  3. They already buy through opticians, where they get fitting and advice, which is the channel we plan to use.
  4. Reliable German-language transcription is their main buying criterion. That plays to localisation, where foreign players are weaker.
- **Gaps:**
  - Information insufficient: the size of the hard-of-hearing glasses-wearer population in Germany is not in the report. Further research recommended.
  - Information insufficient: whether health insurance would reimburse the glasses, which the report explicitly did not investigate. This could change pricing and the channel strategy fundamentally, so it is the top research priority.

### Priority 2: Multilingual professionals and business travellers who wear glasses
- **Need:** Live translation in meetings, at trade fairs and when travelling, with data security as a stated buying criterion (section 3.1).
- **Why second:**
  1. It uses the same hardware and software as Priority 1, with translation added, so it needs no separate product.
  2. Data security matters to them, which makes the EU-hosting promise a selling point rather than just a cost.
  3. They overlap with Even Realities' "professionals" target, so this is where we have to win head-to-head.
- **Gap:** Information insufficient: segment size and willingness to pay. Further research recommended.

### Segments we are deliberately not targeting first
| Segment | Reason for deprioritising |
|---|---|
| Tech early adopters (16-40, urban) | This is Meta's home turf. They want hands-free capture, which needs a camera. Meta dominates on price, brand and distribution. |
| Sport / outdoor | Oakley Meta Vanguard makes up more than 30% of Meta's Q4 2025 shipments and has Garmin/Strava integration. The core need is POV video. |
| Blind / visually impaired | Object and text recognition needs a camera, which conflicts with our core promise. We could revisit this later with a separate, clearly marked product. |
| Enterprise (Mittelstand) | This is a real opportunity, but it has long sales cycles because of works councils, data protection and IT security. Incumbents such as RealWear, Vuzix and TeamViewer are established, and remote support usually needs a camera. We hold it as a Phase 3 option (see GTM). |

---

## 3. Differentiation Strategy

### Core differentiation pillars
1. **Privacy we can verify, not just promise**
   - The hardware has no camera.
   - Audio is processed for subtitles and translation in real time and is not stored by default.
   - Bystander data is never used for AI training.
   - We publish a DPIA summary and a statement mapping the product to the EDPB measures.
   - **Important caveat:** a microphone-based product is still exposed to § 201 StGB (confidentiality of the spoken word). Before launch, we need a legal opinion confirming that live transcription without storage is permissible, and the product should show a clear indicator while listening. The report flags audio recording as "critical" but does not analyse transcription specifically. Information insufficient, legal review required.
2. **German-first communication AI**
   - Quality German subtitles, plus German manuals, support, warranty and withdrawal handling.
3. **Built around prescription lenses and opticians**
   - Designed for optician fitting from day one, through a lens or optician partner (MDR class I).
4. **EU data sovereignty**
   - EU hosting for any processing that is not done on the device, with no US or China transfers. This addresses the trust gap that affects both Meta and the Chinese brands.

### Against key competitors
| Competitor | Their position | Our angle against them |
|---|---|---|
| **Ray-Ban Meta Gen 2 / Oakley Meta** (EUR 349-549) | Mass-market camera AI glasses, around 70-80% share | We avoid competing on capture. Instead we offer what Meta cannot: no camera, no Meta data practices, and no LED controversy. The LED reportedly stays off in some AI modes. |
| **Meta Ray-Ban Display** (EUR price unconfirmed) | Premium display glasses for early adopters, with features rolling out later in Germany | We lead with use cases that are mature in German from launch, no camera, and an optician-led prescription fit. |
| **Even Realities G2** (from about EUR 699, no camera) | **The closest direct competitor.** Discreet, privacy-friendly glasses for professionals | Even Realities has "limited AI features" and is a small company. We beat them on depth of German subtitle and translation quality, the explicit accessibility focus, and documented EU-hosted, GDPR-ready data handling. **Risk:** they hold the camera-free story first, so we must out-execute them on use-case quality rather than just claim the same privacy story. |
| **Rokid Glasses / AI Glasses Neo** (EUR 699 / 449) | Chinese challenger, multi-LLM, translation in 89 languages, prescription lenses up to ±15 dpt | We cannot win on language breadth, so we win on trust: EU data processing, no camera, and German-language depth. Rokid has low brand awareness in Germany and faces trust issues over Chinese data processing. |
| **Samsung/Google Android XR, Apple (2027 rumour)** | Not yet in the EU | This is our time window. We need to establish optician distribution and a privacy reputation before they arrive. |

### Pricing guidance
- Display glasses in Germany sell for about EUR 450-700 (Rokid, Even), and IDC says there is little room for higher hardware margins.
- We should therefore price **at or below Even G2 (about EUR 699)**, with prescription lenses priced separately through the optician.
- Information insufficient: our bill of materials, the margins opticians expect, and possible insurance reimbursement are all unknown. Final pricing needs further research.

---

## 4. Go-To-Market Plan (GTM)

### Phase 0: Compliance and proof of trust (before launch)
- **Product compliance:**
  - CE marking under RED, including the EN 18031 cybersecurity standards
  - GPSR, RoHS/REACH, battery rules and USB-C
  - Registration with stiftung ear (ElektroG) and LUCID (VerpackG)
  - Preparation for CRA vulnerability reporting
- **Data protection:**
  - A DPIA under Art. 35 GDPR
  - Clarifying our controller role in line with the EDPB statement
  - A legal opinion on § 201 StGB for live transcription
  - Meeting EU Data Act requirements for user data access
- **AI Act:** No facial recognition, voice identification of third parties or emotion recognition.
- **Trust assets:**
  - A public privacy whitepaper
  - Ideally, an independent audit or review, used as the main sales argument with opticians and the press
- **Research to close open gaps:**
  1. Health-insurance reimbursement for hearing-support use
  2. Segment sizes
  3. German market volume from GfK/NIQ or Statista
  4. Optician margin expectations

### Phase 1: Optician-led launch (first 6-12 months)
- **Channel:** Independent opticians first, especially those with hearing-aid or audiology services. Run a small, controlled pilot network with in-store fitting and demo units.
- **Optician chains:** Approach Fielmann, Apollo and Mister Spex in parallel.
  - **Pitch:** "A smart-glasses category you can sell without legal exposure." All three chains are named in the HateAid complaint, and Fielmann and Apollo received the Big Brother Award, so they have a concrete reason to want a lower-risk product in the category.
- **Content marketing (German-language):**
  - Demonstration videos of real conversations with subtitles
  - Explainers on why our glasses contain no camera
  - Outreach to hearing-loss and accessibility communities and media
  - Earned media in tech outlets that already cover the category intensively, such as heise and t3n, through a privacy-led story
- **Success signals to track:** Optician sell-through and reorders, return rate, satisfaction with German transcription accuracy, and press sentiment on privacy. Specific numeric targets cannot be set from the report.

### Phase 2: Scale retail and add the translation segment (about 12-24 months)
- **Channels:** Expand to electronics retail and online: MediaMarkt/Saturn, Galaxus and Amazon.de. Promote translation to business travellers and professionals.
- **Timing:** Aim to have a stable distribution footprint before Samsung/Google's EU launch and Apple's rumoured 2027 entry.
- **Partnerships:** Explore partners for the translation use case, such as trade-fair and business-travel partners. Information insufficient: specific partners are not identified in the report.

### Phase 3 (option): Enterprise pilots in the Mittelstand
- **Use cases:** A camera-free display fits step-by-step instructions, checklists and documentation. Remote expert support usually needs a camera.
  - **Option:** An enterprise-only variant with a camera, sold only under a works agreement, with an indicator that cannot be disabled and with no emotion recognition. We decide this only after the consumer brand is established, so it does not dilute the core promise.
- **Entry routes:**
  - The Mittelstand-Digital successor network for free demos and pilots
  - State SME digitalisation funds such as Bavaria's Digitalbonus (runs to 2027) and Saarland's DigitalInvest (up to EUR 20,000), with eligibility decided case by case
  - A software partnership with TeamViewer Frontline
- **Gap:** Information insufficient: German enterprise adoption rates for 2025/26 are not public, so ROI evidence from pilots is required before investing at scale.

### Key risks to monitor
1. **§ 201 StGB and GDPR exposure of microphone processing.** Mitigate with no storage, on-device processing and a listening indicator.
2. **Even Realities moving into German-language subtitles.** Mitigate by speeding up optician exclusivity and building German-language quality.
3. **Meta price pressure on the whole category.** Mitigate by staying out of the camera/lifestyle segment and competing on need and trust.
4. **The category cool-down IDC reports.** Mitigate with a need-based segment and lean pilot phases.
