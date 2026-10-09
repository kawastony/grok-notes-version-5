# Note 31 — Do the micro dynamics map onto this repo?

**Date:** 2026-10-09
**Status:** Check. Packet transferred. Cone dynamics do not inherit it.

A shared audit scale is not a shared physical mechanism. Version 4 is the micro record. This repo has two layers. Only one of them is that record.

## What maps

The kink packet maps, because it was copied, not recomputed.

| v4 micro | v5 note | same object? |
|----------|---------|----------------|
| Zero mode, sign-changing mass | 00, 02 | yes |
| Delta E = A(v) exp(-2 v d), tail product | 06, 19 | yes |
| xi = 1/(2v) | 06 | yes |
| Transfer T = pi / Delta E, middle 0.126, norm 1 | 00, 02, 17 | yes |
| Even scalar to I, odd scalar to sigma_z | 11, 12 | yes, classification of the same pair |
| Field blindness, partial F / partial g = 0 | 08, 13 | yes |

The numbers were not rerun here. The v = 1 window fit 1.772 exp(-d/0.509), the d = 2 transfer 0.07084, and the weights 0.871, 0.437, 0.003 stay version-4 results. This repo cites them.

## What does not map

The cone layer is a different dynamical system.

| v4 micro | v5 cone | map? |
|----------|---------|------|
| H = -i sigma_y d/dx + m sigma_z | ds^2 = dr^2 + (alpha r)^2 d phi^2 | no common operator |
| v, kink mass | alpha, deficit | not identified |
| wall coordinate x | generator r | not identified, note 18 |
| Delta E, transfer clock | l = alpha^2 r^2 d phi/dt | different conserved quantity |
| Callias index N_def | K = 0 off the tip, holonomy 2 pi (1-alpha) | different charge |
| active feed Delta W8 = +0.088 | alpha(t) during active | reading only, note 29 |
| hedgehog Callias count | cone interior Riemann | v4 count failed; cone Riemann is zero. Not a map |

Version 4 note 03 puts active and both pauses on one Callias operator, spectral motion at fixed index. Version 5 notes 29 and 30 use pause as a frozen alpha and active as alpha(t). That is a reuse of the words. The operator tubes were not rerun. Delta W8 is not a geodesic.

## Result

The micro packet maps onto notes 00, 02, 06, 11, and 19 as the same earned object. It does not map onto the geodesic, Riemann, Gaussian, Liouville, or elongating-funnel dynamics. Those notes do not inherit the transfer clock, and the transfer clock does not inherit alpha.
