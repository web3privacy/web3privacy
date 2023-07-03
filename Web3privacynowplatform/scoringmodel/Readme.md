# Scoring model analytics based on a 50+ privacy projects [survey](https://docs.google.com/spreadsheets/d/1JWpAsGL10UTsVeuIVbouzUxRjaSPUAamxcbFljXuUWE/edit?usp=sharing)

**Approach**:
- we made a survey on how privacy projects recommend analysing if they are private or not.
- answers were assembled into 1 Excel sheet to be further analysed

## **Fileverse**	

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

## **Lava Network**	

Answers:
- starting with our litepaper	
- further questions feel free to drop them in our discord

_Observations_:
- "read the docs" is a popular answer without any third-party attestation that docs are correct, care for privacy etc
- Discord serves as a two-way comms platform (but depends on the project) & it creates additional dependence of user on the core team

_Product feature_
- in the future: collab with a security audit companies to create a new docs audit service description when a third-party will attest privacy-features of the initial idea x tooling description

## **Holonym**	

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

## **Spinner cash**	

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

## **Session**	

Answers
- There is the Session code audit	
- See what's being said in (non-paid) media: reviews, articles, etc.

_Observations_:
- existing audit is a plus (even if code could be updated, audit could be partial etc)
- hard to define non-paid media placements, but existing media credibility (reco by trusted people like Vitalik - is a plus)

_Product feature_:
- code audit (yes/no). Case studies (how those audits could look alike with active links)
- simplified media analysis 101

## **ZKBob**

Answers
- whether the solution forces users to preserve their privacy or if it's the user's responsibility. For example, Tornado Cash increases anonymity by requiring users to deposit a specific amount but doesn't require using different addresses for withdrawals	
- zkBOB doesn't force specific amounts or address usage, but encourages the use of new withdrawal addresses by rewarding them with a small amount of native coins that can be used in the next transaction to pay for gas.	
- How the components of the protocol communicate with each other and if users can replace any components is another important aspect.	
- In the case of zkBOB, the pool contracts are the core component, and the user needs to trust the zkBOB development team regarding privacy leaks in the rest of infrastructure: UI and the sequencer. However, the project roadmap includes plans to address these concerns.	
- Since privacy-preserving solutions on the blockchain involve complex mathematical concepts that may be difficult for non-techie individuals to understand, there will always be trust assumptions for this part of the solution.	
- "The only way for non-techie people to reduce risks is to seek expert advice or do extensive research before using such solutions. 
- For zkBOB, it's worth noting that the project is open source, the part of the protocol related to zero-knowledge was audited, and the team does its best to support documentation that's up-to-date and clear for ordinary users."

_Observations_:
- interesting approach opposite to "optional privacy" - push the person to gain privacy by performing extra actions, so privacy will be "tangible"
- privacy culture could be gamified & serve as a privacy 101 (new withdrawal addresses generation)
- "protocol components" are highly-techy issues to track
- ZK decentralisation (to be achieved) should be communicated (if you don't trust project team - that's a risk)
- trust assumption should be expanded within 101 (where exactly person "delegate" trust to the project)
- audit & trust assumptions could co-exist in 1 project, but it's critical to understand risk categories for each component of "trust"/"privacy" relations

_Product feature_:
- trust assumptions 101
- privacy in ZK 101
- later on - case studies when solutions actively embed privacy education within the workflow

## **Litentry**	

Answers:
- you can start by reading Litentry’s explainers first	
- then maybe then read through other privacy solutions to make the comparison?

Observations:
- explainers could explain privacy features but should be helpful to make self-research (to be investigated)
- not many privacy projects compare themselves within privacy features (extreme exception: Samurai team attack Wasabi) - opportunity for us

_Product feature_
- future: privacy features comparison within solutions (creating a comprehensive privacy market metrics set)

## **BrightID**

Answers:
- You could rationalize from the fact that it does not ask you for any personally identifying information directly, so there is nothing to preserve and keep it safe in its infrastructure.	
- technical things you could ask a technical person you trust to look at its oss code.		

_Observations:_
- if there's nothing to ask - there's  nothing to hide, - interesting assumption, but services could collect data without asking (like IP)
- need extra technical help to analyse the code (potential for a privacy QA automation)

_Product features:_
- privacy data leakages 101

## **Swarm**	

Answers
- reading our whitepaper, which provides a comprehensive overview of Swarm's technology and how it achieves privacy	

_Observations_:
- whitepaper is too "heavy" instrument for people with a short attention span & in need of quick attestations. Moreover, it's not up to date, usually

_Product feature_
- web3 docs 101 (basic description in relation to privacy)	

## **Railgun**	

Answers
- Use @Railway_xyz to send a private transfer to a 0zk address through a Relayer. 	
- Examine the "receipt" of that transfer on etherscan or arbiscan.  You will not find: (1) sender, (2) receiver, (3) token or (4) amount anywhere in the transaction receipt.	
- There's a ton a technical person can do to verify but there's also a litmus test of #privacy that anyone can do: https://t.co/PqkUJWwmPD	
- "This is a 0zk -> 0zk transaction (sending tokens from one #DeFi user to another). You'll note in the scan has a from address but this is simply a Relayer address that pays gas to process the on-chain computation.	
- User communications with a Relayer are passed via through the @waku_org p2p gossip network, so Relayers can't know a particular message origin. In other words, even here #privacy was a big consideration throughout the tech stack not just on Etherscan.	
- The To address is simply the RAILGUN smart contract on @0xPolygon in this case. So nothing is revealed about the recipient.
- The value that exchanged hands? #Private
- Try to decode the input data for the transaction? It's all #encrypted.
- So how much money is exchanged hands here? Well, the short answer here is - it's #private. Only the sender and recipient will know. There will be #zeroknowledge about it unless they choose to reveal the transaction information.

_Observations_
- general web3 101 is needed for a person to self-check privacy (what is 0zk address, relayer, etherscan etc)
- simple instructions on transaction traceability will help to self-check sender-receiver-token-ammount links. Input & observations criteria (possible framework?) will help here (short instruction).

_Product feature_
- transaction traceability 101 (the basics on Etherscan example)

## **Penumbra**	

Answers:
- maybe look for people you trust that are able to analyze the technical solution for its privacy merits and then get their opinion? it's prob difficult to analyze a technical protocol with a non-technical analysis.	
- what you're asking about relates to a more holistic assessment of a protocol and its attributes, so that should be within the scope of a research function moreso than a security audit function.

_Observations_: 
- complex technical protocols are inaccessible to the general public unless a third party completes a comprehensive audit from architecture to data leakages analysis 

_Product feature:_
- a checklist of when you need a "tech" person help to attest privacy features & when not (with a focus on a second scenario)

## **HOPR**	

Answers:
- FOSS. Free & Open Source Software is the foundation that enables you to check whatever you want. The hoprd client is released under GPLv3 license that allows you to do that (and also modify and re-distribute) hoprd freely.
- Code quality. Open source code should be readable to be helpful to you! To that end, we enforce code quality via linters for Typescript
https://github.com/hoprnet/hoprnet/blob/df7bc88517329472adbfe73bd4a22bddd5cfbcc9/package.json#L46… and for our Rust code: https://github.com/hoprnet/hoprnet/blob/master/rustfmt.toml…
- Tools. So far we released tools such as http://DERP.hoprnet.org or http://mint.hoprnet.org (which in turn are obviously also FOSS!) that show shortcomings of existing technologies. We will keep building such tools also for HOPR itself. The exact checks you'd do depend on the application that actually uses HOPR E.g. on #RPCh we're thinking of installing a VPN server on the RPCh exit node which would visualize requests via DERP: https://twitter.com/hoprnet/status/1596896868377792520
- If you want to go hardcore, you could use a packet inspection tool such as #Wireshark to check all packets coming into your machine and going out. You will notice that you cannot tell anything from these packets - thanks to the Sphinx packet format that we use at HOPR: https://twitter.com/hoprnet/status/1572601550379311104

_Observations_: 
- open-source basics are needed to have trust assumption that FOSS are more trustable compared to Apple, Mozilla etc (or not more, but it's a sign of reputation directly related to trust).
- readable code could be a standard for privacy attestations (for techies, obviously). If it's obscured & not audit-friendly - flag
- tools like DERP are good for transactions & tools ops traceability & should be created by the community (potential direction for us) - "DERP" for "everything"
- packets traceability is a nightmare for non-techie but could be a "level up" needed by a tech person to understand privacy leakages (via "extended audit tooling" track)

_Product feature_
- "DERP"-alike tool for the future privacy script-based "check-up" product releases

## **Waku**	

Answers:
- rfc.vac.dev is a good start. The RFC repository contains the specification of Waku and other protocols. In terms of @ethstatus's privacy claims. It is good to first look at the base layer: @waku_org
- The RFCs describe the protocol and also contain security assumptions/guarantees section."	
- The target audience are researchers and maintainers of Waku implementations. Not the easiest thing to read!

_Observations_: 
- bits of https://vac.dev/wakuv2-relay-anon could be used for educational materials, but it's still highly-technical (or even security officer-centric, researcher-ready) 

_Product feature_
- "attacks" (threats) 101

## **Rotki**	

Answers:
- Don't think u can. Gotta trust either me or someone who can read code	
- The simplest thing a non-techie person can understand are: 
- Local application with all data stored in a local encrypted database (private by design)	
- Opensource, so your techy friend can see we are not lying. It really isn't complicated imo.
- To be 100% sure read code	
- But it does not take an expert to understand that an application that you download, run locally and keeps all data locally is 1000x more private than a webapp. We have been brainwashed to call webapps, as "apps" now.

_Observations_: 
- Trust assumptions, again, are related to high risk. Trust assumptions use-cases could share light on different scenarios of trust compromises. 
- encryption 101 is needed relating to decentralised or local storage
- open-source could be a "nice to have" feature in relation to decreasing the amount of centralisation or control
- local "storage" vs "webapps" privacy scenarios are needed to explain control over the privacy leakages / negative scenarios

_Product feature_
- encryption 101

## **Webb**	

Answers:
- you need to analyze the data they create through transactions. If that data (and metadata) can be analyzed for patterns then that can help define the degree of privacy of the solution.	
- For our bridge solution, this is akin to rebuilding the tx graph and seeing if flows through such a graph can be identified. The main actions in our system are deposit, transfers, and withdrawals. We use the same zero-knowledge proof-based ideas to make it harder to track

_Observations_: 
- Zero-knowledge magic will lead to lots of privacy breakages. 

_Product feature_
- ZK x privacy 101 for future releases (like decentralised sequencer 101)

## **Boring protocol**	

Answers:
- The "no logs" claims are generally very ambiguous. We make a point to know as little as technically possible about our users. We only know the bare minimum required to make the network function. 	
- All we know is your wallet pubkey, with which we issue and assign to a network key.

_Observations_: 
- when the project claims "we don't know" - exactly this should be attested (returning to "DERP" alike solution)

_Product feature_
- pubkey, network key, viewing key etc 101

## **Lit protocol**	

Answers:
- State of Network is available right here: https://t.co/sgaOX5SPga

_Observations_: 
- state of the network isn't linked to privacy - false assumption (even if, it's too hard for a non-techie to double-check it)

## **Alter network**	

Answers:
- Try the #dapp and join the chatroom for @AlterDapp community	
- You can check out this video to see how to create an account on mobile: https://youtu.be/ZgpCHDnR9WU	
- The discord has a lot of resources as well, depending on what you need.

**Observations**: 
- Product usage rarely has sophisticated UX/UI that could correspond privacy features in a simple way with proves
- Projects use socials like Discord to share product-centric materials (from analytics to audits) while websites are not often updated

## **Sons of crypto**	

Answers:
- We have no (google) analytics or tracking	
- We do not run any backend	
- We will have built-in mixers	
- We don't know or what to know who or where users are. For non-techie that would not be straightforward. 
- Perhaps using something like https://charlesproxy.com to see all the traffic. Still fairly techie though.
- For devs all of our code is open source on github, anyone can read it.

_Observations_: 
- Tracking could be by a third party like Google (also compromises privacy & fake conscious consent)
- External services like Charleproxy is really valuable, but create a burden on a non-techie, because of it's complexity (but will work for a techie)
- GitHub (updated, alive) could be a checkmark (formal)

**Product feature**
- GitHub basic score (flag system could be a part of the second product release)
- List of external third-party resources in a Wiki (for those, who like to make extra effort -> influence micro-services creation)

## **Orbis**	

Answers:
- You can check our open-sourced SDK, but that would require people to read some code :) https://t.co/iiA7lSaDdn

_Observations_: 
- SDK is just too technical

## **Nighthawk Wallet**	

Answers:
- It’s been a while since @NighthawkWallet APK was analyzed for privacy concerns. Feel free to test it at @ExodusPrivacy, a friendly service to investigate Android apps. 
- You can also obtain the @NighthawkWallet APK built with @fdroidorg and verify the “no anti-features” tag. 
- We’ve worked hard to remove dependency on third-party services and strictly require users’ consent before opting into sharing information: https://t.co/YwYd4RUeVh	
- Anti-Features are organized into “flags” that packagers can use to mark apps, warning of possibly undesirable behaviour from the user’s perspective, often serving the interest of the developer or a third party: https://t.co/LEaBIh8LV7"

_Observations_: 
- existing third-party allows checking privacy validity (but it's not up to date)
- "no anti-features" should be researched further for qualitative recommendations (DYOR track)
- consent in the web3 privacy services is a field for further research (how it differs from web3 GDPR-centric consent, do services share their state of privacy features etc?) 

_Product feature_
- "Anti-features" 101

## **KILT Protocol**	

Answers:
KILT preserves privacy in the same way paper or plastic credentials do:

1. they are not stored on any central entity but totally decentralised in the wallets of their owners. 
2. users decide for what reason they share a credential with whom. 
3. one can share credentials partially"	A DID is created on the user‘s device. Like your blockchain keypair. It’s an identifier like your face, your fingerprint or your signature. It’s not issued by any entity. This way it’s always decentralised and does not have a decentralisation status.

_Observations_: 
- web2 product comparison with the web3 is a valuable hint to not necessarily expect 100% privacy if it's a format, or product feature (not a bug) - applicable to a whole category
- "free to share" ability could be communicated as a person's agency over privacy (similar to the "viewing key" approach in ZK)
- a link between the different parts of DID should be more explored (like how age or geo could lead to identity discovery)

_Product feature_
- did 101 (with a focus on the linkage between different data types)	

## **Onionclub**	

Answers:
- actually, privacy is by default on our platform. It's not an option! 
- So, every user will have this enabled and if they want to be doxxed then they need to jump through some hoops.		

_Observations_: 
- lack clear attestation

_Product feature_
- web3 comms 101 (with a focus on misleading comms that create an obscure understanding of the tech/product)

## **Sismo**

Answers:
- Here are the public resources we have around the core of our ZK systems: 
- Commitment mapper https://docs.sismo.io/sismo-docs/technical-concepts/commitment-mapper…
- Hydra-S1 ZK Scheme https://docs.sismo.io/sismo-docs/technical-concepts/hydra-zk-proving-schemes…	
- Privacy & Security FAQ (the less technical part): https://t.co/M3eVLoYeUK				

_Observations_: 
- all concepts are too technical, & FAQ is missing from the docs

## **Krebit**	

Answers:
- Privacy-preserving: your credential's claims are stored encrypted off-chain. 
- Self-sovereign: you control the access conditions to read your private data	
- This is possible thanks to @LitProtocol and @ceramicnetwork

_Observations_
- self-sovereignty is still an obscure concept for many people online. Especially, when technical concepts like "access conditions" are shared with people
- it's important to share public audits if a product uses privacy features of a third party (the more services are involved in the tech link - the easier is to obscure people's attention & understanding of privacy stack)

## **Puma browser**	

Answers:
One of the reasons we started focusing more on enabling novel use-cases like ENS/HNS/IPFS and others is because it's really easy to demo in 10-15 seconds and prove, vs privacy is much harder to both demo and prove beyond company reputation.

_Observations_: 
- marketing language creates a vague understanding of privacy features. Moreover, people are bombarded by web3 slang, and third-party services & can't test privacy features with ease
				
## **Hideyour.cash** 

Answers:
- We’re in the process to conduct a security audit with a full report when going to mainnet.	
- Our code is open source in case you wanna ask someone from your trust.

_Observations_: 
- would be good if services will share their security audit plans with a clear roadmap. Having a public commitment to privacy could be a part of positive behavior on behalf of the tech teams

_Product feature_
- security audits 101 (basics)

## **Spook**	

Answers:
- If you’re non-technical you won’t be able to verify it yourself.
- You need this information from a trusted source that has done the job of checking its privacy.

_Observations_: 
- which leads to a necessity to have three actors relations: product-"trusted source"-person ("privacy trilemma") 

_Product feature_
- trusted sources checklist (&/or a list)

## **Elusiv**	

Answers:
- Once we are live, detailed docs including our whitepaper will be released!	
- you can expect more explanatory content covering various topics around privacy, ZKPs, MPC and more.

_Observations_: 
- no whitepaper, no docs - could be a soft flag on privacy features (more open data = higher potential privacy rate). Where "having a whitepaper" is a plus, but not a silver bullet

_Product feature_
- web3 open-source checklist (soft screening like whitepaper (yes/no), docs (yes/no) etc) 

## **Beam**	

Answers:
- You can read Beams whitepaper	
- I also recommend reading the Documentation	
- you can reach me here on Twitter, on Telegram @maxnflaxl or on Discord Maxnflaxl#8141		

_Observations_: 
- many projects still project "trust source" on themselves. Without sharing the results of hacker bounties, public QA, whitehacker audits & so on. The culture of third-party public discussions is almost non-existent (to be researched why except the price of audits)

## **Findora**	

Answers:
Dapps using our privacy SDK will allow their users to transact with privacy. The evidence can be found on our block explorer when one attempts to view the details.				

_Observations_: 
- block explorers aren't made for the general public to understand the data flow (this could lead in the future to a human-friendly block explorer x privacy education)

## **Leo wallet**	

Answers:
- Here's a talk by our co-founder/CTO discussing Zero-Knowledge Proofs in general and some features our wallet utilizes to increase privacy (e.g. single-use addresses): https://t.co/BLeKu2ghmS	

_Observations_: 
- visuals complimentary to the interview help to navigate non-techies with ease on the privacy subject. One of the rare projects talking about the limitations of their tech (o ZK tech in general). But still, everything related to ZK (proving schemes, for example) is highly technical.
- ZK-products will see lots of exploitations & bugs in the future, so it's important to educate people on the state of general tech, so they won't transfer all the sensitive data because of the hype, attention etc

_Product feature_
- ZK 101 (with a focus on privacy, not scalability)

## **Scala**	

Answers:
- You should probably start here: https://wiki.scalaproject.io and if you have questions send us a DM.			

_Observations_: 
- again, projects don't care about privacy validation as if it's a default trustless state. Which is incorrect.
- the general wiki isn't the best source of knowledge (one opposite positive example: Waku)

## **Media network**	

Answers:
- Thanks to the blockchain and smart contracts, your personal and payment information is always secure. 	
- Communication between clients and providers is always encrypted.	
- The client only needs to disclose the origin (i.e., the back-end IP) for the CDN marketplace and the Legacy dCDN.		

_Observations_: 
- people could be misinformed about the way blockchain works thinking that security means privacy
- encryption doesn't mean you don't leak your data to RPC, hosting etc. Cross-services/products relations to data leakages should become a market standard of comms (example: using one privacy tool that is private, but connecting it to another that leaks your data equals privacy breaches).

_Product feature_
- web3 privacy 101 (focus on a misleading comms like blockchain security equals privacy)

## **Privacy & Scalability**	

Answers:
- one approach might be looking at the public data from the system. If you see user identifiers being used only once that's perhaps helpful? But a non-technical person doesn't know if identifiers are truly random, or if they're backdoored somehow.	
- With the unirep protocol we're building an explorer that shows all the things happening in the system. So a user could see their epoch keys and attestations and see how they're distinct in the system. One thing we might do is write what can and can't be determined about the different identifiers.				

_Observations_: 
- hackathons on user identification could help to empower product privacy. Whitehackers role in a privacy market could be uplifted to a degree of product self-check/health check providing additional avenues for a third-parties to contribute to the open-source meaningfully.
- identifiers could be created with a maximum anonymity set (and almost no linkage to a real person unlike a Covid passport)

_Product feature_
- different self-check recommendations by security audits, white hackers as a supplement (how would you test product privacy)

## **Automata**	

Answers:
- You should go to the very beginning of the medium articles. There is explained how the architecture works:	
- https://medium.com/atanetwork/whats-automata-i-the-last-puzzle-piece-to-web-3-0-ea8a0af5840e
https://medium.com/atanetwork/whats-automata-ii-protocol-overview-witness-7c1fc2232655
- https://medium.com/atanetwork/whats-automata-iv-conveyor-93c9335e4f43"			

_Observations_: 
- all materials are outdated & not supplied by a third-party attestation
- medium is a centralised platform that could be edited at any time (read: information could be forged)
- projects are creating long-reads as if people have a conscious need to dive deep on their journey of a product audit (misconception or you could say "web3 privacy products biases")

_Product feature_
- part of the wiki: web3 privacy products biases (in relation to privacy features x user experience)

## **Aleo**

Answers:	
- I'd start with the official Blog articles: www.aleo.org/post/welcome-to-aleo
https://www.aleo.org/post/zero-knowledge-primitives-by-aleo	
- also there are so many videos on this topic you can find in 📸┃user-content our community has so many contributions and rich diversity of content				
_Observations_: 
- products or ecosystem bombard people with messy content the same way as corporations (so answers can't be found fast & with the 1 link)

## **MASQ**	

Answers:
- Join our beta testing group and simply try it for yourself!	
- You can run any local and in-browser IP tests you want, and use other tools to see how the data is transported to and from your machine.	
- As a non-techie the first start is simply to check an IP checker website while using		

_Observations_: 
- testing group or phase is a healthy point to the ecosystem & understanding the state of privacy and communal trust (test sandbox with a friendly UX/UI could be a solution here)
- data transportation is a challenge (here we get back with the "DERP") to be explored

_Product feature_
- web3-native IP-checker for a beta version
- web3-native privacy features checker to be R&D (what could be automated & coded for QA-automation) 

## **Lokinet**	

Answers:
- user education would absolutely be how. 
- To be fair lokinet's docs aren't really there rn, it's always on the todo list and never really gets done.	
- once you do all the user education you can, you get to the point where you see that privacy is more of a bonus to seal the deal than a primary feature from the perspective of the consumer-grade user.	
- ideally, we don't want Lokinet to leak anything at all. 
- net usage statistics tools from projects like pihole provide great visualizations for some of it. 
- I am sure there are ones for netflow data too not just dns. 			

_Observations_: 
- docs validity & proficiency is a hard field to analyse. Even the most up-to-date docs could be obscure & vague.
- privacy as a bonus field should be more explored (when a person moves from a user-friendly, let's say, dVPN to a really private one) & mapped down as a user-flow
- pihole is highly complex for a non-techie, but we could encourage services to prove via self-tests (blog posts, videos) when they test & prove how exactly private their services are raising a culture of privacy 

_Product feature_
- "net usage stats" services guide for the end user (but with a focus on empowering product managers to incorporate third-party tools to self-check their products & publicly report on their privacy features)

## **ActiList**	

Answers:
We are running on the Secret Network blockchain, you can check out http://SCRT.network for more information.			

_Observations_: 
- product is obscuring the state of privacy to a bigger ecosystem entity without simple proves (usually, because such projects lacks privacy/security engineers in their teams)

## **Cheqd**	

Answers:
- You can start by learning about verifiable credentials, decentralised identifiers(DID), and the concept of Self-Sovereign identity.	
- cheqd is quite technical, and in order to understand why it is privacy-preserving, you'll need to get familiar with some terms.	
- "You can also learn more about each of the components of the network, the credential types, co-clots of payment rails and verification by visiting our learn pages
https://t.co/8OQ0Fav16W" ("Concepts of payment rails")
- you'll find a range of useful content and project progress on our blog. If you have any questions, you can jump on our official telegram channel or tweet us: https://t.co/wHRkrrJ3F0"

_Observations_: 
- verifiable credentials are still highly technical (although, Dock is trying to simplify end-user understanding) in times when DID is one of the most common use-cases for the web3. Technical complexity created a challenge for non-techie to understand the state of privacy (especially, when it requires dozens of ours of reading materials & new skills development like doc reading, code analysis etc)

_Product feature_
- privacy-preserving vocabulary

## **PirateChain**	

Answers:
Look at the block explorer and see if you can figure out how much ARRR is in a wallet	

_Observations_: 
- obscure & too technical

## **Obscuro**	

Answers:
- we'll build tools that have been audited by trusted authorities to verify attestation of software versions along with audits showing the software doesn't leak privacy
- although superficial, our block explorers will demonstrate privacy"	
- anyone can run a node and use simple network tools to verify data flowing is encrypted
- Provide education on how TEEs preserve privacy and the things to look out for"	
- We'll deploy a game with significant funds that can only be won by breaking Obscuro's privacy. As long as the game isn't won, users can be confident privacy remains intact.			

_Observations_: 
- "trusted authorities" should be investigated: what are their types, why they are "authorities", who authorise them etc
- block explorers demonstrate privacy to a tech people
- "anyone can run a node" is a false concept, because it's a highly technical procedure
- privacy gamification test is a nice demonstration of "unbreakability" (or a public commitment to privacy) - it's similar to whitehackers bounties

_Product feature_
- examples of how products enhance privacy creatively (like a game mention by Obscuro) -> potential market benchmarks

## **SendingMe**	

Answers:
- you can visit @Sending_Network account to learn more about what is under the hood	
- our GitBook is pretty easy to read even if you are not techie :)				

_Observations_: 
- too technical

## **Mysterium Network**	

Answers:
- we would recommend our docs: https://docs.mysterium.network	
- Also here is a study on decentralized VPN (featuring us) by @NorthwesternU, thread + paper here: https://twitter.com/MysteriumNet/status/1619616182964994049"		

_Observations_: 
- third party study could be a nice entry into a category understanding (not directly linked with the project, team)

_Product feature_
- useful links (like dVPN studies in a DYOR section)

## **nix-bitcoin**	

Answers:
- For one, you need to be fairly technical to setup nix-bitcoin at this point.	
- One important aspect is whether all outbound connections are tunnelled through Tor by default. 
- You could check the generated configuration files. For example, make sure that proxy=127.0.0.1:9050 is in fact set in /var/lib/bitcoind/bitcoin.conf.				
_Observations_: 
- if a product requires tech proficiency - it's important to highlight it (entry-level into tech understanding)
- Tor is a plus1 to privacy, but not a silver bullet (important to understand "privacy enhancement" & not just "1 solution to general privacy")
- configuration files can't be checked by non-techies (but could be used as a signal on privacy transparency - if service hides clues on how to self-check it's privacy credibility or not)

_Product feature_
- "privacy stack" enhancement prototyping (1 solution + 1 solution = privacy "2x" (like Session messenger + dVPN)

## **Litecash**	

Answers:
- Litecash is the first fork of BEAM and we tweaked the fees to zero, and less congested to keep lightning-fast transaction along with a sustainable coin supply for mass adoption while keeping inflation resistance. 	
- Our privacy is built on the mimblewimble protocol which is unique compared to other privacy protocols. Litecash transactions are not held on a ledger and disappear as opposed to other methods of scrambling or clustering which could actually be decoded with new wave super computers.	
- if a transfer does not complete due to a wrong address or defunct wallet, funds get sent back to the sender within 24 hours ensuring no lost coins. 			

_Observations_: 
- a fork can be misleading to non-techies mistaking it for a core protocol or misunderstanding as an original product
- third party tech is proven within another community, original protocol engineers &/or researchers which could obscure search on audits, privacy validity
- DeFi features aren't equal privacy features

_Product feature_
- forkability x privacy 101
- privacy tech vocabulary (mimblewimble, scrambling, clustering etc)

## **Black Box**	

Answers:
- For the transactions anonymizer, privacy is preserved when the onchain link between SENDER and RECEIVER wallets is broken or untraceable.					
_Observations:_ 
- general privacy storytelling missing proof on untraceability (linkage between sender & receiver)

_Product feature:_
- private transactions 101 

## **Ergo**	

Answers:
- Ergo has the flexibility to implement privacy in various use cases. Although it is not a privacy-oriented blockchain, Sigma Protocols allow privacy-oriented dApps like ErgoMixer, or private side-chains, to obfuscate specific transactions  https://t.co/KVNIk8amD1

_Observations:_ 
- important to understand that protocols could be non-private, but activate private use-cases (partial implementation). Separate core tech from privacy narrative

_Product feature:_
- case-studies (privacy matching): protocol = transparent, but use-cases = private (like Ethereum)

# Product summary

_Education track 101_
* privacy tech vocabulary (mimblewimble, scrambling, clustering etc)
* open source 101 (short version)
* e2ee 101
* social recovery 101
* missing 3rd party audit potential risks 101
* simplified media analysis 101
* trust assumptions 101
* privacy in ZK 101
* privacy data leakages 101
* "attacks" (threats) 101
* encryption 101
* transaction traceability 101 (the basics on Etherscan example)
* web3 docs 101 (basic description in relation to privacy)
* pubkey, network key, viewing key etc 101
* "Anti-features" 101
* did 101 (with a focus on the linkage between different data types)
* web3 comms 101 (with a focus on misleading comms that create an obscure understanding of the tech/product)
* security audits 101 (basics)
* web3 privacy 101 (focus on a misleading comms like blockchain security equals privacy)
* forkability x privacy 101

_Validity_
* documentation: exists/missing (+/-)
* 3rd party list (yes/no) from security audit agencies to independent security engineers (+their reputation 101 in later versions)
* website checklist (1-2-3-4-5..., yes/no validity)
* code audit (yes/no). Case studies (how those audits could look alike with active links)

_Checklists_
* trusted sources checklist (&/or a list)
* web3 open-source checklist (soft screening like whitepaper (yes/no), docs (yes/no) etc)
* different self-check recommendations by security audits, white hackers as a supplement (how would you test product privacy)
* GitHub basic score (flag system could be a part of the second product release)
* a checklist of when you need a "tech" person help to attest privacy features & when not (with a focus on a second scenario)

_Additional content_
- case studies when solutions actively embed privacy education within the workflow
* List of external third-party resources in a Wiki (for those, who like to make extra effort -> influence micro-services creation)
* case-studies (privacy matching): protocol = transparent, but use-cases = private (like Ethereum)
* future: privacy features comparison within solutions (creating a comprehensive privacy market metrics set)
* later on - case studies when solutions actively embed privacy education within the workflow
* "net usage stats" services guide for the end user (but with a focus on empowering product managers to incorporate third-party tools to self-check their products & publicly report on their privacy features)
* "privacy stack" enhancement prototyping (1 solution + 1 solution = privacy "2x" (like Session messenger + dVPN)
* examples of how products enhance privacy creatively (like a game mentioned by Obscuro) -> potential market benchmarks
* part of the wiki: web3 privacy products biases (in relation to privacy features x user experience)

_DYOR section_
* useful links (like dVPN studies in a DYOR section)

_Automation (beta)_
* "DERP"-alike tool for the future privacy script-based "check-up" product releases
* web3-native IP-checker for a beta version
* web3-native privacy features checker to be R&D (what could be automated & coded for QA-automation)

_Future releases_
* in the future: collab with a security audit company to create a new docs audit service description when a third party will attest privacy features of the initial idea x tooling description
