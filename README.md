# Proyecto Control De Equipos

![Pantalla de Inicio](C:\Users\brand\Desktop\background.jpg)

## Descripcion del Proyecto
Esta propuesta esta diseñada para el departamento de computo,
el cual es responsable del resgistro de todos los esquipos con los
que cuenta la institucion. Este proyecto pretende optimizar el
proceso de registro de dichos equipos.

## Estructura del Proyecto
Esta aplicacion esta estructurada con la arquitectura MVP
la cual trabaja con un Modelo para controlar los datos con los
que se estaran utilizando, un Presentador el cual estara ralizando 
los distintos procesos interactuando con los datos del Modelo y por ultimo
una Vista la cual estara cordinada con el Presentador para manipular los
procesos que se implementaron en el Presentador.

## Gestion de Datos
Para la manipulacion de los datos con los que se estaran trabajando se 
utiliza la plataforma de Firebase que nos proporciona Google. Firebase dentro de
sus herramientas nos brinda una Base de Datos en Tiempo Real, esta base de datos 
trabaja con el formato Json el cual esta basado en una estructura de arbol, donde 
a partir de una raiz, se secciona en nodos los cuales almacenan datos, y cada dato 
cuenta con un identificador unico.

## Patrones de Diseño
En este proyecto se utilaron algunos de los Patrones de Diseño.
Singleton, este patrón de diseño se encarga de que una clase determinada
unicamente pueda tener un único objeto.
Adapter, Convertir la interfaz de una clase en otra interfaz esperada por los
clientes. Permite que clases con interfaces incompatibles se comuniquen.

# Modulos del Proyecto
* Registro de Equipos
* Asigancion
* Consultas
* Modificacion
* Eliminacion
* Consultas Generales