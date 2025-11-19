# 💧 NiFi – Apuntes y Trabajo

Este repositorio reúne mis apuntes teóricos, plantillas (`templates`) y flujos de datos (Data Pipelines) creados con **Apache NiFi** para practicar la ingestión, transformación y enrutamiento de información automatizada.

## 📚 Contenido

### 📘 Teoría / Conceptos Clave

* **Arquitectura NiFi:** FlowFile, Processor y Connections.
* **Gestión de Flujo:** Process Groups, Input/Output Ports.
* **Ciclo de vida del dato:** Data Provenance y Lineage.
* **Configuración:** Controller Services y Contexts.
* **Lenguaje de Expresiones:** Manipulación dinámica de atributos.
* **Docker:** Despliegue y persistencia de volúmenes en contenedores.

### 🧪 Procesadores / Ejercicios Prácticos

* **Ingestión de Datos:**
    * Consumo de APIs externas (`InvokeHTTP`).
    * Lectura de archivos locales (`GetFile`).
* **Transformación:**
    * División de contenido (`SplitText`, `SplitJson`).
    * Modificación de atributos (`UpdateAttribute`).
    * Manipulación de contenido (`ReplaceText`).
* **Enrutamiento:**
    * Filtrado de datos (`RouteOnAttribute`).
    * Control de flujo y esperas.
* **Salida:**
    * Guardado de archivos (`PutFile`).
