---
layout: default
title: Tu web de clasificados en 3 pasos
---

OSClass es un software para crear una web de clasificados en 3 sencillos pasos. 
Está desarrollada en PHP y MySQL bajo una licencia Affero GPLv3. 
Se pueden ampliar sus funcionalidades a través de plugins, así como también disponer de diferentes temas. Las características principales son:

* Multi-idioma, disponible en más de 20 idiomas: español, sueco, lituano, checo, árabe, griego, turco, etc.
* Panel de administración: edición de anuncios, categorías, e-mails, usuarios, etc.
* Creación de campos personalizados. Por ejemplo: Skype, tipo de vivienda, etc.
* SEO: urls semánticas, robots.txt (Hay un plugin de SEO avanzado en desarrollo)
* Los plugins permiten extender las funcionalidades del software: embed youtube, paypal para anuncios premium, google analytics, google maps, edición de texto enriquecido en la descripción, facebook connect, etc.

Para probar OSClass, puedes instalarlo en tu propia máquina. Pero si lo que quieres es publicar la web deberás disponer de alojamiento (ya sea de pago o gratuito). El primer paso es comprobar que el hosting cumpla los [requisitos necesarios](http://osclass.org/es/installation-requirements/):

* PHP >= 5.x
* Base de datos MySQL
* Módulo MySQLi para PHP
* Módulo GD para PHP

En caso de que los requisitos sean correctos, te aparecerá una pantalla similar a la siguiente:

![Requirements][requirements]

Para el siguiente paso será necesario disponer de una base de datos. Para ello, deberás utilizar alguna herramienta que te ofrezca tu proveedor: por ejemplo, phpMyAdmin. Una vez hayas creado la base de datos deberás apuntar algunos datos ya que serán impresincibles para crear la estructura de la base de datos: 

* Nombre de la base de datos que acabas de crear
* Usuario de acceso a la base de datos MySQL
* Clave de acceso a la base de datos MySQL
* Nombre del host (te lo facilita el proveedor)

Con estos datos, ya podemos rellenar los datos necesarios en el primer paso de la instalación.

![Step 1][step_1]

Una vez creada la estructura de base de datos se rellenarán unos campos necesarios para acceder al panel de administración, enviar los datos de acceso e instalar las regiones y ciudades de la localización escogida.

![Step 2][step_2]

Por último, antes de finalizar la instalación puedes escoger unas categorías predefinidas. Si no te gusta, siempre puedes añadirlas o modificarlas más tarde a través del panel de administración. 

![Step 3][step_3]

Felicidades! Ya has finalizado la instalación.

[requirements]: http://osclass.github.com/img/tutorial/requirements.png
[step_1]: http://osclass.github.com/img/tutorial/step1.png
[step_2]: http://osclass.github.com/img/tutorial/step2.png
[step_3]: http://osclass.github.com/img/tutorial/step3.png
[finish]: http://osclass.github.com/img/tutorial/finish.png
