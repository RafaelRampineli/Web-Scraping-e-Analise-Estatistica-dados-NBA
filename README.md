# Web-Scraping-e-Analise-Estatistica-dados-NBA

Laboratório 3 desenvolvido ao final do curso Bônus Web Scraping da Formação Cientista de Dados da Data Science Academy (DSA).

## Definição do Problema

A Ciência de Dados está em todos os lugares. Se há dados disponíveis, podemos extrair, analisar e gerar insights poderosos. E no esporte não seria diferente.

Cada vez mais gestores de todos os esportes descobrem os benefícios e vantagem competitiva em usar análise de dados para compreender o comportamento dos atletas, melhorar o desempenho, unir atletas com características complementares no mesmo time e muito mais.

Neste Laboratório, vamos extrair dados reais de atletas da NBA - a Liga de Basquete Norte Americana - e analisar os dados.

## Fonte de Dados

Nossa fonte de dados será o site <a href="https://www.basketball-reference.com">Bastketball Reference</a> que mantém todos os detalhes e estatísticas sobre a NBA.


**Dicionário de Dados** (conforme mostrado na fonte de dados):

- Rk -- Rank
- Pos -- Position
- Age -- Player's age on February 1 of the season
- Tm -- Team
- G -- Games
- GS -- Games Started
- MP -- Minutes Played Per Game
- FG -- Field Goals Per Game
- FGA -- Field Goal Attempts Per Game
- FG% -- Field Goal Percentage
- 3P -- 3-Point Field Goals Per Game
- 3PA -- 3-Point Field Goal Attempts Per Game
- 3P% -- 3-Point Field Goal Percentage
- 2P -- 2-Point Field Goals Per Game
- 2PA -- 2-Point Field Goal Attempts Per Game
- 2P% -- 2-Point Field Goal Percentage
- eFG% -- Effective Field Goal Percentage

This statistic adjusts for the fact that a 3-point field goal is worth one more point than a 2-point field goal.

- FT -- Free Throws Per Game
- FTA -- Free Throw Attempts Per Game
- FT% -- Free Throw Percentage
- ORB -- Offensive Rebounds Per Game
- DRB -- Defensive Rebounds Per Game
- TRB -- Total Rebounds Per Game
- AST -- Assists Per Game
- STL -- Steals Per Game
- BLK -- Blocks Per Game
- TOV -- Turnovers Per Game
- PF -- Personal Fouls Per Game
- PTS -- Points Per Game

# TO DO:

- Criar um modelo de regressão linear baseado em cada partida jogada por cada jogador. A ideia é ser capaz de fazer uma previsão de rebotes Ofensivos de cada jogador em determinado ponto do jogo (momento/hora).
