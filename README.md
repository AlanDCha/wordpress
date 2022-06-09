# Subir una pagina Wordpress mediante Azure
### Requerimientos
- Tener una cuenta en Azure
- Tener dinero en Azure

---------------------------------------------
### Creando el recurso
Nos dirijimos a [portal.azure.com](https://portal.azure.com) e ingresamos con nuestra cuenta de Azure. Una vez dentro de la pagina ingresamos a Marketplace como se muestra en la siguiente imagen.
![Marketplace de Azure](https://github.com/AlanDCha/wordpress/blob/main/imgs/Marketplace.png)

Una vez que hacemos clic sobre el icono nos dirigirá al Marketplace. En la barra de búsqueda esciribimos **wordpress** y tecleamos la enter para que busque.
Una vez que nos arroje los resultados de nuestra búsqueda tendremos que hacer clic en el siguiente ícono.
![Búsqueda de Marketplace](https://github.com/AlanDCha/wordpress/blob/main/imgs/wordpress.png)

Nos dirigirá al complemento que seleccionamos y hacemos clic en el botón de crear
![Crear Wordpress](https://github.com/AlanDCha/wordpress/blob/main/imgs/crear.png)

Nos dirigirá a las configuraciones para crear el recuros. Recordemos que para crear un recuros en Azure debemos tener al menos estas 4 condiciones mínimas:
1. Nombre del recurso
2. Grupo de recurso
3. Región
4. Subscripción

Si no tenemos un grupo de recursos ahi mismo podemos crear uno como se muestra en la sigueinte imagen:
![Crear grupo de recursos](https://github.com/AlanDCha/wordpress/blob/main/imgs/grupo-recursos.png)

En el apartado de etiquetas podemos crear las que queramos ya que estan hechas con el fin de dar información acerca del recurso. Podemos poner algunas como las siguientes:
![Añadiendo etiquetas](https://github.com/AlanDCha/wordpress/blob/main/imgs/tags.png)

Finalmente, en el apartado de revisar y crear vemos que todo este bien; una vez revisado hacemos clic en el botón de crear.
![Revisar y crear el recurso](https://github.com/AlanDCha/wordpress/blob/main/imgs/reviscreate.png)

### Activar wordpress

Una vez creado el "recurso" nos dirigirá a esta parte como se muestra en la imagen siguiente:

![Recursos creados](https://github.com/AlanDCha/wordpress/blob/main/imgs/groupresources.png)

Como podemos observar, Azure nos ha creado 3 recursos pero el que más nos importa es donde el tipo *App Service*; hacemos clic sobre ese. Nos mandará a esta sección como se muestra en la imagen:

![Revisar y crear el recurso](https://github.com/AlanDCha/wordpress/blob/main/imgs/resource.png)

Hasta esta parte muchos dirán "Esta bien todo pero ¿dondé está mi página?". En la imagen de arriba podemos ver que en la pestaña de *Essentials* se encuentra un atributo llamado URL y en seguida vemos que hay un link. ¡Esa es nuestra pagina wordpress! Si hacemos clic sobre la URL nos abrirá otra página y tendrá el siguiente contenido.

![Idiomas en Wordpress](https://github.com/AlanDCha/wordpress/blob/main/imgs/idiomas.png)

Seleccionamos nuestro idioma preferido y hacemos clic en el botón de continuar. Nos cargará otra seccion como la siguiente:

![Idiomas en Wordpress](https://github.com/AlanDCha/wordpress/blob/main/imgs/forms.png)

Si somos nuevos usuarios en Wordpress llenamos todos los campos y hacemos clic en el botón de Instalar Wordpress. Nos mandará a esta última sección.

![Idiomas en Wordpress](https://github.com/AlanDCha/wordpress/blob/main/imgs/register.png)

Llenamos los campos y hacemos clic en el botón de acceder

![Idiomas en Wordpress](https://github.com/AlanDCha/wordpress/blob/main/imgs/homepage.png)

Con esto ¡ya tenemos nuestra primer página creada!
Podemos editarla cambiando nuestro enlace añadiento "/wp-admin" (sin las comillas dobles) y se abrirá la siguiente página

![Idiomas en Wordpress](https://github.com/AlanDCha/wordpress/blob/main/imgs/edit.png)