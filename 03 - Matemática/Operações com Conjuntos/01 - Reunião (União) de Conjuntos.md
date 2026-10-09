---
título: Reunião de Conjuntos
tema: Operações com Conjuntos
tags:
  - matemática
  - conjuntos
  - união
  - reunião
---

# 01 — Reunião (União) de Conjuntos

> [!abstract] Definição
> Dados dois conjuntos **A** e **B**, a **reunião** (ou **união**) de A e B é o conjunto formado pelos elementos que **pertencem a A OU pertencem a B**.

## 1. Notação
$$
A ∪ B = {x | x ∈ A ou x ∈ B}
$$

- Símbolo: `∪` (união)
- Leitura: "A união B" ou "A reunido com B"

## 2. Exemplo numérico

- `A = {1, 2, 3}`
- `B = {3, 4, 5}`
- `A ∪ B = {1, 2, 3, 4, 5}`

> [!note] Observação importante
> O elemento `3` aparece nos dois conjuntos, mas na **união ele conta apenas uma vez**. Elementos repetidos **não se duplicam**.

---

## 🎨 Diagrama de Venn

![[mat-venn-uniao.svg]]

*União é toda a área pintada — a interseção entra junto.*

## 4. Caso de subconjunto

Se `A ⊆ B`:

- `A ∪ B = B`

> [!example] Exemplo
> Se `A = {1, 2}` e `B = {1, 2, 3, 4}`, então `A ∪ B = {1, 2, 3, 4} = B`, pois A já está contido em B.

---

## ✏️ Exercícios

> [!question] 1. Calcule a união
> a) `{1, 2} ∪ {2, 3, 4}`  
> b) `{a, b, c} ∪ {d, e}`  
> c) `{1, 3, 5} ∪ {1, 3, 5}`  
> d) `∅ ∪ {1, 2, 3}`

> [!success]- Resposta
> a) `{1, 2, 3, 4}`  
> b) `{a, b, c, d, e}`  
> c) `{1, 3, 5}`  
> d) `{1, 2, 3}`

> [!question] 2. Verdadeiro ou falso
> a) `A ∪ B = B ∪ A`  
> b) Se `A = ∅`, então `A ∪ B = B`  
> c) Na união, elementos repetidos aparecem duplicados  
> d) Se `A ⊆ B`, então `A ∪ B = A`

> [!success]- Resposta
> a) **V**  
> b) **V**  
> c) **F** — cada elemento aparece uma única vez  
> d) **F** — neste caso `A ∪ B = B`

> [!question] 3. Aplicação
> Em uma turma, 15 alunos gostam de Matemática e 12 gostam de Física. Sabendo que 5 gostam das duas, quantos gostam de **pelo menos uma** dessas disciplinas?

> [!success]- Resposta
> `n(M ∪ F) = 15 + 12 − 5 = 22` alunos.

> [!question] 4. Diagrama de Venn
> Desenhe `A ∪ B` para dois conjuntos com sobreposição.

> [!success]- Resposta
> Basta pintar **toda** a área dos dois círculos (incluindo a interseção).