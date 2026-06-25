# 🏛️ PBL - Gestão Pública e Turismo Inteligente (Cidade Alfa)

Este repositório contém a solução desenvolvida para a **Fase 4 (Desafio de Análise Exploratória)** do projeto de Bloco (PBL). O objetivo do sistema é coletar, processar e analisar os feedbacks dos cidadãos sobre os pontos turísticos da Cidade Alfa, fornecendo insights estratégicos para a administração pública municipal.

---

## 🛠️ Arquitetura e Tecnologias

A infraestrutura do projeto simula um ambiente de produção real voltado para Engenharia de Dados:
* **Banco de Dados Relacional (Oracle):** Armazenamento estruturado dos dados de cidadãos, atrações e avaliações.
* **Camada de Cache Geoespacial (Redis):** Indexação em memória RAM das coordenadas utilizando comandos nativos (`GEOADD` e `GEOPOS`) para renderização instantânea do mapa.
* **Linguagem & Análise (Python):** Processamento das regras de negócio através de Pandas e NumPy.
* **Visualização de Dados:** Geração de gráficos estatísticos com Matplotlib e mapas interativos com Folium.

---
