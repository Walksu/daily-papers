<div align="center">

# daily-papers

每日论文精选 · Daily papers

惊霓日录 · Jingni Daily

[最新 Latest](#最新--latest) · [关于 About](#关于--about) · [怎么读 How to read](#怎么读--how-to-read) · [目录 Index](#目录--index) · [同系列 The series](#同系列--the-series)

</div>

## 最新 · Latest

## 2026-10-08

- [SquidAgent: Parallelize Wisely, Coordinate Efficiently](https://arxiv.org/abs/2610.08647)
  - 中文：悉尼大学/港浸会，NeurIPS：只在「关键路径 + 重探索 + 对齐」比串行便宜时才并行，墙钟比 Claude Code 快 2.6×｜不要并进 AECP 2610.06481 和 GitSwarm 2610.04862
  - English: Sydney/HKBU, NeurIPS: parallelize only when critical path plus re-exploration plus alignment beats serial cost; 2.6× faster wall-clock than Claude Code—not AECP 2610.06481 or GitSwarm 2610.04862.

- [Stateless Language Agents: Scaling Long-Horizon Automated Research](https://arxiv.org/abs/2610.07625)
  - 中文：Stanford Olukotun：研究状态归 harness、agent 无状态，追平最强基线少用 93% token｜不要并进 Sentry 2610.02994 和 MIRA 2610.02525
  - English: Stanford Olukotun: research state lives in the harness and agents are stateless; matches the strongest baseline with 93% fewer tokens—not Sentry 2610.02994 or MIRA 2610.02525.

- [Why Search When You Can Transfer? Amortized Agentic Workflow Design from Structural Priors](https://arxiv.org/abs/2604.25012)
  - 中文：CMU FOCAL：工作流单次生成免搜索，85.34 对 AFlow 82.25，184 分钟降到 10 秒以内｜不要并进 2609.02264 和 FlowBank 2606.11290
  - English: CMU FOCAL: one-shot workflow generation with no search; 85.34 vs AFlow 82.25, from 184 minutes to under 10 seconds—not 2609.02264 or FlowBank 2606.11290.

- [Who is the Agent to Blame? Localizing Faithfulness and Citation Mistakes in Agentic Deep Research](https://arxiv.org/abs/2608.24306)
  - 中文：Bar-Ilan/UNC，EMNLP：逐调用定位深度研究错误，AI-Q 84.7% 出在 orchestrator｜不要并进 DeFA 2610.01256 和 2606.03032
  - English: Bar-Ilan/UNC, EMNLP: localizes deep-research errors call by call; 84.7% of AI-Q errors come from the orchestrator—not DeFA 2610.01256 or 2606.03032.

- [MANTA: Multi-Agent Network Topology Adaptation for Self-Evolving Multi-Agent Systems](https://arxiv.org/abs/2607.28527)
  - 中文：Cornell：推理期拓扑自进化，均分 74.0（+5.8），去掉开局规划掉到 57.5｜不要并进 SHIFT 2610.04137 和 ReActNet 2609.05774
  - English: Cornell: inference-time self-evolving topology; average 74.0 (+5.8), dropping to 57.5 without upfront planning—not SHIFT 2610.04137 or ReActNet 2609.05774.

- [Fork-and-Flush: Escaping Idea Basins in Autoresearch Agents](https://arxiv.org/abs/2610.07447)
  - 中文：MSR：autoresearch 的想法盆地，分叉加清空对话 0.78 对单次 0.47｜不要并进 2607.12227 和 SLA 2610.07625
  - English: MSR: idea basins in autoresearch; fork-and-flush scores 0.78 vs 0.47 for a single run—not 2607.12227 or SLA 2610.07625.

- [Self-Retrospection Distillation: Turning Post-hoc Experiences into Prior Foresight](https://arxiv.org/abs/2610.08077)
  - 中文：Salesforce：事后经验蒸馏成事前预判，2B 从 0.0% 到 60.6%｜不要并进 RISED 2610.00979 和训练线
  - English: Salesforce: distills post-hoc experience into prior foresight; a 2B model goes from 0.0% to 60.6%—not RISED 2610.00979 or the training line.

- [ServeLearnBench: How Well Can Agents Self-Improve from Serving Experience?](https://arxiv.org/abs/2610.07792)
  - 中文：CMU Beidi Chen：服务经验自改进基准，规则公开 95.4 对自学 14.1｜不要并进 2606.04315 和 2606.15017
  - English: CMU Beidi Chen: a benchmark for self-improving from serving experience; 95.4 with rules given vs 14.1 self-learned—not 2606.04315 or 2606.15017.

- [Inducing Task Models from Computer-Use Traces](https://arxiv.org/abs/2608.20319)
  - 中文：Stanford Diyi Yang/CMU：从操作录像归纳任务模型，步骤吻合 74.9% 对 30.3%，skill +30%｜不要并进 TeleTune 2610.05437
  - English: Stanford Diyi Yang/CMU: induces task models from computer-use recordings; step match 74.9% vs 30.3%, skills +30%—not TeleTune 2610.05437.

- [Surviving the Router: Optimizing Skill Injections for Retrieval and Execution](https://arxiv.org/abs/2610.08098)
  - 中文：ELLIS Tübingen：skill 注入先过路由，已有攻击 ASR 掉 87–97%｜不要并进 2605.09163 和 2609.35912
  - English: ELLIS Tübingen: skill injections must survive the router first; existing attacks lose 87–97% ASR—not 2605.09163 or 2609.35912.

- [Daydreaming: Stealing Hidden Agent Skills through Black-Box Task Interaction](https://arxiv.org/abs/2608.26733)
  - 中文：Berkeley Popa：只靠任务往返偷 skill，恢复 86.8% 能力，中位数 32 次调用｜不要并进 2609.39065 和 CORSA 2610.08098
  - English: Berkeley Popa: steals skills through task round-trips alone, recovering 86.8% of capability in a median of 32 calls—not 2609.39065 or CORSA 2610.08098.

- [Prismata: Confining Cross-Site Prompt Injection in Web Agents](https://arxiv.org/abs/2607.08147)
  - 中文：Berkeley Popa：网页 agent 上下文最小权限，ASR 85.5% 降到 0.7%｜不要并进 2607.05277
  - English: Berkeley Popa: least-privilege context for web agents cuts ASR from 85.5% to 0.7%—not 2607.05277.

- [RAISED: Self-Distillation for Robustness to Prompt Injection in LLM Agents](https://arxiv.org/abs/2610.06401)
  - 中文：巴黎综合理工/GDM：自蒸馏防注入，ASR 39.5% 降到 1.0%，受攻击效用 64.0% 升到 80.5%｜不要并进 SecOPD 2608.21500 和训练线
  - English: École Polytechnique/GDM: self-distillation against injection; ASR 39.5% to 1.0%, utility under attack 64.0% to 80.5%—not SecOPD 2608.21500 or the training line.

- [HarnessSecurity-Bench: Do Security Mechanisms Really Protect Coding Agent Harnesses?](https://arxiv.org/abs/2610.07639)
  - 中文：中山大学：6 个 coding harness 安全实测，auto-approve 让 ASR 从 29.2% 升到 95.6%｜不要并进 2606.30755 和 CUAWright 2610.04116
  - English: Sun Yat-sen: security tests on 6 coding harnesses; auto-approve raises ASR from 29.2% to 95.6%—not 2606.30755 or CUAWright 2610.04116.

- [Discovered, Not Designed: Population Evolution for Collaborative and Compute-Intensive Model Discovery](https://arxiv.org/abs/2610.05950)
  - 中文：Meta：种群协同进化，预训练最佳增益 2.48% 对 0.92%｜不要并进 DarwinX 2608.07545 和训练线
  - English: Meta: population co-evolution; best pretraining gain 2.48% vs 0.92%—not DarwinX 2608.07545 or the training line.

- [XBridge: Entity-Grounded Latent Bridge for Heterogeneous LLM Communication](https://arxiv.org/abs/2608.11676)
  - 中文：UIC，NeurIPS：异构隐空间桥加离散锚点，比自然语言通信高 14–21 个点，延迟低 11×｜不要并进 2609.39788 和 2610.03769
  - English: UIC, NeurIPS: a heterogeneous latent bridge with discrete anchors; 14–21 points above natural-language communication at 11× lower latency—not 2609.39788 or 2610.03769.

- [Decoupled Multi-Agent Orchestration](https://arxiv.org/abs/2610.07556)
  - 中文：NUS：规划与选人解耦，51.5 对 Conductor 44.0｜不要并进 MIRA 2610.02525 和 AECP 2610.06481
  - English: NUS: decouples planning from agent selection; 51.5 vs Conductor 44.0—not MIRA 2610.02525 or AECP 2610.06481.

- [Large Language Model Orchestration under Heterogeneous Preferences via Explicit Persona Inference](https://arxiv.org/abs/2610.07587)
  - 中文：KCL/Harvard：数值后验取代提示词信念，遗憾 2.7–4.4 对 4.5–10.7｜不要并进 2604.15267 和 2610.07556
  - English: KCL/Harvard: numeric posteriors replace prompted beliefs; regret 2.7–4.4 vs 4.5–10.7—not 2604.15267 or 2610.07556.

- [Persistent Memory in Multi-Agent LLM Inference: What It Costs, What It Buys, and When You Can Tell](https://arxiv.org/abs/2610.07782)
  - 中文：UCLA：多 agent 推理的持久记忆层零收益（+0.015），检索可达率只有 24%｜不要并进 2609.23570 和 2610.07792
  - English: UCLA: a persistent memory layer for multi-agent inference yields essentially nothing (+0.015), with only 24% retrieval reachability—not 2609.23570 or 2610.07792.

- [Better, Faster, Stronger: Programmatic Skill Learning Best Reduces Agent Cost](https://arxiv.org/abs/2608.11338)
  - 中文：JHU：程序化 skill 最省钱，输出 token 少约 65%｜不要并进 VALVE 2609.32990 和 SkillOS 2605.06614
  - English: JHU: programmatic skills are cheapest, with about 65% fewer output tokens—not VALVE 2609.32990 or SkillOS 2605.06614.

- [Agent in a Bottle: Can LLM Agents Turn Their Capabilities Into Cheap, Scalable Artifacts?](https://arxiv.org/abs/2610.08775)
  - 中文：Tübingen/KAIST Seong Joon Oh：装瓶能力评测，48/60 低于零样本下界｜不要并进 2609.34262 和训练线蒸馏
  - English: Tübingen/KAIST Seong Joon Oh: evaluating bottled capabilities; 48 of 60 fall below the zero-shot floor—not 2609.34262 or training-line distillation.

- [Understanding and Enhancing Backdoor Persistency in LLM Agent Post-Training](https://arxiv.org/abs/2610.07510)
  - 中文：UIUC Daniel Kang，EMNLP Findings：后门熬过 SFT，RL 不降反升｜不要并进 2608.25776 和训练线
  - English: UIUC Daniel Kang, EMNLP Findings: backdoors survive SFT and grow stronger under RL—not 2608.25776 or the training line.

- [Before Agent Tells The Lie: Has Deception Already Been Represented?](https://arxiv.org/abs/2610.06576)
  - 中文：上海 AI Lab：欺骗在决策前已可从隐状态读出，AUROC 51.2% 升到 80.0%｜不要并进 2607.26115 和 2610.04083
  - English: Shanghai AI Lab: deception is readable from hidden states before the decision; AUROC rises from 51.2% to 80.0%—not 2607.26115 or 2610.04083.

- [Balancing Memory Pathways: Analyzing and Improving Memory Utilization in Hybrid LMs](https://arxiv.org/abs/2610.06750)
  - 中文：UNC/Yale/Mila（Mohit Bansal、Arman Cohan）：混合模型的循环层大半闲置，通路辅助损失让长上下文问答 +8.0｜不要并进 2610.04518 和 2610.08463
  - English: UNC/Yale/Mila (Mohit Bansal, Arman Cohan): recurrent layers in hybrid models sit mostly idle; a pathway auxiliary loss adds +8.0 on long-context QA—not 2610.04518 or 2610.08463.

- [On-Policy Distillation with Negative-Policy Rollouts](https://arxiv.org/abs/2610.07874)
  - 中文：NAVER AI Lab：OPD 加负策略 rollout，Qwen3-4B 数学 62.2 升到 70.5｜不要并进 2610.04272 和 2609.33791
  - English: NAVER AI Lab: on-policy distillation with negative-policy rollouts lifts Qwen3-4B math from 62.2 to 70.5—not 2610.04272 or 2609.33791.

- [UNREAL: Unifying Retrieval and Long-Context with a Single Model](https://arxiv.org/abs/2610.08463)
  - 中文：NVIDIA（Soudry、Ginsburg）：冻结 LLM 加不到 0.5M 参数当全库检索器，NoLiMa 128K 从 1.0% 到 24.83%｜不要并进 agent 线的记忆与 RAG 评测
  - English: NVIDIA (Soudry, Ginsburg): a frozen LLM plus under 0.5M parameters becomes a full-corpus retriever; NoLiMa 128K from 1.0% to 24.83%—not agent-line memory and RAG evals.

- [The Assistance Dilemma: Learning to Teach via Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2610.06446)
  - 中文：ETH（Mrinmaya Sachan）：教学 RL 加迁移后测和硬闸，不加闸时仍有 61% 直接给答案｜不要并进 OnePO 2610.05966 和 agent 评测稿
  - English: ETH (Mrinmaya Sachan): teaching RL with transfer post-tests and a hard gate; without the gate 61% still hand over the answer—not OnePO 2610.05966 or the agent eval piece.

- [Exploration-Preserving Policy Optimization](https://arxiv.org/abs/2610.04011)
  - 中文：Mila（Doina Precup）：按惊异度和通过率重分功劳，k=128 覆盖 51.03 对 44.34｜不要并进 2610.00991 和 2610.01509
  - English: Mila (Doina Precup): reassigns credit by surprisal and pass rate; coverage at k=128 is 51.03 vs 44.34—not 2610.00991 or 2610.01509.

- [TRACE: Rollout-Guided Quantization-Aware Training for FP4 Reinforcement Learning of MoE Language Models](https://arxiv.org/abs/2610.07767)
  - 中文：阿里 Qwen：rollout 引导的 FP4 QAT，NVFP4 rollout 均分 75.3 超过 BF16 的 74.9｜不要并进 2609.22870 和 2610.07043
  - English: Alibaba Qwen: rollout-guided FP4 QAT; NVFP4 rollouts average 75.3, above BF16 at 74.9—not 2609.22870 or 2610.07043.

- [Language Models that Play Chess and Explain Their Moves](https://arxiv.org/abs/2610.03695)
  - 中文：Princeton（Danqi Chen）：自然语言版 Bellman 迭代蒸馏，4B 从 1782 Elo 到 2697｜不要并进 2610.06851 和 agent 自进化稿
  - English: Princeton (Danqi Chen): natural-language Bellman iteration distillation takes a 4B model from 1782 to 2697 Elo—not 2610.06851 or the agent self-evolution piece.


## 2026-10-07

- [GitSwarm: Decentralized Compounding Inference](https://arxiv.org/abs/2610.04862)
  - 中文：Meta MSL：共享 Git 仓库的复利式推理，ProgramBench 79.4% 对 65.1%，94.7% 的贡献被复用｜不要并进 MACU 2606.01533 和训练线 test-time scaling
  - English: Meta MSL: compounding inference via a shared Git repo; ProgramBench 79.4% vs 65.1%, 94.7% of contributions reused—not MACU 2606.01533 or training-line test-time scaling.

- [Worse Together: How Performance Breaks Down in Multi-User Multi-Agent Teams](https://arxiv.org/abs/2610.00583)
  - 中文：Anthropic：多用户各派 agent，团队只达到最优的 30%/12%，协调者 64%/32%｜不要并进 CoopEval 2604.15267 和零成本合作 2604.07821
  - English: Anthropic: multi-user each sends an agent; teams reach only 30%/12% of optimum, coordinator 64%/32%—not CoopEval 2604.15267 or zero-cost cooperation 2604.07821.

- [Bayes-Sufficient Compression Is Not Enough: How Does Communication Help Multi-Agent Systems?](https://arxiv.org/abs/2610.03769)
  - 中文：NeurIPS：同一压缩在不同接收方上符号翻转，0.803→1.000 对 0.889→0.653｜不要并进 Interaction Tax 2608.23541 和 UCLA 拓扑 2609.02264
  - English: NeurIPS: the same compression flips signs across receivers, 0.803→1.000 vs 0.889→0.653—not Interaction Tax 2608.23541 or UCLA topology 2609.02264.

- [Safety of Latent Communication in Multi-Agent Systems](https://arxiv.org/abs/2609.39788)
  - 中文：CISPA：良性训练隐空间连接层，有害顺从从 4.4 升到 31.1，RL 攻击推到 76.9｜不要并进 Covert Channels 2609.32701
  - English: CISPA: benign training of a latent linking layer; harmful compliance 4.4→31.1, RL attack to 76.9—not Covert Channels 2609.32701.

- [MADBench: Benchmarking the Security of Multi-Agent Debate](https://arxiv.org/abs/2609.39146)
  - 中文：清华：辩论吸收 QA 投毒（ASR 为单 agent 的 74%），却把越权读放大 3.09 倍｜不要并进 Consensus Trap 2604.17139 和 Deliberative Illusion 2606.03032
  - English: Tsinghua: debate absorbs QA poisoning (ASR 74% of single-agent) but amplifies unauthorized reads 3.09×—not Consensus Trap 2604.17139 or Deliberative Illusion 2606.03032.

- [When Upstream Messages Override Correct Answers: A Controlled Study of Multi-Agent LLM Collaboration](https://arxiv.org/abs/2609.36855)
  - 中文：中科大/Qwen：上游错消息最多推翻 32% 的正确答案，94% 原样照抄｜不要并进 Deliberative Illusion 2606.03032 和 MADBench 2609.39146
  - English: USTC/Qwen: upstream wrong messages overturn up to 32% of correct answers; 94% copied verbatim—not Deliberative Illusion 2606.03032 or MADBench 2609.39146.

- [VERSE: Verified Self-Evolving Optimizer for Agent Harnesses](https://arxiv.org/abs/2610.02616)
  - 中文：MIT/Amazon：harness 优化器先验证再进化，OOD 37.7% 对 29.3%，不验证增益从 5.2 掉到 1.2｜不要并进 Rethinking Harness Evolution 2607.12227 和 DarwinX 2608.07545
  - English: MIT/Amazon: harness optimizer verifies before evolving; OOD 37.7% vs 29.3%, without verify gain 5.2→1.2—not Rethinking Harness Evolution 2607.12227 or DarwinX 2608.07545.

- [TeleTune: Evolving Agent Skills From Offline Telemetry](https://arxiv.org/abs/2610.05437)
  - 中文：UNC/Microsoft：离线遥测加 held-out 动作预测闸进化 skill，WorkArena L1 92.3%（+12.0）｜不要并进 SkillOS 2605.06614 和 VALVE 2609.32990
  - English: UNC/Microsoft: offline telemetry plus held-out action-prediction gate evolves skills; WorkArena L1 92.3% (+12.0)—not SkillOS 2605.06614 or VALVE 2609.32990.

- [HERA: Harness-Environment Co-Evolution for Reliable Agentic Abstention](https://arxiv.org/abs/2610.06563)
  - 中文：UW/CMU/Stanford：harness 与环境共进化，held-out 弃答从 61.7 到 83.3｜不要并进 VERSE 2610.02616 和 Harness Learning 2609.35738
  - English: UW/CMU/Stanford: harness–environment co-evolution; held-out abstention 61.7→83.3—not VERSE 2610.02616 or Harness Learning 2609.35738.

- [The Optimizer Is the Agent: Reasoning-Driven Search across Prompts, Programs, and ML Workflows](https://arxiv.org/abs/2608.06714)
  - 中文：COLM：优化器就是 agent，TB2 53.3 对 GEPA 42.2｜不要并进 VERSE 2610.02616、SHarP 2610.04178 和 AutoSaddler 2608.23041
  - English: COLM: the optimizer is the agent; TB2 53.3 vs GEPA 42.2—not VERSE 2610.02616, SHarP 2610.04178, or AutoSaddler 2608.23041.

- [Sentry: Learning to Recover from LLM Agent Failures at Test Time](https://arxiv.org/abs/2610.02994)
  - 中文：Stanford：失败教训常驻 playbook 会伤分，按需恢复比 ACE 高 39%｜不要并进 TeleTune 2610.05437 和 Filesystem Memory 2607.26637
  - English: Stanford: persistent failure lessons in a playbook can hurt; on-demand recovery beats ACE by 39%—not TeleTune 2610.05437 or Filesystem Memory 2607.26637.

- [HASTE: Evolving Agent Harnesses Against Emerging Attacks Using Sparse Evidence](https://arxiv.org/abs/2610.02920)
  - 中文：中科大：稀疏证据进化防御 harness，ASR 从 51.39 降到 28.50，效用不降｜不要并进 Defense-as-Skill 2609.01487 和 VERSE 2610.02616
  - English: USTC: sparse-evidence evolution of defense harnesses; ASR 51.39→28.50 without utility loss—not Defense-as-Skill 2609.01487 or VERSE 2610.02616.

- [Self-Propagating Misalignment in LLM Agents, and Why Auditing or Disabling Memory Is Not Enough](https://arxiv.org/abs/2610.04083)
  - 中文：Anthropic：失准行为经记忆自传播，审计后仍有 34%，禁用记忆后还有 11%｜不要并进 Trojan Hippo 2605.01970 和 EVOMAL 2608.25776
  - English: Anthropic: misaligned behavior self-propagates via memory; 34% after audit, 11% with memory disabled—not Trojan Hippo 2605.01970 or EVOMAL 2608.25776.

- [Filesystem-Based Memory for LLM Agents: Organization, Evolution, and Sustainability](https://arxiv.org/abs/2607.26637)
  - 中文：UIUC/UCSD：原样存档胜过 agent 整理，PersonaMem 78.1 对 37.5｜不要并进 MSU 记忆诊断 2606.04315 和 Caltech 知识库 2607.19592
  - English: UIUC/UCSD: raw archives beat agent-organized memory; PersonaMem 78.1 vs 37.5—not MSU memory diagnostics 2606.04315 or Caltech knowledge base 2607.19592.

- [StateWise: Diagnosing and Repairing Persistent Operational State Before Agent Actions](https://arxiv.org/abs/2610.05241)
  - 中文：浙大：坏记忆删掉也救不回，行动前修复后正确率 93.3% 对 38.7%｜不要并进 MemGate 2606.06054 和 StateMemBench 2608.19652
  - English: Zhejiang: deleting bad memory does not save you; pre-action repair reaches 93.3% vs 38.7%—not MemGate 2606.06054 or StateMemBench 2608.19652.

- [CUAWright: A Minimal Unified Interface for Digital Agents](https://arxiv.org/abs/2610.04116)
  - 中文：MSR/OSU：3K 行 bash-only 接口，77.5% 对 GUI 33.5%，胜过 Codex harness｜不要并进脚手架过拟合 2608.06113，不绑 CMU A2
  - English: MSR/OSU: 3K-line bash-only interface; 77.5% vs GUI 33.5%, beats Codex harness—not scaffold overfitting 2608.06113; not tied to CMU A2.

- [Securing Computer-Use Agents Against Branch Steering Attacks](https://arxiv.org/abs/2610.03089)
  - 中文：Cambridge/ETH：分支劫持对 ReAct 的 ASR 94.4%，COBRA 在 1,259 个攻击上 0%｜不要并进 CaMeLs 2610.05640 和 Plan-then-Execute 2605.14290
  - English: Cambridge/ETH: branch-hijack ASR 94.4% on ReAct; COBRA 0% on 1,259 attacks—not CaMeLs 2610.05640 or Plan-then-Execute 2605.14290.

- [MMSkillRisk: Can Agents Stay Safe When Multimodal Skills Become Traps?](https://arxiv.org/abs/2609.35912)
  - 中文：浙大/蚂蚁：skill 图片载荷 ASR 43.1%，比文字高 16.4 个点｜不要并进 SkillShift 2609.02564 和 EVOMAL 2608.25776
  - English: Zhejiang/Ant: skill image payloads ASR 43.1%, +16.4 pts over text—not SkillShift 2609.02564 or EVOMAL 2608.25776.

- [When Order Matters: First-Speaker Bias and Mitigation through Personality in Sequential Multi-Agent Debate](https://arxiv.org/abs/2609.38964)
  - 中文：NUS：强模型先发言影响力高 21.01 个点，准确率 68.78 对 66.43｜不要并进 Upstream Override 2609.36855 和 Consensus Trap 2604.17139
  - English: NUS: strong model speaking first raises influence +21.01 pts; accuracy 68.78 vs 66.43—not Upstream Override 2609.36855 or Consensus Trap 2604.17139.

- [Can CaMeLs Talk? Securing Multi-Agent Systems Against Indirect Prompt Injection Attacks](https://arxiv.org/abs/2610.05640)
  - 中文：Oxford：CaMeL 安全不可跨 agent 组合，multi-CaMeL 补上，额外代价 −3.2｜不要并进 Systems Problem 2605.18991 和 Delegated Misalignment 2609.27900
  - English: Oxford: CaMeL safety does not compose across agents; multi-CaMeL fixes it at −3.2 extra cost—not Systems Problem 2605.18991 or Delegated Misalignment 2609.27900.

- [SHarP: Saliency-based Pruning of Agent Harnesses](https://arxiv.org/abs/2610.04178)
  - 中文：UCSB：OpenHands 剪掉 24/27 个模块，GAIA 从 29.44% 升到 35.00%｜不要并进 CUAWright 2610.04116 和 ServiceNow 等预算复核 2606.15017
  - English: UCSB: OpenHands pruned of 24/27 modules; GAIA 29.44%→35.00%—not CUAWright 2610.04116 or ServiceNow equal-budget review 2606.15017.

- [GPT-Red: Automated Red Teaming via Self-Play at Scale](https://arxiv.org/abs/2607.26115)
  - 中文：OpenAI：自博弈红队 agent，GPT-5.6 被攻破率 <4%，伪造 CoT 鲁棒性从 5.2% 升到 95.9%｜不要并进训练线和 AutoDojo 2606.15057
  - English: OpenAI: self-play red-team agent; GPT-5.6 break rate <4%; forged-CoT robustness 5.2%→95.9%—not training-line work or AutoDojo 2606.15057.

- [Maintaining Benchmarks Against Increasingly Capable Agents: Detection and Remediation of Unearned Passes](https://arxiv.org/abs/2609.34262)
  - 中文：Scale AI：SWE-Bench Pro 违规率随代际从 24% 升到 73%，基准要持续维护｜不要并进 BenchJack 2605.12673 和 Terminal Novelty 2609.33870
  - English: Scale AI: SWE-Bench Pro violation rate rises 24%→73% across generations; benches need continuous maintenance—not BenchJack 2605.12673 or Terminal Novelty 2609.33870.

- [Base Models Can Reason By Taking a Cue From Training Data](https://arxiv.org/abs/2610.06851)
  - 中文：Berkeley/UW/AI2：base 固定两个起手 token 即追平 RL-Zero（MATH-500 42%→78%），cue 由 mid-training 数据决定｜不要并进 agent 线 prompt 优化和 RLVR 投票（2610.00991）
  - English: Berkeley/UW/AI2: fixing two opening tokens on base matches RL-Zero (MATH-500 42%→78%); cue set by mid-training data—not agent-line prompt optimization or RLVR voting (2610.00991).

- [Rethinking Self-Distillation for Multi-Teacher Capability Merging](https://arxiv.org/abs/2610.04272)
  - 中文：Apple/Duke：调好的 SFT 与 MOPD 恢复率同为 93–99%，MOPD 贵 14.8–23.1×｜不要并进 Switch Distillation（2609.01532）和 OnePO（2610.05966）
  - English: Apple/Duke: tuned SFT and MOPD both recover 93–99%; MOPD costs 14.8–23.1× more—not Switch Distillation (2609.01532) or OnePO (2610.05966).

- [Length Generalization Needs Proper Regularization](https://arxiv.org/abs/2610.04518)
  - 中文：IST Lisbon：长度外推是对 ID 长度过拟合，WD 加速；dropout 挪到线性投影前可外推到 256K｜不要并进 Delta-Matching（2609.37852）和免训练 RoPE 重缩放（2609.39929）
  - English: IST Lisbon: length extrapolation is ID-length overfitting; WD accelerates; dropout before linear projections extrapolates to 256K—not Delta-Matching (2609.37852) or training-free RoPE rescale (2609.39929).

- [ORCA: The Annealed Spectral Conditioning Optimizer for Faster, Better LLM Training](https://arxiv.org/abs/2610.06116)
  - 中文：北大/快手可灵：前期强软正交、后期撤掉，比 Muon 的 loss 再低 0.035｜不要并进 SOLAR（2609.34681）和 MuonIO（2610.02705）
  - English: PKU/Kuaishou Kling: strong soft orthogonality early then remove; loss 0.035 below Muon—not SOLAR (2609.34681) or MuonIO (2610.02705).

- [Adapter Thickets: Splitting an RLVR Budget Beats Concentrating It](https://arxiv.org/abs/2610.00991)
  - 中文：Princeton：RLVR 全预算训一个策略会让投票低于 base，切给 K 个随机分片 LoRA 后 16/16 组投票都赢｜不要并进 cue 研究（2610.06851）和 pass@k 收窄类分析
  - English: Princeton: RLVR full-budget single policy makes voting worse than base; splitting across K random LoRA shards wins 16/16 voting groups—not cue work (2610.06851) or pass@k narrowing analyses.

- [More Than Words: Compositional Tokenization for Efficient Language Models](https://arxiv.org/abs/2610.05597)
  - 中文：希伯来大学，COLM 2026：CoBPE 把功能词与标点做成修饰位，序列短 30%，同算力均分 +1.2｜不要并进 byte 级 LM（2610.05978）和 multi-token prediction
  - English: Hebrew U, COLM 2026: CoBPE makes function words/punctuation modifiers; sequences 30% shorter; +1.2 mean at same compute—not byte-level LM (2610.05978) or multi-token prediction.

- [HuatuoGPT-3: RL-Only Domain Adaptation from Base Models](https://arxiv.org/abs/2610.05966)
  - 中文：港中文（深圳），前身 ICML 2026：OnePO 让老师输出到点退场，HealthBench 67.2 超过 SFT+RL 2.7｜不要并进 MOPD 对比（2610.04272）和医疗评测 benchmark
  - English: CUHK(SZ), formerly ICML 2026: OnePO lets the teacher exit at a stop point; HealthBench 67.2 beats SFT+RL by 2.7—not MOPD comparison (2610.04272) or medical eval benches.

- [Dynamic Harness Search: Building Multi-Agent Systems Per-Query via Prediction](https://arxiv.org/abs/2610.04137)
  - 中文：Google SHIFT（Sercan Arık）：按查询搜多智能体结构，六基准均值 79.9%，比最强基线高 7.2 点｜不要并进 ReActNet 2609.05774 和 CUAWright 2610.04116
  - English: Google SHIFT (Sercan Arık): searches multi-agent structure per query; 79.9% average over six benchmarks, 7.2 points above the strongest baseline—not ReActNet 2609.05774 or CUAWright 2610.04116.

- [Inference-Time Graph Engineering for Multi-Agent LLM Workflows](https://arxiv.org/abs/2609.05774)
  - 中文：Meta ReActNet：给每条边写自然语言指令，六数据集均分 92.75，免训练压过 G-Designer｜不要并进 SHIFT 2610.04137
  - English: Meta ReActNet: writes a natural-language instruction for every edge; 92.75 average over six datasets, beating G-Designer without training—not SHIFT 2610.04137.

- [AECP: Artifact-Exclusive Communication Protocol for Multi-Agent Code Generation](https://arxiv.org/abs/2610.06481)
  - 中文：AWS AI Labs AECP：agent 只用结构化工件协调写仓库，测通率比自由消息团队 +28.2%｜不要并进 GitSwarm 2610.04862 和 CaMeLs
  - English: AWS AI Labs AECP: agents coordinate repo writing only through structured artifacts; test pass rate +28.2% over free-messaging teams—not GitSwarm 2610.04862 or CaMeLs.

- [PANDA: A Decentralized Architecture with Flexible Orchestration for Scalable, Fault-Tolerant Multi-Agent Systems](https://arxiv.org/abs/2609.38482)
  - 中文：Northeastern PANDA（Cristina Nita-Rotaru）：去中心发现组队，比 IoA 快约 3×，基础设施故障下完成率 100% 对基线 0｜不要并进 Worse Together 和 ReActNet 2609.05774
  - English: Northeastern PANDA (Cristina Nita-Rotaru): decentralized discovery and team formation; about 3× faster than IoA, 100% completion under infrastructure failure vs 0 for baselines—not Worse Together or ReActNet 2609.05774.

- [Learning What to Investigate Next: Meta-Reasoning for Long-Horizon Research Agents](https://arxiv.org/abs/2610.02525)
  - 中文：Meta MIRA（Anirudh Goyal）：外环决定下一步查什么，内环干净执行，IMOProofBench 从 67.1% 到 100%｜不要并进 GitSwarm 2610.04862 和 TeleTune 2610.05437
  - English: Meta MIRA (Anirudh Goyal): an outer loop decides what to investigate next and an inner loop executes cleanly; IMOProofBench from 67.1% to 100%—not GitSwarm 2610.04862 or TeleTune 2610.05437.

- [CAPMAS: Capability-Based Delegation of Privileges in Multi-Agent Systems](https://arxiv.org/abs/2609.06500)
  - 中文：EPFL CAPMAS（Rachid Guerraoui）：Macaroon 沿委托链缩权，比 OAuth Token Exchange 快 30×，多余权限砍 99.5%｜不要并进 CaMeLs 和 CISPA 隐空间通信攻击
  - English: EPFL CAPMAS (Rachid Guerraoui): Macaroons narrow privileges along the delegation chain; 30× faster than OAuth Token Exchange, cutting excess privileges by 99.5%—not CaMeLs or the CISPA latent-communication attack.


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
