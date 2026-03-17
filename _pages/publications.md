---
permalink: /publications/
title: "Publications"
author_profile: true
---

# Undergraduate Research Overview

Throughout my undergraduate research, I have focused on reinforcement learning, the safety and value alignment of large models (*i.e.*, scalable oversight, deception alignment, and super alignment), with the overarching goal of constructing capable, autonomous, safe, and trustworthy AI systems.

<div style="text-align: center; margin: 1.5em 0;">
  <img src="/files/research_statement.png" alt="Research Statement" style="max-width: 100%; border-radius: 4px;">
</div>

My undergraduate research focuses on two interconnected questions: how to construct capably, safe and trustworthy AI systems, and how to supervise and align superhuman AI systems. The latter is a natural progression of the former and also subsumes it, encompassing both the post-training enhancement of capabilities (*e.g.*, multimodal understanding and generation, and the realization of strong reasoning in systems like o3-level models) and the emergence of novel high-risk failure modes (*e.g.*, deception and alignment faking), along with their underlying mechanisms and potential solutions.



# Undergraduate Publications
<small><sup>*</sup> denotes equal contribution, <sup>α</sup> denotes core contributors, and <sup>†</sup> denotes corresponding author</small>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='/images/papers/intermt.png' alt="sym" width="100%"></div></div>
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='/images/papers/resist.png' alt="sym" width="100%"></div></div>
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


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 Oral</div><img src='/images/papers/aligner.png' alt="sym" width="100%"></div></div>
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


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='/images/papers/pkusaferlhf.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PKU-SafeRLHF: Towards Multi-Level Safety Alignment for LLMs with Human Preference](https://arxiv.org/abs/2406.15513)

Jiaming Ji<sup>*α</sup>, Donghai Hong<sup>*α</sup>, Borong Zhang<sup>α</sup>, **Boyuan Chen**<sup>α</sup>, Josef Dai, Boren Zheng, Tianyi Qiu, Boxun Li, Yaodong Yang<sup>†</sup>


[[**Paper**]](https://arxiv.org/abs/2406.15513)
[[**Data**]](https://huggingface.co/datasets/PKU-Alignment/PKU-SafeRLHF)
<strong><span class='show_paper_citations' data='o23sDqkAAAAJ:WF5omc3nYNoC'></span></strong>
- We introduce PKU-SafeRLHF, a comprehensive dataset for LLM safety alignment research, featuring 44.6k prompts and 265k QA pairs with safety meta-labels across 19 harm categories and three severity levels, along with 166.8k preference data for both dual-preference and single-preference scenarios.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='/images/papers/beavertails.png' alt="sym" width="100%"></div></div>
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


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">The Innovation</div><img src='/images/papers/medaligner.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Med-Aligner: Empowers LLM Medical Applications for complex medical scenarios](https://doi.org/10.1016/j.xinn.2025.101002)

Xiangbin Meng<sup>*</sup>, Jia-ming Ji<sup>*</sup>, Xiangyu Yan<sup>*</sup>, Jun-tao Dai, **Bo-yuan Chen**, Guan Wang, Hua Xu, Jing-jia Wang, Xu-liang Wang, Da Liu, Ming-qi Zheng, Rongzhou Wu, Chuanjie Wu, Yuwei Wu<sup>†</sup>, Wen-yao Wang<sup>†</sup>, Zhen Song<sup>†</sup>, and Yaodong Yang<sup>†</sup>

<strong><span style="color: #DC143C; font-weight: bold;">The Innovation (IF 33.2)</span></strong>

<!-- <strong><span class='show_paper_citations' data='o23sDqkAAAAJ:roLk4NBRz8UC'></span></strong> -->
- We introduce Med-Aligner, a plug-in alignment framework for LLMs that enables targeted medical calibration by learning correction residuals between preferred and non-preferred responses. Built as a 2-billion-parameter model using DeepSpeed and Transformer architecture, it is trained on 267,524 anonymized medical records from 21 departments spanning 4,353 disease types, achieving 90% cross-validation agreement through physician annotations following clinical guidelines.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Computing Surveys</div><img src='/images/papers/alignmentsurvey.png' alt="sym" width="100%"></div></div>
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

<div class='paper-box'><div class='paper-box-image'><div><img src='/images/papers/deceptionsurvey.png' alt="sym" width="100%"></div></div>
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



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='/images/papers/alignanything.png' alt="sym" width="100%"></div></div>
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
