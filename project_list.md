# Project Assignments

Please file your top THREE choices as an issue (will go over in class) by Wednesday () morning at 11:59 AM (i.e., right before noon).  Please list them in the order that you prefer them.  You will be informed as to your project during the next Capstone class on Friday 8 Sep.  If you do not file an issue by then, I will assume you do not care which project you are on and I will place uncommitted students on whichever projects still need people.

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects.   Remember that you are "interviewing" for the project against others, especially if you have selected popular projects.   Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices.  Last semester, every student got into one of their top three (and a majority into their #1 choice), although I do not make any guarantees.

Note: Some of you are working on private projects.  Please file an issue on this repository (as above) but note that you have already been assigned to a project.  List the project and the name of the POC (e.g. faculty member or supervisor).  If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry 

### Yelp

_Yelp Chatbot_ - Yelp will support a student team in building a chatbot using our public API (https://www.yelp.com/developers/documentation/v3) to provide suggestions and information about local businesses. For example, the bot might suggest a local restaurant when it detects a chat conversation about where to go for lunch. The possibilities are endless--be creative!  This can be built for any popular chat service, and can be implemented in any technology stack.  The resulting design and code will belong to the students. Our goals are to tap student creativity in exploring new ways of using Yelp, to get to know a talented team of students, and to support those students in building something cool and useful. About Yelp: Yelp is one of the world's top web and mobile development organizations. We have a strong internship program at our San Francisco headquarters and we hire lots of new college grads. Our Pittsburgh office is at Forbes and Meyran, practically in the midst of Pitt's campus. Our local engineering team includes Pitt alums, experienced entrepreneurs, and Carnegie Mellon alums. (POC: Brian Cavalier, Yelp)

### NetApp

NetApp is developing a product called ONTAP Select Deploy which is a Debian-based VM for orchestrating the deployment of ONTAP Select clusters in a hypervisor environment. For Deploy, we are interested in the future of allowing SSO type login, especially for customers who are using ESX. VMware exposes APIs for authenticating against a vCenter. That is, they offer external identity verification like FB, Google, etc. do for the web.
 
For the project, the students would be responsible for the following items:
 
1. Set up a Debian-based VM in a VMWare vCenter (vCenter is provided)
2. Set up a user account for SSH access with UNIX credentials (username/password on the local machine)
3. Set up vCenter based authentication for SSH login. That is, when the user tries to log in via SSH, let them do so with valid vCenter credentials.
4. Set up an Nginx web server on the VM and have it serve some pages behind basic authentication
5. Set up Nginx to allow for the vCenter credential authentication flow as well

### Viz

_Window Shopping for Data_ - Most people are familiar with the Google approach to search the internet for sources. That works well for an internet-scale repository. When attempting to do a search on a small repository, the user has to play the game of “guess the magic word” as the user is unaware of what is in the repository. The worst situation is when the system returns a result to say there is nothing that matches the search term— is it really the case or did the user not guess the right magic word.

A contrasting approach would be to browse through the repository to find a document of interest. A “window shopping” analogy. While there are some e-Discovery tools that support this approach, they are often specific to a particular domain which does not make them very suitable for a general audience. They are also very heavyweight for each repository and does not scale for multiple repositories. We have text analysis tools that will provide lots of lists of the contents of a repository, but that does not help a user. We are looking for a means to convert those lists into a form that is more useful to a user who needs to find something. (POC: Dr. Mike Bigrigg, General Dyamics Viz)

## Open-Source

### WordPress

_Gutenberg_ - Gutenberg is a new editor experience for WordPress, the open source software used by more than 29% of the internet for creating beautiful websites, blogs, or apps. The goal of the Gutenberg project is to create a new content editing experience that makes it easy for anyone to create rich post and page layouts. It is in active development on GitHub under the WordPress organization. Students will take on the responsibility of developing features for the project, resolving bugs, performing code review, and participating in the discussions which occur in GitHub issues and in the WordPress development Slack instance. Learn more at https://wordpress.org/gutenberg/ . (POC: Andrew Duthie, JavaScript engineer, Automattic)

## Faculty Projects

### Cryptocurrency Code Quality Analysis

_Code Quality Analyzer_ - While cryptocurrency is a burgeoning field at the moment, many projects are of poor quality or are not well-tested.  The goal of this project is threefold.  The first is to determine what constitutes good metrics of code quality and test coverage in relation to a cryptocurrency code base - these are preferably objective and calculable as opposed to subjective.  The second is to determine a list of major cryptocurrencies (e.g. Bitcoin, Ethereum, Litecoin, etc.) and analyze their codebases, and collate this information.  Finally, if time permits, I would like to make this an entirely automated process (e.g., clone the relevant repositories down once per week, run the appropriate tools, and post the results).  Note that this project will be polyglot - you will have to work in several different languages and learn new static analysis tools.  Previous knowledge of cryptocurrency and blockchain technology is not strictly necessary but interest in it is essential. (POC: Bill Laboon, University of Pittsburgh, Computer Science)

### Pharmacy Quiz Game

_Pharmacy Quiz Game_ The PILLab and School of Dental Medicine seek to combine two separate quiz game applications into a unified system. This essentially requires quality assurance testing of the merged databases and the design of a consolidated view offering access to all quizzes. There may be an additional opportunity to re-design the leaderboard and its underlying mechanics. Students who work on this project will gain experience in full-stack (LAMP) development, with an emphasis in database design and interface design under the guidance of domain and technical experts. Successful completion of this project will result in the product being tested directly with users to complete an iteration of the development cycle. (POC: Jonathan Velez, University of Pittsburgh, Information Science and Dr. Ravi Patel, University of Pittsburgh, School of Pharmacy)


### PILLab 

_PILLab website transformation_ - The PILLab is seeking to transform their current website (www.pillab.tech) into a communication and branding platform for their organization. This essentially requires the development an administrative dashboard for managing content, the implementation of session management strategies, and the production of scripts used to dynamically present content. Students who work on this project will gain experience in full-stack (LAMP) development, with an emphasis in database design and interface design under the guidance of domain and technical experts. This product will go live into service upon completion of the project, and will make an excellent professional achievement in any student’s portfolio. (Jonathan Velez, University of Pittsburgh, Information Science and Dr. Ravi Patel, University of Pittsburgh, School of Pharmacy)

### OCCAM Projects

Software curation has been growing in importance in the last decade as studies show that experimental results are hard to reproduce. As reproducibility evolves, along with data and software, and artifact curation, tools are being developed to support it. One such tool is OCCAM, and is being developed right here in the CS Dept at the University of Pittsburgh. (POC: Dr. Daniel Mosse)

* _Development of interactive user interfaces for OCCAM_ - To make OCCAM easy to use by untrained people (e.g., non-computer scientists), user-friendly interactive tools/interfaces are required. The objective of this project is to develop interfaces that guide OCCAM users through all the steps of importing their software into a format that OCCAM can execute. Namely, 1) uploading their software, 2) describing other software dependencies, 3) building and running scripts, and 4) specifying inputs/outputs/configuration options. Students will develop a web application using ruby and javascript, two of the main languages used for web development, and writing both unit and acceptance tests for that application using frameworks like minitest, and capybara.

* _Extending OCCAM to provide a system-level virtual environment with Vagrant_ - OCCAM currently executes software using Docker containers, a lightweight OS-virtualization software that abstracts the running OS to ensure a consistent and coherent running environment. However, one of the shortcomings of Docker is that it shares the Linux kernel of the running system. As a consequence, software that requires a specific kernel version, or software that needs to modify the kernel cannot be executed in Docker. The objective of this project is to extend OCCAM to support system-level virtualization, such as VirtualBox, using tools like Vagrant that allow to spawn virtual machines on demand. To achieve this, you will have to develop an extension to OCCAM using Python, and possibly other programing languages, that analyses software requirements (provided by OCCAM) and creates a virtual machine capable of running that software.

* _Deploying hardware specific SRAM,FRAM experiments with OCCAM and Arduino/Rasp. Pi_ - Running software in commodity hardware is restrictive sometimes, given that some embedded or real-time systems need specific hardware (eg, running a real-time OS, caches disabled, FPGAs, etc).  In this project, students will study and extend OCCAM by designing the necessary modules (software mostly) to interact with the specialized hardware.  For example, benchmarking a SRAM modules (e.g., 23LCV512-I/P vs FM24V05-G) read/write speed access over i2C and SPi protocols in programmable microcontrollers platforms such as Arduino/Raspberry Pi using OCCAM.  Students will write code to interact with the memory modules and write the benchmark code. Also they will design and deploy the experiment running a local OCCAM instance. Qualitative  and qualitative analyses (e.g., performance measurements, time it took to implement, and difficulties encountered) when deploying the experiment will also be a part of this project. 

## Bioinformatics-focused

These projects have a focus on bioinformatics specifically.  Preference is given to BIOSC1640 or CS1640-registered students, or those with a background in bioinformatics or a related discipline.  This does not mean that you cannot sign up for them if you are not in one of those classes, however - in fact, I think it would be ideal to have a good mix of CS and Bioinformatics students working on these.

### Sheep and Goat Tracker

_Sheep and Goat Tracker_ - An app to track all information pertaining to a sheep and goat production enterprise:  breeding, birthing, weighing, scoring, treating, etc. An app that can make calculations to convert raw data into performance data. For example, to compare weaning weights of lambs and kids, all weights have to be adjusted to a common age. They also have to be adjusted for the sex of the lamb/kid, its type of birth and rearing (single, twin, or triplet), and the age of its dam. It is desirable to convert many performance measures to ratios for easier comparison. It is desirable to be able to summarize information from multiple years and to calculate whole flock/herd statistics. An app that runs on both iOS and android platforms and synchronizes with the cloud is ideal. (POC: Susan Schoenian, Sheep & Goat Specialist, University of Maryland)

### Sterile Compounding Augmented Reality

_Augmented Reality in Clinical Training_ - Create an augmented reality environment to train clinicians in specialized clinical procedures.  Training in sterile compounding is a component of pharmacy education and training across the country. Similarly, training for appropriate hand washing required to enter surgical environments are required of medical students. The resources required for this training can be prohibitive due to the time, personnel, and space requirements. Coordinating the resources, trainee experiences, and feedback required in appropriate training is a universal problem for schools, hospitals, and institutions that provide customized pharmacy sterile compounding and surgical procedures in healthcare.  This project will allow (POC: Dmitriy Babichenko, University of Pittsburgh, Information Science)

### Durrant Lab

_Web-Based Drug Discovery_ - The Durrant Lab creates drug-discovery software for analyzing small molecules and proteins. Unfortunately, our software is not always user friendly, and it sometimes requires extensive computer resources. These challenges limit broader adoption. Working with Pitt's Center for Resource Computing and the Network Operating Center, we have begun to build an online system that will allow users to submit their calculations through a web-browser and to run those calculations in the cloud. This project involves building browser-based HTML/JavaScript components (e.g., text boxes, option boxes, etc.) that will allow the user to interact with our system. Familiarity with JavaScript (or, even better, TypeScript) and HTML is essential. The project will require about 10 hours per week.

