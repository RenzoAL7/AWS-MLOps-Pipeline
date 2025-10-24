# 🚀 AWS-MLOps-Pipeline

**AWS-MLOps-Pipeline** es un proyecto de *Machine Learning Operations (MLOps)* desarrollado sobre **Amazon Web Services (AWS)**.  
Integra **web scraping**, **procesamiento de datos**, **entrenamiento de modelos de ML** y **despliegue automatizado** usando servicios cloud y serverless
---
## ☁️ Arquitectura general

[Lambda - Web Scraping]
↓
[S3 - Almacenamiento de datos]
↓
[EC2 - Entrenamiento del modelo]
↓
[S3 - Modelos entrenados]
↓
[Lambda + API Gateway - Predicciones]

### 🧩 Servicios AWS utilizados

| Servicio | Rol principal |
|-----------|----------------|
| **AWS Lambda** | Automatiza tareas de scraping y procesamiento ligero de datos. |
| **Amazon S3** | Almacena datasets, resultados procesados y modelos entrenados. |
| **Amazon EC2** | Entrena y evalúa modelos de machine learning. |
| **Amazon API Gateway** | Expone el modelo entrenado mediante una API REST. |
| **AWS CodePipeline / CodeDeploy** | Implementa CI/CD para desplegar automáticamente nuevas versiones. |

---

## 🔄 Flujo MLOps
