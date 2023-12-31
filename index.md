---
layout: default
---

_Hi there! This is Nhat Quach 👋. Welcome to my personal portfolio which serves as a place for me to showcase my projects especially in data analyzation and transformation aspects._
<br/><br/>

## ☎️ Contact

* **Github**: https://github.com/nhatquachxxx

* **Linkedin**: https://www.linkedin.com/in/nhatquach1011

* **Email**: nhatquach1011@gmail.com
<br/><br/>

## 🛠️ My Toolset

<p align="center">
    <img src="pictures\dbt.png" width="50" />
    <img src="pictures\google_bigquery.png" width="50" />
    <img src="pictures\airflow.png" width="45" />
    <img src="pictures\postgres.png" width="50" />
    <img src="pictures\looker.png" width="50" />
    <img src="pictures\power_bi.png" width="43" />
    <img src="pictures\git.png" width="50" />
    <img src="pictures\jira.png" width="50" />
    <img src="pictures\airbyte.png" width="60" />
</p>
<br/>

## 📝 Projects

### Data Pipeline for Jira platform
<a href="https://github.com/clv-dev/jira-clv-transformation" target="_blank">Explore More
</a>

**Overview** <br/>
In this project, I built a data pipleine to extract data for the purpose of team reporting, task monitoring as well as progress tracking. Firstly data was extracted from Jira and loaded to Bigquery. Airbyte was used as an integration tool for extraction and loading. Finally, I utilized data build tool (aka dbt) to transform data into reportable form which was then consumed by Looker Studio. Good source of data along with appropriate transformation plan create a solid dashboard where users can analyze from multiple angles with different dimensions.

 ![Jira Dashboard](pictures\jira_dashboard.png)
<br/><br/>

### Data Warehouse Project 
<a href="https://github.com/nhatquachxxx/data-warehouse-course" target="_blank">Explore More
</a>

**Overview** <br/>
In this project, I built a Data Warehouse from scratch for 2 modules Sales Orders and Purchasing Orders. Kimball's Dimensional Modeling principles is applied when designing data model especially such hard techniques as snapshot fact table, hierarchy bridge table, etc. Besides, I also implemented data quality check with dbt Test and other add-ins.

![A picture about diagram](pictures\model.png)
