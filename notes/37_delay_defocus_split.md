# Note 37 — Delay is branch-blind; defocus is branch-dependent

**Date:** 2026-10-11
**Status:** Identical-cell (self-similar) lattice executed. Conservative statement.

A shared audit scale is not a shared physical mechanism.

## Minimal statement

In the self-similar lattice (cell ratio ρ fixed, so every cell is identical), cumulative axial delay is independent of the closure parameter ν, while cumulative transverse spreading retains explicit ν-dependence.

## Formulas

Lapse N = σ / (σ + 1), σ = s / ξ. Per-cell axial delay:

Δt_cell = ξ ln ρ.

No transverse quantity enters. Therefore

Δt_tot = N ξ ln ρ, ∂(Δt_tot)/∂ν = 0 exactly.

Bundle width from the Jacobi field B(σ) = R_0 σ^ν (1 + 1/σ), with R ∝ σ^ν:

W_N / W_0 = ρ^(ν N) · [1 + (σ_0 ρ^N)^(-1)] / [1 + σ_0^(-1)].

Outer law: W_N / W_0 ∼ (1/2) ρ^(ν N). Rate ν ln ρ.

## Numbers, hosted

ξ = 1, ρ = 2, σ_0 = 1, W_0 = 1. ξ ln ρ = ln 2 ≈ 0.6931.

| N | delay (all ν) | defocus ν=0 | ν=1/4 | ν=1/2 |
|---|------------------|---------------|--------|--------|
| 10 | 6.931 | 0.5005 | 2.831 | 16.02 |
| 100 | 69.31 | 0.500 | 1.68e7 | 5.63e14 |
| 1000 | 693.1 | 0.500 | 9.05e74 | 1.64e150 |

Numbers scale with the hosted ξ ln ρ. The law does not.

## Corrections kept

Fixed additive cell length is not identical: the per-cell delay ξ ln(1 + a/s_i) weakens outward. Identical cells require self-similar tiling. Multiplying a single inner-cell ratio N times produces a fake focus at ν = 0; the product telescopes to B(σ_N)/B(σ_0), which stays finite. Consistent with no conjugate points.

## What this is

A sector separation inside the optical lattice. Delay is a temporal/axial observable of the lapse. Defocus is a transverse observable of the closure branch. The exponential defocus rate ν ln ρ is a candidate datum for ν.

## What this is not

Not a derivation of the anchor. ξ, ρ, σ_0 remain hosted. Not a constant g. Not a rotation curve. Not a map from the kink packet. The dimensional count of note 35 stands: one input short. The packet firewall of notes 31 and 32 stands.
