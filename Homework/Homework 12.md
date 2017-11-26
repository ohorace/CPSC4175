## Olivia Horace
### Homework 12, CPSC-4175
Chapter 18

*1. What do you think is the difference between an aspect in the aspect oriented development model and
a class in an object oriented development model? Be specific.*  
Aspects in the aspect oriented development model are defined as special modules. They have code that is linked to specific places in a project. A class in the object oriented development model is designed to create objects that will have a specific function. The goal of OOD is to design code that is highly reusable to avoid repetition.

*2. Consider the problem of targeting software to a particular platform, e.g. a handheld device as opposed
to a desktop computer. Describe the differences between addressing this problem in the design phase(s)
of the engineering process and the analysis phase(s) of the engineering process.*  
The design phase will have to take into account the kind of technology that will be used to build the software. Likewise, the analysis phase will have to be specific to that platform as well. It should include any necessary prerequisites for the platform. For example, mobile application operating systems will need to be specified such as Android or iOS. From there, the design will be dependent on that, i.e., using Android Studio vs xCode.  

*3. (Not in book) The Universal Windows Platform (UWP) is one major effort to solve the problem of
deploying software to different platforms. Research the UWP, and brie y describe its approach to
solving this problem.*  
Microsoft Visual Studio has functionality that will help someone to deploy a UWP application. The target machine can be chosen and then there are different options to deploy the application. *Simulator* can be used to deploy an application to a simulated environment on your machine. *Local machine* can be used to deploy the app to your current machine. *Remote machine* allows you to choose a remote target to deploy the app. *Device* will deploy to a USB device. Finally, *Emulator* will deploy the app to an emulator.  

*4. How does a point-and-click IDE (such as Visual Studio) promote component based design? What do
you think the benefits of component based design are? What are its costs?* 
In these types of IDEs it's easier to see how components work together. Some of these IDEs will even generate some design documents for you based on your current project structure. This makes it easier to visualize how pieces are working together, especially if you aren't seeing it yourself during the implementation phases. These kinds of IDEs, however, are usually larger. Many of these IDEs are not free either so there is the issue of licensing.  

*5. Describe infrastructure-as-a-service (IaaS), platform-as-a-service (PaaS), and software-as-a-service (SaaS).
What are the differences between them? What are the similarities?*  
*Infrastructure-as-a-service* is a form of cloud computing that provides resources via the internet.  
*Platform-as-a-service* is also a form of cloud computing that allows a user to build and run applications over the internet.  
*Software-as-a-service* is used to license software by subscriptions. This software is housed in a central location.  
All of these are components of cloud computing yet they address different areas. All are necessary for cloud computing to work and they all are of equal importance. 

*6. The Semantic Web incorporates the concept of marking up information, as opposed to marking up
structure (HTML) and presentation (CSS). This is commonly done with XML. Create a document
marking up the information contained in a fast food menu (hamburgers, tacos, pizza, sandwiches,
etc.). Your document should contain about ten or twelve different items.*  

*7. Discuss one specific technique you can use in your personal software development process that ad-
dresses the concerns of software security. "Discuss" includes describing the technique, explaining how
it promotes security, and giving a concrete example.*  
In my personal software development, I try to randomize anything that I can that will provide security. For example, in our project for this course, we use a random number generator to create our account numbers of a certain length. Instead of having them hard coded or chosen from a set of numbers, they are randomly generated each time an account is created. This makes it harder to brute-force attack because of the length and method used to create this number.

*8. Read the article by E. F. Codd entitled A Relational Model of Data for Large Shared Data Banks, in
the PDF directory in my class Github repository as codd.pdf. Write a one paragraph appreciation of
this article.*  
This was definitely a research paper on a level that I was not prepared to read. I'm sure the amount of work that went into this was astonishing. Codd's abstract covers a very excellent point that the "[f]uture users of large data banks must be protected" (par 1). Everything is data and with breaches becoming more and more common, security of these data is going to be vital. He also mentions that data representation will be changing as a result of changes in how data is accessed and maintained. Codd also discusses relational views of data and defines them. There are different kinds of relations such as unary, binary, ternary, and n-ary.  
