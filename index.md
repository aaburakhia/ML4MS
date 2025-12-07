---
layout: default
title: Home
---

# ML4MS: Machine Learning for Materials Science
**The Engineering Layer for Artificial Intelligence**

---

### 🔭 The Mission
The gap between **Academic AI** (finding new crystals) and **Industrial Engineering** (Asset Integrity) is too wide.

**ML4MS** is a knowledge initiative dedicated to scouting emerging technologies and critiquing their viability for safety-critical operations. We move beyond "Chatbots" to build **Engineering Agents** that respect physics, adhere to global standards (NACE, API, ASTM), and operate with zero-trust architecture.

---

## 📝 Latest Research & Insights

<!-- START AUTOMATED LOOP -->
<!-- This code automatically grabs every file in your _posts folder -->

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
**{{ post.date | date: "%b %d, %Y" }}** | *Topic: {{ post.categories | join: ', ' }}*

{{ post.excerpt | strip_html | truncatewords: 40 }}

[**📖 Read Full Deep Dive →**]({{ post.url | relative_url }})

---
{% endfor %}

<!-- END AUTOMATED LOOP -->

## 🧭 The Research Radar
*Active investigations at the intersection of AI and Heavy Industry.*

#### 1. Accelerated Discovery & Generative Design
Investigating how Generative Adversarial Networks (GANs) and Diffusion Models are creating new alloy compositions.

#### 2. Physics-Informed Machine Learning (PINNs)
Moving beyond traditional Finite Element Analysis (FEA). Exploring how neural networks can solve differential equations for corrosion rates 100x faster.

#### 3. Computer Vision in Characterization
Automating the analysis of SEM (Scanning Electron Microscopy) and metallography images.

---

### 📡 Automated Intelligence Pipeline
*Behind the scenes of ML4MS*

To keep this initiative current, I maintain an automated **n8n data pipeline** that scans pre-print servers (arXiv) and major journals daily. It uses Natural Language Processing to filter noise and surface high-impact research.

---

### 👤 About the Editor
**Ahmed Aburakhia**
*Senior Materials & Project Engineer*

I am an engineer first, and a data scientist second. My goal with ML4MS is to strip away the hype and find the tools that actually solve problems in the physical world.

*   [**Connect on LinkedIn**](https://www.linkedin.com/in/ahmedaburakhia/)
*   [**View Portfolio on GitHub**](https://github.com/aaburakhia?tab=repositories)
