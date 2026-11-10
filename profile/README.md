# Joy Industrial

## 📢 News

- **[2026-11-10] 📊 Dataset release — RealCADBench-V1.0:** We have released RealCADBench, a benchmark for parametric CAD modeling from real industrial design intents, covering multimodal inputs and both part and assembly modeling. Explore the dataset and our evaluation leaderboards. [Dataset](https://huggingface.co/datasets/RealCADBench/RealCADBench-V1.0) · [GitHub & Leaderboards](https://github.com/joyindustrial/RealCADBench#leaderboards) · [Paper](https://arxiv.org/abs/2609.03773)
- **[2026-11-10] 🤖 Model release — JDI-Decision-V1:** We have released JDI-Decision-V1, a multimodal decision system that produces structured choices and probabilities from text and images. Model weights, inference resources, and reproduction instructions are available on Hugging Face. [Model](https://huggingface.co/JoyIndustrial/JDI-Decision-V1) · [GitHub](https://github.com/joyindustrial/JDI-Decision-V1)

## About Us

We are the Foundation Model Team at JD Industrial. We develop industrial foundation models that connect multimodal understanding and reasoning with engineering design and real supply chain workflows. Our goal is to make AI capable of solving industrial problems, with the domain knowledge and practical capabilities these tasks require.

Our work contributes to JoyIndustrial, JD Industrial’s industrial AI model family. Drawing on industrial data and feedback from real applications, we advance model architectures, reinforcement learning, and continual learning to improve how models understand industrial information and carry out complex tasks.

## Research and Innovation

### Industrial Multimodal Models

We develop models for understanding industrial product information across text and images, supporting tasks such as attribute extraction, product matching, and compliance review. Our research includes task-aware mixture-of-experts architectures that specialize experts and dynamically route tasks to reduce interference between capabilities. We combine reinforcement learning for reasoning and agentic tasks with feedback-driven learning to improve tool use and complex task execution.

### Domain Specialization and Industrial Knowledge

We build specialized capabilities on a shared industrial multimodal foundation, using independently trained LoRA adapters that load dynamically for different domains. Retrieval augmentation connects models with industrial knowledge bases and current product information. This approach supports technical question answering, product selection, bill-of-materials analysis, and alternative component recommendations across industrial sectors.

### Generative CAD and Engineering Design

Our VisCAD research translates multimodal design intent into CAD models. We develop CADIR, an intermediate representation for geometric modeling that simplifies adaptation across CAD software and domain-specific languages. Parallel test-time scaling improves design accuracy by generating and selecting among candidate designs. Automated data pipelines expand training coverage and improve supervision through data mining, annotation, augmentation, and distillation. Our evaluation work includes RealCADBench-V1.0, a benchmark built around real industrial products.

### Industrial World Models

We are exploring world models that represent industrial environments and predict how they may evolve. This research combines multimodal spatiotemporal representations with forecasts of multiple interacting agents, and connects world modeling with embodied planning and execution. We focus on potential applications in industrial safety and human–machine collaboration, including risk anticipation and decisions under changing operating conditions.

## Research Grounded in Industrial Practice

Real industrial workflows inform our research priorities and provide feedback for model improvement. We connect advances in model capability with evaluation and efficient inference, including long-context multimodal processing and deployment optimization. Our aim is to bring reliable, accessible AI capabilities to industrial enterprises and improve the efficiency of industrial supply chains.
