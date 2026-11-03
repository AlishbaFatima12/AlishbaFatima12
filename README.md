### Syeda Alishba Fatima

**Founder and sole engineer of [Beepsme](https://beepsme.com)** &middot; researcher on the reliability and evaluation of LLM agents: when an agent says it is done, is that true?

I taught mathematics for years, then built an AI that teaches. Beepsme is a voice-first assistant for Windows that acts on a real computer in 41 languages: it teaches from your own book, solves homework, reads aloud, and sends real messages, with actions verified in code before success is spoken.

**Measured, and corrected in public:**
- Do an agent's end-of-task success reports match the state of the world? On a pre-specified 44-task protocol (31 scored trials), the gate's verdict was right on **68%** of trials and erred equally towards over-confidence and over-deferral.
- A post-hoc self-confidence score separated successes from failures at **ROC AUC 0.80**; a blind human second rating gave **Cohen's kappa 0.47**.
- An earlier headline figure (a false-positive rate of 1.00) came from a logging defect. I found it, re-derived the real verdicts from raw evidence, and documented the correction in the study repository.

**Open work** (the product source is private; the measurement is open):
- [beepsme-verification-gate-eval](https://github.com/AlishbaFatima12/beepsme-verification-gate-eval): the study, data, tests, CI, technical report and an [interactive explorer](https://alishbafatima12.github.io/beepsme-verification-gate-eval)
- [agent-reliability-notes](https://github.com/AlishbaFatima12/agent-reliability-notes): failure modes and design patterns in agentic LLM systems
- [deep_learning / GNN Expressivity Lab](https://github.com/AlishbaFatima12/deep_learning): PyTorch message-passing GNNs against the 1-WL test, with honest limitations

**Elsewhere:** [beepsme.com](https://beepsme.com) &middot; [technical portfolio](https://beepsme.com/portfolio) &middot; MSc Pure Mathematics (Gold Medal) &middot; MS Computer Science

> Reliability is a feature. Honesty is a design decision.
