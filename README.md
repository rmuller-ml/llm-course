# Notebooks for the course: “Large language models: theory and practice with OpenAI GPT”

This repo has the coding examples for the language modeling course. The course is divided into 4 modules where we learn how to build:

* **Auto-correct**: how language models work
* **Auto-complete**: how large language models work
* **Text summarizer**: how to adapt a pre-trained model to a specific task
* **Document question-answering**: how to augment the memory of a language model

Note that while building these 4 tools, we learn the theory of how language models work and are trained. We start by training a small transformer model (auto-correct lesson) and then move to large language models APIs (from OpenAI) for the subsequent lessons for more advanced tasks. At late stages of the course (lesson 4 and 5), we work mostly with prompt engineering and how to combine language models with other tools. We recommend doing the lessons in sequence, since each lesson uses concepts of previous ones.


Table of contents:


1. Introduction
1.Requirements
	2. How language models work
	3. What will we build?
		* [Auto-correct](https://github.com/rmuller-ml/llm-course/blob/main/2_auto_correct.ipynb)
		* [Auto-complete](https://github.com/rmuller-ml/llm-course/blob/main/3_auto_complete.ipynb)
		* Text summarizer
		* Document question-answering 
		* Chatbot (TODO)
		* Parsing unstructured data (TODO)
		* Building a bot that can use tools: local or remote APIs (TODO)
2. Auto-correct: how language models work
	1. Language modeling intro 
	2. Tokenizers
	3. Completion
	4. Auto-correct
	5. Model training
 	6. End-to-end code example 
3. Auto-complete: how large language models work
	1. Sub-words vocabulary
	2. Transformers
	3. Training large language models
	4. GPT and other pre-trained models
 	5. Auto-complete
	6. Classification
4. Text summarizer: how to adapt a pre-trained model to a specific task
	1. Few shot prompt
	2. Classification
	3. Summarization	
	4. Prompt evaluation with hypothesis testing
	5. Fine-tuning
	6. Reinforcement learning with human feedback intro (TODO)
5. Document question-answering: how to augment the memory of a language model
	1. In-memory question answering
	2. Summarization question answering
	3. Similarity search
	4. Embedding question answering
	5. LM chains and Langchain

