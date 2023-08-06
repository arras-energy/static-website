---
layout: page
cover: 'assets/images/talking.jpg'
navigation: True
title:  "Use Cases"
date:   2023-07-20 11:59:00 -0700
logo: 'assets/images/arras.png'
current: about
---

# Arras Energy in Action

The commercial-grade high-performance version of Arras Energy software developed for four California use-cases: load electrification, distributed resource integration hosting capacity, tariff design, and distribution system resilience.

<img src="{{ site.baseurl }}assets/images/metal.jpg" alt="linux" style="max-width: 520px;">

These grid modernization efforts which enhance the sensing and automation capabilities of the distribution system through use of smart grid technologies are projected to accelerate the size of utility investment in the distribution system, giving rise to the following important new features:

- CYME model conversion and import.
- Historical, real-time, and forecasted weather.
- AMI and SCADA data import.
- Distribution system assets, such as poles and duct banks.
- Geographic data sets such as address resolution, ground elevation, vegetation, service
territories, census tracts, geographic distances and powerline paths.
- Subcommands to enable internal data and model modification and maintenance
routines.
- Tools to enable external data and model generation and creation capabilities.
- Templates to enable open-source distribution of analysis methodologies.
- Output to plotting modules and cloud-deployed/streaming data repositories.
- Support for cloud-based deployment infrastructure and automated continuous integration/deployment (CI/CA)
- Online documentation for each version deployed.

These features result in important new algorithmic, modeling capabilities, and upgrades that
are now a standard part of the GridLAB-D suite of tools distributed in the open-source by the
Linux Foundation Energy (LF Energy) under the brand name “Arras Energy”.

### **Hosting Capacity Analysis**
The goal of hosting capacity analysis is to quantify the maximum DER generation, EV charger,
and demand response that can deployed at any location in a distribution network without
violating distribution system voltage, current, or control limits. 

<img src="{{ site.baseurl }}assets/images/air.jpg" alt="linux" style="max-width: 520px;">

This process was also referred
to as integration capacity analysis (ICA), particularly when focused only on solar resource
integration.

ICA is achieved using a system-wide iterative power flow solution that examines
all the combinations of loading at every customer meter in a distribution system. Distributed
generation and DER resources are varied at customer meter, independently, to verify whether
a system violation occurs somewhere within a feeder.

### **Grid Resilience Analysis**
GRIP is a cutting-edge software platform designed to help electric grid operators anticipate, mitigate against, and recover from the effects of extreme weather events. 

By combining state-of-the-art agent-based grid modeling tools with grid resilience metrics, GRIP can quantify the state of the grid assets before extreme events, and provide grid operators with actionable insights, such as staging maintenance crew locations, proactive pole hardening or grid topology reconfiguration, to help minimize equipment damage and revenue loss due to power outages. 

<img src="{{ site.baseurl }}assets/images/fire.jpg" alt="linux" style="max-width: 520px;">

The goal of
GRIP is to assist distribution utilities in responding to grid events by:

- Anticipating grid events using machine learning and artificial intelligence techniques
with diverse data sources.
- Absorbing grid events by employing validated control strategies for distributed energy
resources; and
- Reducing recovery time by managing distributed energy resources in the case of limited
communications.

With GRIP, electrical utility operators can reduce operating costs by optimizing grid hardening costs and lowering liability costs and shareholder exposure. These grid operator benefits will ultimately lead to lower electricity rates for customers. 

### **Electrification** ###

Electrification analysis examines the impact of converting customer end-uses provided by 
natural gas, heating oil, or other fossil-energy sources to electricity. In residential buildings, 
the end-uses that may be converted include heating, cooking, water-heating, and clothes 
drying. The simulation delivers feeder-level load shapes as the fraction of converted end-uses 
is increased. In addition, the residential building model identifies when the capacity of the 
distribution panel in the home is exceeded, and a panel upgrade is required.

### **Tariff Analysis** ###
The tariff analysis use-case is designed to include a few tariff structures that IOUs, POUs and 
CCAs implement to give HiPAS GridLAB-D users the ability to explore a variety of tariff designs 
for their distribution networks and customer compositions. Tariff models are obtained from the 
National Renewable Energy Laboratory (NREL) OpenEI database of tariffs, including:
- Investor-Owned Utilities 
- Publicly Owned LSEs Including Publicly Owned Utilities (POUs)
- Rural Electric Cooperatives
- Community Choice Aggregators

## Learn More
Check out the [Tutorials](https://arras-energy.github.io/static-website/tutorials/) for more quick access to learning materials. Read into in-depth literature and news articles at [Reports](https://arras-energy.github.io/static-website/literature/). File all bugs/feature requests at [Arras Energy's GitHub repo](https://github.com/arras-energy).

## Authors
Chassin, David P., Alyona I. Teyber, Elizabeth Buechler, Duncan Ragsdale, Matthew Tisdale. 2023. HiPAS GridLAB-D: High-Performance Agent-based Simulation with GridLAB-D.
California Energy Commission. Publication Number: CEC-500-202X-XXX.

[Tutorials]:  https://arras-energy.github.io/static-website/tutorials/
[Reports]:   https://arras-energy.github.io/static-website/literature/ 
[Use-Cases]:  https://arras-energy.github.io/static-website/use-cases/ 
[Arras Energy's GitHub repo]: https://github.com/arras-energy