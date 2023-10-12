# Arquitectura de Software 👷 [Sicer Andres Brito Gutierrez](https://github.com/SicerBrito)
# Practica y desarrollo de una Arquitectura de Software  
![SylvesterSilvestreGIF](https://github.com/SicerBrito/Arquitectura-De-Software/assets/126881720/25a764f7-63e5-4443-ab59-05c18738f577)

## 1. ¿Qué es la arquitectura de software? 🚧👷
La arquitectura de softrware es el diseño de más alto nivel de la estructura de un sistema, pero no existe un solo concepto para definirlo con exactitud por el contrario, existen diversas fuentes con diferentes definiciones.


La arquitectura de software se refiere a la estructura y diseño de un programa informático. Es como el plano de una casa que define cómo se organizarán y conectarán sus componentes. Existen de demasiadas arquitecturas de software, aqui hay algunos ejemplos de las mas comunes o mas utilizadas:

---

 - 🚧 ***Arquitectura de tres capas:*** Es una de las arquitecturas más comunes y se utiliza en una amplia variedad de aplicaciones web y empresariales. La arquitectura de tres capas divide una aplicación en tres partes principales: la interfaz de usuario, la lógica de negocios y la capa de datos.  

    Ejemplo: una aplicación web con una interfaz de usuario, un servidor que maneja la lógica y una base de datos que almacena información.

---

 - 🚧 ***Arquitectura cliente-servidor:*** Esta arquitectura es fundamental en la mayoría de las aplicaciones que involucran interacción entre clientes y servidores, como aplicaciones web y bases de datos. En esta arquitectura, los clientes (como navegadores web) solicitan recursos y servicios a un servidor central. 
 
    Ejemplo: un navegador web que solicita páginas web a servidores remotos.

---

 - 🚧 ***Arquitectura de microservicios:*** Ha ganado popularidad en los últimos años debido a su capacidad para crear aplicaciones escalables y flexibles. Se utiliza en aplicaciones distribuidas y sistemas empresariales modernos. Divide una aplicación en pequeños servicios independientes que se comunican entre sí. 
    
    Ejemplo: una plataforma de comercio electrónico donde un servicio gestiona el catálogo de productos y otro maneja el carrito de compras.

---

 - 🚧 ***Arquitectura orientada a servicios (SOA):*** Se utiliza en entornos empresariales para crear sistemas flexibles y modulares. En SOA, los componentes de software se organizan como servicios independientes que pueden comunicarse entre sí a través de estándares como el Protocolo de Acceso a Objetos Distribuidos (SOAP) o REST (Transferencia de Estado Representacional).

---

 - 🚧 ***Arquitectura basada en componentes:*** Es común en el desarrollo de aplicaciones que requieren reutilización de componentes, como aplicaciones de desarrollo rápido. Divide la aplicación en componentes reutilizables que se pueden ensamblar para construir sistemas más grandes. 
    
    Ejemplo: aplicaciones de desarrollo rápido.

---

 - 🚧 ***Arquitectura de una capa (Single-Layer) y Arquitectura de dos capas (Two-Tier):*** Aunque más simples, estas arquitecturas aún se utilizan en aplicaciones más pequeñas o específicas, como scripts y aplicaciones de escritorio básicas.

     - Arquitectura de una capa (Single-Layer):

        Divide la aplicación en componentes reutilizables que se pueden ensamblar para construir sistemas más grandes. Ejemplo: aplicaciones de desarrollo rápido.

     - Arquitectura de dos capas (Two-Tier):

        También conocida como arquitectura de dos niveles, separa la aplicación en dos capas principales: la interfaz de usuario y la capa de datos. Por ejemplo, una aplicación de escritorio que interactúa con una base de datos local sigue una arquitectura de dos capas.


> Es importante destacar que la elección de la arquitectura depende en gran medida de los requisitos del proyecto y de la escala y complejidad de la aplicación que se está desarrollando. Cada una de estas arquitecturas tiene sus propias ventajas y desventajas, y su idoneidad varía según el contexto. Estos solo fueron algunos ejemplos, existen muchas otras arquitecturas y variaciones específicas diseñadas para abordar desafíos particulares o satisfacer necesidades específicas en diversos dominios de desarrollo de software.


---

## 2. ¿Qué son los patrones de diseño? 📉✍️

Los patrones de diseño son soluciones a problemas comunes en el desarrollo de software. Son soluciones que han sido probadas y utilizadas por otros desarrolladores, y que se han demostrado que son efectivas. Estas soluciones son desarrolladas y compartidas por la comunidad de desarrollo de software para ayudar a los programadores a abordar problemas recurrentes de manera eficiente y efectiva.

 - Los patrones de diseño se clasifican en tres categorías principales:

     - ***Creacional:***  

        Estos patrones se centran en la creación de objetos.

        ---

     - ***Estructural:***  

        Estos patrones se centran en la composición de objetos.

        ---

     - ***Comportamental:***  

        Estos patrones se centran en la interacción entre objetos.

        ---

 - Algunos ejemplos de patrones de diseño son:

     - ***Singleton:***
        
        Este patrón garantiza que solo exista una instancia de una clase en un programa.
    
        ---

     - ***Factory:***
        
        Este patrón proporciona una forma de crear objetos sin exponer la lógica de creación.
    
        ---
        
     - ***Adapter:***
        
        Este patrón permite que dos clases que no son compatibles puedan trabajar juntas.
    
        ---

     - ***Decorator:***
        
        Este patrón permite agregar características adicionales a un objeto sin modificar su estructura.
    
        ---

     - ***Command:***
        
        Este patrón permite descomponer una tarea compleja en una serie de comandos más simples.

        ---

    > Los patrones de diseño pueden ser una herramienta valiosa para los desarrolladores de software. Pueden ayudar a los desarrolladores a crear código más eficiente, reutilizable y fácil de mantener.

    ### Para qué sirven los patrones de diseño

    #### Los patrones de diseño sirven para:

     - ***Resolver problemas comunes:***
        
        Los patrones de diseño proporcionan soluciones a problemas comunes que han sido probados y utilizados por otros desarrolladores.
    
        ---

     - ***Mejorar la calidad del código:***
        
        Los patrones de diseño pueden ayudar a los desarrolladores a crear código más eficiente, reutilizable y fácil de mantener.
    
        ---

     - ***Facilitar la comunicación:***
        
        Los patrones de diseño proporcionan un vocabulario común que puede ayudar a los desarrolladores a comunicarse entre sí de manera más efectiva.
        
        ---

    #### Cómo utilizar los patrones de diseño

    Los patrones de diseño se pueden utilizar de varias maneras. Una forma es utilizar un libro o un sitio web que proporcione descripciones de los patrones de diseño. Otra forma es utilizar un IDE que incluya soporte para patrones de diseño.

    Una vez que haya aprendido sobre los patrones de diseño, puede comenzar a utilizarlos en su propio código. Una buena manera de empezar es identificar un problema que necesita resolver. Luego, puede buscar un patrón de diseño que pueda resolver ese problema.

    #### Patrones de diseño web

    Los patrones de diseño web son un subconjunto de los patrones de diseño que se utilizan en el desarrollo de sitios web y aplicaciones web. Estos patrones se centran en la creación de interfaces de usuario que sean eficientes, fáciles de usar y accesibles.

    #### Algunos ejemplos de patrones de diseño web son:

     - ***Layout:***
        
        Estos patrones se centran en la disposición de los elementos de una página web.
    
        ---

     - ***Interacción:***
        
        Estos patrones se centran en la interacción entre el usuario y la página web.
    
        ---

     - ***Comunicación:***
        
        Estos patrones se centran en la comunicación entre la página web y el servidor.
    
        ---

    Los patrones de diseño web pueden ser una herramienta valiosa para los desarrolladores web. Pueden ayudar a los desarrolladores a crear sitios web y aplicaciones web que sean más fáciles de usar y accesibles.



---

## 3. ¿Qué son los estilos arquitectónicos? 👨‍💼🏗️

Los estilos arquitectónicos son conjuntos de características que identifican la tendencia artística de una época o de un autor. Estas características pueden incluir elementos como la forma, la estructura, los materiales, los colores y los ornamentos.

 -  ### Los estilos arquitectónicos se pueden clasificar de varias maneras, incluyendo:

    - ***Por época:***
        
        Los estilos arquitectónicos pueden clasificarse según la época en la que se desarrollaron. Por ejemplo, el estilo gótico se desarrolló en Europa durante la Edad Media, mientras que el estilo moderno se desarrolló en el siglo XX.

        ---

    - ***Por región:***
        
        Los estilos arquitectónicos también pueden clasificarse según la región en la que se desarrollaron. Por ejemplo, el estilo mudéjar se desarrolló en la península ibérica durante la Edad Media, mientras que el estilo colonial se desarrolló en América durante el período colonial.

        ---

    - ***Por autor:***
        
        Los estilos arquitectónicos también pueden clasificarse según el autor que los desarrolló. Por ejemplo, el estilo de Frank Lloyd Wright se caracteriza por sus formas orgánicas y sus espacios 
        abiertos.

        ---

 -  ### Algunos ejemplos de estilos arquitectónicos incluyen:

    - ***Arquitectura clásica:***
        
        Este estilo se caracteriza por sus formas simétricas y proporciones equilibradas.

        ---

    - ***Arquitectura gótica:***
        
        Este estilo se caracteriza por sus arcos apuntados, sus vitrales y sus torres altas.

        ---

    - ***Arquitectura renacentista:***
        
        Este estilo se caracteriza por su énfasis en la proporción, la simetría y la perspectiva.

        ---

    - ***Arquitectura barroca:***
        
        Este estilo se caracteriza por su uso de líneas curvas, ornamentos exuberantes y efectos dramáticos.

        ---

    - ***Arquitectura neoclásica:***
        
        Este estilo se caracteriza por su resurgimiento de los principios de la arquitectura clásica.

        ---

    - ***Arquitectura modernista:***
        
        Este estilo se caracteriza por su énfasis en la funcionalidad, la simplicidad y la pureza de formas.

        ---
        
Los estilos arquitectónicos pueden tener un impacto significativo en el aspecto y la sensación de un edificio. También pueden reflejar las ideas y valores de la época o la región en la que se desarrollaron.

>***Importancia de los estilos arquitectónicos***  
>Los estilos arquitectónicos son importantes por varias razones. En primer lugar, pueden ayudarnos a comprender la historia y la cultura de una época o región. En segundo lugar, pueden inspirarnos a crear nuevos diseños arquitectónicos. En tercer lugar, pueden ayudarnos a apreciar la belleza y la complejidad de la arquitectura.

---

## 4. Patrones de diseño y Patrones arquitectónicos 📉💾

---

## 5. Conceptos Ingeneria de Software