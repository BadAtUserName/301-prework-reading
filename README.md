# 301-prework-reading
prework for 301 course
301 reading notes Intro to react and components

component-Based Architecture

What is a component
A modular portable replaceable and reusable set of well defined functionality that encapsulates it’s implementation and exporting it to a higher level interface. 
Software component: unit of composition with a contractually specified interface and explicit context dependencies only. 
Software component can be deployed independently and is sub to composition by 3rd parties
      C. Object-oriented view
	1. Component is viewed as a set of one or more cooperating classes.
      D. Conventional view
	1. Viewed as function element or modulate of a program that integrates a processing logic, internal data structure and are require to implement the processing logic, and an interface that enables the component to be invoked and data to be passed to it. 
      E. Process-related view
	1. In this view instead of creating each component from scratch the system is building from existing components maintained in a library. 
		a. User interface component includes grids, buttons, and utility composts expose spec subset of functions used in other components
		b. Other common types of components are those that are resource intensive not frequently accessed and must be activated using just-in-time (JIT) approach. 
		c. Many compotes are invisible which are distributed in enterprise business applications and internet web apps such as enterprise JavaBean .net components and CORBA components
     F. Characteristics of components
	1. Reusability: compotes designed to be reused
	2. Replaceable: components may be freely substituted with other similar components
	3. Not Context specific: component are designed to operate in diff enviro and contexts
	4. Extensible: Component can be extended from existing component to provide a new behavior. 
	5. Encapsulated: component depicts the interfaces which allow the colluder to use it’s functionality, and do not expose details of the internal processes or any internal variables or state. 
	6. Independent- Components are designed to have a minimal dependencies on other components
     G. Principles of component based design
	a. Can be roped by using some intermediary reps (graphs tab or text based) can be translate into source code. 
		1. Software system is decomposed into reusable cohesive and encapsulated component unites
		2. Each component has it’s own interface that specs require ports and provided ports: each component hides it’s detailed implementation
		3. Component should be extended wi/o the need to make internal code or design mods to the existing parts of the component. 
		4. Depone on abstractions component do no depend on other concrete components which increase difficulty in expendability
		5. Connectors connected components spec and ruling the interaction among components.
			i. Interaction type speed by interfaces of components
		6. Components interaction can take the form of method invocations asynchronous invocations broadcasting message driven interactions data stream communication and other protocol specific interactions
		7. Server class specialized interfaces should be created to serve major categories of clients only those operations that are relevant to a particular cat or clients should be speeded in the interface. 
		8. Component can extend to other components and still offer it’s own extension points. It is the concept of plug0in used architecture this allows a plugin to offer another plugin API
      H. Component level design guidelines 
	a. Cretes naming conventions for components that are seeded as part of the architectural model and refines part of the component level model
	b attains arcitecural component names from problem domain and ensure they have meaning to all stake holders
	c. Recoded and dissolve these indecent entities as new components
	d. Infastructure comments names reflect their implementation specific meaning. 
	e. Models any dependedns from left to right and inheritance from top to bottom 
	f. Model any component dependencies as interfaces rather than repaying them as direct component to component dependency

  I. Conducting comment level design. 
	a. Recognized all design classes that correspond to the problem domain as defined in the analysis model and architectural model. 
		1. Recognized all design Classe that correspond to the infrastructure domain
		2. Describe all design classes that re not acquired as reusable components and specifies message details
		3.describes processing flow within each operation in detail by means of  of pseudo code or iml activity diagrams
		4. Describes persistent data sources and identifies the classes required to manage them. 
		5. Develop and elaborate behavior presentation for a class or component.
		6 elaborates deployment diagram to provide additional implementation detail 
		7. Demonstrate the location of key packages or classes of components in a system to fusing class instances and designed specific specific hardware and operating system enviro

  J. Advantages
	a. Ease of deployment new computing versions become available it is easier to to play existing versions with no impact on the other components or the system as a as a whole. 
	b. Reduce cost: 3rd part components allows you to spread cost of dev and maintainence.
	c. Ease of development
	d. Reusable
	e. Modification of technical complexity
	f. Reliability 
	g. System maintenance and evolution 
	h. Indépendant 
	
