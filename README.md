<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Yngvarr — Software Engineer, Network & Telecom Infrastructure" src="assets/banner-light.svg" width="880">
</picture>

# Software Engineer · Network & Telecom Infrastructure

**Rust · C · C++ · Python · Linux · Cisco · Huawei · SIP**

Two tracks that rarely meet in one person. I write systems software — `no_std` libraries
for Cortex-M, graph algorithms, cryptographic and binary tooling — and I have spent years
on the other end of the same stack, administering voice and network infrastructure and
leading the department that ran campus and data-centre networking for an oil & gas
company.

That range is the point: the code below is written by someone who has had to operate what
it talks to.

---

## Infrastructure & telecom

- **Head of network infrastructure department** — campus and data-centre networking and
  structured cabling systems (SCS). Led a team of ** > 20
  engineers** across ** > 30 sites**, operating a switching estate of several thousand
  devices.
- **Voice and telecom administration** — IP-PBX platforms, voice gateways and session
  border controllers: AudioCodes Mediant, Cisco, Huawei, Eltex, Nortel, Alcatel.
- **Protocols and dimensioning** — SIP, RTP, H.323, E1/PRI trunking, and the traffic
  engineering behind capacity planning.

The two tracks feed each other. [`erlang_e1`](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/erlang_e1)
implements the Erlang B channel sizing I have applied to real voice trunks;
[`xgraph`](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/xgraph)'s bridge detection finds
exactly the single points of failure a campus topology review looks for.

---

## Open source

Seven crates on [crates.io](https://crates.io/users/xvi-xv-xii-ix-xxii-ix-xiv) and one
package on [PyPI](https://pypi.org/project/pqcrypt/) — **~50 000 downloads** in total.
Published, versioned, documented, and used by other developers.

| Project | What it is | Published | Downloads |
| --- | --- | --- | ---: |
| [xgraph](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/xgraph) | Graph algorithms — Dijkstra, Kosaraju, Brandes centrality, Leiden communities, bridge detection — over homogeneous graphs and heterogeneous multigraphs | crates.io 2.1 | 39 000+ |
| [fibonacci_heap](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/fibonacci_heap) | Fibonacci heap with amortised O(1) `decrease-key`, cascading cuts and link operations | crates.io 1.1 | 5 000+ |
| [huginn](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/huginn) | Input sanitization and validation at the trust boundary, with a typed validator pipeline | crates.io 1.0 | 1 700+ |
| [bearingpro](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/bearingpro) | Maritime navigation: true and magnetic bearings, deviation, course conversion | crates.io 0.12 | 1 100+ |
| [erlang_e1](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/erlang_e1) | Erlang B traffic engineering — sizing E1 voice channels against a target blocking probability | crates.io 0.9 | 1 100+ |
| [ourobuf](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/ourobuf) | `no_std` circular buffer with constant-time operations for allocator-free targets | crates.io 0.1 | 862 |
| [patternhunt](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/patternhunt) | Filesystem search: globs, brace expansion, extglobs, regex and metadata predicates, sync or streaming | crates.io 0.4 | 828 |
| [pqcrypt](https://github.com/xvi-xv-xii-ix-xxii-ix-xiv/pqcrypt) | Post-quantum file encryption and signing CLI — ML-KEM (NIST FIPS 203) and ML-DSA (FIPS 204), hybrid encrypt-then-sign | PyPI 1.0 | — |

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

**[yngvarr.dev@gmail.com](mailto:yngvarr.dev@gmail.com)**

Open to remote roles in the EU and to work with companies across RU/CIS.
