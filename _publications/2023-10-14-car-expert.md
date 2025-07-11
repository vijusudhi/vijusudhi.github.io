---
title: "CarExpert: Leveraging Large Language Models for In-Car Conversational Question Answering"
collection: publications
category: conference
permalink: /publications/2023-10-14-car-expert
excerpt: 'We propose CarExpert, an in-car retrieval-augmented conversational question-answering system leveraging LLMs for different tasks. Specifically, CarExpert employs LLMs to control the input, provide domain-specific documents to the extractive and generative answering components, and controls the output to ensure safe and domain-specific answers. '
date: 2023-10-14
venue: 'Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing: Industry Track'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://aclanthology.org/2023.emnlp-industry.56/'
citation: 'Md Rashad Al Hasan Rony, Christian Suess, Sinchana Ramakanth Bhat, Viju Sudhi, Julia Schneider, Maximilian Vogel, Roman Teucher, Ken Friedl, and Soumya Sahoo. 2023. CarExpert: Leveraging Large Language Models for In-Car Conversational Question Answering. In Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing: Industry Track, pages 586–604, Singapore. Association for Computational Linguistics.'
---

Large language models (LLMs) have demonstrated remarkable performance by following natural language instructions without fine-tuning them on domain-specific tasks and data. However, leveraging LLMs for domain-specific question answering suffers from severe limitations. The generated answer tends to hallucinate due to the training data collection time (when using off-the-shelf), complex user utterance and wrong retrieval (in retrieval-augmented generation). Furthermore, due to the lack of awareness about the domain and expected output, such LLMs may generate unexpected and unsafe answers that are not tailored to the target domain. In this paper, we propose CarExpert, an in-car retrieval-augmented conversational question-answering system leveraging LLMs for different tasks. Specifically, CarExpert employs LLMs to control the input, provide domain-specific documents to the extractive and generative answering components, and controls the output to ensure safe and domain-specific answers. A comprehensive empirical evaluation exhibits that CarExpert outperforms state-of-the-art LLMs in generating natural, safe and car-specific answers.


<iframe id="pubIFrame" name="pubIFrame" style="width:100%;height:1600px;border:0" src="https://pub.uni-bielefeld.de/embed?cql=person%3D575596699&amp;lang=de&amp;fmt=iframe"></iframe>