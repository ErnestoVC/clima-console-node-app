# clima-console-node-app
_Es una aplicación interactiva de consola que permite buscar una ciudad y utilizando la API MapBox sacamos la Latitud y Longitud. Estos valores serán utilizados por la API de OpenWeather para saber la temperatura actual, mínimo, máxima y como está._

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._


### Pre-requisitos 📋

_Se necesita instalar los módulos de node utilizando el siguiente comando:_

```
npm install
```

### Instalación 🔧

_Crear el archivo **.env** donde se introducirán las credeanciales para utilizar la API de MapBox y OpenWeather_

```
MAPBOX_KEY=YOUR_KEY
```

```
OPENWEATHER_KEY==YOUR_KEY
```

_Después de configurar el **.env**, simplemente se puede ejecutar con el siguiente comando:_
```
npm start
```
**O**
```
node app
```

## Construido con 🛠️

* [Node.js®](https://nodejs.org/es/) - Node.js® es un entorno de ejecución para JavaScript construido con el motor de JavaScript V8 de Chrome
* [colors.js](https://www.npmjs.com/package/colors) - Un módulo de Node.js para darle color a tu consola
* [Inquirer.js](https://www.npmjs.com/package/inquirer) - Inquirer.js se esfuerza por ser una hermosa interfaz de línea de comandos fácilmente integrable para Node.js
* [dotenv](https://www.npmjs.com/package/dotenv) - Dotenv es un módulo de dependencia cero que carga variables de entorno desde un archivo .env en process.env.
* [MapBox](https://www.mapbox.com/) - Datos de ubicación precisos y potentes herramientas de desarrollo para cambiar la forma en que navegamos por el mundo
* [OpenWeather](https://openweathermap.org/) - Un enfoque científico pero simple para el pronóstico del tiempo. Gratis. Sin anuncios