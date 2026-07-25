# 🎓 aules-skills

Herramientas para generar actividades y cursos evaluables para **Aules** (Moodle de la Generalitat Valenciana), pensadas para usarse con un asistente IA (Claude) o directamente por línea de comandos. Todo el material se comparte bajo licencia **CC BY-SA 4.0** — libre de usar y adaptar citando la autoría (Jose Manuel Sánchez Vilchez).

## Catálogo

| Repositorio | Qué genera | Formato de salida |
|---|---|---|
| [ahorcado](https://github.com/aules-skills/ahorcado) | Juego del Ahorcado evaluable | SCORM (.zip) |
| [binary-game](https://github.com/aules-skills/binary-game) | Clon del Binary Game de Cisco (decimal↔binario) | SCORM (.zip) |
| [pasapalabra](https://github.com/aules-skills/pasapalabra) | Rosco / Pasapalabra evaluable | SCORM (.zip) |
| [h5p](https://github.com/aules-skills/h5p) | Crucigrama, sopa de letras, huecos, arrastrar palabras | H5P (.h5p) |
| [pdf-a-h5p](https://github.com/aules-skills/pdf-a-h5p) | Igual que `h5p`, partiendo de un PDF | H5P (.h5p) |
| [h5p-quiz](https://github.com/aules-skills/h5p-quiz) | Cuestionario tipo test con banco de preguntas | H5P (.h5p) |
| [forms-quiz](https://github.com/aules-skills/forms-quiz) | Cuestionario desde subtítulos de vídeo | .docx (Forms) + Aiken (Aules) |
| [cursoaules](https://github.com/aules-skills/cursoaules) | Curso completo de Aules desde un currículum PDF (temas + libro de calificaciones por competencias) | Backup Moodle (.mbz) |
| [html2pdf](https://github.com/aules-skills/html2pdf) | Botón de exportar a PDF + marcadores de sesión para páginas HTML de apuntes | Inyección en HTML |

## Qué tienen en común

Todas las skills de juegos (ahorcado, binary-game, pasapalabra) generan paquetes **SCORM** que registran nota sobre 10 y tiempo en el libro de calificaciones de Aules. Las de tipo **H5P** (h5p, pdf-a-h5p, h5p-quiz) se autocorrigen y puntúan como actividad H5P normal. Todas están pensadas para usarse conversando con un asistente IA: le das un PDF, unos apuntes o un tema, y el asistente redacta el contenido y ejecuta el script.

## Cómo empezar

Entra en el repositorio que te interese — cada uno tiene su propio README con instrucciones paso a paso, requisitos y ejemplos.

## Licencia

CC BY-SA 4.0 en todos los repositorios. Libre de usar, compartir y adaptar citando la autoría.
