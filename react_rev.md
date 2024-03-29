# Component-Based Architecture 

<br>
<br>


## What is a Component?


A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.

### Views of a Component

 A component can have three different views − object-oriented view, conventional view, and process-related view.

### Object-oriented view <br>

 A component is viewed as a set of one or more cooperating classes. Each problem domain class (analysis) and infrastructure class (design) are explained to identify all attributes and operations that apply to its implementation. It also involves defining the interfaces that enable classes to communicate and cooperate.
Conventional view

It is viewed as a functional element or a module of a program that integrates the processing logic, the internal data structures that are required to implement the processing logic and an interface that enables the component to be invoked and data to be passed to it.

### Process-related view <br>

In this view, instead of creating each component from scratch, the system is building from existing components maintained in a library. As the software architecture is formulated, components are selected from the library and used to populate the architecture.

A user interface (UI) component includes grids, buttons referred as controls, and utility components expose a specific subset of functions used in other components.

Other common types of components are those that are resource intensive, not frequently accessed, and must be activated using the just-in-time (JIT) approach.

Many components are invisible which are distributed in enterprise business applications and internet web applications such as Enterprise JavaBean (EJB), .NET components, and CORBA components.

## Characteristics of Components <br>

> Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task. <br>


> Replaceable − Components may be freely substituted with other similar components. <br>

> Not context specific − Components are designed to operate in different environments and contexts. <br>

> Extensible − A component can be extended from existing components to provide new behavior. <br>

> Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state. <br>

> Independent − Components are designed to have minimal dependencies on other components. <br>
