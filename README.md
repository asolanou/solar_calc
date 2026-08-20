## Características Principales

**Se ha realizado una hoja de precálculo solar. Esta hoja no toma valores especificos de ubicación.** 
* **Cálculo Optimizado de Dimensionamiento:** Aplica una tasa de autarquía predeterminada del **80%** para ajustar los sistemas a escalas viables, estándar y de alto retorno de inversión (ROI).
* **Cumplimiento Normativo UPR (El Salvador):** Evalúa la potencia contratada por el cliente. Si el dimensionamiento por consumo supera este límite, la herramienta topa automáticamente la capacidad en kWp para alinearse a la normativa de Usuarios Productores de Energía Renovable de la SIGET.
* **Proyección Temporal Dinámica:** Detecta la fecha actual y ordena automáticamente la gráfica y la tabla de generación mensual para que inicien a partir del **mes siguiente** a la emisión de la preoferta.
* **Gráfica Mixta Dual:** Muestra la generación estimada ($kWh$) en barras inferiores y la tendencia del ahorro mensual ($USD$) en una línea superior clara y sin superposiciones.
* **Modo Impresión / Exportación a PDF:** Diseñado con estilos CSS claros (`@media print`) y fondo blanco para ocultar paneles de entrada y generar un documento comercial formal en un solo clic (`window.print()`).
* **Protección de Márgenes Comerciales:** Incorpora un margen del **30%** sobre la base del costo unitario ($0.70 USD/Wp) integrado de forma opaca en la lógica del script.

---

## Parámetros y Constantes de Ingeniería

La herramienta trabaja internamente con los siguientes estándares predefinidos a forma de precalculo.

| Parámetro | Valor Prefijado | Descripción |
| :--- | :--- | :--- |
| **PSH** | `5.0` | Horas Sol Pico promedio en El Salvador |
| **PR** | `75%` (0.75) | Performance Ratio global (temperatura, cableado, ineficiencias) |
| **Cobertura (Autarquía)** | `80%` (0.80) | Dimensión óptimo respecto al consumo real, esto varia de acuerdo al consumo diario por lo que al dejarlo fijo se puede determinar un equipo más optimo previo al cálculo real |
| **Costo Base Wp** | `$0.70 USD` | Estructura base de costos por Wp |
| **Margen Comercial** | `30%` | Factor interno aplicado a la inversión final | **USOS NETAMENTE INTERNOS COMO VARIABLES DE VENTA**

---

##  Despliegue en GitHub Pages

Para publicar o actualizar esta herramienta en la web:

1. Clonar el repositorio o subir directamente el archivo **`index.html`** en la rama principal (`main`).
2. Ir a **Settings** > **Pages** en el menú de GitHub.
3. En **Branch**, seleccionar `main` y la carpeta `/ (root)`.
4. Guardar cambios. La aplicación estará en línea en la dirección proporcionada por GitHub Pages.

---

##DISCLAIMER

Los valores presentados por esta herramienta son estimaciones preliminares generadas automáticamente con fines comerciales de rápida prospección. No constituyen una oferta contractual vinculante. Todo proyecto final está sujeto a un levantamiento técnico en sitio, análisis de sombras y un diseño de ingeniería certificado mediante software especializado así como que se ha utilizado herramienta de GEMINI 3.1 PRO para ayudar en la realización a HTML.
