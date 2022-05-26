# ProyectoFinalTelematica
primero clonar el repositorio con el siguiente comando: 
git clone https://github.com/Andres241218/ProyectoFinalTelematica .

1. Para iniciar el contenedor se ejecuta el siguiente comando:
  sudo docker build -t proyectofinal:01 .

2. Para ejecturar el servicio se usa el siguiente comando:
  sudo docker run -it -p 80:80 proyectofinal:01 python3 app.py                                                                
 
