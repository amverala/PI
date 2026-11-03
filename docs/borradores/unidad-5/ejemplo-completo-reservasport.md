# Ejemplo completo · ReservaSport

Este es el apartado **5. Estudio de viabilidad y recursos** completo del proyecto de ejemplo ReservaSport, tal y como podría aparecer en una memoria. Úsalo como referencia, no como molde: tu proyecto tendrá sus propios recursos, cifras y condiciones.

---

## 5. Estudio de viabilidad y recursos

### 5.1. Recursos necesarios

| Tipo | Recurso | Para qué | ¿Disponible? | Coste |
|--------|--------|--------|--------|:-----:|
| Humano | Autor del proyecto (125 h) | Desarrollo y documentación | Sí | Valorado en el apartado 5.3 |
| Humano | Dos responsables de instalaciones pequeñas | Entrevistas y pruebas | Sí (colaboración voluntaria) | 0 € |
| Material | Portátil | Desarrollo | Sí | Amortización |
| Material | Móvil personal | Pruebas de uso desde móvil | Sí | 0 € |
| Software | Editor de código, control de versiones y base de datos | Desarrollo | Sí (libre o gratuito) | 0 € |
| Software | Herramienta de prototipos | Bocetos de pantallas | Sí (plan gratuito) | 0 € |
| Servicio | Alojamiento | Publicar el MVP para las pruebas | No | 5 €/mes |
| Servicio | Dominio | Dirección propia de la aplicación | No | 12 €/año |
| Información | Documentación oficial y guías de la AEPD | Desarrollo y cumplimiento legal | Sí | 0 € |

El **alojamiento** es el recurso crítico: sin él no se pueden realizar las pruebas con usuarios reales.

---

### 5.2. Viabilidad técnica y temporal

**Viabilidad técnica**

| Funcionalidad | Tecnología | ¿La domino? | Riesgo | Qué haré |
|--------|--------|--------|--------|--------|
| Registro e inicio de sesión | Lenguaje y framework del ciclo | Poca experiencia con sesiones | Medio | Prototipo previo |
| Consulta de disponibilidad | Consultas SQL | Sí | Bajo | — |
| Evitar reservas duplicadas | Restricciones de la base de datos | Parcialmente | Medio | Prueba específica |
| Uso desde el móvil | Diseño adaptable | Sí | Bajo | Probar en un móvil real |

*Conclusión técnica:* viable, con un punto a vigilar: la gestión de sesiones.

**Viabilidad temporal**

| Concepto | Horas |
|--------|:-----:|
| Horas del plan (apartado 3) | 104 |
| Prototipo previo (acción CAME, apartado 4) | 6 |
| **Horas necesarias** | **110** |
| Horas disponibles (47 días laborables × 2,5 h/día) | ≈ 117 |
| **Margen real** | **≈ 7** |

*Conclusión temporal:* viable pero ajustado. El margen real es inferior al previsto en la planificación, por lo que se hará un seguimiento semanal y, si el margen baja de 3 horas, se simplificará la cancelación de reservas.

---

### 5.3. Viabilidad económica

*Datos ilustrativos, basados en los supuestos indicados.*

**Inversión inicial**

| Concepto | Cálculo | Coste |
|--------|--------|:-----:|
| Mano de obra simulada | 125 h × 15 €/h | 1.875 € |
| Amortización del portátil | 800 € ÷ 48 meses × 2 meses | ≈ 33 € |
| Software | Libre o con plan gratuito | 0 € |
| **Total** | | **≈ 1.908 €** |

**Costes recurrentes anuales:** alojamiento (60 €) y dominio (12 €), 72 € en total.

**Beneficio.** Supuestos: el personal administrativo dedica unos 90 minutos diarios a gestionar reservas por teléfono y la aplicación los reduce a 30; el coste del personal es de 12 €/h y hay 220 días laborables al año.

- Ahorro anual: 1 h × 220 días × 12 €/h = 2.640 €.
- Beneficio neto anual: 2.640 € − 72 € = 2.568 €.

**Periodo de recuperación**

| Escenario | Beneficio neto anual | Recuperación |
|--------|:-----:|:-----:|
| Base | 2.568 € | Unos 9 meses |
| Prudente (ahorro a la mitad) | 1.248 € | Unos 18 meses |

*Conclusión económica:* viable. Incluso en el escenario prudente la inversión se recupera en menos de dos años. El coste monetario real para el autor es de unos 105 €.

---

### 5.4. Viabilidad legal

| Aspecto | Afecta | Medida |
|--------|--------|--------|
| Datos personales | Nombre, correo y teléfono de los usuarios | Recoger solo esos tres datos, informar de su uso y guardar las contraseñas cifradas (RGPD y LOPDGDD). |
| Cookies | Sesión de usuario | Usar solo cookies técnicas; no usar cookies de seguimiento. |
| Licencias | Software y recursos gráficos | Usar software libre y recursos con licencia que lo permita, citando la procedencia. |
| Accesibilidad | Destinado a instalaciones municipales (sector público) | Tomar como objetivo WCAG 2.1 de nivel AA (Real Decreto 1112/2018). |

Durante el desarrollo y las pruebas se utilizarán **datos ficticios**.

*Conclusión legal:* viable. Los datos tratados son mínimos y están justificados.

---

### 5.5. Conclusión de viabilidad

| Dimensión | Valoración | Motivo principal |
|--------|:--:|--------|
| Técnica | 🟡 | La gestión de sesiones es la parte menos conocida. |
| Temporal | 🟡 | El margen real (7 h) es menor que el previsto. |
| Económica | 🟢 | Recuperación en unos 9 meses (18 en el escenario prudente). |
| Legal | 🟢 | Tres datos personales, justificados y protegidos. |

**Dictamen: el proyecto es viable con condiciones.**

**Condiciones**

1. Realizar un prototipo de inicio de sesión antes de empezar el desarrollo.
2. Revisar el avance cada semana con el tablero Kanban y simplificar la cancelación de reservas si el margen baja de 3 horas.
3. Mantener los datos recogidos en nombre, correo y teléfono.

**Decisión:** se continúa con el proyecto aplicando estas condiciones, que ya están reflejadas en el plan de trabajo y en las acciones CAME.

---

## ¿Qué hace bien este ejemplo?

✅ Parte de los datos de las unidades anteriores (horas, acciones CAME, alcance).

✅ Cada conclusión se apoya en una cifra o en un dato verificable.

✅ Compara horas necesarias con disponibles y reconoce que el margen es menor que el previsto.

✅ Explica los supuestos de los beneficios y calcula un escenario prudente.

✅ Aplica medidas legales concretas, como la minimización de datos.

✅ Emite un dictamen claro, con condiciones comprobables.

---

## Plantilla rápida del apartado 5

```text
5. Estudio de viabilidad y recursos

5.1. Recursos necesarios
[Tabla de recursos + recursos críticos]

5.2. Viabilidad técnica y temporal
[Tabla técnica + horas necesarias, disponibles y margen real]

5.3. Viabilidad económica
[Inversión, costes anuales, beneficios con supuestos, recuperación]

5.4. Viabilidad legal
[Tabla de aspectos y medidas]

5.5. Conclusión de viabilidad
[Cuadro resumen + dictamen + condiciones + decisión]
```

---

## Entregable de la unidad

!!! abstract "Actividad final · Apartado 5 de tu memoria"

    Redacta el apartado **5. Estudio de viabilidad y recursos** de tu proyecto, con las cinco secciones (5.1 a 5.5), a partir de lo trabajado en las unidades 2, 3 y 4.

### Qué debes entregar

- Texto del apartado 5 completo, en Markdown.
- Tabla de recursos con disponibilidad y coste.
- Cálculo de horas necesarias, disponibles y margen real.
- Cálculo económico con supuestos y periodo de recuperación.
- Tabla de aspectos legales con medidas.
- Cuadro resumen y dictamen de viabilidad.

### Criterios de evaluación

- [ ] El inventario de recursos es completo y señala los críticos.
- [ ] Las horas necesarias coinciden con mi planificación y mis acciones CAME.
- [ ] El margen real se calcula con horas disponibles realistas.
- [ ] Los costes y beneficios tienen supuestos explicados.
- [ ] Incluyo un escenario prudente.
- [ ] Las medidas legales son concretas y pertinentes para mi proyecto.
- [ ] El dictamen se apoya en datos y tiene condiciones comprobables.
- [ ] El texto está bien redactado, sin copiar el ejemplo.

!!! warning "Importante"

    Las cifras de ReservaSport son ilustrativas. Copiarlas no demuestra que hayas estudiado la viabilidad de **tu** proyecto: usa tus propias horas, tus propios costes y tus propios supuestos.

---

## Resumen de la unidad

!!! success "Qué debes recordar"

    ✅ El estudio de viabilidad comprueba con datos si el proyecto se puede hacer.

    ✅ Primero se inventarían los recursos; después se valoran la viabilidad técnica, temporal, económica y legal.

    ✅ Las horas necesarias deben compararse con las disponibles reales y el margen debe calcularse.

    ✅ Los beneficios necesitan supuestos explicados, y conviene calcular un escenario prudente.

    ✅ El dictamen puede ser viable, viable con condiciones o no viable tal como está.

---

## Próximos pasos

En la **Unidad 6** reunirás todos los apartados en la memoria final: revisarás su coherencia, redactarás la introducción, las conclusiones y la bibliografía, y prepararás la defensa.
