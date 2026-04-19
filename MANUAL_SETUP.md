# 🌌 Manual de Configuración Inicial - Nexo ∞

¡Bienvenido al ecosistema Nexo ∞! Este manual te guiará en el despliegue de tu arquitectura de pensamiento potenciada por IA. Nexo no es solo una herramienta, es un puente de inteligencia diseñado bajo principios de soberanía intelectual y resiliencia técnica.

---

## 🛠️ Paso 1: Auditoría y Requisitos Previos

Antes de iniciar el despliegue, el sistema realizará una auditoría automática de tu hardware. Para una experiencia óptima, asegúrate de contar con:

1.  **Obsidian:** El motor de persistencia y visualización. Descárgalo en [https://obsidian.md/download](https://obsidian.md/download). No crees la bóveda manualmente; Nexo la desplegará por ti.
2.  **Ollama (IA Local):** Fundamental para la soberanía de datos. Instálalo desde [https://ollama.com/](https://ollama.com/) para habilitar el procesamiento local sin tokens de nube.
3.  **Hardware y Recomendador:** El sistema detectará automáticamente tu CPU/GPU para sugerir el modelo de Ollama más eficiente y optimizar el triaje de alta densidad.

---

## 🚀 Paso 2: Ejecución y Setup Wizard

Ejecuta el binario compilado `nexo.exe`. Al ser una distribución protegida mediante **Nuitka**, garantiza la integridad del código.

### 📋 El Asistente de Despliegue:

1.  **Identidad:** Ingresa tu nombre para personalizar los metadatos de tu ecosistema.
2.  **Espacios de Pensamiento (Temas):** Define tus áreas de estudio (ej: *Física, Literatura, Técnica*). Nexo creará estructuras aisladas y escalables para cada una.
3.  **IA Híbrida y Router de Resiliencia:** 
    *   Configura tus llaves API (SambaNova, Groq, OpenRouter).
    *   Nexo utiliza un algoritmo **Round Robin** que rota entre llaves para evitar límites de cuota.
    *   **Prioridad Local:** Si Ollama está activo, Nexo lo priorizará para análisis de privacidad sensible.

---

## 🔑 Paso 3: Activación y Licencia Educativa

Nexo ∞ promueve la gratuidad para el sector educativo mediante un sistema de **Soberanía del Conocimiento**:

*   **Clave Educativa:** Los docentes e instituciones pueden solicitar una clave de uso permanente.
*   **Vínculo con Hardware:** La activación se realiza mediante una solicitud "in-app" vinculada a tu **Machine ID** (identificador único de hardware). Esto genera una clave cifrada intransferible para tu equipo.
*   **Modo Básico:** Existe un límite de uso gratuito razonable; una vez agotado, se activan las funciones esenciales hasta la activación de la licencia.

---

## 📁 Paso 4: Despliegue del Ecosistema

Al confirmar, Nexo ejecutará el despliegue automático:

1.  **Bóveda en Documentos:** Se crea la carpeta `Nexo` en tu directorio de usuario.
2.  **Inyección de Plugins:** Se instalan y configuran `Dataview` y el **Nexo Bridge**.
3.  **Nexo Bridge:** Se activa un servidor API (FastAPI) en el **puerto 8000** para la comunicación en tiempo real entre la IA y Obsidian.
4.  **Dashboards de Control:** Generación de paneles visuales y constelaciones de conocimiento.

---

## 🧠 Paso 5: Filosofía del "Discernimiento"

Una vez en Obsidian (Ctrl+E para modo lectura), recuerda:

*   **Curaduría Crítica:** Nexo no es un generador de contenido; es un motor de validación. Su objetivo es encontrar "puntos ciegos" y sugerir conexiones, no sustituir tu pensamiento.
*   **Triaje de Alta Densidad:** El sistema extrae el "ADN" del texto (10%) permitiendo analizar volúmenes masivos (+130k palabras) en segundos.
*   **Privacidad Local-First:** ChromaDB gestiona tu memoria semántica localmente. Si la similitud conceptual es >95%, Nexo no consume tokens de IA.

---

## ❓ Solución de Problemas

*   **Error de Puerto 8000:** Asegúrate de que ninguna otra aplicación esté usando este puerto para que el Nexo Bridge funcione.
*   **Machine ID no coincide:** Si cambias de hardware principal, deberás solicitar una re-vinculación de tu clave educativa.
*   **Ollama no responde:** Verifica que el servicio de Ollama esté corriendo en segundo plano antes de iniciar Nexo.

---
*Nexo ∞ - La eficiencia que nos vuelve irrelevantes, combatida con discernimiento humano.*

