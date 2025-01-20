Challenge realizado para la empresa manguear.

Consigna: 
Desarrollar una API REST que devuelva el mensaje "Hello world" al ser consultada. La API debe ser implementada con AWS Lambda y expuesta mediante API Gateway.

Requisitos:
Utilizar cualquier lenguaje de programación soportado por AWS Lambda (Node.js, Python, etc.).
Utilizar serverless framework para poder utilizar la aplicación localmente y desplegarla

Especificaciones:
El endpoint debe ser accesible públicamente a través de Internet.
La respuesta debe ser un mensaje en formato JSON con el contenido:

{
  "message": "Hello world"
}

Implementación:
Crear una función Lambda para manejar la solicitud.
Configurar un API Gateway REST API para exponer el endpoint.

Entrega:
Entregar la URL pública generada por API Gateway para probar la API.
Entregar la URL del repositorio público con instrucciones claras de como poder levantar el proyecto localmente

_________________________________________________________________________________________________________________
Para ejecutar el repositorio una vez clonado, probar por consola respectivamente los siguientes comandos:

1) serverless invoke local --function helloworld
2) serverless deploy
3) curl https://5pzs28aiv4.execute-api.us-east-1.amazonaws.com/hello

4) URL pública generada: https://5pzs28aiv4.execute-api.us-east-1.amazonaws.com/hello

5) Link para ver mi explicación paso a paso de mi desarrollo del challenge: https://youtu.be/IPsTGkmoN5A?si=8U2QJJZxgcK06JZZ
6) 
