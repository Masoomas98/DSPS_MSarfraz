For this homework I worked alone, it was about finding a plot that is visually bad following  three points, and a good plot that follows some of the tufts rules. And then finding a bad plot we made and correcting it.

**PART A**

**Visually Bad Plot**

<img width="946" alt="Screenshot 2023-11-22 at 10 04 54 PM" src="https://github.com/Masoomas98/DSPS_MSarfraz/assets/129995121/d11711e2-359f-48b8-bad7-b2484b7dc571">

The plot is somewhat misleading hence distorted as the caption mention 4 processes but the labels are only for 3 process, that too not defined properly which curve presents which process. There is no key for the symbols they have used for example sterics or triangles represent what? What is the grey color plot presenting? So there is distortion and ambiguity as ecuase of same tones of black and gre the error bars are messed up above 1GeV and it could lead to confusion among the readers, One way t oplot these could be to use subplots and explain all 4 processes separately for the cross sections or atleast use different distinct colors or some transparency to see what's hidden underneath the overlapping plots.

**Visually Good Plot**

<img width="1445" alt="Screenshot 2023-11-22 at 11 58 51 PM" src="https://github.com/Masoomas98/DSPS_MSarfraz/assets/129995121/6019f46a-90c1-42a7-bba6-50ff5ae23628">

This plot caught my attention as it was extremely easy to understand. According to Tufte's rules:
1. It has maximized data-ink ratio, instead of a separate dimension for change in mass, it is mentioned on top of each peak, however there is still ambiguity, it could have a title.
2. Lie factor=  the peaks correspond to the change in mass and it's in proportion with the numbers on them and also the relative difference of neighboring peaks is reasonable.
3. There is no chart junk no extra visuals to distract the reader from the original data.
4. There seems to be no redundancy, except repetetition of colors which could have been avoided.

**PART B**

<img width="693" alt="Screenshot 2023-11-23 at 12 59 43 AM" src="https://github.com/Masoomas98/DSPS_MSarfraz/assets/129995121/684f5674-7ed1-4a00-a3d7-73e0839dfb39">

After learning about good and bad plots it's funny back in spring '23 I added this plot in my report for one lab without any axis labels, units or axis. So I will be correcting this plot and explain what is this plot about.

**Corrected version**

<img width="901" alt="Screenshot 2023-11-23 at 1 30 41 AM" src="https://github.com/Masoomas98/DSPS_MSarfraz/assets/129995121/0289f1ce-5754-42f2-8082-9047f167859c">


This is a graph of Power dpectral density vs frequency for experimental calibration. The main idea was to find the bandwidth for later use and eventually find Boltzmann constant.
(THEORY)
Johnson noise, also known as thermal noise is an electronic noise present in all electronic devices due to thermal agitation of charge carriers. This noise is caused by random motion of electrons and ions, which leads to random fluctuations of voltage and current.
Johnson noise is proportional to the temperature of the component, resistance of the component
and the bandwidth of the measurement. As per theory, the voltage noise density due to Johnson noise in a resistor with resistance R at temperature T can be calculated using the following equation:
< Vj^2 > = 4𝑘𝑇𝑅Δ𝑓 - (1) Where Vj is the voltage noise density, R is the resistance and Δ𝑓 is the bandwidth and k is the
Boltzmann constant. Equation 1 says that the voltage noise density due to Johnson noise increases with increasing temperature and bandwidth. Vj is proportional to the square root of resistance. Which means reducing the temperature, decreasing the bandwidth or lowering the resistance can reduce the impact of Johnson noise in electronic circuit.
Johnson noise can limit the sensitivity and accuracy of the devices, especially those operating at low signal levels. This is fundamental noise.
Using the graph above which is basically Voltage spectral density vs frequency we find the bandwidth for calibration and then plotting < Vj^2 > vs. R, resistance, the slope would give the value of 4𝑘𝑇Δ𝑓 then we can extract the Boltzmann constant from this.
