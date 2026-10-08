# 03 · Consistency audit

Step 3. Every pair of statements in the response that could conflict, checked against the rows of [02-decisions.md](02-decisions.md). Prepared 2026-09-30.

**How to read it.**

- Each conflict (K1, K2, …) quotes both sides word for word from the response, with line numbers (L…) and the matching rows (D…). Then it gives the clash in one sentence and two ways to resolve it.
- **The two resolutions are PROPOSALS from this audit, not recommendations.** Every conflict is **OPEN (Javeline decides)**. Nothing has been resolved here, and 02-decisions.md has not been changed.
- Values stay in 02-decisions.md. Where a quote contains a number, the row it belongs to is given.
- "Draft 3" means `NAOMS-Kitestring-PSLP-draft3-2026-09-25.pdf`, cited only where the response adopts part of it ("should stay as drawn", "as proposed").
- The pairs that were tested and found consistent are listed at the end, so it's clear they were checked.

**Summary: 32 conflicts.**

| Test | Conflicts |
|---|---|
| 1. Musts against the absolute minimum and the cut list | K1, K2, K3, K4 |
| 2. Must-nots against every mechanism | K5, K6, K7, K8 |
| 3. Priority order against build order | K9, K10, K11 |
| 4. "No standing seat for me" against personal powers | K12, K13, K14, K15, K16 |
| 5. "Recorded with no typing" against how sessions are recorded | K2 (above), K17 |
| 6. Evidence discipline against imported history | K18, K19 |
| 7. Network dashboard and other numbers against the trust wire | K20, K21, K22 |
| 8. Other conflicts found in step 2 | K23–K32 |

---

## 1. Musts against the absolute minimum and the cut list

### K1 · Must 2 (trust wire) is cut by the minimum · was C1

**DECIDED 2026-10-06 (Javeline):** a Must with a deadline. Not needed for the one-community pilot; required before a second community's seals are recognised and before the hatch closes. See D125, D157 in 02-decisions.md.

- **Side A** (Must 2, L333, D125): "Credentials become trust edges (the §07 wire)." Also L293: "M0 first, in parallel with M1."
- **Side B** (cut list, L380, D138): "Trust wire (M0) | One community needs no trust between communities | A second community certifies". Also L391: "it is simply off Certified Practitioner's critical path."
- **Clash:** a Must cannot also be off the critical path, and the list itself says "anything not on these lists is negotiable" (L328), so Musts are the part that is not negotiable.
- **Resolution 1:** keep M0 as a Must, but state its trigger: it must ship before a second community seals, and the one-group pilot runs without it. Must 2 and the cut row then say the same thing.
- **Resolution 2:** move M0 off the Musts list into the cut list for good, and add a Must-not in its place: "Never let a seal cross communities before the trust wire ships."

### K2 · Must 1 (no typing) against how the minimum records a session · was C2

**DECIDED 2026-10-06 (Javeline):** resolution 2 for K2 and resolution 1 for K17. Must 1 now reads "no one has to type a record". See D124.

- **Side A** (Must 1, L332, D124): "A real session is recorded with no typing and co-signed by gossip." Also L292: "Nobody types a record."
- **Side B** (minimum, L371, D137): "Pick the cards played from a list; name the designer, deliverer and players; attach photos of the traces; RoTI; co-signed by Positive Gossip". And the cut list (L381, D138): "Camera card recognition and the voice-built brief | Picking cards from a list works".
- **Clash:** without camera and voice, picking cards from a list and naming the designer, deliverer and players is manual data entry, so the minimum does not meet Must 1.
- **Resolution 1:** keep camera recognition and the voice-built brief in the pilot, so Must 1 holds from the first recorded session.
- **Resolution 2:** reword Must 1 so the pilot is a stated exception, for example "no free-text typing: picking and tapping are allowed in the pilot", and keep the current add-back trigger ("the pilot shows recording is too slow").

### K3 · Must 5 (money through the app) is deferred by the minimum · was C9

**DECIDED 2026-10-06 (Javeline):** resolution 1, with diplomas ("certificates of practice") as the one paid path. See D128. Consequences: the signers for diploma money (Q24) and the euro-rail dependency must be settled before the pilot.

- **Side A** (Must 5, L336, D128): "A paid session or a diploma runs through the app, and every flow of its money is visible." Build order (L356, D134) puts diplomas in M3.
- **Side B** (cut list, L383–385, D138): "Marketplace, billing and levies | … | Certification is trusted", "Flow-funding software | Run the experiment by hand, in the open, while revenue is small" and "Diplomas | The sealed credential is enough | Employers ask for paper".
- **Clash:** with billing and diplomas both deferred, nothing can "run through the app", so the minimum cannot meet Must 5.
- **Resolution 1:** keep one paid path in the minimum (for example diplomas only, or opt-in billing for one paid session), with its flows published, so Must 5 is met.
- **Resolution 2:** mark Must 5 as a Must for a later milestone (M3 or M5), and say plainly that the minimum meets Musts 1–4 and 6 only. Mujo's feedback asks for exactly this statement if a Must waits.

### K4 · The pilot must prove four things, but the build order builds two of them after the pilot

**DECIDED 2026-10-06 (Javeline):** resolution 2, adjusted. Pilot 1: recording, reputation, sealing and certificates of practice. Pilot 2: wiki and online course. See D158.

- **Side A** (minimum, L366, D137): "Certified Practitioner is my deck and archive plus four things: a trustworthy record of practice, reputation computed from it, certification sealed by a user group, and a wiki that writes its own course. Everything else waits until the pilot proves those four work."
- **Side B** (build order, L355–357, D134): the pilot is step 3; "M3 · Practice and certification, with the shared rubric, the computed ladder…" is step 4, and "M4 · The commons, with … the wiki-to-course pipeline…" is step 5.
- **Clash:** the pilot cannot prove computed reputation, sealing or the self-writing course, because the build order builds them after it.
- **Resolution 1:** move the pilot after M4 (or after a thin slice of M3 and M4), so it tests all four things the minimum names.
- **Resolution 2:** split the pilot in two: pilot 1 after M2 proves recording only, and pilot 2 after M4 proves reputation, sealing and the course. Reword L366 to say which pilot proves which thing.

---

## 2. Must-nots against every mechanism

### K5 · "Never sell the claim" against a training fee that includes certification

**DECIDED 2026-10-06 (Javeline):** Resolution 1. "Includes certification" dropped; a training fee pays for learning and practice only, and the certificate is earned from the record and bought separately (D71, D69, D162).

- **Side A** (Must-not, L341, D72): "Never sell the claim; only learning, practice and the reading of an earned record." And L89 (D32): "certifying a record is always free."
- **Side B** (L155, D71): "A training's fee includes certification, so every training sends money to the commons."
- **Clash:** if certification is included in a paid training fee, the buyer pays for a package that includes the certification, which reads as paying for the claim when certifying is meant to be free.
- **Resolution 1:** drop "includes certification". A training fee pays for learning and practice only, and money reaches the commons through the levy (D76) or the diploma, not through certification.
- **Resolution 2:** keep the bundle, but define it so it cannot buy a seal: the fee covers the training and the chance to be assessed, and a user group can still say "not yet" with no refund of the certification part (because there isn't one).

### K6 · "Never pay for recruiting" against mechanisms that reward bringing people in

**DECIDED 2026-10-06 (Javeline):** Resolution 1. Payment follows use in a co-signed session, never headcount; adoption and lineage carry recognition and phase only (D168).

- **Side A** (Must-not, L342, D130): "Never pay anyone for recruiting someone else." And L206 (D93): "No one earns from signing up someone else. … it has to hold in code."
- **Side B**, three mechanisms:
  - L72 (D18): "my deck becomes an offering others can adopt as their home deck, with use in their sessions crediting me through the flow."
  - L88 (D28): the top ecocycle stage is "Creative Destruction (enabled someone else to host it)". L310 (D114): "'Learned from' lineage edges are a natural source of trust edges".
  - L186 (D84): "anything more flows on to the people they appreciate."
- **Clash:** each of these pays or ranks someone more when others adopt their deck, learn from them, or appreciate them, and the response has no checkable rule that separates this from paying for recruitment.
- **Resolution 1:** write the line precisely: payment follows use of a contribution in a co-signed session (D50), never the number of people adopted, taught or appreciated. Home-deck adoption and lineage then count for recognition and phase but carry no money.
- **Resolution 2:** allow these rewards but cap them: one level only (no payment from people your adopters or learners bring in), and a limit on how much of a recipient's inflow can come from their own lineage. The cap is a new row in 02-decisions.md.

### K7 · "No share for the deck author outside what the commons decides" against hatch rules written by the deck author

**DECIDED 2026-10-06 (Javeline):** A variant of resolution 2. The commons vote that starts flow funding (D165) also adopts the flow rules, and Javeline abstains; no money flows before it (D169).

- **Side A** (Must-not, L343, D130): "Never take a share for the platform or the deck author outside what the commons decides."
- **Side B:**
  - L351 (D131): "Parameters in this document (the flow-funding experiment, the founding oligarchy, the levy rates) are starting values, not decisions." These run for the hatch.
  - L72 (D18): deck adoption credits the deck author.
  - L133 (D58): "The Liberating Structures website and my existing videos populate the first version". L135 (D59): "content a course uses counts as use for its authors."
- **Clash:** during the hatch, the flow rules that pay the deck author (through deck adoption and the course seed) come from the deck author's document, not from anything the commons has decided.
- **Resolution 1:** during the hatch, let content by the deck author earn recognition but no money until the commons confirms the flow rules. Payouts to the author start after the parameters conversation.
- **Resolution 2:** have the starting parameters ratified at the start of the hatch by the founding sealers or the pilot user group, so the commons has decided before any money flows. The deck author abstains from that vote.

### K8 · "Never show a number the trust wire cannot yet support" against the witness picture kept from draft 3

**DECIDED 2026-10-06 (Javeline):** Resolution 1. Screen 8 shows pilot-community witnesses and says wider diversity is not yet measured (D173).

- **Side A** (Must-not, L344, D130): "Never show a number the trust wire cannot yet support."
- **Side B** (L289): "The recording layer is right and should stay as drawn: screens 1–9, A–C and S1–S8." Draft 3's screen 8 shows witnesses "from 3 communities" and a Boundary Spanner picture, and draft 3's build 9 "needs the §07 wire for trust distance". With M0 cut (L380), screen 8 would show those numbers without the wire.
- **Clash:** keeping screen 8 as drawn while cutting M0 means showing a witness-diversity number the trust wire cannot yet support.
- **Resolution 1:** keep screen 8 but, until M0 ships, show only same-community witnesses and say plainly that cross-community diversity is not yet measured, as L232 already asks of the dashboard.
- **Resolution 2:** leave screen 8's witness picture out of the minimum and bring it back with M0, keeping only the ladder (change 6) in the pilot.

---

## 3. Priority order against build order

The ranking "says what we protect when they compete for build time" (L37, D7).

### K9 · Diplomas (Priority 3, marketplace) are built before the commons (Priority 2)

**DECIDED 2026-10-06 (by Javeline's Q3 and Q4 answers):** Resolution 2 in effect. Certificates of practice are the one paid path in the minimum and ship in pilot 1 (D128, D158), so they belong with Priority 1, not the marketplace. Closed by Claude from those answers; Javeline can reopen it.

- **Side A** (L32–33, D6): "2. A knowledge commons and the automatic course." ranks above "3. A marketplace." Diplomas are listed under Priority 3 (L155, D66).
- **Side B** (build order, L356, D134): "M3 · Practice and certification, with … session tiers, and diplomas." M3 comes before "M4 · The commons".
- **Clash:** diplomas are a Priority 3 product built one milestone ahead of Priority 2.
- **Resolution 1:** move diplomas to M5 with the rest of the marketplace, so the build follows the ranking.
- **Resolution 2:** reclassify diplomas as part of Priority 1 (certified practice), since the diploma is the formal output of a seal, and say so in Priority 3's list.

### K10 · The network dashboard (Priority 4) is built before the marketplace (Priority 3)

**DECIDED 2026-10-06 (Javeline):** Resolution 2. The ranking governs what is protected when build time is short, not build order (D174).

- **Side A** (L33–34, D6): "3. A marketplace." ranks above "4. The network sees itself."
- **Side B** (L357–358, D134): M4 includes "the network dashboard"; "M5 · A living, with opt-in billing, the levy, and the flow-funding experiment" comes after.
- **Clash:** the Priority 4 dashboard is built one milestone ahead of Priority 3 billing.
- **Resolution 1:** move the dashboard to after M5 (or to its own milestone), keeping only the "plain list of sessions and user groups" (L387) in M4.
- **Resolution 2:** state that the ranking governs what is protected when build time is short, not the order things are built, and say the dashboard goes in M4 because it is cheap once the commons exists.

### K11 · The must-have (home deck, archive) sits outside the ranking but is built first

**DECIDED 2026-10-06 (Javeline):** Resolution 1. The home deck and archive import are Priority 0, above certified practice (D175).

- **Side A** (L29, D6): "Five goals, in priority order", with certified practice first.
- **Side B** (L41, D10): "This is non-negotiable for me as the first practitioner on the platform". L353 (D134): M1 includes "my deck first, my imported archive". L366 (D137): "Certified Practitioner is my deck and archive plus four things".
- **Clash:** the home deck and archive import are not among the five ranked goals, yet they are non-negotiable and built before Priority 1, so the ranking does not say what wins if they compete with certification for build time.
- **Resolution 1:** rank the must-have explicitly as Priority 0, above certified practice.
- **Resolution 2:** fold the home deck into Priority 1 (as part of recording practice) and the archive import into the hatch work, and say which parts can slip if certification needs the build time.

---

## 4. "No standing seat for me" against every place Javeline personally chooses, invites, approves or holds a veto

Side A is the same for K12–K16: "No standing seat for me" (L401, D35), together with the Must-not "Never take a share for the platform or the deck author outside what the commons decides" (L343) and "its rules change only by the commons" (L208, D95).

### K12 · Javeline invites the founding sealers, with no limit or end · was C3

**DECIDED 2026-10-06 (Javeline):** resolution 2. The pilot user group's stewards invite the founding sealers; Javeline is one nominee. See D33.

- **Side B** (L90, D33): "sealing is an honest oligarchy: user groups and people with established reputation in the community, invited by me through an invitation flow in the app." L355 (D136): "with founding sealers I invite."
- **Clash:** choosing who may seal is a standing gatekeeping power over sealing, and the response gives it no quorum, co-signers or end date.
- **Resolution 1:** name the role ("founding inviter"), require co-signature by at least one other founding sealer for each invitation, end it at a fixed date or at the parameters conversation, and let the founding sealers revoke it.
- **Resolution 2:** remove the personal power: the pilot user group's stewards invite the founding sealers from the start, and Javeline is one nominee among others.

### K13 · Javeline chooses the pilot community and the next candidate

**DECIDED 2026-10-06 (Javeline):** Neither resolution as written. Pilot 1 starts with LS Go Online and the Wise Crowds Design Call together; later communities join by open invitation (D136). Each group joins because its stewards agree, with no member vote (Q48, 2026-10-06).

- **Side B** (L355, D136): "starting with the Wise Crowds Design Call as the most frequent channel, with founding sealers I invite. The LS Go Online user group is the next candidate."
- **Clash:** where certification first runs, and who seals there, is set by one person, which shapes whose practice gets certified first.
- **Resolution 1:** keep the choice as a one-off operational decision, but state it as such and make the second community's entry an open invitation any user group can answer.
- **Resolution 2:** have the pilot community confirm its own participation and its own founding sealers, so Javeline proposes and the group decides.

### K14 · Javeline decides how the automatic course is reviewed and co-decides which cards are accepted

**DECIDED 2026-10-06 (Javeline):** Resolution 1. Course review and card acceptance go to the commons; the official course is a distillation by community up-votes; Javeline is an ordinary contributor (D60, D151). Curated collections are encouraged alongside it (D57).

- **Side B** (open design spaces, L420, D60): "Who reviews the automatic course? | Automatic by default, with a way to flag errors … | Jeremy". L419 (D151): "How is a new card or structure accepted, credited and printed? | … | Jeremy and the commons".
- **Clash:** the official course carries the certification's name and pays its authors, and card acceptance affects what counts toward the ladder (D27), so a personal say over both is a standing seat outside sealing.
- **Resolution 1:** hand both to the commons: course review and card acceptance follow the same community evaluation as the wiki, and Javeline is an ordinary contributor.
- **Resolution 2:** keep Javeline as the initial owner for the hatch only, with decisions published and reversible by the founding sealers, ending at the parameters conversation.

### K15 · Javeline's deck and videos are the default seed, beside the core

**DECIDED 2026-10-06 (Javeline):** Resolution 1. A labelled hatch seed; other practitioners add theirs from day one; all ranked by up-votes (D58).

- **Side B** (L113, D45): "the 43 core Liberating Structures as published; my deck, offered as one community set among many". L133 (D58): "The Liberating Structures website and my existing videos populate the first version". L357: "the wiki-to-course pipeline seeded from the website and my videos".
- **Clash:** at launch Javeline's deck is the only named community set beside the core, and Javeline's videos are the only personal seed for the official course, so "one set among many" is, at first, one set.
- **Resolution 1:** keep the seed, but label it as a hatch seed and open the same slot to other practitioners' decks and videos from day one, ordered by the community's votes.
- **Resolution 2:** seed the official course from the Liberating Structures website only, and offer Javeline's deck and videos as a curated course (D57) and a community set, like any other practitioner's.

### K16 · Javeline sets the hatch parameters and settles three questions privately with Mujo

**DECIDED 2026-10-06 (Javeline, by Q10–Q13):** the hatch has an end (D132); the pilot group confirms the starting values, with Javeline abstaining (D170); the commons judges the experiment (D171); the refund rule is drafted by Javeline and Mujo and confirmed by the pilot group (D121). Line added in step 6.

- **Side B** (L351, D131–D132): "Parameters in this document (the flow-funding experiment, the founding oligarchy, the levy rates) are starting values … The hatch lasts at least 13 months". L409 (D121): "Questions 3, 6 and 10 stay open; I would rather settle them with you after the pilot." Nothing says who decides when the hatch ends, or who declares the experiment "wrong" and triggers the fallback (L202, D92).
- **Clash:** for at least the length of the hatch, the money and sealing rules are the ones Javeline wrote, and the currency, refund and co-design questions are settled by Javeline and Mujo, not the commons (D95).
- **Resolution 1:** state who ends the hatch and who judges the experiment (for example, the founding sealers by quorum), and bring questions 3, 6 and 10 to the pilot community rather than settling them bilaterally.
- **Resolution 2:** keep the author-set starting values, but give them a hard end date and a right for the pilot community to change any of them before then by a stated quorum.

---

## 5. "Recorded with no typing" against how the minimum records a session

K2 above covers the minimum's list-picking. One more clash:

### K17 · Must 1 (no typing) against the tap-and-type path the response keeps from draft 3

**DECIDED 2026-10-06 (Javeline):** resolution 2 for K2 and resolution 1 for K17. Must 1 now reads "no one has to type a record". See D124.

- **Side A** (Must 1, L332, D124): "A real session is recorded with no typing".
- **Side B** (L353, D134): "M0 · Trust wire and M1 · Play and record, in parallel, as proposed." Draft 3's M1 includes build item 15, "An equal path without voice: tap and type for every voice step", which exists so that deaf and speech-impaired players are not excluded.
- **Clash:** a Must that forbids typing contradicts the accessibility path the response adopts, which records by typing.
- **Resolution 1:** reword Must 1 as "no one has to type a record", so typing stays available as the equal path but is never required.
- **Resolution 2:** keep "no typing" literally, and make the equal path tap-only (pick lists, icons, gestures) with no free text.

---

## 6. The evidence discipline against imported, un-co-signed history

### K18 · Imported sessions against a phase and a seal computed from records · was C4

**DECIDED 2026-10-06 (Javeline):** neither resolution as written. Under the evidence principle (D161), imported sessions count as claims and are shown at their evidence level. See D20.

- **Side A** (L73, D20): "Past sessions are marked 'imported, not co-signed' until someone who was there co-signs." Also L294: "Positive Gossip as the co-signature". And L90 (D34): "no seal without a robust record."
- **Side B** (L88, D28–D30): "Computed, not filled in. … The app's records show which stage applies." L373 (D137): "Each person's ecocycle stage per pattern, and their phase, computed from records". L351 (D131): the hatch is "catching up with the current reality of the practice, largely by hand, to populate the system."
- **Clash:** the response never says whether imported, un-co-signed sessions count toward someone's stage, phase or seal, and the hatch depends on them to populate the system.
- **Resolution 1:** imported sessions never count until co-signed. Everyone's phase starts from co-signed records only, and imported history is shown beside it as context.
- **Resolution 2:** imported sessions count, visibly marked, for the phase shown to the practitioner, but a seal needs a set minimum of co-signed records. That minimum becomes a new row in 02-decisions.md.

### K19 · Founding sealers qualify by "established reputation", not by records

**DECIDED 2026-10-06 (Javeline):** closed by Q5, Q6 and Q6b. Sealers are user groups (D31) invited by the pilot group's stewards (D33), so no individual qualifies by reputation alone.

- **Side A** (L88, D30): "Computed, not filled in." And L85: "One shared rubric."
- **Side B** (L90, D33): "user groups and people with established reputation in the community". L401: "people with established reputation in the community".
- **Clash:** the people who apply the rubric during the hatch are chosen by a reputation that exists outside the records and the rubric.
- **Resolution 1:** accept this openly as the hatch's bootstrap exception: name it in the document, list the founding sealers publicly, and end it at the parameters conversation.
- **Resolution 2:** have founding sealers qualify through the same records: each must reach a set phase from co-signed or imported-then-co-signed sessions before sealing. That phase becomes a new row in 02-decisions.md.

---

## 7. The network dashboard and other numbers against the trust wire (M0)

### K20 · The whole dashboard is community-wide, but anything that crosses communities must wait for M0

**DECIDED 2026-10-06 (Javeline):** Resolution 1. Per-community numbers, labelled "self-reported, not yet cross-verified"; pilot-community numbers shown as normal (D173).

- **Side A** (L219, D100): "where the practice is active, which user groups are running, which structures are used for which problems, what is trending, where it is being invited in, and where the leading edge is growing." L387 (D138): "A plain list of sessions and user groups falls out of the records".
- **Side B** (L232, D102): "Witness diversity and anything that crosses communities cannot be measured until the trust wire (M0) ships." Must-not, L344: "Never show a number the trust wire cannot yet support." M0 is cut from the minimum (L380).
- **Clash:** almost every dashboard question aggregates across user groups, which L232 says cannot be measured before M0, and the minimum cuts M0.
- **Resolution 1:** until M0 ships, show only per-community numbers, plus totals marked "self-reported by each community, not cross-verified".
- **Resolution 2:** make M0 a prerequisite of the dashboard: move the dashboard after M0, and keep M0 in the build order ahead of M4 even if it stays out of the pilot.

### K21 · Flow funding pays across communities on evidence M0 cannot yet support

**DECIDED 2026-10-06 (Javeline):** Resolution 2, adapted. One pool; until the trust wire ships, sessions from communities outside the pilot community count for appreciation only, not use (D172).

- **Side A** (Must-not, L344): "Never show a number the trust wire cannot yet support." L232: "anything that crosses communities cannot be measured until the trust wire (M0) ships."
- **Side B** (L183, D80): "use (a card, string or tip earns when it is used in a co-signed session)". L181 (D79): one flow with one common pool. L208 (D95): "Every flow is shown in the open". L384 (D138): flow funding is run "by hand, in the open" in the minimum, where M0 is cut.
- **Clash:** a single pool paying on co-signed use from any community is a cross-community number, published and paid in money, before the trust wire that would show whether those co-signatures come from a closed circle.
- **Resolution 1:** run the flow experiment per community until M0 ships: each user group's pool pays only on its own co-signed sessions, and a shared pool starts after M0.
- **Resolution 2:** keep one pool, but count "use" only from sessions with witnesses from at least a set number of distinct communities once M0 ships, and pay "appreciation" only until then. The number becomes a row in 02-decisions.md.

### K22 · Which seals a charter trusts, against the honest floor before M0

**DECIDED 2026-10-06 (Javeline, by Q29):** no charter recognises another community's seal before the trust wire ships (D157). Line added in step 6.

- **Side A** (L322, D122): "Until the trust wire ships, yes-or-no recognition between communities is the honest floor."
- **Side B** (change 4, L308, D112): "The charter sets who seals, the quorum, the diploma fee, and which seals it trusts". L380: M0 is cut until "A second community certifies".
- **Clash:** they are consistent only if "which seals it trusts" means yes-or-no recognition, and the response doesn't say so; a charter trusting a seal with weights or distances would need M0.
- **Resolution 1:** state that before M0 a charter's trust in another seal is yes-or-no only.
- **Resolution 2:** state that no charter recognizes another community's seal until M0 ships, matching the cut row's trigger.

---

## 8. Other conflicts found in step 2

### K23 · Two designers: question 10 open, change 7 answers it · was C5

**DECIDED 2026-10-06 (Javeline):** Resolution 1. Question 10 closed; everyone on a design team is credited as co-designer, equally by default (D115).

- **Side A** (L409, D121): "Questions 3, 6 and 10 stay open". Draft 3 question 10 asks: "Can a record have two designers?"
- **Side B** (change 7, L311, D115): "Design and delivery are distinct but usually the same person, so nest them: credit both by default, and split only when someone delivers another's design."
- **Clash:** change 7 answers how credit is split between design and delivery, while question 10 is listed as still open.
- **Resolution 1:** close question 10 with change 7, and say two designers of one design are credited the same way as a split.
- **Resolution 2:** keep question 10 open, but narrow it to what change 7 leaves unanswered: co-designers of the same design, as opposed to one designer and one deliverer.

### K24 · Diploma fee: one figure, or set per charter · was C6

**DECIDED 2026-10-06 (Javeline):** Resolution 1. One fee across Certified Practitioner, €100 during the hatch, changed only by the commons; "the diploma fee" is dropped from what a charter sets (D69, D112).

- **Side A** (L155, D69): "the certificate costs a fee (about €100 during the hatch)".
- **Side B** (change 4, L308, D112): "The charter sets who seals, the quorum, the diploma fee, and which seals it trusts".
- **Clash:** the diploma fee is both a single figure and something each charter sets.
- **Resolution 1:** one fee across Certified Practitioner (the diploma is signed by Certified Practitioner, L155), and drop "the diploma fee" from what a charter sets.
- **Resolution 2:** each charter sets its own diploma fee, and the single figure becomes a suggested default for the hatch.

### K25 · Diplomas and courses: commons products or levied · was C7

**DECIDED 2026-10-06 (Javeline):** Resolution 1. Diplomas and courses are commons products and their full price enters the pool; the levy applies to paid sessions and hiring only (D76).

- **Side A** (L171–172, D74): "Courses | Commons product" and "Diplomas | Commons product".
- **Side B** (change 2, L306, D76): "Add a levy on diplomas, paid sessions, hiring and courses, feeding the flow."
- **Clash:** a commons product's whole price is revenue for the flow, while a levy is a share of someone else's price, so it is unclear whether diploma and course revenue goes to the flow in full or only in part.
- **Resolution 1:** diplomas and courses are commons products and their full price enters the flow; the levy applies to paid sessions and hiring only.
- **Resolution 2:** diplomas and courses are levied: the levy enters the flow and the rest goes to named parties (for example, the signing peers or the course's authors), who must then be listed.

### K26 · Every training sends money to the commons, but levies only apply to billing through the app · was C8

**DECIDED 2026-10-06 (Javeline):** Resolution 1. L155 narrowed to "every training billed through the app sends money to the commons" (D71).

- **Side A** (L155, D71): "every training sends money to the commons."
- **Side B** (L174, D75): "A levy, only when a practitioner or user group lets the app handle billing". L177 (D77): "A practitioner's own fee for their work stays theirs."
- **Clash:** a training billed outside the app pays no levy, so not every training sends money to the commons.
- **Resolution 1:** narrow L155 to "every training billed through the app sends money to the commons".
- **Resolution 2:** make a contribution to the commons a condition of a training carrying the "immersion workshop" or "certified practice" tier, whoever bills it.

### K27 · One flow for all revenue, but each community sets its own session splits · was C11

**DECIDED 2026-10-06 (Javeline):** Resolution 1. A community's split applies to its own session income, shared by Happy Money Story (D167), and only the levy enters the flow (D97).

- **Side A** (L161, D73): "All revenue is distributed by threshold-based flow funding". L181: "One flow replaces fixed shares." The same answer (L403) says: "No fixed split during the hatch: threshold-based flow funding".
- **Side B** (L403, D97): "Each community sets its own session splits".
- **Clash:** if all revenue goes through one flow and a practitioner's fee stays theirs, it is unclear what a community's session split divides.
- **Resolution 1:** a community's split applies only to its own session income before the levy (for example, shared costs, co-hosts), and only the levy enters the flow.
- **Resolution 2:** drop community session splits during the hatch, and let communities set them after the parameters conversation.

### K28 · Currency: question 3 open, but euros already chosen · was C12

**DECIDED 2026-10-06 (Javeline):** Resolution 1. Euros for certificates and the marketplace; community credit stays open (D98). Refunds are drafted by Javeline and Mujo and confirmed by the pilot group (D121, D170).

- **Side A** (L409, D121): "Questions 3, 6 and 10 stay open". Draft 3 question 3: "Euros through the Monerium rail, community credit, or both?"
- **Side B** (open design spaces, L423, D98): "Euros for the marketplace, once Monerium is enabled".
- **Clash:** question 3 is listed as open while the response already gives euros as the answer for the marketplace.
- **Resolution 1:** close question 3 for the marketplace (euros), and keep it open only for community credit.
- **Resolution 2:** keep question 3 fully open, and mark "euros for the marketplace" as current thinking only.

### K29 · Who may seal: stewards only, or reputable individuals too · was C13

**DECIDED 2026-10-06 (Javeline):** resolution 1. Only user groups seal; reputable individuals take part as stewards within a group. See D31.

- **Side A** (L89, D31): "A user group's stewards attest that the record meets the rubric. Their attestation is the certification".
- **Side B** (L90, D33; L401): "user groups and people with established reputation in the community".
- **Clash:** a seal is a user group's attestation, yet during the hatch individuals with reputation can seal too.
- **Resolution 1:** only user groups seal; reputable individuals take part as stewards within a user group.
- **Resolution 2:** individuals may seal during the hatch, marked as an individual seal distinct from a user group seal, and this ends at the parameters conversation.

### K30 · Milestone numbering · was C14 (open from step 1)

**DECIDED 2026-10-06 (Javeline):** Resolution 1. Keep M0–M5; change 1 is reworded to "money arrives in M5 (A living)".

- **Side A** (L357–358, D134): "M4 · The commons" and "M5 · A living".
- **Side B** (change 1, L305): "An app for Jeremy's deck; money arrives in M4", in draft 3's sense, where M4 is "A living".
- **Clash:** "M4" means two different milestones in the same document.
- **Resolution 1:** keep the response's M0–M5 numbering and reword change 1 to "money arrives in draft 3's M4 (A living)".
- **Resolution 2:** keep draft 3's numbering and give the commons milestone a new label (for example M3b), so M4 always means "A living".

### K31 · Who sets sealers: charters, or the founding oligarchy until the hatch ends · was C15

**DECIDED 2026-10-06 (Javeline):** resolution 2. Charters set who seals from the start of the hatch; the parameters conversation reviews it. See D112, D150.

- **Side A** (change 4, L308, D112): "The charter sets who seals, the quorum, …".
- **Side B** (L90, D33): founding sealers "invited by me". L418 (D150): "How does sealing open up beyond the founding oligarchy? | Decided in the parameters conversation that closes the hatch | The commons".
- **Clash:** charters decide who seals, yet during the hatch the founding oligarchy decides and opening it up waits for the parameters conversation.
- **Resolution 1:** charters set who seals only after the hatch; during the hatch, the founding sealers are the only sealers.
- **Resolution 2:** charters set who seals from the start, and the founding sealers are just the first charter's choice.

### K32 · Hatch length: settled, or a proposal · was C16

**DECIDED 2026-10-06 (Javeline):** Resolution 1, extended: at least 13 months of flow funding from the start vote, closed at the next equinox gathering, with a 2-year maximum from the start of pilot 1 (D132).

- **Side A** (L351, D132): "The hatch lasts at least 13 months, the length of the flow-funding experiment."
- **Side B** (L351): "Parameters in this document … are starting values, not decisions." L194: "The targets are proposals for the hatch, to be confirmed."
- **Clash:** the hatch length is worded as settled, but it is defined by an experiment the response calls a proposal. 02-decisions.md marks it PROPOSAL until Javeline says otherwise.
- **Resolution 1:** mark the minimum hatch length DECIDED, separate from the experiment's other targets.
- **Resolution 2:** mark it PROPOSAL, to be confirmed with the experiment's targets.

---

## Pairs tested and found consistent

| Pair | Why it holds |
|---|---|
| Must 3 (phase computed) against the minimum | The minimum keeps "Reputation: … computed from records" (L373). Whether imported history counts is K18. |
| Must 4 (a user group seals and warmly declines) against the minimum | The minimum keeps sealing by one user group, with "not yet" (L374). Who may seal is K29. |
| Must 6 (Data Wash, votes, self-writing course) against the minimum | The minimum keeps the wiki with publish choices, votes and the automatic course (L375–376). Card versioning and curated courses are deferred, but Must 6 does not need them. Whether the pilot can prove it is K4. |
| Must-not "never hardcode what is specific to Liberating Structures" against deferring white label | Deferring the packaging (L389) does not undo the data-not-code rule (D106). The deck, taxonomy, rubric and vocabulary stay data. |
| Must-not "never take a share for the platform" against revenue | No mechanism pays the platform. Upkeep is the common pool's survival threshold (D82, D85). |
| Priority 1 (certification) against build order | Certification (M3) comes after recording (M0–M2), which it needs. |
| Priority 5 (white label) against build order | It is last (step 8). |
| Data Wash (Priority 2) built in M2, before certification (Priority 1) | It is a small item (D52) that Must 6 needs, and M2 is where privacy is handled. The response places it there on purpose (L354). |
| "Votes never pay" against the course | Votes rank the wiki the course draws on, but payment follows use in co-signed sessions (D49, D50, D59). Whether votes need weighting is for step 5. |
| Home deck first for everyone against "no standing seat" | It is the same right for every practitioner (L52). The one-person seed powers are K15. |
| Guests as witnesses (D119) against the evidence discipline | Guests give feedback through the app, so their witness is a signed act. |
| The dashboard's witness-diversity metric against M0 | L232 already defers it and asks the dashboard to say so. Only the rest of the dashboard conflicts (K20). |
