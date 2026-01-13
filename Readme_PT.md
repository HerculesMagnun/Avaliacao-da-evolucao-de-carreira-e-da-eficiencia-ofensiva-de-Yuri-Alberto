# Yuri Alberto — Análise de Performance de Carreira ⚽📊

## Visão Geral do Projeto
Este projeto tem como objetivo analisar a **carreira profissional de Yuri Alberto**, utilizando análise de dados esportivos para simular um cenário real de **avaliação de jogadores para scouting e recrutamento**.

O foco principal é compreender a evolução da performance do atleta ao longo das temporadas, especialmente no que diz respeito à **eficiência ofensiva**, e avaliar se seu perfil estatístico indica crescimento contínuo ou estabilização de desempenho.

Este projeto reflete o tipo de análise utilizada por **departamentos de análise de desempenho e scouting no futebol profissional**.

---

## Objetivos
A análise busca responder às seguintes perguntas-chave:

- A eficiência ofensiva do jogador evoluiu ao longo das temporadas com o ganho de experiência?
- Quantas finalizações, em média, o jogador precisa para marcar um gol, e essa relação melhorou com o tempo?
- Com base nos dados históricos de performance, o jogador apresenta um perfil atrativo para decisões de contratação?

Essas perguntas foram definidas **antes da coleta dos dados**, garantindo uma análise guiada por hipóteses e não apenas por exploração aleatória.

---

## Fonte dos Dados
O dataset utilizado neste projeto foi construído manualmente a partir de dados coletados no **SofaScore**, uma plataforma pública confiável de estatísticas de desempenho no futebol.

Todos os dados da carreira foram organizados por temporada, cobrindo a trajetória do jogador desde suas primeiras aparições no futebol profissional até as temporadas mais recentes.  
Quando determinadas estatísticas não estavam disponíveis, os valores foram intencionalmente mantidos como `NULL`, preservando a integridade dos dados e evitando suposições.

---

## Estrutura do Dataset
O dataset principal está armazenado em formato CSV e contém os seguintes campos:

- `season`
- `club`
- `matches`
- `minutes_played`
- `goals`
- `assists`
- `average_rating`
- `competition_won`
- `shots`
- `shots_on_target`
- `big_chances_missed`

O dataset foi projetado para permitir análises longitudinais e cálculo de métricas de eficiência.

---

## Ferramentas e Tecnologias
A análise é conduzida utilizando:

- **SQL** para consultas, agregações e criação de métricas
- **Google Sheets** para organização inicial dos dados
- **CSV** como formato padronizado de dados
- (Futuro) Ferramentas de visualização para análise de tendências

---

## Metodologia
O processo analítico segue as seguintes etapas:

1. Coleta dos dados no SofaScore
2. Estruturação e limpeza dos dados
3. Importação do dataset para um banco de dados SQL
4. Análise exploratória e cálculo de métricas
5. Avaliação de performance utilizando métricas normalizadas (ex: gols por 90 minutos)

---

## Escopo e Limitações
Este projeto tem foco exclusivo na **performance ofensiva individual** do jogador.

Não tem como objetivo:
- Avaliar impacto tático coletivo
- Analisar títulos ou desempenho do time
- Aprofundar análises sobre lesões ou cartões (etapa futura)

---

## Próximos Passos
- Finalizar a importação e validação dos dados no SQL
- Desenvolver métricas avançadas de eficiência
- Criar visualizações para demonstrar a evolução da performance
- Expandir a análise para comparação com outros jogadores

---

## Aviso Legal
Este projeto possui fins **educacionais e de portfólio**, não representando decisões oficiais de scouting ou recrutamento.


/data
  └── yuri_alberto_career.csv

/sql
  ├── create_table.sql
  ├── exploratory_queries.sql


