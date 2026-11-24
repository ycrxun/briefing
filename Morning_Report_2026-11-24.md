# 🌐 全球情报日报 (Global Intel Briefing)
**日期:** 2026-11-24
**生成时间:** 07:08
**数据源:** HN, GitHub, 36Kr, WallStreetCN, V2EX, PH, ArXiv, X, TechCrunch, MIT TR

---

## 🛠️ 技术趋势 (Tech Trends)
> Hacker News + GitHub Trending

### 1. [Figma employee sues, alleging company forced her to confront harassers](https://techcrunch.com/2026/11/23/figma-employee-sues-alleging-company-forced-her-to-confront-harassers/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

### 2. [Anthropic launches Claude Ship, letting AI agents review, fix, and approve code changes](https://techcrunch.com/2026/11/23/anthropic-launches-claude-ship-letting-ai-agents-review-fix-and-approve-code-changes/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

### 3. [Supertake raises $20M to let AI agents turn your market predictions into stock portfolios](https://techcrunch.com/2026/11/23/supertake-raises-20m-to-let-ai-agents-turn-your-market-predictions-into-stock-portfolios/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

### 4. [Elon Musk and others rejoice as Jensen Huang is reinstated at Nvidia amid scandal](https://techcrunch.com/2026/11/23/elon-musk-and-others-rejoice-as-jensen-huang-is-reinstated-at-nvidia-amid-scandal/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

### 5. [Megaspeed, the company at the center of the Jensen Huang scandal, appears headed for a US blacklist](https://techcrunch.com/2026/11/23/megaspeed-the-company-at-the-center-of-the-jensen-huang-scandal-appears-headed-for-a-u-s-blacklist/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

### 6. [Nvidia employees greet Jensen Huang like a hero as he returns to company’s HQ](https://techcrunch.com/2026/11/23/nvidia-employees-greet-jensen-huang-like-a-hero-as-he-returns-to-companys-hq/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

### 7. [‘Outrageous,’ ‘reckless,’ ‘wow’: Here’s what politicians are saying about Jensen Huang’s return to Nvidia](https://techcrunch.com/2026/11/23/outrageous-reckless-wow-heres-what-politicians-are-saying-about-jensen-huangs-return-to-nvidia/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

### 8. [Google Search’s AI Mode can now tap into Drive and Wallet for more personalized responses](https://techcrunch.com/2026/11/23/google-searchs-ai-mode-can-now-tap-into-drive-and-wallet-for-more-personalized-responses/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

### 9. [Jensen Huang scheduled to testify next week in Senate following reinstatement as Nvidia CEO](https://techcrunch.com/2026/11/23/jensen-huang-scheduled-to-testify-next-week-in-senate-following-reinstatement-as-nvidia-ceo/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

### 10. [Amazon snaps up Decart’s AI optimization tech for $7.5B as it prepares to sell Trainium chips](https://techcrunch.com/2026/11/23/amazon-snaps-up-decarts-ai-optimization-tech-for-7-5b-as-it-prepares-to-sell-trainium-chips/)
📍 TechCrunch | 🔥 🔥 Featured | 🕒 Mon, 23 Nov 2026

## 💰 资本动向 (Capital Flow)
> 36Kr + 华尔街见闻

*暂无数据*

## 📚 学术前沿 (Research)
> ArXiv AI/ML Papers

### 1. [TrialAgentBench: Evaluating AI Agents for Clinical-Trial Analysis and Long-Horizon Drug-Development Decisions](https://arxiv.org/abs/2611.30916v1)
👤 Bradley Segal, William Bolton | 📅 2026-11-23

**详情:** Clinical drug development is a long-horizon, high-stakes process requiring sequential decisions based on information that costs money and time to acquire. AI agents have demonstrated capabilities for scientific analysis, but there is no established way to evaluate them on these decisions, as real trials are expensive, involve people, and never reveal the counterfactual. We introduce TrialAgentBench, a benchmark for evaluating AI agents on clinical trial analysis and drug development decision-making using simulated trials where the truth is known, embedded within the data records of a fictional drug sponsor. We publicly release nearly 3,500 tasks, varying from analysing a single trial to managing multi-phase programmes with budget and time constraints. We score each analysis by rerunning its code on new trials, and each programme by the value its decisions achieve. Across 24 closed- and open-weight models, the strongest agents can analyse raw, messy trial records to within 6% of a process-aware analysis, even when an assumption is violated, with 95% confidence intervals containing the true effect 94--95% of the time. Over the prior year, the best model improved from 19% above this analysis, with serious misses on 15% of tasks, to 3.5% and 1%. What limits them is decision-making from evidence under uncertainty: when to correct, what evidence to buy, when to stop. The strongest agents are overly careful, correcting on 83% of tasks with equal recording errors, where it is unnecessary. On drug programmes, the best agent has substantial headroom, reaching 48% of the value an oracle achieves against 58% for a rule-based developer, with others falling 24 to 66% short. Model generations show ongoing improvements in handling data and evidence, with substantial variation. The strongest models can act as competent analysts, but do not yet make reliable long-horizon decisions.

### 2. [Replay Before You Reply: Second-Look Prompting for Unified Multimodal Encoding](https://arxiv.org/abs/2611.30909v1)
👤 Yicheng Zhang, Xun Zhang | 📅 2026-11-23

**详情:** Solving multimodal tasks requires Vision-Language Models (VLMs) to form a unified understanding of the image and the question text. However, under causal attention in current VLMs, a token can attend only to what precedes it. Whichever modality comes first is therefore encoded under partial observation of the input, uninformed by the rest of the multimodal context. We introduce Second-Look Prompting (SLP), a training-free method that repeats the image-question pair in the input. In the repeated copy, every visual and textual token can attend to the complete input, yielding a unified multimodal encoding of the pair. Moreover, the added visual tokens contribute computation beyond re-exposing the image: even a blank image in their place can improve reasoning. Across 12 benchmarks, SLP improves the overall average score of every evaluated model, spanning nine open-source models (3B-72B) and three proprietary frontier models, with gains reaching 5.6 points for Gemini 3 Flash on MATH-Vision. Our analysis reveals two complementary mechanisms: the question guides where the second image attends, and the added visual tokens act as a prefill scratchpad whose hidden states retain answer-relevant information from the image and question. These findings highlight input presentation as a simple yet effective way to improve VLM performance.

### 3. [Predicting Rare-Mode Collapse in Recursive Generative Training from Single-Generation Calibration](https://arxiv.org/abs/2611.30897v1)
👤 Jingyao Zhang, Mingyu Du | 📅 2026-11-23

**详情:** Recursive generative training can preserve sample counts in a rare region while silently eroding its characteristic core. Mapping this finite-horizon collapse across real-data quotas, rare prevalences, and feedback perturbations via exhaustive multi-generation chains is computationally prohibitive. We develop a decoupled framework that forecasts multi-generation collapse probabilities and locates operating risk boundaries from independent single-generation conditional fits alone. Pairing an exact three-source multinomial count law with single-generation response banks propagates count marginals in closed form, backed by explicit calibration-error and boundary-resolution bounds. For additive Gaussian perturbations, we further prove that equal-variance all-row and sparse policies reverse their boundary-crossing order at a unique hyperplane distance. Across a 2,178-setting count benchmark, exact propagation cuts risk mean absolute error (MAE) from 1.85 to 0.49 percentage points (pp). Across ten two-dimensional learners, calibration achieves 2.60--5.69~pp six-round core MAE on nine stationary learners (65--81\% below an unperturbed baseline), diagnoses non-stationary outlier drift in standard DDIM (16.38~pp) via a stability probe, and resolves the predicted six-round geometric reversal. On Fashion-MNIST latent flow-matching chains, calibration outperforms direct-chain Gaussian-process interpolation at lower fit budgets and tracks the 20\% latent-perturbation boundary shift (3.14 versus 10.78~pp MAE for proportion copying) driven by opposing inflow to the rare region and outflow from its core.

### 4. [Speak When You See It: Proactive Task Assistants Should Wait for Evidence, Not the Clock](https://arxiv.org/abs/2611.30895v1)
👤 Bohe Chen | 📅 2026-11-23

**详情:** Proactive assistants that guide people through physical tasks must decide, every few seconds, whether a step is complete and whether a mistake has occurred. We find that two benchmarks for this task largely reward knowing when rather than seeing what: a timer that never looks at the video, raising an alarm at 25 s and confirming each step at 30 s, reaches a mistake F1 of 0.373 on Ego-MC-Bench, above every published result (at most 0.27). We formalize this as the video-blind frontier, the best trade-off between completion accuracy and mistake F1 that policies reach from the elapsed time, the instruction and training statistics alone: every published per-step result on Ego-MC-Bench lies inside it, and so do all twelve zero-shot models we run on QICD. To move beyond it, we introduce Evidence-Contrastive Training (ECT): fine-tune on the benchmark's own questions, and pair its positives with negatives from the same recording at the same elapsed time, so that elapsed time cannot separate the two sides of a pair. Trained on 209 QICD videos in about 15 GPU-hours, a 2B model with ECT crosses the frontier on both benchmarks in all four seeds; transferred to Ego-MC-Bench without adaptation, it confirms 59% of mistake-free steps in time, against 30% for a published model with the same backbone trained on about 25k synthetic counterfactuals and real recordings. Its decisions follow the video beyond what timing explains: at equal elapsed time it tells a finished step from an unfinished one in 90-92% of test pairs, where the instruction's typical duration reaches 65%, rescaling the time stamps between the frames leaves it essentially unchanged, and swapping in another recording, of the same recipe where one exists, cuts its completion accuracy by two thirds. The code and model weights will be publicly released.

### 5. [AeroJEPA: A Two-Stage Framework for Aerosol Forecasting with Joint-Embedding Predictive Learning](https://arxiv.org/abs/2611.30891v1)
👤 Zitong Shuai, Zengliang Zang | 📅 2026-11-23

**详情:** Aerosol forecasting requires integrating sparse ground observations and modeling meteorologically driven concentration evolution and spatial structure. However, analysis-initialized forecasts make limited explicit use of historical observations, while pointwise regression tends to smooth local variations and provides limited constraints on fine spatial structures. In this work, we propose AeroJEPA, a two-stage joint-embedding predictive framework for regional surface PM$_{2.5}$ forecasting. Specifically, Stage I fuses historical observations, model backgrounds, and meteorological information to predict an initial future state, meteorological conditions, and multi-scale structures. Morphology-guided encoding and joint-embedding predictive supervision support learning future spatial representations, supplementing concentration regression with structural constraints. Stage II uses predicted meteorology to guide state refinement and incorporates coarse- and fine-scale structures into state updates and decoding to generate the concentration field at a single future time step. Experiments show that AeroJEPA reduces gridded and independent-station RMSE by 17.23\% and 7.90\%, respectively, relative to PFGNet, while improving spatial consistency with analysis fields. In a 48 h recursive forecasting case study, AeroJEPA generally achieves lower RMSE and MAE than the numerical forecasts across the forecast period, indicating promising short- to medium-range forecasting performance.

## 💎 产品精选 (Product Gems)
> Product Hunt Today

*暂无数据 (Product Hunt API 可能需要配置)*

## 🐦 社交热议 (Social)
> X (Twitter) - AI/Tech Discussions

*暂无数据 (需要配置 XAI_API_KEY)*

## 🗣️ 社区热点 (Community)
> V2EX 热门

### 1. [2026 年我的常用 Mac 软件分享](https://www.v2ex.com/t/1259301)
💬 99 replies

### 2. [黄仁勋又重新回到了他的英伟达，服了，把全世界当猴耍](https://www.v2ex.com/t/1259265)
💬 90 replies

### 3. [北京 35+前端失业一个月心态崩了，想去干转转上门回收，月入过万靠谱吗？](https://www.v2ex.com/t/1259332)
💬 81 replies

### 4. [密码管理怎么做比较好？](https://www.v2ex.com/t/1259186)
💬 74 replies

### 5. [仁勋这招叫做以退为进吗？](https://www.v2ex.com/t/1259299)
💬 66 replies

## 💡 深度洞察 (Insights)
> HN Top Blogs + MIT Technology Review — 精选深度分析

### 1. [A legendary philosopher isn’t buying Anthropic’s consciousness argument](https://www.technologyreview.com/2026/11/23/1149569/a-legendary-philosopher-isnt-buying-anthropics-consciousness-argument/)
📍 James O'Donnell | 📅 Mon, 23 Nov 2026

### 2. [The Download: AI’s judgment problem and carbon removal’s crop threat](https://www.technologyreview.com/2026/11/23/1149548/the-download-ai-judgment-problem-carbon-removal-crop-threat/)
📍 Thomas Macaulay | 📅 Mon, 23 Nov 2026

### 3. [Why using rocks for carbon removal could eventually reduce crop growth](https://www.technologyreview.com/2026/11/23/1149392/why-using-rocks-for-carbon-removal-could-eventually-reduce-crop-growth/)
📍 James Temple | 📅 Mon, 23 Nov 2026

### 4. [The most misunderstood graph in AI just got a major update](https://www.technologyreview.com/2026/11/20/1149399/the-most-misunderstood-graph-in-ai-just-got-a-major-update/)
📍 Grace Huckins | 📅 Fri, 20 Nov 2026

### 5. [The Download: inside the quest to make our minds immortal](https://www.technologyreview.com/2026/11/20/1149371/the-download-quest-to-make-minds-immortal/)
📍 Thomas Macaulay | 📅 Fri, 20 Nov 2026

---
*报告由 Unified Intelligence Engine V2 自动生成*