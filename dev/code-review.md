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
3. SOLID: cada classe tem uma razão para mudar? aberta para extensão? subclasses substituem a base? interfaces coesas? dependências abstratas?
4. DRY: lógica duplicada? constantes repetidas? abstração ausente?
5. Clean Code: nomes revelam intenção? funções fazem uma coisa só? sem side effects ocultos? sem null desnecessário? Lei de Demeter respeitada?
6. Object Calisthenics: um nível de indentação por função? sem else? sem primitivos expostos (wrap types)? coleções em classes próprias? sem getters/setters?
7. Fail Fast: entradas validadas no início? falhas explícitas e imediatas?
8. O que está bem e não precisa mudar

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
