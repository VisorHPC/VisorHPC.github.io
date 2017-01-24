---
layout: default
---

## News
{:id="news"}

 * Jan 24, 2017: Pre-Print of <a href="proceedings.pdf">COSH/VisorHPC proceedings</a> is online.
 * Jan 09, 2017: The (tentative) <a href="/#program">workshop program</a> is online.
 * Jan 02, 2017: This year, we've decided to merge the VisorHPC workshop with the HiPEAC's workshop on <a href="http://wwwi10.lrr.in.tum.de/~trinitic/COSH2017/">Co-Scheduling of HPC Applications</a> in order to present a comprehensive program.
 * Dec 20, 2016: We are looking forward to the <a href="/#keynote">invited keynote talk by Prof. DK Panda</a>:
 <center>
        <h3>HPC Meets Cloud: Opportunities and Challenges in Designing High-Performance MPI and Big Data Libraries on Virtualized InfiniBand Clusters</h3>
 </center>
 * Dec 20, 2016: [Call for participation!](https://www.hipeac.net/2017/stockholm) The early bird registration rate for HiPEAC 17 ends on __December 25__! Register right [here](https://www.hipeac.net/2017/stockholm/register/)!
 * Nov 30, 2016: The <a href="/#deadlines">author notification</a> has been postponed by one week to __December 07__ (Sorry for this inconvenience, but please stay tuned!)
 * Oct 31, 2016: The paper submission <a href="/#deadlines">deadline has been extended</a> by two weeks until __November 15__.
 * Oct 21, 2016: The <a href="/#committee">program committee</a> list is online.
 * Oct 03, 2016: It’s our great pleasure to announce that [Professor DK Panda](http://web.cse.ohio-state.edu/~panda/) of the Ohio State University volunteered to deliver the invited keynote talk.


## About VisorHPC
{:id="about"}

Although virtualization solutions are quite common in server farms and cloud computing environments, their usage is in contrast by far not prevalent in the domain of high-performance computing (HPC).
This is because, at least up to now, virtualization solutions like the employment of virtual machines (VM) have proven to be too heavyweight to be acceptable in scalable HPC systems.
However, future exascale systems, equipped with a much higher degree of computing power but also with a much larger amount of computing cores than today’s HPC systems, will demand for resiliency and malleability features that may only be provided by increasing likewise the degree of virtualization within the systems.
Moreover, recent advancements, e.g. concerning container-based virtualization or regarding hardware abstraction of high-performance interconnects, currently propel the idea of introducing more virtualization solutions even in the domain of HPC.
Prominent examples for such added values stemming from virtualization and fostering resiliency, usability and malleability also in HPC systems are the possibility of live-migration and transparent checkpoint/restart, as well as the option to provide each user with an individual environment in terms of customized VM images.

## Keynote Abstract
{:id="keynote"}

Significant growth has been witnessed during the last few years in HPC clusters with multi-/many-core processors, accelerators, and high-performance interconnects (such as InfiniBand, Omni-Path, iWARP, and RoCE).
To alleviate the cost burden, sharing HPC cluster resources to end users through virtualization for both scientific computing and Big Data processing is becoming more and more attractive.
The recently introduced Single Root I/O Virtualization (SR-IOV) technique for InfiniBand and High Speed Ethernet provides native I/O virtualization capabilities and is changing the landscape of HPC virtualization.
However, SR-IOV lacks locality-aware communication support, which leads to performance overheads for inter-VM communication even within the same host.
In this talk, we will first present our recent studies done on MVAPICH2-Virt MPI library over virtualized SR-IOV-enabled InfiniBand clusters, which can fully take advantage of SR-IOV and IVShmem to deliver near-native performance for HPC applications under Standalone, OpenStack, and Containers environments.
In the second part, we will present a framework for extending SLURM with virtualization-oriented capabilities, such as dynamic virtual machine creation with SR-IOV and IVShmem resources, to effectively run MPI jobs over virtualized InfiniBand clusters.
Next, we will demonstrate how high-performance solutions can be designed to run Big Data applications (like Hadoop) in HPC cloud environments. Finally, we will share our experiences of running these designs on the [Chameleon Cloud](https://www.chameleoncloud.org) testbed.

__The keynote will be delivered by Dhabaleswar K. (DK) Panda of The Ohio State University.__

DK Panda is a Professor and University Distinguished Scholar of Computer Science and Engineering at the Ohio State University.
He has published over 400 papers in the area of high-end computing and networking.
The [MVAPICH2](http://mvapich.cse.ohio-state.edu) (High Performance MPI and PGAS over InfiniBand, Omni-Path, iWARP and RoCE) libraries, designed and developed by his research group, are currently being used by more than 2,700 organizations worldwide (in 83 countries).
More than 405,000 downloads of this software have taken place from the project's site.
As of Nov’16, this software is empowering several InfiniBand clusters (including the 1st, 13th, 17th, and 40th ranked ones) in the TOP500 list.
The RDMA packages for Apache Spark, Apache Hadoop, Apache HBase, and Memcached together with OSU HiBD benchmarks from his group are also [publicly available](http://hibd.cse.ohio-state.edu).
These libraries are currently being used by more than 200 organizations in 29 countries.
More than 19,000 downloads of these libraries have taken place.
He is an IEEE Fellow.

More details about Prof. Panda are available at [http://www.cse.ohio-state.edu/~panda](http://www.cse.ohio-state.edu/~panda).

## Program
{:id="program"}

* 10:00 - 10:10 Welcome and Introduction

* 10:10 - 11:10 Keynote Talk by Prof. DK Panda:<br>
  __HPC Meets Cloud: Opportunities and Challenges in Designing High-Performance MPI and Big Data Libraries on Virtualized InfiniBand Clusters__

* Coffee Break

* 11:40 - 12:00 S. Fan, F. Chen, H. Rauchfuss, N. Har'el, U. Schilling and N. Struckmann:<br>
  __Towards a Lightweight RDMA Para-Virtualization for HPC__

* 12:00 - 12:30 T. Küstner, C. Trinitis, J. Weidendorfer, A. Blaszczyk, P. Kaufmann and M. Johansson:<br>
  __On the Applicability of Virtualization in an Industrial HPC Environment__

* 12:30 - 13:00 S. Pickartz, J. Breitbart and S. Lankes:<br>
  __Co-scheduling on Upcoming Many-Core Architectures__

* Lunch Break

* 14:15 - 15:00 Invited Talk by Dr. Mikko Byckling from Intel Finland:<br>
  __An Update on Intel Technologies for High Performance Computing__

* 15:00 - 15:30 A. de Blanche and T. Lundqvist:<br>
  __Disallowing Same-program Co-schedules to Improve Efficiency in Quad-core Servers__

* Coffee Break

* 16:00 - 16:30 I. Papadakis, K. Nikas, V. Karakostas, G. Goumas and N. Koziris:<br>
  __Improving QoS and Utilisation in modern multi-core servers with Dynamic Cache Partitioning__

* 16:30 - 16:45 HermitCore Live Demo by Dr. Stefan Lankes:<br>
  __HermitCore: A Library Operating System for Cloud and High-Performance Computing__

* 16:45 - 17:00 Wrap-up and Workshop Closing

## Workshop Topics
{:id="topics"}

___All___ __subjects concerning virtualization solutions in HPC__, especially (but not limited to):

* Employment and management of virtual machines and/or software containers in HPC
* Checkpointing and/or migration solutions for resiliency and malleability in HPC
* Solutions for network and I/O virtualization regarding HPC interconnects
* Parallel I/O and HPC storage solutions taking advantage from virtualization
* Hypervisors and other virtualization solutions tailored for HPC systems
* Virtualization solutions for dealing with heterogeneity in HPC environments
* Extensions to resource managers and job schedulers with respect to virtualization
* Adaptation of cloud-computing technologies to HPC environments
* Operating system support for virtualization in HPC systems
* Performance and power analysis of virtualized HPC systems
* Debugging and/or profiling in virtual environments


## Call for Papers
{:id="cfp"}

* Open call for papers
* All papers will be peer-reviewed
* Accepted papers will be published online
* Proceedings will be referenceable through ISBN plus DOI
* Three types of papers are welcome for submission:
  * Full (regular) research papers of 6-8 pages (will be peer-reviewed by at least 3 reviewers)
  * Short papers of up to 4 pages (may include content not yet mature enough for a full paper)
  * Industrial white papers of up to 4 pages (may present products from a technical point of view)


## Submission Guidelines

* Papers should be formatted according to the [IEEE manuscript templates](http://www.ieee.org/conferences_events/conferences/publishing/templates.html) for conferences
* Please stick to the page limits of 4 and 8 pages, respectively
* Submissions should be done via the [EasyChair submission server](https://easychair.org/conferences/?conf=visorhpc2017)


## Preliminary Deadlines
{:id="deadlines"}

* Paper submission deadline:		~~October 31~~ November 15, 2016
* Notification of acceptance:		~~November 30~~ December 07, 2016
* Camera ready due:			~~December 15~~ January 15, 2016


## Program Committee
{:id="committee"}
* Frank Bellosa, Karlsruhe Institute of Technology (KIT)
* Carsten Clauss, ParTec Cluster Competence Center GmbH
* Stefan Lankes, RWTH Aachen University
* Julián Morillo Pozo, Barcelona Supercomputing Center (BSC)
* Lena Oden, Argonne National Laboratory (ANL)
* Pablo Reble, Intel Corporation
* Josh Simons, VMware, Inc.
* Josef Weidendorfer, Technical University of Munich (TUM)


## Organizers and Contact
{:id="contact"}

* Carsten Clauss, ParTec Cluster Competence Center GmbH, Germany, Email: <clauss@par-tec.com>
* Stefan Lankes, RWTH Aachen University, Germany, Email: <slankes@eonerc.rwth-aachen.de>
