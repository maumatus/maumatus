### Hola, soy Maumatus 👋

<!--
**maumatus/maumatus** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

He trabajado varios años en Desarrollo de postproducción y Motion Graphics en video/imagen para Publicidad/Educativos. Ante la necesidad de tener mas herramientas comencé a aprender programación. Dentro del tiempo que llevo desarrollando, si bien manejo lo básico y entiende bien FrontEnd esencial (HTML+CSS+JS) me he enfocado en desarrollo de Backend y Sistemas. Esto porque las herramientas necesitan de la potencia del servidor o el sistema de resolver el problema. Un contrasentido viniendo de área visual en la que soy Senior, pero creo que este enfoque me ha sido mas útil. Si bien manejo NodeJS y ExpressJS, aprendo un poco de Python por facilidad de crear Scripts pero me estoy enfocando en aprender RUST, los lenguajes de bajo nivel permiten crear herramientas más útiles para el área en la que me enfoco. También experimento un poco con codificación creativa y creo puede reemplazar en parte a las herramientas existentes para motion graphics como los son After Effects y actualmente Cavalier.

- 🔭 Actualmente desarrollo un par de proyectos mientras sigo trabajando como realizador Motion Graphics:

1. Video-Repair app: Es una app en NodeJS que funciona en local. Presenta alternativas para solucionar un problema que tuve hace años como Postproductor de video para una serie de CNTV infantil, eliminar ruido electrónico de video. Me explio, todo sensor de camara digital foto o video 
genera ruido electronico, esto es imperceptible en condiciones de buena luz (sensor funcionando dentro de parametros normales por su tecnología y
determinado por su fabricante), pero el problema comienza cuando extremamos esas condiciones, por ejemplo: hay que grabar al atardecer o casi de noche. Ahí el sensor comienza a funcionar fuera de sus condiciones ideales (hardware y software noise reduction de camara) y se calienta, eso se transforma en pixeles de distintos colores debido a que todo el sistema genera errores que quedan en pixeles. Antiguamente en cine análogo, la película lo aceptaba y generaba granos mas grandes pero también mantenía los negros puros, de hecho se veía bien en cine negro y fue un estilo y géner de cine. En cine/audiovisual actualemente se ve muy mal.

Los programas de edición de video, compositores de video y color grading tienen modulos para eliminar ruido pero siempre es 1, a lo mucho 2 porque
suponen que grabación se hace con buenos estandares y condiciones, pero la realidad no es así. 

Asi que en corto una vez tuve que tratar de rescatar un material muy destruído por poca luz, pero no fue posible y mi herramienta no me dio más que una opción de solución, probe otra y pedía tanta ram que no funcionó. Finalmente hubo que grabar media jornada mas para solucionar, con los consigueintes problemas y mayor costo.

Pensé por años como solucionar eso, no hay un software que se enfoque solo en ruido electronico en video asi que rebuscando dí con Ffmpeg,
pero su problema es su sintaxis de uso por línea de comandos, lo que no es muy utilizable en producción de cine/audiovisual donde se necesita interfaz grafica (GUI), porque funciona en medio visual. Ante eso y luego de ganarme una de las becas de Talento Digital y aprender desarrollo JS Full Stack ví que en NodeJS se podía armar una app específica para solucionar este problema, tanto para mí como para otros, y así nace Video_Repair_app. 

Tiene la implementación de 6 algoritmos de Noise Reduction de Ffmpeg a partir de Modulo Fluent-Ffmpeg de NodeJS, despues de armar un Backend y hacer primeras pruebas me dio mejor resultado que After Effects para eliminar ruido, asi que seguí adelante. Actualmente falta el FrontEnd y la conexión con el back, que esta listo. Backend es simple, un Server que usa 6 modulos ES6 con parametros cargados por el mismo server luego de deserializar la data de frontend con las rutas de entrada y salida, y los valores numericos necesario para los los modulo de reducción de ruido.

2. Blender-Dragon
App web que convierte datos de animación desde Blender 3d al modulo ARCMotion de Dragonframe. Esto lo hice para darle utilidad y probar que mas puedo hacer con un cabezal robotico EMotimo TB-3, al cual le he dado poco uso, aunque tiene mucho potencial mas allá de Timelapses. Es un robot que permite animar stop motion y tiene un canal extra para moverlo a un slider robotizado. La app permite crear una producción virtual, o sea se anima dentro del expacio 3d de Blender y luego toda la data se convierte a espacio físico real y animar los elementos, asi se pueden mezclar elementos 3d con realidad sin tener que recurrit a Motion Tracking que tiene limitaciones. Actualmente trabajo para agregar un modulo de fondo virtual para stop motion a misma app, asi se puede ahorrar chroma key o generar un fondo con Unreal Engine, lo que permitiría generar un sistema de producción virtual completo, que puede funcional de forma descentralizada. Incluso se podría agregar streaming desde el feed de camara para visualización remota del trabajo. Todas estas implementaciones permitirían crear un sistema completo de producción virtual y visualización para un área en que no existe y aún hay un trabajo manual. Puede aportar a que no quede obsoleta o sea solo una tecnica de animación para artistas.

3. Web app Cangrejo-León
Aun en desarrollo una app CRUD para Librería/Editorial Cangrejo León. Todo el sistema se genera alrededor de una base de datos en postgreSQL de una biblioteca de libros (colección editorial), ademas de una base de datos de clientes. Todo esto conecta a la app en NodeJS y React (one page aplication). Lo que se agregará será mayor movimiento y desarrollo visual para diferenciarse de otras aplicaciones de negocios que son mas mínimas en este aspecto.
Ha sido dificil y se me ha complicado mas pero sigo aprendiendo y construyendo esta app.

4.Mi portafolio
App basica que aún no implemento, JS Vanilla y falta agregar CRUD basico de contacto y prospección de clientes.
Pretendía agregar gestión clientes pero falta tiempo y terminar proeyctos anteriores, aunque puede ser la primera porque es mas facil de implementar. Podría ser simplemente con render desde Servidor.


- 🌱 Actualmente sigo aprendiento JavaScript y dentro de este NodeJS, React, NodeSockets. Agrego un poco de Python 3+ pero solo a nivel de creación de scripts aun, tambien Bash Scripting y he iniciado Rust (que me encanta). Dentro de mi formación inicial aprendí PostgreSQL, con SQL que también me gusta, pero no he tenido tantos proyecto de practica.

- 👯 Estoy buscando colaborar en proyectos, o trabajo dependiente que me permita aprender. Si conecta con ñarea visual donde tengo mucha experiencia, mejor aún.

- 🤔 Si quieres implementar alguno de estos repositorios y no entiendes algo, contactame al correo.
- 📫 Mi contacto es: matusalen04@gmail.com, ese es mi correo para todos mis contactos.
- 😄
- ⚡ He hecho muchas cosas, tal vez un poco disperso pero hay tanto por aprender actualmente. Soy originario del Sur (Lago Ranco) y un ciclista desde hace 20+ años.

