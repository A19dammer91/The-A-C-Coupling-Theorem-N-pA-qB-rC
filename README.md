# The A–C Coupling Theorem — Formal

**Exact closed-form representation counts for three-variable linear Diophantine systems, with extension to four variables.**

---

## System Definition

**N = pA + qB + rC**, with:
- N non-negative integer
- coefficients p, q, r positive integers
- variables A, B, C non-negative integers

---

## Structural Conditions (V1–V4)

| Condition | Statement |
|---|---|
| V1 | gcd(p, q) = 1 (coprimality) |
| V2 | p ≡ 1 (mod q) |
| V3 | r divides q |
| V4 | p ≡ 1 (mod r) |

---

## Main Results

### Theorem I — The A–C Coupling
Under V1–V4, the invariant **A + rC ≡ N (mod q)** emerges. Variable B is the sole free variable; A and C are modularly locked to one another.

### Theorem II — Exact O(1) Count
The representation count **R₃(N; p, q, r)** is given by an exact closed formula replacing the classical O(N/r) recursive Popoviciu approach. The formula exploits a periodic remainder cycle of fixed length q/r, yielding constant-time computation independent of N.

### Theorem III — Frobenius Collapse
For system (19, 9, 3), adding s = 1 causes **g(19, 9, 3, 1) = 0**: every positive integer becomes representable. The Frobenius problem ceases to exist entirely.

---

## Extension to 4D

**N = pA + qB + rC + sD** with added conditions:
- s divides r
- p ≡ 1 (mod s)

The coupling structure **A + rC + sD ≡ N (mod q)** follows identically, but R₄ = Σᴅ R₃(N − sD) runs at O(N/s) — a fully closed O(1) formula remains an open research direction.

---

## Full Paper

The complete mathematical treatment, proofs, and examples are available at:

**DOI: [10.5281/zenodo.20114511](https://doi.org/10.5281/zenodo.20114511)**



