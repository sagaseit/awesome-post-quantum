# awesome-post-quantum [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources about post-quantum cryptography.

To contribute, please file a PR. Please list items alphabetically.

We try to keep this page up to date, as some resources and URLs may become
obsolete. If you notice such issues before us, please file PR or an
Issue.

"PQC" stands for post-quantum cryptography.


## Government Initiatives

USA:

* [NIST's PQC Project](https://csrc.nist.gov/projects/post-quantum-cryptography/post-quantum-cryptography-standardization) ([Selected Algorithms 2022](https://csrc.nist.gov/projects/post-quantum-cryptography/selected-algorithms-2022) announcement)

* [DHS PQC approach and roadmap](https://www.dhs.gov/quantum)
* [NSA PQC FAQ](https://media.defense.gov/2021/Aug/04/2002821837/-1/-1/1/Quantum_FAQs_20210804.PDF)
* [NIST and NCCoE's Migration to PQC](https://www.nccoe.nist.gov/sites/default/files/2022-07/pqc-migration-project-description-final.pdf)

EU:

* [A Coordinated Implementation Roadmap for the Transition to Post-Quantum Cryptography](https://digital-strategy.ec.europa.eu/en/library/coordinated-implementation-roadmap-transition-post-quantum-cryptography)

South Korea:

* [KpqC Competition](https://kpqc.or.kr/competition_02.html)

France:

* [ANSSI's views](https://cyber.gouv.fr/en/publications/follow-position-paper-post-quantum-cryptography)

UK:

* [NCSC's Next steps in preparing for post-quantum cryptography](https://www.ncsc.gov.uk/whitepaper/next-steps-preparing-for-post-quantum-cryptography) 

## Research Resources

* [IACR ePrint](https://www.google.com/search?q=site%3Aeprint.iacr.org+%22post-quantum%22)
* [pqcrypto.org](https://pqcrypto.org/) (incl. conference series)

Survey papers:

* [A Decade of Lattice-Based Cryptography](https://eprint.iacr.org/2015/939.pdf) by Chris Peikert
* [A Survey on Code-Based Cryptography](https://arxiv.org/abs/2201.07119) by Violetta Weger, Niklas Gassner and Joachim Rosenthal
* [Mathematics of Isogeny-Based Cryptography](https://arxiv.org/abs/1711.04062) by Luca de Feo
* [Post-Quantum Cryptography](https://www.researchgate.net/profile/Nicolas-Sendrier-2/publication/226115302_Code-Based_Cryptography/links/540d62d50cf2df04e7549388/Code-Based-Cryptography.pdf) by Daniel J. Bernstein, Johannes Buchmann and Erik Dahmen
* [Post-quantum cryptography---dealing with the fallout of physics success](https://eprint.iacr.org/2017/314) by Daniel J. Bernstein and Tanja Lange
* [The Learning with Errors Problem](https://cims.nyu.edu/~regev/papers/lwesurvey.pdf) by Oded Regev

## Recommendations for Organizations

* [Post-Quantum Cryptography 101: Why Your Organization Needs to Pay Attention](https://terraquantum.swiss/news/post-quantum-cryptography-101-why-your-organization-needs-to-pay-attention/)
* [Postkvantová kryptografie v protokolu TLS: jak nasadit vše potřebné už dnes](https://www.root.cz/clanky/postkvantova-kryptografie-v-protokolu-tls-jak-nasadit-vse-potrebne-uz-dnes/#h26) by Jakub Anderka(CZ)


## Software Projects
* [jtesta/ssh-audit](https://github.com/jtesta/ssh-audit)
* [aws/s2n-tls](https://github.com/aws/s2n-tls/tree/main/pq-crypto)
* [kudelskisecurity/crystals-go](https://github.com/kudelskisecurity/crystals-go)
* [Microsoft/PQCrypto-LWEKE](https://github.com/Microsoft/PQCrypto-LWEKE) (FrodoKEM)
* [Microsoft/PQCrypto-SIDH](https://github.com/Microsoft/PQCrypto-SIDH)
* [mupq/pqm4](https://github.com/mupq/pqm4)
* [Open Quantum Safe](https://openquantumsafe.org/)
* [open-quantum-safe/liboqs](https://github.com/open-quantum-safe/liboqs)
* [PQClean/PQClean](https://github.com/PQClean/PQClean)
* [rustpq/pqcrypto](https://github.com/rustpq/pqcrypto)
* [paulmillr/noble-post-quantum](https://github.com/paulmillr/noble-post-quantum) (Dilithium, Kyber, Sphincs+ in JS)
* [PQ Code Package](https://github.com/pq-code-package) (a Linux Foundation [PQCA](https://pqca.org/) project building high-assurance implementations of standards-track algorithms)

Official, authors' implementations of the NIST-selected algorithms:

* [Dilithium](https://pq-crystals.org/dilithium/software.shtml)
* [Falcon](https://falcon-sign.info/impl/falcon.h.html)
* [Kyber](https://pq-crystals.org/kyber/software.shtml)
* [HQC](https://pqc-hqc.org/implementation.html)
* [SPHINCS+](https://sphincs.org/software.html)


## NIST Post-Quantum Cryptography Standardization

* Homepage [NIST Post-Quantum
  Cryptography](https://csrc.nist.gov/Projects/post-quantum-cryptography)

* All [Round 1 submissions](https://csrc.nist.gov/Projects/post-quantum-cryptography/Round-1-Submissions)

### Selected algorithms 2022


### Algorithms selected for standardization 

#### Selected in 2022

Lattice-based:

* [Dilithium](https://pq-crystals.org/dilithium/) (signature)
    - [FIPS 203: Module-Lattice-Based Key-Encapsulation Mechanism Standard](https://csrc.nist.gov/pubs/fips/203/final)
* [Falcon](https://falcon-sign.info/) (signature)
* [Kyber](https://pq-crystals.org/kyber) (KEM)
    - [FIPS 204: Module-Lattice-Based Digital Signature Standard](https://csrc.nist.gov/pubs/fips/204/final)

Hash-based:

* [SPHINCS+](https://sphincs.org/) (signature)
    - [FIPS 205: Stateless Hash-Based Digital Signature Standard](https://csrc.nist.gov/pubs/fips/205/final)


#### Selected in 2025

* [HQC](https://www.pqc-hqc.org/) (KEM)


## Round 3 submissions

(Only listing those that were not selected for standardization or round
4)

Lattice-based:

* [FrodoKEM](http://frodokem.org/) (KEM, alternate candidate)
* [NTRU](https://ntru.org/) (KEM, finalist)
* [NTRU Prime](https://ntruprime.cr.yp.to/) (KEM, alternate candidate)
* [SABER](https://www.esat.kuleuven.be/cosic/pqcrypto/saber/) (KEM, finalist)

MQ-based:

* [GeMSS](https://www-polsys.lip6.fr/Links/NIST/GeMSS.html) (signature,
  alternate candidate)
* [Rainbow](https://www.pqcrainbow.org/) (signature, finalist)

ZKP-based:

* [Picnic](https://microsoft.github.io/Picnic/) (signature, alternate
  candidate)

### Round 4 submissions

(Only listing those that were not selected for standardization)

Code-based:
* [BIKE](https://www.esat.kuleuven.be/cosic/pqcrypto/saber/) (KEM)
* [Classic McEliece](https://classic.mceliece.org/) (KEM)

Isogeny-based:

* [SIKE](https://sike.org/) (KEM)
    - Withdrawn, see for example [You could have broken SIDH](https://yx7.cc/blah/2022-08-22.html)

## NIST PQC Additional Digital Signature Schemes

This project coming after the selection of 4 signatures in 2022 aims to
select algorithms "that are not based on structured lattices" and/or
"that have short signatures and fast verification."

* Homepage [PQC Digital Signature
  Schemes](https://csrc.nist.gov/projects/pqc-dig-sig)

* [Round 1 submissions](https://csrc.nist.gov/Projects/pqc-dig-sig/round-1-additional-signatures)

* [Round 2 submissions](https://csrc.nist.gov/Projects/pqc-dig-sig/round-2-additional-signatures)

* [Comparison tool](https://pqshield.github.io/nist-sigs-zoo/)

## Other National Standards

[South Korea](https://kpqc.or.kr/competition_02.html):

* [AIMer](https://www.kpqc.or.kr/images/pdf/AIMer.pdf) (signature)
* [HAETAE](https://kpqc.cryptolab.co.kr/haetae) (signature)
* [NTRU+](https://www.kpqc.or.kr/images/pdf/NTRU+.pdf) (KEM)
* [SMAUG-T](https://kpqc.cryptolab.co.kr/smaug-t) (KEM)


## IETF Specifications

Internet Drafts and RFCs:

* ID [Framework to Integrate Post-quantum Key Exchanges into Internet Key Exchange Protocol Version 2 (IKEv2)](https://datatracker.ietf.org/doc/html/draft-tjhai-ipsecme-hybrid-qske-ikev2-04)
* ID [Hybrid Post-Quantum Key Encapsulation Methods (PQ KEM) for Transport Layer Security 1.2 (TLS)](https://datatracker.ietf.org/doc/html/draft-campagna-tls-bike-sike-hybrid)
* ID [Hybrid key exchange in TLS 1.3](https://datatracker.ietf.org/doc/html/draft-ietf-tls-hybrid-design)
* RFC 8391: [XMSS: eXtended Merkle Signature Scheme](https://datatracker.ietf.org/doc/html/rfc8391)
* RFC 8554: [Leighton-Micali Hash-Based Signatures](https://datatracker.ietf.org/doc/html/rfc8554)


## Other Algorithms

Hash-based:

* [PRUNE-HORST](https://github.com/gravity-postquantum/prune-horst) (few-times signature)

Isogeny-based:

* [CSIDH](https://csidh.isogeny.org/) (KEM)




## Misc

* [SUPERCOP](https://bench.cr.yp.to/results-kem.html) (benchmarks)
* [PQCHacks: a gentle introduction to post-quantum cryptography (slides)](https://cr.yp.to/talks/2015.12.27/slides-dan+tanja-20151227-16x9.pdf)
* [PQCrypto Usage & Deployment](https://ianix.com/pqcrypto/pqcrypto-deployment.html)
* Quantum Doomsday Planning blog posts:
    - [1/2: Risk assessment & quantum attacks](https://www.taurushq.com/blog/quantum-doomsday-planning-2-2-the-post-quantum-technology-landscape/)
    - [2/2: The post-quantum technology
      landscape](https://www.taurushq.com/blog/quantum-doomsday-planning-2-2-the-post-quantum-technology-landscape/)
* [PQC Cheat Sheet](https://github.com/marioschiener/PQC-Cheat-Sheet)
* ["Fancy" Cryptography](https://github.com/fancy-cryptography/fancy-cryptography)

## Related awesome-pages

* [awesome-quantum-computing](https://github.com/desireevl/awesome-quantum-computing)
* [awesome-quantum-software](https://github.com/qosf/awesome-quantum-software)
