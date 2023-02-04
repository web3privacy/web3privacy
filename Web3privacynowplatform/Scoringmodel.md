# Privacy scoring modelling research

**Approach**

| Phase  | Description |
| ------------- | ------------- |
| 1. **Expert take**  | Outreach privacy experts behind core privacy services - aggregate their professional opinions on how to analyze if a service is truly private or not.) |
| 2. **Scoring model prototyping**  | Create an open & flexible scoring model for a communal feedback loop - share with the privacy community, evaluate. |
| 3. **Scoring model MVP release**  | Deliver balanced model for privacy services assessment - powered by pros & general public opinions. |

# Current status (4.02.2023)

![alt text](https://github.com/Msiusko/web3privacy/blob/main/Web3privacynowplatform/Staticobjects/Screenshot%202023-02-04%20at%2017.03.45.png?raw=true)

## On-going community research (survey) within the privacy experts. 
I asked experts behind privacy-services or contributors to the privacy-centric communities to share their visions on analysing whether a service is private. Answers were collected via chats & survey [form](https://forms.gle/ETBEZed9LUUtLWT87)

**Criteria**:
- min 50 different experts
- a broad range of positions: tech, ops, marketing, devrel, strategy
- a broad range of services: from privacy coins to mixnets
- different geographies: from the USA to Russia

# Questions from the privacy experts

# Take 1
- does it has traceability? (ie addresses is hidden from the public ledger)
- does it has unlinkability? (ie transactions can't be linked to each other)
- does the amount of transfer is hidden? 
- does IP addresses of participants hidden? 
- is it decentralized and based on open-source technology? 

# Take 2

| Question  | Observation |
| ------------- | ------------- |
| much the users in control of their data disclosure?  | (Scale 1-10) |
| how well community feedback and evaluation is built into product dev? | the less -» the more centralized it is -» the smaller the % of it staying private without collective intelligence. This is like the web3privacynow  - platform part, actually, for sales, but also I found this really relevant. |
| is there a community bug/security bounty program/platform?  | yes, no |
| how much transparent disclosure is available on the tech and company | like smart contract audits, security audits, source of financing?   |
| how private the tech stack it uses on all layers. from hardware to l3/l4 etc.  | how well it is disclosed what they built on and where they host stuff, or if the tech is decentralized like nym - is there available dashboard data about this? |
| product roadmap and release flexibility - this is a harder one, and I'm not sure it makes sense. What I mean is it's also important to have a clear vision while reacting to current needs/bugs /fixing vulnerabilities.  | maybe its redundant with no2 and no2b |

# Take 3
1. What are the trust assumptions the user has by using the platform?
2. What and how is user information stored and transmitted?
3. How much PII is stored/collected?
4. How is information collected + processed + disseminated
5. How completely can you participate with total privacy?

# Take 4

| Direction  | Observation |
| ------------- | ------------- |
| network privacy  | how do you connect to the chain? Can you do it via Tor? |
| blockchain privacy  | do the resulting on-chain transactions offer the user any on-chain obfuscation? |
| censorship resistance  | how resistant is the project to external pressure? Will the project censor you? |
| permission  | do I need to create an account to access the thing, or is the thing open access? |
| custody of funds  | is the user out of control of their keys at any point? |

# Categorisation

## Contents
- [General](#General)
- [Docs](#Docs)
- [Third-party analisys](#Third-party-analisys)
- [VCs](#VCs)
- [Team](#Team)
- [Privacy policy](#Privacy-policy)
- [Token](#Token)
- [Infrastructure](#Infrastructure)
- [Storage](#Storage)
- [Data aggregation](#Data-aggregation)
- [Traction](#Traction)
- [Governance](#Governance)
- [Privacy execution](#Privacy-execution)
- [Product-centric](#Product-centric)
- [Testing](#Testing)
- [Other](#Other)

# General
- Immutability 
- Decentralised throughout, including hosting
- Permissionless & accessible to all
- Open source
 
# Docs
- read the documentation
- Good and comprehensive documentation

# Third-party analisys
- ask about its weaknesses from competitors
- Number of peer-reviewed articles at conferences and journals of team members
- Where's the code? Has it been audited?
- Validation by trusted and respected independent scientists and researchers

# VCs
- Who are the VCs
- not funded by big US VCs like a16z

# Team
- ideological team
- Reputation of the team
- is it purely marketing oriented, or it seems created by researchers/developers, are the developers anons?

# Privacy policy
- Privacy Policy content
- Non-vague and non-intrusive privacy policy
- #privacy protection policies

# Token
- is there a token since the beginning?
- if the token since beginning - weird

# Infrastructure
- How much to run a node. 
- Where are the nodes
- Number of nodes/servers/ -> the larger the footprint the best privacy

# Storage
- e2e encrypted LOCAL storage
- What user information is stored? (username, IP address, last connection, wallets associate, etc)
- Where is it stored? (centralized server, certain jurisdictions, on-chain, in browser/local cache)

# Data aggregation
- no email or tel nr for signup
- control over personal data
- does not implement KYC or AML
- Metadata privacy / Minimal to no metadata capture

# Traction
- Amount of transactions 
- number of people using it
- is it famous
- Time of test and battle-tested code - (e.g. how BSC had passed the stress time of withdrawals with FTX drama or crypto schemes such as ECDSA with more than 2-3 decades alive) 
- Latency
- Cost

# Governance
- DAO structure (if applied)

# Privacy execution
- How is it being transmitted? (encrypted, unencrypted, offuscated, etc)
- Confidentiality of transactions
- the ability to hide transactional data from the public
- strong encryption algorithms
- If the speed in connection is too fast, there most probably no privacy there and rather a direct channel between user - app
- p2p / no central server
- Reliant on one encryption method or multiple
- Combined those encryption methods effectively (holistic solution)
- Trustless - No ID required (this is where ZKs are useful)
- Usage of ZK

# Product-centric
- Onboarding steps
- Usability - for end users or in the developer experience if it is a B2B project.

# Testing
- Ability to run part of the service and verify for myself
- try to trace a transaction
- There is a way to verify the code I think is running, really is running e.g. attestation service
- Other tooling to verify e.g. block explorers 

# Other
- Entropy (non-trivial to estimate, different measurements for type of service). Some examples: https://arxiv.org/abs/2211.04259 or https://blog.nymtech.net/an-empirical-study-of-privacy-scalability-and-latency-of-nym-mixnet-ff05320fb62d
- Censorship-resistant (how hard it's for a powerful party to block/censor a given service)
- Precise description of the concrete privacy properties. Privacy is complicated, so if they don't say exactly what they protect, then its likely vapour
- Doesn’t sell your data
- protects against a global passive adversary
- strong secure anonymity tech
- Credibly neutral
- ISO/IEC 29190:2015: https://www.iso.org/standard/45269.html
- Anonymity Assessment – A Universal Tool for Measuring Anonymity of Data Sets Under the GDPR with a Special Focus on Smart Robotics: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3971139

# My personal notes on privacy scoring (they were made before communal survey)

_Sketches what could be put inside privacy-solutions scoring model_ (note: think of these as questions to experts for a workshop on scoring ideation).

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
