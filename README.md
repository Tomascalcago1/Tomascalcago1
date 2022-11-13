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
-	Realizar un request GET a la URL: 

![Captura de pantalla (2)](https://user-images.githubusercontent.com/89410795/201197702-ca6fc6a5-4967-4e66-955d-134e91c7c1c9.png)

>2
- Realizar un request POST a la URL anterior, y con mi nombre y mail en el body:

![Captura de pantalla (4)](https://user-images.githubusercontent.com/89410795/201197910-8c7bf9b5-d2f6-4d04-a451-d0ec654a253e.png)

>3
-	Realizar nuevamente un request GET a la URL: 

![Captura de pantalla (3)](https://user-images.githubusercontent.com/89410795/201197947-e902209b-77cb-4fa0-a18b-e4143fa047c1.png)

La diferencia entre las llamadas 1 y 3 es que luego de realizada la segunda request GET se muestran mis datos en la pagina al final de la misma 

## Ejercicio 4

[Perfil Trailhead](https://trailblazer.me/id/tcalcagno)

## Ejercicio 5

>Lead:

Es donde se encuentran las cuentas de los candidatos para la empresa. Los datos que se almacenan son: Nombre completo, Compañia, Estado o provincia, Correo electronico, Estado del candidato, Fecha de creacion, Alias del propietario.

>Account:

Es donde se encuentran las cuentas de las empresas con las que se tiene relacion. Los datos que se almacenan son: Nombre de la cuenta, Sitio de la cuenta, Estado o provincia de facturacion, Telefono, Tipo, Alias del propietario.

>Contact:

Es donde se guardan los contactos de los empleados que trabajan en las empresas con las que se tiene relacion. Los datos que se almacenan son: Nombre completo, Nombre de la cuenta, Cargo, Telefono, Correo electronico, Alias del propietario.

>Opportunity:

Es donde se encuentran las oportunidades de ventas. Los datos que se almacenan son: Nombre de la oportunidad, Nombre de la cuenta, Importe, Fecha de cierre, Etapa, Alias del propietario de la oportunidad.

>Product:

Es donde se encuentran los detalles de los productos. Los datos que se almacenan son: Nombre del producto, Codigo del producto, Alias del propietario.

>PriceBook

Es donde se encuentran los detallados los precios de los productos. Los datos que se almacenan son: Nombre de la lista de precios, Descripcion, Alias del propietario.

>Quote



>Asset

Es donde se encuentran los datos de un activo. Los datos que almacena son: Contacto, Cuenta, Estado, Numero de serie, Propietario del activo, Ubicacion.

>Case:

Es donde se encuentan todos los casos de los contactos que se deben resolver. Los datos que se almacenan son: Numero del caso, Nombre del contacto, Asunto, Estado Prioridad, Fecha/hora de apertura, Alias del propietario del caso.

>Article


![Ejercicio 5 drawio](https://user-images.githubusercontent.com/89410795/201535108-96c4e50a-89a3-47d3-8f33-7f38e8cec973.png)


## Ejercicio 6

- Soluciones de Salesforce

>¿Qué es Salesforce?

Salesforce es una **plataforma de gestión de las relaciones con los clientes** (CRM) basada en la nube que proporciona a todos los departamentos de su organización, incluidos los de marketing, ventas, servicio de atención al cliente y ecommerce, una visión unificada de sus clientes en una plataforma integrada.

>¿Qué es Sales Cloud?

Sales Cloud es una **herramienta de ventas todo en uno y CRM** que combina la mayoría de las mismas capacidades que encontrarás en otras herramientas. Sin embargo, con Sales Cloud, obtienes las funciones de automatización de ventas que necesitas en un solo lugar.

>¿Qué es Service Cloud?

Service Cloud es una **solución completa de atención al cliente** creada especialmente para dar soporte a los clientes a cualquier hora y en cualquier lugar, por teléfono, correo electrónico, redes sociales, chats y páginas o comunidades de auto ayuda.

>¿Qué es Health Cloud?

Health Cloud es una plataforma especialmente diseñada para la **gestión clínica de pacientes por medio de tecnologías on-cloud**, la cual ofrece: una comunicación más personalizado entre pacientes, miembros, proveedores y prestadores de servicios de salud, y un mejor ajuste a los procesos, servicios y datos médicos según el perfil de cuidado de cada paciente.

>¿Qué es Marketing Cloud?

Como parte de los servicios Salesforce, Marketing Cloud es un **módulo de Salesforce** que contiene múltiples herramientas para mejorar la **interacción de las marcas con sus clientes** y potenciales a través de todo tipo de canales.


- Funcionalidades de Salesforce




