
Investigar que hacen y para que se usan los siguientes comandos dentro de un Dockerfile:


## HEALTHCHECK
### Que hace:
Permite indicar como se comprueba la salud de un contenedor. Para hacerlo, se declara como se verifica si el contenedor está saludable o no, y es tan simple como un comando, que puede devolver:

0 → Significa que el contenedor funcionaría bien y el servicio está correcto.
1 → Este código de retorno significaría que el contenedor no está dando el servicio esperado.

### Para que se utiliza:
Validar salud de un contenedor corriendo en un ambiente
El estado de los contenedores es una información que Docker “conoce”, pero no hace nada con ella. Esto cambia con los orquestadores, como por ejemplo Docker Swarm. Este último tiene esta salud en cuenta para dos cosas:

Reiniciar (y posiblemente recolocar) los contenedores unhealthy para asegurar que se da servicio con el número de contenedores especificado.
Para hacer rolling updates, esperando a que los contenedores estén saludables antes de quitar los anteriores, resultando en despliegues sin downtime.


## ONBUILD
### Que hace:
### Para que se utiliza:



## VOLUME
### Que hace:
### Para que se utiliza:
