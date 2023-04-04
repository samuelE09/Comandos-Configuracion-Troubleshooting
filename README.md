# **Repositorio General de Comandos de Configuración y Troubleshooting**

Este repositorio busca ser la concentración de los diferentes Comandos usados para realizar las configuraciones y monitoreo/troubleshooting de los Equipos de Red de diferentes marcas.

Este repositorio tiene como visión principal llegar a ser una fuente de apoyo para los profesionales de Redes y Telecomunicaciones que laboran y trabajan en dicha área

<div align="center">
    <img src=""> 
</div>

**Tabla de Contenido**

|# Item | Marca - Equipo de Red          |
|------|:-------------------------------:|
| 01  |  [Cisco](./Cisco/README_CISCO.md)      |
| 02  |  [Fortinet](./Fortinet/README_FORTINET.md)|
| 03  |  [Huawei](./Huawei/README_HUAWEI.md)    |
| 04  |  [Mikrotik](./Mikrotik/README_MIKROTIK.md)|

 
# **Como Contribuir**


1. Si tienes conocimientos de **git** y tienes una cuenta de **Github** podrias seguir el proceso de colaboracion de un proyecto.

    > _**Nota:** [Pasos para Colaborar en un Proyecto](https://gist.github.com/BCasal/026e4c7f5c71418485c1)_

    **Formato de Contribucion**

    - Identifica el archivo `.md` donde vas a contribuir y agrega el contenido a modificar

    - Modifica el Titulo de la Configuracion

    - Modifica la Descripcion de la Configuración

    - Agrega la imagen a la carpeta correspondiente, el nombre debe estar en minuscula separada por guiones en formato png, el nombre debe referenciar de manera explicita a que configuracion se refiere, puedes guiarte de las que ya se encuentran agregadas.

    - Modifica el contenido de los comandos, recuerda que deben estar entre los simbolos
    

    ```
        # _**Titulo de la configuracion**_

        [<< Volver](#lista-de-configuraciones-en-equipos-de-red-cisco)

        Configuracion de un `Titulo de la configuracion` 

        <br>
        <div align="center">
            <img src="./img_carpeta/titulo_de_la_configuracion.png" width="300" >
        </div>
        <br>

        ```bash

        Aqui va la configuración
        Router(config)# ip access-list extended badgroup
        Router(config-ext-nacl)# deny tcp 172.16.4.0 0.0.0.255 any eq 23
        Router(config-ext-nacl)#  permit ip any any
        Router(config-ext-nacl)#  interface e0
        Router(config-if)# ip access-group badgruop out
        ```
    
    ```


2. Si no cuentas con conocimientos en git y no tienes una cuenta de GitHub, podrias colaborar y dar tu aporte a traves de nuestro Servidor de Discord, donde podrás enviar tu aporte en formato de mensaje

    > _**Nota:** [Unete a Nuestro Servidor de Discord](https://www.discord.com)_


# **Nuestros Colaboradores**

Forma parte de nuestra `Lista de Colaboradores`, en esta lista adjuntados el contacto de nuestros Colaboradores, profesionales en el Area de Redes y Telecomunicaciones `(LinkdIn, Twitter, Facebook o Instagram entre otros)`

**Lista de Colaboradores**

| Nombre | Nombre | Nombre | Nombre |
|--------|--------|--------|--------|
|[Samuel Berrú Alvarado](https://www.linkedin.com/in/sberrualvarado2496/)|nom2|nom3|nom4|