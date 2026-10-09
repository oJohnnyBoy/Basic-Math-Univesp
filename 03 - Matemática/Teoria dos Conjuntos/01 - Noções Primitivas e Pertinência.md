---
título: Noções Primitivas e Pertinência
tema: Teoria dos Conjuntos
tags:
  - matemática
  - conjuntos
  - pertinência
---

# 01 — Noções Primitivas e Pertinência

> [!info] Noções primitivas
> São aceitas **sem definição formal**: **conjunto**, **elemento** e **relação de pertinência**.

## 1. Conjunto

Agrupamento, coleção, classe ou sistema.

**Exemplos:**
- Conjunto dos algarismos romanos: `{I, V, X, L, C, D, M}`
- Conjunto dos números positivos primos: `{2, 3, 5, 7, 11, ...}`

## 2. Elemento

Cada membro ou objeto que forma um conjunto.

Pode ser:
- letra
- palavra
- número
- **outro conjunto**

## 3. Relação de pertinência

| Situação | Notação | Leitura |
|---|---|---|
| x é elemento de A | `x ∈ A` | x pertence a A |
| x não é elemento de A | `x ∉ A` | x não pertence a A |

**Exemplo:**
Se `A = {1, 5, 10}`, então `5 ∈ A` e `7 ∉ A`.

---

---

## 🖼️ Exemplos visuais

![[mat-venn-pertinencia.svg]]

*Estar dentro do círculo é pertencer. Estar fora é não pertencer.*

## ✏️ Exercícios

> [!question] 1. Classifique como V ou F
> a) `3 ∈ {1, 2, 3, 4}`  
> b) `7 ∉ {2, 4, 6, 8}`  
> c) `{1, 2} ∈ {1, 2, 3}`  
> d) `∅ ∈ {∅}`

> [!success]- Resposta
> a) V  
> b) V  
> c) F — `{1, 2}` é **subconjunto**, não elemento.  
> d) V — o conjunto `{∅}` tem como único elemento o conjunto vazio.

> [!question] 2. Escreva com símbolos
> a) 5 pertence ao conjunto dos números ímpares.  
> b) O número 0 não pertence ao conjunto dos números positivos.

> [!success]- Resposta
> a) `5 ∈ {x | x é ímpar}`  
> b) `0 ∉ {x | x > 0}`

> [!question] 3. Desafio
> É possível um elemento ser um conjunto? Dê um exemplo.

> [!success]- Resposta
> Sim. Exemplo: `A = { {1, 2}, {3, 4} }`. Os elementos de A são os conjuntos `{1, 2}` e `{3, 4}`.