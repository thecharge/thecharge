# Radoslav Sandov — I build where atoms meet bits

> Senior Software Engineer · Solution Architect · Hardware Tinkerer  
> Sofia, Bulgaria · [thecharge@gmail.com](mailto:thecharge@gmail.com) · [@Radoslav_Sandov](https://x.com/Radoslav_Sandov)

---

I've spent 15 years building across the full stack — from FPGA pin constraints to Kubernetes orchestration, from HIPAA-compliant healthcare platforms to financial compliance systems. 

The common thread: I'm most interested in the problems that live at the intersection of disciplines most engineers pick only one of.

I make watches as a hobby. 
I design PCBs. 
I write compilers. 

These are not separate interests — they're the same obsession with how systems fit together precisely.

---

## Active Projects

### [sndv-hdl](https://github.com/thecharge/sndv-hdl) — TypeScript → SystemVerilog Compiler
Write hardware logic in TypeScript. Compile to synthesizable SystemVerilog. Flash to real FPGAs.

Software engineers shouldn't need to learn a 30-year-old HDL to describe hardware. 
This compiler closes that gap — TypeScript classes become hardware modules, decorators map signals to physical pins, and the emitter handles all the `always_ff` blocks for you.

Early stage. Core compiler works. Gowin and iCE40 toolchain flows are scripted and running.

`TypeScript` `Bun` `SystemVerilog` `FPGA` `Compilers`

---

### [sndv-kv](https://github.com/thecharge/sndv-kv) — Blackboard Architecture for LSM Storage
A research database exploring whether autonomous agents can replace static database algorithms.

Traditional LSM databases hardcode their compaction thresholds, cache policies, and flush triggers. 

This project tests the hypothesis that autonomous agents observing shared blackboard state can adapt to workloads more intelligently than fixed rules. 

ML compaction, adaptive caching, and workload-aware agents — in progress, openly tracked.

`Go` `LSM-Tree` `Agent Architecture` `Blackboard Pattern` `Storage Systems`

---

### Metering Ledger *(launching soon)*
Tamper-proof metering system with 
audit trail system with hash-chained records.

`Metering` `Cryptographic Integrity`

---

### Enterprise AI Copilot *(in development)*

Blackboard-based reasoning loop for enterprise software delivery — from PRD to production.

Not a glorified while-loop. 

A temporal, pgsql, multi-model coordination machine that understands brownfield codebases, reasons across context windows, and can copilot the full software lifecycle. 

Built on the same blackboard principles as sndv-kv, applied to autonomous software engineering.

`Multi-Agent` `Temporal` `Enterprise` `LLM Orchestration`

---

**Primary stack:** TypeScript · React/Native · Go (→ Zig will come as replacement) · Python · Kubernetes · PostgreSQL · Kafka · Cloud (AWS/GCP)


**Certifications:** SEI SAPP · SAFe Practitioner · SRE · IBM Big Data · HIPAA

---

## What I'm exploring

- Edge AI inference on custom FPGA fabric
- Adaptive storage for LLM KV caches (1B+ token contexts)
- Brownfield-aware AI software engineering agents
- Hardware-software co-design tooling for the next generation of embedded AI devices
- Anything non-trivial CRUD related

---

## AI Tooling

- Claude - primary thinking partner
- Gemini - strong second opinion and reasoning
- Copilot - good fidelity at the right price
- OpenCode - gets things done, not always gracefully

---

*I build in public. Feedback, collaboration, and brutal critiques all welcome.*
