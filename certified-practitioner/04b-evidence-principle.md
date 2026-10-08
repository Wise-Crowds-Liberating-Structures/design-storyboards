# 04b · The evidence principle

Javeline's explanation in the thread on 2026-10-06, as I understood it, and what it changes in the open questions. Status: **DECIDED 2026-10-06** (Javeline confirmed; D161 and D20 in 02-decisions.md).

## The principle, in Javeline's terms

Certified Practitioner is an agent-based system, not a deterministic one. It works like paint on the road, not crash barriers: it guides, it doesn't enforce. Instead of deciding which claims count, it:

1. **Admits every claim**, whatever its evidence.
2. **Shows how well each claim is evidenced.**
3. **Leaves participants and the marketplace to judge**, using their own intelligence and discretion. Some buyers want a strong track record. Others, with "more time than money", are happy with an early-stage practitioner.

## What makes a claim stronger

From the thread, roughly from weaker to stronger:

| Evidence | Example |
|---|---|
| Personal claim | "I ran this." |
| Attestation | "I was there." |
| Peer co-signature and peer feedback | Positive Gossip, RoTI |
| Content and artifacts | Photos of traces, transcripts, designs, recordings |
| Provenance | A recording published at the time, with a creation date close to the session, is worth more than a fresh link claiming something from long ago |
| Network topology | Witnesses from many different communities are stronger than a closed circle. Draft 3 already draws this with the Network Relationship cards (Boundary Spanner, Cohesive Clique) |
| Community certification | A user group's seal (D160: an optional endorsement) |

These combine: a claim can carry several kinds of evidence at once.

## What it settles or changes

| Open item | What the principle suggests | Still needs |
|---|---|---|
| **Q8** imported history | Neither option as asked. Imported sessions count as claims and are shown at their evidence level ("imported, not co-signed", with any content and its dates), never silently blended with co-signed records | Javeline to confirm |
| **D160** certificate of practice | The certificate shows an evidence profile (what kind of evidence backs each part of the record), not just a phase | Whether the phase number itself is computed from all claims, or only from claims above some evidence level |
| **Q7d** witness signatures | A minimum may not be needed to *issue* a certificate. The certificate shows how many witnesses there are and how diverse they are | Whether any floor applies, given the certificate is paid (the "never sell the claim" Must-not) |
| **Evidence discipline** (L297, Mujo's "nothing counts unless co-signed") | Becomes "everything is shown at its evidence level" | A change to the response's wording; worth telling Mujo explicitly |
| **Closed circles** (Mujo's §04, K6, K21) | Answered by showing them, not preventing them, as draft 3 already said ("shows collusion, does not prevent it") | See money, below |
| **Trust wire** (D125, D157) | Topology across communities needs M0. Before M0, topology can only be shown within one community | Nothing new: D157 already covers it |
| **Archive import** (D16) | Must keep the original creation and publication dates of imported content as provenance evidence | Add to the importer's requirements |
| **Wiki votes** (Mujo: "votes need weighting") | Votes could show voters' evidence levels instead of being weighted in secret | A later question |

## Where the principle meets a hard limit: money

Reputation and certificates can work as "paint on the road". **Money can't.** Mujo's §03 is a hard constraint: money moves only under a threshold of signers, by published rules. Flow funding pays on "use in a co-signed session" and "appreciation". So somewhere a rule has to decide which evidence level counts for payment. Letting the marketplace judge works for hiring someone. It doesn't work for an automatic payout.

This is the main new question the principle raises (Q8c in the queue).

## New questions this raises

- **Q8a:** Is the phase computed from all claims, or only from claims above an evidence level, with the rest shown beside it?
- **Q8b:** Who or what sorts claims by evidence: rules written into the app, AI agents, community review, or all three? "Agent-based" could mean any of these.
- **Q8c:** For money (flow funding), which evidence level does a "use" or "appreciation" need before it pays?
