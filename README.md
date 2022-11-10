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

Los códigos de estado de respuesta HTTP indican si se ha completado satisfactoriamente una solicitud HTTP específica. Las respuestas se agrupan en cinco clases:

- Respuestas informativas (100–199),
- Respuestas satisfactorias (200–299),
- Redirecciones (300–399),
- Errores de los clientes (400–499),
- Errores de los servidores (500–599).


>6.	¿Cómo se envía la data en un Get y cómo en un POST? 
>7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?
>8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
>9.	Explicar brevemente el estándar SOAP
>10.	Explicar brevemente el estándar REST Full
>11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?


