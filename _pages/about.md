---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Biography

I am a software engineer working on **core database engine development** at Salesforce, with a focus on:
- **Cloud-native, distributed OLTP systems**: transaction processing, asynchronous networking, replication, and fault tolerance for large-scale production databases.
- **AI agents for database infrastructure**: applying LLMs and data-driven agents to feature rollout, incident diagnosis, and operational automation. I am particularly interested in the intersection of **database systems, distributed systems, and AI-native infrastructure**.

I approach system building with a strong sense of pragmatism, caring deeply about **production impact**, product quality, and the **people** who build, operate, and rely on these systems. I value **structured thinking** when navigating complex design spaces, and I am motivated by building systems that are not only correct and scalable, but also usable and humane.

I received my Ph.D. in Computer Sciences from the University of Wisconsin–Madison, where I worked with Prof. Xiangyao Yu. My research focused on transaction processing and cloud-native databases, with publications at SIGMOD, VLDB, and FAST. During my Ph.D., I also collaborated with industry research labs including Microsoft Research, Meta, and AWS Redshift.

## Latest

<br><span style="color:rgb(64, 115, 158)">[Dec. 2023]</span> Joined Salesforce, working on core database engine development for a cloud-native distributed OLTP system.
<br><span style="color:rgb(64, 115, 158)">[Sep. 2022] &#128293;</span> **Cornus**, optimized two-phase commit for Cloud OLTP, has been accepted to VLDB 2022 (presented in 2023)!
<br><span style="color:rgb(64, 115, 158)">[Mar. 2022]</span> How Good is My HTAP System, has been accepted to SIGMOD 2022!
<br><span style="color:rgb(64, 115, 158)">[Oct. 2021] &#128293;</span> Awarded the **2021-2022 Microsoft Research PhD Fellowship (US & Canada)**!
<br><span style="color:rgb(64, 115, 158)">[Mar. 2021] &#128293;</span> **Bamboo**, optimized two-phase locking for high contention, has been accepted to SIGMOD 2021!
<br><span style="color:rgb(64, 115, 158)">[Dec. 2020]</span> Non-Hierarchical Caching, a generic method to optimize caching for Persistent Memory hierarchies, has been accepted to **FAST 2021**!

## Publications 

<b>Cornus: Atomic Commit for Cloud DBMS with Storage Disaggregation</b>
<br><span style="color:rgb(64, 115, 158)">*Zhihan Guo*</span>, Xinyu Zeng, Kan Wu, Wuh-Chwen Hwang, Ziwei Ren, Xiangyao Yu, Mahesh Balakrishnan, Philip A. Bernstein
<br>VLDB'2022 
<a href="https://www.vldb.org/pvldb/vol16/p379-guo.pdf">[*paper*]</a> <a href="https://arxiv.org/pdf/2102.10185.pdf">[*extended version*]</a>

<b>How Good is My HTAP System?</b>
<br>Elena Milkai, Yannis Chronis, Kevin Gaffney, <span style="color:rgb(64, 115, 158)">*Zhihan Guo*</span>, Jignesh Patel, Xiangyao Yu
<br>SIGMOD'2022

<b>Releasing Locks As Early As You Can: Reducing Contention of Hotspots by Violating Two-Phase Locking</b>
<br><span style="color:rgb(64, 115, 158)">*Zhihan Guo*</span>, Kan Wu, Cong Yan, Xiangyao Yu 
<br>SIGMOD'2021 <a href="files/rdm447-guoA.pdf">[*paper*]</a> <a href="https://arxiv.org/pdf/2103.09906.pdf">[*extended version*]</a>

<b>The Storage Hierarchy is Not a Hierarchy: Optimizing Caching on Modern Storage Devices with Orthus</b>
<br>Kan Wu, <span style="color:rgb(64, 115, 158)">*Zhihan Guo*</span>, Guanzhou Hu, Kaiwei Tu, Ramnatthan Alagappan, Rathijit Sen, Kwanghyun Park, Andrea Arpaci-Dusseau and Remzi Arpaci-Dusseau 
<br>FAST'2021 <a href="https://research.cs.wisc.edu/adsl/Publications/fast21-kan.pdf">[*paper*]</a> 

<b>The Storage Hierarchy is Not a Hierarchy: Optimizing Caching on Modern Storage Devices with Orthus</b>
<br>Kan Wu, <span style="color:rgb(64, 115, 158)">*Zhihan Guo*</span>, Guanzhou Hu, Kaiwei Tu, Ramnatthan Alagappan, Rathijit Sen, Kwanghyun Park, Andrea Arpaci-Dusseau and Remzi Arpaci-Dusseau 
<br>NVMW'2021 <a href="https://research.cs.wisc.edu/adsl/Publications/nvmw21-kan.pdf">[*paper*]</a> 

<b>A Statistical Perspective on Discovering Functional Dependencies in Noisy Data</b>
<br>Yunjia Zhang, <span style="color:rgb(64, 115, 158)">*Zhihan Guo*</span> and Theodoros Rekatsinas 
<br>SIGMOD'2020 <a href="http://pages.cs.wisc.edu/~zhihan/publications/mod0552-zhangA.pdf">[*paper*]</a>  <a href="https://github.com/sis-ethz/Profiler-Public">[*code*]</a> 

<b>Unsupervised Functional Dependency Discovery for Data Preparation</b>
<br><span style="color:rgb(64, 115, 158)">*Zhihan Guo*</span> and Theodoros Rekatsinas 
<br>ICLR'2019, Learning from Limited Data Workshop <a href="https://openreview.net/pdf?id=B1eos4meuV">[*paper*]</a> <a href="https://arxiv.org/abs/1905.01425">[*extended version*]</a>  <a href="files/ICLR_poster_final_tiff.tiff">[*poster*]</a>

<b>Data profiling methods for interactive data cleaning</b>
<br><span style="color:rgb(64, 115, 158)">*Zhihan Guo*</span> and Theodoros Rekatsinas 
<br>MMLS'2018

## Research & Work Experience

<img style="float: left; box-shadow: 4px 4px 8px #888; margin-right: 15px;" src="images/logo/salesforce-logo.png" width="80px" >
<b>Senior Member of Technical Staff</b><br><a href="https://aws.amazon.com/redshift/">Salesforce</a>, SDB, in San Francisco, CA<br> 2023.12 - present

<img style="float: left; box-shadow: 4px 4px 8px #888; margin-right: 15px;" src="images/logo/uwm-logo.png" width="80px" >
<b>Research Assistant</b><br><a href="https://database.cs.wisc.edu/">UW-Madison Database Group</a> in Madison, WI<br>2018.02 - 2023.12

<img style="float: left; box-shadow: 4px 4px 8px #888; margin-right: 15px;" src="images/logo/aws-logo.png" width="80px" >
<b>Software Engineer Intern</b><br><a href="https://aws.amazon.com/redshift/">Amazon</a>, Redshift, in East Palo Alto, CA<br> 2022.06 - 2022.09

<img style="float: left; box-shadow: 4px 4px 8px #888; margin-right: 15px;" src="images/logo/ms-logo.png" width="80px" >
<b>Affiliate Research Assistant</b><br><a href="https://www.microsoft.com/en-us/research/group/gray-systems-lab/">Microsoft Research GSL</a> in Madison, WI<br>2021.08 - 2022.06

<img style="float: left; box-shadow: 4px 4px 8px #888; margin-right: 15px;" src="images/logo/fb-logo.png" width="80px" >
<b>Software Engineer Intern in System & Infrastructure</b><br><a href="https://research.fb.com/category/systems-infrastructure/">Facebook</a>, Delos Team, in Seattle, WA<br>Summer 2021 

<img style="float: left; box-shadow: 4px 4px 8px #888; margin-right: 15px;" src="images/logo/uwm-logo.png" width="80px" >
<b>Research Assistant</b><br><a href="https://hci.cs.wisc.edu/">UW-Madison HCI Group</a> in Madison, WI<br>2017.02 - 2018.05

<img style="float: left; box-shadow: 4px 4px 8px #888; margin-right: 15px;" src="images/logo/hm-logo.jpg" width="80px" >
<b>Research Assistant</b><br><a href="https://centerhealthyminds.org/">Center for Healthy Minds</a> in Madison, WI<br>2017.01 - 2017.09

<img style="float: left; box-shadow: 4px 4px 8px #888; margin-right: 15px;" src="images/logo/waisman-logo.png" width="80px" >
<b>Research Assistant</b><br><a href="https://childemotion.waisman.wisc.edu/">Child Emotion Lab @ Waisman Center</a> in Madison, WI<br>2016.01 - 2017.09

## Teaching
Teaching Assistant for [CS564 Database Management Systems](https://klklassy.com/cs564-fall19/), Fall 2019

