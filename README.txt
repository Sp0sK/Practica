Practicador — Sífilis Congénita (deploy sin build)
=================================================

Este paquete está listo para subirse **tal cual** a Netlify desde un iPad (o cualquier navegador),
sin instalar Node, npm ni hacer `npm run build`.

Cómo publicarlo gratis en Netlify (desde iPad):
1) Entra a https://app.netlify.com/ (créate cuenta si no tienes).
2) "Add new site" → **Deploy manually**.
3) Sube la carpeta completa `practicador-sifilis-cdn` o sube el ZIP.
4) Netlify publicará una URL tipo: https://tusitio.netlify.app

Uso:
- En la web publicada, pulsa **Cargar banco (HTML)** y selecciona tu archivo `sifilis_congenita_banco_200.html`.
- Configura modo Flashcards/Examen, orden, bloques, etc.

Notas técnicas:
- Este paquete usa React y Tailwind vía CDN + Babel en el navegador para que funcione sin 
  proceso de build. Si más adelante quieres una versión con build (Vite), puedo generarte
  un proyecto completo para que despliegues con Vercel/Netlify conectado a GitHub.