maxdrone - DroneControl
========

A Max/Msp mxj external for controlling the ARDrone written in scala, uses [JavaDrone](http://code.google.com/p/javadrone/) api

-------

To build:

  * put a copy of max.jar and jitter.jar in ./lib (found in your max installation directory)
  * sbt compile
  * sbt proguard -> to package as single jar file

To run:

  * build or download latest build: [ARDrone1.0](https://github.com/downloads/fishuyo/max-ardrone/DroneControlv0.3.zip) or [ARDrone2.0 - no video](https://github.com/downloads/fishuyo/max-ardrone/DroneControlv0.3.2.zip)
  * place built jar into MAXMSP_PATH/Cyclin' 74/java/lib 
  * see DroneControl.maxhelp for usage
