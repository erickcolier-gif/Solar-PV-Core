# Solar-PV-Core
Todos los recursos de código para implementar soluciones solares: desde la integración de sensores IoT hasta algoritmos para el mantenimiento predictivo de paneles.

Servicios Solares Fotovoltaicos de Ingeniería Avanzada

Este proyecto es una landing page de alta conversión diseñada específicamente para un emprendimiento que ofrece servicios de ingeniería, diseño, instalación y monitoreo de sistemas solares fotovoltaicos.

El objetivo principal es capturar leads cualificados mediante una calculadora de ahorro simulada y destacar el valor tecnológico de la oferta (monitoreo, optimización y dashboards de cliente).

🚀 Características Principales

La estructura de la página se enfoca en guiar al visitante a través del valor del servicio hacia el formulario de contacto:

Hero con CTA (Llamada a la Acción): Titular impactante y botón principal que dirige directamente a la calculadora de ahorro.

Diferenciadores de Ingeniería (Sección 2):

Optimización de Diseño: Énfasis en el modelado avanzado de sistemas ($\gamma, \beta$).

Monitoreo y Predicciones: Resalta el monitoreo 24/7 y el uso de modelos predictivos basados en datos climáticos.

Dashboard de Cliente: Promete un acceso fácil a los datos de rendimiento y proyecciones de ahorro.

Calculadora de Eficiencia (Conversión): Un formulario de primer paso que simula un cálculo de ahorro estimado para incentivar al usuario a completar el formulario de contacto más detallado.

Visualización de Monitoreo: Una sección con un dashboard simulado para visualizar el tipo de datos de rendimiento (kWh, Eficiencia, Ahorro) que el cliente obtendrá con el servicio.

Prueba Social: Sección de Testimonios y un carrusel simulado de Proyectos Destacados (fotos).

🛠️ Tecnologías Utilizadas

HTML5: Estructura base del documento.

Tailwind CSS: Framework de utility-first CSS para un diseño moderno, limpio y completamente responsivo.

JavaScript (Vanilla JS): Utilizado para la lógica simple de la Calculadora de Ahorro y el manejo del formulario de contacto simulado.

Notación Científica: Uso de notación LaTeX (como $\eta$, $\gamma, \beta$) para añadir rigor técnico a la descripción de los servicios.

⚙️ Uso y Despliegue

Dado que este es un archivo HTML autocontenido (index.html), su uso es extremadamente simple:

Ejecutar: Simplemente abre el archivo index.html en cualquier navegador web.

Estilo: El diseño es cargado mediante el CDN de Tailwind CSS, asegurando que todos los estilos y la respuesta móvil estén activos inmediatamente.

Nota: La lógica del formulario de contacto y la calculadora son simuladas (solo muestran mensajes de éxito/resultados temporales). En un entorno de producción, la función submitForm() debe ser conectada a un servicio de backend (como Firestore o una API de email marketing) para el almacenamiento real de los leads.