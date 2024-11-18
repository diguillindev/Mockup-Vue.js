Realizado con Vue cdn 
Ver las versiones de un paquete en unpkg:
URL básica de unpkg: Puedes acceder a un paquete específico utilizando la URL básica de unpkg, yendo directamente a la versión que necesitas.

Ejemplo:

https://unpkg.com/:package@:version/:file
Ejemplo con Vue.js:

https://unpkg.com/vue@2.6.14/dist/vue.min.js
Esto cargará la versión 2.6.14 de Vue.js desde unpkg.

Ver todas las versiones de un paquete: Si deseas ver todas las versiones disponibles de un paquete, simplemente termina la URL con una barra (/). Esto mostrará un listado de los archivos disponibles para ese paquete.

Ejemplo para Vue:

https://unpkg.com/vue/
Usar un paquete de npm en tu proyecto Vue.js:
Si tienes un paquete de npm que deseas usar en tu proyecto Vue, solo necesitas incluir el enlace a unpkg en tu HTML o JavaScript.

Ejemplo básico:

<script src="https://unpkg.com/vue@2.6.14/dist/vue.min.js"></script>
Esto carga Vue.js en tu página sin necesidad de instalar nada en tu proyecto localmente.

Uso de versiones y etiquetas con unpkg:
Puedes usar semver (versionado semántico) o etiquetas como latest en lugar de una versión fija.

https://unpkg.com/vue@latest/dist/vue.min.js
Esto siempre cargará la última versión de Vue disponible.
