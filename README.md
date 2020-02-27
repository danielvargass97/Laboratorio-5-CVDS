# Laboratorio-5-CVDS

## Daniel Vargas-Esteban Bernal

### Parte I. - Jugando a ser un cliente HTTP
3.  Antes de que el servidor cierre la conexión por falta de comunicación: 
	- Revise el resultado obtenido. ¿Qué codigo de error sale?, revise el significado del mismo en la lista de codigo de estado HTTP:
	301 Moved permanently: Estas y todas las solicitudes futuras deben dirigirse a la URL dado.

	- ¿Qué otros códigos de error existen?, ¿En qué caso se manejarán?:
		- 1xx: Respuestas informativas
		- 2xx: Peticiones correctas
		- 3xx: Redirecciones
		- 4xx: Errores del cliente
		- 5xx: Errores de servidor
4. Realice una nueva conexión con telnet, esta vez a:
	- Host: www.httpbin.org
    	- Puerto: 80
    	- Versión HTTP: 1.1

	Ahora, solicite (GET) el recurso /html. ¿Qué se obtiene como resultado?:
	
