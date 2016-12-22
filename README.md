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
<li>A Toolstrip at the top that contains command buttons and icons for commonly used functionality in MATLAB. It is organized by tabs that group related functionality. The toolstrip contains a number of global tabs, such as the Home tab, that are always present, and contextual tabs that become available when you need them.</li>
<li> A Command window that allows you to enter and execute MATLAB commands and functions (a dedicated set of code lines designed to perform specific tasks) <br>
<pre><code>Try typing 2+3 in your command window. We can essentially use this part of MATLAB as a calculator.</code></pre></li>
<li>	A Current folder panel that lists all the files and folders present in your current working directory. MATLAB can access all the files that are present here through code. If we want to access files that are not in our current directory using MATLAB code, we can either manually move the files from their current location or change the current folder to the folder containing the necessary files. This can be done using the ```cd``` command followed by the location of the folder we want to change it to. For example, if I want to change my working directory to a folder in C drive called 'MatExample', I would type in:<br>
<pre> <code> cd 'C:\MatExample' </code></pre> </li>
<li>	A Workspacethat lists all the variables and functions currently loaded into the memory. You can view the contents of the variable by double clicking on the name of the variable in the workspace. </li>
<li>	An Editor for writing, testing and saving code. </li>
</ul></p>
<p>

### Getting Help in MATLAB
 
If you ask me what I like most about MATLAB’s interface, my answer will always be the ability to quickly and efficiently look for help. MATLAB comes equipped with a richly documented help and support functionality that you can access anytime. We’ve enumerated several ways of accessing MATLAB Help below. <br>
<p><ul>
<li> Type help and exact name of the command/function, separated by a space, in command window. </li>
<li> Write your query in ‘Search Documentation’ field located on top right corner of MATLAB interface.</li>
<li> Open MATLAB documentation from ‘Help’ menu on toolstrip.</li>
<li> Search the internet! Remember Google is your best friend.</li>
</ul></p>


### Glossary
