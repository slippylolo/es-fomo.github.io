---
layout: about
title: 🏡 workshop
permalink: /
subtitle: <i>Workshop at the International Conference on Machine Learning (ICML) 2024.</i>
---

![Banner](assets/img/banner.png){:width="512" .center-image}
*Code it, run it, crash it--restart it.*
{: style="color:gray; font-size: 80%; text-align: center;"}

➡️ **ES-FoMO is back for ICML 2024!** Check-out our [**📝 call for papers**](/call/), deadline **3rd of June** for submissions!

## 🔥 the gist

* **what?** A workshop to bring together **interdisciplinary experts** working on the emerging research questions and challenges associated with **foundation model training and inference**.
* **when & where?**
  * Join us at **[ICML 2024](https://icml.cc)**, either virtually or [physically](https://maps.app.goo.gl/9Vf8oroxYyiUf2bb7) in Vienna;  
  * **Submit your papers** on OpenReview (coming soon!), see the [**📝 call for papers**](/call/) for more information.
* **questions?** Contact us at `esfomo.workshop@gmail.com`.
* **looking for the 2023 edition?**
  * Check-out the **recorded talks and panels**, on the **[official ICML platform](https://icml.cc/virtual/2023/workshop/21479)**;
  * Check-out the **accepted papers** on **[OpenReview](https://openreview.net/group?id=ICML.cc/2023/Workshop/ES-FoMO)**.

<br>

## 📆 the plan
*All times CET, UTC+2. Full schedule to be confirmed.*

|        | Topic                                                                                                                  | Speaker                               |
|--------|------------------------------------------------------------------------------------------------------------------------|---------------------------------------|
| 9:00am | *Opening remarks*                                                                                                      |                                       |
| 9:15am | **📈 Session I: Emerging Architectures**                                                                               |                                       |
|        | Mixture-of-Experts: Scaling and Tradeoffs at Training and Inference                                                    | Abhinav Venigalla <br> *(Databricks)* |
|        | A Deep Dive into State-Space Models                                                                                    | Albert Gu <br> *(Carnegie Mellon)*    |
| 10:15am | 🎤 **Contributed Talk 1**                                                                                              |                                       |
| 10:30am | *Coffee break*                                                                                                         |                                       |
| 10:45am | 🎤 **Contributed Talk 2**                                                                                              |                                       |
| 11:00am | 🚀 **Session II: Efficient (and Open) Implementations**                                                                |                                       |
|        | Efficient Quantization Methods and Marlin, a Fast 4-Bit Inference Kernel                                               | Elias Frantar <br> *(IST Austria)*    |
|        | TBC                                                                                                                    |                                       |
| noon   | *Lunch break*                                                                                                          |                                       |
| 1:00pm | 🧑‍🎓 **Poster Session**                                                                                               |                                       |
| 2:00pm | 💬 **Panel: Data and Architecture Trends Across Industry and Open Communities**                                        |                                       |
|        | Aakanksha Chowdhery (Google DeepMind), Dylan Patel (SemiAnalysis), Stella Biderman (EleutherAI)--more to be announced! |                                       |
|        | *Moderators TBC.*                                                                                                      |                                       |
| 3:00pm | 🎤 **Contributed Talk 3**                                                                                              |                                       |
| 3:15pm | *Coffee break*                                                                                                         |                                       |
| 3:30pm | 🎤 **Contributed Talk 2**                                                                                              |                                       |
| 3:45pm | ⚙️ **Session III: Data Tooling and Hardware**                                                                          |                                       |
|        | Hardware for Efficient Machine Learning                                                                                | Azalia Mirhoseini <br> *(Stanford)*   |
|        | Open Tooling for Large Data Pipelines                                                                                  | Ludwig Schmidt <br> *(MIT/LAION)*     |
| 4:45pm | 🏅 **Awards**                                                                                                          |                                       |
| 6:00pm | 🎉 **Post-workshop happy hour**                                                                                        |                |

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
