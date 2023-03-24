---
layout: about
title: 🏡 workshop
permalink: /
subtitle: <i>Workshop at the International Conference on Machine Learning (ICML) 2023.</i>
---

## 🔥 the gist
* **what?** A workshop to bring together **interdisciplinary experts** working on the emerging research questions and challenges associated with **foundation model training and inference**.
* **when & where?**
  * Submit your papers by **`2023/05/31`** (see our [**📝 call for papers**](/call/) for details);
  * Attend the workshop, **`28-29th of July 2023 (TBC)`**, in **Honolulu, Hawaii**—or join us virtually.
  

![Banner](assets/img/banner.png){:width="512" .center-image}
*Code it, run it, crash it--restart it.*
{: style="color:gray; font-size: 80%; text-align: center;"}

## 🦾 the pitch

As models increase in size and training budget, they not only systematically improve in upstream quality, but also exhibit novel emergent capabilities. This increase in scale raises proportionate difficulties for practitioners: foundation model training and inference lie at a unique interdisciplinary crossroad, combining open problems in algorithms, system design, and software engineering. 

Machine learning practitioners are key stakeholders here: on the one hand, researchers may contribute algorithmic insights and novel methods to improving training and inference of large models; on the other hand, novel research findings may be best demonstrated at scale—which may require training models as efficiently as possible to make the best use of available resources. 

The goal of this workshop is to **bring together interdisciplinary experts working on the emerging research questions and challenges associated with foundation model training and inference**. We welcome submissions around training and inference systems/algorithms for foundation models, focusing on scaling-up or on reducing compute, time, memory, bandwidth, and energy requirements. Notably, we encourage submissions concerning the entire spectrum of foundation models: from BERT-sized Transformers, to large models with 100B+ parameters. Topics include but are not limited to (see our [**📝 call for papers**](/call/) for details): 
* **Training and inference systems**, either distributed at large scale or in resource-constrained scenarios;
* **Algorithms for improved training and inference efficiency**;
* **Systems for foundation models**, such as novel programming languages or compilers. 

<br>

## 📆 the plan
*(timings are provided tentatively while we wait for the logistics to be confirmed, all times HST, UTC-10)*

|   | Topic                                                                 | Speaker                                                                                |
|--------------------|-----------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| 8:45am      | *Opening remarks*                                                     |                                                                                        |
| 9:00am     | **Session I: Training Strategies and Libraries**                      |                                                                                        |
|                    | Scaling Up Models and Data with `t5x` and `seqio`                     | Adam Roberts <br> *(Google Research)*                                                         |
|                    | Using Megatron to Train Large Language Models               | Deepak Narayanan <br> *(Microsoft Research)*                                                  |
|                    | Training Large Language Models on Cerebras Wafer-Scale Clusters       | Natalia Vassilieva <br> *(Cerebras)*                                                          |
| 10:15am    | **Contributed Talk 1**                                                |                                                                                        |
| 10:30am    | *Coffee break*                                                        |                                                                                        |
| 10:35am      | **Contributed Talk 2**                                                |                                                                                        |
| 11:00am       | **Session II: Efficient Inference**                                   |                                                                                        |
|                    | The Case for 4-bit Inference                                          | Tim Dettmers <br> *(University of Washington)*                                                |
|                    | Efficienly Scaling Transformer Inference                              | Aakanksha Chowdhery <br> *(Google Research)*                                                  |
| noon           | *Lunch break*                                                         |                                                                                        |
| 1pm            | **Session III: Deep Optimization**                                    |                                                                                        |
|                    | PyTorch 2.x: Faster, More Pythonic, and as Dynamic as Ever            | Natalia Gimelshein <br> *(Meta)*                                                              |
| 2pm         | **Contributed Talk 3**  
| 2:15pm      | **Poster session**  |                                                                                        |
| 3:15pm      | *Coffee break*                                                        |                                                                                        |
 | 3:30pm      | **Panel: Large Language Models Tooling Across Industry and Academia** | Anna Goldie *(Anthropic)*, <br>Rishi Bommasani *(Stanford University)*,<br> Susan Zhang *(Meta)*,<br> Emily Weber *(AWS)* | |                                                                                        |
| 4:30pm      | **Session IV: Collaborative Approaches**                              |                                                                                        |
|                    | Distributed Systems for Decentralized AI                              | Ce Zhang <br> *(ETH, Together)*                                                                    |
|                    | Open Tooling for Large Language Models                                | Thomas Wang <br> *(HuggingFace)*                                                              |
| 5:30pm      | **Awards**                                                            |                                                                                        |

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

## 💬 the panelists 

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

