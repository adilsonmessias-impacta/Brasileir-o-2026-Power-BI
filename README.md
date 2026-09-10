Entrega 1: Tabela de Classificação
Nesta etapa inicial, o foco é comprovar a extração de dados da API, o tratamento no Power Query e a criação da página de visão geral.

Base de Dados: Endpoint de Classificação (/standings).

Gráfico/Visual Principal: Matriz ou Tabela estruturada replicando a tabela real do campeonato de forma limpa.

Funcionalidade Nova: Inserção de Imagens Dinâmicas (Escudos) via URL e Formatação Condicional (cores de fundo para destacar zonas de classificação e de rebaixamento).

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
