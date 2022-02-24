# L06 Saha Equations Part 1

Week 3, Thursday

No notebook for this class meeting

## Material covered and references

We found out that to calculate the mean molecular weight precisely, we also need to know the degree of ionization of each elements. To do so, we need to do some Stat Mech. 

* We need to use first the concept of Boltzmann factor that describes the probability of finding a particle in one of its energy state. In a large ensemble of particle, the fraction of particle in a given state becomes equal to this probability
* We also need to find out the possible states for the free electron that results from the ionization. This is when we need to use the uncertainty principle. For this we find that we can put only 2 electrons (of opposite spin) in a "quantum box" of size <img src="https://render.githubusercontent.com/render/math?math=dVd^3p\approx h^3">.

> In the [textbooks](../textbooks.md):
> 
>* For this part, I suggest looking into the undergrad Thermo/StatMech book by Schroeder (2.5, 6.7). 
>* You can also find a nice description in "Astrophysical Concepts" by Martin Harwitt, 4.11

---

Here are the steps to find the Saha equation that relates the number of electron in two adjacent ionization levels:

1. Using the Boltzmann factor for each ionizations level, we can find the relation between the number of atoms with their electron in the ground state and the total number of atoms in this ionization state.  
2. Now, we can look at the removal of single electron from an atom in its ground-state configuration to the next ionization stage also in its ground-state configuration (note: this next ionization stage has also to take into account the state of the ejected electron). 
3. We can combine all the equations found in 1 and 2 to get a single relation between <img src="https://render.githubusercontent.com/render/math?math=n^r"> and <img src="https://render.githubusercontent.com/render/math?math=n^{r%2B1}">, called the Saha equation. 

> In the [textbooks](../textbooks.md):
> 
>* My favorite derivation is in the Kip 14.1
>* Leblanc 1.5
>* Hansen 3.4
>* McD Chap.7

---

We want to use the Saha equation to find the number of elements in each ionization stage of each elements present in a gas. 

With a bit of math, we can setup 3 sets of equations with three sets of unknowns.

For the case of hydrogen, we analytically solved this set of equation. We will see during next lecture what do to if we have multiple ionization stages, and multiple elements.

> In the [textbooks](../textbooks.md):
> 
>* Kip 14.2
