---
título: Diagrama de Venn
tipo: conceito
área: Matemática / Teoria dos Conjuntos
tags:
  - matemática
  - conjuntos
  - diagrama-de-venn
  - visualização
---

# 🔵 Diagrama de Venn

> [!abstract] Definição
> Representação gráfica de conjuntos por meio de **círculos** (ou outras formas fechadas), que permite visualizar elementos, interseções e relações entre conjuntos.
> Também chamado de **Diagrama de Euler-Venn** — em homenagem a **Leonhard Euler** e **John Venn**.

## Visual

![[Pasted image 20261009105414.png]]       ![[Pasted image 20261009105541.png]]

![[Pasted image 20261009105626.png]]

![[Pasted image 20261009105638.png]]

## 🎨 Representação básica

- Cada conjunto = um círculo
- Área interna = elementos do conjunto
- Sobreposição = elementos comuns (**interseção**)
- Área fora dos círculos = elementos que não pertencem aos conjuntos representados
![[mat-venn-operacoes-2.svg]]

*As seis operações entre dois conjuntos, com a região resultado destacada.*
Universo (U)


## 🔗 Relações visuais

| Relação | Representação |
|---|---|
| `A ⊆ B` | Círculo A dentro do círculo B |
| `A = B` | Círculos coincidentes |
| `A ∩ B = ∅` | Círculos separados |
| `A ∩ B ≠ ∅` | Círculos com sobreposição |
| `A − B` | Parte de A fora de B |

## 1. Dois conjuntos

- **Interseção** (`A ∩ B`): elementos comuns
- **União** (`A ∪ B`): todos os elementos
- **Diferença** (`A − B`): elementos só de A

## 2. Três conjuntos

Com três círculos é possível visualizar **8 regiões**:

- 3 regiões de apenas um conjunto
- 3 regiões de interseção dupla
- 1 região de interseção tripla
- 1 região externa (fora dos três, mas dentro do universo)

> [!tip] Fórmula da união (2 conjuntos)
> `n(A ∪ B) = n(A) + n(B) − n(A ∩ B)`

> [!tip] Fórmula da união (3 conjuntos)
> `n(A∪B∪C) = n(A) + n(B) + n(C) − n(A∩B) − n(A∩C) − n(B∩C) + n(A∩B∩C)`

---

---

## 🖼️ Exemplos visuais

![[mat-venn-tres-conjuntos.svg]]

*Com três círculos surgem 8 regiões — cada numeral é uma delas.*

![[mat-venn-exemplo-40.svg]]

*O exercício 1 resolvido região por região.*

## ✏️ Exercícios

> [!question] 1. Dois conjuntos
> Em uma turma de 40 alunos, 25 gostam de Matemática, 20 gostam de Português e 10 gostam das duas. Quantos **não gostam de nenhuma**?

> [!success]- Resposta
> `n(M ∪ P) = 25 + 20 − 10 = 35`  
> `40 − 35 = 5` alunos não gostam de nenhuma.

> [!question] 2. Três conjuntos
> Em uma pesquisa com 100 pessoas:  
> - 50 leem jornal A  
> - 40 leem jornal B  
> - 30 leem jornal C  
> - 20 leem A e B  
> - 15 leem A e C  
> - 10 leem B e C  
> - 5 leem os três  
> Quantas **não leem nenhum**?

> [!success]- Resposta
> `n(A∪B∪C) = 50+40+30 −20−15−10 +5 = 80`  
> Não leem nenhum: `100 − 80 = 20`

> [!question] 3. Desenhe o diagrama
> Represente graficamente `A ⊆ B`.

> [!success]- Resposta
> Círculo A completamente dentro do círculo B.

> [!question] 4. Desafio
> Se `A ∩ B = ∅`, como ficam os círculos no diagrama?

> [!success]- Resposta
> Círculos **separados**, sem sobreposição (conjuntos disjuntos).

## 🔗 Links relacionados

- [[Teoria dos Conjuntos]]
- [[Conjuntos Numéricos]]
- [[Matemática Básica]]
- [[01 - Noções Primitivas e Pertinência]]
- [[04 - Igualdade e Subconjuntos]]