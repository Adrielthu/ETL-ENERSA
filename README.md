# 🛠️ Diseño de DW y Visualización de Energía Eléctrica
>[!NOTE]
>El objetivo es aplicar conceptos de modelado de datos, procesos ETL y visualización de información.

> [!IMPORTANT]
> Este proyecto es **ficticio** y no representa datos reales ni está orientado a su uso en producción.

---

## 📌 Descripción General

Se simula el análisis del consumo eléctrico de usuarios de Paraná, Entre Ríos.
Flujo de trabajo:
- Diseño e implementación de base de datos en PosgreSQL de donde se van a extraer inicialmente los datos.
- Generación y carga de datos ficticios a la base de datos previamente implementada.
- Diseño e implementación de Data Warehouse en PostgreSQL.
- ETL para calcular y cargar las métricas en el Data Warehouse.
- Visualización iteractiva de la información.
---

# 📂 Estructura del Proyecto

<details>
<summary> 📁 Estructura </summary>

```
ETL-ENERSA/
│
├── etl                      # Carpeta principal del ETL
│   ├── ETL.py               # Contiene la extracción y carga del DW
│   ├── README.MD            # Documento explicando la configuración
│   └── dimension_utils.py   # Función para actualizar una tabla de dimensión de un DW
├── graficar                 # Esta carpeta contiene la visualización
│   ├── templates            # Páginas html
│   └── graficar.py          # Archivo que genera la página donde se visualiza el dashboard
├── sql                      # Contiene las plantillas HTML para renderizar las vistas
│   ├── DDL-DW.sql           # DDL del respectivo Data Warehouse
│   ├── DDL.sql              # DDL de la base de datos de donde se extraen los mismos
│   └── INSERT.sql           # Archivo para generar y cargar los datos ficticios
└── README.md                # Documento principal de presentación del proyecto
```
</details>

---

## ✍️ Autores

- **Adriel Starchevich**  
  [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adriel-starchevich)

- **Joaquin Frattin**  
  [![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaquinfrattin/)

📍 Paraná, Entre Ríos – Argentina

---
