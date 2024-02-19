# Springboot

SpringBoot es un framework de Spring que permite crear aplicaciones standalone, sin necesidad de un servidor de aplicaciones externo a ella.

Para iniciar una aplicación SB (SpringBoot a partir de ahora) bastará con ejecutar el comando "java -jar nombre_de_la_aplicacion.jar"

```sql
CREATE TABLE `user` (
  `FECHA_MODIFICACION` datetime NOT NULL,
  `FECHA_REGISTRO` datetime(6) NOT NULL DEFAULT current_timestamp(6),
  `ID` int(11) NOT NULL AUTO_INCREMENT,
  `USERNAME` varchar(255) NOT NULL,
  `NOMBRE` varchar(255) NOT NULL,
  `PASSWORD` varchar(255) NOT NULL,
  PRIMARY KEY (`ID`)
);
```

Se puede acceder al SWAGGER desde el siguiente [enlace](http://localhost:8080/demo-bg/api/swagger-ui/index.html).
<p align="center"><img src="https://raw.githubusercontent.com/javiercode/demoBG/main/src/main/resources/assets/swagger.png"></p>
