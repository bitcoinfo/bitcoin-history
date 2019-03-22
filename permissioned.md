---
title: The History of Permissioned Ledgers
description: "Starting from 2014, the term 'distributed ledger' came into use, and the idea of 'Blockchain for Business' was born. What's become of permissioned ledgers over the years?"
image: "https://i.imgur.com/UnfJmvG.png"
---

# History of Permissioned Ledgers

Primarily to be focused on the development of permissioned ledgers, but including some general enterprise stuffs while I get my timeline together.

I used this space to prep for writing this article: 

* [The Times and History of Permissioned Ledgers](https://www.axiomtech.io/blog-feed/history-of-permissioned-ledgers)

I'll get around to making this a real space eventually, but working on the above article satisfied my curiosity.. I'm just not interested enough in permissioned blockchain to focus much energy here.

However, if you are looking at this, and the above article, thinking: "I really would love a more detailed report" feel free to [contact me](https://infominer.id) so we can discuss your needs. 

---

## Contents

* [Early use, and discussion of "Distributed Ledger"](#early-use-and-discussion-of-distributed-ledger-)
* [Misc-2015](#misc-2015-)
* [Multichain](#multichain-)
* [Hyperledger](#hyperledger-)
* [Fabric](#fabric-)
* [Sawtooth](#sawtooth-)
* [Iroha](#iroha-)
* [Evernym-Sovrin](#evernym-sovrin-)
* [Quorum](#quorum-)
* [R3-Corda](#r3-corda-)
* [Misc-2016](#misc-2016-)
* [2017](#2017-)
* [2018](#2018-)

## Early use, and discussion of "Distributed Ledger" [**^**](#contents)

* [Decentralized Anonymous Credentials](https://eprint.iacr.org/2013/622.pdf)
  >"Our approach builds on recent results in the area of electronic cash and uses techniques — such as [...] a distributed transaction ledger" and later they even use the words "distributed ledger" together but informally 
* [Innovations in Payment Technologies & Emergence of Digital Currencies—Bank of England](https://web.archive.org/web/20141021033143/https://www.bankofengland.co.uk/publications/Documents/quarterlybulletin/2014/qb14q3digitalcurrenciesbitcoin1.pdf)
  > This article argues, however, that the key innovation of digital currencies is the ‘distributed ledger’ which allows a payment system to operate in an entirely decentralised way, without intermediaries such as banks.
* [Today I realized that Satoshi Nakamoto's great invention was the blockchain, not Bitcoin](https://www.reddit.com/r/Bitcoin/comments/1tt88c/today_i_realized_that_satoshi_nakamotos_great/) (Dec '13)
* https://www.coindesk.com/top-10-bitcoin-myths-debunked

* [A SIMPLE MODEL TO MAKE SENSE OF THE PROLIFERATION OF DISTRIBUTED LEDGER, SMART CONTRACT AND CRYPTOCURRENCY PROJECTS](https://gendal.me/2014/12/19/a-simple-model-to-make-sense-of-the-proliferation-of-distributed-ledger-smart-contract-and-cryptocurrency-projects/) 12/2014

* https://domsteil.com/2014/12/29/distributed-consensus-protocols/


### Monax - Eris [**^**](#contents)

—the first open-source permissioned blockchain

* $100,000 bounty [was announced](https://www.reddit.com/r/Bitcoin/comments/25sf4f/100000_bounty_for_software_platform_that_can/) for the creation of a software platform to replace the Bitcoin Foundation, out of concerns over a lack of transparency

I’m into blockchains, having been a founder and former COO of [Monax](https://monax.io/). Monax built [the first](https://blogs.wsj.com/moneybeat/2015/04/14/bitbeat-blockchains-without-coins-stir-tensions-in-bitcoin-community/) open-source permissioned blockchain client in 2014. The design has since evolved into the market-leading Hyperledger Burrow permissioned Ethereum blockchain node. Burrow is presently the Hyperledger Project’s only Ethereum Virtual Machine (EVM), and is used by Intel and IBM’s contributions to that project, Sawtooth and Fabric, to run EVMs on those codebases. 

* https://prestonbyrne.com/2014/06/02/project-d/
  > In response, Casey Kuhlman, Dennis McKinnon and Preston Byrne of Monax led an effort to create the worlds first Decentralized Autonomous Organization
* https://prestonbyrne.com/2014/10/25/introducing-eris-industries/
  - This became [Eris Industries](https://web.archive.org/web/20150213194226/https://erisindustries.com/), growing into an open-source [Distributed Application Software Stack](https://web.archive.org/web/20160411053017/https://blog.erisindustries.com/philosophy/2016/03/02/eris-and-tendermint/) including a distributed application server ([Decerver](https://web.archive.org/web/20150414200414/https://decerver.io/)), [ErisDB](https://web.archive.org/web/20151120220014/https://erisindustries.com/components/erisdb/),

They didn't win the bounty, but their open-source permissionable implementation of the Ethereum Virtual Machine (EVM) was submitted to the Hyperledger Foundation under the name [Burrow](https://www.hyperledger.org/wp-content/uploads/2017/06/HIP_Burrowv2.pdf), and has helped any number of people and organizations experiment with a blockchain virtual machine.

* https://prestonbyrne.com/2015/04/08/blockchain-without-bitcoin-is-now-a-thing/


## Misc-2015 [**^**](#contents)

<img src="https://static1.squarespace.com/static/5b83cf270dbda3e6230cec3d/t/5c51336c898583c26f213862/1548825472554/permissioned-distributed-ledger-blockchains.png"/>
<a href="https://www.ofnumbers.com/2015/07/20/buckets-of-permissioned-permissionless-and-permissioned-permissionlessness-ledgers/">Tim Swanson-Permissioned, Permissionless, and Permissioned Permissionless Ledgers—2015</a>

* [An Overlooked Development: Ethereum, IBM ADEPT and the Internet of Things (IoT)](https://rywalk.wordpress.com/2015/01/27/ethereum-ibm-adept-and-the-internet-of-things-iot/)
  * [Device democracy - Saving the future of the Internet of Things - IBM](http://www-01.ibm.com/common/ssi/cgi-bin/ssialias?subtype=XB&infotype=PM&appname=GBSE_GB_TI_USEN&htmlfid=GBE03620USEN&attachment=GBE03620USEN.PDF#loaded)
* [19 Crypto 2.0 projects to watch - 2015](https://www.coindesk.com/19-crypto-2-0-projects-watch-2015)
* [COST? TRUST? SOMETHING ELSE? WHAT’S THE KILLER-APP FOR BLOCK CHAIN TECHNOLOGY?](https://gendal.me/2015/01/15/cost-trust-something-else-whats-the-killer-app-for-block-chain-technology/)
  * Could decentralized ledgers change the face of accounting?
* https://a16z.com/2015/11/11/blockchain-bitcoin-fintech/

* https://bitcoinmagazine.com/articles/itbit-hires-former-nydfs-general-counsel-daniel-alter-pushes-ahead-bankchain-project-1441313267/ (https://www.itbit.com/)

* https://www.ofnumbers.com/wp-content/uploads/2015/04/Permissioned-distributed-ledgers.pdf

* https://prestonbyrne.com/2015/04/19/crypto-2-0-musings-deconstructing-trust/

* [BITCOIN AND BLOCKCHAIN: TWO REVOLUTIONS FOR THE PRICE OF ONE?](https://gendal.me/2015/07/23/bitcoin-and-blockchain-two-revolutions-for-the-price-of-one/)

* https://www.ibtimes.co.uk/deloitte-libra-accenture-work-auditors-age-bitcoin-2-0-technology-1515932

* [Nick Szabo: If banks want benefits of blockchains they must go permissionless](https://www.ibtimes.co.uk/nick-szabo-if-banks-want-benefits-blockchains-they-must-go-permissionless-1518874)
  >"bureaucracies are so heavily invested in the expertise and importance of local regulations and standards that it’s extremely difficult for them to cut the Gordian knot and implement seamless global systems,” said Szabo. “So they keep trying to re-inject points of control, and thus points of vulnerability, into blockchains, e.g. through ‘permissioning’; but this nullifies their main benefits, which come from removing points of vulnerability.”

* [Consensys and Microsoft form relationship to deliver enterprise Ethereum Blockchain-as-a-Service (E BaaS) on Microsoft Azure.](https://web.archive.org/web/20160304024513/https://consensys.net/static/MSFT-CON.pdf)

## Multichain [**^**](#contents)

* [Multichain](https://www.multichain.com/download/MultiChain-White-Paper.pdf) is a Bitcoin based permissioned ledger. 
(6/15)


## Hyperledger [**^**](#contents)

* [The Hyper Ledger Transaction Protocol (HLTP) is protocol designed from the ground up to enable payments for the internet age](https://safenetforum.org/t/the-hyper-ledger-transaction-protocol-hltp-is-protocol-designed-from-the-ground-up-to-enable-payments-for-the-internet-age/660) '14
  - original Hyperledger, IP later [sold to Digital Asset](https://hub.digitalasset.com/press-release/digital-asset-acquires-hyperledger-following-prior-acquisition-of-bits-of-proof) and given to the Hyperledger foundation.
* [Linux Foundation unites Industry Leaders to Advance Blockchain Tech](https://www.linuxfoundation.org/press-release/2015/12/linux-foundation-unites-industry-leaders-to-advance-blockchain-technology/) 12/2015


## Fabric [**^**](#contents)

* [A Brief History of Hyperledger Fabric](https://www.linkedin.com/pulse/hyperledger-fabric-brief-history-binh-nguyen)

https://wiki.hyperledger.org/projects/fabric#history

* https://github.com/openblockchain
  - The beginning of what became hyperledger fabric

https://www.hyperledger.org/blog/2017/07/11/hyperledger-fabric-1-0-is-released


## Sawtooth [**^**](#contents)


https://docs.google.com/document/d/1j7YcGLJH6LkzvWdOYFIt2kpkVlLEmILErXL6t-Ky2zU/edit


https://www.ibtimes.com/intel-reveals-its-plan-blockchain-technology-sawtooth-lake-distributed-ledger-2350599

https://bitcoinmagazine.com/articles/intel-develops-sawtooth-lake-distributed-ledger-technology-for-the-hyperledger-project-1460397461/


## Iroha [**^**](#contents)

https://docs.google.com/document/d/1sN-6mv-m85NlbI3ZjwFkDT0izTcxbUaZN9LjLEe045Y/edit

https://www.hyperledger.org/blog/2016/11/01/hyperledger-welcomes-iroha

https://arxiv.org/pdf/1809.00554.pdf

## Evernym-Sovrin [**^**](#contents)

Around the same time, Evernym published its initial [identity white paper](https://www.evernym.com/wp-content/uploads/2017/02/Identity-System-Essentials.pdf) and began its work on [Plenum], an implementation of RBFT consensus, supporting the development of a [decentralized public key infrastructure (DPKI)](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust/blob/master/final-documents/dpki.pdf).

In September, the open-source Sovrin codebase was [donated to the Sovrin Foundation](http://www.windley.com/archives/2016/09/announcing_the_sovrin_foundation.shtml): a private-sector, international non-profit established to govern a global public utility for self-sovereign identity.

for more info on this see: https://github.com/infominer33/awesome-decentralized-id

## Quorum [**^**](#contents)

10/2016, JP Morgan announced their development of Quorum, a permissioned version of Ethereum supporting data privacy to enable interaction between public and private blockchains and allowing for private, secure, peer-to-peer transactions.

* [J.P. Morgan Has a New Twist on Blockchain](http://archive.is/Q1Xm0)
https://futurism.com/say-hello-to-quorum-j-p-morgans-private-blockchain-network

## R3 - Corda [**^**](#contents)

11/16, R3 [open-sourced Corda](https://www.ofnumbers.com/2017/02/27/a-brief-history-of-r3-the-distributed-ledger-group/), it’s permissioned distributed ledger platform. Corda features private transactions and smart contracts based upon [Smart Contract Templates: foundations, design landscape, and research directions, Barclays, University College London](https://arxiv.org/abs/1608.00771).

## Misc-2016 [**^**](#contents)

* https://data.gov.ru/sites/default/files/documents/315354748-applying-blockchain-technology-in-global-data-infrastructure.pdf '16

* http://allcoinsnews.com/2016/04/11/chain-mitsubishi-ufj-start-blockchain-proof-of-concept-for-promissory-notes/

* [Anonymous Identities for Permissioned Blockchains](https://petertodd.org/assets/2016-04-21/MIT-ChainAnchor-DRAFT.pdf)

https://cdn.discordapp.com/attachments/479362197835743233/497710026006200320/Smart_Contracts_12_Use_Cases_for_Business_Beyond.pdf


## 2017 [**^**](#contents)

https://entethalliance.org/enterprise-ethereum-alliance-going-strong/

https://entethalliance.org/wp-content/uploads/2017/02/EEA.pdfFeb 


## 2018 [**^**](#contents)

* https://www.theblockcrypto.com/2018/12/12/mapping-out-enterprise-blockchain/
 