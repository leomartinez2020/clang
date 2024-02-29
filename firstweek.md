# First Week

![The seven steps](/assets/clang-seven-steps.png)

The programmer begins by devising an algorithm for the task and splits the planning phase into four steps. After creating a proper algorithm,
the programmer proceeds to Step 5, translating the plan into code. This phase may start slowly due to unfamiliarity with syntax, but it is
generally straightforward. If the algorithm includes complex steps, they are turned into separate programming tasks.

The next step, Step 6, involves testing the implemented code to uncover errors in the algorithm or implementation. If errors are found, the
programmer proceeds to Step 7, debugging, to identify and fix the issues. The programmer may need to revisit algorithm design or code
translation to address errors. This testing and debugging process is repeated until the programmer is convinced that the program is correct,
although no amount of testing can guarantee absolute correctness. The programmer's confidence in the code's correctness increases with more testing.

There should be a disciplined approach to algorithm writing, instead of haphazardly throwing code together and fixing issues later. 
The analogy of a chaotic sandwich-making process resulting in kitchen disasters illustrates this point.
Novice programmers often dive into coding without a clear plan, leading to extensive troubleshooting and tangled code.

![The seven steps](/assets/clang-code-planning.png)

The recommended approach is to devise an algorithm systematically, as depicted in a figure, with each step discussed in detail.
Notably, code translation should only occur after testing the algorithm by hand. By planning thoroughly and translating accurately,
the code is expected to work correctly on the first attempt. If issues arise, the solid plan serves as a guide for debugging.

## Step 1
Step 1 of designing an algorithm involves working through an example of the problem manually, selecting specific values for parameters and 
possibly drawing diagrams for clarity. It's essential to be precise during this step, as it lays the groundwork for subsequent stages. 
Examples such as determining if a number is prime or computing exponents illustrate this process. If difficulties arise at this stage, 
it could be due to a lack of clarity in the problem or a lack of domain knowledge. Resolving these issues may require consulting experts or 
references in the relevant field. Additionally, domain knowledge from various fields, including computer science and engineering subfields, 
may be necessary for solving specific types of problems.

## Step 2
In Step 2 of the algorithm design process, the focus is on articulating the steps taken to solve a specific problem instance in Step 1. 
The goal is to create a clear set of instructions that anyone else could follow to replicate the solution for that instance. If multiple 
instances were worked on in Step 1, Step 2 is repeated for each one. The challenge lies in being precise and not overlooking small details or 
implicit steps. The text highlights the importance of avoiding assumptions or relying on common sense, using the example of a peanut butter and 
jelly exercise to illustrate potential pitfalls. The provided example of computing x to the y demonstrates the creation of precise and unambiguous 
steps suitable for a computer to follow.

## Step 3
In Step 3 of the algorithm design process, the focus is on generalizing the specific steps formulated in Step 2 to create a more versatile 
algorithm applicable to a broader class of problems. This generalization involves replacing specific values with mathematical expressions of 
parameters. Two common strategies are highlighted: replacing specific values with variables and identifying repetitions in steps. The example 
of computing 3^4 illustrates the process, showing the replacement of specific values with variables and recognizing repetitive patterns.

Generalization may involve adjusting steps to ensure exact repetition, and the number of repetitions often depends on the parameters involved. 
Care is taken not to make assumptions about repetitions based on coincidental values. The text emphasizes the need to generalize specific values 
to functions of parameters. If difficulties arise in identifying patterns, revisiting Steps 1 and 2, and working on more instances of the problem, 
can provide additional insights. The process is likened to writing 'pseudo-code,' a method commonly used by programmers to design algorithms 
before implementing them in a specific programming language.

# Step 4
In Step 4 of the algorithm design process, the primary objective is to test the algorithm to ensure its accuracy before further progress. 
This involves executing the algorithm manually with different parameter values than those used during its design. By comparing the algorithm's output to the correct answers, the designer can identify any errors. While testing builds confidence in the algorithm, it cannot guarantee correctness; formal mathematical proof is the only means of complete assurance, although it is not covered in this specialization.

Common mistakes, such as misgeneralizing in Step 3, can be detected through testing. If a problem arises, revisiting Steps 1 and 2 for the 
specific test case is recommended. Another common mistake is neglecting certain cases, as illustrated in the example of computing x^y where 
the case y = 0 was not considered initially. Corrections may involve adjustments to the generalizations made in Step 3.

The text emphasizes the importance of determining good test cases, suggesting the inclusion of various cases that produce different 
answers and exploring corner cases. When problems are detected during testing, it is advised to return to Steps 1 and 2 for more information 
or insight into the correct generalization. The overall goal is to refine and retest the algorithm until confidence in its correctness is achieved.

