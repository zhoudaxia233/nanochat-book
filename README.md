# nanochat-book

一份为 CV / 视觉模型背景读者所写的 [`nanochat`](https://github.com/karpathy/nanochat) 中文深读手稿。

从 **tokenization → pretraining → mid-training → SFT → RL → serving** 这条完整的现代 LLM 流水线，每一段都拆开来讲清楚——包括 Transformer 自注意力的数学与直觉、RoPE / RMSNorm / SwiGLU 这些"现代 LLM 标配件"、Muon + AdamW 的混搭优化器、GRPO 强化学习、KV cache 与采样策略，以及完整评估流程。

## 阅读

打开 [`index.html`](./index.html) 即可，单文件自包含。字体走 Google Fonts，数学用 KaTeX (CDN)，图示均为内联 SVG。

如果仓库启用了 GitHub Pages，也可以直接在浏览器里访问。

## 章节

| § | 标题 |
|---|---|
| 0 | 写在前面 |
| 1 | NLP / LLM 世界观 |
| 2 | Tokenization (BPE) |
| 3 | Embeddings |
| 4 | Transformer 核心 |
| 5 | nanochat 的模型实现 |
| 6 | Pretraining |
| 7 | Mid-training |
| 8 | SFT |
| 9 | RL / GRPO |
| 10 | Inference (KV cache, sampling) |
| 11 | Evaluation |
| 12 | 跑起来 |
| 13 | 进阶资源 |

## 致谢

骨架与教学路径完全跟随 Andrej Karpathy 的 [`nanochat`](https://github.com/karpathy/nanochat) 仓库。
