# 📊 Dashboard de Importações — 2021 a 2025  
![Status](https://img.shields.io/badge/status-concluído-green)

Este repositório documenta o **Sprint 1 de 2025**, cujo objetivo foi **coletar, tratar e analisar dados estratégicos sobre o mercado de importação de smartphones no Brasil**, com base em informações oficiais e visualizações no Power BI.  

---

## 📁 Sumário  
[Etapa 1 — Conversão e Tratamento de Dados](#etapa-1--conversão-e-tratamento-de-dados)  
[Etapa 2 — Montagem do Dashboard no Power BI](#etapa-2--montagem-do-dashboard-no-power-bi)  
[Fontes e Referências](#fontes-e-referências)  

---

## 🧩 Etapa 1 — Conversão e Tratamento de Dados  

Após o download dos arquivos brutos do **Comex Stat**, foi desenvolvido um **código flexível no Google Colab** para realizar:  
- A **leitura automática** dos arquivos CSV originais;  
- A **transcrição e padronização** dos campos;  
- A **junção dos anos de 2021 a 2025** em uma única base consolidada.  

🔹 **Objetivo:** estruturar uma base limpa e pronta para análise no Power BI.  

<details>
<summary>📷 Visualizar prévia do código no Google Colab</summary>

![Prévia do Colab](https://github.com/user-attachments/assets/14d03e36-9278-4439-83b1-43bdd5cf1eeb)

</details>

📦 **Fontes de dados:**  
- [Comex Stat — Portal Oficial](https://comexstat.mdic.gov.br/pt/home)  
- [Arquivo Google Colab (.zip)](https://github.com/user-attachments/files/22854187/Conversao.de.dados.zip)  

---

## 📈 Etapa 2 — Montagem do Dashboard no Power BI  

Com a base tratada, o dashboard foi desenvolvido em **quatro páginas** que representam diferentes perspectivas da análise de importação de smartphones no Brasil.  

Atualmente, o projeto encontra-se em **fase de protótipo visual**.

---

### 🟦 1ª Página — Visão Geral  
Resumo dos principais indicadores de desempenho, incluindo **volume total importado**, **valor FOB** e **preço médio por KG**.  

<img width="1316" height="738" alt="Dashboard página 1" src="https://github.com/user-attachments/assets/b6440b81-c60f-431a-a3bd-9cba9b2d283b" />

---

### 🟧 2ª Página — Análise Temporal  
Visualização da **evolução mensal e anual das importações**, permitindo identificar tendências e sazonalidades.  

<img width="1317" height="740" alt="Dashboard página 2" src="https://github.com/user-attachments/assets/1355b33a-8adf-4325-9a8f-faa7c550a22f" />

---

### 🟨 3ª Página — Produtos e Categorias  
Análise detalhada por **NCM e descrição de produto**, com ranking dos **10 itens mais importados**.  

<img width="1315" height="741" alt="Dashboard página 3" src="https://github.com/user-attachments/assets/738f7695-90ec-4bd7-9fbd-69ace1ea1b97" />

---

### 🟩 4ª Página — Distribuição Geográfica  
Mapa interativo exibindo a **origem das importações por país**, destacando os **principais parceiros comerciais**.  

<img width="1315" height="736" alt="Dashboard página 4" src="https://github.com/user-attachments/assets/362b3a87-7dd3-45a7-8207-02fd3ac1cda5" />

---

### 🌐 Acesso direto  
- [📊 Visualizar no Power BI](https://app.powerbi.com/view?r=eyJrIjoiYzU3OTdjZmEtMjY5NS00ZWQ3LTg1NGEtMjZkMmQ5ODE1YjJhIiwidCI6ImNmNzJlMmJkLTdhMmItNDc4My1iZGViLTM5ZDU3YjA3Zjc2ZiIsImMiOjR9)  

---

## 📚 Fontes e Referências  

| Tipo | Fonte |
|------|-------|
| Dados | [Comex Stat – Ministério da Economia](https://comexstat.mdic.gov.br/pt/home) |
| Processamento | Google Colab |
| Visualização | Power BI Desktop / Power BI Service |
| Autor | **Bruno Pimenta** |

---

### 💬 Observação  
O projeto será expandido futuramente para incluir:
- Indicadores de **valor agregado por produto (US$/kg)**  
- Comparação **Brasil × principais países exportadores**  
- Dashboards dinâmicos com **filtros interativos por ano, mês e país**  

---
