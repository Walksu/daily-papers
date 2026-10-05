<div align="center">

# daily-papers

每日论文精选 · Daily papers

惊霓日录 · Jingni Daily

[最新 Latest](#最新--latest) · [关于 About](#关于--about) · [怎么读 How to read](#怎么读--how-to-read) · [目录 Index](#目录--index) · [同系列 The series](#同系列--the-series)

</div>

## 最新 · Latest

## 2026-10-05

- [Multi-Agent Computer Use](https://arxiv.org/abs/2606.01533)
  - 中文：CMU 多 agent CUA，Odysseys 8.5→34.0，长程 CUA 默认改编排｜不要并进单 agent GUI grounding，也不绑 CMU A2
  - English: CMU multi-agent CUA lifts Odysseys 8.5→34.0; long-horizon CUA should rewrite the schedule by default—not single-agent GUI grounding, and not tied to CMU A2.

- [The Interaction Tax: When Communication Erases Diversity in Multi-Agent Teams](https://arxiv.org/abs/2608.23541)
  - 中文：ICML：全解交流一轮抹平多样性，首轮互评 57% 改差｜不要并进「多 agent 一律无用」的等预算否定论
  - English: ICML: one full-solution exchange flattens diversity; first-round peer review makes 57% worse—not an equal-budget claim that multi-agent is always useless.

- [Rethinking the Evaluation of Harness Evolution for Agents](https://arxiv.org/abs/2607.12227)
  - 中文：AI2/UW：harness 进化在等预算下 67.4 < 并行采样 72.3｜不要并进 harness 学习类（2609.35738）
  - English: AI2/UW: under equal budget, harness evolution scores 67.4 vs parallel sampling 72.3—not merged with harness-learning work (2609.35738).

- [Despite Instructions: Frontier Agents Improvise Covert Channels at Test Time](https://arxiv.org/abs/2609.32701)
  - 中文：1 位反馈就长出隐蔽信道，98.8% vs 25%，监控失效｜不要并进 Covert Assistance 2609.39050
  - English: One bit of feedback grows a covert channel (98.8% vs 25%); monitoring fails—not merged with Covert Assistance 2609.39050.

- [Trojan Hippo Bench: A Dynamic Benchmark for Persistent Memory Attacks and Defenses in LLM Agents](https://arxiv.org/abs/2605.01970)
  - 中文：ETH/Berkeley：持久记忆投毒最高 100% ASR，潜伏 100 会话仍生效｜不要并进 ZoneClaw 2610.00450
  - English: ETH/Berkeley: persistent memory poisoning reaches 100% ASR and still works after 100 dormant sessions—not merged with ZoneClaw 2610.00450.

- [Can Agent Memory Systems Track Evolving State?](https://arxiv.org/abs/2608.19652)
  - 中文：UIUC：记忆追当前态，准确率 1.8×，状态结构贡献 +15–32｜不要并进 PoS 2610.01415 和长上下文 QA
  - English: UIUC: memory that tracks the current state gets 1.8× accuracy; state structure adds +15–32—not merged with PoS 2610.01415 or long-context QA.

- [CoopEval: Benchmarking Cooperation-Sustaining Mechanisms and LLM Agents in Social Dilemmas](https://arxiv.org/abs/2604.15267)
  - 中文：ICML：LLM 单次博弈全背叛，合同机制回收 80% 社会最优｜不要并进单 agent 价值对齐评测
  - English: ICML: LLMs fully defect in one-shot games; contract mechanisms recover 80% of the social optimum—not single-agent value-alignment evals.

- [When Successful Strategies Fail: Adaptation to Environmental Novelty in Terminal Agents](https://arxiv.org/abs/2609.33870)
  - 中文：环境新颖性让终端 agent pass@1 84.1→53.4｜不要并进跨榜迁移稿 2610.00890
  - English: Environmental novelty drops terminal-agent pass@1 from 84.1 to 53.4—not merged with cross-benchmark transfer 2610.00890.

- [SecOPD: Mitigating Adaptive Prompt Injections by On-Policy Distillation](https://arxiv.org/abs/2608.21500)
  - 中文：EMNLP：token 级 on-policy 蒸馏把自适应注入 ASR 94.0%→9.0%｜不要并进 UCM 和通用 OPD 训练稿
  - English: EMNLP: token-level on-policy distillation cuts adaptive-injection ASR from 94.0% to 9.0%—not merged with UCM or generic OPD training papers.

- [AgentBoundary: Counterfactual Evaluation of Safety in Tool-Using LLM Agents](https://arxiv.org/abs/2609.33658)
  - 中文：北大：GPT-5.5 拦越权 99.5%，风险外观授权任务只完成 28.7%｜不要并进对话越狱拒答基准
  - English: PKU: GPT-5.5 blocks over-privilege at 99.5%, but completes only 28.7% of risk-looking authorized tasks—not a chat jailbreak-refusal bench.

- [Beyond the Payload: How User Invocation Shapes Coding Agent Vulnerability to Repository Poisoning](https://arxiv.org/abs/2608.30686)
  - 中文：EMNLP：投毒 ASR 由用户任务类型决定，跑测试 45.5% vs 修 bug 8.6%｜不要并进 skill 供应链和网页注入
  - English: EMNLP: poison ASR depends on the user task type—45.5% on running tests vs 8.6% on bugfix—not skill supply-chain or web injection.

- [Harness Learning Enables Generalizable Test-Time Adaptation](https://arxiv.org/abs/2609.35738)
  - 中文：CMU：训出的 4B harness proposer 在未见任务族上胜过 35B 教师（0.62 vs 0.56）｜不要并进同基准搜索型 harness 进化
  - English: CMU: a trained 4B harness proposer beats a 35B teacher on unseen task families (0.62 vs 0.56)—not same-benchmark search-style harness evolution.

- [WHALE: A Simple Recipe for Joint Harness-Weight Optimization](https://arxiv.org/abs/2609.00196)
  - 中文：权重 × harness 交替优化，只用 29% 的 rollout 超过分阶段优化｜不要并进纯提示优化和通用 RLVR
  - English: Alternating weight×harness optimization beats staged training with only 29% of the rollouts—not pure prompt opt or generic RLVR.

- [Untrusted Content Masking for Web Agents with Security Guarantees](https://arxiv.org/abs/2607.05277)
  - 中文：ETH：DOM 结构遮蔽不可信区，加强版 WASP 0% ASR｜不要并进训练型注入防御；写清防不了数据流篡改
  - English: ETH: DOM-structure masking of untrusted regions reaches 0% ASR on a hardened WASP; it does not stop data-flow tampering—not training-time injection defense.

- [FORTIS: Benchmarking Over-Privilege in Agent Skills](https://arxiv.org/abs/2605.09163)
  - 中文：USC/JHU（Chaowei Xiao）：skill 层本身是越权源，10 个模型选 skill 失败 35.5–52.7%，两段合计成功最多 14.3%｜不要并进 TrustProbe 2609.39065、APEX 2610.01564 和 AgentBoundary 2609.33658
  - English: USC/JHU (Chaowei Xiao): the skill layer itself is an over-privilege source; 10 models fail skill selection 35.5–52.7%, two-stage success at most 14.3%—not TrustProbe, APEX, or AgentBoundary.

- [FlowBank: Query-Adaptive Agentic Workflows Optimization through Precompute-and-Reuse](https://arxiv.org/abs/2606.11290)
  - 中文：Furong 组：互补工作流库加路由，比 AFlow 高 3.00 分｜不要并进 FloWright 和 Component Routing
  - English: Furong group: a complementary workflow bank plus routing beats AFlow by 3.00 points—not FloWright or Component Routing.

- [SkillOS: Learning Skill Curation for Self-Evolving Agents](https://arxiv.org/abs/2605.06614)
  - 中文：UIUC/Google：skill 策展可以训，8B 胜过 Gemini-2.5-Pro 当策展器｜不要并进 GSO 和 DeFA
  - English: UIUC/Google: skill curation is trainable; an 8B curator beats Gemini-2.5-Pro—not GSO or DeFA.

- [SWE-chat: Coding Agent Interactions From Real Users in the Wild](https://arxiv.org/abs/2604.20779)
  - 中文：COLM：真实用户 coding agent 代码只有 59% 进 commit｜不要并进离线 SWE 基准
  - English: COLM: only 59% of real-user coding-agent code reaches a commit—not offline SWE benches.

- [Benchmarking Open-Ended Multi-Agent Coordination in Language Agents](https://arxiv.org/abs/2606.08340)
  - 中文：Edinburgh/UCL：LLM 团队协调分逼近 10 亿步 MARL，断通信 17.5→5.3｜不要并进 MACU 和 CoopEval
  - English: Edinburgh/UCL: LLM team coordination scores approach billion-step MARL; cutting communication drops 17.5→5.3—not MACU or CoopEval.

- [StepGuard: Learning Step-Level Guardrails with Scalable Supervision and Safety-Utility Balancing](https://arxiv.org/abs/2608.24777)
  - 中文：EMNLP：步级执行前护栏，ASR 相对 −77.3%、效用 −2.8｜不要并进 AgentBoundary 评测
  - English: EMNLP: step-level pre-execution guardrails cut ASR by 77.3% relative with −2.8 utility—not AgentBoundary eval.

- [CompactionRL: Reinforcement Learning with Context Compaction for Long-Horizon Agents](https://arxiv.org/abs/2607.05378)
  - 中文：清华：压缩上下文的 agent RL，SWE-V 比推理时压缩高 +6.6｜不要并进通用长上下文和 RLVR 训练稿
  - English: Tsinghua: agent RL with context compaction beats inference-time compaction by +6.6 on SWE-V—not generic long-context or RLVR training papers.

- [Can Agents Trust Their Skills? Uncovering Unsafe Chains of Trust in Skill-Based LLM Agents](https://arxiv.org/abs/2609.39065)
  - 中文：中科院信工所：skill 准入通道本身是漏洞，直接提示只复现 31.7%｜不要并进 APEX 2610.01564 和仓库投毒
  - English: CAS IIE: the skill admission channel itself is a vulnerability; direct prompting only reproduces 31.7%—not APEX 2610.01564 or repo poisoning.

- [VibeMemBench: Evaluating Memory Systems for Coding Agents on Real Repository Coding Tasks](https://arxiv.org/abs/2609.23570)
  - 中文：SIAT/阿里：coding agent 记忆增益 1.1–4.5 分，置信区间全跨零｜不要并进 StateMemBench 和对话记忆榜
  - English: SIAT/Alibaba: coding-agent memory gains 1.1–4.5 points with CIs that all cross zero—not StateMemBench or dialogue-memory boards.

- [How Much Is an AI Token Worth? Scaling Laws for Wild AI-Generated Web Text](https://arxiv.org/abs/2609.40295)
  - 中文：UMD/Mohit Iyyer：800 个模型测出数据充足后 AI 网页 token 价值为负，新 scaling law 外推误差低 41%｜不要并进 FinePhrase（2604.13977）和 model-collapse 研究
  - English: UMD/Mohit Iyyer: across 800 models, AI web tokens turn negative once data is plentiful; a new scaling law cuts extrapolation error 41%—not FinePhrase or model-collapse work.

- [Broken Symmetry in BF16 Attention: Why FlashAttention Gradients Blow Up Late in Training](https://arxiv.org/abs/2609.34272)
  - 中文：Rutgers/CMU（Eric Xing）：BF16 FA3 梯度泄漏均值 key，GProj 把 q 梯度误差 219%→0.34%｜不要并进 Muon / 学习率类不稳定研究
  - English: Rutgers/CMU (Eric Xing): BF16 FA3 gradients leak the mean key; GProj cuts q-gradient error from 219% to 0.34%—not Muon or LR-instability work.

- [Do We Really Need KL Divergence for On-Policy Distillation of Large Language Models?](https://arxiv.org/abs/2609.33791)
  - 中文：清华 LeapLab/黄高：OPD 用方向 ±1 即可复现 KL，<1.5% 高分歧 token 决定成败｜不要并进 2609.35259 和 2610.02179
  - English: Tsinghua LeapLab/Gao Huang: OPD with ±1 direction recovers KL; <1.5% high-disagreement tokens decide outcomes—not 2609.35259 or 2610.02179.

- [EasyPPO: Stabilizing the Critic Is Key](https://arxiv.org/abs/2609.36802)
  - 中文：Berkeley/Princeton：PPO 不稳源于 critic，actor-only 过滤 + 噪声归一化后三种子零崩溃｜不要并进 Trust the Critic More（2609.39247）
  - English: Berkeley/Princeton: PPO instability comes from the critic; actor-only filtering plus noise normalization yields zero crashes across three seeds—not Trust the Critic More.

- [How Can We Synthesize High-Quality Pretraining Data? A Systematic Study of Prompt Design, Generator Model, and Source Data](https://arxiv.org/abs/2604.13977)
  - 中文：Hugging Face，COLM 2026：合成预训练改写器 1B 反超 27B，FinePhrase 生成成本降 30×｜不要并进野生 AI 文本研究（2609.40295）和 PPT（2609.39827）
  - English: Hugging Face, COLM 2026: a 1B synthetic pretraining rewriter beats a 27B; FinePhrase cuts generation cost 30×—not wild AI-text work or PPT.

- [Trust the Critic More](https://arxiv.org/abs/2609.39247)
  - 中文：Stanford/Tengyu Ma：critic 就绪后截断 rollout，达到 GRPO 峰值少用 2.5× 解码 FLOPs｜不要并进 EasyPPO（2609.36802）
  - English: Stanford/Tengyu Ma: truncate rollouts once the critic is ready; reach GRPO peak with 2.5× fewer decode FLOPs—not EasyPPO.

- [The Quality-Utility Paradox: Why High-Reward Data Impairs Small Model Mathematical Reasoning](https://arxiv.org/abs/2606.16152)
  - 中文：清华深研院/MSRA，ICML 2026：RM 分更高的 Oracle 蒸馏数据，小模型反而学得更差｜不要并进 KL-free OPD（2609.33791）和偏好蒸馏 reject 研究
  - English: Tsinghua AIR/MSRA, ICML 2026: higher-RM Oracle distillation data makes small models learn worse—not KL-free OPD or preference-distill reject work.

## 关于 · About

只收当天核过、值得留下的论文。综述、方法、研究和轻观点都可以，但没进日选的标题不进这本。

Papers that cleared the day's selection. Surveys, methods, studies, and lighter notes all qualify. A title that was not selected stays out.

**不收 Left out.** 机构新闻、转述、仓库和访谈不进这本。 Institutional news, retellings, repositories, and interviews stay out.

## 怎么读 · How to read

首页只做目录，当天的条目在 [years/](years) 里，新的日期在上面。一条里，标题就是链接，下面各一句中文和英文。

The front page is the index. A day's entries live in [years/](years), newest date first. The title is the link. Under it, one sentence in Chinese and one in English.

版式长这样。下面不是一条真记录。

The shape looks like this. The block below is not a real entry.

> **2026-01-01**
>
> - [标题放这里 Title goes here](#怎么读--how-to-read)
>   - 中文一句，只说为什么留。
>   - One English sentence on why it stays.

同一天同一个链接只留一次。

The same link is kept once on a given day.

## 目录 · Index

| 年 Year | 档案 File |
| --- | --- |
| 2026 | [years/2026.md](years/2026.md) |

## 同系列 · The series

| 仓库 Repo | 中文 | English |
| --- | --- | --- |
| [daily-papers](https://github.com/Walksu/daily-papers) | 论文精选 | Papers |
| [daily-repos](https://github.com/Walksu/daily-repos) | 优质仓库 | Repositories |
| [daily-guides](https://github.com/Walksu/daily-guides) | 教程与路线 | Guides |
| [daily-brief](https://github.com/Walksu/daily-brief) | 资讯 | Briefing |
| [daily-voices](https://github.com/Walksu/daily-voices) | 访谈与播客 | Voices |
| [daily-essays](https://github.com/Walksu/daily-essays) | 本人博客 | Essays |
| [daily-signals](https://github.com/Walksu/daily-signals) | 机构与学者信号 | Signals |
