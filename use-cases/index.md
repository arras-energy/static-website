---
layout: page
cover: 'assets/images/talking.jpg'
navigation: True
title:  "Use Cases"
date:   2023-07-20 11:59:00 -0700
logo: 'assets/images/logo.png'
current: about
---

# Arras Energy in Action

Arras Energy was developed with four main analysis use-cases in mind, hosting capacity,
tariff design, electrification, and resilience. These use-cases were identified by the Technical
Advisory Committee. 

These use-cases provided the basis for additional
requirements, which themselves can be considered more general use-cases for HiPAS GridLABD, giving rise to the following important new features:

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
- Support for cloud-based deployment infrastructure, including Amazon AWS and Docker.
- Support for automated continuous integration and continuous deployment (CI/CA)
- Online documentation for each version deployed.

These features result in important new algorithmic, modeling capabilities, and upgrades that
are now a standard part of the GridLAB-D suite of tools distributed in the open-source by the
Linux Foundation Energy (LF Energy) under the brand name “Arras Energy”.

### **Hosting Capacity Analysis**
The goal of hosting capacity analysis is to quantify the maximum DER generation, EV charger,
and demand response that can deployed at any location in a distribution network without
violating distribution system voltage, current, or control limits. This process was also referred
to as integration capacity analysis (ICA), particularly when focused only on solar resource
integration.

ICA is achieved using a system-wide iterative power flow solution that examines
all the combinations of loading at every customer meter in a distribution system. Distributed
generation and DER resources are varied at customer meter, independently, to verify whether
a system violation occurs somewhere within a feeder.

### **Grid Resilience Analysis**
The resilience use-case was supported by the US Department of Energy's Grid Resilience
Intelligence Project (GRIP) project, funded by the Solar Energy Technology Office. The goal of
GRIP is to assist distribution utilities in responding to grid events by:

- Anticipating grid events using machine learning and artificial intelligence techniques
with diverse data sources.
- Absorbing grid events by employing validated control strategies for distributed energy
resources; and
- Reducing recovery time by managing distributed energy resources in the case of limited
communications.

GRIP builds on previous efforts to collect massive amounts of data that can be used to finetune grid operations, including the VADER project and other Grid Modernization Lab
Consortium projects on distributed controls and cyber security.

GRIP included innovative applications of artificial intelligence and machine learning for
distribution grid resilience using predictive analytics, image recognition, increased “learning”
and “problem solving” capabilities for anticipation of grid events. The GRIP project
demonstrates distributed control theory with and without communications to absorb and
recover from grid events.

GRIP was deployed, tested and validated with utility partners in North America. Anticipation
analytics were tested and validated with Southern California Edison; absorption algorithms
were tested in Vermont; and extremum seeking controls developed by Lawrence Berkeley
National Laboratory were tested with member utilities of the National Rural Electric
Cooperative Association.

To effectively absorb and recover from grid events a grid resilience model was developed in
HiPAS GridLAB-D, which is coupled with resilience control strategies. HiPAS GridLAB-D code
includes a physical failure model for distribution power poles. Using the physical characteristics
of poles, such as material type, pole size, pole-top equipment specifications and pole design
factors, as well as pole aging information such as age, treatment, maintenance, and general
climate conditions, in conjunction with regional weather data, HiPAS GridLAB-D simulates the
conditions at which a particular pole may fail.

Along with the physical stress and failure model, a degradation model addresses aging of the
poles. An electrical pole is considered at the end of service life by the electrical utility company
when the minimum shell thickness is less than 2 inches. Based on this assumption, the
degradation model uses the difference between the inside and the outside pole’s core moment
at the base of the structure where it is considered weakest. Note that the lifetime of the pole
depends on the geographical location, pole treatment, and the weight of the pole-top
equipment, all of which are described by the pole data and configuration.

Applying the HiPAS GridLAB-D pole model to GRIP resilience studies allows the simulation to
consider the weather vulnerability of the electrical grid based on the electrical network models.
Utility-provided Cyme networks and distribution management system (DMS) control models
are used as test cases to provide realistic network conditions. The implementation of the
electrical feeders starts at substation level and capture components such as transformers,
switches, capacitors, electrical lines and metered loads in the model. These models are loaddriven and data-driven using real-world information from AMI and SCADA systems.

The absorption component of GRIP includes strategies that allow the network to be broken
down into virtual island components using GridLAB-D network modeling capabilities in the
efforts to protect and restore the system, after being exposed to a vulnerability. HiPAS
GridLAB-D allows users to model the conditions when system faults occur and determine
recovery tactics using algorithms developed by Packetized Energy. Using this feature, a power
system failure is simulated because of an extreme event, such as high wind, which breaks the
network into isolated islands. The networks are assumed to be equipped with solar and battery
technology to support the generation requirements within a virtual network island as seen in Figure 1, below. 

The topology employs large switching devices under specific control strategies 
that disconnects portions of the grid based on the location of the fault or system vulnerability. \Figure 1. 

**Figure 1. Virtual islanding capability for GRIP’s absorption algorithm developed by Packetized Energy.**


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
National Renewable Energy Laboratory (NREL) OpenEI database of tariffs. These include 
recent tariff data for the following utilities. 
- **Investor-Owned Utilities** 
    - Bear Valley Electric Service 
    - Pacific Gas and Electric 
    - PacifiCorp 
    - San Diego Gas and Electric 
    - Southern California Edison (SCE) 

-  **Publicly Owned LSEs Including Publicly Owned Utilities (POUs)**
    - Alameda Municipal Power 
    - City of Anaheim 
    - Azusa Light and Water 
    - City of Banning
    - Biggs Municipal Utilities 
    - Burbank Water and Power 
    - CCSF (also called the Power Enterprise of the San Francisco Public Utilities Commission)
    - City of Cerritos, Cerritos Electric Utility
    - City of Industry
    - Colton Public Utilities
    - City of Corona
    - Eastside Power Authority
    - Glendale Water and Power
    - Gridley Electric Utility
    - City of Healdsburg
    - Imperial Irrigation District (IID)
    - Kirkwood Meadows Public Utility District
    - Lassen Municipal Utility District
    - Lathrop Irrigation District
    - Lodi Electric Utility
    - City of Lompoc
    - Los Angeles Department of Water & Power (LADWP)
    - Merced Irrigation District (MeID)
    - Modesto Irrigation District (MID) 
    - Moreno Valley Utility (MVU)
    - City of Needles (Public Utility Authority)
    - City of Palo Alto
    - Pasadena Water and Power
    - City of Pittsburg, Pittsburg Power Company Island Energy
    - Port of Oakland
    - Port of Stockton
    - Power and Water Resources Pooling Authority (PWRPA)
    - Rancho Cucamonga Municipal Utility 
    - Redding Electric Utility 
    - City of Riverside
    - Roseville Electric 
    - Sacramento Municipal Utility District (SMUD) 
    - City of Shasta Lake 
    - Shelter Cove Resort Improvement District 
    - Silicon Valley Power (SVP) 
    - Trinity Public Utilities District (PUD) 
    - Truckee Donner Public Utilities District 
    - Turlock Irrigation District (TID)
    - City of Ukiah
    - City of Vernon
    - Victorville Municipal Utilities Services

## Learn More
Check out the [Literature][Literature] for in-depth reports on Arras Energy and its successful use-cases. File all bugs/feature requests at [Arras Energy's GitHub repo][Arras Energy's GitHub repo]. If you have questions, you can ask them on our [Contact Form][Contact Form].

## Authors
Chassin, David P., Alyona I. Teyber, Elizabeth Buechler, Duncan Ragsdale, Matthew Tisdale. 2023. HiPAS GridLAB-D: High-Performance Agent-based Simulation with GridLAB-D.
California Energy Commission. Publication Number: CEC-500-202X-XXX.

[Literature]: https://google.com
[Arras Energy's GitHub repo]: https://github.com/arras-energy
[Contact Form]: https://talk.jekyllrb.com/