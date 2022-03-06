
Investigar que hacen y para que se usan los siguientes comandos dentro de un Dockerfile:


## HEALTHCHECK
### Que hace:
Permite indicar como se comprueba la salud de un contenedor. Para hacerlo, se declara como se verifica si el contenedor está saludable o no

* 0 → Significa que el contenedor funcionaría bien y el servicio está correcto.
* 1 → Este código de retorno significaría que el contenedor no está dando el servicio esperado.

### Para que se utiliza:
Validar la salud de un contenedor corriendo en un ambiente


## ONBUILD
### Que hace:
No terminé de entenderlo.
### Para que se utiliza:
No terminé de entenderlo.


## VOLUME
### Que hace:
Mapea un directorio local con un directorio del contenedor.

### Para que se utiliza:
Guardar datos a pesar de que el contenedor se detenga.
