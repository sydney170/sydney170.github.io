---
layout: page
title: Home
---

## Welcome!

Hi, I'm **Yancheng He**, an LLM Researcher at Alibaba Group.

## Research Interests

Currently, I am actively exploring the potential of **Large Language Models (LLMs)**. My research is centered on pursuing the advancement of **Agentic Intelligence** and **Reasoning Capabilities** through **Reinforcement Learning**. I hold a firm belief that LLMs will fundamentally reshape our daily lives and the way we interact with the world, and I am keen to explore the possibilities within this shift.

## Key Projects

- [**ROME**](https://huggingface.co/FutureLivingLab/iFlow-ROME) - An open-source agentic model for long-horizon agentic tasks
- [**ROLL**](https://github.com/alibaba/ROLL) - High-performance RL training frameworks
- [**Agentic Learning Ecosystem (ALE)**](https://arxiv.org/pdf/2512.24873) - A comprehensive framework for agentic AI development

## Latest News

- **[2026.02]** Published blog post ["The Bitter Lesson Behind Building Agentic RL in Terminal Environments"](https://www.notion.so/The-Bitter-Lesson-Behind-Building-Agentic-RL-in-Terminal-Environments-2eaddd45837f80c9ad2ed6a15ef3c1a1)
- **[2026.01]** 3 papers accepted by **ICLR 2026** 🎉
- **[2025.12]** Open-sourced our medium-sized agentic model [ROME](https://huggingface.co/FutureLivingLab/iFlow-ROME) and released the [technical report](https://arxiv.org/pdf/2512.24873)
- **[2025.12]** Introduced "3A" works: [Asynchronous Training](https://arxiv.org/pdf/2510.11345), [Asymmetric PPO (AsyPPO)](https://arxiv.org/abs/2510.01656), and Attention-based Reasoning Rhythm—deeply coupled techniques advancing RL for LLMs toward efficiency, precision, and interpretability
- **[2025.06]** 5 papers accepted by **ACL 2025** 🎉

## Selected Publications

<div class="paper-card">
  <div class="paper-image">
    <img src="/images/ale.png" alt="rome" />
  </div>
  <div class="paper-content">
    <h3 class="paper-title">Let It Flow: Agentic Crafting on Rock and Roll</h3>
    <p class="paper-authors">
      ROLL TEAM
    </p>
    <span class="paper-conference">Arxiv</span>
    <p class="paper-abstract">
      We introduce the Agentic Learning Ecosystem (ALE), a foundational infrastructure that optimizes the production pipeline for agentic model. And, we release ROME, an open-source agent grounded by ALE and trained on over one million trajectories.
    </p>
    <p><a href="https://arxiv.org/abs/2512.24873" class="paper-link">[paper]</a>  <a href="https://huggingface.co/FutureLivingLab/iFlow-ROME" class="paper-link">[model]</a></p>
  </div>
</div>
<div class="paper-card">
  <div class="paper-image">
    <img src="/images/liteppo.png" alt="Liteppo" />
  </div>
  <div class="paper-content">
    <h3 class="paper-title">Tricks or Traps? A Deep Dive into RL for LLM Reasoning</h3>
    <p class="paper-authors">
      Zihe Liu, Jiashun Liu, Yancheng He, Weixun Wang, Jiaheng Liu, Ling Pan, Xinyu Hu, Shaopan Xiong, Ju Huang, Jian Hu, Shengyi Huang, Siran Yang, Jiamang Wang, Wenbo Su, Bo Zheng
    </p>
    <span class="paper-conference">ICLR2026</span>
    <p class="paper-abstract">
      We present clear guidelines for selecting RL techniques tailored to specific setups and provide a reliable roadmap for practitioners navigating the RL for the LLM domain. Finally, we show that a minimalist combination of two techniques can unlock the learning capability of critic-free policies with a vanilla PPO loss.
    </p>
    <p><a href="https://arxiv.org/abs/2508.08221" class="paper-link">[paper]</a>  <a href="https://github.com/alibaba/ROLL/blob/main/docs_roll/i18n/zh-Hans/docusaurus-plugin-content-docs/current/User%20Guides/Algorithms/LitePPO.md" class="paper-link">[code]</a>  <a href="https://mp.weixin.qq.com/s/cl9tZrVsEV4eLUjkgPbCrg" class="paper-link">[机器之心]</a></p>
  </div>
</div>

<div class="paper-card">
  <div class="paper-image">
    <img src="/images/flash.png" alt="flash" />
  </div>
  <div class="paper-content">
    <h3 class="paper-title">ROLL Flash -- Accelerating RLVR and Agentic Training with Asynchrony</h3>
    <p class="paper-authors">
      Han Lu, Zichen Liu, Shaopan Xiong, Yancheng He, Wei Gao, Yanan Wu, Weixun Wang
    </p>
    <span class="paper-conference">Arxiv</span>
    <p class="paper-abstract">
      We present ROLL Flash, a system that extends ROLL with native support for asynchronous RL post-training. ROLL Flash is built upon two core design principles: fine-grained parallelism and rollout-train decoupling.
    </p>
    <p><a href="https://arxiv.org/abs/2510.11345" class="paper-link">[paper]</a>  <a href="https://github.com/alibaba/ROLL" class="paper-link">[code]</a>  <a href="https://mp.weixin.qq.com/s/czc2vbj2VI43Chh0YxZoxA" class="paper-link">[机器之心]</a></p>
  </div>
</div>

<div class="paper-card">
  <div class="paper-image">
    <img src="/images/aysnppo.png" alt="aysnppo" />
  </div>
  <div class="paper-content">
    <h3 class="paper-title">Asymmetric Proximal Policy Optimization: mini-critics boost LLM reasoning</h3>
    <p class="paper-authors">
      Jiashun Liu, Johan Obando-Ceron, Han Lu, Yancheng He, Weixun Wang, Wenbo Su, Bo Zheng, Pablo Samuel Castro, Aaron Courville, Ling Pan
    </p>
    <span class="paper-conference">ICLR2026</span>
    <p class="paper-abstract">
      We revisit this bottleneck from an architectural perspective and introduce Asymmetric Proximal Policy Optimization (AsyPPO), a simple and scalable framework that restores the critics role while remaining efficient in large-model settings.
    </p>
    <p><a href="https://arxiv.org/abs/2510.01656" class="paper-link">[paper]</a>  <a href="https://mp.weixin.qq.com/s/czc2vbj2VI43Chh0YxZoxA" class="paper-link">[机器之心]</a></p>
  </div>
</div>

<div class="paper-card">
  <div class="paper-image">
    <img src="/images/thinkj.png" alt="think-j" />
  </div>
  <div class="paper-content">
    <h3 class="paper-title">Think-J: Learning to Think for Generative LLM-as-a-Judge</h3>
    <p class="paper-authors">
      Hui Huang, Yancheng He, Hongli Zhou, Rui Zhang, Wei Liu, Weixun Wang, Jiaheng Liu, Wenbo Su
    </p>
    <span class="paper-conference">AAAI2025</span>
    <p class="paper-abstract">
      Although generative LLMs have made substantial progress in various tasks, their performance as LLM-Judge still falls short of expectations. In this work, we propose Think-J, which improves generative LLM-as-a-Judge by learning how to think.
    </p>
    <p><a href="https://arxiv.org/abs/2505.14268" class="paper-link">[paper]</a>  <a href="https://github.com/huihuichyan/think-j" class="paper-link">[code]</a></p>
  </div>
</div>

<div class="paper-card">
  <div class="paper-image">
    <img src="/images/deltabench.png" alt="deltabench" />
  </div>
  <div class="paper-content">
    <h3 class="paper-title">Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?</h3>
    <p class="paper-authors">
      Yancheng He, Shilong Li, Jiaheng Liu, Weixun Wang, Xingyuan Bu, Ge Zhang, Zhongyuan Peng, Zhaoxiang Zhang, Zhicheng Zheng, Wenbo Su, Bo Zheng
    </p>
    <span class="paper-conference">ACL2025</span>
    <p class="paper-abstract">
      We introduce the DeltaBench including the generated long CoTs from different o1-like models for different reasoning tasks, to measure the ability to detect errors in long COT reasoning. Based on DeltaBench, we first perform fine-grained analysis of the generated long CoTs to discover the effectiveness and efficiency of different o1-like models.
    </p>
    <p><a href="https://aclanthology.org/2025.acl-long.905.pdf" class="paper-link">[paper]</a>  <a href="https://github.com/LivingFutureLab/DeltaBench" class="paper-link">[github]</a></p>
  </div>
</div>

Feel free to explore my page for more on our latest research. If you are interested in our research topics, please feel free to reach out via <a href="mailto:sydney_he@163.com">email</a>.


