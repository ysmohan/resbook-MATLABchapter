# Introduction

MATLAB is a programming language used extensively for data analysis in science and engineering.

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

Once MATLAB is successfully installed on your computer, you will find a ‘MATLAB app icon  ’ appear in the start menu if you are on Windows or in Launchpad/ Applications folder for Mac. Click on   to launch MATLAB interface. If everything is working perfectly, you should see a window appear similar to Fig. 1

### Anatomy of MATLAB interface

A typical MATLAB interface contains
<p><ul>
<li>The Toolstrip at the top that contains command buttons and icons for commonly used functionality in MATLAB. It is organized by tabs that group related functionality. The toolstrip contains a number of global tabs, such as the Home tab, that are always present, and contextual tabs that become available when you need them.</li>
<li> The Command window that allows you to enter and execute MATLAB commands and functions (a dedicated set of code lines designed to perform specific tasks) <br>
<pre><code>Try typing 2+3 in your command window. We can essentially use this part of MATLAB as a calculator.</code></pre></li>
<li>	The current folder panel that lists all the files and folders present in your current working directory. MATLAB can access all the files that are present here through code. If we want to access files that are not in our current directory using MATLAB code, we can either manually move the files from their current location or change the current folder to the folder containing the necessary files. This can be done using the 'cd' command followed by the location of the folder we want to change it to. For example, if I want to change my working directory to a folder in C drive called 'MatExample', I would type in:<br>
<pre> <code> cd 'C:\MatExample' </code></pre> </li>
<li>	The Workspacethat lists all the variables and functions currently loaded into the memory. You can view the contents of the variable by double clicking on the name of the variable in the workspace. </li>
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

## Background

### MATLAB
MATLAB was developed way in the late 70s by a professor who just wanted his students to be able to do some Maths. He originally built it on a programming language called Fortran which was complicated and MATLAB was meant to be an easier alternative. In 1984, some others joined this professor and rebuilt MATLAB on another programming language called C and also established Mathworks. Because of its lineage, MATLAB is essentially used in the science and engineering communities when it comes to research and it does certain things like matrix manipulations really really well. How would is this useful to you? Well, a lot of data sets come as matrices that can be manipulated in MATLAB. For example, excel spreadsheets can be converted into matrices. Images can be converted into matrices. MATLAB allows you to easily manipulate these matrices.

### Yamni

### Warda

<h2 id="ex"> Example </h2>
Other researchers around the world have used MATLAB analysis and data visualisation. Some of you may have seen the climate spiral — a graph of spiralling temperatures from the late 1800s to now, showing an increase in global temperature. For those of you who haven't, you can find it here: LINK. The researchers in this study used MATLAB for data analysis and visualisation and here is what they had to say about it:

“I use MATLAB for data analysis because it can handle the very large datasets produced in climate science.” – Dr. Ed Hawkins

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


![](RowsandColumns.PNG)

We can simply add two matrices or vectors by using the ```+``` sign or subtract them using the ```-``` sign. To multiply and divide we use ```.*``` and ```./```. We use the ```.``` terminology to make sure the operation we are performing applies to each individual element in our matrix or vector.

##### Note: When performing operations such as addition, subtraction, multiplication or division on two matrices, then need to be of the same size.

<h3 id= "Challenge2"> Challenge #2 </h3>

<pre><code>% Copy and paste the following code into the command window.
X= [1:5];
Y= [1:2:10]; % We are making two vectors and calling them X and Y. These will appear in our workspace.

% Add the two vectors.
% Now multiply them.
</code></pre>

<hr> </hr>

<h2 id= "plot"> Plotting </h2>

We created two vectors, X and Y. We can plot them individually by clicking on the vector in the workspace, going to the plots tab and clicking plot.

![](plotting.png)

<h3 id= "Challenge3"> Challenge #3 </h3>

<pre><code>% Use the scatter plot option in the PLOTS tab to make a scatter plot of X and Y.
</code></pre>


