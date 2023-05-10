# stoffel.github.io

# Professional Development Independent Study- Spring 2023 
## Prof Knox and Prof State

### Introduction

  The purpose of this professional development independent study is to develop skills that will be useful in the professional world. The specific implementation being use of the exercism.org C++ track to develop coding skills to complement the Data Structures class that I am currently taking that also uses the C++ language. 

### Personal Background

  My background is a professional pilot with a degree in Aerospace Engineering in my third semester of the Applied Computer Science program at the University of Colorado. As such my coding background is limited to Python and C++ as part of the 1300 introduction class and some Python in application during Discrete Structures and Cognitive Science in the second semester. During this semester we are also using the Zybooks platform. 

### Getting Started With Exercism.org

  Getting started with exercism I found it relatively easy to set up an account using my GitHub login. My first attempt at an exercise was the standard "Hello world" program which left me overconfident and ready to attempt the standard "leap year" program. I was immediately faced with different namespaces and  a ".h" file. Neither of which I had experienced before. Some googling and YouTube videos later I began to understand what namespaces are but still had little idea how to implement them. Exercism provides very little instruction other than asking for mentoring and the error codes provided by the automatic grading/checker. I decided to hold off a bit and focus on the zybook to catch up with class. Second week of zybook I was learning about classes so I began to reattempt the challenge. After about an hour of trial and error I was able to pass the "leap year" challenge and move on. I found writing code that would hopefully solve some of the errors, such as a bool function that only returned "true", allowed me to start to understand how to get an input tested and returned and cause the actual tests to run. I was still confused why when I would start with a function such as "bool is_leap_year(int year)" I would get an error because year was unexpected, that error went away when I deleted "year" but caused issues with actual variables in the code. Later I added "year" back in and the code worked with no issues. After two and a half weeks I have accomplished two challenges with no more meaningful understanding of interacting with the exercism code. On a positive side, this has given me challenges to bounce off of zybooks and I feel I'll have a much better understanding of both classes of and namespaces which can only serve me better in the future. 
The next challenge is calculating how many years 1000000 seconds is on different planets. Already I've hit the exact same wall I hit the first time. 

### Weekly updates

#### March 12 Update:

  I've been very behind on updating progress of this project. I have completed a total of six exercises in exercism and am getting a little better at understanding the interface. The biggest breakthrough came when I finally processed that the errors I was seeing included errors from the testing code, not just my own. This simplified my troubleshooting. I found focussing on the basics the last few weeks with 2270, especially reattempting the practice coding tests for the midterm made my basic programming within functions significantly better. Things I missed is making sure I add things like "#include <string>" if I was working with strings in that exercise, basics that are generally already included in the 2270 projects. I still am having trouble with a few of the "easy" projects such as "space_time" that highlight weeknesses in my understanding of classes and give me an area to focus in zybooks. I am feeling more comfortable working in exercism and am planning on requesting mentoring this week on a couple of the exercises. I also noticed they have a "A Brief Introduction to C++" on the dashboard now so I will report back on if that is useful. 

  One major lesson learned was I initially treated this site as something like zybooks that I should be able to do all inclusive. Instead, I now use exercises to guide my searches into difference functions, syntax, and features of C++ and where I need to refocus and review in zybooks.


  Worked through the Triangle exercise. I was able to find other solutions and things I leard looking at their solutions: Declaring an "enum class" of flavor to create the results for equalateral, isosceles, scalene and including <stdexcept> to throw exceptions if any of the requirements of a triangle are violated after I created tests for them. Again, I'm curious how exercism expects me to learn these issues without any reference to other solutions or hints as to what to research. It's a bit frustrating. 

  This [introduction](https://youtu.be/9RL8ZssWg5Q) to exercism C++ was added a few days ago and I wish it had existed the whole time. Gave some great resources and a coding demo that explained both the idea of improving in iteration and how much more efficient the "Reverse String" exercise could be solved. I guess part of my student mindset from 2270 is we are building the structures and algorithms as opposed to using built in which is probably making things more difficult than they should be. 
  
#### March 20th update:
  
  Worked through the Triangle exercise. I was able to find other solutions and things I leard looking at their solutions: Declaring an "enum class" of flavor to create the results for equalateral, isosceles, scalene and including to throw exceptions if any of the requirements of a triangle are violated after I created tests for them. Again, I'm curious how exercism expects me to learn these issues without any reference to other solutions or hints as to what to research. It's a bit frustrating.
  
  This [introduction](https://youtu.be/9RL8ZssWg5Q) to exercism C++ was added a few days ago and I wish it had existed the whole time. Gave some great resources and a coding demo that explained both the idea of improving in iteration and how much more efficient the "Reverse String" exercise could be solved. I guess part of my student mindset from 2270 is we are building the structures and algorithms as opposed to using built in which is probably making things more difficult than they should be.
 
  I have submitted one of my exercises for mentoring and look forward to that feedback.

#### April 2nd Update
  
  Not much progress the last two weeks that is very remarkable. Finished a couple more of the easy problems. I did have one mentor that helped me improve one of my earlier problems. I think the mentorship is useful and look forward to applying it to more difficult problems that are less straightforward. My plan for this next week is to attempt some of the medium difficulty problems. A few of them look like they include some of the number theory I learned last semester.
  
#### Update for week April 2-8
  
  Late update. Worked on one of the Exercism projects using maps. Going back and forth between this project and the Huffman project was really helpful in learning to implement maps. I'll get a chance to solidify this understanding through more practice because the exercise was updated before I had finished all the tests and most of my code was deleted. Overall I feel like my programming has changed. Both from confidence level and from attempting to program cold to understanding the tests before starting to approach my solution.

#### April 20th update:

  Worked on the Class, Two_fer, and a few other problems. I learned a bit working through the Two_fer about overrides for functions. The ability to have a default value if no value is provided by the user. I feel like I understand it in this usage but not entirely sure I follow the syntax in a way I could use it elsewhere. I'm still struggling to understand reading the test files to understand what functions I need to write. This coming week I plan on working on using exercism through an editor on my computer so I get a bit better error explanations. It's especially frustrating when I can't get the program to run to get to the tests compared to what we've been doing in class where I generally find the answers easier to understand. Last week was spent studying for both the midterm and cranking through the graph homework due next week. 

#### May 2nd update:

  Completed two more exercises working with RNA/DNA sequences. I'm getting more comfortable with searching through documentation to find and learn how to use the different libraries and functions. One insight from the graph interview was how I've learned between the two courses to go back over my code and see areas where I might create a new helper function or simplify the code. This week I'm focusing on finishing my 2270 project with that in mind and will look over a couple of the already solved solutions and community solutions to see if I can understand ways to simplify my solves and make the code cleaner. While I've struggled both with consistency and even getting started with Exercism. I feel that I learned a lot from the process, specifically how I might approach coding in the real world instead of building every function myself. I have especially struggled reading the test cases in exercism to understand what I am attempting to solve compared to the test cases provided for the 2270 class. One thing I especially miss in Exercism is the provided function skeletons that include the input and output correctly formatted. It makes me curious how this is approached in the real world. 
  
#### May 9th update:
  
  In a fitting last week of work I was finally able to complete the Space Age exercise I started with so many weeks ago. I was actually impressed how the work creating my final project allowed me to see the issues I was having a lot clearer. Combined with a better understanding of the error codes generated by the tests and the skill I should have learned a long time ago of googling error codes verbatim made this problem seem relatively easy now. My final project required me to use constructors, class variables, and constants more than I had in any previous exercise and all were fundamental in completing this exercise. It felt like a validation of the work I put into both the independent study and the 2270 course. 
  
### Summary and Conclusion
I started this semester with the vague direction that I was going to use Exercism to develop coding skills that would help me both with my 2270 Data Structure and Algorithms class, and to practice learning a new coding language as a professional skill. I initially started with the intention of working 20-30 minutes a day, totaling three hours a week, and posting weekly on Piazza. I entered this course feeling it was going to be as easy as working through a second Zybook program on the side. 

  Over the semester I was able to complete 13 exercises with 4 more in progress. I also created and have updated this github page to document this course. More importantly, I feel I learned the following higher-level skills:
* I personally do better in 1-to-2-hour blocks when it comes to solving problems, zybook lessons I could handle in the 20-30 minutes if required.
* My C++ coding has improved tremendously between both the 2270 Data Structures course and the Exercism exercises. 
I am better able to review my code and look for inefficiencies. I often found I could write a helper function instead of writing the same code multiple times. Sometimes I could find clever ways simplify my approach to the problem or just use preexisting libraries. 
* I improved my ability to search for and read the error codes and determine what they said about my code, and which ones could be safely ignored. In fixing the first error, it would be able to fix later errors. A big learning point was when I finally realized a lot of these errors related to the test cases. Because was different than I had experienced using VS Code, with the 2270 exercises, where errors were purely my code, and the tests were separate. I also learned to read the test code to determine what was required of me. Compared to 2270, I spent more time trying to get code to run error free before considering the test cases. 
* I learned some of the distinction between how I think and code as a student compared to how I may code as a professional. This includes starting with more of a mindset that this will give me problems to solve, but not necessarily teach me to code, which was different than any of the learning environments I had experienced so far. I also started by approaching every problem with how I could create all the functions I needed from scratch, much like we were building the data structures in 2270. Instead, I could lean on libraries to provide functions and write much simpler, cleaner code. 
* I became much more comfortable reading and referencing the cplusplus.com documentation as my primary source when troubleshooting a function. 

If I could give another student starting this same independent study advice, I would give the following: 

* Focus on the zybook refresher for the first week or two, as it has the basics you need to start the Exercism. 
* Ask for help early. Schedule office hours at the end of the first week, or beginning of the second, when you approach the Exercism exercises. Better to ask 30 minutes of simple questions than to spend two weeks spinning your wheels and getting frustrated. 
* Feel free to jump between exercises, they are not necessarily arranged in an order that is a natural progression.
* Learn to read the tests and search the error codes, they will guide you to what code you need to write. Get comfortable with the documentation.
* Every few weeks go back and see if you can solve the earlier problems in simpler ways. This includes looking at community solutions to see if you can understand how other people solved the problem. That said, don’t worry if you can’t understand some of those solutions. 
* One of the most useful and my most often ignored lessons from Prof. Knox: Write out what steps you need to accomplish as comments, then go back and code them. If you have a clear understanding of what you’re trying to accomplish it makes the coding much easier. For example, my class projects were a lot easier to code than my Exercism projects because this is where I followed his advice most. 
* Specific for this course: write your posts after every session. The couple times I would code for an hour then write a quick summary led to much better weekly posts than if I tried to remember what I accomplished later. Set a reminder at the same time each week to update Piazza with what you learned. In general take notes when you learn something.

As I reviewed my posts from this course, I could see where I started to get frustrated, break down, and blame the tools and the way Exercism is set up for my lack of progress. Instead, I should have focused on where I could learn the skills I need for each problem and return to solve it. I think one of the most valuable lessons I can take forward is to appreciate what any course or program offers, instead of focusing on what it doesn’t--and above all, ask for help when needed. 

