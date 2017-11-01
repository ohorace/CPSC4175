## Olivia Horace  
### Homework 10, CPSC-4175  

**1. In building a software product, the book identifies two kinds of planning that must occur. Name the
two types and give two examples of each.**  
The two types of planning are: (1) the planning that proceeds throughout the project and (2) the intense planning that must be carried out once the specifications are complete.  
Examples of 1: creating a plan for how to complete a project, determining resources needed for a project  
Examples of 2: estimating cost, estimating a timeline for project completion  
**2. What does figure 9.1 tell you about the range of cost estimates during the various workfl ows of a
software project? Be specific as to the percentage of uncertainty at each of the four work flows shown
on the X axis of the chart.**  
The figure shows that the cost estimate is the highest during the Requirements phase. In the case of a $1 million dollar cost, if the project cost was estimated during the Requirements phase, it would have been in the range of $0.25 million and $4 million. This is much higher than the estimated cost during the implementation phase, which would have an estimate between $0.67 million and $1.5 million. That is a significant difference in cost estimation.  

**3. The book identifies two different kinds of costs associated with building a software product. Identify
the two kinds of costs, and for each give two examples.**  
The two different kinds of costs are: (1) **internal cost** which is the cost to the developers and (2) **external cost** which is the price that the client will pay.  
Examples of 1: salaries of the development team, the cost of the hardware and software for developing the product
Examples of 2: how much the client is going to pay for the software, how much they will provide for the creation of the software  

**4. The book lists six reasons why the LOC (lines of code) metric may not be satisfactory. List four
of them and for each, give an example (preferably from your own personal experience) showing the
problematic nature of that reason.**  
*Creation of source code is only a small part of the total software development effort* - the lines of code is really only a smaller part of the bigger picture. The number of lines does not accurately reflect the amount of work that went into an overall effort.  
*Implementing the same product in two different languages results in versions with different numbers of lines of code* - this is especially true because in some languages I've used, the same code ended up being significantly shorter or longer. For example, writing a program to sort strings in Java can be done with a lot fewer lines than an assembler program.  
*It is often unclear exactly how to count lines of code* - what exactly is defined as a line of code? Is a single curly brace on a line by itself counted as a line of code? If so, that can easily affect the total and would vary based on the programmer. Some like to have the curly braces on a line by themselves and some like to put it at the end of the preceding line.  
*The number of lines of code in the final product can only be determined when the product is finished* - estimating the cost of a product based on the estimate of the lines of code is not reliable and it is discouraged. There is no way to know the final count of lines until the project is finished. This estimation can, and probably will, change several times during the course of development.  
**5. The function point metric is widely used. Do some independent research on function point analysis/-
function point estimation and write a brief summary of your research. In particular, Does there seem
to be a widely accepted formula for function point estimation?**  
Function point analysis is defined as a sizing measure of business significance. Essentially, it relates to business requirements for software. It analyzes the functions found in software based on their use and acceptance by the software users. This type of analysis can be used on any type of software development as well as during any phase of the development. From the article I found, there is a widely accepted formula and the result of this formula is a single number. This number is called the Function Point index and it is used to measure the size and complexity of software. 

http://www.ifpug.org/about-ifpug/about-function-point-analysis/  

**6. The book references IEEE-158. This standard has been superseded by IEEE-16326. I have placed a
copy of IEEE-16326 in the SWE directory of my Github repository for CPSC-4175. Select one major
subsection of subsection 5 (Elements of the project management plan) and write a brief discussion of
that major subsection. Choose whatever item interests you.**  
The project planning subsection discusses project management processes. This section goes over different parts of the planning process. This includes staffing and estimation which are two points that I think are very important. The staffing section focuses mainly on finding people with the skills required for the project as well as getting the correct number of people. The estimation plan section focuses on cost and scheduling. From the previous questions on this chapter, estimation is a very important part of software development. It is very crucial and this section not only covers cost but also schedule, resource requirements and confidence levels. 

**7. The book notes that, for every 100 hours developers spent on implementation, they spent 150 hours on
activities related to documentation. Give some thought to your project in this class, and state some
practices and/or guidelines you may adopt in an effort to generate appropriate documentation for your
project. As you will discover when you work as a developer, in many cases, a failure to document your
efforts is tantamount to a failure to complete the project.**  
I think the first thing that I need to do is to start better documenting the work that I do on the project. I don't have much documentation for the project thus far. I think that from now on I will have some type of documentation for every artifact that I produce. This will include basic info such as the iteration, the date, what it is, how it was produced, how long it took and any other notes that I believe are relevant. 

**8. Why do you think a user would conclude that you did not write a piece of software if you did not
document the software?**  
Someone would think that you did not write a piece of software because there is no trail of documentation that shows someone that you wrote said software. This documentation allows someone to understand why you did what you did as opposed to coding it another way. Likewise, not having documentation for code that isn't *very* simple (such as Hello World) can often make someone think that you just copied it from somewhere. This would also make someone assume that you do not know how that piece of code works and could not explain it if asked to do so.
