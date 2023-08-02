---
layout: page
cover: 'assets/images/sunrise.jpg'
title: About Arras Energy
navigation: true
logo: 'assets/images/arras.png'
current: about
---


# A simulation platform for future electricity distribution power systems.

HiPAS GridLab-D, rebranded as Arras Energy, has emerged as an important open-source tool for utilities, researchers, and technology vendors in the development, maturation, and deployment of smart-grid and renewable energy resource integration technology. 

GridLAB-D was originally developed for the US Department of Energy by a team of researchers at Pacific Northwest National Laboratory to address emerging electric power system engineering challenges associated with grid modernization and climate change response, mitigation, and adaptation. 

## Background & Purpose

The first release of GridLAB-D was in 2008. Since then it has been used by the US Department of Energy for key electric power system studies, including conservation voltage reduction, dynamic pricing, peer-to-peer energy exchange, and fault-induced delayed voltage recovery.

The commercial-grade high-performance version of Arras Energy software developed for four California usecases: load electrification, distributed resource integration hosting capacity, tariff design, and
distribution system resilience. 

These grid modernization efforts which enhance the sensing and automation
capabilities of the distribution system through use of smart grid technologies are projected to
accelerate the size of utility investment in the distribution system. 

### Key results:
- Achieved 97.5% success rate in automatic conversion from Cyme models.
-  Simulation speed tests approximately 180 times faster than the DOE version.
- Significant reductions in cloud operating costs, including 94% reduction in storage, and
more than 99% reductions in runtime and computing costs.

## Architecture
Arras delivers an open and developer-friendly framework for addressing important use-cases identified by key industry stakeholders. These use-cases include (1) distributed energy resource hosting capacity, (2) tariff design, (3) end-use load electrification, (4) extreme weather resilience, (5) wildfire safety and protection, (6) peer-to-peer energy, (7) advanced load modeling and forecasting, and (8) high-performance scenario planning at scale to better plan for increasing uncertainty with DER integration.

Arras addresses the needs of key stakeholders such as power system researchers, planners, operators, policy-makers and regulators. Specifically, this software provides an open-source advanced power system simulation engine capable of performing very large scale simulations of distribution systems that include a large fraction of so-called smart grid technology and distributed energy resources that the key stakeholders cannot obtain and/or afford to license from existing software vendors. The goal is for these open source tools to continue to gain ongoing support to possibly open the idea of replacing legacy license tools.

## Open Source Resource
In 2018, the California Energy Commission authorized $6M of EPIC program funding for three open-source projects for SLAC National Accelerator Laboratory to create a commercially viable version of GridLAB-D’s back-end simulation engine and Hitachi America Labs to create a front-end for users in California’s three largest utilities. This could include all users for the tool, from students, researchers, utilities (investor owned and publicly owned), regulators, developers, etc. The front-end software is called GLOW (which stands for GridLAB-D Open Workspace), and the back-end software, which was called HiPAS GridLAB-D, now Arras, as well as OpenFIDO which includes the pipeline tools that use Arras for multifunctional purposes.

California Investor-Owned Utilities are the owners and operators of distribution systems
serving millions of residential, commercial, industrial, and agricultural customers. By 2016, IOU
spending on distribution systems constituted between 32% and 40% of annual revenue.

![camera]({{ site.baseurl }}assets/images/camera.jpg)

Software support and maintenance
infrastructure is open to contributors and administered by professional software engineers in
consultation with experienced electrical and mechanical engineers.

## Customer Adoption

Customer adoption of
distributed energy resources interconnected into the utility distribution system, climate
stressors such as wildfires and extreme weather, and decarbonization of buildings and
transportation add significant challenges to distribution planning and operation. Utility and
customer actions in response to these challenges underpin the states’ climate policies,
including clean energy adoption goals and resource mandates such as the following:

| Pollution Reduction | Effective Savings | Resource Mandates|
| -------------- | ----------------- | ---------------- |
| (AB 32) Greenhouse Gas Reduction | (AB 327) IOUs identify DER locations |(AB 2514) Storage Systems Load-Serving Entities|
| (SB 350) Clean Energy Act | Deployment Cost Minimization | Required Public Renewables  |
| Independent System Operator | Ratepayer Benefits | Statewide Natural Gas Termination |

These regulations impact all market segments and all electricity consumers. To achieve these
mandates and other DER goals, California utilities seek more interoperable and efficient tools
to plan and operate the grid. The HiPAS GridLAB-D project has provided the development of a
necessary tool to bring the stakeholders together to support the adoption of mandates and
regulations through modeling and simulation activities.

## **HiPAS GridLAB-D Upgrade**
The DOE version of GridLAB-D is highly versatile and
scalable, but it has several important limitations for the [use-cases][use-cases] that are common to utilities
serving ratepayers in California. Specifically, difficultly to installment and deployment in diverse operating environments, obtaining proprietary data, no standard analysis methodologies, and studies were too slow or too expensive to run.

HiPAS upgraded and augmented the DOE version of GridLAB-D to run large-scale
simulations and analyses on desktop computers, on-premise servers and private clouds, as
well as coordinate a large number of hosted cloud computing assets to complete groups of
simulations that explore a range of scenarios and options. 


## **Faster, Safer, & Reliable Results**

In 2021 National Grid evaluated HiPAS GridLAB-D as an alternative to the DOE version used
for previous annual 15-year load forecast. The evaluation considered simulation speed,
accuracy of results, and cost of operations as the primary metrics of performance. The simulations
were run for a 1-year horizon, and the results were extrapolated to 15 years using load growth
projections and distributed energy resource adoption rates.

The automatic conversion from Cyme models achieved a 97.5% success rate. Accuracy was verified by comparing the
2022 simulation results to 2021 and confirming that most of the feeders in 2022 consumed
nearly the same energy or slightly more energy than they did in 2021. Simulation speed tests comparing HiPAS GridLAB-D to the DOE version showed that the CEC
version is approximately 180 times faster. 

Cloud operations costs were also reduced from the required 17 TB of storage, to 1.1 TB required storage for the CEC version, resulting from corrections to the Cyme
converter, which reduced warning outputs during the simulation. The runtime of the DOE
version required 25,592 hours at an estimated cost of $113,000. After optimization of the
server and simulation, the runtime of the CEC version required a total of 4.5 hours and cost
only $20.25.

## Learn More
Check out the [Tutorials][Tutorials] for more quick access to learning materials. Read into in-depth liturature and news articles at [Reports][Reports]. If you have questions, you can ask them on [Contact Form][Contact Form] to reach a professional for more information.

## Authors
Chassin, David P., Alyona I. Teyber, Elizabeth Buechler, Duncan Ragsdale, Matthew Tisdale. 2023. HiPAS GridLAB-D: High-Performance Agent-based Simulation with GridLAB-D.
California Energy Commission. Publication Number: CEC-500-202X-XXX.

[Tutorials]:   https://github.com/arras-energy
[Reports]:   https://github.com/arras-energy
[Contact Form]:   https://github.com/arras-energy
[Use-Cases]:   https://github.com/arras-energy
