---
title: Elliptical Galaxies, Dwarfs, and Scaling Relations
---

# Elliptical Galaxies, Dwarfs, and Scaling Relations

[i=M87-elliptical-Virgo-Cluster.jpg]

---
[contents]
---
[P "Morphological Classification of Ellipticals"]

<!--
triaxial spheroid = sausage/disc/sphere; denser cores
## Observed shape
- $10\times(1-\frac{1}{b})$
- E0 = round 
- Typical maximum of E7
-->

- **Hubble Ellipticity Index ($E0 \text{--} E7$):** Classified by apparent major ($a$) and minor ($b$) axis ratios: [+]
  $$E = 10 \left(1 - \frac{b}{a}\right)$$ [+]
- **Flattened Systems ($E4 \text{--} E8$ / $S0$):** High ellipticity often indicates edge-on fast-rotating disks or lenticular galaxies without visible arms. [+]
- **Compact Ellipticals ($cE$):** Small, dense, high-surface-brightness systems (e.g., M32); formed primarily as tidal remnants stripped by a massive neighbor. [+]
- **Central Dominant Galaxies ($cD$):** Supergiant ellipticals surrounded by vast, faint, extended stellar envelopes. Usually found at the centers of rich clusters. [+]

---

[P "Intrinsic 3D Shapes & Kinematic Support"]

<!--[i="image_agent_tag_783226219513890030"]-->

- **De-projecting Ellipticity:** Apparent 2D shape depends on intrinsic 3D semi-axes ($a \ge b \ge c$) and inclination. [+]
- **The Ellipsoidal Families:** [+]
  * **Oblate (Disc-like):** $a = b > c$ (flattened along the axis of rotation). [+]
  * **Prolate (Sausage-like):** $a > b = c$ (elongated along the major axis). [+]
  * **Triaxial (General):** $a > b > c$ (three distinct principal axes; orbits can be non-planar). [+]

-v-

## Kinematics:
- Stars in a gravity well have some balance of:
  - Coherent **rotational velocity** ($V_{\rm rot}$) - from the difference in mean doppler shift across the galaxy
  - Random **anisotropic stellar "pressure"** ($\sigma$) - from the broadening in individual absorption lines (corrected for instrumental broadening)
- The $V/\sigma$ ratio is a key divider between disc-like and elliptical galaxies. 
  - Faint/low-mass ellipticals are isotropic oblate rotators ($V/\sigma > 1$)
  - Giant ellipticals are slow-rotating, pressure-supported systems ($V/\sigma \ll 1$), often with triaxial shapes. [+]

---
[P "Other Features of Ellipticals"]

- **Stellar populations**
  - Dominated by Population II stars[+]
  - Very little gas between stars[+]
  - Very low star formation rates[+]
- **Supermassive Black Holes**[+]
  - Most (all?) ellipticals host a large central black hole (some with jets)[+]
- **Globular Clusters** (dense/old stellar clusters):[+]
  - Nearby ellipticals like M87 show 100x that of the Milky Way[+]

<!--# 1) Elliptical morphology
## E4-E7 or S0?
- Highly elongated ellipticals... may not be elliptical.
- They are instead lenticular galaxies viewed edge-on-->
---

[P "Galaxy Demographics & Locations"]

[i=Galaxy_mass_function.png]

- By **Number Density ($\Phi$)**: Late-type spirals (Sab–Sd) and dwarf/irregular galaxies (Sd–Irr, dE) dominate counts.[+]
-v-
- By **Stellar Mass Budget ($\rho_*$)**: Spheroid-dominated elliptical galaxies hold the majority of mass ($\sim 71\%$ of total stellar mass resides in Es + S0/Sas).[+]
- When split only by bulge- vs disc-dominated (i.e. ellipticals & bulge-dominated lenticulars vs spirals), the nearby universe shows a ~50/50 split by mass[+]
- Best statistics from [GAMA](https://arxiv.org/abs/1407.7555) survey.

-v-

<!--[i="image_agent_tag_783226219513890192"]-->
- The local density of galaxies can vary from sparse environments to large superclusters.
- **The Morphology-Density Relation (Dressler 1980):** Spiral galaxies dominate low-density field environments; $S0$ and $E$ galaxies dominate densest regions of clusters (80-90%). [+]
- **$cD$ Galaxies at Potential Well Minima:** Located at the exact gravitational centers of massive clusters (e.g., M87 in Virgo, ESO 137-001). [+]
- **Galactic Cannibalism & Intracluster Light (ICL):** $cD$ envelopes grow by accreting smaller cluster members; tidal disruption scatters stars into the extended ICL halo. [+]
<!--## Other galaxies
- Dwarf Ellipticals (dEs)
- cE (compact elliptical e.g. M32)
- S0, ES (intermediate discs) and E
- cD (central diffuse)
- gE - giant ellipticals-->


---

[P "The Low-Mass Zoo: Dwarf Galaxies"]

[i=Dwarf_Galaxies_examples.png]

-v-

- **Dwarf Ellipticals ($dE$) & Spheroidals ($dSph$):** Gas-poor, smooth stellar distributions ($M_V > -18$). $dSph$ systems are extreme, low-surface-brightness extensions ($M_V > -14$). [+]
- **Ultra-Faint Dwarfs ($UFDs$):** The faintest, most dark-matter-dominated systems known ($L \sim 10^2\text{--}10^5 L_\odot$, $M/L > 100\text{--}1000$). [+]
- **Ultra-Diffuse Galaxies ($UDGs$):** Dwarf-like stellar mass ($10^7\text{--}10^8 M_\odot$) expanded over a Milky Way-sized spatial radius ($R_e \ge 1.5\text{ kpc}$). [+]
- **Dwarf Irregulars ($dIrr$):** Gas-rich, actively star-forming dwarfs with irregular morphologies and low metallicities. [+]

---
[P "Scaling relations (basics)"]

- The many properties of galaxies (size, mass, rotational speed/velocity dispersion, luminosity, etc) are not infinitely variable.[+]
- Instead there exists underlying physics which produces strong correlations between parameters.[+]
- These are modelled via "scaling relations"[+]
- For example, one scaling relation is a constant **mass-to-light ratio** (i.e. $M \propto L$)[+]
- This is understandable as higher stellar mass must produce higher luminosities.[+]

-v-

### Red Sequence

[i=color_magnitude_plot.png]

- Ellipticals show a clear relationship between total mass & colour

---

[P "Scaling relations (velocities)"]

### Tully-Fisher

[i=tully_fisher.jpg]

- In spiral galaxies, rotational velocity correlates strongly with luminosity: $L \propto \nu^\alpha_{\rm max}$, where $\alpha \approx 4$ in spirals

<!-- Connects total optical/IR luminosity (or baryonic mass) to maximum disk rotation speed ($V_{\text{max}}$):- $$L \propto V_{\text{max}}^{\alpha} \quad (\alpha \approx 3\text{--}4)$$-->
-v-
### Tully-Fisher
- Tully & Fisher (1977) realised that total optical/IR luminosity (or baryonic mass) to maximum disk rotation speed
- Assuming constant mass-to-light ratio ($M = cL$), rotational velocity defined as $\nu_{\rm max} = \sqrt{GM/R}$, and mean surface brightness $\mu = L/R^2$, what should alpha be?
- $R^2 = G^2M^2/\nu^4_{\rm max}; hance R^2 = cG^2L^2/\nu^4_{\rm max}$
- So $L = \langle I_e \rangle R^2$; $L = \langle I_e \rangle cG^2L^2/\nu^4_{\rm max}$; $L = \nu^4_{\rm max}/(cG^2\langle I_e \rangle)$
- As $c$ (mass-to-light proportionality) and $\langle I_e \rangle$ (surface brightness ratio) can be assumed constant for all spirals, $L \propto \nu^4_{\rm max}$.

-v-

## Faber-Jackson

[i=Tully_Fischer.png]

- In **elliptical galaxies**, faster velocity _dispersions_ in their cores (\sigma_0) correlate with higher luminosities: $L \propto \sigma_0^\gamma \quad (\gamma \approx 4)$
- This can similarly be derived from expected velocities due to galaxy masses.

-v-
## Physical Basis

- As with Tully-Fisher, Faber-Jackson can be derived by combining:
  - The **virial theorem** - e.g. using equilibrium in gravitational potential ($G M / R \propto V^2$); and[+]
  - A constant (or slowly varying) stellar mass-to-light ratio ($M/L$)[+]
  <!-- Potential energy from point masses inside radius R is $U = -\frac{3}{5}\frac{GM^2}{R}$
  - Kinetic Energy is $K = 3/2 M \sigma^2$
  - Must be balanced, e.g. $2K+U = 0$; hence $\sigma^2 = -\frac{1}{5}\frac{GM}{R}$
  -->
---

[P "Scaling velocities (fundamental plane)"]

- The brightness profiles of ellipticals  makes calculating the _total flux_ difficult
- It is easier to compute the effective radius, $R_e$, where 50% surface brightness is reached.
- Unlike spiral galaxies, the surface brightness of ellipticals varies substantially with galactic luminosity: $L \propto \langle I_e \rangle_e^{-0.66}$ - larger ellipticals have lower surface brightnesses.
- Using both surface brightnesses ($\langle I_e \rangle_e$) and velocity disperson ($\sigma_0$) corrects for this change: $R_e \propto \sigma_0^{1.4} \langle I_e \rangle_e^{-0.85}$.
- In logarithmic quantities $\log_{10} R_e = a \log_{10} \sigma_0 + b \log_{10} \langle I_e \rangle + c$ where $a \approx 1.2\text{--}1.4$, $b \approx -0.85\text{--}-0.90$)[+]

-v-

## Fundamental plane

[i=mFP_vp_rotate.gif]

- This can be thought of a third dimension to the Faber-Jackson and is a _better predictor_ of galaxy size/luminosity

-v-
### Understanding the "Tilt":
- Pure Virial Theorem ($M \propto R_e \sigma_0^2$) predicts $a = 2.0, b = -1.0$.
- The discrepancy ("tilt") reflects systematic variations in $M/L$:
  - $M/L$ of ellipticals increases with galaxy stellar mass. [+]

<!--
## Scaling relations
- Scaling relations can now be inverted to produce the expected luminosity given other measurements
- This then produces a distance estimate (distance modulus), independent to Hubble's law!-->

---
[P "Scaling Relations (Mass-Size)"]

- **Mass-Size Scaling ($M_* \text{--} R_e$):** Displays a structural regime shift around $M_* \sim 3 \times 10^{10} M_\odot$: [+]
  * **Low-Mass Spheroids ($M_* < 10^{10.5} M_\odot$):** Shallow size growth ($R_e \propto M_*^{0.1\text{--}0.2}$). [+]
  * **Massive Ellipticals ($M_* > 10^{11} M_\odot$):** Steep size expansion ($R_e \propto M_*^{0.6\text{--}0.8}$). [+]
- **Sérsic Index Scaling ($n \text{--} L$):** Central concentration (Sérsic index $n$) scales smoothly with total luminosity ($L \propto n^3$), unifying faint dwarf ellipticals and giant ellipticals within a single structural framework. [+]

---
[P "Impact of scaling relations"]

#### Standard candles
- Relations between parameters enable us to convert one observed parameter into another[+]
  - e.g. velocity disperson $\sigma$ to mass (and therefore to intrinsic luminosity).[+]
  - This can anchor a standard candle (e.g. for distance, and even $H_0$ determination)[+]
#### Unresolved galaxies[+]
- Enable us to apply information derived from resolved calaxies to distant galaxies without any spatial (e.g. $V$ or $\langle I_e \rangle$) information[+]
#### Probe underlying physics[+]
- For example, deviations of observed scaling laws from expectations as proof of unseen physics (Fundamental plane "tilt" due to increasing dark matter mass fraction in massive galaxies)[+]

-v-
### Next time

Turn these observed properties of galaxiesm into understand how (and when) galaxies and stellar populations form...
