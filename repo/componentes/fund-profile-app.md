<!-- TITLE: fund-profile-app -->
<!-- SUBTITLE: El componente principal de la aplicación, aquí se resuelven peticiones de datos, se monta el grid de la vista y se pasan los datos al resto de componentes. -->

# Elementos
## Sub-componentes
* [info-table](http://wiki.muflonex.eu:2000/componentes/info-table)
* [return-calculation](http://wiki.muflonex.eu:2000/componentes/return-calculation)
* [date-browser](http://wiki.muflonex.eu:2000/componentes/date-browser)
* [general-information](http://wiki.muflonex.eu:2000/componentes/general-information)

## Métodos
| Método | Parámetros | Return | Descripción | 
|---|---|---|---|
| formatDate() | *`Date`* date  | *`String`* date | Devuelve la fecha en formato DD/MM/YY |
| convertDate() | *`Date`* date  | *`Number`* timestamp | Recibe fecha en formato Date y devuelve el timestamp que coresponde a la medianoche de UTC | 
| changeDate() | *`Event`* e | - | Recibe el `Evento` de date-browser que lleva un `String` con la fecha elegida, la cual utiliza el anexo de [info-table](http://wiki.muflonex.eu:2000/componentes/info-table) en su componente hijo [return-calculation](http://wiki.muflonex.eu:2000/componentes/return-calculation) |
| handleResponse() | - | - | Sirve para manejar el estado de carga de iron-ajax durante su respuesta |

## Dependencias
* paper-spinner
* iron-ajax
* tab-menu