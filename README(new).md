# Theory of Causal Relativity

**Will Brown**  
January 20, 2025

---

## Abstract

The Theory of Causal Relativity is a parallel geometric framework that replaces the temporal coordinate of standard physics with self-referential spatial radial coordinates. Every mass continuously emits light and gravity shells that expand at \(c\). Each shell permanently records the mass, energy, and size that existed at the moment of its emission. These expanding shells supply an intrinsic fourth spatial dimension. All standard equations of classical mechanics, special relativity, general relativity, electromagnetism, thermodynamics, and quantum mechanics are recovered by re-expressing them in these radial coordinates.

---

## Core Definition (the single idea that makes the framework intelligible)

Every mass continuously emits radial light and gravity shells that expand at the speed of light.  
Each shell is permanently stamped with the mass, energy, and size present when it left the source.  

At any later radius \(r\) the gravitational field is simply the value carried by the shell that has now reached \(r\):

\[
K(r) = \frac{G\, M(r_{\rm emission})}{r^{2}}
\]

No second mass is required. The grid itself is both the source and the record of the field.  
This construction supplies the fourth spatial coordinate and makes the \(n=1\) (single-mass) universe measurable.

---

## Postulates

**Newton’s postulates**  
1. Space and time are absolute and separate.  
2. Gravity acts instantaneously.  
3. Light speed varies with the observer.

**Einstein’s postulates**  
1. The laws of physics are the same in all inertial frames.  
2. The speed of light is constant.  
3. Space and time form a four-dimensional spacetime.

**Causal Relativity postulates**  
1. The laws of physics are independent of any external time coordinate.  
2. Frames are relative to all other frames.  
3. Frames are relative to themselves (self-referential radial grids).

---

## The \(n=1\) Universe – Why the Framework Is Needed

In ordinary physics a single isolated mass has no measurable gravitational force, because Newton’s and Einstein’s equations are relational: they require a second mass or a test particle.  

Causal Relativity answers the question “can a fire cast its own shadow?” by letting the mass’s own expanding light-and-gravity grid serve as the probe. The radial coordinate of each shell carries the gravitational information that would otherwise be undefined.

---

## Causal Relativity Equations

All equations below are the standard results of physics rewritten so that the time coordinate is replaced by the self-referential radial coordinate \(r\). The numerical predictions remain identical; only the geometric interpretation changes.

### Mass
| Phenomenon | Original | Causal Relativity |
|------------|----------|-------------------|
| Newton’s gravitational force | \(F = Gm_1m_2/r^2\) | \(K(r) = GM(r_{\rm emission})/r^2\) |
| Gravitational curvature (GR) | Einstein field equation | \(K(r) = GM(r_{\rm emission})/r^2\) |

### Light
| Phenomenon | Original | Causal Relativity |
|------------|----------|-------------------|
| Faraday’s law | \(\nabla\times\mathbf{E}=-\partial\mathbf{B}/\partial t\) | \(\nabla\times\mathbf{E}=-\kappa\nabla\cdot\mathbf{B}\) |
| Ampère–Maxwell law | \(\nabla\times\mathbf{B}=\mu_0\mathbf{J}+\mu_0\epsilon_0\partial\mathbf{E}/\partial t\) | \(\nabla\times\mathbf{B}=\mu_0\mathbf{J}+\mu_0\epsilon_0\kappa\nabla\cdot\mathbf{E}\) |
| Wave equation | \(\nabla^2\mathbf{E}-(1/c^2)\partial^2\mathbf{E}/\partial t^2=0\) | \((1-\kappa^2)\nabla^2\mathbf{E}=0\) |

### Light + Gravity (Special & General Relativity)
| Phenomenon | Original | Causal Relativity |
|------------|----------|-------------------|
| Length contraction | \(L=L_0\sqrt{1-v^2/c^2}\) | \(L'=L\sqrt{1-v^2/c^2}\) |
| Time dilation → spatial dilation | \(\Delta t'=\gamma\Delta t\) | \(\Delta L'=\Delta L\sqrt{1-v^2/c^2}\) |
| Relativity of simultaneity | Lorentz transformation in \(t\) | Intersection of radial shells: \(C_A(r)=C_B(r)\) |
| Gravitational redshift | \(z=(1-2GM/c^2r)^{-1/2}-1\) | \(\Delta L'=\Delta L(1-2GM/c^2r)^{-1/2}\) |

### Black-Hole Entropy (example of a possible extension)
\[
S_{\rm BH,causal}=\frac{A}{4\ell_P^2}\left(1+\frac{\Delta A}{A}\right)
\]
The correction term \(\Delta A\) is proposed to arise from the finite thickness of the radial shells at the horizon; its derivation from the grid dynamics remains an open calculation.

---

## Status of the Framework

- **Consistency**: In flat space and in the weak-field limit the radial-coordinate description recovers every standard result of special and general relativity (simultaneity, Doppler shift, length contraction, etc.).
- **Novelty**: The framework supplies an operational meaning for gravity in a true \(n=1\) universe and offers a purely spatial language for the same physics.
- **Open questions**: Whether the self-curvature of the grids produces measurable deviations inside black holes, in the early universe, or at the Planck scale has not yet been demonstrated.

---

## Repository Structure

- `Papers/Causal Relativity/` – foundational papers and the black-hole / Big-Bang discussions  
- `Papers/Special Relativity/` – spatial re-derivations of the classic SR effects  
- `Papers/General Relativity/` – spatial re-derivations of the classic GR effects  
- `Papers/Causal Relativity/Maths/Calculations/` – explicit numerical checks (simultaneity, twin paradox, lensing, \ldots)  
- `Derivations/` – step-by-step rewrites of individual equations  
- `Causal Sphere Diagrams/` – visual illustrations of the radial grids  

---

## How to Read This Work

1. Begin with the **Core Definition** above.  
2. Examine the \(n=1\) argument – it is the conceptual heart of the theory.  
3. Verify that the radial-coordinate versions of the classic equations reproduce the known numerical results.  
4. Only then consider the speculative extensions (singularity resolution, modified entropy, etc.).

The framework is offered as a coherent parallel geometry, not as a claim of new experimental predictions—unless and until the self-referential grids are shown to deviate from standard general relativity in a measurable regime.
