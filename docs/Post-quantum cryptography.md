>quantum computer research; break cryptosystems; compromise confidentiality, integrity of communications; PQ Crypto; secure - interoperate; merely engineering challenge - ETA 20 years; 20 years to deploy modern PK crypto - PREPARE NOW

Substantial amount of research on quantum computers that exploit quantum mechanical phenomena to solve mathematical problems that are difficult or intractable for conventional computers. If large-scale quantum computers are ever built, they will be able to break many of the public-key cryptosystems currently in use. This would seriously compromise the confidentiality and integrity of digital communications on the Internet and elsewhere. The goal of _post-quantum cryptography_ (also called quantum-resistant cryptography) is to develop cryptographic systems that are secure against both quantum and classical computers, and can interoperate with existing communications protocols and networks.
While in the past it was less clear that large quantum computers are a physical possibility, many scientists now believe it to be merely a significant engineering challenge. Some engineers even predict that within the next twenty or so years sufficiently large quantum computers will be built to break essentially all public key schemes currently in use. **Historically, it has taken almost two decades to deploy our modern public key cryptography infrastructure.**  Therefore, regardless of whether we can estimate the exact time of the arrival of the quantum computing era, we must begin now to prepare our information security systems to be able to resist quantum computing.
Also, "Harvest now, decrypt later" / retrospective decryption surveillance strategy.
# CRYSTALS-Dilithium, CRYSTALS-KYBER,  SPHINCS
- post-quantum digital signature algorithm (DSA)
- selected by [[National Institute of Science and Technology (USA)|NIST]] for standardisation
## Kyber
- chrome support ✅
- cloudflare ✅
- Signal ✅
# Challenges
- Preliminary stages of development - [‘Post-Quantum’ Cryptography Scheme Is Cracked on a Laptop](https://www.quantamagazine.org/post-quantum-cryptography-scheme-is-cracked-on-a-laptop-20220824/)
	- solution - add on top of classical cryptography