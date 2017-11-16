![logo_city.jpg](https://raw.githubusercontent.com/Stangrotic/photoREX/master/logo_city.jpg)

Rex White Paper<br><br>
**A Decentralized Multiple Listing Service & Real Estate Transaction Application**  

●	Rex: referring to the platform, Rex<br>
●	REX: referring to the token, REX

## Executive Summary<br>
Real property, defined as anything that is owned by a person or entity that has any interest in land, real estate, or the improvements on it; has existed since man first settled the ancient lands of Mesopotamia in 4500 BCE [3] [5]. Since the ancient settlements there have been two major pieces of a real estate transaction:

1. Data
2. Transactions 


Traditionally, obtaining reliable property information has been difficult. Today, with advances in technology, data has become easier to ascertain. However, the data has become controlled, manipulated, and governed by centralized organizations, resulting in exorbitant transaction and listing fees. With recent advances in peer-to-peer data distribution and blockchain technology, Rex will provide universal access to real estate information and streamline the transaction process. 

Rex will start by building a global multiple listing service, creating a data layer that is accessible to everyone. The database will minimize listing fees and maximize listing exposure. In our third phase, Rex will provide users the ability to create sale and lease “smart” contracts. Benefits include a savings on time, communication, and administrative costs. Finally, Rex will develop an architecture to create tokenized contracts with an exchange where property tokens can be traded. 

## Contents
 
**1.0 MLS<br>**
1.1 What is a Multiple Listing Service?<br>
1.2 Evolution of Multiple Listing Services<br>
1.3 Overview of Rex’s Listing Service<br>
1.4 Why Rex is starting with listings<br>
1.5 Specifics on how Rex will work<br>
1.6 Technology architecture<br>
1.7 Technology stack & future potential<br><br>
**2.0 Blockchain<br>**
2.1	 What is the Blockchain?<br>
2.2	 What is Ethereum?<br>
2.3 Why is Rex building on Ethereum?<br>
2.4 Data distribution<br> 
2.5 IPFS<br>
2.6 Benefits to REX<br>

**3.0 Problem & Solution**<br>
3.1 Problem<br> 
3.2 Solution<br>

**4.0 Rex’s Model**<br>
4.1 Model<br>
4.2 Phases<br>
4.3 Token Allocation<br>
4.4 Token Utility<br>
4.5 Listing Rewards<br>
4.6 Verification System<br>
4.7 Payment Delays<br>
4.8 Fees<br>
4.9 Subscription Model<br>
4.10 Tokensale<br><br>
**5.0 Conclusion**<br>

**6.0 Founder biographies**<br>
6.1 Stephen King<br>
6.2 Russell McLernon<br>

**7.0 Contact and References**<br>
7.1 Contact<br>
7.2 References<br>

**8.0 Appendices**<br>
8.1 Appendix A: Real Estate Transactions: Today<br>
8.2 Appendix B: Lease Transaction<br>
8.3 Appendix C: Tokenized Ownership<br>
 
## **1. MLS**<br>
#### 1.1 What is a Multiple Listing Service?
 
A multiple listing service (MLS, also “multiple listing system” or “multiple listings service”), is a suite of services that enables real estate brokers to establish contractual offers of compensation (from brokers), that facilitates cooperation with other broker participants, and that accumulates and distributes information to enable appraisals. An MLS also acts as a facility for the orderly correlation and dissemination of listing information to better serve brokers’ clients, landlords, tenants, and the public [4]. A multiple listing service’s database and software are used by real estate brokers and real estate owners to share information about properties with other brokers, owners, buyers, sellers and tenants.

#### 1.2 Evolution of Multiple Listing Services

*Listing Service 1.0 (Pre-Internet)*<br>
Pre-internet, the real estate industry relied on print for dependable real estate information. Print releases were bi-annual with dated property information. 
 
*Listing Service 2.0 (Post-Internet, Pre-Blockchain)*
 <br>Most countries have a handful of dominant online MLS' providers.

Typical fee structures:<br>
●	Approximately $299.95/month for up to 10 listings<br>
●	Approximately $399.95/month to list one “Platinum Property”<br>
●	Approximately $90.00 fee to view up to 3 comparable properties
 
We can approximate that the average subscriber is paying at least $30.00/listing per month or $360.00/listing per year:
 
	300/10 = 30
 
	30 * 12 = 360
 
Users subscribing to Platinum and Comparable Properties are paying approximately $520.00/listing per month or $6,240.00/listing per year:
 
	30+ 400 + 90 = 520.00
 
	520 * 12 = 6,240.00
 
Common complaints amongst users include a lack of price transparency, user experience, and dated information. The MLS' limit the amount of data a “non subscriber” can view. 
 
#### 1.3 Overview of Rex’s Listing Service

Rex provides a new type of multiple listing service where data is universal and interoperable with other systems. The raw database is decentralized and owned by the listees. Value to the user beyond ownership and control is a reward system that compensates users in REX tokens for participating in the network. For every verified listing (see “Verification System”) the user is paid in REX. Traditional MLS’ make money from collecting user data and charging a fee to publish it to the platform. The user creates the value (data) but the MLS is the beneficiary. On Rex, the user owns the data and are compensated for their contributions: The more listings a user publishes, the more rewards they earn. The more listings on Rex, the more eyeballs. The more eyeballs the more demand for the REX token. Value is driven from listees and they are the beneficiaries. In addition, users can sell and exchange data, such as market studies, inspection reports and advertising space. Finally, a listees exposure will go from local to global. Rex is one large homogenous database that is not bound by countries or borders. 

#### 1.4 Why we’re starting with listings

Rex envisions a 3-year time frame to deploy three tools:

1.	Year 1: MLS & Filtration
2.	Year 2: Transactions
3.	Year 3:Tokenized Ownership in the RexDex (US/Australia) 

Rex’s roadmap accounts for the maturity of the Ethereum ecosystem, expanding government participation and steady user adoption. First, blockchain technology is in its infancy. The basic infrastructure is still being built and tested. The real estate industry and regulation authorities are not ready to risk transactions until the infrastructure is proven. Thus, building an MLS is the most logical place to start for several reasons. First, data is where every real estate transaction begins. Second, if data is lost during the testing period it’s a recoverable event. Third, Ethereum comes with a learning curve. Features on Rex involve transactions, tokens and virtual wallets. The user will require these features to be intuitive and frictionless like the web they use today. For this reason, Rex has heavily invested in UX. As technology, regulation and user confidence expands, Rex will advance into transactional services.

#### 1.5 Specifics on how it will work

Rex’s database will be free and accessible to anyone with a computer and internet connection. In order to be eligible for the listing reward, the user is required to register with Rex. The registration process includes the submission of a user's name, contact details, firm (if applicable) and real estate license (if applicable). Once registered, the user can start submitting listings and be eligible for the reward. The listing will publish immediately with a 2-week time delay for the listing reward. During the 2-week time delay other users have the opportunity to flag the listing as spam. If the listing is flagged, both users will enter an arbitration period. The winner of the arbitration period will receive the listing reward. The user found gaming the listing rewards contract will lose their verification status and no longer be eligible for further rewards. REX tokens have various utilities like spam reduction, market sponsorships, professional profiles, and data exchanges that are elaborated on below (see “Token Utility”). 

#### 1.6 Technology Architecture 

Rex Technology Stack:<br>
●	NodeJS<br>
●	Mithril<br>
●	Solidity<br>
●	Web3.js<br>
●	IPFS<br>

Rex Contract Stack:<br>
**ListingRewards.sol**: This Contract keeps track of pending reward requests and their status<br>
**Metafeed.sol**: This Contract organizes the platforms main spam feed. Users are automatically subscribed to Rex’s metafeed but can unsubscribe anytime and/or subscribe to another user's feed.<br>
**Datafeed.sol**:  This Contract handles the individual datafeeds, i.e one of these contracts deployed for each country and market combination.<br>
**DatafeedCoordinator.sol**: This Contract handles the datafeed collection<br>
**Dex.sol**: This contract provides a decentralized exchange for trading REX with ETH<br>
**RexCoordinator.sol**: This Contract is used by other Rex contracts to determine the addresses of other contracts.<br>

#### 1.7 Technology stack & future potential 

Once the data layer is proven, Rex will expand into Phase 3: transactions. Rex will launch with simple lease contracts (Appendix B) for several reasons:

1.	Regulation: Less government oversight in leasing transactions
2.	Number of contract variables: Small leases typically establish 3-5 variables to execute per transaction: verify, time, money, access (sales many more)
3.	Counterparties: Lease contracts average 5 counterparties (sales many more):<br>
a.	Lessor<br>
b.	Lessee<br>
c.	Broker(s)<br>
d.	Attorney(s)<br>
e.	Bank(s)<br>

Rex will provide the software/GUI that will guide users through the smart contract creation process. Rex will also provide integration tools to third party banks and dApp developers.

Rex’s fourth phase is incorporating tokenized ownership (Appendix C) into the RexDex. Tokenized ownership is a new means of fractionalizing real estate ownership across many different holders. Digitizing ownership provides many benefits including liquidity, affordability and transferability.  

The RexDex will have several applications, one of which will be for trading digital property assets created through tokenized ownership. 

There are major legal hurdles with tokenized ownership, especially in the US and Australia (see “Model: Phase 3 and 4”). Thus, REX will breakdown tokenized ownership into two phases:

1.	Adding tokenized ownership to the RexDex: There are friendlier jurisdictions outside the US and Australia with dApps already being created to tokenize real estate assets. The RexDex will offer a place for these tokenized assets to be traded. 
2.	Tokenized Ownership: Rex’s strength is architecting and building the technology infrastructure for tokenized ownership. Rex will introduce tokenized ownership in one of two ways:
a.	Form a partnership with an established firm (Rex is currently speaking to two).
b.	License the technology with property assets being traded on the RexDex.

 
## 2.0 Blockchain
 
#### 2.1 What is the Blockchain?
 
The blockchain is a distributed database or public ledger that gained popularity following the release of Bitcoin. It maintains a continuously growing list of all the transactions in a particular network that have ever been executed. The “blocks” are added in chronological order with cryptography to prevent tampering, thus becoming an indelible record of every transaction in the network and accessible to every participant [1].
 
####  2.2 What is Ethereum?
 
The Ethereum system can be described as a single shared computer that is run by the network of users, on which resources are parceled out and paid for in Ether. In essence, it’s a world computer.
 
#### 2.3 Why is Rex building on Ethereum?
 
Data needs to be on a server. A server is generally owned or leased by a corporation. Therefore, the individual relinquishes control of their data.
 
This leads to increased costs with low accessibility and virtually no interoperability between systems.
 
We now have the means of decentralizing data. BitTorrent, Swarm, and IPFS can do that on their own, but the blockchain provides the ability to organize and order the data with no central authority. Ethereum provides a means to mesh together the blockchain, data distribution, and currency all under one roof. Ether acts as a convenient medium in which Ether can be exchanged for REX, and REX will fuel the application. This is the absolute value Rex sees for blockchain and Ethereum technology.
 
Rex is building on the Ethereum protocol for several reasons. The first is to provide a distributed database where anyone can access real estate information for free.
 
Distributed databases provide two advantages:
 
1. The user always owns and has access to their information. Third party advertisements, especially those of competing brokers, will never exist on a listees page unless they initiate private advertising.
2. Price Stability: No central authority owns the information thus placing capital controls on the data.
 
Ethereum also provides a means for tokenized currency. Rex is utilizing the tokenized aspect of Ethereum to reward contributors for providing content and offering a digital exchange where real estate data can be freely traded.
 
While Rex's database stores all active listings for 90 days, it is possible to build a comprehensive history of each individual parcel ever listed on the platform.
 
#### 2.4 Data Distribution
 
Since the 90’s, the HTTP protocol has been a useful tool to send and receive data packets from one or more central servers to the requesting node.
 
Today we distribute much larger packets of information. If too many requests are made servers become overwhelmed. The result is increased latency, downtime, and maintenance requirements. The costs are passed from owner to user. In 2017, the HTTP protocol is inefficient. We’re at an inflection point where nodes no longer need to communicate through centralized routes, but rather, can do so peer-to-peer.
 
#### 2.5 IPFS<br>
The Interplanetary File System (IPFS) is a new hypermedia distribution protocol, addressed by content and identities. IPFS enables the creation of completely distributed applications. It aims to make the web faster, safer, and more open.
  
#### 2.6 Benefits to Rex<br>
IPFS provides a means for Rex to distribute the data in a decentralized manner. When a listing is submitted to Rex, Rex hashes the listings identity and pushes the details to IPFS. The data is encrypted by default and disseminated globally to machines running the IPFS instance. Since the data is distributed and not stored on one single computer, costs are reduced and access is universal. The architecture of IPFS provides a built in governor so Rex (or any other dApps built on top of Rex) cannot charge large sums of money or deny access to users. 

## 3.0 Problem/Solution
 
#### 3.1 Problem
 
1. Users sacrifice ownership and control of their real estate data to third party vendors.
2. Transacting real estate is expensive and time consuming with poor communication channels.
 
#### 3.2 Solution
 
1. Build a global real estate database utilizing Ethereum and IPFS. Users maintain ownership/control of their data.
2. Provide transaction layer that will facilitate sale/lease contracts.
 
 
## 4.0 Rex's Model
 
#### 4.1 Model
 
Reed Hastings built Netflix with the idea of streamlining the way users view and receive digital content. First, Hastings exercised value out of the existing technological infrastructure. Users rented dvds online and had them physically delivered via US mail thus avoiding the inconveniences of traditional retail (time, travel, and late fees). Netflix grew exponentially as infrastructure matured and delivery went from physical to digital.
 
Rex is taking a similar long-term approach. Starting with the foundation laid by Ethereum, Rex will begin assembling the database in the form of a multiple listing service. As the database scales and the network stabilizes, Rex will gradually implement the transaction layer.
 
#### 4.2 Phases 
 
●	Phase 1: Build the global real estate database<br>
●	Phase 2: Filtration layers<br>
●	Phase 3: Implement transaction layer<br> 
●	Phase 4: Introduce tokenized ownership into the RexDex exchange “liquid real estate”<br>

There are regulatory hurdles that will be introduced in Phase 3 and 4. First, smart contracts need to recognized by courts as legal, enforceable contracts. This process is beginning to unfold in places like Arizona with the recent signing of HB 2417. Recently, Arizona Governor Doug Ducey signed into law HB 2417 that amends Arizona law to provide that signatures secured through blockchain are valid electronic signatures and that smart contracts are legally, enforceable contracts under Arizona law. [Arizona’s House and Senate approved HB 2417 bill on a nearly unanimous basis.](http://www.swlaw.com/blog/data-security/2017/04/04/arizona-authorizes-smart-contracts-on-a-blockchain/)

Next, banking regulation needs to adopt language applicable to crypto lending. The Consumer Financial Protection Bureau (CFPB) regulates the mortgage industry in the United States. Banks will need to take an active role in gaining the CFPB’s attention and participation. 

Tokenized ownership introduces another set of government oversight. The Securities and Exchange Commission (SEC) promotes full public disclosure, protects investors against fraudulent and manipulative practices in the market, and monitors corporate takeover actions in the United States. Generally, most issues of securities offered in interstate commerce, through the mail or on the internet, must be registered with the SEC. Additionally, the IRS (US tax code), and FINRA will play a part in tokenized ownership. FINRA, as a regulatory body, is tasked with governing all business dealings conducted between dealers, brokers and all public investors. 

Tokenized ownership should be proven in jurisdictions with less regulatory oversight before being introduced and tested in the United States and Australia. Rex will leverage our strength in technology and partner with an entity that has experience with regulation. 

Some layers beyond Phase 1 including a subscription service, polished UI, advanced filtration techniques and user services will be closed source.
 
####  4.3 Token Allocation
 
![Alt description](assets/token_dist.png)
 
Founders and Angels will have a two year vesting period at no more than 1,000,000 REX a year. This is to ensure price stability amongst the REX token.
 
#### 4.4 Token Utility<br>
Phases 1 and 2
 
1. **Listing Rewards**: Verified users are paid "x" REX for every listing they contribute to the database.
2. **Listing Spam Reductor (LSR)**: Users pay "x" REX when submitting a new listing. The LSR is to prevent gaming of the listing rewards contract. The listing reward will always be higher than the LSR. In addition, each new verified user upon their first listing will be issued 5 REX to subsidize their first transaction and LSR.
3. **Curation Feeds**: By default, users are subscribed to Rex's Curation feed. A Curation feed is a screening process where bad listings are weeded out of user query results. For example, Bob lives in New York and believes he can filter spam better than Rex’s default Curation feed. Bob creates a unique feed and gains a following. Users subscribed to Bob’s Curation feed now only see New York query results through Bob’s Curation feed. Bob can monetize his Curation feed through advertising and listing promotion. 
4. **Curation Ads**: Users that create Curation feeds and gain a following can charge REX for promoting listings and advertising throughout their feed.
5. **Market Sponsorships**: Users pay "x" REX to sponsor a geographic market.
6. **Featured Properties**: Offered through Curation feeds. 
7. **Broker & Landlord Professional Profiles**: Users pay "x" REX to create a professional profile. Users with Professional Profiles are searchable in the Rex database.
 
Phases 3 and 4
 
1. **Transaction Services**: Users pay "x" REX to utilize Rex's prebuilt contracts/GUI for transactional purposes. 
2. **Tokenized Contracts**: (RexDex)*
 
In Phase 4, Rex will introduce tokenized ownership. The assets will be traded via Rex’s internal exchange, the RexDex. The REX token will be utilized for trades and settlement services. We will release more information on the  Tokenized Ownership in the coming months.
  
#### 4.5 Listing Rewards 

Listing Rewards provide a distributed means to build and scale the database. Anyone can upload a listing to Rex. Each upload by a verified user will be eligible for the Listing Reward. Users who are verified (see verification below) will receive the Listing Reward. 

Listing rewards are self funded by the platform. In the event transaction fees don’t keep up with reward demand, the reward payout will be lowered or halted.

In addition to REX funding listing rewards, the REX DAO can withdraw from the rewards reserve to fund future priority development. It’s the DAO’s responsibility to convince the Rex community the importance of funding further development projects.
 
#### 4.6 Verification System
 
Rex requires users to register in order to receive the Listing Reward.  Listings submitted by users that are not the broker, landlord or seller must provide Proof of Approval* in order to receive the Listing Reward. 
 
*Rex will provide Proof of Approvals (PoA) to users submitting listings that are not their own. PoA's will require evidence from the user that the listing broker or landlord has authorized them to submit listings on their behalf. Listings submitted without PoA's will not be eligible for the Listing Reward and may result in the user losing their verified status.
 
#### 4.7 Payment Delay
 
Registered listee’s will need to submit a claim for their listing rewards, upon which there is a 2 week period for other users of the platform to submit a protest vote on the claim.  If there is no protest the listee can withdraw their reward at the end of the 2 weeks.  If the listee loses a protested claim then they lose the pending payments and potentially their verification status.
 
*2-week payment delay process: In the two week delay, other users can flag the listing as spam. If the listing is not flagged by other users, the listee is eligible to claim reward. If the listing is flagged, the flagger and flagee will be identified and notified. The listee can do one of two things:
 
1. If listing is spam, forfeit the deposit to flagger for trying to game the listing rewards
2. Protest: User submits a ticket to Rex that they are being unfairly targeted. An arbitration period is initiated and Rex mediates. The flagger or flagee identified as the malicious user loses the fee and their reputation is downgraded. 
 
#### 4.8 Fees
 
REX fees will be collected in the datafeed contract and can be drawn upon for rewards or used by the RexDAO contract.  
 
#### 4.9 Rex Subscription Model
 
Rex will offer a subscription based model that will handle all backend transactions for the user.
 
#### 4.10 Tokensale
 
REX tokens will be distributed according to the following schedule:<br>

Week #1: 1,000 REX Tokens per /1 ETH of Contribution;<br>
Week #2: 900 REX Tokens per /1 ETH of Contribution;<br>
Week #3: 800 REX Tokens per/1 ETH of Contribution;<br>
Week #4: 700 REX Tokens/ per 1 ETH of Contribution<br>

Contract Variables<br>

The contribution period will conclude when one of the two following variables is met:<br>

Conclusion of the four week contribution period<br>
Security cap is met: 133,333 ETH<br>

#### Pool A (Token Sale) consists of 50% of the Total REX Token Supply. Pool A will be allocated to users who have made contributions during the token sale.<br>

#### Pool B consists of 20% of the Total REX Token Supply. Pool B will be allocated to the Listing Reward Contract on the REX platform.<br>

#### Pool C consists of 5% of the Total REX Token Supply. Pool C will be allocated to angel investor.<br>

#### Pool D consisting of 15% of the Total REX Token Supply. Pool D will be allocated to persons who participated as managers, founders, worked to develop the ideas, implementations and supporting structures of the REX Project.<br>

#### Pool E consisting of 7% of the Total REX Token Supply. Pool E will be allocated to partners and/or advisors of the REX Project, as well as to participants of Bounty campaigns.<br>

#### Pool F consisting 3% of the Total REX Token Supply. Pool F will be allocated to corporate affiliates.<br>

The REX Token Sale Address: 0xf05a9382A4C3F29E2784502754293D88b835109C<br>

The token sale contract is based on the OpenZeppelin framework. We have contracted with OpenZeppelin on the creation and testing of the REX token sale contracts. We are also working with Matthew Di Ferrante, who has previously worked with members on the Ethereum Foundation, and recently audited a large exchange’s smart contracting infrastructure that will handle millions of tx’s per day.<br>

#### Sending Instructions<br>

On the day of the token sale, please review the address on the token sale page and cross reference it with at least two of our verified social media accounts (listed below) before contributing. We will continually post the token sale address over our channels throughout the next week.<br>
 
## 5.0 Conclusion
 
Rex believes we should be in control of our listing data. We should have the ability to transact more efficiently. With today’s advances in storage, bandwidth, distribution and flexible blockchains like Ethereum, we can rebuild the old systems into cost effective platforms. Users will retain ownership of their real estate data and not become a product of a larger corporation. They will earn and collect fees for their data, not the platform. Brokers and attorneys won’t spend time and money chasing unpaid invoices. Real estate will become liquid with tokenized ownership. These goals can be achieved with the technology and a proper strategy.  Vision and execution are pivotable to gaining the confidence of Rex’s users base and regulators around the world. Modularizing development into four achievable milestones provides Rex the ability to build, test and deploy the platform so it can succeed and scale.

## 6.0 Founder Bios
 
#### 6.1 Stephen King
 
Stephen is an entrepreneur with a focus in commercial real estate and blockchain technology. Since 2013, Stephen has lead King Realty Group in Princeton, New Jersey and participated in tens of millions in real estate transactions. Stephen has participated in the design of several real estate related technology startups. Stephen is the founder of Princeton Ethereum Meetup.
 
#### 6.2 Russell McLernon
 
Russell is the technology strategist. He brings over 15 years of experience in enterprise software development and over 7 years in blockchain related development and projects. Although acutely technical, he has an innate ability to quickly decipher user needs. There's no software development or integration challenge he can't handle.
 
## 7.0 Contact & References
#### 7.1  Contact
**Email**<br> support@rexmls.com
 
**Rex Landing Page** <br>http://www.rexmls.com
 
**Rex Blog**<br>http://www.rexmls.com/blog/
 
**Slack**<br>https://rexmls.herokuapp.com/

**twitter**<br>https://twitter.com/REXmls

**Facebook**<br>https://www.facebook.com/theREXmls/

**LinkedIn**<br>https://www.linkedin.com/company-beta/11070246/

**Instagram**<br> @theREXmls
 
#### 7.2 References 

1. https://cre.tech/will-sleepy-real-estate-industry-wake-blockchain/
 
2. https://ipfs.io/
 
3. http://legal-dictionary.thefreedictionary.com/Property+(ownership+right)
 
4. https://en.wikipedia.org/wiki/Multiple_listing_service
 
5. http://digitalcommons.law.yale.edu/cgi/viewcontent.cgi?article=1409&context=fss_papers
 
6. http://www.ibtimes.co.uk/ethereums-viktor-tron-talks-about-swarm-skeleton-web-3-0-1560654
 
## 8.0 Appendices 
#### 8.1 Appendix A<br>Real estate transactions: Today
 
Data:<br>
A buyer, tenant or broker searching for a house, office, warehouse, land or retail space typically begins their search with an online MLS. The accessible data is limited before the user hits a paywall. The paywalls consist of annual memberships that enlist high annual fees and collect superfluous data about their customers and their dealings.
 
 
Transaction:<br>
After the user subscribes and locates a property, they engage the listing agent to negotiate price. The buyer and seller have their attorneys draft, edit, and finalize the Purchase & Sale Agreement (PSA). Within the PSA are a list of terms the buyer and seller must perform for the transaction to consummate. The buyer is permitted approximately 30-90 days to perform an analysis of the property called due diligence. Due diligence includes, but is not limited to:
 
1. Structural inspections
2. Electrical inspections
3. Well/septic inspections
4. Roof inspections
5. Environmental inspections
6. Lien queries
7. Survey
 
The buyer’s lender will conduct:
 
1. Mortgage origination (qualify the buyer)
2. Appraisal
3. Title search
 
During due diligence, the seller will perform certain obligations spelled out in the PSA:
 
1. Building repairs
2. Municipal approvals
3. Cure judgments/liens
4. Obtain a certificate of occupancy (if necessary)
 
Throughout the transaction, the buyer and seller communicate through their banks, attorneys, inspectors and real estate brokers. The chain of communication inevitably leads to delays and increased costs to the buyer and seller.
 
Once diligence expires and both sides meet their respective obligations, a closing date is set. The following is a brief list of documents required at closing:
 
1. Closing statement
2. Title report
3. Tax/insurance statements
4. Inspection/survey reports
5. Proof of identity
6. Bank statements/authorizations
7. Funds
 
In the US, closing costs average approximately +$10,000 for residential and approximately +$20,000 for commercial (subject to the size of the deal and local tax jurisdictions).
 
Hypothetical Example
 
Bob wants to sell a mixed use building in Princeton, New Jersey:
 
* Address: 236 Nassau Street
* Price: $3,500,000
* 9 1-bedroom apartments
* 2 retail units
* Net Operating Income: $175,000
* Capitalization Rate: 5%
 
Data:<br>
Bob decides to list 236 Nassau Street on his local MLS. After several weeks and no traction, Bob decides to sign up for the MLS' Premium Addition (approximately $299.95/month). The Premium Edition grants Bob access to surrounding property data. After three weeks and no action, Bob decides to obtain a Comparable Property Analysis. Bob pays approximately $90.00 for the service. The information is dated and proves useless. Bob realizes 234 Nassau is at the bottom of the search query. For an additional fee of approximately $399.95 for 30 days, Bob can have 236 Nassau Street listed as "Platinum" on the results page. Bob proceeds with the Platinum listing.
 
Bob is spending approximately $790.00/month or $790.00/per listing on marketing 234 Nassau Street.
 
Transaction:<br>
Alice’s broker finds Bobs listing on the MLS and presents it to Alice. Alice makes an offer of $3,400,000. Bob accepts Alice’s offer and their attorneys negotiate the Purchase & Sale agreement on the following terms:
 
1. Alice is to obtain 70/30 financing.
2. Due diligence period: 60 days.
3. Closing to take place five days after the due diligence period expires.
4. Bob must repair the damaged sidewalks and obtain electrical inspections.
5. Bob must replace the cast iron waste line with PVC.
6. Bob must replace the damaged roof shingles.
7. Bob’s building must pass a fire inspection.
 
Alice deposits $175,000 in her attorney’s escrow account. Due to miscommunication between the title agency and bank, closing is delayed two weeks costing both Bob and Alice money in attorney fees and carrying costs.  Finally, a closing date is set, and after several hours of paperwork, title is passed. Title is recorded manually at Princeton’s municipal clerk’s office. 
 
Alice and Bob paid approximately $40,000 in combined transaction costs and Bob paid approximately $790.00/month in listing fees.

 
#### 8.2 Appendix B<br>Lease Transaction

Alice, a broker for CBRO, lists a 25,000/SF office suite on REX. Bob, a broker for Ether Realty, shows 123 Alpha to his client, Osprey Inc. Osprey proceeds with a 10-year lease with the following terms:<br>
Contract Details<br>
Property: 123 Alpha Street, Sydney Australia<br>
Tenant: Osprey Inc.<br>
Price: $50.00/SF<br>
Term: 10 years<br>

Lease Contingencies Osprey Inc. (Tenant)<br>
1.	Osprey Inc. to escrow 2-months security upon contract execution<br>
2.	Osprey Inc. to escrow first month's’ rent upon contract execution<br>
123 Alpha Street, Inc. (Landlord)<br>
1.	Demo interior walls within 30 days of contract execution<br>
2.	Escrow and release a $25/SF work letter ($250,000) to Osprey Inc. upon contract execution.<br>
3.	Escrow and pay a 2% brokerage fee to CBRO and 2% fee to Ether Realty, ½ on signing, ½ 90 days after contract execution.<br>

123 Alpha & Osprey’s council collaborate to sign the above into a smart contract on REX. The contract can be amended anytime by having both parties broadcast a transaction to the contract. The contract and changes are viewable in real time on the blockchain. 123 Alpha Inc. and Osprey Inc. agree to use a stablecoin to handle the transfer of funds. All money is escrowed and released according to the terms in the smart contract.

123 Alpha Inc. and Osprey Inc. benefit from a transparent smart contract where changes are viewed and agreed upon quickly. Efficient communication channels lead to a decrease in time and fees. The transaction is permanently recorded on the blockchain providing a secure means for record keeping and lease renewals. CBRO and Ether Realty are paid on time according to the smart contract negating the need for invoicing and payment follow ups; completing our leasing example


#### 8.3 Appendix C<br>Tokenized Ownership

What if you could trade 1,000 tokens in the Chrysler building like you trade a 1,000 shares of Apple?

Background<br>
The Chrysler building was completed May 27, 1930. Owned by Walter P. Chrysler, it was built to serve as Chrysler's new headquarters. The Chrysler building is 77 floors high and approximately 2,062,772 square feet in office space. The building has changed hands several times since the Chrysler family sold it in 1953. In 1998, Tishman Speyer Properties along with Travelers Insurance purchased the Chrysler building for $220,000,000. In 2001, Tishman sold a 75% stake to Abu Dhabi Investment Council. Today, Abu Dhabi Investment Council owns 90% and Tishman retains 10%.<br>

Redefining Real Estate Ownership: Chrysler Dapp<br>
Let’s say Rex purchases Abu Dhabi’s and Tishman’s entire stake in the Chrysler building for $3,000,000,000 cash at a 4% capitalization rate:<br>

The Chrysler building is 90% occupied with long term leases averaging $108/SF. The gross income is $200,500,000 per year. Expenses run about 40% or $80,200,500. Thus, the Net Operating Income is $120,000,000.

Blockchain Using Ethereum, Rex creates a decentralized application called Chrysler Dapp. The Chrysler Dapp creates 1,000,000,000 CHRY tokens. Chrysler Dapp allocates 750,000,000 CHRY tokens (75% of the total supply) to be sold in an upcoming crowdsale. CHRY tokens will be listed at $3.00 per token (valuing the building at $3,000,000,000).

The developers of Chrysler Dapp create an incorporated company called Chrysler Management Inc. Chrysler Management Inc. will be the managing entity of the Chrysler building, responsible for management, leasing and legal. Chrysler Management Inc. will retain 100,000,000 CHRY or 10% of the total supply. The remaining 150,000,000 CHRY will be held for capital reserves.
Each quarter, Chrysler Management Inc. will convert all positive cash flow (after expenses) to CHRY tokens and deposit them in a community smart contract. The contract will distribute CHRY tokens to stakeholders according the percentage of tokens each stakeholder owns.

In the bylaws between CHRY token holders and Chrysler Management Inc., it will state that each quarter (much like public companies are required by the SEC), Chrysler Management Inc. is obligated to release a detailed income and expense report for that quarter.

Economics<br>
Token participants have the opportunity to own a piece of an iconic building in New York City with a potential 10% upside: If Chrysler Management Inc. leases the 10% vacancy, it will increase net operating income which in turn should increase the value of the building:<br>
> vacancy + tenant = +NOI = +building value = +CHRY token value

Market equilibrium shows us an increase in value usually creates an increase in price. Conversely, if Chrysler loses a major tenant the token’s value should decrease.

Physical Asset<br>
As we’ve seen with recent token sales, prices fluctuate and markets can be highly irrational. However, a physical asset like the Chrysler building can be pegged to the local real estate market offering a more precise determination of value and perceived risk.

for example:<br>
ABC Inc. occupies 500,000/SF at $108/SF. Their lease expires and they vacate the Chrysler building. In one deal, the asset loses $54,000,000 in gross annual income. The CHRY token price drops to $1.00 valuing the building at $1,000,000,000. A few sophisticated individuals discover the actual market value (after the loss of ABC Inc.) should be closer to $1,700,000,000:
$146,500,000 — $80,200,000 = $66,300,000 NOI at a 4% CAP = $1.657 billion or $1.67 per CHRY token.

The investors can profit from a potential $0.67 upside in token value, long term building appreciation and any increase in value once the remaining 10% vacancy is filled.
The same is true if the token value jumps to $4.00 or $4,000,000,000 with no real increase in NOI. Sophisticated investors may short CHRY tokens thus stabilizing value with market equilibrium.

