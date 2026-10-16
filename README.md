<img src="banner.svg" alt="DASANMOS" width="100%"/>

<h1 align="center">👨‍💻 David Santiago Mosquera · DASANMOS 📚</h1>

<p align="center">
  <b>Desarrollador autodidacta · Tecnología aplicada a la educación</b><br>
  <i>Tecnología y educación · Innovación formativa</i>
</p>

<p align="center">
  <a href="https://serena.infinityfreeapp.com"><img src="https://img.shields.io/badge/▶_DEMO-Serena-39A900?style=for-the-badge"/></a>
  <a href="https://github.com/dasanmos/serena"><img src="https://img.shields.io/badge/CÓDIGO-Serena-181717?style=for-the-badge&logo=github"/></a>
</p>

<p align="center">
  <a href="https://banco-escolar-david.netlify.app"><img src="https://img.shields.io/badge/demo-Banco_Escolar-2E7D32?style=flat"/></a>
  <a href="https://sonocolemp.infinityfreeapp.com/"><img src="https://img.shields.io/badge/demo-SonoColeMP-1B5E20?style=flat"/></a>
  <a href="https://github.com/dasanmos/plataforma-bienestar-estudiantil"><img src="https://img.shields.io/badge/code-Bienestar_Estudiantil-1565C0?style=flat"/></a>
</p>

<p align="center">
  <a href="#-sobre-mí">Sobre mí</a> ·
  <a href="#-proyecto-estrella-serena">Serena</a> ·
  <a href="#-más-proyectos">Más proyectos</a> ·
  <a href="#-docencia-y-educación">Docencia</a> ·
  <a href="#️-tecnologías">Tecnologías</a>
</p>

---

## 🧠 Sobre mí

Grado XI-10 · **I.E. INEM José Félix de Restrepo**, Medellín, Colombia
Media Técnica en Programación de Software · Aprendiz SENA (Técnico en Desarrollo de Software)

Empecé a programar con un juego en Python y desde entonces no he parado de aprender por mi cuenta. Diseño, desarrollo y administro plataformas académicas que usa gente real en mi colegio: horarios, bienestar emocional, banca gamificada, podcasts y preparación para el ICFES.

Mi meta es doble: **ingeniero de sistemas y docente**. Quiero combinar ambas cosas en una carrera enfocada en tecnología educativa y, a largo plazo, liderar una institución educativa pública.

| | |
|---|---|
| 🔭 **Ahora mismo** | Llevando **Serena** a la socialización de etapa productiva del SENA y administrando el sistema escolar de mi curso, XI-10. |
| 🌱 **Aprendiendo** | `TypeScript` · `React` · `Java` · `Spring Boot` |
| 🎯 **Ruta hacia la docencia** | Técnico en Programación de Software (SENA) → Normalista Superior / licenciatura → Ingeniería de Sistemas |
| 🤝 **Abierto a colaborar** | Proyectos EdTech, sobre todo herramientas para instituciones públicas |

---

## 🌟 Proyecto estrella: Serena

<p align="center">
  <img src="https://raw.githubusercontent.com/dasanmos/serena/main/public/assets/img/logo/logo.png" alt="Logo de Serena" width="150"/>
</p>

<p align="center"><b>Plataforma web académica y de bienestar emocional para toda la institución educativa, desde grado sexto.</b><br><i>Cuerpo · Mente · Bienestar</i></p>

Las apps de bienestar miden emociones, hábitos o diario **por separado**, y las plataformas académicas solo gestionan notas y matrículas. **Serena reúne las dos cosas en un solo lugar y conecta al estudiante con psicología y orientación.** Es gratuita para la institución: PHP y MySQL libres y hosting gratuito.

<p align="center">
  <a href="https://serena.infinityfreeapp.com"><b>🔗 Demo en vivo</b></a> ·
  <a href="https://github.com/dasanmos/serena"><b>💻 Código fuente</b></a> ·
  <a href="https://github.com/dasanmos/serena/blob/main/docs/Presentacion_Serena_SENA_final.pptx"><b>📑 Presentación</b></a> ·
  <a href="https://github.com/dasanmos/serena/blob/main/docs/INSTALACION.md"><b>⚙️ Instalación</b></a>
</p>

<table>
<tr>
<td width="50%" valign="top">

**💛 Bienestar emocional**
- Registro de emociones varias veces al día
- Sueño, hábitos y metas con rachas e insignias
- Diario personal protegido con PIN
- Estadísticas e informe en PDF
- Alertas tempranas tras días de ánimo bajo
- Chat y citas con psicología u orientación
- Encuestas, respiración guiada y líneas de ayuda

</td>
<td width="50%" valign="top">

**📚 Gestión académica**
- Inscripción web, matrícula y renovación
- Notas, planilla de seguimiento y boletín
- Asistencia con alerta de ausentismo
- Horarios con detección de cruces
- Hoja de vida y convivencia (Ley 1620)
- Certificados con **código QR verificable**
- Informes en PDF/CSV, SIMAT y SIMPADE

</td>
</tr>
</table>

<details>
<summary><b>👥 Los 11 roles, cada uno con su propio panel</b></summary>
<br>

`estudiante` · `acudiente` · `docente` · `psicólogo` · `orientador` · `coordinador` · `rector` · `secretaría académica` · `administrador` · `secretaría de educación` · `superadmin`

Coordinación y rectoría solo ven informes **agregados**, sin datos individuales de bienestar. Cada colegio está aislado de los demás.

</details>

<details>
<summary><b>🔐 Seguridad y privacidad</b></summary>
<br>

- Consentimiento explícito de tratamiento de datos (**Ley 1581 de 2012**)
- Verificación en 2 pasos: app autenticadora, correo, WhatsApp o rostro (secretos cifrados con AES-256-GCM)
- Sentencias preparadas (PDO), tokens CSRF y control de acceso por rol
- 5 intentos fallidos bloquean la cuenta 15 minutos
- Sesiones activas visibles y bitácora de auditoría

</details>

<details>
<summary><b>🤖 IA, modo demostración y más</b></summary>
<br>

- Asistente **«Pregúntale a Serena»** y análisis en informes con OpenRouter (modelos gratuitos); los datos se anonimizan antes de enviarse y la IA es opcional.
- **Modo demostración:** una cuenta maestra recorre los 11 roles sobre un colegio ficticio que se restablece en un clic.
- **Varios colegios:** capa de Secretaría de Educación con semáforo, comparativos y comunicados.
- Centro de ayuda integrado por rol, responsive (celular, tablet y computador) y modo oscuro.

</details>

**Stack:** `PHP 8.1+` `MySQL 8` `HTML` `CSS` `JavaScript` · sin frameworks · hosting InfinityFree
**Equipo:** David Santiago Mosquera Mosquera y Ana Sofía Ángel Moncada (aprendices SENA).

---

## 🚀 Más proyectos

### 🗓️ Horario INEM XI-10 — Sistema Escolar Integral (PWA)

> De horario simple a plataforma completa con roles, asistencia y comunidad.

Aplicación web progresiva sobre **Firebase (Firestore + Authentication)** que administro activamente para mi curso. Nació como un horario de clases y creció hasta tener cuatro roles: administrador, profesor, monitor y estudiante.

- 📅 Horario de clases y control de asistencia
- ✅ Tarjetas de compromisos y cartelera comunitaria con encuestas anónimas
- 🧮 Calculadoras de notas, temporizador Pomodoro y modo de presentación para TV
- 🔔 Notificaciones push vía Cloud Functions
- 🎨 Identidad visual propia (dorado/negro/crema, tipografía EB Garamond)

`Firebase` `Firestore` `JavaScript` `PWA` `Cloud Functions`

---

### 🎙️ SonoColeMP — Plataforma de podcast escolar

Plataforma local de streaming de podcasts, desarrollada en equipo con Karen Palacio, Jose Ribon e Isabela Díaz.

🔗 [Ver demo](https://sonocolemp.infinityfreeapp.com/) · `PHP` `MySQL` `Python`

---

### 🏦 Banco Escolar

> Economía y hábitos financieros, gamificados para el aula.

Banca gamificada como herramienta de apoyo docente para enseñar economía y finanzas personales.

🔗 [Ver demo](https://banco-escolar-david.netlify.app) · `HTML` `CSS` `JavaScript` `Firebase`

---

### 💙 Plataforma de bienestar estudiantil

Backend en **Spring Boot** con arquitectura por capas, conectado a un frontend web con Firebase. Fue el primer acercamiento al bienestar emocional que después evolucionó en Serena.

🔗 [Ver código](https://github.com/dasanmos/plataforma-bienestar-estudiantil) · `Java` `Spring Boot` `Firebase` `HTML/CSS/JS`

---

### 📊 Plataforma PreIcfes 2026

Sistema multi-rol (administrador, profesor, institución, estudiante) con motor de calificación estilo ICFES Saber 11°: hoja de respuestas, bloqueo de sesión y ponderación por área evaluada.

`PHP` `MySQL`

---

### 🤖 Automatización de citaciones ICFES

> 138 estudiantes, cero descargas manuales.

Script en **Python + Playwright**, ejecutado en Google Colab, que descargó las citaciones del examen ICFES Saber 11° de 138 estudiantes de grado 11. Resolvió formularios JSF/PrimeFaces y restricciones de accesibilidad móvil.

`Python` `Playwright` `Automatización`

---

## 🎓 Docencia y educación

No solo construyo software para el aula: también he estado en ella.

- He reemplazado a profesores ausentes en mi colegio, con actividades dinámicas propias.
- Exploro la ruta profesional para combinar **programación y docencia**.
- Interés en legislación docente, escalafón y proyección profesional en el sector educativo colombiano.
- Fortalezas: Matemáticas, Geometría, Economía y Política, Tecnología e Informática.

---

## 🛠️ Tecnologías

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

**Otras herramientas:** Netlify · GitHub · InfinityFree · Google Cloud Functions · Playwright

## 🌱 Cómo trabajo

- Aprendo por cuenta propia y lo aplico enseguida en proyectos reales.
- Construyo pensando en personas concretas: cada proyecto nació de una necesidad real en mi colegio.
- Me importan la seguridad y la confidencialidad, sobre todo cuando hay datos de estudiantes.
- Prefiero entender el porqué de una solución antes de implementarla, no solo copiar código.

---

<p align="center"><i>Tecnología y educación · Innovación formativa</i></p>
