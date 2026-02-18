# Sean Brar

ML systems engineer building evaluation and verification infrastructure for AI systems. [Google DeepMind GSoC 2025](https://summerofcode.withgoogle.com/) alumnus.

My work focuses on the question: when an AI system produces output, how do you know it's correct? I build the harnesses, validation pipelines, and correctness guarantees that answer that question — from [statistical evaluation of retrieval systems](https://github.com/seanbrar/ContextRAG) to [schema-constrained LLM output validation](https://github.com/seanbrar/gh-templates) to [infrastructure-level correctness in LLM orchestration](https://polluxlib.dev).

Currently pursuing post-baccalaureate CS and Mathematics, preparing for graduate research in ML evaluation and verification.

## Selected Projects

**[Pollux](https://polluxlib.dev)** — Async multimodal LLM orchestration library with deterministic content-hash caching, single-flight deduplication, and retry-policy separation for generation vs. side-effect calls. 90% API cost reduction on fan-out workloads. *GSoC 2025 with Google DeepMind. Published on PyPI.*

**[ContextRAG](https://github.com/seanbrar/ContextRAG)** — RAG evaluation harness computing 7 retrieval metrics with TOST equivalence testing, bootstrap CIs, and Holm-Bonferroni correction. Validated a preregistered null hypothesis across 60+ experiment runs and 3 datasets.

**[gh-templates](https://github.com/seanbrar/gh-templates)** — Schema-constrained LLM extraction pipeline across 3,746 repositories. Pydantic contracts validating structured Gemini output with transient/permanent error taxonomy at 99.97% success rate.

**[paperweight](https://github.com/seanbrar/paperweight)** — arXiv paper discovery and triage CLI with golden-set validation, offline integration testing, and Tenacity retry architecture. *Published on PyPI.*

## Connect

[seanbrar.com](https://seanbrar.com) ·
[LinkedIn](https://linkedin.com/in/seanbrar) ·
[hello@seanbrar.com](mailto:hello@seanbrar.com)
