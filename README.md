
# RAG Multimodal con Vertex AI Gemini
Este repositorio contiene la implementación de **RAG (Retrieval-Augmented Generation) Multimodal** usando **Vertex AI y la API de Gemini**.

## 📌 Contenido
El repositorio incluye los siguientes archivos y carpetas:

- 📂 **Notebooks** (`.ipynb`): Código en Jupyter Notebook para pruebas y desarrollo.
- 📝 **Scripts** (`.py`): Funciones y utilidades en Python para procesamiento de datos y consultas a la API.
- 📊 **Datos** (`data/`): Carpeta con datos de ejemplo para pruebas.
- 🖼 **Imágenes** (`images/`): Capturas y recursos visuales para la documentación.
- 📄 **Requerimientos** (`requirements.txt`): Lista de dependencias necesarias para el entorno de ejecución.

## 🚀 Requisitos
Antes de ejecutar el código, instale las dependencias necesarias ejecutando:

```bash
pip install -r requirements.txt
```

## 🔧 Configuración
Clonar el repositorio:

```bash
git clone https://github.com/Raziel-JM/RAG-multimodal-API-Vertex-AI-Gemini.git
cd RAG-multimodal-API-Vertex-AI-Gemini
```

### Configurar credenciales
Para interactuar con Vertex AI, asegúrese de que tiene autenticación correcta con Google Cloud:

```bash
gcloud auth application-default login
```

## 📖 Uso
Ejecuta el notebook principal con:

```bash
jupyter notebook intro_multimodal_rag-v1.0.0.ipynb
```

Si prefieres ejecutarlo desde un entorno interactivo en **Vertex AI**:

1. Abre **Vertex AI Workbench**.
2. Carga el notebook `intro_multimodal_rag-v1.0.0.ipynb`.
3. Ejecuta las celdas para probar las consultas con la API de Gemini.

## 🔗 Referencias
📜 [Documentación de Vertex AI](https://cloud.google.com/vertex-ai/docs)  
🤖 [API de Gemini](https://ai.google.dev/)  
🏗 [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)

