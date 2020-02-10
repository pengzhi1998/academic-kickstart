+++
# Date this page was created.
date = 2020-01-07T00:00:00
layout = "project"

# Project title.
title = "Compiler for simple C++"

# Project summary to display on homepage.
summary = """
 This course project was to implement a simple compiler for C++. <br>
 Got A+ for this course!
 """

tags = ["Programming","CS"]

# Optional external URL for project (replaces project detail page).
external_link = ""
+++

In UCSB, I took the course CS160 and finished the projects. It contained 6 projects. The first two of 
them are individual missions. Project 3-6 are an intact task. <br><br>
In project 2, I implemented an independent scanner and LL(1) parser without any tools. But we
were provided with the main structure of the code. We just needed to fill in the important parts. <br><br>
For the following projects, I used lex and yacc (these are fornt-end generators) to build LR parsers.
Project 4 was relatively easy. We built an abstract syntax tree (AST) and got familiar with the AST classes
of the project and Yacc's actions. This step could make the semantic analysis and code generation
easier.  <br><br>
Project 5 was to analyze semantic properties of C++ programs and perform type checking. There are many
checks which I needed to do: more than one main function, main() has no arguments, duplicate procedures,
duplicate variables, undefined procedures and so on. <br><br>
To finish the whole project, the last step was to generate X86 code from the C++ programs in
project 6. <br><br>
There is no doubt that the projects for CS160 are really well designed. I have really learnt a lot from all
of them! If you are interested in them, click
[here](https://sites.cs.ucsb.edu/~chris/teaching/cs160/index.html) (Actually my instructor was Assistant
Professor Yufei Ding, however her url for this course is not working these days. Luckily, I found the 
requirements for the course projects from Professor Kruegel which are similar to what I have worked
on).
Meanwhile, you could find my solutions for the homework
[here](https://github.com/pengzhi1998/Compiler-for-simple-cpp-of-UCSB-CS160). I didn't got full score for
P2. <br>
