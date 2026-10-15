# analise-comercio-brasil-china
Dashboard interativo em Power BI sobre 23 anos de comércio entre Brasil e China (2002-2025), com dados do Comex Stat, mostrando a evolução de exportações e exportações e as categorias de produtos que dominam a relação.
# Comércio Brasil-China (2003-2025): Dashboard em Power BI
![Visão Geral](visao-geral.png)
![Dados Detalhados](dados-detalhados.png)

## Perguntas que o projeto responde

- Como exportações e importações evoluíram entre 2003 e 2025?
- O Brasil tem superávit ou déficit comercial com a China?
- Quais categorias de produto mais pesam na relação, e em qual direção (venda ou compra)?

## O que há no dashboard

**Visão Geral**
- Top 10 categorias de produto (capítulos do Sistema Harmonizado) por valor comercializado, separadas por exportação e importação
- Evolução anual de exportações e importações
- Filtro de intervalo de anos

**Dados Detalhados**
- Tabela com exportação, importação e total por ano
- Participação de exportação e importação no comércio total
- Resumo dos principais resultados

## Principais resultados

- Entre 2003 e 2025, o Brasil exportou cerca de US$ 1,07 trilhão para a China e importou cerca de US$ 719 bilhões
- O Brasil teve superávit em 21 dos 23 anos analisados (2007 e 2008 foram os anos de déficit)
- As exportações atingiram o pico em 2023, acima de US$ 104 bilhões
- As exportações cresceram cerca de 22 vezes no período, e as importações cerca de 33 vezes
- O Brasil vende principalmente produtos primários (soja e outros grãos oleaginosos, minérios, combustíveis minerais, carnes) e compra principalmente produtos industrializados (máquinas, equipamentos elétricos e mecânicos, químicos orgânicos, veículos)

## Conclusões

A evolução do comércio entre Brasil e China evidencia a crescente importância da relação bilateral para a economia brasileira. Embora o aumento das exportações represente uma oportunidade estratégica, a concentração da pauta exportadora em produtos primários e de menor valor agregado, em contraste com a importação de bens industrializados e insumos de maior complexidade tecnológica, suscita questões sobre a inserção internacional do Brasil e sua posição nas cadeias globais de valor.

Nesse contexto, este projeto analisa a evolução dos fluxos comerciais entre os dois países, explorando tendências de exportação e importação, a composição da pauta comercial e a dinâmica do saldo bilateral entre 2003 e 2025. A partir da visualização e interpretação dos dados, busca-se contribuir para a compreensão dos desafios associados à diversificação produtiva, à agregação de valor e à competitividade da economia brasileira no cenário internacional.

## Fonte de dados

[Comex Stat](https://comexstat.mdic.gov.br/), do Ministério do Desenvolvimento, Indústria, Comércio e Serviços (MDIC). Valores em US$ FOB, consulta por país (China) e capítulo do Sistema Harmonizado (SH2).

## Ferramentas

Power BI Desktop (Power Query e DAX)

## Limitações

- Valores nominais em dólares, sem correção pela inflação
- A análise é bilateral e não considera o comércio do Brasil com outros países
- As categorias estão agregadas no nível de capítulo (SH2), o que esconde diferenças entre produtos dentro de cada capítulo
- O gráfico de Top 10 soma exportação e importação para ordenar as categorias
