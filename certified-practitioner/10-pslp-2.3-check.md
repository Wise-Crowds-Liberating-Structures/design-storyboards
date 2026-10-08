# 10 · PSLP v2.3: consistency check

Step 10, 2026-10-08. Javeline's question: "take a look at the newest version of the PSLP. Is it consistent? What is it missing?"

The file checked is `PSLP white paper v2.3.pdf`, uploaded by Javeline on 2026-10-08. It has 14 pages, and its change log is dated 2026-10-08. It was checked against [02-decisions.md](02-decisions.md), the single source of truth, and against [08-response-v2.md](08-response-v2.md). Values are not repeated here; rows are cited by number.

**Labels used in this file.**

- Every inconsistency (P1, P2, …) is **OPEN (Javeline decides)**: either the paper changes, or the decision does.
- Every suggested fix is a **PROPOSAL** from this check.

**Resolved 2026-10-08 (Javeline: "1 describe how the pilot 1 initializes the wiki / 2 fix").** All P, E and M items are applied in [11-pslp-v2.4.md](11-pslp-v2.4.md), except E4 (the outside sources stay cited and labelled ASSUMPTION; the Press Start deck was not sent). E1 is corrected to Luigi Fantappiè, early 1940s, as Javeline asked. The wiki initialization is new row D207 (PROPOSAL).

## Summary

- **The three corrections 08 asked for are done.**
  - The header now says v2.3.
  - The certificate is issued from the computed record, with the seal as an optional endorsement (D160).
  - The fee is one fee everywhere, changed only by the commons (D69).
  - The ladder (D23, D29), CC BY-SA 4.0 (D61), "the claim is never for sale" (D72) and "§3.6.5 located, not resolved" (D122) still hold.
- **Ten places still disagree with the decisions (P1–P10).** Five matter most:
  - "steward" means something different in the paper (P1);
  - the ledger "accepts only what participants have collectively attested" (P2);
  - the record is described as immutable (P3);
  - all four rubric dimensions seem to count (P4);
  - the LS Commons signature is stated as fact (P5).
- **Five editing and source problems (E1–E5)**, including a probable factual error about who coined "syntropy".
- **Missing: everything decided since 29 September about money, governance, privacy and the pilots** (M1–M10). The paper says *what* is recorded and *why*, but not *how* money moves, *who* decides, or *what is built first*.

## Inconsistencies with the decisions

| # | PSLP v2.3 says | The decisions say | Suggested fix (PROPOSAL) |
| --- | --- | --- | --- |
| P1 | "The stewards (who captured and submitted the record)" (§3.3, §3.6.1). "Participants collectively, or designated stewards/facilitators, submit a record" (§3.2) | A steward is an organiser who takes responsibility that things happen (D176). Stewards are recognised by request and admitted by unanimous vote at the equinox (D199), and they seal and sign (D31, D201). The person who captures a record is a **Scribe**, whose own evidence is shown but does not count toward co-signature (D202) | Rename the record-capturing role "Scribe". Keep "steward" for the governance role |
| P2 | "The ledger accepts only what participants have collectively attested" (§3.1) | Every claim is admitted and shown with its evidence level; people judge (D161). Imported sessions are kept as claims (D20). The phase is shown side by side per evidence level (D30) | "The ledger admits every claim and shows how well it is evidenced; only co-signed records count toward a phase and a certificate" |
| P3 | "Transparent and immutable record" (§3.1, §3.5, §3.8). "The core record of learning events is immutable" (§3.5) | Anyone can correct, withdraw or take themselves out of a record (D137, consent). Each contributor chooses per entry to publish under their name, publish anonymized, or withhold (D51), from the first data in (D205). Records stay open for late signatures (D120) | Say what is immutable (the signed history of changes) and what is not (what is shown, and whether a person stays in a record) |
| P4 | The rubric "is multi-dimensional, not a session count"; credibility is "claimed against goals met" (§3.6.2, item 1) | The phase and the certificate use **patterns in use only** (D25). People reached, diversity of settings and design goals achieved are shown as plain counts without thresholds. The commons may add thresholds later (D179) | Add one sentence: only patterns in use set the phase; the other three are shown on the record and do not gate it yet |
| P5 | The certificate "is signed by the relevant user groups and the LS Commons" (§3.6.2, item 2) | The LS Commons is presumed to sign until it says otherwise; if it doesn't, the user groups sign alone (D201). Whether the witnessing peers still sign (D160) is an ASSUMPTION (needs clarification, Javeline) | "… signed by the relevant user groups and, presumed, the LS Commons". Add the witnesses if Javeline confirms |
| P6 | Role is "a data-grounded progression (novice → practitioner → steward → certified organizational game designer)" (§3.5) | The progression is the ladder: Despairing Cynic → Cautious Optimist → Rapturous Super-User → Maestro Minimalist (D23). Becoming a steward is a request and an election, not a level (D199). A certificate states the record, not a title or competence (D160) | Use the ladder names. Take "steward" and "certified organizational game designer" out of the progression |
| P7 | Validation by "a quorum of participants" or by participants signing; "designated stewards" can submit (§3.2) | A session counts as co-signed when at least 3 players send Positive Gossip (D30). Guests show on the record as witnesses but don't count (D119, D184). Only people who attest themselves count (D202) | Name Positive Gossip as the co-signature and point to the rule, without the number (D30) |
| P8 | Reputation is "never sold"; pay-to-certify money "goes in full to the common pool" (§3.6.3) | Consistent with D72 and D163, but the paper stops there. The pool only fills at first; flow funding starts later by an equinox vote (D163, D165) | Add a sentence and point to the money section (M1) |
| P9 | §3.5 lets trust and progress "unlock higher levels of access or influence over content organization" | Wiki and course votes are open to members with a co-signed record (D193, PROPOSAL). Governance follows stewardship, never earnings (D87). Weak content sinks by votes and is not removed (D180) | Tie "influence" to D87 and D193 (or say it is open) |
| P10 | The trust wire fix is "a one-to-two-week change" (§3.6.5) | The decision sets a deadline, not a duration: before a second community's seals are recognised, and no later than the end of the hatch. Mujo builds it (D125) | State the deadline from D125. Keep the estimate only as Mujo's |

## Editing and source problems

| # | Problem | Suggested fix (PROPOSAL) |
| --- | --- | --- |
| E1 | **Probably wrong:** "Syntropy — the term established by Lofredo de Matteo in 1945" (§3.7). As far as Claude knows, the term is usually credited to the mathematician Luigi Fantappiè in the early 1940s. This is not checked against a source in the folder: ASSUMPTION (needs clarification, Javeline) | Check the source, then correct the name and year, or drop the attribution |
| E2 | The change log's last lines repeat themselves. The text "races, syntropy reflection), re-worked §3.5 … added Appendix A." appears twice, and it ends in a stray "*" | Delete the duplicate |
| E3 | §3.6.5 says "the two functions that would have no production caller", without naming the two functions. A word or list is missing | Name the two functions, or rewrite as "two functions have no production caller" |
| E4 | The paper cites sources that are not in this folder: the "Press Start: Organizational Game Design" deck (Papa Pita, 2026), "the field guide", "the 2026 book", Toyota Kata, and Mujo's Kitestring proposal §07. Draft 3 is in the project folder but not in the GitHub repository. Per rule 3, these claims are ASSUMPTION (needs clarification) | Javeline: send the Press Start deck if the paper relies on it. Otherwise keep the citations, but don't add more |
| E5 | The paper calls the certificate "issued to an employer or L&D budget holder" (§3.6.3) | It is issued to the practitioner, who shows it to an employer (D160, D162) |

## What v2.3 is missing

Everything below is decided (or proposed) in 02 and written up in 08, but absent from the paper. The paper doesn't need every number; it needs the mechanism and a pointer.

| # | Missing | Rows |
| --- | --- | --- |
| M1 | **How money moves.** The common pool only fills in pilot 1, and the 3 pilot stewards hold the keys, any 2 of 3 signing. Flow funding starts once the pool covers a season of survival thresholds and an equinox vote approves, with Javeline abstaining. Happy Money Story shares grants. Neither the platform nor Javeline takes anything outside the flow | D163, D200, D165, D169, D167, D85 |
| M2 | **Who decides.** The commons (user groups voting together), the equinox cycle, how stewards are recognised, and the founder limits. The paper's §4 still lists governance as future work | D166, D199, D35, D159 |
| M3 | **The evidence principle** ("paint on the road, not crash barriers"), with evidence levels shown side by side. This is the single biggest idea added since v2.2 | D161, D30, D20 |
| M4 | **Privacy as a choice from the first data in.** Data Wash (attributed, anonymized or withheld), and correct, withdraw, take me out. §3.8 talks about ZKPs and TEEs but not about the person's own choice | D51, D205, D137 |
| M5 | **Two pilots.** What is built first (recording, ladder, certificates, Data Wash, session package) and what comes in pilot 2 (wiki, course, optional seal). The paper treats the Learning Journal (wiki) as the core interface, but the journal now comes in pilot 2 | D158, D134, 07-scope.md |
| M6 | **The co-signature itself:** Positive Gossip, the 3 givers, guests as witnesses, Scribe evidence, and the late-signature window | D30, D119, D202, D120 |
| M7 | **Gaming defences and accepted risks:** one appreciation budget per member, one counted account per person, no pay for use when the author was in the session, and the risks reviewed at each equinox | D183, D184, D187, D203 |
| M8 | **The session package for AI agents** (download a whole session, for example as an MCP server) and the rule that AI only suggests labels while fixed rules decide what counts and pays | D139, D65, D182 |
| M9 | **The deck's own licence:** Javeline's deck and videos are re-released under CC BY-SA 4.0. The paper only covers the LS material | D64 |
| M10 | **The network pattern cards** as labels for a person's position and a session's context (it fits §3.6.5's small-world section) | D198 |

## Questions for Javeline

1. Should I write v2.4 of the paper with fixes P1–P10 and E2, E3 and E5? I would add a short section for M1–M8 that points to the decisions instead of repeating them (recommended), or list the changes for you to make.
2. E1: do you have the source for "Lofredo de Matteo, 1945"? If not, I'll correct the name and year to Fantappiè, early 1940s, and mark it ASSUMPTION.
3. E4: is the "Press Start: Organizational Game Design" deck something you can add to the folder?
