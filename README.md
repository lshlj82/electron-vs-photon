# Electrons and Photons, Interactively · 전자와 광자

Where do the energy–momentum relations of a massive particle and a photon come from? An interactive companion to the supplementary note “Where do the energy–momentum relations of particles and photons come from? The Schrödinger equation vs. Maxwell's wave equation,” with an English / 한국어 switch.

**Live demo:** https://lshlj82.github.io/electron-vs-photon/

Created by **Claude Opus 5.5**, following the guidance of **Sang Hoon Lee**. Companion to the demos on [degenerate Fermi gases](https://lshlj82.github.io/degenerate-fermi-gas/) and [photon statistics](https://lshlj82.github.io/photon-statistics/).

## What's inside

1. **Same box, same momenta, different energies.** One standing wave in a box of length L, with λ_n = 2L/n and p_n = nh/2L for both, next to the two energy ladders: E_n ∝ n² for the electron, E_n ∝ n for the photon.
2. **From wave equation to dispersion relation.** Plane waves turn ∂/∂t into −iω and ∇ into ik, so the Schrödinger equation gives ω = ħk²/2m and the Maxwell wave equation ω = ck; a time derivative of order a and a space derivative of order b give ω^a ∝ k^b. The plot shows both curves with the phase velocity (slope from the origin) and group velocity (tangent): v_g = 2v_ph for the electron, v_ph = v_g = c for light.
3. **Dispersion: packets that spread.** Gaussian wave packets built from plane waves, animated under both dispersion relations. The electron packet spreads as σ₀√(1 + (ħt/2mσ₀²)²) and its crests slide backward through the envelope; the light packet keeps its shape.
4. **One relation, two limits.** E² = p²c² + m²c⁴ (Klein–Gordon) with an adjustable mass: p²/2m for p ≪ mc, pc for m = 0 or p ≫ mc, and why the Schrödinger equation is first order in time.
5. **Counting states in a 3D box.** A slice of n-space with equal-energy bins (rings thinning outward for the particle, equal width for the photon) and exact lattice counts compared with g(E) ∝ E^{1/2} and g(E) ∝ E² (two polarizations); E ∝ p^s gives g ∝ E^{3/s−1} and P = (s/3)u.
6. **Summary table** of the governing equation, dispersion relation, E(p), box levels, density of states, pressure, and thermal result.

Everything is in one self-contained `index.html`; MathJax and Google Fonts load from CDNs.
