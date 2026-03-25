# Explicación de cambios en CSS y HTML

##  Variables en `:root`

```css
:root {
  --primario: #54239f;
  --primario-oscuro: #29217f;
  --texto: #1f2937;
  --texto-suave: #6b7280;
  --borde: #d1d5db;
  --fondo: #f9fafb;
  --blanco: #ffffff;
  --error: #ef1b1b;
  --exito: #17dd60;
  --radio: 17px;
  --sombra: 0 4px 20px rgba(0,0,0,0.08);
}
```

En esta parte hice varios cambios importantes:

- Cambie el color **primario** a un tono **morado (#54239f)** para darle una apariencia mas moderna
- Cambie el **primario oscuro** a un morado mas intenso (#29217f)
- Agregue la variable `--radio: 17px;` para redondear los bordes y que se vea mas lindo y prolijo 

---

## Campo de edad (HTML)

```html
<!-- Edad -->
<div class="campo">
  <label for="edad">Edad</label>
  <input 
    type="number" 
    id="edad" 
    name="edad"
    placeholder="¿Cuántos años tienes?"
    min="18"
    max="99">
</div>
```

Aqui trabaje con un campo de entrada

- Use `type="number"` para permitir solo numeros
- Añadi un placeholder para guiar al usuario
- Defini un rango entre 18 y 99 años

---

##  Cambios en estilos (CSS)

```css
box-shadow: 0 4px 12px rgba(25, 8, 49, 0.4);
border-color: var(--primario-oscuro);
```

Cambios:

- **box-shadow**: añadi una sombra con tono oscuro para dar profundida
- **border-color**: use el color primario oscuro para mantener el estilo

---

##  Resumen

- Se cambio la paleta a tonos morados
- Se agregaron bordes redondeados (17px)
- Se creo un campo para la edad
- Se añadieron efectos visuales para una mejor apariencia de la pagina
