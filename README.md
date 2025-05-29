# Projeto SAD 2024/2025 — Previsão de Procura de Bicicletas com Clima

Este projeto foi desenvolvido no âmbito da unidade curricular de Sistemas de Apoio à Decisão, do curso de Informática de Gestão, com o objetivo de prever a procura por bicicletas partilhadas em cidades urbanas com base em dados meteorológicos. A solução foi construída com a linguagem R, utilizando técnicas de regressão e visualização interativa através de R Shiny.

---

## 🔍 Objetivo

O principal objetivo é ajudar operadores e decisores urbanos a planear a alocação de bicicletas com base nas previsões meteorológicas, contribuindo para uma gestão mais eficiente da mobilidade urbana.

---

## 📦 Estrutura do Projeto

Este projeto está organizado da seguinte forma:

- `data/raw/` – Dados recolhidos de fontes públicas (API OpenWeather, Wikipédia, datasets CSV)
- `data/clean/` – Dados tratados e prontos para análise e modelação
- `scripts/` – Scripts R para:
  - carregar dados
  - limpar dados
  - análise exploratória (EDA)
  - construção e avaliação de modelos
- `shiny_app/` – Aplicação interativa desenvolvida em R Shiny com previsões por cidade
- `report/` – Contém o relatório final e os slides da apresentação
- `video/` – Apresentação gravada com explicação do projeto e demonstração da aplicação

---

## 📈 Técnicas utilizadas

- 📊 **Análise de Dados**: `tidyverse`, `dplyr`, `ggplot2`, `stringr`, `janitor`
- 🧠 **Modelação**: `Tidymodels`, regressão linear simples e múltipla
- 🌐 **APIs e Web Scraping**: `httr`, `jsonlite`, `rvest`, `xml2`
- 🗺️ **Visualização Interativa**: `R Shiny`, `leaflet`
- 🛠️ **Qualidade e preparação dos dados**: tratamento de nulos, normalização, criação de variáveis dummy

---

## 👨‍💻 Como executar

Para executar este projeto localmente, segue os seguintes passos:

1. Instala os pacotes necessários no R (caso ainda não tenhas):

```r
install.packages("tidyverse")
install.packages("shiny")
install.packages("readr")
install.packages("rvest")
install.packages("leaflet")
install.packages("janitor")
install.packages("jsonlite")
install.packages("httr")
install.packages("tidymodels")
