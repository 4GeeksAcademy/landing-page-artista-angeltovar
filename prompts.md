# Prompts y Uso de IA en el Proyecto

## Proposito del documento

Este archivo resume como fue utilizada la inteligencia artificial durante el desarrollo de esta landing page. La idea es dejar evidencia clara del proceso, los prompts principales usados y la forma en que la IA ayudo a construir una pagina web moderna, semantica, accesible y optimizada para buscadores.

## Objetivo del proyecto

Desarrollar una landing page para un artista musical usando solo HTML y CSS, cumpliendo con estos puntos:

- Estructura semantica en HTML.
- Estilos en un archivo CSS separado.
- Accesibilidad para lectores de pantalla y navegacion por teclado.
- Diseno responsive.
- SEO tecnico basico.
- Implementacion de datos estructurados con Schema.org.

## Como utilice la IA

La IA fue usada como asistente de desarrollo para:

- Crear la estructura inicial del HTML.
- Organizar y separar los estilos CSS.
- Mejorar la accesibilidad del sitio.
- Agregar metadatos SEO y Open Graph.
- Implementar datos estructurados en JSON-LD.
- Refinar el contenido textual para que fuera mas creible.
- Ajustar el diseno responsive.
- Revisar el cumplimiento de la rubrica del proyecto.

En todo momento se mantuvo la condicion principal del encargo: trabajar solo con HTML y CSS para la parte funcional y visual del sitio.

## Flujo de trabajo paso a paso

### 1. Creacion de la landing base

**Prompt usado:**

"Crea una landing page para un artista con navegacion a secciones: Sobre mi, Trayectoria y Proximas presentaciones. Cada seccion debe ocupar la pantalla como una sola pagina. Usa HTML semantico, accesibilidad, SEO y Schema.org."

**Resultado:**

- Se creo la estructura inicial del sitio.
- Se organizo la pagina en secciones claras.
- Se anadieron elementos base de SEO y semantica.

### 2. Separacion de estilos en CSS externo

**Prompt usado:**

"Saca todos los estilos a un css aparte, no quiero estilos en linea en mi html."

**Resultado:**

- Se movieron todos los estilos a `styles.css`.
- `index.html` quedo limpio y mejor organizado.

### 3. Cambio del concepto del artista

**Prompt usado:**

"Cambiemos el artista por un artista underground venezolano de hip hop."

**Resultado:**

- Se redefinio el enfoque visual y textual del sitio.
- Se adapto el contenido al perfil del artista urbano.

### 4. Construccion de una identidad mas creible

**Prompt usado:**

"Hazlo creible, no debes mencionar que es un artista ficticio."

**Resultado:**

- Se eliminaron referencias que rompian la ilusion del personaje artistico.
- Se ajusto el tono para que sonara mas profesional y realista.

### 5. Cambio de nombre artistico

**Prompt usado:**

"El nombre del artista sera Arkharm a partir de ahora."

**Resultado:**

- Se actualizo el branding en todo el sitio.
- Se modificaron titulo, metadatos, textos visibles y Schema.org.

### 6. Mejora del header y navegacion

**Prompt usado:**

"Quiero el nombre Arkharm a la izquierda y Sobre mi, Trayectoria y Proximas presentaciones del lado derecho en una sola linea y que siga siendo responsive."

**Resultado:**

- Se reorganizo la cabecera para escritorio.
- Se optimizo la distribucion visual del menu.

### 7. Menu hamburguesa para moviles

**Prompt usado:**

"Quiero que se vuelva un menu hamburguesa a medida que el tamano de la pagina sea mas pequeno, por ejemplo en moviles."

**Resultado:**

- Se creo una version responsive del menu.
- Se mantuvo navegacion por teclado y compatibilidad con lector de pantalla.

### 8. Carrusel de bienvenida

**Prompt usado:**

"Toma estas imagenes y creame un carrusel de bienvenida con transicion automatica."

**Resultado:**

- Se agrego un carrusel visual al inicio del sitio.
- El efecto se implemento con HTML y CSS.

### 9. Ajustes de altura y espaciado

**Prompts usados:**

- "Cambiale el vh a ese carrucel de 50%."
- "Cambia el padding top de las tres secciones a 1 para que queden mas pegadas al heading."
- "Cambiale el vh a las tres secciones a un 70%."

**Resultado:**

- Se refino el espaciado general del sitio.
- Se mejoro la distribucion entre header, carrusel y secciones.

### 10. Mejora de contenido en Sobre mi y Trayectoria

**Prompt usado:**

"Crea mas contexto creible en Trayectoria y Sobre mi, unas 2 lineas mas."

**Resultado:**

- Se agregaron parrafos adicionales.
- El perfil del artista gano profundidad y credibilidad.

### 11. Presentaciones en lugares reales

**Prompt usado:**

"Cambiale las presentaciones por sitios reales donde se hacen batallas y conciertos de freestyle a nivel nacional."

**Resultado:**

- Se reemplazaron venues genericos por sedes reales en Venezuela.
- Tambien se sincronizaron esos cambios con los eventos en Schema.org.

### 12. Boton flotante de inicio

**Prompt usado:**

"Agrega un boton de inicio que me regrese directamente al carrucel y se mantenga flotando en la pantalla."

**Resultado:**

- Se agrego un boton flotante persistente.
- Mejora la navegacion dentro de la landing.

### 13. Auditoria y cierre de accesibilidad

**Prompts usados:**

- "La pagina es util para invidentes?"
- "Haz lo que tenga que hacer entonces para dejarlo al 100%."

**Resultado:**

- Se revisaron semantica, texto alternativo, estructura de encabezados y atributos ARIA.
- Se mejoro el menu movil para teclado y lector de pantalla.
- Se agrego control de pausa para el carrusel usando solo HTML y CSS.

## Aspectos tecnicos mejorados con ayuda de la IA

### Estructura

- HTML5 semantico.
- Jerarquia correcta de titulos.
- Separacion limpia de HTML y CSS.

### Accesibilidad

- `skip-link` al contenido principal.
- `aria-label` y `aria-labelledby` donde aportan contexto.
- `alt` en todas las imagenes del carrusel.
- foco visible con teclado.
- menu movil accesible.
- control para pausar animaciones.

### SEO

- `title` y `meta description`.
- `meta robots`.
- etiquetas Open Graph.
- Twitter Card.
- `canonical`.
- datos estructurados `Schema.org` con `Person`, `WebSite`, `ProfilePage`, `MusicAlbum` y `Event`.

### Diseno

- Paleta visual coherente.
- Diseno responsive.
- Secciones claras y legibles.
- Navegacion fija con boton flotante.

## Lo que aprendi con este proceso

- Una pagina moderna no solo debe verse bien; tambien debe ser semantica, accesible y rastreable.
- La accesibilidad debe pensarse desde el inicio, no dejarse para el final.
- SEO no es solo el titulo: incluye metadatos sociales, canonical y datos estructurados.
- HTML y CSS bien usados pueden resolver gran parte de un proyecto sin necesidad de JavaScript.

## Conclusion

La inteligencia artificial fue usada como asistente de apoyo tecnico y creativo durante la construccion de esta landing page. Su aporte principal fue ayudar a estructurar, revisar, corregir y optimizar el proyecto hasta alinearlo con los criterios de evaluacion solicitados.

El resultado final es una pagina web desarrollada con bases solidas en:

- HTML semantico
- CSS organizado
- accesibilidad
- responsive design
- SEO tecnico
- datos estructurados

Este documento sirve como evidencia del proceso y como referencia para futuros proyectos donde se quiera reutilizar una metodologia similar de trabajo asistido por IA.