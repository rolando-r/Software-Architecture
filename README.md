<div align="center">
  <h1>SOFTWARE ARCHITECTURE</h1>
  <a href="URL_DEL_ENLACE"><img src="https://cdn-images-1.medium.com/max/1200/1*DenJfjmLJ5drVjPLTqkHzQ.png" alt="Imagen"></a>
</div>
<div>
    <h2 align="center"><a href="https://www.youtube.com/watch?v=7ukajubprdE&list=PLFHx3afTdaY0hvX2NXRxMVM3j5sk-3aE3&index=2">Definitions 📚</a></h2>
      <p>• The software architecture of a system is the set of structures necessary to reason about the system.</p>
      <p>• It is the set of design decisions important to organize the software and promote the desired quality attributes.</p>
      <p>• Architecture is about the important things. Whatever they are.</p>
</div>
  
  <h2 align="center">What are design patterns? 📐</h2>
      
  <h4><a href="https://www.youtube.com/watch?v=pk-lawTRbmg">What are?</a></h4>
  <p>A pattern is a solution to a problem in a context.</p>

  <h4>Patterns System  P.O.S.A (Pattern-Oriented Software Architecture)</h4>
  <p>• Architectural patterns: Expresses an essential structural organization scheme for a software system, consisting of subsystems, their responsibilities and interrelationships.</p>
  <p>• Design patterns: A design pattern is one that describes a recurring structure for communicating components, which solves a general design problem in a particular context.</p>
  <h5>Creation patterns: They abstract the process of creating objects. They give a lot of flexibility in deciding what objects are created, who creates them, how they are created and when (Singleton, Factory Method, Abstract Factory, Builder and Prototype).</h5>
  <h5>Structure patterns: They organize classes to create more complex structures; Keeps the structure flexible and efficient (Adapter, Bridge, Composite, Decorator, Facade, Flyweight and Proxy).</h5>
  <h5>Behavior patterns: They specialize in algorithms and the assignment of responsibilities between objects. They describe how objects communicate with each other (Chain of responsibility, Command, Interpreter, Iterator, Mediator, Memento, Observer, State, Strategy, Template Method and Visitor).</h5>

  <h4><a href="https://www.youtube.com/watch?v=8HvzNnh4oeA">Design patterns and architectonics patterns</a></h4>
  <img src="https://i.postimg.cc/BQdG6sPW/Captura-de-pantalla-2023-10-11-080840.png">
  <p>• Design patterns: Design patterns are reusable solutions to common problems in software design, originating from the collective experience of software designers, formalized by the "Gang of Four" in their 1994 book. They consist of a structure with a name, problem, solution, and consequences, categorized into creation, structure, and behavior patterns. Examples include Singleton, Factory Method, Adapter, Composite, and Observer. Applying these patterns results in more flexible, maintainable, and scalable code. It's essential to apply them consciously and adapt to the project's specific needs..</p>
  <p>• Design patterns: Architectural patterns are reusable solutions to common structural challenges in software design, drawing from the collective experience of architects. They encompass a structure comprising a name, problem, solution, and consequences, categorized into creation, structure, and behavior patterns. Examples include Model-View-Controller (MVC), Microservices, and Layered Architecture. Applying these architectural patterns yields more scalable, maintainable, and adaptable software. It's crucial to apply them thoughtfully, tailoring them to the specific requirements of the project.</p>

  <h4><a href="https://www.youtube.com/watch?v=VyMRGf0Dji4&list=PLFHx3afTdaY3pAFWNUEJRCeiIw4raCi3U&index=10">What is the difference between design patterns and architectural patterns</a></h4>

  <p>• Design Patterns: Design patterns are solutions to recurring problems at the level of objects and classes in software design. They provide reusable templates for solving common issues related to object creation, composition, and interaction. Examples of design patterns include Singleton, Factory Method, and Observer. These patterns focus on improving the structure and efficiency of code within a module or a class.</p>
  <p>• Architectural Patterns: Architectural patterns, on the other hand, deal with high-level structures and organization of an entire software application. They address issues related to the overall system architecture, such as the distribution of responsibilities, the arrangement of components, and the flow of data between them. Examples of architectural patterns include Model-View-Controller (MVC), Microservices, and Layered Architecture. Architectural patterns guide the organization and design of the entire software system.</p>
  <p>• Key Differences: Design patterns operate at a lower level, addressing class and object concerns, while architectural patterns operate at a higher level, dealing with the organization of the entire system. Design patterns handle specific design problems, while architectural patterns tackle broader structural issues.</p>

  <h4><a href="https://www.youtube.com/watch?v=87lBMvk75eM&list=PLFHx3afTdaY0KR3h_NVjoWajr2OLRiqPv">What are the architectural patterns for?</a></h4>
  <p>Architectural patterns are reusable models that provide proven and effective solutions to common problems in system and application design at an architectural level. These patterns offer a structured guide for organizing and relating various components within a system.</p>

  <h3>How to differentiate an architectural pattern?</h3>
  <p>Architectural patterns are easily recognizable due to their global impact on the application, dictating the way components work and communicate. Any change to these patterns directly affects the component and, potentially, related components. A common example is the "Three-Tier Architecture," which separates the application into presentation, business, and data layers.</p>
  <div align="center">
    <img src="https://i.postimg.cc/FRHnJvdw/Captura-de-pantalla-2023-10-11-204652.png" alt="Descripción opcional">
  </div>
  <p>In this model, each layer has a specific task: presentation generates views, business implements logic, and data interacts with the database. If one layer fails, the application experiences a total failure. Changing the pattern after building the application has a significant impact, requiring modifications to all views, business logic, and possibly the database interaction. This alteration not only affects the component itself but may also have repercussions on other components, even those external to the domain, further complicating the situation.</p>
  <p>Furthermore, there is the option of "Four-Tier Architecture," which adds an additional layer for service management. In this case, the service layer handles shared application logic and common services, providing greater modularity. This approach can address more complex applications and offer increased flexibility. However, any changes to the 4-layer structure will also have a significant impact on the application, so the choice of architectural pattern should be carefully considered from the early stages of development.</p>
  <div align="center">
    <img align="center" src="https://i.postimg.cc/xdxB5q29/Captura-de-pantalla-2023-10-11-205119.png">
  </div>
  <h2 align="center">What are the architectural styles 🏰</h2>

  <p>A style describes a type of architecture or pieces of it. Styles can be reused in similar situations in the future.</p>
  <p>What are they for?: They define a semantics for the composition rules of the elements. They enable the analysis of systems built on style.</p>

  <h4>Elements</h4>
  <p>• Processing: Provides the transformation of data.</p>
  <p>• Data: Contains the information to be processed.</p>
  <p>• Connection: Procedure calls, messages.</p>
  <p>• Form: The properties and relationships between elements.</p>
  <p>• Reason: Motivation for the choice of elements and their shapes.</p>

  <h4>Style catalog</h4>

  <p>• Data-centric architecture (whiteboard architectures, Data Warehouse).</p>
  <p>• Data flow architecture (Pipes and Filters, sequential batch processing).</p>
  <p>• Call and return architectures (remote procedure calls, Model-View-Controller).</p>
  <p>• Object-oriented architectures.</p>
  <p>• Aspect-oriented architectures.</p>
  <p>• Service-oriented architectures (SOA).</p>
  <p>• Layered architectures.</p>
  
  <p><a href="https://www.youtube.com/watch?v=PK9TTcTosTw">Software architecture styles 🎥</a></p>
  <h3>The relationship between design, architectural patterns and architectural styles</h3>
  
  <p>Distinguishing between design patterns, architectural patterns, and architectural styles can be a challenge for many software architects. The attached image clarifies the relationship between these concepts.</p>
  <div align="center">
    <img src="https://i.postimg.cc/nVQs7P8P/Captura-de-pantalla-2023-10-11-215536.png">
  </div>
  <p>The hierarchy reveals that architectural styles form the foundation, facilitating the implementation of architectural patterns, which, in turn, can incorporate design patterns. This hierarchical structure highlights the specialization of each level, from the most general to the most specific.</p>
  <p>It is crucial to understand that architectural patterns address recurring problems, while architectural styles provide frameworks for common designs. Confusing the two can result in design and implementation errors.</p>
  <p>Although interconnected, the distinction between these concepts is vital. This report emphasizes the need to focus on learning architectural styles and patterns, excluding design patterns for those who already master them.</p>
  

  <h2 align="center">Design patterns 🎨</h2>
  <p>Examples in design patterns in Java</p>
  
  ```mermaid
    flowchart TD
    A[Patrones de Diseño <a href='https://www.youtube.com/watch?v=cwfuydUHZ7o&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=1'>Video</a>] --> B[Creación]
    A -->C[Structural]
    A -->D[Behavior]
    B -->E[Sigleton <a href='https://www.youtube.com/watch?v=gocJeOHtj9w&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=2'>Video</a>] 
    B -->F[Factory  <a href='https://www.youtube.com/watch?v=R6Ef64hDwGo&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=3'>Video</a>]
    B -->G[Abstract Factory <a href='https://www.youtube.com/watch?v=QmE-o5R7ZF4&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=4'>Video</a>]
    B -->H[Prototype <a href='https://www.youtube.com/watch?v=M3VT1v54cq4&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=5'>Video</a>]
    C -->I[Proxy <a href='https://www.youtube.com/watch?v=LUJbqdthTzA&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=8'>Video</a>]
    C -->J[Facade <a href='https://www.youtube.com/watch?v=6dYwdDbhpwQ&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=6'>Video</a>]
    D -->k[Memento <a href='https://www.youtube.com/watch?v=Q5CL1b-FD9E&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=10'>Video</a>]
    D -->O[Command <a href='https://www.youtube.com/watch?v=hDBOfyzFKEU&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=9'>Video</a>]
    D -->P[Observer <a href='https://www.youtube.com/watch?v=QiKrKNTdGGs&list=PLvimn1Ins-41Uiugt1WbpyFo1XT1WOquL&index=11'>Video</a>]
  ```
  <div>

  <h4>Abstract Factory in C# (Creational)</h4>
  <div align="center">
    <img src="https://www.dofactory.com/img/diagrams/net/abstract.png">
    <p>The diagram illustrates a simple network with two nodes: a web server and a web client connected by a link using the HTTP protocol for web page transmission. Nodes represent devices, links denote connections between them, and protocols set standards for data exchange. This is a basic example of an abstract network diagram, useful for representing networks of any size and complexity. Examples of protocols include HTTP for web pages, TCP/IP for most communications, and Ethernet for local area networks.</p>
  </div>
  <h4>Builder in C# (Creational)</h4>
  <div align="center">
    <img src="https://indiedevart.files.wordpress.com/2016/06/l1.png">
    <p>Class diagram for the C# Builder design pattern, facilitating the creation of enemies with unique characteristics. The abstract class "EnemyCreator" defines the interface, while the concrete classes "EnemyTypeA" and "EnemyTypeB" implement the creation of enemies with distinct properties. The "ConstructEnemy()" method in "EnemyCreator" coordinates the selection of model, behavior, and components. In summary, the Builder pattern is employed to create diverse enemies through specialized classes.</p>
  </div>
  <h4>Adapter in C# (Structural)</h4>
  <div align="center">
    <img src="https://www.dofactory.com/img/diagrams/net/adapter.png">
    <p>Class diagram for the Adapter design pattern, facilitating collaboration between two classes with incompatible interfaces. The "Adapter" class inherits from "Adaptee" and implements the "Target" interface, acting as an intermediary. In the diagram, the "Client" class uses the "Request()" method of the "Adapter," which, in turn, delegates the request to the "SpecificRequest()" method of the "Adaptee." In summary, the Adapter pattern enables two classes with different interfaces to work together seamlessly.</p>
  </div>
  <h4>Factory Method in C# (Creational)</h4>
  <div align="center">
    <img src="https://n7b3p4s2.stackpathcdn.com/article/factory-design-pattern-in-c-sharp/Images/Attribute.jpg">
    <p>The Factory Pattern, a creational design pattern, enables flexible and decoupled object creation by centralizing the process through an interface, the VehicleFactory, with Concrete Factories (CarFactory, BykeFactory, RickshawFactory) responsible for creating specific types of vehicles (Car, Byke, Rickshaw). The FactoryDemo class illustrates its application for creating Vehicle objects, promoting code reuse and maintainability. Widely used in C# and other languages, this pattern provides flexibility and extensibility for efficiently creating objects in a decoupled manner.</p>
  </div>

    
  <h2 align="center">Concepts of Software Engineering 🖥️</h2>

  <h3>Software quality atrributes</h3>
  
  <h4>What is?</h4>
  <p>Software quality attributes are characteristics that assess its performance and usefulness. They include aspects such as functionality, reliability, usability, efficiency, maintainability, portability, security, and adaptability. These criteria help determine the overall quality of the software in terms of meeting requirements, avoiding errors, being user-friendly, efficient, modifiable, adaptable to different environments, secure, and capable of handling changes.</p>
  <h4>The most common attributes</h4>
    <ul>
        <li>Deployability (ease of deployment).</li>
        <li>Availability.</li>
        <li>Scalability.</li>
        <li>Interoperability.</li>
        <li>Modifiability.</li>
        <li>Performance.</li>
        <li>Security.</li>
        <li>Testability (ease of testing the system).</li>
        <li>Usability.</li>
    </ul>

  <h4>Other quality attributes</h4>
    <ul>
        <li>Accessibility.</li>
        <li>Adaptability.</li>
        <li>Agility.</li>
        <li>Reliability.</li>
        <li>Compliance with standards (depending on the industry and user needs).</li>
        <li>Distributed development. Does the system design allow separate teams globally to work on it?</li>
        <li>Elasticity.</li>
        <li>Extensibility.</li>
        <li>Ease of development.</li>
        <li>Ease of installation.</li>
        <li>Feasibility. Is what is intended feasible according to time and budget?</li>
        <li>Internationalization (i18n).</li>
        <li>Localization (l10n).</li>
        <li>Marketability. Is the system built with technologies that the market considers attractive and modern?</li>
        <li>Maintainability.</li>
        <li>Mobility.</li>
        <li>Modularity.</li>
        <li>Monitorability.</li>
        <li>Portability.</li>
        <li>Recoverability.</li>
        <li>Reusability.</li>
        <li>Fault tolerance.</li>
        <li>Variability.</li>
    </ul>
  <h4>Attributes and architecture patterns</h4>

  <p>In the dynamic landscape of software development, the proper selection of architecture attributes and patterns is crucial to achieve efficient and sustainable systems. This report explores the significance of these elements in designing robust architectures and provides an in-depth view of some key attributes and relevant architectural patterns.</p>
  <h5>Architecture Attributes</h5>
  <ul>
    <li>Adaptability: The system's ability to evolve and adjust to changes in the operational environment or user requirements without compromising its integrity.</li>
    <li>Fault Tolerance: The system's capability to maintain acceptable performance and functionality in the presence of failures or disruptions.</li>
    <li>Elasticity: The ability to dynamically scale resources in response to changes in workload, enabling efficient resource utilization.</li>
  </ul>
  <h5>Architecture Patterns</h5>
  <ul>
    <li>Cloud Architecture: Designing the system to leverage cloud services, enabling scalability, availability, and flexibility.</li>
    <li>Microservices Architecture: Breaking down the system into independent and autonomous components, facilitating deployment, updates, and maintenance.</li>
    <li>Serverless Architecture: Developing applications without managing the underlying infrastructure, providing greater agility and reducing operational overhead.</li>
  </ul>
  <h5>Emerging Challenges</h5>
  <ul>
    <li>Sustainability: Integrating architectural practices that minimize environmental impact, considering energy efficiency and responsible resource usage.</li>
    <li>Ethics in Architecture: Considering ethical principles in architectural design to ensure privacy, fairness, and transparency in data handling.</li>
  </ul>
  <h5>Links:</h5>
  <p><a href="https://manuelzapata.co/atributos-de-calidad/#:~:text=Adaptabilidad.,las%20necesidades%20de%20los%20usuarios.">Quality attributes article 🌐</a></p>
  <p><a href="https://www.youtube.com/watch?v=NmRuhzyKCWM&list=PLFHx3afTdaY0hvX2NXRxMVM3j5sk-3aE3&index=5">Software quality attributes ✨</a></p>
  
  <h3>Coupling</h3>
  <p>The degree of interdependence between modules or components within a system. In simpler terms, it indicates how different elements of a system are related or connected to each other.</p>
  <p>There are two main types of coupling:</p>
  <ul>
    <li>Tight Coupling: Occurs when two modules are highly interconnected and strongly depend on each other. If a change is made in one module, it is more likely to affect the other. This type of coupling can make the system less flexible and harder to maintain.</li>
    <li>Loose Coupling: Refers to a more independent relationship between modules. Changes in one module have less impact on others, making the system more flexible and easier to maintain. It is a good practice to design systems with loose coupling to favor modularity and scalability.</li>
  </ul>

  <h5>Acoplamiento Eferente</h5>
  <img src="https://i.postimg.cc/yxhBsXtk/Captura-de-pantalla-2023-10-12-090257.png">
  <p></p>

  <h5>Acoplamiento Aferente</h5>
  <img src="https://i.postimg.cc/qvrfp3x3/Captura-de-pantalla-2023-10-12-090529.png">
  <p></p>

  <h5>Acoplamiento Patólogico</h5>
  <p></p>

  <h5>Acoplamiento Común</h5>
  <img src="https://i0.wp.com/www.disrupciontecnologica.com/wp-content/uploads/2019/06/clasesCBO.png?resize=313%2C230&ssl=1">
  <p></p>

  <h5>Acoplamiento Sellado</h5>
  <p></p>

  <h5>Acoplamiento por Datos</h5>
  <p></p>

  <h5>Acoplamiento por Mensajes</h5>
  <p></p>

  <h5>El acoplamiento ideal es que no exista.</h5>
  
  <p><a href="https://www.youtube.com/watch?v=0ggDGJTAFVs&list=PLFHx3afTdaY3tPDnw0O0WDu1c3PSuMLNf&index=4">Coupling ➰</a></p>
  
  <h3>Cohesion</h3>
  <p><a href="https://www.youtube.com/watch?v=bLEnvIBak60&list=PLFHx3afTdaY3tPDnw0O0WDu1c3PSuMLNf&index=7">Cohesion 🤝</a></p>
  
  <h3>SOLID</h3>
  <p><a href="https://profile.es/blog/principios-solid-desarrollo-software-calidad/#Los_principios_SOLID">S.O.L.I.D 📙</a></p>
  <p><a href="https://www.youtube.com/watch?v=rMlPvEhrHDs&list=PLFHx3afTdaY3tPDnw0O0WDu1c3PSuMLNf&index=2">S.O.L.I.D 🎥</a></p>

</div>
