# Proyecto primer año DAM/DAW a distancia para institutos Nebrija

De momento el repo esta exclusivamente para poder trabajar en ello en multiples ordenadores. La idea es que este README.md pase a contener toda la informacion necesaria solicitada para el proyecto.

## Alcance
Esta web proyecto se compondra de una vista web, donde un usuario va a poder navegar por la tienda, conectarse, y agregar chuches al carrito, para su posterior compra.
De la misma forma, el administrador del pequeño comercio podra conectarse para gestionar la web. Tendra que poseer una serie de habilidades basicas:

  - Administrador (previo logeo)
    - Agregar un producto nuevo
    - Modificar un producto ya existente
    - Descatalogar un producto
    - Eliminar un producto
    - Cambiar la visibilidad de un producto
  - Usuario (previo logeo)
    -   Agregar chuches al carrito
    -   Eliminar chuches del carrito
    -   Modificar cantidad de un producto del carrito
    -   Agregar datos de envio
    -   Modificar datos de envio
    -   Eliminar datos de envio
    -   Enviar a una pasarela para el pago del producto (sera dummy porque eso entra dentro del uso de API's externas, competencias de segundo)
    -   Ver listado de pedidos y sus detalles
  - Anonimo (sin logeo)
    - Solamente acceso a la vista basica de la web

## Tecnologias

Debido a ser un proyecto de primer año, esta limitado el uso de tecnologias al uso de componentes "vanilla": Nada de frameworks, nada de extras, ni mucho menos. 
Para el front end, se usara HTML, CSS y JS basico, el backed se puede usar o Java (Tomcat) o PHP, y se ha de usar una base de datos relacional para el almacenamiento de datos (MYSQL/MariaDB).
Ademas se debera montar un servidorpara el alojamiento de esta web, y, si no he entendido mal, eso es competencia de una maquina virtual usando VirtualBox, y usando XAMPP si no he entendido mal.
Entiendo que esta permitido instalar el server en la propia distro y montar todo el tinglado ahi dentro.

## Documentacion

El proyecto ha de ir acompañado de una memoria, la cual incluye toda la informacion relacionada con el proyecto. Entre otras cosas, ha de incluir:

  - Diagrama de clases
  - Diagrama de entidad-relacion
  - Diagrama de comportamiento
  - Diagrama de flujo
  - Explicacion de las clases mas importantes
  - Como se relacionan las diversas partes entre si
  - Explicacion de como pasar de este repo de Github a tener el proyecto funcionando (como instalarlo, vaya)

> [!TIP]
> Cositas que puedo usar para todos estos diagramas: Lucidchart, comprobar si va bien para facilitarme la creacion de los diagramas en la version gratuita y hacer P2W.

La memoria debe de tener unas 50 paginas o cosa asi, igual que la memoria que hice para el proyecto de grado superior Programacion de la produccion en fabricacion mecanica.
No estoy muy seguo que ha de incluir el anexo. A mi entender deberia incluir cosas como los diagramas ya comentados. Pero, considerando que es un proyecto relativamente sencillo, 
deberia poderse incluir dentro de la memoria para ser comentado en el mismo sitio.

## Hitos entregables

Se debera entregar:

  - Una memoria, con su anexo la cual explique el proyecto aqui acometido.
  - El codigo fuente de la aplicacion, disponible en un repositorio git, ya sea Github u otro repo
  - Como bonus, enlace a la apicacion web subida a servidor de manera funcional

## Acciones generales requeridas

  - [ ] Escritura de frontend
    - [ ] Header & Footer
    - [ ] Pagina principal con 6 featured items
    - [ ] Listado del catalogo de productos
    - [ ] Pagina de registro
    - [ ] Pagina de login
    - [ ] Pagina de carrito
    - [ ] Pagina de compra (direccion y pago)
    - [ ] Pagina de administracion
    - [ ] Estilizacion con CSS
    - [ ] Dinamismo con JS
  - [ ] Escritura de backend
    - [ ] Tomcat servlet endpoints
      - [ ] Registro de usuario
      - [ ] Login/logout de usuario
      - [ ] Gestion de carrito
      - [ ] Realizacion de compra
      - [ ] Listar items
      - [ ] Agregar item
      - [ ] Modificar item
      - [ ] Eliminar item
      - [ ] Listado de los featured items
      - [ ] Listado de todos los productos
    - [ ] Base de datos
      - [ ] Tabla de usuarios
      - [ ] Tabla de productos
      - [ ] Tabla de pedidos
  - [ ] Servidor
    - [ ] Instalacion en maquina virtual de una distribucion de servidor (debian o alma linux como sustituto de centos)
    - [ ] Instalacion de Apache
    - [ ] Instalacion de Mysql/MariaDB
    - [ ] Instalacion de Java
    - [ ] Instalacion de Tomcat
    - [ ] Instalacion tanto del frontend como del backend
  - [ ] Memoria
    - [ ] Proposito del proyecto
    - [ ] Caso de uso
    - [ ] Tecnologias usadas y porque de dicha eleccion
    - [ ] Diagrama de flujo
    - [ ] Diagrama de clases
    - [ ] Base de datos
    - [ ] Diagrama de entidad-relacion
    - [ ] Diagrama de comportamiento
       
> [!WARNING]
> Lo mas importante de todo esto es la memoria. De nada sirve tener una app 110% funcional si la memoria es pobre.

> [!IMPORTANT]
> Usa los ejemplos que se han colgado tanto en la plataforma como en internet para el esqueleto de la memoria. Las cabeceras de los puntos son parecidas, no tiene sentido reinventar la rueda

> [!NOTE]
> Evaluar el uso de Github issues para un segimiento mas minucioso de cada uno de los detalles de cada uno de los puntos.

## Revisiones

Este documento ira siendo revisado a medida que el proyecto avance, y se iran anotando en este documento dichos cambios.

 - V1.0: Documento inicial (24/02/2024)
