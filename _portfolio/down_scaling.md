---
title: "Down-scaled modelling of Wind Turbine Gearboxes"
excerpt: "Down-scaling a 5 MW WT gearbox to 0.5 kW while keeping the same safety level and frequency distribution"
collection: portfolio
permalink: /portfolio/down_scaling

---

Despite the widespread use of scaled models in the wind industry and engineering in general, gearboxes are tested at full scale in specialized facilities, leading to expensive and restrictive tests. These problems can be mitigated with appropriate down-scaled gearboxes as the ones shown in the figure below. The 4 gearboxes at the top have similar safety factors and resonance distribution (max. 5% relative deviation) as the reference gearbox at the bottom. These results were obtained with a step-by-step procedure in which the parameters to be scaled are divided according to their relation to the gearbox’s integrity and dynamic behavior. The method, which is described in [(Rebouças and Nejad, 2020)](/publication/A3), allows for fine-tuning once an overall scaling has been done.

<figure>
  <img src="{{site.url}}/images/projects/DT_comparison.png" alt="Cross-scale gearbox comparison"/>
  <figcaption>Schematics of WT gearboxes with different rated power (5000 kW to 0.5 kW) but similar safety factors and resonance distribution. 
  <span style="background-color:rgb(230, 049, 051)">red: sun/pinion gears;</span> 
  <span style="background-color:rgb(075, 139, 191)">blue: planet/wheel gears;</span> 
  <span style="background-color:rgb(095, 183, 092)">green: ring gear;</span> 
  <span style="background-color:rgb(255, 140, 026)">orange: planet carrier;</span> 
  <span style="background-color:rgb(175, 103, 061)">brown: main shaft;</span> 
  <span style="background-color:rgb(221, 207, 110)">yellow: output shafts</span> for each gear stage.</figcaption>
</figure>

The effects of gear parameters on safety factors are evaluated with [KISSsoft](https://www.kisssoft.com/en), while [MATLAB’s](https://mathworks.com/products/matlab.html) root-finding and optimization methods are used to find appropriate scaling factors. Both software are used in a structured form, combining their main characteristics.

This project is a good opportunity to develop myself within gear calculations and software development practices. Using an object-oriented approach, I obtained a better understanding of gear safety calculation while implementing some parts of the [ISO 6336](https://www.iso.org/standard/63819.html) standard for estimating the pitting safety factors of planetary and parallel gear stages. I use [KISSsoft's](https://www.kisssoft.com/en) COM interface to control it using [MATLAB](https://mathworks.com/products/matlab.html). These abilities combined give me the expertise to develop robust analysis and design simulation tools for gears and other machine elements in a concise and integrated perspective.
