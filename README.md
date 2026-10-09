# Hola, soy Alberto García 👋 · Hi, I'm Alberto García

**Data Engineer** · Costa Rica

🌐 **Portafolio / Portfolio:** [ajg2pro89.github.io](https://ajg2pro89.github.io)

---

### Sobre mí

Ingeniero de datos enfocado en construir pipelines confiables y de bajo costo: ingesta, modelado y lakehouse sobre ecosistemas Microsoft, Databricks y AWS. Me gusta reemplazar infraestructura cara por arquitecturas serverless simples y bien documentadas.

### About me

Data engineer focused on building reliable, low-cost pipelines: ingestion, modeling and lakehouse work across Microsoft, Databricks and AWS ecosystems. I enjoy replacing expensive infrastructure with simple, well-documented serverless architectures.

---

### ⭐ Proyecto destacado · Featured project

#### [canvas-data-2-datalake](https://github.com/AJG2Pro89/canvas-data-2-datalake)

Pipeline serverless que sincroniza **Canvas Data 2** (API DAP de Instructure) hacia un data lake en AWS.
*Serverless pipeline that syncs **Canvas Data 2** (Instructure DAP API) into an AWS data lake.*

```
EventBridge (06:00 UTC) → Step Functions → Lambda ×3 → S3 (Parquet) → Glue Catalog → Athena
```

- 💸 **~$12–15 USD/mes** vs. ~$77 de la arquitectura de referencia con Aurora PostgreSQL · *~$12–15/month vs. ~$77 for the Aurora-based reference architecture*
- 🔁 3 modos de sincronización: `incremental` (upsert/delete), `snapshot`, `append` particionado · *3 sync modes*
- 🧱 `TypeEnforcer` con esquema canónico para evitar `HIVE_BAD_DATA` entre particiones · *canonical schema enforcement*
- ⚙️ Configuración por CSV en S3: agregar tablas sin redeploy · *config-driven, no redeploy needed*
- 🏗️ Infraestructura como código con AWS SAM · *IaC with AWS SAM*

📖 [Caso de estudio completo / Full case study →](https://ajg2pro89.github.io/#project)

---

### 🛠️ Stack

- **Lenguajes / Languages:** Python · PySpark · T-SQL · SQL
- **Datos / Data platforms:** SQL Server · Azure Synapse Analytics · Databricks · Delta Lake · Snowflake
- **ETL / Orquestación:** SSIS · AWS Step Functions · EventBridge
- **Cloud:** Azure · AWS (Lambda, S3, Glue, Athena, SAM)
- **Formatos / Formats:** Parquet · Delta · CSV · JSON
