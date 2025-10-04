# Reto 2 - Next Gen Coding - Módulo 2

Este repositorio contiene el desarrollo del **Reto 2** del curso Next Gen Coding, enfocado en la construcción de sistemas de orquestación y generación asistida de código para aplicaciones modernas, utilizando IA generativa y buenas prácticas de arquitectura.

## Notebooks principales

### 1. [`Reto_2_LLM_Diseño_Arquitectura.ipynb`](https://github.com/caviedesjoaquin/next-gen-coding-modulo2/blob/main/Reto_2_LLM_Disen%CC%83o_Arquitectura.ipynb)

**Objetivo:**  
Diseñar la arquitectura de un sistema CRUD para la gestión de identidad digital de usuarios y análisis de incidentes urbanos, utilizando metodologías de IA generativa (LangChain, GPT-5) y Chain-of-Thought (CoT).

**Contenido:**
- Instalación y configuración de entorno y dependencias.
- Uso de Few-Shot Prompts y metodología CREATE para obtener diseños de arquitectura óptimos.
- Generación de la estructura de proyecto, definición de componentes (backend, frontend, base de datos, contenerización).
- Ejemplos y artefactos de cada componente (archivos de código, Dockerfiles, `requirements.txt`, etc.).
- Guía rápida de ejecución local y con Docker Compose.
- Puntos fuertes, debilidades y mejoras propuestas para la arquitectura.

### 2. [`Reto_2_Automatización.ipynb`](https://github.com/caviedesjoaquin/next-gen-coding-modulo2/blob/main/Reto_2_Automatizacio%CC%81n.ipynb)

**Objetivo:**  
Orquestar y automatizar la generación de código para cada etapa del desarrollo usando IA generativa y pipelines con LangChain.

**Contenido:**
- Pruebas y orquestación de cadenas para generación asistida de modelos, backend, frontend y despliegue.
- Modelos de configuración Pydantic para estructuras de datos (usuarios, incidentes).
- Uso avanzado de LangChain para generación de modelos Pydantic con validaciones, docstrings y constraints robustos.
- Generación automática de routers FastAPI completos y empresariales, con CRUD, paginación y seguridad.
- Ejemplo de integración y ejecución de pipelines completos para generación de código profesional.

## ¿Cómo usar este repositorio?

1. Clona el repositorio y instala las dependencias indicadas en los notebooks.
2. Sigue el flujo propuesto en `Reto_2_LLM_Diseño_Arquitectura.ipynb` para entender la lógica y la estructura recomendada.
3. Ejecuta `Reto_2_Automatización.ipynb` para probar la generación y orquestación automática de componentes y funcionalidades.
4. Revisa los artefactos generados y adapta los ejemplos para tus propios proyectos.

## Requisitos

- Python 3.11+ recomendado.
- Acceso a una API Key de OpenAI para ejecutar prompts generativos.
- Docker y Docker Compose para pruebas de contenerización.
- Revisa los archivos `requirements.txt` y las instrucciones dentro de cada notebook para dependencias específicas.

## Créditos

Desarrollado por [caviedesjoaquin](https://github.com/caviedesjoaquin) para Next Gen Coding Módulo 2.

---
**Licencia:** MIT

```
