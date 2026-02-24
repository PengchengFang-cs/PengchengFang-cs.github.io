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

Mr. Pengcheng Fang received his Bachelor's degree from Shanxi University in China, followed by a Master's degree from Lancaster University. He is a PhD candidate at the University of Southampton, supervised by [Prof. Xiaohao Cai](He is a PhD candidate at the University of Southampton, supervised by [Prof. Xiaohao Cai](https://xiaohaocai.netlify.app/) and [Dr. Jianshi](https://www.southampton.ac.uk/people/5x96vy/doctor-jian-shi).


After completing his master's degree, Dr. Fang worked in China as an algorithm engineer, focusing primarily on computer vision applications. He served as a research team lead at two publicly listed companies, where he led the development and deployment of several successful consumer-facing (C-end) and enterprise-level (B-end) AI projects. These real-world experiences provided him with deep insights into the practical challenges of applying machine learning at scale. Motivated by a strong interest in scientific research and innovation, he later resigned from industry and pursued a Ph.D. in the United Kingdom to further explore cutting-edge research in artificial intelligence.

Mr. Fang is currently engaged in several interdisciplinary research projects at the intersection of artificial intelligence and real-world applications. His work focuses on:

* Human motion generation, where he explores generative models and transformer-based architectures for producing realistic and controllable movements from textual or sensory inputs.

* Multimodal foundation models, aiming to unify visual, textual, and structural data for improved perception, understanding, and reasoning across domains.

* Multi-object tracking (MOT), particularly in complex and unconstrained environments, using deep tracking-by-detection methods and video transformers.

* Wildlife biometrics, focusing on animal identification and behavior analysis using computer vision, with an emphasis on non-invasive recognition of species such as donkeys in natural settings.

* Medical image reconstruction and segmentation, where he applies lightweight Mamba-based models and diffusion techniques to enhance MRI imaging and improve diagnostic accuracy.

* His research integrates model efficiency, representation learning, and real-world deployment concerns, with applications ranging from intelligent surveillance to conservation and healthcare.

# ✨ News 
- 🔥 **[2026-02-24]**, Our MRI reconstruction project BridgeMamba: Frequency–Spatial Bridging for Undersampled MRI Segmentation is accepted by CVPR!
- 🔥 **[2026-02-24]**, Our Motion Generation project [MotionDuet: Dual-Conditioned 3D Human Motion Generation with Video-Regularized Text Learning](https://arxiv.org/pdf/2511.18209) is accepted by CVPR!
- 🔥 **[2025-11-20]**, Our MRI reconstruction project [HiFi-Mamba: Dual-Stream W-Laplacian Enhanced Mamba for High-Fidelity MRI Reconstruction](https://arxiv.org/pdf/2508.09179) is accepted by AAAI!  
- 🔥 **[2025-11-20]**, Our Motion Generation project [MOGO: Residual Quantized Hierarchical Causal Transformer for High-Quality and Real-Time 3D Human Motion Generation](https://arxiv.org/pdf/2506.05952) is accepted by AAAI! 
- 🔥 **[2025-06-19] Breaking News**: Our AI-powered donkey recognition project has been featured on <img src="images/bbc_black.svg" alt="BBC Logo" width="48"/>[BBC News](https://www.bbc.co.uk/news/articles/cgrxjd1l2p1o). Our GitHub and dataset will be open-sourced soon.
- ✅ **[2025-06-03]**, Our motion generation project [MOGO](https://github.com/MiRECoFu/Mogo) is now open-source on GitHub! 
- ✅ **[2024-09-03]**, Our remote-sensing segmentation project [Hi-ResNet](https://github.com/AmberJar/Prior) is now open-source on GitHub! 

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI2026</div><img src='images/mambav1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HiFi-Mamba: Dual-Stream W-Laplacian Enhanced Mamba for High-Fidelity MRI Reconstruction](https://arxiv.org/pdf/2508.09179)

Hongli Chen<sup>★</sup>, **Pengcheng Fang**<sup>★</sup>, Yuxia Chen, Xiaohao Cai, Yingxuan Ren, Jing Hao, Fangfang Tang, Xiaohao Cai, Shanshan Shan, Feng Liu

- The paper “HiFi-Mamba: Dual-Stream W-Laplacian Enhanced Mamba for High-Fidelity MRI Reconstruction” presents HiFi-Mamba, a frequency-aware dual-stream architecture for MRI reconstruction. By coupling a w-Laplacian block for spectral decoupling with a
guided Mamba block that models global anatomy while integrating high-frequency details.
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

Yuxia Chenx<sup>★</sup>, **Pengcheng Fang**<sup>★</sup>, Xiaoling Zhong, Jianhui Yu, Xiaoming Zhang, Tianrui Li

- The paper "Hi‑ResNet: Edge Detail Enhancement for High‑Resolution Remote Sensing Segmentation" proposes a novel segmentation network tailored for high-resolution remote sensing images. It introduces a funnel module for high-res semantic extraction and a multi-branch Information Aggregation (IA) module to capture multi-scale object variations. Additionally, a Class-agnostic Edge Aware (CEA) loss is designed to enhance boundary accuracy. The method achieves strong performance on benchmarks like LoveDA, Potsdam, and Vaihingen.
</div>
</div>

# 🎓 Educations
- *2024.07 - 2028.07 (now)*, PhD, University of Southampton, Southampton, UK.
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
