# The Weekly Governance Cycle

The Weekly Governance Cycle is formalized within the Governance Scope of the [Atlas](https://sky-atlas.powerhouse.io/#A.1.9_Weekly_Governance_Cycle-95671ce7-60d8-4d8e-b9b6-de7493560308|0db3) and provides a predictable weekly framework for recurring operational decisions.

The Weekly Governance Cycle comprises two distinct subsets:
- [Operational Weekly Cycle](https://sky-atlas.powerhouse.io/#A.1.9.1_Operational_Weekly_Cycle-b189fa17-57a9-4d4e-9780-0ce4efd94211|0db30308)
- [Atlas Edit Weekly Cycle](https://sky-atlas.powerhouse.io/#A.1.9.2_Atlas_Edit_Weekly_Cycle-4a8ad9ad-5c5d-4994-9b46-f04c0e61ce59|0db30308)

Both Weekly Cycles work in conjunction with the [Monthly Governance Cycle](https://sky-atlas.powerhouse.io/#A.1.10_Monthly_Governance_Cycle-54d76c73-366a-453f-92e6-13e775ef326e|0db3). They permit recurring decisions to be made that require quicker action than is allowed by the Monthly Governance Cycle.

## Operational Weekly Governance Cycle 

### Overview

The Operational Weekly Cycle is implemented via Governance Polls and Executive Votes, which are controlled by Governance Facilitators listed in the [Atlas List of Responsible Facilitators](https://sky-atlas.powerhouse.io/#A.1.6.2.3.1_List_of_Responsible_Facilitators-37c513ee-cc53-4626-84dd-c50800a2b747|0db334351551bcec). 

- A **Weekly Poll** (”Governance Poll” or “Poll”) is a non-binding Governance Poll that determines the bi-weekly Executive Vote contents. Weekly Polls cannot change system parameters independently; they merely dictate what will be included in the next Executive Vote. Governance Polls occur on-chain and are used to measure the sentiment of MKR voters. The Governance Facilitators may create proposals using the Weekly Governance Cycle to enable them to fulfill their responsibilities.

- A **Non-Standard Weekly Poll** ("Signal Request") is a non-binding Weekly Poll that contains arbitrary time-sensitive decisions. These polls need to be expedited through the Maker governance process via a separate vote. The use of Non-Standard Weekly Polls is exclusive to Facilitators, given that they have already established a high level of trust with the community. The use of Non-Standard Weekly Polls is limited to situations where the Weekly Governance Cycle is determined to operate too slowly to be usable. If a Non-Standard Weekly Poll  has been proposed, it will also be put in the Weekly Poll. The creation of a Non-Standard Weekly Poll requires an urgent and apparent reason from a timing perspective to justify it, and is only permitted when it is specifically triggered and required by the Atlas.

- An **Executive Vote** (also "Executive") is a formalized governance proposal that requires on-chain voting. Through the Executive Vote mechanism, MKR holders steward Maker Governance by voting on Executive proposals that pertain to operations maintaining the Protocol. Executive Votes execute technical changes to the Maker Protocol. The Executive Vote occurs approximately every two weeks. Its contents are often determined by weekly Governance Polls, however, the Atlas can explicitly authorize proposals to go directly to an Executive Vote.

### Related Definitions

- The term **‘Executive’** or **‘Executive Vote’** is used in all instances where the formal governance vote is being referenced.
- The term **‘Executive Process’** refers to the end-to-end process of the development of an Executive Vote, in which Facilitators, spell teams (also referred to collectively as the “Governance Security Engineering Team”) and other recognized Ecosystem Actors participate.
- The term **‘Spell’** or **‘Executive Spell’** refers to the smart contract that executes the changes to the protocol approved by Maker Governance in an Executive Vote. Generally, when referring to spell team operations and their technical outcome or product (including code base, code operations, code reviews and code quality), the term ‘spell’ will be used
- The term **‘Spell Process’** or **‘Executive Spell Process’** refers to the end-to-end process of developing a spell, a process in which the Governance Facilitators and the current spell team participate. The term ‘spell development process’ is a subset of the ‘spell process’ and pertains solely to the technical development of the spell by the current spell team.

---

### Full Cycle Breakdown

**Monday, T-10**

- Every Monday, the Weekly Operational Cycle begins and includes standard recurring decisions proposed in the form of a weekly poll. Operational Weekly Cycle proposals (”proposals”) can be proposed by Facilitators and recognized Ecosystem Actors. The proposals should be posted to the Maker Forum by previous Friday at 8:00 am UTC to ensure the Governance Facilitators have sufficient time to prepare the needed polls for the following Monday. After confirming that the proposer has the authority to request a poll, the relevant Scope Facilitator must post an explicit approval of the poll request as a reply to the proposer’s Forum thread. The Governance Facilitators must then prepare and publish the Governance Poll. The Operational Weekly Cycle polls run for three days. Polls often run concurrently, allowing voters to participate in any number of them at the same time.

**Friday, T-6**

- The Governance Facilitators confirm the Executive Vote contents with respective Content Liaisons (i.e. relevant Scope Facilitators, Advisory Councils, and other recognized Ecosystem Actors) and with the technical spell team. They will also confirm that the contents meet Governance requirements and standards, as per the Atlas.

**Monday, T-3**

- The Governance Facilitators will prepare the Executive Vote and hand the instructions for Executive spell to the spell team. Spell team will craft and review the spell between Monday and Thursday.

**Thursday, T0**

- Spell team will deploy the spell on both testnet and mainnet, and hand it over to the Governance Facilitators.
- Governance Facilitators will review the spell's contents and, if everything is correct, add spell address to the Executive Vote.
- Governance Facilitators will add the Executive Vote to the voting portal and communicate this to the MakerDAO Community. The Weekly Operational Executive Vote has an expiration of thirty days.

### Edits To The Atlas

The Operational Weekly Cycle may be used to edit the Atlas, but only if the pertinent Atlas document specifies that it, or a related unit of governance logic which it expressly controls, is modifiable through the Operational Weekly Cycle.
The general rule is that an Operational Weekly Cycle proposal requires a Governance Poll followed by an Executive Vote. The general rule, by default, is assumed wherever the Atlas provides that a document, or a unit of governance logic controlled by said document, is modifiable through the Operational Weekly Cycle. Any exception to the general rule must be specifically stated in the pertinent Atlas document. The possible exceptions include documents that can be modified subject to a Governance Poll only; and documents that can be modified subject to an Executive Vote only, without requiring a previous Governance Poll.

## Atlas Edit Weekly Governance Cycle

### Overview & Principles

The Atlas Edit Weekly Cycle is implemented via **Weekly Governance Polls**. In the transition to Endgame, the Atlas can be edited through the submission of an **Atlas Edit Weekly Cycle Proposal** (also "Weekly Cycle Proposal", "Proposal", or “AEW Proposal"). 

The following rules apply to Atlas Edit Weekly Cycle:
- Multiple amendments to multiple components of the Atlas are allowed to be submitted in a single Weekly Cycle Proposal.
- A single Weekly Cycle Proposal may seek to remove multiple components of the Atlas.
- Atlas Edit Weekly Cycle Proposals cannot include language that aims to prevent other Atlas Edit Weekly Cycle Proposals from editing the same component of the Atlas within the same Governance Cycle.
- If Multiple Atlas Edit Weekly Cycle Proposals editing the same component of the Atlas are approved by voters in the same Governance Cycle, the Reconciliation Process must be followed:

   - Non-conflicting/ logically compatible edits will be consolidated by Governance Facilitators in a transparent way, available for examination prior to the end of the relevant polls.

  - Conflicting / logically incompatible edits that cannot be coherently reconciled will be enclosed in a poll for voters to chose which one they wish to accept. For two conflicting Atlas Edit Weekly Proposals, a binary vote will be held. For three and more conflicting Atlas Edit Weekly Cycle Proposals, the Governance Facilitators may choose a suitable polling method that allows voters to choose between multiple options. The difference between the conflicting amendments must be clearly presented so that voters can make an informed choice on their preferred option.

  - A Reconciliation Process Poll will take place during the Operational Weekly Cycle immediately following the closure of the originating polls. The Reconciliation Process Poll will last for three days.

- Atlas Edits must always adhere to the Spirit of the Atlas and remain within the bounds of Universal Alignment.

### Full Cycle Breakdown

**Before Friday T-3 8:00 UTC**

The Authors post their Proposals in the Maker Forum in the appropriate category and signal their intent to submit them to the Weekly Cycle. Aligned Delegates (including Prime Delegates) are prohibited from authoring an Atlas Edit Weekly Cycle Proposal.

A Prime Delegate triggers the Proposal by posting a reply to the Author’s Weekly Cycle Proposal on the Forum, signalling clearly their intent to trigger the Weekly Cycle Proposal. An Atlas Edit Weekly Cycle Proposal can only be triggered by a Prime Delegate whose AD Buffer contains at least one month’s worth of [budget](https://sky-atlas.powerhouse.io/#A.1.5.8.1_Budget_Amount_For_Prime_Delegate_Slots-a8a767c3-9594-4e84-aa14-51829c6264f5|0db3af4ece0cd3aa) at the time of triggering the Proposal. Prime Delegates must “stake” their AD Buffer to trigger a Proposal. 

**Before Monday T0 16:00 UTC**

Governance Facilitators review the triggered Atlas Edit Weekly Cycle Proposals to ensure they meet the established requirements, and that they are aligned with the spirit of the Atlas. The Governance Facilitators can reject an Atlas Edit Weekly Cycle Proposal if they deem it to be misaligned. If a Facilitator rejects an Atlas Edit Weekly Cycle Proposal for misalignment, the Prime Delegate who triggered the poll loses their AD buffer.

**Monday T0 16:00 UTC**

The Governance Facilitators publish the set of Governance Polls representing the accepted Atlas Edit Weekly Cycle Proposals to the community Github and the official Voting Portal. The Polls run for three days. Atlas Edit Weekly Cycle Proposals must have at least 20.000 MKR of Yes votes to be accepted. Successful polls trigger direct edits to the Atlas. If the Proposal is voted down or does not reach the minimum quorum, proposed changes have no effect on the Atlas, and the Prime Delegate triggering the Proposal loses their staked AD Buffer.


>Page last reviewed: 2024-11  
>Next review due: 2025-11  
