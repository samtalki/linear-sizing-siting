# linear-sizing-siting
Basic linear program sizing/siting algorithm for a single PV system.

# What is this program?

This program **may*** help Solar Developers make a basic decision about where to install a commercial-scale PV system. This program was originally designed to be used to assist a solar development design for the New Mexico State University campus in the [US Department of Energy Solar District Cup](https://www.energy.gov/eere/solar/solar-district-cup). The inspiration for this tool and the data used to design it were graciously provided by the National Renewable Energy Lab (NREL).

# What do I need to use this program?
In a nutshell, you will need a complete power system model described via OpenDSS and corresponding hourly consumption data. I cannot provide you either of these used for the creation of this tool because I do not have the right to do so. The OpenDSS-compatible data needed to run this simulation is typically restricted data, and the data I used to design this program is no different. A common model used to facillitate power system optimization research is the IEEE feeder, which could be used for this task.

However, to give you an idea, roughly what you will need is:

* An OpenDSS Model for your use case
  * A .dss circuit model
  * A PV panel OpenDSS model (provided)
* Hourly time interval consumption data for each building in your use case.
  
