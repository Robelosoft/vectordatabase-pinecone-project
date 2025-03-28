# Vector Database with Pinecone 🚀

[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Pinecone](https://img.shields.io/badge/Powered%20by-Pinecone-6434d3)](https://www.pinecone.io/)

Proyecto de implementación de una base de datos vectorial utilizando Pinecone para búsquedas semánticas y manejo de embeddings.

## 📦 Requisitos

- Python 3.8+
- [Cuenta en Pinecone](https://www.pinecone.io/start/) (API Key gratuita)
- Dependencias:
  ```bash
  pip install -r requirements.txt

🛠️ Configuración
Clona el repositorio:

bash
Copy
git clone https://github.com/Robelosoft/vectordatabase-pinecone-project.git
cd vectordatabase-pinecone-project
Configura tus variables de entorno:

Crea un archivo .env basado en .env.example:

env
Copy
PINECONE_API_KEY=tu_api_key_aquí
PINECONE_ENVIRONMENT=us-east1-gcp
Instala dependencias:

bash
Copy
pip install -r requirements.txt
🚀 Uso
Ejecuta el script principal:

bash
Copy
python main.py
Funcionalidades principales:
✅ Indexado de vectores en Pinecone

✅ Búsqueda semántica

✅ Manejo de embeddings con modelos pre-entrenados

🗂️ Estructura del proyecto
Copy
vectordatabase-pinecone-project/
├── main.py                # Script principal
├── utils.py               # Funciones auxiliares
├── requirements.txt       # Dependencias
├── .env.example           # Plantilla para variables de entorno
└── README.md              # Este archivo
🌟 Características destacadas
Implementación lista para producción

Soporte para múltiples modelos de embeddings

Configuración modular

🤝 Contribuir
¡Las contribuciones son bienvenidas! Por favor:

Haz un fork del proyecto

Crea una rama (git checkout -b feature/nueva-funcionalidad)

Haz commit de tus cambios (git commit -m 'Add some feature')

Haz push a la rama (git push origin feature/nueva-funcionalidad)

Abre un Pull Request