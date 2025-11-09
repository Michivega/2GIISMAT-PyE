---
tags:
  - def
---
**Parámetros:** $N, D, n$

**Definición:** Número de elementos de la clase $A$ en una muestra de $n$ elementos sin reemplazamiento

**Notación:** $H(N,D,n)$

**Función de probabilidad:** $P(X = k) = \frac{\binom{D}{k} \binom{N-D}{n-k}}{\binom{N}{n}}$

**Media:** $E(X) = n \cdot \frac{D}{N}$

**Varianza:** $\text{Var}(X) = n \cdot \frac{D}{N} \cdot \frac{N-D}{N} \cdot \frac{N-n}{N-1}$
