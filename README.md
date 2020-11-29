< [GMIT Data Analytics](https://web.archive.org/web/20201029063153/https://www.gmit.ie/computer-science-and-applied-physics/higher-diploma-science-computing-data-analytics-ict) | [Table of Contents](https://github.com/E6985) | [README](https://github.com/E6985/pda-numpy-random/blob/master/README.md) >

<img src="img/gmit.png" />

## Programming for Data Analysis - Assignment 2020
## Due: last commit on or before November 22nd, 2020

Undergraduate of Computing (Data Analytics) at Galway-Mayo Institute of Technology. This repository contains the assignment instructions for the ``Programming for Data Analysis`` module in 2020. The assessment is worth 50% of the marks for the module. Four tasks completed in a single [Jupyter Notebook](https://github.com/E6985/pda-numpy-random/blob/master/Programming-for-Data-Analysis-Assignment-2020.ipynb).

## Assignment

Assignment concerns the numpy.random package in Python. Required to create a Jupyter Notebook explaining the use of the package, including detailed explanations of at least five of the distributions provided for in the package. Four distinct tasks are carried out in the Jupyter notebook.

Task 1. Explain the overall purpose of the package.

- Keywords: TRNG - PRNG - seed - Epoch - testing - simulation - real-world - modelling - synthesising - variables - distributions - relationship - random - generate - covid-19 - Leaving Certificate - bell curve - standard deviation - normal distribution - predict - numpy - pandas - scipy - matplotlib

- Introduction to the numpy.random package.

Task 2. Explain the use of the “Simple random data” and “Permutations” functions.

- Introduction to each of the simple random data - methods - integers - random - choice - bytes and the permutation - methods - shuffle - permutation.

- Detailed explanation of each methods parameters/return value with plots included when appropriate.    

Task 3. Explain the use and purpose of at least five “Distributions” functions.

- Includes commentary on discrete/continuous probability distributions. Explaining discrete and continuous variables with plots when appropriate.

- Introducing the discrete probability distributions - methods - binomial - poisson. Plots included when appropriate.

- Introducing the continuous probability distributions - methods - normal - uniform - chi-square. Plots included when appropriate.

- Given the detailed explanation of each method parameter in Task 2 - possible overlap - Task 3 is focused on the statistics behind the distributions.   

Task 4. Explain the use of seeds in generating pseudorandom numbers.

- Keywords: chance - predictable - bias - random - PRN - precalculated tables - mathematical formula - RAND - seed - linear congruential generator - Mersenne twister - permutated congruential generator

- Introduction to seeds with examples. Reviewing historical algorithms given there use even today, and the fact todays algorithm build upon.  

#### Marking Scheme
1. ``25%`` - Research - Investigation of the package as demonstrated by references, background information, and approach.

2. ``25%`` - Development - Clear, well-written, and efficient code with appropriate comments.

3. ``25%`` - Consistency - Good planning and pragmatic attitude to work as evidenced by commit history.

4. ``25%`` - Documentation - Concise descriptions and plots of theoretical and practical aspects of problems.

#### Getting Started
- Keeping in mind the impression given to someone who is looking at this repository, this submission is to provide direct evidence of each of the items listed in each category - ``Research`` - ``Development`` - ``Consistency`` - ``Documentation`` - refer ``Marking Scheme`` above.

1. Research:

	- ***Investigation of the package as demonstrated by references, background information, and approach***: References will be in the format:

		- [task-number.number] authorNames, referenceTitle, locationWebsiteBookVideo, dateMonthYear.

	- Demonstrating work completed in the submission with good references and not just for the problem but for level of understanding of the problem.

	- Code comments will include details of package, module, function, object, method, attribute if applicable to demonstrate understanding of software documentation and libraries used.

2. Development:

	- ***Clear, well-written, and efficient code with appropriate comments***: Using Jupyter Notebook markdown cells to summarise concise workings. 

	- Individual code statements will have single Jupyter Notebook code cell unless user-defined functions are created. 

	- As much as possible use ``Style Guide for Python Code`` [Guido van Rossum](https://web.archive.org/web/20201029095211/https://www.python.org/dev/peps/pep-0008/). User-defined coding conventions to be given separate section - refer ``Coding Conventions`` - within README as and when presented (note good commits do not change many different files - when a user-defined coding convention is represented within a Jupyter Notebook then the commit completed will include an update to this README file - this will be the only time this will happen given that to update README every time is wasteful):- 

3. Consistency:

	- ***Good planning and pragmatic attitude to work as evidenced by commit history***: This README will form the template for this and all future tasks/projects. Git commit to include within the blurb the number of days outstanding before deadline.

	- Endeavour to submit work every day worthy of a git commit. At best 4/5 times per week. Later presentation of topics/sections will require more commits to ensure equal proof of work for all before the deadline.

	- Correctly use git history by putting in a little blurb - 2/3 lines. 

	- Commits to highlight changes made since the last commit so that reviews of the git history can demonstrate compartmentation of work into the different sections.   

4. Documentation - 

	- ***Concise descriptions and plots of theoretical and practical aspects of problems***: Comments to be very concise for ease of readability. 

	- Descriptions of code requiring further explanation will be presented in Jupyter Notebook markdown cells prior to code execution.   

#### Considerations

- The four listed categories - ``Research`` - ``Development`` - ``Consistency`` - ``Documentation`` - are each worth 25%. 

- Designed not only to be about programming but also about looking at information - data - manipulating the data and coming up with techniques. 

- Sometimes the most complex algorithms are counter-intuitive but do work and have been proven to work. Sometimes only a few lines of code is required to complete a topic/section but to obtain full marks it is not good enough to submit the lines of code. Must explain how the algorithm was developed and the reasoning behind why/how the code works.

- Jupyter Notebook text formatting/presentation to be tidied up closer to the deadline.

#### Coding Conventions

- variable/name/functions - start with letters as follows

| Example       | Signify 		          |
| ------------- |:-----------------------:|
|	f        	|	user-defined function |

| Example       | Signify 		          |
| ------------- |:-----------------------:|
|	n        	|	name - no variables   |

#### Prerequisites

- Require Python to be loaded on your local machine. Recommend downloading and installing Anaconda.

https://www.anaconda.com/download/

#### Execute Jupyter Notebook

- The software must be downloaded and run on a machine as follows:

	- Clone the repository with the following command:

	``git clone https://github.com/E6985/pda-numpy-random.git``

    - Run Jupyter Notebooks from the repository with the following command:

	``jupyter notebook``

    - Open notebook - Programming-for-Data-Analysis-Assignment-2020.ipynb

    - Once running within the Jupyter environment can navigate with ease - links are plentiful.

	- Notebook links will not work on github given that github renders as static HTML.  