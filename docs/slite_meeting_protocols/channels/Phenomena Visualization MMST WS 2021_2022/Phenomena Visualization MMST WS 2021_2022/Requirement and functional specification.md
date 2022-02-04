
title: Requirement and functional specification
created at: Tue Nov 23 2021 22:23:14 GMT+0000 (Coordinated Universal Time)
updated at: Tue Nov 23 2021 22:36:22 GMT+0000 (Coordinated Universal Time)
---

# Requirement and functional specification

| **Projectname**     | **Phenomena Visualization** |
| ------------------- | --------------------------- |
| **Project manager** | **Marcus Rothhaupt**        |
| **Created on**      | **10/27/2021**              |
| **Last change on**  | **23/11/2021**              |
| **Status**          | **in progress**             |
| **Current version** | **0.3**                     |

* * *

# ** Introduction**

\*\* \*\*

The present specification contains the functional and non-functional requirements placed on the product to be developed. It serves as the basis for the invitation to tender and the drafting of the contract and thus forms the specification for the preparation of the offer. If a contract is concluded between the contractor and the client, the existing specifications are legally binding. With the requirements, the framework conditions for the development are specified, which are detailed by the contractor in the specification.\*\* \*\*

# **General\*\***\_ \_\*\*

## **\_ \_\*\***Distribution of roles\*\*

\*\* \*\*

| Role (s)        | **Name**         | **E-Mail**                                                                              |
| --------------- | ---------------- | --------------------------------------------------------------------------------------- |
| Project manager | Marcus Rothhaupt | [marcus.rothhaupt@mailbox.tu-dresden.de](mailto:marcus.rothhaupt@mailbox.tu-dresden.de) |
| Designer        | Dmytro Kostiuk   | [dmytro.kostiuk@mailbox.tu-dresden.de](mailto:dmytro.kostiuk@mailbox.tu-dresden.de)     |
| Quality         | Artan Kabashi    | [artan.kabashi@mailbox.tu-dresden.de](mailto:artan.kabashi@mailbox.tu-dresden.de)       |
|                 | Felix Mehlhorn   | [felix.mehlhorn1@mailbox.tu-dresden.de](mailto:felix.mehlhorn1@mailbox.tu-dresden.de)   |
| Designer        | Tamino Schorcht  | [tamino.schorcht@mailbox.tu-dresden.de](mailto:tamino.schorcht@mailbox.tu-dresden.de)   |

# **Concept**

## **Objective (s) and benefit of the user**

-   Clarity
-   Correctness
-   Intuitiveness
-   Process
-   understanding Reliability
-   Illustration of a complex process
-   Good and simple controllability

## **Target group (s)**

-   machine operator
-   training participants

# **Functional requirements**

Functional requirements are the desired functionality or behavior of a system or product. They describe what the product to be developed should or should be able to do.

\*\* \*\*

| **Number** | **Description**                                                                               | **Agent** |
| ---------- | --------------------------------------------------------------------------------------------- | --------- |
| FA01       | The furnace has 3 inputs and 2 outputs                                                        |           |
| FA02       | inputs and outputs are linked useful                                                          |           |
| FA03       | The size of the combustion reaction of the furnace is visualized                              |           |
| FA04       | The temperature of the I / O is visualized. Temperature of Inlet, Outlet, Combustion Products |           |
| FA05       | All 3 inputs can be controlled by the user                                                    |           |
| FA06       | A warning is issued for critical inputs                                                       |           |
| FA07       | Display of important relevant information about the process                                   |           |
| FA08       | Amount of fuel is displayed                                                                   |           |
| FA09       | Amount of air is displayed                                                                    |           |
| FA10       | Opt: Control of the 2 outputs                                                                 |           |

\*\* \*\*

# 

# **Nonfunctional requirements**

\*\* \*\*Non-functional requirements are requirements for the quality in which the required functionality is to be provided. This also includes, for example, the design, conformity to certain laws / regulations or the response time of the system.

| **Number** | **Name**                          | **Description** |
| ---------- | --------------------------------- | --------------- |
| NF01       | Clarity                           |                 |
| NF02       | correctness                       |                 |
| NF03       | intuitiveness                     |                 |
| NF04       | process                           |                 |
| NF05       | understanding reliability         |                 |
| NF06       | illustration of a complex process |                 |
| NF07       | good and simple controllability   |                 |

# **Duties**

| **Number** | **Category** | **Description**                                                                                                                                                                                                                              | **Processor** |
| ---------- | ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| D01        | Design       | The furnace has three inputs and two outputs, they have touch-enabled controller for a predefined range of                                                                                                                                   |               |
| F01        | Function     | inputs and outputs are meaningfully linked:<br />- the heat is not completely transferred to outlet <br />- increase flow rate of fuel -> increase temp. of outlet stream <br />- increase flow rate feed -> decrease temp. of outlet stream |               |
| D02        | Design       | The size of the combustion reaction of the furnace is visualized                                                                                                                                                                             |               |
| D03        | Design       | The temperature of the I / O is visualized. Temperature of Inlet, Outlet, Combustion Products                                                                                                                                                |               |
| F02        | Function     | All 3 inputs (Input, Air and Fuel) can be controlled by the user                                                                                                                                                                             |               |
| D04        | Design       | The control panel for the 3 inputs is sensibly positioned                                                                                                                                                                                    |               |
| F03        | Function     | A warning is issued for critical inputs                                                                                                                                                                                                      |               |
| D05        | Design       | A warning must be given on a good one Space to be displayed                                                                                                                                                                                  |               |
| D06        | Design       | Display of important relevant information on the process                                                                                                                                                                                     |               |
| D07        | Design       | The legend is clearly visible                                                                                                                                                                                                                |               |
| F04        | Function     | The color of the I / O changes according to a scale                                                                                                                                                                                          |               |
| D08        | Design       | Amount of fuel is shown                                                                                                                                                                                                                      |               |
| D09        | Design       | Amount of air is shown                                                                                                                                                                                                                       |               |
| F05        | Function     | Opt: Control of the outlet control                                                                                                                                                                                                           |               |
| F06        | Function     | Opt : Water pressure influences the temp. Of the water                                                                                                                                                                                       |               |
| D10        | Design       | The temperature profile of various I / O is visualized in graphs.                                                                                                                                                                            |               |
| D11        | Design       | information about the furnace and how it works can be displayed after clicking on an info button                                                                                                                                             |               |

          