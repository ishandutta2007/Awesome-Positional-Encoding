# The Absolute Static Era

This era focused on using fixed deterministic sine and cosine functions to encode positional information. These were directly added to the input token embeddings.

```mermaid
graph TD
    A[Token Index] --> B[Sine/Cosine Calculation]
    B --> C[Positional Vector]
    D[Word Embedding] --> E[Addition]
    C --> E
    E --> F[Transformer Input]
```

[Back to Home](../README.md)