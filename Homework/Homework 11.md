## Olivia Horace  
### Homework 11, CPSC-4175  

**1. Give an informal description or definition of stepwise refinement. Pretend that you are trying to explain
it to your grandmother or a younger brother or sister.**  
In stepwise refinement, decisions are postponed as late as possible. In other words, someone/a team procrastinates on making a decision in order to focus on other things that are more important.

**2. Consider topdown development, stepwise refinement. We have now encountered both of these. Tradi-
tionally, software engineering was taught developing programs using the topdown, stepwise refinement
paradigm. (OOAD has replaced this paradigm.) You have probably never developed a program using
that paradigm, but think about the implications of that technique versus OOAD. Discuss several of
the major differences you can think of.**  
I believe that top down development is more straight-line than OOAD. It involves development from top to bottom while holding off on items that are of less importance. With stepwise refinement, you work on the items of most importance but with OOAD the entire project is broken down into modules. These modules come together in the end to create the software product that has been requested. 

**3. Read the article in my PDF directory on Github by Nicklaus Wirth entitled Program Development by
Stepwise Refinement and write a one paragraph appreciation of that article.**  
This article made some good points from the very beginning. I agree that programming is done by examples. Likewise, I agree that active programming consists of designing new programs. Technology is ever changing so something that worked 10 years ago may not be the most efficient method in present day. Wirth explains refinement step development as a gradual sequence. The steps are broken down and refined. Usually each step involves a series of decisions or choices to be made regarding the goal of that particular step.  

**4. In business school cost benefit analysis goes by the name due diligence. Following the example in the
book, give a non-technical example of the exercise of due diligence. ("Non-technical" in the sense of a
business or management decision, for example, opening a branch office or expanding a product line.)**  
An example of due diligence would be if a company decides to stop sending postage paid envelopes. They would have to determine the cost of the current status quo. Then, they would have to estimate the cost of the alternative (i.e. going digital instead of sending postage paid envelopes). Likewise, they need to analyze the benefits of making this change.  

**5. Your book gives the following illustration: "suppose that object A contains an invocation of a method
of object B. In this situation, object A cannot be reused without reusing object B as well." Please
discuss this problem and state a specific solution to the problem that advances separation of concerns.**  
The problem here is trying to minimize interactions between components. Composite design is one possible solution to this problem. This involves designing modules that have heavy interaction within themselves and minimum interaction with other modules. The former is known as high cohesion and the latter is known as low coupling.  

**6. Answer one of the following two questions. Use the analytical tools you have read about in this chapter.
(a) Design a small program and write the pseudo-code that generates documentation from a source file.
Input is a source listing. Output is a formatted documentation document. You documentation
should document all variables by giving the visibility, type, name, and initial value, and all
functions giving the visibility, type, name, and input parameters. You are allowed to require your
source listings to use a particular formatting, similar to Javadoc.**  
        import java.io.*;  
        //begin pseudocode
	
 	throw IOException
	private String methodHeader;
	private String description;
	private String codeText;

	read in source file as input
	while(fileReader.hasNext()){
	input = fileReader.nextLine();

	if line is a part of a method header
		i.e. locate curly braces
		generateHeader(String input)

	if line is a comment
		i.e. locate forward slashes
		generateComments(String input)

	else
		//if line is code
		generateCode(String input)
     }
	

**7. One very common problem, particularly with languages similar to C, is that many files must be compiled
in a specific order because of (among other things) dependencies among files. For example, program.c
may depend on program.h. Make files are almost universally used. Search for a brief makefile example,
and comment on it line by line.**  

     # build an executable named myprog from myprog.c //simple makefile example   
      all: myprog.c
		//compiles program and generates debugging information using -g
		//-wall enables compiler's warning messages, -o writes to an output file  
		gcc -g -Wall -o myprog myprog.c
	
      clean:  
            $(RM) myprog//action to remove file
