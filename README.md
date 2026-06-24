# 👥 Análise de Dados de RH — Power BI

Dashboard de análise de composição de quadro de funcionários, com foco em distribuição por cargo, disponibilidade para hora extra e níveis de envolvimento no trabalho.

## 🎯 Problema de negócio

Apoiar o time de RH no diagnóstico da composição do quadro técnico, dos padrões de disponibilidade para hora extra e dos níveis de envolvimento no trabalho — informações que orientam ações de retenção e planejamento de capacidade da equipe.

## 🔍 Principais insights

- **Quadro fortemente concentrado em um único cargo.** Cientistas de Dados representam 638 dos 1.400 funcionários (45,6%) — quase a metade da empresa em uma única função, o que é uma composição de equipe atípica e sugere uma organização centrada em produto de dados/tecnologia.
- **Maioria não está disponível para hora extra.** 71,57% dos funcionários não têm disponibilidade, contra 28,43% que têm.
- **Quase 1 em cada 3 funcionários tem envolvimento baixo ou ruim no trabalho.** Embora a maior parte esteja no nível "Médio" (59%), somando os níveis "Baixo" (25,43%) e "Ruim" (5,64%) chega-se a 31,07% da base — um ponto de atenção relevante para risco de retenção.
- **Leve maioria masculina.** 59,86% dos funcionários são homens (838) e 40,14% mulheres (562).
- **Experiência média de 11,29 anos** e **salário médio de R$ 6.927,51** no quadro geral.

## 📄 Estrutura do dashboard

Página única, com filtro de faixa etária (18–60 anos) e os seguintes blocos:

- **KPIs gerais:** total de funcionários, salário médio, experiência média, distribuição por gênero
- **Disponibilidade para hora extra:** percentual de funcionários disponíveis x não disponíveis
- **Funcionários por função:** Cientista de Dados, Analista de Dados, Engenheiro de IA, Arquiteto de Dados e demais funções técnicas
- **Envolvimento no trabalho:** distribuição entre os níveis Médio, Baixo, Alto e Ruim

## 🛠️ Stack técnica

- **Ferramenta:** Power BI Desktop
- **Modelagem e visualização:** cards de KPI, gráficos de rosca, gráfico de barras horizontal, filtro de intervalo (slider) por idade
- **DAX:** medidas customizadas utilizadas para os cálculos de indicadores do dashboard

## 📊 Fonte dos dados

Dataset público utilizado no curso de Power BI da **Data Science Academy (DSA)**. 

## 🔗 Acesse o relatório

[Acesse o dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzJjMjk1NzctMzZjMy00YmM5LTkwNWUtZjJlNzFmNDY5NWI4IiwidCI6ImIyZTE2Mjk3LTJlZDYtNDFiOC1iODIyLWE5NTRlOTViZDJmMCIsImMiOjR9) — não requer login ou conta Power BI

## 📌 Limitações e próximos passos

- Os nomes completos de 2 das funções no gráfico de barras estão truncados na captura de tela atual ("Engenheiro de..." e "Engenheiro An..."); revisar e atualizar com o nome completo antes de publicar.
- Não foi confirmado se houve tratamento de dados via Power Query neste projeto.
- Próxima iteração: cruzar nível de envolvimento no trabalho com disponibilidade para hora extra, para verificar se a falta de disponibilidade está associada a maior ou menor engajamento.
