# Dipole Antenna Pattern

A single-page HTML visualisation of the gain characteristics of a half-wave dipole antenna, plotted in polar coordinates.

## Usage

Open `index.html` directly in a browser — no build step or server required.

## Background

A half-wave dipole has a toroidal radiation pattern. Gain peaks broadside to the antenna (~2.15 dBi) and drops to zero off the tips. This plot renders the standard analytical pattern:

```
E(θ) = cos(π/2 · cos θ) / sin θ
```
