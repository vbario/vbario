## Hi there

I'm Vladimir from Toronto.

### Sleeping LLM — sleep-wake memory for language models

A system that gives LLMs persistent memory by injecting facts directly into model weights during wake (via MEMIT) and maintaining them through sleep cycles with null-space-constrained refreshes. No RAG, no database — the knowledge is in the weights.

**Key results:** 100% recall at 60 facts on 70B with zero perplexity drift. Sleep converges to perfect recall from 40% degradation in 4 cycles. Sharp wake capacity threshold at 13 facts (8B) — a phase transition, not gradual decay.

**5 research papers** covering the full trajectory from LoRA prototype through the alignment tax discovery to the current MEMIT-only system:

| Paper | Topic | DOI |
|-------|-------|-----|
| 1. Sleep-Wake Consolidation | LoRA sleep-wake on 3B | [10.5281/zenodo.18778760](https://doi.org/10.5281/zenodo.18778760) |
| 2. The Alignment Tax | RLHF suppresses continual learning at scale | [10.5281/zenodo.18778762](https://doi.org/10.5281/zenodo.18778762) |
| 3. Dual-System Memory | MEMIT+LoRA, null-space constraints | [10.5281/zenodo.18778764](https://doi.org/10.5281/zenodo.18778764) |
| 4. Sleeping LLM: Two-Phase | SWS+REM sleep, per-fact staged consolidation | [10.5281/zenodo.18778766](https://doi.org/10.5281/zenodo.18778766) |
| 5. Sleep-Wake Convergence | MEMIT-only, convergence proof, pruning death spiral | [10.5281/zenodo.18778768](https://doi.org/10.5281/zenodo.18778768) |

Code + experiments: [**vbario/sleeping-llm**](https://github.com/vbario/sleeping-llm)

---

Other projects:
- [ResonantMail.com](https://resonantmail.com) — Get your first 100 customers with 1:1 personalized email
- [DefaultTools.com](https://defaulttools.com) — Collapse 10-20 tabs into one place
- [ChatSetter.ai](https://chatsetter.ai) — Instagram DM tool that books appointments
- ClawzBot.com — Open source AI robot (coming soon)

Fields of interest: continual/lifelong machine learning, intelligence orchestration, digital biology, cognitive ergonomics
