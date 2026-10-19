<img src="banner.svg" alt="DASANMOS" width="100%"/>

<h1 align="center">David Santiago Mosquera · DASANMOS</h1>

<p align="center">
  <b>Desarrollador autodidacta que construye tecnología para la educación pública</b><br>
  <i>Aprendiz SENA · Técnico en Desarrollo de Software · Medellín, Colombia</i>
</p>

<p align="center">
  <a href="https://serena.infinityfreeapp.com"><img src="https://img.shields.io/badge/▶_DEMO-Serena-39A900?style=for-the-badge"/></a>
  <a href="https://github.com/dasanmos/serena"><img src="https://img.shields.io/badge/CÓDIGO-Serena-181717?style=for-the-badge&logo=github"/></a>
</p>

<p align="center">
  <a href="#-sobre-mí">Sobre mí</a> ·
  <a href="#-proyecto-estrella-serena">Serena</a> ·
  <a href="#-más-proyectos">Más proyectos</a> ·
  <a href="#-trayectoria">Trayectoria</a> ·
  <a href="#-docencia">Docencia</a> ·
  <a href="#-tecnologías">Tecnologías</a> ·
  <a href="#-estadísticas">Estadísticas</a>
</p>

---

## 🧠 Sobre mí

Estudio en la **I.E. INEM José Félix de Restrepo** (Media Técnica en Programación de Software) y soy aprendiz del **SENA**. Empecé a programar con un juego en Python y desde entonces aprendo por mi cuenta y lo aplico enseguida: **cada proyecto que ves aquí nació de una necesidad real de mi colegio y lo usa gente real.**

Mi meta es ser **ingeniero de sistemas y docente**, y algún día liderar una institución educativa pública.

| | |
|---|---|
| 🔭 **Ahora** | Socializando **Serena** en la etapa productiva del SENA y administrando el sistema escolar de mi curso |
| 🌱 **Aprendiendo** | `TypeScript` · `React` · `Java` · `Spring Boot` |
| 🎯 **Ruta** | Técnico en Desarrollo de Software (SENA) → Normalista o licenciatura → Ingeniería de Sistemas |
| 🤝 **Busco colaborar en** | EdTech para instituciones públicas |

---

## 🌟 Proyecto estrella: Serena

<p align="center">
  <img src="https://raw.githubusercontent.com/dasanmos/serena/main/public/assets/img/logo/logo.png" alt="Logo de Serena" width="140"/>
</p>

<p align="center"><b>Plataforma web académica y de bienestar emocional para toda la institución, desde grado sexto.</b></p>

Las apps de bienestar miden emociones, hábitos o diario **por separado**, y las plataformas académicas solo gestionan notas y matrículas. **Serena reúne las dos cosas y conecta al estudiante con psicología y orientación a tiempo**, con costo cero para la institución.

<p align="center">
  <a href="https://serena.infinityfreeapp.com"><b>🔗 Demo en vivo</b></a> ·
  <a href="https://github.com/dasanmos/serena"><b>💻 Código</b></a> ·
  <a href="https://github.com/dasanmos/serena/blob/main/docs/Presentacion_Serena_SENA_final.pptx"><b>📑 Presentación</b></a> ·
  <a href="https://github.com/dasanmos/serena/blob/main/docs/INSTALACION.md"><b>⚙️ Instalación</b></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/dasanmos/serena/main/public/assets/img/ayuda/est-inicio-1.jpg" alt="Inicio del estudiante" width="32%"/>
  <img src="https://raw.githubusercontent.com/dasanmos/serena/main/public/assets/img/ayuda/est-emociones-1.jpg" alt="Registro emocional" width="32%"/>
  <img src="https://raw.githubusercontent.com/dasanmos/serena/main/public/assets/img/ayuda/doc-seguimiento-1.jpg" alt="Seguimiento del docente" width="32%"/>
</p>

| 11 | 110 | 69 | 125 | 4 | $0 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| roles con su propio panel | tablas en la base | informes en PDF y CSV | capturas en el manual | métodos de 2FA | costo para la institución |

<table>
<tr>
<td width="50%" valign="top">

**💛 Bienestar emocional**
- Emociones varias veces al día, con color y nota
- Sueño, hábitos y metas con rachas e insignias
- Diario personal protegido con PIN
- **Alertas tempranas** tras días de ánimo bajo
- Chat y citas con psicología u orientación
- Encuestas, respiración guiada y líneas de ayuda

</td>
<td width="50%" valign="top">

**📚 Gestión académica**
- Inscripción web, matrícula y renovación
- Notas, planilla de seguimiento y boletín
- Asistencia con alerta de ausentismo
- Horarios con detección de cruces
- Hoja de vida, convivencia (Ley 1620) y cuentas de familia
- Certificados con **código QR verificable**, SIMAT y SIMPADE

</td>
</tr>
</table>

<details>
<summary><b>👥 Roles y privacidad por diseño</b></summary>
<br>

`estudiante` · `acudiente` · `docente` · `psicólogo` · `orientador` · `coordinador` · `rector` · `secretaría académica` · `administrador` · `Secretaría de Educación` · `superadmin`

- Cada persona ve solo lo que necesita: el diario es solo del estudiante, y sus emociones solo las ven psicología y orientación (el orientador, de sus grupos).
- Coordinación, rectoría y la Secretaría de Educación ven el bienestar **solo en cifras agregadas**.
- **Una persona, una cuenta:** quien es docente y madre, por ejemplo, entra con la misma cuenta y elige el rol. Si su documento está en varios colegios, elige la institución.
- Cada colegio está aislado de los demás, y cada consulta a una hoja de vida queda registrada.

</details>

<details>
<summary><b>🔐 Seguridad</b></summary>
<br>

- Consentimiento de tratamiento de datos (**Ley 1581 de 2012**)
- Verificación en 2 pasos: app autenticadora, correo, WhatsApp o rostro (secretos cifrados con AES-256-GCM)
- Sentencias preparadas (PDO), tokens CSRF y control de acceso por rol y por estudiante
- Límite de intentos en el inicio de sesión, el PIN y la verificación en 2 pasos
- Enlaces de recuperación con token cifrado y de un solo uso
- Sesiones activas visibles y bitácora de auditoría

</details>

<details>
<summary><b>✨ Experiencia, IA y modo demostración</b></summary>
<br>

- Diseño con color por módulo y por emoción, animaciones y sonidos sintetizados (se respetan «reducir movimiento» y el alto contraste).
- Asistente **«Pregúntale a Serena»** y análisis en informes con IA opcional; los datos se anonimizan antes de enviarse.
- **Modo demostración:** una cuenta maestra recorre los 11 roles sobre un colegio ficticio que se restablece en un clic.
- Centro de ayuda por rol con buscador, manual descargable y 125 capturas generadas automáticamente.
- Responsive, modo oscuro y dictado por voz.

</details>

**Stack:** `PHP 8.1+` `MySQL` `HTML` `CSS` `JavaScript` · sin frameworks · hosting InfinityFree<br>
**Equipo:** David Santiago Mosquera Mosquera (desarrollador full stack, Product Owner y analista de requerimientos) y Ana Sofía Ángel Moncada (gestora de proyectos y diseñadora UI/UX).

### 🧪 Lo que aprendí construyendo Serena

| Reto | Cómo lo resolví |
|---|---|
| El hosting gratuito no deja usar `public/` como raíz | `index.php` que redirige y `.htaccess` que blinda `src/`, `sql/` y los `.env` |
| El puerto SMTP está bloqueado | Correos por la API HTTPS de Brevo |
| Datos de menores (Ley 1581) | Permisos por rol **y** por estudiante, registro de cada consulta y cifras agregadas para directivos |
| Una docente que también es madre | Cuentas **multirol**: una sola cuenta y elige con qué rol entrar |
| El mismo documento en dos colegios | Al iniciar sesión, Serena pregunta a qué institución entrar |
| Verificación en 2 pasos sin librerías | TOTP propio según las RFC 6238 y 4226, con secretos cifrados con AES-256-GCM |
| Mantener el manual al día | Script con Playwright que toma solas las 125 capturas de la ayuda |

---

## 🧭 Trayectoria

```
🐍  Primer juego en Python ─────────────► empecé a aprender por mi cuenta
🗓️  Horario INEM (PWA con Firebase) ────► mi primera plataforma con usuarios reales
🏦  Banco Escolar ──────────────────────► gamificación para enseñar finanzas
💙  Bienestar estudiantil (Spring Boot) ─► primer acercamiento al bienestar emocional
🎙️  SonoColeMP ─────────────────────────► trabajo en equipo
🤖  Citaciones ICFES (Playwright) ──────► automatización para 138 compañeros
🌟  Serena ─────────────────────────────► plataforma académica y de bienestar, 11 roles
```

---

## 🚀 Más proyectos

| Proyecto | Qué resuelve | Tecnología | Enlace |
|---|---|---|---|
| 🗓️ **Horario INEM XI-10** | PWA que administro para mi curso: horario, asistencia, compromisos, cartelera con encuestas anónimas, calculadora de notas, Pomodoro y notificaciones push. Cuatro roles: administrador, profesor, monitor y estudiante. | `Firebase` `JavaScript` `PWA` `Cloud Functions` | — |
| 🎙️ **SonoColeMP** | Plataforma de podcasts del colegio, hecha en equipo con Karen Palacio, Jose Ribon e Isabela Díaz. | `PHP` `MySQL` `Python` | [Demo](https://sonocolemp.infinityfreeapp.com/) |
| 🏦 **Banco Escolar** | Banca gamificada para enseñar economía y finanzas personales en el aula. | `JavaScript` `Firebase` | [Demo](https://banco-escolar-david.netlify.app) |
| 💙 **Bienestar estudiantil** | Mi primer acercamiento al bienestar emocional, que después evolucionó en Serena. Backend por capas. | `Java` `Spring Boot` `Firebase` | [Código](https://github.com/dasanmos/plataforma-bienestar-estudiantil) |
| 📊 **PreIcfes 2026** | Simulacros con motor de calificación estilo Saber 11°: hoja de respuestas, bloqueo de sesión y ponderación por área. Multirol. | `PHP` `MySQL` | — |
| 🤖 **Citaciones ICFES** | Descargó las citaciones de **138 estudiantes** sin una sola descarga manual, resolviendo formularios JSF/PrimeFaces. | `Python` `Playwright` | — |

---

## 🎓 Docencia

No solo construyo software para el aula: también he estado al frente de ella.

- He reemplazado a profesores ausentes en mi colegio, con actividades propias.
- Busco unir **programación y docencia** en una carrera de tecnología educativa.
- Mis fuertes: Matemáticas, Geometría, Economía y Política, y Tecnología e Informática.

---

## 🛠️ Tecnologías

**Uso a diario**<br>
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Aprendiendo**<br>
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

**Herramientas:** GitHub · Netlify · InfinityFree · Google Cloud Functions · Playwright

---

## 📈 Estadísticas

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dasanmos&show_icons=true&hide_border=true&title_color=8A6A00&icon_color=E8B923&text_color=2B2B2B&bg_color=FFFDF6&locale=es" alt="Estadísticas de GitHub" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dasanmos&layout=compact&hide_border=true&title_color=8A6A00&text_color=2B2B2B&bg_color=FFFDF6&locale=es" alt="Lenguajes más usados" height="165"/>
</p>

---

## 🌱 Cómo trabajo

- **Personas primero:** cada proyecto nació de una necesidad real en mi colegio.
- **Datos de estudiantes con cuidado:** seguridad y confidencialidad desde el diseño, no al final.
- **Entender antes de copiar:** busco el porqué de cada solución antes de implementarla.
- **Documentar para otros:** guías de instalación, manual por rol y notas de cada fase, para que cualquiera pueda continuar el trabajo.

---

## 📫 Hablemos

¿Trabajas en un colegio público, en una Secretaría de Educación o en un proyecto EdTech? Escríbeme abriendo un *issue* en [Serena](https://github.com/dasanmos/serena/issues) o en cualquiera de mis repositorios.

<p align="center"><i>Tecnología y educación · Innovación formativa</i></p>
