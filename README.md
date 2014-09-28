>> Contacto de referencia: jaim.acevedoc@gmail.com




worckshop_ciit_2013-Windows_phone
=================================
Clases del worckshop

El desarrollo de windows phone utiliza la interfaz de usuario escrito en XML. toda la interfaz del usuario es de forma panorámica de tal modo que el usuario posee una vista completa de toda la planificación horizontalmente. Esta interfaz no delimita la pantalla si no que el usuario tiene la opción de seguir leyendo o posicionar la vista en el sector de la aplicación que más le acomode.

## Gestor de vistas

las aplicaciones de windows phone pueden poseer múltiples interfaces escritas en XML. Estas ventanas se llaman: 
```
navigationservuce.navigate(new uri("ventana.xml"))
```

## Gestor deeventoss.
el evento es programado en un cs escrito en lenguaje "C#".

###Método MessageBox.Show.
Este método envía mensajes al usuario, utiliza un método estático.
```
MessageBox.Show("Hola Mundo!!");
```
> Reference: (http://windowsphone.interoperabilitybridges.com/media/130113/Windows-Live-Writer_41ed3c16a143_6B0D_clip_image008_thumb_2.png)

### TextBox.Text.toString()

Este método recupera el texto que posee el objeto TextBox
Ejemplo:
```
String nombre = TextBox.Text.toString();
```

## Objetos
### Atributos
#### _Name_
Es el elemento único que posee cada objeto
### TextBox
Este objeto permite que el usuario ingrese un texto, en html es ``` <input type="text"> ```
###


