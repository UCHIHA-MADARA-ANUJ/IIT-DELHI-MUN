# 07 — ORIGINAL SOLUTION ARCHITECTURE

> Purpose: Convert Brazil's policy and the AAWG common ground into an original, actionable regulatory architecture that can survive MUN debate, negotiation and resolution drafting.
>
> Critical distinction: The mechanisms in this document are Brazil/AAWG design proposals unless explicitly identified as an existing rule, forum, or documented State proposal. They are not presented as existing international-law obligations.
>
> Core design logic:
>
> PROHIBITION GATE → ASSURANCE CASE → OPERATING ENVELOPE → CONTINUING REVIEW → TRACEABILITY → INCIDENT LEARNING → PROTECTED VERIFICATION → CAPACITY / TRANSFER CONTROLS
>
> The goal is not to put every mechanism into one resolution. The goal is to have a coherent architecture from which the committee can select the strongest package.

---

# 1. THE PROBLEM THE ARCHITECTURE MUST SOLVE

A weak LAWS resolution says:

> "States should ensure meaningful human control."

A stronger resolution answers:

> How does a State prove that human judgement actually constrained the system?

A weak resolution says:

> "States should comply with IHL."

A stronger resolution answers:

> What process identifies an unacceptable autonomous function before deployment?

A weak resolution says:

> "States should monitor AI."

A stronger resolution answers:

> What happens when the software, model, sensor stack or mission changes after the original review?

A weak resolution says:

> "States should be transparent."

A stronger resolution answers:

> Which information is public, which is confidential, who reviews it, and what happens after an incident?

The architecture therefore targets seven governance failures:

1. Scope failure — States do not know exactly what falls inside the regime.
2. Prohibition failure — unacceptable systems are described too vaguely to prohibit.
3. Control failure — a human exists somewhere in the chain, but may not exercise effective judgement.
4. Lifecycle failure — a system is reviewed once and then changes materially.
5. Evidence failure — after an incident, nobody can reconstruct what the system was authorized and configured to do.
6. Verification failure — verification is either meaningless or so intrusive that States will reject it.
7. Implementation failure — obligations exist on paper but States lack testing, legal-review, procurement or technical capacity.

---

# 2. THE ARCHITECTURE IN ONE PAGE

Brazil/AAWG can explain the framework as eight linked gates.

### GATE 1 — CHARACTERIZE

Identify whether the system performs the critical autonomous functions covered by the framework.

### GATE 2 — CLASSIFY

Place the system/use into:

- Tier 1 — prohibited
- Tier 2 — strictly regulated

### GATE 3 — ASSURE

Create an Autonomy Assurance Case containing:

- intended use;
- autonomy functions;
- target categories;
- operating environment;
- limitations;
- failure modes;
- human-control arrangements;
- legal-review findings;
- testing evidence.

### GATE 4 — BOUND

Assign an Autonomy Operating Envelope covering:

- target;
- place;
- time;
- scale;
- environment;
- communications assumptions;
- intervention/deactivation conditions.

### GATE 5 — AUTHORIZE

Require legal review, testing and procurement/deployment authorization before the system enters operational use.

### GATE 6 — MONITOR

Preserve logs, monitor performance and trigger additional review after material change or serious incident.

### GATE 7 — VERIFY / INVESTIGATE

Use a graduated verification ladder and a serious-incident mechanism without requiring indiscriminate disclosure of sensitive military information.

### GATE 8 — LEARN / ADAPT

Use incidents, technology change and review cycles to update national controls and the international framework.

---

# 3. THE ASSURANCE CASE IS THE CORE ORIGINAL IDEA

The most important improvement over a generic "legal review" provision is to make the State assemble an Autonomy Assurance Case.

This is a proposed mechanism.

It is not an existing treaty requirement.

The idea is simple:

> A State should not merely say its system is lawful. It should maintain evidence supporting that conclusion.

The package can contain:

1. system identity/version;
2. intended mission;
3. autonomy functions;
4. target classes;
5. operating envelope;
6. environmental assumptions;
7. known limitations;
8. foreseeable failure modes;
9. human judgement/control arrangements;
10. legal-review findings;
11. testing/evaluation results;
12. software/model change history;
13. cybersecurity controls;
14. operator training;
15. incident history where applicable.

### Why this matters

It turns:

> "We complied."

into:

> "Here is the evidence by which our compliance process can be assessed."

---

# 4. MECHANISM 1 — AUTONOMOUS WEAPONS IMPACT ASSESSMENT (AWIA)

## Problem

A State may assess a weapon legally but never build one consolidated record of:

- intended mission;
- autonomy function;
- target category;
- operating environment;
- foreseeable failures;
- control arrangements;
- testing.

## Proposed solution

Before development/deployment of a covered system, the State completes an Autonomous Weapons Impact Assessment.

### Minimum contents

- mission;
- autonomy function;
- target class;
- expected environment;
- geographic limits;
- temporal limits;
- engagement scale;
- human-control model;
- failure modes;
- cybersecurity assumptions;
- legal review;
- testing evidence.

### Critical trigger

The assessment is updated after a material modification.

### Strength

Creates one evidence spine connecting legal, technical and operational review.

### Weakness

It can become paperwork.

### Fix

Do not make the AWIA an isolated form.

Tie it to:

- deployment authorization;
- procurement;
- change control;
- incident review.

### MUN line

> "An impact assessment without an authorization consequence is paperwork; an impact assessment linked to deployment and material-change gates becomes accountability."

---

# 5. MECHANISM 2 — THE AUTONOMY OPERATING ENVELOPE (AOE)

## Problem

"Human control" becomes meaningless when the system receives a huge mission and is otherwise allowed to make highly consequential decisions.

## Proposed solution

Every regulated system receives a documented Autonomy Operating Envelope.

The envelope defines:

### WHO / WHAT

Permitted target categories.

### WHERE

Authorized geographic area.

### WHEN

Maximum operating duration.

### HOW MUCH

Maximum engagement scale or other applicable quantitative constraints.

### UNDER WHAT CONDITIONS

Environmental assumptions.

### WITH WHAT COMMUNICATIONS

Expected communication conditions.

### WHAT IF CONDITIONS CHANGE

Required halt, reassessment, intervention or deactivation response.

### Critical rule

Outside the envelope, the system must not initiate or continue the covered autonomous engagement.

### Why it is original enough for MUN

It translates "human control" into a machine-operable constraint.

It creates an auditable question:

> "What exactly was the system allowed to do?"

---

# 6. THE "ENVELOPE FAILURE" TEST

Before a system is cleared, ask:

1. Can the permitted target category be technically constrained?
2. Can the geographic boundary be enforced?
3. Can duration be enforced?
4. Can scale be limited?
5. What happens when the environment leaves validated assumptions?
6. What happens when communications fail?
7. What happens when sensors degrade?
8. Can the operator intervene where feasible?
9. Can the system be safely halted when a critical condition becomes invalid?

If these questions have no credible answers, the proposed control model is weak.

---

# 7. MECHANISM 3 — CONTINUING ARTICLE 36-STYLE ASSURANCE

## Legal discipline

Article 36 of Additional Protocol I is a treaty obligation for States Parties to that Protocol; it should not be described as universally binding on all States.

## Proposed architecture

Use Article 36 as a model for continuing legal review rather than pretending every State has the identical treaty obligation.

### Review stages

1. development;
2. acquisition;
3. pre-deployment;
4. material software/model change;
5. material mission change;
6. serious incident;
7. periodic reassessment.

### Core idea

> The reviewed system must remain sufficiently characterized after the review.

This is particularly important for adaptive machine-learning systems.

---

# 8. MECHANISM 4 — MATERIALITY TRIGGER MATRIX

A major original design improvement is to define when a change is material.

This is a proposed implementation tool.

### Low materiality

Examples:

- cosmetic interface changes;
- routine maintenance with no effect on critical functions.

### Medium materiality

Examples:

- sensor replacement;
- software optimization;
- non-critical integration change.

### High materiality

Examples:

- change to target classification;
- change to engagement logic;
- new sensor fusion affecting target selection;
- model-weight change affecting critical selection functions;
- changed autonomy mode;
- change expanding geography/time/target scope.

### Trigger logic

Low:
documented internally.

Medium:
targeted regression testing.

High:
renewed technical assurance + legal review + deployment authorization.

### Why it matters

Without a materiality rule, "re-review after modification" is either too broad or too weak.

---

# 9. MECHANISM 5 — MODEL / SOFTWARE CHANGE CONTROL

## Problem

The system approved on Day 1 may not be the system used on Day 100.

## Proposed rule

Material changes to:

- model weights;
- target classifier;
- engagement logic;
- sensor integration;
- autonomy mode;
- critical thresholds

trigger renewed assurance.

### Minimum evidence

- previous version;
- new version;
- change description;
- affected function;
- test results;
- failure-mode comparison;
- legal-review determination;
- approval authority.

---

# 10. ADAPTIVE AI: THREE CONTROL TIERS

A useful architecture for adaptive autonomy:

## TIER A — FIXED / BOUNDED

Critical targeting functions cannot change after approval without review.

Use where predictability is a core condition.

## TIER B — ADAPTIVE BUT CONTROLLED

Adaptation can occur only within a validated operating envelope.

Required:

- version logging;
- threshold controls;
- rollback;
- monitoring;
- revalidation.

## TIER C — SELF-MODIFYING CRITICAL TARGETING

Highly restricted or prohibited where the State cannot demonstrate sufficient predictability, controllability and legal compliance.

### MUN line

> "The question is not whether software learns; the question is whether a State can still characterize, constrain and legally assure what the weapon does."

---

# 11. MECHANISM 6 — THE LAWS COMPLIANCE REGISTRY

## Proposed architecture

A confidential or tiered international registry could record:

- system category;
- assurance status;
- broad operating limitations;
- responsible authority;
- legal-review status;
- testing status;
- serious incidents where reportable.

## Not required

The framework does not need:

- source-code publication;
- public technical manuals;
- sensitive deployment locations;
- vulnerabilities.

## Three-layer model

### PUBLIC

Aggregate information and national framework descriptions.

### CONFIDENTIAL

Detailed reporting available through agreed procedures.

### PROTECTED EXPERT

Technical examination by accredited reviewers.

### Core principle

> Transparency does not have to mean vulnerability disclosure.

---

# 12. MECHANISM 7 — PROTECTED TECHNICAL REVIEW PANEL

## Purpose

Some States will reject intrusive verification because sensitive data cannot be shared publicly.

A proposed solution is a Protected Technical Review Panel.

## Possible role

Review:

- testing methodology;
- operating envelope;
- change-control records;
- failure-rate evidence;
- model/version documentation.

## The panel does NOT

- command national forces;
- approve military operations;
- receive unrestricted intelligence;
- replace national legal review.

## Why it helps

It provides a middle layer between:

> "trust us"

and:

> "give us everything."

---

# 13. PROTECTED REVIEW SAFETY VALVE

A State could provide:

### Full public summary

What was reviewed.

### Confidential technical file

Evidence needed for specialists.

### Classified national material

Retained under national security procedures.

The international mechanism should assess assurance sufficiency, not demand unnecessary disclosure.

---

# 14. MECHANISM 8 — SERIOUS INCIDENT MECHANISM (SIM)

## Trigger events

A serious autonomous-system incident could include:

- civilian harm;
- unauthorized target engagement;
- loss of control;
- unexpected engagement;
- major software failure;
- cyber compromise affecting critical functions;
- material deviation from the operating envelope.

## Required response

1. preserve relevant records;
2. prevent further loss of evidence;
3. conduct national investigation;
4. determine whether the system remains deployable;
5. assess whether a material change/review trigger exists;
6. report under the framework where applicable.

## International layer

A designated focal point could receive reports and produce:

- anonymized lessons learned;
- recurring-risk patterns;
- technical themes;
- recommended safeguards.

---

# 15. THE INCIDENT → REVIEW LOOP

This is one of the most important pieces of the architecture.

INCIDENT

↓

EVIDENCE PRESERVED

↓

INVESTIGATION

↓

ROOT-CAUSE ANALYSIS

↓

SYSTEM / DOCTRINE / TRAINING CHANGE

↓

REVALIDATION

↓

DEPLOYMENT DECISION

↓

AGGREGATE LESSONS LEARNED

This prevents every incident from becoming a dead-end report.

---

# 16. MECHANISM 9 — EMERGENCY ABORT STANDARD

## Problem

A control requirement is useless if the system cannot be stopped when critical assumptions become invalid.

## Proposed requirement

Regulated systems should have a tested response appropriate to context, such as:

- abort;
- deactivation;
- return;
- safe loiter;
- handover.

## Important qualification

Not every system can use the same emergency response.

For time-critical defensive contexts, an immediate "human approves every engagement" rule may be operationally impossible.

Therefore:

> The standard should be context-specific but tested.

---

# 17. THE "ABORT WITHOUT COMMUNICATIONS" TEST

Every regulated system should be asked:

> What happens if communications are lost?

Possible design requirements:

- terminate engagement;
- transition to a predefined safe state;
- remain inside the operating envelope;
- return/handover;
- cease use of force.

The exact response depends on the system and context.

The universal requirement should be:

> communications loss cannot silently expand the system's authorized autonomy.

---

# 18. MECHANISM 10 — PROCUREMENT GATE

## Why procurement matters

Procurement is one of the points at which abstract commitments can become contractual requirements. SIPRI's 2026 work specifically identifies procurement as a mechanism through which States can give effect to responsible military-AI commitments and recommends clearer supplier expectations. 

## Proposed procurement gate

A State should not acquire a covered system without evidence of:

- legal review;
- testing;
- system limitations;
- cybersecurity;
- change control;
- accountability assignment;
- supplier documentation;
- maintenance/update procedures.

## Procurement question

> "Can the State prove before buying the system that it can govern the system?"

That is a powerful Brazil line.

---

# 19. MECHANISM 11 — SUPPLIER RESPONSIBILITY CLAUSE

## Proposed contractual requirements

Supplier contracts can require:

- notification of material changes;
- disclosure of relevant limitations;
- update control;
- audit rights;
- cybersecurity requirements;
- incident-investigation support;
- protection against unauthorized modification.

## Legal caveat

International responsibility remains primarily a matter for States and applicable international law.

Supplier provisions are an implementation bridge, not a claim that private companies replace States as the international-law addressees of treaty duties.

---

# 20. MECHANISM 12 — REGIONAL TESTING & ASSURANCE HUBS

## Problem

A global rule is difficult to implement if only technologically advanced militaries can perform expensive testing.

## Proposed mechanism

Regional or multinational centres can support:

- legal-review training;
- adversarial testing;
- cyber assurance;
- model evaluation;
- operator training;
- technical standards exchange.

## Important political advantage

Capacity-building becomes part of the architecture rather than a closing paragraph that says:

> "Developed States should help developing States."

---

# 21. REGIONAL HUB GOVERNANCE

A regional hub could be governed by:

- participating States;
- technical experts;
- legal experts;
- rotating oversight;
- confidentiality rules.

It should not become:

- a command authority;
- a weapons procurement agency;
- a military inspection force.

Its function is assurance capacity.

---

# 22. MECHANISM 13 — CONFIDENCE-BUILDING PACKAGE

Instead of beginning with intrusive inspections, States could exchange:

- terminology;
- national review methodologies;
- general testing concepts;
- training practices;
- aggregate incident information;
- non-sensitive operating principles.

This helps create a common language before stronger verification is politically feasible.

---

# 23. THE VERIFICATION LADDER

Verification should be graduated.

## LEVEL 1 — NATIONAL PROCESS

- legal review;
- authorization;
- testing;
- training.

## LEVEL 2 — TRANSPARENCY

- national framework summaries;
- aggregate reporting.

## LEVEL 3 — PEER EXCHANGE

- experts compare methods;
- voluntary demonstrations;
- technical workshops.

## LEVEL 4 — INCIDENT REPORTING

- serious incidents;
- lessons learned.

## LEVEL 5 — PROTECTED TECHNICAL AUDIT

- methodology;
- records;
- assurance evidence.

## LEVEL 6 — NARROW INTERNATIONAL INSPECTION

Potentially available only where States agree and security concerns can be managed.

### Principle

> Start with process evidence and build toward deeper verification rather than making intrusive inspection the entry requirement.

---

# 24. MECHANISM 14 — COMPLIANCE PACKET

A proposed State-level LAWS Compliance Packet can unify:

1. AWIA;
2. legal review;
3. operating envelope;
4. test results;
5. model/version identity;
6. operator training evidence;
7. procurement documents;
8. change history;
9. incident history;
10. authorization record.

The Compliance Packet is the record that a State can use to demonstrate due diligence.

---

# 25. "ASSURANCE CASE" VS "COMPLIANCE PACKET"

Do not confuse them.

### Assurance Case

Why the State believes the system is safe/lawful within the defined scope.

### Compliance Packet

Evidence that the required procedures were actually completed.

The first is the argument.

The second is the evidence trail.

Together:

> ARGUMENT + EVIDENCE

---

# 26. MECHANISM 15 — CONTROL CONTINUITY TEST

This is a proposed AAWG test.

A system passes only if human judgement remains effective across the lifecycle.

Test at:

### BEFORE USE
Can the human define the mission and limits?

### DURING USE
Can the operator understand relevant system status?

### WHEN CONDITIONS CHANGE
Can authority reassess?

### WHEN COMMUNICATIONS FAIL
Does the system remain inside defined limits?

### WHEN A CRITICAL ERROR OCCURS
Can the system be interrupted or move to an appropriate fail state where feasible?

### AFTER USE
Can the State reconstruct who authorized what?

This converts "human control" into a lifecycle test.

---

# 27. MECHANISM 16 — AUTOMATION BIAS CHECK

A human can formally retain authority while functionally treating the system as infallible.

Therefore proposed assurance should include:

- operator training;
- uncertainty/limitation awareness;
- override training;
- interface testing;
- doctrine review;
- time-pressure testing;
- post-use audit.

### Test question

> "If the human disagrees with the machine, can the human realistically override it without the system, interface, doctrine or command structure making the override meaningless?"

---

# 28. MECHANISM 17 — THE MATERIAL CHANGE TRIGGER

Create one simple rule:

> If a change could materially affect target selection, engagement, control, predictability, operating boundaries or expected effects, reassessment is triggered.

This can include:

- software;
- model;
- sensor;
- mission;
- geography;
- duration;
- target class;
- scale;
- communications architecture.

The exact threshold can remain nationally implemented while the international framework defines the common trigger concept.

---

# 29. MECHANISM 18 — DEPLOYMENT AUTHORIZATION GATE

Before deployment, the responsible authority confirms:

- classification;
- legal review;
- testing;
- operating envelope;
- human-control arrangement;
- emergency response;
- cybersecurity;
- accountability assignment.

The key idea:

> Legal review should connect to operational authorization.

Otherwise a review may exist on paper while deployment proceeds independently.

---

# 30. MECHANISM 19 — REVIEW / SUNSET TRIGGER

A review should automatically be triggered by:

- serious incident;
- major technology change;
- new autonomy capability;
- repeated control failures;
- new evidence showing an existing restriction is insufficient;
- major expansion in the operating envelope.

A review does not necessarily mean prohibition.

It means:

> the rule must be reconsidered against new evidence.

---

# 31. MECHANISM 20 — TRANSFER "ASSURANCE PASSPORT"

This is a more ambitious original proposal.

For a regulated system transferred between States, a State could provide a standardized Assurance Passport containing:

- system/version;
- approved operating characteristics;
- legal-review status;
- testing status;
- limitations;
- prohibited modifications;
- update procedure;
- responsible supplier;
- required operator training;
- incident/update history.

## Benefit

The recipient does not start from zero.

## Safeguard

Transfer of the passport does not authorize transfer of prohibited capabilities.

---

# 32. WHY TRANSFER CONTROLS BELONG IN THE ARCHITECTURE

Autonomous-weapons governance does not stop at deployment.

Potential risks include:

- diversion;
- unauthorized modification;
- uncontrolled software updates;
- component substitution;
- transfer to actors with lower assurance capacity.

The regime can therefore connect:

transfer control
→ end-user control
→ software/update security
→ assurance continuity

---

# 33. MECHANISM 21 — POST-TRANSFER REVALIDATION

The recipient State should confirm:

- operating environment;
- legal framework;
- personnel capability;
- system configuration;
- testing conditions;
- control arrangements.

A system lawful/assured in one context is not automatically assured in another.

---

# 34. MECHANISM 22 — PROCUREMENT-TO-RETIREMENT TRACEABILITY

The system should be traceable from:

design
→ testing
→ procurement
→ training
→ deployment
→ modification
→ incident
→ transfer/retirement

This provides a lifecycle chain of responsibility.

---

# 35. RETIREMENT SAFEGUARD

When systems are retired, States should address:

- stored models;
- software;
- classified operating data;
- update credentials;
- spare parts;
- transferred components.

The purpose is to reduce unauthorized reuse or uncontrolled modification.

---

# 36. TIER 1 — HOW TO DRAFT THE PROHIBITION GATE

The prohibition tier should be narrow enough to be enforceable and strong enough to matter.

Potential criteria can combine:

### HUMAN-TARGET CRITERION

Autonomous use of force directly against persons.

### CONTROL CRITERION

Systems where effective human judgement/control cannot be maintained.

### PREDICTABILITY CRITERION

Systems whose effects cannot be sufficiently characterized in expected conditions.

### IHL COMPATIBILITY CRITERION

Systems that cannot be used consistently with distinction, proportionality, precautions or other applicable IHL obligations.

### UNCONTROLLABILITY CRITERION

Systems whose critical behaviour cannot be reliably bounded or interrupted where required by the framework.

These are candidate drafting criteria, not a claim that each is already a universally accepted rule.

---

# 37. TIER 1 TEST

Ask four questions:

1. Can the system's relevant effects be sufficiently predicted?
2. Can its operational use be bounded?
3. Can effective human judgement/control be maintained?
4. Can the State demonstrate compliance with applicable international law?

If the State cannot answer these questions sufficiently, the system/use should move toward the prohibited side of the architecture.

The exact legal threshold remains negotiable.

---

# 38. TIER 2 — STRICTLY REGULATED SYSTEMS

Tier 2 is not:

> "Everything else is fine."

Tier 2 means:

- operating envelope;
- legal review;
- testing;
- human judgement/control;
- lifecycle monitoring;
- change control;
- traceability;
- incident investigation;
- accountability;
- cybersecurity;
- appropriate transfer/procurement controls.

---

# 39. THE TWO-TIER SWITCH

A system can move between categories.

Example:

System initially bounded
→ validated
→ deployed
→ material software modification
→ operating envelope expands
→ predictability decreases
→ review triggered
→ system may be restricted further.

This is important because classification should not be a permanent sticker.

---

# 40. THE "FUNCTION NOT PLATFORM" RULE

Do not classify systems only by platform name.

The same underlying platform could be:

- remotely controlled;
- automated;
- autonomous within a bounded task;
- adapted through changing software.

Therefore the framework should examine:

- critical functions;
- target selection;
- engagement;
- autonomy;
- human role;
- environment.

This also avoids treating every loitering munition or every AI-enabled platform as automatically equivalent.

---

# 41. DUAL-USE / AI DECISION SUPPORT BOUNDARY

Do not accidentally regulate every military AI application as LAWS.

Differentiate:

### AI decision support

Human makes the final consequential decision.

### Automated function

System performs a predefined task.

### Autonomous weapon function

System can perform relevant target-selection/engagement functions without further human intervention.

### Key rule

> Regulate the function that creates the risk, not the word "AI".

---

# 42. DEFENSIVE SYSTEMS

Do not create an automatic blanket exemption.

Instead assess:

- target nature;
- operational environment;
- predictability;
- scale;
- duration;
- geography;
- human constraints;
- communication loss;
- intervention feasibility.

A defensive system may need a context-specific operating envelope.

The framework can recognize contextual differences without saying:

> "defensive = automatically safe."

---

# 43. SWARMS

The architecture must address not only individual system behaviour but interaction.

Potential controls:

- maximum number of simultaneously active systems;
- shared operating boundaries;
- aggregate engagement limits;
- deconfliction;
- communications-loss behaviour;
- swarm-level incident logging.

### Important concept

> A set of individually bounded systems can create collective risk that does not appear when evaluating each unit separately.

This is a proposed risk-assessment principle.

---

# 44. EMERGING INTERACTION RISK

Evaluate interactions between:

- multiple autonomous systems;
- autonomous and remotely controlled systems;
- AI decision support and autonomous systems;
- electronic warfare;
- cyber interference;
- degraded communications;
- civilian systems.

Testing should include representative interaction scenarios.

---

# 45. CYBER / ADVERSARIAL INPUTS

Testing should include:

- corrupted data;
- spoofed sensors;
- adversarial inputs;
- communications interference;
- compromised updates;
- degraded navigation;
- unexpected sensor conditions.

The purpose is not to demand publication of vulnerabilities.

The purpose is to establish that the State tested foreseeable ways the system could fail.

---

# 46. THE "EVIDENCE BEFORE OPERATION" RULE

For every major regulatory requirement, identify evidence.

### Human control
Evidence:
- authorization;
- operating envelope;
- logs;
- intervention records.

### Predictability
Evidence:
- test results;
- failure analysis.

### Lifecycle
Evidence:
- version/change records.

### Accountability
Evidence:
- responsible authority;
- mission authorization.

### Verification
Evidence:
- review records;
- reporting.

This is how the framework avoids becoming purely declaratory.

---

# 47. THE "NO SOURCE-CODE OBSESSION" RULE

AAWG should not make source-code disclosure the default verification requirement.

Why?

Because the core question is:

> Can the State demonstrate sufficient assurance and control?

A State may be able to demonstrate that through:

- test evidence;
- version control;
- performance records;
- assurance arguments;
- protected expert review.

Source-code inspection can be considered in specialized circumstances, but it should not be treated as the only meaningful form of verification.

---

# 48. THE INTERNATIONAL SECRETARIAT / FOCAL POINT

A future framework could designate a small international focal point for:

- receiving reports;
- maintaining aggregate records;
- convening technical exchanges;
- supporting capacity-building;
- distributing lessons learned.

It should not automatically become:

- a global weapons police;
- a command authority;
- an intrusive inspection bureaucracy.

Institutional scope must match what States could realistically accept.

---

# 49. WHAT THE CCW DOES IN THE ARCHITECTURE

The CCW remains the principal specialist negotiating environment in this architecture.

The practical route can be:

UNGA political momentum
+
CCW technical/legal negotiation
+
Review Conference decision
+
future negotiating mandate / instrument

This avoids pretending the UNGA and CCW perform identical functions.

---

# 50. WHAT THE UNGA DOES

UNGA can support:

- political attention;
- reporting;
- inclusive dialogue;
- capacity-building;
- further multilateral work;
- broader legitimacy.

It should not be presented as a substitute for the specialist technical negotiation already occurring in the CCW.

---

# 51. THE LEGAL-FORM LADDER

Brazil can maintain its preference for a legally binding instrument while leaving room for negotiation on sequencing.

### LEVEL 1

Political commitment / principles.

### LEVEL 2

Common elements + reporting + confidence-building.

### LEVEL 3

Negotiating mandate.

### LEVEL 4

Legally binding instrument.

### Brazil position

The destination is:

> a legally binding international instrument

The sequencing can be negotiated.

---

# 52. MANDATE DESIGN

A proposed future mandate should specify:

- scope;
- definitions;
- prohibition questions;
- regulated-system safeguards;
- human judgement/control;
- lifecycle review;
- verification;
- transfers;
- capacity-building;
- institutional reporting.

The mandate should avoid being so broad that negotiations become general military-AI governance.

---

# 53. THE "MINIMUM VIABLE ARCHITECTURE"

If the committee gives Brazil very little drafting space, preserve these seven pieces:

1. two-tier classification;
2. human judgement/control;
3. operating envelope;
4. legal review + testing;
5. material-change review;
6. accountability/incident reporting;
7. capacity-building.

Everything else can be added later.

---

# 54. THE "FULL ARCHITECTURE"

If the committee allows substantial detail:

### Layer 1
Definitions.

### Layer 2
Prohibition gate.

### Layer 3
Tier 2 operating controls.

### Layer 4
Autonomy Assurance Case.

### Layer 5
Legal review.

### Layer 6
Testing / TEVV.

### Layer 7
Procurement.

### Layer 8
Supplier controls.

### Layer 9
Change management.

### Layer 10
Logging and traceability.

### Layer 11
Serious incidents.

### Layer 12
Protected technical review.

### Layer 13
Transfers.

### Layer 14
Capacity-building.

### Layer 15
Review / update.

---

# 55. THE ARCHITECTURE AS A FLOWCHART

System / Function
↓
Characterize
↓
Tier 1 or Tier 2?
├── Tier 1 → Prohibit
└── Tier 2 → Assurance Case
             ↓
        Operating Envelope
             ↓
         Legal Review
             ↓
           Testing
             ↓
         Procurement
             ↓
      Deployment Gate
             ↓
          Operation
             ↓
      Monitor / Log
             ↓
       Incident or Change?
        ├── No → Continue
        └── Yes → Reassess / Investigate
                         ↓
                   Revalidate
                         ↓
                 Lessons Learned

---

# 56. HOW THE ARCHITECTURE CLOSES THE GOVERNANCE LOOP

### Design stage
Can it be characterized?

### Legal stage
Can it comply with applicable law?

### Technical stage
Can its performance be sufficiently assured?

### Operational stage
Are its boundaries defined?

### Human stage
Is judgement/control actually meaningful in context?

### Lifecycle stage
Does assurance survive modification?

### Accountability stage
Can the State reconstruct what happened?

### International stage
Can States learn from incidents and improve the framework?

That is the whole architecture.

---

# 57. THE BRAZIL NEGOTIATION HIERARCHY

Brazil should separate:

## NON-NEGOTIABLE OUTCOME

- prohibited unacceptable uses/systems;
- continuing human responsibility;
- meaningful/context-appropriate human judgement/control in substance;
- accountability;
- legal and technical assurance.

## HIGH PRIORITY

- operating envelope;
- material-change review;
- incident mechanism;
- lifecycle safeguards.

## STRONG BUT FLEXIBLE

- protected technical review;
- registry;
- procurement gate;
- supplier requirements;
- regional hubs.

## PROCEDURAL FLEXIBILITY

- exact institutional home;
- legal-form sequencing;
- reporting format;
- public vs confidential reporting detail;
- exact wording of "meaningful human control."

---

# 58. HOW BRAZIL SHOULD TRADE

Do not trade:

> human accountability

for:

> a reporting format.

Do not trade:

> prohibition of clearly unacceptable autonomous use

for:

> a general political statement.

Trade implementation detail instead.

Examples:

### Brazil gives
flexibility on direct vs indirect control.

### Brazil asks
for operating-envelope requirements.

---

### Brazil gives
flexibility on reporting format.

### Brazil asks
for serious-incident reporting.

---

### Brazil gives
confidentiality protections.

### Brazil asks
for protected technical review.

---

### Brazil gives
sequencing flexibility.

### Brazil asks
for an explicit negotiating pathway toward a binding instrument.

---

# 59. THE BRIDGE-STATE VERSION

For cautious States:

> "You do not have to accept the strongest possible legal form to support an assurance architecture that improves predictability, testing, operating limits and accountability."

This allows cooperation on substance before legal-form agreement.

---

# 60. THE STRONGER-BAN VERSION

For States wanting stronger restrictions:

> "Let's make the prohibition testable. Which operational condition makes the autonomous use unacceptable?"

Then build:

- target criterion;
- predictability criterion;
- control criterion;
- IHL compatibility criterion.

---

# 61. THE DEVELOPMENT / GLOBAL-SOUTH VERSION

For States concerned about implementation:

> "No regime is credible if compliance requires capabilities only a few technologically advanced States possess."

Then offer:

- regional hubs;
- legal-review assistance;
- testing methodologies;
- technical experts;
- training;
- procurement guidance.

---

# 62. THE TECHNICAL VERSION

For technical delegates:

> "We are not trying to regulate 'AI' as a label. We are regulating the critical functions and conditions that create lethal autonomy risk."

Then discuss:

- target-selection;
- engagement;
- environment;
- predictability;
- intervention;
- change management.

---

# 63. THE "OUT-OF-THE-BOX" TEST

The committee wants original solutions.

Do not call something original merely because the name sounds new.

A mechanism is genuinely useful when it:

1. solves a defined governance gap;
2. identifies an implementing actor;
3. has a trigger;
4. has evidence;
5. has a compliance consequence;
6. respects confidentiality where necessary;
7. can survive negotiation.

By this test:

### Strong original architecture
- Assurance Case;
- Materiality Trigger Matrix;
- Control Continuity Test;
- Incident-to-Review Loop;
- layered verification;
- procurement-to-retirement traceability.

### Existing-but-usefully-combined architecture
- legal review;
- testing;
- operating envelope;
- incident reporting;
- procurement controls;
- capacity hubs.

The originality comes from how they connect, not from pretending each component was invented from nothing.

---

# 64. THE FIVE MOST DEFENSIBLE ORIGINAL MECHANISMS

If the Chair asks:

> "What is Brazil's flagship innovation?"

Use these five.

## 1. Autonomy Assurance Case

Evidence-based assurance package.

## 2. Materiality Trigger Matrix

Defines when changes require renewed review.

## 3. Control Continuity Test

Checks human judgement/control across the lifecycle.

## 4. Incident-to-Review Loop

Turns serious incidents into mandatory reassessment and lessons learned.

## 5. Procurement-to-Retirement Traceability

Makes accountability continuous rather than beginning only after deployment.

---

# 65. THE FIVE-MECHANISM PITCH

> "Brazil proposes an assurance-based architecture. First, an Autonomy Assurance Case records what the system is designed and authorized to do. Second, an operating envelope makes human control technically meaningful. Third, a materiality matrix triggers renewed legal and technical review when critical functions change. Fourth, serious incidents trigger an evidence-preservation and reassessment loop. Fifth, procurement-to-retirement traceability ensures responsibility follows the system across its lifecycle."

That is a 30–40 second solution pitch.

---

# 66. THE TWO-TIER RESOLUTION SKELETON

### PREAMBULAR LOGIC

- recalling applicable IHL;
- recognizing technological change;
- recognizing existing CCW work;
- emphasizing human responsibility;
- recognizing capacity differences.

### OPERATIVE BLOCK I — SCOPE

Define covered autonomous functions.

### OPERATIVE BLOCK II — PROHIBITION

Identify Tier 1 criteria.

### OPERATIVE BLOCK III — REGULATION

Create Tier 2 safeguards.

### OPERATIVE BLOCK IV — ASSURANCE

AWIA / Assurance Case / legal review / testing.

### OPERATIVE BLOCK V — OPERATION

Operating envelope / intervention / communications loss.

### OPERATIVE BLOCK VI — LIFECYCLE

Change control / reassessment / updates.

### OPERATIVE BLOCK VII — ACCOUNTABILITY

Logging / records / responsible authorities / incident investigation.

### OPERATIVE BLOCK VIII — VERIFICATION

National reporting / peer exchange / protected review.

### OPERATIVE BLOCK IX — CAPACITY

Regional hubs / technical assistance / legal-review support.

### OPERATIVE BLOCK X — INSTITUTIONAL PATH

CCW continuation / Review Conference / negotiating mandate or further work.

---

# 67. CLAUSE-BUILDING TEMPLATE

Use this sentence structure:

> Calls upon States to [ACTOR/ACTION] by [MECHANISM], applying [TRIGGER/SCOPE], requiring [EVIDENCE], with [CONFIDENTIALITY SAFEGUARD], and subject to [REVIEW/ACCOUNTABILITY].

Example:

> "Calls upon States to establish procedures for renewed legal and technical assurance where material modifications affect critical targeting functions, requiring documentation of the modified function and associated testing, while allowing sensitive technical information to remain protected under national security procedures."

---

# 68. EXAMPLE OPERATIVE CLAUSES — WORKING DRAFT ONLY

### OP1 — Assurance

> Calls upon States to establish national procedures for documenting the intended function, operating environment, autonomy parameters, target categories, human-control arrangements, legal-review findings and testing evidence of covered autonomous weapon systems prior to deployment;

### OP2 — Operating envelope

> Encourages States to define an operational envelope for regulated autonomous weapon systems specifying, as appropriate, target categories, geographic scope, duration, engagement scale, environmental assumptions and conditions requiring reassessment, interruption or deactivation;

### OP3 — Material change

> Calls upon States to conduct renewed legal and technical review following material modifications affecting critical functions, including target-selection logic, engagement logic, sensor integration, autonomy mode or other changes capable of materially altering expected effects;

### OP4 — Serious incidents

> Encourages States to preserve relevant technical and operational records and investigate serious incidents involving loss of control, unexpected target engagement, civilian harm or other material deviation from authorized operating conditions;

### OP5 — Protected review

> Invites States to explore voluntary or agreed procedures for protected technical exchange concerning testing methodologies, operating envelopes, change-control systems and assurance evidence, while respecting legitimate national-security requirements;

### OP6 — Capacity

> Encourages the development of regional technical and legal capacity-building initiatives supporting testing, legal review, operator training, cybersecurity and responsible procurement;

### OP7 — Procurement

> Encourages States to incorporate legal-review documentation, testing evidence, change-management requirements, cybersecurity safeguards and accountability arrangements into procurement procedures for covered autonomous weapon systems;

### OP8 — Review trigger

> Encourages periodic review of national frameworks following significant technological developments, serious incidents, material changes in system capability or evidence that existing safeguards are insufficient.

---

# 69. WHY THE CLAUSES WORK TOGETHER

OP1 creates evidence.

OP2 creates boundaries.

OP3 keeps the evidence current.

OP4 preserves lessons.

OP5 makes verification politically easier.

OP6 makes compliance more universal.

OP7 pushes safeguards upstream into acquisition.

OP8 prevents technological obsolescence.

That is a system, not eight unrelated paragraphs.

---

# 70. WHAT NOT TO DO IN THE FINAL RESOLUTION

Do not include all 20+ mechanisms just because this document contains them.

Avoid:

- six different registries;
- three overlapping reporting systems;
- multiple committees with the same mandate;
- intrusive inspections before political buy-in;
- mandatory source-code publication;
- undefined "AI ethics" language;
- automatic bans based only on platform category;
- automatic exemptions for defensive systems;
- one universal human-control model for every operational context.

The final text should be smaller than this architecture.

This file is the design bank.

---

# 71. THE "MECHANISM SELECTION" SCORECARD

Not a political score or country ranking. This is a drafting test.

For each proposed mechanism ask:

| Test | Yes/No |
|---|---|
| Solves a concrete problem? | |
| Clear implementing actor? | |
| Clear trigger? | |
| Evidence exists? | |
| Compliance can be assessed? | |
| Confidentiality manageable? | |
| Politically negotiable? | |
| Technically plausible? | |
| Avoids duplication? | |
| Supports accountability? | |

Keep mechanisms that survive most of the tests.

---

# 72. MECHANISM DEPENDENCIES

Some mechanisms should not be drafted independently.

### AWIA
depends on:
- scope;
- legal review;
- testing.

### Operating Envelope
depends on:
- target class;
- geography;
- duration;
- scale;
- emergency response.

### Change Control
depends on:
- materiality definition;
- version tracking;
- testing.

### Incident Mechanism
depends on:
- logging;
- evidence preservation;
- responsible authority.

### Protected Review
depends on:
- confidentiality;
- assurance evidence.

### Procurement Gate
depends on:
- technical requirements;
- legal review;
- supplier duties.

This dependency map prevents broken architecture.

---

# 73. THE "ONE SOURCE OF TRUTH" PRINCIPLE

Do not create separate incompatible records for:

- procurement;
- legal review;
- testing;
- operations.

Use one common system identity and version history.

Example:

System ID: A-024

Model: M-7

Version: 7.3

Approved envelope: E-3

Legal review: LR-24

Test package: T-17

Material changes: MC-03

Incident records: IR-02

This is a proposed administrative model.

The point is reconstructability.

---

# 74. INCIDENT RECONSTRUCTION TEST

After an incident, a reviewer should be able to ask:

> What system version was active?

> What mission was authorized?

> What target category was allowed?

> What geographic boundary applied?

> What environmental assumptions were used?

> Who authorized the deployment?

> What warnings occurred?

> Did anyone intervene?

> What happened when conditions changed?

> Was the system inside its operating envelope?

> Had the system been materially modified?

If the State cannot reconstruct these basic facts, accountability is weakened.

---

# 75. THE "FAIL-SAFE VS FAIL-OPEN" PRINCIPLE

A system should not automatically gain greater lethal autonomy because:

- communications disappear;
- sensors degrade;
- software detects uncertainty;
- external control is disrupted.

Therefore:

> critical failure conditions should trigger a predefined safe response, not silent expansion of authority.

Exact response remains context-specific.

---

# 76. THE "HUMAN CONTROL IS A SYSTEM PROPERTY" IDEA

Do not frame human control as:

> "There is a person."

Frame it as:

> "The socio-technical system preserves effective human judgement and responsibility."

That means evaluating:

- operator;
- interface;
- training;
- doctrine;
- time;
- information;
- override;
- system constraints;
- command authority.

This is a stronger analytical frame than a headcount rule.

---

# 77. THE "ACCOUNTABILITY STACK"

Responsibility should exist at multiple stages.

### Commander / authorizing authority
Mission and use.

### Operator
Supervision/intervention where applicable.

### Procurement authority
Acquisition controls.

### Developer / supplier
Contractual documentation and change notification.

### Legal reviewer
Lawfulness assessment within the applicable national/legal framework.

### Investigative authority
Post-incident reconstruction.

The international framework should not pretend these actors have identical legal responsibility.

---

# 78. THE "NO ACCOUNTABILITY GAP" TEST

If a delegate asks:

> "Who is responsible when the machine makes the decision?"

Brazil's answer:

> "The system does not replace human legal responsibility; the framework requires responsibility to remain attributable to authorized human decision-makers and institutions, supported by records that allow reconstruction of the decision chain."

Do not say:

> "The programmer is always responsible."

That is too crude.

---

# 79. THE "NO TECHNOLOGY FREEZE" PRINCIPLE

The architecture should be technology-neutral.

It should govern:

- functions;
- risks;
- control;
- predictability;
- lifecycle assurance.

Not one specific:

- algorithm;
- platform;
- manufacturer;
- model.

This makes the framework more durable.

---

# 80. THE "REVIEW BEFORE TECHNOLOGY BREAKS THE RULE" PRINCIPLE

The review mechanism should not wait for obvious disasters.

Trigger reconsideration when:

- a new capability materially changes risk;
- autonomous operation becomes more adaptive;
- systems interact at larger scales;
- environmental assumptions widen;
- target classes expand.

This is why sunset/review triggers matter.

---

# 81. INSTITUTIONAL ARCHITECTURE — MINIMAL VERSION

A politically lighter institutional package:

### International focal point
Receives reports and supports exchanges.

### Expert network
Provides technical/legal capacity.

### State focal points
Maintain national implementation.

### Review Conference / designated CCW process
Reviews progress and updates the framework.

This avoids creating a giant new bureaucracy.

---

# 82. INSTITUTIONAL ARCHITECTURE — STRONGER VERSION

If the committee wants more:

- standing technical expert roster;
- protected review procedure;
- annual lessons-learned report;
- voluntary national framework reports;
- regional capacity hubs;
- periodic review cycle.

The legal nature of these mechanisms can be negotiated separately from their operational usefulness.

---

# 83. THE "CCW-FIRST, UNGA-SUPPORTED" OPTION

For the Brazil line:

> "Use the UNGA for political momentum and inclusive reporting; use the CCW for specialist negotiation, technical/legal text and the path toward an instrument."

The 2026 CCW GGE mandate is to formulate, by consensus, a set of elements of an instrument without prejudging its nature, alongside other possible measures. The September session then worked through a substantive set of elements for the Seventh Review Conference. 

That means Brazil can argue for a future binding instrument without claiming that the existing GGE text is already a treaty.

---

# 84. THE "POLITICAL MOMENTUM + TECHNICAL DEPTH" MODEL

Use:

UNGA
→ visibility / political impetus

CCW GGE
→ technical/legal convergence

Review Conference
→ next-stage institutional decision

Future negotiations
→ legal instrument

This is more institutionally precise than:

> "UNGA will just ban LAWS."

---

# 85. HOW TO SELL THE ARCHITECTURE IN GSL

Start:

> "Brazil believes the central weakness in the LAWS debate is not a lack of principles. It is a lack of mechanisms that make those principles verifiable throughout a weapon's lifecycle."

Then:

> "Brazil therefore proposes an assurance-based framework combining a two-tier prohibition and regulation model with operating envelopes, continuing legal review, material-change triggers, incident reporting, procurement safeguards and protected technical review."

Then:

> "Our objective is simple: if a State claims a system is lawful and under meaningful human control, the State should be able to demonstrate how."

---

# 86. 20-SECOND VERSION

> "Brazil proposes two tiers: prohibit clearly unacceptable autonomous uses and strictly regulate the rest through operating envelopes, legal review, testing and continuing lifecycle assurance. Material software changes trigger re-review, serious incidents trigger investigation, and protected technical verification can improve accountability without forcing States to disclose sensitive military information."

---

# 87. 10-SECOND VERSION

> "Ban the unacceptable, bound the permissible, prove the controls, re-review the changes, investigate the failures."

---

# 88. THE MASTER MEMORY MAP

Remember:

## P1 — PROHIBIT
Clearly unacceptable autonomous uses/systems.

## P2 — PARAMETERIZE
Operating envelope.

## P3 — PROVE
Assurance Case + testing + legal review.

## P4 — PRESERVE
Logs + traceability + evidence.

## P5 — REASSESS
Material changes + serious incidents.

## P6 — PROTECT
Confidential technical review.

## P7 — PREPARE
Capacity-building + procurement.

## P8 — PROCEED
Institutional pathway toward a binding instrument.

---

# 89. FINAL DESIGN RULE

A solution is not original because it has a fancy name.

It is original when it creates a new connection between existing governance needs that the committee can actually defend.

The strongest Brazil architecture is therefore:

> "A two-tier LAWS regime in which prohibited uses are screened out, permitted systems are bounded by an operational envelope, legal and technical assurance is documented before deployment, material changes trigger renewed review, serious incidents trigger a learning loop, accountability is supported by traceability, and verification is graduated so that it protects legitimate security concerns while still producing evidence."

That is the system.

---

# 90. SOURCE DISCIPLINE

Use the repository research as the primary foundation for drafting.

Key internal sources:

- RESEARCH/AGENDA/18_PROHIBITIONS_DEEP_DIVE.md
- RESEARCH/AGENDA/19_HUMAN_CONTROL_DEEP_DIVE.md
- RESEARCH/AGENDA/20_REGULATION_LIFECYCLE_VERIFICATION_DEEP_DIVE.md
- RESEARCH/AGENDA/29_UNGA_VS_CCW_INSTITUTIONAL_PATH.md
- RESEARCH/AGENDA/30_ORIGINAL_REGULATORY_ARCHITECTURE_OPTIONS.md
- RESEARCH/AGENDA/31_ADAPTIVE_AI_ARTICLE_36_AND_ASSURANCE.md
- RESEARCH/AGENDA/34_CASE_STUDY_EVIDENCE_AUDIT.md
- RESEARCH/AGENDA/26_BRAZIL_NEGOTIATING_SPACE.md
- HAHA/05_AAWG_COMMON_POSITION.md
- HAHA/06_AAWG_COUNTRY_ALIGNMENT.md

Important legal/position discipline:

- Do not describe Article 36 as universally binding.
- Do not present "meaningful human control" as an already universally codified standalone treaty rule.
- Do not claim every autonomous or AI-enabled system is LAWS.
- Do not present any proposed mechanism in this document as an existing treaty requirement.
- Do not equate GGE consensus on elements with agreement on the final legal form of an instrument.
- Do not imply that one technical standard is globally mandated unless the source supports that claim.

---

# 91. CURRENT 2026 EXTERNAL ANCHORS

## CCW GGE

The 2026 GGE mandate is to formulate, by consensus, a set of elements of an instrument without prejudging its nature, alongside other possible measures. The first-session Chair's summary also records debate around human control, incident investigation and information exchange.

The UN transcript for the September session records the Chair presenting a substantive set of elements and other possible measures for the report and recommending that the Seventh Review Conference decide the future way forward.

## Procurement

SIPRI's 2026 research describes procurement as a mechanism through which States can operationalize responsible military-AI commitments and recommends clearer supplier expectations and inclusion of procurement in international policy discussions.

These sources support the architecture's emphasis on:

- continuing assurance;
- procurement;
- lifecycle controls;
- incident learning;
- evidence-based implementation.

They do not turn the proposed mechanisms in this file into existing international law.

---

# 92. FINAL COMMITTEE USE

This file should feed directly into:

### Part 8
GSL + MOD solution lines.

### Part 9
POIs attacking weak architectures.

### Part 10
Resolution operative clauses.

### Part 11
Mock committee.

### Part 12
Weakness patching.

The important shift is:

> Do not merely know Brazil's solution. Know how every part of the solution operates.
