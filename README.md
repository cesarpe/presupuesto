## Calculadora de presupuesto
Calcula el presupuesto diario para gastar

---
### 1. Límite por Día Original

* **Definición:** Es el presupuesto teóricamente ideal que puedes gastar por día al inicio del mes, calculado de forma estática.
* **Cómo se calcula:**

$$\text{Límite Original} = \frac{\text{Total Ingresos Fijos} - \text{Total Gastos Fijos} - \text{Ahorro Objetivo}}{\text{Total de días del mes}}$$


* **Para qué sirve:** Te marca la pauta o meta base constante que deberías intentar seguir cada día para cumplir exactamente con tu objetivo de ahorro mensual sin tocar tus obligaciones fijas.

---

### 2. Promedio Gastado/Día

* **Definición:** Es la velocidad real a la que estás consumiendo tu dinero en lo que va del mes. Muestra cuánto estás gastando en promedio por cada día transcurrido.
* **Cómo se calcula:**

$$\text{Promedio Gastado} = \frac{\text{Suma total de gastos diarios registrados hasta hoy}}{\text{Días transcurridos del mes}}$$


* **Para qué sirve:** Te permite auditar tu comportamiento financiero. Si este número es mayor que tu *Límite por Día Original*, significa que estás gastando más rápido de lo planeado.

---

### 3. Restante Real por Día

* **Definición:** Es tu presupuesto diario dinámico y actualizado. Es el monto exacto que puedes gastar **por día durante lo que queda del mes**, tomando en cuenta el dinero que ya gastaste o que "ahorraste" en los días anteriores.
* **Cómo se calcula:**

$$\text{Restante Real} = \frac{(\text{Disponible Inicial} - \text{Gastos Diarios Acumulados hasta hoy})}{\text{Días que faltan por transcurrir en el mes (incluyendo hoy)}}$$


* **Para qué sirve:** Es la métrica más útil del día a día. Se adapta automáticamente:
* Si hoy gastaste menos de tu límite, el sistema redistribuye ese sobrante y **aumenta** ligeramente tu presupuesto para los días siguientes.
* Si te excediste, el sistema **reduce** automáticamente tu cuota diaria restante para obligarte a compensar y llegar a fin de mes sin romper tu meta de ahorro.
