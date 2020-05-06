# Minimum Viable Governance
This document describes the Minimum Viable Governance of Social Dist0rtion Protocol.

## Language
The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "NOT RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [BCP 14](https://tools.ietf.org/html/bcp14) \[[RFC2119](https://tools.ietf.org/html/rfc2119)\] \[[RFC8174](https://tools.ietf.org/html/rfc8174)\] when, and only when, they appear in all capitals, as shown here.

## Goverance
Governance is the sum of all Dist0rtion Improvement Proposals (DIPs) contained in the master branch of this repository.

### Improve it
Anyone can open a pull request to this repository to submit a new DIP. If the pull request is approved by the majority of the owners, it is then merged to master, becoming part of the governance.

## Funds
The funds of the DAO are managed by the multi signature wallet deployed in the Main Ethereum Network at the address `0x527621278422FFf45A66f7086bAeAC770CF12b69`

The multi signature wallet defines a *set of owners* and a *number of required confirmations* to execute transactions.

## Proposals
Anyone can make a **proposal** by opening an issue in any repository of the Social Dist0rtion Protocol organization on GitHub.

The proposal MUST contain:
- The *problem* being addressed.
- The *solution* proposed.

The proposal MAY contain:
- An *estimated effort*.
- The *payment conditions*.

The author of the proposal has the responsibility to gauge interest around their work, but it is not an obligation of the DAO to take their work into consideration.

If the proposal is to be resolved on-chain (payments, minting, adding and removing owners, ...), owners MAY vote "yes" by confirming the proposed transaction in the multi signature wallet.

Any other proposal can be voted by the owners in the comment section of the issue. If the number of "yes" votes is equal to the *number of required confirmations* defined in the multi signature wallet, then the proposal is implemented.

## Owner's Responsibilities
The correct functioning of the DAO depends on the conduct of its owners.

Every owner is REQUIRED to follow those rules:
- Backup their keys, and store them securely.
- Immediately report lost or stolen keys to the other owners.
- Be responsive to evaluate a proposal when asked by another owner.
