---
layout: page
title: Contact
navigation: true
logo: 'assets/images/logo.png'
current: about
---

SLAC Laboratory, Stanford, U.S. Department of Energy
Utility companies - Pacific Gas & Electric Co., San Diego Gas & Electric, Southern California Edison Company
Quotes, and reviews
Government funding


# A simulation platform for California's future electricity distribution power systems.

GridLAB-D is a research-grade power system simulator developed by the US Department of
Energy and used to study future electricity distribution systems. HiPAS GridLAB-D, rebranded as Arras Energy, is a
commercial-grade high-performance version of this software developed for four California usecases: load electrification, distributed resource integration hosting capacity, tariff design, and
distribution system resilience. 

These use-cases address California’s climate change goals,
including electricity infrastructure decarbonization and response to climate change impacts on
electricity distribution system infrastructure.

Arras Energy is as an open-source product available free-of-charge for users, and easily
installed on the most widely used computing platforms. Software support and maintenance
infrastructure is open to contributors and administered by professional software engineers in
consultation with experienced electrical and mechanical engineers.

Key results:
- Achieved 97.5% success rate in automatic conversion from Cyme models.
-  Simulation speed tests approximately 180 times faster than the DOE version.
- Significant reductions in cloud operating costs, including 94% reduction in storage, and
more than 99% reductions in runtime and computing costs.

Linux Foundation Energy, an open-source foundation focused on the power systems sector,
adopted Arras Energy and hosts it within the Linux Foundation’s neutral, collaborative
community to build the shared digital investments that are transforming the world's
relationship to energy.

## **Background & Purpose**
California Investor-Owned Utilities are the owners and operators of distribution systems
serving millions of residential, commercial, industrial, and agricultural customers. By 2016, IOU
spending on distribution systems constituted between 32% and 40% of annual revenue.

Looking ahead, grid modernization efforts which enhance the sensing and automation
capabilities of the distribution system through use of smart grid technologies are projected to
accelerate the size of utility investment in the distribution system. 

Customer adoption of
distributed energy resources interconnected into the utility distribution system, climate
stressors such as wildfires and extreme weather, and decarbonization of buildings and
transportation add significant challenges to distribution planning and operation. Utility and
customer actions in response to these challenges underpin the states’ climate policies,
including clean energy adoption goals and resource mandates such as the following:

- AB 32, greenhouse gas reduction (GHG) and a cap-and-trade program. 
- AB 2514, requires CPUC to determine 
cost-effective energy storage systems by load-serving entities.
- SB 350, Clean Energy and Pollution Reduction Act, 1) expands California’s RPS
goals and requires retail sellers of electricity and local publicly owned electricity to increase procurement of eligible renewable energy resources to 40% by the end of 2024, 45%
by the end of 2027, and 50% by the end of 2030; 2) requires Energy Commission to
establish annual targets for statewide energy efficiency savings in electricity and natural
gas final end uses of retail customers by January 1, 2030; and 3) provides
transformation of Independent System Operator into a regional organization.
- AB 327, requires IOUs to identify optimal locations of DER deployment to
minimize overall system costs and maximize ratepayer benefit from investment in DER.

These regulations impact all market segments and all electricity consumers. To achieve these
mandates and other DER goals, California utilities seek more interoperable and efficient tools
to plan and operate the grid. The HiPAS GridLAB-D project has provided the development of a
necessary tool to bring the stakeholders together to support the adoption of mandates and
regulations through modeling and simulation activities.

## **HiPAS GridLAB-D Upgrade**
GridLAB-D is a modern open-source agent-based power system simulation tool developed by
US Department of Energy’s (DOE) Office of Electricity to study modern power systems with
high renewables, energy storage and demand response at the distribution level. GridLAB-D has
been available to the public since 2008. The DOE version of GridLAB-D is highly versatile and
scalable, but it has several important limitations for the use-cases that are common to utilities
serving ratepayers in California. Specifically,
1. GridLAB-D is difficult to install and deploy in the diverse operating environments found
at utilities in California.
2. GridLAB-D requires data that is often difficult to obtain from public sources or is only
available from tools and databases that are proprietary and often difficult to access.
3. There are no standard analysis methodologies implemented in GridLAB-D for the
identified use-cases required by California utilities.
4. Regulatory agencies need open-source software to perform analyses to consider
distribution and tariff planning questions for renewable integration, energy storage and
demand response.
5. GridLAB-D is sometimes too slow and too expensive to run for the kinds of planning
studies needed by larger utilities.

This HiPAS project upgraded and augmented the DOE version of GridLAB-D to meet the needs
identified by the user community in California. These included the ability to run large-scale
simulations and analyses on desktop computers, on-premise servers and private clouds, as
well as coordinate a large number of hosted cloud computing assets to complete groups of
simulations that explore a range of scenarios and options. These upgrades have been 
3
integrated into an open-source production release of GridLAB-D that is freely available to the
public.


## **Faster, Safer, & Reliable Results**

In 2021 National Grid evaluated HiPAS GridLAB-D as an alternative to the DOE version used
for previous annual 15-year load forecast. The evaluation considered simulation speed,
accuracy of results, and cost of operations as the primary metrics of performance. The study 
required the conversion of approximately 2000 feeder models from Cyme, the import of
historical weather data, and a mapping of load data to network load busses. The simulations
were run for a 1-year horizon, and the results were extrapolated to 15 years using load growth
projections and distributed energy resource adoption rates.

The automatic conversion from Cyme models achieved a 97.5% success rate. The remaining
models had issues that required manual intervention to correct modeling errors that do not
affect Cyme but did affect GridLAB-D simulations. Accuracy was verified by comparing the
2022 simulation results to 2021 and confirming that most of the feeders in 2022 consumed
nearly the same energy or slightly more energy than they did in 2021.

Simulation speed tests comparing HiPAS GridLAB-D to the DOE version showed that the CEC
version is approximately 180 times faster. Key performance indicators for hosting capacity on
the benchmark taxonomy feeders, show that the time to solution (in minutes) as a function of
the network size n (in nodes) in 870n2-83n. The time to solve (in seconds) as a function of the
number of DERs modeled d is 0.57d+2.95. A similar hosting capacity performance test on 476
National Grid feeders shows the time to solution as a function of the number of branches b is
1,080b^2+180b.

Cloud operations costs were also evaluated and compared to the DOE version of GridLAB-D for
the National Grid study. The DOE version required 17 TB of storage, whereas the CEC version
required 1.1 TB of storage, with most of the reduction resulting from corrections to the Cyme
converter, which reduced warning outputs during the simulation. The runtime of the DOE
version required 25,592 hours at an estimated cost of $113,000. After optimization of the
server and simulation, the runtime of the CEC version required a total of 4.5 hours and cost
only $20.25.

## Learn More
Check out the [Google][Google] for more info on Arras Energy. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

## Authors
Chassin, David P., Alyona I. Teyber, Elizabeth Buechler, Duncan Ragsdale, Matthew Tisdale. 2023. HiPAS GridLAB-D: High-Performance Agent-based Simulation with GridLAB-D.
California Energy Commission. Publication Number: CEC-500-202X-XXX.

[Google]: https://google.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
