---
title: "Illuminer: Instruction-tuned large language models as few-shot intent classifier and slot filler"
collection: publications
category: conferences
permalink: /publications/2024-03-26-illuminer
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-03-26
venue: 'Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://aclanthology.org/2024.lrec-main.758/'
citation: 'Paramita Mirza, Viju Sudhi, Soumya Ranjan Sahoo, and Sinchana Ramakanth Bhat. 2024. ILLUMINER: Instruction-tuned Large Language Models as Few-shot Intent Classifier and Slot Filler. In Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024), pages 8639–8651, Torino, Italia. ELRA and ICCL.'
---

State-of-the-art intent classification (IC) and slot filling (SF) methods often rely on data-intensive deep learning models, limiting their practicality for industry applications. Large language models on the other hand, particularly instruction-tuned models (Instruct-LLMs), exhibit remarkable zero-shot performance across various natural language tasks. This study evaluates Instruct-LLMs on popular benchmark datasets for IC and SF, emphasizing their capacity to learn from fewer examples. We introduce ILLUMINER, an approach framing IC and SF as language generation tasks for Instruct-LLMs, with a more efficient SF-prompting method compared to prior work. A comprehensive comparison with multiple baselines shows that our approach, using the FLAN-T5 11B model, outperforms the state-of-the-art joint IC+SF method and in-context learning with GPT3.5 (175B), particularly in slot filling by 11.1--32.2 percentage points. Additionally, our in-depth ablation study demonstrates that parameter-efficient fine-tuning requires less than 6% of training data to yield comparable performance with traditional full-weight fine-tuning.