# Remote Work & Mental Health Analysis

Este proyecto explora cómo el trabajo remoto, híbrido y presencial impacta en la salud mental de los empleados. Analizamos variables como el estrés, el aislamiento social y la satisfacción laboral usando el dataset sintético [Remote Work & Mental Health](https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health), disponible en Kaggle.

## Objetivo del Proyecto
El objetivo es comprender las tendencias y patrones en el bienestar emocional y la satisfacción laboral en un entorno laboral moderno, donde el trabajo remoto tiene un papel fundamental. Esto incluye:
- Evaluar cómo las modalidades de trabajo afectan los niveles de estrés.
- Investigar la relación entre el aislamiento social y la satisfacción laboral.
- Identificar patrones y tendencias que puedan mejorar el diseño de políticas laborales.

---

## Proceso del Análisis

1. **Limpieza de Datos:**
   - Identificación y tratamiento de valores nulos usando técnicas como la imputación con la moda.
   - Preparación de los datos para asegurar análisis confiables y consistentes.

2. **Análisis Exploratorio de Datos (EDA):**
   - Visualizaciones como gráficos de barras y cajas para analizar patrones en niveles de estrés, aislamiento social y satisfacción laboral según la modalidad de trabajo.

3. **Preguntas Exploratorias:**
   - ¿Qué modalidad de trabajo está asociada con menores niveles de estrés?
   - ¿Existe una relación entre el aislamiento social y la satisfacción laboral en trabajadores remotos?

4. **Resultados Clave:**
   - La modalidad de trabajo no es el único factor determinante en el bienestar emocional; variables como el rol laboral y el equilibrio trabajo-vida también influyen.
   - No se encontraron diferencias significativas en los niveles de aislamiento social entre modalidades de trabajo.

---

## Cómo Reproducir este Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/remote-work-analysis.git

2. Instala las dependencias necesarias:
    ```bash
    pip install -r requirements.txt

3. Ejecuta los notebooks en la carpeta notebooks/ para reproducir el análisis:

- eda_remote_work.ipynb: Limpieza de datos y análisis exploratorio.


### Dataset
Nombre: Remote Work & Mental Health

Fuente: Kaggle - Dataset Link

Descripción: Datos sintéticos que simulan patrones reales relacionados con modalidades de trabajo y bienestar emocional.

### Herramientas Utilizadas
Python: Lenguaje principal para el análisis.

Pandas: Manipulación y limpieza de datos.

Seaborn y Matplotlib: Creación de visualizaciones.

Jupyter Notebooks: Documentación y análisis interactivo.