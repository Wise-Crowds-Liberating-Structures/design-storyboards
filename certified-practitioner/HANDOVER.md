# Handover for AI agents: Certified Practitioner

Written 2026-10-08 for any agent asked to continue or extend this project. Read this file first, then the files in the order given under "Reading order". Everything here points at files in this folder; nothing depends on chat history.

**Where the files live.** The working folder is the project folder (`/mnt/project-files`). A copy is in the public GitHub repository `Wise-Crowds-Liberating-Structures/design-storyboards`, in the `certified-practitioner/` folder. The repository leaves out NAOMS's two documents (marked below), by Javeline's decision of 2026-10-08, until Mujo agrees to publish them. If you work from the repository and need them, ask Javeline for them.

## 1. What the project is

**Certified Practitioner** is a community-owned certification program for people who practise Liberating Structures (LS). It proves someone learned a practice socially, from and with peers: sessions are recorded, co-signed by other participants, and computed into a public record. That record unlocks a paid **certificate of practice**, and the money flows to the people and the common pool that make the practice valuable ("omni-win").

- **Author:** Javeline (also written as **Jeremy**, Javeline's pseudonym: the same person).
- **Builder:** NAOMS, represented by **Mujo**. NAOMS builds it as an app on its platform. "Kitestring draft 3" is NAOMS's design draft.
- **First community (pilot 1):** LS Go Online and the Wise Crowds Design Call, counted as one community.
- **Other names that appear:** The LS Commons (presumed co-signer of certificates), Kevin and Maurits (possible ecosystem funders, D206), The Liberators (price reference, D40).

## 2. Where the work stands (2026-10-08)

The job so far has been to turn Javeline's response to NAOMS into a consistent document that another team can build from. Steps 1–9 are done.

- **`08-response-v2.md` is final and ready to send to NAOMS.** It has passed the step 9 checklist.
- **All conflicts are settled.** C1–C19 in 02-decisions.md and K1–K22 in 03-conflicts.md.
- **42 questions are still open, each with an owner** (06-questions.md and "Still open" in 08). Nine block pilot 1, plus Javeline's trademark check (D204). They break down as follows:
  - **Mujo:** the euro rail (Monerium), checking the refund rule against EU consumer law, one person per account, the credential format, Data Wash sizing, and testing.
  - **Javeline and Mujo together:** funding the build (D206 PROPOSAL: ecosystem funding via Kevin or Maurits), and the lawful basis for transcribing old recordings.
  - **The pilot group:** confirming the starting values (D170).
- **Waiting on Javeline:** The Liberators' prices (source for D40).
- **`09-game-design-doc.pdf`** is a 12-page visual edition of 08, styled as a game design document. Where the two differ, 08 wins.

## 3. Standing rules (from Javeline, 2026-09-30). Follow them in every step.

1. **One source of truth.** Every decision, number, price, threshold and duration lives in ONE table: `02-decisions.md` (and its condensed copy at the top of 08). Everything else refers to rows (D1…D207) and never repeats a value.
2. **Label every sentence that is not settled.** The labels are:
   - DECIDED (with who and when);
   - PROPOSAL (with who proposed it);
   - OPEN (with who decides);
   - ASSUMPTION (needs clarification).
3. **Never reference a document, version or section that is not in the folder.** If Javeline mentions one, stop and ask for it. Claims resting on outside sources are labelled ASSUMPTION.
4. **No unfinished sections.** A heading either has content or is removed.
5. **Conflicting statements:** show both and ask. Never pick one quietly.
6. **Keep Javeline's voice and ideas.** The job is consistency, completeness and honesty, not rewriting.
7. **Save every result as markdown in the folder, named by step:** 01-…, 02-…, and so on. Next free number: **12**.

Javeline sends steps one message at a time.

## 4. Key ideas you must not break

- **Evidence principle (D161, 04b):** "paint on the road, not crash barriers". Every claim is admitted and shown at its evidence level; people judge. **Money is the exception:** it moves only by fixed rules and signer thresholds.
- **Two pilots (D158, D134):**
  - **Pilot 1:** recording, ladder/reputation, certificates, stewards, the pool, Data Wash privacy from the first data in (D205), and the session package for AI agents (D139).
  - **Pilot 2:** wiki, course and the optional seal.
- **Certificates (D160, D162, D201, D69):**
  - Issued from the computed record and unlocked at Cautious Optimist (8+ co-signed patterns).
  - One fee everywhere.
  - Signed by the relevant user groups; the LS Commons is presumed to co-sign, and if it doesn't, the groups sign alone.
  - Only attesters count; Scribe evidence is shown but does not count (D202).
- **Stewards (D199):** anyone may ask to become one, evaluated at the equinox and admitted by a unanimous vote of the existing stewards, who come from different user contexts. Javeline nominates the 3 pilot stewards once.
- **Pool (D200, D163):** the 3 pilot stewards hold the keys and any 2 of 3 sign. In pilot 1 the pool only fills.
- **Flow funding (D165, D169):** starts when the pool covers a season of survival thresholds and an equinox vote approves. Javeline abstains.
- **Governance runs on the equinox cycle.** Thresholds and grants are settled by Happy Money Story (D167; summary in `sources/`).
- **Licence (D61–D64):** LS material, Javeline's videos and the deck are all CC BY-SA 4.0.
- **Anti-gaming (05-gaming.md):**
  - Decided: D183–D185, D187, D189, D190.
  - Still proposals: D186, D188, D191–D197.
  - Residual risks are accepted and reviewed each equinox (D203).

## 5. ID schemes

| Prefix | Meaning | Lives in |
| --- | --- | --- |
| D1–D207 | Decisions and numbers (gaps are folded or replaced rows) | 02-decisions.md |
| C1–C19 | Conflicts within the decisions table, all settled | 02-decisions.md |
| K1–K22 | Consistency conflicts in the response | 03-conflicts.md |
| F1–F26 | Fixes from the power-and-money check | 04-power-and-money.md |
| Q1–Q51 | Decision queue put to Javeline | 04a-decision-queue.md |
| G1–G15 | Gaming attacks and fixes | 05-gaming.md |
| L1–L55 | Question ledger (open and decided) | 06-questions.md |
| P0.1–P5.3 | Features by priority | 07-scope.md |
| L123 etc. | Line numbers in the original response file | (cited in 01–05) |

## 6. Files

**Reading order:**

1. This file.
2. `08-response-v2.md`, the current document.
3. `02-decisions.md`, the source of truth.
4. `06-questions.md`, what is open.
5. `07-scope.md`, what is built when.

Then, as needed, the step files and sources below.

| File | What it is |
| --- | --- |
| `01-inventory.md` | Step 1: inventory of files and cross-references, and Javeline's first answers |
| `02-decisions.md` | Step 2: **the single source of truth** (D, C) |
| `03-conflicts.md` | Step 3: consistency audit (K) |
| `04-power-and-money.md` | Step 4: mechanisms tested against NAOMS's money-and-power constraints (F) |
| `04a-decision-queue.md` | The queue of decisions put to Javeline and the answers (Q) |
| `04b-evidence-principle.md` | Javeline's evidence principle |
| `05-gaming.md` | Step 5: adversarial pass (G) |
| `05a-network-pattern-cards.md` | Using the network pattern cards to label context and position (D198) |
| `06-questions.md` | Step 6: question ledger (L) |
| `07-scope.md` | Step 7: scope and pilot minimum (P), adopted |
| `08-response-v2.md` | Steps 8–9: version 2 of the response, ready to send |
| `09-game-design-doc.pdf` | Visual game-design edition of 08 (source in `gdd-source/`) |
| `10-pslp-2.3-check.md` | Step 10: PSLP v2.3 checked against the decisions (P inconsistencies, E edits, M missing) |
| `11-pslp-v2.4.md` | Step 11: PSLP white paper v2.4, all step 10 fixes plus how pilot 1 seeds the wiki (D207) |
| `Certified Practitioner — response to Kitestring draft 3.md` | **Original input:** Javeline's response, 29 Sep 2026. Line numbers cited in 01–05 refer to it |
| `NAOMS-Kitestring-PSLP-draft3-2026-09-25.pdf` | **Input:** NAOMS's design draft 3 (mostly images). Not in the GitHub repository |
| `NAOMS-Certified-Practitioner-feedback-2026-09-29.pdf` | **Input:** Mujo's feedback on the response. Not in the GitHub repository |
| `PSLP white paper v2.3.pdf` | **Input:** latest PSLP white paper (2026-10-08) |
| `PSLP white paper v2.2 (2026-09-29).pdf` | **Input:** previous PSLP white paper (header still says 2.0) |
| `certified practitioner 2.1.pdf`, `Proof of Social Learning White Paper (1).pdf` | **Input:** earlier white papers |
| `sources/` | Summaries of outside sources Javeline gave (Happy Money Story, LS Commons note) |
| `uploads/hearth/` | Javeline's uploaded images. Each file is named by its ID, without an extension (see `.notes/inputs.md` for which is which): the network pattern cards, the LS principles, Ostrom's principles |
| `.notes/inputs.md` | Notes on every input file: size, format, quirks. Update it when you add inputs |

## 7. How to extend the work

- **A new decision:** add a row to 02-decisions.md with the next D number, a source (who and when) and a status. Mirror it in 08's table if it belongs in the response. Update the matching L row in 06 and the "Still open" table in 08.
- **A change to a decision:** edit the row, and add a dated note in that row rather than deleting history. Then search every file for the D number and fix the text that refers to it.
- **Before calling anything ready:**
  - every D reference in 08 resolves to a row in its table;
  - every open item names an owner;
  - no heading is left empty;
  - no file outside the folder is cited.
- **Rebuilding the PDF:** edit `gdd-source/gdd.html`, then print with headless Chromium. Example: `chrome --headless --no-sandbox --print-to-pdf=09-game-design-doc.pdf --no-pdf-header-footer gdd-source/gdd.html`. The fonts are local woff2 files in the same folder. The card colours were sampled from the uploaded cards:
  - frame green `#0b7354`
  - mint `#2fd39a`
  - purple `#a020f0`
  - light pink `#f9a8cf`
  - pink-red `#f0335f`
  - blue `#12a8dc`
  - deep blue `#2457d6`
- **Tooling notes:** pypdf fails in this environment; use `pymupdf`. Draft 3's screens are images, so read them by eye.

## 8. People and how they want to work

- **Javeline** decides everything in the design. Answers come in short numbered replies ("1 yes / 2 unanimous"). Put questions as numbered options with a recommendation.
- **Mujo (NAOMS)** owns the platform questions: payments, identity, credentials, data. Questions for Mujo go in 08's "Questions for NAOMS" section.
- Write plainly, in full sentences, and lead with the answer.
