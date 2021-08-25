# Execution Trace & Data Flow Analysis


## Dataset
The *[Exploit Database](https://www.exploit-db.com/)* - Exploits, Shellcode, 0days, Remote Exploits, Local Exploits, Web Apps, Vulnerability Reports, Security Articles, Tutorials and more.

## SIEM

### Root Cause Diagnosis
- ARCUS: Symbolic Root Cause Analysis of Exploits in Production Systems. C Yagemann, et al. Security'2021 [paper](https://www.usenix.org/system/files/sec21fall-yagemann.pdf)
- Execution Reconstruction: Harnessing Failure Reoccurrences for Failure Reproduction. G Zuo, et al. PLDI'2021 [paper](https://web.eecs.umich.edu/~barisk/public/er.pdf)
- POMP++: Facilitating Postmortem Program Diagnosis with Value-set Analysis. D Mu, et al. TSE'2019 [paper](https://mudongliang.github.io/files/papers/pomp++.pdf)
- REPT: Reverse Debugging of Failures in Deployed Software. W Cui, et al. OSDI'2018 [paper](https://www.usenix.org/system/files/osdi18-cui.pdf)
- Postmortem Program Analysis with Hardware-Enhanced Post-Crash Artifacts. J Xu, et al. Security'2017 [paper](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-xu.pdf)
- DEEPVSA: Facilitating Value-set Analysis with Deep Learning for Postmortem Program Analysis. W Guo, D Mu, et al. Security'2019 [paper](https://www.usenix.org/system/files/sec19-guo.pdf)
- Failure Sketching: A Technique for Automated Root Cause Diagnosis of In-Production Failures. B Kasikci, et al. SOSP'2015 [paper](https://dslab.epfl.ch/pubs/gist.pdf)
- Lazy Diagnosis of In-Production Concurrency Bugs. B Kasikci, et al. SOSP'2017 [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/09/snorlax-sosp17.pdf)
- AURORA: Statistical Crash Analysis for Automated Root Cause Explanation. T Blazytko, et al. Security'2020 [paper](https://www.usenix.org/system/files/sec20fall_blazytko_prepub.pdf)
- Credal: Towards Locating a Memory Corruption Vulnerability with Your Core Dump. J Xu, et al. SIGSAC'2016 [paper](http://xinyuxing.org/pub/p529-xu.pdf)
- RETracer: Triaging Crashes by Reverse Execution from Partial Memory Dumps. W Cui, et al. ICSE'2016 [paper](https://softsec.kaist.ac.kr/~sangkilc/papers/cui-icse16.pdf)
- ProRace: Practical Data Race Detection for Production Use. T Zhang, et al. ASPLOS'2017 [paper](https://www3.cs.stonybrook.edu/~dongyoon/papers/ASPLOS-17-ProRace.pdf)
- HOLMES: Effective Statistical Debugging via Efficient Path Profiling. T Chilimbi, et al. ICSE'2009 [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/Holmes20-20Effecitve20Statistical20Debugging20via20Efficient20Path20Profiling.pdf)
- PRES: Probabilistic Replay with Execution Sketching on Multiprocessors. W Xiong, et al. SOSP'2009 [paper](https://www.sigops.org/s/conferences/sosp/2009/papers/park-sosp09.pdf)
- The Inflection Point Hypothesis: A Principled Debugging Approach for Locating the Root Cause of a Failure. Y Zhang, et al. SOSP'2019 [paper](http://www.cs.otago.ac.nz/cosc440/readings/inflection_point.pdf)
- PSE: Explaining Program Failures via Postmortem Static Analysis. R Manevich, et al. FSE'2004 [paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.188.9374&rep=rep1&type=pdf)
- WATCHER: In-Situ Failure Diagnosis. H Liu, et al.OOPSLA'2020. [paper](https://people.umass.edu/tongping/pubs/Watcher_OOPSLA20.pdf)

### CFI
- Enforcing Unique Code Target Property for Control-Flow Integrity. H Hu, et al. CCS'2018 [paper](https://huhong789.github.io/papers/ucfi.pdf)
- Origin-sensitive Control Flow Integrity. M Khandaker, et al. Security'2019 [paper](https://www.usenix.org/system/files/sec19-khandaker.pdf)
- Efficient Protection of Path-Sensitive Control Security. R Ding, et al. Security'2017 [paper](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-ding.pdf)
- GRIFFIN: Guarding Control Flows Using Intel Processor Trace. X Ge, et al. ASPLOS'2017 [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/01/griffin-asplos17.pdf)
- PT-CFI: Transparent backward-edge control ﬂow violation detection using intel processor trace. Y Gu, et al. CODASPY'2017 [paper](http://web.cse.ohio-state.edu/~zhao.2708/assets/codaspy17/CODASPY17.pdf)
- 

### Taint Analysis (Theory)
- SELECTIVETAINT: Efficient Data Flow Tracking With Static Binary Rewriting. S Chen, et al. Security'2021 [paper](https://www.usenix.org/system/files/sec21fall-chen-sanchuan.pdf)
- StraightTaint: Decoupled Offline Symbolic Taint Analysis. J Ming, et al. ASE'2016 [paper](https://faculty.ist.psu.edu/wu/papers/StraightTaint-ASE16.pdf)
- TaintPipe: Pipelined Symbolic Taint Analysis. J Ming, et al. Security'2015 [paper](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-ming.pdf)


### Deobfuscation
- QSynth - A Program Synthesis based Approach for Binary Code Deobfuscation. R David, et al. Binary Analysis Research Workshop,NDSS'2020 [paper](https://archive.bar/pdfs/bar2020-preprint9.pdf)

### Coredump Analysis
- CREDAL: Towards Locating a Memory Corruption Vulnerability with Your Core Dump. J Xu, et al. SIGSAC'2016 [paper](https://www.semanticscholar.org/paper/CREDAL%3A-Towards-Locating-a-Memory-Corruption-with-Xu-Mu/fb69ca4ce65a5c796f6247559205322e9796f2fc)

## Limitations


