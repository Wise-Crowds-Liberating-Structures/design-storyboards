# 04 · Power and money check

Step 4. Every mechanism in the response, tested against §03 "How community money and power work on NAOMS" in `NAOMS-Certified-Practitioner-feedback-2026-09-29.pdf` (pages 4–5). §03 is treated as a hard constraint. Prepared 2026-10-06.

**How to read it.**

- Mechanisms are cited by their rows in [02-decisions.md](02-decisions.md) (D…). No values are repeated here.
- Where a failure overlaps a conflict from [03-conflicts.md](03-conflicts.md), the K number is given.
- **Every proposed fix is a PROPOSAL from this check.** Each one is **OPEN (Javeline decides)**. Where a fix needs a number (a quorum, a signer threshold, a date), the number is left blank as "N" so Javeline can set it in 02-decisions.md. The one exception is NAOMS's own floor, quoted below: a money threshold of at least two signers.
- §03 quotes NAOMS design documents that are not in the folder. This check relies on the feedback PDF's quotations of them, not on the documents themselves.

**Summary.** I checked 40 mechanisms. 11 pass all three questions. 29 fail at least one, and the fix table covers them in 26 fixes (F1–F26), since some fixes cover several mechanisms. The failures fall into four groups:

1. **No signers named for money.** The response never says who holds the common pool, who moves flow-funding money, or who signs diplomas or white-label licences.
2. **Personal powers with no sunset or recall.** These are the K12–K16 powers from step 3, plus the hatch itself, which has a minimum length but no end.
3. **"The commons decides" is undefined.** The response never says who votes, with what quorum, or how a decision is recorded and signed.
4. **Exit and fork are mostly unaddressed.** Members can take their records, but the response is silent on taking reputation and seals with them, and on what a forking group may take.

---

## 1. The constraint

From the feedback PDF, §03 (pages 4–5), as quoted there:

| # | NAOMS principle | What it means here |
|---|---|---|
| N1 | "A founder is not different from any other steward … there must be nothing special about the founder." Authority comes from a revocable role. | Javeline's founding powers must be ordinary, revocable steward roles. |
| N2 | "No 'admin' who can rewrite the rules of the hive without going through governance", and no global admin slot. | Every rule and parameter changes only through a recorded, signed governance decision. |
| N3 | "Open-source code with closed governance is still capture." | Nobody holds a single point of control. |
| N4 | "One treasurer alone can neither move the tokens on-chain nor authorise a redeem." A threshold of one is refused as "no multisig at all". | Every pool and treasury is multi-signature, with at least two signers. |
| N5 | Distribution is "rule-based and governed, not captured by whoever holds the keys". | Payouts follow published rules, not whoever runs them. |
| N6 | "The substrate takes no fee and mints nothing for itself." | Matches D85. |
| N7 | You leave "carrying everything", and "anyone with the content can start a new hive from the same chain". | Members can leave with their records and reputation, and groups can fork. |

§03 then lists five consequences for Certified Practitioner (page 5). The hatch needs an end date, a quorum or co-signers, and community revocation. Sealers are revocable stewards with stated admission and removal. Money moves only under a signer threshold. Parameters change only by governance. People can leave and groups can fork. It also quotes NAOMS's flow-funding notes: "self-perpetuating, invitation-only delegation invites collusion", "what recall/exit exists?", and conflict-of-interest rules: "no self/relative/stipend funding".

The three questions from the step:

- **Q1 · Single person?** Can any one person, Javeline included, act alone here to appoint, seal, veto, move money, change rules or set parameters?
- **Q2 · Bounded?** If yes, is it time-limited, bounded by a quorum or signer threshold, and reversible by the community?
- **Q3 · Exit and fork?** Can a member leave with their own records and reputation, and can a group fork if it disagrees?

**Pass** means the response already satisfies the question. **Fail** means it doesn't. **Silent** means the response doesn't say, which counts as a fail under a hard constraint. **n/a** means the question doesn't apply.

---

## 2. Every mechanism, tested

| # | Mechanism | Rows | Q1 Single person? | Q2 Bounded? | Q3 Exit and fork | Result |
|---|---|---|---|---|---|---|
| P1 | Home deck first; votes never reorder your own deck | D10–D15 | Each person over their own view only | n/a | n/a | Pass |
| P2 | Archive import with a review queue | D16–D17 | Each person over their own material | n/a | Own material stays theirs | Pass |
| P3 | Other people's recordings stay private until consent | D19 | No | n/a | n/a | Pass |
| P4 | Deck adoption credits the author through the flow | D18 | No (paid by flow rules) | Depends on flow rules (P19) | Silent: can an author withdraw a deck others adopted? | Fail → F21 |
| P5 | The shared rubric and its thresholds | D22–D25 | Silent: nobody is named who can change the rubric | Silent | Silent: does a phase travel with a member who leaves? | Fail → F1, F20 |
| P6 | Phase computed from records | D28–D30 | No (computed) | n/a | Silent (as P5) | Fail → F20 |
| P7 | Sealing by a user group's stewards | D31, D142 | Silent: quorum not given (D112 leaves it to the charter) | Silent: no rule for admitting or removing a steward | Silent: does a seal survive leaving the group? | Fail → F2, F20 |
| P8 | Founding sealers invited by Javeline | D33, D136, D143 | **Yes**: Javeline appoints alone | **No**: no co-signer, no end beyond "at least" a minimum hatch, no recall | n/a | Fail → F3 (K12) |
| P9 | Founding sealers qualify by "established reputation" | D33 | Yes, through P8 | No | n/a | Fail → F3 (K19) |
| P10 | "Not yet": a seal is declined | D36, D127 | Silent: depends on quorum (P7) | Silent: no appeal or second review | n/a | Fail → F4 |
| P11 | Session price set by the practitioner or user group | D39, D42 | Each over their own work | n/a | n/a | Pass |
| P12 | New cards accepted, credited and printed | D46, D151 | **Yes, partly**: Javeline co-decides with "the commons" | No | n/a | Fail → F5 (K14) |
| P13 | Wiki ranking by up and down votes | D48–D49 | No | n/a | ShareAlike content can be reused (D62, ASSUMPTION) | Pass, but see F6 for removal |
| P14 | Removing or moderating wiki entries and cards | — | Silent: the response never says who can remove content | Silent | n/a | Fail → F6 |
| P15 | Data Wash | D51 | Each over their own entries | n/a | Supports exit | Pass |
| P16 | Automatic course review | D60 | **Yes**: Javeline is the named owner | No | n/a | Fail → F7 (K14) |
| P17 | Course and community-set seed | D45, D58 | **Yes**: Javeline's deck and videos are the seed, chosen by Javeline | No | n/a | Fail → F8 (K15) |
| P18 | Session package for agents | D65 | No: consent-gated (D94) | n/a | Supports exit with records | Pass |
| P19 | "Rules change only by the commons" | D95, D149 | No | **Silent**: who counts as "the commons", the quorum, and how a decision is signed are not defined | n/a | Fail → F9 |
| P20 | Hatch parameters written into the response | D131 | **Yes**: the author set them | Partly: they end with the hatch, but the hatch has no end date (P21) | n/a | Fail → F10 (K16) |
| P21 | Hatch length and end | D132, D133 | Silent: nobody is named to end or extend it | **No**: a minimum, no maximum | n/a | Fail → F11 (K32) |
| P22 | The parameters conversation | D133 | No | Silent: who convenes it, who may vote, the quorum | n/a | Fail → F9 |
| P23 | Opt-in billing through the app | D67, D75 | Silent: who holds billed money between payer and payee? | Silent: no signers | n/a | Fail → F12 |
| P24 | Diplomas: issuing and signing | D68, D70 | Silent: who signs as "Certified Practitioner"? | Silent: no signer threshold | Verifiable credential travels with its holder (D70) | Fail → F13 |
| P25 | Diploma fee | D69, D112 | Silent: set by the response, or per charter (K24) | No governance stated | n/a | Fail → F14 |
| P26 | Levy rates | D76, D78 | Starting values set by the author (D131) | Ends only with the hatch (P21) | n/a | Fail → F10 |
| P27 | Common pool: who holds it | D79, D82 | **Silent**: no keyholders, no threshold | **Silent** | Silent: does a forking group take a share? | Fail → F15, F22 |
| P28 | Flow funding: computing and paying out | D73, D83, D138 | **Yes, by default**: run "by hand" in the minimum, with nobody named | No signers | n/a | Fail → F16 |
| P29 | Self-declared survival and thriving thresholds | D81 | **Yes**: each recipient alone sets the threshold that governs their own payout | No review during the hatch | n/a | Fail → F17 |
| P30 | Overflow to "the people they appreciate" | D84 | **Yes**: each recipient's appreciation directs money | No conflict-of-interest rule | n/a | Fail → F18 |
| P31 | The common pool's own thresholds (protocol upkeep) | D82 | Silent: nobody is named who sets the upkeep figure | Silent | n/a | Fail → F15 |
| P32 | Judging the flow experiment and triggering the fallback | D91, D92 | Silent: nobody is named | Silent | n/a | Fail → F19 (K16) |
| P33 | Platform and Javeline take nothing outside the flow | D85 | No | n/a | n/a | Pass (matches N6) |
| P34 | Charters: who seals, quorum, trusted seals | D112 | No: each community | Depends on P7 | n/a | Pass, subject to F2 |
| P35 | Each community sets its own session splits | D97 | No: each community | Through its charter | n/a | Pass (meaning: K27) |
| P36 | Credits field set by the person giving gossip | D115 | Each giver alone sets design or delivery credit, which changes who earns from "use" | Silent: no rule when givers disagree | n/a | Fail → F23 |
| P37 | Pilot community and next candidate chosen | D136 | **Yes**: Javeline | No | n/a | Fail → F24 (K13) |
| P38 | Draft 3 questions 3, 6 and 10 settled by Javeline and Mujo | D121 | Two people, not the community, decide currency and refund policy | No | n/a | Fail → F25 (K16) |
| P39 | White-label licences and instantiation | D103–D104 | Silent: who decides to license, and who signs? | Silent | Licensing another community is close to an authorised fork | Fail → F26 |
| P40 | Governance follows stewardship, never earnings; tokens out of scope; public dashboard; guests as witnesses; equal evidence; take me out | D87, D99, D100, D96, D119, D137 | No | n/a | Take me out supports exit | Pass |

---

## 3. Failures and proposed fixes

Fix types, as the step asks: **quorum**, **sunset**, **signer threshold**, or **community vote**. "N" marks a value for Javeline to set, which then goes in 02-decisions.md.

| # | Mechanism | Fails | Why | Proposed fix | Type |
|---|---|---|---|---|---|
| F1 | Shared rubric and thresholds (P5) | Q1, Q2 | Nobody is named who may change the rubric or its thresholds, so in practice the author of the document does (N2). | The rubric is changed only by a recorded community vote of all user groups' stewards, with a quorum of N user groups. A change applies to new seals only. | Community vote, quorum |
| F2 | Stewards and sealing (P7) | Q2 | No rule for admitting or removing a steward, and the sealing quorum is left to each charter with no floor (§03 point 2). | A seal needs N stewards of the user group, never one. A new steward is admitted by N existing stewards. Any steward, a founder included, can be removed by a vote of the user group's members. | Quorum, community vote **DECIDED 2026-10-06:** adopted as a shared floor for all charters (D159). |
| F3 | Founding sealers invited by Javeline (P8, P9) | Q1, Q2 | One person appoints the sealers, with no co-signer, no end date and no recall: "invitation-only delegation invites collusion" (§03, flow-funding notes). | Each invitation is co-signed by N founding sealers who are not the inviter. The invitation power ends on a fixed date or at the parameters conversation, whichever comes first. The founding sealers can revoke it, and any founding sealer, Javeline included, can be removed by them. | Signer threshold, sunset, community vote **DECIDED 2026-10-06:** the invitation power goes to the pilot group's stewards instead (D33). |
| F4 | "Not yet" (P10) | Q2 | A decline cannot be reviewed, so a small group of stewards can keep someone out with no recourse. | A practitioner who is declined can ask for a second review by N stewards of a different user group (or of the same group, excluding those who declined). Reasons stay on record. | Quorum **DECIDED 2026-10-06:** adopted as a shared floor for all charters (D159). |
| F5 | Card acceptance (P12) | Q1, Q2 | Javeline is named co-decider beside "the commons", which is a special founder role (N1). | Cards are accepted by community evaluation in the wiki alone, with a stated vote threshold. Javeline votes as an ordinary member. | Community vote |
| F6 | Removing content (P14) | Q1, Q2 (silent) | Nobody is named who can remove an entry or card, so whoever runs the system can (N3). | Removal needs N stewards, is logged in the open, and can be reversed by a community vote. Authors can always withdraw their own unpublished work (Data Wash). | Quorum, community vote |
| F7 | Course review (P16) | Q1, Q2 | One named person owns review of a paid product that carries the certification's name. | Review is done by a rotating panel of N practitioners at a set phase, chosen by the stewards. Javeline may serve on it for a fixed term, like anyone else. | Quorum, sunset |
| F8 | Course and deck seed (P17) | Q1, Q2 | The founder's material is the default seed, chosen by the founder. | The seed is labelled a hatch seed and ends at the parameters conversation. Other practitioners can add seed material from day one, ranked by the community's votes. | Sunset, community vote |
| F9 | "The commons decides" and the parameters conversation (P19, P22) | Q2 | The response relies on "the commons" for every rule change but never says who votes, the quorum, or how a decision is recorded and signed (N2). | Define "the commons" in one place: the members of the participating user groups. A decision needs a quorum of N user groups and a majority within each, is recorded on the community's chain, and is signed by N stewards. The same process convenes and closes the parameters conversation. | Quorum, community vote, signer threshold |
| F10 | Hatch parameters set by the author (P20, P26) | Q1, Q2 | Levy rates, the founding oligarchy and flow rules are the author's starting values and run until the hatch ends, which has no date (N1, N2). | The founding sealers or the pilot user group ratify the starting values at the start of the hatch, with Javeline abstaining. Any value can be changed during the hatch by the F9 process. | Community vote, sunset |
| F11 | Hatch end (P21) | Q2 | A minimum length with no maximum, and nobody named to end it, means founding powers can last indefinitely (§03 point 1). | Give the hatch a maximum length of N months, after which founding powers lapse automatically. Ending it earlier needs the F9 process. | Sunset |
| F12 | Opt-in billing (P23) | Q1, Q2 (silent) | The response doesn't say who holds billed money between payment and payout. | Billed money goes to the user group's own multi-signature account (N4), with a threshold of at least two signers, never one. The practitioner's fee is released by rule (N5), not by a keyholder's choice. | Signer threshold |
| F13 | Diploma signing (P24) | Q1, Q2 (silent) | "Signed by Certified Practitioner" names no signers, so whoever holds that key issues diplomas alone. | A diploma is issued only with the user group's seal plus at least N witnessing peers' signatures. "Certified Practitioner" signs through a key held by a threshold of at least two stewards. | Signer threshold |
| F14 | Diploma fee (P25) | Q2 | The fee is set in the response, or per charter (K24), with no governance stated. | The fee is a parameter set and changed by the F9 process (or by each charter, if Javeline picks that side of K24). | Community vote |
| F15 | Common pool (P27, P31) | Q1, Q2 (silent) | No keyholders and no threshold are named, and nobody is named who sets the upkeep figure (N4, N5). | The common pool is a multi-signature account with at least two signers, drawn from more than one user group. Javeline cannot sign alone. Spending follows published rules, and the upkeep figure is set by the F9 process. | Signer threshold, community vote |
| F16 | Flow payouts "by hand" (P28) | Q1, Q2 | In the minimum, someone computes and pays the flow by hand, and nobody is named (N4, N5). | Each payout is computed from published inputs, posted for N days before it is paid, and released by a threshold of at least two treasurers who are not recipients in that round. | Signer threshold |
| F17 | Self-declared thresholds (P29) | Q1, Q2 | Each recipient alone sets the figure that governs their own payout, with no review during the hatch. | Keep self-declaration, but publish thresholds before each round, cap them at N, and let any member challenge one for a vote of the stewards. | Community vote |
| F18 | Overflow by appreciation (P30) | Q1, Q2 | Each recipient's appreciation directs money, with no conflict-of-interest rule (§03: "no self/relative/stipend funding"). | Overflow can't go to oneself, a relative, a household member or anyone paying the recipient. The exact algorithm and stopping rule are published before any euros move. | Community vote (to adopt the rule) |
| F19 | Judging the experiment (P32) | Q1 (silent), Q2 | Nobody is named to decide whether the experiment worked or to trigger the fallback. | The result is judged by the F9 process on the published measures (D90), at the hatch's end or earlier if N user groups ask. | Community vote, quorum |
| F20 | Leaving with reputation and seals (P5–P7) | Q3 | The response says members can take their records (session package, Data Wash, take me out) but not whether their computed phase and seals go with them. | Phase is computed from records the member holds, so it travels with them. A seal stays valid after leaving the user group, marked with the group and date it was granted, and can be revoked only by the F2 process, not by the member leaving. | Community vote (to adopt the rule) |
| F21 | Deck adoption after the author leaves (P4) | Q3 | Silent on whether an author can withdraw a deck others adopted, and what happens to the credit flow. | Under ShareAlike (ASSUMPTION, needs clarification) adopted cards stay usable. An author who leaves keeps attribution, and their flow credit stops or continues by a rule set through F9. | Community vote |
| F22 | Forking (P27) | Q3 | The response doesn't say what a group that disagrees can take: the wiki, the records, a share of the common pool (N7). | A forking group may take all shared content and its members' records. A share of the common pool is released to it only by the F9 process, in proportion to a published measure. | Community vote, quorum |
| F23 | Credits set by gossip givers (P36) | Q1, Q2 | Each giver alone decides design or delivery credit, which changes who earns from "use", and there is no rule when givers disagree. | Credit follows the majority of givers, with ties credited to both. The designer and deliverer can contest it within the record's open window (D120). | Quorum |
| F24 | Pilot choice (P37) | Q1 | One person picks where certification starts. | The pilot community confirms its own participation and founding sealers by its own vote. Later communities join by open invitation. | Community vote |
| F25 | Questions settled by two people (P38) | Q1, Q2 | Currency and refund policy affect every member's money but are settled by Javeline and Mujo. | Bring questions 3 and 6 to the pilot community through the F9 process. Mujo's input stays technical. | Community vote |
| F26 | White-label licences (P39) | Q1, Q2 (silent) | Nobody is named who decides to license the protocol or who signs a licence that pays the common pool. | Licences are approved by the F9 process and signed by the common pool's signer threshold (F15). | Community vote, signer threshold |

---

## 4. What already meets the constraint

These parts of the response already match NAOMS and need no change:

- **The platform takes nothing** (D85). This matches N6.
- **Equal evidence**, and governance following stewardship rather than earnings (D96, D87).
- **Consent and exit for data:** take me out, Data Wash, the session package, and private recordings until consent (D137, D51, D65, D19).
- **Seals are local, and the user group is the certifying body** (D31). It is consistent with N1 once F2 and F3 are added.

**One dependency to flag.** §03 notes that NAOMS's "surplus distribution and multi-community settlement are not built yet". Fixes F15, F16 and F22 assume a common pool that spans user groups. Until that exists on NAOMS, they would have to run per user group or by hand under a signer threshold. ASSUMPTION (needs clarification) with Mujo.
