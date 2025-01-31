# Main dataset of [Ethereum Privacy Ecosystem report](https://docs.web3privacy.info/research/ethereum-privacy-ecosystem)

_Here we track all Ethereum privacy related projects, research & events (based on Web3privacy now general DB)_

## Current phase: Ethereum Privacy DB aggregation
1. Filtering out non-Ethereum projects from our main DB.
2. Adding new positions like EIP-7503

## Important note
Later on DB will be re-organized within Ethereum-centric (build on solidity), ETH-centric (DeFi allowing to bridge, swap ETH) & EVM-comatible or multichain projects.
Segmentation will help to split "native" projects & broader actors serving different chains. Plus it will map the nature of privacy within Ethereum Privacy Stack.

![alt text](https://github.com/web3privacy/docs/blob/main/docs/assets/Types%20of%20projects%20contributing%20to%20Ethereum%20privacy.png?raw=true)

## Categories
  - [DeFi](#defi)
  - [Currency](#currency)
  - [Infrastructure](#infrastructure)
  - [Wallet](#wallet)
  - [Computing network](#computing-network)
  - [Layer 2](#layer-2)
  - [Hardware](#hardware)
  - [DID](#did)
  - [DAO](#dao)
  - [Bridge](#bridge)
  - [Messaging](#messaging)
  - [Browser](#browser)
  - [KYC](#kyc)
  - [RPC](#rpc)
  - [Storage](#storage)
  - [dApps](#dapps)
  - [NFT](#nft)
  - [R\&D](#rd)
  - [Node](#node)
  - [Mixing services](#mixing-services)
  - [Other](#other)
  - [Events](#events)
  - [Network state](#network-state)
  - [Papers](#papers)
  - [Privacy & Scaling Explorations](#privacy-&-scaling-explorations)

# Ethereum-centric

## DeFi
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/DEFI.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team | Docs | Audit |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- | ------------- | ------------- |
| [Firn Protocol](https://app.firn.cash) | Firn is the first-ever zero-knowledge privacy platform in the _account-based_ model, and introduces pluggable, flexible privacy to Ethereum-based chains. ✨️**ZK** | ([GitHub](https://github.com/firnprotocol)) | live, june 2022 | Ethereum | anon | [Docs](https://docs.firn.cash) | [BlockSec](https://github.com/blocksecteam/audit-reports/blob/main/solidity/blocksec_firnprotocol_v1.0-signed.pdf) |
| [0xbow](https://www.0xbow.io) | privacy orientated infrastructure for the next generation of regulated DeFi | - | - | Ethereum | public | - | - |
| [Night](https://night.finance) | A Stealth Address-Powered Private and Composable Account Layer for Ethereum | - | TBD | Ethereum | anon | [whitepaper](https://night.finance/Night_protocol_whitepaper_1.1.pdf) | - |
| [Fluidkey](https://www.fluidkey.com/) | Stealth address generation system x payments | [Github](https://github.com/fluidkey/) | beta, Apr 24 | Ethereum | public | [Docs](https://docs.fluidkey.com) | - |
| [Sienna Network](https://sienna.network) | Sienna is a privacy-first and cross-chain decentralized finance platform where you can privately swap, lend and convert your tokens into their private equivalent  | ([GitHub](https://github.com/SiennaNetwork)) | Q2 2023 | Secret Network | anon | [Docs](https://docs.sienna.network/main/) | [Certik](https://sienna.network/static/documents/REP-Sienna_Wrapped-19_03_2021.pdf), [Certik](https://sienna.network/static/documents/REP-Sienna_Vesting-28_04_2021.pdf), [Halborn](https://sienna.network/static/documents/Rewards_V3_CosmWasm_Smart_Contract_Security_Audit_Report_Halborn.pdf), [Certik](https://sienna.network/static/documents/SiennaSwap---AMM-Report.pdf), [Halborn](https://sienna.network/static/documents/AMM_Protocol_CosmWasm_Smart_Contract_Security_Audit_Halborn.pdf), [Halborn](https://sienna.network/static/documents/Sienna_Network_Lending_Protocol_CosmWasm_Smart_Contract_Report_Halborn.pdf), [Halborn](https://sienna.network/static/documents/Sienna_Network_Lending_Protocol_Updated_Code_CosmWasm_Smart_Contract.pdf), [Halborn](https://sienna.network/static/documents/Launchpad-IDO.pdf), [Halborn](https://sienna.network/static/documents/Lending-and-Launchpad-Updated-Code.pdf), [Halborn](https://sienna.network/static/documents/Rewards-Bonding-Update.pdf) |
| [Offshift](https://www.offshift.io) | Offshift’s proprietary Shifting mechanism allows users to Shift between our native token, XFT, and a full palette of private synthetics | ([GitLab](https://open.offshift.io/offshiftXFT)) | live, march 2023 | Ethereum | ([anon](https://offshift.io/#team)) | - | - |
| [CAPE](https://www.espressosys.com/product) | Configurable Asset Privacy for Ethereum | ([GitHub](https://github.com/EspressoSystems/cape)) | testnet | Ethereum | anon | [Docs](https://docs.espressosys.com/sequencer/espresso-sequencer-architecture/readme) | - |
| [Webb](https://app.webb.tools/#/tornado) | an interoperable private bridge ✨️**ZK** | ([GitHub](https://github.com/webb-tools)) | beta | Tangle | anon | [Docs](https://docs.webb.tools/docs/) | [Audit of the DKG-Substrate pallet](https://blog.webb.tools/webbs-evm-bridge-security-audit-completed-by-veridise/) | 
| [Panther Protocol](https://www.pantherprotocol.io) | is a decentralized privacy metaprotocol enabling confidential, trusted transactions and interoperability with DeFi ✨️**ZK** | ([GitHub](https://github.com/pantherprotocol))  | testnet launch Q2 2023, mainnet launch Q3 2023 | Ethereum, Elrond, Polkadot, Avalanche, Near, Flare | ([Public](https://www.pantherprotocol.io/)) | [Docs](https://docs.pantherprotocol.io/docs/start-here/panther-protocol-documentation) | [ZKP Vesting](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Vesting.pdf), [ZKP Token](https://www.pantherprotocol.io/resources/REP-Panther-ZKP-Token.pdf) | 
| **sunset** [zk.money](https://zk.money) | The private DeFi yield aggregator for Ethereum.✨️**ZK** | ([Docs](https://docs.aztec.network/zk-money/userguide)) | live, july 2022 | Ethereum | anon | [Docs](https://docs.aztec.network) | - | 
| [RAILGUN](https://railgun.org) | Private transfers and DeFi infra for Ethereum, Polygon, Binance Smart Chain and Arbitrum.✨️**ZK** | - | live, Jul 2021 | Ethereum, BNB, Polygon | ([Public](https://railgun.org/#/contributors)) | [Docs](https://docs.railgun.org/developer-guide/cookbook/cookbook-overview) | [5 audits](https://assets.railgun.org/docs/audits/) | 
| [Umbra](https://app.umbra.cash) |  As a protocol, Umbra defines a simple set of standards, coupled with a singleton smart contract instance, to enable stealth addresses on Ethereum | ([GitHub](https://github.com/ScopeLift/umbra-protocol)) | mainnet, june 2021 | Ethereum | anon | - | [3 audits](https://app.umbra.cash/faq#security) |
| [Horizon](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | Decentralized Anonymous Payment Systems ✨️**ZK** | - | TBD | - | anon | [Docs](https://messier.gitbook.io/catalogue-de-messier/messier-applications/horizon) | [Messier](https://skynet.certik.com/projects/messier) |
| [Common](https://common.fi) | Common will be a decentralized exchange that mitigates the Maximal Extractable Value (MEV) problem. | - | coming in 2023 | Near, Ethereum, Solana, Kusama, Azero | anon | - | - |
| [Sacred](https://sacred.finance) |  multi-chain DeFi Platform offers private Yield Bearing Deposits to DeFi users ✨️**ZK* | ([GitHub](https://github.com/Sacred-Finance)) | TBD | Ethereum, Polygon | anon | - | - |
| **sunset* [Sahara](https://sahara.network) | The first dedicated privacy protocol ecosystem that enables on-platform trade between volatile and stable assets | - | coming in 2023 | Ethereum, BNB, Polygon, Solana, Avalanche | ([Public](https://sahara.network/)) | - | [Vesting contract](https://sahara.network/resources/sahara-security-audit.pdf) |
| [StealthPay](https://www.stealthpay.cash) | a stealth address protocol for Ethereum.| ([GitHub](https://github.com/cryptoadong)) | TBD | Ethereum | anon | - | - |
| [Hinkal](https://hinkal.pro) | an easy-to-integrate privacy SDK that helps users anonymize transactions.  | - | mainnet | Polygon | ([Public](https://hinkal.pro/#section-team)) | - | [Competitive security](https://github.com/Secure3Audit/Secure3Academy/blob/main/audit_reports/Hinkal/Hinkal_final_Secure3_Audit_Report.pdf) |
| [CIA protocol](https://ciaprotocol.com) | Building the truest form of DeFi with privacy by default. | - | TBD | Ethereum | anon | - | - |
| **sunset** [CoinBook](https://www.coinbook.app) | Decentralized Multi Chain P2P Order Book | - | - | multichain | anon | - | - |
| [zkUSD](https://zkusd.money/#Features) | Privacy-Preserving Collateralized Lending & more | ([GitHub](https://github.com/zkUSDLabs)) | - | - | - | [Docs](]https://zkusd.gitbook.io/zkusd-documentation) | - |
| [Spiral Finance](https://www.spiralfi.io) | non-custodial privacy solution based on ZK-Sync ERA ✨️**ZK** | - | - | - | - | ([Docs](https://docs.spiralfi.io/introduction/spiral-finance)) | - |
| [Kalium Network](https://kalium.network/app/public-wallet) | Seamlessly integrated with Ethereum, BSC, Polygon, and NEAR for enhanced privacy via ZK cryptography | - | - | - | - | - | - |
| [Swapr](https://swapr.eth.limo) | a DeFi protocol that offers dark pool trading with an integrated compliance solution which has the potential to revolutionize the financial industry | - | - | - | - | ([GitHub](https://github.com/SwaprHQ)) | - |
| [Unimix](https://unimix.cash) | The world's most secure privacy transaction service | - | live | multichain | anon | - | - |
| [illumineX](https://illuminex.xyz/swap) | Confidential multichain DEX gateway | ([GitHub](https://github.com/illumineXswap)) | - | - | - | ([Docs](https://docs.illuminex.xyz/illuminex-docs/)) | - |
| [Blend Protocol](https://www.blendprotocol.io) | cutting-edge privacy application allowing anonymous swaps from over 50 different chains | - | - | - | - | - | - |
| [Horus Protocol](https://horus.cash) | The ZKP crypto payment layer on Ethereum, BASE, Arbitrum, OP, Polygon and zkSync. | - | - | - | - | ([Docs](https://horuscash.notion.site/horuscash/Horus-Cash-Docs-332db90e9de444c49f2ff2d4bbe342ec)) | - |
| [Lucrisma](https://lucrisma.com) | digital asset dashboard | - | - | - | - | - | - |
| [Hydranet](https://hydranet.ai) | Layer3 orderbook + DEX | - | - | - | - | ([Docs](https://docs.hydranet.ai)) | - |
| [ZOOK](https://www.zook.fi) | DeFi ecosystem | ([GitHub](https://github.com/zookfi/)) | - | - | - | ([Docs](https://docs.zook.fi/zook-defi-ecosystem/)) | - |
| [GRVT](https://grvt.io) | The next-gen hybrid derivatives exchange. | - | - | - | - | ([Docs](https://grvt.gitbook.io/grvt/introduction/about-grvt)) | - |
| [Enclave Markets](https://www.enclave.market) | Fully Encrypted Exchange  | - | - | - | - | ([Docs](https://enclave-markets.notion.site/Enclave-Markets-API-Documentation-93b53ce24d3a4531ba09519c708483a9)) | - |
| [RenegadeFi](https://www.renegade.fi) | Dark Pool  | ([GitHub](https://github.com/renegade-fi)) | - | - | - | ([Docs](https://docs.renegade.fi)) | - |

## Currency
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Currency.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [BOB Protocol](https://zkbob.com/) | a multi-chain, multi-collateral stable token enhanced with optional privacy features  | ([GitHub](https://github.com/zkBob)) | live, beta | Polygon, Optimism, BNB, Ethereum | anon |

## Infrastructure
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Infrastructure.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Token |
| ------------- | ------------- |------------- |------------- | ----------- |
| [Manta Network](https://www.manta.network) | On-Chain Privacy for Web 3, DeFi and more ✨️**ZK* | [GitHub](https://github.com/manta-network) | testnet v3, january 2023 | MANTA |
| [NYM](https://nymtech.net) | Mixnet used to enhance validator privacy | [GitHub](https://github.com/nymtech) | mainnet, february 2022 | NYM |
| [NuCypher](https://www.nucypher.com) | Cryptographic Infrastructure for Privacy-Preserving Applications | [GitHub](https://github.com/nucypher/) | mainnet, january 2023 | NU |
| [Espresso Systems](https://www.espressosys.com) | Bring low-fees and better privacy to your Web3 applications with Espresso Systems' high-throughput EVM-compatible blockchain | [GitHub](https://github.com/EspressoSystems/) | testnet, June 2022 | No |
| [HOPR](https://hoprnet.org/protocol) | a fully incentivized and decentralized privacy mixnet that enables private point-to-point data exchange | [GitHub](https://github.com/hoprnet) | testnet, 2021 | HOPR |
| [Mystiko.Network](https://mystiko.network) | The Universal Web3 Zero-Knowledge Connectivity And Privacy Base Layer ✨️**ZK** | [GitHub](https://github.com/mystikonetwork) | testnet | no |
| [Raze Network](https://www.raze.network) | a EVM-compatible Privacy Layer on Multichains | [GitHub](https://github.com/Raze-Net) | mainnet, november 2021 | RAZE |
| [Verida](https://www.verida.io) | A multi-chain protocol for interoperable database storage and messaging built on decentralized identity | [GitHub](https://github.com/verida/) | live | no |
| [Keep](https://keep.network/info) | The privacy-focused infrastructure behind tBTCv2, the only truly decentralized solution for Bitcoin on Ethereum | [GitHub](https://github.com/keep-network/) | live | KEEP |
| [Mysterium](https://www.mysterium.network) | An open-source ecosystem of tools and infrastructure to liberate the web  | [GitHub](https://github.com/MysteriumNetwork) | Decentralized VPN (2017), testnet (2018), mainnet (2021) | MYST|
| [Lit](https://litprotocol.com) | Decentralized Cryptography for Access Control, Compute, and Encryption | [Docs](https://developer.litprotocol.com) | TBD | LIT |
| [Orbis](https://orbis.club) | We make it easy to add social features to your application | [GitHub](https://github.com/OrbisWeb3/) | TBD | OBT |
| [MACI](https://privacy-scaling-explorations.github.io/maci/) | Minimum Anti-Collusion Infrastructure (MACI) is a base layer for bribery-resistant, secure, and private digital voting. | [GitHub](https://github.com/privacy-scaling-explorations/maci) | TBD | no |
| [Threshold](https://threshold.network/build/taco) | A decentralized threshold cryptography network with programmable access control | [GitHub](https://github.com/nucypher) | live | T |
| [Comit Network](https://comit.network/) | COMIT is an open protocol facilitating trustless cross-blockchain applications, connecting all blockchains without adding yet another. Working on [BTC-XMR atomic swaps](https://github.com/comit-network/xmr-btc-swap) as well as various libraries and clients. | [Github](https://github.com/comit-network) | TBD | no |
| [Asterizm](https://asterizm.io) | Plug and play blockchain interoperability solution for enterprises, web3 protocols and fintech with privacy at the core | ([GitHub](https://github.com/Asterizm-Protocol)) | - | - | - | - |
| [Mind Network](https://mindnetwork.xyz ) | decentralized zero trust data lake | ([GitHub](https://github.com/mind-network)) | - | - | - |
| [Nomos](http://nomos.tech) | Nomos is a novel blockchain project that will address a network state's fundamental need for adaptable privacy and sovereignty. | ([GitHub](https://github.com/logos-co)) | - | - | - |
| [Swisstronik](https://swisstronik.com) | Layer 1 solution designed to build scalable dApps that ensure users' data protection and privacy, while remaining compliant | ([GitHub](https://github.com/SigmaGmbH)) | - | - | - |
| [Meson.Network](https://www.meson.network) | a suite of critical Web3 network infrastructure as well as the world’s first decentralized Bandwidth Exchange | ([GitHub](https://github.com/daqnext)) | - | - | - |
| [Ampere Chain](https://amperechain.com) | Experience the next generation of D-QBFT. Pioneering EVM, privacy nodes, & unmatched efficiency.  | ([GitHub](https://github.com/AmpereChain)) | - | - | - |
| [inDEX](https://index.phala.network) | Cross-Chain Intent Infrastructure  | ([GitHub](https://github.com/Phala-Network/index-contract)) | - | - | - |
| [Insider Protocol](https://insiderprotocol.com/) | Cross-Chain Intent Infrastructure  | - | - | - | - |
| [PADO](https://padolabs.org/)|Decentralized zkAttestation and Computation Network Powered by Interactive ZKP and zkFHE|([Github](https://github.com/pado-labs))| - | - | - |

## Wallet
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Wallet.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [Lunar aka Brume Wallet](https://devfolio.co/projects/lunar-wallet-34c4) | the first privacy native Ethereum wallet based on a built-in integration of TOR | ([GitHub](https://github.com/hazae41/ethbrno-wallet)) or ([GitHub](https://github.com/brume-wallet)) | PoC | Ethereum | ([Public](https://twitter.com/BrumeWallet)) |
| [Email Wallet](https://www.emailwallet.org) | Use your email address as a crypto wallet, via [zk email](https://prove.email) to keep the protocol decentralized and emails private on-chain. | ([Github](https://github.com/zkemail/email-wallet)) | - | - | - |
| [Myna Wallet](https://github.com/mynawallet) | Use your Japanese My Number card as a crypto wallet, via verifying the full passport validity inside ZK and using it to sign a transaction. | ([Github](https://github.com/mynawallet)) | - | - | - |
| [Edge](https://edge.app) | The most secure way to buy, store & trade crypto under your control | ([GitHub](https://github.com/EdgeApp)) | ([live](https://edge.app/)) | multichain | ([Public](https://edge.app/about/?af=github-com-web3privacy-web3privacy)) |
| [Zecrey Wallet](https://www.zecrey.com/) | Zecrey Chrome extension is a portal to the new & open Internet. Zecrey is an all-in-one wallet that not only provides a multi-chain layer-1 wallet but also a private cross-chain layer-2 wallet | ([GitHub](https://github.com/Zecrey-Labs)) | live, 2022 | multichain | anon |
| [Railway](https://railway.xyz) | DeFi privacy wallet | - | live | Ethereum, BNB, Polygon | anon |
| [Brave Wallet](https://brave.com/wallet/) | The secure multi-chain crypto wallet | ([GitHub](https://github.com/brave/brave-wallet-docs)) | live | multichain | ([Public](https://brave.com/about/)) |
| [BlockWallet](https://blockwallet.io) | The first crypto wallet protecting you on Web3 without any compromises | ([GitHub](https://github.com/block-wallet)) | ([live](https://chrome.google.com/webstore/detail/blockwallet/bopcbmipnjdcdfflfgjdgdjejmgpoaab)) | Ethereum | ([Public](https://www.linkedin.com/search/results/people/?currentCompany=%5B%2275124744%22%5D&origin=COMPANY_PAGE_CANNED_SEARCH&sid=LXn)) |
| [Frame](https://frame.sh) | A privacy focused Ethereum wallet that runs natively on macOS, Windows and Linux | ([GitHub](https://github.com/floating/frame)) | live | Ethereum | anon |
| [Sons of Crypto](https://sonsofcrypto.com) | web3 wallet by degens for degens | ([GitHub](https://github.com/sonsofcrypto)) | under development | multichain | anon |
| [ZenGo](https://zengo.com) | The only self-custodial wallet with no seed phrase vulnerability (shielded transactions) | ([GitHub](https://github.com/ZenGo-X)) | live | multichain | ([Public](https://zengo.com/team/)) |
| [Zeal](https://www.zeal.app) | The web3 wallet that defends your crypto and privacy | - | launching beta, Q2 2023 | multichain | anon |
| [Sphereon](https://github.com/Sphereon-Opensource/ssi-mobile-wallet) | The Sphereon Wallet enables you to store your own private data and gives you full and sole control over whom you want to share your information with | ([GitHub](https://github.com/Sphereon-Opensource/ssi-mobile-wallet)) | PoC | - | anon |
| [Zoker](https://zoker.tech) | The foremost ZK-based Wallet in Web3 | ([Docs](https://zoker.tech/wp.pdf)) | live | multichain | anon |
| [Beam](https://beam.eco/) | self-custodial wallet | - | - | - | - | - |
| [Elite](https://elitewallet.sc) | Android and IOS Wallet that respects your privacy | - | - | - | - | - |
| [Anon/Nero](https://t.me/anoneroapks) | private wallet | - | - | - | - | - |
| [Imperiume](https://www.imperiume.io/wallet) | non-custodial wallet | - | - | - | - |
| [Cool Wallet](www.coolwallet.io) | non-custodial wallet | - | - | - | - |
| [Phoenix](https://phoenix.acinq.co) | Non-custodial wallet on Lightning network | - | - | - | - |
| [Coingrig](https://www.coingrig.com) | Non-custodial wallet on Lightning network | ([GitHub](https://github.com/coingrig)) | - | - | - |
| [Pulse Wallet](https://www.coingrig.com) | Non-custodial wallet on Lightning network | ([GitHub](https://github.com/coingrig)) | - | - | - |
| [UltraNote Infinity](https://ultranote.org/#wallet) | Based on CryptoNote V.2 technology with secure transactions and decentralized blockchain. | - | - | - | - |
| [Ninji Wallet](https://ninji.xyz/) | agile crypto wallet | ([Docs](https://docs.ninji.xyz)) | - | - | - |

## Computing network
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Computing%20network.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [Findora](https://findora.org) | a decentralized, privacy-preserving smart contract platform. | ([GitHub](https://github.com/findoranetwork)) | mainnet | multichain | ([Public](https://findora.org/team/)) |
| [ARPA](https://www.arpanetwork.io/en-US) | Threshold BLS network can serve as the infrastructure of verifiable random number generator (RNG), secure wallet, cross-chain bridge, decentralized custody etc. | ([GitHub](https://github.com/ARPA-Network)) | mainnet, Q2 2023 | multichain | anon |
| [Phoenix](https://phoenix.global) | blockchain infrastructure empowering intelligence web3 applications. | ([GitHub](https://github.com/phoenixglobal)) | testnet | multichain | anon |
| [Privasea](https://www.privasea.tech) | Using secure Multi-Party sharing we protect data ownership and privacy, and facilitate secure sharing between different parties so data still can be processed. | - | - | multipurpose | ([Public](https://www.privasea.tech/about)) |
| [Alaya](https://alaya.network/en) | Alaya is a business sandbox and testing field for the next-generation of financial infrastructure of PlatON. | ([GitHub](https://github.com/AlayaNetwork)) | live, 2022 | Ethereum | anon |
| [Nillion](https://www.nillion.com) | The Secure Processing Layer of Web3. | ([Docs](https://docsend.com/view/7bkgvzagr6ifhwrc)) | live | multichain | ([Public](https://www.linkedin.com/search/results/people/?currentCompany=%5B%2280922042%22%5D&origin=COMPANY_PAGE_CANNED_SEARCH&sid=*cU)) |
| [Marlin](www.marlin.org) | Serverless backends for Web3: Access and process data verifiably using ZKPs and TEEs | ([GitHub](https://github.com/marlinprotocol)) | live | - | - |
| [Ethernity Cloud](https://ethernity.cloud) | The Web3 decentralized confidential computing ecosystem | ([Docs](https://docs.ethernity.cloud)) | live | - | - |

## Layer 2
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Layer%202.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [Aztec](https://aztec.network) | privacy-first Layer 2 on Ethereum ✨️**ZK** |([GitHub](https://github.com/AztecProtocol)) | - | Ethereum | ([Public](https://aztec.network/team/)) | 
| [Polygon Nightfall](https://polygon.technology/solutions/polygon-nightfall) | A Privacy-Focused Rollup for Enterprises ✨️**ZK** |([GitHub](https://github.com/maticnetwork/nightfall-sdk/ )) | mainnet, July 2022 | Polygon | ([Public](https://polygon.technology/about)) | 
| [Zecrey](https://www.zecrey.com) | zkRollup basedLayer 2 protocol featuring privacy and scalability |([GitHub](https://github.com/Zecrey-Labs)) | mainnet, Q2 2023 | multichain | anon |
| [Obscuro](https://obscu.ro) | Obscuro is a layer 2 solution for Ethereum that brings privacy and scale. It ensures the inputs, contract state and execution are always encrypted. No changes to dApps, just migrate and gain privacy | ([Docs](https://docs.obscu.ro)) | testnet | Ethereum | ([Public](https://obscu.ro/#team)) | 
| [ZKCHAOS](https://www.zkchaos.com) | ZKCHAOS is a layer2-based anonymous transaction protocol, and a fair game platform, which is built to enhance privacy for all kinds of cryptocurrency. | - | TBD | TBD | TBD |
| [StarkEX](https://starkware.co/starkex/) | A Layer-2 scalability engine, live on Ethereum Mainnet ✨️**ZK** | ([GitHub](https://github.com/starkware-libs/starkex-resources)) | live | Ethereum | ([Public](https://starkware.co/about-us/)) |
| [Tusima](https://tusima.network) | Privacy Financial Infrastructure For Blockchain | ([Docs](https://tusima.gitbook.io/tusima_en/tusima-introduction/what-is-tusima)) | - | - | - | - |
| [OLA](https://sin7y.org) | ZK-ZKVM Bringing Programmable Privacy to Blockchains | ([GitHub](https://github.com/Sin7Y) | - | - | - |
| [Polybase](https://polybase.xyz) | a public L2 blockchain with private transactions and MEV-resistance powered by zero-knowledge proofs (plus bridging USDC from Ethereum) | ([Docs](https://polybase.xyz/docs/introduction) | - | - | - |
| [TrueZK](https://www.truezk.com) | Post-Quantum ZK Rollup as a service x private DIDs | ([Docs](https://docs.truezk.com)) | - | - | - |
| [EtherChat](https://etherchat.app) |  First Layer-2 For Decentralized Chat | ([GitHub](https://github.com/EtherChatApp)) | - | - | - |
| [Kinto](https://kinto.xyz) | L2 focused on providing safe access to financial services.  | ([GitHub](https://docs.kinto.xyz/kinto-the-safe-l2/general/welcome-to-kinto)) | - | - | - |
| [Coti](https://coti.io) | Privacy-Focused Ethereum Layer-2  | ([GitHub](https://github.com/coti-io)) | - | - | - |

## Hardware
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Hardware.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [DappNode](https://dappnode.io/) | Easy to use hardware and software solution for running Ethereum and other kind of nodes, staking, IPFS, etc. | [(GitHub](https://github.com/dappnode)) | live | multichain | ([Public](https://dappnode.com/pages/about))
| [Avado](https://www.mysterium.network/avado) | A plug-and-play hardware device that connects users to many different kinds of blockchains. Their node-running software makes it easy and efficient for users to help power multiple networks at once, and earn crypto in the process | ([GitHub](https://github.com/mysteriumnetwork/AVADO-DNP-Mysterium-Server)) | live | multichain | ([Public](https://www.mysterium.network/team)) |
| [Privacy Infrastructure Solutions](https://www.chain-reaction.io) | Cloud and data center acceleration solution for Privacy Enhancing Technologies. | ([Docs](https://www.chain-reaction.io/resource-hub/)) | live | multichain | ([Public](https://www.chain-reaction.io/about/)) |
| [RawBox](https://github.com/Raw-Box/graypaper) | privacy-focused FOSS self-sovereign router | - | - | Nym | public |

## DID
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/IDENTITY.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Token | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- | ------------- |
| [KILT](https://www.kilt.io) | A blockchain identity protocol for issuing self-sovereign, verifiable credentials and decentralized identifiers | ([GitHub](https://github.com/KILTprotocol)) | live | multichain | ([yes](https://coinmarketcap.com/it/currencies/kiltprotocol/)) | ([Public](https://www.kilt.io/team)) |
| [MBuddy](https://metamirror.space/) | Web 3.0+ identity infrastructure | ([Docs](https://docs.metamirror.space/mbuddy/introduction/overview)) | under development | multichain | (yes) | anon |
| [Web3ID](https://www.dock.io/web3id) | Privacy-preserving user verification for Web3 | ([GitHub](https://github.com/docknetwork)) | live | multichain | ([yes](https://coinmarketcap.com/it/currencies/dock/)) | ([Public](https://www.dock.io/verifiable-credentials-company)) |
| [Anonybit](https://www.anonybit.io) | Anonybit’s revolutionary, patented solution offers a decentralized framework that strengthens compliance, protects identity, and secures personal assets (focus on biometrics) | - | PoC | multichain | no | ([Public](https://www.anonybit.io/team/)) |
| [Polygon ID](https://polygon.technology/polygon-id/) | Polygon ID is a blockchain-native identity system with programmable privacy that empowers people and enables the creation of trusted interactions with web3 services ✨️**ZK** | ([GitHub](https://github.com/0xPolygonID)) | live | Polygon | no | ([Public](https://github.com/orgs/0xPolygonID/people)) |
| [Dmail Network](https://dmail.ai) | Construct DID in Web3.0, Not Just an Email. | ([GitHub](https://github.com/dmailofficial/dmail)) | live | multichain | no | anon |
| [Litentry](https://litentry.com) | A decentralized identity aggregator, providing the structure and tools to empower you and your identity | ([GitHub](https://github.com/litentry)) | beta | multichain | ([yes](https://coinmarketcap.com/currencies/litentry/)) | ([Public](https://www.linkedin.com/search/results/people/?currentCompany=%5B%2240805422%22%5D&origin=COMPANY_PAGE_CANNED_SEARCH&sid=2W3)) |
| [VerusID](https://verus.io/verusid) | VerusID is for self-sovereign individuals, and conscious organizations that value their data | ([GitHub](https://github.com/VerusCoin)) | live | multichain | ([yes](https://coinmarketcap.com/it/currencies/veruscoin/)) | ([Public](https://verus.io/people)) |
| [Findora CR](https://findora.org/findora-cr/) | Enabling ZK Identity Management & CRedentials for Web3 | ([GitHub](https://github.com/findoranetwork)) | live | multichain | ([yes](https://coinmarketcap.com/it/currencies/findora/)) | ([Public](https://findora.org/team/)) |
| [Iden3](https://iden3.io) | The open-source protocol at the basis of Polygon ID. The protocol defines on a low-level how the parties listed above communicate and interact with each. Polygon ID is an abstraction layer to enable developers to build applications leveraging the Iden3 protocol | ([GitHub](https://github.com/iden3)) | live | Ethereum | no | anon |
| [Holonym](https://www.holonym.id) | Your ZK Passport for Web3. A holistic identity that lets you prove facts about yourself without revealing who you are ✨️**ZK** | ([GitHub](https://github.com/holonym-foundation)) | - | - | - | - |
| [ZK Email](https://www.prove.email) | Open-source protocol to prove any subset of any partially redacted email in zk on chain, via verifying email signatures within zk proofs. Used for [email-based wallet recovery](https://prove.email/recovery), decentralized on/off ramps, and decentralized identity verification. | ([GitHub](https://github.com/zkemail)) | - | - | - | - |
| [Cursive](https://www.cursive.team) | By combining NFC cards that generate zk-friendly signatures with ZK, FHE, PSI, and folding schemes, uses advanced cryptography to privately interact with people across communities. | ([GitHub](https://github.com/cursive-team)) | - | - | - | - |
| [zCloak](https://zcloak.network) | Privacy-first DID and verifiable computation infrastructure ✨️**ZK** | ([GitHub](https://github.com/zCloak-Network)) | - | - | - | - |
| [BrightID](https://www.brightid.org) | A social identity network that allows you to prove that you’re only using one account. It’s the holy grail of digital identity | ([GitHub](https://github.com/BrightID)) | - | - | - | - |
| **sunset** [Sismo](https://www.sismo.io/) | Sismo is a modular protocol issuing ZK Badges for reputation portability and aggregation | ([GitHub](https://github.com/sismo-core)) | - | - | - | - |
| **sunset** [Notebook labs](https://www.notebooklabs.xyz) | Zero-Knowledge Cryptography for anonymous KYC and soul-bound credentials. ✨️**ZK** | ([Docs](https://notebook-6.gitbook.io/notebook-docs/guides/for-authentication)) | - | - | - |
| [ONT ID](https://ont.id) | Bringing trustless identity to Web3 manage your data with ONT ID | ([GitHub](https://github.com/ont-id/)) | - | - | - | - |
| [Interep](https://interep.link) | Anti-sybil as a service | ([GitHub](https://github.com/interep-project)) | - | - | - | - |
| [Universal Reputation](https://developer.unirep.io) | a private and non-repudiable reputation system | ([GitHub](https://github.com/unirep)) | - | - | - | - |
| [Cerebrum](https://www.cerebrum.com) | Ensure everyone in your organization is credentialed and compliant with Cerebrum's verifiable data technology and vID ecosystem | ([GitHub](https://github.com/cerebruminc)) | - | - | - | - |
| [Spruce](https://spruceid.com) | the open-source stack to leave control of identity and data where it should be: with users. | ([GitHub](https://github.com/spruceid)) | - | - | - | - |
| [Hypersign](https://hypersign.id) | the ultimate stack for identity management  | ([GitHub](https://github.com/hypersign-protocol)) | - | - | - | - |
| [Fractal ID](https://web.fractal.id) | We help web3 platforms and ecosystems ensure data and regulatory compliance by enabling selective disclosure of verified user data to KYC/AML status | ([GitHub](https://github.com/trustfractal)) | - | - | - | - |
| [Next.ID](https://next.id) | An open-sourced protocol that synergises your Web2 and Web3 profiles. | ([GitHub](https://github.com/nextdotid)) | - | - | - | - |
| [Slashags](https://slashtags.to) | Slashtags gives developers tools to build secure and scalable peer-to-peer applications that put users in control of their profiles, contacts, accounts, and data. | ([GitHub](https://github.com/synonymdev/slashtags)) | - | - | - | - |
| [AesirX WEB3 ID](https://web3id.aesirx.io) | an advanced identity management solution that protects users’ personal data and ensures privacy on the internet. | ([GitHub](https://github.com/aesirxio)) | - | - | - | - |
| [Quadrata](https://quadrata.com) | Establish Trust and Identification via Sybil resistant DIDs and KYC/AML natively on-chain | - | - | - | - | - |
| [SEER sdid](https://sdid.seer.eco/) | Building your own community identity like a brand | - | - | - | - |
| [Valid.id](https://valid3.id) | Build the root of trust for your entity in a way that is both cryptographic and legally binding. | - | - | - | - | - |
| [zkPass](https://zkpass.org/home) | Protocol for Private Data based on MPC, ZKP, 3P-TLS | ([GitHub](https://github.com/zkPassOfficial) | - | - | - | - |
| [Anagolay](https://anagolay.network) | Web3 Framework for Original Creators to claim and verify ownership of online identities and multimedia content and license creative works P2P | ([GitHub](https://github.com/anagolay) | - | - | - |
| [DAuth Network](https://www.dauth.network) | a decentralized authentication network empowering wallets and dApps to create authentication with a focus on privacy | ([GitHub](https://github.com/DAuth-Network)) | - | - | - |
| [Icebreaker](https://www.icebreaker.xyz) | zero knowledge  x self-sovereign identity | - | - | - | - |
| [zkMe](https://zk.me) | Identity Oracles that leverage the power of zero-knowledge-proofs to enable secure, self-sovereign and private credential verifications. | ([GitHub](https://github.com/zkMeLabs)) | - | - | - |
| [WIW](https://wiw.io) | Build, Aggregate, Own Your Decentralized Identity & Reputation | ([GitHub](https://github.com/wiw-io)) | - | - | - |
| [Anon Aadhaar](https://anon-aadhaar-documentation.vercel.app) | Anon Aadhaar circuit lets citizens with an Aadhaar card generate zero-knowledge identity proof. | ([GitHub](https://github.com/privacy-scaling-explorations/anon-aadhaar)) | - | - | - |
| [Anrk Verify](https://www.ankr.com/blog/ankr-verify-product-launched-to-provide-blockchains-with-readymade-user-id-solution/?page=1) | Provide Blockchains With Readymade User ID Solution | ([GitHub](https://github.com/Ankr-network/)) | - | - | - |
| [Neonyx](https://neonyx.io) | DID + Flexible social platform | ([GitHub](https://github.com/neonyxhub)) | - | - | - |
| [Fame](https://getfame.ai) | transform into an AI-powered influencer | ([GitHub](https://fame.gitbook.io/fame-ai/)) | - | - | - |
| [CARV](https://carv.io) | credential infra focused on gaming, enabling players with achievement display, semantic social, and access to gaming premiums. | ([Docs](https://docs.carv.io/overview/carv-intro)) | - | - | - |

## DAO
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/%20DAO.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [AnyDAO](https://www.anydao.app) | Vote aggregation across different blockchain networks with adjustable privacy settings which controls the visibility of the voting |  [Docs](https://docs.ata.network/anydao/introduction/) | - | - | - | 
| [HeyAnon](https://www.heyanoun.xyz) | Allows noun-holders to give feedback on proposals while maintaining their privacy using zero-knowledge proofs ✨️**ZK** | - | - | - | - | 
| [LunarDAO](https://lunardao.net) | DAO fostering R&D and investments within Lunarpunk movement |  [GitHub](https://github.com/lunardao/dao) | - | - | - |   

## Bridge
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Bridge.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [Aztec Connect*sunset*](https://aztec.network/connect/) | The Aztec Connect SDK allows any Ethereum protocol to be integrated in Aztec’s private rollup with a simple Solidity interface and front-end SDK | ([GitHub](https://github.com/critesjosh/aztec-sdk-starter)) | - | - | - |
| [ChainPort Private Bridge](https://www.chainport.io/private-bridge) | Full control and security for your token – manage supported chains, path, amounts, and own the keys | ([GitHub](https://docs.chainport.io)) | - | - | - |
| [Blockbend](https://blockblend.io) | Anonymous cross-chain transactions, farming, prepaid crypto card, escrow service. | - | - | - | - |
| [ZkPay](https://zkpay.finance) | Private Aztec withdrawal Bridge. | - | - | - | - |
| [Carrier](https://www.carrier.so) | A powerful token and NFT bridge for Web3 natives | ([Docs](https://docs.carrier.so/introduction/about)) | - | - | - |
| [Polyhedra Network](https://polyhedra.network) | Infrastructure for Web3 Interoperability | - | - | - | - | - |
| [BlockBlend](https://blockblend.io) | anonymous cross-chain decentralized services. Stake, farm, blend and send | [GitHub](https://docs.blockblend.io/utilities/bridge) | - | - | - | - |

## Messaging
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Messaging.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [Waku](https://waku.org) | Waku is the communication layer for Web3. Decentralized communication that scales | ([GitHub](https://github.com/waku-org)) | - | - | - |
| [Status](https://status.im) | Status is a secure messaging app, crypto wallet, and Web3 browser built with state of the art technology | ([GitHub](https://github.com/status-im/)) | - | - | - |
| [Sending.me](https://sending.me) | open-source communication & social platform. | - | - | - | - |
| [RLN Anonymous Chat](https://github.com/njofce/zk-chat) | A spam resistant instant messaging application for private and anonymous communication. | - | - | - | - |
| [Mejhool](https://hzmcoin.com/mejhool/) | a Decentralized web and mobile app with peer-to-peer text messaging, decentralized file transfer and voice-over-IP service.| - | - | - | - |
| [DeChat](https://www.dechat.io) | an open, secure web3 communications protocol that powers decentralized user interactions | ([GitBook](https://dechat.gitbook.io/dechat/)) | - | - | - |
| [4thPillar Project](https://the4thpillar.io) | Community-build dMail & dChat | ([GitHub](https://github.com/4P-project/)) | - | - | - |

## Browser
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Browser.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [Status Web3 Browser](https://status.im/web-three-browser/) | Access the latest defi dapps, exchanges, marketplaces, games and more with the Web3 Browser. | - | - | - | - |

## KYC
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/KYC.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [Proof of Passport](https://github.com/zk-passport/proof-of-passport) | Use ZK proofs to verify any information inside any passport with an NFC signature, such as proving you are over 18 or you are a USA citizen. | [GitHub](https://github.com/zk-passport/proof-of-passport)  | - | - | - |
| [Hashbon Pass](https://pass.hashbon.com) | Tokenized All Web3 Pass to KYC while being anonymous. | - | - | - | - |
| [Holonym](https://holonym.id) | ZK-identity protocol for anonymous KYC, sybil resistance, and compliance. ZK | [GitHub](https://github.com/holonym-foundation)) | - | - | - |

## RPC
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/RPC.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [1RPC](https://www.1rpc.io) | The Web3 Private RPC Relay ([Docs](https://docs.ata.network/1rpc/introduction/)) + ([GitHub](https://github.com/orgs/automata-network/repositories)) | - | - | - |
| [Secure RPC](https://securerpc.com) | SecureRpc is a bare-metal, fully conformant JSON-RPC/gRPC Infrastructure plane that aims to perform well. | - | - | - | - |
| [DERP](https://derp.hoprnet.org/) | DERP is an RPC endpoint you can add to your wallet to visualize data leaked by your wallet in communication with the blockchain ([GitHub](https://github.com/hoprnet/derp)) | - | - | - |
| [RPCh](https://rpch.net/) | RPCh is a privacy-preserving RPC service for wallets that detaches the user’s identity from all communication with the blockchain ([GitHub](https://github.com/Rpc-h/RPCh)) | - | - | - |
| [Ethereum Portal Network](https://www.ethportal.net/) | Decentralized P2P overlay network on top of Ethereum devp2p for serving RPC requests.  | - | - | - | - |
| [Spook](https://github.com/EdenBlockVC/spook) | Mixing service using the Nym network to anonymize Ethereum RPC calls.  | - | - | - | - |
| [Zoci](https://zoci.io) | private RPC services | ([GitHub](https://github.com/zoci-io)) | - | - | - | - |
| [VeilRPC](https://veilrpc.com) | High-performing private RPC node | ([Docs](https://docs.veil.exchange/veil-rpc/explanation-and-features)) | - | - | - | - |
| [Helios](https://github.com/a16z/helios) | Light client | ([GitHub](https://github.com/a16z/helios)) | - | - | - | - |

## Storage
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [Swarm](https://www.ethswarm.org) | a decentralised data storage and distribution technology. Ready to power the next generation of censorship-resistant, unstoppable, serverless dapps | ([GitHub](https://github.com/ethersphere/swarm-cli)) | - | - | - |
| [Fileverse](https://fileverse.io) | On-chain people and communities deserve on-chain tools for private communication and collaboration. | ([GitHub](https://github.com/fileverse)) | - | - | - |

## dApps
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/DAPPS.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [Mask](https://mask.io) | Mask Network brings privacy and benefits from Web3 to social media like Facebook & Twitter - with an open-sourced browser extension | ([GitHub](https://github.com/DimensionDev/Maskbook)) | - | - | - |
| [ZkMaps](https://gitcoin.co/grants/5781/zkmaps-proof-of-location) | Protecting users location with ZK proofs | ([GitHub](https://github.com/zkMaps)) | - | - | - |
| [Plugin.io](https://plugin.io/) | Privacy focussed, ad free social media & digital marketplace.  | - | - | - | - |
| [Krebit](https://krebit.id) | open identity verification protocol for Web3 Verifiable Credentials | ([GitHub](https://github.com/KrebitDAO)) | - | - | - |
| [FYEO Identity](https://www.gofyeo.com/fyeo-identity) | Decentralized password management. Real-time identity monitoring. | - | - | - | - |
| [LiquidFactory](https://liquidfactory.io) | unlocks liquidity to DeFi, GameFi & NFTs. | - | - | - | - |
| [CheqD](https://cheqd.io) | a secure network that enables individuals and organisations to fully control their personal data. It allows self-sovereign identity (SSI) companies to build and deliver secure solutions to you | ([GitHub](https://github.com/cheqd)) | - | - | - |
| [SPKZ](https://spkz.io) | the first fully decentralized web3 community/chat platform. | - | - | - | - |
| [TLSNotary](https://tlsnotary.org) | Proof of data authenticity | ([GitHub](https://github.com/tlsnotary/tlsn)) | - | - | - |
| [Damus](https://damus.io) | Nostr client for the social network you control. | - | - | - | - |
| [Weavemail](https://docs.arweave.org/info/tools/weavemail) | the mail that cannot be lost, censored, or read by Google: Weavemail is mail that you own. | - | - | - | - |
| [Stealthdrop](https://stealthdrop.xyz) | Anonymous Airdrops using ZK-SNARKS ✨️**ZK** | ([GitHub](https://github.com/stealthdrop/stealthdrop))  | - | - | - |
| [Bringing Privacy to ENS](https://www.cerebrum.com) | ChainSafe’s Proposed Integration Using Aztec Network | ([GitHub](https://github.com/ChainSafe/ens-aztec-privacy/))  | - | - | - |
| [Silent Data](https://silentdata.com) | Verify web2 Data in web3 Applications. | - | - | - | - |
| [okSign](https://www.oksign.app) | Create, Sign and Save eSignatures with smart contracts and permissioned NFTs. | - | - | - | - |
| [Literully](https://literully.com) | a decentralized voting platform that allows users to create and participate in voting on any topic, all without giving up their privacy or control over their data | ([Docs](https://docs.literully.com/articles/))   | - | - | - |
| [Bermuda](https://www.bmda.io) | next-gen private utility dApp for sending legal, anonymous transactions of multiple ERC-20 tokens. | - | - | - | - |
| [Privacy Pools](https://www.privacypools.com) | allow you to generate a brand new Ethereum address that is completely unlinkable to any prior transaction history. But our privacy-preserving technology does much more than that. | ([GitHub](https://github.com/ameensol/privacy-pools)) | - | - | - |
| [Sociogram](https://sociogram.org) | Web3Social Media focused on privacy. | - | - | - | - |
| [Blockyfile](https://blockyfile.org) | The new way to upload files anonymously and without censorship. | - | - | - | - |
| [AsMatch](https://www.asmatch.app) | the only Web3 matching app that uses ZKPs to authenticate users’ on-chain credentials | - | - | - | - | - |
| [Juno Analytics](https://juno.build/blog/introducing-juno-analytics-unlock-deeper-insights-with-privacy-in-mind) | simple, performant, and open-source web3 analytics solution designed with privacy in mind for the developers building decentralized dapps | ([Docs](https://juno.build/docs/build/analytics#getting-started)) | - | - | - |
| [Buildoor](https://buildoor.xyz) | Privacy Focused Analytics | - | - | - | - |
| [Nocturne](https://nocturnelabs.xyz) | a protocol enabling usable on-chain privacy | ([GitBook](https://nocturne-xyz.gitbook.io/nocturne/introduction/one-pager) | - | - | - |
| [Sirius Sync](https://siriussync.io ) | Web3 Social Ecosystem | - | - | - | - |
| [FreeChat](https://twitter.com/Freeture_Chat) | Web3 Social | - | - | - | - |
| [POMP](https://mantapacific.pomp.money) | comprehensive DeFi platform for token swaps, lending, NFT trading, collateralization | - | - | - | - |
| [Onvote](https://onvote.app) | Anonymous, gasless & modular voting for web3 | - | - | - | - |
| [Rehide](https://app.rehide.io) | Private, zero-knowledge password manager and vault | ([Docs](https://docs.rehide.io/)) | - | - | - |
| [ZkLocus](https://zklocus.dev) | Private Geolocation Off & On-Chain | ([GitHub](https://github.com/iluxonchik/zkLocus/)) | - | - | - |
| [ETH.LIMO](https://eth.limo/#how-limo-works) | a privacy-preserving ENS gateway, enabling users to access Ethereum-native dApps and content | ([GitHub](https://github.com/ethlimo)) | - | - | - |

## NFT
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/NFT.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [NFT Fair](https://www.nftfair.app) | The do-good NFT launch platform | - | - | - | - |
| [Email Wallet](https://www.emailwallet.org) | Send NFTs on-chain to or from any email address using [zk email](https://prove.email) to keep the protocol decentralized. | ([Github](https://github.com/zkemail/email-wallet)) | - | - | - |
| [The Anon Club](https://theanonclub.com) | worlds first privacy focused digital collectibles | - | - | - | - |
| [Polyhedra ZK-NFT Container](https://polyhedra.network/zknft-container) | a new NFT protocol that can contain other NFTs, realizing maximum interoperability | - | - | - | - | - |
| [sudoswap](https://sudoswap.xyz/#/) | private bids | ([GitHub](https://github.com/sudoswap) | - | - | - | - |

## R&D
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/R&D.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [P0X labs](https://p0xeidon.xyz) | the decentralized laboratory for building cutting-edge privacy technologies. | - | - | - | - |
| [=nil; Foundation](https://nil.foundation) | Foundation intends to create a tightly integrated set of technologies becoming a basis for secure data storages operating in insecure environments. | - | - | - | - |
| [Privacy & Security Explorations](https://appliedzkp.org) | We explore new use cases for zero-knowledge proofs and other cryptographic primitives through research and proof-of-concepts. | - | - | - | - |
| [Personae Labs](https://personaelabs.org) | R&D lab investigating the future of human expression online ([GitHub](https://github.com/personaelabs)) | - | - | - |
| [Hypermine](https://hypermine.co) | smart tools and protocols for Identity, Privacy & Security, with our roots in Distributed Systems, Machine Learning & Cryptography. | - | - | - | - |
| [Entropy1729](https://www.entropy1729.com) | Zero Knowledge Shop | - | - | - | - |
| [Trivium](https://trivium.network) | provides validator services to serveral networks, and develops privacy-preserving dApps ([GitHub](https://github.com/TriviumNode)) | - | - | - |
| [RealRan](https://www.realran.com/home) | RealRan comes from the global engineering and cryptography research team,  expertise in cryptography protocol and distribution consensus engineering ([GitHub](https://github.com/realran)) | - | - | - |
| [HashCloak](https://hashcloak.com) | an independent research lab focused on helping organizations and blockchain communities integrate a privacy-first approach into their processes. ([GitHub](https://github.com/hashcloak)) | - | - | - |
| [OSOMPrivacy](https://www.osomprivacy.com) | From software to hardware OSOM Privacy gives you the tools that you need to make sure your data, your information is always private and protected. | - | - | - | - |
| [Pollen Labs](https://pollenlabs.org) | We are a passionate and dedicated team of individuals working within the Privacy and Scaling Explorations division of the Ethereum Foundation. | - | - | - | - |

## Node
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/NODE.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [NiceNode](https://nicenode.xyz) | Launcher with a simple user experience to run an Ethereum node on your computer. | - | - | - | - |
| [Stereum](https://stereum.net/ethereum-node-setup/) | Graphical tool for installing Ethereum clients on a remote server via SSH connection with a simple setup guide, phone app for remote monitoring, control center and other features. | - | - | - | - |

## Mixing services
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Mixing%20services.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [TC](https://en.wikipedia.org/wiki/Tornado_Cash) | TornadoCash is an open source, non-custodial, fully decentralized cryptocurrency tumbler that runs on Ethereum Virtual Machine-compatible networks. | - | - | - | - |
| [Cyclone](https://cyclone.xyz) | Cyclone is a protocol that applies zkSNARKs to enable transactional privacy by breaking the on-chain link between depositor and recipient addresses ([Docs](https://github.com/cycloneprotocol/cyclone-contracts))   | - | - | - |
| [CoinMix](https://www.coinmix.tech) | the first mixer of the market with its own liquidity | - | - | - | - |
| [Mix to Earn](https://www.mixtoearn.app) | Compliant Mixing Solution | - | - | - | - |

## Other
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Other.png?raw=true)
| Project  | Description | GitHub | Product-readiness | Ecosystem | Team |
| ------------- | ------------- |------------- |------------- | ------------- | ------------- |
| [ZKP2P](https://www.zkp2p.xyz) | Via zk proofs of payment confirmation emails, use [zk-email](https://prove.email) to on and off ramp directly from Venmo, UPI, and Garanti to crypto, without trusting an intermediary. | ([GitHub](https://github.com/zkp2p/zk-p2p/)) | - | - | - |
| [Privy](https://www.privy.io) | Privy's simple, powerful APIs help you manage user data off-chain | ([GitHub](https://github.com/privy-io)) | - | - | - |
| [Conveyor](https://conveyor.ata.network/#/swap) | Automata Conveyor is an anti-front-running service that ingests and outputs transactions in a determined order (MEV Minimization solution)  | ([GitHub](https://github.com/automata-network/conveyor-sdk)) | - | - | - |
| [CryptWerk](https://cryptwerk.com/) | Cryptwerk is online directory with companies, websites, shops, services where you can pay with Bitcoin and other popular cryptocurrencies. | - | - | - | - |
| [Incognito](https://incognito.org) | The privacy marketplace for crypto assets. | ([GitHub](https://github.com/incognitochain)) | - | - | - |
| [ex-Nucleo, now-Puzzle](https://puzzle.online) | Private, auditable shared multisig to shield & send assets | - | - | - | - |
| [Meson](https://mesonmix.net) | a mix network for cryptocurrency transactions. It breaks the link connecting your network-level information to your cryptocurrency transactions. | ([GitHub](https://github.com/hashcloak/Meson)) | - | - | - |
| [Lava](https://lavanet.xyz) | Lava pairs Providers with Applications for scalable, private and uncensored access to Web3. | - | - | - | - |
| [rotki](https://rotki.com) | rotki is an open source portfolio tracker, accounting and analytics tool that protects your privacy. | ([GitHub](https://github.com/rotki)) | - | - | - |
| [Semaphore Protocol](http://semaphore.appliedzkp.org) | Using zero knowledge, Semaphore allows Ethereum users to prove their membership of a group and send signals such as votes or endorsements without revealing their original identity ✨️**ZK** | ([GitHub](https://github.com/semaphore-protocol/semaphore)) | - | - | - |
| [Zkitter](https://www.zkitter.com/) | ZK social protocol, anonymous social network | - | - | - | - |
| [Minds](https://www.minds.com) | Minds is an open source social network dedicated to Internet freedom. Speak freely, protect your privacy, earn crypto rewards and take back control of your social media. | - | - | - | - |
| [S𝛑PETs](https://ethresear.ch/t/s-pets-sustainable-practically-indistinguishable-privacy-enhanced-transactions/14565) | Universal covert privacy-enhanced transactions for ANY public blockchain that supports ECDSA or Schnorr based on two-party computation (2PC) combined with adaptor signatures and verifiable timed commitments (VTC). | ([GitHub](https://github.com/timoth-y/spy-pets))   | - | - | - |
| [Media Network](https://www.media.network) | a privacy-first and community-governed CDN. | ([GitHub](https://github.com/mediafoundation)) | - | - | - |
| [Datum](https://datumtechs.com) | Web3 Privacy-preserving Data Service. | ([GitHub](https://github.com/datumtechs)) | - | - | - |
| [ZK-Groups](https://github.com/privacy-scaling-explorations/zk-groups) | a comprehensive infrastructure to allow anyone to create and manage their own groups privately ([GitHub](https://github.com/privacy-scaling-explorations/zk-groups)) | - | - | - |
| [Crypt-Keeper](https://github.com/CryptKeeperZK/crypt-keeper-extension) | a browser extension which enables Zero knowledge identity management and proof generation  ([GitHub](https://github.com/CryptKeeperZK/crypt-keeper-extension)) | - | - | - |
| [3num](https://www.3num.co) | the first anonymous Web3 mobile number that protects your identity and provides private, secure messaging. | ([GitHub](https://github.com/3numdao)) | - | - | - |
| [ZKTsunami](https://www.zktsunami.io) | ZK-AnonSNARK powered transactional anonymity at your fingertips  | - | - | - | - |
| [Self](https://www.joinself.com) | Web3 fraud prevention for everyone. | ([GitHub](https://github.com/joinself)) | - | - | - |
| [Web3Shield](https://www.web3shield.com) | a platform providing insurance, security and privacy focused products for all things Web3. | - | - | - | - |
| [Foundation Cash](https://foundationtoken.io) | a revolutionary crypto mixer token that serves as a utility to reduce fees when using the mixer. | - | - | - | - |
| [CryptoChill](https://cryptochill.com) | a highly customizable cryptocurrency payment gateway and custodial wallets provider focused on security, privacy and scalability. | - | - | - | - |
| [ZK-DEX](https://zk-dex.io) | we set your personal information private, you govern your own asset. | - | - | - | - |
| [Mailchain](https://mailchain.com) | Send and receive messages directly between wallets. | ([Docs](https://docs.mailchain.com/developer/)) | - | - | - |
| [Humanode](https://humanode.io) | Humanode conducts private biometric verification of its validators to ensure that there is only one unique living human being behind each node. | ([Docs](https://gitbook.humanode.io/oauth2-service)) | - | - | - |
| [Namachain](https://namachain.com) | A Universal Key & ID manager, fully decentralized and with zero-knowledge offline authentication.  | - | - | - | - |
| [flashbots-privacy](https://github.com/hashcloak/flashbots-privacy) | Practical Experiments on how to add complete privacy to flashbots. ([GitHub](https://github.com/hashcloak/flashbots-privacy)) | - | - | - |
| [Aztec Network](https://aztec.network/index.html) | Aztec is a first-of-its-kind hybrid zkRollup supporting both public and private smart contract execution.  [Github](https://github.com/AztecProtocol) | - | - | - |
| [TOME](https://tome.fm) | anonymous, uncensorable broadcast service that allows anyone to publish any string onto Ethereum | ([GitHub](https://github.com/firnprotocol/tome)) | - | - | - |
| [Sarcophagus](https://sarcophagus.io) | Decentralized, blockchain-enabled, cryptographically secure, general-purpose Digital Dead Man's Switch | [GitHub](https://github.com/sarcophagus-org) | - | - | - |
| [Hype](https://hype-eth.com) | the first Telegram-based bot that can be used to mix your ETH, clean your wallets and bridge anonymously| - | - | - | - |
| [Lightstreams](https://lightstreams.network) | provides secure data sharing for web3 applications. | ([GitHub](https://github.com/lightstreams-network/)) | - | - | - |
| [Spectrum Marketplace](https://spectrummarket.io) | a marketplace where everyone has the opportunity to contribute, transact, and interact without compromising on privacy or security. | ([Docs](https://spectrum-market.gitbook.io/spectrum-whitepaper/about-us/the-vision)) | - | - | - |
| [Data Ownership Protocol](https://dop.org) | selective transparency on Ethereum | - | - | - | - |
| [xBlock](https://www.xblock.tech) | compliant solution for private transactions in Web3. Privately send, swap, bridge and receive payments with xBlock’s trusted API | ([Docs](https://xblock.gitbook.io/product-docs)) | - | - | - |
| [Clique](https://www.clique.social) | Clique securely connects Web2 and Web3 user data with Identity and Attestation Oracles -- built with ZKP, TEE, and MP | ([GitHub](https://github.com/CliqueOfficial)) | - | - | - |
| [GenomesDAO](https://genomes.io) |  money and anonymously power scientific and medical research | - | - | - | - |
| [0xbow](https://www.0xbow.io) |  the first ASP (association set provider) for Privacy Pools | - | - | - | - |

## Events
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Events.png?raw=true)
- [ETH Brno](https://ethbrno.cz) - an annual independent & open community hackathon for supporters of decentralised finance, smart contracts and Web3 happening in Brno, Czech Republic **13 projects**: ([Devfolio](https://ethbrno.devfolio.co/projects?show_winners=false))

| Winner  | Description |
| ------------- | ------------- |
| [Lunar aka Brume Wallet](https://devfolio.co/projects/lunar-wallet-34c4)  | the first privacy native Ethereum wallet based on a built-in integration of TOR ([GitHub](https://github.com/hazae41/ethbrno-wallet)) or ([GitHub](https://github.com/brume-wallet))  |

- [ETH Berlin](https://ethberlin.ooo/contributors/) - a hackathon, a cultural festival, an educational event, a platform for hacktivism, and a community initiative to push the decentralized ecosystem forward. **100 projects**: ([Devfolio](https://ethberlin.devfolio.co/projects?show_winners=false))

- [ETHDam](https://www.ethdam.com/hackathon) - Ethereum-focused privacy & DeFi hackathon. [Projects](https://taikai.network/cryptocanal/hackathons/ethdam)

| Winner  | Description |
| ------------- | ------------- |
| [zikiLeaks](https://zikileaks.vercel.app)  | Privacy-preserving posting, non-invasive content verification, & anonymous donations empower whistleblowers to fight for human rights globally. ([GitHub](https://github.com/mattiapomelli/zikileaks)) |

- [ETH #Privacy](https://www.leadingprivacy.com/istanbul) - ETH #Privacy is the hackathon around privacy, organized by the Leading Privacy Alliance of web3.

- [ETH Rome](http://ethrome.org) - privacy-centric hackathon. **20+ projects**: ([Devfolio](https://taikai.network/ethrome/hackathons/ethrome-23/projects))

## Network state
![alt text](https://github.com/Msiusko/web3privacy/blob/main/static-assets/Network%20state.png?raw=true)
- [Logos](https://logos.co) - a grassroots movement to provide trust-minimized, corruption resistant governing services and social institutions to underserved citizens ([GitHub](https://github.com/acid-info))

## Papers
- [Blockchain Privacy and Regulatory Compliance: Towards a Practical Equilibrium](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4563364)
- [EIP-7503: Zero-Knowledge Wormholes](https://eips.ethereum.org/EIPS/eip-7503)
- [Derecho: Privacy Pools with Proof-Carrying Disclosures](https://eprint.iacr.org/2023/273)
- [Lightweight Authentication of Web Data via Garble-Then-Prove](https://eprint.iacr.org/2023/964)

## Privacy & Scaling Explorations
this part will be restructured later on by categories

| Project  | GitHub | 
| ------------- | ------------- |
| [Anon Aadhaar](https://pse.dev/en/projects/anon-aadhaar) - Tools for building build privacy-preserving applications using government ID cards, specifically Aadhaar cards in India |[Github](https://github.com/privacy-scaling-explorations/anon-aadhaar) |
| [AnonKlub](https://pse.dev/en/projects/anon-klub) - A mechanism for anonymous proof of Ethereum address ownership. | [Github](https://github.com/anonklub) |
| [Bandada](https://pse.dev/en/projects/bandada) - An open-source system for managing privacy-preserving groups of anonymous individuals | [Github](https://github.com/privacy-scaling-explorations/bandada) |
| [Channel 4](https://pse.dev/en/projects/channel-4) - Content discovery through community contributions, using state channels to reward users for popular posts. | [Github](https://github.com/State-Channel-4) |
| [COCO](https://pse.dev/en/projects/coco) - Integrating Nova into the EVM involves wrapping Liam Eagen's theoretical ECIP argument in Halo 2 | [Mirror](https://mirror.xyz/privacy-scaling-explorations.eth/tEf7iYa8l7ECZwN2T57yyiws7h9Uchip30CQvx-JBBQ) |
| [CryptKeeper](https://pse.dev/en/projects/cryptkeeper) - A browser extension for secure, portable anonymous identity management across applications. | [Github](https://github.com/CryptKeeperZK) |
| [Discreetly](https://pse.dev/en/projects/discreetly) - An anonymous, federated, chat application using ZK. | [Github](https://github.com/Discreetly) |
| [EigenTrust](https://pse.dev/en/projects/eigen-trust) - A distributed reputation system with zero-knowledge features. | [Github](https://github.com/eigen-trust/protocol) |
| [Interep](https://pse.dev/en/projects/interep) - An identity bridge from web2 to web3 | [Github](https://github.com/interep-project) |
| [jubmoji.quest](https://pse.dev/en/projects/jubmoji) - Users of Jubmoji.quest tap NFC cards to collect signatures. By collecting these signatures, they complete quests. | [Github](https://github.com/jubmoji/jubmoji.quest) |
| [MACI](https://pse.dev/en/projects/maci) - An on-chain voting solution that protects privacy and minimizes the risk of collusion and bribery | [Github](https://github.com/privacy-scaling-explorations/maci) |
| [Rate-Limiting Nullifier](https://pse.dev/en/projects/rln) - A protocol for deterring spam and maintaining anonymity in communication systems. | [Github](https://github.com/Rate-Limiting-Nullifier/circom-rln) |
| [Semaphore](https://pse.dev/en/projects/semaphore) - A zero-knowledge protocol enabling anonymous group membership proof and signaling. | [Github](https://github.com/semaphore-protocol) |
| [Summa](https://pse.dev/en/projects/summa) - Protocol enabling centralized exchanges to prove solvency without compromising private information. | [Github](https://github.com/summa-dev) |
| [TLSNotary](https://pse.dev/en/projects/tlsn) - A protocol for creating cryptographic proofs of authenticity for any data on the web. | [Github](https://github.com/tlsnotary/tlsn) |
| [UniRep Protocol](https://pse.dev/en/projects/unirep-protocol) - A Zero-Knowledge Protocol built to handle anonymous user data. | [Github](https://github.com/Unirep) |
| [Zkitter](https://pse.dev/en/projects/zkitter) - A decentralized social network prioritizing privacy and anonymity | [Github](https://github.com/zkitter) |
| [ZKOPRU](https://pse.dev/en/projects/zkopru) - Optimistic Rollup with zk-SNARKs for private Ethereum transactions. | [Github](https://github.com/zkopru-network) |

# Ethereum-as-a-Currency (ETH)

