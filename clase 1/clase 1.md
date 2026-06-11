# Resumen: Introducción al Análisis y Diseño de Software

## 1. Importancia del análisis y el diseño

Antes de programar es necesario comprender el problema y planificar la solución.

### Análisis
Define **qué** se va a construir:
- Quiénes usarán el sistema.
- Qué necesidades tienen.
- Qué información manejará.
- Qué restricciones existen.

### Diseño
Define **cómo** se va a construir:
- Arquitectura del sistema.
- Módulos y comunicación entre ellos.
- Tecnologías a utilizar.
- Diseño de la interfaz.

### Idea clave
> El análisis define QUÉ se construye.  
> El diseño define CÓMO se construye.  
> La programación es el último paso.

### Regla 1-10-100
El costo de corregir errores aumenta según la etapa:
- Análisis: $1
- Diseño: $10
- Programación: $100
- Producción: $1000+

### Conclusión
La principal causa del fracaso de proyectos de software son los requerimientos mal definidos.

---

# 2. Ciclo de Vida del Software

El software pasa por varias etapas desde su creación hasta su reemplazo.

## Fases

### 1. Análisis de Requerimientos
- Identificación de necesidades.
- Documentación de requisitos.

**Resultado:** Especificación de Requerimientos.

### 2. Diseño
- Definición de arquitectura.
- Diagramas y prototipos.

**Resultado:** Planos del sistema.

### 3. Implementación
- Desarrollo del código.

**Resultado:** Software funcional.

### 4. Pruebas
- Detección y corrección de errores.

**Resultado:** Sistema validado.

### 5. Despliegue
- Entrega y puesta en producción.

**Resultado:** Sistema operativo para usuarios.

### 6. Mantenimiento
- Corrección de fallos.
- Incorporación de mejoras.

**Resultado:** Nuevas versiones del software.

### Idea clave
El proceso suele ser cíclico, ya que los cambios generan nuevas necesidades y reinician el ciclo.

---

# 3. Metodologías Estructuradas

Se basan en una planificación detallada desde el inicio.

## Modelo Cascada
Fases secuenciales:

Análisis → Diseño → Programación → Pruebas → Despliegue

### Ventajas
- Fácil de gestionar.
- Documentación completa.
- Requisitos bien definidos.

### Desventajas
- Poco flexible.
- Cambios costosos.
- El cliente ve el resultado al final.

## Modelo en V
Relaciona cada fase de desarrollo con una fase de pruebas correspondiente.

### Ventaja
Permite planificar la validación desde el inicio.

## Modelo Espiral
Desarrollo iterativo basado en la gestión de riesgos.

### Características
- Desarrollo por ciclos.
- Reducción progresiva de incertidumbre.

### Cuándo usar metodologías estructuradas
- Sistemas críticos.
- Proyectos regulados.
- Requisitos estables.
- Necesidad de alta previsibilidad.

---

# 4. Metodologías Ágiles

Surgen para responder a cambios constantes durante el desarrollo.

## Manifiesto Ágil (2001)

Valores principales:

- Personas e interacciones sobre procesos y herramientas.
- Software funcionando sobre documentación extensa.
- Colaboración con el cliente sobre contratos.
- Adaptación al cambio sobre seguir un plan rígido.

## Iteración

Se desarrolla en ciclos cortos que incluyen:
- Análisis.
- Diseño.
- Programación.
- Pruebas.
- Entrega.

## Scrum

### Roles
- Product Owner.
- Scrum Master.
- Equipo de desarrollo.

### Elementos principales
- Sprints (1 a 4 semanas).
- Reuniones diarias.
- Demostraciones.
- Retrospectivas.

## Kanban

Utiliza un tablero visual:

- Por hacer
- Haciendo
- Probando
- Hecho

Objetivo:
- Controlar el flujo de trabajo.
- Limitar tareas simultáneas.

## XP (Extreme Programming)

Prácticas principales:
- Programación en pares.
- Desarrollo guiado por pruebas (TDD).
- Refactorización constante.
- Entregas frecuentes.

### Cuándo usar metodologías ágiles
- Startups.
- Aplicaciones móviles.
- Productos digitales.
- Entornos con cambios frecuentes.

---

# 5. Comparación entre metodologías

| Aspecto | Estructuradas | Ágiles |
|----------|--------------|---------|
| Planificación | Completa al inicio | Continua |
| Cambios | Costosos | Bienvenidos |
| Documentación | Amplia | Mínima necesaria |
| Participación del cliente | Al final | Constante |
| Equipo ideal | Grande y especializado | Pequeño y multifuncional |
| Riesgos | Se detectan tarde | Se detectan temprano |
| Ejemplos | Cascada, V, Espiral | Scrum, Kanban, XP |

### Regla práctica
- Sistemas críticos → Metodologías estructuradas.
- Productos innovadores → Metodologías ágiles.

---

# 6. Requerimientos

## Definición

Un requerimiento es una descripción de:
- Lo que el sistema debe hacer.
- Las restricciones que debe cumplir.

Son la traducción de las necesidades del cliente a especificaciones técnicas.

---

## Tipos de requerimientos

### Funcionales
Definen qué hace el sistema.

Ejemplos:
- Registrar usuarios.
- Generar reportes.
- Procesar pagos.

### No funcionales
Definen cómo debe comportarse el sistema.

Ejemplos:
- Tiempo de respuesta.
- Disponibilidad.
- Seguridad.
- Compatibilidad.

---

## Características de un buen requerimiento (SMART)

- **Specific:** Específico.
- **Measurable:** Medible.
- **Achievable:** Alcanzable.
- **Relevant:** Relevante.
- **Time-bound:** Con plazo definido.

### Ejemplo

❌ Malo:
> El sistema debe ser rápido.

✅ Bueno:
> El sistema debe responder en menos de 2 segundos para el 95% de las solicitudes.

---

## Obtención de requerimientos

Técnicas principales:

- Entrevistas.
- Encuestas.
- Observación.
- Talleres.
- Revisión documental.
- Prototipos.

---

## Cambios en los requerimientos

Los requerimientos suelen cambiar durante el proyecto.

### Enfoques

**Metodologías estructuradas**
- Intentan minimizar los cambios mediante planificación detallada.

**Metodologías ágiles**
- Asumen que los cambios son inevitables y se adaptan continuamente.

---

# Ideas clave finales

- El análisis identifica el problema.
- El diseño planifica la solución.
- Los requerimientos son la base del proyecto.
- Existen requerimientos funcionales y no funcionales.
- Los requerimientos deben ser SMART.
- Las metodologías estructuradas priorizan la planificación.
- Las metodologías ágiles priorizan la adaptación al cambio.
- Detectar errores temprano reduce significativamente los costos.