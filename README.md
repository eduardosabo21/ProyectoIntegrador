# AI Travel Agent: Prototipo de Agente de IA para Reservas de Viajes

Este repositorio contiene el desarrollo de un prototipo de agente de inteligencia artificial diseñado para la automatización de la búsqueda y recomendación de vuelos y hoteles.
El sistema se basa en aprendizaje automático (ML) y utiliza datasets preprocesados de Kaggle para simular la interacción con plataformas de reservas en su fase piloto.

## Descripción del Proyecto
El propósito del AI Travel Agent es asistir a los usuarios en la selección y reserva de viajes con base en criterios personalizados, como destino, fechas, presupuesto y preferencias de alojamiento.
El modelo evalúa diferentes opciones, filtra resultados y presenta las mejores recomendaciones disponibles en los datasets utilizados.

Actualmente, el agente se ejecuta en Google Colab, pero está diseñado para escalabilidad, permitiendo futuras integraciones con APIs de aerolíneas y plataformas de hoteles.

## Estructura del Proyecto
```bash
Copiar
Editar
📁 AI-Travel-Agent
│── 📂 data               # Datasets preprocesados de Kaggle
│── 📂 models             # Modelos entrenados en ML
│── 📂 notebooks          # Notebooks de Google Colab con el código principal
│── 📂 reports            # Documentación y análisis exploratorio de datos (EDA)
│── 📜 README.md          # Documentación del proyecto
│── 📜 requirements.txt   # Librerías necesarias para la ejecución del código
│── 📜 architecture.md    # Especificación detallada de la arquitectura del sistema
```

## Metodología Utilizada
El desarrollo del prototipo sigue la metodología CRISP-ML(Q), que permite estructurar el proceso de machine learning en fases iterativas:

Comprensión del Negocio: Se identificó la necesidad de automatizar la tarea de búsqueda y reserva de viajes en empresas que gestionan asistentes ejecutivas.
Comprensión de los Datos: Se analizaron datasets de Kaggle relacionados con viajes, reservas y preferencias de usuarios.
Preparación de Datos: Se realizó limpieza, transformación y análisis exploratorio de datos (EDA).
Modelado: Se implementaron modelos de machine learning para la generación de recomendaciones optimizadas.
Evaluación: Se probaron los resultados en un entorno controlado, evaluando métricas de precisión y usabilidad.
Despliegue (Futuro): Se plantea la integración con APIs para su implementación en producción.
Tecnologías y Herramientas Utilizadas
Lenguaje de Programación: Python 3.10
Entorno de Desarrollo: Google Colab
Librerías Principales: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Enfoque de Machine Learning: Modelos de recomendación basados en aprendizaje supervisado y ranking
Gestión de Versionamiento: GitHub

## Instalación y Ejecución
Para utilizar este proyecto en local o en Google Colab, siga estos pasos:

Clonar el repositorio

```bash
Copiar
Editar
git clone https://github.com/eduardosabo21/AI-Travel-Agent.git
cd AI-Travel-Agent
Instalar las dependencias
```
```bash
Copiar
Editar
pip install -r requirements.txt
Ejecutar el Notebook

Abrir notebooks/AI_Travel_Agent.ipynb en Jupyter Notebook o en Google Colab y seguir las instrucciones.
Resultados Esperados
Generación de recomendaciones de vuelos y alojamientos optimizados.
Filtrado de opciones con base en preferencias del usuario.
Implementación inicial en un entorno de pruebas con datasets preprocesados.
Posibilidad de escalabilidad mediante integración con APIs de reservas.
```
Consideraciones y Limitaciones

*Fase Piloto: Actualmente, el sistema no está conectado a APIs en vivo. Se utilizan datasets estáticos para entrenar y probar los modelos.

Alcance: Se centra en optimizar la búsqueda y selección de viajes, pero no realiza transacciones en tiempo real.
Escalabilidad: En futuras iteraciones, se podrá conectar con sistemas externos para automatizar completamente el proceso.
Referencias

## Bibliografía
Visengeriyeva, L., Kammer, A., Bär, I., Kniesz, A., & Plöd, M. (2023). CRISP-ML(Q). The ML Lifecycle Process. MLOps. INNOQ. Disponible en: https://ml-ops.org/content/crisp-ml
Kumar Mukhiya, S., & Ahmed, U. (2020). Hands-On Exploratory Data Analysis with Python. Packt Publishing. Disponible en: https://learning.oreilly.com/library/view/hands-on-exploratory-data/9781789537253/

## Datasets Utilizados
Expedia Travel Dataset: https://www.kaggle.com/jacopoferretti/expedia-travel-dataset
Traveler Trip Dataset: https://www.kaggle.com/rkiattisak/traveler-trip-data
Travel Review Dataset: https://www.kaggle.com/wirachleelakiatiwong/travel-review-rating-dataset

