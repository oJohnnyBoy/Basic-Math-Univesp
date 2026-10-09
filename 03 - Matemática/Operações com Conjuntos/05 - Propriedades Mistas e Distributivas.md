---
título: Propriedades Mistas e Distributivas
tema: Operações com Conjuntos
tags:
  - matemática
  - conjuntos
  - distributividade
  - propriedades-mistas
---

# 05 — Propriedades Mistas e Distributivas

> [!abstract] Misturando união e interseção
> Além das propriedades isoladas, existem propriedades que **combinam** `∪` e `∩`.

## 1. Propriedades de absorção

| Propriedade | Descrição |
|---|---|
| `A ∩ (A ∪ B) = A` | "A absorve a união com B" |
| `A ∪ (A ∩ B) = A` | "A absorve a interseção com B" |

> [!tip] Por que funciona?
> Tudo que está em A permanece em A quando fazemos união ou interseção com **qualquer** conjunto que contém A.

## 2. Propriedades distributivas

### Distributiva da interseção sobre a união
A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)

### Distributiva da união sobre a interseção
A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C)


> [!example] Analogia com "chuveirinho"
> Assim como em álgebra: `3 · (5 + x) = 3 · 5 + 3 · x`, aqui "distribuímos" o conjunto A para dentro dos parênteses.

## 3. Ordem de resolução

Em expressões mistas, resolva **primeiro o que está entre parênteses**, depois o restante.

**Exemplo:**
`A ∪ (B ∩ C)` → resolve `B ∩ C` primeiro → depois `A ∪ (resultado)`

## 4. Visualização no Diagrama de Venn

- `A ∩ (B ∪ C)`: parte de A que também está em B ou C
- `A ∪ (B ∩ C)`: A inteiro + a parte comum de B e C

---

---

## 🖼️ Exemplos visuais

![[mat-venn-distributiva.svg]]

*Os dois lados da distributiva pintam exatamente a mesma região.*

## ✏️ Exercícios

> [!question] 1. Aplique a distributiva
> `A ∩ (B ∪ C)` com `A = {1, 2, 3}`, `B = {2, 3, 4}`, `C = {3, 5}`.

> [!success]- Resposta
> **Passo 1:** `B ∪ C = {2, 3, 4, 5}`  
> **Passo 2:** `A ∩ (B ∪ C) = {2, 3}`  
> **Verificação pela distributiva:**  
> `A ∩ B = {2, 3}`  
> `A ∩ C = {3}`  
> `(A ∩ B) ∪ (A ∩ C) = {2, 3} ∪ {3} = {2, 3}` ✅

> [!question] 2. Aplique a outra distributiva
> `A ∪ (B ∩ C)` com `A = {1}`, `B = {1, 2}`, `C = {1, 3}`.

> [!success]- Resposta
> **Passo 1:** `B ∩ C = {1}`  
> **Passo 2:** `A ∪ (B ∩ C) = {1}`  
> **Verificação:**  
> `A ∪ B = {1, 2}`  
> `A ∪ C = {1, 3}`  
> `(A ∪ B) ∩ (A ∪ C) = {1}` ✅

> [!question] 3. Absorção
> Simplifique `A ∪ (A ∩ B)`.

> [!success]- Resposta
> `A ∪ (A ∩ B) = A`.

> [!question] 4. Desafio
> Calcule `A ∩ (B ∪ C)` sendo `A = B = C = {1, 2, 3}`.

> [!success]- Resposta
> `B ∪ C = {1, 2, 3}`  
> `A ∩ {1, 2, 3} = {1, 2, 3}`  
> Logo, o resultado é `{1, 2, 3}`.

> [!question] 5. Ordem importa?
> `(A ∩ B) ∪ C` e `A ∩ (B ∪ C)` dão sempre o mesmo resultado?

> [!success]- Resposta
> **Não.** A ordem dos parênteses **importa**. Dê um exemplo:
> - `A = {1}`, `B = {2}`, `C = {1, 2}`
> - `(A ∩ B) ∪ C = ∅ ∪ {1, 2} = {1, 2}`
> - `A ∩ (B ∪ C) = {1} ∩ {1, 2} = {1}` → **diferente!**