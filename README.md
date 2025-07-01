# Análise da Infraestrutura Escolar no Brasil (Censo Escolar 2024)

Este repositório contém um projeto de análise de dados realizado com base nos microdados do **Censo Escolar 2024 (INEP)**, com o objetivo de explorar e visualizar a infraestrutura das escolas brasileiras.

## Objetivo

Este trabalho foi desenvolvido como exercício prático de **tratamento e análise de dados com Python**, utilizando o Jupyter Notebook como ambiente interativo.

O foco está em responder questões como:

- As escolas brasileiras possuem acesso a água potável?
- Quais têm biblioteca, laboratórios ou quadras esportivas?
- Existem diferenças entre redes (municipal, estadual, federal, privada)?
- Como está a acessibilidade nas instituições de ensino?

## Estrutura do projeto

- `Infra_edu.ipynb`: Notebook principal com toda a análise, gráficos e interpretações.
- `microdados_ed_basica_2024.csv`: Arquivo original de dados (Censo Escolar).
- `README.md`: Este arquivo de apresentação do projeto.

## Sobre os dados

Devido ao tamanho do arquivo original do Censo Escolar 2024 (INEP), ele não está incluído diretamente neste repositório.

Contudo, o notebook está configurado para **baixar automaticamente o dataset original** do Google Drive utilizando a biblioteca `gdown`. Isso garante a reprodutibilidade da análise sem exigir upload manual por parte do usuário.

Se preferir baixar manualmente, os dados podem ser obtidos diretamente no site oficial do INEP.

## Bibliotecas utilizadas

- `Pandas`
- `Matplotlib`
- `Seaborn`
- `Numpy`
- `Gdown`

## Destaques da análise

- Comparações entre tipos de rede e regiões.
- Porcentagens de escolas com recursos básicos.
- Visualizações diversas (gráficos de barras, roscas, mapas de calor).
- Análises críticas sobre acessibilidade e desigualdade educacional.

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
