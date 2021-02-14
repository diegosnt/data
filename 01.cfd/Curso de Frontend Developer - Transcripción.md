**Curso de Frontend Developer - Transcripción** 

**1. Introducción al curso**

**Presentación y bienvenida al curso de Frontend Developer**

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

**¿Qué son y para qué nos sirven HTML y CSS?**

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

**DOM, CSSOM, Render Tree y el proceso de renderizado de la Web**

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