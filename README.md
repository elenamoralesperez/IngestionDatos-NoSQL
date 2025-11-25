# 💧 Ingestión de Datos: NiFi & 🍃 NoSQL
Este repositorio reúne mis apuntes teóricos, plantillas (templates) y flujos de datos (Data Pipelines) creados con Apache NiFi para practicar la ingestión, transformación y enrutamiento de información automatizada. Además, incluye una sección dedicada a bases de datos NoSQL (MongoDB) para la gestión y consulta de datos semi-estructurados.

## 📚 Contenido
### 1. Apache NiFi
### 📘 Teoría / Conceptos Clave
Arquitectura NiFi: Conceptos de FlowFile, Processor y Connections.

Gestión de Flujo: Organización mediante Process Groups y uso de Input/Output Ports.

Ciclo de vida del dato: Trazabilidad con Data Provenance y Lineage.

Configuración: Uso de Controller Services y Contexts.

Lenguaje de Expresiones: Manipulación dinámica de atributos (Expression Language).

Docker: Despliegue de la arquitectura y persistencia de volúmenes en contenedores.

### 🧪 Ejercicios Prácticos
Ingestión de Datos:

- Consumo de APIs externas (InvokeHTTP).

- Lectura de archivos locales (GetFile).

Transformación:

- División de contenido (SplitText, SplitJson).

- Modificación de atributos (UpdateAttribute).

- Manipulación de contenido y limpieza (ReplaceText).

Enrutamiento:

- Filtrado de datos con lógica condicional (RouteOnAttribute).

Salida:

- Guardado final de archivos en disco (PutFile).

### 2. NoSQL (MongoDB)
### 📘 Teoría
Fundamentos NoSQL: Diferencias con SQL, escalabilidad y flexibilidad de esquemas.

Estructura de Datos: Colecciones (Collection) y Documentos (Document).

Sintaxis JSON/BSON: Formato de datos y tipos específicos (ISODate, ObjectId).

Operadores de Consulta: Uso de selectores de comparación ($gt, $lt, $eq) y lógicos.

### 🧪 Ejercicios Prácticos (Dataset: Vuelos)
Consultas de Búsqueda (find).

Consultas de rangos temporales y numéricos.

Manipulación de Objetos Anidados:

Uso de Dot Notation para acceder a sub-documentos (ej. live.altitude).

Filtrado basado en estados lógicos (ej. vuelos active).

Conteo de registros y documentos (countDocuments).
