# A Brief History of Artificial Intelligence

Artificial intelligence is all about context. Knowing how the field evolved makes it easier to understand why current tools work the way they do, and how to debug problems when you run into them. Modern breakthroughs like transformers and large language models came from many earlier ideas and failures.

A classic example of context is the sentence:

> I swam across the river to get to the other bank.

The word "bank" alone is ambiguous. With "swam" and "river" around it, the meaning becomes clear. Modern AI (especially transformers) is built to capture this kind of context.

---

## Ancient Roots and Early Ideas

- Early myths of artificial beings  
  - Greek: Talos, Hephaestus' mechanical servants  
  - Chinese: Yan Shi’s automaton  
- Development of formal logic (Aristotle)  
- Leibniz imagined a "machine for reasoning"  
- The key idea: the world (including thinking) might be described using rules or mathematics.
- People thousands of years ago were just as intelligent as today, but lacked the tools, data, and computing technology.

---

## Foundations of Computation

- 1936: Alan Turing proposes the Turing Machine as an abstract model of computation.  
- 1950: Turing Test asks "Can machines think?" and proposes a behavioral test for machine intelligence.  
- These ideas set the stage for AI by showing that computation can model many aspects of reasoning.

---

## The Birth of AI (1950s to 1960s)

- 1956 Dartmouth Conference marks the start of AI as a formal field.  
- Key pioneers: John McCarthy, Marvin Minsky, Herbert Simon, Allen Newell.  
- Early symbolic AI systems:  
  - Logic Theorist  
  - General Problem Solver  
- Strong optimism: many believed human-level AI was only a few decades away.
- Limitation: hardware was weak. There were no modern computers or GPUs, so ideas outpaced what could be built.

---

## AI Winters (1970s to 1980s)

- Early systems failed to handle real world complexity.  
- Lighthill Report in the UK criticised AI research.  
- DARPA and other agencies reduced funding in the US.  
- Result:  
  - Loss of confidence and cuts in budgets  
  - Mathematicians and researchers continued theory, but AI mostly disappeared from the spotlight  
- Symbolic AI and rules-based approaches showed clear limits.

---

## The Rise of Machine Learning (1990s to 2000s)

- Shift from rules-based systems to statistical learning.  
- Growth of digital data and improvements in computing power allowed practical use of statistics.  
- Important ML methods from this era:  
  - Decision Trees  
  - Support Vector Machines  
  - Ensemble methods like Random Forests and Boosting  
- 1997: IBM Deep Blue defeats Garry Kasparov at chess.  
  - Big symbolic moment that showed computers could beat humans in complex tasks.  
- Machine learning became the dominant approach as computers finally had enough power to handle the math.

---

## Deep Learning Revolution (2010s)

- 2012: AlexNet wins the ImageNet competition using a deep convolutional neural network.  
  - First time a model clearly beat traditional methods on large-scale image recognition.  
  - Proved that deep neural networks could be practical, not just theory.  
- GPUs made training large models fast enough to be useful.  
  - Cryptocurrency mining also pushed GPU availability and performance.  
- Deep learning succeeds in:  
  - Computer vision  
  - Speech recognition  
  - Early language tasks  
- 2016: AlphaGo beats Lee Sedol at Go using deep reinforcement learning.  
  - Go is far more complex than chess, so brute force search is not enough.  
  - Demonstrated the power of combining deep learning with reinforcement learning.

---

## Transformers and Attention

- 2017: Paper "Attention Is All You Need" introduces the transformer architecture and self-attention.  
  - Attention is a way to use context: each word is interpreted based on surrounding words.  
  - This solves many limitations of earlier sequence models like RNNs and LSTMs.  
- At first, the impact was not obvious. Many courses and companies were still focused on CNNs, RNNs, and traditional ML in 2019–2021.  
- Over time, transformers became the core of modern NLP and many other domains.

---

## Generative AI and Foundation Models (2020s)

- Large scale transformer models begin to dominate:  
  - GPT-2 (early, very hallucination-prone but a proof of concept)  
  - GPT-3 to GPT-4  
  - Claude  
  - Gemini  
- Foundation models trained on huge text and multimodal datasets:  
  - ChatGPT  
  - DALL·E  
  - Midjourney  
  - GitHub Copilot  
- Capabilities:  
  - Text generation and chat  
  - Code generation  
  - Image generation and understanding  
  - Audio and multimodal reasoning  
- Two broad model types today:  
  - Text-only foundation models  
  - Multimodal models (language, images, audio, video)

---

## Challenges and Considerations

- Bias and fairness  
  - Models can inherit bias from training data.  
  - Larger models often trend toward more balanced behavior because they see more varied data, but bias never fully disappears.  
- Explainability and transparency  
  - Many models are black boxes.  
  - Difficult to explain why a specific decision or answer was produced, even when decisions involve large amounts of money or safety.  
- Hallucinations  
  - Models sometimes produce confident but false information.  
  - Problematic when used in high stake contexts.  
- Alignment and safety  
  - Different countries and cultures want models aligned with their values and historical narratives.  
  - Same question can produce very different answers across models.  
- Regulation and ethics  
  - Governments are only starting to understand AI.  
  - Regulatory frameworks lag behind the technology.  
  - Questions about who sets the rules and how to enforce them.  
- Environmental cost  
  - Training large models consumes significant energy and compute resources.

---

## Key Paradigm Shifts in AI

1. Symbolic AI (1950s to 1980s)  
   - Logic, rules, and hand coded reasoning.  
2. Statistical Machine Learning (1990s to 2010s)  
   - Decision trees, SVMs, ensembles, data driven methods.  
3. Deep Learning (2010s)  
   - Neural networks, CNNs, and deep architectures powered by GPUs.  
4. Foundation Models and Generative AI (2020s to now)  
   - Transformer based models, large scale pretraining, multimodal AI.

---

## One Sentence Summary

AI evolved from symbolic reasoning to statistical learning to deep neural networks, and now to large transformer based foundation models, with each stage driven by better data, more compute, and new algorithms, plus an increasing focus on context, alignment, and real world impact.
