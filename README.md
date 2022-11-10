## Ejercicio 2

>1.	¿Qué es un servidor HTTP? 

Un servidor web o servidor HTTP es un programa informático que **procesa una aplicación** del lado del servidor, realizando conexiones bidireccionales o unidireccionales y síncronas o asíncronas con el cliente y **generando o cediendo una respuesta** en cualquier lenguaje o aplicación del lado del cliente.


>2.	¿Qué son los verbos HTTP? Mencionar los más conocidos

HTTP define un conjunto de métodos de petición para **indicar la acción** que se desea realizar para un recurso determinado. Aunque estos también pueden ser sustantivos, estos métodos de solicitud a veces son llamados HTTP verbs

Los verbos mas conocidos son:

- GET :
El método GET solicita una representación de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.

- HEAD :
El método HEAD pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta.

- POST :
El método POST se utiliza para enviar una entidad a un recurso en específico, causando a menudo un cambio en el estado o efectos secundarios en el servidor.

- PUT :
El modo PUT reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición.

- DELETE :
El método DELETE borra un recurso en específico.

- CONNECT :
El método CONNECT establece un túnel hacia el servidor identificado por el recurso.

- OPTIONS :
El método OPTIONS es utilizado para describir las opciones de comunicación para el recurso de destino.

- TRACE :
El método TRACE realiza una prueba de bucle de retorno de mensaje a lo largo de la ruta al recurso de destino.

- PATCH :
El método PATCH es utilizado para aplicar modificaciones parciales a un recurso.


>3.	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?

HTTP se basa en un modelo solicitud / respuesta, de modo que hay dos tipos de mensajes HTTP: la solicitud y la respuesta. El navegador abre una conexión a un servidor y **realiza una solicitud**. El servidor procesa la solicitud del cliente y **devuelve una respuesta**. 
Las cabeceras y los códigos de estado HTTP resultan útiles como ayuda para programas intermediarios y clientes a la hora de **comprender la información sobre solicitudes y respuestas de aplicaciones**. Las cabeceras HTTP contienen información de metadatos. Los códigos de estado HTTP proporcionan información de estado sobre la respuesta.


>4.	¿Qué es un queryString? (En el contexto de una url)

Query string es un término informático que se utiliza para hacer referencia a una interacción con una base de datos. Es la parte de una URL que contiene los datos que deben pasar a aplicaciones web.


>5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

Los códigos de estado de respuesta HTTP **indican si se ha completado satisfactoriamente una solicitud HTTP específica**. Las respuestas se agrupan en cinco clases:

- Respuestas informativas (100–199),
- Respuestas satisfactorias (200–299),
- Redirecciones (300–399),
- Errores de los clientes (400–499),
- Errores de los servidores (500–599).


>6.	¿Cómo se envía la data en un Get y cómo en un POST? 

La diferencia entre los métodos get y post radica en la **forma de enviar los datos a la página** cuando se pulsa el botón “Enviar”. Mientras que el método GET envía los datos usando la URL, el método POST los envía de forma que no podemos verlos (en un segundo plano u "ocultos" al usuario).


>7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?

Cuando accedemos a una pagina el navegador utiliza el verbo **GET**


>8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

- JSON está constituído por dos estructuras:

  - Una colección de pares de nombre/valor. En varios lenguajes esto es conocido como un objeto, registro, estructura, diccionario, tabla hash, lista de claves o un arreglo asociativo.
  - Una lista ordenada de valores. En la mayoría de los lenguajes, esto se implementa como arreglos, vectores, listas o sequencias.
 
- HTM tiene las siguientes caracteristicas :
  
  - Los elementos de un documento XML deben seguir una estructura de “árbol” (estrictamente jerárquica).
  - Los elementos deben estar correctamente anidados.
  - Los elementos no se pueden superponer entre ellos.
  - Sólo puede haber un elemento raiz, en el que estén contenidos todos los demás.


>9.	Explicar brevemente el estándar SOAP

SOAP es un protocolo ligero para el intercambio de información en entornos descentralizados y distribuidos. Los mensajes SOAP son las transmisiones de información de remitentes a destinatarios. Los mensajes SOAP se pueden combinar para crear patrones de petición/respuesta.


>10.	Explicar brevemente el estándar REST Full

Un conjunto de funciones y procedimientos que ofrece una biblioteca para que otro software la utilice como capa de abstracción mediante el formato estándar de JSON o XML

>11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

Los HTTP headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. La primera línea es la línea del request, que contiene su información básica (método HTTP, URL y versión)
Content-Type es la propiedad de cabecera (header) usada para indicar el media type (en-US) del recurso. Content-Type dice al cliente que tipo de contenido será retornado.hace 3 días

## Ejercicio 3

>1

![Captura de pantalla (2)](https://user-images.githubusercontent.com/89410795/201197702-ca6fc6a5-4967-4e66-955d-134e91c7c1c9.png)
>2
>3

