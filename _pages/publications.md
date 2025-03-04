---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.co.in/citations?user=yymAYRoAAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Color code: <span style="color:orange">**Orange**</span>: journal, <span style="color:green">**Green**</span>: conference, <span style="color:purple">**Purple**</span>: workshop.
- **Hyena: Balancing Packing, Reuse, and Rotations for Encrypted Inference**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Shreyas Singh, Sumanth Gudaparthi, Xiong Fan, Rajeev Balasubramonian  
(accepted, yet to appear at) <span style="color:green">**IEEE Symposium on Security and Privacy 2024**</span>    
\[[Full Text](https://sarabjeetsingh007.github.io/files/sp24.pdf)\]  
- **XCRYPT: Accelerating Lattice Based Cryptography with Memristor Crossbar Arrays**    
<span style="text-decoration:underline">Sarabjeet Singh</span>, Xiong Fan, Ananth Krishna, Lia Jin, Anirban Nag, 
Mahdi Bojnordi, Rajeev Balasubramonian, Elaine Shi  
<span style="color:orange">**IEEE Micro 2023**</span>  
\[[Full Text](https://sarabjeetsingh007.github.io/files/micro23.pdf)\]  
- **HyGain: High Performance, Energy-Efficient Hybrid Gain Cell based Cache Hierarchy**    
<span style="text-decoration:underline">Sarabjeet Singh</span>, Neelam Surana, Kailash Prasad, Pranjali Jain, Joycee Mekie, Manu Awasthi   
<span style="color:orange">**ACM TACO 2022**</span>  
\[[Full Text](https://sarabjeetsingh007.github.io/files/taco22.pdf)\]  
- **EPIC: Efficient Packing for Inference using Cheetah**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Shreyas Singh, Rajeev Balasubramonian  
<span style="color:purple">**CogArch 2022**</span>    
\[[Full Text](https://sarabjeetsingh007.github.io/files/cogarch22.pdf)\]  
- **CANDLES: Channel-Aware Novel Dataflow-Microarchitecture Co-Design for Low Energy Sparse Neural Network Acceleration**  
Sumanth Gudaparthi, <span style="text-decoration:underline">Sarabjeet Singh</span>, Surya Narayanan, Rajeev Balasubramonian, Visvesh Sathe  
<span style="color:green">**IEEE HPCA 2022**</span>    
\[[Full Text](https://sarabjeetsingh007.github.io/files/hpca22.pdf)\]  
- **Efficacy of Statistical Sampling on Contemporary Workloads: The Case of SPEC CPU2017**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Manu Awasthi  
<span style="color:green">**IEEE IISWC 2019**</span>   
\[[Full Text](https://sarabjeetsingh007.github.io/files/iiswc19.pdf)\]  
<span style="color:red">**Traces of Simulation Points available, contact me!**</span>
- **Memory Centric Characterization and Analysis of SPEC CPU2017 Suite**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Manu Awasthi  
<span style="color:green">**ACM/SPEC ICPE 2019**</span>   
\[[Full Text](https://sarabjeetsingh007.github.io/files/icpe19.pdf)\]
- **PANE: Pluggable Asynchronous Network-on-Chip Simulator**  
Sneha N. Ved, <span style="text-decoration:underline">Sarabjeet Singh</span>, Joycee Mekie  
<span style="color:orange">**ACM JETC 2019**</span>   
\[[Full Text](https://sarabjeetsingh007.github.io/files/jetc19.pdf)\], \[[Code](https://github.com/sarabjeetsingh007/PANE)\]  
<span style="color:red">**PANE is open-source, available here!**</span>

Current/Past Projects
======
- **Efficient Integrity Verification using Custom DIMM**  
Reducing the cost of integrity verification in trusted environments with near-memory support.  
Jan'21 - Present
- **ZPU: Zero-Knowledge Proof Processing Units**  
Novel high throughput Processing units for MSM/NTT kernels to maximize throughput in ZKP.   
Aug'23 - Present 
- **Reducing expensive Key movement in FHE using Processing in Memory**  
Partitioning FHE kernels on CPU-UPMEM model.   
May'23 - Present 
- **Secure AI using Samsung's AxDIMM (One of the finalist for Samsung AxDIMM contest)**  
Finalists for Samsung AxDIMM contest.  
Oct'21 - Jun'22 
- **Efficient Metadata for Memory Protection**    
Aug'20 - Mar'21
- **AMBOP: Adaptive Multiple Best Offset Prefetcher**    
Mar'19 - Aug'19

Blogs
======
- **Post Quantum Cryptography**  
ACM SigArch Computer Architecture Today Blog, Feb'21  
\[[Read here!](https://www.sigarch.org/post-quantum-cryptography/)\]
