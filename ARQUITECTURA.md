# ARQUITECTURA DE SYNAP

## Introducción

La arquitectura de Synap se basa en una separación estricta de responsabilidades.

Su objetivo es preservar la continuidad del conocimiento evitando dependencias innecesarias entre almacenamiento, procesamiento, visualización y ejecución.

La arquitectura no se diseña alrededor de aplicaciones concretas.

Se diseña alrededor de funciones.

---

# Principio fundamental

Cada capa debe poder evolucionar o ser sustituida sin comprometer el conocimiento acumulado por el sistema.

La información debe sobrevivir a las herramientas que la gestionan.

---

# Capas del ecosistema

## Almacenamiento

Responsabilidad:

Conservar los datos.

Ejemplos:

- documentos
- fotografías
- registros
- configuraciones
- archivos históricos

Principio:

El almacenamiento constituye la fuente de verdad del ecosistema.

Los datos deben permanecer accesibles independientemente de las aplicaciones utilizadas para gestionarlos.

---

## Procesamiento

Responsabilidad:

Transformar datos en información estructurada.

Ejemplos:

- clasificación
- extracción
- indexación
- análisis
- generación de observaciones

Principio:

El procesamiento modifica la comprensión de los datos, pero no reemplaza la fuente de verdad.

---

## Memoria

Responsabilidad:

Conservar contexto, decisiones y conocimiento acumulado.

Esta capa está representada principalmente por Contextum.

Incluye:

- documentación
- arquitectura
- procedimientos
- aprendizajes
- observaciones históricas

Principio:

La memoria preserva el significado de la información.

---

## Interpretación

Responsabilidad:

Facilitar la exploración y comprensión del conocimiento existente.

Incluye:

- inteligencia artificial
- sistemas conversacionales
- motores de búsqueda
- herramientas de análisis

Principio:

La interpretación ayuda a comprender.

No sustituye a la memoria.

---

## Visualización

Responsabilidad:

Presentar información al usuario.

Ejemplos:

- paneles
- aplicaciones
- interfaces web
- informes

Principio:

La visualización puede cambiar sin alterar el conocimiento subyacente.

---

## Ejecución

Responsabilidad:

Realizar acciones sobre el entorno.

Ejemplos:

- automatizaciones
- control domótico
- flujos operativos
- respuestas del sistema

Principio:

La ejecución debe permanecer separada de la interpretación y de la memoria.

---

# Contextum

Contextum constituye la memoria documental privada de Synap.

Su función es preservar:

- decisiones
- procedimientos
- arquitectura
- conocimiento consolidado

Contextum actúa como continuidad documental del ecosistema.

---

# Atlas

Atlas constituye la representación pública de Synap.

Su función es explicar:

- principios
- arquitectura
- filosofía
- aprendizajes

Atlas no sustituye a Contextum.

Atlas surge a partir de él.

---

# Externalia

Externalia conserva la memoria de las relaciones externas del proyecto.

Incluye:

- comunidades
- contribuciones
- participaciones
- aprendizajes externos

Representa la dimensión pública y comunitaria de Synap.

---

# Resultado

La combinación de estas capas permite que Synap evolucione sin depender de herramientas concretas.

Las aplicaciones pueden cambiar.

Los servicios pueden desaparecer.

La infraestructura puede renovarse.

El objetivo de la arquitectura es que el conocimiento permanezca.