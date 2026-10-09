---
título: Interseção de Conjuntos
tema: Operações com Conjuntos
tags:
  - matemática
  - conjuntos
  - interseção
---

# 02 — Interseção de Conjuntos

> [!abstract] Definição
> Dados dois conjuntos **A** e **B**, a **interseção** de A e B é o conjunto formado pelos elementos que **pertencem a A E também pertencem a B**.

## 1. Notação
$$
A ∩ B = {x | x ∈ A e x ∈ B}
$$


- Símbolo: `∩` (interseção)
- Leitura informal: "A inter B"

## 2. Exemplo numérico

- `A = {1, 2, 3}`
- `B = {3, 4, 5}`
- `A ∩ B = {3}`

## 3. Com três conjuntos
$A ∩ B ∩ C = {x | x ∈ A e x ∈ B e x ∈ C}$

O elemento precisa estar **nos três conjuntos ao mesmo tempo**.

## 4. Diagrama de Venn

```
   A = {1, 2, 3}       B = {3, 4, 5}

   A inter B = {3}

   +-----+-----+-----+
   |  1  |  2  |  3  |   <- A
   +-----+-----+-----+
                 |
                 +-----> elemento comum aos dois
                 |
   +-----+-----+-----+
   |  3  |  4  |  5  |   <- B
   +-----+-----+-----+
                 ^
                 |
              A inter B
```

> [!tip] Dica visual
> A interseção é sempre a **região compartilhada**. Se não há região compartilhada, a interseção é o conjunto vazio.

---

---

## 🖼️ Exemplos visuais

![[mat-venn-intersecao.svg]]

*A interseção é a região compartilhada; sem sobreposição, é vazia.*

## ✏️ Exercícios

> [!question] 1. Calcule a interseção
> a) `{1, 2, 3} ∩ {2, 3, 4}`  
> b) `{a, b, c} ∩ {d, e, f}`  
> c) `{1, 2, 3} ∩ {1, 2, 3}`  
> d) `ℕ ∩ ℤ`

> [!success]- Resposta
> a) `{2, 3}`  
> b) `∅` (conjuntos disjuntos)  
> c) `{1, 2, 3}`  
> d) `ℕ` (pois ℕ ⊆ ℤ)

> [!question] 2. Três conjuntos
> `A = {1, 2, 3, 4}`, `B = {2, 4, 6}`, `C = {2, 4, 8}`. Determine `A ∩ B ∩ C`.

> [!success]- Resposta
> `{2, 4}` — ambos estão nos três conjuntos.

> [!question] 3. Aplicação
> Em uma pesquisa, 20 pessoas leem jornal A e 15 leem jornal B. Sabendo que 8 leem os dois, quantas leem **apenas A**?

> [!success]- Resposta
> Leem apenas A: `20 − 8 = 12` pessoas.

> [!question] 4. Verdadeiro ou falso
> a) `A ∩ B = B ∩ A`  
> b) `A ∩ ∅ = A`  
> c) `A ∩ A = A`  
> d) `U ∩ A = A` (U = universo)

> [!success]- Resposta
> a) **V**  
> b) **F** — `A ∩ ∅ = ∅`  
> c) **V**  
> d) **V**