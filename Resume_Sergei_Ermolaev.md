# Sergei Ermolaev

[](https://t.me/j1nsei/)

[](https://www.linkedin.com/in/saermolaev/)

<saermolaev.w@gmail.com>

[+7 (930) 802-31-25](tel:+79308023125)

Nizhny Novgorod (UTC+3)

[RU CV](https://j1nsei.github.io/cv/index.html?utm_source=en_pdf)

## Summary

**AI / Machine Learning Engineer with 3 years of professional experience**. My background includes classification, computer vision, and speech processing. My current focus is **RAG, LLM inference, AI agents, and hybrid search**. I specialize in rapid prototyping of ML/AI solutions, from testing ideas to building demos. I take solutions into production with quality evaluation and monitoring, optimizing for latency and compute constraints. Open to remote work and relocation.

## Experience

*Nizhny Novgorod \| Nov 2023 – Present*

**Proton** *(IT company of AGAT Group, [top-5 Russian automotive dealer group](https://www.forbes.ru/biznes/535642-vyrucka-25-krupnejsih-avtodilerov-rossii-vyrosla-do-2-4-trln-rublej), 120+ showrooms)*\
Machine Learning Engineer:

- Improved **multi-label call classification** from **79% to 94% sample-wise F1** and from **3% to 61.6% EMR**, with sub-second CPU inference for **1,000+ calls daily**. Handled data preparation, transcription, multilabel stratification, model experiments, and production integration. Company analysts estimated the financial impact at **~\$1.7M**.

- Built and deployed a **RAG assistant using RAGFlow and vLLM**, achieving **4.7/5 user satisfaction**, **95% faithfulness**, and **p99 TTFT of 4.6s** under load with long contexts. Selected models, adapted RAGFlow to the corporate knowledge base, and built a custom document preprocessing and parsing pipeline with production monitoring, tracing, and quality evaluation.

- Designed and implemented a ticket routing **AI agent** for an internal workflow system using RAG, Guardrails, Memory, LangGraph, LangFuse, and vLLM; owned the full development cycle, including **quality and performance monitoring**.

- Developed a **car parts search system** that reduced requests to parts specialists from **300 to 20 per day (−93%)**. Implemented hybrid search with custom ranking and relevance thresholds, built an abbreviation dictionary, and deployed the service using **FastAPI and Docker**.

- Built an **LLM-based call labeling** pipeline using Mistral/Qwen, zero-/few-shot prompting, and **LoRA Qwen2.5-3B**; achieved up to **90% accuracy** in experiments and deployed an XLinear baseline with 88% accuracy for CPU inference.

- Built a **vehicle test-drive tracking** pipeline using **YOLOv5**, multi-threaded video processing, and ROI cropping; improved tracking accuracy from **65% to 87%** and reached up to **15 FPS** on a consumer-grade GPU.

## Projects

*Sept 2022 – May 2023*

**HSE University Nizhny Novgorod** *(Academic R&D)*\
ML Engineer \| *WhisperX, Llama.cpp, aiogram, guidance. [GitHub](https://github.com/J1nsei/Voice-Message-Summarization-Bot)*

- Developed an autonomous AI assistant (Telegram Bot on aiogram) for audio transcription and summarization with a focus on data privacy. Designed an ASR pipeline based on WhisperX with text alignment and regex noise filtering. Implemented hybrid (CPU/GPU) inference of the quantized LLM via llama.cpp with custom memory management and strict generation control using the guidance framework. The system runs without external APIs and optimized for local execution on consumer hardware (from 12GB VRAM).

*Feb 2021 – May 2021*

**HSE University Nizhny Novgorod** *(Joint R&D project with business)*\
ML Researcher \| *Selenium, Colabeler, torchvision*

- Designed a data collection and preparation pipeline for a CV model detecting car damage. Collected the dataset, performed labeling, augmentation, and class balancing.

## Education

**HSE University**\
Nizhny Novgorod, Russia\
Master’s degree in Data Mining\
Sept 2022 – June 2024

**HSE University**\
Nizhny Novgorod, Russia\
Bachelor’s degree in Applied Mathematics and Informatics\
Sept 2018 – June 2022

### Professional Development

[Yandex School of Data Analysis Intensive: AI Agents Security Week](https://education.yandex.com/profile/docs?id=686cc0f4-1c98-408c-aeb7-4bfb81df4730) — Jul 27, 2026 – Jul 31, 2026

[Yandex School of Data Analysis Intensive: Agents Week](https://education.yandex.com/profile/docs?id=2f1dd619-4a1b-45a6-93f1-491e18333322) — Apr 6, 2026 – Apr 10, 2026

[Yandex School of Data Analysis Intensive: LLM Scaling Week](https://education.yandex.com/profile/docs?id=95aa3c1d-031f-4a09-9d8e-af8159728780) — Nov 10, 2025 – Nov 14, 2025

## Skills

**DL/ML:** Python, PyTorch, vLLM, Transformers, LangChain, LangGraph, llama.cpp, DeepEval, RAGFlow, NumPy, prompt engineering, Infinity, Unsloth, scikit-learn, WhisperX, spaCy, Ultralytics

**Infra/Tools:** Linux, Docker, FastAPI, Git, DVC, Streamlit, LangFuse, W&B, matplotlib, Grafana, Kubeflow

**Data:** pandas, polars, SQL

**Languages:** Russian - Native, English - B2 / Upper-Intermediate
