# HelpdeskZ

Versión: 2.0.2 del 9 de marzo de 2021
[Help Desk Software HelpDeskZ](https://www.helpdeskz.com/)

HelpDeskZ es un software gratuito basado en PHP que le permite administrar el soporte de su sitio con un sistema de tickets de soporte basado en la web. Tiene la capacidad de recibir y responder a los clientes cualquier duda o problemas de soporte con una interfaz fácil de usar y se pueden traducir fácilmente a cualquier idioma.

HelpDeskZ está desarrollado con CodeIgniter PHP framework 4, se publica bajo la [licencia pública general GNU](https://www.helpdeskz.com/license/gpl).

## Requisitos del servidor

* Se requiere PHP versión 7.2 o posterior

* Extensión intl , extensión mbstring y extensión imap instaladas.

* MySQL (5.1+) a través del controlador MySQLi

## Archivo de configuración

* Descomprima el paquete de script HelpDeskZ.

* Vaya al directorio / hdz / app / Config / y cambie el nombre del archivo Helpdesk.new.php a Helpdesk.php .

* Edite este archivo y complete la información requerida (URL del sitio, información de la base de datos, etc.).

## Instalación

1. Conéctese con FTP a la carpeta pública de su servidor.

2. Sube todo HelpDeskZ en el directorio en el que lo instalarás (directorio de dominio o subdominio).

3. Abra / instale en su navegador, por ejemplo http://support.mysite.com/install (modifique su URL).

4. Se ejecutará el script de instalación de HelpDeskZ. Haga clic en INSTALAR HELPDESKZ y siga las instrucciones a través del asistente de instalación.

5. ¡Ahora es el momento de configurar su mesa de ayuda! Abra el panel de personal en su navegador, por ejemplo: http://support.mysite.com/staff Utilice los detalles de inicio de sesión que ingresó en el proceso de instalación.

6. Todas las configuraciones disponibles en ese momento debería ser autoexplicativa.

Nota: ** Si desea realizar una nueva instalación nuevamente, asegúrese de eliminar el archivo /hdz/writable/cache/instal.config para desbloquear el asistente de instalación. **

# Actualización de la versión anterior
El proceso de actualización es muy simple y solo siga estos pasos:

## Archivo de configuración
Descomprima el paquete de script HelpDeskZ.

Vaya al directorio / hdz / app / Config / y cambie el nombre del archivo Helpdesk.new.php a Helpdesk.php .

Edite este archivo y complete la información requerida (URL del sitio, información de la base de datos, etc.).

## Actualiza tu sitio
Cargue todos los archivos de v2.x en su directorio HelpDeskZ.

Abra / instale en su navegador, por ejemplo http://support.mysite.com/install (modifique su URL).

Se ejecutará el script de instalación de HelpDeskZ. Haga clic en ACTUALIZAR HELPDESKZ y siga las instrucciones a través del asistente de actualización.

## Repositorios HelpDeskZ
HelpDeskZ es un proyecto de código abierto y el repositorio está alojado en [GitHub](https://github.com/helpdesk-z/helpdeskz-dev)

# Configuración

HelpDeskZ admite la canalización de correo electrónico, esto permite la creación automática de tickets de correos electrónicos entrantes a una dirección de correo electrónico establecida.

## Configuración de correo electrónico
En el Panel de personal, vaya a Configuración -> Direcciones de correo electrónico.

Agregue una nueva dirección de correo electrónico o edite el correo electrónico para la configuración de tuberías.

Vaya a la pestaña **Incomming** y seleccione **Pipe**

## Reenvío de correo electrónico
En su panel de alojamiento, vaya a reenvío de correo electrónico.

Ingrese la dirección de correo electrónico que configuró en su panel de personal.

Para el destino, seleccione Tubería

Ingrese la ruta a pipe.php, por ejemplo /public_html/helpdeskz/pipe.php

*(Para que funcione correctamente, verifique que pipe.php tenga permisos ejecutables (CHMOD 755))*

![1.Imágenes dentro del propio HelpdeskZ](HelpdeskZ/imagenes/1.png)
![2.Imágenes dentro del propio HelpdeskZ](HelpdeskZ/imagenes/2.png)
![3.Imágenes dentro del propio HelpdeskZ](HelpdeskZ/imagenes/3.png)
![4.Imágenes dentro del propio HelpdeskZ](HelpdeskZ/imagenes/4.png)



