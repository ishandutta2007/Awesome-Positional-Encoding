# The Rotary & Multi-Scale Era

Introduced Rotary Position Embedding (RoPE) which multiplies the Query and Key vectors by a rotation matrix, encoding relative distance as an angle in a complex plane.

```mermaid
graph TD
    A[Query/Key Vector] --> B[Rotation Matrix based on Position]
    B --> C[Rotated Vector in Complex Plane]
```

[Back to Home](../README.md)