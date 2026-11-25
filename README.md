<h1 align="center">Hi, I'm Siddhartha</h1>
<h3 align="center">I build analytics and AI tools, then test whether the results actually hold up.</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/siddhartha-ananthula/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ananthulasiddhartha@gmail.com"><img src="https://img.shields.io/badge/Email-ananthulasiddhartha%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Location-Melbourne%2C%20Australia-2E7D32?style=flat" alt="Location: Melbourne, Australia">
</p>

Data analyst and data scientist · Master of Data Science, RMIT University (2026).

- 🟢 **Open to** data analyst, data scientist and AI engineering roles in Australia
- 🔭 Building **[The Substitution Gap](https://github.com/siddharthaananthula/substitution-gap)** in public: ranking grocery substitutes by whether shoppers accept them, not by product similarity (in progress)
- 💬 Ask me about **dbt testing, MCP agents and how to evaluate them, or why I chose not to publish an uplift number**
- 📄 Published: *CAPTCHA Recognition Using DCNN*, IJSREM, 2023
- 🏆 Best Demonstration Award, RMIT Open Day 2026

### How I work

```mermaid
flowchart LR
    Q["Business question"] --> V["Validate the data<br/>coverage, duplicates, gaps"]
    V --> B["Build<br/>SQL and dbt pipelines<br/>models, agents"]
    B --> T["Test<br/>dbt tests, eval sets,<br/>checks against raw SQL"]
    T --> R["Report<br/>results and what failed"]
```

### Findings from my projects

| Finding | Project |
|---|---|
| **80.28%** of revenue came from mixed-brand baskets, which were 57.0% of all baskets | [Retail Performance Analytics](https://github.com/siddharthaananthula/retail-performance-analytics) |
| **78.28%** of transaction lines had no matching promotion record, so I rejected the observational design before estimating any uplift | [Promo Effectiveness](https://github.com/siddharthaananthula/promo-effectiveness) |
| **9 of 10** out-of-scope and adversarial requests correctly escalated or refused by an MCP-connected agent | [Internal Help-Centre Agent](https://github.com/siddharthaananthula/internal-help-centre-agent) |
| **69%** of populated Victorian SA2 areas had no mapped AFL community venue | [Grassroots Footy Map](https://github.com/siddharthaananthula/afl-accessibility-map) |

### Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt%20Core-FF694B?style=flat&logo=dbt&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI%20%C2%B7%20DAX-F2C811?style=flat&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=flat&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas%20%C2%B7%20QGIS-139C5A?style=flat&logo=qgis&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

### Featured projects

| Project | What it shows |
|---|---|
| [**Retail Performance Analytics**](https://github.com/siddharthaananthula/retail-performance-analytics) | 2.6M transaction lines through PostgreSQL and dbt (20 models, 73 tests, CI) into a seven-page Power BI report, with key figures checked against independent SQL. [Site](https://siddharthaananthula.github.io/retail-performance-analytics/) |
| [**Promo Effectiveness**](https://github.com/siddharthaananthula/promo-effectiveness) | Tests whether campaign data can support an uplift estimate, finds it can't, and designs a randomised holdout sized with a power analysis instead |
| [**Internal Help-Centre Agent**](https://github.com/siddharthaananthula/internal-help-centre-agent) | OpenAI tool-calling agent with read-only MCP tools, a 30-question evaluation set, cost and latency logging, and a go-live agent card (prototype) |
| [**300,000 Streets of Melbourne**](https://github.com/siddharthaananthula/300-000-School-Streets) | Team capstone with Regen Melbourne: school-street safety screen built from crash, OpenStreetMap, EPA and ABS data, with a Leaflet.js dashboard. [Dashboard](https://siddharthaananthula.github.io/300-000-School-Streets/) |
| [**Grassroots Footy Map**](https://github.com/siddharthaananthula/afl-accessibility-map) | 252 AFL community venues mapped against ABS disadvantage data across Victoria. [Map](https://siddharthaananthula.github.io/afl-accessibility-map/) |
| [**The Substitution Gap**](https://github.com/siddharthaananthula/substitution-gap) | Grocery substitution ranking based on shopper behaviour, with customer-level evaluation (in progress) |
