### **Derivations of Equations: Light+Gravity, Mass+Light, Mass+Gravity**

#### **Light + Gravity:**

- **Length Contraction:**

  **Original**: 
  \[
  L = L_0 \sqrt{1 - \frac{v^2}{c^2}}
  \]

  **Causal Relativity**: 
  - Here, we interpret length contraction as spatial contraction due to relative motion:
    \[
    L' = L \sqrt{1 - \frac{v^2}{c^2}}
    \]

  **Problem**: Calculate the length contraction of a spaceship moving at 0.8c if its rest length is 100 meters.

  - Using \(v = 0.8c\):
    \[
    L' = 100 \sqrt{1 - \left(\frac{0.8c}{c}\right)^2} = 100 \sqrt{1 - 0.64} = 100 \times 0.6 = 60 \, \text{m}
    \]

- **Time Dilation:**

  **Original**: 
  \[
  \Delta t' = \gamma \Delta t
  \]

  **Causal Relativity**: 
  - Time dilation is reinterpreted as spatial dilation:
    \[
    \Delta L' = \Delta L \sqrt{1 - \frac{v^2}{c^2}}
    \]

  **Problem**: If a clock on a moving spaceship ticks once every second in its frame, how much spatial dilation occurs if it moves at 0.6c relative to an observer?

  - Here, \(\Delta L\) is the spatial distance the light travels in one tick in the rest frame, and \(\Delta L'\) is in the observer's frame:
    \[
    \Delta L' = \Delta L \sqrt{1 - \left(\frac{0.6c}{c}\right)^2} = \Delta L \sqrt{1 - 0.36} = \Delta L \times 0.8 = 0.8 \Delta L
    \]

- **Stretching (Cosmological Expansion):**

  **Original**: 
  \[
  ds^2 = -c^2 dt^2 + a(t)^2 \left( \frac{dr^2}{1 - k r^2} + r^2 (d\theta^2 + \sin^2\theta \, d\phi^2) \right)
  \]

  **Causal Relativity**: 
  - We consider only the spatial part for cosmological expansion:
    \[
    ds^2 = g_{ij} dx^i dx^j
    \]

  **Problem**: For a flat universe expanding uniformly where \(a(t) = t\), how does the spatial metric look?

  - In a flat universe (\(k=0\)), and considering spatial components only:
    \[
    ds^2 = t^2 \left( dr^2 + r^2 (d\theta^2 + \sin^2\theta \, d\phi^2) \right)
    \]

- **Relativity of Simultaneity:**

  **Original**: 
  \[
  x' = \gamma (x - \frac{v\Delta x}{c^2})
  \]

  **Causal Relativity**: 
  - This becomes a spatial displacement in Causal Geometry:
    \[
    x' = \gamma (x - \frac{v\Delta x}{c^2})
    \]

  **Problem**: If an event occurs at \(x = 1000 \, \text{km}\) in the rest frame and the observer is moving at \(v = 0.5c\), what's the spatial displacement in the observer's frame?

  - Using \(\gamma = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}}\):
    \[
    x' = \frac{1}{\sqrt{1 - 0.25}} \left(1000 - \frac{0.5c \times 1000}{c^2}\right) = \frac{1}{\sqrt{0.75}} \left(1000 - \frac{500}{c}\right) \approx 1.1547 \times 500 \approx 577.35 \, \text{km}
    \]

- **Gravitational Time Dilation:**

  **Original**: 
  \[
  d\tau = \sqrt{1 - \frac{2GM}{c^2 r}} \, dt
  \]

  **Causal Relativity**: 
  - Here, we convert time dilation into spatial dilation:
    \[
    \Delta L' = \Delta L \sqrt{1 - \frac{2GM}{c^2 r}}
    \]

  **Problem**: Determine the spatial dilation near a neutron star of mass \(M = 2M_{\odot}\) at a distance \(r = 10 \, \text{km}\).

  - Given \(M_{\odot} \approx 1.989 \times 10^{30} \, \text{kg}\):
    \[
    \Delta L' = \Delta L \sqrt{1 - \frac{2 \times 6.67430 \times 10^{-11} \times 2 \times 1.989 \times 10^{30}}{(3 \times 10^8)^2 \times 10^4}} \approx \Delta L \sqrt{1 - 0.59} \approx 0.64\Delta L
    \]
    
- **Gravitational Redshift:**

  **Original**: 
  \[
  z = \frac{1}{\sqrt{1 - \frac{2GM}{c^2 r}}} - 1
  \]

  **Causal Relativity**: 
  - We interpret redshift as a spatial stretching:
    \[
    \Delta L' = \Delta L \left( \frac{1}{\sqrt{1 - \frac{2GM}{c^2 r}}} \right)
    \]

  **Problem**: Calculate the spatial stretching for light emitted from the surface of a white dwarf with \(M = 0.6M_{\odot}\) and radius \(r = 5000 \, \text{km}\).

  - Using the formula:
    \[
    \Delta L' = \Delta L \left( \frac{1}{\sqrt{1 - \frac{2 \times 6.67430 \times 10^{-11} \times 0.6 \times 1.989 \times 10^{30}}{9 \times 10^{16} \times 5 \times 10^6}}} \right) \approx 1.000007 \Delta L
    \]

#### **Mass + Light:**

- **Precession:**

  **Original**: 
  \[
  \Delta \phi = \frac{6 \pi G M}{c^2 a (1 - e^2)}
  \]

  **Causal Relativity**: 
  - The equation remains unchanged as it deals with spatial deflection:
    \[
    \Delta \phi = \frac{6 \pi G M}{c^2 a (1 - e^2)}
    \]

  **Problem**: Compute the precession of Mercury's orbit per century given \(M \approx M_{\odot}\), semi-major axis \(a = 57.9 \times 10^9 \, \text{m}\), eccentricity \(e = 0.206\).

  - For Mercury, over one orbit:
    \[
    \Delta \phi \approx \frac{6 \pi \times 6.67430 \times 10^{-11} \times 1.989 \times 10^{30}}{(3 \times 10^8)^2 \times 57.9 \times 10^9 \times (1 - 0.206^2)} \approx 5.01 \times 10^{-7} \, \text{radians}
    \]
    Per century (since Mercury orbits the Sun about 415 times in 100 years):
    \[
    \Delta \phi_{\text{century}} \approx 5.01 \times 10^{-7} \times 415 \times \frac{180}{\pi} \approx 43 \, \text{arcseconds}
    \]

- **Gravitational Lensing:**

  **Original**: 
  \[
  \theta = \frac{4GM}{c^2 R}
  \]

  **Causal Relativity**: 
  - This remains the same, describing spatial bending:
    \[
    \theta = \frac{4GM}{c^2 R}
    \]

  **Problem**: Find the deflection angle for light passing close to the Sun, with \(R\) being the distance of closest approach, approximately 700,000 km.

  - Using \(M = M_{\odot}\):
    \[
    \theta = \frac{4 \times 6.67430 \times 10^{-11} \times 1.989 \times 10^{30}}{(3 \times 10^8)^2 \times 7 \times 10^8} \approx 1.75 \times 10^{-6} \, \text{radians} \approx 1.0 \, \text{arcsecond}
    \]

- **Spacetime Curvature and Geodesics:**

  **Original**: 
  \[
  \frac{d^2 x^\mu}{d\tau^2} + \Gamma^\mu_{\rho\sigma} \frac{dx^\rho}{d\tau} \frac{dx^\sigma}{d\tau} = 0
  \]

  **Causal Relativity**: 
  - In spatial terms:
    \[
    \frac{d^2 x^i}{ds^2} + \Gamma^i_{jk} \frac{dx^j}{ds} \frac{dx^k}{ds} = 0
    \]

  **Problem**: Describe the path of a light ray in the gravitational field of a Schwarzschild black hole.

  - For light, \(ds = 0\), and near the black hole:
    \[
    \frac{d^2 r}{ds^2} + \frac{1}{2r}(1 - \frac{r_s}{r})^{-1} \left(\frac{dr}{ds}\right)^2 - \frac{r_s}{2r^2} (1 - \frac{r_s}{r})^{-1} = 0
    \]
    This describes how light bends around the black hole's event horizon.

- **Frame-Dragging:**

  **Original**: 
  \[
  \Delta \theta = \frac{4GJ}{c^2 r^2}
  \]

  **Causal Relativity**: 
  - The equation is already spatial:
    \[
    \Delta \theta = \frac{4GJ}{c^2 r^2}
    \]

  **Problem**: Calculate the frame-dragging effect near a rapidly rotating neutron star with angular momentum \(J = 10^{40} \, \text{kg m}^2/\text{s}\) at \(r = 10 \, \text{km}\).

  - Using \(G \approx 6.67430 \times 10^{-11} \, \text{m}^3 \text{kg}^{-1} \text{s}^{-2}\):
    \[
    \Delta \theta = \frac{4 \times 6.67430 \times 10^{-11} \times 10^{40}}{(3 \times 10^8)^2 \times (10^4)^2} \approx 2.97 \times 10^{-15} \, \text{radians}
    \]

- **Tidal Forces:**

  **Original**: 
  \[
  F_{\text{tidal}} = \frac{2GMm}{r^3}
  \]

  **Causal Relativity**: 
  - No change, as it's a spatial interaction:
    \[
    F_{\text{tidal}} = \frac{2GMm}{r^3}
    \]

  **Problem**: Determine the tidal force on an astronaut at \(r = 100 \, \text{km}\) from a black hole with mass \(M = 10M_{\odot}\).

  - Using \(M = 10 \times 1.989 \times 10^{30} \, \text{kg}\), and assuming \(m\) is the astronaut's mass (e.g., 70 kg):
    \[
    F_{\text{tidal}} = \frac{2 \times 6.67430 \times 10^{-11} \times 10 \times 1.989 \times 10^{30} \times 70}{(10^5)^3} \approx 1.85 \times 10^6 \, \text{N}
    \]

- **Black Hole Event Horizon:**

  **Original**: N/A

  **Causal Relativity**: 
  - Spatial metric for the event horizon of a Schwarzschild black hole:
    \[
    ds^2 = \left( 1 - \frac{r_s}{r} \right) dr^2 + r^2 d\theta^2 + r^2 \sin^2\theta d\phi^2
    \]

  **Problem**: Describe the spatial metric just outside the event horizon of a black hole with \(M = 1M_{\odot}\).

  - For \(r_s = \frac{2GM}{c^2}\):
    \[
    ds^2 = \left( 1 - \frac{2 \times 6.67430 \times 10^{-11} \times 1.989 \times 10^{30}}{(3 \times 10^8)^2 \times r} \right) dr^2 + r^2 d\theta^2 + r^2 \sin^2\theta d\phi^2
    \]
    At \(r = 2r_s\), this becomes:
    \[
    ds^2 = \left( 1 - \frac{1}{2} \right) dr^2 + (2r_s)^2 d\theta^2 + (2r_s)^2 \sin^2\theta d\phi^2
    \]
    \[
    ds^2 = 0.5 dr^2 + 4r_s^2 d\theta^2 + 4r_s^2 \sin^2\theta d\phi^2
    \]

- **Stretching of Spacetime:**

  **Original**: 
  \[
  ds^2 = -c^2 dt^2 + a(t)^2 \left( \frac{dr^2}{1 - k r^2} + r^2 (d\theta^2 + \sin^2\theta \, d\phi^2) \right)
  \]

  **Causal Relativity**: 
  - Spatial metric without time:
    \[
    ds^2 = g_{ij} dx^i dx^j
    \]

  **Problem**: For an expanding universe with \(a(t) = t\) and \(k = 0\), describe the spatial metric.

  - In this case:
    \[
    ds^2 = t^2 \left( dr^2 + r^2 (d\theta^2 + \sin^2\theta \, d\phi^2) \right)
    \]

- **Energy-Momentum Tensor:**

  **Original**: 
  \[
  G_{\mu\nu} = \frac{8 \pi G}{c^4} T_{\mu\nu}
  \]

  **Causal Relativity**: 
  - Spatial stress-energy tensor:
    \[
    G_{ij} = \frac{8 \pi G}{c^4} T_{ij}
    \]

  **Problem**: If the energy density \(T_{00} = \rho\) in a given region, what's the spatial contribution to the curvature?

  - In spatial terms, we consider only the spatial components of \(T_{\mu\nu}\):
    \[
    G_{ij} \approx \frac{8 \pi G}{c^4} \rho \delta_{ij}
    \]
    Where \(\delta_{ij}\) is the Kronecker delta, assuming isotropy.

#### **Mass + Gravity:**

- **Mass-Energy Equivalence:**

  **Original**: 
  \[
  E = mc^2
  \]

  **Causal Relativity**: 
  - Remains the same, interpreted as spatial energy density:
    \[
    E = mc^2
    \]

  **Problem**: What's the energy equivalent of 1 kg of mass?

  - Using \(c = 3 \times 10^8 \, \text{m/s}\):
    \[
    E = 1 \times (3 \times 10^8)^2 = 9 \times 10^{16} \, \text{J}
    \]

- **Relativistic Mass:**

  **Original**: 
  \[
  m' = \frac{m}{\sqrt{1 - \frac{v^2}{c^2}}}
  \]

  **Causal Relativity**: 
  - Here, we interpret it as spatial mass increase:
    \[
    m' = \frac{m}{\sqrt{1 - \frac{v^2}{c^2}}}
    \]

  **Problem**: Calculate the relativistic mass of an object moving at 0.9c if its rest mass is 1 kg.

  - Using \(v = 0.9c\):
    \[
    m' = \frac{1}{\sqrt{1 - (0.9)^2}} = \frac{1}{\sqrt{0.19}} \approx 2.29 \, \text{kg}
    \]

- **Time Dilation:**

  **Original**: 
  \[
  \Delta t' = \gamma \Delta t
  \]

  **Causal Relativity**: 
  - Converts to spatial dilation:
    \[
    \Delta L' = \Delta L \sqrt{1 - \frac{v^2}{c^2}}
    \]

  **Problem**: If a meter stick moves at 0.7c, how long does it appear in the direction of motion?

  - Using the spatial dilation formula:
    \[
    \Delta L' = 1 \, \text{m} \sqrt{1 - (0.7)^2} = 1 \times \sqrt{0.51} \approx 0.71 \, \text{m}
    \]

- **Energy of Light in Gravitational Field:**

  **Original**: 
  \[
  E_{\text{out}} = E_{\text{in}} \left( \frac{r_s}{r} \right)
  \]

  **Causal Relativity**: 
  - Adjusts energy in spatial terms:
    \[
    E_{\text{out}} = E_{\text{in}} \left( \frac{r_s}{r} \right)
    \]

  **Problem**: Calculate the energy of a photon once it has escaped from just above the event horizon of a black hole with \(M = 5M_{\odot}\) if its energy at the event horizon was 1 J.

  - \(r_s = \frac{2 \times 6.67430 \times 10^{-11} \times 5 \times 1.989 \times 10^{30}}{(3 \times
