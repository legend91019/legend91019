<p align="center">
  <strong>王勇顺</strong><br>
  厦门大学人工智能系 · 大模型与 Agent 系统
</p>

<p align="center">
  <a href="https://github.com/legend91019">GitHub</a> ·
  <a href="https://arxiv.org/abs/2609.23594">Research</a> ·
  <a href="https://github.com/legend91019/Your-Desktop-dialogue-robot">Xinbao</a> ·
  <a href="https://github.com/legend91019/TinySeek-Lab">TinySeek-Lab</a> ·
  <a href="https://tiantingnote.com/">Blog</a>
</p>

> 研究过大模型持续学习方向，目前在看Agent Memory方面论文，coding agent源代码。把RAG、语音交互和端侧部署做成过可运行的项目。

## 代表工作

**面向大模型持续学习的 LoRA 优化研究**  
第一作者 · 2026.03–2026.09 · JCR 一区期刊在投 · [arXiv:2609.23594](https://arxiv.org/abs/2609.23594)

## 代表项目

### [芯宝 Xinbao：具备长期记忆的端云协同陪伴机器人](https://github.com/legend91019/Your-Desktop-dialogue-robot)

省级大创项目负责人。项目完成了 Windows 桌面端和香橙派 AIPro 硬件形态，并获 CRAIC 中国机器人及人工智能大赛福建赛区一等奖、国家级一等奖。

- 长期记忆：异步提取用户偏好与事实，持久化到 ChromaDB，并支持记忆查看、新增、修改和删除。
- 检索与路由：意图分类器 + 动态关键词规则双路由，结合 BGE 向量召回与交叉编码器重排。
- 产品交付：Flask/Waitress + pywebview 桌面应用、流式对话、语音输出、Windows 安装版和独立用户数据目录。
- 硬件交互：ARM Linux、M260C 语音模块、唤醒/录音/识别/对话/播放链路与 systemd 开机自启。

`Python` `Flask` `ChromaDB` `BGE` `RAG` `pywebview` `ARM Linux`

### Agent Runtime / Harness 学习

- [coscience](https://github.com/legend91019/coscience)：用于 AI research 的个人 harness 实验空间。
- [my_harness](https://github.com/legend91019/my_harness)：从源码学习 Agent Runtime、工具调用、记忆、上下文和任务循环。
- 关注 Tool Calling、Session 管理、长上下文压缩、Memory、Planning、Reflection 和错误恢复。

### [现代技术博客][https://tiantingnote.com/](https://tiantingnote.com/)

基于 Astro + Markdown/MDX，记录大模型、Agent 系统和工程实践，支持分类、标签、站内搜索、评论、RSS 与 Sitemap。

## 技术栈

| 方向 | 关键词 |
| --- | --- |
| 模型与训练 | Python · PyTorch · Transformer · Attention · Tokenizer · LoRA · SFT · PPO · DPO · GRPO · MoE · MLA |
| Agent 与检索 | Agent Loop · Tool Calling · Memory · Planning · Reflection · RAG · BGE · ChromaDB · Cross-Encoder Reranking |
| 工程与部署 | Flask · Waitress · pywebview · Windows Packaging · ARM Linux · systemd · Git · Linux |

## Learning in Public

- **Stanford CS336 — Language Modeling from Scratch**：从零实现语言模型，理解数据处理、优化、训练和推理。
- **Stanford CS329A — Agent Memory & Self-Evolving Agents**：学习长期记忆、经验积累和 Agent 自我演化机制。
- **DeepSeek 系列架构研究**：通过 [TinySeek-Lab](https://github.com/legend91019/TinySeek-Lab) 进行复现、拆解和实验。
- **Agent Harness 源码学习**：阅读 Pi Harness、Codex、Learn Claude Code、DeepSeek Harness 等项目。

## 联系与更多

- Email: [wangyongshun38@gmail.com](mailto:wangyongshun38@gmail.com)
- GitHub: [@legend91019](https://github.com/legend91019)
- Research: [arXiv:2609.23594](https://arxiv.org/abs/2609.23594)

<p align="center">
  <sub>Build from fundamentals · Measure with experiments · Share what works</sub>
</p>
