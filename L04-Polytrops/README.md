# L04 Polytrops

Week 2, Thursday



## Material covered and references

Derivation of the Lane-Emden equation

So far, we only have two equations for stellar structure: mass continuity, and hydrostatic equilibrium. However, we have 3 unknowns: Mr(r), P(r), and rho(r). 

We need to find a relation between two of these quantities. The ideal gas law is a relation between P and rho (called an "equation of state", but it introduced another unknown T(r). To find T(r) we will have to talk about energy transport (later on).  

But for know, we can use some useful polytropic equation of state where the pressure only depends on the density to a certain power such that 
<img src="https://render.githubusercontent.com/render/math?math=
P\left(r\right)\:=\:K\:\rho\left(r\right)^{^{\frac{^{n+1}}{n}}}">.

By setting the density <img src="https://render.githubusercontent.com/render/math?math=\rho\left(r\right)\:=\:\rho_c\:\theta\left(r\right)^{^n}">, where theta is a unit-less function that describes the variation of the density as a function of radius, we can transform our equations of structure into the well-known Lane-Emden differential equation for polytrops, the solution of which gives <img src="https://render.githubusercontent.com/render/math?math=\theta\left(\epsilon\right)">, where epsilon is unit-less and related to r.

> In the [textbooks](../textbooks.md):
> 
>* The best one in my opinion is in the Leblanc: Sec 5.4, until eq. 5.93
>* But you can also look in McDo: Chap 9 until eq 9.10, or Hanson Sec. 7.2.1 until eq. 7.26
>* Kip has the derivation in Chap 19 until eq 19.10, but uses a nomenclature different than the other books ( w(z) instead of theta(epsilon)

---

Once we obtain the solution for <img src="https://render.githubusercontent.com/render/math?math=\theta\left(\epsilon\right)"> for a certain n index, we can use it to determine characteristics of the polytrop. The two things we need from the solution are the value of epsilon where theta is null (the surface), which we called epsilon_1, and the slope of theta (theta') evaluated at epsilon_1.

In class, we found 3 equations that uses these two quantities, and relate Mstar, Rstar, Po, rho_o, and K. As we only have 3 independent equations, this means we define two quantities, we can find the other 3.

For example, you can make equations for Po, \rho_o, and K that only depends on Mstar, Rstar. 

Another example would be for stars with degenerate matter (we'll talk about this later in the course). In this case K is known from statistical mechanics -- therefore if we pick the mass of the star, the radius is known. 

> In the [textbooks](../textbooks.md):
> 
>* Hanson has the best description of the properties of polytrops. 

>Table 7.1 also gives values for epsilon_1 and theta'(epsilon_1) for various n.
 
---

Python skills:

* Practice adding curves to graph, and use the astropy units and constant packages
* Learn about functions
* Learn about loops

## Supplemental problems suggestions:

* Leblanc ex. 5.4 shows that a n=0 polytrop represent the constant density case.
* Leblanc Prob. 5.10 