# VREspaceRoomUE
Unreal Engine code to facilitate the creation of VR Escape Rooms that interact with physical Object using Antilatency systems

Spanish requirements

Primero debes descargar [Android Studio](https://developer.android.com/studio) si no lo tienes e instalar el Android SDK version 29 y el Android NDK version 21.4.7075529. Además, debes marcar la opción para instalar las herramientas de desarrollo de Android (Android development tools) durante la instalación del SDK.

Después, descarga [Java jre](https://www.oracle.com/es/java/technologies/javase/javase8-archive-downloads.html) version 1.8.0_242. 

Establece las librerías correctas en Unreal accediendo a los Project Settings on Edit>Project Settings...>Platforms>Android SDK como se especifica en las [Oculus Guidelines](https://developer.oculus.com/documentation/unreal/unreal-quick-start-guide-quest/?locale=es_ES). 

Tras ello, incluye los plugin de Oculus, Antilatency y Escape Rooms en tu proyecto. Puedes encontrar el plugin de Antilatency en su [website](https://developers.antilatency.com/Root/Index_en.html) dentro de la pestaña SDK. Debes seleccionar todas las funciones y ejemplos que te proporcionarán y la versión para Unreal Engine 4.27.2 y después hacer click en descargar. 

Tras descargarlo, expande el archivo resultante a la carpeta Plugin dentro de tu proyecto. Si la carpeta no existe dentro de tu proyecto, creala e introduce en ella la carpeta expandida. Después debes ir a la ventana Edit>Plugins y activar el plugin de Antilatency que acaba de aparecer. Si el plugin no aparece, reinicia la aplicación y vuelve a acceder a la ventana de los plugins.

Repite el mismo proceso con el plugin de Escape Rooms.

Por otro lado, para incluir el plugin de Oculus, accede a la ventana de plugins, busca el plugin Oculus VR y actívalo. 

English Requirements

You must download [Android Studio](https://developer.android.com/studio) and install Android SDK version 29, Android NDK version 21.4.7075529 and Android Development tools.

Then download [Java jre](https://www.oracle.com/es/java/technologies/javase/javase8-archive-downloads.html) version 1.8.0_242. 

Set the downloaded libraries on the project Settings, located at Edit>Project Settings...>Platforms>Android SDK as per the Oculus Guidelines [Oculus Guidelines](https://developer.oculus.com/documentation/unreal/unreal-quick-start-guide-quest/?locale=es_ES). 

Add the Antilatency Plugin to your project ([website](https://developers.antilatency.com/Root/Index_en.html)) for Unreal 4.27.2 and drag the Escape Room plugin to your project.

Make sure to activate Oculus VR plugin to allow the project to correctly install in Oculus.
