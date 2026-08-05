Guía de Explicación del Código: Recicla+
Esta guía está diseñada para ayudarte a presentar el código de la aplicación de una manera sencilla, ideal para alguien con experiencia en Python o Java pero nuevo en el desarrollo moderno de Android con Kotlin.
1. El Corazón de la App: Jetpack Compose
A diferencia del Java tradicional en Android (donde usabas XML), aquí usamos Jetpack Compose.
•
¿Qué es?: Es un sistema "declarativo". En lugar de decir cómo cambiar la pantalla (ej: button.setText("...")), simplemente describes qué debe haber en la pantalla según los datos actuales.
•
Comparación: Si conoces Python, piensa en cómo se definen funciones que devuelven componentes visuales. Si la función recibe datos nuevos, la pantalla se actualiza sola.
2. Estructura Principal (MainActivity.kt)
Es el punto de entrada. Aquí ocurre la magia de la navegación.
•
NavHost: Es como un "enrutador". Define qué pantalla mostrar según una "ruta" (ej: "main", "result", "settings").
•
rememberNavController: El objeto que maneja los viajes entre pantallas.
•
ImageClassifierHelper: Es el puente con la Inteligencia Artificial (TensorFlow Lite).
3. Manejo de Estados (El concepto de "Remember")
En Kotlin/Compose, verás mucho var algo by remember { mutableStateOf(...) }.
•
¿Para qué sirve?: En Python, una variable cambia y ya. En Android, si quieres que la pantalla reaccione a ese cambio, necesitas que el sistema "recuerde" el estado.
•
Ejemplo: Cuando la IA detecta un objeto, actualizamos classificationResult. Al ser un estado, la app sabe automáticamente que debe dejar de mostrar la cámara y mostrar la ResultScreen.
4. La Inteligencia Artificial
La app usa un modelo de TensorFlow Lite (un archivo .tflite).
•
Proceso:
i.
Se captura la foto.
ii.
Se convierte a un formato que la IA entienda (Bitmap).
iii.
La IA devuelve etiquetas y probabilidades (ej: "Plástico" con 90% de confianza).
iv.
El código filtra esos resultados y busca la información de reciclaje correspondiente.
5. Diseño y Temas (ui/theme)
•
Colors.kt: Aquí definimos la paleta de colores (Verdes, Azules, etc.).
•
Theme.kt: Define cómo se ve la app en modo claro y oscuro. Es como un archivo CSS global pero escrito en Kotlin.
6. Funciones "Composables" (Las piezas del LEGO)
Cada pantalla (MainScreen, ResultScreen, etc.) es una función marcada con @Composable.
•
Estas funciones se pueden reutilizar. Por ejemplo, el ActionButton que creamos para el menú principal es una pieza que usamos 4 veces cambiándole solo el texto, el icono y el color.
Resumen para tu presentación:
"Nuestra aplicación está construida con Kotlin y Jetpack Compose, la tecnología más moderna de Google. Funciona mediante un sistema de componentes reactivos: la interfaz de usuario se actualiza automáticamente cuando los datos cambian. La detección de materiales se realiza localmente en el dispositivo mediante Inteligencia Artificial con TensorFlow Lite, lo que garantiza velocidad y privacidad. La arquitectura está dividida en pantallas independientes conectadas por un sistema de navegación centralizado."
