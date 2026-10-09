# Note 27 — Gaussian curvature

**Date:** 2026-10-09
**Status:** Scalar computed. Cone and curved funnel are different.

A shared audit scale is not a shared physical mechanism.

## Definition

In two dimensions the Riemann tensor is one number. The Gaussian curvature is that number divided by the area density,

K = R_r phi r phi / (g_rr g_phi phi).

For an embedded surface it is also the product of the principal curvatures, K = kappa_1 kappa_2. Theorema egregium: K is intrinsic. It does not depend on the embedding.

## Cone

Metric ds^2 = dr^2 + c(r)^2 d phi^2 with c = alpha r. Then K = -c''/c. The second derivative vanishes, so K = 0 for r > 0, as in note 26. Extrinsically one principal curvature is zero because the generators are straight, so the product is zero even though the parallel circles are curved.

The tip is the exception. Gauss-Bonnet on a loop around it converts the angular deficit into integrated curvature, integral K dA = 2 pi (1 - alpha). For alpha = 0.8 that is 2 pi / 5. It is a delta, not a regular value of K.

## Curved funnel

A surface of revolution with profile radius R(z) has

K = - R'' / ( R (1 + (R')^2 )^2 ).

Straight sides, R'' = 0, recover the cone. Curved sides do not. The profile R = sqrt(R0^2 + z^2) at z = R0 = 1 has K = -1/9. Negative curvature means nearby geodesics diverge. That is a local tidal field. The cone does not have it off the tip.

Elongation at fixed base radius, note 20, lengthens a straight generator if the side stays straight. K remains zero. A fall along a curved side would need R'' nonzero. That profile is not forced by the cone metric, and it is not the kink mass.

## Scope

K = 0 off the tip does not fix (v, d) and does not supply g. A chosen curved profile would be an import. Note 23 stands.
