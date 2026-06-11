# 📚 Resumen: Requerimientos y Atributos de Calidad

## 1. Concepto de Requerimiento

### Definición
Un **requerimiento** es una propiedad documentada que un sistema debe cumplir para resolver un problema o alcanzar un objetivo.

**Características clave:**
- 📄 Documentado
- ✅ Verificable

### Niveles de abstracción
1. **Necesidad del usuario**
   - "Quiero saber qué hay de comida."
2. **Requerimiento del sistema**
   - "El sistema debe mostrar el menú del día."
3. **Especificación técnica**
   - "La API debe responder en menos de 300 ms."

### Fuentes de requerimientos
- Usuarios finales
- Clientes o patrocinadores
- Leyes y regulaciones
- Sistemas externos

### Cualidades de un buen requerimiento
- Necesario
- No ambiguo
- Verificable
- Consistente
- Completo
- Atómico (una sola idea)
- Trazable

---

# 🔧 Requerimientos Funcionales (RF)

## ¿Qué son?
Describen **qué hace el sistema**.

### Cómo identificarlos
Buscar:
- Verbos de acción (registrar, mostrar, enviar, validar, calcular)
- Entradas y salidas
- Reglas de decisión
- Roles de usuario

### Plantilla
> El sistema deberá + acción + objeto + condición.

### Ejemplos
- Permitir iniciar sesión.
- Mostrar el menú del día.
- Calcular promedios.
- Generar reportes PDF.
- Enviar correos de confirmación.

### Categorías
- 🔐 Autenticación
- 📊 Cálculos
- 💾 Persistencia (CRUD)
- 📨 Comunicación
- 📑 Reportes
- ✅ Validaciones

---

# ⚙️ Requerimientos No Funcionales (RNF)

## ¿Qué son?
Describen **cómo debe funcionar el sistema**.

### Diferencia principal

| RF | RNF |
|----|----|
| Qué hace | Cómo lo hace |

### Categorías principales

#### ⚡ Rendimiento
- Tiempo de respuesta
- Uso de recursos

Ejemplo:
> Responder consultas en menos de 2 segundos.

#### 🔒 Seguridad
- Cifrado
- Autenticación
- Control de acceso

Ejemplo:
> Contraseñas almacenadas con bcrypt.

#### 👍 Usabilidad
- Facilidad de aprendizaje y uso

#### 🛡️ Confiabilidad
- Disponibilidad
- Recuperación ante fallos

#### 📈 Escalabilidad
- Soportar crecimiento de usuarios

#### 🔧 Mantenibilidad
- Facilidad de modificación y pruebas

#### 📱 Compatibilidad / Portabilidad
- Funcionamiento en múltiples plataformas

#### 📜 Cumplimiento legal
- Protección de datos
- Normativas vigentes

### Regla de oro
Todo RNF debe ser:
- Medible
- Verificable
- Con un umbral definido

### Trade-offs comunes
- Seguridad ↔ Usabilidad
- Rendimiento ↔ Mantenibilidad
- Escalabilidad ↔ Costos

---

# 💎 Atributos de Calidad (ISO/IEC 25010)

## ¿Qué son?
Características generales que determinan la calidad del software.

### Relación con los RNF
- **Atributo de calidad:** concepto general.
- **RNF:** implementación medible del atributo.

Ejemplo:
- Atributo: Seguridad.
- RNF: Bloquear cuenta tras 5 intentos fallidos.

### Los 8 atributos de calidad

1. ✅ Adecuación funcional
2. ⚡ Eficiencia de desempeño
3. 🔗 Compatibilidad
4. 👍 Usabilidad
5. 🛡️ Confiabilidad
6. 🔒 Seguridad
7. 🔧 Mantenibilidad
8. 📦 Portabilidad

---

# 🧩 Caso Práctico: SchoolEats

## Problemas detectados
- Filas largas en cafetería.
- Menú desconocido hasta llegar.
- Comida insuficiente.
- Pagos únicamente en efectivo.
- Mala planificación de producción.

## Stakeholders
- 🎓 Estudiantes
- 👨‍🍳 Cafetería
- 🎩 Rector
- 👪 Padres
- 💼 Entidades regulatorias

## Técnicas de levantamiento

| Stakeholder | Técnica |
|------------|----------|
| Estudiantes | Encuestas + Focus Group |
| Cocineros | Observación + Entrevistas |
| Rector | Entrevista estructurada |
| Padres | Encuestas digitales |

## Necesidades identificadas

### Estudiantes
- Consultar menú.
- Reservar almuerzo.
- Pagar desde la app.
- Recibir notificaciones.

### Cafetería
- Estimar demanda.
- Visualizar pedidos.

### Rector
- Obtener reportes.
- Garantizar disponibilidad.

### Padres
- Recargar saldo.
- Consultar historial de consumo.

---

# 📋 Ejemplos de Requerimientos

## Funcionales
- Mostrar menú del día.
- Reservar almuerzos.
- Procesar pagos.
- Generar reportes PDF.

## No Funcionales
- Disponibilidad mínima del 99.5%.
- Tiempo de respuesta menor a 2 segundos.
- Compatibilidad con iOS, Android y web.

---

# 🎯 Conceptos Clave para Recordar

- Un requerimiento debe ser **documentado y verificable**.
- Los **RF** describen **qué hace** el sistema.
- Los **RNF** describen **cómo debe hacerlo**.
- Todo RNF debe incluir métricas y criterios de validación.
- Los requerimientos deben ser **atómicos**.
- Los atributos de calidad están definidos por **ISO/IEC 25010**.
- El analista transforma necesidades informales en requerimientos formales y verificables.
- Los atributos más importantes para SchoolEats son:
  - 🛡️ Confiabilidad
  - 👍 Usabilidad
  - 🔒 Seguridad