# Bitcoin History Reference — Key Figures

A standalone public reference on key figures in Bitcoin history.
Scope begins with intellectual precursors to Bitcoin (cypherpunk era and earlier)
and extends through the present.

**255 entries — last updated 2026-07-08**

**Entry fields:**
- **Tier:** 1 = Foundational | 2 = Builders | 3 = Catalysts
- **Role:** Primary function in Bitcoin's story
- **Active:** Era of Bitcoin-relevant activity
- [Prose — neutral, factual, sourced]
- **Sources:** Books, papers, articles for research

---

## TIER 1 — FOUNDATIONAL
*The people whose ideas made Bitcoin possible or whose early work defined it.*

---

## Friedrich Hayek (1899–1992)
**Tier:** 1
**Role:** Economist / Intellectual Precursor
**Active:** 1940s–1976 (Bitcoin-relevant)

Austrian economist whose 1976 book *The Denationalisation of Money* argued that competing private currencies would outperform government monopoly money and that central banks lack the knowledge to set monetary policy rationally. Hayek's work predates Bitcoin by more than three decades and is cited by Bitcoin writers including Saifedean Ammous as an intellectual antecedent to Bitcoin's design.

**Sources:**
- *The Denationalisation of Money* (1976) — F.A. Hayek
- *The Road to Serfdom* (1944) — F.A. Hayek
- *The Bitcoin Standard* — Saifedean Ammous (extensive Hayek treatment)

---

## David Chaum (1955–present)
**Tier:** 1
**Role:** Cryptographer / Digital Cash Pioneer
**Active:** 1980s–1990s

American cryptographer who invented blind signatures (1982) and built DigiCash, the first working system for private cryptographic digital payments. Chaum's blind signature scheme allowed a bank to sign a digital token without learning its contents, enabling anonymous electronic cash. DigiCash operated through the 1990s before filing for bankruptcy in 1998. Satoshi's whitepaper addresses the same double-spend problem Chaum solved, but without a central trusted party — a distinction Satoshi draws explicitly in the paper's opening section.

**Sources:**
- "Blind Signatures for Untraceable Payments" (1982) — Chaum paper
- *The Genesis Book* — Aaron van Wirdum, Ch. 1–2
- "Security Without Identification" (1985) — Chaum paper

---

## Timothy C. May (1951–2018)
**Tier:** 1
**Role:** Cryptographer / Cypherpunk Founder / Ideologist
**Active:** 1988–2000s

American cryptographer and Intel engineer who authored the *Crypto Anarchist Manifesto* (1988) and co-founded the Cypherpunks mailing list (1992) with Eric Hughes and John Gilmore. His manifesto, distributed at a hackers conference in 1988, argued that public-key cryptography would enable anonymous transactions and undermine state surveillance. The mailing list he co-founded became the primary forum for cryptographic privacy research in the 1990s; b-money (Wei Dai), Hashcash (Adam Back), and RPOW (Hal Finney) — all cited or echoed in Bitcoin's design — were announced or discussed there.

**Sources:**
- *Crypto Anarchist Manifesto* (1988) — Timothy May
- *The Cyphernomicon* (1994) — Timothy May (online)
- *This Machine Kills Secrets* — Andy Greenberg

---

## Eric Hughes (1958–present)
**Tier:** 1
**Role:** Mathematician / Cypherpunk Co-Founder
**Active:** 1992–late 1990s

American mathematician who co-founded the Cypherpunks mailing list (1992) with Timothy May and John Gilmore, and authored *A Cypherpunk's Manifesto* (1993). The manifesto articulated the principle that privacy requires anonymous transaction systems built with cryptography, not policy. The mailing list Hughes helped create was the primary forum where cryptographic privacy tools were developed and distributed throughout the 1990s, including PGP, Hashcash, and b-money.

**Sources:**
- *A Cypherpunk's Manifesto* (1993) — Eric Hughes (online)
- *The Genesis Book* — Aaron van Wirdum

---

## John Gilmore (1955–present)
**Tier:** 1
**Role:** Technologist / Cypherpunk Co-Founder / Civil Libertarian
**Active:** 1992–2000s

American technologist and civil libertarian who co-founded the Cypherpunks mailing list (1992), hosted the first cypherpunk meeting at his home, and co-founded the Electronic Frontier Foundation (EFF, 1990) with Mitch Kapor and John Perry Barlow. The EFF took the lead legal role in the encryption export battles of the 1990s, including Bernstein v. United States (9th Circuit, 1999), which established that cryptographic source code is protected speech under the First Amendment. Gilmore is also known for his maxim: "The Net interprets censorship as damage and routes around it."

**Sources:**
- EFF founding documents (eff.org)
- *This Machine Kills Secrets* — Andy Greenberg
- *The Genesis Book* — Aaron van Wirdum

---

## Phil Zimmermann (1954–present)
**Tier:** 1
**Role:** Software Developer / Privacy Activist
**Active:** 1991–present

American software developer who created PGP (Pretty Good Privacy) in 1991, the first widely used public-key encryption tool available to civilians. Zimmermann released PGP freely over the internet; when a third party posted it to Usenet and it reached foreign users, the U.S. Customs Service opened a criminal investigation under the Arms Export Control Act, which classified strong encryption as a munition. The investigation ran from 1993 to 1996. Zimmermann's legal response included publishing the full PGP source code as a physical book, exploiting the First Amendment protection for printed matter that did not extend to software exports. The government dropped the case in January 1996. The episode is a primary event in the Crypto Wars (see separate entry) and established legal precedent for encryption as protected speech.

**Sources:**
- *PGP: Pretty Good Privacy* (1994) — Simson Garfinkel
- Zimmermann's PGP documentation (mit.edu)
- U.S. Customs Service investigation records (1993–1996)
- PGP source code book publication documentation
- *The Genesis Book* — Aaron van Wirdum
- *This Machine Kills Secrets* — Andy Greenberg

---

## The Crypto Wars — The Battle for Civilian Encryption (1991–2000)
**Tier:** 1
**Role:** Legal & Political Watershed / Cypherpunk Victory
**Active:** 1991–2000

A decade-long legal and political conflict (1991–2000) between the U.S. government, which classified strong encryption as a munition under export control law, and cypherpunks, civil liberties organizations, and academics who contested that classification. The key events: the PGP criminal investigation (1993–1996, see Phil Zimmermann entry), the NSA Clipper Chip proposal (a mandatory government backdoor in all encryption hardware, proposed 1993, defeated after public opposition), and Bernstein v. United States (1995–1999), in which the Ninth Circuit ruled that cryptographic source code is protected speech under the First Amendment. U.S. encryption export controls were substantially relaxed between 1999 and 2000. Bitcoin's public-key cryptography — used for addresses, transaction signatures, and Lightning channels — is freely distributable under the legal framework that resulted from these cases.

**Sources:**
- Bernstein v. United States (9th Circuit, 1999) — landmark encryption-as-speech ruling
- NSA Clipper Chip proposal and defeat (1993–1994)
- EFF Crypto Wars documentation (eff.org)
- *This Machine Kills Secrets* — Andy Greenberg
- *The Genesis Book* — Aaron van Wirdum
- PGP investigation records (cross-reference: Phil Zimmermann entry)

---

## Claus-Peter Schnorr (1943–present)
**Tier:** 1
**Role:** Mathematician / Schnorr Signature Inventor
**Active:** 1989–present (Bitcoin-relevant)

German mathematician who invented Schnorr signatures in 1989 and patented them in 1990 (U.S. Patent 4,995,082). Schnorr signatures are simpler and more efficient than RSA or ECDSA and support native multi-party signing. Because the patent was active when Satoshi designed Bitcoin, Satoshi used ECDSA instead. The Schnorr patent expired in February 2008 — the same year Satoshi published the whitepaper. Bitcoin did not adopt Schnorr signatures until BIP340, activated as part of Taproot in November 2021. Schnorr had no connection to Bitcoin; his patent's timing shaped Bitcoin's cryptographic architecture indirectly.

**Sources:**
- U.S. Patent 4,995,082 — Claus-Peter Schnorr (1990, expired 2008)
- BIP340 — Wuille, Nick, Ruffing (Schnorr for Bitcoin)
- Schnorr's academic papers on digital signatures

---

## Whitfield Diffie (1944–present) & Martin Hellman (1945–present)
**Tier:** 1
**Role:** Cryptographers
**Active:** 1976

American cryptographers who published "New Directions in Cryptography" (1976), establishing the theoretical foundation for public-key cryptography and describing the Diffie-Hellman key exchange. Their paper introduced the concept of asymmetric key pairs — a public key for encryption, a private key for decryption — which underlies every digital signature scheme in use today, including ECDSA, the algorithm Bitcoin uses for transaction authorization. They received the Turing Award in 2015.

**Sources:**
- "New Directions in Cryptography" (1976) — Diffie & Hellman
- *The Code Book* — Simon Singh
- Turing Award lecture (2015)

---

## Adam Back (1970–present)
**Tier:** 1
**Role:** Cryptographer / Developer / CEO Blockstream
**Active:** 1997–present

British cryptographer who invented Hashcash (1997), a proof-of-work system originally designed to reduce email spam by requiring senders to perform a small computational task. Satoshi cited Hashcash directly in the Bitcoin whitepaper as the basis for Bitcoin's mining mechanism. Back is documented as one of the first people Satoshi contacted before the whitepaper's publication. He co-founded Blockstream in 2014 and serves as its CEO; Blockstream has employed several Bitcoin Core developers and funded protocol research including Confidential Transactions, the Liquid sidechain, and work toward Simplicity.

**Sources:**
- *Hashcash — A Denial of Service Counter-Measure* (2002) — Adam Back
- Bitcoin whitepaper citations
- *The Genesis Book* — Aaron van Wirdum

---

## Wei Dai (1975–present)
**Tier:** 1
**Role:** Computer Engineer / Cryptographer
**Active:** 1998–early 2000s

Chinese-American computer engineer who proposed b-money (1998), an electronic cash scheme describing a peer-to-peer network where participants maintain transaction ledgers and consensus is enforced through computational work and economic incentives. B-money was never implemented. Satoshi cited it in the Bitcoin whitepaper alongside Hashcash. The smallest denomination of Ether (0.000000000000000001 ETH) is named "wei" in his honor.

**Sources:**
- b-money proposal (1998) — Wei Dai (weidai.com)
- Bitcoin whitepaper references
- *The Genesis Book* — Aaron van Wirdum

---

## Nick Szabo (1964–present)
**Tier:** 1
**Role:** Computer Scientist / Legal Scholar / Cryptographer
**Active:** 1990s–present

American computer scientist and legal scholar who coined the term "smart contracts" (1994) and proposed Bit Gold (described in a 1998 post, published 2005). Bit Gold proposed chaining proof-of-work solutions into a distributed timestamp ledger to create unforgeable digital scarcity — a structure with close parallels to Bitcoin. It was never implemented. Satoshi did not cite Szabo in the whitepaper. Szabo denies being Satoshi. His smart contracts framework later became foundational to Ethereum. He has written extensively on the history of money and cryptographic property rights at unenumerated.blogspot.com.

**Sources:**
- "Bit Gold" (2005, originally ~1998) — Nick Szabo (unenumerated.blogspot.com)
- "Smart Contracts" (1994) — Nick Szabo
- *The Genesis Book* — Aaron van Wirdum

---

## Hal Finney (1956–2014)
**Tier:** 1
**Role:** Cryptographer / Developer / Early Bitcoin Contributor
**Active:** 1990s–2014

American cryptographer and software developer who was among the first engineers hired by Phil Zimmermann to develop PGP. He created RPOW (Reusable Proofs of Work) in 2004, a system that allowed Hashcash tokens to be reused by passing them through a trusted server — a direct technical precursor to Bitcoin's chain of proof-of-work. He received the first Bitcoin transaction from Satoshi on January 12, 2009, and was among Bitcoin's earliest active developers. Finney was diagnosed with ALS in 2009 and continued contributing to Bitcoin until shortly before his death in 2014. His correspondence with Satoshi and his forum posts are primary sources for Bitcoin's early development period.

**Sources:**
- RPOW announcement (2004) — Hal Finney
- Finney's "Running Bitcoin" tweet (Jan 11, 2009)
- "Dying Outside" — Hal Finney (bitcointalk.org, 2013)
- *The Genesis Book* — Aaron van Wirdum
- PGP development history / Zimmermann interviews

---

## Satoshi Nakamoto (identity unknown)
**Tier:** 1
**Role:** Creator of Bitcoin
**Active:** 2008–2011 (publicly)

Pseudonymous individual or group who published the Bitcoin whitepaper ("Bitcoin: A Peer-to-Peer Electronic Cash System") in October 2008 and launched the Bitcoin network on January 3, 2009, mining the genesis block with the headline "The Times 03/Jan/2009 Chancellor on brink of second bailout for banks" embedded in its coinbase. Satoshi communicated via email and the Bitcointalk forum through 2010 before gradually withdrawing, with the last known communication in April 2011. No individual has been cryptographically verified as Satoshi Nakamoto. The unspent coins associated with Satoshi's early mining — estimated at approximately 1 million BTC — have never moved.

**Sources:**
- *Bitcoin: A Peer-to-Peer Electronic Cash System* (2008) — Satoshi Nakamoto
- Satoshi's emails and forum posts (bitcoin.org, bitcointalk.org archive)
- *The Genesis Book* — Aaron van Wirdum
- *Digital Gold* — Nathaniel Popper

---

## John Perry Barlow (1947–2018)
**Tier:** 1
**Role:** Internet Freedom Advocate / EFF Co-Founder / Cypherpunk Fellow Traveler
**Active:** 1990–2018

American lyricist (Grateful Dead), essayist, and internet freedom advocate who co-founded the Electronic Frontier Foundation (1990) with John Gilmore and Mitch Kapor and authored "A Declaration of the Independence of Cyberspace" (1996). The Declaration, written in Davos in response to the U.S. Communications Decency Act, asserted that governments have no legitimate sovereignty over the internet. Barlow was not a developer or cryptographer; his role was as a writer and public voice in the social and political networks surrounding the cypherpunk movement and the EFF's legal work.

**Sources:**
- "A Declaration of the Independence of Cyberspace" (1996) — John Perry Barlow
- EFF founding documentation (eff.org)
- *This Machine Kills Secrets* — Andy Greenberg

---

## Len Sassaman (1980–2011)
**Tier:** 1
**Role:** Cypherpunk / Cryptographer / Anonymity Researcher
**Active:** 2000s

American cypherpunk and cryptographer who maintained the Mixmaster anonymous remailer network and worked on anonymity and privacy protocols in the early 2000s. He worked at PGP Corporation alongside Hal Finney. He died by suicide in July 2011, two months after Satoshi's last known public communication. Some researchers have proposed Sassaman as a Satoshi candidate based on stylistic and technical parallels; this has not been verified. His death was noted in tributes by Meredith Patterson and others in the cypherpunk community.

**Sources:**
- Sassaman tribute by Meredith Patterson (2011)
- *The Genesis Book* — Aaron van Wirdum
- Dustin Trammell Satoshi research (circumstantial)

---

## TIER 2 — BUILDERS
*Developers, miners, and operators who built Bitcoin from whitepaper to working system.*

---

## James A. Donald (dates unknown)
**Tier:** 2
**Role:** Cryptography Mailing List Member / First Public Critic
**Active:** 2008

Cryptography mailing list participant who sent the first public reply to Satoshi's whitepaper on November 2, 2008. Donald's response raised concerns about scalability: "It doesn't seem to scale to the required size." Satoshi's replies to Donald constitute some of the earliest on-record explanations of Bitcoin's design decisions and are archived at the Satoshi Nakamoto Institute.

**Sources:**
- Cryptography mailing list archive (November 2008)
- *The Genesis Book* — Aaron van Wirdum
- Satoshi Nakamoto Institute email archive

---

## Ray Dillinger (dates unknown)
**Tier:** 2
**Role:** Developer / Pre-Launch Code Reviewer
**Active:** 2008

Developer and cryptography mailing list participant who reviewed Satoshi's Bitcoin code before the network launched in January 2009 — one of the few people documented to have seen the code prior to release. His correspondence with Satoshi, published later at the Satoshi Nakamoto Institute, records specific technical criticisms and Satoshi's responses, including decisions about memory pool handling and network design.

**Sources:**
- Satoshi Nakamoto Institute email archive
- Dillinger's later Bitcointalk posts reflecting on the pre-launch review

---

## NewLibertyStandard (identity unknown)
**Tier:** 2
**Role:** Early Miner / First Exchange Rate Setter
**Active:** 2009

An unidentified early Bitcoin participant who established the first Bitcoin exchange rate in October 2009, setting 1,309.03 BTC per U.S. dollar by dividing the cost of electricity used to mine one bitcoin by the corresponding dollar cost. The exchange rate was posted on the NewLibertyStandard website and constitutes the first documented attempt to assign Bitcoin a monetary value derived from a real-world input cost. The first recorded dollar-denominated Bitcoin transaction followed shortly after. His posts and the exchange rate methodology are archived in early Bitcoin forum records.

**Sources:**
- NewLibertyStandard Bitcointalk posts (2009)
- Bitcoin exchange rate history documentation
- *Digital Gold* — Nathaniel Popper

---

## Ribuck (identity unknown)
**Tier:** 2
**Role:** Early Forum Member / Naming Contributor
**Active:** 2010–2011

An unidentified early Bitcointalk forum member who proposed in 2010–2011 that the smallest unit of Bitcoin (0.00000001 BTC) be named the "satoshi" in honor of Bitcoin's pseudonymous creator. The proposal was adopted by the Bitcoin community and the satoshi became the standard base denomination used in Lightning Network invoices, fee calculations, and Bitcoin accounting more broadly. No further biographical information about Ribuck has been documented.

**Sources:**
- Bitcointalk forum archive (2010–2011)

---

## Theymos / Michael Marquardt (dates unknown)
**Tier:** 2
**Role:** Bitcointalk Forum Administrator
**Active:** 2009–present

The administrator of Bitcointalk and r/Bitcoin, Bitcoin's two largest public discussion forums, serving as their primary moderator for over a decade beginning in 2009. His moderation decisions during the blocksize war (2015–2017) — including the removal of posts supporting larger blocks from r/Bitcoin — are documented in *The Blocksize War* by Jonathan Bier and were publicly contested at the time. Critics argued the removals distorted the public debate; Theymos maintained he was enforcing forum rules. The episode is a documented case study in how forum governance intersected with Bitcoin protocol governance.

**Sources:**
- *The Blocksize War* — Jonathan Bier
- Bitcointalk forum history
- r/Bitcoin moderation controversies (2015–2017)

---

## Dorian Nakamoto (1949–present)
**Tier:** 3
**Role:** Unwilling Public Figure / Misidentified Satoshi
**Active:** 2014 (involuntarily)

A retired Japanese-American physicist and engineer living in California who was publicly identified as Satoshi Nakamoto by Newsweek in a March 2014 cover story by Leah McGrath Goodman. Nakamoto denied the identification, and it was never substantiated. Hal Finney organized a community fundraiser on his behalf following the unwanted attention. The episode is a documented case in Bitcoin media history of a private individual being publicly named as Satoshi on circumstantial grounds, and is frequently cited in discussions of press ethics and the Satoshi identity question.

**Sources:**
- Newsweek "The Face Behind Bitcoin" (March 2014) — Leah McGrath Goodman
- Dorian Nakamoto's denial statements
- Hal Finney fundraising post (Bitcointalk, 2014)

---

## Laszlo Hanyecz (1980–present)
**Tier:** 2
**Role:** Developer / Miner
**Active:** 2009–2010

Hungarian-American developer and early Bitcoin miner who made the first documented real-world commercial Bitcoin transaction on May 22, 2010 — paying 10,000 BTC for two pizzas via a Bitcointalk forum post, fulfilled by a counterparty who ordered from Papa John's. May 22 is observed annually in the Bitcoin community as Bitcoin Pizza Day. Hanyecz was also among the first to mine Bitcoin using graphics processing units (GPUs) rather than CPUs, and shared the method publicly in 2010, a meaningful efficiency improvement during Bitcoin's earliest mining era.

**Sources:**
- Bitcointalk forum post (May 22, 2010) — Laszlo Hanyecz
- *Digital Gold* — Nathaniel Popper
- Bitcoin Pizza Day documentation (bitcoinpizzaday.com)

---

## Martti Malmi (1988–present)
**Tier:** 2
**Role:** Early Bitcoin Developer / Forum Founder
**Active:** 2009–2011 (core era)

Finnish developer who became the second person to contribute code to Bitcoin, working directly with Satoshi Nakamoto beginning in 2009. Known online as "Sirius," Malmi built the original bitcoin.org website and created the first dedicated Bitcoin forum, which Satoshi later moved to what became Bitcointalk. He sold 5,050 BTC for $5.02 in October 2009, one of the earliest documented Bitcoin-to-fiat transactions. His email correspondence with Satoshi, surfaced in the COPA v. Wright litigation (2024), is a primary source for understanding Satoshi's thinking and intentions during Bitcoin's first two years.

**Sources:**
- Malmi's Bitcoin Core contribution history (2009–2011)
- Satoshi Nakamoto email correspondence with Malmi (surfaced in COPA v. Wright, 2024)
- bitcoin.org and Bitcointalk founding documentation
- Early Bitcoin transaction records (October 2009 sale)

---

## Gavin Andresen (1966–present)
**Tier:** 2
**Role:** Developer / Bitcoin Foundation
**Active:** 2010–2016

American developer who became Bitcoin's lead maintainer after Satoshi's gradual withdrawal beginning in 2010. Satoshi transferred the bitcoin.org domain, the network alert key, and access to the Sourceforge code repository to Andresen — the most direct documented transfer of Bitcoin stewardship. Andresen built the Bitcoin faucet (a free Bitcoin distribution site) and founded the Bitcoin Foundation in 2012, which drew criticism for centralizing influence and later faced scrutiny over financial management. His advocacy for larger block sizes aligned him with the big-block faction in the blocksize war, and his 2016 claim that Craig Wright is Satoshi Nakamoto was disputed by Bitcoin Core developers; his commit access was subsequently revoked. His role is documented extensively in *Digital Gold* and *The Blocksize War*.

**Sources:**
- *Digital Gold* — Nathaniel Popper
- *The Blocksize War* — Jonathan Bier
- Bitcoin Core GitHub contribution history
- Bitcoin Foundation founding documentation (2012)

---

## Jeff Garzik (1973–present)
**Tier:** 2
**Role:** Bitcoin Core Developer / Entrepreneur
**Active:** 2010–2017

American developer and one of Bitcoin's earliest prolific Core contributors, with an active commit history beginning in 2010. Garzik later proposed BIP100, a competing block size increase proposal, and co-led the Segwit2x effort (2017), a hard fork attempt backed by a significant segment of the mining and exchange industry that collapsed in November 2017 when key supporters withdrew. Both BIP100 and Segwit2x failed to activate. The Segwit2x collapse is documented in *The Blocksize War* as a case study in how Bitcoin's upgrade governance functions when economic nodes do not support a miner-backed change.

**Sources:**
- *The Blocksize War* — Jonathan Bier
- Bitcoin Core GitHub contribution history
- Segwit2x documentation (2017)

---

## Mike Hearn (1980–present)
**Tier:** 2
**Role:** Bitcoin Core Developer / Google Engineer
**Active:** 2011–2016

British developer and former Google engineer who contributed to Bitcoin from 2011, working on payment channel concepts, SPV verification, and other infrastructure. He resigned from Bitcoin development in January 2016 with a widely read post — "Why Bitcoin's Vision Is Flawed" — that declared the project a failure and contributed to a short-term price decline. Hearn subsequently joined R3, a bank-backed distributed ledger consortium. His contributions and departure are documented in *The Blocksize War* as a reference point in the blocksize conflict.

**Sources:**
- *The Blocksize War* — Jonathan Bier
- "Why Bitcoin's Vision Is Flawed" (2016) — Mike Hearn (Medium)
- Bitcoin Core GitHub contribution history

---

## Pieter Wuille (1988–present)
**Tier:** 2
**Role:** Bitcoin Core Developer
**Active:** 2011–present

Belgian Bitcoin Core developer who has authored or co-authored more Bitcoin Improvement Proposals than any other individual contributor: BIP16 (pay-to-script-hash), BIP32 (hierarchical deterministic wallets), BIP39 (mnemonic seed phrases), BIP141 (SegWit), BIP340 (Schnorr signatures), and BIP341 (Taproot), among others. BIP32 and BIP39 together form the basis of every modern Bitcoin wallet's seed phrase system. He co-founded Blockstream in 2014 and later moved to Chaincode Labs as a researcher. His contributions span more than a decade of active Core development across wallet infrastructure and protocol-level upgrades.

**Sources:**
- GitHub bitcoin/bitcoin contribution history (github.com/sipa)
- BIP index — BIP16, BIP32, BIP39, BIP141, BIP340, BIP341
- Blockstream and Chaincode Labs documentation

---

## Wladimir van der Laan (1986–present)
**Tier:** 2
**Role:** Bitcoin Core Lead Maintainer
**Active:** 2012–2022

Dutch developer who served as Bitcoin Core's lead maintainer from 2012 to 2022, the longest tenure of any maintainer and the longest of Gavin Andresen's successors in that role. The lead maintainer position is a coordination and merge-management function rather than a unilateral protocol authority, but it carries significant influence over what code ships in Core releases. Van der Laan's decade in the role spanned the blocksize war, SegWit activation, the Taproot upgrade, and the early Lightning Network era. He stepped back from the role in 2022.

**Sources:**
- Bitcoin Core GitHub contribution history (github.com/laanwj)
- *The Blocksize War* — Jonathan Bier

---

## Andreas Antonopoulos (1972–present)
**Tier:** 2
**Role:** Educator / Author / Advocate
**Active:** 2012–present

Greek-British technologist and author who authored *Mastering Bitcoin* (2014), a technical reference for developers that has gone through multiple updated editions, and the three-volume *The Internet of Money* series (collected talks). He testified before the Canadian Senate on Bitcoin in 2014, a documented primary source for early Bitcoin policy discussions, and accepted Bitcoin as payment for speaking engagements before widespread merchant adoption. In 2017 he publicly disclosed he had not retained significant Bitcoin savings and the community organized a donation to him, an episode documented in Bitcoin media.

**Sources:**
- *Mastering Bitcoin* (2014, updated editions) — Andreas Antonopoulos
- *The Internet of Money* Vol. 1–3 — Andreas Antonopoulos
- Canadian Senate testimony on Bitcoin (2014)
- Antonopoulos community Bitcoin donation story (2017)
- aantonop.com; YouTube lecture archive

---

## Ralph Merkle (1952–present)
**Tier:** 2
**Role:** Cryptographer
**Active:** 1979 (Bitcoin-relevant)

American cryptographer who invented Merkle trees (1979), the hash-based data structure Bitcoin uses to organize transactions within each block, with the Merkle root recorded in the block header. Bitcoin's use of Merkle trees allows SPV (Simplified Payment Verification) wallets to confirm a transaction's inclusion in a block without downloading the full block. Merkle also independently developed public key cryptography concepts and invented the Merkle-Hellman knapsack encryption scheme. His invention of Merkle trees predates Bitcoin by nearly thirty years; Satoshi applied them directly as Bitcoin's transaction verification structure.

**Sources:**
- "A Digital Signature Based on a Conventional Encryption Function" (1987) — Ralph Merkle
- *The Code Book* — Simon Singh
- Bitcoin whitepaper, Section 7 (Reclaiming Disk Space) — Satoshi Nakamoto

---

## Bisq — Manfred Karrer (founded 2014)
**Tier:** 2
**Role:** Decentralized Bitcoin Exchange
**Active:** 2014–present

Manfred Karrer, an Austrian game designer and developer, founded Bisq (originally named Bitsquare) in 2014 after discovering Bitcoin in 2011 and teaching himself to code to build a peer-to-peer exchange that required no central authority, no identity verification, and no custody of funds. Bisq runs as a desktop application using a distributed network, enabling Bitcoin trades against fiat and other assets without a central operator. In April 2019 Bisq launched a Decentralized Autonomous Organization (DAO) structure governed by BSQ tokens, and in May 2019 Karrer fully relinquished his unique access and privileges, transferring control to the contributor community. Bisq remains one of the longest-running and most philosophically consistent non-custodial Bitcoin exchanges.

**Sources:**
- bisq.network
- Bitcoin Magazine — Bisq DAO launch (2019)
- CoinDesk — Bisq decentralization analysis (2018)

---

## Nicolas Dorier (1986–present)
**Tier:** 2
**Role:** Developer / Open-Source Builder
**Active:** 2017–present

French developer who built BTCPay Server in 2017, a self-hosted, open-source Bitcoin payment processor, in direct response to BitPay's support for the Segwit2x hard fork. Dorier announced the project publicly, stating his intent to build a non-commercial alternative to BitPay's custodial model. BTCPay Server is fee-free, requires no third-party trust, and has been adopted by thousands of merchants and integrated into numerous Bitcoin projects. It is maintained as an open-source community project.

**Sources:**
- BTCPay Server GitHub (github.com/btcpayserver)
- Original tweet/post (2017): "This is lies, my response is to build my own payment processor and you should too"
- BTCPay Server documentation and history (btcpayserver.org)

---

## Pierre Rochard (1989–present)
**Tier:** 2
**Role:** Bitcoin Researcher / Advocate / Analyst
**Active:** 2013–present

American Bitcoin researcher and analyst who co-founded the Satoshi Nakamoto Institute (SNI) in 2013, which maintains an archive of Satoshi's writings, cypherpunk texts, and early forum posts that serves as the primary research library for Bitcoin's intellectual history. He authored "Speculative Attack" (2014) and other essays connecting Bitcoin to the Austrian economics tradition. He later served as VP of Research at Riot Platforms, a publicly traded Bitcoin mining company.

**Sources:**
- Satoshi Nakamoto Institute (nakamotoinstitute.org)
- "Speculative Attack" (2014) — Pierre Rochard
- Riot Platforms research publications

---

## Bitstein / Michael Goldstein (dates unknown)
**Tier:** 2
**Role:** Bitcoin Philosopher / SNI Co-Founder
**Active:** 2013–present

Michael Goldstein, writing under the pseudonym Bitstein, co-founded the Satoshi Nakamoto Institute (SNI) in 2013 alongside Pierre Rochard. SNI maintains the canonical archive of Satoshi's writings, cypherpunk primary texts, and early Bitcoin forum posts. Goldstein authored "Everyone's a Scammer" (2014), an essay arguing that Bitcoin's monetary properties make all competing systems structurally adversarial to holders, and has written on Bitcoin from a Misesian and Rothbardian economic framework. He served as president of SNI and has been a consistent voice for Bitcoin maximalism as an intellectually grounded position.

**Sources:**
- Satoshi Nakamoto Institute (nakamotoinstitute.org)
- "Everyone's a Scammer" — Michael Goldstein (2014)
- SNI publications

---

## Luke Dashjr (1985–present)
**Tier:** 2
**Role:** Bitcoin Core Developer / Protocol Conservative
**Active:** 2011–present

American developer who has contributed to Bitcoin Core since 2011 and created BFGMiner, an early and widely used mining software. He has served as a long-running maintainer and has been a consistent dissenting voice against protocol changes he views as departures from Bitcoin's original design, including opposition to Taproot. In December 2022, he publicly reported that his personal Bitcoin node was compromised and a substantial amount of BTC stolen, a documented case of operational security failure covered in Bitcoin media. In December 2023 he co-founded Ocean, a decentralized mining pool designed to return block template construction to individual miners (cross-reference: Bitcoin Mechanic entry).

**Sources:**
- Bitcoin Core GitHub contribution history
- BFGMiner documentation
- *The Blocksize War* — Jonathan Bier

---

## Robin Linus (dates unknown)
**Tier:** 2
**Role:** Bitcoin Protocol Researcher / Developer
**Active:** 2016–present

A Bitcoin protocol researcher and Ph.D. candidate at Stanford University focused on Bitcoin scalability, privacy, and usability. He published the BitVM whitepaper in October 2023, proposing a framework to enable arbitrary computation on Bitcoin via fraud proofs without requiring a soft fork — a significant conceptual expansion of what is possible within Bitcoin's existing script constraints. He subsequently published BitVM2, a permissionless single-step fraud proof variant. Linus is a core contributor at ZeroSync Association, a Swiss non-profit developing STARK proofs to verify Bitcoin's chain state, and has also proposed zkCoins, a client-side validation payment system with privacy and scalability properties. He created SnapDrop, a local network file-sharing application with millions of documented monthly users, before focusing on Bitcoin research.

**Sources:**
- "BitVM: Compute Anything on Bitcoin" — Robin Linus (October 2023)
- BitVM2 paper (2024)
- ZeroSync documentation
- robinlinus.com

---

## Supertestnet (pseudonym, identity unknown)
**Tier:** 2
**Role:** Bitcoin Developer / Protocol Experimenter
**Active:** 2021–present

A pseudonymous freelance Bitcoin developer active in the Austin Bitcoin community, known for rapidly prototyping experimental Bitcoin and Lightning Network concepts. Supertestnet contributed an early proof-of-concept implementation of BitVM (tapleaf-circuits), a framework proposed by Robin Linus enabling Bitcoin-based computation via fraud proofs without a soft fork. Additional projects include Hedgehog, a protocol for improved Layer 2 Bitcoin payments; Zaplocker, a non-custodial Lightning address server; and Superstore, a Bitcoin web commerce tool using whisper addresses for privacy.

**Sources:**
- supertestnet.org
- GitHub (github.com/supertestnet)
- Austin Bitcoin Developers community
- Public interviews and writings

---

## Bitcoin Mechanic (pseudonym, identity unknown)
**Tier:** 2
**Role:** Mining Pool Co-Founder / Decentralization Advocate
**Active:** 2020s–present

A pseudonymous Bitcoin mining advocate and co-founder of Ocean, a Bitcoin mining pool launched in December 2023 alongside Luke Dashjr. Ocean was designed as a decentralized mining pool that returns block template construction to individual miners rather than the pool operator — a direct response to concerns that large centralized pools had accumulated too much control over transaction selection. Ocean uses the TIDES (Transparent Index of Distinct Extended Shares) payout system and publishes full transparency on transaction filtering policies. Bitcoin Mechanic has been a vocal advocate for miner decentralization and has written and spoken extensively on the risks of pool centralization to Bitcoin's censorship resistance.

**Sources:**
- Ocean pool documentation (ocean.xyz)
- Ocean launch announcement (December 2023)
- Bitcoin Mechanic public writings and interviews

---

## Peter Todd (1988–present)
**Tier:** 2
**Role:** Bitcoin Core Developer / Researcher
**Active:** 2012–present

Canadian Bitcoin Core developer who contributed foundational research on replace-by-fee (RBF), fraud proofs, and client-side validation from 2012 onward. His RBF work changed how Bitcoin nodes handle unconfirmed transactions and remains a subject of ongoing discussion in the developer community. He has published extensively on Bitcoin's long-term security model and scalability at petertodd.org. In 2024, HBO's Bitcoin documentary *Money Electric* named him as a Satoshi Nakamoto candidate without his consent; he denied the claim and the suggestion was not accepted by the broader Bitcoin developer community.

**Sources:**
- Peter Todd's research blog (petertodd.org)
- Bitcoin Core GitHub contribution history
- HBO *Money Electric* documentary (2024)

---

## Jameson Lopp (1983–present)
**Tier:** 2
**Role:** Security Engineer / Bitcoin Educator / Self-Custody Advocate
**Active:** 2013–present

American security engineer who built statoshi.info, a Bitcoin node statistics dashboard, and co-founded Casa, a multisig self-custody platform. He has written extensively on Bitcoin self-custody, node operation, and personal security. His home was swatted in 2017; he subsequently adopted documented privacy practices and published his approach publicly. Casa's multisig model, which Lopp helped develop, is a reference implementation for consumer Bitcoin custody and has been influential in how the industry approaches key management and Bitcoin inheritance.

**Sources:**
- Lopp's blog (blog.lopp.net)
- Casa documentation and whitepapers
- statoshi.info

---

## Gloria Zhao (1999–present)
**Tier:** 2
**Role:** Bitcoin Core Developer / Maintainer
**Active:** 2020–present

American Bitcoin Core developer who became a maintainer in 2022, focusing on mempool policy and package relay — a mechanism that allows related transactions to be evaluated together for fee purposes, which is foundational infrastructure for Lightning Network efficiency. She joined Bitcoin Core development through a Chaincode Labs residency and later received a Brink fellowship. Her work on transaction relay policy is among the most active areas of Bitcoin protocol development as of mid-2025.

**Sources:**
- Bitcoin Core GitHub (github.com/glozow)
- Package relay BIP documentation
- Brink.dev fellowship profile

---

## Gregory Maxwell (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Cryptographer / Protocol Designer
**Active:** 2011–present

Bitcoin Core developer and cryptographer who has been active since 2011 and served as CTO of Blockstream. Maxwell proposed or co-developed CoinJoin (the foundational Bitcoin privacy mixing technique, Bitcointalk 2013), Confidential Transactions, Schnorr signatures for Bitcoin, MAST (Merkelized Abstract Syntax Trees), and Taproot (originally proposed on the Bitcoin-dev mailing list in 2018, activated 2021). He co-authored the MuSig multi-party Schnorr signing scheme (2018). His mailing list posts and forum contributions from 2011 onward are primary source material for Bitcoin's technical evolution, and his work on cryptographic protocol design has been incorporated into Bitcoin's current scripting and privacy infrastructure.

**Sources:**
- Bitcoin Core GitHub (github.com/gmaxwell)
- CoinJoin proposal — Gregory Maxwell (Bitcointalk, 2013)
- Taproot proposal — Gregory Maxwell (Bitcoin-dev mailing list, 2018)
- Blockstream CTO documentation
- Bitcoin-dev mailing list archive (Maxwell contributions)

---

## Chaincode Labs (founded 2014)
**Tier:** 2
**Role:** Bitcoin Developer Research & Education Organization
**Active:** 2014–present

New York-based research organization founded in 2014 by Alex Morcos, Matt Corallo, and Suhas Daftuar, dedicated to Bitcoin Core development and developer education. Chaincode has employed or funded a significant share of active Bitcoin Core contributors since its founding. Its Residency program — an intensive in-person seminar — has trained developers who went on to contribute to Core, Lightning, and related projects, including Gloria Zhao, Amiti Uttarwar, and Carla Kirk-Cohen. Chaincode co-organized the Scaling Bitcoin workshops and has been a consistent hub for Bitcoin protocol research.

**Sources:**
- Chaincode Labs documentation (chaincode.com)
- Chaincode Residency program alumni and curriculum
- Cross-references: Matt Corallo, Suhas Daftuar, Gloria Zhao entries

---

## Brink (founded 2020)
**Tier:** 2
**Role:** Bitcoin Developer Funding Organization
**Active:** 2020–present

Bitcoin developer funding non-profit co-founded in 2020 by John Newbery and Mike Schmidt, providing salary-equivalent grants and fellowships to open-source Bitcoin Core contributors. Brink fellows and grant recipients have included Core contributors across wallet, p2p networking, cryptography, and testing domains. Brink also runs the Bitcoin Core PR Review Club, a weekly online session where contributors work through open pull requests — a documented onboarding pathway for new Core developers. Together with Chaincode Labs and Spiral, Brink is part of the non-commercial Bitcoin developer funding ecosystem that has grown substantially since 2019.

**Sources:**
- Brink documentation (brink.dev)
- Brink grant and fellowship recipients
- Cross-references: John Newbery, Gloria Zhao entries

---

## Spiral — Square Crypto / Block (founded 2019)
**Tier:** 2
**Role:** Bitcoin Developer Funding Organization / Lightning Infrastructure
**Active:** 2019–present

Bitcoin-focused developer funding and product organization within Block (Jack Dorsey's company), launched as Square Crypto in 2019 and later renamed Spiral. It funds individual Bitcoin and Lightning developers through grants, built the Lightning Development Kit (LDK) — an embeddable Lightning library adopted by Cash App, Strike, and other Lightning products — and helped establish the Bitcoin Design Community and bitcoin.design, which produced open-source design resources for Bitcoin application developers. Spiral's grant recipients have included contributors across Bitcoin Core, Lightning, and Bitcoin privacy tools.

**Sources:**
- Spiral documentation (spiral.xyz)
- LDK (Lightning Development Kit) documentation
- Bitcoin Design Community (bitcoin.design)
- Spiral grant recipients
- Cross-references: Jack Dorsey, Matt Corallo (LDK) entries

---

## OpenSats (founded 2021)
**Tier:** 2
**Role:** Bitcoin & Open Source Developer Funding Organization
**Active:** 2021–present

501(c)(3) nonprofit co-founded in 2021 by Matt Odell and Ben Price to fund contributors to Bitcoin, Nostr, and related free and open-source projects. OpenSats operates with a nine-person board and does not take a cut from donations to fund its own operations. Its treasury is Bitcoin-first — all donations, whether received in bitcoin or fiat, are held in bitcoin, with fiat donations promptly converted. Grant recipients have included Bitcoin Core contributors, hardware wallet developers, privacy researchers, ecash projects, Lightning developers, educators, and translators across more than 32 countries. As of mid-2025, OpenSats had allocated over $21 million to 252 grantees and distributed approximately $1 million per month. Jack Dorsey's StartSmall foundation contributed $21 million to OpenSats in May 2024, following earlier donations. Board members have included Odell, Price, Lisa Neigut, and Elaine Ou. OpenSats expanded its scope to include Nostr development grants, reflecting the overlap between the Bitcoin and Nostr developer communities.

**Sources:**
- opensats.org — grant announcements and fund documentation
- OpenSats About page (opensats.org/about)
- Bitcoin Nonprofit Directory — OpenSats case study
- Philanthropy News Digest — Jack Dorsey / OpenSats $21M donation (2024)
- Stephan Livera Podcast SLP278 — Matt Odell & Ben Price on OpenSats

---

## Matt Corallo (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Infrastructure Builder
**Active:** 2011–present

Long-tenured Bitcoin Core contributor who has been active since 2011. Corallo built the FIBRE (Fast Internet Bitcoin Relay Engine) network, a low-latency block relay system that reduced orphan block rates and structural mining pool advantages arising from block propagation latency. He co-founded Chaincode Labs in 2014 and later focused on Lightning Network development at Spiral/Block, where he led development of the Lightning Development Kit (LDK), an embeddable Lightning library adopted by Cash App, Strike, and other products. His contributions span p2p networking, consensus code, mining infrastructure, and Lightning protocol development.

**Sources:**
- Bitcoin Core GitHub (github.com/TheBlueMatt)
- FIBRE documentation (bitcoinfibre.org)
- Chaincode Labs documentation (chaincode.com)
- LDK (Lightning Development Kit) documentation — Spiral/Block

---

## Suhas Daftuar (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Chaincode Labs Researcher
**Active:** 2014–present

Senior Bitcoin Core contributor and co-founder of Chaincode Labs who specializes in mempool policy, transaction relay, consensus code, and network-layer development. Daftuar has authored and reviewed critical p2p and consensus code since 2014. His work on mempool improvements and transaction relay policy is foundational to how the Bitcoin network evaluates and propagates unconfirmed transactions. Chaincode Labs, which he co-founded, has become a primary institution for training and funding the next generation of Bitcoin Core developers.

**Sources:**
- Bitcoin Core GitHub (github.com/sdaftuar)
- Chaincode Labs documentation
- Bitcoin-dev mailing list contributions

---

## John Newbery (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Developer Education Pioneer
**Active:** 2016–2022

Bitcoin Core contributor who focused on p2p networking and transaction relay from 2016, and who founded the Bitcoin Core PR Review Club — a weekly online session where contributors work through open pull requests together, which became a primary onboarding pathway for new Core developers. He also co-founded Brink, a Bitcoin developer funding nonprofit, in 2020. Newbery stepped back from active contribution in 2022.

**Sources:**
- Bitcoin Core PR Review Club (bitcoincore.reviews)
- Brink documentation (brink.dev)
- Bitcoin Core GitHub (github.com/jnewbery)

---

## Marco Falke (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Maintainer / Test Infrastructure
**Active:** 2014–present

One of Bitcoin Core's longest-serving maintainers, primarily responsible for the project's test framework, continuous integration infrastructure, and code quality processes since 2014. Falke authored and maintained the functional test suite that allows Core contributors to verify that changes do not break existing behavior — infrastructure that is foundational to the reliability of a codebase managing significant financial value.

**Sources:**
- Bitcoin Core GitHub (github.com/MarcoFalke)
- Bitcoin Core test framework documentation

---

## Sjors Provoost (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Author / Educator
**Active:** 2017–present

Dutch Bitcoin Core contributor who has been active since 2017, focusing on hardware wallet integration, pruning, and general node improvements. He authored *Bitcoin: A Work in Progress* (btcwip.com), a technical book documenting Bitcoin's ongoing development from the perspective of an active contributor, covering soft forks, p2p improvements, and the process of Bitcoin development itself. He also hosts a podcast on Bitcoin development topics.

**Sources:**
- *Bitcoin: A Work in Progress* — Sjors Provoost (btcwip.com)
- Bitcoin Core GitHub (github.com/Sjors)
- Provoost's podcast appearances on Bitcoin development process

---

## Michael Ford / fanquake (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Maintainer / Build Systems
**Active:** 2012–present

Australian Bitcoin Core maintainer responsible for the build system, dependency management, and release process — the infrastructure that converts Bitcoin Core source code into the binaries that node operators download. He has been one of the most active code reviewers in the project's history since 2012. His maintenance of the reproducible build system allows anyone to verify that released binaries match the published source code, a documented security property of Bitcoin Core releases.

**Sources:**
- Bitcoin Core GitHub (github.com/fanquake)
- Bitcoin Core build system and reproducible build documentation

---

## Hennadii Stepanov / hebasto (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Maintainer / GUI
**Active:** 2019–present

Ukrainian Bitcoin Core maintainer who became one of the most active contributors and reviewers in the project since joining in 2019. Stepanov leads development of the Bitcoin Core GUI (graphical user interface) and the bitcoin-gui repository, and has reviewed code across multiple areas of the codebase. He continued contributing actively through the Russia-Ukraine war.

**Sources:**
- Bitcoin Core GitHub (github.com/hebasto)
- Bitcoin-gui repository documentation

---

## Andrew Chow (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Maintainer / Wallet
**Active:** 2017–present

Bitcoin Core maintainer who has contributed since 2017, specializing in wallet development, PSBT (Partially Signed Bitcoin Transactions, BIP174), and descriptor wallets. Chow co-authored BIP174, the standard for passing partially-signed transactions between wallets and hardware signing devices, and led the multi-year effort to migrate Bitcoin Core's wallet from its legacy architecture to a descriptor-based system capable of expressing complex spending conditions including multisig and timelocks.

**Sources:**
- Bitcoin Core GitHub (github.com/achow101)
- BIP174 (PSBT) — Andrew Chow
- Descriptor wallet documentation

---

## Antoine Poinsot (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Security Researcher / Miniscript
**Active:** 2019–present

French Bitcoin Core contributor and co-founder of Wizardsardine, a Bitcoin custody company. Poinsot co-developed Miniscript — a structured language for writing Bitcoin Scripts that makes spending conditions analyzable and composable — alongside Pieter Wuille and Andrew Poelstra. He has also responsibly disclosed multiple historical vulnerabilities in Bitcoin Core discovered through security audits, and has become an increasingly active Core maintainer since 2019.

**Sources:**
- Miniscript documentation (bitcoin.sipa.be/miniscript)
- Wizardsardine documentation
- Bitcoin Core GitHub (github.com/darosior)
- Poinsot's security disclosure write-ups

---

## Eric Lombrozo (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / SegWit Activation Advocate
**Active:** 2013–present

Bitcoin Core contributor and co-author of BIP141 (SegWit), the 2015 proposal that introduced Segregated Witness to Bitcoin. Lombrozo co-founded Ciphrex and was a vocal advocate for the small-block position during the blocksize war, contributing to the activation logic and community coordination behind SegWit. His role in the SegWit activation process is documented in *The Blocksize War* by Jonathan Bier.

**Sources:**
- BIP141 (SegWit) — Lombrozo, Lau, Wuille
- *The Blocksize War* — Jonathan Bier
- Bitcoin Core GitHub (github.com/eric-lombrozo)
- Ciphrex documentation

---

## Russell O'Connor (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Script Researcher / Simplicity Author
**Active:** 2012–present

Canadian Bitcoin Core contributor and Blockstream researcher who authored Simplicity, a formal low-level programming language designed as a long-term replacement for Bitcoin Script with mathematically provable properties. Simplicity spending conditions can be formally verified to behave as specified — a property Bitcoin Script does not offer. As of mid-2025, Simplicity is not deployed on Bitcoin mainnet; Blockstream has developed an implementation for the Liquid sidechain as a testing environment. O'Connor also contributed to the development of Taproot's script path.

**Sources:**
- Simplicity whitepaper and documentation — Russell O'Connor (Blockstream)
- Bitcoin Core GitHub contributions
- Blockstream Research blog

---

## Bryan Bishop / kanzure (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Contributor / Meeting Transcriber / Research Aggregator
**Active:** 2012–present

Bitcoin Core contributor who systematically transcribed Bitcoin developer IRC meetings, Scaling Bitcoin conferences, and CoreDev meetups, creating a searchable public archive at diyhpl.us/wiki/transcripts that is a primary source for researchers studying Bitcoin's technical decision-making process. Bishop also contributed directly to Bitcoin Core development across key management, transaction introspection, and research tooling, and is known for broad technical knowledge spanning biology, hardware, and cryptography alongside software development.

**Sources:**
- Bitcoin developer meeting transcripts (diyhpl.us/wiki/transcripts)
- Bitcoin Core GitHub (github.com/kanzure)
- Scaling Bitcoin conference transcripts

---

## Cory Fields (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Build Systems / Infrastructure
**Active:** 2012–present

Bitcoin Core contributor who led the transition to the Autotools build system and later CMake, and made significant contributions to libbitcoinconsensus — the library that allows external software to validate Bitcoin transactions using Core's actual consensus rules without running a full node. Fields has been active in Bitcoin Core since 2012. His build system and consensus library work reduced the risk of subtle incompatibilities between Bitcoin Core and downstream software that relies on it.

**Sources:**
- Bitcoin Core GitHub (github.com/theuni)
- libbitcoinconsensus documentation
- Bitcoin Core build system history

---

## Samuel Dobson / meshcollider (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Maintainer / Wallet
**Active:** 2017–2022

New Zealand Bitcoin Core contributor who became a maintainer from 2017 to 2022, focusing on wallet development and hardware wallet support via HWI (Hardware Wallet Interface) — the standard interface between Bitcoin Core and hardware wallet devices. Dobson contributed to the wallet modernization effort alongside Andrew Chow and reviewed code across multiple codebase areas before stepping back from active contribution.

**Sources:**
- Bitcoin Core GitHub (github.com/meshcollider)
- HWI (Hardware Wallet Interface) documentation

---

## Carl Dong (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Reproducible Builds
**Active:** 2018–2022

Bitcoin Core contributor who led the multi-year effort to migrate Bitcoin Core's build system from Gitian to Guix, a fully reproducible and bootstrappable build system that allows anyone to independently verify that released binaries are built from the claimed source code with no hidden modifications. Dong's work between 2018 and 2022 addressed a documented supply chain attack vector in critical open-source software by removing the need to trust any specific build machine, developer, or organization.

**Sources:**
- Bitcoin Core Guix build documentation
- Carl Dong's presentations on reproducible builds (Advancing Bitcoin conference)
- Bitcoin Core GitHub (github.com/dongcarl)

---

## Martin Zumsande (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / P2P Networking
**Active:** 2019–present

German Bitcoin Core contributor who has specialized in p2p networking improvements since 2019, particularly address relay and peer discovery — the mechanisms by which Bitcoin nodes find and connect to each other. His work has contributed to improving Bitcoin's network robustness against eclipse attacks, where an adversary controls all of a node's connections and feeds it a false view of the blockchain.

**Sources:**
- Bitcoin Core GitHub (github.com/mzumsande)
- Bitcoin-dev mailing list contributions on p2p networking

---

## Murch / Mark Erhardt (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developer / Researcher
**Active:** 2015–present

A Bitcoin Core developer specializing in wallet optimization, coin selection, and UTXO management. Erhardt wrote his Master's thesis on coin selection algorithms, work that was subsequently merged into Bitcoin Core. He has worked at BitGo and Chaincode Labs, and co-founded Localhost Research alongside Ava Chow and Jay Berg, an organization funding Bitcoin Core developers. In 2023, he and Gloria Zhao co-authored "Waiting for Confirmation," a widely read educational series on transaction relay, mempool policy, and mining transaction selection. He is a prolific contributor to Bitcoin Stack Exchange and a recognized voice on Bitcoin wallet architecture and protocol research.

**Sources:**
- Chaincode Labs
- Bitcoin Core GitHub contribution history
- "Waiting for Confirmation" series (2023) — Mark Erhardt & Gloria Zhao
- Bitcoin Stack Exchange

---

## Dustin Trammell (dates unknown)
**Tier:** 2
**Role:** Early Node Operator / Satoshi Correspondent
**Active:** 2009

American security researcher who downloaded Bitcoin within days of its January 2009 launch and likely operated one of the first nodes on the network after Satoshi and Hal Finney. Trammell corresponded directly with Satoshi, submitted early bug reports, and received BTC directly from Nakamoto. His correspondence is archived at the Satoshi Nakamoto Institute and is primary source material; his questions to Satoshi are documented to have prompted the removal of the IP-based coin sending feature.

**Sources:**
- CoinTelegraph: "The first days of Bitcoin and Dustin D. Trammell's emails with Satoshi Nakamoto"
- Satoshi Nakamoto Institute email archive

---

## Jeremy Sturdivant / jercos (dates unknown)
**Tier:** 2
**Role:** Early Forum Member / Pizza Counterparty
**Active:** 2010

A 19-year-old Bitcointalk member who, on May 22, 2010, accepted Laszlo Hanyecz's forum offer and ordered two Papa John's pizzas in exchange for 10,000 BTC — completing Bitcoin's first documented real-world commercial transaction. Sturdivant subsequently spent his 10,000 BTC at an implied value of approximately $400. Bitcoin Pizza Day, observed annually on May 22, traces directly to this exchange.

**Sources:**
- Bitcointalk Pizza thread (May 2010) — Laszlo Hanyecz
- BitcoinWiki: jercos

---

## Dustin Dollar / dwdollar (dates unknown)
**Tier:** 2
**Role:** Founder, First Bitcoin Exchange
**Active:** 2010

Early Bitcoin participant who proposed Bitcoin Market on Bitcointalk on January 15, 2010 and launched it on March 17, 2010 — the first documented cryptocurrency exchange. Bitcoin Market allowed users to buy and sell Bitcoin for U.S. dollars, establishing the first market-based price discovery mechanism for Bitcoin. The exchange collapsed in mid-2011 after PayPal withdrew support due to fraud, but its brief operation defined the foundational model for Bitcoin exchanges that followed.

**Sources:**
- Bitcointalk: Bitcoin Market thread (January 2010)
- fullycrypto.com: "Remembering BitcoinMarket, Bitcoin's First-ever Exchange"

---

## Daniel Folkinshteyn / nanotube (dates unknown)
**Tier:** 2
**Role:** Developer / OTC Market Pioneer
**Active:** 2010–2013

Developer who launched the #bitcoin-otc IRC trading channel in October 2010 and built the Bitcoin-OTC web-of-trust system with the "gribble" IRC bot — the first structured over-the-counter Bitcoin market and the first reputation system for Bitcoin trading. The web-of-trust model allowed participants to rate counterparties after trades using PGP-key-authenticated identities, creating a public and permanent reputation record without central authority. Bitcoin-OTC was the primary peer-to-peer Bitcoin trading venue before formal exchanges dominated the market.

**Sources:**
- Private Internet Access interview with nanotube (2013)
- Bitcoin-OTC documentation archive

---

## Bitcoin-OTC Web of Trust — The Infrastructure (2010–2013)
**Tier:** 2
**Role:** Decentralized Reputation System / OTC Trading Infrastructure
**Active:** 2010–2013 (peak era)

The Bitcoin-OTC Web of Trust (bitcoin-otc.com), built by nanotube around the #bitcoin-otc IRC channel, was the first decentralized reputation system in Bitcoin — a public, user-maintained database of trust ratings between Bitcoin traders, enforced by the "gribble" IRC bot. Participants authenticated using PGP keys and rated counterparties after trades; the ratings were public and permanent. It was the primary peer-to-peer trading infrastructure from 2010 to roughly 2013, before formal exchange volume came to dominate. The web-of-trust model applied PGP-based identity authentication — a cypherpunk technique — to the problem of counterparty risk in decentralized commerce without requiring legal identity or a central custodian.

**Sources:**
- Bitcoin-OTC documentation and web-of-trust database archive (bitcoin-otc.com)
- Gribble bot documentation
- Interview with nanotube (cross-reference: nanotube entry)
- Bitcoin-OTC web-of-trust data archive

---

## Rusty Russell (dates unknown)
**Tier:** 2
**Role:** Blockstream Developer / Core Lightning Author
**Active:** 2015–present

Australian developer at Blockstream who authored c-lightning (now Core Lightning), the third major Lightning Network implementation alongside LND and Eclair, and co-authored the BOLTs (Basis of Lightning Technology) specification that standardizes interoperability across all Lightning implementations. Russell's background as a Linux kernel developer brought systems-programming rigor to Lightning development. His Core Lightning implementation and BOLTs co-authorship work are primary sources for the Lightning protocol specification.

**Sources:**
- Core Lightning GitHub (github.com/ElementsProject/lightning)
- BOLTs specification (github.com/lightning/bolts)
- Blockstream research documentation

---

## ACINQ / Pierre-Marie Padiou (dates unknown)
**Tier:** 2
**Role:** Lightning Implementation Team / Phoenix Wallet Founders
**Active:** 2016–present

Paris-based Bitcoin and Lightning development company co-founded by Pierre-Marie Padiou that built Eclair, the second major Lightning Network implementation; created Phoenix wallet, a non-custodial Lightning wallet with automated channel management via ACINQ's LSP; and operates one of the most well-connected Lightning routing nodes globally. ACINQ has contributed to the BOLTs specification and conducted research on trampoline routing, channel splicing, and other Lightning protocol improvements.

**Sources:**
- ACINQ GitHub (github.com/ACINQ)
- Eclair implementation documentation
- Phoenix wallet documentation (phoenix.acinq.co)

---

## Sergej Kotliar — Bitrefill (dates unknown)
**Tier:** 2
**Role:** CEO, Bitrefill / Early Lightning Merchant
**Active:** 2015–present

Swedish entrepreneur who founded Bitrefill, a service for purchasing gift cards, phone top-ups, and eSIMs with Bitcoin, which became one of the earliest commercial Lightning Network merchants in 2018 and subsequently one of its larger routing nodes. Bitrefill's commercial Lightning deployment provided early production data on payment throughput and routing. The company operates a Bitcoin circular economy model allowing users to acquire goods for Bitcoin without converting to fiat.

**Sources:**
- Bitrefill documentation (bitrefill.com)
- Lightning Network routing node statistics
- Kotliar's public writing and conference appearances

---

## Amboss — Jesse Shrader & Anthony Potdevin (founded ~2021)
**Tier:** 2
**Role:** Lightning Network Analytics & Infrastructure
**Active:** 2021–present

Jesse Shrader and Anthony Potdevin co-founded Amboss, a Lightning Network analytics platform and explorer at amboss.space, providing node operators with data on liquidity, channel discoverability, routing efficiency, and network topology. The platform functions as a social layer for Lightning node operators — surfacing reputational data and liquidity information that was otherwise opaque. Amboss raised $4 million in seed funding led by Stillmark to expand its Lightning infrastructure products and AI research. Shrader serves as CEO and has been a public advocate for Lightning Network adoption and for USDT on Lightning as a growth vector.

**Sources:**
- amboss.space; amboss.tech
- Bitcoin Magazine — Amboss seed funding (2022)
- PRWeb — Amboss $4M raise announcement

---

## RoboSats — Reckless_Satoshi (pseudonym) (founded 2022)
**Tier:** 2
**Role:** Peer-to-Peer Lightning Bitcoin Exchange
**Active:** 2022–present

A peer-to-peer Bitcoin/fiat exchange built on the Lightning Network, created by a pseudonymous developer operating as Reckless_Satoshi and first publicly announced on February 27, 2022. The platform uses Lightning hold invoices as fidelity bonds and trade escrows, enabling non-custodial, KYC-free Bitcoin trades accessible via Tor. RoboSats was inspired by P2PLNBot and designed to minimize custody while maximizing privacy. The project is fully open-source and community-maintained. Its Tor-based architecture and no-KYC design made it a prominent tool in the Bitcoin privacy and sovereignty community.

**Sources:**
- robosats.org; learn.robosats.org
- GitHub — Reckless-Satoshi/robosats
- Bitcoin Magazine — RoboSats profile (2022)

---

## lnp2pBot — Francisco Calderón (founded 2021)
**Tier:** 2
**Role:** Peer-to-Peer Lightning Bitcoin Exchange / Telegram Bot
**Active:** 2021–present

Francisco Calderón, a Venezuelan software developer and former free software movement activist known online as Negruch, began developing lnp2pBot in mid-2020 at the suggestion of Javier Bastardo, founder of the Satoshi en Venezuela (SEV) community group. The bot launched publicly in August 2021 as an open-source Telegram bot enabling peer-to-peer Bitcoin trading over the Lightning Network without KYC or identity verification. The system uses Lightning hold invoices for escrow, connecting buyers and sellers directly in local currencies. Within five months of launch, users from Argentina, Venezuela, Spain, the United States, Colombia, Peru, El Salvador, Mexico, Cuba, and Brazil were trading through the bot. Calderón received a grant from the Human Rights Foundation (HRF) for the project. lnp2pBot became a significant tool for Bitcoin adoption in Latin America, particularly in countries with currency controls and limited access to formal exchanges.

**Sources:**
- lnp2pbot.com
- GitHub — lnp2pBot/bot
- BitFinance News — lnp2pBot growth coverage (2022)
- HRF grant announcement

---

## Kilian Rausch & Boltz (founded 2019)
**Tier:** 2
**Role:** Non-Custodial Bitcoin Swap Service / Lightning Infrastructure
**Active:** 2019–present

Kilian Rausch co-founded Boltz in 2019 alongside a pseudonymous co-founder (Michael) as a non-custodial swap service enabling trustless transfers between Bitcoin on-chain, Lightning Network, Liquid Network, and Rootstock. Boltz originated in 2018 as a solution to Lightning channel liquidity balancing while building an early Lightning-based decentralized exchange (OpenDex). The mainnet launched in April 2019 and has been self-funded since inception. Boltz uses submarine swaps and atomic swap technology to enable cross-layer Bitcoin transfers without counterparty risk. In 2023, Boltz expanded to Liquid Network swaps and went full-time. The project has been described as infrastructure for bridging Bitcoin's various layers without custodial trust.

**Sources:**
- boltz.exchange
- blog.boltz.exchange
- Bitcoin Magazine coverage
- Stephan Livera Podcast SLP557
- Bitcoin Infinity Show (January 2025)

---

## René Pickhardt (dates unknown)
**Tier:** 2
**Role:** Lightning Routing Researcher
**Active:** 2019–present

German Lightning Network researcher who co-authored "Optimally Reliable & Cheap Payment Flows on the Lightning Network" (2021, with Stefan Richter), which proposed a probabilistic model for routing payments through the Lightning Network that improves payment reliability and reduces costs by modeling channel liquidity as probability distributions. His research has influenced routing algorithm implementations across multiple Lightning clients and has been cited in ongoing Lightning protocol development.

**Sources:**
- "Optimally Reliable & Cheap Payment Flows on the Lightning Network" (2021) — Pickhardt & Richter
- Pickhardt's research blog and publications
- Lightning Network routing algorithm implementations

---

## Thomas Voegtlin (1979–present)
**Tier:** 2
**Role:** Developer / Electrum Wallet Creator
**Active:** 2011–present

French developer who created Electrum in November 2011, one of the earliest SPV (Simplified Payment Verification) wallets, allowing users to verify Bitcoin transactions without downloading the full blockchain. Voegtlin built Electrum following the MyBitcoin.com custodial wallet theft of 2011 as a non-custodial alternative. Electrum has been in continuous use and active development since 2011, making it one of the longest-running Bitcoin wallets on record.

**Sources:**
- Electrum documentation and history (electrum.org)
- Bitcointalk: Electrum launch thread (November 2011)

---

## Stefan Thomas / justmoon (1987–present)
**Tier:** 2
**Role:** Developer / Educator
**Active:** 2011–present

German-American developer who created the "What is Bitcoin?" animated explainer video in 2011, an early and widely distributed Bitcoin educational resource, and served as a Bitcointalk co-administrator. He later became CTO of Ripple. In 2021, he publicly disclosed that he was locked out of an IronKey hardware drive containing 7,002 BTC because he had forgotten the password — a case documented in the New York Times that became a widely cited example of self-custody risk.

**Sources:**
- "What is Bitcoin?" video (2011) — Stefan Thomas
- New York Times: IronKey story (2021)
- Bitcointalk co-administrator history

---

## Mike Caldwell / Casascius (dates unknown)
**Tier:** 2
**Role:** Physical Bitcoin Creator
**Active:** 2011–2013

American developer who created Casascius physical Bitcoin coins in 2011 — brass coins with embedded private keys sealed under a holographic sticker — minting coins representing nearly 100,000 BTC before FinCEN issued a cease and desist order in November 2013, citing unlicensed money transmission. The FinCEN action was among the first U.S. regulatory enforcement actions against a Bitcoin product. Loaded Casascius coins with intact seals are now collected as artifacts of early Bitcoin history.

**Sources:**
- Bitcointalk: Casascius launch thread (August 2011)
- FinCEN cease and desist (November 2013)
- Bitcoin Wiki: Casascius physical bitcoins

---

## Joseph Poon & Thaddeus Dryja (dates unknown)
**Tier:** 2
**Role:** Lightning Network Co-Authors
**Active:** 2015–present

Co-authors of "The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments" (2016), the whitepaper that proposed payment channels and multi-hop routing as Bitcoin's off-chain scalability mechanism. The Poon-Dryja proposal became the foundational technical document for all three major Lightning implementations: LND, Core Lightning, and Eclair. Dryja later co-founded the MIT Digital Currency Initiative; Poon subsequently became involved in Ethereum's Plasma project.

**Sources:**
- "The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments" (2016) — Poon & Dryja
- MIT Digital Currency Initiative documentation
- Lightning Network history documentation

---

## Elizabeth Stark & Laolu Osuntokun / roasbeef (Stark: 1983–present)
**Tier:** 2
**Role:** Co-Founders, Lightning Labs / LND Developers
**Active:** 2016–present

Co-founders of Lightning Labs, incorporated in 2016, which develops LND (Lightning Network Daemon), one of three major Lightning Network implementations and the basis for a large share of Lightning nodes and wallets. Stark holds degrees from Harvard and Stanford Law School and taught courses on internet architecture and peer-to-peer technology at Stanford and Yale before entering the Bitcoin space; she has served as CEO and public spokesperson for Lightning Labs since its founding. Osuntokun (known as roasbeef) leads technical development of LND and has contributed extensively to the BOLTs (Basis of Lightning Technology) specification and to taproot channel work. In addition to LND, Lightning Labs developed Loop (a service for managing Lightning channel liquidity via submarine swaps), Pool (a marketplace for acquiring inbound Lightning channel liquidity), and Taproot Assets (formerly Taro, a protocol for issuing assets on the Bitcoin and Lightning Network using Taproot). Lightning Labs raised a $2.5 million seed round in March 2018, a $10 million Series A in February 2020, and a $70 million Series B in April 2022 led by Valor Equity Partners with participation from Baillie Gifford, NYDIG, Stillmark, and others; Jack Dorsey was an early investor.

**Sources:**
- Lightning Labs documentation (lightning.engineering)
- LND GitHub (github.com/lightningnetwork/lnd)
- BOLTs (Basis of Lightning Technology) specification
- Forbes — Lightning Labs $70M Series B (April 2022)
- Bitcoin Magazine — Lightning Labs Series B announcement (2022)
- CoinDesk — Elizabeth Stark profile (2018)

---

## Christian Decker (dates unknown)
**Tier:** 2
**Role:** Blockstream Researcher / Lightning Pioneer
**Active:** 2012–present

Swiss Bitcoin and Lightning researcher at Blockstream who has been active since 2012. Decker co-invented eltoo (later formalized as LN-Symmetry), a simplified Lightning channel update mechanism that addresses state management in a cleaner way than the original Poon-Dryja design, published with Russell and Osuntokun in 2018. He holds what is believed to be the longest-running Lightning node and has contributed to the BOLTs specification and to ongoing Lightning research.

**Sources:**
- Eltoo paper (2018) — Decker, Russell, Osuntokun
- Blockstream research blog
- BOLTs specification contributions

---

## Burak / @brqgoo — Bitmatrix (dates unknown)
**Tier:** 3
**Role:** Developer / Lightning Network Exploit Actor
**Active:** 2022 (Bitcoin-relevant)

A developer associated with Bitmatrix who, on October 9, 2022, broadcast a valid but non-standard Bitcoin transaction — a 998-of-999 Tapscript multisig with 998 signatures in the witness field — that caused btcd nodes to reject valid blocks, crashing all Lightning Network Daemon (LND) nodes that depended on btcd. A second transaction followed containing 500,001 pushes exceeding btcd's hardcoded limit. The disruption prevented new Lightning channels from being opened across the network. Burak reportedly paid F2Pool approximately $700 to include the non-standard transaction in a block. The incident exposed a consensus divergence between btcd and Bitcoin Core and prompted urgent patching of LND. Christian Decker and others publicly condemned the action as a harmful stunt rather than responsible disclosure.

**Sources:**
- CoinDesk — "Rogue Actor Disrupts Lightning Network With a Single Transaction" (November 2022)
- Bitcoin Magazine — LND bug analysis (2022)
- Cross-reference: Christian Decker entry

---

## fiatjaf (pseudonym, identity known)
**Tier:** 2
**Role:** Creator of Nostr Protocol
**Active:** 2020–present

Brazilian developer who created the Nostr protocol (Notes and Other Stuff Transmitted by Relays) in 2020 — a simple, decentralized social protocol built on cryptographic keypairs that uses relays for message distribution, removing centralized points of control or account deplatforming. Lightning Network integration (via "zaps") enables direct micropayment tipping within the protocol. Jack Dorsey donated 14 BTC to fiatjaf in 2022, funding continued protocol development. Multiple Nostr clients, relay operators, and Bitcoin wallets support the protocol as of 2025.

**Sources:**
- Nostr protocol specification (github.com/nostr-protocol/nostr)
- fiatjaf's blog and writing (fiatjaf.com)
- Nostr NIPs (Nostr Implementation Possibilities) repository

---

## Keonne Rodriguez & William Hill / TDevD (dates unknown)
**Tier:** 2
**Role:** Co-Founders, Samourai Wallet
**Active:** 2015–2024

Co-founders of Samourai Wallet, a privacy-focused non-custodial Bitcoin wallet featuring Whirlpool (CoinJoin), Ricochet, PayNym (BIP47 reusable payment codes), and Stonewallx2. Both were arrested by the U.S. Department of Justice in April 2024 on charges of money laundering and operating an unlicensed money transmitting business — charges that the developers and their supporters disputed on the grounds that Samourai is non-custodial software and the developers never held user funds. The DOJ dropped the charges in March 2025. The case generated documented discussion in the Bitcoin development community about the legal risks facing open-source privacy tool developers.

**Sources:**
- DOJ criminal complaint against Rodriguez and Hill (April 2024)
- Samourai Wallet documentation and GitHub
- Bitcoin community response and legal defense documentation
- Whirlpool CoinJoin technical documentation

---

## k00b / Keyan Kousha (dates unknown)
**Tier:** 2
**Role:** Founder, Stacker News
**Active:** 2021–present

American developer who built Stacker News (stacker.news), a Lightning-native link aggregator and discussion platform launched in 2021 where every interaction — posts, comments, and votes — is denominated in satoshis. It is the first documented Bitcoin-native social platform with sustained user activity. Stacker News operates a territory model allowing community members to run their own sub-communities within the platform, all using Lightning micropayments for economic activity.

**Sources:**
- Stacker News (stacker.news)
- k00b's posts and development updates on Stacker News
- Lightning Network integration documentation

---

## Evan Kaloudis (dates unknown)
**Tier:** 2
**Role:** Developer, Zeus Wallet
**Active:** 2019–present

American developer who built Zeus, a mobile Bitcoin and Lightning wallet designed to connect to users' own Lightning nodes via remote control, making non-custodial Lightning accessible on mobile for users running their own infrastructure. Later versions of Zeus added an embedded LND node, allowing full self-custody on mobile without a separate remote node. Zeus has become a reference implementation of self-sovereign Lightning wallet design.

**Sources:**
- Zeus Wallet GitHub (github.com/ZeusLN/zeus)
- Zeus documentation (zeusln.app)

---

## Hampus Sjöberg (dates unknown)
**Tier:** 2
**Role:** Developer, Blixt Wallet
**Active:** 2019–present

Swedish developer who built Blixt Wallet, a non-custodial mobile Lightning wallet with a neutrino backend, notable for implementing advanced Lightning features including zero-conf channels via a dunder LSP, LNURL support, and Tor routing. Sjöberg developed Blixt as an open-source project; it became a reference point for technically capable non-custodial Lightning mobile wallet design.

**Sources:**
- Blixt Wallet GitHub (github.com/hsjoberg/blixt-wallet)
- Blixt documentation and release notes

---

## Breez — Roy Sheinfeld (dates unknown)
**Tier:** 2
**Role:** Lightning Wallet Developer / LSP Pioneer
**Active:** 2019–present

Israeli entrepreneur who founded Breez, a non-custodial Lightning wallet that acts as its own LSP (Lightning Service Provider), and built the Breez SDK — an embeddable toolkit that allows third-party app developers to integrate non-custodial Lightning without building the underlying infrastructure from scratch. Breez was among the first Lightning wallets to include a built-in point-of-sale mode for merchants and integrated Podcasting 2.0, enabling per-minute satoshi streaming to podcast creators. Sheinfeld has written publicly on Lightning infrastructure economics and LSP sustainability.

**Sources:**
- Breez documentation (breez.technology)
- Breez SDK documentation
- Podcasting 2.0 / value-for-value integration documentation

---

## Podcasting 2.0 — Adam Curry & Dave Jones (founded 2020)
**Tier:** 2
**Role:** Open Podcast Protocol Movement / Bitcoin Lightning Integration
**Active:** 2020–present

Open podcasting initiative co-founded by Adam Curry and Dave Jones, launched in August 2020. Curry, known as "the Podfather" for his role in creating podcasting in the early 2000s alongside Dave Winer, and Jones, a developer, co-created the Podcast Index — a free, open podcast directory launched as an alternative to Apple's privately controlled directory — and began the Podcasting 2.0 movement to extend the RSS-based podcast standard with new open features. Central among these was the Value4Value (V4V) model, which uses Lightning Network streaming payments to allow listeners to send satoshis to podcast creators per minute of listening, without intermediaries or platform fees. Podcasting 2.0 defined a set of new RSS namespace tags enabling apps to implement these features interoperably. The initiative attracted a community of podcast app developers building compatible clients, including Fountain, Breez, and others. The Podcast Index has grown to index more podcasts than Apple's directory.

**Sources:**
- podcastindex.org
- Podcasting 2.0 podcast — Curry & Jones (2020–present)
- Podnews — Podcast Index launch coverage (2020)
- Castopod — "The Podfather 2.0" (2021)

---

## Fountain — Nick Malster & Oscar Merry (founded 2021)
**Tier:** 2
**Role:** Bitcoin Podcast App / Value4Value Platform
**Active:** 2021–present

Bitcoin-native podcast application co-founded by Nick Malster and Oscar Merry in 2021, built on the Podcasting 2.0 protocol and the Lightning Network's Value4Value model. Malster and Merry were inspired by Adam Curry's Podcasting 2.0 initiative and concluded that Bitcoin and Lightning made global creator-to-listener payments practical without platforms taking a cut. Fountain allows listeners to stream satoshis directly to podcast creators per minute of listening, tip episodes, and earn satoshis for listening. Pre-seed funding included participation from Anthony Pompliano. Fountain became one of the most widely used Podcasting 2.0-compatible apps and a documented distribution channel for Bitcoin-adjacent podcast content.

**Sources:**
- fountain.fm
- Yahoo Finance — Fountain Lightning listen-to-earn upgrade coverage
- Castos — "Podcast 2.0 App Fountain.fm with Oscar Merry"
- Podnews — Fountain Bitcoin rewards coverage

---

## Phoenix Wallet — ACINQ (launched 2019)
**Tier:** 2
**Role:** Non-Custodial Lightning Wallet / Privacy-First Design
**Active:** 2019–present

ACINQ's consumer-facing Lightning wallet, launched in 2019 and notable for implementing trampoline routing — a technique that routes payments through intermediate nodes that do not know the final destination, improving payment privacy — as well as channel splicing (resizing channels without closing them) and automated liquidity management via ACINQ's LSP. In 2024 Phoenix temporarily withdrew from U.S. app stores over regulatory uncertainty about whether LSPs could be classified as money transmitters, before returning with modified terms. The episode is a documented case of regulatory pressure affecting non-custodial Lightning wallet distribution.

**Sources:**
- Phoenix wallet documentation (phoenix.acinq.co)
- Trampoline routing specification and ACINQ research
- Phoenix U.S. app store withdrawal and return (2024)
- Channel splicing documentation
- Cross-reference: ACINQ company entry

---

## Ben Carman, Tony Giorgio & Paul Miller — Mutiny Wallet (dates unknown)
**Tier:** 2
**Role:** Developers, Mutiny Wallet
**Active:** 2022–2024

Developers who built Mutiny Wallet, the first browser-based non-custodial Lightning wallet, using a WebAssembly-based LDK implementation to run a full Lightning node inside a web browser without requiring an app store or custodian. Mutiny operated from 2022 and shut down in December 2024 after the team publicly disclosed they were unable to find a sustainable business model. The shutdown announcement documented the economic challenges facing open-source Bitcoin infrastructure projects.

**Sources:**
- Mutiny Wallet GitHub (github.com/MutinyWallet)
- Mutiny shutdown announcement (December 2024)
- LDK (Lightning Development Kit) documentation

---

## Ben Arc (pseudonym)
**Tier:** 2
**Role:** Developer, LNbits / ShockWallet
**Active:** 2019–present

Pseudonymous self-taught developer who created LNbits, a free and open-source Lightning wallet and accounts system first developed in 2019. Arc's path to Lightning development began with hardware projects including a modified point-of-sale device piloted at Room77, Berlin's Bitcoin-accepting bar, where it was tested in a live payment environment. LNbits is a lightweight Python application that sits on top of any Lightning funding source and provides isolated wallet accounts, a full REST API, and an extension system for building custom Lightning-powered tools without modifying the core software. The extension architecture attracted contributions from notable developers including Calle (creator of Cashu) and fiatjaf (creator of Nostr). LNbits has been deployed in hackathons, community Bitcoin projects, point-of-sale systems, tipping bots, and paywalls, and accumulated over 60 extensions and support for 20+ backend funding sources. After learning that IBEX was using LNbits in banking products, Arc formalized LNbits as a company in 2022 to ensure software stability and continued development.

**Sources:**
- LNbits GitHub (github.com/lnbits/lnbits)
- LNbits documentation (lnbits.com)
- Bitcoin Magazine — "Building LNbits: The WordPress for Your Bitcoin Lightning Node" (2024)

---

## Rivest, Shamir & Adleman — RSA (1977)
**Tier:** 2
**Role:** Cryptographers
**Active:** 1977

Ron Rivest, Adi Shamir, and Leonard Adleman published RSA public-key cryptography in 1977 — the first widely deployable implementation of asymmetric key cryptography, enabling anyone to encrypt a message with a public key that only the corresponding private key holder could decrypt. Diffie and Hellman had established the theoretical framework in 1976 but did not produce a working asymmetric cipher; RSA filled that gap and became the basis of SSL/TLS, email encryption, and the PGP ecosystem. Bitcoin uses ECDSA rather than RSA for transaction signatures, a more efficient asymmetric algorithm developed later. Adi Shamir also invented Shamir's Secret Sharing (1979), a cryptographic scheme used in some Bitcoin key recovery and multisig implementations.

**Sources:**
- "A Method for Obtaining Digital Signatures and Public-Key Cryptosystems" (1978) — Rivest, Shamir, Adleman
- *The Code Book* — Simon Singh
- Shamir's Secret Sharing paper (1979) — Adi Shamir

---

## TIER 3 — CATALYSTS
*People who accelerated, stressed-tested, or threatened Bitcoin — for better or worse.*

---

## Ross Ulbricht (1984–present)
**Tier:** 3
**Role:** Founder, Silk Road / Dread Pirate Roberts
**Active:** 2011–2013

Built and operated Silk Road (2011–2013), the first major dark web marketplace, using Bitcoin as its exclusive payment rail and Tor for anonymity; arrested in a San Francisco library in October 2013 and sentenced to two consecutive life terms without parole. The market processed an estimated $1.2 billion in transactions before its shutdown and represented Bitcoin's first large-scale commercial use case. Ulbricht's arrest and sentencing drew sustained public attention: his supporters argued the sentence was disproportionate for a non-violent offense, while critics noted the charges included murder-for-hire solicitation. His case constituted the first major legal confrontation between Bitcoin's permissionless design and state authority. He was pardoned by President Trump in January 2025 after serving over a decade.

**Sources:**
- *American Kingpin* (2017) — Nick Bilton
- Ulbricht trial record and sentencing documents (2015)
- Free Ross campaign documentation
- Trump pardon (January 2025)

---

## Variety Jones / Thomas Clark (dates unknown)
**Tier:** 3
**Role:** Silk Road Advisor / Architect
**Active:** 2011–2013

Served as Ross Ulbricht's closest advisor on Silk Road under the alias "Variety Jones," shaping the market's policies, philosophy, and operational security decisions; his communications with Ulbricht were recovered and used at trial, documenting his advisory influence over Silk Road's direction. He evaded capture for two years after Silk Road's shutdown before being arrested in Thailand in 2015 and extradited to the U.S., where he pleaded guilty and was sentenced in 2020. The trial record provides documentation of Silk Road's operational structure beyond what Ulbricht's own communications revealed.

**Sources:**
- *American Kingpin* (2017) — Nick Bilton
- Variety Jones sentencing documents (2020)
- Ulbricht trial transcripts

---

## Blake Benthall / Defcon (dates unknown)
**Tier:** 3
**Role:** Operator, Silk Road 2.0
**Active:** 2013–2014

A SpaceX engineer who took over and operated Silk Road 2.0 after Ulbricht's arrest, rebuilding the marketplace under the alias "Defcon" before being arrested by the FBI in November 2014 after the site was infiltrated by undercover agents. Silk Road 2.0 launched weeks after Silk Road's shutdown, demonstrating continued demand for a Bitcoin-based dark web marketplace. The FBI's infiltration of the successor market, through an undercover agent who obtained an administrator role, illustrated that operational security failures rather than cryptographic weaknesses were the primary vulnerability in dark web market operations.

**Sources:**
- FBI criminal complaint against Blake Benthall (2014)
- *American Kingpin* (2017) — Nick Bilton
- Wired coverage of Silk Road 2.0 takedown

---

## Alexandre Cazes / Alpha02 (1991–2017)
**Tier:** 3
**Role:** Founder, AlphaBay
**Active:** 2014–2017

Founded AlphaBay (2014), which became the largest dark web marketplace in history after Silk Road's fall, processing hundreds of millions in transactions before a joint U.S.-Thai operation shut it down in July 2017. Law enforcement estimates placed AlphaBay at approximately ten times Silk Road's transaction volume at its peak. Cazes was identified through a documented operational security failure: his personal email address appeared in AlphaBay's automated welcome messages. He was arrested in Bangkok in 2017 and died in his cell days later, ruled a suicide. The AlphaBay takedown was coordinated with the simultaneous Hansa Market operation, in which Dutch law enforcement had been quietly running Hansa after seizing it in order to collect data on users who migrated from AlphaBay following its shutdown.

**Sources:**
- DOJ AlphaBay takedown announcement (July 2017)
- Europol/Hansa Market simultaneous operation documentation
- Wired and Vice coverage of Cazes arrest and death

---

## Carl Force & Shaun Bridges (dates unknown)
**Tier:** 3
**Role:** Corrupt Federal Agents / Silk Road Investigators
**Active:** 2012–2015

DEA agent Carl Force IV and Secret Service agent Shaun Bridges, both assigned to the Silk Road task force, used their investigative access to steal Bitcoin, extort Ulbricht, and sell him information about the ongoing investigation; both were convicted of federal crimes. Force extorted Ulbricht under multiple fake identities and stole Bitcoin from the investigation; Bridges moved seized Bitcoin into personal accounts. Their convictions complicated the Ulbricht prosecution and raised documented questions about the integrity of the evidence gathered against him. Blockchain forensics — tracing transactions on the public ledger — played a documented role in building the case against both agents.

**Sources:**
- DOJ criminal complaints against Carl Force (2015) and Shaun Bridges (2015)
- *American Kingpin* (2017) — Nick Bilton
- Wired coverage of Force and Bridges convictions

---

## Mark Karpelès (1985–present)
**Tier:** 3
**Role:** CEO, Mt. Gox
**Active:** 2011–2014

French developer who acquired Mt. Gox from Jed McCaleb in 2011 and ran it until its collapse in February 2014, when approximately 850,000 BTC were reported lost — at the time valued at approximately $450 million. Mt. Gox handled an estimated 70% of all Bitcoin transactions globally at its peak, and its collapse was the largest Bitcoin loss event in history to that point; subsequent bankruptcy proceedings extended over a decade with creditors still awaiting final distribution as of 2024. Karpelès was arrested in Japan in 2015, tried on embezzlement and data manipulation charges, and ultimately convicted on the data manipulation charge while being acquitted of embezzlement. Approximately 200,000 BTC were later recovered in cold storage during the proceedings.

**Sources:**
- Mt. Gox bankruptcy proceedings (Tokyo District Court, 2014–present)
- *Digital Gold* — Nathaniel Popper
- Karpelès trial records (Japan, 2017–2019)
- Mt. Gox creditor claim documentation

---

## Jed McCaleb (1975–present)
**Tier:** 3
**Role:** Developer / Founder
**Active:** 2010–present

Founded Mt. Gox in 2010 as a Magic: The Gathering card trading site, repurposed it as a Bitcoin exchange, and sold it to Mark Karpelès in 2011 before its eventual collapse. He subsequently co-founded Ripple (2012) and later departed Ripple to co-found Stellar (2014), a competing network. His Bitcoin holdings from the Ripple pre-mine became a documented market overhang on Ripple's XRP, and his departure from Ripple to found a directly competing network is documented in the history of both projects.

**Sources:**
- *Digital Gold* — Nathaniel Popper
- Mt. Gox founding and transfer documentation (2010–2011)
- Ripple and Stellar founding records

---

## Roger Ver (1979–present)
**Tier:** 3
**Role:** Early Investor / "Bitcoin Jesus" / Bitcoin Cash Advocate
**Active:** 2011–present

One of Bitcoin's earliest large-scale investors and public advocates — nicknamed "Bitcoin Jesus" — who later became the most prominent backer of the Bitcoin Cash hard fork (August 2017) and operator of Bitcoin.com, which promoted BCH as "Bitcoin" to users. Ver renounced U.S. citizenship in 2014 and obtained citizenship of Saint Kitts and Nevis. His use of Bitcoin.com to direct users toward BCH rather than Bitcoin was widely criticized and is documented in *The Blocksize War* as a central feature of the hard fork's aftermath. In 2024 he was arrested in Spain on U.S. tax evasion charges related to his citizenship renunciation.

**Sources:**
- *The Blocksize War* — Jonathan Bier
- *Cryptopians* — Laura Shin
- Bitcoin.com promotional history (2017–present)
- Ver tax evasion indictment (2024)

---

## Hodlonaut / Magnus Granath (dates unknown)
**Tier:** 3
**Role:** Bitcoin Advocate / Craig Wright Legal Opponent
**Active:** 2019–present (Bitcoin-relevant)

Magnus Granath, a Norwegian public school teacher operating under the pseudonym Hodlonaut, became a central figure in the legal battles surrounding Craig Wright's claim to be Satoshi Nakamoto. In March 2019, Granath posted tweets calling Wright a fraud; Wright responded by offering a bounty for his identity, doxxing him, and filing a defamation lawsuit in the UK. Granath preemptively filed a declaratory action against Wright in Norway. The Oslo trial ran over seven days in September 2022 and concluded in October 2022 with the Norwegian court ruling in Granath's favor, ordering Wright to pay approximately $380,000 in legal fees. The case drew significant community support for Granath and is documented as a landmark episode in the Bitcoin community's resistance to Wright's Satoshi claims.

**Sources:**
- Bitcoin Magazine timeline — Hodlonaut vs. Craig Wright
- Norwegian court ruling (October 2022)
- CoinDesk coverage (2022)
- Cross-reference: Craig Wright entry

---

## Craig Wright (1970–present)
**Tier:** 3
**Role:** BSV Proponent / Satoshi Claimant
**Active:** 2015–present

Australian computer scientist who publicly claimed to be Satoshi Nakamoto beginning in 2015; co-drove the Bitcoin SV (BSV) hard fork from Bitcoin Cash in 2018 with Calvin Ayre; and pursued extensive litigation against Bitcoin developers and others, including copyright claims over the Bitcoin whitepaper and protocol. In March 2024, the UK High Court (COPA v. Wright) ruled that Wright is not Satoshi Nakamoto and that his claim was a fraud involving fabricated evidence; the ruling also dismissed his copyright claims over the Bitcoin whitepaper and source code. His Bitcoin SV fork, promoted as the "original Bitcoin," holds minimal market share. The COPA case constitutes the primary judicial record on the Satoshi identity question.

**Sources:**
- COPA v. Wright (UK High Court, March 2024) — Judge Mellor's judgment
- *The Blocksize War* — Jonathan Bier
- COPA v. Wright trial documentation and expert witness reports
- Bitcoin SV founding (2018) — documentation

---

## Cameron & Tyler Winklevoss (1981–present)
**Tier:** 3
**Role:** Investors / Exchange Founders / ETF Pioneers
**Active:** 2012–present

Among Bitcoin's earliest large institutional investors, accumulating approximately 1% of all Bitcoin supply by 2013; founded Gemini exchange (2014); and filed the first Bitcoin ETF application with the SEC in 2013 — a decade before any spot ETF was approved. The SEC's repeated rejections of their applications from 2013 through 2023 are a documented chapter in Bitcoin's regulatory history, and their Gemini exchange pursued a compliance-focused model and obtained a New York trust company charter. Gemini Earn, a lending product, placed customer funds with Genesis Trading; when Genesis froze withdrawals in November 2022 following FTX's collapse, Gemini Earn customers were unable to withdraw funds, and the resulting dispute with Barry Silbert's DCG was litigated publicly before reaching a settlement in 2024.

**Sources:**
- *Bitcoin Billionaires* (2019) — Ben Mezrich
- Winklevoss ETF application (2013) and SEC rejection history
- Gemini Earn / Genesis Trading litigation documentation

---

## Charlie Shrem (1989–present)
**Tier:** 3
**Role:** Co-Founder, BitInstant
**Active:** 2011–present

Co-founded BitInstant (2011), one of Bitcoin's earliest fiat-to-Bitcoin services that processed a significant share of Bitcoin purchases in its era; arrested in 2014 and convicted of aiding and abetting an unlicensed money transmitting business connected to Silk Road after allowing a Silk Road Bitcoin broker to use BitInstant with knowledge of the funds' destination; served approximately a year in federal prison. His conviction was among the first high-profile enforcement actions against a Bitcoin company executive. After his release he became a podcast host (Untold Stories) and public figure in the Bitcoin community.

**Sources:**
- *Digital Gold* — Nathaniel Popper
- Shrem plea and sentencing records (SDNY, 2014)
- Untold Stories podcast documentation

---

## Amir Taaki (1988–present)
**Tier:** 3
**Role:** Developer / Anarchist / Bitcoin Radical
**Active:** 2010–present

Early Bitcoin Core contributor who authored BIP-0001 (establishing the Bitcoin Improvement Proposal process), created the Libbitcoin project — the first alternative full node implementation (2011) — and co-created DarkWallet (2014) with Cody Wilson, one of the first Bitcoin wallets built around privacy through CoinJoin and stealth addresses. He departed Bitcoin development in 2015 to fight with the Kurdish YPG against ISIS in Syria, publicly describing the two activities as expressions of the same political philosophy, and returned to Bitcoin development afterward. His departure and return are documented events in Bitcoin's developer history.

**Sources:**
- DarkWallet GitHub and documentation (2014)
- Vice documentary on Amir Taaki in Syria
- Bitcoin Core contribution history

---

## Cody Wilson (1988–present)
**Tier:** 3
**Role:** Crypto-Anarchist / Developer / Provocateur
**Active:** 2012–present

Co-created DarkWallet with Amir Taaki and founded Defense Distributed, which produced the Liberator — the first functional 3D-printed firearm (2013) — and later the Ghost Gunner CNC machine series. DarkWallet was a documented contribution to Bitcoin privacy tooling, implementing CoinJoin and stealth addresses at the wallet layer. Wilson's work applied the logic of censorship-resistant technology to both financial transactions and physical weapons manufacturing. He was convicted of sexual assault in 2018.

**Sources:**
- DarkWallet GitHub and documentation (2014)
- *Come and Take It* (2016) — Cody Wilson
- Defense Distributed documentation

---

## Lyn Alden (1984–present)
**Tier:** 3
**Role:** Macroeconomic Analyst / Author / Bitcoin Thinker
**Active:** 2020–present

Founded Lyn Alden Investment Strategy and authored *Broken Money* (2023), a history of monetary technology from commodity money through the modern financial system to Bitcoin. Her writing covers both macro investment analysis and monetary history, treating Bitcoin as a technological and monetary asset within a historical framework. Her background is electrical engineering, not finance, which she has discussed publicly as influencing her analytical approach to monetary and economic systems.

**Sources:**
- *Broken Money* (2023) — Lyn Alden
- Lyn Alden Investment Strategy research (lynalden.com)
- Alden's public writing and podcast appearances

---

## Robert Breedlove (dates unknown)
**Tier:** 3
**Role:** Bitcoin Philosopher / Podcaster
**Active:** 2019–present

Hosts the *What is Money?* podcast, known for long-form philosophical explorations of Bitcoin's meaning, and authored "The Number Zero and Bitcoin" essay. His interview series with Michael Saylor (2020) was widely shared within the Bitcoin community and is cited as a significant influence on Saylor's subsequent public framing of Bitcoin. Breedlove frames sound money as a moral and philosophical issue, reaching audiences who approach Bitcoin through ethical and political philosophy rather than technical or investment arguments.

**Sources:**
- *What is Money?* podcast — Robert Breedlove
- "The Number Zero and Bitcoin" essay — Robert Breedlove
- Breedlove / Saylor interview series (2020–present)

---

## SegWit — The Upgrade That Split Bitcoin (activated August 2017)
**Tier:** 2
**Role:** Protocol Upgrade / Governance Watershed
**Active:** 2015–2017

Segregated Witness (BIP141), proposed by Pieter Wuille, separated transaction signature data from transaction data, fixing transaction malleability (a prerequisite for Lightning Network channel construction) and modestly increasing effective block capacity. Proposed in 2015 and activated in August 2017, SegWit's activation process became the defining governance event of the blocksize war: miners withheld signaling for months despite developer and user support. The UASF movement (BIP148, authored pseudonymously as Shaolinfry) set a deadline for miners to signal support or face chain-split rejection; miners activated SegWit shortly before the deadline. The activation is documented in *The Blocksize War* as a case study in Bitcoin's governance dynamics.

**Sources:**
- BIP141 — Pieter Wuille (SegWit specification)
- BIP148 — Shaolinfry (UASF specification)
- *The Blocksize War* (2021) — Jonathan Bier
- SegWit activation data (August 2017)

---

## Shaolinfry (pseudonymous)
**Tier:** 2
**Role:** Anonymous Developer / UASF Architect
**Active:** 2017

Pseudonymous developer who authored BIP148, the User Activated Soft Fork (UASF) proposal that specified a mechanism for economic nodes to orphan non-SegWit blocks after August 1, 2017, independent of miner signaling. Miners activated SegWit in July 2017 before the deadline. Shaolinfry's identity remains unknown. BIP148 is documented in *The Blocksize War* and contemporaneous mailing list records as the mechanism that broke the miner stalemate in the SegWit activation dispute.

**Sources:**
- BIP148 — Shaolinfry
- UASF movement documentation (uasf.co)
- *The Blocksize War* (2021) — Jonathan Bier

---

## Taproot — Bitcoin's Privacy & Efficiency Upgrade (activated November 2021)
**Tier:** 2
**Role:** Protocol Upgrade / Schnorr Signatures & Smart Contract Privacy
**Active:** 2018–2021

Taproot (BIP340/341/342) was originally proposed by Greg Maxwell in 2018 and developed by Pieter Wuille, Jonas Nick, A.J. Towns, and Tim Ruffing; it introduced Schnorr signatures and MAST (Merkelized Abstract Syntax Trees), allowing complex spending conditions to appear indistinguishable from simple single-key payments on-chain when the spending path taken is the cooperative path. Taproot activated in November 2021 at block 709,632 via the Speedy Trial signaling mechanism, which set a defined threshold and timeline. BIP340/341/342 together represent Bitcoin's first significant scripting upgrade since SegWit.

**Sources:**
- BIP340 (Schnorr Signatures) — Wuille, Nick, Ruffing
- BIP341 (Taproot) — Wuille, Nick, Towns
- BIP342 (Tapscript) — Wuille, Nick, Towns
- Speedy Trial activation mechanism documentation
- Taproot activation data (block 709,632, November 14, 2021)

---

## The Covenants Debate — Bitcoin's Open Question (ongoing, ~2019–present)
**Tier:** 2
**Role:** Protocol Debate / Scripting Capability
**Active:** 2019–present

An ongoing and unresolved technical debate about whether Bitcoin's script system should be extended with "covenants" — opcodes that allow an output to restrict how future outputs spending it must be structured. Documented use cases include time-delayed self-custody vaults, improved Lightning channel management, and trustless financial contracts. Active proposals as of mid-2025 include CTV (BIP119), ANYPREVOUT (BIP118), OP_VAULT (BIP345), MATT, LNHANCE, and OP_CAT. No covenant proposal has reached consensus among Bitcoin developers. Concerns raised by opponents include added complexity, unintended consequences, and potential applications to coin censorship.

**Sources:**
- BIP119 (CTV) — Jeremy Rubin
- BIP118 (ANYPREVOUT) — A.J. Towns & Christian Decker
- BIP345 (OP_VAULT) — James O'Beirne
- Bitcoin optech covenants documentation (bitcoinops.org)
- Delving Bitcoin forum covenant discussions

---

## Jeremy Rubin (dates unknown)
**Tier:** 2
**Role:** Bitcoin Developer / CTV Proponent
**Active:** 2019–present

Bitcoin developer who proposed OP_CHECKTEMPLATEVERIFY (CTV, BIP119), a covenant opcode enabling Bitcoin vaults, payment batching, and congestion control. In 2022, Rubin released a CTV activation client intended to push the proposal toward activation without achieving prior community consensus; the move generated significant backlash from Bitcoin developers and the wider community, and Rubin subsequently stepped back from the activation effort. CTV remains unactivated as of mid-2025. The episode is a documented case study in Bitcoin upgrade governance and the limits of unilateral activation attempts.

**Sources:**
- BIP119 — Jeremy Rubin (CTV specification)
- Rubin's CTV activation client announcement (2022)
- Rubin's subsequent step-back documentation
- Bitcoin Optech CTV coverage (bitcoinops.org)

---

## James O'Beirne (dates unknown)
**Tier:** 2
**Role:** Bitcoin Developer / Vault Researcher
**Active:** 2019–present

Bitcoin developer who proposed OP_VAULT (BIP345), a covenant mechanism designed for Bitcoin vaults — a self-custody model where funds can only be withdrawn after a time delay, during which a recovery key can claw back the funds if the withdrawal was unauthorized. The proposal addresses the irreversibility of Bitcoin theft by making theft detectable and reversible within a defined window. OP_VAULT has been cited in discussions with both self-custody advocates and institutional custody providers and is one of the most practically motivated covenant proposals in the ongoing covenants debate.

**Sources:**
- BIP345 (OP_VAULT) — James O'Beirne
- O'Beirne's vault research and blog posts
- Bitcoin Optech OP_VAULT coverage (bitcoinops.org)

---

## Schnorr Signatures in Bitcoin — The Thirteen-Year Wait (BIP340, 2021)
**Tier:** 2
**Role:** Protocol History / Cryptographic Upgrade
**Active:** 2008–2021

A documented case in Bitcoin's protocol history: Schnorr signatures were invented in 1989 and patented until February 2008 — months before Satoshi published the Bitcoin whitepaper. Satoshi used ECDSA instead, as the Schnorr patent was still active at the time of Bitcoin's design. Greg Maxwell advocated for adopting Schnorr signatures in Bitcoin for years, citing their smaller size, linearity property (enabling MuSig multi-party signing), and cleaner security proofs. BIP340, formalizing Schnorr signatures for Bitcoin, was authored by Wuille, Nick, and Ruffing and activated as part of Taproot in November 2021 — thirteen years after the patent expired.

**Sources:**
- BIP340 — Wuille, Nick, Ruffing (Schnorr signatures for Bitcoin)
- Greg Maxwell Schnorr advocacy and research documentation
- Taproot activation data (November 2021)
- Cross-reference: Claus-Peter Schnorr entry (Tier 1); Taproot entry

---

## MuSig & MuSig2 — Multi-Party Schnorr Signing
**Tier:** 2
**Role:** Cryptographic Protocol / Privacy & Efficiency
**Active:** 2018–present

MuSig (2018) and MuSig2 (2020), developed by Gregory Maxwell, Andrew Poelstra, Yannick Seurin, Pieter Wuille, Jonas Nick, and Tim Ruffing, enable multiple parties to collaboratively produce a single Schnorr signature that is indistinguishable on-chain from a single-signer signature — making n-of-n multisig transactions invisible as multisig to chain observers. MuSig2 reduced the required communication rounds from three to two, making it practical for hardware wallets and signing devices with limited interactivity. Both are formalized in BIP327 (MuSig2 for Bitcoin) and are foundational to the next generation of Bitcoin multisig custody and Lightning channel infrastructure.

**Sources:**
- MuSig paper (2018) — Maxwell, Poelstra, Seurin, Wuille
- MuSig2 paper (2020) — Nick, Ruffing, Seurin
- BIP327 (MuSig2 for Bitcoin) — Jonas Nick, Tim Ruffing, Elliott Jin
- Blockstream MuSig research documentation

---

## Jonas Nick & A.J. Towns (dates unknown)
**Tier:** 2
**Role:** Bitcoin Core Developers / Taproot & Schnorr Co-Authors
**Active:** 2018–present

Jonas Nick (Blockstream researcher) co-authored BIP340 (Schnorr signatures), BIP341 (Taproot), and BIP327 (MuSig2), and has contributed extensively to multi-party Schnorr signing research at Blockstream. A.J. Towns co-authored BIP341 and BIP342 (Tapscript) and subsequently proposed ANYPREVOUT (BIP118) for Lightning Network channel improvements, making him an active participant in the ongoing covenants debate alongside his Taproot co-authorship work.

**Sources:**
- BIP340, BIP341, BIP342 authorship records
- A.J. Towns covenant and BIP118 proposals
- Bitcoin Core GitHub contribution history

---

## Blockstream — Adam Back, Greg Maxwell, Pieter Wuille, Mark Friedenbach, Jorge Timón & team (founded 2014)
**Tier:** 2
**Role:** Bitcoin Technology Company / Protocol Research & Infrastructure
**Active:** 2014–present

Bitcoin technology company founded in 2014 by Adam Back, Greg Maxwell, Pieter Wuille, Mark Friedenbach, Jorge Timón, and others — the first company dedicated entirely to Bitcoin protocol development and infrastructure. Blockstream produced the Liquid Network (a Bitcoin sidechain for fast settlement), Blockstream Satellite (global Bitcoin blockchain broadcast via satellite), Core Lightning (the c-lightning Lightning implementation), and Blockstream Jade (a hardware wallet). Its researchers and developers authored or co-authored SegWit, Taproot, Schnorr signatures, Confidential Transactions, MuSig, and contributions to the Lightning specification. The company has been criticized by some for concentrating developer influence over Bitcoin Core; its open-source output and the documented independence of its researchers are points of context in that ongoing discussion.

**Sources:**
- Blockstream company documentation (blockstream.com)
- Liquid Network technical documentation
- Blockstream Satellite documentation
- Blockstream Jade hardware wallet documentation
- Cross-references: Adam Back (Tier 1), Greg Maxwell, Pieter Wuille, Christian Decker, Rusty Russell (all Tier 2)

---

## Mark Friedenbach (dates unknown)
**Tier:** 2
**Role:** Blockstream Co-Founder / Protocol Researcher
**Active:** 2014–present

Blockstream co-founder who contributed foundational Bitcoin protocol research including work on script upgrades, soft fork mechanisms, and his "Forward Blocks" proposal — a documented technical contribution to Bitcoin's scalability debate. Friedenbach has engaged in Bitcoin's technical discussions on how to upgrade the script system safely and how to structure soft forks to minimize risk; his research has been cited in developer discussions of Bitcoin's long-term throughput and scalability architecture.

**Sources:**
- Blockstream research documentation
- "Forward Blocks" proposal — Mark Friedenbach
- Bitcoin Core contribution history

---

## Foundation Devices — Zach Herbert (dates unknown)
**Tier:** 2
**Role:** Hardware Wallet Developer / Open-Source Bitcoin Security
**Active:** 2020–present

American entrepreneur who founded Foundation Devices and created the Passport, a Bitcoin-only hardware wallet with fully open-source hardware and firmware — the first hardware wallet to make both the software and the physical hardware design auditable. The Passport supports microSD air-gapped signing and has a Bitcoin-only focus. Foundation's open-source approach allows independent verification of both the firmware and the hardware schematics, a documented security property that distinguishes it from hardware wallets with closed designs.

**Sources:**
- Foundation Devices documentation (foundationdevices.com)
- Passport hardware wallet documentation
- Open-source hardware and firmware repository (GitHub)

---

## SeedSigner (pseudonymous creator)
**Tier:** 2
**Role:** DIY Hardware Wallet Developer / Open-Source Community Project
**Active:** 2021–present

A pseudonymous developer who created SeedSigner, a stateless, open-source Bitcoin signing device built on a Raspberry Pi Zero and assemblable for under $50 from commodity parts. SeedSigner's defining design feature is that it never stores a seed phrase — the user enters the seed each session and the device retains nothing when powered off, eliminating the class of attacks targeting persistent seed storage. The project is community-developed and fully open-source, allowing independent verification of both hardware and firmware.

**Sources:**
- SeedSigner documentation and GitHub (github.com/SeedSigner/seedsigner)
- SeedSigner community documentation and build guides

---

## Trezor / SatoshiLabs — Marek "Slush" Palatinus & Pavol "Stick" Rusnák (dates unknown)
**Tier:** 2
**Role:** Hardware Wallet Pioneers / First Mining Pool Creator
**Active:** 2010–present

Czech developers who co-founded SatoshiLabs in Prague. Marek Palatinus created Slush Pool in 2010 — the first Bitcoin mining pool — and later co-founded SatoshiLabs with Pavol Rusnák, which produced the Trezor Model One in 2014: the first dedicated Bitcoin hardware wallet. Trezor introduced the concept of a dedicated signing device that never exposes private keys to internet-connected computers. Slush Pool is separately notable as the pooled mining model that made participation accessible when solo mining became impractical.

**Sources:**
- Trezor / SatoshiLabs documentation (trezor.io)
- Slush Pool history (braiins.com)
- Trezor Model One launch documentation (2014)

---

## Ledger — Éric Larchevêque & team (dates unknown)
**Tier:** 2
**Role:** Hardware Wallet Manufacturer
**Active:** 2014–present

French company founded in 2014 that produced the Nano series of hardware wallets, which became the world's best-selling Bitcoin and crypto hardware wallets with millions of devices shipped. In 2020, Ledger suffered a customer data breach that exposed the personal information — names, addresses, phone numbers — of over 270,000 customers, leading to documented phishing attacks and physical threats against holders. In 2023, Ledger announced "Ledger Recover," an optional seed phrase backup service that would allow Ledger to shard and store user seed phrases in escrow; the announcement generated significant backlash from the Bitcoin community on the grounds that it contradicted the foundational hardware wallet guarantee that the seed never leaves the device. Ledger paused the rollout following the backlash but did not abandon the feature.

**Sources:**
- Ledger company documentation (ledger.com)
- Ledger data breach reporting (2020) — 270,000+ customer records
- Ledger Recover announcement and community backlash (2023)

---

## Coldcard / Coinkite — NVK / Rodolfo Novak (dates unknown)
**Tier:** 2
**Role:** Hardware Wallet Developer / Bitcoin-Only Security Advocate
**Active:** 2017–present

Canadian Bitcoin developer and entrepreneur (known online as NVK) who founded Coinkite and created Coldcard, a Bitcoin-only hardware wallet with air-gapped signing via microSD card, early PSBT (BIP-174) support, and a design philosophy that assumes the connected computer may be compromised. Coldcard's Bitcoin-only focus and emphasis on adversarial threat modeling have made it a reference point in Bitcoin self-custody discussions. NVK has been a vocal public critic of competitors' security decisions, including Ledger's 2023 Recover announcement.

**Sources:**
- Coldcard documentation (coldcard.com)
- Coinkite product history
- NVK public statements on Bitcoin security and Ledger Recover criticism
- PSBT (BIP-174) specification

---

## Nick Neuman — Casa (dates unknown)
**Tier:** 2
**Role:** CEO, Casa / Bitcoin Self-Custody Platform
**Active:** 2018–present

CEO of Casa, a Bitcoin self-custody company co-founded with Jameson Lopp that produces tiered multisig vault products — including 2-of-3 and 3-of-5 key setups — designed for individual users without requiring deep technical knowledge. Neuman led the development of the Casa Covenant inheritance protocol, which provides a multisig-based approach to Bitcoin succession planning, and the Key Shield key recovery service. Casa is documented as a reference implementation for consumer-grade collaborative custody.

**Sources:**
- Casa documentation and product history (keys.casa)
- Casa Covenant inheritance protocol documentation
- Casa Key Shield documentation
- Cross-reference: Jameson Lopp entry (co-founder)

---

## Joseph Kelly — Unchained (dates unknown)
**Tier:** 3
**Role:** Co-Founder & CEO, Unchained
**Active:** 2016–present

Co-founded Unchained (formerly Unchained Capital), a Bitcoin-only financial services company specializing in collaborative multisig custody, Bitcoin-backed loans, and inheritance planning. Unchained's collaborative custody model holds one key of a multisig arrangement but never controls funds unilaterally, offering users the ability to self-custody while retaining a backup key at Unchained. Bitcoin-backed loans are a core product, providing liquidity without requiring customers to sell their holdings. Parker Lewis's "Gradually, Then Suddenly" essay series was written during his time at Unchained.

**Sources:**
- Unchained documentation (unchained.com)
- Unchained collaborative multisig whitepaper
- Bitcoin-backed loan product documentation

---

## Phil Geiger — Unchained Inheritance Planning (dates unknown)
**Tier:** 2
**Role:** Bitcoin Estate Planning Advocate / Unchained Education
**Active:** 2019–present

Unchained's head of education who became a prominent public voice on Bitcoin inheritance and estate planning, authoring guides on how to pass Bitcoin to heirs through multisig structures integrated with legal instruments such as trusts and wills. Geiger's work at Unchained documented multisig-based inheritance approaches that address the documented problem of self-custodied Bitcoin becoming inaccessible to heirs without proper succession planning. His public writing has been cited within the Bitcoin self-custody community.

**Sources:**
- Unchained inheritance planning guides and documentation (unchained.com)
- Phil Geiger's public writing on Bitcoin estate planning
- Unchained collaborative multisig inheritance protocol
- Cross-reference: Joseph Kelly entry (Unchained CEO)

---

## Parker Lewis (dates unknown)
**Tier:** 3
**Role:** Bitcoin Writer / Unchained Capital
**Active:** 2019–present

Authored the "Gradually, Then Suddenly" essay series (2019–2020), a widely circulated explanation of Bitcoin's monetary properties later compiled into a book, written while working at Unchained, a Bitcoin-only financial services company. The series takes its title from Hemingway's description of how bankruptcy occurs and applies a similar framework to Bitcoin's adoption trajectory. The essays were widely distributed in Bitcoin circles as an onboarding resource for readers seeking a monetary economics argument rather than a technical or investment case.

**Sources:**
- "Gradually, Then Suddenly" essay series (2019–2020) — Parker Lewis (unchained.com)
- *Gradually, Then Suddenly* (book compilation) — Parker Lewis
- Unchained Capital / Unchained documentation

---

## Álvaro D. María — *La Filosofía de Bitcoin* (dates unknown)
**Tier:** 3
**Role:** Bitcoin Author / Spanish-Language Bitcoin Intellectual
**Active:** 2022–present

Authored *La Filosofía de Bitcoin* (*The Philosophy of Bitcoin*), a Bitcoin book written originally in Spanish that approaches the subject from philosophical and humanistic starting points rather than economic or technical framing. The book is widely read in Spanish-speaking Bitcoin communities and has been cited within Latin American and Iberian Bitcoin intellectual discourse as a distinct contribution to the field. It stands alongside a small body of original Spanish-language Bitcoin writing serving adoption communities across El Salvador, Argentina, and other regions where Bitcoin use has been documented at scale.

**Sources:**
- *La Filosofía de Bitcoin* — Álvaro D. María (publication documentation)
- Spanish-language Bitcoin media coverage and reception
- Coverage: Bitcoin Magazine en Español, Nostr

---

## Jimmy Song (dates unknown)
**Tier:** 3
**Role:** Bitcoin Developer / Educator / Author
**Active:** 2013–present

Bitcoin developer, educator, and author of *Programming Bitcoin* (2019), a hands-on book for software developers building Bitcoin from scratch in Python. Song taught in-person and online Bitcoin development bootcamps and co-founded Base58, a Bitcoin protocol school. He has been a consistent public critic of altcoin projects, making technical arguments against their design and business models in writing and on podcasts.

**Sources:**
- *Programming Bitcoin* (2019) — Jimmy Song (O'Reilly)
- Base58 Bitcoin protocol school documentation
- Song's writing, podcast appearances, and public commentary on altcoins

---

## Yan Pritzker (dates unknown)
**Tier:** 3
**Role:** Co-founder, Swan Bitcoin / Author
**Active:** 2019–present

Co-founded Swan Bitcoin, a Bitcoin-only recurring purchase platform focused on dollar-cost averaging, and authored *Inventing Bitcoin* (2019), a short book that walks readers through Bitcoin's technical design from first principles, explaining the rationale behind each design decision. *Inventing Bitcoin* was widely distributed in the Bitcoin community as an onboarding text for technically curious readers who wanted to understand how Bitcoin works without requiring developer-level depth. Swan Bitcoin built automated purchasing infrastructure for long-term Bitcoin accumulation at a time when most major exchanges were diversifying into altcoins.

**Sources:**
- *Inventing Bitcoin* (2019) — Yan Pritzker
- Swan Bitcoin documentation (swanbitcoin.com)
- Pritzker's public writing and podcast appearances

---

## Dhruv Bansal (dates unknown)
**Tier:** 3
**Role:** Bitcoin Writer / Co-founder, Unchained
**Active:** 2014–present

Co-founded Unchained Capital (now Unchained), a Bitcoin-only collaborative custody and financial services company, and authored the "Bitcoin Astronomy" essay series, long-form writing that examines Bitcoin's proof-of-work through the frameworks of thermodynamics and physics. The series has been cited by Bitcoin writers and analysts as a distinct analytical approach to the proof-of-work energy debate. His role at Unchained connects him to the collaborative multisig custody and Bitcoin inheritance planning work documented in other entries in this reference.

**Sources:**
- "Bitcoin Astronomy" essay series — Dhruv Bansal (unchained.com)
- Unchained Capital / Unchained documentation (cross-reference)
- Bansal's collected writing

---

## Erik Cason (dates unknown)
**Tier:** 3
**Role:** Bitcoin Philosopher / Writer / Cypherpunk Thinker
**Active:** 2019–present

Author of "Cryptosovereignty" and other essays exploring Bitcoin through the lens of individual sovereignty, the cypherpunk tradition, and political philosophy. His writing draws on political philosophy, Austrian economics, and cypherpunk history to frame Bitcoin as a tool of personal sovereignty rather than primarily a financial or investment instrument. The "Cryptosovereignty" essay is cited in Bitcoin philosophical writing and on Nostr and represents a strand of Bitcoin thought that connects directly to the cypherpunk tradition.

**Sources:**
- "Cryptosovereignty" essay — Erik Cason
- Cason's collected writing and social media
- Coverage: Bitcoin Magazine, Nostr

---

## Jeff Booth (dates unknown)
**Tier:** 3
**Role:** Entrepreneur / Author / Bitcoin Thinker
**Active:** 2019–present

Canadian entrepreneur and author of *The Price of Tomorrow* (2020), which argued that technology is fundamentally deflationary and that central bank inflation policy is in structural conflict with that trend; Bitcoin, in Booth's framework, is the monetary system compatible with a deflationary technological future. The book was widely cited in the Bitcoin community and led Booth to co-found Ego Death Capital, a Bitcoin-only venture fund focused on the Lightning ecosystem. His background as a builder and seller of BuildDirect, a large e-commerce company, distinguished his arguments from those originating in academic economics.

**Sources:**
- *The Price of Tomorrow* (2020) — Jeff Booth
- Ego Death Capital portfolio and documentation (cross-reference)
- Booth's podcast appearances and public writing

---

## Saifedean Ammous (1980–present)
**Tier:** 3
**Role:** Economist / Author / Bitcoin Theorist
**Active:** 2015–present

Authored *The Bitcoin Standard* (2018), a widely read book making the economic case for Bitcoin as hard money within an Austrian economics framework, and *The Fiat Standard* (2021), a follow-up examining the fiat monetary system. *The Bitcoin Standard* placed Bitcoin in the Misesian and Hayekian tradition of sound money and has been cited by corporate Bitcoin adopters including Michael Saylor as an influence on their thinking. Ammous also hosts the Bitcoin Standard Podcast and has continued writing in the Austrian economics tradition.

**Sources:**
- *The Bitcoin Standard* (2018) — Saifedean Ammous
- *The Fiat Standard* (2021) — Saifedean Ammous
- The Bitcoin Standard Podcast

---

## Michael Saylor (1969–present)
**Tier:** 3
**Role:** Corporate Bitcoin Advocate / Investor
**Active:** 2020–present

Converted MicroStrategy's corporate treasury to Bitcoin beginning in August 2020 with an initial purchase of $250 million, establishing and publicly documenting a corporate Bitcoin treasury strategy that other public companies subsequently adopted. Saylor became the most prominent institutional advocate for corporate Bitcoin adoption and has continued accumulating Bitcoin for MicroStrategy's balance sheet through subsequent market cycles. His public commentary and educational materials on Bitcoin have addressed corporate treasury managers and institutional investors rather than retail or cypherpunk audiences.

**Sources:**
- MicroStrategy Bitcoin treasury announcements (2020–present)
- *What is Money?* podcast appearances (Robert Breedlove)
- Saylor Academy / Bitcoin for Corporations materials

---

## Brian Armstrong (1983–present)
**Tier:** 3
**Role:** Co-Founder & CEO, Coinbase
**Active:** 2012–present

Co-founded Coinbase (2012), which became the largest and most regulated U.S. Bitcoin and crypto exchange, and took it public on Nasdaq in 2021. Coinbase pursued a compliance-focused model that made it accessible to mainstream U.S. users and drew consistent criticism from Bitcoin privacy advocates who viewed its KYC requirements and data practices as surveillance chokepoints. Armstrong's 2020 internal memo stating that Coinbase would not engage in political activism as a company generated significant public commentary. Coinbase was subject to an SEC enforcement action filed in 2023.

**Sources:**
- *The Coinbase Story* — various profiles (WSJ, Bloomberg)
- Coinbase S-1 (2021)
- Armstrong's "Coinbase is not a political activist organization" post (2020)

---

## Rob Witoff (dates unknown)
**Tier:** 2
**Role:** Bitcoin Infrastructure Engineer / Coinbase Chief Architect / Cold Storage Pioneer
**Active:** 2014–present

Engineer and infrastructure architect who joined Coinbase in 2014 and served as Chief Architect, leading security and infrastructure development during a formative period of Coinbase's growth. Before entering the Bitcoin space, Witoff held engineering roles at NASA's Jet Propulsion Laboratory, where he served as lead engineer on the International Space Station's laser communication system (OPALS), and contributed to SpaceX's launch capabilities and Space Station systems engineering. He holds a degree in aerospace engineering from the University of Colorado Boulder. After his first stint at Coinbase, he co-founded Unit 410, which became an industry-leading provider of institutional self-custody wallets and staking infrastructure; Coinbase acquired Unit 410 in 2021. Following the acquisition, Witoff rejoined Coinbase as Head of Platform. He also served as CTO of Polychain Capital. His work at Coinbase on cold storage and security infrastructure in the 2014–2017 period coincided with an era when exchange hacks — including Mt. Gox — made custodial security a central concern for the industry.

**Sources:**
- Coinbase blog — "Welcome Rob Witoff to the Coinbase Exec Team"
- QCon New York 2017 — Rob Witoff speaker profile
- FX News Group — Rob Witoff rejoins Coinbase as Head of Platform
- Crunchbase — Rob Witoff / Unit 410

---

## Jihan Wu & Bitmain (Wu: 1986–present)
**Tier:** 3
**Role:** ASIC Manufacturer / Mining Industrialist
**Active:** 2013–present

Co-founded Bitmain in 2013, which became the dominant Bitcoin ASIC manufacturer and at its peak controlled the majority of global mining hardware production and a substantial share of hashrate through its own pools. Bitmain's Antminer series industrialized Bitcoin mining at scale, and Wu was a prominent big-block advocate and Bitcoin Cash supporter, giving him significant influence during the blocksize war. His Chinese translation of the Bitcoin whitepaper was among the first and contributed to Bitcoin's adoption in China's technical community. Bitmain filed a withdrawn S-1 in 2018; Wu was subsequently removed from leadership before later founding Bitdeer.

**Sources:**
- *The Blocksize War* — Jonathan Bier
- Bitmain S-1 filing (2018, withdrawn)
- Various profiles: Bloomberg, WSJ, CoinDesk

---

## Butterfly Labs (founded 2012)
**Tier:** 3
**Role:** Bitcoin Mining Hardware Manufacturer / FTC Enforcement Case
**Active:** 2012–2016

A Kansas City-based company founded in 2012 by Nasser Ghoseiri and Sonny Vleisides that became one of the first to announce Bitcoin ASIC mining hardware. Butterfly Labs accepted pre-orders from thousands of customers but repeatedly delayed shipments — in many cases mining Bitcoin with customers' hardware before shipping it, or failing to deliver at all. The FTC alleged the company took between $20 million and $50 million in customer funds through unfair and deceptive practices. The FTC obtained a court order halting operations in September 2014 and the company settled in May 2016, paying a $15,000 fine with founders barred from cryptocurrency-related business for three years. The case became a documented cautionary example of pre-order fraud in the early Bitcoin mining hardware market. Co-founder Sonny Vleisides had previously pleaded guilty to mail fraud in an unrelated lottery scam.

**Sources:**
- FTC press release and court order (September 2014)
- FTC settlement documentation (May 2016)
- Bitcoin Wiki — Butterfly Labs
- Forbes / Kashmir Hill coverage (2014)

---

## Yifu Guo & Avalon / Canaan Creative (founded 2012)
**Tier:** 2
**Role:** First Commercial Bitcoin ASIC / Hardware Manufacturer
**Active:** 2012–present

The Avalon project, started in late 2012 by NG Zhang (张楠赓), Jiaxuan Li, and Xiangfu Liu, produced the first commercially available Bitcoin ASIC miner — a purpose-built 110nm chip that rendered GPU mining economically obsolete. Yifu Guo served as the public-facing sales and marketing representative for Avalon in its first year, becoming the recognizable name in Western Bitcoin communities before departing the project in 2013. Canaan Creative, the company founded by NG Zhang and team, took over the Avalon brand in 2014 and grew into one of the major Bitcoin mining hardware manufacturers, eventually listing on NASDAQ (CAN) in 2019. The Avalon ASIC's release triggered the industrial mining era.

**Sources:**
- Bitcoin Wiki — Avalon
- Motherboard/Vice interview with Yifu Guo (2013)
- Canaan Creative (canaan.io)
- BitcoinTalk Avalon thread (2012)

---

## Friedcat / Jiang Xinyu (1986–present)
**Tier:** 3
**Role:** ASIC Pioneer / Mining Hardware Designer
**Active:** 2012–2013

Jiang Xinyu, operating under the pseudonym Friedcat, designed the first commercially successful Bitcoin ASIC chips via ASICMiner. Born in 1986 in Shaoyang, Hunan Province, China, he posted the first photos of ASICMiner's chip carrier on Bitcointalk on December 28, 2012 — beginning mining before Avalon shipped its hardware to customers. On May 4, 2013, ASICMiner released the Block Erupter USB, the first Bitcoin ASIC in a USB form factor, which sold for approximately $13 each and briefly democratized small-scale mining. ASICMiner at its peak held approximately 42% of the entire Bitcoin network's hashrate; Friedcat voluntarily shed hashrate to keep it below 20% in response to documented community concerns about a potential 51% attack. He subsequently withdrew from public activity and his whereabouts remain undocumented.

**Sources:**
- ASICMiner Bitcointalk thread (2012–2013)
- *Digital Gold* — Nathaniel Popper
- "The Other Bitcoin Mystery: Where's Friedcat?" — siggy47, Stacker News

---

## AntPool — Bitmain (founded 2014)
**Tier:** 2
**Role:** Bitcoin Mining Pool
**Active:** 2014–present

Launched by Bitmain in 2014 to provide mining pool services to operators of its Antminer hardware line. AntPool grew alongside Bitmain's dominance of the ASIC hardware market and became one of the largest Bitcoin mining pools globally, consistently commanding 15–30% of total network hashrate. As of 2026 it remains among the two or three largest pools alongside Foundry USA and F2Pool. Bitmain also operated BTC.com as a separate pool during the same period.

**Sources:**
- Bitmain company documentation (bitmain.com)
- AntPool documentation (antpool.com)
- Cross-reference: Jihan Wu & Bitmain entry

---

## Poolin — Kevin Pan, Zhibiao Pan, Fa Zhu & Tianzhao Li (founded 2018)
**Tier:** 2
**Role:** Bitcoin Mining Pool
**Active:** 2018–present

Founded in 2018 by Kevin Pan, Zhibiao Pan, Fa Zhu, and Tianzhao Li — all former Bitmain and BTC.com employees. Zhibiao Pan had previously founded TangPool (2014) before running BTC.com at Bitmain; he and his co-founders departed Bitmain in 2017. Bitmain subsequently sued three of the founders for violating non-compete agreements. Poolin grew into one of the largest Bitcoin mining pools during 2019–2021. In September 2022, Poolin publicly acknowledged liquidity issues, suspending withdrawals — a documented case of pool-level financial stress during the 2022 market downturn.

**Sources:**
- Bitcoin Wiki — Poolin
- CoinDesk — Poolin liquidity issues (September 2022)
- Bitcoin Magazine — Poolin profile
- Bitmain lawsuit documentation (2019)

---

## Discus Fish / Mao Shihang & Chun Wang — F2Pool (founded 2013)
**Tier:** 2
**Role:** Bitcoin Mining Pool Co-Founders
**Active:** 2013–present

Mao Shihang (known online as Discus Fish) and Chun Wang co-founded F2Pool in May 2013, one of the first and longest-running Bitcoin mining pools. Wang coded the backend infrastructure; Mao handled operations. F2Pool grew to command approximately one-third of Bitcoin's global hashrate at its peak and has mined over 1.3 million BTC — more than 9% of all Bitcoin blocks ever produced. Chun Wang also co-founded Stakefish (2018) and funded and commanded the SpaceX Fram2 polar orbit mission (2025), becoming the first Maltese citizen to travel to space. F2Pool remains one of the largest active mining pools in Bitcoin's history.

**Sources:**
- Wikipedia — Chun Wang
- F2Pool documentation (f2pool.com)
- Bitcoin Magazine — Chun Wang profile
- CoinDesk coverage

---

## Jered Kenna — Tradehill (dates unknown)
**Tier:** 3
**Role:** Bitcoin Exchange Founder
**Active:** 2011–2013 (Bitcoin-relevant)

A former U.S. Marine who founded Tradehill in June 2011, one of the earliest U.S. Bitcoin exchanges and at its peak the second-largest Bitcoin exchange in the world behind Mt. Gox, handling approximately a quarter of all global Bitcoin transactions. Tradehill suspended operations in February 2012 after payment processor Dwolla removed over $100,000 from the exchange's account without notice, leaving staff unpaid for months. The exchange briefly relaunched before permanently closing in August 2013 amid ongoing regulatory and financial pressures. Kenna subsequently relocated to Colombia, where he pursued other entrepreneurial ventures.

**Sources:**
- Tradehill exchange history documentation
- Bitcoin.com profile (2015)
- "Tradehill: A Rollercoaster Ride in Early Bitcoin" — Kevin Finnerty (Medium)

---

## Jesse Powell (1980–present)
**Tier:** 3
**Role:** Co-Founder & CEO, Kraken
**Active:** 2011–present

Founded Kraken (2011), one of the oldest continuously operating Bitcoin exchanges, with a documented security and regulatory compliance record. Powell was present at Mt. Gox during the hack and has cited that experience as formative in Kraken's emphasis on security and proof of reserves. He has been a public voice on regulation and exchange integrity, and his 2022 departure from the CEO role followed public controversy over statements he made on social media.

**Sources:**
- Kraken company history (kraken.com)
- Powell's public statements and interviews
- Mt. Gox witness accounts

---

## Wences Casares (1974–present)
**Tier:** 3
**Role:** Entrepreneur / Bitcoin Evangelist / Xapo Founder
**Active:** 2013–present

Founded Xapo (2014), a Bitcoin vault and custody service, and became an early Bitcoin explainer to Silicon Valley technology executives and venture capitalists — conversations he has described publicly. His background growing up in Argentina through hyperinflation and currency crises informed his arguments for Bitcoin as a savings tool. Xapo's cold storage vault became a custody solution for large Bitcoin holders, and his essay "Bet on Bitcoin" is a documented statement of a long-term Bitcoin monetization thesis.

**Sources:**
- "Bet on Bitcoin" — Wences Casares (essay)
- *Digital Gold* — Nathaniel Popper
- Xapo company history

---

## Cory Klippsten (1976–present)
**Tier:** 3
**Role:** Founder & CEO, Swan Bitcoin
**Active:** 2019–present

Founded Swan Bitcoin (2019), a Bitcoin-only recurring purchase platform focused on automated dollar-cost averaging for long-term savings, at a time when most exchanges were diversifying into the broader crypto market. Klippsten has been a consistent public critic of altcoins and a vocal advocate for Bitcoin-only financial products. Swan Bitcoin's Bitcoin-only model distinguished it operationally from multi-asset exchanges; Klippsten's public commentary on the crypto industry has been documented across podcasts, social media, and Bitcoin media.

**Sources:**
- Swan Bitcoin company history (swanbitcoin.com)
- Klippsten's public writing and podcast appearances
- Unchained Capital / Swan partnership documentation

---

## River Financial — Alex Leishman (founded 2019)
**Tier:** 3
**Role:** Bitcoin-Only Brokerage / Custody / Financial Services
**Active:** 2019–present

Bitcoin-only financial services company founded in 2019 by Alex Leishman, who holds degrees in aerospace engineering and computer science from Stanford. Leishman's background includes early work at MaiCoin, a Taiwanese Bitcoin exchange, followed by graduate research at Stanford where he assisted with Dan Boneh's Bitcoin and cryptography courses, and subsequent work building custody infrastructure at Polychain Capital. River is built exclusively around Bitcoin and offers brokerage with zero-fee recurring purchases, full-reserve custody with Proof of Reserves, Lightning Network wallets, and Bitcoin mining services. The company raised $35 million in a Series B round in May 2023 led by Kingsway Capital, with participation from Peter Thiel, Valor Equity Partners, Goldcrest, and others, bringing total funding to approximately $70 million. River publishes an annual Bitcoin adoption report tracking corporate and institutional Bitcoin accumulation trends.

**Sources:**
- river.com
- Bitcoin Magazine — "River: A Bitcoin Brokerage Built From The Ground Up"
- CoinDesk — "Peter Thiel Backs Bitcoin Startup River in $35M Round" (May 2023)
- PR Newswire — River Series B announcement (2023)
- River Business Bitcoin Adoption Report (2024)

---

## David Bailey (1990–present)
**Tier:** 3
**Role:** CEO, BTC Inc / Bitcoin Magazine
**Active:** 2012–present

Acquired and built Bitcoin Magazine into Bitcoin's most prominent media brand, and founded BTC Inc as a Bitcoin-focused media and events conglomerate that organizes the annual Bitcoin Conference in cities including Miami and Nashville. Bitcoin Magazine was Vitalik Buterin's early publishing venue before he founded Ethereum. Bailey has been documented as facilitating Bitcoin-related outreach to the Trump campaign in 2024, and the annual conference has become a venue where major Bitcoin-related policy and corporate announcements have been made.

**Sources:**
- Bitcoin Magazine history (bitcoinmagazine.com)
- BTC Inc company documentation
- Bitcoin Conference coverage (2019–present)

---

## James McCarthy / Nefario (dates unknown)
**Tier:** 3
**Role:** Founder, Global Bitcoin Stock Exchange (GLBSE)
**Active:** 2011–2012

Founded the Global Bitcoin Stock Exchange (GLBSE) in May 2011 — the first Bitcoin securities and bond exchange, using Ricardian contracts to represent shares and debt instruments. GLBSE operated for over a year before McCarthy shut it down in October 2012 under regulatory pressure, returning funds to users. The exchange represented one of the earliest attempts at Bitcoin-denominated capital market infrastructure and predated the tokenized asset platforms that emerged in subsequent years.

**Sources:**
- Bitcoin Magazine: Interview with Nefario (2012)
- GLBSE documentation and Bitcoin Wiki history

---

## Trendon Shavers / pirateat40 (dates unknown)
**Tier:** 3
**Role:** Fraudster / Inadvertent Legal Precedent
**Active:** 2011–2012

Ran Bitcoin Savings and Trust (2011–2012), a Ponzi scheme on Bitcointalk promising 7% weekly returns, collecting over 700,000 BTC before collapsing. His prosecution — SEC v. Shavers (2013) — produced the first U.S. federal court ruling that Bitcoin constitutes money for purposes of securities law, a foundational legal precedent that influenced subsequent regulatory actions across the crypto industry. The fraud cost the early Bitcoin community a significant fraction of circulating supply at the time.

**Sources:**
- SEC v. Shavers (2013) — court documents
- Bitcointalk: Bitcoin Savings and Trust thread
- Bitcoin Wiki: Trendon Shavers

---

## Bobby Lee (dates unknown)
**Tier:** 3
**Role:** Co-Founder, BTCC / Bitcoin Entrepreneur
**Active:** 2011–present

A Stanford-trained computer scientist who co-founded BTCC (Bitcoin China) in June 2011 alongside Yang Linke and Huang Xiaoyu — China's first Bitcoin exchange. BTCC grew to become the largest Bitcoin exchange in the world by volume in November 2013, briefly surpassing Mt. Gox with approximately 31.7% market share. The exchange shut down trading in September 2017 following China's People's Bank announcement banning initial coin offerings, and was sold to an undisclosed Hong Kong firm in January 2018. Bobby Lee is the brother of Charlie Lee, the creator of Litecoin. After BTCC, he founded Ballet, a company producing physical Bitcoin wallets, and authored *The Promise of Bitcoin* (2021).

**Sources:**
- BTCC founding documentation
- Wikipedia — BTCC
- *The Promise of Bitcoin* — Bobby Lee (2021)
- CNBC and CoinTelegraph coverage (2017–2018)

---

## Charlie Lee (1977–present)
**Tier:** 3
**Role:** Developer / Litecoin Creator
**Active:** 2011–present

Created Litecoin (October 2011), the first significant Bitcoin-derived altcoin to achieve long-term survival, while working at Google; later served as Coinbase engineering director before going full-time on Litecoin. In December 2017, near the market peak, he publicly sold his entire Litecoin holdings, stating that his position as creator created a conflict of interest — a documented act that generated significant discussion about founder conflicts in token projects. Litecoin has been used as a technical testing ground, deploying SegWit and Lightning Network support before those features were activated on Bitcoin.

**Sources:**
- Litecoin launch thread — Bitcointalk (October 2011)
- Lee's conflict-of-interest statement (December 2017)
- Wikipedia: Charlie Lee

---

## Cash App Bitcoin — Block Inc. (launched 2018)
**Tier:** 3
**Role:** Bitcoin Retail Onramp / Payment Platform
**Active:** 2018–present

Block's Cash App added Bitcoin buying in January 2018, becoming one of the largest and most accessible Bitcoin purchase platforms in the U.S. and serving millions of retail users. Bitcoin revenue became a significant and publicly reported portion of Block's total revenue, documented in quarterly earnings filings. Cash App later added Lightning Network withdrawals, making it one of the first mainstream consumer applications to support both custodial Bitcoin purchase and non-custodial Lightning withdrawals.

**Sources:**
- Cash App Bitcoin feature launch documentation (January 2018)
- Block Inc. quarterly earnings reports (Bitcoin revenue)
- Cash App Lightning Network withdrawal documentation

---

## Square / Block Terminal & Bitcoin Commerce (founded 2009)
**Tier:** 3
**Role:** Merchant Payment Infrastructure / Bitcoin Commerce
**Active:** 2009–present (Bitcoin integration from 2018)

Square's point-of-sale hardware and software, used by millions of merchants, has been progressively integrated with Bitcoin capabilities under Block's stated Bitcoin-first mission. Block's TBD division has worked on decentralized financial infrastructure connecting Bitcoin to broader payment systems. Full Bitcoin payment integration at the merchant terminal level has been gradual, and the scope of Square's Bitcoin commerce integration is documented in Block Inc. public communications and product announcements.

**Sources:**
- Block Inc. / Square terminal documentation
- TBD (Block's decentralized finance division) documentation
- Block Inc. Bitcoin strategy communications

---

## Bitkey — Block Inc. (launched December 2023)
**Tier:** 2
**Role:** Bitcoin Hardware Wallet / Consumer Self-Custody
**Active:** 2023–present

Block launched Bitkey in December 2023 — a Bitcoin hardware wallet using a 2-of-3 multisig model in which the three keys are held by: the user's mobile phone, the Bitkey hardware device, and Block's recovery server. No single key, including Block's, can move funds unilaterally. Block holds one key for recovery purposes — a trust assumption that some Bitcoin self-custody advocates have noted publicly — enabling account recovery when users lose devices or forget PINs. The product's fingerprint sensor and mobile-first design target mainstream consumer users rather than technically experienced Bitcoiners.

**Sources:**
- Bitkey launch documentation (bitkey.build)
- Bitkey 2-of-3 multisig architecture documentation
- Block Inc. Bitkey product communications (December 2023)

---

## Jack Dorsey (1976–present)
**Tier:** 3
**Role:** Tech Founder / Bitcoin Advocate / Nostr Funder
**Active:** 2018–present

Former Twitter/X CEO who founded Block Inc. (formerly Square) with a stated Bitcoin-first mission; built Cash App into one of the largest Bitcoin purchase platforms in the U.S.; launched Bitkey (a Bitcoin hardware wallet); funded Nostr development with 14 BTC in 2022; and funds Bitcoin open-source development through Spiral (formerly Square Crypto), which has supported core Bitcoin and Lightning developers including Gloria Zhao. His public statements have drawn a consistent line between Bitcoin and the broader crypto industry. See also: Cash App Bitcoin, Bitkey, and Square/Block terminal entries.

**Sources:**
- Block Inc. / Spiral Bitcoin developer funding documentation
- Dorsey's Nostr funding announcement (2022)
- Dorsey's congressional testimony and public statements on Bitcoin

---

## Matt Odell (dates unknown)
**Tier:** 3
**Role:** Podcaster / Privacy Advocate / BitDevs Organizer
**Active:** 2017–present

Co-host of Citadel Dispatch and Tales from the Crypt, and co-organizer of Bitcoin Park Nashville and its BitDevs meetup. Odell's podcast work has consistently emphasized privacy practices — running your own node, CoinJoin, avoiding KYC where possible — and has documented Bitcoin self-custody and circular economy practices for a broad audience. Bitcoin Park Nashville became a physical hub for Bitcoin development and community gatherings distinct from large industry conference formats.

**Sources:**
- Citadel Dispatch (citadeldispatch.com)
- Bitcoin Park Nashville documentation
- Tales from the Crypt podcast archive

---

## Giacomo Zucco (dates unknown)
**Tier:** 3
**Role:** Bitcoin Maximalist / Entrepreneur / Educator
**Active:** 2013–present

Italian Bitcoin entrepreneur, founder of BHB Network (a Bitcoin consultancy), and a prolific speaker and educator at Bitcoin conferences worldwide. He is associated with the RGB protocol — a smart contract and asset layer built on top of Bitcoin using client-side validation, designed to add programmability to Bitcoin without base layer protocol changes. His public writing and speaking addresses technical and economic arguments for a Bitcoin-only position, and he writes and speaks in both English and Italian with documented engagement in European Bitcoin communities.

**Sources:**
- BHB Network documentation and conference talks
- RGB protocol documentation and development history
- Zucco's writing, interviews, and public debates on Bitcoin maximalism

---

## Eric Voskuil (dates unknown)
**Tier:** 3
**Role:** Bitcoin Developer / Economic Theorist
**Active:** 2014–present

Bitcoin developer and author of *Cryptoeconomics*, a comprehensive treatise developing an economic theory of Bitcoin's security model, mining incentives, fee market dynamics, and the long-term security budget problem — the question of whether transaction fees alone can sustain sufficient mining security as the block subsidy approaches zero. His work is published as a free online book and is cited in Bitcoin developer and analyst discussions of long-term monetary policy and mining incentive structures. Voskuil is also a maintainer of the Libbitcoin node implementation (cross-reference: Amir Taaki entry).

**Sources:**
- *Cryptoeconomics* — Eric Voskuil (GitHub / libbitcoin.info)
- Voskuil's writing on Bitcoin security budget and fee market
- Libbitcoin project (cross-reference: Amir Taaki entry — Voskuil is a Libbitcoin maintainer)

---

## Udi Wertheimer (dates unknown)
**Tier:** 3
**Role:** Bitcoin Developer / Provocateur / Ordinals Advocate
**Active:** 2017–present

Israeli Bitcoin developer and commentator known for contrarian commentary on Bitcoin culture and for being one of the most prominent proponents of Ordinals and Bitcoin NFTs. Co-created Taproot Wizards, an Ordinals-based project that made a point of maximizing block space usage. His Ordinals advocacy directly connects to the Rodarmor/Ordinals and Core/Knots controversy entries in this document, and the underlying debate — whether Bitcoin's block space is exclusively for monetary transactions or for whatever users will pay fees to include — is a defining protocol argument of the post-Taproot era.

**Sources:**
- Taproot Wizards documentation and Ordinals advocacy
- Wertheimer's writing and social media commentary
- Coverage of Ordinals / Core / Knots controversy (cross-reference: Rodarmor entry)

---

## Dan Held (dates unknown)
**Tier:** 3
**Role:** Bitcoin Writer / Growth Marketer / Podcaster
**Active:** 2018–present

Bitcoin writer best known for the "Planting Bitcoin" essay series (2018–2019), which reconstructed Satoshi Nakamoto's design choices and argued that Bitcoin's launch was a series of deliberate decisions to ensure maximum decentralization before the network could be captured or shut down. Held has also worked in growth and marketing roles at Kraken and other Bitcoin companies and hosts *The Dan Held Show*. The "Planting Bitcoin" series has been widely read in Bitcoin circles as an account of Satoshi's strategic deliberateness and has been cited in subsequent writing on Bitcoin's founding period.

**Sources:**
- "Planting Bitcoin" essay series (2018–2019) — Dan Held
- *The Dan Held Show* podcast
- Held's writing and public appearances at Kraken and beyond

---

## Laura Shin (dates unknown)
**Tier:** 3
**Role:** Bitcoin & Crypto Journalist / Podcaster / Author
**Active:** 2016–present

One of the earliest prominent mainstream journalists to cover Bitcoin seriously, working at Forbes before launching the *Unchained* podcast — a long-form interview show with founders, developers, and investors that reached mainstream finance audiences. Her book *The Cryptopians* (2022) covers the early crypto ecosystem including Mt. Gox, Roger Ver, and the forces that pulled the community away from Bitcoin toward Ethereum, and serves as a primary source for the period in which Bitcoin's early community fractured. Her journalism archive at CoinDesk and Forbes constitutes contemporaneous coverage of Bitcoin's formative years.

**Sources:**
- *The Cryptopians* (2022) — Laura Shin (PublicAffairs; Bitcoin-relevant sections)
- *Unchained* podcast archive (unchainedpodcast.com)
- Forbes crypto journalism archive (Shin byline)

---

## Zeke Faux (dates unknown)
**Tier:** 3
**Role:** Investigative Journalist / Author
**Active:** 2021–present (Bitcoin-relevant)

Bloomberg investigative journalist and author of *Number Go Up* (2023), which documents the 2020–2022 crypto boom and collapse, covering Tether, FTX, SBF, Celsius, and related entities through primary-source field reporting including travel to the Bahamas, Cambodia, and elsewhere. The book includes extended reporting on Tether's reserve opacity and systemic risk — the most detailed published account of that entity's dollar-backing claims — alongside reporting on FTX, celebrity endorsements, and other crypto industry practices. It was researched independently of privileged access to subjects, contrasting methodologically with Michael Lewis's *Going Infinite*.

**Sources:**
- *Number Go Up* (2023) — Zeke Faux (Crown)
- Faux's Bloomberg investigative journalism on Tether and FTX
- Faux's Cambodia crypto scam reporting

---

## Michael Lewis (dates unknown)
**Tier:** 3
**Role:** Author / Financial Journalist
**Active:** 2023 (Bitcoin-relevant)

Celebrated financial narrative author (*Liar's Poker*, *The Big Short*, *Flash Boys*) who wrote *Going Infinite* (2023), a biography of Sam Bankman-Fried and account of the FTX collapse based on privileged access to SBF before and during the collapse. The book was widely criticized within the Bitcoin and crypto communities for what reviewers characterized as insufficient scrutiny of SBF and the scale of the fraud, while providing the most detailed inside account of FTX's culture and Bankman-Fried's psychology. Lewis's mainstream literary prestige brought the FTX story to a substantially larger audience than any crypto-native reporting.

**Sources:**
- *Going Infinite* (2023) — Michael Lewis
- Lewis's *60 Minutes* SBF interview (pre-collapse)
- Community and critical response to *Going Infinite* (2023)

---

## Andy Greenberg (dates unknown)
**Tier:** 3
**Role:** Journalist / Author / Cybersecurity & Bitcoin Historian
**Active:** 2012–present

WIRED senior writer and author of multiple books at the intersection of Bitcoin, cypherpunks, and cybersecurity. *This Machine Kills Secrets* (2012) chronicled the history of WikiLeaks, cypherpunks, and digital privacy tools and serves as a primary non-Bitcoin-community source for the cypherpunk intellectual history covered in Tier 1 of this document. *Tracers in the Dark* (2022) documented how blockchain forensics investigators and federal investigators — including IRS-CI agent Tigran Gambaryan and Chainalysis co-founder Jonathan Levin — used on-chain data to identify and prosecute dark web market operators including Silk Road 2 and AlphaBay. Both books are based on primary-source reporting and court records.

**Sources:**
- *This Machine Kills Secrets* (2012) — Andy Greenberg (WIRED / Dutton)
- *Tracers in the Dark* (2022) — Andy Greenberg
- *Sandworm* (2019) — Andy Greenberg
- WIRED journalism archive (greenberg byline)

---

## Nathaniel Popper (dates unknown)
**Tier:** 3
**Role:** Journalist / Author / Bitcoin Historian
**Active:** 2013–present

New York Times financial journalist and author of *Digital Gold* (2015), the first serious long-form narrative history of Bitcoin's early years, covering 2009 through approximately 2014. The book was written for a mainstream audience and drew on original interviews and access to figures who had not spoken publicly before, covering Satoshi's identity, the early forum community, Mt. Gox, the Winklevoss twins, Silk Road, and the first wave of Bitcoin entrepreneurs. It is cited more frequently in this reference document than almost any source other than *The Blocksize War*.

**Sources:**
- *Digital Gold* (2015) — Nathaniel Popper (Penguin)
- Popper's New York Times Bitcoin and crypto journalism archive
- Original interviews with early Bitcoin figures (sourced in the book)

---

## Jonathan Bier (dates unknown)
**Tier:** 3
**Role:** Bitcoin Historian / Author
**Active:** 2021–present

Author of *The Blocksize War* (2021), an account of the 2015–2017 block size conflict reconstructed from primary sources, interviews, and contemporaneous records, documenting how the small-block position prevailed, the role of various actors (miners, developers, exchanges, users), and the governance mechanisms that determined the outcome. It is the only book-length treatment of the conflict and the primary secondary source for multiple entries in this document, including Gavin Andresen, Jeff Garzik, Mike Hearn, Theymos, Shaolinfry, and SegWit2x. It is among the most frequently cited sources in this reference.

**Sources:**
- *The Blocksize War* (2021) — Jonathan Bier
- Bier's research methodology and sourcing notes
- Bitcoin Core mailing list and forum archives (primary sources underlying the book)

---

## Simon Dixon (dates unknown)
**Tier:** 3
**Role:** Bitcoin Investor / Entrepreneur / Mt. Gox Creditor Advocate
**Active:** 2012–present

British Bitcoin investor and founder of BnkToTheFuture, an online equity crowdfunding platform that became a primary vehicle for early-stage Bitcoin and fintech company investment, allowing retail investors to back Bitcoin startups when traditional venture capital largely avoided the space. Dixon became one of the most prominent advocates for Mt. Gox creditors, spending years lobbying for a civil rehabilitation process that would allow creditors to be repaid in Bitcoin rather than fiat — a distinction worth billions of dollars given Bitcoin's price appreciation since 2014. His advocacy contributed to the civil rehabilitation outcome eventually reached by trustee Nobuaki Kobayashi.

**Sources:**
- BnkToTheFuture platform documentation (bnktothefuture.com)
- Mt. Gox civil rehabilitation proceedings and creditor advocacy
- Dixon's public commentary and interviews on Mt. Gox and Bitcoin investment

---

## Pete Rizzo (dates unknown)
**Tier:** 3
**Role:** Bitcoin Journalist / Historian / Editor
**Active:** 2013–present

Served as editor at CoinDesk during its formative years (2013–2018), producing contemporaneous coverage of the Mt. Gox collapse, the blocksize war, and early regulatory events; subsequently became editor at Bitcoin Magazine with an explicit Bitcoin-only editorial direction. His CoinDesk byline constitutes a primary source for Bitcoin's major events from 2013–2018, and his historical research on early Bitcoin figures and forum history has been cited by Bitcoin writers and researchers. His move from CoinDesk to Bitcoin Magazine is itself a documented editorial position during a period when Bitcoin publications faced pressure to broaden into general crypto coverage.

**Sources:**
- CoinDesk journalism archive (Rizzo byline, 2013–2018)
- Bitcoin Magazine long-form and historical journalism (Rizzo byline)
- Rizzo's Bitcoin history research and public writing

---

## Aaron van Wirdum (dates unknown)
**Tier:** 3
**Role:** Bitcoin Journalist / Historian / Author
**Active:** 2014–present

Dutch Bitcoin journalist and author of *The Genesis Book* (2024), a documented history of the intellectual precursors to Bitcoin tracing the ideas, people, and failed experiments from Chaum through Hashcash and b-money. Van Wirdum conducted primary source research including mailing list archives and interviews with surviving cypherpunk participants, filling a gap that earlier Bitcoin histories left open by not covering the pre-Satoshi era in depth. He also wrote for Bitcoin Magazine for years covering technical upgrades, protocol debates, and historical research, and *The Genesis Book* is a principal secondary source for this reference document's Tier 1 entries.

**Sources:**
- *The Genesis Book* (2024) — Aaron van Wirdum
- Bitcoin Magazine long-form journalism archive (van Wirdum byline)
- van Wirdum's research and interviews with cypherpunk era figures

---

## Shinobi (pseudonym, dates unknown)
**Tier:** 3
**Role:** Bitcoin Technical Writer / Developer / Educator
**Active:** 2018–present

Pseudonymous Bitcoin developer and technical writer who served as a technical editor and writer at Bitcoin Magazine, producing accessible explanations of Bitcoin protocol concepts — covering Taproot, Schnorr signatures, covenants, Lightning Network mechanics, and privacy tools for a technically engaged but non-developer audience. Also hosts the *Block Digest* podcast. His explanations of protocol upgrades and covenant proposals such as CTV and OP_VAULT have been cited as reference material in Bitcoin community discussions of those topics.

**Sources:**
- Bitcoin Magazine technical writing archive — Shinobi
- *Block Digest* podcast
- Shinobi's writing on Taproot, Schnorr, covenants, Lightning, and privacy

---

## Vijay Boyapati (dates unknown)
**Tier:** 3
**Role:** Bitcoin Writer / Monetary Economist
**Active:** 2018–present

Author of "The Bullish Case for Bitcoin" — published as a long-form essay on Medium in 2018 and later expanded into a book (2021) — which was widely shared as an onboarding document throughout the 2018–2021 period. The essay makes a monetary economics argument for Bitcoin adoption using a framework of money's properties and stages of monetization and has been translated into multiple languages. Boyapati has a documented background as a Google engineer.

**Sources:**
- "The Bullish Case for Bitcoin" essay (2018) — Vijay Boyapati (Medium)
- *The Bullish Case for Bitcoin* (book expansion) — Vijay Boyapati
- Boyapati's public writing and interviews

---

## Jason Lowery (dates unknown)
**Tier:** 3
**Role:** U.S. Space Force Officer / National Security Bitcoin Theorist
**Active:** 2022–present

U.S. Space Force officer and MIT graduate who authored *Softwar* (2023), a thesis submitted to MIT arguing that Bitcoin's proof-of-work is a form of digital power projection — a "softwar" capability allowing actors to impose real-world physical costs in cyberspace without kinetic violence — and that the United States should treat Bitcoin mining dominance as a national security priority analogous to other strategic deterrence capabilities. The thesis generated debate in both Bitcoin and defense policy circles and reached audiences in the Pentagon and defense establishment through a framing distinct from monetary or Austrian economics arguments for Bitcoin.

**Sources:**
- *Softwar* (2023) — Jason Lowery (MIT thesis)
- Lowery's public writing, interviews, and congressional testimony
- Coverage: Bitcoin Magazine, defense policy media, Nostr

---

## Troy Cross (dates unknown)
**Tier:** 3
**Role:** Philosophy Professor / Bitcoin Ethicist / Environmental Advocate
**Active:** 2021–present

Philosophy professor at Reed College who has written on the ethics of Bitcoin mining, its environmental impact, and the philosophical underpinnings of Bitcoin as a monetary system. He co-authored research with Daniel Batten on Bitcoin's actual carbon footprint, applying analytic philosophy methodology to questions typically addressed only with economic or engineering arguments. His collaboration with Batten combined philosophical rigor with Batten's empirical data on the Bitcoin mining energy mix and sustainable energy usage.

**Sources:**
- Cross and Batten collaborative research on Bitcoin environmental impact
- Troy Cross essays on Bitcoin ethics and philosophy
- Reed College faculty documentation
- Coverage: Bitcoin Magazine, Nostr, academic outlets

---

## Daniel Batten (dates unknown)
**Tier:** 3
**Role:** Bitcoin Environmental Researcher / Advocate
**Active:** 2021–present

New Zealand-based researcher and investor who has produced data-driven analysis of Bitcoin mining's actual energy mix, carbon intensity, and potential as a methane mitigation tool. Batten maintains a public dataset on Bitcoin's sustainable energy usage and has documented cases where Bitcoin miners capture and combust methane that would otherwise be vented or flared from landfills and oil wells. His research is cited in discussions of Bitcoin's environmental footprint alongside the Gridless/Africa stranded hydro mining work, which connects to his broader thesis about stranded and wasted energy as inputs to Bitcoin mining.

**Sources:**
- Batten's Bitcoin sustainable energy research and datasets (batcoinz.com)
- Methane mining and landfill gas documentation
- Coverage: Bitcoin Magazine, mining-focused media, Nostr

---

## Allen Farrington (dates unknown)
**Tier:** 3
**Role:** Bitcoin Writer / Essayist
**Active:** 2020–present

Author of long-form Bitcoin essays drawing on philosophy, economic history, and political theory, most notably "Bitcoin is Venice" (co-authored with Sacha Meyers) — an argument situating Bitcoin within a historical analysis of Venice's Renaissance-era commercial civilization — and "Wittgenstein's Money." His writing applies economic history and political philosophy frameworks to Bitcoin arguments and has been cited within Bitcoin intellectual circles. Both essays are published on Bitcoin Magazine and through Farrington's own writing.

**Sources:**
- "Bitcoin is Venice" — Allen Farrington & Sacha Meyers
- "Wittgenstein's Money" — Allen Farrington
- Farrington's essays on Bitcoin Magazine and personal writing

---

## The Canadian Freedom Convoy & Bitcoin (February 2022)
**Tier:** 3
**Role:** Defining Moment / Bitcoin Censorship-Resistance Proof of Concept
**Active:** February 2022

The "Freedom Convoy" — a protest by Canadian truckers and supporters against COVID-19 vaccine mandates — generated documented instances of Bitcoin's censorship-resistance in practice. The Canadian government invoked the Emergencies Act to freeze the bank accounts of protesters and donors without court orders; GoFundMe froze and reversed approximately $10 million in donations; and Prime Minister Trudeau's government pressured financial institutions to monitor and freeze crypto transactions. Bitcoin donations facilitated through Tallycoin, a Lightning-native crowdfunding tool, reached recipients and could not be frozen. The episode is documented in parliamentary testimony and coverage and has been widely cited in Bitcoin community discussions of financial censorship and self-custody.

**Sources:**
- Canadian Emergencies Act invocation (February 2022)
- GoFundMe Canada donation freeze documentation
- Tallycoin Freedom Convoy campaign records
- Parliamentary testimony on Emergencies Act financial measures
- Coverage: Bitcoin Magazine, Reuters, BBC, Nostr

---

## Lisa Neigut / niftynei & Bitcoin++ (dates unknown)
**Tier:** 2
**Role:** Lightning Developer / Conference Organizer / Educator
**Active:** 2018–present

American Bitcoin and Lightning developer who authored the dual-funding protocol for Lightning Network channels — BOLT #2 updates allowing both channel parties to contribute liquidity at open, improving liquidity distribution — and contributed extensively to Core Lightning at Blockstream. She also co-founded Bitcoin++, a developer-focused conference series held in Austin, Berlin, and other cities, covering Lightning internals, Taproot, covenants, and Bitcoin script for a technical audience.

**Sources:**
- Dual-funding BOLT specification — Lisa Neigut / niftynei
- Bitcoin++ conference documentation (btcplusplus.dev)
- Core Lightning GitHub contributions (github.com/niftynei)
- Bitcoin++ Austin, Berlin, and other event archives

---

## Bitcoin Ben — Ben Perrin (dates unknown)
**Tier:** 3
**Role:** Bitcoin Educator / YouTuber / Canadian Advocate
**Active:** 2017–present

Canadian Bitcoin educator and YouTuber who founded "BTC Sessions," one of the most-watched Bitcoin tutorial YouTube channels, covering wallets, self-custody, Lightning, nodes, and hardware wallets with step-by-step practical instruction. He became a prominent voice during the Freedom Convoy episode, advocating for Bitcoin as a tool against financial censorship in real time as the Canadian government's Emergencies Act freezes unfolded. His Canadian background gave him a distinct perspective on an episode involving his own country's citizens.

**Sources:**
- BTC Sessions YouTube channel (youtube.com/@BTCSessions)
- Perrin's Freedom Convoy commentary and coverage
- Self-custody and Lightning tutorial archive

---

## John Carvalho (dates unknown)
**Tier:** 3
**Role:** Bitcoin Entrepreneur / Advocate / CEO Synonym
**Active:** 2013–present

Known online as "Bitcoin Error Log"; CEO of Synonym, a company building Slashtags (a Bitcoin-based identity and data protocol) and Bitkit (a Lightning wallet with on-device data storage); previously worked at BitRefill; and a contributor to the LSP (Lightning Service Provider) specification work to standardize Lightning Service Provider interfaces. His Slashtags work is an attempt to build a user data and identity layer on Bitcoin without trusted intermediaries, and his LSP specification contributions address coordination gaps in Lightning's commercial infrastructure. He has been a consistent and outspoken public advocate for a Bitcoin-only position across podcasts, social media, and public debates.

**Sources:**
- Synonym documentation (synonym.to) — Slashtags, Bitkit
- LSP specification contributions (github.com/BitcoinAndLightningLayerSpecs)
- Carvalho's public writing and advocacy

---

## John Vallis (dates unknown)
**Tier:** 3
**Role:** Bitcoin Podcaster / Philosopher
**Active:** 2019–present

Canadian host of the *Bitcoin Rapid-Fire* podcast, known for long-form, philosophically oriented conversations exploring how Bitcoin changes the way people think about money, time, identity, and human flourishing. Vallis focuses on Bitcoin as a catalyst for personal and philosophical change rather than price, markets, or protocol debates, and his interviews address dimensions of the Bitcoin experience that more technically or financially focused podcasts do not.

**Sources:**
- *Bitcoin Rapid-Fire* podcast archive
- Vallis's public writing and interviews

---

## Aleksandar Svetski (dates unknown)
**Tier:** 3
**Role:** Bitcoin Author / Podcaster / Publisher
**Active:** 2019–present

Australian Bitcoin writer and entrepreneur of Eastern European descent; founder of *The Bitcoin Times*, an annual Bitcoin-only publication featuring long-form essays; host of the *Unhashed Podcast*; and author of essays including "Bitcoin Is The Hope" and "Meditations on Cypherpunk Nightmares." *The Bitcoin Times* collects serious long-form Bitcoin writing in a single annual volume and is one of the few curated Bitcoin publications of its kind. Svetski's family background includes origins in Yugoslavia/Eastern Europe, which he has referenced publicly in his writing on what happens when states fail and money becomes a tool of coercion.

**Sources:**
- *The Bitcoin Times* annual publication (thebitcointimes.com)
- *Unhashed Podcast* — Aleksandar Svetski
- "Bitcoin Is The Hope" and collected essays — Svetski

---

## Gigi — Der Gigi (pseudonym, dates unknown)
**Tier:** 3
**Role:** Bitcoin Author / Philosopher / Nostr Advocate
**Active:** 2019–present

Pseudonymous Bitcoin author best known for *21 Lessons* (2019), a philosophical meditation on what Bitcoin teaches the curious student structured around the 21 million supply cap, which has been widely translated and distributed as an onboarding text. Also authored *21 Ways* and numerous essays; was among the earlier prominent Bitcoin authors to publish and engage on Nostr, giving the protocol early visibility within Bitcoin intellectual circles. His writing on Bitcoin and time — the idea that Bitcoin creates its own temporal framework through the blockchain — is a documented contribution to Bitcoin philosophical writing. He publishes pseudonymously and his real identity is not publicly confirmed.

**Sources:**
- *21 Lessons* (2019) — Gigi (dergigi.com)
- *21 Ways* — Gigi
- Gigi's essays on Bitcoin and time (dergigi.com)
- Gigi's Nostr presence and advocacy

---

## Knut Svanholm (dates unknown)
**Tier:** 3
**Role:** Bitcoin Author / Philosopher
**Active:** 2019–present

Swedish Bitcoin author known for a series of short philosophical books approaching Bitcoin from first principles, including *Bitcoin: Sovereignty Through Mathematics* and *Bitcoin: Everything Divided by 21 Million*. His writing is brief and philosophical — closer to essays than treatises — and has been widely shared as onboarding material. The phrase "everything divided by 21 million" from his writing became a commonly repeated encapsulation of Bitcoin's scarcity thesis in community discussion.

**Sources:**
- *Bitcoin: Sovereignty Through Mathematics* — Knut Svanholm
- *Bitcoin: Everything Divided by 21 Million* — Knut Svanholm
- Svanholm's essays and public writing

---

## Tomer Strolight (dates unknown)
**Tier:** 3
**Role:** Bitcoin Writer / Philosopher / Editor
**Active:** 2020–present

Canadian Bitcoin writer who authored *Why Bitcoin* — a collection of concise essays each making a single argument for Bitcoin from a different angle — and served as editor-in-chief at Bitcoin Magazine. Each essay in *Why Bitcoin* is self-contained and short enough to function as a standalone piece, suited to sharing online or on Nostr. His work at Bitcoin Magazine during a pivotal period is documented in that publication's editorial history.

**Sources:**
- *Why Bitcoin* — Tomer Strolight
- Bitcoin Magazine editorial work
- Strolight's essays and public writing

---

## Nik Bhatia (dates unknown)
**Tier:** 3
**Role:** Finance Academic / Author / Bitcoin Macro Analyst
**Active:** 2019–present

Adjunct professor of finance and economics at USC Marshall School of Business and author of *Layered Money* (2021), which explains Bitcoin and the Lightning Network through the historical framework of layered monetary systems — from gold and representative money through Eurodollars to Bitcoin as a base settlement layer with Lightning as a second layer. Bhatia's background includes work as an institutional fixed income trader, and *Layered Money* is designed to present Bitcoin in the vocabulary of reserve assets, settlement layers, and monetary history accessible to finance professionals and policymakers. He also publishes The Bitcoin Layer newsletter and podcast.

**Sources:**
- *Layered Money* (2021) — Nik Bhatia
- Bhatia's academic work and public writing
- The Bitcoin Layer newsletter and podcast

---

## Luke Gromen (dates unknown)
**Tier:** 3
**Role:** Macro Analyst / Bitcoin Thinker
**Active:** 2019–present

Founder of Forest for the Trees (FFTT), a macro research firm, and one of the more cited macro analysts in the Bitcoin space for work on dollar hegemony, U.S. sovereign debt, global reserve currency dynamics, and the structural conditions under which Bitcoin might serve as a neutral reserve asset. His macro framework positions Bitcoin as a probable beneficiary of U.S. debt-to-GDP trajectory and dollar debasement, addressing institutional and sovereign-level audiences rather than retail or ideological ones. His analysis of the petrodollar system's fragility connects to geopolitical adoption stories documented in the Iran, Russia, and CAR entries of this reference.

**Sources:**
- Forest for the Trees (FFTT) macro research
- Gromen's podcast appearances and public writing
- Coverage: macro investing media, Bitcoin Magazine, Nostr

---

## Preston Pysh (dates unknown)
**Tier:** 3
**Role:** Investor / Podcaster / Bitcoin Macro Analyst
**Active:** 2019–present

Co-founder of The Investor's Podcast Network and host of *We Study Billionaires*, one of the most widely distributed investing podcasts; applies traditional value investing and macroeconomic frameworks to Bitcoin, reaching an audience of mainstream investors rather than Bitcoin-native or cypherpunk audiences. He co-hosts a dedicated Bitcoin podcast and has conducted interviews with prominent investors, economists, and Bitcoin developers in a format aimed at bridging traditional finance and Bitcoin discourse.

**Sources:**
- *We Study Billionaires* podcast — The Investor's Podcast Network
- Preston Pysh Bitcoin podcast and interview archive
- Pysh's macro Bitcoin analysis and public writing

---

## Lawrence Lepard (dates unknown)
**Tier:** 3
**Role:** Investment Manager / Sound Money Advocate / Author
**Active:** 2006–present

Investment manager and founder of Equity Management Associates (EMA), established in 2006, which positions itself as providing "Monetary Debasement Insurance" through investments in gold, silver, precious metals mining companies, and Bitcoin. Lepard holds an MBA from Harvard Business School and has over four decades of investment experience. An advocate of Austrian School economics and sound money principles, he adopted Bitcoin as a complement to gold as a hedge against central bank monetary expansion and high global debt-to-GDP ratios. Lepard is active on social media and has appeared frequently on podcasts including What Bitcoin Did and Coin Stories with Natalie Brunell discussing monetary policy, Federal Reserve history, and the case for hard assets. In 2025 he published *The Big Print: What Happened to America and How Sound Money Will Fix It*, which traces U.S. monetary history from the Federal Reserve's founding through contemporary inflation and argues for a return to sound money via gold and Bitcoin.

**Sources:**
- ema2.com — EMA fund documentation
- *The Big Print* (2025) — Lawrence Lepard
- Forbes — "Lawrence Lepard Predicts 'The Big Print'" (May 2025)
- Palisades Gold Radio — Lepard interview
- thebigprintbook.com

---

## James Lavish (dates unknown)
**Tier:** 3
**Role:** Investment Manager / Macro Analyst / Author
**Active:** 2021–present

Institutional investment professional with over 25 years of experience who became a prominent Bitcoin macro analyst and educator. Lavish graduated from Yale University in 1993, holds a CFA designation, and earned an Executive Certificate in FinTech from Cornell University in 2021. His career included positions as an international ADR arbitrage trader on the floor of the New York Stock Exchange for SG Warburg, risk arbitrage trader at Tribeca Investments, head arbitrage trader and compliance officer at Carlson Capital, co-founder and managing partner of Ranger Arbitrage, and Chief Operating Officer of Alternative Investments at LKCM, a $26 billion Texas-based asset management firm. He co-founded the Bitcoin Opportunity Fund, a partnership making public and private investments in the Bitcoin ecosystem, after concluding that traditional inflation hedges including gold and Treasury Inflation-Protected Securities were insufficient against the scale of monetary expansion he anticipated. Lavish authors The Informationist, a Substack newsletter with over 40,000 subscribers that explains one complex financial concept per issue in accessible terms. He co-founded Looking Glass Education, a Bitcoin financial education platform.

**Sources:**
- jameslavish.com — The Informationist
- lookingglasseducation.com
- BTC Prague speaker profile
- Bitcoin Magazine author archive — James Lavish
- Stacker News AMA — @jameslavish (2024)

---

## Robert Kiyosaki (1947–present)
**Tier:** 3
**Role:** Author / Financial Educator / Bitcoin and Hard Asset Advocate
**Active:** 1997–present (Bitcoin advocacy c. 2018–present)

Robert Toru Kiyosaki was born April 8, 1947, in Hilo, Hawaii, to a Japanese-American family. He attended the U.S. Merchant Marine Academy, graduated in 1969, and served as a helicopter gunship pilot in the U.S. Marine Corps during the Vietnam War. His 1997 book *Rich Dad Poor Dad*, written with Sharon Lechter, challenged conventional personal finance advice by arguing that financial education, asset acquisition, and entrepreneurship — not job security or credentials — are the foundations of wealth. The book became one of the best-selling personal finance titles in history, translated into dozens of languages. Kiyosaki subsequently built a financial education company and media brand around the Rich Dad framework. Beginning around 2018 he became a public advocate for Bitcoin, gold, and silver as protection against central bank monetary expansion and dollar debasement, framing them as "real assets" versus fiat currency. He has called Bitcoin "insurance against a dying dollar" and made high public price predictions. In 2025 he disclosed selling silver holdings to increase his Bitcoin position, signaling a shift in emphasis within his hard asset framework. His large social media following has directed mainstream audiences toward Bitcoin as a sound money concept.

**Sources:**
- *Rich Dad Poor Dad* (1997) — Robert Kiyosaki & Sharon Lechter
- Wikipedia — Robert Kiyosaki
- richdad.com
- TheStreet / Yahoo Finance — Kiyosaki Bitcoin commentary (2024–2025)

---

## Guy Swann (dates unknown)
**Tier:** 3
**Role:** Podcaster / Bitcoin Literature Curator
**Active:** 2017–present

Creator and host of *Bitcoin Audible* (formerly *The Cryptoconomy Podcast*), a long-running Bitcoin podcast built around reading Bitcoin articles, essays, and foundational texts aloud, making the written canon of Bitcoin literature accessible in audio form. Swann has recorded hundreds of episodes covering the whitepaper, cypherpunk manifestos, developer blog posts, and philosophical essays, creating an audio library of Bitcoin's intellectual history. His long-form commentary alongside the readings he presents adds analytical context to the source material.

**Sources:**
- *Bitcoin Audible* podcast archive (bitcoinaudible.com)
- Swann's commentary and curation work across Bitcoin literature

---

## Rabbi Michael Caras (dates unknown)
**Tier:** 3
**Role:** Bitcoin Educator / Author / "Bitcoin Rabbi"
**Active:** 2017–present

Rabbi and educator based in Albany, New York, known online as @thebitcoinrabbi, who has built a following bridging the Bitcoin and Jewish communities on social media. Caras is affiliated with the Chabad-Lubavitch movement and teaches Judaism, digital media, and technology at Maimonides Hebrew Day School. He became interested in Bitcoin in 2017 and has drawn connections between the cypherpunk ethos, sound money principles, and Jewish ethics and halacha. In 2019 he published *Bitcoin Money: A Tale of Bitville Discovering Good Money* (illustrated by Marina Yakubivska), a children's book explaining the origins of money and Bitcoin through a fictional town called Bitville; the book has sold over 10,000 copies and became one of the most widely distributed Bitcoin educational books for children. Caras has spoken at synagogues and Jewish youth groups about Bitcoin, describes himself as a two-way ambassador between the Jewish and Bitcoin communities, and has appeared in Jewish media including The Forward, Times of Israel, and the Jewish Telegraphic Agency.

**Sources:**
- *Bitcoin Money: A Tale of Bitville Discovering Good Money* (2019) — Michael Caras
- The Forward — "Meet the beloved 'Bitcoin Rabbi' of Twitter" (2021)
- Times of Israel — Bitcoin Rabbi profile
- Jewish Telegraphic Agency — "Albany Rabbi Puts His Money On Bitcoin" (2019)

---

## Natalie Brunell (dates unknown)
**Tier:** 3
**Role:** Bitcoin Journalist / Podcaster / Media Personality
**Active:** 2020–present

Former mainstream television journalist who became one of Bitcoin's most prominent media voices, hosting the *Coin Stories* podcast and conducting interviews with developers, economists, miners, and institutional investors. Her background in broadcast journalism distinguished her interview style and audience reach from most Bitcoin podcasters with tech or finance backgrounds, and *Coin Stories* reached audiences that would not typically encounter Bitcoin-native media. She has been documented as one of the most visible women in Bitcoin public media.

**Sources:**
- *Coin Stories* podcast (coinStories.io)
- Brunell's journalism background and Bitcoin media work
- Coverage: Bitcoin Magazine, podcast ecosystem

---

## Marty Bent (dates unknown)
**Tier:** 3
**Role:** Podcaster / Media Founder
**Active:** 2017–present

Founded TFTC (Tales from the Crypt) podcast with Matt Odell and later launched TFTC Media as an independent Bitcoin media company. Bent has documented Bitcoin's development across hundreds of podcast episodes interviewing developers, economists, miners, and policymakers, with the show covering multiple market cycles, protocol debates, and regulatory events since 2017. His "Rabbit Hole Recap" newsletter has served as a daily digest of Bitcoin and macro news for regular readers.

**Sources:**
- TFTC Media (tftc.io)
- Tales from the Crypt podcast archive

---

## Peter McCormack (dates unknown)
**Tier:** 3
**Role:** Podcaster / Media Personality / Bitcoin Circular Economy Experimenter
**Active:** 2017–present

Founded What Bitcoin Did podcast (2017), a widely listened Bitcoin interview show, and has publicly documented his own trajectory from cryptocurrency speculator to Bitcoin-only advocate. He purchased Real Bedford FC, a non-league English football club, and operates it as a Bitcoin circular economy experiment — paying staff in Bitcoin and accepting Bitcoin for tickets and merchandise. Craig Wright sued him for defamation for publicly calling Wright a fraud; Wright lost the case, and McCormack v. Wright (UK, 2022) is a documented legal footnote in the Satoshi identity controversy.

**Sources:**
- What Bitcoin Did podcast (whatbitcoindid.com)
- Real Bedford FC documentation and McCormack's public updates
- McCormack v. Wright defamation case (UK, 2022)

---

## Christian Langalis — Bitcoin Sign Guy (dates unknown)
**Tier:** 3
**Role:** Cultural Moment / Accidental Bitcoin Ambassador
**Active:** 2017

Held a handwritten "Buy Bitcoin" sign behind Federal Reserve Chair Janet Yellen during her live Congressional testimony on July 12, 2017, producing a widely shared image in Bitcoin's cultural record. Langalis later auctioned the sign, with proceeds going to charity. The image is documented in Bitcoin cultural history as a widely circulated reference point from the 2017 market period.

**Sources:**
- Congressional testimony footage (July 12, 2017)
- Langalis interviews and sign auction documentation

---

## Benedictines of Mary, Queen of Apostles — Bitcoin-Funded Church (2017)
**Tier:** 3
**Role:** Cultural Moment / Religious Bitcoin Adoption
**Active:** 2017

A cloistered Benedictine order of nuns founded by Sister Mary Wilhelmina Lancaster in Gower, Missouri, that received Bitcoin donations in 2017 and used the proceeds to fund construction of a new church — completed debt-free. The church features hand-painted murals, Italian marble, vaulted ceilings, and stained-glass windows. The community follows the traditional Rule of Saint Benedict and operates with a self-sufficiency model, drawing financial support from donors worldwide. Father Matthew Bartulica set up the sisters with hardware wallets and taught them to send, receive, and hold Bitcoin in cold storage. The nuns hold Bitcoin on behalf of their monastery and the episode became a widely cited cultural story in Bitcoin media as an example of unexpected Bitcoin adoption — a cloistered religious community using Bitcoin's sound money properties and censorship-resistance to build physical infrastructure without debt or traditional banking intermediaries. The story received coverage in Bitcoin Magazine (2022) and mainstream Catholic and financial media.

**Sources:**
- Bitcoin Magazine — "Meet The Catholic Nuns Who Are Building A New Church With Bitcoin" (October 2022)
- benedictinesofmary.org
- Christianity Daily — Benedictines of Mary Bitcoin coverage (2022)
- Bitcoin News — Benedictines of Mary Bitcoin adoption story

---

## BitPay — Tony Gallippi & Stephen Pair (dates unknown)
**Tier:** 3
**Role:** Bitcoin Payment Processor / Merchant Adoption Pioneer
**Active:** 2011–present

Founded BitPay (2011), the first major Bitcoin payment processor, enabling merchants to accept Bitcoin and receive local currency; handled transactions for Dell, Microsoft, Newegg, and others through the mid-2010s. BitPay's alignment with the big-block faction during the blocksize war and its handling of the 2017 hard fork produced a documented community backlash. Nicolas Dorier (see BTCPay Server entry) built BTCPay Server in 2017 explicitly as an open-source non-commercial alternative, citing BitPay's political alignment. BitPay's history is a documented reference case for discussions of custodial payment processor alignment in Bitcoin governance disputes.

**Sources:**
- BitPay company history and documentation (bitpay.com)
- BitPay SegWit2x and Bitcoin Cash support documentation (2017)
- BTCPay Server origin story — Nicolas Dorier (cross-reference)

---

## OpenNode — Afnan Rahman & João Almeida (dates unknown)
**Tier:** 3
**Role:** Bitcoin-Only Payment Processor
**Active:** 2018–present

Built OpenNode, a Bitcoin-only payment processing platform supporting both on-chain and Lightning Network payments, designed as a developer-friendly alternative to BitPay with explicit Lightning support. OpenNode launched after the blocksize war and positioned itself as Bitcoin-only by design with developer APIs for integration. Its Lightning support gave merchants access to instant, low-fee Bitcoin payments at a time when on-chain fees made small transactions impractical, and it became a documented payment rail for Bitcoin-native businesses.

**Sources:**
- OpenNode documentation (opennode.com)
- OpenNode Lightning Network integration documentation

---

## Geyser Fund — Mick Morucci & Stelios Rammos (founded 2022)
**Tier:** 2
**Role:** Bitcoin Crowdfunding Platform
**Active:** 2022–present

Bitcoin-native crowdfunding platform co-founded by Mick Morucci (known as MetaMick) and Stelios Rammos, launched in January 2022. The founders conceived Geyser during the COVID-19 pandemic after concluding that Bitcoin and the Lightning Network made global crowdfunding more practical than any prior platform but that no Bitcoin-native equivalent existed. Morucci had previously worked in the Ethereum space before reorienting to Bitcoin. Geyser enables creators, projects, and humanitarian causes to raise funds directly via Lightning Network payments, without custodians or geographic restrictions. The platform has facilitated funding for Bitcoin education initiatives, open-source projects, community projects, and humanitarian causes across multiple countries. Geyser later introduced recoverable grants, a mechanism allowing conditional fundraising with refund capability.

**Sources:**
- geyser.fund
- Forbes — "Geyser Is Democratising Crowdfunding With Bitcoin's Lightning Network" (March 2024)
- Area Bitcoin — Geyser Fund profile (2024)
- Crunchbase — Geyser company profile

---

## Steak 'n Shake / Sardar Biglari (dates unknown)
**Tier:** 3
**Role:** Corporate Bitcoin Adopter / Fast Food Chain
**Active:** 2024–present

Steak 'n Shake, a U.S. fast food chain with hundreds of locations, began accepting Bitcoin payments at the point of sale under CEO Sardar Biglari, becoming one of the largest brick-and-mortar restaurant chains to accept Bitcoin. The adoption is distinguished from corporate Bitcoin treasury strategies in that it involves consumer transactions rather than balance sheet holdings. Biglari's public advocacy has framed the decision as a deliberate statement on Bitcoin rather than a passive payment option.

**Sources:**
- Steak 'n Shake Bitcoin payment announcement
- Biglari Holdings documentation
- Bitcoin point-of-sale implementation coverage

---

## Joe Nakamoto (pseudonym)
**Tier:** 3
**Role:** Bitcoin Documentary Creator / Circular Economy Advocate
**Active:** 2020s–present

Travels the world producing video documentation of Bitcoin circular economies — communities and regions where Bitcoin is used for everyday commerce — making the global adoption story visible to a broad online audience. His videos from El Salvador, African communities, Latin America, and elsewhere document merchants, vendors, and ordinary people transacting in Bitcoin and are cited in this reference alongside field reports from Bitcoin Ekasi, Bitcoin Lake, and other circular economy entries. He publishes under a pseudonym.

**Sources:**
- Joe Nakamoto YouTube channel and social media
- Field documentation from El Salvador, Africa, and Latin America

---

## Central African Republic — Bitcoin Adoption (2022)
**Tier:** 3
**Role:** Second Nation to Adopt Bitcoin as Legal Tender
**Active:** 2022–2023

In April 2022, the Central African Republic became the second country in history (after El Salvador) to adopt Bitcoin as legal tender, alongside the CFA franc — a currency tied to France and widely described across Francophone Africa as a remnant of monetary colonialism. The Bitcoin law was passed quickly with limited public consultation and faced implementation challenges; the legal tender status was reversed in 2023. The underlying driver — dissatisfaction with the CFA franc arrangement — is documented in the political discourse surrounding the adoption and is connected to the broader Francophone Africa monetary sovereignty debate covered in the Bitcoin in Africa entry.

**Sources:**
- CAR Bitcoin Law (April 2022)
- CAR reversal of Bitcoin legal tender status (2023)
- CFA franc history and Francophone Africa monetary sovereignty debate
- Coverage: Bitcoin Magazine, CoinDesk

---

## Bitcoin Ekasi — Hermann Vivier & Community (dates unknown)
**Tier:** 2
**Role:** Circular Economy Pioneers / South Africa
**Active:** 2021–present

Hermann Vivier led the development of a Bitcoin circular economy in Ekasi, the township of Mossel Bay, South Africa, beginning in 2021 — onboarding local vendors and residents to earn, save, and spend Bitcoin via Lightning. The initiative was modeled on El Zonte (El Salvador) and is documented in Bitcoin media as an example of circular economy adoption in a South African township context with high banking exclusion and remittance costs. Vivier's work is covered by Anita Posch / Bitcoin for Fairness.

**Sources:**
- Bitcoin Ekasi documentation (bitcoinekasi.com)
- Hermann Vivier interviews and field documentation
- Coverage via Anita Posch / Bitcoin for Fairness

---

## Bitcoin Jungle — Rich Scotford & Community (dates unknown)
**Tier:** 2
**Role:** Circular Economy Pioneers / Costa Rica
**Active:** 2021–present

Rich Scotford led the development of a Bitcoin circular economy in the Uvita and Dominical region of Costa Rica's Pacific coast, beginning in 2021, with dozens of local merchants accepting Bitcoin via Lightning. Bitcoin Jungle developed an open-source wallet app for community circular economy use that contributed to the broader Galoy/community wallet ecosystem. The initiative grew organically from local entrepreneurs and expatriates rather than by government mandate.

**Sources:**
- Bitcoin Jungle documentation and wallet (bitcoinjungle.app)
- Rich Scotford interviews
- Galoy Money / community wallet ecosystem documentation

---

## Bitcoin Lake — Patrick Melder & Community (dates unknown)
**Tier:** 2
**Role:** Circular Economy Pioneers / Guatemala
**Active:** 2021–present

Patrick Melder led the development of a Bitcoin circular economy around Lake Atitlán in the highlands of Guatemala, centered on the town of San Marcos La Laguna, beginning in 2021. He onboarded local vendors, tuk-tuk drivers, and market stalls to accept Bitcoin via Lightning. The initiative took root in a predominantly indigenous, low-income community with limited banking access and high remittance dependency, and has been documented in Bitcoin media and in Joe Nakamoto's field work.

**Sources:**
- Bitcoin Lake documentation (bitcoinlake.org)
- Patrick Melder interviews and field documentation
- Coverage via Bitcoin Magazine, Joe Nakamoto documentary work

---

## BTC Isla — Isabella Santos Giha (founded c. 2022)
**Tier:** 3
**Role:** Bitcoin Circular Economy Pioneer / Media Personality / Mexico
**Active:** 2022–present

Isabella Santos Giha (known online as Isa, @isabellasg3) built a Bitcoin circular economy on Isla Mujeres, a small island off the coast of Cancun, Mexico, relocating there from Miami to pursue the project full-time. BTC Isla grew to approximately 30 merchants accepting Bitcoin via Lightning, including a Bitcoin cafe and a Bitcoin-powered gym. Santos co-founded Get Based, a Bitcoin media company, and co-created Bitcoin Backstage, a show distributed on Bitcoin Magazine platforms. She runs Bitcoin 101 immersive educational courses on the island and has extended her education and circular economy work to Peru and other parts of Latin America. She has a significant social media presence on TikTok and has appeared on multiple Bitcoin podcasts discussing circular economy building and Bitcoin education in the developing world.

**Sources:**
- @isabellasg3 (X / TikTok)
- Bitcoin Treasuries Podcast — "Building a Bitcoin Circular Economy w/ Isabella"
- Efrat Fenigson Podcast Ep. 40 — Isabella Santos
- Bitcoin Magazine — Bitcoin Backstage

---

## Próspera — Honduras Special Economic Zone (2020–present)
**Tier:** 3
**Role:** Libertarian Charter City / Bitcoin-Friendly Jurisdiction
**Active:** 2020–present

Próspera is a semi-autonomous special economic zone on the island of Roatán, Honduras, built on the concept of charter cities — private governance, common law, and opt-in regulation. It adopted Bitcoin as a recognized unit of account, allows contracts denominated in Bitcoin, and has attracted Bitcoin entrepreneurs and investors. Próspera has been in ongoing legal and political conflict with the Honduran central government over the ZEDE (Zone for Employment and Economic Development) legal framework under which it operates, illustrating the political risks of private-jurisdiction Bitcoin integration.

**Sources:**
- Próspera documentation (prospera.hn)
- Charter city / ZEDE legal framework documentation (Honduras)
- Próspera vs. Honduras government dispute coverage
- Coverage: Bitcoin Magazine, Reason, Nostr

---

## Bitcoin Island — Roatán, Honduras (dates unknown)
**Tier:** 2
**Role:** Circular Economy / Caribbean Island Bitcoin Community
**Active:** 2021–present

Roatán, a Caribbean island off the coast of Honduras, developed an organic Bitcoin circular economy distinct from — though geographically adjacent to — the Próspera special economic zone. Local businesses, dive shops, restaurants, and tourism operators began accepting Bitcoin via Lightning, driven by a community of Bitcoin-focused residents and visitors rather than any charter city or government framework. The circular economy on Roatán grew independently of Próspera and is documented separately in Bitcoin media.

**Sources:**
- Bitcoin Island Roatán community documentation
- Coverage via Bitcoin Magazine, podcasts, Nostr
- Cross-reference: Próspera (same island, different model)

---

## Madeira — Bitcoin-Friendly Portuguese Island (2022–present)
**Tier:** 3
**Role:** Bitcoin-Friendly Jurisdiction / European Circular Economy Node
**Active:** 2022–present

Madeira, an autonomous Portuguese island in the Atlantic, became the most prominent Bitcoin-friendly jurisdiction in Europe after President Miguel Albuquerque declared Madeira a Bitcoin-friendly region at the Bitcoin 2022 conference in Miami. The island subsequently hosted Bitcoin-focused events, attracted Bitcoin entrepreneurs and remote workers, and developed a small but documented Lightning circular economy. Albuquerque's public declaration represented a regional government within the EU publicly embracing Bitcoin ahead of any national-level EU policy.

**Sources:**
- Miguel Albuquerque Bitcoin 2022 Miami speech
- Madeira Bitcoin community documentation
- Coverage: Bitcoin Magazine, Nostr

---

## Arnhem — "Bitcoin City," Netherlands (2014–present)
**Tier:** 2
**Role:** Circular Economy Pioneer / First Bitcoin City
**Active:** 2014–present

A mid-sized city in the Netherlands that became the first city in the world to be identified as a "Bitcoin City," with dozens of local merchants accepting Bitcoin beginning in 2014 — years before the Lightning Network or any government Bitcoin adoption story. At its peak the Arnhem Bitcoin City initiative counted over 100 participating businesses, including restaurants, shops, and service providers. The initiative predated El Zonte by five years and operated on on-chain Bitcoin before Lightning existed, making it both the earliest documented large-scale urban circular economy and a case study in the practical limitations of on-chain Bitcoin for small payments.

**Sources:**
- Arnhem Bitcoin City documentation (arnhembitcoinstad.nl)
- Early Dutch Bitcoin merchant adoption coverage
- Coverage: Bitcoin Magazine, CoinDesk

---

## Lugano Plan B — Switzerland (2022–present)
**Tier:** 3
**Role:** Bitcoin-Friendly City-State Initiative / European Adoption
**Active:** 2022–present

The city of Lugano, in the Italian-speaking canton of Ticino, Switzerland, launched "Plan B" in partnership with Tether — declaring Bitcoin and USDT accepted for paying taxes, city fees, and municipal services, and building out merchant infrastructure across the city. Lugano hosts the annual Plan B Forum, which has attracted Bitcoin and stablecoin figures. The initiative is notable as a functioning European municipality integrating Bitcoin payments at the civic level; the deep involvement of Tether alongside Bitcoin is a documented feature of the program that distinguishes it from Bitcoin-only adoption initiatives.

**Sources:**
- Lugano Plan B documentation and Forum proceedings (planb.lugano.ch)
- City of Lugano / Tether partnership announcement (2022)
- Plan B Forum coverage: Bitcoin Magazine, CoinDesk

---

## Biarritz Bitcoin — France (dates unknown)
**Tier:** 2
**Role:** Circular Economy Pioneers / France
**Active:** 2021–present

A surf town and resort city on France's Atlantic Basque coast that developed one of the most active Bitcoin circular economies in continental Europe, with local merchants, restaurants, and surf shops accepting Bitcoin via Lightning beginning in 2021. The initiative grew organically from the local Bitcoin community. It is a documented reference point for French-language Bitcoin adoption and is covered in French Bitcoin media and Bitcoin Magazine.

**Sources:**
- Biarritz Bitcoin community documentation
- Coverage: French Bitcoin media, Bitcoin Magazine, Nostr

---

## Bitcoin in Africa — Senegal & the CFA Franc Context (ongoing)
**Tier:** 3
**Role:** Continental Adoption Story / Monetary Sovereignty Movement
**Active:** 2019–present

Across Francophone West Africa — and Senegal in particular — Bitcoin adoption has grown alongside a political movement to exit the CFA franc, the colonial-era currency used by 14 African nations that is pegged to the euro and partially controlled by the French Treasury. Broader African Bitcoin adoption documented by Anita Posch, Joe Nakamoto, and others spans Nigeria, Ghana, Zimbabwe, Zambia, and Kenya, driven by currency weakness, banking exclusion, and remittance costs; Nigeria in particular recorded some of the world's highest peer-to-peer Bitcoin trading volumes during the naira crisis of 2023–2024 even after the Central Bank of Nigeria restricted crypto purchases. Multiple circular economy projects in Africa — Bitcoin Ekasi, Gridless, and others — are documented separately in this reference.

**Sources:**
- CFA franc history and West African monetary sovereignty debate
- Nigeria P2P Bitcoin trading volume data (2021–2024)
- Bitcoin for Fairness / Anita Posch field documentation (Zimbabwe, Zambia)
- Joe Nakamoto documentary coverage of African circular economies
- Bitcoin Ekasi documentation (cross-reference)
- Coverage: Bitcoin Magazine Africa, African Bitcoin podcasts, Nostr

---

## Bitcoin Nigeria — P2P Adoption & the Naira Crisis (2017–present)
**Tier:** 3
**Role:** Largest African Bitcoin Market / Regulatory Battleground
**Active:** 2017–present

Nigeria has consistently ranked among the top countries globally for Bitcoin P2P trading volume, driven by currency weakness, high remittance costs, and a large young population. In February 2021, the Central Bank of Nigeria ordered banks to close accounts of cryptocurrency exchanges, which shifted adoption to P2P platforms such as Paxful and Binance P2P and is documented to have increased rather than decreased grassroots usage. The naira's collapse in 2023–2024 produced elevated P2P Bitcoin trading volumes. The Nigerian government detained Binance executives in 2024, generating international attention and regulatory debate about the enforcement of financial regulations against global crypto platforms.

**Sources:**
- Central Bank of Nigeria crypto ban (February 2021)
- Nigeria P2P trading volume data — Paxful, LocalBitcoins, Binance P2P (2021–2024)
- Naira crisis documentation (2023–2024)
- Nigerian government detention of Binance executives (2024)
- Coverage: Bitcoin Magazine, CoinDesk, African Bitcoin podcasts

---

## Bitcoin India — Regulatory Suppression & Grassroots Adoption (2017–present)
**Tier:** 3
**Role:** Major Emerging Market Bitcoin Country / Regulatory Battleground
**Active:** 2017–present

India has faced sustained regulatory hostility toward Bitcoin, including a Supreme Court-overturned RBI banking ban (2018–2020) and a 30% flat tax on crypto gains combined with a 1% tax deducted at source (TDS) on transactions (2022) that significantly reduced domestic exchange volume. India is the world's largest remittance-receiving country, giving Bitcoin's remittance use case particular relevance. Despite regulatory restrictions, India's P2P Bitcoin activity and developer community have remained documented and active, with Indian Bitcoiners among the more visible voices in global Bitcoin media and on Nostr.

**Sources:**
- Reserve Bank of India crypto banking ban (2018); Supreme Court overturn (2020)
- India crypto tax legislation (30% gains tax, 1% TDS, 2022)
- India P2P trading volume data
- Remittance use case documentation
- Coverage: Bitcoin Magazine, Indian crypto media, Nostr

---

## Gridless & Off-Grid Bitcoin Mining in Africa — Malawi, Kenya & Beyond (2022–present)
**Tier:** 2
**Role:** Off-Grid Bitcoin Mining Pioneer / Stranded Energy Monetization
**Active:** 2022–present

Gridless Compute, co-founded by Erik Hersman and Janet Maingi, pioneered a model of deploying small-scale Bitcoin miners alongside micro-hydro power plants in rural Africa — locations where electricity is generated but has no local grid connection or demand to absorb it. Operations expanded across Kenya, Malawi, and other East and Southern African countries. The company received investment from Block (Jack Dorsey) and other investors, and has been documented as an applied case of the "stranded energy" mining thesis: Bitcoin miners act as a buyer of last resort for otherwise wasted power, providing revenue to micro-hydro operators and creating a path toward rural electrification.

**Sources:**
- Gridless Compute documentation and blog (gridlesscompute.com)
- Erik Hersman and Janet Maingi interviews
- Block / Square investment in Gridless documentation
- Malawi and Kenya off-grid mining field reports
- Coverage: Bitcoin Magazine, mining-focused podcasts, Nostr

---

## Bitcoin Argentina — Hyperinflation, Capital Controls & Milei (2013–present)
**Tier:** 3
**Role:** Major Hyperinflationary Bitcoin Market / Latin American Adoption Story
**Active:** 2013–present

Argentina has recorded significant Bitcoin adoption driven by recurring currency crises, chronic peso depreciation, strict capital controls (the "cepo cambiario"), and a population with documented experience of bank freezes including the 2001 corralito. Argentines developed parallel currency markets — the "dólar blue" — and later crypto P2P markets as savings preservation mechanisms, with Bitcoin and stablecoins (primarily USDT) both gaining large user bases. The 2023 election of Javier Milei, who publicly expressed sympathy for Bitcoin, led to dollarization of the economy and dismantling of capital controls — documented policy changes with direct implications for Bitcoin and the informal dollar markets that had developed alongside it.

**Sources:**
- Argentina peso crisis and capital control history (2011–2023)
- 2001 corralito bank freeze documentation
- Argentina P2P Bitcoin and crypto trading volume data
- Javier Milei economic platform and dollarization (2023–2024)
- Coverage: Bitcoin Magazine, Latin American Bitcoin media, Nostr

---

## Bitcoin Venezuela — Hyperinflation, the Petro & Diaspora Remittances (2016–present)
**Tier:** 3
**Role:** Hyperinflationary Bitcoin Adoption / State Crypto Cautionary Tale
**Active:** 2016–present

Venezuela experienced one of the worst hyperinflationary collapses in modern history — bolivar inflation peaked in the millions of percent — driving citizens to Bitcoin for savings preservation and cross-border remittances. The Maduro government launched the Petro (2018), a state-issued cryptocurrency backed by claimed oil reserves, which became the most prominent example of a government-controlled digital currency and was widely regarded as a failure. Venezuela also became a notable Bitcoin mining country as citizens used subsidized state electricity to mine — a form of capital flight the government struggled to suppress — and Venezuelan diaspora remittances via Bitcoin are among the more extensively documented humanitarian use cases in this reference.

**Sources:**
- Venezuela hyperinflation data (2016–2020)
- Petro cryptocurrency launch and failure documentation (2018–present)
- Venezuela Bitcoin mining and electricity subsidy documentation
- Venezuelan diaspora remittance via Bitcoin data
- Coverage: Bitcoin Magazine, Human Rights Foundation, Nostr

---

## Bitcoin Iran — Sanctions Evasion, State Mining & Crackdowns (2019–present)
**Tier:** 3
**Role:** Sanctioned State Bitcoin Mining / Geopolitical Adoption Story
**Active:** 2019–present

Iran legalized and licensed Bitcoin mining in 2019, explicitly as a mechanism to generate hard currency outside U.S. dollar sanctions; at peak, Iran was estimated to account for 4–7% of global Bitcoin hashrate (Cambridge CBECI estimates). State-owned power plants and subsidized electricity made large-scale licensed mining viable, while the government simultaneously cracked down on unlicensed mining and periodically restricted crypto trading for citizens. Iran's use of Bitcoin mining to acquire internationally liquid assets outside the banking system demonstrated that sanctioned nation-states could operate within Bitcoin's protocol and is documented in U.S. Treasury and OFAC discussions of crypto and sanctions enforcement.

**Sources:**
- Iranian government Bitcoin mining legalization (2019)
- Iran hashrate estimation data (Cambridge Centre for Alternative Finance)
- U.S. Treasury / OFAC Iran sanctions and crypto documentation
- Iran electricity subsidy and mining crackdown coverage
- Coverage: CoinDesk, Bitcoin Magazine, Reuters

---

## Bitcoin Russia — State Ambivalence, War Sanctions & Mining Expansion (2022–present)
**Tier:** 3
**Role:** Sanctioned State Crypto Adoption / Major Mining Country
**Active:** 2017–present

Russia has had a volatile regulatory relationship with Bitcoin — the Central Bank of Russia pushed for an outright ban in early 2022 — before the February 2022 invasion of Ukraine and subsequent Western sanctions prompted a policy shift toward accommodating Bitcoin and crypto as cross-border settlement and sanctions circumvention tools. Russia is also a major Bitcoin mining country, with Siberian hydroelectric power and gas flaring used to power operations; mining expanded after China's 2021 ban drove hashrate migration and Russia absorbed a significant portion of that displaced hashrate. Russia's use of Bitcoin for cross-border payments under sanctions is documented in OFAC sanctions guidance and coverage of the post-invasion Russian financial landscape.

**Sources:**
- Central Bank of Russia Bitcoin ban proposal (January 2022)
- Russia cryptocurrency legislation post-invasion (2022–2024)
- Russia hashrate data post-China ban (Cambridge Centre for Alternative Finance)
- OFAC Russia sanctions and crypto circumvention documentation
- Coverage: CoinDesk, Bitcoin Magazine, Reuters, Financial Times

---

## Bitcoin China — The Mining Superpower That Banned Itself (2012–2021)
**Tier:** 3
**Role:** Dominant Mining Nation / Regulatory Crackdown Case Study
**Active:** 2012–2021 (dominant era); ongoing in diaspora

China was the center of gravity of Bitcoin mining from approximately 2014 to 2021 — at peak accounting for an estimated 65–75% of global hashrate, driven by cheap coal and hydro electricity, proximity to ASIC hardware manufacturers (Bitmain, MicroBT), and a large manufacturing base. Chinese mining pools (F2Pool, AntPool, Poolin, BTC.com) dominated block production during this period. The Chinese government issued escalating crackdowns on Bitcoin exchanges (2013, 2017) before the People's Bank of China declared all crypto transactions illegal and the State Council banned mining outright in May–June 2021, triggering the largest hashrate migration in Bitcoin history. Bitcoin's hashrate dropped roughly 50% and recovered to new all-time highs within months as miners relocated to the U.S., Kazakhstan, Russia, and elsewhere.

**Sources:**
- PBOC Bitcoin exchange crackdowns (2013, 2017)
- China State Council Bitcoin mining ban (May–June 2021)
- Hashrate migration data (Cambridge Centre for Alternative Finance, 2021)
- Bitmain / Jihan Wu documentation (cross-reference)
- Coverage: CoinDesk, Bitcoin Magazine, Reuters, South China Morning Post

---

## Bitcoin Kazakhstan — The Hashrate Refuge & Power Crisis (2021–2022)
**Tier:** 3
**Role:** Post-China Hashrate Destination / Mining Boom and Bust
**Active:** 2021–2022

Kazakhstan absorbed a large share of the Chinese mining exodus after the May 2021 ban, briefly becoming the second-largest Bitcoin mining country in the world (after the U.S.) with an estimated 18% of global hashrate by late 2021. The rapid influx overwhelmed Kazakhstan's Soviet-era power grid, producing widespread electricity shortages and forcing the government to impose mining power limits and elevated electricity tariffs targeting miners. In January 2022, mass political unrest ("Bloody January") led to internet shutdowns across Kazakhstan, which produced a measurable drop in Bitcoin's global hashrate — a documented instance of geopolitical events causing quantifiable disruption to Bitcoin's mining network; the network recovered following the outage.

**Sources:**
- Kazakhstan hashrate growth data (Cambridge Centre for Alternative Finance, 2021–2022)
- Kazakhstan electricity crisis and mining power limits (2021–2022)
- Kazakhstan Bloody January unrest and internet shutdown (January 2022)
- Hashrate impact of Kazakhstan internet outage — on-chain data
- Coverage: CoinDesk, Bitcoin Magazine, Reuters

---

## Bitcoin Ethiopia — Grand Renaissance Dam & Industrial Mining (2022–present)
**Tier:** 3
**Role:** Emerging Major Mining Nation / African Hydro Mining Hub
**Active:** 2022–present

Ethiopia emerged as a notable Bitcoin mining destination powered by surplus electricity from the Grand Ethiopian Renaissance Dam (GERD), the largest hydroelectric dam in Africa. The Ethiopian Electric Power utility negotiated power purchase agreements with licensed Bitcoin miners including Marathon Digital, and the Ethiopian government publicly stated that Bitcoin mining served as a mechanism to monetize excess hydro capacity the domestic grid could not yet absorb. Ethiopia's industrial-scale hydro mining is documented alongside smaller-scale stranded hydro mining models such as Gridless's operations in Malawi and Kenya in Bitcoin's African mining narrative.

**Sources:**
- Grand Ethiopian Renaissance Dam documentation and power capacity
- Ethiopian Electric Power Bitcoin mining licensing framework
- Marathon Digital Ethiopia operations documentation
- Cambridge Centre for Alternative Finance hashrate data (Africa)
- Coverage: Bitcoin Magazine, CoinDesk, Reuters Africa

---

## Bitcoin Paraguay — Itaipu Dam & Cheap Hydro Mining (2021–present)
**Tier:** 3
**Role:** South American Mining Hub / Hydro-Powered Bitcoin Country
**Active:** 2021–present

Paraguay became one of Latin America's most attractive Bitcoin mining destinations due to surplus hydroelectric power from the Itaipu Dam — one of the world's largest power plants, shared with Brazil — providing access to low-cost electricity. Large-scale Bitcoin mining operations established themselves in the country, and the Paraguayan Congress passed legislation to regulate and legalize Bitcoin mining, though presidential vetoes and political friction complicated implementation. Paraguay also developed a Bitcoin circular economy community in parallel with and predating the industrial mining boom, constituting two distinct Bitcoin adoption stories within the same country.

**Sources:**
- Itaipu Dam electricity production and pricing documentation
- Paraguay Bitcoin mining legislation (2022) and presidential veto
- Paraguay circular economy community documentation
- Coverage: Bitcoin Magazine, CoinDesk, Latin American Bitcoin media

---

## BitDevs NYC (founded 2013)
**Tier:** 3
**Role:** Bitcoin Developer Meetup / Originator of the BitDevs Socratic Seminar Format
**Active:** 2013–present

The original BitDevs chapter, founded in New York City in 2013, and the originator of the Socratic Seminar format that has since been adopted by Bitcoin developer meetup communities worldwide. The first BitDevs NYC Socratic Seminar was held on August 7, 2013, making it one of the earliest recurring technical Bitcoin developer forums. Rather than organizing around presentations and lectures, BitDevs NYC structured its monthly events as open Socratic seminars in which participants collaboratively review recent Bitcoin Core pull requests, research papers, technical blog posts, IRC and mailing list discussions, and network data. The format was designed to foster debate and technical rigor rather than passive consumption. BitDevs NYC became a documented gathering point for Bitcoin Core developers and protocol researchers in New York. The model has been replicated in dozens of cities globally — including Austin, San Francisco, London, and Tampa — with the BitDevs network maintaining a directory of chapters that regularly host Socratic seminars. John Newbery has been among the documented organizers.

**Sources:**
- bitdevs.org
- Meetup.com — BitDevs NYC (first event: August 7, 2013)
- Bitcoin Magazine — "Op Ed: Want To Learn About Bitcoin? Try A Local Socratic Seminar"
- BitDevs NYC — "Running a Great Socratic Seminar" (bitdevs.org)

---

## Austin BitDevs & the Texas Bitcoin Community (2014–present)
**Tier:** 3
**Role:** Grassroots Developer Meetup / Bitcoin Community Hub
**Active:** 2014–present

Austin BitDevs is part of the global BitDevs network of monthly Socratic seminars where developers review recent Bitcoin research, pull requests, and protocol developments. Austin became a significant Bitcoin hub in the 2020s as developers, entrepreneurs, and companies relocated from higher-cost cities, and its BitDevs chapter reflects the technical talent concentrated there. The broader Texas Bitcoin ecosystem — deregulated energy markets making it the dominant U.S. mining state, Ted Cruz's pro-mining advocacy, the Texas Blockchain Council, and Bitcoin++ (Lisa Neigut) — is documented across multiple entries in this reference; Austin BitDevs represents the grassroots developer community layer of that ecosystem.

**Sources:**
- Austin BitDevs meetup archive (austinbitdevs.com)
- *Bitcoiners* documentary (YouTube: youtube.com/watch?v=FcaQ-EifEJY)
- Texas Blockchain Council documentation
- Cross-references: Ted Cruz, Riot/Rockdale, Lisa Neigut/Bitcoin++, Bitcoin Park Nashville entries

---

## Car Gonzalez — Carlos Gonzalez (dates unknown)
**Tier:** 3
**Role:** Bitcoin Community Organizer / Austin BitDevs Figure
**Active:** 2019–present

Carlos Gonzalez (known as "Car") is a figure in the Austin Bitcoin community featured in a documentary about Austin BitDevs — one of the few filmed records of a local Bitcoin developer community from the inside — and an active contributor on Stacker News (@car). He has been a consistent presence in Texas Bitcoin community organizing, and the documentary in which he appears (youtube.com/watch?v=FcaQ-EifEJY) provides a documented record of what grassroots Bitcoin meetup culture looks like at the local level.

**Sources:**
- *Bitcoiners* documentary (YouTube: youtube.com/watch?v=FcaQ-EifEJY)
- Stacker News (@car contributions)
- Austin BitDevs community documentation

---

## Tampa BitDevs & Bitcoin Bay Foundation — bennyhodl (founded 2022)
**Tier:** 3
**Role:** Bitcoin Developer Meetup / Community Nonprofit
**Active:** 2022–present

Bitcoin developer meetup and community nonprofit founded in Tampa Bay, Florida by a developer known as bennyhodl, who launched the first Tampa BitDevs session in October 2021 after traveling to Austin BitDevs for eight months and wanting to establish an equivalent technical community locally. The organization formally launched in January 2022 and grew into the Bitcoin Bay Foundation, the largest Bitcoin-focused community in the Tampa Bay area, hosting five or more free events per month with over 100 monthly attendees. Events include Tampa BitDevs Socratic seminars, Bitcoin 101 workshops, business workshops, and the annual Sound Money Soiree charity gala. By end of 2023, Bitcoin Bay Foundation had received 501(c)(3) nonprofit status, documented as the first Bitcoin-only meetup organization to do so. The foundation also developed Bay Wallet, an LDK-based Lightning wallet built by Tampa community members. Wesley Schlemmer has served as president of the foundation.

**Sources:**
- bitcoinbay.foundation
- Bitcoin Magazine — "Tampa Bay's Bitcoin Community Builds Circular Economy Momentum" (2023)
- Bitcoin Magazine — Bitcoin Bay Foundation Gasparilla Parade coverage (2024)
- GitHub — bitcoinbayfoundation/baywallet

---

## Thomas Pacchia & Partners — Pubkey (dates unknown)
**Tier:** 3
**Role:** Bitcoin Cultural Institution Founders
**Active:** 2023–present

Founded Pubkey, a Bitcoin bar and gathering space in Greenwich Village, New York City (2023), which accepts only Bitcoin via Lightning. Pubkey operates as a Bitcoin-only business accepting no fiat and has hosted meetups, developer discussions, and community events since opening. It is documented as a physical hub for the Bitcoin community in New York City and a working example of Bitcoin-only point-of-sale commerce operating via the Lightning Network at street level.

**Sources:**
- Pubkey NYC documentation and event history (pubkey.bar)
- Lightning Network payment integration documentation

---

## Club Orange — Matteo Pellegrini (formerly Orange Pill App, founded 2022)
**Tier:** 2
**Role:** Bitcoin Community Social Network
**Active:** 2022–present

Location-based social network for the Bitcoin community, founded by Matteo Pellegrini and launched as Orange Pill App at Pacific Bitcoin in November 2022. Pellegrini built the app after struggling to find local Bitcoiners when he moved to a new area, identifying a gap between online Bitcoin communities and real-world connection. The app enables users to discover nearby Bitcoiners, find meetups and conferences, and locate merchants that accept Bitcoin, with an integrated self-custodial Lightning wallet for sending sats between members. Orange Pill App raised $250,000 in pre-seed funding and grew to over 20,000 members across 71 countries. The app was later rebranded as Club Orange. It has been used as an infrastructure layer for the Bitcoin parallel economy — connecting individuals, events, and businesses in local Bitcoin ecosystems worldwide.

**Sources:**
- cluborange.org
- Bitcoin Magazine — "Orange Pill: A New App To Meet Bitcoiners"
- Bitcoin Magazine — Orange Pill App $250K pre-seed funding (2023)
- BTC Times — Orange Pill App Merchants feature

---

## Stephan Livera (dates unknown)
**Tier:** 3
**Role:** Podcaster / Educator
**Active:** 2018–present

Founded the Stephan Livera Podcast (2018), focusing on Austrian economics, Bitcoin technical topics, and Lightning development; also works at Swan Bitcoin. His episodes on monetary theory, Lightning protocol development, and Bitcoin privacy are among the more technically and economically detailed available to a general audience, and his consistent Austrian economics framing connects Bitcoin's monetary arguments to that intellectual tradition.

**Sources:**
- Stephan Livera Podcast (stephanlivera.com)
- Swan Bitcoin association

---

## Daniel Prince (dates unknown)
**Tier:** 3
**Role:** Bitcoin Podcaster / Educator
**Active:** 2019–present

British Bitcoin podcaster and educator who hosts *Once Bitten! A Bitcoin Podcast*, launched in 2019, with a focus on personal stories of how Bitcoin has changed individuals' and families' lives and financial trajectories. Prince spent over 17 years in the banking and finance sector at voice brokerage houses in the Foreign Exchange markets before leaving the industry to travel through Asia, Europe, and North America with his wife and four children. He is also the author of *Choose Life*, a book about long-term family travel, world-schooling, and digital nomadism, and has hosted homeschool and alternative education summits. *Once Bitten* is distributed across major podcast platforms and has featured a wide range of guests from across the Bitcoin ecosystem. Prince has spoken at BTC Prague and other Bitcoin conferences.

**Sources:**
- Once Bitten! A Bitcoin Podcast — Apple Podcasts / Spotify
- LinkedIn — Daniel Prince
- BTC Prague speaker profile

---

## Donald Trump (1946–present)
**Tier:** 3
**Role:** 45th & 47th U.S. President / Bitcoin Policy Architect
**Active:** 2024–present (Bitcoin-relevant)

Spoke at the Bitcoin Conference in Nashville (July 2024) pledging to make the U.S. the "Bitcoin superpower of the world"; pardoned Ross Ulbricht upon taking office (January 2025); and signed executive orders establishing a U.S. Strategic Bitcoin Reserve and directing federal agencies to hold rather than sell seized Bitcoin. Trump had previously stated publicly that he was "not a fan of Bitcoin." His administration's documented Bitcoin-relevant policy outcomes include Ulbricht's pardon, Gary Gensler's departure as SEC chair, and the Strategic Bitcoin Reserve executive order — a shift from the enforcement-focused approach of 2021–2024.

**Sources:**
- Trump's Bitcoin Conference Nashville speech (July 2024)
- Executive Order on Digital Assets / Strategic Bitcoin Reserve (January 2025)
- Trump pardon of Ross Ulbricht (January 2025)
- Trump campaign crypto policy platform (2024)

---

## Benjamin Lawsky (dates unknown)
**Tier:** 3
**Role:** Regulator / NYDFS Superintendent
**Active:** 2011–2015 (Bitcoin-relevant)

Served as the first Superintendent of the New York Department of Financial Services (NYDFS) from 2011 to 2015 and is the architect of the BitLicense — New York's regulatory framework for businesses engaged in virtual currency activity, finalized in June 2015. The BitLicense was the first state-level comprehensive cryptocurrency regulatory regime in the United States and became one of the most contested regulatory actions in early Bitcoin history. Critics argued it imposed compliance costs that made operating in New York prohibitive for small Bitcoin businesses, leading several companies to exit the New York market rather than apply. Lawsky resigned from NYDFS shortly after the BitLicense's finalization to found a consulting firm advising financial institutions on regulatory compliance.

**Sources:**
- NYDFS BitLicense final rule (June 2015)
- Lawsky's public statements and congressional testimony
- Bitcoin industry responses to BitLicense proposal (2014–2015)

---

## Eric Trump (1984–present)
**Tier:** 3
**Role:** Entrepreneur / Bitcoin Mining Investor
**Active:** 2025–present (Bitcoin-relevant)

Son of President Donald Trump and Executive Vice President of the Trump Organization. In 2025, Eric Trump became involved in American Bitcoin Corp., a majority-owned subsidiary of Hut 8 Corp focused on industrial-scale Bitcoin mining and strategic Bitcoin reserve development. His involvement represents a direct intersection of the Trump family brand with institutional Bitcoin mining.

**Sources:**
- American Bitcoin Corp. launch announcement (2025)
- Hut 8 Corp public filings (NASDAQ: HUT)

---

## Senator Cynthia Lummis (R-WY) (1954–present)
**Tier:** 3
**Role:** U.S. Senator / Bitcoin Legislator
**Active:** 2021–present

Introduced the BITCOIN Act (Boosting Innovation, Technology, and Competitiveness through Optimized Investment Nationwide), proposing a U.S. Strategic Bitcoin Reserve of 1 million BTC; holds Bitcoin personally and has disclosed this in Senate ethics filings. Her BITCOIN Act preceded Trump's Strategic Bitcoin Reserve executive order and is documented in the legislative history of U.S. Bitcoin policy. Lummis has consistently distinguished Bitcoin from altcoins in her congressional arguments and has been the most persistently Bitcoin-specific legislative voice in the Senate.

**Sources:**
- BITCOIN Act of 2024 — Senator Cynthia Lummis
- Lummis's Senate floor speeches and hearings on Bitcoin
- Lummis personal Bitcoin holdings disclosures

---

## Senator Elizabeth Warren (D-MA) (1949–present)
**Tier:** 3
**Role:** U.S. Senator / Bitcoin Critic / Regulatory Architect
**Active:** 2021–present (Bitcoin-relevant)

Led sustained congressional opposition to Bitcoin and crypto, introducing the Digital Asset Anti-Money Laundering Act (2022, reintroduced 2023) — which would have applied bank-like BSA compliance requirements to Bitcoin miners, node operators, and non-custodial wallet developers — and publicly building what she called an "anti-crypto army" in the Senate. The bill did not pass. Her framing of Bitcoin as primarily a vehicle for financial crime, sanctions evasion, and drug trafficking is documented in congressional hearing records and public statements, and was publicly rebutted by Bitcoin developers and advocates.

**Sources:**
- Digital Asset Anti-Money Laundering Act (2022, 2023) — Senator Warren
- Warren's Senate Banking Committee hearings on crypto
- Warren's "anti-crypto army" public statements (2023–2024)

---

## Representative Brad Sherman (D-CA) (1954–present)
**Tier:** 3
**Role:** U.S. Congressman / Bitcoin Antagonist
**Active:** 2018–present (Bitcoin-relevant)

One of the most vocal and consistent congressional critics of Bitcoin; introduced a bill in 2019 to ban all cryptocurrency; and has repeatedly called for Bitcoin's prohibition in House Financial Services Committee hearings. His 2019 ban proposal did not advance, but his consistent presence in hearings has produced a documented record of prohibition arguments including that Bitcoin primarily serves criminal purposes and undermines the dollar's global reserve status. These arguments are documented in hearing transcripts and have been publicly rebutted by Bitcoin developers and advocates.

**Sources:**
- Crypto-Currency Act / Bitcoin ban proposal — Rep. Brad Sherman (2019)
- House Financial Services Committee hearing transcripts

---

## Senator Ted Cruz (R-TX) (1970–present)
**Tier:** 3
**Role:** U.S. Senator / Bitcoin Mining Advocate
**Active:** 2021–present (Bitcoin-relevant)

Emerged as a prominent Bitcoin advocate in the Senate, particularly on mining policy, arguing that Bitcoin mining can monetize stranded energy in Texas and stabilize the grid; also introduced legislation to allow congressional cafeterias to accept Bitcoin. His arguments ground Bitcoin mining's energy case in Texas energy politics and the state's deregulated electricity market. Texas became the dominant U.S. Bitcoin mining state in the period following China's 2021 ban, and Cruz has been a vocal part of the political environment that made Texas attractive to mining operators.

**Sources:**
- Cruz Senate speeches on Bitcoin mining and energy (2021–present)
- Texas Bitcoin mining policy documentation
- Cruz legislative proposals on Bitcoin

---

## Representative Patrick McHenry (R-NC) (1975–present)
**Tier:** 3
**Role:** House Financial Services Committee Chair / FIT21 Author
**Active:** 2021–2024 (Bitcoin-relevant)

As chair of the House Financial Services Committee, shepherded the Financial Innovation and Technology for the 21st Century Act (FIT21) through the House with bipartisan support in May 2024 — the most comprehensive digital asset regulatory framework to pass either chamber of Congress. FIT21 proposed allocating jurisdiction over digital assets between the SEC and CFTC based on decentralization criteria, representing a documented legislative approach to the longstanding jurisdictional dispute over Bitcoin and crypto regulation. The bill did not become law before McHenry's retirement from Congress.

**Sources:**
- Financial Innovation and Technology for the 21st Century Act (FIT21, 2024)
- House Financial Services Committee hearing records
- FIT21 House vote record (May 2024)

---

## Chris Giancarlo / "Crypto Dad" (1959–present)
**Tier:** 3
**Role:** CFTC Chairman / Regulatory Pioneer
**Active:** 2017–2019 (Bitcoin-relevant)

As CFTC Chairman, oversaw the approval of Bitcoin futures trading on the CME and CBOE in December 2017 — the first regulated Bitcoin derivatives products in the U.S. — earning the nickname "Crypto Dad" for his relatively supportive regulatory posture. The December 2017 futures approvals gave institutional investors a regulated vehicle for Bitcoin exposure and were the first instance of a U.S. federal regulator enabling a Bitcoin-linked product. The CME futures launch coincided with Bitcoin's 2017 price peak; some analysts have attributed the subsequent price decline partly to institutional short-selling through the new futures market, though this remains debated.

**Sources:**
- CFTC Bitcoin futures approval (December 2017)
- Giancarlo's public statements on digital assets
- CME and CBOE Bitcoin futures launch documentation

---

## Representative Warren Davidson (R-OH) & Representative Tom Emmer (R-MN)
**Tier:** 3
**Role:** Pro-Bitcoin Congressmen / Legislative Advocates
**Active:** 2021–present

Davidson introduced the "Keep Your Coins Act" protecting the right to self-custody Bitcoin without government interference; Emmer introduced the CBDC Anti-Surveillance State Act blocking the Federal Reserve from issuing a retail CBDC without congressional authorization. Both bills are documented in House Financial Services Committee records and represent the Bitcoin-specific (as opposed to generic crypto) legislative agenda focused on self-custody rights and opposition to a government-issued digital dollar with surveillance capabilities.

**Sources:**
- Keep Your Coins Act — Rep. Warren Davidson
- CBDC Anti-Surveillance State Act — Rep. Tom Emmer
- House Financial Services Committee records

---

## Riot Platforms — Jason Les (dates unknown)
**Tier:** 3
**Role:** Public Bitcoin Mining Company
**Active:** 2017–present

One of the largest publicly traded Bitcoin mining companies in the U.S., operating a large facility in Rockdale, Texas using the state's deregulated energy grid; subject to SEC reporting, which provides a documented public record of industrial Bitcoin mining economics. The Rockdale facility has been cited in energy policy discussions about demand-response programs and renewable integration. Pierre Rochard served as VP of Research at Riot (see his entry). In 2024, Riot attempted a hostile takeover of Bitfarms, which Bitfarms rejected.

**Sources:**
- Riot Platforms SEC filings and annual reports
- Rockdale, Texas mining facility documentation
- Texas energy grid / Bitcoin mining integration research

---

## Marathon Digital Holdings / MARA — Fred Thiel (dates unknown)
**Tier:** 3
**Role:** Public Bitcoin Mining Company
**Active:** 2012–present (mining focus from 2020)

One of the largest publicly traded Bitcoin miners by hashrate; under CEO Fred Thiel, adopted a policy of holding all mined Bitcoin on its balance sheet rather than selling, making MARA one of the largest corporate Bitcoin holders in the world alongside its mining operations. This approach tied the company's financial performance explicitly to Bitcoin's price rather than treating mined Bitcoin as a commodity to liquidate. Thiel has been a public advocate for the U.S. mining industry in policy circles, arguing that domestic mining strengthens Bitcoin's decentralization and national energy security.

**Sources:**
- Marathon Digital Holdings SEC filings and annual reports
- MARA Bitcoin treasury holdings documentation
- Fred Thiel public statements and congressional testimony

---

## Core Scientific — Darin Feinstein & Adam Sullivan (dates unknown)
**Tier:** 3
**Role:** Public Bitcoin Mining & Hosting Company
**Active:** 2017–present

Built one of the largest Bitcoin mining and hosting operations in the U.S.; went public via SPAC in 2021; filed for bankruptcy in December 2022 amid the 2022 bear market and energy cost increases; and emerged from bankruptcy in January 2024 under CEO Adam Sullivan after restructuring. Core Scientific's SPAC listing, bankruptcy, and restructuring is a documented case study in industrial Bitcoin mining's exposure to simultaneous Bitcoin price decline and energy price increases. Co-founder Darin Feinstein has written publicly on Bitcoin mining and sustainable energy.

**Sources:**
- Core Scientific SEC filings and bankruptcy documentation (December 2022)
- Core Scientific emergence from bankruptcy (January 2024)
- Adam Sullivan CEO tenure documentation
- Darin Feinstein public statements on Bitcoin mining and energy

---

## CleanSpark — Zach Bradford (dates unknown)
**Tier:** 3
**Role:** Public Bitcoin Mining Company / Clean Energy Focus
**Active:** 2020–present (mining focus)

Built one of the fastest-growing publicly traded Bitcoin mining operations with an explicit focus on low-carbon and sustainable energy sources, primarily in Georgia and Nevada. CEO Zach Bradford has made clean energy sourcing a defining feature of CleanSpark's investor communications, and the company grew during the 2022–2023 bear market period when multiple competitors went bankrupt or faced distress. CleanSpark's energy sourcing is documented in its SEC filings and investor materials.

**Sources:**
- CleanSpark SEC filings and annual reports
- CleanSpark energy sourcing documentation
- Zach Bradford public statements and investor communications

---

## Foundry — Mike Colyer (dates unknown)
**Tier:** 3
**Role:** Bitcoin Mining Pool & Equipment Financier / DCG Subsidiary
**Active:** 2019–present

Founded by DCG (Barry Silbert) as a Bitcoin mining services company; Foundry USA Pool became the largest or second-largest Bitcoin mining pool in the world by hashrate, consistently controlling 25–30% of global block production at its peak. Foundry's concentration of pool hashrate raised centralization concerns at the pool layer analogous to earlier concerns about Bitmain's hardware dominance; its DCG parentage is notable given DCG's simultaneous involvement in custody (Grayscale), lending (Genesis), and media (CoinDesk). It also became the dominant U.S.-based pool during the period of active industry de-risking from Chinese mining concentration following the 2021 China ban.

**Sources:**
- Foundry USA Pool hashrate statistics
- DCG / Foundry company documentation
- Bitcoin mining pool distribution tracking (mempool.space, etc.)

---

## Bitfarms — (various leadership)
**Tier:** 3
**Role:** Public Bitcoin Mining Company / Canadian Pioneer
**Active:** 2017–present

One of the oldest publicly traded Bitcoin mining companies, founded in Canada with operations across Canada, Argentina, Paraguay, and the U.S., built predominantly on hydroelectric power; survived the 2018 and 2022 bear markets and operated internationally when most publicly traded U.S. miners were domestically focused. In 2024, Riot Platforms made a hostile takeover attempt that Bitfarms ultimately rejected — a documented episode in the consolidation of the public Bitcoin mining sector. Its hydroelectric power sourcing in Canada and South America is documented in its SEC filings.

**Sources:**
- Bitfarms SEC filings and annual reports
- Riot Platforms hostile takeover attempt documentation (2024)
- Bitfarms international operations documentation

---

## Iris Energy — Daniel & William Roberts (dates unknown)
**Tier:** 3
**Role:** Public Bitcoin Mining Company / Renewable Energy Focus
**Active:** 2018–present

Australian-founded Bitcoin mining company, co-founded by brothers Daniel and William Roberts, operating predominantly on renewable energy — primarily hydroelectric — in Canada and the U.S.; publicly listed on Nasdaq. Iris Energy has pursued a dual strategy of Bitcoin mining and AI/high-performance computing (HPC) using the same data center infrastructure, making it an early documented case of a Bitcoin mining company diversifying into high-performance compute. Its renewable energy usage is documented in its SEC filings and investor communications.

**Sources:**
- Iris Energy SEC filings and annual reports (IREN)
- Iris Energy renewable energy and HPC documentation
- Daniel and William Roberts investor communications

---

## Bitdeer Technologies — Jihan Wu (dates unknown)
**Tier:** 3
**Role:** Bitcoin Mining Hosting & Hardware Company / Bitmain Spin-off
**Active:** 2021–present

Founded by Jihan Wu following his departure from Bitmain; operates Bitcoin mining hosting facilities globally and has developed its own ASIC mining hardware (Sealminer), making it one of the few companies to compete with Bitmain in chip design; listed on Nasdaq via SPAC. Bitdeer's Sealminer chip development is a documented attempt to compete in the Bitcoin ASIC hardware market, which Bitmain has long dominated. The company's global facility footprint reflects the post-China-ban dispersal of Bitcoin mining infrastructure.

**Sources:**
- Bitdeer Technologies SEC filings and annual reports
- Sealminer ASIC chip development documentation
- Bitdeer Nasdaq listing via SPAC documentation

---

## Ross Stevens — NYDIG (dates unknown)
**Tier:** 3
**Role:** Founder, NYDIG / Institutional Bitcoin Pioneer
**Active:** 2017–present

Founded NYDIG (New York Digital Investment Group) as a Bitcoin-only subsidiary of Stone Ridge Holdings, becoming one of the largest institutional Bitcoin custodians and financial infrastructure providers in the U.S. NYDIG's partnerships with U.S. Bank, Ally, and dozens of community banks brought Bitcoin purchasing to millions of existing banking customers without requiring separate exchange accounts. Stone Ridge Holdings itself became one of the larger corporate Bitcoin holders; both Stone Ridge and NYDIG's Bitcoin positions have been disclosed in regulatory filings. NYDIG's Bitcoin-only focus distinguished it from multi-asset crypto custodians in its positioning to conservative institutional counterparties.

**Sources:**
- NYDIG institutional documentation (nydig.com)
- Stone Ridge Holdings Bitcoin treasury disclosures
- NYDIG bank partnership announcements (U.S. Bank, Ally, et al.)

---

## Mike Novogratz — Galaxy Digital (1964–present)
**Tier:** 3
**Role:** Founder & CEO, Galaxy Digital
**Active:** 2018–present

Founded Galaxy Digital (2018), a full-service crypto merchant bank and asset manager, after a career as a Goldman Sachs partner and Fortress Investment Group macro trader. Galaxy has grown into an institutional player across trading, asset management, mining, and banking. Unlike NYDIG, Galaxy is not Bitcoin-only; its business spans the broader digital asset market, though Bitcoin has been central to its public positioning. Novogratz has been a frequent public commentator on Bitcoin and crypto markets and has publicly acknowledged when his price predictions were incorrect.

**Sources:**
- Galaxy Digital company documentation (galaxy.com)
- Novogratz public market commentary and interviews
- Galaxy Digital SEC filings

---

## Wolf — Ross Stevens & Kelly Brewster (founded 2022)
**Tier:** 3
**Role:** Bitcoin & Lightning Startup Accelerator
**Active:** 2022–present

A New York City-based Bitcoin and Lightning Network startup accelerator launched on October 26, 2022, by Stone Ridge Holdings Group — the parent company of NYDIG. Ross Stevens, founder and CEO of Stone Ridge and NYDIG, founded Wolf; Kelly Brewster, formerly CMO of NYDIG, serves as CEO. Wolf is an 8-week in-person accelerator program offering accepted teams a guaranteed $250,000 investment, with one winner per cohort receiving $750,000. Its inaugural cohort (Wolfpack 1) comprised eight teams and 23 founders from 10 countries, selected from over 100 applicants across 36 countries. Wolf is among the first accelerators focused exclusively on Bitcoin and Lightning infrastructure.

**Sources:**
- wolfnyc.com
- PRNewswire — Wolf launch announcement (October 2022)
- Bitcoin Magazine — Wolf first cohort (2023)
- TechCrunch — Wolfpack 1 coverage (May 2023)
- Cross-reference: Ross Stevens / NYDIG entry

---

## Ten31 (founded 2020)
**Tier:** 3
**Role:** Bitcoin-Only Venture Fund
**Active:** 2020–present

A Bitcoin-only venture fund co-founded and managed by Matt Odell and Marty Bent, launched formally on October 31, 2021 — the anniversary of the Bitcoin whitepaper. The fund name references that date. Ten31 invests exclusively in Bitcoin-focused companies and infrastructure, directing a portion of management fees to open-source Bitcoin development grants. The fund has deployed approximately $200 million across two funds, making it among the largest Bitcoin-focused venture platforms. Portfolio companies have included Bitcoin infrastructure, privacy tools, and freedom technology projects. Ten31's first portfolio company to achieve a public listing was GRIID Infrastructure (2024).

**Sources:**
- ten31.xyz; ten31.vc
- Bitcoin Magazine — Ten31 launch (October 31, 2021)
- BusinessWire — GRIID public listing (January 2024)
- Cross-reference: Matt Odell entry; Marty Bent entry

---

## Gabriel Kurman (dates unknown)
**Tier:** 3
**Role:** Bitcoin Circular Economy Advocate / Author / Entrepreneur
**Active:** 2012–present

An Argentine economist with a background in corporate finance and private equity who transitioned to Bitcoin full-time. Kurman co-founded Rootstock (RSK), a Bitcoin sidechain enabling smart contracts; Koibanx, a blockchain financial infrastructure company for Latin America; Bitcoin4Humanity (B4H); the Bitcoin Institute of Philosophy and Economy (IFEB); and La Bitcoineta, a mobile Bitcoin education and adoption initiative in Latin America. He co-authored *Bitcoin Circular Economies: Stories of Hope Built on the Sovereign Money of the Future* with Ivan Kaleja, documenting real-world Bitcoin circular economy projects in Latin America and Africa.

**Sources:**
- *Bitcoin Circular Economies* — Gabriel Kurman & Ivan Kaleja
- Bitcoin Magazine author archive
- Bitcoin 2026 speaker profile
- Rootstock / RSK documentation

---

## Ivan Kaleja (dates unknown)
**Tier:** 3
**Role:** Bitcoin Educator / Circular Economy Advocate
**Active:** 2014–present

A Venezuelan-based Bitcoin educator and advocate who began mining Bitcoin approximately a decade ago and built one of Venezuela's largest Bitcoin mining farms. In 2017 he launched a Spanish-language YouTube channel focused on Bitcoin education. Kaleja co-founded Bitcoin4Humanity alongside Gabriel Kurman and co-authored *Bitcoin Circular Economies: Stories of Hope Built on the Sovereign Money of the Future*, documenting grassroots Bitcoin adoption in Latin America and Africa. He has been a speaker at the Lugano Plan B Forum and other international Bitcoin conferences.

**Sources:**
- *Bitcoin Circular Economies* — Gabriel Kurman & Ivan Kaleja
- LinkedIn — Ivan Kaleja
- Lugano Plan B Forum (2024)

---

## Ego Death Capital — Jeff Booth, Nico Lechuga & Will Cole (dates unknown)
**Tier:** 3
**Role:** Bitcoin-Only Venture Fund
**Active:** 2021–present

Founded Ego Death Capital, a Bitcoin-only venture fund focused on the Lightning Network ecosystem, with Jeff Booth, Nico Lechuga, and Will Cole as co-founders. The fund is explicitly Bitcoin-only in a VC landscape crowded with multi-chain funds, and its investment thesis is grounded in Booth's *The Price of Tomorrow* framework — that technology is deflationary and Bitcoin is the monetary system compatible with a deflationary world. The fund has backed Lightning and Bitcoin-adjacent companies with that thesis as the filter.

**Sources:**
- Ego Death Capital portfolio and documentation
- *The Price of Tomorrow* (2020) — Jeff Booth
- Booth's public writing and podcast appearances

---

## Lightning Ventures — Mike Jarmuz (founded 2021)
**Tier:** 3
**Role:** Bitcoin-Only Venture Fund
**Active:** 2021–present

Bitcoin-only venture fund founded by Mike Jarmuz and headquartered in Buenos Aires, Argentina, focused exclusively on companies building products and services on Bitcoin. Lightning Ventures deployed a pilot fund investing in approximately 40 Bitcoin-only companies and built what it described as the world's largest Bitcoin-focused investing network, with over 2,000 members who collectively invested $6.8 million in Bitcoin-only startups across two fund vehicles, Node 1 Fund and Node 2 Fund. The team includes CTO Uncle Rockstar Dev, formerly of Strike and a contributor to BTCPay Server, and COO Vivek Patel, previously of PrimeTrust. Lightning Ventures later launched Thunder Funder, a Regulation CF crowdfunding portal enabling retail investors to participate in Bitcoin startup funding; the Thunder Funder pre-seed round drew participation from El Zonte Capital, Max Keiser, and Stacy Herbert. Jarmuz has spoken at Adopting Bitcoin conferences and advocates for Bitcoin-only venture capital as distinct from multi-chain crypto funds.

**Sources:**
- ltng.ventures
- Bitcoin Magazine — "The Future of Venture Capital Is Investing in Bitcoin-Only Companies"
- Bitcoin Magazine — Thunder Funder launch coverage (2024)
- PRWeb — Thunder Funder announcement (2024)

---

## Larry Fink (1952–present)
**Tier:** 3
**Role:** CEO, BlackRock / Bitcoin ETF Catalyst
**Active:** 2023–present

Filed BlackRock's iShares Bitcoin Trust ETF application with the SEC in June 2023, triggering a wave of institutional filings; IBIT was approved in January 2024 and accumulated over $50 billion in assets in its first year, a documented ETF inflow record. Fink had previously stated publicly that Bitcoin was "an index of money laundering" and publicly described Bitcoin as "digital gold" and a legitimate portfolio asset in multiple 2024 investor communications. BlackRock's approximately $10 trillion AUM made its ETF filing a benchmark event in Bitcoin's institutional adoption timeline.

**Sources:**
- BlackRock iShares Bitcoin Trust S-1 filing (June 2023)
- IBIT launch and AUM tracking (January 2024–present)
- Fink's public statements on Bitcoin (2023–2024)
- BlackRock investor communications

---

## Gary Gensler (1957–present)
**Tier:** 3
**Role:** SEC Chairman / Regulatory Antagonist
**Active:** 2021–2025

Served as SEC Chairman from 2021 to January 2025; repeatedly delayed and rejected spot Bitcoin ETF applications while approving Bitcoin futures ETFs; and presided over enforcement actions against Coinbase, Binance, Ripple, and others; resigned upon Trump's inauguration. Gensler had taught a course on Bitcoin at MIT prior to his appointment. His rejection of Grayscale's ETF application was overturned by the DC Circuit Court in August 2023 as "arbitrary and capricious," the ruling that cleared the path for January 2024 approvals. His departure marked a documented regulatory shift in the SEC's approach to Bitcoin and digital assets.

**Sources:**
- SEC v. Coinbase (2023)
- Grayscale Investments v. SEC (DC Circuit, August 2023)
- Gensler's MIT Bitcoin course materials (2018)
- SEC spot ETF rejection letters (2021–2023)
- Gensler resignation (January 2025)

---

## Michael Sonnenshein (1984–present)
**Tier:** 3
**Role:** CEO, Grayscale Investments
**Active:** 2021–2024

Led Grayscale's legal battle against the SEC after it rejected the conversion of GBTC into a spot ETF; the DC Circuit Court ruled in Grayscale's favor in August 2023, finding the SEC's reasoning "arbitrary and capricious" — the ruling that cleared the legal basis for rejecting all spot Bitcoin ETFs and made January 2024 approvals possible. GBTC converted to a spot ETF in January 2024 alongside BlackRock, Fidelity, and others. Following conversion, GBTC experienced substantial outflows as investors moved to lower-fee competing ETFs, a dynamic documented in ETF flow data for 2024.

**Sources:**
- Grayscale Investments v. SEC (DC Circuit Court, August 2023)
- GBTC conversion to spot ETF (January 2024)
- GBTC outflow data (2024)
- Sonnenshein public statements and interviews

---

## Cathie Wood / ARK Invest (Wood: 1955–present)
**Tier:** 3
**Role:** Fund Manager / ETF Applicant
**Active:** 2021–present

Filed for a spot Bitcoin ETF through ARK Invest's partnership with 21Shares more times and over a longer period than any other applicant before the January 2024 approval, with each rejection and re-filing extending the documented record of SEC denials. ARK's Bitcoin price predictions — publicly stated at $1 million or more per coin — generated significant commentary. The ARK 21Shares Bitcoin ETF (ARKB) was among the January 2024 approvals.

**Sources:**
- ARK 21Shares Bitcoin ETF (ARKB) filing history (2021–2024)
- ARK Invest Bitcoin research and price target documentation
- SEC rejection letters to ARK (2022–2023)
- ARKB approval and launch (January 2024)

---

## Stephen Ehrlich — Voyager Digital (dates unknown)
**Tier:** 3
**Role:** Co-Founder & CEO, Voyager Digital
**Active:** 2018–2022

Co-founded Voyager Digital (2018), a publicly traded crypto brokerage offering interest-bearing accounts that collapsed in July 2022 after Three Arrows Capital defaulted on a $650 million loan Voyager had extended to the hedge fund; filed for bankruptcy July 5, 2022 with 3.5 million customers locked out of their funds. Voyager had publicly stated that customer funds were FDIC insured; the FDIC and FTC disputed this characterization and the FTC later charged Ehrlich for the misrepresentation. FTX bid for Voyager's assets; that bid collapsed when FTX itself failed. Coinbase eventually acquired Voyager's customer accounts. The case is documented in bankruptcy records and FTC regulatory actions.

**Sources:**
- Voyager Digital bankruptcy filings (July 2022)
- FTC charges against Stephen Ehrlich (FDIC misrepresentation)
- 3AC default documentation
- FTX bid for Voyager assets (failed, November 2022)
- Coinbase acquisition of Voyager customer accounts

---

## Alex Mashinsky (1965–present)
**Tier:** 3
**Role:** Founder & CEO, Celsius Network / Convicted Fraudster
**Active:** 2017–2022

Founded Celsius Network (2017), a crypto lending platform promising high yields on deposited Bitcoin and crypto; froze all withdrawals in June 2022 with $4.7 billion in customer funds locked; filed for bankruptcy July 2022; was arrested in July 2023 on fraud and market manipulation charges; and pleaded guilty in December 2024. Celsius had over 1.7 million customers at the time of its collapse; court filings documented $4.7 billion in customer claims. Mashinsky's marketing employed anti-bank rhetoric while the platform was alleged to have manipulated the CEL token price and misrepresented its financial health. The Celsius collapse is documented in bankruptcy filings and DOJ criminal records and is a reference case in discussions of custodial crypto lending risk.

**Sources:**
- DOJ criminal complaint against Alex Mashinsky (July 2023)
- Celsius Network bankruptcy filings (July 2022)
- Mashinsky guilty plea (December 2024)
- *Number Go Up* (2023) — Zeke Faux

---

## Su Zhu & Kyle Davies — Three Arrows Capital / 3AC (dates unknown)
**Tier:** 3
**Role:** Founders, Three Arrows Capital
**Active:** 2012–2022

Co-founded Three Arrows Capital (3AC), one of the largest crypto hedge funds, which collapsed in June 2022 after leveraged positions in LUNA/Terra were wiped out; the default triggered the first and most destructive domino in the 2022 crypto credit contagion. The fund had borrowed from Genesis Trading, Voyager, BlockFi, and others, all of which suffered losses when 3AC defaulted; the cascading effects contributed to the conditions that eventually brought down FTX. Zhu and Davies fled to Dubai, were held in contempt by a British Virgin Islands court, and Zhu was later briefly arrested in Singapore.

**Sources:**
- 3AC bankruptcy filings (British Virgin Islands, July 2022)
- Genesis Trading losses from 3AC default
- Su Zhu and Kyle Davies contempt proceedings
- *Number Go Up* (2023) — Zeke Faux

---

## Prime Trust (founded 2016, collapsed 2023)
**Tier:** 3
**Role:** Crypto Custodian / Trust Company
**Active:** 2016–2023

A Nevada-chartered trust company that served as custodian for dozens of crypto companies including Swan Bitcoin; placed into receivership by Nevada regulators in August 2023 after a shortfall of approximately $82 million in customer funds was discovered. Swan Bitcoin was among the companies forced to find new custody arrangements when Prime Trust was seized. The collapse demonstrated that regulated, state-chartered custodians holding Bitcoin on behalf of other companies are not immune to failure, and is documented in Nevada regulatory orders and bankruptcy filings.

**Sources:**
- Nevada Financial Institutions Division receivership order (August 2023)
- Prime Trust bankruptcy filings
- Swan Bitcoin customer communications on Prime Trust transition

---

## Zac Prince — BlockFi (dates unknown)
**Tier:** 3
**Role:** Co-Founder & CEO, BlockFi
**Active:** 2017–2022

Co-founded BlockFi (2017), a crypto lending and interest platform; accepted an emergency $400 million credit facility from FTX in June 2022 following losses from the 3AC default; filed for bankruptcy in November 2022 days after FTX collapsed. BlockFi had paid a $100 million SEC and state securities regulator settlement in early 2022 over its interest accounts. Approximately 600,000 BlockFi customers lost access to funds when the company filed for bankruptcy. The sequence — damaged by 3AC, temporarily rescued by FTX, then collapsed when FTX failed — is documented in bankruptcy filings as a case study in 2022 crypto credit contagion.

**Sources:**
- BlockFi bankruptcy filings (November 2022)
- BlockFi / FTX credit facility documentation (June 2022)
- BlockFi SEC settlement ($100 million, February 2022)
- *Number Go Up* (2023) — Zeke Faux

---

## QuadrigaCX — Gerald Cotten (founded 2013, collapsed 2019)
**Tier:** 3
**Role:** Canadian Exchange / Collapse Case Study
**Active:** 2013–2019

Canada's largest cryptocurrency exchange, founded by Gerald Cotten and Michael Patryn (later revealed to be Omar Dhanani, a convicted identity thief). The exchange collapsed in January 2019 following Cotten's death in India in December 2018, with Cotten's widow Jennifer Robertson claiming that approximately CAD $250 million in customer funds were inaccessible because only Cotten held the private keys. A subsequent investigation by the Ontario Securities Commission (OSC) found that Cotten had been operating QuadrigaCX as a fraud for years — using customer deposits to fund personal trading losses and lifestyle expenses, with fabricated exchange balances. The OSC report (2020) concluded the exchange had been insolvent long before Cotten's death. Cotten's death and the circumstances surrounding the missing funds generated persistent public speculation documented in the Netflix documentary *Trust No One: The Hunt for the Crypto King* (2022).

**Sources:**
- Ontario Securities Commission investigation report (2020)
- *Bitcoin Widow* — Jennifer Robertson (2022)
- *Trust No One: The Hunt for the Crypto King* (Netflix, 2022)
- Court filings

---

## Sam Bankman-Fried / SBF (1992–present)
**Tier:** 3
**Role:** Founder, FTX / Alameda Research / Convicted Fraudster
**Active:** 2019–2022

Founded FTX (2019), which became the world's second-largest crypto exchange; simultaneously ran Alameda Research, a trading firm that secretly used FTX customer funds; arrested in December 2022 after FTX collapsed; convicted on seven counts of fraud and conspiracy in November 2023; and sentenced to 25 years in prison. FTX's collapse resulted in an estimated $8 billion in misappropriated customer funds and triggered documented contagion at Genesis, BlockFi, Celsius, and Voyager. The case is documented in DOJ criminal records, trial transcripts, and FTX bankruptcy filings and is a reference point in discussions of custodial exchange risk.

**Sources:**
- DOJ criminal complaint and indictment against SBF (December 2022)
- *Going Infinite* (2023) — Michael Lewis
- *Number Go Up* (2023) — Zeke Faux
- FTX bankruptcy filings (November 2022)
- SBF trial transcripts and sentencing documents (2023–2024)

---

## Caroline Ellison (1994–present)
**Tier:** 3
**Role:** CEO, Alameda Research / Cooperating Witness
**Active:** 2019–2022

Served as CEO of Alameda Research, FTX's sister trading firm, and as SBF's romantic partner; cooperated with federal prosecutors after FTX's collapse and testified against SBF at trial. Her testimony detailed Alameda's use of FTX customer funds, the spreadsheets used to track positions, and the decision-making chain; her personal journals were entered into evidence. She was sentenced to 24 months in November 2024, significantly below the government's recommended range, reflecting her cooperation. The cooperation agreement and trial testimony are documented in court records.

**Sources:**
- DOJ cooperation agreement with Caroline Ellison
- Ellison trial testimony transcripts (2023)
- *Going Infinite* (2023) — Michael Lewis
- *Number Go Up* (2023) — Zeke Faux

---

## Changpeng Zhao / CZ (1977–present)
**Tier:** 3
**Role:** Founder & CEO, Binance
**Active:** 2017–present

Founded Binance (2017), which became the world's largest crypto exchange by volume; his November 2022 tweet announcing Binance would liquidate its FTX Token (FTT) holdings triggered the bank run that collapsed FTX; pleaded guilty to AML violations and stepped down as Binance CEO in November 2023; and was sentenced to four months in prison. Binance subsequently reached a $4.3 billion DOJ settlement in November 2023, resolving AML and sanctions violations. CZ's four-month sentence drew significant commentary given the scale of the violations; it is documented in DOJ sentencing records.

**Sources:**
- CZ's FTT liquidation tweet (November 6, 2022)
- DOJ settlement with Binance ($4.3 billion, November 2023)
- CZ sentencing documents (2024)
- *Number Go Up* (2023) — Zeke Faux

---

## Bitcoin Beach / El Zonte — Mike Peterson & Community (dates unknown)
**Tier:** 2
**Role:** Circular Economy Pioneers / Bitcoin Legal Tender Catalyst
**Active:** 2019–present

Mike Peterson and local organizers including Jorge Valenzuela and Roman Martinez built the world's first Bitcoin circular economy in El Zonte, a small coastal village in El Salvador, beginning in 2019 after an anonymous donor gave a large Bitcoin gift on the condition that it be used as Bitcoin — not converted to dollars — to benefit local residents. Peterson's team built a Lightning-based merchant network in El Zonte before Lightning wallets were widely available. Galoy Money (now Blink) built the Bitcoin Beach Wallet that powered the community's transactions. Bitcoin Beach is documented in multiple accounts as influential on President Bukele's decision to propose the Bitcoin Law of 2021; Jack Mallers and other figures visited El Zonte prior to the law's passage.

**Sources:**
- Bitcoin Beach documentation (bitcoinbeach.com)
- Mike Peterson interviews and community documentation
- Galoy Money / Blink wallet history (blink.sv)
- Coverage of El Zonte as inspiration for El Salvador Bitcoin Law

---

## Nayib Bukele & El Salvador (Bukele: 1981–present)
**Tier:** 3
**Role:** President of El Salvador / First Bitcoin Legal Tender Nation
**Active:** 2021–present

As President of El Salvador, passed the Bitcoin Law (June 2021) making Bitcoin legal tender — the first nation in history to do so — launched the Chivo government wallet with $30 in BTC for every citizen, and accumulated Bitcoin for the national treasury. El Salvador's Bitcoin Law generated documented international responses including an IMF pressure campaign and World Bank refusal to assist with implementation. In early 2025, El Salvador removed Bitcoin's mandatory legal tender status as a condition of an IMF loan agreement while retaining national Bitcoin holdings in a state fund. The experiment produced documented data on Lightning infrastructure deployment, merchant acceptance rates, and Chivo wallet usage.

**Sources:**
- El Salvador Bitcoin Law (June 2021)
- Chivo wallet launch documentation
- IMF negotiations and El Salvador Bitcoin legal tender removal (2025)
- Bitcoin Beach / Hope House documentation (El Zonte)
- El Salvador national Bitcoin treasury tracking

---

## Jack Mallers (1994–present)
**Tier:** 3
**Role:** Founder & CEO, Strike / Lightning Payments Pioneer
**Active:** 2019–present

Founded Strike, a Lightning-native payments application; announced El Salvador's Bitcoin Law adoption on the Bitcoin 2021 conference mainstage in Miami; and built Strike into an international Bitcoin payments platform. Strike provided documented infrastructure for Lightning payments deployed across El Salvador and has expanded into cross-border Bitcoin remittances with documented payment corridors between the U.S. and the Philippines, West Africa, and Latin America. Mallers has testified before Congress on Bitcoin payment infrastructure.

**Sources:**
- Jack Mallers / Strike Bitcoin 2021 Miami announcement (June 2021)
- Strike documentation (strike.me)
- El Salvador Bitcoin Law implementation coverage

---

## Samson Mow (dates unknown)
**Tier:** 3
**Role:** Bitcoin Nation-State Adoption Strategist / Jan3 Founder
**Active:** 2017–present

Former CSO of Blockstream who founded Jan3, a company dedicated to accelerating Bitcoin adoption at the nation-state level; architected the Volcano Bonds concept for El Salvador, a proposal for Bitcoin-backed bonds to fund Bitcoin City and national debt; and has advised multiple sovereign governments on Bitcoin policy and adoption strategy including in Bhutan. The Volcano Bonds proposal was delayed by market conditions but established a documented template for nation-state Bitcoin financial instruments. Mow's advisory work at the intersection of Bitcoin and sovereign governments is documented in Jan3's public materials and conference appearances.

**Sources:**
- Jan3 company documentation (jan3.com)
- Volcano Bonds / El Salvador Bitcoin bond proposal
- Mow's public statements and conference appearances
- Blockstream CSO tenure documentation

---

## Max Keiser & Stacy Herbert (Keiser: 1960–present)
**Tier:** 3
**Role:** Bitcoin Advocates / El Salvador Advisors
**Active:** 2011–present

Among the earliest and most sustained mainstream media Bitcoin advocates — Keiser publicly predicted Bitcoin's rise on his RT program *The Keiser Report* beginning in 2011, one of the longer-running Bitcoin advocacy presences in broadcast media. Both relocated to El Salvador, where Keiser has described an advisory relationship with President Bukele on Bitcoin policy and Herbert became editor of the Bitcoin Magazine El Salvador edition. Both are documented participants in El Salvador's Bitcoin adoption story through their public statements and editorial work.

**Sources:**
- *The Keiser Report* — RT (2011–present)
- Max Keiser El Salvador advisory role documentation
- Bitcoin Magazine El Salvador edition — Stacy Herbert

---

## Julian Assange (1971–present)
**Tier:** 3
**Role:** WikiLeaks Founder / Bitcoin's First Censorship-Resistance Test
**Active:** 2010–present (Bitcoin-relevant)

Founded WikiLeaks, which became one of the first organizations to accept Bitcoin donations in 2011 after Visa, Mastercard, PayPal, and Bank of America blocked payments to the organization following U.S. government pressure. The WikiLeaks payment blockade documented the financial system's centralized chokepoints in a high-profile, adversarial context. Satoshi Nakamoto's response is historically notable: he posted on Bitcointalk expressing concern, writing "I wish you wouldn't have done this… it would have been better to grow more quietly," indicating concern about premature regulatory attention. WikiLeaks raised significant Bitcoin donations over subsequent years, and Assange was released in 2024 after a plea deal following years of confinement in the Ecuadorian embassy in London and Belmarsh prison.

**Sources:**
- WikiLeaks Bitcoin donation address history (2011)
- Satoshi Nakamoto's Bitcointalk post on WikiLeaks (December 2010)
- WikiLeaks payment blockade documentation (Visa, Mastercard, PayPal, 2010)
- Assange plea deal and release documentation (2024)

---

## Edward Snowden (1983–present)
**Tier:** 3
**Role:** NSA Whistleblower / Surveillance Critic / Bitcoin Advocate
**Active:** 2013–present (Bitcoin-relevant)

Leaked NSA classified documents in 2013 revealing the scope of global mass surveillance programs; subsequently became a prominent advocate for privacy tools including Bitcoin, living in exile in Russia; documented that he purchased his first Bitcoin using the leaked documents' proceeds routed through privacy tools. The Snowden revelations documented government mass surveillance of financial transaction metadata and communications and provided a factual basis for Bitcoin's financial privacy use case. His critique of Bitcoin's on-chain traceability has also been a documented influence on Bitcoin privacy tool development discussions.

**Sources:**
- Snowden NSA document leaks (June 2013)
- *Permanent Record* (2019) — Edward Snowden
- Snowden's Bitcoin and privacy advocacy (Twitter/X, interviews)
- Snowden's first Bitcoin purchase documentation

---

## Alex Gladstein (dates unknown)
**Tier:** 3
**Role:** Chief Strategy Officer, Human Rights Foundation / Bitcoin & Human Rights Advocate
**Active:** 2014–present (Bitcoin-relevant)

As CSO of the Human Rights Foundation, has published documented interviews and essays on Bitcoin's use by people under authoritarian regimes, hyperinflation, and financial censorship in Venezuela, Afghanistan, Nigeria, Belarus, and other contexts, making his work a primary source for humanitarian Bitcoin use cases. Authored "Check Your Financial Privilege" and numerous other essays. The Human Rights Foundation's Oslo Freedom Forum has featured Bitcoin discussions in a human rights context, and HRF's developer grant program funds Bitcoin privacy tools. His writing on CBDCs focuses on their potential for government surveillance and financial control.

**Sources:**
- "Check Your Financial Privilege" — Alex Gladstein (Bitcoin Magazine, 2022)
- Human Rights Foundation Bitcoin documentation (hrf.org)
- HRF Bitcoin developer grant program
- Gladstein's books and collected essays on Bitcoin and human rights
- Oslo Freedom Forum Bitcoin programming

---

## Farida Bemba Nabourema (1990–present)
**Tier:** 3
**Role:** Human Rights Activist / Bitcoin Advocate / Africa Bitcoin Conference Founder
**Active:** 2010s–present (Bitcoin advocacy c. 2020–present)

Togolese activist, pan-Africanist, and writer born in 1990 in Lomé, Togo, into a family with a long history of political resistance — her father, Bemba Nabourema, was an active opponent of the military regime that has controlled Togo since 1967. She serves as Executive Director of the Togolese Civil League and has advocated for democracy and human rights in Togo since her teenage years. Nabourema adopted Bitcoin as a tool to fund civic resistance movements after discovering that her country's repressive government was monitoring and blocking money transfers to democracy activists; she has reported sending Bitcoin into Togo to fund civil resistance without government interdiction. She has connected Bitcoin to the CFA franc question — the colonial-era currency imposed on 14 Francophone African nations — framing monetary sovereignty as a human rights issue and Bitcoin as a path toward financial independence from external monetary control. She founded the Africa Bitcoin Conference (ABC), an annual gathering held each December that draws Bitcoiners from over 40 African countries and the African diaspora. She has spoken at the Oslo Freedom Forum, BTC Prague, and other international Bitcoin events, and is a Forbes contributor.

**Sources:**
- nabourema.info
- Bitcoin Magazine — "Togolese Activist Farida Nabourema Finds Freedom in Bitcoin"
- Blockworks — "Why Bitcoin is key for resistance movements in Togo"
- This Is Africa — "The daughter of Togo and the money they cannot seize"
- Guardian Nigeria — HRF backs Africa Bitcoin Conference
- Forbes — Farida Nabourema contributor page

---

## Vitalik Buterin (1994–present)
**Tier:** 3
**Role:** Ethereum Founder / Bitcoin Alumnus
**Active:** 2011–present

Co-founded Bitcoin Magazine (2012) as a Bitcoin journalist and enthusiast; proposed Ethereum (2013) after concluding Bitcoin's scripting language was too limited for general programmability; and launched Ethereum in 2015. Buterin wrote for Bitcoin Magazine in its early years before departing to build a separate programmable blockchain. Ethereum's subsequent emergence as the dominant alternative to Bitcoin crystallized the Bitcoin vs. general-purpose blockchain debate that continues in Bitcoin developer and philosophical discussions. Bitcoin Magazine was Buterin's early publishing platform before the two projects diverged.

**Sources:**
- Early Bitcoin Magazine articles — Vitalik Buterin (2012)
- Ethereum whitepaper (2013) — Vitalik Buterin
- *The Cryptopians* — Laura Shin

---

## Erik Voorhees (1988–present)
**Tier:** 3
**Role:** Entrepreneur / Libertarian Advocate
**Active:** 2012–present

Founded SatoshiDice (2012), one of the first Bitcoin gambling sites and briefly responsible for a significant share of all Bitcoin on-chain transactions; later founded ShapeShift, an early non-custodial crypto exchange. SatoshiDice drew an SEC settlement in 2014, making Voorhees one of the first Bitcoin entrepreneurs to navigate the SEC's regulatory frontier. ShapeShift later pivoted to full KYC compliance under regulatory pressure — a decision Voorhees addressed publicly — illustrating the tension between Bitcoin's permissionless design philosophy and institutional regulatory requirements.

**Sources:**
- SEC settlement documents (2014)
- ShapeShift KYC announcement and Voorhees's response (2018)
- Voorhees's public writing and podcast appearances

---

## Barry Silbert (1976–present)
**Tier:** 3
**Role:** Investor / Digital Currency Group Founder
**Active:** 2012–present

Founded Digital Currency Group (DCG), owning Grayscale (GBTC), Genesis Trading, CoinDesk, and numerous other investments. Grayscale's GBTC was the dominant institutional Bitcoin vehicle before spot ETFs existed; its premium/discount to NAV was widely tracked as a metric of institutional sentiment. Genesis Trading, a DCG subsidiary, was one of Three Arrows Capital's largest creditors and lost hundreds of millions when 3AC collapsed in June 2022; Genesis subsequently froze withdrawals following FTX's collapse in November 2022, trapping billions including Gemini Earn users' deposits. DCG's 2022–2023 difficulties are documented in bankruptcy filings and regulatory actions as a case study in interconnected leverage across crypto custodians and lenders.

**Sources:**
- DCG portfolio documentation
- Genesis Trading bankruptcy filings (2023)
- Gemini Earn lawsuit documentation
- *Coindesk* coverage of DCG collapse

---

## Soichiro "Michael" Moro (dates unknown)
**Tier:** 3
**Role:** CEO, Genesis Global Trading (2014–2022)
**Active:** 2014–2022

Former Citi executive who served as CEO of Genesis Global Trading, a DCG subsidiary and one of the largest institutional crypto OTC trading and lending desks, for nearly a decade beginning in 2014. Genesis launched its institutional OTC desk in 2013 and under Moro's tenure grew into a major counterparty for institutional Bitcoin borrowing and lending, accumulating billions in loan exposure. When Three Arrows Capital defaulted on approximately $2.36 billion owed to Genesis in June 2022, the firm absorbed losses that destabilized its balance sheet; Genesis subsequently froze withdrawals in November 2022 following FTX's collapse, trapping billions in customer funds including deposits from Gemini Earn users. Moro stepped down as CEO in August 2022 as Genesis cut 20% of its workforce. In January 2025, DCG and Moro agreed to pay a combined $38.5 million to settle SEC securities fraud charges; the SEC alleged that Moro made false or misleading public statements on social media characterizing Genesis's balance sheet as strong and falsely claiming the firm had shed risk related to the 3AC default.

**Sources:**
- CoinDesk — "Crypto Broker Genesis Cutting 20% of Workforce as CEO Michael Moro Exits" (August 2022)
- SEC press release — SEC v. DCG and Moro (January 2025)
- Bloomberg — Genesis CEO Steps Down (August 2022)
- Coalition Greenwich — Michael Moro CEO profile

---

## Anita Posch (dates unknown)
**Tier:** 3
**Role:** Bitcoin Educator / Author / Africa Advocate
**Active:** 2017–present

Founded Bitcoin for Fairness, a non-profit focused on Bitcoin education in the Global South, particularly Sub-Saharan Africa, and authored *Learn Bitcoin* and *Bitcoin: Sovereignty through Mathematics*. She has conducted documented on-the-ground education work in Zimbabwe, Zambia, and other African nations, training local educators and producing firsthand accounts of Bitcoin use by people under hyperinflation, banking exclusion, and currency controls. Her field documentation is cited in Bitcoin humanitarian adoption discussions in this reference and elsewhere.

**Sources:**
- Bitcoin for Fairness (bitcoinisfairness.com)
- *Learn Bitcoin* — Anita Posch
- *Bitcoin: Sovereignty through Mathematics* — Anita Posch
- Posch's podcast and field documentation from Zimbabwe and Zambia

---

## Ray Youssef (1977–present)
**Tier:** 3
**Role:** Entrepreneur / Financial Inclusion Advocate
**Active:** 2015–present

Co-founded Paxful (2015), a peer-to-peer Bitcoin marketplace that became a major platform for Bitcoin adoption in Africa and the developing world, enabling purchases via gift cards, mobile money, and hundreds of other local payment methods — enabling Bitcoin trading in regions where traditional exchange onboarding was unavailable or impractical. Paxful recorded significant volume in Nigeria, Ghana, and other African markets. Youssef's "Built with Bitcoin" foundation funded documented infrastructure projects in Africa. Paxful shut down in 2023 following a public dispute between Youssef and co-founder Artur Schaback, with Youssef attributing the shutdown to the partner conflict and legal and regulatory pressures.

**Sources:**
- Paxful platform history and documentation
- "Built with Bitcoin" foundation reports
- Paxful shutdown announcement (2023)

---

## Mircea Popescu (1980–2021)
**Tier:** 3
**Role:** Early Large Holder / Bitcoin Exchange Operator / Provocateur
**Active:** 2011–2021

Ran MPEX, one of Bitcoin's earliest Bitcoin-denominated securities exchanges, and was among the first to accumulate Bitcoin at significant scale. His blog Trilema was a prolific and often abrasive commentary on Bitcoin, finance, and culture that had a documented readership in early Bitcoin culture for a decade. He drowned in Costa Rica in June 2021; his estate's Bitcoin holdings were subsequently reported on, though exact figures are unverified.

**Sources:**
- Trilema blog archive (trilema.com)
- MPEX documentation and history
- Popescu estate reporting (2021)

---

## The Most Serene Republic of Bitcoin (TMSR) — Popescu's Web of Trust (2012–2021)
**Tier:** 3
**Role:** Radical Bitcoin Subculture / Alternative Governance Experiment
**Active:** 2012–2021

"The Most Serene Republic of Bitcoin" was Mircea Popescu's attempt to build an alternative sovereignty structure around Bitcoin — a self-declared jurisdiction with its own web of trust, laws, and culture, operating through his Trilema blog, the #bitcoin-assets IRC channel, and MPEX. Key figures included hanbot (Popescu's long-term associate and executor of his estate), asciilifeform (Stanislav Datskovskiy, a programmer and hardware researcher who wrote extensively at loper-os.org), ben_vulpes (a Portland-based developer), and mod6 and trinque, who maintained "Trb" (The Real Bitcoin) — a conservative, stripped-down fork of Bitcoin Core that TMSR considered the legitimate node implementation. TMSR's web of trust was more rigorous than bitcoin-otc's, requiring PGP-authenticated communication; the IRC log archive and the writing of its participants constitute a primary source for a strain of early Bitcoin culture not covered in mainstream Bitcoin histories. Most members scattered or went silent following Popescu's death in 2021.

**Sources:**
- Trilema blog archive (trilema.com) — Mircea Popescu
- #bitcoin-assets IRC log archives
- asciilifeform's blog (loper-os.org) — Stanislav Datskovskiy
- Trb (The Real Bitcoin) documentation
- hanbot blog and estate documentation

---

## Casey Rodarmor & Ordinals (Rodarmor: dates unknown)
**Tier:** 3
**Role:** Developer / Ordinals Protocol Creator
**Active:** 2022–present

Created the Ordinals protocol (January 2023), which assigned sequential numbers to individual satoshis and enabled "inscriptions" — arbitrary data (images, text, video, code) embedded into Bitcoin transactions via witness data — and subsequently created Runes (2024), a more efficient fungible token protocol on Bitcoin. The Ordinals protocol's launch generated documented fee spikes and block space congestion. The subsequent debate divided the Bitcoin developer and user community: proponents argued valid transactions cannot be censored under Bitcoin's rules; critics argued inscriptions are spam that prices out monetary transactions and represents a misuse of witness data capacity. The Ordinals debate has directly influenced the Core/Knots controversy and ongoing discussions of Bitcoin's fee market.

**Sources:**
- Ordinals documentation (ordinals.com)
- Rodarmor's Ordinals specification and launch documentation (January 2023)
- Runes protocol documentation (2024)
- BRC-20 token standard documentation

---

## The Core / Knots Controversy — Bitcoin's Node Policy War (2023–present)
**Tier:** 3
**Role:** Governance Controversy / Node Policy Debate
**Active:** 2023–present

An ongoing and unresolved conflict between Bitcoin Core (the dominant node implementation) and Bitcoin Knots (Luke Dashjr's implementation) over how nodes should handle Ordinals inscriptions and data-carrying transactions, crystallizing into the 2024 OP_RETURN limit debate when Core developers proposed removing the 83-byte default cap on OP_RETURN outputs. Bitcoin Knots added filters to reject inscription transactions as non-standard, treating them as spam; Bitcoin Core's majority view held that if transactions are valid per consensus rules, nodes should relay them. The 2024 proposal to remove the OP_RETURN byte limit became a flashpoint — Core developers argued the limit served no purpose if already circumventable via witness data; Knots supporters argued removing it was capitulation to spam use of the protocol. Luke Dashjr's role in Bitcoin Knots is central to this controversy and is covered in his separate entry.

**Sources:**
- Bitcoin Core PR #29519 (OP_RETURN limit removal proposal, 2024)
- Bitcoin Knots inscription filtering documentation
- Ordinals community and Bitcoin community debate archives
- Luke Dashjr public statements on inscription filtering (cross-reference: Luke Dashjr entry)

---

## E-Gold / Douglas Jackson (1960s–present)
**Tier:** 3
**Role:** Founder, e-gold
**Active:** 1996–2009

Built e-gold, the first widely-used digital currency backed by gold, which reached millions of users before the U.S. government shut it down in 2008 via a DOJ indictment for operating an unlicensed money transmitting business. E-gold's shutdown in 2008 is part of the context of failed centralized digital money systems that preceded Bitcoin's launch the same year.

**Sources:** *The Genesis Book* — Aaron van Wirdum; DOJ indictment (2007)

---

## Francis Pouliot (dates unknown)
**Tier:** 2
**Role:** Bitcoin Entrepreneur / Bull Bitcoin CEO
**Active:** 2013–present

A Quebec-based Bitcoin entrepreneur and one of Canada's earliest full-time Bitcoin advocates. Pouliot co-founded Bull Bitcoin (2018), a Bitcoin-only exchange based in Canada known for its non-custodial philosophy and emphasis on self-sovereignty, and acquired Bylls, the first Bitcoin bill payment service globally and Canada's largest Bitcoin payment processor. Earlier roles included CEO of Bitcoin Foundation Canada and Director of Public Affairs at The Bitcoin Embassy. He has served as a fintech advisor at the Ontario Securities Commission and as an associate researcher at the Montreal Economic Institute. Pouliot has been a vocal advocate for Bitcoin maximalism and peer-to-peer financial sovereignty.

**Sources:**
- Bull Bitcoin (bullbitcoin.com)
- Bylls documentation
- Bitcoin Foundation Canada
- Public writings and conference appearances (2013–present)

---

## Arthur Hayes (1985–present)
**Tier:** 3
**Role:** Co-Founder, BitMEX / Writer
**Active:** 2014–present

Co-founded BitMEX (Bitcoin Mercantile Exchange) in 2014, a cryptocurrency derivatives exchange that pioneered perpetual swap contracts and became one of the highest-volume Bitcoin trading venues in the world during the 2017–2020 era. BitMEX's perpetual swap product became a widely copied instrument across the derivatives market. In October 2020, the U.S. Department of Justice indicted Hayes and co-founders Ben Delo and Samuel Reed on charges of violating the Bank Secrecy Act by failing to implement AML and KYC programs; Hayes pleaded guilty in 2022 and received a sentence of two years probation. He writes a widely read macroeconomic and Bitcoin essay blog covering global liquidity, monetary policy, and Bitcoin market dynamics.

**Sources:**
- BitMEX founding documentation
- DOJ indictment (October 2020)
- Hayes guilty plea (2022)
- Arthur Hayes essay blog (arthur.substack.com)

---

## Didi Taihuttu & The Bitcoin Family (Taihuttu: 1978–present)
**Tier:** 3
**Role:** Bitcoin Circular Economy / Public Advocates
**Active:** 2017–present

Didi Taihuttu is a Dutch entrepreneur who, in 2017, sold his house, cars, business, and most of his family's possessions — converting approximately €250,000 into Bitcoin at around $900 per coin — and began living entirely on Bitcoin with his wife and three daughters while traveling the world. The family became publicly known as "The Bitcoin Family" and documented their lifestyle through media coverage and the website yolofamilytravel.com. Their story became widely covered in mainstream media as a real-world demonstration of living on a Bitcoin standard. In 2025, CNBC reported that the family had etched Bitcoin private key codes onto metal cards hidden on four continents as a security measure following high-profile crypto kidnappings.

**Sources:**
- Wikipedia — Didi Taihuttu
- CNBC coverage (2022, 2025)
- yolofamilytravel.com
- The National (2021, 2022)

---

## British HODL (pseudonym, identity unknown)
**Tier:** 3
**Role:** Bitcoin Investor / Educator / Content Creator
**Active:** 2020–present

A pseudonymous British Bitcoin investor and educator based in London, with an 18-year background in investment and early experience in London real estate beginning at age 16. He came to Bitcoin in 2020 after initially viewing it skeptically, discovering it through Bitcoin discussions on Clubhouse. He runs the British HODL YouTube channel and website, producing Bitcoin market commentary and educational content, and authored *Bitcoin: Its Path to $5m Per Coin*. He identifies as a long-term holder and is known in the Bitcoin content creator community for his bullish long-term thesis.

**Sources:**
- britishhodl.com
- IQ.wiki — British HODL
- *Bitcoin: Its Path to $5m Per Coin* — British HODL

---

## Surfer Jim (pseudonym)
**Tier:** 3
**Role:** Grassroots Bitcoin Educator / Author / Speaker
**Active:** c. 2018–present

Pseudonymous Bitcoin educator and entrepreneur who has built and repaired custom homes on Fire Island, New York for over 30 years while pursuing a lifelong passion for surfing. He first encountered Bitcoin around 2015 via a Netflix documentary but dismissed it as too complex; he later came to Bitcoin through algorithmically surfaced YouTube content and became a committed advocate. Known online and in the Bitcoin community as Surfer Jim, he became active on social media, podcasts, and the conference circuit as a grassroots Bitcoin evangelist. He produced *The Superiority of Bitcoin*, available as an audiobook, making the case for Bitcoin from a first-principles, non-technical perspective accessible to tradespeople and small business owners. He has appeared on the BitBlockBoom conference stage and on multiple Bitcoin podcasts including The Bitcoin Matrix. His story — a construction worker and surfer on Long Island becoming a Bitcoin radical and educator — has been profiled by Bitcoin Magazine as representative of grassroots Bitcoin adoption outside the finance and tech industries.

**Sources:**
- Bitcoin Magazine — "Interview: Surfing, Construction and Bitcoin With Surfer Jim"
- *The Superiority of Bitcoin* — Surfer Jim (Audible)
- BitBlockBoom speaker profile
- The Bitcoin Matrix Podcast #17 — Surfer Jim

---

## Jeff Berwick (1970–present)
**Tier:** 3
**Role:** Anarcho-Capitalist / Bitcoin Advocate / Media Personality
**Active:** 2012–present (Bitcoin-relevant)

A Canadian-Dominican entrepreneur who founded Stockhouse.com (1994), an early financial media website that grew to 250 employees and a $240 million market cap during the dot-com era. He founded The Dollar Vigilante in 2009, an anarcho-capitalist newsletter covering gold, silver, and Bitcoin, and launched Anarchast, an interview podcast, in 2012. In 2013, Berwick launched what he described as the world's first Bitcoin ATM in Cyprus — the same year the Cyprus banking confiscation crisis drew international attention to Bitcoin. He founded Anarchapulco (2015), an annual anarcho-capitalist conference in Acapulco, Mexico, and appeared in the documentary *Magic Money: The Bitcoin Revolution* (2017). He approaches Bitcoin from an anarcho-capitalist and anti-state philosophy.

**Sources:**
- The Dollar Vigilante (dollarvigilante.com)
- Anarchapulco documentation
- *Magic Money: The Bitcoin Revolution* (2017)
- Wikipedia — Jeff Berwick

---

## Tone Vays (dates unknown)
**Tier:** 3
**Role:** Bitcoin Analyst / Trader / Educator
**Active:** 2013–present

A former Wall Street risk analyst who worked at Bear Stearns and later as Vice President at JP Morgan Chase before transitioning to Bitcoin in 2013, partly motivated by the 2013 Cyprus banking confiscation crisis. He holds a Master's degree in Financial Engineering from Florida State University and Bachelor's degrees in Mathematics and Geology. Vays became a prominent Bitcoin technical analyst and educator, producing the *Trading Bitcoin* podcast and founding the Unconfiscatable, Understanding Bitcoin, and Financial Summit conferences. He has appeared in the documentaries *Magic Money* (2017) and *Bitcoin: Beyond the Bubble*, and on CNBC and RT.

**Sources:**
- tonevays.com
- *Magic Money: The Bitcoin Revolution* (2017)
- Public interviews and conference appearances (2013–present)

---

## Mark Moss (dates unknown)
**Tier:** 3
**Role:** Bitcoin Investor / Media Personality / Educator
**Active:** 2015–present

Entrepreneur, venture capitalist, and Bitcoin-focused media personality with over 25 years of investment experience spanning real estate, internet stocks, and digital assets. Moss began investing in foreclosed real estate in 1995, launched his first online business during the dot-com bust in 2001, and lost a significant portion of his capital in the 2008 financial crisis — experiences he has cited as formative in developing his framework for technology cycles and asset allocation. He encountered Bitcoin in the mid-2010s and committed fully to digital assets by 2015, launching Block United, an online crypto asset publication, in 2016. In 2017 he launched the Market Disruptors YouTube channel, later rebranded as The Mark Moss Show, which grew to nearly 20 million views covering Bitcoin, macro investing, monetary policy, and technology cycles. The Mark Moss Show is nationally syndicated as a radio and podcast program. He has appeared frequently at Bitcoin conferences and on other Bitcoin podcasts as an advocate for Bitcoin within a broader macro investment thesis.

**Sources:**
- markmoss.com / mm.1markmoss.com
- The Mark Moss Show — Apple Podcasts / iHeart
- Grokipedia — Mark Moss biography

---

## Dr. Jack Kruse (dates unknown)
**Tier:** 3
**Role:** Neurosurgeon / Bitcoin Advocate
**Active:** 2020s–present (Bitcoin-relevant)

A neurosurgeon with over 30 years of clinical experience and founder of the Kruse Longevity Center, known for his work in circadian biology, quantum biology, and evolutionary medicine. Kruse became a Bitcoin advocate and recurring conference speaker, appearing at Adopting Bitcoin (2024, 2025) and BTC Prague, where he draws parallels between Bitcoin's decentralized structure and his framework for decentralized health. His Bitcoin commentary intersects themes of sovereignty, energy, and biological systems, approaching Bitcoin from a medical and biophysics rather than financial or technical lens.

**Sources:**
- Adopting Bitcoin 2024 and 2025 speaker profiles
- BTC Prague speaker profile
- Bitcoin Magazine
- Public podcast appearances

---

## Trace Mayer (dates unknown)
**Tier:** 3
**Role:** Early Bitcoin Investor / Podcaster / Advocate
**Active:** 2010–present

One of Bitcoin's earliest public advocates, Mayer began recommending Bitcoin when it was trading at approximately $0.25 with a market cap under $2 million. He holds a BS in Accounting and a JD from the University of Wyoming and has studied Austrian economics. He made early investments in BitPay, Armory, and Kraken, and hosts *The Bitcoin Knowledge Podcast*, one of the longest-running Bitcoin podcasts. In 2019, Mayer initiated "Proof of Keys" day on January 3 — the anniversary of Bitcoin's genesis block — encouraging Bitcoin holders to withdraw coins from exchanges to personal wallets annually, as a check on exchange solvency. The initiative gained renewed attention following the FTX collapse in November 2022.

**Sources:**
- bitcoin.kn
- tracemayer.net
- "Proof of Keys" documentation (January 3, 2019–present)
- Early investment documentation

---

## Tim Draper (1958–present)
**Tier:** 3
**Role:** Venture Capitalist / Bitcoin Investor
**Active:** 2014–present (Bitcoin-relevant)

A Silicon Valley venture capitalist and founder of Draper Fisher Jurvetson (DFJ) who became one of Bitcoin's most visible early institutional investors. In June 2014, Draper won a U.S. Marshals Service auction of approximately 29,656 Bitcoin seized from Silk Road, purchased at roughly $18 million — one of the most publicized early institutional Bitcoin acquisitions. He publicly made a series of Bitcoin price predictions and has been a consistent advocate for Bitcoin and cryptocurrency as transformative financial technology. Draper's firm has invested in numerous Bitcoin and blockchain companies and he has been a recurring speaker at Bitcoin and technology conferences.

**Sources:**
- U.S. Marshals Service auction records (June 2014)
- Draper Associates portfolio documentation
- Public interviews and conference appearances (2014–present)

---

## Anthony Pompliano (dates unknown)
**Tier:** 3
**Role:** Investor / Media Personality / Bitcoin Advocate
**Active:** 2017–present

A Bitcoin investor and media personality who co-founded Morgan Creek Digital Assets, an early institutional crypto fund, and built a large following through his newsletter "The Pomp Letter" and podcast *The Pomp Podcast*, which featured interviews with investors, entrepreneurs, and policymakers. Pompliano was an early and prominent voice arguing for Bitcoin as a macro hedge and institutional asset, and contributed to normalizing Bitcoin investment language for mainstream financial audiences. He later founded Pomp Investments and has remained active as a commentator and investor.

**Sources:**
- Morgan Creek Digital Assets
- The Pomp Letter newsletter
- *The Pomp Podcast*
- Public writings and media appearances (2017–present)

---

## Mark Yusko (dates unknown)
**Tier:** 3
**Role:** Investment Manager / Institutional Bitcoin Advocate
**Active:** 2018–present (Bitcoin-relevant)

Founder, CEO, and Chief Investment Officer of Morgan Creek Capital Management, an investment firm founded in 2004 managing approximately $1.5 billion in assets. Yusko's career prior to Morgan Creek included serving as CIO and founder of the University of North Carolina at Chapel Hill endowment investment office (UNCMC) and as Senior Investment Director at the University of Notre Dame Investment Office, where he was an early adopter of the endowment model of investing in alternative assets. He holds a BA from Notre Dame and an MBA in accounting and finance from the University of Chicago. In 2018, Yusko co-founded Morgan Creek Digital Assets with Anthony Pompliano and Jason Williams — built from an earlier venture fund called Full Tilt Capital — to invest in blockchain technology and digital assets with an institutional endowment-model framework. Morgan Creek Digital was among the earliest U.S. investment firms to pitch pensions and endowments on digital asset exposure. Yusko has been a consistent public voice arguing for Bitcoin as a portfolio allocation and has appeared frequently on financial media.

**Sources:**
- morgancreekcap.com
- Morgan Creek Digital documentation
- The Block — Mark Yusko interview (2019)
- TechCrunch — Anthony Pompliano / Morgan Creek Digital history (2024)

---

## Jeff Ross (dates unknown)
**Tier:** 3
**Role:** Hedge Fund Manager / Bitcoin Investor
**Active:** 2016–present (Bitcoin-relevant)

A physician-turned-fund manager who founded Vailshire Capital Management (2013) and the Vailshire Partners hedge fund (2014), transitioning from a career as an interventional radiologist to institutional investing. Ross became a Bitcoin advocate after entering the space around 2016 and has been a recurring conference speaker and podcast guest connecting macroeconomic analysis to Bitcoin. He has contributed financial commentary to Seeking Alpha and The Motley Fool and appeared on Bitcoin-focused podcasts including The Investor's Podcast.

**Sources:**
- Vailshire Capital Management
- The Investor's Podcast appearances
- Conference presentations (2022–present)

---

## Joe Consorti (dates unknown)
**Tier:** 3
**Role:** Bitcoin Analyst / Writer
**Active:** 2020s–present

A Bitcoin and macroeconomic analyst who writes on on-chain data, global liquidity, monetary policy, and Bitcoin market cycles. He has written for Bitcoin Magazine and The Bitcoin Layer, and publishes widely followed commentary on YouTube and X. He has worked in the Bitcoin financial services space, including a role as Head of Growth at Horizon, a company building products that allow homeowners to hold Bitcoin against home equity, and Theya (Y Combinator).

**Sources:**
- Bitcoin Magazine author archive
- The Bitcoin Layer
- joeconsorti.com
- Public writings and appearances

---

## Sam Callahan (dates unknown)
**Tier:** 3
**Role:** Bitcoin Analyst / Writer
**Active:** 2020s–present

Bitcoin analyst and writer who served as Lead Analyst at Swan Bitcoin, where he wrote the "Running the Numbers" section of the monthly Swan Private Insight Report covering Bitcoin market data, on-chain analytics, macroeconomic context, and industry developments. His academic background is in biology and physics from Indiana University. He has also written for Bitcoin Magazine and contributed research across multiple Bitcoin financial services organizations including a role as Vice President at Battery Finance and Director of Strategy and Research at OranjeBTC. He serves on the advisory boards of MARA Digital Holdings, LQwD Technologies, and Cantilever Advisors, and has appeared on The Investor's Podcast and the Stephan Livera Podcast.

**Sources:**
- Bitcoin Magazine author archive — Sam Callahan
- Swan Bitcoin — Running the Numbers / Swan Private Insight Report
- BTC Prague speaker profile
- Qwoted — Sam Callahan profile

---

## Jeffrey Tucker (dates unknown)
**Tier:** 3
**Role:** Economist / Author / Bitcoin Advocate
**Active:** 2013–present (Bitcoin-relevant)

A libertarian economist and prolific writer who became an early and vocal Bitcoin advocate, connecting Bitcoin to the Austrian economics tradition and the history of sound money. Tucker served as editorial director at the Foundation for Economic Education (FEE) and later founded the Brownstone Institute. He authored *Bitcoin: The New Gold Standard* and numerous essays arguing that Bitcoin represented a spontaneous market solution to state monetary monopoly. His writing introduced Austrian economic framing of Bitcoin to a broad audience and was widely circulated in libertarian and Bitcoin communities in the early-to-mid 2010s.

**Sources:**
- Foundation for Economic Education (FEE) publications
- Brownstone Institute
- *Bitcoin: The New Gold Standard* — Jeffrey Tucker
- Public writings and conference appearances

---

## Nick Spanos (dates unknown)
**Tier:** 2
**Role:** Bitcoin Entrepreneur / Bitcoin Center NYC Founder
**Active:** 2013–present

A New York-based entrepreneur and Bitcoin advocate who founded Bitcoin Center NYC in 2013 — the first cryptocurrency trading floor in the world, opened directly across the street from the New York Stock Exchange. Bitcoin Center NYC served as an early physical hub for Bitcoin education, trading, and community in New York during the formative years of the ecosystem. Spanos is also CEO of Blockchain Technologies Corp., which developed VoteWatcher, a blockchain-based voting platform, and co-founded Zap.org, a platform enabling real-world data to trigger smart contract execution.

**Sources:**
- bitcoincenternyc.com
- nickspanos.com
- Public interviews and writings (2013–present)

---

## Paul Vigna (dates unknown)
**Tier:** 3
**Role:** Journalist / Author
**Active:** 2013–present (Bitcoin-relevant)

A longtime Wall Street Journal reporter who began covering Bitcoin in 2013 and co-authored *The Age of Cryptocurrency: How Bitcoin and the Blockchain Are Challenging the Global Economic Order* (2015) with Michael J. Casey — the first book about Bitcoin published by a Big Five publisher. The book introduced Bitcoin to a mainstream financial audience through the lens of Wall Street journalism. Vigna and Casey followed it with *The Truth Machine* (2018), covering blockchain's broader applications. Vigna later became managing editor at American Banker and writes the Substack newsletter PofV.

**Sources:**
- *The Age of Cryptocurrency* — Paul Vigna & Michael J. Casey (St. Martin's Press, 2015)
- *The Truth Machine* — Paul Vigna & Michael J. Casey (2018)
- Wall Street Journal coverage (2013–present)

---

## Michael J. Casey (dates unknown)
**Tier:** 3
**Role:** Journalist / Author / Researcher
**Active:** 2013–present (Bitcoin-relevant)

An Australian journalist who spent 18 years at The Wall Street Journal and Dow Jones Newswires before becoming a prominent voice in Bitcoin and blockchain media. He co-authored *The Age of Cryptocurrency* (2015) and *The Truth Machine* (2018) with Paul Vigna. He served as a Senior Advisor at the MIT Media Lab's Digital Currency Initiative and as a Senior Lecturer at MIT Sloan School of Management, and later became Chief Content Officer at CoinDesk. He co-authored *Our Biggest Fight: Reclaiming Liberty, Humanity and Dignity in the Digital Age* (2024) with Frank H. McCourt Jr.

**Sources:**
- *The Age of Cryptocurrency* — Paul Vigna & Michael J. Casey (2015)
- *The Truth Machine* — Paul Vigna & Michael J. Casey (2018)
- *Our Biggest Fight* — Michael J. Casey & Frank H. McCourt Jr. (2024)
- MIT Digital Currency Initiative; CoinDesk

---

## Frank H. McCourt Jr. (1953–present)
**Tier:** 3
**Role:** Entrepreneur / Digital Rights Advocate
**Active:** 2020s–present (Bitcoin-adjacent)

An American business executive and philanthropist best known outside Bitcoin circles as the former owner of the Los Angeles Dodgers (2004–2012) and founder of McCourt Global. In the Bitcoin-adjacent space, McCourt founded Project Liberty, a $500 million initiative to reform internet infrastructure through a Decentralized Social Networking Protocol (DSNP) enabling user ownership of personal data. He co-authored *Our Biggest Fight: Reclaiming Liberty, Humanity and Dignity in the Digital Age* (2024) with Michael J. Casey, framing digital rights and data sovereignty in terms that overlap with Bitcoin's censorship-resistance philosophy, though his work is not Bitcoin-specific.

**Sources:**
- *Our Biggest Fight* — Frank H. McCourt Jr. & Michael J. Casey (2024)
- Project Liberty documentation (projectliberty.io)
- McCourt Global (mccourt.com)

---

## *Life on Bitcoin* (2014) — Joseph Lebaron & Travis Pitcher
**Tier:** 3
**Role:** Bitcoin Documentary
**Active:** 2014

Documentary directed by Joseph Lebaron and Travis Pitcher following newlyweds Austin Craig and Beccy Bingham on a 90-day experiment living exclusively on Bitcoin, beginning the day after their wedding in 2013. The film documents the practical challenges of spending only Bitcoin in a world where merchant acceptance was limited, serving as a real-world test of Bitcoin's usability as a medium of exchange in its early era.

**Sources:**
- IMDB (tt3910512)
- CoinDesk coverage (2014)

---

## *Ulterior States* (2015) — Tomer Kantor / IamSatoshi
**Tier:** 3
**Role:** Bitcoin Documentary
**Active:** 2015

A self-funded documentary directed by Tomer Kantor (IamSatoshi) and produced as a final project for London South Bank University (MA — Arts & Humanities — Digital Film), released June 27, 2015. The film took three years and 125 interviews to complete and argues for Bitcoin and decentralized cryptocurrencies as a form of code-as-activism. One of the few Bitcoin documentaries produced from an explicitly ideological and community-driven perspective rather than a journalistic one.

**Sources:**
- YouTube — Ulterior States (IamSatoshi, 2015)
- Bitcoinist review (2015)

---

## *Deep Web* (2015) — Alex Winter
**Tier:** 3
**Role:** Bitcoin Documentary
**Active:** 2015

A documentary directed by Alex Winter examining Silk Road, Bitcoin's role in dark web commerce, and the arrest and trial of Ross Ulbricht, narrated by Keanu Reeves. The film presents a civil liberties framing of the Ulbricht case alongside Bitcoin's role in enabling pseudonymous online transactions. Alex Winter subsequently directed *Trust Machine* (2018), a broader examination of blockchain technology.

**Sources:**
- IMDB — Deep Web (2015)
- CoinDesk interview with Alex Winter (April 2015)

---

## *Magic Money: The Bitcoin Revolution* (2017)
**Tier:** 3
**Role:** Bitcoin Documentary
**Active:** 2017

A documentary exploring Bitcoin's origins, monetary theory, and potential as an alternative to government-issued currency, featuring interviews with Trace Mayer, Tone Vays, Jeff Berwick, and others. The film contextualizes Bitcoin within concerns about global financial instability and Austrian economics and was widely circulated in Bitcoin communities in 2017.

**Sources:**
- IMDB — Magic Money: The Bitcoin Revolution (2017)
- Public film distribution

---

## *Trust Machine: The Story of Blockchain* (2018) — Alex Winter
**Tier:** 3
**Role:** Bitcoin & Blockchain Documentary
**Active:** 2018

A documentary directed by Alex Winter and narrated by Rosario Dawson examining blockchain technology's potential applications and challenges, including Bitcoin, smart contracts, and decentralized systems. Winter's second cryptocurrency-related documentary following *Deep Web* (2015).

**Sources:**
- IMDB — Trust Machine: The Story of Blockchain (2018)

---

## *Bitcoin Big Bang: L'Improbable Épopée de Mark Karpelès* (2018) — Vincent Gonon & Xavier Sayanoff
**Tier:** 3
**Role:** Bitcoin Documentary
**Active:** 2018

A French documentary directed by Vincent Gonon and Xavier Sayanoff documenting the collapse of Mt. Gox, the disappearance of approximately 850,000 Bitcoin, and the arrest of CEO Mark Karpelès. The film draws primarily on Karpelès's own account of events (cross-reference: Mark Karpelès entry).

**Sources:**
- IMDB (tt8056932)
- Films Media Group documentation

---

## *Bitconned* (2024) — Bryan Storkel / Netflix
**Tier:** 3
**Role:** Bitcoin-Adjacent Documentary / Crypto Fraud Case Study
**Active:** 2024

A Netflix documentary directed by Bryan Storkel, released January 1, 2024, following the three co-founders of Centra Tech — Ray Trapani and associates — who raised more than $32 million in a fraudulent initial coin offering (ICO) before their arrest. The film is a true crime account of cryptocurrency fraud during the 2017–2018 ICO boom rather than a Bitcoin-specific documentary, but is included as a documented case study of fraud in the broader crypto space during that era.

**Sources:**
- Netflix — Bitconned (2024)
- IMDB (tt30317302)
- Wikipedia — Bitconned

---

## Daniel Mross & Nicholas Mross — *The Rise and Rise of Bitcoin* (dates unknown)
**Tier:** 3
**Role:** Documentary Subjects / Filmmaker
**Active:** 2013–2014 (Bitcoin-relevant)

*The Rise and Rise of Bitcoin* (2014) is a documentary directed by Nicholas Mross and centered on his brother Daniel Mross, a Pittsburgh-based computer programmer who began mining Bitcoin in 2011. The film premiered at the Tribeca Film Festival on April 23, 2014, and documents Daniel's journey from early Bitcoin mining through the rapid professionalization of the mining industry. The film features interviews with prominent early Bitcoin figures and offers a firsthand account of the 2013–2014 period when Bitcoin was heading toward $1,000 for the first time. It is one of two foundational early Bitcoin documentaries alongside *Banking on Bitcoin* (2016).

**Sources:**
- *The Rise and Rise of Bitcoin* (2014, dir. Nicholas Mross)
- Tribeca Film Festival premiere (April 2014)
- IMDB (tt2821314)

---

## Christopher Cannucciari (dates unknown)
**Tier:** 3
**Role:** Documentary Filmmaker
**Active:** 2016–present (Bitcoin-relevant)

A documentary filmmaker whose *Banking on Bitcoin* (2016) was among the earliest feature-length documentary treatments of Bitcoin's origins and early community. The film reached the number one position on iTunes upon release and held a top-ten documentary position on Netflix for an extended period. Cannucciari spent approximately three years researching and producing the film, which covers Bitcoin's early pioneers, the Silk Road arrests, and regulatory confrontations. He subsequently announced *I Am Not Satoshi*, a follow-up documentary focused on the search for Satoshi Nakamoto's identity.

**Sources:**
- *Banking on Bitcoin* (2016, dir. Christopher Cannucciari)
- IMDB (tt5033790)
- cannucciari.com

---

## Brian Estes (dates unknown)
**Tier:** 3
**Role:** Bitcoin Fund Manager / Documentary Co-Creator / Educator
**Active:** 2016–present

Founder, CEO, and Chief Investment Officer of Off the Chain Capital, a Bitcoin and blockchain investment fund founded in 2016. Estes holds a BA in economics from the University of Illinois and an MBA with high honors from Washington University in St. Louis, and studied abroad at the University of Cambridge and the London School of Economics. Prior to founding Off the Chain Capital, he rose to become the youngest senior vice president in the history of A.G. Edwards & Sons in St. Louis, then founded Estes Financial in 2004, where he was ranked in the top one-tenth of one percent of Morningstar asset managers from 2004 to 2014. Off the Chain Capital claimed the top-performing ranking in the HFRI blockchain fund universe over its first five years and raised a $160 million fund. Estes teaches blockchain and digital asset investing at the University of Cambridge, Washington University, and Morgan State University's Center of Blockchain and Financial Technology. He and his wife Kelly Estes co-created *God Bless Bitcoin* (2024), a documentary examining the moral and ethical dimensions of current monetary systems and Bitcoin's potential as an alternative, featuring interviews with Michael Saylor, Anthony Pompliano, and religious leaders from Christianity, Judaism, and Islam.

**Sources:**
- Off the Chain Capital documentation
- Blockworks — Off the Chain Capital $160M fund announcement
- PR Newswire — Off the Chain Capital five-year performance (2022)
- godblessbitcoin.com
- IMDB — *God Bless Bitcoin* (tt32881100)

---

## Brian Dixon (dates unknown)
**Tier:** 3
**Role:** CEO, Off the Chain Capital / Bitcoin Investor / Author
**Active:** 2012–present

President and CEO of Off the Chain Capital, a value-oriented Bitcoin and digital asset investment fund founded by Brian Estes. Dixon entered the digital assets space in 2012 as an early Bitcoin adopter and has described his investment approach as Warren Buffett-style value investing applied to Bitcoin — acquiring blockchain assets at a discount to intrinsic value. Prior to Off the Chain Capital, he served as Chief Operating Officer and Managing Director of Capital Innovators, a venture fund manager and accelerator program provider. He attended Washington University in St. Louis School of Law. Dixon has authored four books covering Bitcoin and advanced technology, has performed over 80 national and international speaking engagements, and has written for TheStreet Crypto. He has appeared at Bitcoin MENA 2025 and in CoinDesk video interviews advocating for Bitcoin as significantly undervalued relative to its long-term potential.

**Sources:**
- Crunchbase — Brian Dixon / Off the Chain Capital
- CoinDesk — "Bitcoin Is 'Significantly Undervalued Today': Off the Chain Capital CEO"
- FINTECH.TV — Brian Dixon interview
- Bitcoin MENA 2025 speaker profile
- TheStreet Crypto — Brian Dixon author archive

---

## PlanB (pseudonym, identity unknown)
**Tier:** 3
**Role:** On-chain Analyst / Quantitative Modeler
**Active:** 2019–present

A pseudonymous Dutch institutional investor and Bitcoin analyst who published the Stock-to-Flow (S2F) model for Bitcoin price in March 2019, one of the most widely circulated Bitcoin price models of the halving era. The model borrows from commodity valuation methodology, treating Bitcoin's scarcity — measured by the ratio of existing supply to annual new issuance — as a primary price driver, and drew attention to the four-year halving cycle as a structural feature of Bitcoin's monetary policy. PlanB later published a cross-asset S2F model (S2FX) extending the framework. The model attracted both significant mainstream attention and substantial academic and empirical criticism, particularly after Bitcoin's price diverged from S2F predictions in 2021–2022. PlanB has maintained his pseudonymity while describing himself publicly as a Dutch institutional investor with a background in law and finance.

**Sources:**
- "Modeling Bitcoin's Value with Scarcity" — PlanB (Medium, March 2019)
- S2FX model publication (2020)
- Public interviews and writings

---

## Andrew M. Bailey, Bradley Rettler & Craig Warmke — *Resistance Money* (dates unknown)
**Tier:** 3
**Role:** Philosophers / Authors
**Active:** 2020s–present

Three academic philosophers who co-authored *Resistance Money: A Philosophical Case for Bitcoin* (Routledge, 2024), a systematic philosophical examination of Bitcoin's properties and moral status. Andrew M. Bailey is Associate Professor of Humanities at Yale-NUS College, Singapore; Bradley Rettler is Associate Professor of Philosophy at the University of Wyoming; and Craig Warmke is Associate Professor of Philosophy at Northern Illinois University. The book is one of the few academic philosophical treatments of Bitcoin, engaging with questions of monetary theory, censorship resistance, and the ethical dimensions of sound money from an analytic philosophy framework.

**Sources:**
- *Resistance Money: A Philosophical Case for Bitcoin* — Andrew M. Bailey, Bradley Rettler, Craig Warmke (Routledge, 2024)

---

## Hut 8 Corp (founded 2017)
**Tier:** 3
**Role:** Publicly Traded Bitcoin Mining Company
**Active:** 2017–present

Founded in October 2017 by Marc van der Chijs and initially headquartered in Toronto, Ontario, Hut 8 established large-scale Bitcoin mining operations in Alberta, Canada, before merging with U.S. Bitcoin Corp in November 2023 to form Hut 8 Corp, headquartered in Miami, Florida. The company trades on NASDAQ (HUT) and has been among the larger publicly traded Bitcoin miners by stockpiled BTC. Bill Tai serves as Independent Chairman of the Board. In 2025, Hut 8 launched American Bitcoin Corp., a majority-owned subsidiary focused on industrial-scale Bitcoin mining and strategic Bitcoin reserve development, with Eric Trump involved in the venture.

**Sources:**
- Hut 8 Corp public filings (NASDAQ: HUT)
- U.S. Bitcoin Corp merger documentation (November 2023)
- hut8.com

---

## Bill Tai (dates unknown)
**Tier:** 3
**Role:** Venture Capitalist / Bitcoin Investor
**Active:** 2010–present

A Silicon Valley venture capitalist with a background in electrical engineering and an MBA from Harvard, who became an early backer of Bitcoin and the Bitcoin mining industry. Tai has been involved in Bitcoin since approximately 2010 and was an early investor in Bitfury Group, personally funding their Bitcoin mining ASIC development. He serves as Chairman of Hut 8 Corp (NASDAQ: HUT), one of the larger publicly traded Bitcoin mining companies by stockpiled BTC. His broader venture career includes early investments in Zoom, Canva, and Twitter. He co-authored *And Then You Win: A Start-Up's Untold Story of Grit, Grind, and Glory* (2025) with Bitfury co-founder George Kikvadze.

**Sources:**
- *And Then You Win* — George Kikvadze & Bill Tai (2025)
- Bitfury advisory board documentation (bitfury.com)
- Hut 8 Corp public filings (NASDAQ: HUT)

---

## George Kikvadze (dates unknown)
**Tier:** 3
**Role:** Bitfury Co-Founder / Executive
**Active:** 2011–present

A co-founder of Bitfury Group who served as its Vice Chairman. He was a central figure in Bitfury's growth from a startup into one of the largest Bitcoin mining hardware and infrastructure companies in the world. He co-authored *And Then You Win: A Start-Up's Untold Story of Grit, Grind, and Glory* (2025), a firsthand account of Bitfury's founding and expansion.

**Sources:**
- *And Then You Win* — George Kikvadze & Bill Tai (2025)
- Bitfury company documentation

---

## Marco Streng (dates unknown)
**Tier:** 3
**Role:** Co-Founder & CEO, Genesis Digital Assets / Genesis Mining
**Active:** 2013–present

Began mining Bitcoin in his university dormitory in 2013 while studying mathematics and co-founded Genesis Mining, which grew into one of the largest cloud Bitcoin mining operations in the world, and later Genesis Digital Assets, one of the largest industrial-scale Bitcoin mining companies by hashrate. He co-authored *Decrypting Money: A Comprehensive Introduction to Bitcoin* (2023) alongside Marco Krohn, Anthony Jefferies, and Zoran Balkic.

**Sources:**
- *Decrypting Money* — Marco Krohn, Anthony Jefferies, Marco Streng, Zoran Balkic
- Genesis Digital Assets company documentation

---

## Zoran Balkic — Bitfury (dates unknown)
**Tier:** 3
**Role:** CEO, Bitfury / Author
**Active:** 2010s–present

Bitfury is one of the earliest vertically integrated Bitcoin mining companies, founded in 2011 by Valery Vavilov, developing its own ASIC mining chips and operating large-scale data centers in Iceland, Georgia, and Norway. The company expanded beyond mining hardware into blockchain infrastructure and analytics software. Zoran Balkic serves as CEO of Bitfury Group and co-authored *Decrypting Money*, a comprehensive introduction to Bitcoin.

**Sources:**
- *Decrypting Money* — Marco Krohn, Anthony Jefferies, Marco Streng, Zoran Balkic
- Bitfury company documentation and public announcements

---

## Caitlin Long (dates unknown)
**Tier:** 3
**Role:** Banker / Attorney / Bitcoin Advocate
**Active:** 2016–present

A Wall Street veteran and attorney who became a prominent Bitcoin advocate and founded Custodia Bank (formerly Avanti Financial Group), a Wyoming-chartered special purpose depository institution designed to offer Bitcoin custody and dollar services to institutional clients without fractional reserve lending. She was a principal architect of Wyoming's blockchain-friendly legislation beginning in 2018, including laws establishing legal clarity for digital asset property rights and special purpose depository institution (SPDI) charters. Custodia's application for a Federal Reserve master account was denied in January 2023, a decision Custodia challenged in federal court as discriminatory toward crypto-native banks. Long has written and testified extensively on the distinction between full-reserve and fractional-reserve banking in the context of Bitcoin custody.

**Sources:**
- Custodia Bank filings and documentation
- Wyoming blockchain legislation (2018–present)
- Federal Reserve master account denial (January 2023)
- Long's public testimony, writing, and conference appearances

---

## Perianne Boring (dates unknown)
**Tier:** 3
**Role:** Policy Advocate / Trade Association Founder
**Active:** 2014–present

Founder and CEO of the Chamber of Digital Commerce, the largest trade association for the digital asset industry in Washington, D.C., established in 2014. Boring graduated from the University of Florida in 2010 with a degree in business administration and economics, served as a White House intern during the Obama administration, and worked as a legislative analyst and constituent relations director for U.S. Representative Dennis Ross (R-FL). She later became host and anchor of *Prime Interest*, an international finance program that aired in over 100 countries to approximately 650 million viewers via RT America, where Bitcoin became a frequent subject of coverage. She founded the Chamber of Digital Commerce in 2014 after concluding the industry lacked formal policy representation in Washington; its membership has included Accenture, Cisco, Microsoft, IBM, Fidelity, Wells Fargo, BitPay, and others. She teaches blockchain as an adjunct professor at Georgetown University's McDonough School of Business and has testified before Congress and regulatory agencies on digital asset policy. CoinDesk named her among its "10 Most Influential People in Blockchain" in 2016.

**Sources:**
- Chamber of Digital Commerce documentation (digitalchamber.org)
- Forbes profile — Perianne Boring
- American Banker — Perianne Boring contributor
- CNBC — Chamber of Digital Commerce interview (2022)
- CoinDesk — "10 Most Influential in Blockchain" (2016)

---

## Natalie Smolenski (dates unknown)
**Tier:** 3
**Role:** Policy Researcher / Author / Bitcoin Advocate
**Active:** 2017–present

A cultural anthropologist and Bitcoin policy researcher known for writing on the philosophical and political dimensions of Bitcoin, self-sovereign identity, and digital rights. She served as an advisor to the Bitcoin Policy Institute and Texas Bitcoin Foundation and authored *Bitcoin and the American Century*, an essay arguing that Bitcoin is compatible with and beneficial to American economic and geopolitical interests. Her work bridges anthropology, philosophy of technology, and Bitcoin advocacy, and has been cited in Bitcoin policy discussions in Washington. She has written on the relationship between identity, surveillance, and monetary sovereignty.

**Sources:**
- *Bitcoin and the American Century* — Natalie Smolenski
- Bitcoin Policy Institute publications
- Texas Bitcoin Foundation
- Public writings and conference appearances

---

## Willy Woo (dates unknown)
**Tier:** 3
**Role:** On-chain Analyst
**Active:** 2013–present

A New Zealand-based Bitcoin analyst known for pioneering on-chain data analysis as a method for evaluating Bitcoin market cycles. He developed several widely cited indicators, including the NVT Ratio (Network Value to Transactions Ratio, 2017), which applies a price-to-earnings analogy to Bitcoin by comparing market cap to on-chain transaction volume, and the NVT Signal, a variation developed to generate earlier cycle signals. Woo co-founded Hyperwave capital and later launched Woobull Charts (woobull.com), a public repository of on-chain metric visualizations used by traders, analysts, and researchers. He has been a recurring commentator on Bitcoin market structure and a proponent of on-chain analysis as an alternative to traditional technical analysis.

**Sources:**
- Woobull Charts (woobull.com)
- NVT Ratio — Willy Woo (2017)
- Public interviews and writings (2013–present)

---

## Tuur Demeester (dates unknown)
**Tier:** 3
**Role:** Macroeconomist / Investment Analyst
**Active:** 2012–present

A Belgian macroeconomist and investment analyst who became an early public advocate for Bitcoin. In 2012, he published a research report recommending Bitcoin as an investment when the price was under $10, one of the earliest institutional-style analyses of Bitcoin as an asset. He founded Adamant Research, a Bitcoin-focused research firm, and later co-founded Adamant Capital. He is known for long-form analyses connecting Austrian economics to Bitcoin monetary theory and for public debates on Bitcoin's development direction, including vocal opposition to Ethereum. Demeester has been a recurring speaker at Bitcoin conferences and a contributor to debates on Layer 2 scaling and soft fork governance.

**Sources:**
- Adamant Research reports
- Conference presentations and public appearances (2012–present)
- Public writings and interviews

---

*Last updated: 2026-07-08*
*Status: 317 entries. Tier 1 complete. Tier 2/3 stubs — expand as research progresses.*

---

## BIBLIOGRAPHY

### Books
- *The Genesis Book* (2024) — Aaron van Wirdum. The definitive history of Bitcoin's intellectual precursors. Primary source for Tier 1 entries.
- *Digital Gold* (2015) — Nathaniel Popper. Narrative history of Bitcoin's early years through 2014.
- *The Bitcoin Standard* (2018) — Saifedean Ammous. Austrian economics case for Bitcoin as hard money.
- *The Fiat Standard* (2021) — Saifedean Ammous. Follow-up examining the fiat monetary system.
- *The Blocksize War* (2021) — Jonathan Bier. Definitive account of the 2015–2017 block size conflict.
- *The Cryptopians* (2022) — Laura Shin. Covers Ethereum's founding and early crypto ecosystem; relevant for Buterin, Karpelès, Ver.
- *Mastering Bitcoin* (2014, updated) — Andreas Antonopoulos. Technical reference; relevant to Antonopoulos entry.
- *The Internet of Money* Vol. 1–3 — Andreas Antonopoulos. Collected talks on Bitcoin's social significance.
- *American Kingpin* (2017) — Nick Bilton. Narrative account of Ross Ulbricht and Silk Road.
- *Bitcoin Billionaires* (2019) — Ben Mezrich. Winklevoss twins' Bitcoin story.
- *Come and Take It* (2016) — Cody Wilson. Wilson's own account of Defense Distributed and DarkWallet.
- *This Machine Kills Secrets* (2012) — Andy Greenberg. History of cypherpunks, WikiLeaks, and digital privacy.
- *Tracers in the Dark* (2022) — Andy Greenberg. Blockchain forensics, IRS-CI investigators, and the takedown of Silk Road 2 and AlphaBay.
- *The Code Book* (1999) — Simon Singh. Accessible history of cryptography; useful background for Tier 1 cryptographers.
- *The Road to Serfdom* (1944) — F.A. Hayek.
- *The Denationalisation of Money* (1976) — F.A. Hayek. Direct intellectual precursor to Bitcoin's monetary design.
- *PGP: Pretty Good Privacy* (1994) — Simson Garfinkel. History of PGP and Zimmermann.
- *The Bitcoin Standard Podcast* — Saifedean Ammous (ongoing).
- *The Price of Tomorrow* (2020) — Jeff Booth. Deflationary technology thesis and Bitcoin as monetary resolution.
- *Broken Money* (2023) — Lyn Alden. History of monetary technology and Bitcoin's place in it.
- "Gradually, Then Suddenly" essay series (2019–2020) — Parker Lewis (unchained.com); also published as a book.
- *La Filosofía de Bitcoin* — Álvaro D. María. First major Spanish-language original Bitcoin philosophy text; significant in Latin American Bitcoin culture.
- *Inventing Bitcoin* (2019) — Yan Pritzker. Short, accessible technical primer building intuition for Bitcoin's design from first principles.
- *Programming Bitcoin* (2019) — Jimmy Song (O'Reilly). Hands-on developer book; builds Bitcoin from scratch in Python.
- *Layered Money* (2021) — Nik Bhatia. Explains Bitcoin and Lightning as layers in a historical framework of monetary systems; accessible to finance and banking professionals.
- *Softwar* (2023) — Jason Lowery (MIT thesis). National security argument for Bitcoin mining as strategic power projection; influenced defense establishment thinking.
- "The Bullish Case for Bitcoin" (2018) — Vijay Boyapati (Medium; also published as book). Rigorous monetary economics argument; most widely shared Bitcoin onboarding essay of the 2018–2021 era.
- "The Number Zero and Bitcoin" essay — Robert Breedlove.
- *What is Money?* podcast — Robert Breedlove (ongoing).
- *Going Infinite* (2023) — Michael Lewis. SBF biography and FTX account.
- *Number Go Up* (2023) — Zeke Faux. Investigative account of the crypto boom and FTX collapse.

### Academic & Technical Papers
- *Bitcoin: A Peer-to-Peer Electronic Cash System* (2008) — Satoshi Nakamoto. The whitepaper.
- "Blind Signatures for Untraceable Payments" (1982) — David Chaum.
- "Security Without Identification" (1985) — David Chaum.
- "New Directions in Cryptography" (1976) — Whitfield Diffie & Martin Hellman.
- "A Method for Obtaining Digital Signatures and Public-Key Cryptosystems" (1978) — Rivest, Shamir & Adleman.
- "A Digital Signature Based on a Conventional Encryption Function" (1987) — Ralph Merkle.
- *Hashcash — A Denial of Service Counter-Measure* (2002) — Adam Back.
- b-money proposal (1998) — Wei Dai. (weidai.com)
- "Bit Gold" (~1998/2005) — Nick Szabo. (unenumerated.blogspot.com)
- "Smart Contracts" (1994) — Nick Szabo.
- RPOW announcement (2004) — Hal Finney.
- Ethereum whitepaper (2013) — Vitalik Buterin.
- "Speculative Attack" (2014) — Pierre Rochard.

### Primary Documents & Manifestos
- *Crypto Anarchist Manifesto* (1988) — Timothy C. May.
- *The Cyphernomicon* (1994) — Timothy C. May. (online)
- *A Cypherpunk's Manifesto* (1993) — Eric Hughes. (online)
- "A Declaration of the Independence of Cyberspace" (1996) — John Perry Barlow. (eff.org)
- U.S. Customs Service PGP investigation records (1993–1996)
- PGP source code book publication — Phil Zimmermann
- Bernstein v. United States (9th Circuit, 1999) — encryption as protected speech
- NSA Clipper Chip proposal and defeat documentation (1993–1994)
- EFF Crypto Wars documentation (eff.org)
- Ordinals protocol documentation (ordinals.com); Rodarmor launch documentation (January 2023)
- Runes protocol documentation (2024)
- Bitcoin Core PR #29519 (OP_RETURN limit removal proposal, 2024)
- Bitcoin Knots inscription filtering documentation
- Satoshi Nakamoto email archives — Satoshi Nakamoto Institute (nakamotoinstitute.org)
- Cryptography mailing list archive, November 2008 (Satoshi whitepaper thread)
- Bitcointalk forum archives (bitcointalk.org) — early posts by Satoshi, Finney, Malmi, NewLibertyStandard, Ribuck, Hanyecz, dwdollar, Casascius, nanotube, Nefario, pirateat40, and others
- "Running Bitcoin" tweet — Hal Finney (January 11, 2009)
- "Dying Outside" — Hal Finney (bitcointalk.org, 2013)
- "Why I'm no longer a Bitcoin developer" — Mike Hearn (Medium, 2016)
- BIP-0001 — Amir Taaki. Established the Bitcoin Improvement Proposal process.
- Litecoin launch thread — Charlie Lee (Bitcointalk, October 2011)
- Bitcoin Market launch thread — Dustin Dollar / dwdollar (Bitcointalk, January 2010)
- Electrum wallet launch thread — Thomas Voegtlin (Bitcointalk, November 2011)
- Bitcoin Pizza thread — Laszlo Hanyecz / jercos (Bitcointalk, May 2010)
- Casascius physical Bitcoin announcement — Mike Caldwell (Bitcointalk, August 2011)
- Bitcoin Savings and Trust thread — Trendon Shavers / pirateat40 (Bitcointalk, 2011)
- "Bet on Bitcoin" essay — Wences Casares.
- Charlie Lee conflict-of-interest statement (December 2017) — Reddit/Twitter.
- Libbitcoin project documentation — Amir Taaki (2011).
- Bitcoin-OTC web-of-trust documentation archive (bitcoin-otc.com)

### Journalism & Long-Form
- "The Face Behind Bitcoin" (March 2014) — Leah McGrath Goodman, Newsweek. (Dorian Nakamoto misidentification)
- *HBO Money Electric* documentary (2024). (Peter Todd Satoshi claim)
- Vice documentary on Amir Taaki in Syria.
- "The first days of Bitcoin and Dustin D. Trammell's emails with Satoshi Nakamoto" — CoinTelegraph.
- "Remembering BitcoinMarket, Bitcoin's First-ever Exchange" — fullycrypto.com.
- Interview with nanotube, founder of Bitcoin-OTC — Private Internet Access blog (2013).
- Interview with Nefario (James McCarthy) — Bitcoin Magazine (2012).
- "The Man Who Lost $220 Million in Bitcoin" (Stefan Thomas / IronKey) — New York Times (2021).
- "What is Bitcoin?" animated video — Stefan Thomas (2011). (YouTube)
- Satoshi Nakamoto Institute (nakamotoinstitute.org) — canonical archive of primary Bitcoin texts.
- BIP index (github.com/bitcoin/bips) — all Bitcoin Improvement Proposals.
- Bitcoin Core GitHub (github.com/bitcoin/bitcoin) — contribution history for developer entries.
- Bitcoin Wiki (en.bitcoin.it) — reference entries for early figures including Casascius, Trendon Shavers, jercos.
- Electrum wallet documentation and history (electrum.org).
- Swan Bitcoin company history (swanbitcoin.com).
- Kraken company history (kraken.com).
- Xapo company history and documentation.
- BTCPay Server documentation and history (btcpayserver.org).
- statoshi.info — Jameson Lopp's Bitcoin node statistics dashboard.
- Lopp's personal blog (blog.lopp.net).
- Peter Todd's research blog (petertodd.org).
- Trilema blog archive — Mircea Popescu (trilema.com).
- Paxful platform history and shutdown announcement (2023).

### Lightning & Nostr
- U.S. Patent 4,995,082 — Claus-Peter Schnorr (1990, expired February 2008)
- MuSig paper (2018) — Maxwell, Poelstra, Seurin, Wuille
- MuSig2 paper (2020) — Nick, Ruffing, Seurin
- BIP327 (MuSig2 for Bitcoin) — Jonas Nick, Tim Ruffing, Elliott Jin
- BIP119 (CTV / OP_CHECKTEMPLATEVERIFY) — Jeremy Rubin
- BIP345 (OP_VAULT) — James O'Beirne
- Bitcoin Optech covenants documentation (bitcoinops.org)
- Delving Bitcoin forum covenant discussions (delvingbitcoin.org)
- BIP141 — Pieter Wuille (SegWit specification, 2015)
- BIP148 — Shaolinfry (UASF specification, 2017); UASF movement documentation (uasf.co)
- BIP340 (Schnorr Signatures) — Wuille, Nick, Ruffing
- BIP341 (Taproot) — Wuille, Nick, Towns
- BIP342 (Tapscript) — Wuille, Nick, Towns
- Taproot activation data (block 709,632, November 14, 2021)
- Speedy Trial activation mechanism documentation
- "The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments" (2016) — Joseph Poon & Thaddeus Dryja. The Lightning whitepaper.
- Core Lightning GitHub (github.com/ElementsProject/lightning)
- Breez documentation (breez.technology); Breez SDK documentation
- Phoenix wallet documentation (phoenix.acinq.co); trampoline routing specification; U.S. withdrawal/return (2024)
- Eclair implementation — ACINQ GitHub (github.com/ACINQ)
- Bitrefill documentation (bitrefill.com)
- "Optimally Reliable & Cheap Payment Flows on the Lightning Network" (2021) — Pickhardt & Richter
- Blockstream company documentation (blockstream.com); Liquid Network, Satellite, and Jade documentation
- "Forward Blocks" proposal — Mark Friedenbach
- Foundation Devices documentation (foundationdevices.com); Passport open-source hardware/firmware repository
- SeedSigner documentation and GitHub (github.com/SeedSigner/seedsigner)
- Trezor / SatoshiLabs documentation (trezor.io); Slush Pool history (braiins.com)
- Ledger documentation (ledger.com); 2020 data breach reporting; Ledger Recover controversy (2023)
- Coldcard documentation (coldcard.com); PSBT / BIP-174 specification
- Cash App Bitcoin feature documentation; Block Inc. quarterly earnings (Bitcoin revenue)
- Bitkey launch documentation (bitkey.build); 2-of-3 multisig architecture
- Block Inc. / TBD documentation (block.xyz)
- Unchained collaborative multisig and inheritance planning documentation (unchained.com)
- Casa documentation, Covenant and Key Shield products (keys.casa)
- BOLTs (Basis of Lightning Technology) specification (github.com/lightning/bolts)
- Eltoo / LN-Symmetry paper (2018) — Decker, Russell, Osuntokun
- LND GitHub (github.com/lightningnetwork/lnd)
- LDK (Lightning Development Kit) documentation (lightningdevkit.org)
- Lightning Labs documentation (lightning.engineering)
- Nostr protocol specification (github.com/nostr-protocol/nostr)
- Nostr NIPs repository (github.com/nostr-protocol/nips)
- Zeus Wallet GitHub (github.com/ZeusLN/zeus)
- Blixt Wallet GitHub (github.com/hsjoberg/blixt-wallet)
- Mutiny Wallet GitHub and shutdown announcement (December 2024)
- LNbits GitHub (github.com/lnbits/lnbits)
- Samourai Wallet GitHub and Whirlpool documentation
- Stacker News (stacker.news)
- Bitcoin Park Nashville documentation
- Citadel Dispatch (citadeldispatch.com)
- TFTC Media (tftc.io)
- What Bitcoin Did podcast (whatbitcoindid.com)
- Stephan Livera Podcast (stephanlivera.com)
- Spiral / Square Crypto developer funding documentation (spiral.xyz)

### Political & Legislative
- BitPay company history and SegWit2x/BCH support documentation (2017)
- OpenNode documentation (opennode.com)
- Bitcoin Sign Guy Congressional footage (July 12, 2017)
- Bitcoin Beach documentation (bitcoinbeach.com); Mike Peterson interviews
- Galoy Money / Blink wallet history (blink.sv)
- El Salvador Bitcoin Law (June 2021)
- Chivo wallet launch documentation
- IMF negotiations and El Salvador Bitcoin legal tender removal (2025)
- Jack Mallers / Strike Bitcoin 2021 Miami announcement (June 2021)
- Strike documentation (strike.me)
- Iris Energy SEC filings (IREN); renewable energy and HPC documentation
- Bitdeer Technologies SEC filings; Sealminer ASIC chip documentation
- CleanSpark SEC filings and energy sourcing documentation
- Foundry USA Pool hashrate statistics; DCG/Foundry company documentation
- Bitfarms SEC filings; Riot hostile takeover attempt documentation (2024)
- Riot Platforms SEC filings and Rockdale facility documentation
- Marathon Digital Holdings (MARA) SEC filings and Bitcoin treasury documentation
- Core Scientific bankruptcy filings (December 2022) and emergence (January 2024)
- Trump Bitcoin Conference Nashville speech (July 2024)
- Executive Order on Digital Assets / Strategic Bitcoin Reserve (January 2025)
- BITCOIN Act of 2024 — Senator Cynthia Lummis
- Digital Asset Anti-Money Laundering Act (2022, 2023) — Senator Elizabeth Warren
- Crypto-Currency Act / Bitcoin ban proposal — Rep. Brad Sherman (2019)
- Financial Innovation and Technology for the 21st Century Act (FIT21, 2024); House vote record (May 2024)
- Keep Your Coins Act — Rep. Warren Davidson
- CBDC Anti-Surveillance State Act — Rep. Tom Emmer
- CFTC Bitcoin futures approval (December 2017); CME and CBOE launch documentation

### Legal & Regulatory
- DOJ indictment of e-gold / Douglas Jackson (2007)
- Ulbricht trial record and sentencing documents (2015)
- Trump pardon of Ross Ulbricht (January 2025)
- DOJ criminal complaint against Carl Force IV (2015)
- DOJ criminal complaint against Shaun Bridges (2015)
- Variety Jones / Thomas Clark sentencing documents (2020)
- FBI criminal complaint against Blake Benthall / Defcon (2014)
- DOJ AlphaBay takedown announcement (July 2017)
- Europol Hansa Market simultaneous operation documentation (July 2017)
- SEC settlement with Erik Voorhees / SatoshiDice (2014)
- SEC v. Shavers (2013) — first U.S. court ruling affirming Bitcoin as money under securities law.
- FinCEN cease and desist against Casascius / Mike Caldwell (November 2013).
- Bitmain S-1 filing (2018, withdrawn)
- Genesis Trading bankruptcy filings (2023)
- Gemini Earn lawsuit documentation (2023)
- COPA v. Wright (2024 UK ruling — Craig Wright is not Satoshi)
- Ross Ulbricht trial record and sentencing documents
- GLBSE shutdown documentation (October 2012)
- BlackRock iShares Bitcoin Trust S-1 filing (June 2023)
- Grayscale Investments v. SEC (DC Circuit Court, August 2023)
- SEC spot Bitcoin ETF approval (January 10, 2024) — all approved ETFs
- SEC rejection letters to Winklevoss, ARK, VanEck, and others (2017–2023)
- ARK 21Shares Bitcoin ETF (ARKB) filing history
- Winklevoss ETF application (2013) and SEC rejection history
- Gensler MIT Bitcoin course materials (2018)
- Voyager Digital bankruptcy filings (July 2022); FTC charges against Stephen Ehrlich
- DOJ criminal complaint against Alex Mashinsky / Celsius (July 2023); guilty plea (December 2024)
- Celsius Network bankruptcy filings (July 2022)
- 3AC bankruptcy filings (British Virgin Islands, July 2022)
- Nevada Financial Institutions Division receivership order — Prime Trust (August 2023)
- Prime Trust bankruptcy filings
- BlockFi bankruptcy filings (November 2022)
- BlockFi / FTX credit facility documentation (June 2022)
- BlockFi SEC settlement ($100 million, February 2022)
- DOJ criminal indictment against Sam Bankman-Fried (December 2022)
- FTX bankruptcy filings (November 2022)
- SBF trial transcripts and sentencing documents (2023–2024)
- DOJ cooperation agreement with Caroline Ellison; trial testimony transcripts (2023)
- DOJ settlement with Binance / CZ ($4.3 billion, November 2023)
- CZ sentencing documents (2024)
- DOJ criminal complaint against Keonne Rodriguez and William Hill / Samourai Wallet (April 2024)
- McCormack v. Wright defamation case (UK, 2022)
