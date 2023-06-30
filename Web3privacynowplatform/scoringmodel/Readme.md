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

Answers:
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

**Litentry**	

Answers:
- you can start by reading Litentry’s explainers first	
- then maybe then read through other privacy solutions to make the comparison?

_Observations_: 

_Product feature_


**BrightID**

Answers:
- You could rationalize from the fact that it does not ask you for any personally identifying information directly, so there is nothing to preserve and keep it safe in its infrastructure.	
- technical things you could ask a technical person you trust to look at its oss code.		

_Observations_: 

_Product feature_		

**Swarm**	

Answers:
- reading our whitepaper, which provides a comprehensive overview of Swarm's technology and how it achieves privacy	

_Observations_: 

_Product feature_	

**Railgun**	

Answers:
- Use @Railway_xyz to send a private transfer to a 0zk address through a Relayer. 	
- Examine the "receipt" of that transfer on etherscan or arbiscan.  You will not find: (1) sender, (2) receiver, (3) token or (4) amount anywhere in the transaction receipt.	
- There's a ton a technical person can do to verify but there's also a litmus test of #privacy that anyone can do. https://t.co/PqkUJWwmPD	
- "This is a 0zk -> 0zk transaction (sending tokens from one #DeFi user to another. 
- You'll note in the scan has a from address but this is simply a Relayer address that pays gas to process the on-chain computation.	
- User communications with a Relayer are passed via through the @waku_org p2p gossip network, so Relayers can't know a particular message origin. 
- In other words, even here #privacy was a big consideration throughout the tech stack not just on Etherscan.	
- The To address is simply the RAILGUN smart contract on @0xPolygon in this case. So nothing is revealed about the recipient.
- The value that exchanged hands? #Private
- Try to decode the input data for the transaction? It's all #encrypted.
- So how much money exchanged hands here? Well, the short answer here is - it's #private. Only the sender and recipient will know. There will be #zeroknowledge about it unless they choose to reveal the transaction information.

_Observations_: 
-

_Product feature_
-

**Penumbra**	

Answers:
- maybe look for people you trust that are able to analyze the technical solution for its privacy merits and then get their opinion ? it's prob difficult to analyze a technical protocol with a non-technical analysis.	
- what you're asking about relates to a more holistic assessment of a protocol and its attributes, so that should be within the scope of a research function moreso than a security audit function.

_Observations_: 
-

_Product feature_
-

**HOPR**	

Answers:
- FOSS. Free & Open Source Software is the foundation that enables you to check whatever you want. The hoprd client is released under GPLv3 license that allows you to do that (and also modify and re-distribute) hoprd freely: GitHub"	
- Code quality. Open source code should be readable to be helpful to you! To that end we enforce code quality via linters for Typescript
https://github.com/hoprnet/hoprnet/blob/df7bc88517329472adbfe73bd4a22bddd5cfbcc9/package.json#L46… and for our Rust code: https://github.com/hoprnet/hoprnet/blob/master/rustfmt.toml…
- Tools. So far we released tools such as http://DERP.hoprnet.org or http://mint.hoprnet.org (which in turn are obviously also FOSS!) that show shortcomings of existing technologies. We will keep building such tools also for HOPR itself."	"The exact checks you'd do depend on the application that actually use HOPR

E.g. on #RPCh we're thinking of installing a VPN server on the RPCh exit node which would visualize requests via DERP: https://twitter.com/hoprnet/status/1596896868377792520"	If you want to go hardcore, you could use a packet inspection tool such as #Wireshark to check all packets coming into your machine and going out	
- You will notice that you cannot tell anything from these packets - thanks to the Sphinx packet format that we use at HOPR:
https://twitter.com/hoprnet/status/1572601550379311104
- Check out our HOPR Basics series for more details:
https://medium.com/hoprnet/basics/home"

_Observations_: 
-

_Product feature_
-

**Waku**	

Answers:
- rfc.vac.dev is a good start. The RFC repository contains the specification of Waku and other protocols. In terms of @ethstatus's privacy claims. It is good to first look at the base layer: @waku_org
- The RFCs describe the protocol and also contains security assumptions/guarantees section."	
- The target audience are researchers and maintainers of Waku implementations. Not the easiest thing to read!

_Observations_: 
-

_Product feature_
-

**Rotki**	

Answers:
- Don't think u can. Gotta trust either me or someone who can read code	"The simplest thing a non-techie person can understand is:
- Local application with all data stored in a local encrypted database (private by design)"	
- Opensource, so your techy friend can see we are not lying. It really isn't complicated imo.
- To be 100% sure read code	
- But it does not take an expert to understand that an application that you download, run locally and keeps all data locally is 1000x more private than a webapp
- We have been brainwashed to calling webapps, as ""apps"" now.

_Observations_: 
-

_Product feature_
-

**Webb**	

Answers:
- you need to analyze the data they create through transactions. If that data (and metadata) can be analyzed for patterns then that can help define the degree of privacy of the solution.	
- For our bridge solution, this is akin to rebuilding the tx graph and seeing if flows through such a graph can be identified. The main actions in our system are deposit, transfers, and withdrawals. We use the same zero knowledge proof based ideas to make it harder to track…

_Observations_: 
-

_Product feature_
-

**Boring protocol**	

Answers:
- The "no logs" claims are generally very ambiguous. We make a point to know as little as technically possible about our users. We only know the bare minimum required to make the network function. 	
- All we know is your wallet pubkey, with which we issue and assign to a network key.

_Observations_: 
-

_Product feature_
-  

**Lit protocol**	

Answers:
- State of Network is available right here:  https://t.co/sgaOX5SPga

_Observations_: 
-

_Product feature_
-

**Alter network**	

Answers:
- "Try the #dapp and join the chatroom for @AlterDapp community	
- "You can check out this video to see how to create an account on mobile: https://youtu.be/ZgpCHDnR9WU"	
- The discord has a lot of resources as well, depending in what you need.

_Observations_: 
-

_Product feature_
- 

**Sons of crypto**	

Answers:
- We have no (google) analytics or tracking	
- We do not run any backend	
- We will have built in mixers	
- We dont know or what to know who or where users are. For non-techie that would not be straight forward. 
- Perhaps using something like https://charlesproxy.com to see all the traffic. Still fairly techie though.
- For devs all of our code is open source on github, anyone can read it.

_Observations_: 
-

_Product feature_
-

**Orbis**	

Answers:
- You can check our open-sourced SDK, but that would require people to read some code :) https://t.co/iiA7lSaDdn

_Observations_: 
-

_Product feature_
-  

**Nighthawk Wallet**	

Answers:
- "It’s been a while since @NighthawkWallet APK was analyzed for privacy concerns. Feel free to test it at @ExodusPrivacy, a friendly service to investigate Android apps. 	
- You can also obtain the @NighthawkWallet APK built with @fdroidorg and verify the “no anti-features” tag. We’ve worked hard to remove dependency on third-party services and strictly require users’ consent before opting into sharing information: https://t.co/YwYd4RUeVh	
- Anti-Features are organized into “flags” that packagers can use to mark apps, warning of possibly undesirable behaviour from the user’s perspective, often serving the interest of the developer or a third party: https://t.co/LEaBIh8LV7"

_Observations_: 
-

_Product feature_
-  

**KILT Protocol**	

Answers:
"KILT preserves privacy in the same way paper or plastic credentials do:

1. they are not stored on any central entity but totally decentralised in the wallets of their owners. 
2. users decide for what reason they share a credential with whom. 
3. one can share credentials partially"	A DID is created on the user‘s device. Like your blockchain keypair. It’s an identifier like your face, your fingerprint or your signature. It’s not issued by any entity. This way it’s always decentralised and does not have a decentralisation status.

_Observations_: 
-

_Product feature_
-			

**Onionclub**	

Answers:
- actually privacy is by default on our platform. It's not an option! 
- So, every user will have this enabled and if they want to be doxxed then they need to jump through some hoops.		

_Observations_: 
-

_Product feature_
-

**Sismo**

Answers:
- Here are the public resources we have around the core of our ZK systems: 
- Commitment mapper https://docs.sismo.io/sismo-docs/technical-concepts/commitment-mapper…
- Hydra-S1 ZK Scheme https://docs.sismo.io/sismo-docs/technical-concepts/hydra-zk-proving-schemes…	
- Privacy & Security FAQ (the less technical part): https://t.co/M3eVLoYeUK				

_Observations_: 
-

_Product feature_
-

**Krebit**	

Answers:
- Privacy-preserving: your credential's claims are stored encrypted off-chain. Self-sovereign: you control the access conditions to read your private data	
- This is possible thanks to @LitProtocol and @ceramicnetwork

_Observations_: 
-

_Product feature_
-

**Puma browser**	

Answers:
One of the reasons we started focusing more on enabling novel use-cases like ENS/HNS/IPFS and others is because it's really easy to demo in 10-15 seconds and prove, vs privacy is much harder to both demo and prove beyond company reputation.

_Observations_: 
-

_Product feature_
-
				
**Hideyour.cash** 

Answers:
- We’re in the process to conduct a security audit with a full report when going to mainnet.	
- Our code is open source in case you wanna ask someone from your trust.

_Observations_: 
-

_Product feature_
-

**Spook**	

Answers:
- If you’re non-technical you won’t be able to verify it yourself.
- You need this information from a trusted source that has done the job of checking its privacy.

_Observations_: 
-

_Product feature_
-

**Elusiv**	

Answers:
- Once we are live, detailed docs including our whitepaper will be released!	
- you can expect more explanatory content covering various topics around privacy, ZKPs, MPC and more.

_Observations_: 
-

_Product feature_
-

**Beam**	

Answers:
- You can read Beams whitepaper	
- I also recommend reading the Documentation	
- you can reach me here on Twitter, on Telegram @maxnflaxl or on Discord Maxnflaxl#8141		

_Observations_: 
-

_Product feature_
-

**Findora**	

Answers:
Dapps using our privacy SDK will allow their users to transact with privacy. The evidence can be found on our block explorer when one attempts to view the details.				

_Observations_: 
-

_Product feature_
-

**Leo wallet**	

Answers:
- Here's a talk by our co-founder/CTO discussing Zero-Knowledge Proofs in general and some features our wallet utilizes to increase privacy (e.g. single-use addresses): https://t.co/BLeKu2ghmS		

_Observations_: 
-

_Product feature_
-

**Scala**	

Answers:
- You should probably start here: https://wiki.scalaproject.io and if you have questions send us a DM.			

_Observations_: 
-

_Product feature_
-

**Media network**	

Answers:
- Thanks to the blockchain and smart contracts, your personal and payment information is always secure. 	
- Communication between clients and providers is always encrypted.	
- The client only needs to disclose the origin (i.e., the back-end IP) for the CDN marketplace and the Legacy dCDN.		

_Observations_: 
-

_Product feature_
-

**Privacy & Scalability**	

Answers:
- one approach might be looking at the public data from the system. If you see user identifiers being used only once that's perhaps helpful? But a non-technical person doesn't know if identifiers are true random, or if they're backdoored somehow.	
- With the unirep protocol we're building an explorer that shows all the things happening in the system. So a user could see their epoch keys and attestations and see how they're distinct in the system. One thing we might do is write what can and can't be determined about the different identifiers.				

_Observations_: 
-

_Product feature_
-

**Automata**	

Answers:
- You should go to the very beginning of the medium articles. There is explained how the architecture works:	
- https://medium.com/atanetwork/whats-automata-i-the-last-puzzle-piece-to-web-3-0-ea8a0af5840e
https://medium.com/atanetwork/whats-automata-ii-protocol-overview-witness-7c1fc2232655
- https://medium.com/atanetwork/whats-automata-iv-conveyor-93c9335e4f43"			

_Observations_: 
-

_Product feature_
-

**Aleo**

Answers:	
- I'd start with the official Blog articles: www.aleo.org/post/welcome-to-aleo
https://www.aleo.org/post/zero-knowledge-primitives-by-aleo	
- Hi! there are so many info you can find in blog articles :Laughheart:  unofficial! 
also there are so many videos on this topic you can find in 📸┃user-content our community has so many contributions and rich diversity of content				

_Observations_: 
-

_Product feature_
-

**MASQ**	

Answers:
- Join our beta testing group and simply try it for yourself!	
- You can run any local and in-browser IP tests you want, and use other tools to see how the data is transported to and from your machine.	
- As a non-techie the first start is simply check an IP checker website while using		

_Observations_: 
-

_Product feature_
-

**Lokinet**	

Answers:
- user education would absolutely be how. 
- To be fair lokinet's docs arent really there rn, it's always on the todo list and never really gets done.	
- once you do all the user education you can, you get to the point where you see that privacy is more of a bonus to seal the deal than a primary feature from the perspective of the consumer grade user.	
- ideally we dont want lokinet to leak anything at all. 
- net usage statistics tools from projects like pihole provide great visualizations for some of it. 
- i am sure there are ones for netflow data too not just dns. 			

_Observations_: 
-

_Product feature_
-

**ActiList**	

Answers:
We are running on the Secret Network blockchain, you can check out http://SCRT.network for more information.			

_Observations_: 
-

_Product feature_
-

**Cheqd**	

Answers:
- You can start by learning about verifiable credentials, decentralised identifiers(DID), and the concept of Self-Sovereign identity.	
- cheqd is quite technical, and in order to understand why it is privacy preserving, you'll need to get familiar with some terms.	
- "You can also learn more about each of the components of the network, the credential types, co clots of payment rails and verification by visiting our learn pages
https://t.co/8OQ0Fav16W" ("Concepts of payment rails")
- As a final note, you'll find a range of useful content and project progress on our blog. If you have any questions, you can jump on our official telegram channel or tweet us: https://t.co/wHRkrrJ3F0"		

_Observations_: 
-

_Product feature_
-

**PirateChain**	

Answers:
Look at the block explorer and see if you can figure out how much ARRR is in a wallet...	

_Observations_: 
-

_Product feature_
-

**Obscuro**	

Answers:
- we'll build tools that have been audited by trusted authorities to verify attestation of software versions along with audits showing the software doesn't leak privacy
- although superficial, our block explorers will demonstrate privacy"	
- anyone can run a node and use simple network tools to verify data flowing is encrypted
- Provide education on how TEEs preserve privacy and the things to look out for"	
- We'll deploy a game with significant funds that can only be won by breaking Obscuro's privacy. As long as the game isn't won, users can be confident privacy remains intact.			

_Observations_: 
-

_Product feature_
-

**SendingMe**	

Answers:
- you can visit  @Sending_Network account to learn more about what is under the hood	
- our GitBook is pretty easy to read even if you are not techie :)				

_Observations_: 
-

_Product feature_
-

**Mysterium Network**	

Answers:
- we would recommend our docs: https://docs.mysterium.network	
- "Also here is a study on decentralized VPN (featuring us) by @NorthwesternU, thread + paper here :https://twitter.com/MysteriumNet/status/1619616182964994049"				

_Observations_: 
-

_Product feature_
-

**nix-bitcoin**	

Answers:
- For one, you need to be fairly technical to setup nix-bitcoin at this point.	
- One important aspect is whether all outbound connections are tunnelled through Tor by default. 
- You could check the generated configuration files. For example, make sure that proxy=127.0.0.1:9050 is in fact set in /var/lib/bitcoind/bitcoin.conf.				

_Observations_: 
-

_Product feature_
-

**Litecash**	

Answers:
- Litecash is the first fork of BEAM and we tweaked the fees to zero, and less congested to keep lightning fast transaction along with a sustainable coin supply for mass adoption while keeping inflation resistance. 	
- Our privacy is built on the mimblewimble protocol which is unique compared to other privacy protocols. Litecash transactions are not held on a ledger and disappear as opposed to other methods of scrambling or clustering which could actually be decoded with new wave super computers.	
- if a transfer does not complete due to a wrong address or defunct wallet, funds get sent back to the sender within 24 hours ensuring no lost coins. 			

_Observations_: 
-

_Product feature_
-

**Black Box**	

Answers:
- For the transactions anonymizer, privacy is preserved when the onchain link between SENDER and RECEIVER wallets is broken or untraceable.					

_Observations_: 
-

_Product feature_
-

**Ergo**	

Answers:
- Ergo has the flexibility to implement privacy in various use cases. Although it is not a privacy-oriented blockchain, Sigma Protocols allow privacy-oriented dApps like ErgoMixer, or private side-chains, to obfuscate specific transactions  https://t.co/KVNIk8amD1

_Observations_: 
-

_Product feature_
-
