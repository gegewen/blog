<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.10.2/dist/katex.min.css" integrity="sha384-yFRtMMDnQtDRO8rLpMIKrtPCD5jdktao2TV19YiZYWMDkUR5GQZR/NOVTdquEx1j" crossorigin="anonymous">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.10.2/dist/katex.min.js" integrity="sha384-9Nhn55MVVN0/4OFx7EE5kpFBPsEMZxKTCnA+4fqDmg12eCTqGi6+BB2LjY8brQxJ" crossorigin="anonymous"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.10.2/dist/contrib/auto-render.min.js" integrity="sha384-kWPLUVMOks5AQFrykwIup5lo0m3iMkkHrD0uJ4H5cjeGihAutqP0yW0J6dpFiVkI" crossorigin="anonymous" onload="renderMathInElement(document.body);"></script>


# Get started


## 2.1 Homogeneous case
> The targeted reservoir is a 200m thick homogeneous reservoir with a permeability of 50mD. The reservoir is located 1500m below the ground surface with a 10m deep water table. The geothermal gradient of the location is 30 °C/km with an average surface temperature of 20 °C. We want to inject CO$_2$ at a rate of 1.5 MT/yr at the bottom half of the reservoir. How big will the plume be at 30 years?

#### Choose reservoir conditions:
- Initial pressure at reservoir top (bar):
$$P = \rho\mathbf{g}h = 1,000 \frac{kg}{m^3} \times9.8 \frac{N}{m^2}\times (1,500m - 10m) = 137 bar$$
- Reservoir tempearture ($^\circ$C):
$$T=T_{surface} + \frac{\Delta T}{\Delta h} \times h = 20^\circ C + 30\frac{^\circ C}{km}\times1.5km =65^\circ C$$
- Reservoir thickness (m): $200m$
#### Choose reservoir conditions:
- Injection rate (MT/yr): $1.5MT/yr$
- Depth to top of perforation (m): $100m$
- Perforation thickness (m): $100m$
#### Choose rock properties:
- Irreducible water saturation: $0.2$
- van Genucheten scaling factor: $0.5$

