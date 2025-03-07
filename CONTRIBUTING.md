# Guía de contribución

[Si estás creando tu versión de un target](#target)

[Si estás modificanto algún elemento del proyecto](#project)


## Versión de un target

<a name="target"></a>
1. Haz un fork del repositorio desde la rama main
    - Dentro del repositorio, haz clic en el botón de "Fork" en la esquina superior derecha.

2. Clona el repositorio y crea una nueva rama, siguiendo la siguinte nomenclatura:
    - target/'id'-'tu nombre de usuario en github'
id es el número identificador del target que has recreado, por ejemplo, el calendario de Github tiene el número 01. Puedes ver este número en el nombre de la propia carpeta del target.

    ```
    git clone https://github.com/kasimxo/KaS-RecreandoComponentes.git
    cd KaS-RecreandoComponentes
    git checkout -b 'id'-'tu nombre de usuario en github'
    ```

3. Crea tu propia versión del target dentro del directorio targets:
    - Crea un directorio con tu nombre de usuario de github dentro de target, en el que incluirás todo tu código.

4. Cuando termines tu componente asegurate de hacer un commit & push:
    ```
    git add .
    git commit -m "target: 'id'-'tu nombre de usuario en github'"
    git push origin 'id'-'tu nombre de usuario en github'
    ```

5. Abre una Pull Request desde Github
    - Asegurate de que al hacer la Pull Request estás apuntando a la rama <b>developer</b>

> [!WARNING]
>
> Si en tu Pull Request aparece código o archivos modificados fuera del directorio:
> src/targets/'tu target'/'tu nombre de usuario en github'
> es muy posible que se soliciten cambios o no sea aceptada

## Modificación del proyecto

<a name="project"></a>
En primer lugar, ¡gracias por tu interés en el proyecto!

Aunque en un principio <b>no</b> se aceptarán modificaciones al código del proyecto base, es posible que hayas detectado una carencia en el mismo o que creas que puedes mejorar la implementación de algo. En ese caso, en primer lugar se deberá crear un issue, en el que se estableceran las modificaciones a realizar.

No se garantiza que tu Pull Request sea aceptada o respondida si trata de modificar el proyecto.
