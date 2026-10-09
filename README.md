<h1 align="center">Olá, eu sou o Gabriel Sabino 🤖</h1>

<p align="center">
  <a href="https://github.com/Gsabin0">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00B4D8&center=true&vCenter=true&width=600&lines=Desenvolvedor+RPA+%7C+Dados;Automa%C3%A7%C3%A3o+%2B+Integra%C3%A7%C3%A3o+%2B+Dados;Python+%7C+SQL+%7C+UiPath+%7C+Spark" alt="Typing SVG" />
  </a>
</p>

---

### Sobre mim

Desenvolvedor RPA com mais de 4 anos de experiência em **automação de processos e integração de sistemas** com **Python, SQL Server e API REST**. Atuo do mapeamento do processo à sustentação em produção, com foco em ERPs, rotinas ETL e automação web com Selenium e Playwright.

- **Desenvolvedor RPA** na **Paranoá Indústria de Borracha**, desde 2022 (estagiário até fev/2023, desenvolvedor desde mar/2023)
- **80+ automações** entregues em produção
- Conduzi a migração de **30+ processos de UiPath para Python**, eliminando **R$ 120 mil/ano em licenças** e liberando a execução em paralelo
- Criei um **orquestrador próprio em Node-RED** (fila de execução, logs e alertas), que reduziu o tempo de detecção de falhas de **4 h para menos de 5 min**
- Pós-graduado em **Big Data & Data Engineering** (FIA) e **RPA / Hiperautomação** (PUC Minas)
- Graduado em **Análise e Desenvolvimento de Sistemas** (SENAI Diadema)
- Diadema / São Paulo, Brasil
- Nas horas vagas: Pokémon VGC competitivo

---

### O que eu construo

**RPA & Integração**

- **Orquestração de robôs:** as automações rodavam isoladas, sem agendamento nem monitoramento. Construí um orquestrador em Node-RED com fila de execução, logs e alertas de falha, que acabou com os disparos manuais.
- **Migração de plataforma:** levei 30+ processos de UiPath para Python e padronizei tratamento de exceções, logging e estrutura de projeto numa biblioteca interna.
- **Fiscal e faturamento:** integrei sistemas internos e o ERP via API REST e SQL Server, substituindo o lançamento manual de cerca de 300 registros/mês. O tempo caiu de 15 min para 3 min por registro, liberando **60 h/mês** da equipe fiscal e eliminando a conferência em papel.
- **Conciliação documental com lançamento em ERP:** robô que acessa o portal de um cliente, baixa os PDFs, extrai os valores, grava em SQL Server e faz o de-para com outro sistema via API. Quando os valores batem, ele lança direto no ERP. Quando há divergência, encaminha só o caso inconsistente, e o time passou a tratar exceções em vez de conferir 500 documentos/mês.
- **Extração e raspagem web:** robôs que acessam portais e sistemas web (Selenium, WebDriver, Playwright), extraem e raspam dados, tratam arquivos XML, Excel e CSV e validam tudo antes da carga, abastecendo áreas como administração de vendas.

**Engenharia de dados**

- **Extração paginada em larga escala:** minha maior ferramenta de dados. Extrai dados de plantas industriais como serviço contínuo, percorre as fontes de forma paginada, guarda estado para retomar de onde parou e faz a ingestão no data lake.
- **Tráfego de dados online:** serviço que envia continuamente os indicadores de produção (OEE) das plantas para a nuvem, alimentando dashboards em tempo quase real.
- **Ingestão incremental:** ETL com controle incremental por watermark, gravação em Parquet no MinIO e camada analítica consumida via ODBC no Power BI, que reduziu o tempo de carga em **70%**.

---

### Tecnologias e ferramentas

**Linguagens & Desenvolvimento**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

**RPA & Hiperautomação**

<p>
  <img src="https://img.shields.io/badge/UiPath-FA4616?style=for-the-badge&logo=uipath&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white" />
  <img src="https://img.shields.io/badge/Node--RED-8F0000?style=for-the-badge&logo=nodered&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_Apps-742774?style=for-the-badge&logo=powerapps&logoColor=white" />
  <img src="https://img.shields.io/badge/SharePoint-0078D4?style=for-the-badge&logo=microsoftsharepoint&logoColor=white" />
</p>

**Automação Web**

<p>
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
  <img src="https://img.shields.io/badge/WebDriver-43B02A?style=for-the-badge&logo=selenium&logoColor=white" />
</p>

**Dados**

<p>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenPyXL-217346?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Parquet-50ABF1?style=for-the-badge&logo=apache&logoColor=white" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
</p>

**Ferramentas & Infraestrutura**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

---

### GitHub Stats

<div align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=Gsabin0&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&locale=pt-br" />
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gsabin0&layout=compact&langs_count=7&theme=tokyonight&hide_border=true&locale=pt-br" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Gsabin0&theme=tokyonight&hide_border=true&locale=pt_BR" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Gsabin0/Gsabin0/output/github-contribution-grid-snake-dark.svg" />
    <img alt="" src="https://raw.githubusercontent.com/Gsabin0/Gsabin0/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

---

### Contato

<p>
  <a href="https://www.linkedin.com/in/gabrielsabinocp/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:gsabino56@icloud.com"><img src="https://img.shields.io/badge/iCloud_Mail-3693F3?style=for-the-badge&logo=icloud&logoColor=white" /></a>
</p>
