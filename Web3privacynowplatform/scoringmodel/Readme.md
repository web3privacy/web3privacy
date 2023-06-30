Scoring model analytics based on a 50+ privacy projects [survey](https://docs.google.com/spreadsheets/d/1JWpAsGL10UTsVeuIVbouzUxRjaSPUAamxcbFljXuUWE/edit?usp=sharing)

**Approach**:
- we made a survey on how privacy projects recommend analysing if they are private or not.
- answers were assembled into 1 Excel sheet to be further analysed

**Fileverse**	

Answers:
- open sourcing our work
- you literally generate and download your own e2ee keys
- documentation
- social recovery options

_Observations_: 
- open source non-techies should know what "open source" means & how to measure it (solution: Open source 101 education)
- key ownership is another knowledge person should know (contrast: Google or Meta "owns" your ID/key) + e2ee 101 is a must here
- clicking on the documentation link & understanding it are different skills
- social recovery is a less techy assessment & is linked to a persona (data ownership)

_Product feature_
- open source 101 (short version)
- e2ee 101
- documentation: exists/missing (+/-)
- social recovery 101

**Lava Network**	

Answers:
- starting with our litepaper	
- further questions feel free to drop them in our discord

_Observations_:
- "read the docs" is a popular answer without any third-party attestation that docs are correct, care for privacy etc
- Discord serves as a two-way comms platform (but depends on the project) & it creates additional dependence of user on the core team

_Product feature_
- in the future: collab with a security audit companies to create a new docs audit service description when a third-party will attest privacy-features of the initial idea x tooling description

**Holonym**	

Answers:
- Check their website or docs	
- If they vaguely say “data is kept private” and provide no explanation how, run	
- If they provide an explanation, check with an expert or DYOR

_Observations_:
- "check" is a highly abstract action related to the website or docs -> extract value should be related to understanding "privacy"-validity markers
- "private data explainers" needed to be defined within use-cases (case studies for the market)


_Product feature_:
- website checklist (1-2-3-4-5..., yes/no validity)
- case studies "private data" explainers
- DYOR (that's our platform)

**Spinner cash**	

Answers
- code is law. 
- So how about "don't trust, verify"?	But to verify, it would require certain technical skills... like reading source code 😅	
- We hope to bring in 3rd party auditors at some point

_Observations_:
- the more ideological language is on the website - the harder to navigate the factual privacy features 
- source code reading is a highly technical skill (moreover: Ethereum dev could struggle with Solana code & vice versa)
- 3rd party list is needed here to be transformed into privacy signalling features

_Product feature_:
- missing 3rd party audit potential risks 101
- 3rd party list (yes/no) from security audit agencies to independent security engineers (+their reputation 101 in later versions)

**Session**	

Answers

- There is the Session code audit	
- See what's being said in (non-paid) media: reviews, articles, etc.

_Observations_:
- existing audit is a plus (even if code could be updated, audit could be partial etc)
- hard to define non-paid media placements, but existing media credibility (reco by trusted people like Vitalik - is a plus)

_Product feature_:
- code audit (yes/no). Case studies (how those audits could look alike with active links)
- simplified media analysis 101

**ZKBob**

Answers

- ZKBob	hether the solution forces users to preserve their privacy or if it's the user's responsibility. For example, Tornado Cash increases anonymity by requiring users to deposit a specific amount, but doesn't require using different addresses for withdrawals	
- zkBOB doesn't force specific amounts or address usage, but encourages the use of new withdrawal addresses by rewarding them with a small amount of native coins that can be used in the next transaction to pay for gas.	
- How the components of the protocol communicate with each other and if users can replace any components is another important aspect.	
- In the case of zkBOB, the pool contracts are the core component, and the user needs to trust the zkBOB development team regarding privacy leaks in the rest of infrastructure: UI and the sequencer. However, the project roadmap includes plans to address these concerns.	
- Since privacy-preserving solutions on the blockchain involve complex mathematical concepts that may be difficult for non-techie individuals to understand, there will always be trust assumptions for this part of the solution.	
- "The only way for non-techie people to reduce risks is to seek expert advice or do extensive research before using such solutions. 
- For zkBOB, it's worth noting that the project is open source, the part of the protocol related to zero-knowledge was audited, and the team does its best to support documentation that's up-to-date and clear for ordinary users."

