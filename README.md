# 🔍 Automatización de búsqueda de sitios web y correos electrónicos con Python

## Descripción del Proyecto  
Este proyecto aborda el desafío de buscar sitios web y correos electrónicos de empresas con nombres genéricos, muchas de las cuales no tienen página web o solo están presentes en redes sociales. Mediante el uso de Python, APIs y técnicas de scraping, logramos automatizar el proceso, obteniendo un **25% de resultados válidos**.

## 🚀 Funcionalidades  
- **Búsqueda automática de sitios web** utilizando la API de Google Custom Search.
- **Extracción de correos electrónicos** desde páginas web relevantes.
- **Guardado de resultados** en un archivo Excel para facilitar su análisis posterior.

## 🛠 Tecnologías utilizadas  
- **Python**: Lenguaje principal para la automatización.  
- **Librerías**:  
  - `pandas`: Lectura y escritura de archivos Excel.  
  - `requests`: Realización de solicitudes HTTP.  
  - `re`: Uso de expresiones regulares para extraer correos electrónicos.  
- **Google Custom Search API**: Herramienta para encontrar sitios web relevantes.

## 📝 Desafíos y resultados  
- **Desafíos**:  
  - Nombres de empresas muy genéricos que dificultaban encontrar sitios relevantes.  
  - Falta de presencia web o páginas estructuradas para scraping.  
- **Resultado final**: Un **25% de resultados válidos**, destacando la importancia de los datos de entrada para el éxito del proceso.

## 📂 Estructura del Proyecto  
├── Buscar_Empresas.xlsx # Archivo de entrada con nombres y tipos de empresas. 
├── Resultado_Emails.xlsx # Archivo de salida con los resultados. 
├── main.py # Script principal. 
├── README.md # Este archivo.

## ⚙ Cómo ejecutar el proyecto  
## 1. Clona este repositorio:  
   
   git clone https://github.com/saharaqc/ExtratEmailPython.git
   
## 2. Instala las dependencias necesarias
 !pip install pandas requests

## 3. Configura las claves de la API de Google en el script:
api_key: Tu clave de Google Cloud Console.
cx: ID de tu motor de búsqueda personalizado.

## 4. Ejecuta el script:
python main.py

## 5. Revisa los resultados en el archivo resultado_final.xlsx.

## 📊 Contribuciones:
¡Siempre son bienvenidas! Si tienes ideas para mejorar el proyecto, no dudes en abrir un issue o enviar un pull request.

## 🌟 Inspiración:

Este proyecto refleja la importancia de la automatización en tareas repetitivas y cómo incluso un pequeño porcentaje de éxito puede aportar valor significativo en proyectos con grandes volúmenes de datos.
