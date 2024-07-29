# Análisis de Rendimiento Estudiantil y Predicción de Notas

## Índice
<details>
<summary>Descripción del Proyecto</summary>

Este proyecto tiene como objetivo analizar el rendimiento de los estudiantes en una institución educativa y desarrollar un modelo predictivo para identificar los factores que influyen en las notas finales. El dataset proporcionado incluye datos históricos sobre actividades académicas, como exámenes, entregas de tareas y fechas importantes. La variable objetivo es la `nota_final_materia`, donde una nota mayor o igual a 5 indica la aprobación del curso.

Las tareas incluyen:
- **Análisis Exploratorio de Datos (EDA)**: Examinar el dataset para detectar inconsistencias, valores nulos y obtener estadísticas descriptivas.
- **Ingeniería de Características**: Crear nuevas características a partir de los datos existentes y evaluar su impacto en modelos predictivos.
- **Desarrollo y Evaluación de Modelos Predictivos**: Comparar múltiples modelos predictivos, como regresión y árboles de decisión, y optimizarlos usando técnicas avanzadas.
- **Presentación del Modelo Final**: Seleccionar el mejor modelo basado en métricas de rendimiento y justificar su elección.

</details>

<details>
<summary>Instrucciones de Instalación</summary>

Para ejecutar los notebooks y scripts de este proyecto, sigue estos pasos:

1. **Clona el Repositorio**
   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   cd nombre-del-repositorio
Crea un Entorno Virtual (opcional, pero recomendado)

bash
Copiar código
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
Instala las Dependencias

bash
Copiar código
pip install -r requirements.txt
Ejecuta los Notebooks

Abre Jupyter Notebook:
bash
Copiar código
jupyter notebook
Navega hasta la carpeta notebooks/ y abre los notebooks 01_EDA.ipynb, 02_feature_engineering.ipynb, y 03_modeling.ipynb para ver el análisis, la ingeniería de características y el modelado, respectivamente.
</details>
<details>
<summary>Estructura del Proyecto</summary>
data/: Carpeta que contiene los datos.

raw/: Datos originales sin procesar.
processed/: Datos que han sido limpiados y procesados para el análisis.
notebooks/: Carpeta con los notebooks de Jupyter.

01_EDA.ipynb: Análisis exploratorio de datos.
02_feature_engineering.ipynb: Creación y evaluación de nuevas características.
03_modeling.ipynb: Desarrollo y evaluación de modelos predictivos.
scripts/: Carpeta con scripts Python para procesamiento y modelado.

preprocessing.py: Scripts para la limpieza y procesamiento de datos.
feature_engineering.py: Scripts para la creación de nuevas características.
modeling.py: Scripts para el entrenamiento y evaluación de modelos.
reports/: Carpeta con informes y visualizaciones.

figures/: Gráficos y visualizaciones generados durante el análisis.
requirements.txt: Archivo que lista las dependencias del proyecto.

</details>
<details>
<summary>Resultados y Conclusiones</summary>
Análisis Exploratorio de Datos: Se identificaron varios valores nulos e inconsistencias en el dataset, lo que llevó a la limpieza y el procesamiento de los datos para asegurar su calidad.

Ingeniería de Características: Se crearon nuevas características basadas en el análisis de datos, como days_until_due, que mejoraron la capacidad predictiva de los modelos.

Modelos Predictivos: Se compararon varios modelos, incluyendo regresión logística y árboles de decisión. El modelo final seleccionado mostró un buen desempeño en términos de precisión y otras métricas, lo que indica que es capaz de predecir con alta exactitud la probabilidad de aprobación de los estudiantes.

</details>
