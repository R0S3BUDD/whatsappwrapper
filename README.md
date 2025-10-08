# 📦 WhatsApp Desktop Linux Wrapper

## 🇬🇧 Project Description

The goal of this project is to build a lightweight **desktop wrapper** for **WhatsApp Web** using **Java**, fully integrated with the Linux desktop environment.  
The app will act as a standalone window with system notifications, audio and video support for calls, and automatic startup options.

### ✨ Planned Features

- **Linux desktop integration:** custom window, tray icon, and keyboard shortcuts.
- **System notifications:** native notification support (via `notify-send` or JavaFX APIs).
- **Call support:** handle WhatsApp calls through the embedded browser or system audio APIs.
- **Autostart on boot:** launch automatically on system startup (`~/.config/autostart`).
- **Minimalist mode:** clean UI without extra distractions.

### 🧰 Initial Technical Requirements

- **Java 17+**
- **JavaFX**
- **Gradle** as a dependency manager
- **WebView** component (for embedding WhatsApp Web)
- **Linux environment** (GNOME, KDE, XFCE, or Cinnamon preferred)

---

---

## 🇪🇸 Descripción del proyecto

El objetivo de este proyecto es crear una aplicación ligera que permita usar **WhatsApp** desde el escritorio de Linux sin depender de navegadores externos.  
La aplicación funcionará como un **wrapper** (envoltorio) alrededor de WhatsApp Web, ofreciendo una experiencia más nativa y práctica.

### ✨ Características planeadas

- **Integración a escritorio Linux:** ventana propia, icono en la bandeja del sistema, y atajos de teclado.
- **Notificaciones del sistema:** soporte para notificaciones nativas (por ejemplo, `notify-send` o JavaFX Notifications API).
- **Soporte para llamadas:** integración con el audio y video del sistema (a través del navegador embebido o APIs compatibles).
- **Arranque automático:** ejecución al iniciar el sistema (servicio o autostart en `~/.config/autostart`).
- **Modo minimalista:** interfaz limpia y sin distracciones.

### 🧰 Requerimientos técnicos iniciales

- **Java 17+**
- **JavaFX** (para la interfaz gráfica)
- **Gradle** (gestor de dependencias)
- **WebView** (para mostrar WhatsApp Web embebido)
- **Linux (entorno gráfico GNOME, KDE o Cinnamon recomendado)**