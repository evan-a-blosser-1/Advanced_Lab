# Advanced_Lab

Open ended labratory experiments cunducted for introduciton into research. 

## Lab 1: Cavendish Experiment: Calcuating Newtons Gravitational Constant "Big G"

The Cavendish experiment was carried out with the Pasco Gravitational Torsion Balance. This apparatus is capable of negating the effects of Earth's gravity in order to measure the gravitational forces acting on the smaller weighted spheres $m_2$, suspended on a pendulum, by the larger spheres $m_1$. For the experiment, we utilized Mathematica and video recording equipment to obtain position data of the oscillating beam reflected by the pendulum's mirror. 

We carried out **Method II: Measurement by Equilibrium Positions** from the Cavendish Pasco Manual. Equation 1.9 from the manual gives the calculation for $G$ with only 2 unknowns. These unknowns are the differences in equilibrium positions $\Delta s$ & the period $T$. The following is Eq. 1.9 and all known values:

$$
G = \pi^2 \Delta s b^2 \frac{d^2+\frac{2}{5}r^2}{T^2m_1Ld}
$$

where:

$r=9.55mm$

$d=50mm$

$b=46.5mm$
    
$m_1 = 1.5kg$

$L1= 8.80216m$ {Small Measurements and Trig relations}

$L2=8.724m$  {Single Tape Mearument}

We will also use the equation for $G_o$ on page 12 of the manual that accounts for systematic error as follows:

$$
G_o = \frac{G}{1-b}
$$


For comparison, we found the accepted value is, $G = 6.67430e-11$ from https://pml.nist.gov/cuu/Constants/.

## Conclusion 

For the four experimental runs, we carried out our closest value to the accepted $G$ value is, $G_o \approx 6.61758 \times 10^{-11} \pm 1.28143 \frac{m^3}{kg\cdot s}$, which was calculated from our first experimental run's first equilibrium position. However, this value also carries with it the second to greatest uncertainty behind data set 3's uncertainty of $0.8499 \%$. Thus, there is still some systematic error unaccounted for within the experiment. Especially when this is compared to the values from our second and fourth experimental run. We somehow found approximate values for the first and third runs, yet our second and fourth showed severe errors. This could have come from miscalculated lowering of the saddle which keeps the pendulum in place while not being used. 

### Uncertainty
The uncertainty for each $G_o$ calculation was taken from the square root of the diagonal of the covariance matrix. This means that the uncertainty for each of the fit parameters $T$, $S_1$, & $S_2$ were used within the equation for $G$. Given that $\Delta S$ is a summation then we can sum their uncertainties, but the calculation of the period is $\frac{2\pi}{\omega}$ and in $G$ the period is squared; thus we must finish our summation of uncertainties as the fractional uncertainties of $\Delta S$ & $T$. 

The uncertainty for the mass $m_1$ was found to be $\pm 10g$ as defined on page 3 of the Pasco manual, and it's percentage of uncertaitny was calculated as $\frac{10g}{1500g}\cdot100\%$. For our measurements of L we decided to use L1 which we defined as our smaller measurments of the apparatus along with trigonometric relations. We also defiend the uncertainty of this mesurement to be $\pm 0.0005$. These were also included in the calculation of the uncertainty percentage.   

With this taken into account we can see our measurement with the least uncertainty was from our fourth data set. This measurment of $G_o = 8.64524 \times 10^{-11} \pm 1.19537 \frac{m^3}{kg\cdot s}$ was roughly $29.5\%$ away from the accepted value for $G$, yet has the least uncertainty within it's mearuments. Overall, our results show that we did in fact get a measurement within $1\%$ of the accepted value. The uncertainty within the fit parameters shows that there is an error in processing the data to find the period and equilibrium positions. Also as the uncertainty was greater for the closest calculation of $G$ it can be concluded that this is not as accurate as it may appear.



## Lab 2: Two-Slit Single Photon at a Time

The Two-slit experiment utilized both a laser and a light bulb as the source of photons. For the laser measurements, voltage readings were taken to measure the interference pattern of the photons after passing the double slit within the apparatus. For the bulb, a photomultiplier tube (PMT) was used along with an oscilloscope and a pulse counter/interval timer (PCIT) in order to count the individual photons passing through the apparatus into the PMT. The PCIT was set to a $10$ $second$ interval thus each initial reading of the counts was in $\frac{counts}{10 \textit{ sec.}}$ and then converted into $\frac{counts}{1 \textit{ sec.}}$. 

