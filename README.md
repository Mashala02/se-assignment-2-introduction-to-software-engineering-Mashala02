[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244583&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

Software Engineering is the branch of computer science that deals wuth the design development,testing and maintenace of applications.

ref:https://www.mtu.edu/cs/undergraduate/software/what/


What is software engineering, and how does it differ from traditional programming?

Software Engineering is concerned with developing software products that are reliable ,efficient and easy to maintain.it applies scientific and mathemical principles to the design,analysis and implemenation of software systems.
Programming on the other hand is mainly concerned with writing code to solve specific problems
    ref:https://en.itpedia.nl
Software Development Life Cycle (SDLC):

1. Requirements gathering:Collect and document user needs and expectations.
2. Design:Create a detailed design of the software architecture.
3. Implementation:Write the code and develop website.
4. Testing:Verify the software meets requirements and is bug free.
5. Deployment:Release the software to production.
6. Maintenance:Update,fix and enhance the software post release.

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Agile vs. Waterfall Models:

Agile models :
    Iterative and incremental-software is developed in small manageable increments eith regular reassessment and adaption
    fleibility-allows changes to requirements even late in development process
    customer collaboration-frequent feedback
    Cross functional teams -teams are composed of members with diverse skills who collaborate closely
    Continuous testing and integration- ensures defects are identified and fixed early

Waterfall models:
    Sequential Development- Each phase must be done completed before he next begins
    Defind Requirements- Detailed documentation of requirements is created at the beginning of the projects
    Empasis on Documentation-Extensive documentation is created at each phase
    Less customer interaction-Less opportunity for ongoing feedback and adjustments
    Testing After Development- Testing is conducted only after the development phase is complete

scenerios :

flexibility
Agile is high and accommodates changes at any stage
waterfall is low and changes are difficult once the project is underway
Documentation
Agile minimal ,just enough to support development
Waterfall extensive , detailed documentation at each stage
Testing
Agile is continuous ,integrated with developmeny
Waterfall id post development phase


Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be 
preferred?



Requirements Engineering:

Is the process of identifying ,eliciting,analyzing,specifying,validating and managing the needs and expectations of stakeholders for a software system
the process:
- Feasibility study: An initial study to determine the practicality of the project.
- Requirements elicitation: Gathering information from stakeholders to understand their needs and expectations.
- Requirements specification: Documenting the requirements in a clear and concise manner.
- Requirements verification and validation: Checking that the requirements are complete, consistent, and accurate.
- Requirements management: Managing the requirements throughout the software development lifecycle.
The importance of requirements engineering in the software development lifecycle includes :
- Ensuring that the software meets the needs and expectations of stakeholders
- Identifying potential issues early in the development process
- Improving communication and collaboration between the development team and stakeholders
- Ensuring that the software is developed on time, within budget, and to the required quality standards
- Providing a solid foundation for the development process, reducing the risk of failure.

       ref: https://www.geeksforgeeks.org

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Software Design Principles:
Modularity  is a fundamental design principle in software engineering aimed at creating software in a way that minimizes dependencies among the components of a system. 
      ref: https://www.ituonline.com

Improve by:
Maintainabiity- chamges in one module typically do not affect others making bugs easier to track down and fix without risking other parts of the systeem

Scalability-by adding new modules or enhancing extisting ones without impacting the rest og the system
     ref:https://www.ituonline.com


Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Testing in Software Engineering:
 Is the process of checking the quality,functionality and performance of a software product before launching.
 ref: https://katalon.com

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

Unit testing: Test individual code units or models to ensure they function correctly
Integration testing:Test how units work together to ensure seamless intergration
System testing:Tests the entire software system to ensure it meets requirements 
Acceptance testing:Tests software meets user acceptance criteria and is ready for deployment

Software testing is crucial in software development for the following reasons:
RIsk mitigation - testing helps identify defects and failures early
Confidnece-Excuting  a well planned software test strategy
Compliance-Testing can ensure that software adheres standards
Cost saving-Investing  in testing activities reduces downstreams costs

    ref:https://www.computer.org

Version Control Systems:

Version Control Systems tracks every alteratiom to a file or set of files enabling developers to journey back to earlier versions and collabrorate seamlessly

VCS is important for sevaral reasons:
1. Tracking changes - allows developers to track changes made to code,   
                      documentation and other digotal content.
2. Collaboration - enables multiple developers to collaborate on a project by    
                   managing different versions of code
3. Back up and Recovery-provides a back up of the code and allows developers to   
                        recover previous versions incase of errors or losses

    ref: https://about.gitlab.com                    

 Examples :
 Git-branching and merging
 ref:https://git-scm.com
 SVN-versioning
 ref:SVN Book(Read Bean Software)
 Mercurial- Easy to use 
 ref:Mercurial Tutotial (Mercurial official website )
                       
What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Software Project Management:

Software Project Management is dedicated to the planning ,scheduling ,resource allocation,execution,tracking and delivery software and web projects.

key responsibilities
Planning-puts together the blueprint for the entire project.
Leading-assembles and leads the project team.
Execution-Will supervise the successful execution of each stage of the project. 
Time management-Staying on schedule is crucial to the successful completion of any project.
Budget-are tasked with creating a budget for a project and sticking to it as closely as possible, moderating spending and reallocating funds when necessary.
Maintenance encourages constant product testing to discover and fix bugs early, adjust the end product to the customer’s needs, and keep the project on target. 
  
  ref:https://www.wrike.com/project-management-guide/faq/what-is-software-project-management/
Challenges faced in managing software projects:
1. Scope creep
2. Poor planning and unrealisic deadlines
3. Lack of accountablility

 ref:https://www.koombea.com

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Software Maintenance:

Software Maintenace is the process of modifying ,changing and updating a software system or module to resolve errors ,improve performance or adopt to a changing environment

   ref:https://radixweb.com

Different types of maintenace activities 
Adaptive Software Maintenace-about changing software in response to changes in its       
                             environment
Perfective Software Maintenace-focus on functional enhancements to improve the user     
                               experience
Corrective Software Maintenace -correcting software bugs,errors and defects
Preventive Software Maintenance -definesthe adoptations and modifications of the software 
                                 that mitigate the deterioration risk

    ref:https://radixweb.com


Maintenace is essential to ensure software continues to meet user needs and remains relevant

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Ethical Considerations in Software Engineering:

 Ethical issues might face:

 Privacy and Confidentially
 Social Vulnerable populations
 Individual resposibility
 Race and Ethinicity
 Implentation issues
     ref:https://www.ncbi.nlm.nih
Can ensure they adhire to ethical standards by:
Staying up to date with laws and regulations (e.g . data privacy laws)
Implementing ethical design principles(e.g value sensitivity )
Conducting ethical impact assessments(e.g privacy,security,bias)
familiarizing themselves with industry codes and guidlines (e.g IEEE Code of Ethics)
      Ref:"Ethics of software Engineers" by IEEE 



What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
