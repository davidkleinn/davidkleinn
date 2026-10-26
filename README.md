<div align="center">
  <img src="code.jpg" alt="Banner" width="100%">
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=Engenharia+%26+An%C3%A1lise+de+Dados;Automa%C3%A7%C3%A3o+de+Processos;Python+%C2%B7+SQL+%C2%B7+Power+BI" alt="Typing SVG" />
  </a>
</div>

<br>

Olá! Sou o **Davi**, estudante de Ciência da Computação na **UNIFOR**. Gosto de transformar dado bruto em informação que ajuda alguém a decidir: construo pipelines, dashboards e automações, e tento sempre explicar o porquê de cada decisão técnica.

- 🎓 Bacharelado em Ciência da Computação, **UNIFOR** (Fortaleza, CE)
- 🎯 Buscando estágio ou vaga júnior em **Dados / BI** e **Automação de Processos**
- 📊 Pipelines batch, modelagem analítica e dashboards com dados públicos
- 🤖 Automações com Power Automate e n8n
- 🌍 Idiomas: Português (nativo) · Inglês (fluente) · Espanhol (intermediário) · Alemão (básico)

---

## 🛠️ Tecnologias

**Análise de Dados & BI**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**Engenharia de Dados & Orquestração**

![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

**Bancos de Dados & Nuvem**

![PostgreSQL](https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

**Automação**

![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

---

## 🚀 Projetos em destaque

### 📊 Pipeline de Indicadores Econômicos — Banco Central do Brasil
> Pipeline batch ponta a ponta com Selic, IPCA e dólar, da ingestão ao dashboard.

Extração diária e idempotente orquestrada com **Apache Airflow**, processamento de 42 anos de histórico (~21 mil registros) com funções de janela no **PySpark** (médias móveis, variação percentual) e modelagem em camadas (staging → intermediate → marts) no **dbt**, com 16 testes automatizados de qualidade. Os dados são publicados no **BigQuery** e exibidos em um dashboard no **Power BI**, tudo containerizado com **Docker Compose**. O README documenta cada decisão de arquitetura (estratégia de idempotência, materializações, por que PySpark em um volume pequeno).

[→ Ver repositório](https://github.com/davidkleinn/pipeline-indicadores-bcb)

---

### 🛒 E-Commerce Funnel & Behavior Analysis
> Análise do funil de conversão e do comportamento de usuários de uma loja virtual (9,3 mil+ eventos).

Feito com **SQL (DuckDB)**, **Python (Pandas)** e **Metabase**. Análise de coorte, segmentação de clientes por RFM e desempenho de receita, com resultados apresentados em um deck executivo. A conversão global foi de 16,5%, e o e-mail foi o canal de maior rentabilidade (33,9%).

[→ Ver repositório](https://github.com/davidkleinn/ecommerce-funnel-analysis)

---

### 🤖 Machine Learning do Zero — Phishing e Preço de Imóveis
> KNN, Naive Bayes, Regressão Linear, Perceptron e MLP implementados só com NumPy, sem scikit-learn.

Comparação dos algoritmos em dois problemas reais com **validação cruzada 5-fold**, normalização calculada apenas no treino (sem vazamento de dados) e métricas implementadas à mão. Na detecção de phishing (11 mil sites), o KNN com distância de Manhattan chegou a **95,7% de acurácia**. Na previsão de preço de imóveis (21 mil registros), o mesmo KNN teve **R² de 0,76**, acima da regressão linear (0,70). Os MLPs ficaram abaixo da regressão linear, e o README analisa por quê.

[→ Ver repositório](https://github.com/davidkleinn/Projeto-IA-Av2)

---

## 🏛️ Experiência acadêmica

- 🏆 **Grupo de Programação Competitiva (GPC) — UNIFOR** (2024.2 – 2025.1): problemas de algoritmos sob restrição de tempo e memória, em Java e Python.

---

<div align="center">
  <i>Vamos conversar!</i>
  <br><br>
  <a href="https://www.linkedin.com/in/davi-klein-7b43833b6/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:davimonteklein1711@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</div>
