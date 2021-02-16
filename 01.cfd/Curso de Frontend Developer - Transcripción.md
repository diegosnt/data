# Curso de Frontend Developer - Transcripción 

## 1. Introducción al curso

### **Presentación y bienvenida al curso de Frontend Developer**

Hola, bienvenido y bienvenida a este curso de frente en Developer.
Mi nombre es Estefanía Aguilar.
Soy Genera telecomunicaciones de la Universidad de Medellín.
Aunque actualmente me desempeño como desarrolladora.
Esa fuerza me gusta mucho la ilustración.
Me encanta poder transmitir ideas y conceptos a través del dibujo.
En Medellín Soy organizador.
Hay una comunidad, llámame y quince veces es una comunidad en donde a través de charlas y talleres aprendemos sobre ese ese ese y conceptos de frente.
En general, también estoy en el equipo de organizador de Sí.
Ese descongelan vio en la primera conferencia de Sí es es en Colombia Estoy.
Muy feliz de poder te acompañar en este curso.
Vamos a aprender conceptos fundamentales sobre HTML sobre seis de ese arquitecturas.
Maquetación prospere procesadores, accesibilidad y bueno, vamos a llevar a cabo un proyecto que se llama Platzi Vídeo.
Así que déjame mostrarte.
Aquí tendremos nuestra pantalla.
Inicio de sesión.
Tendremos nuestro loco.
Vamos a aprender.
Asombre hará estas Kartika s Vamos a poder escribir textos.
Botones input en en la pantalla de registro también va a ser algo muy similar.
Vamos a tener input botones, Un Führer Ya vamos a ver qué es eso.
Y en la pantalla de La Vista General, tendremos un buscador.
Es una especie de de buscador de vídeos.
Tendremos estaba Rita y un carrusel donde nos va a mostrar los diferentes vídeos.
Tendremos un botoncito de play, un botoncito donde podemos añadir estos videos a nuestra lista.
Y bueno, esto es lo que vamos a aprender a lo largo del curso.
Espero te gusten.
Si es pronto, tienes alguna duda? Algún problema? Recuerda que tenemos una pantallita donde puedes describir todas tus dudas no solamente a mí, sino a tus compañeros.
Así que no siendo más vamos a comenzar con la primera clase de HTML y CSS..

### ¿Qué son y para qué nos sirven HTML y CSS?

Hola en esta clase vamos a aprender sobre HTM l sobresee CSI que son y para qué no sirve HTML es un lenguaje, pero no es un lenguaje de programación, es un lenguaje marcado.
Y justamente este lenguaje nos va a permitir estructurar todos nuestros sitios web.
Es decir, que nos va a dar como la forma o el esqueleto de todo lo que nosotros construya.
Ms Con este lenguaje.
Nosotros tenemos una, crean cantidad de elementos, tenemos etiquetas y gracias a sus elementos podemos construir ciertas cosas en el navegador, como por ejemplo botones, podemos construir imágenes, textos, entre otras cosas.
Vamos a ver un ejemplo Tenemos yo tu bien, yo tú en la parte superior tenemos una barrita de búsqueda en la parte izquierda tenemos un menú y justamente en la parte central son todos los vídeos que no recomienda.
Yum CTO Cuando nosotros le damos click derecho y leamos en inspector en inspeccionar, vamos a darnos cuenta de que aquí hay una gran cantidad de código cuando era pequeñita y de esto por error y bueno, pensé que me había tirado la página del computador.
Algo así, pero bueno, nada.
Esto es natural.
Y justamente este inspector nos va a servir muchísimo más adelante sea convertir como el nuestro mejor amigo.
Si nosotros le damos en esta flechita De acá vamos a inspeccionar aquí y nos vamos a dar cuenta que nos dice que es un input.
Un input es una etiqueta de HTML que justamente no sirve para poder realizar búsquedas.
En este caso, si le damos nuevamente en una de estos elementos, nos damos cuenta que este es una imagen.
También es una etiqueta de HTML que nos permite demostrar imagines.
Entonces, si nosotros los notamos, nos dimos cuenta que esto es una imagen por allá.
Hay un input para que hay un día.
Entonces HTML tiene una gran cantidad de elementos que nos permiten colocar diferentes cosas en el navegador.
Aquí tengo una referencia muy buena.
Esta documentación me gusta muchísimo.
Se llama html referéndums y aquí nos va a mostrar todos los elementos que podemos tener en htm.
L podemos tener las cosas que tienen por defecto.
Más adelante veremos de este en detalle.
No nos entremos, saca todavía centrémonos más en esta parte izquierda.
Vamos a ver que tenemos a que tenemos para convertir que es de pausa.
Tenemos por acá donde el tenemos por acá un H uno que es para colocar títulos.
En fin, tenemos una gran cantidad de elementos y con estos elementos, pues podemos construir todos nuestros sitios web Sin embargo, si nosotros miramos es el HTML solamente nos va a la estructura solamente nos va a dar un esqueleto si nosotros queremos que esa imagen que dimos ahorita Yum tu sea de cierto tamaño.
Eso no lo podemos hacer con HTML ya tenemos que hacer uso de otro lenguaje que es seis es y si escuchaste muy piense ese Ese también es un lenguaje para no es un lenguaje, me programación ni ha marcado.
Es un lenguaje de hojas de estilo Tags.
Cuando escuches que FS eso es un lenguaje.
Sí, sí lo es.
Con este de FCS podemos estilizar todas nuestras páginas web.
Es decir, que le podemos colocar colores.
Podemos colocar le diferentes textos tamaños.
Podemos hacer una gran cantidad de cosas.
Si retomamos, señor, tu vamos a ver que por aquí a bajito en el inspector.
Vamos a tener ese elemento que seleccionamos.
Lo tenemos aquí, pero ya con estas.
Con estas, digamos, las y con este código desde ese es Vamos a ver más adelante.
No quiero entrar en detalle ahorita, que son todas estas cosas y que ese estoy acá, pero quiero que veas que todo Estoy acaso en los estilos que le podemos aplicar a nuestra página o a todos nuestros elementos.
También tenemos una documentación muy buenas que se llama si ese de referencia y aquí también vamos a ver todos los elementos DFS.
Desde que podemos utilizar podemos alinear el texto en el centro podemos colocar animaciones que también lo vamos a ver en este curso podemos ver bordes, podemos DIR padrins, etcétera.
Buena de las cosas que más me gusta a mí como desarrolladora es entender que sucede por debajo.
Es decir, nosotros como desarrolladores escribimos nuestro código y vemos el resultado en el navegador.
Sin embargo, es transparente para nosotros todo lo que hace el navegador para poder entender ese código y poder pintarlo.
Este tipo de detalles son los que a nosotros nos hacen muy buenos desarrolladores y también si en algún momento tenemos algún error, podemos llegar a él un poco más fácil.
No Siento más, vamos a la siguiente clase y te voy a contar sobre don sobre si ese o y todo el proceso de renderizado en la web.

### DOM, CSSOM, Render Tree y el proceso de renderizado de la Web

Hola en esta clase.
Vamos a hablar de un concepto fundamental para nosotros como desarrolladores frontenis y es todo el proceso de renderizado en la web.
Para eso tendremos tres conceptos fundamentales El primero es Don que por sus siglas en inglés quiere decir Document Object Model Esto en palabras un poco más cotidianas quiere decir que nosotros como desarrolladores, al escribir el código HTML en el nave en el editor, lo vamos a pasar al navegador Y.
Ese navegador no entiende absolutamente nada de lo que nosotros escribimos en este en este editor.
Entonces lo que él tiene que hacer es transformar esas etiquetas y esos tags que nosotros hacemos ahí y pasarlos a unos objetos.
Por eso se llama Oddset Model, porque precisamente transforma eso en unos objetos que son entendibles para el navegador para que lo pueda pintar.
Entonces, cada vez que te hablen de Don quiere decir una transformación del código HTML que nosotros escribimos a objetos que son entendibles por el navegador.
Sin embargo, el don sigue siendo exactamente el mismo en la misma estructura que te escribes.
Es la misma que el navegador entiende.
Sin embargo, pues en otro proceso para que el para que lo pueda entender muchísimo más fácil El ciencias o es exactamente lo mismo, También es una representación de objetos por.
En este caso, ya no es de HTML, sino de ceses.
También coges de código y lo convierte en objetos que son entendibles para el el render Three es precisamente un árbol y este árbol lo que lo que es es el don y el Ciencias o en juntos para poder renderizar todo ese proceso que nosotros hemos hecho en el código.
Aquí vamos a ver un código HTML y le no te asustes y de pronto no conoces alguna de las etiquetas que están allí.
Más adelante lo vamos a ver Sin embargo, quiero que notemos que tenemos una etiqueta principal, que es HTML y que dentro de ella está el jefe y está el body Dentro del Voy.
Esto lo que nosotros vamos a hacer y qué vamos a pintar en el navegar en esta etiqueta? Voy nosotros.
Vamos a ver que tenemos un H, una que es justamente una etiqueta de apertura y una H uno que tiene un Slash, que es una etiqueta de cierre y dentro vamos a ver el contenido que en este caso es una la para el navegador.
Entonces esto es completamente desconocidos.
Nosotros más adelante vamos a entrar en más detalle para el navegador.
Por más de que le explicamos eso no le va.
No le va a funcionar porque no lo va a comprender.
El tiene que hacer unos pasos.
Estos son cinco pasos fundamentales para poder hacer esa transformación La primera son los gays en lo que hace es coger ese juego y lo transforma en Valls.
Es decir, que en este momento tendremos un montón de numeritos.
Y después de tener todos esos Waits, lo que va a hacer es transformar a unos caracteres dependiendo de esa codificación que nosotros le hemos dicho.
No sé si lo notaste, pero en este código HTML le primera etiqueta que dice Meta tiene un U T f ocho.
Ese Bute fe ocho es la codificación con la que nosotros estamos trabajando.
Es decir, que esto es tan importante porque le estamos diciendo al navegador codifica a ocho.
Entonces los caracteres son precisamente es la transformación de Waits en unos caracteres que nosotros ya le establecimos en el código a que codificación.
Luego el va a ser esa transformación de los caracteres.
En unos Doc ens Eso esto.
Pienso precisamente esos htm.
Le sus tags de del body del jefe del H uno que nosotros ya tenemos, pero a decir Bueno, este la etiqueta principal está en la que cierra.
Esa es la que ahora y así sucesivamente.
Es decir, que organizar todos esos baile y todo eso que él ya establece en caracteres, pero luego a transformar en unos elementos HTML.
Hay una especificación que la especificación y la documentación más importante, que es la el Add le un trece y allí están establecidas todas las etiquetas de HTML, que también lo vimos en la clase anterior.
Sin embargo Help a decir Bueno, estas cadenas caracteres corresponde al etiqueta HTM.
Le esta otra corresponde la etiqueta Voy y así sucesivamente.
Es decir, que el por dentro va a empezar a identificar a qué etiquetas de relación Luego de ya saber todo eso.
Quién va primero? Quien va después va a ser una transformación a los nodos.
Esos nodos son precisamente objetos y estos objetos son los que entiende.
Entonces ahí ya tenemos nos desde alcanzan a ver en en circulitos.
Esos son como los objetos, los tags, los elementos y justamente los que están de otra forma son el contenido, que es como una especie de cuadradito que dice Hola estrella, no es untar, sino que es el contenido de uno de esos de esos elementos.
Por eso está en, pues, como color y adicto.
De otra forma, luego Elton ya sería coger todos esos elementos y ponerlos en un árbol.
EFE árbol va a tender una estructura dependiendo de la organización que tengan el código, por ejemplo, Miren que la etiqueta principal era ht ml.
Por eso ella es la primera que va a estar ahí, en ese en ese árbol.
Y después se van a desprender dos etiquetas principales que son G y después está el voy y cada una se van a desprender.
Entonces justamente ese es el árbol de representación de HTM.
También conocidos como dos.
Así que aquí ya tenemos una representación mucho más amigable.
Porque no solamente tenemos el HTML, sino que tenemos el seis seis porque bueno, el HTML ya vimos que nos da la estructura, pero también es importante que tenga el CDS.
Es para que le de un poco más de vida nuestras aplicaciones y a nuestras páginas que construyan Sudo El, CDS o M.
Lo que va a hacer es esa transformación individual, pero esa transformación la tiene que pegar.
Digámoslo así, en este arbolito que nosotros ya construimos del don.
Entonces ya nos quedaría este árbol que tenemos aquí.
Todos tenemos el HTML principal y a cada una le va a empezar a asignar el seis desde que le corresponde.
Por eso es muy importante que nosotros tengamos cincuenta y presente todo el CD seis de que escribamos Si, no solamente escribir por escribir, sino también ser un poquito más conscientes de todo el proceso que tiene que hacer el navegador para acoger una etiqueta y pegarle este ceses y empezar a identificar cuales de cual y así sucesivamente.
Y este proceso siempre se muera un poquito.
Si nosotros empezamos a escribir eso, así como al Al Honka, posiblemente este proceso va a ser un poquitito más lento y nuestras aplicaciones se van a ver muy afectadas.
A eso nosotros le conocemos como per forman o rendimiento de la aplicación y bueno, en resumen, tenemos entonces estos cinco pasos El primero es el proceso de HTML y construye el don Después.
Tenemos el proceso del seis CDs para construir el sí es es Open.
Luego en lo que hace es juntar estos dos árboles y construye uno solo, que es el render Three y después lo que hace es ejecutar todo este render Three y pintar El final.
Pues ya sería como este proceso y de pintado final, desdecir ya lo que llega al usuario.
Estos cinco pases o de un fundamentales, posiblemente te lo lleves a encontrar más adelante o puede que no, pero para ti van a ser completamente nuevos y muy buenas para que los tengas en cuenta, para poder más adelante, como saber en qué está fallando de aplicación o de pronto que tú digas.
Bueno, mi aplicación está fallando un poquito en rendimiento que puede estar pasando.
De pronto estoy escribiendo muchos DFS.
Tengo muchas etiquetas que no corresponden de pronto a no sé, a la optimización, etcétera.
Estos cinco pasos son fundamentales para tu carrera como desarrollador o desarrolladora frante.
Es muy importante que con escasos dos términos de don si es eso, En y render Trillas super fundamental.
Así que bueno, te espero en la siguiente clase.
Vamos a hablar sobre HTML.
Aquí toda la anatomía.

## 2. Conceptos iniciales de HTML

### Anatomía de un Elemento HTML: Atributos, Anidamiento y Elementos vacíos

Hola en esta clase Vamos aprender sobre la anatomía de un elemento htm l vamos aprender sobre anidamiento sobre atributos y sobre elementos vacías.
Aquí vamos a vivir una etiqueta H uno.
Eso es.
Lo que nos quiere decir es que es un encabezado principal, el más principal de todos en HTML.
Nosotros podemos escribir diferentes títulos.
Va desde el H uno, H dos h tres h cuatro h cinco y H seis.
El H uno siempre va a ser el título principal y el H seis siempre va a ser que el título menos principal.
En este caso tenemos un H uno Como.
Puedes notar lo vamos a ver que un elemento html está compuesto por una etiqueta de apertura Es etiqueta apertura tiene que tener sí o sí el nombre del del elemento que en este caso H uno y va a estar envuelto en unos paréntesis angulares.
Aunque a mí me gusta decir le pico paréntesis, pero te lo puede decir como quieras.
Tiene que estar encerrado en estos dos paréntesis.
Luego va a seguir un contenido que en este caso hacer Hola.
Y después de esta el contenido vamos a tener la etiqueta de cierra esta etiqueta de cierre va a ser muy parecida a la etiqueta de apertura.
Sin embargo, en este caso vamos a tener un a ti que una home Slash Que indicando que este la etiqueta de cierre.
Esto es fundamental porque justamente en este proceso de renderizado en la web El navegador va a decir Bueno, tenemos una etiqueta apertura y dónde está la etiqueta de cierre? Entonces? Es muy importante que nosotros tengamos en cuenta ponerle esa barrita para indicarle que precisamente la etiqueta a terminar o el elemento a terminar, justamente la etiqueta de apertura, el contenido y la etiqueta de cierre nos forman el elemento htm.
Cuando hablamos de elemento es justamente todo ese conjunto.
Ahora vamos a entrar en un concepto muy importante, que son los atributos, justamente a quien H uno.
Vamos a tener un atributo que se llama clase Esta clase es súper importante porque con clase nosotros podemos darle como una identificador al elemento y con este identificador podemos en CFS decirle que estilos va a tener estos atributos.
Siempre van a ir en la etiqueta de apertura, no pueden ir ni en el contenido ni en la etiqueta de cierre.
Siempre van a tener que ir en esta etiqueta principal.
En la primer hito que hace es uno en los atributos también tenemos una cantidad de atributos diferentes favorita, vemos otros y este clase tiene que estar seguido de un igual después de este, igual justamente el atributo, el valor tiene que ir entre comillas.
Y este va a ser justamente el valor que va a tomarse ese ese para añadirle los estilos.
Esto ES entonces en la etiqueta apertura, el el atributo correspondiente.
Vamos a notar que, como vimos en la clase anterior, vamos a tener un código y que no solamente las etiquetas van una sequía en la otra, sino que hay etiquetas que están dentro de otras elementos que van dentro de otros.
Entonces vamos a mirar este este ejemplo Tenemos un turista no tuvo hélices como una lista de cosas que tenemos que hacer en este caso es inventado El título dicen Code es que o hacer hoy y abajo Tenemos una lista que está desordenada, por eso se llama o el porqué desorden, una lista desordenada y dentro vamos a tener esos ítems.
Entonces dentro tenemos leer media hora, reunirme con mi lider, hacer pruebas unitarias.
Crearon Pull Rick uez e ir al Mir Add Cómo podemos notarlo? Tanto el H uno que es el título principal Como huele, están dentro del voy y dentro de huele hay unos elementos que están también por dentro.
Es decir, que ya no hablamos de que eso está por dentro de de algo, sino que hablamos de anidamiento en HTML.
Tenemos que tener muy presente y muy en cuenta siempre este tema de anidamiento.
Esto es fundamental porque justamente esta es la base para que podamos construir aplicaciones muy bien y que justamente se nos render icen de la forma en que nosotros queramos Los elementos vacíos.
Uno de ellos es imagen.
Si yo quiero colocar una imagen, no necesita un contenido.
Sin embargo, necesita unos atributos especiales para poder renderizar o para poder pintar una imagen.
Uno de sus atributos importantes es shorts o ese erece que también tiene que estar seguido de un igual.
Y en tres comiditas tiene que ir la were le o el enlace en donde se encuentra.
Ubicada mi imagen seguido se encuentra otro tributo muy importante que se llama al.
Justamente este Aid es muy importante por si de pronto algo sucede con la imagen y no se puede renderizar el usuario.
Puede haber algo hay en el navegar, cierto.
Por ejemplo, en este caso es pop y PNG, pero yo no quiero que sea Puppy porque el usuario no va a saber que es Puppy.
Entonces le voy a colocar como otro indicador, que en este caso es mi mascota.
Entonces ya le estoy diciendo el usuario mira, como no puedes ver la imagen, te voy a decir que lo que se iba a pintar ahí era mi mascota.
Esto tambien sirve para personas que son ciegas y que tiene que utilizar Screen Ryders o lectores de pantalla.
Esos lectores de pantalla lo que van a hacer es leer justamente esta etiqueta al y le voy a decir al usuario que era lo que tiene que lo que lo que tenía que renderizar o, en este caso, pues mi mascota.
Bueno, en este cada hemos terminado el tema de elementos HTML y hay otro muy importante que es la estructura de un documento HTML.
Esto lo vamos a en la siguiente clase.

### Anatomía de un Documento HTML: DOCTYPE, html, head y body

Hola en esta clase vamos a hablar sobre la anatomía de un documento HT ml.
En clases anteriores vimos un ejemplo muy parecido al que estamos viendo.
Aquí tenemos un documento donde la etiqueta principal es htm l y dentro de ella está el etiquetaje y la etiqueta agobio Dentro de cada una.
Ellas también pueden existir otros elementos.
Sin embargo, es muy importante que nosotros tengamos en cuenta para que sirven esas etiquetas porque están ahí.
Así que vamos a verlo con más detenimiento en el editor de código.
En mi caso utilizo Visual Studio Code, pero tú puedes utilizar el editor de texto que prefieras.
Aquí voy a crear un archivo le hoy harén Yum Fall y automáticamente me crea un archivo con un título.
Sin embargo, no me crea una extensión htm l Esta extensión es muy importante para que le Víctor me entienda en qué lenguaje estoy trabajando, así que vamos a darle nuevamente en Fay y en seis Tags.
Aquí le voy a colocar cualquier cosa.
Le voy a colocar que hace uno y le voy a colocar un punto y seguido en la extensión que es htm el Con esto le vamos a dar guardar y listo.
Vamos a tener que tenemos la extensión HTML y que inmediatamente Estoy bonito nos cambió a unos paréntesis angulares, lo que quiere decir que ya estamos trabajando con HTML.
Aquí vamos a empezar a escribir nuestro código, así que voy a empezar a escribir HT ml y como puedes ver aquí tenemos una pequeña ayuda que es HTML dos punto cinco.
Me gusta muchísimo porque miren lo que sucede.
Vamos a darle aquí Clic y automáticamente me crea todo el documento de HTM.
L tenemos una etiqueta de apertura, el heavy Help odi.
Es decir, que no nos tenemos que preocupar por nada.
Solamente nos tenemos que preocupar por empezar a escribir nuestro código en la etiqueta agua.
Pero bueno, empecemos a ver esta un poquito y con más en detalle.
Doctor, nos asegura precisamente que el documento sea analizado de la misma manera en los diferentes navegadores.
Aquí tenemos una etiqueta htm.
L está la etiqueta principal que también es conocida como Ruth elemento donde es cada vez que de pronto escuchas por ahí es que la palabra Ruth Estamos hablando de la etiqueta htm Dentro de esta etiqueta HTML.
Tenemos el Head y el body es muy importante que nosotros sepamos quienes como en la mama y quién quiénes son como los hijos En este casa, la mamá sería HTML y los hijos serían Get para nosotros no presentar como hay dos inconvenientes de bueno quienes? La mamá, quienes son los hijos? Lo que hacemos como desarrolladores es Edit entar el código Init entrar es precisamente ese espacio que hay desde la etiqueta padre desde donde empieza Un espacio citó.
Y eso lo podemos hacer con Leti, Con el tabulador, por ejemplo, yo le hoy aquí borrar le puedo dar con la tecla Tags y ya me Edit enter, es decir, que me crea un espacio.
Citó ese espacio.
Citó Digamos que no tiene ninguna implicación visual en el navegador.
Sin embargo, nos ayuda nosotros que visualmente el código sea completamente organizado por defecto esta estos dos.
Bueno, te preguntaras que aquí porque no estará separado, pero justamente lo hacen así para que no sea como tan enredos y para que no sea de pronto un arbolito dentro de un árbol y Tags, sino que siempre los en así, aunque tú también lo puedes como separar en este caso.
Bueno, separemos lo para que sepamos que es de la etiqueta padre y que estas dos son le TIC las etiquetas, dijo.
Tenemos entonces del jefe Esto no tiene ninguna implicación visual dentro del navegador.
Sin embargo, es muy importante aquí tendremos la codificación en caracteres.
Este justamente incluye todos los caracteres en todos los idiomas humanos.
Y tenemos también otros.
Meta Esto ya depende, pues de cada uno depende de lo que usted le quieran colocar.
Si quieren que sea compatible, si quieren, etcétera.
Bueno, y aquí tenemos le etiqueta tacto es en estas dije Tags va a estar el título de nuestra aplicación.
Esto no se va a ver dentro del contenido del navegador, pero si se va a ver en la pestaña Rita cuando entremos al navegador, entonces le podemos dejar documento o tú le puedes colocar cualquier otro título que es es justamente en Voy bastar nuestro cuerpo de o el esqueleto de htm.
El si nosotros quisiéramos estilizar colocar estilos Lo podríamos hacer en un archivo independiente.
O también lo podemos hacer en nuestra estructura de HTML, en donde irían.
Pues debajo deje colocaría mos una etiqueta que se llama Stay Yo Lo puede escribir y le puedo colocar como auto completar le voy a colocar enter y el automáticamente me crea.
Es de etiquetas tal y a ir a Podría empezar a escribir mi Seis LS Sin embargo en en esta clase no lo vamos a ver.
Y a quién voy? Bueno, voy a colocar un encabezado principal.
Cuando yo hago eso es porque escribo el etiqueta y con la con la tecla Itata y el automáticamente pues me me crea el la etiquetan con la etiqueta.
Inició la etiqueta de final y realista para que yo pueda empezar a escribir el contenido dentro del Bueno, la voy a borrar.
Eso lo hago con Coman x A quien Mac Y aquí puedo colocarle Esta es mi primera etiqueta htm.
El esto.
Tú también puedes crear otras.
Puedes colocar un diez.
Puedes colocar un párrafo y puedes colocar aquí Estoy muy feliz de escribir este par.
Así que como te voy ha mostrado anteriormente, nosotros tenemos una documentación en HTML referencia Y tú puedes ahí ver todas las etiquetas.
Puedes utilizar la que más desee.
Después de utilizar tips párrafos puedes colocar Lynx listas, entre otras.
Ya tenemos nuestro cobijo.
Y justamente en este código escribimos un encabezado principal con una etiqueta H uno y se quedó de esa.
Utilizamos hundir y un p muy.
Seguramente estos eran completamente nuevas para ti porque no te preocupes, le vamos a ver un día es como una caja, imagínate que es una cajita.
Todos los elementos en HTML son una caja, pero este es especial porque se utiliza básicamente para En volver otros elementos o para crear caja, círculos, entre otros.
Y dentro de este Edit utilizamos una etiqueta P.
Este p indica que es un párrafo.
Es decir, si yo no quiero tener un encabezado principal un título, sino que simplemente quiero escribir un texto, lo escribo dentro de la etiqueta P.
Vamos a mirar esto como sería en el en el navegador Si volvemos Vamos a ver que en nuestro editor de código no hemos guardado.
Es muy importante esta bolita nos quiere decir que no hemos guardado.
Le vamos a dar con como han ense y hay automáticamente en Add cuarta y vamos a ir al navegar aquí vamos a abrir una personita y vamos a escribir la ruta en donde está nuestro nuestro archivo que acabamos de crear.
En mi caso, yo lo puse en texto, como describir de stop y dentro voy a colocar clase uno punto html aquí le voy a dar enter y debería haber lo que yo acabe de escribir en en el editor de texto vamos a ver que esta es mi primera etiqueta HTML Estoy Muy feliz de escribir este párrafo.
Vamos al clic derecho inspeccionar y a ver qué fue lo que lo que hicimos.
Miren que aquí el utiliza justamente esa estructura que nosotros describimos en el código tenemos el HTML, tenemos una cabecera y tenemos el body, que es justamente en donde escribimos nuestro cómico y está nuestra etiqueta H uno Tenemos nuestro vivir y tenemos nuestro para Como te puedes dar cuenta tenemos todos estos elementos y cuando le damos como joven o nos paramos como en sí mitades cada una Las etiquetas Él nos vamos el automáticamente como la relación el equivalente en el navegador.
Entonces me paro en H uno y como puedes ver, aquí tenemos como una especie de cajita por.
En este caso no es una caja, sino que es como una especie de rectángulo.
Asimismo, con el diez y dentro del diez de tendríamos un párrafo.
Si tu puedes ver aquí nos vamos a dar cuenta que tenemos unas márgenes como de color Naranjito y tenemos otro espacio que es de color azul y asimismo, aquí no no sale tampoco el color verde, pero en algún futuro lo vamos a poder tener en la parte de abajo.
Vamos a tener esto está que es un es un modelo de caja.
Este modelo de casa es muy importante y nos va a parecer por cada elemento que nosotros hagamos en el navegador.
Más adelante lo vamos a ver con detalle, pero es importante que lo tengamos en cuenta.
Ya creamos nuestro primer documento HTML.
Tú también puedes explorar con diferentes de etiquetas.
Nosotros en clases anteriores vimos una documentación que se llama HTML diferentes.
Tú puedes hacer uso de esa documentación para que puedas ver otras etiquetas.
No importa si no la hemos visto.
Utiliza la hice libre de hacer tu documento HTML.
Lo puedes colocar en la sección de comentarios y bueno, estaremos muy felices de ver.
Tu resulta.
Nos vemos en la siguiente clase.

### La importancia del código semántico

En esta clase, Vamos a hablar sobre el código semántico.
Es muy importante que como desarrolladores también tengamos en cuenta todo el significado que tiene o toda la implicación que tiene el escribir el código, no solamente a.
Bueno, eso funciona.
Eso pinta y ya, sino que también seamos conscientes de que lo que estamos haciendo realmente tenga un sentido en lo que en lo que estamos Cobián.
Por ejemplo, yo puedo escribir un texto en una etiqueta Adif y lo puedo guardar Lopo renderizar y me pinta el texto que escriben el Dir Sin embargo, pues eso no sería tan buena práctica porque existen etiquetas especializadas para colocar texo encabezados.
Entonces es muy bueno que nosotros tengamos en cuenta todas estas recomendaciones.
Sé que son demasiadas etiquetas HTML.
Sin embargo, es bueno que tengamos en cuenta y presentes las más importantes.
En la imagen.
Nosotros vamos a ver una estructura que tiene un Get Her tiene un artículo, tiene una etiqueta de navegación, Tiene un Führer.
Esto es muy importante para el navegador.
A eso nosotros le conocemos como semántica HTML es justamente darle un sentido y una estructura a eso que nosotros estamos haciendo.
No es solamente colocar Un día para todo o un en una etiqueta para todo.
Porque eso funciona.
Que básicamente, sí puede funcionar.
Pero es mejor que leemos el sentido adecuado cada una.
Esas etiquetas.
Vamos a ver en el código.
Cómo funcionaría esto? Aquí retomamos de nuestro ejemplo anterior.
Tenemos un H uno, un diez y un bar Cher.
Vamos a borrar todo eso y voy a colocar solamente una etiqueta diez dentro de esta vez voy a colocar Hola, mundo Feliz Vigo ya muerta aquí en el navegador.
Voy a volver a refrescar y voy a ver qué dice.
Hola, mundo feliz.
Seguramente te darás cuenta.
Bueno, pero entonces porque colocamos un H uno porque colocamos un pez y de toda forma més la mostrando un texto Pues bien.
La etiqueta dice casi que no sirve para todo.
Pero eso pues no sería tan ideal.
Por qué? Porque si yo llego como desarrolladora a comité, mi código puede ser muy entendible para mí.
Pero sí llegó otra persona.
Posiblemente no sea tan entendible, cierto? Va a empezar a leer.
Bueno, que quiso hacer esta persona que quiso hacer.
En cambio, si tenemos un un sentido a todas las etiquetas, utilizamos las etiquetas correspondientes.
Pues es más fácil si llega otro desarrollador a trabajar en nuestro proyecto y entender más fácil que es lo que hemos tratado nosotros de hacer.
Bueno, tenemos aquí este Edit.
Podemos colocar otro día y de la misma manera podemos renderizar, pues cualquier contenido Esto no sería entonces lo ideal.
Lo ideal sería colocar siempre una etiqueta Unger.
Cuando hablamos de Ger es una cabecera.
Esta cabecera, generalmente nosotros la vemos en las aplicaciones, en la parte superior y en Steger podemos colocar cualquier contenido.
Puede ser un lobo.
Puede ser una lista, una lista de elementos.
Aquí lo podemos colocar.
Vamos a hacer una lista ordenada en esta lista ordenada.
Vamos a colocar, inició.
Y también podemos colocar otras que dedica usuario, usuario, cuenta más fácil cuenta.
Vamos a guardar y vamos a darle click aca ya vamos a darnos cuenta que es una lista ordenada y aquí tenemos el G del Vamos a inspeccionar este elemento.
Vamos a darnos cuenta que este es un Eley Y también acabamos saber que esto está envuelto en un etiquetaje, que sería como el Papa Después de eso también podemos colocar otra etiqueta que sería una sección, es decir, que hace parte del contenido principal, pero no es ni mujer ni un título ni nada.
Simplemente es una sección.
Y en esta sección podemos colocar imágenes o podemos colocar también DivX Blog diez.
No son malos, son buenos Pero.
Es bueno que tengamos en cuenta también la importancia de la semántica Asimismo.
Hay otras etiquetas que quiero que veamos.
Por ejemplo, voy a borrar este pedacito y voy a colocar la etiqueta E M.
Y también voy a colocar la etiqueta y Estas dos.
Si yo escribo un texto, por ejemplo, Hola Y aquí también voy a colocar Hola, Vamos a guardar y al renderizar voy a ver que ambas son iguales.
Cierto.
Miren que acá yo tengo un M y Unix son etiquetas completamente diferentes, pero vemos que, aunque son diferentes, hacen exactamente lo mismo.
Cuál sería entonces la diferencia entre ambas La diferencia principal es que y nos coloca el texto Itálico y no más, Es decir que solamente se enfoca en la fuente o en el tipo de tipografía.
Sin embargo, E M ya se enfoca en el énfasis que nosotros le estamos dando esta palabra.
No sé si es pronto.
Ha leído en un libro que tenemos una letra así, pero de la nada no sale como una letra a la Diada.
Esa letra a la Diada quiere decir que estamos haciendo completo énfasis en esa palabra.
Tres Ahí radica precisamente el uso de la buena semántica con el solamente le estamos dando el tipo, pero acá ya estamos hablando de algo muy importante, que es el énfasis que le damos a las palabras, es decir, la importancia que le damos a las palabras.
Por eso es que es muy importante que tengamos en cuenta toda esa semántica Así.
Tenemos un Jewel, una sección y también podríamos tener un Führer.
Y en este Führer también podemos colocar como contactanos o algo por el estilo.
Lo guardamos y lo podemos ver acá claramente todo se nos ve negro, pero para eso tenemos una clase FCS en estas clases es LS vamos a aprender a estilizar documentos Textos imágenes, entre otras.
Pero antes de que veamos esta parte tan importante que me gusta muchísimo que es el CSS.
Tenemos que tener en cuenta y precedente el por qué es importante utilizar el código semántico.
Nosotros podemos ver nuestra web, podemos sentar, presionar botones, ver textos Sin embargo, hay personas que tienen una discapacidad visual.
Estas personas hacen uso de unos escribir Ryders o lectores de pantalla que les ayuda a entender toda la página Estos escribir un líder lo que hacen es leer todas las etiquetas y les va diciendo al usuario sí, es un título.
Si es una imagen, etcétera, va leyendo literalmente toda la página.
Es muy importante que nosotros tengamos en cuenta este código semántico y hacerlo de la mejor forma posible para que estas personas también puedan entender este código que nosotros estamos viendo de una forma también muy accesible.
Entonces esta es una de las partes más importantes.
Cuando hablamos de accesibilidad hablamos, no solamente que nosotros podamos ver una parte, una página bonita, sino que también otras personas lo pueden entender.
Este tema accesibilidad es tan importante que lo vamos a ver en un módulo más adelante, así que vamos a comenzar con la clase de de Woking y detección de errores.



### Tipos de errores en HTML, debugging y servicio de validación de etiquetas

Hola en esta clase vamos a hablar sobre errores de Bobby y validación de etiquetas.
Hemos trabajado ya con HTML y con algunas etiquetas.
Sin embargo, todo nos ha salido super bien y no hemos tenido errores.
Sin embargo, en el día a día nos vamos a encontrar con una gran cantidad de errores que claramente son normales.
No quiere decir que seamos males desarrolladores.
Eso siempre nos va a pasar htm.
L es un lenguaje como ya lo vimos, pero este lenguajes interpretado no es compilado.
Cómo lo del rostro? Como estaba El navegador Intérpretes htm l y por esta razón es como un poquito permitido que quiere decir que sea permisivo, que así tengamos errores en HTML.
El navegador nunca nos va a decir que tenemos errores Esto.
De cierta manera es bueno y a la vez es mal.
Al principio, cuando comenzó en la web, eso era super bueno porque no no nos enfocaba tanto en que la gente tuviera malos errores de sintaxis, sino que puede presentar su contenido fácilmente Así.
Tenemos dos errores en HTML o en en cualquier lenguaje, programación o cualquier el lenguaje mate marcado.
Esos son los errores sintácticos y los de errores lógicos.
Los errores sintácticos son errores que básicamente siempre nos van a pasar cuando nos equivocamos de pronto, al escribir, por ejemplo, en vez de escribir función, escribe escribí función sin la L.
Eso quiere decir que tuve un error de Tip al, pero ya no le decimos cerrar de Tip Add o, sino que es un error sintáctico.
Es decir, que se mete ya con el programa y con la estructura que tiene este programa.
Un error lógico ya es un error de este tipo, por ejemplo, tenemos un un botón y este botón nos tiene, que dirigirá Yum tú, Sin embargo, cuando le damos click no ir hija, yo tú, sino que se nos va a traer el El navegador ni el COI.
El editor de código nos va a decir que tenemos un error porque claramente está dirigiendo a algún lado.
Es eso? Son errores lógicos.
Ya no tienen que ver con la escritura el código, sino llamas con la lógica, pues del negocio.
Bueno, tenemos ahora una, un un tema muy importante que es el debut.
No nos tiene que dar miedo ver errores.
A mi me pasa muchísimo también, pero cuando estoy trabajando por ejemplo, en Uría habría que siempre me va a mandar un mensajito en rojo diciéndome que tuve un error, como les mencioné antes.
Htm.
L no tiene errores, no nos muestra la en la negador, que tenemos errores.
Vamos a hacerlo en código para que veamos bien de esto que les estoy mencionan aquí ya cree un archivo de HTML la la llame vemos punto html y lo que vamos a escribir es HTML dos punto cinco y enter aquí en el body.
Vamos a escribir un código y es de código.
Va a estar mal escrito.
Vamos a colocar H uno.
Ya sabemos que cuando le damos TAP en los autos completa, pero en este caso no vamos a dejar la etiqueta de cierre.
Vamos a colocar series favoritas y abajo.
Vamos a colocar una lista ordenada, como lo vimos en clases anteriores y vamos a borrar la etiqueta de finalizar Dentro de esa etiqueta de lista.
Vamos a colocar un elemento y intencionalmente vamos a quitar esa barrita de final.
Aquí vamos a colocar, por ejemplo, no se estrenó ayer Finish.
Y vamos a guardar, Vamos a ir al navegador.
Vamos a ver y oh, por Dios! Tenemos literalmente tenemos de esto.
Muy bien, O L.
Pues sacan uno cerró entonces él intencionalmente como que piensa que hay otro elemento que es este que nosotros tenemos acá de pronto visualmente, si nos damos cuenta que bueno, hay un error, porque solamente con lo que una serie.
Pero si nosotros inspección amos en el navegador y le vamos con esta flechita nos paramos aquí en H uno, en este H uno y vamos a ver qué bueno tienen a series a quienes dos le también tienes enter fins.
Pero como podemos ver el automáticamente corrige esos errores que nosotros tuvimos Tenemos el H uno.
Nosotros nunca le pusimos estado Harry Tags las ni terminamos la etiqueta Igualmente no, l tiene la y miren que también me cerró la primera y la otra, pues pensó que había otro elemento vacío.
Esto es un poco malo para nosotros.
Es como desarrolladores porque porque bueno, no nos están mostrando exactamente el error Como vimos escribimos un código en HTML mal Sin embargo, el inspector no lo mostró.
Su perdiéndolos corrigió que habíamos nosotros como desarrolladores para darnos cuenta de que tuvimos de dos de errores Seguramente en estas líneas de juegos que son tan pequeños es muy fácil deducir el error Sin embargo, si tenemos unas hojas muy grandes de HTML pues sería un poco complicado empezar a mirar línea por línea Así tenemos ahora un sistema de validación de etiquetas que lo creó la OLED tres precisamente pensando en este tipo de errores que ya tiene la web.
Vamos a mirar De qué se trata Aquí en mi código con lo que es Trens ger sin la N Vamos a cuarta RI Vamos a ver el nuevo resultado Mesa darle aquí ahora si ya se me corrigió y voy a ir aquí donde dice validadoras doble U tres Tú también puedes entrar a esta o Here le para mirar el mismo.
Lo mismo que tengo aquí en pantalla Nosotros en este validadoras podemos ingresar una Were le podemos subir un archivo o podemos colocar directamente el CO y CO en mi caso, pues vamos a colocar directamente este pequeño código.
Vamos a seleccionar lo todo y con comencé lo copio y aquí me voy a como el pueblo Luego.
Aquí tenemos un botoncito que no dice Checa Le vamos a dar a cabo y aquí, en la parte de abajo nos va a mostrar todos los errores que tuvimos, todas las advertencias, etcétera, Quizás al principio sea un poquito complejo entender todo los, los de errores Sin embargo, cuando vayamos cogiendo un poco más de experticia un poquito y con más de de experiencia en vamos a poder leer esto con un poco más de facilidad.
Aquí MÁS abajo están inglés Sin embargo, tú pues colocar una extensión de de traductor para que esto sea un poquitito más sencillo.
Y en el idioma de nosotros, en esta parte de aquí nos está diciendo que nos de Ramos etiquetas que el H uno no puede tener este hijo, que esto está no está cerrado, que ese elemento tampoco está cerrada.
Y ya con este sistema de validación de etiquetas puedo detectar exactamente cuáles fueron mis errores y cómo corregirlos.
Miren que aquí también me está diciendo mirate faltando CTO Tau y es precisamente porque colocamos esta fracción sin él Voy sin el jefe, sin etiqueta H htm.
L Entonces con esto ya podemos darnos cuenta cuáles son nuestros errores y asimismo ir al código y corregirlos.
En la siguiente clase.
Te voy a dejar una lectura con un reto Espero los realices y si tienes alguna duda o comentario, no dudes hacerlo en la sección de comentarios.
Nos vemos en la siguiente clase..



## 3.Conceptos iniciales de CSS


### Anatomía de una declaración CSS: Selectores, Propiedades y Valores

Hola.
Bienvenidos a un nuevo módulo.
Este tema me encanta muchísimo.
Vamos a hablar sobre ese Ese ese sobre cómo vamos a escribir estos estilos en nuestras hojas de htm? L Vamos a hablar de selectores.
Vamos a hablar de propiedades y de valores.
Nosotros en clases anteriores Trabajamos con HTML y nos dimos cuenta que al escribir ese código y ver el resultado en la pantalla, todos los elementos se nos posicionaban en la esquina superior izquierda.
Sin embargo, qué pasaría si nosotros no quisiéramos que dos elementos estuvieran ahi sino al lado derecho? En la esquina inferior izquierda.
Eso lo podemos hacer a través de seis meses.
Y también podemos colocarle un poquitito más de vida.
Por ejemplo, si creemos que nuestros parrafos sean de un color rojo, vamos a utilizar lo que vemos aquí Tenemos una P y tenemos unas llaves.
Esas llaves van a hacer la apertura de nuestras propias estas propiedades.
En este caso tenemos la del color.
Tenemos color dos puntos y el valor, que en este caso también es Red Asimismo podemos escribir otras propiedades y otros valores de se s Sí, pero vamos a comenzar con el código y así mismo, vamos a empezar a ver otros estilos.
Aquí cree otra, Otra archivo te llama.
Estáis punto html nuevamente escribimos html dos punto cinco y dentro del PO y vamos a empezar a escribir nuestro código en este caso, vamos a ver el resultado de colocar todos nuestros párrafos en rojo.
Le damos P y con la tecla tabulador vamos a escribir.
Hola, mundo feliz y abajo.
Vamos a colocar otro párrafo que sean Hola.
Hola, mundo.
Muy no Vamos a guardar y vamos a ver eso en el navegador Como.
Bien.
Vimos todos en la exposición, en la esquina superior izquierda.
Vamos a ver cómo hacemos para que justamente esto que nosotros acabamos de escribir se nos vea de color rojo debajo del etiquetaje.
Vamos a escribir otra etiqueta.
Qué sustancia le vamos a dar? Enter.
Vamos a darle un doble espacio.
Citó.
Vamos a dejar que vamos a hacer que aquí haya un espacio para colocar nuestros estilos.
Aquí vamos a empezar a colocar todos nuestros.
Es es si queremos escribir, si queremos hacer que todos nuestros parrafos sean rojos, vamos a colocar P.
Esto va indicar que va a seleccionar todos los párrafos.
Abrimos con llaves y dentro de estas llaves, vamos a describir nuestra propia que en este caso va a ser color y el valor desde color que en este caso y Red.
Vamos a guardar y vamos a actualizar aquí el navegador.
Vamos a ver que efectivamente todos nuestros párrafos están siendo escritos de Col coloreados de color Blog Sin embargo, qué pasaría si nosotros no creemos que todos los párrafos sean de color rojo? Qué pasaría si queremos que solamente sea la letra inicial o que sea el primer párrafo.
Para eso tenemos que ver un tema muy importante que es hablar bien de selectores de pseudo clases y deseo de elementos.
Eso lo vamos a ver en la siguiente clase..



### Tipos de selectores, pseudo-clases y pseudo-elementos

Hola en esta clase vamos a hablar sobre selectores sobre pseudo clases y sobre Saioud Elements.
En la clase anterior vimos que pudimos colorear todos nuestros párrafos de color rojo Sin embargo, qué pasaría si no queremos colorear los todos, sino que queremos colorear el primero o el último o simplemente uno en especial? Para eso tenemos otro tipo de selectores Uno de ellos es el selector universal que se escribe con un asterisco Cuando colocamos un este disco en nuestro archi rito ese ese ese.
Vamos a ver que se van a colorear o han aplicarse todas estas propiedades a todos nuestros elementos en HTML Si yo coloco esque asterisco y ahí con lo que una propiedad que sea color red todos mis tics que tengan algún texto, todos nuestros párrafos H uno H dos El que sea, se les va a aplicar este colar.
Ahora tenemos otros el lector que es el el selector de tipo esto es el lector de tipo es como el que utilizamos en la clase anterior, la P SSL en sus electores no son tan buenos y tan recomendables utilizarlos cuando estamos trabajando en aplicaciones grandes o con muchas hojas de estilo con muchos estilos porque Porque si yo utilizo P se me van a colorear todos los pequeño tenga en mi aplicación y muy seguramente no voy a querer es puede que en una pantalla quiera los p de color negro, pero en otra pantalla quiera los p de color verde, por ejemplo.
Entonces no es tan buen utilizar este tipo de de selectores.
Para eso llegan otros electores, que son los electores de clase.
Nosotros tenemos los elementos y como vimos también en clases anteriores, podemos colocar le atributos a estos elementos.
Uno de sus atributos es Clase Hay.
Le vamos a colocar una especie de identificador a nuestros elementos y con este identificador podemos trabajar lo en seis meses.
Por ejemplo, mi párrafo, el que escribí en la clase anterior.
Le puedo colocar Class título principal o un párrafo principal y ya con esta clase y la puedo trabajar en CSS y decirle que mi título principal va a tener un color rojo y así no se me van a colorear Absolutamente todos los padres Por último tenemos estos electores por aire Tampoco es aconsejable trabajar con hay, dice.
Más adelante les voy a hablar sobre especificidad y vamos a ver porque no es tan bueno y tan recomendable utilizar Idees.
El latinos va a aumentar la especificidad y después trabajar con esto Va a hacer un poquitito complicado.
No te preocupes y de pronto no entiende donas escuchado anteriormente en la palabra especificidad.
Eso lo vamos a ver más a él.
La pseudo clases.
Si nosotros queremos aplicar un estilo en especial.
Por ejemplo, el primer párrafo, el último párrafo de lo que hablamos al principio tenemos la pseudo classe que nos ganaron estilos pero específicos.
Por ejemplo, aquí tenemos el P.
Tenemos dos puntos y Finish Chai Eso qué quiere decir? Que el primer hijo que tenga P le voy a aplicar esas propiedades que están allá de El.
Segundo ejemplo Espe las chal.
Esto quiere decir que el último hijo que tenga P género se me van a aplicar esos estilos.
Y por último, tenemos otro que es n THE Charles mejor lo vamos a ver en el código para que veamos cómo funcionan estas pseudo classe Ahora.
Tenemos nuestro escribe anteriores que hicimos en la clase anterior.
Vamos a ahorrar.
Lo vamos a borrar también los estilos.
Y vamos a colocar un nuevo barra aquí tengo una lista de animales.
Utilice unos de Morris, pero tú también puedes utilizar en muchos.
Si de pronto utilizas Mac en la parte superior dice Edit.
Y aquí le puedes dar n Morris de salió una lista de Morris y pues seleccionar el que más te gusta, sino sino utilizas Mac.
Pues también hacer uso de este recurso que tengo acá, que se llama en Montjuic, invoca y te voy a dejar este enlace también para que lo puedas utilizar.
Solamente es copiar.
Dale click y luego vas al código y le das con Manuel.
Ella se te pegaría.
Es de mucho.
Voy a copiar Entonces estos animales que tengo acá voy a colocar otro párrafo.
Voy a copiar este que hice perro y también voy a copiar este que dice banco Sólo voy a ocupar estos estos tras.
Pero tú puedes colocar cuantos quieras En el estilo ya vamos a empezar a ver cómo funcionar que estas pseudo clases.
Voy a colocar P y solamente quiero ver mi conejo con el texto Conejo de color rosa.
Para eso le voy a colocar dos puntos y le escribo Fierce al Esto.
Quiere decir que el primero de todos esos P cmd a retirar con esos estilos que yo le ponga ahí, en este caso sería con los y en tu le puedes colocar también el color que seis vamos a guardar y acá vamos a refrescar.
Vamos a ver qué conejo solamente tiene ese color y que perviva acá siguen exactamente con los que tenían por defecto.
Si, por ejemplo, quiero que sea ahora Vaca, lo que voy a hacer es coger P dos puntos.
Le colocó las Chai, lo que quiere decir que va a coger el último de todos esos P y le voy a colocar otro color.
Vamos a colocar le no, voy a guardar y vamos a ver qué sucede.
Efectivamente, se nos colorea.
Vaca de color café.
Listo.
Esa casta super bien, pero bueno, también podemos jugar un poquito ICO con esta pseudo classe y podemos aplicar un poco de matemática.
No te abrume si de pronto no te gustan mucho las matemáticas, pero aquí va a ser super.
Es sencilla y superfácil, muy chevere.
Vamos a colocar acá B dos puntos y vamos a utilizar esa pseudo classe de que vimos también en el es light anterior, que es en el pH echar eso qué quiere decir? N es un número cualquiera, puede ser el cero el diez el veinte y TH hace alusión a los números ordinarios en inglés.
Si yo coloco, por ejemplo, en inglés fes Lo que hago es escribir uno en siete Si Voy a escribirse con escribo dos n.
Esto es normalmente en el lenguaje común y corriente.
Si empiezo con tres o el tercero sería tres D h y así sucesivamente con todos los todos los números ordinarios Asimismo sucede acá Todo el código que escribimos está en inglés y por esa razón TH así alusión a los números ordinarios.
Siendo así, vamos a colocar Todos los números pares.
Es decir, en este caso sería perro.
Y si tenemos otro elemento, vamos a colocarlo para que no nos quede perro solita mezzo colocar sap on le vamos a pegar aquí para que no quede solamente, Pero todos en ETH Chávez como sería entonces la ecuación matemática para colocar que solamente los elementos parece vamos a colocar n n siempre va a ser el numero empieza desde cero cero uno dos.
Para eso le voy a colocar dos donde dos por cero cero Después dos por uno, dos dos gordos Cuatro.
Así que este me va a dar todos los números que son.
Parece.
Vamos a ver.
Vamos a colocar le aquí color red y vamos a borrar o vamos a comentar esto que ya tenemos a cargo.
Vamos a guardar y vamos a ver qué sucedió.
Efectivamente, perro, quizá porque son los que son pares en este caso.
Uno, dos, tres y cuatro son los que se nos colorean de color rojo.
Ahora, para no dejar conejo Ibaka sin estilos.
Vamos a hacer lo mismo, pero con los impares vamos a escribir P, N, T, H echar igualmente.
Y ahora, como sería? Sería dos n.
Tenemos los números pares, pero para que sea impar le tenemos que sumar un uno Ya así, si nosotros nos ponemos a a tantear, a mirar.
Si n cero dos por cero cero más uno uno.
Ya estaríamos cogiendo el conejo con el siguiente número, que es uno dos por uno.
Dos más uno sería tres, tres.
Ya tenemos ahí conejo y vaca.
Vamos a colocar le color vio Igual mucha cuerda.
Vamos a refrescar y efectivamente lo que es Conejo y vaca.
Se nos van a colorear de color azul.
Esta es una de las cosas que más me gusta también dice ese ese poder interactuar, poder jugar con todos los colores, con las de estilos, con los elementos Retomando, aparte de los de la pseudo clases tenemos lo que son los seudo elementos.
Los aut elementos funcionan un poco similar a lo que son las pseudo clases Sin embargo, los seudo elementos se diferencian de la pseudo clases.
Primero, porque tienen otros dos públicos.
O sea, si colocamos P en el pH hecha y con dos puntos aquí vamos a colocar P dos puntos, dos puntos y vamos a colocar el pseudo elemento en pantalla.
Podemos ver uno de los de los EU de elementos.
En este caso tenemos vi for a Esos son muy usual, muy usados.
Comúnmente lo va a saber muchísimo en su esencia.
Bueno, también hay otras.
Vamos a mirar en el código.
A ver qué podemos decir con estos Edit de alimentos.
Aquí tenemos entonces nuestras euros.
Qué haces? Anteriores? Las vamos a ahorrar y ahora vamos a colocar P dos puntos, dos puntos para indicar que es un un pseudo elemento.
Colocamos la primera letra y dentro vamos a colocar los estilos que quiero que me aplica.
En este caso vamos a colocar le color red.
Y también vamos a colocar le otra nueva propiedad que sería Fons ais.
Vamos a aumentar.
Le también es de tamaño la primera ley la Vamos a cuarta HR y vamos a ver el resultado en el navegador Y muy bien.
No estamos viendo absolutamente nada en lo que hicimos Pero es precisamente por este monje que tenemos acá Mac, esto no lo toma como si fuera un texto, así que lo vamos a borrar.
Vamos a volver a guardar refresca Moss Y ahí si vemos que nuestra primera letra tiene el color rojo y tiene también la fuente Más grandecita.
También quiero mostrarte unas una documentación muy buena que es de M, de MN demos y la Aquí puedes ver todos los las euro claves que puedes utilizar Chile Add clic en alguna te va a mostrar también ejemplos Y así mismo, si vamos a los seudo elementos de esta misma documentación, te va a mostrar los posibles pseudo elementos que puedes utilizar.
Y si les das click, también puedes encontrar algunos ejemplos Es por esta clase te haya gustado muchísimo y nos vemos en la proxima.


### Modelo de caja

Hola en esta clase.
Vamos a hablar sobre el modelo de caja Valores relativos y valores absolutos.
Todos los elementos HTML tienen un modelo de K.
Este modelo, el Caja, está compuesto por cuatro elementos El.
Primero es el contenido.
Como podemos ver aquí.
El contenido es lo que está de color azul seguido.
Esta el padre, ese padre en esta entre el borde y el contenido seguido Help Add himba.
Entonces el borde y despues Delporte va el marcha.
Estos conceptos son muy importantes porque nos puede modificar todos los elementos que nosotros construyamos.
Vamos a mirar esto en código para ver lo más detalladamente para que lo podamos inspeccionar en el navegador.
Aquí tengo un archivo llamado Modelo Encaja.
Tú le puedes colocar el nombre que es es y vamos a tratar de inspeccionar con algunos elementos de HTML Tenemos hundir.
Vamos a Quart AR y vamos a refrescar nuestro navegador.
En este momento, claramente no vamos a ver nada.
Sin embargo, echábamos a tener este diez en el inspector de elementos.
A eso lo conocemos también.
Cómodo.
Este es el don.
Aquí tenemos en la parte de abajo un modelo de caja.
Este es el que representa este Edit.
Como podemos ver, no tiene ni marginen NI Border ni padre tiene una especie de contenido para este contenido.
No tiene absolutamente nada.
Luego vamos a ir a los estilos como vimos.
Vamos a colocar una etiqueta.
Esta ahí debajo de jefe Y aquí en esta ahi vamos a colocarle una clase.
Ya vimos esto de los electores.
Entonces vamos a colocar Caja.
Vamos a abrir llaves y a este Edit le vamos a colocar una clase con el nombre Caja aquí en los estilos Vamos a empezar a molestar un poquito.
Vamos a colocarle un ancho y un alto en CSS para colocarle un ante un ancho de un alto le colocamos cuidado.
Podemos colocar le veinte píxeles y le colocamos un High.
Esto indica que éste también es el alto.
Vamos a colocar le veinte píxeles Y si vamos al navegador no vamos a oír absolutamente nada todavía porque está en blanco el color por defecto para nosotros Les colocamos un Bagram Con Este va a Crouch.
Le podemos definir cualquier color que nosotros quedamos Tanto Este va a Brown como este Funcionan igual si tú puedes con los carpa grado o va a gran color pasión.
Exactamente lo mismo, pero es muy bueno que coloca con los que hemos Va a gran color como para decirle que efectivamente vamos a utilizar un color en este Bagram porque también podemos colocar otro tipo de cosas.
En Help, agrado Aquí Podemos colocar cualquier color.
Muchas veces cuando trabajamos no pasamos de los colores primarios, pero me quite tengo una página que me encanta.
Esta paginita te va a arrojar una cantidad de colores que ya combinarían entre sí.
Pero tú también puedes colocar aquí.
Bueno, quiero que me vote los amarillos o quiero que me muestre todos los que estén con naranja y así yo voy a colocar este solamente es darle clic y listo a quién va a gran color, donde le voy a colocar este valor y aquí no me funcionaría de tendría que colocar es de este numeral para que me funciona.
Vamos a aguardar y nuevamente el modelo de caja.
Vamos a refrescar y vamos a ver nuestro Edit con veinte píxeles y veinte píxels.
Miremos, que es que en el modelo de cajas ya nos está diciendo que tenemos un contenido con veinte píxeles y con veinte píxeles.
Sin embargo, seguimos sin tener absolutamente nada.
K Qué pasaría si le agregamos un padre? Vamos a ver qué sucede.
Vamos a colocar le padre, Vamos a colocar le también veinte píxeles.
Y qué crees tú? Qué piensas? Si tenemos un Huid de veinte píxeles, un Jay de veinte píxeles? Será que si le ponemos un Padín tendrá el mismo tamaño que nosotros le escribimos acá o se verá modificado, afectado? Vamos a mirar.
Qué sucede? Vamos, Aqu, hartar y miren que nuestras cajita se está viendo afectar.
Nosotros le habíamos puesto veinte píxeles de ancho, veinte píxeles de alto.
Sin embargo, no, No respetó lo que nosotros estábamos diciendo porque LOS padrins siempre nos van a afectar este modelo de caja.
Eso es una de las cosas que tenemos que tener siempre presentes aquí.
En el modelo de casa podemos ver que tenemos del contenido de veinte píxeles.
Sin embargo, el huir se va a empezar a sumar.
Mire que cuando yo le acojo ver home pasó por encima este contenido.
Vamos a ver que en el resultado a este lado sea empezar a formar una cajita de color azul.
Ahí me está mostrando el contenido.
Y cuando acojo ver encima de de padre.
Pues me va a mostrar el respectivo paguen que tiene aquí podemos ver que me está sumando los veinte píxeles más el contenido.
Esto siempre va a ser muy, muy, muy importante.
Vamos ahora colocarle un borde de nosotros podemos colocarle el borde de la siguiente forma.
Vamos a colocar le dos píxeles en el navegador siempre vamos a trabajar con píxeles.
Siempre el navegador tiene esto, pero también hay otras unidades que las vamos a ver ahorita Los pixeles.
Le vamos a colocar el tipo de borde que yo quiero.
En este caso va a ser sólido, es decir, que va a ser una línea uniforme y le vamos a colocar otros color.
Voy a venir aquí, a mi página y le voy a poner este Lo.
Copio y lo pegó con el numeral.
Le vamos a dar guardar, vamos a la página y re- Cargamos que sucedió mi Vim, que Kaká también nosotros le pusimos un borde y también se está viendo afectado nuestro de modelo de caja Acá.
Tenemos que ya no tenemos el Week de veinte píxeles que teníamos al principio, sino que tiene estos veinte más de estos dos.
Esto también es muy importante que lo tengamos.
Cincuenta.
Qué pasaría si yo no quiero que eso se vea afectado por Help Add? Y ni por el borde.
Nosotros podemos utilizar una propia que se llama Vox.
Hay sin Woods hay cine que me tiene que salir Vox hay Vim Border Vox.
Eso quiere decir que me voy a respetar el tamaño que yo le con lo que desde el principio Vamos aguardar y vamos a actualizar acá.
Como bien puedes ver nuestra cajita volvió a hacer del tamaño Kernel.
Esto es porque ya le decimos que respete lo que nosotros estábamos metiendo desde el principio.
Se lo vamos a quitar.
Vamos a aguardar y vamos a ver nuestras cajita través grandes.
Un Mardin siempre nos va a funcionar cuando tengamos otros elementos a los lados.
No sé si de pronto te estarás preguntando qué significa este espacio sito que hay acá.
Los las páginas por defecto tienen un margen.
Esto es muy bueno y muy buenas prácticas que nosotros se lo quitemos siempre para que no se vean afectadas todas nuestras nuestras creaciones en el navegador.
Vamos a colocar voz Vim y vamos a colocar le margen cero.
Vamos a guardar y vamos a ver que ese espacio citó ya se nos quita siquiera se lo puedes dejar o se lo puedes colocar en mi casa.
Se lo voy a quitar para que se vea un poquito y como mejor Ahora voy a colocar otro, dice Vamos a le Control + L seis Control + L, Rubén, Moya colocarle caja dos.
Y aquí vamos a colocar le Caja uno.
Vamos a cambiar acá.
Aquí nuevamente.
Vamos a crear una caja, en este caso, hacer caja dos.
Vamos a colocar le también un buit Es de muy, muy Según.
Va a tener treinta píxeles.
Tenemos un High también de treinta píxeles.
Y vamos a colocarle un background.
Aquí no son dos punto cama, va gran color y nuevamente vamos a nuestra página.
A ver qué otro color le podemos colocar.
Este amarillito esta bonita.
Se lo vamos a poner y le colocamos El.
Numeral.
Aquí vamos a mirar el resultado en el navegador.
Vamos a actualizar y vemos que se nos creó nuestra caja con treinta píxeles y treinta píxeles.
Vamos a mirar que los dos están muy pegaditos y como haríamos nosotros para que no estén tan pegados? Pues vamos a colocarle un margen ese margen.
Lo vamos a colocar en en la caja uno también puede ser en la caja dos, como tú quieras que vamos a colocar Mardin y vamos a colocar le heridas pixeles.
Vamos a guardar y vamos a ver el resultado.
Como bien, no solamente se nos amplio en la parte de abajo, sino también al rededor.
Eso es porque se Mardin, se toma en todos los lados.
Qué pasaría si yo quiero que sea solamente abajo aquí en el mar Vim le colocaría Mardin Borón y solamente le colocó estos diez píxeles Hay Vamos a guardar, vamos a actualizar y vemos que la cajita sigue en su estado natural desde donde está por defecto.
Sin embargo, solamente tiene un margen en la parte de abajo.
Ahora, si queremos colocar le diferentes Martins lo podemos hacer siempre.
Tenemos que tener en cuenta que esto es como un reloj.
Va desde la parte de arriba y va en el sentido de las manecillas hacia la derecha Aquí empezaríamos por top.
Es decir, que el valor del Martín de arriba sería diez píxeles.
Vamos a colocarle al siguiente veinte píxeles Después treinta píxeles y cuarenta píxels.
Vamos a guardar, actualizamos y vamos a mirar eso en el modelo de caja, como vemos en las muele casa.
Entonces tenemos un Martín arriba de días, Pizza les veinte, treinta y cuarenta en el sentido de las manecillas del reloj Esto.
También lo podemos hacer con el padre.
Ya vimos el modelo ECA y su importancia.
Sabemos a inspeccionar elementos y mirar su modelo.
Encaja en el inspector.
Ahora vamos a ver valores relativos y valores absolutos.
También vamos a construir nuestro primer componente.
Te veo en la siguiente clase..

### Valores relativos y absolutos

Hola en esta clase vamos a hablar sobre medidas absolutas media relativas y vamos a construir nuestro primer componente en nuestra aplicación Las medidas absolutas son, por ejemplo, estas que podemos ver Acá están los píxeles dos milímetros, los centímetros las pulgadas.
Este tipo de unidades son absolutas precisamente porque no tienen en cuenta a nadie más.
Es decir, que no se fijan en la medida de otro o en el tamaño de algún otro elemento para hacer ellas mismas.
Por ejemplo, cuando estábamos nosotros en la clase anterior vimos que les colocamos subir de veinte píxeles Un Jay de veinte píxeles.
Sin embargo, este estos pixela Ges se vieron representados en el navegador sin ningún problema.
No se vieron afectados por nadie.
Las medidas relativas se llaman precisamente así porque están relativas a otra unidad de medida o a otro elemento.
Por ejemplo, en estas podemos encontrar los porcentajes en CDC se los vamos a encontrar muchísimo.
También podemos encontrar Ve Max me me divirtió Jair todos esto les vamos a A continuación en el coche tenemos un archivo nuevo que se llama G DIR y nuevamente vamos a es que empezar a escribir nuestros Cowen Voy En este hoy vamos a colocar nuestra etiquetaje, ver por semánticas muy bueno que lo utilicemos.
Entonces tenemos nuestro Gerd y vamos a colocar debajo de Get nuestra etiqueta esta para empezar a colocar los estilos.
Vamos a colocar que ver como selector y vamos a abrir entre Chávez y Tags para empezar a escribir nuestros estilos.
Acá le vamos a colocar un Week, pero ya no se lo vamos a colocar como medida absoluta, sino que se lo vamos a poner como me ha relativa Eso porque queremos que se ajuste a todos los niveles de pantallas que nosotros queremos.
En este caso queremos que el Gener vaya de inicio a fin.
Por eso le vamos a colocar que tome el cien por ciento de toda nuestra pantalla.
Vamos a colocar le punto y coma y vamos a colocarle un Home.
En este caso le podemos colocar ochenta píxeles.
Vamos a aguardar.
Aún no vamos a ver nada porque no tenemos ningún color.
Vamos a Iraq al navegador.
Efectivamente.
No vemos nada.
Y vamos a ir a esta otra página en donde podemos encontrar diferentes colores.
En.
Esta es K.
Tengo ya el resultado del inicios.
Es decisión de nuestra aplicación y vemos que el Jerez tiene un color como ver dos.
Ese color no lo pasó el equipo de diseño y es este que está aquí precisamente.
Solamente le vamos a dar click Vamos a co le comencé Vamos a nuestro código colocamos Help Accra on color y vamos a copiar este color nuevamente hemos colocarle el numeral Vamos a guardar, miramos en nuestro navegador y efectivamente, tenemos nuestro G, nuestra Gerd con el el huir y el High que le Establecimos Como vimos en la clase anterior tenemos un pequeño espacio que se lo vamos a quitar unos a colocarle body, abrimos llaves y entre estas llaves vamos a escribir Mardy cero punto y coma.
Si quieres, le puedes colocar Pic seis.
Vamos a guardar y vemos el resultado Ya Tenemos nuestro Jero Ya.
Después de Steger podemos colocar algunas otras etiquetas.
Podemos utilizar anidamiento nosotros en esta parte.
Acá tenemos un logo de Platzi Este logo Help Latin.
Te lo voy a compartir para que lo puedas colocar dentro de dentro del género.
Aquí voy a colocar la etiqueta y MG para anexar imágenes Y mi ruta es la siguiente Tengo aquí el loco.
Tú puedes ir a la ruta en donde descargas del archivo y toque te compartir.
Voy a darle guardar y en ese ERE CD voy a colocar esta ruta.
Vamos a dejarlo.
Desde y Users han así está bien, Vamos a guardar y vamos a ver nuestro resultado.
Vamos a ver que éste Luego está súper grande, pero nosotros podemos estilizar los Una de las formas que podemos utilizar para estilizar esta imagen es colocar, ceder y vamos a colocar y en México lo que quiere decir que este IMG es un hijo de de Ter.
Vamos a colocar.
Vamos a utilizar todas las imágenes que hayan dentro de esta etiqueta Jero así vamos a colocarle un buit Tienes de caso de dos cientos píxeles.
Vamos a guardar y vamos a ver el resultado Cristo se nos vea y superbien Tags llenos de con el tamaño que nosotros queremos.
Ahora lo que tenemos que hacer es entrar nuestro elemento de forma vertical.
Vamos a mirar cómo lo podemos hacer.
Acá.
Vamos al en el inspector es muy bueno que también lo utilicemos.
No siempre es como mirando el código.
El inspector también nos puede ayudar para escribir nuestro código, tantear, probar y después hay si pasamos el resultado que ya nos guste al código.
En este caso tenemos esta Imagina si le Home podemos colocar un pequeño margen arriba y le colocamos.
No se veinte píxeles.
Podemos colocar le.
Bueno, fue mucho tonces empezamos a disminuir.
Le Joaqu al Estoy disminuyendo con las teclas de mi computar del teclado.
Puede que lo dejemos.
Hay en diez píxeles.
Está muy bien.
Y también podemos colocar un mar Vim al lado izquierdo.
Mardin Les CTO Aca le podemos colocar entonces diez píxeles y se nos ve super bien.
Vamos a ver.
Vamos a colocar estos dos Estas dos propiedades que lo acabamos de añadir y las vamos a copiar.
Vamos aquí en nuestro código las pegamos.
Guarda más Cuando refresque.
Hemos deberíamos ver el mismo resultado.
Tengo un reto para ti.
El reto es escribir tu propio ceder.
Steger lo puede hacer con los colores que más te gusten y lo puedes compartir en la sección de comentarios.
Si tienes alguna duda, no dudes en hacerlo.
Estamos los compañeros y yo para resolver cualquier duda o encontrar inquietud que tengas.
Nos vemos en la siguiente clase.

## 4.Arquitectura CSS

### ¿Qué son y para qué nos sirven las arquitecturas CSS?

Hola.
Comenzamos un nuevo móvil en nuestro curso Este módulo sobre Arquitecturas de ese Ese ese este tema es muy importante.
Y curiosamente es un poco desconocido por los desarrolladores.
Cuando nosotros trabajamos con Cdcs, nos damos cuenta de que tenemos una gran cantidad de líneas de CO y CO en nuestras clases.
Hemos trabajado con cinco, diez líneas Sin embargo en los proyectos nos podemos enfrentar a quinientas mil dos mil líneas dependiendo el proyecto Te.
Imaginas cómo sería tener todas esas líneas de juego en un solo archivo? Muy seguramente para nosotros que ya conocemos el proyecto sea un poco fácil Pero si llega otra persona ayudarnos va a ser un poco complejo poder entender todas esas dos mil líneas de código Para eso se crearon las arquitecturas de SSL Uno de los objetivos claros es que estas arquitecturas sean predecibles.
Que quiere decir que sean predecibles? Si, establezco una regla.
Esa regla debe cumplirse exactamente tal cual Como se dijo No, debo establecer una regla y que esa regla Add a otra cosa diferente Otra de las cosas importantes es que sea reutilizable.
Todo nuestro código Sí, por ejemplo, tengo una clase que tiene un color y un mar Vim y voy a utilizar la en otro lado.
La idea es que en ese otro lado, en ese otro elemento, no copie y pegue San esos estilos, sino que trata de ver la forma de como puedo reutilizar.
Es el juego sin escribir más líneas Otra de las cosas, de los objetivos importantes es que el código sea mantenible.
Qué quiere decir que sea mantenible? Si tengo esas dos mil líneas de código, creerías que esos mantenible? Muy seguramente no.
Por qué? Porque si yo voy a llegar a hacer nuevas cosas, pues me tocaría.
Posiblemente volverá.
Copiaría pecar, ya se volvería un poco engorroso.
Trabajar con él no sería mantenible.
No? En un futuro sería muy difícil poder trabajar con estas dos mil líneas Asimismo llega la escalabilidad Si.
Nosotros tenemos un archivo tan grande En un futuro va a ser muy difícil poder hacer que se ese archivo crezca de forma buena.
En este caso podría crecer y crecer y crecer Pero se diría un afectadas varias partes en nuestra de aplicaciones, como por ejemplo el rendimiento Es.
Así como estas, estos principios que acabamos de mencionar se van a ver reflejados en unas muy buenas prácticas.
Entre esas buenas prácticas está establecer reglas Con el equipo? No, no basta con que yo se pasa reglas de arquitectura y mi compañero no las conozco porque hay vamos a empezar a chocar en el proyecto, donde es importante que ambos se sienten y empiecen a estructurar esas reglas con las que ambos van a trabajar.
También está, explican, la estructura base.
Si yo tengo una estructura base, ya tengo un proyecto avanzado y si alguna persona nueva es importante, que se le ve todo ese vacas y que se les de conocimiento que ya se tienen el proyecto, establecer estándares de codificación.
Esos estándares los vamos a ver en la siguiente clase Por.
Es importante que si establecemos algo también lo es.
Hemos definido, sea al principio en un documento parte, pero que ya están definidas y no se rompan, porque si establecemos reglas y al final no las cumplimos, pues no estamos haciendo esto.
Este tema de las arquitecturas de una forma vil, evitar largas, largas, hojas de estilo.
Esto es muy importante para que, para que podamos tener un juego mantenible y escalable.
Asimismo, en la documentación de hemos tener como muy buena práctica la documentación no quiere decir que línea por línea.
Empecemos a explicar que esto es un color, que esto es una margen, que nada de eso La documentación se basa al principio o en ciertas cosas que pueden ser un poco complejas o no tan fáciles de comprender para otra persona que llegue en un futuro inclusiva para nosotros mismos.
Nos decías pronto te ha pasado que escribes algo y a la semana lo va a saber y se hay yo porque escribí eso.
Entonces es muy buena en la documentación, entonces, no siendo más vamos a ver el tema de arquitecturas.
Vamos a ver o o si es es vamos a ver que es es mas ven entre otras.
Así que allá nos vemos..

### OOCSS, BEM, SMACSS, ITCSS y Atomic Design

Hola.
Comenzamos un nuevo móvil en nuestro curso Este módulo sobre Arquitecturas de ese Ese ese este tema es muy importante.
Y curiosamente es un poco desconocido por los desarrolladores.
Cuando nosotros trabajamos con Cdcs, nos damos cuenta de que tenemos una gran cantidad de líneas de CO y CO en nuestras clases.
Hemos trabajado con cinco, diez líneas Sin embargo en los proyectos nos podemos enfrentar a quinientas mil dos mil líneas dependiendo el proyecto Te.
Imaginas cómo sería tener todas esas líneas de juego en un solo archivo? Muy seguramente para nosotros que ya conocemos el proyecto sea un poco fácil Pero si llega otra persona ayudarnos va a ser un poco complejo poder entender todas esas dos mil líneas de código Para eso se crearon las arquitecturas de SSL Uno de los objetivos claros es que estas arquitecturas sean predecibles.
Que quiere decir que sean predecibles? Si, establezco una regla.
Esa regla debe cumplirse exactamente tal cual Como se dijo No, debo establecer una regla y que esa regla Add a otra cosa diferente Otra de las cosas importantes es que sea reutilizable.
Todo nuestro código Sí, por ejemplo, tengo una clase que tiene un color y un mar Vim y voy a utilizar la en otro lado.
La idea es que en ese otro lado, en ese otro elemento, no copie y pegue San esos estilos, sino que trata de ver la forma de como puedo reutilizar.
Es el juego sin escribir más líneas Otra de las cosas, de los objetivos importantes es que el código sea mantenible.
Qué quiere decir que sea mantenible? Si tengo esas dos mil líneas de código, creerías que esos mantenible? Muy seguramente no.
Por qué? Porque si yo voy a llegar a hacer nuevas cosas, pues me tocaría.
Posiblemente volverá.
Copiaría pecar, ya se volvería un poco engorroso.
Trabajar con él no sería mantenible.
No? En un futuro sería muy difícil poder trabajar con estas dos mil líneas Asimismo llega la escalabilidad Si.
Nosotros tenemos un archivo tan grande En un futuro va a ser muy difícil poder hacer que se ese archivo crezca de forma buena.
En este caso podría crecer y crecer y crecer Pero se diría un afectadas varias partes en nuestra de aplicaciones, como por ejemplo el rendimiento Es.
Así como estas, estos principios que acabamos de mencionar se van a ver reflejados en unas muy buenas prácticas.
Entre esas buenas prácticas está establecer reglas Con el equipo? No, no basta con que yo se pasa reglas de arquitectura y mi compañero no las conozco porque hay vamos a empezar a chocar en el proyecto, donde es importante que ambos se sienten y empiecen a estructurar esas reglas con las que ambos van a trabajar.
También está, explican, la estructura base.
Si yo tengo una estructura base, ya tengo un proyecto avanzado y si alguna persona nueva es importante, que se le ve todo ese vacas y que se les de conocimiento que ya se tienen el proyecto, establecer estándares de codificación.
Esos estándares los vamos a ver en la siguiente clase Por.
Es importante que si establecemos algo también lo es.
Hemos definido, sea al principio en un documento parte, pero que ya están definidas y no se rompan, porque si establecemos reglas y al final no las cumplimos, pues no estamos haciendo esto.
Este tema de las arquitecturas de una forma vil, evitar largas, largas, hojas de estilo.
Esto es muy importante para que, para que podamos tener un juego mantenible y escalable.
Asimismo, en la documentación de hemos tener como muy buena práctica la documentación no quiere decir que línea por línea.
Empecemos a explicar que esto es un color, que esto es una margen, que nada de eso La documentación se basa al principio o en ciertas cosas que pueden ser un poco complejas o no tan fáciles de comprender para otra persona que llegue en un futuro inclusiva para nosotros mismos.
Nos decías pronto te ha pasado que escribes algo y a la semana lo va a saber y se hay yo porque escribí eso.
Entonces es muy buena en la documentación, entonces, no siendo más vamos a ver el tema de arquitecturas.
Vamos a ver o o si es es vamos a ver que es es mas ven entre otras.
Así que allá nos vemos..


## 5. Construcción de componentes
### ¿Qué es un componente? Analicemos nuestros diseños

Hola, Mi nombre es Stefan Eguilar.
Soy la profe.
El curso Afronten Developer de la escuela Ella Maastricht En esta clase pública.
Vamos a aprender que es un componente y vamos a identificarlos dentro de nuestra aplicación.
Un componente básicamente es un elemento muy pequeño que podemos utilizarlo más adelante para construir futuros componentes.
Por ejemplo, vamos a pensar en Lego.
Si nosotros compramos un Lego, nos vamos a dar cuenta que tenemos una cantidad de fichas y que para construir el resultado final debemos unir esas piezas Asimismo funciona nuestra aplicación.
Debemos coger esos componentes unirlos y así mismo empezará a formar las vistas de nuestra aplicación Ahora.
Tenemos un proyecto que se llama Platzi Vídeo.
Vamos a mirar la vista y vamos a identificar qué componentes podemos sacar de ahí.
Esto es muy importante que lo hagamos antes de escribir nuestro código para que nos facilite mucho más del desarrollo.
En este caso tenemos un carro.
Se lo voy a señalar aquí de color rojo Este sería el componente principal o el contenido? El contenedor quería Carrousel acá tenemos un ítem desde carros ser.
Vamos a señalarlos para identificarlos.
Y dentro de ese ítem vamos a ver que tenemos unos iconos, básicamente puede ser los mismos Sin embargo, le vamos cambiando la imagen, sin embargo, sigue siendo el mismo componente icono.
Acá tenemos un título.
Sería un texto principal principal y esto sería un texto secundario.
Si lo notamos es de título principal.
Es muy similar al que hay en el Führer y al que hay acá.
Tiene el mismo tamal.
Podemos reutilizarlos y decir que este también es un texto principal.
Ésa es básicamente la idea de los componentes que lo logremos identificar y mirar en donde lo podemos volver a utilizar Ahora miremos el G DIR que sería estado a Rita superior.
También tenemos un y logo y así mismo tenemos un menú.
Desplegar este meno también lo podemos utilizar más adelante Finalizando Tenemos un input que es el buscador principal de toda la vista de Plachy vídeo y le podemos colocar simplemente buscador este buscador.
Aunque lo utilicemos solamente en la vista principal, es muy importante que también lo tengamos cincuenta como componen Después de tener identificados nuestros componentes, lo que vamos a hacer es pasarlos a nuestro código.
Una de las opciones que tenemos es tener una carpeta que se llame componen y dentro de él de ella.
Tener otros Folder s con el nombre de cada uno de los componentes que identificamos, por ejemplo, y buscar el buscador tendría dentro todos los archivos de Javascript de HTML y de seis es claro está, dependiendo del lenguaje que utilices o de la librería por el freno.
Pull Otra opción es utilizar History Dotx cual Story Push Podemos tener una documentación muy amigable y visual de todos los componentes.
Lo único que tenemos que hacer es instalar History Pull PKG y después correrlo con el comando N P M Ranch History.
Poco después de correr esta comandos se nos va a abrir una ventana y vamos a experimentar como si estuviéramos en una librería, como si hubiéramos creado una librería de nuestros propios componentes.
Lo que podemos hacer ahí es interactuar con ellos, darle click, mirar qué opciones tiene que colores, etcétera.
Es muy agradable utilizar History poco para nosotros.
Como desarrollarse.
Todos los componentes son muy buenos utilizarlos precisamente porque nos ayudan a optimizar el código, nos permiten reutilizarlo y se ve mucho más agradable tanto para nosotros como desarrolladores como para alguna otra persona que llegue nueva el proyecto Mira todo lo que aprendiste en una sola clase aquí.
Te voy a dejar el en las del curso para que sigas aprendiendo.
También te voy a compartir un vídeo.
Relaciona Y no se te olvide suscribirte a nuestro canal..

### Estructura con HTML y BEM de un menú desplegable

Hola en esta clase aprenderemos a crear un menú desplegable.
Para ello vamos a ver la vista principal de nuestro proyecto para ver de qué se trata.
Tenemos Platzi vídeo y en la parte superior derecha vamos a ver un menú desplegable este acá justamente cuando le damos Jover con nuestro Maus Vamos a darnos cuenta que tenemos dos ítems.
En este caso es cuenta y cerrar sesión.
Este efecto lo vamos a aprender a hacer en esta clase Anteriormente teníamos un código como este, teníamos un GB y dentro de él una imagen.
Vamos a ver como SE de nuestro navegador EST debería ser el resultado.
Sin embargo, podemos ver que en Platzi Video el Fondo ha cambiado Ya no es este verde, sino que es este Murado.
Lo que vamos a hacer es ir nuevamente a la paleta de colores que ya habíamos visto en clases anteriores.
Vamos a copiarnos, es de color morado desde el más clarito y lo vamos a pegar aquí donde dice genera para que todo que con este mismo color De la misma forma lo vamos a poner en el body para que corresponda con el color de nuestra de nuestra vista principal vamos a ir a Buscador.
Vamos a actualizar Y efectivamente, ya tenemos algo muy parecido a lo que tenemos en Platzi vídeo.
Muy bien, vamos a a empezar con nuestro menos como bien vimos, trabajamos con Ben.
Entonces vamos a seguir con esta misma metodología.
Entonces aquí la clase del Heaven sería Ger.
Le vamos a colocar aquí un punto para que corresponde con esa clase.
Y en imagen vamos a colocar una clase que va a ser Recordemos que ven significa bloque elemento modificador.
Aquí sería GB del Bloque M es el elemento sería imagen.
Te vamos a colocar IMG Así aquí le le pondríamos un punto y un iríamos estas dos palabras con guión bajo bien bajo.
Vamos a guardar y mirar que eso esté funcionando perfectamente.
Muy bien, aquí abajo, después de y MG vamos a colocar un dit que se va a hacer el Papa o el contenedor de nuestro menos colocamos la clase.
Vamos a colocar le ceder y Home bajo Debian bajo meno Vamos, A Y aquí el CSS y vamos a escribir esta clase G y un bajo quien bajo minutos.
En este momento este contenedor no tiene ningún efecto.
En parte en particular.
Sin embargo, le vamos a colocar un margen porque si nos damos cuenta tiene un pequeño espacio entre el elemento y el borde final de la pantalla.
Lo que vamos a hacer es colocar un margen en esta parte.
Vamos a colocar le Martin Gray treinta píxeles.
Listo.
Ya tenemos un mar Vim en nuestro contenidor seguido.
Esto vamos a tener dos partes fundamentales.
Tenemos donde dice perfil y la parte donde dice cuenta y cerrar sesion.
Lo vamos a envolver en dos contenedores diferentes.
Entonces tenemos un diez en este Edit.
Vamos a colocar la clase que sería y Kuala esta Germeno Sin embargo, le vamos a colocar, pero falló que eso significa el perfil, precisamente el usuario dentro de ese perfil vamos a ver que tenemos una imagen.
Ya miramos de donde sacamos de esa imagen y luego vamos a colocar la palabra perfil Vamos.
Acuerda? Y vamos a ver qué es lo que estamos haciendo.
Muy bien, Tenemos perfil.
Nos hace falta la imagen Esta.
La podemos sacar de esta página que es y con ocho vamos a colocar aquí.
Yo ser.
Le damos enter y nuevamente no salen un montón de de iconos.
Lo que vamos a hacer es seleccionar el que más nos guste.
Por ejemplo, este.
Y le damos descarga.
Cuando leemos descargar el nos pregunta en qué formato, en este caso, vamos a escoger PNG y el píxel AG puede ser el que nosotros queramos, porque porque vamos a cambiarlo de todas formas, con ceses, en este caso, dieciséis píxeles Go treinta estaría perfecto.
No le voy a descargar porque yo ya la tengo aquí, en el proyecto.
Lista.
Voy a seleccionar la ruta.
En este caso sería apuntes las este punto Slash quiere decir que la imagen está al mismo nivel del archivo.
Htm Help.
Aquí ya me sale por una ayuda.
Vamos a colocar y Usher.
John, Hay con y aquí, en el All.
Vamos a colocar le y Users.
Tú puedes colocar le el que más de gusta.
Yo nos Aware tar y vamos a ver en buscar qué es lo que no salió perfectamente.
Ya tenemos.
Ahí está parte del lobo con el nombre.
Muy bien, seguida está.
Vamos a tener otro contenedor.
Va a ser una lista.
Y en esta lista vamos a tener unos items con unas con unas etiquetas A porque lo colocó como a precisamente porque cuando le demos clic a esa lista me tiene que direccionar a otra parte.
Por eso estamos haciendo como un buen uso en la semántica.
Utilizando esta a aquí voy a colocar una ruta por defecto, que sería la ruta inicial Ese sería como el Home o la pantalla principal.
Vamos, A.
Le Control + L se Control + L B y dentro de estas etiquetas donde sacó el Oscar? Entonces cuenta y cerrar sesión.
Listo.
Vamos a guardar y veamos cómo vamos Hay muy bien.
Listo.
Lo que vamos a hacer es empezar estilizar En este caso voy a colocar le Aca debajo de gener.
Menú.
Vamos a copiar.
No sea pegarnos de eso para que sea un poco más más fácil para nosotros un estar copiando.
Gerd que han bajo en bajo.
Listo, Vamos a colocar menos y Profile.
Vamos a aguardar y listo, que tendríamos que colocar en este en este Profile.
Vamos a colocar de pronto margen para que tenga de pronto un espaciado comandos a Jolo carne, entonces un mal Vim Git o un espaciado entre la imagen y el texto.
Entonces vamos a colocarles en Mardin Ray de ocho, ficha les y abajo.
Le vamos a colocar un Where de cuarenta pizza les puede ser lista.
Vamos a guardar.
Ahorita miramos entonces el resultado Vamos a seguir.
Por lo pronto con esta parte del menú.
Con esta parte de la lista es muy importante que tengamos en cuenta que la Lisa se va a ver en un momento, pero en otro momento no.
Vamos entonces a estilizar esta lista.
Moda colocar puede ser aquí a Rita para que tengamos coherencia con lo que estamos viendo acá.
Es decir, que yo aquí Vea y MG y aquí estoy, DMG y abajo, menú menos a que siga la misma línea.
No, que primero este emerger Profile después por allá.
Gernot que tengan la misma niño.
Vamos a colocar entonces he quien bajo quien bajo menú Y como no le hemos colocado una clase a este vamos a colocar le simplemente el huele.
En este caso sería ideal que le colocáramos un display, no un para que no viéramos nada de esta lista por el momento vamos a mirar qué es lo que sucede? Vamos a recargar y efectivamente, no estamos viendo una.
Vamos a empezar estilizar, pero para ver el estilo.
Pues vamos a comentar esto por un momento Vamos a quitarle eso esas Puntí coso bolitas que vemos en la lista que no sale por defecto y se lo vamos a quitar con esa propia Linux estado Colocamos Gnome guardamos y miremos que ya aquí no están esos en esos politicos Vamos a colocar también un padre porque ellos por defecto lo tiene y se lo vamos a quitar, le vamos a decir Pau cero Pit seis.
Este huele por defecto en lo miramos, Vamos a inspeccionar.
Vamos a seleccionar este elemento.
Bueno, si no nos agarra, pues vamos a venir aquí el inspector Colocamos, huele y miramos que tenemos de color verde Help Add en que está justamente en esta parte.
Se lo vamos a quitar, Se lo quitamos precisamente con este padre.
Cero pic seis.
También vamos a colocarle una posición absoluta para que posiblemente más adelante empecemos a posicionarlo como nosotros queramos en relación al bar.
Vamos a cogerlo, Cat le absoluto le son.
Vamos a colocar le también un buit de si en píxeles Y vamos a alinear el texto, porque si vemos aquí cuando hacemos joven el texto se alinea justamente de esta parte hacia ya.
Entonces lo vamos a hacer igual para acá.
Vamos a colocar en Text Alain y Crouch.
Como es acortar y vamos a refrescar.
Listo? Ya no tenemos desde Padín y el texto está alineado a la derecha.
Lo que también podemos hacer es colocarle un margen negativo a este lado porque porque cuando yo le hoy aquí el se sale justamente de él empieza el dia K, pero quiero que se me corra un poco más de para ya y que empiece justamente en esta línea.
Entonces acá ya no quiero que empiece desde aca, sino que empiece a la raíz de donde dice perfil para eso.
Entonces lo que debemos hacer es colocar.
Comenzaba quitar este display.
Vamos a colocar entonces un mal alguien? Vamos a colocar cero píxeles en arriba, a la derecha abajo y ya sería cuanto menos catorce pixeles, más o menos.
A este la vamos a refrescar y vamos a ver si efectivamente nos cogió el Martín sería este ley o que hay no lo coge.
Sin embargo, el como ya está al límite, pues no va a ir hasta ya.
Lo que tenemos que hacer es posicionar estos elementos para que ella tenga en cuenta esta posición relativa.
Bueno, hemos terminado esta parte de la estructura de HTM l Hemos estilizado algunos componentes, pero vamos a seguir en la próxima clase para estilizar toda la lista y dejar completamente liso nuestro menos..

### Estilizando nuestro menú desplegable con CSS

hoy en nuestra clase anterior hicimos todo el menú desplegable en HTML Estiliza mos un poco, pero aún nos queda faltando.
Vamos a comenzar con esta parte que nos quedó faltando de nuestras que hace anterior aquí en nuestro código ya tenemos el Germeno medio y tenemos el profe.
Vamos a mirar en qué quedamos? Vamos a refrescar.
Quedamos en esta sección y justamente lo que queremos es que este perfil llegue a esta esquina así como nos muestra el original.
Vamos entonces a utilizar una especificación muy que nos puede ayudar muchísimo, que es Flex pocs para utilizar Flex pocs.
Tengo esta guía.
Lo único que tenemos que saber es que tenemos que utilizar this play Flex y alinearlo Schilling elementos con dos propiedades que ya te las voy a comentar en el momento.
No importa si no entendemos absolutamente toda la especificación.
Eso lo vamos a ver en más detalle, más a él han En Jer.
Vamos a colocar entonces Display ya no le colocamos en la en sí, lo que les colocamos Flex y el contenedor, que en este caso del Jerez tiene que alinear esos elementos.
Para eso vamos a utilizar Yuste Fay content y le vamos a colocar, estéis min TTY.
Eso lo que nos va a ser es que nos va a colocar estos dos elementos con un espacio en medio, así como nos dice también esa propiedad Listo.
Esto es por el momento, lo que necesitamos para que se nos ubique es elemento justamente en la esquina.
Muy bien, ahora vamos a ver que cuando le hacemos joven necesitamos que no salga eso en fin, vamos a hacer Sjoeberg aquí, en la parte de abajo, donde está el duelo.
Vamos a colocar otra clase que se va a llamar header y un bajo guión bajo menú.
Y ahora sí vamos a hacer uso de nuestra pseudo classe.
El joven.
Queremos que cuando acabamos Jover en este menú todas las el EU esto es lo que quiere decir estoy acá.
Vamos a colocar que también cuando le damos joven a los el EU, es decir, cuando yo le haga joven a este lo que va a tomar esa propiedad son estas duele, sin embargo, estas huele al hacerle joven.
También va a suceder lo que vamos a escribir aquí adentro, que en este claro caso es una línea de código, no más, que es colocar le display Blog porque colocamos eso? Porque justamente cuando nosotros le dijimos a él que no se mostrara necesitamos que las del joven se muestre.
Y este es el efecto que logramos cuando colocamos Display, No? Y display Blog.
Vamos a aguardar.
Vamos a ver el resultado.
Efectivamente, no tenemos nada.
Nos acercamos y aparece en nuestro o el muy bien Vamos entonces a estilizar nuestros l y que no están como visualmente iguales.
Entonces lo que vamos a hacer es colocar punto G DIR meno que un bajo bien bajo menos.
Y vamos a utilizar los de ley con vamos a colocar un margen porque porque soy un poco pegadita.
Vamos a colocar Martín dos puntos, diez píxeles y cero pixeles.
Eso qué quiere decir? Cuando solamente colocamos dos es tema para el Top y para el borrón.
Y está ya capa para leer y para el mar.
Vamos, acuerdo.
Tar visto ya no se sientan juntos los dos.
Muy bien.
Ahora vamos a utilizar lo que está dentro de los Lake.
En este caso son a Colocamos nuevamente.
Esto mismo.
Vamos a darle Command + L CD comande.
Aquí cogemos de la que le vamos a borrar esa propia.
Muy bien.
Vamos a colocarle un color en este caso, hacer blanco para que siga en la guía que nos está indicando el la aplicación.
Y vamos a colocar le también un texte con ella, porque por defecto todas las A tienen una línea por debajo y no lo queremos.
Queremos que esté limpio.
Vamos a colocar le .txt.
Corrección, no.
Y con eso vamos a quitar esa línea que no sale por defecto Visto.
Ya tenemos esto, Sin embargo, si lo puedes notar, vemos que estas letras son muy diferentes a las que estamos utilizando.
Acá hay un una página que me gusta mucho, que se llama Cuba.
Alfons Tengo.
Bueno, Fat, vamos a buscar el tipo de letra de nuestra aplicación, que en este caso se llama mi Elio.
Listo, ya la tenemos.
Después de tenerla, le damos clic aca.
En este más nos va a salir la familia seleccionada y lo que tenemos que hacer es copiar este link.
Esto es super importante y lo vamos a pegar justamente en el jefe de nuestra aplicación.
Vamos a colocar la hay y también nos hace falta colocar esto.
Que es Fone Feeder, le vamos a copiar y lo vamos a pegar justamente en el Voy para que todas las letras de nuestra aplicación, que con este tipo de letra vamos a coartar.
Y vamos a ver, no nuevamente nuestro buscado muy bien, ya acogió las letras igualitas a las que tenemos en la aplicación.
Listo.
Entonces necesitamos que a las del joven también en el duele en la lista.
Pues si nos quería incierto, porque si yo le hoy Click, yo hago Jover acá y acá no? Pues nunca voy a poder seleccionar esto.
Sin embargo, nosotros ya hicimos es el inconveniente.
Es este perfil que está acá.
Tenemos que subirlo como lo subimos solamente colocando display Flex.
Vamos a ver ese resultado acá ya lo pasamos en código.
Muy bien.
Cuando le damos acaba joven, efectivamente, ya me dejaría pasar aquí a cuenta y a inicio de sesión Listo.
Entonces vamos a hacer eso mismo aca vamos a ir a germen un profano Y aquí mismo les colocamos Display y Flex también cuando le colocamos desde mayo.
Ahí te pronto no fue lo mejor, porque bueno, se nos esconde bastante y con entonces los que vamos a hacer es han ampliarles en margen para que desde Mardin bueno, nos deje ver lo que estamos haciendo.
Vamos a inspeccionar acá y vamos a subir le a este mar Vim a ver hasta dónde es que queremos.
Lo podemos dejar en sesenta presentó estaría bien y así ya podemos venir a este a este joven Bueno, vamos a copiarnos de esta propiedad.
Marginó Wright, coman C, Vamos, Ager menú y se lo vamos a y se la vamos a cambiar.
La copie En.
Ese no era y es el Este CTO ya no son treinta, sino que son sesenta Vamos Aguardar, refresca, Moss y listo.
Perfecto.
Ya tenemos nuestro nuestro menos bueno, despues de eso, lo que nos queda es que también cuando le hagamos joven a a este se nos presente esa línea que queda por deba.
Miremos acá, le damos acá, Jover y cuando venimos acá, vamos a darnos cuenta que tenemos una línea por debajo Al hacer Jover vamos a hacer ese mismo afecto.
Venimos nuevamente a nuestro código.
Colocamos Get her en quien bajo bien bajo meno y vamos a colocar ley a que Entonces esto indica que los elementos a que están dentro de ley que están dentro de esta clase Vamos a abrir nuevamente y le vamos a colocar entonces a Bueno, aquí nos falta el joven precisamente porque es justamente cuando hace joven y en esta parte le vamos a colocar nuevamente esa propiedad que se la quitamos acá cuando da copiarle a pegar la mejor copiamos, pegamos y ya no sería no, sino que sería Wonder.
La vamos a guardar, refresca, Moss y listo.
Cuando hacemos Jover tenemos ese efecto en esa línea.
Cita dio nos queda faltando colocar este perfil también de color blanco.
Y si lo notamos, cuando de perfil saltamos a cuenta, se nos escapa.
Eso es porque este logo que tenemos acá está muy grande.
Vamos a también hacerlo más pequeño y con eso daríamos finalizado nuestro menos en esta parte de acabamos más a colocar.
Bueno, copia monos aquí Eso, nos aplicarlo y vamos a eliminar todo eso.
Listo en Profa Y yo quiero la imagen.
Entonces ahí vamos a darle enter y escribimos un Marchi marginó.
Hay más de cuarenta.
Pongamos le ocho píxeles.
Tuvo para que haya un espacio cita.
Y también le vamos a colocar un Windows Es.
El Whit sería cuarenta píxeles por ahora estamos intentando ver cuál sería el resultado.
Bueno, no está como Como.
Bien, entonces lo que tenemos que hacer es precisamente a este container le podemos colocar.
Podemos intentar Alain hay tens se enter y vamos a colocarle a este Profile a la imagen le vamos a colocar un Jair a ver familia cuarenta píxeles.
Listo.
Muy bien, Vamos a hacer esto mismo.
No saberse haciéndole joven, ya nada.
Entonces lo que vamos a hacer es quitarle precisamente un mar Vim que tiene este párrafo de acá es de marcha.
Es es que no se está evitando hacer eso.
Vamos, A.
Y con este PP le vamos a decir Mar Vim cero pixeles.
Listo? Vamos a ver, más o menos listo lo que necesitamos.
Desde entonces con locales EP que sería el texo Un margen de cero, dices Vamos a buscar ese párrafo.
Sería acá desde el menú profa y copiamos y pegamos eso.
Vamos, A en vez de imagen le vamos a colocar P y le vamos a colocar un margen de cero pixels.
Listo.
Con ese margen de cero pixeles nos quedaría ya vivita.
Eso tambien lo podemos ubicar Muchísimo mejor con Flex posó entonces también miremos como lo podemos hacer.
Pero ya que tenemos destape acá demo- le vivir y vamos a dar el color.
Cuál No está blanco porque listos, carnet, huir, sino que es color como ES acuerda dar Vamos a darle ca y listo.
Hacemos joven y precisamente podemos hacer eso con fácilmente.
Lo único que nos queda es esta esta estructura que es conflicts Vox ya eso lo podemos organizar muchísimo mejor si lo utilizamos en este eje.
Ver lo que podemos hacer es colocar una alineación de los ítems de forma centrar.
Listo, Eso mismo lo tendríamos que hacer en este contenido.
Entonces con los que hemos de esa propiedad que colocamos en GB, que es Alain, hay tens nos acopiar la La.
Vamos a colocar a Can el ceder para que nos Aline los elementos de forma vertical.
Y también lo vamos a hacer en el contenedor de la imagen y el Text, que en este caso sería Germeno Profile no vamos a colocar por acá.
Vamos a colocar al hay, hay tensa enter y vamos a guardar listo.
Ya tenemos nuestro menú.
Sin embargo, miremos que tenemos acá un pequeño salto sabios.
Me poso acá y no me sale en estas listas de o era algo que puede estar fallando ahí.
Vamos a revisar qué es lo que puede estar pasando.
Vamos a hacerlo con el inspector.
Vamos a colocar acá justamente cuando hacemos joven.
En eso es que tiene que pasar lo otro.
Lo que aquí estamos viendo que es como si Germeno Profile tuviera solamente una imagen.
Pero no, él también tiene un perfil.
Nosotros le pusimos aquí un Whit.
No le vamos a colocar este Whit, sino que lo vamos a dejar así para que el dato me tanto la imagen como el perfil.
Posiblemente mientras hacíamos esto con la imagen se nos fue justamente en esta clase y no era y sino en la imagen, pero en ese tipo de cosas pueden pagar Aca en Profile.
Vamos a quitarse la vamos a guardar y vemos que también se nos amplios de Mardin.
Entonces le hayamos puesto sesenta píxeles.
Vamos a buscar esos sesenta pizza.
Les podemos colocar como han EFE Colocamos sesenta pieds es Y aquí te nos muestran donde es Lo podemos hacer directamente acá O podemos abrir esta flechita, colocar treinta PX y le vamos a Can reemplazar todos los que tengan sesenta píxeles y ya no lo cambio.
Vamos a cortar, vamos a refrescar y vamos a ver el resultado.
Muy bien, ya.
Y ya tenemos nuestro menos.
Bueno, hemos creado un menú en la siguiente clase.
Vamos a hablar sobre un buscador.
Vamos a también.
Code Add.
Lo íbamos a mirar.
Que funcione correcta..

### Creación de un buscador

Hola en esta clase aprenderemos hacer un buscador.
Vamos a mirar en nuestra aplicación de Platzi biberón para ver de qué se trata.
Tenemos entonces nuestra aplicación de Platzi vídeo y nuestra buscador sería precisamente este que tenemos acá.
Vamos a colocar le también este texto.
En la clase anterior quedamos en el menú desplegable.
Lo que vamos a hacer es darle en Perth y vamos a empezar a escribir debajo este G.
Vamos a hacer una sección y dentro de esa sección vamos a tener precisamente En un título.
Y este elemento, que es un imputó Acabamos a colocar entonces un H dos El nivel de importancia.
Este texto no es tan grande.
Entonces no le vamos a colocar H uno, sino que le vamos a colocar a Chidos dentro de este.
Le vamos a escribir lo que lo que tiene ahí.
La pregunta que sería que eres.
Ve hoy listo.
Seguido.
Eso iríamos con él.
Imputó muy bien este impute es de tipo texto y se quedó eso Tendríamos que añadirle algo más.
Este imputó.
Vamos, acuerdo.
Tar vamos a mirar aquí el resultado liso.
Tenemos nuestro título y el input Sin embargo, podemos ver que tiene acá como un texto interno que dice buscar.
Vamos a agregarse lo también ese texto interna se llama Play Volver.
Lo vamos a describir acá y le decimos Bush punto, punto punto.
Vamos a guardar y miremos el resultado.
Muy bien, Listo.
Ya nos queda.
Es colocarle las clases y empezar estilizar como tal.
Esto ya sería todo nuestro htm.
Vamos a darle Class.
Y acá vamos a colocar le me, tú le puedes colocar la clase que ese esa clase vamos a colocar.
Le entonces el bloque que sería mail y vamos a hacer alusión a este elemento desde el elemento.
En este caso sería un título Para input sería algo similar.
Vamos a colocar el bloque y vamos a colocar el imputó Muy bien.
Vamos a guardar aquí no veríamos absolutamente nada.
Muy bien.
Hemos cambiado en la Bueno, empezamos a escribir nuestros estilos de banjo.
Es de germen, un profano.
Empezamos con mail Este sería nuestro contenedor.
En este caso nos tocaría alinear los elementos de formas, entrada a lo horizontal y a lo vertical.
Sin embargo, no hemos visto Flex voz y no quiero que lo hagamos todavía.
Y lo vamos a hacer en la clase de Flex Push.
Sin embargo, le vamos a colocar entonces un High y lo vamos a tener listo para nuestra clase de PL ESP.
Os vamos a guardar y vamos a empezar estilizar el H dos con entonces la clase sita que sería Me Quién pagó quien bajo con ello vamos a abrir Chaves y justamente le vamos a colocar un color que es blanca y abajo Vamos a escribir un fons A Hizo un poco más pequeño porque se nos está pasando un poquito y vamos a colocar veinticinco píxeles.
Esto también depende del gusto tuya.
Puntos de le puedes colocar el tamaño que es es a mí me gusta veinticinco pixeles.
Pero si lo quieres dejar asi, grande, lo puedes hacer listo.
Después de esto vendría la estilización de nuestro Imputó.
Le podríamos dejar esta clase Estaría muy bien.
Sin embargo, lo amarra.
Haríamos un poco a la jerarquía de mí.
Es decir si yo quiero utilizar este input después no lo podría hacer porque ya estaría anclado a esto, A esto que estamos haciendo? Entonces le voy a quitar este mail y lo vamos a dejar solamente input.
Ya tenemos claro en la estructura.
Deben, pero lo vamos a quitar por si lo vamos a utilizar en algún en alguno, en algún otro momento.
Y vamos a abrirlo.
Y vamos a empezar estilizar lo todos tenemos una forma diferente.
Comenzar.
A mí me gusta de pronto comenzar como con los colores, con el porte, con etcétera, como lo que se me vaya dando.
Pero si tú quieres empezar por el tamaño o después de lo que aquí adentro lo puedes hacer con total libertad, entonces vamos a colocar en el input un porte.
En este caso le colocamos entonces borde, sería dos píxeles sólido.
Y también le vamos a colocar.
Que sea el borde de color en blanquito por defecto.
Tiene como una especie de de grises y toque no se alcanza a ver muy bien, pero bueno, ahí está.
Vamos a guardar.
Vamos, Arlette guardar aquí aún no se nos ha.
No se nos ve como correctamente ese Bor te, pero bueno, es porque es blanco.
Y también el lo de Add entre el blanco.
Pero bueno, listo.
Ya tenemos desde Word, te vamos a Colo a redondear.
Lo lo vamos a hacer con Border, re- radios y le vamos a colocar veinticinco picha.
Les vamos a guardar y a refrescar acá.
Muy bien, ya tenemos ese borde sito que necesitamos.
También le pues de tantear podemos acá inspeccionar y mirar desde acá el valor que nosotros deseamos.
Yo esto lo hice previamente entonces de uno es de que y le Push del veinticinco.
Pero tú puedes colocar le el jefe es eso.
Después de ese entonces colocamos un color del texto, que sea también blanco.
Y le vamos a colocar la familia que sería esta que le pudimos sacar con Manze.
Y acá le vamos a dar Command + L nueve Ya tenemos también el mismo Help o la misma familia y la vamos a colocar un un tamaño también a la letra.
Vamos a colocar le Fons ays de aproximadamente dieciséis pisas Guardamos.
Vamos viendo.
Listo.
Nos creció un poquitín co ya se nos desaparecen CTO o que Después de eso.
Vamos a colocarle un hay determinado porque éste está más grande que este que tenemos acá por defecto.
Entonces se lo vamos a cuadrar.
Sería hay de unos cincuenta píxeles Vamos a puerta que vamos a ver.
El resultado sería super grande.
Eso lo podemos solucionar mirando aquí, en el inspector, a ver qué es lo que sucede, Posiblemente tenga algún padre en interno, etcétera, que nos esté aumentando este este alto que ya tenemos.
Le podemos colocar entonces un padre de cero pixeles sería arriba y abajo y vemos que está muy pegado este texto del input.
Entonces también lo vamos a separar.
Le podemos colocar unos veinte pizza, Les vamos a cortar y vamos a refrescar.
Bueno, Sin, embargo, sí, que estando un poco pequeña este input vamos ampliarlo porque como vemos, esta muy grandecito, pero vamos a colocar una medida relativa, porque si nosotros inspección amos aquí lo que ya tenemos.
Vamos a darnos cuenta que si estamos en Mogwai el nos debe corresponder a este a este dispositivo también.
Entonces lo que vamos a hacer es utilizar esa medida a en relativa.
Lo colocamos con Where.
Vamos, A con cambiarle el ancho y vamos a colocar unos setenta Pit uno se tenga un setenta por ciento.
No vamos a trabajar con Pixies, refresca, Moss y vemos que ya tiene un setenta por ciento dependiendo de el tamaño de nuestra pantalla.
Para eso es que son muy útiles nuestros valores relativos, que nos quedaría faltando.
Tendríamos entonces un va Crouch un poquito diferente es un poco más claro.
Lo que vamos a hacer es que le vamos a colocar entonces acá en input Vamos a colocarle un va Creo Help va a crear un color.
Puede ser.
Y vamos a colocar RG B A que significa RG.
Vea R es Red, Brin y club y está a Hace alusión a la opacidad.
Lo que vamos a colocar es un color.
En este caso es de colores blanco.
Dos cincuenta y cinco, dos.
Cincuenta y cinco, cincuenta y cinco.
Y acá le vamos a colocar un opacidad.
Le vamos a colocar cero punto uno que sea lo más clarito posible.
Vamos a aguardar Refresca Moss y listo.
Se nos está viendo De esta forma ya está un poco más clarito.
Ya se nos está pareciendo un poco Siento yo que le coloque el morado más clarito y que aquí estamos utilizando el morado más oscuro.
Pero bueno, solo podemos arreglar fácilmente.
Confiamos aquí este nuevo color.
Vamos a al código.
Esto va a ser muy sencillo.
Vamos a abrir nuestra barrita Fahim.
Vamos a colocar el color.
El establecimos anteriormente lo buscamos.
Y lo que hacemos en reemplazarlo por este nuevo color.
Abrimos esta flecha damos Command + L, Command + L nube y le damos en este icono que es de reemplazar.
Muy bien, vamos al buscador.
Guardábamos y listas ya de no se está pareciendo un poco nos quedaría faltando colocarle ahí este texto, el color blanco.
Para ello vamos a hacer uso de un pseudo elemento que es Fleiss hall DIR.
Vamos a abrir nuestras llaves y le vamos a colocar esta misma propia.
Vamos a colocar le color.
Bueno, guardamos y vemos aquí que efectivamente, ya tenemos ese mismo colar.
Lo que nos quedaría faltando es colocar, quitarle este aula Haim que tenemos acá, que es cuando le damos click, nos aparece justamente ese borde azul.
Eso no lo queremos aquí tampoco lo vamos a encontrar cuando les demos clic.
Y lo otro es que seguramente eso tiene un borde.
Citó más redondeado lo que vamos a tratar de hacer entonces y redondear esto.
Bueno, hemos terminado.
Nuestro buscado queda como tarea que estiliza.
Es tu buscador que le redondee.
Es un poco más Eso es sus bordes y aparte de eso, quitarle el aula en que sale por defecto.
Cuando le damos click, nos vemos en la siguiente que hace.

