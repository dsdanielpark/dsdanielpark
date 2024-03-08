
### *Hello, I'm MinWoo(Daniel) Park*

<div align=right>

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/dsdanielpark/)](https://www.linkedin.com/in/dsdanielpark/) 
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fdsdanielpark&count_bg=%23000000&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=ProfileViews&edge_flat=false)](https://hits.seeyoufarm.com)
<!--<a href="https://www.buymeacoffee.com/parkminwoo"><img src="https://cdn.buymeacoffee.com/buttons/v2/arial-orange.png" height="20px"></a>-->
</div>

- I am a passionate developer adept at leveraging Machine Learning and Deep Learning technologies to address challenges across diverse domains. 
- My extensive experience and knowledge in fields such as LLM, Natural Language Processing, Computer Vision, and the medical and healthcare sectors have enabled me to connect the dots and craft sophisticated solutions for a broad range of industry problems. <br>
- Currently, I am focusing on advancing the field ofthe state-of-the-art LLM (Language Model) technology.
- I believe that all the knowledge I have gained will converge at the end of my journey.

*Research Interests:* Large Language Models, Optimization Techniques, Vector Databases
<br>

<p align="center">
<a href="https://github.com/dsdanielpark">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=dsdanielpark&show_icons=true&theme=nord&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=dsdanielpark&layout=compact&langs_count=8&theme=nord"/>
</a>
</p>



<br>

## Portfolio Contents
_On 2023-11-07, I have decided to make the majority of repositories and Hugging Face models **private**._
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
- **KORANI:** KORANI is a Korean-specific LLM developed based on Jindo and GORANI's accumulated technology. It is based on the 13B Llama2 chat, transformed into an LLM, with the goal of making it available under a commercial license.
***


### *Huggingface*
  Link: https://huggingface.co/danielpark
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
  Pypi link: https://pypi.org/user/archi-park/ <br>

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
  Link: https://hub.docker.com/u/parkminwoo91

***

### *Work Experience*

<details>
<summary>Work Experience</summary>
<div style="overflow-x: auto;">

#### 01 Internal Projects (2017 - 2022)
- **Inflow Analysis/Product Selection/Trend Analysis/Price Trend/Logistics Demand Prediction Model** (2017-2018, Recommender System, Natural Language Processing)
- **Analysis of National Health Insurance Service (NHIS) Data and Development of Biological Age Calculation Algorithm, Disease Prevalence Prediction** (2020, Machine Learning)
- **Detection of Overhead Wires using Big Data from Korea Electric Power Corporation (KEPCO)** (2021, Computer Vision)
- **Development Planning of Food Ingredient Discovery and Characterization Platform** (2021, Machine Learning, Natural Language Processing)
- **Software Development for Automating Protein Mechanisms, Interactions, and Molecular Structure Extraction and Analysis from Alzheimer's Disease Papers** (2021, Natural Language Processing, Computer Vision)
- **Prediction of Diseases and Physical Vitality based on Animal Metabolite (Fur/Blood) Datasets** (2021, Machine Learning, Natural Language Processing)
- **Anomaly Signs Prediction, Health Index Forecast, Gut Microbiome Data Analysis using National Health Insurance Data** (2021, Machine Learning, Natural Language Processing)
- **Development Planning for Heat Efficiency and Energy Optimization Algorithms in Sihwabanwol Industrial Complex** (2021, Optimization)
- **Development of Automatic Brain Structure Segmentation and Tumor Area Segmentation Model using MRI and CT Images and Skull Extraction Algorithms** (2022, Computer Vision)
- **Development of Body Type Classification and 3D Body Shape Change Prediction Model based on Time-Series Korean Body Data Collection** (2022, Computer Vision)
- **Algorithm and Deep Learning Model Development for Extracting Drawing Factors from Engineering Drawings** (2022, Computer Vision)
- **Algorithm for Visualization and Analysis of Noise Sources, Automation Pipeline for Noise Source Localization and Clustering** (2022, Computer Vision)

#### 02 Personal Projects (2022 - 2023)
- **Bard-API**: Unofficial Python Package for Fetching Responses from Google Bard (GitHub Star 5.4k, Downloads 379k, 2023, Python Development)
- **ExceptNotifier**: Package for Sending Detailed Error Messages to Users via Messenger when Errors Occur in try-except Statements (Downloads 27k, 2023, Python Development)
- **All About LLM**: Documentation of Papers and Projects on Large Language Models (2023, LLM)
- **Ko LLaMa2 Jindo**: Project Focused on Creating a Korean Natural Language Model, Entire Pipeline Construction and Lightweighting (2023, LLM)
- **GORANI**: Multipurpose Korean LLM Development Project based on LLaMA2 (2023, LLM)
- **HF Trans LLM**: Translator Project for Multilingual Translation and Text Generation (2023, LLM, Python Development)
- **Korean Open LLM Datasets-chain**: Project for Collecting/Processing Korean LLM Datasets (2023, Python Development, LLM)
- **Open LLM Datasets**: Compilation of Datasets and Papers Used in Open LLM (2023, Python Development, LLM)
- **Open LLM Leaderboard-report**: Visualization of Performance of Open Source LLMs based on Four Metrics for Performance Comparison (2023, LLM)
- **Medical QA Bert Chat GPT**: Fine-tuning GPT-2 for Question-Answering in the Medical Domain (2023, LLM)
- **Translang**: Translation Service Module Providing API for Language Translation (2023, Python Development)
- **Fine-tuned-korean-bert-news-article-classifier**: Model Development for News Article Topic Classification, Comparing BERT Implementations in Various Frameworks (2023, LLM)
- **Multi Objective Recommender**: Project to Build a Multi-Objective Recommendation System based on Real E-commerce Sessions (2023, Recommender System)
- **Co Coder**: Python Package to Simplify Debugging using OpenAI Chat GPT and Google Bard (2023, Python Development)
- **EDA-Nif**: Organizing Metadata of Medical AI Nifti Files and Providing Some Functions such as Image Registration and Arbitrary Slicing (2022, AI for Life)
</div>
</details>
