# Note 24 — Derivation of the cone geodesic equation

**Date:** 2026-10-09
**Status:** Derivation of note 22. No new physical claim.

A shared audit scale is not a shared physical mechanism.

## Metric

ds^2 = dr^2 + (alpha r)^2 d phi^2.

Nonzero components: g_rr = 1, g_phi phi = alpha^2 r^2. Inverse: g^rr = 1, g^phi phi = 1/(alpha^2 r^2). Alpha constant.

## From the Lagrangian

L = (1/2) (dr/dt)^2 + (1/2) alpha^2 r^2 (d phi/dt)^2.

phi is cyclic. Its conjugate momentum is conserved,

l = partial L / partial (d phi/dt) = alpha^2 r^2 d phi/dt.

The r equation is d/dt (partial L / partial dr/dt) = partial L / partial r,

d^2 r / dt^2 = alpha^2 r (d phi/dt)^2.

That is the radial geodesic equation of note 22. No potential enters L, so none enters the equation.

## From the Christoffel symbols

Gamma^lambda_mu nu = (1/2) g^lambda sigma ( partial_mu g_nu sigma + partial_nu g_mu sigma - partial_sigma g_mu nu ).

The only r derivative of the metric is partial_r g_phi phi = 2 alpha^2 r. The nonzero symbols are

Gamma^r_phi phi = - alpha^2 r,

Gamma^phi_r phi = Gamma^phi_phi r = 1/r.

The geodesic equation d^2 x^lambda / dt^2 + Gamma^lambda_mu nu (dx^mu/dt) (dx^nu/dt) = 0 then splits.

Radial: d^2 r / dt^2 - alpha^2 r (d phi/dt)^2 = 0.

Angular: d^2 phi / dt^2 + (2/r) (dr/dt) (d phi/dt) = 0.

The angular equation is d/dt ( r^2 d phi/dt ) = 0. Since alpha is constant this is the same conservation law as l = alpha^2 r^2 d phi/dt.

## Unrolling, derived

Set psi = alpha phi. Then d psi = alpha d phi, and

ds^2 = dr^2 + r^2 d psi^2,

the flat polar metric on a sector of angle 2 pi alpha. Straight lines in (r cos psi, r sin psi) are the geodesics of a flat metric, hence of the cone. A line at perpendicular distance b from the tip is r^2 = b^2 + s^2, which is r(phi) = b / cos( alpha (phi - phi_0) ) on the interval where the cosine stays positive.

## Scope

Both routes give the same equation. Neither inserts g, v, or d. Note 23 stands: this derivation does not reopen the bridge.
