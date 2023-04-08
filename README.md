# awesome-llm-utilities

Tooling and frameworks to support building tools that utilize LLM agents


# Agent orchestration, multi-step planning

* https://github.com/microsoft/JARVIS - JARVIS, a system to connect LLMs with ML community. Paper: https://arxiv.org/pdf/2303.17580.pdf (HuggingGPT)
* https://github.com/hwchase17/langchain - ⚡ Building applications with LLMs through composability ⚡
* https://github.com/jerryjliu/llama_index - LlamaIndex (GPT Index) is a project that provides a central interface to connect your LLM's with external data.
* https://github.com/emptycrown/llama-hub - A library of data loaders for LLMs made by the community -- to be used with GPT Index and/or LangChain
* https://github.com/stanfordnlp/dsp - 𝗗𝗦𝗣: Demonstrate-Search-Predict. A framework for composing retrieval and language models for knowledge-intensive NLP.
* https://github.com/amazon-science/mm-cot - Multimodal Chain-of-Thought Reasoning in Language Models
* https://github.com/microsoft/visual-chatgpt - Visual ChatGPT connects ChatGPT and a series of Visual Foundation Models to enable sending and receiving images during chatting. See our paper: [Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models](https://arxiv.org/abs/2303.04671)
* https://github.com/lightaime/camel - CAMEL: Communicative Agents for “Mind” Exploration of Large Scale Language Model Society - www.camel-ai.org


# Coding agents, Implicitly defined tools, Tools for Developers

* https://github.com/irgolic/AutoPR - Fix issues with AI-generated pull requests, powered by ChatGPT. discord.gg/ykk7Znt3K6
* https://github.com/e2b-dev/e2b - e2b (english2bits) is an IDE powered by AI agents. Developers describe what they want to build by writing documentation. Then let AI agents with access to tools do the coding work. e2b.dev
* https://github.com/dmarx/the-rest-of-the-fucking-owl - Trigger an LLM in your CI/CD to auto-complete your work
* https://github.com/BlackHC/llm-strategy - Directly Connecting Python to LLMs - Dataclasses & Interfaces <-> LLMs blackhc.github.io/llm-strategy
* https://github.com/biobootloader/wolverine - Give your python scripts regenerative healing abilities! Run your scripts with Wolverine and when they crash, GPT-4 edits them and explains what went wrong. Even if you have many bugs it will repeatedly rerun until it's fixed.
* https://github.com/Quansight/pseudocode - pseudocode is a python module which allows users to describe the functions they want via type annotations and docstrings without writing the actual code. It empowers users to iterate with large language models to generate functions which satisfy the user along with defined tests.
* 


# Prompt Construction, Generation Validation and Guidance

* https://github.com/ShreyaR/guardrails - Adding guardrails to large language models. discord.gg/Jsey3mX98B
* https://github.com/benlipkin/probsem - a framework to leverage large language models (LLMs) to assign context-conditional probability distributions over queried strings, with default support for all OpenAI engines and HuggingFace CausalLM models.
* https://github.com/HazyResearch/manifest - How to make prompt programming with Foundation Models a little easier.


# IDE extensions, frontends, browser plugins

* https://github.com/MateusZitelli/PromptMate - 
* https://github.com/socketteer/loom - Multiversal tree writing interface for human-AI collaboration

# Annotation, Conversational Information Retrieval, misc

* https://github.com/explosion/prodigy-openai-recipes - This repository contains example code on how to combine zero- and few-shot learning with a small annotation effort to obtain a high-quality dataset with maximum efficiency. Specifically, we use large language models available from OpenAI to provide us with an initial set of predictions, then spin up a Prodigy instance on our local machine to go through these predictions and curate them. This allows us to obtain a gold-standard dataset pretty quickly, and train a smaller, supervised model that fits our exact needs and use-case.
* https://github.com/hwchase17/chat-langchain - This repo is an implementation of a locally hosted chatbot specifically focused on question answering over the LangChain documentation. 
* https://github.com/whitead/paper-qa - LLM Chain for answering questions from documents with citations
* https://github.com/jagilley/fact-checker - Fact-checking LLM outputs with langchain



# Generation SDKs

* https://github.com/hyperonym/basaran - Basaran is an open-source alternative to the OpenAI text completion API. It provides a compatible streaming API for your Hugging Face Transformers-based text generation models.
* https://github.com/NVIDIA/NeMo - NVIDIA NeMo is a conversational AI toolkit built for researchers working on automatic speech recognition (ASR), text-to-speech synthesis (TTS), large language models (LLMs), and natural language processing (NLP). The primary objective of NeMo is to help researchers from industry and academia to reuse prior work (code and pretrained models) and make it easier to create new conversational AI models.
* https://github.com/togethercomputer/OpenChatKit - OpenChatKit provides a powerful, open-source base to create both specialized and general purpose chatbots for various applications. The kit includes an instruction-tuned language models, a moderation model, and an extensible retrieval system for including up-to-date responses from custom repositories. OpenChatKit models were trained on the OIG-43M training dataset, which was a collaboration between Together, LAION, and Ontocord.ai.

# Autonomy Experiments

* https://github.com/Torantulino/Auto-GPT - An experimental open-source attempt to make GPT-4 fully autonomous.
* 


# Misc Research

* https://github.com/posgnu/rci-agent - A codebase for "Language Models can Solve Computer Tasks" - posgnu.github.io/rci-web/
* https://github.com/yizhongw/self-instruct - Aligning pretrained language models with instruction data generated by themselves. https://arxiv.org/abs/2212.10560
* https://github.com/noahshinn024/reflexion - Code for the approach proposed in [Reflexion: an autonomous agent with dynamic memory and self-reflection](https://arxiv.org/abs/2303.11366)
* https://github.com/GammaTauAI/reflexion-human-eval - This is a spin-off project inspired by the paper: [Reflexion: an autonomous agent with dynamic memory and self-reflection. Noah Shinn, Beck Labash, Ashwin Gopinath. _Preprint_, 2023](https://arxiv.org/abs/2303.11366)
* https://github.com/ysymyth/ReAct
* https://github.com/GammaTauAI/opentau
* https://github.com/madaan/self-refine - LLMs can generate feedback on their work, use it to improve the output, and repeat this process iteratively.
* https://github.com/Muennighoff/sgpt - SGPT: GPT Sentence Embeddings for Semantic Search
* https://github.com/HKUNLP/instructor-embedding - This repository contains the code and pre-trained models for our paper [One Embedder, Any Task: Instruction-Finetuned Text Embeddings](https://arxiv.org/abs/2212.09741). Please refer to our [project page](https://instructor-embedding.github.io/) for a quick project overview. We introduce **Instructor**👨‍🏫, an instruction-finetuned text embedding model that can generate text embeddings tailored to any task (e.g., classification, retrieval, clustering, text evaluation, etc.) and domains (e.g., science, finance, etc.) ***by simply providing the task instruction, without any finetuning***. Instructor👨‍ achieves sota on 70 diverse embedding tasks!
* https://github.com/reasoning-machines/pal - PaL: Program-Aided Language Models. reasonwithpal.com
* https://github.com/conceptofmind/toolformer - Open-source implementation of [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) by Meta AI.
* https://github.com/project-baize/baize-chatbot - Baize is an open-source chat model trained with [LoRA](https://github.com/microsoft/LoRA). It uses 100k dialogs generated by letting ChatGPT chat with itself. We also use Alpaca's data to improve its performance. We have released 7B, 13B and 30B models. Please refer to the [paper](https://arxiv.org/pdf/2304.01196.pdf) for more details.

# LLM Red Teaming and Prompt Bypass

* https://github.com/greshake/llm-security - New ways of breaking app-integrated LLMs. We demonstrate potentially brutal consequences of giving LLMs like ChatGPT interfaces to other applications. We propose newly enabled attack vectors and techniques and provide demonstrations of each in this repository. See also: https://greshake.github.io/
