---
título: Conjuntos Numéricos
tipo: conceito
área: Matemática / Teoria dos Conjuntos
tags:
  - matemática
  - conjuntos
  - conjuntos-numéricos
  - números
---

# 🔢 Conjuntos Numéricos

> [!abstract] Definição
> São conjuntos formados por números, organizados de forma hierárquica por inclusão:
> `ℕ ⊂ ℤ ⊂ ℚ ⊂ ℝ ⊂ ℂ`

## 1. Conjunto dos Naturais (ℕ)

Números usados para contagem.
- ℕ = {0, 1, 2, 3, 4, 5, ...}

- **ℕ*** = naturais **sem o zero**: `{1, 2, 3, ...}`

## 2. Conjunto dos Inteiros (ℤ)

Naturais + seus opostos (negativos).
ℤ = {..., −3, −2, −1, 0, 1, 2, 3, ...}


**Subconjuntos:**
- `ℤ*` = inteiros não nulos
- `ℤ₊` = inteiros não negativos
- `ℤ₋` = inteiros não positivos

## 3. Conjunto dos Racionais (ℚ)

Números que podem ser escritos como **fração** `a/b`, com `a, b ∈ ℤ` e `b ≠ 0`.
ℚ = {x | x = a/b, a ∈ ℤ, b ∈ ℤ*}

**Inclui:**
- Inteiros: `5 = 5/1`
- Decimais finitos: `0,25 = 1/4`
- Dízimas periódicas: `0,333... = 1/3`

## 4. Conjunto dos Irracionais (𝕀)

Números que **não** podem ser escritos como fração.

**Exemplos:**
- `√2`, `√3`, `π`, `e`
- Dízimas **não periódicas**: `2,71345...`

## 5. Conjunto dos Reais (ℝ)

União dos racionais e irracionais.

ℝ = ℚ ∪ 𝕀

Representação na reta real e hierarquia por inclusão:

![[mat-conjuntos-numericos.svg]]



## 6. Conjunto dos Complexos (ℂ)

Extensão dos reais com a unidade imaginária `i = √−1`.
ℂ = {a + bi | a, b ∈ ℝ}

## 🗂️ Relação entre os conjuntos

| Símbolo | Nome | Exemplos |
|---|---|---|
| `ℕ` | Naturais | 0, 1, 2, 3 |
| `ℤ` | Inteiros | −2, −1, 0, 1, 2 |
| `ℚ` | Racionais | 1/2, 0,75, −3 |
| `𝕀` | Irracionais | √2, π, e |
| `ℝ` | Reais | ℚ ∪ 𝕀 |
| `ℂ` | Complexos | 2 + 3i |

> [!important] Hierarquia de inclusão
> `ℕ ⊂ ℤ ⊂ ℚ ⊂ ℝ ⊂ ℂ`

---

## ✏️ Exercícios

> [!question] 1. Classifique cada número
> a) `−7`  
> b) `√9`  
> c) `√5`  
> d) `0,333...`  
> e) `π`

> [!success]- Resposta
> a) Inteiro (ℤ), Racional  
> b) Natural (ℕ) — pois `√9 = 3`  
> c) Irracional (𝕀)  
> d) Racional (ℚ) — dízima periódica  
> e) Irracional (𝕀)

> [!question] 2. Verdadeiro ou falso
> a) Todo natural é inteiro.  
> b) Todo inteiro é natural.  
> c) Todo racional é real.  
> d) Todo real é racional.

> [!success]- Resposta
> a) V  
> b) F (ex.: −3 é inteiro, mas não natural)  
> c) V  
> d) F (ex.: √2 é real, mas não racional)

> [!question] 3. Escreva na forma de fração
> a) `0,5`  
> b) `0,25`  
> c) `0,333...`

> [!success]- Resposta
> a) `1/2`  
> b) `1/4`  
> c) `1/3`

> [!question] 4. Determine a que conjuntos pertence o número `−5`
> (ℕ, ℤ, ℚ, ℝ)

> [!success]- Resposta
> Pertence a **ℤ, ℚ e ℝ**. **Não** pertence a ℕ.

> [!question] 5. Desafio
> O número `0,101001000100001...` é racional ou irracional?

> [!success]- Resposta
> **Irracional** — é uma dízima **não periódica**.

## 🔗 Links relacionados

- [[00 - Teoria dos Conjuntos]]
- [[Diagrama de Venn]]
- [[Matemática Básica]]
- [[Intervalos Reais]]
- [[01 - Noções Primitivas e Pertinência]]
- [[03 - Conjuntos Especiais - Unitário, Vazio e Universo]]