[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15240508&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
is an engineering process that is mainly related to computers and programming and developing different kinds of applications through the use of information technology. deals with the design, development, testing, and maintenance of software applications.

What is software engineering, and how does it differ from traditional programming?
is an engineering process that is mainly related to computers and programming and developing different kinds of applications through the use of information technology. deals with the design, development, testing, and maintenance of software applications.
It is mainly related to computers, programming, and writing codes for building applications.


Software Development Life Cycle (SDLC):
 SDLC or the Software Development Life Cycle is a process that produces software with the highest quality and lowest cost in the shortest time possible. SDLC provides a well-structured flow of phases that help an organization to quickly produce high-quality software which is well-tested and ready for production use.

    
Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

1. Requirements analysis and definition 
The system’s services, constraints, and goals are established by consultation with system users. They are then defined in detail and serve as a system specification.
2. System and software design The systems design process allocates the requirements to either hardware or software systems. It establishes an overall system architecture. Software design involves identifying and describing the fundamental software system abstractions and their relationships.
3. Implementation and unit testing During this stage, the software design is realized as a set of programs or program units. Unit testing involves verifying that each unit meets its specification
4.Integration and system testing The individual program units or programs are 
integrated and tested as a complete system to ensure that the software 
requirements have been met. After testing, the software system is delivered 
to the customer.
5. Operation and maintenance Normally, this is the longest life-cycle phase. The 
system is installed and put into practical use. Maintenance involves correcting 
errors that were not discovered in earlier stages of the life cycle, improving the 
implementation of system units, and enhancing the system’s services as new 
requirements are discovered

Agile vs. Waterfall Models:
The Waterfall Model is one of software development's earliest and most straightforward methodologies. It is a sequential design process often used in software development, where progress flows steadily downwards  similar to a waterfall through diverse phases. This highly structured model divides the software development process into distinct phases, each with specific deliverables and a review process WHILE The Agile Model is a highly flexible and interactive approach to software development that emphasizes adaptability, customer satisfaction, and iterative progress. Unlike traditional models like Waterfall, which treat software development as a sequence of strictly defined phases, Agile approaches software development as small, manageable increments known as sprints or iterations. The Agile Model is not just a set of practices for software development but a mindset guided by values outlined in the Agile Manifesto, emphasizing individuals and interactions, working software, customer collaboration, and responding to change.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
1. Waterfall model is squential and linear while agile is iterative and incrimental.
2. Waterfall model there is  Low changes are difficult and costly once the project is underway while in agile hign welcomes changes even in late development stages.
3. There is extensive planning at the beginning of the project; changes are discouraged while in agile Minimal upfront planning; plans evolve as the project progresses.

Requirements Engineering:
is the discipline that involves establishing and documenting requirements. The various activities associated with requirements engineering are elicitation, specification, analysis, verification and validation, and management.

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

1. Feasibility Study

The feasibility study mainly concentrates on below five mentioned areas below. Among these Economic Feasibility Study is the most important part of the feasibility analysis and the Legal Feasibility Study is less considered feasibility analysis. 

    1. Technical Feasibility: In Technical Feasibility current resources both hardware software along required technology are analyzed/assessed to develop the project. This technical feasibility study reports whether there are correct required resources and technologies that will be used for project development. Along with this, the feasibility study also analyzes the technical skills and capabilities of the technical team, whether existing technology can be used or not, whether maintenance and up-gradation are easy or not for the chosen technology, etc.
    2. Operational Feasibility: In Operational Feasibility degree of providing service to requirements is analyzed along with how easy the product will be to operate and maintain after deployment. Along with this other operational scopes are determining the usability of the product, Determining suggested solution by the software development team is acceptable or not, etc. 
    3. Economic Feasibility: In the Economic Feasibility study cost and benefit of the project are analyzed. This means under this feasibility study a detailed analysis is carried out will be cost of the project for development which includes all required costs for final development hardware and software resources required, design and development costs operational costs, and so on. After that, it is analyzed whether the project will be beneficial in terms of finance for the organization or not. 
2. Requirements elicitation is the process of gathering information about the needs and expectations of stakeholders for a software system. This is the first step in the requirements engineering process and it is critical to the success of the software development project. The goal of this step is to understand the problem that the software system is intended to solve and the needs and expectations of the stakeholders who will use the system.
Several techniques can be used to elicit requirements, including:
interiview, Survery, Focus group etc.

Software Design Principles:
Software design principles are concerned with providing means to handle the complexity of the design process effectively. Effectively managing the complexity will not only reduce the effort needed for design but can also reduce the scope of introducing errors during design.
    1. Problem Partitioning
For small problem, we can handle the entire problem at once but for the significant problem, divide the problems and conquer the problem it means to divide the problem into smaller pieces so that each piece can be captured separately.
    2. Abstraction
An abstraction is a tool that enables a designer to consider a component at an abstract level without bothering about the internal details of the implementation. Abstraction can be used for existing element as well as the component being designed.Here, there are two common abstraction mechanisms Functional Abstraction and Data Abstraction
    3. Modularity
Modularity specifies to the division of software into separate modules which are differently named and addressed and are integrated later on in to obtain the completely functional software. It is the only property that allows a program to be intellectually manageable. Single large programs are difficult to understand and read due to a large number of reference variables, control paths, global variables, etc. 
    4. Strategy of Design
A good system design strategy is to organize the program modules in such a method that are easy to develop and latter too, change. Structured design methods help developers to deal with the size and complexity of programs. Analysts generate instructions for the developers about how code should be composed and how pieces of code should fit together to form a program.To design a system, there are two possible approaches:

    Top-down Approach
    This approach starts with the identification of the main components and then decomposing them into their more detailed sub-components.
    Bottom-up Approach
    A bottom-up approach begins with the lower details and moves towards up the hierarchy, as shown in fig. This approach is suitable in case of an existing system.

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Modularity in software design is a technique where complex software is divided into smaller, independent modules, such as functions, classes, or components. It facilitates easier management and understanding of complex systems by breaking them down into digestible parts.

    1. Ease of Reading: Software becomes more readable as it's separated into specific functions handling distinct aspects of the overall functionality.
    2. Simpler Testing: Testing is more straightforward and detailed when focusing on smaller, singular-function modules.
    3. System Focus: Developers can concentrate on individual system parts without affecting the entire system, enhancing development efficiency.
    4. Code Organization: Grouping similar functions into files and libraries makes finding specific code easier, streamlining development.

Testing in Software Engineering:
Testing is the process of executing a program to find errors. To make our software perform well it should be error-free. If testing is done successfully it will remove all the errors from the software. In this article, we will discuss first the principles of testing and then we will discuss, the different types of testing.
Principles of Testing

    1.All the tests should meet the customer’s requirements.
    2.To make our software testing should be performed by a third party.
    3.Exhaustive testing is not possible. As we need the optimal amount of testing based on the risk assessment of the application. 
    4.All the tests to be conducted should be planned before implementing it 
    5.It follows the Pareto rule(80/20 rule) which states that 80% of errors come from 20% of program components. 
    6.Start testing with small parts and extend it to large parts. 

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

1. Unit tests

Unit tests are very low level and close to the source of an application. They consist in testing individual methods and functions of the classes, components, or modules used by your software. Unit tests are generally quite cheap to automate and can run very quickly by a continuous integration server.
2. Integration tests

Integration tests verify that different modules or services used by your application work well together. For example, it can be testing the interaction with the database or making sure that microservices work together as expected. These types of tests are more expensive to run as they require multiple parts of the application to be up and running.
3.System Testing

System testing is the third level of testing. This level of testing assists you in identifying bugs and challenges while ensuring that the software will meet all specific requirements. A specialized testing team is usually in charge of this type of testing.
4. Acceptance Testing
Acceptance testing is the last and final level of testing. This level of testing is broad in scope, ranging from simply finding spelling and cosmetic errors to discovering bugs that might produce a significant error in the software.

Version Control Systems:
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.
Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.


What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
As we know that a software product is developed in collaboration by a group of developers they might be located at different locations and each one of them contributes to some specific kind of functionality/features. So in order to contribute to the product, they made modifications to the source code(either by adding or removing). A version control system is a kind of software that helps the developer team to efficiently communicate and manage(track) all the changes that have been made to the source code along with the information like who made and what changes have been made. A separate branch is created for every contributor who made the changes and the changes aren’t merged into the original source code unless all are analyzed as soon as the changes are green signaled they merged to the main source code. It not only keeps source code organized but also improves productivity by making the development process smooth.

    1.Enhances the project development speed by providing efficient collaboration,
    2.Leverages the productivity, expedites product delivery, and skills of the employees through better communication and assistance,
    3.Reduce possibilities of errors and conflicts meanwhile project development through traceability to every small change,
    4.Employees or contributors of the project can contribute from anywhere irrespective of the different geographical locations through this VCS,
    5.For each different contributor to the project, a different working copy is maintained and not merged to the main file unless the working copy is validated. The most popular example is Git, Helix core, Microsoft TFS,
   

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

Software project manager's responsibilities are to analyze project constraints, establish the project objectives, coordinate the project's internal and external teams, construct the project timelines and monitor the project's key performance indicators.Software project managers are responsible for planning, scheduling and managing the delivery of software and web projects. They're usually qualified in computer science, software engineering or a similar subject and have strong technical knowledge of IT, development and computer systems.

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
 is the process of modifying, changing, and updating a software system or module to resolve errors, improve performance, or adapt to a changing environment.”

Software maintenance is one type of process, which helps to upgrade, modify, and update software to stay up with client needs. Software maintenance is performed for a variety of purposes, including improving the software overall, addressing faults or bugs, increasing performance, and more, once the software is released or launched.

Software maintenance is known as the modification of a software product after it has been delivered to rectify flaws, improve performance, or other features, in terms of software engineering.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

    Data Security: Trustworthy software systems prioritize data security, protecting sensitive data and preventing unauthorized access. This is particularly crucial for applications dealing with financial transactions, personal information, or healthcare records. Implementing robust security measures instills confidence in users to trust the software.
    Reliability: Reliable software systems are critical for businesses, organizations, and users. Frequent crashes, system failures, or glitches can lead to disruption of services, financial loss, and frustrated users. Trustworthy software systems prioritize stability, performance, and continuous uptime.
    Transparency: Emphasizing transparency in software systems is essential for building trust. Users expect clear and honest communication regarding data usage, privacy policies, and system behavior. By being transparent, software providers demonstrate accountability and foster trust amongst users.
    Compliance: Trustworthy software systems comply with relevant laws, regulations, and industry standards. This includes adhering to data protection laws, accessibility guidelines, and security certifications. Compliance demonstrates a commitment to ethical and responsible software development practices, building trust with users and stakeholders.

https://www.geeksforgeeks.org/software-engineering-software-project-management-spm/
https://www.tutorialspoint.com/software_engineering/software_project_management.htm
https://moldstud.com/articles/p-ethical-considerations-in-software-engineering
Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
