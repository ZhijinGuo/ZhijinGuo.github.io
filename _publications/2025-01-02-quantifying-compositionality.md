---
title: "Quantifying compositionality in classic and state-of-the-art embeddings"
collection: publications
permalink: /publication/2025-01-02-quantifying-compositionality
excerpt: "A comprehensive evaluation of compositionality in embeddings across SBERT, GPT, LLAMA, and Knowledge Graph embeddings."
date: 2025-01-02
venue: "Under review by the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP)"
citation: "Z. Guo, C. Xue, Z. Xu, et al., \"Quantifying compositionality in classic and state-of-the-art embeddings,\" under review by the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP), 2025."
---

This paper addresses the challenge that state-of-the-art Transformer and graph models lacked measurable limits on context-driven meaning shifts, undermining trust in novel expression generalization.

**Abstract**: We designed a two-step evaluation methodology that applies Canonical Correlation Analysis to quantify linear alignment between known entity attributes and their embeddings, then reconstructs embeddings for unseen attribute combinations across SBERT, GPT, LLAMA, and Knowledge Graph embeddings.

**Key Contributions**:
- Novel two-step evaluation methodology for embedding compositionality
- Canonical Correlation Analysis for quantifying attribute-embedding alignment
- Comprehensive evaluation across multiple embedding types (SBERT, GPT, LLAMA, TransE/DistMult)
- Metrics including L2 loss, cosine similarity, and retrieval accuracy
- Analysis of optimal layer selection for downstream tasks

**Results**: 
- Demonstrated additive compositionality during training
- Improved generalization in Multi-BERT 
- 1.5× rise in attribute–embedding correlation in graph models
- Found deeper transformer layers peaked at 94% compositional signal before tail-off

**Applications**: Developed rigorous embedding-quality metrics analogous to quantitative finance signal validation, improving reliability of text-driven systematic strategy inputs.

Recommended citation: Z. Guo, C. Xue, Z. Xu, et al., "Quantifying compositionality in classic and state-of-the-art embeddings," Under review by the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP), 2025.
