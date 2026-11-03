# Ejemplo completo · ReservaSport

Este es el apartado **4. Análisis DAFO y CAME** completo del proyecto de ejemplo ReservaSport, tal y como podría aparecer en una memoria. Úsalo como referencia, no como molde: tu proyecto tendrá sus propios factores y acciones.

---

## 4. Análisis DAFO y CAME

### 4.1. Análisis interno

**Fortalezas**

- **F1.** El alcance del MVP está acotado a tres funcionalidades esenciales y es realista para el tiempo disponible.
- **F2.** Los usuarios y sus necesidades están definidos con claridad en el apartado 2.
- **F3.** El plan de trabajo incluye un margen del 20 % para imprevistos.

**Debilidades**

- **D1.** Poca experiencia desarrollando una aplicación completa.
- **D2.** Dedicación limitada, de 2 a 3 horas diarias.
- **D3.** Trabajo individual, sin posibilidad de repartir tareas.

---

### 4.2. Análisis externo

**Oportunidades**

- **O1.** Muchas instalaciones deportivas pequeñas aún gestionan las reservas por teléfono o en papel.
- **O2.** Existen herramientas y documentación gratuitas y bien mantenidas.
- **O3.** Los usuarios están acostumbrados a reservar servicios por internet.

**Amenazas**

- **A1.** Existen aplicaciones de reservas consolidadas, aunque de pago.
- **A2.** La normativa de protección de datos obliga a tratar con cuidado la información personal.
- **A3.** Parte de los usuarios tiene poca soltura con herramientas digitales.

La competencia se ha revisado analizando tres aplicaciones existentes, todas basadas en suscripción y orientadas a grandes instalaciones.

---

### 4.3. Matriz DAFO

|  | **Ayuda** | **Perjudica** |
|--------|--------|--------|
| **Interno** | **Fortalezas**<br>F1. Alcance acotado<br>F2. Usuarios definidos<br>F3. Plan con margen | **Debilidades**<br>D1. Poca experiencia<br>D2. Poco tiempo diario<br>D3. Trabajo individual |
| **Externo** | **Oportunidades**<br>O1. Reservas aún manuales<br>O2. Herramientas gratuitas<br>O3. Hábito de reservar online | **Amenazas**<br>A1. Apps consolidadas<br>A2. Protección de datos<br>A3. Poca soltura digital |

**Estrategias derivadas del cruce**

| Tipo | Cruce | Estrategia |
|--------|--------|--------|
| FO | F1 + O1 | Centrar el MVP en instalaciones pequeñas que aún reservan por teléfono. |
| FO | F2 + O3 | Diseñar la interfaz siguiendo los hábitos de reserva online que ya conocen. |
| FA | F1 + A2 | Recoger únicamente los datos personales imprescindibles. |
| FA | F2 + A3 | Diseñar pantallas muy sencillas validadas con usuarios reales. |
| DO | D1 + O2 | Apoyarse en documentación y tutoriales gratuitos y elegir tecnologías conocidas. |
| DA | D2 + A1 | No competir en funciones: mantener el alcance sin ampliaciones. |

---

### 4.4. Estrategias y plan de acción (CAME)

| Tipo | Factor | Acción | Cuándo | Cómo sabré que está hecha |
|--------|--------|--------|--------|--------|
| **C**orregir | D1 | Hacer un prototipo con inicio de sesión y una consulta a la base de datos. | Antes de T4 | Prototipo funcionando. |
| **A**frontar | A2 | Recoger solo nombre, correo y teléfono, justificando cada campo. | En T2 | Lista de campos justificada. |
| **M**antener | F1 | No añadir funcionalidades fuera del MVP. | Todo el proyecto | Ninguna tarea fuera del alcance. |
| **E**xplotar | O1 | Entrevistar a dos instalaciones pequeñas para validar los requisitos. | En T1 | Dos entrevistas realizadas. |

**Reflejo en la planificación.** La acción de corregir D1 se incorpora al plan como una tarea adicional de 6 horas antes de T4, que se descuentan del margen del 20 %. La acción de explotar O1 se integra en la tarea T1 de requisitos. El resto no modifica el calendario.

---

## ¿Qué hace bien este ejemplo?

✅ Los factores son concretos y propios del proyecto.

✅ Distingue bien lo interno de lo externo.

✅ Incluye debilidades y amenazas reales, no solo virtudes.

✅ Cada estrategia nombra los factores que cruza.

✅ Cada acción CAME responde a un factor, tiene plazo y un criterio de finalización.

✅ Las acciones se reflejan en la planificación de la unidad 3.

---

## Plantilla rápida del apartado 4

```text
4. Análisis DAFO y CAME

4.1. Análisis interno
[Fortalezas y debilidades con códigos]

4.2. Análisis externo
[Oportunidades y amenazas con códigos + fuentes]

4.3. Matriz DAFO
[Matriz + estrategias derivadas de los cruces]

4.4. Estrategias y plan de acción (CAME)
[Tabla de acciones + reflejo en la planificación]
```

---

## Entregable de la unidad

!!! abstract "Actividad final · Apartado 4 de tu memoria"

    Redacta el apartado **4. Análisis DAFO y CAME** de tu proyecto, con las cuatro secciones (4.1 a 4.4), a partir de lo trabajado en las unidades 2 y 3.

### Qué debes entregar

- Texto del apartado 4 completo, en Markdown.
- Matriz DAFO con factores codificados.
- Al menos cuatro estrategias derivadas del cruce (una de cada tipo).
- Tabla de acciones CAME con plazo e indicador.
- Tu plan de la unidad 3 actualizado si alguna acción lo modifica.

### Criterios de evaluación

- [ ] Los factores son concretos y propios de mi proyecto.
- [ ] Distingo correctamente lo interno de lo externo.
- [ ] Incluyo debilidades y amenazas reales.
- [ ] He investigado la competencia y cito qué he consultado.
- [ ] Las estrategias nombran los factores que cruzan.
- [ ] Las acciones CAME son concretas, realistas y comprobables.
- [ ] Las acciones están reflejadas en mi planificación.
- [ ] El texto está bien redactado, sin copiar el ejemplo.

!!! warning "Importante"

    El ejemplo de ReservaSport es una referencia. Un DAFO que valdría igual para cualquier proyecto no demuestra que hayas analizado **el tuyo**.

---

## Resumen de la unidad

!!! success "Qué debes recordar"

    ✅ El DAFO separa lo interno (fortalezas y debilidades) de lo externo (oportunidades y amenazas).

    ✅ Un buen factor es concreto, verificable y propio de tu proyecto.

    ✅ La matriz se cruza para obtener estrategias FO, FA, DO y DA.

    ✅ El CAME convierte el análisis en acciones: corregir, afrontar, mantener y explotar.

    ✅ Las acciones deben ser realistas y reflejarse en el plan de trabajo.

---

## Próximos pasos

En la **Unidad 5** estudiarás la viabilidad de tu proyecto. El diagnóstico que has hecho aquí te dará buenos argumentos para justificar si es viable y bajo qué condiciones.
