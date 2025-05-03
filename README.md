# Análise de Dados: Impacto da Frequência de Faxinas na Satisfação dos Moradores

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue.svg)](https://github.com/llealdev)


## Visão Geral

Este projeto apresenta uma análise detalhada dos dados de limpeza de apartamentos ao longo do ano de 2020, com o objetivo de avaliar a relação entre a frequência de faxinas, o número de moradores, os custos envolvidos e a satisfação dos moradores (medida pela nota de limpeza). O trabalho foi desenvolvido como parte de um teste técnico para uma vaga de estágio em dados, buscando responder se a contratação de mais faxineiras é necessária para melhorar a satisfação ou se existem alternativas para otimizar os recursos atuais.

Os dados incluem informações mensais sobre o número de moradores, quartos, notas de limpeza, custos com faxinas e a equipe responsável pelas limpezas. A análise foi realizada utilizando Python, com bibliotecas como Pandas, Matplotlib e Seaborn, e está documentada em um Jupyter Notebook.

## Objetivos da Análise

- Avaliar a relação entre a frequência de faxinas e a satisfação dos moradores.
- Identificar se a redução na frequência de faxinas está correlacionada com a queda nas notas de limpeza.
- Analisar os custos associados às faxinas em relação ao número de moradores e à satisfação.
- Estimar a necessidade de contratações adicionais ou redistribuição de faxinas para atingir uma meta de frequência.
- Fornecer recomendações baseadas em dados para equilibrar satisfação e impacto financeiro.

## Principais Resultados

- **Evolução da Satisfação**: A nota de limpeza caiu de valores acima de 4 em janeiro para abaixo de 3 a partir de setembro de 2020, coincidindo com o aumento de moradores (de 8 para 182) e a redução de faxinas por morador (de 3.88 para 1.81).
- **Correlação Forte**: Uma correlação de 0.94 foi identificada entre "Faxinas por Morador" e "Nota de Limpeza", indicando que mais faxinas por pessoa aumentam a satisfação.
- **Meses Críticos**: De setembro a dezembro, as notas ficaram abaixo de 3, com o menor valor em dezembro (2.69), mesmo com aumento no total de faxinas.
- **Custo por Morador**: O custo por morador diminuiu (de R$540 para R$208), mas a satisfação foi impactada negativamente.
- **Necessidade de Faxineiros**: Para atingir a meta de 3 faxinas por morador, até 7 faxineiros adicionais são necessários em dezembro (déficit de 216 faxinas).
- **Redistribuição de Faxinas**: O excesso de faxinas nos primeiros meses (22) não cobre o déficit total (674), tornando a redistribuição insuficiente.

## Recomendações para o Time de Finanças

- **Contexto Pandêmico**: Considerar que a demanda por limpeza em 2020 pode ser temporariamente maior devido ao isolamento social. Avaliar se o crescimento de moradores é uma tendência de longo prazo.
- **Contratação Temporária ou Freelance**: Contratar temporariamente 3 a 7 faxineiras na modalidade freelance ou por demanda, especialmente nos meses críticos (setembro a dezembro), pagando apenas pelas faxinas realizadas ou por contratos de curta duração.
- **Metas de Faxinas por Morador**: Estabelecer uma meta de 3 faxinas por morador por mês, já que a satisfação não aumenta significativamente acima disso.
- **Redistribuição de Faxinas**: Ajustar a alocação de faxinas dos meses com excesso para os críticos, combinando com contratações temporárias para otimizar custos.
- **Otimização de Custos**: Aumentar controladamente o orçamento para faxinas (mantendo o custo por faxina entre R$115 e R$140) para melhorar a satisfação sem grande impacto financeiro.
- **Campanhas de Conscientização**: Promover ações educativas com moradores para reduzir a demanda por limpeza (ex.: regras de uso de áreas comuns).

## Contato

Para dúvidas ou sugestões, entre em contato:
- **Nome**: Matheus Leal
- **Email**: lleal.dev@gmail.com
- **LinkedIn**: [Matheus Leal](https://www.linkedin.com/in/llealdev/)
