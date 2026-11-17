# 🤖 CNC & Cobot Studio v4.2 PRO

> **Universal Orchestrator & Kinematic Studio for CNC Machining and 6-DOF Collaborative Robots**  
> *Created with pride by **EagleCelest** · Democratizing Industrial Robotics & Advanced Manufacturing*

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-00f2fe?style=for-the-badge&logo=github)](https://cnccobotstudio.github.io/cnc-cobot-studio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Status: v4.2 PRO](https://img.shields.io/badge/Release-v4.2%20PRO-10b981?style=for-the-badge)](https://github.com/cnccobotstudio/cnc-cobot-studio)
[![Platform: Web & Tablet](https://img.shields.io/badge/Optimized-Web%20%7C%20Tablet%20%7C%20Mobile-blueviolet?style=for-the-badge)](#)
[![Student Access](https://img.shields.io/badge/Student%20Access-100%25%20Free%20(0€)-2563eb?style=for-the-badge)](#)

---

## 🌟 Visión & Misión: Democratizar la Automatización Industrial

**CNC & Cobot Studio** es una suite interactiva web ligera, autocontenida y de alta precisión desarrollada para cerrar la brecha entre la teoría académica y la operación real en planta de mecanizado CNC y robótica colaborativa (Cobots de 6 grados de libertad).

Diseñada especialmente para:
- 🎓 **Estudiantes y Centros de Formación Profesional / Universidades**: Acceso formativo 100% libre y gratuito (0€) para aprender sistemas de coordenadas, matrices cinemáticas y calibración sin riesgos mecánicos.
- 🛠️ **Autónomos, Talleres de Mecanizado y Pequeñas Empresas**: Configuración rápida de herramientas (TCP), verificación de trayectorias y transpilación de código sin licencias abusivas de software privativo.
- ⚙️ **Ingenieros de Automatización & CAM**: Simulación en tiempo real y transpilación universal de código ISO G-code a scripts nativos para brazos robóticos.

---

## 🚀 Probar la Aplicación en Vivo

No requiere instalación de software, terminal ni dependencias locales. Funciona directamente en cualquier navegador moderno (PC, Tablet y Móvil):

👉 **[https://cnccobotstudio.github.io/cnc-cobot-studio/](https://cnccobotstudio.github.io/cnc-cobot-studio/)**

---

## ⚡ Características Principales

### 🎯 1. Calibrador Universal de Herramienta (TCP - 4 Puntos)
- Cálculo geométrico de centro de herramienta (*Tool Center Point*) mediante el método estándar de 4 puntos de orientación dispar.
- Monitorización de residuo y error medio cuadrático (**RMS residual < 0.038 mm**).
- Soporte para herramientas de fresado plano, esférico, pinzas de agarre y cabezales de dispensado.

### 🦾 2. Entorno Cinemático & Jog 6-DOF
- Simulación articular para articulaciones **J1 a J6** con control por pasos angulares configurables ($0.1^\circ$, $1.0^\circ$, $5.0^\circ$).
- Lectura de cotas en pantalla (**DRO Estable**) con protección anti-vibración (*zero jitter*) en ejes cartesianos X, Y, Z y ángulos de Euler (Rx, Ry, Rz).
- Representación en vivo de la matriz homogénea de transformación $T_{4\times4}$ basada en parámetros Denavit-Hartenberg (DH).

### 🔄 3. Transpilador Universal G-code ↔ Scripts Robot
- Entrada en **ISO G-code (DIN 66025 / ISO 6983)**: ciclos de mecanizado, orígenes `G54`/`G55`, avances `F` y cabezal `S`.
- Generación instantánea de rutinas cinemáticas para robots colaborativos:
  - **URScript** (`movej`, `movel`, `set_tcp`, `set_payload`) para Universal Robots (UR3e, UR5e, UR10e, UR16e).
  - Dialectos industriales listos para Fanuc CRX / KAREL.

### 🛡️ 4. Seguridad de Grado Taller (SIL-3 & E-STOP)
- Pulsador reactivo de **Paro de Emergencia (E-STOP)** con corte de simulación de servomotores.
- Verificación de envolvente de seguridad, velocidad colaborativa permitida (norma **ISO/TS 15066**) y detección de proximidad a singularidades cinemáticas.

### 📚 5. Biblioteca Didáctica de Probetas y Retos
- Casos prácticos de mecanizado progresivo:
  1. *Nivel 1*: Planeado y Cajera Simple (calibración en Z y amarre G54).
  2. *Nivel 2*: Interpolación Circular (chequeo de desvíos cuadrantales y singularidad de muñeca).
  3. *Nivel 3*: Trayectorias complejas y 5 Ejes Continuo (RTCP con DMU / Hermle).
- Exportación e importación de proyectos en formato abierto `.cncproj`.

---

## 💻 Arquitectura Técnica

- **Frontend Core**: Vanilla JavaScript (ES6+) con arquitectura reactiva de estado (`window.AppState`).
- **Estilos & UI**: Tailwind CSS (Dark Industrial Mode inspirado en interfaces de HMI CNC Siemens Sinumerik y Heidenhain).
- **Iconografía & Gráficos**: Lucide Icons + Gráficos vectoriales SVG dinámicos.
- **Persistencia**: `localStorage` nativo del navegador para gestión de estados, preferencias y encuesta diferida de calidad.
- **Zero-Dependency**: 100% autocontenido en un solo archivo `index.html`. Cero configuración, cero costes de servidor.

---

## 📥 Uso Local / Despliegue Propio

Si deseas ejecutar o modificar **CNC & Cobot Studio** en tu propio entorno:

```bash
# 1. Clonar el repositorio
git clone https://github.com/cnccobotstudio/cnc-cobot-studio.git

# 2. Entrar en la carpeta
cd cnc-cobot-studio

# 3. Abrir en cualquier navegador
# En Windows:
start index.html
# En macOS:
open index.html
# En Linux:
xdg-open index.html
```

---

## 📬 Buzón de Feedback & Soporte

¿Tienes sugerencias, necesitas incorporar un postprocesador para tu máquina o quieres proponer una mejora didáctica para tu aula?

- 📧 **Correo Oficial de Feedback**: [cnccobot.feedback@gmail.com](mailto:cnccobot.feedback@gmail.com)
- 🐛 **GitHub Issues**: [Abrir una incidencia / propuesta](https://github.com/cnccobotstudio/cnc-cobot-studio/issues)

---

## 👤 Autor & Agradecimientos

- **Creado y Diseñado por**: **EagleCelest**
- *Dedicado a la comunidad técnica, estudiantes de FP, autónomos y amantes de la automatización y robótica colaborativa.*
