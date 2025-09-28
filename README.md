# Green Space and Physical Activity (GSPA) Exploratory Model
Green space and physical activity exploratory model for introducing leverage points in community-health improvement planning. The model includes an online interface that can be accessed through [isee Exchange](https://exchange.iseesystems.com/public/psh/greenspace-and-physical-activity/index.html#page1). To further explore the model, go to isee Systems and download [isee Player](https://www.iseesystems.com/softwares/player/iseeplayer.aspx), a free vesion of Stella that allows anyone to explore a model, look at the equations, and run simulations. Alternatively, the model included this repository should also work with the open source [PySD module](https://pysd.readthedocs.io/en/master/#) on Python, which allows for more exensive simulation studies.   

## Background
This exploratory model (Richardson, 2024) was developed during an initial Community-Based System Dynamics (CBSD) (Hovmand, 2014) workshop with faculty and staff a the Morehouse School of Medicine's Cardiovascular Institute in 2023 to introduce CBSD and explore interests in a collaboration between Morehouse School of Mecidine, Case Western Reserve and Google Research. It has since been used in various courses and workshops to introduce basic concepts in system dynamics and illustrate the counterintuitiveness of leverage points (Meadows, 1999) in a public health context. 

## Overview
The model consists of two basic stock and flow structures: green space and physical activity. The model includes seven different places where one can intervene in a system by turning on or off various switches. These are indicated as intervention points (IPs). The model starts in a dynamic equilibrium and the goal of exercises and demonstrations is to find the combination of intervention points that maximize the overall impact on increasing the prevalance of physical activity in a community. 

<img width="810" height="650" alt="image" src="https://github.com/user-attachments/assets/dfcc48c5-dbbb-4789-ae11-744fc4aa6233" />

In the online interface, there is an overall effect size (ES) of 50%, meaning one can intervene with a direct effect on the system of 50% from one intervention, 25% from two interventiosn, 16.7% from three interventions, etc. This approach penalizes adding more interventiosn that are ineffective (or even harmful despite their immediate intended benefits) in favor of higher impact from focusing interventions. 

## Acknowledgements
This effort was initially catalyzed and supported through a gift from Google Research. 

## References
Hovmand, P. S. (2014). *Community based system dynamics.* Springer. 

Meadows, D. (1999). *Leverage points: places to intervene in a system.*

Richardson, G. P. (2024). Building confidence in exploratory models. *System Dynamics Review, 40*(4), e1769. https://doi.org/https://doi.org/10.1002/sdr.1769 




