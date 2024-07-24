# Code organization

### A few pointers

-   [Markov-LLM](Markov-LLM) contains the full transformer model for binary k-order Markov sources with absolute positional embeddings.
-   [Markov-RPE](Markov-RPE) contains the full transformer model with relative positional embeddings.
-   [Markov-LLM-AO](Markov-LLM-AO) contains the attention-only model.

The script to run the experiments is in src/main.py.
