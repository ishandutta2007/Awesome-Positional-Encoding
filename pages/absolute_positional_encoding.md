# Absolute Positional Encoding

Assigns a unique, standalone position vector to each absolute index before data reaches self-attention. It can be deterministic or learned.

```mermaid
graph LR
    A[Index 0] --> B[Vector 0]
    C[Index 1] --> D[Vector 1]
```

[Back to Home](../README.md)