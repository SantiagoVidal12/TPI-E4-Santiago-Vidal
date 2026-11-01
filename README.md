# TPI-E4-Santiago-Vidal
# TPI Entrega 4: Procesos, Trabajo Colaborativo y Control Integrador

## Información Académica
*   **Alumno:** Santiago Jair Vidal
*   **Carrera:** Tecnicatura Universitaria en Programación
*   **Institución:** Universidad Tecnológica Nacional (UTN)
*   **Materia:** Organización Empresarial
*   **Cátedra:** Docente Titular: Carolina Bruno | Docente Tutor: Francisco Alejandro Varberde Thompson
*   **Fecha de Presentación:** 1 de noviembre de 2026

---

## 1. Descripción del Sistema (Caso de Estudio: Logitech)
Este repositorio contiene la documentación del **Módulo de Análisis Predictivo y Feedback Centralizado de Clientes (MAPFC)** para **Logitech Internacional S.A.**. El sistema captura interacciones en tiempo real (redes sociales, soporte y eSports) para anticipar fallas de firmware/hardware o picos de demanda, coordinando la información entre las áreas de I+D y Producción/Compras.

---

## 2. Modelado de Procesos de Negocio (BPMN)
El proceso automatizado por el módulo MAPFC se diseñó bajo la notación estándar BPMN con la siguiente estructura:
*   **Pools:** Ambiente / Actores Externos (Comunidad Gamer y APIs de Terceros) y la organización interna (Logitech Internacional).
*   **Lanes Internos:** Módulo MAPFC (Comportamiento Automatizado), Área de I+D / Ingeniería, y Área de Producción y Compras.
*   **Flujo de Excepciones:** Una compuerta de decisión evalúa si la probabilidad de falla supera el 85%, derivando el flujo a parches urgentes en Logitech G HUB o a modificaciones en las órdenes de compra de microchips.

*(Nota: El diagrama visual completo se encuentra adjunto en los archivos del repositorio).*

---

## 3. Entorno Colaborativo y Gestión de Versiones (Git & GitHub)
El desarrollo documental de este repositorio se gestionó mediante los siguientes estándares obligatorios:
*   **Ramas Secundarias (Branches):** El trabajo se organizó en ramas específicas según la consigna (ej. `feature/diagrama-bpmn`).
*   **Mensajes de Commit:** Se utilizaron descripciones profesionales y claras para registrar cada cambio técnico.
*   **Gestión de Pull Request (PR):** Se integraron las secciones mediante la apertura y aprobación de un Pull Request con revisión de pares antes de unificar el contenido en la rama `main`.

---

## 4. Gestión del Backlog Ágil (GitHub Projects)
Las actividades se controlaron mediante un tablero ágil vinculando las historias de usuario con sus estados (*Por Hacer*, *En Progreso*, *Listo*):

1.  **HU 1 (FEEDBACK_CLIENTE):** Como Analista de Sistemas del Módulo MAPFC, quiero que el sistema capture e ingrese automáticamente los comentarios y quejas de redes sociales y soporte técnico, para centralizar el feedback crudo de los clientes en tiempo real sin depender de cargas manuales.
2.  **HU 2 (PREDICCION_ANALITICA):** Como Ingeniero del Área de Investigación de Desarrollo (I+D), quiero recibir alertas automatizadas basadas en algoritmos predictivos cuando la probabilidad de falla de firmware o hardware supere el 85%, para desplegar parches de actualización urgente en Logitech G HUB antes de que afecte masivamente al mercado.
3.  **HU 3 (ALERTA_STOCK):** Como Responsable de Producción y Compras, quiero que el sistema emita notificaciones automáticas de quiebre de stock estimado ante picos de demanda, para modificar las órdenes de compra de microchips con los proveedores.

---

## 5. Mecanismos de Control y Estándares de Desempeño
Se establecieron tres indicadores cuantitativos (KPIs) para auditar el rendimiento técnico del sistema:
*   **KPI de Tiempo de Respuesta:** $\frac{\text{Registros analizados en } \le 3 \text{ seg}}{\text{Total de registros de feedback capturados}} \times 100$ (Estándar: $\ge 95\%$ de los datos en rango).
*   **KPI de Escalabilidad:** Latencia adicional al superar los 5.000.000 de registros mensuales (Estándar: Soportar hasta 10.000.000 de registros sin degradar el rendimiento más de un $5\%$).
*   **KPI de Calidad de la IA:** $\frac{\text{Alertas predictivas erróneas}}{\text{Total de alertas emitidas}} \times 100$ (Estándar: Tasa de falsos positivos menor al $15\%$).

---

## 6. Declaración de Uso de IA
*   **Justificación de Prompts:** Los prompts se orientaron específicamente a mejorar la calidad de las palabras usadas en la redacción, estructurar el formato Markdown del repositorio y obtener información esencial sobre la empresa Logitech.
*   **Correcciones Humanas:** El contenido generado por el asistente de IA fue revisado, filtrado y corregido para adaptarlo estrictamente a las consignas solicitadas por la cátedra y a la realidad operativa del caso de estudio.
