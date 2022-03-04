## 🧑‍💻 Basic information

Project Name: Stackton

Slogan: "Makes the Assist"

License: GPLv3

Team Name: AktaryTech   

Payment Address: 0x06A2f84bAb3872E04d9495bE8C43F9E2281411a1

## 🎯 Project Overview

Stackton is a lending and borrowing platform focused on safely "stacking" apex assets. An apex asset is one that the user believes, with some conviction, will increase in value. Users learn to develop an investment thesis, and to responsibly use collateralized leverage towards their conviction.

This will be accomplished by the user inputting the range of what they believe the minimum and maximum prices will be on an asset for a given timeframe. With a sliding calculator, users will make a thesis like “ETH will go to $4000 in 1 year, potentially hitting $1500 on drawbacks.” The user will also be asked to present a percentage conviction of this thesis, like “I believe this statement with 75% certainty.”

These numbers will automatically adjust a suggested Loan-To-Value (LTV) ratio that would be considered in-line with their conviction. This LTV is what they will manage, and can adjust these risk parameters by reviewing their calculations each time they're in the app.

Another key focus of Stackton will be stablecoins. Users will learn how to manage LTV on drawbacks; depositing stablecoins, or advanced strategies like providing liquidity pools with stable coins and their apex asset. We want to give the user all the education and tools they need to become experts at DeFi and in avoiding liquidations.

Stackton intends to be the application to symbolize learning in DeFi. We believe that users will put trust in a protocol that has taught them how to set up and manage an investment thesis with collateralization. Ultimately, this trust from building a smart DeFi community will allow Stackton to expand into a complete DeFi ecosystem.

---

**Frontend**

The inspiration for this project will be the smooth user experience of the Anchor Protocol on the Terra blockchain. DeFi education and loan health calculators will be new UI elements that we will be building out. This will be a significant innovation over the majority of lending and borrowing applications.

Most AAVE-like applications have a basket of assets to borrow and lend. Stackton will only have apex assets to deposit, that earn rewards, while allowing you to borrow stablecoins with accruing interest. On a separate page, you will also deposit stablecoins to earn interest.

Pages:

- Stack — Deposit apex assets (KCS, ETH, ...), borrow stablecoins.
- Earn — Deposit stablecoins.
- Stake — Stake the governance token.
- Dashboard — See all your metrics.

**DeFi Education / Calculators**

KCS has historically been a good investment. Let’s say you believe KCS (currently $20) is going to $100 one year from now. Along that time, you think the overall market could affect the price of KCS enough that it could drop to $10. You put this thesis into our calculator: time-frame=1 year, high=$100, low=$10, conviction=75%. Instead of “safe”, “medium”, and “high-risk” borrowing amounts, you slide the conviction scale to determine your belief in this thesis. The calculator is stateless, so whenever you enter Stackton you have to re-adjust your thesis. Which is good because you may have changed it based on new knowledge or current events.

To start, you deposit KCS, and borrow USDC. The calculator takes your low and adjusts it by remainder of your conviction percentage; in this case $10 + 25% = $12.5. This becomes your “safe” liquidation price. The calculator gives you a suggested amount to borrow. You go to KuSwap and swap that USDC for more KCS and deposit that back into Stackton. Your LTV reflects your conviction.

The amount of stablecoins a user has in the "Earn" can also allow the suggested LTV to go higher, since there is an immediate method of preventing liquidations by withdrawing the deposited stablecoin and paying down the borrowed amount.

**Smart Contracts**

A fork of AAVE protocol v2 will be the mechanism behind lending and borrowing. Initially the apex assets for depositing may be just KCS and ETH. Stablecoins (USDC or USDT) for borrowing and depositing will be whatever has better liquidity with those apex assets.

**Stacktonomics**

To incentivize lenders, we will have an `$ASST` token. Just like with AAVE, locking this token to boost the safety module will be rewarded.

The source of revenue is the difference in interest charged on borrowing stablecoins to the apex asset deposit rewards. Liquidation fees will also be revenue.

Token Allocation: we will settle on an effective mechanism to distribute `$ASST` with airdrops to other KCC users, staking rewards, liquidity management, strategic sale, founding team, DAO partnerships and ecosystem treasury.

Staking `$ASST` will secure the protocol, provide inflationary rewards, and give governance rights.

**Documentation**

GitBook based documentation with added DeFi education materials. Innovation here will focus on bringing new users, or less financially literate users, into the sphere of DeFi responsibly.

**Governance**

Ultimately, governance will happen through token-weighted voting on Stackton Improvement Protocols. A foundation managed by a DAO will be the organizer of continued improvements.

**Target Market**

The initial target would be KuCoin CEX users who are getting started in KCC, and want a simple tool with some DeFi basics and education. Another target would be current users of KCC protocols, who we could target with an airdrop of $ASST or NFTs.

## 👥 Team

**Shane Neeley — Community Manager —** 10 years experience in machine learning for healthcare and scientific software. Author of two books on AI. Built and launched an NFT community; coded backend for token reservations. Skilled in technical writing, marketing, natural language processing, Python, Node.js.

[linkedin.com/in/neeley1](https://linkedin.com/in/neeley1) || [github.com/shane-neeley](https://github.com/shane-neeley)

**Adam Kecskes — Projects Orchestrator —** 25 years tech veteran with a background in project management, customer advocacy, operations improvement, frontend architecture (C/C++, JS/React, more), M&A software due diligence, technical writing. Degrees in Math and CS. Scrum master; public speaker; options trader.

[linkedin.com/in/adamkecskes](https://linkedin.com/in/adamkecskes) || [github.com/adamk72](https://github.com/adamk72)

**Dan Hepworth — Blockchain and Smart Contracts Engineer —** Duke C.S., background in finance and EdTech. Featured in Bloomberg about Web3 jobs. Member of the social DAO, Friends With Benefits. Skilled in Solidity, Hardhat, IPFS, Brownie, Ethers.js, Chai testing, CI/CD, Node.js and Typescript.

[linkedin.com/in/danhep](https://linkedin.com/in/danhep) || [github.com/djh58](https://github.com/djh58)

**Geoffrey Ballard — Senior Engineer —** Design savvy senior software engineer with experience building and delivering complex, scalable, and robust applications for web, mobile, and desktop. Skilled in Node.js, React, Next.js, TypeScript, AWS, Google Cloud, and GitHub CI/CD.

[linkedin.com/in/gaballard](https://linkedin.com/in/gaballard)  || [github.com/gaballard](https://github.com/gaballard)

**Molly McConnell — Frontend Developer —** Strong engineering professional with a design bent. C.S. degree, and Node.js certified from The Linux Foundation. Makes beautiful, functional dApps in React, Web3.js, Next.js, HTML and CSS.

[linkedin.com/in/molly-mcconnell-226309129](https://linkedin.com/in/molly-mcconnell-226309129) || [github.com/mmcconnell10](https://github.com/mmcconnell10)

**Luke — Backend Engineer —** Computer Science degree with experience in data analytics companies. DevOps and deployment with AWS and Google Cloud. Skilled in Python, Node.js, and smart contract programming with Solidity and Hardhat.

**Jared Childers — Blockchain Engineer —** A Gitcoin KERNEL Fellow and a Gitcoin + Filecoin APOLLO Fellow. Skilled in Solidity, Hardhat, IPFS, Web3.py, Ethers.js, Chai testing and GitHub CI/CD.

[linkedin.com/in/jared-childers-343b68195](https://linkedin.com/in/jared-childers-343b68195)  || [github.com/JaredChilders](https://github.com/JaredChilders)

**Paul Giordano — Asset Manager —** Chief Investment Officer of Keccak Capital. Thirty-nine years of experience in finance and trading.

[linkedin.com/in/paul-giordano-25b8618a](https://linkedin.com/in/paul-giordano-25b8618a)

**David Aktary — CEO —** Founder of AktaryTech and three other companies. Founded ERC dEX, one of the first Ethereum token trading platforms in 2017. Currently leading Keccak Capital, delivering crypto exposure through quantitative, model-driven portfolio construction.

[https://www.linkedin.com/in/aktary](https://www.linkedin.com/in/aktary/)

---

Contact: `sneeley@aktarytech.com`

Legal Structure: Aktary Enterprises LLC., 701 Brazos St #500, Austin, Texas 78701, USA

ENS: aktary.eth

---

**Team's experience:**

AktaryTech is a professional Web3 and dApp development agency. We’ve built a talented team, put in-place the best software practices, and committed ourselves to quality and code safety. We’ve helped clients launch automated trading bots, DeFi yield aggregation, lending protocols, developer education tools, on-chain games, and NFT marketplaces. Our skills in the entire Web3 stack are growing with every new project. Below are some highlights of our service delivery, with their names obfuscated on this public document.

**Client 1**

We built a beautiful dApp for a cross-chain DeFi hub for lending, borrowing, rates, staking, and interoperability. We built the frontend in React and managed many backend smart contracts and integrations. Our contracts are currently running on a Cosmos-based chain as well as Ethereum Goerli and Kovan testnets.

**Client 2**

A unique automated cross-chain yield aggregator. We built the interconnecting architecture for their liquidity terminal. This architecture was a transport layer for interactions between chains. This comprised of Solidity smart contracts and relayers via Node.js, TypeScript and Redis.

**Hummingbot Connectors**

Hummingbot is an open source algorithmic trading bot for CEXs and DEXs. We built connectors for clients that link Hummingbot's internal trading algorithms with live information from different exchanges. They interact with an exchange's REST API and through real-time interactions via Websockets; such as by gathering order book data and sending and canceling trades. We built connectors for speed in Python, Cython and AsyncIO. The projects we’ve done so far:

- **Client 3**  — connector for a hybrid liquidity platform with an off-chain order book + on-chain AMM
- **Client 4**  —  a crypto market maker who needed an OSL Exchange connector.

**Client 5**

We built a smart contract education for a developer-incentivized blockchain. It’s a free interactive code school that teaches developers how to create their own Cosmwasm contracts and deploy dApps to the network. This app trains devs on the Rust programming language for decentralized applications. We gained experience with Rust, Cosmwasm, and this growing ecosystem of non-EVM products.

**Client 6**

We built the backend and frontend of an NFT marketplace that is focused on anime-themed NFTs. The app is a full marketplace, where artists can create and mint NFTs, and sell them on the primary and secondary markets. We used a layer 2 of Ethereum for the source for minting and the secondary market provider.

**Client 7**

An on-chain game, modeled after a roulette wheel where bets are placed in BNB tokens on the Binance Smart Chain. For game logic, we used Chainlink VRF (Verified Random Function), and Chainlink Keepers for trustless spinning of the wheel. We used the Graph Protocol for indexed user information and Tailwind CSS Framework for the UI theme. Since we have mathematics expertise, we also built the probabilities for the game through Monte Carlo simulations of winning and losing scenarios.

**Client 8**

We built and designed an Automated Market Maker (AMM) and an asset bridge between ETH and BNB.

---

Team Code Repos: [github.com/AktaryTech](https://github.com/AktaryTech)

Most work is done on our client's repositories. There are some examples on our personal profile above, as well as some team member's profiles.

## 🏆 Development Roadmap

Through years of service delivery, we've developed a teamwork process that allows all members to participate in new projects. Members of the above team will cycle in and out of Stackton work as needed. We're also actively hiring, and can bring in new team members specifically for this grant-funded work.

Overview: 18 weeks until the smart contract deployment on KCC mainnet along with a user interface. Overall 29 weeks for all phases of development and marketing. At our Blended Resource Hourly Rate of $200, the total cost is **$472,000**. Additional liquidity support, if part of your newly launched [accelerator program](https://kccofficial.medium.com/kcc-announces-50m-ecosystem-accelerator-program-43f65285f33b), would benefit this DeFi project.

---

|                                      |              |  |                        |                |            |
| --- | --- | --- | --- | --- | --- |
| **Milestone 1: Deliverables**            |              |  | **Milestone 1: Resources** |                |            |
| Deliverable                          | Time (Weeks) |  | Resource               | Quantity (FTE) | Cost (USD) |
| Project Initiation and Planning      | 1            |  | Engineers              | 3              | $24,000    |
| Design of System Architecture        | 2            |  | Product Managers       | 1              | $8,000     |
| Design of User Interface             | 1            |  | Design                 | 3              | $24,000    |
|                                      |              |  |                        |                |            |
| Time (Weeks)                         | 4            |  | Cost (USD)             |                | $56,000    |

|                                      |              |  |                        |                |            |
| --- | --- | --- | --- | --- | --- |
| **Milestone 2: Deliverables**            |              |  | **Milestone 2: Resources** |                |            |
| Deliverable                          | Time (Weeks) |  | Resource               | Quantity (FTE) | Cost (USD) |
| Smart Contracts                      | 2            |  | Engineering            | 4              | $32,000    |
| Deployed Smart Contracts to Testnet  | 1            |  | Product Management     | 2              | $16,000    |
| Deployed User Interface to Staging   | 1            |  | DevOps                 | 2              | $16,000    |
|                                      |              |  | Design                 | 1              | $8,000     |
| Time (Weeks)                         | 4            |  | Cost (USD)             |                | $72,000    |

|                                      |              |  |                        |                |            |
| --- | --- | --- | --- | --- | --- |
| **Milestone 3: Deliverables**            |              |  | **Milestone 3: Resources** |                |            |
| Deliverable                          | Time (Weeks) |  | Resource               | Quantity (FTE) | Cost (USD) |
| Documentation                        | 2            |  | Engineering            | 3              | $24,000    |
| Stress Testing                       | 1            |  | Product Managers       | 2              | $16,000    |
| Beta User Experience Feedback        | 1            |  | DevOps                 | 2              | $16,000    |
|                                      |              |  | Design                 | 2              | $16,000    |
| Time (Weeks)                         | 4            |  | Cost (USD)             |                | $72,000    |

|                                      |              |  |                        |                |            |
| --- | --- | --- | --- | --- | --- |
| **Milestone 4: Deliverables**            |              |  | **Milestone 4: Resources** |                |            |
| Deliverable                          | Time (Weeks) |  | Resource               | Quantity (FTE) | Cost (USD) |
| Security Analysis / Audit            | 1            |  | Security (Audit)       | 4              | $32,000    |
| Token Liquidity and Listing          | 1            |  | Product Management     | 2              | $16,000    |
|                                      |              |  | DevOps                 | 1              | $8,000     |
|                                      |              |  | Finance                | 1              | $8,000     |
| Time (Weeks)                         | 2            |  | Cost (USD)             |                | $64,000    |

|                                      |              |  |                        |                |            |
| --- | --- | --- | --- | --- | --- |
| **Milestone 5: Deliverables**            |              |  | **Milestone 5: Resources** |                |            |
| Deliverable                          | Time (Weeks) |  | Resource               | Quantity (FTE) | Cost (USD) |
| Smart Contract Mainnet Deployment    | 2            |  | Engineering            | 4              | $32,000    |
| User Interface Production Deployment | 2            |  | Product Management     | 2              | $16,000    |
|                                      |              |  | DevOps                 | 3              | $24,000    |
| Time (Weeks)                         | 4            |  | Cost (USD)             |                | $72,000    |

|                                      |              |  |                        |                |            |
| --- | --- | --- | --- | --- | --- |
| **Milestone 6: Deliverables**            |              |  | **Milestone 6: Resources** |                |            |
| Deliverable                          | Time (Weeks) |  | Resource               | Quantity (FTE) | Cost (USD) |
| Marketing Engagement                 | 1            |  | Community Management   | 2              | $16,000    |
| Discord, Telegram, Twitter           | 1            |  | Marketing              | 3              | $24,000    |
| Outreach and KCC Involvement         | 1            |  |                        |                |            |
|                                      |              |  |                        |                |            |
| Time (Weeks)                         | 3            |  | Cost (USD)             |                | $40,000    |

|                                      |              |  |                        |                |            |
| --- | --- | --- | --- | --- | --- |
| **Milestone 7: Deliverables**            |              |  | **Milestone 7: Resources** |                |            |
| Deliverable                          | Time (Weeks) |  | Resource               | Quantity (FTE) | Cost (USD) |
| Community Governance Forum           | 2            |  | Engineering            | 2              | $16,000    |
| DAO planning                         | 2            |  | Community Management   | 2              | $16,000    |
| UX Metrics & Analytics               | 1            |  | Marketing              | 2              | $16,000    |
|                                      |              |  |                        |                |            |
| Time (Weeks)                         | 5            |  | Cost (USD)             |                | $48,000    |

|                                      |              |  |                        |                |            |
| --- | --- | --- | --- | --- | --- |
| **Milestone 8: Deliverables**            |              |  | **Milestone 8: Resources** |                |            |
| Deliverable                          | Time (Weeks) |  | Resource               | Quantity (FTE) | Cost (USD) |
| NFT Design                           | 2            |  | Artists                | 2              | $16,000    |
| NFT Launch                           | 1            |  | Community Management   | 2              | $16,000    |
|                                      |              |  | Marketing              | 2              | $16,000    |
|                                      |              |  |                        |                |            |
| Time (Weeks)                         | 3            |  | Cost (USD)             |                | $48,000    |
|                                      |              |  |                        

|                                      |              |  |                        |                |            |
| --- | --- | --- | --- | --- | --- |
| All Deliverables Completed           |              |  | All Required Resources
| Total Time (Weeks)                   | 29           |  | Total Cost (USD)       |                | **$472,000**   |

---

## 📡 Future Plans

Stackton intends to become a fully decentralized platform, managed by on-chain governance. Stability and long-term viability of the project are of utmost importance. We want all stakeholders to benefit from economic incentives as well as DeFi education.

Members of our team also have experience in NFTs; in the artistic creation, launch, contracts and ongoing community engagement around a successful NFT project. Certainly this could drive traffic to the application, and even to the KCC ecosystem from other chains.

Though our service delivery team is being repurposed to build this, future plans are to build a decentralized organization for the foundation and continued development.

## 🙋 Additional Information ➕

Thank you for this opportunity. We believe that with our skills in development as well as deep financial expertise, Stackton will drive users to the KCC chain for many years to come.
