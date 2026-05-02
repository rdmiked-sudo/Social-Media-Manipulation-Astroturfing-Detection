# OSINT Investigation: Social Media Manipulation & Astroturfing Detection

## 📌 Resumen del Caso
Investigación de inteligencia dirigida a identificar y desmantelar una red de **Astroturfing** (campaña coordinada de perfiles falsos) que operaba para manipular la opinión pública y atacar la reputación de una entidad competidora. 

El análisis se centró en detectar comportamientos no humanos y patrones de coordinación entre múltiples cuentas en redes sociales que aparentaban ser usuarios independientes.

## 🎯 Objetivos de la Investigación
*   **Detección de Botnets:** Identificar cuentas con comportamiento automatizado o coordinado.
*   **Análisis de Narrativas:** Rastrear el origen de los mensajes clave y su velocidad de propagación.
*   **Atribución de Campaña:** Encontrar nexos técnicos o lingüísticos que vinculen a los operadores de la red.

## 🛠️ Metodología y Herramientas (SOCMINT Stack)
Se aplicó un análisis cuantitativo y cualitativo para confirmar la inautenticidad de la red:

- **Análisis de Metadatos de Perfil:** Uso de `Twint` y `Tinfoleak` para extraer fechas de creación masiva. Se detectó que el 80% de la red fue creada en un periodo de 48 horas.
- **Identificación de Medios Sintéticos:** Análisis forense de fotos de perfil mediante detección de artefactos de IA (ojos perfectamente alineados y fondos desenfocados por redes neuronales StyleGAN).
- **Análisis de Coincidencia de Tiempo:** Uso de scripts de Python para mapear la frecuencia de publicación. Se halló una correlación del 95% en los horarios de actividad, sugiriendo el uso de un panel de control centralizado.
- **Análisis Lingüístico:** Detección de patrones de "copy-paste" y errores gramaticales idénticos en múltiples cuentas, indicando el uso de un mismo guion (script).

## 📊 Hallazgos Críticos
1.  **Coordinación Artificial:** Identificación de 45 cuentas que publicaban contenido idéntico en un intervalo de menos de 30 segundos entre cada una.
2.  **Amplificación Forzada:** Se detectó que las cuentas solo interactuaban entre sí para inflar artificialmente las métricas de *engagement* y posicionar hashtags específicos en los "Trending Topics".
3.  **Vínculos de Infraestructura:** El rastreo de enlaces acortados utilizados en las biografías reveló un dominio común registrado por una agencia de marketing digital con antecedentes de campañas de desprestigio.

## 🏁 Conclusión y Resolución
La investigación permitió clasificar la actividad como una **Operación de Información (IO)** coordinada y no como un movimiento orgánico de usuarios.

*   **Acción Realizada:** Se generó un informe de evidencia digital que permitió el reporte masivo y posterior suspensión de la red por violación de las políticas de manipulación de la plataforma.
*   **Impacto:** Se neutralizó la narrativa negativa al demostrar públicamente el origen artificial de los ataques, protegiendo la integridad reputacional del cliente.

---
**Nota Profesional:** *Este repositorio constituye el resumen ejecutivo del caso. Por razones de seguridad operativa (OPSEC) y confidencialidad, no se incluyen enlaces directos a los perfiles investigados ni el dataset bruto.*
