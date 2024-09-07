# NTFY
NTFY | Servicio notificaciones NTFY autohospeado en Docker

Saber uid y gid; usar comando id

genbyte@raspberrypi:~ $ id

Cambiar puerto 80:80 por 8000:80 en el docker-compose.yml. El 80 lo tengo usado para otro Servicio.

Acceso vía web:

http://IP:8000/

Después crear tópico, indicando nombre fijo ó aleatorio. Para hacer la prueba, desde la terminal escribir los siguiente:

curl -d "Mensaje" IP:PUERTO/NombreTópico

Ejemplo: curl -d "Es una prueba de NTFY Genbyte" 192.168.1.101:8000/d86976fMhjuF5G

![image](https://github.com/user-attachments/assets/6de3aeb2-c1cf-460c-ae16-f1049eeffd16)

Documentación oficial: https://docs.ntfy.sh/install/#docker
