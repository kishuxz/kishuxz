# Kishore Kumar

I build AI-enabled software systems where evidence, evaluation, and failure handling matter as much as the model call.

Seattle-based and interested in early-stage teams building reliable agent workflows, voice systems, provenance layers, and production AI infrastructure.

## What I'm Building

- Reliable AI-agent workflows using explicit specifications, provenance, and verification
- Real-time voice and conversational systems with grounded memory and consent boundaries
- Full-stack AI applications using React, FastAPI, PostgreSQL/Supabase, and WebSockets
- Evaluation, observability, and failure handling for production AI behavior
- Cloud-backed data and ML systems where reproducibility is part of the product

## Selected Work

**[Provenance Guard](https://github.com/kishuxz/provenance-guard)**  
Inline provenance enforcement for AI systems: block invalid evidence before context assembly, refuse unsupported claims before delivery, and emit lineage graphs for review. I built the TypeScript monorepo, CLI, bench harness, graph packages, deterministic fixtures, and CI gates. Proof point: GitHub Actions CI is green and the README reports generated benchmark tables with explicit known misses and false positives.

**[Speaker Attribution Graph](https://github.com/kishuxz/speaker-attribution-video)**  
A public foundation for tracing audio, transcript, and optional video evidence into speaker-attribution decisions without shipping private media, transcripts, datasets, or model weights. I built the Python graph/data contracts, source-neutral ingestion boundary, policy checks, conformance suites, packaging gates, and publication review. Proof point: CI is green, local `scripts/verify.py` passed, and the repo records a publication-safety review.

**[EchoPersona](https://github.com/kishuxz/echopersona)**  
A full-stack conversational persona application with React, FastAPI, WebSockets, Supabase, RAG, billing hooks, consent flows, and safety-oriented backend tests. I built across the backend, frontend, persona memory, retrieval, and real-time voice paths. Proof point: the public deployment link is live, and the repository includes tests for consent, grounding, entitlements, persona isolation, WebSocket readiness, and high-stakes safety behavior.

**[openloop-bench](https://github.com/kishuxz/openloop-bench)**  
A benchmark and corpus for evaluating whether models can extract open commitments from founder-style messaging. I built the corpus schema, extractor, matcher, scoring logic, cost model, report generation, and results browser. Proof point: CI validates the corpus, regenerates fixtures/results, and fails if committed evaluation artifacts drift.

**[Checkpoint / SRE Spec](https://github.com/kishuxz/sre-spec)**  
Typed specs and CI gates that hold destructive agent actions before side effects run. The core guarantee is that an injected executor is never called when a run is held. I built the TypeScript packages, examples, CLI, GitHub Action, and SRE traces. Proof point: CI includes lint, typecheck, tests, build, and a dogfood GitHub Action that checks both a blocked bad trace and a passing good trace.

**[avatar-inference-bench](https://github.com/kishuxz/multimodal-avatar)**  
Latency and quality benchmarking for real-time conversational avatar inference, covering LLM serving and diffusion rendering tradeoffs. I built the benchmark harness, analysis scripts, committed result artifacts, and written methodology/caveats. Proof point: results and plots are traceable to committed scripts and data files, with limitations documented in the README.

## How I Work With Coding Agents

- Start with explicit scope, constraints, non-goals, and acceptance criteria.
- Break ambiguous work into independently reviewable stages with issues, branches, tests, and review notes.
- Use agents for implementation, exploration, adversarial review, documentation, and cleanup.
- Require reproducible evidence before accepting completion: tests, CI, generated reports, safety scans, or public artifacts.
- Record limitations, failed assumptions, skipped paths, and unresolved review requirements instead of smoothing them over.

## Open-Source Work

I do not claim SageOx `ox` contributor status yet. I will describe SageOx work here only after there is a public issue comment, branch, PR, or merged commit to link.

## Connect

- GitHub: [kishuxz](https://github.com/kishuxz)
