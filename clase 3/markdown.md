# 📚 Resumen: Elicitación, Levantamiento de Información y Viabilidad

---

# 1. 🧠 Elicitación de Requerimientos

## Definición
La **elicitación** es el proceso de descubrir y extraer las necesidades reales de clientes y usuarios para transformarlas en requerimientos formales.

> Elicitar ≠ Recolectar
>
> El analista participa activamente para descubrir necesidades, incluso aquellas que el cliente no expresa explícitamente.

## El analista como detective
Un buen analista:
- Observa.
- Escucha activamente.
- Hace preguntas.
- Conecta información.
- Busca causas y problemas reales.

### Problema del iceberg
Lo que el cliente expresa es solo una parte del problema:

- 🧊 Lo que dice.
- 💭 Lo que piensa pero no expresa.
- 🌊 Lo que hace automáticamente sin ser consciente.

## Habilidades necesarias
- 👂 Escucha activa.
- ❓ Curiosidad.
- 🤐 Saber guardar silencio.
- 🪞 Empatía.
- 📝 Tomar notas.
- 🚫 No asumir.

---

# 2. 💬 Entrevistas

## Definición
Conversación estructurada entre analista y stakeholder para obtener información relevante.

## Tipos de entrevistas

### 📋 Estructurada
- Preguntas definidas previamente.
- Orden fijo.
- Fácil comparación de respuestas.

**Ventajas**
- Datos consistentes.

**Desventajas**
- Poca flexibilidad.

### 🗣️ No estructurada
- Conversación libre.
- Sin guion rígido.

**Ventajas**
- Descubre información inesperada.

**Desventajas**
- Difícil de analizar.

### ⭐ Semi-estructurada
- Preguntas guía.
- Posibilidad de profundizar.

**Ventajas**
- Equilibrio entre estructura y flexibilidad.

## Etapas de la entrevista

### Antes
- Investigar el contexto.
- Definir objetivos.
- Preparar preguntas.
- Programar reunión.

### Durante
- Romper el hielo.
- Explicar el propósito.
- Hacer preguntas abiertas.
- Profundizar con preguntas de sondeo.
- Tomar notas.

### Después
- Organizar notas.
- Detectar requerimientos potenciales.
- Registrar dudas.
- Agradecer al participante.

## Tipos de preguntas

### 🌍 Abiertas
Buscan explicación.

Ejemplo:
> ¿Cómo realiza actualmente este proceso?

### 🎯 Cerradas
Buscan datos específicos.

Ejemplo:
> ¿Cuántos empleados trabajan aquí?

### 🔍 De sondeo
Profundizan una respuesta previa.

Ejemplo:
> ¿Podría darme un ejemplo?

## Errores comunes
- Asumir respuestas.
- Interrumpir.
- Hacer preguntas demasiado técnicas.
- Sugerir respuestas.
- No tomar notas.

---

# 3. 📊 Encuestas

## Definición
Instrumento para recolectar información de muchas personas de forma rápida.

## Cuándo utilizarlas
- Muchos usuarios.
- Participantes dispersos.
- Datos cuantitativos.
- Validar hipótesis.
- Necesidad de anonimato.

## Cuándo evitarlas
- Temas complejos.
- Pocos stakeholders clave.
- Necesidad de profundidad.

## Tipos de preguntas

### Selección única
Ejemplo:
- Estudiante
- Profesor
- Administrativo

### Selección múltiple
Permite varias opciones.

### Escala Likert
Mide opiniones o actitudes.

Ejemplo:

| Valor | Significado |
|---------|------------|
| 1 | Muy en desacuerdo |
| 5 | Muy de acuerdo |

### Numéricas
Ejemplo:
> ¿Cuántos minutos espera en la fila?

### Abiertas cortas
Ejemplo:
> ¿Qué mejoraría?

## Buenas prácticas
- Máximo 10-15 preguntas.
- Lenguaje claro.
- Una idea por pregunta.
- Evitar jerga técnica.
- Comenzar con preguntas sencillas.
- Probar antes de publicar.

## Errores frecuentes
### Dos ideas en una pregunta
❌ ¿La app es rápida y fácil de usar?

### Sugerir respuestas
❌ ¿No cree que la app es excelente?

### Jerga técnica
❌ ¿Prefiere OAuth o JWT?

---

# 4. 👀 Observación

## Definición
Consiste en observar a los usuarios realizando sus actividades reales para descubrir necesidades y problemas.

## Ventaja principal
Permite conocer:

> Lo que las personas hacen realmente, no solo lo que dicen que hacen.

## Tipos de observación

### 🪞 Directa
Observador pasivo.

### 🎬 Participante
El analista participa en el trabajo.

### 🌐 Etnográfica
Observación profunda durante largos períodos.

### 🎥 Shadowing
Seguir y registrar las actividades de una persona.

## Qué observar
- Flujo de trabajo.
- Herramientas utilizadas.
- Interacciones.
- Tiempos.
- Atajos.
- Frustraciones.
- Errores.
- Comunicación informal.

## Registro recomendado

| Hora | Persona | Actividad | Observación |
|--------|---------|------------|-------------|
| 09:00 | Cajera | Abre caja | Busca información en un cuaderno |

## Efecto Hawthorne
Las personas modifican su comportamiento cuando saben que están siendo observadas.

Para reducirlo:
- Observar varios días.
- Mantener perfil bajo.
- Complementar con entrevistas.

---

# 5. 📋 Levantamiento de Información

## Proceso recomendado

### 1. Investigación previa
- Revisar documentos.
- Entender el negocio.

### 2. Entrevistas iniciales
- Obtener visión general.

### 3. Observación
- Analizar procesos reales.

### 4. Encuestas
- Validar hallazgos.
- Obtener datos masivos.

### 5. Consolidación
- Resolver contradicciones.
- Crear requerimientos formales.

## Caso Biblioteca Escolar

### Stakeholders
- Bibliotecarios.
- Estudiantes.
- Profesores.
- Rector.

### Hallazgos

#### Entrevistas
- Problemas para localizar libros.
- Falta de estadísticas.

#### Observación
- Filas largas.
- Procesos lentos.

#### Encuestas
- Deseo de reservas móviles.
- Notificaciones.
- Consulta de disponibilidad.

### Conversión a requerimientos

#### Hallazgo
> Los estudiantes quieren reservar libros.

#### RF
> El sistema deberá permitir reservar libros desde una aplicación móvil.

#### Hallazgo
> El préstamo tarda 5 minutos.

#### RNF
> El registro de préstamos deberá completarse en menos de 60 segundos.

## Triangulación
Consiste en combinar:
- Entrevistas.
- Observación.
- Encuestas.

Esto aumenta la confiabilidad de los resultados.

---

# 6. ⚖️ Análisis de Viabilidad

## Definición
Proceso para determinar si un requerimiento puede implementarse de forma realista.

## Dimensiones de viabilidad

### 🛠️ Técnica
Preguntas:
- ¿Existe la tecnología?
- ¿El equipo tiene conocimientos?

### 💰 Económica
Preguntas:
- ¿Existe presupuesto?
- ¿Vale la pena la inversión?

### 👥 Operativa
Preguntas:
- ¿Los usuarios lo aceptarán?
- ¿Encaja en los procesos actuales?

### 📜 Legal
Preguntas:
- ¿Cumple las leyes?
- ¿Respeta la protección de datos?

### ⏱️ Temporal
Preguntas:
- ¿Puede desarrollarse en el tiempo disponible?

## Semáforo de viabilidad

### 🟢 Alta
Proyecto viable.

### 🟡 Media
Requiere renegociar alcance, tiempo o presupuesto.

### 🔴 Baja
No es viable en su estado actual.

## Objetivos
- Evitar proyectos imposibles.
- Detectar riesgos tempranamente.
- Asesorar al cliente.
- Tomar decisiones informadas.

---

# 🎯 Conceptos Clave

- La elicitación busca descubrir necesidades reales.
- El analista actúa como investigador o detective.
- Las entrevistas permiten profundidad.
- Las encuestas permiten alcance masivo.
- La observación revela comportamientos reales.
- Las técnicas deben combinarse (triangulación).
- Los hallazgos deben transformarse en RF y RNF.
- Todo requerimiento debe evaluarse en términos de viabilidad:
  - Técnica
  - Económica
  - Operativa
  - Legal
  - Temporal
- Decir "no es viable" a tiempo es parte del trabajo profesional del analista.