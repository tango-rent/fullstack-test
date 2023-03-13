# Instrucciones de desarrollo

## Desafío Frontend:

Crear una página en HTML utilizando [Vue.js v3](https://vuejs.org/) o [React.js v18] para diseñar un calendario, que recibe como parametro un archivo json con la siguiente estructura:

```
[
    {
        "id": 0,
        "name": "Sofía González",
        "weekDay": "lunes",
        "startTime": "10:30",
        "enddTime": "11:00"
    }, {
        "id": 1,
        "name": "Santiago Morales",
        "weekDay": "martes",
        "startTime": "12:30",
        "enddTime": "14:30"
    },{
        "id": 2,
        "name": "Ana Herrera",
        "weekDay": "miercoles",
        "startTime": "16:00",
        "enddTime": "16:15"
    },{
        "id": 3,
        "name": "Luisa Gutiérrez",
        "weekDay": "jueves",
        "startTime": "15:45,
        "enddTime": "16:30"
    },{
        "id": 4,
        "name": "Carlos Castro",
        "weekDay": "viernes",
        "startTime": "18:45",
        "enddTime": "19:45"
    },{
        "id": 5,
        "name": "Valentina Flores",
        "weekDay": "martes",
        "startTime": "14:30",
        "enddTime": "15:00"
    },{
        "id": 6,
        "name": "Pablo Hernández",
        "weekDay": "viernes",
        "startTime": "14:30",
        "enddTime": "15:30"
    },{
        "id": 7,
        "name": "Juan Soto",
        "weekDay": "lunes",
        "startTime": "17:30",
        "enddTime": "18:30"
    }
]
```
El resultado debe ser un calendario de la semana actual, con bloques de horario de 1 hora y se deben dibujar las horas tomadas, respetando los horarios que indican los registros.

El diseño queda a la imaginación del desarrollador(a), junto con los colores o utilidades que desea usar, esta es una imagen de referencia:

![cal](https://user-images.githubusercontent.com/3177719/224832396-8049dbe2-5de6-43f6-b3eb-43df6bc50ca9.png)

Al abrir la página HTML se debe cargar el calendario sin hacer ninguna interacción.

**Bonus**: Mostrar una línea roja sobre el calendario que indique la hora actual. Esta hora se debe tomar del computador del cliente.

## Desafío Backend:

Desarrollar un scraper en Python3 que permita obtener información de esta [página web](https://renter.tangoapp.rent/advanced-search?p=all) y almacenarla en un archivo Excel con las siguientes columnas:

* Dirección
* Valor de arriendo
* Dormitorios
* Estacionamientos
* Gastos comunes
* URL 1º foto
* ¿Acepta mascotas?
* Superficie total
* Orientación 


**Nota**: Se debe usar la librería [Selenium](https://pypi.org/project/selenium/) para obtener los datos.


## Entrega
El resultado se debe enviar por correo a carlos.veliz@tango.rent y se debe entregar en un archivo .zip, junto con todas las indicaciones para ser revisado.

Si el resultado es una entrega parcial de lo solicitado, se debe indicar qué funciona y qué no.

Si tienes dudas sobre este test, puedes crear supuestos o escribir directamente las dudas acá: carlos.veliz@tango.rent.
