# Hi, I'm Satyam Saxena 
AI/ML Researcher • Open‑source Developer • AI Ethics & Bias Mitigation • Advocate for Centrally‑Localized (On‑Device/Self‑Hosted) LLMs • Public Speaker

I build practical, privacy‑respecting AI systems that run locally and make a real impact. I care deeply about accessibility, model efficiency, and responsible AI. My work spans speech recognition, LLM fine‑tuning (LoRA), generative imaging, fuzzy logic control, and data tooling—always with a bias toward clear UX and simple, reproducible installs.

<!-- Badges -->
<p align="left">
  <img src="https://komarev.com/ghpvc/?username=SatyamSaxena1&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
  <a href="mailto:satyam.saxena11@yahoo.com"><img src="https://img.shields.io/badge/Email-satyam.saxena11%40yahoo.com-8B89CC?logo=minutemailer&logoColor=white" alt="Email badge"/></a>
  <a href="https://www.linkedin.com/in/satyam-saxena-754155134/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://www.kaggle.com/satyamsaxena12"><img src="https://img.shields.io/badge/Kaggle-satyamsaxena12-20BEFF?logo=kaggle&logoColor=white" alt="Kaggle"/></a>
  <a href="https://github.com/SatyamSaxena1?tab=followers"><img src="https://img.shields.io/github/followers/SatyamSaxena1?label=Followers&style=social" alt="GitHub followers"/></a>
</p>
<!-- PROJECT_LAUNCHPAD_START -->

---

## Portfolio Launchpad

<p>
  <a href="https://satyamsaxena1.github.io/">
    <img src="https://img.shields.io/badge/Open-Portfolio%20Site-bf3036?style=for-the-badge" alt="Open portfolio site"/>
  </a>
  <a href="https://github.com/SatyamSaxena1/SatyamSaxena1.github.io">
    <img src="https://img.shields.io/badge/View-Portfolio%20Source-24292f?style=for-the-badge&logo=github" alt="View portfolio source"/>
  </a>
  <a href="https://satyamsaxena1.github.io/railway/">
    <img src="https://img.shields.io/badge/Read-Railway%20Story-0f6e69?style=for-the-badge" alt="Read the railway project story"/>
  </a>
</p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://satyamsaxena1.github.io/">Portfolio Website</a></h3>
      <p>GitHub Pages portfolio for applied AI, railway inspection, GPS tooling, and public engineering projects.</p>
      <p><a href="https://satyamsaxena1.github.io/">Open site</a> | <a href="https://github.com/SatyamSaxena1/SatyamSaxena1.github.io">Source</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://satyamsaxena1.github.io/railway/">Railway Vision</a></h3>
      <p>Pantograph and overhead-line detection from cabin-camera video: 23,551 labelled frames, YOLO26x and RF-DETR, and the story of how it was built.</p>
      <p><a href="https://satyamsaxena1.github.io/railway/">Project story</a> | <a href="https://github.com/SatyamSaxena1/railway-overhead-line-detection">Documentation</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SatyamSaxena1/Subtitles-for-Visual-Impairment-Assistance-">Accessibility-First Live Speech Captions</a></h3>
      <p>Local, lightweight live transcription with modes for fast highlighted captions and longer continuous context.</p>
      <p><a href="https://github.com/SatyamSaxena1/Subtitles-for-Visual-Impairment-Assistance-">Open repo</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/SatyamSaxena1/fuzzy-logic-highway-proj">Intelligent Joining Speed on Highways</a></h3>
      <p>Fuzzy-logic merge-speed recommendation system using lane state, traffic density, vehicle distance, and rule-based inference.</p>
      <p><a href="https://github.com/SatyamSaxena1/fuzzy-logic-highway-proj">Open repo</a></p>
    </td>
  </tr>
</table>

<!-- PROJECT_LAUNCHPAD_END -->

---

## Featured: Railway Overhead-Line Detection (Data and Models)
- What: detecting the pantograph, masts, arms and contact points on overhead electrification from cabin-camera video, so that heights can be measured from a detection.
- The data: 23,551 frames from five Indian routes (Lucknow, Ahmedabad, Mehsana, Palanpur, Mumbai), annotated by me in CVAT. The full dataset is private and protected; a public write-up with sample frames is on Kaggle.
- How it was labelled: a small pretrained detector pre-annotates, tracking carries boxes between frames, and I review every frame by hand. I tried oriented boxes and dropped them, because for height measurement the top edge of a box must stay parallel to the bottom of the frame and rotation was extra work for no payoff.
- Models: YOLO26x (mAP@50:95 0.698) and RF-DETR Large (0.679), validated on different sets, so not a head-to-head ranking. Per-class scores, the data-prep steps, a development timeline and the known issues in the labels are in the write-up.
- Write-up and samples: https://www.kaggle.com/datasets/satyamsaxena12/railway-overhead-line-showcase
- Project story and documentation: https://satyamsaxena1.github.io/railway/ and https://github.com/SatyamSaxena1/railway-overhead-line-detection

---

## Featured: Accessibility‑First Live Speech Captions
- Project: Subtitles for Visual Impairment Assistance — local, lightweight live speech transcription
- Why I built it: After being diagnosed with ear injuries and dealing with intermittent tinnitus, I relied on Chrome’s live captions. When I switched to Firefox and lost that feature, I built a locally hosted, open‑source alternative with a simple install.
- Highlights:
  - Fully local; total footprint ~150 MB (deps + model)
  - Two modes:
    - Live: big, highlighted words in real time (TikTok/Reels‑style)
    - Comprehensive: continuous paragraph view for long talks where full context matters
  - Designed for accessibility, privacy, and low overhead
- Repo: https://github.com/SatyamSaxena1/Subtitles-for-Visual-Impairment-Assistance-



## Projects
- Intelligent Joining Speed on Highways (Fuzzy Logic)
  - A fuzzy‑logic system that ingests lane condition, oncoming traffic, lane density, vehicle distance, etc., and recommends near‑instant optimal merge speed using >100 rules with Gaussian/logistic/singleton membership functions.
  - Repo: https://github.com/SatyamSaxena1/fuzzy-logic-highway-proj

- Reddit Saved‑Posts → Mind‑Map/Notion Board
  - A WIP tool to analyze your exported saved posts (starting with Reddit), cluster/group them, and resurface forgotten ideas in a mood‑board style workflow.
  - Repo: https://github.com/SatyamSaxena1/reddit-scraper-for-mind-map-project

---

## Top Skills 
- AI/ML: Speech recognition and transcription, NLP/LLMs (prompting + LoRA fine‑tuning), fuzzy logic systems, recommender systems, classical ML
- Generative AI: Stable Diffusion (SDXL) pipelines, Kohya_ss training, BLIP, safetensors
- Optimization & Efficiency: LoRA, Adafactor, BF16 precision, small‑footprint local deployments
- Data: CSV ETL pipelines, structured data modeling, data segmentation, caption augmentation
- Tooling & Frameworks: PyTorch, Hugging Face Diffusers, OpenCV, Tableau
- Languages: Python, C++, R
- Platforms & Hardware: Anaconda, NVIDIA T4 / RTX 3080 Ti; Google Colab, AWS
- Communication: Public speaking, clear UX thinking, documentation, teamwork/leadership

---

## Tech Stack
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/Diffusers-FFAE00?logo=huggingface&logoColor=black" alt="Diffusers"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Stable%20Diffusion-SDXL-0A0A0A" alt="Stable Diffusion SDXL"/>
  <img src="https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white" alt="R"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?logo=c%2B%2B&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white" alt="Tableau"/>
  <img src="https://img.shields.io/badge/Anaconda-44A833?logo=anaconda&logoColor=white" alt="Anaconda"/>
  <img src="https://img.shields.io/badge/NVIDIA-76B900?logo=nvidia&logoColor=white" alt="NVIDIA"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=white" alt="Google Colab"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" alt="Git"/>
</p>

---

## Education
- MSc, Artificial Intelligence — Asia Pacific University of Technology and Innovation (APU/APIIT) & De Montfort University (Dual Degree), 2023–2024
  - Activities: Software Engineering Project Showcase, Open Source Contribution, Technology & Innovation Society, Programming Club
- B.Tech, Computer Science & Engineering — G.D. Goenka University, 2022 
  - Specialization in AI & Machine Learning

---

## What I care about
- Ethical AI and bias mitigation baked into the lifecycle
- Privacy‑first, centrally‑localized/on‑device LLMs
- Sustainable, efficient systems that are easy to install and use
- Sharing knowledge through open source and public speaking

---

## Get in touch
Email only: satyam.saxena11@yahoo.com
