<div align="center">
  <h1>SOFTWARE ARCHITECTURE</h1>
  <a href="URL_DEL_ENLACE"><img src="https://cdn-images-1.medium.com/max/1200/1*DenJfjmLJ5drVjPLTqkHzQ.png" alt="Imagen"></a>
</div>
<div>
    <h2 align="center"><a href="https://www.youtube.com/watch?v=7ukajubprdE&list=PLFHx3afTdaY0hvX2NXRxMVM3j5sk-3aE3&index=2">Definitions 📚</a></h2>
      <p>• The software architecture of a system is the set of structures necessary to reason about the system.</p>
      <p>• It is the set of design decisions important to organize the software and promote the desired quality attributes.</p>
      <p>• Architecture is about the important things. Whatever they are.</p>


  
  <h2 align="center">What are design patterns? 📐</h2>
      
  <h4><a href="https://www.youtube.com/watch?v=pk-lawTRbmg">What are?</a></h4>
  <p>A pattern is a solution to a problem in a context.</p>

  <h4>Sistema de patrones P.O.S.A (Pattern-Oriented Software Architecture)</h4>
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

  
  <h2 align="center">Concepts of Software Engineering 🖥️</h2>

  <h3>Software quality atrributes</h3>
  <p><a href="https://manuelzapata.co/atributos-de-calidad/#:~:text=Adaptabilidad.,las%20necesidades%20de%20los%20usuarios.">Quality attributes article 🌐</a></p>
  <p><a href="https://www.youtube.com/watch?v=NmRuhzyKCWM&list=PLFHx3afTdaY0hvX2NXRxMVM3j5sk-3aE3&index=5">Software quality attributes ✨</a></p>
  
  <h3>Coupling</h3>
  <p><a href="https://www.youtube.com/watch?v=0ggDGJTAFVs&list=PLFHx3afTdaY3tPDnw0O0WDu1c3PSuMLNf&index=4">Coupling ➰</a></p>
  
  <h3>Cohesion</h3>
  <p><a href="https://www.youtube.com/watch?v=bLEnvIBak60&list=PLFHx3afTdaY3tPDnw0O0WDu1c3PSuMLNf&index=7">Cohesion 🤝</a></p>
  
  <h3>SOLID</h3>
  <p><a href="https://profile.es/blog/principios-solid-desarrollo-software-calidad/#Los_principios_SOLID">S.O.L.I.D 📙</a></p>
  <p><a href="https://www.youtube.com/watch?v=rMlPvEhrHDs&list=PLFHx3afTdaY3tPDnw0O0WDu1c3PSuMLNf&index=2">S.O.L.I.D 🎥</a></p>

</div>
