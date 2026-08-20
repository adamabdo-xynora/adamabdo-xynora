# Adam Abdo

Cofounder of [Xynora](https://xynora.com), a B2B AI practice. I build production systems with Claude Code daily. Two of them are closed-source client systems running in production today: a quoting and estimation platform for a manufacturing business, and a webhook-driven integration layer that syncs data between vendor systems. The patterns I can share publicly, I do — starting with [webhook-guard](https://github.com/adamabdo-xynora/webhook-guard), a security-hardened webhook receiver extracted from that production work: HMAC verification, idempotent delivery, and credential redaction by value before anything touches disk.

The evaluation side of that work is public too: [agent-eval-harness](https://github.com/adamabdo-xynora/agent-eval-harness) calibrates an LLM judge against human-labeled transcripts — Cohen's kappa, per-criterion drift gates, and a six-run calibration log that includes the judge catching an arithmetic error in my own ground-truth labels.

[![webhook-guard CI](https://github.com/adamabdo-xynora/webhook-guard/actions/workflows/ci.yml/badge.svg)](https://github.com/adamabdo-xynora/webhook-guard) [![agent-eval-harness CI](https://github.com/adamabdo-xynora/agent-eval-harness/actions/workflows/ci.yml/badge.svg)](https://github.com/adamabdo-xynora/agent-eval-harness)
