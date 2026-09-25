<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=2800&pause=900&color=00E5FF&center=true&vCenter=true&width=620&lines=0xWxse;vulnerability+research;symbolic+execution+%2F%2F+binary+analysis;deterministic+over+probabilistic" alt="0xWxse" />

<sub><code>SECURITY ENGINEERING</code> &nbsp;/&nbsp; <code>REVERSE ENGINEERING</code> &nbsp;/&nbsp; <code>FORMAL METHODS</code></sub>

<br/><br/>

<img src="https://img.shields.io/badge/status-active__research-0D1117?style=flat-square&labelColor=0D1117&color=00E5FF" />
<img src="https://img.shields.io/badge/node-WiseHax-0D1117?style=flat-square&labelColor=0D1117&color=30363D" />
<img src="https://img.shields.io/badge/open_to-collaboration-0D1117?style=flat-square&labelColor=0D1117&color=00E5FF" />

</div>

<br/>

```text
$ whoami
  0xWxse :: security engineer in training, systems programmer

$ cat ./principle
  Prove the bug. Don't guess it.
  Signatures describe what was seen before. Constraints describe what is possible.

$ echo $FOCUS
  vulnerability research | symbolic execution | malware dissection | memory-safe tooling
```

---

### `0x00` &nbsp;Overview

I work at the layer where software stops being abstract: machine code, memory, and the paths an attacker can actually reach. My research centers on **symbolic execution** and **SMT-backed analysis**, using solvers to reason about which states a program can enter instead of relying on pattern matching alone. Most of the tooling I build is written in **Rust**, because analysis software that parses hostile input should not be the weakest binary on the machine.

---

### `0x01` &nbsp;Research Tracks

| Track | What I'm working on |
| :--- | :--- |
| **Symbolic Execution** | Encoding program paths as constraints and using Z3 to check reachability of memory-corruption states. |
| **Binary De-obfuscation** | Lifting binaries to Ghidra P-Code / IR to statically resolve opaque predicates and undo control-flow flattening. |
| **Malware Analysis** | A CLI engine for static and dynamic payload triage, with YARA integration and MITRE ATT&CK technique mapping. |
| **Memory-Safe Tooling** | Vulnerability scanners, taint-analysis passes, and system hooks written in Rust. |
| **Systems & OS** | Bare-metal experiments in C and assembly toward a minimal OS environment built for security work. |

---

### `0x02` &nbsp;Toolchain

<p>
  <img src="https://img.shields.io/badge/Rust-0D1117?style=flat-square&logo=rust&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/C-0D1117?style=flat-square&logo=c&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/x86__64_ASM-0D1117?style=flat-square&logo=intel&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/Go-0D1117?style=flat-square&logo=go&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=00E5FF" />
</p>
<p>
  <img src="https://img.shields.io/badge/Ghidra-0D1117?style=flat-square&logo=ghidra&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/Z3_SMT-0D1117?style=flat-square&logo=microsoft&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/YARA-0D1117?style=flat-square&logo=virustotal&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/MITRE_ATT%26CK-0D1117?style=flat-square&logo=target&logoColor=00E5FF" />
  <img src="https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=00E5FF" />
</p>

<details>
<summary><code>also builds</code> &nbsp;secure application backends</summary>
<br/>

Hardened web and enterprise systems, with attention to input validation, authorization boundaries, and data sanitization.

<img src="https://img.shields.io/badge/Laravel-0D1117?style=flat-square&logo=laravel&logoColor=8B949E" />
<img src="https://img.shields.io/badge/C%23-0D1117?style=flat-square&logo=dotnet&logoColor=8B949E" />
<img src="https://img.shields.io/badge/Java-0D1117?style=flat-square&logo=openjdk&logoColor=8B949E" />

</details>

---

### `0x03` &nbsp;Current Ops

```diff
+ [running]   symbolic path explorer   :: Z3 constraint backend, Rust
+ [running]   malware triage CLI       :: YARA rules + ATT&CK mapping
~ [research]  P-Code de-obfuscation    :: opaque predicate elimination
~ [research]  taint analysis pass      :: source-to-sink tracking on lifted IR
- [queued]    bare-metal security OS   :: boot + memory manager
```

---

### `0x04` &nbsp;Telemetry

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=WiseHax&show_icons=true&hide_border=true&bg_color=0D1117&title_color=00E5FF&icon_color=00E5FF&text_color=C9D1D9&rank_icon=github" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=WiseHax&layout=compact&hide_border=true&bg_color=0D1117&title_color=00E5FF&text_color=C9D1D9" height="170" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=WiseHax&hide_border=true&background=0D1117&ring=00E5FF&fire=00E5FF&currStreakLabel=00E5FF&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" height="150" />
</p>

---

### `0x05` &nbsp;Contact

```text
directory   github.com/WiseHax
interests   symbolic execution research, open-source core utilities, defensive tooling
status      accepting collaboration requests
```

<div align="center">
<sub><code>// end of transmission</code></sub>
</div>
