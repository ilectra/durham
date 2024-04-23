# The Living Lab

A project to investigate technologies to reduce the environmental impact of HPC systems in a working environment.
 - An immersion cooling system enabling higher waste heat temperatures
 - An exploratory heat storage and reuse facility to make use of waste HPC heat

## Background


Traditional air-cooled data centres are extremely inefficient 
with typically as much power being used to deal with waste heat as is
used to power compute equipment. This Power Utilisation Efficiency
(PUE) is improved for systems with water cooled rear rack doors, to
typical values around 1.3–1.5 (the ratio of total power to useful
power), and further to around 1.1–1.3 for systems using Direct Liquid
Cooling (DLC), where cooling fluid is piped into CPU heat
sinks. Immersion cooling can improve the PUE further, to typical
values around 1.02–1.05, meaning that cooling the system consumes
around 2–5% of the power that the compute facilities consume. For
large pre-Exascale and Exascale systems, with power consumption of
order 10MW, this improvement is significant, typically saving of order
1MW power. The output temperature from immersion systems can also be
higher, meaning that the waste heat is more easily usable, for example
for heating buildings.

### Heat storage and reuse

Total waste heat in the UK is in excess of 390 TWh per year. However,
heat is not considered as a pollutant in the UK and low-grade heat is
not treated as a commodity, despite almost half (2.43 EJ = 675 TWh/yr)
of all energy used in the UK is for generation of heat. Currently,
heat production is almost entirely (77%) from burning fossil fuels
with consequential emissions of 120 Mt CO2 , equivalent to 30+% of the
UK’s annual total. To meet the next UK Carbon Budget it is critical
that heat production in the UK is decarbonised. This will involve
displacement of natural gas by a combination of geothermal energy,
electricity and possibly hydrogen. What has yet to be properly
considered is the use of surplus or waste heat. This is in part due to
the difficulty of moving heat without it dissipating. However, instead
of attempting to move the location of heat we need to consider
shifting it in time, from times of plenty to times of need. This
requires heat storage in large volumes. Construction of large heat
stores, although possible, is expensive and has substantial surface
impact in terms of amenity value of what might otherwise be green
space surrounding domestic and office accommodation. However, the UK
has a combination of subsurface manufactured water holding cavities –
abandoned and flooded mines as well as natural saline aquifers both of
which can be used to store heat. The theoretical heat storage capacity
of subsurface waters in the UK, including flooded mines and deep
saline aquifers is orders of magnitude higher than national heat
demand, and much of the UK population lives in areas underlain by
sedimentary basins containing both saline aquifers and abandoned
mines. It would seem sensible to store waste heat (and harvested solar
heat) when not required during the summer months and reproduce the
heat when it is required in the winder months. To date this has not
been attempted in the UK but is proven and operational in Heerlen,
Netherlands.

## Strategic aims

This living lab sub-project will provide confidence in the
installation and operation of immersion cooling and thus lead to
increases in the efficiency of HPC data centres both at Durham and
other UKRI-funded sites. We will develop and explore the new solutions
for efficient cooling of HPC systems and will engage the wider UKRI
DRI community to share and impart knowledge and experience, and
provide direct access to these advanced facilities, and thus ensure
and enable the adoption of sustainable research infrastructure.

An additional benefit of immersion cooling is a reduction in HPC
server complexity. Internal fans, heat sinks and cooling pipes
(typically copper) are no longer required, thus simplifying server
design, and reducing embodied carbon during manufacture. This compares
favourably with a DLC system such as that used with the COSMA8
facility, which requires coolant distribution units to feed a
secondary cooling loop, in-rack manifolds which deliver coolant to
nodes, and heat pipes within the nodes to remove heat from the CPUs.
Other components within the server are not typically cooled in this
way (RAM, disks, motherboard), which can mean that up to 30% of the
heat load still needs air cooling, thus requiring active cooled rear
rack doors (we note that some bespoke systems to direct-liquid cool
other components, but at significant additional cost and
complication). An immersion tank greatly simplifies the components
required, and helps to reduce the embodied CO2 emissions associated
with manufacture.

It should be noted that data centre efficiency (PUE) is not only
dependent on the type of cooling equipment within the data centre, but
also on how this waste heat is dealt with. Previous systems have
typically used air conditioning unit and active refrigeration
components. In recent years, efficiency has improved by the use of dry
air coolers, which seek to cool, rather than actively chill, the data
centre water supply. However further gains in efficiency can be made
by making use of this waste heat, for example to heat buildings and
pre-heat hot water supplies which we explore in the second
sub-project. The hotter this waste heat is (helped by immersion
cooling), the more efficiently it can be removed or reused.

We will aim to develop the UK's first underground thermal energy
storage (UTES) scheme, utilising the abandoned and flooded coal mines
that lie beneath the Durham University campus. Heat supply will come
from the necessary cooling process associated with the HPC at the same
site.

## Societal impact

The immersion cooling facility will be made available to the UKRI DRI
community, including technical support teams, infrastructure teams and
system design teams. We will regularly invite teams to visit the
facility and operate on the immersed equipment, and host regular ”open
days” on known dates when community members can visit. We will also
host training seminars and publish white papers and How-To guides. We
will present results, experiences and findings at national and
international HPC conferences.

A successful demonstration of the feasibility of seasonal heat storage
and retrieval from the HPC systems in Durham will have massive
implications for assisting the nation decarbonise its massive heat
requirement.  The potential sources of waste heat and storage areas
have already been identified. Waste heat storage will also help
de-risk geothermal developments and ensure sustainability. This
project, if funded, will become under the umbrella of the emerging
National Geothermal Centre (NGC; co-led by Durham Energy Institute),
the aim of which is to ensure rapid roll-out of geothermal energy
projects across the UK and will benefit from NGC’s drive to establish
a supply chain for heat delivery infrastructure as well as ensuing the
appropriate legislation and regulation are in place to facilitate and
manage what will be a substantial industry in the UK.

## Summary

The combination of more efficient HPC cooling with higher working
temperatures better suited to space and water heating, and the use of
heat storage technology to store excess heat for reuse in the cooler
winter months will have a significant benefit for the UK’s greenhouse
emissions and aid the journey to net-zero.  This project seeks to
develop a living lab to allow investigations in these areas.
