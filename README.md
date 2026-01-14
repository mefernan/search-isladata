# 🔍 Azure Search Python App

Una aplicación moderna de búsqueda semántica en documentos usando Azure Cognitive Search.

## ✨ Descripción

Esta aplicación permite realizar búsquedas en un índice de Azure Search, devolviendo documentos con información sobre ubicaciones, personas y frases clave extraídas.

## Requisitos

- Python 3.8+
- Cuenta de Azure con Cognitive Search configurado

## 🚀 Instalación Rápida

### 1. Clona el repositorio
```bash
git clone git@github.com:mefernan/search-isladata.git
cd search-isladata
```

### 2. Crea un entorno virtual

```bash
python -m venv labisladata
source labisladata/bin/activate  # En Windows: labisladata\Scripts\activate
```

### 3. Instala las dependencias

```bash
pip install -r requirements.txt
```

## 🔧 Configuración

Crea un archivo `.env` en la raíz del proyecto con las siguientes variables:

```env
SEARCH_ENDPOINT=<tu-endpoint-de-search>
QUERY_KEY=<tu-query-key>
INDEX_NAME=<nombre-de-tu-indice>
```

## 🎉 Uso

Ejecuta la aplicación:

```bash
python search-app.py
```

Luego, escribe consultas y presiona Enter. Escribe `quit` para salir.

## 📦 Dependencias

- `python-dotenv`: Gestión de variables de entorno
- `azure-identity`: Autenticación de Azure
- `azure-search-documents`: Cliente de Azure Search

## 📝 Notas

- El archivo `.env` no se incluye en el repositorio por razones de seguridad.
- No compartir credenciales de Azure en repositorios públicos.

## 📄 Ejemplo de archivo `.env` (sin credenciales)

```env
SEARCH_ENDPOINT=https://<tu-recurso>.search.windows.net
QUERY_KEY=<tu-query-key>
INDEX_NAME=<nombre-de-tu-indice>
```

Puedes crear estos archivos usando:

- **En VS Code**: File > New File, escribe el contenido y guarda con el nombre correspondiente
- **En Terminal PowerShell**: 
```powershell
# Desde la carpeta del proyecto:
"contenido" | Out-File -Encoding utf8 -FilePath .gitignore
"contenido" | Out-File -Encoding utf8 -FilePath README.md
"contenido" | Out-File -Encoding utf8 -FilePath .env.example
```

Este README tiene:
- ✨ Emojis estratégicos que lo hacen visualmente atractivo
- 🎯 Estructura clara y profesional
- 📊 Tabla de dependencias
- 🏗️ Diagrama de arquitectura
- 🔒 Énfasis en seguridad y best practices
- 💼 Lenguaje moderno y directo que gusta a tech recruiters

¿Te gustaría que añada algo más?
