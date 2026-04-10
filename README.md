# Sprint-7-Proyecto-Final
# Análisis ConnectaTel 📊

## Objetivo
Analizar el negocio usando los 3 datasets (clientes, uso_real y planes) para que ConnectaTel entienda cómo se comportan sus usuarios según edad, volumen de llamadas/mensajes y nivel de consumo. El entregable será un análisis completo (distribuciones, outliers, segmentación y oportunidades comerciales) acompañado de un notebook limpio y reproducible.

## Datasets utilizados
- plans.csv: Catálogo de planes con sus precios y beneficios.
- users_latam.csv: Información de cada usuario (datos personales, plan, fecha de registro, churn).
- usage.csv: Actividad generada por los usuarios: llamadas, mensajes, duración, longitud. 

## Etapas del análisis
1. Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
2. Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
3. Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
4. Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
5. Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.
6. Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.
7. Documentar todo el proceso en un Jupyter Notebook, junto con un README reproducible para subirlo a GitHub.

## Cómo ejecutar
1. Abre el notebook en Google Colab
2. Carga los tres datasets en la carpeta `/datasets/`
3. Ejecuta las celdas en orden (Runtime → Run All)

## Reproducción
- Python 3.9+
- Librerías: pandas, numpy, matplotlib, seaborn
