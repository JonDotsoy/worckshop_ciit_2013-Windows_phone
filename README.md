worckshop_ciit_2013-Windows_phone
=================================
Clases del worckshop

El desarrollo de windows phone utiliza la interfas de usuario escrito en XML. toda la interfaz del usuario es de forma panoramica de tal modo que el usuario posee una vista completa de toda la plaicacion hjorisontalmente. Esta interfaz no delimita la pantalla si no que el usuario tiene la opcion de seguir leyendo o posicionar la vista en el sector de la aplicacion que mas le acomode.

## Gestor de evnetos.
el evento es rpgoramado en un cs escrito en lenguaje "C#".

### Metodo MessageBox.Show.
Este metodo envia mensajes al usuario, utiliza un metodo estatico.
```
MessageBox.Show("Hola Mundo!!");
```
> Reference: (http://windowsphone.interoperabilitybridges.com/media/130113/Windows-Live-Writer_41ed3c16a143_6B0D_clip_image008_thumb_2.png)

### TextBox.Text.toString()

Este metodo recupera el texto que posee el objeto TextBox
Elemplo:
```
String nombre = TextBox.Text.toString();
```

## Objetos
### Atributos
#### _Name_
Es el elemento unico que posee cada ojeto
### TextBox
Este objeto permite que el usuario ingrese un texto, en html es ``` <input type="text"> ```
###
