---
layout: about
title: 🏡 workshop
permalink: /
subtitle: <i>Workshop at the International Conference on Machine Learning (ICML) 2024.</i>
---

![Banner](assets/img/banner.png){:width="512" .center-image}
*Code it, run it, crash it--restart it.*
{: style="color:gray; font-size: 80%; text-align: center;"}

➡️ **ES-FoMO is back for ICML 2024!** Check-out the schedule below, and the accepted papers on [OpenReview](https://openreview.net/group?id=ICML.cc/2024/Workshop/ES-FoMo-II&referrer=%5BHomepage%5D(%2F)#tab-your-consoles).


## 🔥 the gist

* **what?** A workshop to bring together **interdisciplinary experts** working on the emerging research questions and challenges associated with **foundation model training and inference**.
* **when & where?**
  * Join us at **[ICML 2024](https://icml.cc)**, either virtually or [physically](https://maps.app.goo.gl/9Vf8oroxYyiUf2bb7) in Vienna.
* **questions?** Contact us at `esfomo.workshop@gmail.com`.
* **looking for the 2023 edition?**
  * Check-out the **recorded talks and panels**, on the **[official ICML platform](https://icml.cc/virtual/2023/workshop/21479)**;
  * Check-out the **accepted papers** on **[OpenReview](https://openreview.net/group?id=ICML.cc/2023/Workshop/ES-FoMO)**.

<br>

## 📆 the plan
*All times CET, UTC+2. Full schedule to be confirmed.*

|         | Topic                                                                                                                    | Speaker                                   |
|---------|--------------------------------------------------------------------------------------------------------------------------|-------------------------------------------|
|         | **🎛️ Session I: Quantization, Pruning, and Sparsity**                                                                   |                                           |
| 9:00am  | Talk: **Efficient Quantization Methods and Marlin, a Fast 4-Bit Inference Kernel**                                       | Elias Frantar <br> *(IST Austria)*        |
| 9:30am  | Oral: [Prompt-prompted Adaptive Structured Pruning for Efficient LLM Generation](https://arxiv.org/html/2404.01365v1)    | Harry Dong <br> *(CMU)*                   |
| 9:45am  | Oral: [Lottery Ticket Adaptation: Mitigating Destructive Inference in LLMs](https://arxiv.org/abs/2406.16797)            | Berivan Isik <br> *(Stanford)*            |
| 10:00am | *Coffee break*                                                                                                           |                                           |
|         | **🦾 Session II: Emerging Architectures**                                                                                |                                           |
| 10:15am | Oral: [Simple Linear Attention Language Models Balance the Recall-Throughput Tradeoff](https://arxiv.org/abs/2402.18668) | Simran Arora <br> *(Stanford)*            |
| 10:30am | Oral: [xLSTM: Extended Long Short-Term Memory](https://arxiv.org/abs/2405.04517)                                         | Maximilian Beck <br> *(JKU)*              |
| 10:45am | Talk: **A Deep Dive into State-Space Models**                                                                            | Albert Gu <br> *(CMU)*                    |
| 11:15am | Talk: **Scaling Mixture-of-Experts: Lessons from DBRX**                                                                  | Vitaliy Chiley <br> *(Databricks)*        |
| 11:45am | Oral: [Characterising Prompt Compression Methods for Long Context Inference](https://arxiv.org/abs/2407.08892)           | Siddharth Jha <br> *(UCB)*                |
| noon    | *Lunch break*                                                                                                            |                                           |
| 1:00pm  | 🧑‍🎓 **Poster Session**                                                                                                 |                                           |
| 2:15pm  | 🏅 **Best Paper and Best Poster Awards**                                                                                 |                                           |
|         | **🔥 Session III: Hardware**                                                                                             |                                           |
| 2:30pm  | Talk: **Hardware for Efficient Machine Learning**                                                                        | Azalia Mirhoseini <br> *(Google)* |
| 3:00pm  | Off-the-record: **Frontier Clusters for Frontier Models: Scaling to 100,000 GPUs and Beyond**                            | Dylan Patel <br> *(SemiAnalysis)*         |
| 3:30pm  | *Coffee break*                                                                                                           |                                           |
| 3:45pm  | 💬 **Panel: Data and Architecture Trends Across Industry and Open Communities**                                          |                                           |
|         | Aakanksha Chowdhery (Google DeepMind), Dylan Patel (SemiAnalysis), Dirk Groeneveld (AI2)                                 |                                           |
|         | *Moderators TBA*                                                                                                         |                                           |
| 4:30pm  | 💾 **Session IV: Data**                                                                                                  |                                           |
|         | **Open Tooling for Large Data Pipelines**                                                                                | Ludwig Schmidt <br> *(MIT/LAION)*         |
| 6:00pm  | 🎉 **Post-workshop happy hour**                                                                                          |                                           |

<br>

## 🦾 the pitch

As models increase in size and training budget, they not only systematically improve in upstream quality, but also exhibit novel emergent capabilities. This increase in scale raises proportionate difficulties for practitioners: foundation model training and inference lie at a unique interdisciplinary crossroad, combining open problems in algorithms, system design, and software engineering. 

Machine learning practitioners are key stakeholders here: on the one hand, researchers may contribute algorithmic insights and novel methods to improving training and inference of large models; on the other hand, novel research findings may be best demonstrated at scale—which may require training models as efficiently as possible to make the best use of available resources. 

The goal of this workshop is to **bring together interdisciplinary experts working on the emerging research questions and challenges associated with foundation model training and inference**. We welcome submissions around training and inference systems/algorithms for foundation models, focusing on scaling-up or on reducing compute, time, memory, bandwidth, and energy requirements. Notably, we encourage submissions concerning the entire spectrum of foundation models: from BERT-sized Transformers, to large models with 100B+ parameters. Topics include but are not limited to (see our [**📝 call for papers**](/call/) for details): 
* **Training and inference systems**, either distributed at large scale or in resource-constrained scenarios;
* **Algorithms for improved training and inference efficiency**;
* **Systems for foundation models**, such as novel programming languages or compilers. 

This is the **second installment** of ES-FoMo; we are bringing further focus in our sessions and talks on three trends observed in 2023:
* **The emergence of novel architectures**, popularized by [Mamba](https://arxiv.org/abs/2312.00752) (state-space models) and [Mixtral](https://arxiv.org/abs/2401.04088) (mixture-of-experts);
* **Efficient open implementations**, such as [`gpt-fast`](https://github.com/pytorch-labs/gpt-fast) and [vLLM](https://github.com/vllm-project/vllm);
* **Open questions on novel hardware and data tooling.**

<br>

## 🧑‍🏫 the speakers

<div class="projects">
  {%- assign sorted_projects = site.projects | sort: "importance" | where: "category", "speaker" -%}
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

<br>

## 💬 the panelists (& moderators)

<div class="projects">
  {%- assign sorted_projects = site.projects | sort: "importance" | where: "category", "panelist" -%}
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

<br>

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
