# Tutorials

<a label="ftorch" />

## ICCS: FTorch
Presenter: Joe Wallwork, Tom Meltzer (ICCS, Cambridge)
- Monday 11:00 - 12:30 - Session 1

Description: t.b.d.

<a label="SmartSim" />

## HPE: SmartSim
Presenter: Alessandro Rigazzi (HPE), Holly Judge (HPE)
- Monday 13:30 - 15:00 - Session 1
- Monday 15:00 - 15:30 - Coffee break 
- Monday 15:30 - 17:00 - Session 2

As machine learning (ML) becomes more prevalent, it is unsurprising that using ML in combination with scientific HPC simulations has become more popular. Coupling HPC and ML in this way can improve the overall efficiency of HPC workflows by allowing ML predictions to help guide or replace parts of simulations.
However, there are challenges coupling the two approaches as HPC applications are typically written in C, C++ or Fortran and run on CPUs, whereas ML frameworks are usually Python based and benefit from being run on GPUs. In this tutorial we will introduce SmartSim, an open-source framework that has been developed to help address these challenges and allow researchers to easily adapt their traditional HPC workloads to include ML.  
 
In this two-part tutorial we will aim to familiarise the audience with SmartSim and demonstrate how it can be used to integrate ML into their own applications. In the first session we will give an overview of SmartSim and show it can interact with simulation data in HPC applications in order to integrate ML models. We will also show real examples of how SmartSim has been used in different fields of research such as Computational Fluid Dynamics and Climate Modelling. We also explain what needs to be done to integrate SmartSim into an application and to deploy the resulting workflow. 
 
The second session will take a more hands-on approach where attendees can run examples of hybrid scientific simulation/AI workflows using SmartSim.  Attendees will learn how to launch SmartSim leveraging the system’s native batch scheduler and job launcher and gain a practical understanding of the modifications required to adapt HPC applications to use ML.  
 
There would be an opportunity to discuss how users’ individual applications could be modified to use SmartSim. 

<a label="amd" />

## AMD: Simplify your HPC Application Port to GPUs - OpenMP and Managed Memory on AMD MI300A and MI300X 
Presenter: Bob Robey (AMD)
- Tuesday 9:00-10:30 - Session 1
- Tuesday 10:30-11:00 - Coffee break
- Tuesday 11:00-12:30 - Session 2

This will be a hands-on exploration of the new next-gen AMD Fortran and the C and C++ compiler implementation of the OpenMP offloading GPU compiler. We'll also exploit the managed memory capabilities of the APU Programming Model to make the porting much easier.

What kind of complex, real-world language constructs can these compilers handle? We look at many cases in C, C++, and Fortran. Bring your complex reproducers in Fortran and C++ and we'll see if we can break the compilers.

<a label="sycl" />

## Codeplay: Accelerate your code on GPUs and more using C++ and SYCL
Presenter: t.b.c. (Codeplay) 
- Tuesday 13:30 - 15:00 - Session 1
- Tuesday 15:00 - 15:30 - Coffee break 
- Tuesday 15:30 - 17:00 - Session 2

Parallel programming can be used to take advantage of heterogeneous architectures including GPUs, FPGAs, XPUs, IPUs, TPUs or special units on CPUs to significantly increase the performance of applications. SYCL is an open standard programming model that is defined by the industry and lets developers support many of these processors from different vendors using a single code base and only modern standard C++ code.

This tutorial will give software developers the knowledge they need to begin developing parallel applications using C++ and the SYCL programming model. Our goal is to equip attendees with the skills they need to build highly performant applications that can be used in the fields of HPC and AI and deployed to multiple hardware platforms. We will cover the fundamentals of the SYCL programming model before moving to more advanced topics. We will explore how SYCL can be used to write serious applications, covering intermediate to advanced features of SYCL as well as some of the tools and libraries that support SYCL application development.
This is a hands-on tutorial, attendees will work through exercises that represent key design patterns encountered by people who program heterogeneous systems and deploy this code to multiple processors from different vendors.

<a label="lustre" />

## Lustre User Group: Darshan profiling on Lustre 
Presenters: Robert Esnouf, Gareth Wilson 
- Tuesday 9:00-10:00 - Talks
  - 9:00-9:05 - Welcome
  - 9:05-9:25 - Paul Ingram, Red Oak Consulting, Lustre PFL
  - 9:25-9:45 - David Ford, Oxford, Tiering to tape
  - 9:45-10:05 - TBC
- Tuesday 10:10-10:30 - Account sign up for Darshan Tutorial
  - Please bring a laptop with internet access and SSH client
- Tuesday 10:30-11:00 - Coffee break
- Tuesday 11:00-12:30 - Darshan introduction and tutorial - Rich Mansfield, DDN.

Description: Boost Your Code's Performance with Darshan! Lustre User Group (LUG) UK Summer Workshop @ Durham HPC Days.

Join us for the LUG UK Summer Workshop at Durham HPC Days, featuring
an interactive tutorial on I/O profiling with Darshan to help you
learn to optimize your code's I/O performance, plus talks from Lustre
Users and Experts.

 
What's in it for you?
- Learn to profile your code: Discover how Darshan can reveal your application's I/O bottlenecks.
- Optimize your I/O: Gain practical skills to improve data read/write efficiency for faster execution.
- Lustre User Insights: Hear from experienced Lustre users sharing their tips and tricks.
- Networking: Connect with fellow HPC enthusiasts and experts.

### Ready to take your I/O to the next level?
Register via the HPC Days registration link.  Space is limited, so don't miss out - we look forward to seeing you there.
