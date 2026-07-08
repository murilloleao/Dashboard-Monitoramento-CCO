# 📊 Pipeline de Dados End-to-End: Monitoramento CCO & Logística
[🇧🇷 Português](#-português) | [🇺🇸 English](#-english)

---

## 🇧🇷 Português

### 📝 Descrição do Projeto
Este projeto demonstra a construção de um pipeline de dados completo (End-to-End) para o Centro de Controle Operacional (CCO) da Torre Construções. A solução nasce na automação da coleta de dados na operação (via JavaScript) e deságua em um Dashboard Executivo no Power BI para controle de produtividade, acompanhamento de SLAs e redução de custos.

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
An End-to-End Data Pipeline built for the Operational Control Center (CCO) at Torre Construções. This solution starts with automated data collection at the operational level (JavaScript/Apps Script), processes data through heavy ETL in Power Query, and flows into an Executive Power BI Dashboard focused on SLA tracking, driver productivity (Ton/h), and decimal overtime cost control.
