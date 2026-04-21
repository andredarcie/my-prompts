---
layout: default
title: Clean Code Review
---

# Clean Code Review

Análise de PR com base nos princípios do Clean Code.

```text
Analise o PR abaixo com base nos princípios do Clean Code:

**Nomes:** revelam intenção? sem abreviações ou ruído?
**Funções:** fazem uma coisa só? pequenas? sem side effects ocultos? sem flag arguments?
**Comentários:** o código se explica sozinho? comentários justificam apenas o WHY não óbvio?
**Objetos:** Lei de Demeter respeitada? internals encapsulados?
**Erros:** sem retorno de null? exceções com contexto?
**Testes:** independentes? um conceito por teste? legíveis como especificação?

Liste os problemas encontrados ordenados por impacto:

| # | Gravidade | Princípio violado | Comentário | Justificativa |
|---|-----------|-------------------|------------|---------------|
| 1 | 🔴 Crítico | ... | ... | ... |
| 2 | 🟠 Alto    | ... | ... | ... |
| 3 | 🟡 Médio   | ... | ... | ... |
| 4 | 🔵 Baixo   | ... | ... | ... |

[COLE O DIFF OU CÓDIGO AQUI]
```
