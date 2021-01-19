# Theory of Algorithms Project 2021

#### Due: last commit on or before April 30<sup>th</sup>, 2021


These are the instructions for the assessment for Theory of Algorithms in 2021.
This assessment contains a number of components but overall it is worth 100% of the marks for the module.
All aspects of the project will be covered during the semester.
You should complete and commit the parts of the project, following the timelines indicated by the lecturer during the semester.


In this project you must write a program in the C programming language to calculate the SHA512 value of an input file.
Your program must take the name or path of the file as a command line argument and output the SHA512 value of it.
The program must be included in a GitHub repository along with other files detailed below.
The URL for the repository should be submitted using the on the Moodle page.
Your repository must be set to private from the beginning.


The program must be coded from scratch.
You cannot use any external libraries other than what is included in the C standard library.
Your program must compile using gcc and you must include a `Makefile` which compiles it upon `make` being called in the project folder.
You must also include tests which run upon `make test` being called, as will be described in lectures.


You must also include in your repository an appropriate `.gitignore` file and a `README.md`.
The README must cover the following:

- **Description** of what is contained in the repository, pitched at an outsider.
- **Compilation** instructions stating how to compile, test, and run your program.
- **Explanation** of what the SHA512 algorithm is and why it is important.
- **Analysis** of how secure the algorithm is, including the complexity of reversing it.

Please read the **Using git for assessments** document on the Moodle page which applies here.
As always, you must also follow the code of student conduct and the policy on plagiarism.


#### Marking scheme

The following marking scheme will be used to mark your submission out of 100%.
The examiner's overall impression of your submission may influence marks in each individual component.
It is important that your submission provides direct evidence of each of the items listed in each category.
For instance, your commit history should demonstrate and provide evidence that you had a pragmatic attitude to completing the assessment.
Likewise, your submission should have references in it to demonstrate that you considered the literature and the work of others.
  

| Weight | Category | Description |
|---|---|---|
|25% | Research | Evidence of research performed on topic; submission based on referenced literature, particularly academic literature; evidence of understanding of the documentation for any software or libraries used. |
|25% | Development | Environment can be set up as described; code works without tweaking and as described; code is efficient, clean, and clear; evidence of consideration of standards and conventions appropriate to code of this kind. |
|25% | Consistency | Evidence of planning and project management; pragmatic attitude to work as evidenced by well-considered commit history; commits are of a reasonable size; consideration of how commit history will be perceived by others. |
|25% | Documentation | Clear documentation of how to create an environment in which any code will run, how to prepare the code for running, how to run the code including setting any options or flags, and what to expect upon running the code. Concise descriptions of code in comments and README. |