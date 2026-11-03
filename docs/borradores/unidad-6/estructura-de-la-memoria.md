# Estructura de la memoria

## De los apartados sueltos al documento final

Cada unidad te dejó un apartado. Ahora hay que darles forma de documento único: con portada, índice, numeración coherente y un formato uniforme.

---

## La estructura definitiva

| Parte | Contenido |
|--------|--------|
| **Portada** | Título, autoría, ciclo, módulo, curso y fecha. |
| **Índice** | Lista numerada de apartados. |
| **Resumen** *(si lo pide tu profesor)* | De 100 a 150 palabras con el proyecto en pocas líneas. |
| **1. Introducción** | Contexto, problema, propuesta y estructura. |
| **2. Definición del proyecto** | 2.1 Descripción, 2.2 Objetivos y alcance. |
| **3. Planificación temporal** | 3.1 a 3.5. |
| **4. Análisis DAFO y CAME** | 4.1 a 4.4. |
| **5. Estudio de viabilidad y recursos** | 5.1 a 5.5. |
| **6. Conclusiones** | Resultados, valoración, limitaciones y trabajo futuro. |
| **7. Bibliografía** | Fuentes y herramientas. |
| **Anexos** *(opcional)* | Material que apoya pero no cabe en el texto. |

!!! info "Idea clave"

    El orden de los apartados cuenta una historia: *hay un problema → esto es lo que propongo → así lo haré → estos son los riesgos → es viable → esto he concluido.*

---

## Una portada sencilla y completa

```text
Título del proyecto
Subtítulo (una frase que explique de qué trata)

Autoría: Nombre y apellidos
Ciclo formativo: Desarrollo de Aplicaciones Web (1.º DAW)
Módulo: Proyecto Intermodular I
Centro: ...
Profesorado: ...
Fecha: ...
```

!!! tip "El título importa"

    Un buen título nombra el proyecto y dice qué hace. «ReservaSport: gestión de reservas de instalaciones deportivas» informa; «Mi proyecto» no.

---

## Cómo organizarla en tu repositorio

Una forma práctica y compatible con Git es tener una carpeta con un archivo por apartado y un índice:

```text
memoria/
├── index.md              (portada, índice y resumen)
├── 01-introduccion.md
├── 02-definicion.md
├── 03-planificacion.md
├── 04-dafo-came.md
├── 05-viabilidad.md
├── 06-conclusiones.md
├── 07-bibliografia.md
└── anexos/
```

!!! tip "Por qué un archivo por apartado"

    Con Git puedes ver qué ha cambiado en cada apartado, volver atrás si algo sale mal y trabajar sin pisar el resto del documento.

### Reglas de formato

| Elemento | Regla |
|--------|--------|
| **Títulos** | Un solo título principal. Los apartados son de segundo nivel y las secciones de tercer nivel. |
| **Numeración** | Los mismos números en el índice y en los títulos. |
| **Tablas** | Con título y numeradas (por ejemplo, *Tabla 3.1. Tareas del proyecto*). |
| **Figuras y diagramas** | Con título y referenciadas en el texto (*como muestra la Figura 3.1...*). |
| **Estilo** | Voz coherente en todo el documento, preferentemente impersonal (*«se estima»*), y mismo tiempo verbal. |

---

## El formato de entrega

Tu profesor o profesora indicará el formato y el plazo de entrega: **[formato y plazo que se indiquen]**.

Si te piden un archivo, estas son algunas opciones habituales:

| Opción | Cuándo conviene |
|--------|--------|
| Exportar a PDF desde un editor de Markdown | Entrega de un único documento. |
| Imprimir a PDF desde el navegador | Si la memoria está publicada como página web. |
| Convertir a un documento de texto | Si te piden un formato editable. |

!!! warning "Comprueba el resultado"

    Al exportar, abre el archivo final y revisa que se ven bien las tablas, los diagramas y las imágenes. Algunos conversores no dibujan los diagramas Mermaid; si pasa, expórtalos como imagen y añádelos al documento.

---

## Actividad 1 · Ordena la memoria

Ordena estos apartados como aparecerían en la memoria:

Conclusiones · Viabilidad · Introducción · Planificación · Bibliografía · DAFO y CAME · Definición del proyecto

??? success "Solución"

    Introducción, Definición del proyecto, Planificación, DAFO y CAME, Viabilidad, Conclusiones, Bibliografía.

---

## Actividad 2 · Crea tu esqueleto

1. Crea la carpeta `memoria/` con los archivos de la estructura.
2. Copia en cada archivo el apartado correspondiente (2, 3, 4 y 5).
3. Deja los archivos de introducción, conclusiones y bibliografía con su título y una nota de «pendiente».
4. Comprueba que los títulos y la numeración son coherentes.

---

## Actividad 3 · Portada y título

1. Escribe tres posibles títulos para tu proyecto.
2. Elige el que mejor lo describe y justifica por qué.
3. Redacta tu portada con todos los datos.

---

## ¿Cómo aparecerá esto en la memoria?

### Plantilla de índice

```text
Índice

1. Introducción
2. Definición del proyecto
   2.1. Descripción
   2.2. Objetivos y alcance
3. Planificación temporal
   3.1. Fases del proyecto
   ...
6. Conclusiones
7. Bibliografía
Anexos
```

---

## Lo que irá a la memoria

```text
Partes previas

- Portada.
- Índice.
- Resumen (si se pide).
```

---

## Autoevaluación

- [ ] Mi memoria sigue la estructura definitiva.
- [ ] Tengo un archivo por apartado en mi repositorio.
- [ ] Los títulos y la numeración son coherentes.
- [ ] Mi portada tiene todos los datos.
- [ ] Sé en qué formato debo entregar.
