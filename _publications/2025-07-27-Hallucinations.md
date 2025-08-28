---
title: "Alleviating Hallucinations from Knowledge Misalignment in Large Language Models via Selective Abstention Learning"
collection: publications
category: conferences
permalink: /publication/2025-07-27-Hallucinations
excerpt: ''
date: 2025-07-27
venue: 'ACL 2025'
paperurl: 'https://aclanthology.org/2024.lrec-main.934.pdf'
citation: 'Lei Huang, Xiaocheng Feng, Weitao Ma, Yuchun Fan, Xiachong Feng, Yuxuan Gu, Yangfan Ye, Liang Zhao, Weihong Zhong, <b>Baoxin Wang</b>, Dayong Wu, Guoping Hu, Lingpeng Kong, Tong Xiao, Ting Liu, and Bing Qin. 2025. In Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (<b>ACL 2025</b>).'
---

Large language models (LLMs) are known to suffer from severe hallucination issues. One of the main causes lies in the knowledge misalignment between the pre-training stage and the supervised fine-tuning stage. The unfamiliar knowledge encountered during fine-tuning may encourage LLMs to generate facts that are not grounded in parametric knowledge. To address this, we propose Seal, a novel training objective with an abstention mechanism, in which the model learns to selectively reject tokens that misalign with the desired knowledge distribution via a special [REJ] token. This allows the model the option of acknowledging the insufficiency of knowledge rather than blindly assigning high probability to all ground-truth answers. We further propose a regularized decoding objective that penalizes uncertain predictions during inference by using the [REJ] probability learned during training. Extensive experiments on six short-form and long-form QA datasets with three LLMs of different sizes demonstrate that our method effectively alleviates hallucinations caused by knowledge misalignment. Further analysis highlights the adaptations of our method in answer refusal scenarios and its ability to effectively maintain the model’s instruction-following capabilities.
