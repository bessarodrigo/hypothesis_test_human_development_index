# Teste de Hipóteses - Índice de Desenvolvimento Humano
## Testes de Hipóteses | Média e Variância de duas populações

# Problema de Negócio
A Secretaria da Educação solicitou a análise do IDHM Educação por região para avaliar se a diferença no índice, observada entre as regiões, é estatisticamente significante. Para isso, consolidou a base de dados das 3 principais regiões a serem avaliadas: Norte, Nordeste e Sul com uma amostra de seus municípios.

Este trabalho consiste em 3 tarefas principais:
- Construir histogramas para cada região e avaliar se as distribuições se aproximam da Normal
- Calcular as medidas resumo por região: número de observações, média e desvio padrão
- Realizar um Teste de Hipóteses para comparar se a média do IDHM Educação é diferente entre as regiões: Nordeste e Sul e Norte e Nordeste

Para cada Teste de Hipóteses, serão realizados os seguintes passos:
- Formular as hipóteses a serem testadas
- Avaliar se as variâncias do IDHM entre as regiões podem ser consideradas iguais para selecionar o teste mais adequado
- Calcular o p-valor
- Interpretar o resultado do teste considerando um coeficiente de confiança de 5%

# Hipóteses
**Nordeste x Sul**
- H0: A média do IDHM Educação do Nordeste é igual à média IDHM do Sul, ou: IDHMn = IDHMs
- H1: A média do IDHM Educação do Nordeste é menor do que a média IDHM do Sul, ou: IDHMn < IDHMs
  
**Nordeste x Norte**
- H0: A média do IDHM Educação do Nordeste é igual à média IDHM do Norte, ou: IDHMnordeste = IDHMnorte
- H1: A média do IDHM Educação do Nordeste é diferente da média IDHM do Norte, ou: IDHMnordeste < IDHMnorte

# Resultado
**Nordeste x Sul**
Como o p-valor é menor que 5%, rejeitamos H0. Então existem evidências estatísticas que o IDHM do Nordeste é menor que o do Sul.

**Nordeste x Norte**
Como o p-valor é maior que 5%, não rejeitamos H0. Não existem evidências estatísticas que o IDHM do Norte é maior que o IDHM do Nordeste.
