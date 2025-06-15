🥉 Bronze Medal Solution – Zindi Lelapa AI Buzuzu-Mavi Challenge
📌 Challenge Overview
The Lelapa AI Buzuzu-Mavi Challenge focused on addressing a critical issue in AI: the lack of performant, lightweight language models for African languages. Existing open-source LLMs are too large and resource-intensive, often requiring high-end GPUs and consuming significant energy—barriers for wide deployment in Africa.

This competition challenged participants to compress Lelapa AI’s InkubaLM—a small language model (SLM)—while retaining or improving performance on two underrepresented languages: Swahili and Hausa.

🏆 Solution Summary
This repository contains the solution that achieved a Bronze Medal in the challenge.

✅ Goals Achieved:
Model Compression: Applied quantization and pruning to reduce model size and inference time.

Performance Optimization: Fine-tuned for downstream tasks in Swahili and Hausa.

Balanced Trade-off: Delivered improved performance with significantly reduced resource demands.

🧪 Tasks & Evaluation
Participants were evaluated on:

Sentiment Analysis

AfriXNLI (Natural Language Inference)

Machine Translation (English → Swahili/Hausa)

The objective was to either:

Increase average model performance on any of the tasks/languages, or

Reduce model size and resource requirements, or

Do both effectively.

🔬 Techniques Used
🔧 Quantization: Reduced model precision to 8-bit and 4-bit where applicable.

✂️ Pruning: Removed redundant weights to decrease size.

🌍 Language-Specific Fine-tuning: Focused on domain/task-specific data for Swahili and Hausa.

💡 Impact
This project contributes to:

Making AI accessible in low-resource settings.

Empowering African developers with deployable tools.

Laying the groundwork for low-power NLP applications in healthcare, education, agriculture, and customer support.
