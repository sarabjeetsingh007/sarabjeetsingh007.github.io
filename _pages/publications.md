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
- **CANDLES: Channel-Aware Novel Dataflow-Microarchitecture Co-Design for Low Energy Sparse Neural Network Acceleration**  
Sumanth Gudaparthi, <span style="text-decoration:underline">Sarabjeet Singh</span>, Surya Narayanan, Rajeev Balasubramonian, Visvesh Sathe  
to appear at <span style="color:green">**IEEE HPCA 2022**</span> 
- **HyGain: High Performance, Energy-Efficient Hybrid Gain Cell based Cache Hierarchy**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Neelam Surana, Pranjali Jain, Joycee Mekie, Manu Awasthi  
\[[available on arxiv](https://arxiv.org/abs/2110.01208)\] 
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
<span style="text-decoration:underline">Sarabjeet Singh</span>, Shreyas Singh, Rajeev Balasubramonian, Siddharth Chhabra (NVIDIA), Frank Mckeen (Intel)  
Jan'21 - Present
- **Packing and Dataflow for Homomorphic Encryption based Machine Learning Accelerator**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Xiong Fan (Algorand), Shreyas Singh, Sumanth Gudaparthi, Rajeev Balasubramonian, Elaine Shi (CMU)  
Aug'21 - Present
- **Loss-less FHE-based CNNs - performing non-linear layers on encrypted data**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Shreyas Singh, Rajeev Balasubramonian  
Aug'21 - Present
- **Hardware-Software Co-design for accelerating Post Quantum Cryptography**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Xiong Fan (Algorand), Ananth Krishna, Lia Jin, Anirban Nag (Uppsala University), 
Mahdi Bojnordi, Rajeev Balasubramonian, Elaine Shi (CMU)  
Nov'20 - Present
- **Secure AI using Samsung's AxDIMM (One of the finalist for Samsung AxDIMM contest)**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Ananth Krishna, Shreyas Singh, Lin Jia, Rajeev Balasubramonian  
Oct'21 - Present
- **Efficient Metadata for Memory Protection**  
<span style="text-decoration:underline">Sarabjeet Singh</span>, Meysam Taassori, Rajeev Balasubramonian, Siddharth Chhabra (Intel)  
Aug'20 - Mar'21
- **AMBOP: Adaptive Multiple Best Offset Prefetcher**  
Archit Checker, Arup Mondal, <span style="text-decoration:underline">Sarabjeet Singh</span>, Manu Awasthi  
Mar'19 - Aug'19

Blogs
======
- **Post Quantum Cryptography**  
ACM SigArch Computer Architecture Today Blog, Feb'21  
\[[Read here!](https://www.sigarch.org/post-quantum-cryptography/)\]