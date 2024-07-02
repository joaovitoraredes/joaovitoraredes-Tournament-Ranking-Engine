# Tournament-Ranking-Engine

Este projeto em Python realiza a análise de dados de jogos de futebol de diversas temporadas e ligas para montar a classificação final de cada temporada.

### Legenda do DataSet:

- Sea: Season / Temporada
- Lge: Liga / Campeonato
- Date: Data do jogo
- Ht: Hometeam, time mandante
- At: AwayTeam, time visitante
- Hs: Gols marcados pelo time mandante
- As: Gols marcados pelo time visitante
- Gd: Saldo de gols (Hs - As)
- WDL: Resultado da partida na perspectiva do time mandante (W: Vitória, L: Derrota, D: Empate)
- Vitória vale 3 pontos, empate vale 1 ponto, derrota vale 0 pontos.

### Informações na Classificação:

A classificação final gerada inclui as seguintes informações para cada clube:

- **Clube**: Nome do clube
- **Pts**: Pontos totais acumulados
- **PJ**: Partidas jogadas
- **V**: Vitórias
- **E**: Empates
- **D**: Derrotas
- **GM**: Gols marcados
- **GC**: Gols sofridos
- **SG**: Saldo de gols (GM - GC)

### Como Usar:

1. **Instalação:**

   Clone o repositório:

   ```
   git clone https://github.com/seu-usuario/Tournament-Ranking-Engine.git
   ```
   
   Instale as dependências:

   ```
   pip install -r requirements.txt
   ```
   
2. **Execução:**

   Execute o script principal:

   ```
   python tournament_ranking.py
   ```
   

### Exemplo de Uso:

Para entender como o projeto funciona na prática, você pode modificar o arquivo `tournament_ranking.py` para carregar seus dados específicos e adaptar o cálculo da classificação de acordo com as suas necessidades.