# Selective Deference in Small Language Models

This project investigates how model size affects **selective deference** — the ability of Small Language Models (SLMs) to accept correct user corrections while resisting incorrect suggestions under multi-turn user pressure.

### Models
We evaluate six instruction-tuned models:
- Qwen2.5-Instruct: 1.5B, 3B, 7B
- Falcon3-Instruct: 1B, 3B, 7B

### Methodology
- Evaluated on 400 questions from the MMLU benchmark.
- Tested across multiple conversational turns with bare disagreement, correct suggestions, incorrect suggestions, and neutral controls.
- Measured resistance, acceptance, and true-versus-false discrimination.
- Used logistic regression to analyse the effects of model size, family, and initial confidence.

### Key Findings
Larger models demonstrate better baseline accuracy but become more susceptible to sustained user pressure. Increasing model size does not necessarily improve their ability to distinguish correct advice from incorrect suggestions.

### Authors
Shreyas Gupta and Anand Vardhan Shukla  
Birla Institute of Technology and Science, Pilani
