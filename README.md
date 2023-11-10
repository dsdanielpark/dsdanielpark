
### *Hello, I'm Daniel Park*

<div align=right>

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/dsdanielpark/)](https://www.linkedin.com/in/dsdanielpark/) 
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fdsdanielpark&count_bg=%23000000&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=ProfileViews&edge_flat=false)](https://hits.seeyoufarm.com)
<!--<a href="https://www.buymeacoffee.com/parkminwoo"><img src="https://cdn.buymeacoffee.com/buttons/v2/arial-orange.png" height="20px"></a>-->
</div>

- I am training to become a developer with insight and an engineer with skill and wit.
- With deep expertise in various domains, such as largen language model, bioinformatics, computer vision, and natural language processing, I have tackled complex challenges in different industries.
- Currently, I am focusing on advancing the field of Korean natural language processing and the state-of-the-art LLM (Language Model) technology.
- I believe that all the knowledge I have gained will converge at the end of my journey.

<br>

<p align="center">
<a href="https://github.com/dsdanielpark">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=dsdanielpark&show_icons=true&theme=nord&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=dsdanielpark&layout=compact&langs_count=8&theme=nord"/>
</a>
</p>



<br>

## Portfolio Contents
_On 2023-11-07, I have decided to make the majority of open-source repositories and Hugging Face models **private**._
- [*Large Language Model*](#large-language-model)
- [*Huggingface*](#huggingface)
- [*Projects*](#projects)
- [*Packages*](#packages)
- [*Dockerhub*](#dockerhub)
- [*Work Experience*](#work-experience)



<br>

***

### *Large Language Model*
- The code for LLM projects will remain private. Due to ethical issues, the model's performance will be disclosed once it is verified after development.
- **sLLM, Jindo**: Jindo is a relatively small sLLM that includes various experiments. It aims to develop multi-modal and domain-specific highly personalized models, but it is not recommended for general use as it is primarily used for experiments.
- **GORANI:** The project is actively underway. GORANI is being developed as an English language model for comparison with other LLMs and to assess its technical capabilities. It is planned to be distributed under a research-purpose license.
- **KORANI:** KORANI is a Korean-specific LLM developed based on Jindo and GORANI's accumulated technology. It is based on the 13B Llama2 chat, transformed into an LFM (Large Foundation Model), with the goal of making it available under a commercial license.
***


### *Huggingface*
  link: https://huggingface.co/danielpark
| Project Title                      | Backbone | Description                                                                                                                      |
|------------------------------------|---------|----------------------------------------------------------------------------------------------------------------------------------|
| [ko-llama-2-jindo-7b-instruct](https://huggingface.co/danielpark/ko-llama-2-jindo-7b-instruct)       | [LLaMA2-7b](https://huggingface.co/llamaste/Llama-2-7b-hf)  | Korean LLM model efficiently fine-tuned with QLoRA (Efficient Finetuning of Quantized LLMs)    |
| [ko-llama-2-jindo-13b-instruct](https://huggingface.co/danielpark/ko-llama-2-jindo-13b-instruct)      | [LLaMA2-13b](https://huggingface.co/llamaste/Llama-2-13b-hf)  | Korean LLM model efficiently fine-tuned with QLoRA                                        |
| [ko-llama-2-jindo-7b-instruct-ggml](https://huggingface.co/danielpark/ko-llama-2-jindo-7b-instruct-ggml)   | [LLaMA2-7b](https://huggingface.co/llamaste/Llama-2-7b-hf)  | Model weights transformed through GGML(Generic Graph Machine Learning) to efficiently perform inference using GPU and CPU.      |
| [ko-llama-2-jindo-7b-instruct-4bit-128g-gptq](https://huggingface.co/danielpark/ko-llama-2-jindo-7b-instruct-4bit-128g-gptq) | [LLaMA2-7b](https://huggingface.co/llamaste/Llama-2-7b-hf)  | Model weights using LLaMA2 as the backbone, one-shot weight quantized with GPTQ(Accurate Post-Training Quantization for Generative Pre-trained Transformers) to increase inference speed. |


***

### *Projects*

| Project                               | Description                                              | Repo                                                           |
|:--------------------------------------|:---------------------------------------------------------|:---------------------------------------------------------------|
| Bard API                              | Interfaces with Google Bard API to retrieve responses.  | [GitHub](https://github.com/DSDanielPark/BARD_API)             |
| Amazing Bard Prompts                  | Includes curated Google Bard prompts for enhanced utilization. | [GitHub](https://github.com/dsdanielpark/amazing-bard-prompts) |
| ExceptNotifier                        | Enriches try-except with comprehensive error messages.  | [GitHub](https://github.com/dsdanielpark/ExceptNotifier)       |
| Co Coder                              | Python package that treamlines error debugging from Chat GPT and Google Bard. | [GitHub](https://github.com/dsdanielpark/Co-Coder)            |
| GPT BERT Medical QA Chatbot           | Research repository focused on GPT 2 fine-tuning for medical domain. | [GitHub](https://github.com/DSDanielPark/medical-qa-bert-chatgpt)|
| Korean news topic classification using KO BERT | Classifies Korean news articles into eight categories using fine-tuned Korean BERT. | [GitHub](https://github.com/DSDanielPark/fine-tuned-korean-bert-news-article-classifier)|
| Multi-objective recommender           | Recommendation system leveraging user behavior data for improved accuracy. | [GitHub](https://github.com/DSDanielPark/kaggle2023-multi-objective-recommender)|

***
 
### *Packages*
  pypi link: https://pypi.org/user/archi-park/ <br>

| Package       | Description                                                  | Repo                                                           |
|:--------------|:-------------------------------------------------------------|:---------------------------------------------------------------|
| bardapi       | The python package that returns Response of Google Bard through API. | [GitHub](https://github.com/DSDanielPark/bardapi)            |
| arxiv2text    | Converting PDF files to text, mainly with a focus on arXiv papers. | [GitHub](https://github.com/DSDanielPark/arxiv2text)         |
| transllm      | LLMtranslator translates and generates text in multiple languages. | [GitHub](https://github.com/DSDanielPark/hf-transllm)           |
| translang     | Translation Service API Module.                              | [GitHub](https://github.com/DSDanielPark/translang)          |
| catchexception| Nightly version of ExceptNotifier | [GitHub](https://github.com/DSDanielPark/catchexception)    |
| googlebardapi | The python package that returns Response of Google Bard through API. | [GitHub](https://github.com/DSDanielPark/googlebardapi)     |
| cocoder       | Python package that treamlines error debugging from Chat GPT and Google Bard. | [GitHub](https://github.com/DSDanielPark/cocoder)           |
| exceptnotifier| With Python's try-except to receive notifications about Errors or Successes in your code through messenger app or email. | [GitHub](https://github.com/DSDanielPark/exceptnotifier)    |
| utilfunction  | The Python package utilfunction wraps and distributes useful functions in an easy-to-use way. | [GitHub](https://github.com/DSDanielPark/utilfunction)     |
| quickshow     | Quick-Show provides simply but powerful insight plots       | [GitHub](https://github.com/DSDanielPark/quickshow)         |
| googledriver  | The Python package google drive facilitates access to files uploaded to Google Drive. | [GitHub](https://github.com/DSDanielPark/googledriver)     |
| youtuber      | Support tools including crawler, video editing, YouTube API, etc. | [GitHub](https://github.com/DSDanielPark/youtuber)         |
| docfilter     | The Python package docfilter is used to detect and remove inappropriate information from text. | [GitHub](https://github.com/DSDanielPark/docfilter)        |
| kmi2122       | This dataset includes some macroeconomic indicators for South Korea in 2021-2022. | [GitHub](https://github.com/DSDanielPark/kmi2122)          |
| corpusshow    | Corpus-Show makes it easier and faster to visualize corpus through sentence embedding of corpus. | [GitHub](https://github.com/DSDanielPark/corpusshow)       |
| edanif        | EDA-NIf creates a dataframe containing meta information of NIfTi files and provides several useful features. | [GitHub](https://github.com/DSDanielPark/edanif)           |


***

  
### *Dockerhub*
  link: https://hub.docker.com/u/parkminwoo91

***

### *Work Experience*

<details>
<summary>Work Experience</summary>
<div style="overflow-x: auto;">


| Year      | Category             | Projects                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|:----------|:---------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2023      | Large Language Model (LLM), AI for Life | - Bard API: An unofficial Python package to interface with Google Bard and retrieve responses. <br> - all-about-llm: A documentation of papers and projects related to large language models. <br> - ko-llama2-jindo: A project focused on creating Korean language models, constructing the entire pipeline, and lightweighting. <br> - KOLANI: A multi-purpose Korean LLM development project based on LLaMA2. <br> - hf-transllm: The LLMtranslator project for multilingual translation and text generation. <br> - korean-open-llm-datasets-chain: A project to collect/process Korean LLM datasets. <br> - open-llm-datasets: A repository summarizing datasets and papers used in Open LLM. <br> - open-llm-leaderboard-report: Periodically visualizing the performance of Open LLMs based on four metrics. <br> - medical-qa-bert-chatgpt: Fine-tuned GPT-2 for question-answering in the medical domain. <br> - ExceptNotifier: Improves try-except statements to allow users to receive detailed error messages via email or messenger apps, supporting features like REST API, webhooks, and code alarms. <br> - translang: A collection of translation service modules providing APIs for language translation. <br> - Co-Coder: A Python package simplifying debugging with OpenAI Chat GPT and Google Bard, providing hints, example codes, and related Stack Overflow links. <br> - Recommender System: Multi-objective-recommender: A project building a multi-objective recommendation system based on real e-commerce sessions. |
| 2017-2022 | Computer Vision, Natural Language Process, Time Serise, Tabular, Analysis, Optimization, AI for Life       | - Development of algorithms for extracting key factors from engineering drawings (P.O: Hyundai Motor Group, 2022) <br> - Algorithm and pipeline development for visualizing and analyzing noise sources, determining their locations, and clustering them (P.O: Hyundai Motor Group, 2022) <br> - Large-scale data processing, including Hadoop data refinement and data handling via PySpark (P.O: Hyundai Motor Group, 2022) <br> - Detection of abnormalities in power lines using big data from Korea Electric Power Corporation (KEPCO, 2021) <br> - Development of body classification and prediction models based on time-series big data (2022) <br> - Prediction and factor analysis of the real estate market based on large-scale data (MicroSoft Korea, KB Financial Group, 2021)  <br> - Development of automatic brain structure segmentation and tumor area segmentation models using MRI and CT images and skull extraction algorithms (2022) <br> - Body classification and 3D body shape change prediction model based on time-series data collected from Koreans (2022) <br> - Algorithm and deep learning model development for extracting drawing factors from engineering drawings (2022) <br> - Algorithm and pipeline automation for visualizing and analyzing noise sources (2022) <br> - Natural Language Processing: Planning for the development of a platform to discover and characterize food ingredients (2021) <br> - Software development for automating extraction and analysis of mechanisms, interactions, and molecular structures of proteins from Alzheimer's disease papers (2021) <br> - Disease and physical vitality prediction based on animal metabolite (fur/blood) datasets (2021) <br> - Prediction of anomalies, health index, and analysis of intestinal microbes using National Health Insurance (NHI) data (2021) <br> - Analysis of inflow/purchase trends, price trends, and logistics predictions (2017-2018) <br> - Analysis of National Health Insurance (NHI) data and development of algorithms for biological age calculation and disease prevalence prediction (2021) <br> -  Planning for the development of algorithms for heat efficiency and energy optimization in Siheung Banwol Industrial Complex (2021) <br> - Automation of preprocessing pipeline for medical term database (SNOMED CT) (2021) <br> - Data cleansing for Hadoop and data processing optimization through PySpark (2022) <br> - Development of a Cohort-Based Big Data Analysis System for the National Health Insurance Corporation of Korea, Risk Assessment of Major Adult Diseases (Including Cancer and Diabetes), and the Development of a Biological Age Calculation Algorithm (2020) <br> - Analysis of Inflows/Product Selection/Trend Analysis/Price Trends/Logistics Prediction (2017) <br> - Development of a logistics demand forecasting model using data analysis and machine learning techniques (2017) <br> - AI-Powered Logistics and Retail Solo Entrepreneurship (Established in 2017-2018 with an annual income of USD 2 million) |


</div>
</details>
