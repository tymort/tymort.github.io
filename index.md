---
driveId: 1WhfWkIvw8S2VV3WZuG3Idtqwl0FVeXe7/preview
---

## Self-Assessment

Over the course of my past 3 years with SNHU, I have gained several important skills pertaining to the field of computer science. I will be able to carry these skills with me into my future career and hobbies. I entered SNHU with very limited coding knowledge, only maintaining the knowledge I had acquired through an intro to computer science at Boyertown Area Senior High. However, with time this grew into a vast knowledge of databases, algorithms and data structures, and software design and engineering. These pillars of my education will forge the path to a successful career in the industry. 

### Team Environments:
My time at SNHU has allowed me to participate in many team environments. I have been lucky enough to be a part of many group discussions and utilizing GitHub repositories to publish and share my work. I have been able to gain experience with the web browser version of GitHub, command line commits, and the GitHub desktop app which prepares me for any variety of GitHub work in my career. I was able to utilize pull requests and our discussion boards to assist other classmates with their work. Recently, in my CS-465 course, I was able to help another classmate with an issue loading their dashboard. The site would show up completely blank. I was able ot issue a pull request and view their code and discovered they had referenced the site as an HTTPS domain, however, without proper certificates it was invalid. I changed it to an HTTP reference and the site worked perfectly. This showcases how important collaboration is to a team. 

### Communicating to Stakeholders:
Communicating with stakeholders in an important part of ensuring appropriate expectations, pace, and results. One course with SNHU focused on the Agile model, much like real development teams. In this course I took the role of a scrum master, a developer, and a project manager. I was able to work many of the different aspects of these interactions whiched help me to better understand the goals of each member in ensuring their voices made it to the shareholders. In doing this, I learned it is very important to set clear expectations. Both the development team and stakeholders should be very clear on the expected development time and resources, as well as the project specifications. This can be done in many ways, but one of the most common is a UML or Universal Modeling Language. This is a form of unified markup that allows the team to visually represent the projects and its many aspects in an easy to read manner that showcases its scope. The project manager can present this to the stakeholders and ensure it matches their vision before any work begins.

### Data Structures and Algorithms:
Data has become ever more important as the digital era continues to grow. Thankfully, SNHU has taught me the importance of proper data management and utilizing efficient algorithms. I have learned the most appropriate storage and retrieval methods for a variety of situations. Structures such as vectors, hash tables, and binary search trees have been explained and their strengths and weaknesses documented. By understanding a wide variety of these structures, I can always choose the most effective and efficient method for my work.

### Software Engineering and Databases:
There have been many interactions with MongoDB, DynamoDB, and SQL databases. I have learned the many differences between these databases and when each one is better than the other, such as DynamoDB for large databases and fast queries. I have also learned how to create CRUD (Create, Read, Update, Delete) modules to allow me to interface with my databases through my code. I have learned advanced querying techniques such as aggregation which allows me to see the data I need as fast as possible. 

### Security:
Security is critical to ensuring a consistent, well functioning application for end users. These course taught me to create secure code by checking for vulnerabilities and running vulnerability checks on dependencies. This allowed me to see where possible vulnerabilities existed and code around them or update the dependency to remove it. I have learned how to properly manage iterating programs or loops in order to ensure execution stops appropriately and doesn't hang the application. I have also learned how to perform input sanitization by checking the data input and ensuring only the relevant and safe data is accepeted. This has culminated into making sure that I think about the safety of an application as much as I can without inhibiting functionality, as a safe program is key to a happy end user.

### Inclusion:
For this project I have chosen three artifacts, with one each tackling improvments in Software Design and Enginerring, Algorithms and Data Structures, and Databases. I incorporated enhancments to a OpenGL visual scene to showcase software design improvements as I revamped the textures, lighting, and commenting to make it more readable and look more visuably comparible to its intent. I also utilized a course search tool that was formed off of a Binary Search Tree in C++ to showcase data structures and algorithms as I was able ot make significant improvements in search times. For my last enchancement I took a Dash framework project in Jupyter notebook and modified it into standalone python. I also moved it to a locally hosted MongoDB and allowed it to pull a user's liked songs on Spotify and display them, showcasing database usage. Overall, these three artifacts form together to showcase improvements across traditional and visual code, data structure and algorithm improvements, and a core understanding of databases.

## [Chosen Artifact #1](https://github.com/tymort/tymort.github.io/blob/main/Original%20Artifacts/Mort%20Category%201%20-%20CS%20330.zip)
This artifact comes from the CS-330 Computational Graphics and Visualization course. This project defines a scene with objects and textures, lighting, and camera movement. 

## [Chosen Artifact #2](https://github.com/tymort/tymort.github.io/blob/main/Original%20Artifacts/Mort%20Category%202%20-%20CS300.zip)
This artifact comes from the CS-300 Data Structures course and focuses on a class sorting mechanism. It provides an on screen display to load a CSV file of courses into a BST and then prompts the user to search for a course or print a list of course. 

## [Chosen Artifact #3](https://github.com/tymort/tymort.github.io/blob/main/Original%20Artifacts/Mort%20Category%203%20-%20CS%20340.zip)
This artifact comes from the CS-340 Adcanced Programming Concepts course. This project utilizes the Dash framework to showcase database entries with graphical visualization.


## Code Review

{% include googleDrivePlayer.html id=page.driveId %}


## [Enhancement One: Software Design and Engineering](https://github.com/tymort/tymort.github.io/tree/main/Enhancement%20One)

The artifact I created is a scene of a countertop with several glasses and a vase created in C++ using OpenGL. This artifact was originally created in the summer of 2024. 

This project was included in my ePortfolio due to its stark distinction from the other projects. It includes visual elements that are not showcased in other projects which allows me to expand my showcase and its versatility. While the use of OpenGL isn’t the only way to create visual elements, it represents an important skill for games or other visual focused projects. The artifact was improved by streamlining the lighting sources and removing a redundant light source. The main light source was softened to create a less harsh brightness as well. In addition, textures were created for the cups to make them feel more realistic and tangible than their bright, single-color predecessors. The glass cup was also made more transparent using a proper alpha channel.

One thing I learned while creating and improving this artifact is how hard it can be to revisit old projects when comments are not clear. Without the many comments I left in this code, it would be nearly impossible for me to remember its function. Thankfully through the use of these comments, I was able to relearn many of the things I knew in OpenGL and could work towards successful revision. This showcases the importance of proper documentation, especially on projects that may involve a large number of different people.

## [Enhancement Two: Algorithms and Data Structure](https://github.com/tymort/tymort.github.io/tree/main/Enhancement%20Two)

The artifact I created is a program that reads a CSV file into a binary search tree to allow the organization of college classes. This artifact was originally created in the spring of 2024. 

This project was included in my ePortfolio because it deals with search which is ever more important as companies like Google focus on improving their search divisions. The same approach used to improve search times here leads to better search times and lower complexity on those projects. Therefore, showcasing an ability to improve search metrics and understand the tradeoffs that a faster search may have, are critical to a well founded portfolio. In my improvement of the artifact, I was able to cut search times from 2.691 and 2.19 seconds to 1.368 and 1.284 seconds respectively. While this is not a large amount of raw time due to the small nature of the list, it is roughly a 50% reduction in time taken to search, albeit at the cost of accuracy. It would struggle to return an accurate result if two courses share the same number, however, this is an acceptable tradeoff for its speed as the program will not error out. Instead, it would only return one of the possible courses and then prompt again. 

One thing I learned while working on this artifact was how difficult it is to remove specifically alpha characters from a string. I was hoping to use regex like c#, however, there is no support as far as I could tell. There were several convoluted solutions, but due to the static nature of the prefixes I was instead able to trim the beginning of each string. I may try converting the course number string to an integer and see how that affects the search time as well.

## [Enhancement Three: Databases](https://github.com/tymort/tymort.github.io/tree/main/Enhancement%20Three)

The artifact I created is a program that reads a CSV file of Spotify data into a data frame for showcasing playlist statistics, however, it will have a database interface within the next few days. Unfortunately, I encountered numerous issues with MongoDB hosting and will be exploring other methods. However, all other aspects of the program are operational. This artifact was originally created in the summer of 2024. 

This project was included in my ePortfolio because it deals with web dashboards and data displays which are very important and common today, especially in business climates. The usage of a large quantity of data also makes it perfect for a database interface. While this project is not identical to it’s original artifact form, it takes the same dash dashboard and migrates it from Jupyter notebook to Python. In addition, it migrates from cloud to local hosting, allowing anyone to utilize this program with their own data. It also now supports completely custom playlist uploading. This project showcases an ability to mesh mathematical data analysis through plotly with a traditional web dashboard using dash. It utilizes a MongoDB database that stores a user's Spotify data and interfaces with this database to call for data. It then utilizes this to create and display matplot figures as html embeds.

One thing I learned while working on this artifact was how difficult it is to setup Python properly and how much of a difference it can make. When I originally setup Python on my computer, I must have downloaded it to a specific user and it now conflicts with another installation. Whenever I was utilizing pip install or other commands, it would show a successful installation, however, it would not work which prevented me from using PyMongo. I have learned to properly setup Python in the future and have begun the process of clean installing windows and Python and necessary packages. 
