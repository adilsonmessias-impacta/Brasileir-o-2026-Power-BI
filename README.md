# Dashboard Analítico de Futebol (Power BI & REST API)

## Descrição do Projeto

Este projeto consiste no desenvolvimento de um **Dashboard Interativo no Power BI** consumindo dados em tempo real da API pública [football-data.org](https://www.football-data.org/). O objetivo principal é realizar análises profundas sobre o Campeonato Brasileiro (Série A), demonstrando habilidades em extração de dados via web, tratamento complexo com Power Query (Linguagem M), modelagem de dados relacional e construção de métricas analíticas (DAX). 

## 🛠️ Tecnologias Utilizadas

- **Power BI:** Visualização de dados e Data Storytelling.
- **Power Query / Linguagem M:** Conexão com API (paginação, inserção de chaves no Header), remoção, limpeza e tipagem de JSON.
- **DAX:** Criação de medidas de desempenho e cálculos lógicos.
- **APIs REST:** Extração de dados ao vivo com autenticação via Token.

---

## Entregas do Projeto

### ✅ Entrega 1: Visão Geral e Interatividade (Concluída)

A primeira fase focou em estabelecer a infraestrutura de dados e a visão central do campeonato.
- **Bases Consumidas:** Endpoints de Classificação (`/standings`) e Partidas (`/matches`).
- **Funcionalidades:** 
  - Criação de uma Tabela de Classificação realista, com os escudos dos times renderizados dinamicamente via URL de imagem.
  - Lista de partidas do campeonato detalhando rodadas e resultados parciais/finais.
  - **Interatividade (Cross-Filtering):** O painel possui filtros cruzados onde, ao clicar no escudo/nome de um time na tabela de classificação, a lista de jogos é automaticamente filtrada para exibir apenas o histórico e os confrontos futuros daquela equipe.

### ⏳ Entrega 2: Evolução de Desempenho e Temporalidade (Planejada)

Nesta fase, o foco será analisar a progressão das equipes ao longo da temporada, introduzindo conceitos de inteligência de tempo e segmentação de dados.
- **Bases Consumidas:** Endpoint de Partidas (`/matches`), utilizando as colunas de data/hora e rodada para construção de um calendário analítico.
- **Funcionalidades Previstas:** 
  - **Evolução Temporal:** Gráficos (como linhas ou área) demonstrando a progressão de **pontos** e **gols** das equipes ao longo do campeonato.
  - **Cálculo de Aproveitamento:** Criação de métricas com DAX para medir a taxa de aproveitamento (percentual de pontos ganhos em relação aos disputados) de forma dinâmica.
  - **Filtros de Tempo Dinâmicos:** Implementação de segmentadores de dados por **Mês** e por **Rodada**, permitindo ao usuário "viajar no tempo" e analisar a performance e a tabela em recortes temporais específicos.

### ⏳ Entrega 3: Raio-X dos Elencos e Jogadores (Planejada)

Nesta etapa, o projeto elevará o nível de **Modelagem de Dados**, conectando diferentes tabelas através de Chaves Primárias (IDs).
- **Bases Consumidas:** Endpoints de Artilheiros/Estatísticas (`/scorers`) relacionado com a base de Elencos Completos (`/teams`).
- **Funcionalidades Previstas:** 
  - Relacionamento de tabelas 1:N usando o `ID do Jogador`.
  - Tabela visual com o Top Assistências, Artilheiros e jogadores com mais partidas.

### ⏳ Entrega 4: Visão Macro e Institucional do Campeonato (Planejada)

A entrega final consolida o dashboard com estatísticas gerais do torneio, sem focar em um indivíduo ou clube específico.
- **Bases Consumidas:** Endpoint do Cadastro de Clubes (`/matches`).
- **Funcionalidades Previstas:** 
  - Gráfico de sazonalidade mostrando a média de gols marcados por rodada ao longo do tempo.
  - Cards com indicadores chave gerais da temporada (Soma total de gols, Média de gols por jogo, Total de jogos).

---

> **Status do Projeto:** 🚧 Em desenvolvimento (Fase 1 de 4 concluída).
