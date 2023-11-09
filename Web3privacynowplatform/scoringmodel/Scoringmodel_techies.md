# Privacy scoring modelling > Web3privacy now analytical [platform](https://github.com/Msiusko/web3privacy/tree/main/Web3privacynowplatform)

# MVP for non-tecies expanded to techies

**Sandbox: DeFi category that has been analyzed**

**How to use sandbox?**
1. Read takeaways.
2. Give us feedback via general comments in the Community on [Signal](https://chat.web3privacy.info/) or make a Pull request here.
3. You can always explore 38 DeFi project' assessment [here](https://github.com/web3privacy/web3privacy/blob/main/Web3privacynowplatform/scoringmodel/DeFi%20category%20prototype.md)

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
* Are there external contributors outside of the team members?
* What are licenses in use?

**example**: _Free & Open Source Software is the foundation that enables you to check whatever you want. The hoprd client is released under [GPLv3 license](https://github.com/hoprnet/hoprnet/blob/master/LICENSE) that allows you to do that (and also modify and re-distribute) Hoprn freely_

**Docs**
- read the documentation: is it comprehensive?
- how well-written are privacy & security assumptions/guarantees?
- if aplicable: how well-written is encryption method? [example](https://developer.litprotocol.com/v3/sdk/access-control/encryption)

**Team**
* Check if there are known contributors (reputation 101)
* Check commits at GitHub
* How many community contributors beyond core team?
* How many technical specialists in the team?
* How mature are core contributors (previous projects, GitHub commits)?

**Third-party audit**
- Were bugs fixed?
- How centralized is the protocol governance?
- How centralized are product updates?

**Infrastructure**
| Scoring  | Techie |
| ------------- | ------------- | 
| Where are the nodes (check block explorer) | + |
| Number of nodes/servers/ (the larger the footprint the best privacy) | + |

**Data aggregation**
| Scoring  | Techie |
| ------------- | ------------- |
| no email or tel number for signup | + |
| does not implement KYC or AML | + |
| What user information is stored? (username, IP address, last connection, wallets associate, etc) | + |

**Traction**
| Scoring  | Techie |
| ------------- | ------------- | 
| Amount of transactions  | + |
| number of people using it | + |

**Governance**
| Scoring  | Techie |
| ------------- | ------------- |
| DAO structure (if applied)  | + |

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
| Privacy Policy content | + |
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

## Testing
| Scoring  | Techie |
| ------------- | ------------- |
| try to trace a transaction | + |
| Other tooling to verify e.g. block explorers  | + |
