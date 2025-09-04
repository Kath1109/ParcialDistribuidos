
FROM alpine:3.20

RUN apk add --no-cache curl

WORKDIR /app


COPY mensaje.txt .


CMD ["cat", "/app/mensaje.txt"]
