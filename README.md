En primer lugar realizamos un fork y clonamos el reposiyorio 

Despues creamos una rama desde cero y le damos el nombre de solución y vamos haciendo paso por paso lo hace en las otras ramas

Para los strings idiomas tenemos que crear 2 strings en el directorio values 2 porque son dos idiomas los que vamos a añadir uno en Español y otro en Inglés y vamos al activity_main del layout y cambiamos en el apartado android:text y ponemos "@string/...y el nombre que le dimos"

Para poner las imagenes primero las descargamos de internet y las pegamos en el drawable y en la parte de MainActivity las declaramos y si son muy grandes en el apartado activity_main imageview le cambiamos a (android:layout_width="200dp /// android:layout_height="200dp") que es para darle el tamaqño que queramos a las imagenes

Para cambiar la funcion random buscamos una cualquiera en google y la ponemos en el apartado de (val randomInt = Random().nextInt(6) + 1) que se encuentra en el MainActivity 

Para cambiar la imagen del boton descargamos una de google y la pegamos en el apartado drawable y añadimos a la funcion del button que se encuentra en el activity_main  (app:icon="@drawable/baseline_favorite_24" ///// style="@style/Widget.MaterialComponents.Button.TextButton.Icon")
