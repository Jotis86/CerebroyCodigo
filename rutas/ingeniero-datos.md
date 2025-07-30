# 🔧 Ruta de Estudio: Ingeniero de Datos

![Data Engineer Banner](https://img.shields.io/badge/Duración-14--18%20semanas-blue) ![Nivel](https://img.shields.io/badge/Nivel-Intermedio%20a%20Avanzado-red) ![Dedicación](https://img.shields.io/badge/Dedicación-15--20h%2Fsemana-orange)

## 🎯 Objetivo de la Ruta

Convertirte en un Ingeniero de Datos capaz de diseñar, construir y mantener arquitecturas de datos escalables, crear pipelines robustos de ETL/ELT, gestionar data lakes y warehouses, y garantizar la calidad y disponibilidad de datos para equipos de análisis y ciencia de datos.

## 📋 ¿Qué lograrás al completar esta ruta?

- ✅ Diseñar arquitecturas de datos escalables
- ✅ Construir pipelines ETL/ELT robustos
- ✅ Gestionar data lakes y data warehouses
- ✅ Implementar streaming de datos en tiempo real
- ✅ Orquestar workflows complejos de datos
- ✅ Garantizar calidad y governance de datos
- ✅ Trabajar con tecnologías Big Data
- ✅ Aplicar principios de DataOps

---

## 🗓️ Cronograma Detallado

### **Fase 1 (Semana 1-3): Fundamentos y Python Avanzado** 🐍

**Objetivo**: Establecer bases sólidas en programación y automatización para ingeniería de datos.

**📚 Recursos del repositorio:**
- [Python (general)](../1_Fundamentos/Python.pdf)
- [Buenas prácticas en Python](../1_Fundamentos/Buenas_practicas_Python.pdf)
- [Automatización con Python](../1_Fundamentos/Automatizacion_Python.pdf)
- [Testing en Python](../1_Fundamentos/Testing_en_Python.pdf)

**🌐 Recursos complementarios:**
- [Real Python](https://realpython.com) - Python para ingeniería de datos
- [Python Tutor](https://pythontutor.com/) - Debugging avanzado
- [Exercism](https://exercism.org/) - Algoritmos y estructuras de datos

**🎯 Proyectos de la fase:**
- **Semana 1**: Framework de logging y monitoring para scripts
- **Semana 2**: Sistema de configuración dinámico con variables de entorno
- **Semana 3**: CLI avanzado para administración de datos

---

### **Fase 2 (Semana 4-7): Gestión Avanzada de Datos** 🗃️

**Objetivo**: Dominar técnicas de extracción, transformación y carga de datos.

**📚 Recursos del repositorio:**
- [Bases de datos](../2_Gestion_Datos/Bases_de_datos.pdf)
- [Obtención de datos](../2_Gestion_Datos/Obtencion_datos.pdf)
- [Limpieza de datos con Python](../2_Gestion_Datos/Limpieza_datos_Python.pdf)
- [Web Scraping](../2_Gestion_Datos/Web_Scraping.pdf)
- [APIs](../2_Gestion_Datos/APIs.pdf)

**🌐 Recursos complementarios:**
- [dbt](https://www.getdbt.com/) - Transformaciones modernas de datos
- [SQLBolt](https://sqlbolt.com/) - SQL avanzado
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) - Fuentes de datos
- [Public APIs](https://github.com/public-apis/public-apis) - APIs para integración

**🎯 Proyectos de la fase:**
- **Semana 4**: Pipeline ETL con múltiples fuentes de datos
- **Semana 5**: Data warehouse dimensional con dbt
- **Semana 6**: Sistema de web scraping distribuido
- **Semana 7**: API gateway para unificación de datos

---

### **Fase 3 (Semana 8-11): Big Data y Procesamiento Distribuido** 🌐

**Objetivo**: Trabajar con volúmenes masivos de datos usando tecnologías distribuidas.

**📚 Recursos del repositorio:**
- [Python en análisis de datos](../3_Analisis_Visualizacion/Python_Analisis_Datos.pdf)
- [Bash](../6_Desarrollo/Bash.pdf)
- [Docker](../6_Desarrollo/Docker.pdf)
- [Kubernetes](../6_Desarrollo/Kubernetes.pdf)

**🌐 Recursos complementarios:**
- [Apache Spark](https://spark.apache.org/) - Procesamiento distribuido
- [Apache Kafka](https://kafka.apache.org/) - Streaming de datos
- [Apache Airflow](https://airflow.apache.org/) - Orquestación de workflows
- [Hadoop Ecosystem](https://hadoop.apache.org/) - Big Data tools

**🎯 Proyectos de la fase:**
- **Semana 8**: Cluster Spark para procesamiento batch
- **Semana 9**: Pipeline streaming con Kafka y Spark Streaming
- **Semana 10**: Data lake con formato Delta/Iceberg
- **Semana 11**: Orquestación compleja con Airflow

---

### **Fase 4 (Semana 12-15): Cloud y DataOps** ☁️

**Objetivo**: Implementar soluciones de datos en la nube con prácticas DevOps.

**📚 Recursos del repositorio:**
- [CI/CD](../6_Desarrollo/CICD.pdf)
- [Terraform](../6_Desarrollo/Terraform.pdf)
- [DevOps](../6_Desarrollo/DevOps.pdf)
- [Metodología Ágil](../7_Carrera/Metodologia_Agil.pdf)

**🌐 Recursos complementarios:**
- [AWS Data Services](https://aws.amazon.com/big-data/) - S3, Redshift, EMR
- [Google Cloud Data](https://cloud.google.com/products/data-analytics) - BigQuery, Dataflow
- [Azure Data Platform](https://azure.microsoft.com/en-us/products/category/analytics) - Synapse, Data Factory
- [Terraform Registry](https://registry.terraform.io/) - Módulos de datos

**🎯 Proyectos de la fase:**
- **Semana 12**: Data platform en AWS con Terraform
- **Semana 13**: CI/CD para pipelines de datos
- **Semana 14**: Monitoring y alertas para data quality
- **Semana 15**: Multi-cloud data replication strategy

---

### **Fase 5 (Semana 16-18): Proyecto Final Enterprise** 🏢

**Objetivo**: Crear una plataforma completa de datos para una empresa ficticia.

**📚 Recursos del repositorio:**
- [Roadmap to Data Engineer](../5_Roadmaps/Roadmap_Data_Engineer.pdf)
- [Roles en Datos](../7_Carrera/Roles_en_Datos.pdf)

**🎯 Proyecto final:**
Plataforma completa de datos para e-commerce que incluye: ingesta en tiempo real, data lake, data warehouse, ML feature store, APIs de datos y dashboards ejecutivos.

---

## 🛠️ Stack Tecnológico Data Engineering

### Lenguajes y Frameworks:
```python
# Core Programming
python>=3.9
scala
java
sql

# Python Libraries
pandas
numpy
dask
polars
pyspark

# Relational
postgresql
mysql
sqlite

# NoSQL
mongodb
cassandra
redis
elasticsearch

# Analytical
clickhouse
duckdb

# Processing
apache-spark
apache-flink
apache-beam
dask

# Streaming
apache-kafka
apache-pulsar
amazon-kinesis

# Workflow Management
apache-airflow
prefect
dagster
luigi

# Container Orchestration
kubernetes
docker-compose

# AWS
s3, redshift, emr, glue, kinesis

# GCP
bigquery, dataflow, pub/sub, cloud-storage

# Azure
synapse, data-factory, event-hubs, blob-storage