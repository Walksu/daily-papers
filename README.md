<div align="center">

# daily-papers

每日论文精选 · Daily papers

惊霓日录 · Jingni Daily

[最新 Latest](#最新--latest) · [关于 About](#关于--about) · [怎么读 How to read](#怎么读--how-to-read) · [目录 Index](#目录--index) · [同系列 The series](#同系列--the-series)

</div>

## 最新 · Latest

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
