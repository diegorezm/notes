---
title: software engineering Ian Sommerville 9th edition
date: 20-05-2024
tags:
  - software_engineering
  - sommerville
index: "[[software engineering]]"
---

# Software engineering Ian Sommerville 9th edition
## Cap - 5
### Model engineering 
- MDE is a software development approach that emphasizes the use of models to represent and design software systems. Instead of writing code directly, developers create models that capture the system's structure, behavior, and requirements. These models are then used to automatically generate code for various platforms and languages.
- The author mentions that MDE has roots in model-driven architecture (MDA). However, the author seems to imply that MDE offers a broader approach to software development compared to MDA.
## Cap - 4
### Requirements Types

#### User Requirements:

- Natural language statements with diagrams describing the services the system should provide to its users and the constraints under which it should operate.

#### System Requirements:

- More detailed descriptions of the functions, services, and operational constraints of the software system. The system requirements document (sometimes called functional specification) should define exactly what should be implemented. It may be part of the contract between the system buyer and the software developers.

#### Functional Requirements:

- Statements of services that the system should provide, how the system should react to specific inputs, and how the system should behave in certain situations. In some cases, functional requirements may also explicitly state what the system should not do.

#### Non-functional Requirements:

- Constraints on the services or functions offered by the system. They include timing constraints, development process constraints, and constraints imposed by standards. Unlike individual features or services of the system, non-functional requirements often apply to the system as a whole.

#### Non-functional Requirements Details

##### Product Requirements:

- These requirements specify or restrict the software's behavior. Examples include performance requirements for how fast the system should run and how much memory it requires, reliability requirements that establish the acceptable failure rate, security requirements, and usability requirements.

##### Organizational Requirements:

- These are the general system requirements derived from the policies and procedures of the client and developer organization. Examples include operational process requirements, which define how the system will be used, development process requirements that specify the programming language, development environment, or process standards to be used, as well as environmental requirements that specify the system's operating environment.

##### External Requirements:

- This type covers all requirements that derive from factors external to the system and its development process. They may include regulatory requirements, which define what must be done for the system to be approved for use by a regulator, such as a central bank; legal requirements, which must be followed to ensure that the system operates within the law; and ethical requirements, which ensure that the system will be acceptable to its users and the general public.

### Examples

**Product Requirement:**

- The MHC-PMS must be available to all clinics during normal business hours (Monday to Friday, 8:30 am to 5:30 pm). Periods of non-operation within normal business hours may not exceed five seconds in a day.

**Organizational Requirement:**

- MHC-PMS system users must authenticate with their health authority ID cards.

**External Requirement:**

- The system must implement patient privacy provisions, as established in HStan-03-2006-priv.

### Requirements Document

- Should include both user requirements for a system and a detailed specification of system requirements.
- Instead of a formal document, approaches like Extreme Programming (BECK, 1999) collect user requirements incrementally and write them on cards as user stories. The user then prioritizes the requirements for implementation in the next system increment.
- The level of detail you should include in a requirements document depends on the type of system being developed and the process used. Critical systems need detailed requirements, because safety and security must be analyzed in detail.
- System requirements should only describe the external behavior of the system and its operational constraints. They should not be concerned with how the system should be designed or implemented.

### Requirements Document Structure

![[tabela_doc_requisitos.png]]

### Natural Language Specification

- Since the beginning of software engineering, natural language has been used to write software requirements. It is expressive, intuitive, and universal. It is also potentially vague, ambiguous, and its meaning depends on the reader's knowledge.

To minimize misunderstandings when writing requirements in natural language:

1. **Invent a standard format and ensure that all requirement definitions adhere to that format.**

2. **Use consistent language to distinguish between mandatory and desirable requirements.**

3. **Use a way to highlight the fundamental parts of the requirement (bold, italic, or colors).**

4. **Do not assume that readers understand the technical language of software engineering. Frequently, words like 'architecture' and 'module' are misinterpreted. You should therefore avoid using jargon, acronyms and abbreviations.**

5. **Whenever possible, try to associate a logic with each of the user requirements.**

In more complex cases, you can add extra information to the requirements in natural language, using tables or graphical models of the system, for example.

Requirements engineering processes can include four high-level activities. They aim to assess whether the system is useful for the company (feasibility study), discovering requirements (elicitation and analysis), converting them into some standard form (specification), and verifying whether the requirements really define the system that the customer wants (validation).

In virtually all systems, requirements change. The process of managing these ever-changing requirements is called requirements management.

### Requirements Elicitation and Analysis

- After an initial feasibility study, the next stage of the requirements engineering process

# References