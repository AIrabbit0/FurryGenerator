# FurryGenerator
Este cuaderno fue realizado con la finalidad de que pueden usar los modelos de stable Diffusion de una forma sencilla y práctica.
Las herramientas usadas en el cuaderno fueron basados de los repositorios de github de [camenduru](https://github.com/camenduru) y [nolanaatama](https://github.com/nolanaatama).
El cuaderno fue desarrollado por [AIrabbit0](https://github.com/AIrabbit0/FurryGenerator), para los usuarios del [grupo](https://www.facebook.com/groups/429481779336019) y la [pagina](https://www.facebook.com/profile.php?id=100086789162708) de Dibujos Furry Hechos por una IA.
Además el cuaderno se actualizará peridócamente, ya que ciertos componente pueden fallar al momento que se actualice el cuaderno, en dado caso se recomienda esperar o hacer una copia previa.

## **Antes de empezar**
El cuaderno se conforma de tres secciones o celdas:
* La primera celda permite descargar los archivos para el entorno de la interfaz web, además de descargar los modelos de imágenes generativas como los archivo LoRA.
* La segunda celda es una celda opcional y permite al usuario cargar archivos desde Google Drive al entorno.
* Y la tercera celda permite ejecutar el entorno desplegando la interfaz gráfica.

Si eres principiante se recomienda ejecutar las celdas número uno y número tres.

Los **modelos** son archivos que contiene la información para generar imágenes, es decir sin un modelo no se podría generar imágenes.

Este cuaderno proporciona varios modelos para generar imágenes, desde tipo anime hasta furry, selecciona el modelo de preferencia y comienza a jugar que imagen(es) vas a generar.

Nota: Cada modelo es distinto con diferentes estilos ya se por los data sets que utilizaron asi como la mejora entre versiones de un mismo modelo a otro. Como complemento algunos modelos pueden generar imágenes más opacas o sin colores vividos por lo que se recomienda usar un archivo **VAE**.
Para más información, recursos o consultas, visitar la wiki del cuaderno. [Aquí](https://github.com/AIrabbit0/FurryGenerator/wiki)

## **Instrucciones de la IA**

1. Seleccione su modelo **marcando** la casilla. _Recomendación 3 a 4 modelos, ya que se puede quedar si espacio en el disco del entorno_. Y si sabe usar LoRA selecciona el archivo de su preferencia. 
2. Presione el play (▶) y espere que se cargue los componentes para pasar a la siguiente casilla.
3. Una vez que los archivos se hayan descargado dirigirse a la ultima casilla (número tres), para desplegar el entorno. 
4. Presione el play (▶), en la celda de iniciar entorno, para que se ejecute y despliegue la WebUI.
![Ejemplo](https://dochub.com/rabbit0bot/275eAYrVo3JjjnMVzXnBNQ/link-png?dt=s7zS8X3s9xtfmqkXWcBD)
5. Al final mostrara tres enlaces, estos enlaces permiten desplegar la vista para usar la interfaz gráfica y pueda generar sus imágenes con más facilidad.
6. Selecciones cualquiera de los dos últimos enlaces para abrir la interfaz.
7. ¡Diviértase!

**Nota**: *Si hay un error de desconexión, detener y ejecutar la celda número tres otra vez.*

### Opcional cargar archivos desde Google Drive

La celda número dos es una celda opcional ya que permite subir archivos como modelos de entrenamientos, hypernets, embeddings/textual inversors y/o archivos lora, al entorno. Esto para una personalizacion de los usuarios más experimentados que quieran hacer uso de archivos personalizados de su autoría o que tengan alojados en su Google Drive; El proceso para subir estos archivos al entorno es el siguiente:

1.	Abra la carpeta de archivos de colab, que está en la barra lateral izquierda 📁
2.	Busque su carpeta Drive y despliegue las carpetas que están adentro.
3.	Marque el número de archivos que va a importar.
4.	Click derecho sobre el archivo a importar y copie la ruta junto con la extensión del archivo. Ejemplo: MyDrive/content/modelo.ckpt
5.	Seleccione que tipo de archivo es si es modelo, lora, hypernetwork, embedding. Esto para que el archivo se guarde en la carpeta correcta.
6.	Presione el play (▶) y espere que se cargue los componentes para pasar a la siguiente casilla.

Para una guia mas extensa visitar la wiki. [Aquí](https://github.com/AIrabbit0/FurryGenerator/wiki)

## Wiki
Para más información ir a la wiki, con guías sobre mas información de los modelos generativos, conceptos básicos, como usar las vistas o extensiones, personalizar el entorno, así como recursos y tutoriales de gente con experiencia. [Aquí](https://github.com/AIrabbit0/FurryGenerator/wiki)

## Stable Diffusion licencia.
https://huggingface.co/spaces/CompVis/stable-diffusion-license
