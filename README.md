<div align="center">

# ⚡ Youssef Hamdi (0xZodiac)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00ADD8&center=true&vCenter=true&width=800&lines=AI+Systems+Security+Researcher;Zero-Day+Vulnerability+Hunter;Red+Teamer+%26+Offensive+Tool+Builder;Low-Level+Memory+Forensics+Expert)](https://git.io/typing-svg)

**`AI Infrastructure Security`** • **`Low-Level Memory Forensics`** • **`Offensive Tool Engineering`** • **`Red Teaming Automation`**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/youssefhamdi)
[![Email](https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail)](mailto:youssefhamdi329@gmail.com)

</div>

---

## 👨‍💻 `whoami`

```console
foo@ubuntu:~$ Youssef.info()

> Operating at the critical intersection of Low-Level Systems Engineering,
  AI Privacy, and Offensive Cyber Security.

> Primary Mission: Breaking and securing next-generation AI serving
  infrastructure through rigorous forensic measurement.

> Specialization: Dynamic heap analysis, runtime VRAM profiling,
  protocol-layer hijacking, and high-performance reconnaissance engines.

> Core Languages: Go (Golang), Python, C/C++, Bash Scripting.
```

---

## 📝 High-Impact Research & Publications

### 🧠 1. The Illusion of "Local": A Four-Layer Forensic Measurement of Privacy Boundaries in Consumer Local-LLM Serving Stacks

> **Status:** Under Review for Top-Tier Security Venues *(Targeting USENIX Security / IEEE TIFS)*

**Core Vulnerabilities Discovered:**

| ID | Vulnerability | Severity |
|----|--------------|----------|
| CWE-862 | **Cross-Tenant Session Hijacking** — Unauthenticated protocol-layer primitive in the llama.cpp API permitting deterministic retrieval of other tenants' KV-cache data ($200/200$ successful trials) | 🔴 Critical |
| MEM-001 | **Runtime Memory Leakage** — Isolated 11–13 persistent cleartext prompt copies remaining in the process heap, structurally resistant to object-level zeroisation due to glibc per-thread arena retention | 🔴 Critical |
| LOG-001 | **Wrapper Cleartext Logging** — Consumer wrapper daemons (LM Studio) write all user interactions and hidden reasoning traces directly to unencrypted disk logs by default | 🟠 High |

**Methodology:** Designed a strict **4-layer forensic framework** (File-format → Runtime memory → Interface wrapper → Network protocol) audited at $n \ge 50$ trials per condition across multiple model architectures.

---

### 📊 2. ACTS: A Multi-Tier Benchmark for Evaluating LLM Cipher Identification Accuracy

> **Status:** Under Review at *Expert Systems with Applications* (ESWA, Impact Factor: **9.4**)

**Focus:** Architected a multi-tier benchmarking orchestration framework to rigorously evaluate large language models on their capabilities to detect, parse, and identify complex cryptographic ciphers under varied metadata and prompt constraints.

---

## 🛠️ Open-Source Technical Portfolio

### 🛡️ AI Security & Forensics Engineering

```
┌─────────────────────────────────────────────────────────────────────┐
│  REPO: Local-LLM-Forensics                                          │
│  ─────────────────────────────────────────────────────────────────  │
│  Official codebase accompanying the local LLM forensic paper.       │
│  ✦ Memory-dumping harnesses                                         │
│  ✦ Automated network fuzzing batteries                              │
│  ✦ Raw /proc/mem heap parsers                                       │
│  ✦ Custom low-level patches for strict runtime memory               │
│    zeroisation in llama.cpp and Ollama runtimes                     │
└─────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────┐
│  REPO: ACTS-Benchmark                                               │
│  ─────────────────────────────────────────────────────────────────  │
│  Data orchestration engine and evaluation harnesses for             │
│  multi-tier cipher identification accuracy across leading LLMs.     │
│  ✦ Automated generation pipelines                                   │
│  ✦ Multi-tier evaluation harnesses                                  │
│  ✦ Cross-architecture benchmarking support                          │
└─────────────────────────────────────────────────────────────────────┘
```

### ⚡ Offensive Security & High-Performance Recon

```
┌─────────────────────────────────────────────────────────────────────┐
│  TOOL: Fastrails                               [Go / Golang]        │
│  ─────────────────────────────────────────────────────────────────  │
│  Blazing fast, concurrent subdomain extraction from SecurityTrails. │
│  ✦ Bypasses traditional API rate limitations via session cookie     │
│    management and dynamic low-level authentication structures        │
│  ✦ Harvests up to 10,000 subdomains per target seamlessly          │
│  ✦ Native concurrency for maximum throughput                        │
└─────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────┐
│  TOOL: SigmaRecon                              [Python]             │
│  ─────────────────────────────────────────────────────────────────  │
│  Advanced enterprise-grade subdomain enumeration orchestrator.      │
│  ✦ Integrates 23+ industry-standard passive/active recon tools     │
│  ✦ Automated multi-threaded validation pipelines                    │
│  ✦ Wildcard elimination & structured intelligence data output       │
│  ✦ Immediate target mapping and intelligence structuring            │
└─────────────────────────────────────────────────────────────────────┘
```

---

## ⚙️ Advanced Technical Skills Matrix

```
╔══════════════════════════╦══════════════════════════════════════════════════════════════╗
║ CATEGORY                 ║ WEAPONRY & TOOLS                                             ║
╠══════════════════════════╬══════════════════════════════════════════════════════════════╣
║ Languages                ║ Go (Golang) · Python · C/C++ · Bash Scripting                ║
╠══════════════════════════╬══════════════════════════════════════════════════════════════╣
║ Forensics & Reversing    ║ GDB · cuda-gdb (Direct VRAM Probing) · AddressSanitizer     ║
║                          ║ (ASan) · Memory Mapping (/proc/[pid]/maps) · Valgrind        ║
╠══════════════════════════╬══════════════════════════════════════════════════════════════╣
║ Offensive Operations     ║ Custom Fuzzing Battery Development · Protocol-Layer          ║
║                          ║ Exploitation · Automated Recon Pipelines                     ║
║                          ║ Traffic Analysis (Wireshark / tcpdump)                       ║
╠══════════════════════════╬══════════════════════════════════════════════════════════════╣
║ AI Infrastructures       ║ llama.cpp & llama-server builds · CUDA & OpenBLAS runtimes  ║
║                          ║ Ollama Core · LM Studio Daemons · GGUF Specs                ║
╠══════════════════════════╬══════════════════════════════════════════════════════════════╣
║ Systems & DevOps         ║ Advanced Linux Kernel Tuning · Isolated Network Namespaces  ║
║                          ║ (netns) · Docker Containerization · WSL2 HW Passthrough     ║
╚══════════════════════════╩══════════════════════════════════════════════════════════════╝
```

---

## 📈 Live Threat Intel & Contribution Activity

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=youseefhamdi&theme=tokyonight&hide_border=true&background=0d1117&stroke=00ADD8&ring=00ADD8&fire=FF6B6B&currStreakLabel=00ADD8)](https://github.com/youseefhamdi)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=youseefhamdi&theme=tokyo-night&bg_color=0d1117&color=00ADD8&line=00ADD8&point=FF6B6B&area=true&hide_border=true)](https://github.com/youseefhamdi)

</div>

---

<div align="center">

```console
[ MISSION LOG ] ─────────────────────────────────────────────────────
  "Automating the offensive lifecycle and securing the AI frontier.
   One deterministic vulnerability at a time."
─────────────────────────────────────────────────────────────────────
```

![Profile Views](https://komarev.com/ghpvc/?username=youseefhamdi&color=00ADD8&style=for-the-badge&label=PROFILE+VIEWS)

</div>
