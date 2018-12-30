# Functional specifications template

This functional specifications template is adapted from [Electric Power Research Institute](http://www.erpi.com)

For a tutorial on how functional specifications can help your project, you can read this [functional specifications tutorial](http://sixarm.com/functional-specifications-tutorial)

Contents:

* [Overview](#overview)
  * [Product description](#product-description)
  * [Product functional capabilities](#product-functional-capabilities)
  * [User Roles](#user-roles)
  * [Use Cases for all operations](#use-cases-for-all-operations)
  * [General constraints](#general-constraints)
  * [Assumptions](#assumptions)
  * [Other software](#other-software)
* [Specific Function Descriptions](#specific-function-descriptions)
  * [Description](#description)
  * [Inputs](#inputs)
  * [Processing](#processing)
  * [Outputs](#outputs)
* [External Interfaces](#external-interfaces)
  * [User Interfaces](#user-interfaces)
  * [Hardware Interfaces](#hardware-interfaces)
  * [Software Interfaces ](#software-interfaces)
  * [Communication Interfaces](#communication-interfaces)
  * [Performance](#performance)
  * [Design Constraints](#design-constraints)
* [Attributes](#attributes)
  * [Security](#security)
  * [Reliability, Availability, Maintainability](#reliability-availability-maintainability)
  * [Configurability and Compatibility](#configurability-and-compatibility)
  * [Installability](#installability)
  * [Usability](#usability)
* [Additional Requirements](#additional-requirements)
  * [Database](#database)
  * [Administration](#administration)
  * [User documentation](#user-documentation)
  * [Other requirements](#other-requirements)


## Overview

Describe the purpose, scope, and organization of the Functional Specification.


### Product description

Describe briefly why the software (or upgrade) is being developed, and list the most important features and capabilities.


### Product functional capabilities

Present a list of the functions that the software will be required to perform.  If a product feature comprises several functional capabilities, a table may be developed to illustrate these relationships.  The list of functional capabilities may be an updated version of the capabilities listed in the Software Requirements Document.


### User Roles

Describe the intended users of the software in terms of job roles, specialized knowledge, skill levels, etc. Considers various user roles such as managers, administrators, auditors, etc.


### Use Cases for all operations

Describe how persons will normally use the software, and the tasks they will most frequently perform.  Also covers how users might use the software on an occasional basis, such as creating data backups or importing data from another program.


### General constraints

Describe any algorithm limitations, user interface limitations, data limitations, etc. Include items such as minimum space or room needed to house equipment, type of electrical and HVAC required (e.g. conditioned power), maintenance requirements.  Also, state if training is required for optimum use, or if calculated results are only applicable in certain situations.


### Assumptions

List any assumptions that were made in specifying the functional requirements.


### Other software

How does the program interact with other software, such as spreadsheets, word processing or presentation software? For example, can a user cut and paste from the application to other Windows software programs? Does the program import/export data to other software? Does the program use any communication, integration, or protocols to exchange data with other software?


## Specific Function Descriptions

This section is repeated for each function of the software. Some examples of functions are: engineering calculations, sorting or sequencing, other operations relating inputs to outputs, validity checks on inputs, error handling and recovery.


### Description

Describe the function and its role in the software.


### Inputs

Describe the inputs to the function.  Where user interface (UI) elements are present, these are described.  Examples of UI elements are check boxes, dropdown lists, and alphanumeric fields. Input validation strategy, allowed data types and value ranges are specified for each input.


### Processing

Describe what is done by the function.  Where algorithms, equations, or other logic are used, they are described here. If calculations are done utilizing the methods of specific standards or references, these are cited. Database definitions are also included where relevant.


### Outputs

Describe the outputs of the function.  Where a user interface description is relevant, it is included. Define any reports.


## External Interfaces

The interfaces in this section are specified by documenting: the name and description of each item, source or input, destination or output, ranges, accuracy and tolerances, units of measure, timing, display formats and organization, and data formats.


### User Interfaces

Describe all major screens, pages, forms, including any complex dialog boxes.  This is usually best done via simulated, non-functioning screen shots, and may take the form of a separate document. 

The navigation flow of the windows, menus, and options is described, along with the expected content of each window. Examples of items included are screen resolutions, color scheme, primary font type and size. Discussion also includes how input validation will be done, and how data will be protected from accidental changes. Specific items are described for each screen such as input fields, control buttons, sizing options, and menus.


### Hardware Interfaces

Describe the equipment needed to run the software, and also other output or input devices such as printers or handheld devices.


### Software Interfaces 

Describe any software that will be required in order for the product to operate fully. Include any in-house software or commercial applications that customers will be utilizing together with the planned software. Also describes any software that the software product will interact with such as operating system platforms supported, file import and export, networking, automation, or scripting. Specify whether the users must provide the interfacing software themselves, and any special licensing requirements.


### Communication Interfaces

Describes how the software product will communicate with itself (for multi-platform applications) or other software applications, including items such as networking, email, intranet, and Internet communications.


### Performance

Discuss items such as response times, throughput requirements, data volume requirements, maximum data file size or problem complexity, maximum number of concurrent uses, and peak load requirements (for web-based applications). Includes expected response times for entering information, querying data files and databases, performing calculations of various complexities, and importing/exporting data.


### Design Constraints

Examples of constraints that affect software design choices are items such as memory constraints involving minimum and maximum RAM and hard disk space, and limitations arising from hardware, software or communications standards.


## Attributes


### Security

Describe any password-protected access levels such as operator, engineer/modeler, manager, database administrator-and which functionality will be accessible to each access level. If relevant, describes the planned approach to locking the software.


### Reliability, Availability, Maintainability

Describe requirements items such as days or weeks of continuous operation, strategy for data recovery, code structuring for ease of future modification.


### Configurability and Compatibility

Describe requirements such as those connected with individual customization or operation in specific computing environments.


### Installability

Describe the planned method for installation: done by the user independently, done by customer company internal IT services, done by an external contractor. Specifies the handling of such items as data transfer from prior releases, and the presence of software elements from prior releases.


### Usability

Describe items that will ensure the user-friendliness of the software. Examples include error messages that direct the user to a solution, input range checking as soon as entries are made, and order of choices and screens corresponding to user preferences. 


## Additional Requirements

Describe other characteristics the software must have, that were not covered in the prior sections.


### Database

Describe any specific requirements relating to the database, such as database type (e.g. relational), capability to handle large text fields, real-time capability (e.g. handling an incoming data stream, as from instruments), multi-user capability, special requirements relating to queries and forms.


### Administration

Include any periodic updating or data management needed.


### User documentation

Describe the user documentation to be delivered with the software, including both hard copy and online requirements. 


### Other requirements

Describe any other requirements not already covered above that need to be considered during the design of the software.

