# Note 26 — Riemann tensor on the cone

**Date:** 2026-10-09
**Status:** Components computed. One independent entry, and it is zero off the tip.

A shared audit scale is not a shared physical mechanism.

## Definition

R^rho_sigma mu nu = partial_mu Gamma^rho_nu sigma - partial_nu Gamma^rho_mu sigma + Gamma^rho_mu lambda Gamma^lambda_nu sigma - Gamma^rho_nu lambda Gamma^lambda_mu sigma.

Symmetries: antisymmetric in mu nu, antisymmetric in the lowered first pair, pair-symmetric, and the first Bianchi identity. In two dimensions those leave one independent component.

## Cone symbols

From note 24, metric ds^2 = dr^2 + (alpha r)^2 d phi^2.

Gamma^r_phi phi = - alpha^2 r. Gamma^phi_r phi = Gamma^phi_phi r = 1/r. The rest that enter here are zero.

## The component

R^r_phi r phi = partial_r Gamma^r_phi phi - partial_phi Gamma^r_r phi + Gamma^r_r lambda Gamma^lambda_phi phi - Gamma^r_phi lambda Gamma^lambda_r phi.

partial_r Gamma^r_phi phi = - alpha^2. The phi derivative vanishes. The first quadratic term vanishes. The last term is Gamma^r_phi phi times Gamma^phi_r phi = (- alpha^2 r)(1/r) = - alpha^2.

R^r_phi r phi = - alpha^2 - (- alpha^2) = 0.

Lowering with g_rr = 1 gives R_r phi r phi = 0. Gaussian curvature K = R_r phi r phi / (g_rr g_phi phi) = 0 for r > 0. The same zero is K = -c''/c with c = alpha r, note 25.

## Distributional piece

The component above is the regular part. A loop around the tip has holonomy 2 pi (1 - alpha), so the integrated curvature is a delta at r = 0, integral K dA = 2 pi (1 - alpha). That delta is not a component of the regular tensor on r > 0.

## Scope

The regular Riemann tensor does not stretch geodesics off the tip, does not fix (v, d), and does not supply g. Note 23 stands.
