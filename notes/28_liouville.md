# Note 28 — Liouville equation

**Date:** 2026-10-09
**Status:** Curvature equation for the conformal factor. Cone is the harmonic case.

A shared audit scale is not a shared physical mechanism.

## Equation

Write the metric in isothermal coordinates,

ds^2 = exp(2 u) (dx^2 + dy^2).

The Gaussian curvature of note 27 is then

K = - exp(-2 u) (u_xx + u_yy).

Rearranged,

Delta u + K exp(2 u) = 0.

This is Liouville's equation. It is the statement that u is the conformal factor of a metric with curvature K. It is not a field equation for the kink mass.

## Cone

Off the tip, K = 0, so Delta u = 0. The conformal factor is harmonic. On the unrolled sector, u = 0 is the solution, which is the flat metric of notes 22 and 24. A harmonic u does not prefer a direction and does not fix a scale.

The tip is outside this regular equation. The deficit 2 pi (1 - alpha) is the jump around the puncture, not a source term in Delta u on r > 0.

## Constant curvature

If K = -1, the equation is Delta u = exp(2 u). One solution on the disk is u = log( 2 / (1 - x^2 - y^2) ). At (0.2, 0.1) the residual of Delta u + K exp(2 u) is about 1e-7. Nearby geodesics diverge. That is the curved funnel of note 27, not the cone.

If K = +1, u = log( 2 / (1 + x^2 + y^2) ) is the sphere in stereographic coordinates. The cone is neither.

## Scope

Prescribing K and solving for u does not identify u with v, and it does not insert g. The cone solution is the harmonic one. Note 23 stands.
