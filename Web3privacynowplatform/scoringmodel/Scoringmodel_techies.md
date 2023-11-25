# Privacy scoring modelling > Web3privacy now analytical [platform](https://github.com/Msiusko/web3privacy/tree/main/Web3privacynowplatform)

_Currently we are surveying developers, security engineers and  researchers to find out bottle necks & potential room for growth within privacy features assessment by techies._ 

## Core user group (techies definition):
- junior or general devs with under 1-year web3 coding experience
- poor security auditing skills
- general interest in privacy tech

## Why this group
- general public within the devs landscape is the most vulnerable audience compared to mature decs with connections & experience
- generalisation helps to make universal tooling & secure research from the niche approaches

## General scoring will consist of
- audit check up (manual)
- scoring features
- dev toolkit
- DYOR expanded track (subjective observations)

## Quick take from market assessment 
- devs lack the basics of security audits (while auditing companies or security engineers create piles of written that require lots of dev hours to read & more to understand)
- case studies could help to "visualize" the assessment journey
- DB of the malicious practices & critical bugs within the privacy landscape will come in handy for practical devs

**Hypothesis**: can the market create a standard of cross-project privacy features check-up increasing general privacy stack levelling? 

**Crucial scoring context**: time on research x potential amount of privacy anti-features detection. Meaning that scoring could be scalable if more people will use it under the economy, general business & without expert knowledge level.

# MVP for non-techies expanded to techies

**Sandbox: DeFi category that has been analyzed**

**How to use sandbox?**
1. Read scoring assumptions below.
2. Give us feedback via Pull request here.
3. You can always explore [scoring MVP](https://mirror.xyz/0x0f1F3DAf416B74DB3DE55Eb4D7513a80F4841073/90XEXa7AG_qc-VgYKs40i88xB1HF97gr1zqb-qvnif0) based on 38 DeFi project' assessment [here](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/DeFi%20category%20prototype.md)

**important note**: here "techies" covers "juniors" & general "developers" (masses) & not aplicable to "lead", "seniors" or even "mid"-devs (core devs).

# Scoring model 1.2: validity track

_Validity track covers GitHub, Product-readiness, Team, Docs, Audit._

**Note**: quick assessment helps to decrease privacy dark patterns from obscure language to test-net claiming it has a "state of art privacy".
![alt text](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/staticobjects/Scoring%201.2%20validity%20track.png?raw=true)

## Sandbox

**Extended scoring 1.0**
| Project | GitHub | Product-readiness | Team | Docs | Audit | Contributors | Licenses | Support | Score |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| **Test project** | available & active GitHub / not (25%) | Live or 🚧 (exclusion criteria) | public team / not (25%) | available & not marketing docs / not (25%) | available & up to date third-party audit / not (25%) | external contributors outside of the team members | What licenses are in use | Some form of support available? (telegram, discord, forum) | from 0 to 100% |
| **score** | 12.5% | 12.5% | 12.5% | 12.5% | 12.5% | 12.5% | 12.5% | 12.5% | 100% |

**Updates 1.1**

**GitHub**
* Is it in stable release, 1.0 and not an alpha or untested code?
* Are there many PRs and Issues pending?
* Are there external contributors outside of the team members? [Waku example](https://github.com/waku-org/go-waku)
* What are licenses in use? [Privy Apache-2.0 license](https://github.com/privy-io/shamir-secret-sharing)

**example**: _Free & Open Source Software is the foundation that enables you to check whatever you want. The hoprd client is released under [GPLv3 license](https://github.com/hoprnet/hoprnet/blob/master/LICENSE) that allows you to do that (and also modify and re-distribute) Hoprn freely_

**Docs**
- read the documentation: is it comprehensive?
- how well-written are privacy & security assumptions/guarantees?
- if aplicable: how well-written is encryption method? [example](https://developer.litprotocol.com/v3/sdk/access-control/encryption)
- is Whitepaper marketing or dev-centric?

**Team**
* Check if there are known contributors (reputation 101)
* Check commits at GitHub
* How many community contributors beyond core team?
* How many technical specialists in the team?
* How mature are core contributors (previous projects, GitHub commits)?

**Third-party audit**
- Were bugs fixed? [Zokyo x Railgun_ example, p.7](https://assets.railgun.org/docs/audits/2023-02-03%20Zokyo.pdf)
- How centralized are product updates?

**Infrastructure**
| Scoring  | Techie |
| ------------- | ------------- | 
| Where are the nodes (check block explorer) [Nym mainnet explorer](https://explorer.nymtech.net) | + |
| Number of nodes (the larger the footprint the best privacy) | + |

**Data aggregation**
| Scoring  | Techie |
| ------------- | ------------- |
| no email or tel number for signup | + |
| does not implement KYC or AML | + |
| What user information is stored? (username, IP address, last connection, wallets associate, etc) | + |

**Traction**
| Scoring  | Techie |
| ------------- | ------------- | 
| Amount of transactions (Dune, DeFi Lama, block explorer etc) | + |
| number of people using it | + |

**Governance**
| Scoring  | Techie |
| ------------- | ------------- |
| DAO structure (if applied)  | + |
| How centralized is the protocol governance? [Railgun_ governance docs](https://docs.railgun.org/wiki/rail-token/protocol-governance) | + |

**Traceability**

example:
1. Use @Railway_xyz to send a private transfer to a 0zk address through a Relayer. 
2. Examine the "receipt" of that transfer on etherscan or arbiscan.  You will not find: (1) sender, (2) receiver, (3) token or (4) amount anywhere in the transaction receipt.

https://t.co/PqkUJWwmPD
* This is a 0zk -> 0zk transaction (sending tokens from one #DeFi user to another. You'll note that the scan has a from address but this is simply a Relayer address that pays gas to process the on-chain computation).
* User communications with a Relayer are passed via through the @waku_org p2p gossip network, so Relayers can't know a particular message origin. In other words, even here #privacy was a big consideration throughout the tech stack not just on Etherscan.
* The To address is simply the RAILGUN smart contract on @0xPolygon in this case. So nothing is revealed about the recipient.
* The value that exchanged hands? #Private
* Try to decode the input data for the transaction? It's all #encrypted.
* So how much money exchanged hands here? Well, the short answer here is - it's #private. 
* Only the sender and recipient will know. There will be #zeroknowledge about it unless they choose to reveal the transaction information.

# Backlog

## General
| Scoring  | Techie |
| ------------- | ------------- |
| Immutability | + |
| Decentralised throughout, including hosting | + |
| Permissionless & accessible to all | + |
| Open-source | + | 

## Privacy policy
| Scoring  | Techie |
| ------------- | ------------- | 
| Privacy Policy content [Railway zero data aggregation PP](https://www.railway.xyz/privacy.html) | + |
| Non-vague and non-intrusive privacy policy | + |

## Storage
| Scoring  | Techie |
| ------------- | ------------- | 
| e2e encrypted LOCAL storage | + |
| Where is it stored? (centralized server, certain jurisdictions, on-chain, in browser/local cache) | + |

## Privacy execution
| Scoring  | Techie |
| ------------- | ------------- | 
| p2p / no central server | + |
| Trustless - No ID required (this is where ZKs are useful) | + |

**example**: "with the unirep protocol we're building an explorer that shows all the things happening in the system. So a user could see their epoch keys and attestations and see how they're distinct in the system. One thing we might do is write what can and can't be determined about the different identifiers".

## Testing
| Scoring  | Techie |
| ------------- | ------------- |
| try to trace a transaction | + |
| Other tooling to verify e.g. block explorers  | + |

## Hardcore

from community

* use a packet inspection tool such as #Wireshark to check all packets coming into your machine and going out
* using something like https://charlesproxy.com to see all the traffic
* Android: Feel free to test it at [Exodus Privacy](https://exodus-privacy.eu.org/en/), a friendly service to investigate Android apps. 
* Android: check https://f-droid.org and verify the “no anti-features” tag (like dependency on third-party services). [Example](https://f-droid.org/en/packages/com.nighthawkapps.wallet.android/)

# ETHSecurity community recommendations
_We asked Ethereum security chat members to share guides that devs could use to check privacy features of a given dApp or a protocol. Here are the first tips:_

[DeFiSafety](https://medium.com/defi-safety/introducing-our-0-9-process-79ba88f8bba4): "a clear list of what a dev should add to a protocol (over and above the software)"

**Officercia** recommendations
- [The ultimate security checklist](https://www.beirao.xyz/blog/Security-checklist)
- [Tips for Solidity Code Auditors](https://github.com/OffcierCia/tips-solidity-code-auditors)
- [Minimum viable security plans from Trail of Bits](https://docs.google.com/document/d/1-_0Wlwch_vtkPM4F-SdEXLjQYaYT7KoPlU2rjt7tkLQ/edit)
- [Opinionated security and code quality standard for Solidity smart contracts](www.github.com/Rari-Capital/solcurity)

[SCSVS](https://github.com/ComposableSecurity/SCSVS/): Smart Contract Security Verification Standard

[EthTrust](https://entethalliance.github.io/eta-registry/security-levels-spec.html): EEA EthTrust Security Levels Specification v-after-1
