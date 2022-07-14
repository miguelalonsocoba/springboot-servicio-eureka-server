# Servicio Eureka Server

### Introducción

Se utiliza para registrar los mircoservicios con la finalidad de registrar nombre de la maquina o IP y el puerto, y como respuesta del servicio de Eureka pasara el registro completo de los demas microservicios que esten registrados en este ecosistema para que se puedan comunicar y escalar de forma automatica, sin especificar el puerto, IP, ni el nombre del dominio. Se conectan y trabajan de forma automatica, usando el nombre del microservciio.

### Caracteristicas

- Java 11
- Puerto del servidor de Eureka: http://localhost:8761/
- Desactivación de configuración de Eureka-Cliente, ya que solo se usa como servidor para el registro de los microservicios.

### Dependencias

- spring-cloud-starter-netflix-eureka-server
- spring-boot-devtools