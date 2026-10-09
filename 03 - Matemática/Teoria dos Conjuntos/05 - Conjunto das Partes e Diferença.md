---
tema: Teoria dos Conjuntos
tags:
  - matemática
  - conjuntos
  - conjunto-das-partes
  - diferença
---

# 05 — Conjunto das Partes e Diferença

## 1. Conjunto das partes

`P(A)` = conjunto de **todos os subconjuntos** de A.
P(A) = {x | x ⊆ A}

**Exemplo:**
`A = {a, b}` → `P(A) = { ∅, {a}, {b}, {a, b} }`

> [!tip] Fórmula
> Se `A` tem `n` elementos, `P(A)` tem `2ⁿ` elementos.

## 2. Diferença

`A − B` = elementos que pertencem a A **e não** pertencem a B.
A − B = {x | x ∈ A e x ∉ B}


**Exemplo:**
`A = {1, 2, 3, 4}`, `B = {3, 4, 5, 6}` → `A − B = {1, 2}`

---

---

## 🖼️ Exemplos visuais

![[mat-venn-partes-diferenca.svg]]

*Os 4 subconjuntos de {a, b} e a diferença nos dois sentidos.*

## ✏️ Exercícios

> [!question] 1. Conjunto das partes
> Determine `P(A)` para `A = {1, 2, 3}`. Quantos elementos?

> [!success]- Resposta
> `P(A) = { ∅, {1}, {2}, {3}, {1,2}, {1,3}, {2,3}, {1,2,3} }`  
> `2³ = 8` elementos.

> [!question] 2. Diferença
> `A = {a, b, c, d}`, `B = {c, d, e}`. Calcule `A − B` e `B − A`.

> [!success]- Resposta
> `A − B = {a, b}`  
> `B − A = {e}`

> [!question] 3. Desafio
> Se `A − B = ∅`, o que podemos afirmar?

> [!success]- Resposta
> Que `A ⊆ B` (todos os elementos de A estão em B).

