[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15241074&assignment_repo_typegit=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering: 

Ans:Software engineering is the application of engineering principles and knowledge of programming languages to design, develop, operate and maintain software.

What is software engineering, and how does it differ from traditional programming?

Ans: Software engineering is a systematic approach which invloves planning, desgining, developing, testing, quality assurance and maintance of software systems whilst traditional programming is mainly concerned with just writting code

 Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

Ans: The stages of Software Development Cycle are as follows

1. Planning
At this stage you define the scope of the project (i.e the boundaries and deliverables of the project). Project objectives and goals are also set. A feasibility study is conducted to asses whether the project is technically, finacially and operationally achievable.

2. Requirements gathering 
At this stage system requirement(these are the  functionalities and specifications of the system required by the client) are gathered and analyzed and a documentation is done inform of a SRS(System Requirements Specification).

3.Designing
This is when the architectural design and system models are made using different tools like Data Flow Diagrams,Flowcharts etc.
Design specifications are also developed

4. Implementation 
This is when the code is written and compiled according to design specifications.Modules and components are intergrated.

5.Testing
Tests are conducted which include unit testing, intergration testing,system testing and acceptance tests.
The system is tested to determine whether or not it meets system requirements.Black and white box tests are also conducted using different testing tools like  JUnit,JaCoCo etc.

6.Deployment
 The sytstem is now deployed(handed over to the client) and installed to his production enviroment.User trainings are conductedand different documentation like user manuals are made.
 
 7.Maintenance 
 This involves monitoring the software for issues and how it is performing.It also involves providing support and updates according to user feedbacks.





 

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
  Ans: Agile model  is iterative and incremental  while waterfall model is sequential and a phase has tobefinished before going to another.
  Agile  methodoligies emphasizes close collaboration  with the stakeholders/ clients  inorde to meet their requirements whilst waterfall model does not emphasize on customer involvement especially in the development stages.
  Agile model is flexible and adapts to chnaging requirements whilst waterfall model is rigid and doesnt accomodate changing  requirements once developments starts.
   
  Agile model is used when projects requirements are expected to change frequently  
  waterfall model is used  on predictable projects with well defined requiremets. 

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
 Ans:Requirements engineering is the process of defining,documenting, and maintaning requirements in the software engineering process. It invloves gathering requirements coming up with an SRS document and maintaning the documented requirements.The process has the following stages
 1.Feasibility study
 This encompases  technical, operational and economic feasiblity studies. This study assess the econimic, technical and operating resources to see if they are match the requirments.

 2. Elicitation 
 It is the process of gathering information about the needs and expectations of stakeholders for a software system.It involves several requiremnts gathering techniques which includde interviews,questionnaires,surveys, observation and prototyping.
3. Requirements Specifications
This involves clear identification  analysis and grouping of requirements into functional requirements and non functional requirements.
4. Requirements  Verification and validation
 Verification is checking that requirements are complete consistent and accurate.
 Validation  is the process of checking that the requirements meet the needs and expactions of the stakeholders.
5. Requirements  Management
It is the process of managing requirements throught the SDLC  including tracking  and controlling changes and ensuring that requirement are still valid and relevant. 

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Ans: Modularity is subdividing a large software system into smaller manageable parts which can be built, tested and maintaned separately and then intergrated later to form a larger syatem.

modularity improves maintanability  since it is easier to update or replace a module rather than a whole system.?
 modularity improves scalability since it is easy to add ceratin functions to a module rather than a whole system
Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

Ans: Unit testing
 It is when you test the smallest functional module of a system.
 
 intergration test
 It is when 2 modules are gradually intergrated and tested as one unified component.

 system testing
 It is  a software testing where the fully intergated system functionality and perfomance is tested.

 acceptance testing
 It is when software is tested to determine whether or not it meets fully meets the functional and non functional requirements before its handed to the client/stakeholders.
 
 Testing is important because it ensures that the system is secure, perfoming well and it also meets the stakeholders requirements. 


Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

Version Control Systems are software tools that manage and  record changes made to files by keeeping track of modificationsand updates don to code.
Version Control systems are important because they make colloborating easy since a team of developers can access the code,they also provide cloud backup of code and it makes code management easy since it keeps track of changes made to code.
 
 The most popular version control system is GIT.

Software Project Management:

 Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
A software project manager is responsible for:

planning and defining project scope-  develops a project plan and define project boundaries.
resource allocation -  this involves allocation of human and financial resources to different project parts of the project.
requirements management-this involves gathering, documenting , controlling changes and ensuring that requirements arestill relevenat.
team management - This invloves assigning tasks and making sure tasks are executed and delivered on time.
communication - this involves internal and exteranl communication all involved stakeholders.
qaulity assuarance - this is assuaring that a good qaulity software product is deliveredtoa client.
progress tracking- involves generating reports based on time stamps and deliverables.

 challenges faced in software project management
scope creep- this is when project scope exceeds beyond set boundaries
time constraints - this is when project deadlines are not met and projects delays and exceeds expected time.
budget limitations- this usually happens due to under budgeting leading to budget limiations.
communication  issues -  communication breakdowns during project execution can lead to delays and also errors.


 
Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Ans:
Software maintanance is modifying and updating software after deployment to fix bugs, enhance features and adaptto changing requiremens.
Maintanace activities are
1. adaptive maintanance- modifying software to adapt in changing enviroments
2. corrective maintanance - fixing and debbuging errors inncurred during use.
3.perfective maintanance - enhancing function to improve perfomance.
4.code refactoring - thisis simplification of code removing duplicates and improving code without changes the perfomance and functions of a system.

importance of maintanance 
it helps in fixing bugs
improves security
ensures optimum perfomance 
ensures adaptability to changing enviroments
ensures customer satisfication.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
 privacy issues with handling personal data
 security concerns with malicious softwares
 intellectual properties and avoiding pragiarism and unathourized use of lisenced software.
how to adhere to ethical standars
 buying and installing licensed softwares not copyrighted one'
 ensuring data privacy and respecting confidential information.

 References Geeks for geeks, chatGPT.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
