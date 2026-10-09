# Note 22 — Geodesic equations on the cone

**Date:** 2026-10-09
**Status:** Intrinsic equations. Not a gravitational fall.

A shared audit scale is not a shared physical mechanism.

## Metric

The cone used in version 4 note 62, deficit included,

ds^2 = dr^2 + (alpha r)^2 d phi^2,

phi identified with phi + 2 pi. Alpha = 1 is the plane. Alpha < 1 is a deficit of 2 pi (1 - alpha). The slant coordinate r is the distance to the tip. This is the static cone. An elongating funnel is a different metric at each instant.

## Equations

Affine parameter t. The angular momentum is conserved,

l = alpha^2 r^2 d phi / dt.

The radial equation is

d^2 r / dt^2 - alpha^2 r (d phi / dt)^2 = 0.

With the energy constant epsilon = (dr/dt)^2 + l^2 / (alpha^2 r^2), this is motion in a centrifugal barrier. No potential is present. Nothing in these equations is g, and nothing is the kink mass v.

## Unrolling

Set psi = alpha phi. Then ds^2 = dr^2 + r^2 d psi^2, the flat polar metric, with psi ranging over an interval of length 2 pi alpha. Geodesics are straight lines on that sector.

A line whose perpendicular distance to the tip is b has

r^2 = b^2 + s^2,

s the arc length. In cone coordinates,

r(phi) = b / cos( alpha (phi - phi_0) ),

on the interval where the cosine is positive and the line has not crossed the cut. A line aimed at the tip, b = 0, reaches r = 0 in finite affine time. The tip is singular. The geodesic does not continue uniquely through it.

Checked: alpha = 0.8, b = 1.5. The straight line on the unrolling satisfies the radial equation to 1e-11 at three sample points.

## What is absent

A geodesic has no preferred direction down a generator. The fall in notes 20 and 21 needed a gradient along the slant. That gradient is not this equation. Constraining a particle to a cone in an external gravitational field adds a potential and a normal force. Those are imports. They are not the intrinsic geodesics.
