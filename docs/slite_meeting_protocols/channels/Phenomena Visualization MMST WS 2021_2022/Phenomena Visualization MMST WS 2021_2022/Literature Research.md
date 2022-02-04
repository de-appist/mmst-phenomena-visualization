
title: Literature Research
created at: Tue Nov 23 2021 21:45:03 GMT+0000 (Coordinated Universal Time)
updated at: Tue Nov 23 2021 22:39:16 GMT+0000 (Coordinated Universal Time)
---

# Literature Research

# ** Meeting Questions**

1.  Can we also use Figma for the project or is Axure a mandatory tool?

2.  Is the main design thought to be an industrial UI Interface to control the process and watch the phenomena?

3.  Muss Lastenheft/Pflichtenheft(Requirements specification / specification sheet) separat abgegeben werden?

# **Furnace**

-   <https://www.sciencedirect.com/science/article/pii/B978008099377500006X?via%3Dihub>

The principal Objective of a furnace is to attain a higher processing temperature than can be achieved in the open air. Although some Processes could be carried out in the open air, to do so would be far less efficient, the fuel consumption would be much higher and control of the processes would be much more difficult. (s4)

Heat is liberated by burning fuel with air (or oxygen) and some of the heat is transferred to the product. The remaining heat leaves in the flue gas and through openings such as charging doors, or is lost from the external surface. n= Qp/Qs (s5)

Combustion is a specific group of chemical reactions where a fuel and oxygen burn together at sufficiently high temperature to evolve heat and combustion products

**Process control system is required to meet following objectives: (S288)**

-   Maximising furnace production capacity
-   Ensuring satisfactory product quality
-   Minimising fuel consumption
-   Minimising emissions
-   Controlling furnace warm-up
-   Enabling smooth changeover between different products

**Posible controllable Parameters: (S289)**

-   Fuel flow rate or heat inputs of the furnace
-   Combustion air flow rate or air/fuel ratio
-   Combustion air temperature
-   Furnace temperature
-   Furnace exit gas combustion
-   Furnace exit gas temperature
-   Feed rate of raw material of the furnace
-   Physical and chemical composition of raw material of the furnace
-   Product exit temperature

Flow rate: Q- m³/s

## **Risk factors: (S 314)           **

![media_Literature%20Research/pqluSJmirBmSBVojvIb2vRUPPc-Qpbny4AA3qqiDxT8HBSGS4zzIoDWyv4HN5KaqcOlTWOZz3tKbARI0N8ci37LyndItxBI5IG7c4rjGPkFDfXF6BobPnZrSspPpTicIat_m8_1f](media_Literature%20Research/pqluSJmirBmSBVojvIb2vRUPPc-Qpbny4AA3qqiDxT8HBSGS4zzIoDWyv4HN5KaqcOlTWOZz3tKbARI0N8ci37LyndItxBI5IG7c4rjGPkFDfXF6BobPnZrSspPpTicIat_m8_1f)

-   If fuel is the missing component then the system is safe.
-   If air or heat for ignition is missing the situation is potentially dangerous but for an explosion to occur the fuel/air mixture must be within the flammable range.

Combustion control: controlling firing rate and air flow

# **Ecological Interface Design (suggested Papers from Nazanin)**

This paper will develop a framework for interface design that attempts to support operators during familiar, unfamiliar, and in particular, unanticipated events

One way to classify events in complex human-machine

Systems:

-   Familiar events are routine in that operators experience them frequently
-   Unfamiliar, but anticipated events occur infrequently and thus operators will not have a great deal of experience to rely on.
-   Unfamiliar and unanticipated are also unfamiliar to operators because they rarely occur.

Two questions that must be addressed by a design framework, specification of information content and design of visual form:

-   The abstraction hierarchy is a psychologically relevant framework that allows one to specify the information content of an interface in a way that provides operators with a basis for coping with unanticipated events.
-   The skills, rules, and knowledge taxonomy is used to integrate a variety of findings from the literature so as to derive inferences for how information should be presented in an interface.

**Abstraction hierarchy**

Five levels of constraint have been found to be useful for describing process control systems:

-   the purposes for which the system was designed (functional purpose)
-   the intended causal structure of the process in terms of mass, energy, information, or value flows (abstract function)
-   the basic functions that the plant is designed to achieve (generalized function)
-   the characteristics of the components and the connections between them (physical function)
-   the appearance and spatial location of those components (physical form).

Each level in the hierarchy represents a different class of constraint

Higher levels represent relational information about system purpose, whereas the lower levels represent more elemental data about physical implementation.

Higher levels are less detailed than lower levels

## **MULTIPLE LEVELS OF COGNITIVE CONTROL**

-   skill-based behavior (SBB)
-   rule-based behavior(RBB)
-   knowledge-based behavior (KBB)

There are two phenomenologically different types of control strategies that can be adopted by operators:

-   surface control (corresponding to SBB and RBB)
-   deep control (corresponding to KBB).

Surface control is guided by the perceptual properties of the displays, whereas deep control of the system is guided by the operator’s mental model of the underlying process.

Operators have a distinct preference for surface control rather than deep control of the system In other words, process control operators have a preference for lower levels of cognitive control.

It is easy for operators to forget, and therefore fail to consider, properties of the process that are not shown in the display. - “out of sight, out of mind”

However, the tendency for surface control can lead to problems when the mapping between surface and depth is not an isomorphic one

Interfaces should be designed to allow people to effectively meet the demands of the task by relying on lower levels of cognitive control.

Lower levels of cognitive control tend to be executed more quickly, more effectively, and with less effort than higher levels.

SBB can only be activated when information is presented in the form of time-space signals. RBB, on the other hand, is triggered by familiar perceptual forms (signs). And finally, KBB is activated by meaningful relational structures (symbols).

The intent is to develop a single design that will simultaneously support all three levels of cognitive control.

-   **SBB** - To support interaction via time-space signals, the operator should be able to act directly on the display, and the structure of the displayed information should be isomorphic to the part-whole structure of movements. This principle attempts to structure the interface so as to take advantage of SBB. Because the operator cannot directly act on the plant components, the motor control patterns at the SBB level will only be concerned with the manipulation of objects displayed in the interface.
-   **RBB** - Provide a consistent one-to-one mapping between the work domain constraints and the cues or signs provided by the interface. This second principle attempts to support the RBB level. At this level, the display provides operators with signs that they use as cues for the selection of an appropriate action.

There is a 1:1 mapping between symbols and signs, the operator can exhibit what looks like KBB by merely relying on RBB. The advantage of knowledge-based control is that, being based on fundamentals, its applicability is not restricted to specific conditions (e.g., frequently encountered scenarios) as RBB often tends to be.

-   **KBB** - The difficulty of successfully relying on KBB can be attributed to the complexity of high-tech systems. It is, therefore, very difficult for operators to ensure that all of the consequences of the action they select have been taken into account and evaluated

#  Design Principles

-   **Buch von Zühlke: **[**<u>https://link.springer.com/book/10.1007%2F978-3-642-22074-6</u>**](https://link.springer.com/book/10.1007%2F978-3-642-22074-6)
-   **Compatibility -** A fundamental requirement for a user-friendly operating system is its compatibility, which results from the correspondence of the arrangement in reality and in the representation on the operating system or the arrangement in reality and in the user's imagination. With regard to compatibility, a distinction is made between three different versions: Compatibility of the location, direction and sequence.
-   **Consistency**
    -   An action should always have the same effect, regardless of the operating system mode. If the boundary conditions are the same, the system should always react in the same way.
    -   A consistent design is a prerequisite for an operating system with a predictable appearance and behavior, e.g. B. with regard to information display, information manipulation and navigation.
    -   The operating system must be consistent and should also be striven for across all systems.
-   **Grouping -** Criteria for grouping of objects can be:
    -   Content-related and functional togetherness
    -   Frequency of operation
    -   Order of operation
-   **Conciseness - **Shapes and figures are perceived preferentially if they are concise and if they do not have a random, but rather logical structure. Shapes and figures must be ordered, kept simple and balanced, and make the essentials of individual objects appear as clear, regular, and optimally as possible. Structures that are composed of similar shaped parts appear clear. The human being has the need for clarity and order in his perception.
-   **Proximity -** Forms that lie close to one another combine to form a unit. Similar and dissimilar molded parts also tend to appear as a uniform shape when they are close. Groups can be formed through closeness or individual elements can enter into correspondence with one another.
-   **Cohesion -** Compared to open forms, closed forms are easier to perceive as a figure. Open and incomplete structures are closed and completed in the process of perception. What a person sees as a closed figure does not have to be bounded by a line.
-   **Similarity -** Elements of a pictorial representation appear to belong together even over considerable gaps if there is similarity in terms of color (has the strongest effect), shape, size and behavior (movement). If an element deviates significantly from the others, it is recognized very quickly.
-   **Separation methods**
    -   Separation by distance
    -   Stand out through color
    -   Marking by shape
    -   Change in size
    -   Insertion of dividing lines
-   **Windows, Icons, Menus, Pointers** (WIMP)
-   **VDE/VDI Norms**
    -   **ISO 9241 -** The most important standard for the development of operating systems is DIN EN ISO 9241. In this standard, in a total of 29 parts, the knowledge available worldwide on the ergonomic design of software, hardware and work environment is collected, evaluated and integrated into a standard. The standard offers assistance in the conception, design and evaluation of computer workstations and defines minimum requirements for the ergonomic design of software. It must be noted that the design principles were primarily developed for applications in the office area and cannot be adopted without reservation for applications in production areas, this applies above all to the controllability and customizability.
-   **VDI 3850 -** The VDI guideline 3850 "Nutzergerechte Gestaltung von Bediensystemen für Maschinen" is intended to provide a design framework for developers of control systems. With the help of this framework they can create an operating system quickly and in a user-friendly manner. However, this is not intended to impose a standard operating system on the developer; rather, he is given sufficient creative freedom to develop independent operating systems.
-   **VDI 3699 -** In Respect to the VDI / VDE guideline 3850, the guideline 3699 "„Prozessführung mit Bildschirmen" represents the counterpart for process engineering. This guideline should be the basis for the proper implementation of the VDU (visual display units) workstation ordinance in control rooms in process engineering. This guideline is intended to benefit operators and end users as well as manufacturers of operating and monitoring systems for process control technology.

#  Phenomena

## **1. Why do we need to visualize chemical phenomena? How can it be useful for a user (from cognitive viewpoint)? **

A variety of research studies have elicited several advantages in using external visual representations to support learning and understanding. These advantages are most significant when such representations match or are aligned with the learning demands of the task at hand. Visual representations may help reduce the cognitive effort required to solve a problem by, for example, grouping together information and facilitating search and recognition. Visualizations can also help externalize or make explicit abstract information, or they may focus learners’ attention and limit the range of inferences that they can make about the concepts that are represented.

-   _<http://ccl.northwestern.edu/2017/scalco.pdf>_

Computer-based modeling tools can also provide similar functionality, but as computer visualization capabilities become more powerful, viewers now have access to more dynamic types of representations. While physical tools can be useful to represent the static aspects of the molecular level (i.e., molecular structure), using them to represent the dynamic aspects of the molecular level (i.e., chemical reactions) may be more difficult. Computer tools, on the other hand, have the ability to provide the dynamic animation functionality that can help students model and think about these dynamic aspects. But while the roles for these different modeling tools may seem straightforward and intuitive, there is still a question about the utility of animated representations given their complexity and the actual differences between static and dynamic representations in this context.

-   _<http://websites.umich.edu/~hiceweb/papers/documents/Chemation_AERA2007.pdf>_

## **2. Is phenomena visualization always beneficial for supervising a plant or it is helpful in special situations? In other words, is one and only view of the plant with all phenomena taking place in it sufficient, or the user should have access to different views of the plant and switch between them based on the situation?**

Diﬀerent representations of the same system or phenomenon may lead to the creation of diﬀerent mental models or ways of reasoning. A second consideration is the nature of the design elements that will more eﬀectively guide student attention to relevant information. The selection of these elements depends on the learning goals and the role that the representation plays within the educational resource. Additionally, one must reﬂect on how students’ prior knowledge, experiences, and intuitive reasoning may inﬂuence their processing of the information that is represented.

To build a successful representation, readers should be able to meaningfully connect core elements in the text and incorporate their background knowledge to build a mental representation that provides an interpreted description of what is read. The construction of an appropriate mental model requires active inferencing and adequate prior knowledge.16

-   [<u>_http://ccl.northwestern.edu/2017/scalco.pdf_</u>](http://ccl.northwestern.edu/2017/scalco.pdf)

## **3. Are there any useful phenomena representation of chemical equipment in the literature? If yes, how can we improve them? What are their weak points?**

As computers continue to increase in power and functionality, expert scientists and science learners can draw from these representations to develop models that would be difficult to develop with physical media. When we consider the range of modeling tools that are now available to science learners in today’s classrooms, it is important that we understand how learners can best use those tools and what role different modeling tools and representations can play in an educational context.

-   _<http://websites.umich.edu/~hiceweb/papers/documents/Chemation_AERA2007.pdf>_

To help students understand chemistry at the three levels, researchers have suggested a variety of instructional approaches, such as adapting teaching strategies based on the conceptual change model (Krajcik, 1991), integrating laboratory activities into class instruction (Johnstone & Letton, 1990), using concrete models (Copolo & Hounshell, 1995), and using technologies as learning tools (Barnea & Dori, 1996; Kozma, Russell, Jones, Marx, & Davis, 1996). Among these approaches, using concrete models and technologies as learning tools seems promising. For example, viewing dynamic and three-dimensional animations created by technological tools could help students learn to use microscopic and symbolic representations to describe and explain a chemical process (Williamson & Abraham, 1995). Multiple linked representations provided by multimedia tools allow students to visualize the interactions among molecules and understand the related chemical concepts (Kozma et al., 1996). In addition, manipulating physical models promotes long-term understanding of molecules and atoms (Copolo & Hounshell, 1995; Gabel & Sherwood, 1980; Talley, 1973).

-   _<https://deepblue.lib.umich.edu/bitstream/handle/2027.42/34515/1033_ftp.pdf>_

![media_Literature%20Research/b3MwKXQXmQgYJKQ8OLaG6nV-cdmMYWVxbd8tFzQmmZLL4rOc4ibjc52FLQevO46R8tJ32mS0pfUWPNQ2Rz8TQUhpOj9wFvPTLCMMonGNG1s7NpzMfJZVEa3jMQS4yk4x5wib-Ocv](media_Literature%20Research/b3MwKXQXmQgYJKQ8OLaG6nV-cdmMYWVxbd8tFzQmmZLL4rOc4ibjc52FLQevO46R8tJ32mS0pfUWPNQ2Rz8TQUhpOj9wFvPTLCMMonGNG1s7NpzMfJZVEa3jMQS4yk4x5wib-Ocv)

-   <https://virurmt.com/en/esitlusmaterjalid/automatic-equipment-projects/visualiseerimine/>

          