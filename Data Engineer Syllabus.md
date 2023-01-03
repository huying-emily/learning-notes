# Data Engineer Syllabus

<aside>
📌 Summarised @ Emily Hu.

</aside>

# 🗝Direction & Title

1. infrastructure / service → Data Infrastructure Engineer / Data Engineer
2. data warehousing / data modelling / pipeline automation → Data Warehouse Engineer / 算法工程师 / Machine Learning Engineer / Analytical Engineer
3. transformation 
4. data analysis → BI / BA

# 📚Data Warehouse

## Data Warehouse Building

1. Be familiar with common designs: **snowflake** v.s. **star** schema (Data warehouse design kimball v.s. Inmon: Reading #1, Reading #2)
2. Data Warehouse Building:
    
    1.数据仓库搭建 link: [https://www.zhihu.com/question/19703294](https://www.zhihu.com/question/19703294)
    
    2.ODS, DWD, DWS, ADS
    

## Modelling

1. SCD: **Slowly Changing Dimension** (3 types)
2. CDC: **Change Data Capture**

## Data Quality Check / Data Health Check

1. DBT test
2. Mappers: Reusable and Automatic 
3. Visualisation

## Technique and Knowledge

Redshift Modify Methods:  

what is it? why we use it? how it works? when to use? have any example?

1. **Distribution Key**
2. **Sort Key**
3. other questions: how to deal with large table? etc.

Distribution Key (in Redshift) v.s. **Partition Key** (in Hive):

how it works? when to use? problem in modification? how to resolve?

Other common techniques, concepts, principles. (like Hive is similar with Redshift in data storing)

Spark & Hive (low priority)

## Trending

1. Data Lake v.s. Data Warehouse v.s. Data Lake House(湖仓一体): pros and cons, when to use, how to choose
2. Data Mesh
3. Domain-driven Data Architecture 
4. Data Governance 
5. Data Platform as a Service (PaaS) v.s. Data Infrastructure as a Service (IaaS) v.s. Data Software as a service (SaaS)
6. Centralised Governance(Centralised data warehouse) v.s. Decentralised Governance(Self-management data warehouse)

# 🧮  Infrastructure

# 📚 Readings

[Books](https://www.notion.so/33cc50a18b2443c8a30974154c9125bc)

### Article:

[https://preset.io/blog/reshaping-data-engineering/](https://preset.io/blog/reshaping-data-engineering/)