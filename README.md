# Distrileco Digital Control 📱🌾
> **Desarrollado por:** Vibras Positivas HM  
> **Contacto:** +57 300 6614485  
> **Año:** 2026

Herramienta interna en formato **PWA (Progressive Web App)** integrada en un único archivo autónomo. Diseñada para optimizar, auditar y controlar las tareas diarias del personal *In-House* (redes sociales y desarrollo web) y la gestión en punto de venta de la impulsadora/mercaderista para las marcas propias **Superarroz** y **Vistahermosa**.

---

## 🚀 Características Clave

*   **Estructura de Archivo Único:** Todo el diseño (Tailwind CSS), la lógica de negocio (JavaScript), el Service Worker y el Manifiesto PWA coexisten en un único archivo ejecutable (`index.html`).
*   **Base de Datos Corta (Short-DB):** Sistema de almacenamiento optimizado en `LocalStorage` que retiene únicamente los últimos 15 registros operativos para garantizar un rendimiento fluido y evitar la saturación de memoria en dispositivos móviles.
*   **Geolocalización Mandatoria:** Captura automática en tiempo real de coordenadas GPS para auditar la presencia de la impulsadora en los puntos de venta y el cumplimiento de horarios del *In-House*.
*   **Integración Fluida con WhatsApp:** Conversión de los formularios en plantillas de texto completamente estructuradas listas para ser enviadas con un solo clic a las líneas de administración.

---

## 🕒 Horarios de Operación Configurados

El sistema de control está parametrizado bajo los bloques de horario comercial oficiales de **Distrileco**:
*   **Lunes a Viernes:** 07:30 AM – 12:00 PM  &  02:00 PM – 05:00 PM
*   **Sábados:** 07:30 AM – 12:00 PM

---

## 🧑‍💻 Módulos y Roles del Sistema

### 1. Vista In-House
Permite al diseñador/desarrollador realizar sus registros obligatorios de inicio y cierre de jornada, exigiendo la descripción textual de entregables (parrillas de contenido, diseños creados, mantenimiento del sitio web, pauta publicitaria).

### 2. Vista Impulsadora / Mercaderista
Formulario optimizado para trabajo en campo donde se selecciona el tipo de actividad (Inicio, Avance, Fin de jornada), el nombre del punto de venta, la cantidad de unidades vendidas y observaciones del mercado.
> *Nota: Al redireccionar a WhatsApp, el usuario debe adjuntar el registro fotográfico directo de la góndola.*

### 3. Vista Administrador (Consola de Control)
Exclusiva para la dirección comercial (**Harold Marín**). Permite:
*   Visualizar el historial corto de reportes locales almacenados con su estampa de tiempo y geolocalización.
*   Calcular de forma ponderada la nota de desempeño semanal mediante tres pilares objetivos:
    *   **Parrilla y Redes:** 40%
    *   **Control de Impulsadora:** 40%
    *   **Reportes y Horarios:** 20%

---

## 🛠️ Instrucciones de Instalación y Despliegue

Al ser una aplicación web progresiva serverless, no requiere configuraciones complejas de backend:

1.  **Guardar el archivo:** Copia el código fuente completo y guárdalo localmente con el nombre de `index.html`.
2.  **Despliegue Rápido:** Sube el archivo a tu plataforma de hosting preferida (Netlify, GitHub Pages, Firebase Hosting o Railway).
3.  **Instalación en Dispositivos (PWA):**
    *   **Android / Chrome:** Abre el enlace del sitio desplegado, presiona los tres puntos superiores y selecciona **"Agregar a la pantalla principal"** o **"Instalar aplicación"**.
    *   **iOS / Safari:** Abre el enlace, presiona el botón **"Compartir"** y selecciona **"Agregar a inicio"**.

---

## ⚖️ Derechos de Autor y Licencia

Este software es propiedad digital exclusiva. Quedan reservados todos los derechos de autoría y propiedad intelectual sobre el método de desarrollo y diseño de interfaz de un solo archivo.

**Hecha por Vibras Positivas HM**  
*Garantizando la digitalización, control y crecimiento comercial.*
