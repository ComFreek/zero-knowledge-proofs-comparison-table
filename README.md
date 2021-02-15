# Comparison Table of Introductory Zero-Knowledge Proof Examples

I had created this table while attending the lecture [*Privacy-Preserving Cryptocurrencies*](https://www.chaac.tf.fau.eu/teaching/lectures/) by [Dominique Schröder](https://dominique-schroeder.de/) in Summer 2020 at [FAU Erlangen-Nürnberg](https://fau.eu), primarily to improve my own understanding of the material.
Privacy-preserving cryptocurrencies use zero-knowledge proofs to hide the identities of senders and/or amounts transerred in transactions.

## Comments (retrospective)

- Don't take the column with "any hard graph property" too seriously, I think it's flawed
- I might be wrong at places about terminology. As far as I understand, cryptographers employ a -- weird on first sight -- family of definitions given by the regex `(zero-knowledge)? (argument|proof) (of knowledge)?`.

  I think "argument vs proof" qualifies whether you consider soundness probabilistically or not.
  "zero-knowledge" qualifies that there is a simulator that can simulate your protocol "from the outside" with "rewinding Turing machines".
  (This is taken to be the formalization of the informal notion of zeroknowledge).
  And "of knowledge" qualifies that the protocol proves knowledge *of something*.
  Given a prover in your protocol, for "of knowledge" an extractor is required to exist that is able to extract a witness for the "of something".
