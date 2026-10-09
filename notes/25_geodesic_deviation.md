# Note 25 — Geodesic deviation on the cone

**Date:** 2026-10-09
**Status:** Deviation equation derived. Local tidal field is zero off the tip.

A shared audit scale is not a shared physical mechanism.

## Equation

Two nearby geodesics, tangent u and separation xi. The deviation equation is the commutator of covariant derivatives along the congruence,

D^2 xi^mu / dt^2 + R^mu_nu rho sigma u^nu xi^rho u^sigma = 0.

The Riemann term is the relative acceleration. No potential is added by hand. If Riemann vanishes, nearby geodesics deviate only by the initial separation and its initial rate, as in flat space.

## Cone Riemann

Metric of notes 22 and 24, ds^2 = dr^2 + (alpha r)^2 d phi^2. For a metric dr^2 + c(r)^2 d phi^2 the Gaussian curvature is K = -c''(r)/c(r). Here c = alpha r, so c'' = 0 and K = 0 at every r > 0. The Riemann tensor vanishes off the tip.

The tip is not a regular point. A loop around it has holonomy 2 pi (1 - alpha): a vector parallel-transported around the deficit returns rotated by the deficit angle. The integrated curvature is a delta at r = 0,

integral K dA = 2 pi (1 - alpha).

For alpha = 0.8 that is 2 pi / 5. Away from the tip the deviation equation collapses to

D^2 xi^mu / dt^2 = 0.

Separation grows at most linearly in the affine parameter. There is no local tidal stretch, and no local focusing, until a geodesic hits the singularity.

## What this does not do

A delta at the tip is not an odd scalar along a wall coordinate, and it is not g. Geodesics that miss the tip never feel it. Geodesics that hit it are removed in finite time, as in note 22. The deviation equation does not fix (v, d), does not generate a sigma_z detuning, and does not supply a unit. Note 23 stands.
