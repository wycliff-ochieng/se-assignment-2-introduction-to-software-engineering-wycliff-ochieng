[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15248143&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
it is a branch of computer science that deals with design,testing,implementation,development and maintenance of software applications


What is software engineering, and how does it differ from traditional programming?
software engineering is th process of designing,developing,implementing and maintaining software applications while on the hand traditonal programming involves writing code to solve a specific problem or create a specific software application

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.


Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Agile model-it is an incremental approach to software development and involves delivering small, working pieces of software in short iterations. Agile models allow for frequent feedback and course correction which ensures the final product meets the needs of the users
Waterfall madel-is a linear, sequential approach to software development. It involves completing each phase of the SDLC before moving on to the next phase. This approach is often used for projects with well-defined requirements and a clear understanding of problems to be solved .

(REFERENCE: geeksforgeeks.org)


Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirements Engineering is the process of identifying, eliciting, analyzing, specifying, validating, and managing the needs and expectations of stakeholders for a software system.It is crucial as it  involves working with stakeholders to understand their needs and translating those needs into clear, concise, and testable requirements. Requirements engineering is an important part of the software development process, as it helps ensure that the final product meets the needs of its users.

(REFERENCE: geeksforgeeks.org)

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Modularity is a fundamental principle in software desighn where it focuses on breaking down complex systems into smaller, independent and reusable units called modules.It improves maintainability as smaller modules are easier to understand and debug, new feature can be added by creating a new module instead of modifying existing ones and changes within a module are less likely to break other part of the given systems and concerns are separated. Scalability is improved as modules can either be added or removed when needed and can also be independently optimized for performance and functionality

(REFERENCE: geeksforgeeks.org)

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

Unit testing-Focuses on individual units of testing i.e classes,function,modules.It ensures that each unit performs its intended functions correctly in isolation
Integration testing- Focuses on how different modules interact and work together.It ensure modules communicate efffectively and data flows smoothly between them
System testing-Focuses on entire software system as a whole as it makes sure system fulfills its overall requirements and performs as expected in a simulated real world environment
Acceptance testing-Focuses on whether the software meets the user's needs and acceptance criteria as it ensures software delivers full value and meets user's expectations
Testing is crucial in software development because it improved quality of software by identifying and fixing bug before software is deployed, reduces cost as defects and bugs are identified before reaching advanced stages of SDLC and enhances reliability as well tested software increases confidence that it will worl=k in different environments upon deployment

(REFERENCES FROM www.tutorialspoint.com)

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

Version control systems are essential tools in software development that track and manages changes to code over time
and act like a digital filing systems to your codebase
    importance of version control system
(a)Improved Code Quality: VCS helps maintain code stability by allowing rollbacks and facilitating collaboration without accidental overwrites.
(b)Enhanced Development Speed: Streamlines the development process by enabling parallel work on different features and faster issue resolution.
(c)Better Project Management: VCS provides a clear audit trail of code changes, aiding project management and decision-making.
(d)Collaboration Efficiency: Enables smooth teamwork by allowing developers to work on different parts of the codebase simultaneously.
(e)Historical Reference: Provides a record of all changes made to the codebase, aiding in understanding code evolution and identifying the source of bugs.
     Examples of version control systems
(a)Git - has distributed architecture and  good branching strategies 
(b)Subversion - has centralized server, easy to leaarn and use and has good access control
(c)Mercurial - has distributed architecture, lightweight and efficient and good for large projects

(REFERENCES FROM www.tutorialspoint.com,geeksfofgeeks.org)

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

A software project manager  acts as the central figure in guiding a software development project from conception to completion.Their core role is to ensure the project is delivered on time, within budget, and meets all the defined requirements.
    key responsibilities
-Define project goals and objectives.
-Assemble and lead a cross-functional team (developers, designers, testers) and delegate tasks to them effectively
-Identify and assess potential risks that could derail the project and develop mitigation plans to address those risks.
-Maintain clear communication with stakeholders 
-Monitor project expenses and stay within budget constraints.
    challenges faced in managing projects
-Pressure to deliver the project on unrealistic timeframes.
-Unforeseen changes or additions to project requirements after the initial planning stage.
-Keeping up with the ever-evolving software development landscape and adapting to new technologies.
-Building a cohesive and productive team environment with diverse personalities and skillsets.
-Ensuring clear and consistent communication between all stakeholders (team, clients, management).

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Software maintenance is the process of updating and modifying software after it has been deployed to ensure the software continues to function as intended, meets user needs, and adapts to a changing environment.
  Types of maintenance activities
(a)Corrective maintenance-Identifying and fixing bugs, errors, or defects reported by users
(b)Perfective maintenance-Enhancing the software's functionality, usability, or performance by adding new features, improving user interfaces, or optimizing code for efficiency.
(c)Adaptive maintence-Modifying the software to adapt to changes in the external environment.This includes adapting to new operating systems, hardware platforms, regulations, or business requirements.
(d)Preventive maintenance Proactively identifying and addressing potential issues before they cause problems.
  why software maintenance is crucial
(a)Ensures Reliability and Uptime by fixing bugs and addressing issues preventing unexpected crashes or malfunctions, leading to a more reliable and stable software experience.
(b)Improves Performance as regular maintenance can optimize code and system resources, leading to improved performance and responsiveness.
(c)Enhances Security since new security vulnerabilities are discovered regularly.
(d)Maintains User Satisfaction by addressing bugs, adding features, and keeping the software up-to-date, maintenance keeps users happy and engaged.

(REFERENCES FROM www.tutorialspoint.com)

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Privacy and Security: for example  a social media engineer might deal with the ethical implications of collecting user data or implementing features that track user behavior extensively.

Bias and Fairness: An engineer working on a resume filtering algorithm might have to consider how the algorithm could perpetuate biases based on race, gender, or keywords.

Transparency and Explainability: for instance developers of a loan approval AI system might face pressure to keep the algorithm's inner workings secret, hindering transparency and accountability in loan decisions.

Environmental Impact: i.e Software engineers designing cryptocurrency mining software might need to weigh the potential benefits against the high energy consumption associated with mining.

    how software engineers ensure they adhere to ethical standards
(a)Staying informed about ethical issues in software development and potential consequences of their work.
(b)Considering the broader societal impact of their work and potential risks before deploying software.
(c)Following established codes of ethics set by professional organizations 
(d)Speaking up against unethical practices and promoting responsible software development within their teams and organizations.
(e)Pushing for clear and open communication about data collection practices, algorithmic decision-making, and potential biases.


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
