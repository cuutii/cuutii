<!--
  ============================================================
  README DE PERFIL DE GITHUB  (usuario: cuutii)
  ============================================================
  Es lo primero que se ve en https://github.com/cuutii
  Regla de esta página: solo datos verificables. Si hay un número
  escrito acá, se contó con `gh repo list cuutii` o leyendo el
  código de cada proyecto. Nada de badges decorativos.
  ============================================================
-->

<h1 align="center">Hola, soy Maximo Sanabria</h1>

<p align="center">
  <b>Estudiante de programación · Buscando mi primer trabajo</b><br>
  Escribo web a mano, sin frameworks, y la publico:
  <b>7 de mis proyectos están en vivo ahora mismo</b>, y el código de cada uno está abierto al lado.
</p>

---

## Qué puedo aportar

Construyo cosas que se pueden abrir y probar en el momento: una bóveda de contraseñas que cifra en tu navegador, un mapa que sigue andando sin internet, una landing lista para publicar. Cada proyecto ataca un problema concreto y declara abiertamente **qué no resuelve**.

No tengo experiencia laboral que mostrar todavía. Lo que sí puedo mostrar está acá abajo, funcionando.

---

## 🔎 Mirá esto primero (30 segundos)

1. 🔐 **[Bóveda](https://cuutii.github.io/gestor-contrasenas/)** — gestor de contraseñas que cifra con AES-GCM **en tu navegador**: sin servidor, sin base de datos y sin una sola petición de red.
2. 🗺️ **[Perito Map](https://cuutii.github.io/perito-map/)** — mapa de glaciares instalable como app que, después de la primera carga, **anda sin internet**.
3. 📄 **[CV en PDF](https://github.com/cuutii/Portfolio-Maximo/blob/main/Curriculum%20Sanabria%20Maximo%20PDF.pdf)** — si preferís ir directo al perfil.

---

## ✅ Lo que ya está publicado

Tengo 10 repos públicos; estos 7 tienen sitio propio corriendo en GitHub Pages.

- 🔐 **[Bóveda](https://cuutii.github.io/gestor-contrasenas/)** · [código](https://github.com/cuutii/gestor-contrasenas) — Guardar contraseñas cifradas (AES-GCM de 256 bits, clave derivada con PBKDF2) sin que un servidor jamás las vea. Se instala como app y funciona offline.
- 🗺️ **[Perito Map](https://cuutii.github.io/perito-map/)** · [código](https://github.com/cuutii/perito-map) — Recorrer los glaciares del Calafate en un mapa con fotos reales y clima en vivo, pensado para el celular y para usarse sin señal.
- 🔑 **[Generador de contraseñas](https://cuutii.github.io/generador-contrasenas/)** · [código](https://github.com/cuutii/generador-contrasenas) — Crear contraseñas con aleatoriedad criptográfica y medir su fortaleza en tiempo real. Un solo archivo, sin dependencias.
- 🧳 **[Explore Calafate](https://cuutii.github.io/Explore-Calafate/)** · [código](https://github.com/cuutii/Explore-Calafate) — Guía turística con reseñas de turistas filtrables por país e idioma, publicadas una por una a mano para que ninguna sea inventada.
- 💻 **[Portfolio](https://cuutii.github.io/Portfolio-Maximo/)** · [código](https://github.com/cuutii/Portfolio-Maximo) — Mi presentación con estética de terminal: habilidades, proyectos y CV en PDF descargable desde la propia página.
- 🤝 **[Fernanda](https://cuutii.github.io/Fernanda/)** · [código](https://github.com/cuutii/Fernanda) — Landing page de una consultora freelance de RRHH: 6 servicios, HTML semántico y accesible, sin dependencias.
- 📖 **[Progresivo](https://cuutii.github.io/Progresivo/)** · [código](https://github.com/cuutii/Progresivo) — Ejercicio que muestra la misma página con y sin CSS, para entender qué hace realmente el estilo.

Sin sitio (es de consola): **[Cal.Tri](https://github.com/cuutii/Cal.Tri)**, mi primer programa en C++: menú con validación de opciones que calcula áreas de figuras.

---

## 🛠️ Qué usa mi código

Tecnologías que están en el código de arriba, no en una lista de deseos:

- **HTML5 · CSS3 · JavaScript** — los 7 sitios son estáticos, escritos a mano y sin frameworks.
- **WebCrypto API** — `crypto.subtle` con PBKDF2-SHA-256 (600.000 iteraciones) y AES-GCM de 256 bits en Bóveda; `crypto.getRandomValues` en el generador de contraseñas.
- **Service Worker + Cache API** y **Web App Manifest** — Bóveda y Perito Map, las dos instalables como app.
- **Leaflet + OpenStreetMap** — el mapa de Perito Map, con la librería copiada en el repo en vez de un CDN.
- **API REST (Open-Meteo)** — clima en vivo en Perito Map.
- **localStorage · Geolocation API** — recorrido y clima guardados, botón "Mi ubicación".
- **Content-Security-Policy** — Bóveda declara `connect-src 'none'`: la página no tiene permitido llamar a ningún lado.
- **C++** — Cal.Tri, en consola (`iostream`, `conio.h`).

---

## 🧪 Cómo comprobarlo en 30 segundos

1. Abrí **[la demo de Bóveda](https://cuutii.github.io/gestor-contrasenas/)** y creá una bóveda con una contraseña de prueba. Si querés ver la parte difícil, [crypto.js](https://github.com/cuutii/gestor-contrasenas/blob/main/src/crypto.js) tiene el cifrado comentado.
2. Abrí **[Perito Map](https://cuutii.github.io/perito-map/)**, esperá a que cargue el mapa y apagá los datos del celular: sigue funcionando.
3. ¿Algo no te cierra? El código de los 7 proyectos es público. Si encontrás un error, mejor todavía: avisame.

---

## 📬 Contacto

- **GitHub:** [@cuutii](https://github.com/cuutii)
- **LinkedIn:** [Maximo Sanabria](https://www.linkedin.com/in/maximo-sanabria-cutib/)

---

<p align="center"><i>Gracias por llegar hasta acá.</i></p>
