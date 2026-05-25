# AIO Online 1.0

**AIO Online 1.0** es una aplicación de escritorio desarrollada con [Electron](https://www.electronjs.org/) diseñada para automatizar la instalación de software gratuito, de código abierto y herramientas esenciales en sistemas Windows.

Esta herramienta está pensada para técnicos y usuarios que desean configurar un equipo nuevo en minutos, seleccionando manualmente programas o utilizando plantillas predefinidas.

> **Editor:** DGR Inc & Qwen IA  
> **Versión:** 1.0  
> **Fecha:** 18/05/2026

---

## 🚀 Características Principales

*   **Más de 37 Aplicaciones Disponibles:** Desde navegadores y ofimática hasta mantenimiento y seguridad.
<img width="1364" height="201" alt="04_Individual" src="https://github.com/user-attachments/assets/383b16a3-d1a1-4349-8f20-cfdb3a7abf22" />

*   **Instalación Automatizada:** Utiliza **Winget** y scripts personalizados para instalar software sin intervención del usuario.
*   **3 Modos de Plantilla (Templates):** Configuración rápida según las especificaciones del equipo (Lite, Normal, Full).
<img width="1368" height="188" alt="05_Plantillas" src="https://github.com/user-attachments/assets/f1c4cde0-72b8-400b-9437-d2a59e329e54" />

*   **Herramientas AIO Integradas:** Office, Visual C++ y Utilidades de sistema.
<img width="1318" height="828" alt="10_Office" src="https://github.com/user-attachments/assets/f5f10a30-dafa-436c-9132-fec535425923" />

*   **Interfaz Personalizable:** Tema Claro/Oscuro, imagen de fondo propia y color de acento.
<img width="1484" height="1096" alt="01_Claro" src="https://github.com/user-attachments/assets/ec4c6207-0adc-4f53-af69-156e5bc4abcf" />
<img width="1484" height="1092" alt="02_Oscuro" src="https://github.com/user-attachments/assets/e5652b17-7011-46e3-997b-e2c6bca5d3c8" />
<img width="1482" height="1092" alt="03_Personalización" src="https://github.com/user-attachments/assets/a6bf594e-244a-4186-8817-92da941d323f" />
<img width="367" height="180" alt="07_Personalización2" src="https://github.com/user-attachments/assets/7591b46a-1b64-4865-8a0d-2454bf871f7b" />

*   **Reproductor de Música:** Integrado localmente para disfrutar de audio mientras trabajas (se puede pausar en cualquier momento. Lo puedes encontrar en la sección de personalización).
*   Para mas datos en la aplicación, incluí un menú que te puede interesar!.
<img width="121" height="221" alt="09_Mas" src="https://github.com/user-attachments/assets/7c0ad527-6baa-4c60-bb8f-06e73369355c" />

*   Ventana de estado de actual selección.
<img width="1363" height="342" alt="06_Selección" src="https://github.com/user-attachments/assets/439e2b4d-11af-4454-9a75-1de751c135e1" />

*   Apartado de mis redes sociales por si deseas seguirme!! :)
<img width="865" height="139" alt="08_Redes" src="https://github.com/user-attachments/assets/34f150ce-ac09-435d-9339-b5c9db3abacb" />

---

## 📥 Instalación

1.  Ve a la sección de **[Releases](https://github.com/Hellowen6060/AIO-Online-1.0/releases)** del repositorio.
2.  Descarga el archivo `.exe` (instalador NSIS).
3.  Ejecuta el instalador y sigue los pasos.
    *   *Nota:* Es posible que **Windows Defender** muestre una advertencia (falso positivo común en apps de Electron). Si confías en la fuente, permite la ejecución.

---

## 📖 Manual de Uso

### 1. Selección Individual
Ideal si solo quieres instalar programas específicos (ej. solo Google Chrome y 7-Zip).
1.  En la sección **Categorías de Programas**, haz clic en la categoría deseada (ej. *Internet*).
2.  Marca las casillas de los programas que deseas instalar.
3.  Haz clic en el botón verde **Iniciar**.

### 2. Plantillas Preestablecidas
Ideal para formateos rápidos. Selecciona una plantilla y se marcarán automáticamente los programas ideales para ese tipo de equipo.
1.  Selecciona una opción:
    *   **Lite:** Equipos básicos (4-6GB RAM / 240GB SSD). Incluye lo esencial.
    *   **Normal:** Equipos hogar (6-8GB RAM / 500GB SSD). Incluye ofimática y navegación estándar.
    *   **Full:** Equipos alto rendimiento. Incluye herramientas de desarrollo y diseño.
2.  Haz clic en el botón verde **Iniciar**.

### 3. Herramientas Especiales y AIOs
Estas herramientas realizan tareas complejas y están incluidas en la app:

*   **AIO Office:** Instala Microsoft Office (versiones 365, 2024, 2021, etc.) + Activador MAS.
*   **AIO Visual:** Instala todos los paquetes Microsoft Visual C++ (x86/x64) necesarios para juegos y apps de diseño.
*   **Chris Titus:** Abre la herramienta de Tweaking de Windows para optimizar el sistema.
*   **Utilidades:**
    *   *Mi Equipo:* Genera un informe rápido de hardware.
    *   *Antiguo Menú:* Restaura el menú contextual clásico de Windows.
    *   *Visor Fax:* Restaura el antiguo visor de imágenes de Windows.

---

## ️ Personalización

*   **Modo Nocturno:** Usa los botones "Claro" u "Oscuro" en la cabecera.
*   **Fondo de Pantalla:** Haz clic en "Cargar imagen" para poner tu propio fondo.
*   **Música:** Haz clic en el botón "Música" para reproducir el audio local incluido.

---

## ⚠️ Solución de Problemas

**Q: El instalador es bloqueado por el antivirus.**  
**A:** Al ser una aplicación compilada con Electron que ejecuta comandos de PowerShell, algunos antivirus lo marcan erróneamente. Si has descargado el archivo de este repositorio oficial, es seguro añadirlo a las excepciones.

**Q: La instalación se detiene en un programa.**  
**A:** Revisa el log en tiempo real (la consola negra en la app). Algunos programas requieren conexión a internet estable o que Windows Update esté al día.
<img width="1316" height="188" alt="11_Log" src="https://github.com/user-attachments/assets/398a7d13-e9fc-4fbd-9985-4323c1daae0f" />

---

## 💻 Detalles Técnicos

*   **Framework:** Electron + TailwindCSS
*   **Backend:** Node.js (Child Process para Winget y PowerShell)
*   **Requisitos:**
    *   Windows 10 / 11
    *   Conexión a Internet
    *   Permisos de Administrador

---

## 📜 Licencia

Este proyecto es de uso personal y educativo.
https://raw.githubusercontent.com/Hellowen6060/LicenciaLibre/main/README.md

Derechos reser
vados © 2026 - DGR Inc & Qwen IA.
