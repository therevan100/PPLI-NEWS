# PPLI-NEWS
![cabeceradecanal](https://user-images.githubusercontent.com/79986286/113424145-eede6e00-93cf-11eb-9aba-705112fda4ef.jpg)

<h1>Web y aplicación móvil para Plataforma por el Periodismo Libre e Independiente (PPLI NEWS) </h1>

Visita la web www.pplinews.tk

Descripción del proyecto web
Landing page SPA (Single Page Application) en javascript puro programado en HTML5, CSS3/SASS con base de datos XML codificada en UTF8 y Hexadecimal.
Siendo un medio periodístico digital que necesita de contínua actualización, 'Plataforma por el Periodismo Libre e Independiente' utiliza una base de datos a la que accede haciendo uso de AJAX/Javascript y decodificando hexadecimal a UTF8 debido a que incluye código HTML5 dentro del propio XML con el fin de integrar a la perfección ambos lenguajes de programación en un solo fichero de DB para la entradas de cada noticia. Todo esto se imprime en un formato totalmente Responsive, que puede adaptarse a todos los dispositivos. Incluye sonidos al hacer click en el menú y en los post, una sección de contenido 'relacionado' en caso de haberlo en la DB en relación a la noticia que está visualizando el usuario en ese momento que tenga asignada la misma categoría. Incluye Scroll view y tecnologías similares permitidas en los requisitos de la web. Está preparada para posteriores implementaciones de Backend en las que se admitirá uso de HTML5 para la publicación de contenido. Las seciones de la web contienen los ultimos post añadidos a la base de datos ordenados por id y agrupados por categoría. Se ha hecho uso de la API de Youtube, Spotify, Twitch y Telegram para añadir contenido multimedia alojado en estas plataformas. También incluye un Ticker en el que se muestran las últimas noticias y se puede hacer clic para acceder a la noticia. Incluye un botón para ponerse en contacto por mail al pie de página. Para cumplir con la legalidad incluye un aviso de uso de cookies que se muestra al usuario cada vez que entra hasta que clique aceptar, una vez las acepta guarda su preferencia y no vuelve a aparecer el mensaje.

Imágenes Página Web:

![WebAppDesktop5](https://user-images.githubusercontent.com/79986286/113147961-9e310e80-9231-11eb-9b7b-556a6881ede9.png)
![WebAppDesktop](https://user-images.githubusercontent.com/79986286/113147973-a12bff00-9231-11eb-8c0a-82e5329163e0.png)
![WebAppDesktop2](https://user-images.githubusercontent.com/79986286/113147982-a2f5c280-9231-11eb-8051-fbcc7afc1977.png)
![WebAppDesktop3](https://user-images.githubusercontent.com/79986286/113147987-a5f0b300-9231-11eb-8d88-fa1db0075da4.png)
![WebAppDesktop6](https://user-images.githubusercontent.com/79986286/113147990-a6894980-9231-11eb-9952-d649b5ff3962.png)
![WebAppDesktop4](https://user-images.githubusercontent.com/79986286/113148004-a8eba380-9231-11eb-8e63-1616a4487ccb.png)
![WebAppDesktop7](https://user-images.githubusercontent.com/79986286/113148007-a9843a00-9231-11eb-97b0-e3f2f0e76486.png)
![WebAppDesktop8](https://user-images.githubusercontent.com/79986286/113148010-aab56700-9231-11eb-8f32-631d7ca9de3b.png)

Vista Móvil:

<img src="https://user-images.githubusercontent.com/79986286/113148086-bef96400-9231-11eb-93e3-3d1921e97bbe.png" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113148095-c02a9100-9231-11eb-9925-d7026f3b21cc.png" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113148101-c15bbe00-9231-11eb-927a-2de487f3b4f8.png" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113148106-c28ceb00-9231-11eb-8314-858437543cdf.png" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113148113-c456ae80-9231-11eb-9818-4d228dbd854b.png" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113148129-c7ea3580-9231-11eb-828a-d52e7aa7933b.png" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113148134-c91b6280-9231-11eb-9de9-d69cd6b224e4.png" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113148137-ca4c8f80-9231-11eb-906d-d4254fccd450.png" width="auto" height="600px">



Descripción de la aplicación móvil (Android Nativo)
La aplicación inicia con un Splash Screeen en tiempo de carga con inicio de sesión/ registro con cuenta e-mail haciendo uso de Firebase DB, en la que existen 2 tipos de usuarios con distintos privilegios, uno con derecho de lectura/escritura en la DB (administrador) y otro con derecho a lectura (usuario) que puede ver las noticias que publica el administrador y configurar sus propios datos de perfil de usuario (imagen de perfil, nombre, email, contraseña, fecha de nacimiento, género etc en tiempo real) en el menú de configuración, así como guardar noticias publicadas en 'marcadores' para su posterior visualización (marcador en progreso). 

La aplicación estructura su interfaz por categorías de noticias ordenadas por fecha de creación y permite su búsqueda haciendo uso de una barra de búsqueda (barra de búsqueda en progreso). La apllicación incluye modo nocturno selecionable desde el panel lateral (modo nocturno en progreso) además de funciones adicionales como recuperar contraseña por correo a través de 'olvidé mi contraseña'. También incluye una sección de comentarios en cada noticia publicada en la que el usuario puede comentar. El usuario también puede optar por no establecer una imagen de perfil, por lo que para dicho caso todas las funciones comunes al usuario están establecidas con una imagen de perfil por defecto. Está programadama en JAVA en entorno Android Studio.

Imágenes Aplicación Móvil

<img src="https://user-images.githubusercontent.com/79986286/113598418-695ff580-963d-11eb-8ec5-b164a940864c.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598423-69f88c00-963d-11eb-9e32-5072e75ccd1f.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598424-6a912280-963d-11eb-9ddd-92b1d1161efc.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598425-6b29b900-963d-11eb-85ac-08c8c0943113.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598428-6b29b900-963d-11eb-8c5a-6c47c539ded5.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598432-6bc24f80-963d-11eb-821f-92dea7b00f24.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598434-6bc24f80-963d-11eb-89c2-3826aaece172.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598436-6c5ae600-963d-11eb-9436-86d89f7f9ab2.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598437-6c5ae600-963d-11eb-811f-0f31814599cb.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598439-6cf37c80-963d-11eb-9620-fbaf70c2141b.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598440-6d8c1300-963d-11eb-8154-19f5fadd835b.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598441-6d8c1300-963d-11eb-8129-bebdd92831aa.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598442-6e24a980-963d-11eb-81ef-a0a22948b3cb.jpg" width="auto" height="600px"><img src="https://user-images.githubusercontent.com/79986286/113598443-6ebd4000-963d-11eb-8440-9f71e375fc84.jpg" width="auto" height="600px">


Sobre la base de datos: La utilizada es Firebase Real Time Database y Firebase Storage para imágenes. Firebase utiliza un sistema .json para almacenar los datos.

Esta es la configuración actual de la base de datos:
<img src="https://user-images.githubusercontent.com/79986286/113621635-26f9e100-965c-11eb-99e7-1a8a11d1dfd1.png" width="auto" height="900px"><img src="https://user-images.githubusercontent.com/79986286/113621637-27927780-965c-11eb-86cc-20b914dd324c.png" width="auto" height="900px"><img src="https://user-images.githubusercontent.com/79986286/113621642-28c3a480-965c-11eb-8ab3-3ad575d6b208.png" width="auto" height="900px">

Estos son los datos de prueba introducidos en la Base de datos:
<img src="https://user-images.githubusercontent.com/79986286/113622127-d33bc780-965c-11eb-9799-96534911a785.png" width="auto" height="900px"><img src="https://user-images.githubusercontent.com/79986286/113622130-d3d45e00-965c-11eb-97f3-b1345344f264.png" width="auto" height="900px"><img src="https://user-images.githubusercontent.com/79986286/113622135-d5058b00-965c-11eb-9ca9-9f7d74d45377.png" width="auto" height="900px">

Debido a incorporación tardía al curso por cambio de centro, al uso de tecnologías distintas a las cursadas y a la adaptación del proyecto al de I.E.S. Campanillas así como diversos cambios en el planteamiento del proyecto por petición del tutor el proyecto comienza su desarrollo en Enero de 2021.

Histórico de avances actualizado:

11/01/2021 al 17/01/2021:

Creación de los ficheros y directorios básicos del proyecto web.

18/01/2021 al 24/01/2021:

Desarrollo de iconos y apartados gráficos del proyecto web así como la sección HTML y SASS/CSS

Bibliografía utilizada:

Udemy: 
Curso Sass/CSS

Youtube: 
Vídeos búsqueda: "cómo compilar Sass/Css en linux" y "... con Plugin en VSCode".

25/01/2021 al 31/01/2021:

Continúa el proyecto CSS e implementaciones Javascript añadiendo efectos visuales.

En esta fase ya se ha concluido la incorporación de todos los requerimientos del proyecto:
- Uso de grid Layout/Area Layout.
- Media Querys responsivos en distintos tamaños adaptados a todos los dispositivos.
- Menú móvil y menú ordenador.
- Footer funcionando con flex-box.
- Incorporación de sonidos en la navegación y otros elementos multimedia.

Bibliografía utilizada:

W3Schools.com - tutoriales Css.

1/02/2021 al 7/02/2021:

Implementación de AJAX con BBDD en XML usando codificación Hexadecimal/UTF-8
Correcta implementación de la búsqueda de rutas XML ordenadas por filtro.

Bibliografía utilizada:

Foro en stackoverflow.com preguntas de otros usuarios.
W3Schools.com tutoriales XML path entre otros.

8/02/2021 al 14/02/2021:

Resolución de problemas y testeo general del diseño y de todas las funcionalidades.

15/02/2021 al 21/02/2021:

Creación de ficheros de redireccionamiento 404 y htaccess, creación de dominio y puesta
a punto del servidor host donde se ha alojado la web www.pplinews.tk, además de las 
respectivas configuraciones en el CDN Cloudflare.

Se ha realizado un testeo completo de la web online.

22/02/2021 al 28/02/2021:

Diseño de la aplicación móvil, se ha creado el splash screen en tiempo de carga al inicio de sesión
Se ha implementado el inicio de sesión con e-mail y google y se ha creado la BBDD en Firebase.

1/03/2021 al 7/03/2021:

Menú de usuario e interfaz en construcción.

8/03/2021 al 14/03/2021:

Resolución de incompatibilidades en Android Studio con paquetes afectados y actualizaciones pendientes.

15/03/2021 al 21/03/2021:

En la App móvil las imágenes de los usuarios ahora se guardan en la BBDD de Firebase, nueva interfaz de usuario.
Queda finalizado el inicio de sesión de los usuarios y las configuraciones de gestión de cuentas en Firebase.

Bibliografía utilizada:

Stackoverflow:
https://es.stackoverflow.com/questions/411128/error-al-implementar-firebase-en-proyecto-android-studio

Android CodeLabs Developers:
https://developer.android.com/training/permissions/requesting

Firebase Studio Developers:
https://firebase.google.com/docs/auth/android/password-auth?hl=es
https://firebase.google.com/docs/storage/android/start?hl=es

Webs:
https://www.programcreek.com/ "com.google.firebase.auth.UserProfileChangeRequest"

22/03/2021 al 28/03/2021:

Funcionalidad e interfaz de la sección publicar noticias terminada. Sección de comentarios terminada.

Bibliografía utilizada:

Android Codelabs Developers
https://developer.android.com/guide/topics/ui/layout/recyclerview
https://developer.android.com/guide/navigation/navigation-getting-started?hl=es
https://developer.android.com/reference/com/google/android/material/navigation/NavigationView.OnNavigationItemSelectedListener

StackOverflow
https://stackoverflow.com/questions/34730938/onfragmentinteractionlistener
https://stackoverflow.com/questions/35583686/android-recyclerview-no-adapter-attached-skipping-layout

Youtube

https://www.youtube.com/watch?v=gGFvbvkZiMs&ab_channel=SimplifiedCoding

Librería de carga de imágenes:
https://github.com/bumptech/glide

29/03/2021 al 04/03/2021:

Apartados gráficos de la sección configuración del usuario, estilos visuales, funcionalidades: modificar contraseña, modificar e-mail, recuperar contraseña, modificar nombre, modificar fecha de nacimiento y seleccionar género terminadas.

Bibliografía utilizada:


https://developer.android.com/guide/topics/ui/layout/recyclerview

https://www.youtube.com/watch?v=gGFvbvkZiMs&ab_channel=SimplifiedCoding

https://firebase.google.com/docs/auth/android/manage-users?hl=es#java_1

https://firebase.google.com/docs/database/admin/retrieve-data



05/03/2021 al 05/03/2021:
Trabajando en el modo nocturno y el menú de configuración de la cuenta.


Archivos de proyecto encriptados para mayor seguridad. Para fines de evaluación solicite la contraseña: rsantiagoy.3ia@gmail.com.

Para cualquier duda o sugerencia: rsantiagoy.3ia@gmail.com, Slack, Telegram ó tlf: 620 859 904.
