# Noise Meter 

Noise Meter es una aplicación móvil desarrollada con tecnologías web que permite medir el nivel de ruido ambiental en tiempo real, con el objetivo de determinar si un entorno es adecuado para el estudio o la concentración.

La aplicación utiliza el micrófono del dispositivo para analizar el sonido ambiente y muestra el nivel de ruido mediante un indicador visual dinámico que cambia de color según la intensidad detectada.

---

##  ¿Qué hace la aplicación?

- Mide el ruido ambiental en tiempo real
- Accede al micrófono del dispositivo
- Muestra un indicador circular de volumen
- Cambia de color según el nivel de ruido:
  - 🟢 Verde: entorno silencioso (apto para estudiar)
  - 🟡 Amarillo: ruido moderado
  - 🔴 Rojo: ruido alto
- Funciona como una aplicación móvil Android empaquetada

---

## 🛠️ Tecnologías utilizadas

- **React**: desarrollo de la interfaz de usuario
- **Capacitor**: empaquetado de la aplicación web como app móvil
- **Web Audio API**: captura y análisis del audio del micrófono
- **WebView**: renderizado del contenido web dentro de la app móvil
- **Android Studio**: generación del APK para Android
- **HTML / CSS / JavaScript**: tecnologías base de la aplicación

---

##  Arquitectura

La aplicación sigue una arquitectura híbrida, donde una aplicación web desarrollada en React es encapsulada dentro de una aplicación móvil nativa mediante Capacitor y WebView, permitiendo el acceso a funcionalidades del dispositivo como el micrófono.

---

##  Contexto académico

Este proyecto fue desarrollado como parte de una práctica académica para la asignatura de **Técnicas de Programación Avanzadas para Dispositivos Móviles**, con el fin de aplicar conceptos de aplicaciones híbridas y uso de APIs del dispositivo móvil.

