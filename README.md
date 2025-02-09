
# 🔍 RAG Multimodal con Vertex AI Gemini  
Este repositorio contiene la implementación de **Retrieval-Augmented Generation (RAG) Multimodal** utilizando **Vertex AI y la API de Gemini** para la recuperación y generación de contenido enriquecido con inteligencia artificial.  

Este enfoque permite combinar modelos generativos con sistemas de recuperación de información, potenciando la precisión y relevancia de las respuestas en aplicaciones que requieren interacción con texto, imágenes y otros tipos de datos.  

## 📌 Contenido del Repositorio  
El repositorio está organizado en las siguientes carpetas y archivos:  

- 📂 **Notebooks** (`.ipynb`) → Jupyter Notebooks con ejemplos prácticos y pruebas de RAG Multimodal.  
- 📝 **Scripts** (`.py`) → Módulos en Python para procesamiento de datos, consultas a la API de Gemini y funciones auxiliares.  
- 📊 **Datos** (`data/`) → Conjunto de datos de ejemplo para pruebas y evaluación del modelo.  
- 🖼 **Imágenes** (`images/`) → Recursos visuales y capturas de pantalla para documentación.  
- 📄 **Requerimientos** (`requirements.txt`) → Lista de dependencias necesarias para la ejecución del proyecto.  

## 🚀 Instalación y Configuración  
Antes de ejecutar el código, asegúrese de contar con las siguientes herramientas:  

- **Python 3.8+**  
- **Google Cloud SDK**  
- **Jupyter Notebook**  

### 🔧 Instalación de Dependencias  
Ejecute el siguiente comando para instalar las dependencias necesarias:  

```bash
pip install -r requirements.txt
```  

### 🏗 Clonación del Repositorio  
Descargue el código fuente con:  

```bash
git clone https://github.com/Raziel-JM/RAG-multimodal-API-Vertex-AI-Gemini.git  
cd RAG-multimodal-API-Vertex-AI-Gemini  
```  

### 🔑 Configuración de Credenciales en Google Cloud  
Para acceder a **Vertex AI** y la API de **Gemini**, asegúrese de autenticarse correctamente con Google Cloud ejecutando:  

```bash
gcloud auth application-default login  
```  

Si aún no tiene un proyecto en Google Cloud, puede crearlo y habilitar las API necesarias siguiendo la [documentación oficial](https://cloud.google.com/vertex-ai/docs/start).  

## 🖥 Uso del Proyecto  
### 🚀 Ejecución en Local  
Para probar la implementación en su máquina, abra el notebook principal:  

```bash
jupyter notebook intro_multimodal_rag-v1.0.0.ipynb  
```  

### 🌐 Ejecución en Vertex AI Workbench  
Si prefiere ejecutarlo en un entorno administrado en Google Cloud:  

1. Acceda a **Vertex AI Workbench** en la consola de Google Cloud.  
2. Cargue el notebook `intro_multimodal_rag-v1.0.0.ipynb`.  
3. Ejecute las celdas y experimente con consultas multimodales a la API de Gemini.  

## 📚 ¿Qué es RAG Multimodal?  
El **Retrieval-Augmented Generation (RAG) Multimodal** combina modelos de generación de lenguaje con sistemas de recuperación de información de diversas fuentes, incluyendo texto, imágenes y otros datos.  

Este enfoque mejora la precisión de las respuestas generadas al proporcionar contexto relevante extraído de bases de datos, documentos y otros repositorios de información.  

### 🔹 Aplicaciones Clave  
- **Asistentes inteligentes** que combinan texto e imágenes para generar respuestas enriquecidas.  
- **Análisis de contenido** a partir de bases de conocimiento y documentos estructurados.  
- **Búsquedas semánticas** mejoradas con generación de lenguaje natural.  

## 🔗 Recursos y Referencias  
📜 [Documentación de Vertex AI](https://cloud.google.com/vertex-ai/docs)  
🤖 [API de Gemini](https://ai.google.dev/)  
🏗 [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)  
🛠 [Laboratorio de Google Cloud Skills Boost](https://www.cloudskillsboost.google/paths/183/course_templates/981/labs/514649)  
