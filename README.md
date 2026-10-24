# Probatur

Machine-checked proofs that zero-knowledge circuits accept **exactly** what their rule allows: sound and complete, for every input, re-checkable with one command. A project of [Next Ridge Solutions Ltd](mailto:probatur@nxridge.com).

## Published proofs

| Repository | What is proved |
| --- | --- |
| [bigmult](https://github.com/probatur/bigmult) | our BigMult circuit (4 × 64-bit limbs) computes exactly the integer product |
| [bigmodinv](https://github.com/probatur/bigmodinv) | our BigModInv circuit accepts exactly the modular inverse |
| [longtoshortnoendcarry](https://github.com/probatur/longtoshortnoendcarry) | our carry-normalisation circuit accepts exactly the correct normalised form |

Each covers a circom-bigint template that the 2022 public audit listed as "In Progress". Each proof is checked by the Rocq/Coq kernel and by an independent kernel checker, with no axioms, and rebuilds with `docker build .`.

Contact: probatur@nxridge.com
