# Simphonea 🎸

**Simphonea** es una suite profesional para guitarristas, diseñada para ofrecer alta precisión y portabilidad. Enfocada en la estética minimalista y el rendimiento técnico, proporciona las herramientas esenciales para cualquier músico, desde la afinación hasta la composición.

## ✨ Características Principales

### 🎯 Afinador de Alta Precisión
*   **Algoritmo "First-Peak"**: Lógica de autocorrelación avanzada que evita saltos de octava y garantiza estabilidad en todas las cuerdas (desde Mi2 hasta Mi4).
*   **Precisión de Centésimas**: Implementación de interpolación parabólica para una afinación extremadamente fina.
*   **Feedback Visual**: Interfaz con estética "Glassmorphism" que brilla en ámbar al alcanzar la nota perfecta.
*   **Presets**: Soporte para afinación Estándar, Drop D y Open G.

### ⏱️ Metrónomo Pro
*   **Reloj de Alta Precisión**: Utiliza el temporizador de alta resolución de la Web Audio API para un tempo sólido como una roca.
*   **Tap Tempo**: Configura los BPM rápidamente pulsando al ritmo de cualquier canción.
*   **Pulso Visual**: Indicadores dinámicos para mantener el ritmo visualmente.

### 📚 Handbook de Crecimiento
*   **Técnica y Teoría**: Una colección curada de consejos sobre toque ligero, mantenimiento y teoría de intervalos.

### 🧪 Laboratorio de Creación
*   **Captura de Riffs**: Espacio dedicado para guardar tus inspiraciones musicales, progresiones de acordes y letras.
*   **Persistencia Local**: Todas tus ideas se guardan de forma segura en tu dispositivo mediante LocalStorage.

## 🛠️ Stack Tecnológico
*   **Core**: HTML5 y JavaScript Vanilla (ES6+).
*   **Diseño**: Tailwind CSS con tokens personalizados de Glassmorphism.
*   **Motor de Audio**: Web Audio API para procesamiento de señal en tiempo real.
*   **Iconografía**: Lucide Icons.
*   **Despliegue**: GitHub Actions para compilación automatizada de APK.

## 🚀 Instalación y Compilación

### Web / PWA
Simphonea es una Aplicación Web Progresiva. Puedes abrir `DISEÑO.HTML` en cualquier navegador moderno o alojarlo en GitHub Pages. Para instalarlo en tu móvil:
1. Abre la URL en Chrome (Android) o Safari (iOS).
2. Selecciona "Añadir a la pantalla de inicio".

### APK de Android
El proyecto está configurado para generar una APK nativa automáticamente mediante GitHub Actions:
1. Ve a la pestaña **Actions** en este repositorio.
2. Selecciona la ejecución más reciente.
3. Descarga el artefacto **Simphonea-APK**.

## 👨‍💻 Arquitectura Técnica
Simphonea está construida como una aplicación de archivo único altamente portátil. Los activos (como el logo) están embebidos en Base64 para asegurar que la suite sea funcional incluso como un archivo independiente. La lógica está estructurada de forma modular para facilitar la expansión de nuevas afinaciones y herramientas.

---
*Desarrollado con ❤️ para guitarristas de todo el mundo.*
