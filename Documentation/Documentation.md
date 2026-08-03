# **StudyZone**
## **Focus, Build, Improve.**
### **DEVELOPED BY TechLemon99**
# **![](/img_assets/StudyZone.png)**

# **✤ Section 1 \- IDENTIFYING AND DEFINING**

## **⇒ 1.1 \- Problem Statement ⇐**

* Outline the problem or opportunity that the project addresses. Consider who is affected by this issue.  
* Explain why this problem or opportunity is significant.  
* Justify the development of a software solution as an appropriate response.

In modern society, digital distractions such as video games and social media significantly impair focus and negatively affect the mental health, productivity, and academic performance of people worldwide. The human brain's naturally programmed craving for dopamine makes it susceptible to these distractions, particularly through doomscrolling apps like YouTube Shorts and TikTok, which promote instant gratification and reduced attention spans to victims all around the world. 

Existing productivity tools address only specific aspects of this issue, such as task management or time tracking, rather than providing a comprehensive system intricately designed to support focus and self-discipline. As a result, I feel the need for a unified platform that can help people feel truly confident about embarking on a journey to cure their internet and video game addictions and rewire their brains after a long history of procrastination. 

 This project, StudyZone, aims to challenge and fight against these ever-growing issues of internet and video game addictions by providing an integrated environment with productivity tools, task tracking, focus timers, and many other useful motivational features to help users improve concentration and develop healthier study habits, properly addressing the need for such a unified platform.

## **⇒ 1.2 \- Project Purpose and Boundaries ⇐**

* Outline what the project is trying to achieve.

### **The Purpose**

The ultimate purpose of StudyZone is to design and develop a multi-functional application related to self-improvement and productivity that helps users improve concentration, manage their time efficiently, and reduce digital distractions during study or work sessions. The application aims to provide a fully centralised platform where registered users can organise tasks, track goals, and access built-in productivity tools such as a Pomodoro timer, task manager, and focus-enhancing utilities designed to reeducate and rewire the brain to mitigate procrastination. StudyZone’s core goals are to encourage consistent study and working habits and boost the overall long-term productivity rates of individuals by combining multiple productivity functions into one single application. With these purposes in mind, the system will be intuitive, reliable, and visually engaging enough to encourage regular use from stakeholders who frequently struggle with maintaining focus.

### **The Boundaries**

There are certain boundaries that must first be clearly defined to maintain a manageable project development scope for the application. First of all, StudyZone will focus more on desktop functionality rather than full mobile deployment, and it will operate as a standalone productivity application rather than being an add-on needing to be integrated directly with external social media or learning platforms. Aside from that, highly advanced features such as cloud synchronisation, large-scale online data storage, or AI camera detection systems will not be implemented within the foreseeable scope of this project due to highly difficult mechanisms involved in their development and user privacy concerns. The current plan is to store user data locally using structured data formats so that retrieval is efficient alongside basic up-to-standard security features.

## **⇒ 1.3 \- Stakeholder Requirements ⇐**

* Identify stakeholders (client, users, teacher, peers).  
* Describe their needs, expectations, and how these influenced the project direction.

### **Stakeholders**

The main stakeholders of the project are students, teenagers, young adults, and other users of all ages or races around the world who share the universal issue of struggling with distraction, poor time management or low motivation while attempting to study or work. 

### **Their Needs**

These stakeholders all need a functional application that is easy to use, visually engaging, and capable of helping them stay focused at the same time without needing them to feel excessively overwhelmed by the internal application mechanics. 

### **Their Expectations**

They would expect practical tools, such as task trackers, timers, reminders and progress features that support productivity in a simple and organised way. They would also expect these tools to be fully effective and functional at all times, rather than just being there for no reason. 

### **How do their needs influence the project direction?**

The stakeholders’ needs influence the direction of StudyZone by requiring the software to prioritise usability, convenience and features that directly support focus and self-improvement, allowing them to comfortably reset their brains and become their better selves without any extra unnecessary struggle.

## **⇒ 1.4 \- Functional Requirements ⇐**

* List and describe what the system must do.

**REQUIREMENT 1:** The system must allow users to create, view, edit, and delete their to-do tasks, goals, note entries, and reminders. The system must also allow users to manually select the tasks they have completed. Users must be able to organise their work, update tasks as priorities change, and remove tasks that are no longer needed. Similarly, the system must also allow users to mark sessions as completed by implementing completion tracking mechanics. This is a very important requirement since it allows users to truly feel their progression.

**REQUIREMENT 2:** The system must be able to track user progress. For example, the application may record completed tasks, completed study sessions, streaks, or productivity statistics. The system must also display measurable improvement over time so that users can feel motivated to continue their progress. As a result, the system will need to provide a method to display such progress visually. This may include labels, charts, progress bars, text summaries or anything else that allows users to quickly understand their performance.

**REQUIREMENT 3:** The system must provide a graphical user interface for interaction. The user should be able to interact with features through buttons, menus, text fields and visual screens rather than through simple command-line input. Besides this, the system must also allow the user to easily navigate through different sections of the application without major problems. This is crucial for the overall usability and accessibility of multi-functional programs like this application.

**REQUIREMENT 4:** The system must validate user input where necessary. For example, the program should prevent empty task names, invalid dates or incorrect data entry. On top of this, the system must also be able to handle errors properly and gracefully, providing clear, detailed error messages with the capability of recovering quickly after encountering errors during runtime.

**REQUIREMENT 5:** The system must include motivational or focus-support tools designed to help users improve themselves. This could potentially include encouraging messages, habit-building tools and trackers, goal planners, Pomodoro timers, and aim trainers designed to help individuals improve their physical abilities, such as hand-eye coordination. Having these features is central to the functionality of the program since they help users improve focus and self-discipline.

## **⇒ 1.5 \- Non-Functional Requirements ⇐**

* List and describe system qualities such as:  
  * Performance  
  * Usability  
  * Security  
  * Reliability

**Performance:** The system must respond quickly to user input, load screens efficiently, and perform actions such as saving data or switching pages without any noticeable delay. The system must also not freeze or crash when errors are encountered. Performance is extremely important for this project because the whole program itself is designed to support concentration, and as a result, slow performance would likely interrupt the workflow and reduce the overall user experience.

**Security:** User data must be stored safely and protected from corruption or misuse. The system must ensure that all user input is properly validated and sanitised to defend itself against attacks. The system must prioritise user privacy issues at all costs and minimise its chances of getting attacked or breached. Even in scenarios where it faces a serious attack from criminals, the system must not expose any vulnerable user data. To enforce this, secure coding practices will be strictly implemented under the “security-by-design” principle.

**Reliability:** The program should operate consistently without frequent crashes, broken features, data loss, or any other vulnerabilities that can reduce the trust between the user and the system. The system must be reliable so that users can trust that their tasks, progress and study data will remain accurate and available at all times. The system must also consider data integrity, ensuring that the user’s data is unchanged while at rest.

**Usability:** The interface should be intuitive, simple to navigate, and easy for users to understand without needing technical knowledge. Buttons, menus, labels, and layouts should be clear and consistent so that users can use the program efficiently.

**Accessibility:** The application should be designed so that a wide range of users can interact with it comfortably. This includes readable font sizes, clear contrast between text and background, logical layout structure, and controls that are easy to identify and use.

**Maintainability:** The code should be organised into clear sections and modules so that the software can be updated, debugged and improved more easily over time. This is extremely important because large projects like this oftentimes need to add new features or refine existing features post-development as part of the maintenance process. As a result, the system’s ability to maintain itself will have a big role since this dictates how efficient the maintenance process will be. 

## **⇒ 1.6 \- Project Constraints ⇐**

* Identify limitations affecting the project, such as:  
  * Time  
  * Technical knowledge  
  * Hardware/software access

One major constraint in the project's development is the extremely tight deadline. The whole project has a lead time of less than two terms, with one of the terms spent on the Identifying and Defining as well as the Researching and Planning phases. This restricts the time available for programming, testing, evaluating and polishing, making it impossible for me to develop all planned features to their full complexity. This means that I must prioritise the most essential and feasible features of the app, while more advanced ideas may need to be simplified or excluded. Additionally, the project must remain within manageable boundaries since it is a school assessment, meaning that the focus will be on features that significantly impact StudyZone, addressing the core issues of distraction and poor study habits rather than attempting to include every single productivity-related feature in existence.

Another constraint of the project is my technical ability to create the program. Despite having much experience in coding projects, this one is different since it has to be crafted and polished to the maximum standard in order to reflect what I’ve learned from this course in the past few years. I have limited technical knowledge, meaning that I would definitely struggle to create some features for this program. I can still utilise my current understanding of Python and software design principles to accomplish some aspects of the project, but highly advanced features like cloud synchronisation, extremely detailed animations, AI-driven features or enterprise-level security systems will be impossible for me to create within the given time due to my lack of professional software knowledge. Therefore, I must design and develop the software in a way that remains challenging but is still realistic and manageable.

## **⇒ 1.7 \- Requirements Analysis and Prioritisation ⇐**

* Analyse the functional and non-functional requirements. In your analysis, consider:  
  * which requirements were prioritised and why,  
  * trade-offs made due to constraints,  
  * how requirements align with the identified problem or opportunity

### **Prioritized Requirements**

**FUNCTIONAL \-** The highest-priority functional requirements are the ability to create, manage, and complete tasks, track progress, provide a graphical user interface, and include focus-support tools such as Pomodoro timers and motivational systems. These are prioritised because they are the core features that directly address the identified problem. Without task management, users cannot organise their work. Without progress tracking, the app will almost lose all of its motivational value. Without a GUI, the app would not be practical and engaging enough for everyday users. Without focus-support tools, the software would fail to meaningfully separate itself from a basic to-do list application. In summary, these features are prioritised because they are the most important features that define the application as what it is and what it does.

**NON-FUNCTIONAL \-** Among the non-functional requirements, I treat performance, reliability, usability and security as the highest priorities. Performance is essential because delays, lags and errors in the system would interrupt concentration, which directly conflicts with the overall purpose of this program. Reliability is also critical because users must be able to trust that their data will not be lost or corrupted. If the user fails to trust an app due to reliability issues, then the application has basically failed its purpose of satisfying its users. Usability is also a high priority because the program should be clear and intuitive enough for the user to use, or otherwise the overall user experience (UX) might decrease since the program is too mentally exhausting to use. Lastly, security is listed as one of the top priorities for this project because it revolves around the concept of security. Security is a top-notch must-have aspect of this program because the application will need to store personal productivity data, and it is my utmost responsibility to ensure that the data is handled safely, securely, and responsibly.

### **Trade-offs Made Due to Constraints**

Due to the project’s time limit, available hardware, and my current technical knowledge, it is certain to say that I will definitely face issues that will result in trade-offs for this project. First of all, I will be sacrificing some highly advanced features like cloud storage, cross-platform mobile deployment and large-scale online databases in order to develop and polish the features that are truly crucial to this application. The idea is to sacrifice these advanced features, marking them as “trade-offs”, and shift the focus from high-end development to building a stable desktop-based app with strong local functionality and structured data storage.

Another trade-off that might be necessary for this project involves balancing feature quantity against software quality. Currently, I have many tools in mind that I would like to add to this application in order to maximise its utility. But if I look at a more realistic scope, then having too many features could reduce the development quality and increase the risk of bugs or incomplete implementation because I would need to spend more time on the development phase and less time on the testing and debugging phases. Since I would like to balance out the allocated time for each phase equally, I will need to focus more on the core features and less on the optional extras.

### **Alignment with the Identified Problem or Opportunity**

The prioritised requirements align strongly with the identified problem because they are specifically designed to help users reduce distraction, organise their responsibilities, and build better study habits. Functional features such as task management, focus timers, and progress tracking systems will be able to provide direct solutions to growing issues of poor organisation, lack of motivation and procrastination, while the non-functional qualities such as usability, reliability, and accessibility can ensure that these features are actually effective in practice rather than simply existing in theory. In summary, these functional and non-functional requirements ensure that StudyZone remains focused on its central purpose: **to create a practical, reliable, and motivating application that helps users become more disciplined and productive despite all the distractions of modern life.**

# ──────────────  ⋆⋅☆⋅⋆ ───────────────

# **✤ Section 2 \- RESEARCHING AND PLANNING**

## **⇒ 2.1 \- Development Methodology ⇐**

* Describe the development approach used (e.g. Agile, Waterfall, WAgile).  
* Justify the suitability of this methodology. You could consider…  
  * Project size and complexity  
  * Time constraints  
  * Feedback and iteration requirements

### **The WAgile Approach**

The development methodology I will use for StudyZone is the WAgile approach. This is a hybrid model that combines elements of both the Waterfall and the Agile methodologies. Waterfall is a linear and structured approach where each phase of development is completed before moving on to the next, and Agile is an iterative approach that focuses on continuous development, testing, and improvement. WAgile integrates the strengths of both by maintaining clear planning and documentation while simultaneously allowing for flexibility and continuous improvement over time. For this project, I will start with a Waterfall phase for Identifying and Defining, Researching and Planning, and System Design, in order to lay the foundation for this project. Once the foundation is set, I will shift to the Agile approach to create my sprints for Producing and Implementing, as well as Testing and Evaluation. I like to use the WAgile approach for many of my projects because it is an extremely versatile approach to programming, since the project’s "what" is defined by Waterfall (fixed scope), while the project’s "how" is handled by Agile (flexible implementation). By using WAgile for this project, I strongly believe that StudyZone can become more flexible, with reduced structural risks and better stakeholder alignment.

### **Why is WAgile a Suitable Methodology for This Project?**

I strongly believe that the WAgile approach is extremely suitable for this project due to the sheer amount of size and complexity included in my application. Because StudyZone includes many different interconnected features, each of them having immense complexity and mechanics, I believe that it would be exceptionally difficult to build everything in a single linear process. However, WAgile is a more iterative approach than just Waterfall since it combines both Agile and Waterfall. WAgile’s iterative nature can allow each component in my application to be developed and improved gradually, which can make the project much more manageable. I also believe that the WAgile approach is well-suited to the project’s time constraints. The project has a very limited development period of only two terms, so I have to ensure that the development progress is consistent and that the core features are completed early. Because WAgile combines the structured planning aspect of Waterfall with the iterative development aspect of Agile, this means that WAgile can allow the project to remain both organised and adaptable within such a limited timeframe. 

## **⇒ 2.2 \- Tools and Technologies ⇐**

* Justify the selection of software applications, engines, developer tools, programming languages, IDEs, frameworks, libraries and/or hardware components.  
* Explain how these tools supported efficient and effective development.

### **Software Applications**

Canva will be used to design the visual assets, such as the StudyZone logo, icons, and interface elements, where possible. These assets can be imported into the main application to improve its visual appeal and create a more engaging experience for the user. Using Canva can make the application look more professionally designed, since Canva offers users the ability to design intricate visual elements without requiring too much graphic design skill. 

### **Programming Languages**

The primary programming language selected for this project is Python. It is very suitable for StudyZone due to its simplicity, readability and extensive library support. Python offers a relatively simple and readable syntax that closely resembles the English language. This means that I would be able to debug the code more easily, leading to a reduction of errors and making the project more maintainable. Python also supports a wide range of libraries that can be integrated if needed. This is extremely useful since these libraries can be used to create many features in the application.

### **Development Environment \- IDEs**

The project will be developed using Visual Studio Code as the Integrated Development Environment (IDE). I chose Visual Studio Code because it is easy to use and also provides essential tools needed for the development of the application, such as syntax highlighting. I also decided to choose Visual Studio Code because I have lots of experience with this IDE, and it is also the IDE on which I have spent the most time developing other projects.

### **Frameworks**

The primary framework I will use to design the graphical interface of the application is Tkinter, which is included with Python and also provides the ability to create tools for user interaction, such as windows, buttons, labels and any other interface components. I believe that Tkinter is an excellent choice for this project because it is a very lightweight framework that is easy to implement while also being compatible with Python itself. Additionally, Tkinter is exceptionally capable of producing outstanding user interfaces that align perfectly with user needs as well as the core goals of the application.

### **Libraries**

The application will feature many built-in Python modules, such as the random module. They are part of the standard Python library, meaning that they do not need to be installed via pip. However, built-in Python modules are all relatively simple. Since StudyZone will be an extremely complicated application, I will need to expand beyond built-in Python modules. This means that most of the application will be built with 3rd-party Python libraries, such as the requests library used for API interactions. These 3rd-party Python libraries will need to be installed via pip or requirements.txt. Some ideas for possible 3rd-party libraries I can integrate into the application include Pandas, which could be used to manage and analyse user data such as task completion records or productivity statistics. Matplotlib could also be used to generate visual representations, such as graphs or progress charts. These libraries would support the functional requirement of tracking and displaying user progress. However, there are numerous other Python libraries out there waiting to be discovered, and eventually, more of them will be included in the application depending on how useful they are to StudyZone. I will do more research on this as I begin the actual coding process.

Since Tkinter does not support HTML natively, I also have to include a 3rd-party library that acts as a bridge between Tkinter's windowing system and HTML/CSS rendering. Possible 3rd-party libraries in this scenario include TkinterWeb or tkhtmlview, although the former is more likely since it directly provides an HTMLFrame widget that can render modern HTML and CSS directly inside a Tkinter window, ideal for creating complex layouts like registration forms.

### **Hardware Resources**

This project will mostly be developed on two separate sets of devices, the first set being a Dell laptop connected to an external monitor, and the second set being a school desktop computer connected to an external monitor. Although sounding simple, they can actually provide a decently stable and practical development environment. I can take advantage of the dual-screen setup to improve productivity, since this setup allows me to view code, documentation, and the running application simultaneously. The hardware is sufficient enough to support Python development, GUI rendering, and testing without major performance issues.

## **⇒ 2.3 \- Gantt Chart / Timeline ⇐**

* Include a timeline showing key project milestones.  
* Explain how time was allocated to planning, development, testing, and evaluation.

**NOTE:** No milestones are highlighted because this Gantt Chart is made as a start-of-project time management outlook rather than a whole end-of-project review of my time management throughout the task, meaning that this is how I wish my time developing this would be like. This Gantt Chart is made in Section 2\. For the Gantt Chart which would be made in the foreseeable future that will have milestones labeled on them (since the milestones are supposed to be when I actually completed the sections of the task), I will put it into Section 6 or 7 as a fully updated end-of-project review.  

![](/Documentation/img_doc/Gantt%20Charts/GanttChart1.png)  

I’ve started planning my project since around Week 4, and started working on the documentation since Week 5\. In Week 4, I did a lot of background research regarding study apps, and as a result I’ve developed a somewhat substantial knowledge base regarding these types of apps. By the start of Week 5, I’ve locked in on my decision of creating a multi-functional study and habit application for this project.

For the entirety of Week 5, I’ve finished writing the problem statement, project purpose/boundaries, and the stakeholder requirements. This may seem like slow progress, but I also had to spend a lot of time researching for resources and other materials I would need to know about in order to create such a complicated program. 

## **⇒ 2.4 \- Communication Plan ⇐**

* Explain how client or peer feedback was obtained and incorporated.

### **Obtaining Feedback**

Feedback will be collected at multiple stages of development rather than only at the end when I begin the evaluation process. Early in the development process, initial concepts and UI designs for the application will be created and then carefully examined. After proper examinations and adjustments, these designs may then be sent to peers for general review and subtle feedback. Their opinions on the application's layout, usability, and feature ideas can be gathered and used to boost productivity during the development phase, as I will be able to identify potential design issues before development begins.

During the development phase, working prototypes and small segments of the overall code will also be shared with peers for minor testing during development. These small segments of code will give access to partial, unfinished versions of the program. Feedback through digital social media or programming forums may also be acquired in desperate situations. Users will be asked to perform specific tasks, such as creating a to-do list, using the timer, or navigating between sections of the program. I will carefully record their feedback and suggestions. Their experiences and difficulties while using the app will be observed and responded to.

### **Incorporating Feedback**

The feedback collected will be carefully analysed and prioritised based on its relevance to the core goals of this project. I will create a list of problems that must be addressed as soon as possible by carefully reviewing the feedback from testers. These problems will then be categorised from most important to least important. The most important problems will be the ones that directly impose a negative impact on the usability, functionality, and reliability of the application, since they have the greatest impact on the user experience. These problems will be addressed first through rigorous effort to re-evaluate the code.

Improvements will be implemented in stages, following the WAgile approach. After each development cycle, changes will be made according to the feedback received. Afterwards, the updated version of the application will be tested again, creating a continuous feedback loop. I believe that this is a very healthy feedback system since it allows the system to be constantly refined and improved.

# ──────────────  ⋆⋅☆⋅⋆ ───────────────

# **✤ Section 3 \- System Design**

## **⇒ 3.1 \- Context Diagram (Level 0 DFD) ⇐**

* Include a context diagram showing system boundaries and external entities.

![](/Documentation/img_doc/Data%20Flow%20Diagrams/ContextDiagram.png)

## **⇒ 3.2 \- Level 1 Data Flow Diagram ⇐**

* Illustrate how data moves through the system.

![](/Documentation/img_doc/Data%20Flow%20Diagrams/Level1DFD.png)

## **⇒ 3.3 \- Structure Chart ⇐**

* Show the modular structure of the system and relationships between modules.

![](/Documentation/img_doc/StructureChart.png)


## **⇒ 3.4 \- IPO Chart ⇐**

| Input | Process | Output |
| :---- | :---- | :---- |
| Username Password Registration Details | Validate Input Check existing user Store/retrieve credentials | Login success/failure message User authentication status |
| App Open Event (When user launches app) User Activity Data | Check last login date Check streak conditions Update streak value Repeat daily tracking | Updated streak count Streak popup notification |
| User Navigation Input (Button clicks, menu selection, etc.) | Handle Navigation Logic Load selected module | Updated screen (dashboard, timer, tasks, etc.) |
| Task Data (title, deadline, priority, completion input, etc.) | Validate input Store/update/delete task Repeat for multiple tasks | Updated task list Task completion status |
| Completed Tasks Timer Sessions | Record activity Update statistics Calculate totals | Updated progress data Updated user performance statistics |
| Timer Settings (duration, start/pause/reset) | Start timer Run countdown loop Check pause/resume | Timer countdown display Session completion |
| User Interaction with Internal Tools (mouse clicks in the aim trainer, reaction input in the reaction time trainer, etc.) | Detect input Validate input Calculate speed Calculate accuracy Evaluate performance | Performance results |
| Current Date  Python DateTime module System Time | Retrieve current date and time data Format into calendar layout | Calendar displayed to user with correct month |
| User Input  (Calendar Day Box) Selected Date | Detect selected date Store selected day Open text box Save user calendar entry | Selected date highlighted Display events for selected day Event stored successfully  |
| Calendar Data Stored Event Data | Load all stored events Check for upcoming events Sort by date | Upcoming events list displayed for the entire calendar |
| Stored Progress Data | Retrieve and analyse data Generate statistics | Graphs Reports Performance summaries |
| User Performance Data Streak value | Analyze performance trends Select appropriate motivational message | Motivational feedback message Additional advice |
| Goal Title Description Timeframe (Daily/Weekly/Monthly/Yearly/Custom) Deadline | Validate input Check for missing/invalid data Format goal structure | Validated goal data |
| User Request to View Goals | Retrieve goal data Filter by timeframe | Displayed goal list |
| User Text Entry (Sticky Notes/Journal/Blog) Title | Validate input Check for empty fields Format content | Validated entry ready for storage |
| Raw Entry Data | Save entry to storage Organise by user and timestamp | Entry stored in system database |
| Stored Entry Data Entry Category | Analyse stored entries Organize chronologically Determine entry category Assign access permissions | Organised user entries by chronological order Public entries (blogs) visible to everyone Private entries (sticky notes/journals) displayed securely to author only |
| User Profile Data (profile info, history, etc.) | Load user profile Compile statistics | Dashboard display (user profile \+ stats) |
| File/Data Storage (JSON/SQL) | Save data Retrieve data Validate integrity | Persistent, up-to-date user data Updated Storage |

## **⇒ 3.5 \- Data Dictionary ⇐**

| Variable | Data Type | Format | Size (bytes) | Description | Example | Validation |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| user\_id | integer | NNNN | Varies | Unique integer identifier for each user | 1076 | Must be unique for each user |
| username | string | Text | ≤ 20 | User’s account name, used for login | levinshao021 | Alphanumeric only; no spaces |
| password | string (hashed) | Encrypted | 64 | Secure user password | (hashed value) | Minimum 8 chars; stored as hashed value |
| login\_status | boolean | True/False | 1 | Indicates if user is logged in | True | Automatically updated |
| task\_list | list\[dict\] | List | Varies | Stores all user tasks | \[{task1}, {task2}\] | Cannot be empty structure |
| task\_name | string | Text | ≤ 50 | Name of task | “Finish developing StudyZone by next term” | Cannot be empty |
| task\_priority | integer | 1-5 | 1 | Importance level of the task; 1 is most important, 5 is least | 2 | Must be an integer between 1-5 |
| task\_due\_date | date and time | YYYY-MM-DD | 10 | Task deadline | 2026-05-30 | Must be a date in the future |
| task\_completed | boolean | True/False | 1 | Completion status of the task | False | Default \= False |
| tasks\_completed | integer | NNN | 4 | Total amount of completed tasks | 32 | Must be greater than or equal to 0 |
| study\_time\_total | float | NN.N hrs | 4 | Total study time | 42.8 hrs | Must be greater than or equal to 0  |
| streak\_days | integer | NNN | 4 | Consecutive days studied, resets when the user doesn’t log in to the app for a day | 18 | Must be greater than or equal to 0 |
| session\_duration | integer | N hrs NN mins | 3 | Length of study session | 2 hrs 13 mins | Hours and minutes, both values must be greater than or equal to 0 |
| break\_duration | integer | NN minutes | 2 | Length of break | 30 mins | 1-60; if break time surpasses 60 minutes, study session automatically ends |
| timer\_state | string | Running/ Paused/ Stopped | ≤ 10 | Current status of timer | Running | Must match valid states |
| goal\_list | list\[dict\] | List | Varies | Stores all goals | \[{goal1}, {goal2}\] | Cannot be empty |
| goal\_title | string | Text | ≤ 50 | Name of goal | “Jog 5 km daily” | Cannot be empty |
| goal\_type | string | Daily/ Weekly/ Monthly/ Yearly/ Custom | ≤ 10 | Goal category | Daily | Users must only be able to select the five options listed |
| goal\_completed | boolean | True/False | 1 | Completion status of the goal | False | Default \= False |
| calendar\_grid | 2D array | 7x5 or 7x6 | Varies | Calendar layout (weeks x days) | \[\[1,2,3…\]\] | Must follow a standard calendar structure |
| has\_event\_flag | boolean | True/False | 1 | Indicates if a day has events | True | Auto-calculated based on calendar and events data |
| selected\_day\_flag | boolean | True/False | 1 | Highlights the selected day of an event | True | Only one true at a time |
| entry\_list | list\[dict\] | List | Varies | Stores all sticky notes/journal/blog entries | \[{entry1}\] | Cannot be empty |
| entry\_title | string | Text | ≤ 50 | Title of the entry | “26/04/26 \- Today was productive\!” | Cannot be empty for blogs or journals; optional for sticky notes |
| entry\_content | String  | Text | ≤ 300 OR ≤ 5000 | Main content of the entry | “Although I studied well today, there were so many things I could have done better on…” | Cannot be empty for any category of entry.  |
| entry\_date | date and time | YYYY-MM-DD HH:MM | 16 | Timestamp of the entry, i.e. when it was written | 2026-04-26 21:30 | Auto-generated using time modules |
| reaction\_time | float | NNN.N ms | 6 | User reaction speed | 180.5 ms | Value greater than 0 |
| best\_score | float | NNN.N ms | 6 | User’s best performance in reaction time trainer | 128.6 ms | Value greater than 0 |
| attempts | integer | NN | 2 | Number of attempts | 12 | Value greater than 0 |
| feedback\_text | string | Text | ≤ 300 | Feedback message for the user based on performance statistics | “You can do it. The key is to never give up, no matter what\!” | Random; Cannot be empty |

## **⇒ 3.6 \- UML Class Diagram ⇐**

* Include a class diagram which explains the class structure and relationships.

![](/Documentation/img_doc/ClassDiagram.png)

# ──────────────  ⋆⋅☆⋅⋆ ───────────────

# **✤ Section 4 \- Producing and Implementing**

## **⇒ 4.1 \- Development Process ⇐**

* Describe how the solution was built and implemented.  
* Justify the engineering techniques used, such as:  
  * Modular design  
  * Object-oriented principles  
  * Reuse of code  
  * Validation and error handling

I used the WAgile approach for the development of this task. Each feature was built slowly and progressively, and I ensured to test for bugs after they were properly implemented. I started with the most essential features, such as the registration & login pages, since the app would be impossible to access without them. After they were finished, I began with the most important features, such as the task tracker and goal planner features. After the foundation had been laid out, I began to work on some sub-programs, such as the user settings page and music dashboard, ensuring that they function well before moving on to the next. Using this approach provided lots of organisation and simplicity since I was able to have a clear outlook for the program’s design while building it at the same time.

The design solution was built with Python and implemented with Tkinter. Each function of the system was made with lots of code for widgets, such as code to build frames, text boxes, input fields, and bars at the top of the utility modules. Code was also reused for some parts of the system where the mechanics for their function aligned similarly with each other. For example, the task tracker and goal tracker were similar in nature, both being trackers with similar UIs; therefore, I copied and pasted the code used for the task tracker into the goal tracker file, then changed up some things, such as removing the priority dropdown field and reintroducing it as a toggle button instead. I had also used strategic integration for the program, meaning that I broke each function down into smaller chunks and put them into many different files so that they could be integrated into the main.py file for use. Each different screen had its own file, and files that belonged to the same feature were put into a bigger folder. By separating a megafile with many lines of code into smaller pieces linked together, this allowed the entire program to remain internally neat and maintainable, since the code had become more organised and readable.

## **⇒ 4.2 \- Key Features Developed ⇐**

* Describe the core features of the system.  
* Justify their inclusion.

The way my program works is that when you register/log in, you will be taken to the main menu, where you can access lots of multi-functional tools located within “squares”. There are 2 rows of squares in the main menu, and each square has 5 columns, adding to 10 squares in total. I utilised this design since it felt clean, simple and also makes the app very easy to navigate. 

#### **SQUARE 1:** Productivity

Since the whole point of the application is to make it as satisfying to use as possible, I added a separate menu used for tracking users’ wants, including the task tracker, goal tracker, and habit tracker. These trackers are essential to my program since it was designed for self-improvement and studying, so users have a fundamental right to be able to list their upcoming tasks for studying and goals/habits for self-improvement. A fitness tracker was also planned to be developed, but unfortunately did not make it before the due date.

#### **SQUARE 2:** Study Tools

This menu is called the StudyMenu. A digital notebook feature was designed for note-taking and organisation. It includes a flashcards system for effective memorisation, a pomodoro timer for improved study habits and time management, and a basic calculator for simple primary school level arithmetics, with plans for future enhancements. 

#### **SQUARE 3:** Calendar \+ Reminders

This is a very simple and self-explanatory calendar system. Initially, the calendar function and the reminder function were planned to be separate in two different squares, but later they were merged into one. This decision was motivated by the fact that calendar and reminder systems were already very similar in nature, so I was able to design it in a way that allows users to both be able to view the calendar and also add events to certain dates by clicking on the dates within the calendar.

#### **SQUARE 4:** Creativity

This section allows users to express creativity, featuring an art pad for drawings. Originally part of the “Express Yourself” menu, it has been restructured into the Creativity tab, while other components like the journal are now under the Mindfulness Portal. Future updates will include a Library for writing and publishing books and a mind map creator. They will be included since I believe that creativity has the ability to unlock a portal that can ascend the human mind. 

#### **SQUARE 5:** Skill Trainers

This is the Skill Training menu where users can take a break from their studying and work more on their physical abilities, such as the reaction time trainer to train their reaction time and the memory game to train their memory. This section works more like a “fun mini-games” section where users can relax and work on themselves at the same time.

#### **SQUARE 6:** Public Forums (UNDEVELOPED)

Currently undeveloped, but in the future, I am aiming for it to be a full social media-type feature where users could discuss appropriate topics. It will act similarly to Twitter or Instagram, but with of course a much less toxic community. This will be included since humans are social creatures who benefit from healthy conversation with other people, which will ultimately boost their confidence and social skills.

#### **SQUARE 7:** Resources

Barely developed, but currently it allows you to open text files, edit them, and save them. The original plan was to make a folder system where users could organize their resources by creating folders then add files into them so whenever they need to review a file, they can open the relevant folder, double click on the file, then be able to edit and save them. Currently the folder system had not been developed, so it ended up being a barely finished feature that currently does not serve any purpose. 

#### **SQUARE 8:** Mindfulness Portal

This is the (almost) perfect place for users to enhance mindfulness and mental health through wellbeing journalling, which is basically an exact copy-paste of the digital notebook, except that now, instead of a dropdown menu, it allows users to input weather, temperature, and emotions. Future enhancements will include mood boards and breathing exercises. This was included since well-being journaling has been proven to be an extremely useful tool for practising mindfulness. 

#### **SQUARE 9:** StudyBuddy (UNDEVELOPED)

An integrated Artificial Intelligence model that was never planned to be in the application. This idea came to me a few days before the deadline. For the submitted version of the program, this feature will be absent; I will work on it as a passion project in the future without the pressure of deadlines. This feature will be included since it makes StudyZone more versatile overall. 

#### **SQUARE 10:** Utilities

I dedicated this square to the miscellaneous but useful tools designed to enhance user efficiency. These tools don’t really belong in any of the squares above, but they are, at times, extremely useful, such as by assisting users in making decisions, like choosing whether or not to attend a late-night party and come back home at 4 am the next morning (flip a coin), or determining between multiple options. Many more features are to be added here in the future.

#### **OVAL 1:** User Dashboard

This was planned to be a user dashboard, but ended up being a simple menu with three buttons: back, log out, or delete account, since I had no time to create the progress system and animations as I had originally planned to. In the future, users can view their own custom profile on this page and also view their progress analytics.

#### **OVAL 2:** MUSIC SYSTEM

This is the menu where users can interact with music in the app. Here, they can adjust the volume, pause/restart songs, and view their playlist, where they have the option to add/remove songs from their own playlist. This was originally planned to be included in a separate square but was later redesigned as an oval. I included music in the app since music, especially calming music such as lo-fi, can help users focus more since it provides them a sense of relaxation, relieving stress and boosting mood.

#### **OVAL 3:** STREAK MENU

This tab allows users to view their current daily log-in streak. Automatically updated whenever the user logs into their account every day, and automatically breaks when users don’t log onto the app for over a day. This feature is included since streaks are able to provide motivation for users to continue their difficult journey. Take Duolingo for example. You don’t really want to spend time doing your Spanish lesson every day, but when you see that streak, you’ll realize that you’re pretty much forced to do them.

#### **Feedback & Support Section** (UNDEVELOPED)

Users will be able to send me a direct email for feedback on the app or to ask questions for help and support. Will be included in future updates.

## **⇒ 4.2.1 \- Back-End Engineering Contribution ⇐**

* Explain how back-end engineering contributed to the success and ease of use of the software, including  
  * Data processing  
  * Validation and logic  
  * Storage and retrieval  
  * Authentication (if applicable)

Backend engineering had contributed a lot to the program. The most essential backend functions were stored into a single file called ui\_helpers.py. This file was then imported to almost every single other file involved in the system, since it served crucial functions such as the exit button at the top left for every menu in the backend. ui\_helpers.py also contains the create\_small\_button function which laid the foundation for the button design style used in some features of the app such as the productivity trackers.

### **Data Processing**

The backend is also responsible for processing user input and converting it into structured data that the software can manage efficiently. Registration details are collected, processed and formatted before being stored. Notebook pages are converted into dictionaries containing the title, category, content, creation date and modification date. Task Tracker converts user input into task objects containing the task name, description, deadline, priority, and completion status. Login streaks are automatically calculated/updated by comparing the current date with the previous login date, and the skill trainer modules process statistics such as reaction time, accuracy and high scores before saving them to data.json.

### **Validation and Logic**

Another contribution of the backend is preventing invalid data from entering the system.  
Examples include the registration system which validates usernames format, username duplication, email format (using regex/regular expressions), password strength, and date of birth format. Similarly, the task tracker prevents users from creating invalid tasks by checking task name availability, duplicate tasks, as well as deadline formatting and plausibility. Notebook pages automatically record creation dates, update "Last Modified" whenever a page is edited, and prevent blank notes being saved thanks to backend engineering. In the login system, usernames are checked for case-sensitivity, and user-entered passwords are compared to their hashed versions using SHA-256. And finally, non-MP3 files are not allowed to be added into a user’s music playlist using in-built code restrictions.

### **Storage and Retrieval**

StudyZone uses JSON databases to permanently store user information. The software separates information into two databases. **Users.json** stores key account information, such as an account’s username, email, hashed password, last login date (required for the streak system), as well as their current and best login streaks. On the other hand, **data.json** stores content that is not related to a user’s account, but rather more related to their statistics and progress data they created within the main features of the app, such as their stored tasks, goals, habits, and notebook pages. The program retrieves data using dedicated functions within the data\_manager.py file which is the main handler for user data. These functions centralise all file access so that other parts of the program never need to manipulate JSON files directly. In external files that requires access to the database in order to function, data\_manager.py will be integrated into the external file so that the external file will be able to use the methods needed for data handling.

### **Authentication**

StudyZone includes a complete user authentication system. Security features include unique usernames for each new user, case-insensitive username lookup, password hashing using SHA-256 before storage, hashed password comparison during login, and separate account database from user content. Instead of storing passwords in plain text, passwords are converted into irreversible SHA-256 hashes. This improves security because even if the JSON database is viewed directly, the user's original password cannot be read. A final feature added for authentication is that users will not be able to tell which field contained the wrong credentials if they tried to log in with the wrong user credentials, since the error message does not inform them whether the user had entered the wrong username or the wrong password. This means that users will need to identify for themselves where went wrong, improving account security.

## **⇒ 4.3 \- Screenshots of Interface ⇐**

* Include annotated screenshots explaining how the user interacts with the system.

| First Menu: Allows users to register, log in or seek help![][image7] | Registration Page: Allows users to register for an account ![][image8] |
| :---- | :---- |
| **Login Page:** Allows users to log in to their accounts ![][image9] | **Main Menu:** Allows users to click on squares or ovals to use what they want ![][image10] |
| **Task Tracker:** Allows users to add, edit, remove, or mark tasks complete![][image11] | **Goal Planner:** Allows users to add, edit, remove, or mark goals complete![][image12] |
| **Habit Tracker:** Allows users to add or remove habits or mark them complete for today ![][image13] | **Digital Notebook (Main Entry Page):** Allows users to write notes and other things. ![][image14] |
| **Digital Notebook (Access Previous Pages):** Allows users to access previous notes ![][image15] | **Digital Notebook (Read Previous Pages):** Allows users to read/edit/delete previous notes ![][image16] |
| **Flashcards (Add Cards):** Allows users to add flashcards for memorisation and content review ![][image17] | **Flashcards (View Cards):** Allows users to view flashcards or shuffle flashcards ![][image18] |
| **Pomodoro Timer:** Allows users to set timers for periodic studying and break patterns![][image19] | **Calculator:** Allows users to perform basic arithmetics for mathematics ![][image20] |
| **Calendar View:** Allows users to view dates and go back and forward for each month/year ![][image21] | **Calendar (Add Events):** Allows users to add events for a specific day in the calendar ![][image22] |
| **Aim Trainer:** A minigame that allows users to practice their aim and hand-eye coordination ![][image23] | **Reaction Time Trainer:** A minigame that allows users to train their reaction time  ![][image24] |
| **Memory Trainer:** A minigame that allows users to train their memory skills ![][image25] | **File Reader / Editor:** Allows users to open files and edit them (.txt recommended) ![][image26] |
| **Wellbeing Journal Entry Page:** Allows users to write entries in their personal wellbeing journal![][image27] | **Wheel of Choices:** Allows users to enter a range of options, then spin a wheel for a decision ![][image28] |
| **Coin Flipper:** Allows users to flip a coin for decisions ![][image29] | **Streak Menu:** Allows users to view their daily log-in streak ![][image30] |
| **Music Menu:** Allows users to change their music volume, pause/restart music, or enter the playlist ![][image31] | **Music Playlist:** Allows users to add or remove songs from their playlist, with music-on-demand ![][image32] |
| **Account Settings:** Allows users to rename their account, log out, or delete their account. **![][image33]** | **Help Guide:** Allows users to seek help (not fully finished since I ran out of time but it’s alright) **![][image34]** |

# ──────────────  ⋆⋅☆⋅⋆ ───────────────

# **✤ Section 5 \- Testing and Evaluation**

## **⇒ 5.1 \- Testing Methods Used ⇐**

* Describe testing approaches, such as:  
  * Unit testing  
  * Integration testing  
  * User testing  
* Explain how testing results were used to improve performance, efficiency, or reliability.

The testing process was simple but tiring. Since the system required users to log in every time the app is opened (still trying to find a way to fix this issue), I have created a separate function that allows users to skip the registration/login requirement completely and experience the app in a special Guest Account. I used this function heavily when I was testing the program so that I could skip having to log in to the testing account every time I closed and reopened the app. In terms of testing methods, I utilised a mix of unit, integration and system testing to ensure the software operated correctly, remained reliable after updates, and provided a positive user experience. Since the application contains many interconnected modules, it was important to test both individual components and the complete integrated system.

Whenever unexpected behaviour occurred, debugging tools such as console output, traceback messages and manual inspection of JSON files were used to identify and resolve errors before further development continued. In extreme cases where I could not identify the solution to errors due to technical limitations, online websites and responses from Github Copilot were used in a purely instructional manner for debugging and resolution.

### **Unit Testing**

Unit testing was performed continuously during development to verify that individual functions behaved as expected before integrating them into the larger application. Each major function was tested independently using both valid and invalid inputs. 

The registration system underwent extensive testing to ensure that usernames, email addresses, passwords and dates of birth were validated correctly. Test cases included empty fields, usernames containing invalid characters, usernames that were too short or too long, duplicate usernames, invalid email formats, weak passwords and incorrectly formatted dates. Password hashing was also verified to ensure that passwords were never stored as plain text within the JSON database. The login system was tested by attempting successful logins, incorrect usernames, incorrect passwords and usernames entered with different capitalisation. Since the login system performs case-insensitive username matching, tests confirm that users must need to log in with the correct letter case.

The notebook module was tested by creating, editing, deleting and filtering notebook pages. Testing confirmed that pages were correctly saved into the database, modification dates updated after edits, and category filters displayed only the appropriate notebook entries. Additional tests ensured that blank notebook pages could not be saved unintentionally. The Task Tracker underwent detailed validation testing. Various combinations of task names, deadlines and priorities were entered to confirm that duplicate tasks were rejected, deadlines could not be set in the past, invalid date formats generated appropriate error messages, and users were required to select a valid priority before tasks could be added. Other individual modules were also tested individually to verify that each feature behaved correctly under normal operating conditions.

### **Integration Testing**

After individual modules had been tested independently, integration testing was performed to ensure that all parts of StudyZone communicated correctly with one another. Particular attention was given to the interaction between the GUI and the backend data management system. Every module that created, modified or deleted user information was tested to confirm that changes were immediately written to the JSON database and correctly reloaded when the application was reopened.

Navigation between menus was also tested extensively. Since StudyZone contains numerous nested menus and submenus, every navigation button and Escape key shortcut was checked to verify that users were always returned to the correct previous screen without creating duplicate windows or causing circular import errors. The account management system was integrated with all personalised features. After logging into different accounts, testing confirmed that each user viewed only their own notebook pages, flashcards, tasks, habits, goals, journal entries and statistics. This verified that user data remained isolated between accounts. Lastly, the music player was tested alongside other modules to ensure that background music continued playing while users navigated between different sections of the application.

One significant issue discovered during integration testing involved the Pomodoro timer. Initially, the timer reset whenever the user left the Pomodoro screen because the timer state existed only within the interface. This issue highlighted the importance of maintaining application state independently from individual pages. The timer was subsequently redesigned to store its state within the main application object (in main.py). Integration testing also identified issues involving circular imports between interface modules. These were resolved by moving import statements inside callback functions and by creating reusable helper functions within the ui\_helpers.py module.

### **User Testing**

User testing was performed throughout development by interacting with StudyZone as an end user would. This involved simulating realistic study sessions rather than simply verifying whether individual functions executed without errors. Registration and login were tested repeatedly using multiple accounts to verify account creation, authentication and persistent data storage. I then navigated through every major module, creating notebook pages, flashcards, calendar events, journal entries and productivity trackers before closing and reopening the application to ensure that all information remained saved.

The graphical interface was tested on displays with different screen resolutions. During testing, an issue was discovered where pages containing large text boxes extended beyond the bottom of smaller laptop screens. This reduced accessibility for users with lower-resolution displays. To resolve this problem, I created a reusable scrollable page system and added it to ui\_helpers.py so that it can be integrated into larger interfaces, allowing content to remain fully accessible regardless of screen size. User testing also identified inconsistencies between different interface components. For example, notebook category selection originally used different dropdown widgets across various screens, resulting in inconsistent visual appearance. These interfaces were later standardised using the same widget styling to improve consistency and usability.

Additional user testing focused on edge cases, including repeatedly creating and deleting tasks, rapidly switching between menus, entering extremely long text into notebook pages, cancelling operations midway through editing, attempting invalid logins and creating duplicate entries. These tests helped reveal validation issues and improved the overall stability of the software.

### **Reflection**

Testing played a significant role throughout the development process and directly influenced many design improvements. Validation testing strengthened input handling by preventing invalid or duplicate data from being stored. Integration testing identified communication issues between modules, leading to improvements in navigation and state management. User testing highlighted interface consistency issues and screen scaling problems, resulting in the implementation of reusable scrollable layouts and standardised interface components. Debugging sessions also revealed several unexpected behaviours, including incorrect registration validation, JSON database corruption, dropdown selection errors and timer state management issues. Resolving these problems significantly improved the reliability, usability and maintainability of StudyZone.

Overall, the combination of unit testing, integration testing and user testing ensured that StudyZone became progressively more stable throughout development. Regular testing allowed defects to be identified early, reduced the likelihood of data corruption, improved the user experience and increased confidence that each feature would continue functioning correctly as additional modules were added.

## **⇒ 5.2 \- Test Cases and Results ⇐**

| TEST ID | Description | Expected Result | Actual Result | Pass/Fail |
| :---- | :---- | :---- | :---- | :---- |
| 0001 | Testing invalid username, DoB and email formats during registration | Error message appears, registration button becomes inactive | Error message appears, registration button becomes inactive | Pass |
| 0002 | Testing if successful user registration saves new user data to database | User data appears in database | User data appears in database | Pass |
| 0003 | Testing user password strength requirements | Display “weak password” error message for weak passwords | Error message was displayed for weak passwords | Pass |
| 0004 | Testing if user password is properly hashed on registration | Hashed password in database | Password is hashed and appears in database | Pass |
| 0005 | Testing duplicate usernames | Error message appears, registration button becomes inactive | Error message appears, registration button becomes inactive | Pass |
| 0006 | Testing invalid login credentials | Error message appears, log in button becomes inactive | Error message appears, log in button becomes inactive | Pass |
| 0007 | Testing valid login credentials for an existing account | Login succeeds, redirected to main menu | Login succeeds, redirected to main menu | Pass |
| 0008 | Testing invalid task details for task tracker | Error messages appear, “add task” button becomes unusable | Error messages appear, “add task” button becomes unusable | Pass |
| 0009 | Testing valid task details for task tracker | No error messages will appear and “add task” button becomes available | No error messages appears and “add task” button becomes available | Pass |
| 0010 | Mark task complete | The cross next to the task becomes a tick and task status is updated to completed | The cross next to the task becomes a tick and task status is updated to completed | Pass |
| 0011 | Remove task from list box | The task disappears from list box and fully erased from data.json | The task disappears from list box and fully erased from data.json | Pass |
| 0012 | Testing duplicate task creation | Add task button greys out and error message is displayed | Add task button greys out and error message is displayed | Pass |
| 0012 | Testing login streak updates after consecutive daily login | Current streak increments by one | Current streak increments by one | Pass |
| 0013 | Testing best streak display after breaking consecutive logins | Current streak resets to 0 and best streak is displayed | Current streak resets to 0 and best streak is displayed | Pass |
| 0014 | Testing notebook note creation | Note saved successfully | Note saved successfully | Pass |
| 0015 | Testing notebook note editing | Changes saved successfully | Changes saved successfully | Pass |
| 0016 | Testing notebook note deletion | Note removed from database | Note removed from database | Pass |
| 0017 | Testing flashcard creation | Flashcard appears in list | Flashcard appears in list | Pass |
| 0018 | Testing flashcard editing | Changes saved correctly to flashcards | Changes saved correctly to flashcards | Pass |
| 0019 | Testing flashcard deletion | Flashcard removed successfully | Changes reflected correctly | Pass |
| 0020 | Testing Review Flashcards when no flashcards exist | Buttons disabled so you can’t press the button to enter | Buttons disabled so you can’t press the button to enter | Pass |
| 0021 | Testing Review Flashcards button after adding flashcard | Button becomes enabled | Button becomes enabled | Pass |
| 0022 | Testing journal entry creation | Entry saved successfully | Entry saved successfully | Pass |
| 0023 | Testing journal entry editing | Changes saved correctly | Changes saved correctly | Pass |
| 0024 | Testing journal entry deletion | Entry removed successfully | Entry removed successfully | Pass |
| 0025 | Testing calendar event creation | Event appears on calendar | Event appears on calendar | Pass |
| 0026 | Testing calendar event deletion | Event removed successfully | Event removed successfully | Pass |
| 0027 | Testing aim trainer statistics update after game | Statistics increase appropriately and results displayed accurately at the end | Statistics increase appropriately and results displayed accurately at the end | Pass |
| 0028 | Testing reaction trainer best time update | Best time updates when improved | Best time updates when improved | Pass |
| 0029 | Testing logout and re-login persistence | All user data remains intact | All user data remains intact | Pass |
| 0030 | Testing loading existing account data | Previously saved information loads correctly | Previously saved information loads correctly | Pass |
| 0031 | Testing exit navigation using Escape key | Returns to previous menu without errors | Returns to previous menu without errors | Pass |
| 0032 | Testing oval buttons if they respond to clicks | Correct menu opens | Correct menu opens | Pass |
| 0033 | Testing repeated rapid button presses | Application remains responsive without crashing | Application remains responsive without crashing | Pass |
| 0035 | Testing app consistency after closing and reopening StudyZone | All saved user information remains available | All saved user information remains available | Pass |

## **⇒ 5.3 \- Evaluation Against Requirements ⇐**

* Evaluate how effectively the solution meets the identified functional and non-functional requirements. Consider your ongoing quality assurance processes.  
* Evaluate your project in terms of how effectively you addressed compliance and legislative requirements (consider privacy, use of data, etc).

### **Evaluation Against Functional Requirements**

**REQUIREMENT 1:** This requirement has been successfully achieved. The system allows users to freely create, view, edit and delete tasks, goals, notebook pages, habits and events. The “mark complete” button allows users to select the tasks they have completed. Users are able to organise their notebook pages via categorisation, although I admit that more work could have been done on this part. One thing that had been a failure was the implementation of completion tracking mechanics. They were not implemented in the final version due to time restraints and technical limitations.

**REQUIREMENT 2:** This requirement has not been successfully achieved to the best of its ability. This was due to me changing the core functionality of the program as I progressed through the development of the app. Another contributing factor to the failure of this requirement was me overlooking the difficulty of implementing visual progress within a Tkinter application, since I had planned to introduce smooth, flow-style visual animations to represent user progress, which was extremely difficult to implement. A final factor was poor time management. I had spent too much time developing crucial functions within the app instead of working on progress tracking. Had the deadline been increased or my technical ability improved, this requirement would’ve been done.

**REQUIREMENT 3:** This requirement has been successfully achieved. I have built a system where users are allowed to freely interact with the user interface, including free and flawless interactions with buttons, entry fields, list boxes, skill training games, and the art pad feature. These widgets have been integrated smoothly into the system and, after extensive testing, have been proven to work seamlessly.

**REQUIREMENT 4:** This requirement has been successfully achieved. Where possible, the program warns users of invalid input with helpful error messages, while also preventing users from being able to submit data with invalid inputs. This is a crucial step to ensure that the system remains completely functional and unaffected by errors related to user queries.

**REQUIREMENT 5:** This requirement has been successfully achieved. Many support tools and features have been added to the system, such as task trackers, goal planners, studying tools, and miscellaneous utilities. Helpful messages have also been embedded into the main menu panel, guaranteed to boost user mood and confidence, which ultimately improves the user experience.

### **Evaluation Against Non-Functional Requirements**

**Performance:** This requirement has been successfully achieved. The program does not have any significant delays and does not freeze or crash when errors occur. The system also responds extremely quickly to user demands. The system also operates at a consistent refresh rate and is usable across a range of different computers, as shown by peer testing.

**Security:** This requirement has theoretically been achieved, although not to the best of its ability. User data was stored simply in publicly accessible JSON files. However, user passwords are securely hashed and encoded in a way that it becomes unreadable, and the hashing process remains irreversible. Several factors contributed to the semi-failure of this non-functional requirement, such as storing data being extremely difficult if not using JSON. I’ve tried experimenting with other secure data methods, such as encrypting the JSON file, switching to cloud storage (Firebase), or data storage through SQL. However, all these methods ended up failing since they caused damage to the application.

**Reliability:** This requirement has been successfully achieved. User data is stored safely in JSON files and experiences no changes to them at any given time unless the user chooses to edit their data or mark them complete. User data will be saved and available even when users log out of their account or close their application window, since every time data is needed, JSON files are summoned, and data will be accessed from there.

**Usability:** This requirement has been successfully achieved. The user interface is extremely intuitive, neat, and simple to use. All features are properly labelled with a title, and their corresponding squares or ovals are properly labelled with text or an emoji depicting what it does. All buttons are organised, and entry fields for features are clear and flawless to ensure data integrity and a positive user experience.

**Accessibility:** This requirement has been achieved to some extent. The final version of the app offers readable font sizes, clear contrast in colour between font colour and background, and logical program structure. However, due to time constraints, there were no opportunities for me to add tools that can adjust and customise these settings, such as font sizes, in order to align with the needs of some users. In the future, these adjustment tools will definitely be added.

**Maintainability:** This requirement has been achieved to the absolute peak of its ability. For a simple project like this, I have organised the code into 40 distinct and much smaller yet interconnected Python files. All these Python files are connected with each other through special bonds and integration. For example, the ui\_helpers.py file is integrated into almost every single other Python file since the exit menu binding functions are essential for every single feature in the application. This shows that the difference between the backend code and the frontend code has been distinctly separated, making it easier for me to maintain and update code since I would have an excellent knowledge about each section of the application, because they would have their own individual files.

## **⇒ 5.4 \- Improvements and Future Development ⇐**

* Outline your project’s limitations.  
* Explain realistic future enhancements.

### **Limitations**

Due to the extremely narrow amount of time restricted for development, there were many planned features that were left undeveloped and eventually left behind for this task. Features such as public blogs (later renamed to StudyZone Forums), where users could freely chat to one another and post about their thoughts, feelings and daily life, were initially planned to be developed within the time frame, but due to their extreme complexity, I simply did not have the skill level to create this feature, as it required lots of time investment and also required reworks to many currently existing features. As a result, I eventually left this out of the program and only included the square for it in the main menu. Similarly, user progress reports and analytics data were also left out due to poor time management and the difficulty of implementation. Aside from those, many other features, such as the fitness tracker and support ticket tool, were also left behind. The File Storage tool and the typing test tool in the Skill Trainers menu had also ended up being very poorly made, since the File Storage currently only opens files and cannot store files, and the typing test tool just looks extremely ugly, highlighting the need for a visual rework.

### **Possible Future Enhancements**

In future updates, without the threat of extremely tight time limits, I would definitely spend more time doing research and working on this project. I would definitely first of all start creating user progress analytics, generate flow-style animations, add user progress analytics, and many other features. The File Storage and typing test will also be reworked extensively. More tools will be added to the Creativity and Mindfulness menus, such as mood boards, mind map creators, prompt generators, and many more. In upcoming updates, users will also be able to search for accounts and message each other. The main user interface might also receive a visual rework through methods such as expanding the colour palette and adopting different fonts and styles for different functions. A mailbox feature and private messaging functionality will also be added so that users can communicate with each other. However, this feature will be defined by user privacy settings, which will be added in the account settings in the future. The system can also notify users about critical information, such as overdue tasks or failed goals.

Although it was never part of my plan in the first place, StudyBuddy is a hypothesised, highly theoretical yet achievable feature that could be implemented into the system with a long period of hard work. StudyBuddy is an AI tool that will respond to user queries in a friendly manner and provide mental or emotional support whenever needed, acting like “your digital best friend”. This remains only a concept, but it is very tempting for me to give it a crack and try to develop it in the future.

## **⇒ 5.5 \- Evaluation of Social, Ethical and Legal Issues ⇐**

* Evaluate your project in terms of social, ethical and legal issues.

### **Social Issues**

StudyZone is able to help students organise their learning by combining multiple study tools into one application. Features such as the task tracker, digital notebook, Pomodoro timer and calendar will encourage better time management, organisation, and study habits. This can reduce stress during assessment periods and improve academic performance. Furthermore, the wellbeing journal and mindfulness tools (to be added in the future) encourage users to reflect on their emotions and develop healthy study routines. These features may help reduce academic stress and promote positive wellbeing. Lastly, communication tools (to be added in the future) such as StudyZone Forums and StudyBuddy allows lonely, depressed or mentally ill users to communicate with others, potentially boosting their mood and confidence in themselves.

Negative social issues also exist. Students may become overly reliant on digital tools to organise their lives instead of developing independent organisational skills, resulting in reduced self-management without technology and overdependence on software availability. Additionally, if the future StudyZone Forums become available, users may post inappropriate, offensive, misleading, or harmful content, emphasizing the need for strict filters, censorship tools and moderation technologies. Finally, not every student owns a powerful computer or has reliable internet access, therefore they may potentially be excluded from receiving opportunities to use StudyZone.

### **Ethical Issues**

Lots of ethical issues are involved with StudyZone. Since StudyZone stores extremely sensitive information such as usernames, passwords and user account data such as their notebook pages or goals, users have a fundamental right of being able to trust the software to keep this information private, meaning that the developer has an ethical responsibility to never share user information. Therefore the developer must prioritize the secure storage of data and ensure unauthorized access could never occur.

Additionally, sensitive information should be protected against theft or modification. The current JSON storage is only used since the current version of StudyZone is mainly created for a school project. JSON is not secure for commercial software. It is essential for the developer to consider adding encrypted databases using cloud storage, secure authentication and automatic backups to the cloud.

For future updates, if an AI assistant is added, then it must clearly indicate when information may be inaccurate. It must also avoid encouraging cheating and provide educational support rather than completing students’ homework tasks and assessments dishonestly. Furthermore, progress statistics should accurately represent the user's activity. StudyZone should never manipulate statistics or exaggerate productivity just to simply make users feel better for themselves.

### **Legal Issues**

StudyZone collects personal information. If the app is to be publicly released in Australia, it would need to comply with the Privacy Act 1988 and the Australian Privacy Principles. This means that StudyZone must only collect only necessary information, protect stored information, inform users how their data is used at all times, and give users the freedom to access or delete their data anytime, anywhere.

StudyZone uses many assets such as icons, images, music, fonts and code exemplars. Some of these assets are found on the internet. Therefore, the developer must ensure these assets are original, licensed for use, and fully open-source. The developer must also have permission from the original creator in order to use assets found on the internet such as background music, otherwise the developer must choose to use royalty-free music. Similarly, the StudyZone source code is the developer's intellectual property. If published online such as to Github, then an appropriate licence should specify how others may use or modify the software.

Lastly, if the support system emails feedback to the developer, then users must be able to know that their messages are being sent externally. Email addresses should not be shared with unknown third parties, and messages should be handled confidentially. Under no circumstances should messages ever be used in a malicious or exploitative manner that violates Australian law.

# ──────────────  ⋆⋅☆⋅⋆ ───────────────

# **✤ Section 6 \- Feedback, Security & Reflection**

## **⇒ 6.1 \- Summary of Client or Peer Feedback ⇐**

* Summarise feedback received and explain how it influenced development.  
* You could collect a ‘PMI’ (Plus, Minus, Implication) table from at least three different people after testing, or record and summarise an interview with at least three three people who test the software.  
* Evaluate your use of feedback to improve your project:  
  * Consider your individual workflow and how well you responded to peer / stakeholder feedback.  
  * Consider how well you involved, empowered or negotiated with a peer/client throughout the process.

### **Peer Feedback PMI Table**

| Users | Plus | Minus | Implications |
| :---- | :---- | :---- | :---- |
| @RayBirbz | Extremely satisfying to use Friendly user interface Almost zero lag and most errors are handled well Extremely useful tools Data is stored even if you exit app | Some features are left undeveloped which is kind of sad, it would be better if more features could be developed, for example the creativity tab currently only has one feature Colour scheme is kinda repetitive, would recommend expanding colour palette | TechLemon99 has developed a very good app that for sure has the potential to make millions of people achieve better lives. It is an excellent app dedicated to self-improvement and studying, with plenty of decent tools. However the app could be better if more unique features are developed. Overall it’s an excellent app I would definitely consider using if it formally releases. |
| @RonenGupta | Easy to use Very use friendly Developed features work perfectly good features (timer, flashcards) for a study app, would consider using. | Some features are repetitive some are kind of unrelated to a study app. | Easy to use Plethora of features, however would benefit from those which are related |
| @CursedToxic | friendly interface detailed functions performance is optimized well | some features are redundant such as the goal planner too many features, strays off the main goal of study app | overall quite easy to use, however some features could be removed for a more minimalistic interface |

### **Response to Peer Feedback**

Peer Feedback had been a key driver for decision-making during development. My plans were heavily influenced by what the users (in this case being my peers) actually wanted. In this case, peers were satisfied that their wants and needs were able to make it into the program. However, they are somewhat dissatisfied at the fact that the program contains too many features deemed “unnecessary” or “irrelevant”, which is caused by the name of the application “StudyZone” making them believe that this is an app used only for studying purposes. What I failed to highlight is the fact that the app is also multi-functional, meaning that there will be many more components to the app than only studying tools. For example, the reaction time trainer and memory trainer are built for self-improvement purposes rather than studying. 

Feedback also shows that users are slightly displeased with the repetitiveness in some aspects of the app, such as the uncanny similarity between the digital notebook and the wellbeing journal. These two features, although may look like they’d overlap, actually serve fundamentally different features and purposes, one being used for note-taking (studying) and the other being used for mindfulness (mental health). Tester @RayBirbz has also pointed out the repetitiveness in the colour scheme of the app, which I do agree with. In the future, the colour palette used for designing the app will be expanded and some parts of the app may be redesigned with different colours. This highlights the key fact that feedback is extremely important for software applications since they reveal the wants and needs of the users, and software is solely developed for the users to enjoy, meaning that their opinions matter significantly.

## **⇒ 6.2 \- Secure Software Design and Data Handling ⇐**

* Evaluate the approach undertaken to safely and securely collect, use, and store data.  
* Your evaluation should address:  
  * Secure coding practices applied during development  
  * Input validation and error handling  
  * Data storage and protection methods  
  * The impact of secure software design on user trust, data integrity, and system reliability

StudyZone was developed using several secure coding practices to protect user information while maintaining the reliability and usability of the software. With the security-by-design principle in mind throughout the entire development process, security had been a key aspect of the app in which I had heavily focused on during development. Security was heavily considered during the implementation of the registration system, authentication process, data validation, and storage mechanisms. These features work together to reduce the likelihood of data corruption, unauthorised access, and invalid user input.

### **Input Validation and Error Handling**

StudyZone performs extensive user input validation to ensure that only valid data is processed and stored. The program first validates all user input before it is accepted into the system. During account registration, usernames are checked to ensure they contain only permitted characters, meet minimum and maximum length requirements, and are unique regardless of letter case. Email addresses are validated using regular expressions to ensure they follow a valid email format, while dates of birth are checked to ensure they are valid dates that do not occur in the future. Passwords must satisfy minimum complexity requirements by containing at least eight characters with both letters and numbers. Registration fields provide immediate feedback whenever invalid information is entered, preventing malformed data from entering the system. Similar validation is used throughout other modules, such as in productivity trackers and calendar reminders. 

StudyZone also includes error handling measures when reading JSON data files, meaning that if a data file becomes corrupted or contains invalid syntax, then the software safely catches the error and attempts to recover from a backup copy located in a backup folder instead of crashing the app. This improves the robustness of the application and helps prevent data loss caused by accidental corruption or unexpected interruptions such as a user’s laptop suddenly dying in the middle of data being saved.

### **Data Storage and Protection Methods**

Passwords are never stored as plain text. Instead, they are converted into SHA-256 cryptographic hashes before being saved to the user database. This means that even if the user database were accessed by an unauthorized individual, the original passwords cannot be directly viewed, and neither can the hashed passwords be decrypted. When the user logs out then tries to log back in, the password entered by the user is hashed again and compared against the stored hash, ensuring the original password is never exposed during authentication.

Furthermore, StudyZone stores user account information separately from productivity data using two independent JSON databases. The first database, users.json, contains account information such as usernames, hashed passwords, login streaks, email addresses and dates of birth, while the second, data.json, stores user data generated within the main app, including their created tasks, flashcards, goals, and habits. Separating authentication data from application data improves organisation, makes the backend workspace look neater than it actually is, and reduces the impact of corruption to a singular JSON file. If one data file experiences an issue, the other can remain fully functional.

To address this issue even further, I created the backup files so that backup copies of both JSON databases can be automatically maintained. Before new data is written, the current version of the database is copied into a backup directory. If the primary file later becomes corrupted or unreadable, the application can automatically restore the previous backup instead of losing all stored information. This increases system reliability and provides protection against file corruption, incomplete writes or unexpected application failures. I also built helper functions such as safe\_load\_json() in the backend so that it can handle everything related to JSON file loading and validation, making sure that every module reads data consistently.

Lastly, additional protection has been implemented through login rate limiting. If a user repeatedly enters incorrect login credentials, the account is temporarily locked for a specified period (1 min) before another few attempts can be made. This can heavily reduce the effectiveness of brute force attacks, where an attacker repeatedly guesses passwords until the correct one is found.

### **Impact on User Trust, Data Integrity and System Reliability**

The implemented security measures contribute to positive user trust by demonstrating that personal information is handled responsibly and reliably within the system. Password hashing ensures sensitive credentials are never stored in plain text; validation prevents the risk of invalid or highly malicious input data from compromising existing storage data; automatic backups and corruption resistant functions makes it unlikely for user information to be permanently lost, even if a data file becomes damaged; login rate limiting reassures users that their accounts are protected against repeated unauthorised login attempts, highlighting safety as a primary concern. These design decisions improve data integrity by ensuring that only valid information enters the system and that stored data remains consistent across all application sessions. They also improve software reliability by reducing crashes caused by malicious or inappropriate data and providing automatic recovery mechanisms when unexpected errors such as file corruption occurs.

### **Future Security Enhancements**

* Passwords to be secured using modern password hashing algorithms such as bcrypt or Argon2 instead of SHA-256, since these algorithms include automatic salting and are specifically designed to resist password cracking attacks.  
* Sensitive information such as email addresses and dates of birth to be encrypted before being stored on disk, preventing unauthorized users from reading personal information directly from the JSON database.  
* Additional security measures such as multi-factor authentication, reset password functionality, and audit logs recording important account actions.  
* When StudyZone becomes an online application, the JSON storage system will be replaced with a secure cloud database management system supporting encrypted network communication, role-based access control, secure authentication protocols, and server-side validation.

## **⇒ 6.3 \- Personal Reflection ⇐**

* Reflect on what you learned during the project, including  
  * Software engineering skills developed  
  * Challenges encountered and how they were overcome

Developing StudyZone had been the most technically challenging yet also rewarding project I had ever undertaken in my entire software engineering career. At the beginning, I only had decent but limited understanding in Python and Tkinter, as well as some key concepts such as separating, integrating and combining modules. Throughout the development process, I gradually learned how to build and structure a large software project. By integrating modules into main and creating many different functions, I am able to develop each feature independently while still integrating into one complete application. I also further deepened my understanding about Python variables, backend engineering, Tkinter widget styling, as well as Python’s math module. The overall experience significantly improved my confidence in software engineering and also showed me the importance of extensive planning and documentation, modular design, and iterative development using WAgile.

One of the most valuable skills which I was able to enhance was developing maintainable code. When the project slowly expanded itself beyond over 1000 lines of code, placing everything into a few crowded files became difficult to manage. Therefore, using the fundamental skill of module integration, I was able to separate the core functionality into multiple Python modules, such as registration systems, data management, productivity tools, study tools and user interface helpers. Creating reusable helper functions such as functions for custom button design and reusable exit buttons greatly reduced duplicate code and made future development considerably easier. I also gained a stronger understanding of classes. Using a central class for the main StudyZone app allowed multiple components of the program to share information such as the application colour palette, music settings and UI functions. Instead of having to repeatedly pass large amounts of data between files, I learnt how to simplify communication between independent modules.

Working with data storages taught me how software manages user information safely and securely. Before developing the project I only understood basic JSON functionalities like reading and writing, but throughout development I constantly researched and eventually learnt how to safely load data, create missing user profiles, update existing records and recover from corrupted files. Implementing separate databases for the two types of data improved the overall cleanliness of the software and even made future expansion easier.

The Pomodoro timer was one of the most difficult and absolutely undoubtedly the worst feature I had ever needed to write and debug. Although the timer functioned correctly while the page remained open, maintaining accurate timing while navigating between different menus was significantly more complex than I had expected because Tkinter's event scheduling depends on active widgets. This challenge made me realize that software development often involves understanding the limitations of existing frameworks rather than simply writing code. This traumatizing experience taught me the importance of researching framework behaviour before designing complex features. 

Overall, this project significantly improved my programming ability and confidence in tackling complex problems. I developed practical skills in modular programming, user interface development, debugging and software testing, and many things else. More importantly, I learned that successful software engineering requires careful planning, patience and continuous refinement. This had been a memorable journey full of ups and downs, filled with happiness and traumatization. The task may be over, but the app definitely isn’t. I will definitely continue working on this project in my own time in the future. 

# ──────────────  ⋆⋅☆⋅⋆ ───────────────

# **✤ Section 7 \- Appendices**

## **FULLY FINISHED GANTT CHART WITH MILESTONES**

![](/Documentation/img_doc/Gantt%20Charts/GanttChart2.png)

## **CODE SNIPPETS**

| ![](/Documentation/img_doc/Code%20Snippets/Snippet1.png) | ![](/Documentation/img_doc/Code%20Snippets/Snippet2.png) |
| :---- | :---- |
| ![](/Documentation/img_doc/Code%20Snippets/Snippet3.png) | ![](/Documentation/img_doc/Code%20Snippets/Snippet4.png) |
| ![](/Documentation/img_doc/Code%20Snippets/Snippet5.png) | ![](/Documentation/img_doc/Code%20Snippets/Snippet6.png) |