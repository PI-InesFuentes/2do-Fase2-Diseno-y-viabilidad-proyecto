# F2 · Diseño y viabilidad del proyecto

**Proyecto Intermodular · Segundo curso · Fase 2**

## Objetivo de la actividad

En la Fase 1 identificaste una necesidad y definiste una propuesta inicial de aplicación web para darle respuesta.

El objetivo de esta segunda fase es **transformar esa propuesta en un proyecto suficientemente definido y técnicamente viable**, concretando qué quieres conseguir, qué incluirá la aplicación, qué requisitos deberá cumplir, qué recursos serán necesarios y cómo podría organizarse técnicamente.

---

## 1. Punto de partida

Debes continuar trabajando sobre la propuesta desarrollada en la Fase 1.

Antes de comenzar este documento, revisa el trabajo entregado anteriormente y el feedback recibido. Si consideras necesario modificar el contexto, los usuarios, alguna funcionalidad o cualquier otra decisión inicial, puedes hacerlo siempre que el cambio esté justificado.

En esta fase empezarás a tomar decisiones de diseño del proyecto, pero no es necesario que todas ellas sean definitivas. Algunas podrán evolucionar posteriormente a medida que avances en el desarrollo.

> **Importante:** no se pretende que elijas tecnologías simplemente porque ya las conoces o porque estén de moda. Debes intentar justificar por qué las alternativas consideradas podrían ser adecuadas para las necesidades de tu proyecto.

---

## 2. Documento que debes elaborar

Debes elaborar un documento de diseño y viabilidad que permita comprender con suficiente precisión qué aplicación pretendes desarrollar y comprobar que el proyecto puede llevarse a cabo.

El documento deberá estar organizado utilizando, como mínimo, los siguientes apartados. Puedes añadir otros si consideras que ayudan a definir mejor tu proyecto.

### 2.1. Resumen y revisión de la propuesta

Comienza recordando brevemente cuál es el proyecto que vas a desarrollar. No debes volver a copiar todo el contenido de la Fase 1.

Resume en uno o dos párrafos:

- el contexto en el que se desarrolla el proyecto;
- la necesidad principal que quieres resolver;
- los usuarios principales;
- la solución propuesta.

Si has realizado algún cambio respecto a la propuesta entregada en la Fase 1, explica brevemente qué has modificado y por qué.

### 2.2. Objetivo general y objetivos específicos

Define qué pretende conseguir el proyecto.

Debes establecer:

- un **objetivo general** que resuma la finalidad principal de la aplicación;
- varios **objetivos específicos** que concreten los principales resultados que deseas alcanzar.

Los objetivos deben describir resultados o capacidades, no simplemente tareas que vas a realizar.

> **Ejemplo de objetivo:**
> Permitir que los usuarios consulten la disponibilidad de los recursos y realicen reservas evitando solapamientos.
>
> **No sería un objetivo:**
> Programar la pantalla de reservas.

### 2.3. Alcance del proyecto

Define con claridad qué incluirá el proyecto y qué quedará fuera de él.

Clasifica las funcionalidades en tres grupos:

- **Funcionalidades esenciales:** deben estar implementadas para considerar que la aplicación cumple su finalidad principal.
- **Funcionalidades de ampliación:** se desarrollarán si el núcleo principal está terminado y dispones de tiempo.
- **Fuera de alcance:** funcionalidades relacionadas con el contexto del proyecto que deliberadamente no vas a desarrollar.

Esta clasificación debe ayudarte a mantener un proyecto realista.

Una aplicación relativamente pequeña pero completa, funcional y bien integrada es preferible a una propuesta enorme de la que solo puedas implementar una parte.

### 2.4. Requisitos principales

A partir de los objetivos y funcionalidades anteriores, identifica los principales requisitos que deberá cumplir la aplicación.

Diferencia al menos entre:

- **Requisitos funcionales:** describen qué acciones, operaciones o servicios debe permitir el sistema.
- **Requisitos no funcionales:** establecen condiciones relacionadas con aspectos como accesibilidad, usabilidad, seguridad, rendimiento, compatibilidad, fiabilidad o mantenibilidad.

Intenta formularlos de forma concreta y, siempre que sea posible, comprobable.

> **Ejemplo de requisito funcional:**
> El sistema permitirá consultar los recursos disponibles para una fecha y franja horaria determinadas.
>
> **Ejemplo de requisito no funcional:**
> La aplicación deberá poder utilizarse correctamente desde dispositivos móviles y ordenadores de escritorio.

**Ten en cuenta los mínimos comunes del Proyecto Intermodular:**

Independientemente del contexto elegido, la aplicación deberá permitir posteriormente trabajar con una gestión real de recursos y reservas.

- consultar disponibilidad;
- gestionar recursos y reservas;
- realizar operaciones de alta, consulta, modificación y eliminación;
- validar la información introducida;
- evitar reservas incompatibles o solapadas;
- disponer de persistencia de datos;
- establecer comunicación entre cliente y servidor;
- adaptar la autenticación y los permisos a los usuarios definidos en tu proyecto.

### 2.5. Estudio inicial de viabilidad técnica

Analiza si la solución que has planteado puede desarrollarse técnicamente y qué elementos serán previsiblemente necesarios.

Debes estudiar, como mínimo:

- tecnologías o alternativas para el frontend;
- tecnologías o alternativas para el backend;
- sistema de persistencia o base de datos;
- forma de comunicación entre cliente y servidor;
- infraestructura necesaria para ejecutar y desplegar la aplicación;
- posibles servicios externos;
- principales dificultades técnicas que anticipas.

No basta con realizar una lista de tecnologías. Debes justificar brevemente por qué las alternativas consideradas son adecuadas para tu proyecto.

También puedes comparar varias opciones cuando todavía no tengas clara una decisión.

> **Importante:** el stack tecnológico planteado en esta fase no tiene por qué ser definitivo. Podrás modificarlo posteriormente si encuentras una alternativa más adecuada o aparecen nuevas necesidades.

### 2.6. Arquitectura preliminar

Representa mediante un diagrama sencillo los principales componentes de tu aplicación y la forma en la que se comunicarán.

Como referencia, una estructura básica podría ser:

```
Navegador / Frontend   ↔   Backend / API   ↔   Base de datos
```

Tu arquitectura puede incluir además otros elementos cuando tengan sentido:

- servicio de autenticación;
- almacenamiento de archivos;
- servicios de correo electrónico;
- notificaciones;
- APIs externas;
- otros servicios específicos de tu proyecto.

Acompaña el diagrama con una breve explicación de qué responsabilidad tiene cada componente.

### 2.7. Fases generales del proyecto

Identifica las principales fases que consideras necesarias para pasar desde la propuesta actual hasta una aplicación terminada.

Puedes tomar como referencia una estructura similar a:

- análisis y definición;
- diseño de la solución;
- diseño de la interfaz;
- desarrollo del frontend;
- desarrollo del backend y persistencia;
- integración;
- pruebas;
- despliegue;
- documentación y entrega.

Explica brevemente qué trabajo se realizaría en cada fase aplicado a tu proyecto concreto.

En esta actividad no debes crear todavía un cronograma detallado ni asignar fechas u horas a cada tarea. Esa planificación se realizará posteriormente.

### 2.8. Recursos necesarios

Identifica los recursos que previsiblemente serían necesarios para desarrollar y poner en funcionamiento el proyecto.

Incluye, cuando proceda:

- hardware;
- sistema operativo;
- entorno o entornos de desarrollo;
- software y herramientas;
- gestor de bases de datos;
- repositorio de control de versiones;
- herramientas de diseño o prototipado;
- servicios de alojamiento y despliegue;
- dominio;
- servicios o APIs externas;
- otros recursos específicos.

Debes identificar también los recursos personales o perfiles profesionales que serían necesarios si el proyecto se desarrollara en un contexto profesional.

En el Proyecto Intermodular tú asumirás diferentes funciones, pero debes ser capaz de identificar qué perfiles podrían intervenir en un desarrollo real: desarrollo frontend, backend, diseño, sistemas, gestión del proyecto, pruebas, etc.

### 2.9. Estimación económica inicial

Realiza una estimación básica de los principales costes que podría tener el desarrollo o la puesta en marcha de la solución.

Puedes utilizar una tabla con columnas similares a:

| Concepto | Servicio o recurso | Coste estimado | Periodicidad (cuando proceda) | Fuente consultada |
|----------|--------------------|----------------|-------------------------------|-------------------|

Valora, cuando corresponda:

- hosting;
- dominio;
- base de datos o almacenamiento;
- servicios externos;
- licencias;
- otros costes asociados a la solución.

Si utilizas una alternativa gratuita, indícalo igualmente y explica brevemente qué plan o servicio utilizarías.

No se pide un plan de empresa ni un estudio financiero completo. Queremos comprobar que puedes identificar los costes principales de la solución y realizar una estimación razonable.

### 2.10. Necesidades de financiación

Reflexiona brevemente sobre cómo podría financiarse hipotéticamente el desarrollo o la puesta en marcha del proyecto en un contexto real.

En la Fase 1 investigaste posibles ayudas o programas relacionados con la digitalización. No es necesario repetir ese apartado.

Aquí debes centrarte en:

- si el proyecto necesitaría financiación;
- qué costes principales habría que cubrir;
- qué alternativas podrían utilizarse para financiarlo: recursos propios, presupuesto de la organización, inversión, financiación externa, subvenciones, cuotas por el servicio u otras opciones;
- qué alternativa tendría más sentido para tu caso.

### 2.11. Primer flujo funcional de la aplicación

Realiza un esquema sencillo de las principales pantallas o vistas de la aplicación y de cómo se relacionan entre ellas.

Puedes realizarlo a mano y digitalizarlo o utilizar una herramienta sencilla de diagramación.

Por ejemplo:

```
Inicio de sesión → Inicio / disponibilidad → Nueva reserva → Confirmación → Mis reservas → Detalle / modificación
```

El ejemplo anterior es únicamente orientativo. Tu flujo debe adaptarse a los usuarios y funcionalidades definidos en tu proyecto.

No se evalúa todavía el diseño visual. No necesitas definir colores, tipografías, componentes gráficos ni el aspecto final de las pantallas. Queremos comprobar la estructura funcional y la navegación general de la aplicación.

### 2.12. Condiciones de calidad

Identifica qué aspectos deberán controlarse durante el desarrollo para poder considerar que el resultado final tiene una calidad adecuada.

Define condiciones concretas relacionadas, cuando proceda, con:

- funcionamiento correcto de las funcionalidades principales;
- validación de datos;
- prevención de reservas incompatibles o solapadas;
- seguridad;
- accesibilidad;
- usabilidad;
- adaptación a diferentes tamaños de pantalla;
- tratamiento adecuado de errores;
- integridad de la información;
- organización y calidad del código;
- documentación;
- pruebas de funcionamiento.

Intenta que las condiciones planteadas puedan comprobarse posteriormente.

Evita expresiones demasiado genéricas como «la aplicación funcionará bien», «será segura» o «será fácil de utilizar» sin explicar qué significan esas afirmaciones en tu proyecto.

### Qué no debes desarrollar todavía

En esta fase no se pide todavía:

- crear un cronograma detallado de tareas y fechas;
- asignar horas concretas a cada actividad;
- crear la base de datos definitiva;
- diseñar visualmente todas las pantallas;
- programar la aplicación;
- desplegar la solución;
- realizar un plan de empresa;
- considerar definitivo el stack tecnológico propuesto.

---

## 3. Formato del documento

La entrega deberá realizarse mediante un **único documento PDF**.

El documento deberá cumplir las siguientes indicaciones:

- extensión orientativa de 7 a 12 páginas de contenido, sin contar portada, índice, fuentes o anexos;
- incluir una portada con, al menos, título del proyecto, nombre y apellidos del alumno o alumna y curso;
- mantener una estructura clara mediante títulos y subtítulos;
- utilizar un formato legible y coherente en todo el documento;
- incorporar los diagramas, esquemas y tablas necesarios para explicar el proyecto;
- revisar ortografía, redacción y presentación antes de entregar;
- citar o enlazar las fuentes utilizadas para investigar tecnologías, precios, servicios u otra información externa;
- exportar el documento finalmente a PDF. No se admitirán documentos en Word, LibreOffice u otros formatos editables.

**Nombre recomendado del archivo:** `F2_Apellido1_Apellido2_Nombre.pdf`

---

## 4. Vídeo de presentación

Además del documento, deberás realizar un **vídeo de entre 3 y 5 minutos** en el que expliques las principales decisiones adoptadas en esta fase.

El vídeo no consiste en leer literalmente el documento. Debes ser capaz de explicar con tus propias palabras:

- cuál es el objetivo principal del proyecto;
- qué funcionalidades forman parte del alcance;
- qué requisitos consideras más importantes;
- qué solución técnica planteas inicialmente;
- cómo se organiza la arquitectura propuesta;
- qué recursos y costes principales has identificado;
- por qué consideras que el proyecto es viable.

Puedes utilizar los diagramas o esquemas incluidos en el documento como apoyo durante la explicación.

Puedes aparecer en cámara, grabar tu voz acompañada de una presentación o utilizar otro formato similar. Lo importante es que el vídeo permita comprobar que comprendes y puedes justificar las decisiones que has tomado.

### Cómo entregar el vídeo

1. Graba el vídeo y súbelo a un servicio que permita compartirlo mediante enlace, preferentemente OneDrive utilizando tu cuenta educativa.
2. Configura los permisos para que el profesorado pueda visualizar el vídeo sin solicitarte acceso.
3. Copia el enlace de visualización.
4. Antes de realizar la entrega, abre una ventana de navegación privada o de incógnito y pega el enlace.
5. Comprueba que el vídeo puede abrirse y reproducirse correctamente.
6. Incluye el enlace al vídeo en el apartado final del PDF con el título **«Enlace al vídeo de presentación»**.

> **Muy importante:** es responsabilidad del alumno o alumna comprobar que el enlace entregado funciona y tiene los permisos adecuados. Un enlace que solicite autorización, esté restringido o no permita visualizar el vídeo se considerará vídeo no entregado hasta que se subsane.

---

## 5. Entrega en Aules

La entrega se realizará exclusivamente mediante esta actividad de Aules.

Debes entregar:

- un único archivo PDF con el documento completo de diseño y viabilidad;
- dentro del mismo documento, los diagramas y esquemas solicitados;
- las fuentes utilizadas;
- al final del PDF, el enlace al vídeo de presentación.

No debes subir directamente el archivo de vídeo a Aules, salvo que el profesorado indique expresamente lo contrario.

Antes de pulsar **Enviar tarea**, realiza una última comprobación:

- [ ] el PDF correcto está adjunto;
- [ ] el documento se abre correctamente;
- [ ] no faltan páginas ni apartados;
- [ ] los diagramas y tablas pueden leerse correctamente;
- [ ] las fuentes externas están indicadas;
- [ ] el enlace al vídeo aparece dentro del documento;
- [ ] el enlace funciona;
- [ ] has probado el enlace desde una ventana de incógnito;
- [ ] el vídeo puede reproducirse sin solicitar permisos;
- [ ] la versión entregada es realmente la versión definitiva.

---

## 6. Uso de fuentes e información externa

Esta actividad requiere consultar información sobre tecnologías, herramientas, servicios, precios y posibles alternativas técnicas.

Siempre que utilices información externa debes indicar de dónde procede. Puedes hacerlo mediante enlaces, notas o un apartado final de fuentes consultadas.

Especialmente en el apartado económico, **no inventes precios**. Utiliza información disponible en el momento en el que realices la actividad e indica la fuente utilizada.

No es suficiente con copiar la descripción de una tecnología o servicio. Debes seleccionar la información relevante y relacionarla con las necesidades de tu propio proyecto.

---

## 7. Uso de herramientas de inteligencia artificial

Puedes utilizar herramientas de inteligencia artificial como apoyo para investigar alternativas, comprender tecnologías, organizar información, comparar opciones o mejorar la redacción.

Sin embargo, las decisiones del proyecto deben estar comprendidas y justificadas por ti. Eres responsable de revisar la información obtenida, comprobar su veracidad y adaptarla a tu proyecto.

No incluyas tecnologías, arquitecturas, servicios, costes o conceptos que no seas capaz de explicar.

El vídeo de presentación, las tutorías y las posteriores fases del proyecto podrán utilizarse para comprobar la comprensión y autoría del trabajo.

---

## Qué se valorará

La actividad corresponde al **RA2** del Proyecto Intermodular. Se valorará especialmente:

- la selección y utilización de información relevante;
- la calidad del estudio de viabilidad técnica;
- la correcta identificación de las fases del proyecto;
- la claridad de los objetivos y la definición del alcance;
- la identificación de recursos materiales y personales;
- la coherencia de la estimación económica;
- la reflexión sobre las necesidades de financiación;
- la calidad de la documentación de diseño, incluyendo requisitos, arquitectura y flujo funcional;
- la identificación de condiciones que permitan controlar la calidad del proyecto;
- la capacidad para explicar y justificar las decisiones adoptadas.
