---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🧑‍ About Me 

I am **Pengcheng Fang (方鹏程)**, a PhD candidate at the **University of Southampton**, supervised by [Prof. Xiaohao Cai](https://xiaohaocai.netlify.app/) and [Dr. Jian Shi](https://www.southampton.ac.uk/people/5x96vy/doctor-jian-shi). I am currently a research intern in **Prof. Shengjin Wang's group at Tsinghua University**, Department of Electronic Engineering, working on world models and embodied intelligence.


My research focuses on **learning representations and dynamics for motion generation and intelligent action**. I study controllable human motion generation, the role of future information in world action models, and structured neural operators. My work combines method development and theoretical analysis with empirical evaluation; **CHASM**, for example, studies the structure of spectral token operators through a shared channel basis across frequencies.

My current research interests include:

* **Human motion generation:** motion representations, generative modeling, and control through text, video, and sparse motion constraints.

* **World models and embodied intelligence:** future-aware action learning, robot manipulation, and learning from egocentric observations.

* **Neural operators and efficient architectures:** spectral modeling, structured operators, and analysis of their representational properties.

* **Multimodal understanding:** visual grounding, hallucination mechanisms, and reliable vision-language models.

Before my PhD, I worked as an algorithm engineer on computer vision and deployed AI systems. I received my master's degree from Lancaster University and my bachelor's degree from Shanxi University. I also collaborate on applications in medical imaging and wildlife conservation.

# ✨ News 
- 🔥 **[2026-09]** Two papers accepted at **NeurIPS 2026**: [CHASM](https://arxiv.org/abs/2605.14727) on spectral neural operators and [Dual-Pathway Circuits](https://arxiv.org/abs/2605.13156) on object hallucination in vision-language models!
- **[2026-08]** I joined Prof. Shengjin Wang's group at **Tsinghua University** as a research intern, working on world models and embodied intelligence.
- 🔥 **[2026-02-24]**, Our MRI segmentation project BridgeMamba: Frequency–Spatial Bridging for Undersampled MRI Segmentation is accepted by ISMRM!
- 🔥 **[2026-02-24]**, Our Motion Generation project [MotionDuet: Dual-Conditioned 3D Human Motion Generation with Video-Regularized Text Learning](https://arxiv.org/pdf/2511.18209) is accepted by CVPR!
- 🔥 **[2025-11-20]**, Our MRI reconstruction project [HiFi-Mamba: Dual-Stream W-Laplacian Enhanced Mamba for High-Fidelity MRI Reconstruction](https://arxiv.org/pdf/2508.09179) is accepted by AAAI!  
- 🔥 **[2025-11-20]**, Our Motion Generation project [MOGO: Residual Quantized Hierarchical Causal Transformer for High-Quality and Real-Time 3D Human Motion Generation](https://arxiv.org/pdf/2506.05952) is accepted by AAAI! 
- 🔥 **[2025-06-19] Breaking News**: Our AI-powered donkey recognition project has been featured on <img src="images/bbc_black.svg" alt="BBC Logo" width="48"/>[BBC News](https://www.bbc.co.uk/news/articles/cgrxjd1l2p1o). Our GitHub and dataset will be open-sourced soon.
- ✅ **[2025-06-03]**, Our motion generation project [MOGO](https://github.com/MiRECoFu/Mogo) is now open-source on GitHub! 
- ✅ **[2024-09-03]**, Our remote-sensing segmentation project [Hi-ResNet](https://github.com/AmberJar/Prior) is now open-source on GitHub! 

# 📝 Publications

<sup>★</sup> Equal contribution. Preprints are listed separately below.

<div class="paper-box paper-box--text-only">
<div class="paper-box-text" markdown="1">

<span class="publication-venue">NeurIPS 2026</span>

**[CHASM: Cross-frequency Harmonized Axis-Separable Mixing for Spectral Token Operators](https://arxiv.org/abs/2605.14727)**

**Pengcheng Fang**, Hongli Chen, Yuxia Chen, Tengjiao Sun, Jiaxin Liu, Xiaohao Cai

A structured spectral neural operator with a shared channel basis and frequency-specific gains. The work combines analysis of the resulting operator family with evaluations on image reconstruction and segmentation.

</div>
</div>

<div class="paper-box paper-box--text-only">
<div class="paper-box-text" markdown="1">

<span class="publication-venue">NeurIPS 2026</span>

**[Dual-Pathway Circuits of Object Hallucination in Vision-Language Models](https://arxiv.org/abs/2605.13156)**

Jiaxin Liu, Ding Zhong, Yue Wang, Zhidong Yang, Zhaolu Kang, Guangyuan Dong, Qishi Zhan, **Pengcheng Fang**, Aofan Liu

A causal investigation of visual grounding and object hallucination in vision-language models, identifying distinct internal pathways and evaluating targeted interventions.

</div>
</div>

<div class="paper-box paper-box--text-only">
<div class="paper-box-text" markdown="1">

<span class="publication-venue">CVPR 2026</span>

**[MotionDuet: Dual-Conditioned 3D Human Motion Generation with Video-Regularized Text Learning](https://arxiv.org/abs/2511.18209)**

Yi-Yang Zhang<sup>★</sup>, Tengjiao Sun<sup>★</sup>, **Pengcheng Fang**<sup>★</sup>, Deng-Bao Wang, Xiaohao Cai, Min-Ling Zhang, Hansung Kim

Controllable 3D human motion generation that combines textual semantics with video-derived motion cues, using cross-modal alignment to connect the two conditions.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI2026</div><img src='images/mambav1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HiFi-Mamba: Dual-Stream W-Laplacian Enhanced Mamba for High-Fidelity MRI Reconstruction](https://arxiv.org/pdf/2508.09179)

Hongli Chen<sup>★</sup>, **Pengcheng Fang**<sup>★</sup>, Yuxia Chen, Yingxuan Ren, Jing Hao, Fangfang Tang, Xiaohao Cai, Shanshan Shan, Feng Liu

A dual-stream architecture for MRI reconstruction that combines W-Laplacian spectral decomposition with Mamba-based modeling of global anatomy and high-frequency detail.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI2026</div><img src='images/mogo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MOGO: Residual Quantized Hierarchical Causal Transformer for High-Quality and Real-Time 3D Human Motion Generation](https://arxiv.org/pdf/2506.05952)

Dongjie Fu<sup>★</sup>, Tengjiao Sun<sup>★</sup>, **Pengcheng Fang**<sup>★</sup>, Xiaohao Cai, Hansung Kim

- The paper “MOGO: Residual Quantized Hierarchical Causal Transformer for High‑Quality and Real‑Time 3D Human Motion Generation” presents MOGO, an autoregressive transformer designed for efficient, on‑the‑fly 3D motion synthesis. It features residual quantization and a hierarchical causal structure to balance fidelity and real-time responsiveness. The framework achieves state-of-the-art motion quality while enabling streaming generation. It’s validated on benchmark datasets, demonstrating both high quality and low latency performance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Journal</div><img src='images/hiresnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hi-ResNet: Edge Detail Enhancement for High-Resolution Remote Sensing Segmentation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10638169)

Yuxia Chen<sup>★</sup>, **Pengcheng Fang**<sup>★</sup>, Xiaoling Zhong, Jianhui Yu, Xiaoming Zhang, Tianrui Li

- The paper "Hi‑ResNet: Edge Detail Enhancement for High‑Resolution Remote Sensing Segmentation" proposes a novel segmentation network tailored for high-resolution remote sensing images. It introduces a funnel module for high-res semantic extraction and a multi-branch Information Aggregation (IA) module to capture multi-scale object variations. Additionally, a Class-agnostic Edge Aware (CEA) loss is designed to enhance boundary accuracy. The method achieves strong performance on benchmarks like LoveDA, Potsdam, and Vaihingen.
</div>
</div>

## Selected Preprints

The following works are publicly available on arXiv and are listed as preprints.

<div class="paper-box paper-box--text-only">
<div class="paper-box-text" markdown="1">

<span class="publication-venue publication-venue--preprint">arXiv 2026 · Preprint</span>

**[Privileged Foresight Distillation: Zero-Cost Future Correction for World Action Models](https://arxiv.org/abs/2604.25859)**

**Pengcheng Fang**, Hongli Chen, Xiaohao Cai

Distills future-conditioned action corrections from a training-time teacher into a policy that observes only the current frame, avoiding future-video generation at inference.

</div>
</div>

<div class="paper-box paper-box--text-only">
<div class="paper-box-text" markdown="1">

<span class="publication-venue publication-venue--preprint">arXiv 2026 · Preprint</span>

**[MoGeFlow: Flowing Through Motion Codebook Geometry for Text-to-Motion Generation](https://arxiv.org/abs/2606.11656)**

**Pengcheng Fang**, Tengjiao Sun, Xiaoyu Zhan, Xiaohao Cai, Dongjie Fu

Uses the geometry of learned motion codebooks to guide text-conditioned continuous flow, then maps generated states to valid discrete motion codes for decoding.

</div>
</div>

# 🎓 Educations
- *2024.07 - 2027.07 (expected)*, PhD, University of Southampton, Southampton, UK.
- *2019.01 - 2020.11*, Master, Lancaster University, Lancaster, UK.
- *2014.09 - 2018.07*, Undergraduate, Shanxi University, Shanxi, China.

# 📅 Events
- *2024.07 - now*, Cooperated with The Isle of Wight Donkey Sanctuary on wildlife protection.
- *2023.06*, Invited talk at Greater Bay Area Industrial Expo.

## 🛠 Projects
### 🔹 *2024.08 – now* **Isle of Wight Donkey Sanctuary & International Partners｜AI for Donkey Biometrics and Conservation**
- Partnered with the **Isle of Wight Donkey Sanctuary (UK)** and a **Canadian animal welfare organization** to develop an AI-based donkey identification and behavior monitoring system.
- Designed a lightweight, non-invasive biometric recognition pipeline using facial and morphological features for long-term tracking in sanctuary environments.
- Collected and curated a diverse, real-world donkey dataset under varying environmental conditions to support research in animal biometrics and AI robustness.
- Integrated motion analysis and pose estimation to monitor health indicators and behavioral anomalies, enabling proactive welfare management.
- Supported ethical and environmentally conscious AI deployment through offline inference and minimal equipment footprint.
- Facilitated international collaboration on animal welfare technologies and aligned with global conservation goals by planning open access to the dataset and models.
- 📢 The project reflects a strong intersection of **applied AI**, **wildlife protection**, and **academic support**, and was recently featured in <img src="images/bbc_black.svg" alt="BBC Logo" width="48"/>[BBC News](https://www.bbc.co.uk/news/articles/cgrxjd1l2p1o).


### 🔹 *2023.10 – 2024.01* **Thunder Software Technology Co., Ltd.｜Railway Fault Detection and Industrial Visual Inspection**
- Developed vision-based systems for comprehensive railway infrastructure monitoring in collaboration with Hitachi Rail.
- Built a vehicle recognition and tracking module to monitor train entry and exit across key transit points.
- Designed fault detection pipelines to identify potential mechanical anomalies on trains, including component wear and structural irregularities.
- Implemented visual inspection techniques to detect risks on signal towers, such as loose or corroded fasteners and alignment issues.
- Integrated geospatial localization to associate detection results with real-world coordinates, supporting intelligent maintenance scheduling.
- Supported deployment by adapting outputs to Japanese railway engineering standards and infrastructure protocols.



---

### 🔹 *2023.01 – 2023.10* **Aerospace｜AI Digital Human for Metaverse Interaction**
- Developed an interactive AI digital human system capable of generating real-time multimodal responses from user input text.
- Leveraged GPT for multi-turn natural language understanding and dialogue generation.
- Supported user-selected avatars that respond with synchronized voice and facial animation:
  - Employed a fine-tuned VITS-Chinese model to synthesize high-quality speech.
  - Adapted and enhanced the WavLip model to generate lip movements aligned with the synthesized audio.
- Seamlessly integrated text, voice, and animation to produce lifelike avatar responses.
- Deployed the end-to-end system in Unity and Unreal Engine environments, enabling immersive metaverse interactions.


---

### 🔹 *2023.01 – 2023.10* **Aerospace｜GPT-powered Game Intelligence Engine**
- Designed dynamic storylines and dialogue using large language models.
- Built an event reasoning module to maintain world consistency.
- Enabled text-based control and multi-agent memory management.

---

### 🔹 *2022.07 – 2023.01* **Aerospace｜CityGen: Rapid 3D Urban Modeling System**
- Built an automated pipeline to generate city-scale 3D models within days, supporting rapid urban modeling at the scale of entire districts or cities.
- Applied a remote sensing segmentation model to classify seven categories from satellite imagery: buildings, streets, vegetation (grass, forest), rivers, greenhouses, and wasteland.
- Designed an attribute inference algorithm to assign semantic and physical properties (e.g., height, material type, layout constraints) based on detection results and contextual rules.
- Integrated stereo vision techniques to enhance 3D structure estimation for key regions such as building clusters and terrain variations.
- Generated detailed, attribute-rich 3D meshes compatible with urban simulation and smart city visualization platforms.


---

### 🔹 *2021.10 – 2022.05* **NetThink Technology Group Co., Ltd.｜CAD Drawing Recognition and Auto-review System**
- Recognized telecommunication symbols and cable routes in CAD blueprints using deep learning and OCR.
- Built automatic auditing tools to validate engineering plans.
- Streamlined the quality assurance process for engineering drawings.

---

### 🔹 *2021.07 – 2021.12* **NetThink Technology Group Co., Ltd.｜Fiber Distribution Box Structure Recognition**
- Detected fiber layout, ports, and labels inside optical distribution boxes.
- Built structural models for cable routing and fault diagnostics.
- Integrated system into field inspection tools for telecom engineers.

---

### 🔹 *2021.03 – 2021.07* **NetThink Technology Group Co., Ltd.｜Knowledge Graph and GNN-based User Profiling**
- Constructed enterprise-level knowledge graphs connecting people, roles, and behaviors.
- Designed GCN/GAT models for relation modeling and user profiling.
- Supported applications in risk detection and personalized recommendation.



# 💻 Working Experiences
- *2023.10 - 2024.03*, Thunder Software Technology.
- *2022.07 - 2023.10*, Chengdu Guoxing Aerospace Technology.
- *2021.03 - 2022.07*, NetThink Technology Group.
