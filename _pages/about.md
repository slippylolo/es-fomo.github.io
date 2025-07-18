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
- The deadline is **May 27**, 2025 11:59PM UTC time - **one-day extension for US Memorial Day**.
- Camera-ready deadline is **July 03**, 2025 11:59PM UTC time - **extension for OpenReview crashing**.
<!-- Find us in room **Lehar 2**, and check-out the schedule below, and the accepted papers on [OpenReview](https://openreview.net/group?id=ICML.cc/2024/Workshop/ES-FoMo-II&referrer=%5BHomepage%5D(%2F)). -->


## 🔥 the gist

* **what?** A workshop to bring together **interdisciplinary experts** working on the emerging research questions and challenges associated with **foundation model training and inference**.
* **when & where?**
  * Join us at **[ICML 2025](https://icml.cc)** in Vancouver!
* **questions?** Contact us at `esfomo.workshop@gmail.com`.

<!-- * **looking for the 2024 edition?**
  * Check out the [2024 workshop page](/2024)! -->

<!-- <br> -->

## 📆 the plan
*All times PT. Full schedule to be confirmed.*

|         | Topic    | Speaker        |
|---------|----------|----------------|
| 8:30am  | **Opening Remarks**      |     |
| 8:40am  | Invited Talk   | Hagay Lupesko: Zero to 50 ExaFLOPS in under a year - lessons from the trenches <br> **(Cerebras Systems)**          |
| 9:10am  | Invited Talk   | Wanchao Liang: TorchTitan: a PyTorch native platform for training foundation models <br> **(Thinking Machines)**                |
| 9:40am | **Coffee break**                |                               |
| 10:00am | Invited Talk | Baris Kasikci: The Quest For Blazingly Fast LLM Serving <br> **(University of Washington)**             |
|         | **Orals Session 1**     |                          |
| 10:30am | Oral    | FPTQuant: Function-Preserving Transforms for LLM Quantization         |
| 10:45am | Oral    | Cartridges: Lightweight and general-purpose long context representations via self-study         |
| 11:00am | Oral    | zip2zip: Inference-Time Adaptive Vocabularies for Language Models via Token Compression         |
| 11:15am | Spotlight Lightning Talks     | TBA                       |
| 11:30am | **Lunch Break**  |  |
| 1:00pm | 🧑‍🎓  **Poster Session**           |                    |
| 2:30pm  | Invited Talk    | Avanika Narayan: Minions: Cost-efficient Collaboration Between On-device and Cloud Language Models <br> **(Stanford / Rox)** |
| 3:00pm  | **Coffee break**   |   |
|         | **Orals Session 2**   |    |
| 3:30pm | Oral    | Any-Order GPT as Masked Diffusion Model: Decoupling Formulation and Architecture         |
| 3:45pm | Oral    | Hardware-Efficient Attention for Fast Decoding         |
| 4:00pm  | Invited Talk    | Zachary Charles: Making Communication-Efficient Language Model Training Reliable and Scalable with DiLoCo <br> **(Google)**    |
| 4:30pm  | **Closing Remarks / Awards** |  |

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

This year, we're excited to welcome a number of excellent speakers, watch out for more soon!

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
