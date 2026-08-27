<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="Yngvarr — systems engineer and head of network infrastructure" src="assets/banner-light.svg" width="880">
</picture>

**I write the algorithm, and I run the network it describes.**

**Currently** — running the network infrastructure department of an oil & gas company across 30+
sites, and publishing the Rust crates that come out of that work.

**[yngvarr.dev@gmail.com](mailto:yngvarr.dev@gmail.com)** · Remote, CET/EET · open to remote roles
in the EU and to work with companies across RU/CIS

[`xgraph`](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/xgraph)'s bridge detection finds exactly
the single points of failure a campus topology review looks for — published, versioned, used by
other developers, and it came off the job. So did every crate below it.

**20+ years in production networks** · 7 published packages · **52 000+ downloads** ·
**24 engineers** led across **30+ sites**

**Rust · C · C++ · Python · Linux** — **Cisco · Huawei · SIP · E1/PRI**

---

## Where the two tracks meet

Plenty of engineers have one of these tracks. What is rare is the edge between them — and every
crate below sits on it.

- **Topology review → code.** Finding the one link whose failure splits a campus network is
  exactly a graph bridge; `xgraph` computes bridges, betweenness centrality and communities on
  graphs of that shape.
- **Trust boundary → code.** `huginn` validates and sanitizes input at the boundary, written by
  someone who has seen what actually arrives at a production network edge.

---

## Open source

Six crates on [crates.io](https://crates.io/users/xvi-xv-xii-ix-xxii-ix-xiv) and one package on
[PyPI](https://pypi.org/project/pqcrypt/) — **52 000+ downloads** on crates.io alone, all
documented and maintained.

| Project | What it is | Version | Downloads |
| --- | --- | :---: | :---: |
| [xgraph](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/xgraph) | Graph algorithms — Dijkstra, Kosaraju, Brandes centrality, Leiden communities, bridge detection — over homogeneous graphs and heterogeneous multigraphs | [![xgraph version](https://img.shields.io/crates/v/xgraph?style=flat-square&label=&color=555)](https://crates.io/crates/xgraph) | [![xgraph downloads](https://img.shields.io/crates/d/xgraph?style=flat-square&label=&color=555)](https://crates.io/crates/xgraph) |
| [fibonacci_heap](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/fibonacci_heap) | Fibonacci heap with amortised O(1) `decrease-key`, cascading cuts and link operations | [![fibonacci_heap version](https://img.shields.io/crates/v/fibonacci_heap?style=flat-square&label=&color=555)](https://crates.io/crates/fibonacci_heap) | [![fibonacci_heap downloads](https://img.shields.io/crates/d/fibonacci_heap?style=flat-square&label=&color=555)](https://crates.io/crates/fibonacci_heap) |
| [huginn](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/huginn) | Input sanitization and validation at the trust boundary, with a typed validator pipeline | [![huginn version](https://img.shields.io/crates/v/huginn?style=flat-square&label=&color=555)](https://crates.io/crates/huginn) | [![huginn downloads](https://img.shields.io/crates/d/huginn?style=flat-square&label=&color=555)](https://crates.io/crates/huginn) |
| [bearingpro](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/bearingpro) | Maritime navigation — true and magnetic bearings, deviation, course conversion | [![bearingpro version](https://img.shields.io/crates/v/bearingpro?style=flat-square&label=&color=555)](https://crates.io/crates/bearingpro) | [![bearingpro downloads](https://img.shields.io/crates/d/bearingpro?style=flat-square&label=&color=555)](https://crates.io/crates/bearingpro) |
| [ourobuf](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/ourobuf) | `no_std` circular buffer with constant-time operations for allocator-free targets | [![ourobuf version](https://img.shields.io/crates/v/ourobuf?style=flat-square&label=&color=555)](https://crates.io/crates/ourobuf) | [![ourobuf downloads](https://img.shields.io/crates/d/ourobuf?style=flat-square&label=&color=555)](https://crates.io/crates/ourobuf) |
| [patternhunt](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/patternhunt) | Filesystem search — globs, brace expansion, extglobs, regex and metadata predicates, sync or streaming | [![patternhunt version](https://img.shields.io/crates/v/patternhunt?style=flat-square&label=&color=555)](https://crates.io/crates/patternhunt) | [![patternhunt downloads](https://img.shields.io/crates/d/patternhunt?style=flat-square&label=&color=555)](https://crates.io/crates/patternhunt) |

**Newest —** [`pqcrypt`](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/pqcrypt) [![pqcrypt version](https://img.shields.io/pypi/v/pqcrypt?style=flat-square&label=&color=555)](https://pypi.org/project/pqcrypt/) — post-quantum
file encryption and signing from the command line. ML-KEM (NIST FIPS 203) and ML-DSA (FIPS 204),
hybrid encrypt-then-sign. Published on PyPI.

---

## Infrastructure & telecom

- **Head of network infrastructure department** — campus and data-centre networking and structured
  cabling systems (SCS) for an oil & gas company. **24 engineers** across **30+ sites**, operating
  a switching estate of several thousand devices.
- **Voice and telecom administration** — IP-PBX platforms, voice gateways and session border
  controllers: AudioCodes Mediant, Cisco, Huawei, Eltex, Nortel, Alcatel.
- **Protocols and dimensioning** — SIP, RTP, H.323, E1/PRI trunking, and the traffic engineering
  behind capacity planning.

---

## Engineering focus

- **Systems programming** — Rust, C, C++, Linux, memory- and cache-aware design, concurrency
- **Embedded** — `no_std`, ARM Cortex-M4/M7, STM32, RTIC, ATmega/ATtiny, DMA, USB, UART, real-time constraints
- **Networking** — campus and data-centre switching, structured cabling, TCP/IP, topology and capacity planning
- **Telecom** — SIP, RTP, H.323, E1/PRI, IP-PBX, voice gateways, session border controllers
- **Security** — post-quantum cryptography, encryption and signing, input validation, binary analysis
- **Algorithms** — graphs, data structures, performance work and benchmarking
- **Leadership** — running an infrastructure department: planning, vendor management, incident response

## Stack

**Languages** — Rust · C · C++ · Python · Bash · JavaScript · PHP  
**Embedded** — STM32 · Cortex-M4/M7 · RTIC · ATmega · ATtiny · Raspberry Pi · `no_std`  
**Networking** — Cisco · Huawei · Eltex · HP · campus LAN · data centre · SCS  
**Telecom** — SIP · RTP · H.323 · IP-PBX · AudioCodes Mediant · Nortel · Alcatel · E1/PRI  
**Systems** — Linux (Debian/Ubuntu) · multithreading · async · real-time  
**Data and ML** — PostgreSQL · MySQL · Redis · NumPy · pandas · PyTorch · scikit-learn · NetworkX  
**Tools** — Git · Docker · CI/CD · GDB · CMake

---

## Contact

**[yngvarr.dev@gmail.com](mailto:yngvarr.dev@gmail.com)** · Remote, CET/EET

[GitHub](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv) ·
[crates.io](https://crates.io/users/xvi-xv-xii-ix-xxii-ix-xiv) ·
[PyPI](https://pypi.org/project/pqcrypt/)

Open to remote roles in the EU and to work with companies across RU/CIS.
