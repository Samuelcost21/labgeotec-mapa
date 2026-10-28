# LABGEOTEC — Municípios e Projetos

Mapa interativo dos municípios onde o LABGEOTEC (Laboratório de Geotecnologias – UFAM) atua, com os projetos de cada um e o andamento do trabalho.

## Como editar os dados

Abra `index.html` e procure, no início do script:

- `PROJETOS` — nome, resumo, descrição, parceiros, cor e link de cada projeto (`papelLab` descreve o papel do laboratório).
- `MUNICIPIOS` — nome, UF, código IBGE, coordenadas e `andamento` (% concluído) em cada projeto.
- `DADOS_DE_EXEMPLO` — mude para `false` quando os percentuais forem reais.

## Publicação

Publicado com GitHub Pages (Settings → Pages → branch `main`, pasta `/`).
Os limites municipais são carregados da API de malhas do IBGE; o mapa base é © OpenStreetMap / CARTO.
