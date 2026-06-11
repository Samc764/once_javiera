# 📚 Resumen: Documentación, IEEE 830, Casos de Uso y Revisión

---

# 1. 📄 ¿Por qué documentar?

## 📖 Importancia
Documentar requerimientos significa **registrarlos por escrito** para evitar pérdida de información y malentendidos.

## 🧠 Memoria vs documentación

| 🧠 En la mente | 📜 Documentado |
|----------------|----------------|
| Se olvida rápido | Permanece en el tiempo |
| Solo una persona lo sabe | Todo el equipo lo conoce |
| No es verificable | Es auditable |
| Cambia fácilmente | Es estable |
| No sirve como evidencia | Sirve como respaldo legal |

## 💥 Problemas de no documentar
- Pérdida de conocimiento si alguien se va.
- Malentendidos con el cliente.
- Retrabajo costoso.
- Problemas legales y auditorías fallidas.

## 🎯 Funciones de la documentación
- 🤝 Acuerdo entre cliente y equipo.
- 🗺️ Guía para desarrolladores.
- 🧪 Base para pruebas.
- 📚 Memoria del proyecto.
- ⚖️ Evidencia legal.

## 📊 Nivel de documentación según contexto
- Startup → mínima.
- Empresa media → intermedia.
- Gobierno/banca → completa y formal.
- Sistemas críticos → trazabilidad total.

---

# 2. 📘 IEEE 830 (SRS)

## 📖 ¿Qué es?
El **IEEE 830** es un estándar que define cómo escribir un **SRS (Software Requirements Specification)**.

👉 SRS = documento maestro de requerimientos.

## 🎯 Objetivo
Permitir que cualquier ingeniero entienda el sistema de forma clara y universal.

## 📑 Estructura del SRS

1. 📌 Introducción  
2. 📊 Descripción general  
3. 📋 Requisitos específicos  
4. 📎 Apéndices  

## ✨ Características de un buen SRS
- Correcto
- No ambiguo
- Completo
- Consistente
- Priorizado
- Verificable
- Modificable
- Trazable

---

# 3. 🎭 Casos de Uso

## 📖 Definición
Un caso de uso describe una **historia paso a paso** de cómo un usuario interactúa con el sistema.

## 🔄 Requerimiento vs Caso de uso

| Requerimiento | Caso de uso |
|--------------|-------------|
| Qué hace | Cómo ocurre |
| Frase corta | Historia completa |

## 🧩 Elementos
- 🎭 Actor: quien usa el sistema.
- 🎯 Objetivo: lo que quiere lograr.
- ⚙️ Sistema: software.
- 📜 Escenario: pasos de interacción.

## 🔗 Relaciones UML
- `include` → obligatorio
- `extend` → opcional

---

# 4. 📋 Plantilla de Caso de Uso

## 📑 Estructura
- 🏷️ ID
- 📛 Nombre
- 🎭 Actor
- 📝 Descripción
- ✅ Precondiciones
- 🎯 Postcondiciones
- ▶️ Flujo principal
- 🔀 Flujos alternos
- ⚠️ Excepciones
- 📜 Reglas de negocio
- 📊 Frecuencia
- ⭐ Prioridad

## ⚠️ Errores comunes
- Escribir como manual de usuario.
- Mezclar actor y sistema.
- Olvidar excepciones.
- Ser demasiado general o demasiado detallado.

---

# 5. ✍️ Levantamiento de Casos de Uso

## 🧠 Ejemplo general
Sistema de inscripción a torneos escolares.

## 📌 Elementos clave
- Validación de requisitos.
- Flujo de inscripción.
- Confirmaciones.
- Notificaciones.

---

# 6. 📑 SRS IEEE por secciones

## 📌 Sección 1: Introducción
- Propósito del sistema
- Alcance
- Definiciones
- Referencias
- Visión general

## 📌 Sección 2: Descripción general
- Contexto del sistema
- Usuarios
- Restricciones
- Dependencias

## 📌 Sección 3: Requisitos específicos
- RF (funcionales)
- RNF (no funcionales)
- Interfaces externas
- Casos de uso

## 📌 Sección 4: Apéndices
- Diagramas
- Glosario
- Trazabilidad

## 🔑 Importancia de IDs
- RF-001, RNF-001, CU-001
- Permiten trazabilidad
- Facilitan pruebas
- Mejoran organización

---

# 7. 🔎 Revisión cruzada

## 📖 Definición
Proceso donde otro analista revisa el documento para detectar errores.

## 🎯 Qué se busca
- Ambigüedades
- Contradicciones
- Faltantes
- Falta de métricas
- No atómicos
- Jerga técnica
- No verificables

## 📐 Proceso
1. Leer completo
2. Marcar errores
3. Discutir con autor
4. Corregir y revalidar

---

# 🎯 Ideas clave finales

- Documentar evita pérdidas de conocimiento.
- IEEE 830 estandariza los SRS.
- Casos de uso explican el comportamiento paso a paso.
- Un SRS debe ser claro, completo y verificable.
- Todo requerimiento debe tener ID y trazabilidad.
- La revisión cruzada mejora la calidad del documento.
- Un buen documento sobrevive al equipo y al tiempo.
```