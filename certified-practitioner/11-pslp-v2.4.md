# White Paper: Proof of Social Learning Protocol

**Version 2.4.** Organizational Game Design revision, aligned to the Certified Practitioner response (v2, Oct 7) and to the decisions through D207. Date: October 2026. Status: draft for community review.

> **How to read this version.** Numbers, prices and thresholds are not repeated in this paper. They live in the Decisions and numbers table, which is in [02-decisions.md](02-decisions.md) and condensed in [08-response-v2.md](08-response-v2.md). D-numbers in brackets point to its rows. Anything not yet settled carries a label: **PROPOSAL** (a suggestion, not yet decided) or **ASSUMPTION** (rests on a source that is not in the project folder). The changes since v2.3 are listed in the change log at the end, and were found in [10-pslp-2.3-check.md](10-pslp-2.3-check.md).

## Abstract

This white paper introduces a novel Proof of Social Learning Protocol (PSLP), designed to record knowledge transfer and learning events within communities of practice transparently and with a tamper-evident history. It uses Distributed Ledger Technology (DLT), specifically a blockchain. Unlike traditional blockchain protocols, which rely on computational proof-of-work for validation, PSLP uses social learning events as the fundamental validation mechanism ("mining").

This revision frames the protocol in terms of organizational games. These are structured interactions that deliberately organize a group's time, attention, information processing and energy; the Liberating Structures are the most mature and best-refined example. Two central commitments distinguish this version:

1. **Traces, not bare agreements.** The protocol records not only what a community did, but how the group's thinking moved. It accumulates traces, so that the community can see and sense its own system.
2. **Syntropic value.** The protocol favors structures and practices that become more organized and more ordered over time. It expands the possibility space of the communities that use them, rather than dissipating their potential.

The protocol is particularly well suited to communities focused on procedural knowledge, such as the Liberating Structures community of practice, where specific methods or "structures" can be seen as discrete packets of procedural knowledge. A core component is a shared Learning Journal (wiki) interface. It uses recorded learning progress, community evaluation and available data to enhance user learning and to keep information organization low-effort. The journal arrives in the second pilot, already filled with what the first pilot recorded (§3.4.1).

Privacy, data sovereignty, security, ethical sharing and attribution are paramount to the protocol's design, and so is the cultivation of a regenerative economy of value, discovery, divestment and distribution.

## 1. Introduction: The Value of Capturing Social Learning

Knowledge transfer and learning within communities are often implicit, fragmented, and difficult to track or formally recognize. Digital platforms exist for sharing information, but they frequently rely on centralized models that can lead to silos, data exploitation and a lack of trust. Traditional credentialing systems can be costly and exclusive, and may not accurately reflect embodied practice or collaborative learning.

### 1.1 A capacity that is real but unclaimed

Much of the most valuable work that happens inside groups is organizational design in the broadest sense: the responsible organization of a group's time, attention, information processing and energy. Human attention is the scarcest and most valuable asset any group possesses. A person who can reliably structure it, setting up the conditions under which a group thinks well, decides well and acts together, is exercising a capacity that is widely needed and rarely credibly evidenced.

We call the holder of this capacity an organizational game designer: a practitioner who designs games in the deepest sense (socially constructed rule systems for distributing attention and power) and who has the demonstrated skill of deploying them in specific contexts. Liberating Structures practitioners, skilled facilitators, experienced coaches and capable meeting chairs are all working instances of this capacity.

The Liberating Structures literature is itself testimony to its value. The structures are "incredibly well-designed". By leaning into their design elements, a practitioner can understand how group intelligence actually works and how to work with it. The design elements are:

- how participation is distributed;
- how groups are formed;
- the steps over time;
- the invitation;
- the organization of materials and space.

Three problems attend this capacity today:

1. **It is implicit.** It lives in embodied practice and in the design decisions behind a meeting. It lives, too, in the system of justification the practitioner holds when asked why they chose these elements and not others. It is, in the words that describe the field itself, "super easy to use, hard as anything to explain."
2. **It is unevidenced.** There is no shared record of who has demonstrated it, in what contexts, at what scale, and with what results. Claims are cheap, evidence is costly, and the evidence is currently nowhere to be found.
3. **It is unvalued in formal terms.** No credential makes this capacity declarable for the general practitioner, that is, a non-speculative, community-grounded way of stating "I can do this".

Capturing and valuing social learning requires new approaches. They need to align with the principles of decentralized collaboration, community empowerment, and the recognition of diverse forms of value beyond the purely monetary. This white paper proposes the Proof of Social Learning Protocol (PSLP) as a framework for building such a system. The protocol treats the social learning events of a community of practice as the primary evidence of the capacities those events produce and refine.

### 1.2 Why a distributed ledger

Blockchain technology offers a decentralized and transparent means of recording transactions and data. However, many blockchain applications have focused primarily on financial value or speculative assets, often reproducing existing inequalities and power dynamics.

There is a need to explore how DLT can support social and community-driven objectives, moving beyond purely transactional exchanges to enable social and solidarity practices. PSLP is one such application: a ledger whose native "currency" is not tokens but attested evidence of learning and capacity. Tokens are out of scope until the common pool is large enough to experiment with (D99).

## 2. The Liberating Structures Community: A Suitable Use Case

The Liberating Structures (LS) community of practice provides an ideal context for piloting a Proof of Social Learning Protocol. LS are a set of microstructures that can be used to engage groups of any size in collaborative problem-solving, innovation and planning. The core set is described in D26, and its count and edition are an ASSUMPTION. They are simple rules to unleash a culture of innovation, and they make it practical for people at any skill or hierarchical level to quickly become expert contributors.

Importantly, each Liberating Structure is a discrete packet of procedural knowledge, defined by five design elements:

- how participation is distributed;
- how groups are formed;
- the steps over time;
- the invitation (question or prompt);
- how materials and space are organized.

Learning LS involves direct experience, practice and debriefing with peers, not instruction alone. As the field guide puts it (ASSUMPTION: the guide is not in the project folder), you will not believe what the structures do for you until you have practiced the methods and learned from them. This has two consequences for the protocol, developed in §3.2 and §3.6:

- Every LS practice session is embodied skill acquisition, and its record is strong evidence of practitioner capacity.
- The community that practices the structures is at the same time training the validators of any protocol built around them.

The LS framework and its community embody key principles that align with PSLP's goals:

- **Focus on process:** LS emphasizes how people interact and collaborate, providing a structured approach to social dynamics.
- **Community of practice:** LS is learned and spread through shared experiences and peer-to-peer interaction.
- **Open source nature:** LS is licensed under Creative Commons (CC BY-SA 4.0), encouraging adaptation and sharing (D61). The Certified Practitioner deck and its seed videos are re-released under the same licence (D64).
- **Diverse participation:** LS methods are designed to include and unleash everyone, regardless of hierarchy or skill level.
- **Design discipline:** LS are "incredibly well-designed" and carry explicit design elements and a system of justification. That makes them natural, structured units of record on the ledger.

Documenting how these structured interactions are applied and learned provides a tangible starting point for recording complex social learning events on a ledger.

## 3. The Proof of Social Learning Protocol (PSLP)

### 3.1 Core Concept: An Evidence Archive, Not a Transaction Log

The PSLP uses a DLT, specifically a blockchain, as an open, shared, decentralized database to record information about social learning events. This section restates the core concept with the emphasis this revision places on it. The ledger is best understood as an evidence archive: a growing, permissioned, community-validated record of what people have actually done, in what contexts, and with what attested outcomes.

In a commons, claims are cheap and evidence is costly. Anyone can say they are a capable facilitator. The ledger therefore admits every claim, and shows how well each one is evidenced:

- a personal claim;
- an attestation;
- a peer co-signature;
- content and artifacts;
- provenance dates;
- the shape of the witness network;
- a community seal.

Participants and the marketplace judge for themselves (D161). This is paint on the road, not crash barriers: the protocol guides rather than enforces. Only co-signed records count toward a practitioner's phase and certificate (D30, D162). Money is the one exception to "show and let people judge": it moves only by published rules (§3.9).

No single record certifies anyone. Credential emerges from the pattern across records:

- the structures used;
- the contexts of application;
- the scale of groups;
- the novelty of situations;
- the community evaluation recorded in the Reflection field (§3.3).

Equally important is what the records are. Meeting minutes are an agreement: a snapshot of consensus at a point in time. A PSLP record is a trace: a record of motion, of how a group's thinking actually moved through an event. It shows what the group touched, what it produced, and what was learned in the doing.

The distinction matters because traces are what you can look back on and sense the system through. The protocol's native data unit is therefore the trace. The Learning Journal (§3.4) is the place where traces accumulate until the community's own system becomes visible to itself.

The ledger provides a transparent record of learning activities within the community, with a tamper-evident history: every signature, correction and withdrawal is itself recorded. The record's value grows with every event, because every event adds not just information but capacity evidence about the community's own designers.

### 3.2 Social Learning Events as "Mining"

Instead of relying on energy-intensive computational puzzles for validation, as in Proof-of-Work, PSLP uses social learning events themselves as the "mining" process that validates and adds data to the ledger. A social learning event could be:

- a practice session where a specific LS is used;
- a workshop or training where LS methods are taught and practiced;
- a coaching session applying LS-based inquiry;
- any structured interaction where explicit learning or knowledge transfer using defined protocols occurs.

**How an event is recorded.** During or after a social learning event, the participants, or a Scribe on their behalf, record the event. Nobody has to type a record: the host picks the cards played from a list, photographs the traces, and the session closes in a fixed order (D124, D53):

1. traces;
2. Return on Time Invested (RoTI);
3. Positive Gossip;
4. Data Wash.

**How it is validated.** Validation rests on the social consensus of the participants involved. Each player confirms the session by sending Positive Gossip, a short, signed appreciation of the others' practice. A session counts as co-signed when enough distinct, verified players have sent it (D30, D184). This distributed trust mechanism validates the "block" of learning data before it is added to the chain. It distributes trust rather than removing it.

Some evidence does not count toward co-signature:

- Guests who give feedback show on the record as witnesses, but they do not count toward co-signature or payment (D119).
- A Scribe's evidence, for example a "present" mark for a player without a phone, is shown at its evidence level, but only people who attest for themselves count (D202).

Records stay open for late signatures for a fixed window (D120).

**First-class events.** All structured learning interactions qualify as social learning events, but a subset is first-class: events in which participants practice the community's own method. Training and practice in the Liberating Structures themselves is the paradigmatic case, because LS are acquired through direct experience, practice and peer debriefing rather than instruction alone. Such records are first-class in two ways:

1. **They are the strongest evidence of practitioner capacity.** A participant who has structured, run and debriefed a practice session has demonstrated the very capacity the community values above others: the responsible organization of a group's time, attention and energy.
2. **They train the protocol's own validators.** The quality of the ledger depends on the capacity of those who witness, attest and record its blocks, and practice-in-the-method records document exactly that capacity in formation. The ledger thus records the events that produce its qualified validators. This is a productive self-reference, since the evidence is attested by participants rather than issued by an external authority.

First-class records carry the same data model as any other event (§3.3), but they are flagged as such. They form the primary evidence base for the certificate of practice described in §3.6.

### 3.3 Data Model: Recording Learning Activities

Each social learning event recorded on the PSLP ledger includes structured data, captured through intuitive interfaces to minimize user effort. The data model encompasses:

- **Context:** where and when the learning event took place (for example organization, community group, date, time). The setting can also be labelled with a network pattern card describing the group's shape (D198).
- **Objective:** the stated purpose or goal of the learning event. For LS applications, this could link to the "Nine Whys" of the work, or to the ideal-state goal-setting practiced in facilitation traditions (the "definition of awesome" of Toyota Kata; ASSUMPTION: source not in the project folder).
- **Participants and roles:** pseudonymized or verified identities of the participants, with roles kept distinct.
  - **The designer or designers:** the person who organized the group's time, attention, information processing and energy. Everyone on a design team is credited as a co-designer (D115).
  - **The deliverer:** design and delivery are nested. Both are credited by default, and they are split only when someone delivers another's design (D115).
  - **The players:** the participants in the game itself.
  - **A Scribe, where there is one:** the person who captured part of the record for others.
  - **Witnesses:** guests who gave feedback.

  Permission layers manage the visibility of this data, based on user preferences and community norms. Distinguishing roles is what makes the ledger a capacity archive rather than an attendance log.
- **Process and structure:** the specific LS, or sequence of structures ("strings"), used, including time allocation and group configurations. These are the five design elements made explicit.
- **System of justification:** why these elements, and why this design? This is the design rationale the practitioner holds: how the chosen structure serves the stated objective, given the participants and constraints. This field converts a record from "what happened" into "how a designer thinks", and it is the single most discriminating field in the model.
- **Content and outcomes:** summaries of discussions, key insights, emergent ideas, decisions made, or planned next steps. This could include links to external documentation or artifacts where appropriate.
- **Traces and artifacts:** the concrete artifacts the event produced.
  - Maps, for example Ecocycles.
  - Traces, for example Simple Ethnography notes, 25/10 Crowd Sourcing outputs and "What I Need From You" lists.

  These are the evidence that the group's thinking actually moved, and they are what later communities can read to sense the system.
- **Reflection:** an evaluation of Return on Time Invested, structure choice, design, novelty and innovation, second thoughts, and Tips and Traps. Per §3.7, it also assesses the event's syntropic quality: did the event leave the group more organized, more capable, and with a larger possibility space than it found them?
- **Consent:** each contributor's Data Wash choice for each of their entries: publish under their name, publish anonymized, or withhold (D51). This applies from the first data in (D205).

Capturing this structured data allows us to map how different structures are applied in various contexts for specific purposes, and the outcomes they generate.

### 3.4 The Shared Learning Journal (Wiki Interface)

The shared Learning Journal serves as the main interface for users to access and interact with the data on the PSLP ledger. Designed as a collaborative wiki, it visualizes the recorded learning events, and offers functions that support user learning and community knowledge building. Per pattern it holds Tips, Traps and Riffs; per string, the designs actually played, with their outcomes; and per setting, which patterns are used for which problems (D44). The journal uses the structured data on the ledger in several ways:

- **Learning progress:** users can track their own participation in learning events and see their experience with different LS patterns, using the Ecocycle as the developmental pathway (§3.6.2). Because the journal is a trace archive, a user's history is not a count of events. It is a readable progression of demonstrated capacity: structures used, contexts of application, scale of groups, and community-evaluated results.
- **Novelty and utility:** the journal can highlight instances where structures were used in novel contexts or situations, or where community evaluation indicates high utility or impact.
- **Organization and navigation:** the wiki can organize information about LS patterns, strings, Tips, Traps, Riffs, variations and examples, based on the recorded data. It can use metadata (context, objective, participants) for searching and filtering, so that users can find relevant examples or connect with practitioners. A practitioner's own Tips, Traps, Riffs and videos lead in their own views. Community entries follow, ranked by votes (D13, D48).
- **Seeing and sensing the system:** because the journal accumulates traces rather than bare agreements, the community can watch its own system develop: which structures travel, which designers are repeatedly attested, and which contexts produce which outcomes. The journal is, in effect, a sociological instrument pointed at the community's own learning.
- **Low resource demands:** because the wiki draws structured data from the ledger, it can automate organizational tasks, which takes less manual effort than a traditional wiki. Non-intrusive interfaces for entering data during learning events also keep the burden on participants low.

The journal fosters a knowledge commons where collective wisdom is shared and made accessible. Community evaluation adds to it: up and down votes rank entries, and Ostrom's principles are the governance frame (D48). Votes rank the journal but never pay (D49). Weak content sinks and stays visible at its rating. Removal is only for legal or safety reasons (D180).

#### 3.4.1 How pilot 1 initializes the journal

The journal opens in the second pilot, together with the automatic online course. It is fed by the first pilot's records (D158), so on its first day it is not empty: the first pilot has been filling it from the first recorded session (D207, PROPOSAL).

1. **Every pilot 1 record already has the journal's shape.** When a session is recorded in pilot 1, its data is stored by pattern, by string and by setting, the three ways the journal is organized (D44). The cards played identify the patterns and the string. The context and the network pattern card identify the setting. The Reflection holds the Tips and Traps.
2. **Every entry already carries its consent.** From the first data in, each contributor chooses per entry whether to publish it under their name, publish it anonymized, or withhold it (D51, D205). The journal never asks again later, and never publishes what someone withheld.
3. **On the journal's first day, the published entries become its first pages:**
   - **per pattern:** the Tips and Traps from pilot 1's RoTI and reflections, credited to their authors or shown anonymized;
   - **per string:** the designs actually played in pilot 1, with their traces (photos of walls, maps and lists) and their co-signed outcomes;
   - **per setting:** which patterns pilot 1's two groups used for which problems, labelled by the network pattern cards where the session had one.
4. **The imported archive joins at its own evidence level.** In pilot 1, practitioners import their past sessions and materials. Each item lands in a review queue as a proposal, which the practitioner approves, fixes or discards (D16, D17). Approved items keep their label "imported, not co-signed" (D20). They join the journal as drafts beside the co-signed entries, never blended with them.
5. **The practitioner's own entries lead, and the community starts sorting.** In each practitioner's view, their own entries come first (D13). Voting opens with the journal in pilot 2, and the automatic course is generated from what the votes rank highest (D55, D158). Pilot 1's evidence levels stay visible on every entry, so voters can see what was co-signed and what was claimed (D161).

Pilot 1 is therefore also the journal's seeding season: the wiki starts from real records with real consent, rather than from an empty page or a copy of the community website.

#### 3.4.2 How the journal bootstraps an online course

The journal is not the end of the line; it feeds one official automatic course that integrates everything in the journal and updates itself (D55). Its automation is the point (D54).

1. **The seed.** The knowledge graph behind the journal and the course is seeded from three sources (D58):
   - pilot 1's published records (§3.4.1);
   - the Liberating Structures website;
   - Javeline's deck and videos, labelled as a hatch seed.

   Other practitioners can add their own decks and videos from day one.
2. **The distillation.** The commons creates the official course through its up-votes: a distillation of the most relevant knowledge in the graph, with a way to flag errors. Javeline takes part as an ordinary contributor (D60). Only members with a co-signed record vote, one per person (D193, PROPOSAL). Votes rank, but never pay (D49).
3. **The structure.** The course follows the journal's own shape. Each pattern is a lesson built from its best-ranked Tips, Traps and Riffs. Strings that were actually played, with their traces and co-signed outcomes, are worked examples. The patterns used for each kind of problem are the course's map of settings (D44).
4. **Many curations.** Beside the official course, any user can hand-select content into a curated course or collection. Curation is actively encouraged, because many curators bring more perspectives than any program. The automatic course and the curated ones are compared on how well they work (D57).
5. **The return.** Course revenue enters the flow. Content a course uses counts as use for its authors, and a curator's selection counts as use too (D59). The price of the automatic course is a PROPOSAL (D56).
6. **The loop closes.** People who take the course practice what it teaches in real sessions. Those sessions are recorded and co-signed, and their Tips, Traps and designs flow back into the journal (§3.4.1), so the next version of the course is distilled from more practice than the last.

#### 3.4.3 Outputs become inputs: the protocol as a string

In Liberating Structures, a *string* is a sequence of structures in which the output of one becomes the input of the next. A 1-2-4-All produces ideas that a 25/10 Crowd Sourcing then ranks, and the ranked ideas become the invitation for the next step. The design of a string is the design of those handoffs.

The protocol is built the same way, as a string at the scale of the community. Each stage's output is the next stage's input:

| Stage | Output | Becomes the input of |
| --- | --- | --- |
| A session (a string of structures, played) | Traces, RoTI, Positive Gossip, a Data Wash choice | The record |
| The record (§3.2, §3.3) | Co-signed, consented evidence, stored by pattern, string and setting | The practitioner's phase, and the journal |
| The journal (§3.4, §3.4.1) | Tips, Traps, Riffs and played designs, ranked by votes | The course |
| The course (§3.4.2) | Lessons, worked examples, a map of settings | New practitioners' sessions |
| New sessions | New traces and records | The journal again, one season richer |

Three properties of a good string carry over:

- **Nothing is typed twice.** Each handoff reuses what the previous stage produced, which is how "nobody has to type a record" (D124) extends to "nobody has to write the course".
- **The invitation carries forward.** A string's next question grows out of the last one's answers. Here, what the votes rank highest and what the evidence shows is missing (patterns with few Tips, settings with no played designs) become the community's next invitation.
- **Each loop leaves the group more capable.** This is the syntropic flow of §3.7 at the scale of the commons: the water is held high, and every pass touches more surfaces.

#### 3.4.4 How the string capitalizes the commons

Every pass through the string adds to a shared stock that no single member owns: co-signed records, ranked knowledge, a course, and the common pool's money. That stock is the commons' capital. It grows with use rather than being used up: a Tip read by a new practitioner is not consumed, and the session it inspires adds new evidence. Course revenue and certificate fees add to the pool (D59, D163). Use of a contribution in a co-signed session credits its author through the flow (D50, D168).

Ostrom's principles are the governance frame for the journal (D48). The table below reads them through the eight core design principles for cooperation adapted from Wilson, Ostrom and Cox, as uploaded by Javeline (uploads/hearth/352512c4-…, CC BY-SA 4.0, GlobalESD.org). How each principle is met is Claude's reading of the decisions: PROPOSAL (Javeline decides).

| Principle | How the string meets it |
| --- | --- |
| 1. Strong group identity and understanding of purpose | User groups are the certifying bodies, and each runs on its own charter (D142, D112). The purpose is shared: capacity made visible |
| 2. Fair distribution of costs and benefits | Payment follows use in a co-signed session, never recruitment (D168). Course and certificate revenue go to the pool, and nobody takes anything outside the flow (D59, D85) |
| 3. Fair and inclusive decision-making | The commons decides as user groups together, voting within each group (D166). Course votes come from members with a co-signed record (D193, PROPOSAL) |
| 4. Monitoring agreed behaviours | Every claim is shown with its evidence level (D161). The experiment's measures are published (D171), and the community-wide view becomes a public dashboard (D100, PROPOSAL) |
| 5. Graduated responses to helpful and unhelpful behaviour | Weak content sinks by votes and stays visible; removal is only for legal or safety reasons, by stewards from several groups (D180). Thresholds can be questioned at the equinox (D81) |
| 6. Fast and fair conflict resolution | Challenges are settled at the equinox; an unsettled threshold challenge goes to the commons (D81; D191, PROPOSAL) |
| 7. Authority to self-govern | Each community sets its own session splits and charter within a shared floor (D97, D112, D159). People own their data and choose its publication (D51, D205) |
| 8. Appropriate relations with other groups (nested levels) | User groups nest in the commons. The trust wire connects communities (D125). The LS Commons co-signs certificates, presumed (D201), and ShareAlike keeps every riff open (D62) |

### 3.5 Permissions and Access Control

PSLP includes a granular permission system, managed on the ledger and reflected in the Learning Journal, to ensure data sovereignty and control over who can access and share information. Permissions are managed dynamically, based on factors such as:

- **User identity:** individuals control their own data. They decide which information is shared publicly, shared within specific community circles, or kept private (D51, D205).
- **Learning progress:** as users gain experience, they may be given access to more design detail. For example, the depth of RoTI and design questions asked of a giver rises with their phase (D117). Progress is not a tag but the ladder of §3.6.2, from Despairing Cynic through Cautious Optimist and Rapturous Super-User to Maestro Minimalist (D23). Each step rests on ledger records, so it is visible, checkable and contestable by the community.
- **Roles:** roles are separate from progress. A steward is an organizer who takes responsibility that things happen in a user group (D176). Any user may ask to be recognized as a steward; requests are evaluated at the equinox gathering, and existing stewards admit new ones unanimously (D199). Stewards seal and sign; they do not rank higher on the ladder.
- **Community evaluation and trust:** governance follows stewardship recognized by peers, never earnings (D87). Votes that shape the official course or accept a new card count only from members with a co-signed record, one per person (D193, PROPOSAL).

The history of the record cannot be changed: every signature, correction and withdrawal is logged. What a person shows, and whether they stay in a record, remains theirs to decide. Anyone can correct an entry, withdraw it, or take themselves out of a record (D137). The accessibility and visibility of detail in the journal are governed by community norms, trust and individual consent.

### 3.6 Ethical Sharing, Attribution, and the Economy of Value

The PSLP is designed to promote ethical sharing and proper attribution of contributions. By recording the participants and process of learning events, the protocol provides a basis for crediting individuals and groups for their roles in knowledge creation and transfer.

The protocol aims to cultivate a regenerative economy of value, discovery, divestment and distribution within the learning community. This goes beyond traditional monetary exchange, recognizing and valuing diverse contributions such as:

- **Value creation:** documenting the successful application of structures, or the emergence of new insights, acknowledges the value created through collaboration.
- **Discovery:** the journal makes it easier to discover effective practices, novel applications and potential collaborators.
- **Distribution:** insights, knowledge, and potentially related resources or opportunities can be distributed throughout the network.
- **Divestment:** the system distributes financial resources throughout the community of practice, through the common pool and flow funding (§3.9).

These four flows describe what circulates in the community. The subsections that follow specify how value is credibly claimed, evidenced and transferred. That is the mechanism that makes attribution something participants can rely on, not merely something the system displays.

#### 3.6.1 Claims are cheap; evidence is costly

In a commons, claims are cheap and evidence is costly. Each recorded social learning event is an observation about the capacities of the people involved, shown with how well it is evidenced (§3.1). The ledger is an evidence archive: what people have actually done, in what contexts, and with what attested outcomes.

Events recorded under §3.3 attribute distinct roles, and each role is a distinct form of evidence:

- **The designer and deliverer:** the person or people who organized the group's time, attention, information processing and energy. In the protocol's terms, they are the organizational game designer of that event.
- **The players:** their engagement, contributions, reflections and Positive Gossip evidence their participation in the learning, and co-sign the event.
- **The Scribe and the witnesses:** they add evidence about the event's occurrence and basic details, shown at its evidence level.

The pattern across records, not any single record, is what makes a capacity claim credible.

#### 3.6.2 Reputation first, and the certificate that reads from it

The protocol leads with reputation, not certification. A practitioner's reputation is the accreting, emergent track record of what they have done and what others have attested: the pattern across records described in §3.6.1. It is always present, it is generated by play, and it is never sold. This is the honest, commons-compatible core: it requires no purchase, no licensing body, and no fee.

Certification is then the optional formalization that reads from reputation. A key design commitment: certification does not create capacity; it formalizes it. In conventional credentialing, the certificate comes first and enables the work; the PSLP inverts this. Its certificate is a declarable statement that the ledger now supports: this person's record meets a community-defined threshold, in these communities, as of this date.

Three separations make this work. They deliberately split what a fully local or fully centralized scheme would fuse:

1. **The criteria are shared: one developmental path for everybody.** Ironically for a protocol built on trust over hierarchy, the criteria are centralized. They are not a local menu, but a single shared rubric that every practitioner walks the same way (D22). The point is comparability: to have "some degree of expected competence", and to be able to "know where the blind spots and competence are". This standardizes the map of competence; it does not re-centralize authority. The rubric is the deck's Development Phases ladder. It reads four dimensions:
   - **Structures in use, computed rather than filled in.** For each person, each pattern moves through its own ecocycle: Gestation (never seen it), Birth (led through it), Maturity (hosted others in it), and Creative Destruction (enabled someone else to host it). "Patterns in use" is the count at Maturity or beyond (D29). The phases are Despairing Cynic (Unconscious Incompetence), Cautious Optimist (Conscious Naive), Rapturous Super-User (Conscious Competence) and Maestro Minimalist (Unconscious Competence); beyond that, one is simply a maestro. The thresholds are in D23. The deck has no ceiling: community cards count, so the ladder is not captive to the structures in the book. The core stays constant (the ten principles, the icons, their Min Specs), and everything else is a community riff on top (D26, D27).
   - **People reached:** the breadth of distinct practitioners and groups the work was actually done with, not the number of sessions delivered.
   - **Diversity of settings:** the range of contexts (corporate, community, family, cross-cultural, conflict, celebratory) in which the structures have been run.
   - **Design-goal achievement:** the degree to which the practitioner accomplished their design goals. We are "not using these things in a vacuum". Much group work is legitimately about vibes, trust and getting to know one another, and those are real design goals. But they count only as intended, designed toward, and effectively accomplished. Credibility is claimed against goals met, not against time spent.

   **Only structures in use set the phase and unlock the certificate.** The other three dimensions are shown on the record as plain counts, without thresholds. The commons may add thresholds for them later, from what the pilots show (D25, D179). A practitioner is declared at a phase, not assigned a tag. The phase is computed separately at each evidence level and shown side by side (for example, co-signed phase and phase including claims). The certificate uses the co-signed phase (D30).

2. **The certificate is issued from the record, and the seal is an optional endorsement.** A certificate of practice is issued from the computed record. It states the record and its evidence profile, never competence (D160). A practitioner can buy one once their co-signed phase reaches the shared minimum. Below that, the record stays visible in the app for free (D162).

   The certificate is signed by the relevant user groups, each signing through its stewards, and, presumed until it says otherwise, by the LS Commons. If the LS Commons does not sign, the user groups sign alone (D201). Whether the witnessing peers also sign is an ASSUMPTION (D201).

   On top of that, a user group's seal is an optional endorsement: a stronger claim for those who want it, not the thing that makes the certificate valid. It comes in the second pilot or later (D158). The community, not the platform and not the deck author, stands behind it; the deck author holds no standing seat (D35). The criteria (item 1) say what counts; the signed record is the proof; the optional seal is an added endorsement.

3. **Activation is demand-driven.** A certificate becomes useful and hireable when there is demand: a hiring request, a client's brief. Until then, it rests as a reading of reputation.

Two further commitments keep it from becoming a cash grab:

- **The pay-to-win path is structurally unavailable.** Because the evidence trail is the reputation and the certificate only reads from it, there is no shortcut to purchase. What is never for sale is the claim. Money buys learning, practice, and a formal document of an earned record; it cannot buy a record that was not earned (D72).
- **The Creative Commons case, corrected to the actual licence.** The Liberating Structures material is licensed CC BY-SA 4.0. There is no non-commercial term, so selling courses and services built on it is allowed (D61). The constraint on the protocol therefore does not come from the licence forbidding sale; it comes from the protocol's own commitment that the claim of capacity is never for sale. Certifying a record is free. A fee attaches only to the certificate of practice, the formal document of an earned record that an employer or L&D budget holder asks for. There is one fee everywhere, set and changed only by the commons (D69). The protocol's market value grows with evidence, not with purchase.

#### 3.6.3 A legitimate market layer

The protocol's commons does not require the exclusion of market exchange. It requires that exchange be structured so that it does not extract from the commons. Three market models are therefore legitimate:

- **Pay-to-learn:** a participant with more money than time may pay for design assistance (coaching, structure design, practice scheduling) that makes their learning journey more effective. The payment buys development of capacity. The resulting evidence enters the ledger in the same form as evidence produced without payment.
- **Pay-to-play:** where an event has costs (materials, space, travel), participants may contribute toward them. Distributing such funds is itself one of the divestment flows of §3.6.
- **Pay-to-certify:** what is paid for is not the certification itself, since certifying a record is free. It is the certificate of practice: the formal, verifiable document of an earned record. It is issued to the practitioner, who shows it to an employer or L&D budget holder. There is one fee everywhere, set and changed only by the commons (D69), and it goes in full to the common pool. This is the protocol's intended economic engine: a cash grab that goes to the community of practice, never to the certifier. What the pool does with the money is described in §3.9.

All three models are constrained by an omni-win requirement: the transaction must be structured so that all parties' capacities grow, the payer's, the payee's and the community's. A facilitation engagement that leaves both payer and payee more capable is omni-win; one that merely transfers attention from one party to the other is not.

The Liberating Structures repertoire is designed to satisfy this constraint by construction. The structures are simple enough that the engagement itself builds capacity in everyone present, including the payee. Paid practice should therefore be delivered many-to-many wherever possible, with one design serving many learners, rather than as one-to-one extraction.

#### 3.6.4 First-class events: practice in the protocol's own method

A social learning event is first-class when it directly trains the capacities the protocol depends on. Practice and training in the Liberating Structures themselves is the paradigmatic case.

The field guide is explicit about how structures are learned: through direct experience, practice and peer debriefing, not instruction alone. Every LS practice session and training is therefore embodied skill acquisition. Its record on the ledger directly evidences the development of the attention-designing capacity that the §3.6.2 certificate formalizes.

This makes the protocol self-referential in a productive sense: the ledger records the events that train its own validators. The validator is trained by the protocol's own subject matter, and the certificate rests on the protocol's own evidence. No external credentialing body is needed, because the ledger is the evidence archive. The recursion is sound precisely because the evidence is attested by participants rather than issued by an authority.

**Intended audience and the value-first principle.** The protocol's primary users are user-group organizers and practitioners out in the field: people already running these structures. Everything the protocol does (collection, attestation, certification) serves one first obligation: making it easier for them to design and develop their interventions.

The protocol delivers that value first, and transparently. In exchange, it builds together with them a repository of knowledge, a commons whose value is significantly greater than the sum of its parts, as a co-benefit. The value delivered to the field must be smooth, transparent and overwhelming; the knowledge repository is what the field builds as the byproduct. Collection is never the point of the protocol; usefulness is.

The same principle reaches practitioners' own AI tools. Anyone can download one package of everyone's permitted notes, transcripts and photos from a session, for example as an MCP server (D65, D139). AI agents only suggest labels: countable evidence and everything that pays come from fixed rules (D182).

#### 3.6.5 Trust propagation and network topology

Attribution cannot remain local. Evidence about a facilitator's capacity in one community should inform trust in another, with appropriate attenuation. A record witnessed directly by a participant is stronger than the same record as reported by a second party, who in turn is attested by their own witnesses. Trust therefore propagates through the social graph, decaying with distance, with confidence weighted by the reliability of the intermediaries carrying it.

This is fundamentally a small-world propagation problem. Communities of practice have the topology that small-world networks describe:

- high local clustering: tight-knit practice groups that know their members well;
- short average path lengths: a small number of bridge figures (stewards, certified designers, cross-community facilitators) connect most of the network.

Evidence needs no more than a few hops to reach almost any community. The protocol's task is to let it propagate with its integrity metadata intact, and to let hub nodes be recognized by the community rather than assumed by the platform. The network pattern cards give people words for these positions: for example "Bridging the Gaps" for a boundary spanner, or "Gatekeeper" for the only link between two sides. Practitioners can opt in to see their own position, and groups reflect on their webs at each equinox (D198).

> **[LOCATED 2026-09-28, by Mujo's Kitestring proposal, §07** (ASSUMPTION: the proposal is not in the project folder).
>
> In the NAOMS implementation, the small-world gap is not merely conceptual. All the trust primitives exist: signed chains, co-signing by role, FROST hive credentials, and selective-disclosure R-Cards. But nothing writes trust edges: two functions have no production caller, and trust propagation returns zero for every pair. §07 located the gap in code; it did not close it.
>
> The fix benefits every NAOMS app:
>
> - write trust edges from accepted, counter-signed credentials;
> - feed each contact's trust flow from propagation;
> - verify the credential behind each reference.
>
> Mujo (NAOMS) builds it. It must ship before a second community's seals are recognized, and no later than the end of the hatch (D125). Until it ships, yes-or-no recognition between communities is the honest floor, and no trust-weighted numbers should be shown. Displays that cross communities say "not yet measured" instead of showing zero (D102, D173). That floor is exactly the attenuated, hop-decayed propagation this subsection describes.]

**Collection and presentation render independently.** The application that does the registration, attestation and evidence collection does not have to be the application that presents the public journal. The collection side feeds a separately designed presentation that:

- is more cleanly organized;
- is usable across skill levels;
- shows the state of the community of practice, and how its patterns are actually used, better than the existing community website does.

This separation is deliberate: the ledger's job is evidence; the journal's job is knowing.

#### 3.6.6 The regenerative character of the economy

The regenerative character of this economy is not a metaphor. Each recorded event produces more evidence than it consumes: the attestation required to record an event is itself a community practice that builds the very capacity the protocol is documenting. The currency of the network is not a token but capacity made visible: attributable, checkable, and, when its holder wishes, marketable. Attribution built on social consensus and community evaluation is what turns the four flows (value creation, discovery, distribution, divestment) from a description of values into a working protocol. Its thermodynamic signature is described next.

### 3.7 Syntropy: The Protocol's Organizing Principle

Entropy is the tendency of closed systems toward disorder and lost possibility: energy dissipates, potential flattens, and the number of things a system can do shrinks. The classic image is water flowing downhill. Held high on the landscape, it can turn mills and feed organisms across its slow descent. Once it reaches the sea, that entire category of possibility is gone, no longer up for grabs.

Syntropy names the opposite capacity: the ability of open, energy-importing systems to build local order over time, against the default drift. The term was introduced by the Italian mathematician Luigi Fantappiè in the early 1940s.

In ecological practice, the image is "holding the water high in the drainage". Vegetation is literally the cellulose gauze of nature: it holds water high in the landscape, so that, as the water moves slowly, it touches more surfaces and feeds more organisms. At scale it powers the biotic pump: vegetation seeds clouds, clouds create rain, and the possibility space for more life expands. A syntropic system does not merely resist decay; it increases the possibility space of its surroundings by maintaining and expanding order.

The organizing goal of an organizational game is syntropic. A well-designed structure is a device for creating what we call syntropic flows: flows of attention and information that, as they move, leave the group more organized and more capable than they found it. The structure includes the design brief that frames the context, the storyboard that organizes the intervention, and the structure itself that carries the play.

Organization, in this sense, is not control imposed on a group. It is the group's own thinking being given beneficial flows: a collective metacognitive move, in which the group thinks about its own thinking and designs the conditions under which emergence becomes more probable. Emergence is not the absence of structure; it is structure designed to make emergence more probable.

The PSLP adopts syntropy as its measurability criterion in three places:

1. **Per event:** the Reflection field (§3.3) asks whether the event was syntropic. Did it leave the group more organized and more capable, with a larger possibility space than it entered with? Community evaluation supplies the attestation.
2. **Per practitioner:** a practitioner's evidence pattern is syntropic when, across their recorded events, the groups they have designed for show growth in capability and optionality over time. The practitioner is holding the water high for the communities they serve.
3. **Per community:** by accumulating traces, the Learning Journal works as a knowledge biotic pump. It holds the community's knowledge "high in the drainage" (visible, referenceable, reusable), so that it can flow through more practitioners, more contexts and more generations of events than a single meeting could have touched. Each trace read by a new practitioner is water touching a new surface. The journal is the infrastructure by which a community's learning creates more learning than it consumed. Pilot 1 holds the water from the first session, so that the journal opens full (§3.4.1).

A PSLP learning event is regenerative in exactly this syntropic sense: a structure that, played well, leaves the community more organized, more ordered, and with a larger possibility space than it had before. That is checkable, and it is attributable. This is why the protocol's economy of value is regenerative rather than merely aspirational.

### 3.8 Privacy, Data Sovereignty, and Security

Ensuring privacy, data sovereignty and security is critical. The inherent transparency of a blockchain must be balanced with the need for confidentiality and user control.

- **Privacy as each person's choice:** after a session closes, each contributor chooses, entry by entry, whether to publish under their name, publish anonymized, or withhold (Data Wash, D51). The choice and the permissions behind it apply from the first data in, in the first pilot. They cover everything that comes in, including imported archive material, session records and the session package, not only journal entries (D205).
- **Privacy by design:** although records of learning events are on-chain, sensitive data can be kept off-chain with references on the ledger, or encrypted using techniques such as Zero-Knowledge Proofs (ZKPs) or Trusted Execution Environments (TEEs) where feasible. Participant data can also be pseudonymized or anonymized. The system of justification field is naturally shareable in summary; the underlying artifacts and reflections can be permissioned in layers.
- **Data sovereignty:** users keep control over their personal learning data and identity, deciding how it is shared and used, in line with their preferences and community agreements. Anyone can correct an entry, withdraw it, or take themselves out of a record (D137). This follows the principle of "nothing about us without us".
- **Security:** the DLT protects the integrity of the learning records' history through cryptographic proof and distributed consensus. Robust access controls based on cryptography can protect sensitive information.

Developing this aspect requires careful design, potentially drawing on advances in privacy-preserving technologies in the DLT space.

### 3.9 Money and Governance in the Pilots

The protocol's economy is designed to be omni-win: the common pool is a player too, and its needs are counted alongside everyone else's (D79, PROPOSAL). This section states the mechanism; every number is in the Decisions and numbers table.

**Money follows rules, not judgement (D161).** Every claim is shown and judged by people, but money moves only by published rules and signer thresholds.

**In pilot 1, the pool only fills.** Certificate fees, and any other commons revenue, accumulate in the common pool, and nothing is paid out (D163). The pool's keys are held by the three pilot stewards, any two of whom must sign, so nobody moves money alone (D200). Neither the platform nor the deck author takes anything outside the flow (D85). Building the platform before revenue is funded from outside the flow: Javeline proposes requesting ecosystem funding (D206, PROPOSAL).

**Flow funding starts in two steps (D165, D169):**

1. The pool holds enough to cover one season of the survival thresholds of every practitioner who has requested flow funding.
2. The next equinox gathering votes to start it. The deck author abstains on the flow rules.

From then on, recipients publish their survival and thriving thresholds, which are questioned and settled at the equinox (D81). Grants from the pool are allocated by several signers from different groups, never to a signer, their group, their family or a payer (D164, D190). People's shares are settled by the Happy Money Story procedure (D167). Payment is for contribution, never for recruitment.

**The commons decides, on the equinox cycle.** The work happens through the season. At the spring and autumn equinox, the community gathers to settle thresholds, start or adjust flows, evaluate steward requests, welcome new communities, and review the experiment's measures and its gaming risks (D164, D166, D199, D203).

"The commons" means user groups deciding together. Members vote within their own user group, and a decision passes when enough groups each reach a majority, signed by stewards from several groups (D166).

**The founder's limits.** Javeline nominates the three pilot stewards once, at rollout. That power ends when they are seated, and they are removable like any steward (D199). Javeline has no standing seat in sealing (D35) and abstains on the flow rules (D169).

**Defences against gaming (D183–D197, D203).** The cheapest attack is a small circle that co-signs itself. Before any money moves, the circle is held back by four rules:

- one appreciation budget per member (D183);
- one counted account per person (D184);
- no pay for use when the author was in the session (D187);
- appreciation-only credit for sessions outside the pilot community (D172).

Further defences are PROPOSALS, for example: only announced sessions count for money (D186), and payout inputs are fixed and checked by signers (D197). The risks that remain are stated openly and reviewed at each equinox (D203).

**Two pilots (D158, D134):**

- **Pilot 1** proves recording, computed reputation and record-based certificates of practice, with real money going into the pool. It also includes Data Wash privacy and the session package for AI agents. It runs in LS Go Online and the Wise Crowds Design Call, counted as one community (D136, D157).
- **Pilot 2** adds the Learning Journal and the automatic online course, seeded by pilot 1 (§3.4.1), and the optional seal.

## 4. Challenges and Future Work

Implementing a Proof of Social Learning Protocol presents several challenges:

- **Technological complexity:** designing and building the DLT and the wiki interface with the required privacy, security and permission features is complex. User-friendly interfaces are needed to make the technology accessible to a broad community.
- **Social adoption and cultural shift:** such a system requires a cultural shift toward more explicit documentation, sharing and collaborative validation of learning. Acknowledging resistance or apprehension from new users is essential.
- **Defining and measuring learning:** although LS offers discrete structures, capturing the nuances of embodied practice, experiential learning and emergent outcomes remains challenging. Developing community-agreed metrics and evaluation processes is key. Two instances are open:
  - thresholds for the three rubric dimensions that do not yet set the phase (D25);
  - measuring syntropy, as a per-event, community-attested assessment of whether the event expanded the group's possibility space. Community evaluation is the instrument; the open work is converging on a shared scale or vocabulary for it.
- **The difficulty of articulation:** the subject matter is, by its nature, "super easy to use, hard as anything to explain". The protocol's interfaces and the Learning Journal must carry articulation that designers themselves struggle to produce. The system of justification field is a first answer, but the wiki must do real design work.
- **Trust propagation across communities:** the small-world model for how evidence and attribution travel across clustered local communities with few bridging nodes (§3.6.5) is not yet formalized. This is a research item: trust-decay functions across hops, hub recognition, and the governance of bridging roles. The engineering prerequisite, the trust wire, has an owner and a deadline (D125).
- **Sustainability and governance:** the first pilot's governance is now designed (§3.9). What remains open: the starting values the pilot group confirms (D170), the flow rules the commons adopts (D169), and how a livelihood's sufficiency and stewardship are read from the data (D86, D87).
- **Legal and regulatory landscape:** the evolving legal status of decentralized organizations, and the use of DLT for non-financial purposes, need to be navigated. Concrete open items include checking the refund rule against EU consumer law, the lawful basis for transcribing old recordings that show other people, and a trademark check before the first certificate is sold (D121, D19, D204).

Future work involves:

- refining the protocol design;
- building and testing the two pilots;
- engaging the LS community in a participatory design process;
- research into advanced privacy features, different DLT platforms and user-friendly interfaces;
- formalizing the small-world trust-propagation model;
- building community agreement on syntropy assessment.

## 5. Conclusion

The Proof of Social Learning Protocol offers a compelling vision for using DLT to support and amplify social learning within communities of practice like Liberating Structures. By using social learning events as the validation mechanism, the protocol aligns the technology with the community's core activities and values.

This revision adds the frame that makes the alignment visible. The events the protocol records are organizational games; the capacity they exercise is design; and the record itself is an evidence archive of traces, in which the community sees and senses its own system. Certification is not a product the protocol sells but a property the evidence acquires. And the protocol's economy is syntropic in a checkable sense: it rewards, records and amplifies exactly those structures and practitioners that hold the water high, leaving every group they touch more organized, more capable, and with a larger possibility space than they found it.

The integrated Learning Journal, seeded by the first pilot's records, can become a powerful tool for knowledge sharing, skill development, and a regenerative economy of value based on collaboration, attribution and the ethical distribution of insights. Significant technical and social challenges remain. But the potential for building a more transparent, equitable and vibrant learning ecosystem makes this a worthwhile endeavor, and, by the protocol's own criterion, a syntropic one: the act of recording learning makes more learning possible.

## Appendix A: Organizational Game Design: Key Concepts

Distilled from the "Press Start: Organizational Game Design" deck (Papa Pita, 2026). ASSUMPTION: the deck is not in the project folder. This is the practitioner's vocabulary underlying §3.

**Organizational games.** The broad category of socially constructed rule systems that organize a group's time, attention, information processing and energy. Liberating Structures are the most mature, well-refined example; almost all human behavior can be read as game-like in this sense. The design question is how to distribute and clear away power so that games can be good. That is why the frame is games and game design, rather than mere facilitation technique.

**The metagame.** The games that help you figure out which game to deploy. It has two sides.

**The Design Brief (situational assessment).** The five P's, battle-tested across about 200 help requests:

- **Place:** the context; the arena the intervention finds itself in.
- **Problem:** the tension driving change; the baseline; why leaving things as they are is a horrible idea.
- **Purpose:** the ideal state, the "definition of awesome"; the speculative-fiction daydream that opens the possibility space.
- **Participants:** those with influence and power, those with expertise, and those who will be affected; the players, whose play the game exists to create.
- **Practicals:** constraints mapped by domain. Fixed constraints are boundaries or walls. Governing constraints are levers, knobs or gears. Enabling constraints are resources (gravity is an enabling constraint). In practice: deadlines, cadences, availability windows.

**The Design Storyboard (design and deploy).** The practitioner's most-used structure; "the alpha and omega". Each step has these fields:

- **Agenda item:** what you'll call it to a lay person (they care about the artifact, not the mechanism).
- **Goal:** what this step is for; the design brief jams into this slot.
- **Invitation:** the question placed at the center of the conversation to steer it.
- **Interaction pattern:** the rules: participation distribution, time, space, steps.
- **Artifacts, materials, space:** maps (for example the Ecocycle) and traces (for example Simple Ethnography, 25/10 Crowd Sourcing, What I Need From You).
- **System of justification:** why these elements, and why this design; how the choices line up into a coherent "slam dunk" on the goal.

**Traces vs. agreements.** Agreements are snapshots; traces are records of motion, artifacts that let you see and sense the system. The protocol's native data unit is the trace.

**Syntropic flow.** A flow of attention and information designed so that, as it moves, it leaves the group more organized and the possibility space larger. Emergence is not the absence of structure but structure designed to make emergence more probable: the opposite of the "tyranny of structurelessness".

**The irony.** "Super easy to use, hard as anything to explain." This is why the field's answer is to get people talking to each other (the structures do the explaining), and why a shared evidence archive is not a luxury but a necessity for a practice that cannot narrate itself.

## Change log

**v2.4 (2026-10-08).** Aligned to the decisions through D207, after the consistency check in 10-pslp-2.3-check.md:

- **New §3.4.1:** how pilot 1 initializes the Learning Journal (D207, PROPOSAL).
- **New §3.4.2–§3.4.4:** how the journal bootstraps the online course; outputs becoming inputs, as in a string; and how that capitalizes the commons, read through Ostrom's principles (mapping: PROPOSAL).
- **New §3.9:** money and governance in the pilots: the pool, flow funding, the commons, the equinox, founder limits, gaming defences, and the two pilots.
- **Roles:**
  - The person who captures a record is a Scribe; "steward" is kept for the governance role (§3.2, §3.3, §3.5, §3.6.1).
  - Designer and deliverer are nested, and guests are witnesses (§3.3).
- **Evidence:**
  - The ledger admits every claim and shows its evidence level; only co-signed records count toward phase and certificate (§3.1).
  - Positive Gossip is named as the co-signature (§3.2).
- **Records:**
  - "Immutable" is replaced by a tamper-evident history, with correct, withdraw and take me out (§3.1, §3.5, §3.8).
  - Data Wash is a field in the data model and applies from the first data in (§3.3, §3.8).
- **The ladder and certificate (§3.5, §3.6.2):**
  - The progression uses the ladder names, and stewardship is a recognized role, not a level.
  - Only structures in use set the phase.
  - The LS Commons signature is presumed.
- **Other corrections:**
  - The certificate is issued to the practitioner (§3.6.3).
  - The trust wire's owner and deadline replace the effort estimate (§3.6.5).
  - Syntropy is attributed to Luigi Fantappiè, early 1940s (§3.7).
  - The deck licence, the session package for AI agents, and the network pattern cards are added.
- **Housekeeping:**
  - Values are replaced by D-number references.
  - The duplicated change log text is removed.

**v2.3 (2026-10-08).** Aligned to the Certified Practitioner response v2 (Oct 7):

- The header now says v2.3.
- §3.6.2: the certificate is issued from the computed record and states the record, not competence, with the user-group seal as an optional endorsement (not the thing that makes it valid). It is signed by the relevant user groups and the LS Commons.
- §3.6.2 and §3.6.3: there is one fee everywhere, changed only by the commons; "diploma" is renamed "certificate of practice".

**v2.2 (2026-09-29).** Corrected per the Certified Practitioner response:

- §3.6.2: the ladder thresholds are computed per pattern via the ecocycle, and the deck is uncapped (core constant, community riffs on top).
- The CC case is corrected to CC BY-SA 4.0: there is no non-commercial term, and the case is that the claim is never for sale, not that selling is forbidden.
- Certifying a record is free; the fee is only on the diploma.
- §3.6.5 is re-labelled LOCATED, not RESOLVED: the trust wire must still ship, and yes-or-no recognition is the honest floor until then.

**v2.1 (2026-09-28).** Kitestring integration:

- §3.6.2 re-worked to reputation first, with a centralized rubric and a decentralized seal:
  - the criteria are one shared, multi-dimensional Development Phases rubric;
  - the seal is a user group's attestation;
  - the deck author holds no standing seat;
  - the certificate is activated by demand.
- A community-governed pay-to-certify fee was added, with proceeds flowing to the commons, never to the platform or the deck author (§3.6.2, §3.6.3).
- Collection and presentation independence was added (§3.6.5).
- Intended audience and the value-first principle were added (§3.6.4).
- The §3.6.5 pending slot was resolved by Mujo's Kitestring §07 finding.

**v2.0 (2026-08-23).** Organizational Game Design revision:

- Added §1.1 (capacity as organizational game design).
- Re-framed §3.1 as an evidence archive, with traces versus agreements.
- Added first-class events to §3.2.
- Extended the §3.3 data model (roles, system of justification, traces, syntropy reflection).
- Re-worked the §3.5 progression.
- Expanded §3.6: evidence archive, certification as formalized capacity, market layer, first-class events, and small-world trust propagation.
- Added §3.7, Syntropy as the organizing principle.
- Extended §4 and re-framed §5.
- Added Appendix A.
