<h2 align="center">Valdiney Alves · Ney 👋</h2>

<p align="center">
  <strong>Analista de Dados Pleno → Engenharia de Dados</strong><br>
  Crédito Consignado · Conciliação · Meios de Pagamento · São Paulo, BR
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/valdineyalves/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:valdiney.alves03@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

---

Trabalho com dados em uma fintech de crédito consignado. Cuido do caminho inteiro do dado: entrada, tratamento e entrega pronta para análise.

Minha área não tem acesso ao banco SQL da empresa. Montei a estrutura de dados com as ferramentas que tinha — Python, Parquet, Dataflows e camadas Medallion. Está rodando em produção e virou a base da migração das bases para SQL.

Vim da conciliação financeira, então olho qualidade de dado como regra de negócio: um valor divergente vira desconto recusado e, no fim, inadimplência.

---

**O que eu faço hoje**

- Construo e mantenho os pipelines da área, da entrada do dado até a camada que o time consome: Medallion, Parquet, Dataflows (Microsoft Fabric), BigQuery sobre Cloud Storage e Databricks (SQL, tabelas Delta)
- Trato de 260 a 380 mil linhas por dia
- Automatizo coletas e integrações em Python: Microsoft Graph API, REST e, quando a fonte não tem API, Selenium
- Cuido da qualidade dos dados: regras de conciliação e matching, detecção de divergências, deduplicação e monitoramento de falhas de carga
- Sou a ponta técnica da iniciativa de IA da área: modelos de previsão de resultado, busca inteligente de inadimplência, chat de perguntas sobre os dados e agentes (n8n) que acompanham conciliações, erros operacionais e pagamentos
- Construo e mantenho os dashboards em Power BI e HTML

---

**Impactos**

- A atualização do pipeline caiu de mais de **2 horas para menos de 15 minutos**. Levei o processamento local para ETL em nuvem e cortei as etapas que se repetiam
- Montei a arquitetura Medallion do zero e converti os arquivos .dat para Parquet: **70% menos espaço** e **42% menos tempo de refresh** no Power BI Service. Isso liberou o uso de todo o histórico, antes inviável, e enxugou o custo de licenças e de capacidade contratada
- Envio mensal das importações de convênio: de **~12 horas para ~5 minutos**, com um app em Python que mostra quantidades e valores para conferir antes do disparo e alerta os erros do processo
- Criei a automação de repasse de valores em lote para contornar o limite de 10 mil linhas por dia da plataforma, que atrasava o crédito do cliente no vencimento. **O atraso diminuiu em 3 dias**, com pontos de validação e alerta de convênio perto de perder o vencimento. O time incorporou a ferramenta ao processo e a apelidou de "Neyliqui"
- No negócio: tabelas operacionais e relatórios executivos entregues mais cedo, menos retrabalho entre cortes de fatura e importações, e painéis atualizados com mais frequência

---

**Em estudo agora:** SQL · PySpark · Airflow · Docker (pipeline próprio, com dados sintéticos, evoluindo uma camada por fase)

**Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Aprendendo**

![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
