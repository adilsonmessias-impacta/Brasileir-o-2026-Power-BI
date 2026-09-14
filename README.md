⚽ Dashboard Analítico de Futebol (Power BI & REST API)
📖 Descrição do Projeto
Este projeto consiste no desenvolvimento de um Dashboard Interativo no Power BI consumindo dados em tempo real da API pública football-data.org. O objetivo principal é realizar análises profundas sobre o Campeonato Brasileiro (Série A), demonstrando habilidades em extração de dados via web, tratamento complexo com Power Query (Linguagem M), modelagem de dados relacional e construção de métricas analíticas (DAX).

O projeto foi planejado metodicamente para ser desenvolvido e avaliado em 4 entregas progressivas, adicionando camadas de complexidade analítica a cada fase.

🛠️ Tecnologias Utilizadas
Power BI: Visualização de dados e Data Storytelling.

Power Query / Linguagem M: Conexão com API (paginação, inserção de chaves no Header), extração, limpeza e tipagem de JSON.

DAX: Criação de medidas de performance e cálculos lógicos.

APIs REST: Extração de dados ao vivo com autenticação via Token.

🚀 Entregas do Projeto (Roadmap)
✅ Entrega 1: Visão Geral e Interatividade (Concluída)
A primeira fase focou em estabelecer a infraestrutura de dados e a visão central do campeonato.

Bases Consumidas: Endpoints de Classificação (/standings) e Partidas (/matches).

Funcionalidades:

Criação de uma Tabela de Classificação realista, com os escudos dos times renderizados dinamicamente via URL de imagem.

Lista de partidas do campeonato detalhando rodadas e resultados parciais/finais.

Interatividade (Cross-Filtering): O painel possui filtros cruzados onde, ao clicar no escudo/nome de um time na tabela de classificação, a lista de jogos é automaticamente filtrada para exibir apenas o histórico e os confrontos futuros daquela equipe.

⏳ Entrega 2: Análise de Desempenho dos Times (Planejada)
Aprofundamento nas estatísticas táticas para entender como e onde as equipes pontuam.

Bases Consumidas: Endpoint de Partidas (/matches) com separação de tempos.

Funcionalidades Previstas:

Análise de "Fator Casa": Medidas DAX comparando o aproveitamento e vitórias como Mandante vs. Visitante.

Gols por Tempo de Jogo: Gráficos mostrando a proporção de gols marcados no 1º Tempo vs. 2º Tempo para identificar equipes com melhor preparo físico/foco nas etapas finais.

⏳ Entrega 3: Raio-X dos Elencos e Jogadores (Planejada)
Nesta etapa, o projeto elevará o nível de Modelagem de Dados, conectando diferentes tabelas através de Chaves Primárias (IDs).

Bases Consumidas: Endpoints de Artilheiros/Estatísticas (/scorers) relacionado com a base de Elencos Completos (/teams).

Funcionalidades Previstas:

Relacionamento de tabelas 1:N usando o ID do Jogador.

Tabela visual com o Top Assistências ("Garçons") e Artilheiros.

Análise demográfica do campeonato cruzando a Idade (calculada a partir da data de nascimento) vs. Desempenho, além de distribuição por Posição e Nacionalidade.

⏳ Entrega 4: Visão Macro e Institucional do Campeonato (Planejada)
A entrega final consolida o dashboard com estatísticas gerais do torneio, sem focar em um indivíduo ou clube específico.

Bases Consumidas: Endpoint do Cadastro de Clubes (/teams).

Funcionalidades Previstas:

Gráfico de sazonalidade mostrando a média de gols marcados por rodada ao longo do tempo.

Filtro e análise de volume de partidas/resultados por Estádio.

Cards com indicadores chave gerais da temporada (Soma total de gols, Média de gols por jogo, Total de cartões/jogos).

Status do Projeto: 🚧 Em desenvolvimento (Fase 1 de 4 concluída).
