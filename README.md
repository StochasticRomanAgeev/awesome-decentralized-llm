# awesome-decentralized-llm

Collection of LLM resources that can be used to build products you can "own" or to perform reproducible research. Please note there are Terms of Service around some of the weights and training data that should be investigated before commercialization.

Table of Contents:

- [Leaderboards](#leaderboards)
- [Local LLMs](#local-llms)
- [LLM-based Tools](#llm-based-tools)
- [Training and Quantization](#training-and-quantization)
- [Non-English Models](#non-english-models)
- [Autonomous Agents](#autonomous-agents)

If you are looking for a list of open-source LLMs that can be used commercially, this is a great list:
[Open LLMs](https://github.com/eugeneyan/open-llms)

-----

## Leaderboards

I am having a hard time keeping up with the latest and greatest open-source LLMs. Below are leaderboards I am checking periodically:

- [HuggingFace Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)
  The 🤗 Open LLM Leaderboard aims to track, rank and evaluate LLMs and chatbots as they are released.
  (2023-05-23, HuggingFace)

- [AlpacaEval 🦙 Leaderboard](https://tatsu-lab.github.io/alpaca_eval/)
  An Automatic Evaluator for Instruction-following Language Models
  (2023-07-01, Stanford Alpaca/Tatsu Lab)

- [Code Generation on HumanEval](https://paperswithcode.com/sota/code-generation-on-humaneval)
  HumanEval problem solving dataset described in the paper "Evaluating Large Language Models Trained on Code"
  (2023-07-01, Papers With Code)
  
-----

## Local LLMs

### Local LLM Repositories

- [LLM Foundry](https://github.com/mosaicml/llm-foundry)
  Release repo for MPT-7B and related models.
  (2023-05-05, MosaicML, Apache 2.0)

- [FastChat](https://github.com/lm-sys/FastChat)
  Release repo for Vicuna and FastChat-T5
  (2023-04-20, LMSYS, Apache 2.0)

- [StabilityLM](https://github.com/stability-AI/stableLM/) -
  Stability AI Language Models
  (2023-04-19, StabilityAI, Apache and CC BY-SA-4.0)

- [GPT4All](https://github.com/nomic-ai/gpt4all) -
  LLM trained with ~800k GPT-3.5-Turbo Generations based on GPT-J and LLaMa.
  (2023-04-13, Nomic AI, Apache/Meta ToS/OpenAI ToS)
 
- [Dolly](https://github.com/databrickslabs/dolly) -
  Large language model trained on the Databricks Machine Learning Platform
  (2023-03-24, Databricks Labs, Apache)
  
- [bloomz.cpp](https://github.com/NouamaneTazi/bloomz.cpp)
  Inference of HuggingFace's BLOOM-like models in pure C/C++.
  (2023-03-16, Nouamane Tazi, MIT License)
  
- [alpaca.cpp](https://github.com/antimatter15/alpaca.cpp) -
  Locally run an Instruction-Tuned Chat-Style LLM
  (2023-03-16, Kevin Kwok, MIT License)

- [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca) -
  Code and documentation to train Stanford's Alpaca models, and generate the data.
  (2023-03-13, Stanford CRFM, Apache License, Non-Commercial Data, Meta/OpenAI ToS)

- [llama.cpp](https://github.com/ggerganov/llama.cpp) -
  Port of Facebook's LLaMA model in C/C++. 
  (2023-03-10, Georgi Gerganov, MIT License)

- [ChatRWKV](https://github.com/BlinkDL/ChatRWKV) -
  ChatRWKV is like ChatGPT but powered by RWKV (100% RNN) language model, and open source.
  (2023-01-09, PENG Bo, Apache License)
  
- [RWKV-LM](https://github.com/BlinkDL/RWKV-LM) -
  RNN with Transformer-level LLM performance. Combines best of RNN and transformer: fast inference, saves VRAM, fast training.
  (2022?, PENG Bo, Apache License)

- [Open Assistant](https://open-assistant.io/) - A chat-based ChatGPT-like large language model. (2023-04-15, Pythia, LLAMA, Apache 2.0 License)

### Local LLM Spaces, Models & Datasets

- [RedPajama-Data-1T](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-1T)
  (2023-04-17, [@togethercompute](https://twitter.com/togethercompute))

- [Vicuna 13b](https://huggingface.co/lmsys/vicuna-13b-delta-v1.1)
  (2023-04-12, [@lmsysorg](https://twitter.com/lmsysorg))

- [Dolly 15k Instruction Tuning Labels](https://github.com/databrickslabs/dolly/tree/master/data)
  (2023-04-12, DataBricks, CC3 Allows Commercial Use)
  
- [Cerebras-GPT 7 Models](https://huggingface.co/cerebras)
  (2023-03-28, Huggingface, Cerebras, Apache License)

- [Alpine Data Cleaned](https://github.com/gururise/AlpacaDataCleaned)
  (2023-03-21, Gene Ruebsamen, Apache & OpenAI ToS)

- [Alpaca Dataset](https://huggingface.co/datasets/tatsu-lab/alpaca)
  (2023-03-13, Huggingface, Tatsu-Lab, Meta ToS/OpenAI ToS)
  
- [Alpaca Model Search](https://huggingface.co/models?sort=downloads&search=alpaca)
  (Huggingface, Meta ToS/OpenAI ToS)
  

### Local LLM Resources

- [Introducing MPT-7B: A New Standard for Open-Source, Commercially Usable LLMs](https://www.mosaicml.com/blog/mpt-7b)
  (2023-05-05, MosaicML, Blog Post)

- [Google "We Have No Moat, And Neither Does OpenAI"](https://www.semianalysis.com/p/google-we-have-no-moat-and-neither)
  (2023-05-04, Leaked Internal Google Document)

- [RedPajama reproduces LLaMA training dataset of over 1.2 trillion tokens](https://www.together.xyz/blog/redpajama)
  (2023-04-17, Together, Blog Post)

- [What’s in the RedPajama-Data-1T LLM training set](https://simonwillison.net/2023/Apr/17/redpajama-data/)
  (2023-04-17, Simon Willison, Blog Post)
  
- [GPT4All-J: An Apache-2 Licensed Assistant-Style Chatbot](https://static.nomic.ai/gpt4all/2023_GPT4All-J_Technical_Report_2.pdf)
  (2023-04-13, nomic.ai)

- [Databricks releases Dolly 2.0, the first open, instruction-following LLM for commercial use](https://venturebeat-com.cdn.ampproject.org/c/s/venturebeat.com/ai/databricks-releases-dolly-2-0-the-first-open-instruction-following-llm-for-commercial-use/amp/)
  (2023-04-13, Venture Beat, Sharon Goldman)

- [Summary of Curent Models](https://docs.google.com/spreadsheets/d/1O5KVQW1Hx5ZAkcg8AIRjbQLQzx2wVaLl0SqUu-ir9Fs/edit#gid=1158069878)
  (2023-04-11, Dr Alan D. Thompson, Google Sheet)

- [Running GPT4All On a Mac Using Python langchain in a Jupyter Notebook](https://blog.ouseful.info/2023/04/04/running-gpt4all-on-a-mac-using-python-langchain-in-a-jupyter-notebook/)
  (2023-04-04, Tony Hirst, Blog Post)

- [Vicuna Homepage](https://vicuna.lmsys.org/)
  (2023-04-01, Meta ToS)

- [Cerebras-GPT vs LLaMA AI Model Comparison](https://www.lunasec.io/docs/blog/cerebras-gpt-vs-llama-ai-model-comparison/)
  (2023-03-29, LunaSec, Blog Post)

- [Cerebras-GPT: Family of Open, Compute-efficient, LLMs](https://www.cerebras.net/blog/cerebras-gpt-a-family-of-open-compute-efficient-large-language-models/)
  (2023-03-28, Cerebras, Blog Post)

- [Hello Dolly: Democratizing the magic of ChatGPT with open models](https://www.databricks.com/blog/2023/03/24/hello-dolly-democratizing-magic-chatgpt-open-models.html)
  (2023-03-24, databricks, Blog Post)

- [The Coming of Local LLMs](https://nickarner.com/notes/the-coming-of-local-llms-march-23-2023/)
  (2023-03-23, Nick Arner, Blog Post)

- [The RWKV language model: An RNN with the advantages of a transformer](https://johanwind.github.io/2023/03/23/rwkv_overview.html)
  (2023-03-23, Johan Sokrates Wind, Blog Post)
  
- [Bringing Whisper and LLaMA to the masses](https://changelog.com/podcast/532)
  (2023-03-15, The Changelog & Georgi Gerganov, Podcast Episode)
  
- [Alpaca: A Strong, Replicable Instruction-Following Model](https://crfm.stanford.edu/2023/03/13/alpaca.html)
  (2023-03-13, Stanford CRFM, Project Homepage)

- [Large language models are having their Stable Diffusion moment](https://simonwillison.net/2023/Mar/11/llama/)
  (2023-03-10, Simon Willison, Blog Post)

- [Running LLaMA 7B and 13B on a 64GB M2 MacBook Pro with llama.cpp](https://til.simonwillison.net/llms/llama-7b-m2)
  (2023-03-10, Simon Willison, Blog/Today I Learned)
  
- [Introducing LLaMA: A foundational, 65-billion-parameter large language model](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)
  (2023-02-24, Meta AI, Meta ToS)

-----

## LLM-based Tools

- [MiniGPT-4](https://github.com/Vision-CAIR/MiniGPT-4)
  Enhancing Vision-language Understanding with Advanced Large Language Models
  (2023-04-17, Vision CAIR Research Group, KAUST, BSD)

- [Text generation web UI](https://github.com/oobabooga/text-generation-webui)
  A gradio web UI for running Large Language Models like LLaMA, llama.cpp, GPT-J, Pythia, OPT, and GALACTICA.
  (2023-04-15, oobabooga, AGPL)

- [TextSynth](https://bellard.org/ts_server/)
  REST API for Large Language Models. Supports variety of models.
  (2023-04-13, Fabrice Bellard, Commercial License GPU/Shareware CPU)

- [FastChat](https://github.com/lm-sys/FastChat) -
  The release repo for Vicuna: An Open Chatbot Impressing GPT-4
  (2023-04-13, LM-SYS, Apache)

- [tabby](https://github.com/TabbyML/tabby)
  Self-hosted AI coding assistant.
  (2023-04-12, TabbyML)

- [Basaran](https://github.com/hyperonym/basaran)
  Open-source text completion API for Transformers-based text generation models.
  (2023-04-12, Hyperonym)

- [TurboPilot](https://github.com/ravenscroftj/turbopilot)
  CoPilot clone that runs code completion 6B-LLM with CPU and 4GB of RAM.
  (2023-04-11, James Ravenscroft)

- [talkGPT4All](https://github.com/vra/talkGPT4All) -
  A voice chatbot based on OpenAI Whisper and GPT4All, running on local laptop.
  (2023-04-09, Yunfeng Wang, MIT License)

- [LLMZoo](https://github.com/FreedomIntelligence/LLMZoo)
  Data, models, and evaluation benchmark for large language models
  (2023-04-08, FreedomIntelligence, Apache)

- [LMFlow](https://github.com/OptimalScale/LMFlow)
  An Extensible Toolkit for Finetuning and Inference of Large Foundation Models.
  (2023-04-06, OptimalScale)

- [xturing](https://github.com/stochasticai/xturing) -
  Build and control your own LLMs
  (2023-04-03, stochastic.ai)

----

## Training and Quantization

- [DeepSpeed](https://github.com/microsoft/DeepSpeed)
  Deep learning optimization library that makes distributed training and inference easy.
  (2023-04-13, Microsoft, Apache)
  
- [GPTQ-for-LLaMA](https://github.com/qwopqwop200/GPTQ-for-LLaMa) -
  4 bits quantization of LLaMA using GPTQ
  (2023-04-01, qwopqwop200, Meta ToS)

- [GPTQ](https://github.com/IST-DASLab/gptq)
  Code for the ICLR 2023 paper "GPTQ: Accurate Post-training Quantization of Generative Pretrained Transformers".
  (2023-03-22, IST Austria Distributed Algorithms and Systems Lab)

----

## Non-English Models & Datasets

- [Polpaca](https://huggingface.co/mmosiolek/polpaca-lora-7b) -
  Alpaca Speaks Polish
  (2023-04-13, Marcin Mosiolek)

- [KOZA](https://github.com/bqpro1/koza)
  KOZA is an instruct model for Polish language forked from alpaca-lora.
  (2023-04-13, Leszek Bukowski)
  
- [Owca](https://github.com/Emplocity/owca) is a Polish-translated dataset of instructions for fine-tuning the Alpaca model (2023-04-13, Emplocity)
  
----

## Autonomous Agents


### Autonomous Agent Repositories

- [AI Legion](https://github.com/eumemic/ai-legion) -
  JS/TS framework for autonomous agents who can work together to accomplish tasks.
  (2023-04-13, eumemic, MIT)

- [AgentGPT](https://github.com/reworkd/AgentGPT) -
  Assemble, configure, and deploy autonomous AI Agents in your browser.
  (2023-04-12, Rework.ai)
  
- [babyagi](https://github.com/yoheinakajima/babyagi) -
  Python script example of AI-powered task management system. Uses OpenAI and Pinecone APIs to create, prioritize, and execute tasks. 
  (2023-04-06, Yohei Nakajima)

- [ChatArena](https://github.com/chatarena/chatarena) - 
  Multi-Agent Language Game Environments for LLMs.
  (2023-04-05, UCL)
  
- [Auto-GPT](https://github.com/Torantulino/Auto-GPT) -
  An experimental open-source attempt to make GPT-4 fully autonomous.
  (2023-04-06, Toran Bruce Richards)

- [JARVIS](https://github.com/microsoft/JARVIS) -
  JARVIS, a system to connect LLMs with ML community
  (2023-04-06, Microsoft)

- [Autolang](https://github.com/alvarosevilla95/autolang) -
  Based on BabyAGI, focused on workflows that complete. Powered by langchain.
  (2023-04-10, Alvaro Sevilla)

### Autonomous Agent Resources

- [Emergent autonomous scientific research capabilities of large language models](https://arxiv.org/abs/2304.05332)
  (2023-04-11, Daniil A. Boiko,1 Robert MacKnight, and Gabe Gomes - Carnegie Mellon University)

- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/pdf/2304.03442.pdf)
  (2023-04-07, Stanford and Google)

- [Twitter List: Homebrew AGI Club](https://twitter.com/i/lists/1642934512836575232)
  (2023-04-06, [@altryne](https://twitter.com/altryne)]

- [LangChain: Custom Agents](https://blog.langchain.dev/custom-agents/)
  (2023-04-03, LangChain)
 
- [HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace](https://arxiv.org/abs/2303.17580)
  (2023-04-02, Microsoft)
  
- [Introducing Agents in Haystack: Make LLMs resolve complex tasks](https://haystack.deepset.ai/blog/introducing-haystack-agents) (2023-03-30, Haystack and Deepset)

- [Introducing "🤖 Task-driven Autonomous Agent"](https://twitter.com/yoheinakajima/status/1640934493489070080?s=20)
  (2023-03-29, [@yoheinakajima](https://twitter.com/yoheinakajima))

- [A simple Python implementation of the ReAct pattern for LLMs](https://til.simonwillison.net/llms/python-react-pattern)
  (2023-03-17, Simon Willison)

- [ReAct: Synergizing Reasoning and Acting in Language Models](https://react-lm.github.io/)
  (2023-03-10, Princeton & Google)


