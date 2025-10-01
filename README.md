# Análise de Acidentes Rodoviários em Minas Gerais (2020)

## Sobre o Projeto
Este projeto consiste em uma **análise exploratória detalhada** dos dados de acidentes rodoviários ocorridos no estado de Minas Gerais durante o ano de 2020.  
O objetivo principal é identificar **padrões, causas e pontos críticos** para fornecer insights que possam contribuir para a segurança viária.  

A análise foi desenvolvida como um teste prático para a **EstatMG**.

---

## Objetivos da Análise
Conforme a solicitação do cliente, os principais objetivos deste trabalho foram:

- Avaliar as principais causas de acidentes nas rodovias de Minas Gerais.  
- Realizar um mapeamento dos tipos de acidentes e das rodovias com maior incidência.  
- Analisar a distribuição dos acidentes de acordo com variáveis de tempo, como **mês** e **dia da semana**.  

---

## Conjunto de Dados
O dataset utilizado, **`Acidentes_2020.xlsx`**, contém registros de acidentes de 2020 e inclui as seguintes informações:

- **Onde e Quando**: Município, BR, KM, data, dia da semana, horário e coordenadas geográficas (latitude/longitude).  
- **Como Aconteceu**: Tipo de acidente, fase do dia, condição meteorológica e tipo de pista.  
- **Impacto do Acidente**: Número de pessoas, mortos, feridos (graves e leves), ilesos e veículos envolvidos.  

---

## Tecnologias Utilizadas

- **Linguagem de Programação**: R  
- **Ambiente de Desenvolvimento**: RStudio  

### Principais Pacotes (Bibliotecas):
- `tidyverse`: Manipulação e visualização de dados (inclui `ggplot2` e `dplyr`).  
- `readxl`: Importação de arquivos `.xlsx`.  
- `reactable`: Criação de tabelas interativas e elegantes.  
- `leaflet`: Geração de mapas interativos.  
- `ggcorrplot`: Visualização de matrizes de correlação.  
- `lubridate` e `hms`: Manipulação de datas e horários.  
- `quarto` e `overleaf`: Criação do relatório final.  
