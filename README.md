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

![aaa](https://user-images.githubusercontent.com/31961588/273664281-a1926874-7e0c-4f35-bb59-eaa8c749eb65.png)

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

Los estilos arquitectónicos en programación son patrones generales de diseño que se pueden utilizar para estructurar sistemas de software. Estos estilos proporcionan una guía para la selección de componentes, la comunicación entre componentes y la interacción con el entorno.

Los estilos arquitectónicos se pueden clasificar en dos categorías principales:

 - ***Estilos arquitectónicos de composición:***
   
   Estos estilos se basan en la composición de componentes para crear un sistema. Los componentes pueden ser módulos, objetos o servicios.

   ---

 - ***Estilos arquitectónicos de distribución:***
   
   Estos estilos se basan en la distribución de componentes en diferentes máquinas.

   ---

Los estilos arquitectónicos son importantes por las siguientes razones:

 - Ayudan a garantizar que el sistema cumpla con los requisitos. El estilo arquitectónico debe definir cómo el sistema cumplirá con los requisitos funcionales y no funcionales.

   ---

 - Mejoran la calidad del sistema. Un buen estilo arquitectónico puede ayudar a mejorar el rendimiento, la escalabilidad, la facilidad de mantenimiento y otros atributos de calidad.

   ---

 - Reducen los costos de desarrollo y mantenimiento. Un estilo arquitectónico bien diseñado puede hacer que el sistema sea más fácil de desarrollar, mantener y actualizar.

   ---

Los estilos arquitectónicos son una herramienta importante para el desarrollo de sistemas de software exitosos. Al seleccionar el estilo arquitectónico adecuado, los equipos de desarrollo pueden mejorar la calidad, el rendimiento y la facilidad de mantenimiento de sus sistemas.


![Estilo Arquitectonico](https://user-images.githubusercontent.com/31961588/273671383-ded4fc19-ef72-4c8f-bf8b-edff99344e78.png)

---

## 4. Patrones de diseño y Patrones arquitectónicos 📉💾

La principal diferencia entre patrones de diseño y patrones arquitectónicos es el nivel de abstracción al que se aplican. Los patrones de diseño se aplican a un nivel más bajo, a la estructura y el comportamiento de clases y objetos individuales. Los patrones arquitectónicos se aplican a un nivel más alto, a la estructura y el comportamiento de sistemas enteros.

En términos prácticos, esto significa que los patrones de diseño se utilizan para resolver problemas específicos en el diseño de software, como la creación de objetos, la composición de objetos o la interacción entre objetos. Los patrones arquitectónicos se utilizan para definir la estructura general de un sistema de software, como la división del sistema en subsistemas, la comunicación entre subsistemas o la escalabilidad del sistema.

![222](https://user-images.githubusercontent.com/31961588/273667021-a4a09ebc-94fc-46b7-aa5a-016ed21a2059.png)

---

## 5. Conceptos Ingeneria de Software

La ingeniería de software es una disciplina compleja y en constante evolución. Los conceptos básicos de la ingeniería de software proporcionan una base sólida para el desarrollo de software exitoso que se ocupa del desarrollo de software, desde la concepción hasta la implementación y el mantenimiento.

 - ### Atributos de calidad de software

   Los atributos de calidad de software son las características que determinan la calidad de un sistema de software. Estos atributos pueden clasificarse en dos categorías principales: 

      - atributos funcionales
         
         ---

      - atributos no funcionales.

         ---

 - ### Atributos funcionales

   Los atributos funcionales son aquellos que determinan lo que hace un sistema de software. Estos atributos incluyen:

   - Corrección:
      
      El sistema cumple con los requisitos funcionales.

      ---

   - Completitud:
      
      El sistema incluye todas las funciones necesarias.

      ---

   - Precisión:
      
      El sistema produce resultados exactos.

      ---

   - Usabilidad:
      
      El sistema es fácil de usar.

      ---

   - Eficiencia:
      
      El sistema utiliza los recursos de manera eficiente.

      ---

 - ### Atributos no funcionales

   Los atributos no funcionales son aquellos que determinan cómo funciona un sistema de software. Estos atributos incluyen:


   - Requisitos de rendimiento:
      
      El sistema debe cumplir con ciertos requisitos de rendimiento, como la velocidad, la respuesta y la capacidad de respuesta.

      ---

   - Requisitos de seguridad:
      
      El sistema debe estar protegido de la manipulación, el acceso no autorizado y otros ataques.

      ---

   - Requisitos de confiabilidad:
      
      El sistema debe funcionar correctamente durante un período de tiempo determinado.

      ---

   - Requisitos de mantenibilidad:
      
      El sistema debe ser fácil de mantener y actualizar.

      ---

   - Requisitos de portabilidad:
      
      El sistema debe poder ejecutarse en diferentes plataformas y entornos.

      ---

 - ### Acoplamiento y cohesión

   El acoplamiento y la cohesión son dos conceptos relacionados con la estructura de un sistema de software.

   - #### Acoplamiento

      El acoplamiento es el grado de dependencia entre dos unidades de software. Un acoplamiento alto significa que dos unidades de software están fuertemente relacionadas entre sí. Un acoplamiento bajo significa que dos unidades de software están débilmente relacionadas entre sí.

      Un alto acoplamiento puede dificultar el mantenimiento del software, ya que los cambios en una unidad de software pueden requerir cambios en otras unidades de software.

      ---

   - #### Cohesión

      La cohesión es el grado de relación entre las partes de una unidad de software. Una cohesión alta significa que las partes de una unidad de software están estrechamente relacionadas entre sí. Una cohesión baja significa que las partes de una unidad de software están débilmente relacionadas entre sí.

      Una alta cohesión puede facilitar el mantenimiento del software, ya que los cambios en una unidad de software solo requieren cambios en otras partes de la misma unidad de software.
      
      ---

 - ### SOLID

   SOLID es un acrónimo que representa cinco principios de diseño de software que promueven la buena calidad del software. Estos principios son:

    - ***S - Single Responsibility Principle (SRP):***
   
      Cada clase o función debe tener una sola responsabilidad.

      ---

    - ***O - Open-Closed Principle (OCP):***
   
      Un sistema debe ser abierto a la extensión, pero cerrado a la modificación.

      ---

    - ***L - Liskov Substitution Principle (LSP):***
   
      Las instancias de clases derivadas deben poder usarse en lugar de instancias de clases base.

      ---

    - ***I - Interface Segregation Principle (ISP):***
   
      Las interfaces deben ser lo más estrechas posible.

      ---

    - ***D - Dependency Inversion Principle (DIP):***
   
      Las clases dependientes no deben depender de clases concretas, sino de interfaces.

      ---


   Estos principios pueden ayudar a los desarrolladores de software a crear sistemas de software que sean más fáciles de entender, mantener y modificar.