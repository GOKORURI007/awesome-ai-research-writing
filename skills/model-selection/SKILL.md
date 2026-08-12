---
name: model-selection
description: 推荐科研场景下的主力 LLM：论文写作/idea 交互用 Gemini-3-pro/flash，实验代码编写用 Claude-4.5 系列与 Cursor Composer；依据 arena.ai Creative Writing 榜单与一线科研实践（GPT 5.x 写作表现一般）。Recommends LLMs for research: Gemini-3-pro/flash for writing and ideas, Claude-4.5 / Cursor Composer for code, based on the arena.ai creative-writing leaderboard and field practice. Use when the user asks which model to use for paper writing vs coding.
---

# 模型选择：科研场景 LLM 选型建议

> 以下结论来自公开榜单与一线科研人员的真实使用实践，供选型参考。

## 依据

我们从公开网站 [arena.ai](https://arena.ai/zh/leaderboard/text/creative-writing) 上获取了 Creative Writing 能力排名前 10 的模型与具体版本（榜单结果见仓库 `images/model-rank.png`），该榜单结果与调研群体的日常使用选择高度契合。

## 推荐

- **论文写作 / idea 交互**：主力模型为 **Gemini-3-pro / Gemini-3-flash**。
- **实验代码编写**：更多使用 **Claude-4.5 系列**模型，以及 **Cursor 内置的 Composer** 模型。
- **GPT 系列**：从实际体验来看，GPT 5.1 与 GPT 5.2 的表现较为一般，目前对 GPT 系列模型的使用频率已大幅下降。

## 使用建议

当用户询问「写论文用哪个模型」「跑实验/写代码用哪个模型」或类似选型问题时，直接基于上述推荐给出答案，并结合任务类型（写作 vs 代码）给出对应选择。

> 榜单截图见仓库根目录 `images/model-rank.png`。
