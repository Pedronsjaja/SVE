---
name: sve-testes-de-bancada
description: Define e executa casos de teste sobre arquivos sintéticos do SVE.
---

# sve-testes-de-bancada

Use arquivos locais ou dados sintéticos em demonstrações de bancada. O exemplo do repositório está em `examples/telemetria-sintetica.csv`.

1. Comece com o CSV original e prepare uma cópia por cenário: pausa, duplicata, linha inválida e linha fora de ordem.
2. Defina para cada caso a entrada, o resultado esperado e o critério de aprovação. Confira se o gráfico distingue lacuna de valor zero e se a entrada inválida é sinalizada.
3. Registre resultado observado para testes executados e marque explicitamente casos ainda pendentes.
