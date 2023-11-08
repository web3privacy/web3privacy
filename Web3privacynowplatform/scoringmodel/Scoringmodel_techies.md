# Privacy scoring modelling > Web3privacy now analytical [platform](https://github.com/Msiusko/web3privacy/tree/main/Web3privacynowplatform)

# General
| Scoring  | Techie |
| ------------- | ------------- |
| Immutability | + |
| Decentralised throughout, including hosting | + |
| Permissionless & accessible to all | + |
| Open-source | + | 
 
# Docs
| Scoring  |  Techie |
| ------------- | ------------- |
| read the documentation | + |
| Good and comprehensive documentation | + |

# Third-party analysis
| Scoring  | Techie |
| ------------- | ------------- | 
| Where's the code? Has it been audited? | + |
| Validation by trusted and respected independent scientists and researchers | + |

# Team
| Scoring  | Techie |
| ------------- | ------------- | 
| ideological team | + |
| Reputation of the team | + |
| is it purely marketing oriented, or it seems created by researchers/developers, are the developers anons? | + |

# Privacy policy
| Scoring  | Techie |
| ------------- | ------------- | 
| Privacy Policy content | + |
| Non-vague and non-intrusive privacy policy | + |

# Infrastructure
| Scoring  | Techie |
| ------------- | ------------- | 
| How much to run a node |  + |
| Where are the nodes | + |
|  Number of nodes/servers/ -> the larger the footprint the best privacy | + |

# Storage
| Scoring  | Non-web3 person assesment | Web3, but non-tech assesment |
| ------------- | ------------- | ------------- |
|  e2e encrypted LOCAL storage | - | + |
| What user information is stored? (username, IP address, last connection, wallets associate, etc) | - | + |
| Where is it stored? (centralized server, certain jurisdictions, on-chain, in browser/local cache) | - | + |

# Data aggregation
| Scoring  | Non-web3 person assesment | Non-tech assesment |
| ------------- | ------------- | ------------- |
| no email or tel nr for signup | + | + |
| control over personal data | - | - |
| does not implement KYC or AML | + | + |
| Metadata privacy / Minimal to no metadata capture | - | - |

# Traction
| Scoring  | Non-web3 person assesment | Non-tech assesment |
| ------------- | ------------- | ------------- |
| Amount of transactions  | + | + |
| number of people using it | + | + |
| is it famous | + | + |
| Latency  | - | - |
| Time of test and battle-tested code - (e.g. how BSC had passed the stress time of withdrawals with FTX drama or crypto schemes such as ECDSA with more than 2-3 decades alive)  | - | - |
| Cost  | - | + |

# Governance
| Scoring  | Non-web3 person assesment | Non-tech assesment |
| ------------- | ------------- | ------------- |
| DAO structure (if applied)  | - | + |

# Privacy execution
| Scoring  | Non-web3 person assesment | Non-tech assesment |
| ------------- | ------------- | ------------- |
| How is it being transmitted? (encrypted, unencrypted, offuscated, etc)  | - | - |
| Combined those encryption methods effectively (holistic solution) | - | - |
| Confidentiality of transactions | - | - |
| the ability to hide transactional data from the public | - | - |
| strong encryption algorithms | - | - |
| If the speed in connection is too fast, there most probably no privacy there and rather a direct channel between user - app | - | - |
| p2p / no central server | - | - |
| Trustless - No ID required (this is where ZKs are useful) | - | + |
| Usage of ZK | - | - |

# Product-centric
| Scoring  | Non-web3 person assesment | Non-tech assesment |
| ------------- | ------------- | ------------- |
| Onboarding steps  | + | + |
| Usability - for end users or in the developer experience if it is a B2B project. | + | - |

# Testing
| Scoring  | Non-web3 person assesment | Non-tech assesment |
| ------------- | ------------- | ------------- |
| Ability to run part of the service and verify for myself  | - | - |
| try to trace a transaction | - | - |
| There is a way to verify the code I think is running, really is running e.g. attestation service | - | - |
| Other tooling to verify e.g. block explorers  | - | + |

# Other
| Scoring  | Non-web3 person assesment | Non-tech assesment |
| ------------- | ------------- | ------------- |
| Entropy (non-trivial to estimate, different measurements for type of service). Some examples: https://arxiv.org/abs/2211.04259 or https://blog.nymtech.net/an-empirical-study-of-privacy-scalability-and-latency-of-nym-mixnet-ff05320fb62d  | - | - |
| Censorship-resistant (how hard it's for a powerful party to block/censor a given service)  | - | - |
| Precise description of the concrete privacy properties. Privacy is complicated, so if they don't say exactly what they protect, then its likely vapour  | - | - |
| Doesn’t sell your data  | - | - |
| protects against a global passive adversary  | - | - |
| strong secure anonymity tech  | - | - |
| Credibly neutral  | + | + |
| ISO/IEC 29190:2015: https://www.iso.org/standard/45269.html  | - | - |
| Anonymity Assessment – A Universal Tool for Measuring Anonymity of Data Sets Under the GDPR with a Special Focus on Smart Robotics: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3971139 | - | - |

_Huge thanks everyone who contributed! I make it anon now, but will thank everyone (who would liked to be credited) once a scoring model will be published on GitHub for community evaluation._

# 2. My personal notes on privacy scoring (they were made before communal survey)
_Sketches what could be put inside privacy-solutions scoring model_ (note: think of these as questions to experts for a workshop on scoring ideation).

**Key observations**

| Topic  | Observation |
| ------------- | ------------- |
| Broad range of different takes on privacy assesment | Privacy experts have around 50+ tips |
| Tech-centricity of assesment | Majority of the expert takes are hard to execute by non-tech people (they need info-help!) |
| Privacy assessment takes enormous time | Time-To privacy-fit - potential for analytical service |
| Privacy literacy isn't enough | The scoring model demand both "decentralisation", "open-source" & "privacy" topics understanding |
| Mix of objective & subjective takes |  Scoring criteria are different from objective (example: transaction traceability) & subjective (example: backed by a16z crypto) takes  |

**Open-source transparency**
- **GitHub repos**: # of commits, # stars, date of repo creation.

**Third-party validation**
- **Security audits**: yes, no; type of audit; ammount of audits.

**Community validation**
- Existing bugs
- White hackers assessment (like Secret Network TEE bug)
- Negative Discord, Twitter, other public feedback (product & founder-centric)

**Team**
- Market validation
- GitHub contribution
- Track record (incl. red flag projects)

**Financials**
- Investments
- TVL (like Aztec's L2)
- Donation-based
- Public treasury

**Liveliness**
- How active is GitHub activity 
- How active is the community
- Is there public product traction?

**Product-readiness**
- State of product-readiness
- MVP-readiness
- Protocol (test-net/main-net)
- dApp (release timing, third-party validation like AppStore/Play Store)
- network-reliability (the state of privacy in Ethereum, Solana, Avalanche etc)

**Cross-checked data leakage**
- Complementing privacy stack data leakage (example: phone + dApp; wallet + RPC etc)
- Third-party data leakage (from the hackers to state agents (think of Iran or North Korean govs))

**Data aggregation policies**

_Reference_: https://tosdr.org 

**Centralisation level (incl KYC)**

Reference: https://kycnot.me/about#scores
