# Homework 3


**Total: (150 points)**

**Submitting your work:** Turn into D2L as a PDF. In most cases, solutions will be found by hand, then written up in LaTeX or Markdown and exported as a final PDF. 

## Due Before Class Friday, February 28, 2025


1. **The transition to degeneracy** - At higher pressures the density of relatively cold matter is controlled by electron degeneracy with $P=K\rho^{5/3}$. (10 points each)

    - What is $K$ in terms of fundamental constants? For later convenience, also express $K$ with $hbar$ eliminated in favor of $a_{0}$. You can assume pure hydrogen to start but we will generalize at the end. In the spirit of this assignment, drop the order unity constants in $K$. (For an optional extra challenge, do an order of magnitude derivation of $K$) 
    - What are the dimensional estimates of $P_{c}$ and $\rho_{c}$ (central density and pressure) in terms of $M$ and $R$ (total mass and radius)? Use these estimates and the degenerate EOS to derive the mass radius relation $R(M)$. (You can do this more precisely with exact polytrope solutions, but this simple approach is adequate for now. You can also leave your results in terms of $K$.)
    - Evaluate the above result for radius at $1M_{Jup}$ in units of $R_{Jup}$.
    - Now use $R(M)$ to compute the characteristic density $ \rho_{deg}(M) = M/R^{3}$ of a degenerate object. Again leave your result in terms of K.
    - Now find the mass, $M_{cross}$, where above the density crosses the “electrostatic” density ($\rho_{A}\approx A m_{p}/a^3_{0}$)described above. In doing so you have derived the mass of the largest cold object! This mass marks the transition from lower mass ordinary planets (which are bigger when they are more massive) and the regime of high mass planets and low mass stars where degeneracy means that radius decreases with mass. Give the final result analytically in terms of fundamental constants (eliminating $K$ and $a_{0}$, keeping $A$ and $\mu_{e}$ if you can). Then evaluate numerically for hydrogen, in units of $M_{Jup}$.
    - How does $\mu_{e}$ (mean molecular weight per electron) scale with $Z$ and $A$ (atomic number and mass). Now include this factor in the above analysis. How does $M_{cross}$ scale with $Z$ and $A$ (according to our simple analysis)? Compare your result to [Zapolsky & Salpeter (1969](https://articles.adsabs.harvard.edu/full/1969ApJ...158..809Z). Exact agreement is not expected, but can this analysis explain why the critical mass decreases from $H$ to $He$, but then increases for even heavier elements?

    
2. **Why are hot Jupiters big?** - As a first step to understanding why hot Jupiters are larger than Jupiter, we approximate the structure of the hot Jupiter as an inner convective region that is adiabatic, with $T\propto P^{\nabla_{ad}}$ and an external radiative zone that is approximately isothermal with $T = T_{irr}$ a constant that depends on how close the planet is to the star. (10 points each)

    - What is the equilibirum temperature of a planet at a distance $a$ from a star of luminosity $L_{*}$? What is this numerically for $L_{*}=L_{\odot}$ and $a = 0.05$ (AU)? (And what is the orbital period of this planet?)
    - Using $\nabla=d$ ln $T / d$ ln $P$, what is the radiative luminosity: $L_{rad}(T,P,\kappa,M,\nabla)$?
    - Assume an adiabat that follows $P=K_{1}T^{1/\nabla_{ad}}$ and an opacity of $\kappa=\kappa_{0}T^{\alpha}P^{\beta}$ (note that $κ_{0}$ has odd units). Eliminate $P$ to find $L_{rad}(T)$ along the adiabat, including the opacity dependence.
    - Show that $dL_{rad}/dT \lt 0$ along the adiabat requires $\alpha\gt(1-7\beta)/2$. Assume $\nabla=\nabla_{rad}=2/7$ (for diatomic hydrogen) and $M\sim$ constant (valid in the outer regions directly affected by irradiation). 
    - Derive the value of $K_{1}(S)$ along an adiabat with entropy $S$. Start from the thermodynamic relation $\frac{dS}{C_{p}} = \frac{dT}{T} - \nabla_{ad} \frac{dP}{P}$ and assume a constant $C_{p}$ and $\nabla_{ad}$ (for an ideal gas). Integrate from reference values of $S_0$, $T_0$, $P_0$ to show that $\frac{T}{T_{0}} = e^{(S-S_0)/C_P}\left ( \frac{P}{P_0} \right)^{\nabla_{ad}}$ and thus that $K_1$ increases with decreasing entropy $S$. Combined with part c at fixed $T$, this result shows that as an object cools in time, the luminosity decreases. This effect may seem obvious, but modeling this cooling history is crucial for understanding the evolution of giant planets, and Kelvin-Helmholtz contraction in general.

3. **$M-R$ relation for Juptier like Planets** - Using a similar setup to those described in [MESA 2](https://iopscience.iop.org/article/10.1088/0067-0049/208/1/4#apjs477373s2) Sec 2.2 and using the `make_planet` test_suite in MESA: (20 points each)

    - Reproduce Fig 2. for 5 different ages of you test suite model -- including the last model.
    - On the same plot, show the green line from [Zapolsky & Salpeter (1969](https://articles.adsabs.harvard.edu/full/1969ApJ...158..809Z).
    

    
