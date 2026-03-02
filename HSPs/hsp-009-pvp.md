---
hsp: 009
title: NEAR House of Stake Proposals and Voting Procedures
description: Establishes clear procedures for collective decision-making in the House of Stake
author: Hack Humanity
discussions-to: https://gov.near.org/t/hsp-xxx-near-house-of-stake-proposals-and-voting-procedures/42019
status: Review
track: Decision
type: Supermajority
category: Legitimacy & Engagement
stakeholders: See section "Stakeholders"
created: 2026-01-29
requires: Foundation Legal Documents
---

## Abstract

This proposal adopts the Proposals and Voting Procedures v1.0 for NEAR House of Stake.  

The Procedures establish a comprehensive framework governing how proposals are authored, reviewed, screened, voted upon, and executed. They define roles, voting rights, thresholds, quorum, proposal lifecycle stages, and procedural safeguards required for legitimate and resilient governance.

The expected outcome is a predictable, transparent, and enforceable governance process that enables stake-aligned participation, reduces procedural ambiguity, and supports institutional-grade operations across all House of Stake decisions.

## Payload

<details>
<summary> NEAR House of Stake Proposals and Voting Procedures </summary>

# **NEAR House of Stake Proposals and Voting Procedures**

## **Preliminary Article – General Provisions**

### **P.1 Purpose and Application**
P.1.1 These Proposals and Voting Procedures (“**Procedures**”) set out the governance mechanics by which Tokenholders and other recognised governance actors of NEAR House of Stake may submit, deliberate on, and vote upon proposals within the scope of NEAR House of Stake.

P.1.2 These Procedures apply solely as an internal governance framework for the NEAR House of Stake and do not regulate, amend, or supersede the legal structure, powers, or obligations of the NEAR House of Stake Foundation (**“Foundation”**).

### **P.2 Legal Nature and Hierarchy**
P.2.1 These Procedures are not a legal contract and do not, of themselves, create, confer, or give rise to any enforceable rights, obligations, or duties between the Foundation and any Tokenholder, delegate, governance participant, or other person, except as required by applicable law.

P.2.2 These Procedures operate subject to the Memorandum of Association, Articles of Association, and Bylaws of the Foundation (“**Foundation Legal Documents**”), which are located at the NEAR House of Stake Documentation. In the event of any conflict or inconsistency, the Foundation Legal Documents shall prevail.

P.2.3 Nothing in these Procedures shall be construed to require the Foundation, its directors, or supervisors to act unlawfully or in breach of their fiduciary duties. Any governance decision or vote described herein may be implemented only to the extent consistent with applicable law and the Foundation Legal Documents.

P.2.4 These Procedures shall be interpreted consistently with the NEAR House of Stake Constitution, as amended from time to time. In the event of any conflict or inconsistency, the Constitution shall prevail.

### **P.3 Interpretation**
P.3.1 Capitalised terms used in these Procedures but not otherwise defined herein shall have the meanings given to them in the Foundation Legal Documents or the Constitution, as applicable, unless the context requires otherwise.

## **Article 1 - Proposals and Voting Procedure Roles**

### **1.1 HSP Definition**

1.1.1 A House of Stake Proposal (“**HSP**”) is a standardized governance artifact and procedural mechanism through which proposals are submitted, reviewed, deliberated, and voted upon within NEAR House of Stake.

### **1.2 HSP Author**

1.2.1 The House of Stake Proposal Author writes the proposal and submits it for review.

### **1.3 HSP Editors**

1.3.1 The HSP Editors are appointed and removed by the Head of Governance. 

1.3.2 Reviews proposals and provides feedback to the HSP Author regarding correct format, completeness of required sections, and compliance with the scope of these Procedures.

1.3.3 Updates the HSP proposals' statuses in line with the Proposals and Voting Guide.

### **1.4 Authority Limitation**

1.4.1 No role, committee, working group, or participant acting under these Procedures has authority to bind the Foundation, incur obligations, authorize expenditures, or represent the Foundation, except as expressly provided for in the Foundation Legal Documents.

## **Article 2 - Proposals and Voting Actors and Rights**

### **2.1 Tokenholders**

2.1.1 Tokenholders may submit proposals in accordance with these Procedures and may vote on proposals directly with their veNEAR voting power, or by delegating to another Delegate.

2.1.2 HSP Authors are solely responsible for the content of their proposals, including compliance with applicable law, intellectual property rights, and third-party rights.

### **2.2 NEAR House of Stake Delegates**

2.2.1 Any Tokenholder can receive delegated Voting Power by creating a Delegate statement in the voting platform. Delegates may use their delegated Voting Power solely for voting purposes.

## **Article 3 - Voting**

### **3.1 Voting Power**

3.1.1 Voting Power is the veNEAR that each Delegate controls at the moment a proposal is approved by the Screening Committee to be voted on. The voting power of each Delegate is recorded and fixed for the duration of the proposal vote, regardless of any subsequent changes.

3.1.2 veNEAR Tokenholders may revoke delegation at any time. 

### **3.2 Quorum**

3.2.1 The Quorum is the minimum voting power needed for a proposal to be considered valid. In NEAR House of Stake, the Quorum is 1,000 veNEAR.

3.2.2 The Quorum can be updated at any time, following a supermajority proposal.

3.2.3 Abstain votes are counted for purposes of Quorum calculation.

### **3.3 Voting Tracks**

3.3.1 There are two Voting Tracks: Sensing and Decision.

3.3.2 A **Sensing** vote is a tool that HSP Authors may use to gather onchain feedback or signal community sentiment related to their proposal.

3.3.3 A **Decision** vote reflects a final governance determination within the NEAR House of Stake. Implementation remains subject to legal, fiduciary, technical, and operational feasibility in accordance with these Procedures and the Foundation Legal Documents.

### **3.4 Voting Types**

3.4.1 A Simple Majority Vote is used by default unless the proposal meets the criteria for a Supermajority voting type of proposal.

3.4.2 A Supermajority Vote is meant for proposals that create, modify, or enable the governance system itself – including its rules, authority structures, enforcement mechanisms, and technological implementations.

3.4.3 The Screening Committee may, at its discretion, determine that a Proposal requires a Supermajority Voting type, in agreement with the Screening Committee Charter.

### **3.5 Thresholds**

3.5.1 **Simple Majority Vote** requires a voting threshold of over 50% to be ratified, calculated as follows:

$$
\text{passed} = \frac{yes}{yes+no} \ge \frac{1}{2}
$$

3.5.2 **Supermajority Vote** requires a voting threshold of over two-thirds to be ratified, calculated as follows:

$$
\text{passed} = \frac{yes}{yes+no} \ge \frac{2}{3}
$$
    
3.5.3 Abstain votes do not count toward any voting threshold.

3.5.4 Emergency Actions require a 75% approval of the total number of the Security Council members, according to the NEAR House of Stake Foundation Bylaws.

$$
\text{passed} = \frac{yes}{totalSecurityCouncilMembers} \ge \frac{3}{4}
$$

3.5.5 Emergency Overrides to veto Security Council's Emergency Actions require a Simple Majority vote with a 75% of circulating veNEAR as quorum.

$$
\text{passed} = 
\left(\frac{yes}{yes+no} \ge \frac{1}{2}\right)
∧
\left(\frac{voted\  veNEAR}{circulating\  veNEAR} \ge \frac{3}{4}\right)
$$

### **3.6 Proposal Categories**

3.6.1 HSP Authors shall specify one of the following categories:

* Economic Governance - Treasury, inflation, fees, token economics
* Technical Governance - Protocol changes, smart contracts, infrastructure
* Legitimacy & Engagement - Policies, procedures, community initiatives
* Grants & Funding - Grant programs, funding allocations
* Operations - House of Stake operational matters
* Other - Proposals that don't fit above categories

### **3.7 Implementation Safeguards and Responsibility**

3.7.1 Implementation of any approved proposal is subject to ongoing legal, financial, technical, and operational feasibility. Where misuse of funds, material deviation from the approved proposal, or other integrity risks are identified, the Foundation may suspend, modify, or terminate implementation and take remedial or recovery actions, in accordance with the Foundation Legal Documents and applicable law.

3.7.2 Where proposal implementation involves the transfer or use of funds by non-Foundation parties, such parties bear sole responsibility for lawful and proper use of such funds, subject to applicable oversight and recovery mechanisms.

## **Article 4 - Selection and Removal of Governance Body Members**

4.1 The NEAR Foundation, the NEAR House of Stake Foundation, or the Head of Governance may appoint Governance Body Members as part of progressive decentralization towards full autonomy. They may also remove them according to Removal for Cause, as provided in the Constitution.

## **Article 5 - Establishment and Amendment of Constitutional Documents**

5.1 Constitutional Documents are defined in the Constitution and may be established by the NEAR House of Stake Foundation, the Head of Governance on an interim basis, or by Tokenholder Vote.

5.2 All interim Constitutional Documents remain subject to ratification, replacement, amendment, or removal by Tokenholder Vote, consistent with the Foundation Legal Documents.

## **Article 6 - House of Stake Proposal (HSP) Requirements and Template**

### **6.1 HSP Elements**

6.1.1 HSPs use a standardized markdown file format that contains the following elements, mandatory to any proposal:

* Frontmatter according to provision 6.2.  
* Proposal details according to provision 6.3.

### **6.2 Frontmatter**

```yaml
hsp: <number>  
title: <max 44 characters>  
description: <max 140 characters>  
author: <name(s) and contact info>  
discussions-to: <forum URL>  
status: <Draft|Review|Voting|Rejected|Defeated|Final|Living|Vetoed|Withdrawn|Stagnant>  
track: <Sensing|Decision>  
type: <Simple Majority|Supermajority>  
category: <category name>  
stakeholders: <see section "Stakeholders">  
created: <YYYY-MM-DD>  
requires: <HSP number(s)> (optional)
```
    
### **6.3 Template**

```yaml

## Abstract  
Synthesize what is proposed, why it matters, and the expected outcome (max. 120 words).

## Payload
When a proposal contains executable code or text intended for formal adoption, include the payload using the format below, and remove the brackets ([]).

[```]  
<details>  
<summary> Payload title </summary>  
Proposal's code or text  
</details>  
[```]

## Context  
Describe the background that makes this proposal relevant. Explain what prior proposals or decisions relate to this, what discussions or working group outputs informed it, and what recent events or conditions make this timely.

## Problem  
State the problem this proposal addresses and why it matters.

## Approach  
Describe the high-level solution and how it addresses the stated problem. Compare how the proposal solves the problem in relation to other potential approaches, and explain the benefits and limitations of the proposed alternative. Avoid implementation details, timelines, or metrics.

## End-to-end Value Hypothesis  
The proposal shall demonstrate how it, on a standalone basis, delivers complete and meaningful value to the NEAR House of Stake and the NEAR ecosystem, without omission of essential components, deferral to follow-up proposals, or reliance on undefined or uncommitted third-party deliverables. All implementation steps necessary to realize the proposed value shall be specified within the proposal, and any external dependencies shall be explicitly identified, confirmed, and evidenced in the Dependencies subsection. This section defines the logic of value creation inherent to the proposal and does not address success measurement, evaluation metrics, or execution sequencing.

### Objective  
The proposal shall clearly state the specific change or improvement it intends to achieve. Shall not restate expected benefits, outcomes, or performance measurements, which are addressed in other sections.

### Outcome  
The proposal shall describe the observable benefits or changes experienced by affected stakeholders once the stated objectives are achieved, focusing on the resulting impact rather than implementation, process, or measurement.

### Dependencies  
List and detail all external components, infrastructure, systems, or conditions required for the Objective and Outcome to be achieved that are not part of the payload. For each dependency, provide evidence of existence. Do not include implementation steps; they belong in the Implementation Plan. Do not list people or organizations; they belong in the Stakeholders.

## Key Performance Indicators (KPIs)

KPIs define what success looks like. They specify the methods for collecting qualitative or quantitative data and for evaluating impact, taking into account the nature and scope of the proposal.

## Technical Specification  
Clearly describe the technical side of the proposal for reviewers to assess feasibility and correctness, including code, policies, documentation, or any other digital component of the proposed execution.

## Backwards Compatibility  
State whether this proposal conflicts with existing governance rules, technical systems, or processes. If conflicts exist, explain how the proposal aims to resolve them, and if no conflicts exist, briefly explain how the proposal is compatible with the current state of operations.

## Security Considerations  
Identify relevant technical, governance, economic, or operational risks, and include mitigation alternatives for each. If no security considerations apply, state "No security considerations identified."

## Stakeholders  
List all parties required for the proposal to succeed, including external service providers and Governance Body Members. Clearly specify who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for each activity or decision, ensuring that every activity has exactly one Accountable party. This section must make ownership, decision authority, and reporting obligations explicit. 

Use the RACI matrix below. Additional activities must be defined by the author as needed.

| Activity / Decision | Responsible | Accountable | Consulted | Informed |  
|---------------------|------------------|------------------|----------------|---------------|  
| Activity 1 | | | | |

## Implementation Plan

The proposal must outline a clear Definition of Done that includes all necessary implementation steps to achieve the proposed positive impact at the NEAR House of Stake or the NEAR Ecosystem, including the completion criteria and the ways and pace that progress will be reported. This section describes how work is done, not how success is measured (KPIs) or why it creates value (End-to-end Value Hypothesis).

## Milestones

Use the table below to break the proposal into trackable checkpoints that specify when and how critical development steps are achieved. Milestones represent progress toward completion or value realization.

Each milestone must produce a tangible output and, where applicable, reference the KPIs used to evaluate success.

| Milestone name | Target date | Deliverable | Success criteria |  
|----------------|-------------|---------------------------|------------------------------------|  
| Milestone 1 | YYYY-MM-DD | | |

## Budget & Resources  
Details and funding sources, with specific use of requested resources and funding (if applicable), including milestone completion-based fund distribution, subject to compliance. If no funding or resources are requested, state "Not applicable."

## Conflict of Interest  
The author(s) must state that they've read and agree with the House of Stake Conflict of Interest policy, and must state any conflicts of interest, if relevant.

## Copyright  
Copyright and related rights waived via CC0 1.0.
```
## **Article 7 - Proposal Lifecycle**

The proposal lifecycle consists of six stages:

1. Feedback and HSP Editor Review  
2. Onchain Submission  
3. Screening Committee Review  
4. Voting Period  
5. Security Council & Directors Review  
6. Execution

### **7.1 Feedback and HSP Editor Review**

7.1.1 This stage begins when the HSP Author posts the draft proposal on the NEAR Forum using the Proposals tag, using the ID: HSP-XXX and the status attribute `Draft` in the Frontmatter. During this stage, two processes occur:

* Feedback  
* Proposal Review

7.1.2 **Feedback**. During this stage, the HSP Author may not make changes to the HSP.

7.1.2.1 Minimum duration: 7 days;

7.1.2.2 Exception: If a Decision Proposal follows a Sensing Proposal that completed the voting period, and no changes were made, the 7-day requirement does not apply.

7.1.3 **Proposal HSP Editor Review**. The HSP Author submits an HSP on the applicable platform for HSP Editor review. The HSP Editor checks that the HSP complies with the following review criteria:

* Correct format per Article 6 - HSP Requirements and Template.  
* Completeness of required sections.  
* Compliance with the scope of these Procedures and in line with the NEAR House of Stake Constitution.

7.1.4 **HSP Number Assignment**. If the HSP complies with the review criteria, the HSP Editor assigns an HSP number, notifies the HSP Author, and updates the HSP Frontmatter status attribute to `Review`.

7.1.5 **Return for Revisions**. If the HSP fails to comply with the review criteria, the HSP Editor notifies the HSP Author of the requested changes.

7.1.6 **Special cases**. Three special cases are handled as follows:

7.1.6.1 When the HSP Author does not reply to the reviews given by the HSP Editor or the Screening Committee within six months, proposals become ineligible for a vote. In this case, the HSP Editor updates the proposal Frontmatter status to `Stagnant`, and the author can resurrect it by moving it back to `Draft` at any time.

7.1.6.2 When the HSP Author withdraws the proposal before being voted on, the HSP editor updates the proposal status attribute to `Withdrawn`.

7.1.6.3 Constitutional documents and other HSPs that are continuously updated and never reach finality are assigned the HSP status attribute `Living`.

### **7.2 Onchain Submission**

7.2.1 After the Feedback and HSP Editor Review stages, if the proposal is approved by the HSP Editor, the HSP Author may submit their HSP on the voting platform, paying the submission fee. Proposals on the voting platform are tagged as `Created`.

7.2.2 If the Screening Committee approves the proposal for voting, the HSP Editor updates the HSP Frontmatter status attribute to `Voting`.

### **7.3 Screening Committee Review**

7.3.1 **Review Duration**. The Screening Committee has seven calendar days to review and provide feedback.

7.3.2 **Review decision**. The Screening Committee may request changes and decide, at its discretion, whether an HSP proposal should start as a new HSP.

7.3.3 Screening Committee Decisions may be:

7.3.3.1 **Rejection**. The Screening Committee's rejection is final. The HSP Editor updates the HSP Frontmatter status attribute of the proposal to `Rejected`. The HSP Author must draft a new proposal to resubmit.

7.3.3.2 **Approval**. Approved proposals advance to their corresponding voting track period. The HSP Editor updates the proposal's status to `Voting` in the HSP Frontmatter status attribute.

7.3.4 Screening Committee review involves discretionary governance judgment exercised in accordance with the Constitution and applicable House of Stake Constitutional Documents. Nothing in these Procedures creates a right to approval or to procedural remedies.

7.3.5 These Procedures shall be applied in a manner intended to be neutral and consistent across similarly situated proposals, subject to the discretionary judgment of the applicable governance bodies.

### **7.4 Voting Period**

7.4.1 Proposals in the Sensing track have a duration of 7 days. Regardless of the Sensing results, the HSP Author may submit the proposal in the voting platform, and repay the submission fee for the Decision track.

7.4.2 Proposals in the Decision track have a duration of 14 days.

7.4.3 If the proposal does not meet the voting threshold or the quorum, the voting platform updates its proposal tag to `Defeated`, triggering the HSP Editor to update the HSP Frontmatter status attribute to `Defeated`, too.

7.4.4 If the proposal meets the threshold, the voting platform updates its proposal tag to `Succeeded`.

### **7.5 Security Council & Director Review**

7.5.1 **Authority**. The Security Council review period is 14 days following any successful vote. The Security Council may veto or suspend, in accordance with the NEAR House of Stake Bylaws. If not vetoed, the proposal is forwarded to the NEAR House of Stake Foundation Directors for a decision on execution in accordance with their fiduciary duties and applicable law.

7.5.2 **Veto**. When vetoed by the Security Council, it publicly reports the veto and its rationale in the NEAR Forum; when vetoed by the NEAR House of Stake Foundation Director, the Foundation may choose to provide a potential path forward without creating any obligation to implement the proposal.

7.5.3 When vetoed, the HSP Editor updates the HSP Frontmatter status attribute to `vetoed`.

### **7.6 Execution**

7.6.1 The proposal is executed following the Implementation Section within the HSP.

7.6.2 Once the proposal is implemented, the HSP Editor updates the HSP Frontmatter status attribute to `Final`.

7.6.3 Implementation timelines are indicative only and may be adjusted or delayed based on legal, operational, technical, or resource constraints without creating liability or obligation.


## END OF THE NEAR HOUSE OF STAKE PROPOSALS AND VOTING PROCEDURES
</details>

## Context

The NEAR House of Stake Foundation Legal Documents state that the voting lifecycle of proposals within NEAR House of Stake is governed by NEAR House of Stake Proposals and Voting Procedures. The NEAR House of Stake Constitutional Documents further develop this reference. 

This proposal replaces the [Interim HSP-001](https://github.com/houseofstake/proposals/blob/main/HSPs/hsp-001.md) established by NEAR Foundation. 
    
The Proposals and Voting Procedures were developed through several cycles of feedback from core Stakeholder groups, in accordance with the provisions of the Foundation Legal Documents.  

## Problem

Without a formally adopted and comprehensive set of Proposals and Voting Procedures, governance processes are exposed to ambiguity in proposal handling, inconsistent application of voting rules, contested legitimacy of outcomes, and unclear accountability among governance actors. These gaps undermine confidence in decision-making, increase coordination overhead, and introduce risks of procedural disputes or governance deadlock.

## Approach

A ratified procedures instrument is preferable to fragmented guidance or discretionary convention because it produces stable expectations, reduces interpretive discretion in routine cases, and enables stakeholders to verify compliance against an explicit standard. By specifying the full lifecycle, the Procedures also reduce procedural gaps between stages that are commonly exploited by ambiguity, such as transitions from offchain review to onchain submission, or from successful vote to veto review and execution.

As much as possible, the Procedures define rules only, omitting implementation details.

A limitation of the approach within the proposed version is that it reflects only current technical, operational, and institutional capacity. As governance mechanisms evolve, the Procedures may need to be amended.

## End-to-end Value Hypothesis

On a standalone basis, this proposal delivers full value by providing an executable procedural framework for voting on proposals submitted to NEAR House of Stake.  

### Objective
Establish the ratified Proposals and Voting Procedures for NEAR House of Stake.

### Outcome
Following ratification, two outcomes are expected: 

1. Tokenholders and Governance Body members participate in the proposals and voting process, resulting in decisions that enhance the legitimacy of NEAR House of Stake, and are in the best interest of the NEAR Ecosystem.

2. Other governance documents legitimately refer to the Proposals and Voting Procedures as the governance framework for the creation, review, deliberation, and voting lifecycle of proposals within the NEAR House of Stake.

### Dependencies

This proposal depends on the NEAR House of Stake Foundation Legal Documents.  

It depends only on technical mechanisms already deployed in NEAR.  

## Key Performance Indicators (KPIs)

Not applicable to this proposal.

## Technical Specification

No software code, smart contract logic, or protocol-level changes are introduced by this proposal.

## Backwards Compatibility

The proposal is compatible with existing Foundation Legal Documents. It does not override their constitutional authority, but operationalizes their intent by defining concrete procedures.

This proposal is also compatible with the Interim Constitutional documents.

## Security Considerations

As the NEAR House of Stake employs stake-based voting, the risk of malicious proposals and governance attacks by large Tokenholders exists. The measures to mitigate these risks include the following:

* Screening Committee review and approval of proposals
* Security Council review and approval of proposals
* NEAR House of Stake Foundation Director review and execution of proposals

No additional security considerations identified.

## Stakeholders

| Activity / Decision | Responsible | Accountable | Consulted | Informed |
|--------------------|-------------|--------------|------------|-----------|
| Proposal authoring and submission | HSP Author | HSP Author | HSP Editor | NEAR forum |
| Procedural review and status updates | HSP Editor | HSP Editor | Screening Committee | NEAR forum |
| Proposal screening decisions | Screening Committee | Screening Committee | – | NEAR forum |
| Veto and execution review | Security Council and Directors | Security Council and Directors | Security Council and Directors | NEAR forum |

## Implementation Plan

Definition of Done is achieved when the Proposals and Voting Procedures payload is published in the House of Stake Documentation, its text in HSP-001 is updated, and the HSP template replaces the NEAR Forum template used when a new topic is created within the "Proposals" category.  

## Milestones

There are no Milestones applicable to this proposal.

## Budget & Resources

Not applicable.

## Conflict of Interest

The author of this proposal is @HackHumanity, which is contracted by NEAR Foundation including for the implementation of this proposal.

The production of this proposal is consistent with Hack Humanity's engagement in facilitating the [Governance Transition Program](https://gov.near.org/t/near-house-of-stake-governance-transition-program/41673). To avoid any potential conflict of interest, Hack Humanity and its team members will either not vote, or vote abstain on this proposal.

## Copyright

Copyright and related rights waived via CC0 1.0.

## Authorship & Acknowledgment  
**Authored by:**  @klausbrave, @humbertobesso, @danrandow, and @juankbell from @HackHumanity   
**Review and feedback from:**  @klausbrave, @AK_HoG, @lane, Bianca Guimaraes (NF Legal), @haenko
