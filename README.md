# Challenge iOS

## Readme 

- Se necesita crear una aplicación que permita buscar, subir, listar imágenes de Imgur.
- Se debe utilizar tanto `swift` como `objective-c`

### Pantalla Principal(TagsViewController)

- Al lanzar la app, esta debe buscar todos los tags y almacenarlos de manera local, para poder mostarlos si no se tuviera conexión.
- Debe permitir buscar Tags (filtrando en la tabla).
- Debe permitir deslizar y eliminar un tag, este no deberá ser mostrado nuevamente.
- La vista debe permitir pullToRefresh(UIRefreshControl) que solicita nuevamente la lista de tag.

    ![pantalla_principal.png](https://bitbucket.org/repo/Mrndnqd/images/2449792269-pantalla_principal.png)


### Lista de imágenes
- Al seleccionar un **tag** se deben consultar por cada [gallery](https://apidocs.imgur.com/#fbf4474f-5944-4535-80e8-c3219da0b643)
- Visualizar title, description,datetime del item de la gallery

    ![1175342338-lista_de_imágenes.png](https://bitbucket.org/repo/kgzajz/images/787070797-1175342338-lista_de_ima%CC%81genes.png)


### Pantalla de imagen

Al seleccionar una [gallery](https://apidocs.imgur.com/#0f89160b-8bb3-40c5-b17b-a02cc8a2f73d) se debe:

- Mostrar la imagen seleccionada
- Mostrar los upvotes, downvotes y views de la imagen
- Mostrar los [comentarios](https://apidocs.imgur.com/#b95843d0-0036-4486-8e64-152338f88872) de la imagen seleccionada

    ![pantalla_de_imagen.png](https://bitbucket.org/repo/Mrndnqd/images/3511127867-pantalla_de_imagen.png)

## Subir imagen

Tiene que cumplir con las siguientes requerimientos:
 
* Se tiene que poder subir una foto a Imgur seleccionando una imagen desde la galería de fotos del smartphone.
* Tiene que permitir sacar una foto con la cámara del smartphone

    ![subir_imagen.png](https://bitbucket.org/repo/Mrndnqd/images/4108103961-subir_imagen.png)

## Nota

* La aplicación debe ser "Responsive/Auto Layout" para soportar su visualizaciónn en *smartphones* y *tablets*.
* Funcionalidades extra suman puntos
* Uso de realm suma puntos
* Usar MVVM
* La aplicación debe incluir un archivo README.md explicando como instalar las dependencias del proyecto y todos los supuestos fueron considerados
* Para desarrollar la aplicación use como referencia la documentación de [Imgur](https://apidocs.imgur.com).