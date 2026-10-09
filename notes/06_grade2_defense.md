# Note 6 — Grade 2 defense

**Date:** 2026-10-09
**Status:** Load-bearing line. Asymptotic split is grade 1. Window fit is grade 2.

A shared audit scale is not a shared physical mechanism. The ranking in note 3 stands only if the exponential is forced. This note defends that, and it marks the part that is only calibrated.

## Forced

Parent: version 4, notes 43, 49, 54.

The single-wall zero mode is N sech(x)^v, with

N^2 = Gamma(v+1/2) / (sqrt(pi) Gamma(v)).

The far tail is N 2^v exp(-v |x|). Walls at plus and minus d. The product of the tails supplies

Delta E = [4^v Gamma(v+1/2) / (sqrt(pi) Gamma(v))] exp(-2 v d).

No free functional choice enters. The exponent is the asymptotic mass outside each wall. The prefactor is the tail normalization. At v = 1 the formula is 2 exp(-2d). At other v it is not the old 2v guess.

Continuum grid, 801 points on [-16, 16]. Ratio of the measured lowest absolute eigenvalue to this formula:

| v | d=2 | d=3 |
|---|-----|-----|
| 0.5 | 1.003 | 1.002 |
| 1.0 | 0.965 | 0.996 |
| 1.5 | 0.948 | 0.996 |
| 2.0 | 0.933 | 0.997 |

At d = 3 the coefficient is the tail normalization. At d = 2 the walls are not yet asymptotic, and the ratio sits a few percent low. Exponent and prefactor are both accounted for. No a or m0 is inserted.

The length check is the same force. A tail exp(-v x) from each wall gives xi = 1/(2v). Fitted xi is 0.509 at v = 1 and 0.255 at v = 2, against 0.5 and 0.25.

This line is grade 1 inside the lattice: form derived, constant derived, fixed before the comparison, then checked.

## Calibrated, not selected

The phrase "the v = 1 fit Delta E = 1.772 exp(-d/0.509)" is a window calibration. Note 49 measured A and xi before the prefactor was closed. Note 54 closed A(v). The fit does not choose the exponential. It checks a form already fixed, on a window that includes non-asymptotic points. That check is grade 2.

If the exponential had been an ansatz, the packet would drop to grade 3 and the ranking against the galactic ruler would collapse. It was not an ansatz. The strain is real only if this distinction is dropped.

## What stays open

Finite-d corrections below the asymptotic formula are not derived. Chirality of the numerical kernel remains a mixture. The grade-1 claim is the large-d tail product, not every lattice print at small d.

Grade 1 here is internal. It does not supply a metre, an electron-volt, or a coupling g. Note 4 still marks those conversions as not supplied.
