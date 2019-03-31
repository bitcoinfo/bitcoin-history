---
layout: single
title: Practical Crypto
description: "Asymmetric Encryption: Phil Zimmerman, PGP and Bitcoin Signatures, BitcoinTalk Escrow, DeepDotWeb, SSL, Various Apps and Resourses."
image: https://i.imgur.com/swEAkJm.png
hide_description: true
sidebar:
  nav: "infonav"
share: true
toc: true
---

```
pull-requests-welcome

```

* [freelanceforcoins.com/**Business with Crypto 101—Escrow and Key Signatures**](https://freelanceforcoins.com/article/6-escrow) -infominer


## Phil Zimmerman
* [Why I Wrote PGP -Part of the Original 1991 PGP User's Guide](https://www.philzimmermann.com/EN/essays/WhyIWrotePGP.html)
  >It's personal. It's private. And it's no one's business but yours. You may be planning a political campaign, discussing your taxes, or having a secret romance. Or you may be communicating with a political dissident in a repressive country. Whatever it is, you don't want your private electronic mail (email) or confidential documents read by anyone else. There's nothing wrong with asserting your privacy. Privacy is as apple-pie as the Constitution.
* [https://www.wired.com/1993/02/crypto-rebels/](https://www.wired.com/1993/02/crypto-rebels/)
  [![](https://i.imgur.com/kzOMg4o.png)](https://www.wired.com/1993/02/crypto-rebels/)
* [Crypto Wars, Phil Zimmermann and PGP](https://cryptoanarchy.wiki/events/90s-crypto-wars)
  > Phil Zimmermann was a key player in this period. The PGP software he authored was considered as munitions by the US government and subject to export licenses. The US government at this time was keen to avoid strong crypto falling into the hands of civilians and foreign governments. At this time the US government was also pushing for specialised key-escrowed chips that would perform encryption, but make the plaintext readable to NSA if necessary. This was rightly considered a gross violation of privacy, rights, and a huge security hole by the cypherpunks.
* [Defending the last missing pixels: Phil Zimmermann speaks out on encryption, privacy, and avoiding a surveillance state](https://www.techrepublic.com/article/defending-the-last-missing-pixels-phil-zimmermann/)
  >Since writing the PGP encryption software in the 1990s, Phil Zimmermann has been a key figure in the internet privacy debate. With that argument heating up again, his perspective is more relevant than ever.
* [infominer.id/bitcoin-history/before-bitcoin/cypherpunks/](https://infominer.id/bitcoin-history/before-bitcoin/cypherpunks/)
* [Even the Inventor of PGP Doesn’t Use PGP](https://motherboard.vice.com/en_us/article/vvbw9a/even-the-inventor-of-pgp-doesnt-use-pgp)

## PGP for Newbs and Beyond

* [How-To-PGP](https://howtopgp.jugendhackt.de/#/) 
  >With this interactiv instruction we want to explain you, how to encrypt your e-mails with PGP to protect your communication and help stopping mass surveillance.
* [EMAIL SELF-DEFENSE](https://emailselfdefense.fsf.org/en) - "Learn GnuPG in 30 Minutes"
  > ![](https://i.imgur.com/danqZLd.png)
* [How To Use GPG to Encrypt and Sign Messages](https://www.digitalocean.com/community/tutorials/how-to-use-gpg-to-encrypt-and-sign-messages)
* [Quick'n easy gpg cheatsheet](http://irtfweb.ifa.hawaii.edu/~lockhart/gpg/)
* [GPG Quickstart Guide 🔒](https://medium.com/@acparas/gpg-quickstart-guide-d01f005ca99)
* [GPG Tutorial and PGP Public Key for ∀lan ∃liasen](https://futureboy.us/pgp.html)
* [GnuPG for Daily Use (a Mini How-To...)](http://moser-isi.ethz.ch/gpg.html)
* [Configuring Yubikeys, GPG, and Keybase](https://ttmm.io/tech/yubikey/)

### SSH 

Another form of public key encryption, allows you to remotely connect to a server, without typing in your user\name password. 

* <a href="https://help.github.com/en/articles/connecting-to-github-with-ssh" target="_blank">Connecting to GitHub with SSH</a>
* <a href="https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent" target="_blank">Generating a new SSH key and adding it to the SSH agent</a>
* <a href="https://help.github.com/en/enterprise/2.15/user/articles/adding-a-new-ssh-key-to-your-github-account" target="_blank">Adding a new SSH key to your GitHub Account</a>
* <a href="https://medium.freecodecamp.org/manage-multiple-github-accounts-the-ssh-way-2dadc30ccaca" target="_blank">How to manage multiple GitHub accounts on a single machine with SSH keys</a>

Signing Commits
* [managing-commit-signature-verification](https://help.github.com/en/articles/managing-commit-signature-verification)

## Protonmail 

Has built in support for PGP for your e-mails... but doesn't make it super easy to verify messages from outside.
* [https://protonmail.com/support/knowledge-base/how-to-use-pgp/](https://protonmail.com/support/knowledge-base/how-to-use-pgp/)

## Verifying PGP Signatures

* [HOW TO VERIFY YOUR DOWNLOADED FILES ARE AUTHENTIC](https://www.deepdotweb.com/jolly-rogers-security-guide-for-beginners/how-to-verify-your-downloaded-files-are-authentic/)
* [VERIFYING SIGNED MESSAGES WITH SIGNATURES AND SIGNING YOUR OWN MESSAGES](https://www.deepdotweb.com/jolly-rogers-security-guide-for-beginners/verifying-signed-messages-with-signatures-and-signing-your-own-messages/)

```
gpg --import singing_key.pub
gpg --verify signed_file.sig
```
### Bitcoin and Ethereum Signatures

* [How do digital signatures in Bitcoin work?](https://www.cryptocompare.com/wallets/guides/how-do-digital-signatures-in-bitcoin-work/)
* [Signing a message from your Ethereum wallet with MyEtherWallet](https://medium.com/@vinczhain/signing-a-message-from-your-ethereum-wallet-with-myetherwallet-cfef7acd6f6d)


### Keybase
![](https://i.imgur.com/YJAJSU6.png)
* [https://keybase.io/](https://keybase.io/)
  >Keybase is a new and free security app for mobile phones and computers. For the geeks among us: it's open source and powered by public-key cryptography.<br>
  >
  >Keybase is for anyone. Imagine a Slack for the whole world, except end-to-end encrypted across all your devices. Or a Team Dropbox where the server can't leak your files or be hacked.
* [Keybase - PGP Encryption made Easy](https://www.andreagrandi.it/2017/10/21/keybase-pgp-encryption-made-easy/)
* [https://keybase.io/docs/command_line](https://keybase.io/docs/command_line)

## deepdotweb

* [About DeepDotWeb](https://www.deepdotweb.com/about-deepdotweb/)

>We established DeepDotWeb in the wake of our friend being arrested by local authorities, for buying drugs from the original Silk Road marketplace. Our aim is make information about dark net markets accessible to everyone, as well as making the dark net safer by reporting on security risks, scams and operations conducted by law enforcement. 

* [Jolly Roger’s Security Guide for Beginners](https://www.deepdotweb.com/jolly-rogers-security-guide-for-beginners/)
  * [PGP, TAILS, VIRTUAL BOX](https://www.deepdotweb.com/jolly-rogers-security-guide-for-beginners/pgp-tails-virtual-box/)
  * [PGP CONTINUED](http://www.deepdotweb.com/jolly-rogers-security-guide-for-beginners/pgp-continued/)
  * [OBTAINING, SENDING AND RECEIVING BITCOINS ANONYMOUSLY](https://www.deepdotweb.com/jolly-rogers-security-guide-for-beginners/obtaining-sending-and-receiving-bitcoins-anonymously/)
  * [PGP/GPG Email Addresses](https://www.deepdotweb.com/jolly-rogers-security-guide-for-beginners/pgpgpg-email-addresses/)
* [PGP Tutorial For Newbs (GPA - Gpg4Win)](https://www.deepdotweb.com/2013/11/11/pgp-tutorial-for-newbs-gpg4win/)
* [PGP Tutorial For Newbs (Kleopatra - Gpg4Win)](https://www.deepdotweb.com/2015/02/21/pgp-tutorial-for-windows-kleopatra-gpg4win/)
* [PGP Tutorial For Newbs Gpg4usb](https://www.deepdotweb.com/2015/06/21/pgp-tutorial-for-newbs-gpg4usb/)
* [Basic Guide to PGP On Linux](https://www.deepdotweb.com/2015/02/17/basic-guide-pgp-linux/)
* [PGP Tutorial for OSX](http://www.deepdotweb.com/2015/02/20/pgp-tutorial-os-x/)
* [PGP Tutorial for TAILS](https://www.deepdotweb.com/2017/10/22/basic-guide-pgp-tails/)

## Escrow Services

Escrow Agents are impartial and trusted intermediaries who hold custody of buyer's funds until pre-defined conditions are met. They allow parties who don't know or trust each-other to engage in commerce, online.

* [Bitrated.com](https://www.bitrated.com/) 
  >Using multi-signature ensures that the trust agent never has full control over the funds and cannot take them to himself. In addition, when everything goes well, the funds can be released with no intervention by the trust agent.

```
 Launched in 2013, Bitrated was the first multi-signature application ever released to the public. Bitrated is operated from Israel and was founded by Nadav Ivgi, a software developer and a long time Bitcoin enthusiast.
```

* [jobs4btc-escrow.appspot.com](http://jobs4btc-escrow.appspot.com/)

>Traffic on the Jobs4Bitcoins subreddit is picking up, and with it, the number of transactions with anonymous strangers around the internet. One thing that is sorely needed is a simple, trusted escrow system through which to have secure trades of work for bitcoin.

>Commissioned by the admin of the subreddit, /u/matthew_boyd, this app attempts to fill that hole, by providing the service of trusted escrow for a small fee.

>When some work is uploaded, a community-trusted programmer will check through it, to make sure that the project has been successfully completed.


### BitcoinTalk Escrow

These seem to be the currently active bitcointalk threads.
	
* Financisto: [⛓LIST⛓ BitcoinTalk's Escrow Providers: Ranking & Blacklist ☠ Avoid Scammers ☠](https://bitcointalk.org/index.php?topic=276897.0;all) - **(Started `13 — Updated 9/18)**
  ![](https://image.ibb.co/fbhMLU/escrow.png) 
* hedgy73: [Recommended bitcointalk escrow services](https://bitcointalk.org/index.php?topic=2439910.0) - **(Started 11/17 — Updated 7/18)**
![](https://i.imgur.com/EvuQwxN.png)
* [Escrow for anything via discord by Dream (fpga channel mod)
March 03, 2019](https://bitcointalk.org/index.php?topic=5116510.0)
![](https://i.imgur.com/DvuqyGh.png)

## Apps

* [henryboldi/felony](https://github.com/henryboldi/felony)
* [romanz/trezor-agent](https://github.com/romanz/trezor-agent)
* [mapmeld/profanity-pgp](https://github.com/mapmeld/profanity-pgp)
* [jedisct1/minisign](https://github.com/jedisct1/minisign)
* [encrypt.to](https://encrypt.to/)
* [metachat.app](https://metachat.app/)
* [Steven-Ireland/ethmail.tech](https://github.com/Steven-Ireland/ethmail.tech) - PGP\Ethereum Powered Distributed E-mail
* [mailbox_with_mail YAM (short for 'Yet Another Mailer')](https://github.com/jens-maus/yam)
* [nurupo/paper-store](https://github.com/nurupo/paper-store) - Cold store small files on paper as QR codes -- PGP keys, Bitcoin keys, Tox keys or any other small files in general.
* [mozilla/sops](https://github.com/mozilla/sops) - Secrets management stinks, use some sops!

## Resources
* [CyPurr-Collective/cryptoparty-presentation](https://github.com/CyPurr-Collective/cryptoparty-presentation)
* [modernpgp.github.io/about/](https://modernpgp.github.io/about/)
* [Documentation and Examples](https://github.com/jonathancross/jc-docs)
* [ModernPGP/icons](https://github.com/ModernPGP/icons)
* [EMAIL SELF-DEFENSE](https://emailselfdefense.fsf.org/en) - "Learn GnuPG in 30 Minutes"
  >In addition to using encryption, standing up to surveillance requires fighting politically for a reduction in the amount of data collected on us, but the essential first step is to protect yourself and make surveillance of your communication as difficult as possible. This guide helps you do that. It is designed for beginners, but if you already know the basics of GnuPG or are an experienced free software user, you'll enjoy the advanced tips and the guide to teaching your friends.
  ![](https://static.fsf.org/nosvn/enc-dev0/img/en/full-infographic.png)
