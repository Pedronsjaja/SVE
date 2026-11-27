---
name: sve-replay-e-analise
description: Reabre sessões locais e produz gráficos e resumos de telemetria registrada.
---

# sve-replay-e-analise

Use arquivos locais ou dados sintéticos em demonstrações de bancada. O exemplo do repositório está em `examples/telemetria-sintetica.csv`.

1. Leia o arquivo, valide unidades e preserve a identificação da origem dos dados.
2. Mostre o maior valor registrado, seu instante e os intervalos com amostras faltantes segundo a cadência declarada. Evite inferir o que ocorreu dentro da lacuna.
3. Se houver um CSV de simulação já fornecido, identifique as duas séries e confirme a referência de tempo e altitude antes de sobrepô-las.
