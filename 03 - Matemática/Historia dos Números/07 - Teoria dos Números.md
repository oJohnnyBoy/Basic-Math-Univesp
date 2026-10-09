---
título: Teoria dos Números
tema: História dos Números
tags:
  - matemática
  - história-da-matemática
  - teoria-dos-números
  - números-primos
  - criptografia
---

# 07 — Teoria dos Números

> [!abstract] Definição
> Ramo da matemática que estuda as **propriedades dos números inteiros**, especialmente **números primos**, divisibilidade, paridade e estrutura dos conjuntos numéricos.

## 1. Origem histórica

- Fomentada nos séculos **XVI–XVII**
- **Pierre de Fermat** — nome central
- Os **"Problemas de Fermat"** ainda são estudados hoje

## 2. Objeto de estudo

- Estrutura de **números pares** e **ímpares**
- Propriedades dos **números primos**
- Divisibilidade e fatoração

## 3. Números primos

> [!important] Definição
> Números que **não podem ser decompostos** em produto de outros números naturais (exceto 1 e ele mesmo).

**Exemplos:** `2, 3, 5, 7, 11, 13, 17, 19, ...`

- Todo número natural > 1 pode ser **decomposto em fatores primos** (Teorema Fundamental da Aritmética).
- Essa unicidade é **base da criptografia moderna**.

## 4. Aplicação: criptografia

- Sistemas como **RSA** baseiam-se em números primos grandes
- Chaves criptográficas = produto de primos
- Dificuldade de **fatorar** números grandes → segurança

> [!tip] Por que funciona?
> Encontrar dois primos grandes é fácil. **Multiplicá-los** também. Mas **fatorar** o resultado de volta é computacionalmente inviável para primos gigantes.

## 5. Conexão com a disciplina

- A Teoria dos Números aparece em várias disciplinas do curso
- Base para **Teoria dos Conjuntos** e **Álgebra**

---

---

## 🖼️ Exemplos visuais

![[mat-crivo-primos.svg]]

*Crivo de Eratóstenes até 50 e as fatorações pedidas nos exercícios.*

## ✏️ Exercícios

> [!question] 1. Liste os 10 primeiros números primos

> [!success]- Resposta
> `2, 3, 5, 7, 11, 13, 17, 19, 23, 29`

> [!question] 2. Decomponha em fatores primos
> a) 36  
> b) 60  
> c) 100

> [!success]- Resposta
> a) `36 = 2² · 3²`  
> b) `60 = 2² · 3 · 5`  
> c) `100 = 2² · 5²`

> [!question] 3. Explique
> Por que números primos são importantes para a criptografia?

> [!success]- Resposta sugerida
> Porque a **fatoração de números muito grandes** em primos é computacionalmente difícil. Isso permite criar **chaves seguras**: multiplicar dois primos é fácil, mas descobri-los a partir do produto é inviável na prática.

> [!question] 4. Verdadeiro ou falso
> a) Todo número ímpar é primo.  
> b) 1 é primo.  
> c) 2 é o único primo par.

> [!success]- Resposta
> a) **F** (ex.: 9 = 3·3)  
> b) **F** — 1 não é primo por convenção  
> c) **V**

> [!question] 5. Desafio
> Em que áreas práticas a Teoria dos Números é usada?

> [!success]- Resposta sugerida
> Criptografia (RSA, HTTPS), segurança de dados bancários, assinaturas digitais, códigos de correção de erros, hashing, entre outros.