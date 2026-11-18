## STOP,see Repo list here👋
>scroll down to know about my project

This proflie is a mini research and tools lab for AI resrchers 

I'm **Kapil Dhinwa**, a school student learning AI by building practical projects with AI-assisted development.

I enjoy exploring new ideas in machine learning, language models, memory systems, neuromorphic computing, and wave-based AI. I design the ideas, break down the problems, and use AI as a development partner to help turn them into working projects.

---

### 🌍 New Architecture (5)

- [fluid-ARC](https://github.com/kapildhinwa2010-dev/fluid-ARC) — A numerics-first language model built on sheaf-guided spectral diffusion — every math claim machine-checked (21 self-checks, 59 CI tests).
- [DNA_DYNIMO](https://github.com/kapildhinwa2010-dev/DNA_DYNIMO) — An experimental PyTorch toolkit exploring Fourier-feature neural fields for matrix generation, budget-aware routing, and a compact causal transformer.
- [NEXUS-16](https://github.com/kapildhinwa2010-dev/NEXUS-16) — A wave-native, tokenizer-free byte-level semantic encoder crunching text at ~956K tokens/s.
- [Spiking_GNN](https://github.com/kapildhinwa2010-dev/Spiking_GNN) — A bio-inspired 241M-parameter spiking graph neural network that computes with spikes, not dense activations.
- [FREQUENCY_EVER](https://github.com/kapildhinwa2010-dev/FREQUENCY_EVER) — A wave-native blueprint: no floats, no tokenizer, no GEMM — computation is wave interference.

### 🔧 Adaptive Plug-and-Play Layers (2)

- [fluidtech](https://github.com/kapildhinwa2010-dev/fluidtech) 🚀 *flagship* — A bounded memory layer for language models with exact recall, bounded KV-cache management, and an optional PyTorch adapter.
- [TMU](https://github.com/kapildhinwa2010-dev/TMU) — A GPT-2 plugin layer that carries world time into a frozen base model — only the layer trains.



### 🧪 Failed Research Arc: DNA-LLM (Parts 1–3) — Post-Mortem

> *An honest archive of an ambitious attempt to compress full LLM knowledge and behavior into <1–10 MB — documenting what worked in narrow tests, where the approach broke, and why I pivoted.*

- **[DNA-LLM](https://github.com/kapildhinwa2010-dev/DNA-LLM)** *(Part 1 — Weight Generation / `DNA Nanna`)*: Explored Implicit Neural Representations (randomized Fourier Features + MLP) to map 2D coordinates into ~1B virtual parameters (3.75 GB) from ~257K DNA weights (~1 MB, 3913x ratio). **Why it fell short:** Generating structured weights from coordinates didn't translate into compressing real pretrained LLM knowledge without quality collapse.
- **[DNA-LLM-PART-2](https://github.com/kapildhinwa2010-dev/DNA-LLM-PART-2)** *(Part 2 — Behavior Extraction / `Reverse.Dean`)*: Shifted from static weights to activation-level *"Behavior DNA"* (8,784 LOC across 21 experiments using runtime SVD bottlenecks, logit lens, concept injection, spiral zoom, and distribution-shift tests). **Why it fell short:** Activation bottlenecks and concept rescue couldn't generalize reliably to unseen, open-ended prompts.
- **[DNA-LLM-PART-3](https://github.com/kapildhinwa2010-dev/DNA-LLM-PART-3)** *(Part 3 — Knowledge Memory / `HELIX`)*: Separated storage from interpretation using SPIRAL content-addressing, wave lattices, Reed-Solomon ECC, and relational rule algebra (2,308 LOC). **Result:** Achieved 99.9–100% accuracy in 3–13 KB on narrow, rule-dense domains (e.g., structured geography/chemistry relations), **but failed the main goal** — it does not scale to general LLM knowledge, full reasoning behavior, or billions of open-ended facts.

**Key Takeaway:**
- Rule-dense, structured domains compress dramatically well, but general natural-language intelligence and reasoning cannot be replaced by compact coordinate/hash/rule memory alone — which motivated my shift toward practical plug-and-play memory layers like `fluidtech`.

And all the toolkit(24 repos) and advance tools(94 repos) made by above mentioned 3 failed projects ...


### 🧪 Toolkit (24 tools!)

Small, honest, CI-verified research tools — every repo ships with bounded tests, self-diagnosing CI, CodeQL, and honest limitations sections. Negative results included.

**Measurement & trust:**

- [WAVE-CLASH](https://github.com/kapildhinwa2010-dev/WAVE-CLASH) — Stack many messages into one wave signal and measure the crosstalk when you read them back.
- [NEVER_LIE](https://github.com/kapildhinwa2010-dev/NEVER_LIE) — A digest-guarded exact memory that abstains on corruption instead of answering wrong.
- [MOLECULE-COMPRESS](https://github.com/kapildhinwa2010-dev/MOLECULE-COMPRESS) — Quality-gated LLM compression experiments; first result: ternary PTQ collapse, measured on Qwen2.5-0.5B.
- [VARIEANCE-LIES](https://github.com/kapildhinwa2010-dev/VARIEANCE-LIES) — Rank sweeps showing how much of "99% variance preserved" is a lie for actual behavior.
- [RULE-FORAGER](https://github.com/kapildhinwa2010-dev/RULE-FORAGER) — Mines inverse relations between facts, so derived rules cost zero stored bytes.
- [POWERLAW-PROBE](https://github.com/kapildhinwa2010-dev/POWERLAW-PROBE) — SVD spectra of activations vs weights — tells you if a layer is compressible at all.
- [LLM-EQUATION](https://github.com/kapildhinwa2010-dev/LLM-EQUATION) — A curve distiller that fits equations with an extrapolation gate — and rejects curve-fits that lie.
- [ANT-HILL](https://github.com/kapildhinwa2010-dev/ANT-HILL) — Builds a 3D "occupancy mold" of how a model physically organizes knowledge, with an HTML viewer.
- [Draft_ponit_harness](https://github.com/kapildhinwa2010-dev/Draft_ponit_harness) — drift-point: the exact generated token where a compressed model replay first diverges from the original.

**Model introspection:**

- [TRACE-PATH](https://github.com/kapildhinwa2010-dev/TRACE-PATH) — Finds which block of a model carries a piece of information, with activation patching.
- [BUS-TRACE](https://github.com/kapildhinwa2010-dev/BUS-TRACE) — Shows who writes what into the residual stream, block by block.
- [HEAD-DETECTIVE](https://github.com/kapildhinwa2010-dev/HEAD-DETECTIVE) — Classifies what every attention head actually does, straight from its attention patterns.
- [LOGIT-STREAM](https://github.com/kapildhinwa2010-dev/LOGIT-STREAM) — Gives every answer token a birth certificate: which layer pushed it to the top.
- [STATE-MIRROR](https://github.com/kapildhinwa2010-dev/STATE-MIRROR) — Watches where two nearly identical prompts start to differ inside a model.
- [-KNOCKOUT-LAB](https://github.com/kapildhinwa2010-dev/-KNOCKOUT-LAB) — Removes one block at a time and ranks every component by the damage it prevents.
- [NOISE-STORM](https://github.com/kapildhinwa2010-dev/NOISE-STORM) — Pressure-tests every block with calibrated noise and maps what is fragile.
- [PROBE-STACK](https://github.com/kapildhinwa2010-dev/PROBE-STACK) — Maps where a property lives inside a model, one tiny probe per layer.
- [INNER-VOTE-](https://github.com/kapildhinwa2010-dev/INNER-VOTE-) — Checks whether a model agrees with itself: hidden-state consensus across paraphrases.
- [KNOW-VAULT](https://github.com/kapildhinwa2010-dev/KNOW-VAULT) — Censuses the storage vault inside a memory layer: how many slots, how many dead.

**Weight & representation audits:**

- [LAYER-CENSUS-](https://github.com/kapildhinwa2010-dev/LAYER-CENSUS-) — Per-layer atlas of weight matrices: shapes, effective rank, spectrum decay, norm statistics.
- [TWIN-TOWER](https://github.com/kapildhinwa2010-dev/TWIN-TOWER) — Detects duplicated and redundant layers with cross-layer similarity clustering.
- [DEAD-CELL](https://github.com/kapildhinwa2010-dev/DEAD-CELL) — Maps internal waste: zero rows and columns in weights, plus neurons that never activate.
- [SKIP-RUN-](https://github.com/kapildhinwa2010-dev/SKIP-RUN-) — Measures how much model depth is real by skipping every k-th block and tracking behavior deltas.
- [GEOMETRY-SCAN](https://github.com/kapildhinwa2010-dev/GEOMETRY-SCAN) — Per-layer hidden state geometry: intrinsic dimension, anisotropy cone strength, variance spectrum.

> ✦ These projects are co-built with AI, but the ideas, direction, and system designs are mine. I use AI to help execute, test, and iterate on the concepts I want to explore.

### 🔬 Advanced Toolkit (94 specialized tools)

All repositories feature: CI workflows, CodeQL security analysis, comprehensive tests, professional documentation, and bugless Python code.

**DNA & Fourier-based Systems:**

- [FourierNet](https://github.com/kapildhinwa2010-dev/FourierNet) — Fourier-based weight generation with extreme compression (3913x)
- [DNA-Encoder](https://github.com/kapildhinwa2010-dev/DNA-Encoder) — Encode any model into DNA representation
- [DNA-Pro](https://github.com/kapildhinwa2010-dev/DNA-Pro) — Production-ready DNA generator with inference mode
- [DNA-Lite](https://github.com/kapildhinwa2010-dev/DNA-Lite) — Lightweight DNA for small models
- [SparseDNA](https://github.com/kapildhinwa2010-dev/SparseDNA) — Sparse matrix generation with DNA
- [QuantDNA](https://github.com/kapildhinwa2010-dev/QuantDNA) — Quantized DNA weight generation (1-8 bit)
- [MatrixGen](https://github.com/kapildhinwa2010-dev/MatrixGen) — Generate matrices from coordinates
- [WeightForge](https://github.com/kapildhinwa2010-dev/WeightForge) — Forge weights from minimal parameters
- [ParamShrink](https://github.com/kapildhinwa2010-dev/ParamShrink) — Parameter shrinking via Fourier features

**Compression & Activation Analysis:**

- [CompressorNet](https://github.com/kapildhinwa2010-dev/CompressorNet) — Neural network compression benchmark suite
- [ActivationCompress](https://github.com/kapildhinwa2010-dev/ActivationCompress) — SVD, PCA, and random projection compression
- [BehaviorDNA](https://github.com/kapildhinwa2010-dev/BehaviorDNA) — Behavior analysis and compression
- [SVD-Lens](https://github.com/kapildhinwa2010-dev/SVD-Lens) — SVD-based layer analysis and bottleneck detection
- [BottleneckTest](https://github.com/kapildhinwa2010-dev/BottleneckTest) — Bottleneck testing framework
- [DistributionShift](https://github.com/kapildhinwa2010-dev/DistributionShift) — Distribution shift detection
- [GeneralizationTest](https://github.com/kapildhinwa2010-dev/GeneralizationTest) — Generalization testing
- [OutputSensitivity](https://github.com/kapildhinwa2010-dev/OutputSensitivity) — Output sensitivity analysis
- [ActivationRank](https://github.com/kapildhinwa2010-dev/ActivationRank) — Activation rank analysis
- [SensitivityMap](https://github.com/kapildhinwa2010-dev/SensitivityMap) — Sensitivity mapping
- [VarianceBasis](https://github.com/kapildhinwa2010-dev/VarianceBasis) — Variance basis analysis
- [KnowledgeProbe](https://github.com/kapildhinwa2010-dev/KnowledgeProbe) — Knowledge probing
- [GradientFlow](https://github.com/kapildhinwa2010-dev/GradientFlow) — Gradient flow analysis

**Knowledge & Memory Systems:**

- [KnowledgeGraph](https://github.com/kapildhinwa2010-dev/KnowledgeGraph) — Knowledge graph construction
- [InterferenceEngine](https://github.com/kapildhinwa2010-dev/InterferenceEngine) — Interference detection and mitigation
- [ChainReasoner](https://github.com/kapildhinwa2010-dev/ChainReasoner) — Chain-of-thought reasoning
- [AliasDeriver](https://github.com/kapildhinwa2010-dev/AliasDeriver) — Alias derivation
- [FactBase](https://github.com/kapildhinwa2010-dev/FactBase) — Fact-based knowledge storage
- [RuleEngine](https://github.com/kapildhinwa2010-dev/RuleEngine) — Rule-based reasoning
- [ContentAddress](https://github.com/kapildhinwa2010-dev/ContentAddress) — Content-addressable memory
- [ECC-Memory](https://github.com/kapildhinwa2010-dev/ECC-Memory) — Error-correcting code memory
- [CausalMemory](https://github.com/kapildhinwa2010-dev/CausalMemory) — Causal memory system
- [SemanticMemory](https://github.com/kapildhinwa2010-dev/SemanticMemory) — Semantic memory system
- [TemporalMemory](https://github.com/kapildhinwa2010-dev/TemporalMemory) — Temporal memory system
- [HierarchicalMemory](https://github.com/kapildhinwa2010-dev/HierarchicalMemory) — Hierarchical memory system

**HELIX Architecture:**

- [HELIX-Core](https://github.com/kapildhinwa2010-dev/HELIX-Core) — HELIX core architecture
- [SpiralDB](https://github.com/kapildhinwa2010-dev/SpiralDB) — Spiral database for HELIX
- [WaveMemory](https://github.com/kapildhinwa2010-dev/WaveMemory) — Wave-based memory
- [HELIX-Pro](https://github.com/kapildhinwa2010-dev/HELIX-Pro) — Production-ready HELIX
- [Fourier-HELIX](https://github.com/kapildhinwa2010-dev/Fourier-HELIX) — Fourier-based HELIX
- [Compression-HELIX](https://github.com/kapildhinwa2010-dev/Compression-HELIX) — Compression-optimized HELIX
- [DNA-HELIX](https://github.com/kapildhinwa2010-dev/DNA-HELIX) — DNA-based HELIX
- [Activation-HELIX](https://github.com/kapildhinwa2010-dev/Activation-HELIX) — Activation-based HELIX
- [Behavior-HELIX](https://github.com/kapildhinwa2010-dev/Behavior-HELIX) — Behavior-based HELIX

**Router Systems:**

- [ComplexityRouter](https://github.com/kapildhinwa2010-dev/ComplexityRouter) — Complexity-based routing
- [KnowledgeRouter](https://github.com/kapildhinwa2010-dev/KnowledgeRouter) — Knowledge-based routing
- [MemoryRouter](https://github.com/kapildhinwa2010-dev/MemoryRouter) — Memory-based routing
- [SpeedRouter](https://github.com/kapildhinwa2010-dev/SpeedRouter) — Speed-optimized routing
- [HybridRouter](https://github.com/kapildhinwa2010-dev/HybridRouter) — Hybrid routing

**Benchmark Suites:**

- [CompressionBench](https://github.com/kapildhinwa2010-dev/CompressionBench) — Compression benchmarks
- [KnowledgeBench](https://github.com/kapildhinwa2010-dev/KnowledgeBench) — Knowledge benchmarks
- [MemoryBench](https://github.com/kapildhinwa2010-dev/MemoryBench) — Memory benchmarks
- [SpeedBench](https://github.com/kapildhinwa2010-dev/SpeedBench) — Speed benchmarks
- [RobustnessBench](https://github.com/kapildhinwa2010-dev/RobustnessBench) — Robustness benchmarks

**Serving Systems:**

- [DNA-Serve](https://github.com/kapildhinwa2010-dev/DNA-Serve) — DNA serving system
- [HELIX-Serve](https://github.com/kapildhinwa2010-dev/HELIX-Serve) — HELIX serving system
- [Compression-Serve](https://github.com/kapildhinwa2010-dev/Compression-Serve) — Compression serving
- [Knowledge-Serve](https://github.com/kapildhinwa2010-dev/Knowledge-Serve) — Knowledge serving
- [Router-Serve](https://github.com/kapildhinwa2010-dev/Router-Serve) — Router serving

**Libraries:**

- [DNA-Lib](https://github.com/kapildhinwa2010-dev/DNA-Lib) — DNA library
- [HELIX-Lib](https://github.com/kapildhinwa2010-dev/HELIX-Lib) — HELIX library
- [Compression-Lib](https://github.com/kapildhinwa2010-dev/Compression-Lib) — Compression library
- [Activation-Lib](https://github.com/kapildhinwa2010-dev/Activation-Lib) — Activation library
- [Behavior-Lib](https://github.com/kapildhinwa2010-dev/Behavior-Lib) — Behavior library

**Research Tools:**

- [DNA-Research](https://github.com/kapildhinwa2010-dev/DNA-Research) — DNA research tools
- [HELIX-Research](https://github.com/kapildhinwa2010-dev/HELIX-Research) — HELIX research tools
- [Behavior-Research](https://github.com/kapildhinwa2010-dev/Behavior-Research) — Behavior research tools
- [Activation-Research](https://github.com/kapildhinwa2010-dev/Activation-Research) — Activation research tools
- [Memory-Research](https://github.com/kapildhinwa2010-dev/Memory-Research) — Memory research tools

**Testing Frameworks:**

- [CompressionTest](https://github.com/kapildhinwa2010-dev/CompressionTest) — Compression testing
- [MemoryTest](https://github.com/kapildhinwa2010-dev/MemoryTest) — Memory testing
- [SpeedTest](https://github.com/kapildhinwa2010-dev/SpeedTest) — Speed testing
- [RobustnessTest](https://github.com/kapildhinwa2010-dev/RobustnessTest) — Robustness testing

**Generation Systems:**

- [InfiniteGen](https://github.com/kapildhinwa2010-dev/InfiniteGen) — Infinite generation
- [ChunkGen](https://github.com/kapildhinwa2010-dev/ChunkGen) — Chunked generation
- [SafeGen](https://github.com/kapildhinwa2010-dev/SafeGen) — Safe generation
- [StreamGen](https://github.com/kapildhinwa2010-dev/StreamGen) — Streaming generation
- [ParallelGen](https://github.com/kapildhinwa2010-dev/ParallelGen) — Parallel generation

**DNA Architectures:**

- [DNA-Transformer](https://github.com/kapildhinwa2010-dev/DNA-Transformer) — DNA-based Transformer
- [DNA-MLP](https://github.com/kapildhinwa2010-dev/DNA-MLP) — DNA-based MLP
- [DNA-CNN](https://github.com/kapildhinwa2010-dev/DNA-CNN) — DNA-based CNN
- [DNA-RNN](https://github.com/kapildhinwa2010-dev/DNA-RNN) — DNA-based RNN
- [DNA-GAN](https://github.com/kapildhinwa2010-dev/DNA-GAN) — DNA-based GAN

**Additional Tools:**

- [NeuralCompress](https://github.com/kapildhinwa2010-dev/NeuralCompress) — Neural compression tools
- [DeepAnalyze](https://github.com/kapildhinwa2010-dev/DeepAnalyze) — Deep analysis tools
- [ModelLens](https://github.com/kapildhinwa2010-dev/ModelLens) — Model introspection lens
- [KnowledgeNet](https://github.com/kapildhinwa2010-dev/KnowledgeNet) — Knowledge network
- [MemoryFlow](https://github.com/kapildhinwa2010-dev/MemoryFlow) — Memory flow analysis
- [ActivationNet](https://github.com/kapildhinwa2010-dev/ActivationNet) — Activation network
- [BehaviorNet](https://github.com/kapildhinwa2010-dev/BehaviorNet) — Behavior network
- [HELIX-Net](https://github.com/kapildhinwa2010-dev/HELIX-Net) — HELIX network
- [DNA-Net](https://github.com/kapildhinwa2010-dev/DNA-Net) — DNA network
- [CompressNet](https://github.com/kapildhinwa2010-dev/CompressNet) — Compression network
- [RouterNet](https://github.com/kapildhinwa2010-dev/RouterNet) — Router network
- [ServeNet](https://github.com/kapildhinwa2010-dev/ServeNet) — Serving network

---

### 🧠 What I'm learning

- Python and PyTorch
- Large language models and memory systems
- Neural networks and graph learning
- Neuromorphic and wave-based computing
- Reproducible open-source experimentation

---

### 📍 Current status

- 🌍 School student
- 🧑‍🎓 Learning: AI and machine learning
- 🏗️ Building: projects that excite me
- 📱 Back online: Holi 2027

### 👥 Connect and collaborate

I enjoy experimenting with AI architectures and learning in public. If you find an issue or have an idea, feel free to open an issue in the relevant repository.

> **Learn. Build. Share. Repeat.**
