**Multimodal Summarization using CLIP and BART**

This project explores multimodal summarization, focusing on generating concise summaries of technical project documentation containing both text and images. By leveraging the strengths of CLIP for image-text embeddings and BART for abstractive summarization, the model generates meaningful summaries from multimodal input data.

**Project Overview**

Combines CLIP (Contrastive Language–Image Pre-training) for processing image-text relationships and BART (Bidirectional and Auto-Regressive Transformers) for summary generation.
Processes over 700 PDFs of technical documentation from capstone projects, containing textual and visual data like diagrams and tables.
Cross-attention mechanisms align text and image embeddings for effective summarization.

**Key Features**

Multimodal Input: Supports text and images as input for summarization.
CLIP Integration: Converts visual and textual elements into a unified embedding space.
BART Decoder: Generates human-like abstractive summaries from cross-modal embeddings.
Cross-Attention Mechanism: Ensures robust interaction between image and text embeddings.

**Dataset**

A collection of technical project documents from SRM University AP (capstone projects).
Preprocessed to extract essential sections and associated images for training.

**Model Architecture**

CLIP Encoder: Encodes text and images into embeddings.
Cross-Attention Layer: Aligns and integrates embeddings.
BART Decoder: Generates a coherent, abstractive summary.
