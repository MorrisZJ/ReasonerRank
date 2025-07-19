# ReasonerRank

**ACL 2025 Findings** — *ReasonerRank: Redefining Language Model Evaluation with Ground-Truth-Free Ranking Frameworks*  
**Keywords**: Evaluation · Large Language Models · Reasoning · Ground-Truth-Free

## ✨ TL;DR

We propose **ReasonerRank**, a **ground-truth-free evaluation framework** for ranking LLMs. It focuses on **reasoning consistency** and **instruction adherence**, outperforming existing approaches in complex, label-scarce settings.

## 🧠 Abstract

Conventional LLM evaluation depends on ground-truth labels—often unavailable or costly. **ReasonerRank** shifts the focus to evaluating the **transparency and coherence of reasoning**, not correctness alone.  
Each LLM response is segmented into:

- 🟩 **Direct answer**  
- 🧩 **Multi-step explanation**  
- 📚 **Supporting evidence**

We introduce **TopK-ReRank**, which builds a consensus answer from top models to reduce ambiguity across diverse reasoning styles.  
ReasonerRank outperforms majority voting, triplet ranking, and peer-review methods on multiple tasks.

---

## ✅ TODO List

### 📄 Docs & Release
- [x] Draft README
- [ ] Add usage guide

### 🧩 Baselines & Method Code Release
- [ ] Majority Voting
- [ ] Triplet Ranking
- [ ] LLM-as-a-Judge
- [ ] ReasonerRank (ours)
- [ ] End-to-end eval pipeline script

### 📊 Experiments
- [ ] TopK size ablation
- [ ] Low-agreement / adversarial cases
- [ ] Generalization to new tasks
