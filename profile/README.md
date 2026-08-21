# RFTSystems4Ai

## From blame to verifiable recovery.

**Falsifiability infrastructure for AI agents, LLM workflows and autonomous systems.**

`RECORD` → `SEAL` → `VERIFY` → `REPLAY` → `DIFF` → `AUDIT` → `REVALUE` → `RECOVER`

### **YOUR AI CHOSE THIS PATH.**
## **RFTSystems4Ai gives you the rest.**

**[▶ ENTER THE VERIFICATION LAB →](https://rftsystems4ai.github.io/ai-verification-workshop/)**  
**[◈ ENTER THE EVOLUTION DATA DECISION FIELD →](https://rftsystems4ai.github.io/evolution-data-results/)**

When an AI system fails, a screenshot of the final output is not enough. We want the run, the state transitions, the memory evidence, the integrity chain, the replay, the first divergence and the evidence needed to recover deliberately rather than guess.

> ### No receipt → no claim.
> **Verification is not truth. Evidence should survive attempts to falsify it.**

---

## The question is not “who do we blame?”

The useful questions are testable:

| Stage | Falsifiable question | RFTSystems4Ai surface |
|---|---|---|
| **Record** | What did the agent actually do? | [Agent Flight Recorder](https://rftsystems4ai.github.io/ai-verification-workshop/lab/flight-recorder/) |
| **Seal** | Has the recorded evidence changed? | Hash-chained records + signed receipts |
| **Verify** | Does the evidence satisfy its declared integrity and trust contract? | [RFT Memory Receipt Engine](https://rftsystems4ai.github.io/ai-verification-workshop/lab/memory-receipt/) |
| **Replay** | Can the recorded run/state be reproduced? | ReplayProof — controlled integration |
| **Diff** | Where did two executions first diverge? | [TimelineDiff](https://rftsystems4ai.github.io/ai-verification-workshop/lab/timelinediff/) |
| **Audit** | What evidence is strong enough to admit? | [TrustStack Console](https://rftsystems4ai.github.io/ai-verification-workshop/lab/truststack/) + AuditPlane |
| **Revalue** | Does yesterday’s decision survive today’s objective? | [Evolution Data](https://rftsystems4ai.github.io/evolution-data-results/) |
| **Recover** | Was a better alternative already present and retained? | Decision-family recovery + verification receipt |

This is the operating model: **start with the state that exists, trace the evidence backwards, then follow the surviving paths forward again.**

---

# Try to break the evidence

We would rather you falsify a claim than trust a badge.

### A five-minute verification exercise

1. Open the **Agent Flight Recorder**.
2. Generate a browser-local evidence chain.
3. Verify the untouched record.
4. Tamper with one recorded event.
5. Verify again.

The untouched chain should pass. The altered chain should not.

**[Break the Agent Flight Recorder →](https://rftsystems4ai.github.io/ai-verification-workshop/lab/flight-recorder/)**

If a verification system cannot survive controlled tampering, replay, mutation and comparison, it should not be presented as strong evidence.

---

# Public verification workshop

The public workshop connects the verification surfaces without exposing the protected producer layer. The primary demos run as static browser labs on GitHub Pages: no Hugging Face CPU, queue or wake-up delay is required.

**[Enter the AI Verification Workshop →](https://rftsystems4ai.github.io/ai-verification-workshop/)**  
[Inspect the public workshop repository](https://github.com/RFTsystems4ai/ai-verification-workshop)

### 01 · START HERE — Agent Forensics Suite
**Orientation across the full evidence path.**

Record → Seal → Verify → Replay → Diff → Audit.

**[Launch START HERE →](https://rftsystems4ai.github.io/ai-verification-workshop/lab/start-here/)**

### 02 · Agent Flight Recorder
**Black-box evidence for agent runs.**

Hash-chained prompts, outputs, tool calls/results and memory operations. Build the record locally, verify it, mutate an event and watch the chain fail.

**[Launch Flight Recorder →](https://rftsystems4ai.github.io/ai-verification-workshop/lab/flight-recorder/)**

### 03 · RFT Memory Receipt Engine
**Ask which memory actually influenced the result.**

The browser lab builds a transparent synthetic memory ledger, binds retrieved evidence and an answer into a SHA-256 receipt, then demonstrates verification failure after evidence tampering. The broader hardened contract remains explicitly scoped in the release evidence.

**[Launch Memory Receipt Engine →](https://rftsystems4ai.github.io/ai-verification-workshop/lab/memory-receipt/)**

### 04 · TimelineDiff
**Find the first meaningful divergence.**

Compare two independently valid timelines, identify their first behavioural divergence, then separately demonstrate what actual evidence corruption looks like.

**[Launch TimelineDiff →](https://rftsystems4ai.github.io/ai-verification-workshop/lab/timelinediff/)**

### 05 · TrustStack Console
**Decide whether evidence is admissible at the required scope.**

`ALLOW` — required evidence verifies at the declared scope.  
`HOLD` — inspectable evidence exists, but its binding is partial.  
`BLOCK` — integrity or signature verification fails.

**[Launch TrustStack →](https://rftsystems4ai.github.io/ai-verification-workshop/lab/truststack/)**

---

# Controlled verification layer

Some verification capability is intentionally **not shipped as public implementation source**.

### ReplayProof · Agent POV Verified Replay
Controlled deterministic replay and run-consistency checking. Internal mutation tests cover chain integrity, state replay and signature behaviour while keeping signer trust separate from bundle consistency.

### AuditPlane · LLM Decision Proofs
Controlled decision-evidence plane for signed receipts, chained runs, replay/drift analysis and Merkle-backed inclusion evidence.

### RFT-VS · Evidence Verifier
Protected verification extension for deeper evidence checking and organisation-level accountability workflows. Public descriptions expose capability boundaries, not producer implementation.

The public workshop records these capabilities without publishing protected source, signing secrets, private trust stores or reconstruction logic.

---

# Evolution Data · from verification to recovery

> ### Your AI already explored more than it showed you.
> **The question is whether you kept enough evidence to find it again.**

Verification tells you whether the evidence survives inspection. **Recovery asks what that evidence lets you do next.**

Evolution Data retains decision families rather than only yesterday’s winner, then revalues the recorded alternatives when the objective changes.

A model upgrade, tighter latency SLA, new QA threshold, reduced inference budget or changed risk appetite can alter which candidate is preferred — without pretending the old run never happened.

**[ENTER THE DECISION FIELD →](https://rftsystems4ai.github.io/evolution-data-results/)**  
[Inspect the Evolution Data repository](https://github.com/RFTsystems4ai/evolution-data-results)

The Decision Field demonstrates the idea visually:

**observed outcome → reconstruct alternatives → change conditions → detect divergence → test retention → verify the recovered path**

No private ranking, mutation or producer mechanism needs to be exposed for a customer to inspect the resulting evidence contract.

---

# External integration evidence

## HAK_GAL · LLM security workflow

An external builder integrated RFTSystems verification concepts into an LLM security/firewall workflow spanning receipts, event recording, baselines, replay, differential analysis and verification bundles.

We keep the evidence boundary explicit:

- **their report** describes their integration and observed results;
- **our technical follow-up** records the RFTSystems verification-side corrections and contract boundary;
- neither is presented as proof of claims that the other party did not verify.

**[Read HAK_GAL’s integration report →](https://discuss.huggingface.co/t/a-bidirectional-llm-firewall-next-level-x1-help-wanted/172352/11)**  
**[Read the RFTSystems technical verification follow-up →](https://discuss.huggingface.co/t/a-bidirectional-llm-firewall-next-level-x1-help-wanted/172352/16)**

That distinction matters. **External adoption is evidence of use. Our own release gates are evidence about our verification components. They are not interchangeable.**

---

# What “verified” means here

We deliberately separate three questions:

### Integrity
Has the recorded artefact changed relative to the committed evidence?

### Origin / provenance
Does the artefact verify against a key, anchor or source identity that the verifier independently trusts?

### Truth / correctness
Is the underlying statement itself true?

A valid signature can establish integrity and key-relative origin. **It cannot turn a false statement into a true one.**

That boundary is part of the product, not a footnote.

---

# Current release evidence

The verification workshop control plane has completed its current eight-component release candidate gate:

| Evidence | Recorded result |
|---|---:|
| Canonical verification components | **8** |
| End-to-end release checks | **100 / 100 passed** |
| Failed checks | **0** |
| Public-export secret candidates | **0 detected** |
| Public-export private-mechanism candidates | **0 detected** |
| Public Hugging Face provenance records | **5 pinned** |

The public release record is deliberately narrow: it verifies catalogue/provenance consistency, recorded component evidence, public/private separation and the sanitised export surface. It **does not** claim that cryptographic integrity proves the truth of an underlying factual statement, and it does not claim protected runtime execution where that execution was not part of the gate.

**[Inspect the public release status →](https://github.com/RFTsystems4ai/ai-verification-workshop/blob/main/verification/RELEASE_STATUS.json)**  
**[Inspect pinned public-source provenance →](https://github.com/RFTsystems4ai/ai-verification-workshop/blob/main/provenance/PUBLIC_SOURCE_COMMITS.json)**

---

# Built for teams that need failure to become useful

RFTSystems4Ai is aimed at builders working with systems where “the model said it” is not an adequate incident record:

- coding and software-engineering agents;
- multi-agent orchestration;
- tool-using autonomous workflows;
- retrieval and memory systems;
- model or prompt migrations;
- AI security and red-team pipelines;
- evaluation and regression investigation;
- high-accountability internal AI systems;
- reproducibility and incident review.

The objective is not to make failure disappear.

> **Make failure inspectable. Make claims falsifiable. Preserve enough evidence to recover.**

---

## RFTSystems4Ai

**From blame to verifiable recovery.**

Public verification tools are available through the live browser labs above. Controlled integration and API discussions: **rftsystems4ai@gmail.com**
