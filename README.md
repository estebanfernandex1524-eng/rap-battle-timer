🎤 Rap Battle Timer - Freestyle App

Rap Battle Timer es una aplicación web progresiva (PWA) diseñada para organizar, gestionar y practicar batallas de rap y freestyle. Funciona completamente en el navegador, sin necesidad de servidores ni internet una vez cargada.

🔥 Características Principales

Temporizador de Batalla Profesional:

Control de turnos para MC A y MC B.

Indicadores visuales de "Turno Activo".

Tiempos configurables y modos de muerte súbita.

Modos de Juego:

Libre: Cronómetro simple.

Palabras (Rima): Genera palabras con dificultad variable para rimar al momento.

Temática: Propone conceptos abstractos o situaciones.

Internacional: Mezcla palabras en Español, Inglés, Italiano, Francés, etc.

Práctica (Flow): Generación automática de palabras cada 10 segundos (configurable) para entrenar el flujo mental.

Banco de Palabras Inteligente:

Más de 200 palabras y conceptos pre-cargados.

Clasificación por idioma y dificultad (Easy/Hard).

Incluye terminología clásica del Hip Hop y expresiones mundiales ("Cypher", "Olé", "Mic Drop").

Text-to-Speech (TTS):

La aplicación "lee" la palabra generada usando la API de voz del navegador, ayudando a mantener el ritmo sin mirar la pantalla todo el tiempo.

Persistencia de Datos:

Guarda tus configuraciones (idioma, tiempos, nombres de MCs) automáticamente. Si cierras la pestaña, al volver todo estará igual.

🚀 Cómo publicar en GitHub Pages

Sigue estos pasos para tener tu app online en 2 minutos:

Crea un nuevo repositorio en GitHub (ej: rap-battle-timer).

Sube los archivos index.html y README.md a la raíz del repositorio.

Ve a la pestaña Settings (Configuración) del repositorio.

En el menú lateral, busca Pages.

En "Source", selecciona Deploy from a branch.

En "Branch", selecciona main (o master) y la carpeta / (root).

Haz clic en Save.

Espera unos segundos y GitHub te dará el link de tu app (ej: https://tu-usuario.github.io/rap-battle-timer/).

🎮 Cómo Usar

Configuración: Toca el icono de engranaje ⚙️ para cambiar el tiempo de ronda, el intervalo de palabras o los nombres de los MCs.

Modo: Selecciona el modo en el panel superior (Easy, Hard, Theme, Intl).

Batalla:

Dale a PLAY ▶️ para iniciar.

Si estás en modo Práctica, las palabras cambian solas.

Si estás en batalla, usa el botón Cambiar Turno ⇄ para pasar el tiempo al otro MC.

Idioma: Usa el interruptor ES/EN en la esquina superior derecha para cambiar el idioma de la interfaz.

🛠️ Desarrollo y Extensión

Agregar nuevas palabras

Abre el archivo index.html con cualquier editor de texto. Busca la constante WORD_BANK dentro de la etiqueta <script>.
Añade tus palabras siguiendo este formato:

{ text: "Tu Palabra", lang: "es", type: "hard", category: "urban" },


Tecnologías

HTML5 Semántico

CSS3 (Variables, Flexbox, Grid, Animaciones)

Vanilla JavaScript (ES6+)

Web Speech API

LocalStorage API

📄 Licencia

Este proyecto está bajo la Licencia MIT. Eres libre de usarlo, modificarlo y compartirlo.
