---
título: Exercícios Gerais de Operações com Conjuntos
tema: Operações com Conjuntos
tags:
  - matemática
  - conjuntos
  - exercícios
---

# 06 — Exercícios Gerais de Operações com Conjuntos

> [!abstract] Instruções
> Resolva os exercícios abaixo com base nas notas anteriores.
> Respostas em callouts recolhíveis.

## Parte 1 — União e interseção básicas

> [!question] 1. Calcule
> a) `{1, 2, 3} ∪ {3, 4}`  
> b) `{1, 2, 3} ∩ {3, 4}`  
> c) `{a, b} ∪ ∅`  
> d) `{a, b} ∩ ∅`

> [!success]- Resposta
> a) `{1, 2, 3, 4}`  
> b) `{3}`  
> c) `{a, b}`  
> d) `∅`

> [!question] 2. Considere `A = {1, 2, 3, 4, 5}` e `B = {4, 5, 6, 7}`. Determine:
> a) `A ∪ B`  
> b) `A ∩ B`  
> c) `A − B`  
> d) `B − A`

> [!success]- Resposta
> a) `{1, 2, 3, 4, 5, 6, 7}`  
> b) `{4, 5}`  
> c) `{1, 2, 3}`  
> d) `{6, 7}`

## Parte 2 — Conjuntos disjuntos

> [!question] 3. Verifique se são disjuntos:
> `A = {2, 4, 6}` e `B = {1, 3, 5}`

> [!success]- Resposta
> Sim, `A ∩ B = ∅`.

> [!question] 4. Se `A ∩ B = ∅` e `n(A) = 5`, `n(B) = 7`, quanto vale `n(A ∪ B)`?

> [!success]- Resposta
> `5 + 7 = 12`.

## Parte 3 — Propriedades

> [!question] 5. Simplifique
> a) `A ∪ A`  
> b) `A ∩ U`  
> c) `A ∩ (A ∪ B)`  
> d) `(A ∩ B) ∪ A`

> [!success]- Resposta
> a) `A`  
> b) `A`  
> c) `A`  
> d) `A`

> [!question] 6. Verifique a distributiva
> `A = {1, 2}`, `B = {2, 3}`, `C = {3, 4}`. Calcule `A ∪ (B ∩ C)` dos dois modos.

> [!success]- Resposta
> **Direto:** `B ∩ C = {3}` → `A ∪ {3} = {1, 2, 3}`  
> **Distributiva:** `(A ∪ B) = {1, 2, 3}` e `(A ∪ C) = {1, 2, 3, 4}` → `∩ = {1, 2, 3}` ✅

---

## 🖼️ Exemplo resolvido

![[mat-venn-exercicio-50.svg]]

*Preencha sempre pela interseção, depois só cada conjunto e por fim o resto.*

## Parte 4 — Problemas de contagem

> [!question] 7. Em uma turma de 50 alunos:
> - 30 estudam inglês  
> - 25 estudam espanhol  
> - 10 estudam ambos  
> Quantos **não** estudam nenhum dos dois?

> [!success]- Resposta
> `n(I ∪ E) = 30 + 25 − 10 = 45`  
> Não estudam nenhum: `50 − 45 = 5`

> [!question] 8. Em uma pesquisa com 200 pessoas:
> - 120 consomem produto A  
> - 90 consomem produto B  
> - 40 consomem os dois  
> Quantas consomem **apenas A**? E **apenas B**?

> [!success]- Resposta
> Apenas A: `120 − 40 = 80`  
> Apenas B: `90 − 40 = 50`

## Parte 5 — Diagrama de Venn e desafios

> [!question] 9. Se `A ⊆ B`, qual o valor de `A ∩ B` e `A ∪ B`?

> [!success]- Resposta
> `A ∩ B = A`  
> `A ∪ B = B`

> [!question] 10. Desafio
> `(A ∪ B) ∩ C` = `A ∪ (B ∩ C)`? Justifique ou dê contra-exemplo.

> [!success]- Resposta
> **Não é sempre igual.** Contra-exemplo:  
> - `A = {1}`, `B = {2}`, `C = {1, 2}`  
> - `(A ∪ B) ∩ C = {1, 2} ∩ {1, 2} = {1, 2}`  
> - `A ∪ (B ∩ C) = {1} ∪ {2} = {1, 2}`  
> Neste caso coincidiu. Mas com `A = {1, 3}`, `B = {2}`, `C = {1, 2}`:  
> - `(A ∪ B) ∩ C = {1, 2, 3} ∩ {1, 2} = {1, 2}`  
> - `A ∪ (B ∩ C) = {1, 3} ∪ {2} = {1, 2, 3}`  
> **Diferentes.**

---

## 🧠 Gabarito rápido

| Questão | Resposta                |
| ------- | ----------------------- |
| 1a      | `{1, 2, 3, 4}`          |
| 1b      | `{3}`                   |
| 1c      | `{a, b}`                |
| 1d      | `∅`                     |
| 2a      | `{1, 2, 3, 4, 5, 6, 7}` |
| 2b      | `{4, 5}`                |
| 4       | 12                      |
| 5a–5d   | A, A, A, A              |
| 7       | 5                       |
| 8       | 80 e 50                 |