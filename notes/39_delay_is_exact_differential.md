# Note 39 — Delay is an exact differential

**Date:** 2026-10-11
**Status:** Non-identical families run. Conditional theorem.

A shared audit scale is not a shared physical mechanism.

## Integrand

With N(s) = s / (s + ξ),

1/N - 1 = ξ / s.

Therefore

ΔT = integral from s_i to s_f of (ξ / s) ds = ξ ln(s_f / s_i).

The integrand is an exact differential when ξ is constant. The total depends only on the endpoints. Partitioning the interval redistributes the delay among cells. It does not change the sum. With a global ξ the lattice is invisible to the delay channel. Accumulation is the wrong word for that case.

## Families, all ν-blind

| Family | Setup | N=10 result | Across ν |
|--------|-------|-------------|----------|
| 1 | ξ_i in {1, 2}, ρ = 2 | 10.397 | identical |
| 2 | ξ = 1, ρ_i in {2, 3} | 8.9588 | identical |
| 3 | mixed (1, 2) and (2, 3) | 14.452 | identical |

Family 1 at N = 100 is 103.97, same across ν. No term contains a transverse argument, so the equality is exact, not numerical.

## Duality

| Observable | Sees ξ | Sees ρ | Sees ν |
|------------|--------|--------|--------|
| Delay | yes, weighted | yes, as logs | no |
| Defocus | no | yes, as logs | yes |

Delay measures the lapse distribution. Defocus measures the transverse closure. They are complementary.

## Domain bound

W_N / W_0 = 2^(ν N) reaches 10^80 when ν N = 80 ln 10 / ln 2 ≈ 265.7. N_max = 265.7 / ν. That is 531 cells at ν = 1/2 and 1063 at ν = 1/4. The linear defocus model fails past that point. It is a saturation flag, not a prediction of 10^150.

## Leak channel

The proof assumes ξ is transverse-independent. The only way ν enters the delay is if ξ = ξ(R, ν), so that the lapse scale is set by the transverse sector. In the defocus formula ξ also sets the transverse transition depth. It is doing double duty. If it is ever fixed by that transition rather than hosted, the delay inherits ν. The notes hold ξ hosted, so the theorem stands as stated. Its truth is the assumption's truth.

## Not claimed

No GR limit. No optical-gravity branding. No derived anchor. The one-input-short count of note 35 is unchanged. A global ξ makes the lattice even less of a lever on the anchor, because there is nothing to accumulate toward a scale.
