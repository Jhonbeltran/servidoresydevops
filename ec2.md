# EC2 Amazon Web Services

1. Instancia: Es el sistema operativo virtualizado. (Puede ser Windows o Linux)
2. Amazon Machine Image: Plantilla preconfigurada para la instancia. contiene el s.o y los paquetes necesarios. 
3. Volumen de almacenamiento de la instancia: Almacenamiento temporal.
4. Virtual Private Network: Red local privada.


### Para una IP fija podemos usar una Elastic Ip

La encontraremos en la seccion de NETWORK & SECURITY, creamos una nueva ip elastica y la vinculamos a una de nuestras instancias, esto es util para cuando configuremos los registros DNS, lo cual evita que cuando la instancia se reinicie la ip cambie, recuerda marcar la opcion de reasociacion.

