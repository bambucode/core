# Shoppe en Español

Plataforma e-commerce basada en Rails 4 en español.


## Características

* Atractiva y fácil manera de usar la interfaz admin integrado con autentificación
* Mantenimiento de producto/catálogo
* Control de Almacen
* Mantenimiento de impuestos
* Flujo de orden personalizado
* Mantenimiento de envio contemplando el peso del producto
* Fork de https://github.com/grapheno/core

## Getting Started

Shoppe provee un framework para una tienda en linea y solo puedas dedicarte a la parte frontal (del cliente) de la aplicación. Al ser responsable del frontend de la aplicación puedes editar y agregar el método de pago que se desee.

### Instalando la gema en una nueva aplicacion (Rails 4)

Empezar a trabajar con shoppe es muy simple. Solo sigue las siguientes instrucciones:

    rails new mi_tienda
    cd mi_tienda
    echo "gem 'shoppe', :git => 'https://github.com/bambucode/core'" >> Gemfile
    bundle
    rake db:create
    rails generate shoppe:setup
    rails generate nifty:attachments:migration
    rails generate nifty:key_value_store:migration
    rake db:migrate shoppe:setup
    rails server

## Contribuciones

Cualquiera que quiera ayudar con el proyecto debe ponerse en contacto con nosotros. 
Twitter @_dijane, @graphenoteam
Correo contacto@graphen.solutions

## Licencia

Shoppe está licenciado bajo "MIT license". Los detalles se encuentran en el repositorio
