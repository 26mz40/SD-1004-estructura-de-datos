# SD-1004-estructura-de-datos
Tarea estructura de datos


La estructura que mas se me dificulto fue la enlazada, no entendí bien como un elemento guardaba la referencia del siguiente hasta la dibuje con flechas, ahí si lo pude entender mejor.

1. Uber

 grafos con colas de prioridad.

 El mapa se representa como un grafo donde las intersecciones son nodos y las vías son aristas con un peso, que puede ser la distancia o el tiempo. Para encontrar la ruta más corta se usa además una cola de prioridad, que siempre saca primero el camino con menor costo acumulado en vez del que llegó primero. Así no hay que revisar todas las rutas posibles.

2. Netflix

 tablas hash y árboles.

 La tabla hash permite encontrar una película o serie de inmediato a partir de su identificador, sin recorrer todo el catálogo. Los árboles ayudan a organizar el contenido por categorías y subcategorías, como género, año o país, lo que facilita filtrar y mostrar las secciones de la pantalla principal.

3. Facebook

Grafos y listas enlazadas.

 investigando vi que cada usuario es un nodo y cada amistad es una arista que conecta a dos personas. Por eso la aplicación puede sugerir "personas que quizás conozcas", buscando amigos de tus amigos que todavía no están conectados contigo. Por otro lado, el muro de publicaciones funciona como una lista, donde cada publicación nueva se agrega y se va mostrando de la más reciente a la más antigua a medida que haces scroll.
