# 07 · Scope and minimum

Step 7, 2026-10-07. Every feature in "Certified Practitioner — response to Kitestring draft 3" is listed here with five things: its priority, whether it is in the pilot minimum, what it depends on, and when to add it back. A final section checks the minimum against every Must and Must-not.

All values (thresholds, prices, counts) live in [02-decisions.md](02-decisions.md) and are referred to by row, not repeated.

**DECIDED 2026-10-07 (Javeline): this minimum is adopted as laid out.** Every pilot placement and add-back condition below is DECIDED, including those first proposed by Claude. Values and rules that are still PROPOSAL in their own rows of 02-decisions.md (for example D56, D90, D193) stay PROPOSAL; adopting the scope does not settle them.

## How to read it

**Priority** follows the five goals (D6). A feature's priority says what is protected when build time runs short, not the order things are built in (D174). Javeline added **Priority 0** above the five for the home deck and archive (D175). Certificates of practice move from the marketplace (3) to certified practice (1), because they are pilot 1's paid path (D128, K9).

**In the pilot minimum.** There are two pilots (D158), so this column says which one:
- **Pilot 1:** recording, computed reputation, and record-based certificates paid in euros.
- **Pilot 2:** the wiki, the automatic course and the optional seal, built on pilot 1's records.
- **No:** outside both pilots.

The response's "absolute minimum" (D137, D138) is the starting point. Everything it keeps or cuts is shown as written, then changed only where a later decision changed it (D124, D125, D128, D158, D160).

**Add back when** is a condition, not a date:
- Where the response or a decision gives the condition, it is quoted with its row. Those are **DECIDED**, or **PROPOSAL** where D137 and D138 are still proposals.
- Where neither gives one, the condition is Claude's and labelled **PROPOSAL (Claude; Javeline decides)**.
- Where the response gives a milestone (M2, M4) instead of a condition, it is restated as the condition behind that milestone and labelled **PROPOSAL**.

**Pilot placement:**
- Rows marked "Pilot 1" or "Pilot 2" because the response or a decision says so are DECIDED.
- Rows placed by Claude because nothing in the folder places them are **PROPOSAL (Claude)**. The status column says which.
- The whole minimum was adopted by Javeline on 2026-10-07 (D137, D138, L13).

Feature numbers (P0.1, P1.1, …) are used only inside this file.

## Priority 0 · My deck first, my archive in

| # | Feature | Pilot | Depends on | Add back when | Status |
|---|---|---|---|---|---|
| P0.1 | Home deck first wherever cards or content appear, for every practitioner (D10, D11, D14, D15) | Pilot 1 | P5.1 (deck as data) | — | DECIDED (D137) |
| P0.2 | Own card photos as the camera's first reference images (D12) | No | P1.3 (camera recognition) | When camera recognition returns (P1.3) | Follows D124 |
| P0.3 | Own Tips, Traps, Riffs and videos lead in wiki and course views (D13) | Pilot 2 | P2.1, P2.6 | — | Follows D158 |
| P0.4 | Archive import of the practitioner's own cards, designs (strings and briefs) and past sessions as claims at their evidence level (D16, D20) | Pilot 1 | P0.6 (review queue), P1.10 (evidence levels), P2.4 (privacy choice, D205), P5.1 | — | DECIDED (D137). Recordings that show other people stay private (D19), and need a lawful basis to transcribe (06-questions.md, L9) |
| P0.5 | Archive import into the wiki and course: explainer videos, other Google Docs and GoodNotes pages turned into drafted Tips, Traps and Riffs (D16) | Pilot 2 | P0.6, P2.1, P2.4 (Data Wash) | — | PROPOSAL (Claude): the wiki these entries land in is pilot 2 (D158) |
| P0.6 | Review queue: everything imported lands as a proposal to approve, fix or discard (D17) | Pilot 1 | — | — | DECIDED (D17) |
| P0.7 | Others can adopt a practitioner's deck as their home deck; use credits the author (D18) | Pilot 2 | P0.1, P2.3 (card layers). Credit as money needs P3.4 (flow funding) | — | PROPOSAL (Claude). Until flow funding starts, adoption carries recognition only (D168) |

## Priority 1 · Certified practice

| # | Feature | Pilot | Depends on | Add back when | Status |
|---|---|---|---|---|---|
| P1.1 | Record a session: pick the cards played from a list; name the designer, deliverer and players; photos of traces; RoTI; co-signed by Positive Gossip (D124, D53) | Pilot 1 | P5.1 | — | DECIDED (D124, D137) |
| P1.2 | Credits for design and delivery, and co-designers credited equally (D115) | Pilot 1 | P1.1 | — | PROPOSAL (Claude): the ecocycle stages "led" and "hosted" need these credits (D28) |
| P1.3 | Camera card recognition and the voice-built brief | No | P0.2, P1.1 | "The pilot shows recording is too slow" (D124) | DECIDED (D124) |
| P1.4 | Card category and knob settings stored in each record (D107, D110) | Pilot 1 | P1.1, P5.1 | — | Categories: DECIDED (D107). Knobs as optional fields in pilot 1: PROPOSAL (Claude) |
| P1.5 | Question compass as a second way into "find the card" (D109) | No | P1.1 | When picking from the list becomes slow because the deck has grown | PROPOSAL (Claude) |
| P1.6 | Consent: correct, withdraw, or take yourself out of a record | Pilot 1 | P1.1 | — | DECIDED (D137) |
| P1.7 | Player cards and guest web join | No | P1.1 | Response: "M2". Restated as a condition: when sessions regularly include people who don't have the app | PROPOSAL (D138; condition reworded by Claude). Guests count as witnesses, not toward co-signing or pay (D119, D184) |
| P1.8 | A Scribe records evidence for players without a phone; only those who attest count (D202) | Pilot 1 | P1.1 | — | DECIDED (D202) |
| P1.9 | Computed reputation: ecocycle stage per pattern and phase, per evidence level side by side; the other three dimensions as counts (D25, D28–D30) | Pilot 1 | P1.1, P1.2, P1.10 | — | DECIDED (D137, D158) |
| P1.10 | Evidence levels: every claim shown at its level; countable levels and everything that pays computed by fixed rules; AI only suggests (D161, D182) | Pilot 1 | P1.1 | — | DECIDED (D161, D182) |
| P1.11 | One person, one account: only verified members count toward co-signing and pay (D184) | Pilot 1 | NAOMS identity | — | DECIDED (D184). Whether NAOMS supports it: Mujo (L2) |
| P1.12 | Certificate of practice: issued from the computed record, signed by the relevant user groups and the LS Commons, paid in euros (D160, D162, D201) | Pilot 1 | P1.9, P1.11, P1.13, P1.14, the euro rail (L4), the refund rule (D121, L3) | — | DECIDED (D128, D158). Certificate format: Mujo (L8) |
| P1.13 | Common pool under a 2-of-3 signer threshold; it only fills until flow funding starts; every flow is visible (D163, D200, D128) | Pilot 1 | P1.14 | — | DECIDED (D163, D200) |
| P1.14 | Stewards: 3 pilot stewards nominated by Javeline once; any user may request recognition, evaluated at the equinox; unanimous election (D199) | Pilot 1 | — | — | DECIDED (D199) |
| P1.15 | Commons decisions by user groups, signed by stewards (D166); the pilot group confirms starting values (D170) | Pilot 1 | P1.14 | — | DECIDED (D166, D170) |
| P1.16 | Screen 8 witness picture, pilot-community witnesses only, saying wider diversity is not yet measured (D173) | Pilot 1 | P1.9 | — | DECIDED (D173) |
| P1.17 | Optional user-group seal, with the steward floor and a second review after "not yet" (D160, D159) | Pilot 2 | P1.12, P1.14, P1.18 | — | DECIDED (D158, Q7c) |
| P1.18 | OGD Eval on every design, at the depth the giver's phase allows (D113) | Pilot 2 | P1.1, P1.9 | — | PROPOSAL (Claude). The response keeps it in certification so stewards can read it when they seal (D137); sealing is now pilot 2 |
| P1.19 | Phase-tiered RoTI and the maestro window (D117) | No | P1.9 | "Feedback volume grows" (D138) | PROPOSAL (D138) |
| P1.20 | Session tiers on the record: community practice, certified practice, immersion workshop (D42) | No | P1.12, P3.1 | When paid sessions run through the app (P3.1) | PROPOSAL (Claude): tiers price paid sessions, which wait for the marketplace |
| P1.21 | Network pattern cards on sessions and profiles, each with a suggested next move (D198, uses 1 and 2) | No | P1.9, P1.11 | When pilot 1's records are enough to draw a web (Mujo, L49) | PROPOSAL (Claude) |
| P1.22 | Season reflection at the equinox through the network cards (D198, use 3) | No | P1.21 | The first equinox gathering after P1.21 ships | PROPOSAL (Claude) |
| P1.23 | Trust wire (M0): credentials become trust edges (D125) | No | NAOMS (Mujo) | "Before a second community's seals are recognised, and no later than the end of the hatch" (D125). Pilot 1's two groups count as one community (D157) | DECIDED (D125) |

## Priority 2 · The knowledge commons

| # | Feature | Pilot | Depends on | Add back when | Status |
|---|---|---|---|---|---|
| P2.1 | Wiki: Tips, Traps and Riffs per pattern; designs per string; patterns per setting (D44) | Pilot 2 | P1.1, P2.4 | — | DECIDED (D158) |
| P2.2 | Up and down votes rank the wiki; votes never pay; only members with a co-signed record vote (D48, D49, D193) | Pilot 2 | P2.1, P1.11 | — | DECIDED (D48, D49); vote rule D193: PROPOSAL (L27) |
| P2.3 | Card layers side by side: the core, Javeline's deck, community riffs; riffs marked apart from the core assets (D45, D63) | Pilot 2 | P2.1, P5.1 | — | PROPOSAL (Claude): the response puts card submissions in the commons milestone (D134) |
| P2.4 | Data Wash: each contributor chooses per entry to publish attributed, anonymized or withhold, with the permissions behind it, from the first data in (D51, D53, D205) | Pilot 1 | P1.1 | — | DECIDED (D205, 2026-10-07): required from the start of data coming in, including the archive import (P0.4) and the session package (P2.12) |
| P2.5 | Simple card submission and community evaluation (D46, D151) | Pilot 2 | P2.2, P2.3 | — | DECIDED (D46, D151). Acceptance threshold: the commons (L29) |
| P2.6 | Automatic course, distilled by up-votes, seeded from the LS site and Javeline's videos as a labelled hatch seed, sold through the app (D55, D58, D60, D56) | Pilot 2 | P2.1, P2.2, P1.13, the euro rail | — | DECIDED (D158). Price: PROPOSAL (D56, L31) |
| P2.7 | "Play this design": anyone can deliver a design from the wiki (D116) | Pilot 2 | P2.1, P1.2 | — | PROPOSAL (Claude) |
| P2.8 | Removal only for harm, by 3 stewards from different groups, logged and reversible (D180) | Pilot 2 | P2.1, P1.14 | — | PROPOSAL (Claude) on placement; the rule is DECIDED (D180) |
| P2.9 | Card revisions with versions (D47) | No | P2.5 | "The wiki has volume" (D138) | PROPOSAL (D138) |
| P2.10 | Curated courses and collections, whose curators earn as use (D57, D59) | No | P2.1, P2.6. Earning needs P3.4 | "The wiki has volume" (D138) | PROPOSAL (D138) |
| P2.11 | Comparing the automatic course with curated collections (D90 addition) | No | P2.6, P2.10 | When curated courses exist (P2.10) | PROPOSAL (D90) |
| P2.12 | Session package for agents: one download of everyone's permitted notes, transcripts and photos, for example as an MCP server (D65) | Pilot 1 | P1.1, P1.6, P2.4 | — | DECIDED (D139, 2026-10-07; settles C10) |

## Priority 3 · The marketplace

| # | Feature | Pilot | Depends on | Add back when | Status |
|---|---|---|---|---|---|
| P3.1 | Seats in sessions (S1), with tier, price and seats | No | P1.12, P1.20 | "Certification is trusted" (D138) | PROPOSAL (D138) |
| P3.2 | Practitioners for hire (S3, S4) | No | P1.12 | "Certification is trusted" (D138) | PROPOSAL (D138) |
| P3.3 | Opt-in billing and the levy on paid sessions and hiring (D67, D75, D76) | No | P3.1, P3.2, the euro rail. Signers: L37 | "Certification is trusted" (D138). Levy rates: the commons (L36) | PROPOSAL (D138) |
| P3.4 | Flow funding: thresholds, signals, Happy Money Story rounds, equinox settlement (D80–D83, D165, D167) | No | P1.13, P1.15. How records carry appreciation: Mujo (L18) | The pool covers a season of requested survival thresholds, and the next equinox gathering votes to start (D165) | DECIDED (D165) |
| P3.5 | Flow-funding software (automating P3.4) | No | P3.4 | "Revenue justifies automating it"; until then it is run by hand in the open (D138) | PROPOSAL (D138) |
| P3.6 | Equinox grants from the pool (D164, D190) | No | P1.13, P1.14 | When flow funding has started (P3.4), since until then the pool only fills (D163) | PROPOSAL (Claude), reading D163 |
| P3.7 | Fallback to fixed thirds (D92) | No | P3.4 | If the commons judges the experiment wrong (D171) | DECIDED (D171) |
| P3.8 | A forking group's share of the pool (D178) | No | P1.13, P1.15 | When a group forks (D178) | DECIDED (D178) |
| P3.9 | Tokens: a bonding curve on the pool, or a shared token (D99) | No | P3.4 | "The common pool is large enough" (D99) | DECIDED (D99) |

## Priority 4 · The network sees itself

| # | Feature | Pilot | Depends on | Add back when | Status |
|---|---|---|---|---|---|
| P4.1 | A plain list of sessions and user groups, falling out of the records | Pilot 1 | P1.1 | — | PROPOSAL (D138) |
| P4.2 | Public network dashboard with its metrics, per community and labelled until the trust wire (D100, D101, D173) | No | P1.1, P2.4, P1.13. Cross-community figures need P1.23 | Response: "M4". Restated as a condition: once pilot 2's wiki exists, since its "journal activity" metric needs it, and it is cheap once records exist (D174) | PROPOSAL (D138; condition reworded by Claude) |

## Priority 5 · White label

| # | Feature | Pilot | Depends on | Add back when | Status |
|---|---|---|---|---|---|
| P5.1 | Everything specific to Liberating Structures kept as data: deck, taxonomy, rubric, vocabulary (D106) | Pilot 1 | — | — | DECIDED (D106, Must-not) |
| P5.2 | White-label packaging and licences (D103, D104) | No | P5.1, P1.23. Signers: L37 | Response: "Later". Restated as a condition: when another community of practice asks to run it | PROPOSAL (Claude) |
| P5.3 | Open facilitation toolkit, and a collaboration with SessionLab (D105) | No | P5.2 | "Worth exploring later" (D105) | PROPOSAL (D105) |

## The pilot minimum

**Pilot 1:**
- P0.1, P0.4 and P0.6 (home deck first, and the archive import into records with its review queue).
- P1.1, P1.2, P1.4, P1.6 and P1.8 (recording and consent).
- P1.9, P1.10, P1.11 and P1.16 (reputation and evidence).
- P1.12 to P1.15 (certificates, the pool, stewards and commons decisions).
- P2.4 and P2.12 (Data Wash from the first data in, and the session package; D205, D139).
- P4.1 and P5.1.

**Pilot 2** adds:
- P0.3, P0.5 and P0.7.
- P1.17 and P1.18 (the optional seal and OGD Eval).
- P2.1 to P2.3 and P2.5 to P2.8 (the wiki and the automatic course).

## Do the pilots meet every Must?

| Must | Pilot 1 | Pilot 2 | Why that is acceptable |
|---|---|---|---|
| 1 · A real session is recorded and co-signed by gossip, and no one has to type a record (D124) | **Met** by P1.1 | Met | — |
| 2 · Credentials become trust edges (D125) | **Not met** | **Not met** | Javeline decided it is a Must with a deadline (D125): needed before a second community's seals are recognised, and before the hatch closes. Pilot 1's two groups count as one community (D157), and the seal only arrives in pilot 2, within that one community. The pilots never show a cross-community number (D173). The deadline still binds |
| 3 · Phase is computed from records (D126) | **Met** by P1.9 | Met | — |
| 4 · ~~A user group seals~~ | Dropped (D127) | — | Sealing is an optional endorsement (D160), added in pilot 2 |
| 5 · Certificates run through the app, and every flow of their money is visible (D128) | **Met** by P1.12 and P1.13, **only if** the euro rail is on (L4) and the refund rule passes Mujo's check (L3) | Met; courses are added | If Monerium isn't switchable on, pilot 1 can't sell certificates and Must 5 is not met. This is the one Must that depends on something outside the design (06-questions.md, L4) |
| 6 · Contributors choose how entries reach the wiki, votes sort it, and a course generates itself (D129) | **Partly met:** contributors choose from the first data in (P2.4, D205); votes and the course are not in pilot 1 | **Met** by P2.1, P2.2, P2.4 and P2.6 | Javeline split the pilot in two (D158). Pilot 2 is built on pilot 1's records, so the wiki has real content to sort |

**Must-nots in the minimum:**
- **Never sell the claim.** Certificates state the record, not competence, and can be bought only above the minimum phase (D160, D162).
- **Never pay for recruiting.** Nothing pays in pilot 1, since the pool only fills (D163). Flow rules come later (D168, D197).
- **No share outside the commons.** Certificate money goes in full to the pool (D76), under three stewards' keys (D200).
- **Never show a number the trust wire cannot yet support.** Screen 8 shows pilot-community witnesses only (D173).
- **Never hardcode Liberating Structures.** P5.1 is in pilot 1.

**Two things in pilot 1 rest on unconfirmed work:**
- One person per account (P1.11) depends on NAOMS identity (Mujo, L2).
- Signing by the LS Commons is presumed; if it doesn't sign, the user groups sign alone (D201).

## What this changes elsewhere

- **06-questions.md:** L12 is decided (session package in pilot 1, D139). L13 points to this file. L14 (Data Wash sizing) still blocks pilot 1, since Data Wash stays in it (D205).
- **02-decisions.md:** D137 and D138 are DECIDED as laid out here (2026-10-07).
