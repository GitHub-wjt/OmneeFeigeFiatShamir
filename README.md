Feige-Fiat-Shamir
=================

A small proof of concept of the Feige-Fiat-Shamir zero-knowledge proof as described in Feige, Uriel, Amos Fiat, and Adi Shamir. ”Zero-knowledge proofs of
identity.”

run by:
python main.py mode n k t

where "mode" is one of "verifier", "prover" or "cheater"
(verifier has to be run first anyway), n is the agreed upon big integer, k the key size and t the number of challenges to be executed

#Source:
I should have really sourced by forking, but the madness got out of hand and ended up using it.
https://github.com/marceleng/Feige-Fiat-Shamir
