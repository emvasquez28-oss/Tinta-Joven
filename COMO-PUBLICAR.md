# Cómo publicar un texto en Tinta Joven

Cada texto de la revista es un archivo dentro de la carpeta [`textos`](textos). La página lo muestra sola en su sección (Periodismo o Literario), uno o dos minutos después de subirlo. Si olvidas la sección, la página la deduce del género.

## Publicar un texto nuevo

1. Abre la plantilla [`textos/_plantilla.md`](textos/_plantilla.md) y copia todo su contenido.
2. Entra a la carpeta [`textos`](textos) y pulsa **Add file → Create new file** (Agregar archivo → Crear archivo nuevo).
3. Ponle un nombre corto, sin tildes ni espacios y terminado en `.md`. Por ejemplo: `el-dia-que-llovio.md`.
4. Pega la plantilla y cambia los datos de arriba (entre las dos líneas `---`) y el texto de abajo.
5. Pulsa **Commit changes** (Confirmar cambios). Listo.

También puedes escribir el archivo en tu computador y subirlo con **Add file → Upload files**.

## Los datos de arriba

| Dato | Qué escribir |
| --- | --- |
| `titulo` | El título, máximo 12 palabras |
| `autor` | Nombre del estudiante |
| `grado` | Grado y curso, por ejemplo `9.º B` |
| `seccion` | `Periodismo` o `Literario` |
| `genero` | En Periodismo: `Noticia`, `Crónica`, `Artículo`, `Reportaje`, `Caricatura`, `Entrevista` o `Reseña`. En Literario: `Cuento`, `Poesía`, `Minirrelato`, `Cine` o `Música` |
| `fecha` | Fecha de publicación como `2026-11-20` (año-mes-día). Los textos más recientes salen primero |
| `bajada` | Una o dos frases de resumen |
| `imagen` | Opcional. La ruta de una foto subida a la carpeta `imagenes`, por ejemplo `imagenes/feria.jpg`. Si no hay foto, borra esa línea |

## Añadir una foto

1. Entra a la carpeta [`imagenes`](imagenes) y pulsa **Add file → Upload files**.
2. Sube la foto con un nombre sin tildes ni espacios, como `feria-de-ciencias.jpg`.
3. En el texto, escribe `imagen: imagenes/feria-de-ciencias.jpg`.

Usa fotos propias o con permiso, y no muestres la cara de estudiantes sin autorización de su familia.

## Caricaturas

Sube el dibujo a la carpeta `imagenes`, escribe su ruta en `imagen:` y usa `genero: Caricatura`. Debajo de las líneas `---` basta con una frase o el texto de la viñeta.

## Corregir o quitar un texto

- **Corregir:** abre el archivo en la carpeta `textos`, pulsa el lápiz ✏️, cambia lo necesario y pulsa **Commit changes**.
- **Quitar:** abre el archivo, pulsa los tres puntos `…` y elige **Delete file**. GitHub guarda el historial, así que se puede recuperar.
- **Guardar sin publicar todavía:** pon un `_` al inicio del nombre del archivo (por ejemplo `_borrador-cuento.md`). La página no muestra esos archivos.

## Formato del texto

- Deja una línea en blanco entre párrafos.
- En poesía, cada verso en su propia línea y una línea en blanco entre estrofas.
- `**negrilla**`, `*cursiva*`, `## Subtítulo` y `> cita` funcionan como en la plantilla.

Si un texto no aparece después de 5 minutos, revisa que el nombre termine en `.md`, que no empiece por `_` y que las dos líneas `---` estén completas.
