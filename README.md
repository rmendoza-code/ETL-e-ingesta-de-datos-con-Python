# ETL e Ingesta de Datos con Python

Este proyecto implementa un pipeline ETL (Extract, Transform, Load) completo utilizando Python y Pandas, demostrando buenas prácticas de ingeniería de datos para la manipulación, limpieza y carga de datos desde múltiples fuentes.

---

**Características principales**

- Extracción de datos desde diferentes fuentes (CSV, JSON, Excel, bases de datos SQL)
- Transformación y limpieza de datos utilizando Pandas, incluyendo manejo de valores nulos, normalización y validación
- Carga automatizada a sistemas de almacenamiento (bases de datos relacionales, data warehouses)
- Documentación exhaustiva del proceso ETL y guía de uso
- Gestión de privacidad y seguridad de datos sensibles

---

**Tecnologías utilizadas**

- Python 3.10+
- Pandas
- SQLAlchemy
- PostgreSQL/MySQL
- Docker para entornos reproducibles
- Unit testing con pytest

---

## Estructura del Proyecto

```
ETL-e-ingesta-datos-python/
│
├── data/                  # Datos de entrada y salida (no subir datos sensibles a GitHub)
│   ├── raw/
│   └── processed/
│
├── notebooks/             # Jupyter notebooks para exploración y pruebas
│
├── src/                   # Código fuente del proyecto
│   └── main.py            # Script principal de ETL
│
├── tests/                 # Pruebas unitarias o de integración
│
├── .gitignore             # Archivos y carpetas a ignorar por git
├── requirements.txt       # Dependencias del proyecto
├── README.md              # Documentación principal
└── LICENSE                # (Opcional) Licencia del proyecto
```

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/rmendoza-code/ETL-e-ingesta-de-datos-con-Python.git
   ```
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. Coloca tus archivos de datos en la carpeta `data/raw/`.
2. Ejecuta el script principal:
   ```bash
   python src/main.py
   ```
3. Los resultados procesados se guardarán en `data/processed/`.

## Notebooks

Puedes usar los notebooks en la carpeta `notebooks/` para exploración y pruebas adicionales.

## Pruebas

Incluye tus pruebas en la carpeta `tests/` y ejecútalas con tu framework favorito (por ejemplo, pytest).

## Buenas prácticas recomendadas para el código ETL
- Modulariza el código en funciones y/o clases.
- Utiliza logging para el seguimiento de procesos.
- Maneja errores y excepciones de forma clara.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más información.
