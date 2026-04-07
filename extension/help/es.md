---
layout: bare
title: Extensión Furigana Reader - Guía del usuario
lang: es
---

# Furigana Reader - Guía del usuario

> Versión: v1.4.0

## Introducción

Furigana Reader es una extensión de navegador pensada para quienes estudian japonés. Con un analizador morfológico WASM (Lindera + IPAdic) y respaldo en JavaScript, añade con precisión furigana (anotaciones de lectura) a los kanji en páginas web y PDF. Incluye además un diccionario japonés integrado, texto a voz y traducción, para que aprendas la pronunciación del japonés con más facilidad.

---

## Funciones principales

- **Modo furigana en toda la página** — Añade furigana a todos los kanji con un solo clic
- **Diccionario al pasar el cursor** — Pasa el ratón sobre los caracteres anotados para ver definiciones de JMdict (más de 180 000 entradas), lecturas, insignias de nivel JLPT (N5–N1) y botones de pronunciación; elige entre modo Diccionario, modo Lectura o Desactivado
- **Lector PDF** — Lector PDF integrado con furigana, diccionario, voz y traducción; admite arrastrar y soltar, carga por URL y detección automática de PDF con redirección inteligente
- **Tres estilos de lectura** — Hiragana, katakana y rōmaji
- **Separación de okurigana** — Separa con precisión el okurigana (送り仮名) del tronco en kanji
- **Compatibilidad con jukujikun** — Lecturas correctas en compuestos de varios kanji con lecturas especiales (熟字訓)
- **Texto a voz** — Pulsa el botón del altavoz para oír la pronunciación en japonés
- **Lectura de la selección con karaoke** — Selecciona cualquier texto japonés; aparece una barra compacta con hablar y traducir; la voz va con resaltado palabra a palabra o carácter a carácter en tiempo real (efecto karaoke) sincronizado con el audio
- **Traducción de la selección** — Selecciona texto, pulsa traducir en la barra para obtener traducción al instante con Bing o Google Translate, en una burbuja en línea
- **Atajos de teclado** — Acceso rápido a las funciones principales con atajos personalizables
- **Interfaz multilingüe** — 38 idiomas de interfaz

---

## Cómo usarla

### Paso 1: Instalar la extensión

Instala **Furigana Reader** desde la [Chrome Web Store](https://chromewebstore.google.com/) o cárgala en local en modo desarrollador.

### Paso 2: Abrir cualquier página web

Visita una página con contenido en japonés.

### Paso 3: Activar el furigana

Haz clic en el icono de la extensión en la barra de herramientas. Activa «Activar furigana» y luego «Furigana en toda la página» para anotar todos los kanji. También puedes usar el botón flotante abajo a la derecha.

### Paso 4: Ver los furigana

Pasa el ratón sobre los caracteres para ver información emergente con lecturas y definiciones del diccionario. Pulsa el icono del altavoz para oír la pronunciación.

### Paso 5: Hablar y traducir el texto seleccionado

Selecciona texto japonés con el ratón. Cerca de la selección aparece una barra compacta con dos botones:
- **🔊 Hablar** — Lee el texto en voz alta con resaltado tipo karaoke
- **🌐 Traducir** — Muestra una burbuja de traducción en línea debajo de la barra

También puedes hacer clic derecho y elegir «Furigana Reader > Leer la selección en voz alta» o «Furigana Reader > Traducir la selección».

> **Consejo:** Haz clic en el icono de la extensión para abrir los ajustes y cambiar el estilo de furigana, el modo al pasar el cursor, la velocidad de voz, el motor de traducción y más.

---

## Diccionario al pasar el cursor

La extensión incluye un diccionario japonés integrado basado en JMdict (más de 180 000 entradas). En los ajustes puedes elegir entre varios modos al pasar el cursor:

| Modo | Comportamiento |
|------|----------------|
| **Diccionario** | Al pasar el cursor: lectura + definición + nivel JLPT + botón de pronunciación |
| **Lectura** | Al pasar el cursor: lectura + botón de pronunciación (sin definiciones) |
| **Desactivado** | Sin efecto al pasar el cursor |

En el modo **Diccionario**, la información emergente muestra:
- La palabra y su lectura (furigana)
- Un botón de pronunciación (clic para escuchar)
- Definiciones en japonés de JMdict
- Insignia de nivel JLPT (N5–N1) cuando exista

> **Consejo:** Los datos del diccionario se cargan bajo demanda cuando el modo Diccionario está activo y se descargan al cambiar a otros modos para ahorrar memoria.

---

## Lector PDF

Furigana Reader incluye un lector PDF integrado para leer documentos PDF con furigana, diccionario, voz y traducción: las mismas funciones que en páginas web, ahora también en PDF.

### Abrir un PDF

**Método 1: Desde el menú emergente**  
Haz clic en el icono de la extensión y luego en «Abrir lector PDF». Arrastra y suelta un PDF o pulsa «Elegir archivo» para abrir un PDF local. También puedes pegar una URL de PDF.

**Método 2: Menú contextual**  
Haz clic derecho en un enlace `.pdf` y elige «Abrir PDF con Furigana Reader».

**Método 3: Detección automática**  
Con «Detección inteligente de PDF» activada en los ajustes, la extensión redirige automáticamente las URLs `.pdf` al lector integrado. Si se detecta un PDF pero no se redirige (por ejemplo, con el visor integrado de Chrome), verás notificaciones e invitaciones para abrirlo en Furigana Reader.

### Funciones del lector PDF

- **Furigana** — Todo el furigana funciona en el texto del PDF, incluido el modo de página completa y la información emergente
- **Cinco modos de furigana** — Hiragana, katakana, rōmaji, solo al pasar el cursor y desactivado
- **Diccionario por clic** — Haz clic en una palabra para ver su definición en JMdict (en PDF se usa el clic en lugar del paso del cursor para leer con menos distracciones)
- **Barra de selección** — Selecciona texto para hablar, traducir o copiar
- **Barra lateral** — Esquema del índice y miniaturas de página
- **Búsqueda** — Búsqueda de texto completo en el PDF
- **Temas** — Oscuro, claro y sepia
- **Zoom** — Varios niveles de zoom, incluido furigana adaptable al zoom
- **Atajos de teclado** — Flechas para navegar, +/- para zoom, Ctrl/Cmd+F para buscar

---

## Lectura de la selección y karaoke

La lectura de la selección te permite seleccionar cualquier texto japonés y escucharlo con un clic: ideal para practicar la pronunciación de frases y la lectura.

**Método 1: Barra de selección**  
Selecciona texto japonés con el ratón. Aparece una barra compacta con 🔊 hablar y 🌐 traducir. Pulsa hablar para reproducir. Mientras se lee, cada palabra o carácter se resalta en tiempo real (efecto karaoke).

**Método 2: Menú contextual**  
Tras seleccionar texto japonés, clic derecho y «Furigana Reader > Leer la selección en voz alta».

**Método 3: Atajo de teclado**  
Selecciona texto y pulsa `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) para hablar.

> **Consejo:** El karaoke funciona mejor si el navegador admite eventos de límites de palabras en TTS. Si no, la extensión usa un respaldo basado en tiempo para un resaltado fluido.

---

## Traducción

Selecciona cualquier texto de la página y usa la traducción para obtener resultados al instante.

**Método 1: Barra de selección**  
Selecciona texto y pulsa 🌐 traducir en la barra. Debajo aparece una burbuja con el resultado y un botón para copiar.

**Método 2: Menú contextual**  
Selecciona texto, clic derecho y «Furigana Reader > Traducir la selección».

**Método 3: Atajo de teclado**  
Selecciona texto y pulsa `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) para traducir.

**Motores de traducción:**
- **Bing Translate** (predeterminado) — Microsoft Translator
- **Google Translate** — Google

Ambos admiten **108 idiomas de destino**.

Puedes cambiar el motor y el idioma de destino en los ajustes de la extensión. El idioma de destino se detecta automáticamente según el idioma del navegador.

> **Consejo:** Haz clic fuera de la barra o de la burbuja para cerrarlas.

---

## Atajos de teclado

| Atajo | Atajo en Mac | Acción |
|-------|--------------|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Activar o desactivar las anotaciones furigana |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Hablar el texto seleccionado |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traducir el texto seleccionado |

> **Consejo:** Puedes personalizar estos atajos en Chrome en `chrome://extensions/shortcuts`.

---

## Guía de ajustes

| Ajuste | Descripción |
|--------|-------------|
| **Activar furigana** | Interruptor principal para activar o desactivar el furigana |
| **Furigana en toda la página** | Muestra furigana para todos los kanji (puede afectar al diseño) |
| **Modo al pasar el cursor** | Comportamiento al pasar el ratón: Diccionario (lectura + definiciones + JLPT + audio), Lectura (lectura + audio) o Desactivado |
| **Estilo de furigana** | Hiragana, katakana o rōmaji |
| **Velocidad de voz** | Velocidad de la lectura en voz alta |
| **Motor de traducción** | Bing Translate o Google Translate |
| **Idioma de destino** | Idioma al que traducir (detección automática según el navegador) |
| **Detección inteligente de PDF** | Redirige automáticamente las URLs PDF al lector integrado y muestra avisos cuando se detectan PDF |

---

## Preguntas frecuentes

**P: ¿Por qué no funciona en algunas páginas?**  
R: Por seguridad, las extensiones no se ejecutan en páginas especiales (`chrome://`), en la configuración del navegador ni en la Chrome Web Store.

**P: ¿Y si los furigana no son exactos?**  
R: Palabras poco frecuentes o lecturas especiales (jukujikun) pueden fallar. Seguimos mejorando; los casos concretos nos ayudan.

**P: ¿No hay sonido en la síntesis de voz?**  
R: Comprueba el volumen del sistema y que tengas voces en japonés instaladas. El soporte varía según navegador y sistema operativo.

**P: ¿El modo de página completa afecta al diseño?**  
R: Los furigana necesitan espacio extra. Si dificulta la lectura, desactiva el modo de página completa y usa la información al pasar el cursor.

**P: ¿La traducción no funciona?**  
R: La traducción requiere conexión a internet. Si falla Bing Translate, prueba Google Translate en los ajustes. Algunas redes pueden bloquear los servicios de traducción.

**P: ¿Cómo abro un PDF con Furigana Reader?**  
R: Puedes abrir PDF de varias formas: «Abrir lector PDF» en el menú emergente, clic derecho en un enlace PDF y «Abrir PDF con Furigana Reader», o activar «Detección inteligente de PDF» para redirigir automáticamente las URLs PDF al lector integrado.

**P: Tengo activada la detección inteligente de PDF pero algunos no se redirigen**  
R: La redirección automática funciona para URLs que terminan en `.pdf`. Para PDF servidos sin extensión `.pdf` o abiertos en el visor de Chrome, verás una notificación o insignia para abrirlos en Furigana Reader.

**P: ¿Puedo usar el diccionario sin conexión?**  
R: Sí. El diccionario JMdict (más de 180 000 entradas) va incluido en la extensión. Las consultas son locales, sin red.

---

## Enlaces relacionados

- [Política de privacidad](../privacy-policy)
- [Soporte y comentarios](../support)

---
