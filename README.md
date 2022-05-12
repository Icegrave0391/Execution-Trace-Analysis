# Provenance & Execution Trace & Data Flow Analysis


## Dataset
The *[Exploit Database](https://www.exploit-db.com/)* - Exploits, Shellcode, 0days, Remote Exploits, Local Exploits, Web Apps, Vulnerability Reports, Security Articles, Tutorials and more.

### Runtime effiency
To evaluate runtime effiency of the approach or profiling, there are several benchmarks: Apache's benchmarking tool [ab](https://httpd.apache.org/docs/2.4/programs/ab.html), SQLite's performance tests, MySQL's benchmarking tool, and some other published benchmarks.    

To measure performance overhead for MySQL, httpd, and SQLite, we measure the drop in throughput and for all the other benchmarks, we measure the increase in runtime.

- A Case for an Interleaving Constrained Shared-Memory Multi-Processor. J Yu, et al. ISCA'2009 [paper](https://web.eecs.umich.edu/~nsatish/papers/ISCA-09-CPC.pdf)

## SIEM

### Root Cause Diagnosis
- ARCUS: Symbolic Root Cause Analysis of Exploits in Production Systems. C Yagemann, et al. Security'2021 [paper](https://www.usenix.org/system/files/sec21fall-yagemann.pdf)
- Execution Reconstruction: Harnessing Failure Reoccurrences for Failure Reproduction. G Zuo, et al. PLDI'2021 [paper](https://web.eecs.umich.edu/~barisk/public/er.pdf)
- WATCHER: In-Situ Failure Diagnosis. H Liu, et al.OOPSLA'2020. [paper](https://people.umass.edu/tongping/pubs/Watcher_OOPSLA20.pdf)
- AURORA: Statistical Crash Analysis for Automated Root Cause Explanation. T Blazytko, et al. Security'2020 [paper](https://www.usenix.org/system/files/sec20fall_blazytko_prepub.pdf)
- The Inflection Point Hypothesis: A Principled Debugging Approach for Locating the Root Cause of a Failure. Y Zhang, et al. SOSP'2019 [paper](http://www.cs.otago.ac.nz/cosc440/readings/inflection_point.pdf)
- DEEPVSA: Facilitating Value-set Analysis with Deep Learning for Postmortem Program Analysis. W Guo, D Mu, et al. Security'2019 [paper](https://www.usenix.org/system/files/sec19-guo.pdf)
- POMP++: Facilitating Postmortem Program Diagnosis with Value-set Analysis. D Mu, et al. TSE'2019 [paper](https://mudongliang.github.io/files/papers/pomp++.pdf)
- Root Cause Localization for Unreproducible Builds via Causality Analysis over System Call Tracing. Z Ren, et al. ASE'2019 [paper](https://taoxie.cs.illinois.edu/publications/ase19-reptrace.pdf)
- REPT: Reverse Debugging of Failures in Deployed Software. W Cui, et al. OSDI'2018 [paper](https://www.usenix.org/system/files/osdi18-cui.pdf)
- Lazy Diagnosis of In-Production Concurrency Bugs. B Kasikci, et al. SOSP'2017 [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/09/snorlax-sosp17.pdf)
- Postmortem Program Analysis with Hardware-Enhanced Post-Crash Artifacts. J Xu, et al. Security'2017 [paper](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-xu.pdf)
- ProRace: Practical Data Race Detection for Production Use. T Zhang, et al. ASPLOS'2017 [paper](https://www3.cs.stonybrook.edu/~dongyoon/papers/ASPLOS-17-ProRace.pdf)
- Credal: Towards Locating a Memory Corruption Vulnerability with Your Core Dump. J Xu, et al. SIGSAC'2016 [paper](http://xinyuxing.org/pub/p529-xu.pdf)
- RETracer: Triaging Crashes by Reverse Execution from Partial Memory Dumps. W Cui, et al. ICSE'2016 [paper](https://softsec.kaist.ac.kr/~sangkilc/papers/cui-icse16.pdf)
- Failure Sketching: A Technique for Automated Root Cause Diagnosis of In-Production Failures. B Kasikci, et al. SOSP'2015 [paper](https://dslab.epfl.ch/pubs/gist.pdf)
- HOLMES: Effective Statistical Debugging via Efficient Path Profiling. T Chilimbi, et al. ICSE'2009 [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/Holmes20-20Effecitve20Statistical20Debugging20via20Efficient20Path20Profiling.pdf)
- PRES: Probabilistic Replay with Execution Sketching on Multiprocessors. W Xiong, et al. SOSP'2009 [paper](https://www.sigops.org/s/conferences/sosp/2009/papers/park-sosp09.pdf)
- PSE: Explaining Program Failures via Postmortem Static Analysis. R Manevich, et al. FSE'2004 [paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.188.9374&rep=rep1&type=pdf)

### CFI
- Enforcing Unique Code Target Property for Control-Flow Integrity. H Hu, et al. CCS'2018 [paper](https://huhong789.github.io/papers/ucfi.pdf)
- Origin-sensitive Control Flow Integrity. M Khandaker, et al. Security'2019 [paper](https://www.usenix.org/system/files/sec19-khandaker.pdf)
- Efficient Protection of Path-Sensitive Control Security. R Ding, et al. Security'2017 [paper](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-ding.pdf)
- GRIFFIN: Guarding Control Flows Using Intel Processor Trace. X Ge, et al. ASPLOS'2017 [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/01/griffin-asplos17.pdf)
- PT-CFI: Transparent backward-edge control ﬂow violation detection using intel processor trace. Y Gu, et al. CODASPY'2017 [paper](http://web.cse.ohio-state.edu/~zhao.2708/assets/codaspy17/CODASPY17.pdf)

### System Diagnosis
- Argus: Debugging Performance Issues in Modern Desktop Applications with Annotated Causal Tracing. L Weng, et al. ATC'2021 [paper](https://www.usenix.org/system/files/atc21-weng.pdf)
- The Inflection Point Hypothesis: A Principled Debugging Approach for Locating the Root Cause of a Failure. Y Zhang, et al. SOSP'2019 [paper](http://www.cs.otago.ac.nz/cosc440/readings/inflection_point.pdf)

### Provenance Analysis

- Back-Propagating System Dependency Impact for Attack Investigation. P Fang, et al. Security'2022 [paper](https://www.usenix.org/system/files/sec22summer_fang.pdf)
- Forensic Analysis of Configuration-based Attacks. M Inam, et al. NDSS'2021 [paper](https://www.ndss-symposium.org/wp-content/uploads/2022-57-paper.pdf)
- Validating the Integrity of Audit Logs Against Execution Repartitioning Attacks. C Yagemann, et al. CCS'2021
- Causal Analysis for Software-Defined Networking Attacks. B Ujcich, et al. Security'2021 [paper](https://www.usenix.org/system/files/sec21-ujcich.pdf)
- OmegaLog: High-Fidelity Attack Investigation via Transparent Multi-layer Log Analysis. W Hassan, et al. NDSS'2020 [paper](https://whassan3.web.engr.illinois.edu/papers/hassan-ndss20.pdf)
- Rain: Refinable Attack Investigation with On-demand Inter-Process Information Flow Tracking. Y Ji, et al. CCS'2017 [paper](https://taesoo.kim/pubs/2017/ji:rain.pdf)
- Enabling Refinable Cross-Host Attack Investigation with Efficient Data Flow Tagging and Tracking. Y Ji, et al. Security'2018 [paper](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-ji.pdf)

### Bug Detection

- OpenRace: An Open Source Framework for Statically Detecting Data Races. B Swain, et al. HPCA'2021 [paper](https://ieeexplore.ieee.org/document/9651289)
- Automated Bug Hunting With Data-Driven Symbolic Root Cause Analysis. C Yagemann, et al. CCS'2021 [paper](https://dl.acm.org/doi/abs/10.1145/3460120.3485363)

## Taint Analysis

### Taint Acceleration
- SELECTIVETAINT: Efficient Data Flow Tracking With Static Binary Rewriting. S Chen, et al. Security'2021 [paper](https://www.usenix.org/system/files/sec21fall-chen-sanchuan.pdf)
- StraightTaint: Decoupled Offline Symbolic Taint Analysis. J Ming, et al. ASE'2016 [paper](https://faculty.ist.psu.edu/wu/papers/StraightTaint-ASE16.pdf)
- TaintPipe: Pipelined Symbolic Taint Analysis. J Ming, et al. Security'2015 [paper](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-ming.pdf)
- A General Approach for Efficiently Accelerating Software-based Dynamic Data Flow Tracking on Commodity Hardware. K Jee et, al. NDSS'2012 [paper](https://liberty.princeton.edu/Publications/ndss12_tfa.pdf)

### Static Taint
- Statically Discovering High-Order Taint Style Vulnerabilities in OS Kernels. H Zhang, et al. CCS'2021 [paper](https://www.cs.ucr.edu/~zhiyunq/pub/ccs21_static_high_order.pdf)
- NTFUZZ: Enabling Type-Aware Kernel Fuzzing on Windows with Static Binary Analysis. J Choi, et al. SP'2021 [paper](https://softsec.kaist.ac.kr/~jschoi/data/oakland2021.pdf)
- Razzer: Finding Kernel Race Bugs through Fuzzing. D Jeong, et al. SP'2019 [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8835326)
- K-Miner: Uncovering Memory Corruption in Linux. D Gens, et al. NDSS'2018 [paper](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_05A-1_Gens_paper.pdf)

### Indirect Call Resolve
- Refining Indirect Call Targets at the Binary Level. S Kim, et al. NDSS'2021 [paper](http://www.cse.psu.edu/~gxt29/papers/cfgByDatalog_NDSS21.pdf)


### Deobfuscation
- QSynth - A Program Synthesis based Approach for Binary Code Deobfuscation. R David, et al. Binary Analysis Research Workshop,NDSS'2020 [paper](https://archive.bar/pdfs/bar2020-preprint9.pdf)

### Coredump Analysis
- CREDAL: Towards Locating a Memory Corruption Vulnerability with Your Core Dump. J Xu, et al. SIGSAC'2016 [paper](https://www.semanticscholar.org/paper/CREDAL%3A-Towards-Locating-a-Memory-Corruption-with-Xu-Mu/fb69ca4ce65a5c796f6247559205322e9796f2fc)

## Limitations


# Others

- Snowboard: Finding Kernel Concurrency Bugs through Systematic Inter-thread Communication Analysis. S Gong, et al. SOSP'2021
- Formal Verification of a Multiprocessor Hypervisor on Arm Relaxed Memory Hardware. R Tao, et al. SOSP'2021
- Rudra: Finding Memory Safety Bugs in Rust at the Ecosystem Scale. Y Bae, et al. SOSP'2021
