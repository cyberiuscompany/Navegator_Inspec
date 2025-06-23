# 🛡️ Navegator_Inspec

**Cyberius | Herramienta ligera y rápida para analizar la seguridad nativa del navegador web directamente desde el propio navegador.**

---

<p align="center">
  <img src="icono.png" alt="Banner" width="500"/>
</p

---

## 📋 Descripción

`Navegator_Inspec` es una herramienta desarrollada como aplicación web (PWA) que te permite conocer de un vistazo las capacidades, funciones y configuración de seguridad de tu navegador, sin necesidad de instalar software adicional.

Detecta funciones como:
- APIs sensibles (Bluetooth, USB, Clipboard)
- Capacidad WebGL
- Java habilitado o no
- Memoria RAM, núcleos, batería
- Dirección IP pública
- Nivel de soporte y privacidad
- ...y mucho más

> ⚙️ Todo se ejecuta localmente en el navegador del usuario o por medio de la GitHub Pages

---

## 🧭 Características principales

- 📈 Radar de 5 métricas clave (Privacidad, Protección, Soporte, Rendimiento, Configuración)
- 🎯 Tooltip con explicaciones de cada métrica
- 📌 Vista técnica detallada con más de 20 puntos analizados
- 🔍 Buscador en tiempo real entre los datos técnicos
- 📱 Aplicación PWA: instalable, funciona offline

---

## 🚀 Demo en GitHub Pages

📡 Puedes probarla directamente sin instalar nada:  
🔗 [https://cyberiuscompany.github.io/Navegator_Inspec](https://cyberiuscompany.github.io/Navegator_Inspec)

---

## 📁 Archivos importantes

| Archivo         | Descripción                                        |
|----------------|----------------------------------------------------|
| `index.html`    | Página principal con el escáner                    |
| `manifest.json` | Configuración como PWA                            |
| `sw.js`         | Service Worker para caché y modo offline          |
| `cyberius.ico`  | Favicon de la herramienta                         |
| `*.png`         | Capturas de pantalla y gráficos                   |

---

## 🧩 Cómo instalar localmente

```bash
npm install -g serve
serve
