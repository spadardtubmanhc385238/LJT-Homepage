---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<h1 id="about" class="page__title">About</h1>

**Junteng Liu** is currently a first-year Ph.D. candidate in Computer Science (2024-Present) at the **Hong Kong University of Science and Technology (HKUST)**, where he is a member of the **HKUST NLP Group** led and supervised by **Professor Junxian He**. Prior to his doctoral studies, he completed his **B.Eng.** degree (2020-2024) at **Shanghai Jiao Tong University (SJTU)**, graduating in June 2024. During his undergraduate studies at SJTU, he was also previously advised by **Professor Junxian He**.

His research focuses on **natural language processing (NLP)** and **machine learning (ML)**. His publications include first-author works such as [*SynLogic: Synthesizing Verifiable Reasoning Data at Scale for Learning Logical Reasoning and Beyond*](/publication/2025-01-01-synlogic) (2025), [*On the Perception Bottleneck of VLMs for Chart Understanding*](/publication/2025-01-02-perception-bottleneck-vlm) (2025), and [*On the Universal Truthfulness Hyperplane Inside LLMs*](/publication/2024-01-01-universal-truthfulness-hyperplane) (EMNLP 2024), along with co-authored papers at ICML 2024 and NeurIPS 2023.

## Academic Background

- **Ph.D. in Computer Science (2024-Present)**
  - **Hong Kong University of Science and Technology (HKUST)**
  - **HKUST NLP Group**, supervised by **Professor Junxian He**
- **B.Eng. (2020-2024)**
  - **Shanghai Jiao Tong University (SJTU)**, graduated in **June 2024**
  - Previously advised by **Professor Junxian He** during undergraduate studies
- **Honors & Awards**
  - **Zhiyuan Honor Scholarship**, awarded by **Shanghai Jiao Tong University (SJTU)**

## Research Experience

- **Research Intern** at **MINIMAX** | *February 2025 - Present*
  - Worked on LLM reasoning (including *SynLogic: Synthesizing Verifiable Reasoning Data at Scale for Learning Logical Reasoning and Beyond*, published on Arxiv in 2025).
- **Research Intern** at **Tencent WXG** | *June 2024 - September 2024*
  - Advisor: **Zifei Shan**
  - Worked on vision-language models and chart understanding (*On the Perception Bottleneck of VLMs for Chart Understanding*, published on Arxiv in 2025, code repository: *Vision4Chart*).
- **Research Intern** at **Shanghai AI Lab** | *June 2023 - December 2023*
  - Advisor: **Prof. Yu Cheng**
  - Worked on LLM truthfulness and interpretability (*On the Universal Truthfulness Hyperplane Inside LLMs*, published at EMNLP 2024, code repository: *Universal_Truthfulness_Hyperplane*).

## Skills

- **Natural Language Processing (NLP)**
- **Machine Learning (ML)**
- **LLM Reasoning and Reinforcement Learning**
- **Hallucination in Vision-Language Models (VLM)**
- **LLM Truthfulness and Interpretability** (LLM truthfulness and Interpretability)

## Publications

### Conference Papers

1. **SynLogic: Synthesizing Verifiable Reasoning Data at Scale for Learning Logical Reasoning and Beyond** *(2025, First author)*
   - **Authors**: **Junteng Liu**, Yuanxiang Fan, Zhuo Jiang, Han Ding, Yongyi Hu, Chi Zhang, Yiqi Shi, Shitong Weng, Aili Chen, Shiqi Chen, Yunan Huang, Mozhi Zhang, Pengyu Zhao, Junjie Yan, Junxian He
   - **Venue**: Arxiv
   - **Links**: [Code repository (GitHub)](https://github.com/Vicent0205)

2. **On the Perception Bottleneck of VLMs for Chart Understanding** *(2025, First author)*
   - **Authors**: **Junteng Liu**, Weihao Zeng, Xiwen Zhang, Yijun Wang, Zifei Shan, Junxian He
   - **Venue**: Arxiv
   - **Links**: [GitHub code repository: Vision4Chart](https://github.com/hkust-nlp/Vision4Chart)

3. **On the Universal Truthfulness Hyperplane Inside LLMs** *(EMNLP 2024 - Conference on Empirical Methods in Natural Language Processing, 2024, First author)*
   - **Authors**: **Junteng Liu**, Shiqi Chen, Yu Cheng, Junxian He
   - **Venue**: EMNLP 2024 (Conference on Empirical Methods in Natural Language Processing)
   - **Links**: [GitHub code repository: Universal_Truthfulness_Hyperplane](https://github.com/hkust-nlp/Universal_Truthfulness_Hyperplane)

4. **In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation** *(ICML 2024 - International Conference on Machine Learning, 2024, Co-author)*
   - **Authors**: Shiqi Chen, Miao Xiong, **Junteng Liu**, Zhengxuan Wu, Teng Xiao, Siyang Gao, Junxian He
   - **Venue**: ICML 2024 (International Conference on Machine Learning)

5. **C-Eval: A Multi-Level Multi-Discipline Chinese Evaluation Suite for Foundation Models** *(NeurIPS 2023 - Neural Information Processing Systems, 2023, Co-author)*
   - **Authors**: Yuzhen Huang, Yuzhuo Bai, Zhihao Zhu, Junlei Zhang, Jinghan Zhang, Tangjun Su, **Junteng Liu**, Chuancheng Lv, Yikai Zhang, Jiayi Lei, Yao Fu, Maosong Sun, Junxian He
   - **Venue**: NeurIPS 2023 (Neural Information Processing Systems)

6. **Composing Parameter-Efficient Modules with Arithmetic Operations** *(NeurIPS 2023 - Neural Information Processing Systems, 2023, Co-author)*
   - **Authors**: Jinghan Zhang, Shiqi Chen, **Junteng Liu**, Junxian He
   - **Venue**: NeurIPS 2023 (Neural Information Processing Systems)

### Selected Publications (Jekyll Collection)

{% include base_path %}
{% if site.publication_category %}
  {% for category in site.publication_category %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

## Contact Information

- **Email**: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub**: [Vicent0205](https://github.com/Vicent0205) (`https://github.com/Vicent0205`)
- **Google Scholar Profile**: [https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter)**: [@junteng88716710](https://twitter.com/junteng88716710) (`@junteng88716710`)
