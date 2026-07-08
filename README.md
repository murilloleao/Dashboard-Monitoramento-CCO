# 📊 Pipeline de Dados End-to-End: Monitoramento CCO & Logística
[🇧🇷 Português](#-português) | [🇺🇸 English](#-english)

---

## 🇧🇷 Português

### 📝 Descrição do Projeto
Este projeto demonstra a construção de um pipeline de dados completo (End-to-End) para o Centro de Controle Operacional (CCO). A solução nasce na automação da coleta de dados na operação (via JavaScript) e deságua em um Dashboard Executivo no Power BI para controle de produtividade, acompanhamento de SLAs e redução de custos.

### 🖥️ Visualização do Dashboard (Prints Reais)

**Tela 1: Painel de Monitoramento (SLA em Tempo Real)**
<img width="1856" height="786" alt="registro_ligações_SLA" src="https://github.com/user-attachments/assets/9c5b47d0-4073-458d-8f6c-bff00113ac6c" />


**Tela 2: Resumo Operacional (Produtividade CDC & Horas Extras)**
<img width="1209" height="683" alt="resumo_operacional" src="https://github.com/user-attachments/assets/e3ff36fd-6993-424c-9f19-d259ee369c9d" />


### ⚙️ Engenharia de Dados & Funcionalidades
* **Automação na Ingestão (JavaScript/Apps Script):** Desenvolvimento de sistema de registro e formulários integrados, reduzindo o trabalho manual de digitação em até 60% e aplicando lógicas relacionais para travar dados incorretos na fonte.
* **Processamento de Dados (ETL):** Tratamento de bases de dados mensais utilizando o Power Query, realizando limpeza, tratamento de erros, filtros de nulos e consolidação das tabelas (MAR, ABR, MAI, JUN).
* **Modelagem e DAX Avançado:** Criação de Modelo Relacional (Star Schema) com tabela dimensional `dCalendario`. Desenvolvimento de métricas de negócios em DAX para cálculo de horas extras decimais e quebras de SLA.

### 📊 Impacto de Negócio
* Eliminação de relatórios manuais e centralização da operação em um pipeline 100% automatizado.
* Identificação imediata de gargalos operacionais e controle rígido sobre custos de horas extras por motorista.

---

## 🇺🇸 English

### 📝 Project Description
This project demonstrates the development of a complete End-to-End Data Pipeline for the Operational Control Center (CCO) at Torre Construções. The solution begins by automating data collection on the shop floor (via JavaScript) and culminates in an Executive Power BI Dashboard for productivity tracking, SLA monitoring, and cost reduction.

### 🖥️ Dashboard Visualization (Real Screenshots)

**Screen 1: Monitoring Panel (Real-Time SLA)**
<img width="1856" height="786" alt="registro_ligações_SLA" src="https://github.com/user-attachments/assets/dbdbf317-efd8-4ac9-8b4d-dc13d0b95cff" />


**Screen 2: Operational Summary (CDC Productivity & Overtime)**
<img width="1209" height="683" alt="resumo_operacional" src="https://github.com/user-attachments/assets/150637f9-c149-4912-9868-d6fd7a3444d2" />


### ⚙️ Data Engineering & Features
* **Automated Data Ingestion (JavaScript/Apps Script):** Built an integrated logging and form system, reducing manual data-entry effort by up to 60% and implementing relational logic to prevent bad data at the source.
* **Data Processing (ETL):** Handled monthly data sources using Power Query to perform data cleansing, error handling, null filtering, and table consolidation across multiple months (MAR, APR, MAY, JUN).
* **Data Modeling & Advanced DAX:** Developed a relational Star Schema utilizing a custom `dCalendario` dimension table. Authored specialized DAX business metrics to calculate decimal overtime and track SLA breaches.

### 📊 Business Impact
* Complete elimination of manual reporting by shifting the operation to a 100% automated data pipeline.
* Immediate identification of operational bottlenecks and strict control over driver overtime costs.
