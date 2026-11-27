---
name: sve-contrato-de-dados
description: Documenta campos e valida arquivos sintéticos de telemetria para exercícios da URASpace.
---

# sve-contrato-de-dados

Use arquivos locais ou dados sintéticos em demonstrações de bancada. O exemplo do repositório está em `examples/telemetria-sintetica.csv`.

1. Leia o cabeçalho e confira se tempo e altitude são numéricos e finitos.
2. Declare a unidade e a origem de cada campo. Use segundos desde o início da sessão e metros em relação ao zero da sessão para o CSV de exemplo.
3. Liste linhas inválidas, duplicadas e fora de ordem. Preserve o arquivo recebido e indique qualquer interpretação necessária em uma tabela de validação.
