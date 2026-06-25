# The Relative Distance Era

Shifted focus from absolute indices to the relative distance between pairs of tokens. This approach models relative offsets as trainable bias tensors inside the attention matrix.

```mermaid
graph LR
    A[Token i] --> C{Attention Matrix}
    B[Token j] --> C
    D[Relative Distance i-j] --> E[Trainable Bias]
    E --> C
```

[Back to Home](../README.md)