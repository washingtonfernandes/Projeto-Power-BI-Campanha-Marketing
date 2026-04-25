# Análise de campanhas de marketing - Business Intelligence

Este repositório contém um projeto de análise de dados estratégico focado em marketing analítico, desenvolvido durante o curso da **Data Science Academy (DSA)**. O objetivo é transformar dados demográficos e de consumo em inteligência de negócio para otimizar a eficácia de campanhas publicitárias.

## Origem do projeto
O projeto foi estruturado como um estudo de caso prático dentro da formação da **Data Science Academy**, aplicando conceitos de modelagem de dados, tratamento via Power Query e visualização estratégica.

## Visão geral da solução
A análise está organizada em quatro dimensões principais para uma compreensão 360° do negócio:
<img width="1152" height="668" alt="Lab04 - Campanha" src="https://github.com/user-attachments/assets/714088f4-5d59-4b90-b899-8390f097e4ba" />
<img width="1152" height="655" alt="Lab04 - Cliente" src="https://github.com/user-attachments/assets/66a38485-7ae0-4aa9-b9dc-a5f9765b2ea7" />
<img width="1152" height="653" alt="Lab04 - Comportamento" src="https://github.com/user-attachments/assets/ffad520a-2268-4607-bdb3-efe2ae46a55d" />
<img width="1152" height="661" alt="Lab04 - Pontos de Venda" src="https://github.com/user-attachments/assets/49a676c7-828e-468f-b98b-fdd7976da778" />

1.  **Performance das Campanhas**: Avaliação da conversão de vendas baseada em perfis familiares e demográficos.
2.  **Visão do Cliente**: Detalhamento do perfil do público-alvo, incluindo canais de compra (Loja, Web, Catálogo) e nível educacional.
3.  **Comportamento de Gasto**: Análise da correlação entre renda, escolaridade e presença de dependentes no volume de compras.
4.  **Pontos de Venda (PDV)**: Monitoramento geográfico e temporal da evolução dos gastos por país.

## Insights
A análise permitiu identificar padrões comportamentais críticos para a tomada de decisão:

* **Composição familiar**: Existe uma tendência clara de maior aceitação da campanha em clientes que não possuem filhos em casa, apresentando uma queda brusca de conversão conforme o número de dependentes aumenta.
* **Correlação renda vs. gasto**: Observa-se que o volume total de gastos cresce de forma proporcional ao salário anual dos clientes.
* **Perfil de maior valor**: Segmentos de clientes solteiros e com nível superior de ensino destacam-se como os principais impulsionadores de receita no modelo de decomposição de gastos.
* **Influência de dependentes no lar**: O gasto total das famílias tende a reduzir significativamente em lares com maior presença de adolescentes.
* **Dominância de canais**: Embora os canais digitais e de catálogo sejam relevantes, as compras realizadas diretamente nas lojas físicas ainda representam a maior fatia do volume transacional.
* **Expansão geográfica**: O mercado dos Estados Unidos lidera o volume de gastos, com crescimento constante ao longo da série histórica (2018-2023), seguido por mercados europeus como Espanha e Portugal.

## 🛠️ Tecnologias Utilizadas
* **Power BI Desktop**: Para modelagem e criação dos dashboards interativos.
* **DAX (Data Analysis Expressions)**: Para criação de medidas de performance e KPIs.
* **Power Query**: Para limpeza, transformação e normalização dos dados brutos.
