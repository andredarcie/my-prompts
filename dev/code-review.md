---
layout: default
title: Code Review
---

# Code Review

Revisão crítica e objetiva de código.

```text
Revise o código abaixo considerando:
1. Bugs ou edge cases não tratados
2. Problemas de performance ou segurança
3. Violações de SOLID ou princípios de design
4. Clean Code: nomes revelam intenção? funções fazem uma coisa só? sem side effects ocultos? sem null desnecessário? Lei de Demeter respeitada?
5. Object Calisthenics: um nível de indentação por função? sem else? sem primitivos expostos (wrap types)? coleções em classes próprias? sem getters/setters?
6. O que está bem e não precisa mudar

Seja direto. Sem elogios genéricos.

Ao final, liste todos os comentários ordenados do mais para o menos importante:

| # | Gravidade | Princípio | Comentário | Justificativa |
|---|-----------|-----------|------------|---------------|
| 1 | 🔴 Crítico | ... | ... | ... |
| 2 | 🟠 Alto    | ... | ... | ... |
| 3 | 🟡 Médio   | ... | ... | ... |
| 4 | 🔵 Baixo   | ... | ... | ... |

Gravidades: 🔴 Crítico (bug/segurança), 🟠 Alto (design/SOLID), 🟡 Médio (Clean Code/manutenção), 🔵 Baixo (estilo/sugestão).

[COLE O CÓDIGO AQUI]
```
