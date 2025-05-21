# 📊 Proyecto People Analytics – Simulación de RRHH

Este proyecto tiene como objetivo analizar un dataset simulado de Recursos Humanos, orientado al rol de **Analista de People Analytics**. Se realiza un análisis exploratorio completo, con visualizaciones y conclusiones accionables para apoyar la toma de decisiones en áreas clave como retención de talento, carga laboral y satisfacción de los empleados.

---

## 📁 Contenido del repositorio

- `dataset_rrhh.csv`: base de datos simulada con nombres y condiciones del mercado argentino.
- `notebook_EDA.ipynb`: análisis exploratorio completo con visualizaciones y conclusiones.
- `visualizaciones/`: carpeta opcional para exportar los gráficos generados.
- `dashboard_powerbi.pbix`: tablero interactivo desarrollado en Power BI (en construcción).
- `README.md`: este documento.

---

## 📊 Variables del dataset

El dataset incluye 200 empleados simulados, con las siguientes variables:

- `EmpleadoID`: identificador único (no utilizado en el análisis)
- `Nombre`, `Género`, `Edad`
- `Área`: sector laboral (IT, RRHH, Finanzas, etc.)
- `Antigüedad`: años en la empresa
- `Evaluación_Desempeño`: puntuación de 1 a 5
- `Satisfacción_Laboral`: puntuación de 1 a 5
- `Balance_Vida_Trabajo`: puntuación de 1 a 5
- `Horas_Extra`: 0 = no, 1 = sí
- `Estado_Civil`
- `Salario`: en pesos argentinos
- `Renunció`: variable objetivo (0 = sigue, 1 = renunció)

---

## 🔍 Principales hallazgos

- Áreas como Administracion, IT y Atención al cliente presentan mayor tasa de rotación.
- Empleados con **baja satisfacción laboral y mal balance vida-trabajo** tienen más probabilidades de renunciar.
- Las **horas extra** se relacionan directamente con la intención de abandono.
- El salario no garantiza permanencia si otros factores están deteriorados.
- El **modelo de correlaciones permitió identificar variables críticas** para diseñar un sistema de alerta temprana.

---

## 📈 Herramientas utilizadas

- **Python** (pandas, seaborn, matplotlib)
- **Google Colab** para análisis interactivo
- **Power BI** para visualización ejecutiva (en desarrollo)
- **GitHub** como portafolio técnico

---

## 🚀 Próximos pasos

- Incorporar un modelo predictivo (clasificación binaria) para anticipar renuncias.
- Publicar el dashboard Power BI online (Power BI Service).
- Simular intervenciones y medir su impacto con datos sintéticos.

---

## 💼 Sobre mí

Soy **Natalia Noemí Liscio**, profesional en transición desde Recursos Humanos hacia la Ciencia de Datos. Este proyecto integra mi experiencia de más de 10 años en RRHH con mis actuales estudios en **Data Science, Inteligencia Artificial y People Analytics**.

> Actualmente estoy cursando la Licenciatura en Ciencia de Datos en UniCABA y me encuentro postulada para el puesto de Analista de People Analytics en Swiss Medical.

---

## 📬 Contacto

- GitHub: [NataliaLiscio1985](https://github.com/NataliaLiscio1985)
- Email: natalia.liscio@gmail.com
