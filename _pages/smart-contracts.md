---
layout: single
title: Smart Contract History and Related Resources
description: From Szabo and E Lang - to Ethereum, the DAO, Smart Signatures, and the Cambrian Explosion.
header:
  image: https://infominer.id/bitcoin-history/assets/img/elems10.png
  caption: "[erights.org - CapTP Ops: provideFor()](http://www.erights.org/elib/distrib/captp/provideFor.html) '98"
author_profile: false
permalink: smart-contracts/
redirect-from: smart-contracts
---


I was writing this basic introduction, [Smart Contracts: Use cases, and DApps](https://www.axiomtech.io/blog-feed/2018/10/9/smart-contracts-uses-cases-dapps-icos)
  >Smart contracts are self-executing code that defines and executes an agreement between multiple parties. That code contains simple “if/when…then…” statements executed within a distributed network that achieves consensus on transactions made within it.

When I came across:

* [lambda-the-ultimate.org/node/5003#comment-94645](http://lambda-the-ultimate.org/node/5003#comment-94645) 
  * *A Next Generation Smart Contract and Decentralized Application Platform* (Vitaliks ANN post on lambda-the-ultimate)
    > Smart contracts and related languages have a long discussion history on LtU
    
Which took me down the rabbithole and led to the creation of this resource.

## Smart Contract History

![](https://infominer.id/bitcoin-history/assets/img/elems10.png)<br>
  > VatA (the donor) deposits a reference to gift at nonce in VatC's (the host's) from-VatA-for-VatB table, and returns a Vine for the gift-entry. 


## Contents
* [Contents](#contents)
  * [ObCap - Object Capabilities](#object-capabilities)
  * [Nick Szabo](#nick-szabo)
  * [E Lang and Other Early Work](#elang-and-other-early-work)
  * [Ethereum](#ethereum)
  * [DAO](#dao)
  * [After DAO](#after-dao)
* [Resources](#resources)
  * [Ricardian - Legal](#ricardian---legal)
  * [Smart Signatures](#smart-signatures)
  * [Bitcoin](#bitcoin)
  * [Languages\Platforms](#languages---platforms)
  * [Learn-BUIDL](#learn-buidl)
  * [ETC](#etc)
  * [Literature](#literature)
  * [Resources](#resources)


### Object Capabilities (ObCap)

The object-capability model was first proposed by Jack Dennis and Earl C. Van Horn in the 1966 paper.
* [Programming Semantics for Multiprogrammed Computations](https://www.princeton.edu/~rblee/ELE572Papers/Fall04Readings/ProgramSemantics_DennisvanHorn.pdf)
  >The semantics are defined for a number of meta-instructions which perform operations essential to the writing of programs in multiprogrammed computer systems. These meta-instructions relate to parallel processing, protection of separate computations, program debugging, and the sharing among users of memory segments and other computing objects, the names of which are hierarchically structured. The language sophistication contemplated is midway between an assembly language and an advanced algebraic language. 
* [What Are Capabilities?](https://web.archive.org/web/20190423063056/http://habitatchronicles.com/2017/05/what-are-capabilities/)
  >The capability paradigm is about access control. When a system, such as an OS or a website, is presented with a request for a service it provides, it needs to decide if it should actually do what the requestor is asking for. The way it decides is what we’re talking about when we talk about access control. If you’re like most people, the first thing you’re likely to think of is to ask the requestor “who are you?” The fundamental insight of the capabilities paradigm is to recognize that this question is the first step on the road to perdition. That’s highly counterintuitive to most people, hence the related controversy.
* [wikipedia- Object-capability model](https://en.wikipedia.org/wiki/Object-capability_model)
* [Awesome Object Capabilities and Capability-based Security](https://github.com/dckc/awesome-ocap)
* [Linked Data Capabilities](https://github.com/WebOfTrustInfo/rwot5-boston/blob/master/final-documents/lds-ocap.md)
  * [Object Capabilities for Linked Data v0.3](https://w3c-ccg.github.io/ocap-ld/)
* [Cosmos Object-Capability Model](https://cosmos.network/docs/intro/ocap.html)
* [Ethereum Object Capabilities](https://ethereum-magicians.org/t/ethereum-object-capabilities/3035/3)
* [Security in Scala: Using Object Capabilities](https://tersesystems.com/blog/2018/06/24/security-in-scala/)
  * [A Guide To Capabilities](https://wsargent.github.io/ocaps/guide/)
* [DIDAuth + Obj. Cap.](https://iiw.idcommons.net/DIDAuth_%2B_Obj._Cap.)
* [History of Object Capabilities](http://clive.tries.fed.wiki/view/deep-thoughts-on-wiki/view/history-of-object-capabilities)
* [https://www.infoq.com/interviews/johnson-armstrong-oop/](www.infoq.com/interviews/johnson-armstrong-oop/) - [anaphor](https://news.ycombinator.com/item?id=19988339)
  > Then, my thesis supervisor said "But you're wrong, Erlang is extremely object oriented". He said object oriented languages aren't object oriented. I might think, though I'm not quite sure if I believe this or not, but Erlang might be the only object oriented language because the 3 tenets of object oriented programming are that it's based on message passing, that you have isolation between objects and have polymorphism.

	

Object Capabilities are new to me, and I'm just placing any related information here for now until I make them a page of their own.

Basically this research starting in the 60's, with much work throughout the 80's (that is not well dowcumented online), culminating with Nick Szabo's work, and E Language. Object Capabilities are central to the original line of work the term "Smart Contracts" was used in reference to, which was somewhat misappropriated by Vitalik.

#### Agoric

* [Agoric](https://agoric.com/about/)
  * [Object Capabilities with Kate Sills](https://librelounge.org/episodes/episode-13-object-capabilities-with-kate-sills.html) (podcast)

#### Mark S Miller

>Mark S. Miller is an American computer scientist. He is known for his work as one of the participants in the 1979 hypertext project known as Project Xanadu; for inventing Miller columns; as the co-creator of the Agoric Paradigm[1] of market-based distributed secure computing; and the open-source coordinator of the E programming language. He also designed the Caja programming language.
>
>Miller earned a BS in computer science from Yale in 1980 and published his Johns Hopkins PhD thesis in 2006.[2] Previously Chief Architect with the Virus-Safe Computing Initiative at HP Labs, he is now a research scientist at Google[3] and a member of the ECMAScript (JavaScript) committee.[4] - [Wikipedia](https://en.wikipedia.org/wiki/Mark_S._Miller)

* [agoric.com/authors/mark-s-miller](https://agoric.com/authors/mark-s-miller/)
* [marksammiller@twitter.com](https://twitter.com/marksammiller)

### Nick Szabo

* [Nick Szabo](https://ipfs.io/ipfs/QmXoypizjW3WknFiJnKLwHCnL72vedxjQkDDP1mXWo6uco/wiki/Nick_Szabo.html) - Distributed Wikipedia Powered by IPFS
* [Nick Szabo's Essays, Papers, and Concise Tutorials](http://archive.is/H8UGk) - Nick Szabo's Home Page
* [Smart Contracts Glossary](http://archive.is/fcx3I) '95 
* [Smart Contracts: Building Blocks for Digital Markets - Nick Szabo 1996](http://www.alamut.com/subj/economics/nick_szabo/smartContracts.html)
* [Formalizing and Securing Relationships on Public Networks](http://ojphi.org/ojs/index.php/fm/article/view/548/469)- Nick Szabo
* [Let's Talk Bitcoin! #246 Smart Contracts with Nick Szabo](https://letstalkbitcoin.com/blog/post/lets-talk-bitcoin-246-smart-contracts-with-nick-szabo)
  > Adam, Stephanie and Andreas spend an hour with crypto-scholar of note Nick Szabo in a wide ranging discussion covering Smart Contracts, Bitcoin and Blockchains. 
* [A Technology, Legal & Regulatory Introduction — Foreword by Nick Szabo](https://gallery.mailchimp.com/a87f67248663abe55ad9325d6/files/Smart_Contracts_12_Use_Cases_for_Business_Beyond.pdf)
  * Prepared by: Smart Contracts Alliance — In collaboration with Deloitte
    > "the most secure environments for smart contracts are the most mature public blockchains, which are designed for trust minimization instead of trusting the often private and insecure system found resident with a central party" @NickSzabo4 
* [A Formal Language for Analyzing Contracts](https://nakamotoinstitute.org/contract-language/) '02
* [Wet Code and Dry](http://unenumerated.blogspot.com/2006/11/wet-code-and-dry.html) '06

### Elang and other Early Work 

* [erights.org](http://www.erights.org/smart-contracts/)
* [wiki.c3.com - E Language An ObjectCapabilityLanguage](http://wiki.c2.com/?EeLanguage)
* [Mailing list ARChives— e-lang The E capability-secure scripting language](https://marc.info/?l=e-lang)
* [monte.readthedocs.io](https://monte.readthedocs.io/en/latest/)
  >* Monte is a programming language inspired by the E and Python programming languages. Monte aims to be:
  >* A reliable scaffold for secure distributed computing
  >* An example of capability-safe programming language design
  >* A model for misuse-resistant programming
* [news.ycombinator.com - E Programming Language](https://news.ycombinator.com/item?id=19981720#19985614)
  * [kentonv](https://news.ycombinator.com/item?id=19987621)
    >I'm always astounded by the depth to which Mark has explored this space. On more than a few occasions, I've come up with an interesting idea for a new protocol or programming language feature or piece of distributed systems infrastructure and told Mark about it, only to find he had already thought of that problem and discovered and solved several issues I hadn't even thought about yet.
    >
    >Cap'n Proto RPC [https://capnproto.org/rpc.html](https://capnproto.org/rpc.html) is based on E's network protocol, CapTP, e.g. utilizing The Four Tables:
    >
    >[http://erights.org/elib/distrib/captp/4tables.html](http://erights.org/elib/distrib/captp/4tables.html)
    >
    >[https://github.com/capnproto/capnproto/blob/master/c++/src/capnp/rpc.capnp#L116](https://github.com/capnproto/capnproto/blob/master/c++/src/capnp/rpc.capnp#L116)
    >
    >(You can think of this design as an extension of the file descriptor table concept in Unix, except that both sides may export descriptors to the other side (so that calls can flow either way), and either side can be responsible for assigning the numeric descriptor value for any particular description (which makes it easier to compensate for a high-latency transport).)
    >
    >When I first told Mark I was working on an object-oriented RPC protocol, he insisted I visit him and listen while he explained all this to me, and boy am I glad he did... would have taken a lot longer for me to figure it out myself.
    >
    >It's crazy that most of the content of erights.org was written over 10 years ago -- I think some of it goes back to the 90's, even.
  * [7373737373](https://news.ycombinator.com/item?id=19986189)
    > Modern smart contract systems should learn a lesson or five from it, most importantly, (object) capability security.
    >
    >Why? Because it lets programs handle permissions like other objects, keeping them apart and thus reducing the attack surface and preventing Confused Deputy [0] attacks. 
    >
    > [https://en.m.wikipedia.org/wiki/Confused_deputy_problem](https://en.m.wikipedia.org/wiki/Confused_deputy_problem)
  * [ghosthamlet - news.ycombinator](https://news.ycombinator.com/item?id=19987751)
    > The E on Common Lisp Project website is down, code on github: https://github.com/kpreid/e-on-cl
    >
    > e-on-javascript: https://github.com/kpreid/e-on-javascript






### Ethereum 

... *Much More Ethereum Specific - Coming Soon* ...

### DAO 

* [What’s in a Name? — The Disambiguation of Smart Contracts](https://medium.com/@anthonymacey/whats-in-a-name-the-disambiguation-of-smart-contracts-daca8276db4)
  >2014 and Gavin Wood takes the stage at the auditorium in Barclays Whitechapel Accelerator space to describe a brave new world of…
* [They Might be Smart, but these contracts need to be more Secure](https://www.americanbanker.com/news/they-might-be-smart-but-these-contracts-need-to-be-more-secure) '16
* [Scanning Live Ethereum Contracts for Bugs](http://hackingdistributed.com/2016/06/16/scanning-live-ethereum-contracts-for-bugs/) - '16
  >In this post, we examine just how prevalent the recently discovered "unchecked-send" bug is in real, live, deployed Ethereum contracts, with the aid of an automated analysis 


### After DAO 

* [The Future of the Blockchain: my DevCon IV talk. – Mattereum - Humanizing the Internet](https://medium.com/humanizing-the-singularity/the-future-of-the-blockchain-my-devcon-iv-talk-f78b4fb9b95c)
  > This year October 31 at the DevCon IV I gave the first talk on the Smart Property Register  —  the Mattereum innovation, which I think is…
* [Researchers: Roughly 60% of Ethereum smart contracts have never been interated with](https://www.theblockcrypto.com/tiny/researchers-roughly-60-ethereum-smart-contracts-have-never-been-interacted-with/)
  >A group of researchers from the Northeastern University and the University of Maryland published a paper detailing their analysis of Ethereum’s contract topology. The researchers modify Ethereum’s geth client to log how users and contracts interact with one another. The r...
* [Ethereum in BigQuery: a Public Dataset for smart contract analytics](https://cloud.google.com/blog/products/data-analytics/ethereum-bigquery-public-dataset-smart-contract-analytics)
  > Ethereum transactions, like some other cryptocurrencies, are stored in a public ledger. Learn how to analyze that ledger in BigQuery to better understand transaction and even contracts history.

## Resources 

### Ricardian - Legal 

* [On the intersection of Ricardian and Smart Contracts](https://iang.org/papers/intersection_ricardian_smart.html)
* [Smart Contracts, Dumb Signatures: Why Blockchain-based signatures](https://medium.com/@blockarray/smart-contracts-dumb-signatures-why-blockchain-based-signatures-may-not-be-legal-in-your-efb64bc030c0)
  >This is not legal advice, please seek professional guidance from an attorney.
* [Defining smart contracts – Craig Wright – Medium](https://medium.com/@craig_10243/defining-smart-contracts-eb31fd825de6)
  > When contrasting contractual principles, it is clear that where a contract is not required to be in writing (Columbia Law Review, Apr…
* [The application, scope and limits of Letters of Indemnity in Bitco...](https://medium.com/@craig_10243/the-application-scope-and-limits-of-letters-of-indemnity-in-bitcoin-contracts-633e1491cf1)
  > The Bill of Lading is a document unique document as its negotiability fulfils several purposes. These documents have led to a…
* [coala.global](http://coala.global/)
  - Coalition of Automated Legal Applications


### Smart Signatures 

* [WebOfTrustInfo/rwot2-id2020 - Smarter Signatures](https://github.com/WebOfTrustInfo/rwot2-id2020/blob/master/draft-documents/smarter-signatures.md)
* [Smart Signatures—Experiments in Authentication -Christopher Allen](https://www.slideshare.net/ChristopherA/smart-signaturesexperiments-in-authentication-stanford-bpase-2018-final) -SlideShare
  [![](https://i.imgur.com/wxMkWLW.png)](https://www.slideshare.net/ChristopherA/smart-signaturesexperiments-in-authentication-stanford-bpase-2018-final)

{% include video id="E9sbWKbfyJU" provider="youtube" %}
[*Transcript](https://infominer.id/bitcoin-history/transcripts/smart-signatures-christopher-allen/)

* [WebOfTrustInfo/rwot5-boston -Smarm: Requirements for a smart-signatures Scheme](https://github.com/WebOfTrustInfo/rwot5-boston/blob/master/draft-documents/smarm.md)
  ![](https://pbs.twimg.com/media/DNZYt5VVQAAWWuw.jpg)

![](https://pbs.twimg.com/media/DNZbyqMVwAEfp8a.jpg:large)

* [Simplicity Itself for Blockchains](https://blockstream.com/2017/10/30/simplicity/)
  * [https://blockstream.com/simplicity.pdf](https://blockstream.com/simplicity.pdf)
    ![](https://i.imgur.com/YWNr9W3.png)

* [Near Future of Programming Languages](http://dev.stephendiehl.com/nearfuture.pdf)
 - Stephen Diehl (@smdiehl) '17
  

### Bitcoin 

* [Yes, Bitcoin Can Do Smart Contracts and Particl Demonstrates How](https://bitcoinmagazine.com/articles/yes-bitcoin-can-do-smart-contracts-and-particl-demonstrates-how/)
The Bitcoin blockchain is not known for its ability to enable smart contracts. In fact, most developers creating smart contracts use a different blockchain, like Ethereum. But the truth is that the Bitcoin protocol can be used to create smart contracts. Particl.io, the blockc...
* [Scriptless Scripts: How Bitcoin Can Support Smart Contracts](https://bitcoinmagazine.com/articles/scriptless-scripts-how-bitcoin-can-support-smart-contracts-without-smart-contracts/)
Bitcoin’s capacity is limited. Meanwhile, smart contracts can be resource intensive. So even though Bitcoin has always supported basic smart contract functionality, the two have never been a natural match.But a recent topic of research spearheaded by Blockstream mathematici...
* [http://www.rootstock.io/](http://www.rootstock.io/)
  >RSK, bitcoin´s smart contract platform.


### Languages - Platforms 


* [Overtorment/awesome-smart-contracts](https://github.com/Overtorment/awesome-smart-contracts)
  > List of awesome platforms for smart contracts. Contribute to Overtorment/awesome-smart-contracts development by creating an account on GitHub.
* [Comparison of Smart Contract Platforms – Hacker Noon](https://hackernoon.com/comparison-of-smart-contract-platforms-2796e34673b7)
  >Ivy-lang, Plutus, Solidity, Scrypto, Michelson, Hoon, Rust, …
* [Meet ‘Spedn’ — A Smart Contract Programming Language for Bitcoin Cash](https://thebitcoinnews.com/meet-spedn-a-smart-contract-programming-language-for-bitcoin-cash/)
  * On Wednesday, a developer called Tendo Pein announced the launch of a new smart contract programming language for the Bitcoin Cash network. Pein said “Spedn,” a BCH-based language, is designed for explicitness and safety while having a syntax similar to the C programming ...
* [Cardano Introduces Smart Contracts For Financial Transactions](https://toshitimes.com/cardano-introduces-smart-contracts-for-financial-transactions/)
  > Marlowe, a new smart contract language for Cardano aimed primarily at financial contracts on the blockchain was revealed some days ago. The language has been developed by researchers from IOHK, a company that are the main developers and maintainers of the blockchain Cardano. 


### Learn-BUIDL 

This page isn't really about learning how to do smart contracts, but more about the history and different aspects of smart contracts. However, I have these links, and I'll throw them here until I make a page devoted to learning how-to.

* [Learn Solidity — The Ethereum smart contract programming language](https://medium.com/@robbertvermeulen/learn-solidity-the-ethereum-smart-contract-programming-language-7f106fc26d6)
  > In the course of time that I am involved in Ethereum development, I have noticed that not much information exists yet to learn Solidity…
* [https://solidity.readthedocs.io/](https://solidity.readthedocs.io/)
* [NEO Smart Contract development](https://www.linkedin.com/pulse/neo-smart-contract-development-m%C3%A1t%C3%A9-moln%C3%A1r/)
  > My first Smart Contract on NEO blockchain in C#: Open Visual Studio 2017. In Team explorer click on Clone and insert the neo-compiler link: https://github.
* [Blockchain Unleashed: IBM Blockchain Blog](https://www.ibm.com/blogs/blockchain/2018/07/what-are-smart-contracts-on-blockchain/)
  >Whether you're new to smart contracts on blockchain, or you’re looking for an in-depth explanation, this guide is a great place to start.

---

* [Building a non-fungible token sales smart contract](https://medium.com/coinmonks/building-a-non-fungible-token-sales-smart-contract-6573350d5a33) -Selling non-fungible tokens and the ERC721 standard

---

* [Philip Daian | Smart Contract Security - Incentives Beyond the Launch](https://slideslive.com/38911605/smart-contract-security-incentives-beyond-the-launch)
  >To mitigate security issues that were quickly evident in the deployment of smart contracts, developers have tried a wide variety of security techniques. Standard when deploying new contracts is...
* [Preparing for a Smart Contract Code Audit – ConsenSys Media](https://media.consensys.net/preparing-for-a-smart-contract-code-audit-83691200cb9c)
  > If you are planning to launch a project on the Ethereum blockchain, you probably know the importance of a third-party code audit. An…
* [Solidified - Audit Platform for Smart Contracts](https://solidified.io/)
  > A platform for crowd-sourced review of smart contracts, where any developer can bring their contract for review with a large network of verified blockchain experts.


### ETC 

* [The Truth about Smart Contracts – Jimmy Song – Medium](https://medium.com/@jimmysong/the-truth-about-smart-contracts-ae825271811f)
  >Much like the words “blockchain”, “AI” and “cloud”, “smart contract” is one of those phrases that get a lot of hype.
* [Smart contracts: Turing completeness & reality – Hacker Noon](https://hackernoon.com/smart-contracts-turing-completeness-reality-3eb897996621)
  > The meltdown of “The DAO” and, more recently DDOS attacks on Ethereum have spurred a debate on the wisdom of “Turing completeness” in…
* [Bribery-Resistant Voting Schemes for Smart Contracts](https://ethresear.ch/t/bribery-resistant-voting-schemes-for-smart-contracts/3354)
  > This is joint work/post with Ian Miers, Oded Naor, and Ari Juels. Recently, a number of proposals and applications have evolved on Ethereum that require voting; from contracts that use voting-based DAOs for governance or other administrative tasks, to boardroom-like votes to...
* [Why Many Smart Contract Use Cases Are Simply Impossible](https://www.coindesk.com/three-smart-contract-misconceptions/)
  >Coin Sciences CEO Gideon Greenspan attacks common misconceptions that he argues are contributing to outlandish expectations for smart contracts.
* [Deloitte Insights - Upgrading blockchains](https://www2.deloitte.com/insights/us/en/focus/signals-for-strategists/using-blockchain-for-smart-contracts.html)
  > Paper contracts can take weeks to travel around the globe, while digital documents are uncomfortably easy to forge. Is there a way to automate transactions to make them smoother, more efficient, and more secure for all parties? Leaders are looking at blockchain and smart cont...

### Literature 

* [They Might Be Smart, But These Contracts Need to Be More Secure](https://publications.lib.chalmers.se/records/fulltext/234939/234939.pdf)
  >A certification process can provide participants in smart contracts with greater assurances they won't lose their money (see: the DAO). But in distributed systems, the true test of security comes when software is released into the wild.
* [Most Cited Smart Contracts Publications](https://blockchainlibrary.org/2017/10/most-cited-smart-contracts-publications/)

### Resources 

* [https://en.bitcoinwiki.org/wiki/Smart_contract](https://en.bitcoinwiki.org/wiki/Smart_contract)
  > Smart contract (also self-executing contract, blockchain contract, or digital contract) is an electronic algorithm intended for the automation of the contract execution process in the blockchain. The general idea of smart contracts is to exclude divergences in the treatment ...
* [OpenLaw — A free legal repository](https://openlaw.io/)
  > We are home to a passionate group of people, technologists, and dreamers committed to rebuilding the legal industry.
* [Investopedia — Smart Contracts](https://www.investopedia.com/terms/s/smart-contracts.asp#ixzz5SuPmOFNW)
  > Smart contracts are self-executing contracts with the terms of the contract between buyer and seller directly written into lines of code.
