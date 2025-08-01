# ScreenCoder – Mixture of Agents for Code Generation

This project is a practical implementation and adaptation of **ScreenCoder: Mixture of Agents for In-Context Learning in Code Generation** ([arXiv:2507.22827](https://arxiv.org/abs/2507.22827)). The paper introduces a Mixture of Agents (MoA) framework that coordinates multiple large language models (LLMs) to enhance code generation capabilities via a routing mechanism.

---

## 🎯 Objectives

- Reproduce the agent-based code generation setup proposed in ScreenCoder
- Compare outputs from different code-generating LLMs (e.g., GPT-4, Claude, CodeLLaMA)
- Implement and evaluate routing strategies for selecting the best candidate output
- Benchmark the MoA system on standard code generation tasks (e.g., HumanEval, MBPP)

---

## 📁 Project Structure

```text
moa-llm-project/
├── agents/            # Agents using different LLMs (e.g., Mistral, GPT-4)
├── router/            # Router logic to select best output
├── evaluate/          # Evaluation scripts and metrics
├── app/               # Optional demo interface
├── data/              # Prompts, candidate generations
├── requirements.txt   # Python dependencies
└── README.md
