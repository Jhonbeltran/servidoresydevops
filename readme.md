### En la computación en la nube hay tres capas:
1. Infraestructura como un servicio
2. Plataforma como un servicio
3. Software como un servicio


### Así como existen distintas capas, existen distintos tipos de nube, éstas son:
1. Pública --> Es aquella nube que se puede acceder a través de internet. Cualquier aplicación que se despliegue. Entre estas podemos ver que están AWS, Google Cloud, Microsoft Azure, Heroku, entre otras.

2. Privada --> Para empresas muy grandes que son muy celosas con su información. esta información se puede acceder por internet pero la persona que tiene la información posee el control sobre ella y la despliega, por ejemplo, en una zona determinada.
*** 

## Servicios de AWS

### Computación

* EC2: Elastic compute (levantar maquinas virtuales) instancias, se trabajan balanceadores de cargas, escalamiento (programable).  
* Route 53: Configuracion de DNS
* VPC: Virtual Private Cloud (Red Local) para comunicarme de una instancia a otra. ejemplo: cluster de base de datos en un VPC y una red de apliaciones en otro.

***

### Almacenamiento

* CloudFront: Content delivery network, distribuye informacion cuando sea requerida.
* Glacier: Servicio de almacenamiento, guardar informacion (backups), como datos contables.
* S3: Almacenamiento (se usa para informacion centralizada), almacenamiento de continuo acceso.

***

### Bases de datos

* DynamoDB: Servicio nosql de amazon. 
* RDS: usado para desplegar bases de datos relacionales.
* ElastiCache: Almacenado de informacion en memoria, que puede ser accedida por diferentes instancias.

*** 

### Despliegue de apliaciones

* CloudFormation: Templates para desplegar apliaciones facilmente. (como un wordpress).  
* CloudWatch: Monitoreo de los servicios de amazon.
* IAM: Servicio de identificacion de los usuarios de la cuenta de amazon.
* OpsWorks: Devops (formar pilas de requerimientos) para configurar que apliacion deseamos.  












 
