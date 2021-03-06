<!-- TITLE: Fund profile app -->
<!-- SUBTITLE: Con esta app mostramos una página con datos de un fondo dentro de la cartera de fondos de BBVA. Está construida con Polymer 2 y como la fuente de datos utiliza un mock server montado con json-server. -->

[Componentes](http://wiki.muflonex.eu:2000/componentes)
# Introducción
## Autores 
[Jorge Abad Mañes]()
[Mikolaj Bernecki](https://github.com/muflonex)
[Gloria Fernandez Cureses](https://github.com/gloriafercu/)
[Alejandro Martín Capparelli](https://github.com/amcapparelli/)
[Davíd Perailes Tejeiro]()
## Instalación
### Requisitos:
* node 8.x
* git
* bower (o un ZIP descargado [de la página con el repositorio](https://github.com/gloriafercu/fund-profile))
* Polymer CLI
* JSON-server

### Pasos
1. Clonar [el repositorio](https://github.com/gloriafercu/fund-profile) o extraer el ZIP descargado
2. En terminal: *`bower i`* dentro de la carpeta principal del proyecto para descargar dependencias
3. En terminal: *`json-server --watch data.json`*
4. En otro terminal: *`polymer serve -o`*   