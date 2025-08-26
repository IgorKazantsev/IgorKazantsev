readme_updated = """# Hi there, I'm Igor Kazantsev 👋  

## 🎯 Professional Summary  

I am a final-year student at **Tallinn University of Technology (TalTech, Estonia)**, studying **Smart Systems and Digital Solutions** (part-time, distance learning).  
My primary focus is **Data Engineering and Data Science**, and I am continuously developing my expertise in **Python, SQL, and Cloud-based ETL pipelines**.  

I have practical experience from an **Erasmus+ internship in Data Engineering**, where I built scalable ETL pipelines with **Azure Databricks, Python, SQLAlchemy, and PostgreSQL** for financial and macroeconomic data.  

My passion lies in **data-driven technologies**—I enjoy extracting, processing, and analyzing data to uncover valuable insights.  

---

## 📫 Contact Me  
[![Gmail Badge](https://img.shields.io/badge/-igor.kazantsev@taltech.ee-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:igor.kazantsev@taltech.ee)](mailto:igor.kazantsev@taltech.ee)  
[![Linkedin Badge](https://img.shields.io/badge/-igorkazantsev-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/igor-kazantsev/)](https://www.linkedin.com/in/igor-kazantsev/)  
[![GitHub Badge](https://img.shields.io/badge/-IgorKazantsev-black?style=flat-square&logo=github&logoColor=white&link=https://github.com/IgorKazantsev)](https://github.com/IgorKazantsev)  

---

## 🛠 Skills  

**Programming Languages:** Python, SQL, C#  
**Data Engineering & Analytics:** Pandas, NumPy, Power BI, ETL/ELT, Databricks, Azure, PostgreSQL, MySQL  
**Workflow & Orchestration:** Airflow (ETL DAGs), CI/CD basics  
**Web Scraping & Automation:** Selenium, BeautifulSoup  
**Development & APIs:** REST APIs, C# .NET (CRUD Operations)  
**Other Tools:** Git, WordPress  
**Soft Skills:** Strong knowledge of English, Russian, and Estonian; basic Spanish  

---

## 💼 Personal Projects  

### 🔹 **FRED ETL Pipelines**
- A **data engineering project** for building ETL pipelines with public macroeconomic data.  
- Fetches datasets from the **FRED API**, applies transformations, and loads into **PostgreSQL**.  
- Implements **deduplication, logging, and environment-based credential management**.  
📍 **GitHub Repo:** [FRED ETL Pipelines](https://github.com/IgorKazantsev/Fred-etl-pipelines)  

### 🔹 **FastForex ETL**
- A pipeline for ingesting **foreign exchange rates** using the **FastForex API**.  
- Automates extraction of daily currency rates and loads them into **PostgreSQL**.  
- Provides the basis for building **BI dashboards** in Power BI/Tableau.  
📍 **GitHub Repo:** *(coming soon)*  

### 🔹 **Airflow File Ingestion DAG**
- Developed an **Airflow DAG** to automate ingestion of local files (CSV/JSON) into **cloud storage** (Azure Blob / AWS S3).  
- Demonstrates **workflow orchestration**, file monitoring with sensors, and cloud integration.  
- Includes error handling and logging for reliability.  
📍 **GitHub Repo:** *(coming soon)*  

---

## 📚 Education & Internship  

🎓 **Tallinn University of Technology (TalTech)**, Estonia  
_BSc in Smart Systems and Digital Solutions (final year, part-time/distance learning)_  

💼 **Erasmus+ Internship – Data Engineering** (2025)  
- Built and maintained **ETL pipelines** for ingesting macroeconomic and financial datasets.  
- Automated data ingestion (Python, SQLAlchemy, PostgreSQL).  
- Orchestrated data workflows in **Azure Databricks** with batch scheduling.  

---

## 📚 Future Career Goals  

I am passionate about **Data Engineering** and plan to start my career as a **Junior Data Engineer** upon graduation.  
In the future, I aim to **pursue a Master’s degree in Artificial Intelligence** to deepen my expertise and work on advanced **AI-driven solutions**.  

I am constantly seeking **new challenges and learning opportunities** that will help me stay **up-to-date with emerging technologies** and apply them to **create innovative solutions**.  

---

## 🚀 Quick Stats  
![Igor's GitHub stats](https://github-readme-stats.vercel.app/api?username=IgorKazantsev&show_icons=true&hide=["issues"]&theme=dark)  

---

⚠️ *Disclaimer: All showcased projects are based on **public data sources** and are created for **educational and portfolio purposes** only. They are not affiliated with any company.*  
"""

out_path = "/mnt/data/README_PROFILE.md"
with open(out_path, "w", encoding="utf-8") as f:
    f.write(readme_updated)

out_path
