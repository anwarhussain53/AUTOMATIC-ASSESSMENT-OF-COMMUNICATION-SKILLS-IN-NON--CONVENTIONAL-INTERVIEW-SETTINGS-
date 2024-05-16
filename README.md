Project Report On 
AUTOMATIC ASSESSMENT OF 
COMMUNICATION SKILLS IN NON- 
CONVENTIONAL INTERVIEW SETTINGS 
Submitted to CMREC, HYDERABAD 
In Partial Fulfillment of the requirements for the Award of Degree of 
BACHELOR OF TECHNOLOGY 
IN 
COMPUTER SCIENCE AND ENGINEERING 
 
Submitted 
By  
Anwar Hussain 	(208R1A0535)	 

CMR ENGINEERING COLLEGE 

INTRODUCTION :     

Communication is the aptitude to proficiently and expediently transmit information to others. Proficiency in communication skills can have a positive impact on various domains of life, encompassing both professional environments and social contexts, among others. Proficiency in several forms of communication is an essential prerequisite for any employment position held by a knowledge worker. There exist various forms of communication, including spoken, written, and non-verbal. Communication skills encompass more than just face-to-face interactions and verbal communication. The proficiency in producing coherent and impactful written communication is equally essential. The automation of the recruiting process has been made possible by the recent emergence of machine learning in the sector, sometimes referred to as recruitment analytics or hiring analytics. The utilization of social recruitment, virtual evaluations, and video interviews is regarded as the prospective direction for the hiring procedure. Several automated talent assessment platforms, such as Teleview, Hirevue, and Sonru, are currently receiving significant attention. These platforms provide widespread access to interviews and screening processes. However, there are limited number of urgent inquiries that require attention. How do candidates fare in automated environments? What are the observed variations in the behavior and characteristics of the applicants across different settings? The present study examines responses to the a fore mentioned inquiries. In order to accomplish this objective, we have gathered interviews from individuals in three distinct contexts: video interviews, written interviews, and short essays conducted through a specially designed online interface. Subsequently, a range of analyses are conducted on the data, followed by the development of a predictive model aimed at automating the evaluation of participants communication abilities. 
 


 

 
The proposed automated system addresses the limitations of traditional system by leveraging technology and machine learning algorithms to provide fair, efficient, and insightful evaluations of candidate’s communication abilities in non-conventional interview settings. 
Overview 
 
The proposed system enables the automatic assessment of communication skills in non-conventional interview settings, allowing users to receive feedback on their visual expressions, spoken content, and written communication skills. The project integrates computer vision, audio processing, and natural language processing techniques to perform these assessments and provide valuable insights to the users. 
 
 
 
 
 
Proposed system architecture. 
1.	User Interface: 
 
o	The project starts with a graphical user interface (GUI) created using the Tkinter library in Python. 
o	The interface provides options for the user to perform different types of assessments: visual, spoken, and essay assessments. 
 
2.	Loading Assessment Models: 
 
o	When the user clicks the "Generate & Load Assessment Model" button, the system loads pre- trained machine learning models necessary for assessments. 
o	These models include a facial expression recognition model, a speech emotion classifier, and an XGBoost classifier for text data. 
 
3.	Visual Assessment: 
 
✓ If the user chooses the "Visual Interview Assessment" option: 
o	The system activates the computer's camera to capture video frames. 
o	It uses a pre-trained facial expression recognition model to detect facial expressions in the video frames. o The system calculates the confidence and confusion percentages based on the detected expressions. 
o	The results are displayed back to the user, indicating their confidence and confusion- levels during the visual assessment. 
 
4.	Spoken Assessment: 
 
✓ If the user selects the "Spoken Interview Assessment" option: 
o	The user is prompted to select an audio file containing spoken content. 
o	The system extracts relevant features from the audio file. 
o	It utilizes a pre-trained speech emotion classifier to predict the spoken emotion, categorizing it as confident or confused.  o The system informs the user about the prediction result, indicating whether the spoken content sounds confident or confused. 
 
 
                          
 
5.	Essay Assessment: 
 
✓ If the user opts for the "Written & Short Essay Assessment": 
o	The user enters written content in the provided text box. 
o	The system processes the text, cleaning it by removing punctuation, stop words, and stemming/lemmatizing words. 
o	The cleaned text is vectorized using a TF-IDF vectorizer. 
o	The pre-trained XGBoost classifier predicts the communication skill level based on the processed essay content. 
o	The system displays the prediction score to the user. 
 
6.	Displaying Results: 
 
o	The assessment results, including confidence and confusion percentages from the visual assessment, spoken assessment prediction, and essay assessment prediction score, are displayed in the GUI. 
o	For visual assessment, the system displays the count of confident and confused facial expressions. o For spoken assessment, the system informs the user whether their speech sounded confident or confused. o For essay assessment, the system shows the predicted communication skill level based on the written content. 
 
7.	Data Flow and Processing: 
 
o	The project utilizes machine learning models and techniques to process different types of data: 
o	Visual assessment involves processing video frames using a facial expression recognition model. 
o	Spoken assessment extracts features from audio files and uses a speech emotion classifier. o Essay assessment processes text data, cleaning and vectorizing it before prediction. 
 
 
 
Installation & Acceptance Test: 
 
During the installation and acceptance stage, the software artifacts, online help, and initial production data are loaded on to the production server. At this point, all test cases are run to verify the correctness and completeness of the software. Successful execution of the test suite is a prerequisite to acceptance of the software by the customer. After customer personnel have verified that the initial production data load is correct and the test suite has been executed with satisfactory results, the customer formally accepts the delivery of the software. 
 
Installation and Acceptance test 
The primary outputs of the installation and acceptance stage include a production application, a completed acceptance test suite, and a memorandum of customer acceptance of the software. Finally, the PDR enters the last of the actual labor data into the project schedule and locks the project as a permanent project record. At this point the PDR "locks" the project by archiving all software items, the implementation map, the source code, and the documentation for future reference.  
Maintenance: 
 
Outer rectangle presents maintenance of a project, Maintenance team will start with requirement study, understanding of documentation later employees will be assigned work and will undergo training on that particular assigned category. For this life cycle there is no end, it will be continued so on like an umbrella (no ending point to umbrella sticks). 
3.2 Functional Requirements 
 
Output Design 
 
Outputs from computer systems are required primarily to communicate the results of processing to users. They are also used to provides a permanent copy of the results for later consultation. The various types of outputs in general are: 
•	External Outputs, whose destination is outside the organization 
•	Internal Outputs whose destination is within the organization. 
•	Operational outputs whose use is purely within the computer department. 
•	Interface outputs, which involve the user in communicating directly. 
 
Output Definition 
 
The outputs should be defined in terms of the following points: 
 
•	Type of the output 
•	Content of the output 
•	Format of the output 
•	Location of the output 
•	Frequency of the output 
•	Volume of the output 
•	Sequence of the output 
It is not always desirable to print or display data as it is held on a computer. It should be decided as which form of the output is the most suitable. 
Input Design 
 
Input design is a part of overall system design. The main objective during the input design is: 
•	To produce a cost-effective method of input. 
•	To achieve the highest possible level of accuracy. 
•	To ensure that the input is acceptable and understood by the user 
 
Input Stages 
 
The main input stages can be listed as below: 
 
•	Datarecording 
•	Data transcription 
•	Data conversion 
•	Data verification 
•	Data control 
•	Data transmission 
•	Data validation 
•	Data correction 
 
Input Types 
 
Itis necessary to determine the various types of inputs. Inputs can be categorized as follows: 
 
•	External inputs, which are prime inputs for the system. 
•	Internal inputs, which are user communications with the system. 
•	Operational, which are computer department’s communications to the system? 
•	Interactive, which are inputs entered during a dialogue. 
Input Media 
 
At this stage choice has to be made about the input media.  
To conclude about the input media consideration has to begiven to 
•	Type of input 
•	Flexibility of format 
•	Speed 
•	Accuracy 
•	Verification methods 
•	Rejection rates 
•	Ease of correction 
•	Storage and handling requirements 
•	Security 
•	Easy to use 
•	Portability 
Keeping in view the above description of the input types and input media, it can be said that most of the inputs are of the form of internal and interactive. As Input data is to be the directly keyed in by the user, the keyboard can be considered to be the most suitable input device. 
Error Avoidance 
 
At this stage care is to be taken to ensure that input data remains accurate form the stage at which it is recorded up to the stage in which the data is accepted by the system. This can be achieved only by means of careful control each time the data is handled. 
Error Detection 
 
Even though every effort is made to avoid the occurrence of errors, still a small proportion of errors is always likely to occur, these types of errors can be discovered by using validations to check the input data. 
Data Validation 
 
Procedures are designed to detect errors in data at a lower level of detail. Data validations have been included in the system in almost every area where there is a possibility for the user to commit errors. The system will not accept invalid  data. Whenever an invalid  data is keyed in,  the system immediately prompts the user and the user has to again key in the data and the system will accept the data only if the data is correct. Validations have been included where necessary. 
The system is designed to be a user friendly one. In other words the system has been designed to communicate effectively with the user. The system has been designed with popup menus. 
User Interface Design 
 It is essential to consult the system users and discuss the needs while designing the user interface: 
 
User Interface Systems Can Be Broadly Classified As: 
 
•	User initiated interface the user is in charge, controlling the progress of the user/computer dialogue. In the computer-initiated interface, the computer selects the next stage in the interaction. 
•	Computer initiated interfaces in the computer-initiated interfaces the computer guides the progress of the user/computer dialogue.  
•	Information is displayed and the user response of the computer takes action or displays further information. 
User Initiated Interfaces 
 User initiated interfaces all into two approximate classes: 
 
•	Command driven interfaces: In this type of interface, the user inputs commands or queries which are interpreted by the computer. 
•	Forms oriented interface : It is chosen because it is best choice. 
 
Computer-Initiated Interfaces 
 
The following computer –initiated interfaces were used: 
•	The menu system for the user is presented with a list of alternatives. 
•	The user chooses  one of the alternatives. 
•	Questions–answer type dialog system where the computer asks question and takes action. 
 
Right from the start the system is going to be menu driven, the opening menu displays the available options. Choosing one option gives another popup menu with more options. In this way every option leads the users to data entry form where the user can key in the data. 
Error Message Design 
 
The design of error messages is an important part of the user interface design. As user is bound to commit some errors or other while designing a system the system should be designed to be helpful by providing the user with information regarding the error he/she has committed. This application must be able to produce output at different modules for different inputs. 
 
Performance Requirements 
 
Performance is measured in terms of the output provided by the application. Requirement specification plays an important part in the analysis of a system. Only when the requirement specifications are properly given, it is possible to design a system, which will fit into required environment. It rests largely in the part of the users of the existing system to give the requirement specifications because they are the people who finally use the system. This is because the requirements have to be known during the initial stages so that the system can be designed according to those requirements. It is very difficult to change the system once it has been designed and on the other hand designing a system, which does not cater to the requirements of the user, is of no use. The requirement specification for any system can be broadly stated as given below: 
 
•	The system should be able to interface with the existing system 
•	The system should be accurate 
•	The system should be better than the existing system 
The existing system is completely dependent on the user to perform all the duties. 
   
3.3 Non-Functional Requirements 
 
The non-functional requirements specify the quality attribute of a software system. They judge the software system based on Responsiveness, Usability, Security, Portability and other non- functional standards that are critical to the success of the software system. Example of non- functional requirement, “how fast does the website load?” Failing to meet non-functional requirements can result in systems that fail to satisfy user needs. 
Non-functional Requirements allows you to impose constraints or restrictions on the design of the system across the various agile backlogs. Example, the site should load in 3 seconds when the number of simultaneous users are > 10000. Description of non-functional requirements is just as critical as a functional requirement. 
•	Usability requirement 
 
•	Service ability requirement 
 
•	Manage ability requirement 
 
•	Recoverability requirement 
 
•	Security requirement 
 
•	Data Integrity requirement 
 
•	Capacity requirement 
 
•	Availability requirement 
 
•	Scalability requirement 
 
•	Interoperability requirement 
 
•	Reliability requirement 
 
•	Maintainability requirement 
 
•	Regulatory requirement 
 
•	Environmental requirement 
 
Advantages of Non-Functional Requirement 
 Benefits of Non-functional testing: 
 
•	The non-functional requirements ensure the software system follow legal and compilation rules. 
•	They ensure the reliability, availability, and performance of the software system. 
•	They ensure good user experience and as of operating the software. 



4.SYSTEMREQUIREMENTSSPECIFICATION 
 
Software Requirements 
The functional requirements or the overall description documents include the product perspective and features, operating system and operating environment, graphics requirements, design constraints and user documentation. The appropriation of requirements and implementation constraints gives the general overview of the project in regard to what the areas of strength and deficit are and how to tackle them. 
•	PythonIDLE3.7version (or) 
•	Anaconda3.7(or) 
•	Jupiter(or) 
•	Google Collab 
 
4.2 Hardware Requirements 
 
Minimum hardware requirements are very dependent on the particular software being developed by a given Enthought Python / Canopy / VS Code user. Applications that need to store large arrays/objects in memory will require more RAM, whereas applications that need to perform numerous calculations or tasks more quickly will require a faster processor. 
•	Operating system 	: 	Windows, Linux 
•	Processor 	: 	minimuminteli3 
• 	Ram 	: 	minimum4 GB 
• 	Hard disk 	: 	minimum250GB 
4.3 SELECTEDSOFTWARE: 
What is Python? 
 
Below are some facts about Python. 
 
•	Python is currently the most widely used multi-purpose, high-level programming language. 
•	Python allows programming in Object-Oriented and Procedural paradigms.  
•	Python programs generally are smaller than other programming languages like Java. 
•	Programmers have to type relatively less and indentation requirement of the language, makes them readable all the time. 
•	Python language is being used by almost all tech-giant companies like–Google, Amazon, 
Face book, Instagram, Dropbox, Uber… etc. 
The biggest strength of Python is huge collection of standard libraries used for- 
•	Machine Learning 
•	GUI Applications (like Kivy, Tkinter, PyQt etc. ) 
•	Web frameworks like Django (used by You Tube, Instagram, Dropbox) 
•	Image processing (like Opencv, Pillow) 
•	Web scraping (like Scrapy, Beautiful Soup, Selenium) 
•	Test frame works 
•	Multimedia 
Advantages of Python 
 
Let’s see how Python dominates over other languages. 
 
1. Extensive Libraries 
Python downloads with an extensive library and it contain code for various purposes like regular expressions, documentation-generation, unit-testing, web browsers, threading, databases, CGI, email, image manipulation, and more. So, we don’t have to write the complete code for that manually. 
2. Extensible 
 
As we have seen earlier, Python can be extended to other languages. You can write some of your code in languages like C++ or C. This comes in handy, especially in projects. 
3. Embeddable 
 
Complimentary to extensibility, Python is embeddable as well. You can put your Python code in your source code of a different language, like C++. This lets us add scripting capabilities to our code in the other language. 
4. Improved Productivity 
 
The language’s simplicity and extensive libraries render programmers more productive than languages like Java and C++ do. Also, the fact that you need to write less and get more things done. 
5. IOT Opportunities 
 
Since Python forms the basis of new platforms like Raspberry Pi, it finds the future bright for the Internet Of Things. This is a way to connect the language with the real world. 
6. Simple and Easy 
 
When working with Java, you may have to create a class to print ‘Hello World’. But in Python, just a print statement will do. It is quite easy to learn, understand, and code. This is why when people pickup Python, they have a hard time adjusting to other moreover base languages like Java. 
7. Readable 
 
Because it is not such a verbose language, reading Python is much like reading English. This is the reason why it is so easy to learn, understand, and code. It also does not need curly braces to define blocks, and indentation is mandatory. These further aids the readability of the code. 
8. Object-Oriented 
 
This language supports both the procedural and object-oriented programming paradigms. While functions help us with code reusability, classes and objects let us model the real world. 
 
9. Free and Open-Source 
 
Like we said earlier, Python is freely available. But not only can you download Python for free, but you can also download its source code, make changes to it, and even distribute it. It downloads with an extensive collection of libraries to help you with your tasks. 
10. Portable 
 
When you code your project in a language like C++, you may need to make some changes to it if you want to run it on another platform. But it isn’t the same with Python. Here, you need to code only once, and you can run it anywhere. This is called Write Once Run Anywhere (WORA). 
However, you need to be careful enough not to include any system-dependent features. 
11. Interpreted 
    Last, we will say that python is an interpreted language. Since statements are executed one by one.        
Advantages of Python Over Other Languages 
 
1. Less Coding 
Almost all of the tasks done in Python requires less coding when the same task is done in other languages. Python also has an awesome standard library support, so you don’t have to search for any third-party libraries to get your job done. This is the reason that many people suggest learning Python to beginners. 
2. Affordable 
 
Python is free therefore individuals, small companies or big organizations can leverage the free available resources to build applications. Python is popular and widely used so it gives you better community support. The 2019Githubannualsurveyshowed us that Python has overtaken java in the most popular programming language category. 
3. Python is for Everyone 
 
Python code can run on any machine whether it is Linux, Macor Windows. Programmers need to learn different languages for different jobs but with Python, you can professionally build web apps, perform a data analysis and a machine learning, automate things, do web scraping and also build games and powerful visualizations. It is an all-rounder programming language. 
Disadvantages of Python 
 
So far, we’ve seen why Python is a great choice for your project. But if you choose it, you should be aware of its consequences as well. Let’s now see the down sides of choosing Python over another language. 
1. Speed Limitations 
We have seen that Python code is executed line by line. But since Python is interpreted, it often results in slow execution. This, however, isn’t a problem unless speed is a focal point for the project. In other words, unless high speed is a requirement, the benefits offered by Python are enough to distract us from its speed limitations. 
2. Weak in Mobile Computing and Browsers
 
While it serves as an excellent server-side language, Python is much rarely seen on the client-side. Besides that, it is rarely ever used to implement smartphone-based applications. One such application is called Carbon Nelle. 
The reason it is not so famous despite the existence of Bryton is that it isn’t that secure. 
 
3. Design Restrictions 
 
As you know, Python is dynamically typed. This means that you don’t need to declare the type of variable while writing the code. It uses duck-typing. But wait, what’s that? Well, it just means that if it looks like a duck, it must be a duck. While this is easy on the programmers during coding, it can raise run-time errors. 
4. Under developed Database Access Layers 
 
Compared to more widely used technologies like JDBC (Java Data Base Connectivity) and ODBC (Open Data Base Connectivity), Python’s database access layers are a bit underdeveloped. 
Consequently, it is less often applied in huge enterprises. 
 
5. Simple 
 
No, we’re not kidding. Python’s simplicity can indeed be a problem. Take my example. I don’t do Java, I’m more of a Python person. To me, its syntax is so simple that the verbosity of Java code seems unnecessary. This was all about the Advantages and Disadvantages of Python Programming Language. 
Install Python Step-by-Step in Windows and Mac 
 
Python a versatile programming language doesn’t come pre-installed on your computer devices. Python was first released in the year 1991  and until today it is a very popular high-level programming language. Its style philosophy emphasizes code readability with its notable use of great white space. The object-oriented approach and language construct provided by Python enables programmers to write both clear and logical code for projects. 
How to Install Python on Windows and Mac
 
There have been several updates in the Python version over the years. The question is how to install Python? It might be confusing for the beginner who is willing to start learning Python but this tutorial will solve your query. The latest or the newest version of Python is version 3.7.4 or in other words, it is Python 3. 
Note: The python version 3.7.4 cannot be used on Windows XP or earlier devices. 
 
Before you start with the installation process of Python. First, you need to know about your System Requirements. Based on your system type i.e. operating system and based processor, you must download the python version. My system type is a Windows64-bit operating system. So, the steps below are to install python version 3.7.4 on Windows 7 device or to install Python 3. Download The Python Creates there. The step so how to install Python on Windows 10, 8 and 7 are divided into 4 parts to help understand better.  
Download the Correct version into the system
 
Step 1: Go to the official site to download and install python using Google Chrome or any other web browser. OR Click on the following link: https://www.python.org 
 
Now, check for the latest and the correct version for your operating system. 
Step2: Click on the Download Tab. 
 
Step 3: You can either select the Download Python for windows 3.7.4 button in Yellow Color or you can scroll further down and click on download with respective to their version. Here, we are downloading the most recent python version for windows 3.7.4 
 
Step4: Scroll down the page until you find the Files option. 
Step5: Here you see a different version of python along with the operating system. 
 
•  To download Windows 32-bit python, you can select any one from the three options: Windows x86 embeddable zip file, Windows x86 executable installer or Windows x86 web-based installer. 
•  To download Windows 64-bit python, you can select any one from the three options: Windows x86-64 embeddable zip file, Windows x86-64 executable installer or Windows x86-64 web-based installer. 
Here we will install Windows x86-64 web-based installer. Here your first part regarding which version of python is to be down loaded is completed. Now we move ahead with these second part in installing python i.e. Installation 
Note: To know the changes or updates that are made in the version you can click on the Release Note Option. 
Installation of Python 
 
Step 1: Go to Download and Open the downloaded python version to carry out the installation process. 

Step2: Before you click on Install Now, make sure to put a tick on Add Python3.7 to PATH. 
  
Click on Install NOW. After the installation is successful, Click on Close. 
 
With these above three steps on python installation, you have successfully and correctly installed Python. Now is the time to verify the installation. 
Note: The installation process might take a couple of minutes. 
 
Verify the Python Installation 
 
Step1: Click on Start 
 
Step2: In the Windows Run Command, type “cmd”. 
 
Open the Command promptoption. 
 
Step4: Let us test whether the python is correctly installed. Type python–V and press Enter. 
 
 Step5:Youwillgettheansweras3.7.4 
 
Note: If you have any of the earlier versions of Python already installed. You must first uninstall the earlier version and then install the new one. 
Check how the Python IDLE works 
 
Step1: Click on Start 
 
Step2: In the Windows Run command, type “pythonidle”. 
 
 Click on IDLE(Python3.764-bit) and launch the program
 
Step 4: To go ahead with working in IDLE you must first save the file. Click on File > Click on Save 
 
Step5: Name the file and save as type should be Python files. Click on SAVE. Here I have named the files as Hey World. Step6: Now for e.g. enter print(“Hey World”)and Press Enter. 
 
You will see that the command given is launched. With this, we end our tutorial on how to install Python. You have learned how to download python for windows into your respective operating system. 
 
 

  


 
 
 

