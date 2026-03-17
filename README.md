# 📊 Dashboard Executivo e Sistema de Ocorrências - CCO

## 🎯 O Desafio Operacional
Na operação, o registro de ocorrências da frota tomava muito tempo com controles manuais e planilhas descentralizadas. Isso engessava a comunicação do Centro de Controle Operacional (CCO) e atrasava a tomada de decisão da Diretoria.

## 🚀 A Solução e a Evolução do Projeto
Para resolver esse problema, criei uma solução do zero, escalando a tecnologia conforme a operação exigia mais maturidade em dados:

### 📦 V1 - O Início (MS Excel e VBA)
O marco zero da automação. Para acabar com o controle no papel e erros de digitação, desenvolvi uma planilha com formulários em VBA. O operador digita a placa, e o sistema já puxa setor e motorista automaticamente, consolidando tudo numa base limpa.

<img width="1910" height="990" alt="Excel 1" src="https://github.com/user-attachments/assets/2be66af9-40a7-474c-a0dd-37c320a0d59b" />
<img width="1909" height="979" alt="Excel 2" src="https://github.com/user-attachments/assets/61cbb8df-a0de-4ceb-81b2-714bf40375a2" />

### ☁️ V2 - A Nuvem (Google Sheets)
Para permitir que múltiplos operadores do CCO alimentassem o sistema ao mesmo tempo e de lugares diferentes, migrei a lógica da base de dados para a nuvem.

### 📈 V3 - Inteligência Executiva (Power BI)
Com a base estruturada e rodando na nuvem, conectei o Power BI para consumir esses dados via ETL. Eliminei o trabalho braçal de montar relatórios no fim do mês e criei uma visão executiva limpa e interativa.

<img width="1630" height="878" alt="Power BI 1" src="https://github.com/user-attachments/assets/e20f2445-61c5-403d-b490-a1e375bbe876" />
<img width="1611" height="883" alt="Power BI 2" src="https://github.com/user-attachments/assets/d31f989c-e589-45d9-b681-7d687b793116" />



## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Power BI & Power Query (ETL):** Tratamento pesado de dados (correção de anomalias de tempo, conversão para horas decimais reais) e UX Design (Bookmarks, pop-ups e botões).
* **DAX:** Lógicas de negócio para cálculo de médias e criação de Tabela dCalendario.
* **Excel, VBA e Google Sheets:** Criação da interface de lançamento e armazenamento em nuvem.

## 📊 Principais Entregas e KPIs no Dashboard
* **SLA de Atendimento:** Visão do percentual de ocorrências resolvidas no prazo.
* **Top 5 Placas Ofensoras:** Ranking de veículos com maior tempo parado (foco em manutenção preventiva).
* **Volume Diário de Paradas:** Análise de tendência operacional.
* **Resumo Operacional:** Interface de tabela detalhada, com design minimalista.

---
*Próximo passo técnico (Em andamento): Migração da base de planilhas para um Banco de Dados Relacional utilizando modelagem e consultas em SQL.*
