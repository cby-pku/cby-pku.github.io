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

I am a senior undergraduate majoring in Artificial Intelligence at Yuanpei College, [Peking University](https://english.pku.edu.cn/), advised by Prof. [Yaodong Yang](https://www.yangyaodong.com/). With over 1,900 Google Scholar citations, my work has been recognized with an ACL Best Paper Award, as well as NeurIPS Oral and Spotlight presentations. My open-source projects have accumulated 4k+ GitHub Stars, with models and datasets downloaded over 700k times by the community.

<details>
  <summary>关于我（中文）</summary>
  <p>
  陈博远，北京大学元培学院人工智能方向本科生，导师为杨耀东老师，研究方向为强化学习、大模型的安全与价值对齐、可扩展监督、前沿安全风险，曾在计算机顶会NeurIPS发表口头报告（前0.45%）、亮点论文等（前2.6%），荣获ACL 2025 最佳论文奖，谷歌学术引用累计1900余次，GitHub开源累计获得4k+ Star。曾获首批北京市自然科学基金资助（2023年度北京大学人工智能本科生唯一），商汤奖学金（全国仅25位），北京大学2025学生年度人物（全校10位）、北京大学五四奖学金（最高学生荣誉）等，研究成果及模型被OpenAI 、Meta引用，被新华社、光明日报、MIT Tech Review报道。受邀参加联合国秘书长科学顾问委员会讨论。
  </p>
</details>

🌟 I am currently fully devoted to an exciting new endeavor — stay tuned. 

# Undergraduate Research Overview

Throughout my undergraduate research, I have focused on reinforcement learning, the safety and value alignment of large models (*i.e.*, scalable oversight, deception alignment, and super alignment), with the overarching goal of constructing capable, autonomous, safe, and trustworthy AI systems.

<div style="text-align: center; margin: 1.5em 0;">
  <img src="files/research_statement.png" alt="Research Statement" style="max-width: 100%; border-radius: 4px;">
</div>

My undergraduate research focuses on two interconnected questions: how to construct capably, safe and trustworthy AI systems, and how to supervise and align superhuman AI systems. The latter is a natural progression of the former and also subsumes it, encompassing both the post-training enhancement of capabilities (*e.g.*, multimodal understanding and generation, and the realization of strong reasoning in systems like o3-level models) and the emergence of novel high-risk failure modes (*e.g.*, deception and alignment faking), along with their underlying mechanisms and potential solutions.



# News
- *2025.11*: &nbsp;🌟 We are thrilled to announce the release of the first comprehensive [AI Deception Report](https://www.arxiv.org/abs/2511.22619)! Our work has been recognized and referenced by the <font color="#DC143C"><b>UN Secretary-General's Scientific Advisory Board (UN SAB)</b></font>, and has received praise from leading scholars <b>Yoshua Bengio</b> and <b>Stuart Russell</b>.
- *2025.09*: &nbsp;🎉 Three papers have been accepted to NeurIPS 2025! Among them, [InterMT](https://arxiv.org/abs/2505.23950) was selected as a <font color="#DC143C"><b>Spotlight</b> (Top 2.6%)</font>.
- *2025.09*: &nbsp;🎉 Our work [AI Alignment: A Comprehensive Survey](https://dl.acm.org/doi/10.1145/3770749) has been accepted by <font color="#DC143C"><b>ACM Computing Surveys</b> Impact Factor: 28.0 </font>, (ranked 1/147 in Computer Science Theory & Methods) !
- *2025.09*: &nbsp;🎙️ We are excited to announce our latest work, **"Shadows of Intelligence: A Comprehensive Survey of AI Deception."** For more details, please visit [here](https://deceptionsurvey.com/).
- *2025.07*: &nbsp;🎉 Our work [Language Models Resist Alignment](https://arxiv.org/abs/2406.06144) has been awarded the <font color="#DC143C"><b>ACL 2025 Best Paper</b></font>!
- *2025.06*: &nbsp;🎊 Our work MedAligner has been accepted by <font color="#DC143C"><b>The Innovation</b> (IF: 33.2)</font> ! MedAligner demonstrates the potential of Aligner (our NeurIPS 2024 oral work) in the medical domain.
- *2025.06*: &nbsp;🎉 Two papers are accepted by ACL 2025 Main.
- *2025.05*: &nbsp;🎉 We open-source [InterMT](https://pku-intermt.github.io/), the first multi-turn multimodal understanding and generation human preference dataset. Welcome to discuss and collaborate!

<details markdown="1">
  <summary><font size="+1"><b>More news</b></font></summary>
- *2025.01*: &nbsp;🎉 We release [Align-DS-V](https://huggingface.co/PKU-Alignment/Align-DS-V), the first multimodal strong reasoning model.
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

# Undergraduate Publications
<small><sup>*</sup> denotes equal contribution, <sup>α</sup> denotes core contributors, and <sup>†</sup> denotes corresponding author</small>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/papers/intermt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InterMT: Multi-Turn Interleaved Preference Alignment with Human Feedback](https://arxiv.org/abs/2505.23950)

**Boyuan Chen**<sup>*</sup>, Donghai Hong<sup>*</sup>, Jiaming Ji<sup>*</sup>, Jiacheng Zheng, Bowen Dong, Jiayi Zhou, Kaile Wang, Juntao Dai, Xuyao Wang, Wenqi Chen, Qirui Zheng, Wenxin Li, Sirui Han, Yike Guo, and Yaodong Yang<sup>†</sup>

<strong><span style="color: #DC143C; font-weight: bold;">NeurIPS 2025 Spotlight (Top 2.6%)</span></strong>

[[**Project**]](https://pku-intermt.github.io/)
[[**Paper**]](https://arxiv.org/abs/2505.23950) 
<!-- <strong><span class='show_paper_citations' data='o23sDqkAAAAJ:roLk4NBRz8UC'></span></strong> -->
- This paper introduces **Data:** InterMT, a pioneering preference dataset for multi-turn multimodal interactions, comprising 15.6k prompts and 32.4k human-annotated preference pairs. It employs an innovative agentic workflow that utilizes tool-augmented MLLMs to generate multi-turn QA instances. **Algorithm:** The work proposes chain-prefix local and global preference modeling for training judge models, demonstrating *multi-turn scaling law*. **Evaluation:** The study evaluates model capabilities in multi-turn multimodal scenarios through InterMT-Bench.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/papers/resist.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Language Models Resist Alignment](https://arxiv.org/abs/2406.06144)

Jiaming Ji<sup>*</sup>, Kaile Wang<sup>*</sup>, Tianyi Qiu<sup>*</sup>, **Boyuan Chen**<sup>*</sup>, Jiayi Zhou<sup>*</sup>, Changye Li, Hantao Lou, Juntao Dai, Yunhuai Liu, and Yaodong Yang<sup>†</sup>

<strong><span style="color: #DC143C; font-weight: bold;">ACL 2025 Best Paper Award</span></strong>

[[**Project**]](https://pku-lm-resist-alignment.github.io/)
[[**Paper**]](https://arxiv.org/abs/2406.06144) 
<strong><span class='show_paper_citations' data='o23sDqkAAAAJ:IjCSPb-OGe4C'></span></strong>
- This paper makes the *first* exploration of LLM alignment *elasticity* from both theoretical and empirical perspectives, revealing that models tend to revert to pre-training behavior distribution after fine-tuning, with this elasticity *positively correlating* with model size and pre-training data scale.
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

# Journal
<small><sup>*</sup> denotes equal contribution, <sup>α</sup> denotes core contributors, and <sup>†</sup> denotes corresponding author</small>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">The Innovation</div><img src='images/papers/medaligner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Med-Aligner: Empowers LLM Medical Applications for complex medical scenarios](https://doi.org/10.1016/j.xinn.2025.101002)

Xiangbin Meng<sup>*</sup>, Jia-ming Ji<sup>*</sup>, Xiangyu Yan<sup>*</sup>, Jun-tao Dai, **Bo-yuan Chen**, Guan Wang, Hua Xu, Jing-jia Wang, Xu-liang Wang, Da Liu, Ming-qi Zheng, Rongzhou Wu, Chuanjie Wu, Yuwei Wu<sup>†</sup>, Wen-yao Wang<sup>†</sup>, Zhen Song<sup>†</sup>, and Yaodong Yang<sup>†</sup>

<strong><span style="color: #DC143C; font-weight: bold;">The Innovation (IF 33.2)</span></strong>

<!-- <strong><span class='show_paper_citations' data='o23sDqkAAAAJ:roLk4NBRz8UC'></span></strong> -->
- We introduce Med-Aligner, a plug-in alignment framework for LLMs that enables targeted medical calibration by learning correction residuals between preferred and non-preferred responses. Built as a 2-billion-parameter model using DeepSpeed and Transformer architecture, it is trained on 267,524 anonymized medical records from 21 departments spanning 4,353 disease types, achieving 90% cross-validation agreement through physician annotations following clinical guidelines.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Computing Surveys</div><img src='images/papers/alignmentsurvey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AI Alignment: A Comprehensive Survey](https://arxiv.org/abs/2310.19852)

Jiaming Ji<sup>*</sup>, Tianyi Qiu<sup>*</sup>, **Boyuan Chen**<sup>*</sup>, Borong Zhang<sup>*</sup>, Hantao Lou, Kaile Wang, Yawen Duan, Zhonghao He, Jiayi Zhou, Zhaowei Zhang, Fanzhi Zeng, Kwan Yee Ng, Juntao Dai, Xuehai Pan, Aidan O'Gara, Yingshan Lei, Hua Xu, Brian Tse, Jie Fu, Stephen McAleer, Yaodong Yang, Yizhou Wang, Song-Chun Zhu, Yike Guo, Wen Gao

<strong><span style="color: #DC143C; font-weight: bold;">ACM Computing Surveys (IF 28.0)</span></strong>

[[**Paper**]](https://arxiv.org/abs/2310.19852)
[[**Project**]](https://alignmentsurvey.com/)
<strong><span class='show_paper_citations' data='o23sDqkAAAAJ:u-x6o8ySG0sC'></span></strong>
- We present a comprehensive survey of AI alignment research, introducing the RICE principles (Robustness, Interpretability, Controllability, and Ethicality) and exploring both forward alignment (preference modeling, RLHF, scalable oversight) and backward alignment (assurance techniques, governance practices) approaches.
</div>
</div>


# Selected Preprints
You may head for my [Google Scholar profile](https://scholar.google.com/citations?view_op=list_works&hl=zh-CN&hl=zh-CN&user=o23sDqkAAAAJ) to view my other works!

<div class='paper-box'><div class='paper-box-image'><div><img src='images/papers/deceptionsurvey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AI Deception: Risks, Dynamics, and Controls](https://www.arxiv.org/abs/2511.22619)


**Boyuan Chen**<sup>*</sup>, Sitong Fang<sup>*</sup>, Jiaming Ji<sup>*</sup>, Yanxu Zhu<sup>*</sup>, Pengcheng Wen<sup>*</sup>, Jinzhou Wu<sup>*</sup>, ..., Yaodong Yang<sup>†</sup>, Philip Torr , Zhongyuan Wang, Tiejun Huang, Ya-qin Zhang, Hongjiang Zhang, Andrew Yao.

<sub><sup>*</sup> We thank all collaborators for their valuable feedback. Please see [project team](https://www.arxiv.org/abs/2511.22619) for reference</sub>


[[**Paper**]](https://www.arxiv.org/abs/2511.22619)
[[**Website**]](https://deceptionsurvey.com)


- As intelligence increases, so does its shadow. AI deception, in which systems induce false beliefs to
secure self-beneficial outcomes, has evolved from a speculative concern to an empirically demonstrated risk
across language models, AI agents, and emerging frontier systems. This survey provides a comprehensive and up-to-date overview of the field, defining AI deception through the lens of signaling theory and reviewing empirical studies that highlight its sociotechnical risks. We organize existing research into a **deception cycle** with two components: **emergence**, which analyzes incentive foundations, capability prerequisites (perception, planning, and performing), and contextual triggers such as supervision gaps and distributional shifts; and **treatment**, which encompasses detection methods, evaluation protocols, and mitigation strategies. We conclude by outlining key challenges and future directions, emphasizing the need for integrated technical, community, and governance approaches, and provide a living resource at [www.deceptionsurvey.com](http://www.deceptionsurvey.com)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/papers/alignanything.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Align Anything: Training All-Modality Models to Follow Instructions with Language Feedback](https://arxiv.org/abs/2412.15838)

Jiaming Ji<sup>*</sup>, Jiayi Zhou<sup>*</sup>, Hantao Lou<sup>*</sup>, **Boyuan Chen**<sup>*</sup>, Donghai Hong<sup>*</sup>, Xuyao Wang, Wenqi Chen, Kaile Wang, Rui Pan, Jiahao Li, Mohan Wang, Josef Dai, Tianyi Qiu, Hua Xu, Dong Li, Weipeng Chen, Jun Song, Bo Zheng, Yaodong Yang<sup>†</sup>

[[**Paper**]](https://arxiv.org/abs/2412.15838)
[[**Code**]](https://github.com/PKU-Alignment/align-anything) 
[[**Data**]](https://huggingface.co/datasets/PKU-Alignment/align-anything)
<strong><span class='show_paper_citations' data='o23sDqkAAAAJ:Y0pCki6q_DkC'></span></strong>
<strong><a href="https://github.com/PKU-Alignment/align-anything"><img src="https://img.shields.io/github/stars/PKU-Alignment/align-anything.svg?style=flat&logo=github&color=blue" alt="GitHub Repo stars"></a></strong>
- Motivated by the challenge of achieving all-modality human preference alignment, particularly the limitations of binary preferences in accurately reflecting human preferences, we introduce the **align-anything**: **Data**: align-anything-200k, which covers text, image, audio, video modalities, and 8+ specific subtasks, annotated with preference and language feedback; **Algorithm**: improving all-modality alignment by learning from language feedback; **Evaluation**: encompassing all-modality understanding and generation.
</div>
</div>


# Honors and Awards

- *2025* <span style="background-color: #FFFF99">Person of the Year of Peking University (10 people/year)</span>
- *2025* The First Taotian Scholarship of Peking University (¥10000 RMB)
- *2025* The First General Intelligence Scholarship of Peking University (¥5000 RMB)
- *2025* <span style="background-color: #FFFF99">May Fourth Scholarship (Highest-level Scholarship for Peking University)</span>
- *2025* The Huanyu Exploration Award (¥20000 RMB)  
  <details style="margin-left: 1em; margin-top: 0.3em;">
    <summary style="color: #666; font-size: 0.85em; cursor: pointer; outline: none;">More Info</summary>
    <div style="margin-top: 0.5em; padding: 0.8em; background-color: #f8f9fa; border-left: 3px solid #007acc; border-radius: 4px;">
      <p style="font-size: 0.9em; line-height: 1.5; margin: 0; color: #555;">
        The Huanyu Exploration Award, established by Peking University alumnus Mr. Xie Huanyu, honors the Yuanpei College philosophy of "Respect Nature, Express Individuality, and Pursue Common Growth." It recognizes students who demonstrate holistic development, intellectual independence, and innovative spirit through academic research, public service, and social practice.
      </p>
    </div>
  </details>
- *2025* Academic Innovation Award of Peking University
- *2025* Merit Student Pacesetter of Peking University (Ranked 1st out of 356 in the Academy)
- *2025* Dean's Scholarship (¥10000 RMB)
- *2025* The Sixth Yuanpei Young Scholar Award
- *2024* <span style="background-color: #FFFF99">SenseTime Scholarship (25/year in China, 1/25, ¥20000 RMB)</span>
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

- Conference Reviewer for ICCV 2025, ICML 2025, ICLR 2025 (Notable Reviewer), NeurIPS 2025 & 2024, ICLR 2026, ICML2026, ACL ARR and so on.
- Workshop Reviewer for ICML 2024 Workshop TiFA, NeurIPS Solar Workshop 
- Journal Reviewer for PLOS Digital Health and so on


# Blogs
Some thoughts on AI Alignment and Cognitive Reasoning
- [Intentionality](https://cby-pku.github.io/files/essays/intentionality.pdf), *2024.10*
- [Abstraction Reasoning](https://cby-pku.github.io/files/essays/abstraction_reasoning.pdf), *2024.09*
- [Causality](https://cby-pku.github.io/files/essays/causality.pdf), *2024.09*

# Educations
- *2022.09 - Present*, [Yuanpei College](https://yuanpei.pku.edu.cn/), Peking University
  
  Undergraduate Student in Artificial Intelligence

- *2023.05 - Present*, [PAIR Lab: PKU Alignment and Interaction Research Lab](https://pair-lab.com/)
  
  [PKU-Alignment Group](https://pku-alignment.group/), Research Intern
  
  Advisor: Prof. [Yaodong Yang](https://www.yangyaodong.com/) at [Institute for AI, Peking University](https://www.ai.pku.edu.cn/)

<a href='https://clustrmaps.com/site/1c03m'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=600&t=n&d=SyBiJ1Ugb-rc6fbLUU-lVXiLkH4XSENzuYg767o06-o&co=2d78ad&ct=ffffff'/></a>
