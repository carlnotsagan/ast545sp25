# Homework 4


**Total: (160 points)**

**Submitting your work:** Turn into D2L as a PDF. In most cases, solutions will be found by hand, then written up in LaTeX or Markdown and exported as a final PDF. 

## Due 11:59pm Wednesday, April 9, 2025


1. HKT 2.12 (10 points), compare to the total energy radiated by the sun during the lifetime of the main-sequence (10 points) - **Total: 20 points**

2. HKT 2.13 (20 points each sub question) - **Total: 40 points**

3. **Failed supernovae** - Let’s consider the interesting case of a possible failed supernova. If a shock stalls and loses energy, eventually the star may collapse in on itself to form a black hole. Let’s consider a toy model to understand **(a)** whether or not there might be an electromagnetic counterpart to this failed explosion, and **(b)** how long it might last. This problem begins with some order of magnitude arguments presented in [Quataert et al. (2019)](https://academic.oup.com/mnrasl/article/485/1/L83/5420382) and refs therein. **Total: 100 points** - 10 per sub question. 

**(a)** - To understand whether or not we might see anything, we want to know if the material can directly collapse in a spherically symmetric manner onto the black hole, or whether or not it will have sufficient angular momentum to generate a visible accretion disk that can radiate and be observed. 

- i. What is the **minimum radius** of an observable accretion disk around a black hole of mass $M_{\rm{BH}}$?
- ii. Using this size, **calculate the specific angular momentum of material in a Keplerian orbit at this radius**, for a black hole of $10M_{\odot}$.
- iii. **Calculate the minimum rotational velocity of the stars envelope that would provide enough angular momentum to form a visible accretion disk.** Consider a $15M_{\odot}$ star as a Red Supergiant (there are multiple ways to estimate the properties you need for this calculation - consider looking at evolutionary tracks on HR diagrams). Give the answer in terms of a fraction of the maximum breakup Keplarian rotational velocity.
- iv. - Now, assuming no rotation and that we are using mixing length theory such that the turbulent eddies are of size $H$, the scale height of the convective zone. Use this to compute how many convective eddies, $N_{edd}$ will “fit” in a shell at radius $r$? Given an average convective overturn velocity of $v_{conv.}$, calculate the mean rotational velocity from averaging over many eddies $v_{r}^{2}\sim v^{2}_{conv.}/N_{edd}$. Use this to derive an expression for the specific angular momentum of this material. To compare with the value in (iii), assume $H/r\sim 1/3$ and $v_{conv.}\approx 10$ km/s.
- v. Qualitatively, describe in a few sentences if we might observe an EM counterpart under either of the above scenarios - with a rotating or non-rotating RSG progenitor. 


**(b)** Supposing we form an accretion disk that may be visible, we will now estimate the luminosity and lifetime of the disk:

- i. - To get a rough estimate for the luminosity of an accretion disk, calculate $L \sim dE/dt$ for a blob of material in the disk to be transported from a radius $R_{d}$ to the origin (i.e., inside the black hole). This should give you a dimensionally correct luminosity (you can compare with standard viscous accretion disk theory).
- ii. - Now let’s assume that the accretion is Eddington limited. In other words, the disk is going to accrete onto the black hole at the accretion rate such that the disk luminosity from (i) is equal to the Eddington luminosity. Use this to **calculate the accretion rate in terms of the black hole mass**. Assuming the opacity is electron scattering, there should be no other variable in your equation, just constants. For our $10M_{\odot}$ black hole, what is this value? Use CGS or solar masses per year.
- iii. - Estimate the luminosity of this electromagnetic counterpart, again assuming it is at the Eddington limit - use the equation from i. 
- iv. -  In accretion disks we know that the true luminosity can exceed Eddington by a factor of 10 quite easily, so let’s use an accretion rate that is 10$\dot{M}_{\rm{Edd}}$, and assume that much of the envelope mass as been lost in the failed explosion, so we need to accrete about $1M_{\odot}$ of material. **How long will the accretion disk last?** Does this seem plausible to you?
- v. Let's estimate accretion disk lifetime another way. **Estimate the free fall timescale of material in the convective envelope**. Use a density in the envelope of $\rho\sim 10^{-8}$ g cm$^{-3}$ for a [15$M_{\odot}$ RSG envelope 3D hydrodynamical model](https://ui.adsabs.harvard.edu/abs/2022ApJ...929..156G/abstract). Compare this result to the value found in iv. and comment briefly. 


Turns out that the idea of failed SN fallback disks and direct black hole formation is an unsolved problem.


