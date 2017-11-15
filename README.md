# El Vigilante
Proyecto avanzado 

### Dashboard

![](https://github.com/vicboma1/ElVigilanteBluemix/blob/master/assets/vigilante.gif)

Este proyecto hace uso de ingeniería inversa para desamblar el empaquetado de la aplicación dashboard de node-RED.

Se ha sustituido los componentes de la libreria original por componentes BootStrap.

El esquema de nodos baja las siguientes dependencias :

* https://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css
* https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap.min.css
* https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css
* https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js

A través de un textEdit, se introduce un nombre de usuario y se hace uso de la Api de Github para la identificación del usuario.

Luego se consulta el perfil de usuario y se obtienen los datos que se presentan en un formulario asíncrono.

La carga de la imagen se hace mediante una promesa.

En segundo plano, se crea un tweet en la cuenta de Twitter de "ElVigilanteCloud" con la Ip y el nombre de la consulta.

![](https://github.com/vicboma1/ElVigilanteBluemix/blob/master/assets/vigilante.png)


@Author: [Victor Bolinches Marin](https://github.com/vicboma1)  

@Documento Principal  [CoEValencia - Hackathon 2017](https://github.com/CoEValencia/Hackathon_2017)

