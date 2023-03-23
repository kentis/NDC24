# Green Software Development Workshop: Creating Experiments to Make Green Choices

## Part 1: Introduction

Welcome to the Green Software Development workshop focused on creating experiments to make green choices! In this workshop, you will learn how to design and conduct experiments to determine how to develop software that is environmentally friendly and sustainable.

### Objectives

The objectives of this workshop are:

* To understand the importance of green software development
* To learn how to design and conduct experiments
* Make green choices when writing software
* Have fun answering questions


### Anatomy of an experiment

The design and execution of rigourous experiments fit for publication in
academic journals is well out of the scope of this workshop. Instead we propose
a simple model for experiments designed to reduce uncertinty.

The figure below shows the general flow of an experiment. The first step is to
find a question. Step two is too design an experiment to answer, or reduce uncertanty, about the question and to create whatever software is needed to run the experiment. Then you run the experiment draw whatever conclusions
that are warrented and finally publish your results and, preferably, use them
to inform future decisinos.

![question -> design -> run -> publish](figures/experiment_flow.png "Experiment flow")



## Step 1: Identifying a Question

The best questions are the ones that informs an imediate decision or
satifies your curiosity. An example of such a question that might arise
when you are writing code might be what is actually the best way to
parse a simple date?

Since it may be hard to think of a question right on the spot when doing 
a workshop, we have compiled a list of questions. For each question, we have
provided example experiment designs and code. To get maximal effect of this workshop, you should only look at the designs for other questions for ideas on designing you own experiment to answer your selected question.

### List of questions

*Q1: What is the effect of declaring a value inside vs outside a loop in
    * Python
    * Java
*Q2: What is the effect of using async/await in c# where it is not entirly nessecary?
*Q3: What is the most efficient way to parse a date in Java?



## Step 2: Designing your Experiment

When designing an experiment it is useful to keep in mind that the
purpose of any measurement is to reduce uncertainty and not
to provide absolute proof. Also, if an experiment does not give any clear
answers, youo an always improve on the experiment to increase confidence
in your results. It can also be useful to vary the conditions uner wich
an experiment is conducted.

When designing an experiment where direct measurement is dificult, yuo first have to decide on proxies to measure. Perhaps the simplest way to create an experiment for measuring enecgy consumption is to measure time it takes to comoplete a task since time is strongly conrrolated with energgy use. 

Next, you should decide on what to measure. If your question is on the form
is it (much) more efficient to do x by doinx x rather than y, one strategy may be to implement one program that uses the x approach and one that uses y. An example of this, if we are interested in knowing wether one way of parsing dates is more efficient than another might be to create a program that times and performs the operation a number of times in onoe way, and another program that does the same and oonly differs by parsing the date in some ogther way. Another approach, shown below might be to do both sequentially in a single program.


## Step 3: Running the Experiment

To run the experiment, simply execute the program or programs youo created in the design phase. It may be useful to execure the programs several times and record the
results in order to ensure consistent result. Furthermore, it may also be usefull to vary the programs in oorder to discover hoow to best interpret the results.


## Step 4: Pulish Results

In this workshop we will present our findings to the group in the form of mini-presentations. We sugest the following format for your presentation:

1. The question you chose
2. The experimental design and code you created
3. The results from running
4. What you have learned


