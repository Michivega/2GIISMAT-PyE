---
tags:
  - def
---

**Parámetros:** $n \in \mathbb{N}$, $p \in (0,1)$

**Definición:** Número de veces que aparece $A$ en ejecuciones independientes hasta que por $n$-ésima vez aparece $A$

**Notación:** $BN(n,p)$

**Función de probabilidad:** $P(X = k) = \binom{n+k-1}{k}(1-p)^k p^n$

**Media:** $E(X) = \frac{n(1-p)}{p}$

**Varianza:** $\text{Var}(X) = \frac{n(1-p)}{p^2}$
