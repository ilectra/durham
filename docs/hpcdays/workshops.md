# Workshops

## Tuesday, 3 June 2025

### DiRAC RSEs: 13:30-15:00 and 16:30-18:00

**Convener: Ilektra Christidi (UCL)**

This session is for the DiRAC RSEs to present their work to the UK HPC community, as well as catch up with each other and other DiRAC people that might want to join. Come join us to see how DiRAC RSEs accelerate science in particle physics, astrophysics, and cosmology, by promoting good software development practices, optimising software running on the DiRAC sites, and assisting researchers in implementing new functionality and using accelerators in their codes.

- 13:30-15:00: 4x20-minute talks (speakers to be confirmed)
- 15:30-17:00: This workshop consists of two parts, and the second part is for DiRAC RSEs only.


## Wednesday, 4 June 2025

### WHPC: 09:45-10:30 

**Convener: Eleanor Broadway (EPCC)**

Organised by representatives from the Women in High Performance Computing (WHPC) community, this session will explore new, sustainable and realistic strategies for improving and supporting the diversity in our community. Don’t miss this opportunity to be part of the conversation on overcoming our current barriers to change, exploring the crucial role of funders and leaders, and discovering how we can all contribute to a more inclusive future in HPC and beyond.

More details coming soon! 

### HPC/HTC in High-Energy Physics: 13:30-15:00 

**Convener: Enrico Bothmann (CERN), Luigi del Debbio (Edinburgh), Marek Schoenherr (Durham)**

Speakers: 

- Maria Girone (CERN)

- Dave Britton (Glasgow)

- Davide Constanzo (Sheffield)

- Manuel Griffels (KIT)


### HPC in Weather & Climate Research: 13:30-15:00 and 15:30-16:15

**Conveners: Chris Maynard (Met Office), Marion Weinzierl (ICCS, University of Cambridge)**

In this session we will hear from a series of speakers from the Weather and Climate Research community, talking about how they leverage HPC and AI in their domain.

Our speakers are:

- Greenville Lister, NCAS: 
   <details>
       <summary>"Running large simulation models and workflow"</summary>
      tbc
   </details>

- Ben Went, Met Office: 
   <details>
       <summary>"Using PSyclone, a domain specific compiler to parallelise the Met Office weather and Climate model with OpenMP"</summary>
      tbc
   </details>

- Nell Hartney, University of Exeter: 
   <details>
       <summary>"Incorporating an automatically differentiable dynamical core in training machine learning models for weather and climate."</summary>
      Machine learning (ML) approaches are becoming more and more widespread in weather and climate science. Applications range from emulating parametrisation schemes to data assimilation and more recently even to full ML-based weather and climate prediction models. The large quantities of data needed and the costly nature of training these ML models means that they are intrinsically linked with HPC.
      A common theme in ML-based schemes for weather and climate prediction is a significant deterioration in their performance at longer lead times due to rapidly growing errors and the model drifting outside the range of training data. One proposed solution for this issue is the idea of imposing physical constraints within the training loss function, which gives a tighter coupling at the training stage between this model physics and the data.
      The key ingredient in this approach is a differentiable physics-based model. Gusto, the dynamical core toolkit built on the Firedrake finite element library, is one such model that is automatically differentiable. Because full-scale weather and climate models are typically optimised for computational efficiency on specific computing hardware, scoping projects using the likes of Gusto are essential to provide guidance on decisions about HPC infrastructure.   
      This talk will discuss our progress towards using Gusto as the differentiable dynamical core in a hybrid ML atmospheric model, in the style of NeuralGCM. We will investigate questions about the impact of the dynamical core formulation, including using a simplified equation set and different spatial and temporal discretisations.
   </details>

- Denis Sergeev, University of Exeter/ University of Bristol: 
   <details>
       <summary>"Atmospheric dynamics on other planets"</summary>
      Detection and characterisation of exoplanetary atmospheres is entering a new era thanks to the new generation of powerful telescopes. To make the best use of observational data and guide future missions, we must advance our theoretical understanding of atmospheric dynamics. In this talk, I will show my recent work on adapting the Met Office's new 3D general circulation model (LFRic) to various exoplanets, from temperate terrestrial planets to hot Jupiters. I will talk about LFRic’s new capabilities and its potential for studying planetary atmospheres.
   </details>

- Joe Wallwork, ICCS, University of Cambridge: 
   <details>
       <summary>"Accelerating UKCA by predicting timesteps with FTorch"</summary>
      The United Kingdom Chemistry and Aerosols (UKCA) model is a community atmospheric chemistry and aerosol microphysics model, which forms part of the Met Office's weather forecasting system. It is also a key part of the UK Earth System Model (UKESM), whose outputs feed into IPCC reports. UKCA is a particularly expensive part of the Met Office's model, so significant reductions to its computational cost would be welcome. The chemistry component of UKCA (the most expensive) uses an implicit timestepping scheme in which each iteration starts from a default, large timestep size. In each iteration, an attempt is made to solve the nonlinear system over several grid-boxes in the spatial domain, but in many cases this fails at the default timestep size. If so, the timestep size is repeatedly halved and the solver re-run until convergence is achieved. In this talk, we propose a method for predicting the timestep that will be required in advance,  thereby avoiding wasted computation in the attempts to run the chemistry model with timestep sizes that are too large. We utilise a simple machine learning (ML) based approach, coupled into UKCA using FTorch - a Fortran interface for the popular Python-based ML tool, PyTorch. Further, we make use of FTorch's recently added online training functionality, in order to avoid archiving training data that would have no clear other purpose.
   </details>

   - Justs Zarins, EPCC:
   <details>
       <summary>"Exploring Dataflow Architectures for Improved Efficiency in Earth System Models"</summary>   
     Earth system models are crucial for simulating environmental processes but demand significant computational resources and energy. In this presentation we will explore the potential of               dataflow architectures to enhance both computational and energy efficiency of ESMs. We will primarily discuss the Cerebras Wafer Scale Engine, examining its capabilities and evaluating                its suitability for the shallow water equation.
   </details>

## Thursday, 5 June 2025

### HPC/HTC in High-Energy Physics: 09:45-10:30

**Convener: Enrico Bothmann (CERN), Luigi del Debbio (Edinburgh), Marek Schoenherr (Durham)**

Speakers: 

- Gurtej Kanwar (Edinburgh)

- Roy Stegman (Edinburgh)

- Antonin Portelli (Edinburgh)


### eCSE Session: 11:00-12:30

**Convener: Mladen Ivkovich (Durham University)**

The ARCHER2 GPU eCSE support provides funding to the UKRI research community to develop software in a sustainable manner to run on GPU-based architectures. Two such GPU eCSE calls have closed recently. In this knowledge exchange workshop, leads and developers of the funded projects present their current work and the challenges they're facing in their respective domains with regards to HPC GPU acceleration of scientific software. 

### Benchmarking Symposium: Benchmarking of HPC systems for simulation and AI 16.30-18:00

**Conveners: DiRAC, ExCALIBUR, UKRI Living Benchmarks**
**Lead: Mark Wilkinson**

Benchmarking is an essential part of the co-design and procurement of large-scale computing
systems, supporting the deployment of cost-e8ective, productive services. Benchmarks are
also valuable tools for obtaining quantitative information about the health of systems following
their deployment in production, for example confirming that application performance is
maintained following system software updates.

The UK has an outstanding track record of the successful use of science benchmarks to
optimise the design of large-scale computing services. There are a number of recent and
currently active projects in this area, including the ExCALIBUR Benchmarking project, the
ExCALIBUR BASE-II project, the UKRI Living Benchmarks project and the DiRAC-4 design
process. As UKRI develops its plans for the services which will comprise the future DRI
ecosystem, a workshop to discuss the benefits and challenges of e8ective benchmarking is
particularly timely.

The goals of this workshop are to:

1. share experiences (both positive and negative) and tools related to the development and
application of benchmark codes in system co-design, procurement or health-checking.
2. support the development and sharing of best practice in the area of benchmarking
   
We will invite speakers from across the benchmarking activities mentioned above and will also
actively seek presentations from other individuals and groups with relevant experience either
in the UK or internationally. We will also try to include at least one presentation by an
international partner to bring insights from outside the UK.

## Friday, 6 June 2025 

### Benchmarking Symposium: Benchmarking of HPC systems for simulation and AI 9.45-10:30

**Conveners: DiRAC, ExCALIBUR, UKRI Living Benchmarks**
**Lead: Mark Wilkinson**

Benchmarking is an essential part of the co-design and procurement of large-scale computing
systems, supporting the deployment of cost-e8ective, productive services. Benchmarks are
also valuable tools for obtaining quantitative information about the health of systems following
their deployment in production, for example confirming that application performance is
maintained following system software updates.

The UK has an outstanding track record of the successful use of science benchmarks to
optimise the design of large-scale computing services. There are a number of recent and
currently active projects in this area, including the ExCALIBUR Benchmarking project, the
ExCALIBUR BASE-II project, the UKRI Living Benchmarks project and the DiRAC-4 design
process. As UKRI develops its plans for the services which will comprise the future DRI
ecosystem, a workshop to discuss the benefits and challenges of e8ective benchmarking is
particularly timely.

The goals of this workshop are to:

1. share experiences (both positive and negative) and tools related to the development and
application of benchmark codes in system co-design, procurement or health-checking.
2. support the development and sharing of best practice in the area of benchmarking
   
We will invite speakers from across the benchmarking activities mentioned above and will also
actively seek presentations from other individuals and groups with relevant experience either
in the UK or internationally. We will also try to include at least one presentation by an
international partner to bring insights from outside the UK.


### WHPC: 11:00-12:30 

**Convener: Eleanor Broadway (EPCC)**

Organised by representatives from the Women in High Performance Computing (WHPC) community, this session will explore new, sustainable and realistic strategies for improving and supporting the diversity in our community. Don’t miss this opportunity to be part of the conversation on overcoming our current barriers to change, exploring the crucial role of funders and leaders, and discovering how we can all contribute to a more inclusive future in HPC and beyond.

More details coming soon! 

### Numerical Relativity: 9:45-10:30 and 11:00-12:30 

**Convener: Han Zhang**

More details coming soon! 

### CoSeC: 13:30-15:00 and 15:30-17:00

**Conveners: Stephen Longshaw (UKRI STFC), Damian Jones (UKRI STFC)**

More details coming soon! 


### HPC/HTC in High-Energy Physics: 13:30-15:00  
      
**Convener: Enrico Bothmann (CERN), Luigi del Debbio (Edinburgh), Marek Schoenherr (Durham)**

Speakers:  

- Daniel Maitre (Durham)

- Enrico Bothmann (CERN)

- Konrad Helms (Goettingen)

- Daniele Massaro (CERN)
 

