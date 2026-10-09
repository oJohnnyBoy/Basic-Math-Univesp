---
título: Propriedades da União e da Interseção
tema: Operações com Conjuntos
tags:
  - matemática
  - conjuntos
  - propriedades
---

# 04 — Propriedades da União e da Interseção

## 🔗 Propriedades da União (∪)

| Nome | Propriedade |
|---|---|
| **Idempotência** | `A ∪ A = A` |
| **Elemento neutro** | `A ∪ ∅ = A` |
| **Comutatividade** | `A ∪ B = B ∪ A` |
| **Associatividade** | `(A ∪ B) ∪ C = A ∪ (B ∪ C)` |

## 🔗 Propriedades da Interseção (∩)

| Nome | Propriedade |
|---|---|
| **Idempotência** | `A ∩ A = A` |
| **Comutatividade** | `A ∩ B = B ∩ A` |
| **Associatividade** | `(A ∩ B) ∩ C = A ∩ (B ∩ C)` |
| **Interseção com U** | `A ∩ U = A` |

> [!info] Curiosidade sobre nomes
> Os nomes (idempotência, elemento neutro, comutatividade, associatividade) raramente serão usados no dia a dia, mas fazem parte da linguagem formal da Álgebra.

## 1. Idempotência

- `A ∪ A = A`
- `A ∩ A = A`

> Faz sentido: juntar A consigo mesmo (ou achar os elementos comuns entre A e ele mesmo) sempre dá A.

## 2. Elemento neutro

- **União:** `A ∪ ∅ = A` → o vazio é o **elemento neutro** da união
- **Interseção com o universo:** `A ∩ U = A` → o universo é o **elemento neutro** da interseção

> [!tip] Analogia
> Funciona como o `0` na adição ou o `1` na multiplicação: operar não muda o resultado.

## 3. Comutatividade

- `A ∪ B = B ∪ A`
- `A ∩ B = B ∩ A`

> A **ordem** dos conjuntos não altera o resultado.

## 4. Associatividade

- `(A ∪ B) ∪ C = A ∪ (B ∪ C)`
- `(A ∩ B) ∩ C = A ∩ (B ∩ C)`

> O **agrupamento** (parênteses) não altera o resultado.

---

---

## 🖼️ Exemplos visuais

![[mat-venn-propriedades.svg]]

*As quatro propriedades e a tabela de simplificações.*

## ✏️ Exercícios

> [!question] 1. Simplifique
> a) `A ∪ ∅`  
> b) `A ∩ A`  
> c) `A ∪ A`  
> d) `A ∩ U`

> [!success]- Resposta
> a) `A`  
> b) `A`  
> c) `A`  
> d) `A`

> [!question] 2. Verifique se é comutativo
> `{1, 2} ∪ {3, 4}` = `{3, 4} ∪ {1, 2}`?

> [!success]- Resposta
> Sim, ambos dão `{1, 2, 3, 4}`.

> [!question] 3. Associatividade
> Sendo `A = {1, 2}`, `B = {2, 3}`, `C = {3, 4}`, calcule `(A ∪ B) ∪ C` e `A ∪ (B ∪ C)`.

> [!success]- Resposta
> `(A ∪ B) = {1, 2, 3}` → `∪ C = {1, 2, 3, 4}`  
> `(B ∪ C) = {2, 3, 4}` → `A ∪ = {1, 2, 3, 4}`  
> Os resultados **são iguais**.

> [!question] 4. Desafio
> Se `A ∪ B = A`, o que podemos concluir sobre `B`?

> [!success]- Resposta
> Que `B ⊆ A` (B é subconjunto de A).