Sobre o Projeto
Este projeto consiste em um dashboard interativo desenvolvido para a análise de dados cinematográficos. O objetivo principal é fornecer insights visuais sobre o desempenho de filmes, tendências de gêneros, avaliações de público/crítica e métricas de bilheteria, facilitando a tomada de decisão ou o estudo do mercado audiovisual.

Como o Dashboard foi Construído
A construção deste dashboard seguiu as melhores práticas de desenvolvimento de Business Intelligence, estruturada nas seguintes etapas:

Coleta e Transformação de Dados (ETL):

Os dados brutos foram importados para a ferramenta.

Utilizando o Power Query, a base de dados passou por um processo de limpeza e transformação. Isso incluiu a remoção de valores nulos, padronização de textos, ajuste de tipos de dados (moeda, data, texto) e criação de colunas condicionais essenciais para a análise.

Modelagem de Dados:

Foi criado um modelo relacional (como o Star Schema), separando tabelas fato (ex: histórico de bilheteria ou avaliações) de tabelas dimensão (ex: diretores, gêneros, calendário). Isso garante a performance ideal do relatório.

Cálculos e Métricas (DAX):

Foram desenvolvidas medidas personalizadas utilizando a linguagem DAX (Data Analysis Expressions). Essas métricas permitem análises dinâmicas, como o cálculo de lucro total, média de notas de usuários, contagem de filmes por ano e ranqueamento dos maiores sucessos de bilheteria.

Visualização de Dados (Data Storytelling):

A interface foi projetada com foco na experiência do usuário (UX). Foram utilizados gráficos de barras, linhas, dispersão e cartões de KPI para responder às principais perguntas de negócio de forma clara e objetiva. Filtros interativos e segmentações de dados foram adicionados para permitir que o usuário explore os dados por ano, gênero ou diretor.

Estruturação do Projeto (PBIP):

O dashboard foi salvo no formato de Projeto do Power BI (.pbip).

Essa abordagem moderna separa o relatório (Analise_Filme.Report)  do modelo de dados, facilitando o controle de versão (como o uso de Git) e o trabalho colaborativo em equipe. O projeto também está configurado para permitir a recuperação automática em caso de falhas ("enableAutoRecovery": true).

Ferramentas Utilizadas
Microsoft Power BI Desktop: Plataforma principal de desenvolvimento.

Power Query: Transformação e modelagem da estrutura dos dados.

Linguagem DAX: Criação de inteligência de tempo e métricas dinâmicas.

Como Executar
Certifique-se de ter o Power BI Desktop (versão mais recente) instalado em sua máquina.

Certifique-se de que a opção de visualização para "Salvar como Projeto do Power BI (.pbip)" está ativada nas opções do seu Power BI.

Abra o arquivo Analise_Filme.pbip  diretamente no Power BI Desktop para explorar o relatório e o modelo de dados.
