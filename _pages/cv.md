---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* METU - Middle East Technical University
  * B.S. in Computer Engineering - Sep. 2018, Jul. 2022
    * CGPA: 3.99/4.00 - Ranked 2𝑛𝑑/168 
  * B.S. in Mathematics (Double Major) - Sep. 2019, Jul. 2022
* EPFL (Ecole Polytechnique Federale de Lausanne)
  * M.S. in Computer Science - Sep. 2022, Jul. 2024 (Expected)

Work experience
======
* Edge Delta - Seattle, USA (Remote)
  * Software Engineer - Jun. 2022, Current 
  * Designed and implemented advanced log searching functionality,that enables users to search for complex queries
  * Increased log search user experience by adding a tool that links query syntax with visualization of the filters using typescript.
  * Enhanced automation and efficiency byworkingonKubernetesCronjobsandbashscripts.

* FileMap - Ankara, Turkey
  * Software Engineer Intern - Feb. 2021, Mar. 2021
  * Increased usage analysis and performance evaluation by developing utility tools using Javascript and Node.js.
  * Provided viable feature improvement directions by analyzing the literature and verifying the products against customer requirements.

* KOVAN Research Laboratory - Ankara, Turkey
  * Research Engineer Intern - Jul. 2020 -- Aug. 2020
  * Created a Deep-Q reinforcement learning model that would learn the weights on the causal graph using the data obtained from IKEA Furniture Assembly Environment.

Projects
======
* EpflGPT - Spring 2023
  * ChatGPT like dialogue assistant in the area of education.
  * Collected interaction data by using prompting strategies and data augmentation.
  * Trained a reward model to be used for reinforcement learning from human feedback (RLHF) using the GPT-2 model from Hugging Face.
  * Trained a dialogue model by supervised learning and (RLHF) using the Flan-T5 model from Hugging Face.

* Nori - Spring 2023
  * Implemented octree optimization structure, ray tracer, next event estimation, path tracer with multiple importance sampling, and microfacet brdf using C++. 
  * Extended by implementing textures, image based lighting, homogeneous participating media, and Disney BSDF using C++.

* Make It Stand 3D - Fall 2023
  * Replicated the algorithm of the paper ("Make it stand: balancing shapes for 3d fabrication")[https://igl.ethz.ch/projects/make-it-stand/make-it-stand-siggraph-2013-prevost-et-al.pdf] to make objects stand in a desired pose under gravity. 
  * Implemented inner carving and minimal shape deformation for tetramesh representations.

* Trap - Sep. 2021, Jul. 2022
  * Implemented state-of-the-art machine learning models that make use of RL and NLP for technical analysis of algorithmic trading strategies.
  * Developed an end-to-end web app with React and Django.

* MaskSplit - Spring 2021
  * Introduced a new paradigm that removes laborious training data labeling needs from few show semantic segmentation by adding self-supervision to a meta-learning-based approach.
  * Created the data pipeline and the evaluation metrics for few-shot semantic segmentation models using PyTorch.

* Timed Automata Relaxation for Reachability - Spring 2020
  *  Automated the procedure of using MILP on the constraint set to minimize the total change in the bounds.
  *  Created a data pipeline between our tool and (Imitator)[https://www.imitator.fr/] that let us do extensive analysis of our results.
  
Awards
======
* Top 79/6373 teams (1st place in Switzerland) IEEEXtreme 16.0 Programming Competition 
  * Online - 2022
* Semifinalist at the ICPC Southwestern Europe Regional Contest (SWERC)
  * Milan, Italy - 2022
* Third place at METU Guided Research Symposium
  * Ankara, Turkey - 2021

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
