# Leo Bergmiller

**M.S. Data Science — Columbia University (Expected Dec 2026)**

I work on LLM systems and mechanistic interpretability — how multi-agent dialogue dynamics, adversarial inputs, and instruction tuning interact with what models actually represent internally. I've also implemented modern architectures from scratch to keep my fundamentals sharp.

---

## Featured Projects

### 🔹 Gaslighting Resilience in Multi-Agent LLM Systems
*CoT-Targeted Attacks and Mechanistic Analysis of Capitulation*

A 1,200-exchange controlled study of fabricated chain-of-thought attacks against three open-source LLMs (Llama-3-8B-Instruct, Mistral-7B-v0.1, Pythia-6.9B) with a GPT-4o-mini adversarial attacker. Identifies CoT-targeted gaslighting as a vulnerability that emerges with instruction tuning.

- TransformerLens + native-hook layer-wise activation analysis
- Cross-validated logistic probes (capitulation decodable from layer 1 on Pythia, layer 12 on Llama)
- LLM-as-a-judge classifier validated against human consensus (F1 = 0.987, κ = 0.94)
- Full statistical pipeline: chi-squared, Bonferroni, Cohen's h, Mann-Whitney U / KS, Wilson 95% CIs

→ [gaslighting_multi_agent_llm_systems](https://github.com/KaurArshnoor/gaslighting_multi_agent_llm_systems)

### 🔹 Tiny Transformer From Scratch
Implemented a causal self-attention Transformer in PyTorch for next-token prediction on Tiny Shakespeare.

- Positional encoding
- Multi-head self-attention
- Causal masking
- Residual connections
- Perplexity evaluation
- Attention heatmap visualization

### 🔹 Boosting Models & Bias-Variance Study
Compared Decision Trees, Gradient Boosting, and XGBoost.

- Hyperparameter tuning
- Learning curves
- Bias-variance analysis
- Feature importance
- Precision-Recall evaluation

---

## Technical Stack
Python · PyTorch · HuggingFace Transformers · TransformerLens · Scikit-learn · SciPy · statsmodels · XGBoost · NumPy · pandas · Matplotlib · Streamlit
