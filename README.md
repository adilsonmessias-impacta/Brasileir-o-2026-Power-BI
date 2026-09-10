Entrega 1: Tabela de Classificação e de Jogos

Gráfico/Visual Principal: Tabela de Classificação do Campeonato e de Jogos

Funcionalidade: Tabela de classificação com visual de zonas de classificações e rebaixamento, e tabela de próximos jogos e jogos já finalizados com interação com a tabela de classificação onde ao clicar em um time será filtrados somente os jogos desse time.

Entrega 2: Análise dos Times
Aqui, você expande o modelo trazendo o histórico de jogos e focando exclusivamente na performance das equipes.

Base de Dados: Endpoint de Partidas (/matches).

Gráfico/Visual Principal: Gráfico de Barras Empilhadas detalhando a proporção de gols marcados no 1º Tempo versus 2º Tempo para cada time.

Funcionalidade Nova: Criação de Medidas DAX para análise tática, como o cálculo do "Fator Casa" (taxa de vitórias como mandante) e um Segmentador de Dados (Filtro) por clube.

Entrega 3: Análise dos Jogadores
A complexidade aumenta ao isolar estatísticas individuais, respondendo quem são os grandes talentos da temporada.

Base de Dados: Endpoint de Artilheiros (/scorers).

Gráfico/Visual Principal: Gráfico de Dispersão cruzando Idade do jogador com a quantidade de Gols ou Assistências, revelando jovens promessas e veteranos eficazes.

Funcionalidade Nova: Construção de um Tooltip (Dica de Ferramenta) customizado. Ao passar o mouse sobre o gráfico, um mini-painel flutuante revela a posição e a nacionalidade do atleta.

Entrega 4: Raio-X do Campeonato
A entrega final consolida o projeto com uma visão macro e institucional do evento, sem focar em um clube ou jogador específico.

Base de Dados: Endpoint de Clubes (/teams) relacionado com a tabela de Partidas.

Gráfico/Visual Principal: Gráfico de Linhas exibindo a sazonalidade e a média de gols por rodada ao longo do calendário.

Funcionalidade Nova: Gráfico de Árvore (Treemap) e Rosca mapeando o volume de partidas por Estádio e a porcentagem global de resultados (Vitórias de Mandantes vs. Visitantes vs. Empates).
