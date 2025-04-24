# Talks schedule

## Tuesday, 3 June 2025

<table border="0">
<tr>
<td><b>Time</b></td>
<td><b>Talk</b></td>
<td><b>Who</b></td>
<td></td>
</tr>
  
<tr>
<td>16:30 - 16:50</td>
<td>Isambard-AI and Isambard 3: Democratising the User Experience for AI and simulation HPC</td>
<td>Richard Gilham</td>
<td><a href="https://durham.readthedocs.io/en/latest/hpcdays/talks.html#isambard-ai-and-isambard-3-democratising-the-user-experience-for-ai-and-simulation-hpc">details</a></td>
</tr>

<tr>
<td>16:50 - 17:10</td>
<td>The HPC Hardware Lab at Durham University</td>
<td>Alastair Basden</td>
<td></td>
</tr>

<tr>
<td>17:10 - 17:30</td>
<td>Commissioning Aire, a new HPC system at The University of Leeds</td>
<td>Andrew Harvie</td>
<td></td>
</tr>

<tr>
<td>17:30 - 17:50</td>
<td>Delivering Training with a mini HPC built from Raspberry Pis</td>
<td>Jannetta Steyn</td>
<td></td>
</tr>

</table>

## Abstracts
### Isambard-AI and Isambard 3: Democratising the User Experience for AI and simulation HPC
**Who:** Richard Gilham, Bristol Centre for Supercomputing 
**Abstract:** Isambard-AI and Isambard 3 offer a unique opportunity to rethink how we build supercomputers, from the data centre to the User Experience. The rapid adoption of AI, and indeed simulation HPC, across traditional and new research sectors has resulted in new communities of users to emerge with distinct requirements and skillsets. After introducing the Isambard supercomputers, this talk will explore our approach to User Experience and how it acts as a useful lens for decision-making when creating and maintaining an HPC service.

### The HPC Hardware Lab at Durham University
**Who:** Alastair Basden, Durham University
**Abstract:** The Durham HPC Hardware Lab is hosted by the DiRAC COSMA HPC facility and provides UK researchers with access to cutting edge technologies and facilities, to allow testing of codes, software migration to new hardware, and study of new paradigms. This lab has grown in scope over the past few years, funded by ExCALIBUR H&ES, DiRAC, Durham and various UKRI grants. Of particular interest to many users is access to new GPU systems, novel networking topologies, composable infrastructure, and access to BlueField DPUs. In addition to compute hardware, the Hardware Lab includes data centre-scale technologies, such as solar power generation, immersion cooling and waste heat storage. This talk presents the Hardware Lab, including information about how it can be accessed.

### Commissioning Aire, a new HPC system at The University of Leeds
**Who:** Andrew Harvie, University of Leeds
**Abstract:** Since the end of 2024, the Research Computing Team at the University of Leeds have been working on bringing online our new HPC system, Aire, while at the same time decommissioning our previous systems, ARC3 and ARC4. Aire represents a significant improvement in capability over the previous systems, most notably with a 7-fold increase in the number of available GPUs, accounting for the rapidly increasing demand for GPU compute in AI/ML applications. Deciding on a specification for the new system – particularly regarding GPU capabilities – required careful balancing of expected current and future use cases with considerations of time pressure and market factors. On the new system, we also decided to move to a new scheduler (Slurm, from Grid Engine). With completely new hardware and software platforms, we were free to start afresh in defining usage/support policies, system configurations, and documentation.

In this talk I will discuss how we are approaching the ongoing commissioning of the new system, including:
 - Balancing supporting pre-existing workflows with the desire to keep a slim common software environment,
 - Choosing GPUs; balancing cost and availability vs performance and FP64 support when deciding between L40S and H100 cards,
 - Encouraging best practices from HPC users; balancing software engineering with social engineering for best security, reproducibility and system performance,
 - Onboarding first test users; managing expectations and being useful to researchers while extracting useful testing information,
 - How and when to write user documentation during active commissioning.
 - Lessons learnt for (very near) future HPC systems. 

### Delivering Training with a mini HPC built from Raspberry Pis
**Who:** Jannetta Steyn, Newcastle University
**Abstract:** Building an HPC with Raspberry Pis might sound like something entertaining that you should do on a Sunday afternoon during that "long dark tea-time of the soul" but, in actual fact, it is no menial task. In this presentation I'll walk the audience through the process of selecting hardware and software and the pitfalls in building a working mini HPC with single board computers such as the Raspberry Pi. I will finally talk a bit about practical applications of the mini-HPC, particularly as a training tool where students can get to grips with a real HPC system in a safe setting where the consequences of making mistakes are minimal.
