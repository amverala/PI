# Viabilidad legal

!!! warning "Nota importante"

    Esta página tiene finalidad educativa: te ayuda a identificar qué normas pueden afectar a tu proyecto. No es asesoramiento jurídico. En un proyecto real conviene consultar a un profesional y a las fuentes oficiales, como la Agencia Española de Protección de Datos (AEPD).

## ¿Qué se comprueba?

La viabilidad legal responde a una pregunta: **¿puede mi proyecto funcionar cumpliendo las normas que le afectan?**

No hace falta ser abogado. Se trata de identificar las normas relevantes y decidir qué medidas tomas.

---

## Los cuatro aspectos habituales en un proyecto web

| Aspecto | Qué normas o criterios entran en juego |
|--------|--------|
| **Datos personales** | RGPD (Reglamento UE 2016/679) y LOPDGDD (Ley Orgánica 3/2018). |
| **Cookies y servicios web** | LSSI (Ley 34/2002). |
| **Licencias** | Licencias del software y de los recursos que uses. |
| **Accesibilidad** | Real Decreto 1112/2018 si el proyecto es del sector público. |

---

## Datos personales

Si tu aplicación guarda nombres, correos, teléfonos o cualquier dato de una persona, trata **datos personales**.

### Medidas básicas

| Principio | Qué significa en tu proyecto |
|--------|--------|
| **Minimización** | Recoge solo los datos imprescindibles para la finalidad. Si no los necesitas, no los pidas. |
| **Información** | El usuario debe saber qué datos se recogen, para qué y quién es el responsable. |
| **Seguridad** | Guarda las contraseñas cifradas y protege el acceso a los datos. |
| **Derechos** | El usuario puede pedir acceder a sus datos, corregirlos o eliminarlos. |

!!! tip "Ayuda gratuita"

    La AEPD ofrece guías y herramientas gratuitas para ayudar a cumplir la normativa, pensadas incluso para quien no tiene conocimientos legales.

!!! info "Menores de edad"

    Si tu proyecto trata datos de menores, la protección es mayor. En España, los menores de 14 años necesitan el consentimiento de sus padres o tutores para el tratamiento de sus datos.

### En las pruebas, datos ficticios

Mientras desarrollas y pruebas, usa **datos inventados**. Así no expones datos reales de nadie.

---

## Cookies y aviso legal

Si tu web usa cookies que no son estrictamente necesarias (por ejemplo, de analítica o publicidad), hay que informar al usuario y pedir su consentimiento. Si te limitas a las técnicas necesarias para el funcionamiento (como la sesión), el requisito es menor.

!!! tip "Decisión de diseño"

    Una forma sencilla de reducir obligaciones es no usar cookies de seguimiento ni analítica en tu MVP.

---

## Licencias

### Software

Casi todo el software que usas tiene una licencia. Las licencias libres (como MIT o GPL) permiten usarlo, pero con condiciones distintas. Revisa que lo que uses permita tu uso y apunta cuáles son.

### Imágenes, iconos y fuentes

Que algo esté en internet no significa que puedas usarlo. Usa recursos con licencia que lo permita (por ejemplo, ciertas licencias Creative Commons) y cita la autoría cuando se exija.

!!! warning "Error frecuente"

    Copiar imágenes de buscadores sin comprobar su licencia.

---

## Accesibilidad

Si tu proyecto está destinado al **sector público** (ayuntamientos, centros educativos públicos...), la normativa española obliga a que sus sitios web y aplicaciones sean accesibles. El Real Decreto 1112/2018 transpone una directiva europea y toma como referencia las pautas WCAG 2.1 de nivel AA.

Aunque tu proyecto no sea público, aplicar esas pautas es una buena práctica: contrastes suficientes, textos alternativos en las imágenes, uso con teclado, etiquetas en los formularios.

---

## Caso práctico 1 · Biblioteca escolar

| Aspecto | Afecta | Medida |
|--------|--------|--------|
| Datos personales | Nombre y curso del alumnado, historial de préstamos | Recoger solo los necesarios. Atención especial por ser menores. |
| Menores | Parte del alumnado es menor de 14 años | Contar con el consentimiento de las familias o gestionarlo a través del centro. |
| Accesibilidad | Centro público | Seguir WCAG 2.1 nivel AA como objetivo. |

## Caso práctico 2 · Gestión de incidencias

| Aspecto | Afecta | Medida |
|--------|--------|--------|
| Datos personales | Nombre del docente que avisa | Limitarlo al nombre y no recoger más. |
| Cookies | Sesión de usuario | Usar solo cookies técnicas de sesión. |
| Licencias | Iconos de la interfaz | Usar un conjunto de iconos con licencia libre. |

---

## Actividad 1 · ¿Es un dato personal?

Indica cuáles son datos personales:

1. Correo electrónico de un usuario.
2. Nombre de una instalación deportiva.
3. Teléfono de contacto.
4. Número de reservas totales del mes.

??? success "Solución orientativa"

    Son datos personales el 1 y el 3. El 2 es un dato de un lugar, no de una persona, y el 4 es un dato agregado que no identifica a nadie.

---

## Actividad 2 · Minimiza los datos

Un formulario de registro pide: nombre, apellidos, DNI, fecha de nacimiento, dirección postal, correo, teléfono y profesión. La aplicación solo sirve para reservar pistas deportivas.

¿Qué datos mantendrías?

??? success "Solución orientativa"

    Nombre, correo (para el acceso y los avisos) y, si hace falta, teléfono. El resto no es necesario para la finalidad, así que no debe pedirse.

---

## Actividad 3 · Licencias

Un alumno incluye en su aplicación una foto descargada de un buscador de imágenes y un conjunto de iconos con licencia libre. No ha anotado de dónde salen.

¿Qué debería hacer?

??? success "Solución orientativa"

    Comprobar la licencia de la foto y, si no permite su uso, sustituirla. Anotar la procedencia y la licencia de los iconos para citarlos en la memoria.

---

## Actividad 4 · Tu viabilidad legal

1. Lista los datos personales que trata tu proyecto y justifica cada uno.
2. Indica si usarías cookies no necesarias.
3. Anota las licencias del software y los recursos principales.
4. Indica si le afecta la normativa de accesibilidad del sector público.
5. Escribe una medida para cada aspecto que te afecte.

```text
| Aspecto | ¿Me afecta? | Medida |
|---------|-------------|--------|
```

---

## Ejemplos de redacción para la memoria

| Nivel | Ejemplo |
|---------|---------|
| ❌ Pobre | El proyecto cumplirá la ley. |
| ⚠️ Básico | El proyecto cumple la normativa de protección de datos. |
| ✅ Bueno | Se recogerán solo nombre, correo y teléfono, en cumplimiento del principio de minimización del RGPD. |
| ⭐ Excelente | Se tratarán únicamente tres datos personales (nombre, correo y teléfono), justificados por la finalidad. Se informará al usuario de su uso, las contraseñas se guardarán cifradas y no se usarán cookies de seguimiento. Se toma como objetivo la accesibilidad WCAG 2.1 de nivel AA. |

---

## ¿Cómo aparecerá esto en la memoria?

### Plantilla reutilizable

```text
Viabilidad legal

Datos personales tratados y justificación: ...
Medidas de protección: ...
Cookies: ...
Licencias del software y los recursos: ...
Accesibilidad: ...

Conclusión legal: ...
```

---

## Lo que irá a la memoria

```text
5.4. Viabilidad legal

- Normas que afectan al proyecto.
- Datos personales y medidas.
- Licencias.
- Accesibilidad.
- Conclusión legal.
```

---

## Autoevaluación

- [ ] Sé qué es un dato personal.
- [ ] He aplicado el principio de minimización.
- [ ] He revisado las licencias de lo que uso.
- [ ] Sé si me afecta la normativa de accesibilidad del sector público.
- [ ] Podría redactar el apartado 5.4 de mi memoria.
