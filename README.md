# 3erIntentoPokedex

![image](https://user-images.githubusercontent.com/112832288/206821149-2297dda8-f181-4ccd-9c90-513ae1c0944e.png)

## API REST

proporcionan una forma flexible y ligera de integrar aplicaciones y surge como el método más común para conectar componentes en la arquitectura de microservicio

Una API de REST, o API de RESTful, es una interfaz de programación de aplicaciones (API o API web) que se ajusta a los límites de la arquitectura REST y permite la interacción con los servicios web de RESTful.

Las API son conjuntos de definiciones y protocolos que se utilizan para diseñar e integrar el software de las aplicaciones. Se pueden considerar como el contrato entre el proveedor de información y el usuario, donde se establece el contenido que se necesita por parte del consumidor (la llamada) y el que requiere el productor (la respuesta).

En el nivel más básico, una API es un mecanismo que permite a una aplicación/servicio acceder a un recurso dentro de otra aplicación o servicio. La aplicación/servicio que realiza el acceso se denomina cliente y la aplicación o servicio que contiene el recurso se denomina servidor.

Las API REST se pueden desarrollar mediante el uso de prácticamente cualquier lenguaje de programación y son compatibles con una variedad de formatos de datos. El único requisito es que se ajusten a los siguientes seis principios de diseño de REST, también conocidos como restricciones de arquitectura:

Interfaz uniforme
Separación entre cliente y servidor
Sin estado
Capacidad de almacenamiento en memoria caché
Arquitectura de sistema de capas
Código bajo demanda (opcional)

## Fetch y Axios

Axios: es una librería que facilitaa una acción en particular en el código JavaScript: llamar una URL o líneas HTTP. Axios actúa como un cliente HTTP significa que es como una herramienta que permite hacer peticiones de datos a una URL. El uso más común de esta herramienta es hacer peticiones de tipo GET a la URL de una API con datos que nececitamos para emplearlos en un proyecto.

Fetch: Es una herramienta muy similar a Axios ya que nos permite ejecutar las mismas acciones: llamar a una URL, solicitar datos determinados y procesarlos. La diferencia principal de Fetch en relación a Axios es que esta es una herramienta implementada directamente dentro del navegador. Significa que fetch es un método nativo del Browser Object Model, un concepto que nos permite acceder y manipular las propiedades del navegador desde su diversidad de métodos.

Hay que tener en cuenta que a la hora de trabajar con Fetch es que sus peticiones se ejecutan por medio de promesas. ya que las peticiones HTTP no tienen un tiempo determinado, asi que se consideran procesos asíncronos.

# 3erIntentoPokedex

#SERVICIOS UTILIZADOS: POKEAPI: https://pokeapi.co/

Para este proyecto se consumira la Api de pokemon, la cual nos proporcionara una "base de datos" que trabajaremos para obtener la informacion necesaria para simular el uso de un "Pokedex", el cual es un dispositivo en la que se almacena toda la informacion de los pokemones, en esta ocasion los de la primera generacion, en esta podremos encontrar los datos de los pokemones como su altura, peso, experiencia, tipo, habilidadaes, entre otras.

## Componentes

HEADER: 

Se mostrara la pantalla de inicio para empezar el Pokedex.

![image](https://user-images.githubusercontent.com/112832288/206822740-bd9838ac-a8f5-40c7-b8af-9b6e0f5a15b5.png)

LISTA DE POKEMONES:

Se desplegara la pantalla del Pokedex, la cual se podra utilizar para buscar cualquier pokemon de la primera generacion, este mostrara las items mas relevantes de los pokemones como su imagen, su nombre, su altura, peso y el tipo de pokemon.

![image](https://user-images.githubusercontent.com/112832288/206822941-20e5047d-4e83-4adf-93b1-2fee41717446.png)

