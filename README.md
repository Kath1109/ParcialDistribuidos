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
