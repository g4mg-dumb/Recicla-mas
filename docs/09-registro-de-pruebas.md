# Registro de pruebas

| Código | Función | Datos de prueba | Resultado esperado | Resultado obtenido | Estado | Responsable | Evidencia |
|---|---|---|---|---|---|---|---|
| CP-01 | Capturar imágenes de residuos con la cámara del dispositivo y detectar su información mediante la IA Teachable Machine| Utilizar el botón de la cámara para capturar una fotografía de un residuo y enviarla al modelo de IA de Teachable Machine para su análisis. | La aplicación debe abrir la cámara, capturar la fotografía y detectar correctamente el material del residuo mediante el modelo de IA. | La aplicación abrió correctamente la cámara, capturó la fotografía y detectó el material del residuo mediante el modelo de IA  | Aprobada | Equipo de desarrollo | <img width="200" height="451" alt="resultado" src="https://github.com/user-attachments/assets/6b1a26cf-c3b8-4bc9-a8e3-7f516aaec28a" /> |
| CP-02 | Identificación de residuos de vidrio | Fotografiar un residuo de vidrio (por ejemplo, una botella o un frasco de vidrio) | Detectar el material como vidrio y mostrar la información correspondiente  | No realizado | Pendiente | Jorge Badani | Pendiente |
| CP-03 | Crear página con WordPress | Crear una página oficial del proyecto con WordPress | La página se crea correctamente, se guarda, es funcional y puede visualizarse sin errores  | No realizado | Pendiente | Equipo de desarrollo | Pendiente |
| CP-04 | Consultar puntos de reciclaje desde la página | Desarrollar e integrar la sección de puntos de reciclaje en la página web de la aplicación.  | La página debe mostrar correctamente los puntos de reciclaje disponibles y ser accesible para los usuarios. | No realizado | Pendiente | Equipo de desarrollo | Pendiente |

Estados: Aprobada, Fallida, Corregida, Pendiente.

## Errores encontrados

| Código | Descripción | Pasos para reproducir | Prioridad | Issue | Estado |
|---|---|---|---|---|---|
| E-01 | La aplicación no se pudo instalar en dispositivo Redmi Note 9 durante las pruebas. Se desconoce si el problema afecta a otros modelos. | 1. Transferir el archivo APK al dispositivo.<br>2. Intentar instalar la aplicación.<br>3. La instalación no se completa. | Alta | #1 | Pendiente |

## Validación con usuario

- Usuario o rol: Desarrollador de la app.
- Fecha: (Desconocida)
- Observaciones: Al intentr ejecutar la instalación de la APK dentro del dispositivo, este mostró el mensaje: **"There was a problem parsing the package"**.
- Cambios acordados: Investigar la causa de la incompatibilidad de la APK con los dispositivos probados y realizar nuevas pruebas en otros modelos de teléfonos Android.
