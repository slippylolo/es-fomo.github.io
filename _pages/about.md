---
layout: about
title: 🏡 workshop
permalink: /
subtitle: <i>Workshop at the International Conference on Machine Learning (ICML) 2025.</i>
---

![Banner](assets/img/banner.png){:width="512" .center-image}
*Code it, run it, crash it--restart it.*
{: style="color:gray; font-size: 80%; text-align: center;"}

➡️ **ES-FoMO is back for ICML 2025!** Submissions are live on [OpenReview](https://openreview.net/group?id=ICML.cc/2025/Workshop/ES-FoMo-III)!
- The deadline is May 19, 2025 11:59PM UTC time.
<!-- Find us in room **Lehar 2**, and check-out the schedule below, and the accepted papers on [OpenReview](https://openreview.net/group?id=ICML.cc/2024/Workshop/ES-FoMo-II&referrer=%5BHomepage%5D(%2F)). -->


## 🔥 the gist

* **what?** A workshop to bring together **interdisciplinary experts** working on the emerging research questions and challenges associated with **foundation model training and inference**.
* **when & where?**
  * Join us at **[ICML 2025](https://icml.cc)** in Vancouver!
* **questions?** Contact us at `esfomo.workshop@gmail.com`.
<!-- * **looking for the 2024 edition?**
  * Check out the [2024 workshop page](/2024)! -->

<!-- <br> -->

<!-- ## 📆 the plan
*All times CET, UTC+2. Full schedule to be confirmed.*

|         | Topic                                                                                                                    | Speaker                                               |
|---------|--------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
|         | **🎛️ Session I: Quantization, Pruning, and Sparsity**                                                                   |                                                       |
| 9:00am  | Talk: **Efficient Quantization Methods and Marlin, a Fast 4-Bit Inference Kernel**                                       | Elias Frantar <br> *(IST Austria)*                    |
| 9:30am  | Oral: [Prompt-prompted Adaptive Structured Pruning for Efficient LLM Generation](https://arxiv.org/html/2404.01365v1)    | Harry Dong <br> *(CMU)*                               |
| 9:45am  | Oral: [Lottery Ticket Adaptation: Mitigating Destructive Inference in LLMs](https://arxiv.org/abs/2406.16797)            | Ashwinee Panda <br> *(Princeton)*                        |
| 10:00am | *Coffee break*                                                                                                           |                                                       |
|         | **🦾 Session II: Emerging Architectures**                                                                                |                                                       |
| 10:15am | Oral: [Simple Linear Attention Language Models Balance the Recall-Throughput Tradeoff](https://arxiv.org/abs/2402.18668) | Simran Arora <br> *(Stanford)*                        |
| 10:30am | Oral: [xLSTM: Extended Long Short-Term Memory](https://arxiv.org/abs/2405.04517)                                         | Maximilian Beck <br> *(JKU)*                          |
| 10:45am | Talk: **On the Tradeoffs of State-Space Models**                                                                         | Albert Gu <br> *(CMU)*                                |
| 11:15am | Talk: **Scaling Mixture-of-Experts: Lessons from DBRX**                                                                  | Vitaliy Chiley <br> *(Databricks)*                    |
| 11:45am | Oral: [Characterising Prompt Compression Methods for Long Context Inference](https://arxiv.org/abs/2407.08892)           | Siddharth Jha <br> *(UCB)*                            |
| noon    | *Lunch break*                                                                                                            |                                                       |
| 1:00pm  | 🧑‍🎓 **Poster Session**                                                                                                 |                                                       |
| 2:15pm  | 🏅 **Best Paper and Best Poster Awards**                                                                                 |                                                       |
|         | **🔥 Session III: Hardware**                                                                                             |                                                       |
| 2:30pm  | Talk: **Scaling Intelligence**                                                                                           | Azalia Mirhoseini <br> *(Stanford / Google DeepMind)* |
| 3:00pm  | Off-the-record: **Frontier Clusters for Frontier Models: Scaling to 100,000 GPUs and Beyond**                            | Dylan Patel <br> *(SemiAnalysis)*                     |
| 3:30pm  | *Coffee break*                                                                                                           |                                                       |
| 3:45pm  | 💬 **Panel: Data and Architecture Trends Across Industry and Open Communities**                                          |                                                       |
|         | Deepak Narayanan (NVIDIA), Dylan Patel (SemiAnalysis), Dirk Groeneveld (AI2), Hailey Schoelkopf (EleutherAI)             |                                                       |
| 4:30pm  | 💾 **Session IV: Data**                                                                                                  |                                                       |
|         | **Open Tooling for Large Data Pipelines**                                                                                | Vaishaal Shankar <br> *(Apple)*                       |
| 6:00pm  | 🎉 **Post-workshop happy hour**                                                                                          |                                                       | -->

<br>

## 🦾 the pitch

As models increase in size and training budget, they not only systematically improve in upstream quality, but also exhibit novel emergent capabilities. This increase in scale raises proportionate difficulties for practitioners: foundation model training and inference lie at a unique interdisciplinary crossroad, combining open problems in algorithms, system design, and software engineering. 

Machine learning practitioners are key stakeholders here: on the one hand, researchers may contribute algorithmic insights and novel methods to improving training and inference of large models; on the other hand, novel research findings may be best demonstrated at scale—which may require training models as efficiently as possible to make the best use of available resources. 

The goal of this workshop is to **bring together interdisciplinary experts working on the emerging research questions and challenges associated with foundation model training and inference**. We welcome submissions around training and inference systems/algorithms for foundation models, focusing on scaling-up or on reducing compute, time, memory, bandwidth, and energy requirements. Notably, we encourage submissions concerning the entire spectrum of foundation models: from BERT-sized Transformers, to large models with 100B+ parameters. Topics include but are not limited to (see our [**📝 call for papers**](/call/) for details): 
* **Training and inference systems**, either distributed at large scale or in resource-constrained scenarios;
* **Algorithms for improved training and inference efficiency**;
* **Systems for foundation models**, such as novel programming languages or compilers. 

This is the **third installment** of ES-FoMo; we are bringing further focus in our sessions and talks on two trends observed in 2024 and early 2025:
* **Test-time compute**, popularized by Open AI o1 and DeepSeek r1
* **Emergence of new modeling paradigms and modalities** sucha s real-time video and decentralized training

We look forward to continuing to grow this community at ICML 2025!

<br>

## 🧑‍🏫 the speakers

This year, we're excited to welcome a number of excellent speakers, watch out for the list soon!

## 😎 the organizers

<div class="projects">
  {%- assign sorted_projects = site.projects | sort: "importance" | where: "category", "organizer" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
</div>
