---
título: Representação de Conjuntos e Diagrama de Venn
tema: Teoria dos Conjuntos
tags:
  - matemática
  - conjuntos
  - diagrama-de-venn
---

# 02 — Representação de Conjuntos e Diagrama de Venn

## 1. Enumeração

Elementos entre **chaves**, separados por vírgula.

- `A = {1, 2, 3, 4, 5}`
- `B = {Flamengo, Palmeiras, Corinthians}` (sem ordenação)

## 2. Propriedade característica

Descreve o conjunto por uma característica.
- `A = {x | x tem a propriedade P}`

A barra `|` significa **“tal que”**.

**Exemplos:**
- `A = {x | x é divisor de 3}`
- `B = {x ∈ ℤ | 0 ≤ x ≤ 100}`

> [!info] Conjunto finito vs. infinito
> - **Finito:** `{1, 2, 3}`
> - **Infinito:** `{2, 3, 5, 7, 11, ...}`

## 3. Diagrama de Venn

- Círculos representam conjuntos.
- Elementos podem estar em um, dois ou três conjuntos.

> [!example] Exemplo
> Três círculos = três conjuntos. Interseções mostram elementos comuns.

---

---

## 🖼️ Exemplos visuais

![[mat-venn-representacao.svg]]

*As três notações descrevem o mesmo conjunto A = {2, 4, 6, 8}.*

## ✏️ Exercícios

> [!question] 1. Represente por enumeração
> a) Conjunto dos números pares entre 1 e 10.  
> b) Conjunto dos divisores de 12.

> [!success]- Resposta
> a) `{2, 4, 6, 8, 10}`  
> b) `{1, 2, 3, 4, 6, 12}`

> [!question] 2. Represente por propriedade
> a) `{1, 3, 5, 7, 9}`  
> b) `{2, 3, 5, 7, 11, 13, ...}`

> [!success]- Resposta
> a) `{x | x é ímpar e 1 ≤ x ≤ 9}`  
> b) `{x | x é primo positivo}`

> [!question] 3. Diagrama de Venn
> Em uma turma, 20 alunos gostam de Matemática, 15 de Física, e 8 gostam das duas. Quantos gostam de pelo menos uma?

> [!success]- Resposta
> `20 + 15 − 8 = 27` alunos.