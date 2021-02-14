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