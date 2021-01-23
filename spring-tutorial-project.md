# vrk-spring-tutorial-projects : Documentation

* Spring Framework is one of the most popular Java EE frameworks.
* The Spring Framework is a mature, powerful and highly flexible framework focused on building **web applications** in Java.
* The Spring Framework consists of features organized into about 20 modules. These modules are grouped into Core Container, Data Access/Integration, Web, AOP (Aspect Oriented Programming), Instrumentation, Messaging, and Test, as shown in the following diagram.

![spring-overview](https://github.com/veerrajukakarla434/vrk-spring-tutorial-projects/blob/main/src/images/spring-overview.png "spring-overview")

#### Spring modules description 

Spring is well-organized architecture consisting  of seven modules. Modules in the Spring framework are:

* **Core Container:**

* The Core Container consists of the Core, Beans, Context, and Expression Language modules the details of which are as follows −

* The Core module provides the fundamental parts of the framework, including the IoC and Dependency Injection features.

* The Bean module provides **BeanFactory**, which is a sophisticated implementation of the factory pattern.

* The Context module builds on the solid base provided by the Core and Beans modules and it is a medium to access any objects defined and configured. The **ApplicationContext** interface is the focal point of the Context module.

* The SpEL module provides a powerful expression language for querying and manipulating an object graph at runtime.

* **Data Access/Integration:**

* The Data Access/Integration layer consists of the JDBC, ORM, OXM, JMS and Transaction modules whose detail is as follows −

* The JDBC module provides a JDBC-abstraction layer that removes the need for tedious JDBC related coding.

* The ORM module provides integration layers for popular object-relational mapping APIs, including JPA, JDO, Hibernate, and iBatis.

* The OXM module provides an abstraction layer that supports Object/XML mapping implementations for JAXB, Castor, XMLBeans, JiBX and XStream.

* The Java Messaging Service JMS module contains features for producing and consuming messages.

* The Transaction module supports programmatic and declarative transaction management for classes that implement special interfaces and for all your POJOs.

* **Web:**
* The Web layer consists of the Web, Web-MVC, Web-Socket, and Web-Portlet modules the details of which are as follows −

* The Web module provides basic web-oriented integration features such as multipart file-upload functionality and the initialization of the IoC container using servlet listeners and a web-oriented application context.

* The Web-MVC module contains Spring's Model-View-Controller (MVC) implementation for web applications.

* The Web-Socket module provides support for WebSocket-based, two-way communication between the client and the server in web applications.

* The Web-Portlet module provides the MVC implementation to be used in a portlet environment and mirrors the functionality of Web-Servlet module.

