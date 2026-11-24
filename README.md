# CNC & Cobot Studio v4.2 🦾⚙️

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Web App](https://img.shields.io/badge/Demo-Live%20Web%20App-emerald.svg)](https://cnccobotstudio.github.io/cnc-cobot-studio/)
[![Created by](https://img.shields.io/badge/Author-EagleCelest-amber.svg)](#)
[![Status](https://img.shields.io/badge/Release-v4.2%20Public%20Ready-blueviolet.svg)](#)

> [English Version](#-english-version) | [Versión en Español](#-versión-en-español)

---

## 🇬🇧 English Version

### 🚀 Overview
**CNC & Cobot Studio** is an open-source, zero-dependency, web-based 3D kinematic simulator, TCP configurator, and multi-robot post-processor for **6-DOF collaborative robots (Cobots)** and **5-axis CNC machining centers**.

Designed and engineered by **EagleCelest**, this project was created to democratize hands-on technical education in robotics, industrial automation, and advanced manufacturing without expensive hardware or proprietary software license barriers.

👉 **[Launch Live Web App in your browser](https://cnccobotstudio.github.io/cnc-cobot-studio/)**

---

### 🌟 Key Features

- **🦾 6-DOF Cobot Kinematics (UR10e / Fanuc CRX)**: Real-time simulation of joint coordinates ($J_1-J_6$) and Cartesian TCP positions with sub-millimeter precision.
- **🧭 Universal Tool Center Point (TCP) & Base Setup**: 4-point touch-off calibration wizard, dynamic coordinate frame offsets, and visual safety zones.
- **🔄 Multi-Robot Code Generation & Transpiler**:
  - Universal Robots (`URScript`: `movej`, `movel`, waypoint sequences).
  - Fanuc CRX / ISO G-code scripts.
- **🛡️ Built-in SIL-3 / ISO/TS 15066 Safety Simulator**: Real-time collaborative speed monitoring, collision envelope checks, and interlock safety stops.
- **⚡ 100% Client-Side & Lightweight**: Zero cloud latency, no server dependencies, no installation needed. Runs smoothly on any desktop, laptop, or tablet browser.

---

### 🎓 Educational Mission & Community

Quality industrial robotics software often carries prohibitive licensing costs. **CNC & Cobot Studio is 100% free for students, makers, independent entrepreneurs, and vocational schools (VET/FP).**

- **Vocational Training Centers & Universities**: Looking for classroom exercises, teacher kits, or curriculum integration?
- **Feedback, Questions & Suggestions**: Reach out directly at [`cnccobot.feedback@gmail.com`](mailto:cnccobot.feedback@gmail.com).

---

## 🇪🇸 Versión en Español

### 🚀 Resumen del Proyecto
**CNC & Cobot Studio** es una suite interactiva de simulación cinemática 3D, configuración de TCP/Base y postprocesamiento multirrobot para **Cobots de 6 grados de libertad (UR10e, Fanuc CRX)** y **mecanizado CNC de 5 ejes continuo (RTCP)**.

Diseñado y desarrollado por **EagleCelest**, este proyecto nace con el compromiso firme de democratizar la enseñanza técnica y práctica en automatización y robótica industrial, eliminando las barreras económicas y de licencias privativas.

👉 **[Abrir Aplicación en Vivo en el Navegador](https://cnccobotstudio.github.io/cnc-cobot-studio/)**

---

### 🌟 Características Principales

- **🦾 Cinemática Cobot 6-DOF**: Control articular en tiempo real ($J_1-J_6$) y cartesiano con visualización de cotas sin vibración (*zero jitter*).
- **🧭 Asistente Didáctico Universal TCP y Base**: Calibración por 4 puntos, cálculo de matrices de transformación y comprensión visual de sistemas de coordenadas.
- **🔄 Transpilador de Código Multirrobot**:
  - Scripts nativos para Universal Robots (`URScript`: `movej`, `movel`).
  - Código estructurado para Fanuc CRX y lenguaje ISO G-code.
- **🛡️ Seguridad ISO/TS 15066 & Interlock SIL-3**: Monitorización de velocidad colaborativa, detección de colisiones e interlock de parada.
- **⚡ Ejecución Local 100% Autocontenida**: Sin servidores externos ni instalaciones complejas; compatible con navegadores de escritorio, tabletas de taller y dispositivos táctiles.

---

### 🎓 Filosofía Educativa & Contacto

El acceso al aprendizaje de tecnologías industriales debe ser abierto e inclusivo. **CNC & Cobot Studio es completamente gratuito para estudiantes, profesores de Formación Profesional, autónomos y pequeñas empresas.**

- **Centros Educativos y Universidades**: Si deseas integrar la suite en tus clases o solicitar ejercicios didácticos guiados.
- **Sugerencias y Feedback Directo**: Contáctanos en [`cnccobot.feedback@gmail.com`](mailto:cnccobot.feedback@gmail.com).

---

## 🛠️ Tecnologías Empleadas

- **Frontend**: HTML5, Vanilla JavaScript, Tailwind CSS
- **Motor Gráfico**: Gráficos vectoriales SVG y aceleración por hardware
- **Licencia**: Código abierto bajo licencia MIT

