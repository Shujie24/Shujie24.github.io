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
* **M.Eng in Electrical Engineering and Computer Science**, University of California, Berkeley, 2024 - Present
  * cGPA: 3.98/4.00
  * Recipient of Fung Excellence Scholarship

* **Honours Bachelor of Science**, University of Toronto, 2019 - 2024
  * Computer Science and Mathematics Major, with Focus on Artificial Intelligence
  * cGPA: 3.91/4.00, Course Average: A+
  * Worked as a Teaching Assistant for CSC148: Introduction to Computer Science

**Selected Courses**: Natural Language Processing (NLP), Parallel Computing, LLM Agents, Neural Network and Deep Learning, Data Structures and Algorithm Design, Probability and Statistics, Operating Systems, Software Design, Databases, Computer Vision, Probabilistic Machine Learning, Computer Organization

Work Experience
======
* **Sep 2024 - Present: Research Assistant**
  * FHL Vive Center for Enhanced Reality, UC Berkeley
  * Supervised by Allen Yang
  * Researching Edge AI integration using Qualcomm AI Hub to develop end-to-end on-device LLM applications
  * Experimenting model distillation and integrating open-source LLMs Llama into Android app to enable robots actions using Kotlin
  * Collaborated with the UI/UX team to integrate a responsive frontend for Android app, incorporating speech-to-text capabilities for enhanced accessibility

* **May 2022 - Jul 2023: Machine Learning Engineer Intern**
  * Tealbook, Toronto, Ontario
  * Constructed, fine-tuned and optimized backend attribute supplier classifiers using BERT, GPT, XGBoost, LightGBM and RoBERTa for over 5 million supplier companies, increasing accuracy by 9% on average
  * Experimented on OpenAI APIs and Cohere API with few-shot learning and integrated with SerpAPI to improve supplier data quality using Dataflow and Airflow in Google Cloud Platform (GCP) in CI/CD pipeline
  * Designed metrics with BERTScore and F1 score to compare semantic similarity for regression models as validation pipeline with cross-functional teams

* **Apr 2023 - Apr 2024: Machine Learning Research Assistant**
  * Vector Institute, Toronto, Ontario
  * Supervised by Xujie Si
  * Led the project and benchmarked Large Language Models' logical reasoning ability with few-shot learning
  * Built a pipeline by integrating LLM and z3 solver with Retrieval Augmented Generation (RAG) to improve the reasoning performance of LLM
  * Improved accuracy for ProofWriter (16.7%), LogicalDeduction (8.7%), FOLIO (5.5%), ProntoQA (0.4%) datasets

* **May 2021 - Apr 2022: Data Science Researcher**
  * Department of Computer Science, University of Toronto
  * Supervised by Peter Marbach
  * Investigated the relationship between users' engagement and indicators of online social platforms
  * Conducted data mining, hypothesis test, and A/B Test using large-scale data from 57 sites with 50GB
  * Identified key engagement indicators for text-driven platforms to be coverage and thread size and visualized key insights by Matplotlib

Technical Skills
======
* **Languages**: Python (Proficient), C/C++, Java, SQL (PostgreSQL), R
* **Machine Learning Frameworks**: PyTorch, TensorFlow, NLTK, CUDA, AutoGen, LangChain, Hugging Face, NumPy
* **Developer Tools**: Git, Unix/Linux, Bash, Google Cloud Platform (BigQuery, Airflow), Agile Development, React
* **Software & Cloud Tools**: Docker, Kubernetes, Cloud Computing (GCP, Azure), Postman

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and Leadership
======
* Teaching Assistant for CSC148: Introduction to Computer Science at University of Toronto
* Active contributor to open-source machine learning projects
