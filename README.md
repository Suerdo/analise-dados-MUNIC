# Análise de Dados MUNIC

Este projeto contém análises baseadas nos dados do MUNIC (Pesquisa de Informações Básicas Municipais). Ele inclui:
- Visualizações de dados por região.
- Análises sobre recursos recebidos por diferentes esferas de governo.

## Estrutura do Projeto

- **`MUNIC_files/datasets`**: Contém os arquivos de dados originais.
- **`notebooks`**: Contém o notebook Jupyter com as análises.

## Pré-requisitos

- Python 3.9+
- Bibliotecas utilizadas:
  - `pandas`
  - `matplotlib`
  - `seaborn`

## Contexto da Análise

A análise foca na parte da pesquisa MUNIC relacionada aos **Serviços de Assistência Técnica e Extensão Rural** para agricultores familiares e povos de comunidades tradicionais (MSAN01). O objetivo é avaliar a distribuição dos recursos relacionados a esses serviços, considerando as diferentes esferas políticas (federal, estadual e municipal).

Será feita uma análise detalhada para compreender como os recursos são alocados em cada região e identificar padrões e diferenças na distribuição. Isso permite gerar insights importantes para políticas públicas e iniciativas que visem melhorar a assistência aos agricultores e comunidades tradicionais.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Suerdo/analise-dados-MUNIC.git
2. Navegue até o diretório do projeto:
   ```bash
   cd analise-dados-MUNIC
3. Abra e execute os notebooks Jupyter no diretório notebooks/:
   ```bash
   jupyter notebook MUNIC_files/notebooks/analise_municipios.ipynb
