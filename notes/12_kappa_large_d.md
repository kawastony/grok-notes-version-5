# Note 12 — Kappa in the large-d limit

**Date:** 2026-10-09
**Status:** Computed for an imported odd scalar. Not a derivation of the coupling.

A shared audit scale is not a shared physical mechanism.

## Setup

Import, not reduction: add V(x) = g x, the odd scalar of note 11. Walls at +d and -d. At large separation each near-zero mode is the single-wall Jackiw-Rebbi mode, density even about its wall. The single-wall profile is sech(x - x0)^v, so

<L|x|L> = -d, <R|x|R> = +d,

with corrections of order exp(-2 v d) from hybridization and from the distortion of each wall by the other.

Define kappa by the diagonal bias

<L|V|L> - <R|V|R> = 2 kappa g d.

Then

kappa = (<L|x|L> - <R|x|R>) / (2 d) = -1 + O(exp(-2 v d)).

The off-diagonal <L|x|R> is the same order as the overlap and renormalizes Delta E, it does not set kappa.

## What this settles

If the odd scalar is granted, Step 1 is not an insertion of an arbitrary coefficient. Kappa is fixed at -1 in the large-d limit. The two-mode block is

H_2 = (Delta E / 2) sigma_x - (g d) sigma_z,

up to that exponential correction and up to the sign convention for which wall sits at +d. This is the same tilt as note 9, with the coefficient no longer free.

## What this does not settle

V = g x is not in the packet. Kappa fixed inside an imported term is not a forced coupling. The isolated class still has partial F / partial g = 0. A lattice check of the same projection was not used: a central-difference operator did not isolate the chiral pair, so it is not evidence for or against kappa.
