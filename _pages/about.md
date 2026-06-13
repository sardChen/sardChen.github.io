---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

**Background:** I received my Ph.D. from Tsinghua University, advised by Prof. Yu Jiang. Before that, I received my Master’s degree from the School of Software, Tsinghua University, and my Bachelor’s degree from the School of Software, Nanjing University. I am currently a Lecturer at the School of Information, Renmin University of China. My research focuses on hardware security, software security analysis, and AI security.

**Research Achievements:** I have published multiple papers in top-tier conferences such as IEEE S&P, USENIX Security, EuroSys, USENIX ATC, and ASE. My research has developed automated techniques for detecting deep and subtle security bugs in complex software and hardware-software systems, including consensus failures in blockchain systems, metadata inconsistency bugs and imbalance failures in distributed file systems, fault-dependent configuration bugs in distributed systems, vulnerabilities in Wi-Fi network devices, and security flaws in RISC-V CPUs. My work has uncovered numerous previously unknown vulnerabilities in real-world systems and devices, with **130+ CVEs** assigned and fixes adopted by vendors.

**Awards:** My work *DualFuzz: Detecting Vulnerability in Wi-Fi NICs through Dual-Directional Fuzzing* received the Distinguished Paper Award at ASE 2025. I also received the China Computer Federation’s (CCF) First Prize for Technical Invention in 2024 and was named an Outstanding Graduate of Beijing. 

**Current Research:** I am currently working on intelligent security assurance for critical software and hardware systems, with a focus on chip security, agent security, operating system security, and endpoint threat detection. My research aims to combine large language models, program analysis, dynamic testing, fuzzing, and security specification modeling to detect vulnerabilities, reason about abnormal behaviors, and improve the robustness and resilience of complex systems.




# 🔥 News

* *2026.06*:  🎉🎉 Our paper “DRVFuzz: Data-Sensitive RISC-V CPU Fuzzing” was accepted by **USENIX Security 2026**!
* *2026.03*:  🎉🎉 Our paper “RISCSmith: Finding RISC-V CPU Bugs via Rich Instruction Construction and On-the-fly Differential Analysis” was accepted by **DAC 2026**!
* *2026.01*:  🎉🎉 Our paper “VeriEQ: Finding Verilog Simulators and Synthesizers Bugs with Equivalence Circuit Transformation” was accepted by **OOPSLA 2026**!
* *2025.11*:  🎉🎉 Our paper “DualFuzz: Detecting Vulnerability in Wi-Fi NICs through Dual-Directional Fuzzing” received the **Distinguished Paper Award** at **ASE 2025**!



# 📝 Selected Publications

1. Zehong Yu, **Yuanliang Chen**<sup>✉</sup>, Zhen Yan, Xudong Zhang, Zhensheng Xian, Yu Jiang:
   DRVFuzz: Data-Sensitive RISC-V CPU Fuzzing,
   *USENIX Security Symposium*, 2026. (**Security**, CCF-A)

2. Xudong Zhang, **Yuanliang Chen**<sup>✉</sup>, Zehong Yu, Zhen Yan, Fuchen Ma, Dalong Shi, Yu Jiang:
   RISCSmith: Finding RISC-V CPU Bugs via Rich Instruction Construction and On-the-fly Differential Analysis,
   *ACM/IEEE Design Automation Conference*, 2026. (**DAC**, CCF-A)

3. Juanen Li, Peng Qian, Guanyan Li, Rui Wang, Peixin Wang, Zhiqing Tang, Fuchen Ma, **Yuanliang Chen**<sup>✉</sup>, Lun Zhang:
   EchoFuzz: Empowering Smart Contract Fuzzing with Large Language Models,
   *ACM International Conference on Software Engineering*, 2026. (**ICSE**, CCF-A)

4. Zhen Yan, **Yuanliang Chen**<sup>✉</sup>, Fuchen Ma, Zehong Yu, Dalong Shi, Yu Jiang:
   VeriEQ: Finding Verilog Simulators and Synthesizers Bugs with Equivalence Circuit Transformation,
   *ACM SIGPLAN International Conference on Object-Oriented Programming, Systems, Languages, and Applications*, 2026. (**OOPSLA**, CCF-A)

5. Fuchen Ma, **Yuanliang Chen**<sup>✉</sup>, Zhen Yan, Yuanhang Zhou, Yu Jiang, Mingchao Wan:
   Fuzzing Enterprise-Grade Blockchain Systems: Industrial Practice and Solutions,
   *ACM European Systems Conference*, 2026. (**EuroSys**, CCF-A)

6. **Yuanliang Chen**, Fuchen Ma, Yanyang Zhao, Yuanyi Li, Yu Jiang:
   DualFuzz: Detecting Vulnerability in Wi-Fi NICs through Dual-Directional Fuzzing,
   *IEEE/ACM International Conference on Automated Software Engineering*, 2025. (**ASE**, Distinguished Paper Award, CCF-A)

7. **Yuanliang Chen**, Fuchen Ma, Yanyang Zhao, Yuanyi Li, Yu Jiang:
   CAFault: Enhance Fault Injection Technique in Practical Distributed Systems via Abundant Fault-Dependent Configurations,
   *USENIX Annual Technical Conference*, 2025. (**ATC**, CCF-A)

8. **Yuanliang Chen**, Fuchen Ma, Yuanhang Zhou, Zhen Yan, Qing Liao, Yu Jiang:
   Themis: Finding Imbalance Failures in Distributed File Systems via a Load Variance Model,
   *ACM European Systems Conference*, 2025. (**EuroSys**, CCF-A)

9. **Yuanliang Chen**, Fuchen Ma, Yuanhang Zhou, Ming Gu, Qing Liao, Yu Jiang:
   Chronos: Finding Timeout Bugs in Practical Distributed Systems by Deep-Priority Fuzzing with Transient Delay,
   *IEEE Symposium on Security and Privacy*, 2024. (**S&P**, CCF-A)

10. **Yuanliang Chen**, Fuchen Ma, Yuanhang Zhou, Zhen Yan, Yu Jiang, Jiaguang Sun:
    A Survey of Dynamic Testing Methods for Distributed Systems,
    *Journal of Software*, 2024, 32(7): 1–37. In Chinese. (**JoS**, CCF-A)

11. Fuchen Ma, **Yuanliang Chen**, Yuanhang Zhou, Jingxuan Sun, Zhuo Su, Yu Jiang, Jiaguang Sun, Huizhong Li:
    Phoenix: Detect and Locate Resilience Issues in Blockchain via Context-Sensitive Chaos,
    *ACM SIGSAC Conference on Computer and Communications Security*, 2023. (**CCS**, CCF-A)

12. Fuchen Ma, **Yuanliang Chen**, Meng Ren, Yuanhang Zhou, Yu Jiang, Ting Chen, Huizhong Li, Jiaguang Sun:
    LOKI: State-Aware Fuzzing Framework for the Implementation of Blockchain Consensus Protocols,
    *Network and Distributed System Security Symposium*, 2023. (**NDSS**, CCF-A)

13. **Yuanliang Chen**, Fuchen Ma, Yuanhang Zhou, Yu Jiang, Ting Chen, Jiaguang Sun:
    Tyr: Finding Consensus Failure Bugs in Blockchain Systems with Behaviour Divergent Model,
    *IEEE Symposium on Security and Privacy*, 2023. (**S&P**, CCF-A)

14. **Yuanliang Chen**, Yu Jiang, Fuchen Ma, Jie Liang, Mingzhe Wang, Chijin Zhou, Xun Jiao, Zhuo Su:
    EnFuzz: Ensemble Fuzzing with Seed Synchronization among Diverse Fuzzers,
    *USENIX Security Symposium*, 2019. (**Security**, CCF-A)

<sup>✉</sup> Corresponding author


