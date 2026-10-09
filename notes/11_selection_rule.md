# Note 11 — Selection rule for a detuning

**Date:** 2026-10-09
**Status:** Step 1 as a symmetry test. Isolated packet has no sigma_z channel.

A shared audit scale is not a shared physical mechanism. This note asks what forbids or allows a sigma_z term in the two-mode block. It does not fit a ruler.

## Isolated class

The packet Hamiltonian is

H = -i sigma_y d/dx + m(x) sigma_z,

with m real. For the two-wall family, m is even: m(-x) = m(x), walls at +d and -d. The coordinates of this family are v and d. An external acceleration is not among them.

Mirror parity swaps the left and right walls. The near-zero pair can be chosen as mirror partners |L> and |R>. A scalar perturbation is classified by that mirror.

## Three projections

Let V be multiplication by a real function, acting as the identity in spin space. This operator is not in H. The projection onto the pair is:

- Even V. Mirror symmetry forces <L|V|L> = <R|V|R>. The two-mode block is a common shift times I, plus an overlap correction to the existing sigma_x split. No sigma_z.
- Odd V. Mirror symmetry forces <L|V|L> = -<R|V|R>. The diagonal bias is nonzero. The off-diagonal <L|V|R> is an overlap of tails and is exponentially small at large d. The block is a sigma_z detuning.
- A deformation delta m(x) sigma_z. This stays inside the packet class. An even delta m renormalizes the split. An odd delta m is a different defect, not an acceleration.

## Result

A sigma_z detuning is allowed only for an odd scalar that is not part of the isolated Hamiltonian. An even perturbation, including any overall energy shift, cannot supply it. The reduction of the present H does not generate the detuning.
