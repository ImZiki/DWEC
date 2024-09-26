# Proyecto 1 DWEC
## Arcade Alley
<img src="src/images/logoArcAll.jpeg" alt="drawing" width="500"/>

### Idea de la aplicacion
Una plataforma social para jugadores de videojuegos donde poder encontrar a gente con los mismos intereses, nivel de habilidad, horarios, preferencias, etc.


### Audiencia objetivo
Jugadores de videojuegos de cualquier plataforma actual y antigua con la necesidad de conocer o formar comunidades basadas en sus juegos favoritos.


### Analisis de mercado y propuesta de valor
#### Analisis de los rivales directos
#### Steam

**Fortalezas**:
Comunidad gigantesca de jugadores activos.
Sistema integrado con los juegos (listas de amigos, logros, mods, etc.).
Foros específicos para cada juego que facilitan la resolución de problemas y la interacción directa con desarrolladores.

**Debilidades**:
Las funciones sociales son secundarias; Steam se centra principalmente en la compra y distribución de juegos.
Las discusiones en los foros pueden ser desorganizadas o saturadas, lo que dificulta mantener la atención del usuario.
Falta de personalización en las interacciones sociales o sistemas complejos de interacción en tiempo real.

#### Reddit

**Fortalezas**
Comunidad masiva y diversa.
Amplia gama de subcomunidades dedicadas a juegos específicos.
Funcionalidad de votación que promueve el contenido relevante

**Debilidades**
Las funciones sociales son secundarias; Steam se centra principalmente en la compra y distribución de juegos.
Las discusiones en los foros pueden ser desorganizadas o saturadas, lo que dificulta mantener la atención del usuario.
Falta de personalización en las interacciones sociales o sistemas complejos de interacción en tiempo real.

#### Propuesta de diferenciación
- Integración de múltiples medios de interacción: Combinar lo mejor de los foros de discusión de Reddit (interacción estructurada, votaciones y publicaciones largas) y las funcionalidades de comunidad de Steam (sistemas de reseñas).

- Sistemas de recompensas y gamificación: Introducir un sistema de logros, recompensas o puntos por participar en la comunidad, algo que no está presente en Reddit o Steam de manera integrada. Esto puede incentivar el compromiso a largo plazo.


- Organización de eventos y torneos: Ofrecer funciones específicas para la organización de torneos y eventos en línea, lo cual es limitado en Reddit o Steam.


#### Aportación de valor
- Curación de contenido: Mientras que Reddit pueden ser caóticos y difíciles de seguir debido a la naturaleza abierta y desorganizada del contenido, Arcade Alley se podría centrar en la curación de contenido de calidad, destacando las mejores guías, reseñas y discusiones. 
  
  Ejemplo: Moderadores o algoritmos que identifiquen contenido valioso y lo presenten de manera prominente, lo que aumenta la visibilidad y utilidad de las publicaciones importantes.
- Herramientas sociales mejoradas: Mientras que Steam se centra principalmente en la funcionalidad básica de amigos y comunicación, Arcade Alley podría centrarse en un enfoque más profundo en las conexiones sociales entre jugadores.
  
  Ejemplo: Perfiles de jugadores más avanzados, con estadísticas, historia de juegos jugados, recomendaciones personalizadas de amigos y eventos.

- Multiplataforma con integración social: Facilitar una mejor integración entre plataformas. Si bien Steam ofrece funcionalidades limitadas en dispositivos móviles, una plataforma web optimizada para móvil con un enfoque en comunidad podría llenar este vacío.
  
  Ejemplo: Posibilidad de sincronizar cuentas de Steam y otros servicios, permitiendo una experiencia social unificada y centralizada.

### Funcionalidades clave
1. Creacion de cuentas

    Sea mediante el clasico correo electronico + contraseña o aprovechando la API de Steam y usando su sistema de login para vincular la cuenta de Steam a la de Arcade Alley.

2. Panel de control de usuario

    Lugar donde ver y editar los detalles que se muestren o no al publico en tu perfil de usuario.


3. Sistema de comunidades

    Siguiendo un poco los modelos de Steam y Reddit en tanto en cuanto a que están divididas por tematica especifica o por videojuego.

4. Buscador / Boton de "Recomiendame una comunidad nueva".
    
    Las comunidades tendrán una puntuacion que los usuarios iran granjeando cumpliendo ciertos criterios de actividad de sus juegos recientes mediante la API de Steam, retos propuestos a las comunidades, etc. Al pulsar dicho boton de recomendación o buscar comunidades por un juego concreto, las comunidades con mayor puntuacion tendrán mayor posibilidad de aparecer recomendadas antes que otras 

    Esta puntuación se reseteará cada primero de mes.

5. Gestor de comunidades

    Los administradores/creadores de las comunidades podrán hacerlas publicas o privadas mediante un sistema whitelist de peticion de admision donde recibirán un informe completo de la cuenta del usuario solicitante donde podrán ver un historial de comportamiento entre otros datos.

6. Sistema de logros
    
    Sistema de logros que se irán adquiriendo con la veteranía en Arcade Alley o mediante completar retos o actividad reciente, datos de los juegos que tengan en la cuenta de Steam mediante su API si el perfil fuese publico etc.



### Tecnologias a utilizar
Front-end:
- HTML5
- CSS3
- React.js

Back-end:
- BD con MySQL
- Java Spring boot.



### Un análisis de los modelos de ejecución cliente/servidor, incluyendo ejemplos y comparaciones.

### La evaluación de los lenguajes de programación web seleccionados, destacando sus ventajas y desventajas.

### Un estudio sobre la compatibilidad en navegadores, identificando posibles problemas y soluciones, y cómo estas consideraciones afectan la elección de tecnologías.

### Un análisis de los mecanismos de integración de los lenguajes de marcas con los lenguajes de programación de clientes web.

### La evaluación de herramientas de programación para clientes web, explicando sus funciones y ventajas distintivas.


### Links de interes/referencias
#### APIs de Steam mencionadas en las funcionalidades clave
- [API Steam](https://steamcommunity.com/dev?l=spanish)
- [API ISteamNews](https://developer.valvesoftware.com/wiki/Steam_Web_API#GetNewsForApp_.28v0001.29)
- [API ISteamUserStats](https://developer.valvesoftware.com/wiki/Steam_Web_API#GetGlobalAchievementPercentagesForApp_.28v0001.29)
- [API ISteamUser ](https://developer.valvesoftware.com/wiki/Steam_Web_API#GetPlayerSummaries_.28v0001.29)
#### API de Epic Games mencionada en funcionalidades clave
- [API Free Epic Games](https://rapidapi.com/kwik-api-kwik-api-default/api/free-epic-games)
- [APIs generales de Epic Games](https://dev.epicgames.com/docs/web-api-ref)
