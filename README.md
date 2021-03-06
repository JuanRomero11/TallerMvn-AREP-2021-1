
# Mean and standard deviation
# Profesor: Luis Daniel Benavides
# AREP - Arquitecturas Empresariales 2021-1

El proyecto Mean and standard deviation tiene como fin realizar el calculo en cuanto a la media y la desviacion estandar de una serie de datos los cuales se almacenaran de uno en uno en una implementacion PROPIA de la coleccion LikendList java, basada en esta se realizo una implementacion de una lista encadenada, y creando los diferentes metodos para poder realizar la insercion, eliminacion,iterador, impresion y busqueda de un dato en una posicion en especifico. 

## Prerrequisitos

Como primera medida se debera intalar el JDK y maven y si es necesario un editor como ECLIPSE,NETBEANS,etc. Si solo se quiere ejecutar el proyecto de manera local solo se necesitara el JDK y maven. Para el JDK JAVA se instala la versión 8, a continuacion se adjuntara el link donde muestran las instrucciones detalladas de como descargar este y ademas en esta mismo link se podra realizar la descarga y futura instalacion, de igual forma se adjunta el link de la pagina oficial de maven en el cual esta el instructivo detallado y los paquetes necesarios para la version del sistema operativo en el cual se ejecutara, y por ultimo es recomdable descargar la aplicacion git tambien se anexara el link desde la pagina oficial, se anexan los links debido a que se especifican mas en cada uno con respecto a cada sistema operativo y no uno en especifico.

### Instalacion

Descargar JDK e instrucciones de instalacion
https://www.oracle.com/technetwork/es/java/javase/downloads/index.html
Descargar maven e instrucciones de instalacion
https://maven.apache.org/download.cgi
Descargar Git e instrucciones de instalacion
https://git-scm.com/downloads

## Construccion
Este proyecto basicamente esta construido en maven y el editor que se utilizo fue NetBeans, teniendo el JDK antes mencionado, especificamente se utilizo el lenguaje Java.

## Diseño

![alt text](https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/imagenes/Captura.PNG)

## Descripcion del diseño
En este diseño se pueden evidenciar dos paquetes principales, uno en el que se encuentra la clase calculator la cual puede realizar el calculo de la media, la desviacion estandar, haciendo uso de nuestra LikendList y sus metodos, esta se encuentra el otro paquete principal.


## Como usar el Proyecto
En este mismo repositorio puede clonar o descargar el proyecto a traves de la aplicacion git ya instalada en su computador. Recomendacion, Si se clona utilizar el comando :

        git clone https://github.com/JuanRomero11/TallerMvn-AREP-2021-1
        
Despues de que el proyecto esta clonado se accede a la consola del computador en este caso accedemos a la terminal de comandos de Windows(cmd) y entramos directamente en la carpeta en donde esta nuestro proyecto y como primer paso compilamos con el comando 

        mvn package


![alt text](https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/imagenes/Package.PNG)
      

## Ejecución de Pruebas

Para ejecutar las pruebas se pueden utilizar dos comandos:

          mvn package
          
          mvn test
          
Despues de ello se ejecutan todas las pruebas realizadas 

Las pruebas se realizaron con los siguientes datos:

![alt text](https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/imagenes/Datos.PNG)

y se comprobaron los resultados con los siguientes datos:

![alt text](https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/imagenes/Resultados.PNG)

Se realizaron en total nueve pruebas, cinco de la clase LinkendList y cuatro de la clase Calculator.

Evidencia que las pruebas de Calculator se realizaron con los datos correctos

![alt text](https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/imagenes/testCalcularMedia.PNG)

![alt text](https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/imagenes/CalcularMedia2.PNG)

![alt text](https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/imagenes/CalcularDesviaci%C3%B3n.PNG)

![alt text](https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/imagenes/CalcularDesviaci%C3%B3n2.PNG)

Resultados obtenidos:

![alt text](https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/imagenes/ResulTest.PNG)

## Autor
Juan Guillermo Romero 
## License
Este codigo tiene una licencia Apache License 2.0 la cual se detalla en https://github.com/JuanRomero11/TallerMvn-AREP-2021-1/blob/main/LICENSE
