# Introducción

PostComm es un smart contract escrito bajo el protocolo NEAR que permite:

* Crear un perfil de empresa o usuario. 
* Navegar entre las diferentes campañas.
* Seleccionar y compartir una de ellas en redes sociales o página web.
* Obtener ganancias en NEAR compartiendo el contenido.
* Verificar a la empresa como confiable.
* Editar u eliminar una publicación o campaña publicitaria completa (solo los   creadores de esta podrán hacerlo).



# Requisitos

- Tener instalado en su dispositio Node.js

- Instalar yarn:

  > npm install -g yarn

- Instalar dependencias: yarn install

- Crear un test near account [WALLET.TESTNET](https://wallet.testnet.near.org/)

- Instalar el NEAR CLI global para interactuar directamente con los comandos correspondientes a NEAR blo

  > ```
  > npm install -g near-cli
  > ```

# Instalación Local 

## Paso 1

Ya que hayas creado tu cuenta en NEAR testnet, te iras a la near cli y comprueba que haya sido creada correctamente:

> ```
> near login
> ```

### Paso 2

Clonar repositorio, en tu Bash de GIT pega el siguiente código para que permita tener el proyecto en tu dispositivo:

> git clone https://github.com/WConanSantacruz/NEAR-PostComm.git 

Enseguida utiliza el siguiente comando para que se ejecuten todos los comandos dentro del repositorio:

> cd postcomm

Los comandos que requerirás para poder desplegarla serán los siguientes:

> * npm init //crea un package.json 
>
> * yarn install //instalar dependencia yarn
>
> - yarn add -O near-sdk-as //coleccion de paquetes de near para desarrollo
>
> - mkdir assembly    //crear un directorio de lenguaje assemblyscript
>
> - touch asconfig.json   //se agrega asconfig al cliente
>
> * yarn asb // create a release build and place it
>
> * yarn asb --wat //herramienta de yarn asb
>
> * yarn asp --init //creacion de pruebas de asp
>
> * yarn install --global near-cli //intalar el cliente de near de forma global
>
> * yarn global ad near-cli //agregar un cliente de near al proyecto
>
> * yarn asp --verbose // test de pruebas
>
> * yarn --frozen-lockfile 
>
> * near login //log de una cuenta near




# Mockup de la aplicación

Para ver como quedaría el diseño de la aplicación da click en el siguiente enlace:

https://drive.google.com/drive/folders/1nskJvZ2Vhd6tEnB_Xa8ltLyesgO3A2_i?usp=sharing
