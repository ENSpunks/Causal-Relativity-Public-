# Causal Shell Boundary and Grid Distortion

## Status

Foundational research hypothesis / empirical benchmark.

This document develops a measurable geometric representation of the Causal Relativity idea that relative velocity is represented by distortion of causal grids while the measured object remains at rest in its intrinsic frame.

The purpose is not to assume special-relativistic formulas, but to identify the physical quantities that a future derivation must reproduce.

---

## 1. Shell boundaries

Represent a finite causal propagation element by an inner and outer boundary:

\[
r_{\mathrm{out}}(\hat{\mathbf n},\sigma),
\qquad
r_{\mathrm{in}}(\hat{\mathbf n},\sigma).
\]

Define its radial boundary separation (shell thickness) as

\[
\boxed{\Delta r(\hat{\mathbf n},\sigma)=r_{\mathrm{out}}-r_{\mathrm{in}}.}
\]

For either causal grid,

\[
\Delta r_G,
\qquad
\Delta r_L
\]

are allowed to be distinct because the gravity and light grids carry different information and obey different interaction rules.

A useful dimensionless distortion observable is

\[
\boxed{D_i(\hat{\mathbf n},v)=\frac{\Delta r_i(\hat{\mathbf n},v)}{\Delta r_{i,0}}},
\qquad i\in\{G,L\},
\]

where \(D_i=1\) denotes the reference configuration.

---

## 2. Two different meanings of boundary separation

A critical distinction is required before identifying shell thickness with wavelength.

A finite wave packet has a leading/trailing envelope separation. That is a packet width and is not generally equal to wavelength.

For a periodic light field, wavelength is instead the spatial separation between equivalent phase surfaces (for example successive crests):

\[
\lambda=\Delta r_{\mathrm{phase}}.
\]

Therefore Causal Relativity should retain two possible observables:

\[
\Delta r_{\mathrm{packet}}
\]

for the physical thickness of a finite causal packet, and

\[
\boxed{\Delta r_{\mathrm{phase}}=\lambda}
\]

for the spacing of repeating light-grid phase structure.

This prevents the theory from incorrectly identifying a wave packet's physical width with its wavelength.

---

## 3. Intrinsic-frame condition

The measured source remains at rest in its own intrinsic frame:

\[
\mathbf{x}_M=0,
\qquad
v_{M/M}=0.
\]

Relative velocity is therefore represented by the relationship between causal grids and another frame:

\[
G\rightarrow G_v,
\qquad
L\rightarrow L_v.
\]

The invariant propagation condition remains

\[
\left|\frac{d\mathbf r_G}{d\sigma}\right|=c,
\qquad
\left|\frac{d\mathbf r_L}{d\sigma}\right|=c.
\]

The proposed distortion therefore changes the spatial organization of the causal structure, not the intrinsic propagation speed.

---

## 4. Light-grid benchmark: relativistic Doppler effect

For the light grid, the experimentally established benchmark is relativistic Doppler shifting.

If an observer moves relative to a light wave, the observed frequency changes while the locally measured propagation speed remains \(c\). For longitudinal motion, the standard relativistic result can be written

\[
\omega'=\gamma(1-\beta\cos\theta)\omega,
\]

where

\[
\beta=\frac{v}{c},
\qquad
\gamma=\frac{1}{\sqrt{1-\beta^2}}.
\]

For a photon propagating in the same direction as the observer's velocity (\(\cos\theta=1\)):

\[
\omega'=\gamma(1-\beta)\omega
=\sqrt{\frac{1-\beta}{1+\beta}}\,\omega.
\]

Since \(\lambda=c/f\), the corresponding wavelength is

\[
\boxed{
\lambda'=\lambda\sqrt{\frac{1+\beta}{1-\beta}}
}
\]

for an observer chasing a photon propagating in the same direction.

For the opposing propagation direction (\(\cos\theta=-1\)):

\[
\omega'=\gamma(1+\beta)\omega
=\sqrt{\frac{1+\beta}{1-\beta}}\,\omega,
\]

and therefore

\[
\boxed{
\lambda'=\lambda\sqrt{\frac{1-\beta}{1+\beta}}
}.
\]

Thus the proposed causal-grid picture has a real physical benchmark: relative motion produces direction-dependent spatial phase separation while the propagation speed remains \(c\).

These equations are **not being adopted as axioms of Causal Relativity**. They are the target that a causal-shell derivation must recover.

---

## 5. Important correction: velocity versus acceleration

The persistent directional distortion is associated with relative velocity, not acceleration by itself.

If Alice accelerates, her instantaneous velocity \(v(\sigma)\) changes. Consequently the measured light-grid distortion changes from shell to shell:

\[
D_L(\hat{\mathbf n},\sigma)
=
D_L[\hat{\mathbf n},v(\sigma)].
\]

A changing velocity therefore produces a changing wavelength/frequency pattern (a relativistic chirp) for signals emitted or received during the acceleration.

Acceleration is thus naturally represented as a **change in the grid-distortion state**, rather than as a new propagation speed.

---

## 6. The direction of the wavelength change matters

If Alice moves to the right and light propagates to the right, Alice is chasing the light and the observed wavelength is longer.

If Alice moves to the right while light propagates to the left, Alice moves toward the incoming light and the observed wavelength is shorter.

Therefore the theory should not state simply that "motion compresses the forward grid." The correct statement is directional:

\[
\boxed{
\text{relative velocity produces an angularly dependent causal-grid distortion.}
}
\]

The sign depends on the relative orientation of the velocity and causal propagation direction.

---

## 7. Candidate light-grid distortion field

A useful target representation is

\[
\boxed{
D_L(\hat{\mathbf n},v)
=
\frac{\lambda(\hat{\mathbf n},v)}{\lambda_0}
}
\]

with the special-relativistic benchmark

\[
\boxed{
D_L(\hat{\mathbf n},v)
=
\frac{1}{\gamma(1-\beta\cos\theta)}
}
\]

when the wavelength is defined through phase-front separation in the moving observer's frame.

The Causal Relativity task is to derive an equivalent expression from causal-shell geometry without inserting the Lorentz transformation as a starting assumption.

---

## 8. Gravity-grid analogue

The gravity grid should not be assigned a wavelength merely for symmetry with light.

Instead, define its shell state using at least two quantities:

\[
G_i=\left(\Delta r_G,\,S_G,\,I_G\right),
\]

where

- \(\Delta r_G\) = causal boundary separation or spatial extent of the gravitational update;
- \(S_G\) = gravitational state/strength variable to be derived;
- \(I_G\) = source-state information carried by the shell.

A gravity shell may therefore possess a measurable spatial extent without possessing a wavelength.

The corresponding velocity distortion can be represented provisionally as

\[
D_G(\hat{\mathbf n},v)
=
\frac{\Delta r_G(\hat{\mathbf n},v)}{\Delta r_{G,0}}.
\]

No functional form for \(D_G\) should be assumed yet.

---

## 9. Potential connection to gravitational retardation

The shell interpretation suggests that a gravitational field at radius \(r\) may encode source information associated with an earlier causal state. Schematically,

\[
G(r)=\mathcal G[M(\sigma_r)],
\qquad
\sigma_r\sim\frac{r}{c}
\]

in the simplest undistorted model.

However, this must not be interpreted as saying that the static Newtonian gravitational field is literally a collection of ordinary outward-moving shells. General relativity describes gravity through spacetime geometry, and gravitational radiation has its own field-theoretic structure.

The Causal Relativity hypothesis must therefore demonstrate how the proposed gravity grid maps onto the metric field and, in dynamical situations, onto gravitational radiation.

---

## 10. Minimum derivation target

The next mathematical problem is now sharply defined.

Start with an intrinsic causal cell or phase interval satisfying

\[
\Delta r_0=c\,\Delta\sigma_0.
\]

Define how a relative-frame transformation changes the boundary separation while preserving the causal propagation condition

\[
|d\mathbf r/d\sigma|=c.
\]

Then determine whether the required directional distortion can be derived as

\[
D_L(\hat{\mathbf n},v)
=
\frac{1}{\gamma(1-\beta\cos\theta)}
\]

or whether a different law follows.

The derivation must not assume the Lorentz transformation merely by rewriting it in shell notation.

---

## 11. Falsifiability

The shell-boundary formulation becomes scientifically useful only if it produces measurable predictions.

At minimum, the theory should reproduce:

1. invariant local light speed \(c\);
2. longitudinal relativistic Doppler shift;
3. transverse Doppler shift;
4. aberration of light;
5. reciprocity between inertial frames;
6. the appropriate low-velocity limit;
7. gravitational redshift and light bending once the gravity grid is coupled to geometry.

If the causal-grid equations fail any established benchmark, the proposed distortion law must be revised rather than the observation being reinterpreted.

---

## 12. Working interpretation

The strongest current formulation is therefore:

> **Relative velocity does not require the measured mass to move through its own intrinsic frame. It can instead be represented as an angularly dependent distortion of the causal structures used to relate that mass to another frame. For the light grid, this distortion is observable through changes in phase-front spacing (wavelength) and frequency while the propagation speed remains \(c\). The gravity grid should possess an analogous spatial/state distortion, but not necessarily a wavelength.**

This is a hypothesis to be derived and tested, not an established physical result.
