# Análise de Dados e Business Intelligence - Ian Store 📊

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Windows 10](https://img.shields.io/badge/Windows_10-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Analítica-blue?style=for-the-badge)

Este projeto apresenta uma solução completa de Business Intelligence, abrangendo desde a extração e tratamento de dados (ETL) até a criação de dashboards estratégicos para suporte à tomada de decisão. 

---

## 🛠️ Tecnologias e Ferramentas
* **Power BI Desktop** (Criação de Dashboards e Visualização)
* **Power Query / Linguagem M** (Processo de ETL e Limpeza de Dados)
* **DAX** (Métricas personalizadas e Inteligência de Dados)
* **Ambiente de Desenvolvimento:** Virtual Machine (VM) com **Windows 10** configurada sobre Host **Ubuntu Linux**.
* **Dataset:** Ian Store (Vendas/Varejo).

## 🏗️ 1. Processamento de Dados (ETL)
Para garantir a integridade das análises e a precisão dos cálculos, realizei as seguintes etapas:
* **Integridade:** Remoção de duplicatas na coluna de IDs para evitar redundância de vendas.
* **Tratamento de Nulos:** Ajuste de valores nulos para que recebessem 0.
* **Padronização:** Ajuste dos formatos de data (Date) e monetários/rating (Decimal Fixo), seguindo a localidade **Inglês (Estados Unidos)**.
* **Escalabilidade:** Correção da escala monetária (divisão por 100).
* **Enriquecimento:** Inserção de uma nova coluna de **Turnos** para avaliação por períodos.
* **Métricas DAX:** Total de Vendas, Lucro Total, Ticket Médio, Rating Final e Total de Itens Vendidos.

## 📈 2. Análise Descritiva (O que aconteceu?)
* **Insight:** O turno da tarde concentra mais de 50% das vendas, indicando a necessidade de reforço operacional.
* **Análise de Pagamento:** Tickets maiores no crédito sugerem incentivos para parcelamentos maiores.

> ![Análise Descritiva](Prints/Análise%20Descritiva.png)

## 🔍 3. Análise Diagnóstica (Por que aconteceu?)
* **Perfil do Público:** Maior concentração de público masculino.
* **Insight de Negócio:** Expandir mix de produtos femininos e criar combos de tecnologia + alimentação para cross-selling.

> ![Análise Diagnóstica](Prints/Análise%20Diagnóstica.png)

## 🔮 4. Análise Preditiva (O que pode acontecer?)
* **Sazonalidade:** Configuração de ciclo semanal (7 dias).
* **Tendência:** Crescimento estável, minimizando riscos de quebra e garantindo cobertura de custos fixos.

> ![Análise Preditiva](Prints/Análise%20Preditiva.png)

---
**Desenvolvido por Ana Luiza.**