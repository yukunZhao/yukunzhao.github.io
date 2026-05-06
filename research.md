## **RESEARCH STATEMENT** 

Yukun Zhao (yukunzhao.sdu@gmail.com) 

I develop natural language processing and information retrieval algorithms that are tightly coupled with realworld applications, particularly in search, question answering, and dialogue systems. My work has consistently aimed to bridge the gap between theory and deployment: from large language model adaptation to human-centered evaluation, and from academic exploration to product-grade performance. 

My research background has been uniquely shaped by nearly five years of experience as a Staff Engineer at Baidu, combined with graduate training at Shandong University. At Baidu, I led core efforts in trustworthy large language models (LLMs), (visual) retrieval-augmented generation (RAG), question answering, and dialogue systems, all of which powered widely used systems in Baidu Web Search and Multimodal Search. 

The novelty and practical value of my work are reflected in multiple first-author papers published at top-tier conferences including ACL, NAACL, COLING, EMNLP, and SIGIR. These projects tackle fundamental problems, such as hallucination detection, robustness, generalization, and visual-linguistic grounding, while also delivering measurable gains in deployed AI services. 

In this research statement, I first summarize my research contributions on trustworthy LLMs, multimodal large language models (MLLMs), traditional language models (LMs), and topic modeling in the pre-LM area. Then I describe my research philosophy and conclude with my future research directions in conversational AI, particularly in the context of image/query understanding, search planning, RAG, and alignment learning. 

## **1 Research Contributions** 

I aim to bring a practical, deployment-driven perspective to NLP research. My research contributions are summarized in three main areas: 

**Trustworthy large language models** : LLMs inevitably produce hallucinations—plausible but incorrect outputs—which is widely recognized as a key challenge for deployment. My work targets this issue through novel mitigation techniques. I introduced a self-detection method to pre-detect prompts likely to induce hallucinations [1]. I also worked on consistency alignment of model outputs to improve robustness [2]. I proposed task knowledge injection via interpolations and knowledge reinstatement to improve generalization on user instructions [3]. To mitigate catastrophic forgetting during instruction tuning, I proposed joint flashback adaptation [4] to enable joint learning of latent tasks, new tasks, and flashbacks (a limited number of prompts from old tasks). The line of work has been published in top venues (ACL/NAACL/COLING), demonstrating both theoretical insight and practical impact on model reliability. 

**Vision-Language Alignment and RAG in MLLMs** : I have advanced methods for joint image–text modeling and co-developed VisLingInstruct [9], a framework that autonomously optimizes textual instructions between visual perception and language in MLLMs. It significantly boosts zero-shot performance on vision–language tasks. I also explored visual retrieval-augmented techniques for visual queries which augment MLLMs with external knowledge to ground visual tasks. With instruction optimization and our self-built visual RAG, our visual understanding ranks first among GPT-4o, ERNIE 4.5, Qwen2.5-VL, Seed1.5-VL, Doubao App, and Quark App. Altogether, my work in this area led to top performance in multimodal AI systems. 

**Language models** : I led Baidu’s dialogue system and machine reading comprehension (MRC) teams, advancing conversational AI before the ChatGPT era. A notable achievement is the DiQAD benchmark [5], a large-scale (100K dialogue) dataset for end-to-end open-domain dialogue quality assessment, released in EMNLP 2023. DiQAD provides human-judged quality labels for real user conversations, enabling rigorous evaluation of dialogue models. Baidu’s MRC technology was also improved for high-throughput question answering on search queries. One research paper [10] on debiasing has been published in AAAI 2023. 

**Topic Modeling for Understanding User Interests in Social Media** : This work was conducted during my master’s studies. To address the challenges posed by data sparsity, noise, and rapidly evolving content in social media, I proposed a dynamic user clustering topic model that tracks users’ evolving interests over time using temporal Dirichlet-multinomial mixtures in my work [6] and its extended version [8]. Building on this, I explored content personalization [7], which models both tweet content and author influence to improve performance in users’ timelines. These contributions offer practical methods for dynamic topic modeling and personalized user interest understanding in social media. 

## **2 Research philosophy** 

My research philosophy centers on translating research to real-world impact. In particular: 

**(1). Conducting impactful research.** I strive to work on research problems that are both scientifically fundamental and practically valuable. I focus on topics situated at the core of natural language processing and machine learning, such as trustworthiness of LLMs, retrieval-augmented generation, and multimodal understanding, where theoretical insights can lead to advances that are broadly recognized and adopted by the research community. I aim to contribute to mainstream directions while ensuring the technical rigor, reproducibility, and long-term relevance of my work. 

**(2). Maximizing social and user impact.** I prioritize research problems that are aligned with societal needs. I choose problems that have real-world implications, especially in the context of trustworthy AI, user interaction, and accessibility. For example, my work on hallucination detection, forgetting resistance, and instruction optimization is motivated by a desire to make AI systems safer, more transparent, and more useful in everyday applications. I place strong emphasis on developing methods that are robust, interpretable, and aligned with human values. 

**(3) Industrial collaboration** : Given my extensive experience in leading research teams in industry, I view industrial collaboration as a powerful catalyst for impactful research. I actively pursue partnerships with engineers, product teams, and industrial research labs to ensure that my work remains grounded in real-world challenges. This allows me to identify high-impact problems, access large-scale data and infrastructure, and validate research ideas through deployment. I believe that close collaboration between academia and industry is essential for advancing the state of the art and accelerating technology transfer. 

**(4) Cross-disciplinary collaboration.** I actively seek collaboration with researchers from adjacent domains such as computer vision, linguistics, neuroscience, and machine learning. These cross-disciplinary efforts help me approach problems from new angles and integrate diverse methodologies into my work. For instance, my research in multimodal language models benefits greatly from advances in visual representation learning, while my work on dialogue quality evaluation draws upon insights from discourse analysis and user behavior modeling. I believe that interdisciplinary research not only enriches technical innovation but also expands the real-world applicability and societal relevance of AI systems. 

## **3 Future research directions** 

My current research raises a number of potentially challenging research directions that I plan to address immediately. In future work, I plan to focus on advanced conversational AI, with research directions including fine-grained image and query understanding, search planning and agent-based interaction, retrieval-augmented generation, and human alignment training. By combining novel technical strategies with cross-disciplinary teamwork, I aim to advance conversational AI in directions that serve users and society. Furthermore, I will advance foundational technologies to enhance the performance of general intelligence systems to improve their effectiveness across various fields such as law, healthcare, education, etc. In the longer term, I intend to pursue a flexible and adaptable research agenda that addresses emerging challenges and leverages funding opportunities from diverse sources. 

## **References** 

- [1] Y. Zhao, et al. Knowing What LLMs DO NOT Know: A Simple Yet Effective Self-Detection Method. _NAACL_ 2024 

- [2] Y. Zhao, et al. Improving the Robustness of Large Language Models via Consistency Alignment. _COLING_ 2024 

- [3] Y. Zhao, et al. Task Knowledge Injection via Interpolations and Reinstatement for Large Language Model Generalization. _ACL_ 2025 

- [4] Y. Zhao, et al. Joint Flashback Adaptation for Forgetting-Resistant Instruction Tuning. Submitted to _EMNLP_ 2025 

- [5] Y. Zhao, et al. DiQAD: A Benchmark Dataset for Open-domain Dialogue Quality Assessment. _EMNLP_ 2023 

- [6] Y. Zhao, et al. Explainable User Clustering in Short Text Streams. _SIGIR_ 2016 

- [7] Y. Zhao, et al. Personalized Re-ranking of Tweets. _WISE_ 2016 

- [8] S. Liang, Z. Ren, Y. Zhao, et al. Inferring Dynamic User Interests in Streams of Short Texts for User Clustering. _TOIS_ 2017 

- [9] D. Zhu, X. Tang, W. Han, J. Lu, Y. Zhao, et al. VisLingInstruct: Elevating Zero-Shot Learning in Multi-Modal Language Models with Autonomous Instruction Optimization. _NAACL_ 2024 

- [10] Y. Lyu, P. Li, Y. Yang, M. Rijke, P. Ren, Y. Zhao, et al. Feature-level Debiased Natural Language Understanding. _AAAI_ 2023 

