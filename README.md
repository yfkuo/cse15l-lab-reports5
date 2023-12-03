# Lab Report 5 - Putting it All Together (Week 9)

## Part 1 – Debugging Scenario
Design a debugging scenario, and write your report as a conversation on EdStem. It should have:

1. The original post from a student with a screenshot showing a symptom and a description of a guess at the bug/some sense of what the failure-inducing input is.

- Hi TA,
  I ran my code but it seems like there's a bug situation going on, but I am not sure how to fix it.
  I am guessing the bug must be somehow related to a failure-inducing input inside ListExamplesTests.java, but I am not too sure which part of the code I did wrong in ListExamples.java to trigger.(tbd)

- Here is the screenshot for the symtom output:
  -  [Image]!(test_trigger.png)
 
- Here are the screenshots of how my ListExamples.java and ListExamplesTests.java files look like:
  -  ListExamples.java: [Image]!(ListExamples.png)
  -  ListExamplesTests.java: [Image]!(ListExamplesTests.png)

2. A response from a TA asking a leading question or suggesting a command to try (To be clear, you are mimicking a TA here.)


3. Another screenshot/terminal output showing what information the student got from trying that, and a clear description of what the bug is.


4. At the end, all the information needed about the setup including:
- The file & directory structure needed:
  - [Image]!(file_directory_structure.png)
 
- The contents of each file before fixing the bug:
  -  ListExamples.java: [Image]!(ListExamples.png)
  -  ListExamplesTests.java: [Image]!(ListExamplesTests.png)
  -  test.sh: [Image]!(test.png)
 
- The full command line (or lines) you ran to trigger the bug
  -  I put my command lines in a bash script called test, then I ran bash test.sh to trigger the bug.
  -  [Image]!(test_trigger.png)
  -  [Image]!(test_jdb.png)
 
- A description of what to edit to fix the bug:
  - step
  - step
  
You should actually set up and run the scenario from your screenshots. It should involve at least a Java file and a bash script. Describing the bug should involve reading some output at the terminal resulting from running one or more commands. Design an error that produces more interesting output than a single message about a syntax or unbound identifier error – showcase some interesting wrong behavior! Feel free to set this up by cloning and breaking some existing code like the grading script or code from class, or by designing something of your own from scratch, etc.




## Part 2 – Reflection
In a couple of sentences, describe something you learned from your lab experience in the second half of this quarter that you didn’t know before. It could be a technical topic we addressed specifically, something cool you found out on your own building on labs, something you learned from a tutor or classmate, and so on. It doesn’t have to be specifically related to a lab writeup, we just want to hear about cool things you learned!



