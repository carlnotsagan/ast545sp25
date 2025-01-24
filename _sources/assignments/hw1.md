# Homework 1


**Total: (80 points)** - Each sub question worth 10 points. 

**Submitting your work:** Turn into D2L as a PDF. In most cases, solutions will be found by hand, then written up in LaTeX or Markdown and exported as a final PDF. 

## Due Before Class Wednesday, January 29, 2025


1. HKT Section 1.6 describes the notion of homologous stars. Show that:
    * Eq. 1.62 follows from 1.2
    * Eq. 1.63 (with a factor of G included) is a good order of magnitude estimate for the central pressure (e.g. using the equation of HSE).
    * Demonstrate that Eq. 1.71 is the correct matrix equation for homologous stars where heat transport is dominated by radiative diffusion.

    
2. HKT Exercise 1.3 - A useful (albeit not terribly realistic) model for a homogeneous composition star may be obtained by assuming that the density is a linear function of radius. (See Stein, 1966.) Thus assume that $\rho = \rho_{c} [1-(r/R)]$ where where $\rho_{c}$ is the central density and $R$ is the total radius where zero boundary conditions, $ P ( R ) = T ( R ) = 0$ apply. 


    * Find an expression for the central density in terms of R and M. (You will have to use
the mass equation.)
    * Use the equation of hydrostatic equilibrium and zero boundary conditions to find pressure as a function of radius. Your answer will be of the form $P ( R )= P_{c} \times $(polynomial in $r/R$). What is $P_c$ in terms of $M$ and $R$? (It should be proportional to GM$^2$/R$^4$.) Express $P_c$ numerically with $M$ and $R$ in solar units.
    * In this model, what is the central temperature, $T_c$? (Assume an ideal gas.) Compare this result to that obtained for the constant-density model. Why is the central pressure higher for the linear model whereas the central temperature is lower?
    * Verify that the virial theorem is satisfied and write down an explicit expression for $\Omega$ (i.e., what is $q$ of Eq. 1.7?).

    
3. Using MESA, run the `1M_pre_ms_to_wd` [test suite](https://docs.mesastar.org/en/latest/test_suite.html) and export a pgstar image at the end of the simulation of an HR diagram when the stellar model has began cooling as a white dwarf. You can embed the pgstar image into your solutions PDF or include it separately. 