# 🌐 全球情报日报 (Global Intel Briefing)
**日期:** 2026-11-25
**生成时间:** 05:43
**数据源:** HN, GitHub, 36Kr, WallStreetCN, V2EX, PH, ArXiv, X, TechCrunch, MIT TR

---

## 🛠️ 技术趋势 (Tech Trends)
> Hacker News + GitHub Trending

### 1. [Yale’s Sonnenfeld: Nvidia is a ‘detriment’ to US industrial might — not a champion](https://techcrunch.com/2026/11/24/yales-sonnenfeld-nvidia-is-a-detriment-to-u-s-industrial-might-not-a-champion/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Wed, 25 Nov 2026

### 2. [Trump reportedly says pardoning Jensen Huang is ‘an option’](https://techcrunch.com/2026/11/24/trump-reportedly-says-pardoning-jensen-huang-is-an-option-but-that-he-doesnt-think-it-will-be-necessary/)
📍 TechCrunch | 🔥  | 🕒 Wed, 25 Nov 2026

### 3. [Jensen Huang still thinks a succession plan creates unnecessary hierarchy](https://techcrunch.com/2026/11/24/jensen-huang-still-thinks-a-succession-plan-creates-unnecessary-hierarchy/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Tue, 24 Nov 2026

### 4. [In all-hands meeting, Jensen Huang thanks White House and says he’s in therapy](https://techcrunch.com/2026/11/24/in-all-hands-meeting-jensen-huang-thanks-white-house-and-says-hes-in-therapy/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Tue, 24 Nov 2026

### 5. [Even the best AI agents struggle with everyday life](https://techcrunch.com/2026/11/24/even-the-best-ai-agents-struggle-with-everyday-life/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Tue, 24 Nov 2026

### 6. [Walmart teams up with Meta to bring Black Friday deals to AI agent Muse](https://techcrunch.com/2026/11/24/walmart-teams-up-with-meta-to-bring-black-friday-deals-to-ai-agent-muse/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Tue, 24 Nov 2026

### 7. [Maple raises $5.3M to build AI products that protect your data, even from itself](https://techcrunch.com/2026/11/24/maple-raises-5-3m-to-build-ai-products-that-protect-your-data-even-from-itself/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Tue, 24 Nov 2026

### 8. [Dozens of oil and shipping tankers hacked in recent weeks, per report](https://techcrunch.com/2026/11/24/dozens-of-oil-and-shipping-tankers-hacked-in-recent-weeks-per-report/)
📍 TechCrunch | 🔥  | 🕒 Tue, 24 Nov 2026

### 9. [Anthropic shares fall below IPO price, a worrying sign for AI startups](https://techcrunch.com/2026/11/24/anthropic-shares-fall-below-ipo-price-a-worrying-sign-for-ai-startups/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Tue, 24 Nov 2026

### 10. [UK warns AI-driven cyberattacks are exposing years of weak security](https://techcrunch.com/2026/11/24/uk-warns-ai-driven-cyberattacks-are-exposing-years-of-weak-security/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Tue, 24 Nov 2026

## 💰 资本动向 (Capital Flow)
> 36Kr + 华尔街见闻

*暂无数据*

## 📚 学术前沿 (Research)
> ArXiv AI/ML Papers

### 1. [OmniAct: One Policy, One Million Embodiments](https://arxiv.org/abs/2611.33158v1)
👤 Xiang Fan, Yuheng Wang | 📅 2026-11-24

**详情:** A single policy that controls diverse robots must not only transfer task knowledge across embodiments, but also adapt its behavior to each robot's capabilities. Existing approaches facilitate transfer through shared action representations, but these representations do not necessarily capture how differences in robot morphology should shape manipulation strategies. We introduce OmniAct, a cross-embodiment manipulation policy that conditions directly on each robot's kinematics in a specific scene to produce embodiment-specific behavior. This kinematic graph represents the robot's joint positions, motion axes, and connectivity to its visual observation, allowing the policy to account for how its embodiment related to objects and surfaces in the scene. A flow-matching policy predicts relative joint motions for each node, enabling control across robots with different degrees of freedom and kinematic configurations. To learn how physical structure shapes behavior at scale, we procedurally design and filter one million physically feasible robot embodiments; next, we develop algorithms to generate robot trajectories in simulation for all embodiments; finally, we train across diverse simulated manipulation tasks. On 2,000 embodiment-scene-held-out evaluation episodes, OmniAct achieves 63.0% success, compared to 17.8% for pi 0.5 and 57.9% for the strongest baseline; on the task families GPT-6 Astra was evaluated on, it achieves 64.7% against GPT-6 Astra's 41.1%. On a previously unseen real-world robot, it achieves nearly twice the success rate of the next best method, MolmoAct2. Beyond task success, we observe that OmniAct learns distinct manipulation strategies that exploit the capabilities and accommodate the limitations of different morphologies. Project: https://omniact.github.io/

### 2. [MetaFORGE: A Meta-Learning Framework for Harness Optimization in Automated Code Generation for Parallel Computing](https://arxiv.org/abs/2611.33119v1)
👤 Scott Piersall, Yang Gao | 📅 2026-11-24

**详情:** Large language models (LLMs) can generate parallel programs, but their correctness and performance depend strongly on the instructions that guide generation. We present \textsc{MetaFORGE}, an execution-grounded meta-learning framework that iteratively optimizes persistent natural-language skill specifications for MPI C code generation. \textsc{MetaFORGE} combines correctness testing, compiler diagnostics, static-analysis findings, runtime measurements, and rank-level load-imbalance profiles into a scalar reward that drives textual-gradient refinement, while an external memory distills and retrieves reward-supported optimization knowledge across runs. Across six MPI tasks and three workload sizes, \textsc{MetaFORGE} improves static-analysis quality, runtime, and load balance relative to zero-shot generation and generally exceeds the evaluated \textsc{TextGrad} iterative baseline. A model-matched refinement ablation shows that the MetaFORGE advantage persists when its refinement model is reduced to \texttt{gpt-4o}. An expanded retrieval ablation across all 18 task--workload configurations shows consistent runtime benefit and broad static-analysis and load-balance benefit from retrieved context. Leakage-controlled held-out and zero-update experiments further provide evidence that optimization knowledge persists in both the transferred skill and external memory under the evaluated protocol.

### 3. [Draft Calibration for Speculative Decoding: Accelerating LLM Serving by Matching Draft and Target Distributions](https://arxiv.org/abs/2611.33111v1)
👤 Yuxing Liu, Wei Zuo | 📅 2026-11-24

**详情:** Speculative decoding accelerates large language model (LLM) inference by employing a lightweight draft model to propose draft tokens and allowing the target model to verify the new tokens in parallel to improve inference-time compute utilization. The speedup relies on the acceptance probability of draft tokens in target verification, which is directly related to the gap $\|p-q\|_1$ between the target distribution $p$ and the draft distribution $q$. In this paper, we study draft calibration of speculative decoding to improve the speedup of speculative decoding, where we employ post-hoc methods to calibrate the draft distribution to mitigate the distribution gap. We observe that though current community open-source draft models may learn the top candidate token correctly, they are generally underconfident compared to the target model, suggesting a consistent distribution mismatch. To mitigate the effect of this mismatch on the acceptance rate of the draft models, we try various post-hoc calibration methods, including standard temperature scaling and token-wise calibration. Our results suggest that a standard temperature scaling applied to the draft distribution improves the acceptance length by up to approximately 10\% with almost no additional cost across different tasks. Throughput analysis further verifies that this improvement in serving efficiency. Analysis of more general calibration methods reveals further potential room for improvement.

### 4. [Temporal Conditioning for Human Behavioral Cloning in Chess](https://arxiv.org/abs/2611.33106v1)
👤 Victor Dziwniel, Tianxiang Lu | 📅 2026-11-24

**详情:** Behavioral cloning models in chess typically predict human moves from board states while ignoring temporal inputs such as the remaining clock. However, time pressure is a major determinant of human decision-making quality, and temporal state is a missing dimension of human behavioral modeling. This paper introduces a time-aware transformer that extends a Chessformer-style architecture with learned temporal conditioning tokens encoding player clock state, time control, and recent tempo, together with behavioral heads for thinking time and resignation. The model is trained on large-scale online chess data and evaluated against time-agnostic baselines and the state of the art. Results show that temporal conditioning yields modest overall accuracy improvements but substantially stronger gains under time pressure. Beyond move choice, it also produces more accurate thinking-time and resignation predictions. More importantly, the model better matches human move-quality degradation in critical time regimes, reducing the systematic over-strength observed in time-agnostic behavioral cloning models. These results suggest that temporal state is a previously underutilized but important signal for human behavioral cloning in chess.

### 5. [Delegent: A Multi-Agent Harness That Reduces Cost without Sacrificing Performance](https://arxiv.org/abs/2611.33098v1)
👤 Lingwei Gu, Jimmy Lin | 📅 2026-11-24

**详情:** Agents built on frontier language models are expensive. At every step, the frontier model re-reads its entire context and executes every subtask regardless of its difficulty. This paper explores the simple thesis that much of this cost can be removed by delegating easy subtasks to a small language model, or SLM, that runs on hardware one already owns. To test it, we build Delegent, a simple and effective agent harness built on Claude Code, in which the frontier model stays in charge of every task but hands focused subtasks, such as investigating code, running tests, and searching a corpus, to SLM subagents. Existing approaches such as cascades and model routers usually choose which model executes the entire task, whereas in Delegent, the frontier model always leads the execution and delegates easy subtasks to the SLM. No router or model is trained, so either model can be swapped freely. With the help of a 27B FP8 SLM, Delegent reduces the frontier cost of long-horizon coding by 67% and of agentic search by 59%, with no loss in task performance, and even a 2B SLM that fits on a laptop reduces the coding cost by 66%. The savings grow with the legwork that the frontier model would otherwise do itself, and a short instruction, which leaves the main coding tasks to the frontier model, accounts for most of the saving and keeps the 2B SLM from losing tasks. Code: https://github.com/castorini/delegent

## 💎 产品精选 (Product Gems)
> Product Hunt Today

*暂无数据 (Product Hunt API 可能需要配置)*

## 🐦 社交热议 (Social)
> X (Twitter) - AI/Tech Discussions

*暂无数据 (需要配置 XAI_API_KEY)*

## 🗣️ 社区热点 (Community)
> V2EX 热门

### 1. [养猫两个月，我和猫的关系却越来越糟](https://www.v2ex.com/t/1259458)
💬 207 replies

### 2. [理发怎么能那么贵！](https://www.v2ex.com/t/1259612)
💬 112 replies

### 3. [我知道你几岁](https://www.v2ex.com/t/1259639)
💬 104 replies

### 4. [大家怎么第一次面对亲人的离去？](https://www.v2ex.com/t/1259613)
💬 90 replies

### 5. [密码管理很少见到大家用苹果自带的 passwords](https://www.v2ex.com/t/1259605)
💬 55 replies

## 💡 深度洞察 (Insights)
> HN Top Blogs + MIT Technology Review — 精选深度分析

### 1. [Raising the stakes for enterprise networks with AI modernization](https://www.technologyreview.com/2026/11/24/1148091/raising-the-stakes-for-enterprise-networks-with-ai-modernization/)
📍 MIT Technology Review Insights | 📅 Tue, 24 Nov 2026

### 2. [The Download: AI’s gas power boom and a consciousness reality check](https://www.technologyreview.com/2026/11/24/1149669/the-download-data-centers-gas-ai-consciousness/)
📍 Thomas Macaulay | 📅 Tue, 24 Nov 2026

### 3. [Data centers are getting their own natural gas power plants](https://www.technologyreview.com/2026/11/24/1149622/data-centers-natural-gas/)
📍 Casey Crownhart | 📅 Tue, 24 Nov 2026

### 4. [A legendary philosopher isn’t buying Anthropic’s consciousness argument](https://www.technologyreview.com/2026/11/23/1149569/a-legendary-philosopher-isnt-buying-anthropics-consciousness-argument/)
📍 James O'Donnell | 📅 Mon, 23 Nov 2026

### 5. [The Download: AI’s judgment problem and carbon removal’s crop threat](https://www.technologyreview.com/2026/11/23/1149548/the-download-ai-judgment-problem-carbon-removal-crop-threat/)
📍 Thomas Macaulay | 📅 Mon, 23 Nov 2026

---
*报告由 Unified Intelligence Engine V2 自动生成*