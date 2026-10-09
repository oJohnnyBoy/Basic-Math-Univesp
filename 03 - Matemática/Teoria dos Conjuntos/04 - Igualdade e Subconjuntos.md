---
título: Igualdade e Subconjuntos
tema: Teoria dos Conjuntos
tags:
  - matemática
  - conjuntos
  - subconjuntos
---

# 04 — Igualdade e Subconjuntos

## 1. Igualdade

`A = B` se, e somente se, todo elemento de A pertence a B **e** todo elemento de B pertence a A.
A = B ⇔ ∀x, (x ∈ A ⇔ x ∈ B)

> [!warning] Repetição é irrelevante
> `{a, a, b}` = `{a, b}`. Em Estatística, porém, frequência importa.

## 2. Subconjunto

`A ⊆ B` se todo elemento de A também pertence a B.

**Leituras:**
- A está contido em B
- A é subconjunto de B
- B contém A → `B ⊇ A`

**Não contido:** `A ⊄ B`

### Propriedades

| Propriedade | Descrição |
|---|---|
| Vazio | `∅ ⊆ A` |
| Reflexiva | `A ⊆ A` |
| Antissimétrica | `A ⊆ B` e `B ⊆ A` ⇒ `A = B` |
| Transitiva | `A ⊆ B` e `B ⊆ C` ⇒ `A ⊆ C` |

---

---

## 🖼️ Exemplos visuais

![[mat-venn-igualdade-subconjunto.svg]]

*Círculo dentro = contido; círculos coincidentes = iguais.*

## ✏️ Exercícios

> [!question] 1. Determine se é verdadeiro
> a) `{1, 2} ⊆ {1, 2, 3}`  
> b) `{1, 2, 3} ⊆ {1, 2}`  
> c) `∅ ⊆ {a, b}`

> [!success]- Resposta
> a) V  
> b) F  
> c) V

> [!question] 2. Igualdade
> `A = {x ∈ ℕ | x < 3}` e `B = {0, 1, 2}`. São iguais?

> [!success]- Resposta
> Sim, `A = B`.

> [!question] 3. Subconjuntos
> Liste todos os subconjuntos de `{a, b}`.

> [!success]- Resposta
> `∅, {a}, {b}, {a, b}`