**Privacy scoring options to consider**

**Note**: _final scoring model shouldn't be too complex to execute._

_Sketches what could be put inside privacy-solutions scoring model_ (note: think of these as questions to experts for workshop on scoring ideation).

**Open-source transparency**
- **GitHub repos**: # of commits, # stars, date of repo creation.

**Third party validation**
- **Security audits**: yes, no; type of audit; ammount of audits.

**Community validation**
- Existing bugs
- White hackers assesment (like Secret Network TEE bug)
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
- How active is community
- Is there a public product traction?

**Product-readiness**
- State of product-readiness
- MVP-readiness
- Protocol (test-net/main-net)
- dApp (release timing, third party validation like AppStore/Play Store)
- network-reliability (the state of privacy in Ethereum, Solana, Avalanche etc)

**Cross-checked data leakage**
- Complementing privacy stack data leakage (example: phone + dApp; wallet + RPC etc)
- Third party data leakage (from the hackers to state agents (think of Iran or North Korea govs))

**Data aggregation policies**

_Reference_: https://tosdr.org 

**Centralisation level (incl KYC)**

Reference: https://kycnot.me/about#scores

## *On-going community research (survey) within the privacy experts 
**all answers on how to score services privacy (non-redacted)**:

_Questions to be observed_
- does it has untracebility ? (ie addresses is hidden from public ledger)
- does it has unlinkability? (ie transactions can't be linked between each other)
- does amount of transfer is hidden? 
- does IP address of participants hidden? 
- is it decentralized and based on opensource technology ? 

1)  much the users in control of their data disclosure? (Scale 1-10)
2) how well commnity feedback and evaluation is built into product dev? (the less -» the more centralised it is -» the smaller the % of it staying private without the collectiv intelligence. this is like the web3privacynow  - platform part actually, for sales but also i found this really relevant.
2/b) is there a community bug / security bounty program / platform? 
3) how much transparent disclosure is avaliable on the tech and company - like smart contract audits, security audits,source of financing?
4) how private the tech stack it uses on all layers. from hardware to l3/l4 etc. how well it is disclosed what they built on and where they host stuff, or if the tech is decentralised like nym - is there avaialbe dashboard data about this?
5) product roadmap and release flexibiity - this is harder one, and I'm not sure it makes sense. what i mean is its also important to have a clear vision but at the same time to react to current needs / bugs / fixing vulnerabilities. maybe its redundant with no2 and no2b

1. What are the trust assumptions the user has by using the platform?
2. What and how is user information stored and transmitted?
3. How much PII is it stored/collected?
4. How is information collected + processed + disseminated
5. How completely you can participate with total privacy?

1) network privacy -  (how do you connect to the chain? can you do it via Tor?) 
2) blockchain privacy - (do the resulting on chain transactions offer the user any on chain obfuscation?)
3) censorship resistance - (how resistant is the project to external pressure. will the project censor you?)
4) permission - (do I need to create an account to access the thing or is the thing open access?)
5) custody of funds - (at any point is the user out of control of their own keys?)

**Categories**
 
**Docs**
- read the documentation
- Good and comprehensive documentation

**Third-party analisys**
- ask about its weaknesses from competitors
- Number of peer reviewed articles at conferences and journals of team members
- Where's the code, has it been audited

**VCs**
- Who are the VCs
- not funded by big US VCs like a16z

**Team**
- ideological team
- Reputation of team
- is it purely marketing oriented or it seems created by researcher/developers, are the developers anons?

**Privacy policy**
- Privacy Policy content
- Non-vague, and non-intrusive privacy policy
- #privacy protection policies

**Token**
- is there a token since the beginning ?
- if token since beginning, weird

**Infrastructure**
- How much to run a node. 
- Where are the nodes
- Number of nodes/servers/ -> the larger the footprint the best privacy

**Storage**
- -e2e encrypted LOCAL storage
- What user information is stored? (username, IP address, last connectino, wallets associate, etc)
- Where is it stored? (centralized server, certain jurisdictions, on chain, in browser/local cache)

**Data aggregation**
- no email or tel nr for signup
- control over personal data

**Traction**
- Amount of transactions 
- number of people using it
- is it famous

**Governance**
- DAO structure (if applied)

**Privacy execution**
- How is it being transmited? (encrypted, unencrypted, offuscated, etc)
- Confidentiality of transactions
- ability to hide transactional data from the public
- strong encryption algorithms
- If the speed in connection is too fast most probably there no privacy there and rather a direct channel between user - app
- p2p / no central server
- Reliant on one encryption method or multiple
- Combined those encryption methods effectively (holistic solution)
- Trustless - No ID required (this is where ZK's are useful)

**Other**
- Time of test and battletested code - (e.g. how BSC had passed the stress time of withdrawals with FTX drama or crypto schemes such as ECDSA with more than 2-3 decades alive)
Metadata privacy
- Cost
- Latency
- Entropy (non-trivial to estimate, different measurements for type of service) some examples:
- https://arxiv.org/abs/2211.04259
- https://blog.nymtech.net/an-empirical-study-of-privacy-scalability-and-latency-of-nym-mixnet-ff05320fb62d…
- Censorship-resistant (how hard it's for a powerful party to block/censor a given service)
- Onboarding steps
- Immutability 
- Decentralised throughout, including hosting
- Permissionless & accessible to all
- try to trace a transaction
- Precise description of the concrete privacy properties. Privacy is complicated so if they don't say exactly what they protect, then its likely vapor
- Usability - for end users or in the developer experience if it is a B2B project.
- Validation by trusted and respected independent scientists and researchers
- Open source
- There is a way to verify the code I think is running, really is running e.g. attestation service
- Ability to run part of the service and verify for myself
- Other tooling to verify e.g. block explorers 
- Open source/FOSS
- Minimal to no metadata capture
- Doesn’t sell your data
- protects against global passive adversary
- does not implement kyc or aml
- strong secure anonymity tech
- Decentralized 
- Credibly neutral
- Usage of ZKP
