---
título: Conjuntos Disjuntos
tema: Operações com Conjuntos
disciplina: Matemática Básica
tags:
  - matemática
  - conjuntos
  - conjuntos-disjuntos
  - interseção
---

# 03 — Conjuntos Disjuntos

> [!abstract] Definição
> Dois conjuntos $A$ e $B$ são chamados de **conjuntos disjuntos** (ou mutuamente exclusivos) quando **não possuem nenhum elemento em comum**. Em termos formais, a interseção entre eles é o conjunto vazio.

$$A \cap B = \emptyset$$

---

## 1. Representação Gráfica no Diagrama de Venn

No Diagrama de Venn, conjuntos disjuntos são representados por círculos completamente separados, sem nenhuma área de sobreposição:
```
   A = {1, 3, 5}       B = {2, 4, 6}

   Nenhum elemento em comum  ->  A inter B = vazio

   +-----+-----+-----+       +-----+-----+-----+
   |  1  |  3  |  5  |       |  2  |  4  |  6  |
   +-----+-----+-----+       +-----+-----+-----+
          (A)                       (B)

   Os dois conjuntos ficam lado a lado, SEM sobreposicao.
```

---

## 2. Exemplos Notáveis

1. **Conjunto dos Pares vs. Ímpares:**
   - $P = \{x \in \mathbb{N} \mid x \text{ é par}\} = \{0, 2, 4, 6, \dots\}$
   - $I = \{x \in \mathbb{N} \mid x \text{ é ímpar}\} = \{1, 3, 5, 7, \dots\}$
   - $P \cap I = \emptyset \implies P$ e $I$ são disjuntos.

2. **Números Racionais vs. Irracionais:**
   - $\mathbb{Q} \cap \mathbb{I} = \emptyset \implies$ Um número real ou é racional ou é irracional, nunca ambos simultaneamente.

---

## 3. Cardinalidade da União de Conjuntos Disjuntos

Quando dois conjuntos finitos $A$ e $B$ são disjuntos, o número de elementos da sua união é simplesmente a soma direta dos elementos de cada um:

$$n(A \cup B) = n(A) + n(B) \quad (\text{se } A \cap B = \emptyset)$$

> [!info] Comparação com o caso geral
> Para conjuntos quaisquer (não disjuntos), a fórmula geral do Princípio da Inclusão-Exclusão é:
> $$n(A \cup B) = n(A) + n(B) - n(A \cap B)$$

---

---

## 🖼️ Exemplos visuais

![[mat-venn-disjuntos.svg]]

*Sem sobreposição não há elementos comuns: A ∩ B = ∅.*

## ✏️ Exercícios

> [!question] 1. Identificação de Disjunção
> Dados os conjuntos $A = \{x \in \mathbb{Z} \mid -2 \leq x \leq 2\}$ e $B = \{x \in \mathbb{N} \mid x \geq 3\}$, determine $A \cap B$ e classifique se são disjuntos.

> [!success]- Resposta sugerida
> - $A = \{-2, -1, 0, 1, 2\}$
> - $B = \{3, 4, 5, 6, \dots\}$
> - $A \cap B = \emptyset$.
> Portanto, $A$ e $B$ **são disjuntos**.

> [!question] 2. Problema de Cardinalidade
> Uma sala tem dois grupos de estudos disjuntos: o grupo de História com 14 alunos e o grupo de Química com 18 alunos. Nenhum aluno pertence aos dois grupos ao mesmo tempo. Quantos alunos há no total na soma dos dois grupos?

> [!success]- Resposta sugerida
> Como os grupos são disjuntos ($H \cap Q = \emptyset$):
> $$n(H \cup Q) = n(H) + n(Q) = 14 + 18 = \mathbf{32\text{ alunos}}.$$

---

## 🔗 Links relacionados

- [[00 - Operações com Conjuntos]]
- [[01 - Reunião (União) de Conjuntos]]
- [[02 - Interseção de Conjuntos]]
- [[04 - Propriedades da União e da Interseção]]
- [[Diagrama de Venn]]
- [[Matemática Básica]]
