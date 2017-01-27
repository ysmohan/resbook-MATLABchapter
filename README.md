# Introduction

Matlab is a programming language used for data analysis, modeling, algorithm development, testing and application design. Matlab is used extensively for data analysis by engineers, scientists, researchers and statisticians. 


## Learning Objectives:

- Be Familiar with the MATLAB environment.
- Be able to write and run code from the command window.
- Be able to perform simple calculations in MATLAB.
- Be able to visualise data.
- Be able to use MATLAB functions.
- Be able to extract raw data from published figures.

## Contents:

The rest of this chapter is set out as follows:
<p><ul>
<li> <a href="#context"> Context </li>
<li> <a href="#bg"> Background </li>
<li> <a href="#ex"> Example </li>
<li> <a href="#TheMAT"> The MATLAB environment </li>
<li> <a href="#MatnVec"> Matrices and Vectors </li>
<li> <a href="#plot"> Plotting </li>
<li> <a href="#Functions">Functions</a> </li>
<li> <a href="#Ext">Extracting data from published figures</a> </li>
<li> <a href="#Plen"> Plenary </a> </li>
</ul></p>

# Context
This part tells you what you need to know before starting out programming in MATLAB

## Installing MATLAB

MALTAB can be purchased and downloaded from the official Mathworks website (https://au.mathworks.com/). Refer here for more detailed installation instructions.

### MATLAB Interface – First Steps

Once MATLAB is successfully installed on your computer, you will find a ‘MATLAB app icon ![alt tag](https://github.com/ysmohan/resbook-MATLABchapter/blob/master/Figures/MATLABicon.png) ’ appear in the start menu if you are on Windows or in Launchpad/ Applications folder for Mac. Click on  ![alt tag](https://github.com/ysmohan/resbook-MATLABchapter/blob/master/Figures/MATLABicon.png) to launch MATLAB interface. If everything is working perfectly, you should see a window appear similar to Fig. 1

![alt tag](https://github.com/ysmohan/resbook-MATLABchapter/blob/master/Figures/MatlabInterface.png)
Fig. 1 An example of a MATLAB interface.

### Anatomy of MATLAB interface

A typical MATLAB interface contains
<p><ul>
<li>The Toolstrip at the top that contains command buttons and icons for commonly used functionality in MATLAB. It is organized by tabs that group related functionality. The toolstrip contains a number of global tabs, such as the Home tab, that are always present, and contextual tabs that become available when you need them.</li>
<li> The Command window that allows you to enter and execute MATLAB commands and functions (a dedicated set of code lines designed to perform specific tasks) <br>
<pre><code>Try typing 2+3 in your command window. We can essentially use this part of MATLAB as a calculator.</code></pre></li>
<li>	The current folder panel that lists all the files and folders present in your current working directory. MATLAB can access all the files that are present here through code. If we want to access files that are not in our current directory using MATLAB code, we can either manually move the files from their current location or change the current folder to the folder containing the necessary files. This can be done using the 'cd' command followed by the location of the folder we want to change it to. For example, if I want to change my working directory to a folder in C drive called 'MatExample', I would type in:<br>
<pre> <code> cd 'C:\MatExample' </code></pre> </li>
<li>	The Workspace that lists all the variables and functions currently loaded into the memory. You can view the contents of the variable by double clicking on the name of the variable in the workspace. </li>
<li>	The Editor for writing, testing and saving code. </li>
</ul></p>

### Getting Help in MATLAB
 
If you ask me what I like most about MATLAB’s interface, my answer will always be the ability to quickly and efficiently look for help. MATLAB comes equipped with a richly documented help and support functionality that you can access anytime. We’ve enumerated several ways of accessing MATLAB Help below. <br>
<p><ul>
<li> Type help and exact name of the command/function, separated by a space, in command window. </li>
<li> Write your query in ‘Search Documentation’ field located on top right corner of MATLAB interface.</li>
<li> Open MATLAB documentation from ‘Help’ menu on toolstrip.</li>
<li> Search the internet! Remember Google is your best friend.</li>
</ul></p>

### Lesson Material

A digital copy of the lesson material and the challenge files can be found here- Provide GitHub link.

### Glossary

And finally before we start off, here are a list of terms you need to be familiar with to make the best of this chapter-

- Algorithm: A structured code implementing a method to solve a specific problem.
- Variable: A variable is a container where you store values and the values can be changed according to our needs.
- 

# Background

Before MATLAB, number curnching was a complicated task and involved a programming language called FORTRAN. While it was the major tool in the number crunching business, it had its own limitations. For instance, writing the code to perfrom a simple task was complicated and did not always result in particulary efficient solutions. For decades, engineers all over the world kept writing algorithms over and over again to solve the same problem. To make the process of algorithm development efficient, the U.S government decided to hire experienced numerical analysts to develop standard collections of algorithms called 'libraries'. These libraries were freely available to everyone. In late 70s, One of the professors at Stanford, Cleve Moler, just wanted his students to be able to do some Maths using these libraries. However, he still thought that working with these libraries was a lot of work. So he developed MATLAB as an easier alternative. He specifically desinged this new tool to be interactive, intuitive and to be able to deal with large datasets. In 1984, Jack Little, an engineer, came across MATLAB and realised its commercial potential. Along with Clever Moler, he rebuilt MATLAB on another programming language called C and established Mathworks. <br></br>

Because of its lineage, MATLAB is essentially used in the science and engineering communities when it comes to research and it does certain things like matrix manipulations really really well. How is this useful to you? Well, a lot of datasets come as matrices that can be manipulated in MATLAB. For example, excel spreadsheets can be converted into matrices. Images can be converted into matrices. MATLAB allows you to easily work with these matrices.


# Examples 
In academia, MATLAB is used in many capacities. It is used for data analysis, visualisations, and for modelling and prediction. MATLAB toolboxes have also contributed to some major discoveries around the world. In this part, we will look at some examples of how MATLAB can be useful in various aspects of research.

### Data Analysis and Visualisation: A climate Science Story

Some of you may have seen the climate spiral — a graph of spiralling temperatures from the late 1800s to now, showing an increase in global temperature.

![alt tag](http://blogs.reading.ac.uk/climate-lab-book/files/2016/09/spiral_aug2016.gif). 

Dr. Ed Hawkins,Climate scientist in the National Centre for Atmospheric Science (NCAS) at the University of Reading, used MATLAB for data analysis and visualisation and here is what they had to say about it:
“I use MATLAB for data analysis because it can handle the very large datasets produced in climate science.” – Dr. Ed Hawkins
This quote highlights one of MATLAB's important functionalities, i.e., it deals well with large datasets and this is because of it's ability to do matrix manipulations. It also highlights MATLAB's advanced graphic capabilities.


### Customised MATLAB tools and gravitational waves

The detection of gravitational waves was arguably one of the most exciting scientific discoveries of this century. It was proof of a 100 year old problem and was detected by an advanced LIGO (aLIGO). Not to detract from the news but MATLAB was used in multiple aspects of the underlying research.  A MATLAB toolbox called Optikle was custom built to simulate the aLIGO so the researchers could better understand the behaviour of the complex aLIGO system. Another MATLAB based tool called GWINC was used to simulate the noise performance of the aLIGO system given certain parameters. Further, MATLAB also proved friendly to the collaborative nature of the project. The description of on image on the cover of the LIGO magazine said this: " A MATLAB-based procedure developed by Darkhan Tuyenbayev (graduate student from UTB) and implemented by Thomas Abbott (graduate student from LSU)... ". Apart from sweet intra-country collaborations, the ease with which MATLAB code can be shared amongst researchers is also demonstrated here. Infact, the project had "1000 scientists and engineers focused on the task by 2015", the gravitational wave was detected between observatories in Washington state and Lousiana operated by Caltech and MIT. The publication mentioned collaborators from all over the world including Australia. It's use in the process shows how flexible MATLAB toolboxes can be. Here are some links if you need more information.

 - [MATLAB blog](http://blogs.mathworks.com/headlines/2016/05/19/100-years-later-a-faint-chirp-proves-einstein-was-right/?s_eid=PSM_gen&hootPostID=03fee7910bfb1984713095cd054d6c74) 
 - [A list of Mark Evans Publications](https://emvogil-3.mit.edu/~mevans/papers.html)
 - [Advanced LIGO anticipated Sensitivity Curves] (https://dcc.ligo.org/public/0002/T0900288/002/AdvLIGO%20noise%20curves.pdf)



Without futher ado, let's begin our MATLAB journey.

<h2 id="MatnVec"> Matrices and Vectors</h2>

Matrices are the basic data structure in MATLAB.
A matrix is a rectangular table of numbers.
Any rectangular table of numbers can be thought of as a matrix;
one example is a spreadsheet of numerical data.

The reason matrices are so important is because they can be used to encode
information about a lot of different types of mathematical objects.
There are also rules which let us combine matrices together,
called matrix operations.
Matrix operations are analogous to arithmetic between numbers,
and are even still called addition and multiplication.

A matrix that has only one column or only one row is called a vector.
In this sub-section, we are going to do some basic matrix and vector operations.


![alt tag](https://github.com/ysmohan/resbook-MATLABchapter/blob/master/Figures/RowsandColumns.PNG)

We can simply add two matrices or vectors by using the ```+``` sign or subtract them using the ```-``` sign. To multiply and divide we use ```.*``` and ```./```. We use the ```.``` terminology to make sure the operation we are performing applies to each individual element in our matrix or vector.

##### Note: When performing operations such as addition, subtraction, multiplication or division on two matrices, then need to be of the same size.

<h3 id= "Challenge1"> Challenge #1 </h3>

<pre><code>% Copy and paste the following code into the command window.
X= [1:5];
Y= [1:2:10]; % We are making two vectors and calling them X and Y. These will appear in our workspace.

% Add the two vectors.
% Now multiply them.
</code></pre>

<hr> </hr>

<h2 id= "plot"> Plotting </h2>

We created two vectors, X and Y. We can plot them individually by clicking on the vector in the workspace, going to the plots tab and clicking plot.

![alt tag](https://github.com/ysmohan/resbook-MATLABchapter/blob/master/Figures/plotting.png)

<h3 id= "Challenge2"> Challenge #2 </h3>

<pre><code>% Use the scatter plot option in the PLOTS tab to make a scatter plot of X and Y.
</code></pre>

## Functions

### <i>A function is the powerhouse of a MATLAB code</i>

In this section, we will introduce the concept of calling built-in or user-defined functions in MATLAB. 

TIP: If you have prior coding experience, you might want to skip this section though if you are curious about the relationship between microwaving food and using a MATLAB function, we’ll suggest you to keep reading. 

A function is defined as a dedicated piece of code written to perform a specific programming task. Each function has a distinct name and can be ‘called’ by other functions or any other body of code. Generally, a function accepts some input variables called ‘arguments’ and returns an output. For instance, the function ‘plus(a,b)’ in MATLAB is used to calculate sum of two numbers. It accepts two input arguments ‘a’ and ‘b’ and returns the sum ‘a+b’ as output. It is possible for a function to have no input arguments or output.  

In order to better understand the concept of functions lets consider an analogy between a microwave and a MATLAB function. A microwave performs a specific task i.e. heating/cooking food just like a function. When using a microwave, we first open the door, place the food, close the door and hit the start button. Similarly, when calling a function in our code, we first write the name of the function, open the small brackets ‘(’ to indicate that now we are going to pass the input arguments, write all the required input arguments, and close the close the small brackets ‘)’. We then hit ‘enter’ to execute the function. Once the microwave is done heating or the function is done executing, we get the output. In case of the microwave	, the output is steaming hot food and for a function the output is usually one or more variables. 

![alt tag](https://github.com/ysmohan/resbook-MATLABchapter/blob/master/Figures/Function.png)

Now that we have a fairly clear idea of what a MATLAB function is and how it works, lets put our knowledge to practice. Go to the MATLAB interface and type the lines of code given below in the command window. 

<pre><code>A=10;
B = 20;
plus(A+B) </code></pre>

MATLAB comes equipped with a wide range of pre-defined functions to help us in developing our codes efficeintly and quickly.

TIP: Some of the most widely MALTAB funcitons are clc, plot, save, load, mean, std. You can go to MALTAB help and explore the available functions.

### User defined functions

This function loads an image/picture/photo into the workspace, allows the user to select pixels and converts each pixel location into a ‘data point’. 

### Description

‘You are a final year PhD student, and you have been working on understanding ‘velocity profile of a falling batman’ for past four years. 

During your research, you’ve collected and analysed a huge amount of data in MATLAB. Just before publishing your results, you found a top-secret government study on the same topic through Wikileaks. Now you want to compare your results with this new study but there is one hurdle – you’ve got no data from your rival study!

Luckily, you find a MATLAB function ‘getData’ that you can use to retrieve data from figures/ images in the government study, except there is one catch – there is no documentation of the function and you don’t know how to properly use it!  Your only resource is a jpg image ‘Batman.jpg’

Your task now is to figure out how to use the function properly and compare your results to the results of the government study.  Feel free to share your observations!’

TIP: You can download similarly designed challenges and helper files from the course Github repository.


### Bad Science!

So... it turns out that your results were the same as government study. You take this particularly badly. After years and years of blood and sweat, all your work turned out to be for nothing. You wanted to make great changes to the world using science. But academia being the cruel mistress she is broke you. You decided to turn to industry ("the lucrative, dark side of science"). However, poor judgement on your part followed by numerous bad
decisions left you working for the Big Bad — Evil Corp, aka E-Corp, headed by CEO Big Frump. Now E-Corp was not a good organisation. They had numerous dealings in
non-renewable energy sources and rumour has it that their scientists practiced "Bad Science". Their key motto was "Correlation = Causation" —
the simple principle that just because two events are related, one must have caused the other. Their arguments frequently involved repeatedly
yelling "Wrong" and their favorite explanation was "Because I said so."
Seduced by the ease of non-reason and misinformation, you have indeed turned to the dark side.

### The Task
In the face of damning evidence suggesting that global temperatures are indeed rising as shown in example 1, Big Frump himself has decided to put together a task
force. You are a part of this task force of like-minded immoral "scientists". Your task is to come up with the worst possible climate hypothesis. You have trawled through the internet and found numerous data sets which can be found here and you need to use your MATLAB skills to find a relationship between them. Through this bad science you will help E-Corp perpetrate hate and fear. You will help Big Frump rule the post-apocalyptic wasteland that will be his one lasting legacy.
Mwahahahaha!



<pre><code>
In order to successfully complete the challenge, you need to do the following:

Step 1: Download the 'masterchallenge.mat' and 'variabledesc.txt' files into the MasterChallenge folder you created in challenge 1. variabledesc.txt contains a description of all the vectors you found on the Internet.
Step 2: Ensure that the folder MasterChallenge is your current working directory. Double click on masterchallenge.mat. This should populate your workspace with the different vectors that you found on the internet.
Step 3: Using scatter plots, find any relationship between the variables in your workspace.
Step 4: Tweet your hypothesis and tag #ResBaz

</code></pre>

# Plenary

At the end of this chapter, you would have learned how to:

- Change the current directory
- Load vectors/matrices into the workspace.
- Use the command window to perform simple arithmetic operations on your matrices and vectors.
- Use the Plots tab to perform some exploratory data analysis.
- How to use functions and the need for them.
- How to extract data from a figure and then re-plot them.

If you want to learn more about using MATLAB, you can find our course material here:

LINKs to be added.



