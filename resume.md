# Edjutawee Dawit
**ML / AI Engineer | Reliable Inference, Evaluation & Model Efficiency**

*Email: edjutaweedawit@gmail.com | Phone: (717) 519-9070*
*Links: [GitHub](https://github.com/edawite) | [LinkedIn](https://linkedin.com/in/edjutawee)*
*Status: U.S. Citizen*

---

## EDUCATION

**Purdue University** | *Expected May 2027*
B.S. in Artificial Intelligence
* **Roles:** Reviewer, NeurIPS 2026 PriGM Workshop | Founding member, Purdue AI Safety Club

---

## EXPERIENCE

**Microsoft** | *Software Engineer Intern, Azure Reliability* | Atlanta, GA (May – Aug 2026)
* Built **SHAP explanations and PSI/KS drift monitoring** for production XGBoost risk predictions, with attribution safeguards and label-free performance estimates.
* Designed a **15-case, five-metric evaluation harness** for risk accuracy, SHAP faithfulness, groundedness, feature overlap and offline F1; wrote **200+ automated tests**.
* Integrated grounded LLM explanations into HTTP/queue-triggered Azure Functions; preserved core predictions through bounded-latency fallback.
* Provisioned private, keyless Azure OpenAI with Bicep, managed identity, role assignments, and private networking.

**Purdue University** | *Undergraduate Researcher (Prof. Abulhair Saparov)* | (Nov 2025 – Present)
* Ran **3-seed Transformer depth sweeps (2–24 layers)** on ACCESS/Anvil GPUs to study modular-arithmetic generalization; tracked train/test behavior in Weights & Biases.
* Analyzed memorization, weight decay, and Fourier representations in held-out generalization; designed synthetic tasks for self-verification and failure prediction.
* **Sole author** of an algorithmic-transfer paper submitted to NeurIPS 2026 PriGM Workshop.

**Eli Lilly** | *LLM Researcher* | Indianapolis, IN (Nov 2025 – May 2026)
* Built an LLM cybersecurity-intelligence system and adversarial evaluation workflow.
* Exposed confident, incorrect threat conclusions under prompt perturbations and conflicting evidence.

**NASA Beyond the Algorithm Challenge** | *ML Engineer* | Remote (May – Aug 2025)
* Built a **PyTorch-to-ONNX-to-TensorRT** pipeline for SAR flood segmentation, achieving **0.92 IoU and 10x faster inference**.
* Evaluated degradation under distribution shift.

---

## SELECTED RESEARCH & PROJECTS

**When Annealed Causal Erasure Fails to Induce Algorithmic Transfer Through Intermediate Tokens**
*Sole author | Submitted to NeurIPS 2026 PriGM Workshop*
* Used residual-state erasure with **3 WAIT tokens** to test whether Transformers perform algorithmic computation in an intermediate workspace.
* Measured **100% mean training accuracy and 0% held-out accuracy** across 24 modular-inversion runs, separating memorization from transfer.

**Performance Engineering** | *Anthropic Public Benchmark (Independent)* | 2026
* Built a dependency-DAG scheduler across **five execution engines**, combining SIMD fusion, software pipelining, and utilization profiling.
* Reduced the benchmark from **147,734 to 1,026 simulated cycles (144x)** with original tests unchanged.

**OpenAI Parameter Golf** | *Independent CPU Study* | 2026
* Built a resumable CPU training/evaluation pipeline with int8 model packing and compressed n-gram sidecars; kept total payload to **15.95 MB**.
* Delta-coded 1.33M n-gram contexts, shrinking the table from 6.40 to 3.47 MB; cut bits-per-byte **5.3% (1.9572 to 1.8534)** on 2.1M validation tokens.

---

## OPEN SOURCE (Google DeepMind Libraries)

* **Optax [#1413](https://github.com/google-deepmind/optax/pull/1413) & Haiku [#846](https://github.com/google-deepmind/dm-haiku/pull/846):** Merged learning-rate schedule edge cases and LayerNorm dtype/JIT regression tests.
* **OpenSpiel [#1557](https://github.com/google-deepmind/open_spiel/pull/1557):** Implemented Quarto in C++, including two-phase turns, win detection, undo, and tensor observations.
* **Distrax [#334](https://github.com/deepmind/distrax/pull/334):** Corrected JAX pytree handling for AOT compilation with donated arguments.

---

## TECHNICAL SKILLS

* **Languages & ML:** Python, C++, Java, TypeScript, SQL, Bash; PyTorch, JAX, XGBoost, SHAP, ONNX, TensorRT
* **Research/Eval:** Model monitoring, evaluations, red-teaming, interpretability, adversarial robustness, ablation studies
* **Infrastructure:** Azure Functions, Storage Queues, Azure OpenAI, Bicep, Docker, Git, CI/CD, Weights & Biases, SIMD/VLIW scheduling
