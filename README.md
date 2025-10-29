# AI-Crash-Course
AI Crash Course to help busy builders catch up to the public frontier of AI research in 2 weeks

**Intro:** I’m [Henry Shi](https://www.linkedin.com/in/henrythe9th/) and I started Super.com in 2016 and grew it to $150MM+ in annual revenues and recently exited. As a traditional software founder, I needed to quickly catch up to the frontier of AI research to figure out where the next opportunities and gaps were. I compiled a list of resources that were essential for me and should get you caught up within 2 weeks.

For more context, checkout the [original twitter thread](https://x.com/henrythe9ths/status/1877056425454719336)

**Start Here:**  
[Neural Network \-\> LLM Series](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

**Then get up to speed via Survey papers:**

- Follow the ideas in the survey paper that interest you and dig deeper

[LLM Survey](https://arxiv.org/pdf/2402.06196v2) \- 2024  
[Agent Survey](https://arxiv.org/pdf/2308.11432) \- 2023  
[Prompt Engineering Survey](https://arxiv.org/pdf/2406.06608) \- 2024  
[Context Engineering Survey](https://arxiv.org/abs/2507.13334) \- 2025

**AI Papers:** (prioritize ones with star \*)

**Foundational Modelling:**  
[**Transformers**\*](https://arxiv.org/pdf/1706.03762) (foundation, self-attention) \- 2017  
[Scaling Laws](https://arxiv.org/pdf/2001.08361)/[**GPT3**\*](https://arxiv.org/pdf/2005.14165) (conviction to scale up GPT2/3/4) \- 2020  
[LoRA](https://arxiv.org/abs/2106.09685) (Fine tuning) \- 2021  
[Training Compute-Optimal LLMs](https://arxiv.org/pdf/2203.15556) \- 2022  
[**RLHF**\*](https://arxiv.org/pdf/2203.02155) (InstructGPT-\>ChatGPT) \- 2022  
[DPO](https://arxiv.org/pdf/2305.18290) (No need for RL/Reward model) \- 2023  
[LLM-as-Judge](https://arxiv.org/pdf/2306.05685) (On par with human evaluations) \- 2023  
[MoE](https://arxiv.org/pdf/2401.04088) (MIxture of Experts) \- 2024  

**Planning/Reasoning:**  
[AlphaZero](https://arxiv.org/pdf/1712.01815)/[**MuZero**\*](https://arxiv.org/pdf/1911.08265) (RL without prior knowledge of game or rules) \- 2017/2019  
[**CoT**\* (Chain of Thought)](https://arxiv.org/pdf/2201.11903)/[ToT (Tree of Thoughts)](https://arxiv.org/pdf/2305.10601)/[GoT (Graph of Thoughts)](https://arxiv.org/pdf/2308.09687)/[Meta CoT](https://arxiv.org/pdf/2501.04682) \- 2022/2023/2023/2025  
[ReACT](https://arxiv.org/pdf/2210.03629) (Generate reasoning traces and task-specific actions in interleaved manner) \- 2022  
[Let’s Verify Step by Step](https://arxiv.org/pdf/2305.20050) (Process \> Outcome) \- 2023  
[**ARC-Prize**\*](https://arxiv.org/pdf/2412.04604) (Latest methods for solving ARC-AGI problems) \- 2024  
[**DeepSeek R1**\*](https://arxiv.org/pdf/2501.12948v1) (Building OSS o1-level reasoning model with pure RL, no SFT, no RM) \- 2025

**Applications:**  
[Toolformer](https://arxiv.org/pdf/2302.04761) (LLMs to use tools) \- 2023  
[GPT4](https://arxiv.org/pdf/2303.08774) (Overview of GPT4, but fairly high level) \- 2023  
[**Llama3**\*](https://arxiv.org/pdf/2407.21783) (In depth details of how Meta built Llama3 and the various configurations and hyperparameters) \- 2024  
[Gemini1.5](https://arxiv.org/pdf/2403.05530) (Multimodal across 10MM context window) \- 2024  
[Deepseekv3](https://github.com/deepseek-ai/DeepSeek-V3/blob/main/DeepSeek_V3.pdf) (Building a frontier OSS model at a fraction of the cost of everyone else) \- 2024  
[SWE-Agent](https://arxiv.org/pdf/2405.15793)/[OpenHands](https://arxiv.org/pdf/2407.16741) (OpenSource software development agents) \- 2024

**Benchmarks:**  
[BIG-Bench](https://arxiv.org/pdf/2206.04615) (First broad & diverse collaborative OSS benchmark) \- 2022  
[SWE-Bench](https://arxiv.org/pdf/2310.06770) (Real world software development) \- 2023  
[Chatbot Arena](https://arxiv.org/pdf/2403.04132) (Live human preference Elo ratings) \- 2024

<hr />

**Videos/Lectures:**  
[3Blue1Brown on Foundational Math/Concepts](https://www.youtube.com/@3blue1brown)  
[Build a Large Language Model (from Scratch) \#1 Bestseller](https://www.amazon.com/Build-Large-Language-Model-Scratch/dp/1633437167)  
[Andrej Kaparthy: Zero to Hero Series](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)  
[Yannic Kilcher Paper Explanations](https://www.youtube.com/@YannicKilcher)  
[Noam Brown (o1 founder) on Planning in AI](https://www.youtube.com/watch?v=eaAonE58sLU)  
[Stanford: Building LLMs](https://www.youtube.com/watch?v=9vM4p9NN0Ts)  
[Foundations of LLMs](https://arxiv.org/pdf/2501.09223)  
[Why You’re Not Too Old to Pivot Into AI](https://www.latent.space/p/not-old) (motivation)

**Helpful Websites:**  
[History of Deep Learning](https://github.com/adam-maj/deep-learning?tab=readme-ov-file) \- summary timeline of deeplearning with major breakthroughs and key concepts  
[Full Stack Deep Learning](https://fullstackdeeplearning.com/) \- courses for building AI products  
[Prompting Guide](https://www.promptingguide.ai/) \- extensive list of prompting techniques and examples  
[a16z AI Cannon](https://a16z.com/ai-canon/) \- similar list of resources, but longer (slightly dated)  
[2025 AI Engineer Reading List](https://www.latent.space/p/2025-papers) \- longer reading list, broken out by focus area  
[State of Generative Models 2024](https://nrehiew.github.io/blog/2024/) \- good simple summary of current state

**Others (non LLMs):**  
[Vision Transformer](https://arxiv.org/pdf/2010.11929) (no need for CNNs) \- 2021  
[Latent Diffusion](https://arxiv.org/pdf/2112.10752) (Text-to-Image) \- 2021

**Obvious/easy papers (to get your feet wet if you're new to papers):**  
[CoT (Chain of Thought)](https://arxiv.org/pdf/2201.11903) \- 2022  
[SELF-REFINE: Iterative Refinement with Self-Feedback](https://arxiv.org/pdf/2303.17651) \- 2023  
