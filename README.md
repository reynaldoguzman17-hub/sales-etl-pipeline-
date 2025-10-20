# sales-etl-pipeline-
# Sales ETL Pipeline

![Python](https://img.shields.io/badge/python-v3.9+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 📋 Descripción

Pipeline ETL automatizado que procesa datos de ventas desde archivos CSV, realiza transformaciones y validaciones, y carga los resultados en una base de datos PostgreSQL para análisis posterior.

## 🎯 Objetivos

- Extraer datos de múltiples fuentes (CSV, APIs)
- Limpiar y transformar datos inconsistentes
- Validar calidad de datos
- Cargar datos en base de datos relacional
- Generar reportes automáticos

## 🛠️ Stack Tecnológico

- **Python 3.9+**
- **Pandas** - Manipulación de datos
- **SQLAlchemy** - ORM para base de datos
- **PostgreSQL** - Base de datos
- **pytest** - Testing
- **logging** - Monitoreo

## 📁 Estructura del Proyecto

sales-etl-pipeline/ ├── data/ # Datos raw y procesados ├── src/ # Código fuente ├── notebooks/ # Análisis exploratorio ├── tests/ # Tests unitarios └── config/ # Archivos de configuración

## 🚀 Instalación

### Prerrequisitos
- Python 3.9 o superior
- PostgreSQL instalado
- pip o conda

### Pasos

1. Clonar el repositorio:
```bash
git clone https://github.com/tu-usuario/sales-etl-pipeline.git
cd sales-etl-pipeline
2.	Crear entorno virtual:
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
3.	Instalar dependencias:
pip install -r requirements.txt
4.	Configurar variables de entorno:
cp .env.example .env
# Editar .env con tus credenciales

