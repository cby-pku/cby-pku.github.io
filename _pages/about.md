---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
body_class: "page--about"
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a undergraduate majoring in Artificial Intelligence at Yuanpei College, [Peking University](https://english.pku.edu.cn/), advised by Prof. [Yaodong Yang](https://www.yangyaodong.com/).
My research direction are reinforcement learning, the safety and value alignment of large models (*i.e.*, scalable oversight, deception alignment and super alignment). My current research focuses on the goal of constructing safe and trustworthy AI systems. You can find my <b>research statement</b> [here](https://cby-pku.github.io//files/research_statement.pdf).

My answers to the [Hamming question](https://www.cs.virginia.edu/~robins/YouAndYourResearch.html) (“What are the most important problems [that you should probably work on]?”): 
<ul>
<li>How to align systems smarter than humans and how to align them on tasks challenging for human evaluation? (<i>i.e.</i>, <b>scalable oversight</b>)</li>
<li>How can we integrate theory and experimental validation to embed moral values into AI systems? (<i>e.g.</i>, <b>moral reflection</b> and <b>moral progress</b>) and address the AI alignment problem from a <b>socio-technical</b> perspective.</li>
</ul> 

I have just started on this long road, and I will leverage my youth and curiosity to seize more opportunities and time for an in-depth exploration of these problems.
Feel free to reach out! <b>Email</b>: boyuan.chen.byc at gmail dot com



<details>
  <summary>关于我（中文）</summary>
  <p>
  陈博远，北京大学元培学院人工智能方向本科生，导师为杨耀东老师，研究方向为强化学习、大模型的安全与价值对齐、可扩展监督，曾在计算机顶会发表口头报告，谷歌学术引用累计1000余次，GitHub开源累计获得3.5k+ Star。曾获首批北京市自然科学基金资助（2023年度北京大学人工智能本科生唯一），商汤奖学金（全国仅25位），研究成果及模型被OpenAI 、Meta引用，被MIT Tech Review报道。
  </p>
</details>

# News
- *2025.06*: &nbsp;🎉 Two papers are accepted by ACL 2025 Main.
- *2025.05*: &nbsp;🎉 We open-source [InterMT](https://pku-intermt.github.io/), the first multi-turn multimodal understanding and generation human preference dataset. Welcome to discuss and collaborate!
- *2025.01*: &nbsp;🎉 We release [Align-DS-V](https://huggingface.co/PKU-Alignment/Align-DS-V), the first multimodal strong reasoning model.

<details markdown="1">
  <summary><font size="+1"><b>More news</b></font></summary>
- *2024.10*: &nbsp;💥 We open-source the first all-modality alignment framework - [Align-Anything](https://github.com/PKU-Alignment/align-anything)!
- *2024.09*: &nbsp;💥 **<font color="#DC143C">Aligner</font>** has been accepted as an **<font color="#DC143C">Oral</font>** presentation at NeurIPS 2024!
- *2024.06*: &nbsp;🎉 We introduce the [PKU-SafeRLHF dataset](https://sites.google.com/view/pku-saferlhf), designed to promote research on safety alignment in LLMs.
- *2024.06*: &nbsp;🎙️ Happy to introduce our new work about *elasticity* of LLMs. Click [here](https://arxiv.org/abs/2406.06144) for further details.
- *2024.04*: &nbsp;🎊 Our work - [BeaverTails](https://github.com/PKU-Alignment/beavertails) has been recognized by [Meta](https://llama.meta.com/trust-and-safety), further contributing to AI safety research.
- *2024.03*: &nbsp;💥 Our alignment survey has been recognized by [NIST](https://www.nist.gov/)! [More details](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2023.pdf?utm_source=danielmiessler.com&utm_medium=newsletter&utm_campaign=ul-no-415-it-s-raining-9-cves-40-job-loss-from-ai-invisible-prompt-injection).
- *2024.03*: &nbsp;🚀 We have made significant updates to the [alignment survey](https://alignmentsurvey.com/) (V4)!
- *2024.02*: &nbsp;💥 We release [Aligner](https://arxiv.org/abs/2402.02416): **a new efficient alignment paradigm, bypasses the whole RLHF process.**
- *2023.11*: &nbsp;🚀 We release [AI Alignment Survey](https://arxiv.org/abs/2310.19852) and [Alignment Resource Website](https://alignmentsurvey.com/). Welcome to further discussion!
</details>

# Publications
<small><sup>*</sup> denotes equal contribution, <sup>α</sup> denotes core contributors, and <sup>†</sup> denotes corresponding author</small>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/papers/intermt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InterMT: Multi-Turn Interleaved Preference Alignment with Human Feedback](https://arxiv.org/abs/2505.23950)

**Boyuan Chen**<sup>*</sup>, Donghai Hong<sup>*</sup>, Jiaming Ji<sup>*</sup>, Jiacheng Zheng, Bowen Dong, Jiayi Zhou, Kaile Wang, Juntao Dai, Xuyao Wang, Wenqi Chen, Qirui Zheng, Wenxin Li, Sirui Han, Yike Guo, and Yaodong Yang<sup>†</sup>

[[**Project**]](https://pku-intermt.github.io/)
[[**Paper**]](https://arxiv.org/abs/2505.23950) 
<strong><span class='show_paper_citations' data='o23sDqkAAAAJ:roLk4NBRz8UC'></span></strong>
- This paper presents InterMT, the first preference dataset for multi-turn multimodal interaction, featuring 15.6k prompts and 32.4k human-labeled preference pairs, with a novel agentic workflow leveraging tool-augmented MLLMs to construct multi-turn QA instances and assess model capabilities through InterMT-Bench.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/papers/resist.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Language Models Resist Alignment](https://arxiv.org/abs/2406.06144)

Jiaming Ji<sup>*</sup>, Kaile Wang<sup>*</sup>, Tianyi Qiu<sup>*</sup>, **Boyuan Chen**<sup>*</sup>, Jiayi Zhou<sup>*</sup>, Changye Li, Hantao Lou, Juntao Dai, Yunhuai Liu, and Yaodong Yang<sup>†</sup>

[[**Project**]](https://pku-lm-resist-alignment.github.io/)
[[**Paper**]](https://arxiv.org/abs/2406.06144) 
<strong><span class='show_paper_citations' data='o23sDqkAAAAJ:IjCSPb-OGe4C'></span></strong>
- This paper makes the *first* exploration of LLM alignment *elasticity* from both theoretical and empirical perspectives, revealing that models tend to revert to pre-training behavior distribution after fine-tuning, with this elasticity *positively correlating* with model size and pre-training data scale.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/papers/pkusaferlhf.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PKU-SafeRLHF: Towards Multi-Level Safety Alignment for LLMs with Human Preference](https://arxiv.org/abs/2406.15513)

Jiaming Ji<sup>*α</sup>, Donghai Hong<sup>*α</sup>, Borong Zhang<sup>α</sup>, **Boyuan Chen**<sup>α</sup>, Josef Dai, Boren Zheng, Tianyi Qiu, Boxun Li, Yaodong Yang<sup>†</sup>


[[**Paper**]](https://arxiv.org/abs/2406.15513) 
[[**Data**]](https://huggingface.co/datasets/PKU-Alignment/PKU-SafeRLHF)
<strong><span class='show_paper_citations' data='o23sDqkAAAAJ:WF5omc3nYNoC'></span></strong>
- We introduce PKU-SafeRLHF, a comprehensive dataset for LLM safety alignment research, featuring 44.6k prompts and 265k QA pairs with safety meta-labels across 19 harm categories and three severity levels, along with 166.8k preference data for both dual-preference and single-preference scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 Oral</div><img src='images/papers/aligner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Aligner: Achieving Efficient Alignment through Learned Correction](https://arxiv.org/abs/2402.02416)

Jiaming Ji<sup>*</sup>, **Boyuan Chen**<sup>*</sup>, Hantao Lou, Donghai Hong, Borong Zhang, Xuehai Pan, Juntao Dai, and Yaodong Yang<sup>†</sup>

<strong><span style="color: #DC143C; font-weight: bold;">NeurIPS 2024 Oral (Top 0.45%)</span></strong>


[[**Project**]](https://pku-aligner.github.io/)
[[**Paper**]](https://arxiv.org/abs/2402.02416)
[[**Media**]](https://mp.weixin.qq.com/s/O9PP4Oc_Ee3R_HxKyd31Qg)
<strong><span class='show_paper_citations' data='o23sDqkAAAAJ:Tyk-4Ss8FVUC'></span></strong>
- We propose Aligner, a novel and simple alignment paradigm that learns correctional residuals between preferred and dispreferred answers using a small model, achieving comparable performance with significantly reduced computational costs while being model-agnostic and plug-and-play.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/papers/beavertails.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BEAVERTAILS: Towards Improved Safety Alignment of LLM via a Human-Preference Dataset](https://openreview.net/pdf?id=g0QovXbFw3)

Jiaming Ji<sup>*</sup>, Mickel Liu<sup>*</sup>, Juntao Dai<sup>*</sup>, Xuehai Pan, Chi Zhang, Ce Bian, **Boyuan Chen**, Ruiyang Sun, Yizhou Wang, Yaodong Yang<sup>†</sup>


[[**Project**]](https://sites.google.com/view/pku-beavertails)
[[**Paper**]](https://openreview.net/pdf?id=g0QovXbFw3)
<strong><span class='show_paper_citations' data='o23sDqkAAAAJ:u5HHmVD_uO8C'></span></strong>
- We introduce BEAVERTAILS, a large-scale dataset with 333,963 QA pairs and 361,903 expert comparisons, uniquely separating helpfulness and harmlessness annotations to advance LLM safety alignment research.
</div>
</div>

# Honors and Awards
- *2025* The Sixth Yuanpei Young Scholar Award
- *2024* SenseTime Scholarship (25/year in China, 1/25, ¥20000 RMB)
- *2024* Yicong Huang Scholarship (research innovation award, ¥8000 RMB)
- *2024* Research Excellence Award (¥5000 RMB)
- *2024* Ching-Ling Soong Future Scholarship (¥5000 RMB)
- *2024* Beijing Natural Science Foundation for Undergraduate Students (first batch; the sole recipient in the Peking University's intelligence field)
- *2023* Yicong Huang Scholarship (¥8000 RMB)
- *2023* Peking University Scholarship (¥4000 RMB)
- *2023* Peking University Public Service Scholarship (¥2000 RMB)
- *2022* Peking University Freshman Scholarship (¥10000 RMB)


# Invited Talks
- *2025.02*: DeepSeek-R1 Analysis and Sharing [[Video]](https://www.bilibili.com/video/BV1DJwRevE6d/?spm_id_from=333.999.0.0)
- *2024.09*: Technical details analysis about OpenAI o1 and Post-Training Scaling Law [[Video]](https://alignmentsurvey.com/talks/) [[Slides]](https://cby-pku.github.io//files/post-training-scaling-final.pdf)
- *2023.11*: Invited talk about [AI Alignment Survey](https://alignmentsurvey.com/) [[Video]](https://www.bilibili.com/video/BV1rj411L7XH/?spm_id_from=333.999.0.0&vd_source=b1ff6dcfa0111e176021e49d4a0ee142)

# Service

- Conference Reviewer for ICCV 2025, ICML 2025, ICLR 2025 (Notable Reviewer), NeurIPS 2025 & 2024
- Workshop Reviewer for ICML 2024 Workshop TiFA



# Blogs
Some thoughts on AI Alignment and Cognitive Reasoning
- [Intentionality](https://cby-pku.github.io/files/essays/intentionality.pdf), *2024.10*
- [Abstraction Reasoning](https://cby-pku.github.io/files/essays/abstraction_reasoning.pdf), *2024.09*
- [Causality](https://cby-pku.github.io/files/essays/causality.pdf), *2024.09*

# Educations
- *2022.09 - Present*, [Yuanpei College](https://yuanpei.pku.edu.cn/), Peking University
  
  Undergraduate Student in Artificial Intelligence

- *2023.05 - Present*, [PAIR Lab: PKU Alignment and Interaction Research Lab](https://pair-lab.com/)
  
  Research Intern
  
  Advisor: Prof. [Yaodong Yang](https://www.yangyaodong.com/) at [Institute for AI, Peking University](https://www.ai.pku.edu.cn/)

<a href='https://clustrmaps.com/site/1c03m'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=600&t=n&d=SyBiJ1Ugb-rc6fbLUU-lVXiLkH4XSENzuYg767o06-o&co=2d78ad&ct=ffffff'/></a>
