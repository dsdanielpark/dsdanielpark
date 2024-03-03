
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
- **KORANI:** KORANI is a Korean-specific LLM developed based on Jindo and GORANI's accumulated technology. It is based on the 13B Llama2 chat, transformed into an LFM (Large Foundation Model), with the goal of making it available under a commercial license.
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

- Bard API: An unofficial Python package to interface with Google Bard. (LLM, 2023)
- All about llm: Documentation of papers and projects on large language models. (LLM, 2023)
- Ko llama2-jindo: Korean language model development and lightweighting. (LLM, 2023)
- KOLANI: Multi-purpose Korean LLM project based on LLaMA2. (LLM, 2023)
- Hf transllm: LLMtranslator for multilingual translation and text generation. (LLM, 2023)
- Korean-open-llm-datasets-chain: Collection and processing of Korean LLM datasets. (LLM, 2023)
- Open llm datasets: Summary of datasets and papers for Open LLM. (LLM, 2023)
- Open llm leaderboard report: Visualizing Open LLM performance metrics. (LLM, 2023)
- Medical QA bert chatgpt: GPT-2 fine-tuned for medical domain Q&A. (AI for Life, 2023)
- ExceptNotifier: Detailed error notifications via email or messenger. (Python Package, 2023)
- Translang: Translation service modules with language translation APIs. ((Python Package, 2023)
- Co Coder: Debugging aid with OpenAI Chat GPT and Google Bard in ipython. (Python Package, 2023)
- Multi objective recommender: E-commerce based recommendation system. (Recommendation System, 2023)
- Algorithms and deep-learninig models for key factor extraction from engineering drawings. (**Hyundai Motor Group** / Vision, 2022)
- Noise source visualization, location determination, and clustering model. (**Hyundai Motor Group** / Vision, 2022)
- Data processing and PySpark data pipeline optimization. (**Hyundai Motor Group**/ Big Data, Analysis, 2022)
- Noise source analysis automation. (**Hyundai Motor Group** / Vision, Predcition, Time Series, 2022)
- 3D body shape prediction from time-series data. (Time Series, 2022)
- Body classification and prediction models from time-series data. (Vision, Time Series, 2022)
- Real estate market prediction and analysis. (**Microsoft Korea, KB Financial Group** / Analysis, Time Series, 2021)
- Power line abnormality detection using KEPCO big data. (Vision, 2021)
- Food ingredient discovery platform development. (NLP, Big Data, 2021)
- Protein analysis software from Alzheimer's disease papers. (Big Data, NLP, 2021)
- Biological age and disease prediction algorithms from Korea NHISS data. (AI for life, Analysis, 2021)
- Heat efficiency and energy optimization algorithm development. (Prediction, Time Serise, Optimization, 2021)
- Medical term database preprocessing automation. (AI for Life, 2021)
- Animal metabolite-based disease and vitality prediction. (Predcition, Analysis, 2021)
- Health index and intestinal microbe analysis using NHI data. (AI for life, Analysis, 2021)
- Cohort-based big data analysis system for major diseases. (AI for life, Analysis, 2020)
- Logistics and price trend analysis. (Predcition, Analysis, 2017-2018)
- Logistics demand forecasting model development. (Time Serise, Analysis, 2017)
- AI-Powered Logistics and Retail Solo Entrepreneurship. (Time Serise, Analysis, 2017-2018)

</div>
</details>
