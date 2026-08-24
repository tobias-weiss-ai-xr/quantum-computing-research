<h1 align="center">
  <strong>Quantum Computing Research Corpus</strong>
</h1>
<h3 align="center">Data-driven, auto-validated literature review for quantum computing: algorithms, error correction, hardware, simulation, ML, and cryptography</h3>

### 🔗 Links

- **GitHub**: https://github.com/tobias-weiss-ai-xr/quantum-computing-research
- **License**: https://github.com/tobias-weiss-ai-xr/quantum-computing-research/blob/main/LICENSE
- **CI**: https://github.com/tobias-weiss-ai-xr/quantum-computing-research/actions/workflows/validate.yml
- **GitHub Pages**: https://tobias-weiss-ai-xr.github.io/quantum-computing-research/


> 📊 **Auto-validated corpus** — papers in `papers.yaml` are validated by
> `scripts/validate_papers.py` on every push. The README is auto-generated
> from `papers.yaml` via `scripts/generate_readme.py`.

## What you get

| Capability | How |
|------------|-----|
| 📄 **Curated corpus** | `papers.yaml` is the source of truth — one structured entry per paper |
| ✅ **Auto-validation** | `scripts/validate_papers.py` checks schema, duplicates, URL normalization |
| 🧾 **Auto-generated README** | `scripts/generate_readme.py` renders the paper list grouped by taxonomy |
| 📊 **Statistics & trends** | `scripts/standard_stats.py` → `statistics.json` |
| 🔍 **Literature review** | `scripts/analysis/generate_reports.py` → `docs/research/` |
| 🔎 **Paper discovery** | `scripts/fetch/fetch_new_papers.py` (arXiv), `fetch_openalex_bulk.py`, `fetch_other_sources.py` |
| 🤖 **Agentic workflow** | `AGENTS.md` + `config/taxonomy.yaml` make this repo agent-friendly |

## 📚 Paper list

- [📚 Quantum Algorithms & Complexity](#quantum-algorithms-&-complexity)
  - [Theory](#theory)
  - [Method](#method)
  - [Application](#application)
- [📚 Quantum Error Correction](#quantum-error-correction)
  - [Theory](#theory)
  - [Method](#method)
  - [Application](#application)
  - [Development](#development)
  - [Systems & Technology](#systems-&-technology)
- [📚 Quantum Hardware & Architecture](#quantum-hardware-&-architecture)
  - [Theory](#theory)
  - [Method](#method)
  - [Application](#application)
  - [Development](#development)
  - [Systems & Technology](#systems-&-technology)
  - [Evaluation & Benchmarks](#evaluation-&-benchmarks)
- [📚 Quantum Information Theory](#quantum-information-theory)
  - [Theory](#theory)
  - [Method](#method)
  - [Development](#development)
  - [Systems & Technology](#systems-&-technology)
- [📚 Quantum Simulation](#quantum-simulation)
  - [Theory](#theory)
  - [Method](#method)
  - [Application](#application)
  - [Development](#development)
- [📚 Quantum Machine Learning](#quantum-machine-learning)
  - [Theory](#theory)
  - [Method](#method)
  - [Application](#application)
  - [Systems & Technology](#systems-&-technology)
  - [Evaluation & Benchmarks](#evaluation-&-benchmarks)
  - [Reviews & Surveys](#reviews-&-surveys)
- [📚 Quantum Cryptography & Communication](#quantum-cryptography-&-communication)
  - [Theory](#theory)
  - [Method](#method)
  - [Application](#application)
  - [Systems & Technology](#systems-&-technology)
- [📚 Quantum Software & Tools](#quantum-software-&-tools)
  - [Development](#development)
- [📚 Surveys & Taxonomies](#surveys-&-taxonomies)
  - [Theory](#theory)
  - [Method](#method)
  - [Application](#application)
  - [Reviews & Surveys](#reviews-&-surveys)

### Quantum Algorithms & Complexity

#### Theory

##### 2026

- [2026] **Iterative Interpolation Schedules for Quantum Approximate Optimization Algorithm** *ACM Transactions on Quantum Computing* [[paper](https://doi.org/10.1145/3815778)]
- [2026] **Quantum simulation of non-Markovian dynamical systems** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.13533)]
- [2026] **Quantum image processing filters based on FRQI representation** *Quantum Information Processing* [[paper](https://doi.org/10.1007/s11128-026-05321-y)]
- [2026] **Exponential convergence dynamics in Grover’s search algorithm** *Quantum Science and Technology* [[paper](https://doi.org/10.1088/2058-9565/ae8df3)]
- [2026] **Quantum approaches to the traveling salesman problem: A critical review of formulations, complexity, and implementation limits** *Physica A Statistical Mechanics and its Applications* [[paper](https://doi.org/10.1016/j.physa.2026.131649)]
- [2026] **A KnoWellian Solution to the Millennium Prize Problem: The $P$ vs. $NP$ Problem as Dual-Ontology Computational Resolution** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21871240)]
- [2026] **Constant-round quantum advantage in communication complexity for total functions** [[paper](https://arxiv.org/abs/2608.19787)]
- [2026] **No low-degree tests for quantum states** [[paper](https://arxiv.org/abs/2608.00265)]
- [2026] **Improved Quantum Algorithms for Subset Sum and $k$-SUM** [[paper](https://arxiv.org/abs/2608.07309)]
- [2026] **On the quantum communication complexity of total functions** [[paper](https://arxiv.org/abs/2608.18784)]
- [2026] **Evaluating QAOA expectation values can be as hard as counting optimal solutions** [[paper](https://arxiv.org/abs/2608.11385)]
- [2026] **Quantum Coordination Advantages in AI State-Tracking Tasks: Semantic Compilation and Latent Memory** [[paper](https://arxiv.org/abs/2608.11066)]
- [2026] **Separating quantum circuits from classical LLMs** [[paper](https://arxiv.org/abs/2608.03962)]
- [2026] **Good Stabilizer Codes from Shallow Clifford Circuits with Random Matchings** [[paper](https://arxiv.org/abs/2608.18536)]
- [2026] **Shor's algorithm requires Fanout** [[paper](https://arxiv.org/abs/2608.06703)]
- [2026] **A Paturi Theorem for Signed Subcube Representations** [[paper](https://arxiv.org/abs/2608.06256)]
- [2026] **Hardness of approximation for minimum-weight decoding of two-dimensional topological quantum codes** [[paper](https://arxiv.org/abs/2608.17109)]
- [2026] **Learning Clifford-structured quantum unitaries and Hamiltonians** [[paper](https://arxiv.org/abs/2608.09912)]
- [2026] **Classical Adversarial Fault-Tolerance and PCPs** [[paper](https://arxiv.org/abs/2608.16860)]
- [2026] **Superlogarithmic Gap Result for LCLs on Trees in Quantum-LOCAL** [[paper](https://arxiv.org/abs/2608.16854)]
- [2026] **Sharp Hardness for MAX-3-CUT and Quantum MAX-CUT** [[paper](https://arxiv.org/abs/2608.00333)]
- [2026] **Proof of the hiding conjecture for Gaussian boson sampling with an arbitrary number of squeezed input modes** [[paper](https://arxiv.org/abs/2608.19314)]
- [2026] **phase2: full-state vector simulation of quantum time evolution at scale** *Communications AI & Computing* [[paper](https://doi.org/10.1038/s44488-026-00002-2)]
- [2026] **Parallelizable Exact Synthesis of Quantum Circuits via Semi-Tensor Product** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.24195)]
- [2026] **Quantum Natural Gradient Optimization for Convergence Reliability in NISQ Variational Quantum Algorithms** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-10488762/v1)]
- [2026] **Reducing circuit resources in Grover’s algorithm via constraint-aware initialization** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-64187-3)]
- [2026] **Quantum multi-label k-nearest neighbor** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.21919)]
- [2026] **Quantum Simulation of Stokes Flow via Schrödingerisation and Artificial Compressibility** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.00281)]
- [2026] **Quantum-Enhanced Artificial Intelligence: Bridging Quantum Physics and Machine Learning for Next-Generation Computing Paradigms** *Buana Information Technology and Computer Sciences (BIT and CS)* [[paper](https://doi.org/10.36805/5cdcfp74)]
- [2026] **Fourier space readout method for efficiently recovering functions encoded in quantum states** *Quantum Science and Technology* [[paper](https://doi.org/10.1088/2058-9565/ae8930)]
- [2026] **LLM-Guided Initialization for Accelerated Hybrid Quantum-Classical Medical Image Classification** [[paper](https://arxiv.org/abs/2607.27262)]
- [2026] **The Quantum Fold Machine - An Exact, Parameter-Free and Machine-Closed Complete-Field Derivation of Reversible and Quantum Computation from Smithian Fold Theory** *Open MIND* [[paper](https://github.com/MettaMazza/ernos-labs-sft-platform)]
- [2026] **Observation of disorder-free localization using a (2+1)D lattice gauge theory on a quantum processor** *Science* [[paper](https://doi.org/10.1126/science.adr9680)]
- [2026] **Exact and Fixed-Point Grover Search with Qudits** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.24658)]
- [2026] **Efficient Fully Homomorphic Evaluation of FIPS 203 ML-KEM Sessions via Native Wire Conversion and Measured Noise-Control Options α, β, θ, δ without Functional Bootstrapping** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21543529)]
- [2026] **Complexity of Normalized Persistence Problems for Topological Data Analysis and Local Hamiltonians** [[paper](https://arxiv.org/abs/2607.03278)]
- [2026] **Efficient classical simulation of large-scale unitary cluster Jastrow circuits** [[paper](https://arxiv.org/abs/2607.21337)]
- [2026] **Frozen-Tree Sampling Refutes Quantum Advantage of Random Circuit Sampling** [[paper](https://arxiv.org/abs/2607.04054)]
- [2026] **Separating Geometry From Interference in Constrained Quantum Optimization** [[paper](https://arxiv.org/abs/2607.13630)]
- [2026] **Circuit complexity lower bounds for quantum spin glasses** [[paper](https://arxiv.org/abs/2607.14384)]
- [2026] **Quantum Algorithms for Modular Factorials** [[paper](https://arxiv.org/abs/2607.29453)]
- [2026] **XOR Games at Full Tilt: The Hardness of Binary Nonlocal Games** [[paper](https://arxiv.org/abs/2607.06876)]
- [2026] **Spectral gap of Lee-Yang Hamiltonians** [[paper](https://arxiv.org/abs/2607.10765)]
- [2026] **Explicit Separations for One-Query Unitary Synthesis** [[paper](https://arxiv.org/abs/2607.26478)]
- [2026] **Optimal Stabilizer Testing and Learning with Limited Quantum Memory** [[paper](https://arxiv.org/abs/2607.02444)]
- [2026] **Optimal T Counts under Sparsity: from QROM to State Preparation and Block Encoding** [[paper](https://arxiv.org/abs/2607.28260)]
- [2026] **Dismantling the Stoquastic Dichotomy** [[paper](https://arxiv.org/abs/2607.18596)]
- [2026] **A Quantitative Framework for Comparing Classical and Quantum Algorithms for the Traveling Salesman Problem** [[paper](https://arxiv.org/abs/2607.24581)]
- [2026] **The Keyl-Werner algorithm is not optimal for spectrum estimation** [[paper](https://arxiv.org/abs/2607.27117)]
- [2026] **Linear Algebra of Generalized Contextuality in All Prepare-Transform-Measure Scenarios** [[paper](https://arxiv.org/abs/2607.26139)]
- [2026] **Quantum amplitude estimation for Wright–Fisher parameter inference: Theoretical query complexity advantages conditional on efficient oracle construction** *International Journal of Modern Physics C* [[paper](https://doi.org/10.1142/s0129183126430047)]
- [2026] **A Quantum Algorithm for Random Number Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.13034)]
- [2026] **Configurable Algorithms for Histopathologic Cancer Detection on Quantum Hardware** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.21752)]
- [2026] **Faster algorithm for achieving minimal-size quantum decision diagrams** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.24789)]
- [2026] **Quantum Machine Learning for Robotics: A Comprehensive Review of Algorithms, Applications, and Future Directions** [[paper](https://doi.org/10.65218/jius.2026.13)]
- [2026] **The Meld ISA: Complex-MGE, Quantum Algorithm Discovery, and the T-Gate as Octonion Obstruction** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20773563)]
- [2026] **Acc-VQLS: Accelerated Variational Quantum Linear Solver for VSC Simulation** *ACM Transactions on Quantum Computing* [[paper](https://doi.org/10.1145/3821429)]
- [2026] **Cardinality-Aware Quantum Retrieval for Large-Scale Predicate Matching in Big Data Systems** *Data Science & Big Data Technology* [[paper](https://doi.org/10.63646/ibmy3458)]
- [2026] **The Cookie-Cutter Lifting Programme: Shor as a Clifford Circuit** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20955521)]
- [2026] **N-K UNIVERSAL COMPUTER AND HARD COMPUTING PROBLEMS** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20735293)]
- [2026] **On the Complexity of the Circuit Width Problem** [[paper](https://arxiv.org/abs/2606.18201)]
- [2026] **Unobservables and Decoherence from Complexity** [[paper](https://arxiv.org/abs/2606.20927)]
- [2026] **Exponential Quantum Space Advantage for Approximating Max-$k$SAT in the Streaming Setting** [[paper](https://arxiv.org/abs/2606.05366)]
- [2026] **Worst-case depth hierarchy for shallow quantum circuits** [[paper](https://arxiv.org/abs/2606.16425)]
- [2026] **Quantum Kravchuk Transform using $\mathfrak{su}(2)$ fast-forwarding** [[paper](https://arxiv.org/abs/2606.08443)]
- [2026] **Probabilistically Checking Quantum Proofs, with Interaction** [[paper](https://arxiv.org/abs/2606.09588)]
- [2026] **Quantum-Classical Equivalence for AND-Functions** [[paper](https://arxiv.org/abs/2606.03249)]
- [2026] **Approximability limits for bounded-degree max-LINSAT and implications for decoded quantum interferometry** [[paper](https://arxiv.org/abs/2606.13570)]
- [2026] **Quantum Lazy Sampling and Path Recording for Any Group** [[paper](https://arxiv.org/abs/2606.30281)]
- [2026] **A Modular Approach to Succinct Arguments for QMA** [[paper](https://arxiv.org/abs/2606.10408)]
- [2026] **Quantum Advantage in Tolerant Junta Testing** [[paper](https://arxiv.org/abs/2606.23194)]
- [2026] **Genuine Global Kochen-Specker Contextuality as Classical Coordination Cost** [[paper](https://arxiv.org/abs/2606.23577)]
- [2026] **Scaling Laws for Neural-Network Quantum States** [[paper](https://arxiv.org/abs/2606.02794)]
- [2026] **The Observer World: A Cryptographic Extension of Impagliazzo's Five Worlds** [[paper](https://arxiv.org/abs/2606.27139)]
- [2026] **Collision Resistance of Single-Layer Neural Nets** [[paper](https://arxiv.org/abs/2606.03807)]
- [2026] **The Physical Impossibility of Quantum Computational Speedup** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19622607)]
- [2026] **An Entropy-Governed Speedup for Quantum Algorithms on Local Hamiltonians** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.18241)]
- [2026] **From Hilbert's Tenth Problem to Quantum Speedup: Explicit Oracles for Bounded Diophantine Systems** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.13980)]
- [2026] **EFaaS: A Quantum-Classical Serverless Entangled Scheduler for Hybrid Variational Algorithms** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.27540)]
- [2026] **A Controlled Study of Memory Hierarchy Transitions in Quantum Circuit Simulation on Apple M4 Pro Unified Memory Architecture** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.08792)]
- [2026] **Quantum Walks for Collision-Based Information Set Decoding** [[paper](https://doi.org/10.1145/3801487.3801826)]
- [2026] **Linear-Time T-Gate Optimization via Random Abstraction** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.13929)]
- [2026] **TEMPORAL ROTATION SECURITY PROTOCOL (TRSP) Physics-First Cryptographic Architecture: Time as the Fundamental Security Parameter** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20324081)]
- [2026] **Quantum state isomorphism problems for groups** [[paper](https://arxiv.org/abs/2605.12615)]
- [2026] **A Critical Comment on 'Entropy Computing: A Paradigm for Optimization in Open Photonic Systems'** [[paper](https://arxiv.org/abs/2605.03612)]
- [2026] **Elfs, transducers and quantum walks** [[paper](https://arxiv.org/abs/2605.30013)]
- [2026] **Rounding Almost Commuting Hamiltonians** [[paper](https://arxiv.org/abs/2605.26096)]
- [2026] **Quantum algorithms for path and cycle containment problems** [[paper](https://arxiv.org/abs/2605.09017)]
- [2026] **Simulation of Non-Hermitian Hamiltonians with Bivariate Quantum Signal Processing** [[paper](https://arxiv.org/abs/2605.12450)]
- [2026] **A sharp interaction-degree threshold for simulating QAOA** [[paper](https://arxiv.org/abs/2605.22758)]
- [2026] **Extensive long-range magic in non-Abelian topological orders** [[paper](https://arxiv.org/abs/2605.15150)]
- [2026] **A quantum gradient descent algorithm for optimizing Gaussian process models** *Mathematical Models and Methods in Applied Sciences* [[paper](https://doi.org/10.1142/s0218202526420042)]
- [2026] **Demonstration of Exponential Quantum Speedup with Constant-Depth Compiled Circuits for Simon's Problem** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.27457)]
- [2026] **Scalable multi-objective genetic algorithm for quantum circuit optimization** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-47674-5)]
- [2026] **Simon's Algorithm for the Even-Mansour Cipher on Quantum Hardware** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.25509)]
- [2026] **Partial oracles quantum algorithm framework -- Part I: Analysis of in-place operations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.21788)]
- [2026] **Quantum Statistical Bootstrap** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.00951)]
- [2026] **Commutator Obstruction to Quantum Advantage: A Spectral Confinement Theorem for Quantum Heuristics** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19476258)]
- [2026] **Quantum Search without Global Diffusion** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.15435)]
- [2026] **Distributed Variational Quantum Linear Solver** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.14435)]
- [2026] **HHL with a Coherent Fourier Oracle: A Proof-of-Concept Quantum Architecture for Joint Melody-Harmony Generation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.20882)]
- [2026] **A Comparative Analysis of Quantum Computational Paradigms in Medical Imaging and Diagnostics: A Comprehensive Review** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19880686)]
- [2026] **A Landscape Classification Framework for NP-Hard Problems: From Reconnaissance to Algorithm Selection** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19510539)]
- [2026] **Topological Z/6Z Superselection: Analytic Phase Derivation and Dissipative Stabilization for FTQC Cryptanalysis** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19354011)]
- [2026] **A Relativizing MIP for BQP** [[paper](https://arxiv.org/abs/2604.11952)]
- [2026] **IQP circuits for 2-Forrelation** [[paper](https://arxiv.org/abs/2604.15248)]
- [2026] **Quantum polymorphism characterisation of commutativity gadgets in all quantum models** [[paper](https://arxiv.org/abs/2604.01408)]
- [2026] **Dequantizing Short-Path Quantum Algorithms** [[paper](https://arxiv.org/abs/2604.12131)]
- [2026] **On quantum functionals for higher-order tensors** [[paper](https://arxiv.org/abs/2604.18283)]
- [2026] **Quantum embedding of graphs for subgraph counting** [[paper](https://arxiv.org/abs/2604.18754)]
- [2026] **Quantum Property Testing for Bounded-Degree Directed Graphs** [[paper](https://arxiv.org/abs/2604.07954)]
- [2026] **Strict Hierarchy for Quantum Channel Certification to Unitary** [[paper](https://arxiv.org/abs/2604.26900)]
- [2026] **Parity $\notin$ QAC0 $\iff$ QAC0 is Fourier-Concentrated** [[paper](https://arxiv.org/abs/2604.02793)]
- [2026] **Learning and Generating Mixed States Prepared by Shallow Channel Circuits** [[paper](https://arxiv.org/abs/2604.01197)]
- [2026] **The Quantum Query Complexity of Finding a Tarski Fixed Point on the 2D Grid** [[paper](https://arxiv.org/abs/2604.08223)]
- [2026] **Reachability Constraints in Variational Quantum Circuits: Optimization within Polynomial Group Module** [[paper](https://arxiv.org/abs/2604.13735)]
- [2026] **DQC1-completeness of normalized trace estimation for functions of log-local Hamiltonians** [[paper](https://arxiv.org/abs/2604.01519)]
- [2026] **The Exact Replica Threshold for Nonlinear Moments of Quantum States** [[paper](https://arxiv.org/abs/2604.22627)]
- [2026] **The power of unentanglement without destructive interference** [[paper](https://arxiv.org/abs/2604.27886)]
- [2026] **En Route to a Standard QMA1 vs. QCMA Oracle Separation** [[paper](https://arxiv.org/abs/2604.26921)]
- [2026] **Coherent-State Propagation: A Computational Framework for Simulating Bosonic Quantum Systems** [[paper](https://arxiv.org/abs/2604.19625)]
- [2026] **Optimality of Quantum Adiabatic Search Algorithm and Its Circuit Model** *Quantum Reports* [[paper](https://doi.org/10.3390/quantum8020028)]
- [2026] **Neural Quantum Manifold Forging (NQF): A High-Performance Rust Framework for Dynamic Circuit Topology and Hybrid Quantum-Classical Convergence** *OSF Preprints (OSF Preprints)* [[paper](https://osf.io/h6b3w)]
- [2026] **Practical Guide to Quantum Computing: Grover's Algorithm # 4** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18865416)]
- [2026] **Hybrid Quantum Classical Acceleration of Machine Learning Algorithms: A Performance Study** *Springer Link (Chiba Institute of Technology)* [[paper](https://www.epj-conferences.org/10.1051/epjconf/202636001011/pdf)]
- [2026] **Quadratically Fast Searching in Quantum Computation** [[paper](https://doi.org/10.1201/9781003674818-21)]
- [2026] **Quantum Machine Learning: A Comprehensive Scientific Review From Foundational Algorithms to 2026 State-of-the-Art** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19175660)]
- [2026] **Practical Guide to Using a Quantum Computer (Based on Materials from the International Quantum Center at CERN, Switzerland) # 7** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18861780)]
- [2026] **Practical Guide to Using a Quantum Computer (Based on Materials from the International Quantum Center at CERN, Switzerland) # 6** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18861744)]
- [2026] **GroverGPT: A Large Language Model with 8 Billion Parameters for Quantum Searching** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-8816953/v1)]
- [2026] **Practical Guide to Quantum Computing: Phase Estimation and Factoring # 3** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18865351)]
- [2026] **RotorMap and Quantum Fingerprints of DNA Sequences via Rotary Position Embeddings** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.22245)]
- [2026] **Risk Analysis of Information Security Violations and Vulnerabilities in Information Processing Systems: Grover's Algorithm** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18865592)]
- [2026] **Fractal Correction Engine Applied to Integer Factorization: A Comprehensive Investigation of Classical Period-Finding and Its Fundamental Limits** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18945844)]
- [2026] **Complexity of Quadratic Bosonic Hamiltonian Simulation: $\mathsf{BQP}$-Completeness and $\mathsf{PostBQP}$-Hardness** [[paper](https://arxiv.org/abs/2603.26561)]
- [2026] **Has quantum advantage been achieved?** [[paper](https://arxiv.org/abs/2603.09901)]
- [2026] **Quantum Algorithms for Approximate Graph Isomorphism Testing** [[paper](https://arxiv.org/abs/2603.02656)]
- [2026] **A Perfectly Distributable Quantum-Classical Algorithm for Estimating Triangular Balance in a Signed Edge Stream** [[paper](https://arxiv.org/abs/2603.16029)]
- [2026] **The color code, the surface code, and the transversal CNOT: NP-hardness of minimum-weight decoding** [[paper](https://arxiv.org/abs/2603.22064)]
- [2026] **Classical simulability of quantum circuits followed by sparse classical post-processing** [[paper](https://arxiv.org/abs/2603.05920)]
- [2026] **Towards Exponential Quantum Improvements in Solving Cardinality-Constrained Binary Optimization** [[paper](https://arxiv.org/abs/2603.14744)]
- [2026] **Quantum information advantage based on Bell inequalities** [[paper](https://arxiv.org/abs/2603.07930)]
- [2026] **Exponential Separation of Quantum and Classical One-Way Numbers-on-Forehead Communication** [[paper](https://arxiv.org/abs/2603.22795)]
- [2026] **Search-Driven Clause Learning for Product-State Quantum $k$-SAT (PRODSAT-QSAT)** [[paper](https://arxiv.org/abs/2603.20038)]
- [2026] **Certifying and learning local quantum Hamiltonians** [[paper](https://arxiv.org/abs/2603.29809)]
- [2026] **Random tensor isomorphism under orthogonal and unitary actions** [[paper](https://arxiv.org/abs/2603.27128)]
- [2026] **Quantum linear solvers for scientific computing: a comparison of VQLS, HHL and quantum annealing on time-fractional diffusion problems** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-40910-y)]
- [2026] **Toward speedup without quantum coherent access** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.20781)]
- [2026] **Neural-Plasma Algorithm for Drift-Resistant Lattice Optimization in ML-KEM: Empirical Validation and Quantum Adversarial Resilience** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18727591)]
- [2026] **Introduction to Quantum Computing** *Auerbach Publications eBooks* [[paper](https://doi.org/10.1201/9781003674566-1)]
- [2026] **Dequantization Barriers for Guided Stoquastic Hamiltonians** [[paper](https://arxiv.org/abs/2602.23183)]
- [2026] **On the Need for (Quantum) Memory with Short Outputs** [[paper](https://arxiv.org/abs/2602.23763)]
- [2026] **A 1-bit quantum filter for particle trajectory reconstruction** *Communications Physics* [[paper](https://arxiv.org/abs/2601.07766)]

##### 2025

- [2025] **Multi-GPU quantum circuit simulation and the impact of network performance** *Computer Physics Communications* [[paper](https://arxiv.org/abs/2511.14664)]
- [2025] **End-to-end quantum algorithm for topology optimization in structural mechanics** *Quantum Science and Technology* [[paper](https://arxiv.org/abs/2510.07280)]
- [2025] **Quantum Matrix Arithmetics with Hamiltonian Evolution** *ACM Transactions on Quantum Computing* [[paper](https://arxiv.org/abs/2510.06316)]
- [2025] **Continuous-time quantum-walk-based ansätze on neutral-atom hardware** *Physical Review A* [[paper](https://arxiv.org/abs/2509.00386)]
- [2025] **Quantum circuits for the Metropolis–Hastings algorithm** *Journal of Physics A Mathematical and Theoretical* [[paper](https://arxiv.org/abs/2506.11576)]
- [2025] **Deterministic quantum search for arbitrary initial success probabilities** *Quantum Information Processing* [[paper](https://arxiv.org/abs/2505.15512)]
- [2025] **Quantum simulation-based optimization for cooling system design** *Journal of Physics A Mathematical and Theoretical* [[paper](https://arxiv.org/abs/2504.15460)]
- [2025] **Advancing scientific discovery and complex optimization through distributed quantum neural networks** *npj Computational Materials* [[paper](https://arxiv.org/abs/2503.00221)]
- [2025] **Real-Time Sign-Problem-Suppressed Quantum Monte Carlo Algorithm for Noisy Quantum Circuit Simulations** *Physical Review Letters* [[paper](https://arxiv.org/abs/2502.18929)]

##### 2024

- [2024] **On Estimating the Trace of Quantum State Powers** *IEEE Transactions on Information Theory* [[paper](https://arxiv.org/abs/2410.13559)]
- [2024] **Distributed quantum approximate optimization algorithm on a quantum-centric supercomputing architecture** *npj Quantum Information* [[paper](https://arxiv.org/abs/2407.20212)]
- [2024] **Attribute fusion-based evidential classifier on quantum circuits** *Quantum Machine Intelligence* [[paper](https://arxiv.org/abs/2401.01392)]

[⬆ Back to top](#paper-list)

#### Method

##### 2026

- [2026] **Aicir: A Full-Stack Quantum Circuit Simulator with AscendNPU Support** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.09733)]
- [2026] **Quantum Key Search Algorithms under Side-channel Attack** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-10245840/v1)]
- [2026] **QForge™ A Next-Generation Engineering Platform for Scalable Quantum Computing Design, Verification, and Industrial Algorithm Development** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21857594)]
- [2026] **Quantum Speedups Require Structure or Depth** [[paper](https://arxiv.org/abs/2608.19158)]
- [2026] **Quantum circuit optimization using deep reinforcement learning: Applications across multiple gate sets** [[paper](https://arxiv.org/abs/2608.19103)]
- [2026] **Parallel Quantum Advantage with Limited Adaptivity Requires Structure** [[paper](https://arxiv.org/abs/2608.20297)]
- [2026] **Breaking the Curse of Dimensionality in Quantum PDE Solvers via Gevrey Regularity** [[paper](https://arxiv.org/abs/2608.07893)]
- [2026] **Efficient Quantum Modular Reduction: Crandall reduction and its Fault-tolerant resource analysis** [[paper](https://arxiv.org/abs/2608.11563)]
- [2026] **Gate-based emulation of boson sampling using photonic qubits** [[paper](https://arxiv.org/abs/2608.09509)]
- [2026] **Matrix Product Evolution: A Method for Simulating Quantum Circuits Using Tensor Networks** [[paper](https://arxiv.org/abs/2608.03472)]
- [2026] **Rethinking Quantum Circuits** [[paper](https://arxiv.org/abs/2608.19370)]
- [2026] **Qu-Trefoil: Large-Scale Quantum Circuit Simulator Working on FPGA With SATA Storages** [[paper](https://arxiv.org/abs/2608.14285)]
- [2026] **Witnessing the architecture of quantum circuits** [[paper](https://arxiv.org/abs/2608.13169)]
- [2026] **GPU-Accelerated A* Search with Deep Neural Network Heuristics** *Proceedings of the International Symposium on Combinatorial Search* [[paper](https://doi.org/10.1609/socs.v19i1.43083)]
- [2026] **Quantum algorithm for Clifford multiplication** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.10473)]
- [2026] **C-3PQ: A Closeness Centrality-based Circuit Partitioner for Quantum Simulations** [[paper](https://doi.org/10.1145/3797905.3807864)]
- [2026] **Quantum Bit-Parallel Swap Matching** [[paper](https://doi.org/10.1145/3806645.3816165)]
- [2026] **The potential of quantum computers for Particle Image Velocimetry** [[paper](https://arxiv.org/abs/2607.13641)]
- [2026] **Molecular Docking with Quantum Circuit Evolution** [[paper](https://arxiv.org/abs/2607.12060)]
- [2026] **Feynman's clock and hierarchy-informed sampling for quantum error mitigation** [[paper](https://arxiv.org/abs/2607.06752)]
- [2026] **Parametrized-circuit-free quantum regression with variance regularization** [[paper](https://arxiv.org/abs/2607.02696)]
- [2026] **DQAOA-GPT: AI-Accelerated Distributed Quantum Optimization for Combinatorial Problems** [[paper](https://arxiv.org/abs/2607.20225)]
- [2026] **Quantum algorithms for second-order boundary value problems** [[paper](https://arxiv.org/abs/2607.11410)]
- [2026] **Comparing and learning figures of merit for quantum circuit compilation** [[paper](https://arxiv.org/abs/2607.03275)]
- [2026] **Quantum Channel Polynomial Processing** [[paper](https://arxiv.org/abs/2607.06557)]
- [2026] **How Many Shots Does It Take? A Noise-Aware Quantum Resource Allocation Framework** [[paper](https://arxiv.org/abs/2607.24704)]
- [2026] **MOSAIQC: Mixed-topology-aware Optimization for Scalable Approximate noise-Informed Quantum circuit Cutting** [[paper](https://arxiv.org/abs/2607.18888)]
- [2026] **Nearly optimal quantum circuits for Boolean oracles** [[paper](https://arxiv.org/abs/2607.28402)]
- [2026] **Building Shor's Algorithm in Lean: An Agentic Formalization of Quantum Attacks on RSA-2048 and P-256** [[paper](https://arxiv.org/abs/2607.14082)]
- [2026] **Strategic Plan for Neutral Atom Quantum Computation** [[paper](https://arxiv.org/abs/2607.21554)]
- [2026] **Variational Learning with Sparse Long-range Entangling Gates** [[paper](https://arxiv.org/abs/2607.07547)]
- [2026] **HamQASBench: A Hamiltonian-Informed Diagnostic Benchmark for Evaluating Quantum Architecture Search** [[paper](https://arxiv.org/abs/2607.04845)]
- [2026] **Dependency-Aware Circuit Scheduling for Multi-Core Quantum Systems to Minimize Makespan** [[paper](https://arxiv.org/abs/2607.00469)]
- [2026] **CutBackdoor: A Circuit Cut Triggered Backdoor Attack on Variational Quantum Algorithms** [[paper](https://arxiv.org/abs/2607.18126)]
- [2026] **Multiple-shooting for Optimal Control of Quantum Dynamics** [[paper](https://doi.org/10.2172/3389358)]
- [2026] **A qubit-efficient boolean quantum oracle for value-at-risk estimation in NISQ devices** *Physica Scripta* [[paper](https://doi.org/10.1088/1402-4896/ae89f6)]
- [2026] **🌀 LRO-κ⁸ SPINE + 3.1.3 MASTER FILE including cross platform LRO-κ⁸ SPINE + 3.1: A Geometric Control Language for Quantum-Holographic Field Manipulation – Extended AI Migration Protocol with Holographic GPU, Quantum Circuit Execution, Volumetric Field-Effect Display, Automatic C/Rust Kernel Generation, and Official Verification Suite. Including LRO-κ⁸ QUANTUM PLATFORM PATCH — CHINA EDUCATIONAL DEPLOYMENT** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21308155)]
- [2026] **LRO-κ⁸ SPINE + 3.1 A Geometry-Aware Systems Language for Quantum-Holographic Field Manipulation. The Bridge Between Analytical Physics and Production-Grade Machine Code — 1,708× Faster than C, Rust, and Zig for Field Geometry Problems — With Full Conventional Code Support and Self-Propagating AI Migration Bootloader** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21306965)]
- [2026] **LRO-κ⁸ SPINE + 3.1.2 : A Geometry-Aware Systems Language for Quantum-Holographic Field Manipulation Subtitle: The Bridge Between Analytical Physics and Production-Grade Machine Code — 1,708× Faster than C, Rust, and Zig for Field Geometry Problems — With Full Conventional Code Support, Self-Propagating AI Migration Bootloader, and Universal Cross-Platform Compatibility** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21307429)]
- [2026] **Communication-Partition Co-Optimization for Quantum Circuit Simulation on CPU+GPU Clusters** *IEEE Transactions on Parallel and Distributed Systems* [[paper](https://doi.org/10.1109/tpds.2026.3678345)]
- [2026] **Hybrid Quantum-Classical Implementation of the HHL Algorithm: Total Code and Reproducibility Package** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20714901)]
- [2026] **Provable Quantum Advantage for Dynamical Phase Transition** [[paper](https://arxiv.org/abs/2606.30396)]
- [2026] **An efficient quantum Hadamard product algorithm for functions** [[paper](https://arxiv.org/abs/2606.03612)]
- [2026] **How to make quantum cheese: efficient geometry oracles for exponentially many pseudorandom microstructures** [[paper](https://arxiv.org/abs/2606.00222)]
- [2026] **Quantum Circuit Realization of the PPT and CCNR Criteria** [[paper](https://arxiv.org/abs/2606.29769)]
- [2026] **How Many Shots Are Enough for a Quantum Circuit?** [[paper](https://arxiv.org/abs/2606.16965)]
- [2026] **Optimizing resource allocation for accuracy in noisy variational quantum algorithms** [[paper](https://arxiv.org/abs/2606.20153)]
- [2026] **Quantum Signal Processing for Linear PDEs: Circuit Design and Experimental Validation** [[paper](https://arxiv.org/abs/2606.00368)]
- [2026] **Quantum circuit decomposition of the tangent-fermion Dirac operator** [[paper](https://arxiv.org/abs/2606.19020)]
- [2026] **Projector Quantum Variational Ansatz** [[paper](https://arxiv.org/abs/2606.07084)]
- [2026] **Q-DICE: Quantum Distributed Interconnect Compiler and Emulator** [[paper](https://arxiv.org/abs/2606.11340)]
- [2026] **Scalable Message-Passing Quantum Graph Neural Networks in the Weisfeiler-Leman Hierarchy** [[paper](https://arxiv.org/abs/2606.26873)]
- [2026] **Towards an Optimally Distributed Quantum Fourier Transform Circuit** [[paper](https://arxiv.org/abs/2606.18494)]
- [2026] **Challenges in Barren Plateau Mitigation with Dynamic Parameterized Quantum Circuits** [[paper](https://arxiv.org/abs/2606.23751)]
- [2026] **Quantum algorithm for the nonlinear Schrödinger equation via the Lax-pair scattering** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.29276)]
- [2026] **Quantum-enhanced Monte Carlo Tree Search framework for combinatorial optimization problems** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.30415)]
- [2026] **Quantum Thermal Logic Gates** [[paper](https://arxiv.org/abs/2606.06432)]
- [2026] **Iterative Matrix Product State Simulation for Scalable Grover’s Algorithm** [[paper](https://doi.org/10.1109/icassp55912.2026.11461240)]
- [2026] **A Demonstration of Quantum Circuit Implementation for Obstacle Flow Using Carleman-Linearized Lattice Boltzmann Method** [[paper](https://arxiv.org/abs/2605.28135)]
- [2026] **Shortest Path in Pauli Forest -- An Algorithm for Decomposing Pauli Exponentials to Quantum Circuits** [[paper](https://arxiv.org/abs/2605.03545)]
- [2026] **Loop Composition in Quantum Algorithms** [[paper](https://arxiv.org/abs/2605.07518)]
- [2026] **Optimal Approximation of Single Qubit Rotations within a Quantum Circuit** [[paper](https://arxiv.org/abs/2605.09671)]
- [2026] **Quantum Multi-Level Estimation of Functionals of Discrete Distributions** [[paper](https://arxiv.org/abs/2605.03685)]
- [2026] **Second-Order FALQON Parameter Transfer for the Max-Cut Problem on 3-Regular Graphs** [[paper](https://arxiv.org/abs/2605.04253)]
- [2026] **Zero-shot Quantum Neural Architecture Search** [[paper](https://arxiv.org/abs/2605.27410)]
- [2026] **Adversarial Effects on Expressibility and Trainability in Distributed Variational Quantum Algorithms** [[paper](https://arxiv.org/abs/2605.03629)]
- [2026] **Quantum Decoding Algorithms: Quantum Speedups in Optimization** [[paper](https://arxiv.org/abs/2605.00312)]
- [2026] **A Variational Dissipative Framework for Quantum Algorithms** [[paper](https://arxiv.org/abs/2605.25841)]
- [2026] **Automated Circuit Depth Reduction of Quantum Subroutines via Compilation** [[paper](https://arxiv.org/abs/2605.04748)]
- [2026] **A Variational Quantum Algorithm for Nonlinear Finite Element Analysis of Hyperelastic Materials** [[paper](https://arxiv.org/abs/2605.29181)]
- [2026] **Distributed Quantum Circuit Optimisation: Evaluating Global and Local encodings** [[paper](https://arxiv.org/abs/2605.02727)]
- [2026] **Modeling and Resource Optimization for Quantum Oracles** [[paper](https://arxiv.org/abs/2605.21380)]
- [2026] **Structural $f$-divergence: Tight universal bounds for cost function moments and gradients in parameterized quantum circuits** [[paper](https://arxiv.org/abs/2605.18051)]
- [2026] **Practical Log-Depth Quantum State Preparation and Circuit Verification via Tree Tensor Network Compilation** [[paper](https://arxiv.org/abs/2605.06579)]
- [2026] **Combining non-parametric quantum states and MERA tensor networks for ground-state optimization** [[paper](https://arxiv.org/abs/2605.21447)]
- [2026] **Diagonal Adaptive Non-local Observables on Quantum Neural Networks** [[paper](https://arxiv.org/abs/2605.15410)]
- [2026] **Efficient quantum algorithm for linear matrix differential equations and applications to open quantum systems** [[paper](https://arxiv.org/abs/2605.16195)]
- [2026] **ffsim: Faster simulation of fermionic quantum circuits** [[paper](https://arxiv.org/abs/2605.03123)]
- [2026] **Fault Tolerant Quantum Computing with Lower Overhead** *UNM’s Digital Repository (University of New Mexico)* [[paper](https://digitalrepository.unm.edu/ece_etds/777)]
- [2026] **Accelerating State-Vector Quantum Simulation on Integrated GPUs via Cache Locality Optimization: A Cross-Architecture Evaluation** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.15098)]
- [2026] **Hybrid Gaussian-exponential zero-noise extrapolation for periodic circuits** [[paper](https://arxiv.org/abs/2605.29242)]
- [2026] **A Semantic Quantum Circuit Cache for Scalable and Distributed Quantum-Classical Workflows** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.26788)]
- [2026] **Grover Quantum Algorithm: Applications and Limits** *Encyclopedia* [[paper](https://doi.org/10.3390/encyclopedia6040089)]
- [2026] **Explicit Quantum Search Algorithm for the Densest k-Subgraph Problem** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.27782)]
- [2026] **Large-Scale Quantum Circuit Simulation on HPC Cluster via Cache Blocking, Boosting, and Gate Fusion Optimization** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.12256)]
- [2026] **A Fully Quantum Algorithm for Image Edge Detection** [[paper](https://arxiv.org/abs/2604.23535)]
- [2026] **Exponentially-improved effective descriptions of physical bosonic systems** [[paper](https://arxiv.org/abs/2604.18720)]
- [2026] **Learning error suppression strategies for dynamic quantum circuits** [[paper](https://arxiv.org/abs/2604.18734)]
- [2026] **Recent Advances in Quantum Architecture Search** [[paper](https://arxiv.org/abs/2604.26289)]
- [2026] **Q-LINK: Quantum Layerwise Information Residual Network via a Messenger Qubit for Barren Plateaus Mitigation** [[paper](https://arxiv.org/abs/2604.11831)]
- [2026] **Quantum algorithms for the fractional Poisson equation via rational approximation** [[paper](https://arxiv.org/abs/2604.00603)]
- [2026] **Computing the free energy of quantum Coulomb gases and molecules via quantum Gibbs sampling** [[paper](https://arxiv.org/abs/2604.15263)]
- [2026] **Efficient $n$-qubit entangling operations via a superconducting quantum router** [[paper](https://arxiv.org/abs/2604.15432)]
- [2026] **QMC-Net: Data-Aware Quantum Representations for Remote Sensing Image Classification** [[paper](https://arxiv.org/abs/2604.11817)]
- [2026] **On the importance of hyperparameters in initializing parameterized quantum circuits** [[paper](https://arxiv.org/abs/2604.21266)]
- [2026] **A Review of Variational Quantum Algorithms: Insights into Fault-Tolerant Quantum Computing** [[paper](https://arxiv.org/abs/2604.07909)]
- [2026] **GreenPeas: Unlocking adaptive quantum error correction with just-in-time decoding hypergraphs** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.16613)]
- [2026] **GPU-Accelerated Quantum Simulation: Empirical Backend Selection, Gate Fusion, and Adaptive Precision** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.03816)]
- [2026] **Exploring Quantum-Enhanced AI Models in Distributed Cloud Systems** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19660283)]
- [2026] **Towards High Performance Quantum Computing (HPQ): Parallelisation of the Hamiltonian Auto Decomposition Optimisation Framework (HADOF)** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.27836)]
- [2026] **QR-SPPS: Quantum-Native Retail Supply Chain Risk Simulation via VQE, ADAPT-VQE Counterfactual Policy Ranking, and DOS-QPE Boltzmann Tail Risk Quantification** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.00035)]
- [2026] **Database Reordering for Compact Grover Oracles with ESOP Minimization** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.06578)]
- [2026] **Polylogarithmic-Weight Dicke States in QAC$^0$ and Arbitrary Symmetric States in QAC$^0_f$** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.15298)]
- [2026] **Efficient Time-Aware Partitioning of Quantum Circuits for Distributed Quantum Computing** [[paper](https://arxiv.org/abs/2603.04126)]
- [2026] **GPU-Accelerated Quantum Simulation of Stabilizer Circuits** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.14641)]
- [2026] **Practical Experience with IBM Q Quantum Computer: Bernstein–Vazirani Algorithm** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18865682)]
- [2026] **Hybrid Circuit–Spintronic Quantum Framework for Financial Risk Analysis with QCVaR Estimation Using Variational Quantum Algorithms and Maximum-Likelihood Amplitude Estimation** *Quantum Information and Computation* [[paper](https://doi.org/10.2478/qic-2026-0002)]
- [2026] **EQISA: Energy-efficient Quantum Instruction Set Architecture using Sparse Dictionary Learning** [[paper](https://arxiv.org/abs/2603.20646)]
- [2026] **Quantum Algorithms for Network Signal Coordination** [[paper](https://arxiv.org/abs/2603.04758)]
- [2026] **Asymptotically Optimal Quantum Circuits for Comparators and Incrementers** [[paper](https://arxiv.org/abs/2603.12917)]
- [2026] **Improved quantum circuits for division** [[paper](https://arxiv.org/abs/2603.18110)]
- [2026] **Distributed Quantum Computing via Adaptive Circuit Knitting** [[paper](https://arxiv.org/abs/2603.12411)]
- [2026] **Quantum Riemannian Hamiltonian Descent** [[paper](https://arxiv.org/abs/2603.28624)]
- [2026] **Explicit Block Encodings of Discrete Laplacians with Mixed Boundary Conditions** [[paper](https://arxiv.org/abs/2603.12405)]
- [2026] **Full-quantum variational dynamics simulation for time-dependent Hamiltonians with global spectral discretization** [[paper](https://arxiv.org/abs/2603.17062)]
- [2026] **Fisher information based lower bounds on the cost of quantum phase estimation** [[paper](https://arxiv.org/abs/2603.12706)]
- [2026] **Hamiltonian Simulation and Linear Combination of Unitary Decomposition of Structured Matrices** [[paper](https://arxiv.org/abs/2603.17816)]
- [2026] **Efficient equivalence checking of Clifford-U circuits with shared single-qubit unitaries** [[paper](https://arxiv.org/abs/2603.12697)]
- [2026] **Fault-tolerant execution of error-corrected quantum algorithms** [[paper](https://arxiv.org/abs/2603.04584)]
- [2026] **Efficiently architecting VQAs: Expressibility--Trainability--Resources Pareto-Optimality** [[paper](https://arxiv.org/abs/2603.22142)]
- [2026] **Dynamics of Many-Emitter Ensembles: Probing Cooperative Evolution with Scalable Quantum Circuits** [[paper](https://arxiv.org/abs/2603.12563)]
- [2026] **Logical-to-Physical Compilation for Reducing Depth in Distributed Quantum Systems** [[paper](https://arxiv.org/abs/2603.29536)]
- [2026] **Fast and memory-efficient classical simulation of quantum machine learning via forward and backward gate fusion** [[paper](https://arxiv.org/abs/2603.02804)]
- [2026] **How to find expressible and trainable parameterized quantum circuits?** [[paper](https://arxiv.org/abs/2603.14451)]
- [2026] **Towards Noise-Resilient Quantum Multi-Armed and Stochastic Linear Bandits** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.18431)]
- [2026] **Parallel iQCC Enables 200 Qubit Scale Quantum Chemistry on Accelerated Computing Platforms Surpassing Classical Benchmarks in Ruthenium Catalysts** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.08883)]
- [2026] **Imperfect Graphs from Unitary Matrices -- I** [[paper](https://arxiv.org/abs/2602.21808)]
- [2026] **Numerical Experiments with Parameter Setting of Trotterized Quantum Phase Estimation for Quantum Hamiltonian Ground State Computation** [[paper](https://arxiv.org/abs/2602.22349)]
- [2026] **Quantum circuit design from a retraction-based Riemannian optimization framework** [[paper](https://arxiv.org/abs/2602.20605)]
- [2026] **Q-Tag: Watermarking Quantum Circuit Generative Models** [[paper](https://arxiv.org/abs/2602.23085)]
- [2026] **MAFFT-inspired Quantum Shift-based Sequence Alignment and its Efficient Simulation on Decision Diagrams** [[paper](https://arxiv.org/abs/2602.23848)]

##### 2025

- [2025] **Cobble: Compiling Block Encodings for Quantum Computational Linear Algebra** *Proceedings of the ACM on Programming Languages* [[paper](https://arxiv.org/abs/2511.01736)]
- [2025] **Combinatorial optimization enhanced by shallow quantum circuits with 104 superconducting qubits** *National Science Review* [[paper](https://arxiv.org/abs/2509.11535)]
- [2025] **A modular, adaptive, and scalable quantum factoring algorithm** *The European Physical Journal Plus* [[paper](https://arxiv.org/abs/2509.05010)]
- [2025] **Quantum-classical auxiliary field quantum Monte Carlo with matchgate shadows on trapped ion quantum computers** *Physical Review Research* [[paper](https://arxiv.org/abs/2506.22408)]
- [2025] **Iterative Quantum Feature Maps** *Advanced Quantum Technologies* [[paper](https://arxiv.org/abs/2506.19461)]
- [2025] **Efficient Compilation for Shuttling Trapped-Ion Machines via the Position Graph Architectural Abstraction** *ACM Transactions on Quantum Computing* [[paper](https://arxiv.org/abs/2501.12470)]

##### 2014

- [2014] **A Quantum Approximate Optimization Algorithm** [[paper](https://arxiv.org/abs/1411.4028)]

##### 2013

- [2013] **A Variational Eigenvalue Solver on a Quantum Processor** *Nature Communications 5, 4213 (2014)* [[paper](https://arxiv.org/abs/1304.3061)]

[⬆ Back to top](#paper-list)

#### Application

##### 2026

- [2026] **Application and optimization of quantum-powered generative models for job shop scheduling in semiconductor manufacturing** *Journal of Industrial Information Integration* [[paper](https://doi.org/10.1016/j.jii.2026.101115)]

[⬆ Back to top](#paper-list)

### Quantum Error Correction

#### Theory

##### 2026

- [2026] **Fault-Tolerant Quantum Computation: Architectural Trade-Offs Between Surface Codes, Color Codes, and Quantum LDPC Codes** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21981195)]
- [2026] **QECTOR Decoder v3: Syndrome-Faithful Decoding - Foundations, Algorithms, and Architecture of a Fifteen-Backend Quantum Error Correction Engine** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21941045)]
- [2026] **The Nine‑Node Coherence Engine: A Coherence‑First Framework for Graphene‑Based Quantum Architectures** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20903218)]
- [2026] **Finite Distinction Maintenance in Fault-Tolerant Quantum Computation Logical Distinction Ledgers, Error-Correction Infrastructure, and Architecture-Specific Resource Bounds** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20302569)]
- [2026] **Concatenating Algebraic Codes over High-Rate Quantum LDPC Codes** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.21898)]
- [2026] **Quantum Error Correction and Fault-Tolerant Quantum Computing: Principles, Progress, and Future Directions** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20176500)]
- [2026] **Green quantum computing: evaluating energy efficient error correction mechanisms** *Proceedings of the Indian National Science Academy* [[paper](https://doi.org/10.1007/s43538-026-00737-7)]
- [2026] **Information-Theoretic Framework for Quantum State Purification and Error Correction via Entropy Compression Mechanisms** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202604.2029.v1)]

##### 2025

- [2025] **A simple universal routing strategy for reducing the connectivity requirements of quantum LDPC codes** *Research Square* [[paper](https://arxiv.org/abs/2509.00850)]

##### 2024

- [2024] **An almost-linear time decoding algorithm for quantum LDPC codes under circuit-level noise** *npj Quantum Information* [[paper](https://arxiv.org/abs/2409.01440)]

[⬆ Back to top](#paper-list)

#### Method

##### 2026

- [2026] **Embedding Stabilizer Codes and Leakage Correction in Multilevel Quantum Systems** [[paper](https://arxiv.org/abs/2608.12450)]
- [2026] **Information locality of a quantum locally recoverable code** [[paper](https://arxiv.org/abs/2608.04403)]
- [2026] **Real-time decoding of quantum error correction codes using high-performance computing** [[paper](https://arxiv.org/abs/2608.03948)]
- [2026] **X-Z Round Scheduling for the Surface Code with Defects under Biased Noise** [[paper](https://arxiv.org/abs/2608.05518)]
- [2026] **Quantum error correction at ultra-low overhead** [[paper](https://arxiv.org/abs/2608.02773)]
- [2026] **Quantum error correction with global control** [[paper](https://arxiv.org/abs/2608.05821)]
- [2026] **Beyond Legal Spacing: A Residual-Aware Characterization of Entangling-Zone Spacing in Neutral-Atom Compilation** [[paper](https://arxiv.org/abs/2608.17331)]
- [2026] **The Magic Scroll: Leveraging biased noise to improve magic state cultivation in register-based architectures** [[paper](https://arxiv.org/abs/2608.09018)]
- [2026] **Provably Efficient Self-Calibrating Quantum Fault Tolerance** [[paper](https://arxiv.org/abs/2608.05686)]
- [2026] **Exponential logical-error reduction in quantum memories via optimal syndrome-measurement timing** [[paper](https://arxiv.org/abs/2608.06242)]
- [2026] **Fast logical operations in quantum LDPC codes using simple resource states** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.16166)]
- [2026] **A harmonized corpus of quantum error correction publications and patents (1995–2025)** *Mendeley Data* [[paper](https://doi.org/10.17632/cxrrmvy56p.1)]
- [2026] **Fault-tolerant quantum computation with static atomic buses** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.02804)]
- [2026] **QAdapt: A Noise-Adaptive Neural Pre-Decoding Framework for Quantum Error Correction** [[paper](https://arxiv.org/abs/2607.28422)]
- [2026] **Towards logical entanglement creation in trivalent planar architectures** [[paper](https://arxiv.org/abs/2607.15044)]
- [2026] **Surface code logical operations on a superconducting quantum processor** [[paper](https://arxiv.org/abs/2607.01473)]
- [2026] **Machine-learned syndrome post-selection for reliable quantum error correction** [[paper](https://arxiv.org/abs/2607.19563)]
- [2026] **Erasure surface code circuit without mid-circuit erasure checks** [[paper](https://arxiv.org/abs/2607.29443)]
- [2026] **Nishimori Threshold Estimation for Bayesian Inference and $\mathbb{Z}_q$ Surface Code Decoding** [[paper](https://arxiv.org/abs/2607.18374)]
- [2026] **Low-Overhead Error-Corrected QCNNs Using Bivariate Bicycle Codes** [[paper](https://arxiv.org/abs/2607.05724)]
- [2026] **Recovery Algorithm for Correlated Errors in Permutation-Invariant Quantum Codes** [[paper](https://arxiv.org/abs/2607.02346)]
- [2026] **Minimal Counterexamples of the MacWilliams Extension Theorem for Stabilizer Codes** [[paper](https://arxiv.org/abs/2607.26214)]
- [2026] **Latency-Constrained Hardware-Aware Quantum Error Correction Co-Design with Adaptive Confidence-Gated Neural Decoding for the Rotated Surface Code** [[paper](https://arxiv.org/abs/2607.05814)]
- [2026] **Entanglement Wedge Reconstruction without Holographic Quantum Error Correction** [[paper](https://arxiv.org/abs/2607.08684)]
- [2026] **MDQEC-QAS: Meta-Decoding for Quantum Error Correction with Hardware-Aware VQC Search and Confidence-Gated Recovery** [[paper](https://arxiv.org/abs/2607.10707)]
- [2026] **Fault-Tolerant Logical Operations and Efficient State Preparation in Modular Quantum Architectures with Noisy Interfaces** [[paper](https://arxiv.org/abs/2607.27204)]
- [2026] **Genuine Multipartite Entanglement between Logical Qubits via Cross-Code Lattice Surgery** [[paper](https://arxiv.org/abs/2607.04227)]
- [2026] **The verifier side of speculative window decoding: a predictability bracket, a machine-checked blast-radius bound, and a decoder-agnostic recover loop** [[paper](https://arxiv.org/abs/2607.13062)]
- [2026] **Biased-Noise Quantum Reed-Solomon Codes and a Tornado Concatenation for Cat Qubits** [[paper](https://arxiv.org/abs/2607.13105)]
- [2026] **Hybrid Clifford Codes via Operator Algebra Quantum Error Correction and Projective Representation Theory** [[paper](https://arxiv.org/abs/2606.02531)]
- [2026] **Chutes and Ladders: Dynamical Automorphisms via the ZX-Calculus** [[paper](https://arxiv.org/abs/2606.02542)]
- [2026] **Demystifying Objectivity with Operator Algebra Quantum Error Correction** [[paper](https://arxiv.org/abs/2606.06588)]
- [2026] **Learning Arbitrary Lindbladians with Quantum Error Correction** [[paper](https://arxiv.org/abs/2606.18188)]
- [2026] **Logical error estimation from syndrome data of surface-code experiments** [[paper](https://arxiv.org/abs/2606.11496)]
- [2026] **Block algebra for morphing circuits** [[paper](https://arxiv.org/abs/2606.12724)]
- [2026] **Subsystem Quantum Error Correction for Noisy Quantum Metrology** [[paper](https://arxiv.org/abs/2606.19628)]
- [2026] **Random Local Stabilizer Codes in Three Dimensions without String or Self-Similar Fractal Logical Operators** [[paper](https://arxiv.org/abs/2606.19873)]
- [2026] **Quantum Logic Codes: Complete Transversal Logical Clifford Instruction Sets for High-Rate Stabilizer Quantum Error Correcting Codes** [[paper](https://arxiv.org/abs/2606.13521)]
- [2026] **Approximate quantum error correction theory of non-isometric codes** [[paper](https://arxiv.org/abs/2606.13559)]
- [2026] **Quantum Global Variational Learning for Quantum Error Correction** [[paper](https://arxiv.org/abs/2606.08592)]
- [2026] **When to Skip Syndrome Extraction in Surface-GKP Codes** [[paper](https://arxiv.org/abs/2606.24469)]
- [2026] **Toric code made subsystem: a framework for topological subsystem codes using anticommuting quantum spin liquids** [[paper](https://arxiv.org/abs/2606.26226)]
- [2026] **Efficient Magic State Factory Via Transversal Non-Clifford Gate** [[paper](https://arxiv.org/abs/2606.16199)]
- [2026] **An Analysis of Speculative Window Decoders for Quantum Error Correction** [[paper](https://arxiv.org/abs/2606.24048)]
- [2026] **Optimizing bias-tailored quantum error correction beyond code-capacity noise** [[paper](https://arxiv.org/abs/2606.17709)]
- [2026] **Majorana-Pauli stabilizer codes and duality webs of fermionic topological phases** [[paper](https://arxiv.org/abs/2606.25048)]
- [2026] **Breakeven demonstration of quantum low-density parity-check codes** [[paper](https://arxiv.org/abs/2606.06455)]
- [2026] **All about quantum error correction: distillation, mitigation, self-correction and beyond** [[paper](https://arxiv.org/abs/2606.14034)]
- [2026] **Bunny Codes: Broadening Superconducting Quantum Error Correction Capability through Advanced Control Engineering** [[paper](https://arxiv.org/abs/2606.22853)]
- [2026] **Efficient Magic State Cultivation for $\sqrt{T}$ Gates** [[paper](https://arxiv.org/abs/2606.10430)]
- [2026] **Practical gates by Majorana fermion motion** [[paper](https://arxiv.org/abs/2606.03916)]
- [2026] **Projected logical ensembles in surface codes via the random-matrix theory of quantum dots** [[paper](https://arxiv.org/abs/2606.17140)]
- [2026] **Quantum non-demolition measurements as a practical primitive for fault-tolerant computation against biased noise** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.24262)]
- [2026] **Non-Clifford Crosstalk Noise in Surface Codes Using Hybrid Stabilizer-Tensor Network Methods** [[paper](https://arxiv.org/abs/2605.29514)]
- [2026] **Clifford-deformed zero-rate LDPC codes with 50% biased noise thresholds** [[paper](https://arxiv.org/abs/2605.15348)]
- [2026] **Design and Analysis of Quantum Dual-Containing CSS LDPC Codes based on Quasi-Dyadic Matrices** [[paper](https://arxiv.org/abs/2605.03631)]
- [2026] **Homomorphic Quantum Error Correction** [[paper](https://arxiv.org/abs/2605.25692)]
- [2026] **A Scalable FPGA Architecture for Real-Time Decoding of Quantum LDPC Codes Using GARI** [[paper](https://arxiv.org/abs/2605.01035)]
- [2026] **Real-time Surface-Code Error Correction Using an FPGA-based Neural-Network Decoder** [[paper](https://arxiv.org/abs/2605.04892)]
- [2026] **Towards Scalable Quaternary Message-Passing Decoding for Quantum Error Correction** [[paper](https://arxiv.org/abs/2605.24177)]
- [2026] **Nonlocal Topological Maxwell Demon Teleporting Ergotropy via Surface-Code Quantum Error Correction** [[paper](https://arxiv.org/abs/2605.14924)]
- [2026] **Construction of EAQECCs with imperfect ebits** [[paper](https://arxiv.org/abs/2605.23119)]
- [2026] **Trapped-Ion Multiqubit Gates are Compatible with Scalable Quantum Error Correction** [[paper](https://arxiv.org/abs/2605.28536)]
- [2026] **Real-Time Quantum Error Correction System Stack: Architecture, Algorithms, and Engineering Practice** [[paper](https://arxiv.org/abs/2605.30765)]
- [2026] **Lottery BP: Unlocking Quantum Error Decoding at Scale** [[paper](https://arxiv.org/abs/2605.00038)]
- [2026] **Intrinsic locality dimension of quantum codes** [[paper](https://arxiv.org/abs/2605.31441)]
- [2026] **Rethink the Role of Neural Decoders in Quantum Error Correction** [[paper](https://arxiv.org/abs/2605.12046)]
- [2026] **Spatial overhead reduction for 2D hypergraph product codes** [[paper](https://arxiv.org/abs/2605.11318)]
- [2026] **Topological subsystem bivariate bicycle codes with four-qubit check operators** [[paper](https://arxiv.org/abs/2605.04151)]
- [2026] **Energy-error tradeoff in encoding quantum error correction** [[paper](https://arxiv.org/abs/2605.04329)]
- [2026] **Learning Logical Operations for Arbitrary Quantum Error Correction Codes** [[paper](https://arxiv.org/abs/2605.28162)]
- [2026] **Complementing Quantum Error Correction in Quantum Metrology via Swap Test** [[paper](https://arxiv.org/abs/2605.23792)]
- [2026] **Lower overhead fault-tolerant building blocks for noisy quantum computers** [[paper](https://arxiv.org/abs/2605.12385)]
- [2026] **Hybrid Quantum Error Correction Architecture: 98-Qubit Block with Iceberg Protocol, Distributed LDPC, and Surface Code (Independent Preprint)** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19453462)]
- [2026] **The 2026 Quantum Audit: What Changed, What Didn't, and What It Costs** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19519508)]
- [2026] **Fault-Tolerant Quantum Computing with Trapped Ions: The Walking Cat Architecture** [[paper](https://arxiv.org/abs/2604.19481)]
- [2026] **Adaptive Deformation of Color Code in Square Lattices with Defects** [[paper](https://arxiv.org/abs/2604.05874)]
- [2026] **Quantum Decoherence of the Surface Code: A Generalized Caldeira-Leggett Approach** [[paper](https://arxiv.org/abs/2604.18968)]
- [2026] **Learning to Concatenate Quantum Codes** [[paper](https://arxiv.org/abs/2604.14931)]
- [2026] **Quasi-Orthogonal Stabilizer Design for Efficient Quantum Error Suppression** [[paper](https://arxiv.org/abs/2604.12684)]
- [2026] **O3LS: Optimizing Lattice Surgery via Automatic Layout Searching and Loose Scheduling** [[paper](https://arxiv.org/abs/2604.15099)]
- [2026] **Continuous Noise Model for Quantum Circuits** [[paper](https://arxiv.org/abs/2604.26008)]
- [2026] **Autonomous Quantum Error Correction of Spin-Oscillator Hybrid Qubits** [[paper](https://arxiv.org/abs/2604.11145)]
- [2026] **Belief Propagation Convergence Prediction for Bivariate Bicycle Quantum Error Correction Codes** [[paper](https://arxiv.org/abs/2604.07995)]
- [2026] **Fast, High-Fidelity Erasure Detection of Dual-Rail Qubits with Symmetrically Coupled Readout** [[paper](https://arxiv.org/abs/2604.16292)]
- [2026] **Optimising Quantum Error Correction Using Morphing Circuits** [[paper](https://arxiv.org/abs/2604.09797)]
- [2026] **A graph-aware bounded distance decoder for all stabilizer codes** [[paper](https://arxiv.org/abs/2604.25424)]
- [2026] **QGPU: Parallel logic in quantum LDPC codes** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.05398)]
- [2026] **ReloQate: Transient Drift Detection and In-Situ Recalibration in Surface Code Quantum Error Correction** [[paper](https://arxiv.org/abs/2603.00837)]
- [2026] **Mirror codes: High-threshold quantum LDPC codes beyond the CSS regime** [[paper](https://arxiv.org/abs/2603.05496)]
- [2026] **Parsimonious Quantum Low-Density Parity-Check Code Surgery** [[paper](https://arxiv.org/abs/2603.05082)]
- [2026] **Minimum Weight Decoding in the Colour Code is NP-hard** [[paper](https://arxiv.org/abs/2603.04234)]
- [2026] **Achieving Thresholds via Standalone Belief Propagation on Surface Codes** [[paper](https://arxiv.org/abs/2603.05381)]
- [2026] **State-dependent geometries from magic-enriched quantum codes** [[paper](https://arxiv.org/abs/2603.13475)]
- [2026] **Preserving MWPM-Decodability in Fault-Equivalent Rewrites** [[paper](https://arxiv.org/abs/2603.19522)]
- [2026] **Correlated Atom Loss as a Resource for Quantum Error Correction** [[paper](https://arxiv.org/abs/2603.24237)]
- [2026] **A Scalable Open-Source QEC System with Sub-Microsecond Decoding-Feedback Latency** [[paper](https://arxiv.org/abs/2603.16203)]
- [2026] **Spatiotemporal Pauli processes: Quantum combs for modelling correlated noise in quantum error correction** [[paper](https://arxiv.org/abs/2603.05474)]
- [2026] **On-Demand Correlated Errors in Superconducting Qubits from a Particle Accelerator** [[paper](https://arxiv.org/abs/2603.13124)]
- [2026] **Low Latency GNN Accelerator for Quantum Error Correction** [[paper](https://arxiv.org/abs/2603.22149)]
- [2026] **Velocity-Enabled Quantum Computing with Neutral Atoms** [[paper](https://arxiv.org/abs/2603.15561)]
- [2026] **Obstacles to Continuous Quantum Error Correction via Parity Measurements** [[paper](https://arxiv.org/abs/2603.02106)]
- [2026] **Qudit stabiliser codes for $\mathbb{Z}_N$ lattice gauge theories with matter** [[paper](https://arxiv.org/abs/2602.20661)]
- [2026] **CQM: Cyclic Qubit Mappings** [[paper](https://arxiv.org/abs/2602.20123)]
- [2026] **Quantum Error Correction and Dynamical Decoupling: Better Together or Apart?** [[paper](https://arxiv.org/abs/2602.19042)]

##### 2012

- [2012] **Surface Codes: Towards Practical Large-Scale Quantum Computation** *Physical Review A 86, 032324 (2012)* [[paper](https://arxiv.org/abs/1208.0928)]

[⬆ Back to top](#paper-list)

#### Application

##### 2026

- [2026] **Hardware-in-the-Loop Syndrome-to-Decoder Validation for Repetition, Surface, CSS-LDPC, and Digitized-GKP Codes** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.19447)]
- [2026] **Accelerating Computation in Quantum LDPC Code** [[paper](https://doi.org/10.1145/3779212.3790122)]

[⬆ Back to top](#paper-list)

#### Development

##### 2026

- [2026] **QECTOR DECODER v0.6.6: A Source-Available Rust-Backed Python Platform for High-Performance Quantum Error Correction Decoding** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21320543)]

[⬆ Back to top](#paper-list)

#### Systems & Technology

##### 2026

- [2026] **Hybrid Quantum Error Correction Architecture: 98-Qubit Block + Iceberg + LDPC + Surface Code** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19437498)]

[⬆ Back to top](#paper-list)

### Quantum Hardware & Architecture

#### Theory

##### 2026

- [2026] **The Branch-Amplitude Discriminant: A Null Test of Measurement Dynamics with Imbalanced Logical GHZ States** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21823149)]
- [2026] **Quantum Computing: A Contemporary Review of Qubit Platforms, Algorithms, Error Correction, and Emerging Applications** *International Journal of Computer Applications* [[paper](https://doi.org/10.5120/ijca2b2d25a3c082)]
- [2026] **A study of qubit modalities in contemporary quantum computing** *Discover Quantum Science* [[paper](https://doi.org/10.1007/s44464-026-00033-9)]
- [2026] **<b>Cooling Lithium and Cesium Single Atoms in Optical Tweezers</b>** *Figshare* [[paper](https://figshare.com/articles/thesis/_b_Cooling_Lithium_and_Cesium_Single_Atoms_in_Optical_Tweezers_b_/32867018)]
- [2026] **Plaquette: A hardware-aware design platform for fault-tolerant quantum computers** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.08767)]
- [2026] **NISQ in practice: navigating noise, scale, and hardware constraints of near-term devices in quantum machine learning workflows** *New Journal of Physics* [[paper](https://doi.org/10.1088/1367-2630/ae8053)]
- [2026] **Cooling Lithium and Cesium Single Atoms in Optical Tweezers** *Purdue* [[paper](https://doi.org/10.25394/pgs.32867018)]
- [2026] **Current Technological Advances in Quantum Computing** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/979-8-2600-0156-1.ch011)]
- [2026] **Advances in Logical Qubits and Quantum Error Correction: Progress Toward Fault-Tolerant Quantum Computing** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20143179)]
- [2026] **From Primitives to the Limits of Quantum Computation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20145689)]
- [2026] **Discriminating Thomas–Wigner from Pancharatnam–Berry Rotations in Sequential Weak Qubit Measurements: A Variable-Visibility Protocol** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19722697)]
- [2026] **Quantum Computing: Next-Generation Computational Paradigm** *International Journal for Research in Applied Science and Engineering Technology* [[paper](https://doi.org/10.22214/ijraset.2026.80467)]
- [2026] **Quantum Computed Moments: A New Paradigm for Simulating Molecular Properties in Drug Discovery** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19659140)]
- [2026] **PSI-Model & Protocol-P7: Cross-Platform Validation of the Informational Shielding Effect (ISE) in NISQ Circuits.** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20279168)]
- [2026] **Engineering Quantum Mechanics for Molecular Systems: From Theory to Drug Discovery Applications** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19658974)]
- [2026] **Modular Assembly of High-Performance Logical Blocks from the Lorentzian Causal Diamond: Pareto-Optimal Finite-Block Codes, Asymmetric Distance Families, and an E₈ Structural Obstruction** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19484042)]
- [2026] **Securing Elliptic Curve Cryptocurrencies against Quantum Vulnerabilities: Resource Estimates and Mitigations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.28846)]
- [2026] **The Landauer Equality for Quantum Error Correction** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18921524)]
- [2026] **2026.03.16_Entropy-Induced_Collapse_III_False-Collapse_Statistics_in_Quantum_Error_Correction_Regimes** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19040060)]
- [2026] **2026.03.19_Entropy-Induced_Collapse_(EIC)_Operational_Windows_in_Monitored_and_Error-Managed_Quantum_Systems** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19103384)]
- [2026] **I know what's in the box and I don't have to open it.** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18962960)]
- [2026] **Quantum in the Cloud: Hype vs. Hardware** *Open MIND* [[paper](https://myweirdprompts.com/episode/quantum-cloud-service-reality-2026)]
- [2026] **Quantum Computing and Industry Transformation** *Auerbach Publications eBooks* [[paper](https://doi.org/10.1201/9781003587835-12)]
- [2026] **How to Build a Quantum Supercomputer: Enabling Utility-Scale Quantum Computing with HPC-QC Integration** *Underline Science Inc.* [[paper](https://doi.org/10.48448/1n8w-sw25)]

##### 2024

- [2024] **Promise of Graph Sparsification and Decomposition for Noise Reduction in QAOA: Analysis for Trapped-Ion Compilations** *Quantum* [[paper](https://arxiv.org/abs/2406.14330)]

[⬆ Back to top](#paper-list)

#### Method

##### 2026

- [2026] **Coherent errors in a superconducting six-qubit network with beyond-nearest-neighbor connectivity** *Physical Review Research* [[paper](https://doi.org/10.1103/6jdh-pm39)]
- [2026] **Origami: An Open Instruction Set Architecture for Quantum Computing** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21428854)]
- [2026] **InterQ: Communication-Aware Scheduling Across Modular QPUs with Classical and Quantum Links** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.17769)]
- [2026] **Energy efficiency of quantum computers** *HAL (Le Centre pour la Communication Scientifique Directe)* [[paper](https://arxiv.org/abs/2605.15090)]
- [2026] **Towards automatic evaluation of circuit fault-tolerance** *Aaltodoc (Aalto University)* [[paper](https://aaltodoc.aalto.fi/handle/123456789/144709)]
- [2026] **QuMod: Parallel Quantum Job Scheduling on Modular QPUs Using Circuit Cutting** [[paper](https://doi.org/10.1109/qcnc69040.2026.00020)]

[⬆ Back to top](#paper-list)

#### Application

##### 2026

- [2026] **XCOM: Full Mesh Network Synchronization and Low-Latency Communication for QICK (Quantum Instrumentation Control Kit)** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.18977)]

[⬆ Back to top](#paper-list)

#### Development

##### 2026

- [2026] **Quantum Technologies: System-Level Performance and Engineering Priorities** *JPL Data* [[paper](https://doi.org/10.48577/jpl.kfhmwq)]

[⬆ Back to top](#paper-list)

#### Systems & Technology

##### 2026

- [2026] **Hardware-Aware Compilation and Execution of Bivariate Bicycle Codes on Neutral-Atom Systems** [[paper](https://arxiv.org/abs/2608.17023)]
- [2026] **Validation and calibration of quantum hardware through the many-body quantum Mpemba effect** [[paper](https://arxiv.org/abs/2608.01788)]
- [2026] **Reconstructing non-Abelian braiding and fusion without anyon transport** [[paper](https://arxiv.org/abs/2608.04103)]
- [2026] **Hundred-hertz quantum circuit iteration rate in a reusable neutral-atom array** [[paper](https://arxiv.org/abs/2608.16815)]
- [2026] **An ionic clock qubit inside a circular Rydberg atom** [[paper](https://arxiv.org/abs/2608.06988)]
- [2026] **Fast Quantum Interconnects via Neutral Atom Ensembles** [[paper](https://arxiv.org/abs/2608.05147)]
- [2026] **Where Atom Loss Lands Matters: Decoder-Aware Risk Deposition in Neutral-Atom QEC** [[paper](https://arxiv.org/abs/2608.17913)]
- [2026] **PaQit: Energy-Runtime-Fidelity Co-Optimization for Neutral Atom Quantum Computers** [[paper](https://arxiv.org/abs/2608.02815)]
- [2026] **Mid-circuit ground-state cooling and ancilla readout in the $\textit{omg}$ architecture** [[paper](https://arxiv.org/abs/2608.13181)]
- [2026] **Ion trap on borosilicate substrate with integrated femtosecond-laser-written waveguide** [[paper](https://arxiv.org/abs/2608.13207)]
- [2026] **Efficient Assembly of a Defect-Free Quantum Register of 1024 Neutral-Atom Qubits** [[paper](https://arxiv.org/abs/2608.12021)]
- [2026] **Collective Quantum Logic Spectroscopy** [[paper](https://arxiv.org/abs/2608.20471)]
- [2026] **A Quantum Interface Between Neutral-Atoms and Trapped-Ions Quantum Registers** [[paper](https://arxiv.org/abs/2607.20998)]
- [2026] **Deterministic atom-shuttle interconnects via ultrafast atom-ion entangling gate** [[paper](https://arxiv.org/abs/2607.15597)]
- [2026] **Qubit Loss Inference with Stabilizer Codes without Leakage Detection Units** [[paper](https://arxiv.org/abs/2607.29603)]
- [2026] **Experimental demonstration of entanglement sudden death induced by natural dissipation** [[paper](https://arxiv.org/abs/2607.08078)]
- [2026] **Spin Chain Quantum Communication on a Trapped-Ion Processor** [[paper](https://arxiv.org/abs/2607.12999)]
- [2026] **Quantum LDPC codes with design rate 1/5 and good performance below 1000 physical qubits** [[paper](https://arxiv.org/abs/2607.27644)]
- [2026] **Simulating the Dicke Model on Qubit-Based and hybrid Qubit-Boson-Based Quantum Computers** [[paper](https://arxiv.org/abs/2607.18546)]
- [2026] **A cryogenic neutral-atom platform with full optical access and 2-hour trap lifetime** [[paper](https://arxiv.org/abs/2607.12988)]
- [2026] **Expressibility and trainability of a two-dimensional pairwise quantum-circuit ansatz** [[paper](https://arxiv.org/abs/2607.12996)]
- [2026] **Improving Dynamical Decoupling for Trapped-Ion QCCD Quantum Computers** [[paper](https://arxiv.org/abs/2607.14441)]
- [2026] **Möbius-Guided Diagonal-Gate Compilation with Native Multiqubit Controlled-Phase Gates on Neutral-Atom Processors** [[paper](https://arxiv.org/abs/2607.08212)]
- [2026] **Low-latency FPGA-based electronic control system for fast preparation of defect-free atom arrays** [[paper](https://arxiv.org/abs/2607.08687)]
- [2026] **Enabling Neutral Atom Integration: Redesigning Device Models for Universal Quantum Ecosystems** [[paper](https://arxiv.org/abs/2607.20616)]
- [2026] **A Quantum-HPC Hybrid Workflow for Reaction-Center Electronic Dynamics: Application to a Cytochrome P450-Inspired Iron-Complex Model** [[paper](https://arxiv.org/abs/2607.05786)]
- [2026] **Resolving Structure in Prethermal Floquet Dynamics with Precision Quantum Computation** [[paper](https://arxiv.org/abs/2607.24937)]
- [2026] **Robust Ion-Photon Entanglement via Polarization-to-Time-Bin Conversion** [[paper](https://arxiv.org/abs/2607.07805)]
- [2026] **Electron shuttling as a probe for charge defects** [[paper](https://arxiv.org/abs/2607.21718)]
- [2026] **Real-Time Detection of Charge Jumps in Superconducting Qubits with a Convolutional Neural Network** [[paper](https://arxiv.org/abs/2607.14293)]
- [2026] **Structure-Preserving Quantum Simulation of Wave Equations on a Trapped-Ion Processor** [[paper](https://arxiv.org/abs/2607.28499)]
- [2026] **An End-to-End Multi-Stage Kill-Chain Attack on Quantum Neural Networks: Demonstration on Trapped-Ion Hardware** [[paper](https://arxiv.org/abs/2607.03337)]
- [2026] **Substrate-metal interface engineering enhances TaN/Ta thin film superconducting resonator performance** [[paper](https://arxiv.org/abs/2607.22294)]
- [2026] **The SQU, TriQ, and SevenQ: Standard Hardware for the Origami ISA** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20581486)]
- [2026] **Simulating Condensed Matter Physics on Quantum Hardware** [[paper](https://arxiv.org/abs/2606.02721)]
- [2026] **Quantum Cinema: An Interactive Cinematic Exploration of Quantum Computing Hardware via Generative World Models** [[paper](https://arxiv.org/abs/2606.17102)]
- [2026] **Simulation of Two-qubit Gate Variability and Fidelity of Spin Qubits Built on Nanosheet Technology** [[paper](https://arxiv.org/abs/2606.32030)]
- [2026] **Analog Quantum Asynchronous Event-Based Graph Neural Network** [[paper](https://arxiv.org/abs/2606.11000)]
- [2026] **Suppressing Intrinsic Spin-Phonon Errors in Trapped-Ion Quantum Simulation** [[paper](https://arxiv.org/abs/2606.15518)]
- [2026] **QuBE/Qubex: an integrated hardware-software system for superconducting qubit experiments with broadband control** [[paper](https://arxiv.org/abs/2606.13010)]
- [2026] **High-performance gates on trapped ion qubits using counterpropagating pulse-shaped laser beams** [[paper](https://arxiv.org/abs/2606.15672)]
- [2026] **Tensor-Network-Based Distributed Quantum Dynamics on Independent Quantum Computers** [[paper](https://arxiv.org/abs/2606.11579)]
- [2026] **Suppression of Quasiparticle Poisoning to $10^{-11}$ Levels in Superconducting Qubits via Infrared Shielding** [[paper](https://arxiv.org/abs/2606.07339)]
- [2026] **Emergency hub placement with a neutral-atom quantum computer** [[paper](https://arxiv.org/abs/2606.19589)]
- [2026] **Microscopic universal theory of symmetry-enriched topological quantum spin liquids** [[paper](https://arxiv.org/abs/2606.08558)]
- [2026] **Scalable On-Hardware Training of Quantum Neural Networks and Application to Clinical Data Imputation** [[paper](https://arxiv.org/abs/2606.03517)]
- [2026] **Rapid Cavity-Based Mid-Circuit Measurement and Feedforward in a Neutral Atom Array** [[paper](https://arxiv.org/abs/2606.24869)]
- [2026] **Distributed Quantum Error Correction with Bivariate Bicycle Codes in a Modular Architecture** [[paper](https://arxiv.org/abs/2605.04663)]
- [2026] **Measuring Control-Plane Openness in Near-Term Quantum Computing: A Rubric, Its Validation, and an Application to Thirteen Vendor Stacks** [[paper](https://arxiv.org/abs/2605.15233)]
- [2026] **Measuring Accuracy and Energy-to-Solution of Quantum Fine-Tuning of Foundational AI Models** [[paper](https://arxiv.org/abs/2605.02798)]
- [2026] **Neural optimization for quantum architectures: graph embedding problems with Distance Encoder Networks** [[paper](https://arxiv.org/abs/2605.03565)]
- [2026] **QuCtrl-BELL: A Compiler-Driven Sub-Microsecond Feedback Control Stack for Scalable Trapped-Ion Quantum Experiments** [[paper](https://arxiv.org/abs/2605.22433)]
- [2026] **Surface-Code Thresholds and Qubit Footprints in Shuttling-Based Spin-Qubit Railways** [[paper](https://arxiv.org/abs/2605.05881)]
- [2026] **Understanding oxide-thickness-dependent variability in dense Si-MOS quantum dot arrays** [[paper](https://arxiv.org/abs/2605.12143)]
- [2026] **Scale-Invariant Open Quantum Systems** [[paper](https://arxiv.org/abs/2605.22919)]
- [2026] **Fidelity bounds for spin-dependent kicks with pulsed lasers** [[paper](https://arxiv.org/abs/2605.31409)]
- [2026] **Harnessing DEN models for quantum computing tasks on neutral atom QPUs** [[paper](https://arxiv.org/abs/2605.03503)]
- [2026] **Non-equilibrium exciton dynamics in tailored molecular potentials of Rydberg ion crystals** [[paper](https://arxiv.org/abs/2605.21250)]
- [2026] **Cryogenic Time-Division-Multiplexed Voltage Control for Scalable Trapped-Ion Quantum Processors** [[paper](https://arxiv.org/abs/2605.17824)]
- [2026] **QOuLiPo: What a quantum computer sees when it reads a book** [[paper](https://arxiv.org/abs/2605.14188)]
- [2026] **Orbital-Angular-Momentum Entangled Photon Emission from Circular Currents in Semiconductor-Superconductor Structures** [[paper](https://arxiv.org/abs/2605.20329)]
- [2026] **Protein folding on a 64 qubit trapped-ion hardware via counterdiabatic quantum optimization** [[paper](https://arxiv.org/abs/2604.26861)]
- [2026] **QCalEval: Benchmarking Vision-Language Models for Quantum Calibration Plot Understanding** [[paper](https://arxiv.org/abs/2604.25884)]
- [2026] **What quantum computer to buy?** [[paper](https://arxiv.org/abs/2604.04761)]
- [2026] **CVaR-Assisted Custom Penalty Function for Constrained Optimization** [[paper](https://arxiv.org/abs/2604.20088)]
- [2026] **HyPulse: A Pulse Synthesis Framework for Hybrid Qubit-Oscillator Gates on Trapped-Ion Platform** [[paper](https://arxiv.org/abs/2604.26804)]
- [2026] **Classical simulation of free-fermionic dynamics and quantum chemistry with magic input** [[paper](https://arxiv.org/abs/2604.26813)]
- [2026] **Quantum Lattice Boltzmann Solutions for Transport under 3D Spatially Varying Advection on Trapped Ion Hardware** [[paper](https://arxiv.org/abs/2604.28121)]
- [2026] **Scalable surface ion trap design for magnetic quantum sensing and gradiometry** [[paper](https://arxiv.org/abs/2604.21342)]
- [2026] **Hybrid Quantum-Classical Optimization Workflows for the Shipment Selection Problem** [[paper](https://arxiv.org/abs/2604.11758)]
- [2026] **Spin Qubit Leapfrogging: Dynamics of shuttling electrons on top of another** [[paper](https://arxiv.org/abs/2604.13760)]
- [2026] **Fundamentals and Applications of Hybrid Electro- and Opto-mechanical system coupled to Superconducting Qubit: A Short Review** [[paper](https://arxiv.org/abs/2604.18186)]
- [2026] **Phase-Stable Hologram Updates for Large-Scale Neutral-Atom Array Reconfiguration** [[paper](https://arxiv.org/abs/2604.04600)]
- [2026] **Nonlocal Games as Cross-Platform Quantum Benchmarks: Exceeding unconditional classical bounds on trapped-ion processors** [[paper](https://arxiv.org/abs/2603.18323)]
- [2026] **Large Language Model-Assisted Superconducting Qubit Experiments** [[paper](https://arxiv.org/abs/2603.08801)]
- [2026] **Feasibility of satellite-augmented global quantum repeater networks** [[paper](https://arxiv.org/abs/2603.11127)]
- [2026] **Achieving speedup in Dark Matter search experiments with a transmon-based NISQ algorithm** [[paper](https://arxiv.org/abs/2603.03157)]
- [2026] **Quantum Deep Learning: A Comprehensive Review** [[paper](https://arxiv.org/abs/2603.06644)]
- [2026] **Adaptive Parallelism-Aware Qubit Routing for Ion Trap QCCD Architectures** [[paper](https://arxiv.org/abs/2603.19969)]
- [2026] **Entangling ions with engineered light gradients** [[paper](https://arxiv.org/abs/2603.07548)]
- [2026] **Local robust shadows on a trapped ion computer -- a case study** [[paper](https://arxiv.org/abs/2603.28307)]
- [2026] **Probing excited-state quantum phase transitions with trapped cold ions** [[paper](https://arxiv.org/abs/2603.28509)]
- [2026] **Sustaining high-fidelity quantum logic in neutral-atom circuits via mid-circuit operations** [[paper](https://arxiv.org/abs/2603.01612)]
- [2026] **Single-ion phonon laser in the quantum regime** [[paper](https://arxiv.org/abs/2603.01585)]
- [2026] **Ion-atom two-qubit quantum gate based on phonon blockade** [[paper](https://arxiv.org/abs/2602.19222)]
- [2026] **Characterization and cancellation of power-line-induced motional-mode frequency noise in a trapped-ion system** [[paper](https://arxiv.org/abs/2602.19588)]
- [2026] **A frequency-agile microwave-optical interface for superconducting qubits** [[paper](https://arxiv.org/abs/2602.24098)]
- [2026] **Computing with many encoded logical qubits beyond break-even** [[paper](https://arxiv.org/abs/2602.22211)]

[⬆ Back to top](#paper-list)

#### Evaluation & Benchmarks

##### 2019

- [2019] **Quantum Supremacy Using a Programmable Superconducting Processor** *Nature 574, 505-510 (2019)* [[paper](https://arxiv.org/abs/1910.11333)]

[⬆ Back to top](#paper-list)

### Quantum Information Theory

#### Theory

##### 2026

- [2026] **A quantum game of telephone** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.03963)]
- [2026] **Complementary Quantum Correlations Are Universal for Qubits** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.04916)]
- [2026] **Twenty-one characterizations of reversible quantum channels** [[paper](https://arxiv.org/abs/2608.01088)]
- [2026] **A Unified Framework for Sample Complexity of Structured Quantum State Tomography under Noisy Observations** [[paper](https://arxiv.org/abs/2608.05526)]
- [2026] **Entanglement depth and ancilla efficiency in quantum channel estimation** [[paper](https://arxiv.org/abs/2608.11042)]
- [2026] **Improved regret bounds for structured online learning of quantum states** [[paper](https://arxiv.org/abs/2608.05740)]
- [2026] **Spin-coherent quantum designs** [[paper](https://arxiv.org/abs/2608.11310)]
- [2026] **Optimality of Gaussian Entanglement of Formation** [[paper](https://arxiv.org/abs/2608.01909)]
- [2026] **Asymptotic Entanglement Hiding under Stabilizer Restrictions** [[paper](https://arxiv.org/abs/2608.18440)]
- [2026] **Entanglement Mpemba Effect** [[paper](https://arxiv.org/abs/2608.07465)]
- [2026] **Opposite post-processing orders of fermionic horizon channels and their quantum-resource monotonicity** [[paper](https://arxiv.org/abs/2608.08215)]
- [2026] **On-chip generation of multi-qubit graph states with high-dimensional encoded single photons** [[paper](https://arxiv.org/abs/2608.03012)]
- [2026] **Tomographic Limits of the Petz Recovery Map** [[paper](https://arxiv.org/abs/2608.21309)]
- [2026] **Entanglement Generation Beyond Quantum Theory: From Product States to Popescu-Rohrlich Boxes** [[paper](https://arxiv.org/abs/2608.02403)]
- [2026] **Adding Quantum Mechanics to Darwin's Theory of Evolution... The Secret of Bacterial Adaptive Mutation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21328921)]
- [2026] **Entanglement Detection for Two-Qubit and Three-Qubit Pure States via Unitary Transformations and Ancilla State Measurements** [[paper](https://arxiv.org/abs/2607.15201)]
- [2026] **SSP-QST: Spectral Subspace Purification for Photonic Quantum State Tomography** [[paper](https://arxiv.org/abs/2607.21836)]
- [2026] **Nonlocal Magnonic Cat States in Hybrid Magnon-Qubit Architectures** [[paper](https://arxiv.org/abs/2607.25643)]
- [2026] **Relativistic quantum teleportation protected by the anti-Unruh effect** [[paper](https://arxiv.org/abs/2607.17216)]
- [2026] **Superadditivity for Entanglement-Assisted Communication** [[paper](https://arxiv.org/abs/2607.15151)]
- [2026] **Logarithmic negativity typically equals exact entanglement cost** [[paper](https://arxiv.org/abs/2607.01320)]
- [2026] **Rank-Adaptive Matrix-Free Atomic Quantum State Tomography** [[paper](https://arxiv.org/abs/2607.19577)]
- [2026] **Flow-based Phase-space Tomography of Continuous-variable Quantum States** [[paper](https://arxiv.org/abs/2607.21584)]
- [2026] **Latency-Constrained Encoded Quantum Teleportation with Punctured Codes** [[paper](https://arxiv.org/abs/2607.19770)]
- [2026] **A solution to 2-copy distillability of Werner states** [[paper](https://arxiv.org/abs/2607.21367)]
- [2026] **The Ruskai-Audenaert conjecture &amp; equipartitions of positive operators** [[paper](https://arxiv.org/abs/2607.23066)]
- [2026] **Chiral Entangled-State Generation through Dissipative Quantum Dynamics** [[paper](https://arxiv.org/abs/2607.17302)]
- [2026] **Enhancing Entanglement Purification with Shared Randomness** [[paper](https://arxiv.org/abs/2607.21555)]
- [2026] **Single-acquisition tomography of photonic qubits with structured media** [[paper](https://arxiv.org/abs/2607.03052)]
- [2026] **Demonstration of tripartite cat states in two distinct classes of entanglement** [[paper](https://arxiv.org/abs/2607.12317)]
- [2026] **Deleterious effect of photon-phonon coupling on microcavities in their application as quantum sources** [[paper](https://arxiv.org/abs/2607.21743)]
- [2026] **Entanglement and Wavefunction Collapse as Boundary-Persistence Phenomena: A Falsification Test Programme for Open Quantum Systems** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20560850)]
- [2026] **Hyperon-pair spin tomography beyond scalar spin correlations** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.24811)]
- [2026] **$Λ\bar Λ$ spin correlations in high-energy collisions from quantum channels: an open quantum system view of hadronization** [[paper](https://arxiv.org/abs/2606.30737)]
- [2026] **Demonstration of unpartible entanglement** [[paper](https://arxiv.org/abs/2606.30468)]
- [2026] **Informational completeness of qubit measurements and IC preservability of qubit channels: Characterization and Quantification** [[paper](https://arxiv.org/abs/2606.03964)]
- [2026] **Many-body chirality of topological stabilizer states** [[paper](https://arxiv.org/abs/2606.20472)]
- [2026] **Characterizing quantum channels from local-unitary invariants** [[paper](https://arxiv.org/abs/2606.03722)]
- [2026] **Noise cancellation by superposition of channels and superactivation of quantum capacity: Experimental realization by NMR** [[paper](https://arxiv.org/abs/2606.10744)]
- [2026] **Information-Geometric Bound on the Robustness of Entanglement Generation** [[paper](https://arxiv.org/abs/2606.05696)]
- [2026] **Quantum Illumination with Symmetry-Constrained Random Unitaries** [[paper](https://arxiv.org/abs/2606.15586)]
- [2026] **Observation of residual entanglement in chip-based entanglement purification** [[paper](https://arxiv.org/abs/2606.03343)]
- [2026] **Chirality routing non-polaritonic vacuum correlations in Landau polaritons** [[paper](https://arxiv.org/abs/2606.00165)]
- [2026] **Efficient entanglement of three remote single-atom quantum-network nodes** [[paper](https://arxiv.org/abs/2606.32006)]
- [2026] **Quantum learning with a single-atom sensor** [[paper](https://arxiv.org/abs/2606.15071)]
- [2026] **Entanglement Generation through Coherent and Non-Coherent Control** [[paper](https://arxiv.org/abs/2606.09599)]
- [2026] **Optimizing Entanglement Distillation Policies via Markov Decision Process Formulation** [[paper](https://arxiv.org/abs/2606.14908)]
- [2026] **Entanglement-Coupling Precursors of Decoherence in Quantum Circuits: A Heuristic Information-Theoretic Precursor Framework (KA-Quantum)** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202605.0709.v1)]
- [2026] **Experimental observation of entropic-singularity-induced nonadditive quantum communication in a qutrit platypus channel** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.17418)]
- [2026] **Integrated time-bin entangled quantum light source on a 4H-SiC microring chip** [[paper](https://arxiv.org/abs/2605.18124)]
- [2026] **Entanglement in quantum channel discrimination: sometimes less is more** [[paper](https://arxiv.org/abs/2605.31519)]
- [2026] **Statistical and Algorithmic Foundations of Probing Quantum Systems with Compressive Measurements: A Review** [[paper](https://arxiv.org/abs/2605.27191)]
- [2026] **Sequential quantum nonlocality sharing under local noisy quantum channels** [[paper](https://arxiv.org/abs/2605.26798)]
- [2026] **Asymptotic Limits of Entanglement Transmission** [[paper](https://arxiv.org/abs/2605.23443)]
- [2026] **Quantum Proper Scoring Rules: Minimax Estimation and Resource-Theoretic Advantages** [[paper](https://arxiv.org/abs/2605.05268)]
- [2026] **New quantum information perspectives in the axion--photon and neutrino systems** [[paper](https://arxiv.org/abs/2605.30419)]
- [2026] **Imaginarity Resource Theory of Gaussian Quantum Channels** [[paper](https://arxiv.org/abs/2605.14299)]
- [2026] **Quantum and classical processing with photonic quantum machine learning** [[paper](https://arxiv.org/abs/2605.10471)]
- [2026] **Loss-induced quantum nonreciprocity and entanglement in superconducting qubits** [[paper](https://arxiv.org/abs/2605.11457)]
- [2026] **Analytical Investigation of Two-Spin Entanglement Generated by Different Types of Bosonic Environments** [[paper](https://arxiv.org/abs/2605.28898)]
- [2026] **Entangling power and fidelity diagnostic for bipartite quantum channels** [[paper](https://arxiv.org/abs/2605.26867)]
- [2026] **Nonreciprocal magnon-magnon entanglement in a spinning cavity-magnon system** [[paper](https://arxiv.org/abs/2605.14394)]
- [2026] **Observable measures of multipartite entanglement** [[paper](https://arxiv.org/abs/2605.01375)]
- [2026] **Non-Maximally Entangled States for Quantum Key Distribution in Underwater Channels: BBM92 Protocol via Kraus Operators** [[paper](https://arxiv.org/abs/2605.23547)]
- [2026] **Non-monotonic evolution of multipartite entanglement under the Unruh effect** [[paper](https://arxiv.org/abs/2605.24424)]
- [2026] **Online Riemannian Gradient Descent for Quantum State Tomography with Matrix Product Operators** [[paper](https://arxiv.org/abs/2605.04533)]
- [2026] **Quantum teleportation with coherent error in Bell-state measurement** [[paper](https://arxiv.org/abs/2605.12130)]
- [2026] **Time-of-flight force sensing below the quantum zero-point fluctuation** [[paper](https://arxiv.org/abs/2605.09854)]
- [2026] **Entanglement increase from local interactions which lead to non-positive local reduced dynamics** [[paper](https://arxiv.org/abs/2605.08923)]
- [2026] **Experimental Validation of Decoherence Inhibition via Intra-System Informational Coupling in Superconducting Quantum Processors.** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19708346)]
- [2026] **Experimental Validation of Decoherence Inhibition via Intra-System Informational Coupling in Superconducting Quantum Processors** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19708001)]
- [2026] **Entanglement of two optical emitters mediated by a terahertz channel** [[paper](https://arxiv.org/abs/2604.21723)]
- [2026] **Rigorous quantum state tomography for distributed quantum computing** [[paper](https://arxiv.org/abs/2604.09775)]
- [2026] **Physics-Informed Discrete-Event Simulation of Polarization-Encoded Quantum Networks** [[paper](https://arxiv.org/abs/2604.07289)]
- [2026] **The use of the output states generated by the broadcasting of entanglement in quantum teleportation** [[paper](https://arxiv.org/abs/2604.12823)]
- [2026] **Wave--particle transition and quantum Zeno effect in which-way experiments with a superconducting quantum processor** [[paper](https://arxiv.org/abs/2604.19115)]
- [2026] **Enhancing Phase Retrievability of Quantum Channels via Interferometric Coupling** [[paper](https://arxiv.org/abs/2604.24363)]
- [2026] **A Framework for Predicting Entanglement Spectra of Gapless Symmetry-Protected Topological States in One Dimension** [[paper](https://arxiv.org/abs/2604.10128)]
- [2026] **Structured Quantum State Reconstruction via Physically Motivated Operator Selection** [[paper](https://arxiv.org/abs/2604.21272)]
- [2026] **On-demand generation of all four Bell states using a single PPKTP entangled photon source** [[paper](https://arxiv.org/abs/2604.19013)]
- [2026] **Absolute Schmidt number: characterization, detection and resource-theoretic quantification** [[paper](https://arxiv.org/abs/2604.02439)]
- [2026] **Optimal Quantum State Testing Even with Limited Entanglement** [[paper](https://arxiv.org/abs/2604.07460)]
- [2026] **Efficient direct quantum state tomography using fan-out couplings** [[paper](https://arxiv.org/abs/2604.04454)]
- [2026] **Genuine tripartite entanglement in Bhabha scattering with an entangled spectator particle** [[paper](https://arxiv.org/abs/2604.26380)]
- [2026] **Minimizing classical resources in variational measurement-based quantum computation for generative modeling** [[paper](https://arxiv.org/abs/2604.11578)]
- [2026] **Catalytic Enhancement of Coherence in Noisy Quantum Channels and Characterization of Strictly Incoherent Operations** [[paper](https://arxiv.org/abs/2604.24291)]
- [2026] **An Exponential Advantage for Adaptive Tomography of Structured States under Pauli Basis Measurements** [[paper](https://arxiv.org/abs/2604.26043)]
- [2026] **P06 Measurement-Non-Backwrite-Principle. Why Descriptor Intervention Cannot Be Upgraded into Mother-Kernel Modification** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19201665)]
- [2026] **Learning Entanglement Quasiprobability from Noisy and Incomplete Data** [[paper](https://arxiv.org/abs/2603.18414)]
- [2026] **Entanglement cost of bipartite quantum channel discrimination under positive partial transpose operations** [[paper](https://arxiv.org/abs/2603.12130)]
- [2026] **Remote engineering of particle-like topologies to visualise entanglement dynamics** [[paper](https://arxiv.org/abs/2603.10491)]
- [2026] **Simulating a quantum sensor: quantum state tomography of NV-spin systems** [[paper](https://arxiv.org/abs/2603.03049)]
- [2026] **Generalized Inverses of Quantum Channels: a categorical perspective** [[paper](https://arxiv.org/abs/2603.13946)]
- [2026] **Entanglement transference and non-inertial quantum reference frames** [[paper](https://arxiv.org/abs/2603.23601)]
- [2026] **Temporal limitations and digital data processing in continuous variable measurements of non-Gaussian states** [[paper](https://arxiv.org/abs/2603.09698)]
- [2026] **Teleporting an unknown qutrit state via a 2-qudit entangled channel** [[paper](https://arxiv.org/abs/2603.18679)]
- [2026] **Genuinely entangled subspaces and strongly nonlocal unextendible biseparable bases in four-partite systems** [[paper](https://arxiv.org/abs/2603.09040)]
- [2026] **Hybrid Analog Teleportation-Direct Transmission in Noisy Bosonic Channels** [[paper](https://arxiv.org/abs/2603.11941)]
- [2026] **Entanglement Fidelity in Standard Quantum Channels** [[paper](https://arxiv.org/abs/2603.07761)]
- [2026] **Topological robustness of orbital angular momentum entanglement in stochastic channels** [[paper](https://arxiv.org/abs/2603.10618)]
- [2026] **Multipartite entanglement dynamics in quantum walks** [[paper](https://arxiv.org/abs/2603.24679)]
- [2026] **On the power of multipartite entanglement for pseudotelepathy** [[paper](https://arxiv.org/abs/2603.17956)]
- [2026] **Reconfigurable circuit for mode tunable topological quantum structured light** [[paper](https://arxiv.org/abs/2603.17716)]
- [2026] **Entanglement-Assisted Discrimination of Nonlocal Sets of Orthogonal States** [[paper](https://arxiv.org/abs/2603.12535)]
- [2026] **Long-time storage of entangled logical states in decoherence-free subspaces** [[paper](https://arxiv.org/abs/2603.07190)]
- [2026] **Causality is rare: some topological properties of causal quantum channels** [[paper](https://arxiv.org/abs/2603.25315)]
- [2026] **Quantum Information Recovery from Hawking Radiation via Dual-Basis Fractal Tomography** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18718721)]
- [2026] **A note on entanglement detection via the generalized realignment moments** [[paper](https://arxiv.org/abs/2602.20763)]
- [2026] **Teleportation transition of surface codes on a superconducting quantum processor** [[paper](https://arxiv.org/abs/2602.21293)]
- [2026] **Quantum correlation and coherence in a mononuclear nickel-based molecular Magnet** [[paper](https://arxiv.org/abs/2602.20013)]

##### 2025

- [2025] **Measurement Strategies and Estimation Precision in Quantum Network Tomography** [[paper](https://arxiv.org/abs/2511.01657)]

[⬆ Back to top](#paper-list)

#### Method

##### 2026

- [2026] **Tripartite Entanglement in $e^+ e^- \to t \bar{t} Z$** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.11296)]
- [2026] **Discrete and Continuous Wigner Functions in Open Quantum Systems: Non-Markovian and Thermodynamic Effects** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.29717)]
- [2026] **Quantum-enhanced Network Tomography** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.25194)]
- [2026] **Modulator-free frequency-bin entanglement certification over multimode channels** [[paper](https://doi.org/10.1117/12.3079739)]

[⬆ Back to top](#paper-list)

#### Development

##### 2026

- [2026] **Quantum Tomography and Entanglement in Semi-Leptonic $h\to VV^*$ Decays at Higher Orders** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.16218)]
- [2026] **Chip-Integrated Broadband Multi-Photon Source for Wavelength-Multiplexed Quantum Networks** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.09397)]

[⬆ Back to top](#paper-list)

#### Systems & Technology

##### 2026

- [2026] **Flagged Unitary–Replacer Channels: Sector-Resolved Choi-Moment Spectral Completion, Fixed-Fidelity Choi-Entropy Fibers, and Joint Transparency–Spectrum Identifiability** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21940129)]

[⬆ Back to top](#paper-list)

### Quantum Simulation

#### Theory

##### 2026

- [2026] **Bounded-Error Quantum Simulation via Hamiltonian and Lindbladian Learning** *Physical Review X* [[paper](https://doi.org/10.1103/s96t-n8tx)]
- [2026] **Dynamic Induction of Lattice Gauge Theories on a Quantum Computer** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.02756)]
- [2026] **Imaginary Time Evolution and Ground State Preparation Using Unitary Multi-Copy Protocols** *PRX Quantum* [[paper](https://doi.org/10.1103/1tf6-bc55)]
- [2026] **Fermi-Hubbard quantum gas microscope: analog simulation and digital gates** *Universitätsbibliothek der LMU* [[paper](https://doi.org/10.5282/edoc.37494)]
- [2026] **State preparation and detection for quantum simulation of particle collisions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.26142)]
- [2026] **TransScale Boundary State Field Calculus: Typed Observation, Admissible Transfer, and Falsifiable Persistence in Finite Open Systems** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21286690)]
- [2026] **Trans-Scale Boundary-State Field Calculus: Typed Observation, Admissible Transfer, and Falsifiable Persistence in Finite Open Systems** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21288645)]
- [2026] **A universal and efficient hybrid digital-analog fermionic quantum simulator** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.05517)]
- [2026] **Rigorous error bounds for dissipative thermal state preparation from weak system-bath coupling** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.03011)]
- [2026] **CLASSICAL AND QUANTUM SIMULATIONS OF MANY-BODY QUANTUM MAGNETS** *Purdue* [[paper](https://doi.org/10.25394/pgs.32065893.v1)]
- [2026] **Analog-Digital Quantum Computing with Quantum Annealing Processors** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.15534)]
- [2026] **Hybrid Analog-Digital Simulation of the Abelian Higgs model** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.12391)]
- [2026] **A Verified Compiler for Trotter-based Hamiltonian Simulation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19078098)]
- [2026] **Entanglement distillation based on Hamiltonian dynamics** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.10843)]

##### 2025

- [2025] **Tight bound for the total time in digital-analog quantum computation** *Physical Review Research* [[paper](https://arxiv.org/abs/2512.11619)]
- [2025] **Exploring Variational Entanglement Hamiltonians** *Quantum* [[paper](https://arxiv.org/abs/2505.10530)]

[⬆ Back to top](#paper-list)

#### Method

##### 2026

- [2026] **Exploring the Relaxation Landscape of a 2D Quantum Magnet on a 256-Qubit Processor** [[paper](https://arxiv.org/abs/2608.07178)]
- [2026] **Reinforcement LearningtoHarness Approximation Errors for Long-Time QuantumSimulation** [[paper](https://arxiv.org/abs/2608.20139)]
- [2026] **Learnable yet not simulable: a quantum resource theory of learning models** [[paper](https://arxiv.org/abs/2608.02325)]
- [2026] **Improved constant factors for qubitized Hamiltonian simulation** [[paper](https://arxiv.org/abs/2608.02734)]
- [2026] **Nonlocality-induced critical-length hierarchy from non-Hermitian competition** [[paper](https://arxiv.org/abs/2608.02746)]
- [2026] **Implementation Possibility of Quantum Simulation for Quantum Molecular Dynamics** [[paper](https://arxiv.org/abs/2608.17261)]
- [2026] **Efficient Compilation for Hamiltonian Simulation via Global Binary Symplectic Form Simplification** [[paper](https://arxiv.org/abs/2608.11579)]
- [2026] **Impact of molecular orbital localization on quantum computational resources for Hamiltonian simulation: A benchmark study of hydrogen chain systems** [[paper](https://arxiv.org/abs/2608.04481)]
- [2026] **Exact and Efficient Circuit Construction for Block Encoding Matrix Polynomials** [[paper](https://arxiv.org/abs/2608.15161)]
- [2026] **Hybrid HPC-Quantum Simulations: DFT-Quantum Embedding for Molecular Systems** [[paper](https://arxiv.org/abs/2608.12884)]
- [2026] **Quantum algorithm for differential equations via permutation matrix representation with application to the Burgers equation** [[paper](https://arxiv.org/abs/2608.19508)]
- [2026] **Symmetry Constrained Quantum Error Mitigation for the Schwinger Model** [[paper](https://arxiv.org/abs/2608.21103)]
- [2026] **Exponential-in-$N_c^2$ cost reduction of product-formula-based quantum simulations of quantum chromodynamics** [[paper](https://arxiv.org/abs/2608.21258)]
- [2026] **Simulation of Electron Transfer on Noisy Quantum Computers** *elib (German Aerospace Center)* [[paper](https://elib.dlr.de/225561/1/Abstract_Heilbronn_2026.pdf)]
- [2026] **QiliSDK** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21262912)]
- [2026] **Covariant Approximate Quantum Codes for Protected Analog Computation** [[paper](https://arxiv.org/abs/2607.07607)]
- [2026] **Polynomial equivalence of the global transverse-field Ising model and the gate model of quantum computation** [[paper](https://arxiv.org/abs/2607.01227)]
- [2026] **Constant-Depth Multi-Product Formula for Trotter Error Mitigation in Near-Term Digital Quantum Simulation** [[paper](https://arxiv.org/abs/2607.12225)]
- [2026] **Entanglement Entropy in Quantum Networks with Tunable Geometry** [[paper](https://arxiv.org/abs/2607.16394)]
- [2026] **Quantum PDE Solvers in Practice: Application-Driven Benchmarking of the Heat Equation** [[paper](https://arxiv.org/abs/2607.12688)]
- [2026] **Quantum Simulation of Strongly Correlated Fermion-Phonon Models in Circuit QED** [[paper](https://arxiv.org/abs/2607.11516)]
- [2026] **Simulation of Lindbladian dynamics via adaptive variational quantum trajectory compression** [[paper](https://arxiv.org/abs/2607.09051)]
- [2026] **Provable learning separation for predicting time-evolution of quantum many-body systems** [[paper](https://arxiv.org/abs/2607.06472)]
- [2026] **An efficient algorithm for approximate shadow Hamiltonian simulation** [[paper](https://arxiv.org/abs/2607.11882)]
- [2026] **An approach for calculating astrophysical opacities on quantum computers** [[paper](https://arxiv.org/abs/2607.02811)]
- [2026] **A Validation Framework for Quantum Simulation of Spin Dynamics against Inelastic Neutron Scattering and Classical Simulation** [[paper](https://arxiv.org/abs/2607.01568)]
- [2026] **COSMA: Communication-aware Optimization of Fermionic Simulation Kernels for Modular Quantum Architectures** [[paper](https://arxiv.org/abs/2607.09381)]
- [2026] **Hamiltonian formulations of lattice gauge theories for quantum simulation** [[paper](https://doi.org/10.22323/1.518.0007)]
- [2026] **Simulating Chemical Dynamics on Noisy Quantum Computers** *elib (German Aerospace Center)* [[paper](https://elib.dlr.de/225575/1/Abstract_Firenze_2026.pdf)]
- [2026] **Multimode Cavities for Quantum Science** *University of Chicago* [[paper](https://doi.org/10.6082/pk56z-mec90)]
- [2026] **Quantum algorithms for viscosity solutions to nonlinear Hamilton–Jacobi equations based on an entropy penalization method** *Proceedings of the National Academy of Sciences* [[paper](https://doi.org/10.1073/pnas.2607144123)]
- [2026] **Photonic Analog Quantum Simulation of (1+1)-Dimensional $U(1)$ Lattice Gauge Theory with Dynamical Matter** [[paper](https://arxiv.org/abs/2606.02756)]
- [2026] **Analog quantum simulation of chiral magnetic dynamics using optical superlattices** [[paper](https://arxiv.org/abs/2606.09708)]
- [2026] **Digital programming of spin correlations in a fermionic lattice quantum simulator** [[paper](https://arxiv.org/abs/2606.13772)]
- [2026] **3D Ising criticality with Platonic lattice superconducting qubits** [[paper](https://arxiv.org/abs/2606.16854)]
- [2026] **Quantum simulations of ultrafast optical spectroscopy of semiconductors on digital quantum computers in the semi-classical approximation** [[paper](https://arxiv.org/abs/2606.04295)]
- [2026] **Measuring Non-Stabilizerness in an SU(2) Lattice Gauge Theory** [[paper](https://arxiv.org/abs/2606.14842)]
- [2026] **Linear Combination of Hamiltonian Simulation with Commutator Scaling** [[paper](https://arxiv.org/abs/2606.11475)]
- [2026] **Fast and Parallel High-Rate STAR Architecture for Megaquop Quantum Simulation** [[paper](https://arxiv.org/abs/2606.25011)]
- [2026] **String dynamics of a (2+1)D U(1) quantum link model on a digital quantum computer** [[paper](https://arxiv.org/abs/2606.19601)]
- [2026] **Tame the Umklapp Processes in Real-Time Lattice Simulation for Hydrodynamics: An Ising Field Theory Study** [[paper](https://arxiv.org/abs/2606.09984)]
- [2026] **Theory and practice of Trotter product formulas for quantum chemistry** [[paper](https://arxiv.org/abs/2606.30741)]
- [2026] **Quantum simulation of neutrino oscillations with bosonic encoding** [[paper](https://arxiv.org/abs/2606.18755)]
- [2026] **Structure-Preserving Quantum Method of Lines for Evolutionary PDEs with Mixed Boundary Conditions** [[paper](https://arxiv.org/abs/2606.03407)]
- [2026] **Practical Estimation of Trotter Error for Hamiltonian Simulation** [[paper](https://arxiv.org/abs/2606.30738)]
- [2026] **A Voxel-Based Quantum Computing Method (VBQC) for Solid Mechanics Problem** [[paper](https://arxiv.org/abs/2606.03515)]
- [2026] **Scalable Quantum Algorithms for Gutzwiller Projection** [[paper](https://arxiv.org/abs/2606.06919)]
- [2026] **A Rust-accelerated, topology-informed workflow for Kuramoto--XY quantum simulation and NISQ benchmarking** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20382138)]
- [2026] **Universal Analog Quantum Simulation** [[paper](https://arxiv.org/abs/2605.06178)]
- [2026] **Bridging Krylov Complexity and Universal Analog Quantum Simulator** [[paper](https://arxiv.org/abs/2605.07668)]
- [2026] **On Performance and Limitations of NISQ Hardware for Simulations of Quantum Wave Packet Dynamics** [[paper](https://arxiv.org/abs/2605.20078)]
- [2026] **Time-resolved digital quantum simulation of cosmological particle creation in a de Sitter-radiation transition** [[paper](https://arxiv.org/abs/2605.04099)]
- [2026] **Fibonacci many-body scars in a decorated Rule-54 quantum cellular automaton** [[paper](https://arxiv.org/abs/2605.18622)]
- [2026] **Digital Quantum Simulation of the quantum $β$-FPUT Lattice: Formulation and Resource Estimation** [[paper](https://arxiv.org/abs/2605.28206)]
- [2026] **Mid-Circuit Measurements for Clifford Noise Reduction in Hamiltonian Simulations** [[paper](https://arxiv.org/abs/2605.06792)]
- [2026] **Near-Optimal Quantum Time Evolution Circuits via Provably Convergent Compression** [[paper](https://arxiv.org/abs/2605.17067)]
- [2026] **Beyond Unitary Quantum Simulation: Open-System Approaches to Quantum Chemistry toward Quantum Advantage** [[paper](https://arxiv.org/abs/2605.15277)]
- [2026] **Quantum dynamics of two $XX$ interacting PT-symmetric non-Hermitian qubits: enhancement of quantum annealing** [[paper](https://arxiv.org/abs/2605.13008)]
- [2026] **Beyond Commutativity: Redesigning Trotter Decomposition via Local Symmetry** [[paper](https://arxiv.org/abs/2605.16016)]
- [2026] **Fast, accurate, high-resolution simulation of large-scale Fermi-Hubbard models on a digital quantum processor** [[paper](https://arxiv.org/abs/2605.04025)]
- [2026] **The Quantum Hamiltonian Analysis Toolkit: Lowering the Barrier to Quantum Computing with Hamiltonians** [[paper](https://arxiv.org/abs/2605.11162)]
- [2026] **Scalable Measurement-Based Quantum Simulation Patterns for Benchmarking** [[paper](https://arxiv.org/abs/2605.12502)]
- [2026] **Multi-flux Aharonov-Bohm caging with tunable couplings** [[paper](https://arxiv.org/abs/2605.23546)]
- [2026] **Permutation Matrix Representation for Quantum Simulation: Comparative Resource Analysis** [[paper](https://arxiv.org/abs/2605.29279)]
- [2026] **Adiabatic Quantum Simulation of the Topological Su--Schrieffer--Heeger--Hubbard Model** [[paper](https://arxiv.org/abs/2605.11823)]
- [2026] **A minimal implementation of Yang-Mills theory on a digital quantum computer** [[paper](https://arxiv.org/abs/2604.15132)]
- [2026] **Simulating the dynamics of an SU(2) matrix model on a trapped-ion quantum computer** [[paper](https://arxiv.org/abs/2604.14094)]
- [2026] **Solvable Random Unitary Dynamics in a Disordered Tomonaga-Luttinger Liquid** [[paper](https://arxiv.org/abs/2604.25995)]
- [2026] **Taming Trotter Errors with Quantum Resources** [[paper](https://arxiv.org/abs/2604.13486)]
- [2026] **Observation of glueball excitations and string breaking in a $2+1$D $\mathbb{Z}_2$ lattice gauge theory on a trapped-ion quantum computer** [[paper](https://arxiv.org/abs/2604.07435)]
- [2026] **Hardware-Efficient Hamiltonian Simulation via Trotter-Initialized Variational Optimization with Native Placement** [[paper](https://arxiv.org/abs/2604.26663)]
- [2026] **Programming long-range interactions in analog quantum simulators** [[paper](https://arxiv.org/abs/2604.22483)]
- [2026] **MonteQ: A Monte Carlo Tree Search Based Quantum Circuit Synthesis Framework** [[paper](https://arxiv.org/abs/2604.19029)]
- [2026] **Hamiltonian simulation for 3D elastic wave equations in homogeneous elastic media** [[paper](https://arxiv.org/abs/2604.20284)]
- [2026] **Approximate Hamiltonian Simulation Algorithm for Efficient Fluid Quantum Simulations** [[paper](https://arxiv.org/abs/2604.17489)]
- [2026] **Three-body interactions in Rydberg lattices** [[paper](https://arxiv.org/abs/2604.11870)]
- [2026] **Non-normality and dissipation in Markovian quantum dynamics: Implications for quantum simulation** [[paper](https://arxiv.org/abs/2604.16869)]
- [2026] **Hybrid Quantum-Classical Algorithm for Hamiltonian Simulation** [[paper](https://arxiv.org/abs/2604.05881)]
- [2026] **Quantum Algorithms for Heterogeneous PDEs: The Neutron Diffusion Eigenvalue Problem** [[paper](https://arxiv.org/abs/2604.05098)]
- [2026] **Assessing System Capabilities and Bottlenecks of an Early Fault-Tolerant Bicycle Architecture** [[paper](https://arxiv.org/abs/2604.20013)]
- [2026] **qSHIFT: An Adaptive Sampling Protocol for Higher-Order Quantum Simulation** [[paper](https://arxiv.org/abs/2604.26263)]
- [2026] **Classical and Quantum Speedups for Non-Convex Optimization via Energy Conserving Descent** [[paper](https://arxiv.org/abs/2604.13022)]
- [2026] **Scalable quantum resources with short-range interacting spin-$\frac12$ chains** [[paper](https://arxiv.org/abs/2603.17071)]
- [2026] **One-to-one quantum simulation of a frustrated magnet with 256 qubits** [[paper](https://arxiv.org/abs/2603.20372)]
- [2026] **Chiral and bond-ordered phases in a triangular-ladder superconducting-qubit quantum simulator** [[paper](https://arxiv.org/abs/2603.16993)]
- [2026] **Trotter Scars: Trotter Error Suppression in Quantum Simulation** [[paper](https://arxiv.org/abs/2603.29857)]
- [2026] **Symmetric Trotterization in digital quantum simulation of quantum spin dynamics** [[paper](https://arxiv.org/abs/2603.07903)]
- [2026] **Onset of Ergodicity Across Scales on a Digital Quantum Processor** [[paper](https://arxiv.org/abs/2603.12236)]
- [2026] **Error-Mitigated Hamiltonian Simulation: Complexity Analysis and Optimization for Near-Term and Early-Fault-Tolerant Quantum Computers** [[paper](https://arxiv.org/abs/2603.11527)]
- [2026] **Efficient Shadow Tomography of Thermal States** [[paper](https://arxiv.org/abs/2603.16845)]
- [2026] **Optimization of the HHL Algorithm** [[paper](https://arxiv.org/abs/2603.15756)]
- [2026] **HyQBench: A Benchmark Suite for Hybrid CV-DV Quantum Computing** [[paper](https://arxiv.org/abs/2603.04398)]
- [2026] **Quantum Simulation of Coupled Harmonic Oscillators: From Theory to Implementation** [[paper](https://arxiv.org/abs/2603.05479)]
- [2026] **Quantum simulation of Liouville equation in geometrical optics with partial transmission and reflection via Schrödingerization** [[paper](https://arxiv.org/abs/2603.11998)]
- [2026] **Low-entropy arrays of microwave-shielded molecules prepared by interaction blockade** [[paper](https://arxiv.org/abs/2603.00400)]
- [2026] **Robust high-order quantum simulation using finite-width pulses** [[paper](https://arxiv.org/abs/2603.15502)]
- [2026] **Efficient Quantum Simulation for Nonlinear Stochastic Differential Equations** [[paper](https://arxiv.org/abs/2603.12398)]
- [2026] **Qubit discretizations of d=3 conformal field theories** [[paper](https://arxiv.org/abs/2603.07420)]
- [2026] **Realizing the Emery Model in Optical Lattices for Quantum Simulation of Cuprates and Nickelates** [[paper](https://arxiv.org/abs/2603.11037)]
- [2026] **Quantum simulation of Motzkin spin chain with Rydberg atoms** [[paper](https://arxiv.org/abs/2603.23422)]
- [2026] **Quantum simulation in the Heisenberg picture via vectorization** [[paper](https://arxiv.org/abs/2602.20154)]
- [2026] **Entanglement-Induced Resilience of Quantum Dynamics** [[paper](https://arxiv.org/abs/2602.20987)]
- [2026] **Identifying quantum coherence in quantum annealers** [[paper](https://arxiv.org/abs/2602.21355)]

##### 2025

- [2025] **Hamiltonian simulation with explicit formulas for digital-analog quantum computing** *Physical Review A* [[paper](https://arxiv.org/abs/2511.11404)]
- [2025] **Simulating electron transfer on noisy quantum computers** *Nature Communications* [[paper](https://arxiv.org/abs/2508.18141)]

[⬆ Back to top](#paper-list)

#### Application

##### 2026

- [2026] **Precision quantum simulation of magnon spectra and interactions** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.13301)]
- [2026] **Realization of fermionic Laughlin state on a quantum processor** *Nature Communications* [[paper](https://doi.org/10.1038/s41467-026-72769-y)]

[⬆ Back to top](#paper-list)

#### Development

##### 2026

- [2026] **First- and Second-Order Digital Quantum Simulation of Three-Level Jaynes-Cummings Dynamics on Superconducting Quantum Processors** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.20614)]

[⬆ Back to top](#paper-list)

### Quantum Machine Learning

#### Theory

##### 2026

- [2026] **Machine Unlearning in the Era of Quantum Machine Learning: An Empirical Study** *Lecture notes in computer science* [[paper](https://doi.org/10.1007/978-3-032-31673-8_3)]
- [2026] **Hilbert-Space Quantum Neural Representation Learning for NISQ-Era Quantum Computing** *Lancaster EPrints (Lancaster University)* [[paper](https://doi.org/10.17635/lancaster/thesis/3358)]
- [2026] **Comparing Classical and Quantum Machine Learning Approaches for Crop and Weed Detection** *Engineering Research Express* [[paper](https://doi.org/10.1088/2631-8695/ae98fa)]
- [2026] **Adaptive Quantum Physics-Informed Neural Networks for Differential Equations with Applications to Fluid Dynamics** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.00850)]
- [2026] **Evaluating Quantum Advantage in Noisy Machine Learning: A Survey of Hardware Degradation, Mitigation Overhead, and Algorithmic Resilienc** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21880331)]
- [2026] **Machine learning-accelerated inverse design of energy materials: A critical review of graph neural networks, physics-informed models, and generative AI for batteries, perovskite solar cells, and electrocatalysts** *Next Materials* [[paper](https://doi.org/10.1016/j.nxmate.2026.102969)]
- [2026] **Hybrid Classical–Quantum-Inspired Neural Network with Simulated Variational Circuit for Credit Card Fraud Detection** *Asian Journal of Research in Computer Science* [[paper](https://doi.org/10.9734/ajrcos/2026/v19i7877)]
- [2026] **Grokking and epoch-wise double descent in quantum neural networks** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.08350)]
- [2026] **Quantum Enhanced Hybrid Face Recognition Using MultiGate-Quantum Convolutional Neural Network (MG-QCNN)** *International Journal for Research in Applied Science and Engineering Technology* [[paper](https://doi.org/10.22214/ijraset.2026.84199)]
- [2026] **Early Detection of Chronic Diseases Using Quantum Machine Learning Algorithms** *SPU Journal of Science Technology and Management Research* [[paper](https://doi.org/10.63766/spujstmr.26.000083)]
- [2026] **Feature‑Adaptive Fusion in Hybrid Quantum–Classical Neural Networks for Robust Biomedical Image Classification** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9777113/v1)]
- [2026] **Deficit Variational Theory for Six Core Artificial Intelligence Paradigms: Transformers, Diffusion Models, LLMs, GNNs, Reinforcement Learning and Quantum Machine Learning (QBN Programme)** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21271117)]
- [2026] **Arithmetic-aware quantum neural networks using fault-tolerant BCD-Excess-3 encoding** *Engineering Research Express* [[paper](https://doi.org/10.1088/2631-8695/ae82b7)]
- [2026] **Research on the application potential and synergistic effects of quantum computing in the field of artificial intelligence: Integrative analysis centered on quantum machine learning (VQC/QNN)** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21273096)]
- [2026] **AF-HQCNN: Adaptive Federated Hybrid Quantum Convolutional Neural Network for Privacy-Preserving Medical Image Classification** *International Research Journal on Advanced Science Hub* [[paper](https://doi.org/10.47392/irjash.2026.032)]
- [2026] **Quantum LEGO Learning: A Modular Design Principle for Hybrid Artificial Intelligence** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9730742/v1)]
- [2026] **Quantum Machine Learning for Industrial Applications** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.14822)]
- [2026] **Adaptive Architecture Quantum Meta-Learning for Bayesian Binary Neural Networks** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20608508)]
- [2026] **Quantum Machine Learning for Industrial Artificial Intelligence** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/979-8-2600-0156-1.ch012)]
- [2026] **Quantum image representation-based quantum neural networks for binary classification** *The Journal of Supercomputing* [[paper](https://doi.org/10.1007/s11227-026-08621-3)]
- [2026] **Quantum machine learning for passive sonar: Spectral feature extraction and Hybrid convolution neural network classification of ship propeller signals** *Ocean Engineering* [[paper](https://doi.org/10.1016/j.oceaneng.2026.125667)]
- [2026] **Empirical Study of Quantum Machine Learning Algorithms for Accelerating Functional Materials Discovery** *Nigerian Journal of Physics* [[paper](https://doi.org/10.62292/njp.v35i3.2026.565)]
- [2026] **Neural Wavefunctions in Quantum Field Theory I: Asymptotic Freedom** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.20791)]
- [2026] **Quantum machine learning for capacity degradation analysis of Li-ion batteries** *Computational Materials Science* [[paper](https://doi.org/10.1016/j.commatsci.2026.114791)]
- [2026] **Accelerating physics-informed neural networks for full waveform inversion using a hybrid quantum-classical finite-basis architecture** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.01110)]
- [2026] **Hybrid Quantum-Classical Machine Learning Models: A Review** *International Journal of Engineering and Creative Science* [[paper](https://doi.org/10.66631/ijecs.2026.9.10.8)]
- [2026] **Quantum Artificial Intelligence for Medical Data: Comparative Evaluation of Quantum Machine Learning Models** *Cureus Journal of Computer Science.* [[paper](https://doi.org/10.7759/s44389-025-00063-x)]
- [2026] **Predicting second harmonic generation in double quantum dots under a magnetic field using deep neural networks** *Ceramics International* [[paper](https://doi.org/10.1016/j.ceramint.2026.05.273)]
- [2026] **Quantum machine learning for complex systems: paradigms, applications, and challenges** *Academia quantum.* [[paper](https://doi.org/10.20935/acadquant8243)]
- [2026] **Quantum-Inspired Variational Inference for Non-Convex Stochastic Optimization: A Unified Mathematical Framework with Convergence Guarantees and Applications to Machine Learning in Communication Networks** *Mathematics* [[paper](https://doi.org/10.3390/math14071236)]
- [2026] **Adversarial Robustness in Quantum Machine Learning: A Scoping Review** *Computers* [[paper](https://doi.org/10.3390/computers15040233)]
- [2026] **Hybrid Quantum Neural Networks for Enhanced Breast Cancer Thermographic Classification: A Novel Quantum-Classical Integration Approach** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.16953)]
- [2026] **A Hybrid Semi‐Inverse Variational and Machine Learning Approach for the Schrödinger Equation** *Advanced Physics Research* [[paper](https://doi.org/10.1002/apxr.70127)]
- [2026] **Hybrid Quantum-Classical Neural Network for Automated Pneumonia Detection from Chest X-Rays: A Comparative Study** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-8940353/v1)]
- [2026] **Automated Ansatz Generation Using Neural Networks for Fermi-Hubbard Simulation** *DigitalCommons-IMSA (Illinois Mathematics and Science Academy)* [[paper](https://digitalcommons.imsa.edu/sir_presentations/2026/session2/41)]
- [2026] **Quantum Measurement Statistics as Bayesian Uncertainty Estimators for Physics-Constrained Learning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.10896)]
- [2026] **A novel quantum convolutional neural network framework for quantum-enhanced classification of pixelated colour images** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-45140-w)]
- [2026] **Benchmarking quantum machine learning methods for intrusion detection on noisy quantum computers** *Quantum Machine Intelligence* [[paper](https://doi.org/10.1007/s42484-026-00379-4)]
- [2026] **Spectral invariance and maximality properties of the frequency spectrum of quantum neural networks** *Quantum Machine Intelligence* [[paper](https://doi.org/10.1007/s42484-026-00372-x)]
- [2026] **Quantum Machine Learning for Classification Tasks:Variational Quantum Classifiers and Quantum Neural Networks** *Journal of Science Engineering Technology and Management Sciences* [[paper](https://doi.org/10.64771/jsetms.2026.v03.i03.pp395-400)]
- [2026] **Machine learning the single-Λ hypernuclei with neural-network quantum states** *Physics Letters B* [[paper](https://doi.org/10.1016/j.physletb.2026.140285)]
- [2026] **Design and Analysis of Modern Quantum Neural Network Architectures for Intelligent Systems** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/979-8-2600-0008-3.ch009)]
- [2026] **Noise Models Impacts and Mitigation Strategies in Photonic Quantum Machine Learning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.09645)]
- [2026] **zkQML: Verifiable and Privacy-Preserving Inference for Quantum Machine Learning (Student Abstract)** *Proceedings of the AAAI Conference on Artificial Intelligence* [[paper](https://doi.org/10.1609/aaai.v40i48.42232)]
- [2026] **Neural quantum support vector data description for one-class classification** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.02700)]
- [2026] **Novel Machine Learning and Quantum Computing for Audio Biometrics: Deep Audio Feature Analysis and Speech Patterns for Real-Time Authentication Systems** [[paper](https://doi.org/10.1109/iconic67661.2026.11517689)]
- [2026] **Exploring Quantum Convolutional Neural Networks for 2D Human Pose Estimation using Synthetic Data** [[paper](https://doi.org/10.1109/icfact66887.2026.11518149)]
- [2026] **Quantum-Enhanced Hybrid Variational Neural Network for IoT Intrusion Detection** [[paper](https://doi.org/10.1109/icbdml68582.2026.11544431)]
- [2026] **Quantum Machine Learning for Complex Systems** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.20352)]
- [2026] **Quantum Optimization for Machine Learning** *Auerbach Publications eBooks* [[paper](https://doi.org/10.1201/9781003674566-10)]
- [2026] **Latest Developments in Quantum Optimization for Machine Learning** *Auerbach Publications eBooks* [[paper](https://doi.org/10.1201/9781003674566-12)]
- [2026] **Quantum recurrent neural network for sequential labeling** *Knowledge and Information Systems* [[paper](https://doi.org/10.1007/s10115-026-02685-6)]
- [2026] **Quantum Machine Learning for Numerical Regression: A Hybrid Quantum-Classical Approach to Predictive Modeling** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18754924)]

##### 2025

- [2025] **TensorHyper-VQC: a tensor-train-guided hypernetwork for robust and scalable variational quantum computing** *npj Quantum Information* [[paper](https://arxiv.org/abs/2508.01116)]
- [2025] **Learning to maximize quantum neural network expressivity via effective rank** *Quantum Science and Technology* [[paper](https://arxiv.org/abs/2506.15375)]

##### 2024

- [2024] **Resource-efficient equivariant quantum convolutional neural networks** *Quantum Machine Intelligence* [[paper](https://arxiv.org/abs/2410.01252)]

[⬆ Back to top](#paper-list)

#### Method

##### 2026

- [2026] **Quantum physics-informed neural network for scattered wavefields** *International Journal of Modern Physics C* [[paper](https://doi.org/10.1142/s0129183126430096)]
- [2026] **An efficient hybrid quantum machine learning framework for Alzheimer classification** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-64291-4)]
- [2026] **Hybrid Quantum Neural Networks: Theory, Implementations, and Applications** [[paper](https://arxiv.org/abs/2608.01194)]
- [2026] **Distributed Variational Quantum Eigensolver: Embarrassingly Parallel strategies on NISQ** [[paper](https://arxiv.org/abs/2608.19824)]
- [2026] **Expressive Power and Limitations of Multi-photon Quantum Neural Networks** [[paper](https://arxiv.org/abs/2608.01365)]
- [2026] **QSVM-RQNN: Low-Qubit Recurrent Quantum Similarity Learning for Condition Monitoring and Fault Classification** [[paper](https://arxiv.org/abs/2608.09652)]
- [2026] **The Input Problem: A Permanent Bottleneck for Quantum Machine Learning** [[paper](https://arxiv.org/abs/2608.08433)]
- [2026] **How Quantum Is the Advantage? A Fair, Calibration- and Noise-Aware Benchmark and Attribution Audit of Quantum Machine Learning for Network Intrusion Detection** [[paper](https://arxiv.org/abs/2608.18155)]
- [2026] **Scalable nuclear shell model calculations on noisy quantum computers** [[paper](https://arxiv.org/abs/2608.16371)]
- [2026] **From Barren Plateaus to SPSA Optimization in Variational Quantum Eigensolvers** [[paper](https://arxiv.org/abs/2608.09810)]
- [2026] **Optimizing Subspace Expansion in Quantum Chemistry through Operator Selection and Reference State Choice** [[paper](https://arxiv.org/abs/2608.16362)]
- [2026] **Benchmarking Quantum and Classical Machine Learning Models on Oncological Data** [[paper](https://arxiv.org/abs/2608.11373)]
- [2026] **A systematic literature review of quantum machine learning for medical: trends, datasets, topics, and methods** *International Journal of Cognitive Computing in Engineering* [[paper](https://doi.org/10.1016/j.ijcce.2026.05.002)]
- [2026] **QCCNN: A novel quantum-classical convolutional neural network for end-to-end EEG-based motor imagery classification** *Advanced Engineering Informatics* [[paper](https://doi.org/10.1016/j.aei.2026.104683)]
- [2026] **A Staged Ablation Study of Quantum Convolution and Variational Quantum Classification Placement in Hybrid CNNs for Brain Tumor MRI Classification** *International Scientific Journal of Engineering and Management* [[paper](https://doi.org/10.55041/isjem08544)]
- [2026] **QUASAR: A Quantum-Classical Neural Network for SAR Satellite Physical-Layer Authentication** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2608.20240)]
- [2026] **Machine Learning-Based Denoising for Single-Photon Detection With MKIDs** *IEEE Transactions on Applied Superconductivity* [[paper](https://doi.org/10.1109/tasc.2026.3718447)]
- [2026] **Exploring the potential of Quantum Graph Neural Networks in analyzing Large-Scale Structure of Universe** *Astronomy and Computing* [[paper](https://doi.org/10.1016/j.ascom.2026.101095)]
- [2026] **Quantum machine learning interatomic potential: Application of variational quantum algorithm** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2607.27841)]
- [2026] **Quantum Machine Learning Applications in Healthcare** [[paper](https://doi.org/10.1201/9781003646068-8)]
- [2026] **Quantum Machine Learning Models, Limitations, and Opportunities in the NISQ Era: A Review** *Journal of Multiscale Materials Informatics* [[paper](https://doi.org/10.62411/jimat.v3i1.15955)]
- [2026] **Depth-dependent separability growth in variational quantum neural networks and its empirical coupling to a parameter-sensitivity statistic** *Physica Scripta* [[paper](https://doi.org/10.1088/1402-4896/ae87e8)]
- [2026] **Qutrit-Based Neural Quantum Kernels for Classification Tasks** [[paper](https://arxiv.org/abs/2607.23683)]
- [2026] **A Non-Commutative Voronovskaya Theorem for Quantum Neural Network Operators** [[paper](https://arxiv.org/abs/2607.11907)]
- [2026] **Benchmarking loss functions for trainable quantum feature maps** [[paper](https://arxiv.org/abs/2607.12487)]
- [2026] **An Agentic Formalization for Certified Quantum Neural Network Design** [[paper](https://arxiv.org/abs/2607.12981)]
- [2026] **SoK: Adversarial Robustness of the Variational Quantum Eigensolver via Red-Teaming** [[paper](https://arxiv.org/abs/2607.19318)]
- [2026] **How Hard Is Quantum Advantage? A Cloud Microphysics Stress Test for Variational Quantum Models** [[paper](https://arxiv.org/abs/2607.04915)]
- [2026] **Digital Quantum Simulation of Nonequilibrium Dynamics in the Schwinger Model under a Strong External Electric Field** [[paper](https://arxiv.org/abs/2607.02894)]
- [2026] **Benchmarking Quantum Simulations of the Lipkin-Meshkov-Glick Model Using Large Tensor Networks** [[paper](https://arxiv.org/abs/2607.28570)]
- [2026] **The Fourier Wall: Why Public Tabular Datasets Refuse Quantum Advantage, and a Certified Recipe for Where It Lives** [[paper](https://arxiv.org/abs/2607.15815)]
- [2026] **Alleviating the Sparse Matrix Scaling Bottleneck in Adaptive VQE via Greedy Operator Commutativity Partitioning and High-Order Taylor State Evolution** [[paper](https://arxiv.org/abs/2607.15906)]
- [2026] **An Integrated DFT-Wannier-Quantum Embedding Pipeline for Strongly Correlated Materials: Scaling Benchmarks in Li-hBN** [[paper](https://arxiv.org/abs/2607.23590)]
- [2026] **HarmQ: Harmonic Backdoor Attacks Against Quantum Neural Networks** [[paper](https://arxiv.org/abs/2607.12055)]
- [2026] **QR-SPPS: Quantum-Native Retail Shock Propagation and Policy Stress Simulator** [[paper](https://arxiv.org/abs/2607.16275)]
- [2026] **A Semantic Framework for Reproducible Variational Quantum Algorithm Execution Records** [[paper](https://arxiv.org/abs/2607.03982)]
- [2026] **Detecting quantum phase transitions via shallow variational quantum circuits** [[paper](https://arxiv.org/abs/2607.25345)]
- [2026] **Quantum Machine Learning for Land Cover Classification: Evaluating Variational Quantum Classifiers Using Sentinel-2 Imagery** [[paper](https://doi.org/10.5753/sbccq.2026.21026)]
- [2026] **Benchmarking Classical and Quantum Machine Learning for Potency Prediction across Ten Therapeutically Relevant Targets** *Figshare* [[paper](https://figshare.com/articles/journal_contribution/Benchmarking_Classical_and_Quantum_Machine_Learning_for_Potency_Prediction_across_Ten_Therapeutically_Relevant_Targets/32927686)]
- [2026] **Quantum Machine Learning for Enhanced Cardiovascular Disease Risk Prediction** [[paper](https://doi.org/10.3390/engproc2026150039)]
- [2026] **Quantum-Aided Bayesian Learning for the Prediction and Uncertainty Quantification of Remaining Useful Life** *PHM Society European Conference* [[paper](https://doi.org/10.36001/phme.2026.v9i1.4971)]
- [2026] **Quantum-Enhanced Intrusion Detection Systems for IoT Networks: Trends, Challenges, and Future Directions** *IJARCCE* [[paper](https://doi.org/10.17148/ijarcce.2026.15723)]
- [2026] **Context-Aware Battery Health Modelling Using an Entangled Variational Quantum Model** *IFIP advances in information and communication technology* [[paper](https://doi.org/10.1007/978-3-032-30809-2_3)]
- [2026] **Quantum computing-based solver for interacting power grids** [[paper](https://arxiv.org/abs/2607.29582)]
- [2026] **Quantum Machine Learning and Quantum Deep Learning: A Review of Algorithms, Applications, Challenges and Future Directions** *International Journal of Research Publication and Reviews* [[paper](https://doi.org/10.55248/gengpi.07.0626.15b19)]
- [2026] **Tailor Made Embeddings for Quantum Machine Learning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.26312)]
- [2026] **Quantum–AI for High-Dimensional Learning: Graph Neural Networks, Topological Data Analysis, Tensor Networks, and Sparse Predictive Modelling** *International Journal of Academic and Industrial Research Innovations(IJAIRI)* [[paper](https://doi.org/10.62311/nesx/rpj2-30062026)]
- [2026] **An LLM System for Autonomous Variational Quantum Circuit Design** [[paper](https://arxiv.org/abs/2606.13380)]
- [2026] **Adaptive directional gradients for parameterised quantum circuits** [[paper](https://arxiv.org/abs/2606.09734)]
- [2026] **Variational Quantum Eigensolver-Based Quantum Bootstrap Embedding for Molecules** [[paper](https://arxiv.org/abs/2606.17095)]
- [2026] **Continuous-variable ADAPT-VQE for bosonic lattice models** [[paper](https://arxiv.org/abs/2606.05297)]
- [2026] **Enhancing Quantum Machine Learning with Anyons** [[paper](https://arxiv.org/abs/2606.16090)]
- [2026] **JGRA: Jacobian Geometry Robustness Assessment in NISQ Noise-Aware Quantum Neural Networks** [[paper](https://arxiv.org/abs/2606.09964)]
- [2026] **High-fidelity two-qubit gates in a 7-qubit register for quantum networks** [[paper](https://arxiv.org/abs/2606.14847)]
- [2026] **Orbital-optimized spin-adapted multistate contracted VQE for excited states and properties on quantum hardware** [[paper](https://arxiv.org/abs/2606.15489)]
- [2026] **Clifford disentanglers for entanglement reduction in molecular electronic structure simulations** [[paper](https://arxiv.org/abs/2606.12056)]
- [2026] **Machine Learning-based Quantum Error Mitigation for Variational Algorithms** [[paper](https://arxiv.org/abs/2606.02697)]
- [2026] **Beyond the Expressivity-Trainability Paradox: A Dynamical Lie Algebra Perspective on Navigating Barren Plateaus in Quantum Machine Learning** [[paper](https://arxiv.org/abs/2606.31536)]
- [2026] **Quantum Generative Diffusion Model for Real-World Time Series** [[paper](https://arxiv.org/abs/2606.27561)]
- [2026] **Quantum Optimization Algorithms for Strongly Correlated Many-Body Systems** [[paper](https://arxiv.org/abs/2606.03147)]
- [2026] **Pulse-optimised circuit elements for scalable and noise-resilient quantum chemistry** [[paper](https://arxiv.org/abs/2606.17357)]
- [2026] **Hamiltonian-Aware ADAPT Variational Quantum Eigensolver for Molecular Ground-State Simulation** [[paper](https://arxiv.org/abs/2606.13118)]
- [2026] **Shallow Quantum Circuits for Deep Chemistry via Valence Bond Embeddings** [[paper](https://arxiv.org/abs/2606.26882)]
- [2026] **Feature Encoding in Quantum Machine Learning: A Survey and Practical Guidelines** [[paper](https://arxiv.org/abs/2606.05387)]
- [2026] **Symmetries and overparametrization properties of Hamiltonian variational ansatzes for the $(1+1)$d $\mathbb{Z}_2$ lattice gauge theory** [[paper](https://arxiv.org/abs/2606.05719)]
- [2026] **Gatekeepers and Hallucinations: A Layered Evaluation Framework for LLM-Driven Quantum Circuit Generation** [[paper](https://arxiv.org/abs/2606.18422)]
- [2026] **All-valid-state HOBO encoding for constrained combinatorial optimization on NISQ devices** [[paper](https://arxiv.org/abs/2606.20017)]
- [2026] **On a Central Limit Theorem and Sanov's principle for quantum neural networks** [[paper](https://arxiv.org/abs/2606.21721)]
- [2026] **Tree-Structured Commutativity Packing in Adaptive Variational Quantum Simulation: Measurement Overhead and Representation Limits** [[paper](https://arxiv.org/abs/2606.13387)]
- [2026] **Alleviating the Sparse Matrix Scaling Bottleneck in Adaptive VQE via High-Order Taylor State Evolution** [[paper](https://arxiv.org/abs/2606.29692)]
- [2026] **Degradation forecasting in laser-engineered TiO₂ electrodes for sodium-ion storage using quantum machine learning** *Future Batteries* [[paper](https://doi.org/10.1016/j.fub.2026.100185)]
- [2026] **QUANTUM-INSPIRED MACHINE LEARNING FRAMEWORK FOR HEALTHCARE DECISION SUPPORT SYSTEMS** *QP-AIDSE* [[paper](https://doi.org/10.65713/qpv2i121)]
- [2026] **Quantum Machine Learning-based Adaptive Modulation for Optimising Wireless Communication Systems** [[paper](https://doi.org/10.1201/9781003667766-13)]
- [2026] **Quantum Machine Learning for Optimizing Drug Free Discovery** *Open MIND* [[paper](https://www.ijert.org/quantum-machine-learning-for-optimizing-drug-free-discovery)]
- [2026] **Quantum Convolutional Neural Networks for Groundwater Heat Plume Prediction: A Surrogate Modeling Approach** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.23411)]
- [2026] **Comparative analysis of quantum machine learning and classical deep learning for power system fault classification under noisy conditions** *Renewable Energy System and Equipment* [[paper](https://doi.org/10.1016/j.rese.2026.05.001)]
- [2026] **Mango leaf disease classification using a hybrid model of ResNet50 and quantum machine learning** *Frontiers in Sustainable Food Systems* [[paper](https://doi.org/10.3389/fsufs.2026.1837661)]
- [2026] **Design of an Iterative Explainable Quantum Machine Learning Method for Adaptive Fraud Detection in Financial Transaction Systems** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20492420)]
- [2026] **Multiclass classification using variational quantum circuit on benchmark dataset** *International Journal of Informatics and Communication Technology (IJ-ICT)* [[paper](https://doi.org/10.11591/ijict.v15i2.pp578-587)]
- [2026] **Machine learning approach to tomographic pattern generation and classification of quantum states of light** *APS Open Science* [[paper](https://doi.org/10.1103/c7g1-yj2y)]
- [2026] **Classical Quantum Federated Learning for Mental Stress Detection** *International Journal for Research in Applied Science and Engineering Technology* [[paper](https://doi.org/10.22214/ijraset.2026.83926)]
- [2026] **Hybrid Classical–Quantum Surrogate Modeling for Nonlinear Reactor Dynamics: A Comparative Study of GRU, LSTM, Transformer, and Variational Quantum Circuits** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20509903)]
- [2026] **Hybrid quantum-classical GANs for the generation of adversarial network flows** [[paper](https://doi.org/10.1117/12.3095130)]
- [2026] **Quantum State Preparation via Neural Network Encoding in Quantum Machine Learning** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.31006)]
- [2026] **Integrating quantum neural networks with the variational quantum eigensolver to calculate nonadiabatic coupling vectors** *The Journal of Chemical Physics* [[paper](https://doi.org/10.1063/5.0319519)]
- [2026] **Efficient Mutation Testing of Quantum Machine Learning Models** [[paper](https://arxiv.org/abs/2605.00107)]
- [2026] **A Transferable Machine Learning Approach to Predict Optimized Orbitals for Electronic Structure Problems** [[paper](https://arxiv.org/abs/2605.04174)]
- [2026] **Probability Distribution Analysis of the Cascaded Variational Quantum Eigensolver** [[paper](https://arxiv.org/abs/2605.00807)]
- [2026] **Geometric Analysis of Variational Quantum Eigensolver** [[paper](https://arxiv.org/abs/2605.27795)]
- [2026] **Rethinking Expressibility-Trainability Trade-off in Hybrid Quantum Neural Networks** [[paper](https://arxiv.org/abs/2605.25768)]
- [2026] **Provable and scalable quantum Gaussian processes for quantum learning** [[paper](https://arxiv.org/abs/2605.00099)]
- [2026] **Automated Unitary Coupled Cluster Circuit Design via Differentiable Quantum Architecture Search** [[paper](https://arxiv.org/abs/2605.28049)]
- [2026] **Thermodynamic-limit dispersion relations on trapped-ion quantum hardware** [[paper](https://arxiv.org/abs/2605.28599)]
- [2026] **Failure-Guided Fuzzing for Hybrid Quantum-Classical Programs** [[paper](https://arxiv.org/abs/2605.14219)]
- [2026] **Hybrid Quantum-Classical Machine Learning for Medical Image Classification under Noisy Conditions** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20125585)]
- [2026] **A Systematic Review of Quantum Machine Learning in Education 5.0: Applications and Future Research Directions** *Algorithms* [[paper](https://doi.org/10.3390/a19050379)]
- [2026] **Quantum Machine Learning for Cyber Threat Intelligence: A Scoping Review of Current Capabilities and Future Directions** [[paper](https://doi.org/10.1109/cspa68262.2026.11517902)]
- [2026] **Comparative Analysis of Classical and Quantum Machine Learning Algorithms in Breast Cancer Classification** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9675941/v1)]
- [2026] **Spectroscopically Constrained Quantum Machine Learning for Complex Systems: Applying the Maxwell-Scretching Framework, the Scretching Quantum Chain, and the Scretching-Schrodinger Equation to QML** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20054300)]
- [2026] **Discovering Data Encoding Strategies for Quantum-Classical Neural Networks Using Monte Carlo Tree Search** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.18540)]
- [2026] **Quantum Enhanced Data-driven Learning for Defect Reduction in Etching Process** [[paper](https://doi.org/10.1109/asmc69324.2026.11551187)]
- [2026] **Hybrid Variational Quantum-Classical Neural Networks for CPT-Based Prediction of Shear Wave Velocity and Soil Behavior Type Index: A Sanity Check Study with Ensemble and Deep Learning Methods** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9524786/v1)]
- [2026] **ADVANCED CUSTOMER CHURN PREDICTION IN BANKING USING USING CLASSICAL AND QUANTUM LEARNING MODELS** *International Journal of Engineering Technology Research & Management* [[paper](https://doi.org/10.5281/zenodo.20054721)]
- [2026] **Support Vector Machine with a Scalable Quantum Kernel** [[paper](https://arxiv.org/abs/2605.31449)]
- [2026] **Quantum Machine Learning for Cyberattack Prediction** *International Journal for Research in Applied Science and Engineering Technology* [[paper](https://doi.org/10.22214/ijraset.2026.80166)]
- [2026] **Multiplexers based on Quantum Neural Networks** [[paper](https://doi.org/10.1109/pacet68758.2026.11498280)]
- [2026] **A Distributed Quantum Neural Network for Network Anomaly Detection** [[paper](https://doi.org/10.1109/qcnc69040.2026.00109)]
- [2026] **A Comprehensive Analysis of Accuracy and Robustness in Quantum Neural Networks** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.26110)]
- [2026] **Quantum Machine Learning for Accelerated Drug Discovery** *International Journal of Engineering Research and Science & Technology* [[paper](https://doi.org/10.62643/ijerst.2026.v22.n2.pp200-207)]
- [2026] **Noise-Aware Adaptive Variational Quantum Neural Network (NAVQNN) For Robust NISQ-Era Banknote Authentication** [[paper](https://doi.org/10.1109/ickecs70176.2026.11527643)]
- [2026] **A hardware efficient quantum residual neural network without post-selection** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2604.06866)]
- [2026] **QEML-Net: Quantum-enhanced machine learning for predictive maintenance in industrial IoT environments using hybrid classical-quantum neural networks** *Journal of Artificial Intelligence Machine Learning and Neural Network* [[paper](https://doi.org/10.55529/jaimlnn.61.100.111)]
- [2026] **Noise-enhanced quantum kernels on analog quantum computers** [[paper](https://arxiv.org/abs/2604.12476)]
- [2026] **Robustness Evaluation of Hybrid Quantum Neural Networks under Noise Models via System-Level Error Mitigation** [[paper](https://arxiv.org/abs/2604.17515)]
- [2026] **Ground-state energies of Ising models calculated using the samples from a quantum computer that simulates short-time evolution** [[paper](https://arxiv.org/abs/2604.25715)]
- [2026] **Ansätz Expressivity and Optimization in Variational Quantum Simulations of Transverse-field Ising Model Across System Sizes** [[paper](https://arxiv.org/abs/2604.20961)]
- [2026] **Non-variational supervised quantum kernel methods: a review** [[paper](https://arxiv.org/abs/2604.07896)]
- [2026] **Quantum computing for effective nuclear lattice model** [[paper](https://arxiv.org/abs/2604.13430)]
- [2026] **Soft-Quantum Algorithms** [[paper](https://arxiv.org/abs/2604.06523)]
- [2026] **Investigation of Automated Design of Quantum Circuits for Imaginary Time Evolution Methods Using Deep Reinforcement Learning** [[paper](https://arxiv.org/abs/2604.07951)]
- [2026] **Quantum-Safe Code Auditing: LLM-Assisted Static Analysis and Quantum-Aware Risk Scoring for Post-Quantum Cryptography Migration** [[paper](https://arxiv.org/abs/2604.00560)]
- [2026] **Eliminating Vendor Lock-In in Quantum Machine Learning via Framework-Agnostic Neural Networks** [[paper](https://arxiv.org/abs/2604.04414)]
- [2026] **Option Pricing on Noisy Intermediate-Scale Quantum Computers: A Quantum Neural Network Approach** [[paper](https://arxiv.org/abs/2604.19832)]
- [2026] **Optimizing ground state preparation protocols with autoresearch** [[paper](https://arxiv.org/abs/2604.25610)]
- [2026] **SPATE: Spiking-Phase Adaptive Temporal Encoding for Quantum Machine Learning** [[paper](https://arxiv.org/abs/2604.11022)]
- [2026] **Hardware-Aware Quantum Support Vector Machines** [[paper](https://arxiv.org/abs/2604.07856)]
- [2026] **A Novel Hierarchy of Quantum Kernel Networks on Smoothed Particle Hydrodynamics** [[paper](https://arxiv.org/abs/2604.24159)]
- [2026] **Regularization-Enhanced Hybrid Quantum-Classical Neural Network for Smart Grid Stability Classification** [[paper](https://doi.org/10.1109/dcas69364.2026.11544419)]
- [2026] **Reconstructing Particle Decay Trees with Quantum Graph Neural Networks in High Energy Physics** *Journal of Physics Conference Series* [[paper](https://doi.org/10.1088/1742-6596/3206/1/012091)]
- [2026] **Bridging Realms: Artificial Intelligence Integrates Omics, Generative Models, and Traditional Medicine for Anticancer Drug Innovation** *Journal of Pharmaceutical Analysis* [[paper](https://doi.org/10.1016/j.jpha.2026.101630)]
- [2026] **Approaches for strong electron correlation beyond DFT: Conventional and neural network quantum Monte Carlo** *Chinese Chemical Letters* [[paper](https://doi.org/10.1016/j.cclet.2026.112708)]
- [2026] **Predictive Intelligence to Early Intervention from Malaria: Comparative Study Between Quantum and Classical Machine Learning Paradigm** [[paper](https://doi.org/10.1109/qpain69676.2026.11545930)]
- [2026] **Molecular Excited States using Quantum Subspace Methods: Accuracy, Resource Reduction, and Error-Mitigated Hardware Implementation of q-sc-EOM** [[paper](https://arxiv.org/abs/2604.05380)]
- [2026] **Physics-informed Hamiltonian learning for large-scale optoelectronic property prediction** *Nature Communications* [[paper](https://doi.org/10.1038/s41467-026-70865-7)]
- [2026] **Decomposition–Quantum Hybrid Model for Accurate Reservoir Inflow Prediction: A Case Study on Khoda Afarin Dam** *Earth* [[paper](https://doi.org/10.3390/earth7020035)]
- [2026] **Optimized Quantum-Enhanced Neural Network Architectures** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/979-8-2600-0008-3.ch007)]
- [2026] **Design of a hybrid quantum machine learning architecture and analysis of quantum noise effects** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-42216-5)]
- [2026] **Introduction to the artificial neural network-based variational Monte Carlo method** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.15460)]
- [2026] **Hybrid Quantum Neural Networks for Early Diagnosis of Multiple Sclerosis using Explorable Quantum AI (VQE and QAOA)** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19057870)]
- [2026] **Quantum-Enhanced Graph Neural Networks for Complex Decision Making in Cognitive Autonomous Systems** [[paper](https://doi.org/10.22541/au.177368940.04003466/v1)]
- [2026] **Real Variance-Based Variational Quantum Eigensolver for Non-Hermitian Matrices** [[paper](https://arxiv.org/abs/2603.28892)]
- [2026] **Asymptotic Expansions for Neural Network Approximations of Quantum Channels** [[paper](https://arxiv.org/abs/2603.18033)]
- [2026] **Velocity Verlet-based optimization for variational quantum eigensolvers** [[paper](https://arxiv.org/abs/2603.09862)]
- [2026] **Distilling the knowledge with quantum neural networks** [[paper](https://arxiv.org/abs/2603.21586)]
- [2026] **Enhancing Variational Quantum Eigensolvers for SU(2) Lattice Gauge Theory via Systematic State Preparation** [[paper](https://arxiv.org/abs/2603.03799)]
- [2026] **Simulating Supersymmetric Quantum Mechanics Using Variational Quantum Algorithms** [[paper](https://arxiv.org/abs/2603.18749)]
- [2026] **Variational Quantum Eigensolver for the Analysis of High-Resolution NMR Spectra: Applications to AB and AB2 Spin Systems** [[paper](https://arxiv.org/abs/2603.05738)]
- [2026] **A unified quantum computing quantum Monte Carlo framework through structured state preparation** [[paper](https://arxiv.org/abs/2603.25582)]
- [2026] **Exponential Scaling Barriers for Variational Quantum Eigensolvers** [[paper](https://arxiv.org/abs/2603.13073)]
- [2026] **Emergent-Coupling-Based Ansatz Evaluated on a Superconducting Quantum Processor** [[paper](https://arxiv.org/abs/2603.28486)]
- [2026] **Finite-size resource scaling for learning quantum phase transitions with fidelity-based support vector machines** [[paper](https://arxiv.org/abs/2603.18211)]
- [2026] **Benchmarking Encoding Families in Quantum Neural Networks Under Fixed Circuit Area for Frequency Spectrum and Trainability** [[paper](https://arxiv.org/abs/2603.27671)]
- [2026] **Auto-regressive Neural Quantum State Sampling for Selected Configuration Interaction** [[paper](https://arxiv.org/abs/2603.24728)]
- [2026] **Auger Spectroscopy via Generative Quantum Eigensolver: A Quantum Approach to Molecular Excitations** [[paper](https://arxiv.org/abs/2603.12859)]
- [2026] **SpinGQE: A Generative Quantum Eigensolver for Spin Hamiltonians** [[paper](https://arxiv.org/abs/2603.24298)] [[code](https://github.com/Mindbeam-AI/SpinGQE)]
- [2026] **Towards Analyzing Formic Acid Using Classical and Quantum Methods** [[paper](https://arxiv.org/abs/2603.28343)]
- [2026] **Identification of quantum generative circuits with parallel quantum neural network** [[paper](https://arxiv.org/abs/2603.02834)]
- [2026] **Quantum Machine Learning Approaches for High-Dimensional Optimization Problems: A Survey** *Journal of Artificial Intelligence and Capsule Networks* [[paper](https://doi.org/10.36548/jaicn.2026.1.001)]
- [2026] **Training the parametric interactions in an analog bosonic quantum neural network with Fock basis measurement** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-45038-7)]
- [2026] **Potential Analysis of Quantum Machine Learning (QML) for Fraud Detection at FI-TS** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19474867)]
- [2026] **Variational Quantum Circuits for Pesticide Environmental Fate Prediction: A Comparative Study with Classical Machine Learning on the EU SPIN Database** *ChemRxiv* [[paper](https://doi.org/10.26434/chemrxiv.15000799/v2)]
- [2026] **$σ$-VQE: Excited-state preparation of quantum many-body scars with shallow circuits** [[paper](https://arxiv.org/abs/2602.20881)]
- [2026] **Spectral Phase Encoding for Quantum Kernel Methods** [[paper](https://arxiv.org/abs/2602.19644)]
- [2026] **Reinforcement Learning for Path Integrals in Quantum Statistical Physics** [[paper](https://arxiv.org/abs/2602.16176)]
- [2026] **Comparing Classical and Quantum Variational Classifiers on the XOR Problem** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2602.24220)]
- [2026] **Stochastic Neural Networks for Quantum Devices** [[paper](https://arxiv.org/abs/2602.22241)]

##### 2025

- [2025] **Parallel Multi-Circuit Quantum Feature Fusion in Hybrid Quantum-Classical Convolutional Neural Networks for Breast Tumor Classification** [[paper](https://arxiv.org/abs/2512.02066)]

##### 2024

- [2024] **Polynomially efficient quantum enabled variational Monte Carlo for training neural-network quantum states for physico-chemical applications** *npj Quantum Information* [[paper](https://arxiv.org/abs/2412.12398)]
- [2024] **A brief review of quantum machine learning techniques for financial services** *Machine Learning Science and Technology* [[paper](https://arxiv.org/abs/2407.12618)]

[⬆ Back to top](#paper-list)

#### Application

##### 2026

- [2026] **vmc_torch: Flexible Variational Monte Carlo for Quantum Many-Body Systems with PyTorch** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21798762)]
- [2026] **Dissipative Tensor Rotation Networks: A Classical Architecture for Parameter-Efficient Machine Learning and Strongly-Correlated Quantum Chemistry** *Open MIND* [[paper](https://github.com/dxg197/dtrn-structured-qc/tree/v1.00)]
- [2026] **Generative quantum machine learning for particle physics** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18877708)]

##### 2025

- [2025] **Application of quantum machine learning using variational quantum classifier in accelerator physics** *Nuclear Science and Techniques* [[paper](https://arxiv.org/abs/2506.06662)]

[⬆ Back to top](#paper-list)

#### Systems & Technology

##### 2026

- [2026] **Fault-tolerant quantum neural networks suppressing barren plateaus via localised cost functions and shallow parametrised architectures** *Pramana* [[paper](https://doi.org/10.1007/s12043-025-03097-x)]

[⬆ Back to top](#paper-list)

#### Evaluation & Benchmarks

##### 2026

- [2026] **Stock Prediction and Trading from OHLCV Data: A Quantum- Enhanced Learning-Based Comparison** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9653068/v1)]
- [2026] **Comparing quantum and classical machine learning for radar-based drone classification: a like-for-like benchmark on noisy data** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-8437365/v1)]

[⬆ Back to top](#paper-list)

#### Reviews & Surveys

##### 2016

- [2016] **Quantum Machine Learning** *Nature 549, 195-202 (2017)* [[paper](https://arxiv.org/abs/1611.09347)]

[⬆ Back to top](#paper-list)

### Quantum Cryptography & Communication

#### Theory

##### 2026

- [2026] **From key distribution to direct transmission: a comprehensive review of quantum image security via QKD and QSDC** *Frontiers in Physics* [[paper](https://doi.org/10.3389/fphy.2026.1878327)]
- [2026] **Quantum Communication, Networks, and Secure Information Processing in a Three-Axiom Global-Realist Framework** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21845047)]
- [2026] **Cross-Layer Security and Responsive Evaluation Architectures for Quantum Resistance in Connected Vehicles** *RIT Scholar Works (Rochester Institute of Technology)* [[paper](https://repository.rit.edu/theses/12750)]
- [2026] **AI Driven Cyber Security Framework for Next Generation Optical Communication Networks** *International Journal of Computer Information Systems and Industrial Management Applications* [[paper](https://doi.org/10.70917/ijcisim-2026-4940)]
- [2026] **Diversity in Coded TE-QKD Channels: Achieving Infinite Diversity out of Finite System Resources** [[paper](https://arxiv.org/abs/2608.05432)]
- [2026] **Exponential quantum advantage for learning signals with a single qubit** [[paper](https://arxiv.org/abs/2608.13521)]
- [2026] **Entanglement assisted quantum $(r,δ)$-locally recoverable codes** [[paper](https://arxiv.org/abs/2608.17118)]
- [2026] **A Lower Bound Framework for Quantum Functional Estimation** [[paper](https://arxiv.org/abs/2608.02600)]
- [2026] **Unifying quantum measurement constructions via a relative-entropy minimum change principle** [[paper](https://arxiv.org/abs/2608.04055)]
- [2026] **Nearly Sample-Optimal Estimators for Quantum Rényi and Tsallis Entropies** [[paper](https://arxiv.org/abs/2608.18070)]
- [2026] **Fault-Tolerant Quantum Computation with Adversarial Errors** [[paper](https://arxiv.org/abs/2608.16857)]
- [2026] **The pseudo-quantum representation of finite reversible Markov chains** [[paper](https://arxiv.org/abs/2608.01253)]
- [2026] **Geodesic Quantum $f$-Divergences** [[paper](https://arxiv.org/abs/2608.15833)]
- [2026] **Quantum Cryptography – Principles, Protocols, and Future Directions: A Review** *Journal of Multiscale Materials Informatics* [[paper](https://doi.org/10.62411/jimat.v3i1.15959)]
- [2026] **Partially device-independent quantum cryptography in asymmetric networks** *Physical Review Research* [[paper](https://doi.org/10.1103/53w8-6v5z)]
- [2026] **Security of binary-modulated optical key distribution against quantum-enhanced coherent eavesdropping** *New Journal of Physics* [[paper](https://doi.org/10.1088/1367-2630/ae8a75)]
- [2026] **Security of consumer electronics on Hybrid Model for Enhancement of RSA Using Quantum Key Distribution** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9363936/v1)]
- [2026] **Role of Quantum Key Distribution System against Various Threats in Digital Era: A Review** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21559794)]
- [2026] **The Collapse of Absolute Security: Exposing the Fundamental Vulnerability of Quantum Cryptography via Non-Demolition Measurement** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21700277)]
- [2026] **Lightweight Anonymous Group Authentication and Quantum-Cloud Key Distribution Based on PUF for Classical Network Environments** *Sensors* [[paper](https://doi.org/10.3390/s26154840)]
- [2026] **Quantum-safe DualRing with shorter signature and public key** *International Journal of Information Security* [[paper](https://doi.org/10.1007/s10207-026-01273-7)]
- [2026] **A Resilient and Decentralized System Based on Blockchain and Quantum-Secure Communication for Cyber and Strategic Diplomacy** *Systems* [[paper](https://doi.org/10.3390/systems14070755)]
- [2026] **Quantum Computing for Secure and Scalable Metaverse Communications** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/979-8-3373-3857-6.ch008)]
- [2026] **Quantum Algorithmic Threats and Countermeasures in Cloud and IoT Security** [[paper](https://doi.org/10.1201/9781003646068-11)]
- [2026] **Advances and Perspectives in Quantum Technologies: from Theoretical Foundations to Operational Frontiers** *Synergistic Manifolds eBooks* [[paper](https://doi.org/10.46337/qites.m260728)]
- [2026] **Lattice-Induced Key Exchange with Optimized Polynomial Sampling** *Journal of Intelligent Decision Making and Information Science* [[paper](https://doi.org/10.59543/jidmis.v3.926)]
- [2026] **Hybrid Quantum–Classical Anomaly Detection for 5G Roaming Signalling with QKD/QSDC Support** *Future Internet* [[paper](https://doi.org/10.3390/fi18080396)]
- [2026] **Evaluating DV/CV-QKD Architectures for SAFE Long-Term Secure Storage: A Risk Model and ILP-Based Cost Optimization Approach** [[paper](https://arxiv.org/abs/2607.19010)]
- [2026] **Secret Key Rate Analysis of Distribution Matching Algorithms for Discrete-Modulated CV-QKD** [[paper](https://arxiv.org/abs/2607.06783)]
- [2026] **Fixed Point Exploration For CV-QKD IR QC-MET-LDPC Toward Hardware Implementation** [[paper](https://arxiv.org/abs/2607.17960)]
- [2026] **Balancing Expressivity and Learnability in Quantum Kernel Bandit Optimization** [[paper](https://arxiv.org/abs/2607.01080)]
- [2026] **Perturbation Analysis of Maximal Quantum Leakage** [[paper](https://arxiv.org/abs/2607.14469)]
- [2026] **Communication Advantages from Quantum Dense Network Coding** [[paper](https://arxiv.org/abs/2607.08133)]
- [2026] **Constraints on recovering quantum information after erasure** [[paper](https://arxiv.org/abs/2607.17319)]
- [2026] **An Information-Theoretic Principle for Optimal Quantum Encoding: Tight Frames and Equiangular Ensembles** [[paper](https://arxiv.org/abs/2607.01564)]
- [2026] **Lossless Address Coding for Quantum Networks** [[paper](https://arxiv.org/abs/2607.23510)]
- [2026] **Hockey stick $f$-divergences** [[paper](https://arxiv.org/abs/2607.08760)]
- [2026] **Towards Minimax Estimation of High-Order Functionals by Quantum Arguments** [[paper](https://arxiv.org/abs/2607.07540)]
- [2026] **Differentially private quantum sensor networks** [[paper](https://arxiv.org/abs/2607.06521)]
- [2026] **Sample complexity of quantum resource testing via one-shot quantum blurring** [[paper](https://arxiv.org/abs/2607.24712)]
- [2026] **On estimating operator norm distance, with optimal trace distance estimation when one state is pure** [[paper](https://arxiv.org/abs/2607.03905)]
- [2026] **Keyless Covert Communication Over Quantum MACs with General Message Sets** [[paper](https://arxiv.org/abs/2607.08898)]
- [2026] **Multivariate Cryptography-Based Anonymous Certificate Scheme** [[paper](https://arxiv.org/abs/2607.13554)]
- [2026] **Four classes of few-weight self-orthogonal codes and their applications for LCD codes and quantum codes** [[paper](https://arxiv.org/abs/2607.07181)]
- [2026] **LDGM-Based Quantum Codes for Fault-Tolerant Quantum Computation** [[paper](https://arxiv.org/abs/2607.15159)]
- [2026] **Quantum key distribution in next-generation networks: a survey of space-based, aerial, and SDN-enabled frameworks for secure communication** *Quantum Information Processing* [[paper](https://doi.org/10.1007/s11128-026-05216-y)]
- [2026] **A photonic integrated long-distance quantum communication network** *Nature Photonics* [[paper](https://doi.org/10.1038/s41566-026-01944-w)]
- [2026] **A Quantum-Enhanced Key Agreement and Signature Protocol for Securing Transportation Cyber-Physical Systems** *IEEE Transactions on Intelligent Transportation Systems* [[paper](https://doi.org/10.1109/tits.2026.3678384)]
- [2026] **Quantum Key Distribution Protocols** [[paper](https://doi.org/10.1201/9781003641650-7)]
- [2026] **A Review on Fundamental Principles of Quantum Cryptography** *River Publishers eBooks* [[paper](https://doi.org/10.1201/9788743809326-12)]
- [2026] **Satellite-Based Quantum Communication: Performance Evaluation of Discrete-Variable Quantum Key Distribution Protocols** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.09217)]
- [2026] **Higher-Dimensional Quantum Cryptography for Maritime Infrastructures** *elib (German Aerospace Center)* [[paper](https://doi.org/10.5281/zenodo.20810271>.)]
- [2026] **AI-Driven Threat Detection and Response Using Quantum Cryptography** *Open MIND* [[paper](https://www.ijert.org/ai-driven-threat-detection-and-response-using-quantum-cryptography)]
- [2026] **A COMPREHENSIVE REVIEW OF QUANTUM CRYPTOGRAPHY: PRINCIPLES, PROTOCOLS, AND PRACTICAL CHALLENGES** [[paper](https://doi.org/10.58532/nbennurissdb3p3c1)]
- [2026] **A Survey on AI-Driven Threat Detection in Quantum Key Distribution Systems with Automated Response Mechanisms** *Open MIND* [[paper](https://www.ijert.org/a-survey-on-ai-driven-threat-detection-in-quantum-key-distribution-systems-with-automated-response-mechanisms)]
- [2026] **Triple-layer quantum defense: Quantum communication, sensing, and ML detection for power grid AGC security** *Quantum Machine Intelligence* [[paper](https://doi.org/10.1007/s42484-026-00400-w)]
- [2026] **QUEST: A Quantum Key Distribution Protocol Employing Eight-State Time-Bin Modulation and Homodyne-Heterodyne Hybridization** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202606.1876.v1)]
- [2026] **A Secure Group Key Distribution Scheme for Classical Networks in IoT Environments** *IEEE Internet of Things Journal* [[paper](https://doi.org/10.1109/jiot.2026.3674128)]
- [2026] **Certification of Network Quantum Sensing** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.10700)]
- [2026] **Multidimensional Reconciliation in Continuous-Variable QKD: Review, Coding Schemes, and Open Source Simulation** [[paper](https://arxiv.org/abs/2606.02323)]
- [2026] **Ultra-Low-Rate Information Reconciliation: Repetition Coding or Dedicated Codes?** [[paper](https://arxiv.org/abs/2606.23726)]
- [2026] **An Effective Pauli-Channel Model for Passive-User Loop-Back QKD** [[paper](https://arxiv.org/abs/2606.04247)]
- [2026] **From Bits to Mixed-Radix Keys: Horner Decomposition, Uniform Sampling, and the Information-Theoretic QKD Interface of the MR-OTP** [[paper](https://arxiv.org/abs/2606.18526)]
- [2026] **Quantum conditional mutual information and channel capacity** [[paper](https://arxiv.org/abs/2606.25264)]
- [2026] **Quantum Hierarchical Locally Recoverable Codes** [[paper](https://arxiv.org/abs/2606.06736)]
- [2026] **Quantum Time Lower Bounds by Permutation Invariance** [[paper](https://arxiv.org/abs/2606.05099)]
- [2026] **Quantum group codes for non-Clifford logic: enhanced decoding, addressability and parallelizability** [[paper](https://arxiv.org/abs/2606.27211)]
- [2026] **Quantum Simultaneous Information and Power Transfer: Capacity-Power Trade-offs in Discrete and Continuous Channels** [[paper](https://arxiv.org/abs/2606.00406)]
- [2026] **A Quantum Method of Types** [[paper](https://arxiv.org/abs/2606.27442)]
- [2026] **Multiple Quantum Hypothesis Testing: One-Shot Pairwise Bounds and Sharp Asymptotics** [[paper](https://arxiv.org/abs/2606.06246)]
- [2026] **QEC and EAQEC Codes from Hermitian Sums and Hulls of Cyclic Codes over $\mathbb{F}_2 \times (\mathbb{F}_2+v\mathbb{F}_2)$** [[paper](https://arxiv.org/abs/2606.02137)]
- [2026] **Unlocking Exponential and Unbounded Robust Gains in Shannon Capacity of Classical Multiple Access Channels with Causal CSIT via Quantum Entanglement Assistance** [[paper](https://arxiv.org/abs/2606.05412)]
- [2026] **Handbook of Error-Correcting Codes** [[paper](https://arxiv.org/abs/2606.11484)]
- [2026] **An Explicit Scott-Type Bound for Absolutely Maximally Entangled States with Arbitrary Defect** [[paper](https://arxiv.org/abs/2606.01943)]
- [2026] **Digital signature schemes based on code equivalence and syndrome decoding from restricted errors** [[paper](https://arxiv.org/abs/2606.31601)]
- [2026] **Constructions of Quantum $(r,δ)$-LRCs from cyclic codes** [[paper](https://arxiv.org/abs/2606.09522)]
- [2026] **Estimating Fidelity to a Reference Quantum State** [[paper](https://arxiv.org/abs/2606.26034)]
- [2026] **Quantum uniformity norms are pullbacks of matrix-valued uniformity norms** [[paper](https://arxiv.org/abs/2606.16862)]
- [2026] **Asymptotic Compression of Interactive Quantum Communication using Type-Constrained de Finetti Reduction** [[paper](https://arxiv.org/abs/2606.24746)]
- [2026] **Advancing Secure Communication in the Quantum Era through the Integration of Artificial Intelligence and Quantum Cryptographic Techniques** *International Journal of Latest Technology in Engineering Management & Applied Science* [[paper](https://doi.org/10.51583/ijltemas.2026.150500034)]
- [2026] **Key parameters of single photon receivers and sources for fi ber-optic quantum cryptography systems: parameter analysis and measurement methods** *Izmeritel`naya Tekhnika* [[paper](https://doi.org/10.32446/0368-1025it.2026-2-58-70)]
- [2026] **Q-IoTGuard: Lightweight Quantum Cryptographic Protocols for Resource-Constrained IoT Devices** [[paper](https://doi.org/10.1109/icicv68925.2026.11554871)]
- [2026] **Quantum Key Distribution (QKD) Enabled Secure Model Update Exchange in Federated Learning** *International Research Journal of Multidisciplinary Technovation* [[paper](https://doi.org/10.54392/irjmt26326)]
- [2026] **Quantum Enhanced Secure Communication Integrating Quantum Entanglement Based Secure Channels with XOR Based Encryption for Resilient Data Exchange** [[paper](https://doi.org/10.1109/icsscna68616.2026.11546978)]
- [2026] **ZeroTrustEdu: A Lightweight Post-Quantum Cryptography Framework with Adaptive Trust Scoring for Secure Cloud-IoT E-Learning Platforms** *Electronics* [[paper](https://doi.org/10.3390/electronics15102132)]
- [2026] **Toward Machine-Checked Post-Quantum Cryptography:Formal Verification of Digital Signature Schemes and Key Encapsulation Mechanisms** *TU/e Research Portal* [[paper](https://research.tue.nl/en/publications/f7469ea1-3786-483c-b71d-6622aaaa8fc7)]
- [2026] **Quantum anti-eavesdropping strategies: phase modulation in secure quantum communications** *Quantum Information Processing* [[paper](https://doi.org/10.1007/s11128-026-05212-2)]
- [2026] **Unveiling the Quantum Internet: Potentials, Challenges, and Security Issues** *Journal of The Institution of Engineers (India) Series B* [[paper](https://doi.org/10.1007/s40031-026-01336-2)]
- [2026] **"Code for the paper titled : Performance Analysis of Hybrid Digital--Quantum Satellite Links"** *IEEE DataPort* [[paper](https://doi.org/10.21227/d6js-h402)]
- [2026] **A Lightweight Double-Ring Hybrid Sparse NTRU (DRH-SNTRU) Scheme for Secure and Real-Time Communication in the Internet of Vehicles (IoV)** *Computers* [[paper](https://doi.org/10.3390/computers15050328)]
- [2026] **Quantum Meets Statistical-Physical Secrecy: A Novel Hybrid Key Distribution Architecture** [[paper](https://arxiv.org/abs/2605.15247)]
- [2026] **Selective Placement of Hollow-Core Fibers for QKD and Classical Communication Coexistence** [[paper](https://arxiv.org/abs/2605.10724)]
- [2026] **Universal quantum resource distillation via composite generalised quantum Stein's lemma** [[paper](https://arxiv.org/abs/2605.15174)]
- [2026] **Exponential speedups in fault-tolerant processing of quantum experiments** [[paper](https://arxiv.org/abs/2605.02057)]
- [2026] **Construction of Quantum Rank-Metric Codes Using Hermitian Orthogonality** [[paper](https://arxiv.org/abs/2605.02571)]
- [2026] **Optimal quantum locally differentially private mechanisms in the high-privacy regime** [[paper](https://arxiv.org/abs/2605.27278)]
- [2026] **List-Decodable Folded Quantum Hermitian Codes** [[paper](https://arxiv.org/abs/2605.10534)]
- [2026] **Enhanced quantum capacity thresholds from symmetry** [[paper](https://arxiv.org/abs/2605.09138)]
- [2026] **Self-Orthogonal Twisted Generalized Reed-Solomon Codes and Their Application to Quantum Error-Correcting Codes** [[paper](https://arxiv.org/abs/2605.23460)]
- [2026] **Optimal Error Exponents for Composite Sequential Quantum Hypothesis Testing** [[paper](https://arxiv.org/abs/2605.04915)]
- [2026] **A Decoding Algorithm for Composite Errors Consisting of Deletions and Insertions in Quantum Deletion-Correcting Codes Based on Quantum Reed-Solomon Codes** [[paper](https://arxiv.org/abs/2605.11510)]
- [2026] **Affine Subcode Ensemble Decoding for Degeneracy-Aware Quantum Error Correction** [[paper](https://arxiv.org/abs/2605.06547)]
- [2026] **Precision and Privacy in Distributed Quantum Sensing: A Quantum Fisher Information Duality** [[paper](https://arxiv.org/abs/2605.20765)]
- [2026] **Tight Contraction Rates for Primitive Channels under Quantum $f$-Divergences** [[paper](https://arxiv.org/abs/2605.06452)]
- [2026] **Quantum Key Distribution in the Post-Quantum Era: Technologies and Deployment Perspectives** [[paper](https://doi.org/10.1109/icecco67619.2026.11488792)]
- [2026] **Field-trial quantum key distribution with qubit-based frame synchronization** *Optics Express* [[paper](https://doi.org/10.1364/oe.593410)]
- [2026] **Continuous Key Refreshment for Hybrid Quantum Cryptography with BB84 and Post Quantum Signatures** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9215050/v1)]
- [2026] **INTEGRATION OF QUANTUM KEY DISTRIBUTION INTO NEXT-GENERATION TELECOM SYSTEMS** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19450362)]
- [2026] **Quantum Computing in Secure Communication: Challenges, Techniques, and Future Directions** *International Journal For Multidisciplinary Research* [[paper](https://doi.org/10.36948/ijfmr.2026.v08i02.73550)]
- [2026] **Communication Complexity of Lattice-Based Cryptographic Protocols: First Exact Bounds for LWE-CC and a New Multiparty Problem from Quorum Key Recovery** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19609633)]
- [2026] **Design of AI-Based Key Distribution and Authentication Protocols Resistant to Quantum Attacks for Next-Generation Cryptosystems** *Ingegneria Sismica* [[paper](https://doi.org/10.65102/is2026750)]
- [2026] **Quantum Key Distribution in Optical Fiber and FreeSpace Networks: Protocols, Security Analysis, Implementation Challenges, and Emerging Directions** *International Journal of Novel Research and Development* [[paper](https://doi.org/10.56975/ijnrd.v11i4.322912)]
- [2026] **Quantum-IoT Security: Advances, Challenges, and Future Directions** *Journal of Hardware and Systems Security* [[paper](https://doi.org/10.1007/s41635-026-00179-z)]
- [2026] **"A Comprehensive 3D Visual Compendium of India's National Quantum Mission: From 1,000-km Fiber Networks and Free-Space Entanglement to QKD Protocols, Bloch Sphere Representation, Startup Ecosystems, and Future Roadmaps for Quantum-Safe Communication Infrastructure"** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19554596)]
- [2026] **V2V-QKD: Simulation and Comparative Analysis of BB84 and SARG04 Protocols for Secure Vehicular Communication** *ResearchSpace (University of Auckland)* [[paper](https://hdl.handle.net/2292/75269)]
- [2026] **A multigraph approach to confusability in quantum channels** [[paper](https://arxiv.org/abs/2604.06072)]
- [2026] **Quantum Anonymous Secret Sharing with Permutation Invariant Codes** [[paper](https://arxiv.org/abs/2604.27284)]
- [2026] **Exponential quantum advantage in processing massive classical data** [[paper](https://arxiv.org/abs/2604.07639)]
- [2026] **Impure codes exceeding the pure bounds for quantum local recovery** [[paper](https://arxiv.org/abs/2604.03569)]
- [2026] **Quantum Relative-alpha-Entropies: A Structural and Geometric Perspective** [[paper](https://arxiv.org/abs/2604.06908)]
- [2026] **Conditional channel entropy sets fundamental limits on thermodynamic quantum information processing** [[paper](https://arxiv.org/abs/2604.01217)]
- [2026] **Quantum channel tomography: optimal bounds and a Heisenberg-to-classical phase transition** [[paper](https://arxiv.org/abs/2604.17369)]
- [2026] **Generalized Roth--Lempel Codes: NMDS Characterization, Hermitian Self-Orthogonality, and Quantum Constructions** [[paper](https://arxiv.org/abs/2604.11350)]
- [2026] **Partial majorization and Schur concave functions on the sets of quantum and classical states** [[paper](https://arxiv.org/abs/2604.13033)]
- [2026] **Quantum Prediction of Transport Dynamics in Discretized State Spaces** [[paper](https://arxiv.org/abs/2604.24161)]
- [2026] **The mixed-dimensional quantum MacWilliams identity: bounds for codes and absolutely maximally entangled states in heterogeneous systems** [[paper](https://arxiv.org/abs/2604.25790)]
- [2026] **Accessible Quantum Correlations Under Complexity Constraints** [[paper](https://arxiv.org/abs/2604.15540)]
- [2026] **Conclusive Identification Via Noisy Classical Channel: Superactivation and Quantum Advantage** [[paper](https://arxiv.org/abs/2604.00089)]
- [2026] **Towards Ultra-High-Rate Quantum Error Correction with Reconfigurable Atom Arrays** [[paper](https://arxiv.org/abs/2604.16209)]
- [2026] **Quantum Algebraic Diversity: Single-Copy Density Matrix Estimation via Group-Structured Measurements** [[paper](https://arxiv.org/abs/2604.03725)]
- [2026] **Quantum Message Passing for Factor Graphs over Finite Abelian Groups** [[paper](https://arxiv.org/abs/2604.12186)]
- [2026] **Optimal, Qubit-Efficient Quantum Vehicle Routing via Colored-Permutations** [[paper](https://arxiv.org/abs/2604.04570)]
- [2026] **Stabilizers for Compiling Logical Circuits under Hardware Constraints** [[paper](https://arxiv.org/abs/2604.25042)]
- [2026] **Reverse-encoded quantum key distribution with Gaussian-modulated coherent states** *Science China Information Sciences* [[paper](https://doi.org/10.1007/s11432-025-4575-5)]
- [2026] **Quantum-Secured AI-Driven Drone Logistics for Real-Time Healthcare Delivery** *Arabian Journal for Science and Engineering* [[paper](https://doi.org/10.1007/s13369-026-11104-5)]
- [2026] **Enhancing Cybersecurity in IoT-Integrated Smart Grids Using Federated Learning and Quantum Encryption Techniques** [[paper](https://doi.org/10.1109/i3ctcon68242.2026.11508099)]
- [2026] **A Web-Based Quantum Key Distribution Simulator with Adaptive Post-Quantum Cryptography Fallback** [[paper](https://doi.org/10.1109/icoeca68095.2026.11485616)]
- [2026] **Quantum cryptography for secure messaging** *World Journal of Advanced Research and Reviews* [[paper](https://doi.org/10.30574/wjarr.2026.29.3.0716)]
- [2026] **Enhanced Quantum Cryptography with Single Particle State Rotation** *SN Computer Science* [[paper](https://doi.org/10.1007/s42979-026-04831-x)]
- [2026] **Decoy State Method: Key to Practical Quantum Cryptography** *Physics and High Technology* [[paper](https://doi.org/10.3938/phit.35.007)]
- [2026] **Quantum Cryptography and Quantum-Enhanced Cybersecurity: A Systematic Review of Issues, Technologies, Algorithms, and Applications** *Open MIND* [[paper](https://doi.org/10.25397/yk8z-s124)]
- [2026] **Quantum-Powered Cryptographic Enhancements through Hybrid Approaches in Network Security** [[paper](https://doi.org/10.1201/9781003674818-25)]
- [2026] **A Quantum Assisted Secure Data Transmission Architecture for Hybrid Classical Quantum Communication Systems** [[paper](https://doi.org/10.1109/icesic67389.2026.11496436)]
- [2026] **Quantum Key Distribution Based Network Integrity Mechanism for Secure Web Chatting with Attack Mitigation** *International Journal of Engineering Research and Science & Technology* [[paper](https://doi.org/10.5281/zenodo.19307405)]
- [2026] **An Intelligent Quantum-Safe Framework for Secure Communication and Financial Prediction** [[paper](https://doi.org/10.1109/iciss67859.2026.11453584)]
- [2026] **Trusted Communication in the Internet of Things: Applications of Blockchain and Quantum Technology** *Reslaj Religion Education Social Laa Roiba Journal* [[paper](https://doi.org/10.47467/reslaj.v8i3.10819)]
- [2026] **A Quantum Leap in Cybersecurity: Novel Paradigms for Safe Digital Communication** [[paper](https://doi.org/10.1109/datascimi67380.2026.11524001)]
- [2026] **Practical Guide to Using a Quantum Computer (Based on Materials from the International Quantum Center at CERN, Switzerland) # 2** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18861567)]
- [2026] **Semi-quantum blockchain** *Discover Computing* [[paper](https://doi.org/10.1007/s10791-026-09990-2)]
- [2026] **Theory and Methodology of Information Security: Quantum Algorithms and Bell States** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18865547)]
- [2026] **Quantum-Enabled Security Framework for 6G Communications Based on QKD-OFDM Integration** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.22015522)]
- [2026] **Integrating Quantum Technology with Wireless NoC: A Review of Architectures, Protocols, and Future Directions** *Radio Science* [[paper](https://doi.org/10.1029/2025rs008411)]
- [2026] **Send the Key in Cleartext: Halving Key Consumption while Preserving Unconditional Security in QKD Authentication** [[paper](https://arxiv.org/abs/2603.25496)]
- [2026] **Quantum Key Distribution Secured Federated Learning for Channel Estimation and Radar Spectrum Sensing in 6G Networks** [[paper](https://arxiv.org/abs/2603.15649)]
- [2026] **Secret Key Rate Analysis of RIS-Assisted THz MIMO CV-QKD Systems under Access-Constrained Eavesdropping** [[paper](https://arxiv.org/abs/2603.28252)]
- [2026] **SDP bounds on quantum codes: rational certificates** [[paper](https://arxiv.org/abs/2603.19901)]
- [2026] **Space-sharing and Singleton Bounds for Entanglement-assisted Classical Coding** [[paper](https://arxiv.org/abs/2603.08563)]
- [2026] **A Note on the Equivalence Between Zero-knowledge and Quantum CSS Codes** [[paper](https://arxiv.org/abs/2603.08941)]
- [2026] **Learning from Radio using Variational Quantum RF Sensing** [[paper](https://arxiv.org/abs/2603.10239)]
- [2026] **Communication-Efficient Quantum Federated Learning over Large-Scale Wireless Networks** [[paper](https://arxiv.org/abs/2603.01222)]
- [2026] **Efficient Soft-Output Guessing for Enhanced Quantum Tanner Code Decoding** [[paper](https://arxiv.org/abs/2603.18318)]
- [2026] **Quantum Entanglement Assistance Improves the Capacity and Activates the Zero-Error Capacity of Classical Channels with Causal CSIT** [[paper](https://arxiv.org/abs/2603.20416)]
- [2026] **Improved Decoding of Quantum Tanner Codes Using Generalized Check Nodes** [[paper](https://arxiv.org/abs/2603.05486)]

##### 2025

- [2025] **Combined Quantum and Post-Quantum Security Performance Under Finite Keys** [[paper](https://arxiv.org/abs/2512.04429)]

[⬆ Back to top](#paper-list)

#### Method

##### 2026

- [2026] **Quantum-Safe Email Client Using Simulated Quantum Key Distribution** [[paper](https://doi.org/10.4018/979-8-3373-9053-6.ch015)]
- [2026] **Single Photon Transmission, Quantum Key Distribution, Multimode Fiber and Higher Order Poincare Spheres** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202608.0188.v1)]
- [2026] **Europe's Post-Quantum Readiness 2026 An Empirical Assessment of the EU-27** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21782640)]
- [2026] **SARA: An LLM-Based Approach for Systematic Literature Review with a Use Case on Classical–Quantum Integration for Secure Communication** *Journal of Bioengineering, Technologies and Health* [[paper](https://doi.org/10.34178/jbth.v9i7.667)]
- [2026] **Modeling of blockchain technology-based hybrid secure communication system using autonomous artificial intelligence agents** [[paper](https://doi.org/10.1117/12.3121054)]
- [2026] **Comprehensive survey of global research trends, challenges, and comparative advances in quantum cryptography and post-quantum cryptographic algorithms** *Discover Artificial Intelligence* [[paper](https://doi.org/10.1007/s44163-026-01841-9)]
- [2026] **QuantumShield-IoT: A Quantum-Resilient Hybrid Framework for Secure Data Transmission Using Quantum Key Distribution, Lightweight Cryptography and Blockchain Technology** *International Journal of Innovative Science and Research Technology (IJISRT)* [[paper](https://doi.org/10.38124/ijisrt/26jul281)]
- [2026] **Quantum Key Distribution for Secure IoT Communication: Recent Advances, Challenges, and Future Perspectives** *IJARCCE* [[paper](https://doi.org/10.17148/ijarcce.2026.15724)]
- [2026] **Securing Swarm Robotics Communication Using Quantum** *Advances in computational intelligence and robotics book series* [[paper](https://doi.org/10.4018/979-8-3373-3857-6.ch012)]
- [2026] **Post-quantum cryptography for healthcare: securing medical data, connected devices, and digital health infrastructure** *Frontiers in Health Services* [[paper](https://doi.org/10.3389/frhs.2026.1901282)]
- [2026] **Simulating BB84 protocol with noise in quantum key distribution systems using IBM Qiskit** *Physica Scripta* [[paper](https://doi.org/10.1088/1402-4896/ae79e4)]
- [2026] **vishwaka-2419/pqc-qkd-migration-framework: As submitted to IET Quantum Communication (July 2026)** *Open MIND* [[paper](https://github.com/vishwaka-2419/pqc-qkd-migration-framework/tree/v1.0.0)]
- [2026] **Development of A BB84-Based Quantum Security System** *International Journal of Latest Technology in Engineering Management & Applied Science* [[paper](https://doi.org/10.51583/ijltemas.2026.150600059)]
- [2026] **Quantum Computing and Its Implications for Information Technology Security** *Iconic Research and Engineering Journals* [[paper](https://doi.org/10.64388/irev10i1-1720192)]
- [2026] **Post-Quantum Secure Software-Defined Networking for Cloud and Edge Computing** *International Journal for Research in Applied Science and Engineering Technology* [[paper](https://doi.org/10.22214/ijraset.2026.84156)]
- [2026] **Application of Quantum-AI Security in Intelligent Transportation** [[paper](https://doi.org/10.4018/979-8-3373-7488-8.ch010)]
- [2026] **Quantum-Secure Communication for Future Cyber-Physical and IoT Systems: A Systematic Review of Classical to Learning Approaches** *Computers* [[paper](https://doi.org/10.3390/computers15060389)]
- [2026] **Quantum-secure networks: A hybrid framework integrating post-quantum cryptography and quantum key distribution for ultra-resilient data transmission** *Computer Networks* [[paper](https://doi.org/10.1016/j.comnet.2026.112331)]
- [2026] **Quantum Key Distribution with Enhanced PQC Validation** *Informatica Economica* [[paper](https://doi.org/10.24818/issn14531305/30.2.2026.03)]
- [2026] **Layered Post-Quantum Cryptography: A Dual-Encryption Approach to Mitigate Quantum Threats** *International Journal of Creative and Open Research in Engineering and Management* [[paper](https://doi.org/10.55041/ijcope.v2i6.338)]
- [2026] **Secure Chat Application using Quantum Cryptography Simulation** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20577641)]
- [2026] **Quantum Phase Parameterized True Random Number Generation for Secure Communication** [[paper](https://doi.org/10.1201/9781003641650-9)]
- [2026] **On the Cryptographic Structure Required for Verifying Qubits** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2606.05527)]
- [2026] **SpaceTech, Edge AI, and Quantum Communication for Climate Monitoring and Global Policy Intelligence** [[paper](https://doi.org/10.62311/nesx/rb5j-978-81-688015-5-4)]
- [2026] **An Energy-Efficient AI-Assisted Quantum-Secure Communication Framework for Scalable and Reliable IoT Networks** *Journal of Wireless Networks and Communication Systems* [[paper](https://doi.org/10.32595/jwncs/v2i2.2026.28)]
- [2026] **Augmenting End-to-End Data Security Using Optimized NTRU Encryption with Quantum-Safe Key Exchange** *International Journal of Computer Networks And Applications* [[paper](https://doi.org/10.22247/ijcna/2026/28)]
- [2026] **A Hybrid Quantum-Post-Quantum Framework for Secure Data Encryption Using Adaptive Steganography** [[paper](https://doi.org/10.1109/iciics67880.2026.11483499)]
- [2026] **Quantum Information Science for Photonic Networks, Secure Satellites and Future Internet Architectures** [[paper](https://doi.org/10.62311/nesx/rb2j-978-81-688203-8-8)]
- [2026] **Quantum resistant software Defined-Networking IPsec, enabling ITS communication over IP networks on real telco infrastructures** *Computer Networks* [[paper](https://doi.org/10.1016/j.comnet.2026.112171)]
- [2026] **A framework for quantum-secure communications in cyber-physical control systems with experimental demonstration in a nuclear reactor** *Scientific Reports* [[paper](https://doi.org/10.1038/s41598-026-49514-y)]
- [2026] **Quantum-Resilient Cryptography and Safe Guarding Post Quantum Cryptographic Protocols Against Quantum Threats** [[paper](https://doi.org/10.1109/icpcsn68523.2026.11543578)]
- [2026] **Quantum-Resistant Cryptographic Protocols for Secure Communication in Cloud Computing Environments** *SN Computer Science* [[paper](https://doi.org/10.1007/s42979-026-05003-7)]
- [2026] **Quantum Computing and Communication for Intelligent Transportation System Networks: Exploring Qubit-based Innovations in Cryptography and Optimization Frontiers** *Artificial Intelligence for Transportation* [[paper](https://doi.org/10.1201/9781003648147-7)]
- [2026] **Enhancing Security in the Smart IoT Systems Using Post‐Quantum Cryptographic Block Cipher** [[paper](https://doi.org/10.1002/9781394347070.ch22)]
- [2026] **AQCTCS: An Adaptive Quantum–Classical Trust-Based Secure Communication System** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.20254920)]
- [2026] **UDMTL-QKD: An Ultra-Deep Multi-Task Learning Approach for Quantum Key Distribution Secured Multi-Bank Transactions in 6G Networks** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9601877/v1)]
- [2026] **Architecture of quantum networks for distributed computing and secure communications** *Computational nanotechnology* [[paper](https://doi.org/10.33693/2313-223x-2026-13-1-222-229)]
- [2026] **Quantum Protocol Architectures and Secure Control Frameworks For 7G+ Networks: Standards, Synchronization, Use Cases, and Challenges** *Advanced Quantum Technologies* [[paper](https://doi.org/10.1002/qute.202500844)]
- [2026] **Quantum Computing and IoT: Transforming Cybersecurity in the Defence Sector** [[paper](https://doi.org/10.1108/978-1-83549-198-020261005)]
- [2026] **Evaluating Quantum Key Protocols for Secure Hybrid Cryptography** [[paper](https://doi.org/10.1109/raeeucci67649.2026.11504879)]
- [2026] **A Quantum Blind Signature Integrated Hybrid Quantum Key Distribution Framework for Secure and Authenticated Quantum Communication** [[paper](https://doi.org/10.23919/indiacom70271.2026.11526451)]
- [2026] **Secure Quantum Communication Architecture** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19544844)]
- [2026] **State-of-the-Art in Quantum Key Distribution for Next-Generation Wireless Networks** *IETE Journal of Research* [[paper](https://doi.org/10.1080/03772063.2026.2637621)]
- [2026] **Quantum Key Distribution (QKD)- Based Cloud Security Model Integrated with Quantum Machine Learning(QML) for Threat Detection** [[paper](https://doi.org/10.1109/iccsp68173.2026.11539237)]
- [2026] **A Review : Enhancing Cybersecurity with Quantum Cryptography and Federated SMOTE-ADA Boost Framework for Detecting Credit Card Fraud** *Open MIND* [[paper](https://ijsrset.com/home/article/view/IJSRSET25122218)]
- [2026] **AN EFFICIENT AND LOW POWER SPAD BASED QUANTUM RANDOM NUMBER GENERATOR USING NLFSR FOR SECURE CRYPTOGRAPHIC APPLICATIONS** *ICTACT Journal on Microelectronics* [[paper](https://doi.org/10.21917/ijme.2026.0379)]
- [2026] **Advancing 6G Ultra-Low-Latency Communications with the Quantum Burst Protocol and Stateless, Quantum-Lite Encryption** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-9260723/v1)]
- [2026] **TeleQNet: Defense-Grade Messaging with Quantum Teleportation** [[paper](https://doi.org/10.1109/icaiss68683.2026.11525809)]
- [2026] **QSFedMA: Quantum‐Secured Authentication Protocol for Privacy‐Preserving Federated IoMT** *Software Practice and Experience* [[paper](https://doi.org/10.1002/spe.70071)]
- [2026] **Synchronized DNA sources for unconditionally secure cryptography** *HAL (Le Centre pour la Communication Scientifique Directe)* [[paper](https://arxiv.org/abs/2603.17149)]
- [2026] **BB84 a new hope enhanced QKD for secure email communication with additional quantum gates** *EPJ Quantum Technology* [[paper](https://doi.org/10.1140/epjqt/s40507-026-00493-z)]
- [2026] **Secure Quantum Communication: Simulation and Analysis of Quantum Key Distribution Protocols** *International Scientific Journal of Engineering and Management* [[paper](https://arxiv.org/abs/2603.16690)]
- [2026] **QUANTUM KEY DISTRIBUTION FOR ULTRA-SECURE WIRELESS COMMUNICATION** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19015487)]
- [2026] **Quantum Cryptography for 6G and Quantum Internet Infrastructure** [[paper](https://doi.org/10.1109/cine68769.2026.11503001)]
- [2026] **CrypTon: A Hybrid Quantum-Classical Framework Integrating BB84 Quantum Key Distribution with AES for Secure Communication** [[paper](https://doi.org/10.1109/nqcomp68334.2026.11497686)]
- [2026] **EAQKD: Entanglement-Based Authenticated Quantum Key Distribution** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.02375)]
- [2026] **Privacy-preserving cloud-based dermatological image processing for medical applications: a review** *Journal of Cloud Computing Advances Systems and Applications* [[paper](https://doi.org/10.1186/s13677-026-00886-6)]
- [2026] **IPsec based on Quantum Key Distribution: Adapting non-3GPP access to 5G Networks to the Quantum Era** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.24426)]
- [2026] **Power Network SCADA Quantum Communications: A Comparison of BB84, B92, E91, and SGS04 Quantum Key Distribution Protocols** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2603.01060)]
- [2026] **Security Analysis of the BB84 Quantum Key Distribution Protocol Using Qiskit** [[paper](https://doi.org/10.1109/icdcs68853.2026.11510985)]
- [2026] **Design & Development of a Quantum Antenna for Advanced Communication and Sensing Applications** *International Journal of Engineering & Extended Technologies Research* [[paper](https://doi.org/10.15662/ijeetr.2026.0802124)]
- [2026] **A Comparative Study between Three Encryption Systems in a Quantum Computer (BB84, B92, BBM92) in Free Space Communication** *Comprehensive Journal of Science* [[paper](https://doi.org/10.65405/qek9ap78)]
- [2026] **QUANTUM TECHNOLOGIES IN DEFENSE AND SECURITY** *Military strategy and technology* [[paper](https://doi.org/10.63978/3083-6476.2026.1.4.05)]
- [2026] **Quantum secure and resilient 5G network slicing** [[paper](https://doi.org/10.1201/9781003650201-64)]
- [2026] **Simulation and analysis of a QKD-PQC protocol for secure communication channel authentication** *Springer Link (Chiba Institute of Technology)* [[paper](https://www.epj-conferences.org/10.1051/epjconf/202636001002/pdf)]
- [2026] **A Quantum-Enhanced Secure Aggregation Framework for Federated Multi-Disease Prediction in IoMT Healthcare** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.19272162)]
- [2026] **Red Means Go: An Adversarial Approach to Robust and Accelerated Assurance in Hybrid Quantum-Classical Communications** *Open MIND* [[paper](https://www.etsi.org/events/2450-etsi-iqc-quantum-safe-cryptography-conference-2025)]
- [2026] **Enhancing Data Security in Satellite Communication Systems: Integrating Quantum Cryptography with CatBoost Machine Learning** *Information* [[paper](https://doi.org/10.3390/info17030220)]
- [2026] **Quantum Key Distribution** *Auerbach Publications eBooks* [[paper](https://doi.org/10.1201/9781003587835-10)]
- [2026] **Quantum Safe Cryptographic Frameworks for Securing National Digital Currencies and Economic Infrastructure** *Journal of Internet Services and Information Security* [[paper](https://doi.org/10.58346/jisis.2026.i1.014)]
- [2026] **A Practical Framework for Simulating the Integration of QKD in TLS Protocol Towards Quantum Secure Communication** [[paper](https://doi.org/10.1109/ncc68160.2026.11478911)]
- [2026] **Quantum-Secured Hybrid Communication System for Tactical Military Networks: Implementation and Performance Analysis of BB84 Protocol Based on Penny Lane** *한국통신학회논문지* [[paper](https://doi.org/10.7840/kics.2026.51.2.449)]
- [2026] **Increasing the secret key rates and point-to-multipoint extension for experimental coherent-one-way quantum key distribution protocol** *The European Physical Journal D* [[paper](https://arxiv.org/abs/2601.04543)]

##### 2025

- [2025] **Overview of Routing Approaches in Quantum Key Distribution Networks** *Lecture notes of the Institute for Computer Sciences, Social Informatics and Telecommunications Engineering* [[paper](https://arxiv.org/abs/2511.15465)]
- [2025] **Obfuscated Quantum and Post-Quantum Cryptography** [[paper](https://arxiv.org/abs/2508.07635)]
- [2025] **Secure multi-party biometric verification using QKD assisted quantum oblivious transfer** *Scientific Reports* [[paper](https://arxiv.org/abs/2501.05327)]

##### 2024

- [2024] **Single-photon advantage in quantum cryptography beyond QKD** *Nature Communications* [[paper](https://arxiv.org/abs/2412.14993)]

[⬆ Back to top](#paper-list)

#### Application

##### 2026

- [2026] **Quantum Coordination and Nonlocal Games: Theory and Applications** [[paper](https://arxiv.org/abs/2608.09540)]
- [2026] **Absorption-emission quantum repeater using diamond quantum memories** [[paper](https://arxiv.org/abs/2608.17470)]
- [2026] **Multiplexing of Continuous-Variable and Discrete-Variable Quantum Key Distribution Systems over Fibered and Free-Space Channels** [[paper](https://arxiv.org/abs/2608.19745)]
- [2026] **Heuristic Lookahead Distillation Protocol Search** [[paper](https://arxiv.org/abs/2608.13644)]
- [2026] **Experimental Quantum Key Distribution in an Indefinite Causal Order** [[paper](https://arxiv.org/abs/2608.13561)]
- [2026] **Secure Medical Data Transmission Using Quantum Key Distribution and Post-Quantum Cryptography in Real-World Fiber Networks** [[paper](https://arxiv.org/abs/2608.18869)]
- [2026] **On the Swapping Capacity of a Quantum Repeater** [[paper](https://arxiv.org/abs/2608.11429)]
- [2026] **Entanglement distribution and quantum storage of more than 8000 modes over a metropolitan network** [[paper](https://arxiv.org/abs/2608.13177)]
- [2026] **Co-transmission of classical data and continuous-variable entanglement over a single quantum channel** [[paper](https://arxiv.org/abs/2607.25179)]
- [2026] **Daylight quantum keyless private communication for free-space links** [[paper](https://arxiv.org/abs/2607.03527)]
- [2026] **GHZ-Equivalent State Distribution in Quantum Networks: Reducing Decoherence and Quantum Resource Consumption** [[paper](https://arxiv.org/abs/2607.17101)]
- [2026] **Quantum Teleportation toward the Quantum Internet: A Concise Review** [[paper](https://arxiv.org/abs/2607.25395)]
- [2026] **Construction of a Class of Communication-Efficient Quantum Secret Sharing Schemes** [[paper](https://arxiv.org/abs/2607.19891)]
- [2026] **Universal quantum cloning beyond noncontextual theory** [[paper](https://arxiv.org/abs/2607.05959)]
- [2026] **Quantum key distribution over a 2 km free-space channel with a high secure key rate** [[paper](https://arxiv.org/abs/2607.24118)]
- [2026] **Experimental Protocol Fingerprinting in Quantum Networks via Physical Layer Side Channel Analysis** [[paper](https://arxiv.org/abs/2607.24624)]
- [2026] **Spectral Attack on Continuous-Variable Quantum Key Distribution Systems** [[paper](https://arxiv.org/abs/2607.15668)]
- [2026] **GHz-rate all-fiber active polarization state analyzer for quantum protocols** [[paper](https://arxiv.org/abs/2607.09597)]
- [2026] **Device-independent Quantum Key Distribution in the commuting operator framework** [[paper](https://arxiv.org/abs/2607.03579)]
- [2026] **End-to-End Quantum Key Distribution Across Hybrid Fiber and Free-Space Links with All-Optical Encoding Conversion** [[paper](https://arxiv.org/abs/2607.12837)]
- [2026] **Entanglement Swapping with Integrated Narrowband Photon Sources for Quantum Repeaters** [[paper](https://arxiv.org/abs/2607.28184)]
- [2026] **Insecurity of Measurement-Device-Independent Quantum Key Distribution** [[paper](https://arxiv.org/abs/2607.01989)]
- [2026] **Influence of laser chirp and interferometer delay and imbalance on the performance of a time-bin BB84 quantum key distribution system** [[paper](https://arxiv.org/abs/2607.00600)]
- [2026] **When Routes Run Out: Adversarial Co-Learning and Explainable Robustness in Quantum Repeater Networks** [[paper](https://arxiv.org/abs/2607.09378)]
- [2026] **Discrete-modulated continuous-variable quantum key distribution with uncertainty principle** [[paper](https://arxiv.org/abs/2607.20840)]
- [2026] **No-Go Theorem for Gaussian Quantum Repeaters from Fractional Extendibility** [[paper](https://arxiv.org/abs/2606.05097)]
- [2026] **Quantum repeater segment with free-space coupled co-trapped ions using telecom photon interference** [[paper](https://arxiv.org/abs/2606.12313)]
- [2026] **Effective discrete-modulated continuous variable QKD under general attacks** [[paper](https://arxiv.org/abs/2606.20346)]
- [2026] **Quantum resonance based encryption protocol with quantum kicked top** [[paper](https://arxiv.org/abs/2606.01953)]
- [2026] **High-Rate and Resource-Efficient All-Photonic Quantum Repeater Architectures with 9 km Repeater Spacing** [[paper](https://arxiv.org/abs/2606.25314)]
- [2026] **Quantum Primitive for Output-Hiding Function Sharing** [[paper](https://arxiv.org/abs/2606.25080)]
- [2026] **Self-Sifting quantum key distribution** [[paper](https://arxiv.org/abs/2606.27299)]
- [2026] **Single-sideband-interference twin-field quantum key distribution without global phase locking** [[paper](https://arxiv.org/abs/2606.27792)]
- [2026] **Experimental Demonstration of Free-Space Unidimensional Continuous-Variable Quantum Key Distribution Under High Detector Noise** [[paper](https://arxiv.org/abs/2606.07206)]
- [2026] **Deployed trusted-node quantum key distribution over 300 km with a multi-core fiber access link** [[paper](https://arxiv.org/abs/2606.06107)]
- [2026] **Authentication in Quantum Networks** [[paper](https://arxiv.org/abs/2606.30636)]
- [2026] **Reconfigurable MDI-QKD and BB84 over 20 km optical channels via EOM-tailored weak coherent states** [[paper](https://arxiv.org/abs/2606.10306)]
- [2026] **Making Quantum Networks Work: Routing, Calibration, and Programmable Quantum Repeaters** [[paper](https://arxiv.org/abs/2606.22316)]
- [2026] **On-Demand Coherent Mapping of Telecom Optical States onto Erbium Hyperfine Spins** [[paper](https://arxiv.org/abs/2606.15009)]
- [2026] **Distributed Property Testing with (Quantum) Carrier Pigeons: Tight Bounds on State Certification** [[paper](https://arxiv.org/abs/2606.31753)]
- [2026] **Fractional graph expanders and network dynamics: spectral properties and diffusion with applications to quantum cryptography** *Quantum Information Processing* [[paper](https://doi.org/10.1007/s11128-026-05204-2)]
- [2026] **From Fundamental Dynamics to Applied Cryptography: Studies on the Quantum Speed Limit and Fully Passive Quantum Key Distribution** *arXiv (Cornell University)* [[paper](https://arxiv.org/abs/2605.17532)]
- [2026] **Emergent Operational Entanglement Graphs and Sub-Quadratic Authentication Scaling in Realistic E91 Quantum Networks** [[paper](https://arxiv.org/abs/2605.27434)]
- [2026] **Distribution of GHz sequential Time-bin Entanglement in a Metropolitan Fiber Network** [[paper](https://arxiv.org/abs/2605.13359)]
- [2026] **Dual wavelength source of entanglement for space quantum communication** [[paper](https://arxiv.org/abs/2605.22339)]
- [2026] **Photon Efficiency of High-Dimensional Quantum Key Distribution** [[paper](https://arxiv.org/abs/2605.21018)]
- [2026] **Performance Analysis of Underwater Quantum Key Distribution Protocols: BB84, SARG04, and BBM92** [[paper](https://arxiv.org/abs/2605.29513)]
- [2026] **CV-QKD over Turbulence Channels with Virtual Photon Subtraction and Quantum Multiple-Symbol Detection for Underwater Quantum Communications** [[paper](https://arxiv.org/abs/2605.23557)]
- [2026] **Analytical Model of Clock Drift in Quantum Key Distribution and a Simple Synchronization Algorithm** [[paper](https://arxiv.org/abs/2605.26705)]
- [2026] **Quantum communications in continuous variable systems** [[paper](https://arxiv.org/abs/2605.19602)]
- [2026] **Realistic Simulation of Quantum Repeater with Encoding and Classical Error Correction** [[paper](https://arxiv.org/abs/2605.06928)]
- [2026] **Chain rules for conditional entropies in quantum cryptography: limitations and improvements** [[paper](https://arxiv.org/abs/2605.29787)]
- [2026] **Entanglement cost in non-local quantum computation** [[paper](https://arxiv.org/abs/2605.02840)]
- [2026] **Discrete-phase-randomized mode-pairing quantum key distribution** [[paper](https://arxiv.org/abs/2605.14484)]
- [2026] **Photon Number Coherence of a Quantum Dot-Cavity System Excited Using the SUPER Scheme** [[paper](https://arxiv.org/abs/2605.02490)]
- [2026] **Single-Satellite Quantum Repeater Performance Analysis** [[paper](https://arxiv.org/abs/2604.16165)]
- [2026] **Loss-Tolerant Quantum Communication via Bosonic-GKP-Parity-Encoding** [[paper](https://arxiv.org/abs/2604.09002)]
- [2026] **PQC-Enhanced QKD Networks: A Layered Approach** [[paper](https://arxiv.org/abs/2604.05599)]
- [2026] **Gigahertz-rate thin-film lithium niobate receiver for time-bin quantum communication** [[paper](https://arxiv.org/abs/2604.16695)]
- [2026] **High-Rate Free-Space Continuous-Variable QKD with Self-Referenced Passive State Preparation** [[paper](https://arxiv.org/abs/2604.27299)]
- [2026] **Quantum-Resistant Quantum Teleportation** [[paper](https://arxiv.org/abs/2604.16101)]
- [2026] **Quantum-safe IPsec in the banking industry** [[paper](https://arxiv.org/abs/2604.12985)]
- [2026] **Convex combinations of bosonic pure-loss channels** [[paper](https://arxiv.org/abs/2604.26874)]
- [2026] **Security Risks of VOA-Induced Luminescence in Chip-Based quantum key distribution** [[paper](https://arxiv.org/abs/2604.18422)]
- [2026] **Bayesian Phase Stabilization at the Shot-Noise Limit for Scalable Quantum Networks** [[paper](https://arxiv.org/abs/2604.21388)]
- [2026] **Geometric phase-assisted simple phase compensation enabling quantum key distribution using phase-shifted Bell states** [[paper](https://arxiv.org/abs/2604.12272)]
- [2026] **Towards National Quantum Communication in Europe: Planning and Sizing Terrestrial QKD Networks** [[paper](https://arxiv.org/abs/2604.06764)]
- [2026] **Quantum Protocols for Time Synchronisation and Distribution: A Critical Assessment** [[paper](https://arxiv.org/abs/2604.10243)]
- [2026] **Balancing Quantum Memories in Asymmetric Repeaters for High-Fidelity Entanglement Distribution** [[paper](https://arxiv.org/abs/2604.24554)]
- [2026] **Device-independent quantum cryptography with input leakage** [[paper](https://arxiv.org/abs/2604.20573)]
- [2026] **Improvement of entanglement generation rate in frequency-multiplexed quantum repeaters using cavity-enhanced SPDC source** [[paper](https://arxiv.org/abs/2604.00434)]
- [2026] **How Events Separated by a Timelike Interval Can Help Us Understand Quantum Nonlocality** [[paper](https://arxiv.org/abs/2604.03744)]
- [2026] **Chip-to-chip entanglement distribution over 80-km multicore fiber link** [[paper](https://arxiv.org/abs/2604.26791)]
- [2026] **Rethinking Quantum Networking with Advances in Fiber Technology** [[paper](https://arxiv.org/abs/2603.23718)]
- [2026] **Toward multi-purpose quantum communication networks: from theory to protocol implementation** [[paper](https://arxiv.org/abs/2603.02923)]
- [2026] **QuaNTUM: A Modular Quantum Communication Testbed for Scalable Fiber and Satellite Integration** [[paper](https://arxiv.org/abs/2603.11314)]
- [2026] **Thermodynamic Limits of Quantum Search** [[paper](https://arxiv.org/abs/2603.13654)]
- [2026] **Maximizing Qubit Throughput under Buffer Decoherence and Variability in Generation** [[paper](https://arxiv.org/abs/2603.25482)]
- [2026] **End-to-End QKD Using LEO Satellite Networks** [[paper](https://arxiv.org/abs/2603.06226)]
- [2026] **A Directly Modulated Laser Platform for High-Dimensional Quantum Key Distribution** [[paper](https://arxiv.org/abs/2603.12819)]
- [2026] **Information-Theoretic Solutions for Seedless QRNG Bootstrapping and Hybrid PQC-QKD Key Combination** [[paper](https://arxiv.org/abs/2603.26907)]
- [2026] **Quantum-Secure-By-Construction (QSC): A Paradigm Shift For Post-Quantum Agentic Intelligence** [[paper](https://arxiv.org/abs/2603.15668)]
- [2026] **Stochastic Multipath Routing for High-Throughput Entanglement Distribution in Quantum Repeater Networks** [[paper](https://arxiv.org/abs/2603.25563)]
- [2026] **A high-performance quantum memory for quantum interconnects** [[paper](https://arxiv.org/abs/2603.01156)]
- [2026] **Quantum CDMA-based Continuous Variable Quantum Key Distribution using Chaotic Phase Shifters** [[paper](https://arxiv.org/abs/2603.12777)]
- [2026] **Quantum Technologies and Edge Devices in Electrical Grids: Opportunities, Challenges, and Future Directions** [[paper](https://arxiv.org/abs/2603.06783)]
- [2026] **Post-selective attack with multi-mode projection onto Fock subspace** [[paper](https://arxiv.org/abs/2603.22122)]
- [2026] **Device independent quantum key distribution with robust self-tests** [[paper](https://arxiv.org/abs/2603.28085)]
- [2026] **Noise Inference by Recycling Test Rounds in Verification Protocols** [[paper](https://arxiv.org/abs/2603.30015)]
- [2026] **Study on Structural Expansion of Quantum Cryptographic Communication (QKD) — Organization of Technical Possibilities and Patentability Perspectives Based on the Five TRIZ Viewpoints of "Substitution, Reversal, Parallelism, Staging, and Analogy" —** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.18892711)]
- [2026] **Fundamental Limits on QBER and Distance in Quantum Key Distribution** [[paper](https://arxiv.org/abs/2602.22319)]
- [2026] **Continuous variable quantum key distribution channel emulator for the SPOQC mission** [[paper](https://arxiv.org/abs/2602.23510)]
- [2026] **Self-stabilized high-dimensional quantum key distribution on a metropolitan free-space link** [[paper](https://arxiv.org/abs/2602.22102)]
- [2026] **Entanglement recovery by reversing the effect of noise in quantum repeater** [[paper](https://arxiv.org/abs/2602.21563)]

[⬆ Back to top](#paper-list)

#### Systems & Technology

##### 2026

- [2026] **A Hybrid Secure Communication Architecture Using Quantum Key Distribution and Post Quantum Cryptography** [[paper](https://doi.org/10.1109/ic2pct68894.2026.11584428)]
- [2026] **Spurious Pulse Detection in Fibre-Optic Channels Using Measurement-Device-Independent Quantum Key Distribution with Single-Photon Avalanche Photodiodes** *Research Square* [[paper](https://doi.org/10.21203/rs.3.rs-8711394/v1)]

[⬆ Back to top](#paper-list)

### Quantum Software & Tools

#### Development

##### 2026

- [2026] **Observing the Quantum Compiler through Automatic Experiment Tracking for Qiskit** [[paper](https://arxiv.org/abs/2608.05041)]
- [2026] **Intent-Level Quantum Programming with Assertion-Guided Execution and Inspectable Intermediate Representation** [[paper](https://arxiv.org/abs/2608.02648)]
- [2026] **ChatGPT Solves All Tested Qiskit Homework Assignments** [[paper](https://arxiv.org/abs/2608.19707)]
- [2026] **Catching Transpilation Drift with a CI/CD Workflow in Quantum Software Development** [[paper](https://arxiv.org/abs/2608.08248)]
- [2026] **RF-Budgeted Frame Compilation for Frequency-Multiplexed Superconducting-Qubit Control Using Qubit-Control Identity Records and a Circuit-Informed RFSoC Model** [[paper](https://arxiv.org/abs/2608.10013)]
- [2026] **Know Your Qubits, Know Your Users: Personas for Quantum Software** [[paper](https://arxiv.org/abs/2608.18598)]
- [2026] **New Methods and Frameworks for Quantum State Preparation in Modern Quantum Systems** [[paper](https://arxiv.org/abs/2608.16937)]
- [2026] **Quantum Uncomputation of Clean and Dirty Ancilla Qubits** [[paper](https://arxiv.org/abs/2608.09578)]
- [2026] **Quantum Circuit for General Unitary: Improved T-count via Block Flattening and Dilation** [[paper](https://arxiv.org/abs/2608.17846)]
- [2026] **Memory-, Circuit-, and Ansatz-Efficient VQLS for CFD on Hybrid Quantum-HPC Systems** [[paper](https://arxiv.org/abs/2608.09661)]
- [2026] **Quantum Simulation of SPAD in the Space Radiation Environment** [[paper](https://arxiv.org/abs/2608.00040)]
- [2026] **Architecture-Aware Reinforcement Learning for Communication-Efficient Distributed Quantum Circuit Compilation** [[paper](https://arxiv.org/abs/2608.06892)]
- [2026] **Toward Standardized Quantum Provenance: A Cross-Provider Analysis, Unified API, and Reference Prototype** [[paper](https://arxiv.org/abs/2608.08272)]
- [2026] **Decoder Comparability Across Quantum Software Stacks: Repeated-Round Surface and Digitized-GKP Syndrome Replay** [[paper](https://arxiv.org/abs/2607.19446)]
- [2026] **KQFuzz: Knowledge-Guided Fuzzing for Quantum Libraries via Large Language Models** [[paper](https://arxiv.org/abs/2607.25647)]
- [2026] **QuTuner: Feature- and Learning-Guided Optimization Pass Tuning for Quantum Compilers** [[paper](https://arxiv.org/abs/2607.04586)]
- [2026] **Quantum Software Engineering in Practice: FPGA and AI Integration for Quantum Certification** [[paper](https://arxiv.org/abs/2607.07597)]
- [2026] **Transpiler Autotuning with Predictive Models for Quantum Circuit Optimization** [[paper](https://arxiv.org/abs/2607.29145)]
- [2026] **Benchmarking Large Language Models on Repairing Qiskit Programs using Bugs4Q** [[paper](https://arxiv.org/abs/2607.09007)]
- [2026] **MLIR for Quantum Beyond Gate Cancellation: Quantum Circuit Mapping Reimagined** [[paper](https://arxiv.org/abs/2607.02616)] [[code](https://github.com/munich-quantum-toolkit/core)]
- [2026] **ORBIT-Q: Dual-axis benchmarking of autonomous agents in scientific quantum programming** [[paper](https://arxiv.org/abs/2607.03105)]
- [2026] **InferQ: A Database-Oriented Benchmark for Quantum Circuits Simulation** [[paper](https://arxiv.org/abs/2607.29134)]
- [2026] **Variance-Reduced Trajectory Unravelings for GPU Noisy Quantum-Circuit Simulation: Characterization and a Qiskit-Aer Integration Gap** [[paper](https://arxiv.org/abs/2607.17678)]
- [2026] **Repositories, Contributors, and Continuity: An Empirical Study of Foundational Quantum Software** [[paper](https://arxiv.org/abs/2607.25437)]
- [2026] **Systematic Experiment Tracking in Quantum Software: A Case Study of Reservoir Computing with Error Mitigation** [[paper](https://arxiv.org/abs/2607.24264)]
- [2026] **Quantum Computing : A New Frontier for Science and Society** [[paper](https://arxiv.org/abs/2607.07222)]
- [2026] **Spectral Born machines: classically trainable quantum generative models for discrete data** [[paper](https://arxiv.org/abs/2607.06675)]
- [2026] **Grover's algorithm for image edge detection** [[paper](https://arxiv.org/abs/2607.15744)]
- [2026] **Demonstrating Quadratic Monte Carlo Speedup via Quantum Amplitude Estimation: Nuclear Engineering Examples** [[paper](https://arxiv.org/abs/2607.10772)]
- [2026] **Comparing the Performance of Leading VQE Algorithms for Computing Ground-State Energies of Amino Acids** [[paper](https://arxiv.org/abs/2607.02620)]
- [2026] **Performance Analysis of QAOA Across Distributed Quantum Network Topologies Using SwitchQNet** [[paper](https://arxiv.org/abs/2607.23407)]
- [2026] **Closed Timelike Curve Decoding on Quantum Hardware** [[paper](https://arxiv.org/abs/2607.27473)]
- [2026] **Benchmarking Zero-Setup Quantum Circuit Simulators** [[paper](https://arxiv.org/abs/2607.09882)]
- [2026] **Hash-QNeRF: Multiresolution Hash Encoding for Quantum Neural Radiance Fields** [[paper](https://arxiv.org/abs/2607.21675)]
- [2026] **Blind Transpiler: An open-source library for universally blind and homomorphic quantum computations** [[paper](https://arxiv.org/abs/2607.17131)]
- [2026] **Structure-Agnostic Unitary Learning from Quantum Observable Dynamics with Application to Hamiltonian Identification** [[paper](https://arxiv.org/abs/2607.15316)]
- [2026] **QBugLM: An Agentic Benchmarking Framework for LLM-based Quantum Software Debugging** [[paper](https://arxiv.org/abs/2606.07314)]
- [2026] **Quasilinear Equivalence Checking for Detector Error Models** [[paper](https://arxiv.org/abs/2606.14677)]
- [2026] **Hard-core Bosons in Action: Applications to Quantum Circuits** [[paper](https://arxiv.org/abs/2606.28004)]
- [2026] **Diagonal-Budgeted Trotterization for Efficient Quantum Hamiltonian Simulation** [[paper](https://arxiv.org/abs/2606.16959)]
- [2026] **Matrix Product Operators In The Age of Block Encoding** [[paper](https://arxiv.org/abs/2606.19083)]
- [2026] **Quantum Multi-Party Threshold Private Set Intersection with Explicit Cardinality Testing** [[paper](https://arxiv.org/abs/2606.27996)]
- [2026] **Verifiable and Collusion-Resistant Multi-Party Quantum Private Set Operations** [[paper](https://arxiv.org/abs/2606.27994)]
- [2026] **SPICE-Q and Large-Scale Quantum Chip Production** [[paper](https://arxiv.org/abs/2606.17907)]
- [2026] **Quantum Divide-and-Conquer for the Traveling Salesman Problem: Surpassing the $2^n$ Barrier** [[paper](https://arxiv.org/abs/2606.07322)]
- [2026] **PauLIB: A High-Performance Library for Processing Pauli Strings** [[paper](https://arxiv.org/abs/2605.25974)]
- [2026] **QBalance: A Reproducible Multi-Objective Workflow for Quantum Compilation, Noise Suppression, and Error-Mitigation Strategy Selection** [[paper](https://arxiv.org/abs/2605.02966)]
- [2026] **QSeqSim: A Symbolic Simulator for Qiskit While Loops Using Sequential Quantum Circuits** [[paper](https://arxiv.org/abs/2605.14881)] [[code](https://github.com/Veri-Q/QSeqSim)]
- [2026] **CO-MAP: A Reinforcement Learning Approach to the Qubit Allocation Problem** *NeurIPS* [[paper](https://arxiv.org/abs/2605.13638)]
- [2026] **HPC-vQPU: A Service-Export Architecture for Virtual QPUs on Batch-Scheduled HPC Systems** [[paper](https://arxiv.org/abs/2605.28845)]
- [2026] **Physics Guided Generative Optimization for Trotter Suzuki Decomposition** [[paper](https://arxiv.org/abs/2605.13268)]
- [2026] **QuChaTeR: A Hybrid Quantum-Chaotic Temporal Framework for Earthquake Prediction** [[paper](https://arxiv.org/abs/2605.16454)]
- [2026] **Digital Annealer-Assisted Accuracy-First Quantum Circuit Transpilation with Integrated QUBO Mapping and Routing** [[paper](https://arxiv.org/abs/2605.11500)]
- [2026] **The finite-shot help-harm boundary of zero-noise extrapolation** [[paper](https://arxiv.org/abs/2605.08251)]
- [2026] **QUTest: A Native Testing Framework for Quantum Programs** [[paper](https://arxiv.org/abs/2605.19736)] [[code](https://github.com/QBugs/qutest)]
- [2026] **TuniQ: Autotuning Compilation Passes for Quantum Workloads at Scale for Effectiveness and Efficiency** [[paper](https://arxiv.org/abs/2605.11375)]
- [2026] **Quantum resource reduction for quantum-centric supercomputing via correlated mean-field downfolding framework** [[paper](https://arxiv.org/abs/2605.08675)]
- [2026] **A Compilation Framework for Quantum Simulation of Non-unitary Dynamics** [[paper](https://arxiv.org/abs/2605.23358)]
- [2026] **Bayesian Sequential Verification for Budget-Aware Quantum Program Testing** [[paper](https://arxiv.org/abs/2605.15601)]
- [2026] **QuPort: Topology-, Port-, and Congestion-Aware Compilation for Modular Multi-QPU Quantum Systems** [[paper](https://arxiv.org/abs/2605.12583)]
- [2026] **McLachlan-projected reduced dynamics for ill-posed Schrödingerized backward diffusion** [[paper](https://arxiv.org/abs/2605.17996)]
- [2026] **dSABRE: A SABRE-Style Router for Multi-Core Distributed Quantum Computers** [[paper](https://arxiv.org/abs/2605.21960)] [[code](https://github.com/ebony72/dsabre)]
- [2026] **Equivariant Reinforcement Learning for Clifford Quantum Circuit Synthesis** [[paper](https://arxiv.org/abs/2605.10910)]
- [2026] **QuanBench+: A Unified Multi-Framework Benchmark for LLM-Based Quantum Code Generation** [[paper](https://arxiv.org/abs/2604.08570)]
- [2026] **Broken Quantum: A Systematic Formal Verification Study of Security Vulnerabilities Across the Open-Source Quantum Computing Simulator Ecosystem** [[paper](https://arxiv.org/abs/2604.06712)]
- [2026] **Architecture-aware Unitary Synthesis** [[paper](https://arxiv.org/abs/2604.23777)]
- [2026] **QLLVM: A Scalable Quantum-Classical Co-Compilation Framework based on LLVM** [[paper](https://arxiv.org/abs/2604.15094)]
- [2026] **Unitary Encoding of Thermal States via Thermofield Dynamics on Quantum Computers** [[paper](https://arxiv.org/abs/2604.00802)]
- [2026] **Speed-oriented quantum circuit backend** [[paper](https://arxiv.org/abs/2604.21656)]
- [2026] **Congestion-free routing on quantum chips** [[paper](https://arxiv.org/abs/2604.27015)]
- [2026] **A Game Theoretic Approach for Optimizing Quantum Error Budget Distribution** [[paper](https://arxiv.org/abs/2604.15603)]
- [2026] **A Quantum Search Approach to Magic Square Constraint Problems with Classical Benchmarking** [[paper](https://arxiv.org/abs/2604.04786)]
- [2026] **Orkan: Cache-friendly simulation of quantum operations on hermitian operators** [[paper](https://arxiv.org/abs/2604.15765)]
- [2026] **Practical HPCQC Integration with QDMI: A Real-Hardware Case Study with IQM Systems** [[paper](https://arxiv.org/abs/2604.19869)] [[code](https://github.com/iqm-finland/QDMI-on-IQM)]
- [2026] **Hybridlane: A Software Development Kit for Hybrid Continuous-Discrete Variable Quantum Computing** [[paper](https://arxiv.org/abs/2603.10919)]
- [2026] **Hybrid Classical-Quantum Transfer Learning with Noisy Quantum Circuits** [[paper](https://arxiv.org/abs/2603.16973)]
- [2026] **Revisiting Quantum Code Generation: Where Should Domain Knowledge Live?** [[paper](https://arxiv.org/abs/2603.22184)]
- [2026] **From Foundation ECG Models to NISQ Learners: Distilling ECGFounder into a VQC Student** [[paper](https://arxiv.org/abs/2603.27269)]
- [2026] **Understanding Bugs in Quantum Simulators: An Empirical Study** [[paper](https://arxiv.org/abs/2603.22789)]
- [2026] **Coefficient-Decoupled Matrix Product Operators as an Interface to Linear-Combination-of-Unitaries Circuits** [[paper](https://arxiv.org/abs/2603.24822)]
- [2026] **Optimized Compilation for Distributed Quantum Computing** [[paper](https://arxiv.org/abs/2602.24062)]

[⬆ Back to top](#paper-list)

### Surveys & Taxonomies

#### Theory

##### 2026

- [2026] **Quantum computing in image processing: A review of applications, models, and prospects** *Franklin Open* [[paper](https://doi.org/10.1016/j.fraope.2026.100631)]
- [2026] **Quantum Computing: Today, Tomorrow, and the Future: A Comprehensive Survey of Foundations, Hardware, Algorithms, Markets, Education, and Careers** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202608.0864.v1)]
- [2026] **Quantum computing for natural language processing: a comprehensive review** [[paper](https://doi.org/10.1117/12.3119914)]
- [2026] **A Survey on Resource Management in the Quantum Era: Taxonomy, Cross-Sectoral Applications, and Strategic Roadmap** *Zenodo (CERN European Organization for Nuclear Research)* [[paper](https://doi.org/10.5281/zenodo.21224183)]
- [2026] **Advancing quantum machine learning from conceptual design to practical use** *Expert Systems with Applications* [[paper](https://doi.org/10.1016/j.eswa.2026.132127)]
- [2026] **Quantum-Accelerated Artificial Intelligence for Edge Devices: A Review of Encodings, Models, Hybrid Architectures, and NISQ-Era Realities** *Electronics* [[paper](https://doi.org/10.3390/electronics15132832)]
- [2026] **QUANTUM MACHINE LEARNING IN HEALTHCARE: ACOMPREHENSIVE SURVEY OF RECENT ADVANCES** [[paper](https://doi.org/10.58532/nbennurambh4)]
- [2026] **Backdoor Threats in Variational Quantum Circuits: Taxonomy, Attacks, and Defenses** [[paper](https://arxiv.org/abs/2605.13796)]
- [2026] **Quantum Image Processing for Medical Image Analysis: A Comprehensive Literature Survey** [[paper](https://doi.org/10.1109/aimla67915.2026.11522292)]

[⬆ Back to top](#paper-list)

#### Method

##### 2026

- [2026] **Hybrid Classical-Quantum Systems: The Unsung Heroes of the NISQ Era** *Preprints.org* [[paper](https://doi.org/10.20944/preprints202608.1044.v1)]
- [2026] **Quantum Computing Disruption in the Banking Sector: Empirical Analysis of Risks and Opportunities** *International Journal of Creative and Open Research in Engineering and Management* [[paper](https://doi.org/10.55041/ijcope.v2i5.834)]

[⬆ Back to top](#paper-list)

#### Application

##### 2026

- [2026] **Quantum generative adversarial networks: a comprehensive survey of theories, applications, and challenges in the NISQ era** *Quantum Information Processing* [[paper](https://doi.org/10.1007/s11128-026-05186-1)]

[⬆ Back to top](#paper-list)

#### Reviews & Surveys

##### 2026

- [2026] **Practical Error Suppression and Mitigation for Reliable Quantum Computing** [[paper](https://arxiv.org/abs/2608.20453)]
- [2026] **Low-Depth and Noise-Resilient Quantum State Preparation for Partial Differential Equations via Virtual Rz** [[paper](https://arxiv.org/abs/2608.17249)]
- [2026] **Entanglement Negativity in Noisy Quantum Volume Sampling** [[paper](https://arxiv.org/abs/2608.13654)]
- [2026] **The NISQ Trap: Eight Years of Demonstrations the Hardware Was Built to Lose** [[paper](https://arxiv.org/abs/2607.07530)]
- [2026] **Circuit Design Informed Adaptive Variational Quantum Algorithms** [[paper](https://arxiv.org/abs/2607.04110)]
- [2026] **Quantum Synchronization** [[paper](https://arxiv.org/abs/2607.19328)]
- [2026] **Image Classification on IBM Quantum Computers** [[paper](https://arxiv.org/abs/2607.17705)]
- [2026] **Procrustes Tomography -- reconstructing noisy quantum channels made easy** [[paper](https://arxiv.org/abs/2607.07988)]
- [2026] **Bridging continuous control and Floquet driving for charging many-body spin chains** [[paper](https://arxiv.org/abs/2607.27985)]
- [2026] **An Analytically Trained Variational Surrogate for Quantum Phase Estimation on NISQ Hardware** [[paper](https://arxiv.org/abs/2607.20943)]
- [2026] **Many-Body Physics with Rydberg Atoms: Quantum Simulation and Non-equilibrium Dynamics** [[paper](https://arxiv.org/abs/2607.11038)]
- [2026] **Turbulence in Quantum Gases: Vortices, Waves, and Cascades** [[paper](https://arxiv.org/abs/2607.22244)]
- [2026] **When AI meets quantum information: A comprehensive review** [[paper](https://arxiv.org/abs/2607.00365)]
- [2026] **A NISQ-Aware Hybrid Quantum-Classical Framework for Scalable Combinatorial Optimization** [[paper](https://arxiv.org/abs/2606.00541)]
- [2026] **A Modular Benchmark of Variational Quantum Attack Algorithms for S-DES** [[paper](https://arxiv.org/abs/2606.30143)]
- [2026] **Benchmarking Quantum Algorithmic Resilience for CVaR Portfolio Optimization: The Expressibility-Coherence Trade-off** [[paper](https://arxiv.org/abs/2606.07727)]
- [2026] **From Period Finding to Lattice Sampling: Experimental Insights into Shor's and Regev's Factoring Algorithms** [[paper](https://arxiv.org/abs/2606.17647)]
- [2026] **Exceptional-Point-Anchored Variational Quantum Eigensolver for Non-Hermitian Many-Body Phase Diagrams: Bridging Skin-Effect Topology and Entanglement Criticality on NISQ Hardware** [[paper](https://arxiv.org/abs/2606.18916)]
- [2026] **I-QMapper: Error-Aware Layout Optimization and Device Diagnostics for NISQ Hardware** [[paper](https://arxiv.org/abs/2606.27508)]
- [2026] **Ultracold atomic lattice systems for simulating topological phases: A review** [[paper](https://arxiv.org/abs/2606.16598)]
- [2026] **Automatic quantum function parallelization and memory management in Qrisp** [[paper](https://arxiv.org/abs/2606.31837)]
- [2026] **Estimating The Energy Consumption of Quantum Computing from A Full System Aspect** [[paper](https://arxiv.org/abs/2605.09580)]
- [2026] **Verifying Adversarial Robustness in Quantum Machine Learning: from theory to physical validation via a software tool** [[paper](https://arxiv.org/abs/2605.29877)]
- [2026] **Quantifying the Hadamard Resilience Law: Discovery of the Coherence Gap in NISQ-Era Classifiers** [[paper](https://arxiv.org/abs/2605.10638)]
- [2026] **Evaluating System-Level Fidelity with Peaked Random Circuits** [[paper](https://arxiv.org/abs/2605.25983)]
- [2026] **Gated QKAN-FWP: Scalable Quantum-inspired Sequence Learning** [[paper](https://arxiv.org/abs/2605.06734)]
- [2026] **Mitigating Noise-Induced Barren Plateaus Using a Non-Unitary Ansatz: Application to Molecular Electronic Transport** [[paper](https://arxiv.org/abs/2605.30572)]
- [2026] **Claim against Measurement: Statistical Artefacts in Quantum Error Mitigation Benchmarks** [[paper](https://arxiv.org/abs/2605.29872)]
- [2026] **QASM-Eval: A Dataset to Train and Evaluate LLMs on OpenQASM-3 Beyond Quantum Circuits** [[paper](https://arxiv.org/abs/2605.30358)] [[code](https://github.com/fuzhenxiao/QASM-Eval)]
- [2026] **Experimental Implementation of the Quantum Volunteer's Dilemma on NISQ Hardware: Noise Analysis and Digital-Twin Validation** [[paper](https://arxiv.org/abs/2605.30676)]
- [2026] **Native topological readout on qubit hardware: a Fibonacci-chain benchmark of measurement-compilation trade-offs** [[paper](https://arxiv.org/abs/2605.25913)]
- [2026] **Quantum Model for CVRPTW** [[paper](https://arxiv.org/abs/2605.18393)]
- [2026] **Electronic and Photonic Integration of Single Quantum Emitters in 2D Materials** [[paper](https://arxiv.org/abs/2605.05721)]
- [2026] **Prime Number Identification Demonstrated with Quantum Processors Using a New Rescaling-Based Noise Mitigation Technique** [[paper](https://arxiv.org/abs/2605.28964)]
- [2026] **Optimal FALQON for Quantum Approximate Optimization via Layer-wise Parameter Tuning** [[paper](https://arxiv.org/abs/2605.08332)]
- [2026] **Hybrid Quantum-Classical Neural Architecture Search** [[paper](https://arxiv.org/abs/2605.18345)]
- [2026] **Quantum Simulation of Magnetic Materials: from Ab-Initio to NISQ** [[paper](https://arxiv.org/abs/2605.10667)]
- [2026] **Maximum Likelihood Decoding of Quantum Error Correction Codes** [[paper](https://arxiv.org/abs/2605.17230)]
- [2026] **Passive optical superresolution at the quantum limit** [[paper](https://arxiv.org/abs/2605.10767)]
- [2026] **Transformer refined quantum sampling for strongly correlated electronic structure** [[paper](https://arxiv.org/abs/2605.24617)]
- [2026] **Utility of NISQ devices: optimizing experimental parameters for the fabrication of Au atomic junction using gate-based quantum computers** [[paper](https://arxiv.org/abs/2604.12549)]
- [2026] **CrossBench: Generalized Crosstalk Benchmark Generation for Quantum Computers** [[paper](https://arxiv.org/abs/2604.27183)]
- [2026] **Quantum-HPC Software Stacks and the openQSE Reference Architecture: A Survey** [[paper](https://arxiv.org/abs/2604.20912)]
- [2026] **Quantum annealing inspired algorithms for the NISQ Era** [[paper](https://arxiv.org/abs/2604.25573)]
- [2026] **Quantum simulation of traversable-wormhole-inspired quantum teleportation in a chaotic binary sparse SYK model** [[paper](https://arxiv.org/abs/2604.10090)]
- [2026] **Phase-Fidelity-Aware Truncated Quantum Fourier Transform for Scalable Phase Estimation on NISQ Hardware** [[paper](https://arxiv.org/abs/2604.05456)]
- [2026] **A SWAP-free Framework for QAOA** [[paper](https://arxiv.org/abs/2604.25058)]
- [2026] **A Systematic Study of Noise Effects in Hybrid Quantum-Classical Machine Learning** [[paper](https://arxiv.org/abs/2604.11541)]
- [2026] **Hybrid Quantum--Classical k-Means Clustering via Quantum Feature Maps** [[paper](https://arxiv.org/abs/2604.07873)]
- [2026] **Fluctuation engineering in cavity quantum materials** [[paper](https://arxiv.org/abs/2604.08666)]
- [2026] **Advancing Practical Quantum Embedding Simulations via Operator Commutativity Based State Preparation for Complex Chemical Systems** [[paper](https://arxiv.org/abs/2604.19470)]
- [2026] **Formulating Subgroup Discovery as a Quantum Optimization Problem for Network Security** [[paper](https://arxiv.org/abs/2604.27153)]
- [2026] **Efficient simulation of noisy IQP circuits with amplitude-damping noise** [[paper](https://arxiv.org/abs/2604.05036)]
- [2026] **Scalable Quantum Error Mitigation with Physically Informed Graph Neural Networks** [[paper](https://arxiv.org/abs/2604.16815)]
- [2026] **A parallel and distributed fixed-point quantum search algorithm for solving SAT problems** [[paper](https://arxiv.org/abs/2604.09980)]
- [2026] **Low Depth Distributed Quantum Algorithms for Unordered Database Search** [[paper](https://arxiv.org/abs/2604.14081)]
- [2026] **Variational and Annealing-Based Approaches to Quantum Combinatorial Optimization** [[paper](https://arxiv.org/abs/2603.19117)]
- [2026] **Multiparty Quantum Key Agreement: Architectures, State-of-the-art, and Open Problems** [[paper](https://arxiv.org/abs/2603.03225)]
- [2026] **Quantum Computing and Error Mitigation with Deep Learning for Frenkel Excitons** [[paper](https://arxiv.org/abs/2603.23936)]
- [2026] **Design and Analysis of an Improved Constrained Hypercube Mixer in Quantum Approximate Optimization Algorithm** [[paper](https://arxiv.org/abs/2603.05187)]
- [2026] **Quantum error mitigation by hierarchy-informed sampling: chiral dynamics in the Schwinger model** [[paper](https://arxiv.org/abs/2603.04339)]
- [2026] **Sequence and Image Transformations with Monarq: Quantum Implementations for NISQ Devices** [[paper](https://arxiv.org/abs/2603.03582)]
- [2026] **Hybrid QPE-Ansatz Strategy for Reliable Excited-State Variational Quantum Deflation** [[paper](https://arxiv.org/abs/2603.27978)]
- [2026] **MQTE: A Measurement-Based Quantum Algorithm for Robust Energy Spectrum Estimation in the NISQ Era** [[paper](https://arxiv.org/abs/2603.17959)]
- [2026] **Closing the Loop: Resource-aware Hybrid NAS Guided by Analytical and Hardware-Calibrated Quantum Cost Modeling** [[paper](https://arxiv.org/abs/2603.00625)]
- [2026] **Progress on artificial flat band systems: classifying, perturbing, applying** [[paper](https://arxiv.org/abs/2603.04248)]
- [2026] **Genuine and Non-Genuine Quantum Non-Markovianity: A Unified Information-Theoretic Review** [[paper](https://arxiv.org/abs/2603.28277)]
- [2026] **Bound Trions in Two-Dimensional Monolayers: A Review** [[paper](https://arxiv.org/abs/2603.08346)]
- [2026] **The Birth of Quantum Mechanics and the Dirac Equation** [[paper](https://arxiv.org/abs/2603.15638)]
- [2026] **Experimental Realization of the Markov Chain Monte Carlo Algorithm on a Quantum Computer** [[paper](https://arxiv.org/abs/2603.08395)]
- [2026] **HAMMR-L: Noise Reduction in Quantum Outcomes Using a Richardson-Lucy Deconvolution Algorithm for Quantum State Graphs** [[paper](https://arxiv.org/abs/2603.28821)]
- [2026] **Robust Parametric Quantum Gate Against Stochastic Time-Varying Noise** [[paper](https://arxiv.org/abs/2603.24345)]
- [2026] **Efficient time-series prediction on NISQ devices via time-delayed quantum extreme learning machine** [[paper](https://arxiv.org/abs/2602.21544)]

##### 2018

- [2018] **Quantum Computing in the NISQ Era and Beyond** *Quantum 2, 79 (2018)* [[paper](https://arxiv.org/abs/1801.00862)]

[⬆ Back to top](#paper-list)

## 📖 Citation

If you use this skeleton for a project, please cite:

```bibtex
@misc{skeleton-research,
  author = {Weiß, Tobias},
  title = {Research Corpus Skeleton: Data-Driven Agentic Literature Review},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/<YOUR_ORG>/skeleton-research}
}
```

## 📄 License

MIT — see [LICENSE](LICENSE).
