### Gravitational Casmir effect / James Q. Quach

- Derive the gravitatonic Casmir effect with non-idealised boundary conditions.
  - This allows the quantification of the gravitonic contribution to the Casmir effect from real bodies.
- Quantify the meagreness of the gravitonic Casmir effect in ordinary matter.
- Quantify the enhanced effect produced by the speculated *Heisenberg-Coulomb* (H-C) effect in superconductors.
  - Providing a test for the validity of the H-C theory, and consequently the existence of gravitons.



#### Introduction

QFT predicts non-zero vacuum energy leads to the Casmir effect.

- Basically, the Casmir effect is the attraction between two perfectly reflecting surfaces as a result of the restriction of allowed modes in the vacuum between them.
- Real bodies however are not perfectly reflecting.
  - The generalisation of these ideal boundary conditions to more realistic ones
    have been derived for the electromagnetic (EM) field
    - Resulting in the Lifshitz formula at zero temperature [1]
- The EM field is not the only field that produces the Casimir effect
  - In theory all fields of the quantum vacuum contribute to the Casimir effect
  - The contribution to the Casimir effect from any massless field which is opaque to the plates should be significant (mass quickly weakens the Casimir effect [2]).
  - Therefore one may imagine plates which are opaque to the gravitational field, 
    - So that the Casimir effect would then be a manifestation of the quantisation of the gravitational field, or gravitons.
  - The difficulty is in finding such a medium, as ordinarily materials are transparent to the gravitational field [3].



Recently however, there have been suggestions that the properties of *quantum fluids* (superconductors, superfluids, quantum Hall fluids, Bose-Einstein condensates) may **enhance the interaction** with gravitational waves (GW).

- The novel effects of the interaction of a gravitational field with a quantum fluid was first investigated by DeWitt [4] and Papini [5], who calculated that a Lense-Thirring field should induce a current in the superconductor.
- further analyses were made into the interaction of GW with superconductors [6, 7], proposing superfluids as a medium for gravitational antennae [8], superconducting circuits as GW detectors [9], transducers [10, 11] and mirrors [12].
  - These idea have not been met without controversy [13, 14].
  - Although a few experiments have attempted to test the proposed enhanced GW interaction [15, 16], none have produced clear and unambiguous outcomes.
    - This is perhaps because of the small magnitude of some of the theorised effects 
    - coupled with the practical challenges in producing the environment capable of their detection [16].
  - In light of the controversial status of enhanced gravitational interaction, an understanding of the gravitonic Casimir effect for realistic bodies is needed to 
    - accurately quantify the contribution in ordinary materials and in any theorised system with enhanced gravitational interactions.

The Casimir effect has also been investigated in weak gravitational fields to see the effect the slightly curved spacetime background would have on the Casimir energy [17].

- In these works, the gravitational field is assumed to be unaffected by the matter that form the boundary conditions.
  - This is different from what we are considering here, where we look at how the **gravitational field of the vacuum interacts with the matter of the boundary conditions** to give rise to the gravitonic Casimir effect, in flat spacetime.
- This gravitonic Casimir effect has been considered in a cosmological context;
  - however in these works, the boundary conditions are idealised and not suitable for realistic terrestrial systems [18].
- The gravitonic Casimir potential also has been calculated for a massive test point particle interacting with a fluctuating mass distribution [19].
- In this letter we derive **the gravitonic Casimir effect for real bodies**.
  - In effect we give the Lifshitz formula for the gravitonic contribution to the Casimir effect at zero temperature.



![image-20190612151547179](/Users/xmoonight/Desktop/Notes/Thoughts/Gravitational_Casmir_effeft/image-20190612151547179.png)

> FIG. 1. The Casimir effect with a two plate setup. The change in the refractive index of the plates causes the gravitational wave to refract. $\mathbf{k}$ represents the wave vector of the incident, transmitted, and reflected gravitational waves, and $\gamma$ is the corresponding angle with respect to the surface normal.

#### Theory

- The linearised Einstein field equations: describe the contribution of small perturbations to the flat spacetime metric $\eta_{\mu\nu}$.

- We begin with a Maxwell-like formulation of the linearised Einstein field equations
  known as *gravitoelectromagnetism* (GEM) [20,21],
  $$
  \begin{array}{c}{\nabla \cdot \mathbf{E}=\kappa \boldsymbol{\rho}^{(E)}} \\ {\nabla \cdot \mathbf{B}=\kappa \boldsymbol{\rho}^{(M)}} \\ {\nabla \times \mathbf{E}=-\frac{\partial \mathbf{B}}{\partial t}-\kappa \mathbf{J}^{(M)}} \\ {\nabla \times \mathbf{B}=\frac{\partial \mathbf{E}}{\partial t}+\kappa \mathbf{J}^{(E)}}\end{array}
  \tag{1 - 4}
  $$
  where $\kappa\equiv 8\pi G/c^4$.

- In this formulation, components of the Weyl tensor ($C_{\alpha\beta\mu\nu}$) play roles analogous to the electric and magnetic fields in electromagnetism:

  - $E_{ij} \equiv C_{0i0j}$ and $B_{ij}\equiv \star C_{0i0j}$ , ($\star$ denotes Hodge dualisation [22]). 
  - The *rhs* of the GEM equations contain components of the matter current, 
    - $J_{\mu \nu \rho} \equiv-T_{\rho[\mu, \nu]}+\frac{1}{3} \eta_{\rho[\mu} T_{, \nu ]}$ where $T_{\mu \nu}\left(T \equiv T_{\mu}^{\mu}\right)$ are the stresses due to the perturbation: $\rho_{i}^{(E)} \equiv-J_{i 00}$, $\rho_{i}^{(M)} \equiv-\star J_{i 00}$, $J_{i j}^{(E)} \equiv J_{i 0 j}$, and $J_{i j}^{(M)} \equiv \star J_{i 0 j}$
      - (we use the convention that Greek letters go from 0 to 3 and Roman letters go from 1 to 3, unless otherwise stated).

  We are interested in the **macroscopic properties** of the system, so $\mathbf{E}, \mathbf{B}, \mathbf{T}$ will represent Russakoff spatial averaged values [23], as is used in the macroscopic Maxwell’s equations.

  - We assume that $T_{i j}=\chi(\omega) E_{i j}$, where $\chi(\omega)$ is the frequency dependent *gravitational susceptibility* [24];

  - we will later show a specific model of matter where the induced stresses are of this form.

  - We consider the gravitoelectromagnetic fields to be of plane wave form,
    $$
    E_{i j}(\mathbf{r}, t)=\mathcal{E}_{i j} e^{i(\mathbf{k} \cdot \mathbf{r}-\omega t)}, B_{i j}(\mathbf{r}, t)=\mathcal{B}_{i j} e^{i(\mathbf{k} \cdot \mathbf{r}-\omega t)}.
    $$

    - From the GEM equations, $\mathbf{E}$ and $\mathbf{B}$ are transverse waves with two independent polarisations, ‘$+$’ and ‘$\times$’, 
    - respectively defined by the only non-vanishing components $\mathcal{E}_{11}-\mathcal{E}_{22}=\mathcal{B}_{12}=\mathcal{B}_{21}=\alpha$ and $-\mathcal{B}_{11}=\mathcal{B}_{22}=\mathcal{E}_{12}=\mathcal{E}_{21}=\beta$  in the proper frame of the plane wave.
    - Here we define the proper frame of the plane wave as that in which $\mathbf{k}$ is
      along the positive $z$-axis.

  - The vacuum energy of any quantum field between parallel plates (separated by distance $a$) is a summation of the energy of all allowed modes of the field.

  - The opaque boundary of the parallel plates in the $xy$-plane means that the $k_z$ components of the field are discrete, whereas the $\mathbf{k}_{ \|} \equiv\left(k_{x}, k_{y}\right)$ components remain continuous.

  - In terms of the graviton eigenfrequencies, the vacuum energy of gravitons between the plates at zero temperature is given by [25],
    $$
    E_{0}=\frac{\hbar}{4 \pi} \int_{0}^{\infty} k_{ \|} d k_{ \|} \sum_{n}\left(\omega_{n}^{+}+\omega_{n}^{ \times}\right) \sigma
    \tag{5}
    $$

    - where $\sigma$ is the surface area of the plate.
    - The allowed modes $\left(\omega_{n}^{+}, \omega_{n}^{ \times}\right)$ between the plates are found by considering the boundary conditions, as follows.

  

- A naive application of Stokes’ theorem to the $\mathbf{E}$ and $\mathbf{B}$ fields at the plate interface will produce an overdetermined problem. 

  - The reason for this is that the extra components of these second-order tensors would introduce extra constraints, as compared to vector fields, such as the EM field.

  - Thus $\mathbf{E}$ and $\mathbf{B}$ cannot be considered completely smooth across the interface.

  - Instead only the traceless part of the tangential components of the tensor
    fields are considered smooth across the interface

    - this is known as the *smoothness principle*.

    - This gives rise to the boundary conditions,
      $$
      \begin{array}{c}{\Delta\left[(1+\kappa \chi / 2) \mathbf{E}^{\mathrm{TT}}\right]=0}, \\ {\Delta \mathbf{B}^{\mathrm{TT}}=0},\end{array}
      \tag{6, 7}
      $$

      - where $E_{a b}^{T T}=\mathcal{E}_{a b}^{T T} e^{i(\mathbf{k} \cdot \mathbf{r}-\omega t)}$ is the traceless part of $\mathbf{E}$ after it has been projected onto the interface, 
      - and $B_{ab}^{TT}=\mathcal{B}_{a b}^{T T} e^{i(\mathbf{k} \cdot \mathbf{r}-\omega t)}$ is the traceless part of $\mathbf{B}$ after it has been
        projected onto the interface,
      - (subscripts $a, b = 1, 2$).

    - In the interface frame as shown in Fig. (1),

      - $\mathcal{E}_{11}^{T T}=-\mathcal{E}_{22}^{T T}=\alpha\left(1-S^{2} / 2\right)$, $\mathcal{E}_{12}^{T T}=\mathcal{E}_{21}^{T T}=\beta C$, and
      - $\mathcal{B}_{11}^{T T}=-\mathcal{B}_{22}^{T T}=-\beta\left(1-S^{2} / 2\right)$, $\mathcal{B}_{12}^{T T}=\mathcal{B}_{21}^{T T}=\alpha C$, 
      - where $S \equiv \sin \gamma= k_{ \|} / k$ and $C \equiv \cos \gamma=k_{z} / k$.
      - $\Delta Q \equiv Q_{1}-Q_{2}$ refers to the change in quantity $Q$ at the interface between medium 1 and medium 2.

- We now adapt van Kampen *et al*.’s [26] contour integral method, except with different boundary conditions, to get the gravitonic Casimir energy. 

  - Applying the boundary conditions of Eq. (6) and (7) at the two plate interfaces, we get the following system of linear homogeneous equations of variables $\alpha, \alpha^{\prime}, \alpha^{\prime \prime}, \alpha^{\prime \prime \prime}$ for the '$+$'-polarisation (primes indicate the region of operation, as
    represented in Fig. 1),
    $$
    \begin{aligned} \alpha^{\prime}(1+\kappa \chi / 2)\left(1-S^{\prime 2} / 2\right) e^{-q^{\prime} a / 2} &=\alpha\left(1-S^{2} / 2\right) e^{-q a / 2}+\alpha^{\prime \prime}\left(1-S^{2} / 2\right) e^{q a / 2}, \\ \alpha^{\prime \prime \prime}(1+\kappa \chi / 2)\left(1-S^{\prime 2} / 2\right) e^{-q^{\prime} a / 2} &=\alpha\left(1-S^{2} / 2\right) e^{q a / 2}+\alpha^{\prime \prime}\left(1-S^{2} / 2\right) e^{-q a / 2}, \\ \alpha^{\prime} C^{\prime} e^{-q^{\prime} a / 2} &=\alpha C e^{-q a / 2}-\alpha^{\prime \prime} C e^{q a / 2}, \\-\alpha^{\prime \prime \prime} C^{\prime} e^{-q^{\prime} a / 2} &=\alpha C e^{q a / 2}-\alpha^{\prime \prime} C e^{-q a / 2}, \end{aligned}
    \tag{8 - 11}
    $$
    where $q^{2} \equiv-k_{z}^{2}=k_{ \|}^{2}-\omega^{2} / c^{2}$ and $q^{\prime 2} \equiv-k_{z}^{\prime 2}=k_{ \|}^{2}-(1+\kappa \chi) \omega^{2} / c^{2}$.

  - A non-trivial solution exists when the determinant of the corresponding matrix is zero,
    $$
    \begin{array}{c}{\Delta^{+} \equiv e^{-a q^{\prime}}\left\{\left[C^{\prime}\left(S^{2}-2\right)-(1+\kappa \chi / 2) C\left(S^{\prime 2}-2\right)\right]^{2} e^{-a q}\right.} \\ {-\left[C^{\prime}\left(S^{2}-2\right)+(1+\kappa \chi / 2) C\left(S^{\prime 2}-2\right)\right]^{2} e^{a q} \}=0}\end{array}
    \tag{12}
    $$

  - The boundary conditions also yield a similar set of linear homogeneous equations of variables $\beta, \beta^{\prime}, \beta^{\prime \prime}, \beta^{\prime \prime \prime}$, from which we get for the ‘$\times$’-polarisation,
    $$
    \begin{array}{c}{\Delta^{ \times} \equiv e^{-a q^{\prime}}\left\{\left[(1+\kappa \chi / 2) C^{\prime}\left(S^{2}-2\right)-C\left(S^{\prime 2}-2\right)\right]^{2} e^{-q a}\right.} \\ {-\left[(1+\kappa \chi / 2) C^{\prime}\left(S^{2}-2\right)+C\left(S^{\prime 2}-2\right)\right]^{2} e^{q a} \}=0}.\end{array}
    \tag{13}
    $$

  - Solutions of Eq. (12) and (13) give the allowed modes between the plates, i.e. the eigenfrequencies $\left(\omega_{n}^{+}, w_{n}^{ \times}\right)$.

    - There will be an infinite number of these eigenfrequencies.

    - We can sum them in Eq. (5), using the argument principle of complex analysis [27], 
      $$
      \sum_{n} \omega_{n}=\frac{1}{2 \pi i}\left[\int_{i \infty}^{-i \infty} \omega d \ln \Delta+\int_{C^{+}} \omega d \ln \Delta\right],
      \tag{14}
      $$
      where the closed of integration has been taken over a semicircle $C^{+}$ of infinite radius in the right half of the complex plane of $\omega$ with its centre at the origin, and the imaginary axis $[i \infty,-i \infty]$, in a counterclockwise
      manner.

  - In the high frequency limit, the system does not have time to respond to the rapid oscillations of the field, and therefore will effectively act with time averaged behaviour.

    - Analogous to the EM case, we thus make the natural assumption $\lim _{w \rightarrow \infty} \chi(\omega)=\lim _{w \rightarrow \infty} d \chi(\omega) / d \omega=0$ and 
      - therefore $\gamma=\gamma'$ in this limit i.e. at very high frequencies the plates are effectively transparent to the GW.
    - With this assumption, the second integral in Eq. (14) is independent of $a$.

  - The summation over the infinite number of allowed modes will of course give an infinite value for $E_0$.

    - To get the finite Casimir energy per unit area we take away the energy at infinite separation.

    - Employing the argument principle to Eq. (5) and then integrating by parts, one arrives at the gravitonic Casimir energy ($\xi=-i\omega$),
      $$
      \begin{aligned} E(a) &=\frac{E_{0}}{\sigma}-\lim _{a \rightarrow \infty} \frac{E_{0}}{\sigma} \\ &=\frac{\hbar}{4 \pi^{2}} \int_{0}^{\infty} k_{ \|} d k_{ \|} \int_{0}^{\infty}\left[\ln \left(1-r_{+}^{2} e^{-2 q a}\right) +\ln \left(1-r_{ \times}^{2} e^{-2 q a}\right) ] d \xi \right. \end{aligned}
      \tag{15}
      $$
      where
      $$
      \begin{array}{l}{r_{+} \equiv \frac{C^{\prime}\left(S^{2}-2\right)-(1+\kappa \chi / 2) C\left(S^{\prime 2}-2\right)}{C^{\prime}\left(S^{2}-2\right)+(1+\kappa \chi / 2) C\left(S^{\prime 2}-2\right)}} \\ {r_{ \times} \equiv \frac{(1+\kappa \chi / 2) C^{\prime}\left(S^{2}-2\right)-C\left(S^{\prime 2}-2\right)}{(1+\kappa \chi / 2) C^{\prime}\left(S^{2}-2\right)+C\left(S^{2}-2\right)}}\end{array}
      \tag{16, 17}
      $$

    - The boundary conditions Eq. (6) and (7) at an interface yield Eq. (8) and (10). Simultaneously solving Eq. (8) and (10) one gets
      $$
      \frac{\alpha^{\prime \prime}}{\alpha}=\frac{-C^{\prime}\left(S^{2}-2\right)+(1+\kappa \chi / 2) C\left(S^{\prime 2}-2\right)}{C^{\prime}\left(S^{2}-2\right)+(1+\kappa \chi / 2) C\left(S^{\prime 2}-2\right)} e^{q a}.
      \tag{18}
      $$

    - Comparison of Eq. (18) with Eq. (16) shows that, $\left|r_{+}\right|=\left|\alpha^{\prime \prime} / \alpha\right|$, i.e. $r_+$ is the magnitude of the gravitational reflection coefficient of the ‘$+$’-polarisation.

    - Similarly for the ‘$×$’-polarisation, $\left|r_{ \times}\right|=\left|\beta^{\prime \prime} / \beta\right|$ is the magnitude of the gravitational reflection coefficient of the ‘$×$’-polarisation. 

    - This tells us that Eq. (16) and (17) are the Fresnel reflection coefficients for the two polarisations of the gravitational wave.

      - Therefore Eq. (15) has the same form as the Lifshitz formula for the EM Casimir energy at zero temperature, except the EM reflection coefficients have been replaced with their gravitational equivalent.
      - It is important to point out that this was **not a priori obvious**, as our starting point was the linearised Einstein equations, which is fundamentally different from Maxwell’s equation of electromagnetism, although GEM provides useful analogies between the two theories. 
      - A marked difference is that the EM fields are vectors whereas $\mathbf{E}$ and $\mathbf{B}$ are tensor fields.



- We need now to find an estimate for $\chi(\omega)$. 

  - A number of models of the interaction of GW with bulk matter exists.

  - For example, Ref. [21, 28] considered a medium consisting of molecules modelled as individual harmonic oscillators to calculate the quadrupole moment induced by an incident GW; 

  - Ref. [29] studied the interaction and dispersion of GW in a hot gas.

  - Here we use Peters’ [30] model who considered the scattering of GW by the gravitational field of individual free particles of a thin sheet of matter.

  - Peters derive a gravitational refractive index $n$ which was much larger than that generated by just considering the induced quadrupole moments, 

    - suggesting that his model encapsulates the dominant GW interaction with matter.

  - Peters gives the gravitational refractive index as,
    $$
    n=1+\frac{2 \pi G \rho}{\omega^{2}},
    \tag{19}
    $$
    where $\rho$ is the density of the medium.

    - Under the Lorentz gauge ($h^{\mu \alpha}_{, \alpha}=0 $), $\partial^{\alpha} \partial_{\alpha} h_{\mu \nu}=-2 \kappa T_{\mu \nu}$ (note $h_{\mu\nu}$ is traceless). Using this, Eq. (19), and the relation $E_{i j}=-\omega^{2} h_{i j} / 2$ , result in gravitational stresses of the previously assumed form, $T_{i j}=\chi(\omega) E_{i j}$ where,
      $$
      \chi(\omega)=\frac{1-n(\omega)^{2}}{\kappa c^{2}},
      \tag{20}
      $$
      with the high frequency limits: $\lim _{w \rightarrow \infty} \chi(\omega)=\lim _{w \rightarrow \infty} d \chi(\omega) / d \omega=0$.

    - Except for the lowest frequencies, for ordinary material parameters, $\chi \ll c^{4} / G$ , and therefore the reflection coefficients and Casimir pressure $[P(a)=-\partial E(a) / \partial a] $ are negligible.

    - Specifically, if we take a typical $O[\rho]=10^{4} \mathrm{kg} / \mathrm{m}^{3}$ and $O[l]=1 \overset{\circ}{\mathrm{A}}$ , then $P\left(10^{-6}\right) \approx 10^{-21} \mathrm{nPa}$ . This value is of course beyond detection. 

    - For the Casimir pressure to be measurable, the density of the material would have to be at the very least $O[\rho]=O\left[c^{2} / G\right] \approx 10^{27} \mathrm{kg} / \mathrm{m}^{3}$ . This material density is clearly not achievable, at least terrestrially.



Up until now we have only considered materials with classical properties. Recently, Minter *et al*. [12] propose that the quantum mechanical properties of superconducting films can give rise to specular reflection of GW. 

- Their claim is that in an ordinary metal plate, the ions and *normal* electrons locally co-move together along the same geodesics in the presence of a GW.
- However, when the plate becomes superconducting, the quantummechanical non-localisability of the negatively charged Cooper pair undergoes non-geodesic motion, whereas the positive charged ions of the lattice remains on the geodesic path. 
- Specifically, the authors couple the gravitational field to the superconductor through DeWitt’s minimal coupling scheme [4].
- To first-order, the ground state of the delocalised Cooper pairs do not change in the
  presence of a GW whose frequency is less than the BCS gap frequency.
- In comparison, the shift in the momentum of the localised ions is proportional to the gravitational vector potential.
- Because the Cooper pairs and ions are oppositely charged, a strong Coulomb force will resist this separation of charge caused by the GW, resulting in its reflection. 
- The authors dub this the *Heisenberg-Coulomb* effect. A similar effect had been proposed in Ref. [6].



The origins of the arguments employed by Minter *et al*. are heuristical in nature, some of which we believe require a much more formal approach to be convincing. 

- This is echoed in a review article [14] on theories of enhanced gravitational interaction with quantum fluids, which predates Ref. [12];
- in particular the authors urge that a formal derivation of the quantum mechanical coupling between an electron and both the electromagnetic and gravitational field is needed.
- Nevertheless, the work by Minter et al. do yield results which can be used to falsify their theory. 
- The H-C effect should enhance the Casimir pressure between superconducting plates.



Here we quantify the size of this effect.

- Minter et al. give the reflection coefficient of a superconducting film from an incident GW as,
  $$
  r_{G}=\left(1+\frac{2 \delta^{2}}{c d} \xi\right)^{-1},
  \tag{21}
  $$
  where $\delta$ is the EM skin depth of the superconducting film and $d$ the film thickness.

  - In the thin superconducting film, the current flows in the $x$ − $y$ plane; 
    - therefore only the normal incident component of the GW will drive
      the current. 
  - At normal incidence the magnitude of the reflection coefficient of the two polarisation modes are the same, as they only differ by a rotation (this is also true for EM waves).
    - We can use Eq. (21) in Eq. (15) to calculate the gravitonic Casimir pressure between two superconducting films.
  - We calculate the gravitonic contribution to Casimir pressure for superconducting lead (Pb) of thickness $d = 2$ nm at zero temperature. 
    - The EM skin depth of Pb is $δ = 37$ nm. 

- We compare this with the photonic contribution to the Casimir pressure of superconducting lead.

  - The EM reflection coefficient is [12]
    $$
    r_{E}=\left(1+\frac{2 \lambda \delta^{2}}{c d^{2}} \xi\right)^{-1},
    \tag{22}
    $$
    where $\lambda=83$ nm is the coherence length.

  - The photonic contribution to the Casimir pressure is calculated by using Eq. (22) in the EM Lifshitz formula [1], which has the same form as Eq. (15).

  - Eq. (22) and (21) are most valid when the driving frequency is less than the BCS gap frequency, 

  - as for higher frequencies the dissipative component of the complex conductivities would need to be taken into account.

- However, as higher frequency modes contribute exponentially less to the Casimir energy, one **may still use** the simple reflection coefficients derived by Minter *et al*. to obtain the first-order estimate of the Casimir pressure for superconductors at zero temperature. 

  - Fig. 2 compares the gravitonic to photonic contribution of the Casimir pressure as a function of separation of plates of superconducting Pb.

  - It shows that gravitons can have a significant contribution to the Casimir pressure, via the H-C effect.

  - In fact, for the superconducting Pb film considered here, the gravitons will dominate the Casimir pressure by an order of magnitude over photons.

- The magnitude of the Casimir pressure and plate separation distance that we are talking about here, is comparable in size to what has already been achieved in current experiments [31, 32].

- Few experiments however, have been conducted at low temperatures [33], as room temperature setups are a more experimentally accessible environment.

  - Of these low temperature investigations, 
    - only the ALADIN project has experimented with superconducting aluminium (Al) film, separated by a thin oxide layer from a thick gold plate, 
    - to observe how the Casimir energy influences the superconducting phase transition (preliminary experimental results are reported in [34]).
    - One could imagine modifying such an experiment to test for the gravitonic contribution to the Casimir effect as described in this letter.



![image-20190612151751344](/Users/xmoonight/Desktop/Notes/Thoughts/Gravitational_Casmir_effeft/image-20190612151751344.png)

> FIG. 2. Gravitonic (dotted line) and photonic (solid line) contributions to the Casimir pressure of parallel plates of superconducting Pb at zero temperature, as a function of plate separation $a$. Due to the Heisenberg-Coulomb effect, the gravitonic contribution exceeds the photonic.

We have derived here a Lifshitz-type formula for the gravitonic Casimir effect for real bodies.

- Besides completing a theoretical gap in our understanding of the Casimir effect, this formula is important in light of recent models of enhanced gravitational interaction, 
  
  - as it allows us to quantify the gravitonic contribution to the Casimir effect predicted by these theories.
- If measurements of the Casimir pressure of the setup described in this letter match only to a photonic contribution [Fig. (2) solid line], 
  
  - then one should conclude that the H-C effect is invalid, if we are to hold on to the idea of the graviton.
- However, if experiments show the Casimir pressure to be an order of magnitude larger than that predicted from the photonic contribution alone, 
  - this would be the first experimental evidence for the validity of the H-C theory and the existence of gravitons. 
  - This would open a new field in the way of graviton detection.

- 

  





[Gravitational Casimir effect](https://arxiv.org/pdf/1502.07429.pdf)

[PRL - Erratum](https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.118.139901)

[GRAVITATIONAL CASIMIR EFFECT - video](https://www.perimeterinstitute.ca/videos/gravitational-casimir-effect)

[Superconductors Could Help Physicists Find 'Gravity Particles'](https://www.livescience.com/50119-superconductors-physicists-gravity-particles.html)

[Science Alert](https://www.sciencealert.com/weird-forces-between-superconducting-wires-teach-us-quantum-physics)

[Scientific American](https://www.scientificamerican.com/article/is-gravity-quantum/)

[Start-Up grant](https://www.tudelft.nl/en/2019/3me/februari/start-up-grant-for-microchip-that-tests-new-fundamental-physics-theories/)



[Mechanical Resonators for Quantum Optomechanics Experiments at Room Temperature](https://arxiv.org/pdf/1511.06235.pdf)

[Platform for measurements of the Casimir force between two superconductors∗](https://arxiv.org/pdf/1806.10151.pdf)

[Putting the squeeze on axions](https://physicstoday.scitation.org/doi/full/10.1063/PT.3.4227)









