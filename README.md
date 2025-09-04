#PUNTO 1

- Teniendo ya el mensaje.txt creamos el dockerfile con la siguiente estructura usando nano


FROM alpine:3.20

RUN apk add --no-cache curl

WORKDIR /app

contenedor
COPY mensaje.txt .

docker build -t mi_app:1.0 .

CMD ["cat", "/app/mensaje.txt"]

-construimos el contenedor con docker build -t mi_app:1.0 .
En la carpeta del punto 1 se encuentra el pantallazo

#PUNTO 2

Para ver la solución del punto 2 se deben ver los pantallazos de la siguiente manera en la carpeta del punto2

Paso1: CreacionVOlumenUsoCOnteiner
Paso2: CreacionTablaParcial
Paso3: eliminandoCOntenedor
Paso4: CreacionNuevoCOntainer

#Punto 3
Para ver la solución del punto 3 se deben ver los pantallazos de la siguiente manera en la carpeta llamada punto3

Paso 1: Carpeta web
Paso 2: container
paso3: localhostInicial
paso4y5: localhostfinal

